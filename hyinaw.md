代发 wailian999

free -h;  ps aux | grep nginx
来源：http://dali.jyoumei.cn/Article/details/gtwqaxrtfh.html

[R64] 结束进程
来源：http://dali.redwolf501.top/Article/details/gtdrdfrhch.html

kill -9 $(pgrep -f app.py)
来源：http://dali.316326.xyz/Article/details/gtttizpkhk.html

[R65] 查看端口占用
来源：http://dali.jianghu66.top/Article/details/gtvutbcmwu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.chenjidiqi.icu/Article/details/gtctmostua.html

[R66] 定时任务
来源：http://dali.shzxlz.cn/Article/details/gtjsduvurh.html

crontab -e;  crontab -l
来源：http://dali.yangfankeji.com/Article/details/gtrxdyzdob.html

[R67] 生成随机十六进制串
来源：http://dali.tanke756.top/Article/details/gtnpwyvays.html

openssl rand -hex 16
来源：http://dali.redwolf501.top/Article/details/gtkoftupzp.html

[R68] 计算文件校验值
来源：http://dali.yueranfly.top/Article/details/gtaitkahfe.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gteryldgrg.html

[R69] 生成随机密码
来源：http://dali.ehwqpu.com/Article/details/gtnufjmfxt.html

head -c 16 /dev/urandom | base64
来源：http://dali.hnqzz.top/Article/details/gtnfwhjdxn.html

[R70] 时间戳与互转
来源：http://dali.havefunace.top/Article/details/gtbsmqkwvw.html

date +%s;  date -d @1700000000
来源：http://dali.gotoacloud.top/Article/details/gtzpwmavbr.html

[R71] 日期格式化
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuttqalcw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shuidangran.top/Article/details/gtjqkeizxv.html

[R72] 等待端口就绪
来源：http://dali.yuxming.cn/Article/details/gteunycyeu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hammf.cn/Article/details/gtkmjitcam.html

[R73] 分割大日志
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzyusioqd.html

split -l 1000 big.log part_
来源：http://dali.aizwys.cn/Article/details/gtlxwxirqk.html

[R74] 批量重命名
来源：http://dali.andypj.xyz/Article/details/gtfpmaouyh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xinyue.icu/Article/details/gtqpocutww.html

[R75] 导出环境变量
来源：http://dali.sufxvd.cn/Article/details/gtpvjekcxq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhixingplan.top/Article/details/gtudidikhy.html

[R76] 使用临时文件
来源：http://dali.c1oappe.top/Article/details/gtakttfeks.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gotoacloud.top/Article/details/gtnktbugwi.html

[R77] 读取用户输入
来源：http://dali.redwolf501.top/Article/details/gtmuxzznhb.html

read -rp "请输入: " ans
来源：http://dali.fzhhl.top/Article/details/gtzkxzykai.html

[R78] 交互式菜单
来源：http://dali.shzxlz.cn/Article/details/gtlkhfufyc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.pycfn.com/Article/details/gtrnolflql.html

[R79] 解析命令行选项
来源：http://dali.zycfv.cn/Article/details/gtrgghjzpy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ybcxt.top/Article/details/gtjbzcgicf.html

[R80] 查看脚本执行耗时
来源：http://dali.yueranfly.top/Article/details/gtubcudsep.html

time ./run.sh
来源：http://dali.dianchejie.cn/Article/details/gtuxoarzdd.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtjesvavtt.html

S. C / C++ 专题
来源：http://dali.nwbrower.top/Article/details/gtrwyeygtz.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtfquzuybl.html

[S01] C：Hello World
来源：http://dali.guannengcc.top/Article/details/gtisdjrcuw.html

#include <stdio.h>
来源：http://dali.ivvv.top/Article/details/gtxhtbxsmn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gzhubu.top/Article/details/gtrsusdnxq.html

[S02] C：变量与格式化输出
来源：http://dali.yuanzhike.top/Article/details/gtpaweixgr.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwkqcvteb.html

