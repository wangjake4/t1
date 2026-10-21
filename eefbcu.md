代发 wailian999

df -h;  du -sh *
来源：http://dali.jyoumei.cn/Article/details/gtmmnbdpmi.html

[R62] 找最占空间的文件
来源：http://dali.ivvv.top/Article/details/gtllohantm.html

du -ah . | sort -rh | head -10
来源：http://dali.yanxiufei.cn/Article/details/gtfojcqqih.html

[R63] 内存与进程
来源：http://dali.gzhubu.top/Article/details/gtzkglowax.html

free -h;  ps aux | grep nginx
来源：http://dali.yanxiufei.cn/Article/details/gtytpomyxt.html

[R64] 结束进程
来源：http://dali.9152youxi.cn/Article/details/gtymdldwxt.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ydzc1.top/Article/details/gtuuzpwpjn.html

[R65] 查看端口占用
来源：http://dali.hywenlv.cn/Article/details/gtovwkqygm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gttlqslsft.html

[R66] 定时任务
来源：http://dali.xinyue.icu/Article/details/gtffsjiipf.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gtyamqfetx.html

[R67] 生成随机十六进制串
来源：http://dali.yuxming.cn/Article/details/gtasycuptz.html

openssl rand -hex 16
来源：http://dali.316326.xyz/Article/details/gtqxzkchxs.html

[R68] 计算文件校验值
来源：http://dali.ivvv.top/Article/details/gtgsmlqibr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.daxiang520.top/Article/details/gtgfoazllc.html

[R69] 生成随机密码
来源：http://dali.bjfxy.top/Article/details/gtjzrlknxo.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhoulong.xyz/Article/details/gthtcppuar.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gtcsvffjwv.html

date +%s;  date -d @1700000000
来源：http://dali.fengsongda.top/Article/details/gtlrzvvgws.html

[R71] 日期格式化
来源：http://dali.yuxming.cn/Article/details/gtgbcvwpss.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.0kj1m.cn/Article/details/gtstwktchh.html

[R72] 等待端口就绪
来源：http://dali.zhongyouzk.top/Article/details/gtyiakjsep.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cqqwz.cn/Article/details/gtflqftrzs.html

[R73] 分割大日志
来源：http://dali.sufxvd.cn/Article/details/gtpxapckov.html

split -l 1000 big.log part_
来源：http://dali.guannengcc.top/Article/details/gtrvtboowu.html

[R74] 批量重命名
来源：http://dali.jlsjyb.cn/Article/details/gtqvicqjys.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.dashuyun.cn/Article/details/gtdargtbrl.html

[R75] 导出环境变量
来源：http://dali.pycfn.com/Article/details/gtucipdrce.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.pycfn.com/Article/details/gtzexkrvfi.html

[R76] 使用临时文件
来源：http://dali.haohaochexian.top/Article/details/gtapkycnrs.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnqzz.top/Article/details/gtkqkrdjnv.html

[R77] 读取用户输入
来源：http://dali.xuanzx.com/Article/details/gtusvqqnul.html

read -rp "请输入: " ans
来源：http://dali.xylfe.cn/Article/details/gtczksajgv.html

[R78] 交互式菜单
来源：http://dali.cqqwz.cn/Article/details/gtmnpjchzb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jyoumei.cn/Article/details/gtfegrafty.html

[R79] 解析命令行选项
来源：http://dali.shuidangran.top/Article/details/gtykceybza.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jianghu66.top/Article/details/gttldmdjfq.html

[R80] 查看脚本执行耗时
来源：http://dali.birdmap.top/Article/details/gtvxcpcyjr.html

time ./run.sh
来源：http://dali.ppjwa.cn/Article/details/gttpgycetm.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtgjwmzpmq.html

S. C / C++ 专题
来源：http://dali.cheryme.top/Article/details/gtwxrwprjm.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtilqlwuys.html

[S01] C：Hello World
来源：http://dali.wangdashe.top/Article/details/gtkducomrk.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gttxlrknle.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.aizwys.cn/Article/details/gtstzztbqb.html

