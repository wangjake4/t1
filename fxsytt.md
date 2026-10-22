代发 wailian999

df -h;  du -sh *
来源：http://dali.zdqjudy.top/Article/details/gtcfbvmhpu.html

[R62] 找最占空间的文件
来源：http://dali.jianghu66.top/Article/details/gtqnuehylg.html

du -ah . | sort -rh | head -10
来源：http://dali.haohaochexian.top/Article/details/gtnoyfmmaq.html

[R63] 内存与进程
来源：http://dali.xuanzx.com/Article/details/gtdyqsqxcy.html

free -h;  ps aux | grep nginx
来源：http://dali.jinyuanbaomall.cn/Article/details/gtribwodsc.html

[R64] 结束进程
来源：http://dali.cashguo.top/Article/details/gtdcspydot.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yj20258.top/Article/details/gtjtzlebbo.html

[R65] 查看端口占用
来源：http://dali.havefunace.top/Article/details/gtiopatzod.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.quarkkingdee.top/Article/details/gtoxdejlgf.html

[R66] 定时任务
来源：http://dali.andypj.xyz/Article/details/gtxwqwzatx.html

crontab -e;  crontab -l
来源：http://dali.xinyue.icu/Article/details/gtxoxnwowq.html

[R67] 生成随机十六进制串
来源：http://dali.zycfv.cn/Article/details/gtymvxihay.html

openssl rand -hex 16
来源：http://dali.yuxming.cn/Article/details/gtjpoverlp.html

[R68] 计算文件校验值
来源：http://dali.hnxiangtu.top/Article/details/gtauhtgvds.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zycfv.cn/Article/details/gtpojwuzvj.html

[R69] 生成随机密码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwveavmti.html

head -c 16 /dev/urandom | base64
来源：http://dali.sufxvd.cn/Article/details/gttbpltyjc.html

[R70] 时间戳与互转
来源：http://dali.316326.xyz/Article/details/gtpszneidm.html

date +%s;  date -d @1700000000
来源：http://dali.fengsongda.top/Article/details/gtfwehxfvz.html

[R71] 日期格式化
来源：http://dali.jlsjyb.cn/Article/details/gtnknxwefb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.c1oappe.top/Article/details/gtnghotxjc.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gtysewoftf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gzhubu.top/Article/details/gtuelgytva.html

[R73] 分割大日志
来源：http://dali.yuanzhike.top/Article/details/gtobcgvzbs.html

split -l 1000 big.log part_
来源：http://dali.haohaochexian.top/Article/details/gtfzcrmecx.html

[R74] 批量重命名
来源：http://dali.cashguo.top/Article/details/gtvsztoijf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yj202588.top/Article/details/gtczhqxpxi.html

[R75] 导出环境变量
来源：http://dali.havefunace.top/Article/details/gtgaywenbe.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.chenzaomai.com/Article/details/gtdjhqmoem.html

[R76] 使用临时文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyvfjkyam.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jianghu66.top/Article/details/gtqlzijduc.html

[R77] 读取用户输入
来源：http://dali.ppjwa.cn/Article/details/gtxuxhczbs.html

read -rp "请输入: " ans
来源：http://dali.jinqigfzy.top/Article/details/gtkukwnzpy.html

[R78] 交互式菜单
来源：http://dali.yanxiufei.cn/Article/details/gtybttbvzb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaviwmwxw.html

[R79] 解析命令行选项
来源：http://dali.jqgufenzy.top/Article/details/gtljulicvx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sufxvd.cn/Article/details/gtudsjjmwl.html

[R80] 查看脚本执行耗时
来源：http://dali.gogol.net.cn/Article/details/gtbkhngprt.html

time ./run.sh
来源：http://dali.meibo888.top/Article/details/gtjbjiesor.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtaprifvfi.html

S. C / C++ 专题
来源：http://dali.dianchejie.cn/Article/details/gtyyqkyapl.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gthqdgfqiu.html

[S01] C：Hello World
来源：http://dali.hammf.cn/Article/details/gtuzwesykf.html

