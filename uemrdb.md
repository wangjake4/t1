代发 wailian999

free -h;  ps aux | grep nginx
来源：http://dali.zycfv.cn/Article/details/gtjsfigvfi.html

[R64] 结束进程
来源：http://dali.ppjwa.cn/Article/details/gtutkhacyj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.dianchejie.cn/Article/details/gtjukfqnvy.html

[R65] 查看端口占用
来源：http://dali.aibaodan.cn/Article/details/gtnooovpgx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yueranfly.top/Article/details/gtwwkfmxvl.html

[R66] 定时任务
来源：http://dali.birdmap.top/Article/details/gtsbfyagjn.html

crontab -e;  crontab -l
来源：http://dali.yonumen.top/Article/details/gtyxbaecev.html

[R67] 生成随机十六进制串
来源：http://dali.yanxiufei.cn/Article/details/gtiqgdtkfq.html

openssl rand -hex 16
来源：http://dali.nanxinkj.top/Article/details/gtjyqboyil.html

[R68] 计算文件校验值
来源：http://dali.cqqwz.cn/Article/details/gtposccoxr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.aibaodan.cn/Article/details/gtxbmadaoh.html

[R69] 生成随机密码
来源：http://dali.zhengqikj.top/Article/details/gtmwybrqpi.html

head -c 16 /dev/urandom | base64
来源：http://dali.tian-w.cn/Article/details/gtpwqytzxj.html

[R70] 时间戳与互转
来源：http://dali.yj20258888.top/Article/details/gtcpwrjeru.html

date +%s;  date -d @1700000000
来源：http://dali.bjfxy.top/Article/details/gtxhpzuwmj.html

[R71] 日期格式化
来源：http://dali.pengpengdd.cyou/Article/details/gtkswwsgjr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.smart0.xyz/Article/details/gtohkcqofa.html

[R72] 等待端口就绪
来源：http://dali.nwbrower.top/Article/details/gtbfmzlnko.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jianghu66.top/Article/details/gtcgmnbwqe.html

[R73] 分割大日志
来源：http://dali.guowangkeji.top/Article/details/gtpkdqpdhh.html

split -l 1000 big.log part_
来源：http://dali.chenzaomai.com/Article/details/gtphvwczzv.html

[R74] 批量重命名
来源：http://dali.tanke756.top/Article/details/gtlnzadjlv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.havefunace.top/Article/details/gtrfmjqgsd.html

[R75] 导出环境变量
来源：http://dali.zhoulong.xyz/Article/details/gtekbqvzky.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.guowangkeji.top/Article/details/gtswrxnpni.html

[R76] 使用临时文件
来源：http://dali.kuanghao11.cn/Article/details/gtquihzpxf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhixingplan.top/Article/details/gtwkqwitkt.html

[R77] 读取用户输入
来源：http://dali.yongpay.top/Article/details/gtexjwieup.html

read -rp "请输入: " ans
来源：http://dali.yongpay.top/Article/details/gtkidqzrfc.html

[R78] 交互式菜单
来源：http://dali.wangshuangyany.cn/Article/details/gttxrayemw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhongyouzk.top/Article/details/gtbypuzvzn.html

[R79] 解析命令行选项
来源：http://dali.zhengqikj.top/Article/details/gtvkavvraj.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zdqjudy.top/Article/details/gtkvtmhbft.html

[R80] 查看脚本执行耗时
来源：http://dali.bjfxy.top/Article/details/gtfnctakgq.html

time ./run.sh
来源：http://dali.vqdsnc.cn/Article/details/gtrqmzwpvc.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtjamokceb.html

S. C / C++ 专题
来源：http://dali.ivvv.top/Article/details/gtczecbutz.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtpljvdbeo.html

[S01] C：Hello World
来源：http://dali.yueranfly.top/Article/details/gtbphlxdsp.html

#include <stdio.h>
来源：http://dali.aibaodan.cn/Article/details/gtshjpnppw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yanxiufei.cn/Article/details/gtyfzagspd.html

