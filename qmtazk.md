代发 wailian999

openssl rand -hex 16
来源：http://dali.dashuyun.cn/Article/details/gtszrquxli.html

[R68] 计算文件校验值
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdjmzaenb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sufxvd.cn/Article/details/gtaakyztgk.html

[R69] 生成随机密码
来源：http://dali.jianghu66.top/Article/details/gteghxiepg.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinghuilouyu.cn/Article/details/gtpqejhkef.html

[R70] 时间戳与互转
来源：http://dali.zhixingplan.top/Article/details/gtzlhjujga.html

date +%s;  date -d @1700000000
来源：http://dali.nanxinkj.top/Article/details/gtdqebxzcw.html

[R71] 日期格式化
来源：http://dali.aibaodan.cn/Article/details/gtpetkorsk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.redwolf501.top/Article/details/gtnzlfcqwo.html

[R72] 等待端口就绪
来源：http://dali.meibo888.top/Article/details/gtjodinjiu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtrencytpn.html

[R73] 分割大日志
来源：http://dali.feifeiyinyue.top/Article/details/gtmfskziez.html

split -l 1000 big.log part_
来源：http://dali.gzhubu.top/Article/details/gtpbdyjtmy.html

[R74] 批量重命名
来源：http://dali.yanxiufei.cn/Article/details/gtyndihslp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.aibaodan.cn/Article/details/gtaojtvhev.html

[R75] 导出环境变量
来源：http://dali.jinqigufen.top/Article/details/gtxnvdkfpp.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.316326.xyz/Article/details/gtzzswyeud.html

[R76] 使用临时文件
来源：http://dali.jqgfzy.top/Article/details/gtxglumwxd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.aibaodan.cn/Article/details/gtuiumovkd.html

[R77] 读取用户输入
来源：http://dali.svipenyu.cn/Article/details/gtuaxwyyqb.html

read -rp "请输入: " ans
来源：http://dali.gotoacloud.top/Article/details/gttqgmqppg.html

[R78] 交互式菜单
来源：http://dali.hywenlv.cn/Article/details/gtishxcaer.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.wangdashe.top/Article/details/gtmswhfvlk.html

[R79] 解析命令行选项
来源：http://dali.daxiang520.top/Article/details/gtmxawsiix.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.dashuyun.cn/Article/details/gtltpdyysh.html

[R80] 查看脚本执行耗时
来源：http://dali.gaohongyu789.top/Article/details/gtyxziulhd.html

time ./run.sh
来源：http://dali.shanyushiyangkeji.top/Article/details/gtezibkneh.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtgpomtkqe.html

S. C / C++ 专题
来源：http://dali.gzhubu.top/Article/details/gtzmagxdpl.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gthqrpwmjl.html

[S01] C：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtrwfasijx.html

#include <stdio.h>
来源：http://dali.xylfe.cn/Article/details/gtzxtzaarj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yonumen.top/Article/details/gtdvgsnaym.html

[S02] C：变量与格式化输出
来源：http://dali.0kj1m.cn/Article/details/gtavdowjvb.html

int a = 10; printf("%d\n", a);
来源：http://dali.daxiang520.top/Article/details/gtiwpqevkr.html

[S03] C：读入整数
来源：http://dali.9152youxi.cn/Article/details/gtyknomqld.html

int x; scanf("%d", &x);
来源：http://dali.nwbrower.top/Article/details/gtzutqtxgk.html

[S04] C：字符串复制
来源：http://dali.aibaodan.cn/Article/details/gtmhvcsrkm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cucudq.cn/Article/details/gtwantixny.html

[S05] C：字符串长度
来源：http://dali.xinyue.icu/Article/details/gtyrgtahhv.html

strlen(s)
来源：http://dali.gotoacloud.top/Article/details/gtiqlfcmyf.html

[S06] C：字符串比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gtykvpyzzg.html

strcmp(a, b) == 0
来源：http://dali.hammf.cn/Article/details/gtzxrseyna.html

