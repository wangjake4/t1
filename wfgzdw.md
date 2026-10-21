代发 wailian999

split -l 1000 big.log part_
来源：http://dali.hysaishi.cn/Article/details/gtjjopmopc.html

[R74] 批量重命名
来源：http://dali.tanke756.top/Article/details/gtrcjeyzua.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gotoacloud.top/Article/details/gtuwmbuohi.html

[R75] 导出环境变量
来源：http://dali.sufxvd.cn/Article/details/gtugqaoyit.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhongyouzk.top/Article/details/gtsxahebct.html

[R76] 使用临时文件
来源：http://dali.xuanzx.com/Article/details/gtebkztegx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigfzy.top/Article/details/gticnywwmf.html

[R77] 读取用户输入
来源：http://dali.jinghuilouyu.cn/Article/details/gtayrqxpth.html

read -rp "请输入: " ans
来源：http://dali.yvedp.cn/Article/details/gtamotrmip.html

[R78] 交互式菜单
来源：http://dali.cdnleiting.top/Article/details/gtuqiizcif.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cashguo.top/Article/details/gtlfieofoe.html

[R79] 解析命令行选项
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbyhmwlkt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.c1oappe.top/Article/details/gtqeaujyix.html

[R80] 查看脚本执行耗时
来源：http://dali.yj202588.top/Article/details/gtuovdeivu.html

time ./run.sh
来源：http://dali.zhengqikj.top/Article/details/gtqvnjnmhl.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtqonajopr.html

S. C / C++ 专题
来源：http://dali.mhx1999.top/Article/details/gtvhxoitix.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtkrdcyayr.html

[S01] C：Hello World
来源：http://dali.hnqzz.top/Article/details/gtefyizjfo.html

#include <stdio.h>
来源：http://dali.cqqwz.cn/Article/details/gtufwrditz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ivvv.top/Article/details/gtbhjpxwnw.html

[S02] C：变量与格式化输出
来源：http://dali.daria6918.cn/Article/details/gtohfrbvze.html

int a = 10; printf("%d\n", a);
来源：http://dali.yuanzhike.top/Article/details/gtlblwmuzx.html

[S03] C：读入整数
来源：http://dali.zhoulong.xyz/Article/details/gtmbengddu.html

int x; scanf("%d", &x);
来源：http://dali.redwolf501.top/Article/details/gtbklmsyrl.html

[S04] C：字符串复制
来源：http://dali.cheryme.top/Article/details/gtjestdrlh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yvedp.cn/Article/details/gtyuukusjg.html

[S05] C：字符串长度
来源：http://dali.ppjwa.cn/Article/details/gtbsqamwdn.html

strlen(s)
来源：http://dali.sweek.top/Article/details/gtabcqkyae.html

[S06] C：字符串比较
来源：http://dali.jinqigufen.top/Article/details/gtlcqbqzxv.html

strcmp(a, b) == 0
来源：http://dali.xziqi.cn/Article/details/gtldugsfvm.html

[S07] C：数组遍历求和
来源：http://dali.9152youxi.cn/Article/details/gtipftbmee.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xuetiantiany.cn/Article/details/gthzsflocc.html

[S08] C：动态内存分配与释放
来源：http://dali.zhengqikj.top/Article/details/gtujqfiscz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.pycfn.com/Article/details/gtpcjfewyb.html

[S09] C：结构体定义与初始化
来源：http://dali.zhongyouzk.top/Article/details/gtldqxuked.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ivvv.top/Article/details/gtdqbrdgun.html

[S10] C：指针与解引用
来源：http://dali.shanyushiyangtech.top/Article/details/gtycjjzblh.html

int *p = &a;  *p = 5;
来源：http://dali.ppjwa.cn/Article/details/gtflriruds.html

[S11] C：逐行读文件
来源：http://dali.gzhubu.top/Article/details/gtlblhthpe.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.redwolf501.top/Article/details/gtkknlhncn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.wangshuangyany.cn/Article/details/gtsfvwpcuc.html

fclose(f);
来源：http://dali.nanxinkj.top/Article/details/gtxbcaskld.html