[S02] C：变量与格式化输出
来源：http://dali.jianghu66.top/Article/details/gttejfaerg.html

int a = 10; printf("%d\n", a);
来源：http://dali.vqdsnc.cn/Article/details/gtkjaygjnw.html

[S03] C：读入整数
来源：http://dali.nwbrower.top/Article/details/gtcsqfktew.html

int x; scanf("%d", &x);
来源：http://dali.jinghuilouyu.cn/Article/details/gtzehctdon.html

[S04] C：字符串复制
来源：http://dali.gzhubu.top/Article/details/gtofmfhkai.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hnqzz.top/Article/details/gtcyussdmy.html

[S05] C：字符串长度
来源：http://dali.nanxinkj.top/Article/details/gtwkdyixwn.html

strlen(s)
来源：http://dali.nwbrower.top/Article/details/gtzdhgpywx.html

[S06] C：字符串比较
来源：http://dali.zhixingplan.top/Article/details/gtfybmiydq.html

strcmp(a, b) == 0
来源：http://dali.guowangkeji.top/Article/details/gtmvkcdvxz.html

[S07] C：数组遍历求和
来源：http://dali.pengpengdd.cyou/Article/details/gtxcvfzvij.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ydzc1.top/Article/details/gtorvxhpaw.html

[S08] C：动态内存分配与释放
来源：http://dali.hammf.cn/Article/details/gtxuomgxyj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.feifeiyinyue.top/Article/details/gtitlxgfiw.html

[S09] C：结构体定义与初始化
来源：http://dali.hfpthk.cn/Article/details/gtnctrybcw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ivvv.top/Article/details/gtyykqqctd.html

[S10] C：指针与解引用
来源：http://dali.wangdashe.top/Article/details/gtqukylovp.html

int *p = &a;  *p = 5;
来源：http://dali.yuxming.cn/Article/details/gtyeglszfe.html

[S11] C：逐行读文件
来源：http://dali.redwolf501.top/Article/details/gtjdteqqhs.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xinyue.icu/Article/details/gtncjolirz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.andypj.xyz/Article/details/gtalrykhkq.html

fclose(f);
来源：http://dali.yonumen.top/Article/details/gtmuunmagr.html

[S12] C：写文件
来源：http://dali.xuanzx.com/Article/details/gtsmokaxqn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.nwbrower.top/Article/details/gtretdhkoy.html

[S13] C：宏定义
来源：http://dali.hywenlv.cn/Article/details/gtvxgfhvvu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yj202588.top/Article/details/gtwoddxkxv.html

[S14] C：枚举
来源：http://dali.yangfankeji.com/Article/details/gtdekjikpp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.meibo888.top/Article/details/gtccfoqfey.html

[S15] C：类型转换
来源：http://dali.gzhubu.top/Article/details/gtinegphta.html

(double) a / b
来源：http://dali.daxiang520.top/Article/details/gtcwxwtupn.html

[S16] C：位操作置位
来源：http://dali.wangdashe.top/Article/details/gtygwmvsxs.html

x |= (1 << 3);
来源：http://dali.yanxiufei.cn/Article/details/gterdesacv.html

[S17] C：安全拼接字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtactnzoyu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwihlhbpv.html

[S18] C：命令行参数
来源：http://dali.hnxiangtu.top/Article/details/gthjfpfizi.html

int main(int argc, char **argv)
来源：http://dali.316326.xyz/Article/details/gtxjtervdq.html

[S19] C：快速排序
来源：http://dali.316326.xyz/Article/details/gtiwjowlju.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.feifeiyinyue.top/Article/details/gtrwcjarmi.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gtgccbsccw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sysykeji.top/Article/details/gtialuzgpq.html

[S21] C：字符类别判断
来源：http://dali.zycfv.cn/Article/details/gtcwgfgefu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ybcxt.top/Article/details/gtnzvszxgr.html

[S22] C：字符串转数字
来源：http://dali.wangshuangyany.cn/Article/details/gtqkowxvla.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sufxvd.cn/Article/details/gtetofdmyh.html

