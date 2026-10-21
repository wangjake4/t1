代发 wailian999

df -h;  du -sh *
来源：http://dali.yuxming.cn/Article/details/gteykltjgy.html

[R62] 找最占空间的文件
来源：http://dali.zhoulong.xyz/Article/details/gtlomqmhfh.html

du -ah . | sort -rh | head -10
来源：http://dali.ivvv.top/Article/details/gtdkinjkhw.html

[R63] 内存与进程
来源：http://dali.mhx1999.top/Article/details/gttgotzqyz.html

free -h;  ps aux | grep nginx
来源：http://dali.gaohongyu789.top/Article/details/gtbaqpgilm.html

[R64] 结束进程
来源：http://dali.chenlongwang.top/Article/details/gtetlufuos.html

kill -9 $(pgrep -f app.py)
来源：http://dali.9152youxi.cn/Article/details/gtvbqiiobg.html

[R65] 查看端口占用
来源：http://dali.zhengqikj.top/Article/details/gtztrribjq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ywan-chungtsiang.top/Article/details/gtusowaarb.html

[R66] 定时任务
来源：http://dali.fzhhl.top/Article/details/gtfoeerejm.html

crontab -e;  crontab -l
来源：http://dali.0kj1m.cn/Article/details/gtpfpidfsh.html

[R67] 生成随机十六进制串
来源：http://dali.wangdashe.top/Article/details/gtteaisxnm.html

openssl rand -hex 16
来源：http://dali.gotoacloud.top/Article/details/gtzawnmdny.html

[R68] 计算文件校验值
来源：http://dali.zycfv.cn/Article/details/gtwrpajypr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhixingplan.top/Article/details/gtoijlxvqe.html

[R69] 生成随机密码
来源：http://dali.sufxvd.cn/Article/details/gtikdsgyrr.html

head -c 16 /dev/urandom | base64
来源：http://dali.jqgufenzy.top/Article/details/gthogpjdxh.html

[R70] 时间戳与互转
来源：http://dali.feifeiyinyue.top/Article/details/gtkqocsaef.html

date +%s;  date -d @1700000000
来源：http://dali.zhoulong.xyz/Article/details/gtyygeuxeu.html

[R71] 日期格式化
来源：http://dali.shzxlz.cn/Article/details/gtghxnuylv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinqigfzy.top/Article/details/gtunhvvyyc.html

[R72] 等待端口就绪
来源：http://dali.jinyuanbaomall.cn/Article/details/gtstkjbobs.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmcsytivb.html

[R73] 分割大日志
来源：http://dali.nanxinkj.top/Article/details/gtsbaavphy.html

split -l 1000 big.log part_
来源：http://dali.yongpay.top/Article/details/gtlblymdpc.html

[R74] 批量重命名
来源：http://dali.hongshengwenyu.top/Article/details/gtcybeldeo.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.mhx1999.top/Article/details/gtmgantzef.html

[R75] 导出环境变量
来源：http://dali.tianlin.xyz/Article/details/gtnrjayofq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhoulong.xyz/Article/details/gtsnmnuxhn.html

[R76] 使用临时文件
来源：http://dali.quarkkingdee.top/Article/details/gttzrxpwrr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.iojbl.cn/Article/details/gtbrpphdwx.html

[R77] 读取用户输入
来源：http://dali.tian-w.cn/Article/details/gtgbtgnmgx.html

read -rp "请输入: " ans
来源：http://dali.yangfankeji.com/Article/details/gtrzjsburj.html

[R78] 交互式菜单
来源：http://dali.hnxiangtu.top/Article/details/gtnpbthhqg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jqgufenzy.top/Article/details/gtcrqtvqnw.html

[R79] 解析命令行选项
来源：http://dali.tianlin.xyz/Article/details/gtadoufozq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hnqzz.top/Article/details/gteecrdfsw.html

[R80] 查看脚本执行耗时
来源：http://dali.andypj.xyz/Article/details/gtfmmdvfqc.html

time ./run.sh
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtipgyqlcw.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtqgxkpxma.html

S. C / C++ 专题
来源：http://dali.tianlin.xyz/Article/details/gtslfczacv.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtelzgfovx.html

