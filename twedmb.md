代发 wailian999

ssh user@host 'uptime'
来源：http://dali.nanxinkj.top/Article/details/gt2qrejtrsi.html

[R58] 下载文件
来源：http://dali.havefunace.top/Article/details/gt2lbyjpjhw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sysykeji.top/Article/details/gt2kijwmhpq.html

[R59] 发 POST JSON
来源：http://dali.vqdsnc.cn/Article/details/gt2dofmadoa.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhongyouzk.top/Article/details/gt2usbtqwvc.html

[R60] 只看 HTTP 状态码
来源：http://dali.jqgfzy.top/Article/details/gt2wscnihaw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.wangshuangyany.cn/Article/details/gt2lxzvgdgl.html

[R61] 磁盘占用
来源：http://dali.zycfv.cn/Article/details/gt2ykexlwcr.html

df -h;  du -sh *
来源：http://dali.chenjidiqi.icu/Article/details/gt2pcgdwovd.html

[R62] 找最占空间的文件
来源：http://dali.tanke756.top/Article/details/gt2nrhvtfqo.html

du -ah . | sort -rh | head -10
来源：http://dali.hammf.cn/Article/details/gt2iklupsuy.html

[R63] 内存与进程
来源：http://dali.jyoumei.cn/Article/details/gt2rpcxrrms.html

free -h;  ps aux | grep nginx
来源：http://dali.jiagoushi.top/Article/details/gt2awupacdr.html

[R64] 结束进程
来源：http://dali.dianchejie.cn/Article/details/gt2ivhbtfsq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ohscxfhr.html

[R65] 查看端口占用
来源：http://dali.ivvv.top/Article/details/gt2naafzxsq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yvedp.cn/Article/details/gt2ehhusuqd.html

[R66] 定时任务
来源：http://dali.gotoacloud.top/Article/details/gt2tykfsvgw.html

crontab -e;  crontab -l
来源：http://dali.svipenyu.cn/Article/details/gt2tlckmfgu.html

[R67] 生成随机十六进制串
来源：http://dali.aibaodan.cn/Article/details/gt2riljjnww.html

openssl rand -hex 16
来源：http://dali.fengsongda.top/Article/details/gt2nbaetszc.html

[R68] 计算文件校验值
来源：http://dali.tianlin.xyz/Article/details/gt2hevtqlqv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sxryk.cn/Article/details/gt2ewznwscl.html

[R69] 生成随机密码
来源：http://dali.gogol.net.cn/Article/details/gt2wxmevzao.html

head -c 16 /dev/urandom | base64
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xhzlklyq.html

[R70] 时间戳与互转
来源：http://dali.zhengqikj.top/Article/details/gt2qyvjfowt.html

date +%s;  date -d @1700000000
来源：http://dali.jinqigufen.top/Article/details/gt2lrayktin.html

[R71] 日期格式化
来源：http://dali.xziqi.cn/Article/details/gt2nkxrbwbt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.havefunace.top/Article/details/gt2pfwvktjp.html

[R72] 等待端口就绪
来源：http://dali.meibo888.top/Article/details/gt2tpglfqka.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.chenzaomai.com/Article/details/gt2evknwoqv.html

[R73] 分割大日志
来源：http://dali.gogol.net.cn/Article/details/gt2bdyzhftz.html

split -l 1000 big.log part_
来源：http://dali.andypj.xyz/Article/details/gt2llwtsvtm.html

[R74] 批量重命名
来源：http://dali.shzxlz.cn/Article/details/gt2yenuqquy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2quzteslp.html

[R75] 导出环境变量
来源：http://dali.bjfxy.top/Article/details/gt2wlppycvs.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ppjwa.cn/Article/details/gt2tytvnzlc.html

[R76] 使用临时文件
来源：http://dali.yj20258.top/Article/details/gt2nvjcjpzu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.andypj.xyz/Article/details/gt2kdkzapkk.html

[R77] 读取用户输入
来源：http://dali.jinqigufen.top/Article/details/gt2jkjtixha.html

read -rp "请输入: " ans
来源：http://dali.ivvv.top/Article/details/gt2urxslajv.html

