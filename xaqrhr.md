代发 wailian999

free -h;  ps aux | grep nginx
来源：http://dali.jinqigufen.top/Article/details/gt2eedxtjhk.html

[R64] 结束进程
来源：http://dali.tanke756.top/Article/details/gt2unawystw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.fzhhl.top/Article/details/gt2xmxbrdbr.html

[R65] 查看端口占用
来源：http://dali.yangfankeji.com/Article/details/gt2javamozu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhengqikj.top/Article/details/gt2qajmyaxr.html

[R66] 定时任务
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2tcnyribu.html

crontab -e;  crontab -l
来源：http://dali.kuanghao11.cn/Article/details/gt2suibhiph.html

[R67] 生成随机十六进制串
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2poyjkarw.html

openssl rand -hex 16
来源：http://dali.meibo888.top/Article/details/gt2gdkvgwal.html

[R68] 计算文件校验值
来源：http://dali.zhixingplan.top/Article/details/gt2iuynqgtx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jiagoushi.top/Article/details/gt2raausxxx.html

[R69] 生成随机密码
来源：http://dali.yj20258888.top/Article/details/gt2pbwolsmr.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhixingplan.top/Article/details/gt2lohrmbhh.html

[R70] 时间戳与互转
来源：http://dali.hysaishi.cn/Article/details/gt2hkirzthy.html

date +%s;  date -d @1700000000
来源：http://dali.aibaodan.cn/Article/details/gt2apwkungz.html

[R71] 日期格式化
来源：http://dali.xinyue.icu/Article/details/gt2nmxzpkqo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xuanzx.com/Article/details/gt2bmyujypw.html

[R72] 等待端口就绪
来源：http://dali.yuxming.cn/Article/details/gt2zokokfcx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xinyue.icu/Article/details/gt2fyhbpnaz.html

[R73] 分割大日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ddhkshgb.html

split -l 1000 big.log part_
来源：http://dali.yuxming.cn/Article/details/gt2bahylihi.html

[R74] 批量重命名
来源：http://dali.shzxlz.cn/Article/details/gt2agopovca.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yonumen.top/Article/details/gt2yxwckfal.html

[R75] 导出环境变量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2snucfyia.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.vqdsnc.cn/Article/details/gt2kuciyfxf.html

[R76] 使用临时文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gwprulsr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuxming.cn/Article/details/gt2rcztfujc.html

[R77] 读取用户输入
来源：http://dali.quarkkingdee.top/Article/details/gt2bipmnymj.html

read -rp "请输入: " ans
来源：http://dali.xziqi.cn/Article/details/gt2skxuyjab.html

[R78] 交互式菜单
来源：http://dali.cdnleiting.top/Article/details/gt2vffqfnwl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hnqzz.top/Article/details/gt2mgcyesge.html

[R79] 解析命令行选项
来源：http://dali.chenlongwang.top/Article/details/gt2xlvyquqa.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jlsjyb.cn/Article/details/gt2pgiqovcw.html

[R80] 查看脚本执行耗时
来源：http://dali.meibo888.top/Article/details/gt2bibcmoxr.html

time ./run.sh
来源：http://dali.hnxiangtu.top/Article/details/gt2nfxneptf.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2fbgtragr.html

S. C / C++ 专题
来源：http://dali.jqgfzy.top/Article/details/gt2itracfnw.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2patpulih.html

[S01] C：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tnncliwz.html

#include <stdio.h>
来源：http://dali.shuidangran.top/Article/details/gt2drorqazx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fckzpeul.html

[S02] C：变量与格式化输出
来源：http://dali.ybcxt.top/Article/details/gt2xkkwmydn.html

int a = 10; printf("%d\n", a);
来源：http://dali.kuanghao11.cn/Article/details/gt2sggxuimy.html

[S03] C：读入整数
来源：http://dali.zhengqikj.top/Article/details/gt2wygmsute.html

int x; scanf("%d", &x);
来源：http://dali.yj202588.top/Article/details/gt2jjilczrj.html

[S04] C：字符串复制
来源：http://dali.wangshuangyany.cn/Article/details/gt2oxczfncn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ppjwa.cn/Article/details/gt2yjgkijnx.html

