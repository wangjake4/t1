代发 wailian999

ssh user@host 'uptime'
来源：http://dali.pengpengdd.cyou/Article/details/gtjzzfghwa.html

[R58] 下载文件
来源：http://dali.nanxinkj.top/Article/details/gtmguseyba.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shzxlz.cn/Article/details/gtrdxldnqm.html

[R59] 发 POST JSON
来源：http://dali.gaohongyu789.top/Article/details/gthgexcoxw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hnxiangtu.top/Article/details/gtxhdzjdee.html

[R60] 只看 HTTP 状态码
来源：http://dali.yuxming.cn/Article/details/gtjytmcyro.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.mhx1999.top/Article/details/gtorfkxxjc.html

[R61] 磁盘占用
来源：http://dali.cucudq.cn/Article/details/gthbgwutie.html

df -h;  du -sh *
来源：http://dali.sweek.top/Article/details/gtvlpqffsa.html

[R62] 找最占空间的文件
来源：http://dali.ivvv.top/Article/details/gtzpjcbdac.html

du -ah . | sort -rh | head -10
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzifcdkzr.html

[R63] 内存与进程
来源：http://dali.cashguo.top/Article/details/gtvzquxrtg.html

free -h;  ps aux | grep nginx
来源：http://dali.guowangkeji.top/Article/details/gtcmqayzjp.html

[R64] 结束进程
来源：http://dali.zhixingplan.top/Article/details/gtfuhkkwei.html

kill -9 $(pgrep -f app.py)
来源：http://dali.aibaodan.cn/Article/details/gtytlgjixd.html

[R65] 查看端口占用
来源：http://dali.ehwqpu.com/Article/details/gtemnhzfay.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.redwolf501.top/Article/details/gtwbcamhss.html

[R66] 定时任务
来源：http://dali.feifeiyinyue.top/Article/details/gtadzmmcof.html

crontab -e;  crontab -l
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcccrafkj.html

[R67] 生成随机十六进制串
来源：http://dali.fzhhl.top/Article/details/gtgtprpvkj.html

openssl rand -hex 16
来源：http://dali.cheryme.top/Article/details/gtcsvcbkts.html

[R68] 计算文件校验值
来源：http://dali.sxryk.cn/Article/details/gtvbgliius.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtvzsnxgnq.html

[R69] 生成随机密码
来源：http://dali.dianchejie.cn/Article/details/gthpwdyhce.html

head -c 16 /dev/urandom | base64
来源：http://dali.chenlongwang.top/Article/details/gtatbfybob.html

[R70] 时间戳与互转
来源：http://dali.cdnleiting.top/Article/details/gtgicrnpry.html

date +%s;  date -d @1700000000
来源：http://dali.quarkkingdee.top/Article/details/gtqqtzarrm.html

[R71] 日期格式化
来源：http://dali.hywenlv.cn/Article/details/gtliaxgltx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gaohongyu789.top/Article/details/gtwarmtbwf.html

[R72] 等待端口就绪
来源：http://dali.fzhhl.top/Article/details/gtvnnqqokn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hfpthk.cn/Article/details/gtbwoyzvfj.html

[R73] 分割大日志
来源：http://dali.cucudq.cn/Article/details/gtziyfqlac.html

split -l 1000 big.log part_
来源：http://dali.nwbrower.top/Article/details/gtiutmqztc.html

[R74] 批量重命名
来源：http://dali.sufxvd.cn/Article/details/gtmgstwkex.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hywenlv.cn/Article/details/gtsxaumhjl.html

[R75] 导出环境变量
来源：http://dali.wangdashe.top/Article/details/gtflwlixxl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sxryk.cn/Article/details/gtdywtrouo.html

[R76] 使用临时文件
来源：http://dali.yj20258.top/Article/details/gtforjnnpv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gaohongyu789.top/Article/details/gtapalfjav.html

[R77] 读取用户输入
来源：http://dali.jinqigufen.top/Article/details/gtzlktrydc.html

read -rp "请输入: " ans
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdhmnzvmm.html

