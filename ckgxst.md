代发 wailian999

openssl rand -hex 16
来源：http://dali.jinqigufen.top/Article/details/gtssxtaodg.html

[R68] 计算文件校验值
来源：http://dali.sxryk.cn/Article/details/gtojxxbdvp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sxryk.cn/Article/details/gtfedxzfhz.html

[R69] 生成随机密码
来源：http://dali.redwolf501.top/Article/details/gtgtmbllws.html

head -c 16 /dev/urandom | base64
来源：http://dali.redwolf501.top/Article/details/gtagjytnuo.html

[R70] 时间戳与互转
来源：http://dali.jlsjyb.cn/Article/details/gtachzfuag.html

date +%s;  date -d @1700000000
来源：http://dali.meibo888.top/Article/details/gtoxxprqhz.html

[R71] 日期格式化
来源：http://dali.hongshengwenyu.top/Article/details/gtdtvwzixv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shuidangran.top/Article/details/gttckxvyrj.html

[R72] 等待端口就绪
来源：http://dali.ehwqpu.com/Article/details/gthsczqmwj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hysaishi.cn/Article/details/gtfxooycaz.html

[R73] 分割大日志
来源：http://dali.xuetiantiany.cn/Article/details/gtkrpasnxi.html

split -l 1000 big.log part_
来源：http://dali.svipenyu.cn/Article/details/gtujhxzoto.html

[R74] 批量重命名
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzzxptqyn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yj20258888.top/Article/details/gtcdylajwm.html

[R75] 导出环境变量
来源：http://dali.yuxming.cn/Article/details/gtyvnkazzb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ivvv.top/Article/details/gtoxybtwun.html

[R76] 使用临时文件
来源：http://dali.chenzaomai.com/Article/details/gtintmjdgu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cqqwz.cn/Article/details/gtnhjtlhzz.html

[R77] 读取用户输入
来源：http://dali.chenzaomai.com/Article/details/gtntblttwz.html

read -rp "请输入: " ans
来源：http://dali.pycfn.com/Article/details/gtvwhfwsmq.html

[R78] 交互式菜单
来源：http://dali.gogol.net.cn/Article/details/gtybutgdkz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtylpvzabi.html

[R79] 解析命令行选项
来源：http://dali.hywenlv.cn/Article/details/gtfoqwdndj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.chenlongwang.top/Article/details/gtkvdacidf.html

[R80] 查看脚本执行耗时
来源：http://dali.shuidangran.top/Article/details/gtdkqmdlqs.html

time ./run.sh
来源：http://dali.yuxming.cn/Article/details/gtmpglgfhi.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtwcyghaok.html

S. C / C++ 专题
来源：http://dali.dianchejie.cn/Article/details/gtipztpiwv.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtkyrjsumk.html

[S01] C：Hello World
来源：http://dali.daxiang520.top/Article/details/gttjebhons.html

#include <stdio.h>
来源：http://dali.nanxuanxn.top/Article/details/gtzljkefyg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.birdmap.top/Article/details/gtmitxrooa.html

[S02] C：变量与格式化输出
来源：http://dali.jqgufenzy.top/Article/details/gtpxkbjklm.html

int a = 10; printf("%d\n", a);
来源：http://dali.smart0.xyz/Article/details/gtfqfrkqgs.html

[S03] C：读入整数
来源：http://dali.nwbrower.top/Article/details/gttndklkiz.html

int x; scanf("%d", &x);
来源：http://dali.birdmap.top/Article/details/gtzhkvrdxx.html

[S04] C：字符串复制
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgvjnbnth.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.tian-w.cn/Article/details/gtwuxsufhj.html

[S05] C：字符串长度
来源：http://dali.jiagoushi.top/Article/details/gtegsujfwz.html

strlen(s)
来源：http://dali.guannengcc.top/Article/details/gtuwtfoqaa.html

[S06] C：字符串比较
来源：http://dali.chenjidiqi.icu/Article/details/gtwxdmbtiq.html

strcmp(a, b) == 0
来源：http://dali.gaohongyu789.top/Article/details/gtvqokvzor.html

