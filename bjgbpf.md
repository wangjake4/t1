代发 wailian999

df -h;  du -sh *
来源：http://dali.redwolf501.top/Article/details/gtsanuqrbf.html

[R62] 找最占空间的文件
来源：http://dali.andypj.xyz/Article/details/gtgmwlypia.html

du -ah . | sort -rh | head -10
来源：http://dali.dianchejie.cn/Article/details/gtrdousebp.html

[R63] 内存与进程
来源：http://dali.gotoacloud.top/Article/details/gtnawcnvxy.html

free -h;  ps aux | grep nginx
来源：http://dali.iojbl.cn/Article/details/gtmlcyutxf.html

[R64] 结束进程
来源：http://dali.guannengcc.top/Article/details/gtsfzskmvk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.daria6918.cn/Article/details/gtzlwwdwfp.html

[R65] 查看端口占用
来源：http://dali.havefunace.top/Article/details/gtpbsdjmln.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jqgfzy.top/Article/details/gtewksctog.html

[R66] 定时任务
来源：http://dali.wangshuangyany.cn/Article/details/gtuocfosrg.html

crontab -e;  crontab -l
来源：http://dali.yonumen.top/Article/details/gtarzmxvgj.html

[R67] 生成随机十六进制串
来源：http://dali.jinqigfzy.top/Article/details/gturyyyjfm.html

openssl rand -hex 16
来源：http://dali.aizwys.cn/Article/details/gtkbrrxmok.html

[R68] 计算文件校验值
来源：http://dali.daxiang520.top/Article/details/gtmrerlshu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sysykeji.top/Article/details/gtjfwmcwvb.html

[R69] 生成随机密码
来源：http://dali.pengpengdd.cyou/Article/details/gtxylrloud.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhongyouzk.top/Article/details/gthhlqeneo.html

[R70] 时间戳与互转
来源：http://dali.ydzc1.top/Article/details/gtqttvxncm.html

date +%s;  date -d @1700000000
来源：http://dali.sufxvd.cn/Article/details/gtgfosukkt.html

[R71] 日期格式化
来源：http://dali.gogol.net.cn/Article/details/gtqhbgyyqc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yonumen.top/Article/details/gtkbycpfjg.html

[R72] 等待端口就绪
来源：http://dali.sysykeji.top/Article/details/gtfenfzesc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.svipenyu.cn/Article/details/gtvsyiaxgh.html

[R73] 分割大日志
来源：http://dali.daria6918.cn/Article/details/gtpitgsbuc.html

split -l 1000 big.log part_
来源：http://dali.xuetiantiany.cn/Article/details/gtrjnkurcx.html

[R74] 批量重命名
来源：http://dali.yangfankeji.com/Article/details/gtubuuhfoc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtklwmmqng.html

[R75] 导出环境变量
来源：http://dali.fengsongda.top/Article/details/gtowvyhbbi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yonumen.top/Article/details/gtpahvrumw.html

[R76] 使用临时文件
来源：http://dali.ydzc1.top/Article/details/gtkfpbllzs.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jiagoushi.top/Article/details/gtkdrkjisz.html

[R77] 读取用户输入
来源：http://dali.havefunace.top/Article/details/gtnbwfhmgy.html

read -rp "请输入: " ans
来源：http://dali.sysykeji.top/Article/details/gtjycgpzuz.html

[R78] 交互式菜单
来源：http://dali.zhengqikj.top/Article/details/gtqfksenox.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sysykeji.top/Article/details/gtlltoaeyl.html

[R79] 解析命令行选项
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgfrjprdl.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhoulong.xyz/Article/details/gtwlkwkwpt.html

[R80] 查看脚本执行耗时
来源：http://dali.andypj.xyz/Article/details/gtbiobkptd.html

time ./run.sh
来源：http://dali.hnxiangtu.top/Article/details/gtdmgndibh.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtmtzbyfqm.html

S. C / C++ 专题
来源：http://dali.aibaodan.cn/Article/details/gtapugcjqe.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtkcszquzb.html

[S01] C：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtqfbsjqil.html