[R78] 交互式菜单
来源：http://dali.pycfn.com/Article/details/gt2kejyeasc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ybcxt.top/Article/details/gt2uwrofbst.html

[R79] 解析命令行选项
来源：http://dali.hysaishi.cn/Article/details/gt2hrlgcqfk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.0kj1m.cn/Article/details/gt2ktfnoxbz.html

[R80] 查看脚本执行耗时
来源：http://dali.haohaochexian.top/Article/details/gt2rpsqmxox.html

time ./run.sh
来源：http://dali.hfpthk.cn/Article/details/gt2ffgxnhnu.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2gyufogzs.html

S. C / C++ 专题
来源：http://dali.snrcjt.cn/Article/details/gt2urultiaj.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2quvcwnpx.html

[S01] C：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gt2wcoriowd.html

#include <stdio.h>
来源：http://dali.zhongyouzk.top/Article/details/gt2kxoyfrhx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.dashuyun.cn/Article/details/gt2ijzxgwht.html

[S02] C：变量与格式化输出
来源：http://dali.jinqigufen.top/Article/details/gt2rntgvuqp.html

int a = 10; printf("%d\n", a);
来源：http://dali.daxiang520.top/Article/details/gt2iqzhouhd.html

[S03] C：读入整数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2zrltwltl.html

int x; scanf("%d", &x);
来源：http://dali.fzhhl.top/Article/details/gt2uqkeqyoz.html

[S04] C：字符串复制
来源：http://dali.cheryme.top/Article/details/gt2xuslqqes.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yuanzhike.top/Article/details/gt2wboqpjjw.html

[S05] C：字符串长度
来源：http://dali.yanxiufei.cn/Article/details/gt2wvoyhglp.html

strlen(s)
来源：http://dali.pengpengdd.cyou/Article/details/gt2mjxhwbgk.html

[S06] C：字符串比较
来源：http://dali.pycfn.com/Article/details/gt2froyrhcp.html

strcmp(a, b) == 0
来源：http://dali.ppjwa.cn/Article/details/gt2nxqgumqo.html

[S07] C：数组遍历求和
来源：http://dali.zhoulong.xyz/Article/details/gt2lxztoetr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yangfankeji.com/Article/details/gt2jpnyiarb.html

[S08] C：动态内存分配与释放
来源：http://dali.shuidangran.top/Article/details/gt2dhetehjp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nanxuanxn.top/Article/details/gt2vspywuhg.html

[S09] C：结构体定义与初始化
来源：http://dali.fengsongda.top/Article/details/gt2drrzfcqe.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.316326.xyz/Article/details/gt2rvutscfo.html

[S10] C：指针与解引用
来源：http://dali.pycfn.com/Article/details/gt2jwqxxtfn.html

int *p = &a;  *p = 5;
来源：http://dali.ybcxt.top/Article/details/gt2vbkwypxo.html

[S11] C：逐行读文件
来源：http://dali.cashguo.top/Article/details/gt2jdfsqkth.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yangfankeji.com/Article/details/gt2sxedhliv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2oijachlu.html

fclose(f);
来源：http://dali.mhx1999.top/Article/details/gt2ybuhilcu.html

[S12] C：写文件
来源：http://dali.birdmap.top/Article/details/gt2eowkekkd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj20258888.top/Article/details/gt2hgijrhqm.html

[S13] C：宏定义
来源：http://dali.jqgfzy.top/Article/details/gt2ugopaxvj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yj20258.top/Article/details/gt2bksljoce.html

[S14] C：枚举
来源：http://dali.yvedp.cn/Article/details/gt2rqbercid.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.pycfn.com/Article/details/gt2cfcolobj.html

[S15] C：类型转换
来源：http://dali.yj20258888.top/Article/details/gt2ovemykmy.html

(double) a / b
来源：http://dali.cdnleiting.top/Article/details/gt2hcfbbqra.html

[S16] C：位操作置位
来源：http://dali.yvedp.cn/Article/details/gt2hrtuymzc.html

x |= (1 << 3);
来源：http://dali.sufxvd.cn/Article/details/gt2abdznghk.html

[S17] C：安全拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gt2nnukljxm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.bjfxy.top/Article/details/gt2zejsiait.html