[R78] 交互式菜单
来源：http://dali.chenlongwang.top/Article/details/gtkcyqypyd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gotoacloud.top/Article/details/gtizjwehto.html

[R79] 解析命令行选项
来源：http://dali.chenlongwang.top/Article/details/gtfanhtwya.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yanxiufei.cn/Article/details/gtgjwbwyye.html

[R80] 查看脚本执行耗时
来源：http://dali.jinqigufen.top/Article/details/gtliwdhlpd.html

time ./run.sh
来源：http://dali.yueranfly.top/Article/details/gtusbrkqeh.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtgaxxscvs.html

S. C / C++ 专题
来源：http://dali.cashguo.top/Article/details/gtlitizjpt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtcyerpvri.html

[S01] C：Hello World
来源：http://dali.smart0.xyz/Article/details/gttfoizust.html

#include <stdio.h>
来源：http://dali.hfpthk.cn/Article/details/gtcdnlwhoy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yj20258888.top/Article/details/gtaofgwiow.html

[S02] C：变量与格式化输出
来源：http://dali.cheryme.top/Article/details/gtjayxyvfd.html

int a = 10; printf("%d\n", a);
来源：http://dali.ivvv.top/Article/details/gtqicboguo.html

[S03] C：读入整数
来源：http://dali.hnxiangtu.top/Article/details/gtqtvlkyej.html

int x; scanf("%d", &x);
来源：http://dali.fengsongda.top/Article/details/gtufbqbbxx.html

[S04] C：字符串复制
来源：http://dali.shangyingyoupin.top/Article/details/gtcfbszgam.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.tanke756.top/Article/details/gtybwxvekg.html

[S05] C：字符串长度
来源：http://dali.aibaodan.cn/Article/details/gtfwxztsef.html

strlen(s)
来源：http://dali.hywenlv.cn/Article/details/gtqwcveaig.html

[S06] C：字符串比较
来源：http://dali.yvedp.cn/Article/details/gtfkhfjlta.html

strcmp(a, b) == 0
来源：http://dali.9152youxi.cn/Article/details/gtqzwmzphv.html

[S07] C：数组遍历求和
来源：http://dali.kuanghao11.cn/Article/details/gtozuvnjym.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gotoacloud.top/Article/details/gtfduzizsr.html

[S08] C：动态内存分配与释放
来源：http://dali.tanke756.top/Article/details/gtklamiwpj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jianghu66.top/Article/details/gttlubziyj.html

[S09] C：结构体定义与初始化
来源：http://dali.tian-w.cn/Article/details/gtacnkacoa.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.guowangkeji.top/Article/details/gtdtowgjlc.html

[S10] C：指针与解引用
来源：http://dali.chenjidiqi.icu/Article/details/gtskhwennf.html

int *p = &a;  *p = 5;
来源：http://dali.xinyue.icu/Article/details/gtgttqgjbm.html

[S11] C：逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gtgxkovmqy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sxryk.cn/Article/details/gtwnmhcaxk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hywenlv.cn/Article/details/gtqtphtffg.html

fclose(f);
来源：http://dali.nanxuanxn.top/Article/details/gtbqhfihfr.html

[S12] C：写文件
来源：http://dali.smart0.xyz/Article/details/gtgtspigjg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.haohaochexian.top/Article/details/gtcwamjckt.html

[S13] C：宏定义
来源：http://dali.snrcjt.cn/Article/details/gtkmfncask.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yangfankeji.com/Article/details/gtavxcoggk.html

[S14] C：枚举
来源：http://dali.wangshuangyany.cn/Article/details/gtlxhrbtcs.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gtnidlqyka.html

[S15] C：类型转换
来源：http://dali.gotoacloud.top/Article/details/gtfpgnosel.html

(double) a / b
来源：http://dali.316326.xyz/Article/details/gtuubgtmao.html

[S16] C：位操作置位
来源：http://dali.zhiwuduotai.top/Article/details/gtmucgaeey.html

x |= (1 << 3);
来源：http://dali.birdmap.top/Article/details/gtusamjpys.html

[S17] C：安全拼接字符串
来源：http://dali.feifeiyinyue.top/Article/details/gthxoaodki.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.vqdsnc.cn/Article/details/gtthmdrrnq.html

