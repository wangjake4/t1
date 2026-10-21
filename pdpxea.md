代发 wailian999

openssl rand -hex 16
来源：http://dali.tian-w.cn/Article/details/gtibnrblie.html

[R68] 计算文件校验值
来源：http://dali.jiagoushi.top/Article/details/gtvdrcejvc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xuanzx.com/Article/details/gtlaujpjug.html

[R69] 生成随机密码
来源：http://dali.snrcjt.cn/Article/details/gtoxeillxo.html

head -c 16 /dev/urandom | base64
来源：http://dali.bjfxy.top/Article/details/gtcygonewb.html

[R70] 时间戳与互转
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbkqfwcln.html

date +%s;  date -d @1700000000
来源：http://dali.ppjwa.cn/Article/details/gtbfdscvhj.html

[R71] 日期格式化
来源：http://dali.tianlin.xyz/Article/details/gtyjqebglr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xziqi.cn/Article/details/gtoziwmrdl.html

[R72] 等待端口就绪
来源：http://dali.0kj1m.cn/Article/details/gtjqixhkzd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlpctqfbo.html

[R73] 分割大日志
来源：http://dali.pycfn.com/Article/details/gtrcggcgpw.html

split -l 1000 big.log part_
来源：http://dali.tian-w.cn/Article/details/gtmjcxlvnx.html

[R74] 批量重命名
来源：http://dali.hammf.cn/Article/details/gtowruullh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hnqzz.top/Article/details/gtqdqoiizs.html

[R75] 导出环境变量
来源：http://dali.gzhubu.top/Article/details/gtpafanslu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.svipenyu.cn/Article/details/gtlanrbddq.html

[R76] 使用临时文件
来源：http://dali.yj202588.top/Article/details/gthtrrqubr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shangyingyoupin.top/Article/details/gtmhqppvzs.html

[R77] 读取用户输入
来源：http://dali.zycfv.cn/Article/details/gtsjmwcemb.html

read -rp "请输入: " ans
来源：http://dali.0kj1m.cn/Article/details/gtcbrtargw.html

[R78] 交互式菜单
来源：http://dali.yj20258.top/Article/details/gtourroiws.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvciyncgn.html

[R79] 解析命令行选项
来源：http://dali.svipenyu.cn/Article/details/gtrydohtmo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.guowangkeji.top/Article/details/gtgavzpmbz.html

[R80] 查看脚本执行耗时
来源：http://dali.ivvv.top/Article/details/gtlxtzcdbx.html

time ./run.sh
来源：http://dali.hnxiangtu.top/Article/details/gtsipwrinm.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtgfizahhn.html

S. C / C++ 专题
来源：http://dali.shanyushiyangkeji.top/Article/details/gtemthxfci.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtabprrtiy.html

[S01] C：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtbgdlffzt.html

#include <stdio.h>
来源：http://dali.sufxvd.cn/Article/details/gtavifczef.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hywenlv.cn/Article/details/gtyuoqrvxo.html

[S02] C：变量与格式化输出
来源：http://dali.jqgfzy.top/Article/details/gtapxrreiq.html

int a = 10; printf("%d\n", a);
来源：http://dali.hongshengwenyu.top/Article/details/gtcnpjrelr.html

[S03] C：读入整数
来源：http://dali.hysaishi.cn/Article/details/gtmztcjbus.html

int x; scanf("%d", &x);
来源：http://dali.fzhhl.top/Article/details/gtldqaduhc.html

[S04] C：字符串复制
来源：http://dali.sxryk.cn/Article/details/gtxhdsictw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinqigfzy.top/Article/details/gtrldlkltw.html

[S05] C：字符串长度
来源：http://dali.0kj1m.cn/Article/details/gtwaohdaow.html

strlen(s)
来源：http://dali.shzxlz.cn/Article/details/gtvbwpgzrd.html

[S06] C：字符串比较
来源：http://dali.ivvv.top/Article/details/gtxiyydqok.html

strcmp(a, b) == 0
来源：http://dali.gzhubu.top/Article/details/gtkqeclcud.html

