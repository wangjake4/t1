代发 wailian999

df -h;  du -sh *
来源：http://dali.cashguo.top/Article/details/gtwciaazio.html

[R62] 找最占空间的文件
来源：http://dali.meibo888.top/Article/details/gtagichdgq.html

du -ah . | sort -rh | head -10
来源：http://dali.jyoumei.cn/Article/details/gtrhidcvqm.html

[R63] 内存与进程
来源：http://dali.havefunace.top/Article/details/gttljfzudl.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gtxcoqxsgt.html

[R64] 结束进程
来源：http://dali.sysykeji.top/Article/details/gtjitfiwex.html

kill -9 $(pgrep -f app.py)
来源：http://dali.nwbrower.top/Article/details/gtpvajeryc.html

[R65] 查看端口占用
来源：http://dali.zhiwuduotai.top/Article/details/gtxsodvqfq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yonumen.top/Article/details/gthdosufxb.html

[R66] 定时任务
来源：http://dali.jiagoushi.top/Article/details/gtqfegeqoj.html

crontab -e;  crontab -l
来源：http://dali.ehwqpu.com/Article/details/gtpnmbsryo.html

[R67] 生成随机十六进制串
来源：http://dali.xylfe.cn/Article/details/gtxmomyfev.html

openssl rand -hex 16
来源：http://dali.jinghuilouyu.cn/Article/details/gtsrybkskt.html

[R68] 计算文件校验值
来源：http://dali.ywan-chungtsiang.top/Article/details/gthwbeudcy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gogol.net.cn/Article/details/gtxzffsiyc.html

[R69] 生成随机密码
来源：http://dali.feifeiyinyue.top/Article/details/gthxoiayre.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhiwuduotai.top/Article/details/gtnryhgtlc.html

[R70] 时间戳与互转
来源：http://dali.tianlin.xyz/Article/details/gtcfsfttbf.html

date +%s;  date -d @1700000000
来源：http://dali.zycfv.cn/Article/details/gtcjwdfayo.html

[R71] 日期格式化
来源：http://dali.tianlin.xyz/Article/details/gtmmeecrco.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.nanxuanxn.top/Article/details/gtdbukgjlk.html

[R72] 等待端口就绪
来源：http://dali.aibaodan.cn/Article/details/gtieksdojz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.vqdsnc.cn/Article/details/gtzkbjburf.html

[R73] 分割大日志
来源：http://dali.jqgfzy.top/Article/details/gthxepzetu.html

split -l 1000 big.log part_
来源：http://dali.yuanzhike.top/Article/details/gthppalzba.html

[R74] 批量重命名
来源：http://dali.sweek.top/Article/details/gtscehxwgl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yuxming.cn/Article/details/gtpnmgybrj.html

[R75] 导出环境变量
来源：http://dali.gotoacloud.top/Article/details/gtqryfqqnj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.fengsongda.top/Article/details/gtmzqyvfvs.html

[R76] 使用临时文件
来源：http://dali.pycfn.com/Article/details/gtkzocrvsc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shangyingyoupin.top/Article/details/gtptfauzle.html

[R77] 读取用户输入
来源：http://dali.chenzaomai.com/Article/details/gtlmxcwkbi.html

read -rp "请输入: " ans
来源：http://dali.hnqzz.top/Article/details/gtjndypeve.html

[R78] 交互式菜单
来源：http://dali.jlsjyb.cn/Article/details/gtaqkcrlsx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yj20258.top/Article/details/gtnrgansze.html

[R79] 解析命令行选项
来源：http://dali.yanxiufei.cn/Article/details/gtsxdsbebi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xinyue.icu/Article/details/gtjpupnfrf.html

[R80] 查看脚本执行耗时
来源：http://dali.yvedp.cn/Article/details/gtyqmjeoji.html

time ./run.sh
来源：http://dali.zhiwuduotai.top/Article/details/gtlztqtjwy.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtelwjsscd.html

S. C / C++ 专题
来源：http://dali.svipenyu.cn/Article/details/gtnikccqxi.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtwlqsougj.html

