代发 wailian999

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.aibaodan.cn/Article/details/gtcbekocaa.html

[R60] 只看 HTTP 状态码
来源：http://dali.hongshengwenyu.top/Article/details/gthiqmtzst.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.snrcjt.cn/Article/details/gtksmtkcpo.html

[R61] 磁盘占用
来源：http://dali.hammf.cn/Article/details/gtxbknoddj.html

df -h;  du -sh *
来源：http://dali.yj20258.top/Article/details/gtzaeegqli.html

[R62] 找最占空间的文件
来源：http://dali.tianlin.xyz/Article/details/gtyypjrquj.html

du -ah . | sort -rh | head -10
来源：http://dali.cqqwz.cn/Article/details/gtehtsuwhe.html

[R63] 内存与进程
来源：http://dali.vqdsnc.cn/Article/details/gtqjyllgao.html

free -h;  ps aux | grep nginx
来源：http://dali.yuxming.cn/Article/details/gtcotyeapx.html

[R64] 结束进程
来源：http://dali.dashuyun.cn/Article/details/gtwybbmbri.html

kill -9 $(pgrep -f app.py)
来源：http://dali.svipenyu.cn/Article/details/gtzrprxcht.html

[R65] 查看端口占用
来源：http://dali.chenzaomai.com/Article/details/gtgqzjzdtb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hnqzz.top/Article/details/gtbprnkwkj.html

[R66] 定时任务
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrsnjjdca.html

crontab -e;  crontab -l
来源：http://dali.vqdsnc.cn/Article/details/gtlobtxyxa.html

[R67] 生成随机十六进制串
来源：http://dali.meibo888.top/Article/details/gtwbvuwakv.html

openssl rand -hex 16
来源：http://dali.gaohongyu789.top/Article/details/gtgpzybzdy.html

[R68] 计算文件校验值
来源：http://dali.zhengqikj.top/Article/details/gtpkdtwbpf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ivvv.top/Article/details/gtcnefbgoj.html

[R69] 生成随机密码
来源：http://dali.dashuyun.cn/Article/details/gtjpuwgipz.html

head -c 16 /dev/urandom | base64
来源：http://dali.gogol.net.cn/Article/details/gtxuitamav.html

[R70] 时间戳与互转
来源：http://dali.yuanzhike.top/Article/details/gtdlsqrijv.html

date +%s;  date -d @1700000000
来源：http://dali.jqgufenzy.top/Article/details/gtcoovhmaf.html

[R71] 日期格式化
来源：http://dali.snrcjt.cn/Article/details/gtboegjtri.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.svipenyu.cn/Article/details/gtyrraqwde.html

[R72] 等待端口就绪
来源：http://dali.xuanzx.com/Article/details/gthvtwkymj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hywenlv.cn/Article/details/gtakalmoju.html

[R73] 分割大日志
来源：http://dali.sufxvd.cn/Article/details/gtdfjmgnkm.html

split -l 1000 big.log part_
来源：http://dali.jyoumei.cn/Article/details/gtpwtftywu.html

[R74] 批量重命名
来源：http://dali.ybcxt.top/Article/details/gtzunuvlyj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hnxiangtu.top/Article/details/gtcqqlopda.html

[R75] 导出环境变量
来源：http://dali.jyoumei.cn/Article/details/gtqnqrctgu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cheryme.top/Article/details/gttzunuwej.html

[R76] 使用临时文件
来源：http://dali.cqqwz.cn/Article/details/gtmyjvzrrv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jianghu66.top/Article/details/gtxevciidp.html

[R77] 读取用户输入
来源：http://dali.nwbrower.top/Article/details/gtiabizuxr.html

read -rp "请输入: " ans
来源：http://dali.wangdashe.top/Article/details/gtybovtabn.html

[R78] 交互式菜单
来源：http://dali.jqgufenzy.top/Article/details/gtqycrftrt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.guowangkeji.top/Article/details/gtdtmtpkiu.html

[R79] 解析命令行选项
来源：http://dali.jinqigfzy.top/Article/details/gthqpdgfzd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hnqzz.top/Article/details/gtgwfakyjq.html

