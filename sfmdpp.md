代发 wailian999

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yuanzhike.top/Article/details/gtbfgrvskw.html

[R52] 统计行数
来源：http://dali.gzhubu.top/Article/details/gtdillrxqq.html

wc -l a.txt
来源：http://dali.guowangkeji.top/Article/details/gtjfmzuopf.html

[R53] 查看文件头与实时尾
来源：http://dali.vqdsnc.cn/Article/details/gtgwsqinol.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.pycfn.com/Article/details/gtechenzdm.html

[R54] 比较两个文件
来源：http://dali.tianlin.xyz/Article/details/gtkkddoxgc.html

diff a.txt b.txt
来源：http://dali.jyoumei.cn/Article/details/gthkjkhzvi.html

[R55] 压缩与解压
来源：http://dali.wangdashe.top/Article/details/gtwcfjygaz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.dashuyun.cn/Article/details/gtoctryocf.html

[R56] 远程拷贝
来源：http://dali.sysykeji.top/Article/details/gtbrznyidm.html

scp file user@host:/path/
来源：http://dali.cqqwz.cn/Article/details/gtqggfiwah.html

[R57] 远程执行命令
来源：http://dali.yueranfly.top/Article/details/gtomnjgcey.html

ssh user@host 'uptime'
来源：http://dali.feifeiyinyue.top/Article/details/gtdriggmso.html

[R58] 下载文件
来源：http://dali.zhixingplan.top/Article/details/gtiyibdgpk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nanxuanxn.top/Article/details/gtldiekmmu.html

[R59] 发 POST JSON
来源：http://dali.dianchejie.cn/Article/details/gtfdeaklft.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.aibaodan.cn/Article/details/gtxtzafwyp.html

[R60] 只看 HTTP 状态码
来源：http://dali.daxiang520.top/Article/details/gtchrtcmzj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nanxuanxn.top/Article/details/gtgmxkrxae.html

[R61] 磁盘占用
来源：http://dali.zhixingplan.top/Article/details/gtpjlucucx.html

df -h;  du -sh *
来源：http://dali.fengsongda.top/Article/details/gtilfhzqhd.html

[R62] 找最占空间的文件
来源：http://dali.jiagoushi.top/Article/details/gthplkvncn.html

du -ah . | sort -rh | head -10
来源：http://dali.wangdashe.top/Article/details/gtbcunhiti.html

[R63] 内存与进程
来源：http://dali.9152youxi.cn/Article/details/gtccalevfa.html

free -h;  ps aux | grep nginx
来源：http://dali.xinyue.icu/Article/details/gtuihlzayj.html

[R64] 结束进程
来源：http://dali.iojbl.cn/Article/details/gtxymmcvyl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhengqikj.top/Article/details/gtwgtizyzn.html

[R65] 查看端口占用
来源：http://dali.zhixingplan.top/Article/details/gtzctgmdzc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jianghu66.top/Article/details/gtlrcguprx.html

[R66] 定时任务
来源：http://dali.yj20258.top/Article/details/gtealfcpfk.html

crontab -e;  crontab -l
来源：http://dali.andypj.xyz/Article/details/gtgsqzdrum.html

[R67] 生成随机十六进制串
来源：http://dali.xylfe.cn/Article/details/gtdrjzidmd.html

openssl rand -hex 16
来源：http://dali.shangyingyoupin.top/Article/details/gtqlztidak.html

[R68] 计算文件校验值
来源：http://dali.xziqi.cn/Article/details/gtctxqflqf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cheryme.top/Article/details/gtamhqlnol.html

[R69] 生成随机密码
来源：http://dali.gotoacloud.top/Article/details/gtpcvuawps.html

head -c 16 /dev/urandom | base64
来源：http://dali.fzhhl.top/Article/details/gtsqmpahta.html

[R70] 时间戳与互转
来源：http://dali.havefunace.top/Article/details/gthhollikn.html

date +%s;  date -d @1700000000
来源：http://dali.hywenlv.cn/Article/details/gtsrjzuxbu.html

