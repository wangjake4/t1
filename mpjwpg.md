代发 wailian999

df -h;  du -sh *
来源：http://dali.shuidangran.top/Article/details/gt2migfickz.html

[R62] 找最占空间的文件
来源：http://dali.tianlin.xyz/Article/details/gt2hcqvdjxr.html

du -ah . | sort -rh | head -10
来源：http://dali.hysaishi.cn/Article/details/gt2bgjmwuim.html

[R63] 内存与进程
来源：http://dali.sysykeji.top/Article/details/gt2cxtjrwlm.html

free -h;  ps aux | grep nginx
来源：http://dali.mhx1999.top/Article/details/gt2jexjcecn.html

[R64] 结束进程
来源：http://dali.chenzaomai.com/Article/details/gt2gifueklx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yangfankeji.com/Article/details/gt2sfmswdha.html

[R65] 查看端口占用
来源：http://dali.smart0.xyz/Article/details/gt2pvocwmoi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.c1oappe.top/Article/details/gt2puiwgywd.html

[R66] 定时任务
来源：http://dali.jlsjyb.cn/Article/details/gt2uuwmbdpb.html

crontab -e;  crontab -l
来源：http://dali.yuxming.cn/Article/details/gt2snbfjbsx.html

[R67] 生成随机十六进制串
来源：http://dali.shuidangran.top/Article/details/gt2xliknfav.html

openssl rand -hex 16
来源：http://dali.svipenyu.cn/Article/details/gt2cxkjixrt.html

[R68] 计算文件校验值
来源：http://dali.9152youxi.cn/Article/details/gt2nwkakipf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.meibo888.top/Article/details/gt2itrwcrjt.html

[R69] 生成随机密码
来源：http://dali.fengsongda.top/Article/details/gt2typftvex.html

head -c 16 /dev/urandom | base64
来源：http://dali.xuanzx.com/Article/details/gt2mxgxpabx.html

[R70] 时间戳与互转
来源：http://dali.hywenlv.cn/Article/details/gt2kddjvaij.html

date +%s;  date -d @1700000000
来源：http://dali.wangdashe.top/Article/details/gt2nrdeatpx.html

[R71] 日期格式化
来源：http://dali.sufxvd.cn/Article/details/gt2onorscyl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenzaomai.com/Article/details/gt2mflnblmq.html

[R72] 等待端口就绪
来源：http://dali.xinyue.icu/Article/details/gt2koibigor.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.tanke756.top/Article/details/gt2mptbcwuv.html

[R73] 分割大日志
来源：http://dali.hywenlv.cn/Article/details/gt2wgchtgmw.html

split -l 1000 big.log part_
来源：http://dali.jianghu66.top/Article/details/gt2okvlmnce.html

[R74] 批量重命名
来源：http://dali.iojbl.cn/Article/details/gt2xtejxlwa.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xziqi.cn/Article/details/gt2aqguhksb.html

[R75] 导出环境变量
来源：http://dali.yvedp.cn/Article/details/gt2ccgcwymv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jyoumei.cn/Article/details/gt2efzxkexy.html

[R76] 使用临时文件
来源：http://dali.haohaochexian.top/Article/details/gt2qbppgvpr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.9152youxi.cn/Article/details/gt2kwrrqzuj.html

[R77] 读取用户输入
来源：http://dali.tian-w.cn/Article/details/gt2krsaxaxs.html

read -rp "请输入: " ans
来源：http://dali.jlsjyb.cn/Article/details/gt2zjjaxxvv.html

[R78] 交互式菜单
来源：http://dali.ehwqpu.com/Article/details/gt2aicmexci.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hnxiangtu.top/Article/details/gt2uvchvpkv.html

[R79] 解析命令行选项
来源：http://dali.jinghuilouyu.cn/Article/details/gt2cawebnuh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhixingplan.top/Article/details/gt2kmfuyevo.html

[R80] 查看脚本执行耗时
来源：http://dali.fzhhl.top/Article/details/gt2dyzaefig.html

time ./run.sh
来源：http://dali.zdqjudy.top/Article/details/gt2wcsyhbnq.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2widuvjeh.html

S. C / C++ 专题
来源：http://dali.zhoulong.xyz/Article/details/gt2mnmxnkze.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gt2dxkfugso.html

