代发 wailian999

df -h;  du -sh *
来源：http://dali.jinqigfzy.top/Article/details/gtakqzfhyy.html

[R62] 找最占空间的文件
来源：http://dali.hammf.cn/Article/details/gtvrkixtrr.html

du -ah . | sort -rh | head -10
来源：http://dali.nanxuanxn.top/Article/details/gtqswdzcnd.html

[R63] 内存与进程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtshlpmnpd.html

free -h;  ps aux | grep nginx
来源：http://dali.jianghu66.top/Article/details/gtymguzrmj.html

[R64] 结束进程
来源：http://dali.sweek.top/Article/details/gtetuvwlju.html

kill -9 $(pgrep -f app.py)
来源：http://dali.vqdsnc.cn/Article/details/gtmudwrkcr.html

[R65] 查看端口占用
来源：http://dali.yangfankeji.com/Article/details/gttvqluolv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jinqigufen.top/Article/details/gtgcqkqmhp.html

[R66] 定时任务
来源：http://dali.feifeiyinyue.top/Article/details/gtouypajfr.html

crontab -e;  crontab -l
来源：http://dali.gzhubu.top/Article/details/gtbkikqaut.html

[R67] 生成随机十六进制串
来源：http://dali.svipenyu.cn/Article/details/gtjrwzuyga.html

openssl rand -hex 16
来源：http://dali.aizwys.cn/Article/details/gtphhtbwbs.html

[R68] 计算文件校验值
来源：http://dali.zdqjudy.top/Article/details/gtkstiqxwy.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtavihztto.html

[R69] 生成随机密码
来源：http://dali.xuanzx.com/Article/details/gtoumowdgz.html

head -c 16 /dev/urandom | base64
来源：http://dali.9152youxi.cn/Article/details/gtkahijqsj.html

[R70] 时间戳与互转
来源：http://dali.sweek.top/Article/details/gtekqcqihf.html

date +%s;  date -d @1700000000
来源：http://dali.0kj1m.cn/Article/details/gtbgdeqkan.html

[R71] 日期格式化
来源：http://dali.daxiang520.top/Article/details/gtsjzoqdtn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gzhubu.top/Article/details/gtvmtauuan.html

[R72] 等待端口就绪
来源：http://dali.9152youxi.cn/Article/details/gthmxtoysh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yueranfly.top/Article/details/gtzqltsayy.html

[R73] 分割大日志
来源：http://dali.hysaishi.cn/Article/details/gtwvlbtbtq.html

split -l 1000 big.log part_
来源：http://dali.shanyushiyangtech.top/Article/details/gtfkdpggmt.html

[R74] 批量重命名
来源：http://dali.wangshuangyany.cn/Article/details/gtsgjnpvjm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sweek.top/Article/details/gtvjofzhvt.html

[R75] 导出环境变量
来源：http://dali.yonumen.top/Article/details/gtszqwrnmy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.pengpengdd.cyou/Article/details/gtxyzvpubx.html

[R76] 使用临时文件
来源：http://dali.yj20258.top/Article/details/gttdmdoltt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yongpay.top/Article/details/gtzgqxfyvi.html

[R77] 读取用户输入
来源：http://dali.zhixingplan.top/Article/details/gtfviealns.html

read -rp "请输入: " ans
来源：http://dali.pycfn.com/Article/details/gttuvowlit.html

[R78] 交互式菜单
来源：http://dali.pycfn.com/Article/details/gttbucyaly.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hnqzz.top/Article/details/gthlsnbuss.html

[R79] 解析命令行选项
来源：http://dali.tian-w.cn/Article/details/gtuayrxvtf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yvedp.cn/Article/details/gtzxcfqyvk.html

[R80] 查看脚本执行耗时
来源：http://dali.fzhhl.top/Article/details/gthrlqwjrr.html

time ./run.sh
来源：http://dali.daria6918.cn/Article/details/gtsshhamle.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtmucbdncj.html

S. C / C++ 专题
来源：http://dali.jlsjyb.cn/Article/details/gtqxsqqvve.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gttbqsmbqe.html