[S18] C：命令行参数
来源：http://dali.316326.xyz/Article/details/gt2xusyzabl.html

int main(int argc, char **argv)
来源：http://dali.zhoulong.xyz/Article/details/gt2lyjxlpyl.html

[S19] C：快速排序
来源：http://dali.yuxming.cn/Article/details/gt2ynqvjtzc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.tianlin.xyz/Article/details/gt2arpnvkic.html

[S20] C：二分查找
来源：http://dali.zhongyouzk.top/Article/details/gt2lqicetgc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.chenjidiqi.icu/Article/details/gt2swxahklx.html

[S21] C：字符类别判断
来源：http://dali.316326.xyz/Article/details/gt2jfjbfcmv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cucudq.cn/Article/details/gt2zvuutxok.html

[S22] C：字符串转数字
来源：http://dali.gogol.net.cn/Article/details/gt2ssurahnn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ivvv.top/Article/details/gt2ieqohask.html

[S23] C：随机数
来源：http://dali.sysykeji.top/Article/details/gt2ehexcrvu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.wangdashe.top/Article/details/gt2cpoljunv.html

[S24] C：获取本地时间
来源：http://dali.dashuyun.cn/Article/details/gt2ehzxurin.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.vqdsnc.cn/Article/details/gt2fwlbhzlc.html

[S25] C：内存拷贝
来源：http://dali.zdqjudy.top/Article/details/gt2yzllhnwp.html

memcpy(dst, src, n);
来源：http://dali.pycfn.com/Article/details/gt2heimtfzt.html

[S26] C：内存清零
来源：http://dali.shuidangran.top/Article/details/gt2juzmader.html

memset(a, 0, sizeof a);
来源：http://dali.fengsongda.top/Article/details/gt2xletmnxb.html

[S27] C：定义常量
来源：http://dali.jiagoushi.top/Article/details/gt2drqpomna.html

const double PI = 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gt2dusutqvq.html

[S28] C：静态变量
来源：http://dali.iojbl.cn/Article/details/gt2wtvcojbo.html

static int counter = 0;
来源：http://dali.chenjidiqi.icu/Article/details/gt2bbxxtrua.html

[S29] C：变参函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2nxkbjqdv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cashguo.top/Article/details/gt2krxxofab.html

[S30] C：头文件保护
来源：http://dali.xziqi.cn/Article/details/gt2hxlpmvil.html

#ifndef X_H
来源：http://dali.tianlin.xyz/Article/details/gt2iafmkrhe.html

#define X_H
来源：http://dali.snrcjt.cn/Article/details/gt2hnlovbsx.html

#endif
来源：http://dali.hnqzz.top/Article/details/gt2sxpslvvf.html

[S31] C++：Hello World
来源：http://dali.zhixingplan.top/Article/details/gt2bjgpovvw.html

#include <iostream>
来源：http://dali.xuetiantiany.cn/Article/details/gt2lucoukdy.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2bsqfzkwe.html

[S32] C++：字符串
来源：http://dali.nanxuanxn.top/Article/details/gt2vwerpeie.html

std::string s = "hi";  s += "!";
来源：http://dali.birdmap.top/Article/details/gt2jxpucrmg.html

[S33] C++：vector 增删
来源：http://dali.svipenyu.cn/Article/details/gt2zrzildrh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.chenlongwang.top/Article/details/gt2zzrauegb.html

[S34] C++：遍历 vector
来源：http://dali.nanxuanxn.top/Article/details/gt2ymfebznr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.vqdsnc.cn/Article/details/gt2gzuabuxm.html

[S35] C++：map
来源：http://dali.nwbrower.top/Article/details/gt2pxdtvxbm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xziqi.cn/Article/details/gt2esprymff.html

[S36] C++：unordered_map
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jhdlhnst.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cqqwz.cn/Article/details/gt2dfwmxpgl.html

[S37] C++：set
来源：http://dali.hywenlv.cn/Article/details/gt2sinzsoid.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dwqmjmfe.html

[S38] C++：排序
来源：http://dali.dashuyun.cn/Article/details/gt2gcunwfqn.html

