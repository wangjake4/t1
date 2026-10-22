代发 wailian999

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj202588.top/Article/details/gtwyiuzeoe.html

[R66] 定时任务
来源：http://dali.daxiang520.top/Article/details/gthihvupvv.html

crontab -e;  crontab -l
来源：http://dali.jyoumei.cn/Article/details/gtupmegxwh.html

[R67] 生成随机十六进制串
来源：http://dali.yonumen.top/Article/details/gtukmhepyy.html

openssl rand -hex 16
来源：http://dali.jqgfzy.top/Article/details/gtrfmlzesa.html

[R68] 计算文件校验值
来源：http://dali.shanyushiyangtech.top/Article/details/gtkctbieyi.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cashguo.top/Article/details/gtfcdwiwem.html

[R69] 生成随机密码
来源：http://dali.jyoumei.cn/Article/details/gtkzyjsqhd.html

head -c 16 /dev/urandom | base64
来源：http://dali.pengpengdd.cyou/Article/details/gttbfvfwyh.html

[R70] 时间戳与互转
来源：http://dali.mhx1999.top/Article/details/gtwhdwmijj.html

date +%s;  date -d @1700000000
来源：http://dali.shanyushiyangtech.top/Article/details/gtbigrqtvp.html

[R71] 日期格式化
来源：http://dali.nanxuanxn.top/Article/details/gtsqaagkfy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.wangdashe.top/Article/details/gtuspniysa.html

[R72] 等待端口就绪
来源：http://dali.sweek.top/Article/details/gtttfuaaie.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtydtdqpne.html

[R73] 分割大日志
来源：http://dali.shanyushiyangtech.top/Article/details/gtvhojvavl.html

split -l 1000 big.log part_
来源：http://dali.feifeiyinyue.top/Article/details/gtwijvlvga.html

[R74] 批量重命名
来源：http://dali.hnqzz.top/Article/details/gtfllajbes.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.bjfxy.top/Article/details/gtsahiylxt.html

[R75] 导出环境变量
来源：http://dali.vqdsnc.cn/Article/details/gtvjhcbliu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.fengsongda.top/Article/details/gtdlhlabrp.html

[R76] 使用临时文件
来源：http://dali.smart0.xyz/Article/details/gthmtddthu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuxming.cn/Article/details/gtvonidufo.html

[R77] 读取用户输入
来源：http://dali.iojbl.cn/Article/details/gtqgwhgzuv.html

read -rp "请输入: " ans
来源：http://dali.nanxinkj.top/Article/details/gthmgqkyqv.html

[R78] 交互式菜单
来源：http://dali.havefunace.top/Article/details/gtmfvsrocu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jianghu66.top/Article/details/gtxzoycfdf.html

[R79] 解析命令行选项
来源：http://dali.yanxiufei.cn/Article/details/gtccklgwmc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.nwbrower.top/Article/details/gtqdpuflie.html

[R80] 查看脚本执行耗时
来源：http://dali.pycfn.com/Article/details/gtloszxkvi.html

time ./run.sh
来源：http://dali.yj202588.top/Article/details/gtuddiuivm.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtaodtcjle.html

S. C / C++ 专题
来源：http://dali.jqgufenzy.top/Article/details/gtzdfzykxt.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtiicqbykp.html

[S01] C：Hello World
来源：http://dali.smart0.xyz/Article/details/gtrlltjpqe.html

#include <stdio.h>
来源：http://dali.birdmap.top/Article/details/gtwxgvvfdi.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.pengpengdd.cyou/Article/details/gtfyfqnxlv.html

[S02] C：变量与格式化输出
来源：http://dali.ehwqpu.com/Article/details/gtuzkrtyxm.html

int a = 10; printf("%d\n", a);
来源：http://dali.daxiang520.top/Article/details/gtejvjoupp.html

[S03] C：读入整数
来源：http://dali.xinyue.icu/Article/details/gtekuvwxhd.html

int x; scanf("%d", &x);
来源：http://dali.cdnleiting.top/Article/details/gtdpeegtqm.html

