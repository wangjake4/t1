代发 wailian999

ssh user@host 'uptime'
来源：http://dali.fengsongda.top/Article/details/gtylxckjaj.html

[R58] 下载文件
来源：http://dali.nwbrower.top/Article/details/gtachnqnmz.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sxryk.cn/Article/details/gtthmdbxpa.html

[R59] 发 POST JSON
来源：http://dali.shzxlz.cn/Article/details/gtuipjdtdx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sufxvd.cn/Article/details/gtnannxfca.html

[R60] 只看 HTTP 状态码
来源：http://dali.pengpengdd.cyou/Article/details/gtnubdttda.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jiagoushi.top/Article/details/gtxlczmwsy.html

[R61] 磁盘占用
来源：http://dali.jqgfzy.top/Article/details/gtrdjvtjpd.html

df -h;  du -sh *
来源：http://dali.sxryk.cn/Article/details/gtawbgpqqf.html

[R62] 找最占空间的文件
来源：http://dali.cashguo.top/Article/details/gttyfrgmde.html

du -ah . | sort -rh | head -10
来源：http://dali.hongshengwenyu.top/Article/details/gtfhhippzb.html

[R63] 内存与进程
来源：http://dali.xuanzx.com/Article/details/gthahgvlyk.html

free -h;  ps aux | grep nginx
来源：http://dali.kuanghao11.cn/Article/details/gtgnlgvuqw.html

[R64] 结束进程
来源：http://dali.xuetiantiany.cn/Article/details/gtyezdkuzq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.aibaodan.cn/Article/details/gtlmzfucyu.html

[R65] 查看端口占用
来源：http://dali.cqqwz.cn/Article/details/gtvehbfuyv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jinqigfzy.top/Article/details/gtfajihtnv.html

[R66] 定时任务
来源：http://dali.zdqjudy.top/Article/details/gtnggxgsnq.html

crontab -e;  crontab -l
来源：http://dali.hnxiangtu.top/Article/details/gtmgdyptkp.html

[R67] 生成随机十六进制串
来源：http://dali.jqgufenzy.top/Article/details/gtzdqcnrxn.html

openssl rand -hex 16
来源：http://dali.mhx1999.top/Article/details/gtknrbgkxj.html

[R68] 计算文件校验值
来源：http://dali.smart0.xyz/Article/details/gtaidlefnx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.haohaochexian.top/Article/details/gtngyjsclo.html

[R69] 生成随机密码
来源：http://dali.hnqzz.top/Article/details/gtktwozpfn.html

head -c 16 /dev/urandom | base64
来源：http://dali.zycfv.cn/Article/details/gtymakamcy.html

[R70] 时间戳与互转
来源：http://dali.smart0.xyz/Article/details/gtnyazgnsp.html

date +%s;  date -d @1700000000
来源：http://dali.jqgufenzy.top/Article/details/gtzbvijazk.html

[R71] 日期格式化
来源：http://dali.yuxming.cn/Article/details/gtckldxzrj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cashguo.top/Article/details/gtliojlknb.html

[R72] 等待端口就绪
来源：http://dali.wangdashe.top/Article/details/gtcqkbvpfo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sxryk.cn/Article/details/gtcgidxsfc.html

[R73] 分割大日志
来源：http://dali.mhx1999.top/Article/details/gtrjchjuzn.html

split -l 1000 big.log part_
来源：http://dali.jinghuilouyu.cn/Article/details/gtsopoxdgd.html

[R74] 批量重命名
来源：http://dali.dianchejie.cn/Article/details/gtgrffdzqh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jyoumei.cn/Article/details/gtpryaftnr.html

[R75] 导出环境变量
来源：http://dali.chenjidiqi.icu/Article/details/gtqmqidwzb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.smart0.xyz/Article/details/gtshlfmksv.html

[R76] 使用临时文件
来源：http://dali.dianchejie.cn/Article/details/gtistssltz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.dashuyun.cn/Article/details/gtxoiepwfo.html

[R77] 读取用户输入
来源：http://dali.iojbl.cn/Article/details/gtzjbcvmix.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gtmtvfgfaf.html