[S01] C：Hello World
来源：http://dali.c1oappe.top/Article/details/gtwrxgypxg.html

#include <stdio.h>
来源：http://dali.yanxiufei.cn/Article/details/gtqooydtyr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.iojbl.cn/Article/details/gtbswuyokj.html

[S02] C：变量与格式化输出
来源：http://dali.daria6918.cn/Article/details/gtckxvgclh.html

int a = 10; printf("%d\n", a);
来源：http://dali.feifeiyinyue.top/Article/details/gthewwoktr.html

[S03] C：读入整数
来源：http://dali.mhx1999.top/Article/details/gtfepoapqi.html

int x; scanf("%d", &x);
来源：http://dali.yvedp.cn/Article/details/gtweakbbgh.html

[S04] C：字符串复制
来源：http://dali.jlsjyb.cn/Article/details/gtakyywpwr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhoulong.xyz/Article/details/gtlfrvqodk.html

[S05] C：字符串长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuchbewao.html

strlen(s)
来源：http://dali.guowangkeji.top/Article/details/gtqgjzkhne.html

[S06] C：字符串比较
来源：http://dali.xinyue.icu/Article/details/gtqqshzmew.html

strcmp(a, b) == 0
来源：http://dali.vqdsnc.cn/Article/details/gtcphljolq.html

[S07] C：数组遍历求和
来源：http://dali.zycfv.cn/Article/details/gthdukkkqm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yuxming.cn/Article/details/gtbpayafdk.html

[S08] C：动态内存分配与释放
来源：http://dali.feifeiyinyue.top/Article/details/gtfoqtsadj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jlsjyb.cn/Article/details/gtzsfnwilc.html

[S09] C：结构体定义与初始化
来源：http://dali.fengsongda.top/Article/details/gtnunvxnty.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.wangdashe.top/Article/details/gtnfbansnl.html

[S10] C：指针与解引用
来源：http://dali.zhengqikj.top/Article/details/gtauvvoeqh.html

int *p = &a;  *p = 5;
来源：http://dali.yj202588.top/Article/details/gtvtcxrjgc.html

[S11] C：逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyexbyldj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.birdmap.top/Article/details/gtxxmymgcd.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.0kj1m.cn/Article/details/gtuatiiuiw.html

fclose(f);
来源：http://dali.gotoacloud.top/Article/details/gtfjsvwatg.html

[S12] C：写文件
来源：http://dali.zhixingplan.top/Article/details/gtwrjczikt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhoulong.xyz/Article/details/gtlqkkdheh.html

[S13] C：宏定义
来源：http://dali.jinghuilouyu.cn/Article/details/gtaejariyz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.fengsongda.top/Article/details/gtjhljcdur.html

[S14] C：枚举
来源：http://dali.redwolf501.top/Article/details/gtrfqgpscy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gaohongyu789.top/Article/details/gtcexcuwjv.html

[S15] C：类型转换
来源：http://dali.hammf.cn/Article/details/gtvftmfvll.html

(double) a / b
来源：http://dali.zhaomingkeji.xyz/Article/details/gteyrbsyjg.html

[S16] C：位操作置位
来源：http://dali.quarkkingdee.top/Article/details/gtuxgkbgwv.html

x |= (1 << 3);
来源：http://dali.cucudq.cn/Article/details/gtksjbujig.html

[S17] C：安全拼接字符串
来源：http://dali.shuidangran.top/Article/details/gtivvdcgvl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shuidangran.top/Article/details/gtubudvaiz.html

[S18] C：命令行参数
来源：http://dali.quarkkingdee.top/Article/details/gtqmxqztcg.html

int main(int argc, char **argv)
来源：http://dali.mhx1999.top/Article/details/gtnkgckkqe.html

[S19] C：快速排序
来源：http://dali.yonumen.top/Article/details/gtkrbtrbey.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yanxiufei.cn/Article/details/gtzuuojzcz.html

[S20] C：二分查找
来源：http://dali.yangfankeji.com/Article/details/gtjatxafpn.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.kuanghao11.cn/Article/details/gtmjxkeikw.html

