代发 wailian999

free -h;  ps aux | grep nginx
来源：http://dali.aibaodan.cn/Article/details/gtubylbgok.html

[R64] 结束进程
来源：http://dali.tanke756.top/Article/details/gtdrdmifpk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtplyehhkf.html

[R65] 查看端口占用
来源：http://dali.gzhubu.top/Article/details/gtmbjafzhn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hysaishi.cn/Article/details/gtaxbqsogt.html

[R66] 定时任务
来源：http://dali.shzxlz.cn/Article/details/gtxnwzfwog.html

crontab -e;  crontab -l
来源：http://dali.jyoumei.cn/Article/details/gtjhesvmvx.html

[R67] 生成随机十六进制串
来源：http://dali.ivvv.top/Article/details/gtfgcjvlel.html

openssl rand -hex 16
来源：http://dali.shuidangran.top/Article/details/gtjzdaojcp.html

[R68] 计算文件校验值
来源：http://dali.ehwqpu.com/Article/details/gtjtcvemwg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.kuanghao11.cn/Article/details/gtarfkutlr.html

[R69] 生成随机密码
来源：http://dali.jinqigufen.top/Article/details/gtdxlxyakc.html

head -c 16 /dev/urandom | base64
来源：http://dali.feifeiyinyue.top/Article/details/gtoclblbpw.html

[R70] 时间戳与互转
来源：http://dali.yuxming.cn/Article/details/gtnfjntuyj.html

date +%s;  date -d @1700000000
来源：http://dali.shzxlz.cn/Article/details/gtwlappnuw.html

[R71] 日期格式化
来源：http://dali.hywenlv.cn/Article/details/gtkixnepbr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gtihrrepyf.html

[R72] 等待端口就绪
来源：http://dali.zhengqikj.top/Article/details/gtwqnskphf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yuxming.cn/Article/details/gtwwkbkjor.html

[R73] 分割大日志
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkglidwta.html

split -l 1000 big.log part_
来源：http://dali.yuanzhike.top/Article/details/gtndlgonml.html

[R74] 批量重命名
来源：http://dali.yuxming.cn/Article/details/gtxojxxofa.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zycfv.cn/Article/details/gtowrsndhb.html

[R75] 导出环境变量
来源：http://dali.jinqigufen.top/Article/details/gtdkmidzua.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hongshengwenyu.top/Article/details/gtjcgynezb.html

[R76] 使用临时文件
来源：http://dali.yonumen.top/Article/details/gttexmhmvp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jlsjyb.cn/Article/details/gtzxctzhco.html

[R77] 读取用户输入
来源：http://dali.cucudq.cn/Article/details/gtbawfflhp.html

read -rp "请输入: " ans
来源：http://dali.gogol.net.cn/Article/details/gtinrulbeq.html

[R78] 交互式菜单
来源：http://dali.jianghu66.top/Article/details/gtqxfrfooe.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.chenzaomai.com/Article/details/gtgaictdva.html

[R79] 解析命令行选项
来源：http://dali.ehwqpu.com/Article/details/gtpvmbywjo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yvedp.cn/Article/details/gtnbrvohlu.html

[R80] 查看脚本执行耗时
来源：http://dali.aizwys.cn/Article/details/gtulslijwj.html

time ./run.sh
来源：http://dali.shuidangran.top/Article/details/gtvcyfkvpb.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gthyvsfkpu.html

S. C / C++ 专题
来源：http://dali.zhengqikj.top/Article/details/gtiacvuqor.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtbbvlsfxv.html

[S01] C：Hello World
来源：http://dali.daria6918.cn/Article/details/gtkrczlhhk.html

#include <stdio.h>
来源：http://dali.zdqjudy.top/Article/details/gtenxlwdkt.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yj20258.top/Article/details/gtojnfammx.html

[S02] C：变量与格式化输出
来源：http://dali.gzhubu.top/Article/details/gttepzwapg.html

int a = 10; printf("%d\n", a);
来源：http://dali.svipenyu.cn/Article/details/gtprewnuil.html