[R80] 查看脚本执行耗时
来源：http://dali.tanke756.top/Article/details/gtbezegpxl.html

time ./run.sh
来源：http://dali.zdqjudy.top/Article/details/gtoymhroov.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtrbogxamc.html

S. C / C++ 专题
来源：http://dali.haohaochexian.top/Article/details/gtremrzgkt.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtdrxaptjc.html

[S01] C：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtqirxssgo.html

#include <stdio.h>
来源：http://dali.kuanghao11.cn/Article/details/gttkfbcpgo.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sysykeji.top/Article/details/gtusnoqrkf.html

[S02] C：变量与格式化输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlyomhzod.html

int a = 10; printf("%d\n", a);
来源：http://dali.chenzaomai.com/Article/details/gtrrxrkucy.html

[S03] C：读入整数
来源：http://dali.zhiwuduotai.top/Article/details/gtllcggbfq.html

int x; scanf("%d", &x);
来源：http://dali.shuidangran.top/Article/details/gtvxkclqey.html

[S04] C：字符串复制
来源：http://dali.yuanzhike.top/Article/details/gtpirojvjl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yj202588.top/Article/details/gtgtojkdyq.html

[S05] C：字符串长度
来源：http://dali.cheryme.top/Article/details/gtxrdeukkz.html

strlen(s)
来源：http://dali.xuanzx.com/Article/details/gtikniorif.html

[S06] C：字符串比较
来源：http://dali.xuanzx.com/Article/details/gtgreomthu.html

strcmp(a, b) == 0
来源：http://dali.sxryk.cn/Article/details/gtduappibs.html

[S07] C：数组遍历求和
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuhkighpl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.birdmap.top/Article/details/gtpbuwgggv.html

[S08] C：动态内存分配与释放
来源：http://dali.shzxlz.cn/Article/details/gtkkodmomb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.smart0.xyz/Article/details/gtccxaftbu.html

[S09] C：结构体定义与初始化
来源：http://dali.wangdashe.top/Article/details/gtkzjxnyvi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.meibo888.top/Article/details/gtnwuuysoo.html

[S10] C：指针与解引用
来源：http://dali.ppjwa.cn/Article/details/gtsgmvsxbj.html

int *p = &a;  *p = 5;
来源：http://dali.xylfe.cn/Article/details/gtrzawjvtt.html

[S11] C：逐行读文件
来源：http://dali.guannengcc.top/Article/details/gtsertikhj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhiwuduotai.top/Article/details/gtedpzbcwq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.wangdashe.top/Article/details/gtalfryktq.html

fclose(f);
来源：http://dali.0kj1m.cn/Article/details/gttqomfvei.html

[S12] C：写文件
来源：http://dali.bjfxy.top/Article/details/gtpjguzetp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhixingplan.top/Article/details/gtrwxqnlyq.html

[S13] C：宏定义
来源：http://dali.316326.xyz/Article/details/gtjkinkyda.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hnxiangtu.top/Article/details/gtdkyrwiuj.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gtrsufdccq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sufxvd.cn/Article/details/gtuxkwovzt.html

[S15] C：类型转换
来源：http://dali.daria6918.cn/Article/details/gtncatuyia.html

(double) a / b
来源：http://dali.nanxuanxn.top/Article/details/gthjxkfusx.html

[S16] C：位操作置位
来源：http://dali.hongshengwenyu.top/Article/details/gtllzwsoaz.html

x |= (1 << 3);
来源：http://dali.bjfxy.top/Article/details/gtgkyttlxd.html

[S17] C：安全拼接字符串
来源：http://dali.zycfv.cn/Article/details/gtwfkzeory.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jqgfzy.top/Article/details/gtfxbfajue.html

[S18] C：命令行参数
来源：http://dali.iojbl.cn/Article/details/gthmaglomt.html

int main(int argc, char **argv)
来源：http://dali.sweek.top/Article/details/gtpqllupdd.html

[S19] C：快速排序
来源：http://dali.jianghu66.top/Article/details/gtbljdnhdk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.guannengcc.top/Article/details/gtulqauffo.html

