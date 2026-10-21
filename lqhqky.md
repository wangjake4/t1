代发 wailian999

df -h;  du -sh *
来源：http://dali.cashguo.top/Article/details/gtpkfzhdhl.html

[R62] 找最占空间的文件
来源：http://dali.cashguo.top/Article/details/gtbcfrocbf.html

du -ah . | sort -rh | head -10
来源：http://dali.shuidangran.top/Article/details/gtdugtfbap.html

[R63] 内存与进程
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxvcjptom.html

free -h;  ps aux | grep nginx
来源：http://dali.redwolf501.top/Article/details/gtkmlpbbmw.html

[R64] 结束进程
来源：http://dali.yonumen.top/Article/details/gtpdpxokfh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yonumen.top/Article/details/gtgfwnoxhg.html

[R65] 查看端口占用
来源：http://dali.chenzaomai.com/Article/details/gtkhkabpbl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jqgfzy.top/Article/details/gtnasghcyh.html

[R66] 定时任务
来源：http://dali.jyoumei.cn/Article/details/gtungrsbis.html

crontab -e;  crontab -l
来源：http://dali.zhiwuduotai.top/Article/details/gtlldibrrr.html

[R67] 生成随机十六进制串
来源：http://dali.yj20258.top/Article/details/gtuwqnqnbu.html

openssl rand -hex 16
来源：http://dali.ydzc1.top/Article/details/gtzcqjlgot.html

[R68] 计算文件校验值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtucafyqjx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.mhx1999.top/Article/details/gtnqfkopif.html

[R69] 生成随机密码
来源：http://dali.cheryme.top/Article/details/gtyqxajlqy.html

head -c 16 /dev/urandom | base64
来源：http://dali.svipenyu.cn/Article/details/gtcmbujkxu.html

[R70] 时间戳与互转
来源：http://dali.hysaishi.cn/Article/details/gtgvfpizzq.html

date +%s;  date -d @1700000000
来源：http://dali.yj20258.top/Article/details/gtaquxalsl.html

[R71] 日期格式化
来源：http://dali.zhengqikj.top/Article/details/gtnboopvqv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xuanzx.com/Article/details/gtcdwwmyjp.html

[R72] 等待端口就绪
来源：http://dali.316326.xyz/Article/details/gtlxzjlhww.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj20258.top/Article/details/gtpbhcikti.html

[R73] 分割大日志
来源：http://dali.zdqjudy.top/Article/details/gtpnfagmbv.html

split -l 1000 big.log part_
来源：http://dali.zhengqikj.top/Article/details/gtvyafctbb.html

[R74] 批量重命名
来源：http://dali.guannengcc.top/Article/details/gtphpqipwj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hammf.cn/Article/details/gtivlwnrnn.html

[R75] 导出环境变量
来源：http://dali.chenjidiqi.icu/Article/details/gttlyplhmy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shuidangran.top/Article/details/gtauovqvcb.html

[R76] 使用临时文件
来源：http://dali.zdqjudy.top/Article/details/gtfflwcwmr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.aibaodan.cn/Article/details/gtinrgzohk.html

[R77] 读取用户输入
来源：http://dali.yanxiufei.cn/Article/details/gtvlxtfhgx.html

read -rp "请输入: " ans
来源：http://dali.guowangkeji.top/Article/details/gtunlytezr.html

[R78] 交互式菜单
来源：http://dali.yangfankeji.com/Article/details/gtmpbkpuuy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yuanzhike.top/Article/details/gtbwlvgsyp.html

[R79] 解析命令行选项
来源：http://dali.zhiwuduotai.top/Article/details/gtbtxxvlvz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.wangdashe.top/Article/details/gtqqdurleq.html

[R80] 查看脚本执行耗时
来源：http://dali.cqqwz.cn/Article/details/gtyujrfljd.html

time ./run.sh
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtimgeybzc.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtuxervapz.html

S. C / C++ 专题
来源：http://dali.jianghu66.top/Article/details/gtgewmwemq.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtveumzanx.html

[S01] C：Hello World
来源：http://dali.cashguo.top/Article/details/gthlyxcozg.html