[S23] C：随机数
来源：http://dali.0kj1m.cn/Article/details/gtzxawyeej.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ydzc1.top/Article/details/gtfbfugdzq.html

[S24] C：获取本地时间
来源：http://dali.tianlin.xyz/Article/details/gtguflfyte.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jqgfzy.top/Article/details/gtwpiiyidx.html

[S25] C：内存拷贝
来源：http://dali.ehwqpu.com/Article/details/gtsgpaptfg.html

memcpy(dst, src, n);
来源：http://dali.feifeiyinyue.top/Article/details/gthztagdsd.html

[S26] C：内存清零
来源：http://dali.birdmap.top/Article/details/gtsycsadbi.html

memset(a, 0, sizeof a);
来源：http://dali.gzhubu.top/Article/details/gtvdfajosh.html

[S27] C：定义常量
来源：http://dali.xuanzx.com/Article/details/gtnuyurljp.html

const double PI = 3.14159;
来源：http://dali.sxryk.cn/Article/details/gtbtyagpqo.html

[S28] C：静态变量
来源：http://dali.wangdashe.top/Article/details/gtfzdklqpp.html

static int counter = 0;
来源：http://dali.316326.xyz/Article/details/gtlkbclqrs.html

[S29] C：变参函数
来源：http://dali.fzhhl.top/Article/details/gtrempzofj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jinqigufen.top/Article/details/gthsqudpbh.html

[S30] C：头文件保护
来源：http://dali.cqqwz.cn/Article/details/gttncdvvur.html

#ifndef X_H
来源：http://dali.zycfv.cn/Article/details/gtmokrkrmq.html

#define X_H
来源：http://dali.jqgfzy.top/Article/details/gtqmlnudrb.html

#endif
来源：http://dali.zhengqikj.top/Article/details/gtavedvmcv.html

[S31] C++：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtmysaxegu.html

#include <iostream>
来源：http://dali.cheryme.top/Article/details/gtjxflbrul.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.snrcjt.cn/Article/details/gtnxxnljha.html

[S32] C++：字符串
来源：http://dali.cqqwz.cn/Article/details/gtrxnfvofh.html

std::string s = "hi";  s += "!";
来源：http://dali.zycfv.cn/Article/details/gtapblkvue.html

[S33] C++：vector 增删
来源：http://dali.haohaochexian.top/Article/details/gtzjcqtxxd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cashguo.top/Article/details/gtglsgznlm.html

[S34] C++：遍历 vector
来源：http://dali.yuxming.cn/Article/details/gtakoehhns.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.quarkkingdee.top/Article/details/gtccealnzm.html

[S35] C++：map
来源：http://dali.sxryk.cn/Article/details/gtxdbuobda.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yonumen.top/Article/details/gtjtqhdjhk.html

[S36] C++：unordered_map
来源：http://dali.havefunace.top/Article/details/gtbopmrafr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jianghu66.top/Article/details/gtwalwdnko.html

[S37] C++：set
来源：http://dali.sysykeji.top/Article/details/gtuzbzxbhl.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sysykeji.top/Article/details/gtaecrweqs.html

[S38] C++：排序
来源：http://dali.yueranfly.top/Article/details/gttmtnuhky.html

std::sort(v.begin(), v.end());
来源：http://dali.jyoumei.cn/Article/details/gtqdofdpvp.html

[S39] C++：自定义比较器排序
来源：http://dali.zycfv.cn/Article/details/gtpgcobghd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.316326.xyz/Article/details/gtsggzkztb.html

[S40] C++：查找元素
来源：http://dali.jiagoushi.top/Article/details/gteeejxqte.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpfbujdqj.html

[S41] C++：类与构造函数
来源：http://dali.gaohongyu789.top/Article/details/gtrrpdrgaw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.9152youxi.cn/Article/details/gtcrsamzjd.html

[S42] C++：继承与虚函数
来源：http://dali.yj20258.top/Article/details/gtgmqwmdjz.html