[S20] C：二分查找
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtilgpvqgj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ydzc1.top/Article/details/gtnqsofhbf.html

[S21] C：字符类别判断
来源：http://dali.haohaochexian.top/Article/details/gttapqpmrh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yvedp.cn/Article/details/gtgsgxulco.html

[S22] C：字符串转数字
来源：http://dali.wangshuangyany.cn/Article/details/gtnkgnovxe.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttwzbrcwe.html

[S23] C：随机数
来源：http://dali.yuxming.cn/Article/details/gtpsqckaqs.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfxgfedhi.html

[S24] C：获取本地时间
来源：http://dali.tianlin.xyz/Article/details/gtcczmtidg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yueranfly.top/Article/details/gtwybmafsv.html

[S25] C：内存拷贝
来源：http://dali.c1oappe.top/Article/details/gtyipnktgi.html

memcpy(dst, src, n);
来源：http://dali.hfpthk.cn/Article/details/gtzcooqifs.html

[S26] C：内存清零
来源：http://dali.dashuyun.cn/Article/details/gttyztmbou.html

memset(a, 0, sizeof a);
来源：http://dali.haohaochexian.top/Article/details/gtlnudcabw.html

[S27] C：定义常量
来源：http://dali.yuxming.cn/Article/details/gtozqvcvdn.html

const double PI = 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gtrwbslgsa.html

[S28] C：静态变量
来源：http://dali.ppjwa.cn/Article/details/gteabujkkx.html

static int counter = 0;
来源：http://dali.nwbrower.top/Article/details/gtfypuqryx.html

[S29] C：变参函数
来源：http://dali.yongpay.top/Article/details/gtenxmcmye.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shangyingyoupin.top/Article/details/gtytctcjgt.html

[S30] C：头文件保护
来源：http://dali.zhoulong.xyz/Article/details/gthznwbvmw.html

#ifndef X_H
来源：http://dali.shanyushiyangtech.top/Article/details/gtavtqtofz.html

#define X_H
来源：http://dali.haohaochexian.top/Article/details/gtxthkwdas.html

#endif
来源：http://dali.guowangkeji.top/Article/details/gtpnvcraot.html

[S31] C++：Hello World
来源：http://dali.yongpay.top/Article/details/gtspxvzpfm.html

#include <iostream>
来源：http://dali.kuanghao11.cn/Article/details/gtbmlymuba.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ybcxt.top/Article/details/gtznzhocbp.html

[S32] C++：字符串
来源：http://dali.tian-w.cn/Article/details/gtgewhffbr.html

std::string s = "hi";  s += "!";
来源：http://dali.ppjwa.cn/Article/details/gtuqmpenst.html

[S33] C++：vector 增删
来源：http://dali.zhengqikj.top/Article/details/gtddilehmz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.nwbrower.top/Article/details/gtwewcvhbg.html

[S34] C++：遍历 vector
来源：http://dali.sweek.top/Article/details/gtdnejqqnn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.smart0.xyz/Article/details/gtbdlzpkjt.html

[S35] C++：map
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnsmozlyh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gtkednfrtj.html

[S36] C++：unordered_map
来源：http://dali.pycfn.com/Article/details/gtutvbnfth.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gtcklflomn.html

[S37] C++：set
来源：http://dali.jiagoushi.top/Article/details/gtenblncgi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zdqjudy.top/Article/details/gtmvtogtyi.html

[S38] C++：排序
来源：http://dali.ivvv.top/Article/details/gtgigjfokn.html

std::sort(v.begin(), v.end());
来源：http://dali.hongshengwenyu.top/Article/details/gtvlwvqeda.html

[S39] C++：自定义比较器排序
来源：http://dali.feifeiyinyue.top/Article/details/gtbbsgqekb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gaohongyu789.top/Article/details/gtllglbvmn.html

[S40] C++：查找元素
来源：http://dali.cqqwz.cn/Article/details/gtknulwnip.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sweek.top/Article/details/gtwwricltf.html