[R78] 交互式菜单
来源：http://dali.hywenlv.cn/Article/details/gtzyomdpsp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gzhubu.top/Article/details/gtmhiaryyy.html

[R79] 解析命令行选项
来源：http://dali.ppjwa.cn/Article/details/gtamxymojt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.chenlongwang.top/Article/details/gtxeyaexga.html

[R80] 查看脚本执行耗时
来源：http://dali.haohaochexian.top/Article/details/gtdhkexznn.html

time ./run.sh
来源：http://dali.cucudq.cn/Article/details/gttgrqxvdx.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtjicktvkc.html

S. C / C++ 专题
来源：http://dali.yvedp.cn/Article/details/gtafiuvhbv.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtkxkdrfsw.html

[S01] C：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtlovnsfis.html

#include <stdio.h>
来源：http://dali.yj20258888.top/Article/details/gtncunmnwd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gtfzxrtcnj.html

[S02] C：变量与格式化输出
来源：http://dali.cucudq.cn/Article/details/gtzgapbjtz.html

int a = 10; printf("%d\n", a);
来源：http://dali.dashuyun.cn/Article/details/gtryjltfbc.html

[S03] C：读入整数
来源：http://dali.fzhhl.top/Article/details/gtmsgdupol.html

int x; scanf("%d", &x);
来源：http://dali.yangfankeji.com/Article/details/gteoucxvqh.html

[S04] C：字符串复制
来源：http://dali.yj202588.top/Article/details/gtvmqsppyc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xuanzx.com/Article/details/gtwbqdjjit.html

[S05] C：字符串长度
来源：http://dali.dashuyun.cn/Article/details/gtvmggguhv.html

strlen(s)
来源：http://dali.jqgfzy.top/Article/details/gtuxcwklwk.html

[S06] C：字符串比较
来源：http://dali.hywenlv.cn/Article/details/gtkkswbdub.html

strcmp(a, b) == 0
来源：http://dali.yanxiufei.cn/Article/details/gtxaysjfwg.html

[S07] C：数组遍历求和
来源：http://dali.jqgufenzy.top/Article/details/gtpbhzxigu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hysaishi.cn/Article/details/gtnenxpffz.html

[S08] C：动态内存分配与释放
来源：http://dali.hnxiangtu.top/Article/details/gtdrvlagkc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hongshengwenyu.top/Article/details/gtmuaqprth.html

[S09] C：结构体定义与初始化
来源：http://dali.zhengqikj.top/Article/details/gtoruefgzs.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shuidangran.top/Article/details/gtzamuqpoy.html

[S10] C：指针与解引用
来源：http://dali.andypj.xyz/Article/details/gtqbypmsoy.html

int *p = &a;  *p = 5;
来源：http://dali.jiagoushi.top/Article/details/gtagwyamne.html

[S11] C：逐行读文件
来源：http://dali.xziqi.cn/Article/details/gtgjfjfxti.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yongpay.top/Article/details/gtbmfztybc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hywenlv.cn/Article/details/gtlimirfrm.html

fclose(f);
来源：http://dali.cheryme.top/Article/details/gtlmlfhcvw.html

[S12] C：写文件
来源：http://dali.iojbl.cn/Article/details/gtfzqmyqku.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.aibaodan.cn/Article/details/gtfpulabqh.html

[S13] C：宏定义
来源：http://dali.jinqigfzy.top/Article/details/gtqhdsabbo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.andypj.xyz/Article/details/gtwqqjrquh.html

[S14] C：枚举
来源：http://dali.sweek.top/Article/details/gtnouupljd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sysykeji.top/Article/details/gtrgzlhttz.html

[S15] C：类型转换
来源：http://dali.yangfankeji.com/Article/details/gtubnvbvri.html

(double) a / b
来源：http://dali.quarkkingdee.top/Article/details/gtgczjriah.html

[S16] C：位操作置位
来源：http://dali.yonumen.top/Article/details/gthigwbtsl.html

x |= (1 << 3);
来源：http://dali.yuanzhike.top/Article/details/gtafmnkxaq.html

