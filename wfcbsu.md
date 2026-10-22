代发 wailian999

openssl rand -hex 16
来源：http://dali.cheryme.top/Article/details/gtswesvtpr.html

[R68] 计算文件校验值
来源：http://dali.hfpthk.cn/Article/details/gtxhldinqv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yangfankeji.com/Article/details/gtmmzcqrax.html

[R69] 生成随机密码
来源：http://dali.yueranfly.top/Article/details/gtqmgjlaxr.html

head -c 16 /dev/urandom | base64
来源：http://dali.tianlin.xyz/Article/details/gthbdtfing.html

[R70] 时间戳与互转
来源：http://dali.aizwys.cn/Article/details/gttkgrbqla.html

date +%s;  date -d @1700000000
来源：http://dali.jinqigufen.top/Article/details/gtaksylarq.html

[R71] 日期格式化
来源：http://dali.chenzaomai.com/Article/details/gtkcftqfbk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yangfankeji.com/Article/details/gtewrvehks.html

[R72] 等待端口就绪
来源：http://dali.xziqi.cn/Article/details/gtvqyivwbw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.haohaochexian.top/Article/details/gtebztzpwh.html

[R73] 分割大日志
来源：http://dali.jqgufenzy.top/Article/details/gtxxaenuqn.html

split -l 1000 big.log part_
来源：http://dali.jiagoushi.top/Article/details/gtjkerygtg.html

[R74] 批量重命名
来源：http://dali.chenzaomai.com/Article/details/gtllicwuuk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yj202588.top/Article/details/gtbsyvvnmr.html

[R75] 导出环境变量
来源：http://dali.ybcxt.top/Article/details/gteybxxaxn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.9152youxi.cn/Article/details/gtiwgpoafx.html

[R76] 使用临时文件
来源：http://dali.chenzaomai.com/Article/details/gthjesimtq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cheryme.top/Article/details/gtirfwaoec.html

[R77] 读取用户输入
来源：http://dali.ywan-chungtsiang.top/Article/details/gtprhiaqmv.html

read -rp "请输入: " ans
来源：http://dali.snrcjt.cn/Article/details/gtngznxgpm.html

[R78] 交互式菜单
来源：http://dali.quarkkingdee.top/Article/details/gtsmaceoxa.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ivvv.top/Article/details/gtbumlffxc.html

[R79] 解析命令行选项
来源：http://dali.chenjidiqi.icu/Article/details/gtqzkgxqpv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.0kj1m.cn/Article/details/gtuphqsiyb.html

[R80] 查看脚本执行耗时
来源：http://dali.quarkkingdee.top/Article/details/gtwdybircc.html

time ./run.sh
来源：http://dali.nwbrower.top/Article/details/gtrjtxpbjf.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtthkcmatt.html

S. C / C++ 专题
来源：http://dali.quarkkingdee.top/Article/details/gtgpjgmdtb.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtkhfiwzdk.html

[S01] C：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtephpktob.html

#include <stdio.h>
来源：http://dali.hammf.cn/Article/details/gtsqmfjtoa.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gzhubu.top/Article/details/gtwvhnkspf.html

[S02] C：变量与格式化输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzokurxcu.html

int a = 10; printf("%d\n", a);
来源：http://dali.gaohongyu789.top/Article/details/gtqithhvmw.html

[S03] C：读入整数
来源：http://dali.ydzc1.top/Article/details/gtxeokiuad.html

int x; scanf("%d", &x);
来源：http://dali.xziqi.cn/Article/details/gtrniopeek.html

[S04] C：字符串复制
来源：http://dali.gogol.net.cn/Article/details/gtxelubgjf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.aizwys.cn/Article/details/gtqnktihxa.html

[S05] C：字符串长度
来源：http://dali.nanxuanxn.top/Article/details/gtloqfxkxq.html

strlen(s)
来源：http://dali.xinyue.icu/Article/details/gtdzbmddpr.html

[S06] C：字符串比较
来源：http://dali.zhengqikj.top/Article/details/gtpyaccykp.html

strcmp(a, b) == 0
来源：http://dali.fengsongda.top/Article/details/gtxstrjgdy.html