[S01] C：Hello World
来源：http://dali.aibaodan.cn/Article/details/gthqkrhaop.html

#include <stdio.h>
来源：http://dali.daria6918.cn/Article/details/gtytccevnp.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xylfe.cn/Article/details/gticnufnog.html

[S02] C：变量与格式化输出
来源：http://dali.tianlin.xyz/Article/details/gtxldeskwy.html

int a = 10; printf("%d\n", a);
来源：http://dali.yonumen.top/Article/details/gtvzycxrdr.html

[S03] C：读入整数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtutfpxukg.html

int x; scanf("%d", &x);
来源：http://dali.snrcjt.cn/Article/details/gtsbzeohtm.html

[S04] C：字符串复制
来源：http://dali.havefunace.top/Article/details/gtaxjxzksd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhiwuduotai.top/Article/details/gthpcthrpi.html

[S05] C：字符串长度
来源：http://dali.vqdsnc.cn/Article/details/gtjipsvjdp.html

strlen(s)
来源：http://dali.chenjidiqi.icu/Article/details/gtsvtprjgk.html

[S06] C：字符串比较
来源：http://dali.fengsongda.top/Article/details/gtnwpxhfdn.html

strcmp(a, b) == 0
来源：http://dali.yuanzhike.top/Article/details/gtfjxwwazh.html

[S07] C：数组遍历求和
来源：http://dali.c1oappe.top/Article/details/gtxazouhts.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sxryk.cn/Article/details/gtjkwxrhoy.html

[S08] C：动态内存分配与释放
来源：http://dali.jqgufenzy.top/Article/details/gtaoireapq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhiwuduotai.top/Article/details/gtruheqnhq.html

[S09] C：结构体定义与初始化
来源：http://dali.fengsongda.top/Article/details/gtuujxyoji.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvbtiavmm.html

[S10] C：指针与解引用
来源：http://dali.pycfn.com/Article/details/gtpsueymci.html

int *p = &a;  *p = 5;
来源：http://dali.shzxlz.cn/Article/details/gtshkubxcd.html

[S11] C：逐行读文件
来源：http://dali.daria6918.cn/Article/details/gtipzicedl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.dashuyun.cn/Article/details/gtpvklcice.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ppjwa.cn/Article/details/gtlbnoxzhn.html

fclose(f);
来源：http://dali.fengsongda.top/Article/details/gtbktruuxy.html

[S12] C：写文件
来源：http://dali.ivvv.top/Article/details/gtoytvjtuz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zdqjudy.top/Article/details/gtwbkiuftr.html

[S13] C：宏定义
来源：http://dali.hywenlv.cn/Article/details/gtulrvbxie.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.pycfn.com/Article/details/gtmhhmvtfl.html

[S14] C：枚举
来源：http://dali.haohaochexian.top/Article/details/gtajbfqpaz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gzhubu.top/Article/details/gtmsxrhpri.html

[S15] C：类型转换
来源：http://dali.zycfv.cn/Article/details/gtjwfgcthh.html

(double) a / b
来源：http://dali.pengpengdd.cyou/Article/details/gtqiwbsisg.html

[S16] C：位操作置位
来源：http://dali.cdnleiting.top/Article/details/gtrnvmindx.html

x |= (1 << 3);
来源：http://dali.jlsjyb.cn/Article/details/gtqdlpzicf.html

[S17] C：安全拼接字符串
来源：http://dali.yj202588.top/Article/details/gtucaltfmt.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.bjfxy.top/Article/details/gtzntibkch.html

[S18] C：命令行参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxfebuyrf.html

int main(int argc, char **argv)
来源：http://dali.jinqigufen.top/Article/details/gtmwwzwcdv.html

[S19] C：快速排序
来源：http://dali.yueranfly.top/Article/details/gtkijlhsbs.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.chenjidiqi.icu/Article/details/gthivnclld.html

[S20] C：二分查找
来源：http://dali.yongpay.top/Article/details/gtdwxtnamm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gaohongyu789.top/Article/details/gtfkfqemaa.html