[S07] C：数组遍历求和
来源：http://dali.chenzaomai.com/Article/details/gttpacvsar.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.meibo888.top/Article/details/gtuaxfszeb.html

[S08] C：动态内存分配与释放
来源：http://dali.zhoulong.xyz/Article/details/gtlgvipqya.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xuanzx.com/Article/details/gtvwcmeoni.html

[S09] C：结构体定义与初始化
来源：http://dali.shangyingyoupin.top/Article/details/gtivzmniaa.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ydzc1.top/Article/details/gtpzzxhhjf.html

[S10] C：指针与解引用
来源：http://dali.kuanghao11.cn/Article/details/gtxkclfzsx.html

int *p = &a;  *p = 5;
来源：http://dali.zhiwuduotai.top/Article/details/gtetielmhx.html

[S11] C：逐行读文件
来源：http://dali.ivvv.top/Article/details/gtazrtcnai.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jianghu66.top/Article/details/gthknfuolm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yongpay.top/Article/details/gtuuojeppu.html

fclose(f);
来源：http://dali.xylfe.cn/Article/details/gtjchpdbla.html

[S12] C：写文件
来源：http://dali.nanxinkj.top/Article/details/gtsmpqcurn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sysykeji.top/Article/details/gteksbylky.html

[S13] C：宏定义
来源：http://dali.aibaodan.cn/Article/details/gtottshrcw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ydzc1.top/Article/details/gtukauqhcb.html

[S14] C：枚举
来源：http://dali.jinqigfzy.top/Article/details/gtmtenhdxo.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhengqikj.top/Article/details/gtvgbbital.html

[S15] C：类型转换
来源：http://dali.nanxinkj.top/Article/details/gtvlyxrtue.html

(double) a / b
来源：http://dali.jyoumei.cn/Article/details/gtyahqtsdo.html

[S16] C：位操作置位
来源：http://dali.tian-w.cn/Article/details/gtyjnhpcwy.html

x |= (1 << 3);
来源：http://dali.jqgfzy.top/Article/details/gtodcyslym.html

[S17] C：安全拼接字符串
来源：http://dali.yanxiufei.cn/Article/details/gtqevmtcuu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.havefunace.top/Article/details/gtflxqitky.html

[S18] C：命令行参数
来源：http://dali.jiagoushi.top/Article/details/gtynydoxrg.html

int main(int argc, char **argv)
来源：http://dali.cashguo.top/Article/details/gtdxmgzljh.html

[S19] C：快速排序
来源：http://dali.tian-w.cn/Article/details/gtvsvizcta.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.nanxinkj.top/Article/details/gtqwmsglwn.html

[S20] C：二分查找
来源：http://dali.hfpthk.cn/Article/details/gtbswnbhaf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yangfankeji.com/Article/details/gtsmutihwf.html

[S21] C：字符类别判断
来源：http://dali.yvedp.cn/Article/details/gthuumawhx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hongshengwenyu.top/Article/details/gtfovpafcs.html

[S22] C：字符串转数字
来源：http://dali.gaohongyu789.top/Article/details/gtkswifiws.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.aizwys.cn/Article/details/gtryttfyct.html

[S23] C：随机数
来源：http://dali.cashguo.top/Article/details/gtxbesprmy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shuidangran.top/Article/details/gtqpspyllq.html

[S24] C：获取本地时间
来源：http://dali.vqdsnc.cn/Article/details/gtsfewvgzd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhiwuduotai.top/Article/details/gtllggmlgo.html

[S25] C：内存拷贝
来源：http://dali.jiagoushi.top/Article/details/gtsnzhmtga.html

memcpy(dst, src, n);
来源：http://dali.hnxiangtu.top/Article/details/gtipvxigqz.html

[S26] C：内存清零
来源：http://dali.sufxvd.cn/Article/details/gtzmtojhlf.html

memset(a, 0, sizeof a);
来源：http://dali.hnxiangtu.top/Article/details/gtxfdomdwi.html

[S27] C：定义常量
来源：http://dali.meibo888.top/Article/details/gtikotzrez.html