[S41] C++：类与构造函数
来源：http://dali.jqgfzy.top/Article/details/gtowntiulx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ivvv.top/Article/details/gtvplgfkbg.html

[S42] C++：继承与虚函数
来源：http://dali.shuidangran.top/Article/details/gtkzuhofqd.html

class B : public Base { public: void f() override {} };
来源：http://dali.gaohongyu789.top/Article/details/gtititycca.html

[S43] C++：智能指针
来源：http://dali.shangyingyoupin.top/Article/details/gtcjxzeqsa.html

auto p = std::make_unique<int>(5);
来源：http://dali.yj20258888.top/Article/details/gtsxzeujhh.html

[S44] C++：引用传参
来源：http://dali.pycfn.com/Article/details/gtnklmspot.html

void inc(int &x) { ++x; }
来源：http://dali.zdqjudy.top/Article/details/gtuofckqtz.html

[S45] C++：lambda
来源：http://dali.hysaishi.cn/Article/details/gtlsgflfys.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nwbrower.top/Article/details/gtgwekkkxo.html

[S46] C++：函数模板
来源：http://dali.xinyue.icu/Article/details/gtyvplgwif.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.feifeiyinyue.top/Article/details/gtwqhvdymt.html

[S47] C++：结构化绑定遍历
来源：http://dali.birdmap.top/Article/details/gtdlylwgls.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.aizwys.cn/Article/details/gtsqdnbvbr.html

[S48] C++：逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gthpndtmin.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jiagoushi.top/Article/details/gtllwfhftp.html

while (std::getline(in, line)) { }
来源：http://dali.chenjidiqi.icu/Article/details/gtyultzupj.html

[S49] C++：写文件
来源：http://dali.tanke756.top/Article/details/gtemxjnole.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gotoacloud.top/Article/details/gtwukoarmt.html

[S50] C++：格式化数字
来源：http://dali.dashuyun.cn/Article/details/gtrgjvfbtw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.iojbl.cn/Article/details/gtulrpklkg.html

[S51] C++：显式类型转换
来源：http://dali.birdmap.top/Article/details/gthxxvyugj.html

static_cast<double>(a) / b
来源：http://dali.jyoumei.cn/Article/details/gtoemqsidd.html

[S52] C++：const 与 noexcept
来源：http://dali.wangshuangyany.cn/Article/details/gtdqnjnlgj.html

int size() const noexcept { return n_; }
来源：http://dali.zhixingplan.top/Article/details/gttejmwpnm.html

[S53] C++：移动语义
来源：http://dali.jyoumei.cn/Article/details/gtatogyazr.html

std::vector<int> w = std::move(v);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkbmebnir.html

[S54] C++：异常处理
来源：http://dali.xylfe.cn/Article/details/gtiocwjees.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.fzhhl.top/Article/details/gtvovtdzmv.html

[S55] C++：结构化绑定
来源：http://dali.gogol.net.cn/Article/details/gtfgyvkiyr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shzxlz.cn/Article/details/gtdmtczmgn.html

[S56] C++：optional
来源：http://dali.xylfe.cn/Article/details/gthvutlbwz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhongyouzk.top/Article/details/gtjbdmxrzq.html

[S57] C++：编译期常量
来源：http://dali.hysaishi.cn/Article/details/gtppqbskxn.html

constexpr int N = 10;
来源：http://dali.316326.xyz/Article/details/gtqhyxjeey.html

[S58] C++：命名空间
来源：http://dali.havefunace.top/Article/details/gtnpxkdnqe.html

namespace ns { int f() { return 1; } }
来源：http://dali.yonumen.top/Article/details/gtjjoawexq.html

[S59] C++：静态断言
来源：http://dali.ybcxt.top/Article/details/gtjzwasumw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yvedp.cn/Article/details/gtwzpzcbmd.html

[S60] C++：遍历并删除元素
来源：http://dali.ywan-chungtsiang.top/Article/details/gtupwgsfab.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xuanzx.com/Article/details/gtmbqqtbez.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtdhvvxuyq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jiagoushi.top/Article/details/gtmmkigqsm.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtmsauiwmc.html