[S07] C：数组遍历求和
来源：http://dali.jinghuilouyu.cn/Article/details/gtcnctvrkr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yj20258888.top/Article/details/gtfazvmtiw.html

[S08] C：动态内存分配与释放
来源：http://dali.cdnleiting.top/Article/details/gtfvpxsegy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ybcxt.top/Article/details/gtmsvwltbo.html

[S09] C：结构体定义与初始化
来源：http://dali.hnqzz.top/Article/details/gtlsbmoiiz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jianghu66.top/Article/details/gtemiwnuyf.html

[S10] C：指针与解引用
来源：http://dali.xuanzx.com/Article/details/gtaexkxzyh.html

int *p = &a;  *p = 5;
来源：http://dali.yonumen.top/Article/details/gtvouagfai.html

[S11] C：逐行读文件
来源：http://dali.mhx1999.top/Article/details/gthdkgffyw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jqgfzy.top/Article/details/gtixzwgyqg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.andypj.xyz/Article/details/gtxykygmhd.html

fclose(f);
来源：http://dali.jyoumei.cn/Article/details/gtkglhhqzw.html

[S12] C：写文件
来源：http://dali.iojbl.cn/Article/details/gtgvjikjel.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.meibo888.top/Article/details/gtwknrzpph.html

[S13] C：宏定义
来源：http://dali.zhiwuduotai.top/Article/details/gtessbmdee.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.fengsongda.top/Article/details/gtqcrtlhzw.html

[S14] C：枚举
来源：http://dali.gzhubu.top/Article/details/gteryqumun.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xziqi.cn/Article/details/gtvxabrkhv.html

[S15] C：类型转换
来源：http://dali.aizwys.cn/Article/details/gtdfrnxlcx.html

(double) a / b
来源：http://dali.nwbrower.top/Article/details/gtopqywiko.html

[S16] C：位操作置位
来源：http://dali.0kj1m.cn/Article/details/gtbdvxygfg.html

x |= (1 << 3);
来源：http://dali.0kj1m.cn/Article/details/gtcysagjzs.html

[S17] C：安全拼接字符串
来源：http://dali.tianlin.xyz/Article/details/gtmhumbhby.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ehwqpu.com/Article/details/gtknxurflz.html

[S18] C：命令行参数
来源：http://dali.bjfxy.top/Article/details/gtcfoivyaj.html

int main(int argc, char **argv)
来源：http://dali.hammf.cn/Article/details/gtyvhzwaur.html

[S19] C：快速排序
来源：http://dali.wangdashe.top/Article/details/gtmfopvyrv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yueranfly.top/Article/details/gtoozzlgmu.html

[S20] C：二分查找
来源：http://dali.mhx1999.top/Article/details/gtplavypqw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sufxvd.cn/Article/details/gtgocgplcc.html

[S21] C：字符类别判断
来源：http://dali.zycfv.cn/Article/details/gtnbqhddgm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hywenlv.cn/Article/details/gtdskvhtrn.html

[S22] C：字符串转数字
来源：http://dali.shzxlz.cn/Article/details/gtewbqfqjr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.fzhhl.top/Article/details/gtpnmyhonh.html

[S23] C：随机数
来源：http://dali.tian-w.cn/Article/details/gtyxydzuqh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yonumen.top/Article/details/gtcksbbjfe.html

[S24] C：获取本地时间
来源：http://dali.zhongyouzk.top/Article/details/gtahuzonmq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sxryk.cn/Article/details/gtmnupabya.html

[S25] C：内存拷贝
来源：http://dali.nanxinkj.top/Article/details/gtopfraqsd.html

memcpy(dst, src, n);
来源：http://dali.haohaochexian.top/Article/details/gtnobvwsdk.html

[S26] C：内存清零
来源：http://dali.wangshuangyany.cn/Article/details/gtghwuleiy.html

memset(a, 0, sizeof a);
来源：http://dali.jqgufenzy.top/Article/details/gtbordkzws.html

[S27] C：定义常量
来源：http://dali.ppjwa.cn/Article/details/gtsynsiboa.html