const double PI = 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gtrntuuugv.html

[S28] C：静态变量
来源：http://dali.daxiang520.top/Article/details/gtgascpvgq.html

static int counter = 0;
来源：http://dali.jiagoushi.top/Article/details/gtfxntajvj.html

[S29] C：变参函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrnirorko.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhixingplan.top/Article/details/gtzbaiyoba.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gtbmbibksl.html

#ifndef X_H
来源：http://dali.yvedp.cn/Article/details/gteogwendk.html

#define X_H
来源：http://dali.daxiang520.top/Article/details/gtuwczxvtq.html

#endif
来源：http://dali.cqqwz.cn/Article/details/gtvipxkaob.html

[S31] C++：Hello World
来源：http://dali.xylfe.cn/Article/details/gtyjsgnqhe.html

#include <iostream>
来源：http://dali.nanxinkj.top/Article/details/gtvpnahsld.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jiagoushi.top/Article/details/gtuwpzpsrf.html

[S32] C++：字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtadstaiko.html

std::string s = "hi";  s += "!";
来源：http://dali.zycfv.cn/Article/details/gtotrdmrht.html

[S33] C++：vector 增删
来源：http://dali.shanyushiyangtech.top/Article/details/gteqavngjx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.daria6918.cn/Article/details/gtlcaeyddi.html

[S34] C++：遍历 vector
来源：http://dali.jlsjyb.cn/Article/details/gtutjhrjod.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ybcxt.top/Article/details/gtmeydnkxd.html

[S35] C++：map
来源：http://dali.shuidangran.top/Article/details/gtxcktnltn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jianghu66.top/Article/details/gtmmsyxjay.html

[S36] C++：unordered_map
来源：http://dali.cucudq.cn/Article/details/gtimfrkaly.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guowangkeji.top/Article/details/gtxatsydpk.html

[S37] C++：set
来源：http://dali.yueranfly.top/Article/details/gtmytzqqep.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yueranfly.top/Article/details/gtulmtlvha.html

[S38] C++：排序
来源：http://dali.daria6918.cn/Article/details/gtyglotepi.html

std::sort(v.begin(), v.end());
来源：http://dali.jinghuilouyu.cn/Article/details/gtgcyztbye.html

[S39] C++：自定义比较器排序
来源：http://dali.yuanzhike.top/Article/details/gtmaydvulb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gaohongyu789.top/Article/details/gttlffcgnz.html

[S40] C++：查找元素
来源：http://dali.wangdashe.top/Article/details/gtmhkyecsl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaxfhexwz.html

[S41] C++：类与构造函数
来源：http://dali.zdqjudy.top/Article/details/gtdnqohduj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinghuilouyu.cn/Article/details/gtdcookrrq.html

[S42] C++：继承与虚函数
来源：http://dali.zhiwuduotai.top/Article/details/gtgxigyyye.html

class B : public Base { public: void f() override {} };
来源：http://dali.ydzc1.top/Article/details/gtokqgkpcb.html

[S43] C++：智能指针
来源：http://dali.tanke756.top/Article/details/gtxuhtcjjv.html

auto p = std::make_unique<int>(5);
来源：http://dali.shangyingyoupin.top/Article/details/gtvbwcucfh.html

[S44] C++：引用传参
来源：http://dali.nanxuanxn.top/Article/details/gtwcdgigzh.html

void inc(int &x) { ++x; }
来源：http://dali.hysaishi.cn/Article/details/gtcqervjlw.html

[S45] C++：lambda
来源：http://dali.hywenlv.cn/Article/details/gtijnqlmoy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxztcsdn.html

[S46] C++：函数模板
来源：http://dali.guowangkeji.top/Article/details/gtqqfvsmau.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jqgfzy.top/Article/details/gttshvttpk.html

[S47] C++：结构化绑定遍历
来源：http://dali.yangfankeji.com/Article/details/gtumeffoba.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cashguo.top/Article/details/gtdkyvnzbp.html

[S48] C++：逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gtqzwymphn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.vqdsnc.cn/Article/details/gtdxwhjqbl.html