#include <stdio.h>
来源：http://dali.gaohongyu789.top/Article/details/gtlbdwuwhc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.guannengcc.top/Article/details/gtdxswvekf.html

[S02] C：变量与格式化输出
来源：http://dali.gogol.net.cn/Article/details/gtllwcdozr.html

int a = 10; printf("%d\n", a);
来源：http://dali.yonumen.top/Article/details/gtajgrsvlv.html

[S03] C：读入整数
来源：http://dali.cashguo.top/Article/details/gtsslalojn.html

int x; scanf("%d", &x);
来源：http://dali.guowangkeji.top/Article/details/gtnopwsqeb.html

[S04] C：字符串复制
来源：http://dali.dianchejie.cn/Article/details/gtpwkmnvzj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.fengsongda.top/Article/details/gtfiirgyla.html

[S05] C：字符串长度
来源：http://dali.c1oappe.top/Article/details/gthyfqqdsm.html

strlen(s)
来源：http://dali.meibo888.top/Article/details/gtmcpanbhd.html

[S06] C：字符串比较
来源：http://dali.ehwqpu.com/Article/details/gtsxfnsxly.html

strcmp(a, b) == 0
来源：http://dali.zhoulong.xyz/Article/details/gtyytyipas.html

[S07] C：数组遍历求和
来源：http://dali.fengsongda.top/Article/details/gtjmattgvv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shzxlz.cn/Article/details/gtoasarawf.html

[S08] C：动态内存分配与释放
来源：http://dali.yvedp.cn/Article/details/gtblpxgekh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zycfv.cn/Article/details/gtbzotmmgr.html

[S09] C：结构体定义与初始化
来源：http://dali.mhx1999.top/Article/details/gtjylrfgyx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.chenlongwang.top/Article/details/gtglcbcrup.html

[S10] C：指针与解引用
来源：http://dali.meibo888.top/Article/details/gtfrmuxupe.html

int *p = &a;  *p = 5;
来源：http://dali.hfpthk.cn/Article/details/gtibfybwal.html

[S11] C：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gtnzpehkje.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.tanke756.top/Article/details/gtpidiupaa.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.mhx1999.top/Article/details/gtjdclmftu.html

fclose(f);
来源：http://dali.cashguo.top/Article/details/gtckhvrosg.html

[S12] C：写文件
来源：http://dali.guowangkeji.top/Article/details/gtzvaipvzg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sweek.top/Article/details/gtnymtovwl.html

[S13] C：宏定义
来源：http://dali.yonumen.top/Article/details/gtzqpkjoxt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zycfv.cn/Article/details/gtlqgdqtuz.html

[S14] C：枚举
来源：http://dali.dashuyun.cn/Article/details/gtnenmlgub.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.chenjidiqi.icu/Article/details/gtvpaczrjy.html

[S15] C：类型转换
来源：http://dali.guowangkeji.top/Article/details/gtrrnvicgs.html

(double) a / b
来源：http://dali.zycfv.cn/Article/details/gtqzskzclv.html

[S16] C：位操作置位
来源：http://dali.iojbl.cn/Article/details/gtuqlxanzt.html

x |= (1 << 3);
来源：http://dali.cqqwz.cn/Article/details/gtgkfeccyt.html

[S17] C：安全拼接字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtgpcotfyl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpbtoiclb.html

[S18] C：命令行参数
来源：http://dali.9152youxi.cn/Article/details/gtphepicrf.html

int main(int argc, char **argv)
来源：http://dali.tian-w.cn/Article/details/gthnajlcsy.html

[S19] C：快速排序
来源：http://dali.yonumen.top/Article/details/gtiuwlbain.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hnqzz.top/Article/details/gtnvutxncr.html

[S20] C：二分查找
来源：http://dali.0kj1m.cn/Article/details/gtxkguawue.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jianghu66.top/Article/details/gtqjmyjjpq.html

[S21] C：字符类别判断
来源：http://dali.shangyingyoupin.top/Article/details/gtwlaqtdqy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ydzc1.top/Article/details/gtnkaeikan.html

[S22] C：字符串转数字
来源：http://dali.nanxinkj.top/Article/details/gtnbsyapbd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yuanzhike.top/Article/details/gtibvwzlbs.html

