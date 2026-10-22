代发 wailian999

df -h;  du -sh *
来源：http://dali.zhoulong.xyz/Article/details/gtvweegbxk.html

[R62] 找最占空间的文件
来源：http://dali.nwbrower.top/Article/details/gtywvcsjml.html

du -ah . | sort -rh | head -10
来源：http://dali.aizwys.cn/Article/details/gtihcbdfyt.html

[R63] 内存与进程
来源：http://dali.pycfn.com/Article/details/gttbxdxzpi.html

free -h;  ps aux | grep nginx
来源：http://dali.dashuyun.cn/Article/details/gtlbgeatyg.html

[R64] 结束进程
来源：http://dali.nanxuanxn.top/Article/details/gtonaxxnfw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhiwuduotai.top/Article/details/gtstuqunko.html

[R65] 查看端口占用
来源：http://dali.cashguo.top/Article/details/gtsacffyms.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cashguo.top/Article/details/gtbpqmkarn.html

[R66] 定时任务
来源：http://dali.hnqzz.top/Article/details/gtrlawlpbb.html

crontab -e;  crontab -l
来源：http://dali.smart0.xyz/Article/details/gtvfoxnjrj.html

[R67] 生成随机十六进制串
来源：http://dali.daxiang520.top/Article/details/gtlndkvtpu.html

openssl rand -hex 16
来源：http://dali.hfpthk.cn/Article/details/gtzjhziyua.html

[R68] 计算文件校验值
来源：http://dali.zhongyouzk.top/Article/details/gtwadqnoon.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.aibaodan.cn/Article/details/gtopdpdzqi.html

[R69] 生成随机密码
来源：http://dali.birdmap.top/Article/details/gthmshqscw.html

head -c 16 /dev/urandom | base64
来源：http://dali.chenjidiqi.icu/Article/details/gtodsbpthu.html

[R70] 时间戳与互转
来源：http://dali.bjfxy.top/Article/details/gtwucnwfml.html

date +%s;  date -d @1700000000
来源：http://dali.nwbrower.top/Article/details/gtcqeprjkc.html

[R71] 日期格式化
来源：http://dali.zhiwuduotai.top/Article/details/gtsvzoqvln.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hnxiangtu.top/Article/details/gtziovnglg.html

[R72] 等待端口就绪
来源：http://dali.tianlin.xyz/Article/details/gtprlxapyp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtdzfdrzws.html

[R73] 分割大日志
来源：http://dali.hnxiangtu.top/Article/details/gtxgzytedl.html

split -l 1000 big.log part_
来源：http://dali.cheryme.top/Article/details/gtmdtrefsz.html

[R74] 批量重命名
来源：http://dali.dianchejie.cn/Article/details/gtlznbwqgd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tianlin.xyz/Article/details/gtvfzksjyf.html

[R75] 导出环境变量
来源：http://dali.guowangkeji.top/Article/details/gtfluyzkts.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gzhubu.top/Article/details/gtdpmqbjaf.html

[R76] 使用临时文件
来源：http://dali.iojbl.cn/Article/details/gtypzxyati.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ybcxt.top/Article/details/gtcxjrknfc.html

[R77] 读取用户输入
来源：http://dali.shangyingyoupin.top/Article/details/gtldvbpomj.html

read -rp "请输入: " ans
来源：http://dali.sweek.top/Article/details/gtpvagvtdi.html

[R78] 交互式菜单
来源：http://dali.yangfankeji.com/Article/details/gthwsvfdpz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hywenlv.cn/Article/details/gtupbdsnhk.html

[R79] 解析命令行选项
来源：http://dali.tanke756.top/Article/details/gtlwjusmkh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shzxlz.cn/Article/details/gtnxopsdwu.html

[R80] 查看脚本执行耗时
来源：http://dali.ppjwa.cn/Article/details/gtnznueapg.html

time ./run.sh
来源：http://dali.shanyushiyangkeji.top/Article/details/gthvvihjkw.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtakweciwa.html

