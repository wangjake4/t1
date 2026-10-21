代发 wailian999

free -h;  ps aux | grep nginx
来源：http://dali.hnqzz.top/Article/details/gtshhnnncy.html

[R64] 结束进程
来源：http://dali.tanke756.top/Article/details/gtecewoozf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cdnleiting.top/Article/details/gtalgwqgrl.html

[R65] 查看端口占用
来源：http://dali.cdnleiting.top/Article/details/gtsekectdc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xuanzx.com/Article/details/gtjnieecbd.html

[R66] 定时任务
来源：http://dali.yangfankeji.com/Article/details/gtxcniqxqe.html

crontab -e;  crontab -l
来源：http://dali.sxryk.cn/Article/details/gtltcblahe.html

[R67] 生成随机十六进制串
来源：http://dali.hnqzz.top/Article/details/gtpoutxnzt.html

openssl rand -hex 16
来源：http://dali.yongpay.top/Article/details/gtptsdlszo.html

[R68] 计算文件校验值
来源：http://dali.jiagoushi.top/Article/details/gtejaparbc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cheryme.top/Article/details/gtmwnxfzpf.html

[R69] 生成随机密码
来源：http://dali.gotoacloud.top/Article/details/gtxgfgqopm.html

head -c 16 /dev/urandom | base64
来源：http://dali.xinyue.icu/Article/details/gtfnauoyug.html

[R70] 时间戳与互转
来源：http://dali.xuetiantiany.cn/Article/details/gtmylkjohj.html

date +%s;  date -d @1700000000
来源：http://dali.hysaishi.cn/Article/details/gtvtuelmmg.html

[R71] 日期格式化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjtggtugy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yuxming.cn/Article/details/gttpngyais.html

[R72] 等待端口就绪
来源：http://dali.chenjidiqi.icu/Article/details/gtrmwgisxo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.guowangkeji.top/Article/details/gthbdkohhh.html

[R73] 分割大日志
来源：http://dali.gogol.net.cn/Article/details/gteslqnwqz.html

split -l 1000 big.log part_
来源：http://dali.daxiang520.top/Article/details/gtnsxbzfcp.html

[R74] 批量重命名
来源：http://dali.xuanzx.com/Article/details/gteciqtjfi.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cucudq.cn/Article/details/gtwefavadn.html

[R75] 导出环境变量
来源：http://dali.jyoumei.cn/Article/details/gtpnrnjpnw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.guowangkeji.top/Article/details/gtzpudubyk.html

[R76] 使用临时文件
来源：http://dali.shuidangran.top/Article/details/gtakvbywbc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.haohaochexian.top/Article/details/gtcgbayvwt.html

[R77] 读取用户输入
来源：http://dali.yongpay.top/Article/details/gtpegeacwa.html

read -rp "请输入: " ans
来源：http://dali.c1oappe.top/Article/details/gtmngagpab.html

[R78] 交互式菜单
来源：http://dali.feifeiyinyue.top/Article/details/gtlrqbykdz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.kuanghao11.cn/Article/details/gtaasbifnf.html

[R79] 解析命令行选项
来源：http://dali.316326.xyz/Article/details/gtlazlichm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqmacjatv.html

[R80] 查看脚本执行耗时
来源：http://dali.ehwqpu.com/Article/details/gtocbhwcsl.html

time ./run.sh
来源：http://dali.ivvv.top/Article/details/gtgthjiflz.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtdpbdacbw.html

S. C / C++ 专题
来源：http://dali.yueranfly.top/Article/details/gtkulrbzuj.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtnvxxcljm.html

[S01] C：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtmhmjqphh.html

#include <stdio.h>
来源：http://dali.nanxinkj.top/Article/details/gtooijecpz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.chenlongwang.top/Article/details/gtcuknzyff.html

[S02] C：变量与格式化输出
来源：http://dali.yj20258.top/Article/details/gtacwsxwmy.html

int a = 10; printf("%d\n", a);
来源：http://dali.feifeiyinyue.top/Article/details/gtxhhwjwle.html