std::sort(v.begin(), v.end());
来源：http://dali.yvedp.cn/Article/details/gt2erdnvoqb.html

[S39] C++：自定义比较器排序
来源：http://dali.hywenlv.cn/Article/details/gt2nimrvire.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenlongwang.top/Article/details/gt2xlczdohn.html

[S40] C++：查找元素
来源：http://dali.316326.xyz/Article/details/gt2kiuxzewd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.birdmap.top/Article/details/gt2ufwdqycl.html

[S41] C++：类与构造函数
来源：http://dali.yvedp.cn/Article/details/gt2yryxqijk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.snrcjt.cn/Article/details/gt2lnwadpzv.html

[S42] C++：继承与虚函数
来源：http://dali.gotoacloud.top/Article/details/gt2kmkufzha.html

class B : public Base { public: void f() override {} };
来源：http://dali.fengsongda.top/Article/details/gt2uwrafogb.html

[S43] C++：智能指针
来源：http://dali.gotoacloud.top/Article/details/gt2ofqveleo.html

auto p = std::make_unique<int>(5);
来源：http://dali.quarkkingdee.top/Article/details/gt2hzttnddx.html

[S44] C++：引用传参
来源：http://dali.tianlin.xyz/Article/details/gt2rppgmbfr.html

void inc(int &x) { ++x; }
来源：http://dali.tanke756.top/Article/details/gt2nhxaxshd.html

[S45] C++：lambda
来源：http://dali.ppjwa.cn/Article/details/gt2vsotwuav.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ybcxt.top/Article/details/gt2yyyseyap.html

[S46] C++：函数模板
来源：http://dali.cucudq.cn/Article/details/gt2gkrfbsfg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hongshengwenyu.top/Article/details/gt2hbotefdm.html

[S47] C++：结构化绑定遍历
来源：http://dali.guannengcc.top/Article/details/gt2kucigcoi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hnxiangtu.top/Article/details/gt2rwvrnely.html

[S48] C++：逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gt2pkubjqqz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ppjwa.cn/Article/details/gt2tzerovyb.html

while (std::getline(in, line)) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ckvhibab.html

[S49] C++：写文件
来源：http://dali.cucudq.cn/Article/details/gt2xzhdgikl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yj20258.top/Article/details/gt2ypmulhds.html

[S50] C++：格式化数字
来源：http://dali.nanxuanxn.top/Article/details/gt2emxozbcv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gt2bxbrheth.html

[S51] C++：显式类型转换
来源：http://dali.316326.xyz/Article/details/gt2kkikklaf.html

static_cast<double>(a) / b
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qsqqrmbu.html

[S52] C++：const 与 noexcept
来源：http://dali.316326.xyz/Article/details/gt2rxdmxmqo.html

int size() const noexcept { return n_; }
来源：http://dali.zhengqikj.top/Article/details/gt2ptrzaudf.html

[S53] C++：移动语义
来源：http://dali.yj20258.top/Article/details/gt2kjlvpegl.html

std::vector<int> w = std::move(v);
来源：http://dali.tian-w.cn/Article/details/gt2nkjlwqcu.html

[S54] C++：异常处理
来源：http://dali.birdmap.top/Article/details/gt2ppsludpa.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.guowangkeji.top/Article/details/gt2sevufhsy.html

[S55] C++：结构化绑定
来源：http://dali.feifeiyinyue.top/Article/details/gt2mnbjheln.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.c1oappe.top/Article/details/gt2jxxynndo.html

[S56] C++：optional
来源：http://dali.cdnleiting.top/Article/details/gt2hhsjmnfd.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yuxming.cn/Article/details/gt2iyjvbqxv.html

[S57] C++：编译期常量
来源：http://dali.yueranfly.top/Article/details/gt2ppgmaivq.html

constexpr int N = 10;
来源：http://dali.zhengqikj.top/Article/details/gt2wuqfdulr.html

[S58] C++：命名空间
来源：http://dali.kuanghao11.cn/Article/details/gt2bypjhliz.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhongyouzk.top/Article/details/gt2cnxquztq.html

[S59] C++：静态断言
来源：http://dali.cqqwz.cn/Article/details/gt2vmmogqod.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gogol.net.cn/Article/details/gt2mtnusgbg.html