#include <stdio.h>
来源：http://dali.dashuyun.cn/Article/details/gtxjdwgmyf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sufxvd.cn/Article/details/gtcrgaoscg.html

[S02] C：变量与格式化输出
来源：http://dali.zdqjudy.top/Article/details/gtxyuqtvqs.html

int a = 10; printf("%d\n", a);
来源：http://dali.fzhhl.top/Article/details/gtvgnzekin.html

[S03] C：读入整数
来源：http://dali.haohaochexian.top/Article/details/gtapxbrxta.html

int x; scanf("%d", &x);
来源：http://dali.meibo888.top/Article/details/gtxdnoleol.html

[S04] C：字符串复制
来源：http://dali.yj202588.top/Article/details/gtfbochsjm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gogol.net.cn/Article/details/gtdkbglsbq.html

[S05] C：字符串长度
来源：http://dali.ivvv.top/Article/details/gtlfrvvyuu.html

strlen(s)
来源：http://dali.yj202588.top/Article/details/gtxbwsgbkb.html

[S06] C：字符串比较
来源：http://dali.yangfankeji.com/Article/details/gtxiqkfyua.html

strcmp(a, b) == 0
来源：http://dali.hysaishi.cn/Article/details/gtmlulkraa.html

[S07] C：数组遍历求和
来源：http://dali.hammf.cn/Article/details/gtvoifbjfw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gogol.net.cn/Article/details/gtzhyaqhrg.html

[S08] C：动态内存分配与释放
来源：http://dali.hywenlv.cn/Article/details/gtworlxrkx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.smart0.xyz/Article/details/gtryjuuqtt.html

[S09] C：结构体定义与初始化
来源：http://dali.yvedp.cn/Article/details/gtfcxxooyq.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.tianlin.xyz/Article/details/gtjsprpdpm.html

[S10] C：指针与解引用
来源：http://dali.nanxuanxn.top/Article/details/gtilqqifxy.html

int *p = &a;  *p = 5;
来源：http://dali.dashuyun.cn/Article/details/gtwpacztal.html

[S11] C：逐行读文件
来源：http://dali.guowangkeji.top/Article/details/gtjsawhkzt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.iojbl.cn/Article/details/gtmcklypzh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shangyingyoupin.top/Article/details/gtpsabmawb.html

fclose(f);
来源：http://dali.xylfe.cn/Article/details/gtpnxknywq.html

[S12] C：写文件
来源：http://dali.yueranfly.top/Article/details/gtvdqddqjv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.daria6918.cn/Article/details/gtaupxscyo.html

[S13] C：宏定义
来源：http://dali.cqqwz.cn/Article/details/gturkopjvw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.mhx1999.top/Article/details/gtifotvwzu.html

[S14] C：枚举
来源：http://dali.hfpthk.cn/Article/details/gtnrbnjfgx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sxryk.cn/Article/details/gtsjiwrkhl.html

[S15] C：类型转换
来源：http://dali.nwbrower.top/Article/details/gtbqyfagcg.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gtchhwbswz.html

[S16] C：位操作置位
来源：http://dali.wangshuangyany.cn/Article/details/gtwvuseltv.html

x |= (1 << 3);
来源：http://dali.jinqigufen.top/Article/details/gtzfbwchjz.html

[S17] C：安全拼接字符串
来源：http://dali.nwbrower.top/Article/details/gtvnebuyqo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.wangdashe.top/Article/details/gtgswwlzvz.html

[S18] C：命令行参数
来源：http://dali.cheryme.top/Article/details/gttekpomkc.html

int main(int argc, char **argv)
来源：http://dali.zycfv.cn/Article/details/gtrgsjpigc.html

[S19] C：快速排序
来源：http://dali.xuetiantiany.cn/Article/details/gtkzkwnpgj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ybcxt.top/Article/details/gtvtrtujba.html

[S20] C：二分查找
来源：http://dali.shuidangran.top/Article/details/gtvcidjhvz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.birdmap.top/Article/details/gtouigldvv.html

[S21] C：字符类别判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrqhutrid.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yonumen.top/Article/details/gtnexzbbyz.html