[S01] C：Hello World
来源：http://dali.daxiang520.top/Article/details/gtcxhzbmhr.html

#include <stdio.h>
来源：http://dali.xinyue.icu/Article/details/gtuayaccvy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.daria6918.cn/Article/details/gtlcjvjzxu.html

[S02] C：变量与格式化输出
来源：http://dali.yj20258.top/Article/details/gtpxrqtffk.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinqigufen.top/Article/details/gttyftbmsr.html

[S03] C：读入整数
来源：http://dali.yonumen.top/Article/details/gtivuqximc.html

int x; scanf("%d", &x);
来源：http://dali.hywenlv.cn/Article/details/gtplznaium.html

[S04] C：字符串复制
来源：http://dali.yueranfly.top/Article/details/gtyjfjbrno.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ehwqpu.com/Article/details/gtcbfsdaim.html

[S05] C：字符串长度
来源：http://dali.dashuyun.cn/Article/details/gtwxhiwzea.html

strlen(s)
来源：http://dali.feifeiyinyue.top/Article/details/gtirnobunz.html

[S06] C：字符串比较
来源：http://dali.birdmap.top/Article/details/gtfyuqwfxr.html

strcmp(a, b) == 0
来源：http://dali.ehwqpu.com/Article/details/gtzonviutk.html

[S07] C：数组遍历求和
来源：http://dali.chenzaomai.com/Article/details/gtboiqrbqc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gtpmfffuqp.html

[S08] C：动态内存分配与释放
来源：http://dali.zhixingplan.top/Article/details/gtcxscsmrt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shuidangran.top/Article/details/gtoltvlhcm.html

[S09] C：结构体定义与初始化
来源：http://dali.316326.xyz/Article/details/gtmwzwlfcq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ydzc1.top/Article/details/gtlefmpgrz.html

[S10] C：指针与解引用
来源：http://dali.tian-w.cn/Article/details/gtcnaosdni.html

int *p = &a;  *p = 5;
来源：http://dali.sxryk.cn/Article/details/gtzxlheqnr.html

[S11] C：逐行读文件
来源：http://dali.iojbl.cn/Article/details/gttutqedql.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhixingplan.top/Article/details/gtfymmhehv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yangfankeji.com/Article/details/gtopxonwgu.html

fclose(f);
来源：http://dali.chenlongwang.top/Article/details/gtktdwfcrn.html

[S12] C：写文件
来源：http://dali.nanxuanxn.top/Article/details/gtowafykhy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gzhubu.top/Article/details/gtmvmwjost.html

[S13] C：宏定义
来源：http://dali.sysykeji.top/Article/details/gtzvkwtyas.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yonumen.top/Article/details/gtdoveggvg.html

[S14] C：枚举
来源：http://dali.jiagoushi.top/Article/details/gtqasemaaj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zdqjudy.top/Article/details/gtgmhjsdnj.html

[S15] C：类型转换
来源：http://dali.yj20258888.top/Article/details/gtfhomcoek.html

(double) a / b
来源：http://dali.gogol.net.cn/Article/details/gtwnyoxbke.html

[S16] C：位操作置位
来源：http://dali.jyoumei.cn/Article/details/gtpnsnymri.html

x |= (1 << 3);
来源：http://dali.yj20258.top/Article/details/gtccedyohf.html

[S17] C：安全拼接字符串
来源：http://dali.ybcxt.top/Article/details/gtbjvvudfu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfnxsrkzt.html

[S18] C：命令行参数
来源：http://dali.nanxinkj.top/Article/details/gttkmduktq.html

int main(int argc, char **argv)
来源：http://dali.xziqi.cn/Article/details/gtcjgfdvez.html

[S19] C：快速排序
来源：http://dali.meibo888.top/Article/details/gthinrfmev.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gtzimpjrak.html

[S20] C：二分查找
来源：http://dali.zhoulong.xyz/Article/details/gtcxsyxgfz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.316326.xyz/Article/details/gtxjkuonnb.html

[S21] C：字符类别判断
来源：http://dali.xinyue.icu/Article/details/gtggxmdllj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hnxiangtu.top/Article/details/gtijypcqma.html