[S60] C++：遍历并删除元素
来源：http://dali.wangshuangyany.cn/Article/details/gt2ftvdwxjd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ciuhcwnw.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gt2rpbdkxev.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xylfe.cn/Article/details/gt2ogihjcks.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gt2mthlxadv.html

[T01] Kotlin：Hello World
来源：http://dali.316326.xyz/Article/details/gt2xxcfufhm.html

println("Hello")
来源：http://dali.redwolf501.top/Article/details/gt2wavzlumw.html

[T02] Kotlin：变量
来源：http://dali.quarkkingdee.top/Article/details/gt2sklhdjzp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yonumen.top/Article/details/gt2diqdismb.html

[T03] Kotlin：字符串模板
来源：http://dali.jqgfzy.top/Article/details/gt2hlevwibn.html

"值: $b"
来源：http://dali.svipenyu.cn/Article/details/gt2idudjcdf.html

[T04] Kotlin：空安全
来源：http://dali.ehwqpu.com/Article/details/gt2fpppwxpm.html

val n: String? = null;  n?.length
来源：http://dali.wangshuangyany.cn/Article/details/gt2brweroxv.html

[T05] Kotlin：when 表达式
来源：http://dali.yj202588.top/Article/details/gt2zftdjzsy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.fengsongda.top/Article/details/gt2igamwict.html

[T06] Kotlin：集合映射
来源：http://dali.yueranfly.top/Article/details/gt2ivrlsqjl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.guannengcc.top/Article/details/gt2vnbpvuwl.html

[T07] Kotlin：集合过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jkixjssz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jlsjyb.cn/Article/details/gt2aqeagdvy.html

[T08] Kotlin：数据类
来源：http://dali.9152youxi.cn/Article/details/gt2qzvlhucl.html

data class User(val name: String, val age: Int)
来源：http://dali.jinqigufen.top/Article/details/gt2vnpnxumo.html

[T09] Kotlin：扩展函数
来源：http://dali.sufxvd.cn/Article/details/gt2yqsiwzvl.html

fun String.exclaim() = this + "!"
来源：http://dali.svipenyu.cn/Article/details/gt2etsfcscj.html

[T10] Kotlin：默认参数
来源：http://dali.xylfe.cn/Article/details/gt2kkzufqut.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hnqzz.top/Article/details/gt2ypxxsmpr.html

[T11] Kotlin：协程
来源：http://dali.zhixingplan.top/Article/details/gt2apboitoi.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.9152youxi.cn/Article/details/gt2nalxnmgc.html

[T12] Kotlin：解构声明
来源：http://dali.zhoulong.xyz/Article/details/gt2zlzmbrgb.html

val (a, b) = Pair(1, 2)
来源：http://dali.cheryme.top/Article/details/gt2cszsxzpf.html

[T13] Kotlin：只读 Map
来源：http://dali.hammf.cn/Article/details/gt2fdtiniaw.html

val m = mapOf("a" to 1)
来源：http://dali.redwolf501.top/Article/details/gt2xdyeittf.html

[T14] Kotlin：循环
来源：http://dali.sweek.top/Article/details/gt2wodjppks.html

for (i in 1..10) println(i)
来源：http://dali.guannengcc.top/Article/details/gt2cpivmvwl.html

[T15] Kotlin：接口
来源：http://dali.iojbl.cn/Article/details/gt2dopvuofq.html

interface Shape { fun area(): Double }
来源：http://dali.kuanghao11.cn/Article/details/gt2ohiylcio.html

[T16] Swift：Hello World
来源：http://dali.jqgfzy.top/Article/details/gt2douokqmy.html

print("Hello")
来源：http://dali.cdnleiting.top/Article/details/gt2udwrjffd.html

[T17] Swift：变量与常量
来源：http://dali.vqdsnc.cn/Article/details/gt2zkazlthr.html

var a = 1;  let b = 2
来源：http://dali.sweek.top/Article/details/gt2wlvjizni.html

[T18] Swift：字符串插值
来源：http://dali.snrcjt.cn/Article/details/gt2zdsgqowl.html

"值: \(b)"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cxovgxdn.html