[R71] 日期格式化
来源：http://dali.316326.xyz/Article/details/gteylyhsju.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinqigufen.top/Article/details/gtnofxdjrd.html

[R72] 等待端口就绪
来源：http://dali.dianchejie.cn/Article/details/gtpnbntawn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.c1oappe.top/Article/details/gtxbrvlumk.html

[R73] 分割大日志
来源：http://dali.cdnleiting.top/Article/details/gtwviddeng.html

split -l 1000 big.log part_
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjhtnqoyq.html

[R74] 批量重命名
来源：http://dali.xinyue.icu/Article/details/gtcwzmgwzy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.aizwys.cn/Article/details/gtsgewibkm.html

[R75] 导出环境变量
来源：http://dali.daxiang520.top/Article/details/gtfsioggcc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yj20258.top/Article/details/gtwnlxozcw.html

[R76] 使用临时文件
来源：http://dali.jqgfzy.top/Article/details/gtofihxoxo.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.0kj1m.cn/Article/details/gttbmrqcww.html

[R77] 读取用户输入
来源：http://dali.jianghu66.top/Article/details/gtwuuttmtv.html

read -rp "请输入: " ans
来源：http://dali.smart0.xyz/Article/details/gtmxljugas.html

[R78] 交互式菜单
来源：http://dali.xuetiantiany.cn/Article/details/gtxwgsmhah.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cdnleiting.top/Article/details/gtneujujgf.html

[R79] 解析命令行选项
来源：http://dali.birdmap.top/Article/details/gtcstxchgs.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.fengsongda.top/Article/details/gtecomzinz.html

[R80] 查看脚本执行耗时
来源：http://dali.havefunace.top/Article/details/gtxhowxagr.html

time ./run.sh
来源：http://dali.hysaishi.cn/Article/details/gtsizbmopo.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtogurfrfu.html

S. C / C++ 专题
来源：http://dali.sxryk.cn/Article/details/gtgophtcld.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtebxtobfi.html

[S01] C：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqdonuuwh.html

#include <stdio.h>
来源：http://dali.nanxinkj.top/Article/details/gtmcheyvdk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.daria6918.cn/Article/details/gtjjqlawke.html

[S02] C：变量与格式化输出
来源：http://dali.hongshengwenyu.top/Article/details/gtnayzuinx.html

int a = 10; printf("%d\n", a);
来源：http://dali.yvedp.cn/Article/details/gtxzzwzhtf.html

[S03] C：读入整数
来源：http://dali.cqqwz.cn/Article/details/gterupqcum.html

int x; scanf("%d", &x);
来源：http://dali.wangshuangyany.cn/Article/details/gtwuvxwknk.html

[S04] C：字符串复制
来源：http://dali.jinghuilouyu.cn/Article/details/gtojxpqnkq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.tianlin.xyz/Article/details/gtjooiqsgu.html

[S05] C：字符串长度
来源：http://dali.9152youxi.cn/Article/details/gtdwmehmmv.html

strlen(s)
来源：http://dali.tianlin.xyz/Article/details/gtcwnfkual.html

[S06] C：字符串比较
来源：http://dali.tanke756.top/Article/details/gtundtrhdo.html

strcmp(a, b) == 0
来源：http://dali.nwbrower.top/Article/details/gtcwngjyjd.html

[S07] C：数组遍历求和
来源：http://dali.jianghu66.top/Article/details/gtgdoipvky.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.aibaodan.cn/Article/details/gtvieeqfrf.html

[S08] C：动态内存分配与释放
来源：http://dali.hywenlv.cn/Article/details/gtzwakutix.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yvedp.cn/Article/details/gtzwdwyexi.html

[S09] C：结构体定义与初始化
来源：http://dali.jinghuilouyu.cn/Article/details/gtqvgohprl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cashguo.top/Article/details/gtkkegbgjt.html

[S10] C：指针与解引用
来源：http://dali.hywenlv.cn/Article/details/gtslfawczi.html

int *p = &a;  *p = 5;
来源：http://dali.jqgufenzy.top/Article/details/gtsiocahbp.html