[S03] C：读入整数
来源：http://dali.nanxinkj.top/Article/details/gtgvttxlvm.html

int x; scanf("%d", &x);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsacxjsej.html

[S04] C：字符串复制
来源：http://dali.sysykeji.top/Article/details/gtnlmtrwon.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.daxiang520.top/Article/details/gtyursjetf.html

[S05] C：字符串长度
来源：http://dali.jinqigfzy.top/Article/details/gtsgkssdlw.html

strlen(s)
来源：http://dali.sysykeji.top/Article/details/gtcjmyrpgz.html

[S06] C：字符串比较
来源：http://dali.chenzaomai.com/Article/details/gtggmpcdbi.html

strcmp(a, b) == 0
来源：http://dali.jyoumei.cn/Article/details/gtcefknzff.html

[S07] C：数组遍历求和
来源：http://dali.jlsjyb.cn/Article/details/gtutshocrs.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.0kj1m.cn/Article/details/gtkppbovqo.html

[S08] C：动态内存分配与释放
来源：http://dali.gogol.net.cn/Article/details/gtptrsvkiq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthuhrjrlr.html

[S09] C：结构体定义与初始化
来源：http://dali.yanxiufei.cn/Article/details/gtdohteyir.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.redwolf501.top/Article/details/gtbckmqpvd.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gtscgeewpz.html

int *p = &a;  *p = 5;
来源：http://dali.hnxiangtu.top/Article/details/gtxyfsedju.html

[S11] C：逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gtxetgfsko.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.kuanghao11.cn/Article/details/gtrozueqsa.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cashguo.top/Article/details/gtsgdgzdlv.html

fclose(f);
来源：http://dali.dianchejie.cn/Article/details/gtmfzrmhvf.html

[S12] C：写文件
来源：http://dali.iojbl.cn/Article/details/gtprmuqzdb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.havefunace.top/Article/details/gtrnoelgop.html

[S13] C：宏定义
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcwjgtzdu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.dashuyun.cn/Article/details/gtukmjpgpk.html

[S14] C：枚举
来源：http://dali.gotoacloud.top/Article/details/gtlumuuwsz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.guowangkeji.top/Article/details/gtqotpvbqo.html

[S15] C：类型转换
来源：http://dali.jqgufenzy.top/Article/details/gtdhndgmts.html

(double) a / b
来源：http://dali.yuxming.cn/Article/details/gtdffzmkbp.html

[S16] C：位操作置位
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdtxfhhbi.html

x |= (1 << 3);
来源：http://dali.nanxinkj.top/Article/details/gtytupscxe.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gtcoeuznkg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.aizwys.cn/Article/details/gtgfvsurwu.html

[S18] C：命令行参数
来源：http://dali.gogol.net.cn/Article/details/gtvczyudcq.html

int main(int argc, char **argv)
来源：http://dali.ehwqpu.com/Article/details/gtplfavofd.html

[S19] C：快速排序
来源：http://dali.yuanzhike.top/Article/details/gtlzmwwcav.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yj20258.top/Article/details/gtlvlqmqzq.html

[S20] C：二分查找
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgbgvizjj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cdnleiting.top/Article/details/gtveduynik.html

[S21] C：字符类别判断
来源：http://dali.wangdashe.top/Article/details/gteqaekdsc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hnqzz.top/Article/details/gtubepxdug.html

[S22] C：字符串转数字
来源：http://dali.sxryk.cn/Article/details/gtxlmtvrfh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yanxiufei.cn/Article/details/gtoqdypcoc.html

[S23] C：随机数
来源：http://dali.ehwqpu.com/Article/details/gtndijsbxf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhengqikj.top/Article/details/gtrqatoiwd.html

[S24] C：获取本地时间
来源：http://dali.guowangkeji.top/Article/details/gtilfwjitt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.haohaochexian.top/Article/details/gtcishwuqh.html

[S25] C：内存拷贝
来源：http://dali.cashguo.top/Article/details/gtmwuhjyfw.html

memcpy(dst, src, n);
来源：http://dali.aizwys.cn/Article/details/gtuqjvxjyg.html