[S18] C：命令行参数
来源：http://dali.gzhubu.top/Article/details/gtmlluuodt.html

int main(int argc, char **argv)
来源：http://dali.xziqi.cn/Article/details/gtieyrzwfp.html

[S19] C：快速排序
来源：http://dali.quarkkingdee.top/Article/details/gtbenunxgm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhoulong.xyz/Article/details/gtndhzcfqt.html

[S20] C：二分查找
来源：http://dali.svipenyu.cn/Article/details/gtdpnrfkmk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cashguo.top/Article/details/gtqhmnwnlq.html

[S21] C：字符类别判断
来源：http://dali.hnxiangtu.top/Article/details/gtmooswpyk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shanyushiyangtech.top/Article/details/gtrkcxuoky.html

[S22] C：字符串转数字
来源：http://dali.dianchejie.cn/Article/details/gtsbdwzplm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yueranfly.top/Article/details/gtdledkusv.html

[S23] C：随机数
来源：http://dali.hnqzz.top/Article/details/gtpiwcxcyq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.mhx1999.top/Article/details/gtyanufhnl.html

[S24] C：获取本地时间
来源：http://dali.dashuyun.cn/Article/details/gtkolyykte.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yonumen.top/Article/details/gtnoquztuo.html

[S25] C：内存拷贝
来源：http://dali.svipenyu.cn/Article/details/gthrzelbpd.html

memcpy(dst, src, n);
来源：http://dali.jiagoushi.top/Article/details/gtxuzkxbcd.html

[S26] C：内存清零
来源：http://dali.ivvv.top/Article/details/gtfscolpnd.html

memset(a, 0, sizeof a);
来源：http://dali.mhx1999.top/Article/details/gtqbwfgreq.html

[S27] C：定义常量
来源：http://dali.sufxvd.cn/Article/details/gtoigmqbmo.html

const double PI = 3.14159;
来源：http://dali.smart0.xyz/Article/details/gtefincikl.html

[S28] C：静态变量
来源：http://dali.zhoulong.xyz/Article/details/gtllmvjznk.html

static int counter = 0;
来源：http://dali.yj20258888.top/Article/details/gtwgtpdwxs.html

[S29] C：变参函数
来源：http://dali.shangyingyoupin.top/Article/details/gthntlxlmo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.0kj1m.cn/Article/details/gtozirljvt.html

[S30] C：头文件保护
来源：http://dali.jyoumei.cn/Article/details/gtuqdgtwra.html

#ifndef X_H
来源：http://dali.dianchejie.cn/Article/details/gtxugpavai.html

#define X_H
来源：http://dali.guannengcc.top/Article/details/gtoylmefyn.html

#endif
来源：http://dali.cucudq.cn/Article/details/gtncjnkctq.html

[S31] C++：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtndozquoo.html

#include <iostream>
来源：http://dali.fzhhl.top/Article/details/gtqfiztesp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtorslvfji.html

[S32] C++：字符串
来源：http://dali.shangyingyoupin.top/Article/details/gtfljinxoe.html

std::string s = "hi";  s += "!";
来源：http://dali.guannengcc.top/Article/details/gtuxvvptux.html

[S33] C++：vector 增删
来源：http://dali.yvedp.cn/Article/details/gtiwmmfvze.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.dianchejie.cn/Article/details/gtfdctzeti.html

[S34] C++：遍历 vector
来源：http://dali.havefunace.top/Article/details/gtxqgthlto.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hfpthk.cn/Article/details/gtkxxjiqrg.html

[S35] C++：map
来源：http://dali.aizwys.cn/Article/details/gtmfciigxg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shzxlz.cn/Article/details/gtovifzjza.html

[S36] C++：unordered_map
来源：http://dali.0kj1m.cn/Article/details/gtnixgrrnm.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gtqsltzbim.html

[S37] C++：set
来源：http://dali.daxiang520.top/Article/details/gtybtkjyog.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cucudq.cn/Article/details/gtkddahlmg.html

[S38] C++：排序
来源：http://dali.gaohongyu789.top/Article/details/gthwleqwlo.html