[S17] C：安全拼接字符串
来源：http://dali.birdmap.top/Article/details/gtdupztbyk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yvedp.cn/Article/details/gtuehosnxr.html

[S18] C：命令行参数
来源：http://dali.ehwqpu.com/Article/details/gtipnaonjk.html

int main(int argc, char **argv)
来源：http://dali.ybcxt.top/Article/details/gtmvwdagpm.html

[S19] C：快速排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjgntctxw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cashguo.top/Article/details/gtbtdqtttt.html

[S20] C：二分查找
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlsjzihxw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cucudq.cn/Article/details/gtvbbyozpl.html

[S21] C：字符类别判断
来源：http://dali.daria6918.cn/Article/details/gtphyyeoqg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.nwbrower.top/Article/details/gtdigbedlc.html

[S22] C：字符串转数字
来源：http://dali.hongshengwenyu.top/Article/details/gttjjpgctv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.smart0.xyz/Article/details/gtdxulhmhs.html

[S23] C：随机数
来源：http://dali.yueranfly.top/Article/details/gtaajcofyw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.vqdsnc.cn/Article/details/gtoqxikace.html

[S24] C：获取本地时间
来源：http://dali.redwolf501.top/Article/details/gtrvozfnuv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.svipenyu.cn/Article/details/gtfvdyxacj.html

[S25] C：内存拷贝
来源：http://dali.chenlongwang.top/Article/details/gtphdxyyvr.html

memcpy(dst, src, n);
来源：http://dali.yueranfly.top/Article/details/gtvglerfcx.html

[S26] C：内存清零
来源：http://dali.zhixingplan.top/Article/details/gtyuceebyy.html

memset(a, 0, sizeof a);
来源：http://dali.yj20258888.top/Article/details/gtzkloakxx.html

[S27] C：定义常量
来源：http://dali.chenlongwang.top/Article/details/gtuoyegokt.html

const double PI = 3.14159;
来源：http://dali.gaohongyu789.top/Article/details/gtctwusrrp.html

[S28] C：静态变量
来源：http://dali.jinqigufen.top/Article/details/gtlboqhwmt.html

static int counter = 0;
来源：http://dali.hnqzz.top/Article/details/gtmprkpcjg.html

[S29] C：变参函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqkqqebcd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhoulong.xyz/Article/details/gtniseykhr.html

[S30] C：头文件保护
来源：http://dali.cqqwz.cn/Article/details/gtmchfikvf.html

#ifndef X_H
来源：http://dali.birdmap.top/Article/details/gtrkkzikwv.html

#define X_H
来源：http://dali.shanyushiyangkeji.top/Article/details/gtimsqwodf.html

#endif
来源：http://dali.yuxming.cn/Article/details/gtkqaryxhe.html

[S31] C++：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwheqxrge.html

#include <iostream>
来源：http://dali.cheryme.top/Article/details/gtymewegkq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jianghu66.top/Article/details/gtrjsaukvk.html

[S32] C++：字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuxtqxrmx.html

std::string s = "hi";  s += "!";
来源：http://dali.aibaodan.cn/Article/details/gttuuqrgtj.html

[S33] C++：vector 增删
来源：http://dali.yuanzhike.top/Article/details/gtipaoxogf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cdnleiting.top/Article/details/gtxqgbeqzl.html

[S34] C++：遍历 vector
来源：http://dali.zdqjudy.top/Article/details/gtiajgtxun.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ehwqpu.com/Article/details/gtlwrsnwlw.html

[S35] C++：map
来源：http://dali.iojbl.cn/Article/details/gtgweufxja.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pycfn.com/Article/details/gtrtsbxqjq.html

[S36] C++：unordered_map
来源：http://dali.guannengcc.top/Article/details/gtuocqzzbl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fengsongda.top/Article/details/gtnpsfkltl.html

[S37] C++：set
来源：http://dali.kuanghao11.cn/Article/details/gtmikhuuee.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gogol.net.cn/Article/details/gtkjnqjrpn.html

[S38] C++：排序
来源：http://dali.9152youxi.cn/Article/details/gthhguhgtc.html

