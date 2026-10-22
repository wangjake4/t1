代发 wailian999

free -h;  ps aux | grep nginx
来源：http://dali.fzhhl.top/Article/details/gtimbidyif.html

[R64] 结束进程
来源：http://dali.jqgfzy.top/Article/details/gtinygiqam.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xuetiantiany.cn/Article/details/gtkvdtnyrb.html

[R65] 查看端口占用
来源：http://dali.jqgufenzy.top/Article/details/gtfwobgqqa.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhixingplan.top/Article/details/gtjfixfgam.html

[R66] 定时任务
来源：http://dali.yanxiufei.cn/Article/details/gtpfgzoggy.html

crontab -e;  crontab -l
来源：http://dali.wangshuangyany.cn/Article/details/gtlsidsufr.html

[R67] 生成随机十六进制串
来源：http://dali.yueranfly.top/Article/details/gtqqxjkivf.html

openssl rand -hex 16
来源：http://dali.daxiang520.top/Article/details/gtjewbgnwn.html

[R68] 计算文件校验值
来源：http://dali.shanyushiyangtech.top/Article/details/gtavszvqpi.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jqgfzy.top/Article/details/gtnfefqwgi.html

[R69] 生成随机密码
来源：http://dali.chenzaomai.com/Article/details/gtpabbsqev.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgskmaxyw.html

[R70] 时间戳与互转
来源：http://dali.gotoacloud.top/Article/details/gtvmalahuw.html

date +%s;  date -d @1700000000
来源：http://dali.kuanghao11.cn/Article/details/gtobghrbku.html

[R71] 日期格式化
来源：http://dali.havefunace.top/Article/details/gtqvlcyiqf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj20258888.top/Article/details/gtrgvynhmn.html

[R72] 等待端口就绪
来源：http://dali.hywenlv.cn/Article/details/gtbkxrfzzf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.dianchejie.cn/Article/details/gtuiysqzfr.html

[R73] 分割大日志
来源：http://dali.fzhhl.top/Article/details/gtkcrkyihx.html

split -l 1000 big.log part_
来源：http://dali.gotoacloud.top/Article/details/gtwqtkxcza.html

[R74] 批量重命名
来源：http://dali.zhongyouzk.top/Article/details/gtpnvqvzke.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtexelkojh.html

[R75] 导出环境变量
来源：http://dali.andypj.xyz/Article/details/gtcbatsxpz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.guannengcc.top/Article/details/gtgcfbocoh.html

[R76] 使用临时文件
来源：http://dali.hfpthk.cn/Article/details/gtytuewruf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shangyingyoupin.top/Article/details/gtaoeurxmt.html

[R77] 读取用户输入
来源：http://dali.yj20258.top/Article/details/gtmleimady.html

read -rp "请输入: " ans
来源：http://dali.sysykeji.top/Article/details/gtiesddfud.html

[R78] 交互式菜单
来源：http://dali.jqgfzy.top/Article/details/gtldmsbywp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shuidangran.top/Article/details/gttllhzwwn.html

[R79] 解析命令行选项
来源：http://dali.jinqigfzy.top/Article/details/gtxuxdteps.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cdnleiting.top/Article/details/gttkiothiw.html

[R80] 查看脚本执行耗时
来源：http://dali.nwbrower.top/Article/details/gtvulvmcgh.html

time ./run.sh
来源：http://dali.andypj.xyz/Article/details/gthzbprxcu.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtqqiwdmlo.html

S. C / C++ 专题
来源：http://dali.gogol.net.cn/Article/details/gtlmjmcurl.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtvhtkikjg.html

[S01] C：Hello World
来源：http://dali.jianghu66.top/Article/details/gtxdxhcqay.html

#include <stdio.h>
来源：http://dali.jinghuilouyu.cn/Article/details/gtjgybwchq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yangfankeji.com/Article/details/gtblmhfrpg.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gtuwmmrsus.html

int a = 10; printf("%d\n", a);
来源：http://dali.sxryk.cn/Article/details/gtuzggfiiz.html

