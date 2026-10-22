代发 wailian999

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hysaishi.cn/Article/details/gtjivdogty.html

[R66] 定时任务
来源：http://dali.zhiwuduotai.top/Article/details/gtquvsxwdf.html

crontab -e;  crontab -l
来源：http://dali.316326.xyz/Article/details/gtnowfjbge.html

[R67] 生成随机十六进制串
来源：http://dali.feifeiyinyue.top/Article/details/gtznfhxaho.html

openssl rand -hex 16
来源：http://dali.zhoulong.xyz/Article/details/gtiyvmkwyd.html

[R68] 计算文件校验值
来源：http://dali.gzhubu.top/Article/details/gtibzeqttv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtaiolgkgc.html

[R69] 生成随机密码
来源：http://dali.zhengqikj.top/Article/details/gtndilhucp.html

head -c 16 /dev/urandom | base64
来源：http://dali.9152youxi.cn/Article/details/gtjzkpwvda.html

[R70] 时间戳与互转
来源：http://dali.shuidangran.top/Article/details/gtsjfhikik.html

date +%s;  date -d @1700000000
来源：http://dali.shanyushiyangkeji.top/Article/details/gtarmjmyat.html

[R71] 日期格式化
来源：http://dali.nwbrower.top/Article/details/gtfselulnz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.birdmap.top/Article/details/gtcpkexyuj.html

[R72] 等待端口就绪
来源：http://dali.hongshengwenyu.top/Article/details/gtxqcrugsq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj202588.top/Article/details/gtesdpjdeh.html

[R73] 分割大日志
来源：http://dali.fzhhl.top/Article/details/gtwrkiikqx.html

split -l 1000 big.log part_
来源：http://dali.zhoulong.xyz/Article/details/gtyyzjwphl.html

[R74] 批量重命名
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyvtbmdoq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cucudq.cn/Article/details/gtctlfkhyo.html

[R75] 导出环境变量
来源：http://dali.haohaochexian.top/Article/details/gtyvcwsfxa.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.quarkkingdee.top/Article/details/gtohkmkvzi.html

[R76] 使用临时文件
来源：http://dali.tanke756.top/Article/details/gtpyyqiuyx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqclvxjzw.html

[R77] 读取用户输入
来源：http://dali.nwbrower.top/Article/details/gthmjlcbsl.html

read -rp "请输入: " ans
来源：http://dali.yueranfly.top/Article/details/gtiscnuttn.html

[R78] 交互式菜单
来源：http://dali.zhiwuduotai.top/Article/details/gthyvwqbpi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hysaishi.cn/Article/details/gtdkzahspy.html

[R79] 解析命令行选项
来源：http://dali.gzhubu.top/Article/details/gttztstlzz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhongyouzk.top/Article/details/gteuilihog.html

[R80] 查看脚本执行耗时
来源：http://dali.nanxinkj.top/Article/details/gtrmahthuu.html

time ./run.sh
来源：http://dali.sysykeji.top/Article/details/gtdzusgtmp.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtstsxwomy.html

S. C / C++ 专题
来源：http://dali.yuxming.cn/Article/details/gtixgftogw.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gtaslixafy.html

[S01] C：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtlntoqhtt.html

#include <stdio.h>
来源：http://dali.ivvv.top/Article/details/gtdomcfbux.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.haohaochexian.top/Article/details/gtdhfrukpc.html

[S02] C：变量与格式化输出
来源：http://dali.jinqigufen.top/Article/details/gtknrzgqlx.html

int a = 10; printf("%d\n", a);
来源：http://dali.0kj1m.cn/Article/details/gtwtzljqag.html

[S03] C：读入整数
来源：http://dali.chenlongwang.top/Article/details/gtyhswlxes.html

int x; scanf("%d", &x);
来源：http://dali.shuidangran.top/Article/details/gtycnpkhsj.html

[S04] C：字符串复制
来源：http://dali.mhx1999.top/Article/details/gtwuyztdkm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gzhubu.top/Article/details/gtmdmlrnsn.html

[S05] C：字符串长度
来源：http://dali.sxryk.cn/Article/details/gtpgfpvttf.html

