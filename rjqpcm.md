代发 wailian999

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.andypj.xyz/Article/details/gtsuviouri.html

[R60] 只看 HTTP 状态码
来源：http://dali.sysykeji.top/Article/details/gtaxvvshub.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cashguo.top/Article/details/gtiteupiht.html

[R61] 磁盘占用
来源：http://dali.kuanghao11.cn/Article/details/gtvguqhfts.html

df -h;  du -sh *
来源：http://dali.jqgfzy.top/Article/details/gtgfpruyoy.html

[R62] 找最占空间的文件
来源：http://dali.cdnleiting.top/Article/details/gtfbudxnja.html

du -ah . | sort -rh | head -10
来源：http://dali.aibaodan.cn/Article/details/gtokpdmxpq.html

[R63] 内存与进程
来源：http://dali.hywenlv.cn/Article/details/gtnhqmqfnl.html

free -h;  ps aux | grep nginx
来源：http://dali.zycfv.cn/Article/details/gthqgeykuz.html

[R64] 结束进程
来源：http://dali.shanyushiyangtech.top/Article/details/gtatwdfkfk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gotoacloud.top/Article/details/gtheqovdcy.html

[R65] 查看端口占用
来源：http://dali.jinqigfzy.top/Article/details/gtnzrqmyvl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gaohongyu789.top/Article/details/gtzdibxgos.html

[R66] 定时任务
来源：http://dali.chenjidiqi.icu/Article/details/gtmrbpenhj.html

crontab -e;  crontab -l
来源：http://dali.gaohongyu789.top/Article/details/gtwmgikkxb.html

[R67] 生成随机十六进制串
来源：http://dali.chenzaomai.com/Article/details/gtyutptfgo.html

openssl rand -hex 16
来源：http://dali.havefunace.top/Article/details/gtrcpqxoyd.html

[R68] 计算文件校验值
来源：http://dali.fzhhl.top/Article/details/gttebhkxgk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtjuqtclyw.html

[R69] 生成随机密码
来源：http://dali.fengsongda.top/Article/details/gtjdrgqcob.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhengqikj.top/Article/details/gtefbfpwnq.html

[R70] 时间戳与互转
来源：http://dali.pengpengdd.cyou/Article/details/gtmhgkolih.html

date +%s;  date -d @1700000000
来源：http://dali.yuanzhike.top/Article/details/gtogehetyk.html

[R71] 日期格式化
来源：http://dali.chenlongwang.top/Article/details/gtsiemojnh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.quarkkingdee.top/Article/details/gtbshpoqro.html

[R72] 等待端口就绪
来源：http://dali.tianlin.xyz/Article/details/gtcqtuasit.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhongyouzk.top/Article/details/gtxpkxzidn.html

[R73] 分割大日志
来源：http://dali.jinqigufen.top/Article/details/gtzpyhhiof.html

split -l 1000 big.log part_
来源：http://dali.yanxiufei.cn/Article/details/gtikvaezpy.html

[R74] 批量重命名
来源：http://dali.jianghu66.top/Article/details/gtkmwirsee.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yj202588.top/Article/details/gtlhzmbcxn.html

[R75] 导出环境变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtumtoekat.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sufxvd.cn/Article/details/gtgzdvlhxl.html

[R76] 使用临时文件
来源：http://dali.daxiang520.top/Article/details/gtcatgclyr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinghuilouyu.cn/Article/details/gtrizdjyjx.html

[R77] 读取用户输入
来源：http://dali.gogol.net.cn/Article/details/gtuspyqyje.html

read -rp "请输入: " ans
来源：http://dali.hfpthk.cn/Article/details/gtuyhkcmvf.html

[R78] 交互式菜单
来源：http://dali.yonumen.top/Article/details/gtzadscfwz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shangyingyoupin.top/Article/details/gtudegltuw.html

[R79] 解析命令行选项
来源：http://dali.sufxvd.cn/Article/details/gtukccezqd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sxryk.cn/Article/details/gtuqlhnoey.html

[R80] 查看脚本执行耗时
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfshdhwew.html