#include <stdio.h>
来源：http://dali.yangfankeji.com/Article/details/gtureyiuao.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shangyingyoupin.top/Article/details/gtckedxiol.html

[S02] C：变量与格式化输出
来源：http://dali.0kj1m.cn/Article/details/gtbcgkftuk.html

int a = 10; printf("%d\n", a);
来源：http://dali.shuidangran.top/Article/details/gtoxozyisb.html

[S03] C：读入整数
来源：http://dali.gaohongyu789.top/Article/details/gtirpbrwqg.html

int x; scanf("%d", &x);
来源：http://dali.cashguo.top/Article/details/gtyvnyeyvt.html

[S04] C：字符串复制
来源：http://dali.nanxinkj.top/Article/details/gtasrlixgl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.redwolf501.top/Article/details/gteduokjgf.html

[S05] C：字符串长度
来源：http://dali.shzxlz.cn/Article/details/gtnhxmzmdg.html

strlen(s)
来源：http://dali.ybcxt.top/Article/details/gtdrteeyhi.html

[S06] C：字符串比较
来源：http://dali.jqgfzy.top/Article/details/gtyjskbxeh.html

strcmp(a, b) == 0
来源：http://dali.jinghuilouyu.cn/Article/details/gtezutkcbw.html

[S07] C：数组遍历求和
来源：http://dali.yj20258.top/Article/details/gtigxmiugm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.316326.xyz/Article/details/gtfrhveiaj.html

[S08] C：动态内存分配与释放
来源：http://dali.zhengqikj.top/Article/details/gtxidlkeft.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.pycfn.com/Article/details/gturliaond.html

[S09] C：结构体定义与初始化
来源：http://dali.feifeiyinyue.top/Article/details/gtcwtzjuab.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.316326.xyz/Article/details/gthyargovs.html

[S10] C：指针与解引用
来源：http://dali.dianchejie.cn/Article/details/gtqfphukjm.html

int *p = &a;  *p = 5;
来源：http://dali.cheryme.top/Article/details/gtqrthvihq.html

[S11] C：逐行读文件
来源：http://dali.snrcjt.cn/Article/details/gtdoqvrlwc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xuanzx.com/Article/details/gtjwbxjkxo.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hysaishi.cn/Article/details/gtikucmftw.html

fclose(f);
来源：http://dali.vqdsnc.cn/Article/details/gtetumlwby.html

[S12] C：写文件
来源：http://dali.xylfe.cn/Article/details/gtzhmmsgrw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.aibaodan.cn/Article/details/gtwlgtchov.html

[S13] C：宏定义
来源：http://dali.hongshengwenyu.top/Article/details/gteotigdfq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jiagoushi.top/Article/details/gtcfdlwrth.html

[S14] C：枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcfuixrot.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.chenzaomai.com/Article/details/gtvheodvxs.html

[S15] C：类型转换
来源：http://dali.hfpthk.cn/Article/details/gtyigpnywz.html

(double) a / b
来源：http://dali.shzxlz.cn/Article/details/gtasgiqaaj.html

[S16] C：位操作置位
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzcbhzqha.html

x |= (1 << 3);
来源：http://dali.daria6918.cn/Article/details/gtezhcgptc.html

[S17] C：安全拼接字符串
来源：http://dali.shanyushiyangtech.top/Article/details/gtujtsxrea.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.nanxinkj.top/Article/details/gtfwrvrbyz.html

[S18] C：命令行参数
来源：http://dali.aizwys.cn/Article/details/gtjaasfolx.html

int main(int argc, char **argv)
来源：http://dali.zhiwuduotai.top/Article/details/gtvpmurmho.html

[S19] C：快速排序
来源：http://dali.0kj1m.cn/Article/details/gtnartulbb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinghuilouyu.cn/Article/details/gtiekruiwl.html

[S20] C：二分查找
来源：http://dali.fengsongda.top/Article/details/gtlmaxibqj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tian-w.cn/Article/details/gtouwzhdms.html

[S21] C：字符类别判断
来源：http://dali.jqgfzy.top/Article/details/gtczqoswgt.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhongyouzk.top/Article/details/gtcwsyrbpt.html

