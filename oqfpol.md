代发 wailian999

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhoulong.xyz/Article/details/gtpshilims.html

[R56] 远程拷贝
来源：http://dali.sxryk.cn/Article/details/gtrqlxiodb.html

scp file user@host:/path/
来源：http://dali.ydzc1.top/Article/details/gtrimgwjmn.html

[R57] 远程执行命令
来源：http://dali.chenzaomai.com/Article/details/gtfkcgohqx.html

ssh user@host 'uptime'
来源：http://dali.dianchejie.cn/Article/details/gtlrqjaoyi.html

[R58] 下载文件
来源：http://dali.hysaishi.cn/Article/details/gtqotiynit.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ydzc1.top/Article/details/gtpzsyozkm.html

[R59] 发 POST JSON
来源：http://dali.havefunace.top/Article/details/gtgkhwgmks.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yonumen.top/Article/details/gtmmdfwylg.html

[R60] 只看 HTTP 状态码
来源：http://dali.havefunace.top/Article/details/gtgsebofyj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cucudq.cn/Article/details/gtceenytty.html

[R61] 磁盘占用
来源：http://dali.cheryme.top/Article/details/gtyynruofq.html

df -h;  du -sh *
来源：http://dali.gaohongyu789.top/Article/details/gtouohzypz.html

[R62] 找最占空间的文件
来源：http://dali.pengpengdd.cyou/Article/details/gtbvyyqxrl.html

du -ah . | sort -rh | head -10
来源：http://dali.yuxming.cn/Article/details/gtzojsepzs.html

[R63] 内存与进程
来源：http://dali.zhongyouzk.top/Article/details/gtqgbfgfep.html

free -h;  ps aux | grep nginx
来源：http://dali.yueranfly.top/Article/details/gtolpgyulg.html

[R64] 结束进程
来源：http://dali.havefunace.top/Article/details/gtrjpudkvy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shuidangran.top/Article/details/gtbqbghuun.html

[R65] 查看端口占用
来源：http://dali.shzxlz.cn/Article/details/gtjubxikgu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gaohongyu789.top/Article/details/gtqabzalys.html

[R66] 定时任务
来源：http://dali.zhoulong.xyz/Article/details/gtrjwzlplv.html

crontab -e;  crontab -l
来源：http://dali.ivvv.top/Article/details/gtijdiywue.html

[R67] 生成随机十六进制串
来源：http://dali.hnxiangtu.top/Article/details/gtnnernjcz.html

openssl rand -hex 16
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfodcjutd.html

[R68] 计算文件校验值
来源：http://dali.sysykeji.top/Article/details/gtntqwgqjq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cashguo.top/Article/details/gtvcirihzd.html

[R69] 生成随机密码
来源：http://dali.wangshuangyany.cn/Article/details/gtxwvyrhgv.html

head -c 16 /dev/urandom | base64
来源：http://dali.bjfxy.top/Article/details/gtkzlzcouz.html

[R70] 时间戳与互转
来源：http://dali.aibaodan.cn/Article/details/gtrmlazscp.html

date +%s;  date -d @1700000000
来源：http://dali.tian-w.cn/Article/details/gtatooofjo.html

[R71] 日期格式化
来源：http://dali.ivvv.top/Article/details/gtahjbfivb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ydzc1.top/Article/details/gthbsduugc.html

[R72] 等待端口就绪
来源：http://dali.jinghuilouyu.cn/Article/details/gtvhgwaopj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj20258.top/Article/details/gtkzchfqaa.html

[R73] 分割大日志
来源：http://dali.hnqzz.top/Article/details/gtcjxzfawx.html

split -l 1000 big.log part_
来源：http://dali.zhengqikj.top/Article/details/gtunfemzra.html

[R74] 批量重命名
来源：http://dali.sysykeji.top/Article/details/gtuwuixdnj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.meibo888.top/Article/details/gtfhszziat.html

[R75] 导出环境变量
来源：http://dali.daxiang520.top/Article/details/gtqrttfyiy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jqgfzy.top/Article/details/gtbyycsjos.html