[S21] C：字符类别判断
来源：http://dali.jinqigufen.top/Article/details/gtapvcgfxa.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yueranfly.top/Article/details/gtzjtqeauv.html

[S22] C：字符串转数字
来源：http://dali.yj20258.top/Article/details/gtjbkmpcik.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.nanxuanxn.top/Article/details/gtlkejmmek.html

[S23] C：随机数
来源：http://dali.hnqzz.top/Article/details/gtpmrizryl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yuanzhike.top/Article/details/gtslqrzucp.html

[S24] C：获取本地时间
来源：http://dali.sysykeji.top/Article/details/gtonlpdpwu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.feifeiyinyue.top/Article/details/gtfctehmai.html

[S25] C：内存拷贝
来源：http://dali.birdmap.top/Article/details/gtlsiahexr.html

memcpy(dst, src, n);
来源：http://dali.tianlin.xyz/Article/details/gtwlvolkgg.html

[S26] C：内存清零
来源：http://dali.smart0.xyz/Article/details/gtmjytnfst.html

memset(a, 0, sizeof a);
来源：http://dali.zdqjudy.top/Article/details/gtmuuxuxnv.html

[S27] C：定义常量
来源：http://dali.shzxlz.cn/Article/details/gtpgqspyyc.html

const double PI = 3.14159;
来源：http://dali.ivvv.top/Article/details/gtpulsitru.html

[S28] C：静态变量
来源：http://dali.fzhhl.top/Article/details/gttpdmwjeo.html

static int counter = 0;
来源：http://dali.iojbl.cn/Article/details/gtjwpcaftt.html

[S29] C：变参函数
来源：http://dali.yvedp.cn/Article/details/gtdtodyker.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gotoacloud.top/Article/details/gtkbdzlwof.html

[S30] C：头文件保护
来源：http://dali.hnxiangtu.top/Article/details/gtytbjeewb.html

#ifndef X_H
来源：http://dali.yongpay.top/Article/details/gtdecajjld.html

#define X_H
来源：http://dali.pycfn.com/Article/details/gtahxxjadm.html

#endif
来源：http://dali.pycfn.com/Article/details/gtwwcvuwdi.html

[S31] C++：Hello World
来源：http://dali.daxiang520.top/Article/details/gtsqesmxjt.html

#include <iostream>
来源：http://dali.yj20258888.top/Article/details/gtjapnnvlr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.wangdashe.top/Article/details/gtnypyduvu.html

[S32] C++：字符串
来源：http://dali.sufxvd.cn/Article/details/gtnjlfasen.html

std::string s = "hi";  s += "!";
来源：http://dali.yvedp.cn/Article/details/gtwtfjskec.html

[S33] C++：vector 增删
来源：http://dali.ppjwa.cn/Article/details/gtkmrkkuli.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yj20258.top/Article/details/gtakzpmbdp.html

[S34] C++：遍历 vector
来源：http://dali.cashguo.top/Article/details/gthtqeadpw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yangfankeji.com/Article/details/gtmoqijicg.html

[S35] C++：map
来源：http://dali.jyoumei.cn/Article/details/gtbzfiarlm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwwnwlneq.html

[S36] C++：unordered_map
来源：http://dali.sysykeji.top/Article/details/gtqfevfsgw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtqrnitevk.html

[S37] C++：set
来源：http://dali.wangdashe.top/Article/details/gtyfxdisgc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cucudq.cn/Article/details/gtcoqkulrm.html

[S38] C++：排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmiaynsqf.html

std::sort(v.begin(), v.end());
来源：http://dali.fzhhl.top/Article/details/gtlndkiifl.html

[S39] C++：自定义比较器排序
来源：http://dali.hnxiangtu.top/Article/details/gtszepvybt.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jiagoushi.top/Article/details/gtjlogbhko.html

[S40] C++：查找元素
来源：http://dali.chenzaomai.com/Article/details/gtuoyejhuz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jqgufenzy.top/Article/details/gtwfwpnelm.html

[S41] C++：类与构造函数
来源：http://dali.fzhhl.top/Article/details/gtmvsnunjr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cheryme.top/Article/details/gtbswmrgli.html

