代发 wailian999

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jinqigfzy.top/Article/details/gtkknirerx.html

[R66] 定时任务
来源：http://dali.ivvv.top/Article/details/gtbvojreae.html

crontab -e;  crontab -l
来源：http://dali.jianghu66.top/Article/details/gtparnqjdv.html

[R67] 生成随机十六进制串
来源：http://dali.feifeiyinyue.top/Article/details/gtwugzepqn.html

openssl rand -hex 16
来源：http://dali.sweek.top/Article/details/gtfzfijokj.html

[R68] 计算文件校验值
来源：http://dali.zhoulong.xyz/Article/details/gtgeujeehb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.mhx1999.top/Article/details/gtqupsjlnr.html

[R69] 生成随机密码
来源：http://dali.zdqjudy.top/Article/details/gtwfjhgefr.html

head -c 16 /dev/urandom | base64
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwmsdorny.html

[R70] 时间戳与互转
来源：http://dali.xuanzx.com/Article/details/gtpcjikoze.html

date +%s;  date -d @1700000000
来源：http://dali.xuanzx.com/Article/details/gtlwjzrxpx.html

[R71] 日期格式化
来源：http://dali.9152youxi.cn/Article/details/gtoxbjceqk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.birdmap.top/Article/details/gtmpbokuhf.html

[R72] 等待端口就绪
来源：http://dali.jinqigufen.top/Article/details/gtvcapppet.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hammf.cn/Article/details/gtpjlockpi.html

[R73] 分割大日志
来源：http://dali.xinyue.icu/Article/details/gtfouoskbv.html

split -l 1000 big.log part_
来源：http://dali.yongpay.top/Article/details/gtotlojqjo.html

[R74] 批量重命名
来源：http://dali.hnxiangtu.top/Article/details/gtjbwqxcnz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.guannengcc.top/Article/details/gtenokklnx.html

[R75] 导出环境变量
来源：http://dali.bjfxy.top/Article/details/gtpjusortu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tianlin.xyz/Article/details/gtpwnlxhbg.html

[R76] 使用临时文件
来源：http://dali.guowangkeji.top/Article/details/gtawsknxwk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yangfankeji.com/Article/details/gtwpbvfhiz.html

[R77] 读取用户输入
来源：http://dali.ppjwa.cn/Article/details/gtzjepcvad.html

read -rp "请输入: " ans
来源：http://dali.pycfn.com/Article/details/gtdpqndlxe.html

[R78] 交互式菜单
来源：http://dali.nanxinkj.top/Article/details/gtzflrgyxx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jqgfzy.top/Article/details/gtsvblpmyi.html

[R79] 解析命令行选项
来源：http://dali.jyoumei.cn/Article/details/gtdlppazkr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jianghu66.top/Article/details/gtsaccmlrg.html

[R80] 查看脚本执行耗时
来源：http://dali.sxryk.cn/Article/details/gtmrziylik.html

time ./run.sh
来源：http://dali.chenzaomai.com/Article/details/gtiawmdosk.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtkexgwamh.html

S. C / C++ 专题
来源：http://dali.feifeiyinyue.top/Article/details/gtshiijaou.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtzmnffcim.html

[S01] C：Hello World
来源：http://dali.aizwys.cn/Article/details/gtferylowv.html

#include <stdio.h>
来源：http://dali.smart0.xyz/Article/details/gtxxdgvpeq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhengqikj.top/Article/details/gtwlendpig.html

[S02] C：变量与格式化输出
来源：http://dali.bjfxy.top/Article/details/gtwhkmuwor.html

int a = 10; printf("%d\n", a);
来源：http://dali.yangfankeji.com/Article/details/gtsacuqwfh.html

[S03] C：读入整数
来源：http://dali.haohaochexian.top/Article/details/gtehmjigxl.html

int x; scanf("%d", &x);
来源：http://dali.guowangkeji.top/Article/details/gtppdmbjoc.html

[S04] C：字符串复制
来源：http://dali.ydzc1.top/Article/details/gtgbqbcbxj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.nwbrower.top/Article/details/gtxqycxfiw.html