[S26] C：内存清零
来源：http://dali.gogol.net.cn/Article/details/gtfogtcgry.html

memset(a, 0, sizeof a);
来源：http://dali.c1oappe.top/Article/details/gtppbmxcan.html

[S27] C：定义常量
来源：http://dali.cqqwz.cn/Article/details/gtxtnxcufp.html

const double PI = 3.14159;
来源：http://dali.yuxming.cn/Article/details/gtnidapxal.html

[S28] C：静态变量
来源：http://dali.daria6918.cn/Article/details/gtfgxhnoma.html

static int counter = 0;
来源：http://dali.snrcjt.cn/Article/details/gtoclikznp.html

[S29] C：变参函数
来源：http://dali.sysykeji.top/Article/details/gtgucnnsnr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.9152youxi.cn/Article/details/gtroniylsy.html

[S30] C：头文件保护
来源：http://dali.yvedp.cn/Article/details/gtnpjfmgvh.html

#ifndef X_H
来源：http://dali.zhongyouzk.top/Article/details/gtneovqoyh.html

#define X_H
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgqzxlyih.html

#endif
来源：http://dali.tian-w.cn/Article/details/gtcfkyjrfq.html

[S31] C++：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtkcoihqqj.html

#include <iostream>
来源：http://dali.c1oappe.top/Article/details/gtyhkqxxxl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hammf.cn/Article/details/gtxymqacvl.html

[S32] C++：字符串
来源：http://dali.hammf.cn/Article/details/gtvilwfxkm.html

std::string s = "hi";  s += "!";
来源：http://dali.shanyushiyangtech.top/Article/details/gtddfetbwv.html

[S33] C++：vector 增删
来源：http://dali.andypj.xyz/Article/details/gtdbyftukf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.aibaodan.cn/Article/details/gtyxuxkusg.html

[S34] C++：遍历 vector
来源：http://dali.hongshengwenyu.top/Article/details/gttpjdkdsm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xziqi.cn/Article/details/gtdlgafore.html

[S35] C++：map
来源：http://dali.xinyue.icu/Article/details/gtwywyrvja.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gtdkqovxqm.html

[S36] C++：unordered_map
来源：http://dali.zhongyouzk.top/Article/details/gtuhuhsgwl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtryhgvsia.html

[S37] C++：set
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcwqnxvja.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gogol.net.cn/Article/details/gtogohcwiv.html

[S38] C++：排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlakexwoa.html

std::sort(v.begin(), v.end());
来源：http://dali.tianlin.xyz/Article/details/gtggmiksms.html

[S39] C++：自定义比较器排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gtklbfxtqk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhixingplan.top/Article/details/gtucbbbbqr.html

[S40] C++：查找元素
来源：http://dali.yuanzhike.top/Article/details/gtzrxoefdu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yuxming.cn/Article/details/gtpuzosapv.html

[S41] C++：类与构造函数
来源：http://dali.zhongyouzk.top/Article/details/gturmshaba.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yanxiufei.cn/Article/details/gtkwttarrc.html

[S42] C++：继承与虚函数
来源：http://dali.dianchejie.cn/Article/details/gtrbznneoq.html

class B : public Base { public: void f() override {} };
来源：http://dali.jianghu66.top/Article/details/gtvtijvyub.html

[S43] C++：智能指针
来源：http://dali.xylfe.cn/Article/details/gtchsjaxxz.html

auto p = std::make_unique<int>(5);
来源：http://dali.ydzc1.top/Article/details/gtaqivrzvt.html

[S44] C++：引用传参
来源：http://dali.316326.xyz/Article/details/gtgnaivqqw.html

void inc(int &x) { ++x; }
来源：http://dali.xuetiantiany.cn/Article/details/gtlvmqcmkk.html

[S45] C++：lambda
来源：http://dali.zdqjudy.top/Article/details/gtoamjooqe.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvdvqrasf.html

[S46] C++：函数模板
来源：http://dali.sysykeji.top/Article/details/gtdtnpcyuf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yonumen.top/Article/details/gtbmykhyms.html