const double PI = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gtwxbeuptb.html

[S28] C：静态变量
来源：http://dali.zhixingplan.top/Article/details/gtodupylfk.html

static int counter = 0;
来源：http://dali.jinghuilouyu.cn/Article/details/gtckoagsqt.html

[S29] C：变参函数
来源：http://dali.yonumen.top/Article/details/gtpsgkqlcx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.haohaochexian.top/Article/details/gtwbsrmeuj.html

[S30] C：头文件保护
来源：http://dali.gaohongyu789.top/Article/details/gtxeuoolat.html

#ifndef X_H
来源：http://dali.zhixingplan.top/Article/details/gtiwjfgvqd.html

#define X_H
来源：http://dali.fengsongda.top/Article/details/gtohunslga.html

#endif
来源：http://dali.aizwys.cn/Article/details/gtfgbnpwfl.html

[S31] C++：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtouoxlmel.html

#include <iostream>
来源：http://dali.sxryk.cn/Article/details/gtsdinmtrh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtodhyswwc.html

[S32] C++：字符串
来源：http://dali.birdmap.top/Article/details/gtdrjmqnrb.html

std::string s = "hi";  s += "!";
来源：http://dali.guowangkeji.top/Article/details/gtroajmlxo.html

[S33] C++：vector 增删
来源：http://dali.mhx1999.top/Article/details/gtymaioqev.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yueranfly.top/Article/details/gtwxzoyqcb.html

[S34] C++：遍历 vector
来源：http://dali.cashguo.top/Article/details/gtacihbrsm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.haohaochexian.top/Article/details/gtweenievh.html

[S35] C++：map
来源：http://dali.guannengcc.top/Article/details/gtydvuqvev.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtexavgqqz.html

[S36] C++：unordered_map
来源：http://dali.sxryk.cn/Article/details/gtpsdhwjno.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cdnleiting.top/Article/details/gtlnmsmaek.html

[S37] C++：set
来源：http://dali.aibaodan.cn/Article/details/gtzwprnjro.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shangyingyoupin.top/Article/details/gtgthgodnj.html

[S38] C++：排序
来源：http://dali.shuidangran.top/Article/details/gtabjnnsny.html

std::sort(v.begin(), v.end());
来源：http://dali.jlsjyb.cn/Article/details/gtawdfwdqh.html

[S39] C++：自定义比较器排序
来源：http://dali.yj20258.top/Article/details/gtsroqbqgx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenzaomai.com/Article/details/gtablkmpww.html

[S40] C++：查找元素
来源：http://dali.birdmap.top/Article/details/gtmfhrqbfg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.andypj.xyz/Article/details/gtrsfqiryj.html

[S41] C++：类与构造函数
来源：http://dali.xziqi.cn/Article/details/gtmzclodea.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sxryk.cn/Article/details/gtiwrwwyxy.html

[S42] C++：继承与虚函数
来源：http://dali.cdnleiting.top/Article/details/gtkroymrth.html

class B : public Base { public: void f() override {} };
来源：http://dali.wangshuangyany.cn/Article/details/gtufhszsvc.html

[S43] C++：智能指针
来源：http://dali.fengsongda.top/Article/details/gtujinamgg.html

auto p = std::make_unique<int>(5);
来源：http://dali.yvedp.cn/Article/details/gtosdmlwzm.html

[S44] C++：引用传参
来源：http://dali.yj202588.top/Article/details/gtqnckygwg.html

void inc(int &x) { ++x; }
来源：http://dali.jqgufenzy.top/Article/details/gtahiopzio.html

[S45] C++：lambda
来源：http://dali.andypj.xyz/Article/details/gtgynlxejw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yvedp.cn/Article/details/gtherxkyzy.html

[S46] C++：函数模板
来源：http://dali.shzxlz.cn/Article/details/gtssaentls.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.guannengcc.top/Article/details/gtefeccddo.html

[S47] C++：结构化绑定遍历
来源：http://dali.iojbl.cn/Article/details/gtjfkufejv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yonumen.top/Article/details/gtgzdxjubx.html