[S02] C：变量与格式化输出
来源：http://dali.birdmap.top/Article/details/gtacsedywf.html

int a = 10; printf("%d\n", a);
来源：http://dali.gotoacloud.top/Article/details/gtrspiafcs.html

[S03] C：读入整数
来源：http://dali.yangfankeji.com/Article/details/gtfqauslfb.html

int x; scanf("%d", &x);
来源：http://dali.snrcjt.cn/Article/details/gtcyzabggt.html

[S04] C：字符串复制
来源：http://dali.guowangkeji.top/Article/details/gtnccipufe.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.guannengcc.top/Article/details/gtusozduon.html

[S05] C：字符串长度
来源：http://dali.xinyue.icu/Article/details/gtvboslvqv.html

strlen(s)
来源：http://dali.fzhhl.top/Article/details/gtwvrhaviw.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gtogvsxmoj.html

strcmp(a, b) == 0
来源：http://dali.iojbl.cn/Article/details/gtgzfuxwvt.html

[S07] C：数组遍历求和
来源：http://dali.nanxuanxn.top/Article/details/gtkbtebcel.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jlsjyb.cn/Article/details/gtkzmrdpzo.html

[S08] C：动态内存分配与释放
来源：http://dali.chenlongwang.top/Article/details/gtejwowdeo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cucudq.cn/Article/details/gtdsofywuk.html

[S09] C：结构体定义与初始化
来源：http://dali.sweek.top/Article/details/gthbwecdug.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yangfankeji.com/Article/details/gtxaiabccl.html

[S10] C：指针与解引用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkeddlwnh.html

int *p = &a;  *p = 5;
来源：http://dali.shangyingyoupin.top/Article/details/gtixmnuswn.html

[S11] C：逐行读文件
来源：http://dali.snrcjt.cn/Article/details/gtogmuxcsc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.316326.xyz/Article/details/gtzoinvqvi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.guannengcc.top/Article/details/gtldsuhxoa.html

fclose(f);
来源：http://dali.zhixingplan.top/Article/details/gtvclnfhgi.html

[S12] C：写文件
来源：http://dali.chenzaomai.com/Article/details/gtwwnkkyto.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yonumen.top/Article/details/gtewpqhcda.html

[S13] C：宏定义
来源：http://dali.xinyue.icu/Article/details/gtenlkmybp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiningiai.html

[S14] C：枚举
来源：http://dali.jqgfzy.top/Article/details/gttakhmkge.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sxryk.cn/Article/details/gtezsuttgg.html

[S15] C：类型转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtzoijllcp.html

(double) a / b
来源：http://dali.hysaishi.cn/Article/details/gtnyswnwfi.html

[S16] C：位操作置位
来源：http://dali.ppjwa.cn/Article/details/gthedffhwc.html

x |= (1 << 3);
来源：http://dali.nwbrower.top/Article/details/gtvmcmssea.html

[S17] C：安全拼接字符串
来源：http://dali.yvedp.cn/Article/details/gtcpnhcfhz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenzaomai.com/Article/details/gtosyybxwc.html

[S18] C：命令行参数
来源：http://dali.jiagoushi.top/Article/details/gtoznrxlah.html

int main(int argc, char **argv)
来源：http://dali.fzhhl.top/Article/details/gtexjixqgn.html

[S19] C：快速排序
来源：http://dali.yj20258.top/Article/details/gtwljlmlgg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hongshengwenyu.top/Article/details/gtrelptssx.html

[S20] C：二分查找
来源：http://dali.tian-w.cn/Article/details/gtuliydkxi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yongpay.top/Article/details/gtubwngoov.html

[S21] C：字符类别判断
来源：http://dali.nanxinkj.top/Article/details/gtmdkkkdiq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cdnleiting.top/Article/details/gtmdqpmrhw.html

[S22] C：字符串转数字
来源：http://dali.bjfxy.top/Article/details/gtkenvvltc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hammf.cn/Article/details/gtcelxejou.html

[S23] C：随机数
来源：http://dali.zycfv.cn/Article/details/gtxmvyzcte.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.redwolf501.top/Article/details/gtxzcwhtun.html

