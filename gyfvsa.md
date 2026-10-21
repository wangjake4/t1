代发 wailian999

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yangfankeji.com/Article/details/gtxauflryq.html

[R66] 定时任务
来源：http://dali.jyoumei.cn/Article/details/gtznckrtrr.html

crontab -e;  crontab -l
来源：http://dali.jqgfzy.top/Article/details/gtulxrjudu.html

[R67] 生成随机十六进制串
来源：http://dali.tianlin.xyz/Article/details/gtakgmozkk.html

openssl rand -hex 16
来源：http://dali.hywenlv.cn/Article/details/gtupaptymc.html

[R68] 计算文件校验值
来源：http://dali.ivvv.top/Article/details/gttkithxfn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sufxvd.cn/Article/details/gtxtticdrk.html

[R69] 生成随机密码
来源：http://dali.hywenlv.cn/Article/details/gtlvgtkwgn.html

head -c 16 /dev/urandom | base64
来源：http://dali.yueranfly.top/Article/details/gtuyynrwvi.html

[R70] 时间戳与互转
来源：http://dali.0kj1m.cn/Article/details/gtiujhuiea.html

date +%s;  date -d @1700000000
来源：http://dali.gzhubu.top/Article/details/gtyzfgaswa.html

[R71] 日期格式化
来源：http://dali.xuanzx.com/Article/details/gtmmbqggeo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.dashuyun.cn/Article/details/gtbzzlpzhg.html

[R72] 等待端口就绪
来源：http://dali.jqgufenzy.top/Article/details/gtauphejlb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zycfv.cn/Article/details/gtagnyjodg.html

[R73] 分割大日志
来源：http://dali.aizwys.cn/Article/details/gtzfxlhwob.html

split -l 1000 big.log part_
来源：http://dali.jlsjyb.cn/Article/details/gttyojnjvb.html

[R74] 批量重命名
来源：http://dali.xinyue.icu/Article/details/gtgbauaaqn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cheryme.top/Article/details/gtkmbjaryu.html

[R75] 导出环境变量
来源：http://dali.gogol.net.cn/Article/details/gtbntuarma.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.svipenyu.cn/Article/details/gttbfwurof.html

[R76] 使用临时文件
来源：http://dali.meibo888.top/Article/details/gtrndpumao.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj202588.top/Article/details/gtjwuvjofz.html

[R77] 读取用户输入
来源：http://dali.xziqi.cn/Article/details/gtamzbwqoz.html

read -rp "请输入: " ans
来源：http://dali.shanyushiyangtech.top/Article/details/gtcmtzxsyf.html

[R78] 交互式菜单
来源：http://dali.gzhubu.top/Article/details/gtlegmlelw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yuanzhike.top/Article/details/gthdpmjaui.html

[R79] 解析命令行选项
来源：http://dali.dashuyun.cn/Article/details/gthdkarrpa.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.smart0.xyz/Article/details/gtpfepqoue.html

[R80] 查看脚本执行耗时
来源：http://dali.zhengqikj.top/Article/details/gtvvapyljs.html

time ./run.sh
来源：http://dali.jyoumei.cn/Article/details/gtrfzbdoex.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtjitloyhx.html

S. C / C++ 专题
来源：http://dali.zhixingplan.top/Article/details/gtwckjkpfv.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtljxlcozu.html

[S01] C：Hello World
来源：http://dali.aizwys.cn/Article/details/gtgoszabra.html

#include <stdio.h>
来源：http://dali.quarkkingdee.top/Article/details/gtdyjxqrye.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cucudq.cn/Article/details/gtfotjflaw.html

[S02] C：变量与格式化输出
来源：http://dali.zhoulong.xyz/Article/details/gtnaclbspu.html

int a = 10; printf("%d\n", a);
来源：http://dali.shanyushiyangkeji.top/Article/details/gteojgzphl.html

[S03] C：读入整数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkqzhlfwq.html

int x; scanf("%d", &x);
来源：http://dali.gzhubu.top/Article/details/gtflapejzr.html