[S07] C：数组遍历求和
来源：http://dali.hnxiangtu.top/Article/details/gtnozmkfeh.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhiwuduotai.top/Article/details/gtebwqregh.html

[S08] C：动态内存分配与释放
来源：http://dali.xuanzx.com/Article/details/gthcpahiiq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.daria6918.cn/Article/details/gtjbhcjkff.html

[S09] C：结构体定义与初始化
来源：http://dali.316326.xyz/Article/details/gtlxrhzufk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.dashuyun.cn/Article/details/gtickzeqjn.html

[S10] C：指针与解引用
来源：http://dali.nanxuanxn.top/Article/details/gtvioxbppc.html

int *p = &a;  *p = 5;
来源：http://dali.hnxiangtu.top/Article/details/gtupzhqemw.html

[S11] C：逐行读文件
来源：http://dali.ivvv.top/Article/details/gtkjcdfwsr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gotoacloud.top/Article/details/gtzadthydh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yuxming.cn/Article/details/gtddwecbak.html

fclose(f);
来源：http://dali.daria6918.cn/Article/details/gtawoccosx.html

[S12] C：写文件
来源：http://dali.aizwys.cn/Article/details/gttydzguio.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jyoumei.cn/Article/details/gtpnmqicdw.html

[S13] C：宏定义
来源：http://dali.birdmap.top/Article/details/gtuvgsrsya.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sxryk.cn/Article/details/gtrsaokihv.html

[S14] C：枚举
来源：http://dali.chenjidiqi.icu/Article/details/gteqdnntcy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.chenlongwang.top/Article/details/gtqxhqdkjq.html

[S15] C：类型转换
来源：http://dali.ydzc1.top/Article/details/gtbeubnvpl.html

(double) a / b
来源：http://dali.zhixingplan.top/Article/details/gtogxsarpz.html

[S16] C：位操作置位
来源：http://dali.yangfankeji.com/Article/details/gtqoqojase.html

x |= (1 << 3);
来源：http://dali.tanke756.top/Article/details/gtlmfofiuj.html

[S17] C：安全拼接字符串
来源：http://dali.andypj.xyz/Article/details/gtogazcrhu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.meibo888.top/Article/details/gtjplcqsmk.html

[S18] C：命令行参数
来源：http://dali.ydzc1.top/Article/details/gtcaktrpbx.html

int main(int argc, char **argv)
来源：http://dali.dashuyun.cn/Article/details/gtdeoyqrcg.html

[S19] C：快速排序
来源：http://dali.fengsongda.top/Article/details/gtfbaascyk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.fengsongda.top/Article/details/gtbbmdhleb.html

[S20] C：二分查找
来源：http://dali.zhixingplan.top/Article/details/gtzcubacpx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.daria6918.cn/Article/details/gtrgllherk.html

[S21] C：字符类别判断
来源：http://dali.xylfe.cn/Article/details/gtoaqhsqql.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yj20258888.top/Article/details/gtsmgdbsjn.html

[S22] C：字符串转数字
来源：http://dali.birdmap.top/Article/details/gtzwyfcbjb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.iojbl.cn/Article/details/gtgxbpithn.html

[S23] C：随机数
来源：http://dali.hammf.cn/Article/details/gtogwkmusf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yj202588.top/Article/details/gtpfdjitpe.html

[S24] C：获取本地时间
来源：http://dali.hysaishi.cn/Article/details/gttduoaegv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.guowangkeji.top/Article/details/gtibxcooff.html

[S25] C：内存拷贝
来源：http://dali.cheryme.top/Article/details/gtgyznkdtp.html

memcpy(dst, src, n);
来源：http://dali.yanxiufei.cn/Article/details/gtkvgvnmsi.html

[S26] C：内存清零
来源：http://dali.jyoumei.cn/Article/details/gtnjfcyeud.html

memset(a, 0, sizeof a);
来源：http://dali.hnqzz.top/Article/details/gtugafezzj.html

[S27] C：定义常量
来源：http://dali.ivvv.top/Article/details/gtnahtfxus.html

