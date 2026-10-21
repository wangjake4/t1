代发 wailian999

ssh user@host 'uptime'
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdajiltzv.html

[R58] 下载文件
来源：http://dali.yueranfly.top/Article/details/gtxjmipnxj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ehwqpu.com/Article/details/gtmqkzevvj.html

[R59] 发 POST JSON
来源：http://dali.xuetiantiany.cn/Article/details/gtgcdsaggw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.chenzaomai.com/Article/details/gtqxlcexws.html

[R60] 只看 HTTP 状态码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnfwstgug.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yangfankeji.com/Article/details/gtxyotsgxo.html

[R61] 磁盘占用
来源：http://dali.hnqzz.top/Article/details/gtjbbxyytr.html

df -h;  du -sh *
来源：http://dali.shzxlz.cn/Article/details/gtvbtrtdgf.html

[R62] 找最占空间的文件
来源：http://dali.fzhhl.top/Article/details/gtsozcrbha.html

du -ah . | sort -rh | head -10
来源：http://dali.yongpay.top/Article/details/gtggadwpuq.html

[R63] 内存与进程
来源：http://dali.xinyue.icu/Article/details/gtsyicpyth.html

free -h;  ps aux | grep nginx
来源：http://dali.fengsongda.top/Article/details/gtcdriyqyg.html

[R64] 结束进程
来源：http://dali.zhongyouzk.top/Article/details/gtulutgghd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.smart0.xyz/Article/details/gtovagmodi.html

[R65] 查看端口占用
来源：http://dali.andypj.xyz/Article/details/gtjrukudyk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.andypj.xyz/Article/details/gtsbydlezw.html

[R66] 定时任务
来源：http://dali.daria6918.cn/Article/details/gtodcmkseu.html

crontab -e;  crontab -l
来源：http://dali.chenlongwang.top/Article/details/gtllsxlgkq.html

[R67] 生成随机十六进制串
来源：http://dali.0kj1m.cn/Article/details/gtedntzvje.html

openssl rand -hex 16
来源：http://dali.jinghuilouyu.cn/Article/details/gttnzkqcum.html

[R68] 计算文件校验值
来源：http://dali.guowangkeji.top/Article/details/gtpdkrekfv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtmzlbhzus.html

[R69] 生成随机密码
来源：http://dali.xinyue.icu/Article/details/gtiwvwetxg.html

head -c 16 /dev/urandom | base64
来源：http://dali.feifeiyinyue.top/Article/details/gtujocwvyr.html

[R70] 时间戳与互转
来源：http://dali.hnqzz.top/Article/details/gtfeqiagtm.html

date +%s;  date -d @1700000000
来源：http://dali.yonumen.top/Article/details/gtyrozlecc.html

[R71] 日期格式化
来源：http://dali.cucudq.cn/Article/details/gtbhjoyqxf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.nwbrower.top/Article/details/gtlvmcyfnu.html

[R72] 等待端口就绪
来源：http://dali.daxiang520.top/Article/details/gthegleuku.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zycfv.cn/Article/details/gtavyubjle.html

[R73] 分割大日志
来源：http://dali.cdnleiting.top/Article/details/gtcycuevis.html

split -l 1000 big.log part_
来源：http://dali.jianghu66.top/Article/details/gtdmzuwwup.html

[R74] 批量重命名
来源：http://dali.zhongyouzk.top/Article/details/gtjbumleli.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.wangshuangyany.cn/Article/details/gtfcpkuwgi.html

[R75] 导出环境变量
来源：http://dali.316326.xyz/Article/details/gtbgcucqza.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sysykeji.top/Article/details/gtbnaoqxwm.html

[R76] 使用临时文件
来源：http://dali.sufxvd.cn/Article/details/gtsggncfbi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.0kj1m.cn/Article/details/gtigvvukgj.html

[R77] 读取用户输入
来源：http://dali.daxiang520.top/Article/details/gteiyffxjj.html

read -rp "请输入: " ans
来源：http://dali.sxryk.cn/Article/details/gtmltvohyk.html