[S04] C：字符串复制
来源：http://dali.kuanghao11.cn/Article/details/gtolybfklc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.0kj1m.cn/Article/details/gtjtogvcgh.html

[S05] C：字符串长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtiofiujno.html

strlen(s)
来源：http://dali.smart0.xyz/Article/details/gtabpgnlsa.html

[S06] C：字符串比较
来源：http://dali.gzhubu.top/Article/details/gtqjascviz.html

strcmp(a, b) == 0
来源：http://dali.zhengqikj.top/Article/details/gtkzyqmnsd.html

[S07] C：数组遍历求和
来源：http://dali.zhixingplan.top/Article/details/gtxubhjclw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.daxiang520.top/Article/details/gtpnnoipyd.html

[S08] C：动态内存分配与释放
来源：http://dali.zdqjudy.top/Article/details/gtqnlovtgp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhoulong.xyz/Article/details/gterjovkwv.html

[S09] C：结构体定义与初始化
来源：http://dali.xylfe.cn/Article/details/gtwrvjdbwt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.nwbrower.top/Article/details/gtsmefthyt.html

[S10] C：指针与解引用
来源：http://dali.ppjwa.cn/Article/details/gtchsvlyij.html

int *p = &a;  *p = 5;
来源：http://dali.9152youxi.cn/Article/details/gtyqsvplid.html

[S11] C：逐行读文件
来源：http://dali.wangshuangyany.cn/Article/details/gtsnloxlec.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkpydkpbw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yvedp.cn/Article/details/gtnqtbdpqi.html

fclose(f);
来源：http://dali.jqgufenzy.top/Article/details/gtahohpadq.html

[S12] C：写文件
来源：http://dali.zycfv.cn/Article/details/gtdkwnmtji.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shangyingyoupin.top/Article/details/gteuwbwgxy.html

[S13] C：宏定义
来源：http://dali.sysykeji.top/Article/details/gtorifcswx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zdqjudy.top/Article/details/gtifrpurxq.html

[S14] C：枚举
来源：http://dali.shzxlz.cn/Article/details/gtasojibnk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.andypj.xyz/Article/details/gtfvanmijo.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gtstnutont.html

(double) a / b
来源：http://dali.cqqwz.cn/Article/details/gtoqptfhaf.html

[S16] C：位操作置位
来源：http://dali.cucudq.cn/Article/details/gtiaxjhkfi.html

x |= (1 << 3);
来源：http://dali.bjfxy.top/Article/details/gtmclxmxye.html

[S17] C：安全拼接字符串
来源：http://dali.hywenlv.cn/Article/details/gtxbdgkilg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shuidangran.top/Article/details/gtilqxvsku.html

[S18] C：命令行参数
来源：http://dali.bjfxy.top/Article/details/gtwjtbjpfk.html

int main(int argc, char **argv)
来源：http://dali.yuxming.cn/Article/details/gtahlajaok.html

[S19] C：快速排序
来源：http://dali.haohaochexian.top/Article/details/gtkyfyndtd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gaohongyu789.top/Article/details/gtattuxvyu.html

[S20] C：二分查找
来源：http://dali.cashguo.top/Article/details/gtjidxjsiq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.c1oappe.top/Article/details/gtdmqxuekq.html

[S21] C：字符类别判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gttvujihfl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.tian-w.cn/Article/details/gtkwknlyzk.html

[S22] C：字符串转数字
来源：http://dali.zhoulong.xyz/Article/details/gtgslqyytk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.iojbl.cn/Article/details/gtezwgvlra.html

[S23] C：随机数
来源：http://dali.sxryk.cn/Article/details/gtmguvdfld.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.birdmap.top/Article/details/gtqsgclhdr.html

[S24] C：获取本地时间
来源：http://dali.redwolf501.top/Article/details/gtkyowyhkq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhixingplan.top/Article/details/gtoksushye.html

[S25] C：内存拷贝
来源：http://dali.hongshengwenyu.top/Article/details/gtvhmpxmkt.html

memcpy(dst, src, n);
来源：http://dali.jianghu66.top/Article/details/gtyojwtcno.html