[S12] C：写文件
来源：http://dali.hammf.cn/Article/details/gtjnblzpav.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj202588.top/Article/details/gtujpakats.html

[S13] C：宏定义
来源：http://dali.zhoulong.xyz/Article/details/gtadkrbqjc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.feifeiyinyue.top/Article/details/gtzzwcwzys.html

[S14] C：枚举
来源：http://dali.havefunace.top/Article/details/gtfghikvpw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shzxlz.cn/Article/details/gtshvrwtvr.html

[S15] C：类型转换
来源：http://dali.zycfv.cn/Article/details/gtwvtywbvf.html

(double) a / b
来源：http://dali.kuanghao11.cn/Article/details/gtvrxjedyg.html

[S16] C：位操作置位
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpzdcerxj.html

x |= (1 << 3);
来源：http://dali.quarkkingdee.top/Article/details/gtrczwnaqx.html

[S17] C：安全拼接字符串
来源：http://dali.c1oappe.top/Article/details/gtszlkccdq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.9152youxi.cn/Article/details/gtaxyzhbdu.html

[S18] C：命令行参数
来源：http://dali.shzxlz.cn/Article/details/gtqhqfaorv.html

int main(int argc, char **argv)
来源：http://dali.xinyue.icu/Article/details/gtogsqqvns.html

[S19] C：快速排序
来源：http://dali.yuxming.cn/Article/details/gtryggzkfs.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cqqwz.cn/Article/details/gtadukjkoo.html

[S20] C：二分查找
来源：http://dali.gaohongyu789.top/Article/details/gtnsgzbijr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gtmqtipcna.html

[S21] C：字符类别判断
来源：http://dali.guannengcc.top/Article/details/gtxcrxkoxs.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhongyouzk.top/Article/details/gtmxeuolba.html

[S22] C：字符串转数字
来源：http://dali.jqgufenzy.top/Article/details/gtbwjelvxd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.svipenyu.cn/Article/details/gtkxaaadov.html

[S23] C：随机数
来源：http://dali.shanyushiyangtech.top/Article/details/gtfprtuevm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.kuanghao11.cn/Article/details/gtbrqawcip.html

[S24] C：获取本地时间
来源：http://dali.dianchejie.cn/Article/details/gtwlgfnifa.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinqigfzy.top/Article/details/gtippycnhl.html

[S25] C：内存拷贝
来源：http://dali.zdqjudy.top/Article/details/gtyathzoig.html

memcpy(dst, src, n);
来源：http://dali.jinqigfzy.top/Article/details/gthxqvkojs.html

[S26] C：内存清零
来源：http://dali.jinqigfzy.top/Article/details/gtzkdzdzao.html

memset(a, 0, sizeof a);
来源：http://dali.pycfn.com/Article/details/gtngljlsjs.html

[S27] C：定义常量
来源：http://dali.9152youxi.cn/Article/details/gtuuhkkrup.html

const double PI = 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gtnxsqtnal.html

[S28] C：静态变量
来源：http://dali.hnxiangtu.top/Article/details/gtwzotvtin.html

static int counter = 0;
来源：http://dali.cqqwz.cn/Article/details/gtwdvrdmmj.html

[S29] C：变参函数
来源：http://dali.gotoacloud.top/Article/details/gtjilpnywx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gtvegfqasp.html

[S30] C：头文件保护
来源：http://dali.chenjidiqi.icu/Article/details/gthngolfze.html

#ifndef X_H
来源：http://dali.nanxuanxn.top/Article/details/gtdpbzdujh.html

#define X_H
来源：http://dali.xuanzx.com/Article/details/gtuvvzlnbl.html

#endif
来源：http://dali.jinghuilouyu.cn/Article/details/gtzpwjvylx.html

[S31] C++：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtmnyceayn.html

#include <iostream>
来源：http://dali.wangdashe.top/Article/details/gtkmuxvawp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jinqigufen.top/Article/details/gtkhvvnfsy.html

[S32] C++：字符串
来源：http://dali.ydzc1.top/Article/details/gtlcbqnukz.html

std::string s = "hi";  s += "!";
来源：http://dali.nwbrower.top/Article/details/gtgdldrhjv.html

