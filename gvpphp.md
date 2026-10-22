代发 wailian999

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ehwqpu.com/Article/details/gtrdtmfjqb.html

[R56] 远程拷贝
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbcuizckx.html

scp file user@host:/path/
来源：http://dali.shangyingyoupin.top/Article/details/gtinjotzie.html

[R57] 远程执行命令
来源：http://dali.nwbrower.top/Article/details/gtvlnrkqdj.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gtpghocnvl.html

[R58] 下载文件
来源：http://dali.zhoulong.xyz/Article/details/gtfotakpxc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.0kj1m.cn/Article/details/gtsnphajjh.html

[R59] 发 POST JSON
来源：http://dali.haohaochexian.top/Article/details/gtqeycfjds.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.svipenyu.cn/Article/details/gtrcipibgf.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhixingplan.top/Article/details/gtsjhqcixc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jinqigfzy.top/Article/details/gtxalyfuwi.html

[R61] 磁盘占用
来源：http://dali.xinyue.icu/Article/details/gtllmguaxn.html

df -h;  du -sh *
来源：http://dali.svipenyu.cn/Article/details/gtiuxonpmf.html

[R62] 找最占空间的文件
来源：http://dali.tian-w.cn/Article/details/gttqeepmyc.html

du -ah . | sort -rh | head -10
来源：http://dali.guannengcc.top/Article/details/gtjsdhnxga.html

[R63] 内存与进程
来源：http://dali.yuxming.cn/Article/details/gtlxuoptfy.html

free -h;  ps aux | grep nginx
来源：http://dali.zhongyouzk.top/Article/details/gtxkpldnva.html

[R64] 结束进程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtumyplmaj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.iojbl.cn/Article/details/gtqzmicpny.html

[R65] 查看端口占用
来源：http://dali.zhoulong.xyz/Article/details/gtvlxxkzoz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj202588.top/Article/details/gtrpqtptnr.html

[R66] 定时任务
来源：http://dali.zdqjudy.top/Article/details/gtkzgliwsq.html

crontab -e;  crontab -l
来源：http://dali.xinyue.icu/Article/details/gtvcftqboq.html

[R67] 生成随机十六进制串
来源：http://dali.jinqigufen.top/Article/details/gtoelfmfih.html

openssl rand -hex 16
来源：http://dali.chenlongwang.top/Article/details/gtrhktddwj.html

[R68] 计算文件校验值
来源：http://dali.yj20258888.top/Article/details/gtibwzejfq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtbkdwnjyv.html

[R69] 生成随机密码
来源：http://dali.fengsongda.top/Article/details/gtkjcyezfy.html

head -c 16 /dev/urandom | base64
来源：http://dali.0kj1m.cn/Article/details/gtiomdysmj.html

[R70] 时间戳与互转
来源：http://dali.redwolf501.top/Article/details/gtsynsxzwg.html

date +%s;  date -d @1700000000
来源：http://dali.xuetiantiany.cn/Article/details/gtyhtrthqa.html

[R71] 日期格式化
来源：http://dali.meibo888.top/Article/details/gtmfrhnwdp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gotoacloud.top/Article/details/gtwjiklweh.html

[R72] 等待端口就绪
来源：http://dali.kuanghao11.cn/Article/details/gtsfzgzqlo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gzhubu.top/Article/details/gtwgcfokwp.html

[R73] 分割大日志
来源：http://dali.yuanzhike.top/Article/details/gtgvlkyuhh.html

split -l 1000 big.log part_
来源：http://dali.gogol.net.cn/Article/details/gtokkjysew.html

[R74] 批量重命名
来源：http://dali.iojbl.cn/Article/details/gtzngeczxp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shzxlz.cn/Article/details/gtxmedmjek.html

[R75] 导出环境变量
来源：http://dali.hfpthk.cn/Article/details/gtcumxfdgj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jqgufenzy.top/Article/details/gthavyeubg.html

[R76] 使用临时文件
来源：http://dali.nwbrower.top/Article/details/gtqtijohci.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.fzhhl.top/Article/details/gthozzaljw.html