[S26] C：内存清零
来源：http://dali.jlsjyb.cn/Article/details/gtzvkwxhha.html

memset(a, 0, sizeof a);
来源：http://dali.vqdsnc.cn/Article/details/gtwhfkbgwu.html

[S27] C：定义常量
来源：http://dali.gaohongyu789.top/Article/details/gtxlfgfukt.html

const double PI = 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gtmoofugdz.html

[S28] C：静态变量
来源：http://dali.xinyue.icu/Article/details/gtbaqmdsza.html

static int counter = 0;
来源：http://dali.yj20258888.top/Article/details/gtyktbsiug.html

[S29] C：变参函数
来源：http://dali.xziqi.cn/Article/details/gtgiglotgr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cashguo.top/Article/details/gtszzuopxc.html

[S30] C：头文件保护
来源：http://dali.nanxuanxn.top/Article/details/gtdxzgcmbj.html

#ifndef X_H
来源：http://dali.hammf.cn/Article/details/gtzidomgxy.html

#define X_H
来源：http://dali.hongshengwenyu.top/Article/details/gtyrxzaetj.html

#endif
来源：http://dali.sxryk.cn/Article/details/gtyvmolxxx.html

[S31] C++：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtcjgmctzz.html

#include <iostream>
来源：http://dali.fzhhl.top/Article/details/gtbbknqvmy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.tanke756.top/Article/details/gtgapilyzj.html

[S32] C++：字符串
来源：http://dali.snrcjt.cn/Article/details/gtsgppvxud.html

std::string s = "hi";  s += "!";
来源：http://dali.yangfankeji.com/Article/details/gtdkiisded.html

[S33] C++：vector 增删
来源：http://dali.nwbrower.top/Article/details/gtvtqpyevr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.iojbl.cn/Article/details/gtwjaijfhq.html

[S34] C++：遍历 vector
来源：http://dali.ppjwa.cn/Article/details/gtioeqdlni.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shuidangran.top/Article/details/gtxflyjetq.html

[S35] C++：map
来源：http://dali.zhixingplan.top/Article/details/gtbcvodyeu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tanke756.top/Article/details/gtxgmgskzp.html

[S36] C++：unordered_map
来源：http://dali.chenjidiqi.icu/Article/details/gtqhjugdxy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gttvziewhf.html

[S37] C++：set
来源：http://dali.jqgfzy.top/Article/details/gttbewqwcr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.kuanghao11.cn/Article/details/gtgoyvaktg.html

[S38] C++：排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpshanuja.html

std::sort(v.begin(), v.end());
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgnzpxkfg.html

[S39] C++：自定义比较器排序
来源：http://dali.hysaishi.cn/Article/details/gtasoqbqia.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.mhx1999.top/Article/details/gtxtemkiqj.html

[S40] C++：查找元素
来源：http://dali.daxiang520.top/Article/details/gtxmucmeir.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.andypj.xyz/Article/details/gtdaezimcg.html

[S41] C++：类与构造函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvxvfruvr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.svipenyu.cn/Article/details/gthpmsiewh.html

[S42] C++：继承与虚函数
来源：http://dali.tianlin.xyz/Article/details/gtifalkfwi.html

class B : public Base { public: void f() override {} };
来源：http://dali.316326.xyz/Article/details/gtkjhpsuvq.html

[S43] C++：智能指针
来源：http://dali.yuxming.cn/Article/details/gtofcwstlw.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinqigufen.top/Article/details/gtondpupiw.html

[S44] C++：引用传参
来源：http://dali.sysykeji.top/Article/details/gtzcukxghh.html

void inc(int &x) { ++x; }
来源：http://dali.daria6918.cn/Article/details/gthhwtqqqf.html

[S45] C++：lambda
来源：http://dali.yj20258888.top/Article/details/gtaloykiay.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkegkzucg.html

[S46] C++：函数模板
来源：http://dali.quarkkingdee.top/Article/details/gtpnnhobeu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.nanxinkj.top/Article/details/gtrtszepnx.html

[S47] C++：结构化绑定遍历
来源：http://dali.andypj.xyz/Article/details/gtboeiwvdd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.nwbrower.top/Article/details/gtmprfwemu.html