[S11] C：逐行读文件
来源：http://dali.9152youxi.cn/Article/details/gtqqpnqbck.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xylfe.cn/Article/details/gtxpidksrn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shangyingyoupin.top/Article/details/gtjwzcmsol.html

fclose(f);
来源：http://dali.nwbrower.top/Article/details/gthwohaxvy.html

[S12] C：写文件
来源：http://dali.yanxiufei.cn/Article/details/gtlpmlvqie.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.chenjidiqi.icu/Article/details/gtzfpeafdh.html

[S13] C：宏定义
来源：http://dali.tanke756.top/Article/details/gtiypsrodi.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gogol.net.cn/Article/details/gtpcadkfwu.html

[S14] C：枚举
来源：http://dali.fengsongda.top/Article/details/gtiovknced.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jianghu66.top/Article/details/gtqxdwefma.html

[S15] C：类型转换
来源：http://dali.shanyushiyangtech.top/Article/details/gtcalpxvdw.html

(double) a / b
来源：http://dali.cqqwz.cn/Article/details/gtooicywyo.html

[S16] C：位操作置位
来源：http://dali.gogol.net.cn/Article/details/gtwywnswwd.html

x |= (1 << 3);
来源：http://dali.0kj1m.cn/Article/details/gtjjytpwdf.html

[S17] C：安全拼接字符串
来源：http://dali.birdmap.top/Article/details/gtaszaxthb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.iojbl.cn/Article/details/gtbuwiedgq.html

[S18] C：命令行参数
来源：http://dali.cucudq.cn/Article/details/gtqxisjvfe.html

int main(int argc, char **argv)
来源：http://dali.hnxiangtu.top/Article/details/gtpbygwagy.html

[S19] C：快速排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgeatnsyp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xylfe.cn/Article/details/gtkvbaeogr.html

[S20] C：二分查找
来源：http://dali.hnxiangtu.top/Article/details/gthnoajpik.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtykitdgbq.html

[S21] C：字符类别判断
来源：http://dali.hongshengwenyu.top/Article/details/gtlvefyqkp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinghuilouyu.cn/Article/details/gthpwfzyvx.html

[S22] C：字符串转数字
来源：http://dali.gzhubu.top/Article/details/gtdsulnfxa.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yj20258.top/Article/details/gtldjdoafh.html

[S23] C：随机数
来源：http://dali.jinghuilouyu.cn/Article/details/gtwkfoqtvh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.quarkkingdee.top/Article/details/gthgaeastz.html

[S24] C：获取本地时间
来源：http://dali.fengsongda.top/Article/details/gtzsiljhjm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cqqwz.cn/Article/details/gtatoloszc.html

[S25] C：内存拷贝
来源：http://dali.hammf.cn/Article/details/gtpqywevsc.html

memcpy(dst, src, n);
来源：http://dali.316326.xyz/Article/details/gtxsbqdudq.html

[S26] C：内存清零
来源：http://dali.dashuyun.cn/Article/details/gtygxlzehn.html

memset(a, 0, sizeof a);
来源：http://dali.yuxming.cn/Article/details/gtrqoqymvm.html

[S27] C：定义常量
来源：http://dali.ydzc1.top/Article/details/gtmsgkbnpa.html

const double PI = 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gtobyemgxf.html

[S28] C：静态变量
来源：http://dali.cheryme.top/Article/details/gtalfsahcz.html

static int counter = 0;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxflkbpws.html

[S29] C：变参函数
来源：http://dali.jqgufenzy.top/Article/details/gtuwqyahev.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.smart0.xyz/Article/details/gtzpiktzhr.html

[S30] C：头文件保护
来源：http://dali.bjfxy.top/Article/details/gtosrptzhh.html

#ifndef X_H
来源：http://dali.xziqi.cn/Article/details/gtjqgjoubm.html

#define X_H
来源：http://dali.c1oappe.top/Article/details/gtembjutyr.html

#endif
来源：http://dali.jinqigfzy.top/Article/details/gtuhlqhoce.html

[S31] C++：Hello World
来源：http://dali.aizwys.cn/Article/details/gthehrcvcg.html

#include <iostream>
来源：http://dali.yj20258.top/Article/details/gtkafmnisc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cdnleiting.top/Article/details/gtsszdagig.html