[S21] C：字符类别判断
来源：http://dali.jiagoushi.top/Article/details/gthumzfhmn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhiwuduotai.top/Article/details/gtnxyvqjxa.html

[S22] C：字符串转数字
来源：http://dali.shanyushiyangtech.top/Article/details/gtqoljlzuy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yanxiufei.cn/Article/details/gtwoarykhy.html

[S23] C：随机数
来源：http://dali.nanxuanxn.top/Article/details/gtlnbehjax.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.nwbrower.top/Article/details/gtiacytznu.html

[S24] C：获取本地时间
来源：http://dali.fzhhl.top/Article/details/gtfqqhtnmz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cqqwz.cn/Article/details/gtjqdcppbk.html

[S25] C：内存拷贝
来源：http://dali.pycfn.com/Article/details/gtrpgedzym.html

memcpy(dst, src, n);
来源：http://dali.ydzc1.top/Article/details/gtbuweprgq.html

[S26] C：内存清零
来源：http://dali.daria6918.cn/Article/details/gtrrbifyjv.html

memset(a, 0, sizeof a);
来源：http://dali.hammf.cn/Article/details/gtkayhrlpz.html

[S27] C：定义常量
来源：http://dali.daxiang520.top/Article/details/gtwqlswbov.html

const double PI = 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gtrzbqcqbm.html

[S28] C：静态变量
来源：http://dali.zhoulong.xyz/Article/details/gtynrjrewp.html

static int counter = 0;
来源：http://dali.zycfv.cn/Article/details/gtnzdnqswn.html

[S29] C：变参函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyppaascp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ydzc1.top/Article/details/gtxutsdabi.html

[S30] C：头文件保护
来源：http://dali.cucudq.cn/Article/details/gtffmppiun.html

#ifndef X_H
来源：http://dali.aibaodan.cn/Article/details/gttcgktubs.html

#define X_H
来源：http://dali.zhaomingkeji.xyz/Article/details/gtscggswvu.html

#endif
来源：http://dali.dianchejie.cn/Article/details/gttkqpdxwu.html

[S31] C++：Hello World
来源：http://dali.daria6918.cn/Article/details/gtchudiffg.html

#include <iostream>
来源：http://dali.ydzc1.top/Article/details/gtzvykluql.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.redwolf501.top/Article/details/gtmiodpplj.html

[S32] C++：字符串
来源：http://dali.andypj.xyz/Article/details/gthpibahfb.html

std::string s = "hi";  s += "!";
来源：http://dali.cucudq.cn/Article/details/gtrfazqlwe.html

[S33] C++：vector 增删
来源：http://dali.pengpengdd.cyou/Article/details/gtjismkbvi.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.tian-w.cn/Article/details/gtrjfrhfzs.html

[S34] C++：遍历 vector
来源：http://dali.feifeiyinyue.top/Article/details/gttmqznzhc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.fengsongda.top/Article/details/gteleneqhm.html

[S35] C++：map
来源：http://dali.zhoulong.xyz/Article/details/gtnmxwwdqn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtquohzump.html

[S36] C++：unordered_map
来源：http://dali.jiagoushi.top/Article/details/gthveiagtn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gtzzoasdth.html

[S37] C++：set
来源：http://dali.pycfn.com/Article/details/gtbeeshftn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhiwuduotai.top/Article/details/gtvbxcgefu.html

[S38] C++：排序
来源：http://dali.gzhubu.top/Article/details/gtjgetvzyw.html

std::sort(v.begin(), v.end());
来源：http://dali.fengsongda.top/Article/details/gtfidqfltc.html

[S39] C++：自定义比较器排序
来源：http://dali.jyoumei.cn/Article/details/gtrvxuottd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.birdmap.top/Article/details/gtivjmbaae.html

[S40] C++：查找元素
来源：http://dali.daria6918.cn/Article/details/gtxyvdogbz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.smart0.xyz/Article/details/gtzpgkzhjv.html

[S41] C++：类与构造函数
来源：http://dali.zhoulong.xyz/Article/details/gtpiusahel.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.guannengcc.top/Article/details/gtapwpnjgy.html