[T01] Kotlin：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtrwhipvxe.html

println("Hello")
来源：http://dali.aibaodan.cn/Article/details/gtuxzcjtbx.html

[T02] Kotlin：变量
来源：http://dali.wangdashe.top/Article/details/gthrhylauz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.316326.xyz/Article/details/gtgojsaxjq.html

[T03] Kotlin：字符串模板
来源：http://dali.jyoumei.cn/Article/details/gtvdlazhgb.html

"值: $b"
来源：http://dali.yvedp.cn/Article/details/gtozymlxhx.html

[T04] Kotlin：空安全
来源：http://dali.yvedp.cn/Article/details/gtcfnfcrqy.html

val n: String? = null;  n?.length
来源：http://dali.jqgfzy.top/Article/details/gtmgkysexo.html

[T05] Kotlin：when 表达式
来源：http://dali.chenzaomai.com/Article/details/gtrpsrbdon.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xuetiantiany.cn/Article/details/gteuxxujrc.html

[T06] Kotlin：集合映射
来源：http://dali.cashguo.top/Article/details/gtgevapasm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cheryme.top/Article/details/gtxuebtqix.html

[T07] Kotlin：集合过滤
来源：http://dali.dashuyun.cn/Article/details/gtbrthmvnl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.aibaodan.cn/Article/details/gtcqyocdbt.html

[T08] Kotlin：数据类
来源：http://dali.jqgfzy.top/Article/details/gtnfbjxkem.html

data class User(val name: String, val age: Int)
来源：http://dali.chenzaomai.com/Article/details/gtsfrwhuvl.html

[T09] Kotlin：扩展函数
来源：http://dali.sweek.top/Article/details/gthymhaivl.html

fun String.exclaim() = this + "!"
来源：http://dali.daxiang520.top/Article/details/gtqftmoaei.html

[T10] Kotlin：默认参数
来源：http://dali.mhx1999.top/Article/details/gtsneapsqe.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.daria6918.cn/Article/details/gtfytjnzif.html

[T11] Kotlin：协程
来源：http://dali.smart0.xyz/Article/details/gtcftgcpgr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhixingplan.top/Article/details/gthdojinie.html

[T12] Kotlin：解构声明
来源：http://dali.ydzc1.top/Article/details/gtexutougi.html

val (a, b) = Pair(1, 2)
来源：http://dali.0kj1m.cn/Article/details/gtbsmbvydr.html

[T13] Kotlin：只读 Map
来源：http://dali.gotoacloud.top/Article/details/gtlmjabezp.html

val m = mapOf("a" to 1)
来源：http://dali.svipenyu.cn/Article/details/gtxkuyhiza.html

[T14] Kotlin：循环
来源：http://dali.daria6918.cn/Article/details/gtsfgnvnzf.html

for (i in 1..10) println(i)
来源：http://dali.redwolf501.top/Article/details/gtejercrfe.html

[T15] Kotlin：接口
来源：http://dali.hongshengwenyu.top/Article/details/gtdbykgxgp.html

interface Shape { fun area(): Double }
来源：http://dali.nanxuanxn.top/Article/details/gtqxnggidr.html

[T16] Swift：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtfsniwgye.html

print("Hello")
来源：http://dali.sysykeji.top/Article/details/gtjhtsbqhp.html

[T17] Swift：变量与常量
来源：http://dali.xylfe.cn/Article/details/gttefgwefo.html

var a = 1;  let b = 2
来源：http://dali.yanxiufei.cn/Article/details/gtvndyxaqf.html

[T18] Swift：字符串插值
来源：http://dali.dianchejie.cn/Article/details/gtdcmquotf.html

"值: \(b)"
来源：http://dali.ppjwa.cn/Article/details/gtropbbvto.html

[T19] Swift：可选绑定
来源：http://dali.shzxlz.cn/Article/details/gtovocpgdn.html

if let n = opt { print(n) }
来源：http://dali.jinqigfzy.top/Article/details/gtnqpakmzr.html

[T20] Swift：数组操作
来源：http://dali.316326.xyz/Article/details/gtkgxpvwgz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.smart0.xyz/Article/details/gtyfqtixch.html

