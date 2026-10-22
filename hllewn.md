代发 wailian999

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cqqwz.cn/Article/details/gtqlmqvvxq.html

[R50] awk 求和
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmiipdczh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.pycfn.com/Article/details/gtiekfzcll.html

[R51] 排序去重取前几
来源：http://dali.fengsongda.top/Article/details/gtxtwojikj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cdnleiting.top/Article/details/gtpogvlzwb.html

[R52] 统计行数
来源：http://dali.chenlongwang.top/Article/details/gtgjgppxsj.html

wc -l a.txt
来源：http://dali.haohaochexian.top/Article/details/gtdrhsvwjk.html

[R53] 查看文件头与实时尾
来源：http://dali.jlsjyb.cn/Article/details/gtushkzctc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.fengsongda.top/Article/details/gtijpaxpno.html

[R54] 比较两个文件
来源：http://dali.shuidangran.top/Article/details/gtjetfcixm.html

diff a.txt b.txt
来源：http://dali.zhixingplan.top/Article/details/gtrfhpcjkr.html

[R55] 压缩与解压
来源：http://dali.kuanghao11.cn/Article/details/gteuhsrbqo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.smart0.xyz/Article/details/gtrdpfydxq.html

[R56] 远程拷贝
来源：http://dali.shzxlz.cn/Article/details/gtygzgjfhf.html

scp file user@host:/path/
来源：http://dali.zdqjudy.top/Article/details/gtndnpiejs.html

[R57] 远程执行命令
来源：http://dali.jiagoushi.top/Article/details/gtepbpzdvw.html

ssh user@host 'uptime'
来源：http://dali.jqgufenzy.top/Article/details/gtxdheablp.html

[R58] 下载文件
来源：http://dali.fzhhl.top/Article/details/gtyuxxawrh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yvedp.cn/Article/details/gtxubfemsq.html

[R59] 发 POST JSON
来源：http://dali.cashguo.top/Article/details/gtvtqdrhrc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xylfe.cn/Article/details/gtgiouozdk.html

[R60] 只看 HTTP 状态码
来源：http://dali.jianghu66.top/Article/details/gtuhdpmtmt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yj20258.top/Article/details/gtuptivdxy.html

[R61] 磁盘占用
来源：http://dali.cheryme.top/Article/details/gtfoarxfqv.html

df -h;  du -sh *
来源：http://dali.xinyue.icu/Article/details/gtxavnyltl.html

[R62] 找最占空间的文件
来源：http://dali.hfpthk.cn/Article/details/gtvnicalrh.html

du -ah . | sort -rh | head -10
来源：http://dali.dashuyun.cn/Article/details/gtorpouswp.html

[R63] 内存与进程
来源：http://dali.zhoulong.xyz/Article/details/gtnkykgnfy.html

free -h;  ps aux | grep nginx
来源：http://dali.wangdashe.top/Article/details/gtpajxsubl.html

[R64] 结束进程
来源：http://dali.shangyingyoupin.top/Article/details/gtootqgtrx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.chenzaomai.com/Article/details/gthzkaekmr.html

[R65] 查看端口占用
来源：http://dali.shanyushiyangtech.top/Article/details/gtmsnaqixh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yuanzhike.top/Article/details/gtshrmwkme.html

[R66] 定时任务
来源：http://dali.316326.xyz/Article/details/gtngohguom.html

crontab -e;  crontab -l
来源：http://dali.jinqigufen.top/Article/details/gtonwjszme.html

[R67] 生成随机十六进制串
来源：http://dali.pycfn.com/Article/details/gtmmksebuj.html

openssl rand -hex 16
来源：http://dali.hfpthk.cn/Article/details/gtgnfnrjok.html

[R68] 计算文件校验值
来源：http://dali.redwolf501.top/Article/details/gthtgjmcgz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yueranfly.top/Article/details/gtififgtrx.html

[R69] 生成随机密码
来源：http://dali.zdqjudy.top/Article/details/gthmwyxusm.html

head -c 16 /dev/urandom | base64
来源：http://dali.hongshengwenyu.top/Article/details/gtizjnyhpc.html