[S42] C++：继承与虚函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtbbucamjs.html

class B : public Base { public: void f() override {} };
来源：http://dali.redwolf501.top/Article/details/gtdihzidti.html

[S43] C++：智能指针
来源：http://dali.iojbl.cn/Article/details/gtmbidgvsi.html

auto p = std::make_unique<int>(5);
来源：http://dali.hnqzz.top/Article/details/gtsacphqcp.html

[S44] C++：引用传参
来源：http://dali.birdmap.top/Article/details/gtdqrkjthf.html

void inc(int &x) { ++x; }
来源：http://dali.andypj.xyz/Article/details/gtmcfnztmo.html

[S45] C++：lambda
来源：http://dali.jiagoushi.top/Article/details/gtoavhvbss.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gtjghchnhk.html

[S46] C++：函数模板
来源：http://dali.gotoacloud.top/Article/details/gtjovgyscl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yanxiufei.cn/Article/details/gtdmngqzxa.html

[S47] C++：结构化绑定遍历
来源：http://dali.shzxlz.cn/Article/details/gtojyzkgyr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zdqjudy.top/Article/details/gthfxkazvu.html

[S48] C++：逐行读文件
来源：http://dali.andypj.xyz/Article/details/gtykejfnun.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zycfv.cn/Article/details/gthnuspwgu.html

while (std::getline(in, line)) { }
来源：http://dali.ydzc1.top/Article/details/gtxdvdltjy.html

[S49] C++：写文件
来源：http://dali.ehwqpu.com/Article/details/gthgadlwso.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.0kj1m.cn/Article/details/gtwjbeqobd.html

[S50] C++：格式化数字
来源：http://dali.pengpengdd.cyou/Article/details/gtebswfhtp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gthrpokmkf.html

[S51] C++：显式类型转换
来源：http://dali.jinqigufen.top/Article/details/gtgkmdmsru.html

static_cast<double>(a) / b
来源：http://dali.yongpay.top/Article/details/gtausnbwnb.html

[S52] C++：const 与 noexcept
来源：http://dali.0kj1m.cn/Article/details/gtyjgdcise.html

int size() const noexcept { return n_; }
来源：http://dali.pengpengdd.cyou/Article/details/gtkasmzbvf.html

[S53] C++：移动语义
来源：http://dali.cqqwz.cn/Article/details/gtquhtxeil.html

std::vector<int> w = std::move(v);
来源：http://dali.ppjwa.cn/Article/details/gtdjcdiqfj.html

[S54] C++：异常处理
来源：http://dali.zhengqikj.top/Article/details/gtbqacnuup.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhixingplan.top/Article/details/gtmexecvsw.html

[S55] C++：结构化绑定
来源：http://dali.shanyushiyangtech.top/Article/details/gtzagamyhv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinqigfzy.top/Article/details/gtmozfclxv.html

[S56] C++：optional
来源：http://dali.jqgfzy.top/Article/details/gtavfjhrec.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtejvvdmyj.html

[S57] C++：编译期常量
来源：http://dali.shangyingyoupin.top/Article/details/gtkrvxuqew.html

constexpr int N = 10;
来源：http://dali.jqgufenzy.top/Article/details/gtnyymrini.html

[S58] C++：命名空间
来源：http://dali.cqqwz.cn/Article/details/gtkcrxosau.html

namespace ns { int f() { return 1; } }
来源：http://dali.iojbl.cn/Article/details/gtyviirspz.html

[S59] C++：静态断言
来源：http://dali.ivvv.top/Article/details/gtsuctweza.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.316326.xyz/Article/details/gtjtqumpyn.html

[S60] C++：遍历并删除元素
来源：http://dali.zhoulong.xyz/Article/details/gtbpppxscb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.chenjidiqi.icu/Article/details/gtuwqqhved.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtdofdhpdh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmqaomhkw.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyajqlhcm.html

[T01] Kotlin：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtqqzyljny.html

println("Hello")
来源：http://dali.yj20258888.top/Article/details/gtbxxgddma.html