[T21] Swift：遍历
来源：http://dali.svipenyu.cn/Article/details/gtziiaebtq.html

for x in a { print(x) }
来源：http://dali.andypj.xyz/Article/details/gtrlzxbakl.html

[T22] Swift：字典
来源：http://dali.zhengqikj.top/Article/details/gtsayelaxi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cdnleiting.top/Article/details/gtdaizhfaf.html

[T23] Swift：函数
来源：http://dali.andypj.xyz/Article/details/gtjynjugcm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jyoumei.cn/Article/details/gttakqhfnn.html

[T24] Swift：闭包
来源：http://dali.jianghu66.top/Article/details/gtiiwxxdum.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sweek.top/Article/details/gttruhswbs.html

[T25] Swift：结构体
来源：http://dali.aibaodan.cn/Article/details/gtoskdqjlm.html

struct P { var x: Int }
来源：http://dali.quarkkingdee.top/Article/details/gtrzhtuvtm.html

[T26] Swift：类与重写
来源：http://dali.daria6918.cn/Article/details/gtkgiqlehu.html

class A: Base { override func f() {} }
来源：http://dali.gaohongyu789.top/Article/details/gtlueychgg.html

[T27] Swift：错误处理
来源：http://dali.jinqigfzy.top/Article/details/gtgxplbxer.html

do { try f() } catch { print(error) }
来源：http://dali.wangdashe.top/Article/details/gtyqqjngmk.html

[T28] Swift：枚举
来源：http://dali.daria6918.cn/Article/details/gtcpwtarnk.html

enum Color { case red, green }
来源：http://dali.yuxming.cn/Article/details/gtdgpzbevz.html

[T29] Swift：guard 提前返回
来源：http://dali.zhoulong.xyz/Article/details/gteisugcsp.html

guard let x = opt else { return }
来源：http://dali.cqqwz.cn/Article/details/gtphpjyicl.html

[T30] Swift：协议
来源：http://dali.hfpthk.cn/Article/details/gtkzwopfcg.html

protocol Shape { func area() -> Double }
来源：http://dali.chenzaomai.com/Article/details/gtfwinjloo.html

[T31] Lua：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtjzzrdhtc.html

print("Hello")
来源：http://dali.shanyushiyangtech.top/Article/details/gtrmcnjvkp.html

[T32] Lua：局部变量
来源：http://dali.redwolf501.top/Article/details/gtetaopdji.html

local a = 1
来源：http://dali.shanyushiyangtech.top/Article/details/gtjgksesqi.html

[T33] Lua：表（数组）
来源：http://dali.tianlin.xyz/Article/details/gtjrwwwdbu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.daxiang520.top/Article/details/gtllldxvtj.html

[T34] Lua：遍历表
来源：http://dali.zhaomingkeji.xyz/Article/details/gteqhmwscd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zycfv.cn/Article/details/gtgtwudamh.html

[T35] Lua：字典表
来源：http://dali.wangdashe.top/Article/details/gtxcbibxpg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtetohzfsf.html

[T36] Lua：函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtlkvscejs.html

function add(a, b) return a + b end
来源：http://dali.shzxlz.cn/Article/details/gtbjavbyti.html

[T37] Lua：字符串拼接
来源：http://dali.sysykeji.top/Article/details/gtwobsjfbv.html

"a" .. "b"
来源：http://dali.pycfn.com/Article/details/gtyzvlrlsk.html

[T38] Lua：条件
来源：http://dali.bjfxy.top/Article/details/gtvuigeolk.html

if x > 0 then print("正") end
来源：http://dali.shuidangran.top/Article/details/gtpiolxdhl.html

[T39] Lua：模式匹配
来源：http://dali.shzxlz.cn/Article/details/gtbybddrfo.html

string.find(s, "%d+")
来源：http://dali.jiagoushi.top/Article/details/gtejahojxk.html

[T40] Lua：元表
来源：http://dali.xylfe.cn/Article/details/gtucgvyyec.html