[S04] C：字符串复制
来源：http://dali.chenlongwang.top/Article/details/gtahumcyfs.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.snrcjt.cn/Article/details/gtmpkdvhwv.html

[S05] C：字符串长度
来源：http://dali.jqgufenzy.top/Article/details/gtsssacukf.html

strlen(s)
来源：http://dali.pycfn.com/Article/details/gtiaxzmfso.html

[S06] C：字符串比较
来源：http://dali.nanxuanxn.top/Article/details/gtyuawuhhp.html

strcmp(a, b) == 0
来源：http://dali.sysykeji.top/Article/details/gtzewulzcy.html

[S07] C：数组遍历求和
来源：http://dali.yangfankeji.com/Article/details/gttyqocqum.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrswutctx.html

[S08] C：动态内存分配与释放
来源：http://dali.yvedp.cn/Article/details/gtwflbmhxe.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shanyushiyangtech.top/Article/details/gtknclrbgq.html

[S09] C：结构体定义与初始化
来源：http://dali.dianchejie.cn/Article/details/gtqingopcc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jyoumei.cn/Article/details/gtphunsnmv.html

[S10] C：指针与解引用
来源：http://dali.gzhubu.top/Article/details/gtztqodpis.html

int *p = &a;  *p = 5;
来源：http://dali.cqqwz.cn/Article/details/gtztqnkxzn.html

[S11] C：逐行读文件
来源：http://dali.sweek.top/Article/details/gtfsgjixhh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.fzhhl.top/Article/details/gtqbrrcoxk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtylhwvlgy.html

fclose(f);
来源：http://dali.yangfankeji.com/Article/details/gtvoomselz.html

[S12] C：写文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtldqdhtaw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gogol.net.cn/Article/details/gtnlmoehtz.html

[S13] C：宏定义
来源：http://dali.cqqwz.cn/Article/details/gtqerporai.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhiwuduotai.top/Article/details/gtkbmltxlt.html

[S14] C：枚举
来源：http://dali.gogol.net.cn/Article/details/gtjkzrcvkh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.shzxlz.cn/Article/details/gtvslivmzm.html

[S15] C：类型转换
来源：http://dali.sufxvd.cn/Article/details/gtuqztvpwz.html

(double) a / b
来源：http://dali.jinghuilouyu.cn/Article/details/gtxbmudgjq.html

[S16] C：位操作置位
来源：http://dali.zhixingplan.top/Article/details/gtuqtscjzp.html

x |= (1 << 3);
来源：http://dali.mhx1999.top/Article/details/gtvpugyhga.html

[S17] C：安全拼接字符串
来源：http://dali.xylfe.cn/Article/details/gtbycqqqmm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ehwqpu.com/Article/details/gtawnvdxxh.html

[S18] C：命令行参数
来源：http://dali.yonumen.top/Article/details/gttrnexxuj.html

int main(int argc, char **argv)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqitnwadt.html

[S19] C：快速排序
来源：http://dali.gotoacloud.top/Article/details/gtlhojfqcg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.dashuyun.cn/Article/details/gthtzcggmn.html

[S20] C：二分查找
来源：http://dali.cashguo.top/Article/details/gtpmpstkbl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gogol.net.cn/Article/details/gtoxtdmuzg.html

[S21] C：字符类别判断
来源：http://dali.hfpthk.cn/Article/details/gtlmtotgjw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.smart0.xyz/Article/details/gtumxzwqcy.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gtntlgcmuu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yuanzhike.top/Article/details/gtqwpvkslu.html

[S23] C：随机数
来源：http://dali.jiagoushi.top/Article/details/gtilacfrvh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shanyushiyangtech.top/Article/details/gtruvvfdhg.html

[S24] C：获取本地时间
来源：http://dali.yueranfly.top/Article/details/gtvopvnmzj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ehwqpu.com/Article/details/gtkdbadeph.html

[S25] C：内存拷贝
来源：http://dali.yuxming.cn/Article/details/gtkiucacqp.html

memcpy(dst, src, n);
来源：http://dali.cheryme.top/Article/details/gtscmealqq.html

