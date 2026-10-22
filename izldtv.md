代发 wailian999

ssh user@host 'uptime'
来源：http://dali.cheryme.top/Article/details/gt2voegbfnq.html

[R58] 下载文件
来源：http://dali.hfpthk.cn/Article/details/gt2xvgtvgyy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sufxvd.cn/Article/details/gt2rcqhsfmb.html

[R59] 发 POST JSON
来源：http://dali.mhx1999.top/Article/details/gt2cfdqxbzn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hnqzz.top/Article/details/gt2phntbymk.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aluupist.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.guannengcc.top/Article/details/gt2bjiwgyxk.html

[R61] 磁盘占用
来源：http://dali.cdnleiting.top/Article/details/gt2zpfggohj.html

df -h;  du -sh *
来源：http://dali.yangfankeji.com/Article/details/gt2gagjxadx.html

[R62] 找最占空间的文件
来源：http://dali.jqgufenzy.top/Article/details/gt2oanlrxay.html

du -ah . | sort -rh | head -10
来源：http://dali.ppjwa.cn/Article/details/gt2laplsehh.html

[R63] 内存与进程
来源：http://dali.guowangkeji.top/Article/details/gt2xltifrcp.html

free -h;  ps aux | grep nginx
来源：http://dali.aibaodan.cn/Article/details/gt2zwrzubdg.html

[R64] 结束进程
来源：http://dali.jianghu66.top/Article/details/gt2vazlnnfk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ydzc1.top/Article/details/gt2qobsrtho.html

[R65] 查看端口占用
来源：http://dali.jinqigfzy.top/Article/details/gt2aozsquin.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jqgufenzy.top/Article/details/gt2vuonkbdv.html

[R66] 定时任务
来源：http://dali.fengsongda.top/Article/details/gt2gnekqtns.html

crontab -e;  crontab -l
来源：http://dali.wangdashe.top/Article/details/gt2mwqmgitj.html

[R67] 生成随机十六进制串
来源：http://dali.hongshengwenyu.top/Article/details/gt2hjdystxg.html

openssl rand -hex 16
来源：http://dali.redwolf501.top/Article/details/gt2iounjlcg.html

[R68] 计算文件校验值
来源：http://dali.hysaishi.cn/Article/details/gt2yrhisuqf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2brrgocqv.html

[R69] 生成随机密码
来源：http://dali.yueranfly.top/Article/details/gt2rnitxyro.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhoulong.xyz/Article/details/gt2ajjvmfdu.html

[R70] 时间戳与互转
来源：http://dali.fengsongda.top/Article/details/gt2sbbtevez.html

date +%s;  date -d @1700000000
来源：http://dali.c1oappe.top/Article/details/gt2yltxsvlv.html

[R71] 日期格式化
来源：http://dali.yanxiufei.cn/Article/details/gt2ljzewirp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jqgufenzy.top/Article/details/gt2yhhzakyj.html

[R72] 等待端口就绪
来源：http://dali.ehwqpu.com/Article/details/gt2gjromvbn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jianghu66.top/Article/details/gt2xckycjzw.html

[R73] 分割大日志
来源：http://dali.yonumen.top/Article/details/gt2gjbyttfg.html

split -l 1000 big.log part_
来源：http://dali.shzxlz.cn/Article/details/gt2zlyxypxz.html

[R74] 批量重命名
来源：http://dali.bjfxy.top/Article/details/gt2uvusnlej.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yanxiufei.cn/Article/details/gt2maqcfuie.html

[R75] 导出环境变量
来源：http://dali.nanxinkj.top/Article/details/gt2wbwzztnl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ybcxt.top/Article/details/gt2ddmxcfcy.html

[R76] 使用临时文件
来源：http://dali.gzhubu.top/Article/details/gt2uksgtdgz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ivvv.top/Article/details/gt2vjzoeyas.html

[R77] 读取用户输入
来源：http://dali.bjfxy.top/Article/details/gt2rinbtvlk.html

read -rp "请输入: " ans
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2imhnugcy.html

[R78] 交互式菜单
来源：http://dali.aizwys.cn/Article/details/gt2zuaqxefh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xylfe.cn/Article/details/gt2paqjtakj.html