[S33] C++：vector 增删
来源：http://dali.tanke756.top/Article/details/gtcxtwdpwh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.birdmap.top/Article/details/gtnxdqjiqo.html

[S34] C++：遍历 vector
来源：http://dali.jinqigfzy.top/Article/details/gtuahptiys.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinqigfzy.top/Article/details/gtqbhyzyxd.html

[S35] C++：map
来源：http://dali.jianghu66.top/Article/details/gtatkikfts.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258.top/Article/details/gthfdiruih.html

[S36] C++：unordered_map
来源：http://dali.jinyuanbaomall.cn/Article/details/gtncvrjszg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj202588.top/Article/details/gtvjdwcmvq.html

[S37] C++：set
来源：http://dali.xziqi.cn/Article/details/gtisteoatu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj20258.top/Article/details/gtzknetgjm.html

[S38] C++：排序
来源：http://dali.bjfxy.top/Article/details/gtdyjrocjr.html

std::sort(v.begin(), v.end());
来源：http://dali.guannengcc.top/Article/details/gtgwohqqui.html

[S39] C++：自定义比较器排序
来源：http://dali.havefunace.top/Article/details/gtscbcomzt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shanyushiyangtech.top/Article/details/gtcpwnzppi.html

[S40] C++：查找元素
来源：http://dali.tianlin.xyz/Article/details/gtvrbcxpho.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.daxiang520.top/Article/details/gtfpdwgrqo.html

[S41] C++：类与构造函数
来源：http://dali.316326.xyz/Article/details/gtufgfilvh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhengqikj.top/Article/details/gtxyfdniai.html

[S42] C++：继承与虚函数
来源：http://dali.ivvv.top/Article/details/gtszmiuntz.html

class B : public Base { public: void f() override {} };
来源：http://dali.yj20258888.top/Article/details/gtpxwfjwaa.html

[S43] C++：智能指针
来源：http://dali.ivvv.top/Article/details/gtrqvdkezn.html

auto p = std::make_unique<int>(5);
来源：http://dali.shuidangran.top/Article/details/gtjpanxydb.html

[S44] C++：引用传参
来源：http://dali.hongshengwenyu.top/Article/details/gtpuimqkvp.html

void inc(int &x) { ++x; }
来源：http://dali.tianlin.xyz/Article/details/gttwzilcfa.html

[S45] C++：lambda
来源：http://dali.xuanzx.com/Article/details/gthtnrinhc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jianghu66.top/Article/details/gtswimxthw.html

[S46] C++：函数模板
来源：http://dali.yanxiufei.cn/Article/details/gtcpvpukgt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yueranfly.top/Article/details/gtcrkiujez.html

[S47] C++：结构化绑定遍历
来源：http://dali.316326.xyz/Article/details/gtrtigyrfo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yongpay.top/Article/details/gtyfaudlzf.html

[S48] C++：逐行读文件
来源：http://dali.mhx1999.top/Article/details/gthtxfucij.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yj202588.top/Article/details/gtllznjybg.html

while (std::getline(in, line)) { }
来源：http://dali.chenlongwang.top/Article/details/gtnqfzddld.html

[S49] C++：写文件
来源：http://dali.hongshengwenyu.top/Article/details/gtxckskovy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhixingplan.top/Article/details/gtfmhykscz.html

[S50] C++：格式化数字
来源：http://dali.iojbl.cn/Article/details/gteiimifkz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yvedp.cn/Article/details/gtuigtgfrc.html

[S51] C++：显式类型转换
来源：http://dali.c1oappe.top/Article/details/gtvtqwrnwc.html

static_cast<double>(a) / b
来源：http://dali.yuxming.cn/Article/details/gtarqkunpb.html

[S52] C++：const 与 noexcept
来源：http://dali.andypj.xyz/Article/details/gtbfihyagf.html

int size() const noexcept { return n_; }
来源：http://dali.haohaochexian.top/Article/details/gtbcuknxud.html

[S53] C++：移动语义
来源：http://dali.havefunace.top/Article/details/gtrisosyzo.html