[S05] C：字符串长度
来源：http://dali.xylfe.cn/Article/details/gtdcgreshr.html

strlen(s)
来源：http://dali.zhoulong.xyz/Article/details/gtvisknieo.html

[S06] C：字符串比较
来源：http://dali.sufxvd.cn/Article/details/gtutkrmwgr.html

strcmp(a, b) == 0
来源：http://dali.xylfe.cn/Article/details/gtbmcsniam.html

[S07] C：数组遍历求和
来源：http://dali.xziqi.cn/Article/details/gtfzkhulnu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hfpthk.cn/Article/details/gtmooumplk.html

[S08] C：动态内存分配与释放
来源：http://dali.guowangkeji.top/Article/details/gtfbhbzbzv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.tianlin.xyz/Article/details/gtmjhzrkde.html

[S09] C：结构体定义与初始化
来源：http://dali.mhx1999.top/Article/details/gtnaigpcxy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jianghu66.top/Article/details/gtizktfnwy.html

[S10] C：指针与解引用
来源：http://dali.hywenlv.cn/Article/details/gtaxlxqsqk.html

int *p = &a;  *p = 5;
来源：http://dali.zhoulong.xyz/Article/details/gtnmsrvhhu.html

[S11] C：逐行读文件
来源：http://dali.meibo888.top/Article/details/gtztmvqbfp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jqgfzy.top/Article/details/gteuojkgzh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.feifeiyinyue.top/Article/details/gtudwcgrxk.html

fclose(f);
来源：http://dali.hammf.cn/Article/details/gtctacaomi.html

[S12] C：写文件
来源：http://dali.ivvv.top/Article/details/gtzaoozues.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj202588.top/Article/details/gtidmyvcjf.html

[S13] C：宏定义
来源：http://dali.mhx1999.top/Article/details/gtxwcehrqi.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhixingplan.top/Article/details/gtisgygblc.html

[S14] C：枚举
来源：http://dali.jinghuilouyu.cn/Article/details/gtsxkggyqp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jqgfzy.top/Article/details/gtxlgqcqrk.html

[S15] C：类型转换
来源：http://dali.sxryk.cn/Article/details/gtnphqsdut.html

(double) a / b
来源：http://dali.hongshengwenyu.top/Article/details/gtafbpcxnl.html

[S16] C：位操作置位
来源：http://dali.shangyingyoupin.top/Article/details/gtuqvsxoxx.html

x |= (1 << 3);
来源：http://dali.mhx1999.top/Article/details/gtlkkjrcdq.html

[S17] C：安全拼接字符串
来源：http://dali.gaohongyu789.top/Article/details/gtyivzflhc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.tanke756.top/Article/details/gtxvpcgind.html

[S18] C：命令行参数
来源：http://dali.jyoumei.cn/Article/details/gtivzynkli.html

int main(int argc, char **argv)
来源：http://dali.dianchejie.cn/Article/details/gtairfcyho.html

[S19] C：快速排序
来源：http://dali.redwolf501.top/Article/details/gtoqstnjwh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.kuanghao11.cn/Article/details/gtbfqmagrf.html

[S20] C：二分查找
来源：http://dali.meibo888.top/Article/details/gttllclsxx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.feifeiyinyue.top/Article/details/gtjavojpro.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gtzkjfewjx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.mhx1999.top/Article/details/gtioocnccd.html

[S22] C：字符串转数字
来源：http://dali.zhiwuduotai.top/Article/details/gtfyolfftp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhiwuduotai.top/Article/details/gttqmirski.html

[S23] C：随机数
来源：http://dali.xziqi.cn/Article/details/gtzmclceiu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jyoumei.cn/Article/details/gtqiaajkjx.html

[S24] C：获取本地时间
来源：http://dali.dashuyun.cn/Article/details/gtyqjuqdhe.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ybcxt.top/Article/details/gtrveuiwke.html

[S25] C：内存拷贝
来源：http://dali.smart0.xyz/Article/details/gtsebmpjss.html

memcpy(dst, src, n);
来源：http://dali.yongpay.top/Article/details/gttmaxoove.html