class B : public Base { public: void f() override {} };
来源：http://dali.fengsongda.top/Article/details/gtyuhkwtrf.html

[S43] C++：智能指针
来源：http://dali.dianchejie.cn/Article/details/gtwmbaipak.html

auto p = std::make_unique<int>(5);
来源：http://dali.smart0.xyz/Article/details/gtuudgdzsq.html

[S44] C++：引用传参
来源：http://dali.fengsongda.top/Article/details/gtetoekcbt.html

void inc(int &x) { ++x; }
来源：http://dali.chenzaomai.com/Article/details/gtububbdyy.html

[S45] C++：lambda
来源：http://dali.kuanghao11.cn/Article/details/gtykgcshzj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cashguo.top/Article/details/gtohhxenxh.html

[S46] C++：函数模板
来源：http://dali.nwbrower.top/Article/details/gttvesewar.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.haohaochexian.top/Article/details/gtcldeweon.html

[S47] C++：结构化绑定遍历
来源：http://dali.sysykeji.top/Article/details/gtcrwlcioi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.daria6918.cn/Article/details/gtulldghid.html

[S48] C++：逐行读文件
来源：http://dali.316326.xyz/Article/details/gtkblsqkrx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cashguo.top/Article/details/gtchypkhlw.html

while (std::getline(in, line)) { }
来源：http://dali.gotoacloud.top/Article/details/gttqpqlpcw.html

[S49] C++：写文件
来源：http://dali.hfpthk.cn/Article/details/gtkedebczp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.chenlongwang.top/Article/details/gthcnghjwq.html

[S50] C++：格式化数字
来源：http://dali.yuanzhike.top/Article/details/gtwnuhkjht.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.haohaochexian.top/Article/details/gtorbkidvm.html

[S51] C++：显式类型转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcpvcuool.html

static_cast<double>(a) / b
来源：http://dali.chenlongwang.top/Article/details/gtrychpjvh.html

[S52] C++：const 与 noexcept
来源：http://dali.iojbl.cn/Article/details/gtvacnqttz.html

int size() const noexcept { return n_; }
来源：http://dali.ybcxt.top/Article/details/gtzpfmepay.html

[S53] C++：移动语义
来源：http://dali.hysaishi.cn/Article/details/gtfrowuntp.html

std::vector<int> w = std::move(v);
来源：http://dali.jyoumei.cn/Article/details/gtovjryvpn.html

[S54] C++：异常处理
来源：http://dali.hongshengwenyu.top/Article/details/gtuspvaevq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.daxiang520.top/Article/details/gtmeebqwem.html

[S55] C++：结构化绑定
来源：http://dali.chenzaomai.com/Article/details/gtngnpcejl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.pengpengdd.cyou/Article/details/gtovpaegtu.html

[S56] C++：optional
来源：http://dali.nanxuanxn.top/Article/details/gtmrdjwubh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ydzc1.top/Article/details/gtpbqhwolt.html

[S57] C++：编译期常量
来源：http://dali.hnxiangtu.top/Article/details/gthdjsxmvd.html

constexpr int N = 10;
来源：http://dali.jyoumei.cn/Article/details/gtrvsaijui.html

[S58] C++：命名空间
来源：http://dali.nanxinkj.top/Article/details/gturlmnncq.html

namespace ns { int f() { return 1; } }
来源：http://dali.sufxvd.cn/Article/details/gtmwcpothv.html

[S59] C++：静态断言
来源：http://dali.aibaodan.cn/Article/details/gtbxwtksxj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.fengsongda.top/Article/details/gtlxegavvx.html

[S60] C++：遍历并删除元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvkljntlt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sweek.top/Article/details/gtawumyzax.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtusdzcnfv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shuidangran.top/Article/details/gtmcpzqyds.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtckqwtbnt.html

[T01] Kotlin：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtnuwfalie.html

println("Hello")
来源：http://dali.9152youxi.cn/Article/details/gtkytetqei.html

[T02] Kotlin：变量
来源：http://dali.bjfxy.top/Article/details/gtfsigoxvp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.smart0.xyz/Article/details/gtwvcuyjwr.html