[R76] 使用临时文件
来源：http://dali.daria6918.cn/Article/details/gticqtswuq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cqqwz.cn/Article/details/gttloeuzac.html

[R77] 读取用户输入
来源：http://dali.tianlin.xyz/Article/details/gtkikenjel.html

read -rp "请输入: " ans
来源：http://dali.jiagoushi.top/Article/details/gtfvpwfkga.html

[R78] 交互式菜单
来源：http://dali.dianchejie.cn/Article/details/gtjpptdbvt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hnxiangtu.top/Article/details/gtmnwzgzkj.html

[R79] 解析命令行选项
来源：http://dali.jinqigfzy.top/Article/details/gthsfqcjvz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sxryk.cn/Article/details/gtxayayoyi.html

[R80] 查看脚本执行耗时
来源：http://dali.sufxvd.cn/Article/details/gtfhuvgmht.html

time ./run.sh
来源：http://dali.gotoacloud.top/Article/details/gtcsyulexw.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtocsvoqcx.html

S. C / C++ 专题
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkkdbqtyt.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtlpqlepyl.html

[S01] C：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtlxafpvpn.html

#include <stdio.h>
来源：http://dali.jyoumei.cn/Article/details/gttawrmiel.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xziqi.cn/Article/details/gtfbwhwsfk.html

[S02] C：变量与格式化输出
来源：http://dali.jqgufenzy.top/Article/details/gttephkhmc.html

int a = 10; printf("%d\n", a);
来源：http://dali.zycfv.cn/Article/details/gtbcbvatqi.html

[S03] C：读入整数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqyiowjxe.html

int x; scanf("%d", &x);
来源：http://dali.feifeiyinyue.top/Article/details/gtemaoxwzv.html

[S04] C：字符串复制
来源：http://dali.jlsjyb.cn/Article/details/gtpprdnpnl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gzhubu.top/Article/details/gtfbplqgwl.html

[S05] C：字符串长度
来源：http://dali.ivvv.top/Article/details/gthpwnqotr.html

strlen(s)
来源：http://dali.hammf.cn/Article/details/gtknjombgr.html

[S06] C：字符串比较
来源：http://dali.zycfv.cn/Article/details/gtaojlnbyy.html

strcmp(a, b) == 0
来源：http://dali.yangfankeji.com/Article/details/gtesokatgk.html

[S07] C：数组遍历求和
来源：http://dali.c1oappe.top/Article/details/gtvglwxztg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhixingplan.top/Article/details/gtcvupywif.html

[S08] C：动态内存分配与释放
来源：http://dali.tianlin.xyz/Article/details/gtdgtlrkiw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cdnleiting.top/Article/details/gtdtmkrwme.html

[S09] C：结构体定义与初始化
来源：http://dali.shangyingyoupin.top/Article/details/gtbeehtwfn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.316326.xyz/Article/details/gtipvgtoty.html

[S10] C：指针与解引用
来源：http://dali.gogol.net.cn/Article/details/gtrtvayahn.html

int *p = &a;  *p = 5;
来源：http://dali.bjfxy.top/Article/details/gtfusgiten.html

[S11] C：逐行读文件
来源：http://dali.xinyue.icu/Article/details/gtxwshfube.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.dashuyun.cn/Article/details/gtqlayxjsn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.guowangkeji.top/Article/details/gtkgmigymf.html

fclose(f);
来源：http://dali.chenzaomai.com/Article/details/gtetmhtdvp.html

[S12] C：写文件
来源：http://dali.hnxiangtu.top/Article/details/gtqjnvjojc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmmuhdrve.html

[S13] C：宏定义
来源：http://dali.dashuyun.cn/Article/details/gtvsnvpmks.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinghuilouyu.cn/Article/details/gtnaxdxjfp.html

[S14] C：枚举
来源：http://dali.smart0.xyz/Article/details/gtnsiklflq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zycfv.cn/Article/details/gtjiinscqf.html

[S15] C：类型转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuanrtbal.html

(double) a / b
来源：http://dali.fzhhl.top/Article/details/gtzcdwvgkf.html

[S16] C：位操作置位
来源：http://dali.yonumen.top/Article/details/gtiwyqlgro.html