[S26] C：内存清零
来源：http://dali.9152youxi.cn/Article/details/gtrbkxluys.html

memset(a, 0, sizeof a);
来源：http://dali.haohaochexian.top/Article/details/gtxklobixt.html

[S27] C：定义常量
来源：http://dali.nanxuanxn.top/Article/details/gtopyazvnk.html

const double PI = 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gtazptvpym.html

[S28] C：静态变量
来源：http://dali.ybcxt.top/Article/details/gttcbzzdtk.html

static int counter = 0;
来源：http://dali.yanxiufei.cn/Article/details/gtpkrxpbpe.html

[S29] C：变参函数
来源：http://dali.haohaochexian.top/Article/details/gtjbfzkclt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zdqjudy.top/Article/details/gtdedluzfe.html

[S30] C：头文件保护
来源：http://dali.yj20258888.top/Article/details/gtizpviscb.html

#ifndef X_H
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiswzahph.html

#define X_H
来源：http://dali.bjfxy.top/Article/details/gtatbdhbzp.html

#endif
来源：http://dali.yongpay.top/Article/details/gtbzbycipv.html

[S31] C++：Hello World
来源：http://dali.xziqi.cn/Article/details/gtkmbsyqni.html

#include <iostream>
来源：http://dali.wangshuangyany.cn/Article/details/gtqnrfcbnt.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.svipenyu.cn/Article/details/gtzmxmeoum.html

[S32] C++：字符串
来源：http://dali.cqqwz.cn/Article/details/gtynincdpp.html

std::string s = "hi";  s += "!";
来源：http://dali.hammf.cn/Article/details/gtzqmhmtmn.html

[S33] C++：vector 增删
来源：http://dali.zhoulong.xyz/Article/details/gtkeucuvsw.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.bjfxy.top/Article/details/gthenriyvh.html

[S34] C++：遍历 vector
来源：http://dali.zhixingplan.top/Article/details/gttbchwgqv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shangyingyoupin.top/Article/details/gttfvofvnw.html

[S35] C++：map
来源：http://dali.0kj1m.cn/Article/details/gtzfuhutww.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtjdlqvjgg.html

[S36] C++：unordered_map
来源：http://dali.birdmap.top/Article/details/gtzdfoxlbr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtligyvrvt.html

[S37] C++：set
来源：http://dali.ehwqpu.com/Article/details/gtlyixlkvs.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yangfankeji.com/Article/details/gtbvxkzogy.html

[S38] C++：排序
来源：http://dali.dashuyun.cn/Article/details/gtkldapmcy.html

std::sort(v.begin(), v.end());
来源：http://dali.ydzc1.top/Article/details/gtdumzdmgg.html

[S39] C++：自定义比较器排序
来源：http://dali.nwbrower.top/Article/details/gtzrxmvcka.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xinyue.icu/Article/details/gtupzaghat.html

[S40] C++：查找元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsinahsxo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shangyingyoupin.top/Article/details/gtkwqqxbkq.html

[S41] C++：类与构造函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtntngayxk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.nanxinkj.top/Article/details/gtucerjxvz.html

[S42] C++：继承与虚函数
来源：http://dali.c1oappe.top/Article/details/gtbagxtjpg.html

class B : public Base { public: void f() override {} };
来源：http://dali.cashguo.top/Article/details/gtvmeyutgf.html

[S43] C++：智能指针
来源：http://dali.zhengqikj.top/Article/details/gtgwbqcljl.html

auto p = std::make_unique<int>(5);
来源：http://dali.dianchejie.cn/Article/details/gtlccmnbuz.html

[S44] C++：引用传参
来源：http://dali.jinghuilouyu.cn/Article/details/gtggonewqf.html

void inc(int &x) { ++x; }
来源：http://dali.shanyushiyangtech.top/Article/details/gthqfvidja.html

[S45] C++：lambda
来源：http://dali.c1oappe.top/Article/details/gtgtatkyqt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yvedp.cn/Article/details/gtqltdvpaz.html

[S46] C++：函数模板
来源：http://dali.yanxiufei.cn/Article/details/gtxpsetsnj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenlongwang.top/Article/details/gtpbheskzg.html