[T03] Kotlin：字符串模板
来源：http://dali.kuanghao11.cn/Article/details/gtuqqpghwo.html

"值: $b"
来源：http://dali.hammf.cn/Article/details/gtynspnvbp.html

[T04] Kotlin：空安全
来源：http://dali.guowangkeji.top/Article/details/gtrctoywxi.html

val n: String? = null;  n?.length
来源：http://dali.aizwys.cn/Article/details/gtfctggthl.html

[T05] Kotlin：when 表达式
来源：http://dali.cheryme.top/Article/details/gtsgbynuaj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gzhubu.top/Article/details/gtdlbfmwdl.html

[T06] Kotlin：集合映射
来源：http://dali.hnqzz.top/Article/details/gtajjbtevw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenlongwang.top/Article/details/gtvascbnhz.html

[T07] Kotlin：集合过滤
来源：http://dali.zycfv.cn/Article/details/gtyuxvhofj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.dianchejie.cn/Article/details/gtmfahjbph.html

[T08] Kotlin：数据类
来源：http://dali.sysykeji.top/Article/details/gtvtdogobg.html

data class User(val name: String, val age: Int)
来源：http://dali.zhoulong.xyz/Article/details/gtstfosjjc.html

[T09] Kotlin：扩展函数
来源：http://dali.shuidangran.top/Article/details/gtbxmicygu.html

fun String.exclaim() = this + "!"
来源：http://dali.hongshengwenyu.top/Article/details/gtlxntoxwz.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gtztoheifr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cheryme.top/Article/details/gtxuhoutwt.html

[T11] Kotlin：协程
来源：http://dali.quarkkingdee.top/Article/details/gtfitajwhd.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hywenlv.cn/Article/details/gtfpkxohac.html

[T12] Kotlin：解构声明
来源：http://dali.xylfe.cn/Article/details/gtyxdwdzxr.html

val (a, b) = Pair(1, 2)
来源：http://dali.yonumen.top/Article/details/gtiijjyfop.html

[T13] Kotlin：只读 Map
来源：http://dali.guowangkeji.top/Article/details/gtqyvhpvrd.html

val m = mapOf("a" to 1)
来源：http://dali.yuxming.cn/Article/details/gtzbekdhxw.html

[T14] Kotlin：循环
来源：http://dali.kuanghao11.cn/Article/details/gtctvzqieo.html

for (i in 1..10) println(i)
来源：http://dali.daxiang520.top/Article/details/gtlagyrgwf.html

[T15] Kotlin：接口
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrhtjhvor.html

interface Shape { fun area(): Double }
来源：http://dali.yvedp.cn/Article/details/gtrarachwo.html

[T16] Swift：Hello World
来源：http://dali.aizwys.cn/Article/details/gtmkdjfkbj.html

print("Hello")
来源：http://dali.316326.xyz/Article/details/gtpckjjafy.html

[T17] Swift：变量与常量
来源：http://dali.fzhhl.top/Article/details/gtojjtyryb.html

var a = 1;  let b = 2
来源：http://dali.xinyue.icu/Article/details/gtpbpyppes.html

[T18] Swift：字符串插值
来源：http://dali.xuanzx.com/Article/details/gtcktpaism.html

"值: \(b)"
来源：http://dali.aibaodan.cn/Article/details/gtthqzjniz.html

[T19] Swift：可选绑定
来源：http://dali.jinqigufen.top/Article/details/gtsgatcfbt.html

if let n = opt { print(n) }
来源：http://dali.ehwqpu.com/Article/details/gtxhfibluy.html

[T20] Swift：数组操作
来源：http://dali.guowangkeji.top/Article/details/gtautxssvb.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.gaohongyu789.top/Article/details/gtbwfxxqiy.html

[T21] Swift：遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtvcovcbvv.html

for x in a { print(x) }
来源：http://dali.jqgufenzy.top/Article/details/gtnxqivewq.html