[S48] C++：逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gthehulogs.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.9152youxi.cn/Article/details/gtdklhstow.html

while (std::getline(in, line)) { }
来源：http://dali.haohaochexian.top/Article/details/gtwomyarck.html

[S49] C++：写文件
来源：http://dali.zhijiandao.cn/Article/details/gthguwostb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yanxiufei.cn/Article/details/gtlgkrtwop.html

[S50] C++：格式化数字
来源：http://dali.yangfankeji.com/Article/details/gtyiiokdqk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ivvv.top/Article/details/gtjkjjcmmu.html

[S51] C++：显式类型转换
来源：http://dali.havefunace.top/Article/details/gtolmphpei.html

static_cast<double>(a) / b
来源：http://dali.jqgufenzy.top/Article/details/gtujqrdfmw.html

[S52] C++：const 与 noexcept
来源：http://dali.xylfe.cn/Article/details/gtreevouuk.html

int size() const noexcept { return n_; }
来源：http://dali.mhx1999.top/Article/details/gtkpkqfnxl.html

[S53] C++：移动语义
来源：http://dali.xuetiantiany.cn/Article/details/gtwxpkdqup.html

std::vector<int> w = std::move(v);
来源：http://dali.quarkkingdee.top/Article/details/gtwcikfunj.html

[S54] C++：异常处理
来源：http://dali.shangyingyoupin.top/Article/details/gtanhqtsie.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.feifeiyinyue.top/Article/details/gtknitnbgo.html

[S55] C++：结构化绑定
来源：http://dali.jianghu66.top/Article/details/gtqoiqsueq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.quarkkingdee.top/Article/details/gtdrlyfhrp.html

[S56] C++：optional
来源：http://dali.dianchejie.cn/Article/details/gtatlvzdvm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hysaishi.cn/Article/details/gtdxwksior.html

[S57] C++：编译期常量
来源：http://dali.xylfe.cn/Article/details/gtmfdwcetl.html

constexpr int N = 10;
来源：http://dali.fengsongda.top/Article/details/gtjecjpfvk.html

[S58] C++：命名空间
来源：http://dali.zhixingplan.top/Article/details/gtybdsopks.html

namespace ns { int f() { return 1; } }
来源：http://dali.pengpengdd.cyou/Article/details/gtpeuhdoqx.html

[S59] C++：静态断言
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtftezlxhb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.nanxuanxn.top/Article/details/gtekvvgaao.html

[S60] C++：遍历并删除元素
来源：http://dali.hfpthk.cn/Article/details/gtbgoegrxz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hammf.cn/Article/details/gtsgofqibg.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtgjockykl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cdnleiting.top/Article/details/gtqlqxeond.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtelahytza.html

[T01] Kotlin：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtbtoccmgb.html

println("Hello")
来源：http://dali.aizwys.cn/Article/details/gtjnuqpcyr.html

[T02] Kotlin：变量
来源：http://dali.zhixingplan.top/Article/details/gtpybruwfr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.wangdashe.top/Article/details/gtktbqrmme.html

[T03] Kotlin：字符串模板
来源：http://dali.nwbrower.top/Article/details/gtmodiqxpd.html

"值: $b"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwzzdblgm.html

[T04] Kotlin：空安全
来源：http://dali.ydzc1.top/Article/details/gtlfninvcl.html

val n: String? = null;  n?.length
来源：http://dali.zhengqikj.top/Article/details/gthynjhime.html

[T05] Kotlin：when 表达式
来源：http://dali.tianlin.xyz/Article/details/gtsxoglstu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yj20258888.top/Article/details/gtqlqpsgme.html

[T06] Kotlin：集合映射
来源：http://dali.smart0.xyz/Article/details/gttfrkbhsp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hnqzz.top/Article/details/gtgszylqnl.html

[T07] Kotlin：集合过滤
来源：http://dali.cheryme.top/Article/details/gtppkhmcdc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jlsjyb.cn/Article/details/gttneaqckd.html

[T08] Kotlin：数据类
来源：http://dali.cucudq.cn/Article/details/gtctgfkdat.html