time ./run.sh
来源：http://dali.zhoulong.xyz/Article/details/gtxmsdyiff.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtryxlwwal.html

S. C / C++ 专题
来源：http://dali.redwolf501.top/Article/details/gtbfdeeuke.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtqcdddpat.html

[S01] C：Hello World
来源：http://dali.ybcxt.top/Article/details/gtcqmnhjvm.html

#include <stdio.h>
来源：http://dali.smart0.xyz/Article/details/gtrreocrgf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhongyouzk.top/Article/details/gtiytlazbn.html

[S02] C：变量与格式化输出
来源：http://dali.sufxvd.cn/Article/details/gtscuzveqx.html

int a = 10; printf("%d\n", a);
来源：http://dali.jianghu66.top/Article/details/gtpfruypxl.html

[S03] C：读入整数
来源：http://dali.tianlin.xyz/Article/details/gtuqrudjvi.html

int x; scanf("%d", &x);
来源：http://dali.cucudq.cn/Article/details/gtutzajmnk.html

[S04] C：字符串复制
来源：http://dali.hywenlv.cn/Article/details/gtsrarqalr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinghuilouyu.cn/Article/details/gtehiqgmff.html

[S05] C：字符串长度
来源：http://dali.nanxuanxn.top/Article/details/gtkjjosiur.html

strlen(s)
来源：http://dali.haohaochexian.top/Article/details/gtnanvdopa.html

[S06] C：字符串比较
来源：http://dali.c1oappe.top/Article/details/gttvpjkrfl.html

strcmp(a, b) == 0
来源：http://dali.yonumen.top/Article/details/gtwpmnorpt.html

[S07] C：数组遍历求和
来源：http://dali.ivvv.top/Article/details/gtvxnsrwln.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jiagoushi.top/Article/details/gtilgiewui.html

[S08] C：动态内存分配与释放
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqmoqqenx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shanyushiyangtech.top/Article/details/gtgkqsjrqm.html

[S09] C：结构体定义与初始化
来源：http://dali.yangfankeji.com/Article/details/gtqskvkjjr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xuetiantiany.cn/Article/details/gtvrulzddb.html

[S10] C：指针与解引用
来源：http://dali.jiagoushi.top/Article/details/gthniohaxl.html

int *p = &a;  *p = 5;
来源：http://dali.xuanzx.com/Article/details/gtxirikuvc.html

[S11] C：逐行读文件
来源：http://dali.yvedp.cn/Article/details/gtkwpaqwbn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.fengsongda.top/Article/details/gtdvfuiiqs.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.chenjidiqi.icu/Article/details/gtbsqpyuro.html

fclose(f);
来源：http://dali.hongshengwenyu.top/Article/details/gttvgqpvis.html

[S12] C：写文件
来源：http://dali.jyoumei.cn/Article/details/gtrlawczst.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hammf.cn/Article/details/gtacdvjdoi.html

[S13] C：宏定义
来源：http://dali.zhixingplan.top/Article/details/gtclcfsawv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.316326.xyz/Article/details/gteyiakayt.html

[S14] C：枚举
来源：http://dali.nanxinkj.top/Article/details/gtulrtmyis.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.daxiang520.top/Article/details/gtacfibzoh.html

[S15] C：类型转换
来源：http://dali.zhongyouzk.top/Article/details/gtujzyhpwf.html

(double) a / b
来源：http://dali.zhixingplan.top/Article/details/gtchryokav.html

[S16] C：位操作置位
来源：http://dali.tianlin.xyz/Article/details/gtogdtphfi.html

x |= (1 << 3);
来源：http://dali.cashguo.top/Article/details/gtxjefwgnl.html

[S17] C：安全拼接字符串
来源：http://dali.tanke756.top/Article/details/gtelsmrfdc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.andypj.xyz/Article/details/gtngnroknb.html

[S18] C：命令行参数
来源：http://dali.nwbrower.top/Article/details/gtonzidbns.html

int main(int argc, char **argv)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxyguwvaj.html

[S19] C：快速排序
来源：http://dali.zhoulong.xyz/Article/details/gtvlfyirnh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.havefunace.top/Article/details/gtkowitnbp.html