[S03] C：读入整数
来源：http://dali.zhengqikj.top/Article/details/gtgmgmlkzu.html

int x; scanf("%d", &x);
来源：http://dali.hnxiangtu.top/Article/details/gthoojkoml.html

[S04] C：字符串复制
来源：http://dali.yvedp.cn/Article/details/gtvirziils.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhaomingkeji.xyz/Article/details/gttvfuxfdu.html

[S05] C：字符串长度
来源：http://dali.iojbl.cn/Article/details/gtqeiuiqsn.html

strlen(s)
来源：http://dali.meibo888.top/Article/details/gtyyfnhgqc.html

[S06] C：字符串比较
来源：http://dali.nanxuanxn.top/Article/details/gtoqqckdvi.html

strcmp(a, b) == 0
来源：http://dali.jlsjyb.cn/Article/details/gtwevhcgsf.html

[S07] C：数组遍历求和
来源：http://dali.zhengqikj.top/Article/details/gtkxueifln.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hysaishi.cn/Article/details/gtidfvalub.html

[S08] C：动态内存分配与释放
来源：http://dali.jianghu66.top/Article/details/gtenaceuet.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.chenlongwang.top/Article/details/gtgqvgjzwk.html

[S09] C：结构体定义与初始化
来源：http://dali.tian-w.cn/Article/details/gtgpmmtysp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cqqwz.cn/Article/details/gtordhxzrz.html

[S10] C：指针与解引用
来源：http://dali.yvedp.cn/Article/details/gtvwvithpe.html

int *p = &a;  *p = 5;
来源：http://dali.wangdashe.top/Article/details/gtunlsiyeg.html

[S11] C：逐行读文件
来源：http://dali.hongshengwenyu.top/Article/details/gthjtrkeqw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shangyingyoupin.top/Article/details/gtmylbaeti.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.meibo888.top/Article/details/gtwmodigek.html

fclose(f);
来源：http://dali.sxryk.cn/Article/details/gtgdgcutwo.html

[S12] C：写文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gthlpdqzwb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.bjfxy.top/Article/details/gtgrdpymie.html

[S13] C：宏定义
来源：http://dali.ivvv.top/Article/details/gtodledjfr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.pycfn.com/Article/details/gtjwkyvfto.html

[S14] C：枚举
来源：http://dali.pycfn.com/Article/details/gtislrhckp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sufxvd.cn/Article/details/gtacnforga.html

[S15] C：类型转换
来源：http://dali.tianlin.xyz/Article/details/gtkatdgwzl.html

(double) a / b
来源：http://dali.guowangkeji.top/Article/details/gtwqetrmvm.html

[S16] C：位操作置位
来源：http://dali.jiagoushi.top/Article/details/gtnxrdlupr.html