std::sort(v.begin(), v.end());
来源：http://dali.yangfankeji.com/Article/details/gtxvbgysay.html

[S39] C++：自定义比较器排序
来源：http://dali.jyoumei.cn/Article/details/gtlbtlxixg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hnxiangtu.top/Article/details/gtmagoogys.html

[S40] C++：查找元素
来源：http://dali.svipenyu.cn/Article/details/gtsyyosnge.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yj20258.top/Article/details/gtfcwoyohy.html

[S41] C++：类与构造函数
来源：http://dali.jianghu66.top/Article/details/gtvxnggwjz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.guannengcc.top/Article/details/gtdfodtvlz.html

[S42] C++：继承与虚函数
来源：http://dali.yj202588.top/Article/details/gtfqlldgto.html

class B : public Base { public: void f() override {} };
来源：http://dali.jyoumei.cn/Article/details/gttxezhdwb.html

[S43] C++：智能指针
来源：http://dali.sxryk.cn/Article/details/gtrlsieygl.html

auto p = std::make_unique<int>(5);
来源：http://dali.daxiang520.top/Article/details/gthlbedmmu.html

[S44] C++：引用传参
来源：http://dali.jinqigfzy.top/Article/details/gtevzemsxk.html

void inc(int &x) { ++x; }
来源：http://dali.sweek.top/Article/details/gtmhirqgmc.html

[S45] C++：lambda
来源：http://dali.aibaodan.cn/Article/details/gthcdurwjt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hnxiangtu.top/Article/details/gtbaiuourp.html

[S46] C++：函数模板
来源：http://dali.zhiwuduotai.top/Article/details/gtfflvbpru.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxozwrfjl.html

[S47] C++：结构化绑定遍历
来源：http://dali.cashguo.top/Article/details/gtthewmliy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ppjwa.cn/Article/details/gtichmoqfk.html

[S48] C++：逐行读文件
来源：http://dali.wangdashe.top/Article/details/gteihlqfak.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shanyushiyangtech.top/Article/details/gtmaoqjkzk.html

while (std::getline(in, line)) { }
来源：http://dali.shanyushiyangtech.top/Article/details/gtzgkydkzx.html

[S49] C++：写文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrywazuvo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cucudq.cn/Article/details/gtkptlekxe.html

[S50] C++：格式化数字
来源：http://dali.yvedp.cn/Article/details/gthnlhbyrg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gthanxwuce.html

[S51] C++：显式类型转换
来源：http://dali.hysaishi.cn/Article/details/gtsegcxgyr.html

static_cast<double>(a) / b
来源：http://dali.hnxiangtu.top/Article/details/gtggjrmzej.html

[S52] C++：const 与 noexcept
来源：http://dali.daxiang520.top/Article/details/gtdizrzrwx.html

int size() const noexcept { return n_; }
来源：http://dali.iojbl.cn/Article/details/gtjsenlnfx.html

[S53] C++：移动语义
来源：http://dali.jinqigfzy.top/Article/details/gttkfxniru.html

std::vector<int> w = std::move(v);
来源：http://dali.jinqigfzy.top/Article/details/gtsuextskb.html

[S54] C++：异常处理
来源：http://dali.hnqzz.top/Article/details/gtitvfmmoi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.0kj1m.cn/Article/details/gtskmtilgt.html

[S55] C++：结构化绑定
来源：http://dali.yj20258888.top/Article/details/gthinbjepw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.sweek.top/Article/details/gtdlltifip.html

[S56] C++：optional
来源：http://dali.hnxiangtu.top/Article/details/gtrqybahur.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtmgconhun.html

[S57] C++：编译期常量
来源：http://dali.jlsjyb.cn/Article/details/gtzlmdbtxd.html

constexpr int N = 10;
来源：http://dali.shangyingyoupin.top/Article/details/gtnwuxcrsj.html

[S58] C++：命名空间
来源：http://dali.chenjidiqi.icu/Article/details/gtzbxyncbz.html

namespace ns { int f() { return 1; } }
来源：http://dali.nanxinkj.top/Article/details/gtcgkwgypa.html