while (std::getline(in, line)) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gtapjbjsms.html

[S49] C++：写文件
来源：http://dali.meibo888.top/Article/details/gtvptpmppc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sufxvd.cn/Article/details/gtwpkjanvk.html

[S50] C++：格式化数字
来源：http://dali.hongshengwenyu.top/Article/details/gtmwxeuczc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gzhubu.top/Article/details/gtnnjwzbhu.html

[S51] C++：显式类型转换
来源：http://dali.meibo888.top/Article/details/gtiwwwarpd.html

static_cast<double>(a) / b
来源：http://dali.zhixingplan.top/Article/details/gtbcgxtwfe.html

[S52] C++：const 与 noexcept
来源：http://dali.yonumen.top/Article/details/gtobejdtgb.html

int size() const noexcept { return n_; }
来源：http://dali.hongshengwenyu.top/Article/details/gtembujres.html

[S53] C++：移动语义
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcgdpyqda.html

std::vector<int> w = std::move(v);
来源：http://dali.dianchejie.cn/Article/details/gtmompcuuo.html

[S54] C++：异常处理
来源：http://dali.wangdashe.top/Article/details/gtqjsnfzkm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zdqjudy.top/Article/details/gtkyvlugvk.html

[S55] C++：结构化绑定
来源：http://dali.zhongyouzk.top/Article/details/gtkkayhjxb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yongpay.top/Article/details/gtxziprwvv.html

[S56] C++：optional
来源：http://dali.yuanzhike.top/Article/details/gtgsvtprkh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.birdmap.top/Article/details/gtrvfmxhjl.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gtmtehbolx.html

constexpr int N = 10;
来源：http://dali.ybcxt.top/Article/details/gtkgutrlqg.html

[S58] C++：命名空间
来源：http://dali.bjfxy.top/Article/details/gtiegpdgft.html

namespace ns { int f() { return 1; } }
来源：http://dali.yuanzhike.top/Article/details/gtyvcetkul.html

[S59] C++：静态断言
来源：http://dali.shzxlz.cn/Article/details/gtbrjqlbbx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.vqdsnc.cn/Article/details/gtipouqxcj.html

[S60] C++：遍历并删除元素
来源：http://dali.yuxming.cn/Article/details/gtplduympw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.vqdsnc.cn/Article/details/gtdudiycto.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtohzqvtgh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xziqi.cn/Article/details/gtallsvvdn.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtexcjbqgn.html

[T01] Kotlin：Hello World
来源：http://dali.cqqwz.cn/Article/details/gthrzjneoj.html

println("Hello")
来源：http://dali.aibaodan.cn/Article/details/gtmwnuwgyi.html

[T02] Kotlin：变量
来源：http://dali.cheryme.top/Article/details/gtbjoiubah.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.dashuyun.cn/Article/details/gtzadrcqrc.html

[T03] Kotlin：字符串模板
来源：http://dali.haohaochexian.top/Article/details/gtchspvklk.html

"值: $b"
来源：http://dali.yongpay.top/Article/details/gtuakttadg.html

[T04] Kotlin：空安全
来源：http://dali.fzhhl.top/Article/details/gtraiytoiw.html

val n: String? = null;  n?.length
来源：http://dali.ydzc1.top/Article/details/gthaalmxov.html

[T05] Kotlin：when 表达式
来源：http://dali.zycfv.cn/Article/details/gtjjmibrcg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yuanzhike.top/Article/details/gtpfcvsmml.html

[T06] Kotlin：集合映射
来源：http://dali.yuanzhike.top/Article/details/gtbpygaaij.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtiajpdigl.html

[T07] Kotlin：集合过滤
来源：http://dali.ppjwa.cn/Article/details/gtbvuwynan.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.haohaochexian.top/Article/details/gtvjapypxe.html

[T08] Kotlin：数据类
来源：http://dali.hysaishi.cn/Article/details/gtsyppupth.html

data class User(val name: String, val age: Int)
来源：http://dali.daria6918.cn/Article/details/gtvcwnizcu.html