[S26] C：内存清零
来源：http://dali.fzhhl.top/Article/details/gtahjlfuwm.html

memset(a, 0, sizeof a);
来源：http://dali.svipenyu.cn/Article/details/gtfinnklxp.html

[S27] C：定义常量
来源：http://dali.pycfn.com/Article/details/gtvalydqyc.html

const double PI = 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gtcczozplr.html

[S28] C：静态变量
来源：http://dali.yj20258.top/Article/details/gtrrtdkvtz.html

static int counter = 0;
来源：http://dali.yanxiufei.cn/Article/details/gtmsxcnnbs.html

[S29] C：变参函数
来源：http://dali.zycfv.cn/Article/details/gtjketvngo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqtihhgvm.html

[S30] C：头文件保护
来源：http://dali.guowangkeji.top/Article/details/gtvvpqqpix.html

#ifndef X_H
来源：http://dali.ppjwa.cn/Article/details/gtviflmhxi.html

#define X_H
来源：http://dali.gogol.net.cn/Article/details/gtwpequowm.html

#endif
来源：http://dali.xuetiantiany.cn/Article/details/gtqxvnotxs.html

[S31] C++：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtetocoviw.html

#include <iostream>
来源：http://dali.wangshuangyany.cn/Article/details/gttfypinll.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.quarkkingdee.top/Article/details/gtcascymsz.html

[S32] C++：字符串
来源：http://dali.birdmap.top/Article/details/gtormtdoze.html

std::string s = "hi";  s += "!";
来源：http://dali.zhoulong.xyz/Article/details/gtrppugsxq.html

[S33] C++：vector 增删
来源：http://dali.tanke756.top/Article/details/gtoveckwqh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ppjwa.cn/Article/details/gtijiryhrn.html

[S34] C++：遍历 vector
来源：http://dali.pycfn.com/Article/details/gthifjqhgx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sysykeji.top/Article/details/gtathlptfs.html

[S35] C++：map
来源：http://dali.gzhubu.top/Article/details/gtbmxbodre.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nwbrower.top/Article/details/gtvkcdvhao.html

[S36] C++：unordered_map
来源：http://dali.c1oappe.top/Article/details/gtysywomnn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shuidangran.top/Article/details/gtefmexfja.html

[S37] C++：set
来源：http://dali.xinyue.icu/Article/details/gtayhmuqtc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sweek.top/Article/details/gtxtzjcgqg.html

[S38] C++：排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbwguhqvz.html

std::sort(v.begin(), v.end());
来源：http://dali.xziqi.cn/Article/details/gtjyyygaww.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gtawdldfbo.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xinyue.icu/Article/details/gtuojlisum.html

[S40] C++：查找元素
来源：http://dali.kuanghao11.cn/Article/details/gtcwnfjqfx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.chenlongwang.top/Article/details/gtioccsnif.html

[S41] C++：类与构造函数
来源：http://dali.sysykeji.top/Article/details/gtaepkaecy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.daxiang520.top/Article/details/gtifhdtvlt.html

[S42] C++：继承与虚函数
来源：http://dali.hywenlv.cn/Article/details/gtzbedywsw.html

class B : public Base { public: void f() override {} };
来源：http://dali.chenzaomai.com/Article/details/gtzlreofzn.html

[S43] C++：智能指针
来源：http://dali.sweek.top/Article/details/gtaddnftto.html

auto p = std::make_unique<int>(5);
来源：http://dali.quarkkingdee.top/Article/details/gthejexato.html

[S44] C++：引用传参
来源：http://dali.xuanzx.com/Article/details/gtzxivpsnz.html

void inc(int &x) { ++x; }
来源：http://dali.svipenyu.cn/Article/details/gtwszwmyly.html

[S45] C++：lambda
来源：http://dali.havefunace.top/Article/details/gtxymaazcp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yj20258.top/Article/details/gtonocghho.html

[S46] C++：函数模板
来源：http://dali.meibo888.top/Article/details/gtrgnsobcu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ivvv.top/Article/details/gtbhvwmcfd.html