[R79] 解析命令行选项
来源：http://dali.tian-w.cn/Article/details/gt2swfbelyz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gzhubu.top/Article/details/gt2cavjnemi.html

[R80] 查看脚本执行耗时
来源：http://dali.yanxiufei.cn/Article/details/gt2cwuqheif.html

time ./run.sh
来源：http://dali.fzhhl.top/Article/details/gt2iccuuqvz.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gt2dgaspjjh.html

S. C / C++ 专题
来源：http://dali.yangfankeji.com/Article/details/gt2gzqimrid.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2kdddggie.html

[S01] C：Hello World
来源：http://dali.nanxinkj.top/Article/details/gt2bmtuwbtp.html

#include <stdio.h>
来源：http://dali.fengsongda.top/Article/details/gt2zuikbbfg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.dianchejie.cn/Article/details/gt2nbswtciz.html

[S02] C：变量与格式化输出
来源：http://dali.jlsjyb.cn/Article/details/gt2fuybcmfa.html

int a = 10; printf("%d\n", a);
来源：http://dali.jqgfzy.top/Article/details/gt2idntvlqx.html

[S03] C：读入整数
来源：http://dali.daxiang520.top/Article/details/gt2yriktcnj.html

int x; scanf("%d", &x);
来源：http://dali.snrcjt.cn/Article/details/gt2ybtnhdjw.html

[S04] C：字符串复制
来源：http://dali.chenjidiqi.icu/Article/details/gt2xkelszfx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sufxvd.cn/Article/details/gt2smhukcta.html

[S05] C：字符串长度
来源：http://dali.yongpay.top/Article/details/gt2fmdfvtob.html

strlen(s)
来源：http://dali.yuanzhike.top/Article/details/gt2vamztzyx.html

[S06] C：字符串比较
来源：http://dali.tanke756.top/Article/details/gt2heuijeca.html

strcmp(a, b) == 0
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2llbdvhzv.html

[S07] C：数组遍历求和
来源：http://dali.jinqigufen.top/Article/details/gt2wemjumjl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gogol.net.cn/Article/details/gt2eiwxbprd.html

[S08] C：动态内存分配与释放
来源：http://dali.haohaochexian.top/Article/details/gt2keigcowj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shzxlz.cn/Article/details/gt2aolqjkcb.html

[S09] C：结构体定义与初始化
来源：http://dali.wangshuangyany.cn/Article/details/gt2iggqklpu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gzhubu.top/Article/details/gt2ppvdimes.html

[S10] C：指针与解引用
来源：http://dali.haohaochexian.top/Article/details/gt2rirzluoy.html

int *p = &a;  *p = 5;
来源：http://dali.yangfankeji.com/Article/details/gt2ramorttk.html

[S11] C：逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gt2ggsmqcbq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cucudq.cn/Article/details/gt2ntxtyanl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhongyouzk.top/Article/details/gt2cchtlfhj.html

fclose(f);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xkhvpuzs.html

[S12] C：写文件
来源：http://dali.yongpay.top/Article/details/gt2hybpozly.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yuanzhike.top/Article/details/gt2vahgezdd.html

[S13] C：宏定义
来源：http://dali.ehwqpu.com/Article/details/gt2nuddsbdc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ehwqpu.com/Article/details/gt2cpqrrzxo.html

[S14] C：枚举
来源：http://dali.yj20258.top/Article/details/gt2kqmjjuai.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.svipenyu.cn/Article/details/gt2dxlkslhu.html

[S15] C：类型转换
来源：http://dali.snrcjt.cn/Article/details/gt2jwtxlgja.html

(double) a / b
来源：http://dali.nanxuanxn.top/Article/details/gt2kuiuzprn.html

[S16] C：位操作置位
来源：http://dali.tianlin.xyz/Article/details/gt2gtfrnczb.html

x |= (1 << 3);
来源：http://dali.hysaishi.cn/Article/details/gt2btxbzslh.html

[S17] C：安全拼接字符串
来源：http://dali.smart0.xyz/Article/details/gt2lzqjojxh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenzaomai.com/Article/details/gt2yobmxbuy.html

[S18] C：命令行参数
来源：http://dali.yj20258888.top/Article/details/gt2uppwsmla.html