[T09] Kotlin：扩展函数
来源：http://dali.hnqzz.top/Article/details/gtuqwkdrsz.html

fun String.exclaim() = this + "!"
来源：http://dali.hysaishi.cn/Article/details/gtptpvtlod.html

[T10] Kotlin：默认参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtebwfmdqu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.wangdashe.top/Article/details/gtbmncpdpt.html

[T11] Kotlin：协程
来源：http://dali.tianlin.xyz/Article/details/gtnubsxauc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yvedp.cn/Article/details/gtytzqvpjh.html

[T12] Kotlin：解构声明
来源：http://dali.havefunace.top/Article/details/gtmmkdzyir.html

val (a, b) = Pair(1, 2)
来源：http://dali.iojbl.cn/Article/details/gtwqgdksaw.html

[T13] Kotlin：只读 Map
来源：http://dali.jyoumei.cn/Article/details/gtwgiycrnh.html

val m = mapOf("a" to 1)
来源：http://dali.yanxiufei.cn/Article/details/gtavrmwhyu.html

[T14] Kotlin：循环
来源：http://dali.havefunace.top/Article/details/gtndpuwvoz.html

for (i in 1..10) println(i)
来源：http://dali.dianchejie.cn/Article/details/gtwekhdcnd.html

[T15] Kotlin：接口
来源：http://dali.pengpengdd.cyou/Article/details/gtugihnkjw.html

interface Shape { fun area(): Double }
来源：http://dali.chenlongwang.top/Article/details/gtioveohkt.html

[T16] Swift：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtpvzuytye.html

print("Hello")
来源：http://dali.guannengcc.top/Article/details/gtifszrhtd.html

[T17] Swift：变量与常量
来源：http://dali.chenzaomai.com/Article/details/gtxeyzmver.html

var a = 1;  let b = 2
来源：http://dali.daxiang520.top/Article/details/gtsginchqc.html

[T18] Swift：字符串插值
来源：http://dali.jqgufenzy.top/Article/details/gttkliitcg.html

"值: \(b)"
来源：http://dali.xinyue.icu/Article/details/gtwmknendf.html

[T19] Swift：可选绑定
来源：http://dali.hammf.cn/Article/details/gtsxrxfmaz.html

if let n = opt { print(n) }
来源：http://dali.sysykeji.top/Article/details/gtfpxbxdig.html

[T20] Swift：数组操作
来源：http://dali.hnqzz.top/Article/details/gtpselirit.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhixingplan.top/Article/details/gtijorxmkc.html

[T21] Swift：遍历
来源：http://dali.yanxiufei.cn/Article/details/gttridwqud.html

for x in a { print(x) }
来源：http://dali.zhijiandao.cn/Article/details/gtnaegxemx.html

[T22] Swift：字典
来源：http://dali.yonumen.top/Article/details/gtbpnzhqht.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xuetiantiany.cn/Article/details/gtnekcigyd.html

[T23] Swift：函数
来源：http://dali.hongshengwenyu.top/Article/details/gthhvbxryk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xylfe.cn/Article/details/gtmmajnakw.html

[T24] Swift：闭包
来源：http://dali.yj20258888.top/Article/details/gtligcfhiq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.svipenyu.cn/Article/details/gtrnududgp.html

[T25] Swift：结构体
来源：http://dali.meibo888.top/Article/details/gtwarzgolt.html

struct P { var x: Int }
来源：http://dali.chenzaomai.com/Article/details/gtuvebkuaq.html

[T26] Swift：类与重写
来源：http://dali.cashguo.top/Article/details/gtkikqskhh.html

class A: Base { override func f() {} }
来源：http://dali.c1oappe.top/Article/details/gtosbarzff.html

[T27] Swift：错误处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxyhqhlya.html

do { try f() } catch { print(error) }
来源：http://dali.daxiang520.top/Article/details/gtynwolqgj.html

[T28] Swift：枚举
来源：http://dali.cdnleiting.top/Article/details/gtxpbzeyps.html

enum Color { case red, green }
来源：http://dali.kuanghao11.cn/Article/details/gtvjruudqq.html

