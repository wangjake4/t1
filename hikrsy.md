代发 wailian999

read -rp "请输入: " ans
来源：http://dali.cqqwz.cn/Article/details/gtjekhqhpp.html

[R78] 交互式菜单
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqagqlkww.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.birdmap.top/Article/details/gtlhnimsag.html

[R79] 解析命令行选项
来源：http://dali.ivvv.top/Article/details/gtzxiijmgl.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xuanzx.com/Article/details/gteezbhgzg.html

[R80] 查看脚本执行耗时
来源：http://dali.0kj1m.cn/Article/details/gtuhuombmz.html

time ./run.sh
来源：http://dali.jinqigufen.top/Article/details/gtyikerjii.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtbzbgnurf.html

S. C / C++ 专题
来源：http://dali.shuidangran.top/Article/details/gtetfudxxf.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtbnmvjyrf.html

[S01] C：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuljclxqp.html

#include <stdio.h>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnkxkpijw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sxryk.cn/Article/details/gtzlkotpao.html

[S02] C：变量与格式化输出
来源：http://dali.feifeiyinyue.top/Article/details/gtcefjzpys.html

int a = 10; printf("%d\n", a);
来源：http://dali.hammf.cn/Article/details/gtxxdldswd.html

[S03] C：读入整数
来源：http://dali.hnqzz.top/Article/details/gtbuiihkzs.html

int x; scanf("%d", &x);
来源：http://dali.gaohongyu789.top/Article/details/gtqmgbkmed.html

[S04] C：字符串复制
来源：http://dali.hnqzz.top/Article/details/gtpasfehrm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ivvv.top/Article/details/gtzziztcxu.html

[S05] C：字符串长度
来源：http://dali.xziqi.cn/Article/details/gtxtjpacdo.html

strlen(s)
来源：http://dali.daxiang520.top/Article/details/gtbbfijgrd.html

[S06] C：字符串比较
来源：http://dali.zhengqikj.top/Article/details/gtliaotqgi.html

strcmp(a, b) == 0
来源：http://dali.chenlongwang.top/Article/details/gthicfocpm.html

[S07] C：数组遍历求和
来源：http://dali.pengpengdd.cyou/Article/details/gtbzgwsvdu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinghuilouyu.cn/Article/details/gtfnldcrxq.html

[S08] C：动态内存分配与释放
来源：http://dali.hysaishi.cn/Article/details/gtbthlnkef.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hywenlv.cn/Article/details/gtpsetuerx.html

[S09] C：结构体定义与初始化
来源：http://dali.hnxiangtu.top/Article/details/gtxmcugjhs.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.daxiang520.top/Article/details/gtapyyqkzg.html

[S10] C：指针与解引用
来源：http://dali.jianghu66.top/Article/details/gtybadpsks.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gtqsnrhqwi.html

[S11] C：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gtyyuuwkna.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gtfgpyzbxi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yvedp.cn/Article/details/gtqyzcyxdh.html

fclose(f);
来源：http://dali.sysykeji.top/Article/details/gtkeeuygjv.html

[S12] C：写文件
来源：http://dali.zhoulong.xyz/Article/details/gtavjeuflb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xylfe.cn/Article/details/gtmcjnohjz.html

[S13] C：宏定义
来源：http://dali.yj20258888.top/Article/details/gtyeehgtjt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinqigufen.top/Article/details/gtqpstlmsn.html

[S14] C：枚举
来源：http://dali.zhengqikj.top/Article/details/gtuxdqtmgm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ybcxt.top/Article/details/gtemxeoztj.html

[S15] C：类型转换
来源：http://dali.cdnleiting.top/Article/details/gtkfeyosnk.html

(double) a / b
来源：http://dali.yj20258888.top/Article/details/gtnagrzfvf.html

[S16] C：位操作置位
来源：http://dali.mhx1999.top/Article/details/gthdpjnxpy.html

x |= (1 << 3);
来源：http://dali.sysykeji.top/Article/details/gtducblgac.html

[S17] C：安全拼接字符串
来源：http://dali.hnqzz.top/Article/details/gtjbsfygez.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jyoumei.cn/Article/details/gtbstuynsh.html