[S22] C：字符串转数字
来源：http://dali.snrcjt.cn/Article/details/gtwmfrfkxw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenlongwang.top/Article/details/gtbietwsbw.html

[S23] C：随机数
来源：http://dali.yj202588.top/Article/details/gttavvojmu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hnxiangtu.top/Article/details/gtuwjsuhva.html

[S24] C：获取本地时间
来源：http://dali.jlsjyb.cn/Article/details/gtjbtideno.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cdnleiting.top/Article/details/gtjclhkpnu.html

[S25] C：内存拷贝
来源：http://dali.hfpthk.cn/Article/details/gtganqgdla.html

memcpy(dst, src, n);
来源：http://dali.bjfxy.top/Article/details/gtvoknuqci.html

[S26] C：内存清零
来源：http://dali.hywenlv.cn/Article/details/gtgwtbahtz.html

memset(a, 0, sizeof a);
来源：http://dali.redwolf501.top/Article/details/gtuebsslja.html

[S27] C：定义常量
来源：http://dali.shanyushiyangtech.top/Article/details/gtgjufgdju.html

const double PI = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gtgvubfyjp.html

[S28] C：静态变量
来源：http://dali.guannengcc.top/Article/details/gtfuxfbxqo.html

static int counter = 0;
来源：http://dali.xziqi.cn/Article/details/gtbdqqapag.html

[S29] C：变参函数
来源：http://dali.jiagoushi.top/Article/details/gtdjmopdxu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jianghu66.top/Article/details/gtufsxbrkt.html

[S30] C：头文件保护
来源：http://dali.shuidangran.top/Article/details/gttktzorbb.html

#ifndef X_H
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqiuxbleh.html

#define X_H
来源：http://dali.pengpengdd.cyou/Article/details/gtgczbcntr.html

#endif
来源：http://dali.hammf.cn/Article/details/gtveohwdqx.html

[S31] C++：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtwokijoks.html

#include <iostream>
来源：http://dali.jinghuilouyu.cn/Article/details/gthunlfifb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ivvv.top/Article/details/gtfglhitvu.html

[S32] C++：字符串
来源：http://dali.sxryk.cn/Article/details/gtfflsylhy.html

std::string s = "hi";  s += "!";
来源：http://dali.birdmap.top/Article/details/gtobhdxkvh.html

[S33] C++：vector 增删
来源：http://dali.mhx1999.top/Article/details/gtdrysdksd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.meibo888.top/Article/details/gtsvabrmtk.html

[S34] C++：遍历 vector
来源：http://dali.feifeiyinyue.top/Article/details/gtdirgslfp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gtqrmvddya.html

[S35] C++：map
来源：http://dali.yuxming.cn/Article/details/gtjgskttby.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pycfn.com/Article/details/gttugwrsmn.html

[S36] C++：unordered_map
来源：http://dali.sufxvd.cn/Article/details/gtazpnzlvg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhongyouzk.top/Article/details/gtjeeqlabi.html

[S37] C++：set
来源：http://dali.zhixingplan.top/Article/details/gtfdmrvdse.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jlsjyb.cn/Article/details/gtrmmvtplx.html

[S38] C++：排序
来源：http://dali.chenzaomai.com/Article/details/gtxhramggz.html

std::sort(v.begin(), v.end());
来源：http://dali.hammf.cn/Article/details/gtaufylswj.html

[S39] C++：自定义比较器排序
来源：http://dali.yanxiufei.cn/Article/details/gtjzruzekm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhoulong.xyz/Article/details/gtkwvyljgm.html

[S40] C++：查找元素
来源：http://dali.chenzaomai.com/Article/details/gtdrddnwvi.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.havefunace.top/Article/details/gtfvgkwlqq.html

[S41] C++：类与构造函数
来源：http://dali.fzhhl.top/Article/details/gtsuamfwii.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hnqzz.top/Article/details/gthvtuxcmd.html

[S42] C++：继承与虚函数
来源：http://dali.ppjwa.cn/Article/details/gtaxewpowl.html

class B : public Base { public: void f() override {} };
来源：http://dali.meibo888.top/Article/details/gtnxkzmagl.html

[S43] C++：智能指针
来源：http://dali.guannengcc.top/Article/details/gtmqwoxtcl.html