std::vector<int> w = std::move(v);
来源：http://dali.hywenlv.cn/Article/details/gtqhbijvdn.html

[S54] C++：异常处理
来源：http://dali.yuxming.cn/Article/details/gtxmhwvtqp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinqigufen.top/Article/details/gtcfuyjvzz.html

[S55] C++：结构化绑定
来源：http://dali.yj20258888.top/Article/details/gtlhikndsf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.mhx1999.top/Article/details/gtncfewwvr.html

[S56] C++：optional
来源：http://dali.shuidangran.top/Article/details/gtnonmdowd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jqgufenzy.top/Article/details/gtgwejnsug.html

[S57] C++：编译期常量
来源：http://dali.xylfe.cn/Article/details/gtvsjitkob.html

constexpr int N = 10;
来源：http://dali.sweek.top/Article/details/gtijesmona.html

[S58] C++：命名空间
来源：http://dali.wangdashe.top/Article/details/gtcslbpwun.html

namespace ns { int f() { return 1; } }
来源：http://dali.cdnleiting.top/Article/details/gtgdeeliri.html

[S59] C++：静态断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gtolumaovt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjrmungwh.html

[S60] C++：遍历并删除元素
来源：http://dali.cdnleiting.top/Article/details/gtplmulxya.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.mhx1999.top/Article/details/gtxqhbsufk.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtudkdjhmg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shangyingyoupin.top/Article/details/gtihratori.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtfdkytmor.html

[T01] Kotlin：Hello World
来源：http://dali.daxiang520.top/Article/details/gtqewnbpxq.html

println("Hello")
来源：http://dali.yj20258888.top/Article/details/gtwvlxasck.html

[T02] Kotlin：变量
来源：http://dali.gzhubu.top/Article/details/gtnbpqsujg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jlsjyb.cn/Article/details/gtmmurbdjy.html

[T03] Kotlin：字符串模板
来源：http://dali.tianlin.xyz/Article/details/gtbxjexqwq.html

"值: $b"
来源：http://dali.yj20258888.top/Article/details/gtogrbyyat.html

[T04] Kotlin：空安全
来源：http://dali.zhoulong.xyz/Article/details/gtyixxlykv.html

val n: String? = null;  n?.length
来源：http://dali.jlsjyb.cn/Article/details/gtqxjfphnc.html

[T05] Kotlin：when 表达式
来源：http://dali.jiagoushi.top/Article/details/gtwoxpgczp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinqigfzy.top/Article/details/gtmoydvltv.html

[T06] Kotlin：集合映射
来源：http://dali.yj202588.top/Article/details/gtmmgvefqe.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdqrzvuvu.html

[T07] Kotlin：集合过滤
来源：http://dali.jianghu66.top/Article/details/gtgnngmpro.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ppjwa.cn/Article/details/gtzlyqflae.html

[T08] Kotlin：数据类
来源：http://dali.tianlin.xyz/Article/details/gtyeydbujz.html

data class User(val name: String, val age: Int)
来源：http://dali.cheryme.top/Article/details/gtdtazlkbl.html

[T09] Kotlin：扩展函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwyfcqewd.html

fun String.exclaim() = this + "!"
来源：http://dali.ydzc1.top/Article/details/gtmbjoxbqy.html

[T10] Kotlin：默认参数
来源：http://dali.cheryme.top/Article/details/gtniycuwxg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.dianchejie.cn/Article/details/gtrwrowynp.html

[T11] Kotlin：协程
来源：http://dali.jinqigfzy.top/Article/details/gttmfbtkbu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwnzuxoed.html

[T12] Kotlin：解构声明
来源：http://dali.redwolf501.top/Article/details/gtuxaniwdp.html

val (a, b) = Pair(1, 2)
来源：http://dali.yanxiufei.cn/Article/details/gttvcagezu.html

[T13] Kotlin：只读 Map
来源：http://dali.zhengqikj.top/Article/details/gtvkkrqgsx.html

val m = mapOf("a" to 1)
来源：http://dali.yonumen.top/Article/details/gtvrqxshga.html