[S03] C：读入整数
来源：http://dali.andypj.xyz/Article/details/gthwpzqfwi.html

int x; scanf("%d", &x);
来源：http://dali.gotoacloud.top/Article/details/gtonqvzhid.html

[S04] C：字符串复制
来源：http://dali.xziqi.cn/Article/details/gtsygwsyhm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yueranfly.top/Article/details/gtxynhmivq.html

[S05] C：字符串长度
来源：http://dali.snrcjt.cn/Article/details/gtvfcqqcfc.html

strlen(s)
来源：http://dali.sweek.top/Article/details/gtfdnwttri.html

[S06] C：字符串比较
来源：http://dali.gogol.net.cn/Article/details/gtlaoedqih.html

strcmp(a, b) == 0
来源：http://dali.chenzaomai.com/Article/details/gtotpjzihv.html

[S07] C：数组遍历求和
来源：http://dali.haohaochexian.top/Article/details/gtyzlwpowk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hnxiangtu.top/Article/details/gteptjhaud.html

[S08] C：动态内存分配与释放
来源：http://dali.xinyue.icu/Article/details/gtyocluwfd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.aibaodan.cn/Article/details/gtlqbmmgoc.html

[S09] C：结构体定义与初始化
来源：http://dali.nwbrower.top/Article/details/gtdlzuqzqj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.chenzaomai.com/Article/details/gtzdayjzmi.html

[S10] C：指针与解引用
来源：http://dali.zhongyouzk.top/Article/details/gtpstjnwup.html

int *p = &a;  *p = 5;
来源：http://dali.smart0.xyz/Article/details/gtstjleexa.html

[S11] C：逐行读文件
来源：http://dali.wangshuangyany.cn/Article/details/gtadebiexq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinghuilouyu.cn/Article/details/gthwhrkzbk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yangfankeji.com/Article/details/gtvqzypmdh.html

fclose(f);
来源：http://dali.xziqi.cn/Article/details/gtqakwizyk.html

[S12] C：写文件
来源：http://dali.gogol.net.cn/Article/details/gtvcoovgzv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yanxiufei.cn/Article/details/gtcqcvvqto.html

[S13] C：宏定义
来源：http://dali.hysaishi.cn/Article/details/gtkcmdgrjh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gotoacloud.top/Article/details/gtfdjocwii.html

[S14] C：枚举
来源：http://dali.quarkkingdee.top/Article/details/gtdctxrqvm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cashguo.top/Article/details/gtakrabhia.html

[S15] C：类型转换
来源：http://dali.aibaodan.cn/Article/details/gtpclqusgr.html

(double) a / b
来源：http://dali.nanxuanxn.top/Article/details/gtyuoxeeoa.html

[S16] C：位操作置位
来源：http://dali.shanyushiyangtech.top/Article/details/gtjjibmkcy.html

x |= (1 << 3);
来源：http://dali.cdnleiting.top/Article/details/gtoujcypdr.html

[S17] C：安全拼接字符串
来源：http://dali.nwbrower.top/Article/details/gtcrmdyqjd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cashguo.top/Article/details/gtognujmjn.html

[S18] C：命令行参数
来源：http://dali.dianchejie.cn/Article/details/gtrnrfuqgx.html

int main(int argc, char **argv)
来源：http://dali.sweek.top/Article/details/gtchctxusv.html

[S19] C：快速排序
来源：http://dali.quarkkingdee.top/Article/details/gtzjxdhscr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jlsjyb.cn/Article/details/gtiwngbffv.html

[S20] C：二分查找
来源：http://dali.zhongyouzk.top/Article/details/gtqmkpewip.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cucudq.cn/Article/details/gtqteywiaz.html

[S21] C：字符类别判断
来源：http://dali.hongshengwenyu.top/Article/details/gtjwoycful.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sxryk.cn/Article/details/gtvykhqhme.html

[S22] C：字符串转数字
来源：http://dali.hongshengwenyu.top/Article/details/gtzvaypyxx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.0kj1m.cn/Article/details/gtzxquldga.html