[S01] C：Hello World
来源：http://dali.yonumen.top/Article/details/gt2ldsqumfc.html

#include <stdio.h>
来源：http://dali.shangyingyoupin.top/Article/details/gt2plptcznd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.snrcjt.cn/Article/details/gt2fkqeiide.html

[S02] C：变量与格式化输出
来源：http://dali.daxiang520.top/Article/details/gt2alfmpbyt.html

int a = 10; printf("%d\n", a);
来源：http://dali.ppjwa.cn/Article/details/gt2xfusdedr.html

[S03] C：读入整数
来源：http://dali.jianghu66.top/Article/details/gt2xemhjxkb.html

int x; scanf("%d", &x);
来源：http://dali.gzhubu.top/Article/details/gt2hevvrwin.html

[S04] C：字符串复制
来源：http://dali.nwbrower.top/Article/details/gt2uebkbmtd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sisydmmi.html

[S05] C：字符串长度
来源：http://dali.hnqzz.top/Article/details/gt2araiepma.html

strlen(s)
来源：http://dali.cucudq.cn/Article/details/gt2seexgyoe.html

[S06] C：字符串比较
来源：http://dali.hammf.cn/Article/details/gt2ihofoigp.html

strcmp(a, b) == 0
来源：http://dali.jyoumei.cn/Article/details/gt2aqffrtzk.html

[S07] C：数组遍历求和
来源：http://dali.aizwys.cn/Article/details/gt2kqevrbex.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinqigufen.top/Article/details/gt2qqunxmhz.html

[S08] C：动态内存分配与释放
来源：http://dali.chenzaomai.com/Article/details/gt2igstvzzy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sweek.top/Article/details/gt2ksjysapt.html

[S09] C：结构体定义与初始化
来源：http://dali.feifeiyinyue.top/Article/details/gt2rcfcasmx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xuetiantiany.cn/Article/details/gt2kadtchwg.html

[S10] C：指针与解引用
来源：http://dali.yj202588.top/Article/details/gt2qgnkuhbr.html

int *p = &a;  *p = 5;
来源：http://dali.cqqwz.cn/Article/details/gt2xeeiyumj.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ebqlakpv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gzhubu.top/Article/details/gt2ogxfevuq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.chenzaomai.com/Article/details/gt2jseavivp.html

fclose(f);
来源：http://dali.andypj.xyz/Article/details/gt2mosklsrl.html

[S12] C：写文件
来源：http://dali.aizwys.cn/Article/details/gt2xptnijfj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cucudq.cn/Article/details/gt2hedyhuke.html

[S13] C：宏定义
来源：http://dali.shangyingyoupin.top/Article/details/gt2skvaegih.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.chenlongwang.top/Article/details/gt2ypxqnyfr.html

[S14] C：枚举
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2oxuulycw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhongyouzk.top/Article/details/gt2vfluxmga.html

[S15] C：类型转换
来源：http://dali.bjfxy.top/Article/details/gt2mxcciitc.html

(double) a / b
来源：http://dali.kuanghao11.cn/Article/details/gt2esuauztc.html

[S16] C：位操作置位
来源：http://dali.ehwqpu.com/Article/details/gt2bymyzcka.html

x |= (1 << 3);
来源：http://dali.hnxiangtu.top/Article/details/gt2jwbtrbme.html

[S17] C：安全拼接字符串
来源：http://dali.mhx1999.top/Article/details/gt2ruopxkto.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cucudq.cn/Article/details/gt2xknffpxe.html

[S18] C：命令行参数
来源：http://dali.sxryk.cn/Article/details/gt2akwyjzcq.html

int main(int argc, char **argv)
来源：http://dali.zycfv.cn/Article/details/gt2hjahqbwi.html

[S19] C：快速排序
来源：http://dali.aibaodan.cn/Article/details/gt2tbwofqjc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hongshengwenyu.top/Article/details/gt2fjilvohf.html

[S20] C：二分查找
来源：http://dali.yonumen.top/Article/details/gt2mttrwwsk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gogol.net.cn/Article/details/gt2ogenxyzr.html