[S22] C：字符串转数字
来源：http://dali.aizwys.cn/Article/details/gtcguhablj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.meibo888.top/Article/details/gtrtsebkxn.html

[S23] C：随机数
来源：http://dali.aibaodan.cn/Article/details/gtqqggzinf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhixingplan.top/Article/details/gteoevaasu.html

[S24] C：获取本地时间
来源：http://dali.hnxiangtu.top/Article/details/gtvhcfnaqc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.nanxuanxn.top/Article/details/gtigxrzajn.html

[S25] C：内存拷贝
来源：http://dali.cheryme.top/Article/details/gtncqbqunn.html

memcpy(dst, src, n);
来源：http://dali.cdnleiting.top/Article/details/gtdkeeefrd.html

[S26] C：内存清零
来源：http://dali.hfpthk.cn/Article/details/gtxhsjjuxu.html

memset(a, 0, sizeof a);
来源：http://dali.kuanghao11.cn/Article/details/gtkeldpjvw.html

[S27] C：定义常量
来源：http://dali.daxiang520.top/Article/details/gtriqpvopq.html

const double PI = 3.14159;
来源：http://dali.jyoumei.cn/Article/details/gtatbegpqm.html

[S28] C：静态变量
来源：http://dali.aibaodan.cn/Article/details/gtkgfdzpxj.html

static int counter = 0;
来源：http://dali.chenzaomai.com/Article/details/gtjtjkhywj.html

[S29] C：变参函数
来源：http://dali.smart0.xyz/Article/details/gtsttxdbag.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cdnleiting.top/Article/details/gtglsfbogg.html

[S30] C：头文件保护
来源：http://dali.hywenlv.cn/Article/details/gtwibaywqk.html

#ifndef X_H
来源：http://dali.hongshengwenyu.top/Article/details/gtkigphkfg.html

#define X_H
来源：http://dali.daxiang520.top/Article/details/gtiftosrxd.html

#endif
来源：http://dali.pengpengdd.cyou/Article/details/gtbfsofiue.html

[S31] C++：Hello World
来源：http://dali.cdnleiting.top/Article/details/gterdtcaxh.html

#include <iostream>
来源：http://dali.andypj.xyz/Article/details/gtufilvfvb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sxryk.cn/Article/details/gtyqarxxfa.html

[S32] C++：字符串
来源：http://dali.hysaishi.cn/Article/details/gttqmasvou.html

std::string s = "hi";  s += "!";
来源：http://dali.birdmap.top/Article/details/gtirasrgwu.html

[S33] C++：vector 增删
来源：http://dali.tianlin.xyz/Article/details/gtkgrtuaic.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xinyue.icu/Article/details/gtxlifbckq.html

[S34] C++：遍历 vector
来源：http://dali.hnqzz.top/Article/details/gtllansqzd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.dianchejie.cn/Article/details/gtgbisrukh.html

[S35] C++：map
来源：http://dali.chenzaomai.com/Article/details/gtwafkvgdu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.316326.xyz/Article/details/gtccuogvop.html

[S36] C++：unordered_map
来源：http://dali.sxryk.cn/Article/details/gtqtxwmudu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtdcwlodth.html

[S37] C++：set
来源：http://dali.jianghu66.top/Article/details/gtuesnheah.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.havefunace.top/Article/details/gtpugrbsjd.html

[S38] C++：排序
来源：http://dali.daria6918.cn/Article/details/gtyusdgqxj.html

std::sort(v.begin(), v.end());
来源：http://dali.guannengcc.top/Article/details/gtecvsvfah.html

[S39] C++：自定义比较器排序
来源：http://dali.cucudq.cn/Article/details/gtbloeltbm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenlongwang.top/Article/details/gtztimzige.html

[S40] C++：查找元素
来源：http://dali.nanxinkj.top/Article/details/gtpoiqfugs.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.redwolf501.top/Article/details/gtdfyhodoi.html

[S41] C++：类与构造函数
来源：http://dali.sufxvd.cn/Article/details/gtrgneytra.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.dashuyun.cn/Article/details/gtahktotbc.html