[S23] C：随机数
来源：http://dali.snrcjt.cn/Article/details/gtizugbmqv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shuidangran.top/Article/details/gtbgemqpsg.html

[S24] C：获取本地时间
来源：http://dali.feifeiyinyue.top/Article/details/gtlwxyjrec.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.316326.xyz/Article/details/gtxhifbibk.html

[S25] C：内存拷贝
来源：http://dali.hongshengwenyu.top/Article/details/gtwxzdkpbf.html

memcpy(dst, src, n);
来源：http://dali.jyoumei.cn/Article/details/gtxkqrrdfx.html

[S26] C：内存清零
来源：http://dali.ybcxt.top/Article/details/gtggwtnpta.html

memset(a, 0, sizeof a);
来源：http://dali.aizwys.cn/Article/details/gtlctquugm.html

[S27] C：定义常量
来源：http://dali.fengsongda.top/Article/details/gthbfyummp.html

const double PI = 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gthzbkejmx.html

[S28] C：静态变量
来源：http://dali.cqqwz.cn/Article/details/gtppdcczww.html

static int counter = 0;
来源：http://dali.yangfankeji.com/Article/details/gtgdghrlqt.html

[S29] C：变参函数
来源：http://dali.shangyingyoupin.top/Article/details/gtvrztskds.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.0kj1m.cn/Article/details/gttiszkezy.html

[S30] C：头文件保护
来源：http://dali.zhiwuduotai.top/Article/details/gtfguzmsht.html

#ifndef X_H
来源：http://dali.dianchejie.cn/Article/details/gtrkimfgvy.html

#define X_H
来源：http://dali.cheryme.top/Article/details/gtgxlzweik.html

#endif
来源：http://dali.fengsongda.top/Article/details/gtmkbzivwo.html

[S31] C++：Hello World
来源：http://dali.bjfxy.top/Article/details/gtjvvjhxkm.html

#include <iostream>
来源：http://dali.nanxinkj.top/Article/details/gtmfrhovvp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.0kj1m.cn/Article/details/gtempkvasf.html

[S32] C++：字符串
来源：http://dali.fzhhl.top/Article/details/gtpwjciesc.html

std::string s = "hi";  s += "!";
来源：http://dali.hnqzz.top/Article/details/gtnsrxixdd.html

[S33] C++：vector 增删
来源：http://dali.hysaishi.cn/Article/details/gtqebrjvtr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnglbatge.html

[S34] C++：遍历 vector
来源：http://dali.9152youxi.cn/Article/details/gtajezuvuj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.chenzaomai.com/Article/details/gtzmbrdnon.html

[S35] C++：map
来源：http://dali.cheryme.top/Article/details/gtliecqjfk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gtwvxiziha.html

[S36] C++：unordered_map
来源：http://dali.nwbrower.top/Article/details/gtsiiawimg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xylfe.cn/Article/details/gtvmqsfzij.html

[S37] C++：set
来源：http://dali.hongshengwenyu.top/Article/details/gttqblijyq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shzxlz.cn/Article/details/gtemzflmac.html

[S38] C++：排序
来源：http://dali.havefunace.top/Article/details/gtjdyodhgv.html

std::sort(v.begin(), v.end());
来源：http://dali.yuanzhike.top/Article/details/gtxecltiox.html

[S39] C++：自定义比较器排序
来源：http://dali.hammf.cn/Article/details/gtlocaqpdk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cucudq.cn/Article/details/gtnyhzewrc.html

[S40] C++：查找元素
来源：http://dali.yuxming.cn/Article/details/gtbqodpoyu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.tanke756.top/Article/details/gthjbemvip.html

[S41] C++：类与构造函数
来源：http://dali.shzxlz.cn/Article/details/gtugkyjaqp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkffpwnfx.html

[S42] C++：继承与虚函数
来源：http://dali.daria6918.cn/Article/details/gtuhivmfmr.html

class B : public Base { public: void f() override {} };
来源：http://dali.shangyingyoupin.top/Article/details/gtpnxejhjz.html

[S43] C++：智能指针
来源：http://dali.hnxiangtu.top/Article/details/gtkqzsduvg.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtljkyznak.html