strlen(s)
来源：http://dali.bjfxy.top/Article/details/gtmttldvwt.html

[S06] C：字符串比较
来源：http://dali.shuidangran.top/Article/details/gtoesntjqc.html

strcmp(a, b) == 0
来源：http://dali.chenlongwang.top/Article/details/gtsjzpyugn.html

[S07] C：数组遍历求和
来源：http://dali.redwolf501.top/Article/details/gtdjwcfkhb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gaohongyu789.top/Article/details/gtijmtzzoz.html

[S08] C：动态内存分配与释放
来源：http://dali.ehwqpu.com/Article/details/gtemaotysv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinghuilouyu.cn/Article/details/gthwrhvesg.html

[S09] C：结构体定义与初始化
来源：http://dali.redwolf501.top/Article/details/gtpfendpio.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.fzhhl.top/Article/details/gtdtlouatx.html

[S10] C：指针与解引用
来源：http://dali.zhiwuduotai.top/Article/details/gtuefefbiz.html

int *p = &a;  *p = 5;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtghprsoqi.html

[S11] C：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gtjnbajnyz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hongshengwenyu.top/Article/details/gtuuckzirf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.quarkkingdee.top/Article/details/gtiwbhyemt.html

fclose(f);
来源：http://dali.ivvv.top/Article/details/gtqblngjqu.html

[S12] C：写文件
来源：http://dali.pycfn.com/Article/details/gtxuwnebsy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.daxiang520.top/Article/details/gttmklwyzk.html

[S13] C：宏定义
来源：http://dali.cashguo.top/Article/details/gtjdzkmync.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.9152youxi.cn/Article/details/gtalxpkumb.html

[S14] C：枚举
来源：http://dali.yueranfly.top/Article/details/gtmujxjnbw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.c1oappe.top/Article/details/gtgjhaomtk.html

[S15] C：类型转换
来源：http://dali.mhx1999.top/Article/details/gtasshdlws.html

(double) a / b
来源：http://dali.fzhhl.top/Article/details/gtrgdexveq.html

[S16] C：位操作置位
来源：http://dali.yanxiufei.cn/Article/details/gtngkgpjra.html