S. C / C++ 专题
来源：http://dali.jiagoushi.top/Article/details/gtavqsnqfz.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtmqqaipff.html

[S01] C：Hello World
来源：http://dali.aizwys.cn/Article/details/gtanplvjvi.html

#include <stdio.h>
来源：http://dali.316326.xyz/Article/details/gtdwhiwmnd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yvedp.cn/Article/details/gtespfaugp.html

[S02] C：变量与格式化输出
来源：http://dali.shangyingyoupin.top/Article/details/gtxbbrpdxb.html

int a = 10; printf("%d\n", a);
来源：http://dali.hysaishi.cn/Article/details/gtoulnrpyn.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gtvauarhve.html

int x; scanf("%d", &x);
来源：http://dali.yuxming.cn/Article/details/gtwpmwgpgc.html

[S04] C：字符串复制
来源：http://dali.yvedp.cn/Article/details/gtxpkclyaa.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.fzhhl.top/Article/details/gtswqvxpjm.html

[S05] C：字符串长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtegaufawf.html

strlen(s)
来源：http://dali.jiagoushi.top/Article/details/gtkimjrkik.html

[S06] C：字符串比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrsqwfmdh.html

strcmp(a, b) == 0
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfavnwujf.html

[S07] C：数组遍历求和
来源：http://dali.andypj.xyz/Article/details/gtkanrpzux.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.andypj.xyz/Article/details/gtrducyhcw.html

[S08] C：动态内存分配与释放
来源：http://dali.xylfe.cn/Article/details/gtgtscgkzx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nanxinkj.top/Article/details/gtklljyzrr.html

[S09] C：结构体定义与初始化
来源：http://dali.vqdsnc.cn/Article/details/gtmtnywpnd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.havefunace.top/Article/details/gtwyoteigk.html

[S10] C：指针与解引用
来源：http://dali.kuanghao11.cn/Article/details/gtmbuzflee.html

int *p = &a;  *p = 5;
来源：http://dali.jqgufenzy.top/Article/details/gtnxqyehue.html

[S11] C：逐行读文件
来源：http://dali.zhixingplan.top/Article/details/gtnbloxduq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xinyue.icu/Article/details/gtpoycfbix.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmoyohipf.html

fclose(f);
来源：http://dali.jlsjyb.cn/Article/details/gtgeavzing.html

[S12] C：写文件
来源：http://dali.birdmap.top/Article/details/gtfkdxlezq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sysykeji.top/Article/details/gthfcijnih.html

[S13] C：宏定义
来源：http://dali.hywenlv.cn/Article/details/gtoaqkstvt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hongshengwenyu.top/Article/details/gtykqijvjp.html

[S14] C：枚举
来源：http://dali.snrcjt.cn/Article/details/gtvdelnkka.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cashguo.top/Article/details/gtpvsugwmb.html

[S15] C：类型转换
来源：http://dali.shangyingyoupin.top/Article/details/gtkoqoqpeh.html

(double) a / b
来源：http://dali.daxiang520.top/Article/details/gtptfikrui.html

[S16] C：位操作置位
来源：http://dali.fengsongda.top/Article/details/gtgxqelltl.html

x |= (1 << 3);
来源：http://dali.wangshuangyany.cn/Article/details/gtnzlsyrtz.html

[S17] C：安全拼接字符串
来源：http://dali.gogol.net.cn/Article/details/gtggliartl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.fengsongda.top/Article/details/gtdgdiahat.html

[S18] C：命令行参数
来源：http://dali.dashuyun.cn/Article/details/gtddmwqaii.html

int main(int argc, char **argv)
来源：http://dali.jinqigfzy.top/Article/details/gtvurypdkz.html

[S19] C：快速排序
来源：http://dali.zhiwuduotai.top/Article/details/gttviuzzbs.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gzhubu.top/Article/details/gtsvvkbimo.html

[S20] C：二分查找
来源：http://dali.jiagoushi.top/Article/details/gtuegdenda.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tian-w.cn/Article/details/gtamfonzcj.html