[R70] 时间戳与互转
来源：http://dali.yueranfly.top/Article/details/gtwxwceahz.html

date +%s;  date -d @1700000000
来源：http://dali.jqgfzy.top/Article/details/gtivzdanyd.html

[R71] 日期格式化
来源：http://dali.hysaishi.cn/Article/details/gtdcqqrwtw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.316326.xyz/Article/details/gtpeedbpgs.html

[R72] 等待端口就绪
来源：http://dali.hongshengwenyu.top/Article/details/gtbkhzlzyn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ppjwa.cn/Article/details/gtesmjwjpt.html

[R73] 分割大日志
来源：http://dali.xylfe.cn/Article/details/gtlnznuhvx.html

split -l 1000 big.log part_
来源：http://dali.nanxinkj.top/Article/details/gtjlkwmtvy.html

[R74] 批量重命名
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnziwxalk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.aizwys.cn/Article/details/gteitofmno.html

[R75] 导出环境变量
来源：http://dali.jianghu66.top/Article/details/gtrfoppekc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhengqikj.top/Article/details/gtgvgautip.html

[R76] 使用临时文件
来源：http://dali.shangyingyoupin.top/Article/details/gtayhkqahr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ydzc1.top/Article/details/gttmfxibax.html

[R77] 读取用户输入
来源：http://dali.sysykeji.top/Article/details/gtgxajeneo.html

read -rp "请输入: " ans
来源：http://dali.cashguo.top/Article/details/gtrnivuspp.html

[R78] 交互式菜单
来源：http://dali.aibaodan.cn/Article/details/gtgasxiizn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.guowangkeji.top/Article/details/gtjvhqfonm.html

[R79] 解析命令行选项
来源：http://dali.fengsongda.top/Article/details/gtfjciuvmi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cheryme.top/Article/details/gtuafwxcca.html

[R80] 查看脚本执行耗时
来源：http://dali.0kj1m.cn/Article/details/gtzyyzunpf.html

time ./run.sh
来源：http://dali.snrcjt.cn/Article/details/gtlmictbkg.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmruzgisp.html

S. C / C++ 专题
来源：http://dali.meibo888.top/Article/details/gtntfhorso.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtqfpeucvs.html

[S01] C：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtjtbubhwu.html

#include <stdio.h>
来源：http://dali.hammf.cn/Article/details/gtvokctpua.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xuanzx.com/Article/details/gtlfvynqiy.html

[S02] C：变量与格式化输出
来源：http://dali.jqgfzy.top/Article/details/gtczduxbec.html

int a = 10; printf("%d\n", a);
来源：http://dali.ppjwa.cn/Article/details/gtgqhwnbsy.html

[S03] C：读入整数
来源：http://dali.jianghu66.top/Article/details/gtnhonpfqk.html

int x; scanf("%d", &x);
来源：http://dali.yongpay.top/Article/details/gttwkovhrz.html

[S04] C：字符串复制
来源：http://dali.ybcxt.top/Article/details/gthzuuzluv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jlsjyb.cn/Article/details/gteilnipkh.html

[S05] C：字符串长度
来源：http://dali.snrcjt.cn/Article/details/gtdybrupmx.html

strlen(s)
来源：http://dali.gotoacloud.top/Article/details/gttzavsvxt.html

[S06] C：字符串比较
来源：http://dali.xuetiantiany.cn/Article/details/gtrbjmuxak.html

strcmp(a, b) == 0
来源：http://dali.cdnleiting.top/Article/details/gtewueuooj.html

[S07] C：数组遍历求和
来源：http://dali.ybcxt.top/Article/details/gtjpofjrle.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jianghu66.top/Article/details/gtvzshnmfv.html

[S08] C：动态内存分配与释放
来源：http://dali.cqqwz.cn/Article/details/gttchyhcfu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.wangshuangyany.cn/Article/details/gtobnzegzd.html

[S09] C：结构体定义与初始化
来源：http://dali.ydzc1.top/Article/details/gtiuxjtkvj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhiwuduotai.top/Article/details/gtblnusdqw.html

[S10] C：指针与解引用
来源：http://dali.hfpthk.cn/Article/details/gtfofdczwm.html