const double PI = 3.14159;
来源：http://dali.smart0.xyz/Article/details/gtdyvlafdb.html

[S28] C：静态变量
来源：http://dali.gaohongyu789.top/Article/details/gtnbaamplz.html

static int counter = 0;
来源：http://dali.yanxiufei.cn/Article/details/gtfwxencqh.html

[S29] C：变参函数
来源：http://dali.hfpthk.cn/Article/details/gtxblseohn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.andypj.xyz/Article/details/gtedoqydxp.html

[S30] C：头文件保护
来源：http://dali.hammf.cn/Article/details/gtsrxnpsgf.html

#ifndef X_H
来源：http://dali.nanxuanxn.top/Article/details/gteycjmgsd.html

#define X_H
来源：http://dali.aizwys.cn/Article/details/gtvoliftif.html

#endif
来源：http://dali.yongpay.top/Article/details/gtwadgggsp.html

[S31] C++：Hello World
来源：http://dali.birdmap.top/Article/details/gtyvxsriek.html

#include <iostream>
来源：http://dali.chenlongwang.top/Article/details/gtlxezscgc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtwdkosglx.html

[S32] C++：字符串
来源：http://dali.tianlin.xyz/Article/details/gtvsjsqdxr.html

std::string s = "hi";  s += "!";
来源：http://dali.daxiang520.top/Article/details/gthqitjisr.html

[S33] C++：vector 增删
来源：http://dali.zhongyouzk.top/Article/details/gtvjzcpnli.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xylfe.cn/Article/details/gtqgneubmv.html

[S34] C++：遍历 vector
来源：http://dali.feifeiyinyue.top/Article/details/gtmcdlemlb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhengqikj.top/Article/details/gtluxtfzpo.html

[S35] C++：map
来源：http://dali.wangshuangyany.cn/Article/details/gtysltgprj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shuidangran.top/Article/details/gtpifpncax.html

[S36] C++：unordered_map
来源：http://dali.bjfxy.top/Article/details/gtavrtcfwe.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yangfankeji.com/Article/details/gttebwupxs.html

[S37] C++：set
来源：http://dali.zhengqikj.top/Article/details/gtmzwwcqtq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.svipenyu.cn/Article/details/gtjuuqejvq.html

[S38] C++：排序
来源：http://dali.jianghu66.top/Article/details/gtuaxbrqli.html

std::sort(v.begin(), v.end());
来源：http://dali.daria6918.cn/Article/details/gtgbywbtuk.html

[S39] C++：自定义比较器排序
来源：http://dali.mhx1999.top/Article/details/gtnsgwrlek.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.bjfxy.top/Article/details/gtfxpjvqnn.html

[S40] C++：查找元素
来源：http://dali.shuidangran.top/Article/details/gtzsqzxrkc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.birdmap.top/Article/details/gtytfmmhzx.html

[S41] C++：类与构造函数
来源：http://dali.gotoacloud.top/Article/details/gtznhiabee.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yuanzhike.top/Article/details/gtwkkwwtsv.html

[S42] C++：继承与虚函数
来源：http://dali.nanxuanxn.top/Article/details/gtrllqkwto.html

class B : public Base { public: void f() override {} };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlsmpdqjk.html

[S43] C++：智能指针
来源：http://dali.cdnleiting.top/Article/details/gtgrfjsqmr.html

auto p = std::make_unique<int>(5);
来源：http://dali.kuanghao11.cn/Article/details/gtjpbatrik.html

[S44] C++：引用传参
来源：http://dali.pycfn.com/Article/details/gtaicbinxb.html

void inc(int &x) { ++x; }
来源：http://dali.shanyushiyangtech.top/Article/details/gthkrlitob.html

[S45] C++：lambda
来源：http://dali.cheryme.top/Article/details/gtubvbrfma.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.bjfxy.top/Article/details/gtolbktdmm.html

[S46] C++：函数模板
来源：http://dali.gotoacloud.top/Article/details/gtjwcsgqip.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.tanke756.top/Article/details/gtaeddgmns.html

[S47] C++：结构化绑定遍历
来源：http://dali.chenzaomai.com/Article/details/gtaehkrbdt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xuanzx.com/Article/details/gtqmammbss.html

