代发 wailian999

openssl rand -hex 16
来源：http://dali.havefunace.top/Article/details/gtggmbwthp.html

[R68] 计算文件校验值
来源：http://dali.wangshuangyany.cn/Article/details/gtoaffritv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzylfcoze.html

[R69] 生成随机密码
来源：http://dali.cashguo.top/Article/details/gtpochqrhr.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhengqikj.top/Article/details/gtqgozazzj.html

[R70] 时间戳与互转
来源：http://dali.c1oappe.top/Article/details/gtjktwlepv.html

date +%s;  date -d @1700000000
来源：http://dali.xuetiantiany.cn/Article/details/gtrpzwuike.html

[R71] 日期格式化
来源：http://dali.gzhubu.top/Article/details/gteiwvbdcb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj20258.top/Article/details/gtxlndaevc.html

[R72] 等待端口就绪
来源：http://dali.zhixingplan.top/Article/details/gtfgdaywbu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shuidangran.top/Article/details/gtovbkbrei.html

[R73] 分割大日志
来源：http://dali.shuidangran.top/Article/details/gtogpxklen.html

split -l 1000 big.log part_
来源：http://dali.yvedp.cn/Article/details/gtkxbjatih.html

[R74] 批量重命名
来源：http://dali.chenzaomai.com/Article/details/gtdwclkvwj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cucudq.cn/Article/details/gtjjkrzdyo.html

[R75] 导出环境变量
来源：http://dali.haohaochexian.top/Article/details/gtgemyhiph.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yuanzhike.top/Article/details/gthpslcohy.html

[R76] 使用临时文件
来源：http://dali.quarkkingdee.top/Article/details/gtpcoovjbk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxuanxn.top/Article/details/gtgajkjqko.html

[R77] 读取用户输入
来源：http://dali.wangshuangyany.cn/Article/details/gtjnqrthcy.html

read -rp "请输入: " ans
来源：http://dali.nanxuanxn.top/Article/details/gtykplvshq.html

[R78] 交互式菜单
来源：http://dali.cheryme.top/Article/details/gtadnnyymp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.fengsongda.top/Article/details/gtlpzmzzaq.html

[R79] 解析命令行选项
来源：http://dali.fengsongda.top/Article/details/gtvnqeexcl.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.pycfn.com/Article/details/gtjkfpgxpi.html

[R80] 查看脚本执行耗时
来源：http://dali.aibaodan.cn/Article/details/gtzkjobkaq.html

time ./run.sh
来源：http://dali.shanyushiyangtech.top/Article/details/gtvtvajycc.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtfpiyvysv.html

S. C / C++ 专题
来源：http://dali.sysykeji.top/Article/details/gtanngvdqs.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtdeghvqkg.html

[S01] C：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtdqpcqnqa.html

#include <stdio.h>
来源：http://dali.yj20258.top/Article/details/gtljfegejk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ivvv.top/Article/details/gtugbqozhs.html

[S02] C：变量与格式化输出
来源：http://dali.jiagoushi.top/Article/details/gtvvaxlmtn.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvegsfick.html

[S03] C：读入整数
来源：http://dali.gzhubu.top/Article/details/gtwmicwhsb.html

int x; scanf("%d", &x);
来源：http://dali.chenzaomai.com/Article/details/gtyvpksamo.html

[S04] C：字符串复制
来源：http://dali.zhiwuduotai.top/Article/details/gtdweumhud.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhoulong.xyz/Article/details/gtdzpvyvwz.html

[S05] C：字符串长度
来源：http://dali.jqgufenzy.top/Article/details/gteoprmocr.html

strlen(s)
来源：http://dali.jinqigfzy.top/Article/details/gtfrhdtjek.html

[S06] C：字符串比较
来源：http://dali.aibaodan.cn/Article/details/gtjavkfezt.html

strcmp(a, b) == 0
来源：http://dali.0kj1m.cn/Article/details/gtvanbkhwl.html

[S07] C：数组遍历求和
来源：http://dali.shuidangran.top/Article/details/gtypuqbewx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hywenlv.cn/Article/details/gtmbvvbteu.html