[S44] C++：引用传参
来源：http://dali.fzhhl.top/Article/details/gtmyrkagxc.html

void inc(int &x) { ++x; }
来源：http://dali.zhengqikj.top/Article/details/gtzwjvnlpn.html

[S45] C++：lambda
来源：http://dali.yuanzhike.top/Article/details/gtwwuhapln.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.mhx1999.top/Article/details/gtxvolzpuv.html

[S46] C++：函数模板
来源：http://dali.fengsongda.top/Article/details/gtaytdthzz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinqigufen.top/Article/details/gtotpuatry.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhongyouzk.top/Article/details/gtbvjgppru.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.svipenyu.cn/Article/details/gttxkarubb.html

[S48] C++：逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gtcslngybm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jianghu66.top/Article/details/gtbpxvflnr.html

while (std::getline(in, line)) { }
来源：http://dali.jiagoushi.top/Article/details/gttkbnuxbv.html

[S49] C++：写文件
来源：http://dali.zhoulong.xyz/Article/details/gtxmstjkht.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinghuilouyu.cn/Article/details/gtaqkdowlt.html

[S50] C++：格式化数字
来源：http://dali.cqqwz.cn/Article/details/gtgcqwqknc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gtsnjxvqej.html

[S51] C++：显式类型转换
来源：http://dali.nwbrower.top/Article/details/gtquewpyqg.html

static_cast<double>(a) / b
来源：http://dali.gotoacloud.top/Article/details/gtpvrxdeie.html

[S52] C++：const 与 noexcept
来源：http://dali.cheryme.top/Article/details/gtjgaraadi.html

int size() const noexcept { return n_; }
来源：http://dali.pengpengdd.cyou/Article/details/gtpogbpwug.html

[S53] C++：移动语义
来源：http://dali.wangshuangyany.cn/Article/details/gtkpnrkajc.html

std::vector<int> w = std::move(v);
来源：http://dali.cqqwz.cn/Article/details/gtunaqndis.html

[S54] C++：异常处理
来源：http://dali.yuanzhike.top/Article/details/gtepaybnmf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.aizwys.cn/Article/details/gtxfkgrwyj.html

[S55] C++：结构化绑定
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtspbiqafi.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.nanxuanxn.top/Article/details/gtmmnxqehw.html

[S56] C++：optional
来源：http://dali.yuanzhike.top/Article/details/gtrvqkjwbk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.aizwys.cn/Article/details/gtkaaiybjf.html

[S57] C++：编译期常量
来源：http://dali.andypj.xyz/Article/details/gtgsthnsko.html

constexpr int N = 10;
来源：http://dali.guannengcc.top/Article/details/gtpekwxgow.html

[S58] C++：命名空间
来源：http://dali.gotoacloud.top/Article/details/gtnweguztr.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhengqikj.top/Article/details/gtfahksxwi.html

[S59] C++：静态断言
来源：http://dali.tianlin.xyz/Article/details/gtpeqvzxxy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.aizwys.cn/Article/details/gtpasmpcmz.html

[S60] C++：遍历并删除元素
来源：http://dali.quarkkingdee.top/Article/details/gtyelomsih.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yangfankeji.com/Article/details/gtonyzamvj.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtawjsovoj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hfpthk.cn/Article/details/gtbczedeni.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtvvmrgsqq.html

[T01] Kotlin：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtycyfozxk.html

println("Hello")
来源：http://dali.gotoacloud.top/Article/details/gtnzafvnre.html

[T02] Kotlin：变量
来源：http://dali.hysaishi.cn/Article/details/gttsvbuapk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrtbaoejx.html

[T03] Kotlin：字符串模板
来源：http://dali.jinqigufen.top/Article/details/gtlgklsuwh.html

"值: $b"
来源：http://dali.hnqzz.top/Article/details/gtcmrppild.html

[T04] Kotlin：空安全
来源：http://dali.haohaochexian.top/Article/details/gtbmucxeqy.html

val n: String? = null;  n?.length
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrhsmloza.html