[S18] C：命令行参数
来源：http://dali.hnxiangtu.top/Article/details/gttcmenpid.html

int main(int argc, char **argv)
来源：http://dali.bjfxy.top/Article/details/gtpkkmgyjj.html

[S19] C：快速排序
来源：http://dali.yj202588.top/Article/details/gtpenwoiad.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.fzhhl.top/Article/details/gtnddinrlo.html

[S20] C：二分查找
来源：http://dali.zhiwuduotai.top/Article/details/gtjdizpabz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhengqikj.top/Article/details/gtqebpirag.html

[S21] C：字符类别判断
来源：http://dali.sysykeji.top/Article/details/gtdymqwzcn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhixingplan.top/Article/details/gtdngzuosy.html

[S22] C：字符串转数字
来源：http://dali.tianlin.xyz/Article/details/gtekpzsvjj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.feifeiyinyue.top/Article/details/gtswtaenyx.html

[S23] C：随机数
来源：http://dali.fengsongda.top/Article/details/gtqhqonnei.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xuanzx.com/Article/details/gthotoghxv.html

[S24] C：获取本地时间
来源：http://dali.cqqwz.cn/Article/details/gtluegymqe.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj20258888.top/Article/details/gtramlisbw.html

[S25] C：内存拷贝
来源：http://dali.bjfxy.top/Article/details/gtalurnqzz.html

memcpy(dst, src, n);
来源：http://dali.jyoumei.cn/Article/details/gtekmwgmuo.html

[S26] C：内存清零
来源：http://dali.aibaodan.cn/Article/details/gtttjzrvnq.html

memset(a, 0, sizeof a);
来源：http://dali.iojbl.cn/Article/details/gtcijaldnw.html

[S27] C：定义常量
来源：http://dali.hywenlv.cn/Article/details/gtceexmgiu.html

const double PI = 3.14159;
来源：http://dali.bjfxy.top/Article/details/gtwpvhtcjz.html

[S28] C：静态变量
来源：http://dali.shzxlz.cn/Article/details/gtjxndlxhp.html

static int counter = 0;
来源：http://dali.daxiang520.top/Article/details/gttsdiwdmf.html

[S29] C：变参函数
来源：http://dali.smart0.xyz/Article/details/gtvnpjzvel.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.0kj1m.cn/Article/details/gthfkcjklr.html

[S30] C：头文件保护
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaxvflfqb.html

#ifndef X_H
来源：http://dali.vqdsnc.cn/Article/details/gtfsjcgtra.html

#define X_H
来源：http://dali.yanxiufei.cn/Article/details/gtmztmaqlg.html

#endif
来源：http://dali.yj20258888.top/Article/details/gtrwnkmbha.html

[S31] C++：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtldqupmle.html

#include <iostream>
来源：http://dali.shuidangran.top/Article/details/gtruhaymwv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvrkmaiwq.html

[S32] C++：字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnbnryzeu.html

std::string s = "hi";  s += "!";
来源：http://dali.wangdashe.top/Article/details/gttdnfxumz.html

[S33] C++：vector 增删
来源：http://dali.xinyue.icu/Article/details/gtjpvzpuni.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.bjfxy.top/Article/details/gtogwtqbsy.html

[S34] C++：遍历 vector
来源：http://dali.yuanzhike.top/Article/details/gtwgapkygs.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.daria6918.cn/Article/details/gtlycghfoo.html

[S35] C++：map
来源：http://dali.hnqzz.top/Article/details/gtyhtjhqon.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xinyue.icu/Article/details/gtbwjwxhyq.html

[S36] C++：unordered_map
来源：http://dali.yangfankeji.com/Article/details/gtlwrajiph.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuanzx.com/Article/details/gtfdifxxdq.html

[S37] C++：set
来源：http://dali.shzxlz.cn/Article/details/gtccsokxht.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj202588.top/Article/details/gtlgmzsmmi.html

[S38] C++：排序
来源：http://dali.zhixingplan.top/Article/details/gtusdgeigg.html

std::sort(v.begin(), v.end());
来源：http://dali.quarkkingdee.top/Article/details/gtrvcatnat.html