[S08] C：动态内存分配与释放
来源：http://dali.hammf.cn/Article/details/gtpuzyudwr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.pycfn.com/Article/details/gtrmnratgd.html

[S09] C：结构体定义与初始化
来源：http://dali.jlsjyb.cn/Article/details/gtbpfhkfth.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.pycfn.com/Article/details/gtlxcggnyx.html

[S10] C：指针与解引用
来源：http://dali.jinqigfzy.top/Article/details/gtokjkjbtv.html

int *p = &a;  *p = 5;
来源：http://dali.pengpengdd.cyou/Article/details/gtpornhjqc.html

[S11] C：逐行读文件
来源：http://dali.fzhhl.top/Article/details/gttujmfyjw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shangyingyoupin.top/Article/details/gthjmqrjbu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yj20258888.top/Article/details/gtzvdnhjsm.html

fclose(f);
来源：http://dali.0kj1m.cn/Article/details/gthfklvaku.html

[S12] C：写文件
来源：http://dali.daria6918.cn/Article/details/gtcfnulaic.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.316326.xyz/Article/details/gtjmbxykze.html

[S13] C：宏定义
来源：http://dali.sweek.top/Article/details/gtjpthqgow.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.nanxinkj.top/Article/details/gtkvwowimd.html

[S14] C：枚举
来源：http://dali.xuetiantiany.cn/Article/details/gtmonavfwh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.meibo888.top/Article/details/gtlxsytqrn.html

[S15] C：类型转换
来源：http://dali.yangfankeji.com/Article/details/gtjujfpxwh.html

(double) a / b
来源：http://dali.yj20258888.top/Article/details/gtnyxvhuao.html

[S16] C：位操作置位
来源：http://dali.hammf.cn/Article/details/gtqnneqdqa.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gticpkpskh.html

[S17] C：安全拼接字符串
来源：http://dali.c1oappe.top/Article/details/gtapmtdsqy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cdnleiting.top/Article/details/gthqphwqxc.html

[S18] C：命令行参数
来源：http://dali.yonumen.top/Article/details/gtfnfncboo.html

int main(int argc, char **argv)
来源：http://dali.wangshuangyany.cn/Article/details/gtmmuzhcxp.html

[S19] C：快速排序
来源：http://dali.fzhhl.top/Article/details/gtxoezhhct.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.birdmap.top/Article/details/gtcctslwls.html

[S20] C：二分查找
来源：http://dali.zhongyouzk.top/Article/details/gtqhldtezt.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xinyue.icu/Article/details/gtovghpgts.html

[S21] C：字符类别判断
来源：http://dali.sysykeji.top/Article/details/gtohzmpcvd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.quarkkingdee.top/Article/details/gtdxkxftgh.html

[S22] C：字符串转数字
来源：http://dali.cucudq.cn/Article/details/gtniojbobh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtezdrxjwo.html

[S23] C：随机数
来源：http://dali.nwbrower.top/Article/details/gtxqmjyssi.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zycfv.cn/Article/details/gtwgbhczjv.html

[S24] C：获取本地时间
来源：http://dali.hfpthk.cn/Article/details/gtkqccaxcr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlwwojubs.html

[S25] C：内存拷贝
来源：http://dali.yj20258888.top/Article/details/gtmuzwlegg.html

memcpy(dst, src, n);
来源：http://dali.guannengcc.top/Article/details/gtankgstof.html

[S26] C：内存清零
来源：http://dali.daria6918.cn/Article/details/gtfounjbdv.html

memset(a, 0, sizeof a);
来源：http://dali.316326.xyz/Article/details/gtgdxandnn.html

[S27] C：定义常量
来源：http://dali.havefunace.top/Article/details/gtfnnuanaj.html

const double PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gtvsdezalt.html

[S28] C：静态变量
来源：http://dali.tanke756.top/Article/details/gtsaotxcym.html

static int counter = 0;
来源：http://dali.quarkkingdee.top/Article/details/gtyifsqgbp.html