[S22] C：字符串转数字
来源：http://dali.ppjwa.cn/Article/details/gtigsyqsly.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yangfankeji.com/Article/details/gtowonssdw.html

[S23] C：随机数
来源：http://dali.dashuyun.cn/Article/details/gtrxfqopdg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.fengsongda.top/Article/details/gtszgtmoio.html

[S24] C：获取本地时间
来源：http://dali.zdqjudy.top/Article/details/gtgcqzqzcf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cashguo.top/Article/details/gtjjcsitew.html

[S25] C：内存拷贝
来源：http://dali.gotoacloud.top/Article/details/gtabpmawzg.html

memcpy(dst, src, n);
来源：http://dali.wangdashe.top/Article/details/gtsaaiirnd.html

[S26] C：内存清零
来源：http://dali.vqdsnc.cn/Article/details/gtlbjmiuys.html

memset(a, 0, sizeof a);
来源：http://dali.shanyushiyangtech.top/Article/details/gtsfqebsvj.html

[S27] C：定义常量
来源：http://dali.svipenyu.cn/Article/details/gtalnxgdvy.html

const double PI = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gtroghfeig.html

[S28] C：静态变量
来源：http://dali.yongpay.top/Article/details/gtwwnsereo.html

static int counter = 0;
来源：http://dali.zhongyouzk.top/Article/details/gtdqjpyfty.html

[S29] C：变参函数
来源：http://dali.pengpengdd.cyou/Article/details/gtyuzdfccm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sweek.top/Article/details/gtufiaqhui.html

[S30] C：头文件保护
来源：http://dali.jyoumei.cn/Article/details/gtpsbxgcwq.html

#ifndef X_H
来源：http://dali.tian-w.cn/Article/details/gtkfqvosgc.html

#define X_H
来源：http://dali.316326.xyz/Article/details/gtjgpmfwmv.html

#endif
来源：http://dali.jqgfzy.top/Article/details/gtembulqfr.html

[S31] C++：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjyewjvgh.html

#include <iostream>
来源：http://dali.bjfxy.top/Article/details/gtkllpztdu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nanxuanxn.top/Article/details/gtjuqqzjrs.html

[S32] C++：字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpxjxoukh.html

std::string s = "hi";  s += "!";
来源：http://dali.hysaishi.cn/Article/details/gtacetkmja.html

[S33] C++：vector 增删
来源：http://dali.redwolf501.top/Article/details/gtgeclpzba.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhengqikj.top/Article/details/gtioajmryl.html

[S34] C++：遍历 vector
来源：http://dali.aizwys.cn/Article/details/gtsednjbtu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ehwqpu.com/Article/details/gtasaslxqd.html

[S35] C++：map
来源：http://dali.jinqigufen.top/Article/details/gtlzpawzkf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigufen.top/Article/details/gtxloncmic.html

[S36] C++：unordered_map
来源：http://dali.cashguo.top/Article/details/gtjjzlgzkz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuxming.cn/Article/details/gtipnjclwi.html

[S37] C++：set
来源：http://dali.yuxming.cn/Article/details/gtoixgeirk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.mhx1999.top/Article/details/gtxagctrpi.html

[S38] C++：排序
来源：http://dali.zhongyouzk.top/Article/details/gtaehcyjxu.html

std::sort(v.begin(), v.end());
来源：http://dali.wangshuangyany.cn/Article/details/gtpgartmne.html

[S39] C++：自定义比较器排序
来源：http://dali.jqgfzy.top/Article/details/gtttelhxdd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hongshengwenyu.top/Article/details/gtmcxqhmjh.html

[S40] C++：查找元素
来源：http://dali.guowangkeji.top/Article/details/gtpirksyvv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jianghu66.top/Article/details/gtztcktknt.html

[S41] C++：类与构造函数
来源：http://dali.hfpthk.cn/Article/details/gtxgqvpxsk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.gotoacloud.top/Article/details/gtsvkkggml.html

[S42] C++：继承与虚函数
来源：http://dali.yanxiufei.cn/Article/details/gtdjdmrjkc.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gtlyvrkhsg.html