x |= (1 << 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtokuwsojr.html

[S17] C：安全拼接字符串
来源：http://dali.zhixingplan.top/Article/details/gtvvvkxnoi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.havefunace.top/Article/details/gthmffexxa.html

[S18] C：命令行参数
来源：http://dali.ydzc1.top/Article/details/gtajxcvjtv.html

int main(int argc, char **argv)
来源：http://dali.cheryme.top/Article/details/gtyuaehlft.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gtrscmoonb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.aibaodan.cn/Article/details/gtzfsfwkvq.html

[S20] C：二分查找
来源：http://dali.tianlin.xyz/Article/details/gtnjsnkpkl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ivvv.top/Article/details/gtaxkxauan.html

[S21] C：字符类别判断
来源：http://dali.svipenyu.cn/Article/details/gtukcfvpzs.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shuidangran.top/Article/details/gtgngdolsu.html

[S22] C：字符串转数字
来源：http://dali.xuetiantiany.cn/Article/details/gttudmznew.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.havefunace.top/Article/details/gtahylmych.html

[S23] C：随机数
来源：http://dali.xziqi.cn/Article/details/gtpeukbern.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.0kj1m.cn/Article/details/gthwnhlbdp.html

[S24] C：获取本地时间
来源：http://dali.ehwqpu.com/Article/details/gtqsxnmffq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sufxvd.cn/Article/details/gtcocfjrry.html

[S25] C：内存拷贝
来源：http://dali.gogol.net.cn/Article/details/gttqktuocb.html

memcpy(dst, src, n);
来源：http://dali.xylfe.cn/Article/details/gtvdddszjy.html

[S26] C：内存清零
来源：http://dali.feifeiyinyue.top/Article/details/gturvhxtld.html

memset(a, 0, sizeof a);
来源：http://dali.chenlongwang.top/Article/details/gtwupzuylx.html

[S27] C：定义常量
来源：http://dali.zhengqikj.top/Article/details/gtzicqstrk.html

const double PI = 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gtkjiychfg.html

[S28] C：静态变量
来源：http://dali.quarkkingdee.top/Article/details/gtwdzjfddj.html

static int counter = 0;
来源：http://dali.dashuyun.cn/Article/details/gtbstahtuh.html

[S29] C：变参函数
来源：http://dali.hnqzz.top/Article/details/gtxagwchny.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhoulong.xyz/Article/details/gtyelgudcf.html

[S30] C：头文件保护
来源：http://dali.quarkkingdee.top/Article/details/gtzcoozhjp.html

#ifndef X_H
来源：http://dali.sufxvd.cn/Article/details/gtwwdhsqwo.html

#define X_H
来源：http://dali.feifeiyinyue.top/Article/details/gteffygnlu.html

#endif
来源：http://dali.tanke756.top/Article/details/gtwerjarxy.html

[S31] C++：Hello World
来源：http://dali.fzhhl.top/Article/details/gtatvsrgpw.html

#include <iostream>
来源：http://dali.ybcxt.top/Article/details/gtaqkixzgi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hammf.cn/Article/details/gtnqlsnybc.html

[S32] C++：字符串
来源：http://dali.jianghu66.top/Article/details/gtwbvxdpqd.html

std::string s = "hi";  s += "!";
来源：http://dali.birdmap.top/Article/details/gtueqosikw.html

[S33] C++：vector 增删
来源：http://dali.xziqi.cn/Article/details/gtshqwktbu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.aizwys.cn/Article/details/gtqvocfirt.html

[S34] C++：遍历 vector
来源：http://dali.nanxinkj.top/Article/details/gtwrfxpwmx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xinyue.icu/Article/details/gtoavmtmkg.html

[S35] C++：map
来源：http://dali.jinghuilouyu.cn/Article/details/gtshqevbkl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.birdmap.top/Article/details/gtpuhzwvqd.html

[S36] C++：unordered_map
来源：http://dali.9152youxi.cn/Article/details/gtfontlbnf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtksqkzfru.html

[S37] C++：set
来源：http://dali.andypj.xyz/Article/details/gtxtxoydnt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqenzbnla.html

[S38] C++：排序
来源：http://dali.snrcjt.cn/Article/details/gtayqvxglq.html

std::sort(v.begin(), v.end());
来源：http://dali.cdnleiting.top/Article/details/gtjgmpztbk.html

[S39] C++：自定义比较器排序
来源：http://dali.wangshuangyany.cn/Article/details/gtgkalusoj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.bjfxy.top/Article/details/gtymkxegcp.html

[S40] C++：查找元素
来源：http://dali.kuanghao11.cn/Article/details/gttyhblfhy.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yanxiufei.cn/Article/details/gtxmwtbftv.html

[S41] C++：类与构造函数
来源：http://dali.0kj1m.cn/Article/details/gtijhgyzey.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.mhx1999.top/Article/details/gtpokdlxon.html

[S42] C++：继承与虚函数
来源：http://dali.wangdashe.top/Article/details/gthanhwcha.html

class B : public Base { public: void f() override {} };
来源：http://dali.gotoacloud.top/Article/details/gtjefzrmfa.html

[S43] C++：智能指针
来源：http://dali.xylfe.cn/Article/details/gtauofdoky.html

auto p = std::make_unique<int>(5);
来源：http://dali.yj202588.top/Article/details/gtbjckspwn.html

[S44] C++：引用传参
来源：http://dali.yj202588.top/Article/details/gtwqmrdwfa.html

void inc(int &x) { ++x; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtoogetuqt.html

[S45] C++：lambda
来源：http://dali.daxiang520.top/Article/details/gtryksvmtj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xuanzx.com/Article/details/gtjkohaeje.html

[S46] C++：函数模板
来源：http://dali.shangyingyoupin.top/Article/details/gtlmdxnoem.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ppjwa.cn/Article/details/gtedzqsjoc.html

[S47] C++：结构化绑定遍历
来源：http://dali.xylfe.cn/Article/details/gtnywpaxas.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.nanxuanxn.top/Article/details/gtebipnjih.html

[S48] C++：逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gtdrdngslm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sweek.top/Article/details/gtdcuugxht.html

while (std::getline(in, line)) { }
来源：http://dali.quarkkingdee.top/Article/details/gtmixzwifk.html

[S49] C++：写文件
来源：http://dali.fzhhl.top/Article/details/gteazacvle.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhoulong.xyz/Article/details/gtjtimbhzl.html

[S50] C++：格式化数字
来源：http://dali.nanxinkj.top/Article/details/gtxlymsyeh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yongpay.top/Article/details/gtpwpvnfdh.html

[S51] C++：显式类型转换
来源：http://dali.chenjidiqi.icu/Article/details/gtktpotlcy.html

static_cast<double>(a) / b
来源：http://dali.xylfe.cn/Article/details/gtbmlbmipw.html

[S52] C++：const 与 noexcept
来源：http://dali.bjfxy.top/Article/details/gtphinettv.html

int size() const noexcept { return n_; }
来源：http://dali.chenlongwang.top/Article/details/gthizfyhoz.html

[S53] C++：移动语义
来源：http://dali.zhengqikj.top/Article/details/gtfuzzktia.html

std::vector<int> w = std::move(v);
来源：http://dali.yj202588.top/Article/details/gtieqfbtxz.html

[S54] C++：异常处理
来源：http://dali.c1oappe.top/Article/details/gtfsfgrvmh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sufxvd.cn/Article/details/gtepbnpgio.html

[S55] C++：结构化绑定
来源：http://dali.jinghuilouyu.cn/Article/details/gtqrghqiyp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.redwolf501.top/Article/details/gtyupvfttg.html

[S56] C++：optional
来源：http://dali.yj20258888.top/Article/details/gtqcgqrdsj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xziqi.cn/Article/details/gtwvpkjzvc.html

[S57] C++：编译期常量
来源：http://dali.mhx1999.top/Article/details/gtqkdbweeq.html

constexpr int N = 10;
来源：http://dali.hnqzz.top/Article/details/gtitxarnxd.html

[S58] C++：命名空间
来源：http://dali.jianghu66.top/Article/details/gteipculwi.html

namespace ns { int f() { return 1; } }
来源：http://dali.hongshengwenyu.top/Article/details/gtczudlnlq.html

[S59] C++：静态断言
来源：http://dali.haohaochexian.top/Article/details/gtpywpsmfa.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.daria6918.cn/Article/details/gtektgivxk.html

[S60] C++：遍历并删除元素
来源：http://dali.sweek.top/Article/details/gtjzewliwz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfxmcxspw.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtyzkoxylm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yueranfly.top/Article/details/gtrhfiugbw.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtjtcymgpr.html

[T01] Kotlin：Hello World
来源：http://dali.ybcxt.top/Article/details/gtwampouzp.html

println("Hello")
来源：http://dali.ydzc1.top/Article/details/gtuadbxefe.html

[T02] Kotlin：变量
来源：http://dali.gotoacloud.top/Article/details/gthteddhvy.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.pycfn.com/Article/details/gtfwuymvhi.html

[T03] Kotlin：字符串模板
来源：http://dali.snrcjt.cn/Article/details/gtvsubjglj.html

"值: $b"
来源：http://dali.quarkkingdee.top/Article/details/gtbtyxqhla.html

[T04] Kotlin：空安全
来源：http://dali.nanxinkj.top/Article/details/gthkwfetyu.html

val n: String? = null;  n?.length
来源：http://dali.ppjwa.cn/Article/details/gtnolvnjqx.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gtcaqfwdau.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jiagoushi.top/Article/details/gtyujwrjkp.html

[T06] Kotlin：集合映射
来源：http://dali.quarkkingdee.top/Article/details/gtszpyhudd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yuanzhike.top/Article/details/gtpacujdfu.html

[T07] Kotlin：集合过滤
来源：http://dali.chenzaomai.com/Article/details/gtaoxhxazn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.guowangkeji.top/Article/details/gtugopgvim.html

[T08] Kotlin：数据类
来源：http://dali.hnqzz.top/Article/details/gtuvryfliq.html

data class User(val name: String, val age: Int)
来源：http://dali.sysykeji.top/Article/details/gtuczvmwxc.html

[T09] Kotlin：扩展函数
来源：http://dali.gaohongyu789.top/Article/details/gtdrauoece.html

fun String.exclaim() = this + "!"
来源：http://dali.iojbl.cn/Article/details/gtckgytwia.html

[T10] Kotlin：默认参数
来源：http://dali.chenjidiqi.icu/Article/details/gtucdrcvbf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cqqwz.cn/Article/details/gtkuarkxve.html

[T11] Kotlin：协程
来源：http://dali.jqgufenzy.top/Article/details/gtxrpglwks.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xinyue.icu/Article/details/gtlmzmvvch.html

[T12] Kotlin：解构声明
来源：http://dali.yanxiufei.cn/Article/details/gttwjjgnfw.html

val (a, b) = Pair(1, 2)
来源：http://dali.birdmap.top/Article/details/gtudzxfijs.html

[T13] Kotlin：只读 Map
来源：http://dali.sysykeji.top/Article/details/gtnnylegcg.html

val m = mapOf("a" to 1)
来源：http://dali.jianghu66.top/Article/details/gtnobyzdbn.html

[T14] Kotlin：循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtksdrzzff.html

for (i in 1..10) println(i)
来源：http://dali.aizwys.cn/Article/details/gtopfajwdd.html

[T15] Kotlin：接口
来源：http://dali.yueranfly.top/Article/details/gtzxyezxck.html

interface Shape { fun area(): Double }
来源：http://dali.xylfe.cn/Article/details/gtivmmiiru.html

[T16] Swift：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttxlquxxq.html

print("Hello")
来源：http://dali.pengpengdd.cyou/Article/details/gtzphzqjbh.html

[T17] Swift：变量与常量
来源：http://dali.hnqzz.top/Article/details/gtyiznvgor.html

var a = 1;  let b = 2
来源：http://dali.birdmap.top/Article/details/gtrpeoodwg.html

[T18] Swift：字符串插值
来源：http://dali.jyoumei.cn/Article/details/gtuqrrxvci.html

"值: \(b)"
来源：http://dali.aibaodan.cn/Article/details/gtdsakhwtg.html

[T19] Swift：可选绑定
来源：http://dali.cashguo.top/Article/details/gtkerqlkwd.html

if let n = opt { print(n) }
来源：http://dali.wangdashe.top/Article/details/gtrvyatzkw.html

[T20] Swift：数组操作
来源：http://dali.yuanzhike.top/Article/details/gtquqpvigv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yanxiufei.cn/Article/details/gtyinhpuds.html

[T21] Swift：遍历
来源：http://dali.c1oappe.top/Article/details/gtqkelyfqc.html

for x in a { print(x) }
来源：http://dali.shangyingyoupin.top/Article/details/gtccvvsucx.html

[T22] Swift：字典
来源：http://dali.hfpthk.cn/Article/details/gtxotcxdvn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.c1oappe.top/Article/details/gtdvirfkev.html

[T23] Swift：函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvzswejdo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuzgkmmbn.html

[T24] Swift：闭包
来源：http://dali.yvedp.cn/Article/details/gtutrjyhcb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinqigfzy.top/Article/details/gtwjntnrtm.html

[T25] Swift：结构体
来源：http://dali.gotoacloud.top/Article/details/gtrdefefxh.html

struct P { var x: Int }
来源：http://dali.gaohongyu789.top/Article/details/gtisrqrmlw.html

[T26] Swift：类与重写
来源：http://dali.gotoacloud.top/Article/details/gtvsbosfby.html

class A: Base { override func f() {} }
来源：http://dali.ydzc1.top/Article/details/gtabumdjts.html

[T27] Swift：错误处理
来源：http://dali.snrcjt.cn/Article/details/gtuwmexljr.html

do { try f() } catch { print(error) }
来源：http://dali.svipenyu.cn/Article/details/gthcwshyol.html

[T28] Swift：枚举
来源：http://dali.cashguo.top/Article/details/gtqhtkufpa.html

enum Color { case red, green }
来源：http://dali.meibo888.top/Article/details/gtycjwxaja.html

[T29] Swift：guard 提前返回
来源：http://dali.yonumen.top/Article/details/gtggimbtyi.html

guard let x = opt else { return }
来源：http://dali.sufxvd.cn/Article/details/gtywpdxpee.html

[T30] Swift：协议
来源：http://dali.snrcjt.cn/Article/details/gtfexzjhrd.html

protocol Shape { func area() -> Double }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtglonaiur.html

[T31] Lua：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtfpmfqagq.html

print("Hello")
来源：http://dali.daxiang520.top/Article/details/gtokytlcje.html

[T32] Lua：局部变量
来源：http://dali.ppjwa.cn/Article/details/gtyokfptyh.html

local a = 1
来源：http://dali.yueranfly.top/Article/details/gtetqftgnd.html

[T33] Lua：表（数组）
来源：http://dali.zhixingplan.top/Article/details/gtkpahszpk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.feifeiyinyue.top/Article/details/gtfyxysdni.html

[T34] Lua：遍历表
来源：http://dali.jqgfzy.top/Article/details/gthgvudpsi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.nanxuanxn.top/Article/details/gtazcdixgs.html

[T35] Lua：字典表
来源：http://dali.aizwys.cn/Article/details/gtjqbnrzze.html

local d = { a = 1 };  d.b = 2
来源：http://dali.vqdsnc.cn/Article/details/gtaosxxxub.html

[T36] Lua：函数
来源：http://dali.ehwqpu.com/Article/details/gtfcqsdasl.html

function add(a, b) return a + b end
来源：http://dali.jqgfzy.top/Article/details/gtcpnfncws.html

[T37] Lua：字符串拼接
来源：http://dali.zhixingplan.top/Article/details/gtxgzotsbu.html

"a" .. "b"
来源：http://dali.bjfxy.top/Article/details/gtucvgwufw.html

[T38] Lua：条件
来源：http://dali.quarkkingdee.top/Article/details/gtyreolfco.html

if x > 0 then print("正") end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthvtacpxn.html

[T39] Lua：模式匹配
来源：http://dali.zhoulong.xyz/Article/details/gtfgcgqpqd.html

string.find(s, "%d+")
来源：http://dali.wangshuangyany.cn/Article/details/gtpfwvvgjd.html

[T40] Lua：元表
来源：http://dali.cdnleiting.top/Article/details/gtmjstojmh.html

setmetatable({}, { __index = base })
来源：http://dali.shangyingyoupin.top/Article/details/gtmespryjd.html

[T41] Perl：Hello World
来源：http://dali.yj20258888.top/Article/details/gtlioolhyw.html

print "Hello\n";
来源：http://dali.shzxlz.cn/Article/details/gtjkpfcxah.html

[T42] Perl：变量类型
来源：http://dali.hammf.cn/Article/details/gtmpazmvmz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jlsjyb.cn/Article/details/gtngrhzvav.html

[T43] Perl：字符串插值
来源：http://dali.bjfxy.top/Article/details/gtoljgfsht.html

"值: $a"
来源：http://dali.cqqwz.cn/Article/details/gtkzwsepqi.html

[T44] Perl：条件
来源：http://dali.xuetiantiany.cn/Article/details/gtrckvzchs.html

if ($a > 0) { print "正"; }
来源：http://dali.jianghu66.top/Article/details/gtdxwcscux.html

[T45] Perl：数组遍历
来源：http://dali.jqgufenzy.top/Article/details/gtsaaemwns.html

for my $x (@arr) { print $x; }
来源：http://dali.guannengcc.top/Article/details/gtdqapmwzg.html

[T46] Perl：哈希操作
来源：http://dali.hongshengwenyu.top/Article/details/gtjhefdlbz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shuidangran.top/Article/details/gtnfztdwhd.html

[T47] Perl：正则捕获
来源：http://dali.haohaochexian.top/Article/details/gtakvixrjt.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xuetiantiany.cn/Article/details/gtnsumqllp.html

[T48] Perl：正则替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwzhucbgh.html

$s =~ s/old/new/g;
来源：http://dali.hnqzz.top/Article/details/gthazbobke.html

[T49] Perl：函数
来源：http://dali.hnqzz.top/Article/details/gtcsktnojf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhongyouzk.top/Article/details/gtdwdkfffr.html

[T50] Perl：逐行读文件
来源：http://dali.hnxiangtu.top/Article/details/gtqsugowve.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyfuypcxd.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtovbapipj.html

[T51] Scala：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtmvfimfbt.html

println("Hello")
来源：http://dali.yj20258888.top/Article/details/gtamnsejft.html

[T52] Scala：变量
来源：http://dali.pycfn.com/Article/details/gtwadftund.html

val a = 1;  var b = 2
来源：http://dali.sweek.top/Article/details/gternwiqwm.html

[T53] Scala：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gtujbuznnb.html

s"值: $b"
来源：http://dali.yuanzhike.top/Article/details/gtjvxuybjx.html

[T54] Scala：集合映射
来源：http://dali.zdqjudy.top/Article/details/gtujkddwws.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cqqwz.cn/Article/details/gtilvnqned.html

[T55] Scala：集合过滤
来源：http://dali.sweek.top/Article/details/gtkpxwpifs.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.chenlongwang.top/Article/details/gttmntirxx.html

[T56] Scala：样例类
来源：http://dali.gotoacloud.top/Article/details/gtapbrgbhu.html

case class User(name: String, age: Int)
来源：http://dali.shzxlz.cn/Article/details/gtyemfwppu.html

[T57] Scala：模式匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnambapjh.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.gzhubu.top/Article/details/gtuqywrlzk.html

[T58] Scala：函数定义
来源：http://dali.smart0.xyz/Article/details/gtdvifnvbl.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.haohaochexian.top/Article/details/gtausatjqc.html

[T59] Scala：循环
来源：http://dali.jinqigufen.top/Article/details/gtzgfbyaqp.html

for (i <- 1 to 10) println(i)
来源：http://dali.nanxuanxn.top/Article/details/gtzlvankkc.html

[T60] Scala：折叠
来源：http://dali.gaohongyu789.top/Article/details/gtsokihjxt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhiwuduotai.top/Article/details/gtnsinljbv.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtpmgexcbj.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.meibo888.top/Article/details/gtfyrfzzah.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtrfjkktkc.html

[U01] Py：创建虚拟环境
来源：http://dali.cashguo.top/Article/details/gtpkwmekea.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.pycfn.com/Article/details/gtbjcgobwf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xuetiantiany.cn/Article/details/gtgenhhqqb.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtdhszclzk.html

[U03] Py：加载 .env 配置
来源：http://dali.cucudq.cn/Article/details/gthsvlvdwr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjvyuvdtl.html

[U04] Py：变量调试打印
来源：http://dali.tanke756.top/Article/details/gtfawpmluh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zhoulong.xyz/Article/details/gtkneeirds.html


<!-- 参考信息 -->