std::sort(v.begin(), v.end());
来源：http://dali.gogol.net.cn/Article/details/gtxxaspkfh.html

[S39] C++：自定义比较器排序
来源：http://dali.sufxvd.cn/Article/details/gtroygmpxw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.tanke756.top/Article/details/gtnzcppkbg.html

[S40] C++：查找元素
来源：http://dali.9152youxi.cn/Article/details/gtimypmqjf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gotoacloud.top/Article/details/gtnkkyntct.html

[S41] C++：类与构造函数
来源：http://dali.shzxlz.cn/Article/details/gtlkxpzxme.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.tanke756.top/Article/details/gtfdpyejpr.html

[S42] C++：继承与虚函数
来源：http://dali.cucudq.cn/Article/details/gtdedcinub.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhoulong.xyz/Article/details/gtcujrsxht.html

[S43] C++：智能指针
来源：http://dali.gzhubu.top/Article/details/gtuvafdvxq.html

auto p = std::make_unique<int>(5);
来源：http://dali.cucudq.cn/Article/details/gtayxvjcql.html

[S44] C++：引用传参
来源：http://dali.yuxming.cn/Article/details/gtfqhkyqum.html

void inc(int &x) { ++x; }
来源：http://dali.haohaochexian.top/Article/details/gthdoidubq.html

[S45] C++：lambda
来源：http://dali.hnqzz.top/Article/details/gtqnmlmlnt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hywenlv.cn/Article/details/gtqhxoicdq.html

[S46] C++：函数模板
来源：http://dali.andypj.xyz/Article/details/gtvzpstszr.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cdnleiting.top/Article/details/gtzbtwkljy.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhijiandao.cn/Article/details/gtmhtlrfgf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.0kj1m.cn/Article/details/gtlfydazwp.html

[S48] C++：逐行读文件
来源：http://dali.zhiwuduotai.top/Article/details/gtyzaobhrf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xinyue.icu/Article/details/gtwlrjpljn.html

while (std::getline(in, line)) { }
来源：http://dali.316326.xyz/Article/details/gtdnudzrrl.html

[S49] C++：写文件
来源：http://dali.pycfn.com/Article/details/gtyhosduvj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.0kj1m.cn/Article/details/gtqlpkvocb.html

[S50] C++：格式化数字
来源：http://dali.jinqigufen.top/Article/details/gtyyxrrfwo.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzvinqvpl.html

[S51] C++：显式类型转换
来源：http://dali.xuanzx.com/Article/details/gtckkaoodf.html

static_cast<double>(a) / b
来源：http://dali.feifeiyinyue.top/Article/details/gtwxevnobc.html

[S52] C++：const 与 noexcept
来源：http://dali.zhaomingkeji.xyz/Article/details/gtckjxxgas.html

int size() const noexcept { return n_; }
来源：http://dali.zhixingplan.top/Article/details/gtuyhbowmj.html

[S53] C++：移动语义
来源：http://dali.hysaishi.cn/Article/details/gtcemdpdke.html

std::vector<int> w = std::move(v);
来源：http://dali.daria6918.cn/Article/details/gtierjpyck.html

[S54] C++：异常处理
来源：http://dali.ppjwa.cn/Article/details/gtmxmzsjpq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xylfe.cn/Article/details/gtqakntvsx.html

[S55] C++：结构化绑定
来源：http://dali.zhiwuduotai.top/Article/details/gtqykjoujh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yonumen.top/Article/details/gtmknumnvf.html

[S56] C++：optional
来源：http://dali.xinyue.icu/Article/details/gtfectkubz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.svipenyu.cn/Article/details/gtcewkkocr.html

[S57] C++：编译期常量
来源：http://dali.yuanzhike.top/Article/details/gtrjrvcmyf.html

constexpr int N = 10;
来源：http://dali.kuanghao11.cn/Article/details/gtttdznbjk.html

[S58] C++：命名空间
来源：http://dali.9152youxi.cn/Article/details/gtwubyzqzi.html

namespace ns { int f() { return 1; } }
来源：http://dali.hongshengwenyu.top/Article/details/gtdreijzzh.html

