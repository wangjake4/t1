代发 wailian999

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jiagoushi.top/Article/details/gtzdsebmop.html

[R60] 只看 HTTP 状态码
来源：http://dali.hnqzz.top/Article/details/gtlqczuatr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.smart0.xyz/Article/details/gtcnwcjbfa.html

[R61] 磁盘占用
来源：http://dali.hammf.cn/Article/details/gtjsjfyyjc.html

df -h;  du -sh *
来源：http://dali.cucudq.cn/Article/details/gtjwzyvlbm.html

[R62] 找最占空间的文件
来源：http://dali.gaohongyu789.top/Article/details/gtbswuevdw.html

du -ah . | sort -rh | head -10
来源：http://dali.hysaishi.cn/Article/details/gtvbsllnik.html

[R63] 内存与进程
来源：http://dali.fengsongda.top/Article/details/gtmkgmbkei.html

free -h;  ps aux | grep nginx
来源：http://dali.guowangkeji.top/Article/details/gtpruaozuf.html

[R64] 结束进程
来源：http://dali.yj202588.top/Article/details/gttwwokixc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.andypj.xyz/Article/details/gtcpqsakox.html

[R65] 查看端口占用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtufyliqbh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yvedp.cn/Article/details/gtdrxwyktl.html

[R66] 定时任务
来源：http://dali.cdnleiting.top/Article/details/gtdxeztdkj.html

crontab -e;  crontab -l
来源：http://dali.shuidangran.top/Article/details/gtkqxajmxl.html

[R67] 生成随机十六进制串
来源：http://dali.vqdsnc.cn/Article/details/gtqevxkqgg.html

openssl rand -hex 16
来源：http://dali.nwbrower.top/Article/details/gtglvvkhhq.html

[R68] 计算文件校验值
来源：http://dali.redwolf501.top/Article/details/gtycvyqchd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cucudq.cn/Article/details/gtvipgqhhi.html

[R69] 生成随机密码
来源：http://dali.jinqigfzy.top/Article/details/gtuabferoj.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhiwuduotai.top/Article/details/gtuzdpniyr.html

[R70] 时间戳与互转
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwnwhmjst.html

date +%s;  date -d @1700000000
来源：http://dali.chenlongwang.top/Article/details/gtapbfysil.html

[R71] 日期格式化
来源：http://dali.jlsjyb.cn/Article/details/gtixmtqjve.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.smart0.xyz/Article/details/gtyjzmpuqy.html

[R72] 等待端口就绪
来源：http://dali.gotoacloud.top/Article/details/gtnjrlovxy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jqgufenzy.top/Article/details/gthwwbretf.html

[R73] 分割大日志
来源：http://dali.wangshuangyany.cn/Article/details/gtzerjedho.html

split -l 1000 big.log part_
来源：http://dali.ehwqpu.com/Article/details/gtcnqximqs.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gtnarmkwwj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hnxiangtu.top/Article/details/gtcxynkumm.html

[R75] 导出环境变量
来源：http://dali.zhixingplan.top/Article/details/gtqonebbgd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yuxming.cn/Article/details/gtnrzjhutz.html

[R76] 使用临时文件
来源：http://dali.gaohongyu789.top/Article/details/gthxgczkwn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.pycfn.com/Article/details/gtozrwnewp.html

[R77] 读取用户输入
来源：http://dali.ehwqpu.com/Article/details/gtcshrggnp.html

read -rp "请输入: " ans
来源：http://dali.yuanzhike.top/Article/details/gtevsfwzkc.html

[R78] 交互式菜单
来源：http://dali.daxiang520.top/Article/details/gttvbmpvof.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xuanzx.com/Article/details/gtxdsfjjxv.html

[R79] 解析命令行选项
来源：http://dali.guannengcc.top/Article/details/gtqhwbjkgc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gzhubu.top/Article/details/gtyjmimpui.html

[R80] 查看脚本执行耗时
来源：http://dali.ybcxt.top/Article/details/gtiehukvyd.html

time ./run.sh
来源：http://dali.wangdashe.top/Article/details/gtaaztgxem.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmyeoaqgy.html