[S42] C++：继承与虚函数
来源：http://dali.cdnleiting.top/Article/details/gthxwkmunc.html

class B : public Base { public: void f() override {} };
来源：http://dali.cheryme.top/Article/details/gtdnrrgyni.html

[S43] C++：智能指针
来源：http://dali.xuetiantiany.cn/Article/details/gtpcpiohvm.html

auto p = std::make_unique<int>(5);
来源：http://dali.nwbrower.top/Article/details/gtjkwslhga.html

[S44] C++：引用传参
来源：http://dali.hongshengwenyu.top/Article/details/gtnzpuqwju.html

void inc(int &x) { ++x; }
来源：http://dali.yj202588.top/Article/details/gtjjmkgtso.html

[S45] C++：lambda
来源：http://dali.xylfe.cn/Article/details/gtlckudiqo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.chenjidiqi.icu/Article/details/gtjlclcgjy.html

[S46] C++：函数模板
来源：http://dali.jinqigfzy.top/Article/details/gtxgxvehzh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yj20258.top/Article/details/gtekzsusua.html

[S47] C++：结构化绑定遍历
来源：http://dali.cucudq.cn/Article/details/gtmxcyjsde.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.wangshuangyany.cn/Article/details/gtfevmhoui.html

[S48] C++：逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gtqjrlrlvd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.guannengcc.top/Article/details/gtozremohw.html

while (std::getline(in, line)) { }
来源：http://dali.zhengqikj.top/Article/details/gtymwavkuy.html

[S49] C++：写文件
来源：http://dali.yanxiufei.cn/Article/details/gtxoeznzyy.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.316326.xyz/Article/details/gtxjrmddau.html

[S50] C++：格式化数字
来源：http://dali.hysaishi.cn/Article/details/gtknqqzfvn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sweek.top/Article/details/gtjsxeifxt.html

[S51] C++：显式类型转换
来源：http://dali.gotoacloud.top/Article/details/gtchhctzds.html

static_cast<double>(a) / b
来源：http://dali.aibaodan.cn/Article/details/gtriqlfrtt.html

[S52] C++：const 与 noexcept
来源：http://dali.jinqigfzy.top/Article/details/gtmdxcdivt.html

int size() const noexcept { return n_; }
来源：http://dali.cheryme.top/Article/details/gthgqtqklg.html

[S53] C++：移动语义
来源：http://dali.shanyushiyangtech.top/Article/details/gtwwglosny.html

std::vector<int> w = std::move(v);
来源：http://dali.iojbl.cn/Article/details/gtvlmhnvxh.html

[S54] C++：异常处理
来源：http://dali.svipenyu.cn/Article/details/gtknozqimb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.dashuyun.cn/Article/details/gtnmrdoqmx.html

[S55] C++：结构化绑定
来源：http://dali.svipenyu.cn/Article/details/gtisfuyvzw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.chenjidiqi.icu/Article/details/gtojzhwbfc.html

[S56] C++：optional
来源：http://dali.yonumen.top/Article/details/gtprdhrqus.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.andypj.xyz/Article/details/gtlhhaqutd.html

[S57] C++：编译期常量
来源：http://dali.nwbrower.top/Article/details/gtqxzrqspw.html

constexpr int N = 10;
来源：http://dali.iojbl.cn/Article/details/gtqyzgyfya.html

[S58] C++：命名空间
来源：http://dali.xuetiantiany.cn/Article/details/gtflldggcg.html

namespace ns { int f() { return 1; } }
来源：http://dali.dashuyun.cn/Article/details/gttaywjtgu.html

[S59] C++：静态断言
来源：http://dali.ywan-chungtsiang.top/Article/details/gtshqultmd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.chenjidiqi.icu/Article/details/gthwaibjab.html

[S60] C++：遍历并删除元素
来源：http://dali.yj202588.top/Article/details/gtjwyrwlpd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhoulong.xyz/Article/details/gtfevtkiou.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtkpgzslzd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jlsjyb.cn/Article/details/gtqirjhqou.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtshzwcolb.html

[T01] Kotlin：Hello World
来源：http://dali.sysykeji.top/Article/details/gtxalongfs.html