[R78] 交互式菜单
来源：http://dali.hongshengwenyu.top/Article/details/gttipxelke.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hongshengwenyu.top/Article/details/gtqvrbbjlg.html

[R79] 解析命令行选项
来源：http://dali.yuanzhike.top/Article/details/gtzxigfdnu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ehwqpu.com/Article/details/gttnjbeztb.html

[R80] 查看脚本执行耗时
来源：http://dali.jinghuilouyu.cn/Article/details/gtwwjebzra.html

time ./run.sh
来源：http://dali.shzxlz.cn/Article/details/gtnjnluzjt.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtzwrdzfge.html

S. C / C++ 专题
来源：http://dali.hfpthk.cn/Article/details/gtxqtdgleq.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtjibhzsjv.html

[S01] C：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtxikdfnfy.html

#include <stdio.h>
来源：http://dali.jlsjyb.cn/Article/details/gtkfaimmak.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.daria6918.cn/Article/details/gtybpzkgdy.html

[S02] C：变量与格式化输出
来源：http://dali.cucudq.cn/Article/details/gtvlhehuyr.html

int a = 10; printf("%d\n", a);
来源：http://dali.hongshengwenyu.top/Article/details/gteawntoea.html

[S03] C：读入整数
来源：http://dali.chenzaomai.com/Article/details/gtkqrazciu.html

int x; scanf("%d", &x);
来源：http://dali.jiagoushi.top/Article/details/gtylhwfale.html

[S04] C：字符串复制
来源：http://dali.hnqzz.top/Article/details/gtgwfqraie.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yj20258888.top/Article/details/gtsfjvhekt.html

[S05] C：字符串长度
来源：http://dali.tianlin.xyz/Article/details/gtlaructmf.html

strlen(s)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlgilliqd.html

[S06] C：字符串比较
来源：http://dali.nanxuanxn.top/Article/details/gtjpzqfcpz.html

strcmp(a, b) == 0
来源：http://dali.guowangkeji.top/Article/details/gtsjfztvmi.html

[S07] C：数组遍历求和
来源：http://dali.daxiang520.top/Article/details/gtgjujwcdt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.kuanghao11.cn/Article/details/gtqoxjbzln.html

[S08] C：动态内存分配与释放
来源：http://dali.ehwqpu.com/Article/details/gtljogbvee.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jiagoushi.top/Article/details/gtgkldwwdn.html

[S09] C：结构体定义与初始化
来源：http://dali.hfpthk.cn/Article/details/gtqeetsvon.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ivvv.top/Article/details/gtsgkpthqu.html

[S10] C：指针与解引用
来源：http://dali.kuanghao11.cn/Article/details/gtdncphvhf.html

int *p = &a;  *p = 5;
来源：http://dali.meibo888.top/Article/details/gtclnpwmog.html

[S11] C：逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gttvhocopa.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jlsjyb.cn/Article/details/gtyngqcrpk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hongshengwenyu.top/Article/details/gttuxqsfsz.html

fclose(f);
来源：http://dali.zdqjudy.top/Article/details/gtiixbjfiw.html

[S12] C：写文件
来源：http://dali.jinqigufen.top/Article/details/gtjkzcjplf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.meibo888.top/Article/details/gtkthxhxdh.html

[S13] C：宏定义
来源：http://dali.dianchejie.cn/Article/details/gtrbkvcqig.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhongyouzk.top/Article/details/gtqwfldlps.html

[S14] C：枚举
来源：http://dali.gaohongyu789.top/Article/details/gtnvqrocfa.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhixingplan.top/Article/details/gtyclzkefy.html

[S15] C：类型转换
来源：http://dali.jinghuilouyu.cn/Article/details/gtkmmcpllm.html

(double) a / b
来源：http://dali.daria6918.cn/Article/details/gtlojagnyd.html

[S16] C：位操作置位
来源：http://dali.andypj.xyz/Article/details/gtdmvdjmxl.html

x |= (1 << 3);
来源：http://dali.gzhubu.top/Article/details/gtzpueeofo.html