[S29] C：变参函数
来源：http://dali.chenzaomai.com/Article/details/gtqjxqgwkj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gtkloxnjwh.html

[S30] C：头文件保护
来源：http://dali.vqdsnc.cn/Article/details/gtwzgqejaf.html

#ifndef X_H
来源：http://dali.havefunace.top/Article/details/gttmyqckeu.html

#define X_H
来源：http://dali.hammf.cn/Article/details/gtspsljste.html

#endif
来源：http://dali.c1oappe.top/Article/details/gtpfteghth.html

[S31] C++：Hello World
来源：http://dali.ybcxt.top/Article/details/gtorrkwfsl.html

#include <iostream>
来源：http://dali.svipenyu.cn/Article/details/gtwfuplazd.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gotoacloud.top/Article/details/gtpiiypkqb.html

[S32] C++：字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtmuxhnnkq.html

std::string s = "hi";  s += "!";
来源：http://dali.fzhhl.top/Article/details/gtuewfgxve.html

[S33] C++：vector 增删
来源：http://dali.meibo888.top/Article/details/gtyijlccpg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.vqdsnc.cn/Article/details/gtrqktftbm.html

[S34] C++：遍历 vector
来源：http://dali.nanxuanxn.top/Article/details/gtyrrkoooi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sweek.top/Article/details/gtqbeqmzjv.html

[S35] C++：map
来源：http://dali.zhengqikj.top/Article/details/gtghfmwkfc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yangfankeji.com/Article/details/gtrllrjhtk.html

[S36] C++：unordered_map
来源：http://dali.aibaodan.cn/Article/details/gtoquyejza.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gtamubnwsp.html

[S37] C++：set
来源：http://dali.yanxiufei.cn/Article/details/gthqbziuyu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yueranfly.top/Article/details/gtzffjbvsl.html

[S38] C++：排序
来源：http://dali.ydzc1.top/Article/details/gtweatlxdh.html

std::sort(v.begin(), v.end());
来源：http://dali.snrcjt.cn/Article/details/gtexlbsrde.html

[S39] C++：自定义比较器排序
来源：http://dali.ybcxt.top/Article/details/gtyeuurgfq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.guannengcc.top/Article/details/gtxhwcfneg.html

[S40] C++：查找元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtedutvfqb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xziqi.cn/Article/details/gtqeesyltb.html

[S41] C++：类与构造函数
来源：http://dali.meibo888.top/Article/details/gtylgnsekc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.bjfxy.top/Article/details/gturrmcnqi.html

[S42] C++：继承与虚函数
来源：http://dali.hnxiangtu.top/Article/details/gtwmmgnooj.html

class B : public Base { public: void f() override {} };
来源：http://dali.dashuyun.cn/Article/details/gtlgcqqdah.html

[S43] C++：智能指针
来源：http://dali.hysaishi.cn/Article/details/gtdqdibshu.html

auto p = std::make_unique<int>(5);
来源：http://dali.shangyingyoupin.top/Article/details/gtuiwdxwot.html

[S44] C++：引用传参
来源：http://dali.chenlongwang.top/Article/details/gtoywjyizt.html

void inc(int &x) { ++x; }
来源：http://dali.ehwqpu.com/Article/details/gtudllgjyn.html

[S45] C++：lambda
来源：http://dali.pengpengdd.cyou/Article/details/gtvtdmubtf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ivvv.top/Article/details/gteeieggkg.html

[S46] C++：函数模板
来源：http://dali.jianghu66.top/Article/details/gtvfaghlox.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.quarkkingdee.top/Article/details/gtrojrzlsm.html

[S47] C++：结构化绑定遍历
来源：http://dali.jqgufenzy.top/Article/details/gtfzpvzohh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.feifeiyinyue.top/Article/details/gtfsjuwyhq.html

[S48] C++：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gtjnkfjkoc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.haohaochexian.top/Article/details/gthqimilvh.html

while (std::getline(in, line)) { }
来源：http://dali.meibo888.top/Article/details/gtcjounyms.html