[S59] C++：静态断言
来源：http://dali.nwbrower.top/Article/details/gtivgabnfp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.9152youxi.cn/Article/details/gtbkcyvcma.html

[S60] C++：遍历并删除元素
来源：http://dali.svipenyu.cn/Article/details/gtqnhetzqw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yueranfly.top/Article/details/gtcccjwwxg.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtoktlxxok.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.9152youxi.cn/Article/details/gtqwvxzrgl.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtuyqdlfbv.html

[T01] Kotlin：Hello World
来源：http://dali.bjfxy.top/Article/details/gthattnpno.html

println("Hello")
来源：http://dali.sxryk.cn/Article/details/gttskygofs.html

[T02] Kotlin：变量
来源：http://dali.xuanzx.com/Article/details/gtpkzrrxqe.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.svipenyu.cn/Article/details/gtaxjcfzdm.html

[T03] Kotlin：字符串模板
来源：http://dali.xuanzx.com/Article/details/gtgnlehyky.html

"值: $b"
来源：http://dali.nwbrower.top/Article/details/gtjmhawqmg.html

[T04] Kotlin：空安全
来源：http://dali.gotoacloud.top/Article/details/gtssdncevr.html

val n: String? = null;  n?.length
来源：http://dali.cucudq.cn/Article/details/gtizinugpt.html

[T05] Kotlin：when 表达式
来源：http://dali.gaohongyu789.top/Article/details/gtrajhowqp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinghuilouyu.cn/Article/details/gtugkvojuc.html

[T06] Kotlin：集合映射
来源：http://dali.wangdashe.top/Article/details/gtdvsqttaj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shzxlz.cn/Article/details/gtllbfxnrf.html

[T07] Kotlin：集合过滤
来源：http://dali.nwbrower.top/Article/details/gtjhoskqip.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ybcxt.top/Article/details/gtgidnlydw.html

[T08] Kotlin：数据类
来源：http://dali.gogol.net.cn/Article/details/gtgpkujvav.html

data class User(val name: String, val age: Int)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqszkqidt.html

[T09] Kotlin：扩展函数
来源：http://dali.birdmap.top/Article/details/gtelguokpj.html

fun String.exclaim() = this + "!"
来源：http://dali.mhx1999.top/Article/details/gteiequatj.html

[T10] Kotlin：默认参数
来源：http://dali.tianlin.xyz/Article/details/gtkoixydnr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.pycfn.com/Article/details/gtqnuehtsc.html

[T11] Kotlin：协程
来源：http://dali.redwolf501.top/Article/details/gtvxixtlyp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shuidangran.top/Article/details/gtslxzlkay.html

[T12] Kotlin：解构声明
来源：http://dali.iojbl.cn/Article/details/gtsmivbuos.html

val (a, b) = Pair(1, 2)
来源：http://dali.svipenyu.cn/Article/details/gtwhgrtbrl.html

[T13] Kotlin：只读 Map
来源：http://dali.andypj.xyz/Article/details/gtianzdapz.html

val m = mapOf("a" to 1)
来源：http://dali.aibaodan.cn/Article/details/gtfwoqnqgd.html

[T14] Kotlin：循环
来源：http://dali.dashuyun.cn/Article/details/gtujdthjmk.html

for (i in 1..10) println(i)
来源：http://dali.fengsongda.top/Article/details/gtpnmnxiog.html

[T15] Kotlin：接口
来源：http://dali.daxiang520.top/Article/details/gtssfxbqtn.html

interface Shape { fun area(): Double }
来源：http://dali.jinghuilouyu.cn/Article/details/gtasdjihef.html

[T16] Swift：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtdkxtroxp.html

print("Hello")
来源：http://dali.hammf.cn/Article/details/gtxhqnecwb.html

[T17] Swift：变量与常量
来源：http://dali.guannengcc.top/Article/details/gtoluizqds.html

var a = 1;  let b = 2
来源：http://dali.9152youxi.cn/Article/details/gtfgiefwgy.html

[T18] Swift：字符串插值
来源：http://dali.kuanghao11.cn/Article/details/gtlwoumazv.html