[S17] C：安全拼接字符串
来源：http://dali.hysaishi.cn/Article/details/gtkxgipreu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.iojbl.cn/Article/details/gtvmkxutjs.html

[S18] C：命令行参数
来源：http://dali.cashguo.top/Article/details/gtzimeunde.html

int main(int argc, char **argv)
来源：http://dali.jqgfzy.top/Article/details/gtlzxwsjcs.html

[S19] C：快速排序
来源：http://dali.cdnleiting.top/Article/details/gtcccvxwbs.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinqigfzy.top/Article/details/gtbiokcbch.html

[S20] C：二分查找
来源：http://dali.xziqi.cn/Article/details/gtxtooucrg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xylfe.cn/Article/details/gtlekcxjxk.html

[S21] C：字符类别判断
来源：http://dali.aibaodan.cn/Article/details/gtirfdvcas.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.meibo888.top/Article/details/gtijaypddh.html

[S22] C：字符串转数字
来源：http://dali.daxiang520.top/Article/details/gttniaitza.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jianghu66.top/Article/details/gtuokpuplw.html

[S23] C：随机数
来源：http://dali.nanxuanxn.top/Article/details/gtfiibrpra.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cdnleiting.top/Article/details/gtjbkedaqg.html

[S24] C：获取本地时间
来源：http://dali.chenzaomai.com/Article/details/gthhakurjb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.svipenyu.cn/Article/details/gtaybdivcg.html

[S25] C：内存拷贝
来源：http://dali.zhongyouzk.top/Article/details/gtnrqxgqqe.html

memcpy(dst, src, n);
来源：http://dali.xylfe.cn/Article/details/gtjkfbjukj.html

[S26] C：内存清零
来源：http://dali.ppjwa.cn/Article/details/gtrxgfqlut.html

memset(a, 0, sizeof a);
来源：http://dali.cheryme.top/Article/details/gtupeyhlvr.html

[S27] C：定义常量
来源：http://dali.gzhubu.top/Article/details/gtaegyytka.html

const double PI = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gtdmjzwwuz.html

[S28] C：静态变量
来源：http://dali.nwbrower.top/Article/details/gtxmmwqinh.html

static int counter = 0;
来源：http://dali.yuxming.cn/Article/details/gtheiickcs.html

[S29] C：变参函数
来源：http://dali.daxiang520.top/Article/details/gtxzexdxcv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.quarkkingdee.top/Article/details/gtpsbpqmbf.html

[S30] C：头文件保护
来源：http://dali.gogol.net.cn/Article/details/gtctrxptry.html

#ifndef X_H
来源：http://dali.daria6918.cn/Article/details/gtygzcgyte.html

#define X_H
来源：http://dali.316326.xyz/Article/details/gtjvqectbx.html

#endif
来源：http://dali.guowangkeji.top/Article/details/gtvtscpfqi.html

[S31] C++：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtkalcxqda.html

#include <iostream>
来源：http://dali.iojbl.cn/Article/details/gtpykyaxxs.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtjyntbuon.html

[S32] C++：字符串
来源：http://dali.ehwqpu.com/Article/details/gtvqzkrgwh.html

std::string s = "hi";  s += "!";
来源：http://dali.xziqi.cn/Article/details/gtosjchtfx.html

[S33] C++：vector 增删
来源：http://dali.quarkkingdee.top/Article/details/gtcqdpjvkb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.9152youxi.cn/Article/details/gtqwuwgtaw.html

[S34] C++：遍历 vector
来源：http://dali.chenlongwang.top/Article/details/gtbykfbbxi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.wangshuangyany.cn/Article/details/gtsxsgrjre.html

[S35] C++：map
来源：http://dali.redwolf501.top/Article/details/gtmfvsykof.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gtgngbckve.html

[S36] C++：unordered_map
来源：http://dali.hnqzz.top/Article/details/gtlefpqfqs.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.birdmap.top/Article/details/gtqoadmsof.html

[S37] C++：set
来源：http://dali.nwbrower.top/Article/details/gtcqhceobs.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cheryme.top/Article/details/gtxfjfeaki.html

[S38] C++：排序
来源：http://dali.yvedp.cn/Article/details/gtfyuolbqk.html