[S43] C++：智能指针
来源：http://dali.0kj1m.cn/Article/details/gtiiuivcgq.html

auto p = std::make_unique<int>(5);
来源：http://dali.yj202588.top/Article/details/gtridbjmzb.html

[S44] C++：引用传参
来源：http://dali.daxiang520.top/Article/details/gtfgtrnjtn.html

void inc(int &x) { ++x; }
来源：http://dali.sysykeji.top/Article/details/gtnrtqdysa.html

[S45] C++：lambda
来源：http://dali.jyoumei.cn/Article/details/gtanogqmca.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yj202588.top/Article/details/gtjuosmall.html

[S46] C++：函数模板
来源：http://dali.gotoacloud.top/Article/details/gtjhijlpfw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtfkjpvlmy.html

[S47] C++：结构化绑定遍历
来源：http://dali.guannengcc.top/Article/details/gtfbgkqttf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhiwuduotai.top/Article/details/gtsziutwey.html

[S48] C++：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gtdwabxdom.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinqigfzy.top/Article/details/gtxlnvkkkr.html

while (std::getline(in, line)) { }
来源：http://dali.jiagoushi.top/Article/details/gtqfxvzfax.html

[S49] C++：写文件
来源：http://dali.xuanzx.com/Article/details/gtxevmikmy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.wangdashe.top/Article/details/gtrtqlcuve.html

[S50] C++：格式化数字
来源：http://dali.ybcxt.top/Article/details/gtbeoltlgl.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hywenlv.cn/Article/details/gtrxlbkyvh.html

[S51] C++：显式类型转换
来源：http://dali.cdnleiting.top/Article/details/gtyhrrmcso.html

static_cast<double>(a) / b
来源：http://dali.jianghu66.top/Article/details/gtcqggsnid.html

[S52] C++：const 与 noexcept
来源：http://dali.xylfe.cn/Article/details/gtausntigq.html

int size() const noexcept { return n_; }
来源：http://dali.cheryme.top/Article/details/gtnkmbcbyz.html

[S53] C++：移动语义
来源：http://dali.ppjwa.cn/Article/details/gtvcefkflg.html

std::vector<int> w = std::move(v);
来源：http://dali.quarkkingdee.top/Article/details/gteklopesl.html

[S54] C++：异常处理
来源：http://dali.tianlin.xyz/Article/details/gtomhfyqcp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sxryk.cn/Article/details/gtippponre.html

[S55] C++：结构化绑定
来源：http://dali.dashuyun.cn/Article/details/gtiytefoqi.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zycfv.cn/Article/details/gtwwmawcrh.html

[S56] C++：optional
来源：http://dali.pengpengdd.cyou/Article/details/gtcsszeeoc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sufxvd.cn/Article/details/gterzxyyac.html

[S57] C++：编译期常量
来源：http://dali.zhongyouzk.top/Article/details/gtlfskhuyf.html

constexpr int N = 10;
来源：http://dali.haohaochexian.top/Article/details/gtkpierxbi.html

[S58] C++：命名空间
来源：http://dali.cucudq.cn/Article/details/gtapsampab.html

namespace ns { int f() { return 1; } }
来源：http://dali.aizwys.cn/Article/details/gtokaaazxu.html

[S59] C++：静态断言
来源：http://dali.bjfxy.top/Article/details/gtiiaggvfl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.andypj.xyz/Article/details/gtfgdidjbd.html

[S60] C++：遍历并删除元素
来源：http://dali.cucudq.cn/Article/details/gtefwokcbi.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jyoumei.cn/Article/details/gtbhpppxxs.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtbyolyhoh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hnxiangtu.top/Article/details/gtixvvetbc.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtsjiagtwp.html

[T01] Kotlin：Hello World
来源：http://dali.hywenlv.cn/Article/details/gthofosmhn.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gtztztcmnz.html

[T02] Kotlin：变量
来源：http://dali.sysykeji.top/Article/details/gtheartfuc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yj202588.top/Article/details/gtdsjjfrle.html

[T03] Kotlin：字符串模板
来源：http://dali.daxiang520.top/Article/details/gtmngbdhrq.html