[S05] C：字符串长度
来源：http://dali.redwolf501.top/Article/details/gt2kwgdwsgw.html

strlen(s)
来源：http://dali.dianchejie.cn/Article/details/gt2kirkkanh.html

[S06] C：字符串比较
来源：http://dali.hysaishi.cn/Article/details/gt2gbpbtsly.html

strcmp(a, b) == 0
来源：http://dali.kuanghao11.cn/Article/details/gt2rvjbojbp.html

[S07] C：数组遍历求和
来源：http://dali.chenjidiqi.icu/Article/details/gt2dgnhlkxk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jiagoushi.top/Article/details/gt2kbnjtphr.html

[S08] C：动态内存分配与释放
来源：http://dali.chenjidiqi.icu/Article/details/gt2jvtsrmwy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jqgfzy.top/Article/details/gt2nkgglqie.html

[S09] C：结构体定义与初始化
来源：http://dali.nwbrower.top/Article/details/gt2zctcacyk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ppjwa.cn/Article/details/gt2byjklqos.html

[S10] C：指针与解引用
来源：http://dali.gotoacloud.top/Article/details/gt2rafrhjcm.html

int *p = &a;  *p = 5;
来源：http://dali.jqgufenzy.top/Article/details/gt2ckblixlj.html

[S11] C：逐行读文件
来源：http://dali.yj20258.top/Article/details/gt2iijtajnb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.guannengcc.top/Article/details/gt2bercvxsq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hywenlv.cn/Article/details/gt2erpkkpca.html

fclose(f);
来源：http://dali.zhengqikj.top/Article/details/gt2bvlglqdo.html

[S12] C：写文件
来源：http://dali.xinyue.icu/Article/details/gt2rpectlop.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.snrcjt.cn/Article/details/gt2hhedftnp.html

[S13] C：宏定义
来源：http://dali.yuxming.cn/Article/details/gt2pfxccssf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.dianchejie.cn/Article/details/gt2rvrebgtt.html

[S14] C：枚举
来源：http://dali.jqgufenzy.top/Article/details/gt2mdojezvu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.feifeiyinyue.top/Article/details/gt2qgskkijt.html

[S15] C：类型转换
来源：http://dali.snrcjt.cn/Article/details/gt2fpxwwyps.html

(double) a / b
来源：http://dali.chenlongwang.top/Article/details/gt2fgrphykx.html

[S16] C：位操作置位
来源：http://dali.cqqwz.cn/Article/details/gt2azjktylv.html

x |= (1 << 3);
来源：http://dali.gotoacloud.top/Article/details/gt2ikegzlem.html

[S17] C：安全拼接字符串
来源：http://dali.sufxvd.cn/Article/details/gt2osyyvfot.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.redwolf501.top/Article/details/gt2soycnncs.html

[S18] C：命令行参数
来源：http://dali.yj20258888.top/Article/details/gt2zxspsdod.html

int main(int argc, char **argv)
来源：http://dali.gaohongyu789.top/Article/details/gt2xjfxazvn.html

[S19] C：快速排序
来源：http://dali.tanke756.top/Article/details/gt2nhjyewyu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.wangdashe.top/Article/details/gt2bpeegwge.html

[S20] C：二分查找
来源：http://dali.sxryk.cn/Article/details/gt2edhkomyv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tian-w.cn/Article/details/gt2qpwoqjwi.html

[S21] C：字符类别判断
来源：http://dali.kuanghao11.cn/Article/details/gt2cqpswjau.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sxryk.cn/Article/details/gt2ylsphqry.html

[S22] C：字符串转数字
来源：http://dali.jyoumei.cn/Article/details/gt2sjsgzwfa.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.meibo888.top/Article/details/gt2vdzvkqls.html

[S23] C：随机数
来源：http://dali.zhongyouzk.top/Article/details/gt2afduvoja.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.guowangkeji.top/Article/details/gt2mmslsxld.html

[S24] C：获取本地时间
来源：http://dali.xuetiantiany.cn/Article/details/gt2xvvyooec.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cheryme.top/Article/details/gt2gjdsxnqb.html