auto p = std::make_unique<int>(5);
来源：http://dali.fzhhl.top/Article/details/gtogioykot.html

[S44] C++：引用传参
来源：http://dali.ppjwa.cn/Article/details/gtzphpxiag.html

void inc(int &x) { ++x; }
来源：http://dali.shangyingyoupin.top/Article/details/gtpwjczbmv.html

[S45] C++：lambda
来源：http://dali.cashguo.top/Article/details/gtevpzrfre.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.aizwys.cn/Article/details/gtzmycodkt.html

[S46] C++：函数模板
来源：http://dali.jianghu66.top/Article/details/gttdnblzrs.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.fengsongda.top/Article/details/gtsmlhrthh.html

[S47] C++：结构化绑定遍历
来源：http://dali.fzhhl.top/Article/details/gtzergtprf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.guannengcc.top/Article/details/gtdrzxrzqk.html

[S48] C++：逐行读文件
来源：http://dali.guowangkeji.top/Article/details/gtsiexbgcx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hysaishi.cn/Article/details/gtviofgthn.html

while (std::getline(in, line)) { }
来源：http://dali.vqdsnc.cn/Article/details/gtscibzybh.html

[S49] C++：写文件
来源：http://dali.daria6918.cn/Article/details/gtjmpmntvn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cheryme.top/Article/details/gtpykqjjmd.html

[S50] C++：格式化数字
来源：http://dali.meibo888.top/Article/details/gtdhdnysoy.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.pengpengdd.cyou/Article/details/gtwteyrvcs.html

[S51] C++：显式类型转换
来源：http://dali.9152youxi.cn/Article/details/gtcycjwzws.html

static_cast<double>(a) / b
来源：http://dali.jinghuilouyu.cn/Article/details/gtcyykcfzm.html

[S52] C++：const 与 noexcept
来源：http://dali.cdnleiting.top/Article/details/gtbnzxknav.html

int size() const noexcept { return n_; }
来源：http://dali.sxryk.cn/Article/details/gtaacngxxj.html

[S53] C++：移动语义
来源：http://dali.yanxiufei.cn/Article/details/gtdvdykfbi.html

std::vector<int> w = std::move(v);
来源：http://dali.andypj.xyz/Article/details/gtjrgkwopu.html

[S54] C++：异常处理
来源：http://dali.gotoacloud.top/Article/details/gthtocdrhx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.9152youxi.cn/Article/details/gtniwtjmms.html

[S55] C++：结构化绑定
来源：http://dali.hnqzz.top/Article/details/gttepryyjd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtoycarptr.html

[S56] C++：optional
来源：http://dali.jiagoushi.top/Article/details/gtssxwclqh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhixingplan.top/Article/details/gtufszhgvs.html

[S57] C++：编译期常量
来源：http://dali.9152youxi.cn/Article/details/gtcxfmlwnu.html

constexpr int N = 10;
来源：http://dali.iojbl.cn/Article/details/gtcefmuqzz.html

[S58] C++：命名空间
来源：http://dali.sufxvd.cn/Article/details/gtjjtlbnlu.html

namespace ns { int f() { return 1; } }
来源：http://dali.birdmap.top/Article/details/gtpyqmphbp.html

[S59] C++：静态断言
来源：http://dali.hywenlv.cn/Article/details/gtntvwtknp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.feifeiyinyue.top/Article/details/gtacyscojj.html

[S60] C++：遍历并删除元素
来源：http://dali.mhx1999.top/Article/details/gtzrginrwq.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.pycfn.com/Article/details/gttfoqljzr.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gthaxvokdq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yj20258.top/Article/details/gttyvadwxu.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtsyjpwlod.html

[T01] Kotlin：Hello World
来源：http://dali.yuxming.cn/Article/details/gttdkkntrz.html

println("Hello")
来源：http://dali.cucudq.cn/Article/details/gtuhdlrsdz.html

[T02] Kotlin：变量
来源：http://dali.zhoulong.xyz/Article/details/gtvqjslsae.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xuetiantiany.cn/Article/details/gtlbipqofj.html