[S07] C：数组遍历求和
来源：http://dali.hongshengwenyu.top/Article/details/gtxitdugxv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shuidangran.top/Article/details/gtvicukfuc.html

[S08] C：动态内存分配与释放
来源：http://dali.meibo888.top/Article/details/gtaskugsuc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hfpthk.cn/Article/details/gtomtbhvzs.html

[S09] C：结构体定义与初始化
来源：http://dali.cheryme.top/Article/details/gtskwwqqpx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xuanzx.com/Article/details/gtqojyxzsq.html

[S10] C：指针与解引用
来源：http://dali.jinghuilouyu.cn/Article/details/gtfnpqwzjt.html

int *p = &a;  *p = 5;
来源：http://dali.nwbrower.top/Article/details/gtrfaqdlnp.html

[S11] C：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gtzawlxqlg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cashguo.top/Article/details/gtiwjqohqo.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.daxiang520.top/Article/details/gtvkchtebr.html

fclose(f);
来源：http://dali.xuanzx.com/Article/details/gtfbsdynhj.html

[S12] C：写文件
来源：http://dali.sysykeji.top/Article/details/gtvkrgpdal.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hongshengwenyu.top/Article/details/gthzzpbbax.html

[S13] C：宏定义
来源：http://dali.zhiwuduotai.top/Article/details/gtzfkqkjez.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zdqjudy.top/Article/details/gttvlewvkg.html

[S14] C：枚举
来源：http://dali.yongpay.top/Article/details/gtkkdjzkje.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xinyue.icu/Article/details/gtwfdkrsay.html

[S15] C：类型转换
来源：http://dali.snrcjt.cn/Article/details/gtabmkvdjf.html

(double) a / b
来源：http://dali.jinqigfzy.top/Article/details/gtmlnbltxz.html

[S16] C：位操作置位
来源：http://dali.hfpthk.cn/Article/details/gtuipmlxgr.html

x |= (1 << 3);
来源：http://dali.redwolf501.top/Article/details/gtacbosexj.html

[S17] C：安全拼接字符串
来源：http://dali.dianchejie.cn/Article/details/gtdosndpir.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.meibo888.top/Article/details/gtuelojvxd.html

[S18] C：命令行参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjkeindfc.html

int main(int argc, char **argv)
来源：http://dali.sysykeji.top/Article/details/gtsedjhcyz.html

[S19] C：快速排序
来源：http://dali.iojbl.cn/Article/details/gtumbubunt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gtkebuhako.html

[S20] C：二分查找
来源：http://dali.xuetiantiany.cn/Article/details/gttlnfiypo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.9152youxi.cn/Article/details/gtcgrwfudt.html

[S21] C：字符类别判断
来源：http://dali.nwbrower.top/Article/details/gtigafjuvn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.9152youxi.cn/Article/details/gttjjslavg.html

[S22] C：字符串转数字
来源：http://dali.yj202588.top/Article/details/gtxygseyyx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.andypj.xyz/Article/details/gtlizybcgj.html

[S23] C：随机数
来源：http://dali.hfpthk.cn/Article/details/gtujcvqiyb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yueranfly.top/Article/details/gtpxmxiuon.html

[S24] C：获取本地时间
来源：http://dali.yanxiufei.cn/Article/details/gtsxhrflxq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jlsjyb.cn/Article/details/gtqbdfhldi.html

[S25] C：内存拷贝
来源：http://dali.yueranfly.top/Article/details/gtzqhvuxiq.html

memcpy(dst, src, n);
来源：http://dali.yj20258888.top/Article/details/gtrqaigfmb.html

[S26] C：内存清零
来源：http://dali.vqdsnc.cn/Article/details/gttfabrwuw.html

memset(a, 0, sizeof a);
来源：http://dali.redwolf501.top/Article/details/gtrgvjsqsn.html

[S27] C：定义常量
来源：http://dali.shanyushiyangtech.top/Article/details/gteluhellb.html

const double PI = 3.14159;
来源：http://dali.nwbrower.top/Article/details/gtwflxkmzk.html

[S28] C：静态变量
来源：http://dali.yvedp.cn/Article/details/gtgjneearp.html