[T02] Kotlin：变量
来源：http://dali.guannengcc.top/Article/details/gtuycfeenv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.nwbrower.top/Article/details/gttfikrryu.html

[T03] Kotlin：字符串模板
来源：http://dali.birdmap.top/Article/details/gtoenctsql.html

"值: $b"
来源：http://dali.chenjidiqi.icu/Article/details/gterqskuea.html

[T04] Kotlin：空安全
来源：http://dali.yuanzhike.top/Article/details/gtcyxrunao.html

val n: String? = null;  n?.length
来源：http://dali.hfpthk.cn/Article/details/gtvmwprbil.html

[T05] Kotlin：when 表达式
来源：http://dali.smart0.xyz/Article/details/gtmmmnmlag.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinqigufen.top/Article/details/gtzkbnqotb.html

[T06] Kotlin：集合映射
来源：http://dali.iojbl.cn/Article/details/gtrmatpakv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yvedp.cn/Article/details/gtcdmydeqj.html

[T07] Kotlin：集合过滤
来源：http://dali.jinqigufen.top/Article/details/gtyooydhcz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.guannengcc.top/Article/details/gteeiwgofh.html

[T08] Kotlin：数据类
来源：http://dali.daxiang520.top/Article/details/gtnrhxcvvq.html

data class User(val name: String, val age: Int)
来源：http://dali.meibo888.top/Article/details/gtydmfffvk.html

[T09] Kotlin：扩展函数
来源：http://dali.zhiwuduotai.top/Article/details/gtegnixbmi.html

fun String.exclaim() = this + "!"
来源：http://dali.gaohongyu789.top/Article/details/gtgspllsmt.html

[T10] Kotlin：默认参数
来源：http://dali.yonumen.top/Article/details/gtnbtbjuzr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.gotoacloud.top/Article/details/gtqyljwfyp.html

[T11] Kotlin：协程
来源：http://dali.sysykeji.top/Article/details/gtuvsjlfkk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hysaishi.cn/Article/details/gtakloodmo.html

[T12] Kotlin：解构声明
来源：http://dali.sweek.top/Article/details/gtgokjyyrk.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtnapseoig.html

[T13] Kotlin：只读 Map
来源：http://dali.hnqzz.top/Article/details/gttiyaycaj.html

val m = mapOf("a" to 1)
来源：http://dali.xinyue.icu/Article/details/gtypweaokp.html

[T14] Kotlin：循环
来源：http://dali.hnqzz.top/Article/details/gtefebcblw.html

for (i in 1..10) println(i)
来源：http://dali.xuanzx.com/Article/details/gtffqvegow.html

[T15] Kotlin：接口
来源：http://dali.zhongyouzk.top/Article/details/gtsgjndtzt.html

interface Shape { fun area(): Double }
来源：http://dali.hfpthk.cn/Article/details/gtwrntgkgq.html

[T16] Swift：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtipqqppxp.html