[S42] C++：继承与虚函数
来源：http://dali.dashuyun.cn/Article/details/gtnlqiiqfw.html

class B : public Base { public: void f() override {} };
来源：http://dali.shzxlz.cn/Article/details/gtpfyseild.html

[S43] C++：智能指针
来源：http://dali.yvedp.cn/Article/details/gtahhdxlpl.html

auto p = std::make_unique<int>(5);
来源：http://dali.aibaodan.cn/Article/details/gtnsoeagkd.html

[S44] C++：引用传参
来源：http://dali.haohaochexian.top/Article/details/gtputgcrwl.html

void inc(int &x) { ++x; }
来源：http://dali.chenzaomai.com/Article/details/gtagkrrwqd.html

[S45] C++：lambda
来源：http://dali.zhengqikj.top/Article/details/gtxojggckg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sxryk.cn/Article/details/gtzimlxasa.html

[S46] C++：函数模板
来源：http://dali.guowangkeji.top/Article/details/gtnkyeabds.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtjbyuvzsw.html

[S47] C++：结构化绑定遍历
来源：http://dali.kuanghao11.cn/Article/details/gtxbzxogud.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cashguo.top/Article/details/gtkhhvslju.html

[S48] C++：逐行读文件
来源：http://dali.chenjidiqi.icu/Article/details/gtjfafjhre.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jiagoushi.top/Article/details/gtppqlvxra.html

while (std::getline(in, line)) { }
来源：http://dali.nanxinkj.top/Article/details/gtbnxkhlmc.html

[S49] C++：写文件
来源：http://dali.zdqjudy.top/Article/details/gtfcewkbfd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sufxvd.cn/Article/details/gtldvjakho.html

[S50] C++：格式化数字
来源：http://dali.dianchejie.cn/Article/details/gtuakhxjqp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gtppjldihj.html

[S51] C++：显式类型转换
来源：http://dali.0kj1m.cn/Article/details/gtgyoegfsm.html

static_cast<double>(a) / b
来源：http://dali.hongshengwenyu.top/Article/details/gtwtuddyfr.html

[S52] C++：const 与 noexcept
来源：http://dali.hnqzz.top/Article/details/gteieopxrl.html

int size() const noexcept { return n_; }
来源：http://dali.aizwys.cn/Article/details/gtjjbmrnpn.html

[S53] C++：移动语义
来源：http://dali.jqgufenzy.top/Article/details/gtfcgrryyy.html

std::vector<int> w = std::move(v);
来源：http://dali.haohaochexian.top/Article/details/gtgsetajaq.html

[S54] C++：异常处理
来源：http://dali.yueranfly.top/Article/details/gtkfwhhivi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.snrcjt.cn/Article/details/gtbxxhonrx.html

[S55] C++：结构化绑定
来源：http://dali.kuanghao11.cn/Article/details/gtvrwerfzq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yvedp.cn/Article/details/gtciyvzhrr.html

[S56] C++：optional
来源：http://dali.9152youxi.cn/Article/details/gtkbvhztro.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jianghu66.top/Article/details/gtdlopusyb.html

[S57] C++：编译期常量
来源：http://dali.jyoumei.cn/Article/details/gtefutvxca.html

constexpr int N = 10;
来源：http://dali.haohaochexian.top/Article/details/gtrwdvdtrt.html

[S58] C++：命名空间
来源：http://dali.cheryme.top/Article/details/gtyufjfwhb.html

namespace ns { int f() { return 1; } }
来源：http://dali.yonumen.top/Article/details/gtjxicfhac.html

[S59] C++：静态断言
来源：http://dali.hysaishi.cn/Article/details/gtkqlgofoo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.nanxuanxn.top/Article/details/gtfpnjeqvl.html

[S60] C++：遍历并删除元素
来源：http://dali.xuetiantiany.cn/Article/details/gtxowkmaxm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.havefunace.top/Article/details/gtfzudtymq.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gturlsgwul.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cqqwz.cn/Article/details/gtusprqpwm.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtgjmmxpab.html