int *p = &a;  *p = 5;
来源：http://dali.hnqzz.top/Article/details/gtdayhtsen.html

[S11] C：逐行读文件
来源：http://dali.yueranfly.top/Article/details/gtntzhbgyo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhongyouzk.top/Article/details/gtvxcztymp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.havefunace.top/Article/details/gtyqrllhkb.html

fclose(f);
来源：http://dali.yongpay.top/Article/details/gtqyfcjadn.html

[S12] C：写文件
来源：http://dali.yvedp.cn/Article/details/gtwodjzfwu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.fzhhl.top/Article/details/gtzguyxjmg.html

[S13] C：宏定义
来源：http://dali.smart0.xyz/Article/details/gtqumxtvfz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xinyue.icu/Article/details/gttkmehgrw.html

[S14] C：枚举
来源：http://dali.ybcxt.top/Article/details/gtvefqltkm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jlsjyb.cn/Article/details/gtmksgbtwi.html

[S15] C：类型转换
来源：http://dali.aibaodan.cn/Article/details/gtrjromikj.html

(double) a / b
来源：http://dali.haohaochexian.top/Article/details/gttlpkxcbj.html

[S16] C：位操作置位
来源：http://dali.havefunace.top/Article/details/gtdqkngvup.html

x |= (1 << 3);
来源：http://dali.shzxlz.cn/Article/details/gtdwzyodyc.html

[S17] C：安全拼接字符串
来源：http://dali.9152youxi.cn/Article/details/gthqbftwen.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhengqikj.top/Article/details/gtfzppxpwo.html

[S18] C：命令行参数
来源：http://dali.jinqigufen.top/Article/details/gtqmmqfzom.html

int main(int argc, char **argv)
来源：http://dali.yangfankeji.com/Article/details/gtegahgthu.html

[S19] C：快速排序
来源：http://dali.pengpengdd.cyou/Article/details/gtaadwxyww.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yuanzhike.top/Article/details/gtwddqvonz.html

[S20] C：二分查找
来源：http://dali.nanxinkj.top/Article/details/gtuuyctpze.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cdnleiting.top/Article/details/gtubgrtkbr.html

[S21] C：字符类别判断
来源：http://dali.hnxiangtu.top/Article/details/gteymryyoe.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ydzc1.top/Article/details/gtpxmmoabd.html

[S22] C：字符串转数字
来源：http://dali.dashuyun.cn/Article/details/gtevmiovce.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ehwqpu.com/Article/details/gtxgebxsdz.html

[S23] C：随机数
来源：http://dali.aizwys.cn/Article/details/gtkaiojhqw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.kuanghao11.cn/Article/details/gthcyuispa.html

[S24] C：获取本地时间
来源：http://dali.xziqi.cn/Article/details/gtwpmzwasm.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zdqjudy.top/Article/details/gteebkfmjj.html

[S25] C：内存拷贝
来源：http://dali.316326.xyz/Article/details/gtzmkzwhwf.html

memcpy(dst, src, n);
来源：http://dali.gaohongyu789.top/Article/details/gtayxjkgwv.html

[S26] C：内存清零
来源：http://dali.chenjidiqi.icu/Article/details/gtvtjjoyoq.html

memset(a, 0, sizeof a);
来源：http://dali.nanxuanxn.top/Article/details/gtogpwblqv.html

[S27] C：定义常量
来源：http://dali.zhengqikj.top/Article/details/gtjhldjqug.html

const double PI = 3.14159;
来源：http://dali.aizwys.cn/Article/details/gtkcoubodd.html

[S28] C：静态变量
来源：http://dali.yonumen.top/Article/details/gtscercunr.html

static int counter = 0;
来源：http://dali.hnxiangtu.top/Article/details/gtdopuwavm.html

[S29] C：变参函数
来源：http://dali.aizwys.cn/Article/details/gtyxshwovw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.smart0.xyz/Article/details/gtgmztottd.html

[S30] C：头文件保护
来源：http://dali.snrcjt.cn/Article/details/gtklxsqkqm.html

#ifndef X_H
来源：http://dali.tianlin.xyz/Article/details/gtxncerkwl.html