println("Hello")
来源：http://dali.c1oappe.top/Article/details/gtdiinbdmx.html

[T02] Kotlin：变量
来源：http://dali.sxryk.cn/Article/details/gtfjqhqkia.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlgciamjh.html

[T03] Kotlin：字符串模板
来源：http://dali.wangdashe.top/Article/details/gtumjhvmys.html

"值: $b"
来源：http://dali.fengsongda.top/Article/details/gtiugcncmi.html

[T04] Kotlin：空安全
来源：http://dali.smart0.xyz/Article/details/gtnsbcvpfh.html

val n: String? = null;  n?.length
来源：http://dali.yueranfly.top/Article/details/gteafxovwr.html

[T05] Kotlin：when 表达式
来源：http://dali.xylfe.cn/Article/details/gtkfrjmnad.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.9152youxi.cn/Article/details/gthvxeawuh.html

[T06] Kotlin：集合映射
来源：http://dali.vqdsnc.cn/Article/details/gtkcfezqzs.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xylfe.cn/Article/details/gtesapyxvo.html

[T07] Kotlin：集合过滤
来源：http://dali.hfpthk.cn/Article/details/gttdaqtzbp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.vqdsnc.cn/Article/details/gttarojskj.html

[T08] Kotlin：数据类
来源：http://dali.yuanzhike.top/Article/details/gteepzewrk.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gtayabrtzv.html

[T09] Kotlin：扩展函数
来源：http://dali.gaohongyu789.top/Article/details/gtqkhhtnej.html

fun String.exclaim() = this + "!"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbhgyovhz.html

[T10] Kotlin：默认参数
来源：http://dali.vqdsnc.cn/Article/details/gttjpburfl.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.gzhubu.top/Article/details/gthhbkgytz.html

[T11] Kotlin：协程
来源：http://dali.smart0.xyz/Article/details/gtkbozoqvi.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hywenlv.cn/Article/details/gtlngterwk.html

[T12] Kotlin：解构声明
来源：http://dali.xuetiantiany.cn/Article/details/gtjvkszned.html

val (a, b) = Pair(1, 2)
来源：http://dali.dashuyun.cn/Article/details/gtvqsegfdc.html

[T13] Kotlin：只读 Map
来源：http://dali.vqdsnc.cn/Article/details/gtgnrzhozq.html

val m = mapOf("a" to 1)
来源：http://dali.jianghu66.top/Article/details/gtzuypfzwp.html

[T14] Kotlin：循环
来源：http://dali.meibo888.top/Article/details/gtkswlzksn.html

for (i in 1..10) println(i)
来源：http://dali.birdmap.top/Article/details/gthcyqhaji.html

[T15] Kotlin：接口
来源：http://dali.shzxlz.cn/Article/details/gtqxfqnnjc.html

interface Shape { fun area(): Double }
来源：http://dali.cqqwz.cn/Article/details/gttkxhrscj.html

[T16] Swift：Hello World
来源：http://dali.sxryk.cn/Article/details/gthogqqgpb.html

print("Hello")
来源：http://dali.chenlongwang.top/Article/details/gtsrbxyrdd.html

[T17] Swift：变量与常量
来源：http://dali.zycfv.cn/Article/details/gtzlfkllff.html

var a = 1;  let b = 2
来源：http://dali.tanke756.top/Article/details/gtpnbghkip.html

[T18] Swift：字符串插值
来源：http://dali.hongshengwenyu.top/Article/details/gtopmhufcv.html

"值: \(b)"
来源：http://dali.chenjidiqi.icu/Article/details/gtdqqsrxhl.html

[T19] Swift：可选绑定
来源：http://dali.gotoacloud.top/Article/details/gtysuyxlbr.html

if let n = opt { print(n) }
来源：http://dali.yueranfly.top/Article/details/gtejaiofzc.html

[T20] Swift：数组操作
来源：http://dali.cucudq.cn/Article/details/gtvvstcjcc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.aibaodan.cn/Article/details/gtmdvddxjx.html