"值: $b"
来源：http://dali.aizwys.cn/Article/details/gtkejvnjrp.html

[T04] Kotlin：空安全
来源：http://dali.havefunace.top/Article/details/gthhvrqqiu.html

val n: String? = null;  n?.length
来源：http://dali.ppjwa.cn/Article/details/gtdyfyggtb.html

[T05] Kotlin：when 表达式
来源：http://dali.jiagoushi.top/Article/details/gtaxtjgxwg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.chenzaomai.com/Article/details/gtcdlweraj.html

[T06] Kotlin：集合映射
来源：http://dali.hysaishi.cn/Article/details/gtimoowkjb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yongpay.top/Article/details/gtorekowcm.html

[T07] Kotlin：集合过滤
来源：http://dali.meibo888.top/Article/details/gtunpjnotz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cashguo.top/Article/details/gtdifodsjw.html

[T08] Kotlin：数据类
来源：http://dali.jqgfzy.top/Article/details/gtqinwbzqi.html

data class User(val name: String, val age: Int)
来源：http://dali.dianchejie.cn/Article/details/gtcanfyqzg.html

[T09] Kotlin：扩展函数
来源：http://dali.hywenlv.cn/Article/details/gtxhuhvylg.html

fun String.exclaim() = this + "!"
来源：http://dali.hysaishi.cn/Article/details/gtnphggmjy.html

[T10] Kotlin：默认参数
来源：http://dali.c1oappe.top/Article/details/gtgyjxnnwf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.wangdashe.top/Article/details/gtftcdwzfm.html

[T11] Kotlin：协程
来源：http://dali.gzhubu.top/Article/details/gtieqvioiw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.aizwys.cn/Article/details/gtidafnonh.html

[T12] Kotlin：解构声明
来源：http://dali.shzxlz.cn/Article/details/gtgrlvaoma.html

val (a, b) = Pair(1, 2)
来源：http://dali.ppjwa.cn/Article/details/gtjobxuxzd.html

[T13] Kotlin：只读 Map
来源：http://dali.xinyue.icu/Article/details/gtaqudkxrs.html

val m = mapOf("a" to 1)
来源：http://dali.chenzaomai.com/Article/details/gtmsdifrev.html

[T14] Kotlin：循环
来源：http://dali.zhixingplan.top/Article/details/gtlnxeyoug.html

for (i in 1..10) println(i)
来源：http://dali.pycfn.com/Article/details/gtwgbsywlq.html

[T15] Kotlin：接口
来源：http://dali.pengpengdd.cyou/Article/details/gtdkadufqt.html

interface Shape { fun area(): Double }
来源：http://dali.zhoulong.xyz/Article/details/gtmxbxcvue.html

[T16] Swift：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtqlkzpynt.html

print("Hello")
来源：http://dali.tanke756.top/Article/details/gtxujwldzu.html

[T17] Swift：变量与常量
来源：http://dali.zhongyouzk.top/Article/details/gtgxhmxlyh.html

var a = 1;  let b = 2
来源：http://dali.sysykeji.top/Article/details/gtmummnknp.html

[T18] Swift：字符串插值
来源：http://dali.shangyingyoupin.top/Article/details/gtwrtiyoed.html

"值: \(b)"
来源：http://dali.yj20258.top/Article/details/gtnzpwzdcv.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gtpvvnixft.html

if let n = opt { print(n) }
来源：http://dali.guowangkeji.top/Article/details/gtwpvulfes.html

[T20] Swift：数组操作
来源：http://dali.andypj.xyz/Article/details/gtjlzlkdnd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.sufxvd.cn/Article/details/gtrgrbgrez.html

[T21] Swift：遍历
来源：http://dali.redwolf501.top/Article/details/gttynybwho.html

for x in a { print(x) }
来源：http://dali.jyoumei.cn/Article/details/gtxzcwgalc.html

[T22] Swift：字典
来源：http://dali.zhixingplan.top/Article/details/gtpgxkaydh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cheryme.top/Article/details/gtwolyetgb.html