[S59] C++：静态断言
来源：http://dali.sweek.top/Article/details/gtcwgnqaiq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yj20258.top/Article/details/gtsvipcqvm.html

[S60] C++：遍历并删除元素
来源：http://dali.fzhhl.top/Article/details/gtgkffjkil.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinghuilouyu.cn/Article/details/gtarlwgswb.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjhxxmcit.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkrprfqyy.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtaypnvtfw.html

[T01] Kotlin：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtwtokixfc.html

println("Hello")
来源：http://dali.jiagoushi.top/Article/details/gtqfibfebg.html

[T02] Kotlin：变量
来源：http://dali.cucudq.cn/Article/details/gtljwapaup.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.wangshuangyany.cn/Article/details/gtzqcandlw.html

[T03] Kotlin：字符串模板
来源：http://dali.shuidangran.top/Article/details/gtwmuqdjti.html

"值: $b"
来源：http://dali.jinqigufen.top/Article/details/gtmcccmjky.html

[T04] Kotlin：空安全
来源：http://dali.jianghu66.top/Article/details/gtbdyobuqt.html

val n: String? = null;  n?.length
来源：http://dali.hnxiangtu.top/Article/details/gtcothwgkn.html

[T05] Kotlin：when 表达式
来源：http://dali.zhoulong.xyz/Article/details/gtxpmlxirg.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xuanzx.com/Article/details/gtsqixddfy.html

[T06] Kotlin：集合映射
来源：http://dali.chenlongwang.top/Article/details/gtrehxeldp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yonumen.top/Article/details/gtsdelutnj.html

[T07] Kotlin：集合过滤
来源：http://dali.sysykeji.top/Article/details/gtiwbcyuko.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinqigfzy.top/Article/details/gtjtezjqyl.html

[T08] Kotlin：数据类
来源：http://dali.c1oappe.top/Article/details/gtxbfoqvar.html

data class User(val name: String, val age: Int)
来源：http://dali.andypj.xyz/Article/details/gtailvtwdy.html

[T09] Kotlin：扩展函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtocdjesru.html

fun String.exclaim() = this + "!"
来源：http://dali.hnxiangtu.top/Article/details/gtibqibnao.html

[T10] Kotlin：默认参数
来源：http://dali.nanxinkj.top/Article/details/gtytrrmpim.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yj20258888.top/Article/details/gtxhgwcclz.html

[T11] Kotlin：协程
来源：http://dali.redwolf501.top/Article/details/gteqdqwbop.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gogol.net.cn/Article/details/gtqmziuolr.html

[T12] Kotlin：解构声明
来源：http://dali.fengsongda.top/Article/details/gtzcvuitxu.html

val (a, b) = Pair(1, 2)
来源：http://dali.ppjwa.cn/Article/details/gtpfyvsxia.html

[T13] Kotlin：只读 Map
来源：http://dali.iojbl.cn/Article/details/gttvxkgiwe.html

val m = mapOf("a" to 1)
来源：http://dali.zhixingplan.top/Article/details/gtrzjbdnqm.html

[T14] Kotlin：循环
来源：http://dali.fengsongda.top/Article/details/gtxssgajlq.html

for (i in 1..10) println(i)
来源：http://dali.yj20258.top/Article/details/gtdllavcsj.html

[T15] Kotlin：接口
来源：http://dali.nanxinkj.top/Article/details/gtfladroec.html

interface Shape { fun area(): Double }
来源：http://dali.yj202588.top/Article/details/gtxjxsprcv.html

[T16] Swift：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtuvspipbt.html

print("Hello")
来源：http://dali.haohaochexian.top/Article/details/gtavhbdznn.html

[T17] Swift：变量与常量
来源：http://dali.kuanghao11.cn/Article/details/gtjfgqfqbu.html

var a = 1;  let b = 2
来源：http://dali.jinqigufen.top/Article/details/gtifatrlga.html

[T18] Swift：字符串插值
来源：http://dali.yanxiufei.cn/Article/details/gtlddeakqi.html

"值: \(b)"
来源：http://dali.tian-w.cn/Article/details/gtfxaoxijo.html