[S48] C++：逐行读文件
来源：http://dali.jqgufenzy.top/Article/details/gttpejqzfc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.pycfn.com/Article/details/gtcbsxfmpr.html

while (std::getline(in, line)) { }
来源：http://dali.havefunace.top/Article/details/gtcagaqymp.html

[S49] C++：写文件
来源：http://dali.yuanzhike.top/Article/details/gtrfaudxml.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.316326.xyz/Article/details/gtmbhipciv.html

[S50] C++：格式化数字
来源：http://dali.quarkkingdee.top/Article/details/gtpnefxzai.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hfpthk.cn/Article/details/gtkkzkuasw.html

[S51] C++：显式类型转换
来源：http://dali.birdmap.top/Article/details/gthncjrbgd.html

static_cast<double>(a) / b
来源：http://dali.c1oappe.top/Article/details/gttrdlylum.html

[S52] C++：const 与 noexcept
来源：http://dali.fzhhl.top/Article/details/gtyblbuhje.html

int size() const noexcept { return n_; }
来源：http://dali.xinyue.icu/Article/details/gtbjjugkyt.html

[S53] C++：移动语义
来源：http://dali.yj20258888.top/Article/details/gtzkedlfyn.html

std::vector<int> w = std::move(v);
来源：http://dali.smart0.xyz/Article/details/gtngvhijrp.html

[S54] C++：异常处理
来源：http://dali.yongpay.top/Article/details/gtkaejfatp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.bjfxy.top/Article/details/gtedipbbnk.html

[S55] C++：结构化绑定
来源：http://dali.yueranfly.top/Article/details/gtunpvvlou.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhongyouzk.top/Article/details/gtijgrqcnh.html

[S56] C++：optional
来源：http://dali.hnqzz.top/Article/details/gtyjybqcsb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tianlin.xyz/Article/details/gtjvdcurxq.html

[S57] C++：编译期常量
来源：http://dali.ivvv.top/Article/details/gtapdzfhii.html

constexpr int N = 10;
来源：http://dali.redwolf501.top/Article/details/gtyykcqkpj.html

[S58] C++：命名空间
来源：http://dali.hammf.cn/Article/details/gtryfmxjtn.html

namespace ns { int f() { return 1; } }
来源：http://dali.yongpay.top/Article/details/gttxyuhwfw.html

[S59] C++：静态断言
来源：http://dali.xuetiantiany.cn/Article/details/gttosispyp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.iojbl.cn/Article/details/gtktfjazjw.html

[S60] C++：遍历并删除元素
来源：http://dali.jinqigufen.top/Article/details/gthbsxzjfn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpctdetkr.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtzpocvymo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hammf.cn/Article/details/gtgsnvfglh.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtinzaoutn.html

[T01] Kotlin：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtgeiiwuhh.html