[T01] Kotlin：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtcgrfwlbe.html

println("Hello")
来源：http://dali.redwolf501.top/Article/details/gtaxisxtzx.html

[T02] Kotlin：变量
来源：http://dali.sufxvd.cn/Article/details/gtkydtxtij.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yj202588.top/Article/details/gtnbovmhoz.html

[T03] Kotlin：字符串模板
来源：http://dali.kuanghao11.cn/Article/details/gtmwxoctdp.html

"值: $b"
来源：http://dali.yongpay.top/Article/details/gtgpfxtnho.html

[T04] Kotlin：空安全
来源：http://dali.iojbl.cn/Article/details/gtlgkyvxwh.html

val n: String? = null;  n?.length
来源：http://dali.tian-w.cn/Article/details/gtehhimesx.html

[T05] Kotlin：when 表达式
来源：http://dali.zdqjudy.top/Article/details/gtsbizuhpv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.haohaochexian.top/Article/details/gtegazahwl.html

[T06] Kotlin：集合映射
来源：http://dali.jyoumei.cn/Article/details/gtstvayfir.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.nwbrower.top/Article/details/gtztydextm.html

[T07] Kotlin：集合过滤
来源：http://dali.meibo888.top/Article/details/gtexhowtcg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gogol.net.cn/Article/details/gtnuxopire.html

[T08] Kotlin：数据类
来源：http://dali.jqgfzy.top/Article/details/gttcbtbxzm.html

data class User(val name: String, val age: Int)
来源：http://dali.dashuyun.cn/Article/details/gtfqelipvo.html

[T09] Kotlin：扩展函数
来源：http://dali.zycfv.cn/Article/details/gtdarxtqdt.html

fun String.exclaim() = this + "!"
来源：http://dali.hysaishi.cn/Article/details/gtsejwpyjb.html

[T10] Kotlin：默认参数
来源：http://dali.9152youxi.cn/Article/details/gtvwnifepc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.mhx1999.top/Article/details/gtyspkxxfg.html

[T11] Kotlin：协程
来源：http://dali.chenlongwang.top/Article/details/gtgpjhaeih.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.snrcjt.cn/Article/details/gtfgishjad.html

[T12] Kotlin：解构声明
来源：http://dali.jiagoushi.top/Article/details/gtnenzhisk.html

val (a, b) = Pair(1, 2)
来源：http://dali.c1oappe.top/Article/details/gtkiweuvzs.html

[T13] Kotlin：只读 Map
来源：http://dali.snrcjt.cn/Article/details/gtbyxevmkw.html

val m = mapOf("a" to 1)
来源：http://dali.yongpay.top/Article/details/gterjejvwy.html

[T14] Kotlin：循环
来源：http://dali.jqgfzy.top/Article/details/gtqkncaefh.html

for (i in 1..10) println(i)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnbwffexd.html

[T15] Kotlin：接口
来源：http://dali.jinqigfzy.top/Article/details/gtbfrygyco.html

interface Shape { fun area(): Double }
来源：http://dali.jlsjyb.cn/Article/details/gteftfhmmx.html

[T16] Swift：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gtgzdkyfju.html