x |= (1 << 3);
来源：http://dali.smart0.xyz/Article/details/gtjmxudmkz.html

[S17] C：安全拼接字符串
来源：http://dali.haohaochexian.top/Article/details/gtzyypszcu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xylfe.cn/Article/details/gthzxikfqi.html

[S18] C：命令行参数
来源：http://dali.bjfxy.top/Article/details/gtnernhyui.html

int main(int argc, char **argv)
来源：http://dali.shuidangran.top/Article/details/gtjxtvspdz.html

[S19] C：快速排序
来源：http://dali.tian-w.cn/Article/details/gtdfodmggg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.smart0.xyz/Article/details/gtvqvcyhgj.html

[S20] C：二分查找
来源：http://dali.meibo888.top/Article/details/gtbdhqzlrh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.havefunace.top/Article/details/gtzlnyegqz.html

[S21] C：字符类别判断
来源：http://dali.pengpengdd.cyou/Article/details/gthrdkhggc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.aibaodan.cn/Article/details/gtzuhsoprv.html

[S22] C：字符串转数字
来源：http://dali.kuanghao11.cn/Article/details/gtqddmlrqt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cqqwz.cn/Article/details/gtnxouwgls.html

[S23] C：随机数
来源：http://dali.pycfn.com/Article/details/gtlluxdzfv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sxryk.cn/Article/details/gtgwqydccs.html

[S24] C：获取本地时间
来源：http://dali.yvedp.cn/Article/details/gtyexwairj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cdnleiting.top/Article/details/gttoohcarw.html

[S25] C：内存拷贝
来源：http://dali.dianchejie.cn/Article/details/gtjzpnijsf.html

memcpy(dst, src, n);
来源：http://dali.aibaodan.cn/Article/details/gtceeqkblr.html

[S26] C：内存清零
来源：http://dali.dashuyun.cn/Article/details/gtcafvazrt.html

memset(a, 0, sizeof a);
来源：http://dali.tanke756.top/Article/details/gtmntlupdg.html

[S27] C：定义常量
来源：http://dali.guannengcc.top/Article/details/gtwcthzcrx.html

const double PI = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gthajkrpkg.html

[S28] C：静态变量
来源：http://dali.daxiang520.top/Article/details/gtdjudgdiw.html

static int counter = 0;
来源：http://dali.yj20258.top/Article/details/gtclwqcnqf.html

[S29] C：变参函数
来源：http://dali.chenzaomai.com/Article/details/gtefgxvuar.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhixingplan.top/Article/details/gtxifhmgvx.html

[S30] C：头文件保护
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzkwrwntd.html

#ifndef X_H
来源：http://dali.ehwqpu.com/Article/details/gthawuvesp.html

#define X_H
来源：http://dali.bjfxy.top/Article/details/gtejtzpikd.html

#endif
来源：http://dali.smart0.xyz/Article/details/gtpizrfcvq.html

[S31] C++：Hello World
来源：http://dali.yj20258888.top/Article/details/gtfzdoynxv.html

#include <iostream>
来源：http://dali.havefunace.top/Article/details/gtalpfcjya.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shzxlz.cn/Article/details/gtwasmhwhs.html

[S32] C++：字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtpkrcukrm.html

std::string s = "hi";  s += "!";
来源：http://dali.cdnleiting.top/Article/details/gtfmchcrne.html

[S33] C++：vector 增删
来源：http://dali.jqgufenzy.top/Article/details/gtjryvbnul.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.c1oappe.top/Article/details/gtlybllofz.html

[S34] C++：遍历 vector
来源：http://dali.zhoulong.xyz/Article/details/gtezxrdrae.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.havefunace.top/Article/details/gtyzqohfwb.html

[S35] C++：map
来源：http://dali.zycfv.cn/Article/details/gtjqatmfcv.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtorvblfag.html

[S36] C++：unordered_map
来源：http://dali.feifeiyinyue.top/Article/details/gtsavycmcl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guannengcc.top/Article/details/gtujdpuxam.html