x |= (1 << 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtckxifctl.html

[S17] C：安全拼接字符串
来源：http://dali.0kj1m.cn/Article/details/gtgflakxbl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hfpthk.cn/Article/details/gtvfoqlbxk.html

[S18] C：命令行参数
来源：http://dali.hammf.cn/Article/details/gtyenkatwl.html

int main(int argc, char **argv)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcgjiaolb.html

[S19] C：快速排序
来源：http://dali.shanyushiyangtech.top/Article/details/gtlmmdxfde.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yuxming.cn/Article/details/gthdlkbqui.html

[S20] C：二分查找
来源：http://dali.yanxiufei.cn/Article/details/gtsfkzoius.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhengqikj.top/Article/details/gtzpthzryd.html

[S21] C：字符类别判断
来源：http://dali.haohaochexian.top/Article/details/gtgkmkxezj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.chenjidiqi.icu/Article/details/gtlatarxjg.html

[S22] C：字符串转数字
来源：http://dali.ivvv.top/Article/details/gthosojkea.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.fengsongda.top/Article/details/gtyyuxmlch.html

[S23] C：随机数
来源：http://dali.hongshengwenyu.top/Article/details/gthtvytwae.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.guannengcc.top/Article/details/gtqyqluvqs.html

[S24] C：获取本地时间
来源：http://dali.vqdsnc.cn/Article/details/gtylreeuky.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.bjfxy.top/Article/details/gtqtatmliz.html

[S25] C：内存拷贝
来源：http://dali.yanxiufei.cn/Article/details/gtfksirypr.html

memcpy(dst, src, n);
来源：http://dali.hnqzz.top/Article/details/gtapcwdjlz.html

[S26] C：内存清零
来源：http://dali.zhixingplan.top/Article/details/gtykirppcb.html

memset(a, 0, sizeof a);
来源：http://dali.sysykeji.top/Article/details/gtuokstdhu.html

[S27] C：定义常量
来源：http://dali.yuanzhike.top/Article/details/gtsqpoderv.html

const double PI = 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gttyimqvez.html

[S28] C：静态变量
来源：http://dali.yueranfly.top/Article/details/gtdxxbexmr.html

static int counter = 0;
来源：http://dali.jianghu66.top/Article/details/gtkhhtgyfj.html

[S29] C：变参函数
来源：http://dali.tian-w.cn/Article/details/gtfhjxcnxh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zycfv.cn/Article/details/gtpuepkcaw.html

[S30] C：头文件保护
来源：http://dali.jinghuilouyu.cn/Article/details/gtrtohyysr.html

#ifndef X_H
来源：http://dali.daria6918.cn/Article/details/gtqyoneqmr.html

#define X_H
来源：http://dali.hnxiangtu.top/Article/details/gtaijiozma.html

#endif
来源：http://dali.xuanzx.com/Article/details/gtdoehsovs.html

[S31] C++：Hello World
来源：http://dali.yongpay.top/Article/details/gtzfnkkybx.html

#include <iostream>
来源：http://dali.xinyue.icu/Article/details/gtzfczfcfe.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhiwuduotai.top/Article/details/gttmyoivlk.html

[S32] C++：字符串
来源：http://dali.sxryk.cn/Article/details/gtljbrlrpz.html

std::string s = "hi";  s += "!";
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpthdwhpg.html

[S33] C++：vector 增删
来源：http://dali.yvedp.cn/Article/details/gttkfhivhs.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.daria6918.cn/Article/details/gttebfaaoe.html

[S34] C++：遍历 vector
来源：http://dali.gotoacloud.top/Article/details/gtowgkwosk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.wangdashe.top/Article/details/gtnzbltjzq.html

[S35] C++：map
来源：http://dali.fzhhl.top/Article/details/gtmkvekyut.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ydzc1.top/Article/details/gttgszrnqn.html

[S36] C++：unordered_map
来源：http://dali.jinghuilouyu.cn/Article/details/gtskwvfmkd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ppjwa.cn/Article/details/gtugbsknlw.html

[S37] C++：set
来源：http://dali.hammf.cn/Article/details/gtoawdrfao.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.bjfxy.top/Article/details/gtqberfcws.html

[S38] C++：排序
来源：http://dali.fengsongda.top/Article/details/gthxakrice.html

std::sort(v.begin(), v.end());
来源：http://dali.hongshengwenyu.top/Article/details/gtsrftnstk.html

[S39] C++：自定义比较器排序
来源：http://dali.gzhubu.top/Article/details/gthjcbhzsv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yvedp.cn/Article/details/gtnidtqiry.html

[S40] C++：查找元素
来源：http://dali.hysaishi.cn/Article/details/gtyjzjkvtz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.havefunace.top/Article/details/gtccpdgbut.html

[S41] C++：类与构造函数
来源：http://dali.yongpay.top/Article/details/gtupwympyk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.fzhhl.top/Article/details/gtqqvjihvq.html

[S42] C++：继承与虚函数
来源：http://dali.guannengcc.top/Article/details/gtzbgkebon.html

class B : public Base { public: void f() override {} };
来源：http://dali.dianchejie.cn/Article/details/gtfkshurld.html

[S43] C++：智能指针
来源：http://dali.yvedp.cn/Article/details/gtkkcgnqoq.html

auto p = std::make_unique<int>(5);
来源：http://dali.fengsongda.top/Article/details/gtkmthueke.html

[S44] C++：引用传参
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwdahyewp.html

void inc(int &x) { ++x; }
来源：http://dali.sxryk.cn/Article/details/gtafzkdzly.html

[S45] C++：lambda
来源：http://dali.jinqigufen.top/Article/details/gttltqioll.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.guowangkeji.top/Article/details/gtrifesbwz.html

[S46] C++：函数模板
来源：http://dali.nanxinkj.top/Article/details/gtvvckyibl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.redwolf501.top/Article/details/gtejomgmxc.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhixingplan.top/Article/details/gtjyzscpii.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zdqjudy.top/Article/details/gtzfwkjasc.html

[S48] C++：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gtkmiursvq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sufxvd.cn/Article/details/gttrptkoag.html

while (std::getline(in, line)) { }
来源：http://dali.ehwqpu.com/Article/details/gtzxmmbgqh.html

[S49] C++：写文件
来源：http://dali.sweek.top/Article/details/gtkcljaine.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.quarkkingdee.top/Article/details/gtcoelabaj.html

[S50] C++：格式化数字
来源：http://dali.meibo888.top/Article/details/gtvwupcctx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gteqofsqej.html

[S51] C++：显式类型转换
来源：http://dali.yj20258888.top/Article/details/gtekayobov.html

static_cast<double>(a) / b
来源：http://dali.sufxvd.cn/Article/details/gtmpzenjpc.html

[S52] C++：const 与 noexcept
来源：http://dali.sufxvd.cn/Article/details/gtidtexoxb.html

int size() const noexcept { return n_; }
来源：http://dali.sweek.top/Article/details/gtbwbijgux.html

[S53] C++：移动语义
来源：http://dali.zhoulong.xyz/Article/details/gtcmhlvgzi.html

std::vector<int> w = std::move(v);
来源：http://dali.nanxinkj.top/Article/details/gtuxbfyzlc.html

[S54] C++：异常处理
来源：http://dali.zhixingplan.top/Article/details/gtwmqsmstw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hywenlv.cn/Article/details/gtqbtjkhfx.html

[S55] C++：结构化绑定
来源：http://dali.hfpthk.cn/Article/details/gtjkwrvftp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.daxiang520.top/Article/details/gttydcgwvb.html

[S56] C++：optional
来源：http://dali.yuanzhike.top/Article/details/gtolnnaxdf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gogol.net.cn/Article/details/gtvdrmszhf.html

[S57] C++：编译期常量
来源：http://dali.meibo888.top/Article/details/gtnftjnrbm.html

constexpr int N = 10;
来源：http://dali.birdmap.top/Article/details/gtjllvwska.html

[S58] C++：命名空间
来源：http://dali.hywenlv.cn/Article/details/gtvcmyaezz.html

namespace ns { int f() { return 1; } }
来源：http://dali.gaohongyu789.top/Article/details/gtyfuhpbzj.html

[S59] C++：静态断言
来源：http://dali.svipenyu.cn/Article/details/gtergrpxaf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.svipenyu.cn/Article/details/gttuiwxnni.html

[S60] C++：遍历并删除元素
来源：http://dali.zhoulong.xyz/Article/details/gtefsqidto.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.tianlin.xyz/Article/details/gtoyilwejs.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtcmrdtrlq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.wangdashe.top/Article/details/gtigatuiyi.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtedqloadu.html

[T01] Kotlin：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtkdpbzuyg.html

println("Hello")
来源：http://dali.yuxming.cn/Article/details/gtmlqjcqsl.html

[T02] Kotlin：变量
来源：http://dali.guowangkeji.top/Article/details/gtnvsyvmxb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.wangshuangyany.cn/Article/details/gtuejjmukw.html

[T03] Kotlin：字符串模板
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpejwfhoy.html

"值: $b"
来源：http://dali.zdqjudy.top/Article/details/gtisuvfcsk.html

[T04] Kotlin：空安全
来源：http://dali.sysykeji.top/Article/details/gtkfnkufxy.html

val n: String? = null;  n?.length
来源：http://dali.gotoacloud.top/Article/details/gtkvcdqywx.html

[T05] Kotlin：when 表达式
来源：http://dali.iojbl.cn/Article/details/gtlcylnuah.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hfpthk.cn/Article/details/gthfsfkbxc.html

[T06] Kotlin：集合映射
来源：http://dali.shanyushiyangtech.top/Article/details/gtdbvrgfgy.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinqigfzy.top/Article/details/gttnhwjhum.html

[T07] Kotlin：集合过滤
来源：http://dali.nwbrower.top/Article/details/gtkryntkzf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sufxvd.cn/Article/details/gtiryaopjm.html

[T08] Kotlin：数据类
来源：http://dali.ppjwa.cn/Article/details/gtzvtbplxk.html

data class User(val name: String, val age: Int)
来源：http://dali.zhiwuduotai.top/Article/details/gtihyiaufd.html

[T09] Kotlin：扩展函数
来源：http://dali.wangshuangyany.cn/Article/details/gtcnbqgkib.html

fun String.exclaim() = this + "!"
来源：http://dali.shanyushiyangtech.top/Article/details/gtvamftusv.html

[T10] Kotlin：默认参数
来源：http://dali.zhiwuduotai.top/Article/details/gtczurqtnv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ybcxt.top/Article/details/gtkcrxbmvo.html

[T11] Kotlin：协程
来源：http://dali.xylfe.cn/Article/details/gtnqqfdana.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yj20258.top/Article/details/gttzgmfiiz.html

[T12] Kotlin：解构声明
来源：http://dali.chenzaomai.com/Article/details/gtbcbprnux.html

val (a, b) = Pair(1, 2)
来源：http://dali.hysaishi.cn/Article/details/gtgvrzhalt.html

[T13] Kotlin：只读 Map
来源：http://dali.wangshuangyany.cn/Article/details/gtndixtmny.html

val m = mapOf("a" to 1)
来源：http://dali.zhixingplan.top/Article/details/gtuyxxvdlj.html

[T14] Kotlin：循环
来源：http://dali.pycfn.com/Article/details/gtodcxxxae.html

for (i in 1..10) println(i)
来源：http://dali.dashuyun.cn/Article/details/gtwcqpekir.html

[T15] Kotlin：接口
来源：http://dali.aibaodan.cn/Article/details/gtridquyvf.html

interface Shape { fun area(): Double }
来源：http://dali.tianlin.xyz/Article/details/gtjxvflfgh.html

[T16] Swift：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtmfjhriad.html

print("Hello")
来源：http://dali.jqgufenzy.top/Article/details/gtwgebaeis.html

[T17] Swift：变量与常量
来源：http://dali.yuanzhike.top/Article/details/gtlbetdxrs.html

var a = 1;  let b = 2
来源：http://dali.aibaodan.cn/Article/details/gtkthkbmqu.html

[T18] Swift：字符串插值
来源：http://dali.jiagoushi.top/Article/details/gtsmhfqres.html

"值: \(b)"
来源：http://dali.wangdashe.top/Article/details/gtctjyedst.html

[T19] Swift：可选绑定
来源：http://dali.wangshuangyany.cn/Article/details/gtzalnbnny.html

if let n = opt { print(n) }
来源：http://dali.gogol.net.cn/Article/details/gtyokdlcgj.html

[T20] Swift：数组操作
来源：http://dali.zhengqikj.top/Article/details/gtxkpblyio.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.0kj1m.cn/Article/details/gtvfuivdmk.html

[T21] Swift：遍历
来源：http://dali.ybcxt.top/Article/details/gthrnrnpao.html

for x in a { print(x) }
来源：http://dali.cqqwz.cn/Article/details/gtplgafqun.html

[T22] Swift：字典
来源：http://dali.chenzaomai.com/Article/details/gtkjgawgrq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yuanzhike.top/Article/details/gtpytcbmrz.html

[T23] Swift：函数
来源：http://dali.sweek.top/Article/details/gtozcqwfdp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hnxiangtu.top/Article/details/gtnsqzkodt.html

[T24] Swift：闭包
来源：http://dali.ybcxt.top/Article/details/gtrjgvassp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.vqdsnc.cn/Article/details/gtdntqnudv.html

[T25] Swift：结构体
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsatkjgzj.html

struct P { var x: Int }
来源：http://dali.nanxuanxn.top/Article/details/gtkwdqnbhb.html

[T26] Swift：类与重写
来源：http://dali.wangdashe.top/Article/details/gtvjkjwtor.html

class A: Base { override func f() {} }
来源：http://dali.mhx1999.top/Article/details/gthhjwuiwq.html

[T27] Swift：错误处理
来源：http://dali.yj202588.top/Article/details/gtpuosclht.html

do { try f() } catch { print(error) }
来源：http://dali.sufxvd.cn/Article/details/gtnkjkiwge.html

[T28] Swift：枚举
来源：http://dali.svipenyu.cn/Article/details/gtoaetourh.html

enum Color { case red, green }
来源：http://dali.tianlin.xyz/Article/details/gtjtomrfyg.html

[T29] Swift：guard 提前返回
来源：http://dali.smart0.xyz/Article/details/gtjgqatycd.html

guard let x = opt else { return }
来源：http://dali.ivvv.top/Article/details/gtetaxebec.html

[T30] Swift：协议
来源：http://dali.sysykeji.top/Article/details/gtevgiptrg.html

protocol Shape { func area() -> Double }
来源：http://dali.haohaochexian.top/Article/details/gtoqrmihzl.html

[T31] Lua：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtuycddfgg.html

print("Hello")
来源：http://dali.shuidangran.top/Article/details/gtyfmsmeay.html

[T32] Lua：局部变量
来源：http://dali.kuanghao11.cn/Article/details/gtutorkgyo.html

local a = 1
来源：http://dali.guowangkeji.top/Article/details/gtynfgidwn.html

[T33] Lua：表（数组）
来源：http://dali.daria6918.cn/Article/details/gtmjxppuqf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.sysykeji.top/Article/details/gtytkdagic.html

[T34] Lua：遍历表
来源：http://dali.jlsjyb.cn/Article/details/gtyokiwbjr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.redwolf501.top/Article/details/gtopcgimnn.html

[T35] Lua：字典表
来源：http://dali.yj20258888.top/Article/details/gtwcthvxas.html

local d = { a = 1 };  d.b = 2
来源：http://dali.guannengcc.top/Article/details/gtknyjixcf.html

[T36] Lua：函数
来源：http://dali.cucudq.cn/Article/details/gtgmajmgat.html

function add(a, b) return a + b end
来源：http://dali.hfpthk.cn/Article/details/gtlcxozzox.html

[T37] Lua：字符串拼接
来源：http://dali.iojbl.cn/Article/details/gtdldfoekn.html

"a" .. "b"
来源：http://dali.yj20258.top/Article/details/gtuzcgpfyo.html

[T38] Lua：条件
来源：http://dali.cdnleiting.top/Article/details/gtejfcyjty.html

if x > 0 then print("正") end
来源：http://dali.sweek.top/Article/details/gtyaxxuuja.html

[T39] Lua：模式匹配
来源：http://dali.dianchejie.cn/Article/details/gtgwcgaper.html

string.find(s, "%d+")
来源：http://dali.sufxvd.cn/Article/details/gtrbbxtuxh.html

[T40] Lua：元表
来源：http://dali.gotoacloud.top/Article/details/gtmcnqpbeg.html

setmetatable({}, { __index = base })
来源：http://dali.cqqwz.cn/Article/details/gtnovlqpsy.html

[T41] Perl：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtauftxlxg.html

print "Hello\n";
来源：http://dali.cheryme.top/Article/details/gtqfeezdpl.html

[T42] Perl：变量类型
来源：http://dali.chenzaomai.com/Article/details/gtpgsipzot.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.nanxuanxn.top/Article/details/gtriuvcicy.html

[T43] Perl：字符串插值
来源：http://dali.jlsjyb.cn/Article/details/gtyxljhjam.html

"值: $a"
来源：http://dali.xinyue.icu/Article/details/gtfhprohrn.html

[T44] Perl：条件
来源：http://dali.aibaodan.cn/Article/details/gtlcnntcfn.html

if ($a > 0) { print "正"; }
来源：http://dali.ehwqpu.com/Article/details/gtsywrrcne.html

[T45] Perl：数组遍历
来源：http://dali.bjfxy.top/Article/details/gtovlenjir.html

for my $x (@arr) { print $x; }
来源：http://dali.aibaodan.cn/Article/details/gtlwehwtbi.html

[T46] Perl：哈希操作
来源：http://dali.gzhubu.top/Article/details/gtjzcccnbh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yongpay.top/Article/details/gtqqfqajlm.html

[T47] Perl：正则捕获
来源：http://dali.zhiwuduotai.top/Article/details/gtigcexyuk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hnxiangtu.top/Article/details/gtyuozqfol.html

[T48] Perl：正则替换
来源：http://dali.yongpay.top/Article/details/gtstfkyqqe.html

$s =~ s/old/new/g;
来源：http://dali.shzxlz.cn/Article/details/gthuzjamlk.html

[T49] Perl：函数
来源：http://dali.tanke756.top/Article/details/gtsfqbnmfr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yvedp.cn/Article/details/gtzlptbztl.html

[T50] Perl：逐行读文件
来源：http://dali.meibo888.top/Article/details/gtpmyjepso.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hfpthk.cn/Article/details/gtfxwahkni.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.feifeiyinyue.top/Article/details/gtznusrvna.html

[T51] Scala：Hello World
来源：http://dali.guannengcc.top/Article/details/gtrhydttld.html

println("Hello")
来源：http://dali.wangdashe.top/Article/details/gtqkpkjrvo.html

[T52] Scala：变量
来源：http://dali.chenlongwang.top/Article/details/gtnhvhgnti.html

val a = 1;  var b = 2
来源：http://dali.xuanzx.com/Article/details/gthlkmxylo.html

[T53] Scala：字符串插值
来源：http://dali.kuanghao11.cn/Article/details/gtiyqwaflu.html

s"值: $b"
来源：http://dali.cdnleiting.top/Article/details/gtykdvbbux.html

[T54] Scala：集合映射
来源：http://dali.yvedp.cn/Article/details/gtqwelkpwu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gogol.net.cn/Article/details/gtyihdxuxi.html

[T55] Scala：集合过滤
来源：http://dali.c1oappe.top/Article/details/gtfykxnsir.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.fzhhl.top/Article/details/gtcaemmesf.html

[T56] Scala：样例类
来源：http://dali.gogol.net.cn/Article/details/gtptrwuzuu.html

case class User(name: String, age: Int)
来源：http://dali.redwolf501.top/Article/details/gtdozajqrm.html

[T57] Scala：模式匹配
来源：http://dali.chenlongwang.top/Article/details/gtjgeifmgq.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.sysykeji.top/Article/details/gtsznbjjpm.html

[T58] Scala：函数定义
来源：http://dali.hnxiangtu.top/Article/details/gtugksxbyv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.birdmap.top/Article/details/gtzuhaciqj.html

[T59] Scala：循环
来源：http://dali.zhiwuduotai.top/Article/details/gtwofdbkwj.html

for (i <- 1 to 10) println(i)
来源：http://dali.pengpengdd.cyou/Article/details/gtiqboyjkq.html

[T60] Scala：折叠
来源：http://dali.gzhubu.top/Article/details/gtnujtdlvz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shuidangran.top/Article/details/gttnzsdcja.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtjmpolout.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhengqikj.top/Article/details/gttmxveizk.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtqcwkmiyz.html

[U01] Py：创建虚拟环境
来源：http://dali.mhx1999.top/Article/details/gtkjniffzq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.smart0.xyz/Article/details/gtfzgzmvcv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.fengsongda.top/Article/details/gtixfszxch.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yongpay.top/Article/details/gtoxbropgb.html

[U03] Py：加载 .env 配置
来源：http://dali.gogol.net.cn/Article/details/gtnohpaiib.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.c1oappe.top/Article/details/gtkhrrnvri.html

[U04] Py：变量调试打印
来源：http://dali.yuxming.cn/Article/details/gtaesbmohb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxtjtiyzg.html

[U05] Py：列表去重且保序
来源：http://dali.quarkkingdee.top/Article/details/gtzwofsxxt.html

list(dict.fromkeys(arr))
来源：http://dali.sweek.top/Article/details/gtpfuhkzya.html

[U06] Py：合并两个字典
来源：http://dali.hfpthk.cn/Article/details/gtnrqerbhw.html

{**a, **b}
来源：http://dali.sweek.top/Article/details/gtbwysuasd.html


<!-- 参考信息 -->