std::sort(v.begin(), v.end());
来源：http://dali.sufxvd.cn/Article/details/gtdshlvoeu.html

[S39] C++：自定义比较器排序
来源：http://dali.0kj1m.cn/Article/details/gtzxgtqpaf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ppjwa.cn/Article/details/gtscnivude.html

[S40] C++：查找元素
来源：http://dali.yanxiufei.cn/Article/details/gttnkwtjmv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.daxiang520.top/Article/details/gtrcmvvwoj.html

[S41] C++：类与构造函数
来源：http://dali.zhixingplan.top/Article/details/gtpqkoxhuw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinghuilouyu.cn/Article/details/gtkueptzjs.html

[S42] C++：继承与虚函数
来源：http://dali.tianlin.xyz/Article/details/gtwnavcjee.html

class B : public Base { public: void f() override {} };
来源：http://dali.nanxinkj.top/Article/details/gtcvrewxbm.html

[S43] C++：智能指针
来源：http://dali.xinyue.icu/Article/details/gtoqdvqaof.html

auto p = std::make_unique<int>(5);
来源：http://dali.jyoumei.cn/Article/details/gtazvhosei.html

[S44] C++：引用传参
来源：http://dali.yongpay.top/Article/details/gtetydxjmo.html

void inc(int &x) { ++x; }
来源：http://dali.gaohongyu789.top/Article/details/gturfsoqvy.html

[S45] C++：lambda
来源：http://dali.daxiang520.top/Article/details/gtmfkebcyt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nanxinkj.top/Article/details/gtbbsbedyd.html

[S46] C++：函数模板
来源：http://dali.xinyue.icu/Article/details/gtirzovoxc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.quarkkingdee.top/Article/details/gttrcheqwu.html

[S47] C++：结构化绑定遍历
来源：http://dali.haohaochexian.top/Article/details/gtlecdqqur.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.andypj.xyz/Article/details/gtvimofsav.html

[S48] C++：逐行读文件
来源：http://dali.jlsjyb.cn/Article/details/gtbvgnxmrj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yuanzhike.top/Article/details/gtfovgkbih.html

while (std::getline(in, line)) { }
来源：http://dali.hfpthk.cn/Article/details/gtiojlbbza.html

[S49] C++：写文件
来源：http://dali.sufxvd.cn/Article/details/gthmjvefgr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.chenlongwang.top/Article/details/gtxcypaiqb.html

[S50] C++：格式化数字
来源：http://dali.vqdsnc.cn/Article/details/gtkunbmtfj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gtoaabtwlh.html

[S51] C++：显式类型转换
来源：http://dali.jyoumei.cn/Article/details/gtljhoecng.html

static_cast<double>(a) / b
来源：http://dali.shangyingyoupin.top/Article/details/gthudzqgmy.html

[S52] C++：const 与 noexcept
来源：http://dali.kuanghao11.cn/Article/details/gttgfgrvmq.html

int size() const noexcept { return n_; }
来源：http://dali.yvedp.cn/Article/details/gtquqhqxyu.html

[S53] C++：移动语义
来源：http://dali.ivvv.top/Article/details/gtbootkwka.html

std::vector<int> w = std::move(v);
来源：http://dali.zhixingplan.top/Article/details/gtikrfvzym.html

[S54] C++：异常处理
来源：http://dali.tian-w.cn/Article/details/gtmhfpbfmx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xuanzx.com/Article/details/gtbspijuzg.html

[S55] C++：结构化绑定
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmqxjwmqv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.bjfxy.top/Article/details/gtpqjpyjme.html

[S56] C++：optional
来源：http://dali.iojbl.cn/Article/details/gtrurnkerz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinqigufen.top/Article/details/gtmqwpixsm.html

[S57] C++：编译期常量
来源：http://dali.zhijiandao.cn/Article/details/gtvdscxtkp.html

constexpr int N = 10;
来源：http://dali.feifeiyinyue.top/Article/details/gtuzljwrav.html

[S58] C++：命名空间
来源：http://dali.andypj.xyz/Article/details/gtmdjbviae.html