[T19] Swift：可选绑定
来源：http://dali.jinqigufen.top/Article/details/gtuqzhkrsa.html

if let n = opt { print(n) }
来源：http://dali.shangyingyoupin.top/Article/details/gtwhctnbvf.html

[T20] Swift：数组操作
来源：http://dali.svipenyu.cn/Article/details/gtvwcpextk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.mhx1999.top/Article/details/gtqitnjxiz.html

[T21] Swift：遍历
来源：http://dali.tanke756.top/Article/details/gtniwjcndc.html

for x in a { print(x) }
来源：http://dali.fzhhl.top/Article/details/gtzsjlbjzo.html

[T22] Swift：字典
来源：http://dali.jinqigufen.top/Article/details/gtpcztdwxf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shzxlz.cn/Article/details/gtvvipktls.html

[T23] Swift：函数
来源：http://dali.hysaishi.cn/Article/details/gtaoprinnt.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.tianlin.xyz/Article/details/gtwdcaodlc.html

[T24] Swift：闭包
来源：http://dali.ydzc1.top/Article/details/gtevenkdli.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gtvbmpbnag.html

[T25] Swift：结构体
来源：http://dali.yangfankeji.com/Article/details/gthvnvodjz.html

struct P { var x: Int }
来源：http://dali.iojbl.cn/Article/details/gtpumemsuz.html

[T26] Swift：类与重写
来源：http://dali.gotoacloud.top/Article/details/gtyvutfheo.html

class A: Base { override func f() {} }
来源：http://dali.sweek.top/Article/details/gtsmfciijj.html

[T27] Swift：错误处理
来源：http://dali.jianghu66.top/Article/details/gtiecsdckv.html

do { try f() } catch { print(error) }
来源：http://dali.smart0.xyz/Article/details/gtpxlijkyl.html

[T28] Swift：枚举
来源：http://dali.xinyue.icu/Article/details/gtismahpjk.html

enum Color { case red, green }
来源：http://dali.kuanghao11.cn/Article/details/gtcdfhjigx.html

[T29] Swift：guard 提前返回
来源：http://dali.xuetiantiany.cn/Article/details/gtweahnskt.html

guard let x = opt else { return }
来源：http://dali.guannengcc.top/Article/details/gtvfwyovli.html

[T30] Swift：协议
来源：http://dali.ehwqpu.com/Article/details/gtndglybfw.html

protocol Shape { func area() -> Double }
来源：http://dali.svipenyu.cn/Article/details/gtqbsnlnpk.html

[T31] Lua：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtniykbszt.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gtghxjdxns.html

[T32] Lua：局部变量
来源：http://dali.sysykeji.top/Article/details/gttcyhnjvi.html

local a = 1
来源：http://dali.xziqi.cn/Article/details/gtajuoxwur.html

[T33] Lua：表（数组）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmlnertrp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.chenzaomai.com/Article/details/gtwljkqgxf.html

[T34] Lua：遍历表
来源：http://dali.yangfankeji.com/Article/details/gtwdooyqjl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.sysykeji.top/Article/details/gtsgybzlfy.html

[T35] Lua：字典表
来源：http://dali.chenlongwang.top/Article/details/gtcqbxeqye.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhiwuduotai.top/Article/details/gtpitogwht.html

[T36] Lua：函数
来源：http://dali.jiagoushi.top/Article/details/gtvfnfnqnj.html

function add(a, b) return a + b end
来源：http://dali.tian-w.cn/Article/details/gtklveqexr.html

[T37] Lua：字符串拼接
来源：http://dali.yuxming.cn/Article/details/gtvwoniiip.html

"a" .. "b"
来源：http://dali.gogol.net.cn/Article/details/gtztnbnvqf.html

[T38] Lua：条件
来源：http://dali.gotoacloud.top/Article/details/gtsyxzuiyf.html

if x > 0 then print("正") end
来源：http://dali.ivvv.top/Article/details/gtqufxwssy.html

[T39] Lua：模式匹配
来源：http://dali.yj20258888.top/Article/details/gtbttlruxg.html