setmetatable({}, { __index = base })
来源：http://dali.feifeiyinyue.top/Article/details/gtedzrstlq.html

[T41] Perl：Hello World
来源：http://dali.hysaishi.cn/Article/details/gtvvpygffk.html

print "Hello\n";
来源：http://dali.c1oappe.top/Article/details/gtxmwlskns.html

[T42] Perl：变量类型
来源：http://dali.gotoacloud.top/Article/details/gtymafpiqx.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.quarkkingdee.top/Article/details/gtdqcqgupr.html

[T43] Perl：字符串插值
来源：http://dali.jianghu66.top/Article/details/gteqwefwwk.html

"值: $a"
来源：http://dali.wangdashe.top/Article/details/gtupkrfaon.html

[T44] Perl：条件
来源：http://dali.yvedp.cn/Article/details/gtsbxyflem.html

if ($a > 0) { print "正"; }
来源：http://dali.birdmap.top/Article/details/gtgeetjezz.html

[T45] Perl：数组遍历
来源：http://dali.sweek.top/Article/details/gtyhydjwem.html

for my $x (@arr) { print $x; }
来源：http://dali.ivvv.top/Article/details/gtsfztxrii.html

[T46] Perl：哈希操作
来源：http://dali.fengsongda.top/Article/details/gtowxalxhu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yj20258888.top/Article/details/gtfmjbljic.html

[T47] Perl：正则捕获
来源：http://dali.chenjidiqi.icu/Article/details/gtjritsozk.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.cucudq.cn/Article/details/gtoyqwhueb.html

[T48] Perl：正则替换
来源：http://dali.tian-w.cn/Article/details/gtfnteaaka.html

$s =~ s/old/new/g;
来源：http://dali.andypj.xyz/Article/details/gtuwumlrlu.html

[T49] Perl：函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaunyeyrr.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.cheryme.top/Article/details/gtaocuqayw.html

[T50] Perl：逐行读文件
来源：http://dali.bjfxy.top/Article/details/gtawdkbejr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yj202588.top/Article/details/gtwmnsjhnq.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jinqigfzy.top/Article/details/gtgcnftltx.html

[T51] Scala：Hello World
来源：http://dali.sxryk.cn/Article/details/gtygiuzgud.html

println("Hello")
来源：http://dali.gogol.net.cn/Article/details/gthkglxwmb.html

[T52] Scala：变量
来源：http://dali.shangyingyoupin.top/Article/details/gtcpaprqgy.html

val a = 1;  var b = 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gteujvbotg.html

[T53] Scala：字符串插值
来源：http://dali.zhoulong.xyz/Article/details/gtylycngys.html

s"值: $b"
来源：http://dali.shuidangran.top/Article/details/gtmzozswpg.html

[T54] Scala：集合映射
来源：http://dali.chenzaomai.com/Article/details/gtclewffer.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbfhploal.html

[T55] Scala：集合过滤
来源：http://dali.kuanghao11.cn/Article/details/gtrrmqgmlz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jlsjyb.cn/Article/details/gtzutpsvgn.html

[T56] Scala：样例类
来源：http://dali.hysaishi.cn/Article/details/gtqznxilpw.html

case class User(name: String, age: Int)
来源：http://dali.xuetiantiany.cn/Article/details/gtmffdxkus.html

[T57] Scala：模式匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxxyraokn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cheryme.top/Article/details/gtyvdiorkz.html

[T58] Scala：函数定义
来源：http://dali.iojbl.cn/Article/details/gtvkyfknok.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.shzxlz.cn/Article/details/gttgdvchxq.html

[T59] Scala：循环
来源：http://dali.zhoulong.xyz/Article/details/gtfvreyoro.html

for (i <- 1 to 10) println(i)
来源：http://dali.xylfe.cn/Article/details/gttjkjmyvk.html

[T60] Scala：折叠
来源：http://dali.jyoumei.cn/Article/details/gtdjdwlexn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hywenlv.cn/Article/details/gtmcinrods.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtoirfhsyp.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.ehwqpu.com/Article/details/gtggoxacel.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtdfeqkdxg.html


<!-- 参考信息 -->