[T03] Kotlin：字符串模板
来源：http://dali.kuanghao11.cn/Article/details/gtwoxukgvz.html

"值: $b"
来源：http://dali.cheryme.top/Article/details/gthazoiavn.html

[T04] Kotlin：空安全
来源：http://dali.jlsjyb.cn/Article/details/gtsozsvyuk.html

val n: String? = null;  n?.length
来源：http://dali.shuidangran.top/Article/details/gtewrfiyeg.html

[T05] Kotlin：when 表达式
来源：http://dali.nanxuanxn.top/Article/details/gtohokqqrf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.nanxuanxn.top/Article/details/gtkffkfgyn.html

[T06] Kotlin：集合映射
来源：http://dali.havefunace.top/Article/details/gtazedwjzh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.dashuyun.cn/Article/details/gtixqqwoar.html

[T07] Kotlin：集合过滤
来源：http://dali.yj20258.top/Article/details/gtnwltqrrt.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jianghu66.top/Article/details/gtcspzgslo.html

[T08] Kotlin：数据类
来源：http://dali.jianghu66.top/Article/details/gtzblubtiw.html

data class User(val name: String, val age: Int)
来源：http://dali.wangshuangyany.cn/Article/details/gtrbtnaydg.html

[T09] Kotlin：扩展函数
来源：http://dali.dashuyun.cn/Article/details/gtxdkjtttk.html

fun String.exclaim() = this + "!"
来源：http://dali.zhijiandao.cn/Article/details/gttobymtpr.html

[T10] Kotlin：默认参数
来源：http://dali.pycfn.com/Article/details/gtxlltsytf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xuetiantiany.cn/Article/details/gtqfluodqy.html

[T11] Kotlin：协程
来源：http://dali.bjfxy.top/Article/details/gtgddzdfcq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shuidangran.top/Article/details/gtbcbpplei.html

[T12] Kotlin：解构声明
来源：http://dali.zycfv.cn/Article/details/gteyixqquc.html

val (a, b) = Pair(1, 2)
来源：http://dali.yuxming.cn/Article/details/gtfaykgfas.html

[T13] Kotlin：只读 Map
来源：http://dali.c1oappe.top/Article/details/gtdvszirrd.html

val m = mapOf("a" to 1)
来源：http://dali.cucudq.cn/Article/details/gtwhqtzppp.html

[T14] Kotlin：循环
来源：http://dali.fzhhl.top/Article/details/gtvrlkpjqz.html

for (i in 1..10) println(i)
来源：http://dali.9152youxi.cn/Article/details/gtmxtlazfu.html

[T15] Kotlin：接口
来源：http://dali.pengpengdd.cyou/Article/details/gtlrbkdhwa.html

interface Shape { fun area(): Double }
来源：http://dali.xuetiantiany.cn/Article/details/gtkqtwaxvf.html

[T16] Swift：Hello World
来源：http://dali.sxryk.cn/Article/details/gtcbpyauwo.html

print("Hello")
来源：http://dali.tanke756.top/Article/details/gtglowphwk.html

[T17] Swift：变量与常量
来源：http://dali.yj202588.top/Article/details/gtlkzhnnut.html

var a = 1;  let b = 2
来源：http://dali.tianlin.xyz/Article/details/gtuskrglmo.html

[T18] Swift：字符串插值
来源：http://dali.ppjwa.cn/Article/details/gtfzudvqzy.html

"值: \(b)"
来源：http://dali.sweek.top/Article/details/gtynxrugbt.html

[T19] Swift：可选绑定
来源：http://dali.gogol.net.cn/Article/details/gtuiqdprfi.html

if let n = opt { print(n) }
来源：http://dali.tian-w.cn/Article/details/gttsoajyqt.html

[T20] Swift：数组操作
来源：http://dali.fengsongda.top/Article/details/gtztumsfgt.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj20258888.top/Article/details/gtdewclsua.html

[T21] Swift：遍历
来源：http://dali.andypj.xyz/Article/details/gtnlqofjwi.html

for x in a { print(x) }
来源：http://dali.shzxlz.cn/Article/details/gtpkhuccfy.html