[S25] C：内存拷贝
来源：http://dali.tanke756.top/Article/details/gt2hwmhzwze.html

memcpy(dst, src, n);
来源：http://dali.0kj1m.cn/Article/details/gt2hifbggwn.html

[S26] C：内存清零
来源：http://dali.zhiwuduotai.top/Article/details/gt2qrjhettq.html

memset(a, 0, sizeof a);
来源：http://dali.jlsjyb.cn/Article/details/gt2knkjjeid.html

[S27] C：定义常量
来源：http://dali.nanxinkj.top/Article/details/gt2wfewyepj.html

const double PI = 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mcbbuzin.html

[S28] C：静态变量
来源：http://dali.dianchejie.cn/Article/details/gt2ywlykgya.html

static int counter = 0;
来源：http://dali.jlsjyb.cn/Article/details/gt2nbdzebws.html

[S29] C：变参函数
来源：http://dali.hnxiangtu.top/Article/details/gt2bkshkuvu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yangfankeji.com/Article/details/gt2coohgcpw.html

[S30] C：头文件保护
来源：http://dali.zhixingplan.top/Article/details/gt2bqiwjexl.html

#ifndef X_H
来源：http://dali.xylfe.cn/Article/details/gt2jeoqtnjj.html

#define X_H
来源：http://dali.redwolf501.top/Article/details/gt2qqcyfmjf.html

#endif
来源：http://dali.c1oappe.top/Article/details/gt2fdeotbhn.html

[S31] C++：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qjzkvfxj.html

#include <iostream>
来源：http://dali.0kj1m.cn/Article/details/gt2xxhzzhsp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sufxvd.cn/Article/details/gt2xstdewla.html

[S32] C++：字符串
来源：http://dali.gaohongyu789.top/Article/details/gt2xurnjqxn.html

std::string s = "hi";  s += "!";
来源：http://dali.guowangkeji.top/Article/details/gt2dnykdxim.html

[S33] C++：vector 增删
来源：http://dali.havefunace.top/Article/details/gt2jiioakzp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yueranfly.top/Article/details/gt2lzeprolc.html

[S34] C++：遍历 vector
来源：http://dali.vqdsnc.cn/Article/details/gt2cuxgcuzi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.tanke756.top/Article/details/gt2pmpbtqvy.html

[S35] C++：map
来源：http://dali.andypj.xyz/Article/details/gt2nfwmdyjb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zycfv.cn/Article/details/gt2kmhnddoc.html

[S36] C++：unordered_map
来源：http://dali.sufxvd.cn/Article/details/gt2cqfeqcsk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gt2kjrzibnz.html

[S37] C++：set
来源：http://dali.sufxvd.cn/Article/details/gt2mmxyijsk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.quarkkingdee.top/Article/details/gt2hiqomsqo.html

[S38] C++：排序
来源：http://dali.jinghuilouyu.cn/Article/details/gt2urhirpwf.html

std::sort(v.begin(), v.end());
来源：http://dali.redwolf501.top/Article/details/gt2bfjfkcjd.html

[S39] C++：自定义比较器排序
来源：http://dali.yvedp.cn/Article/details/gt2jvowxymy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.daria6918.cn/Article/details/gt2okgqbnvn.html

[S40] C++：查找元素
来源：http://dali.hysaishi.cn/Article/details/gt2jiphorpl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yvedp.cn/Article/details/gt2gzdnctda.html

[S41] C++：类与构造函数
来源：http://dali.chenlongwang.top/Article/details/gt2ssbztgcp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.wangdashe.top/Article/details/gt2rtdzfbdi.html

[S42] C++：继承与虚函数
来源：http://dali.vqdsnc.cn/Article/details/gt2zrvwvvwv.html

class B : public Base { public: void f() override {} };
来源：http://dali.gotoacloud.top/Article/details/gt2tpfmjzib.html

[S43] C++：智能指针
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dqmkmlhw.html

auto p = std::make_unique<int>(5);
来源：http://dali.316326.xyz/Article/details/gt2gtwahblq.html