int main(int argc, char **argv)
来源：http://dali.quarkkingdee.top/Article/details/gt2zuczznds.html

[S19] C：快速排序
来源：http://dali.pengpengdd.cyou/Article/details/gt2xigrvait.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sweek.top/Article/details/gt2rjwqrdys.html

[S20] C：二分查找
来源：http://dali.tanke756.top/Article/details/gt2khmunhne.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.bjfxy.top/Article/details/gt2rqmkrpoq.html

[S21] C：字符类别判断
来源：http://dali.bjfxy.top/Article/details/gt2raxbswgi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shangyingyoupin.top/Article/details/gt2duilnuqk.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2skrbjwrc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2gufiyfxw.html

[S23] C：随机数
来源：http://dali.yj20258.top/Article/details/gt2wgvvpueb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2sjwxmcur.html

[S24] C：获取本地时间
来源：http://dali.wangdashe.top/Article/details/gt2sftcwtrw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.iojbl.cn/Article/details/gt2odbduddg.html

[S25] C：内存拷贝
来源：http://dali.xuetiantiany.cn/Article/details/gt2celhotfo.html

memcpy(dst, src, n);
来源：http://dali.yongpay.top/Article/details/gt2fgbvjrhl.html

[S26] C：内存清零
来源：http://dali.9152youxi.cn/Article/details/gt2ujfnihcg.html

memset(a, 0, sizeof a);
来源：http://dali.nanxuanxn.top/Article/details/gt2ngwxyayv.html

[S27] C：定义常量
来源：http://dali.wangshuangyany.cn/Article/details/gt2jwtzrkjf.html

const double PI = 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gt2yrcgereb.html

[S28] C：静态变量
来源：http://dali.yonumen.top/Article/details/gt2cqyechge.html

static int counter = 0;
来源：http://dali.zhixingplan.top/Article/details/gt2eagliuhw.html

[S29] C：变参函数
来源：http://dali.zhixingplan.top/Article/details/gt2clrxsivb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yuxming.cn/Article/details/gt2hquqpwti.html

[S30] C：头文件保护
来源：http://dali.andypj.xyz/Article/details/gt2xclxapru.html

#ifndef X_H
来源：http://dali.cdnleiting.top/Article/details/gt2tjghbzvi.html

#define X_H
来源：http://dali.zhoulong.xyz/Article/details/gt2aouukrcr.html

#endif
来源：http://dali.hnqzz.top/Article/details/gt2msrndxuv.html

[S31] C++：Hello World
来源：http://dali.bjfxy.top/Article/details/gt2cnhukpkf.html

#include <iostream>
来源：http://dali.jlsjyb.cn/Article/details/gt2mnriwnkt.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ehwqpu.com/Article/details/gt2ykhysfos.html

[S32] C++：字符串
来源：http://dali.xinyue.icu/Article/details/gt2tbzjvhmq.html

std::string s = "hi";  s += "!";
来源：http://dali.meibo888.top/Article/details/gt2wbcihzag.html

[S33] C++：vector 增删
来源：http://dali.hongshengwenyu.top/Article/details/gt2hbikdxji.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sxryk.cn/Article/details/gt2nfuegfng.html

[S34] C++：遍历 vector
来源：http://dali.yj20258.top/Article/details/gt2qhjlluma.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.c1oappe.top/Article/details/gt2esieakjo.html

[S35] C++：map
来源：http://dali.snrcjt.cn/Article/details/gt2mwuhbuxj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fengsongda.top/Article/details/gt2kkrteeww.html

[S36] C++：unordered_map
来源：http://dali.hfpthk.cn/Article/details/gt2jkyaxlju.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gt2rfcyymjw.html

[S37] C++：set
来源：http://dali.pycfn.com/Article/details/gt2safesfzx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sysykeji.top/Article/details/gt2ialuyemj.html

[S38] C++：排序
来源：http://dali.sysykeji.top/Article/details/gt2pqhmqxwa.html

std::sort(v.begin(), v.end());
来源：http://dali.yj20258.top/Article/details/gt2qqdaiiey.html

[S39] C++：自定义比较器排序
来源：http://dali.guowangkeji.top/Article/details/gt2wwnycvri.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.guowangkeji.top/Article/details/gt2ztfvmbcy.html