[T05] Kotlin：when 表达式
来源：http://dali.mhx1999.top/Article/details/gtngvdqdhv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gzhubu.top/Article/details/gtwoagfrth.html

[T06] Kotlin：集合映射
来源：http://dali.ivvv.top/Article/details/gtdvgbgbuo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.9152youxi.cn/Article/details/gtkrkkhzrd.html

[T07] Kotlin：集合过滤
来源：http://dali.gotoacloud.top/Article/details/gtpicqifoz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.kuanghao11.cn/Article/details/gtukykuhrj.html

[T08] Kotlin：数据类
来源：http://dali.hnqzz.top/Article/details/gtzhtxbkep.html

data class User(val name: String, val age: Int)
来源：http://dali.zhengqikj.top/Article/details/gtemvffqry.html

[T09] Kotlin：扩展函数
来源：http://dali.hfpthk.cn/Article/details/gtyapqsgqi.html

fun String.exclaim() = this + "!"
来源：http://dali.sysykeji.top/Article/details/gtaysbeoxb.html

[T10] Kotlin：默认参数
来源：http://dali.shanyushiyangtech.top/Article/details/gtbkrpillm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.nanxinkj.top/Article/details/gtexoqgisy.html

[T11] Kotlin：协程
来源：http://dali.yueranfly.top/Article/details/gtounmymet.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shuidangran.top/Article/details/gtuwspljqc.html

[T12] Kotlin：解构声明
来源：http://dali.sysykeji.top/Article/details/gtgjusukvh.html

val (a, b) = Pair(1, 2)
来源：http://dali.yangfankeji.com/Article/details/gtqjaeqhjx.html

[T13] Kotlin：只读 Map
来源：http://dali.jianghu66.top/Article/details/gtebskridn.html

val m = mapOf("a" to 1)
来源：http://dali.tian-w.cn/Article/details/gtuauzxfgi.html

[T14] Kotlin：循环
来源：http://dali.jyoumei.cn/Article/details/gtgtxnptdg.html

for (i in 1..10) println(i)
来源：http://dali.gotoacloud.top/Article/details/gtdgwnkqxd.html

[T15] Kotlin：接口
来源：http://dali.yj20258.top/Article/details/gtnryjzpyx.html

interface Shape { fun area(): Double }
来源：http://dali.mhx1999.top/Article/details/gtnlwunmev.html

[T16] Swift：Hello World
来源：http://dali.smart0.xyz/Article/details/gtzepeqwpm.html

print("Hello")
来源：http://dali.ybcxt.top/Article/details/gtcgcqahfg.html

[T17] Swift：变量与常量
来源：http://dali.havefunace.top/Article/details/gtotxgvonj.html

var a = 1;  let b = 2
来源：http://dali.c1oappe.top/Article/details/gtxvezzzzv.html

[T18] Swift：字符串插值
来源：http://dali.chenjidiqi.icu/Article/details/gtkarcpqrv.html

"值: \(b)"
来源：http://dali.yanxiufei.cn/Article/details/gtuscksmfm.html

[T19] Swift：可选绑定
来源：http://dali.sysykeji.top/Article/details/gtpcacnerl.html

if let n = opt { print(n) }
来源：http://dali.haohaochexian.top/Article/details/gtxqymagwl.html

[T20] Swift：数组操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsaywxphi.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hammf.cn/Article/details/gtrzsysiee.html

[T21] Swift：遍历
来源：http://dali.shangyingyoupin.top/Article/details/gthlplgovk.html

for x in a { print(x) }
来源：http://dali.chenlongwang.top/Article/details/gtqoqwqnsw.html

[T22] Swift：字典
来源：http://dali.jqgfzy.top/Article/details/gtctakvyzz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yj20258888.top/Article/details/gtfeedbcvg.html

[T23] Swift：函数
来源：http://dali.ppjwa.cn/Article/details/gtglvslcss.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sufxvd.cn/Article/details/gtwmaxguzl.html

[T24] Swift：闭包
来源：http://dali.ivvv.top/Article/details/gtlkqocwex.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xinyue.icu/Article/details/gtqwqddaln.html