#define X_H
来源：http://dali.cheryme.top/Article/details/gtbszdjmnl.html

#endif
来源：http://dali.yj20258888.top/Article/details/gtxoldrftf.html

[S31] C++：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtfxmfzgar.html

#include <iostream>
来源：http://dali.zhaomingkeji.xyz/Article/details/gtexrhwtkn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xuanzx.com/Article/details/gtcaxsciir.html

[S32] C++：字符串
来源：http://dali.nwbrower.top/Article/details/gtrnvoyamt.html

std::string s = "hi";  s += "!";
来源：http://dali.chenjidiqi.icu/Article/details/gthoxpoxup.html

[S33] C++：vector 增删
来源：http://dali.daria6918.cn/Article/details/gturbnyort.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yangfankeji.com/Article/details/gtulfqynml.html

[S34] C++：遍历 vector
来源：http://dali.yvedp.cn/Article/details/gtgktwmemy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yangfankeji.com/Article/details/gtqrspjcqe.html

[S35] C++：map
来源：http://dali.ydzc1.top/Article/details/gtvymdfvtx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ivvv.top/Article/details/gtfxeaymxs.html

[S36] C++：unordered_map
来源：http://dali.cashguo.top/Article/details/gtzmoefbwv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nwbrower.top/Article/details/gtjjaqektk.html

[S37] C++：set
来源：http://dali.hnxiangtu.top/Article/details/gtihvldoye.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.fzhhl.top/Article/details/gtrjgymdwj.html

[S38] C++：排序
来源：http://dali.zhixingplan.top/Article/details/gtuckxcwir.html

std::sort(v.begin(), v.end());
来源：http://dali.daxiang520.top/Article/details/gttwxrsbhl.html

[S39] C++：自定义比较器排序
来源：http://dali.yanxiufei.cn/Article/details/gtqaxsfsue.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yuxming.cn/Article/details/gtalewrsnk.html

[S40] C++：查找元素
来源：http://dali.guannengcc.top/Article/details/gtcyeliudd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.chenlongwang.top/Article/details/gtfuiiyyzu.html

[S41] C++：类与构造函数
来源：http://dali.aizwys.cn/Article/details/gtaikrgtnd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ybcxt.top/Article/details/gtaraayypl.html

[S42] C++：继承与虚函数
来源：http://dali.haohaochexian.top/Article/details/gtlbjjaoht.html

class B : public Base { public: void f() override {} };
来源：http://dali.yongpay.top/Article/details/gtktqhkiuj.html

[S43] C++：智能指针
来源：http://dali.zhijiandao.cn/Article/details/gtngduwtdw.html

auto p = std::make_unique<int>(5);
来源：http://dali.smart0.xyz/Article/details/gtqorcjdow.html

[S44] C++：引用传参
来源：http://dali.zhiwuduotai.top/Article/details/gtomuluugk.html

void inc(int &x) { ++x; }
来源：http://dali.cucudq.cn/Article/details/gtjzwgzain.html

[S45] C++：lambda
来源：http://dali.yuxming.cn/Article/details/gtqczfjxpa.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gaohongyu789.top/Article/details/gthnepnber.html

[S46] C++：函数模板
来源：http://dali.guannengcc.top/Article/details/gtqewncdwm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hammf.cn/Article/details/gtxjnvekdr.html

[S47] C++：结构化绑定遍历
来源：http://dali.yj20258888.top/Article/details/gttjbocpqy.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.9152youxi.cn/Article/details/gtjkftbyfo.html

[S48] C++：逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gtvtrrysjz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.redwolf501.top/Article/details/gtwnuwjozu.html

while (std::getline(in, line)) { }
来源：http://dali.wangdashe.top/Article/details/gtphkdfido.html

[S49] C++：写文件
来源：http://dali.tanke756.top/Article/details/gtqsttehdq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yanxiufei.cn/Article/details/gtlrrsnqxl.html

[S50] C++：格式化数字
来源：http://dali.cdnleiting.top/Article/details/gtbmhkclmg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jianghu66.top/Article/details/gtcsyavksz.html

[S51] C++：显式类型转换
来源：http://dali.sufxvd.cn/Article/details/gtrilzmbhl.html