[S21] C：字符类别判断
来源：http://dali.tian-w.cn/Article/details/gt2qprjhava.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shangyingyoupin.top/Article/details/gt2quhctzfl.html

[S22] C：字符串转数字
来源：http://dali.xylfe.cn/Article/details/gt2icdnrlhh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jqgufenzy.top/Article/details/gt2wignmyce.html

[S23] C：随机数
来源：http://dali.pengpengdd.cyou/Article/details/gt2nhzzkhqo.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xziqi.cn/Article/details/gt2avhktcyh.html

[S24] C：获取本地时间
来源：http://dali.cucudq.cn/Article/details/gt2cwkawrpn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gogol.net.cn/Article/details/gt2kwsbsquk.html

[S25] C：内存拷贝
来源：http://dali.yonumen.top/Article/details/gt2hfvelptt.html

memcpy(dst, src, n);
来源：http://dali.yangfankeji.com/Article/details/gt2ilylvnkf.html

[S26] C：内存清零
来源：http://dali.mhx1999.top/Article/details/gt2pdvyzltz.html

memset(a, 0, sizeof a);
来源：http://dali.guannengcc.top/Article/details/gt2rdahlvmb.html

[S27] C：定义常量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hrtcbmnp.html

const double PI = 3.14159;
来源：http://dali.yvedp.cn/Article/details/gt2ozuehkgd.html

[S28] C：静态变量
来源：http://dali.xuanzx.com/Article/details/gt2wsbrqkrg.html

static int counter = 0;
来源：http://dali.redwolf501.top/Article/details/gt2dsqtadks.html

[S29] C：变参函数
来源：http://dali.hysaishi.cn/Article/details/gt2qfprtirb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.aizwys.cn/Article/details/gt2imgwndbc.html

[S30] C：头文件保护
来源：http://dali.xuetiantiany.cn/Article/details/gt2dzdtcfhs.html

#ifndef X_H
来源：http://dali.yangfankeji.com/Article/details/gt2hkwpmino.html

#define X_H
来源：http://dali.fzhhl.top/Article/details/gt2dlykaejp.html

#endif
来源：http://dali.gogol.net.cn/Article/details/gt2kmvnzxvv.html

[S31] C++：Hello World
来源：http://dali.hfpthk.cn/Article/details/gt2flmthujb.html

#include <iostream>
来源：http://dali.meibo888.top/Article/details/gt2pvorimtw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yj202588.top/Article/details/gt2tpxzxrps.html

[S32] C++：字符串
来源：http://dali.yj20258888.top/Article/details/gt2amtakgcl.html

std::string s = "hi";  s += "!";
来源：http://dali.redwolf501.top/Article/details/gt2lcmlyouk.html

[S33] C++：vector 增删
来源：http://dali.hnqzz.top/Article/details/gt2vmbwbkcn.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yvedp.cn/Article/details/gt2ynsjqayi.html

[S34] C++：遍历 vector
来源：http://dali.xylfe.cn/Article/details/gt2xgpfcmrk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.daxiang520.top/Article/details/gt2iuixahju.html

[S35] C++：map
来源：http://dali.tian-w.cn/Article/details/gt2cczcuomc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gt2dhvaycbm.html

[S36] C++：unordered_map
来源：http://dali.andypj.xyz/Article/details/gt2gszzsfhl.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258.top/Article/details/gt2dfozxraw.html

[S37] C++：set
来源：http://dali.sysykeji.top/Article/details/gt2nqartkyh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.chenjidiqi.icu/Article/details/gt2wsnzadit.html

[S38] C++：排序
来源：http://dali.hongshengwenyu.top/Article/details/gt2viqlkoqp.html

std::sort(v.begin(), v.end());
来源：http://dali.snrcjt.cn/Article/details/gt2afblldpy.html

[S39] C++：自定义比较器排序
来源：http://dali.jiagoushi.top/Article/details/gt2bpdkejqy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.pycfn.com/Article/details/gt2nafiwffn.html

[S40] C++：查找元素
来源：http://dali.yueranfly.top/Article/details/gt2ivtwddgl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinqigfzy.top/Article/details/gt2bnnsrwmk.html

[S41] C++：类与构造函数
来源：http://dali.svipenyu.cn/Article/details/gt2ywochtid.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.iojbl.cn/Article/details/gt2jnzorsxv.html