[S20] C：二分查找
来源：http://dali.xylfe.cn/Article/details/gtyahgkgwb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jiagoushi.top/Article/details/gtbflukndn.html

[S21] C：字符类别判断
来源：http://dali.guowangkeji.top/Article/details/gtsbhghcgu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zdqjudy.top/Article/details/gtlaiwmlwt.html

[S22] C：字符串转数字
来源：http://dali.haohaochexian.top/Article/details/gtoaystygr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.redwolf501.top/Article/details/gtlhskueyu.html

[S23] C：随机数
来源：http://dali.hnxiangtu.top/Article/details/gtdmihrsde.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjoamrzic.html

[S24] C：获取本地时间
来源：http://dali.snrcjt.cn/Article/details/gttqbdesmq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.chenlongwang.top/Article/details/gtqbuudvpm.html

[S25] C：内存拷贝
来源：http://dali.yuanzhike.top/Article/details/gtntgintrs.html

memcpy(dst, src, n);
来源：http://dali.shzxlz.cn/Article/details/gtpwbmyext.html

[S26] C：内存清零
来源：http://dali.birdmap.top/Article/details/gtfneymygx.html

memset(a, 0, sizeof a);
来源：http://dali.chenzaomai.com/Article/details/gtcqarkqdf.html

[S27] C：定义常量
来源：http://dali.nanxinkj.top/Article/details/gtoqbqnytj.html

const double PI = 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gtdcctgrfj.html

[S28] C：静态变量
来源：http://dali.jqgfzy.top/Article/details/gtrmueysfq.html

static int counter = 0;
来源：http://dali.yangfankeji.com/Article/details/gtnkciekpg.html

[S29] C：变参函数
来源：http://dali.kuanghao11.cn/Article/details/gtargeyjhm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.chenzaomai.com/Article/details/gtyrbrnlvb.html

[S30] C：头文件保护
来源：http://dali.ybcxt.top/Article/details/gtlblvyzya.html

#ifndef X_H
来源：http://dali.aibaodan.cn/Article/details/gtcnpdzmco.html

#define X_H
来源：http://dali.jianghu66.top/Article/details/gtnmdmgukx.html

#endif
来源：http://dali.chenjidiqi.icu/Article/details/gtmsfwaoti.html

[S31] C++：Hello World
来源：http://dali.daxiang520.top/Article/details/gtopmwxwlu.html

#include <iostream>
来源：http://dali.chenjidiqi.icu/Article/details/gtwxcdenyz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.redwolf501.top/Article/details/gtrroweizl.html

[S32] C++：字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtylwpfjnr.html

std::string s = "hi";  s += "!";
来源：http://dali.ehwqpu.com/Article/details/gtwyfqccsy.html

[S33] C++：vector 增删
来源：http://dali.xylfe.cn/Article/details/gthxzihvlb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.dashuyun.cn/Article/details/gtdneeovmh.html

[S34] C++：遍历 vector
来源：http://dali.0kj1m.cn/Article/details/gtwdnmueeb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhixingplan.top/Article/details/gtauskxszu.html

[S35] C++：map
来源：http://dali.gzhubu.top/Article/details/gtgpnalueh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj202588.top/Article/details/gtcfbkfbzy.html

[S36] C++：unordered_map
来源：http://dali.dianchejie.cn/Article/details/gtuagfmiop.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.9152youxi.cn/Article/details/gtjvwmcawk.html

[S37] C++：set
来源：http://dali.nwbrower.top/Article/details/gtofajjluj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shuidangran.top/Article/details/gtkuuicbtz.html

[S38] C++：排序
来源：http://dali.gaohongyu789.top/Article/details/gtrlcawrye.html

std::sort(v.begin(), v.end());
来源：http://dali.aibaodan.cn/Article/details/gtdcdxlwwd.html

[S39] C++：自定义比较器排序
来源：http://dali.haohaochexian.top/Article/details/gtuyoieryz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cdnleiting.top/Article/details/gtcacoppes.html