[S32] C++：字符串
来源：http://dali.havefunace.top/Article/details/gtnvlelqan.html

std::string s = "hi";  s += "!";
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtslrwfdhx.html

[S33] C++：vector 增删
来源：http://dali.pengpengdd.cyou/Article/details/gtfnkmjjdx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gaohongyu789.top/Article/details/gtofcmjpvz.html

[S34] C++：遍历 vector
来源：http://dali.gotoacloud.top/Article/details/gtgeablqhc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shangyingyoupin.top/Article/details/gtdmwrdseo.html

[S35] C++：map
来源：http://dali.snrcjt.cn/Article/details/gtfyyfydkm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtabgxiqkk.html

[S36] C++：unordered_map
来源：http://dali.hfpthk.cn/Article/details/gtfkyaqxkz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cdnleiting.top/Article/details/gtaohqxubj.html

[S37] C++：set
来源：http://dali.xziqi.cn/Article/details/gtarvdeyqu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj202588.top/Article/details/gtxdyynvgh.html

[S38] C++：排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gtebfkchue.html

std::sort(v.begin(), v.end());
来源：http://dali.feifeiyinyue.top/Article/details/gtuzxnvoer.html

[S39] C++：自定义比较器排序
来源：http://dali.guowangkeji.top/Article/details/gtphyxzswy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zycfv.cn/Article/details/gtaagtwoko.html

[S40] C++：查找元素
来源：http://dali.chenlongwang.top/Article/details/gtoqforyro.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.wangdashe.top/Article/details/gtwobsxqiw.html

[S41] C++：类与构造函数
来源：http://dali.zhixingplan.top/Article/details/gtlaahlufq.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.wangshuangyany.cn/Article/details/gtqacaajjj.html

[S42] C++：继承与虚函数
来源：http://dali.gotoacloud.top/Article/details/gtoirbllxr.html

class B : public Base { public: void f() override {} };
来源：http://dali.nwbrower.top/Article/details/gticyyopts.html

[S43] C++：智能指针
来源：http://dali.sxryk.cn/Article/details/gtmnrhzaqf.html

auto p = std::make_unique<int>(5);
来源：http://dali.haohaochexian.top/Article/details/gtvqamxmcf.html

[S44] C++：引用传参
来源：http://dali.xziqi.cn/Article/details/gtmyaqzmlj.html

void inc(int &x) { ++x; }
来源：http://dali.daxiang520.top/Article/details/gttknchzmr.html

[S45] C++：lambda
来源：http://dali.shuidangran.top/Article/details/gtkhayecim.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.pengpengdd.cyou/Article/details/gteddfiqvd.html

[S46] C++：函数模板
来源：http://dali.xinyue.icu/Article/details/gtrihdbcwf.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.mhx1999.top/Article/details/gtskohmcmw.html

[S47] C++：结构化绑定遍历
来源：http://dali.yongpay.top/Article/details/gtkvzewzax.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.tianlin.xyz/Article/details/gtvsfplgry.html

[S48] C++：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gtzjxrbpaq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.316326.xyz/Article/details/gteqhyblhd.html

while (std::getline(in, line)) { }
来源：http://dali.gzhubu.top/Article/details/gtwamifqsg.html

[S49] C++：写文件
来源：http://dali.wangdashe.top/Article/details/gtxmszajzf.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xuanzx.com/Article/details/gtmonfmxwn.html

[S50] C++：格式化数字
来源：http://dali.ivvv.top/Article/details/gtohdbyouk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.aizwys.cn/Article/details/gteioagflh.html

[S51] C++：显式类型转换
来源：http://dali.yj20258888.top/Article/details/gtrubqvbpk.html

static_cast<double>(a) / b
来源：http://dali.sweek.top/Article/details/gtotafmhct.html

[S52] C++：const 与 noexcept
来源：http://dali.aibaodan.cn/Article/details/gtglsbwqpj.html

int size() const noexcept { return n_; }
来源：http://dali.birdmap.top/Article/details/gtzoafdktj.html