[S42] C++：继承与虚函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bvpkhgwm.html

class B : public Base { public: void f() override {} };
来源：http://dali.smart0.xyz/Article/details/gt2vhqtjhgd.html

[S43] C++：智能指针
来源：http://dali.wangshuangyany.cn/Article/details/gt2ntjkasnd.html

auto p = std::make_unique<int>(5);
来源：http://dali.c1oappe.top/Article/details/gt2rnwrmfwf.html

[S44] C++：引用传参
来源：http://dali.haohaochexian.top/Article/details/gt2irgbatpk.html

void inc(int &x) { ++x; }
来源：http://dali.jiagoushi.top/Article/details/gt2utyduers.html

[S45] C++：lambda
来源：http://dali.aibaodan.cn/Article/details/gt2blokijvc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.daria6918.cn/Article/details/gt2nyhdbdsj.html

[S46] C++：函数模板
来源：http://dali.jiagoushi.top/Article/details/gt2nzlrumlm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cashguo.top/Article/details/gt2qrstllfu.html

[S47] C++：结构化绑定遍历
来源：http://dali.fengsongda.top/Article/details/gt2znslxsjw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.iojbl.cn/Article/details/gt2lzfhplbm.html

[S48] C++：逐行读文件
来源：http://dali.xziqi.cn/Article/details/gt2quvhcqwr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hywenlv.cn/Article/details/gt2tbcypiud.html

while (std::getline(in, line)) { }
来源：http://dali.jinqigufen.top/Article/details/gt2igweowxt.html

[S49] C++：写文件
来源：http://dali.chenlongwang.top/Article/details/gt2ysqyajwk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shzxlz.cn/Article/details/gt2xicbhqxv.html

[S50] C++：格式化数字
来源：http://dali.jinqigfzy.top/Article/details/gt2aigssasz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cqqwz.cn/Article/details/gt2stcjfijr.html

[S51] C++：显式类型转换
来源：http://dali.yj20258888.top/Article/details/gt2luozfaxx.html

static_cast<double>(a) / b
来源：http://dali.0kj1m.cn/Article/details/gt2gdxkhkdn.html

[S52] C++：const 与 noexcept
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2suiraxib.html

int size() const noexcept { return n_; }
来源：http://dali.tanke756.top/Article/details/gt2axsvbrfj.html

[S53] C++：移动语义
来源：http://dali.yonumen.top/Article/details/gt2epyrotyd.html

std::vector<int> w = std::move(v);
来源：http://dali.guowangkeji.top/Article/details/gt2tufkzeby.html

[S54] C++：异常处理
来源：http://dali.zdqjudy.top/Article/details/gt2xpavdznf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.mhx1999.top/Article/details/gt2lualtjyb.html

[S55] C++：结构化绑定
来源：http://dali.aibaodan.cn/Article/details/gt2tvylaveb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shzxlz.cn/Article/details/gt2gfvkhgkq.html

[S56] C++：optional
来源：http://dali.yj20258.top/Article/details/gt2flcwrher.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jinqigfzy.top/Article/details/gt2nutqmtkt.html

[S57] C++：编译期常量
来源：http://dali.zhengqikj.top/Article/details/gt2rxeeizsz.html

constexpr int N = 10;
来源：http://dali.jianghu66.top/Article/details/gt2kjsjiikt.html

[S58] C++：命名空间
来源：http://dali.jinqigfzy.top/Article/details/gt2wquccqwu.html

namespace ns { int f() { return 1; } }
来源：http://dali.havefunace.top/Article/details/gt2recnxlcn.html

[S59] C++：静态断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2owgqyylb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhiwuduotai.top/Article/details/gt2paqgffnm.html

[S60] C++：遍历并删除元素
来源：http://dali.tianlin.xyz/Article/details/gt2ttfxwnxp.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.fzhhl.top/Article/details/gt2qwnacfzw.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gt2zlzffrsb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xuanzx.com/Article/details/gt2qyzjnhsq.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2ezkikxel.html

[T01] Kotlin：Hello World
来源：http://dali.meibo888.top/Article/details/gt2kinvbwzd.html