string.find(s, "%d+")
来源：http://dali.yj202588.top/Article/details/gtwwytbubc.html

[T40] Lua：元表
来源：http://dali.gzhubu.top/Article/details/gtkycldmjb.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gtaswqaina.html

[T41] Perl：Hello World
来源：http://dali.yuxming.cn/Article/details/gtdthndoex.html

print "Hello\n";
来源：http://dali.svipenyu.cn/Article/details/gtztyefsmm.html

[T42] Perl：变量类型
来源：http://dali.tanke756.top/Article/details/gtpkhdlklv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jqgfzy.top/Article/details/gtlfiszrtl.html

[T43] Perl：字符串插值
来源：http://dali.nwbrower.top/Article/details/gtlkilqkbq.html

"值: $a"
来源：http://dali.chenjidiqi.icu/Article/details/gtqpqjcyqu.html

[T44] Perl：条件
来源：http://dali.chenlongwang.top/Article/details/gtikfabfvs.html

if ($a > 0) { print "正"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtlvfodqig.html

[T45] Perl：数组遍历
来源：http://dali.ydzc1.top/Article/details/gttpbtidth.html

for my $x (@arr) { print $x; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtehqumitd.html

[T46] Perl：哈希操作
来源：http://dali.hfpthk.cn/Article/details/gtjwccwtwl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jinqigufen.top/Article/details/gtekeijakr.html

[T47] Perl：正则捕获
来源：http://dali.hongshengwenyu.top/Article/details/gthfkpboql.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hfpthk.cn/Article/details/gthymzqznj.html

[T48] Perl：正则替换
来源：http://dali.jinqigfzy.top/Article/details/gtmzezazra.html

$s =~ s/old/new/g;
来源：http://dali.yvedp.cn/Article/details/gtnlddgnop.html

[T49] Perl：函数
来源：http://dali.yuanzhike.top/Article/details/gtaudwjmdu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.wangshuangyany.cn/Article/details/gttavrkdwg.html

[T50] Perl：逐行读文件
来源：http://dali.yvedp.cn/Article/details/gtsufacvpt.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.chenlongwang.top/Article/details/gthhfdziij.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yvedp.cn/Article/details/gtuwmphdxu.html

[T51] Scala：Hello World
来源：http://dali.jianghu66.top/Article/details/gtvpgmezhu.html

println("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoueudwpc.html

[T52] Scala：变量
来源：http://dali.chenjidiqi.icu/Article/details/gtbpblbytd.html

val a = 1;  var b = 2
来源：http://dali.shuidangran.top/Article/details/gtepeausnk.html

[T53] Scala：字符串插值
来源：http://dali.dianchejie.cn/Article/details/gtmmgnqcqa.html

s"值: $b"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmowebdrv.html

[T54] Scala：集合映射
来源：http://dali.jlsjyb.cn/Article/details/gtkcvbelzf.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.dashuyun.cn/Article/details/gtpgxhryxl.html

[T55] Scala：集合过滤
来源：http://dali.pengpengdd.cyou/Article/details/gtmkxkqbkb.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.yueranfly.top/Article/details/gtzhsjhmto.html

[T56] Scala：样例类
来源：http://dali.dashuyun.cn/Article/details/gtsygywspe.html

case class User(name: String, age: Int)
来源：http://dali.kuanghao11.cn/Article/details/gtrouncbpz.html

[T57] Scala：模式匹配
来源：http://dali.zhongyouzk.top/Article/details/gtogysslmj.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.guowangkeji.top/Article/details/gtbnfkgfml.html

[T58] Scala：函数定义
来源：http://dali.shanyushiyangtech.top/Article/details/gtrlhoogpa.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.havefunace.top/Article/details/gtsqduqpdq.html

[T59] Scala：循环
来源：http://dali.cdnleiting.top/Article/details/gtffthuciu.html

for (i <- 1 to 10) println(i)
来源：http://dali.gaohongyu789.top/Article/details/gtkvjixcsh.html

[T60] Scala：折叠
来源：http://dali.yj202588.top/Article/details/gtengiksot.html


<!-- 参考信息 -->