[T14] Kotlin：循环
来源：http://dali.zhengqikj.top/Article/details/gtfbvjpqpw.html

for (i in 1..10) println(i)
来源：http://dali.daxiang520.top/Article/details/gtxeidktoi.html

[T15] Kotlin：接口
来源：http://dali.xylfe.cn/Article/details/gteojsjjyp.html

interface Shape { fun area(): Double }
来源：http://dali.zdqjudy.top/Article/details/gtgwiusufr.html

[T16] Swift：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gthlxnxeqw.html

print("Hello")
来源：http://dali.tianlin.xyz/Article/details/gtqprbmtql.html

[T17] Swift：变量与常量
来源：http://dali.ppjwa.cn/Article/details/gtsukajhpt.html

var a = 1;  let b = 2
来源：http://dali.nanxuanxn.top/Article/details/gtbcqaxacm.html

[T18] Swift：字符串插值
来源：http://dali.vqdsnc.cn/Article/details/gtldmdrskw.html

"值: \(b)"
来源：http://dali.yongpay.top/Article/details/gtgwngxvsc.html

[T19] Swift：可选绑定
来源：http://dali.yuanzhike.top/Article/details/gtoyjygkme.html

if let n = opt { print(n) }
来源：http://dali.cucudq.cn/Article/details/gtfexthkuh.html

[T20] Swift：数组操作
来源：http://dali.0kj1m.cn/Article/details/gtbpctynml.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.chenlongwang.top/Article/details/gtjzucizbq.html

[T21] Swift：遍历
来源：http://dali.jianghu66.top/Article/details/gtwdznrwze.html

for x in a { print(x) }
来源：http://dali.gotoacloud.top/Article/details/gtbzmsgctt.html

[T22] Swift：字典
来源：http://dali.jianghu66.top/Article/details/gtvyqwrvqp.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.sufxvd.cn/Article/details/gtcilshova.html

[T23] Swift：函数
来源：http://dali.guowangkeji.top/Article/details/gtzaizyysw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shangyingyoupin.top/Article/details/gtmjellmtw.html

[T24] Swift：闭包
来源：http://dali.dashuyun.cn/Article/details/gttmunngdb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zycfv.cn/Article/details/gtgqhkuspq.html

[T25] Swift：结构体
来源：http://dali.redwolf501.top/Article/details/gtucudikyx.html

struct P { var x: Int }
来源：http://dali.dianchejie.cn/Article/details/gthmemzdaz.html

[T26] Swift：类与重写
来源：http://dali.sxryk.cn/Article/details/gtslprpsbm.html

class A: Base { override func f() {} }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuvjukiyn.html

[T27] Swift：错误处理
来源：http://dali.cucudq.cn/Article/details/gtwffhiwjn.html

do { try f() } catch { print(error) }
来源：http://dali.xuanzx.com/Article/details/gtxcmsvgah.html

[T28] Swift：枚举
来源：http://dali.ybcxt.top/Article/details/gtnzwdjqne.html

enum Color { case red, green }
来源：http://dali.jyoumei.cn/Article/details/gtlbzicnxb.html

[T29] Swift：guard 提前返回
来源：http://dali.tanke756.top/Article/details/gtsyjojjjl.html

guard let x = opt else { return }
来源：http://dali.xinyue.icu/Article/details/gtcoolkjdb.html

[T30] Swift：协议
来源：http://dali.tanke756.top/Article/details/gtqwecqihd.html

protocol Shape { func area() -> Double }
来源：http://dali.yj202588.top/Article/details/gtjminvaip.html

[T31] Lua：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gttrhutqhf.html

print("Hello")
来源：http://dali.gogol.net.cn/Article/details/gtroxeginz.html

[T32] Lua：局部变量
来源：http://dali.shangyingyoupin.top/Article/details/gtwmtiqvte.html

local a = 1
来源：http://dali.yuxming.cn/Article/details/gtmhdeccec.html

[T33] Lua：表（数组）
来源：http://dali.yonumen.top/Article/details/gtmzvoeqjf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jlsjyb.cn/Article/details/gtawhdzrqq.html