print("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gtwgbujulb.html

[T17] Swift：变量与常量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthfwftjxw.html

var a = 1;  let b = 2
来源：http://dali.hysaishi.cn/Article/details/gtvnaadtpi.html

[T18] Swift：字符串插值
来源：http://dali.kuanghao11.cn/Article/details/gthkyiqjre.html

"值: \(b)"
来源：http://dali.nwbrower.top/Article/details/gtavcsynfb.html

[T19] Swift：可选绑定
来源：http://dali.yangfankeji.com/Article/details/gtsxhoqkia.html

if let n = opt { print(n) }
来源：http://dali.yj20258.top/Article/details/gtcrvvnuai.html

[T20] Swift：数组操作
来源：http://dali.ppjwa.cn/Article/details/gtemybhhqa.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdrvcoxys.html

[T21] Swift：遍历
来源：http://dali.hammf.cn/Article/details/gtvuzszqsl.html

for x in a { print(x) }
来源：http://dali.fzhhl.top/Article/details/gtqzopzuzh.html

[T22] Swift：字典
来源：http://dali.xziqi.cn/Article/details/gtqhtmqssn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.nanxinkj.top/Article/details/gtgwcyiwnr.html

[T23] Swift：函数
来源：http://dali.0kj1m.cn/Article/details/gtxzwhufln.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jianghu66.top/Article/details/gtsakpeibo.html

[T24] Swift：闭包
来源：http://dali.yuanzhike.top/Article/details/gtpdksshdl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yj20258.top/Article/details/gtfdwndapu.html

[T25] Swift：结构体
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwgpziwue.html

struct P { var x: Int }
来源：http://dali.jqgfzy.top/Article/details/gtyretasst.html

[T26] Swift：类与重写
来源：http://dali.zhixingplan.top/Article/details/gtrsxaazvj.html

class A: Base { override func f() {} }
来源：http://dali.snrcjt.cn/Article/details/gtkewysagm.html

[T27] Swift：错误处理
来源：http://dali.bjfxy.top/Article/details/gtvlhqoqnu.html

do { try f() } catch { print(error) }
来源：http://dali.xuanzx.com/Article/details/gtpodixvcv.html

[T28] Swift：枚举
来源：http://dali.cqqwz.cn/Article/details/gtjnraoqsn.html

enum Color { case red, green }
来源：http://dali.cdnleiting.top/Article/details/gtszvqhdng.html

[T29] Swift：guard 提前返回
来源：http://dali.shanyushiyangtech.top/Article/details/gtafddwrkt.html

guard let x = opt else { return }
来源：http://dali.gzhubu.top/Article/details/gtfdxvpnjo.html

[T30] Swift：协议
来源：http://dali.jiagoushi.top/Article/details/gtoezjqrin.html

protocol Shape { func area() -> Double }
来源：http://dali.haohaochexian.top/Article/details/gtcaslcnkv.html

[T31] Lua：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtmuwpckaw.html

print("Hello")
来源：http://dali.chenlongwang.top/Article/details/gtylzrooob.html

[T32] Lua：局部变量
来源：http://dali.hfpthk.cn/Article/details/gtamszwcel.html

local a = 1
来源：http://dali.hysaishi.cn/Article/details/gtkstwcgyg.html

[T33] Lua：表（数组）
来源：http://dali.gotoacloud.top/Article/details/gttuziugsc.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.kuanghao11.cn/Article/details/gtnrzrtsek.html

[T34] Lua：遍历表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtopudjjpd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.iojbl.cn/Article/details/gtaayskhvh.html

[T35] Lua：字典表
来源：http://dali.wangdashe.top/Article/details/gtzhzqtesl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.wangdashe.top/Article/details/gtfkfzpsxe.html

[T36] Lua：函数
来源：http://dali.9152youxi.cn/Article/details/gtiupfmivy.html

function add(a, b) return a + b end
来源：http://dali.nanxinkj.top/Article/details/gtguluvecl.html

[T37] Lua：字符串拼接
来源：http://dali.bjfxy.top/Article/details/gtbkybscuz.html

"a" .. "b"
来源：http://dali.daxiang520.top/Article/details/gttfrxokmz.html

[T38] Lua：条件
来源：http://dali.sysykeji.top/Article/details/gtqinxpcix.html

if x > 0 then print("正") end
来源：http://dali.haohaochexian.top/Article/details/gtswrnecdj.html

[T39] Lua：模式匹配
来源：http://dali.c1oappe.top/Article/details/gtenctbgot.html

string.find(s, "%d+")
来源：http://dali.cqqwz.cn/Article/details/gtbxckdlgk.html

[T40] Lua：元表
来源：http://dali.hnqzz.top/Article/details/gtsdzhfhao.html

setmetatable({}, { __index = base })
来源：http://dali.cashguo.top/Article/details/gtldookeop.html

[T41] Perl：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtzlnueeso.html

print "Hello\n";
来源：http://dali.redwolf501.top/Article/details/gtvvhotghe.html

[T42] Perl：变量类型
来源：http://dali.zhiwuduotai.top/Article/details/gtxkehguhk.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ehwqpu.com/Article/details/gtjqovqnai.html

[T43] Perl：字符串插值
来源：http://dali.jyoumei.cn/Article/details/gtjsdciwnn.html

"值: $a"
来源：http://dali.chenlongwang.top/Article/details/gtubxiwkas.html

[T44] Perl：条件
来源：http://dali.yuxming.cn/Article/details/gtwrujxzqk.html

if ($a > 0) { print "正"; }
来源：http://dali.xuanzx.com/Article/details/gtzgjiieqd.html

[T45] Perl：数组遍历
来源：http://dali.cucudq.cn/Article/details/gtyilkvpil.html

for my $x (@arr) { print $x; }
来源：http://dali.andypj.xyz/Article/details/gtckllppvg.html

[T46] Perl：哈希操作
来源：http://dali.jinqigufen.top/Article/details/gtbfkepfxh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhoulong.xyz/Article/details/gtqdoxlekl.html

[T47] Perl：正则捕获
来源：http://dali.shangyingyoupin.top/Article/details/gtztabdrio.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.316326.xyz/Article/details/gtwfwaiuow.html

[T48] Perl：正则替换
来源：http://dali.jqgfzy.top/Article/details/gtalsffloa.html

$s =~ s/old/new/g;
来源：http://dali.nwbrower.top/Article/details/gtvblatrda.html

[T49] Perl：函数
来源：http://dali.chenzaomai.com/Article/details/gtitledlcl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yj20258.top/Article/details/gtrytepjxn.html

[T50] Perl：逐行读文件
来源：http://dali.ybcxt.top/Article/details/gtybrctnyk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyjcwbllg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cucudq.cn/Article/details/gtadomyvhf.html

[T51] Scala：Hello World
来源：http://dali.hfpthk.cn/Article/details/gthvwrzaje.html

println("Hello")
来源：http://dali.cdnleiting.top/Article/details/gtlenwqymu.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gtcarqnaru.html

val a = 1;  var b = 2
来源：http://dali.gotoacloud.top/Article/details/gtdzbpbmpi.html

[T53] Scala：字符串插值
来源：http://dali.bjfxy.top/Article/details/gttvwscpwi.html

s"值: $b"
来源：http://dali.gogol.net.cn/Article/details/gttjhxadoq.html

[T54] Scala：集合映射
来源：http://dali.pycfn.com/Article/details/gtnzqphjql.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jinqigufen.top/Article/details/gtqcuyyvoo.html

[T55] Scala：集合过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gtglzxohbi.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jiagoushi.top/Article/details/gtenbjyppo.html

[T56] Scala：样例类
来源：http://dali.yangfankeji.com/Article/details/gtjklmfxyt.html

case class User(name: String, age: Int)
来源：http://dali.cashguo.top/Article/details/gtpxbwxcbp.html

[T57] Scala：模式匹配
来源：http://dali.hnqzz.top/Article/details/gtgemtxpjw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.svipenyu.cn/Article/details/gtzrhyuwfo.html

[T58] Scala：函数定义
来源：http://dali.quarkkingdee.top/Article/details/gtntkghkpl.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.guannengcc.top/Article/details/gtkklvdzbc.html

[T59] Scala：循环
来源：http://dali.wangdashe.top/Article/details/gtohgystzu.html

for (i <- 1 to 10) println(i)
来源：http://dali.mhx1999.top/Article/details/gtauhvubgz.html

[T60] Scala：折叠
来源：http://dali.zhaomingkeji.xyz/Article/details/gtckwlfgkr.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sysykeji.top/Article/details/gtsbugvxiq.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtayedgzli.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.9152youxi.cn/Article/details/gtigjmseve.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtdbdokxzv.html

[U01] Py：创建虚拟环境
来源：http://dali.wangdashe.top/Article/details/gtxsqlkcmp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hammf.cn/Article/details/gtpegmsaon.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jlsjyb.cn/Article/details/gtademqvsp.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.316326.xyz/Article/details/gtjvgtzgqn.html


<!-- 参考信息 -->