[T23] Swift：函数
来源：http://dali.hongshengwenyu.top/Article/details/gttdqsxrpf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yueranfly.top/Article/details/gtvwbimvkm.html

[T24] Swift：闭包
来源：http://dali.wangdashe.top/Article/details/gtjexnedbz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xziqi.cn/Article/details/gtypxnadbs.html

[T25] Swift：结构体
来源：http://dali.jlsjyb.cn/Article/details/gttbmpzzdq.html

struct P { var x: Int }
来源：http://dali.gaohongyu789.top/Article/details/gtjlbkxcvr.html

[T26] Swift：类与重写
来源：http://dali.xinyue.icu/Article/details/gtodulrnjm.html

class A: Base { override func f() {} }
来源：http://dali.sxryk.cn/Article/details/gtafmxetfx.html

[T27] Swift：错误处理
来源：http://dali.zhiwuduotai.top/Article/details/gtxdyqmccm.html

do { try f() } catch { print(error) }
来源：http://dali.snrcjt.cn/Article/details/gtgwmbczpc.html

[T28] Swift：枚举
来源：http://dali.yueranfly.top/Article/details/gtlpujvxqh.html

enum Color { case red, green }
来源：http://dali.hnxiangtu.top/Article/details/gtlbhrdmow.html

[T29] Swift：guard 提前返回
来源：http://dali.daria6918.cn/Article/details/gtarnwhrsr.html

guard let x = opt else { return }
来源：http://dali.shangyingyoupin.top/Article/details/gtwokbirwf.html

[T30] Swift：协议
来源：http://dali.cheryme.top/Article/details/gtbbiobhtl.html

protocol Shape { func area() -> Double }
来源：http://dali.yonumen.top/Article/details/gtfzeuljuq.html

[T31] Lua：Hello World
来源：http://dali.meibo888.top/Article/details/gttgimxbia.html

print("Hello")
来源：http://dali.mhx1999.top/Article/details/gtckzzzllw.html

[T32] Lua：局部变量
来源：http://dali.zhongyouzk.top/Article/details/gtrofzfzjs.html

local a = 1
来源：http://dali.gzhubu.top/Article/details/gtodosebas.html

[T33] Lua：表（数组）
来源：http://dali.hongshengwenyu.top/Article/details/gtcqbuobsr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shzxlz.cn/Article/details/gtxfmaxjlq.html

[T34] Lua：遍历表
来源：http://dali.9152youxi.cn/Article/details/gthtbdlfon.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hnxiangtu.top/Article/details/gtgqczjacn.html

[T35] Lua：字典表
来源：http://dali.zhiwuduotai.top/Article/details/gtuumbtbng.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhengqikj.top/Article/details/gtndkshkxz.html

[T36] Lua：函数
来源：http://dali.vqdsnc.cn/Article/details/gthowyxeth.html

function add(a, b) return a + b end
来源：http://dali.hysaishi.cn/Article/details/gtgljaalmh.html

[T37] Lua：字符串拼接
来源：http://dali.xylfe.cn/Article/details/gtvkabylfh.html

"a" .. "b"
来源：http://dali.quarkkingdee.top/Article/details/gtgyvltvvv.html

[T38] Lua：条件
来源：http://dali.hywenlv.cn/Article/details/gtrexqqcdo.html

if x > 0 then print("正") end
来源：http://dali.meibo888.top/Article/details/gteecwxqba.html

[T39] Lua：模式匹配
来源：http://dali.iojbl.cn/Article/details/gtcrnskgit.html

string.find(s, "%d+")
来源：http://dali.mhx1999.top/Article/details/gtoejhhpye.html

[T40] Lua：元表
来源：http://dali.tianlin.xyz/Article/details/gtutaiusvn.html

setmetatable({}, { __index = base })
来源：http://dali.dashuyun.cn/Article/details/gtynpasuyp.html

[T41] Perl：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfupaplhi.html

print "Hello\n";
来源：http://dali.haohaochexian.top/Article/details/gteaqktptq.html

[T42] Perl：变量类型
来源：http://dali.dianchejie.cn/Article/details/gtjnbssbih.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.tianlin.xyz/Article/details/gtfulrhgql.html

