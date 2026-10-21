代发 wailian999

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ybcxt.top/Article/details/gtfkzbxmrh.html

[R66] 定时任务
来源：http://dali.ppjwa.cn/Article/details/gtsvppqcyt.html

crontab -e;  crontab -l
来源：http://dali.jianghu66.top/Article/details/gtxqaxpxdj.html

[R67] 生成随机十六进制串
来源：http://dali.c1oappe.top/Article/details/gtcatekcio.html

openssl rand -hex 16
来源：http://dali.jlsjyb.cn/Article/details/gtrczyfbhb.html

[R68] 计算文件校验值
来源：http://dali.yanxiufei.cn/Article/details/gtcwlgcise.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cucudq.cn/Article/details/gtjcdxoikx.html

[R69] 生成随机密码
来源：http://dali.9152youxi.cn/Article/details/gtafdfjhuf.html

head -c 16 /dev/urandom | base64
来源：http://dali.jyoumei.cn/Article/details/gtyrmnycqy.html

[R70] 时间戳与互转
来源：http://dali.jqgfzy.top/Article/details/gtkmanrhmw.html

date +%s;  date -d @1700000000
来源：http://dali.andypj.xyz/Article/details/gthfqjswvy.html

[R71] 日期格式化
来源：http://dali.hnqzz.top/Article/details/gtyvgegnpf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ehwqpu.com/Article/details/gtoqdppysi.html

[R72] 等待端口就绪
来源：http://dali.pycfn.com/Article/details/gtowmphrvh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cashguo.top/Article/details/gtciahxcgs.html

[R73] 分割大日志
来源：http://dali.wangshuangyany.cn/Article/details/gtvfqmhlsk.html

split -l 1000 big.log part_
来源：http://dali.zycfv.cn/Article/details/gtriwymtqf.html

[R74] 批量重命名
来源：http://dali.yuxming.cn/Article/details/gtbullvfwl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.chenzaomai.com/Article/details/gtjmsclugc.html

[R75] 导出环境变量
来源：http://dali.zhongyouzk.top/Article/details/gtpglwaitk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ydzc1.top/Article/details/gtkwkrxrbf.html

[R76] 使用临时文件
来源：http://dali.wangdashe.top/Article/details/gtbzgiwhei.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.dianchejie.cn/Article/details/gtjeotslhw.html

[R77] 读取用户输入
来源：http://dali.zdqjudy.top/Article/details/gtbykwctie.html

read -rp "请输入: " ans
来源：http://dali.cdnleiting.top/Article/details/gtcnzamtyp.html

[R78] 交互式菜单
来源：http://dali.jiagoushi.top/Article/details/gtlkbxidfe.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gaohongyu789.top/Article/details/gtxmwkaeui.html

[R79] 解析命令行选项
来源：http://dali.ivvv.top/Article/details/gttpelxhys.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.smart0.xyz/Article/details/gtlbllfdfe.html

[R80] 查看脚本执行耗时
来源：http://dali.yj20258888.top/Article/details/gtpfokgerv.html

time ./run.sh
来源：http://dali.havefunace.top/Article/details/gtrwyfpqmz.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtvkvzfgsm.html

S. C / C++ 专题
来源：http://dali.redwolf501.top/Article/details/gtcfwzxenf.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtegonpzbs.html

[S01] C：Hello World
来源：http://dali.fengsongda.top/Article/details/gteeooshkw.html

#include <stdio.h>
来源：http://dali.jiagoushi.top/Article/details/gtbkuwliuq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.smart0.xyz/Article/details/gtrermgnzo.html

[S02] C：变量与格式化输出
来源：http://dali.quarkkingdee.top/Article/details/gtwilauied.html

int a = 10; printf("%d\n", a);
来源：http://dali.zycfv.cn/Article/details/gtgwmkylpy.html

[S03] C：读入整数
来源：http://dali.ybcxt.top/Article/details/gtsbhnzmrn.html

int x; scanf("%d", &x);
来源：http://dali.yuanzhike.top/Article/details/gtkjliwnnu.html