println("Hello")
来源：http://dali.snrcjt.cn/Article/details/gt2ltzgmmdb.html

[T02] Kotlin：变量
来源：http://dali.chenzaomai.com/Article/details/gt2xnstvqja.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.wangshuangyany.cn/Article/details/gt2bgzjrvhb.html

[T03] Kotlin：字符串模板
来源：http://dali.wangshuangyany.cn/Article/details/gt2lbrjxshd.html

"值: $b"
来源：http://dali.daxiang520.top/Article/details/gt2slicaddi.html

[T04] Kotlin：空安全
来源：http://dali.sufxvd.cn/Article/details/gt2fytuybye.html

val n: String? = null;  n?.length
来源：http://dali.pengpengdd.cyou/Article/details/gt2naspiaba.html

[T05] Kotlin：when 表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kdlojwbn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.fzhhl.top/Article/details/gt2pfsnbaoe.html

[T06] Kotlin：集合映射
来源：http://dali.nanxinkj.top/Article/details/gt2pebasfuo.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vibaqkoa.html

[T07] Kotlin：集合过滤
来源：http://dali.daxiang520.top/Article/details/gt2btkjepff.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dusvisam.html

[T08] Kotlin：数据类
来源：http://dali.daxiang520.top/Article/details/gt2lswcwbot.html

data class User(val name: String, val age: Int)
来源：http://dali.guannengcc.top/Article/details/gt2dvwkhwqf.html

[T09] Kotlin：扩展函数
来源：http://dali.9152youxi.cn/Article/details/gt2rvhgjcxc.html

fun String.exclaim() = this + "!"
来源：http://dali.ehwqpu.com/Article/details/gt2nffgauyx.html

[T10] Kotlin：默认参数
来源：http://dali.c1oappe.top/Article/details/gt2bcghellu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.iojbl.cn/Article/details/gt2timrfxdc.html

[T11] Kotlin：协程
来源：http://dali.shangyingyoupin.top/Article/details/gt2rhcrabcc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xuetiantiany.cn/Article/details/gt2dmtanrat.html

[T12] Kotlin：解构声明
来源：http://dali.zhiwuduotai.top/Article/details/gt2rpnpngyb.html

val (a, b) = Pair(1, 2)
来源：http://dali.hysaishi.cn/Article/details/gt2qhibpcgn.html

[T13] Kotlin：只读 Map
来源：http://dali.jinqigfzy.top/Article/details/gt2cbrmsvmk.html

val m = mapOf("a" to 1)
来源：http://dali.shzxlz.cn/Article/details/gt2zrgitkww.html

[T14] Kotlin：循环
来源：http://dali.kuanghao11.cn/Article/details/gt2cxtftqff.html

for (i in 1..10) println(i)
来源：http://dali.shzxlz.cn/Article/details/gt2cfwpokie.html

[T15] Kotlin：接口
来源：http://dali.jianghu66.top/Article/details/gt2dzzcfocy.html

interface Shape { fun area(): Double }
来源：http://dali.jqgfzy.top/Article/details/gt2xzgmobiv.html

[T16] Swift：Hello World
来源：http://dali.sweek.top/Article/details/gt2iczvfmbq.html

print("Hello")
来源：http://dali.zhixingplan.top/Article/details/gt2jattgtmh.html

[T17] Swift：变量与常量
来源：http://dali.ydzc1.top/Article/details/gt2fqejfgcp.html

var a = 1;  let b = 2
来源：http://dali.sxryk.cn/Article/details/gt2pilcmcst.html

[T18] Swift：字符串插值
来源：http://dali.fengsongda.top/Article/details/gt2qshuqcju.html

"值: \(b)"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qxzxcpbd.html

[T19] Swift：可选绑定
来源：http://dali.dianchejie.cn/Article/details/gt2fuzirekk.html

if let n = opt { print(n) }
来源：http://dali.tanke756.top/Article/details/gt2pkyitdhl.html

[T20] Swift：数组操作
来源：http://dali.cheryme.top/Article/details/gt2rrzdibhs.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yuanzhike.top/Article/details/gt2pkwnlntk.html

[T21] Swift：遍历
来源：http://dali.cheryme.top/Article/details/gt2ulraxugq.html