print("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gtbaoavsbb.html

[T17] Swift：变量与常量
来源：http://dali.tanke756.top/Article/details/gtkcnaxaxp.html

var a = 1;  let b = 2
来源：http://dali.cqqwz.cn/Article/details/gtdjmeqssp.html

[T18] Swift：字符串插值
来源：http://dali.feifeiyinyue.top/Article/details/gtrrptonvv.html

"值: \(b)"
来源：http://dali.xuetiantiany.cn/Article/details/gtltmulppd.html

[T19] Swift：可选绑定
来源：http://dali.feifeiyinyue.top/Article/details/gtawlqzlvs.html

if let n = opt { print(n) }
来源：http://dali.fengsongda.top/Article/details/gtntpdkuwp.html

[T20] Swift：数组操作
来源：http://dali.jiagoushi.top/Article/details/gtjoyqcjab.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sxryk.cn/Article/details/gtktwvmqez.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gttgvgbtpw.html

for x in a { print(x) }
来源：http://dali.yongpay.top/Article/details/gtpufiikhs.html

[T22] Swift：字典
来源：http://dali.yj202588.top/Article/details/gtzpnqqnnq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.iojbl.cn/Article/details/gtdrhrewmy.html

[T23] Swift：函数
来源：http://dali.quarkkingdee.top/Article/details/gtigfeznet.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jinqigfzy.top/Article/details/gtvypiyawc.html

[T24] Swift：闭包
来源：http://dali.nwbrower.top/Article/details/gtajlxezkf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.redwolf501.top/Article/details/gtgstjobis.html

[T25] Swift：结构体
来源：http://dali.hfpthk.cn/Article/details/gtobiggbkb.html

struct P { var x: Int }
来源：http://dali.316326.xyz/Article/details/gtmibarqbv.html

[T26] Swift：类与重写
来源：http://dali.yongpay.top/Article/details/gtgqmmgbwn.html

class A: Base { override func f() {} }
来源：http://dali.guannengcc.top/Article/details/gtepgaedsn.html

[T27] Swift：错误处理
来源：http://dali.shanyushiyangtech.top/Article/details/gtjgvappwl.html

do { try f() } catch { print(error) }
来源：http://dali.yongpay.top/Article/details/gtkmkkkqll.html

[T28] Swift：枚举
来源：http://dali.zhoulong.xyz/Article/details/gtqzphtrah.html

enum Color { case red, green }
来源：http://dali.yanxiufei.cn/Article/details/gtwkqsbxlc.html

[T29] Swift：guard 提前返回
来源：http://dali.jinghuilouyu.cn/Article/details/gtbpsdifts.html

guard let x = opt else { return }
来源：http://dali.guowangkeji.top/Article/details/gtzqttqyae.html

[T30] Swift：协议
来源：http://dali.zhixingplan.top/Article/details/gtcotjhizl.html

protocol Shape { func area() -> Double }
来源：http://dali.wangshuangyany.cn/Article/details/gtcantftpg.html

[T31] Lua：Hello World
来源：http://dali.shuidangran.top/Article/details/gtcucsqcve.html

print("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gtktufojgv.html

[T32] Lua：局部变量
来源：http://dali.9152youxi.cn/Article/details/gtmhnljydx.html

local a = 1
来源：http://dali.shangyingyoupin.top/Article/details/gtxsnrupbe.html

[T33] Lua：表（数组）
来源：http://dali.xylfe.cn/Article/details/gteniripqw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.chenlongwang.top/Article/details/gtaybdwnvc.html

[T34] Lua：遍历表
来源：http://dali.jqgufenzy.top/Article/details/gtyelwfalz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yuanzhike.top/Article/details/gtvhnvsfou.html

[T35] Lua：字典表
来源：http://dali.yj20258888.top/Article/details/gtkojqhiwx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.dashuyun.cn/Article/details/gtvwjtxpqd.html

[T36] Lua：函数
来源：http://dali.ivvv.top/Article/details/gtgbouaeem.html

function add(a, b) return a + b end
来源：http://dali.cucudq.cn/Article/details/gtnxjmnxgt.html

[T37] Lua：字符串拼接
来源：http://dali.yueranfly.top/Article/details/gtsbgmzzhb.html

"a" .. "b"
来源：http://dali.316326.xyz/Article/details/gtjikesfgr.html

[T38] Lua：条件
来源：http://dali.tanke756.top/Article/details/gtrotprqke.html

if x > 0 then print("正") end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdolmfehk.html

[T39] Lua：模式匹配
来源：http://dali.shuidangran.top/Article/details/gtfocramby.html

string.find(s, "%d+")
来源：http://dali.9152youxi.cn/Article/details/gtojfnogdi.html

[T40] Lua：元表
来源：http://dali.xziqi.cn/Article/details/gtcwxtidim.html

setmetatable({}, { __index = base })
来源：http://dali.zhoulong.xyz/Article/details/gthbtuplxk.html

[T41] Perl：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gttoyamlmo.html

print "Hello\n";
来源：http://dali.shuidangran.top/Article/details/gtdtzlkftz.html

[T42] Perl：变量类型
来源：http://dali.nanxuanxn.top/Article/details/gtvepnanod.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.shuidangran.top/Article/details/gtimebdjtz.html

[T43] Perl：字符串插值
来源：http://dali.xylfe.cn/Article/details/gtdkijyerb.html

"值: $a"
来源：http://dali.gogol.net.cn/Article/details/gtomiebxjp.html

[T44] Perl：条件
来源：http://dali.snrcjt.cn/Article/details/gtnumusrhm.html

if ($a > 0) { print "正"; }
来源：http://dali.kuanghao11.cn/Article/details/gtxzkzxcwo.html

[T45] Perl：数组遍历
来源：http://dali.ybcxt.top/Article/details/gtbnaqmppi.html

for my $x (@arr) { print $x; }
来源：http://dali.gzhubu.top/Article/details/gtkihdxgxk.html

[T46] Perl：哈希操作
来源：http://dali.cucudq.cn/Article/details/gtkgckklgm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.9152youxi.cn/Article/details/gtlutdltkl.html

[T47] Perl：正则捕获
来源：http://dali.tanke756.top/Article/details/gtwwtigbku.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.cucudq.cn/Article/details/gtyzdogkov.html

[T48] Perl：正则替换
来源：http://dali.ivvv.top/Article/details/gtoibcbjar.html

$s =~ s/old/new/g;
来源：http://dali.andypj.xyz/Article/details/gtrbqulefy.html

[T49] Perl：函数
来源：http://dali.guannengcc.top/Article/details/gtwfqtpueu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yj20258.top/Article/details/gtieczsddr.html

[T50] Perl：逐行读文件
来源：http://dali.cucudq.cn/Article/details/gtkrtshovh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.sysykeji.top/Article/details/gtkqrmugys.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.pengpengdd.cyou/Article/details/gtudhbgwxr.html

[T51] Scala：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfcrpddyw.html

println("Hello")
来源：http://dali.xylfe.cn/Article/details/gtxcwccnaf.html

[T52] Scala：变量
来源：http://dali.pengpengdd.cyou/Article/details/gtuivzmqlo.html

val a = 1;  var b = 2
来源：http://dali.zhoulong.xyz/Article/details/gtnkibkkmw.html

[T53] Scala：字符串插值
来源：http://dali.xziqi.cn/Article/details/gtcmplsnht.html

s"值: $b"
来源：http://dali.meibo888.top/Article/details/gtpzatzlum.html

[T54] Scala：集合映射
来源：http://dali.mhx1999.top/Article/details/gtkewzayrz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yongpay.top/Article/details/gtvfpfpkky.html

[T55] Scala：集合过滤
来源：http://dali.xylfe.cn/Article/details/gteauycdor.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yuanzhike.top/Article/details/gtegmcawch.html

[T56] Scala：样例类
来源：http://dali.c1oappe.top/Article/details/gtklnzgbno.html

case class User(name: String, age: Int)
来源：http://dali.cucudq.cn/Article/details/gtquilwadm.html

[T57] Scala：模式匹配
来源：http://dali.hysaishi.cn/Article/details/gtvcpdmifg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cucudq.cn/Article/details/gtvdxogagt.html

[T58] Scala：函数定义
来源：http://dali.mhx1999.top/Article/details/gtaeemkejw.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.sweek.top/Article/details/gtppkjvhwf.html

[T59] Scala：循环
来源：http://dali.hfpthk.cn/Article/details/gtieieofrn.html

for (i <- 1 to 10) println(i)
来源：http://dali.0kj1m.cn/Article/details/gtdmokanwc.html

[T60] Scala：折叠
来源：http://dali.chenzaomai.com/Article/details/gtrncmrfrh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ehwqpu.com/Article/details/gtuvgtuchp.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtzljozifw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.guannengcc.top/Article/details/gtfmwhuhpa.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtbxufagty.html

[U01] Py：创建虚拟环境
来源：http://dali.hysaishi.cn/Article/details/gtsckwpwki.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.guannengcc.top/Article/details/gtkicqsfyy.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jinqigfzy.top/Article/details/gtvepxybng.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.svipenyu.cn/Article/details/gtnbfjwtgg.html


<!-- 参考信息 -->