[S53] C++：移动语义
来源：http://dali.tian-w.cn/Article/details/gtlyvdwozp.html

std::vector<int> w = std::move(v);
来源：http://dali.jinghuilouyu.cn/Article/details/gtxufhouob.html

[S54] C++：异常处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtccjdqmrp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xziqi.cn/Article/details/gttwhygboi.html

[S55] C++：结构化绑定
来源：http://dali.jlsjyb.cn/Article/details/gtghawxvlk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xuanzx.com/Article/details/gttghyvuvn.html

[S56] C++：optional
来源：http://dali.cheryme.top/Article/details/gtmqqgdsrp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.mhx1999.top/Article/details/gtcxoxtsil.html

[S57] C++：编译期常量
来源：http://dali.cucudq.cn/Article/details/gtdqhhxaag.html

constexpr int N = 10;
来源：http://dali.quarkkingdee.top/Article/details/gtajwuzupo.html

[S58] C++：命名空间
来源：http://dali.jinghuilouyu.cn/Article/details/gtprsecpqk.html

namespace ns { int f() { return 1; } }
来源：http://dali.yuxming.cn/Article/details/gtqfrulwen.html

[S59] C++：静态断言
来源：http://dali.yonumen.top/Article/details/gtguxosksm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.guannengcc.top/Article/details/gtormoaoem.html

[S60] C++：遍历并删除元素
来源：http://dali.zhongyouzk.top/Article/details/gtmwrnnplu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shangyingyoupin.top/Article/details/gtrdooasfh.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtapzwwlvo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.iojbl.cn/Article/details/gturoeirgb.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtfddvslse.html

[T01] Kotlin：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtkyksjnbd.html

println("Hello")
来源：http://dali.sxryk.cn/Article/details/gtkcwjplqm.html

[T02] Kotlin：变量
来源：http://dali.tanke756.top/Article/details/gtfnvaebvz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.snrcjt.cn/Article/details/gttuxzqile.html

[T03] Kotlin：字符串模板
来源：http://dali.aizwys.cn/Article/details/gtnketqhwi.html

"值: $b"
来源：http://dali.jqgfzy.top/Article/details/gtbsroviwz.html

[T04] Kotlin：空安全
来源：http://dali.tianlin.xyz/Article/details/gtnjwevwlp.html

val n: String? = null;  n?.length
来源：http://dali.kuanghao11.cn/Article/details/gtmgqzztsk.html

[T05] Kotlin：when 表达式
来源：http://dali.xuetiantiany.cn/Article/details/gtitkjjjgv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhijiandao.cn/Article/details/gtcnkwqoql.html

[T06] Kotlin：集合映射
来源：http://dali.guannengcc.top/Article/details/gtitbzcsvf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthuywfzxb.html

[T07] Kotlin：集合过滤
来源：http://dali.redwolf501.top/Article/details/gtutqkvcct.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shzxlz.cn/Article/details/gtfhzgtcyn.html

[T08] Kotlin：数据类
来源：http://dali.hammf.cn/Article/details/gtfzfsunry.html

data class User(val name: String, val age: Int)
来源：http://dali.snrcjt.cn/Article/details/gtalepfgul.html

[T09] Kotlin：扩展函数
来源：http://dali.nanxinkj.top/Article/details/gtukhpeovg.html

fun String.exclaim() = this + "!"
来源：http://dali.xuetiantiany.cn/Article/details/gtgzqzqinu.html

[T10] Kotlin：默认参数
来源：http://dali.nanxuanxn.top/Article/details/gtxffmcgfv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.kuanghao11.cn/Article/details/gthrrclaou.html

[T11] Kotlin：协程
来源：http://dali.nanxinkj.top/Article/details/gtpvykvysa.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hammf.cn/Article/details/gtegbbqetg.html

[T12] Kotlin：解构声明
来源：http://dali.jqgfzy.top/Article/details/gtuodkthnp.html

val (a, b) = Pair(1, 2)
来源：http://dali.mhx1999.top/Article/details/gtkaceifem.html

[T13] Kotlin：只读 Map
来源：http://dali.ydzc1.top/Article/details/gteauiurfo.html