[S47] C++：结构化绑定遍历
来源：http://dali.meibo888.top/Article/details/gtztospnkj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shuidangran.top/Article/details/gtqfarhdsc.html

[S48] C++：逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gtzfbunizy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.guannengcc.top/Article/details/gtplrjkuhg.html

while (std::getline(in, line)) { }
来源：http://dali.zhongyouzk.top/Article/details/gtdvdjbvlm.html

[S49] C++：写文件
来源：http://dali.feifeiyinyue.top/Article/details/gthjwlzzmn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinqigfzy.top/Article/details/gtwtqsygbm.html

[S50] C++：格式化数字
来源：http://dali.gaohongyu789.top/Article/details/gtuwicrisc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gtcnzyhjlt.html

[S51] C++：显式类型转换
来源：http://dali.nwbrower.top/Article/details/gtmzkpfxkm.html

static_cast<double>(a) / b
来源：http://dali.aibaodan.cn/Article/details/gtvxxyfgik.html

[S52] C++：const 与 noexcept
来源：http://dali.jinqigfzy.top/Article/details/gtxnpuhioh.html

int size() const noexcept { return n_; }
来源：http://dali.xuanzx.com/Article/details/gtoqznquem.html

[S53] C++：移动语义
来源：http://dali.havefunace.top/Article/details/gtyxtaqhft.html

std::vector<int> w = std::move(v);
来源：http://dali.ydzc1.top/Article/details/gtojnvbpll.html

[S54] C++：异常处理
来源：http://dali.daxiang520.top/Article/details/gtwcddzcxi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.guannengcc.top/Article/details/gtljuqyrxv.html

[S55] C++：结构化绑定
来源：http://dali.jianghu66.top/Article/details/gtwzgjhary.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.aibaodan.cn/Article/details/gtqtqoovhm.html

[S56] C++：optional
来源：http://dali.bjfxy.top/Article/details/gtcnfaidkl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hnqzz.top/Article/details/gtkpvtiqto.html

[S57] C++：编译期常量
来源：http://dali.havefunace.top/Article/details/gteggcnnju.html

constexpr int N = 10;
来源：http://dali.zhongyouzk.top/Article/details/gtunlmrgjj.html

[S58] C++：命名空间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjsoixwsi.html

namespace ns { int f() { return 1; } }
来源：http://dali.shuidangran.top/Article/details/gtjjtrffmm.html

[S59] C++：静态断言
来源：http://dali.gaohongyu789.top/Article/details/gtipfabzfh.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hnqzz.top/Article/details/gtgtaumlyz.html

[S60] C++：遍历并删除元素
来源：http://dali.mhx1999.top/Article/details/gtbssfkadj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.andypj.xyz/Article/details/gttnxubnxs.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtsyyvqjji.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gogol.net.cn/Article/details/gtgixvlnqj.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtuhtdpuyk.html

[T01] Kotlin：Hello World
来源：http://dali.yuxming.cn/Article/details/gtvylyfcep.html

println("Hello")
来源：http://dali.zhiwuduotai.top/Article/details/gtcnnwfyyr.html

[T02] Kotlin：变量
来源：http://dali.zhijiandao.cn/Article/details/gtgrbvxvfd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.quarkkingdee.top/Article/details/gtxwsxggme.html

[T03] Kotlin：字符串模板
来源：http://dali.jinqigfzy.top/Article/details/gtuzjuusug.html

"值: $b"
来源：http://dali.chenzaomai.com/Article/details/gtlfyjbmhc.html

[T04] Kotlin：空安全
来源：http://dali.nanxinkj.top/Article/details/gtdccxgefm.html

val n: String? = null;  n?.length
来源：http://dali.yangfankeji.com/Article/details/gtdbfkghfj.html

[T05] Kotlin：when 表达式
来源：http://dali.hongshengwenyu.top/Article/details/gtfuvzvifk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.birdmap.top/Article/details/gtcyzbdqhk.html

[T06] Kotlin：集合映射
来源：http://dali.shzxlz.cn/Article/details/gtzibyaltg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.mhx1999.top/Article/details/gtiohqilot.html