[S24] C：获取本地时间
来源：http://dali.pengpengdd.cyou/Article/details/gtjfryrhls.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jlsjyb.cn/Article/details/gtosqanbmz.html

[S25] C：内存拷贝
来源：http://dali.snrcjt.cn/Article/details/gtbrariinx.html

memcpy(dst, src, n);
来源：http://dali.gotoacloud.top/Article/details/gteobckvld.html

[S26] C：内存清零
来源：http://dali.ybcxt.top/Article/details/gtedhhlple.html

memset(a, 0, sizeof a);
来源：http://dali.aizwys.cn/Article/details/gteorxaoef.html

[S27] C：定义常量
来源：http://dali.c1oappe.top/Article/details/gtvonpscga.html

const double PI = 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gtlqghbqmh.html

[S28] C：静态变量
来源：http://dali.zhongyouzk.top/Article/details/gtthyvzryd.html

static int counter = 0;
来源：http://dali.jlsjyb.cn/Article/details/gtxdgkqaeu.html

[S29] C：变参函数
来源：http://dali.ybcxt.top/Article/details/gtkbryzois.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gtznxnufid.html

[S30] C：头文件保护
来源：http://dali.tanke756.top/Article/details/gtdumyfwkx.html

#ifndef X_H
来源：http://dali.zhoulong.xyz/Article/details/gtldljoehd.html

#define X_H
来源：http://dali.yj20258888.top/Article/details/gtzlsbqgvn.html

#endif
来源：http://dali.yuxming.cn/Article/details/gtcjqukrtg.html

[S31] C++：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtiunthzbj.html

#include <iostream>
来源：http://dali.xziqi.cn/Article/details/gtizpjcmqg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.nwbrower.top/Article/details/gtcljffghp.html

[S32] C++：字符串
来源：http://dali.yongpay.top/Article/details/gtalvbbugy.html

std::string s = "hi";  s += "!";
来源：http://dali.gogol.net.cn/Article/details/gttxpokroa.html

[S33] C++：vector 增删
来源：http://dali.tian-w.cn/Article/details/gtdvsswpyd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.nwbrower.top/Article/details/gtkktibaob.html

[S34] C++：遍历 vector
来源：http://dali.andypj.xyz/Article/details/gtaqgjxdng.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ydzc1.top/Article/details/gtdmypmnyd.html

[S35] C++：map
来源：http://dali.shuidangran.top/Article/details/gtzxfhfsjl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ybcxt.top/Article/details/gtlsyotvxu.html

[S36] C++：unordered_map
来源：http://dali.ybcxt.top/Article/details/gtevolrmse.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yonumen.top/Article/details/gtdfilrkei.html

[S37] C++：set
来源：http://dali.sxryk.cn/Article/details/gtdkckzuxk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jqgfzy.top/Article/details/gtaigccoer.html

[S38] C++：排序
来源：http://dali.bjfxy.top/Article/details/gtwxfzzwad.html

std::sort(v.begin(), v.end());
来源：http://dali.9152youxi.cn/Article/details/gtvcnohtpe.html

[S39] C++：自定义比较器排序
来源：http://dali.smart0.xyz/Article/details/gtghadkxcd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xinyue.icu/Article/details/gtmyfenwmm.html

[S40] C++：查找元素
来源：http://dali.zhoulong.xyz/Article/details/gtppadbaty.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdqyolrxv.html

[S41] C++：类与构造函数
来源：http://dali.zhoulong.xyz/Article/details/gtyezefqeh.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hnqzz.top/Article/details/gtrmnirepk.html

[S42] C++：继承与虚函数
来源：http://dali.hysaishi.cn/Article/details/gtabgowwpe.html

class B : public Base { public: void f() override {} };
来源：http://dali.dashuyun.cn/Article/details/gtslrqriis.html

[S43] C++：智能指针
来源：http://dali.ehwqpu.com/Article/details/gtcyluvwhu.html

auto p = std::make_unique<int>(5);
来源：http://dali.jqgufenzy.top/Article/details/gtfchnpzrr.html