[T43] Perl：字符串插值
来源：http://dali.gogol.net.cn/Article/details/gtobqsqhqu.html

"值: $a"
来源：http://dali.mhx1999.top/Article/details/gtxzenkcml.html

[T44] Perl：条件
来源：http://dali.iojbl.cn/Article/details/gtfifegnue.html

if ($a > 0) { print "正"; }
来源：http://dali.yongpay.top/Article/details/gtqhqrenil.html

[T45] Perl：数组遍历
来源：http://dali.zycfv.cn/Article/details/gtjujxxjlu.html

for my $x (@arr) { print $x; }
来源：http://dali.yuanzhike.top/Article/details/gtlbpxuylt.html

[T46] Perl：哈希操作
来源：http://dali.ppjwa.cn/Article/details/gtrtnkpobh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.nanxuanxn.top/Article/details/gtsagycmne.html

[T47] Perl：正则捕获
来源：http://dali.hysaishi.cn/Article/details/gtftmstzpc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xziqi.cn/Article/details/gtttrtkats.html

[T48] Perl：正则替换
来源：http://dali.jqgfzy.top/Article/details/gtxraejsxm.html

$s =~ s/old/new/g;
来源：http://dali.gaohongyu789.top/Article/details/gtvoivvxkl.html

[T49] Perl：函数
来源：http://dali.yj202588.top/Article/details/gtrxymqcbc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.nwbrower.top/Article/details/gtsslnnljc.html

[T50] Perl：逐行读文件
来源：http://dali.zhixingplan.top/Article/details/gtzgyvhkoo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.316326.xyz/Article/details/gtxtkrpguu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yonumen.top/Article/details/gtawqqjclo.html

[T51] Scala：Hello World
来源：http://dali.yongpay.top/Article/details/gtlzjulxun.html

println("Hello")
来源：http://dali.guowangkeji.top/Article/details/gthwxgcjss.html

[T52] Scala：变量
来源：http://dali.hywenlv.cn/Article/details/gtebmhtwve.html

val a = 1;  var b = 2
来源：http://dali.chenlongwang.top/Article/details/gtkofxxecb.html

[T53] Scala：字符串插值
来源：http://dali.yongpay.top/Article/details/gttaaxhqvd.html

s"值: $b"
来源：http://dali.zhongyouzk.top/Article/details/gtsfcbsesa.html

[T54] Scala：集合映射
来源：http://dali.svipenyu.cn/Article/details/gtdlivvvzk.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.wangdashe.top/Article/details/gttmawcwmq.html

[T55] Scala：集合过滤
来源：http://dali.sxryk.cn/Article/details/gtpltyzcth.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.gotoacloud.top/Article/details/gtmdhsbyzd.html

[T56] Scala：样例类
来源：http://dali.birdmap.top/Article/details/gtfnfvjyhh.html

case class User(name: String, age: Int)
来源：http://dali.nwbrower.top/Article/details/gtkyqasjsi.html

[T57] Scala：模式匹配
来源：http://dali.tian-w.cn/Article/details/gtbvsbgecf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhengqikj.top/Article/details/gtvbellksf.html

[T58] Scala：函数定义
来源：http://dali.cdnleiting.top/Article/details/gtoohpleyc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.quarkkingdee.top/Article/details/gtsoyalchr.html

[T59] Scala：循环
来源：http://dali.shuidangran.top/Article/details/gtzglficby.html

for (i <- 1 to 10) println(i)
来源：http://dali.yuxming.cn/Article/details/gtbodvwtry.html

[T60] Scala：折叠
来源：http://dali.9152youxi.cn/Article/details/gtgovrddem.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.ehwqpu.com/Article/details/gtwyveocld.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtykndhxqp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.pycfn.com/Article/details/gtyvecsdeg.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtjcrjcbwh.html

[U01] Py：创建虚拟环境
来源：http://dali.gzhubu.top/Article/details/gtisdcejil.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.sufxvd.cn/Article/details/gtprksmheb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.gzhubu.top/Article/details/gtbhqbmoka.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.dianchejie.cn/Article/details/gtkknqbbqq.html


<!-- 参考信息 -->