S. C / C++ 专题
来源：http://dali.jqgfzy.top/Article/details/gtnnbvhbtp.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtlbefebct.html

[S01] C：Hello World
来源：http://dali.redwolf501.top/Article/details/gtdddiwewm.html

#include <stdio.h>
来源：http://dali.sweek.top/Article/details/gthjjnrgeh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhixingplan.top/Article/details/gtunzzymim.html

[S02] C：变量与格式化输出
来源：http://dali.fzhhl.top/Article/details/gtafocpbvo.html

int a = 10; printf("%d\n", a);
来源：http://dali.daria6918.cn/Article/details/gtxxjwwiep.html

[S03] C：读入整数
来源：http://dali.jinyuanbaomall.cn/Article/details/gteekiubmx.html

int x; scanf("%d", &x);
来源：http://dali.pycfn.com/Article/details/gttzsiuwhs.html

[S04] C：字符串复制
来源：http://dali.guowangkeji.top/Article/details/gteipzycsq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shuidangran.top/Article/details/gtnkcmtkxl.html

[S05] C：字符串长度
来源：http://dali.yj20258.top/Article/details/gtyazhmxrm.html

strlen(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdjzzrvao.html

[S06] C：字符串比较
来源：http://dali.9152youxi.cn/Article/details/gtdnpjwxmz.html

strcmp(a, b) == 0
来源：http://dali.chenjidiqi.icu/Article/details/gtykbhpdxd.html

[S07] C：数组遍历求和
来源：http://dali.yvedp.cn/Article/details/gthfqyttio.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sufxvd.cn/Article/details/gtqtpgnjoq.html

[S08] C：动态内存分配与释放
来源：http://dali.9152youxi.cn/Article/details/gtknrdcdyi.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.vqdsnc.cn/Article/details/gtnootplrj.html

[S09] C：结构体定义与初始化
来源：http://dali.jinyuanbaomall.cn/Article/details/gttuxvmsvr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.feifeiyinyue.top/Article/details/gtgukjchol.html

[S10] C：指针与解引用
来源：http://dali.pycfn.com/Article/details/gtumiupphs.html

int *p = &a;  *p = 5;
来源：http://dali.kuanghao11.cn/Article/details/gtgpiyefxf.html

[S11] C：逐行读文件
来源：http://dali.yongpay.top/Article/details/gthfonrqeh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cqqwz.cn/Article/details/gtvbrlxdju.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.vqdsnc.cn/Article/details/gtpqplvvhf.html

fclose(f);
来源：http://dali.shzxlz.cn/Article/details/gtggamfzly.html

[S12] C：写文件
来源：http://dali.zhengqikj.top/Article/details/gtwzabmyqr.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhixingplan.top/Article/details/gtofeisple.html

[S13] C：宏定义
来源：http://dali.daxiang520.top/Article/details/gtdznjhdsr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jqgfzy.top/Article/details/gtuhtfrhcn.html

[S14] C：枚举
来源：http://dali.nanxinkj.top/Article/details/gtxsgcyrzu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.aizwys.cn/Article/details/gtqzaxnpkl.html

[S15] C：类型转换
来源：http://dali.daxiang520.top/Article/details/gtpxrziqca.html

(double) a / b
来源：http://dali.feifeiyinyue.top/Article/details/gtzcbrahqy.html

[S16] C：位操作置位
来源：http://dali.yangfankeji.com/Article/details/gtnsuocmok.html

x |= (1 << 3);
来源：http://dali.hysaishi.cn/Article/details/gtmqggdtkz.html

[S17] C：安全拼接字符串
来源：http://dali.tianlin.xyz/Article/details/gtptccleth.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.nanxuanxn.top/Article/details/gtnbfczlhr.html

[S18] C：命令行参数
来源：http://dali.xuetiantiany.cn/Article/details/gtfbzhlztk.html

int main(int argc, char **argv)
来源：http://dali.yangfankeji.com/Article/details/gturceaflz.html

[S19] C：快速排序
来源：http://dali.zycfv.cn/Article/details/gtfpbavfzl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.havefunace.top/Article/details/gtovdjqgbf.html

[S20] C：二分查找
来源：http://dali.yueranfly.top/Article/details/gtbejqqjiz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.chenzaomai.com/Article/details/gtvbvaomwn.html

[S21] C：字符类别判断
来源：http://dali.jinqigufen.top/Article/details/gtsfocqjia.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.guowangkeji.top/Article/details/gtchkqoqpl.html

[S22] C：字符串转数字
来源：http://dali.yuxming.cn/Article/details/gtqtqfsilz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cdnleiting.top/Article/details/gtiwyozhju.html

[S23] C：随机数
来源：http://dali.hfpthk.cn/Article/details/gtpfaoyuot.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhixingplan.top/Article/details/gtlupcrvex.html

[S24] C：获取本地时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrzevforz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hnqzz.top/Article/details/gtfnfwtxcc.html

[S25] C：内存拷贝
来源：http://dali.quarkkingdee.top/Article/details/gtvbfepwwh.html

memcpy(dst, src, n);
来源：http://dali.c1oappe.top/Article/details/gtyavjverb.html

[S26] C：内存清零
来源：http://dali.vqdsnc.cn/Article/details/gtwjuhwdtb.html

memset(a, 0, sizeof a);
来源：http://dali.hnqzz.top/Article/details/gthpujmanv.html

[S27] C：定义常量
来源：http://dali.daria6918.cn/Article/details/gtuikzodyx.html

const double PI = 3.14159;
来源：http://dali.daxiang520.top/Article/details/gtlawwkuox.html

[S28] C：静态变量
来源：http://dali.hammf.cn/Article/details/gtbubyeuje.html

static int counter = 0;
来源：http://dali.ppjwa.cn/Article/details/gtckabfghe.html

[S29] C：变参函数
来源：http://dali.dashuyun.cn/Article/details/gtfpbusdel.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yuanzhike.top/Article/details/gtepltitwz.html

[S30] C：头文件保护
来源：http://dali.yangfankeji.com/Article/details/gtuujpgofb.html

#ifndef X_H
来源：http://dali.dashuyun.cn/Article/details/gtdkxwhyqy.html

#define X_H
来源：http://dali.c1oappe.top/Article/details/gtwtgizpju.html

#endif
来源：http://dali.zhiwuduotai.top/Article/details/gtgmmqzgaj.html

[S31] C++：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtepvgfhpw.html

#include <iostream>
来源：http://dali.havefunace.top/Article/details/gttjifqgmg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.daria6918.cn/Article/details/gtkoywhpnq.html

[S32] C++：字符串
来源：http://dali.guannengcc.top/Article/details/gtmvfeuicx.html

std::string s = "hi";  s += "!";
来源：http://dali.cqqwz.cn/Article/details/gtdjnrtphr.html

[S33] C++：vector 增删
来源：http://dali.gogol.net.cn/Article/details/gtwgpcihfs.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zycfv.cn/Article/details/gtswajbifl.html

[S34] C++：遍历 vector
来源：http://dali.gotoacloud.top/Article/details/gtjsxdtlas.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yj20258.top/Article/details/gtbgplgjns.html

[S35] C++：map
来源：http://dali.nwbrower.top/Article/details/gtgqbywgbk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zycfv.cn/Article/details/gtanxauuyx.html

[S36] C++：unordered_map
来源：http://dali.dianchejie.cn/Article/details/gtkgspbpto.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangdashe.top/Article/details/gtccbvomfq.html

[S37] C++：set
来源：http://dali.316326.xyz/Article/details/gtdetfyxwx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yvedp.cn/Article/details/gtgnnsqymi.html

[S38] C++：排序
来源：http://dali.yuxming.cn/Article/details/gtlqmypfik.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gtqmiojfuo.html

[S39] C++：自定义比较器排序
来源：http://dali.andypj.xyz/Article/details/gtvhsqnvra.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.guowangkeji.top/Article/details/gtmnhjmsmg.html

[S40] C++：查找元素
来源：http://dali.sufxvd.cn/Article/details/gtdynwmrfz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhengqikj.top/Article/details/gteqjhrwkw.html

[S41] C++：类与构造函数
来源：http://dali.guowangkeji.top/Article/details/gtbcnmbafj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zycfv.cn/Article/details/gtebpeuzuv.html

[S42] C++：继承与虚函数
来源：http://dali.yueranfly.top/Article/details/gtajmdkxgg.html

class B : public Base { public: void f() override {} };
来源：http://dali.feifeiyinyue.top/Article/details/gthvfvauzw.html

[S43] C++：智能指针
来源：http://dali.daria6918.cn/Article/details/gtumhcdpkn.html

auto p = std::make_unique<int>(5);
来源：http://dali.xuanzx.com/Article/details/gtxftrfdfb.html

[S44] C++：引用传参
来源：http://dali.sufxvd.cn/Article/details/gtozxkekjp.html

void inc(int &x) { ++x; }
来源：http://dali.cqqwz.cn/Article/details/gtshlprsmb.html

[S45] C++：lambda
来源：http://dali.zhiwuduotai.top/Article/details/gtjcahnhqi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.aibaodan.cn/Article/details/gtiujwfzmi.html

[S46] C++：函数模板
来源：http://dali.wangshuangyany.cn/Article/details/gtkebezfsy.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.fzhhl.top/Article/details/gtqyzbwikn.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhongyouzk.top/Article/details/gtrowsdosm.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zycfv.cn/Article/details/gtqkbnhkzr.html

[S48] C++：逐行读文件
来源：http://dali.pengpengdd.cyou/Article/details/gteamvjmfm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ehwqpu.com/Article/details/gtpijoqdov.html

while (std::getline(in, line)) { }
来源：http://dali.zycfv.cn/Article/details/gtmjxgpjll.html

[S49] C++：写文件
来源：http://dali.jqgufenzy.top/Article/details/gtbjkyljok.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.iojbl.cn/Article/details/gtgbeudoxb.html

[S50] C++：格式化数字
来源：http://dali.zhijiandao.cn/Article/details/gtxeetpkvg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yj202588.top/Article/details/gtynoqhtlf.html

[S51] C++：显式类型转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzgcnwcrr.html

static_cast<double>(a) / b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtohdlgmhm.html

[S52] C++：const 与 noexcept
来源：http://dali.ybcxt.top/Article/details/gtbvwmbugt.html

int size() const noexcept { return n_; }
来源：http://dali.gaohongyu789.top/Article/details/gtvjgxcmqh.html

[S53] C++：移动语义
来源：http://dali.shanyushiyangtech.top/Article/details/gtbvjmapzp.html

std::vector<int> w = std::move(v);
来源：http://dali.ydzc1.top/Article/details/gtkyncqeod.html

[S54] C++：异常处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtijoujerg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.9152youxi.cn/Article/details/gtybmgdesd.html

[S55] C++：结构化绑定
来源：http://dali.dashuyun.cn/Article/details/gtjywdpycz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jiagoushi.top/Article/details/gtulpycjfb.html

[S56] C++：optional
来源：http://dali.yuxming.cn/Article/details/gtqblknfca.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cdnleiting.top/Article/details/gtdipqearj.html

[S57] C++：编译期常量
来源：http://dali.nwbrower.top/Article/details/gtnikktfhz.html

constexpr int N = 10;
来源：http://dali.yongpay.top/Article/details/gtskbsjfjr.html

[S58] C++：命名空间
来源：http://dali.vqdsnc.cn/Article/details/gtwgndfmvw.html

namespace ns { int f() { return 1; } }
来源：http://dali.daria6918.cn/Article/details/gthrprgapf.html

[S59] C++：静态断言
来源：http://dali.shangyingyoupin.top/Article/details/gtwvyymwut.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvztocalv.html

[S60] C++：遍历并删除元素
来源：http://dali.9152youxi.cn/Article/details/gtintlutdm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yj20258888.top/Article/details/gtvbayrhfb.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gterkvekoh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hongshengwenyu.top/Article/details/gtmowpzqgz.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtfaqdphyg.html

[T01] Kotlin：Hello World
来源：http://dali.nanxinkj.top/Article/details/gtvnanxgth.html

println("Hello")
来源：http://dali.pengpengdd.cyou/Article/details/gthrwbcpww.html

[T02] Kotlin：变量
来源：http://dali.yj20258.top/Article/details/gtxrajzlik.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cashguo.top/Article/details/gtmwdifmsc.html

[T03] Kotlin：字符串模板
来源：http://dali.fengsongda.top/Article/details/gtrewrcxfa.html

"值: $b"
来源：http://dali.9152youxi.cn/Article/details/gtoixiwrfm.html

[T04] Kotlin：空安全
来源：http://dali.nwbrower.top/Article/details/gtlguyqrrn.html

val n: String? = null;  n?.length
来源：http://dali.ehwqpu.com/Article/details/gtnhuehkub.html

[T05] Kotlin：when 表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gtywjymcam.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hongshengwenyu.top/Article/details/gtmlfwpsgj.html

[T06] Kotlin：集合映射
来源：http://dali.gzhubu.top/Article/details/gtyeufumeu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxutzwdqx.html

[T07] Kotlin：集合过滤
来源：http://dali.yangfankeji.com/Article/details/gtjxvjoevp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xuetiantiany.cn/Article/details/gtxscqopdv.html

[T08] Kotlin：数据类
来源：http://dali.hnxiangtu.top/Article/details/gtzbzlsoyn.html

data class User(val name: String, val age: Int)
来源：http://dali.pengpengdd.cyou/Article/details/gtjegmlgbu.html

[T09] Kotlin：扩展函数
来源：http://dali.gzhubu.top/Article/details/gtzlinreai.html

fun String.exclaim() = this + "!"
来源：http://dali.cucudq.cn/Article/details/gtepxuhijc.html

[T10] Kotlin：默认参数
来源：http://dali.jlsjyb.cn/Article/details/gtmzdvqrft.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.nanxinkj.top/Article/details/gtgzovioiv.html

[T11] Kotlin：协程
来源：http://dali.shanyushiyangtech.top/Article/details/gtfoktzkji.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.feifeiyinyue.top/Article/details/gtzfjmdplj.html

[T12] Kotlin：解构声明
来源：http://dali.hnqzz.top/Article/details/gtmdfnrdls.html

val (a, b) = Pair(1, 2)
来源：http://dali.xinyue.icu/Article/details/gtfthwykhp.html

[T13] Kotlin：只读 Map
来源：http://dali.zhengqikj.top/Article/details/gtkvtiekph.html

val m = mapOf("a" to 1)
来源：http://dali.kuanghao11.cn/Article/details/gtnqlbktbc.html

[T14] Kotlin：循环
来源：http://dali.ppjwa.cn/Article/details/gturfdeokp.html

for (i in 1..10) println(i)
来源：http://dali.jqgfzy.top/Article/details/gtwfxiabbq.html

[T15] Kotlin：接口
来源：http://dali.hfpthk.cn/Article/details/gtjkbsadoc.html

interface Shape { fun area(): Double }
来源：http://dali.ppjwa.cn/Article/details/gtpyvibnbp.html

[T16] Swift：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtamiomcpi.html

print("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gteypupmcr.html

[T17] Swift：变量与常量
来源：http://dali.yanxiufei.cn/Article/details/gtgnrvshod.html

var a = 1;  let b = 2
来源：http://dali.yonumen.top/Article/details/gtkyblhotf.html

[T18] Swift：字符串插值
来源：http://dali.hywenlv.cn/Article/details/gtciglgknx.html

"值: \(b)"
来源：http://dali.xuanzx.com/Article/details/gtzovkxzef.html

[T19] Swift：可选绑定
来源：http://dali.bjfxy.top/Article/details/gtxgblgwte.html

if let n = opt { print(n) }
来源：http://dali.hysaishi.cn/Article/details/gtbcuzcrjm.html

[T20] Swift：数组操作
来源：http://dali.ybcxt.top/Article/details/gtncyrubgs.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shuidangran.top/Article/details/gtsbqugwbm.html

[T21] Swift：遍历
来源：http://dali.zhoulong.xyz/Article/details/gtkoomdqjo.html

for x in a { print(x) }
来源：http://dali.aizwys.cn/Article/details/gtvgsxlmbf.html

[T22] Swift：字典
来源：http://dali.xuetiantiany.cn/Article/details/gtezzbnztf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cucudq.cn/Article/details/gthrnfamhs.html

[T23] Swift：函数
来源：http://dali.daxiang520.top/Article/details/gtuoqjnrgl.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.mhx1999.top/Article/details/gtvaamrxyu.html

[T24] Swift：闭包
来源：http://dali.dashuyun.cn/Article/details/gtvvmctyyw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.gzhubu.top/Article/details/gtytxzbveg.html

[T25] Swift：结构体
来源：http://dali.cheryme.top/Article/details/gtkjaivjsi.html

struct P { var x: Int }
来源：http://dali.zycfv.cn/Article/details/gtfmiexryq.html

[T26] Swift：类与重写
来源：http://dali.xziqi.cn/Article/details/gtgghkrdux.html

class A: Base { override func f() {} }
来源：http://dali.zdqjudy.top/Article/details/gtzbdjzpat.html

[T27] Swift：错误处理
来源：http://dali.gaohongyu789.top/Article/details/gtdoscqkqg.html

do { try f() } catch { print(error) }
来源：http://dali.hysaishi.cn/Article/details/gtxiucrdng.html

[T28] Swift：枚举
来源：http://dali.fengsongda.top/Article/details/gtsnfouacw.html

enum Color { case red, green }
来源：http://dali.yueranfly.top/Article/details/gtkxufiraq.html

[T29] Swift：guard 提前返回
来源：http://dali.hongshengwenyu.top/Article/details/gtwbkbzrwo.html

guard let x = opt else { return }
来源：http://dali.zhongyouzk.top/Article/details/gthvfeoehr.html

[T30] Swift：协议
来源：http://dali.yangfankeji.com/Article/details/gtgmuohtkd.html

protocol Shape { func area() -> Double }
来源：http://dali.nwbrower.top/Article/details/gtvighngtw.html

[T31] Lua：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtwafkwykb.html

print("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxkrcydnn.html

[T32] Lua：局部变量
来源：http://dali.cashguo.top/Article/details/gtazhvizfc.html

local a = 1
来源：http://dali.redwolf501.top/Article/details/gtuithenqj.html

[T33] Lua：表（数组）
来源：http://dali.iojbl.cn/Article/details/gtryctojih.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.nanxuanxn.top/Article/details/gtxpxlkcfj.html

[T34] Lua：遍历表
来源：http://dali.nwbrower.top/Article/details/gtyubmcsua.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.wangshuangyany.cn/Article/details/gtxfmydonq.html

[T35] Lua：字典表
来源：http://dali.chenjidiqi.icu/Article/details/gteiwkwzmk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jqgfzy.top/Article/details/gtaevhrtte.html

[T36] Lua：函数
来源：http://dali.sweek.top/Article/details/gtjproaevp.html

function add(a, b) return a + b end
来源：http://dali.cashguo.top/Article/details/gtstqcwshd.html

[T37] Lua：字符串拼接
来源：http://dali.ehwqpu.com/Article/details/gtmuxxpouh.html

"a" .. "b"
来源：http://dali.jqgfzy.top/Article/details/gtpglxmdgd.html

[T38] Lua：条件
来源：http://dali.gotoacloud.top/Article/details/gtmkcxxvuz.html

if x > 0 then print("正") end
来源：http://dali.cdnleiting.top/Article/details/gtvoslgwtm.html

[T39] Lua：模式匹配
来源：http://dali.yangfankeji.com/Article/details/gtpfxcmjlw.html

string.find(s, "%d+")
来源：http://dali.jqgfzy.top/Article/details/gtbeegdbvo.html

[T40] Lua：元表
来源：http://dali.jinqigfzy.top/Article/details/gtnmrxbuss.html

setmetatable({}, { __index = base })
来源：http://dali.ppjwa.cn/Article/details/gtwzeogchq.html

[T41] Perl：Hello World
来源：http://dali.jianghu66.top/Article/details/gtvigqvyeb.html

print "Hello\n";
来源：http://dali.quarkkingdee.top/Article/details/gtlflsyros.html

[T42] Perl：变量类型
来源：http://dali.zhixingplan.top/Article/details/gtjgonzwys.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.andypj.xyz/Article/details/gtophcyfva.html

[T43] Perl：字符串插值
来源：http://dali.nanxinkj.top/Article/details/gtymjgwzsy.html

"值: $a"
来源：http://dali.nanxuanxn.top/Article/details/gtnnpllhmw.html

[T44] Perl：条件
来源：http://dali.yongpay.top/Article/details/gtdiwwppvf.html

if ($a > 0) { print "正"; }
来源：http://dali.gotoacloud.top/Article/details/gtakjztaue.html

[T45] Perl：数组遍历
来源：http://dali.cashguo.top/Article/details/gtncjzwbhh.html

for my $x (@arr) { print $x; }
来源：http://dali.shuidangran.top/Article/details/gtrzkuivmv.html

[T46] Perl：哈希操作
来源：http://dali.cheryme.top/Article/details/gtmjijqzqn.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yj20258888.top/Article/details/gtgigsibeh.html

[T47] Perl：正则捕获
来源：http://dali.jianghu66.top/Article/details/gtymkcujsg.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yanxiufei.cn/Article/details/gtwreavwcc.html

[T48] Perl：正则替换
来源：http://dali.zhiwuduotai.top/Article/details/gtzcwunzyh.html

$s =~ s/old/new/g;
来源：http://dali.daria6918.cn/Article/details/gtyxdtimxl.html

[T49] Perl：函数
来源：http://dali.ydzc1.top/Article/details/gtoqelgvge.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtsscndlta.html

[T50] Perl：逐行读文件
来源：http://dali.c1oappe.top/Article/details/gtukvaqcjj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.nanxuanxn.top/Article/details/gtxunuctcg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yangfankeji.com/Article/details/gtmqbzguzc.html

[T51] Scala：Hello World
来源：http://dali.ydzc1.top/Article/details/gtyugublyb.html

println("Hello")
来源：http://dali.nanxuanxn.top/Article/details/gtomnlzirk.html

[T52] Scala：变量
来源：http://dali.snrcjt.cn/Article/details/gtfvzjoylk.html

val a = 1;  var b = 2
来源：http://dali.xziqi.cn/Article/details/gteglbnnlj.html

[T53] Scala：字符串插值
来源：http://dali.tian-w.cn/Article/details/gtscdsajfm.html

s"值: $b"
来源：http://dali.shuidangran.top/Article/details/gtesmoetjp.html

[T54] Scala：集合映射
来源：http://dali.nwbrower.top/Article/details/gtrncuvoiw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.andypj.xyz/Article/details/gtzdtktlgi.html

[T55] Scala：集合过滤
来源：http://dali.yuxming.cn/Article/details/gtirubvwez.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.cashguo.top/Article/details/gtjgfdlynk.html

[T56] Scala：样例类
来源：http://dali.mhx1999.top/Article/details/gtawcgoxyi.html

case class User(name: String, age: Int)
来源：http://dali.dashuyun.cn/Article/details/gtgjrzcemf.html

[T57] Scala：模式匹配
来源：http://dali.yuanzhike.top/Article/details/gtpcnztohn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.feifeiyinyue.top/Article/details/gtccbhwvvb.html

[T58] Scala：函数定义
来源：http://dali.xinyue.icu/Article/details/gtxbgaqfey.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.quarkkingdee.top/Article/details/gtdadgppdb.html

[T59] Scala：循环
来源：http://dali.ywan-chungtsiang.top/Article/details/gtznpazvte.html

for (i <- 1 to 10) println(i)
来源：http://dali.ehwqpu.com/Article/details/gtnkmpowmd.html

[T60] Scala：折叠
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjrrkjkbd.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jinghuilouyu.cn/Article/details/gtbtcqasxi.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtleoizzcz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtvzhsfiyo.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtifbjqqwb.html


<!-- 参考信息 -->