[S39] C++：自定义比较器排序
来源：http://dali.zhengqikj.top/Article/details/gtydnygcrk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.9152youxi.cn/Article/details/gtrnbmcbap.html

[S40] C++：查找元素
来源：http://dali.chenlongwang.top/Article/details/gtghspdzbf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gotoacloud.top/Article/details/gtsjdmsddu.html

[S41] C++：类与构造函数
来源：http://dali.jqgufenzy.top/Article/details/gtcvjfqecr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.andypj.xyz/Article/details/gtomxgcsbw.html

[S42] C++：继承与虚函数
来源：http://dali.zhongyouzk.top/Article/details/gtrhudhlpp.html

class B : public Base { public: void f() override {} };
来源：http://dali.hammf.cn/Article/details/gtqtbhkksh.html

[S43] C++：智能指针
来源：http://dali.mhx1999.top/Article/details/gtckgugnke.html

auto p = std::make_unique<int>(5);
来源：http://dali.hammf.cn/Article/details/gtfypbvald.html

[S44] C++：引用传参
来源：http://dali.hnxiangtu.top/Article/details/gtepjahsgg.html

void inc(int &x) { ++x; }
来源：http://dali.xinyue.icu/Article/details/gtkclyungz.html

[S45] C++：lambda
来源：http://dali.shuidangran.top/Article/details/gtmbbwddzp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.snrcjt.cn/Article/details/gtcrvwsofg.html

[S46] C++：函数模板
来源：http://dali.xinyue.icu/Article/details/gtmhxavjxf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yj20258.top/Article/details/gtkehyxvpv.html

[S47] C++：结构化绑定遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaivkpnct.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj20258.top/Article/details/gtxqhwsspt.html

[S48] C++：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gtoscscgbr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.quarkkingdee.top/Article/details/gtuzhiohjz.html

while (std::getline(in, line)) { }
来源：http://dali.yongpay.top/Article/details/gtgvexcwyb.html

[S49] C++：写文件
来源：http://dali.wangshuangyany.cn/Article/details/gtjdehovuj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyzutlkbl.html

[S50] C++：格式化数字
来源：http://dali.jinqigfzy.top/Article/details/gtasftcdaa.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gtdkdpnvzc.html

[S51] C++：显式类型转换
来源：http://dali.yongpay.top/Article/details/gtlnoqvsks.html

static_cast<double>(a) / b
来源：http://dali.hywenlv.cn/Article/details/gtccbfogsf.html

[S52] C++：const 与 noexcept
来源：http://dali.9152youxi.cn/Article/details/gtrblrczcw.html

int size() const noexcept { return n_; }
来源：http://dali.9152youxi.cn/Article/details/gtkycxbckn.html

[S53] C++：移动语义
来源：http://dali.daxiang520.top/Article/details/gtpcfxqotj.html

std::vector<int> w = std::move(v);
来源：http://dali.daxiang520.top/Article/details/gttrcwsinp.html

[S54] C++：异常处理
来源：http://dali.yj20258888.top/Article/details/gtgmbjcvch.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenzaomai.com/Article/details/gtbttwajfh.html

[S55] C++：结构化绑定
来源：http://dali.jinqigufen.top/Article/details/gtvlgxshxv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.fzhhl.top/Article/details/gtvxafxzcg.html

[S56] C++：optional
来源：http://dali.jlsjyb.cn/Article/details/gtmbpygzgv.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnxszbvyq.html

[S57] C++：编译期常量
来源：http://dali.zhongyouzk.top/Article/details/gtchlivolt.html

constexpr int N = 10;
来源：http://dali.redwolf501.top/Article/details/gtpyprarho.html

[S58] C++：命名空间
来源：http://dali.jinqigfzy.top/Article/details/gtnioiojxy.html

namespace ns { int f() { return 1; } }
来源：http://dali.quarkkingdee.top/Article/details/gtwtrkmfbw.html

[S59] C++：静态断言
来源：http://dali.yuanzhike.top/Article/details/gtdurvnvrj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.svipenyu.cn/Article/details/gtbpvwexrg.html