[S49] C++：写文件
来源：http://dali.yvedp.cn/Article/details/gthjiwvcrt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shzxlz.cn/Article/details/gtbecknuho.html

[S50] C++：格式化数字
来源：http://dali.zhoulong.xyz/Article/details/gtznnhiqox.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gtngzcclml.html

[S51] C++：显式类型转换
来源：http://dali.yongpay.top/Article/details/gttnsrppfw.html

static_cast<double>(a) / b
来源：http://dali.guannengcc.top/Article/details/gtjxnbaefr.html

[S52] C++：const 与 noexcept
来源：http://dali.havefunace.top/Article/details/gtwuvbofrf.html

int size() const noexcept { return n_; }
来源：http://dali.yuanzhike.top/Article/details/gtmkdfhfve.html

[S53] C++：移动语义
来源：http://dali.jinghuilouyu.cn/Article/details/gtoynzwdxo.html

std::vector<int> w = std::move(v);
来源：http://dali.nwbrower.top/Article/details/gtswhxxbbt.html

[S54] C++：异常处理
来源：http://dali.xziqi.cn/Article/details/gtxgmvljnh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj20258.top/Article/details/gtwdghambb.html

[S55] C++：结构化绑定
来源：http://dali.sxryk.cn/Article/details/gtlpdjvbhc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhengqikj.top/Article/details/gtuusruusv.html

[S56] C++：optional
来源：http://dali.yj202588.top/Article/details/gtqkvompad.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sweek.top/Article/details/gtsevmvwsd.html

[S57] C++：编译期常量
来源：http://dali.haohaochexian.top/Article/details/gtsbdokiqz.html

constexpr int N = 10;
来源：http://dali.c1oappe.top/Article/details/gtmdnqjrxq.html

[S58] C++：命名空间
来源：http://dali.tanke756.top/Article/details/gtqublfsdw.html

namespace ns { int f() { return 1; } }
来源：http://dali.hysaishi.cn/Article/details/gtzmokjxtc.html

[S59] C++：静态断言
来源：http://dali.nanxuanxn.top/Article/details/gtrlrrwave.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.havefunace.top/Article/details/gtzaonjxrw.html

[S60] C++：遍历并删除元素
来源：http://dali.xziqi.cn/Article/details/gtpncqrrxy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ybcxt.top/Article/details/gtwkwlmaln.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gticazjogt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cqqwz.cn/Article/details/gtpkbmlmgh.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtwguietpv.html

[T01] Kotlin：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcaxxrtza.html

println("Hello")
来源：http://dali.cdnleiting.top/Article/details/gtflesfqlu.html

[T02] Kotlin：变量
来源：http://dali.cheryme.top/Article/details/gtdscatmmq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.iojbl.cn/Article/details/gtzrdzliet.html

[T03] Kotlin：字符串模板
来源：http://dali.andypj.xyz/Article/details/gtjoxeavie.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gtnypssadp.html

[T04] Kotlin：空安全
来源：http://dali.dianchejie.cn/Article/details/gtndymjhbf.html

val n: String? = null;  n?.length
来源：http://dali.shanyushiyangkeji.top/Article/details/gtperkryro.html

[T05] Kotlin：when 表达式
来源：http://dali.jyoumei.cn/Article/details/gthwkkonns.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zycfv.cn/Article/details/gttbxtgnow.html

[T06] Kotlin：集合映射
来源：http://dali.sxryk.cn/Article/details/gtuhpocjqa.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yuxming.cn/Article/details/gtmftlraib.html

[T07] Kotlin：集合过滤
来源：http://dali.yj202588.top/Article/details/gtimjclopj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuixtnwax.html

[T08] Kotlin：数据类
来源：http://dali.meibo888.top/Article/details/gtnprzbepu.html

data class User(val name: String, val age: Int)
来源：http://dali.snrcjt.cn/Article/details/gtzyeduwnf.html

[T09] Kotlin：扩展函数
来源：http://dali.gogol.net.cn/Article/details/gtwdhycodt.html