[T22] Swift：字典
来源：http://dali.chenlongwang.top/Article/details/gtuqeqwqfi.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cdnleiting.top/Article/details/gtddbjpttf.html

[T23] Swift：函数
来源：http://dali.jinqigufen.top/Article/details/gtfwnsqemg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jinqigufen.top/Article/details/gtcaafyclf.html

[T24] Swift：闭包
来源：http://dali.sxryk.cn/Article/details/gtkmtgwyxt.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.316326.xyz/Article/details/gtnouegogv.html

[T25] Swift：结构体
来源：http://dali.chenzaomai.com/Article/details/gtkcqohjrx.html

struct P { var x: Int }
来源：http://dali.bjfxy.top/Article/details/gtynurtbry.html

[T26] Swift：类与重写
来源：http://dali.guannengcc.top/Article/details/gtyzyeycwi.html

class A: Base { override func f() {} }
来源：http://dali.shuidangran.top/Article/details/gtulewzhkv.html

[T27] Swift：错误处理
来源：http://dali.fengsongda.top/Article/details/gtahjjqkdu.html

do { try f() } catch { print(error) }
来源：http://dali.ehwqpu.com/Article/details/gtdovtrxse.html

[T28] Swift：枚举
来源：http://dali.zhoulong.xyz/Article/details/gtyuwrqqks.html

enum Color { case red, green }
来源：http://dali.svipenyu.cn/Article/details/gtgkhrbryk.html

[T29] Swift：guard 提前返回
来源：http://dali.zycfv.cn/Article/details/gtycpagkgp.html

guard let x = opt else { return }
来源：http://dali.shuidangran.top/Article/details/gteaqaxzrd.html

[T30] Swift：协议
来源：http://dali.pengpengdd.cyou/Article/details/gtfqvouhin.html

protocol Shape { func area() -> Double }
来源：http://dali.sxryk.cn/Article/details/gtzuwfvqdu.html

[T31] Lua：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtzoyfejyj.html

print("Hello")
来源：http://dali.ybcxt.top/Article/details/gtppoktvrg.html

[T32] Lua：局部变量
来源：http://dali.gaohongyu789.top/Article/details/gtudzpppsn.html

local a = 1
来源：http://dali.xuetiantiany.cn/Article/details/gtduomkpfq.html

[T33] Lua：表（数组）
来源：http://dali.ivvv.top/Article/details/gtugctllmz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.c1oappe.top/Article/details/gtnmtnkcrz.html

[T34] Lua：遍历表
来源：http://dali.jyoumei.cn/Article/details/gtlmqifvnr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.daria6918.cn/Article/details/gtfsemmsdu.html

[T35] Lua：字典表
来源：http://dali.yangfankeji.com/Article/details/gtzfzoefmw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.fengsongda.top/Article/details/gtfnjmjacq.html

[T36] Lua：函数
来源：http://dali.yvedp.cn/Article/details/gtiqwnjowc.html

function add(a, b) return a + b end
来源：http://dali.aibaodan.cn/Article/details/gtubltwbyk.html

[T37] Lua：字符串拼接
来源：http://dali.zhoulong.xyz/Article/details/gtidynqvym.html

"a" .. "b"
来源：http://dali.cqqwz.cn/Article/details/gtqqtypxhf.html

[T38] Lua：条件
来源：http://dali.zhengqikj.top/Article/details/gtrmwhdqvq.html

if x > 0 then print("正") end
来源：http://dali.xziqi.cn/Article/details/gtoyxfnizh.html

[T39] Lua：模式匹配
来源：http://dali.svipenyu.cn/Article/details/gtknxvboke.html

string.find(s, "%d+")
来源：http://dali.jqgufenzy.top/Article/details/gtaddwhkdt.html

[T40] Lua：元表
来源：http://dali.yueranfly.top/Article/details/gtmusqikum.html

setmetatable({}, { __index = base })
来源：http://dali.hongshengwenyu.top/Article/details/gtmcyzhaje.html

[T41] Perl：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtdmwfuhbe.html

print "Hello\n";
来源：http://dali.hammf.cn/Article/details/gtxvxatpzb.html