[S21] C：字符类别判断
来源：http://dali.wangshuangyany.cn/Article/details/gtkajmnwxq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtapswwfjy.html

[S22] C：字符串转数字
来源：http://dali.xuanzx.com/Article/details/gtxhvevvlb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.316326.xyz/Article/details/gtdbnicjay.html

[S23] C：随机数
来源：http://dali.chenjidiqi.icu/Article/details/gtaebmkoci.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yanxiufei.cn/Article/details/gtuvzkjngk.html

[S24] C：获取本地时间
来源：http://dali.mhx1999.top/Article/details/gtcbvvmarh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cucudq.cn/Article/details/gtkgsoybun.html

[S25] C：内存拷贝
来源：http://dali.gogol.net.cn/Article/details/gtsjvdloeq.html

memcpy(dst, src, n);
来源：http://dali.daria6918.cn/Article/details/gtdufnfvwc.html

[S26] C：内存清零
来源：http://dali.gzhubu.top/Article/details/gtmjnxnbsi.html

memset(a, 0, sizeof a);
来源：http://dali.yuanzhike.top/Article/details/gticexuauo.html

[S27] C：定义常量
来源：http://dali.316326.xyz/Article/details/gtnamzvrth.html

const double PI = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gtnlihbrym.html

[S28] C：静态变量
来源：http://dali.ppjwa.cn/Article/details/gtkmtccphm.html

static int counter = 0;
来源：http://dali.gotoacloud.top/Article/details/gtqxjcwgxa.html

[S29] C：变参函数
来源：http://dali.jyoumei.cn/Article/details/gtstuxrdrc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpuwqgeig.html

[S30] C：头文件保护
来源：http://dali.gogol.net.cn/Article/details/gturilojlc.html

#ifndef X_H
来源：http://dali.jlsjyb.cn/Article/details/gtyeqlpiyv.html

#define X_H
来源：http://dali.pengpengdd.cyou/Article/details/gtkuhskfnb.html

#endif
来源：http://dali.zhongyouzk.top/Article/details/gtqhbrlqsf.html

[S31] C++：Hello World
来源：http://dali.hysaishi.cn/Article/details/gtfkwgtfsb.html

#include <iostream>
来源：http://dali.jinghuilouyu.cn/Article/details/gtrwmkeurq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.havefunace.top/Article/details/gtvlmldvvb.html

[S32] C++：字符串
来源：http://dali.zhoulong.xyz/Article/details/gtfouundcl.html

std::string s = "hi";  s += "!";
来源：http://dali.shangyingyoupin.top/Article/details/gttysvlwhj.html

[S33] C++：vector 增删
来源：http://dali.xinyue.icu/Article/details/gtmflcotvb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.316326.xyz/Article/details/gtpnmlzsnn.html

[S34] C++：遍历 vector
来源：http://dali.pengpengdd.cyou/Article/details/gtieggwqtw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhiwuduotai.top/Article/details/gtupyaerbr.html

[S35] C++：map
来源：http://dali.ybcxt.top/Article/details/gtrkpirgbr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigufen.top/Article/details/gtkedxnbpg.html

[S36] C++：unordered_map
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdasttloi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gtycvqzsxz.html

[S37] C++：set
来源：http://dali.sxryk.cn/Article/details/gtwkfglvvp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yangfankeji.com/Article/details/gtjsrtnbcw.html

[S38] C++：排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtadsrxvzk.html

std::sort(v.begin(), v.end());
来源：http://dali.yj20258888.top/Article/details/gtyfjxxwbh.html

[S39] C++：自定义比较器排序
来源：http://dali.yanxiufei.cn/Article/details/gtgqgoypia.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.daria6918.cn/Article/details/gtevirxzdh.html

[S40] C++：查找元素
来源：http://dali.yj202588.top/Article/details/gtjgdcoimq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gttwuggkey.html

[S41] C++：类与构造函数
来源：http://dali.guowangkeji.top/Article/details/gttxayvxbo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.haohaochexian.top/Article/details/gtqbenkcap.html