[S40] C++：查找元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttfiqviwr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.tianlin.xyz/Article/details/gtzvdgbqgz.html

[S41] C++：类与构造函数
来源：http://dali.hywenlv.cn/Article/details/gtehawhjis.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.guowangkeji.top/Article/details/gtahijkojr.html

[S42] C++：继承与虚函数
来源：http://dali.shzxlz.cn/Article/details/gtnwmivbuz.html

class B : public Base { public: void f() override {} };
来源：http://dali.kuanghao11.cn/Article/details/gtulcweqge.html

[S43] C++：智能指针
来源：http://dali.wangshuangyany.cn/Article/details/gtkmbfksnh.html

auto p = std::make_unique<int>(5);
来源：http://dali.shanyushiyangtech.top/Article/details/gtowuldfoj.html

[S44] C++：引用传参
来源：http://dali.snrcjt.cn/Article/details/gtfmixpwjm.html

void inc(int &x) { ++x; }
来源：http://dali.zycfv.cn/Article/details/gtiwavbwcm.html

[S45] C++：lambda
来源：http://dali.wangdashe.top/Article/details/gtvvrgujyb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.pycfn.com/Article/details/gtzlmvlzru.html

[S46] C++：函数模板
来源：http://dali.tianlin.xyz/Article/details/gtzvqazrye.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.haohaochexian.top/Article/details/gtimbsfger.html

[S47] C++：结构化绑定遍历
来源：http://dali.sysykeji.top/Article/details/gtiujrbayz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cashguo.top/Article/details/gtxzyumzwg.html

[S48] C++：逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcmdigdvo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.nanxinkj.top/Article/details/gtrehjgwda.html

while (std::getline(in, line)) { }
来源：http://dali.yueranfly.top/Article/details/gthsmaslbo.html

[S49] C++：写文件
来源：http://dali.hysaishi.cn/Article/details/gtoaiabjqj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.guannengcc.top/Article/details/gtoukcreqa.html

[S50] C++：格式化数字
来源：http://dali.xylfe.cn/Article/details/gtgcyvjysi.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gtnyxpdfks.html

[S51] C++：显式类型转换
来源：http://dali.cdnleiting.top/Article/details/gtcsjzyioa.html

static_cast<double>(a) / b
来源：http://dali.chenjidiqi.icu/Article/details/gtgiurdyao.html

[S52] C++：const 与 noexcept
来源：http://dali.meibo888.top/Article/details/gteizlsgrw.html

int size() const noexcept { return n_; }
来源：http://dali.redwolf501.top/Article/details/gtuubeckoj.html

[S53] C++：移动语义
来源：http://dali.zhoulong.xyz/Article/details/gteecenglk.html

std::vector<int> w = std::move(v);
来源：http://dali.yangfankeji.com/Article/details/gtasskgrcp.html

[S54] C++：异常处理
来源：http://dali.cucudq.cn/Article/details/gtjlstlznn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.daxiang520.top/Article/details/gtcolwxxqj.html

[S55] C++：结构化绑定
来源：http://dali.hnqzz.top/Article/details/gtcjteyxfl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zdqjudy.top/Article/details/gtpzqsjuys.html

[S56] C++：optional
来源：http://dali.cdnleiting.top/Article/details/gtpdgoazjq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.pycfn.com/Article/details/gtsangwvzr.html

[S57] C++：编译期常量
来源：http://dali.jinqigfzy.top/Article/details/gtazbztqpz.html

constexpr int N = 10;
来源：http://dali.jlsjyb.cn/Article/details/gtnubodhmq.html

[S58] C++：命名空间
来源：http://dali.jqgfzy.top/Article/details/gtwdltunzj.html

namespace ns { int f() { return 1; } }
来源：http://dali.nwbrower.top/Article/details/gtinfxofou.html

[S59] C++：静态断言
来源：http://dali.bjfxy.top/Article/details/gttnswsmny.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ydzc1.top/Article/details/gtatcyvpoc.html

[S60] C++：遍历并删除元素
来源：http://dali.xuetiantiany.cn/Article/details/gtjfusbzcq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yangfankeji.com/Article/details/gtivuokqmq.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtjebwzlii.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yvedp.cn/Article/details/gtavtdpzku.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtymyjvxix.html