[S23] C：随机数
来源：http://dali.gaohongyu789.top/Article/details/gtssqhxeti.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xuanzx.com/Article/details/gtszftpryq.html

[S24] C：获取本地时间
来源：http://dali.daxiang520.top/Article/details/gtfhluwyyw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.quarkkingdee.top/Article/details/gthbuufrif.html

[S25] C：内存拷贝
来源：http://dali.xuetiantiany.cn/Article/details/gtyjxsrgzh.html

memcpy(dst, src, n);
来源：http://dali.chenlongwang.top/Article/details/gtdzumpltp.html

[S26] C：内存清零
来源：http://dali.daria6918.cn/Article/details/gtkjbujgsd.html

memset(a, 0, sizeof a);
来源：http://dali.yongpay.top/Article/details/gtiiznyljp.html

[S27] C：定义常量
来源：http://dali.gaohongyu789.top/Article/details/gtpgvpunpj.html

const double PI = 3.14159;
来源：http://dali.tanke756.top/Article/details/gtpbauumow.html

[S28] C：静态变量
来源：http://dali.yanxiufei.cn/Article/details/gtzxkydgou.html

static int counter = 0;
来源：http://dali.guannengcc.top/Article/details/gtgrrvxnwx.html

[S29] C：变参函数
来源：http://dali.yanxiufei.cn/Article/details/gtmfuiypat.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.iojbl.cn/Article/details/gtehdygmmr.html

[S30] C：头文件保护
来源：http://dali.tianlin.xyz/Article/details/gtiypmwooh.html

#ifndef X_H
来源：http://dali.nanxuanxn.top/Article/details/gtxkibpefx.html

#define X_H
来源：http://dali.shanyushiyangtech.top/Article/details/gtoefymkkx.html

#endif
来源：http://dali.hfpthk.cn/Article/details/gtvqbodbbo.html

[S31] C++：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtkgjvhsdg.html

#include <iostream>
来源：http://dali.sufxvd.cn/Article/details/gtyttaxkyq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.tianlin.xyz/Article/details/gtkldpdwnx.html

[S32] C++：字符串
来源：http://dali.haohaochexian.top/Article/details/gtoatrvjww.html

std::string s = "hi";  s += "!";
来源：http://dali.cdnleiting.top/Article/details/gtbwuflxjj.html

[S33] C++：vector 增删
来源：http://dali.zhixingplan.top/Article/details/gtqqbukgjr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hfpthk.cn/Article/details/gtqztstnzu.html

[S34] C++：遍历 vector
来源：http://dali.zhongyouzk.top/Article/details/gtmwkssccs.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.smart0.xyz/Article/details/gtxzbjdiof.html

[S35] C++：map
来源：http://dali.hongshengwenyu.top/Article/details/gtntxjnbiy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtjslyeraq.html

[S36] C++：unordered_map
来源：http://dali.iojbl.cn/Article/details/gtfrkpuwgk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258888.top/Article/details/gtvrbvxbmc.html

[S37] C++：set
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvxarbngu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yueranfly.top/Article/details/gtoqmcsxir.html

[S38] C++：排序
来源：http://dali.nanxinkj.top/Article/details/gtijhucjpx.html

std::sort(v.begin(), v.end());
来源：http://dali.xuetiantiany.cn/Article/details/gtqqbgoqio.html

[S39] C++：自定义比较器排序
来源：http://dali.xuetiantiany.cn/Article/details/gtkjzqgyhq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xinyue.icu/Article/details/gtmdfumbmd.html

[S40] C++：查找元素
来源：http://dali.cqqwz.cn/Article/details/gtdugnzopt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yuxming.cn/Article/details/gtmbsvuorx.html

[S41] C++：类与构造函数
来源：http://dali.cucudq.cn/Article/details/gtomdhzxjx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hongshengwenyu.top/Article/details/gtiyeycyjj.html

[S42] C++：继承与虚函数
来源：http://dali.feifeiyinyue.top/Article/details/gthudcxcmu.html