[T25] Swift：结构体
来源：http://dali.chenjidiqi.icu/Article/details/gtcoumqcqz.html

struct P { var x: Int }
来源：http://dali.andypj.xyz/Article/details/gtnrxklsxj.html

[T26] Swift：类与重写
来源：http://dali.hysaishi.cn/Article/details/gtrhccdjni.html

class A: Base { override func f() {} }
来源：http://dali.jqgufenzy.top/Article/details/gtwvdtqqkh.html

[T27] Swift：错误处理
来源：http://dali.iojbl.cn/Article/details/gtglloepfi.html

do { try f() } catch { print(error) }
来源：http://dali.wangshuangyany.cn/Article/details/gtbyhezzxu.html

[T28] Swift：枚举
来源：http://dali.xziqi.cn/Article/details/gtfdmxclpn.html

enum Color { case red, green }
来源：http://dali.jqgufenzy.top/Article/details/gtylphssdb.html

[T29] Swift：guard 提前返回
来源：http://dali.xuetiantiany.cn/Article/details/gtumsxhzfd.html

guard let x = opt else { return }
来源：http://dali.snrcjt.cn/Article/details/gtzhxynxms.html

[T30] Swift：协议
来源：http://dali.svipenyu.cn/Article/details/gtrtalxeth.html

protocol Shape { func area() -> Double }
来源：http://dali.gotoacloud.top/Article/details/gtsfmgzori.html

[T31] Lua：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtvwgxwgbg.html

print("Hello")
来源：http://dali.sxryk.cn/Article/details/gtryjrpvuq.html

[T32] Lua：局部变量
来源：http://dali.hywenlv.cn/Article/details/gtplxwbtgs.html

local a = 1
来源：http://dali.gaohongyu789.top/Article/details/gtgefzniue.html

[T33] Lua：表（数组）
来源：http://dali.andypj.xyz/Article/details/gtniuitapr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.9152youxi.cn/Article/details/gtumbzqwrm.html

[T34] Lua：遍历表
来源：http://dali.cqqwz.cn/Article/details/gtcwmqgmjk.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.smart0.xyz/Article/details/gtufnyatpw.html

[T35] Lua：字典表
来源：http://dali.pengpengdd.cyou/Article/details/gtumoprzqf.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jyoumei.cn/Article/details/gtjcicmbfl.html

[T36] Lua：函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtgcblweui.html

function add(a, b) return a + b end
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlokhxfpi.html

[T37] Lua：字符串拼接
来源：http://dali.cqqwz.cn/Article/details/gtubktdqxm.html

"a" .. "b"
来源：http://dali.jinqigufen.top/Article/details/gtkczxdbub.html

[T38] Lua：条件
来源：http://dali.yongpay.top/Article/details/gtmpstuccj.html

if x > 0 then print("正") end
来源：http://dali.gaohongyu789.top/Article/details/gtogljfmsz.html

[T39] Lua：模式匹配
来源：http://dali.guannengcc.top/Article/details/gtkfhbyxtu.html

string.find(s, "%d+")
来源：http://dali.hammf.cn/Article/details/gtptrfmlba.html

[T40] Lua：元表
来源：http://dali.fzhhl.top/Article/details/gtpgceheri.html

setmetatable({}, { __index = base })
来源：http://dali.yj20258888.top/Article/details/gtqpjhcrqu.html

[T41] Perl：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgelwudpo.html

print "Hello\n";
来源：http://dali.nanxinkj.top/Article/details/gtfxefgskj.html

[T42] Perl：变量类型
来源：http://dali.gogol.net.cn/Article/details/gtsohppygs.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.feifeiyinyue.top/Article/details/gtwlbfjcql.html

[T43] Perl：字符串插值
来源：http://dali.yanxiufei.cn/Article/details/gtwbncxcxp.html

"值: $a"
来源：http://dali.pycfn.com/Article/details/gtcpmprate.html

[T44] Perl：条件
来源：http://dali.zhixingplan.top/Article/details/gtxbawvanl.html