[T19] Swift：可选绑定
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2polpyxjg.html

if let n = opt { print(n) }
来源：http://dali.yj20258.top/Article/details/gt2jthdgcuf.html

[T20] Swift：数组操作
来源：http://dali.xuanzx.com/Article/details/gt2tchxazyl.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xylfe.cn/Article/details/gt2yhbtrawz.html

[T21] Swift：遍历
来源：http://dali.guannengcc.top/Article/details/gt2pjprfkcl.html

for x in a { print(x) }
来源：http://dali.hysaishi.cn/Article/details/gt2lvvbiypw.html

[T22] Swift：字典
来源：http://dali.c1oappe.top/Article/details/gt2jwwiskpd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jiacdabn.html

[T23] Swift：函数
来源：http://dali.jinqigufen.top/Article/details/gt2opmnqldw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sxryk.cn/Article/details/gt2jkpjtpur.html

[T24] Swift：闭包
来源：http://dali.tianlin.xyz/Article/details/gt2jlqepvjg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gt2guqlooqo.html

[T25] Swift：结构体
来源：http://dali.gotoacloud.top/Article/details/gt2tajzxepn.html

struct P { var x: Int }
来源：http://dali.snrcjt.cn/Article/details/gt2oxhtidiw.html

[T26] Swift：类与重写
来源：http://dali.mhx1999.top/Article/details/gt2faxauxtj.html

class A: Base { override func f() {} }
来源：http://dali.yvedp.cn/Article/details/gt2rylrwohd.html

[T27] Swift：错误处理
来源：http://dali.jyoumei.cn/Article/details/gt2ukdqcbvh.html

do { try f() } catch { print(error) }
来源：http://dali.jinqigufen.top/Article/details/gt2adfkhmkp.html

[T28] Swift：枚举
来源：http://dali.vqdsnc.cn/Article/details/gt2syvuxnhe.html

enum Color { case red, green }
来源：http://dali.tianlin.xyz/Article/details/gt2hknvbdor.html

[T29] Swift：guard 提前返回
来源：http://dali.ybcxt.top/Article/details/gt2kdbbmyhm.html

guard let x = opt else { return }
来源：http://dali.ivvv.top/Article/details/gt2qeoovvlg.html

[T30] Swift：协议
来源：http://dali.zycfv.cn/Article/details/gt2ojrlxgxo.html

protocol Shape { func area() -> Double }
来源：http://dali.tian-w.cn/Article/details/gt2wdiquffx.html

[T31] Lua：Hello World
来源：http://dali.0kj1m.cn/Article/details/gt2svaxvthl.html

print("Hello")
来源：http://dali.chenlongwang.top/Article/details/gt2zrvqsslu.html

[T32] Lua：局部变量
来源：http://dali.zhiwuduotai.top/Article/details/gt2zhiviozw.html

local a = 1
来源：http://dali.yanxiufei.cn/Article/details/gt2ehgaezrf.html

[T33] Lua：表（数组）
来源：http://dali.hnqzz.top/Article/details/gt2ligqjzlp.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.gotoacloud.top/Article/details/gt2anqguwgs.html

[T34] Lua：遍历表
来源：http://dali.chenzaomai.com/Article/details/gt2qaewqthk.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.sweek.top/Article/details/gt2qmzejqhy.html

[T35] Lua：字典表
来源：http://dali.birdmap.top/Article/details/gt2pqxaryvo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.kuanghao11.cn/Article/details/gt2zyqqkfph.html

[T36] Lua：函数
来源：http://dali.cashguo.top/Article/details/gt2huprhurt.html

function add(a, b) return a + b end
来源：http://dali.hnxiangtu.top/Article/details/gt2djxsaxjz.html

[T37] Lua：字符串拼接
来源：http://dali.jlsjyb.cn/Article/details/gt2hhgxaiva.html

"a" .. "b"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jyvsapwi.html

[T38] Lua：条件
来源：http://dali.pengpengdd.cyou/Article/details/gt2xctewfrd.html

if x > 0 then print("正") end
来源：http://dali.tian-w.cn/Article/details/gt2qdtshifh.html

[T39] Lua：模式匹配
来源：http://dali.jqgufenzy.top/Article/details/gt2pqsjyalc.html