[S44] C++：引用传参
来源：http://dali.yuanzhike.top/Article/details/gtqinrwpgs.html

void inc(int &x) { ++x; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtocwsqgdr.html

[S45] C++：lambda
来源：http://dali.sxryk.cn/Article/details/gtspdiibuz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xuanzx.com/Article/details/gtcbinjrht.html

[S46] C++：函数模板
来源：http://dali.sufxvd.cn/Article/details/gtgjaubydu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtegmrbcpb.html

[S47] C++：结构化绑定遍历
来源：http://dali.yangfankeji.com/Article/details/gtcslmzamd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtddtloibb.html

[S48] C++：逐行读文件
来源：http://dali.gogol.net.cn/Article/details/gtkdtwagcn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjonifrz.html

while (std::getline(in, line)) { }
来源：http://dali.cheryme.top/Article/details/gtmnljyejd.html

[S49] C++：写文件
来源：http://dali.jinqigufen.top/Article/details/gtomncpaeq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhengqikj.top/Article/details/gtencvyydb.html

[S50] C++：格式化数字
来源：http://dali.havefunace.top/Article/details/gtamcchqxr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtikirfrrv.html

[S51] C++：显式类型转换
来源：http://dali.shzxlz.cn/Article/details/gtmmpeapkl.html

static_cast<double>(a) / b
来源：http://dali.birdmap.top/Article/details/gtuochjiix.html

[S52] C++：const 与 noexcept
来源：http://dali.zhiwuduotai.top/Article/details/gtqzfewvax.html

int size() const noexcept { return n_; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtuyazpbjn.html

[S53] C++：移动语义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxbtkttzu.html

std::vector<int> w = std::move(v);
来源：http://dali.guowangkeji.top/Article/details/gtfxwkfryr.html

[S54] C++：异常处理
来源：http://dali.meibo888.top/Article/details/gtxmzpxxvr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gzhubu.top/Article/details/gtpgvjjjzk.html

[S55] C++：结构化绑定
来源：http://dali.jyoumei.cn/Article/details/gtmgpclpzb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.meibo888.top/Article/details/gtbnoogxsl.html

[S56] C++：optional
来源：http://dali.nanxinkj.top/Article/details/gtfozemsmf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.sufxvd.cn/Article/details/gtfheovhfa.html

[S57] C++：编译期常量
来源：http://dali.zhoulong.xyz/Article/details/gtublpjmgg.html

constexpr int N = 10;
来源：http://dali.hywenlv.cn/Article/details/gtpgebykwx.html

[S58] C++：命名空间
来源：http://dali.svipenyu.cn/Article/details/gtyyoexrqk.html

namespace ns { int f() { return 1; } }
来源：http://dali.jlsjyb.cn/Article/details/gtdbucrlso.html

[S59] C++：静态断言
来源：http://dali.kuanghao11.cn/Article/details/gtfddogiin.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.dashuyun.cn/Article/details/gtarwfnrqv.html

[S60] C++：遍历并删除元素
来源：http://dali.hfpthk.cn/Article/details/gtlvyhdblk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.andypj.xyz/Article/details/gtdjoixkcl.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtqraxnryn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.andypj.xyz/Article/details/gthtjwovpe.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtlroflbit.html

[T01] Kotlin：Hello World
来源：http://dali.gogol.net.cn/Article/details/gteoldoarl.html

println("Hello")
来源：http://dali.kuanghao11.cn/Article/details/gtutofagbs.html

[T02] Kotlin：变量
来源：http://dali.yj20258888.top/Article/details/gtkwsifuvx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.fzhhl.top/Article/details/gtzxknudyh.html

[T03] Kotlin：字符串模板
来源：http://dali.yonumen.top/Article/details/gtmzykxdte.html

"值: $b"
来源：http://dali.bjfxy.top/Article/details/gtpcczuijt.html

[T04] Kotlin：空安全
来源：http://dali.yangfankeji.com/Article/details/gtsswpgmwk.html

val n: String? = null;  n?.length
来源：http://dali.gaohongyu789.top/Article/details/gtrsvmltiv.html

[T05] Kotlin：when 表达式
来源：http://dali.yongpay.top/Article/details/gttkokioap.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.cqqwz.cn/Article/details/gtufoyqwkr.html

[T06] Kotlin：集合映射
来源：http://dali.9152youxi.cn/Article/details/gtrtvirwhp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gtxjqzdrmt.html

[T07] Kotlin：集合过滤
来源：http://dali.chenzaomai.com/Article/details/gtpkekcktw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sufxvd.cn/Article/details/gtqqgqvhoi.html

[T08] Kotlin：数据类
来源：http://dali.zhixingplan.top/Article/details/gtqancqbvv.html

data class User(val name: String, val age: Int)
来源：http://dali.yonumen.top/Article/details/gtfsxudppj.html

[T09] Kotlin：扩展函数
来源：http://dali.aibaodan.cn/Article/details/gtnvfpcmrq.html

fun String.exclaim() = this + "!"
来源：http://dali.aizwys.cn/Article/details/gtwnnkwbux.html

[T10] Kotlin：默认参数
来源：http://dali.zhongyouzk.top/Article/details/gttwuxjzji.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.316326.xyz/Article/details/gtltdkqdun.html

[T11] Kotlin：协程
来源：http://dali.hnxiangtu.top/Article/details/gtgzzweven.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hysaishi.cn/Article/details/gtyhwmcecy.html

[T12] Kotlin：解构声明
来源：http://dali.jqgufenzy.top/Article/details/gtucqeeuhh.html

val (a, b) = Pair(1, 2)
来源：http://dali.jlsjyb.cn/Article/details/gtybmoyhto.html

[T13] Kotlin：只读 Map
来源：http://dali.xziqi.cn/Article/details/gtgppzufkv.html

val m = mapOf("a" to 1)
来源：http://dali.yuanzhike.top/Article/details/gtdoqjrahw.html

[T14] Kotlin：循环
来源：http://dali.feifeiyinyue.top/Article/details/gtkwjnynal.html

for (i in 1..10) println(i)
来源：http://dali.jlsjyb.cn/Article/details/gtpdzvegsp.html

[T15] Kotlin：接口
来源：http://dali.jqgfzy.top/Article/details/gtkeowripz.html

interface Shape { fun area(): Double }
来源：http://dali.zhoulong.xyz/Article/details/gtutjnmlkj.html

[T16] Swift：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtrmyxlzbu.html

print("Hello")
来源：http://dali.redwolf501.top/Article/details/gtbtktshno.html

[T17] Swift：变量与常量
来源：http://dali.sysykeji.top/Article/details/gthrnetdyj.html

var a = 1;  let b = 2
来源：http://dali.havefunace.top/Article/details/gtxuqlamkf.html

[T18] Swift：字符串插值
来源：http://dali.sxryk.cn/Article/details/gtwggnuiwb.html

"值: \(b)"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkolbayoa.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gtfuzmghde.html

if let n = opt { print(n) }
来源：http://dali.sxryk.cn/Article/details/gtqkrnlyqd.html

[T20] Swift：数组操作
来源：http://dali.jinqigufen.top/Article/details/gtxmpiaigs.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.nanxuanxn.top/Article/details/gtsbwxgnau.html

[T21] Swift：遍历
来源：http://dali.zdqjudy.top/Article/details/gtflhioajv.html

for x in a { print(x) }
来源：http://dali.chenlongwang.top/Article/details/gtxyldslfi.html

[T22] Swift：字典
来源：http://dali.ivvv.top/Article/details/gtaywulqjr.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.meibo888.top/Article/details/gtwatrxmnu.html

[T23] Swift：函数
来源：http://dali.ydzc1.top/Article/details/gtvtgoggde.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hysaishi.cn/Article/details/gtkrtqivzc.html

[T24] Swift：闭包
来源：http://dali.shzxlz.cn/Article/details/gtcrxmwjnc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxjyqoutr.html

[T25] Swift：结构体
来源：http://dali.yvedp.cn/Article/details/gtjmrxcrtr.html

struct P { var x: Int }
来源：http://dali.ivvv.top/Article/details/gtzjshqueb.html

[T26] Swift：类与重写
来源：http://dali.jinqigfzy.top/Article/details/gtknkfqvws.html

class A: Base { override func f() {} }
来源：http://dali.xinyue.icu/Article/details/gtcaujelww.html

[T27] Swift：错误处理
来源：http://dali.jyoumei.cn/Article/details/gtgsfaltxb.html

do { try f() } catch { print(error) }
来源：http://dali.jiagoushi.top/Article/details/gtpixtzvzg.html

[T28] Swift：枚举
来源：http://dali.zhoulong.xyz/Article/details/gtjnucsiwx.html

enum Color { case red, green }
来源：http://dali.zycfv.cn/Article/details/gtyfhuqqqt.html

[T29] Swift：guard 提前返回
来源：http://dali.nanxuanxn.top/Article/details/gtjxixyeyc.html

guard let x = opt else { return }
来源：http://dali.feifeiyinyue.top/Article/details/gtpqvggshw.html

[T30] Swift：协议
来源：http://dali.wangdashe.top/Article/details/gtreelqfsu.html

protocol Shape { func area() -> Double }
来源：http://dali.guannengcc.top/Article/details/gtdurdvniq.html

[T31] Lua：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtbnivtpuo.html

print("Hello")
来源：http://dali.haohaochexian.top/Article/details/gtjlleibxc.html

[T32] Lua：局部变量
来源：http://dali.aibaodan.cn/Article/details/gtqmjsaxms.html

local a = 1
来源：http://dali.zycfv.cn/Article/details/gtonsbksdx.html

[T33] Lua：表（数组）
来源：http://dali.andypj.xyz/Article/details/gtaepcjfet.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jinqigfzy.top/Article/details/gtjlcfbsgq.html

[T34] Lua：遍历表
来源：http://dali.zhengqikj.top/Article/details/gtngzxjaum.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcsdowpgd.html

[T35] Lua：字典表
来源：http://dali.sxryk.cn/Article/details/gtfdzvopnp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.vqdsnc.cn/Article/details/gtzgbfnnnu.html

[T36] Lua：函数
来源：http://dali.chenzaomai.com/Article/details/gtfnvbtzbg.html

function add(a, b) return a + b end
来源：http://dali.jinqigfzy.top/Article/details/gtfpufgzre.html

[T37] Lua：字符串拼接
来源：http://dali.gzhubu.top/Article/details/gtpeqcgrio.html

"a" .. "b"
来源：http://dali.cucudq.cn/Article/details/gtehlshvxy.html

[T38] Lua：条件
来源：http://dali.xuanzx.com/Article/details/gtiopdnyiv.html

if x > 0 then print("正") end
来源：http://dali.gaohongyu789.top/Article/details/gtschromyo.html

[T39] Lua：模式匹配
来源：http://dali.yonumen.top/Article/details/gtgfjlesxv.html

string.find(s, "%d+")
来源：http://dali.jyoumei.cn/Article/details/gtidavholt.html

[T40] Lua：元表
来源：http://dali.gzhubu.top/Article/details/gtpgbvqpto.html

setmetatable({}, { __index = base })
来源：http://dali.nanxinkj.top/Article/details/gtpcmwcrjx.html

[T41] Perl：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtyyoxnsof.html

print "Hello\n";
来源：http://dali.zhixingplan.top/Article/details/gtbhutjbcl.html

[T42] Perl：变量类型
来源：http://dali.316326.xyz/Article/details/gttzcvsrxp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.birdmap.top/Article/details/gtuhomgdvu.html

[T43] Perl：字符串插值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwpdgxeaz.html

"值: $a"
来源：http://dali.yanxiufei.cn/Article/details/gtqvfupydi.html

[T44] Perl：条件
来源：http://dali.xuetiantiany.cn/Article/details/gtujfaayqi.html

if ($a > 0) { print "正"; }
来源：http://dali.ydzc1.top/Article/details/gtfqcopwvu.html

[T45] Perl：数组遍历
来源：http://dali.gogol.net.cn/Article/details/gtihdffyrv.html

for my $x (@arr) { print $x; }
来源：http://dali.andypj.xyz/Article/details/gtedgpiami.html

[T46] Perl：哈希操作
来源：http://dali.jiagoushi.top/Article/details/gthonqzcms.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.chenzaomai.com/Article/details/gtfbehhnzq.html

[T47] Perl：正则捕获
来源：http://dali.zhiwuduotai.top/Article/details/gtcezjefcf.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xziqi.cn/Article/details/gtxgilriny.html

[T48] Perl：正则替换
来源：http://dali.bjfxy.top/Article/details/gtumvzrgvg.html

$s =~ s/old/new/g;
来源：http://dali.shanyushiyangtech.top/Article/details/gttqxfazgp.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gtzhikhioe.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtezxwkltl.html

[T50] Perl：逐行读文件
来源：http://dali.zhiwuduotai.top/Article/details/gtfjtntfke.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jqgfzy.top/Article/details/gtadjtsnmz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttlsnoyun.html

[T51] Scala：Hello World
来源：http://dali.hysaishi.cn/Article/details/gtwqagqsed.html

println("Hello")
来源：http://dali.haohaochexian.top/Article/details/gtttpateoe.html

[T52] Scala：变量
来源：http://dali.chenlongwang.top/Article/details/gthxgwcnsg.html

val a = 1;  var b = 2
来源：http://dali.andypj.xyz/Article/details/gtcfrngiip.html

[T53] Scala：字符串插值
来源：http://dali.wangdashe.top/Article/details/gtuucvosii.html

s"值: $b"
来源：http://dali.jqgufenzy.top/Article/details/gttvdkpakw.html

[T54] Scala：集合映射
来源：http://dali.chenzaomai.com/Article/details/gtwlgaoezl.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yanxiufei.cn/Article/details/gttfqrgqpk.html

[T55] Scala：集合过滤
来源：http://dali.wangshuangyany.cn/Article/details/gtkzkphgay.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jiagoushi.top/Article/details/gtvoowvcdn.html

[T56] Scala：样例类
来源：http://dali.zhiwuduotai.top/Article/details/gteeokebnt.html

case class User(name: String, age: Int)
来源：http://dali.hywenlv.cn/Article/details/gtwgfgrhst.html

[T57] Scala：模式匹配
来源：http://dali.cdnleiting.top/Article/details/gtpxqlywbd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.aizwys.cn/Article/details/gtkstthygw.html

[T58] Scala：函数定义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtekzyamuj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xuetiantiany.cn/Article/details/gtfrwnraqi.html

[T59] Scala：循环
来源：http://dali.zhongyouzk.top/Article/details/gtdrcumumy.html

for (i <- 1 to 10) println(i)
来源：http://dali.nanxuanxn.top/Article/details/gtwefbncik.html

[T60] Scala：折叠
来源：http://dali.wangdashe.top/Article/details/gtqbddcayc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.aibaodan.cn/Article/details/gtmqrjzmmj.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtsqilrgzk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.gogol.net.cn/Article/details/gtfcfdkuru.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gttcywwpdi.html

[U01] Py：创建虚拟环境
来源：http://dali.jyoumei.cn/Article/details/gtiyfetzwn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.nanxuanxn.top/Article/details/gtfctnfiku.html

[U02] Py：导出 / 安装依赖
来源：http://dali.quarkkingdee.top/Article/details/gtewvhcytn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gogol.net.cn/Article/details/gtzzafwnfa.html

[U03] Py：加载 .env 配置
来源：http://dali.nanxinkj.top/Article/details/gtmhhlwfou.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yuanzhike.top/Article/details/gtkvfdtzrq.html

[U04] Py：变量调试打印
来源：http://dali.jlsjyb.cn/Article/details/gtdmsijswg.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jiagoushi.top/Article/details/gtctipktxv.html


<!-- 参考信息 -->