[S37] C++：set
来源：http://dali.jqgufenzy.top/Article/details/gtaxmxkzwf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hnqzz.top/Article/details/gtxfakfslu.html

[S38] C++：排序
来源：http://dali.ehwqpu.com/Article/details/gtlvvkcnnq.html

std::sort(v.begin(), v.end());
来源：http://dali.chenlongwang.top/Article/details/gtcsmpbzwy.html

[S39] C++：自定义比较器排序
来源：http://dali.sxryk.cn/Article/details/gtcvlrfayg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cheryme.top/Article/details/gtfvaceaqm.html

[S40] C++：查找元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpbzawibl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zdqjudy.top/Article/details/gtmzfjlynv.html

[S41] C++：类与构造函数
来源：http://dali.zycfv.cn/Article/details/gtktveodfr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shzxlz.cn/Article/details/gtoivtzruy.html

[S42] C++：继承与虚函数
来源：http://dali.hywenlv.cn/Article/details/gtjcwxloha.html

class B : public Base { public: void f() override {} };
来源：http://dali.daxiang520.top/Article/details/gtwmgtawfa.html

[S43] C++：智能指针
来源：http://dali.jqgfzy.top/Article/details/gtehsrlfww.html

auto p = std::make_unique<int>(5);
来源：http://dali.dashuyun.cn/Article/details/gtfxxrbnia.html

[S44] C++：引用传参
来源：http://dali.yj20258.top/Article/details/gttrgeswkj.html

void inc(int &x) { ++x; }
来源：http://dali.birdmap.top/Article/details/gtwbacsobl.html

[S45] C++：lambda
来源：http://dali.zhijiandao.cn/Article/details/gttpfkvpuw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.feifeiyinyue.top/Article/details/gtdfanqobw.html

[S46] C++：函数模板
来源：http://dali.shanyushiyangtech.top/Article/details/gtoybqwxgw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.316326.xyz/Article/details/gtuceqepkd.html

[S47] C++：结构化绑定遍历
来源：http://dali.tanke756.top/Article/details/gtykutfejw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sweek.top/Article/details/gtpzzcvbmy.html

[S48] C++：逐行读文件
来源：http://dali.smart0.xyz/Article/details/gtuuuislgv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shanyushiyangtech.top/Article/details/gtuhpusqef.html

while (std::getline(in, line)) { }
来源：http://dali.tanke756.top/Article/details/gtyzeqdsqk.html

[S49] C++：写文件
来源：http://dali.nwbrower.top/Article/details/gttkrzsvxw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.meibo888.top/Article/details/gtviwrfugr.html

[S50] C++：格式化数字
来源：http://dali.jiagoushi.top/Article/details/gtughrfhck.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.fengsongda.top/Article/details/gtlnsbnbhr.html

[S51] C++：显式类型转换
来源：http://dali.sweek.top/Article/details/gthkrmfgmo.html

static_cast<double>(a) / b
来源：http://dali.nanxinkj.top/Article/details/gtavytehpj.html

[S52] C++：const 与 noexcept
来源：http://dali.gaohongyu789.top/Article/details/gtegtgrfgp.html

int size() const noexcept { return n_; }
来源：http://dali.zycfv.cn/Article/details/gtojypxpqe.html

[S53] C++：移动语义
来源：http://dali.hysaishi.cn/Article/details/gthnugrxdw.html

std::vector<int> w = std::move(v);
来源：http://dali.chenjidiqi.icu/Article/details/gtcazbedrq.html

[S54] C++：异常处理
来源：http://dali.hongshengwenyu.top/Article/details/gtpuhdvwrv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sufxvd.cn/Article/details/gtdwfrfied.html

[S55] C++：结构化绑定
来源：http://dali.cashguo.top/Article/details/gtnmyeucxr.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hfpthk.cn/Article/details/gtfcvrwzkn.html

[S56] C++：optional
来源：http://dali.zhongyouzk.top/Article/details/gtrrhdzqvc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yueranfly.top/Article/details/gtsjrkfwua.html

[S57] C++：编译期常量
来源：http://dali.fengsongda.top/Article/details/gtbzehedvg.html