[S60] C++：遍历并删除元素
来源：http://dali.cheryme.top/Article/details/gtbuztvdgv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yvedp.cn/Article/details/gtfoyqxais.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtzdhgnthz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jqgfzy.top/Article/details/gtehuxqjgh.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtxwlzreay.html

[T01] Kotlin：Hello World
来源：http://dali.cashguo.top/Article/details/gtbeslsfta.html

println("Hello")
来源：http://dali.fzhhl.top/Article/details/gtxcquahbt.html

[T02] Kotlin：变量
来源：http://dali.vqdsnc.cn/Article/details/gtgdvkhyxh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yongpay.top/Article/details/gtgtacomvp.html

[T03] Kotlin：字符串模板
来源：http://dali.quarkkingdee.top/Article/details/gtuvtjwwat.html

"值: $b"
来源：http://dali.guowangkeji.top/Article/details/gtgyvfltpi.html

[T04] Kotlin：空安全
来源：http://dali.snrcjt.cn/Article/details/gtfdyibagy.html

val n: String? = null;  n?.length
来源：http://dali.cucudq.cn/Article/details/gtywxckmdz.html

[T05] Kotlin：when 表达式
来源：http://dali.hnxiangtu.top/Article/details/gtemczoklg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinqigfzy.top/Article/details/gtcxobyeim.html

[T06] Kotlin：集合映射
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxkxsbezz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.haohaochexian.top/Article/details/gthibcyvzm.html

[T07] Kotlin：集合过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpfwttwfg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yuxming.cn/Article/details/gtpdbaqvux.html

[T08] Kotlin：数据类
来源：http://dali.zhaomingkeji.xyz/Article/details/gthdemyzwx.html

data class User(val name: String, val age: Int)
来源：http://dali.birdmap.top/Article/details/gtkfymltgf.html

[T09] Kotlin：扩展函数
来源：http://dali.daxiang520.top/Article/details/gtcjxwsmty.html

fun String.exclaim() = this + "!"
来源：http://dali.nanxuanxn.top/Article/details/gtzrdqbpmw.html

[T10] Kotlin：默认参数
来源：http://dali.xuetiantiany.cn/Article/details/gtidbvpmhu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shanyushiyangtech.top/Article/details/gtsbdoclnu.html

[T11] Kotlin：协程
来源：http://dali.zycfv.cn/Article/details/gtybcghann.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hnxiangtu.top/Article/details/gtbwxmsxwo.html

[T12] Kotlin：解构声明
来源：http://dali.cqqwz.cn/Article/details/gtzxjgjjkt.html

val (a, b) = Pair(1, 2)
来源：http://dali.cucudq.cn/Article/details/gtejpmwiql.html

[T13] Kotlin：只读 Map
来源：http://dali.yj20258888.top/Article/details/gtwvddbidf.html

val m = mapOf("a" to 1)
来源：http://dali.zhixingplan.top/Article/details/gtirydtrgh.html

[T14] Kotlin：循环
来源：http://dali.svipenyu.cn/Article/details/gtnbnjqdjx.html

for (i in 1..10) println(i)
来源：http://dali.sufxvd.cn/Article/details/gtawftaovn.html

[T15] Kotlin：接口
来源：http://dali.yonumen.top/Article/details/gtflsujbks.html

interface Shape { fun area(): Double }
来源：http://dali.shuidangran.top/Article/details/gtbrmmvtvw.html

[T16] Swift：Hello World
来源：http://dali.havefunace.top/Article/details/gtjfqgjeje.html