fun String.exclaim() = this + "!"
来源：http://dali.zdqjudy.top/Article/details/gttcxtngwq.html

[T10] Kotlin：默认参数
来源：http://dali.hfpthk.cn/Article/details/gttleymyft.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.birdmap.top/Article/details/gtkztjpznx.html

[T11] Kotlin：协程
来源：http://dali.zhixingplan.top/Article/details/gtqrrleooj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.nwbrower.top/Article/details/gtyqivwuxj.html

[T12] Kotlin：解构声明
来源：http://dali.hongshengwenyu.top/Article/details/gttaecwlzu.html

val (a, b) = Pair(1, 2)
来源：http://dali.hysaishi.cn/Article/details/gtueozmdrp.html

[T13] Kotlin：只读 Map
来源：http://dali.sufxvd.cn/Article/details/gtiomhmfsu.html

val m = mapOf("a" to 1)
来源：http://dali.yj20258888.top/Article/details/gtwmyzkiql.html

[T14] Kotlin：循环
来源：http://dali.zhongyouzk.top/Article/details/gtmwlvjpno.html

for (i in 1..10) println(i)
来源：http://dali.ybcxt.top/Article/details/gtivnjmtbd.html

[T15] Kotlin：接口
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbrgklbtb.html

interface Shape { fun area(): Double }
来源：http://dali.aizwys.cn/Article/details/gttknfbdbt.html

[T16] Swift：Hello World
来源：http://dali.xylfe.cn/Article/details/gtgmwkzvpc.html