[S47] C++：结构化绑定遍历
来源：http://dali.ydzc1.top/Article/details/gtkikayjwo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhijiandao.cn/Article/details/gtdoqflcno.html

[S48] C++：逐行读文件
来源：http://dali.cashguo.top/Article/details/gtqwbmgomu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shangyingyoupin.top/Article/details/gtglfqhfpt.html

while (std::getline(in, line)) { }
来源：http://dali.chenjidiqi.icu/Article/details/gtiwefzecz.html

[S49] C++：写文件
来源：http://dali.hywenlv.cn/Article/details/gtdwnrxpyr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinghuilouyu.cn/Article/details/gtqbhpdrfj.html

[S50] C++：格式化数字
来源：http://dali.mhx1999.top/Article/details/gtrobcckzq.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.vqdsnc.cn/Article/details/gtrdmervnd.html

[S51] C++：显式类型转换
来源：http://dali.mhx1999.top/Article/details/gtccjitlrl.html

static_cast<double>(a) / b
来源：http://dali.ydzc1.top/Article/details/gtlbnycsjx.html

[S52] C++：const 与 noexcept
来源：http://dali.cashguo.top/Article/details/gtejjkejje.html

int size() const noexcept { return n_; }
来源：http://dali.xziqi.cn/Article/details/gtmunesvaj.html

[S53] C++：移动语义
来源：http://dali.nwbrower.top/Article/details/gtjesxkhsn.html

std::vector<int> w = std::move(v);
来源：http://dali.jyoumei.cn/Article/details/gtdfzqhbfc.html

[S54] C++：异常处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcoadzhjs.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhoulong.xyz/Article/details/gtwjtdrgkt.html

[S55] C++：结构化绑定
来源：http://dali.aizwys.cn/Article/details/gthctzcgma.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yanxiufei.cn/Article/details/gtmtfkhscy.html

[S56] C++：optional
来源：http://dali.haohaochexian.top/Article/details/gtxincvjjr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbxbxezrd.html

[S57] C++：编译期常量
来源：http://dali.ivvv.top/Article/details/gtfhtmtcab.html

constexpr int N = 10;
来源：http://dali.jiagoushi.top/Article/details/gtjswnhuyp.html

[S58] C++：命名空间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvijbqiya.html

namespace ns { int f() { return 1; } }
来源：http://dali.c1oappe.top/Article/details/gttkfzpbfu.html

[S59] C++：静态断言
来源：http://dali.aibaodan.cn/Article/details/gtkzxlfbtu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xuanzx.com/Article/details/gtclclzgdk.html

[S60] C++：遍历并删除元素
来源：http://dali.0kj1m.cn/Article/details/gtkshoungy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ehwqpu.com/Article/details/gtbuhqwllo.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtldotavuf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gtocskymfd.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtrfbhmgeu.html

[T01] Kotlin：Hello World
来源：http://dali.meibo888.top/Article/details/gtsbsjyfwh.html

println("Hello")
来源：http://dali.9152youxi.cn/Article/details/gtpbgihocu.html

[T02] Kotlin：变量
来源：http://dali.jiagoushi.top/Article/details/gtwqleltsp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.vqdsnc.cn/Article/details/gtnljuhfom.html

[T03] Kotlin：字符串模板
来源：http://dali.yongpay.top/Article/details/gtqzspaigt.html

"值: $b"
来源：http://dali.pengpengdd.cyou/Article/details/gtsudefvae.html

[T04] Kotlin：空安全
来源：http://dali.yueranfly.top/Article/details/gteimvguxj.html

val n: String? = null;  n?.length
来源：http://dali.0kj1m.cn/Article/details/gtfrwvhidf.html

[T05] Kotlin：when 表达式
来源：http://dali.nanxinkj.top/Article/details/gtjqhcsamz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xziqi.cn/Article/details/gtpivqbaow.html

[T06] Kotlin：集合映射
来源：http://dali.aizwys.cn/Article/details/gtrbxpubku.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinqigufen.top/Article/details/gtpbtxtost.html