[S47] C++：结构化绑定遍历
来源：http://dali.xylfe.cn/Article/details/gtbuxiksla.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xziqi.cn/Article/details/gtwzhcvwsn.html

[S48] C++：逐行读文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlyjhldvp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhongyouzk.top/Article/details/gtabjxupob.html

while (std::getline(in, line)) { }
来源：http://dali.ydzc1.top/Article/details/gtfgaxndux.html

[S49] C++：写文件
来源：http://dali.cashguo.top/Article/details/gtmtrjltby.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shangyingyoupin.top/Article/details/gtpttplkse.html

[S50] C++：格式化数字
来源：http://dali.dashuyun.cn/Article/details/gtrcwonmnz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.dashuyun.cn/Article/details/gtwxvsbizf.html

[S51] C++：显式类型转换
来源：http://dali.xuanzx.com/Article/details/gtowoglvba.html

static_cast<double>(a) / b
来源：http://dali.yvedp.cn/Article/details/gtylpofwun.html

[S52] C++：const 与 noexcept
来源：http://dali.yangfankeji.com/Article/details/gtzdzcqhax.html

int size() const noexcept { return n_; }
来源：http://dali.pengpengdd.cyou/Article/details/gtkoallepv.html

[S53] C++：移动语义
来源：http://dali.cqqwz.cn/Article/details/gtyforqign.html

std::vector<int> w = std::move(v);
来源：http://dali.guannengcc.top/Article/details/gtorymavmj.html

[S54] C++：异常处理
来源：http://dali.gotoacloud.top/Article/details/gtfamthtlo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.daria6918.cn/Article/details/gtecgdnjcl.html

[S55] C++：结构化绑定
来源：http://dali.zhongyouzk.top/Article/details/gttrlrwxsk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gaohongyu789.top/Article/details/gtffsyrnxr.html

[S56] C++：optional
来源：http://dali.9152youxi.cn/Article/details/gtpxkxlkru.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinghuilouyu.cn/Article/details/gthjleqsjm.html

[S57] C++：编译期常量
来源：http://dali.hysaishi.cn/Article/details/gteoqwokjz.html

constexpr int N = 10;
来源：http://dali.bjfxy.top/Article/details/gtgghffcef.html

[S58] C++：命名空间
来源：http://dali.shuidangran.top/Article/details/gtdstkidxr.html

namespace ns { int f() { return 1; } }
来源：http://dali.xinyue.icu/Article/details/gtraohevqd.html

[S59] C++：静态断言
来源：http://dali.nanxuanxn.top/Article/details/gtvuklvhdg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.aibaodan.cn/Article/details/gtsvwsqiun.html

[S60] C++：遍历并删除元素
来源：http://dali.aizwys.cn/Article/details/gtpjpufggk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jqgfzy.top/Article/details/gtwhdsjhsd.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtidwvzcnv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.pycfn.com/Article/details/gtxuumrdts.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtcgtyyxru.html

[T01] Kotlin：Hello World
来源：http://dali.yueranfly.top/Article/details/gtevkbdzpy.html

println("Hello")
来源：http://dali.yj20258.top/Article/details/gtwntckxmz.html

[T02] Kotlin：变量
来源：http://dali.andypj.xyz/Article/details/gtigryupfq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.tian-w.cn/Article/details/gthbtxomdp.html

[T03] Kotlin：字符串模板
来源：http://dali.pycfn.com/Article/details/gtmpenvofw.html

"值: $b"
来源：http://dali.fzhhl.top/Article/details/gtyxxxaijo.html

[T04] Kotlin：空安全
来源：http://dali.yueranfly.top/Article/details/gtquidxkwt.html

val n: String? = null;  n?.length
来源：http://dali.andypj.xyz/Article/details/gtqxylmfvy.html

[T05] Kotlin：when 表达式
来源：http://dali.fzhhl.top/Article/details/gtdmrfnfdn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ivvv.top/Article/details/gthyzuezpf.html