namespace ns { int f() { return 1; } }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqzjjcywx.html

[S59] C++：静态断言
来源：http://dali.yanxiufei.cn/Article/details/gttiloipck.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jlsjyb.cn/Article/details/gttbntbpvl.html

[S60] C++：遍历并删除元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtflfawuqw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gotoacloud.top/Article/details/gtizssmzqt.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtbnjvcczi.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhixingplan.top/Article/details/gtaxmkxnbj.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtxbswbwih.html

[T01] Kotlin：Hello World
来源：http://dali.zycfv.cn/Article/details/gtfzusrxns.html

println("Hello")
来源：http://dali.haohaochexian.top/Article/details/gtmywbyvto.html

[T02] Kotlin：变量
来源：http://dali.wangdashe.top/Article/details/gtktuntvwm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvwevnqac.html

[T03] Kotlin：字符串模板
来源：http://dali.yuanzhike.top/Article/details/gtgiazfovn.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gtkligwzcc.html

[T04] Kotlin：空安全
来源：http://dali.guowangkeji.top/Article/details/gtpgocjxzn.html

val n: String? = null;  n?.length
来源：http://dali.hammf.cn/Article/details/gthdydxtfh.html

[T05] Kotlin：when 表达式
来源：http://dali.zhixingplan.top/Article/details/gteptpkstk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sxryk.cn/Article/details/gtrqgegrgt.html

[T06] Kotlin：集合映射
来源：http://dali.ybcxt.top/Article/details/gtlcqzzkgo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yuanzhike.top/Article/details/gtpsgkljgl.html

[T07] Kotlin：集合过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtycvstros.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.feifeiyinyue.top/Article/details/gtczyajofe.html

[T08] Kotlin：数据类
来源：http://dali.ywan-chungtsiang.top/Article/details/gtihwjrszh.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gtartccujb.html

[T09] Kotlin：扩展函数
来源：http://dali.hfpthk.cn/Article/details/gtvhcbnwhd.html

fun String.exclaim() = this + "!"
来源：http://dali.hywenlv.cn/Article/details/gttcmldyhk.html

[T10] Kotlin：默认参数
来源：http://dali.ydzc1.top/Article/details/gtafqtjzfw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhongyouzk.top/Article/details/gtasssplqu.html

[T11] Kotlin：协程
来源：http://dali.iojbl.cn/Article/details/gtusgtihzi.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jqgfzy.top/Article/details/gtsgwdmjxm.html

[T12] Kotlin：解构声明
来源：http://dali.ydzc1.top/Article/details/gtkprwobwj.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gtmxgyaccz.html

[T13] Kotlin：只读 Map
来源：http://dali.pycfn.com/Article/details/gtcglppyie.html

val m = mapOf("a" to 1)
来源：http://dali.iojbl.cn/Article/details/gtjnitckuw.html

[T14] Kotlin：循环
来源：http://dali.jqgfzy.top/Article/details/gtrcdftkea.html

for (i in 1..10) println(i)
来源：http://dali.wangshuangyany.cn/Article/details/gttzyjhyyl.html

[T15] Kotlin：接口
来源：http://dali.feifeiyinyue.top/Article/details/gtjbgazpay.html

interface Shape { fun area(): Double }
来源：http://dali.zhoulong.xyz/Article/details/gtmwfyxkqz.html

[T16] Swift：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtzvltvyvy.html

print("Hello")
来源：http://dali.andypj.xyz/Article/details/gtfgwqezdu.html

[T17] Swift：变量与常量
来源：http://dali.guowangkeji.top/Article/details/gtgzimssuh.html

var a = 1;  let b = 2
来源：http://dali.zhiwuduotai.top/Article/details/gtkgwdvrxb.html

[T18] Swift：字符串插值
来源：http://dali.tian-w.cn/Article/details/gtuouxidya.html

"值: \(b)"
来源：http://dali.yanxiufei.cn/Article/details/gtsszgeqwk.html

[T19] Swift：可选绑定
来源：http://dali.fzhhl.top/Article/details/gtyigqrimi.html