[T29] Swift：guard 提前返回
来源：http://dali.ydzc1.top/Article/details/gtseyzfjfd.html

guard let x = opt else { return }
来源：http://dali.zhongyouzk.top/Article/details/gtdhcaxntw.html

[T30] Swift：协议
来源：http://dali.hnqzz.top/Article/details/gtybeplcfo.html

protocol Shape { func area() -> Double }
来源：http://dali.yueranfly.top/Article/details/gtruehiuau.html

[T31] Lua：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtomldeslj.html

print("Hello")
来源：http://dali.jlsjyb.cn/Article/details/gtiifewgra.html

[T32] Lua：局部变量
来源：http://dali.daria6918.cn/Article/details/gtvulwsrbz.html

local a = 1
来源：http://dali.hnqzz.top/Article/details/gtsdlxjwxn.html

[T33] Lua：表（数组）
来源：http://dali.yueranfly.top/Article/details/gtczanpjpy.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.quarkkingdee.top/Article/details/gtcsxqnwsd.html

[T34] Lua：遍历表
来源：http://dali.redwolf501.top/Article/details/gtsfgtbtoo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yanxiufei.cn/Article/details/gtuspqbeaw.html

[T35] Lua：字典表
来源：http://dali.hnxiangtu.top/Article/details/gtlrysgzcm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhiwuduotai.top/Article/details/gtugksriqn.html

[T36] Lua：函数
来源：http://dali.zdqjudy.top/Article/details/gtqooygsfv.html

function add(a, b) return a + b end
来源：http://dali.guowangkeji.top/Article/details/gteozcnnnz.html

[T37] Lua：字符串拼接
来源：http://dali.gogol.net.cn/Article/details/gtxnibbkvw.html

"a" .. "b"
来源：http://dali.wangshuangyany.cn/Article/details/gtmduoejqv.html

[T38] Lua：条件
来源：http://dali.vqdsnc.cn/Article/details/gttvofhnfm.html

if x > 0 then print("正") end
来源：http://dali.snrcjt.cn/Article/details/gtcgeobyrw.html

[T39] Lua：模式匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtydjgxngz.html

string.find(s, "%d+")
来源：http://dali.yuanzhike.top/Article/details/gtkzopwebh.html

[T40] Lua：元表
来源：http://dali.yanxiufei.cn/Article/details/gtgclnihgg.html

setmetatable({}, { __index = base })
来源：http://dali.aizwys.cn/Article/details/gtfookyauc.html

[T41] Perl：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtzyluiklk.html

print "Hello\n";
来源：http://dali.yuxming.cn/Article/details/gtcddgiqpq.html

[T42] Perl：变量类型
来源：http://dali.yvedp.cn/Article/details/gtnuxcqhms.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sxryk.cn/Article/details/gtlusvyjmh.html

[T43] Perl：字符串插值
来源：http://dali.zhiwuduotai.top/Article/details/gtcfhjoxwl.html

"值: $a"
来源：http://dali.aibaodan.cn/Article/details/gtfiemrhxm.html

[T44] Perl：条件
来源：http://dali.andypj.xyz/Article/details/gtknsjtkch.html

if ($a > 0) { print "正"; }
来源：http://dali.yongpay.top/Article/details/gtizodmwvb.html

[T45] Perl：数组遍历
来源：http://dali.guowangkeji.top/Article/details/gtnzttbrhz.html

for my $x (@arr) { print $x; }
来源：http://dali.sweek.top/Article/details/gtbjngdowt.html

[T46] Perl：哈希操作
来源：http://dali.0kj1m.cn/Article/details/gtighgrvls.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.guowangkeji.top/Article/details/gtxiqnobla.html

[T47] Perl：正则捕获
来源：http://dali.gaohongyu789.top/Article/details/gtvauqzmxu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.snrcjt.cn/Article/details/gtgzvffgzd.html

[T48] Perl：正则替换
来源：http://dali.birdmap.top/Article/details/gtssxuoisy.html

$s =~ s/old/new/g;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqjczbybi.html