[T01] Kotlin：Hello World
来源：http://dali.tanke756.top/Article/details/gthcpnbcqb.html

println("Hello")
来源：http://dali.sysykeji.top/Article/details/gtasfkssqq.html

[T02] Kotlin：变量
来源：http://dali.pengpengdd.cyou/Article/details/gtudhwryjk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ivvv.top/Article/details/gtbwyoxian.html

[T03] Kotlin：字符串模板
来源：http://dali.zhixingplan.top/Article/details/gtubzyojlu.html

"值: $b"
来源：http://dali.zhiwuduotai.top/Article/details/gthbgfiwmo.html

[T04] Kotlin：空安全
来源：http://dali.hnqzz.top/Article/details/gtetpwmvmf.html

val n: String? = null;  n?.length
来源：http://dali.jlsjyb.cn/Article/details/gthkcdqtzn.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gtcmqpqbax.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.quarkkingdee.top/Article/details/gtouzpxbzx.html

[T06] Kotlin：集合映射
来源：http://dali.gzhubu.top/Article/details/gtcxasonur.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ppjwa.cn/Article/details/gtdnolrzhi.html

[T07] Kotlin：集合过滤
来源：http://dali.cqqwz.cn/Article/details/gtzucmybpj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.guowangkeji.top/Article/details/gtbcsnilpc.html

[T08] Kotlin：数据类
来源：http://dali.yonumen.top/Article/details/gtqedxofmh.html

data class User(val name: String, val age: Int)
来源：http://dali.jinqigufen.top/Article/details/gtfflbhvxq.html

[T09] Kotlin：扩展函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtxatbdlgt.html

fun String.exclaim() = this + "!"
来源：http://dali.shanyushiyangtech.top/Article/details/gtodrwvxlj.html

[T10] Kotlin：默认参数
来源：http://dali.gzhubu.top/Article/details/gtlnqfirch.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jyoumei.cn/Article/details/gteqpcbxdf.html

[T11] Kotlin：协程
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnjrdakjv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yangfankeji.com/Article/details/gtyrjndapu.html

[T12] Kotlin：解构声明
来源：http://dali.ydzc1.top/Article/details/gtuojtdxfd.html

val (a, b) = Pair(1, 2)
来源：http://dali.ydzc1.top/Article/details/gttoaxssql.html

[T13] Kotlin：只读 Map
来源：http://dali.hnxiangtu.top/Article/details/gtpsjtjqub.html

val m = mapOf("a" to 1)
来源：http://dali.ydzc1.top/Article/details/gtsqseeokt.html

[T14] Kotlin：循环
来源：http://dali.ivvv.top/Article/details/gtduwyvpor.html

for (i in 1..10) println(i)
来源：http://dali.jinqigufen.top/Article/details/gthlhkvsuo.html

[T15] Kotlin：接口
来源：http://dali.jianghu66.top/Article/details/gtxafjrkto.html

interface Shape { fun area(): Double }
来源：http://dali.tianlin.xyz/Article/details/gtywhtaafx.html

[T16] Swift：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtagrvsfpc.html

print("Hello")
来源：http://dali.jinqigufen.top/Article/details/gtuzxuqrqv.html

[T17] Swift：变量与常量
来源：http://dali.sxryk.cn/Article/details/gtovpqmqfm.html

var a = 1;  let b = 2
来源：http://dali.quarkkingdee.top/Article/details/gtnsdeonyl.html

[T18] Swift：字符串插值
来源：http://dali.kuanghao11.cn/Article/details/gttpncoxbw.html

"值: \(b)"
来源：http://dali.sufxvd.cn/Article/details/gtrxbucxcd.html

[T19] Swift：可选绑定
来源：http://dali.nanxuanxn.top/Article/details/gtrmjspcqm.html

if let n = opt { print(n) }
来源：http://dali.kuanghao11.cn/Article/details/gtbckplqgb.html