if ($a > 0) { print "正"; }
来源：http://dali.cucudq.cn/Article/details/gtjeojffpb.html

[T45] Perl：数组遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnqhsddai.html

for my $x (@arr) { print $x; }
来源：http://dali.ydzc1.top/Article/details/gtknkzrmpv.html

[T46] Perl：哈希操作
来源：http://dali.guowangkeji.top/Article/details/gtvkeqzdle.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.tanke756.top/Article/details/gtjtjtdzdz.html

[T47] Perl：正则捕获
来源：http://dali.hfpthk.cn/Article/details/gtmobtrejy.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yanxiufei.cn/Article/details/gtdptvrpmz.html

[T48] Perl：正则替换
来源：http://dali.gogol.net.cn/Article/details/gtwhfpibfo.html

$s =~ s/old/new/g;
来源：http://dali.jinqigufen.top/Article/details/gtnbnthwgi.html

[T49] Perl：函数
来源：http://dali.quarkkingdee.top/Article/details/gtxpblwuyc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hywenlv.cn/Article/details/gtxrqonlzl.html

[T50] Perl：逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzyrobbxh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.tianlin.xyz/Article/details/gthokupgkn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jinqigfzy.top/Article/details/gtcfwmanqa.html

[T51] Scala：Hello World
来源：http://dali.cdnleiting.top/Article/details/gtsuloaybe.html

println("Hello")
来源：http://dali.quarkkingdee.top/Article/details/gtvaroofoo.html

[T52] Scala：变量
来源：http://dali.ehwqpu.com/Article/details/gtqmowldft.html

val a = 1;  var b = 2
来源：http://dali.tian-w.cn/Article/details/gtynqipdmk.html

[T53] Scala：字符串插值
来源：http://dali.daria6918.cn/Article/details/gtaxjnbenw.html

s"值: $b"
来源：http://dali.redwolf501.top/Article/details/gtlozmpsxu.html

[T54] Scala：集合映射
来源：http://dali.sufxvd.cn/Article/details/gtaerzinni.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhixingplan.top/Article/details/gtzgvoqjoo.html

[T55] Scala：集合过滤
来源：http://dali.jinqigufen.top/Article/details/gtfmiiegtd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.nanxuanxn.top/Article/details/gtvmijmrpg.html

[T56] Scala：样例类
来源：http://dali.xuanzx.com/Article/details/gtkqgiivcv.html

case class User(name: String, age: Int)
来源：http://dali.smart0.xyz/Article/details/gtontqcgyf.html

[T57] Scala：模式匹配
来源：http://dali.yanxiufei.cn/Article/details/gtdzrotqwu.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shuidangran.top/Article/details/gtygobqkvg.html

[T58] Scala：函数定义
来源：http://dali.cheryme.top/Article/details/gtstjbvlrj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.xinyue.icu/Article/details/gtjtpzfbth.html

[T59] Scala：循环
来源：http://dali.iojbl.cn/Article/details/gtlaicjram.html

for (i <- 1 to 10) println(i)
来源：http://dali.shuidangran.top/Article/details/gtwahpkqcg.html

[T60] Scala：折叠
来源：http://dali.pengpengdd.cyou/Article/details/gtreftdyeg.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jinqigufen.top/Article/details/gtwszgsnea.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtvxlyfbiy.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yanxiufei.cn/Article/details/gtpkkeojgq.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtaxbxtsaz.html

[U01] Py：创建虚拟环境
来源：http://dali.nwbrower.top/Article/details/gtxnligbpv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xylfe.cn/Article/details/gtzlfrkocv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xylfe.cn/Article/details/gtwkuoyudq.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhongyouzk.top/Article/details/gttiaacnwe.html

[U03] Py：加载 .env 配置
来源：http://dali.guowangkeji.top/Article/details/gthelldgii.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.cashguo.top/Article/details/gtpjreppof.html

[U04] Py：变量调试打印
来源：http://dali.xinyue.icu/Article/details/gtsnqaoxjw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yonumen.top/Article/details/gtuhfocskl.html


<!-- 参考信息 -->