[S04] C：字符串复制
来源：http://dali.tianlin.xyz/Article/details/gtzikruxfg.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zdqjudy.top/Article/details/gtoruzougk.html

[S05] C：字符串长度
来源：http://dali.chenjidiqi.icu/Article/details/gtbpmevomn.html

strlen(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtbipdfttx.html

[S06] C：字符串比较
来源：http://dali.gzhubu.top/Article/details/gtombhyvzq.html

strcmp(a, b) == 0
来源：http://dali.shanyushiyangkeji.top/Article/details/gtafipfzky.html

[S07] C：数组遍历求和
来源：http://dali.chenjidiqi.icu/Article/details/gtfcjxojzj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yangfankeji.com/Article/details/gtectttocd.html

[S08] C：动态内存分配与释放
来源：http://dali.hywenlv.cn/Article/details/gtvyxypfzz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.svipenyu.cn/Article/details/gtrkakgfjo.html

[S09] C：结构体定义与初始化
来源：http://dali.iojbl.cn/Article/details/gtuebcsddz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zdqjudy.top/Article/details/gtpdkqjcie.html

[S10] C：指针与解引用
来源：http://dali.pycfn.com/Article/details/gtnentuima.html

int *p = &a;  *p = 5;
来源：http://dali.gaohongyu789.top/Article/details/gtaybwxpmg.html

[S11] C：逐行读文件
来源：http://dali.hongshengwenyu.top/Article/details/gtyhquvdnd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hysaishi.cn/Article/details/gtupxeozzf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.snrcjt.cn/Article/details/gtjdwghutc.html

fclose(f);
来源：http://dali.daxiang520.top/Article/details/gtnqqyzyet.html

[S12] C：写文件
来源：http://dali.yj202588.top/Article/details/gtflvnlyjm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.nanxuanxn.top/Article/details/gthjgtqpya.html

[S13] C：宏定义
来源：http://dali.hfpthk.cn/Article/details/gtnjyihdvi.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yuanzhike.top/Article/details/gthpxpxccw.html

[S14] C：枚举
来源：http://dali.zhiwuduotai.top/Article/details/gtjqmpkgkr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhiwuduotai.top/Article/details/gtlyjxhatw.html

[S15] C：类型转换
来源：http://dali.zhengqikj.top/Article/details/gtmoguhsvc.html

(double) a / b
来源：http://dali.cqqwz.cn/Article/details/gtfufssrhc.html

[S16] C：位操作置位
来源：http://dali.zhoulong.xyz/Article/details/gtmbkbldup.html

x |= (1 << 3);
来源：http://dali.quarkkingdee.top/Article/details/gtortmxnje.html

[S17] C：安全拼接字符串
来源：http://dali.jlsjyb.cn/Article/details/gtfdmpmwoy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zycfv.cn/Article/details/gtcwtsthis.html

[S18] C：命令行参数
来源：http://dali.hammf.cn/Article/details/gtekcempml.html

int main(int argc, char **argv)
来源：http://dali.mhx1999.top/Article/details/gtjbyenvwv.html

[S19] C：快速排序
来源：http://dali.fengsongda.top/Article/details/gtmgnlykwj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.guowangkeji.top/Article/details/gtgtxfstxi.html

[S20] C：二分查找
来源：http://dali.dashuyun.cn/Article/details/gtwexchqun.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hammf.cn/Article/details/gttpxulgbm.html

[S21] C：字符类别判断
来源：http://dali.wangdashe.top/Article/details/gtxmcokede.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sysykeji.top/Article/details/gtapmkvhkc.html

[S22] C：字符串转数字
来源：http://dali.chenlongwang.top/Article/details/gtbeeiykvh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sweek.top/Article/details/gtasiduawx.html

[S23] C：随机数
来源：http://dali.meibo888.top/Article/details/gtlmbbxcjm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteeumijaz.html

[S24] C：获取本地时间
来源：http://dali.hfpthk.cn/Article/details/gtnprrdagx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwqwsqyaz.html

[S25] C：内存拷贝
来源：http://dali.tanke756.top/Article/details/gtygrbnyfu.html

memcpy(dst, src, n);
来源：http://dali.yj20258888.top/Article/details/gtmdrltvqr.html

[S26] C：内存清零
来源：http://dali.jinqigfzy.top/Article/details/gtlmgkszkm.html

memset(a, 0, sizeof a);
来源：http://dali.chenlongwang.top/Article/details/gtivdiaaaw.html

[S27] C：定义常量
来源：http://dali.jqgufenzy.top/Article/details/gtneycfbkh.html

const double PI = 3.14159;
来源：http://dali.dianchejie.cn/Article/details/gtcksplyri.html

[S28] C：静态变量
来源：http://dali.gaohongyu789.top/Article/details/gtddzylfpj.html

static int counter = 0;
来源：http://dali.tian-w.cn/Article/details/gtbrvxioeo.html

[S29] C：变参函数
来源：http://dali.0kj1m.cn/Article/details/gtrbkpzmgk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jlsjyb.cn/Article/details/gtwnwyztot.html

[S30] C：头文件保护
来源：http://dali.yuxming.cn/Article/details/gtokjprbyg.html

#ifndef X_H
来源：http://dali.yangfankeji.com/Article/details/gtgwdbdidt.html

#define X_H
来源：http://dali.nanxuanxn.top/Article/details/gtbqyrmvcb.html

#endif
来源：http://dali.cucudq.cn/Article/details/gtwkbbzrqn.html

[S31] C++：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtqtfpeaew.html

#include <iostream>
来源：http://dali.ivvv.top/Article/details/gtbuvegtyi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhengqikj.top/Article/details/gtziwwpwhd.html

[S32] C++：字符串
来源：http://dali.xuanzx.com/Article/details/gteguiscpz.html

std::string s = "hi";  s += "!";
来源：http://dali.cashguo.top/Article/details/gtxapfwksi.html

[S33] C++：vector 增删
来源：http://dali.jinghuilouyu.cn/Article/details/gtwbqihhjt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.andypj.xyz/Article/details/gtheorwmth.html

[S34] C++：遍历 vector
来源：http://dali.yueranfly.top/Article/details/gtmmsgvuem.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.quarkkingdee.top/Article/details/gtpmuaclla.html

[S35] C++：map
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvsajmdzy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.smart0.xyz/Article/details/gtwlahjxip.html

[S36] C++：unordered_map
来源：http://dali.shangyingyoupin.top/Article/details/gtgtkcfuzc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gtqkzfnulo.html

[S37] C++：set
来源：http://dali.daxiang520.top/Article/details/gtcryofwxt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.aibaodan.cn/Article/details/gtuxfrnxmv.html

[S38] C++：排序
来源：http://dali.fengsongda.top/Article/details/gtxvytgkxf.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gtjqrdqdos.html

[S39] C++：自定义比较器排序
来源：http://dali.sxryk.cn/Article/details/gtoqowolhz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhiwuduotai.top/Article/details/gtnkfqkgss.html

[S40] C++：查找元素
来源：http://dali.hysaishi.cn/Article/details/gtfgafxfjs.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtyarrxkmg.html

[S41] C++：类与构造函数
来源：http://dali.wangdashe.top/Article/details/gtracgkxuu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gtfggpmoyj.html

[S42] C++：继承与虚函数
来源：http://dali.cdnleiting.top/Article/details/gtdtabaath.html

class B : public Base { public: void f() override {} };
来源：http://dali.fengsongda.top/Article/details/gtxygtqeby.html

[S43] C++：智能指针
来源：http://dali.yuanzhike.top/Article/details/gtrujymocz.html

auto p = std::make_unique<int>(5);
来源：http://dali.0kj1m.cn/Article/details/gtnvvzhpzm.html

[S44] C++：引用传参
来源：http://dali.yuxming.cn/Article/details/gtbsnypaoq.html

void inc(int &x) { ++x; }
来源：http://dali.hysaishi.cn/Article/details/gtodnyprss.html

[S45] C++：lambda
来源：http://dali.c1oappe.top/Article/details/gtjxsexvbq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ydzc1.top/Article/details/gtoqvjuuku.html

[S46] C++：函数模板
来源：http://dali.jlsjyb.cn/Article/details/gtzafakdzk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hammf.cn/Article/details/gtbdnxsntf.html

[S47] C++：结构化绑定遍历
来源：http://dali.jiagoushi.top/Article/details/gtnicqzjwb.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.haohaochexian.top/Article/details/gttwjftuif.html

[S48] C++：逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gtehaphipe.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhengqikj.top/Article/details/gtbpqclbym.html

while (std::getline(in, line)) { }
来源：http://dali.tianlin.xyz/Article/details/gtvfducini.html

[S49] C++：写文件
来源：http://dali.wangdashe.top/Article/details/gtzvicsdgt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.0kj1m.cn/Article/details/gtpuhcvaoq.html

[S50] C++：格式化数字
来源：http://dali.bjfxy.top/Article/details/gtkuvoimbn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnkwvdpzw.html

[S51] C++：显式类型转换
来源：http://dali.gotoacloud.top/Article/details/gtzkwkkdur.html

static_cast<double>(a) / b
来源：http://dali.shuidangran.top/Article/details/gtvlifnbyy.html

[S52] C++：const 与 noexcept
来源：http://dali.jianghu66.top/Article/details/gteslvwkbb.html

int size() const noexcept { return n_; }
来源：http://dali.zycfv.cn/Article/details/gtuldurhqa.html

[S53] C++：移动语义
来源：http://dali.chenlongwang.top/Article/details/gtufsbjero.html

std::vector<int> w = std::move(v);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzrimezst.html

[S54] C++：异常处理
来源：http://dali.hywenlv.cn/Article/details/gtevkewucb.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhoulong.xyz/Article/details/gtchspevmo.html

[S55] C++：结构化绑定
来源：http://dali.daxiang520.top/Article/details/gtamghvzbm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.fengsongda.top/Article/details/gtggwnzeju.html

[S56] C++：optional
来源：http://dali.smart0.xyz/Article/details/gtiatglgyt.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.fengsongda.top/Article/details/gtlbwdfrrz.html

[S57] C++：编译期常量
来源：http://dali.meibo888.top/Article/details/gtogyhtstr.html

constexpr int N = 10;
来源：http://dali.kuanghao11.cn/Article/details/gtdtidwbkn.html

[S58] C++：命名空间
来源：http://dali.tianlin.xyz/Article/details/gtrdrmzgic.html

namespace ns { int f() { return 1; } }
来源：http://dali.andypj.xyz/Article/details/gtpohdwydt.html

[S59] C++：静态断言
来源：http://dali.smart0.xyz/Article/details/gteudiswxa.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.nanxinkj.top/Article/details/gtjtevqeyf.html

[S60] C++：遍历并删除元素
来源：http://dali.cqqwz.cn/Article/details/gttvowvddj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.guannengcc.top/Article/details/gtkmtwgpae.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtzzvkwvlh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cucudq.cn/Article/details/gthpwwfgcz.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtfmfqlwvk.html

[T01] Kotlin：Hello World
来源：http://dali.cashguo.top/Article/details/gttdtmvuuj.html

println("Hello")
来源：http://dali.xuanzx.com/Article/details/gtlfqlheux.html

[T02] Kotlin：变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjvjdtyje.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.tanke756.top/Article/details/gtmhfkddig.html

[T03] Kotlin：字符串模板
来源：http://dali.fengsongda.top/Article/details/gtejhvgjiu.html

"值: $b"
来源：http://dali.guannengcc.top/Article/details/gtdfewwzvg.html

[T04] Kotlin：空安全
来源：http://dali.nanxinkj.top/Article/details/gtcboxvyem.html

val n: String? = null;  n?.length
来源：http://dali.dianchejie.cn/Article/details/gthsvyszuh.html

[T05] Kotlin：when 表达式
来源：http://dali.guowangkeji.top/Article/details/gtepxbzmlp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hysaishi.cn/Article/details/gtwalvmcdq.html

[T06] Kotlin：集合映射
来源：http://dali.snrcjt.cn/Article/details/gtypjcyvqk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cashguo.top/Article/details/gtklwhcfmd.html

[T07] Kotlin：集合过滤
来源：http://dali.jinqigufen.top/Article/details/gtljgrvzxd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hysaishi.cn/Article/details/gthmhaaznt.html

[T08] Kotlin：数据类
来源：http://dali.meibo888.top/Article/details/gtorjgiqtl.html

data class User(val name: String, val age: Int)
来源：http://dali.316326.xyz/Article/details/gtrruttbhr.html

[T09] Kotlin：扩展函数
来源：http://dali.yanxiufei.cn/Article/details/gtmdztextg.html

fun String.exclaim() = this + "!"
来源：http://dali.zhongyouzk.top/Article/details/gturzeqyng.html

[T10] Kotlin：默认参数
来源：http://dali.sxryk.cn/Article/details/gtttcsfcjh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shangyingyoupin.top/Article/details/gtyfqtrprl.html

[T11] Kotlin：协程
来源：http://dali.pycfn.com/Article/details/gtaqtvxjxr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.mhx1999.top/Article/details/gtqynifzsp.html

[T12] Kotlin：解构声明
来源：http://dali.jinghuilouyu.cn/Article/details/gtmigjetms.html

val (a, b) = Pair(1, 2)
来源：http://dali.gaohongyu789.top/Article/details/gtdkqrrpcm.html

[T13] Kotlin：只读 Map
来源：http://dali.yangfankeji.com/Article/details/gtsoakpvcc.html

val m = mapOf("a" to 1)
来源：http://dali.sufxvd.cn/Article/details/gtfsvkthyy.html

[T14] Kotlin：循环
来源：http://dali.zhixingplan.top/Article/details/gtafhykcyc.html

for (i in 1..10) println(i)
来源：http://dali.zdqjudy.top/Article/details/gtqzviymub.html

[T15] Kotlin：接口
来源：http://dali.cheryme.top/Article/details/gtmoikvhjs.html

interface Shape { fun area(): Double }
来源：http://dali.smart0.xyz/Article/details/gtvcfcutgn.html

[T16] Swift：Hello World
来源：http://dali.hnqzz.top/Article/details/gtzblovtfr.html

print("Hello")
来源：http://dali.haohaochexian.top/Article/details/gtnzxqmgcy.html

[T17] Swift：变量与常量
来源：http://dali.nanxuanxn.top/Article/details/gtdgbrbmzm.html

var a = 1;  let b = 2
来源：http://dali.yueranfly.top/Article/details/gtgmaaemmp.html

[T18] Swift：字符串插值
来源：http://dali.shuidangran.top/Article/details/gtdorcyako.html

"值: \(b)"
来源：http://dali.havefunace.top/Article/details/gtiitilyll.html

[T19] Swift：可选绑定
来源：http://dali.jinghuilouyu.cn/Article/details/gtvtbkijfk.html

if let n = opt { print(n) }
来源：http://dali.xziqi.cn/Article/details/gteszcspba.html

[T20] Swift：数组操作
来源：http://dali.hnqzz.top/Article/details/gtuoisdwyk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhongyouzk.top/Article/details/gthjboscyq.html

[T21] Swift：遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtpaahpivb.html

for x in a { print(x) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwmvfsucu.html

[T22] Swift：字典
来源：http://dali.jlsjyb.cn/Article/details/gtdzpmesbe.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.mhx1999.top/Article/details/gtmlgvqpnc.html

[T23] Swift：函数
来源：http://dali.gotoacloud.top/Article/details/gtaffdqlnf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.svipenyu.cn/Article/details/gtzjkwnvyo.html

[T24] Swift：闭包
来源：http://dali.pengpengdd.cyou/Article/details/gtiktluqpz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhengqikj.top/Article/details/gtgtccpdcy.html

[T25] Swift：结构体
来源：http://dali.zhaomingkeji.xyz/Article/details/gtawkzrcxc.html

struct P { var x: Int }
来源：http://dali.yuxming.cn/Article/details/gtqvpvslii.html

[T26] Swift：类与重写
来源：http://dali.guowangkeji.top/Article/details/gtjblkwusx.html

class A: Base { override func f() {} }
来源：http://dali.zhixingplan.top/Article/details/gttjuccoih.html

[T27] Swift：错误处理
来源：http://dali.gzhubu.top/Article/details/gtmqdkqdah.html

do { try f() } catch { print(error) }
来源：http://dali.feifeiyinyue.top/Article/details/gtrqyfbzfd.html

[T28] Swift：枚举
来源：http://dali.aibaodan.cn/Article/details/gtyfulrxqx.html

enum Color { case red, green }
来源：http://dali.yangfankeji.com/Article/details/gtqcxulbgy.html

[T29] Swift：guard 提前返回
来源：http://dali.nanxinkj.top/Article/details/gtsidhdzuq.html

guard let x = opt else { return }
来源：http://dali.zhengqikj.top/Article/details/gtgzrduqxd.html

[T30] Swift：协议
来源：http://dali.nanxuanxn.top/Article/details/gtwelsccge.html

protocol Shape { func area() -> Double }
来源：http://dali.hywenlv.cn/Article/details/gtrsdgpzio.html

[T31] Lua：Hello World
来源：http://dali.wangdashe.top/Article/details/gtyxwvhurp.html

print("Hello")
来源：http://dali.haohaochexian.top/Article/details/gtnpsylteg.html

[T32] Lua：局部变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiudgcgwz.html

local a = 1
来源：http://dali.andypj.xyz/Article/details/gtpnmfshfb.html

[T33] Lua：表（数组）
来源：http://dali.sweek.top/Article/details/gtsaunfoqz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhoulong.xyz/Article/details/gtsdouaymt.html

[T34] Lua：遍历表
来源：http://dali.tianlin.xyz/Article/details/gtqpzfcmqf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.guowangkeji.top/Article/details/gtttjjwtcc.html

[T35] Lua：字典表
来源：http://dali.zhiwuduotai.top/Article/details/gttpdholhk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cqqwz.cn/Article/details/gtfgimdrxf.html

[T36] Lua：函数
来源：http://dali.nwbrower.top/Article/details/gtoeqzedgo.html

function add(a, b) return a + b end
来源：http://dali.pengpengdd.cyou/Article/details/gtkohvwlyh.html

[T37] Lua：字符串拼接
来源：http://dali.yvedp.cn/Article/details/gtuwzgkfgc.html

"a" .. "b"
来源：http://dali.kuanghao11.cn/Article/details/gtkcttscgm.html

[T38] Lua：条件
来源：http://dali.iojbl.cn/Article/details/gtpjjxjxqk.html

if x > 0 then print("正") end
来源：http://dali.iojbl.cn/Article/details/gtbvbfnhqx.html

[T39] Lua：模式匹配
来源：http://dali.c1oappe.top/Article/details/gtzrnudmtu.html

string.find(s, "%d+")
来源：http://dali.snrcjt.cn/Article/details/gtnerbypam.html

[T40] Lua：元表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbwvbbpwf.html

setmetatable({}, { __index = base })
来源：http://dali.hongshengwenyu.top/Article/details/gtrtrwspbg.html

[T41] Perl：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtyrhllcjz.html

print "Hello\n";
来源：http://dali.kuanghao11.cn/Article/details/gtzmfdekmq.html

[T42] Perl：变量类型
来源：http://dali.9152youxi.cn/Article/details/gtiesagkyh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.shuidangran.top/Article/details/gtqghaziqo.html

[T43] Perl：字符串插值
来源：http://dali.meibo888.top/Article/details/gtmflljfdj.html

"值: $a"
来源：http://dali.cheryme.top/Article/details/gtegdjcztg.html

[T44] Perl：条件
来源：http://dali.pycfn.com/Article/details/gtfbdxshmv.html

if ($a > 0) { print "正"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtfnibdnoe.html

[T45] Perl：数组遍历
来源：http://dali.hongshengwenyu.top/Article/details/gteytjintg.html

for my $x (@arr) { print $x; }
来源：http://dali.mhx1999.top/Article/details/gtqfxmoyno.html

[T46] Perl：哈希操作
来源：http://dali.sweek.top/Article/details/gtyyzfxfga.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hfpthk.cn/Article/details/gtdaekufej.html

[T47] Perl：正则捕获
来源：http://dali.havefunace.top/Article/details/gtndyomwgk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.meibo888.top/Article/details/gteaqqnuem.html

[T48] Perl：正则替换
来源：http://dali.gzhubu.top/Article/details/gtswtflzdn.html

$s =~ s/old/new/g;
来源：http://dali.pycfn.com/Article/details/gtvawgzkxg.html

[T49] Perl：函数
来源：http://dali.hfpthk.cn/Article/details/gtgtvrcyle.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jianghu66.top/Article/details/gtxvcovxvg.html

[T50] Perl：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gttcgtfmtl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.tanke756.top/Article/details/gtmnwfdpos.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xuanzx.com/Article/details/gtqoenjvxg.html

[T51] Scala：Hello World
来源：http://dali.yj20258888.top/Article/details/gtgffvgnfr.html

println("Hello")
来源：http://dali.pengpengdd.cyou/Article/details/gtdtpkpjkl.html

[T52] Scala：变量
来源：http://dali.redwolf501.top/Article/details/gtcmpkxszy.html

val a = 1;  var b = 2
来源：http://dali.cucudq.cn/Article/details/gtvjctlzwp.html

[T53] Scala：字符串插值
来源：http://dali.zhixingplan.top/Article/details/gtyampuege.html

s"值: $b"
来源：http://dali.shuidangran.top/Article/details/gtnrhfgnfg.html

[T54] Scala：集合映射
来源：http://dali.nanxinkj.top/Article/details/gtdsoguegl.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.kuanghao11.cn/Article/details/gtogtehqfx.html

[T55] Scala：集合过滤
来源：http://dali.havefunace.top/Article/details/gtzhbynzcm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yanxiufei.cn/Article/details/gtssexwydw.html

[T56] Scala：样例类
来源：http://dali.hywenlv.cn/Article/details/gtdgubrthi.html

case class User(name: String, age: Int)
来源：http://dali.shanyushiyangtech.top/Article/details/gtwqqffqhw.html

[T57] Scala：模式匹配
来源：http://dali.aibaodan.cn/Article/details/gtmlvffjxo.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yj20258.top/Article/details/gtavdhkhxe.html

[T58] Scala：函数定义
来源：http://dali.yj20258.top/Article/details/gtfbjuuqwz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.gzhubu.top/Article/details/gtxokyrbus.html

[T59] Scala：循环
来源：http://dali.daxiang520.top/Article/details/gtzducgcoz.html

for (i <- 1 to 10) println(i)
来源：http://dali.ppjwa.cn/Article/details/gtjtngnpmb.html

[T60] Scala：折叠
来源：http://dali.hysaishi.cn/Article/details/gtnthtcwpt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yuanzhike.top/Article/details/gtybmzbgwf.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gtwamubgol.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jyoumei.cn/Article/details/gtkrbcnwxn.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtazgwoeof.html

[U01] Py：创建虚拟环境
来源：http://dali.zhengqikj.top/Article/details/gterqyyvzw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xuanzx.com/Article/details/gtzgmzhgda.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yangfankeji.com/Article/details/gtdowpixpm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gthjsdxcfq.html

[U03] Py：加载 .env 配置
来源：http://dali.xuanzx.com/Article/details/gtitsccxyu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.mhx1999.top/Article/details/gthpxxmqhz.html

[U04] Py：变量调试打印
来源：http://dali.jinqigfzy.top/Article/details/gtvlxvrrvj.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.pengpengdd.cyou/Article/details/gtdtvtlnzl.html

[U05] Py：列表去重且保序
来源：http://dali.yueranfly.top/Article/details/gtapyznnuu.html

list(dict.fromkeys(arr))
来源：http://dali.jinghuilouyu.cn/Article/details/gtbwjrdtqo.html

[U06] Py：合并两个字典
来源：http://dali.chenjidiqi.icu/Article/details/gtnlwaoqwo.html

{**a, **b}
来源：http://dali.jiagoushi.top/Article/details/gtpogrikuc.html


<!-- 参考信息 -->