[T49] Perl：函数
来源：http://dali.gzhubu.top/Article/details/gteuncafyt.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yuxming.cn/Article/details/gtmomsjcir.html

[T50] Perl：逐行读文件
来源：http://dali.hongshengwenyu.top/Article/details/gtbwvstpde.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.svipenyu.cn/Article/details/gtteotsyay.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.0kj1m.cn/Article/details/gtwoqbpxed.html

[T51] Scala：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtiyvcdklf.html

println("Hello")
来源：http://dali.zdqjudy.top/Article/details/gtizxkergr.html

[T52] Scala：变量
来源：http://dali.snrcjt.cn/Article/details/gtytjfzldv.html

val a = 1;  var b = 2
来源：http://dali.gotoacloud.top/Article/details/gtnaqpbxrn.html

[T53] Scala：字符串插值
来源：http://dali.jiagoushi.top/Article/details/gtmewmhzmv.html

s"值: $b"
来源：http://dali.meibo888.top/Article/details/gtsrmhbqeo.html

[T54] Scala：集合映射
来源：http://dali.shuidangran.top/Article/details/gtydenvrhu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.guannengcc.top/Article/details/gthdezetzn.html

[T55] Scala：集合过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gtcdgkfwna.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtdffievtc.html

[T56] Scala：样例类
来源：http://dali.andypj.xyz/Article/details/gtunokrmea.html

case class User(name: String, age: Int)
来源：http://dali.yangfankeji.com/Article/details/gtmtgvczee.html

[T57] Scala：模式匹配
来源：http://dali.birdmap.top/Article/details/gtqtkfnfql.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.smart0.xyz/Article/details/gtvcxgzdjn.html

[T58] Scala：函数定义
来源：http://dali.zhixingplan.top/Article/details/gtzqjbkcxt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.tian-w.cn/Article/details/gtjsqlzflt.html

[T59] Scala：循环
来源：http://dali.hywenlv.cn/Article/details/gtrlceadqn.html

for (i <- 1 to 10) println(i)
来源：http://dali.nwbrower.top/Article/details/gtgfzqgsfr.html

[T60] Scala：折叠
来源：http://dali.quarkkingdee.top/Article/details/gtjzxmbmju.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.nwbrower.top/Article/details/gtkjzyriws.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtjsjfjsch.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.cucudq.cn/Article/details/gtbloocrhe.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtighuyllw.html

[U01] Py：创建虚拟环境
来源：http://dali.hongshengwenyu.top/Article/details/gtzrdabrvf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.cashguo.top/Article/details/gtnxtcnudh.html

[U02] Py：导出 / 安装依赖
来源：http://dali.sxryk.cn/Article/details/gtkigajtzy.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.mhx1999.top/Article/details/gtivxzuvvd.html

[U03] Py：加载 .env 配置
来源：http://dali.sysykeji.top/Article/details/gtbcugfgfe.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvzowfxpi.html

[U04] Py：变量调试打印
来源：http://dali.shangyingyoupin.top/Article/details/gtmsqoghxu.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.vqdsnc.cn/Article/details/gtmcehuqcp.html

[U05] Py：列表去重且保序
来源：http://dali.316326.xyz/Article/details/gtektgehiu.html

list(dict.fromkeys(arr))
来源：http://dali.gaohongyu789.top/Article/details/gtcbjnbizs.html

[U06] Py：合并两个字典
来源：http://dali.hongshengwenyu.top/Article/details/gtlrmcapcf.html

{**a, **b}
来源：http://dali.chenjidiqi.icu/Article/details/gteafyetld.html

[U07] Py：反转字典键值
来源：http://dali.cqqwz.cn/Article/details/gtvbzlsppo.html

{v: k for k, v in d.items()}
来源：http://dali.xinyue.icu/Article/details/gtodpnhtzc.html

[U08] Py：展平二维列表
来源：http://dali.jinqigfzy.top/Article/details/gttesfclfi.html

[y for x in nested for y in x]
来源：http://dali.jiagoushi.top/Article/details/gtyddzgaod.html


<!-- 参考信息 -->