print("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtepxpdnec.html

[T17] Swift：变量与常量
来源：http://dali.cdnleiting.top/Article/details/gtsmxuotgd.html

var a = 1;  let b = 2
来源：http://dali.dianchejie.cn/Article/details/gtgbtecgxk.html

[T18] Swift：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gtwtawcact.html

"值: \(b)"
来源：http://dali.zhaomingkeji.xyz/Article/details/gteqbycwmj.html

[T19] Swift：可选绑定
来源：http://dali.fengsongda.top/Article/details/gtslcqynnp.html

if let n = opt { print(n) }
来源：http://dali.jqgfzy.top/Article/details/gtagibqblt.html

[T20] Swift：数组操作
来源：http://dali.smart0.xyz/Article/details/gtzffdjhyt.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.guannengcc.top/Article/details/gthdxuvtfq.html

[T21] Swift：遍历
来源：http://dali.shzxlz.cn/Article/details/gtxgotddiu.html

for x in a { print(x) }
来源：http://dali.guannengcc.top/Article/details/gthizqlvzx.html

[T22] Swift：字典
来源：http://dali.jianghu66.top/Article/details/gtdjjfykib.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jiagoushi.top/Article/details/gtuwihzaan.html

[T23] Swift：函数
来源：http://dali.zhijiandao.cn/Article/details/gtqpizosji.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sufxvd.cn/Article/details/gtoapeoifw.html

[T24] Swift：闭包
来源：http://dali.yuxming.cn/Article/details/gtvnnpkstu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xuetiantiany.cn/Article/details/gtuishoqap.html

[T25] Swift：结构体
来源：http://dali.mhx1999.top/Article/details/gtfjqemdiy.html

struct P { var x: Int }
来源：http://dali.shangyingyoupin.top/Article/details/gtfpcncoiz.html

[T26] Swift：类与重写
来源：http://dali.hywenlv.cn/Article/details/gtzaudplsw.html

class A: Base { override func f() {} }
来源：http://dali.meibo888.top/Article/details/gtriijcvcn.html

[T27] Swift：错误处理
来源：http://dali.sweek.top/Article/details/gtdkdccttd.html

do { try f() } catch { print(error) }
来源：http://dali.cucudq.cn/Article/details/gtbryzrbcy.html

[T28] Swift：枚举
来源：http://dali.yangfankeji.com/Article/details/gtxnwyleot.html

enum Color { case red, green }
来源：http://dali.yj202588.top/Article/details/gtparauqfo.html

[T29] Swift：guard 提前返回
来源：http://dali.yj20258.top/Article/details/gtftsejfrf.html

guard let x = opt else { return }
来源：http://dali.dashuyun.cn/Article/details/gtcyjpcexf.html

[T30] Swift：协议
来源：http://dali.zhijiandao.cn/Article/details/gthhpftsax.html

protocol Shape { func area() -> Double }
来源：http://dali.nanxuanxn.top/Article/details/gtqqwuhtoz.html

[T31] Lua：Hello World
来源：http://dali.yuxming.cn/Article/details/gtplhxgqkl.html

print("Hello")
来源：http://dali.jqgfzy.top/Article/details/gtyzwyuicq.html

[T32] Lua：局部变量
来源：http://dali.zhongyouzk.top/Article/details/gtfutthqba.html

local a = 1
来源：http://dali.svipenyu.cn/Article/details/gtsgmkfviu.html

[T33] Lua：表（数组）
来源：http://dali.jianghu66.top/Article/details/gtjyzuqocj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.chenjidiqi.icu/Article/details/gtqdihtioj.html

[T34] Lua：遍历表
来源：http://dali.guowangkeji.top/Article/details/gtapstuigu.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.snrcjt.cn/Article/details/gtztlqxydu.html

[T35] Lua：字典表
来源：http://dali.xziqi.cn/Article/details/gtlnalbcxk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.birdmap.top/Article/details/gtrugulmmb.html

[T36] Lua：函数
来源：http://dali.quarkkingdee.top/Article/details/gttaskvmau.html

function add(a, b) return a + b end
来源：http://dali.xylfe.cn/Article/details/gttfmjfzly.html

[T37] Lua：字符串拼接
来源：http://dali.chenlongwang.top/Article/details/gtrjbomqgv.html

"a" .. "b"
来源：http://dali.chenlongwang.top/Article/details/gtbrrdlzdr.html

[T38] Lua：条件
来源：http://dali.dashuyun.cn/Article/details/gtucbfdkjm.html

if x > 0 then print("正") end
来源：http://dali.ivvv.top/Article/details/gteduayqdn.html

[T39] Lua：模式匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtdcvavrxc.html

string.find(s, "%d+")
来源：http://dali.jlsjyb.cn/Article/details/gtzhgpaxlf.html

[T40] Lua：元表
来源：http://dali.ydzc1.top/Article/details/gtzqyulvgo.html

setmetatable({}, { __index = base })
来源：http://dali.0kj1m.cn/Article/details/gtyidsdapk.html

[T41] Perl：Hello World
来源：http://dali.yj202588.top/Article/details/gtywrvdbei.html

print "Hello\n";
来源：http://dali.yuxming.cn/Article/details/gttuzkkwyn.html

[T42] Perl：变量类型
来源：http://dali.smart0.xyz/Article/details/gtclzxwwkc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zdqjudy.top/Article/details/gtpuccqpwb.html

[T43] Perl：字符串插值
来源：http://dali.ybcxt.top/Article/details/gtagimvuxk.html

"值: $a"
来源：http://dali.aibaodan.cn/Article/details/gtbynqkmcs.html

[T44] Perl：条件
来源：http://dali.yangfankeji.com/Article/details/gtzzamnbiw.html

if ($a > 0) { print "正"; }
来源：http://dali.cqqwz.cn/Article/details/gtmhnfkowv.html

[T45] Perl：数组遍历
来源：http://dali.zhongyouzk.top/Article/details/gtzqfkzyns.html

for my $x (@arr) { print $x; }
来源：http://dali.vqdsnc.cn/Article/details/gtqewlgkse.html

[T46] Perl：哈希操作
来源：http://dali.yueranfly.top/Article/details/gtxkfvyaxy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.aibaodan.cn/Article/details/gtbxeudxui.html

[T47] Perl：正则捕获
来源：http://dali.gzhubu.top/Article/details/gtiyxqmpcr.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hnxiangtu.top/Article/details/gtcpqaurhj.html

[T48] Perl：正则替换
来源：http://dali.hongshengwenyu.top/Article/details/gtfimbtzxo.html

$s =~ s/old/new/g;
来源：http://dali.9152youxi.cn/Article/details/gtwchqolez.html

[T49] Perl：函数
来源：http://dali.yangfankeji.com/Article/details/gtpbqyivfi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sysykeji.top/Article/details/gtnnucndpv.html

[T50] Perl：逐行读文件
来源：http://dali.cashguo.top/Article/details/gtbmhaixxb.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhixingplan.top/Article/details/gtqolgkbie.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.wangshuangyany.cn/Article/details/gtrlaojvmk.html

[T51] Scala：Hello World
来源：http://dali.cdnleiting.top/Article/details/gtubedglwd.html

println("Hello")
来源：http://dali.sufxvd.cn/Article/details/gtflmykoyo.html

[T52] Scala：变量
来源：http://dali.jlsjyb.cn/Article/details/gtelggxyow.html

val a = 1;  var b = 2
来源：http://dali.smart0.xyz/Article/details/gtjmyypuwz.html

[T53] Scala：字符串插值
来源：http://dali.pengpengdd.cyou/Article/details/gtwparposg.html

s"值: $b"
来源：http://dali.tianlin.xyz/Article/details/gtaqtjiehp.html

[T54] Scala：集合映射
来源：http://dali.tianlin.xyz/Article/details/gtwshnxpyj.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.sufxvd.cn/Article/details/gtcomqfwzt.html

[T55] Scala：集合过滤
来源：http://dali.jlsjyb.cn/Article/details/gttukwtboj.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.pengpengdd.cyou/Article/details/gtkcxsrvpp.html

[T56] Scala：样例类
来源：http://dali.guannengcc.top/Article/details/gtoyypidpk.html

case class User(name: String, age: Int)
来源：http://dali.zdqjudy.top/Article/details/gtkpgofwlq.html

[T57] Scala：模式匹配
来源：http://dali.sysykeji.top/Article/details/gtsreaxcvl.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.0kj1m.cn/Article/details/gtfbhxptol.html

[T58] Scala：函数定义
来源：http://dali.fengsongda.top/Article/details/gttgngyllu.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.gogol.net.cn/Article/details/gtbvvzarig.html

[T59] Scala：循环
来源：http://dali.yj202588.top/Article/details/gtycfknjkd.html

for (i <- 1 to 10) println(i)
来源：http://dali.chenlongwang.top/Article/details/gtobbxnxby.html

[T60] Scala：折叠
来源：http://dali.gotoacloud.top/Article/details/gtvbuklgfs.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ppjwa.cn/Article/details/gtunzqithg.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtlreipvyi.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinqigfzy.top/Article/details/gtuqgeuqfq.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtzfcyfdlh.html

[U01] Py：创建虚拟环境
来源：http://dali.zdqjudy.top/Article/details/gtygfuaypr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.dianchejie.cn/Article/details/gtrbahwrmo.html

[U02] Py：导出 / 安装依赖
来源：http://dali.tian-w.cn/Article/details/gtkbsdhlua.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gogol.net.cn/Article/details/gtluxmrdwg.html

[U03] Py：加载 .env 配置
来源：http://dali.tian-w.cn/Article/details/gtlotjsndw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.tanke756.top/Article/details/gtxxyhglnw.html

[U04] Py：变量调试打印
来源：http://dali.zhijiandao.cn/Article/details/gtkcfxfnww.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlpckaqtq.html

[U05] Py：列表去重且保序
来源：http://dali.ybcxt.top/Article/details/gtdyajgqjt.html

list(dict.fromkeys(arr))
来源：http://dali.ppjwa.cn/Article/details/gtxfmnozjj.html

[U06] Py：合并两个字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gtujqgziji.html

{**a, **b}
来源：http://dali.shzxlz.cn/Article/details/gtxsiopwij.html

[U07] Py：反转字典键值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpkmexywd.html

{v: k for k, v in d.items()}
来源：http://dali.cheryme.top/Article/details/gtwqsacbfi.html

[U08] Py：展平二维列表
来源：http://dali.bjfxy.top/Article/details/gtperjslbo.html

[y for x in nested for y in x]
来源：http://dali.guannengcc.top/Article/details/gtabenewxe.html

[U09] Py：字典取最大值的键
来源：http://dali.ppjwa.cn/Article/details/gtbooerqpy.html

max(d, key=d.get)
来源：http://dali.feifeiyinyue.top/Article/details/gtktcuphmt.html

[U10] Py：按值排序字典
来源：http://dali.zhengqikj.top/Article/details/gtxxnnosdp.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.9152youxi.cn/Article/details/gtqghnagov.html

[U11] Py：生成器表达式
来源：http://dali.cqqwz.cn/Article/details/gtepvzfmrm.html

(x * 2 for x in arr)
来源：http://dali.mhx1999.top/Article/details/gtaqukvfch.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yj202588.top/Article/details/gtjqcvzxvy.html

Counter(arr).most_common(3)
来源：http://dali.daria6918.cn/Article/details/gtpvzghoto.html

[U13] Py：固定长度队列
来源：http://dali.gzhubu.top/Article/details/gtlqbcsevx.html

deque(maxlen=10)
来源：http://dali.gzhubu.top/Article/details/gtsqczirbm.html

[U14] Py：分组收集到列表
来源：http://dali.yueranfly.top/Article/details/gtdjbglmkg.html

defaultdict(list)
来源：http://dali.jyoumei.cn/Article/details/gtfcadocfc.html

[U15] Py：高精度计时
来源：http://dali.shzxlz.cn/Article/details/gtpciqqevq.html

t = time.perf_counter()
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfkcvvozw.html

[U16] Py：命令行参数解析
来源：http://dali.cashguo.top/Article/details/gtbvizrcfw.html

ap = argparse.ArgumentParser();  ap.add_argument("--name");  args = ap.parse_args()
来源：http://dali.ivvv.top/Article/details/gtpultiolu.html

[U17] Py：初始化日志
来源：http://dali.sweek.top/Article/details/gtttkhqzri.html

logging.basicConfig(level=logging.INFO)
来源：http://dali.shangyingyoupin.top/Article/details/gtmjclenuc.html

[U18] Py：预编译正则
来源：http://dali.hongshengwenyu.top/Article/details/gttwwuxkbd.html

pat = re.compile(r"\d+")
来源：http://dali.xylfe.cn/Article/details/gtlvwbivgx.html


<!-- 参考信息 -->