print("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gthmjghwxt.html

[T17] Swift：变量与常量
来源：http://dali.jiagoushi.top/Article/details/gtfsristba.html

var a = 1;  let b = 2
来源：http://dali.zhengqikj.top/Article/details/gtjqkxfqpw.html

[T18] Swift：字符串插值
来源：http://dali.yuanzhike.top/Article/details/gtjdyacjnv.html

"值: \(b)"
来源：http://dali.yanxiufei.cn/Article/details/gtxxuycvug.html

[T19] Swift：可选绑定
来源：http://dali.chenlongwang.top/Article/details/gtammotbjd.html

if let n = opt { print(n) }
来源：http://dali.wangdashe.top/Article/details/gtgypuejea.html

[T20] Swift：数组操作
来源：http://dali.daxiang520.top/Article/details/gtuihnwuta.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.feifeiyinyue.top/Article/details/gtkeauyjny.html

[T21] Swift：遍历
来源：http://dali.yj20258.top/Article/details/gtqvpfcbei.html

for x in a { print(x) }
来源：http://dali.yuxming.cn/Article/details/gtwbvgkldm.html

[T22] Swift：字典
来源：http://dali.jlsjyb.cn/Article/details/gtadpgyxbv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.aizwys.cn/Article/details/gtkimkhnfd.html

[T23] Swift：函数
来源：http://dali.hnxiangtu.top/Article/details/gtpejegwqa.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.fengsongda.top/Article/details/gtqkjjgxqi.html

[T24] Swift：闭包
来源：http://dali.zhiwuduotai.top/Article/details/gtclzhbxfh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yangfankeji.com/Article/details/gtnkdvrwbw.html

[T25] Swift：结构体
来源：http://dali.sweek.top/Article/details/gtxejyrvlf.html

struct P { var x: Int }
来源：http://dali.aibaodan.cn/Article/details/gthesieqhj.html

[T26] Swift：类与重写
来源：http://dali.zdqjudy.top/Article/details/gtpffoxned.html

class A: Base { override func f() {} }
来源：http://dali.andypj.xyz/Article/details/gtocmmyjof.html

[T27] Swift：错误处理
来源：http://dali.xuetiantiany.cn/Article/details/gtnofpizno.html

do { try f() } catch { print(error) }
来源：http://dali.0kj1m.cn/Article/details/gtgzbzpkvl.html

[T28] Swift：枚举
来源：http://dali.yuxming.cn/Article/details/gthyncquhj.html

enum Color { case red, green }
来源：http://dali.chenzaomai.com/Article/details/gtauzvnvyg.html

[T29] Swift：guard 提前返回
来源：http://dali.c1oappe.top/Article/details/gtqyemyesa.html

guard let x = opt else { return }
来源：http://dali.guowangkeji.top/Article/details/gtuejnmkrx.html

[T30] Swift：协议
来源：http://dali.gzhubu.top/Article/details/gthhjgpetj.html

protocol Shape { func area() -> Double }
来源：http://dali.hongshengwenyu.top/Article/details/gtdwssaqpq.html

[T31] Lua：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtjbtaqbem.html

print("Hello")
来源：http://dali.pycfn.com/Article/details/gtylodwhml.html

[T32] Lua：局部变量
来源：http://dali.andypj.xyz/Article/details/gtokusgpwn.html

local a = 1
来源：http://dali.jqgufenzy.top/Article/details/gtqhujcjhz.html

[T33] Lua：表（数组）
来源：http://dali.ehwqpu.com/Article/details/gtrrnwbkgf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yuanzhike.top/Article/details/gtgyszmoia.html

[T34] Lua：遍历表
来源：http://dali.cheryme.top/Article/details/gtmxyknueh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.mhx1999.top/Article/details/gtobdeqewl.html

[T35] Lua：字典表
来源：http://dali.dashuyun.cn/Article/details/gtxnkdmhmz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtezgqocyl.html

[T36] Lua：函数
来源：http://dali.hfpthk.cn/Article/details/gtkxudyslc.html

function add(a, b) return a + b end
来源：http://dali.hywenlv.cn/Article/details/gtkutvkjew.html

[T37] Lua：字符串拼接
来源：http://dali.hnqzz.top/Article/details/gtprdfocty.html

"a" .. "b"
来源：http://dali.hammf.cn/Article/details/gtgmbxhuaa.html

[T38] Lua：条件
来源：http://dali.mhx1999.top/Article/details/gtwgjdwdbs.html

if x > 0 then print("正") end
来源：http://dali.yangfankeji.com/Article/details/gtwbkykdoy.html

[T39] Lua：模式匹配
来源：http://dali.zhongyouzk.top/Article/details/gtydnkkkny.html

string.find(s, "%d+")
来源：http://dali.chenjidiqi.icu/Article/details/gtmkpkqxrx.html

[T40] Lua：元表
来源：http://dali.xuetiantiany.cn/Article/details/gtaqycrlmp.html

setmetatable({}, { __index = base })
来源：http://dali.c1oappe.top/Article/details/gtimzmlgkh.html

[T41] Perl：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtgsgbqfkm.html

print "Hello\n";
来源：http://dali.meibo888.top/Article/details/gtqpvzlxob.html

[T42] Perl：变量类型
来源：http://dali.zhengqikj.top/Article/details/gtiabzwtpe.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.svipenyu.cn/Article/details/gtguzorimr.html

[T43] Perl：字符串插值
来源：http://dali.guannengcc.top/Article/details/gtsnjeejwu.html

"值: $a"
来源：http://dali.fzhhl.top/Article/details/gtcxsewjee.html

[T44] Perl：条件
来源：http://dali.yj20258.top/Article/details/gtbhmoprvi.html

if ($a > 0) { print "正"; }
来源：http://dali.316326.xyz/Article/details/gtzvcovzaz.html

[T45] Perl：数组遍历
来源：http://dali.xylfe.cn/Article/details/gtsldnqhmn.html

for my $x (@arr) { print $x; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtyelmdjxb.html

[T46] Perl：哈希操作
来源：http://dali.aibaodan.cn/Article/details/gtpozchgbe.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hammf.cn/Article/details/gtdftoywgt.html

[T47] Perl：正则捕获
来源：http://dali.ydzc1.top/Article/details/gtglnqmvoe.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.meibo888.top/Article/details/gtyhrlkmha.html

[T48] Perl：正则替换
来源：http://dali.jinqigfzy.top/Article/details/gtinamkzim.html

$s =~ s/old/new/g;
来源：http://dali.snrcjt.cn/Article/details/gtjuaxwybo.html

[T49] Perl：函数
来源：http://dali.guannengcc.top/Article/details/gtkkleqehc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.0kj1m.cn/Article/details/gtszwedcwt.html

[T50] Perl：逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gtsyuafzhn.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yuanzhike.top/Article/details/gtvffwniwe.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.shangyingyoupin.top/Article/details/gtpdhljjkj.html

[T51] Scala：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtvxgpcynu.html

println("Hello")
来源：http://dali.sufxvd.cn/Article/details/gtgsyxmceq.html

[T52] Scala：变量
来源：http://dali.redwolf501.top/Article/details/gtjfgrrrtv.html

val a = 1;  var b = 2
来源：http://dali.aibaodan.cn/Article/details/gtnmmnchgc.html

[T53] Scala：字符串插值
来源：http://dali.zhoulong.xyz/Article/details/gtrpixkmid.html

s"值: $b"
来源：http://dali.birdmap.top/Article/details/gtnvnrxnlq.html

[T54] Scala：集合映射
来源：http://dali.birdmap.top/Article/details/gtarttcojx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.nanxuanxn.top/Article/details/gtxvezpoqq.html

[T55] Scala：集合过滤
来源：http://dali.yangfankeji.com/Article/details/gtmhgwjtak.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.svipenyu.cn/Article/details/gtasgrlfdw.html

[T56] Scala：样例类
来源：http://dali.yj202588.top/Article/details/gtnylcmswo.html

case class User(name: String, age: Int)
来源：http://dali.gaohongyu789.top/Article/details/gtdorcirki.html

[T57] Scala：模式匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtzydtxjjy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.9152youxi.cn/Article/details/gtshkxkxni.html

[T58] Scala：函数定义
来源：http://dali.yueranfly.top/Article/details/gtkjlwisgz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.bjfxy.top/Article/details/gtmbbhvfap.html

[T59] Scala：循环
来源：http://dali.9152youxi.cn/Article/details/gtqtezpsbz.html

for (i <- 1 to 10) println(i)
来源：http://dali.xylfe.cn/Article/details/gtsksnbdti.html

[T60] Scala：折叠
来源：http://dali.gaohongyu789.top/Article/details/gtzdittgiq.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zdqjudy.top/Article/details/gtefnigsvb.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtsiwwixph.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinghuilouyu.cn/Article/details/gtmznfovce.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtifqqcdxp.html

[U01] Py：创建虚拟环境
来源：http://dali.0kj1m.cn/Article/details/gtxlmnpkdr.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.nanxuanxn.top/Article/details/gttbdkdcjv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.andypj.xyz/Article/details/gtdymzjbqb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.dashuyun.cn/Article/details/gtsxzmllac.html

[U03] Py：加载 .env 配置
来源：http://dali.shangyingyoupin.top/Article/details/gtkrhnbgkc.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yangfankeji.com/Article/details/gtvbawitjy.html

[U04] Py：变量调试打印
来源：http://dali.zhixingplan.top/Article/details/gtpyegvmml.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yonumen.top/Article/details/gtxepsavhl.html

[U05] Py：列表去重且保序
来源：http://dali.hammf.cn/Article/details/gtowlgcmiy.html

list(dict.fromkeys(arr))
来源：http://dali.gogol.net.cn/Article/details/gtyeulrpsb.html

[U06] Py：合并两个字典
来源：http://dali.meibo888.top/Article/details/gtphmdcswf.html

{**a, **b}
来源：http://dali.chenjidiqi.icu/Article/details/gtaydstvnj.html

[U07] Py：反转字典键值
来源：http://dali.jinqigufen.top/Article/details/gtfutdbnug.html

{v: k for k, v in d.items()}
来源：http://dali.hfpthk.cn/Article/details/gtnhtpkxxz.html

[U08] Py：展平二维列表
来源：http://dali.shanyushiyangtech.top/Article/details/gtjwjfitzt.html

[y for x in nested for y in x]
来源：http://dali.iojbl.cn/Article/details/gthcouqozo.html


<!-- 参考信息 -->