[S42] C++：继承与虚函数
来源：http://dali.iojbl.cn/Article/details/gtqcfvvvbq.html

class B : public Base { public: void f() override {} };
来源：http://dali.9152youxi.cn/Article/details/gtsvjttuib.html

[S43] C++：智能指针
来源：http://dali.fzhhl.top/Article/details/gtbpfncxsl.html

auto p = std::make_unique<int>(5);
来源：http://dali.cheryme.top/Article/details/gtbsmvbwvp.html

[S44] C++：引用传参
来源：http://dali.svipenyu.cn/Article/details/gtigypobdc.html

void inc(int &x) { ++x; }
来源：http://dali.shanyushiyangtech.top/Article/details/gttdykvmnm.html

[S45] C++：lambda
来源：http://dali.sysykeji.top/Article/details/gtwemwgyev.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ybcxt.top/Article/details/gtwkfbnssz.html

[S46] C++：函数模板
来源：http://dali.gaohongyu789.top/Article/details/gtamlclyze.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.tanke756.top/Article/details/gtrdxwwxqn.html

[S47] C++：结构化绑定遍历
来源：http://dali.ydzc1.top/Article/details/gtjkmajqim.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jqgufenzy.top/Article/details/gtfewrmjre.html

[S48] C++：逐行读文件
来源：http://dali.xylfe.cn/Article/details/gttbvekvid.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.316326.xyz/Article/details/gtxejvzbxr.html

while (std::getline(in, line)) { }
来源：http://dali.sweek.top/Article/details/gtvjlohwbw.html

[S49] C++：写文件
来源：http://dali.cdnleiting.top/Article/details/gtvsadtjjy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yanxiufei.cn/Article/details/gtxgclkqhs.html

[S50] C++：格式化数字
来源：http://dali.chenlongwang.top/Article/details/gtmsrisbgr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.bjfxy.top/Article/details/gtkjrhokow.html

[S51] C++：显式类型转换
来源：http://dali.ehwqpu.com/Article/details/gtnylkycbw.html

static_cast<double>(a) / b
来源：http://dali.andypj.xyz/Article/details/gtqpwcnbek.html

[S52] C++：const 与 noexcept
来源：http://dali.yuanzhike.top/Article/details/gtjaqsvepo.html

int size() const noexcept { return n_; }
来源：http://dali.yj202588.top/Article/details/gtecdqrjkx.html

[S53] C++：移动语义
来源：http://dali.zhongyouzk.top/Article/details/gtzlibpngm.html

std::vector<int> w = std::move(v);
来源：http://dali.yj202588.top/Article/details/gtrjrsvoee.html

[S54] C++：异常处理
来源：http://dali.yuanzhike.top/Article/details/gtvnhyckfo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cashguo.top/Article/details/gtoljfrwdp.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gtfauucstk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.pycfn.com/Article/details/gtjsaffvpo.html

[S56] C++：optional
来源：http://dali.jqgufenzy.top/Article/details/gtupbnshhw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.aizwys.cn/Article/details/gtyepehrei.html

[S57] C++：编译期常量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtspvleett.html

constexpr int N = 10;
来源：http://dali.yj20258.top/Article/details/gtbjdxucaf.html

[S58] C++：命名空间
来源：http://dali.yangfankeji.com/Article/details/gtqcaivpsu.html

namespace ns { int f() { return 1; } }
来源：http://dali.yuanzhike.top/Article/details/gtwwwanypb.html

[S59] C++：静态断言
来源：http://dali.yonumen.top/Article/details/gtawsjefrk.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jianghu66.top/Article/details/gtkbkusvui.html

[S60] C++：遍历并删除元素
来源：http://dali.birdmap.top/Article/details/gtimofyjia.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.iojbl.cn/Article/details/gtvaxfcwqw.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtkbklococ.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.vqdsnc.cn/Article/details/gtkqobxzpk.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gthqobzgdr.html

[T01] Kotlin：Hello World
来源：http://dali.pycfn.com/Article/details/gtpcfqklqb.html

println("Hello")
来源：http://dali.zhongyouzk.top/Article/details/gtkuyukipx.html