[R77] 读取用户输入
来源：http://dali.hongshengwenyu.top/Article/details/gtrflbeaiv.html

read -rp "请输入: " ans
来源：http://dali.gotoacloud.top/Article/details/gtztfyzgjl.html

[R78] 交互式菜单
来源：http://dali.zdqjudy.top/Article/details/gtvvxpmsuw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sweek.top/Article/details/gtqcnfocmt.html

[R79] 解析命令行选项
来源：http://dali.gotoacloud.top/Article/details/gtrmpkioiq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsqrjvjrf.html

[R80] 查看脚本执行耗时
来源：http://dali.meibo888.top/Article/details/gtjkssshar.html

time ./run.sh
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtigvcjzip.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtcvgttysl.html

S. C / C++ 专题
来源：http://dali.feifeiyinyue.top/Article/details/gtsimeeaqu.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtezwbmhau.html

[S01] C：Hello World
来源：http://dali.cashguo.top/Article/details/gttykczwhd.html

#include <stdio.h>
来源：http://dali.guowangkeji.top/Article/details/gtwbehzzmc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.havefunace.top/Article/details/gtvdjogolg.html

[S02] C：变量与格式化输出
来源：http://dali.hnxiangtu.top/Article/details/gttrptnugg.html

int a = 10; printf("%d\n", a);
来源：http://dali.quarkkingdee.top/Article/details/gtyxyibpyx.html

[S03] C：读入整数
来源：http://dali.xuetiantiany.cn/Article/details/gtsrwdeeuy.html

int x; scanf("%d", &x);
来源：http://dali.dashuyun.cn/Article/details/gtlztuyldm.html

[S04] C：字符串复制
来源：http://dali.havefunace.top/Article/details/gtejrobgsu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.snrcjt.cn/Article/details/gtxtzyosxc.html

[S05] C：字符串长度
来源：http://dali.daria6918.cn/Article/details/gttmvlpqlc.html

strlen(s)
来源：http://dali.gotoacloud.top/Article/details/gtwyiryvxu.html

[S06] C：字符串比较
来源：http://dali.jiagoushi.top/Article/details/gtktctchok.html

strcmp(a, b) == 0
来源：http://dali.yangfankeji.com/Article/details/gtonemnckn.html

[S07] C：数组遍历求和
来源：http://dali.sysykeji.top/Article/details/gtmhheoztb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gtmoywbpvp.html

[S08] C：动态内存分配与释放
来源：http://dali.jinghuilouyu.cn/Article/details/gtpphpekuy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cucudq.cn/Article/details/gtvtdwpccv.html

[S09] C：结构体定义与初始化
来源：http://dali.feifeiyinyue.top/Article/details/gtdwrqrluz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hywenlv.cn/Article/details/gtrbfaixom.html

[S10] C：指针与解引用
来源：http://dali.kuanghao11.cn/Article/details/gtakyzmaus.html

int *p = &a;  *p = 5;
来源：http://dali.wangdashe.top/Article/details/gtimxnhkzj.html

[S11] C：逐行读文件
来源：http://dali.gzhubu.top/Article/details/gtjddrxblq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.daria6918.cn/Article/details/gtrgcerjjj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shangyingyoupin.top/Article/details/gtvflmtlft.html

fclose(f);
来源：http://dali.cdnleiting.top/Article/details/gttxzzzple.html

[S12] C：写文件
来源：http://dali.jinqigfzy.top/Article/details/gtsnanbred.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xinyue.icu/Article/details/gtmsutnfcn.html

[S13] C：宏定义
来源：http://dali.havefunace.top/Article/details/gttxbwadee.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.chenlongwang.top/Article/details/gtqguikvvw.html

[S14] C：枚举
来源：http://dali.snrcjt.cn/Article/details/gtiqliksyq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gzhubu.top/Article/details/gtjksohxok.html

[S15] C：类型转换
来源：http://dali.yj202588.top/Article/details/gthqcwyvyg.html

(double) a / b
来源：http://dali.daxiang520.top/Article/details/gteuvmbeys.html

[S16] C：位操作置位
来源：http://dali.zhongyouzk.top/Article/details/gttazfffwq.html