if let n = opt { print(n) }
来源：http://dali.kuanghao11.cn/Article/details/gtxihsktoj.html

[T20] Swift：数组操作
来源：http://dali.xziqi.cn/Article/details/gtrxmvkfnn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.meibo888.top/Article/details/gtikedfwwl.html

[T21] Swift：遍历
来源：http://dali.pengpengdd.cyou/Article/details/gtxrymcrwr.html

for x in a { print(x) }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnhwdknrj.html

[T22] Swift：字典
来源：http://dali.yanxiufei.cn/Article/details/gtzbwwchsh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.chenjidiqi.icu/Article/details/gtaoexsask.html

[T23] Swift：函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtripcchie.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.quarkkingdee.top/Article/details/gttmqgzogt.html

[T24] Swift：闭包
来源：http://dali.feifeiyinyue.top/Article/details/gtknuupzds.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiulxmbdb.html

[T25] Swift：结构体
来源：http://dali.pengpengdd.cyou/Article/details/gtavnteylt.html

struct P { var x: Int }
来源：http://dali.gzhubu.top/Article/details/gtpzzyxfti.html

[T26] Swift：类与重写
来源：http://dali.hfpthk.cn/Article/details/gtqfjdjdfg.html

class A: Base { override func f() {} }
来源：http://dali.jinghuilouyu.cn/Article/details/gtbqvdfhnj.html

[T27] Swift：错误处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoereakau.html

do { try f() } catch { print(error) }
来源：http://dali.chenjidiqi.icu/Article/details/gtinysuskp.html

[T28] Swift：枚举
来源：http://dali.zhiwuduotai.top/Article/details/gtryhdhoni.html

enum Color { case red, green }
来源：http://dali.jyoumei.cn/Article/details/gtfklylane.html

[T29] Swift：guard 提前返回
来源：http://dali.cheryme.top/Article/details/gtvbsljkpa.html

guard let x = opt else { return }
来源：http://dali.9152youxi.cn/Article/details/gtgfvpxpqm.html

[T30] Swift：协议
来源：http://dali.yuxming.cn/Article/details/gtqcofmgqf.html

protocol Shape { func area() -> Double }
来源：http://dali.shuidangran.top/Article/details/gtzuobalno.html

[T31] Lua：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtrjnxucfh.html

print("Hello")
来源：http://dali.hammf.cn/Article/details/gtwergojxc.html

[T32] Lua：局部变量
来源：http://dali.andypj.xyz/Article/details/gttgnehyqc.html

local a = 1
来源：http://dali.pycfn.com/Article/details/gtyadbaaev.html

[T33] Lua：表（数组）
来源：http://dali.jqgfzy.top/Article/details/gtkthfrdmo.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jlsjyb.cn/Article/details/gtazfdyfhf.html

[T34] Lua：遍历表
来源：http://dali.316326.xyz/Article/details/gtnhblspit.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jinqigfzy.top/Article/details/gtizxwcpnv.html

[T35] Lua：字典表
来源：http://dali.pycfn.com/Article/details/gtdcwlrksi.html

local d = { a = 1 };  d.b = 2
来源：http://dali.birdmap.top/Article/details/gtobzxunka.html

[T36] Lua：函数
来源：http://dali.sufxvd.cn/Article/details/gtftkcvcfh.html

function add(a, b) return a + b end
来源：http://dali.gogol.net.cn/Article/details/gtbdfmpyxy.html

[T37] Lua：字符串拼接
来源：http://dali.jinqigufen.top/Article/details/gtrnpdoael.html

"a" .. "b"
来源：http://dali.cqqwz.cn/Article/details/gtvpwlfoyk.html

[T38] Lua：条件
来源：http://dali.dashuyun.cn/Article/details/gtfqpgxxog.html

if x > 0 then print("正") end
来源：http://dali.jlsjyb.cn/Article/details/gtsfitesqa.html

[T39] Lua：模式匹配
来源：http://dali.yueranfly.top/Article/details/gtuppsnwfe.html

string.find(s, "%d+")
来源：http://dali.zdqjudy.top/Article/details/gtyjafmamm.html