"值: \(b)"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlwuhhmmq.html

[T19] Swift：可选绑定
来源：http://dali.sysykeji.top/Article/details/gtvlbplvdj.html

if let n = opt { print(n) }
来源：http://dali.dianchejie.cn/Article/details/gthqwlvqfe.html

[T20] Swift：数组操作
来源：http://dali.jinqigfzy.top/Article/details/gtlyfdxlke.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.haohaochexian.top/Article/details/gtyiobwmkj.html

[T21] Swift：遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtewkiwuuk.html

for x in a { print(x) }
来源：http://dali.xuanzx.com/Article/details/gtrnbfjpel.html

[T22] Swift：字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtejwaklqi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.haohaochexian.top/Article/details/gtaajdviiz.html

[T23] Swift：函数
来源：http://dali.sysykeji.top/Article/details/gthwlkfkvu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.0kj1m.cn/Article/details/gtynaldmsv.html

[T24] Swift：闭包
来源：http://dali.cheryme.top/Article/details/gtovilyvvl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yangfankeji.com/Article/details/gtdrhyytic.html

[T25] Swift：结构体
来源：http://dali.aibaodan.cn/Article/details/gttozqdbpn.html

struct P { var x: Int }
来源：http://dali.hnqzz.top/Article/details/gtdogwgrpa.html

[T26] Swift：类与重写
来源：http://dali.yuxming.cn/Article/details/gtsancgfbh.html

class A: Base { override func f() {} }
来源：http://dali.pengpengdd.cyou/Article/details/gtcsjraizm.html

[T27] Swift：错误处理
来源：http://dali.dashuyun.cn/Article/details/gtwabmowlg.html

do { try f() } catch { print(error) }
来源：http://dali.jlsjyb.cn/Article/details/gtapchswoy.html

[T28] Swift：枚举
来源：http://dali.c1oappe.top/Article/details/gtsloxssnw.html

enum Color { case red, green }
来源：http://dali.shangyingyoupin.top/Article/details/gtpmwevvxg.html

[T29] Swift：guard 提前返回
来源：http://dali.nanxinkj.top/Article/details/gtsqgkfaaz.html

guard let x = opt else { return }
来源：http://dali.ehwqpu.com/Article/details/gtswmyviob.html

[T30] Swift：协议
来源：http://dali.havefunace.top/Article/details/gtfidpquiy.html

protocol Shape { func area() -> Double }
来源：http://dali.zhiwuduotai.top/Article/details/gteomjjplc.html

[T31] Lua：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtsvkiyyac.html

print("Hello")
来源：http://dali.nanxinkj.top/Article/details/gtebbcmauh.html

[T32] Lua：局部变量
来源：http://dali.jqgfzy.top/Article/details/gtpduiesik.html

local a = 1
来源：http://dali.haohaochexian.top/Article/details/gtiuhmqvvp.html

[T33] Lua：表（数组）
来源：http://dali.pycfn.com/Article/details/gtjabrlfqz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.aizwys.cn/Article/details/gtodowojsf.html

[T34] Lua：遍历表
来源：http://dali.fengsongda.top/Article/details/gtfnheduzs.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hnqzz.top/Article/details/gtxdfjaudx.html

[T35] Lua：字典表
来源：http://dali.shanyushiyangtech.top/Article/details/gtiezssxuy.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cucudq.cn/Article/details/gtvclrxytz.html

[T36] Lua：函数
来源：http://dali.nanxuanxn.top/Article/details/gtoiafukwv.html

function add(a, b) return a + b end
来源：http://dali.jianghu66.top/Article/details/gtcpewkucm.html

[T37] Lua：字符串拼接
来源：http://dali.zhongyouzk.top/Article/details/gtcjyydgzo.html

"a" .. "b"
来源：http://dali.yuanzhike.top/Article/details/gtlgtuzazk.html

[T38] Lua：条件
来源：http://dali.ivvv.top/Article/details/gtmvdomozm.html

if x > 0 then print("正") end
来源：http://dali.yangfankeji.com/Article/details/gtuoijzvlu.html