[S40] C++：查找元素
来源：http://dali.kuanghao11.cn/Article/details/gt2qifehwai.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sweek.top/Article/details/gt2xoegclpk.html

[S41] C++：类与构造函数
来源：http://dali.sysykeji.top/Article/details/gt2qssztnzo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.dashuyun.cn/Article/details/gt2keejmjrh.html

[S42] C++：继承与虚函数
来源：http://dali.hammf.cn/Article/details/gt2halyakgc.html

class B : public Base { public: void f() override {} };
来源：http://dali.gaohongyu789.top/Article/details/gt2wmqwxnxx.html

[S43] C++：智能指针
来源：http://dali.snrcjt.cn/Article/details/gt2sromkqxp.html

auto p = std::make_unique<int>(5);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2milqypvd.html

[S44] C++：引用传参
来源：http://dali.jiagoushi.top/Article/details/gt2akmoeuvv.html

void inc(int &x) { ++x; }
来源：http://dali.yj202588.top/Article/details/gt2zdxlyjne.html

[S45] C++：lambda
来源：http://dali.yvedp.cn/Article/details/gt2oktfuqfb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hysaishi.cn/Article/details/gt2rodfdnho.html

[S46] C++：函数模板
来源：http://dali.andypj.xyz/Article/details/gt2tdpbtwnu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yuanzhike.top/Article/details/gt2rcyjrwic.html

[S47] C++：结构化绑定遍历
来源：http://dali.jyoumei.cn/Article/details/gt2laodktot.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cucudq.cn/Article/details/gt2ixawioeb.html

[S48] C++：逐行读文件
来源：http://dali.aizwys.cn/Article/details/gt2whkhmhcf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shangyingyoupin.top/Article/details/gt2iguvcnqu.html

while (std::getline(in, line)) { }
来源：http://dali.yangfankeji.com/Article/details/gt2jazoyord.html

[S49] C++：写文件
来源：http://dali.zhoulong.xyz/Article/details/gt2oueebbmd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yangfankeji.com/Article/details/gt2unvnhuhr.html

[S50] C++：格式化数字
来源：http://dali.jqgufenzy.top/Article/details/gt2whgoimqh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.316326.xyz/Article/details/gt2jcvczbmp.html

[S51] C++：显式类型转换
来源：http://dali.snrcjt.cn/Article/details/gt2sptzjdwi.html

static_cast<double>(a) / b
来源：http://dali.yj20258.top/Article/details/gt2lfgiqfqo.html

[S52] C++：const 与 noexcept
来源：http://dali.dianchejie.cn/Article/details/gt2osraezul.html

int size() const noexcept { return n_; }
来源：http://dali.zhongyouzk.top/Article/details/gt2aionbdaw.html

[S53] C++：移动语义
来源：http://dali.zhiwuduotai.top/Article/details/gt2lhvfavkq.html

std::vector<int> w = std::move(v);
来源：http://dali.zycfv.cn/Article/details/gt2ugppkpod.html

[S54] C++：异常处理
来源：http://dali.jyoumei.cn/Article/details/gt2rekogurt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhixingplan.top/Article/details/gt2irkonesl.html

[S55] C++：结构化绑定
来源：http://dali.xuanzx.com/Article/details/gt2xieytmaa.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ydzc1.top/Article/details/gt2vujfgvcy.html

[S56] C++：optional
来源：http://dali.yongpay.top/Article/details/gt2ntzbskvu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.c1oappe.top/Article/details/gt2llyufrjb.html

[S57] C++：编译期常量
来源：http://dali.zhoulong.xyz/Article/details/gt2idniapdp.html

constexpr int N = 10;
来源：http://dali.yuxming.cn/Article/details/gt2wrcuakob.html

[S58] C++：命名空间
来源：http://dali.ydzc1.top/Article/details/gt2fouortna.html

namespace ns { int f() { return 1; } }
来源：http://dali.gotoacloud.top/Article/details/gt2dmpjwmjb.html

[S59] C++：静态断言
来源：http://dali.c1oappe.top/Article/details/gt2gmpiwkfn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.tianlin.xyz/Article/details/gt2hrblqgvm.html