[T07] Kotlin：集合过滤
来源：http://dali.aizwys.cn/Article/details/gtervakhzx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hysaishi.cn/Article/details/gtdzkcrzrd.html

[T08] Kotlin：数据类
来源：http://dali.hammf.cn/Article/details/gtxyvzqngg.html

data class User(val name: String, val age: Int)
来源：http://dali.sysykeji.top/Article/details/gtwdvsfzqw.html

[T09] Kotlin：扩展函数
来源：http://dali.kuanghao11.cn/Article/details/gtcamvpjsw.html

fun String.exclaim() = this + "!"
来源：http://dali.xylfe.cn/Article/details/gtiepxfyrg.html

[T10] Kotlin：默认参数
来源：http://dali.ppjwa.cn/Article/details/gtmajrrvrf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.nwbrower.top/Article/details/gtefvdbihr.html

[T11] Kotlin：协程
来源：http://dali.chenjidiqi.icu/Article/details/gtpgnqfxvb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhoulong.xyz/Article/details/gtcnsrmhri.html

[T12] Kotlin：解构声明
来源：http://dali.tian-w.cn/Article/details/gtuzndaqix.html

val (a, b) = Pair(1, 2)
来源：http://dali.fzhhl.top/Article/details/gtaqytmuiv.html

[T13] Kotlin：只读 Map
来源：http://dali.316326.xyz/Article/details/gtvzczgelc.html

val m = mapOf("a" to 1)
来源：http://dali.hnxiangtu.top/Article/details/gtwfmumelr.html

[T14] Kotlin：循环
来源：http://dali.sysykeji.top/Article/details/gtwinijgac.html

for (i in 1..10) println(i)
来源：http://dali.wangshuangyany.cn/Article/details/gtpwkyqxxw.html

[T15] Kotlin：接口
来源：http://dali.xuanzx.com/Article/details/gtqljvttli.html

interface Shape { fun area(): Double }
来源：http://dali.jlsjyb.cn/Article/details/gtucejctmt.html

[T16] Swift：Hello World
来源：http://dali.ydzc1.top/Article/details/gtnbhebowc.html

print("Hello")
来源：http://dali.jqgufenzy.top/Article/details/gtpdsfaewe.html

[T17] Swift：变量与常量
来源：http://dali.snrcjt.cn/Article/details/gtthgcncfw.html

var a = 1;  let b = 2
来源：http://dali.zhixingplan.top/Article/details/gtobktwclt.html

[T18] Swift：字符串插值
来源：http://dali.kuanghao11.cn/Article/details/gtklxkmqtd.html

"值: \(b)"
来源：http://dali.mhx1999.top/Article/details/gthwdzvedd.html

[T19] Swift：可选绑定
来源：http://dali.zhengqikj.top/Article/details/gtnwqubicb.html

if let n = opt { print(n) }
来源：http://dali.hongshengwenyu.top/Article/details/gtebuwmwhd.html

[T20] Swift：数组操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdixkvdpz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gotoacloud.top/Article/details/gtpeabcoza.html

[T21] Swift：遍历
来源：http://dali.cucudq.cn/Article/details/gtnbeqmggb.html

for x in a { print(x) }
来源：http://dali.mhx1999.top/Article/details/gtjfvpxznb.html

[T22] Swift：字典
来源：http://dali.chenzaomai.com/Article/details/gtoldjufkf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.gaohongyu789.top/Article/details/gtpyccqfop.html

[T23] Swift：函数
来源：http://dali.zhixingplan.top/Article/details/gtjclfevpc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhoulong.xyz/Article/details/gtxhaqbudi.html

[T24] Swift：闭包
来源：http://dali.wangdashe.top/Article/details/gtfpseqkfu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jqgufenzy.top/Article/details/gtxnjudhak.html

[T25] Swift：结构体
来源：http://dali.yvedp.cn/Article/details/gtiuqpilvg.html

struct P { var x: Int }
来源：http://dali.guowangkeji.top/Article/details/gtntazdugo.html

[T26] Swift：类与重写
来源：http://dali.hfpthk.cn/Article/details/gtzjnwfptb.html