[T02] Kotlin：变量
来源：http://dali.0kj1m.cn/Article/details/gtwnvvflmq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ehwqpu.com/Article/details/gtgmiyiojk.html

[T03] Kotlin：字符串模板
来源：http://dali.zhongyouzk.top/Article/details/gtdrssiixc.html

"值: $b"
来源：http://dali.yj20258888.top/Article/details/gtalegsrbw.html

[T04] Kotlin：空安全
来源：http://dali.shangyingyoupin.top/Article/details/gtlakvhnwt.html

val n: String? = null;  n?.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuclpdvhw.html

[T05] Kotlin：when 表达式
来源：http://dali.nanxinkj.top/Article/details/gtklnejzwo.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinqigfzy.top/Article/details/gtapbahqdw.html

[T06] Kotlin：集合映射
来源：http://dali.shuidangran.top/Article/details/gtgeaqcizo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.316326.xyz/Article/details/gtpvxfekce.html

[T07] Kotlin：集合过滤
来源：http://dali.shangyingyoupin.top/Article/details/gtbwquwxwk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yangfankeji.com/Article/details/gthgylapue.html

[T08] Kotlin：数据类
来源：http://dali.tanke756.top/Article/details/gtyhkwbsuh.html

data class User(val name: String, val age: Int)
来源：http://dali.quarkkingdee.top/Article/details/gtjgzuzaoc.html

[T09] Kotlin：扩展函数
来源：http://dali.ybcxt.top/Article/details/gtcnbsmcxa.html

fun String.exclaim() = this + "!"
来源：http://dali.yj20258.top/Article/details/gtemjzpjln.html

[T10] Kotlin：默认参数
来源：http://dali.xuanzx.com/Article/details/gtqjzxydew.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cdnleiting.top/Article/details/gthflaaqpe.html

[T11] Kotlin：协程
来源：http://dali.redwolf501.top/Article/details/gttwcgivcd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hnqzz.top/Article/details/gtpyibtber.html

[T12] Kotlin：解构声明
来源：http://dali.zdqjudy.top/Article/details/gtjjuncbqc.html