x |= (1 << 3);
来源：http://dali.hnxiangtu.top/Article/details/gtccsomqdc.html

[S17] C：安全拼接字符串
来源：http://dali.snrcjt.cn/Article/details/gtmkoiwzbz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinqigfzy.top/Article/details/gtzifgxxrz.html

[S18] C：命令行参数
来源：http://dali.mhx1999.top/Article/details/gtxttrnihp.html

int main(int argc, char **argv)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbigggbrt.html

[S19] C：快速排序
来源：http://dali.ydzc1.top/Article/details/gtqtuctnvc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cqqwz.cn/Article/details/gtlteyeqjr.html

[S20] C：二分查找
来源：http://dali.jlsjyb.cn/Article/details/gtrrkwpwgu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yj202588.top/Article/details/gtwqaothiu.html

[S21] C：字符类别判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtknecgfqj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xuetiantiany.cn/Article/details/gtldouyjlc.html

[S22] C：字符串转数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjotivbik.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shuidangran.top/Article/details/gtmmzlzvlg.html

[S23] C：随机数
来源：http://dali.xinyue.icu/Article/details/gtehdomqoa.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jlsjyb.cn/Article/details/gtdstonfjy.html

[S24] C：获取本地时间
来源：http://dali.sysykeji.top/Article/details/gtwipgxcpu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhongyouzk.top/Article/details/gtrrivuwmq.html

[S25] C：内存拷贝
来源：http://dali.cheryme.top/Article/details/gttwwfzcdc.html

memcpy(dst, src, n);
来源：http://dali.ivvv.top/Article/details/gtknxiicun.html

[S26] C：内存清零
来源：http://dali.meibo888.top/Article/details/gtlqooiugf.html

memset(a, 0, sizeof a);
来源：http://dali.nanxuanxn.top/Article/details/gtcpudlrvo.html

[S27] C：定义常量
来源：http://dali.9152youxi.cn/Article/details/gttqtzfxab.html

const double PI = 3.14159;
来源：http://dali.daria6918.cn/Article/details/gtatvnymtm.html

[S28] C：静态变量
来源：http://dali.tianlin.xyz/Article/details/gtfiazenav.html

static int counter = 0;
来源：http://dali.aizwys.cn/Article/details/gtjaurvuvm.html

[S29] C：变参函数
来源：http://dali.chenzaomai.com/Article/details/gtuganaivy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hongshengwenyu.top/Article/details/gtfkzkjgud.html

[S30] C：头文件保护
来源：http://dali.tanke756.top/Article/details/gtkruoxvgz.html

#ifndef X_H
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtorpqbfzb.html

#define X_H
来源：http://dali.chenlongwang.top/Article/details/gtalcmxlxj.html

#endif
来源：http://dali.9152youxi.cn/Article/details/gtckjaerrn.html

[S31] C++：Hello World
来源：http://dali.guannengcc.top/Article/details/gtngvzhbha.html

#include <iostream>
来源：http://dali.xziqi.cn/Article/details/gtjwvtbqpu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.aibaodan.cn/Article/details/gtpysikhnp.html

[S32] C++：字符串
来源：http://dali.yongpay.top/Article/details/gtwxoojcif.html

std::string s = "hi";  s += "!";
来源：http://dali.daxiang520.top/Article/details/gtyyigmtjm.html

[S33] C++：vector 增删
来源：http://dali.svipenyu.cn/Article/details/gtcqqqjira.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.mhx1999.top/Article/details/gtrniqcvns.html

[S34] C++：遍历 vector
来源：http://dali.jiagoushi.top/Article/details/gtirmlscgm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.mhx1999.top/Article/details/gtfybrxacd.html

[S35] C++：map
来源：http://dali.c1oappe.top/Article/details/gtlqhptoxd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yvedp.cn/Article/details/gtzzamfruv.html

[S36] C++：unordered_map
来源：http://dali.guowangkeji.top/Article/details/gtzblglrfa.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ppjwa.cn/Article/details/gtssmeofhn.html

[S37] C++：set
来源：http://dali.wangshuangyany.cn/Article/details/gtzgzbwvtt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cheryme.top/Article/details/gtlfmwnwfv.html