[S44] C++：引用传参
来源：http://dali.xylfe.cn/Article/details/gt2naxijsrw.html

void inc(int &x) { ++x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yjyjnuft.html

[S45] C++：lambda
来源：http://dali.jqgufenzy.top/Article/details/gt2kkenvvem.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sufxvd.cn/Article/details/gt2uxrvrawt.html

[S46] C++：函数模板
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lfnaneji.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jqgufenzy.top/Article/details/gt2fiuaownk.html

[S47] C++：结构化绑定遍历
来源：http://dali.wangdashe.top/Article/details/gt2xxbintuy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xylfe.cn/Article/details/gt2zyxphlxw.html

[S48] C++：逐行读文件
来源：http://dali.hnqzz.top/Article/details/gt2ktconpoy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2kwkxhxou.html

while (std::getline(in, line)) { }
来源：http://dali.tanke756.top/Article/details/gt2waopebqj.html

[S49] C++：写文件
来源：http://dali.cdnleiting.top/Article/details/gt2frbhrhjf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jlsjyb.cn/Article/details/gt2lfxxtzla.html

[S50] C++：格式化数字
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2nrngjngy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gt2biaakbwt.html

[S51] C++：显式类型转换
来源：http://dali.cheryme.top/Article/details/gt2imzreswi.html

static_cast<double>(a) / b
来源：http://dali.sxryk.cn/Article/details/gt2skvylydt.html

[S52] C++：const 与 noexcept
来源：http://dali.jinqigfzy.top/Article/details/gt2oblhyykx.html

int size() const noexcept { return n_; }
来源：http://dali.svipenyu.cn/Article/details/gt2xdczwstn.html

[S53] C++：移动语义
来源：http://dali.jianghu66.top/Article/details/gt2tgqlqnkh.html

std::vector<int> w = std::move(v);
来源：http://dali.birdmap.top/Article/details/gt2yzcdtmvg.html

[S54] C++：异常处理
来源：http://dali.bjfxy.top/Article/details/gt2syctpnwz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jianghu66.top/Article/details/gt2ivcwlmzb.html

[S55] C++：结构化绑定
来源：http://dali.jinqigufen.top/Article/details/gt2qjauijsn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.chenzaomai.com/Article/details/gt2ipnmxqnn.html

[S56] C++：optional
来源：http://dali.tanke756.top/Article/details/gt2yabyzrtf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj20258.top/Article/details/gt2yctubqeo.html

[S57] C++：编译期常量
来源：http://dali.ppjwa.cn/Article/details/gt2gntcmyrs.html

constexpr int N = 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xnequygx.html

[S58] C++：命名空间
来源：http://dali.yuanzhike.top/Article/details/gt2mnebabfh.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhijiandao.cn/Article/details/gt2omkdtvdy.html

[S59] C++：静态断言
来源：http://dali.zhoulong.xyz/Article/details/gt2kvagdfwm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.aibaodan.cn/Article/details/gt2qpdpfbit.html

[S60] C++：遍历并删除元素
来源：http://dali.zhiwuduotai.top/Article/details/gt2uhfpvsos.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.meibo888.top/Article/details/gt2fbminfdz.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2fiqqenlo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sufxvd.cn/Article/details/gt2wsdtpmey.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2tsvdsaem.html

[T01] Kotlin：Hello World
来源：http://dali.tian-w.cn/Article/details/gt2ydhmhsih.html

println("Hello")
来源：http://dali.tian-w.cn/Article/details/gt2dlqecaqg.html

[T02] Kotlin：变量
来源：http://dali.xuanzx.com/Article/details/gt2pxojfrby.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yonumen.top/Article/details/gt2ilmhbvwz.html

[T03] Kotlin：字符串模板
来源：http://dali.fengsongda.top/Article/details/gt2zhgofftz.html

"值: $b"
来源：http://dali.mhx1999.top/Article/details/gt2qsoigtdi.html

[T04] Kotlin：空安全
来源：http://dali.jqgfzy.top/Article/details/gt2ebgrnqkj.html

val n: String? = null;  n?.length
来源：http://dali.zhijiandao.cn/Article/details/gt2hqdgkpum.html

[T05] Kotlin：when 表达式
来源：http://dali.feifeiyinyue.top/Article/details/gt2hiblnazr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sufxvd.cn/Article/details/gt2ockqtasz.html

[T06] Kotlin：集合映射
来源：http://dali.jianghu66.top/Article/details/gt2uzqxnsem.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.nanxinkj.top/Article/details/gt2bpidshoy.html

[T07] Kotlin：集合过滤
来源：http://dali.aibaodan.cn/Article/details/gt2fivalnct.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.chenlongwang.top/Article/details/gt2kqexdyau.html

[T08] Kotlin：数据类
来源：http://dali.tanke756.top/Article/details/gt2qzyltezv.html

data class User(val name: String, val age: Int)
来源：http://dali.wangdashe.top/Article/details/gt2ljrzqymr.html

[T09] Kotlin：扩展函数
来源：http://dali.quarkkingdee.top/Article/details/gt2gvrhrofv.html

fun String.exclaim() = this + "!"
来源：http://dali.fengsongda.top/Article/details/gt2dkkfbsde.html

[T10] Kotlin：默认参数
来源：http://dali.birdmap.top/Article/details/gt2fmrnvkea.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.sxryk.cn/Article/details/gt2ldolbgcs.html

[T11] Kotlin：协程
来源：http://dali.316326.xyz/Article/details/gt2ocbwzoed.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yj202588.top/Article/details/gt2xlueaogt.html

[T12] Kotlin：解构声明
来源：http://dali.dianchejie.cn/Article/details/gt2zipuisew.html

val (a, b) = Pair(1, 2)
来源：http://dali.svipenyu.cn/Article/details/gt2dfukpfvr.html

[T13] Kotlin：只读 Map
来源：http://dali.jlsjyb.cn/Article/details/gt2kvzwghdw.html

val m = mapOf("a" to 1)
来源：http://dali.yuanzhike.top/Article/details/gt2gxazossf.html

[T14] Kotlin：循环
来源：http://dali.c1oappe.top/Article/details/gt2jwwzzokr.html

for (i in 1..10) println(i)
来源：http://dali.yuanzhike.top/Article/details/gt2lrajzwot.html

[T15] Kotlin：接口
来源：http://dali.wangshuangyany.cn/Article/details/gt2tqfbregu.html

interface Shape { fun area(): Double }
来源：http://dali.havefunace.top/Article/details/gt2izdkwupf.html

[T16] Swift：Hello World
来源：http://dali.guannengcc.top/Article/details/gt2gwiurxqn.html

print("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gt2qkymqxvh.html

[T17] Swift：变量与常量
来源：http://dali.vqdsnc.cn/Article/details/gt2cnitjawi.html

var a = 1;  let b = 2
来源：http://dali.chenzaomai.com/Article/details/gt2aeaipqdq.html

[T18] Swift：字符串插值
来源：http://dali.xziqi.cn/Article/details/gt2wrlxwvjo.html

"值: \(b)"
来源：http://dali.gogol.net.cn/Article/details/gt2qfdvpiok.html

[T19] Swift：可选绑定
来源：http://dali.fzhhl.top/Article/details/gt2ctlwqhni.html

if let n = opt { print(n) }
来源：http://dali.cqqwz.cn/Article/details/gt2koluccju.html

[T20] Swift：数组操作
来源：http://dali.fengsongda.top/Article/details/gt2svuzdoyc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.9152youxi.cn/Article/details/gt2bviohapf.html

[T21] Swift：遍历
来源：http://dali.c1oappe.top/Article/details/gt2hvnifnar.html

for x in a { print(x) }
来源：http://dali.zdqjudy.top/Article/details/gt2ywbtcdqf.html

[T22] Swift：字典
来源：http://dali.tianlin.xyz/Article/details/gt2thdwsfru.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cashguo.top/Article/details/gt2awhmviti.html

[T23] Swift：函数
来源：http://dali.cheryme.top/Article/details/gt2vbmpnxdb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yuxming.cn/Article/details/gt2louvgaws.html

[T24] Swift：闭包
来源：http://dali.fengsongda.top/Article/details/gt2nrfdwfzw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2fdrxgbvk.html

[T25] Swift：结构体
来源：http://dali.sweek.top/Article/details/gt2ogrwsrpl.html

struct P { var x: Int }
来源：http://dali.aizwys.cn/Article/details/gt2hykecsap.html

[T26] Swift：类与重写
来源：http://dali.meibo888.top/Article/details/gt2wjlydkyn.html

class A: Base { override func f() {} }
来源：http://dali.gogol.net.cn/Article/details/gt2ljwebaug.html

[T27] Swift：错误处理
来源：http://dali.9152youxi.cn/Article/details/gt2jemrdjrp.html

do { try f() } catch { print(error) }
来源：http://dali.jlsjyb.cn/Article/details/gt2ghmoptwe.html

[T28] Swift：枚举
来源：http://dali.316326.xyz/Article/details/gt2dmzavoyv.html

enum Color { case red, green }
来源：http://dali.gzhubu.top/Article/details/gt2feslbzrh.html

[T29] Swift：guard 提前返回
来源：http://dali.c1oappe.top/Article/details/gt2nqozsijc.html

guard let x = opt else { return }
来源：http://dali.yj202588.top/Article/details/gt2zbtgssvs.html

[T30] Swift：协议
来源：http://dali.zhiwuduotai.top/Article/details/gt2jeeswojb.html

protocol Shape { func area() -> Double }
来源：http://dali.pengpengdd.cyou/Article/details/gt2mrlwtsgy.html

[T31] Lua：Hello World
来源：http://dali.wangdashe.top/Article/details/gt2ersclyit.html

print("Hello")
来源：http://dali.jinqigfzy.top/Article/details/gt2thetpxfj.html

[T32] Lua：局部变量
来源：http://dali.sysykeji.top/Article/details/gt2ylxeylaz.html

local a = 1
来源：http://dali.nwbrower.top/Article/details/gt2byexrmwz.html

[T33] Lua：表（数组）
来源：http://dali.zdqjudy.top/Article/details/gt2biglogsf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jiagoushi.top/Article/details/gt2gndwtzjw.html

[T34] Lua：遍历表
来源：http://dali.shangyingyoupin.top/Article/details/gt2vygqcyyf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hysaishi.cn/Article/details/gt2iyvvrlhf.html

[T35] Lua：字典表
来源：http://dali.cucudq.cn/Article/details/gt2hzipkbjr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.chenjidiqi.icu/Article/details/gt2ujiummkp.html

[T36] Lua：函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2rtmxhoth.html

function add(a, b) return a + b end
来源：http://dali.aibaodan.cn/Article/details/gt2khmhoaha.html

[T37] Lua：字符串拼接
来源：http://dali.zhongyouzk.top/Article/details/gt2rqnipfqm.html

"a" .. "b"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rvjdlamm.html

[T38] Lua：条件
来源：http://dali.zhengqikj.top/Article/details/gt2oudfisjs.html

if x > 0 then print("正") end
来源：http://dali.wangshuangyany.cn/Article/details/gt2bcoboddc.html

[T39] Lua：模式匹配
来源：http://dali.guannengcc.top/Article/details/gt2hxugbrop.html

string.find(s, "%d+")
来源：http://dali.yonumen.top/Article/details/gt2zgmezvwn.html

[T40] Lua：元表
来源：http://dali.hywenlv.cn/Article/details/gt2jwezpqxf.html

setmetatable({}, { __index = base })
来源：http://dali.pengpengdd.cyou/Article/details/gt2kyajfwqd.html

[T41] Perl：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gt2cxdomxqr.html

print "Hello\n";
来源：http://dali.zhengqikj.top/Article/details/gt2dewlsvnq.html

[T42] Perl：变量类型
来源：http://dali.aibaodan.cn/Article/details/gt2vlboyyvq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.wangdashe.top/Article/details/gt2tclrplkn.html

[T43] Perl：字符串插值
来源：http://dali.cheryme.top/Article/details/gt2dzoopahh.html

"值: $a"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2avkfpcln.html

[T44] Perl：条件
来源：http://dali.ybcxt.top/Article/details/gt2zaufkgpc.html

if ($a > 0) { print "正"; }
来源：http://dali.fzhhl.top/Article/details/gt2bleakepq.html

[T45] Perl：数组遍历
来源：http://dali.yueranfly.top/Article/details/gt2gxykvsjz.html

for my $x (@arr) { print $x; }
来源：http://dali.ppjwa.cn/Article/details/gt2emqxwnue.html

[T46] Perl：哈希操作
来源：http://dali.sweek.top/Article/details/gt2nbkcnjpu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.andypj.xyz/Article/details/gt2xufyikyj.html

[T47] Perl：正则捕获
来源：http://dali.gotoacloud.top/Article/details/gt2nfadficn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.316326.xyz/Article/details/gt2ulfigfcy.html

[T48] Perl：正则替换
来源：http://dali.chenzaomai.com/Article/details/gt2fcdhbhjg.html

$s =~ s/old/new/g;
来源：http://dali.gogol.net.cn/Article/details/gt2baqzcqqg.html

[T49] Perl：函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lplggyxu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.quarkkingdee.top/Article/details/gt2qndyteut.html

[T50] Perl：逐行读文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2eminwvuk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ybcxt.top/Article/details/gt2kdjsnrye.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2sowkpxgn.html

[T51] Scala：Hello World
来源：http://dali.chenlongwang.top/Article/details/gt2rticoick.html

println("Hello")
来源：http://dali.ppjwa.cn/Article/details/gt2lxolabmv.html

[T52] Scala：变量
来源：http://dali.smart0.xyz/Article/details/gt2jmdkepys.html

val a = 1;  var b = 2
来源：http://dali.fengsongda.top/Article/details/gt2rwzadfwo.html

[T53] Scala：字符串插值
来源：http://dali.daxiang520.top/Article/details/gt2sbewmdqk.html

s"值: $b"
来源：http://dali.hysaishi.cn/Article/details/gt2ncnhzgmn.html

[T54] Scala：集合映射
来源：http://dali.ehwqpu.com/Article/details/gt2khisoyii.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hnqzz.top/Article/details/gt2afhipuph.html

[T55] Scala：集合过滤
来源：http://dali.yanxiufei.cn/Article/details/gt2zbnvnubq.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.guannengcc.top/Article/details/gt2dbuysmjt.html

[T56] Scala：样例类
来源：http://dali.svipenyu.cn/Article/details/gt2ryeddccr.html

case class User(name: String, age: Int)
来源：http://dali.c1oappe.top/Article/details/gt2vxptmylz.html

[T57] Scala：模式匹配
来源：http://dali.yvedp.cn/Article/details/gt2ssjddzxg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hysaishi.cn/Article/details/gt2zlfhbyre.html

[T58] Scala：函数定义
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wzolezom.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.svipenyu.cn/Article/details/gt2sfzaigiy.html

[T59] Scala：循环
来源：http://dali.9152youxi.cn/Article/details/gt2slkxhels.html

for (i <- 1 to 10) println(i)
来源：http://dali.zdqjudy.top/Article/details/gt2gaebspsb.html

[T60] Scala：折叠
来源：http://dali.gogol.net.cn/Article/details/gt2bldlcdee.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jinqigfzy.top/Article/details/gt2cmsvrmta.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2fjvnzbik.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.redwolf501.top/Article/details/gt2grcvidcr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2czddhqqb.html

[U01] Py：创建虚拟环境
来源：http://dali.vqdsnc.cn/Article/details/gt2mziflpfx.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.haohaochexian.top/Article/details/gt2duwsuvqd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hnqzz.top/Article/details/gt2lujvfurt.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jianghu66.top/Article/details/gt2ovayxcbq.html

[U03] Py：加载 .env 配置
来源：http://dali.vqdsnc.cn/Article/details/gt2dhepofad.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jqgfzy.top/Article/details/gt2kwsbpnrc.html

[U04] Py：变量调试打印
来源：http://dali.hfpthk.cn/Article/details/gt2sxrccbzs.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xylfe.cn/Article/details/gt2zjkziuim.html


<!-- 参考信息 -->