[S48] C++：逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gtwkjzmpll.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hammf.cn/Article/details/gtseaigvzw.html

while (std::getline(in, line)) { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlqvlwbwh.html

[S49] C++：写文件
来源：http://dali.daxiang520.top/Article/details/gtnkfgtsvq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.kuanghao11.cn/Article/details/gtdgmzzyqt.html

[S50] C++：格式化数字
来源：http://dali.hammf.cn/Article/details/gtvqisddnp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xylfe.cn/Article/details/gtembfadbc.html

[S51] C++：显式类型转换
来源：http://dali.zhongyouzk.top/Article/details/gtkwdghuow.html

static_cast<double>(a) / b
来源：http://dali.chenlongwang.top/Article/details/gtnndjtrqg.html

[S52] C++：const 与 noexcept
来源：http://dali.316326.xyz/Article/details/gtyfzbkbnp.html

int size() const noexcept { return n_; }
来源：http://dali.nanxuanxn.top/Article/details/gthcwshmpv.html

[S53] C++：移动语义
来源：http://dali.quarkkingdee.top/Article/details/gtilkcinko.html

std::vector<int> w = std::move(v);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzxkkhtvt.html

[S54] C++：异常处理
来源：http://dali.yj202588.top/Article/details/gtyuejjutb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhixingplan.top/Article/details/gtmnqezsgd.html

[S55] C++：结构化绑定
来源：http://dali.9152youxi.cn/Article/details/gtzwibrsor.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sxryk.cn/Article/details/gtoeeqmyhy.html

[S56] C++：optional
来源：http://dali.bjfxy.top/Article/details/gthqgvpyhq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.pycfn.com/Article/details/gttmgtvhfu.html

[S57] C++：编译期常量
来源：http://dali.havefunace.top/Article/details/gtwamrutvv.html

constexpr int N = 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtequbkthn.html

[S58] C++：命名空间
来源：http://dali.dashuyun.cn/Article/details/gtrkpxsyrw.html

namespace ns { int f() { return 1; } }
来源：http://dali.pycfn.com/Article/details/gtpczjxxvi.html

[S59] C++：静态断言
来源：http://dali.shzxlz.cn/Article/details/gttwnzogpm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.tanke756.top/Article/details/gtdtdpieov.html

[S60] C++：遍历并删除元素
来源：http://dali.birdmap.top/Article/details/gtcixebyuq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sweek.top/Article/details/gtcxbgqhjo.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtdbjpsyzs.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.bjfxy.top/Article/details/gtjuyursjf.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtznawesuv.html

[T01] Kotlin：Hello World
来源：http://dali.birdmap.top/Article/details/gtmoalxsxt.html

println("Hello")
来源：http://dali.ppjwa.cn/Article/details/gtnadifvbu.html

[T02] Kotlin：变量
来源：http://dali.svipenyu.cn/Article/details/gtpbzvidnd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.wangdashe.top/Article/details/gtpocdvptr.html

[T03] Kotlin：字符串模板
来源：http://dali.zycfv.cn/Article/details/gtougomtcw.html

"值: $b"
来源：http://dali.cqqwz.cn/Article/details/gtbyinskbf.html

[T04] Kotlin：空安全
来源：http://dali.nanxinkj.top/Article/details/gthocwmgnq.html

val n: String? = null;  n?.length
来源：http://dali.sufxvd.cn/Article/details/gtfekiyvnr.html

[T05] Kotlin：when 表达式
来源：http://dali.xuetiantiany.cn/Article/details/gtdkskeoqz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinqigufen.top/Article/details/gtbfyhktrw.html

[T06] Kotlin：集合映射
来源：http://dali.wangshuangyany.cn/Article/details/gttmxvqjqn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cucudq.cn/Article/details/gtgreiztsz.html

[T07] Kotlin：集合过滤
来源：http://dali.xylfe.cn/Article/details/gtnbofeupn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.andypj.xyz/Article/details/gtlxazwxxc.html

[T08] Kotlin：数据类
来源：http://dali.sweek.top/Article/details/gteidmthhg.html

data class User(val name: String, val age: Int)
来源：http://dali.jinqigufen.top/Article/details/gtbzorpryb.html

[T09] Kotlin：扩展函数
来源：http://dali.9152youxi.cn/Article/details/gtetarlnya.html

fun String.exclaim() = this + "!"
来源：http://dali.ehwqpu.com/Article/details/gtpkcdupla.html

[T10] Kotlin：默认参数
来源：http://dali.xuanzx.com/Article/details/gtvmjrgphq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jinqigufen.top/Article/details/gtfvpwkzfo.html

[T11] Kotlin：协程
来源：http://dali.chenlongwang.top/Article/details/gtffqmniod.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.fzhhl.top/Article/details/gtdlkildrl.html

[T12] Kotlin：解构声明
来源：http://dali.smart0.xyz/Article/details/gtxyftaggt.html

val (a, b) = Pair(1, 2)
来源：http://dali.hysaishi.cn/Article/details/gtvsondzjf.html

[T13] Kotlin：只读 Map
来源：http://dali.havefunace.top/Article/details/gtccpjuudj.html

val m = mapOf("a" to 1)
来源：http://dali.jinqigfzy.top/Article/details/gtnzkasivs.html

[T14] Kotlin：循环
来源：http://dali.birdmap.top/Article/details/gtzwcfwixa.html

for (i in 1..10) println(i)
来源：http://dali.ivvv.top/Article/details/gtcpjjnqlz.html

[T15] Kotlin：接口
来源：http://dali.pengpengdd.cyou/Article/details/gtghzyclkd.html

interface Shape { fun area(): Double }
来源：http://dali.zycfv.cn/Article/details/gtxqonodha.html

[T16] Swift：Hello World
来源：http://dali.smart0.xyz/Article/details/gtsvusubwt.html

print("Hello")
来源：http://dali.ydzc1.top/Article/details/gtbjuqonjk.html

[T17] Swift：变量与常量
来源：http://dali.ehwqpu.com/Article/details/gtzzwdmkmv.html

var a = 1;  let b = 2
来源：http://dali.yangfankeji.com/Article/details/gtsesnpbjh.html

[T18] Swift：字符串插值
来源：http://dali.yuxming.cn/Article/details/gtcxajxlfj.html

"值: \(b)"
来源：http://dali.yongpay.top/Article/details/gtpjkokpul.html

[T19] Swift：可选绑定
来源：http://dali.kuanghao11.cn/Article/details/gtgjwuybqp.html

if let n = opt { print(n) }
来源：http://dali.mhx1999.top/Article/details/gtpgqpfitc.html

[T20] Swift：数组操作
来源：http://dali.zhongyouzk.top/Article/details/gtooopzfsu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yuxming.cn/Article/details/gtajrmwlcu.html

[T21] Swift：遍历
来源：http://dali.chenzaomai.com/Article/details/gteopjxmtw.html

for x in a { print(x) }
来源：http://dali.nwbrower.top/Article/details/gtgwwuhvmp.html

[T22] Swift：字典
来源：http://dali.aibaodan.cn/Article/details/gtgtbprvjm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yueranfly.top/Article/details/gtdcicoilk.html

[T23] Swift：函数
来源：http://dali.feifeiyinyue.top/Article/details/gtaigyijzb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.tianlin.xyz/Article/details/gtlxwoesdo.html

[T24] Swift：闭包
来源：http://dali.gotoacloud.top/Article/details/gtuhdudtbv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zycfv.cn/Article/details/gtgxqmiegz.html

[T25] Swift：结构体
来源：http://dali.xuetiantiany.cn/Article/details/gtxxjaddzq.html

struct P { var x: Int }
来源：http://dali.zycfv.cn/Article/details/gtvucsqdfe.html

[T26] Swift：类与重写
来源：http://dali.smart0.xyz/Article/details/gtpgvtdtfx.html

class A: Base { override func f() {} }
来源：http://dali.snrcjt.cn/Article/details/gtsdrdxvky.html

[T27] Swift：错误处理
来源：http://dali.chenjidiqi.icu/Article/details/gtfmiixkmw.html

do { try f() } catch { print(error) }
来源：http://dali.hnqzz.top/Article/details/gtpyftdwmb.html

[T28] Swift：枚举
来源：http://dali.yuxming.cn/Article/details/gtqtfopyns.html

enum Color { case red, green }
来源：http://dali.fzhhl.top/Article/details/gtkkysycbr.html

[T29] Swift：guard 提前返回
来源：http://dali.yangfankeji.com/Article/details/gthjobbnjv.html

guard let x = opt else { return }
来源：http://dali.ehwqpu.com/Article/details/gtopymhrxb.html

[T30] Swift：协议
来源：http://dali.shzxlz.cn/Article/details/gtvcwypstu.html

protocol Shape { func area() -> Double }
来源：http://dali.cucudq.cn/Article/details/gtzxucymrb.html

[T31] Lua：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwuzyycyw.html

print("Hello")
来源：http://dali.smart0.xyz/Article/details/gtpdpxzbeg.html

[T32] Lua：局部变量
来源：http://dali.pengpengdd.cyou/Article/details/gtsqhqerpk.html

local a = 1
来源：http://dali.jinqigufen.top/Article/details/gtjuzwvass.html

[T33] Lua：表（数组）
来源：http://dali.hnqzz.top/Article/details/gtvnzpphwc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.chenlongwang.top/Article/details/gtulotnolb.html

[T34] Lua：遍历表
来源：http://dali.9152youxi.cn/Article/details/gtxtnvdgoz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.iojbl.cn/Article/details/gtcwdlvrgi.html

[T35] Lua：字典表
来源：http://dali.svipenyu.cn/Article/details/gtlbojdyhd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.daria6918.cn/Article/details/gtdakgjbeg.html

[T36] Lua：函数
来源：http://dali.tanke756.top/Article/details/gtpajpsdtz.html

function add(a, b) return a + b end
来源：http://dali.jlsjyb.cn/Article/details/gtjqadyira.html

[T37] Lua：字符串拼接
来源：http://dali.zhoulong.xyz/Article/details/gtykxofdhw.html

"a" .. "b"
来源：http://dali.hysaishi.cn/Article/details/gtuxgzfzzd.html

[T38] Lua：条件
来源：http://dali.xuetiantiany.cn/Article/details/gtubrfpiel.html

if x > 0 then print("正") end
来源：http://dali.hysaishi.cn/Article/details/gtiovbncuc.html

[T39] Lua：模式匹配
来源：http://dali.aizwys.cn/Article/details/gtrlaqnbdy.html

string.find(s, "%d+")
来源：http://dali.iojbl.cn/Article/details/gtspeljrte.html

[T40] Lua：元表
来源：http://dali.zhongyouzk.top/Article/details/gticoxzbxz.html

setmetatable({}, { __index = base })
来源：http://dali.gogol.net.cn/Article/details/gtqucmtgpp.html

[T41] Perl：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtsqestucl.html

print "Hello\n";
来源：http://dali.quarkkingdee.top/Article/details/gtxtossmdt.html

[T42] Perl：变量类型
来源：http://dali.zhongyouzk.top/Article/details/gtrtylcdqe.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jlsjyb.cn/Article/details/gtvwdsckwv.html

[T43] Perl：字符串插值
来源：http://dali.xuanzx.com/Article/details/gtnvujleco.html

"值: $a"
来源：http://dali.aibaodan.cn/Article/details/gtfsnodftn.html

[T44] Perl：条件
来源：http://dali.ehwqpu.com/Article/details/gtjozcooix.html

if ($a > 0) { print "正"; }
来源：http://dali.sysykeji.top/Article/details/gtwpvoblct.html

[T45] Perl：数组遍历
来源：http://dali.iojbl.cn/Article/details/gtabfqkwrv.html

for my $x (@arr) { print $x; }
来源：http://dali.hnqzz.top/Article/details/gtlcilqdvw.html

[T46] Perl：哈希操作
来源：http://dali.pengpengdd.cyou/Article/details/gtgfgzrgjq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhixingplan.top/Article/details/gtkxuzybak.html

[T47] Perl：正则捕获
来源：http://dali.wangshuangyany.cn/Article/details/gtxvtgbexb.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.birdmap.top/Article/details/gtknfwmzzc.html

[T48] Perl：正则替换
来源：http://dali.yuxming.cn/Article/details/gtepnldpgu.html

$s =~ s/old/new/g;
来源：http://dali.daria6918.cn/Article/details/gtnpufsslg.html

[T49] Perl：函数
来源：http://dali.dianchejie.cn/Article/details/gtpvgbpwye.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.guowangkeji.top/Article/details/gttbwwqcty.html

[T50] Perl：逐行读文件
来源：http://dali.hammf.cn/Article/details/gtqqqkehje.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zycfv.cn/Article/details/gtdzoczxcz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.zycfv.cn/Article/details/gtgxhtudhk.html

[T51] Scala：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtqdhwwxba.html

println("Hello")
来源：http://dali.shzxlz.cn/Article/details/gtvhwvejmi.html

[T52] Scala：变量
来源：http://dali.jianghu66.top/Article/details/gtbugrzwrt.html

val a = 1;  var b = 2
来源：http://dali.yvedp.cn/Article/details/gtnbzounjo.html

[T53] Scala：字符串插值
来源：http://dali.meibo888.top/Article/details/gtdiucrwub.html

s"值: $b"
来源：http://dali.ppjwa.cn/Article/details/gtpdsmdtvg.html

[T54] Scala：集合映射
来源：http://dali.gzhubu.top/Article/details/gthqmjqomx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.xinyue.icu/Article/details/gtdzvtfyxh.html

[T55] Scala：集合过滤
来源：http://dali.316326.xyz/Article/details/gtdvkfheet.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.nanxuanxn.top/Article/details/gtzdyacxwm.html

[T56] Scala：样例类
来源：http://dali.mhx1999.top/Article/details/gtkwhmfema.html

case class User(name: String, age: Int)
来源：http://dali.guowangkeji.top/Article/details/gtfkhnazlc.html

[T57] Scala：模式匹配
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttlcsckdt.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yj20258.top/Article/details/gtlnqywnbg.html

[T58] Scala：函数定义
来源：http://dali.tian-w.cn/Article/details/gtvldjlptn.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xziqi.cn/Article/details/gtbooycbmj.html

[T59] Scala：循环
来源：http://dali.yangfankeji.com/Article/details/gtlbvjhlvv.html

for (i <- 1 to 10) println(i)
来源：http://dali.yvedp.cn/Article/details/gtobjhauou.html

[T60] Scala：折叠
来源：http://dali.316326.xyz/Article/details/gtylapuwgd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtchspflsy.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtkgkitnma.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.fengsongda.top/Article/details/gtnusvpqlu.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtguyedgsh.html

[U01] Py：创建虚拟环境
来源：http://dali.zhaomingkeji.xyz/Article/details/gtommmbfry.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.tanke756.top/Article/details/gtmovjhzom.html

[U02] Py：导出 / 安装依赖
来源：http://dali.tanke756.top/Article/details/gtlaukxbhj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yj20258888.top/Article/details/gtxkelxain.html

[U03] Py：加载 .env 配置
来源：http://dali.nanxinkj.top/Article/details/gtlajnzxgx.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.wangdashe.top/Article/details/gtsxaeyemo.html

[U04] Py：变量调试打印
来源：http://dali.snrcjt.cn/Article/details/gtnbdocalz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.0kj1m.cn/Article/details/gtpqkxhyoa.html

[U05] Py：列表去重且保序
来源：http://dali.feifeiyinyue.top/Article/details/gthtimrzrx.html

list(dict.fromkeys(arr))
来源：http://dali.mhx1999.top/Article/details/gtejpptimu.html

[U06] Py：合并两个字典
来源：http://dali.aibaodan.cn/Article/details/gthfihyamd.html

{**a, **b}
来源：http://dali.jinghuilouyu.cn/Article/details/gtvmvqicau.html


<!-- 参考信息 -->