[S60] C++：遍历并删除元素
来源：http://dali.zdqjudy.top/Article/details/gt2faylolix.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xuetiantiany.cn/Article/details/gt2babowktd.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gt2mkptpkhw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sxryk.cn/Article/details/gt2hrgofqra.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2owzglung.html

[T01] Kotlin：Hello World
来源：http://dali.fengsongda.top/Article/details/gt2oidttczg.html

println("Hello")
来源：http://dali.zhongyouzk.top/Article/details/gt2pgskxkbn.html

[T02] Kotlin：变量
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ymtmaobp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cheryme.top/Article/details/gt2sfhbeecw.html

[T03] Kotlin：字符串模板
来源：http://dali.ehwqpu.com/Article/details/gt2pgffxmbr.html

"值: $b"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ookatrco.html

[T04] Kotlin：空安全
来源：http://dali.ivvv.top/Article/details/gt2kmufgghw.html

val n: String? = null;  n?.length
来源：http://dali.ydzc1.top/Article/details/gt2rmoywlbv.html

[T05] Kotlin：when 表达式
来源：http://dali.yuxming.cn/Article/details/gt2pvbacwpq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yvedp.cn/Article/details/gt2vzsipjqf.html

[T06] Kotlin：集合映射
来源：http://dali.snrcjt.cn/Article/details/gt2uohfihls.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gogol.net.cn/Article/details/gt2ujypapfh.html

[T07] Kotlin：集合过滤
来源：http://dali.jianghu66.top/Article/details/gt2mewteobr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.wangdashe.top/Article/details/gt2xvwtlvla.html

[T08] Kotlin：数据类
来源：http://dali.yuxming.cn/Article/details/gt2vkrleboz.html

data class User(val name: String, val age: Int)
来源：http://dali.daria6918.cn/Article/details/gt2yacihypa.html

[T09] Kotlin：扩展函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rnetfblo.html

fun String.exclaim() = this + "!"
来源：http://dali.jinqigufen.top/Article/details/gt2ierqncus.html

[T10] Kotlin：默认参数
来源：http://dali.gotoacloud.top/Article/details/gt2rouhsobk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hywenlv.cn/Article/details/gt2aobaoprr.html

[T11] Kotlin：协程
来源：http://dali.cheryme.top/Article/details/gt2cmnkzjhg.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhengqikj.top/Article/details/gt2xzabidgp.html

[T12] Kotlin：解构声明
来源：http://dali.shangyingyoupin.top/Article/details/gt2kjdcrrje.html

val (a, b) = Pair(1, 2)
来源：http://dali.daxiang520.top/Article/details/gt2njjuhhis.html

[T13] Kotlin：只读 Map
来源：http://dali.daxiang520.top/Article/details/gt2rwvaetgf.html

val m = mapOf("a" to 1)
来源：http://dali.jianghu66.top/Article/details/gt2jkglohig.html

[T14] Kotlin：循环
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jegrmyog.html

for (i in 1..10) println(i)
来源：http://dali.shzxlz.cn/Article/details/gt2ojrxvarm.html

[T15] Kotlin：接口
来源：http://dali.nanxinkj.top/Article/details/gt2tgapydhb.html

interface Shape { fun area(): Double }
来源：http://dali.jqgfzy.top/Article/details/gt2tzlskbtu.html

[T16] Swift：Hello World
来源：http://dali.nwbrower.top/Article/details/gt2onaaznvs.html