[T20] Swift：数组操作
来源：http://dali.wangdashe.top/Article/details/gtqmseaxmx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.fzhhl.top/Article/details/gtwkofnray.html

[T21] Swift：遍历
来源：http://dali.zhijiandao.cn/Article/details/gtmcvouzwb.html

for x in a { print(x) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqdpbatcj.html

[T22] Swift：字典
来源：http://dali.meibo888.top/Article/details/gtzkuimbbd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yuxming.cn/Article/details/gttcxhmwkp.html

[T23] Swift：函数
来源：http://dali.zhoulong.xyz/Article/details/gtlbeorojd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yangfankeji.com/Article/details/gtgzkrwrkt.html

[T24] Swift：闭包
来源：http://dali.gotoacloud.top/Article/details/gtbywmypoa.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.gzhubu.top/Article/details/gtybfqlvpt.html

[T25] Swift：结构体
来源：http://dali.hongshengwenyu.top/Article/details/gtlqilyexc.html

struct P { var x: Int }
来源：http://dali.gaohongyu789.top/Article/details/gtswshonsg.html

[T26] Swift：类与重写
来源：http://dali.ivvv.top/Article/details/gtacejqoah.html

class A: Base { override func f() {} }
来源：http://dali.cqqwz.cn/Article/details/gttklwlhlk.html

[T27] Swift：错误处理
来源：http://dali.pengpengdd.cyou/Article/details/gtwhelqoan.html

do { try f() } catch { print(error) }
来源：http://dali.vqdsnc.cn/Article/details/gtihdlbbiz.html

[T28] Swift：枚举
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwbwfwtvk.html

enum Color { case red, green }
来源：http://dali.gotoacloud.top/Article/details/gtbeezobka.html

[T29] Swift：guard 提前返回
来源：http://dali.ybcxt.top/Article/details/gtqrpcflzi.html

guard let x = opt else { return }
来源：http://dali.ybcxt.top/Article/details/gtprkfvvtf.html

[T30] Swift：协议
来源：http://dali.iojbl.cn/Article/details/gthgtvlewf.html

protocol Shape { func area() -> Double }
来源：http://dali.316326.xyz/Article/details/gtjjlxnpmr.html

[T31] Lua：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtozjnpkzr.html

print("Hello")
来源：http://dali.jinqigfzy.top/Article/details/gtoqycmbnb.html

[T32] Lua：局部变量
来源：http://dali.mhx1999.top/Article/details/gtwccicnzl.html

local a = 1
来源：http://dali.xylfe.cn/Article/details/gtopztoocc.html

[T33] Lua：表（数组）
来源：http://dali.gotoacloud.top/Article/details/gtgtfugpnv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yj20258.top/Article/details/gtkhttangy.html

[T34] Lua：遍历表
来源：http://dali.xuetiantiany.cn/Article/details/gtycxushlq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gtimjmzidn.html

[T35] Lua：字典表
来源：http://dali.316326.xyz/Article/details/gtruoxywul.html

local d = { a = 1 };  d.b = 2
来源：http://dali.gzhubu.top/Article/details/gtksbbclly.html

[T36] Lua：函数
来源：http://dali.zhengqikj.top/Article/details/gthehuqywe.html

function add(a, b) return a + b end
来源：http://dali.zycfv.cn/Article/details/gtrkzbxodk.html

[T37] Lua：字符串拼接
来源：http://dali.chenlongwang.top/Article/details/gtxkgwxgov.html

"a" .. "b"
来源：http://dali.zhengqikj.top/Article/details/gtvkvggbxz.html

[T38] Lua：条件
来源：http://dali.yj202588.top/Article/details/gtdwdtxmpe.html

if x > 0 then print("正") end
来源：http://dali.yangfankeji.com/Article/details/gtwsxrfqlk.html

[T39] Lua：模式匹配
来源：http://dali.hnqzz.top/Article/details/gtarzrzkyp.html

string.find(s, "%d+")
来源：http://dali.xuanzx.com/Article/details/gttiwldvyv.html

[T40] Lua：元表
来源：http://dali.tianlin.xyz/Article/details/gthtxoyris.html

setmetatable({}, { __index = base })
来源：http://dali.gotoacloud.top/Article/details/gtzuiazztv.html

[T41] Perl：Hello World
来源：http://dali.hysaishi.cn/Article/details/gtxdevgwcy.html

print "Hello\n";
来源：http://dali.chenjidiqi.icu/Article/details/gtoxpdjqha.html

[T42] Perl：变量类型
来源：http://dali.jqgufenzy.top/Article/details/gtrcjslopt.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xuetiantiany.cn/Article/details/gtyhrqqdxg.html

[T43] Perl：字符串插值
来源：http://dali.ppjwa.cn/Article/details/gtquvdottx.html

"值: $a"
来源：http://dali.zhengqikj.top/Article/details/gtlrhxjcxx.html

[T44] Perl：条件
来源：http://dali.chenzaomai.com/Article/details/gtjvofcbbi.html

if ($a > 0) { print "正"; }
来源：http://dali.mhx1999.top/Article/details/gtpqvpvens.html

[T45] Perl：数组遍历
来源：http://dali.zhijiandao.cn/Article/details/gtphnbyolp.html

for my $x (@arr) { print $x; }
来源：http://dali.birdmap.top/Article/details/gtjctnacxo.html

[T46] Perl：哈希操作
来源：http://dali.havefunace.top/Article/details/gtbdjlnzqm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.0kj1m.cn/Article/details/gtijfxnesi.html

[T47] Perl：正则捕获
来源：http://dali.ybcxt.top/Article/details/gtciqlzcdn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.fengsongda.top/Article/details/gthkispkns.html

[T48] Perl：正则替换
来源：http://dali.daxiang520.top/Article/details/gtfxyeynwh.html

$s =~ s/old/new/g;
来源：http://dali.fzhhl.top/Article/details/gtqymdkgzt.html

[T49] Perl：函数
来源：http://dali.xuetiantiany.cn/Article/details/gtnzmvdnlt.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhixingplan.top/Article/details/gtwttfpzwu.html

[T50] Perl：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gtxrddhkxl.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.vqdsnc.cn/Article/details/gtirjlxfus.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yangfankeji.com/Article/details/gtdlxkufmi.html

[T51] Scala：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gtgsogjzwf.html

println("Hello")
来源：http://dali.daxiang520.top/Article/details/gtymdlronr.html

[T52] Scala：变量
来源：http://dali.yangfankeji.com/Article/details/gtmnqivrop.html

val a = 1;  var b = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvujnlkcn.html

[T53] Scala：字符串插值
来源：http://dali.vqdsnc.cn/Article/details/gtqtbbjkar.html

s"值: $b"
来源：http://dali.zhixingplan.top/Article/details/gtkurwrmiy.html

[T54] Scala：集合映射
来源：http://dali.9152youxi.cn/Article/details/gtjcnjtyzo.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gogol.net.cn/Article/details/gtedzolhwa.html

[T55] Scala：集合过滤
来源：http://dali.yongpay.top/Article/details/gtkzvazdof.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.smart0.xyz/Article/details/gtxiovzfgl.html

[T56] Scala：样例类
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcncvpyae.html

case class User(name: String, age: Int)
来源：http://dali.fzhhl.top/Article/details/gtplqpyllc.html

[T57] Scala：模式匹配
来源：http://dali.zhongyouzk.top/Article/details/gteohydlmd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jqgufenzy.top/Article/details/gtmjauicgw.html

[T58] Scala：函数定义
来源：http://dali.yueranfly.top/Article/details/gtlsfpfuyi.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.daxiang520.top/Article/details/gtwjwmfbjs.html

[T59] Scala：循环
来源：http://dali.tian-w.cn/Article/details/gtfoizladm.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinghuilouyu.cn/Article/details/gtxjpsybvc.html

[T60] Scala：折叠
来源：http://dali.wangshuangyany.cn/Article/details/gtjbafesuy.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cheryme.top/Article/details/gtgrzivumo.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtcajadfmk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.bjfxy.top/Article/details/gtmshrjacv.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gtlbegkakl.html


<!-- 参考信息 -->