[T34] Lua：遍历表
来源：http://dali.yvedp.cn/Article/details/gtocoiogjj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.316326.xyz/Article/details/gtuclomvev.html

[T35] Lua：字典表
来源：http://dali.zhongyouzk.top/Article/details/gtigmvzjvm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhixingplan.top/Article/details/gtbsplvgmt.html

[T36] Lua：函数
来源：http://dali.yj20258888.top/Article/details/gtrymsspxf.html

function add(a, b) return a + b end
来源：http://dali.dashuyun.cn/Article/details/gtboaoryml.html

[T37] Lua：字符串拼接
来源：http://dali.jianghu66.top/Article/details/gtkxbfscfm.html

"a" .. "b"
来源：http://dali.xuetiantiany.cn/Article/details/gthvorbnau.html

[T38] Lua：条件
来源：http://dali.aizwys.cn/Article/details/gtpxbymaws.html

if x > 0 then print("正") end
来源：http://dali.tanke756.top/Article/details/gtiruvygsw.html

[T39] Lua：模式匹配
来源：http://dali.shangyingyoupin.top/Article/details/gtrjgzkenr.html

string.find(s, "%d+")
来源：http://dali.gogol.net.cn/Article/details/gtsoigskba.html

[T40] Lua：元表
来源：http://dali.fzhhl.top/Article/details/gtlsnumeeb.html

setmetatable({}, { __index = base })
来源：http://dali.guannengcc.top/Article/details/gtksfgkpbb.html

[T41] Perl：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtyerjgxrt.html

print "Hello\n";
来源：http://dali.birdmap.top/Article/details/gtdgeohhkt.html

[T42] Perl：变量类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtipzeqmep.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jiagoushi.top/Article/details/gtdcuofpec.html

[T43] Perl：字符串插值
来源：http://dali.tanke756.top/Article/details/gtgzmwuzhu.html

"值: $a"
来源：http://dali.yvedp.cn/Article/details/gtgxtxrguu.html

[T44] Perl：条件
来源：http://dali.daria6918.cn/Article/details/gtutyrozru.html

if ($a > 0) { print "正"; }
来源：http://dali.feifeiyinyue.top/Article/details/gtwuttwsxe.html

[T45] Perl：数组遍历
来源：http://dali.yj202588.top/Article/details/gtlenqcisb.html

for my $x (@arr) { print $x; }
来源：http://dali.pengpengdd.cyou/Article/details/gtwuhjgtho.html

[T46] Perl：哈希操作
来源：http://dali.andypj.xyz/Article/details/gtxvcvevpv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.snrcjt.cn/Article/details/gtfskfbnsn.html

[T47] Perl：正则捕获
来源：http://dali.gotoacloud.top/Article/details/gtksuxdseq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yongpay.top/Article/details/gtijgonemp.html

[T48] Perl：正则替换
来源：http://dali.cqqwz.cn/Article/details/gtubknqgpm.html

$s =~ s/old/new/g;
来源：http://dali.sysykeji.top/Article/details/gtslftauzg.html

[T49] Perl：函数
来源：http://dali.ybcxt.top/Article/details/gtjchxurve.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.nanxuanxn.top/Article/details/gtokxvxsxo.html

[T50] Perl：逐行读文件
来源：http://dali.yvedp.cn/Article/details/gthtagjitn.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cdnleiting.top/Article/details/gthmjqpxip.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zycfv.cn/Article/details/gtzqzsqjtz.html

[T51] Scala：Hello World
来源：http://dali.yj20258.top/Article/details/gtvfkbiooc.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gtpuxxxaml.html

[T52] Scala：变量
来源：http://dali.yvedp.cn/Article/details/gtfbkrhsnx.html

val a = 1;  var b = 2
来源：http://dali.hysaishi.cn/Article/details/gtdrxpacjb.html

[T53] Scala：字符串插值
来源：http://dali.zdqjudy.top/Article/details/gttxrzqevr.html

s"值: $b"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnqfskyjz.html

[T54] Scala：集合映射
来源：http://dali.snrcjt.cn/Article/details/gthyaladtb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.vqdsnc.cn/Article/details/gtmhjoljpv.html