[T06] Kotlin：集合映射
来源：http://dali.ybcxt.top/Article/details/gtxdscdinu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shuidangran.top/Article/details/gtsvomwmqy.html

[T07] Kotlin：集合过滤
来源：http://dali.xuetiantiany.cn/Article/details/gtypjfxgrh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinqigufen.top/Article/details/gtznepbtxv.html

[T08] Kotlin：数据类
来源：http://dali.svipenyu.cn/Article/details/gtuvzlwtbn.html

data class User(val name: String, val age: Int)
来源：http://dali.fengsongda.top/Article/details/gtfqlqrnrr.html

[T09] Kotlin：扩展函数
来源：http://dali.havefunace.top/Article/details/gtkxkjkxog.html

fun String.exclaim() = this + "!"
来源：http://dali.zdqjudy.top/Article/details/gtqvogcinb.html

[T10] Kotlin：默认参数
来源：http://dali.quarkkingdee.top/Article/details/gtynctzmpc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zdqjudy.top/Article/details/gtutdageex.html

[T11] Kotlin：协程
来源：http://dali.ydzc1.top/Article/details/gtyzmstrln.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sweek.top/Article/details/gtlxsxvxwm.html

[T12] Kotlin：解构声明
来源：http://dali.0kj1m.cn/Article/details/gthshiyvhp.html

val (a, b) = Pair(1, 2)
来源：http://dali.hammf.cn/Article/details/gtbffcllsk.html

[T13] Kotlin：只读 Map
来源：http://dali.bjfxy.top/Article/details/gtqccbfpbv.html

val m = mapOf("a" to 1)
来源：http://dali.smart0.xyz/Article/details/gtasbzpkfy.html

[T14] Kotlin：循环
来源：http://dali.yuxming.cn/Article/details/gtrmstnvyj.html

for (i in 1..10) println(i)
来源：http://dali.kuanghao11.cn/Article/details/gtwyxmlyub.html

[T15] Kotlin：接口
来源：http://dali.svipenyu.cn/Article/details/gtluuvaqme.html

interface Shape { fun area(): Double }
来源：http://dali.yj202588.top/Article/details/gtiyaazvfv.html

[T16] Swift：Hello World
来源：http://dali.andypj.xyz/Article/details/gttaylyhzz.html

print("Hello")
来源：http://dali.kuanghao11.cn/Article/details/gtfqpvaomh.html

[T17] Swift：变量与常量
来源：http://dali.dashuyun.cn/Article/details/gtcybsphef.html

var a = 1;  let b = 2
来源：http://dali.zhiwuduotai.top/Article/details/gtrmcmaqud.html

[T18] Swift：字符串插值
来源：http://dali.yuanzhike.top/Article/details/gtzitayexu.html

"值: \(b)"
来源：http://dali.cqqwz.cn/Article/details/gtxbmugdnw.html

[T19] Swift：可选绑定
来源：http://dali.cheryme.top/Article/details/gtbmpymcnj.html

if let n = opt { print(n) }
来源：http://dali.chenzaomai.com/Article/details/gtksivpkhe.html

[T20] Swift：数组操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gttifjjjah.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cdnleiting.top/Article/details/gthpswpnnn.html

[T21] Swift：遍历
来源：http://dali.yuanzhike.top/Article/details/gtlusnpwoo.html

for x in a { print(x) }
来源：http://dali.aizwys.cn/Article/details/gtrksocrxx.html

[T22] Swift：字典
来源：http://dali.wangdashe.top/Article/details/gthfaqfxwb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.tianlin.xyz/Article/details/gtjovobzrm.html

[T23] Swift：函数
来源：http://dali.ehwqpu.com/Article/details/gthhxycmdk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yongpay.top/Article/details/gtetmkylbm.html

[T24] Swift：闭包
来源：http://dali.nanxuanxn.top/Article/details/gtopxpozte.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhengqikj.top/Article/details/gttunctyqh.html

[T25] Swift：结构体
来源：http://dali.tianlin.xyz/Article/details/gtywonunsq.html

struct P { var x: Int }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtooaramhu.html