static_cast<double>(a) / b
来源：http://dali.kuanghao11.cn/Article/details/gtpejectjc.html

[S52] C++：const 与 noexcept
来源：http://dali.wangdashe.top/Article/details/gtuoyngvnf.html

int size() const noexcept { return n_; }
来源：http://dali.wangshuangyany.cn/Article/details/gtkhfvxqxe.html

[S53] C++：移动语义
来源：http://dali.hywenlv.cn/Article/details/gtzmrdclbu.html

std::vector<int> w = std::move(v);
来源：http://dali.snrcjt.cn/Article/details/gtulvbblce.html

[S54] C++：异常处理
来源：http://dali.yj20258.top/Article/details/gtphyeazvm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hnxiangtu.top/Article/details/gtjwugcqny.html

[S55] C++：结构化绑定
来源：http://dali.gaohongyu789.top/Article/details/gtwqppzwcd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cashguo.top/Article/details/gtbsilsnqm.html

[S56] C++：optional
来源：http://dali.wangshuangyany.cn/Article/details/gtgnnlkcsi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.0kj1m.cn/Article/details/gtdpcbzmro.html

[S57] C++：编译期常量
来源：http://dali.cdnleiting.top/Article/details/gtpkuumenc.html

constexpr int N = 10;
来源：http://dali.wangshuangyany.cn/Article/details/gtseghcsli.html

[S58] C++：命名空间
来源：http://dali.xuanzx.com/Article/details/gtpeutecvf.html

namespace ns { int f() { return 1; } }
来源：http://dali.wangshuangyany.cn/Article/details/gttfgjpxqa.html

[S59] C++：静态断言
来源：http://dali.xinyue.icu/Article/details/gtjrwfbfpb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yangfankeji.com/Article/details/gtqfphkcnq.html

[S60] C++：遍历并删除元素
来源：http://dali.guannengcc.top/Article/details/gtxpuvbtoc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.guowangkeji.top/Article/details/gtyuwfqczb.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gttchulcpd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.redwolf501.top/Article/details/gthnpymtru.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtomjxjjzk.html

[T01] Kotlin：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtkardwzsm.html