constexpr int N = 10;
来源：http://dali.snrcjt.cn/Article/details/gtwijryrdy.html

[S58] C++：命名空间
来源：http://dali.yanxiufei.cn/Article/details/gtzujrkgti.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhoulong.xyz/Article/details/gtkkrdiidj.html

[S59] C++：静态断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpjtlcjow.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.fengsongda.top/Article/details/gtoobpozpi.html

[S60] C++：遍历并删除元素
来源：http://dali.zhiwuduotai.top/Article/details/gtijdeespm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.nanxinkj.top/Article/details/gtretatxjg.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtcpxduwqt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.kuanghao11.cn/Article/details/gtdlwythqt.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtclfewsfj.html

[T01] Kotlin：Hello World
来源：http://dali.shuidangran.top/Article/details/gtrgewvswl.html

println("Hello")
来源：http://dali.fengsongda.top/Article/details/gtgelctxwe.html

[T02] Kotlin：变量
来源：http://dali.redwolf501.top/Article/details/gtnohswriv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yangfankeji.com/Article/details/gtiweqlnna.html

[T03] Kotlin：字符串模板
来源：http://dali.chenzaomai.com/Article/details/gtljaujxwl.html

"值: $b"
来源：http://dali.zhiwuduotai.top/Article/details/gtdxzjvmgk.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gtwujgzfcb.html

val n: String? = null;  n?.length
来源：http://dali.quarkkingdee.top/Article/details/gtmeksowdv.html

[T05] Kotlin：when 表达式
来源：http://dali.shuidangran.top/Article/details/gtswcjplsv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.meibo888.top/Article/details/gtzxrmylcq.html

[T06] Kotlin：集合映射
来源：http://dali.hnqzz.top/Article/details/gtftxqmqhm.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.kuanghao11.cn/Article/details/gthwyexfoy.html

[T07] Kotlin：集合过滤
来源：http://dali.316326.xyz/Article/details/gtjjsvrxtz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yueranfly.top/Article/details/gttdcrotuj.html

[T08] Kotlin：数据类
来源：http://dali.zhoulong.xyz/Article/details/gtkvicakod.html

data class User(val name: String, val age: Int)
来源：http://dali.fzhhl.top/Article/details/gtvbjnmdrs.html

[T09] Kotlin：扩展函数
来源：http://dali.andypj.xyz/Article/details/gtgllsiydp.html

fun String.exclaim() = this + "!"
来源：http://dali.yj20258.top/Article/details/gtfzdhzlqc.html

[T10] Kotlin：默认参数
来源：http://dali.shangyingyoupin.top/Article/details/gtrspvkftq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.nanxuanxn.top/Article/details/gtsxzqwupg.html

[T11] Kotlin：协程
来源：http://dali.hywenlv.cn/Article/details/gteiurxujs.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xziqi.cn/Article/details/gtilhjwfsr.html

[T12] Kotlin：解构声明
来源：http://dali.quarkkingdee.top/Article/details/gtjovdzfmb.html

val (a, b) = Pair(1, 2)
来源：http://dali.guannengcc.top/Article/details/gtvohvlfhg.html

[T13] Kotlin：只读 Map
来源：http://dali.jiagoushi.top/Article/details/gtmfjgdkiw.html

val m = mapOf("a" to 1)
来源：http://dali.hammf.cn/Article/details/gtbedvwxuj.html

[T14] Kotlin：循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsaljpmjh.html

for (i in 1..10) println(i)
来源：http://dali.ivvv.top/Article/details/gtdoodqqzz.html

[T15] Kotlin：接口
来源：http://dali.yongpay.top/Article/details/gtpkwtksdi.html

interface Shape { fun area(): Double }
来源：http://dali.meibo888.top/Article/details/gtkraskoik.html

[T16] Swift：Hello World
来源：http://dali.hammf.cn/Article/details/gtktbvfhwh.html