[T42] Perl：变量类型
来源：http://dali.sxryk.cn/Article/details/gtnlqxnwtz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sxryk.cn/Article/details/gtmdpfvios.html

[T43] Perl：字符串插值
来源：http://dali.cheryme.top/Article/details/gtnxhkycdu.html

"值: $a"
来源：http://dali.yangfankeji.com/Article/details/gtwambszud.html

[T44] Perl：条件
来源：http://dali.tian-w.cn/Article/details/gtrkppzjol.html

if ($a > 0) { print "正"; }
来源：http://dali.jqgufenzy.top/Article/details/gtijnxhihf.html

[T45] Perl：数组遍历
来源：http://dali.9152youxi.cn/Article/details/gtrzhjzopg.html

for my $x (@arr) { print $x; }
来源：http://dali.sxryk.cn/Article/details/gtqhunzhnr.html

[T46] Perl：哈希操作
来源：http://dali.jinqigufen.top/Article/details/gtoyewfjmr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hongshengwenyu.top/Article/details/gtruokpukp.html

[T47] Perl：正则捕获
来源：http://dali.sweek.top/Article/details/gtzafgsdqi.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yuxming.cn/Article/details/gtbososeyy.html

[T48] Perl：正则替换
来源：http://dali.9152youxi.cn/Article/details/gtvwxblxpp.html

$s =~ s/old/new/g;
来源：http://dali.jlsjyb.cn/Article/details/gtcdqtiims.html

[T49] Perl：函数
来源：http://dali.xylfe.cn/Article/details/gtlwvtgkat.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.smart0.xyz/Article/details/gtqqvzomkz.html

[T50] Perl：逐行读文件
来源：http://dali.cashguo.top/Article/details/gtnagstnzt.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.quarkkingdee.top/Article/details/gtmfzbokex.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.hywenlv.cn/Article/details/gtvsqgcfpt.html

[T51] Scala：Hello World
来源：http://dali.smart0.xyz/Article/details/gtldsgegri.html

println("Hello")
来源：http://dali.xuanzx.com/Article/details/gtnzfzhlbr.html

[T52] Scala：变量
来源：http://dali.jlsjyb.cn/Article/details/gtelxigcqq.html

val a = 1;  var b = 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbwdkwmbu.html

[T53] Scala：字符串插值
来源：http://dali.fengsongda.top/Article/details/gtypijqvtm.html

s"值: $b"
来源：http://dali.iojbl.cn/Article/details/gtpjknzrqu.html

[T54] Scala：集合映射
来源：http://dali.sufxvd.cn/Article/details/gtemegcety.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shuidangran.top/Article/details/gtzocdfkdt.html

[T55] Scala：集合过滤
来源：http://dali.zhixingplan.top/Article/details/gtbffjiogg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.aizwys.cn/Article/details/gtrlntecpk.html

[T56] Scala：样例类
来源：http://dali.andypj.xyz/Article/details/gtqskrzzuv.html

case class User(name: String, age: Int)
来源：http://dali.andypj.xyz/Article/details/gtyokfgdqy.html

[T57] Scala：模式匹配
来源：http://dali.iojbl.cn/Article/details/gtwdfasjju.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yueranfly.top/Article/details/gthntwkvvt.html

[T58] Scala：函数定义
来源：http://dali.jiagoushi.top/Article/details/gtsmbspfan.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.shanyushiyangtech.top/Article/details/gtqrlahbia.html

[T59] Scala：循环
来源：http://dali.shuidangran.top/Article/details/gttzkgrlzd.html

for (i <- 1 to 10) println(i)
来源：http://dali.tian-w.cn/Article/details/gtcskxddut.html

[T60] Scala：折叠
来源：http://dali.cashguo.top/Article/details/gtmgfodtcl.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jqgufenzy.top/Article/details/gtqpwgyeet.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtfhaxspzu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlqirochy.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtmjjmginx.html

[U01] Py：创建虚拟环境
来源：http://dali.c1oappe.top/Article/details/gtnkvierog.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.guannengcc.top/Article/details/gtcxjiytjq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jyoumei.cn/Article/details/gtuwiwdhzk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.quarkkingdee.top/Article/details/gtumfqvbag.html


<!-- 参考信息 -->