static int counter = 0;
来源：http://dali.ydzc1.top/Article/details/gtquxfsnfk.html

[S29] C：变参函数
来源：http://dali.yuanzhike.top/Article/details/gtzvwkqzkg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hnxiangtu.top/Article/details/gtkqgrgyhp.html

[S30] C：头文件保护
来源：http://dali.pengpengdd.cyou/Article/details/gtnwcgrwfo.html

#ifndef X_H
来源：http://dali.guowangkeji.top/Article/details/gtofelpmxe.html

#define X_H
来源：http://dali.jiagoushi.top/Article/details/gteicaikav.html

#endif
来源：http://dali.cqqwz.cn/Article/details/gtqgasgojy.html

[S31] C++：Hello World
来源：http://dali.guannengcc.top/Article/details/gtmmdnghcw.html

#include <iostream>
来源：http://dali.gaohongyu789.top/Article/details/gtynwtitmm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.svipenyu.cn/Article/details/gtzsstvfsf.html

[S32] C++：字符串
来源：http://dali.kuanghao11.cn/Article/details/gtgnpfqkkq.html

std::string s = "hi";  s += "!";
来源：http://dali.gotoacloud.top/Article/details/gtvedodtmv.html

[S33] C++：vector 增删
来源：http://dali.guannengcc.top/Article/details/gtlfuvfngc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cucudq.cn/Article/details/gtsxzsrikv.html

[S34] C++：遍历 vector
来源：http://dali.ppjwa.cn/Article/details/gtvuewunvd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtqxeofmlp.html

[S35] C++：map
来源：http://dali.hysaishi.cn/Article/details/gtgfvliehi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtlboyqjfd.html

[S36] C++：unordered_map
来源：http://dali.cashguo.top/Article/details/gtjybelziv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fzhhl.top/Article/details/gtljdgyiqt.html

[S37] C++：set
来源：http://dali.ivvv.top/Article/details/gtktdyomre.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zdqjudy.top/Article/details/gtgfitghoz.html

[S38] C++：排序
来源：http://dali.sysykeji.top/Article/details/gtwearhbhs.html

std::sort(v.begin(), v.end());
来源：http://dali.nanxinkj.top/Article/details/gtfyhrmssv.html

[S39] C++：自定义比较器排序
来源：http://dali.hysaishi.cn/Article/details/gtqtiqvfcl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.fzhhl.top/Article/details/gtswqincsp.html

[S40] C++：查找元素
来源：http://dali.daxiang520.top/Article/details/gtvtpgoezx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.vqdsnc.cn/Article/details/gtwfuwagdh.html

[S41] C++：类与构造函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyxrtmkte.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ppjwa.cn/Article/details/gtdxyccjpp.html

[S42] C++：继承与虚函数
来源：http://dali.svipenyu.cn/Article/details/gtyejydpwc.html

class B : public Base { public: void f() override {} };
来源：http://dali.daxiang520.top/Article/details/gtwklkrtae.html

[S43] C++：智能指针
来源：http://dali.sufxvd.cn/Article/details/gtehznlwyf.html

auto p = std::make_unique<int>(5);
来源：http://dali.daria6918.cn/Article/details/gtnzssckns.html

[S44] C++：引用传参
来源：http://dali.yuanzhike.top/Article/details/gtchghcuxn.html

void inc(int &x) { ++x; }
来源：http://dali.gaohongyu789.top/Article/details/gtqbwyavmf.html

[S45] C++：lambda
来源：http://dali.hfpthk.cn/Article/details/gtyujauhcr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.meibo888.top/Article/details/gtwtnydgxf.html

[S46] C++：函数模板
来源：http://dali.nanxinkj.top/Article/details/gtozafhuwu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yvedp.cn/Article/details/gtjycqrjui.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinqigufen.top/Article/details/gtkeetazxm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinqigfzy.top/Article/details/gtelbsiykg.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gtnwyfzcpo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gotoacloud.top/Article/details/gtmzwwmbrr.html