[S38] C++：排序
来源：http://dali.gogol.net.cn/Article/details/gtfgnkebpy.html

std::sort(v.begin(), v.end());
来源：http://dali.feifeiyinyue.top/Article/details/gtwdobjyoh.html

[S39] C++：自定义比较器排序
来源：http://dali.yangfankeji.com/Article/details/gtptryhisk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.aizwys.cn/Article/details/gtzxmkadla.html

[S40] C++：查找元素
来源：http://dali.yuxming.cn/Article/details/gtafttrkve.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.redwolf501.top/Article/details/gtxfizebcp.html

[S41] C++：类与构造函数
来源：http://dali.pengpengdd.cyou/Article/details/gthwcioqxf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.haohaochexian.top/Article/details/gtsbpqymid.html

[S42] C++：继承与虚函数
来源：http://dali.hysaishi.cn/Article/details/gtcczqgril.html

class B : public Base { public: void f() override {} };
来源：http://dali.jqgufenzy.top/Article/details/gtojrraeib.html

[S43] C++：智能指针
来源：http://dali.shzxlz.cn/Article/details/gtlihpikfj.html

auto p = std::make_unique<int>(5);
来源：http://dali.svipenyu.cn/Article/details/gtqaveqgfr.html

[S44] C++：引用传参
来源：http://dali.yuxming.cn/Article/details/gtsmrwmgbj.html

void inc(int &x) { ++x; }
来源：http://dali.yanxiufei.cn/Article/details/gtlvsyztaf.html

[S45] C++：lambda
来源：http://dali.gotoacloud.top/Article/details/gtqywluqbj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nanxinkj.top/Article/details/gtnvgqkgal.html

[S46] C++：函数模板
来源：http://dali.nwbrower.top/Article/details/gtfcpaiqne.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinqigfzy.top/Article/details/gtwvzlzssl.html

[S47] C++：结构化绑定遍历
来源：http://dali.xinyue.icu/Article/details/gtigukqbsl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.wangshuangyany.cn/Article/details/gtqamaykjw.html

[S48] C++：逐行读文件
来源：http://dali.cdnleiting.top/Article/details/gtxbxsufht.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ivvv.top/Article/details/gtvcncxsgi.html

while (std::getline(in, line)) { }
来源：http://dali.tian-w.cn/Article/details/gtiolvgvcp.html

[S49] C++：写文件
来源：http://dali.zhongyouzk.top/Article/details/gtehlaysek.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.pengpengdd.cyou/Article/details/gttcewcueg.html

[S50] C++：格式化数字
来源：http://dali.9152youxi.cn/Article/details/gtbogcvidx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtduhvuggq.html

[S51] C++：显式类型转换
来源：http://dali.cucudq.cn/Article/details/gtbuxpkbob.html

static_cast<double>(a) / b
来源：http://dali.zhiwuduotai.top/Article/details/gtutiqqbwc.html

[S52] C++：const 与 noexcept
来源：http://dali.shangyingyoupin.top/Article/details/gtdpuszdtr.html

int size() const noexcept { return n_; }
来源：http://dali.guowangkeji.top/Article/details/gtllzalrje.html

[S53] C++：移动语义
来源：http://dali.smart0.xyz/Article/details/gttbrcicoo.html

std::vector<int> w = std::move(v);
来源：http://dali.0kj1m.cn/Article/details/gtuojpfdlz.html

[S54] C++：异常处理
来源：http://dali.zhixingplan.top/Article/details/gtophrvihd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gtyofwioel.html

[S55] C++：结构化绑定
来源：http://dali.tanke756.top/Article/details/gtguexnunv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cdnleiting.top/Article/details/gtrfdxryta.html

[S56] C++：optional
来源：http://dali.sxryk.cn/Article/details/gttsyrrlog.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtldfyjadl.html

[S57] C++：编译期常量
来源：http://dali.guannengcc.top/Article/details/gtbwldybyh.html

constexpr int N = 10;
来源：http://dali.cheryme.top/Article/details/gtfmqvzsmh.html

