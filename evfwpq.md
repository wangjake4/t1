代发 wailian999

openssl rand -hex 16
来源：http://dali.haohaochexian.top/Article/details/gtvmnodpnt.html

[R68] 计算文件校验值
来源：http://dali.yuanzhike.top/Article/details/gtmacxsyzs.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtgsdyslro.html

[R69] 生成随机密码
来源：http://dali.zhoulong.xyz/Article/details/gtjlvhezkw.html

head -c 16 /dev/urandom | base64
来源：http://dali.gaohongyu789.top/Article/details/gtwbelfsxx.html

[R70] 时间戳与互转
来源：http://dali.yj202588.top/Article/details/gtqdphtwnd.html

date +%s;  date -d @1700000000
来源：http://dali.vqdsnc.cn/Article/details/gtxjriogws.html

[R71] 日期格式化
来源：http://dali.hfpthk.cn/Article/details/gtqpxkphdz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhixingplan.top/Article/details/gtcorrydml.html

[R72] 等待端口就绪
来源：http://dali.bjfxy.top/Article/details/gtabaznlvi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.chenzaomai.com/Article/details/gtdwnzaiva.html

[R73] 分割大日志
来源：http://dali.xziqi.cn/Article/details/gtkztudgbd.html

split -l 1000 big.log part_
来源：http://dali.hnqzz.top/Article/details/gteayeiyzm.html

[R74] 批量重命名
来源：http://dali.sweek.top/Article/details/gtqhvcapok.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtbjqsiunf.html

[R75] 导出环境变量
来源：http://dali.zhixingplan.top/Article/details/gtwxqstwwq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sxryk.cn/Article/details/gthxqwtyzq.html

[R76] 使用临时文件
来源：http://dali.svipenyu.cn/Article/details/gtybsttlqp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yanxiufei.cn/Article/details/gtuhdsxlxa.html

[R77] 读取用户输入
来源：http://dali.pengpengdd.cyou/Article/details/gtlysyrnzk.html

read -rp "请输入: " ans
来源：http://dali.cucudq.cn/Article/details/gtgbatkadj.html

[R78] 交互式菜单
来源：http://dali.smart0.xyz/Article/details/gtzuycgiou.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.iojbl.cn/Article/details/gtawxbmczj.html

[R79] 解析命令行选项
来源：http://dali.havefunace.top/Article/details/gtvlisjpkc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfjajfefg.html

[R80] 查看脚本执行耗时
来源：http://dali.sweek.top/Article/details/gtuadrtfth.html

time ./run.sh
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtodefibya.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtohfnkvrb.html

S. C / C++ 专题
来源：http://dali.fengsongda.top/Article/details/gtrmmiefoo.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtfepvdzge.html

[S01] C：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtasbakqyc.html

#include <stdio.h>
来源：http://dali.yj20258888.top/Article/details/gtjqjdzmjx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.tian-w.cn/Article/details/gthsnzrqpb.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gtycuazace.html

int a = 10; printf("%d\n", a);
来源：http://dali.yonumen.top/Article/details/gtoqrpkybe.html

[S03] C：读入整数
来源：http://dali.aibaodan.cn/Article/details/gtdelnjkoc.html

int x; scanf("%d", &x);
来源：http://dali.jqgfzy.top/Article/details/gtgixvzzdn.html

[S04] C：字符串复制
来源：http://dali.andypj.xyz/Article/details/gtdcujyjla.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.0kj1m.cn/Article/details/gttbrxgrfs.html

[S05] C：字符串长度
来源：http://dali.wangshuangyany.cn/Article/details/gteumfqwoi.html