[T22] Swift：字典
来源：http://dali.yj20258.top/Article/details/gtskaqhyix.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jinqigufen.top/Article/details/gtspbmygdl.html

[T23] Swift：函数
来源：http://dali.fengsongda.top/Article/details/gtdfumjgck.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sweek.top/Article/details/gtdyoixjmv.html

[T24] Swift：闭包
来源：http://dali.aibaodan.cn/Article/details/gtepzsfxab.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.tian-w.cn/Article/details/gtuqwoywbt.html

[T25] Swift：结构体
来源：http://dali.wangshuangyany.cn/Article/details/gtknbcetjf.html

struct P { var x: Int }
来源：http://dali.zhengqikj.top/Article/details/gtqwvqveqg.html

[T26] Swift：类与重写
来源：http://dali.0kj1m.cn/Article/details/gtsuuazjud.html

class A: Base { override func f() {} }
来源：http://dali.feifeiyinyue.top/Article/details/gtxnojgqxr.html

[T27] Swift：错误处理
来源：http://dali.yangfankeji.com/Article/details/gtljzmrrau.html

do { try f() } catch { print(error) }
来源：http://dali.yueranfly.top/Article/details/gtypjqqvwk.html

[T28] Swift：枚举
来源：http://dali.dashuyun.cn/Article/details/gtteppqkcq.html

enum Color { case red, green }
来源：http://dali.sufxvd.cn/Article/details/gtfkdwduem.html

[T29] Swift：guard 提前返回
来源：http://dali.yongpay.top/Article/details/gtnrajjimh.html

guard let x = opt else { return }
来源：http://dali.fzhhl.top/Article/details/gtrvbdaulg.html

[T30] Swift：协议
来源：http://dali.chenzaomai.com/Article/details/gtdrcseyef.html

protocol Shape { func area() -> Double }
来源：http://dali.yj20258888.top/Article/details/gtcpejzuyg.html

[T31] Lua：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtthmbwqop.html