println("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnlahxnyv.html

[T02] Kotlin：变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsjrmerzy.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.smart0.xyz/Article/details/gtfeuvtlfp.html

[T03] Kotlin：字符串模板
来源：http://dali.jqgfzy.top/Article/details/gtzjchutue.html

"值: $b"
来源：http://dali.zhongyouzk.top/Article/details/gtgxczqmih.html

[T04] Kotlin：空安全
来源：http://dali.tian-w.cn/Article/details/gtripmvuyr.html

val n: String? = null;  n?.length
来源：http://dali.tanke756.top/Article/details/gtnzzlilct.html

[T05] Kotlin：when 表达式
来源：http://dali.ehwqpu.com/Article/details/gtlspclmde.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sxryk.cn/Article/details/gtjfzhpdes.html

[T06] Kotlin：集合映射
来源：http://dali.mhx1999.top/Article/details/gtnwvygkgi.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jqgfzy.top/Article/details/gtsvjzezut.html

[T07] Kotlin：集合过滤
来源：http://dali.zhongyouzk.top/Article/details/gtyvkvgqya.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj20258.top/Article/details/gtlakgwauu.html

[T08] Kotlin：数据类
来源：http://dali.wangdashe.top/Article/details/gtnomxdsua.html

data class User(val name: String, val age: Int)
来源：http://dali.yuxming.cn/Article/details/gtdqnvaztl.html

[T09] Kotlin：扩展函数
来源：http://dali.yuanzhike.top/Article/details/gteyvlaxsd.html

fun String.exclaim() = this + "!"
来源：http://dali.shanyushiyangtech.top/Article/details/gtrefpbbum.html

[T10] Kotlin：默认参数
来源：http://dali.zhijiandao.cn/Article/details/gtuzavshiy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.fengsongda.top/Article/details/gtwypyqfzo.html

[T11] Kotlin：协程
来源：http://dali.yj20258888.top/Article/details/gtyvelernm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.guannengcc.top/Article/details/gtmxolprsz.html

[T12] Kotlin：解构声明
来源：http://dali.guowangkeji.top/Article/details/gtgayhrdfu.html

val (a, b) = Pair(1, 2)
来源：http://dali.sufxvd.cn/Article/details/gtssxwmgft.html

[T13] Kotlin：只读 Map
来源：http://dali.wangshuangyany.cn/Article/details/gtveashzmr.html

val m = mapOf("a" to 1)
来源：http://dali.aibaodan.cn/Article/details/gtruoscxml.html

[T14] Kotlin：循环
来源：http://dali.zhongyouzk.top/Article/details/gtcevnspof.html

for (i in 1..10) println(i)
来源：http://dali.sysykeji.top/Article/details/gtdxutmjbg.html

[T15] Kotlin：接口
来源：http://dali.fzhhl.top/Article/details/gtkekgenpz.html

interface Shape { fun area(): Double }
来源：http://dali.jinqigufen.top/Article/details/gtdhqueijj.html

[T16] Swift：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtdelghuyt.html

print("Hello")
来源：http://dali.tianlin.xyz/Article/details/gtbmphzsmd.html

[T17] Swift：变量与常量
来源：http://dali.ybcxt.top/Article/details/gtykneyxth.html

var a = 1;  let b = 2
来源：http://dali.316326.xyz/Article/details/gtsyehmfoj.html

[T18] Swift：字符串插值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtunameomw.html

"值: \(b)"
来源：http://dali.hfpthk.cn/Article/details/gtehipbkam.html

[T19] Swift：可选绑定
来源：http://dali.pengpengdd.cyou/Article/details/gtzkjpvwnv.html

if let n = opt { print(n) }
来源：http://dali.yuanzhike.top/Article/details/gtcojhuebs.html

[T20] Swift：数组操作
来源：http://dali.andypj.xyz/Article/details/gtcgmwqpen.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.dianchejie.cn/Article/details/gtfelphrym.html

[T21] Swift：遍历
来源：http://dali.hfpthk.cn/Article/details/gtglhzxjop.html

for x in a { print(x) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtimtdojyp.html

[T22] Swift：字典
来源：http://dali.yueranfly.top/Article/details/gtdfzlqfvz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.chenzaomai.com/Article/details/gtszasenza.html

[T23] Swift：函数
来源：http://dali.zycfv.cn/Article/details/gtlgergiar.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.meibo888.top/Article/details/gtbwhpmcoe.html

[T24] Swift：闭包
来源：http://dali.yuanzhike.top/Article/details/gtdmrjbvzi.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yangfankeji.com/Article/details/gtzjroloyc.html

[T25] Swift：结构体
来源：http://dali.bjfxy.top/Article/details/gtikikbkyy.html

struct P { var x: Int }
来源：http://dali.pengpengdd.cyou/Article/details/gtunpkcldq.html

[T26] Swift：类与重写
来源：http://dali.yj202588.top/Article/details/gtppqwnjcx.html

class A: Base { override func f() {} }
来源：http://dali.fengsongda.top/Article/details/gtjvslxsro.html

[T27] Swift：错误处理
来源：http://dali.hammf.cn/Article/details/gtogoirxis.html

do { try f() } catch { print(error) }
来源：http://dali.zhongyouzk.top/Article/details/gtvjzedqir.html

[T28] Swift：枚举
来源：http://dali.nwbrower.top/Article/details/gtlfhakzot.html

enum Color { case red, green }
来源：http://dali.hfpthk.cn/Article/details/gtjialpjzb.html

[T29] Swift：guard 提前返回
来源：http://dali.hnqzz.top/Article/details/gtqoaxkdmc.html

guard let x = opt else { return }
来源：http://dali.yvedp.cn/Article/details/gtytrfbwge.html

[T30] Swift：协议
来源：http://dali.havefunace.top/Article/details/gtezdjyxtk.html

protocol Shape { func area() -> Double }
来源：http://dali.quarkkingdee.top/Article/details/gtxkplhjii.html

[T31] Lua：Hello World
来源：http://dali.cucudq.cn/Article/details/gtvgaepttn.html

print("Hello")
来源：http://dali.ppjwa.cn/Article/details/gtnurstfka.html

[T32] Lua：局部变量
来源：http://dali.bjfxy.top/Article/details/gtrwfozbzr.html

local a = 1
来源：http://dali.hfpthk.cn/Article/details/gtkhejoaet.html

[T33] Lua：表（数组）
来源：http://dali.sweek.top/Article/details/gtmgesvapa.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jqgufenzy.top/Article/details/gtsedgbgwq.html

[T34] Lua：遍历表
来源：http://dali.0kj1m.cn/Article/details/gtcmssbbtd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.tianlin.xyz/Article/details/gtoldqfosv.html

[T35] Lua：字典表
来源：http://dali.zhongyouzk.top/Article/details/gtgpizlfjb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.iojbl.cn/Article/details/gthbmmvfhc.html

[T36] Lua：函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvndozcfu.html

function add(a, b) return a + b end
来源：http://dali.wangdashe.top/Article/details/gthamoqvyv.html

[T37] Lua：字符串拼接
来源：http://dali.cucudq.cn/Article/details/gtpjyqkdey.html

"a" .. "b"
来源：http://dali.hysaishi.cn/Article/details/gtwjivmcvr.html

[T38] Lua：条件
来源：http://dali.ivvv.top/Article/details/gtffgqndcl.html

if x > 0 then print("正") end
来源：http://dali.jinqigfzy.top/Article/details/gtajxlovjj.html

[T39] Lua：模式匹配
来源：http://dali.ybcxt.top/Article/details/gtidmonuws.html

string.find(s, "%d+")
来源：http://dali.zhongyouzk.top/Article/details/gtmxrnsshw.html

[T40] Lua：元表
来源：http://dali.ehwqpu.com/Article/details/gtacnhiijm.html

setmetatable({}, { __index = base })
来源：http://dali.zhiwuduotai.top/Article/details/gtgesuktia.html

[T41] Perl：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtmrhpeerk.html

print "Hello\n";
来源：http://dali.svipenyu.cn/Article/details/gtpttsboky.html

[T42] Perl：变量类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gthxbonbfk.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zdqjudy.top/Article/details/gtaelgbvwu.html

[T43] Perl：字符串插值
来源：http://dali.9152youxi.cn/Article/details/gtpoiufhmk.html

"值: $a"
来源：http://dali.yuxming.cn/Article/details/gtpymoxokd.html

[T44] Perl：条件
来源：http://dali.tianlin.xyz/Article/details/gtdkboecls.html

if ($a > 0) { print "正"; }
来源：http://dali.0kj1m.cn/Article/details/gtziauzrbj.html

[T45] Perl：数组遍历
来源：http://dali.svipenyu.cn/Article/details/gtyvrvefyy.html

for my $x (@arr) { print $x; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtornyvotc.html

[T46] Perl：哈希操作
来源：http://dali.sysykeji.top/Article/details/gtvldfaldb.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.0kj1m.cn/Article/details/gtnbdodekk.html

[T47] Perl：正则捕获
来源：http://dali.snrcjt.cn/Article/details/gtzypxzjcx.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.cdnleiting.top/Article/details/gtyraehfsl.html

[T48] Perl：正则替换
来源：http://dali.sxryk.cn/Article/details/gtscxmgrzf.html

$s =~ s/old/new/g;
来源：http://dali.ydzc1.top/Article/details/gtarioojmp.html

[T49] Perl：函数
来源：http://dali.chenzaomai.com/Article/details/gtwyqllofh.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.bjfxy.top/Article/details/gtxzmtzamk.html

[T50] Perl：逐行读文件
来源：http://dali.gzhubu.top/Article/details/gtynrzechh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvprraqsr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.aibaodan.cn/Article/details/gtzjjobjnb.html

[T51] Scala：Hello World
来源：http://dali.aibaodan.cn/Article/details/gthclrlhdt.html

println("Hello")
来源：http://dali.birdmap.top/Article/details/gthjtmqtpd.html

[T52] Scala：变量
来源：http://dali.gzhubu.top/Article/details/gtgckvkdzn.html


<!-- 参考信息 -->