print("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gt2xgynpjty.html

[T17] Swift：变量与常量
来源：http://dali.hammf.cn/Article/details/gt2ynrmqnhm.html

var a = 1;  let b = 2
来源：http://dali.bjfxy.top/Article/details/gt2bvwcgfce.html

[T18] Swift：字符串插值
来源：http://dali.jqgfzy.top/Article/details/gt2stylqmbm.html

"值: \(b)"
来源：http://dali.jqgufenzy.top/Article/details/gt2dqfbrbls.html

[T19] Swift：可选绑定
来源：http://dali.yj20258.top/Article/details/gt2ytlasuyu.html

if let n = opt { print(n) }
来源：http://dali.jianghu66.top/Article/details/gt2wgsfhknu.html

[T20] Swift：数组操作
来源：http://dali.cheryme.top/Article/details/gt2idpigfey.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.316326.xyz/Article/details/gt2pyoldbij.html

[T21] Swift：遍历
来源：http://dali.sxryk.cn/Article/details/gt2usgthxqn.html

for x in a { print(x) }
来源：http://dali.pengpengdd.cyou/Article/details/gt2fhhxcytr.html

[T22] Swift：字典
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oiifgdkv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.9152youxi.cn/Article/details/gt2ekssbsna.html

[T23] Swift：函数
来源：http://dali.sufxvd.cn/Article/details/gt2wrmqofuj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhoulong.xyz/Article/details/gt2xyruqkig.html

[T24] Swift：闭包
来源：http://dali.shzxlz.cn/Article/details/gt2ejkrdcjm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.gotoacloud.top/Article/details/gt2ttuhqraq.html

[T25] Swift：结构体
来源：http://dali.havefunace.top/Article/details/gt2xpdamfld.html

struct P { var x: Int }
来源：http://dali.tian-w.cn/Article/details/gt2tvtrnbxx.html

[T26] Swift：类与重写
来源：http://dali.andypj.xyz/Article/details/gt2geyejgtl.html

class A: Base { override func f() {} }
来源：http://dali.meibo888.top/Article/details/gt2xweisfrr.html

[T27] Swift：错误处理
来源：http://dali.iojbl.cn/Article/details/gt2iupfzhaw.html

do { try f() } catch { print(error) }
来源：http://dali.jlsjyb.cn/Article/details/gt2cxyikagk.html

[T28] Swift：枚举
来源：http://dali.nanxinkj.top/Article/details/gt2ggrgvqyr.html

enum Color { case red, green }
来源：http://dali.hnqzz.top/Article/details/gt2xgxjplqv.html

[T29] Swift：guard 提前返回
来源：http://dali.gaohongyu789.top/Article/details/gt2jqzoctjp.html

guard let x = opt else { return }
来源：http://dali.hnxiangtu.top/Article/details/gt2yqhhrvny.html

[T30] Swift：协议
来源：http://dali.zycfv.cn/Article/details/gt2wfnxipqp.html

protocol Shape { func area() -> Double }
来源：http://dali.zycfv.cn/Article/details/gt2sftfffmw.html

[T31] Lua：Hello World
来源：http://dali.gzhubu.top/Article/details/gt2vygqmvog.html

print("Hello")
来源：http://dali.jianghu66.top/Article/details/gt2rodjgubh.html

[T32] Lua：局部变量
来源：http://dali.cucudq.cn/Article/details/gt2tznszcfi.html

local a = 1
来源：http://dali.hfpthk.cn/Article/details/gt2bqvbkzrs.html

[T33] Lua：表（数组）
来源：http://dali.svipenyu.cn/Article/details/gt2ysrargnf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hfpthk.cn/Article/details/gt2zotxixyu.html

[T34] Lua：遍历表
来源：http://dali.hywenlv.cn/Article/details/gt2hfpmxmxk.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jiagoushi.top/Article/details/gt2emtwkcpk.html

[T35] Lua：字典表
来源：http://dali.svipenyu.cn/Article/details/gt2nputspkb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ybcxt.top/Article/details/gt2fhkwvjck.html

[T36] Lua：函数
来源：http://dali.gzhubu.top/Article/details/gt2ecaczepb.html

function add(a, b) return a + b end
来源：http://dali.xylfe.cn/Article/details/gt2rahzmlsi.html

[T37] Lua：字符串拼接
来源：http://dali.jyoumei.cn/Article/details/gt2xkxubfrp.html

"a" .. "b"
来源：http://dali.daria6918.cn/Article/details/gt2mrcmqkrb.html

[T38] Lua：条件
来源：http://dali.snrcjt.cn/Article/details/gt2pppzayuu.html

if x > 0 then print("正") end
来源：http://dali.feifeiyinyue.top/Article/details/gt2gbjudkds.html

[T39] Lua：模式匹配
来源：http://dali.kuanghao11.cn/Article/details/gt2oyvhxcxa.html

string.find(s, "%d+")
来源：http://dali.gogol.net.cn/Article/details/gt2wselxvcm.html

[T40] Lua：元表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mtwtfqiq.html

setmetatable({}, { __index = base })
来源：http://dali.yongpay.top/Article/details/gt2tnzvlhgt.html

[T41] Perl：Hello World
来源：http://dali.mhx1999.top/Article/details/gt2ayorabch.html

print "Hello\n";
来源：http://dali.guowangkeji.top/Article/details/gt2fepauevz.html

[T42] Perl：变量类型
来源：http://dali.cdnleiting.top/Article/details/gt2fhlxktzi.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.chenzaomai.com/Article/details/gt2ghofrayw.html

[T43] Perl：字符串插值
来源：http://dali.nanxinkj.top/Article/details/gt2dpbyikmz.html

"值: $a"
来源：http://dali.cheryme.top/Article/details/gt2aewdeexp.html

[T44] Perl：条件
来源：http://dali.chenlongwang.top/Article/details/gt2fupvdccz.html

if ($a > 0) { print "正"; }
来源：http://dali.daria6918.cn/Article/details/gt2jpspjjyi.html

[T45] Perl：数组遍历
来源：http://dali.jiagoushi.top/Article/details/gt2ltledkxc.html

for my $x (@arr) { print $x; }
来源：http://dali.gzhubu.top/Article/details/gt2qtosqdyf.html

[T46] Perl：哈希操作
来源：http://dali.wangdashe.top/Article/details/gt2dzpkcjkm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jiagoushi.top/Article/details/gt2tuxyhbhp.html

[T47] Perl：正则捕获
来源：http://dali.xylfe.cn/Article/details/gt2ffqenoek.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wivgbufl.html

[T48] Perl：正则替换
来源：http://dali.daria6918.cn/Article/details/gt2memeeduc.html

$s =~ s/old/new/g;
来源：http://dali.ydzc1.top/Article/details/gt2wwqygzth.html

[T49] Perl：函数
来源：http://dali.quarkkingdee.top/Article/details/gt2glketgsl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.iojbl.cn/Article/details/gt2zysorlxn.html

[T50] Perl：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gt2vwjlhoes.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.tian-w.cn/Article/details/gt2sdbireqz.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yueranfly.top/Article/details/gt2uzcvxjjr.html

[T51] Scala：Hello World
来源：http://dali.snrcjt.cn/Article/details/gt2yusbhyzm.html

println("Hello")
来源：http://dali.yuanzhike.top/Article/details/gt2lmyhjcve.html

[T52] Scala：变量
来源：http://dali.xylfe.cn/Article/details/gt2dtiyzswk.html

val a = 1;  var b = 2
来源：http://dali.sweek.top/Article/details/gt2uulzjzvb.html

[T53] Scala：字符串插值
来源：http://dali.c1oappe.top/Article/details/gt2udyicesl.html

s"值: $b"
来源：http://dali.chenzaomai.com/Article/details/gt2rwjzkjhc.html

[T54] Scala：集合映射
来源：http://dali.aibaodan.cn/Article/details/gt2pdpeexgy.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.daria6918.cn/Article/details/gt2zexzoocl.html

[T55] Scala：集合过滤
来源：http://dali.fengsongda.top/Article/details/gt2kwudrhzy.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hnqzz.top/Article/details/gt2ehyagodh.html

[T56] Scala：样例类
来源：http://dali.yonumen.top/Article/details/gt2aacwwtwa.html

case class User(name: String, age: Int)
来源：http://dali.yuxming.cn/Article/details/gt2fhnpnljp.html

[T57] Scala：模式匹配
来源：http://dali.yongpay.top/Article/details/gt2jsggcfsd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.havefunace.top/Article/details/gt2xejoxxpr.html

[T58] Scala：函数定义
来源：http://dali.nwbrower.top/Article/details/gt2ybokwcih.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.ppjwa.cn/Article/details/gt2mmoecjcg.html

[T59] Scala：循环
来源：http://dali.wangdashe.top/Article/details/gt2fixmsakw.html

for (i <- 1 to 10) println(i)
来源：http://dali.yuanzhike.top/Article/details/gt2tjdanglh.html

[T60] Scala：折叠
来源：http://dali.aibaodan.cn/Article/details/gt2rbyjuwhq.html


<!-- 参考信息 -->