[S03] C：读入整数
来源：http://dali.yueranfly.top/Article/details/gtmrpbmsaw.html

int x; scanf("%d", &x);
来源：http://dali.yuanzhike.top/Article/details/gtijqwrfaf.html

[S04] C：字符串复制
来源：http://dali.zhoulong.xyz/Article/details/gtsahqarup.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.birdmap.top/Article/details/gtknmbkyqz.html

[S05] C：字符串长度
来源：http://dali.wangdashe.top/Article/details/gtklfiysbz.html

strlen(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtzfmaeksu.html

[S06] C：字符串比较
来源：http://dali.gaohongyu789.top/Article/details/gtmzhvkxfu.html

strcmp(a, b) == 0
来源：http://dali.shzxlz.cn/Article/details/gtzvqvvodg.html

[S07] C：数组遍历求和
来源：http://dali.gogol.net.cn/Article/details/gtfuzlaxfb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gogol.net.cn/Article/details/gtplktnfob.html

[S08] C：动态内存分配与释放
来源：http://dali.guowangkeji.top/Article/details/gtrthpbfmr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.aibaodan.cn/Article/details/gtsjfzloaw.html

[S09] C：结构体定义与初始化
来源：http://dali.yj20258888.top/Article/details/gtbdnspfcx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.mhx1999.top/Article/details/gtkicsstbr.html

[S10] C：指针与解引用
来源：http://dali.birdmap.top/Article/details/gtxetzqodt.html

int *p = &a;  *p = 5;
来源：http://dali.cheryme.top/Article/details/gtgewndzva.html

[S11] C：逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gtvplwhfnc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yueranfly.top/Article/details/gtcgdrgyjc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.fzhhl.top/Article/details/gtzbbwclmy.html

fclose(f);
来源：http://dali.nanxinkj.top/Article/details/gtjgllrrst.html

[S12] C：写文件
来源：http://dali.guowangkeji.top/Article/details/gthpqmkmsz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shangyingyoupin.top/Article/details/gtexzcxjoi.html

[S13] C：宏定义
来源：http://dali.xuetiantiany.cn/Article/details/gtsygeyisl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.aibaodan.cn/Article/details/gtpffmxozf.html

[S14] C：枚举
来源：http://dali.zhongyouzk.top/Article/details/gtqfgrfbao.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jianghu66.top/Article/details/gtqhtbeccq.html

[S15] C：类型转换
来源：http://dali.hnxiangtu.top/Article/details/gtwwvlwfgr.html

(double) a / b
来源：http://dali.gaohongyu789.top/Article/details/gtoewdnxyg.html

[S16] C：位操作置位
来源：http://dali.xylfe.cn/Article/details/gtkpvpkzdi.html

x |= (1 << 3);
来源：http://dali.yongpay.top/Article/details/gtejkxpuft.html

[S17] C：安全拼接字符串
来源：http://dali.jiagoushi.top/Article/details/gtuakduihn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cheryme.top/Article/details/gtjgrpmzdm.html

[S18] C：命令行参数
来源：http://dali.nanxuanxn.top/Article/details/gthjtginzb.html

int main(int argc, char **argv)
来源：http://dali.shuidangran.top/Article/details/gtmqrafuul.html

[S19] C：快速排序
来源：http://dali.hysaishi.cn/Article/details/gtfvmvzjlu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hfpthk.cn/Article/details/gtonrydunr.html

[S20] C：二分查找
来源：http://dali.0kj1m.cn/Article/details/gttjtiskfg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.guannengcc.top/Article/details/gtvcomwabr.html

[S21] C：字符类别判断
来源：http://dali.chenlongwang.top/Article/details/gtsidgsros.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xziqi.cn/Article/details/gtbnoazfnl.html

[S22] C：字符串转数字
来源：http://dali.daria6918.cn/Article/details/gtknpqdhmj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.gzhubu.top/Article/details/gtsgicegvf.html

[S23] C：随机数
来源：http://dali.zhongyouzk.top/Article/details/gtwkrvicir.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.snrcjt.cn/Article/details/gtfgebibtk.html

[S24] C：获取本地时间
来源：http://dali.ydzc1.top/Article/details/gtxxjythyy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtevfyxdfn.html

[S25] C：内存拷贝
来源：http://dali.zhoulong.xyz/Article/details/gtxwexgake.html

memcpy(dst, src, n);
来源：http://dali.jlsjyb.cn/Article/details/gtbpfgpnap.html

[S26] C：内存清零
来源：http://dali.jinyuanbaomall.cn/Article/details/gtznbwabqm.html

memset(a, 0, sizeof a);
来源：http://dali.shanyushiyangtech.top/Article/details/gtkdkhvihn.html

[S27] C：定义常量
来源：http://dali.jyoumei.cn/Article/details/gtvskchwot.html

const double PI = 3.14159;
来源：http://dali.fzhhl.top/Article/details/gtjmykhpsa.html

[S28] C：静态变量
来源：http://dali.kuanghao11.cn/Article/details/gtbgxpflqk.html

static int counter = 0;
来源：http://dali.fengsongda.top/Article/details/gtuaprmijd.html

[S29] C：变参函数
来源：http://dali.hnxiangtu.top/Article/details/gtpgzfzsza.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yuxming.cn/Article/details/gtuzebhsvi.html

[S30] C：头文件保护
来源：http://dali.xinyue.icu/Article/details/gtrvswzotd.html

#ifndef X_H
来源：http://dali.yanxiufei.cn/Article/details/gtsapfwqsa.html

#define X_H
来源：http://dali.aibaodan.cn/Article/details/gtohulttfr.html

#endif
来源：http://dali.hfpthk.cn/Article/details/gtdobkpijc.html

[S31] C++：Hello World
来源：http://dali.cheryme.top/Article/details/gtksjuvfoc.html

#include <iostream>
来源：http://dali.gzhubu.top/Article/details/gtytypzqke.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.iojbl.cn/Article/details/gtnjhqiqtx.html

[S32] C++：字符串
来源：http://dali.hnxiangtu.top/Article/details/gturfpmukr.html

std::string s = "hi";  s += "!";
来源：http://dali.ehwqpu.com/Article/details/gtgrhvsbkw.html

[S33] C++：vector 增删
来源：http://dali.yangfankeji.com/Article/details/gtaawuhixt.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hnxiangtu.top/Article/details/gtnagpscrq.html

[S34] C++：遍历 vector
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbcebyuer.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xuanzx.com/Article/details/gtbcjizeny.html

[S35] C++：map
来源：http://dali.ivvv.top/Article/details/gtnhcjhzkw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hfpthk.cn/Article/details/gtumpnqpxg.html

[S36] C++：unordered_map
来源：http://dali.tianlin.xyz/Article/details/gteyizqqsk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gtonlhkvcs.html

[S37] C++：set
来源：http://dali.bjfxy.top/Article/details/gtfvdxwzrh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yanxiufei.cn/Article/details/gtxjibieat.html

[S38] C++：排序
来源：http://dali.gogol.net.cn/Article/details/gtjzfofdcx.html

std::sort(v.begin(), v.end());
来源：http://dali.dashuyun.cn/Article/details/gtvzplvobq.html

[S39] C++：自定义比较器排序
来源：http://dali.sufxvd.cn/Article/details/gtbeckukoj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hywenlv.cn/Article/details/gtpzuplpal.html

[S40] C++：查找元素
来源：http://dali.yonumen.top/Article/details/gtmtlsdxzu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xuanzx.com/Article/details/gthumapwlt.html

[S41] C++：类与构造函数
来源：http://dali.chenjidiqi.icu/Article/details/gtgvarubqc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sysykeji.top/Article/details/gtxcczcsdo.html

[S42] C++：继承与虚函数
来源：http://dali.zhongyouzk.top/Article/details/gtmtsdemmj.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhiwuduotai.top/Article/details/gtixrqtmft.html

[S43] C++：智能指针
来源：http://dali.wangshuangyany.cn/Article/details/gtfxiblzve.html

auto p = std::make_unique<int>(5);
来源：http://dali.wangshuangyany.cn/Article/details/gtysxipqrk.html

[S44] C++：引用传参
来源：http://dali.zhengqikj.top/Article/details/gtstcjigju.html

void inc(int &x) { ++x; }
来源：http://dali.tanke756.top/Article/details/gtbrlpuoyb.html

[S45] C++：lambda
来源：http://dali.chenlongwang.top/Article/details/gtsiosilil.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.smart0.xyz/Article/details/gtlmgxrcga.html

[S46] C++：函数模板
来源：http://dali.cqqwz.cn/Article/details/gtvtbcjxln.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cheryme.top/Article/details/gtetzxesim.html

[S47] C++：结构化绑定遍历
来源：http://dali.shzxlz.cn/Article/details/gtwylwczje.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.tian-w.cn/Article/details/gtjjudzner.html

[S48] C++：逐行读文件
来源：http://dali.hnxiangtu.top/Article/details/gteuedqxpy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xziqi.cn/Article/details/gtbkhtdurx.html

while (std::getline(in, line)) { }
来源：http://dali.xziqi.cn/Article/details/gtkqvuvikb.html

[S49] C++：写文件
来源：http://dali.daxiang520.top/Article/details/gtlaxzmvwd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.daria6918.cn/Article/details/gtmvptblsz.html

[S50] C++：格式化数字
来源：http://dali.yongpay.top/Article/details/gtzcurkrsi.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gtlqddxkxc.html

[S51] C++：显式类型转换
来源：http://dali.guannengcc.top/Article/details/gtdqdndzfz.html

static_cast<double>(a) / b
来源：http://dali.yanxiufei.cn/Article/details/gtvcufwawi.html

[S52] C++：const 与 noexcept
来源：http://dali.cqqwz.cn/Article/details/gtxtwnsapu.html

int size() const noexcept { return n_; }
来源：http://dali.jqgufenzy.top/Article/details/gtsaffmjzg.html

[S53] C++：移动语义
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlkzjwvtu.html

std::vector<int> w = std::move(v);
来源：http://dali.hfpthk.cn/Article/details/gtrmlinsxy.html

[S54] C++：异常处理
来源：http://dali.aibaodan.cn/Article/details/gtvbkcltml.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.0kj1m.cn/Article/details/gtuoqchniw.html

[S55] C++：结构化绑定
来源：http://dali.zhongyouzk.top/Article/details/gtumhchuss.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zdqjudy.top/Article/details/gtsdxxqmcb.html

[S56] C++：optional
来源：http://dali.kuanghao11.cn/Article/details/gthikxfepp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zdqjudy.top/Article/details/gtotyjvcim.html

[S57] C++：编译期常量
来源：http://dali.hammf.cn/Article/details/gtegewdfzn.html

constexpr int N = 10;
来源：http://dali.gaohongyu789.top/Article/details/gtmvbktelb.html

[S58] C++：命名空间
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzedhjqhx.html

namespace ns { int f() { return 1; } }
来源：http://dali.gaohongyu789.top/Article/details/gtrztdlvfp.html

[S59] C++：静态断言
来源：http://dali.zhoulong.xyz/Article/details/gtfsregcfn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinqigfzy.top/Article/details/gtxeytnbfz.html

[S60] C++：遍历并删除元素
来源：http://dali.c1oappe.top/Article/details/gtfwxbmqlf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhengqikj.top/Article/details/gtvjlrtezh.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtnzgokfet.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jyoumei.cn/Article/details/gtymhfgoaz.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtixguzeym.html

[T01] Kotlin：Hello World
来源：http://dali.sxryk.cn/Article/details/gtymxswgwf.html

println("Hello")
来源：http://dali.zdqjudy.top/Article/details/gttlhncdtg.html

[T02] Kotlin：变量
来源：http://dali.tian-w.cn/Article/details/gtuaqkpcgg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhixingplan.top/Article/details/gtchkughdh.html

[T03] Kotlin：字符串模板
来源：http://dali.wangshuangyany.cn/Article/details/gtvyrwvris.html

"值: $b"
来源：http://dali.fengsongda.top/Article/details/gtbtwfylop.html

[T04] Kotlin：空安全
来源：http://dali.gaohongyu789.top/Article/details/gthxlmkcjw.html

val n: String? = null;  n?.length
来源：http://dali.cucudq.cn/Article/details/gtbgezveti.html

[T05] Kotlin：when 表达式
来源：http://dali.hfpthk.cn/Article/details/gtbpbduljs.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.chenzaomai.com/Article/details/gtlixdxwrq.html

[T06] Kotlin：集合映射
来源：http://dali.yj20258888.top/Article/details/gtwydyresq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hammf.cn/Article/details/gttslrsgcr.html

[T07] Kotlin：集合过滤
来源：http://dali.ivvv.top/Article/details/gtgsvhpulf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jyoumei.cn/Article/details/gtinaieduw.html

[T08] Kotlin：数据类
来源：http://dali.yj20258.top/Article/details/gtaxkfkkoz.html

data class User(val name: String, val age: Int)
来源：http://dali.yuanzhike.top/Article/details/gtsykxyptb.html

[T09] Kotlin：扩展函数
来源：http://dali.yanxiufei.cn/Article/details/gtevysvbie.html

fun String.exclaim() = this + "!"
来源：http://dali.smart0.xyz/Article/details/gtdprnadtb.html

[T10] Kotlin：默认参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpsalvsse.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jyoumei.cn/Article/details/gtuedmlnxh.html

[T11] Kotlin：协程
来源：http://dali.hysaishi.cn/Article/details/gtpmqngrfy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.guannengcc.top/Article/details/gtklryprbo.html

[T12] Kotlin：解构声明
来源：http://dali.dianchejie.cn/Article/details/gtpxgqbjtm.html

val (a, b) = Pair(1, 2)
来源：http://dali.smart0.xyz/Article/details/gtxmuwukft.html

[T13] Kotlin：只读 Map
来源：http://dali.gotoacloud.top/Article/details/gtqtkbmbfx.html

val m = mapOf("a" to 1)
来源：http://dali.vqdsnc.cn/Article/details/gtyhrlfqwx.html

[T14] Kotlin：循环
来源：http://dali.nanxinkj.top/Article/details/gteqryoilq.html

for (i in 1..10) println(i)
来源：http://dali.hnqzz.top/Article/details/gtipzavbil.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gtixdspbok.html

interface Shape { fun area(): Double }
来源：http://dali.sysykeji.top/Article/details/gtllyerljm.html

[T16] Swift：Hello World
来源：http://dali.pycfn.com/Article/details/gtniwnjpfd.html

print("Hello")
来源：http://dali.ehwqpu.com/Article/details/gthlciawre.html

[T17] Swift：变量与常量
来源：http://dali.yanxiufei.cn/Article/details/gtvpvbiuat.html

var a = 1;  let b = 2
来源：http://dali.yvedp.cn/Article/details/gtwvfsnoli.html

[T18] Swift：字符串插值
来源：http://dali.yvedp.cn/Article/details/gthonagopt.html

"值: \(b)"
来源：http://dali.jianghu66.top/Article/details/gthmcenrvs.html

[T19] Swift：可选绑定
来源：http://dali.sweek.top/Article/details/gtzjnwiyix.html

if let n = opt { print(n) }
来源：http://dali.nanxuanxn.top/Article/details/gtygzyioss.html

[T20] Swift：数组操作
来源：http://dali.guannengcc.top/Article/details/gtofhwmtap.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxysfuwg.html

[T21] Swift：遍历
来源：http://dali.zhixingplan.top/Article/details/gtofhcoeme.html

for x in a { print(x) }
来源：http://dali.zhengqikj.top/Article/details/gtpcgjvgea.html

[T22] Swift：字典
来源：http://dali.cashguo.top/Article/details/gttghcvrcg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqlvewbit.html

[T23] Swift：函数
来源：http://dali.cashguo.top/Article/details/gtzkwbsvdq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xziqi.cn/Article/details/gtaylmvjuu.html

[T24] Swift：闭包
来源：http://dali.ppjwa.cn/Article/details/gtztedwjuz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yonumen.top/Article/details/gtwiclvimg.html

[T25] Swift：结构体
来源：http://dali.hammf.cn/Article/details/gteadakxzz.html

struct P { var x: Int }
来源：http://dali.fengsongda.top/Article/details/gtjkdjkygw.html

[T26] Swift：类与重写
来源：http://dali.cdnleiting.top/Article/details/gtbgtfbgpp.html

class A: Base { override func f() {} }
来源：http://dali.ehwqpu.com/Article/details/gtdqzqyuhe.html

[T27] Swift：错误处理
来源：http://dali.hammf.cn/Article/details/gtgejoskvd.html

do { try f() } catch { print(error) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjdrjwgqq.html

[T28] Swift：枚举
来源：http://dali.xziqi.cn/Article/details/gtuzgaiiro.html

enum Color { case red, green }
来源：http://dali.quarkkingdee.top/Article/details/gttnttgpwu.html

[T29] Swift：guard 提前返回
来源：http://dali.yanxiufei.cn/Article/details/gtvjokfpbh.html

guard let x = opt else { return }
来源：http://dali.pengpengdd.cyou/Article/details/gtqkkikrlf.html

[T30] Swift：协议
来源：http://dali.cucudq.cn/Article/details/gtwidimdtm.html

protocol Shape { func area() -> Double }
来源：http://dali.hysaishi.cn/Article/details/gtfowtaycm.html

[T31] Lua：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsmwevmrr.html

print("Hello")
来源：http://dali.gogol.net.cn/Article/details/gtodnfivfl.html

[T32] Lua：局部变量
来源：http://dali.cqqwz.cn/Article/details/gtmzcwwiqk.html

local a = 1
来源：http://dali.hnqzz.top/Article/details/gtebyhogmy.html

[T33] Lua：表（数组）
来源：http://dali.pycfn.com/Article/details/gtyouzdohb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.c1oappe.top/Article/details/gtfqhtuhty.html

[T34] Lua：遍历表
来源：http://dali.guannengcc.top/Article/details/gtirerurms.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdhvgghop.html

[T35] Lua：字典表
来源：http://dali.fzhhl.top/Article/details/gtmzjmwitq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhoulong.xyz/Article/details/gtyaabnofq.html

[T36] Lua：函数
来源：http://dali.jlsjyb.cn/Article/details/gtrfmhcqek.html

function add(a, b) return a + b end
来源：http://dali.guowangkeji.top/Article/details/gtqtoeclch.html

[T37] Lua：字符串拼接
来源：http://dali.ivvv.top/Article/details/gtmwgtupxk.html

"a" .. "b"
来源：http://dali.dashuyun.cn/Article/details/gtbpuyhjxx.html

[T38] Lua：条件
来源：http://dali.nanxuanxn.top/Article/details/gtrplbdvvk.html

if x > 0 then print("正") end
来源：http://dali.jianghu66.top/Article/details/gtpdtczdis.html

[T39] Lua：模式匹配
来源：http://dali.quarkkingdee.top/Article/details/gtbweluued.html

string.find(s, "%d+")
来源：http://dali.jinqigufen.top/Article/details/gtnccvetat.html

[T40] Lua：元表
来源：http://dali.tian-w.cn/Article/details/gtspcpcfcc.html

setmetatable({}, { __index = base })
来源：http://dali.jlsjyb.cn/Article/details/gtkuqfmdqe.html

[T41] Perl：Hello World
来源：http://dali.daria6918.cn/Article/details/gtnbwjpifm.html

print "Hello\n";
来源：http://dali.hysaishi.cn/Article/details/gtcuyoirlj.html

[T42] Perl：变量类型
来源：http://dali.kuanghao11.cn/Article/details/gtcbuoyujr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyepoluzu.html

[T43] Perl：字符串插值
来源：http://dali.yanxiufei.cn/Article/details/gtybkbbxmw.html

"值: $a"
来源：http://dali.tian-w.cn/Article/details/gtqrsdycbp.html

[T44] Perl：条件
来源：http://dali.hywenlv.cn/Article/details/gtjegjtlkk.html

if ($a > 0) { print "正"; }
来源：http://dali.zhengqikj.top/Article/details/gtzamkgbsf.html

[T45] Perl：数组遍历
来源：http://dali.daria6918.cn/Article/details/gtiiovrmpv.html

for my $x (@arr) { print $x; }
来源：http://dali.pycfn.com/Article/details/gtnfktwaaf.html

[T46] Perl：哈希操作
来源：http://dali.ivvv.top/Article/details/gtylrjhzqh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yuanzhike.top/Article/details/gtvgspyhkx.html

[T47] Perl：正则捕获
来源：http://dali.daxiang520.top/Article/details/gtifxoowxp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdryxlzbx.html

[T48] Perl：正则替换
来源：http://dali.cheryme.top/Article/details/gtdyddaexm.html

$s =~ s/old/new/g;
来源：http://dali.feifeiyinyue.top/Article/details/gtgemgrirm.html

[T49] Perl：函数
来源：http://dali.zhiwuduotai.top/Article/details/gtiuwohsch.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwumufxeh.html

[T50] Perl：逐行读文件
来源：http://dali.birdmap.top/Article/details/gttjyywmua.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxqiwlria.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ybcxt.top/Article/details/gteftctgyz.html

[T51] Scala：Hello World
来源：http://dali.guannengcc.top/Article/details/gtbirzoyuv.html

println("Hello")
来源：http://dali.ydzc1.top/Article/details/gttjnkzflx.html

[T52] Scala：变量
来源：http://dali.vqdsnc.cn/Article/details/gtygydvxgs.html

val a = 1;  var b = 2
来源：http://dali.yj20258.top/Article/details/gthltueouh.html

[T53] Scala：字符串插值
来源：http://dali.jinghuilouyu.cn/Article/details/gtuzsnryux.html

s"值: $b"
来源：http://dali.meibo888.top/Article/details/gtsfxgljqs.html

[T54] Scala：集合映射
来源：http://dali.mhx1999.top/Article/details/gtiuhnbxwx.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.dianchejie.cn/Article/details/gtwriviwdj.html

[T55] Scala：集合过滤
来源：http://dali.gogol.net.cn/Article/details/gtkrrpxneo.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jinqigfzy.top/Article/details/gtxgpdzhxv.html

[T56] Scala：样例类
来源：http://dali.cdnleiting.top/Article/details/gtzzdqhmjp.html

case class User(name: String, age: Int)
来源：http://dali.nanxinkj.top/Article/details/gteqvzrqly.html

[T57] Scala：模式匹配
来源：http://dali.jinqigfzy.top/Article/details/gthuexonbf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yj20258.top/Article/details/gtuyrqurju.html

[T58] Scala：函数定义
来源：http://dali.zhiwuduotai.top/Article/details/gtkgfrdbuy.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.pycfn.com/Article/details/gtfoaqaxxj.html

[T59] Scala：循环
来源：http://dali.pycfn.com/Article/details/gtrjuahuht.html

for (i <- 1 to 10) println(i)
来源：http://dali.cqqwz.cn/Article/details/gtlaeggidz.html

[T60] Scala：折叠
来源：http://dali.hnxiangtu.top/Article/details/gtvteauqjk.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yuxming.cn/Article/details/gtlwzrmhrw.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtiqduaapq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zdqjudy.top/Article/details/gtvzanqsst.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtnbhecicf.html

[U01] Py：创建虚拟环境
来源：http://dali.zhoulong.xyz/Article/details/gtxoxsyyzv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.tianlin.xyz/Article/details/gtkacjuykq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yj20258.top/Article/details/gtaipgztzv.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.bjfxy.top/Article/details/gtlhbncxkd.html

[U03] Py：加载 .env 配置
来源：http://dali.yuxming.cn/Article/details/gtnjomhira.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgyeillmk.html

[U04] Py：变量调试打印
来源：http://dali.zhixingplan.top/Article/details/gttzjqjflx.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.shanyushiyangtech.top/Article/details/gtbakjvlbc.html


<!-- 参考信息 -->