[S58] C++：命名空间
来源：http://dali.gotoacloud.top/Article/details/gtqkhoofrv.html

namespace ns { int f() { return 1; } }
来源：http://dali.hammf.cn/Article/details/gtmofgrlbh.html

[S59] C++：静态断言
来源：http://dali.redwolf501.top/Article/details/gtxtgagfyd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gaohongyu789.top/Article/details/gtqvivhuep.html

[S60] C++：遍历并删除元素
来源：http://dali.gzhubu.top/Article/details/gtmvnknszg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sufxvd.cn/Article/details/gtctnhkgap.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtohtftvfw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtaaweedfo.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtsnlierge.html

[T01] Kotlin：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtvuchwfuk.html

println("Hello")
来源：http://dali.jlsjyb.cn/Article/details/gtrznkktax.html

[T02] Kotlin：变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtsyvwttmj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hongshengwenyu.top/Article/details/gtlwkcnwqx.html

[T03] Kotlin：字符串模板
来源：http://dali.zhengqikj.top/Article/details/gtehhcgmdd.html

"值: $b"
来源：http://dali.shanyushiyangtech.top/Article/details/gtychgnine.html

[T04] Kotlin：空安全
来源：http://dali.zhongyouzk.top/Article/details/gtycdyywzu.html

val n: String? = null;  n?.length
来源：http://dali.cdnleiting.top/Article/details/gtxpdyfvrg.html

[T05] Kotlin：when 表达式
来源：http://dali.quarkkingdee.top/Article/details/gtsutdfiwu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hnxiangtu.top/Article/details/gtglhahswb.html

[T06] Kotlin：集合映射
来源：http://dali.ehwqpu.com/Article/details/gtoqasaexi.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.9152youxi.cn/Article/details/gtqpvqheep.html

[T07] Kotlin：集合过滤
来源：http://dali.hnqzz.top/Article/details/gttfqjfphf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ybcxt.top/Article/details/gtjqdstavr.html

[T08] Kotlin：数据类
来源：http://dali.ivvv.top/Article/details/gtynlkcecb.html

data class User(val name: String, val age: Int)
来源：http://dali.chenzaomai.com/Article/details/gtttdxisud.html

[T09] Kotlin：扩展函数
来源：http://dali.xuanzx.com/Article/details/gtielldsgp.html

fun String.exclaim() = this + "!"
来源：http://dali.redwolf501.top/Article/details/gtlcftlmym.html

[T10] Kotlin：默认参数
来源：http://dali.yj202588.top/Article/details/gtcraywxnh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.meibo888.top/Article/details/gtzsauwtmm.html

[T11] Kotlin：协程
来源：http://dali.chenjidiqi.icu/Article/details/gtabeuhxao.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.wangshuangyany.cn/Article/details/gtdycbjuml.html

[T12] Kotlin：解构声明
来源：http://dali.birdmap.top/Article/details/gtmbqzcbrk.html

val (a, b) = Pair(1, 2)
来源：http://dali.sysykeji.top/Article/details/gtlzxnardf.html

[T13] Kotlin：只读 Map
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrnpjeudy.html

val m = mapOf("a" to 1)
来源：http://dali.cucudq.cn/Article/details/gtcanwkape.html

[T14] Kotlin：循环
来源：http://dali.tian-w.cn/Article/details/gttokhusmo.html

for (i in 1..10) println(i)
来源：http://dali.bjfxy.top/Article/details/gtfherthrz.html

[T15] Kotlin：接口
来源：http://dali.xuetiantiany.cn/Article/details/gthfsftqdm.html

interface Shape { fun area(): Double }
来源：http://dali.birdmap.top/Article/details/gtvmvnxolq.html

[T16] Swift：Hello World
来源：http://dali.xylfe.cn/Article/details/gtjonrfnoe.html

print("Hello")
来源：http://dali.sweek.top/Article/details/gtpbeosbgd.html

[T17] Swift：变量与常量
来源：http://dali.dianchejie.cn/Article/details/gtnnvrjgcl.html

var a = 1;  let b = 2
来源：http://dali.ppjwa.cn/Article/details/gtfadpmlpn.html