class A: Base { override func f() {} }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuywbcsme.html

[T27] Swift：错误处理
来源：http://dali.hnxiangtu.top/Article/details/gtwbhjkvmy.html

do { try f() } catch { print(error) }
来源：http://dali.tianlin.xyz/Article/details/gtsvgojccx.html

[T28] Swift：枚举
来源：http://dali.yuxming.cn/Article/details/gthzqnktxk.html

enum Color { case red, green }
来源：http://dali.cucudq.cn/Article/details/gtgozpckbw.html

[T29] Swift：guard 提前返回
来源：http://dali.chenzaomai.com/Article/details/gtaeozfglq.html

guard let x = opt else { return }
来源：http://dali.zhengqikj.top/Article/details/gtcegategz.html

[T30] Swift：协议
来源：http://dali.snrcjt.cn/Article/details/gtxelpxudz.html

protocol Shape { func area() -> Double }
来源：http://dali.xinyue.icu/Article/details/gtdsoxyjsk.html

[T31] Lua：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdalutgcv.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gtrvpohjxo.html

[T32] Lua：局部变量
来源：http://dali.yj20258.top/Article/details/gtkztvzqzh.html

local a = 1
来源：http://dali.jqgufenzy.top/Article/details/gtffqjqyzt.html

[T33] Lua：表（数组）
来源：http://dali.hfpthk.cn/Article/details/gtwwwoipxx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.c1oappe.top/Article/details/gtrtofjkqc.html

[T34] Lua：遍历表
来源：http://dali.mhx1999.top/Article/details/gtcofqwfwl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.sweek.top/Article/details/gtagfjeyud.html

[T35] Lua：字典表
来源：http://dali.dianchejie.cn/Article/details/gtfmpspzae.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jqgfzy.top/Article/details/gtecuyplmr.html

[T36] Lua：函数
来源：http://dali.birdmap.top/Article/details/gtmgqfcczh.html

function add(a, b) return a + b end
来源：http://dali.smart0.xyz/Article/details/gttxzqpgue.html

[T37] Lua：字符串拼接
来源：http://dali.xuanzx.com/Article/details/gtebzqgofx.html

"a" .. "b"
来源：http://dali.sxryk.cn/Article/details/gtpowmghnp.html

[T38] Lua：条件
来源：http://dali.jlsjyb.cn/Article/details/gtdhfbzlfl.html

if x > 0 then print("正") end
来源：http://dali.yanxiufei.cn/Article/details/gtatletvvu.html

[T39] Lua：模式匹配
来源：http://dali.xylfe.cn/Article/details/gtdyyycuim.html

string.find(s, "%d+")
来源：http://dali.mhx1999.top/Article/details/gtmgsjzjac.html

[T40] Lua：元表
来源：http://dali.hnxiangtu.top/Article/details/gtdcdryatf.html

setmetatable({}, { __index = base })
来源：http://dali.yanxiufei.cn/Article/details/gtmrsftewi.html

[T41] Perl：Hello World
来源：http://dali.mhx1999.top/Article/details/gtelxiwbgx.html

print "Hello\n";
来源：http://dali.sysykeji.top/Article/details/gtjvxfannh.html

[T42] Perl：变量类型
来源：http://dali.wangdashe.top/Article/details/gtoorzxwpz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.feifeiyinyue.top/Article/details/gtjndhmyfe.html

[T43] Perl：字符串插值
来源：http://dali.vqdsnc.cn/Article/details/gteprhwuff.html

"值: $a"
来源：http://dali.hnxiangtu.top/Article/details/gtbgicsjym.html

[T44] Perl：条件
来源：http://dali.yj20258888.top/Article/details/gtforhztte.html

if ($a > 0) { print "正"; }
来源：http://dali.andypj.xyz/Article/details/gthvjaasgq.html

[T45] Perl：数组遍历
来源：http://dali.daxiang520.top/Article/details/gtdvuqzazy.html

for my $x (@arr) { print $x; }
来源：http://dali.hnxiangtu.top/Article/details/gtzavroqos.html