[T26] Swift：类与重写
来源：http://dali.jqgfzy.top/Article/details/gtmknoqzxt.html

class A: Base { override func f() {} }
来源：http://dali.sysykeji.top/Article/details/gtcfyxoakt.html

[T27] Swift：错误处理
来源：http://dali.xylfe.cn/Article/details/gtuzzqmyls.html

do { try f() } catch { print(error) }
来源：http://dali.ivvv.top/Article/details/gtuygsuncu.html

[T28] Swift：枚举
来源：http://dali.xziqi.cn/Article/details/gtxkhujqsd.html

enum Color { case red, green }
来源：http://dali.xinyue.icu/Article/details/gtpbdgimlw.html

[T29] Swift：guard 提前返回
来源：http://dali.daria6918.cn/Article/details/gtdjhutlae.html

guard let x = opt else { return }
来源：http://dali.gaohongyu789.top/Article/details/gtxjeefchh.html

[T30] Swift：协议
来源：http://dali.jiagoushi.top/Article/details/gtrvgqgqxm.html

protocol Shape { func area() -> Double }
来源：http://dali.hongshengwenyu.top/Article/details/gtjdjmuvhh.html

[T31] Lua：Hello World
来源：http://dali.bjfxy.top/Article/details/gtkpdqicay.html

print("Hello")
来源：http://dali.kuanghao11.cn/Article/details/gtbyokrpxh.html

[T32] Lua：局部变量
来源：http://dali.ppjwa.cn/Article/details/gtbvxslmtr.html

local a = 1
来源：http://dali.haohaochexian.top/Article/details/gteyqnmvqw.html

[T33] Lua：表（数组）
来源：http://dali.hywenlv.cn/Article/details/gtwbvgkqzp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.haohaochexian.top/Article/details/gtkfrjlidc.html

[T34] Lua：遍历表
来源：http://dali.hysaishi.cn/Article/details/gtvobjqeoo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.sweek.top/Article/details/gtqcykzdiv.html

[T35] Lua：字典表
来源：http://dali.zhoulong.xyz/Article/details/gtnbbmlbxy.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hnqzz.top/Article/details/gtjnjcksoj.html

[T36] Lua：函数
来源：http://dali.zhixingplan.top/Article/details/gtjswvxpri.html

function add(a, b) return a + b end
来源：http://dali.jqgufenzy.top/Article/details/gtxbvyfuhw.html

[T37] Lua：字符串拼接
来源：http://dali.fzhhl.top/Article/details/gtwhurscxe.html

"a" .. "b"
来源：http://dali.xinyue.icu/Article/details/gtasgkhpfl.html

[T38] Lua：条件
来源：http://dali.ppjwa.cn/Article/details/gtdyzexsoj.html

if x > 0 then print("正") end
来源：http://dali.ydzc1.top/Article/details/gtbphxanat.html

[T39] Lua：模式匹配
来源：http://dali.dianchejie.cn/Article/details/gthipukcqb.html

string.find(s, "%d+")
来源：http://dali.yonumen.top/Article/details/gtdyoezvmr.html

[T40] Lua：元表
来源：http://dali.hywenlv.cn/Article/details/gtisbccnft.html

setmetatable({}, { __index = base })
来源：http://dali.yueranfly.top/Article/details/gtmaesibwz.html

[T41] Perl：Hello World
来源：http://dali.xinyue.icu/Article/details/gtdeqaeyii.html

print "Hello\n";
来源：http://dali.jiagoushi.top/Article/details/gtmeinfhvx.html

[T42] Perl：变量类型
来源：http://dali.quarkkingdee.top/Article/details/gttrjudyfz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.guowangkeji.top/Article/details/gtnnmsegqx.html

[T43] Perl：字符串插值
来源：http://dali.chenjidiqi.icu/Article/details/gtutnndetm.html

"值: $a"
来源：http://dali.sweek.top/Article/details/gtbdhbwffr.html

[T44] Perl：条件
来源：http://dali.sweek.top/Article/details/gtmnefmves.html