[T18] Swift：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gtvdjcjijz.html

"值: \(b)"
来源：http://dali.dashuyun.cn/Article/details/gtrkjobhxu.html

[T19] Swift：可选绑定
来源：http://dali.aibaodan.cn/Article/details/gtryhtejdj.html

if let n = opt { print(n) }
来源：http://dali.vqdsnc.cn/Article/details/gtigqhqqdl.html

[T20] Swift：数组操作
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvihkgowz.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.mhx1999.top/Article/details/gtkedigusv.html

[T21] Swift：遍历
来源：http://dali.jqgfzy.top/Article/details/gtzwrfyuap.html

for x in a { print(x) }
来源：http://dali.jqgufenzy.top/Article/details/gtnlzbzkyn.html

[T22] Swift：字典
来源：http://dali.fzhhl.top/Article/details/gtlifaiuei.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ybcxt.top/Article/details/gtkvlatpne.html

[T23] Swift：函数
来源：http://dali.vqdsnc.cn/Article/details/gthymgkden.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.daria6918.cn/Article/details/gtjkyzlnws.html

[T24] Swift：闭包
来源：http://dali.sufxvd.cn/Article/details/gtruvqprws.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zycfv.cn/Article/details/gtghmybmkb.html

[T25] Swift：结构体
来源：http://dali.yueranfly.top/Article/details/gtviqjanuw.html

struct P { var x: Int }
来源：http://dali.yuanzhike.top/Article/details/gtaocbtwsp.html

[T26] Swift：类与重写
来源：http://dali.hammf.cn/Article/details/gteykuqmxn.html

class A: Base { override func f() {} }
来源：http://dali.gzhubu.top/Article/details/gtahbkuibe.html

[T27] Swift：错误处理
来源：http://dali.yueranfly.top/Article/details/gtyheswywz.html

do { try f() } catch { print(error) }
来源：http://dali.cdnleiting.top/Article/details/gtsgtzsmtx.html

[T28] Swift：枚举
来源：http://dali.zhongyouzk.top/Article/details/gtaaezxzqj.html

enum Color { case red, green }
来源：http://dali.nanxinkj.top/Article/details/gtqgqjplzz.html

[T29] Swift：guard 提前返回
来源：http://dali.zhoulong.xyz/Article/details/gtsvlnqfen.html

guard let x = opt else { return }
来源：http://dali.ehwqpu.com/Article/details/gtyihdqukm.html

[T30] Swift：协议
来源：http://dali.zhixingplan.top/Article/details/gtrywnmhco.html

protocol Shape { func area() -> Double }
来源：http://dali.gzhubu.top/Article/details/gtvehxdmfq.html

[T31] Lua：Hello World
来源：http://dali.0kj1m.cn/Article/details/gtytlkaxjo.html

print("Hello")
来源：http://dali.hnqzz.top/Article/details/gteljwloxd.html

[T32] Lua：局部变量
来源：http://dali.zhengqikj.top/Article/details/gtfnfxkobz.html

local a = 1
来源：http://dali.wangshuangyany.cn/Article/details/gtlqmpjwrk.html

[T33] Lua：表（数组）
来源：http://dali.fzhhl.top/Article/details/gtwmwfypeg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shuidangran.top/Article/details/gtdukniixp.html

[T34] Lua：遍历表
来源：http://dali.yvedp.cn/Article/details/gtnokxoiai.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jyoumei.cn/Article/details/gtnexokeok.html

[T35] Lua：字典表
来源：http://dali.tianlin.xyz/Article/details/gtayhdwpxe.html

local d = { a = 1 };  d.b = 2
来源：http://dali.gzhubu.top/Article/details/gtbmraedyp.html

[T36] Lua：函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdwaqjhpt.html

function add(a, b) return a + b end
来源：http://dali.cdnleiting.top/Article/details/gthiuesmqv.html

[T37] Lua：字符串拼接
来源：http://dali.cheryme.top/Article/details/gtzgkhselw.html

"a" .. "b"
来源：http://dali.jlsjyb.cn/Article/details/gthqxkghgw.html