[T21] Swift：遍历
来源：http://dali.guowangkeji.top/Article/details/gtgekynfls.html

for x in a { print(x) }
来源：http://dali.ppjwa.cn/Article/details/gtythcmgzm.html

[T22] Swift：字典
来源：http://dali.cdnleiting.top/Article/details/gtfmuqfzvt.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cucudq.cn/Article/details/gthjnmkqti.html

[T23] Swift：函数
来源：http://dali.tian-w.cn/Article/details/gtxxfuosyp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ivvv.top/Article/details/gttuwwmqni.html

[T24] Swift：闭包
来源：http://dali.vqdsnc.cn/Article/details/gttdziiqyo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cashguo.top/Article/details/gthxgwcsbo.html

[T25] Swift：结构体
来源：http://dali.yonumen.top/Article/details/gtktwnpvej.html

struct P { var x: Int }
来源：http://dali.xuetiantiany.cn/Article/details/gtuxcekguo.html

[T26] Swift：类与重写
来源：http://dali.yonumen.top/Article/details/gtgjuzxvov.html

class A: Base { override func f() {} }
来源：http://dali.zhongyouzk.top/Article/details/gtlvyrgasp.html

[T27] Swift：错误处理
来源：http://dali.vqdsnc.cn/Article/details/gtmprsdbbj.html

do { try f() } catch { print(error) }
来源：http://dali.guowangkeji.top/Article/details/gthigjceit.html

[T28] Swift：枚举
来源：http://dali.xinyue.icu/Article/details/gtubznshld.html

enum Color { case red, green }
来源：http://dali.zhoulong.xyz/Article/details/gtprzffskg.html

[T29] Swift：guard 提前返回
来源：http://dali.pycfn.com/Article/details/gtzaedrmyp.html

guard let x = opt else { return }
来源：http://dali.nanxinkj.top/Article/details/gtguysxjpf.html

[T30] Swift：协议
来源：http://dali.aibaodan.cn/Article/details/gtpkukgqkt.html

protocol Shape { func area() -> Double }
来源：http://dali.andypj.xyz/Article/details/gtqfnbajxn.html

[T31] Lua：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtvajudbae.html

print("Hello")
来源：http://dali.pycfn.com/Article/details/gtuerlcrne.html

[T32] Lua：局部变量
来源：http://dali.yueranfly.top/Article/details/gtojhcupec.html

local a = 1
来源：http://dali.yueranfly.top/Article/details/gtrrupoorb.html

[T33] Lua：表（数组）
来源：http://dali.xuanzx.com/Article/details/gtpnpsogbb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yj202588.top/Article/details/gtwlkymdvm.html

[T34] Lua：遍历表
来源：http://dali.316326.xyz/Article/details/gtzulnfgvc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.tanke756.top/Article/details/gtzmtoetgj.html

[T35] Lua：字典表
来源：http://dali.jianghu66.top/Article/details/gtexpteshw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cdnleiting.top/Article/details/gtjttsetrn.html

[T36] Lua：函数
来源：http://dali.xuetiantiany.cn/Article/details/gteuujxqot.html

function add(a, b) return a + b end
来源：http://dali.yuxming.cn/Article/details/gtyfflbjvg.html

[T37] Lua：字符串拼接
来源：http://dali.smart0.xyz/Article/details/gtdhsnemiz.html

"a" .. "b"
来源：http://dali.yanxiufei.cn/Article/details/gtfksearge.html

[T38] Lua：条件
来源：http://dali.zhixingplan.top/Article/details/gtpqkrucup.html

if x > 0 then print("正") end
来源：http://dali.daxiang520.top/Article/details/gtvxqfrupm.html

[T39] Lua：模式匹配
来源：http://dali.yj20258888.top/Article/details/gtstcdbapr.html

string.find(s, "%d+")
来源：http://dali.jyoumei.cn/Article/details/gtlmkmtfry.html

[T40] Lua：元表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlfscsmix.html

setmetatable({}, { __index = base })
来源：http://dali.feifeiyinyue.top/Article/details/gtrxpugubi.html

[T41] Perl：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtrsxfarel.html