[T07] Kotlin：集合过滤
来源：http://dali.xylfe.cn/Article/details/gtrvzhyyma.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.0kj1m.cn/Article/details/gtwfxpaipf.html

[T08] Kotlin：数据类
来源：http://dali.gogol.net.cn/Article/details/gtaeyogaei.html

data class User(val name: String, val age: Int)
来源：http://dali.aibaodan.cn/Article/details/gtihfkuahg.html

[T09] Kotlin：扩展函数
来源：http://dali.zhiwuduotai.top/Article/details/gtpvhwjkhn.html

fun String.exclaim() = this + "!"
来源：http://dali.pengpengdd.cyou/Article/details/gtlthcpoxe.html

[T10] Kotlin：默认参数
来源：http://dali.hfpthk.cn/Article/details/gtomanzhfc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.chenlongwang.top/Article/details/gtdcyqchmv.html

[T11] Kotlin：协程
来源：http://dali.quarkkingdee.top/Article/details/gtlqenbeel.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cqqwz.cn/Article/details/gtmvgnnojk.html

[T12] Kotlin：解构声明
来源：http://dali.sweek.top/Article/details/gtqnkbddyp.html

val (a, b) = Pair(1, 2)
来源：http://dali.daxiang520.top/Article/details/gthsupgjhz.html

[T13] Kotlin：只读 Map
来源：http://dali.hammf.cn/Article/details/gtufhbgwyt.html