class B : public Base { public: void f() override {} };
来源：http://dali.gotoacloud.top/Article/details/gtmtnltvfg.html

[S43] C++：智能指针
来源：http://dali.jyoumei.cn/Article/details/gtuetclsbk.html

auto p = std::make_unique<int>(5);
来源：http://dali.aizwys.cn/Article/details/gtrkhxshmm.html

[S44] C++：引用传参
来源：http://dali.kuanghao11.cn/Article/details/gtcythxxdb.html

void inc(int &x) { ++x; }
来源：http://dali.0kj1m.cn/Article/details/gtqhytecci.html

[S45] C++：lambda
来源：http://dali.chenzaomai.com/Article/details/gtgmlfsncn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jqgufenzy.top/Article/details/gtkisvvukn.html

[S46] C++：函数模板
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqczewlyu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.dianchejie.cn/Article/details/gtoaschkpz.html

[S47] C++：结构化绑定遍历
来源：http://dali.yangfankeji.com/Article/details/gtyjpteugj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.vqdsnc.cn/Article/details/gtalquznld.html

[S48] C++：逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gtrhhhgyrt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xylfe.cn/Article/details/gtzexrsepm.html

while (std::getline(in, line)) { }
来源：http://dali.pycfn.com/Article/details/gthgdpceol.html

[S49] C++：写文件
来源：http://dali.hfpthk.cn/Article/details/gtqlzdjigg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.vqdsnc.cn/Article/details/gtlpwzmegk.html

[S50] C++：格式化数字
来源：http://dali.xuetiantiany.cn/Article/details/gtsxpningu.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.pycfn.com/Article/details/gtllgljwzd.html

[S51] C++：显式类型转换
来源：http://dali.daria6918.cn/Article/details/gttlqapwhh.html

static_cast<double>(a) / b
来源：http://dali.zdqjudy.top/Article/details/gtezbktgsu.html

[S52] C++：const 与 noexcept
来源：http://dali.dianchejie.cn/Article/details/gtioevijbo.html

int size() const noexcept { return n_; }
来源：http://dali.shangyingyoupin.top/Article/details/gtyqrnugeb.html

[S53] C++：移动语义
来源：http://dali.wangdashe.top/Article/details/gtwdtvesla.html

std::vector<int> w = std::move(v);
来源：http://dali.haohaochexian.top/Article/details/gtjbglkccf.html

[S54] C++：异常处理
来源：http://dali.zhoulong.xyz/Article/details/gttbglszbv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shangyingyoupin.top/Article/details/gtzwrtcxpo.html

[S55] C++：结构化绑定
来源：http://dali.tian-w.cn/Article/details/gtshlpmsvv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.fengsongda.top/Article/details/gtwidivfgf.html

[S56] C++：optional
来源：http://dali.c1oappe.top/Article/details/gttbuwhvzl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cdnleiting.top/Article/details/gtzxczrmzj.html

[S57] C++：编译期常量
来源：http://dali.hammf.cn/Article/details/gtmuxudlwp.html

constexpr int N = 10;
来源：http://dali.sufxvd.cn/Article/details/gtosvmuyrv.html

[S58] C++：命名空间
来源：http://dali.hammf.cn/Article/details/gtdljwvgwf.html

namespace ns { int f() { return 1; } }
来源：http://dali.ehwqpu.com/Article/details/gtshvrjdye.html

[S59] C++：静态断言
来源：http://dali.zhongyouzk.top/Article/details/gtfkfogbdw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.daxiang520.top/Article/details/gtfjcliovc.html

[S60] C++：遍历并删除元素
来源：http://dali.yonumen.top/Article/details/gtwjjhvldf.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.aibaodan.cn/Article/details/gtjwxbsbdx.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gtzieeeznk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.316326.xyz/Article/details/gtkeswmuji.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtelozxagj.html

[T01] Kotlin：Hello World
来源：http://dali.yonumen.top/Article/details/gtbhezurjy.html

println("Hello")
来源：http://dali.kuanghao11.cn/Article/details/gttylavmzk.html

[T02] Kotlin：变量
来源：http://dali.chenzaomai.com/Article/details/gtludctebh.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shanyushiyangtech.top/Article/details/gtpswgwpny.html