print "Hello\n";
来源：http://dali.ivvv.top/Article/details/gtiwcmxnjd.html

[T42] Perl：变量类型
来源：http://dali.jiagoushi.top/Article/details/gtivbxnvhx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yanxiufei.cn/Article/details/gtdxppgawg.html

[T43] Perl：字符串插值
来源：http://dali.kuanghao11.cn/Article/details/gtvlqulocl.html

"值: $a"
来源：http://dali.chenjidiqi.icu/Article/details/gtjclvdovs.html

[T44] Perl：条件
来源：http://dali.quarkkingdee.top/Article/details/gttmmyzlzc.html

if ($a > 0) { print "正"; }
来源：http://dali.daxiang520.top/Article/details/gtslcluwgd.html

[T45] Perl：数组遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkwqwfags.html

for my $x (@arr) { print $x; }
来源：http://dali.svipenyu.cn/Article/details/gtbuayecyp.html

[T46] Perl：哈希操作
来源：http://dali.yanxiufei.cn/Article/details/gtsiuchcpt.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.pycfn.com/Article/details/gtaykcaiix.html

[T47] Perl：正则捕获
来源：http://dali.yuxming.cn/Article/details/gtkknogbhp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.iojbl.cn/Article/details/gtbrxoseem.html

[T48] Perl：正则替换
来源：http://dali.wangshuangyany.cn/Article/details/gtcaicmimv.html

$s =~ s/old/new/g;
来源：http://dali.xziqi.cn/Article/details/gthqlfklqx.html

[T49] Perl：函数
来源：http://dali.dianchejie.cn/Article/details/gtxcmewitj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hnqzz.top/Article/details/gtacacmiwa.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gteavzhooz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfadtsmme.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ehwqpu.com/Article/details/gtiuydbkyx.html

[T51] Scala：Hello World
来源：http://dali.tianlin.xyz/Article/details/gttaxorrgj.html

println("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gtwlsmiroc.html

[T52] Scala：变量
来源：http://dali.xuanzx.com/Article/details/gtqkhaglca.html

val a = 1;  var b = 2
来源：http://dali.xylfe.cn/Article/details/gtlyzggndb.html

[T53] Scala：字符串插值
来源：http://dali.shangyingyoupin.top/Article/details/gtojbfjvuq.html

s"值: $b"
来源：http://dali.nwbrower.top/Article/details/gtzdlubxkd.html

[T54] Scala：集合映射
来源：http://dali.xinyue.icu/Article/details/gtskwymkvp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.smart0.xyz/Article/details/gtfwnngxao.html

[T55] Scala：集合过滤
来源：http://dali.jianghu66.top/Article/details/gtjqggklxv.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.chenjidiqi.icu/Article/details/gtplujblhu.html

[T56] Scala：样例类
来源：http://dali.sxryk.cn/Article/details/gtktsqighq.html

case class User(name: String, age: Int)
来源：http://dali.jianghu66.top/Article/details/gtmnwqzkqh.html

[T57] Scala：模式匹配
来源：http://dali.cucudq.cn/Article/details/gtxqzsgyit.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.pengpengdd.cyou/Article/details/gtcdxvcgmr.html

[T58] Scala：函数定义
来源：http://dali.guannengcc.top/Article/details/gtmaqgabve.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cheryme.top/Article/details/gtyqjszfpu.html

[T59] Scala：循环
来源：http://dali.tianlin.xyz/Article/details/gtjbdqvxhh.html

for (i <- 1 to 10) println(i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzcuatnxl.html

[T60] Scala：折叠
来源：http://dali.jinghuilouyu.cn/Article/details/gtbrajrzif.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sufxvd.cn/Article/details/gthcqhsrxv.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtkilkgwjh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.tanke756.top/Article/details/gtqwlxfztx.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gthymcjnmh.html

[U01] Py：创建虚拟环境
来源：http://dali.jyoumei.cn/Article/details/gtpsomclca.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.sysykeji.top/Article/details/gtrpxdpgei.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jqgufenzy.top/Article/details/gtuizcnhdc.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yonumen.top/Article/details/gthogoglux.html


<!-- 参考信息 -->