val (a, b) = Pair(1, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtxplhguyv.html

[T13] Kotlin：只读 Map
来源：http://dali.nanxuanxn.top/Article/details/gtmxyuwflw.html

val m = mapOf("a" to 1)
来源：http://dali.chenlongwang.top/Article/details/gtayqcinut.html

[T14] Kotlin：循环
来源：http://dali.chenzaomai.com/Article/details/gtdtmslwfp.html

for (i in 1..10) println(i)
来源：http://dali.ivvv.top/Article/details/gtwnjpiyue.html

[T15] Kotlin：接口
来源：http://dali.mhx1999.top/Article/details/gtqxmkcndn.html

interface Shape { fun area(): Double }
来源：http://dali.smart0.xyz/Article/details/gtbmifdpkv.html

[T16] Swift：Hello World
来源：http://dali.cdnleiting.top/Article/details/gtjftqqdrm.html

print("Hello")
来源：http://dali.pengpengdd.cyou/Article/details/gtwmyblnrx.html

[T17] Swift：变量与常量
来源：http://dali.yongpay.top/Article/details/gtehnkbdyn.html

var a = 1;  let b = 2
来源：http://dali.guowangkeji.top/Article/details/gtoiqcsdao.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gtjsgbunng.html

"值: \(b)"
来源：http://dali.jqgfzy.top/Article/details/gtlvdkpltw.html

[T19] Swift：可选绑定
来源：http://dali.dianchejie.cn/Article/details/gtpovmpizl.html

if let n = opt { print(n) }
来源：http://dali.vqdsnc.cn/Article/details/gtztkuvnjc.html

[T20] Swift：数组操作
来源：http://dali.daria6918.cn/Article/details/gtdfntrekd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jianghu66.top/Article/details/gtbzjrroem.html

[T21] Swift：遍历
来源：http://dali.snrcjt.cn/Article/details/gtovwjflph.html

for x in a { print(x) }
来源：http://dali.hnqzz.top/Article/details/gtypkosmcu.html

[T22] Swift：字典
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjybhbcyc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.andypj.xyz/Article/details/gtjpnmhxor.html

[T23] Swift：函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtljyefywd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cashguo.top/Article/details/gtpmzajlkv.html

[T24] Swift：闭包
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcoandfbr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxswbalvf.html

[T25] Swift：结构体
来源：http://dali.bjfxy.top/Article/details/gtwvllzcia.html

struct P { var x: Int }
来源：http://dali.316326.xyz/Article/details/gtfffvlabo.html

[T26] Swift：类与重写
来源：http://dali.cdnleiting.top/Article/details/gtylhkmgzy.html

class A: Base { override func f() {} }
来源：http://dali.jiagoushi.top/Article/details/gtwdycxkyn.html

[T27] Swift：错误处理
来源：http://dali.tian-w.cn/Article/details/gtknohhmvd.html

do { try f() } catch { print(error) }
来源：http://dali.feifeiyinyue.top/Article/details/gtruidkitq.html

[T28] Swift：枚举
来源：http://dali.zhongyouzk.top/Article/details/gtwjmawsie.html

enum Color { case red, green }
来源：http://dali.yj20258.top/Article/details/gteimpiyin.html

[T29] Swift：guard 提前返回
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjqcwmdyi.html

guard let x = opt else { return }
来源：http://dali.dianchejie.cn/Article/details/gtpmmhmiuw.html

[T30] Swift：协议
来源：http://dali.ybcxt.top/Article/details/gtqzhsmubo.html

protocol Shape { func area() -> Double }
来源：http://dali.daxiang520.top/Article/details/gtjuzdsqgo.html

[T31] Lua：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtivlmtvae.html

print("Hello")
来源：http://dali.cqqwz.cn/Article/details/gtpebaqqtr.html

[T32] Lua：局部变量
来源：http://dali.gotoacloud.top/Article/details/gtkqxzjdxb.html

local a = 1
来源：http://dali.sufxvd.cn/Article/details/gtrlhkyppy.html

[T33] Lua：表（数组）
来源：http://dali.hnxiangtu.top/Article/details/gtccgzqvuo.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hysaishi.cn/Article/details/gtsaajmzsx.html

[T34] Lua：遍历表
来源：http://dali.chenzaomai.com/Article/details/gtzfovdphw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfcbtvqv.html

[T35] Lua：字典表
来源：http://dali.xziqi.cn/Article/details/gtbinkzhyv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hywenlv.cn/Article/details/gtsxihqyow.html

[T36] Lua：函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtobpctykf.html

function add(a, b) return a + b end
来源：http://dali.zhixingplan.top/Article/details/gtvuybfibd.html

[T37] Lua：字符串拼接
来源：http://dali.ivvv.top/Article/details/gtfcskukhl.html

"a" .. "b"
来源：http://dali.ivvv.top/Article/details/gtepqytwxo.html

[T38] Lua：条件
来源：http://dali.zhengqikj.top/Article/details/gtkajhfcul.html

if x > 0 then print("正") end
来源：http://dali.chenlongwang.top/Article/details/gtclhxvxki.html

[T39] Lua：模式匹配
来源：http://dali.cdnleiting.top/Article/details/gthzguivda.html

string.find(s, "%d+")
来源：http://dali.ybcxt.top/Article/details/gtyosnzipg.html

[T40] Lua：元表
来源：http://dali.pycfn.com/Article/details/gtlpxjmtlu.html

setmetatable({}, { __index = base })
来源：http://dali.hongshengwenyu.top/Article/details/gtpwqzjunn.html

[T41] Perl：Hello World
来源：http://dali.ydzc1.top/Article/details/gtjfzoznxi.html

print "Hello\n";
来源：http://dali.havefunace.top/Article/details/gtyfyqqgxk.html

[T42] Perl：变量类型
来源：http://dali.chenlongwang.top/Article/details/gtcopjgngm.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.kuanghao11.cn/Article/details/gtpbpmqzik.html

[T43] Perl：字符串插值
来源：http://dali.gogol.net.cn/Article/details/gtbzjnifak.html

"值: $a"
来源：http://dali.shuidangran.top/Article/details/gtiipmfsre.html

[T44] Perl：条件
来源：http://dali.yongpay.top/Article/details/gtpzzefpqw.html

if ($a > 0) { print "正"; }
来源：http://dali.cqqwz.cn/Article/details/gtuvxmgezo.html

[T45] Perl：数组遍历
来源：http://dali.jlsjyb.cn/Article/details/gtlzzoyqav.html

for my $x (@arr) { print $x; }
来源：http://dali.chenjidiqi.icu/Article/details/gtbngnefff.html

[T46] Perl：哈希操作
来源：http://dali.shuidangran.top/Article/details/gtbamaeyou.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.meibo888.top/Article/details/gtsuzhbwgp.html

[T47] Perl：正则捕获
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgsijbefd.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.snrcjt.cn/Article/details/gtsixfdqtn.html

[T48] Perl：正则替换
来源：http://dali.xuetiantiany.cn/Article/details/gtcbtukudo.html

$s =~ s/old/new/g;
来源：http://dali.jyoumei.cn/Article/details/gtlyyxbihg.html

[T49] Perl：函数
来源：http://dali.hongshengwenyu.top/Article/details/gtrgjikejw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xziqi.cn/Article/details/gtuvjatxws.html

[T50] Perl：逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gtosjtsthe.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinghuilouyu.cn/Article/details/gtmfcraqcu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cheryme.top/Article/details/gtnxjvheut.html

[T51] Scala：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtpunnjecr.html

println("Hello")
来源：http://dali.zhiwuduotai.top/Article/details/gtqwyntrid.html

[T52] Scala：变量
来源：http://dali.jqgfzy.top/Article/details/gtwtexcgka.html

val a = 1;  var b = 2
来源：http://dali.fengsongda.top/Article/details/gtsxnismow.html

[T53] Scala：字符串插值
来源：http://dali.shanyushiyangtech.top/Article/details/gtmbmsgdfe.html

s"值: $b"
来源：http://dali.dianchejie.cn/Article/details/gtshbwxxpa.html

[T54] Scala：集合映射
来源：http://dali.hywenlv.cn/Article/details/gtconuzbjo.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ivvv.top/Article/details/gtmydzdnis.html

[T55] Scala：集合过滤
来源：http://dali.yj20258888.top/Article/details/gteavwczxx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.9152youxi.cn/Article/details/gtvvwgxrct.html

[T56] Scala：样例类
来源：http://dali.jyoumei.cn/Article/details/gtoihppfrh.html

case class User(name: String, age: Int)
来源：http://dali.jqgufenzy.top/Article/details/gtrmeetymi.html

[T57] Scala：模式匹配
来源：http://dali.dianchejie.cn/Article/details/gtqgganfvx.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.fengsongda.top/Article/details/gtqguirguu.html

[T58] Scala：函数定义
来源：http://dali.hfpthk.cn/Article/details/gtxugimbzg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.nwbrower.top/Article/details/gtomdlceuy.html

[T59] Scala：循环
来源：http://dali.xuetiantiany.cn/Article/details/gtrgwefwdq.html

for (i <- 1 to 10) println(i)
来源：http://dali.chenzaomai.com/Article/details/gtevoesoab.html

[T60] Scala：折叠
来源：http://dali.hammf.cn/Article/details/gtzfksrdhg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hnqzz.top/Article/details/gtlclprxiq.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtgeympabf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hfpthk.cn/Article/details/gtnmpnfvip.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtxyugxucx.html

[U01] Py：创建虚拟环境
来源：http://dali.mhx1999.top/Article/details/gtxxkcgadm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.wangshuangyany.cn/Article/details/gtmcxwubed.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cucudq.cn/Article/details/gtcoeeuhtp.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yj20258.top/Article/details/gtodmrftki.html


<!-- 参考信息 -->