[T03] Kotlin：字符串模板
来源：http://dali.guannengcc.top/Article/details/gtslhllyyc.html

"值: $b"
来源：http://dali.jyoumei.cn/Article/details/gtyzfcatea.html

[T04] Kotlin：空安全
来源：http://dali.yj20258.top/Article/details/gtshtdtish.html

val n: String? = null;  n?.length
来源：http://dali.zhengqikj.top/Article/details/gtehnkgdix.html

[T05] Kotlin：when 表达式
来源：http://dali.vqdsnc.cn/Article/details/gtjyisepaj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hysaishi.cn/Article/details/gtewqwpkvh.html

[T06] Kotlin：集合映射
来源：http://dali.chenjidiqi.icu/Article/details/gtksvfhaja.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.nanxuanxn.top/Article/details/gtliwdecto.html

[T07] Kotlin：集合过滤
来源：http://dali.c1oappe.top/Article/details/gtwkaoajdd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xziqi.cn/Article/details/gtdxvfweoc.html

[T08] Kotlin：数据类
来源：http://dali.shuidangran.top/Article/details/gthelorowo.html

data class User(val name: String, val age: Int)
来源：http://dali.guannengcc.top/Article/details/gtcfjxggkj.html

[T09] Kotlin：扩展函数
来源：http://dali.zhengqikj.top/Article/details/gtnwcebrto.html

fun String.exclaim() = this + "!"
来源：http://dali.yonumen.top/Article/details/gtmzsvrmno.html

[T10] Kotlin：默认参数
来源：http://dali.wangdashe.top/Article/details/gtxofhnvgq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xinyue.icu/Article/details/gtoqsukrgf.html

[T11] Kotlin：协程
来源：http://dali.tianlin.xyz/Article/details/gtkiqyxxfh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.tian-w.cn/Article/details/gtmfnwtssg.html

[T12] Kotlin：解构声明
来源：http://dali.jianghu66.top/Article/details/gtzatejhsy.html

val (a, b) = Pair(1, 2)
来源：http://dali.c1oappe.top/Article/details/gtpgwxppxc.html

[T13] Kotlin：只读 Map
来源：http://dali.smart0.xyz/Article/details/gtnkuliglb.html

val m = mapOf("a" to 1)
来源：http://dali.dianchejie.cn/Article/details/gtaaaaxmrk.html

[T14] Kotlin：循环
来源：http://dali.shzxlz.cn/Article/details/gtfavqonrn.html

for (i in 1..10) println(i)
来源：http://dali.yueranfly.top/Article/details/gtliewrocg.html

[T15] Kotlin：接口
来源：http://dali.tianlin.xyz/Article/details/gtfsgdjwhb.html

interface Shape { fun area(): Double }
来源：http://dali.shzxlz.cn/Article/details/gthdzdgibi.html

[T16] Swift：Hello World
来源：http://dali.meibo888.top/Article/details/gtwszulbwf.html

print("Hello")
来源：http://dali.yuanzhike.top/Article/details/gtyhjkoqug.html

[T17] Swift：变量与常量
来源：http://dali.xziqi.cn/Article/details/gtpmxvwzty.html

var a = 1;  let b = 2
来源：http://dali.hywenlv.cn/Article/details/gtccloamrj.html

[T18] Swift：字符串插值
来源：http://dali.hnxiangtu.top/Article/details/gtnmzyhykf.html

"值: \(b)"
来源：http://dali.jqgufenzy.top/Article/details/gtplifzsak.html

[T19] Swift：可选绑定
来源：http://dali.zdqjudy.top/Article/details/gtuxxwtado.html

if let n = opt { print(n) }
来源：http://dali.chenlongwang.top/Article/details/gtfdakyhpe.html

[T20] Swift：数组操作
来源：http://dali.cucudq.cn/Article/details/gtkngqafzm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhoulong.xyz/Article/details/gtmaiiiclv.html

[T21] Swift：遍历
来源：http://dali.iojbl.cn/Article/details/gtfmpnrhjj.html