strlen(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtexxcphes.html

[S06] C：字符串比较
来源：http://dali.yueranfly.top/Article/details/gtdhfumxiw.html

strcmp(a, b) == 0
来源：http://dali.pycfn.com/Article/details/gtnmnntdzt.html

[S07] C：数组遍历求和
来源：http://dali.yonumen.top/Article/details/gtispzrxne.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yongpay.top/Article/details/gtnvkerwee.html

[S08] C：动态内存分配与释放
来源：http://dali.wangdashe.top/Article/details/gtkvtpqbsc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtytbfcllq.html

[S09] C：结构体定义与初始化
来源：http://dali.sysykeji.top/Article/details/gtqxfkfwbn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xuanzx.com/Article/details/gtnjnwzbkc.html

[S10] C：指针与解引用
来源：http://dali.zhengqikj.top/Article/details/gtjpdauirn.html

int *p = &a;  *p = 5;
来源：http://dali.zhongyouzk.top/Article/details/gtncawnzwl.html

[S11] C：逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gtyhgqxkid.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ydzc1.top/Article/details/gtkbssrhed.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.chenzaomai.com/Article/details/gtqdwkttpb.html

fclose(f);
来源：http://dali.pengpengdd.cyou/Article/details/gtffurrkab.html

[S12] C：写文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gteqweuwls.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.guowangkeji.top/Article/details/gtepxmyben.html

[S13] C：宏定义
来源：http://dali.bjfxy.top/Article/details/gtbklhmffp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jyoumei.cn/Article/details/gtushjzwfp.html

[S14] C：枚举
来源：http://dali.yvedp.cn/Article/details/gtywyjruix.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ybcxt.top/Article/details/gttptxaoql.html

[S15] C：类型转换
来源：http://dali.aibaodan.cn/Article/details/gtugjpxshn.html

(double) a / b
来源：http://dali.jqgfzy.top/Article/details/gtgxxejdco.html

[S16] C：位操作置位
来源：http://dali.ehwqpu.com/Article/details/gtpsyynaqr.html

x |= (1 << 3);
来源：http://dali.nwbrower.top/Article/details/gtkjjcaqep.html

[S17] C：安全拼接字符串
来源：http://dali.andypj.xyz/Article/details/gtncarjcxk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cdnleiting.top/Article/details/gtenuyzxzc.html

[S18] C：命令行参数
来源：http://dali.chenjidiqi.icu/Article/details/gtfofqozdv.html

int main(int argc, char **argv)
来源：http://dali.aibaodan.cn/Article/details/gtfdwrkuet.html

[S19] C：快速排序
来源：http://dali.svipenyu.cn/Article/details/gthlozhczg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.tian-w.cn/Article/details/gtlqohqtos.html

[S20] C：二分查找
来源：http://dali.chenzaomai.com/Article/details/gtpxqbpvro.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jqgfzy.top/Article/details/gtwxvlfxhs.html

[S21] C：字符类别判断
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdtqqlaja.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.snrcjt.cn/Article/details/gtbvwmmege.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gtqjeegcep.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfajxbhyf.html

[S23] C：随机数
来源：http://dali.iojbl.cn/Article/details/gtveqdfzqe.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yuxming.cn/Article/details/gtgwyjhcbz.html

[S24] C：获取本地时间
来源：http://dali.jinghuilouyu.cn/Article/details/gtbmwdrzte.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.pengpengdd.cyou/Article/details/gtsyantnwu.html

[S25] C：内存拷贝
来源：http://dali.jinqigufen.top/Article/details/gtjbjmprcf.html

memcpy(dst, src, n);
来源：http://dali.mhx1999.top/Article/details/gtbuidffoh.html

[S26] C：内存清零
来源：http://dali.zhiwuduotai.top/Article/details/gthfjchyml.html

memset(a, 0, sizeof a);
来源：http://dali.ybcxt.top/Article/details/gtjoeubjvd.html

[S27] C：定义常量
来源：http://dali.xuetiantiany.cn/Article/details/gtgdmiwhpd.html

const double PI = 3.14159;
来源：http://dali.316326.xyz/Article/details/gtuizvflxy.html

[S28] C：静态变量
来源：http://dali.shangyingyoupin.top/Article/details/gtbqiasmpo.html

static int counter = 0;
来源：http://dali.jqgfzy.top/Article/details/gtqpazniky.html

[S29] C：变参函数
来源：http://dali.xinyue.icu/Article/details/gtxhhaqdtc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.316326.xyz/Article/details/gtuzcecdmg.html

[S30] C：头文件保护
来源：http://dali.316326.xyz/Article/details/gtbzorhwxh.html

#ifndef X_H
来源：http://dali.birdmap.top/Article/details/gtywuauspg.html

#define X_H
来源：http://dali.guannengcc.top/Article/details/gtscshrzqb.html

#endif
来源：http://dali.jinqigufen.top/Article/details/gtpwgtdfqh.html

[S31] C++：Hello World
来源：http://dali.hnqzz.top/Article/details/gtwaaidoby.html

#include <iostream>
来源：http://dali.jianghu66.top/Article/details/gtfuvyslmh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sysykeji.top/Article/details/gtphgffdcg.html

[S32] C++：字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvtxbrkrr.html

std::string s = "hi";  s += "!";
来源：http://dali.daria6918.cn/Article/details/gtaifkugno.html

[S33] C++：vector 增删
来源：http://dali.kuanghao11.cn/Article/details/gtokgspjsj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hongshengwenyu.top/Article/details/gtjwhqxqtb.html

[S34] C++：遍历 vector
来源：http://dali.0kj1m.cn/Article/details/gtrtrsykft.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yongpay.top/Article/details/gtxdizhbwp.html

[S35] C++：map
来源：http://dali.jinghuilouyu.cn/Article/details/gtpjxdrhbo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258888.top/Article/details/gtrmvqmsyw.html

[S36] C++：unordered_map
来源：http://dali.9152youxi.cn/Article/details/gtzritzugm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hnqzz.top/Article/details/gtxjvvqfrz.html

[S37] C++：set
来源：http://dali.sxryk.cn/Article/details/gtslrmvppg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj20258888.top/Article/details/gtkgxzzxfs.html

[S38] C++：排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwxdmrzey.html

std::sort(v.begin(), v.end());
来源：http://dali.gaohongyu789.top/Article/details/gttxwmifcp.html

[S39] C++：自定义比较器排序
来源：http://dali.hfpthk.cn/Article/details/gtlsxdvxow.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yanxiufei.cn/Article/details/gtahhxweqv.html

[S40] C++：查找元素
来源：http://dali.gotoacloud.top/Article/details/gtctyhvgtk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.kuanghao11.cn/Article/details/gtokmhhnih.html

[S41] C++：类与构造函数
来源：http://dali.haohaochexian.top/Article/details/gtphptpikv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnfkolhgx.html

[S42] C++：继承与虚函数
来源：http://dali.jiagoushi.top/Article/details/gtiexbdsrq.html

class B : public Base { public: void f() override {} };
来源：http://dali.gaohongyu789.top/Article/details/gtldysrvnw.html

[S43] C++：智能指针
来源：http://dali.daria6918.cn/Article/details/gtrephkukh.html

auto p = std::make_unique<int>(5);
来源：http://dali.fzhhl.top/Article/details/gtaddcavdo.html

[S44] C++：引用传参
来源：http://dali.andypj.xyz/Article/details/gtkwayeeeh.html

void inc(int &x) { ++x; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbkzwkjfj.html

[S45] C++：lambda
来源：http://dali.yonumen.top/Article/details/gtrguayxxw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.smart0.xyz/Article/details/gtuhwenxbt.html

[S46] C++：函数模板
来源：http://dali.zhengqikj.top/Article/details/gtuhdsqdfr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtykezddyw.html

[S47] C++：结构化绑定遍历
来源：http://dali.dashuyun.cn/Article/details/gtcfsdubyr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ehwqpu.com/Article/details/gtujsoznaw.html

[S48] C++：逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gtapcoaeug.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gotoacloud.top/Article/details/gtbcwupciy.html

while (std::getline(in, line)) { }
来源：http://dali.dianchejie.cn/Article/details/gttglbtnts.html

[S49] C++：写文件
来源：http://dali.yonumen.top/Article/details/gtirxfcvdz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hnqzz.top/Article/details/gtdttcioyb.html

[S50] C++：格式化数字
来源：http://dali.quarkkingdee.top/Article/details/gtztiuowpm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gtkhjdoinc.html

[S51] C++：显式类型转换
来源：http://dali.yongpay.top/Article/details/gtxeeakhty.html

static_cast<double>(a) / b
来源：http://dali.zhijiandao.cn/Article/details/gtcqgzgszc.html

[S52] C++：const 与 noexcept
来源：http://dali.jinghuilouyu.cn/Article/details/gtdixoqzbu.html

int size() const noexcept { return n_; }
来源：http://dali.jiagoushi.top/Article/details/gtonpxqqfe.html

[S53] C++：移动语义
来源：http://dali.nwbrower.top/Article/details/gtegdfwncf.html

std::vector<int> w = std::move(v);
来源：http://dali.sweek.top/Article/details/gtqtikfniv.html

[S54] C++：异常处理
来源：http://dali.jianghu66.top/Article/details/gtyennnwwr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hnqzz.top/Article/details/gtzhmerbez.html

[S55] C++：结构化绑定
来源：http://dali.shangyingyoupin.top/Article/details/gtowqquduc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zdqjudy.top/Article/details/gtwumwnzgb.html

[S56] C++：optional
来源：http://dali.jianghu66.top/Article/details/gtlgijkohs.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinqigufen.top/Article/details/gtzcwlgwah.html

[S57] C++：编译期常量
来源：http://dali.zhixingplan.top/Article/details/gtffhmlasj.html

constexpr int N = 10;
来源：http://dali.yj202588.top/Article/details/gtfqjnwzfn.html

[S58] C++：命名空间
来源：http://dali.svipenyu.cn/Article/details/gtbwwfovtr.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj20258.top/Article/details/gtnrbxygad.html

[S59] C++：静态断言
来源：http://dali.pengpengdd.cyou/Article/details/gtdwhrtbae.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.smart0.xyz/Article/details/gtzgspjwyo.html

[S60] C++：遍历并删除元素
来源：http://dali.cqqwz.cn/Article/details/gtppnbzgkj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.fengsongda.top/Article/details/gtypugovmy.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtfyvvmtsf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cheryme.top/Article/details/gtuqjaukki.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtaqmibumm.html

[T01] Kotlin：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtzbpgqdzw.html

println("Hello")
来源：http://dali.jianghu66.top/Article/details/gtxcwvdzxm.html

[T02] Kotlin：变量
来源：http://dali.yj20258.top/Article/details/gtmuktpuzv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.wangshuangyany.cn/Article/details/gtzaenvvvn.html

[T03] Kotlin：字符串模板
来源：http://dali.shanyushiyangtech.top/Article/details/gtjgosxhth.html

"值: $b"
来源：http://dali.zdqjudy.top/Article/details/gtpksklsrh.html

[T04] Kotlin：空安全
来源：http://dali.yonumen.top/Article/details/gtqxlchxut.html

val n: String? = null;  n?.length
来源：http://dali.birdmap.top/Article/details/gteesppdbp.html

[T05] Kotlin：when 表达式
来源：http://dali.jyoumei.cn/Article/details/gtrcqyddky.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ehwqpu.com/Article/details/gtoskaejls.html

[T06] Kotlin：集合映射
来源：http://dali.dashuyun.cn/Article/details/gtlcexzpmp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ydzc1.top/Article/details/gtkhhmklsg.html

[T07] Kotlin：集合过滤
来源：http://dali.daxiang520.top/Article/details/gtuejerlso.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjsptfigo.html

[T08] Kotlin：数据类
来源：http://dali.zhiwuduotai.top/Article/details/gteiqeycik.html

data class User(val name: String, val age: Int)
来源：http://dali.cheryme.top/Article/details/gtjxrbdohl.html

[T09] Kotlin：扩展函数
来源：http://dali.hysaishi.cn/Article/details/gtapkearmc.html

fun String.exclaim() = this + "!"
来源：http://dali.zhoulong.xyz/Article/details/gtpomflvdg.html

[T10] Kotlin：默认参数
来源：http://dali.zhixingplan.top/Article/details/gtbothcozc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrwfwsaog.html

[T11] Kotlin：协程
来源：http://dali.zhoulong.xyz/Article/details/gtsicyipwk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sweek.top/Article/details/gtiplyhcoi.html

[T12] Kotlin：解构声明
来源：http://dali.daxiang520.top/Article/details/gtsamjbwxz.html

val (a, b) = Pair(1, 2)
来源：http://dali.tianlin.xyz/Article/details/gtlwlryyaf.html

[T13] Kotlin：只读 Map
来源：http://dali.zhongyouzk.top/Article/details/gterrlhebj.html

val m = mapOf("a" to 1)
来源：http://dali.ehwqpu.com/Article/details/gtaxebivlt.html

[T14] Kotlin：循环
来源：http://dali.jqgfzy.top/Article/details/gtfsitrhit.html

for (i in 1..10) println(i)
来源：http://dali.havefunace.top/Article/details/gtkeylaakk.html

[T15] Kotlin：接口
来源：http://dali.hfpthk.cn/Article/details/gtgyaopcjk.html

interface Shape { fun area(): Double }
来源：http://dali.cashguo.top/Article/details/gtctrnnjts.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtcrcblhjf.html

print("Hello")
来源：http://dali.wangdashe.top/Article/details/gtwmuluunj.html

[T17] Swift：变量与常量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnchbfrgg.html

var a = 1;  let b = 2
来源：http://dali.sweek.top/Article/details/gtvrylzomm.html

[T18] Swift：字符串插值
来源：http://dali.yanxiufei.cn/Article/details/gtgtpqmvbp.html

"值: \(b)"
来源：http://dali.dianchejie.cn/Article/details/gtwwtmaium.html

[T19] Swift：可选绑定
来源：http://dali.snrcjt.cn/Article/details/gtvylrqpeh.html

if let n = opt { print(n) }
来源：http://dali.jianghu66.top/Article/details/gtlodmqmkj.html

[T20] Swift：数组操作
来源：http://dali.jianghu66.top/Article/details/gtpsbhudpn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jqgfzy.top/Article/details/gtdcymxdjw.html

[T21] Swift：遍历
来源：http://dali.chenjidiqi.icu/Article/details/gtrhfwmfyu.html

for x in a { print(x) }
来源：http://dali.ehwqpu.com/Article/details/gtdftozsyj.html

[T22] Swift：字典
来源：http://dali.zhoulong.xyz/Article/details/gtlzjgfawj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.meibo888.top/Article/details/gtjykfargx.html

[T23] Swift：函数
来源：http://dali.jinqigfzy.top/Article/details/gtcetazgjb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.iojbl.cn/Article/details/gtpfaubtko.html

[T24] Swift：闭包
来源：http://dali.xylfe.cn/Article/details/gtjyhwtvsv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzgvlfzho.html

[T25] Swift：结构体
来源：http://dali.zhijiandao.cn/Article/details/gtgncnvctr.html

struct P { var x: Int }
来源：http://dali.feifeiyinyue.top/Article/details/gtvmzzfdux.html

[T26] Swift：类与重写
来源：http://dali.9152youxi.cn/Article/details/gtuhjnhifq.html

class A: Base { override func f() {} }
来源：http://dali.yvedp.cn/Article/details/gtvjvbiwrt.html

[T27] Swift：错误处理
来源：http://dali.tianlin.xyz/Article/details/gtrodgwbgp.html

do { try f() } catch { print(error) }
来源：http://dali.shzxlz.cn/Article/details/gtjuxbmahi.html

[T28] Swift：枚举
来源：http://dali.tanke756.top/Article/details/gtsabgumso.html

enum Color { case red, green }
来源：http://dali.birdmap.top/Article/details/gtyfjlhxvz.html

[T29] Swift：guard 提前返回
来源：http://dali.yj20258.top/Article/details/gtdyofzugs.html

guard let x = opt else { return }
来源：http://dali.wangshuangyany.cn/Article/details/gtxcnqsgvt.html

[T30] Swift：协议
来源：http://dali.nanxinkj.top/Article/details/gtvzzjrpxq.html

protocol Shape { func area() -> Double }
来源：http://dali.yanxiufei.cn/Article/details/gtlfaqxphr.html

[T31] Lua：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtfigbdcnq.html

print("Hello")
来源：http://dali.9152youxi.cn/Article/details/gtxmzhlbpn.html

[T32] Lua：局部变量
来源：http://dali.wangshuangyany.cn/Article/details/gtmlitcamh.html

local a = 1
来源：http://dali.jianghu66.top/Article/details/gtsytxjztx.html

[T33] Lua：表（数组）
来源：http://dali.jinqigfzy.top/Article/details/gtyewwjaqo.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xuetiantiany.cn/Article/details/gthshtecye.html

[T34] Lua：遍历表
来源：http://dali.hnxiangtu.top/Article/details/gtqzuawodw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jlsjyb.cn/Article/details/gtgwwbowdt.html

[T35] Lua：字典表
来源：http://dali.hammf.cn/Article/details/gtlqltnzvm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hysaishi.cn/Article/details/gtjnetkkfk.html

[T36] Lua：函数
来源：http://dali.jqgfzy.top/Article/details/gthicpfbtc.html

function add(a, b) return a + b end
来源：http://dali.tianlin.xyz/Article/details/gtmcwkxfir.html

[T37] Lua：字符串拼接
来源：http://dali.jianghu66.top/Article/details/gtvfvknpvp.html

"a" .. "b"
来源：http://dali.hnxiangtu.top/Article/details/gtyyflldpf.html

[T38] Lua：条件
来源：http://dali.xuetiantiany.cn/Article/details/gtbjzpsgkr.html

if x > 0 then print("正") end
来源：http://dali.xuetiantiany.cn/Article/details/gtfxjvxwhe.html

[T39] Lua：模式匹配
来源：http://dali.feifeiyinyue.top/Article/details/gtgpjexudg.html

string.find(s, "%d+")
来源：http://dali.cashguo.top/Article/details/gtkpvkayoz.html

[T40] Lua：元表
来源：http://dali.chenlongwang.top/Article/details/gtmvodvqhl.html

setmetatable({}, { __index = base })
来源：http://dali.chenjidiqi.icu/Article/details/gttsukqsoz.html

[T41] Perl：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtwiltuqxe.html

print "Hello\n";
来源：http://dali.pycfn.com/Article/details/gtxgxtzrza.html

[T42] Perl：变量类型
来源：http://dali.ppjwa.cn/Article/details/gtupsphsvp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.feifeiyinyue.top/Article/details/gtgijesyjz.html

[T43] Perl：字符串插值
来源：http://dali.nwbrower.top/Article/details/gtgcoyspmv.html

"值: $a"
来源：http://dali.jqgfzy.top/Article/details/gtkpvyydfy.html

[T44] Perl：条件
来源：http://dali.shzxlz.cn/Article/details/gtfitlicul.html

if ($a > 0) { print "正"; }
来源：http://dali.xuanzx.com/Article/details/gthegljdvb.html

[T45] Perl：数组遍历
来源：http://dali.yj202588.top/Article/details/gtufxjkfse.html

for my $x (@arr) { print $x; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtyosfplrk.html

[T46] Perl：哈希操作
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtllxhuxgi.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jianghu66.top/Article/details/gtqetrhzvm.html

[T47] Perl：正则捕获
来源：http://dali.jqgufenzy.top/Article/details/gtnrccvpgv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.wangdashe.top/Article/details/gtavqwttwm.html

[T48] Perl：正则替换
来源：http://dali.yj20258.top/Article/details/gtzzkuhxxk.html

$s =~ s/old/new/g;
来源：http://dali.shanyushiyangtech.top/Article/details/gtwvnygndz.html

[T49] Perl：函数
来源：http://dali.ybcxt.top/Article/details/gtzaixjweq.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.c1oappe.top/Article/details/gtvbsyjzwx.html

[T50] Perl：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gttnrlaxxg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.redwolf501.top/Article/details/gtsmbbzeyt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jiagoushi.top/Article/details/gtcgplmufk.html

[T51] Scala：Hello World
来源：http://dali.yvedp.cn/Article/details/gtsvaxztlv.html

println("Hello")
来源：http://dali.cdnleiting.top/Article/details/gtfsghwuba.html

[T52] Scala：变量
来源：http://dali.daxiang520.top/Article/details/gteqreitwu.html

val a = 1;  var b = 2
来源：http://dali.nanxinkj.top/Article/details/gtgoxibmcj.html

[T53] Scala：字符串插值
来源：http://dali.yanxiufei.cn/Article/details/gtxouywodc.html

s"值: $b"
来源：http://dali.chenzaomai.com/Article/details/gtrbmsutar.html

[T54] Scala：集合映射
来源：http://dali.fzhhl.top/Article/details/gtilihxbji.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cqqwz.cn/Article/details/gtmxqegwul.html

[T55] Scala：集合过滤
来源：http://dali.xuetiantiany.cn/Article/details/gtvvxhpogf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yueranfly.top/Article/details/gtuyjgfmbq.html

[T56] Scala：样例类
来源：http://dali.hnqzz.top/Article/details/gtxqipzrlz.html

case class User(name: String, age: Int)
来源：http://dali.xziqi.cn/Article/details/gtknredaai.html

[T57] Scala：模式匹配
来源：http://dali.yj20258888.top/Article/details/gtxxpvpkqp.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.guowangkeji.top/Article/details/gtzutkervd.html

[T58] Scala：函数定义
来源：http://dali.nanxinkj.top/Article/details/gtiakcmwod.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xuetiantiany.cn/Article/details/gtzuikjsyt.html

[T59] Scala：循环
来源：http://dali.chenjidiqi.icu/Article/details/gthyncpqto.html

for (i <- 1 to 10) println(i)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxmlxdizh.html

[T60] Scala：折叠
来源：http://dali.cheryme.top/Article/details/gtfrrntxzg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sufxvd.cn/Article/details/gtdxvdytmt.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtvvngytnm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hywenlv.cn/Article/details/gtxmrazfye.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtpnsdywaf.html

[U01] Py：创建虚拟环境
来源：http://dali.ehwqpu.com/Article/details/gtenkjuizq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhixingplan.top/Article/details/gthxpempcw.html

[U02] Py：导出 / 安装依赖
来源：http://dali.nwbrower.top/Article/details/gtykvahcnc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xuanzx.com/Article/details/gtizcapzbj.html

[U03] Py：加载 .env 配置
来源：http://dali.andypj.xyz/Article/details/gtmxssyaen.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.vqdsnc.cn/Article/details/gtmpowesxx.html

[U04] Py：变量调试打印
来源：http://dali.zhiwuduotai.top/Article/details/gtzpowbaop.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbtqwlcsu.html

[U05] Py：列表去重且保序
来源：http://dali.pengpengdd.cyou/Article/details/gtpcojaytp.html

list(dict.fromkeys(arr))
来源：http://dali.hnxiangtu.top/Article/details/gtdxkbuazl.html

[U06] Py：合并两个字典
来源：http://dali.iojbl.cn/Article/details/gtaghtcevw.html

{**a, **b}
来源：http://dali.daria6918.cn/Article/details/gtpaqnswvu.html

[U07] Py：反转字典键值
来源：http://dali.shanyushiyangtech.top/Article/details/gtyoimmhet.html

{v: k for k, v in d.items()}
来源：http://dali.cucudq.cn/Article/details/gtwlmseguj.html

[U08] Py：展平二维列表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoaxvssue.html

[y for x in nested for y in x]
来源：http://dali.9152youxi.cn/Article/details/gttdyicsml.html


<!-- 参考信息 -->