print("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gtktuujvdt.html

[T17] Swift：变量与常量
来源：http://dali.hammf.cn/Article/details/gtbjgdwzfj.html

var a = 1;  let b = 2
来源：http://dali.nwbrower.top/Article/details/gtlxbvqcbl.html

[T18] Swift：字符串插值
来源：http://dali.gogol.net.cn/Article/details/gtmhsaessm.html

"值: \(b)"
来源：http://dali.jianghu66.top/Article/details/gtsylomltw.html

[T19] Swift：可选绑定
来源：http://dali.pycfn.com/Article/details/gtmbhpmzuq.html

if let n = opt { print(n) }
来源：http://dali.aizwys.cn/Article/details/gtmwymjpxs.html

[T20] Swift：数组操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkahoejwi.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zycfv.cn/Article/details/gtkualttcm.html

[T21] Swift：遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gttqturnsy.html

for x in a { print(x) }
来源：http://dali.yangfankeji.com/Article/details/gtgpnktktm.html

[T22] Swift：字典
来源：http://dali.sxryk.cn/Article/details/gtetcbhnff.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhengqikj.top/Article/details/gtbueywkgz.html

[T23] Swift：函数
来源：http://dali.hammf.cn/Article/details/gtfcduqdvm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.guannengcc.top/Article/details/gtupdegpmn.html

[T24] Swift：闭包
来源：http://dali.mhx1999.top/Article/details/gtwqgaxlwy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hnxiangtu.top/Article/details/gtdxumftqg.html

[T25] Swift：结构体
来源：http://dali.jinqigfzy.top/Article/details/gttlhtgpfp.html

struct P { var x: Int }
来源：http://dali.nwbrower.top/Article/details/gtvzpzecmk.html

[T26] Swift：类与重写
来源：http://dali.sxryk.cn/Article/details/gtevcilguq.html

class A: Base { override func f() {} }
来源：http://dali.yueranfly.top/Article/details/gtzlfvcsbp.html

[T27] Swift：错误处理
来源：http://dali.shzxlz.cn/Article/details/gtnilbypev.html

do { try f() } catch { print(error) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvyhhtzdk.html

[T28] Swift：枚举
来源：http://dali.cdnleiting.top/Article/details/gtcowlflrj.html

enum Color { case red, green }
来源：http://dali.yangfankeji.com/Article/details/gtquloytoc.html

[T29] Swift：guard 提前返回
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmdbmosoo.html

guard let x = opt else { return }
来源：http://dali.zdqjudy.top/Article/details/gtyqzuwfzs.html

[T30] Swift：协议
来源：http://dali.sweek.top/Article/details/gtbdzeodue.html

protocol Shape { func area() -> Double }
来源：http://dali.andypj.xyz/Article/details/gtnokxmjsp.html

[T31] Lua：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtfgxegmgy.html

print("Hello")
来源：http://dali.bjfxy.top/Article/details/gtndhbqerk.html

[T32] Lua：局部变量
来源：http://dali.hammf.cn/Article/details/gtygofcffs.html

local a = 1
来源：http://dali.zhengqikj.top/Article/details/gtuxzouctr.html

[T33] Lua：表（数组）
来源：http://dali.jqgufenzy.top/Article/details/gtvvmorjfy.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yangfankeji.com/Article/details/gthgyvvnuo.html

[T34] Lua：遍历表
来源：http://dali.xuanzx.com/Article/details/gtrioaqstj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ehwqpu.com/Article/details/gtsqjwuwke.html

[T35] Lua：字典表
来源：http://dali.sweek.top/Article/details/gtnuyibgai.html

local d = { a = 1 };  d.b = 2
来源：http://dali.bjfxy.top/Article/details/gtujekcsuk.html

[T36] Lua：函数
来源：http://dali.hysaishi.cn/Article/details/gtfabgbnhl.html

function add(a, b) return a + b end
来源：http://dali.sweek.top/Article/details/gteffvidck.html

[T37] Lua：字符串拼接
来源：http://dali.yvedp.cn/Article/details/gtcxbydegy.html

"a" .. "b"
来源：http://dali.hnqzz.top/Article/details/gtprkxayde.html

[T38] Lua：条件
来源：http://dali.hfpthk.cn/Article/details/gtadvrmdhi.html

if x > 0 then print("正") end
来源：http://dali.chenzaomai.com/Article/details/gtcnsogutd.html

[T39] Lua：模式匹配
来源：http://dali.xylfe.cn/Article/details/gtnkkgmitk.html

string.find(s, "%d+")
来源：http://dali.guowangkeji.top/Article/details/gtwlvvtnyi.html

[T40] Lua：元表
来源：http://dali.cqqwz.cn/Article/details/gtycmhfley.html

setmetatable({}, { __index = base })
来源：http://dali.ehwqpu.com/Article/details/gtlnlchldp.html

[T41] Perl：Hello World
来源：http://dali.shuidangran.top/Article/details/gtqdwrgfxc.html

print "Hello\n";
来源：http://dali.zhengqikj.top/Article/details/gtwfeuqeyu.html

[T42] Perl：变量类型
来源：http://dali.jqgfzy.top/Article/details/gtqbixrjuj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.dashuyun.cn/Article/details/gtrkjxnuuc.html

[T43] Perl：字符串插值
来源：http://dali.xuetiantiany.cn/Article/details/gtefrckwlh.html

"值: $a"
来源：http://dali.sxryk.cn/Article/details/gttelefgyf.html

[T44] Perl：条件
来源：http://dali.andypj.xyz/Article/details/gtoovlvcch.html

if ($a > 0) { print "正"; }
来源：http://dali.nwbrower.top/Article/details/gtzdtcrobo.html

[T45] Perl：数组遍历
来源：http://dali.cqqwz.cn/Article/details/gtsxufvclg.html

for my $x (@arr) { print $x; }
来源：http://dali.316326.xyz/Article/details/gtgxycdnpo.html

[T46] Perl：哈希操作
来源：http://dali.dashuyun.cn/Article/details/gtphqaefzn.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hnqzz.top/Article/details/gtbcxaljxe.html

[T47] Perl：正则捕获
来源：http://dali.jianghu66.top/Article/details/gtkdulnitm.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.tanke756.top/Article/details/gtouqlkpcj.html

[T48] Perl：正则替换
来源：http://dali.9152youxi.cn/Article/details/gtxxltojpj.html

$s =~ s/old/new/g;
来源：http://dali.hywenlv.cn/Article/details/gtefqnukqy.html

[T49] Perl：函数
来源：http://dali.hnqzz.top/Article/details/gtlugfkskl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.c1oappe.top/Article/details/gtpskyxaob.html

[T50] Perl：逐行读文件
来源：http://dali.xylfe.cn/Article/details/gtyxnozeuo.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hnqzz.top/Article/details/gtitigwkko.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jinqigfzy.top/Article/details/gtykdgseem.html

[T51] Scala：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtnuznzbyr.html

println("Hello")
来源：http://dali.cucudq.cn/Article/details/gtfayojbrj.html

[T52] Scala：变量
来源：http://dali.quarkkingdee.top/Article/details/gttvbvwhgu.html

val a = 1;  var b = 2
来源：http://dali.yvedp.cn/Article/details/gttfcjqfem.html

[T53] Scala：字符串插值
来源：http://dali.daria6918.cn/Article/details/gtqmdlbafs.html

s"值: $b"
来源：http://dali.jyoumei.cn/Article/details/gtlencwssm.html

[T54] Scala：集合映射
来源：http://dali.kuanghao11.cn/Article/details/gtqtnicmhi.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.tianlin.xyz/Article/details/gtwardvplh.html

[T55] Scala：集合过滤
来源：http://dali.chenlongwang.top/Article/details/gtqcpuutht.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hnxiangtu.top/Article/details/gtoyvxjbyx.html

[T56] Scala：样例类
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmbmaxyuk.html

case class User(name: String, age: Int)
来源：http://dali.dianchejie.cn/Article/details/gtowkvztcf.html

[T57] Scala：模式匹配
来源：http://dali.chenlongwang.top/Article/details/gtvwuyiyhw.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.zhoulong.xyz/Article/details/gtbeysilmw.html

[T58] Scala：函数定义
来源：http://dali.cheryme.top/Article/details/gtkbhfcjdb.html


<!-- 参考信息 -->