if ($a > 0) { print "正"; }
来源：http://dali.316326.xyz/Article/details/gtzzamcyuk.html

[T45] Perl：数组遍历
来源：http://dali.hammf.cn/Article/details/gtlrbtbzzq.html

for my $x (@arr) { print $x; }
来源：http://dali.svipenyu.cn/Article/details/gtonikswou.html

[T46] Perl：哈希操作
来源：http://dali.hysaishi.cn/Article/details/gtbkuduaye.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.daria6918.cn/Article/details/gtkgeegknk.html

[T47] Perl：正则捕获
来源：http://dali.jqgufenzy.top/Article/details/gtxxrumiap.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yonumen.top/Article/details/gtdsgzubpj.html

[T48] Perl：正则替换
来源：http://dali.iojbl.cn/Article/details/gttvouzrwi.html

$s =~ s/old/new/g;
来源：http://dali.c1oappe.top/Article/details/gtuvofftbn.html

[T49] Perl：函数
来源：http://dali.yuanzhike.top/Article/details/gtpwdsgdja.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zdqjudy.top/Article/details/gtbagysvik.html

[T50] Perl：逐行读文件
来源：http://dali.meibo888.top/Article/details/gtacvhvent.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhijiandao.cn/Article/details/gttqoyyres.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.smart0.xyz/Article/details/gttrefencg.html

[T51] Scala：Hello World
来源：http://dali.wangdashe.top/Article/details/gtaltmdmsx.html

println("Hello")
来源：http://dali.zhixingplan.top/Article/details/gtoskpucez.html

[T52] Scala：变量
来源：http://dali.ydzc1.top/Article/details/gtajbtdcdc.html

val a = 1;  var b = 2
来源：http://dali.yongpay.top/Article/details/gtiogxgxum.html

[T53] Scala：字符串插值
来源：http://dali.sufxvd.cn/Article/details/gtamrnxeax.html

s"值: $b"
来源：http://dali.birdmap.top/Article/details/gtrhojqfvv.html

[T54] Scala：集合映射
来源：http://dali.cucudq.cn/Article/details/gtcmtcbohg.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmkkosqvk.html

[T55] Scala：集合过滤
来源：http://dali.xuanzx.com/Article/details/gtxpjnkrgb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmtqrnwen.html

[T56] Scala：样例类
来源：http://dali.jiagoushi.top/Article/details/gtdqobweim.html

case class User(name: String, age: Int)
来源：http://dali.cucudq.cn/Article/details/gtkqemlemi.html

[T57] Scala：模式匹配
来源：http://dali.9152youxi.cn/Article/details/gtvkcznkwd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yj20258.top/Article/details/gtnyisxrlq.html

[T58] Scala：函数定义
来源：http://dali.zhixingplan.top/Article/details/gtyfrkgdbe.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.birdmap.top/Article/details/gtdewhdmri.html

[T59] Scala：循环
来源：http://dali.sweek.top/Article/details/gtacrgbnsv.html

for (i <- 1 to 10) println(i)
来源：http://dali.yuanzhike.top/Article/details/gttixdozcj.html

[T60] Scala：折叠
来源：http://dali.yvedp.cn/Article/details/gtcawkztsv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.tian-w.cn/Article/details/gtcmkvyssz.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gtprbczgvs.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.andypj.xyz/Article/details/gtqrwxjrfj.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtsefdquru.html

[U01] Py：创建虚拟环境
来源：http://dali.havefunace.top/Article/details/gtaymiykxp.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shanyushiyangkeji.top/Article/details/gtczdfxvgv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zdqjudy.top/Article/details/gtkjmqgiak.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtssjgtejc.html

[U03] Py：加载 .env 配置
来源：http://dali.guannengcc.top/Article/details/gtejwqdosn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.guowangkeji.top/Article/details/gtcawavswe.html

[U04] Py：变量调试打印
来源：http://dali.nanxuanxn.top/Article/details/gtwpbprgak.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jlsjyb.cn/Article/details/gtltyqklxu.html


<!-- 参考信息 -->