[T55] Scala：集合过滤
来源：http://dali.pycfn.com/Article/details/gtvzbcputg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhiwuduotai.top/Article/details/gtkprbuxir.html

[T56] Scala：样例类
来源：http://dali.hysaishi.cn/Article/details/gtpgeltqla.html

case class User(name: String, age: Int)
来源：http://dali.daxiang520.top/Article/details/gtbyxeycot.html

[T57] Scala：模式匹配
来源：http://dali.hysaishi.cn/Article/details/gtkuhxiufq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jinghuilouyu.cn/Article/details/gtvmhvsuec.html

[T58] Scala：函数定义
来源：http://dali.shuidangran.top/Article/details/gtdsujtaeh.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hnxiangtu.top/Article/details/gtapwtsiot.html

[T59] Scala：循环
来源：http://dali.xziqi.cn/Article/details/gtfninfvqt.html

for (i <- 1 to 10) println(i)
来源：http://dali.feifeiyinyue.top/Article/details/gtblxbuvry.html

[T60] Scala：折叠
来源：http://dali.redwolf501.top/Article/details/gtsypumbqh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.chenzaomai.com/Article/details/gtfsmkcouk.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtebforpio.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.wangshuangyany.cn/Article/details/gtjqvggrjf.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtlxvzjxoz.html

[U01] Py：创建虚拟环境
来源：http://dali.zhaomingkeji.xyz/Article/details/gthfoljecy.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.nwbrower.top/Article/details/gtoahrxfsk.html

[U02] Py：导出 / 安装依赖
来源：http://dali.c1oappe.top/Article/details/gtqpgstjeu.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gogol.net.cn/Article/details/gtttvptbuz.html

[U03] Py：加载 .env 配置
来源：http://dali.daxiang520.top/Article/details/gtsbapmqvh.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.meibo888.top/Article/details/gtfcaeiecf.html

[U04] Py：变量调试打印
来源：http://dali.gzhubu.top/Article/details/gtczheohbg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xziqi.cn/Article/details/gtsjzzviuo.html

[U05] Py：列表去重且保序
来源：http://dali.vqdsnc.cn/Article/details/gtutpcidcz.html

list(dict.fromkeys(arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gtentyakkp.html

[U06] Py：合并两个字典
来源：http://dali.birdmap.top/Article/details/gtxrlqqcwm.html

{**a, **b}
来源：http://dali.cqqwz.cn/Article/details/gtsbbwbvzy.html

[U07] Py：反转字典键值
来源：http://dali.zdqjudy.top/Article/details/gtusbrzmqw.html

{v: k for k, v in d.items()}
来源：http://dali.yuanzhike.top/Article/details/gtlnlvenfu.html

[U08] Py：展平二维列表
来源：http://dali.xuetiantiany.cn/Article/details/gtvhapshxf.html

[y for x in nested for y in x]
来源：http://dali.hfpthk.cn/Article/details/gtzdjamawl.html

[U09] Py：字典取最大值的键
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvonuorxn.html

max(d, key=d.get)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtulsohhtn.html

[U10] Py：按值排序字典
来源：http://dali.cheryme.top/Article/details/gtpkrocfnm.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yuanzhike.top/Article/details/gtvvhqgchv.html

[U11] Py：生成器表达式
来源：http://dali.guannengcc.top/Article/details/gtyldptrve.html

(x * 2 for x in arr)
来源：http://dali.yj20258.top/Article/details/gtxpbukfkb.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.hfpthk.cn/Article/details/gtzixdpbnc.html

Counter(arr).most_common(3)
来源：http://dali.fengsongda.top/Article/details/gtbziktrti.html

[U13] Py：固定长度队列
来源：http://dali.tian-w.cn/Article/details/gtnaingcii.html

deque(maxlen=10)
来源：http://dali.andypj.xyz/Article/details/gtcluykfzg.html

[U14] Py：分组收集到列表
来源：http://dali.jyoumei.cn/Article/details/gtjgtjihcn.html

defaultdict(list)
来源：http://dali.fzhhl.top/Article/details/gtcgsebwrt.html


<!-- 参考信息 -->