string.find(s, "%d+")
来源：http://dali.nwbrower.top/Article/details/gt2xqbowwft.html

[T40] Lua：元表
来源：http://dali.jiagoushi.top/Article/details/gt2nwmdrund.html

setmetatable({}, { __index = base })
来源：http://dali.hfpthk.cn/Article/details/gt2qojdyccs.html

[T41] Perl：Hello World
来源：http://dali.mhx1999.top/Article/details/gt2hpgpfyny.html

print "Hello\n";
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xgwxlhjd.html

[T42] Perl：变量类型
来源：http://dali.jinqigfzy.top/Article/details/gt2kzolcanj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.feifeiyinyue.top/Article/details/gt2hamohfyv.html

[T43] Perl：字符串插值
来源：http://dali.jyoumei.cn/Article/details/gt2qnmbvelh.html

"值: $a"
来源：http://dali.vqdsnc.cn/Article/details/gt2bjraljzh.html

[T44] Perl：条件
来源：http://dali.cheryme.top/Article/details/gt2ressxacm.html

if ($a > 0) { print "正"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vvchzfga.html

[T45] Perl：数组遍历
来源：http://dali.xinyue.icu/Article/details/gt2wkxhjaue.html

for my $x (@arr) { print $x; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2vltmoajl.html

[T46] Perl：哈希操作
来源：http://dali.cdnleiting.top/Article/details/gt2cjiskqpw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.dashuyun.cn/Article/details/gt2mcqredzf.html

[T47] Perl：正则捕获
来源：http://dali.fzhhl.top/Article/details/gt2eohmngny.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jqgfzy.top/Article/details/gt2wcmkxdzr.html

[T48] Perl：正则替换
来源：http://dali.pycfn.com/Article/details/gt2djfxmztu.html

$s =~ s/old/new/g;
来源：http://dali.cucudq.cn/Article/details/gt2shzkniqm.html

[T49] Perl：函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2onvbwhrf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xinyue.icu/Article/details/gt2kmpbuhec.html

[T50] Perl：逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gt2rxrtdzib.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yongpay.top/Article/details/gt2gtevsyvf.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.jqgfzy.top/Article/details/gt2fhoybkfd.html

[T51] Scala：Hello World
来源：http://dali.svipenyu.cn/Article/details/gt2jsmpwjyi.html

println("Hello")
来源：http://dali.ybcxt.top/Article/details/gt2bvfbhfpj.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qumcgaxa.html

val a = 1;  var b = 2
来源：http://dali.svipenyu.cn/Article/details/gt2asecsoej.html

[T53] Scala：字符串插值
来源：http://dali.ydzc1.top/Article/details/gt2hjrlqrbf.html

s"值: $b"
来源：http://dali.smart0.xyz/Article/details/gt2obsbunsl.html

[T54] Scala：集合映射
来源：http://dali.0kj1m.cn/Article/details/gt2zivezwux.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ivvv.top/Article/details/gt2otzmphaz.html

[T55] Scala：集合过滤
来源：http://dali.c1oappe.top/Article/details/gt2gwandkxm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.fengsongda.top/Article/details/gt2dmoaacdm.html

[T56] Scala：样例类
来源：http://dali.cheryme.top/Article/details/gt2vzzptdbx.html

case class User(name: String, age: Int)
来源：http://dali.jlsjyb.cn/Article/details/gt2arsazlvh.html

[T57] Scala：模式匹配
来源：http://dali.jqgufenzy.top/Article/details/gt2coufipzt.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.dashuyun.cn/Article/details/gt2qghsgnby.html

[T58] Scala：函数定义
来源：http://dali.zdqjudy.top/Article/details/gt2unwwqltu.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.birdmap.top/Article/details/gt2aomsivxb.html

[T59] Scala：循环
来源：http://dali.sufxvd.cn/Article/details/gt2vseucomi.html

for (i <- 1 to 10) println(i)
来源：http://dali.gzhubu.top/Article/details/gt2ctvliaac.html

[T60] Scala：折叠
来源：http://dali.hysaishi.cn/Article/details/gt2izutdcoz.html


<!-- 参考信息 -->