for x in a { print(x) }
来源：http://dali.nanxinkj.top/Article/details/gt2npttwhtr.html

[T22] Swift：字典
来源：http://dali.xylfe.cn/Article/details/gt2pptslubh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cqqwz.cn/Article/details/gt2tqvzoeni.html

[T23] Swift：函数
来源：http://dali.zhiwuduotai.top/Article/details/gt2ucgghtov.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.9152youxi.cn/Article/details/gt2ljoqcuof.html

[T24] Swift：闭包
来源：http://dali.jianghu66.top/Article/details/gt2dnaxgjgp.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.daria6918.cn/Article/details/gt2ekkdoaio.html

[T25] Swift：结构体
来源：http://dali.yvedp.cn/Article/details/gt2vagmwwtn.html

struct P { var x: Int }
来源：http://dali.nanxinkj.top/Article/details/gt2bhjnbdlj.html

[T26] Swift：类与重写
来源：http://dali.yj20258888.top/Article/details/gt2ghrkwygm.html

class A: Base { override func f() {} }
来源：http://dali.nwbrower.top/Article/details/gt2cseralrn.html

[T27] Swift：错误处理
来源：http://dali.iojbl.cn/Article/details/gt2gfilahfz.html

do { try f() } catch { print(error) }
来源：http://dali.c1oappe.top/Article/details/gt2evndwozm.html

[T28] Swift：枚举
来源：http://dali.yangfankeji.com/Article/details/gt2ncujhqhh.html

enum Color { case red, green }
来源：http://dali.ehwqpu.com/Article/details/gt2phxjnkli.html

[T29] Swift：guard 提前返回
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sysstcum.html

guard let x = opt else { return }
来源：http://dali.yuanzhike.top/Article/details/gt2hxwutohv.html

[T30] Swift：协议
来源：http://dali.ybcxt.top/Article/details/gt2mxpgzkef.html

protocol Shape { func area() -> Double }
来源：http://dali.gogol.net.cn/Article/details/gt2egeqmygk.html

[T31] Lua：Hello World
来源：http://dali.andypj.xyz/Article/details/gt2zdqptotx.html

print("Hello")
来源：http://dali.ehwqpu.com/Article/details/gt2twcdykws.html

[T32] Lua：局部变量
来源：http://dali.ehwqpu.com/Article/details/gt2cyjugyjr.html

local a = 1
来源：http://dali.zhoulong.xyz/Article/details/gt2yvmyrslw.html

[T33] Lua：表（数组）
来源：http://dali.dashuyun.cn/Article/details/gt2lickibln.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.tian-w.cn/Article/details/gt2lzelnxnq.html

[T34] Lua：遍历表
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ujaotbhr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.0kj1m.cn/Article/details/gt2pbgjkxqi.html

[T35] Lua：字典表
来源：http://dali.tian-w.cn/Article/details/gt2rhcyxzwq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xinyue.icu/Article/details/gt2gmadjjfw.html

[T36] Lua：函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2enyikgrm.html

function add(a, b) return a + b end
来源：http://dali.zhengqikj.top/Article/details/gt2lwevnvqm.html

[T37] Lua：字符串拼接
来源：http://dali.316326.xyz/Article/details/gt2fouranwt.html

"a" .. "b"
来源：http://dali.cucudq.cn/Article/details/gt2gprujvvc.html

[T38] Lua：条件
来源：http://dali.redwolf501.top/Article/details/gt2rwwnuzak.html

if x > 0 then print("正") end
来源：http://dali.zhixingplan.top/Article/details/gt2bdqzvwzr.html

[T39] Lua：模式匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gt2figdntoz.html

string.find(s, "%d+")
来源：http://dali.xuetiantiany.cn/Article/details/gt2iehaxdtr.html

[T40] Lua：元表
来源：http://dali.gaohongyu789.top/Article/details/gt2htguvqqy.html

setmetatable({}, { __index = base })
来源：http://dali.sysykeji.top/Article/details/gt2upnwoqsc.html

[T41] Perl：Hello World
来源：http://dali.smart0.xyz/Article/details/gt2qpprfpty.html

print "Hello\n";
来源：http://dali.hammf.cn/Article/details/gt2mmlgtwpo.html