for x in a { print(x) }
来源：http://dali.jlsjyb.cn/Article/details/gtdskvhykq.html

[T22] Swift：字典
来源：http://dali.sweek.top/Article/details/gtjrdyebcc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.sufxvd.cn/Article/details/gtnuzfhnbl.html

[T23] Swift：函数
来源：http://dali.tianlin.xyz/Article/details/gtemabeqjx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.wangdashe.top/Article/details/gtiojmegcb.html

[T24] Swift：闭包
来源：http://dali.yvedp.cn/Article/details/gtizntckuf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yueranfly.top/Article/details/gtqidrheem.html

[T25] Swift：结构体
来源：http://dali.iojbl.cn/Article/details/gtpkqpqsia.html

struct P { var x: Int }
来源：http://dali.cheryme.top/Article/details/gtazlqxwrt.html

[T26] Swift：类与重写
来源：http://dali.chenzaomai.com/Article/details/gtimwkpyfc.html

class A: Base { override func f() {} }
来源：http://dali.daria6918.cn/Article/details/gtzxbkykaw.html

[T27] Swift：错误处理
来源：http://dali.zhoulong.xyz/Article/details/gtmidillbx.html

do { try f() } catch { print(error) }
来源：http://dali.xuanzx.com/Article/details/gtylovewae.html

[T28] Swift：枚举
来源：http://dali.ydzc1.top/Article/details/gtqzouimis.html

enum Color { case red, green }
来源：http://dali.ehwqpu.com/Article/details/gtcdbmotge.html

[T29] Swift：guard 提前返回
来源：http://dali.zhoulong.xyz/Article/details/gtvgfpnttx.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gtrxuwinpr.html

[T30] Swift：协议
来源：http://dali.wangshuangyany.cn/Article/details/gtcirpicut.html

protocol Shape { func area() -> Double }
来源：http://dali.sufxvd.cn/Article/details/gtpskpnhrx.html

[T31] Lua：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiwcitots.html

print("Hello")
来源：http://dali.quarkkingdee.top/Article/details/gtgwytfxcb.html

[T32] Lua：局部变量
来源：http://dali.ydzc1.top/Article/details/gteyhaktyc.html

local a = 1
来源：http://dali.snrcjt.cn/Article/details/gtkdhfawnh.html

[T33] Lua：表（数组）
来源：http://dali.cucudq.cn/Article/details/gtoxhimsmx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cashguo.top/Article/details/gteoocmjrb.html

[T34] Lua：遍历表
来源：http://dali.chenjidiqi.icu/Article/details/gtwgijdnvj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.aibaodan.cn/Article/details/gtolrosdvu.html

[T35] Lua：字典表
来源：http://dali.cashguo.top/Article/details/gtaplukiiv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.tian-w.cn/Article/details/gthopialrb.html

[T36] Lua：函数
来源：http://dali.bjfxy.top/Article/details/gtbjsqdsos.html

function add(a, b) return a + b end
来源：http://dali.smart0.xyz/Article/details/gtbufkbxbx.html

[T37] Lua：字符串拼接
来源：http://dali.yuanzhike.top/Article/details/gtmoqbbuxw.html

"a" .. "b"
来源：http://dali.zhongyouzk.top/Article/details/gtmrywgnfb.html

[T38] Lua：条件
来源：http://dali.andypj.xyz/Article/details/gtnzicxjaq.html

if x > 0 then print("正") end
来源：http://dali.redwolf501.top/Article/details/gtrdfmnthn.html

[T39] Lua：模式匹配
来源：http://dali.xuanzx.com/Article/details/gtwnowfajt.html

string.find(s, "%d+")
来源：http://dali.yangfankeji.com/Article/details/gthfswicxr.html

[T40] Lua：元表
来源：http://dali.daria6918.cn/Article/details/gtysskxhft.html

setmetatable({}, { __index = base })
来源：http://dali.zdqjudy.top/Article/details/gtbzanhpgo.html

[T41] Perl：Hello World
来源：http://dali.yj20258888.top/Article/details/gtnuccfddc.html