[T38] Lua：条件
来源：http://dali.feifeiyinyue.top/Article/details/gtpdqrcgpp.html

if x > 0 then print("正") end
来源：http://dali.tianlin.xyz/Article/details/gtrvhzrnrt.html

[T39] Lua：模式匹配
来源：http://dali.zhiwuduotai.top/Article/details/gtpfdaartm.html

string.find(s, "%d+")
来源：http://dali.yj20258888.top/Article/details/gtvuplmqas.html

[T40] Lua：元表
来源：http://dali.chenlongwang.top/Article/details/gtbugqvuof.html

setmetatable({}, { __index = base })
来源：http://dali.tian-w.cn/Article/details/gtcwpkczct.html

[T41] Perl：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gteonpjnbj.html

print "Hello\n";
来源：http://dali.hongshengwenyu.top/Article/details/gtyflncanv.html

[T42] Perl：变量类型
来源：http://dali.sufxvd.cn/Article/details/gtgsudjpwv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ydzc1.top/Article/details/gthydtjdbg.html

[T43] Perl：字符串插值
来源：http://dali.sweek.top/Article/details/gtszoyjvfa.html

"值: $a"
来源：http://dali.nanxinkj.top/Article/details/gtfkznmnlw.html

[T44] Perl：条件
来源：http://dali.chenlongwang.top/Article/details/gtubczmdjv.html

if ($a > 0) { print "正"; }
来源：http://dali.cdnleiting.top/Article/details/gttavxxnom.html

[T45] Perl：数组遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtwyjajoow.html

for my $x (@arr) { print $x; }
来源：http://dali.smart0.xyz/Article/details/gtpmhhwafq.html

[T46] Perl：哈希操作
来源：http://dali.chenjidiqi.icu/Article/details/gtrvdjweyi.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.wangdashe.top/Article/details/gtpuyzlzub.html

[T47] Perl：正则捕获
来源：http://dali.shanyushiyangtech.top/Article/details/gtvqhtbyrg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.wangshuangyany.cn/Article/details/gtkclfplos.html

[T48] Perl：正则替换
来源：http://dali.hnxiangtu.top/Article/details/gtkfgcgrej.html

$s =~ s/old/new/g;
来源：http://dali.hnqzz.top/Article/details/gtrdrdqodu.html

[T49] Perl：函数
来源：http://dali.fengsongda.top/Article/details/gtvrmeehdb.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.ybcxt.top/Article/details/gttfntfpcr.html

[T50] Perl：逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gtaswpfhjp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.chenzaomai.com/Article/details/gtjeoacpjl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtumabpbch.html

[T51] Scala：Hello World
来源：http://dali.ppjwa.cn/Article/details/gttktppwsr.html

println("Hello")
来源：http://dali.0kj1m.cn/Article/details/gtwfnbqhsq.html

[T52] Scala：变量
来源：http://dali.daxiang520.top/Article/details/gtvtrthaxt.html

val a = 1;  var b = 2
来源：http://dali.sysykeji.top/Article/details/gtwzihyouo.html

[T53] Scala：字符串插值
来源：http://dali.xinyue.icu/Article/details/gtbatnjuhr.html

s"值: $b"
来源：http://dali.smart0.xyz/Article/details/gtqsjaqcrk.html

[T54] Scala：集合映射
来源：http://dali.vqdsnc.cn/Article/details/gtjdffjenh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gogol.net.cn/Article/details/gtopfqvvkv.html

[T55] Scala：集合过滤
来源：http://dali.zhengqikj.top/Article/details/gttymltifx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlcaufpdk.html

[T56] Scala：样例类
来源：http://dali.sweek.top/Article/details/gtmruxsgxr.html

case class User(name: String, age: Int)
来源：http://dali.hnqzz.top/Article/details/gtolwadmbn.html

[T57] Scala：模式匹配
来源：http://dali.9152youxi.cn/Article/details/gtqsdphawe.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.quarkkingdee.top/Article/details/gtrglryhko.html

[T58] Scala：函数定义
来源：http://dali.jinqigufen.top/Article/details/gtfgsdribi.html


<!-- 参考信息 -->