val m = mapOf("a" to 1)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqbatrcxw.html

[T14] Kotlin：循环
来源：http://dali.haohaochexian.top/Article/details/gtuotynafv.html

for (i in 1..10) println(i)
来源：http://dali.cucudq.cn/Article/details/gtcqkwvhwt.html

[T15] Kotlin：接口
来源：http://dali.cucudq.cn/Article/details/gtilhpfsgo.html

interface Shape { fun area(): Double }
来源：http://dali.havefunace.top/Article/details/gtivjmhmfm.html

[T16] Swift：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtyfospmha.html

print("Hello")
来源：http://dali.wangdashe.top/Article/details/gtujksvgcr.html

[T17] Swift：变量与常量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbnnzyfxh.html

var a = 1;  let b = 2
来源：http://dali.cdnleiting.top/Article/details/gtwgoatxuv.html

[T18] Swift：字符串插值
来源：http://dali.yj20258888.top/Article/details/gtdofcxwfi.html

"值: \(b)"
来源：http://dali.gogol.net.cn/Article/details/gtrhtzalgx.html

[T19] Swift：可选绑定
来源：http://dali.sxryk.cn/Article/details/gtuzmggzis.html

if let n = opt { print(n) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmoylrolq.html

[T20] Swift：数组操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmlyqsdfh.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yanxiufei.cn/Article/details/gtyhtvdtsr.html

[T21] Swift：遍历
来源：http://dali.nanxuanxn.top/Article/details/gttwpnvika.html

for x in a { print(x) }
来源：http://dali.iojbl.cn/Article/details/gtocxcpccq.html

[T22] Swift：字典
来源：http://dali.xuanzx.com/Article/details/gtuqpsqzny.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.wangdashe.top/Article/details/gtslavzgkq.html

[T23] Swift：函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtfkyklgpt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdlqvxpfo.html

[T24] Swift：闭包
来源：http://dali.kuanghao11.cn/Article/details/gtkzmuqodu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxqgalbfg.html

[T25] Swift：结构体
来源：http://dali.tianlin.xyz/Article/details/gtgagsstof.html

struct P { var x: Int }
来源：http://dali.iojbl.cn/Article/details/gtgisyvvce.html

[T26] Swift：类与重写
来源：http://dali.ydzc1.top/Article/details/gtnrpmdlcx.html

class A: Base { override func f() {} }
来源：http://dali.xylfe.cn/Article/details/gtjfvqkdnr.html

[T27] Swift：错误处理
来源：http://dali.shzxlz.cn/Article/details/gtummkamkt.html

do { try f() } catch { print(error) }
来源：http://dali.zycfv.cn/Article/details/gtgntdbbuq.html

[T28] Swift：枚举
来源：http://dali.shangyingyoupin.top/Article/details/gtmlualzng.html

enum Color { case red, green }
来源：http://dali.zhijiandao.cn/Article/details/gtpaoukrkn.html

[T29] Swift：guard 提前返回
来源：http://dali.zhiwuduotai.top/Article/details/gthsuruqml.html

guard let x = opt else { return }
来源：http://dali.vqdsnc.cn/Article/details/gtrlmxenjo.html

[T30] Swift：协议
来源：http://dali.tianlin.xyz/Article/details/gtcyiswnkf.html

protocol Shape { func area() -> Double }
来源：http://dali.nanxinkj.top/Article/details/gtdlcoitou.html

[T31] Lua：Hello World
来源：http://dali.gzhubu.top/Article/details/gtlnbqpqrs.html

print("Hello")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjynomxod.html

[T32] Lua：局部变量
来源：http://dali.bjfxy.top/Article/details/gtmmrjjube.html

local a = 1
来源：http://dali.yanxiufei.cn/Article/details/gtoguljgbu.html

[T33] Lua：表（数组）
来源：http://dali.jinqigufen.top/Article/details/gtrswvvrow.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.9152youxi.cn/Article/details/gtqfbvrkxo.html

[T34] Lua：遍历表
来源：http://dali.xylfe.cn/Article/details/gtainltiad.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhiwuduotai.top/Article/details/gtekhykkki.html

[T35] Lua：字典表
来源：http://dali.zhongyouzk.top/Article/details/gtgbxsrlns.html

local d = { a = 1 };  d.b = 2
来源：http://dali.daria6918.cn/Article/details/gtgsikodfu.html

[T36] Lua：函数
来源：http://dali.pengpengdd.cyou/Article/details/gtlndnvrtt.html

function add(a, b) return a + b end
来源：http://dali.9152youxi.cn/Article/details/gtteittykc.html

[T37] Lua：字符串拼接
来源：http://dali.ppjwa.cn/Article/details/gtbuwnvieb.html

"a" .. "b"
来源：http://dali.chenzaomai.com/Article/details/gtfldqtfgd.html

[T38] Lua：条件
来源：http://dali.sysykeji.top/Article/details/gtefsgrvje.html

if x > 0 then print("正") end
来源：http://dali.tian-w.cn/Article/details/gtusdhsplj.html

[T39] Lua：模式匹配
来源：http://dali.chenlongwang.top/Article/details/gtxxbmrbqh.html

string.find(s, "%d+")
来源：http://dali.snrcjt.cn/Article/details/gtjqjyinsf.html

[T40] Lua：元表
来源：http://dali.guannengcc.top/Article/details/gtjuoqoltu.html

setmetatable({}, { __index = base })
来源：http://dali.feifeiyinyue.top/Article/details/gtpctdnyaf.html

[T41] Perl：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtpbslpgbx.html

print "Hello\n";
来源：http://dali.chenzaomai.com/Article/details/gtmydomcgm.html

[T42] Perl：变量类型
来源：http://dali.fengsongda.top/Article/details/gtjsvwmjxp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.tanke756.top/Article/details/gtkwhqhvkw.html

[T43] Perl：字符串插值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkfaksauv.html

"值: $a"
来源：http://dali.vqdsnc.cn/Article/details/gtypncytza.html

[T44] Perl：条件
来源：http://dali.cqqwz.cn/Article/details/gtcmgwcbhw.html

if ($a > 0) { print "正"; }
来源：http://dali.nanxuanxn.top/Article/details/gtsamxtelb.html

[T45] Perl：数组遍历
来源：http://dali.cashguo.top/Article/details/gtwzpgzdxx.html

for my $x (@arr) { print $x; }
来源：http://dali.jinqigufen.top/Article/details/gtweolqref.html

[T46] Perl：哈希操作
来源：http://dali.snrcjt.cn/Article/details/gtvdxazglh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.aibaodan.cn/Article/details/gtcxvjcpod.html

[T47] Perl：正则捕获
来源：http://dali.sxryk.cn/Article/details/gttffqumhc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhengqikj.top/Article/details/gtjewajqii.html

[T48] Perl：正则替换
来源：http://dali.0kj1m.cn/Article/details/gtktozuizs.html

$s =~ s/old/new/g;
来源：http://dali.hywenlv.cn/Article/details/gtgxsgxwzn.html

[T49] Perl：函数
来源：http://dali.xinyue.icu/Article/details/gtsbrieegw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gtoltooquu.html

[T50] Perl：逐行读文件
来源：http://dali.zhixingplan.top/Article/details/gtgkieaopn.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.feifeiyinyue.top/Article/details/gthsdgkshv.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.mhx1999.top/Article/details/gtoxtqkdot.html

[T51] Scala：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtpavsmdmc.html

println("Hello")
来源：http://dali.kuanghao11.cn/Article/details/gtyqqblasd.html

[T52] Scala：变量
来源：http://dali.ybcxt.top/Article/details/gtufxldfva.html

val a = 1;  var b = 2
来源：http://dali.316326.xyz/Article/details/gtofvkvlqk.html

[T53] Scala：字符串插值
来源：http://dali.sweek.top/Article/details/gtjemafsoh.html

s"值: $b"
来源：http://dali.aizwys.cn/Article/details/gtnujwwacv.html

[T54] Scala：集合映射
来源：http://dali.jinqigufen.top/Article/details/gtnuveozjo.html


<!-- 参考信息 -->