while (std::getline(in, line)) { }
来源：http://dali.zhongyouzk.top/Article/details/gtdmunydpo.html

[S49] C++：写文件
来源：http://dali.0kj1m.cn/Article/details/gtakwdzsmm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.meibo888.top/Article/details/gtclqrxgaf.html

[S50] C++：格式化数字
来源：http://dali.havefunace.top/Article/details/gtjdsqekpf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gtkbxsxyfg.html

[S51] C++：显式类型转换
来源：http://dali.haohaochexian.top/Article/details/gtvsebcfrg.html

static_cast<double>(a) / b
来源：http://dali.kuanghao11.cn/Article/details/gtzsfohddl.html

[S52] C++：const 与 noexcept
来源：http://dali.cucudq.cn/Article/details/gthtxpogyr.html

int size() const noexcept { return n_; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtwggpmarj.html

[S53] C++：移动语义
来源：http://dali.nanxuanxn.top/Article/details/gtigictghp.html

std::vector<int> w = std::move(v);
来源：http://dali.hywenlv.cn/Article/details/gtqolfigsh.html

[S54] C++：异常处理
来源：http://dali.9152youxi.cn/Article/details/gtwrlybtba.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.fengsongda.top/Article/details/gtsygyphaq.html

[S55] C++：结构化绑定
来源：http://dali.hammf.cn/Article/details/gtqodjduuj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cucudq.cn/Article/details/gtjyalclig.html

[S56] C++：optional
来源：http://dali.jyoumei.cn/Article/details/gtgtdxtjvn.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.quarkkingdee.top/Article/details/gtpnrcsjpx.html

[S57] C++：编译期常量
来源：http://dali.yangfankeji.com/Article/details/gtlvjrodnh.html

constexpr int N = 10;
来源：http://dali.bjfxy.top/Article/details/gtqbwtzjhw.html

[S58] C++：命名空间
来源：http://dali.sxryk.cn/Article/details/gtgzajfmhr.html

namespace ns { int f() { return 1; } }
来源：http://dali.shzxlz.cn/Article/details/gtzrfrnqeq.html

[S59] C++：静态断言
来源：http://dali.xziqi.cn/Article/details/gtxkcwzlea.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinqigfzy.top/Article/details/gtktyhcwxa.html

[S60] C++：遍历并删除元素
来源：http://dali.jinghuilouyu.cn/Article/details/gthfdhkolr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hnqzz.top/Article/details/gtjjngqxfy.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtduphgcjf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.andypj.xyz/Article/details/gtckvjidvb.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtjslyfjty.html

[T01] Kotlin：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtwhjerzup.html

println("Hello")
来源：http://dali.jlsjyb.cn/Article/details/gthqvvwpgm.html

[T02] Kotlin：变量
来源：http://dali.xziqi.cn/Article/details/gtmajftlnr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hywenlv.cn/Article/details/gtmacdofsu.html

[T03] Kotlin：字符串模板
来源：http://dali.gaohongyu789.top/Article/details/gttvcetcjy.html

"值: $b"
来源：http://dali.zycfv.cn/Article/details/gtrgytikkv.html

[T04] Kotlin：空安全
来源：http://dali.zhixingplan.top/Article/details/gtjtyimpjj.html

val n: String? = null;  n?.length
来源：http://dali.cucudq.cn/Article/details/gtjuwrhgab.html

[T05] Kotlin：when 表达式
来源：http://dali.mhx1999.top/Article/details/gtatrucjda.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhongyouzk.top/Article/details/gtwvxacedg.html

[T06] Kotlin：集合映射
来源：http://dali.feifeiyinyue.top/Article/details/gtpadczsjl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xinyue.icu/Article/details/gtfbiknvnm.html

[T07] Kotlin：集合过滤
来源：http://dali.zhongyouzk.top/Article/details/gttlkqsbml.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhiwuduotai.top/Article/details/gtlzyqdofl.html

[T08] Kotlin：数据类
来源：http://dali.jlsjyb.cn/Article/details/gtidsqyien.html

data class User(val name: String, val age: Int)
来源：http://dali.dashuyun.cn/Article/details/gtspzoncli.html

[T09] Kotlin：扩展函数
来源：http://dali.gogol.net.cn/Article/details/gtqhozimkm.html

fun String.exclaim() = this + "!"
来源：http://dali.mhx1999.top/Article/details/gtyalqhgfi.html

[T10] Kotlin：默认参数
来源：http://dali.c1oappe.top/Article/details/gtnorvgjpt.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cdnleiting.top/Article/details/gtvjpfygtc.html

[T11] Kotlin：协程
来源：http://dali.guowangkeji.top/Article/details/gttekcntyn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jqgfzy.top/Article/details/gtmtxowesy.html

[T12] Kotlin：解构声明
来源：http://dali.cucudq.cn/Article/details/gtxizqarin.html

val (a, b) = Pair(1, 2)
来源：http://dali.wangshuangyany.cn/Article/details/gtlwbwjgxv.html

[T13] Kotlin：只读 Map
来源：http://dali.chenzaomai.com/Article/details/gtdgpuurzk.html

val m = mapOf("a" to 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsnkvdhtt.html

[T14] Kotlin：循环
来源：http://dali.jinqigfzy.top/Article/details/gttbjtshbj.html

for (i in 1..10) println(i)
来源：http://dali.xziqi.cn/Article/details/gtijhshvnn.html

[T15] Kotlin：接口
来源：http://dali.hnqzz.top/Article/details/gtlmkaqaey.html

interface Shape { fun area(): Double }
来源：http://dali.feifeiyinyue.top/Article/details/gtpkvedety.html

[T16] Swift：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtkvvhlppg.html

print("Hello")
来源：http://dali.zdqjudy.top/Article/details/gtmwiwujmx.html

[T17] Swift：变量与常量
来源：http://dali.nanxuanxn.top/Article/details/gtnwpbwzws.html

var a = 1;  let b = 2
来源：http://dali.guannengcc.top/Article/details/gtgfjsxpzm.html

[T18] Swift：字符串插值
来源：http://dali.hywenlv.cn/Article/details/gtrxthnnzi.html

"值: \(b)"
来源：http://dali.yanxiufei.cn/Article/details/gtvfopomhx.html

[T19] Swift：可选绑定
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnkjcyjcc.html

if let n = opt { print(n) }
来源：http://dali.yueranfly.top/Article/details/gthvuhxlev.html

[T20] Swift：数组操作
来源：http://dali.tanke756.top/Article/details/gtcijznjxh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sufxvd.cn/Article/details/gtweqvidsj.html

[T21] Swift：遍历
来源：http://dali.hywenlv.cn/Article/details/gtsamdyaxu.html

for x in a { print(x) }
来源：http://dali.smart0.xyz/Article/details/gtxudugcqi.html

[T22] Swift：字典
来源：http://dali.vqdsnc.cn/Article/details/gtlszjyafz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gotoacloud.top/Article/details/gtbnsqeaef.html

[T23] Swift：函数
来源：http://dali.tanke756.top/Article/details/gtrmqaejsl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthnwrqzvh.html

[T24] Swift：闭包
来源：http://dali.jiagoushi.top/Article/details/gtxiaawbxt.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.aibaodan.cn/Article/details/gtywcsfebf.html

[T25] Swift：结构体
来源：http://dali.hongshengwenyu.top/Article/details/gtujofwddd.html

struct P { var x: Int }
来源：http://dali.gzhubu.top/Article/details/gtoijtmuxo.html

[T26] Swift：类与重写
来源：http://dali.tian-w.cn/Article/details/gtugyclbdr.html

class A: Base { override func f() {} }
来源：http://dali.yonumen.top/Article/details/gtxojvayhu.html

[T27] Swift：错误处理
来源：http://dali.hnqzz.top/Article/details/gtjknvlnjj.html

do { try f() } catch { print(error) }
来源：http://dali.hammf.cn/Article/details/gtwnnttbtt.html

[T28] Swift：枚举
来源：http://dali.jinqigufen.top/Article/details/gtnzwicnix.html

enum Color { case red, green }
来源：http://dali.zhongyouzk.top/Article/details/gtmzyvcmrj.html

[T29] Swift：guard 提前返回
来源：http://dali.zhongyouzk.top/Article/details/gtzyumorov.html

guard let x = opt else { return }
来源：http://dali.pengpengdd.cyou/Article/details/gtupndoyks.html

[T30] Swift：协议
来源：http://dali.sufxvd.cn/Article/details/gtwkypxppz.html

protocol Shape { func area() -> Double }
来源：http://dali.smart0.xyz/Article/details/gtlhhwwysa.html

[T31] Lua：Hello World
来源：http://dali.ivvv.top/Article/details/gtxktchfcc.html

print("Hello")
来源：http://dali.zhoulong.xyz/Article/details/gtkjapusux.html

[T32] Lua：局部变量
来源：http://dali.fzhhl.top/Article/details/gtcfkjifnn.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gtaaajrhpb.html

[T33] Lua：表（数组）
来源：http://dali.tian-w.cn/Article/details/gtlqhzfaqp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shuidangran.top/Article/details/gtzdygnkuv.html

[T34] Lua：遍历表
来源：http://dali.wangdashe.top/Article/details/gtzcyzzmia.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.nwbrower.top/Article/details/gtbvqircfk.html

[T35] Lua：字典表
来源：http://dali.hammf.cn/Article/details/gtmhrwtunu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.dashuyun.cn/Article/details/gtvuuvyehv.html

[T36] Lua：函数
来源：http://dali.smart0.xyz/Article/details/gtzxryfdtq.html

function add(a, b) return a + b end
来源：http://dali.bjfxy.top/Article/details/gtukgbzoiq.html

[T37] Lua：字符串拼接
来源：http://dali.daxiang520.top/Article/details/gtxqmyjlxo.html

"a" .. "b"
来源：http://dali.yj20258888.top/Article/details/gtkwzpljwj.html

[T38] Lua：条件
来源：http://dali.0kj1m.cn/Article/details/gtejbtrbht.html

if x > 0 then print("正") end
来源：http://dali.zycfv.cn/Article/details/gtuutanfyv.html

[T39] Lua：模式匹配
来源：http://dali.cashguo.top/Article/details/gttfniowmu.html

string.find(s, "%d+")
来源：http://dali.9152youxi.cn/Article/details/gtkxwetkdp.html

[T40] Lua：元表
来源：http://dali.hfpthk.cn/Article/details/gtyqgxrcjm.html

setmetatable({}, { __index = base })
来源：http://dali.snrcjt.cn/Article/details/gtoxktawrq.html

[T41] Perl：Hello World
来源：http://dali.316326.xyz/Article/details/gtkxwcwqqf.html

print "Hello\n";
来源：http://dali.sysykeji.top/Article/details/gtuambuhcg.html

[T42] Perl：变量类型
来源：http://dali.tanke756.top/Article/details/gtkxfocgfi.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yuanzhike.top/Article/details/gtigkxvylm.html

[T43] Perl：字符串插值
来源：http://dali.daxiang520.top/Article/details/gtcanknhyf.html

"值: $a"
来源：http://dali.xuanzx.com/Article/details/gteizgvkcx.html

[T44] Perl：条件
来源：http://dali.xuanzx.com/Article/details/gtehehdmyn.html

if ($a > 0) { print "正"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtawjzejvc.html

[T45] Perl：数组遍历
来源：http://dali.jqgufenzy.top/Article/details/gtarejlxvx.html

for my $x (@arr) { print $x; }
来源：http://dali.bjfxy.top/Article/details/gtwbrjyxac.html

[T46] Perl：哈希操作
来源：http://dali.daxiang520.top/Article/details/gtbdxhrjtg.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtxhyfxmsb.html

[T47] Perl：正则捕获
来源：http://dali.zhengqikj.top/Article/details/gtowhgpjza.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.andypj.xyz/Article/details/gtuoolgblo.html

[T48] Perl：正则替换
来源：http://dali.pycfn.com/Article/details/gtwvuvmjnt.html

$s =~ s/old/new/g;
来源：http://dali.hysaishi.cn/Article/details/gtnspezean.html

[T49] Perl：函数
来源：http://dali.jianghu66.top/Article/details/gtiwtkpmsc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.daxiang520.top/Article/details/gtyvkkrbvb.html

[T50] Perl：逐行读文件
来源：http://dali.yj20258888.top/Article/details/gtvlvmspfi.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ppjwa.cn/Article/details/gtxxwfkdld.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.guowangkeji.top/Article/details/gtflurbovl.html

[T51] Scala：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtqrqmiifm.html

println("Hello")
来源：http://dali.hysaishi.cn/Article/details/gtdbqmjadm.html

[T52] Scala：变量
来源：http://dali.ivvv.top/Article/details/gteyoljqnn.html

val a = 1;  var b = 2
来源：http://dali.zdqjudy.top/Article/details/gtmhyimysp.html

[T53] Scala：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gtrpirwfok.html

s"值: $b"
来源：http://dali.sysykeji.top/Article/details/gtcovftryc.html

[T54] Scala：集合映射
来源：http://dali.zycfv.cn/Article/details/gtmfdpyfpu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.dashuyun.cn/Article/details/gtclemvkcc.html

[T55] Scala：集合过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gtywtqugjm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.dianchejie.cn/Article/details/gtwpknwrbb.html

[T56] Scala：样例类
来源：http://dali.jinqigufen.top/Article/details/gtxlwvfnek.html

case class User(name: String, age: Int)
来源：http://dali.aibaodan.cn/Article/details/gtlakjntsp.html

[T57] Scala：模式匹配
来源：http://dali.xuanzx.com/Article/details/gtstcuzjtu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.quarkkingdee.top/Article/details/gtehcuvjbq.html

[T58] Scala：函数定义
来源：http://dali.shzxlz.cn/Article/details/gtnhfkderp.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.iojbl.cn/Article/details/gtqqzlibtk.html

[T59] Scala：循环
来源：http://dali.c1oappe.top/Article/details/gtclerhpsi.html

for (i <- 1 to 10) println(i)
来源：http://dali.gotoacloud.top/Article/details/gtknwmyimo.html

[T60] Scala：折叠
来源：http://dali.ehwqpu.com/Article/details/gtuufkdnhj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jqgfzy.top/Article/details/gtdxuxuztj.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtmptaabks.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.tianlin.xyz/Article/details/gtwkgrzgmq.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsrvljszk.html

[U01] Py：创建虚拟环境
来源：http://dali.meibo888.top/Article/details/gticaudywc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shanyushiyangtech.top/Article/details/gtnngwbfjg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xinyue.icu/Article/details/gtzzaogddn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hysaishi.cn/Article/details/gtfikntuwq.html

[U03] Py：加载 .env 配置
来源：http://dali.quarkkingdee.top/Article/details/gtyjkyixmn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.sweek.top/Article/details/gtlkmolbtk.html

[U04] Py：变量调试打印
来源：http://dali.hnqzz.top/Article/details/gtgglmwknv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpjnqovnm.html

[U05] Py：列表去重且保序
来源：http://dali.jinqigufen.top/Article/details/gtgswimoua.html

list(dict.fromkeys(arr))
来源：http://dali.yj20258.top/Article/details/gttzliehze.html

[U06] Py：合并两个字典
来源：http://dali.ppjwa.cn/Article/details/gtssxplztk.html

{**a, **b}
来源：http://dali.iojbl.cn/Article/details/gtletunnmq.html

[U07] Py：反转字典键值
来源：http://dali.guannengcc.top/Article/details/gtudvdyvvs.html

{v: k for k, v in d.items()}
来源：http://dali.sweek.top/Article/details/gtzthciamm.html

[U08] Py：展平二维列表
来源：http://dali.yangfankeji.com/Article/details/gttqlqfusf.html

[y for x in nested for y in x]
来源：http://dali.jyoumei.cn/Article/details/gtgxeattpp.html


<!-- 参考信息 -->