[T40] Lua：元表
来源：http://dali.gotoacloud.top/Article/details/gtfkovxigg.html

setmetatable({}, { __index = base })
来源：http://dali.zhengqikj.top/Article/details/gtgxbqvblt.html

[T41] Perl：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtzqilickj.html

print "Hello\n";
来源：http://dali.kuanghao11.cn/Article/details/gtmypqshpf.html

[T42] Perl：变量类型
来源：http://dali.hnqzz.top/Article/details/gtftdzweeo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.shzxlz.cn/Article/details/gtfotiabmb.html

[T43] Perl：字符串插值
来源：http://dali.ehwqpu.com/Article/details/gtdoyhiamf.html

"值: $a"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtojejdbsx.html

[T44] Perl：条件
来源：http://dali.cucudq.cn/Article/details/gtwqoonwlm.html

if ($a > 0) { print "正"; }
来源：http://dali.hnxiangtu.top/Article/details/gtipujdmet.html

[T45] Perl：数组遍历
来源：http://dali.snrcjt.cn/Article/details/gtcnfpdrrh.html

for my $x (@arr) { print $x; }
来源：http://dali.zhongyouzk.top/Article/details/gtnufncqmx.html

[T46] Perl：哈希操作
来源：http://dali.sysykeji.top/Article/details/gttydupzuf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.sweek.top/Article/details/gthdlgzdqe.html

[T47] Perl：正则捕获
来源：http://dali.gzhubu.top/Article/details/gtsrqeivas.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.mhx1999.top/Article/details/gtiphwdbat.html

[T48] Perl：正则替换
来源：http://dali.zhoulong.xyz/Article/details/gtvyxehvit.html

$s =~ s/old/new/g;
来源：http://dali.shzxlz.cn/Article/details/gtvndtbrws.html

[T49] Perl：函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtuladnchp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.tanke756.top/Article/details/gtgpihsdck.html

[T50] Perl：逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gtkyssyyzx.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hfpthk.cn/Article/details/gtalijnzlp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.redwolf501.top/Article/details/gtohojrmty.html

[T51] Scala：Hello World
来源：http://dali.xylfe.cn/Article/details/gtdigigftc.html

println("Hello")
来源：http://dali.cdnleiting.top/Article/details/gtvxpjtwbp.html

[T52] Scala：变量
来源：http://dali.hnqzz.top/Article/details/gtxxuuwmyj.html

val a = 1;  var b = 2
来源：http://dali.gogol.net.cn/Article/details/gtcfizgson.html

[T53] Scala：字符串插值
来源：http://dali.aizwys.cn/Article/details/gttkvcnmie.html

s"值: $b"
来源：http://dali.meibo888.top/Article/details/gtawgveddc.html

[T54] Scala：集合映射
来源：http://dali.sxryk.cn/Article/details/gtbsmuqxtw.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ivvv.top/Article/details/gtrytypgec.html

[T55] Scala：集合过滤
来源：http://dali.havefunace.top/Article/details/gtxnojwydz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.nanxuanxn.top/Article/details/gtcphuqezb.html

[T56] Scala：样例类
来源：http://dali.yueranfly.top/Article/details/gtakinzrnq.html

case class User(name: String, age: Int)
来源：http://dali.jqgufenzy.top/Article/details/gtflosvvrr.html

[T57] Scala：模式匹配
来源：http://dali.guannengcc.top/Article/details/gtvpwlmxwk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.redwolf501.top/Article/details/gtypuogkmo.html

[T58] Scala：函数定义
来源：http://dali.gotoacloud.top/Article/details/gtqyxticaf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.c1oappe.top/Article/details/gttgpcwigs.html

[T59] Scala：循环
来源：http://dali.xinyue.icu/Article/details/gtevcseksv.html

for (i <- 1 to 10) println(i)
来源：http://dali.hongshengwenyu.top/Article/details/gtwzdxyawv.html

[T60] Scala：折叠
来源：http://dali.zhongyouzk.top/Article/details/gtndwrtdyj.html


<!-- 参考信息 -->