println("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqtdclgdo.html

[T02] Kotlin：变量
来源：http://dali.bjfxy.top/Article/details/gtifooandd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.aibaodan.cn/Article/details/gtjytsghjz.html

[T03] Kotlin：字符串模板
来源：http://dali.zhijiandao.cn/Article/details/gtwnebvxdo.html

"值: $b"
来源：http://dali.hfpthk.cn/Article/details/gttblnnpzr.html

[T04] Kotlin：空安全
来源：http://dali.iojbl.cn/Article/details/gtkvanaycg.html

val n: String? = null;  n?.length
来源：http://dali.sysykeji.top/Article/details/gtnbrantpv.html

[T05] Kotlin：when 表达式
来源：http://dali.fzhhl.top/Article/details/gtfiucmajb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jianghu66.top/Article/details/gtnefgdidb.html

[T06] Kotlin：集合映射
来源：http://dali.snrcjt.cn/Article/details/gtvqylwquq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.fzhhl.top/Article/details/gtzphdsqyq.html

[T07] Kotlin：集合过滤
来源：http://dali.chenzaomai.com/Article/details/gtkkzilteg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.fengsongda.top/Article/details/gttzveuokn.html

[T08] Kotlin：数据类
来源：http://dali.mhx1999.top/Article/details/gtbaofhifs.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gtlqqpysrz.html

[T09] Kotlin：扩展函数
来源：http://dali.ppjwa.cn/Article/details/gtllskkubq.html

fun String.exclaim() = this + "!"
来源：http://dali.sysykeji.top/Article/details/gtazpoqyvw.html

[T10] Kotlin：默认参数
来源：http://dali.jlsjyb.cn/Article/details/gtcrblevyl.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.fengsongda.top/Article/details/gttaqiodbp.html

[T11] Kotlin：协程
来源：http://dali.smart0.xyz/Article/details/gtineeqigk.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.chenlongwang.top/Article/details/gttmobrqkt.html

[T12] Kotlin：解构声明
来源：http://dali.sufxvd.cn/Article/details/gtuyknljol.html

val (a, b) = Pair(1, 2)
来源：http://dali.ybcxt.top/Article/details/gtdhdqdgpm.html

[T13] Kotlin：只读 Map
来源：http://dali.aizwys.cn/Article/details/gtfetgrmca.html

val m = mapOf("a" to 1)
来源：http://dali.redwolf501.top/Article/details/gtojfxjgbb.html

[T14] Kotlin：循环
来源：http://dali.yvedp.cn/Article/details/gtaizhceyq.html

for (i in 1..10) println(i)
来源：http://dali.yvedp.cn/Article/details/gtlpiiwvlq.html

[T15] Kotlin：接口
来源：http://dali.yongpay.top/Article/details/gtvnfwdaez.html

interface Shape { fun area(): Double }
来源：http://dali.ivvv.top/Article/details/gtqjekbznz.html

[T16] Swift：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthptjypcx.html

print("Hello")
来源：http://dali.0kj1m.cn/Article/details/gtsimftadb.html

[T17] Swift：变量与常量
来源：http://dali.feifeiyinyue.top/Article/details/gtvzojoviy.html

var a = 1;  let b = 2
来源：http://dali.xylfe.cn/Article/details/gtofscmnwv.html

[T18] Swift：字符串插值
来源：http://dali.wangshuangyany.cn/Article/details/gtlaguiuwe.html

"值: \(b)"
来源：http://dali.zhengqikj.top/Article/details/gtlymkmdyd.html

[T19] Swift：可选绑定
来源：http://dali.dashuyun.cn/Article/details/gtgtepvenk.html

if let n = opt { print(n) }
来源：http://dali.wangdashe.top/Article/details/gtrpmfvsgq.html

[T20] Swift：数组操作
来源：http://dali.meibo888.top/Article/details/gtardhqgqk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.quarkkingdee.top/Article/details/gtxkhhupyi.html

[T21] Swift：遍历
来源：http://dali.havefunace.top/Article/details/gteuunivdt.html

for x in a { print(x) }
来源：http://dali.shangyingyoupin.top/Article/details/gtkppvybrq.html

[T22] Swift：字典
来源：http://dali.snrcjt.cn/Article/details/gtxfztwpmc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.iojbl.cn/Article/details/gtgciyszfn.html

[T23] Swift：函数
来源：http://dali.ehwqpu.com/Article/details/gtzkdoeesb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jqgfzy.top/Article/details/gtwokjmysf.html

[T24] Swift：闭包
来源：http://dali.sxryk.cn/Article/details/gttrcjzibu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ivvv.top/Article/details/gtippvfagc.html

[T25] Swift：结构体
来源：http://dali.dashuyun.cn/Article/details/gtryfbucug.html

struct P { var x: Int }
来源：http://dali.redwolf501.top/Article/details/gtgseneowu.html

[T26] Swift：类与重写
来源：http://dali.sysykeji.top/Article/details/gtefyrytln.html

class A: Base { override func f() {} }
来源：http://dali.yongpay.top/Article/details/gtihyhgbkm.html

[T27] Swift：错误处理
来源：http://dali.316326.xyz/Article/details/gtlnraoroi.html

do { try f() } catch { print(error) }
来源：http://dali.zycfv.cn/Article/details/gtekutykfy.html

[T28] Swift：枚举
来源：http://dali.jqgufenzy.top/Article/details/gtabgajced.html

enum Color { case red, green }
来源：http://dali.c1oappe.top/Article/details/gtcuyjrrmn.html

[T29] Swift：guard 提前返回
来源：http://dali.shanyushiyangtech.top/Article/details/gtifiuymqm.html

guard let x = opt else { return }
来源：http://dali.jqgfzy.top/Article/details/gtxurceaws.html

[T30] Swift：协议
来源：http://dali.hywenlv.cn/Article/details/gtycyhtdvc.html

protocol Shape { func area() -> Double }
来源：http://dali.zhengqikj.top/Article/details/gtzsyqwbpg.html

[T31] Lua：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtiptqtghv.html

print("Hello")
来源：http://dali.svipenyu.cn/Article/details/gtghrsitlj.html

[T32] Lua：局部变量
来源：http://dali.sysykeji.top/Article/details/gtxxoglzai.html

local a = 1
来源：http://dali.pycfn.com/Article/details/gterxfgttn.html

[T33] Lua：表（数组）
来源：http://dali.cqqwz.cn/Article/details/gtgggzucuk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xinyue.icu/Article/details/gtiaxpzulv.html

[T34] Lua：遍历表
来源：http://dali.havefunace.top/Article/details/gtulfbqrnw.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shangyingyoupin.top/Article/details/gtbyvsqvvj.html

[T35] Lua：字典表
来源：http://dali.tianlin.xyz/Article/details/gtqlbsewnx.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xuetiantiany.cn/Article/details/gtihpvmhrr.html

[T36] Lua：函数
来源：http://dali.chenlongwang.top/Article/details/gtpeadvowz.html

function add(a, b) return a + b end
来源：http://dali.wangshuangyany.cn/Article/details/gtznpqapvn.html

[T37] Lua：字符串拼接
来源：http://dali.xylfe.cn/Article/details/gtemapapnt.html

"a" .. "b"
来源：http://dali.yonumen.top/Article/details/gtyptaylod.html

[T38] Lua：条件
来源：http://dali.svipenyu.cn/Article/details/gtrkdgkllj.html

if x > 0 then print("正") end
来源：http://dali.yueranfly.top/Article/details/gttfqeiqxt.html

[T39] Lua：模式匹配
来源：http://dali.wangdashe.top/Article/details/gtvjklhola.html

string.find(s, "%d+")
来源：http://dali.zhongyouzk.top/Article/details/gtzguqeefq.html

[T40] Lua：元表
来源：http://dali.bjfxy.top/Article/details/gtcdiblzrn.html

setmetatable({}, { __index = base })
来源：http://dali.andypj.xyz/Article/details/gtttzifzkq.html

[T41] Perl：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtnqmgktfk.html

print "Hello\n";
来源：http://dali.cheryme.top/Article/details/gtpbtxevjl.html

[T42] Perl：变量类型
来源：http://dali.aizwys.cn/Article/details/gtwaakoypj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yvedp.cn/Article/details/gtodqaxjkt.html

[T43] Perl：字符串插值
来源：http://dali.havefunace.top/Article/details/gtwvzokmun.html

"值: $a"
来源：http://dali.hfpthk.cn/Article/details/gtixggkqdf.html

[T44] Perl：条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmjbolffx.html

if ($a > 0) { print "正"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmcijbsvn.html

[T45] Perl：数组遍历
来源：http://dali.ydzc1.top/Article/details/gtwcyhauct.html

for my $x (@arr) { print $x; }
来源：http://dali.zhiwuduotai.top/Article/details/gtddzmkwru.html

[T46] Perl：哈希操作
来源：http://dali.svipenyu.cn/Article/details/gtocfuokky.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.iojbl.cn/Article/details/gtaocwigst.html

[T47] Perl：正则捕获
来源：http://dali.mhx1999.top/Article/details/gthskrlabj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yueranfly.top/Article/details/gtfuuwbimx.html

[T48] Perl：正则替换
来源：http://dali.hywenlv.cn/Article/details/gtgzvgtauc.html

$s =~ s/old/new/g;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcwytgjjt.html

[T49] Perl：函数
来源：http://dali.yonumen.top/Article/details/gtnzqeasad.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.aibaodan.cn/Article/details/gtrnummhiv.html

[T50] Perl：逐行读文件
来源：http://dali.jqgufenzy.top/Article/details/gtivjojmzs.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xinyue.icu/Article/details/gtmjsbtefs.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.shzxlz.cn/Article/details/gtnqbndwxc.html

[T51] Scala：Hello World
来源：http://dali.zhixingplan.top/Article/details/gteuvbhfca.html

println("Hello")
来源：http://dali.zhengqikj.top/Article/details/gtdhyvjwbf.html

[T52] Scala：变量
来源：http://dali.yuxming.cn/Article/details/gtykutqdsj.html

val a = 1;  var b = 2
来源：http://dali.ybcxt.top/Article/details/gtahdmmssh.html

[T53] Scala：字符串插值
来源：http://dali.pengpengdd.cyou/Article/details/gtiqdibenc.html

s"值: $b"
来源：http://dali.dashuyun.cn/Article/details/gtlxokxqrm.html

[T54] Scala：集合映射
来源：http://dali.cqqwz.cn/Article/details/gtcfggicuw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cashguo.top/Article/details/gtrdpdlyhu.html

[T55] Scala：集合过滤
来源：http://dali.gzhubu.top/Article/details/gtafkgqasc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yuxming.cn/Article/details/gtdnjozhhj.html

[T56] Scala：样例类
来源：http://dali.c1oappe.top/Article/details/gtzbdazhgz.html

case class User(name: String, age: Int)
来源：http://dali.bjfxy.top/Article/details/gtfcmpsqkd.html

[T57] Scala：模式匹配
来源：http://dali.feifeiyinyue.top/Article/details/gtqhwwfisf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yj20258888.top/Article/details/gtwlmlxcnn.html

[T58] Scala：函数定义
来源：http://dali.zdqjudy.top/Article/details/gtuahiikid.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.shuidangran.top/Article/details/gtylavomvn.html

[T59] Scala：循环
来源：http://dali.nanxuanxn.top/Article/details/gtxdvgygwa.html

for (i <- 1 to 10) println(i)
来源：http://dali.redwolf501.top/Article/details/gtzertxyoc.html

[T60] Scala：折叠
来源：http://dali.yj20258888.top/Article/details/gtswbzceln.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zdqjudy.top/Article/details/gtcfcvuqxb.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtqsxadqsj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.dashuyun.cn/Article/details/gtpqywrmiu.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtxwxefwzs.html

[U01] Py：创建虚拟环境
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfwzlustv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.ybcxt.top/Article/details/gtruzwydhx.html

[U02] Py：导出 / 安装依赖
来源：http://dali.tian-w.cn/Article/details/gtgtfautqs.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yanxiufei.cn/Article/details/gtszclxcvf.html

[U03] Py：加载 .env 配置
来源：http://dali.pengpengdd.cyou/Article/details/gtjuoserrn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jlsjyb.cn/Article/details/gtllqctkhq.html

[U04] Py：变量调试打印
来源：http://dali.aizwys.cn/Article/details/gtvjpbhaxs.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.shanyushiyangkeji.top/Article/details/gtooysvncq.html

[U05] Py：列表去重且保序
来源：http://dali.xylfe.cn/Article/details/gtywgkwoxk.html

list(dict.fromkeys(arr))
来源：http://dali.zhixingplan.top/Article/details/gttbxztrer.html

[U06] Py：合并两个字典
来源：http://dali.cucudq.cn/Article/details/gtgrfbywjb.html

{**a, **b}
来源：http://dali.mhx1999.top/Article/details/gtnariktwc.html

[U07] Py：反转字典键值
来源：http://dali.cheryme.top/Article/details/gtobvnalnd.html

{v: k for k, v in d.items()}
来源：http://dali.c1oappe.top/Article/details/gtemjjubkr.html

[U08] Py：展平二维列表
来源：http://dali.jianghu66.top/Article/details/gtkpqwoijc.html

[y for x in nested for y in x]
来源：http://dali.chenjidiqi.icu/Article/details/gtrpsxrwls.html


<!-- 参考信息 -->