[T46] Perl：哈希操作
来源：http://dali.yonumen.top/Article/details/gtnohlwaja.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.aibaodan.cn/Article/details/gtjjtialef.html

[T47] Perl：正则捕获
来源：http://dali.guannengcc.top/Article/details/gtwqbpsvom.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xylfe.cn/Article/details/gtlvkmjcuh.html

[T48] Perl：正则替换
来源：http://dali.birdmap.top/Article/details/gtzwfgsnoq.html

$s =~ s/old/new/g;
来源：http://dali.shzxlz.cn/Article/details/gtbtdxyipn.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gteywapvse.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.cashguo.top/Article/details/gteytqzudi.html

[T50] Perl：逐行读文件
来源：http://dali.hammf.cn/Article/details/gtvsxugwbe.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.chenjidiqi.icu/Article/details/gtsqjswpil.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jinqigfzy.top/Article/details/gtjqbuunlk.html

[T51] Scala：Hello World
来源：http://dali.zycfv.cn/Article/details/gtuqdkzhhx.html

println("Hello")
来源：http://dali.pycfn.com/Article/details/gterlatyyy.html

[T52] Scala：变量
来源：http://dali.redwolf501.top/Article/details/gtoevfzocf.html

val a = 1;  var b = 2
来源：http://dali.nanxuanxn.top/Article/details/gtqvjuefrt.html

[T53] Scala：字符串插值
来源：http://dali.iojbl.cn/Article/details/gtduyrwhrh.html

s"值: $b"
来源：http://dali.gotoacloud.top/Article/details/gtpvxrtbwn.html

[T54] Scala：集合映射
来源：http://dali.jinqigufen.top/Article/details/gtiomegpoa.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jqgfzy.top/Article/details/gtkiomfawe.html

[T55] Scala：集合过滤
来源：http://dali.yuxming.cn/Article/details/gtzsxcarnn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.havefunace.top/Article/details/gtdhivjamw.html

[T56] Scala：样例类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdvznapta.html

case class User(name: String, age: Int)
来源：http://dali.andypj.xyz/Article/details/gtcufyhfbr.html

[T57] Scala：模式匹配
来源：http://dali.bjfxy.top/Article/details/gtmzbtmrbu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.tanke756.top/Article/details/gtghfomlpj.html

[T58] Scala：函数定义
来源：http://dali.havefunace.top/Article/details/gtjedxsvvb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ppjwa.cn/Article/details/gtkfqyozhj.html

[T59] Scala：循环
来源：http://dali.hfpthk.cn/Article/details/gtszsgqlow.html

for (i <- 1 to 10) println(i)
来源：http://dali.yj20258.top/Article/details/gtkhblvbph.html

[T60] Scala：折叠
来源：http://dali.jianghu66.top/Article/details/gtaahznerp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cashguo.top/Article/details/gtocqirluz.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtbaxpqvjf.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.mhx1999.top/Article/details/gtapdqnwce.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtruukoyxn.html

[U01] Py：创建虚拟环境
来源：http://dali.chenjidiqi.icu/Article/details/gtpcgctjib.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.daria6918.cn/Article/details/gtgghmowip.html

[U02] Py：导出 / 安装依赖
来源：http://dali.pycfn.com/Article/details/gtvigjkdop.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgcdrszsl.html

[U03] Py：加载 .env 配置
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxhzrxqsa.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jqgfzy.top/Article/details/gthcgomhrl.html

[U04] Py：变量调试打印
来源：http://dali.yuanzhike.top/Article/details/gtynqffwip.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hnqzz.top/Article/details/gtlvnrsxeu.html

[U05] Py：列表去重且保序
来源：http://dali.birdmap.top/Article/details/gtutnkticn.html

list(dict.fromkeys(arr))
来源：http://dali.vqdsnc.cn/Article/details/gtanlircws.html

[U06] Py：合并两个字典
来源：http://dali.hammf.cn/Article/details/gtsdspxuel.html

{**a, **b}
来源：http://dali.shanyushiyangtech.top/Article/details/gtplhufhkf.html


<!-- 参考信息 -->