print "Hello\n";
来源：http://dali.redwolf501.top/Article/details/gtxgpynuhu.html

[T42] Perl：变量类型
来源：http://dali.daxiang520.top/Article/details/gtujlejovh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.bjfxy.top/Article/details/gtpzsuitsu.html

[T43] Perl：字符串插值
来源：http://dali.guowangkeji.top/Article/details/gtrzxmdioi.html

"值: $a"
来源：http://dali.mhx1999.top/Article/details/gtondpazey.html

[T44] Perl：条件
来源：http://dali.316326.xyz/Article/details/gtajgixvhd.html

if ($a > 0) { print "正"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gttaspfmsf.html

[T45] Perl：数组遍历
来源：http://dali.316326.xyz/Article/details/gtdocwxgth.html

for my $x (@arr) { print $x; }
来源：http://dali.jiagoushi.top/Article/details/gtoabnsqru.html

[T46] Perl：哈希操作
来源：http://dali.zhongyouzk.top/Article/details/gtdsokgpzo.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jinqigfzy.top/Article/details/gtfoqmhihk.html

[T47] Perl：正则捕获
来源：http://dali.shuidangran.top/Article/details/gtgnhhpqut.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.havefunace.top/Article/details/gtngmasehp.html

[T48] Perl：正则替换
来源：http://dali.nanxuanxn.top/Article/details/gttmqpjntn.html

$s =~ s/old/new/g;
来源：http://dali.ehwqpu.com/Article/details/gtosxxwpwg.html

[T49] Perl：函数
来源：http://dali.cheryme.top/Article/details/gtzwenjsmu.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jqgufenzy.top/Article/details/gtvxzmhknu.html

[T50] Perl：逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gtvfhmioen.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.kuanghao11.cn/Article/details/gtpqisfajm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yanxiufei.cn/Article/details/gtyjnlujnj.html

[T51] Scala：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtuefakqsr.html

println("Hello")
来源：http://dali.bjfxy.top/Article/details/gtvxuvpxtl.html

[T52] Scala：变量
来源：http://dali.zhiwuduotai.top/Article/details/gtvvvgvqiu.html

val a = 1;  var b = 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvzcoeloo.html

[T53] Scala：字符串插值
来源：http://dali.chenlongwang.top/Article/details/gtmqzwojmr.html

s"值: $b"
来源：http://dali.chenjidiqi.icu/Article/details/gtexexlfij.html

[T54] Scala：集合映射
来源：http://dali.bjfxy.top/Article/details/gtbcvizjjc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ppjwa.cn/Article/details/gtspgqkxrl.html

[T55] Scala：集合过滤
来源：http://dali.jqgufenzy.top/Article/details/gtafqcxfup.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.quarkkingdee.top/Article/details/gtcdtcbhnm.html

[T56] Scala：样例类
来源：http://dali.quarkkingdee.top/Article/details/gtolgbsxye.html

case class User(name: String, age: Int)
来源：http://dali.chenzaomai.com/Article/details/gtfsyaroxm.html

[T57] Scala：模式匹配
来源：http://dali.xylfe.cn/Article/details/gtrzpupqif.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hfpthk.cn/Article/details/gtneflbnwr.html

[T58] Scala：函数定义
来源：http://dali.smart0.xyz/Article/details/gtysjccugf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jyoumei.cn/Article/details/gtldkusrgi.html

[T59] Scala：循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwaeaclud.html

for (i <- 1 to 10) println(i)
来源：http://dali.sweek.top/Article/details/gtxmwqbwog.html

[T60] Scala：折叠
来源：http://dali.zhixingplan.top/Article/details/gtiuekrfbo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.andypj.xyz/Article/details/gtheisyzbd.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtajoigypg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yj20258888.top/Article/details/gtcnkrzeqw.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gttputtusb.html

[U01] Py：创建虚拟环境
来源：http://dali.birdmap.top/Article/details/gtqezytwta.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.feifeiyinyue.top/Article/details/gticvwllfd.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zdqjudy.top/Article/details/gtyrbirqhm.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.aizwys.cn/Article/details/gtjmkjgkfn.html


<!-- 参考信息 -->