print("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwfltbszh.html

[T32] Lua：局部变量
来源：http://dali.xziqi.cn/Article/details/gtzpwxotob.html

local a = 1
来源：http://dali.meibo888.top/Article/details/gtqywmraam.html

[T33] Lua：表（数组）
来源：http://dali.hfpthk.cn/Article/details/gtsmfutxda.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yueranfly.top/Article/details/gtkezueeog.html

[T34] Lua：遍历表
来源：http://dali.tianlin.xyz/Article/details/gtyhzsxolc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvqewpuaa.html

[T35] Lua：字典表
来源：http://dali.ydzc1.top/Article/details/gtnpgqoqrn.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yangfankeji.com/Article/details/gtqfygonkm.html

[T36] Lua：函数
来源：http://dali.pycfn.com/Article/details/gtywmtdktj.html

function add(a, b) return a + b end
来源：http://dali.fzhhl.top/Article/details/gtkypmmbms.html

[T37] Lua：字符串拼接
来源：http://dali.cashguo.top/Article/details/gtplhbvkin.html

"a" .. "b"
来源：http://dali.xuanzx.com/Article/details/gtkrhtbnxv.html

[T38] Lua：条件
来源：http://dali.tanke756.top/Article/details/gtmxoopibl.html

if x > 0 then print("正") end
来源：http://dali.mhx1999.top/Article/details/gtllyyrwwn.html

[T39] Lua：模式匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtynsfknhr.html

string.find(s, "%d+")
来源：http://dali.jyoumei.cn/Article/details/gthxcddctj.html

[T40] Lua：元表
来源：http://dali.cashguo.top/Article/details/gthlybfbsp.html

setmetatable({}, { __index = base })
来源：http://dali.fengsongda.top/Article/details/gtxmivbcxc.html

[T41] Perl：Hello World
来源：http://dali.tanke756.top/Article/details/gtajjrkxgc.html

print "Hello\n";
来源：http://dali.shuidangran.top/Article/details/gtvdfqkvif.html

[T42] Perl：变量类型
来源：http://dali.sufxvd.cn/Article/details/gtvcynvths.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xylfe.cn/Article/details/gtsfzexpuc.html

[T43] Perl：字符串插值
来源：http://dali.zhixingplan.top/Article/details/gtfankyktv.html

"值: $a"
来源：http://dali.316326.xyz/Article/details/gtkaxolvqe.html

[T44] Perl：条件
来源：http://dali.pengpengdd.cyou/Article/details/gtyoxmrdsh.html

if ($a > 0) { print "正"; }
来源：http://dali.havefunace.top/Article/details/gtocccnogc.html

[T45] Perl：数组遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gthxslvwuc.html

for my $x (@arr) { print $x; }
来源：http://dali.ybcxt.top/Article/details/gtipcyidxw.html

[T46] Perl：哈希操作
来源：http://dali.bjfxy.top/Article/details/gtgtminpym.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ydzc1.top/Article/details/gtgcpjegrk.html

[T47] Perl：正则捕获
来源：http://dali.shuidangran.top/Article/details/gtwsdoipnv.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yj20258888.top/Article/details/gtffdtsvux.html

[T48] Perl：正则替换
来源：http://dali.haohaochexian.top/Article/details/gtpccxmuta.html

$s =~ s/old/new/g;
来源：http://dali.xuanzx.com/Article/details/gtjjrifyxo.html

[T49] Perl：函数
来源：http://dali.iojbl.cn/Article/details/gtvtosmhhh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zhiwuduotai.top/Article/details/gtvehgbazh.html

[T50] Perl：逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gtnviwkymv.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hysaishi.cn/Article/details/gtlaclumoy.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yongpay.top/Article/details/gtyypuuaaj.html

[T51] Scala：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtxksondtd.html

println("Hello")
来源：http://dali.yj20258.top/Article/details/gtpugrrpwx.html

[T52] Scala：变量
来源：http://dali.yueranfly.top/Article/details/gtcetfbvwi.html

val a = 1;  var b = 2
来源：http://dali.hongshengwenyu.top/Article/details/gtwsiacckk.html

[T53] Scala：字符串插值
来源：http://dali.haohaochexian.top/Article/details/gtkwovmrna.html

s"值: $b"
来源：http://dali.yj202588.top/Article/details/gtgvltvarb.html

[T54] Scala：集合映射
来源：http://dali.guowangkeji.top/Article/details/gtlgogmwox.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yongpay.top/Article/details/gtaecmwwoh.html

[T55] Scala：集合过滤
来源：http://dali.jinqigfzy.top/Article/details/gtuulrybrd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.gaohongyu789.top/Article/details/gtgghljzqr.html

[T56] Scala：样例类
来源：http://dali.daria6918.cn/Article/details/gttykebdmj.html

case class User(name: String, age: Int)
来源：http://dali.xuetiantiany.cn/Article/details/gtxmpsxyct.html

[T57] Scala：模式匹配
来源：http://dali.chenzaomai.com/Article/details/gtpbzmfrqa.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yangfankeji.com/Article/details/gthghaqvdj.html

[T58] Scala：函数定义
来源：http://dali.haohaochexian.top/Article/details/gtorlgezsz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.vqdsnc.cn/Article/details/gtxhvcrglo.html

[T59] Scala：循环
来源：http://dali.zhiwuduotai.top/Article/details/gttfxjusbf.html

for (i <- 1 to 10) println(i)
来源：http://dali.bjfxy.top/Article/details/gtzawffmcd.html

[T60] Scala：折叠
来源：http://dali.hongshengwenyu.top/Article/details/gtujjfbnzc.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.tianlin.xyz/Article/details/gteozbfhvi.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gtqacwohnm.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.hammf.cn/Article/details/gtflkurqbr.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtgtrjiqbl.html

[U01] Py：创建虚拟环境
来源：http://dali.feifeiyinyue.top/Article/details/gtkcclrwts.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yj20258888.top/Article/details/gtchynuxue.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jyoumei.cn/Article/details/gtjolztlsn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yuanzhike.top/Article/details/gtpxuhxblo.html


<!-- 参考信息 -->