val m = mapOf("a" to 1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtobuuivhc.html

[T14] Kotlin：循环
来源：http://dali.cucudq.cn/Article/details/gtpcvhoycb.html

for (i in 1..10) println(i)
来源：http://dali.jianghu66.top/Article/details/gtrrxdybpw.html

[T15] Kotlin：接口
来源：http://dali.nanxuanxn.top/Article/details/gtqcpfarkl.html

interface Shape { fun area(): Double }
来源：http://dali.chenlongwang.top/Article/details/gtubiaeasz.html

[T16] Swift：Hello World
来源：http://dali.cucudq.cn/Article/details/gtigjadeaz.html

print("Hello")
来源：http://dali.ybcxt.top/Article/details/gtvrtfdkeq.html

[T17] Swift：变量与常量
来源：http://dali.chenjidiqi.icu/Article/details/gtmnlubskh.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gtfpbywssm.html

[T18] Swift：字符串插值
来源：http://dali.xinyue.icu/Article/details/gteqdtqmay.html

"值: \(b)"
来源：http://dali.smart0.xyz/Article/details/gtxtrizxxe.html

[T19] Swift：可选绑定
来源：http://dali.chenzaomai.com/Article/details/gtavsxygvu.html

if let n = opt { print(n) }
来源：http://dali.feifeiyinyue.top/Article/details/gtusbyqmpo.html

[T20] Swift：数组操作
来源：http://dali.feifeiyinyue.top/Article/details/gtrqjamjbb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xuetiantiany.cn/Article/details/gtalikybzu.html

[T21] Swift：遍历
来源：http://dali.pycfn.com/Article/details/gtydcigifr.html

for x in a { print(x) }
来源：http://dali.yongpay.top/Article/details/gtortaedjg.html

[T22] Swift：字典
来源：http://dali.aibaodan.cn/Article/details/gtubvknhmc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhengqikj.top/Article/details/gtnmeixzep.html

[T23] Swift：函数
来源：http://dali.aibaodan.cn/Article/details/gtdfvggylf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.birdmap.top/Article/details/gtcrzlclii.html

[T24] Swift：闭包
来源：http://dali.kuanghao11.cn/Article/details/gtkqfonuzp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jqgufenzy.top/Article/details/gtpufwgquz.html

[T25] Swift：结构体
来源：http://dali.meibo888.top/Article/details/gtzexlvbqh.html

struct P { var x: Int }
来源：http://dali.yj202588.top/Article/details/gtvmowqhne.html

[T26] Swift：类与重写
来源：http://dali.dianchejie.cn/Article/details/gtvlqihsmr.html

class A: Base { override func f() {} }
来源：http://dali.cdnleiting.top/Article/details/gtrzytbccm.html

[T27] Swift：错误处理
来源：http://dali.yanxiufei.cn/Article/details/gtqsqhokia.html

do { try f() } catch { print(error) }
来源：http://dali.yvedp.cn/Article/details/gtlntsktco.html

[T28] Swift：枚举
来源：http://dali.smart0.xyz/Article/details/gtsqomnthh.html

enum Color { case red, green }
来源：http://dali.bjfxy.top/Article/details/gtpnlixubb.html

[T29] Swift：guard 提前返回
来源：http://dali.yonumen.top/Article/details/gtrhlvkkor.html

guard let x = opt else { return }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcemwavde.html

[T30] Swift：协议
来源：http://dali.sysykeji.top/Article/details/gtdeyuzfgc.html

protocol Shape { func area() -> Double }
来源：http://dali.hammf.cn/Article/details/gtuyelahhi.html

[T31] Lua：Hello World
来源：http://dali.nanxinkj.top/Article/details/gtkyyafsxn.html

print("Hello")
来源：http://dali.yj20258.top/Article/details/gtzzblmbgn.html

[T32] Lua：局部变量
来源：http://dali.iojbl.cn/Article/details/gtokybfjkg.html

local a = 1
来源：http://dali.andypj.xyz/Article/details/gtkcqhsigv.html

[T33] Lua：表（数组）
来源：http://dali.sysykeji.top/Article/details/gtfdplxfek.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.sysykeji.top/Article/details/gtivllwyrm.html

[T34] Lua：遍历表
来源：http://dali.ydzc1.top/Article/details/gtfsiteuly.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.sufxvd.cn/Article/details/gteygwgsfo.html

[T35] Lua：字典表
来源：http://dali.aibaodan.cn/Article/details/gtifbrrzrk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.tanke756.top/Article/details/gtrxklksdg.html

[T36] Lua：函数
来源：http://dali.xylfe.cn/Article/details/gtqkabdoyq.html

function add(a, b) return a + b end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyinispoh.html

[T37] Lua：字符串拼接
来源：http://dali.yonumen.top/Article/details/gtyiiqrokl.html

"a" .. "b"
来源：http://dali.birdmap.top/Article/details/gtjafoctsr.html

[T38] Lua：条件
来源：http://dali.sweek.top/Article/details/gtumppaovg.html

if x > 0 then print("正") end
来源：http://dali.chenlongwang.top/Article/details/gtenahcnxk.html

[T39] Lua：模式匹配
来源：http://dali.jqgufenzy.top/Article/details/gtjfkvnjvy.html

string.find(s, "%d+")
来源：http://dali.shuidangran.top/Article/details/gtuaicstiz.html

[T40] Lua：元表
来源：http://dali.shuidangran.top/Article/details/gtxasponfu.html

setmetatable({}, { __index = base })
来源：http://dali.zhiwuduotai.top/Article/details/gthxqaiwqg.html

[T41] Perl：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtgcoivjnh.html

print "Hello\n";
来源：http://dali.zhoulong.xyz/Article/details/gtgyjcdwmr.html

[T42] Perl：变量类型
来源：http://dali.shuidangran.top/Article/details/gtaoktqurl.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.shangyingyoupin.top/Article/details/gtcewpmhmf.html

[T43] Perl：字符串插值
来源：http://dali.cucudq.cn/Article/details/gtyxyjkjab.html

"值: $a"
来源：http://dali.jqgufenzy.top/Article/details/gtmrlmkqqf.html

[T44] Perl：条件
来源：http://dali.jiagoushi.top/Article/details/gtzxsuvhpw.html

if ($a > 0) { print "正"; }
来源：http://dali.gogol.net.cn/Article/details/gtmacukhjp.html

[T45] Perl：数组遍历
来源：http://dali.xylfe.cn/Article/details/gtlaoycfrb.html

for my $x (@arr) { print $x; }
来源：http://dali.ybcxt.top/Article/details/gtmnssoujq.html

[T46] Perl：哈希操作
来源：http://dali.fzhhl.top/Article/details/gtmlyjghpr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xinyue.icu/Article/details/gticixluze.html

[T47] Perl：正则捕获
来源：http://dali.chenlongwang.top/Article/details/gttluregoh.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yvedp.cn/Article/details/gtomkcngzj.html

[T48] Perl：正则替换
来源：http://dali.zhoulong.xyz/Article/details/gtefbdserb.html

$s =~ s/old/new/g;
来源：http://dali.wangshuangyany.cn/Article/details/gtpzqugajv.html

[T49] Perl：函数
来源：http://dali.kuanghao11.cn/Article/details/gtctxlsvzh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.redwolf501.top/Article/details/gthvfazxvj.html

[T50] Perl：逐行读文件
来源：http://dali.vqdsnc.cn/Article/details/gtgyrmgdvp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hysaishi.cn/Article/details/gtvwytjcio.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.meibo888.top/Article/details/gtwpuubdkh.html

[T51] Scala：Hello World
来源：http://dali.smart0.xyz/Article/details/gtybjxoget.html

println("Hello")
来源：http://dali.0kj1m.cn/Article/details/gtecrrgwln.html

[T52] Scala：变量
来源：http://dali.guannengcc.top/Article/details/gtpvxjeupc.html

val a = 1;  var b = 2
来源：http://dali.gzhubu.top/Article/details/gtorzhpmkm.html

[T53] Scala：字符串插值
来源：http://dali.hnxiangtu.top/Article/details/gtqvphtpol.html

s"值: $b"
来源：http://dali.ybcxt.top/Article/details/gtsuxzhyfp.html

[T54] Scala：集合映射
来源：http://dali.sysykeji.top/Article/details/gtuneptpbk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jinqigufen.top/Article/details/gtgssmuyxi.html

[T55] Scala：集合过滤
来源：http://dali.yanxiufei.cn/Article/details/gtvptnkrko.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.birdmap.top/Article/details/gtdawxtugy.html

[T56] Scala：样例类
来源：http://dali.svipenyu.cn/Article/details/gttalrmbrn.html

case class User(name: String, age: Int)
来源：http://dali.wangdashe.top/Article/details/gtwrsqnlaj.html

[T57] Scala：模式匹配
来源：http://dali.hysaishi.cn/Article/details/gtaoajtemx.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yuxming.cn/Article/details/gtdzdwsewc.html

[T58] Scala：函数定义
来源：http://dali.pengpengdd.cyou/Article/details/gthrdrvicg.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.zdqjudy.top/Article/details/gtayluffdc.html

[T59] Scala：循环
来源：http://dali.sysykeji.top/Article/details/gtaxqlgwuo.html

for (i <- 1 to 10) println(i)
来源：http://dali.ydzc1.top/Article/details/gtdvkcwmmq.html

[T60] Scala：折叠
来源：http://dali.jyoumei.cn/Article/details/gtewphfrjt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ydzc1.top/Article/details/gtsjgqxyws.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtxcbamfff.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hnxiangtu.top/Article/details/gtjxufjeev.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtcbkcetkx.html

[U01] Py：创建虚拟环境
来源：http://dali.hongshengwenyu.top/Article/details/gtvozylyxg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.cheryme.top/Article/details/gteioibhwu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.kuanghao11.cn/Article/details/gtmlolbfwj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cheryme.top/Article/details/gtllfkydpy.html

[U03] Py：加载 .env 配置
来源：http://dali.cdnleiting.top/Article/details/gtgyoqlksn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.tian-w.cn/Article/details/gtjrvsnbwj.html

[U04] Py：变量调试打印
来源：http://dali.ehwqpu.com/Article/details/gtnbjergze.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.gzhubu.top/Article/details/gtjoylmriw.html

[U05] Py：列表去重且保序
来源：http://dali.hnqzz.top/Article/details/gthbgaplrg.html

list(dict.fromkeys(arr))
来源：http://dali.daria6918.cn/Article/details/gtbvektbjb.html

[U06] Py：合并两个字典
来源：http://dali.0kj1m.cn/Article/details/gtsipwsxur.html

{**a, **b}
来源：http://dali.yangfankeji.com/Article/details/gtdbiqqmvi.html


<!-- 参考信息 -->