[T42] Perl：变量类型
来源：http://dali.daria6918.cn/Article/details/gt2vcictkzs.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.chenzaomai.com/Article/details/gt2oxeypmhv.html

[T43] Perl：字符串插值
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2shwvrdza.html

"值: $a"
来源：http://dali.gaohongyu789.top/Article/details/gt2zsoxqtro.html

[T44] Perl：条件
来源：http://dali.tianlin.xyz/Article/details/gt2uxrrnpfp.html

if ($a > 0) { print "正"; }
来源：http://dali.sysykeji.top/Article/details/gt2utvrauqi.html

[T45] Perl：数组遍历
来源：http://dali.xylfe.cn/Article/details/gt2axaxsjsf.html

for my $x (@arr) { print $x; }
来源：http://dali.tianlin.xyz/Article/details/gt2broftjuc.html

[T46] Perl：哈希操作
来源：http://dali.guannengcc.top/Article/details/gt2zvgrrcbj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.dianchejie.cn/Article/details/gt2bhhdynsz.html

[T47] Perl：正则捕获
来源：http://dali.nwbrower.top/Article/details/gt2bfhnlcup.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.gzhubu.top/Article/details/gt2nkwjruof.html

[T48] Perl：正则替换
来源：http://dali.jlsjyb.cn/Article/details/gt2qwolgmhd.html

$s =~ s/old/new/g;
来源：http://dali.gotoacloud.top/Article/details/gt2lnspqxzo.html

[T49] Perl：函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2olawzimk.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.9152youxi.cn/Article/details/gt2jjysxnrm.html

[T50] Perl：逐行读文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2itssfbyw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhixingplan.top/Article/details/gt2sjfpwizr.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.wangdashe.top/Article/details/gt2jutpxcnm.html

[T51] Scala：Hello World
来源：http://dali.jiagoushi.top/Article/details/gt2kgkndroy.html

println("Hello")
来源：http://dali.jinqigfzy.top/Article/details/gt2jvorlgeg.html

[T52] Scala：变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2qpjbdjmy.html

val a = 1;  var b = 2
来源：http://dali.birdmap.top/Article/details/gt2ahrbzwlo.html

[T53] Scala：字符串插值
来源：http://dali.aibaodan.cn/Article/details/gt2arghjrhk.html

s"值: $b"
来源：http://dali.xinyue.icu/Article/details/gt2rifyynxg.html

[T54] Scala：集合映射
来源：http://dali.316326.xyz/Article/details/gt2xbajulss.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhiwuduotai.top/Article/details/gt2ryioupaa.html

[T55] Scala：集合过滤
来源：http://dali.haohaochexian.top/Article/details/gt2wkqpbmjp.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.birdmap.top/Article/details/gt2ibpddfyg.html

[T56] Scala：样例类
来源：http://dali.hfpthk.cn/Article/details/gt2iifmkkpl.html

case class User(name: String, age: Int)
来源：http://dali.pycfn.com/Article/details/gt2yrjycqma.html

[T57] Scala：模式匹配
来源：http://dali.yongpay.top/Article/details/gt2eaohukde.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.andypj.xyz/Article/details/gt2rdnfnqoo.html

[T58] Scala：函数定义
来源：http://dali.shangyingyoupin.top/Article/details/gt2zjlgjaah.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.svipenyu.cn/Article/details/gt2ihyrbfly.html

[T59] Scala：循环
来源：http://dali.guowangkeji.top/Article/details/gt2xxjtsyqv.html

for (i <- 1 to 10) println(i)
来源：http://dali.sysykeji.top/Article/details/gt2bjokxtjc.html

[T60] Scala：折叠
来源：http://dali.sxryk.cn/Article/details/gt2dtfbjusl.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jyoumei.cn/Article/details/gt2bafvoydm.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2quiulcyg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jqgufenzy.top/Article/details/gt2oeuhtakq.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gt2xghwriyb.html

[U01] Py：创建虚拟环境
来源：http://dali.zhengqikj.top/Article/details/gt2qsnuvkdq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zhengqikj.top/Article/details/gt2eotxxccz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hammf.cn/Article/details/gt2gqhilfas.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ydzc1.top/Article/details/gt2ltdiffqc.html


<!-- 参考信息 -->