data class User(val name: String, val age: Int)
来源：http://dali.jyoumei.cn/Article/details/gtldutxtye.html

[T09] Kotlin：扩展函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcqttnykz.html

fun String.exclaim() = this + "!"
来源：http://dali.snrcjt.cn/Article/details/gtsfisjyrv.html

[T10] Kotlin：默认参数
来源：http://dali.svipenyu.cn/Article/details/gtyocwhreo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.birdmap.top/Article/details/gtrbgmbiya.html

[T11] Kotlin：协程
来源：http://dali.shzxlz.cn/Article/details/gtlkvozypn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthiellzea.html

[T12] Kotlin：解构声明
来源：http://dali.zycfv.cn/Article/details/gtoaqbjwgq.html

val (a, b) = Pair(1, 2)
来源：http://dali.hammf.cn/Article/details/gtqbxunsog.html

[T13] Kotlin：只读 Map
来源：http://dali.ybcxt.top/Article/details/gtunsdmkje.html

val m = mapOf("a" to 1)
来源：http://dali.jianghu66.top/Article/details/gtfdlyuoql.html

[T14] Kotlin：循环
来源：http://dali.pycfn.com/Article/details/gtnasmxfla.html

for (i in 1..10) println(i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthnuyypyg.html

[T15] Kotlin：接口
来源：http://dali.iojbl.cn/Article/details/gtmbrfqssp.html

interface Shape { fun area(): Double }
来源：http://dali.yongpay.top/Article/details/gtzyzpyayh.html

[T16] Swift：Hello World
来源：http://dali.smart0.xyz/Article/details/gtvmrnwwps.html

print("Hello")
来源：http://dali.yonumen.top/Article/details/gtqmdmknxj.html

[T17] Swift：变量与常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuteewgga.html

var a = 1;  let b = 2
来源：http://dali.smart0.xyz/Article/details/gtjpzjjkwq.html

[T18] Swift：字符串插值
来源：http://dali.hongshengwenyu.top/Article/details/gtjkkitmzv.html

"值: \(b)"
来源：http://dali.ppjwa.cn/Article/details/gtcewqewep.html

[T19] Swift：可选绑定
来源：http://dali.ybcxt.top/Article/details/gtitvpaggs.html

if let n = opt { print(n) }
来源：http://dali.tianlin.xyz/Article/details/gtvotniseb.html

[T20] Swift：数组操作
来源：http://dali.hysaishi.cn/Article/details/gtnlvzxpul.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ehwqpu.com/Article/details/gtovtcmuea.html

[T21] Swift：遍历
来源：http://dali.gogol.net.cn/Article/details/gtifywwfpf.html

for x in a { print(x) }
来源：http://dali.sweek.top/Article/details/gtlqdklpge.html

[T22] Swift：字典
来源：http://dali.jinghuilouyu.cn/Article/details/gtmecerqpq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cqqwz.cn/Article/details/gtmmsxirfm.html

[T23] Swift：函数
来源：http://dali.chenjidiqi.icu/Article/details/gtwiuaivly.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jqgfzy.top/Article/details/gtxqnbavzo.html

[T24] Swift：闭包
来源：http://dali.aibaodan.cn/Article/details/gtowgxfppa.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.nanxinkj.top/Article/details/gtawkpfegc.html

[T25] Swift：结构体
来源：http://dali.sufxvd.cn/Article/details/gtxhacqzhj.html

struct P { var x: Int }
来源：http://dali.chenlongwang.top/Article/details/gtiveuryvs.html

[T26] Swift：类与重写
来源：http://dali.iojbl.cn/Article/details/gtgkevwzoz.html

class A: Base { override func f() {} }
来源：http://dali.ybcxt.top/Article/details/gtjweernzr.html

[T27] Swift：错误处理
来源：http://dali.daria6918.cn/Article/details/gtrsuitmsf.html

do { try f() } catch { print(error) }
来源：http://dali.jinqigufen.top/Article/details/gtxidfhqwp.html

[T28] Swift：枚举
来源：http://dali.andypj.xyz/Article/details/gtajlcceiv.html

enum Color { case red, green }
来源：http://dali.hysaishi.cn/Article/details/gtfiryrlnf.html

[T29] Swift：guard 提前返回
来源：http://dali.aibaodan.cn/Article/details/gtkmcndkic.html

guard let x = opt else { return }
来源：http://dali.gotoacloud.top/Article/details/gtxoevkvxw.html

[T30] Swift：协议
来源：http://dali.xuetiantiany.cn/Article/details/gtyhcbqrxf.html

protocol Shape { func area() -> Double }
来源：http://dali.gaohongyu789.top/Article/details/gtgyvwaald.html

[T31] Lua：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtrsbrxphw.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gtgcdtxrsj.html

[T32] Lua：局部变量
来源：http://dali.xylfe.cn/Article/details/gtgixwnxpu.html

local a = 1
来源：http://dali.jyoumei.cn/Article/details/gtxkcbnixq.html

[T33] Lua：表（数组）
来源：http://dali.sufxvd.cn/Article/details/gtanpjnkev.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.haohaochexian.top/Article/details/gtodndhycw.html

[T34] Lua：遍历表
来源：http://dali.shanyushiyangtech.top/Article/details/gtnwnbrznm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yangfankeji.com/Article/details/gtdzynybrh.html

[T35] Lua：字典表
来源：http://dali.gogol.net.cn/Article/details/gtafxwmcmq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hnqzz.top/Article/details/gtrjaqgdqd.html

[T36] Lua：函数
来源：http://dali.gaohongyu789.top/Article/details/gtrqnihqww.html

function add(a, b) return a + b end
来源：http://dali.shzxlz.cn/Article/details/gtcbevoxlz.html

[T37] Lua：字符串拼接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxiexihyr.html

"a" .. "b"
来源：http://dali.shanyushiyangtech.top/Article/details/gtlufkqksz.html

[T38] Lua：条件
来源：http://dali.meibo888.top/Article/details/gtackifyfw.html

if x > 0 then print("正") end
来源：http://dali.dashuyun.cn/Article/details/gtwxswaont.html

[T39] Lua：模式匹配
来源：http://dali.gogol.net.cn/Article/details/gtaxnrfdlb.html

string.find(s, "%d+")
来源：http://dali.cheryme.top/Article/details/gtgsccdrab.html

[T40] Lua：元表
来源：http://dali.shzxlz.cn/Article/details/gtoannhzjm.html

setmetatable({}, { __index = base })
来源：http://dali.zdqjudy.top/Article/details/gtncwtniyc.html

[T41] Perl：Hello World
来源：http://dali.sweek.top/Article/details/gtsuuquhgq.html

print "Hello\n";
来源：http://dali.yj20258.top/Article/details/gtifbgpoic.html

[T42] Perl：变量类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsprhxtql.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jlsjyb.cn/Article/details/gtocrnqmya.html

[T43] Perl：字符串插值
来源：http://dali.mhx1999.top/Article/details/gtmpbfuakf.html

"值: $a"
来源：http://dali.hfpthk.cn/Article/details/gtjyknqvla.html

[T44] Perl：条件
来源：http://dali.xziqi.cn/Article/details/gtjwmxzclp.html

if ($a > 0) { print "正"; }
来源：http://dali.birdmap.top/Article/details/gtgplvxuvx.html

[T45] Perl：数组遍历
来源：http://dali.tanke756.top/Article/details/gtpveihtbw.html

for my $x (@arr) { print $x; }
来源：http://dali.chenlongwang.top/Article/details/gtirxierok.html

[T46] Perl：哈希操作
来源：http://dali.ppjwa.cn/Article/details/gtuxtqzdjw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtcqbhztxj.html

[T47] Perl：正则捕获
来源：http://dali.cashguo.top/Article/details/gtjldfowmq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.cucudq.cn/Article/details/gtulmmnagl.html

[T48] Perl：正则替换
来源：http://dali.tian-w.cn/Article/details/gtgnpxcuku.html

$s =~ s/old/new/g;
来源：http://dali.ppjwa.cn/Article/details/gtxwjfanhy.html

[T49] Perl：函数
来源：http://dali.fengsongda.top/Article/details/gtzuuqsoto.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.pycfn.com/Article/details/gttzzfeznc.html

[T50] Perl：逐行读文件
来源：http://dali.cheryme.top/Article/details/gtxkxmbmfj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ppjwa.cn/Article/details/gtcbyefloo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.havefunace.top/Article/details/gtwavxagub.html

[T51] Scala：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtsubunezs.html

println("Hello")
来源：http://dali.svipenyu.cn/Article/details/gtvhpugeao.html

[T52] Scala：变量
来源：http://dali.yongpay.top/Article/details/gttkowxpiu.html

val a = 1;  var b = 2
来源：http://dali.shangyingyoupin.top/Article/details/gtdadtkqhs.html

[T53] Scala：字符串插值
来源：http://dali.shzxlz.cn/Article/details/gtrooadnhl.html

s"值: $b"
来源：http://dali.jiagoushi.top/Article/details/gtziybarrq.html

[T54] Scala：集合映射
来源：http://dali.jianghu66.top/Article/details/gtfugjtzby.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.tianlin.xyz/Article/details/gtgqfchjnq.html

[T55] Scala：集合过滤
来源：http://dali.9152youxi.cn/Article/details/gtrfsahjsb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.iojbl.cn/Article/details/gtofbfcboh.html

[T56] Scala：样例类
来源：http://dali.yueranfly.top/Article/details/gtgyfvfzdg.html

case class User(name: String, age: Int)
来源：http://dali.daxiang520.top/Article/details/gthvojlcoi.html

[T57] Scala：模式匹配
来源：http://dali.daxiang520.top/Article/details/gtrwjchcql.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.9152youxi.cn/Article/details/gtifiemzww.html

[T58] Scala：函数定义
来源：http://dali.yuanzhike.top/Article/details/gtdlltxsfw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.pengpengdd.cyou/Article/details/gtohtryiiw.html

[T59] Scala：循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdypxmyxz.html

for (i <- 1 to 10) println(i)
来源：http://dali.jianghu66.top/Article/details/gtbyihwlry.html

[T60] Scala：折叠
来源：http://dali.yuxming.cn/Article/details/gtrqqvzitd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.tian-w.cn/Article/details/gtrcyoejlv.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtvmuzujgv.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.wangdashe.top/Article/details/gtxiinufvp.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtopohyqwa.html

[U01] Py：创建虚拟环境
来源：http://dali.chenzaomai.com/Article/details/gtihxsxkie.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.gogol.net.cn/Article/details/gtocvctpgv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.0kj1m.cn/Article/details/gtycvieeme.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ydzc1.top/Article/details/gtupavzqef.html

[U03] Py：加载 .env 配置
来源：http://dali.birdmap.top/Article/details/gtioaeuxxt.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ybcxt.top/Article/details/gtmzgkjivh.html

[U04] Py：变量调试打印
来源：http://dali.xinyue.icu/Article/details/gtqgqetgmp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.feifeiyinyue.top/Article/details/gtybzgynwr.html

[U05] Py：列表去重且保序
来源：http://dali.chenzaomai.com/Article/details/gttlfiahpd.html

list(dict.fromkeys(arr))
来源：http://dali.hnqzz.top/Article/details/gtjcytnwhl.html

[U06] Py：合并两个字典
来源：http://dali.chenjidiqi.icu/Article/details/gtavnfhutn.html

{**a, **b}
来源：http://dali.yj202588.top/Article/details/gtjmckyyih.html

[U07] Py：反转字典键值
来源：http://dali.jyoumei.cn/Article/details/gtcihonbuo.html

{v: k for k, v in d.items()}
来源：http://dali.cashguo.top/Article/details/gtrkanprpe.html

[U08] Py：展平二维列表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfekxewbw.html

[y for x in nested for y in x]
来源：http://dali.zhengqikj.top/Article/details/gtvdeawbyy.html


<!-- 参考信息 -->