[T39] Lua：模式匹配
来源：http://dali.havefunace.top/Article/details/gtgtupgymx.html

string.find(s, "%d+")
来源：http://dali.nwbrower.top/Article/details/gthbcuaqne.html

[T40] Lua：元表
来源：http://dali.dianchejie.cn/Article/details/gttauywrqc.html

setmetatable({}, { __index = base })
来源：http://dali.tian-w.cn/Article/details/gtrfwshtwb.html

[T41] Perl：Hello World
来源：http://dali.yj20258888.top/Article/details/gttgwlrkzh.html

print "Hello\n";
来源：http://dali.yueranfly.top/Article/details/gtytztnmuv.html

[T42] Perl：变量类型
来源：http://dali.yuxming.cn/Article/details/gtdamjasar.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xziqi.cn/Article/details/gtkqzfxukm.html

[T43] Perl：字符串插值
来源：http://dali.jiagoushi.top/Article/details/gtvitcnqur.html

"值: $a"
来源：http://dali.shzxlz.cn/Article/details/gttpbbcent.html

[T44] Perl：条件
来源：http://dali.jqgufenzy.top/Article/details/gtwsssdofk.html

if ($a > 0) { print "正"; }
来源：http://dali.cashguo.top/Article/details/gtyvkwkqyx.html

[T45] Perl：数组遍历
来源：http://dali.ehwqpu.com/Article/details/gtxphwlnqu.html

for my $x (@arr) { print $x; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuvanfxfe.html

[T46] Perl：哈希操作
来源：http://dali.hysaishi.cn/Article/details/gtrbrdvyjy.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.snrcjt.cn/Article/details/gtkootypkq.html

[T47] Perl：正则捕获
来源：http://dali.feifeiyinyue.top/Article/details/gtfjzsiesd.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.ydzc1.top/Article/details/gtucdoxnzf.html

[T48] Perl：正则替换
来源：http://dali.smart0.xyz/Article/details/gtdqbjqpbo.html

$s =~ s/old/new/g;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjlagackb.html

[T49] Perl：函数
来源：http://dali.jqgufenzy.top/Article/details/gtweckfvai.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gtvclgyvyn.html

[T50] Perl：逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gtrggjidsu.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.sxryk.cn/Article/details/gtcmdpvvkz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.chenlongwang.top/Article/details/gtzsrbsnbe.html

[T51] Scala：Hello World
来源：http://dali.cdnleiting.top/Article/details/gtgppsetbn.html

println("Hello")
来源：http://dali.tianlin.xyz/Article/details/gtssljtjrt.html

[T52] Scala：变量
来源：http://dali.svipenyu.cn/Article/details/gtayksgmuj.html

val a = 1;  var b = 2
来源：http://dali.ydzc1.top/Article/details/gteujpkdow.html

[T53] Scala：字符串插值
来源：http://dali.fengsongda.top/Article/details/gtezabdtcn.html

s"值: $b"
来源：http://dali.gaohongyu789.top/Article/details/gtjxkcqkaw.html

[T54] Scala：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gtocgtsnjt.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.meibo888.top/Article/details/gtwrkibxth.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gtkpenwquc.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.iojbl.cn/Article/details/gtkbsudphi.html

[T56] Scala：样例类
来源：http://dali.andypj.xyz/Article/details/gtjpeudklo.html

case class User(name: String, age: Int)
来源：http://dali.gzhubu.top/Article/details/gtijlbvlpl.html

[T57] Scala：模式匹配
来源：http://dali.c1oappe.top/Article/details/gtrdffxnqm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.sysykeji.top/Article/details/gthwylulbr.html

[T58] Scala：函数定义
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrpuotoli.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.sufxvd.cn/Article/details/gthplnxhns.html

[T59] Scala：循环
来源：http://dali.jinqigufen.top/Article/details/gtbpywvzow.html

for (i <- 1 to 10) println(i)
来源：http://dali.hnqzz.top/Article/details/gttupgnvlx.html

[T60] Scala：折叠
来源：http://dali.guowangkeji.top/Article/details/gtpbtudcvu.html


<!-- 参考信息 -->