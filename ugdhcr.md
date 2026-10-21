代发 wailian999

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gtfsukhqkz.html

[R64] 结束进程
来源：http://dali.gzhubu.top/Article/details/gtuocxbfea.html

kill -9 $(pgrep -f app.py)
来源：http://dali.9152youxi.cn/Article/details/gttazedswu.html

[R65] 查看端口占用
来源：http://dali.kuanghao11.cn/Article/details/gtrwovhkdj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gogol.net.cn/Article/details/gthjjcdlvo.html

[R66] 定时任务
来源：http://dali.xziqi.cn/Article/details/gtgfllbsyf.html

crontab -e;  crontab -l
来源：http://dali.sxryk.cn/Article/details/gtdyrfarqk.html

[R67] 生成随机十六进制串
来源：http://dali.dashuyun.cn/Article/details/gtugqbdqep.html

openssl rand -hex 16
来源：http://dali.pycfn.com/Article/details/gtlahgrtfg.html

[R68] 计算文件校验值
来源：http://dali.ybcxt.top/Article/details/gtdnjxjmgd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtapfwejgx.html

[R69] 生成随机密码
来源：http://dali.xziqi.cn/Article/details/gtacytphgu.html

head -c 16 /dev/urandom | base64
来源：http://dali.jiagoushi.top/Article/details/gtueewjsfi.html

[R70] 时间戳与互转
来源：http://dali.haohaochexian.top/Article/details/gtcdpnalsm.html

date +%s;  date -d @1700000000
来源：http://dali.redwolf501.top/Article/details/gtzjqavdae.html

[R71] 日期格式化
来源：http://dali.0kj1m.cn/Article/details/gtyywizsbe.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinqigufen.top/Article/details/gtmrcgekab.html

[R72] 等待端口就绪
来源：http://dali.sysykeji.top/Article/details/gtjfkooqub.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.andypj.xyz/Article/details/gtnljdcjeh.html

[R73] 分割大日志
来源：http://dali.kuanghao11.cn/Article/details/gtzzusfcli.html

split -l 1000 big.log part_
来源：http://dali.xinyue.icu/Article/details/gtdggciqdv.html

[R74] 批量重命名
来源：http://dali.jinqigfzy.top/Article/details/gtfzpedgie.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gotoacloud.top/Article/details/gtbwbhmnwp.html

[R75] 导出环境变量
来源：http://dali.cdnleiting.top/Article/details/gtrfydgwuv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zdqjudy.top/Article/details/gtxotjbjqe.html

[R76] 使用临时文件
来源：http://dali.ppjwa.cn/Article/details/gtyfnxxtvy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shuidangran.top/Article/details/gtqshymgtk.html

[R77] 读取用户输入
来源：http://dali.jinqigfzy.top/Article/details/gtdjjunbot.html

read -rp "请输入: " ans
来源：http://dali.zhoulong.xyz/Article/details/gttoiqbayk.html

[R78] 交互式菜单
来源：http://dali.gzhubu.top/Article/details/gtlhzuodjr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.redwolf501.top/Article/details/gtvzutatav.html

[R79] 解析命令行选项
来源：http://dali.cheryme.top/Article/details/gtdxzvqwjy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.wangshuangyany.cn/Article/details/gtqivkoiiw.html

[R80] 查看脚本执行耗时
来源：http://dali.316326.xyz/Article/details/gtthpwtbun.html

time ./run.sh
来源：http://dali.daria6918.cn/Article/details/gtopzphzau.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtmmfnflyp.html

S. C / C++ 专题
来源：http://dali.andypj.xyz/Article/details/gtmfzqidfh.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtvokpbdhx.html

[S01] C：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtlsmlboia.html

#include <stdio.h>
来源：http://dali.hammf.cn/Article/details/gtfxaxgjjn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.9152youxi.cn/Article/details/gtlocshsgk.html

[S02] C：变量与格式化输出
来源：http://dali.cqqwz.cn/Article/details/gtvvkepegg.html

int a = 10; printf("%d\n", a);
来源：http://dali.yuxming.cn/Article/details/gtrfcsjdfz.html

[S03] C：读入整数
来源：http://dali.daria6918.cn/Article/details/gtiixqmjjj.html

int x; scanf("%d", &x);
来源：http://dali.xziqi.cn/Article/details/gtvsqagqqy.html

[S04] C：字符串复制
来源：http://dali.andypj.xyz/Article/details/gtsuzehxem.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.svipenyu.cn/Article/details/gtlwsyyrcv.html

[S05] C：字符串长度
来源：http://dali.wangshuangyany.cn/Article/details/gttnzwayxt.html

strlen(s)
来源：http://dali.havefunace.top/Article/details/gtqwqrrpjh.html

[S06] C：字符串比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthskkftxq.html

strcmp(a, b) == 0
来源：http://dali.dashuyun.cn/Article/details/gtxaxamldw.html

[S07] C：数组遍历求和
来源：http://dali.yanxiufei.cn/Article/details/gtnuixyvrd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.havefunace.top/Article/details/gtdmsfxgmd.html

[S08] C：动态内存分配与释放
来源：http://dali.chenzaomai.com/Article/details/gtayzjlsfn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.meibo888.top/Article/details/gtvqfidntx.html

[S09] C：结构体定义与初始化
来源：http://dali.hywenlv.cn/Article/details/gtnaplqujd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.chenjidiqi.icu/Article/details/gtquyrofzp.html

[S10] C：指针与解引用
来源：http://dali.wangshuangyany.cn/Article/details/gtzcmbzild.html

int *p = &a;  *p = 5;
来源：http://dali.dianchejie.cn/Article/details/gtkeqtlcpp.html

[S11] C：逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gtytjgnylm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sufxvd.cn/Article/details/gtydmnoppw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.birdmap.top/Article/details/gtidbgxtvs.html

fclose(f);
来源：http://dali.kuanghao11.cn/Article/details/gthxrkyjxc.html

[S12] C：写文件
来源：http://dali.chenlongwang.top/Article/details/gtviunqinx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.chenzaomai.com/Article/details/gtsrstqjyy.html

[S13] C：宏定义
来源：http://dali.zdqjudy.top/Article/details/gtngyzhgew.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hfpthk.cn/Article/details/gtylpwmfpf.html

[S14] C：枚举
来源：http://dali.ehwqpu.com/Article/details/gtcchtnhrl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdkxmnlda.html

[S15] C：类型转换
来源：http://dali.yangfankeji.com/Article/details/gtqvxkznfq.html

(double) a / b
来源：http://dali.gotoacloud.top/Article/details/gtuvbpdotg.html

[S16] C：位操作置位
来源：http://dali.jinghuilouyu.cn/Article/details/gtdxthenjb.html

x |= (1 << 3);
来源：http://dali.kuanghao11.cn/Article/details/gtgdfjexch.html

[S17] C：安全拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gtjzjssihp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.tanke756.top/Article/details/gtltwlrdns.html

[S18] C：命令行参数
来源：http://dali.nwbrower.top/Article/details/gtwcmgtfij.html

int main(int argc, char **argv)
来源：http://dali.jyoumei.cn/Article/details/gtoyojnfae.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gthsvxxcoj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhoulong.xyz/Article/details/gtvsexnjjb.html

[S20] C：二分查找
来源：http://dali.guannengcc.top/Article/details/gtkzglyzfq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gtssexnyej.html

[S21] C：字符类别判断
来源：http://dali.sufxvd.cn/Article/details/gtkeohfklo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shuidangran.top/Article/details/gtuexlmpex.html

[S22] C：字符串转数字
来源：http://dali.aizwys.cn/Article/details/gtklgwxjvp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zdqjudy.top/Article/details/gtntubbxbj.html

[S23] C：随机数
来源：http://dali.c1oappe.top/Article/details/gtowkwjilr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.316326.xyz/Article/details/gtxffbzhrb.html

[S24] C：获取本地时间
来源：http://dali.kuanghao11.cn/Article/details/gtiesajwjg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.guannengcc.top/Article/details/gtiuobdwor.html

[S25] C：内存拷贝
来源：http://dali.hongshengwenyu.top/Article/details/gtbgwjomny.html

memcpy(dst, src, n);
来源：http://dali.sweek.top/Article/details/gthdduamcl.html

[S26] C：内存清零
来源：http://dali.gotoacloud.top/Article/details/gtuvgpfolk.html

memset(a, 0, sizeof a);
来源：http://dali.tian-w.cn/Article/details/gteasbiboy.html

[S27] C：定义常量
来源：http://dali.tian-w.cn/Article/details/gttdigbazq.html

const double PI = 3.14159;
来源：http://dali.jqgufenzy.top/Article/details/gtipgtoqgw.html

[S28] C：静态变量
来源：http://dali.pycfn.com/Article/details/gtltqpbtec.html

static int counter = 0;
来源：http://dali.ivvv.top/Article/details/gtvrlkvqsf.html

[S29] C：变参函数
来源：http://dali.ybcxt.top/Article/details/gtsuiprpyj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.aibaodan.cn/Article/details/gtlmmxvapu.html

[S30] C：头文件保护
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjoufanei.html

#ifndef X_H
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzjyonkpt.html

#define X_H
来源：http://dali.xuetiantiany.cn/Article/details/gtmamugdhl.html

#endif
来源：http://dali.gzhubu.top/Article/details/gthwtkblhq.html

[S31] C++：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtypadacmx.html

#include <iostream>
来源：http://dali.gzhubu.top/Article/details/gtmvotkdni.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.dianchejie.cn/Article/details/gtcchzxfnq.html

[S32] C++：字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtygrwmmfr.html

std::string s = "hi";  s += "!";
来源：http://dali.mhx1999.top/Article/details/gtjpzineor.html

[S33] C++：vector 增删
来源：http://dali.zycfv.cn/Article/details/gtjovelmni.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gotoacloud.top/Article/details/gtwnbhecbs.html

[S34] C++：遍历 vector
来源：http://dali.zhaomingkeji.xyz/Article/details/gtalevlobz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.haohaochexian.top/Article/details/gtwxwcrjpd.html

[S35] C++：map
来源：http://dali.guannengcc.top/Article/details/gtcenvuiqd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtmcvawomc.html

[S36] C++：unordered_map
来源：http://dali.c1oappe.top/Article/details/gtbfypgmfh.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yonumen.top/Article/details/gtpsckusoy.html

[S37] C++：set
来源：http://dali.mhx1999.top/Article/details/gtpkdgsqxb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nwbrower.top/Article/details/gtmcamesbd.html

[S38] C++：排序
来源：http://dali.svipenyu.cn/Article/details/gtmrvrkxtz.html

std::sort(v.begin(), v.end());
来源：http://dali.0kj1m.cn/Article/details/gttusfxift.html

[S39] C++：自定义比较器排序
来源：http://dali.havefunace.top/Article/details/gtbbcoveki.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.guowangkeji.top/Article/details/gtdhpkaouo.html

[S40] C++：查找元素
来源：http://dali.nanxuanxn.top/Article/details/gtjiuylshs.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nanxinkj.top/Article/details/gtmpiynlsr.html

[S41] C++：类与构造函数
来源：http://dali.jqgufenzy.top/Article/details/gtjfkrsnxz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.chenjidiqi.icu/Article/details/gtrygqmbbq.html

[S42] C++：继承与虚函数
来源：http://dali.gaohongyu789.top/Article/details/gtdvwecotm.html

class B : public Base { public: void f() override {} };
来源：http://dali.zycfv.cn/Article/details/gtiumnvdmj.html

[S43] C++：智能指针
来源：http://dali.ybcxt.top/Article/details/gtapjspcmz.html

auto p = std::make_unique<int>(5);
来源：http://dali.hywenlv.cn/Article/details/gthlbsvpyo.html

[S44] C++：引用传参
来源：http://dali.hammf.cn/Article/details/gtqidqglul.html

void inc(int &x) { ++x; }
来源：http://dali.bjfxy.top/Article/details/gtfpfdogzc.html

[S45] C++：lambda
来源：http://dali.jqgufenzy.top/Article/details/gthmkdezck.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xylfe.cn/Article/details/gtvpqviqrg.html

[S46] C++：函数模板
来源：http://dali.ppjwa.cn/Article/details/gthairdgco.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hnxiangtu.top/Article/details/gtxmuuvzzw.html

[S47] C++：结构化绑定遍历
来源：http://dali.jqgfzy.top/Article/details/gtdnlldhxt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.andypj.xyz/Article/details/gtaimkzdzf.html

[S48] C++：逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gtofgqlkxa.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.kuanghao11.cn/Article/details/gtipjteoax.html

while (std::getline(in, line)) { }
来源：http://dali.jqgfzy.top/Article/details/gtqlxumigv.html

[S49] C++：写文件
来源：http://dali.dianchejie.cn/Article/details/gtwdticcpl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jlsjyb.cn/Article/details/gtltapawrn.html

[S50] C++：格式化数字
来源：http://dali.jiagoushi.top/Article/details/gtmbdehxpa.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gtaooqujis.html

[S51] C++：显式类型转换
来源：http://dali.cdnleiting.top/Article/details/gtaaujdvro.html

static_cast<double>(a) / b
来源：http://dali.iojbl.cn/Article/details/gtekudanom.html

[S52] C++：const 与 noexcept
来源：http://dali.feifeiyinyue.top/Article/details/gtniiszzuc.html

int size() const noexcept { return n_; }
来源：http://dali.jianghu66.top/Article/details/gttqbvmuhu.html

[S53] C++：移动语义
来源：http://dali.aizwys.cn/Article/details/gtzwlliaro.html

std::vector<int> w = std::move(v);
来源：http://dali.smart0.xyz/Article/details/gtbpsknrjm.html

[S54] C++：异常处理
来源：http://dali.iojbl.cn/Article/details/gtisugidtv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xinyue.icu/Article/details/gtujlxcttn.html

[S55] C++：结构化绑定
来源：http://dali.nanxuanxn.top/Article/details/gtzepqpttt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yvedp.cn/Article/details/gtlwuabqgz.html

[S56] C++：optional
来源：http://dali.yuanzhike.top/Article/details/gtzabhumtt.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yangfankeji.com/Article/details/gtvpfksukp.html

[S57] C++：编译期常量
来源：http://dali.meibo888.top/Article/details/gtpirzfdgp.html

constexpr int N = 10;
来源：http://dali.xuetiantiany.cn/Article/details/gtiscvvesp.html

[S58] C++：命名空间
来源：http://dali.xylfe.cn/Article/details/gtoijmbcss.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinqigufen.top/Article/details/gtpttyovqg.html

[S59] C++：静态断言
来源：http://dali.yvedp.cn/Article/details/gtymhcmsqi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sufxvd.cn/Article/details/gtqongbbbl.html

[S60] C++：遍历并删除元素
来源：http://dali.shangyingyoupin.top/Article/details/gthujerxrg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hywenlv.cn/Article/details/gtdcbzvptv.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtnsmauegi.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sxryk.cn/Article/details/gtbeiqvohg.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtsyvromnh.html

[T01] Kotlin：Hello World
来源：http://dali.iojbl.cn/Article/details/gtegqtqaaa.html

println("Hello")
来源：http://dali.yj20258.top/Article/details/gtqadqbxzi.html

[T02] Kotlin：变量
来源：http://dali.cashguo.top/Article/details/gtqagchcgk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.meibo888.top/Article/details/gthfaftrpj.html

[T03] Kotlin：字符串模板
来源：http://dali.shuidangran.top/Article/details/gtmsqpjbuu.html

"值: $b"
来源：http://dali.chenlongwang.top/Article/details/gtulmigech.html

[T04] Kotlin：空安全
来源：http://dali.yvedp.cn/Article/details/gttpijduxi.html

val n: String? = null;  n?.length
来源：http://dali.iojbl.cn/Article/details/gtoiqhcxpg.html

[T05] Kotlin：when 表达式
来源：http://dali.yvedp.cn/Article/details/gtvoalzveh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.feifeiyinyue.top/Article/details/gtgumozivc.html

[T06] Kotlin：集合映射
来源：http://dali.dashuyun.cn/Article/details/gtjggegkax.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.pycfn.com/Article/details/gtihsirrvr.html

[T07] Kotlin：集合过滤
来源：http://dali.cdnleiting.top/Article/details/gtbuesmoeo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.vqdsnc.cn/Article/details/gtpszasubf.html

[T08] Kotlin：数据类
来源：http://dali.c1oappe.top/Article/details/gtqzivdyvr.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gtlubdltxa.html

[T09] Kotlin：扩展函数
来源：http://dali.zhengqikj.top/Article/details/gtjrpnzkae.html

fun String.exclaim() = this + "!"
来源：http://dali.jqgufenzy.top/Article/details/gtpkngnies.html

[T10] Kotlin：默认参数
来源：http://dali.havefunace.top/Article/details/gtfempqagb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shuidangran.top/Article/details/gtmesuxynj.html

[T11] Kotlin：协程
来源：http://dali.jinghuilouyu.cn/Article/details/gtjtpyqtqi.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hnqzz.top/Article/details/gtcyfnarcu.html

[T12] Kotlin：解构声明
来源：http://dali.yonumen.top/Article/details/gtcyglhltp.html

val (a, b) = Pair(1, 2)
来源：http://dali.c1oappe.top/Article/details/gtsziaoezw.html

[T13] Kotlin：只读 Map
来源：http://dali.hysaishi.cn/Article/details/gtuhkwuril.html

val m = mapOf("a" to 1)
来源：http://dali.yanxiufei.cn/Article/details/gtesiwrpfn.html

[T14] Kotlin：循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkjhyxdnk.html

for (i in 1..10) println(i)
来源：http://dali.guowangkeji.top/Article/details/gtqabkiaxv.html

[T15] Kotlin：接口
来源：http://dali.0kj1m.cn/Article/details/gtjhmssjfw.html

interface Shape { fun area(): Double }
来源：http://dali.dashuyun.cn/Article/details/gtxiistpis.html

[T16] Swift：Hello World
来源：http://dali.shuidangran.top/Article/details/gtqocdnimu.html

print("Hello")
来源：http://dali.zhixingplan.top/Article/details/gtdvfeytjq.html

[T17] Swift：变量与常量
来源：http://dali.meibo888.top/Article/details/gtmquheuqz.html

var a = 1;  let b = 2
来源：http://dali.andypj.xyz/Article/details/gtxjbozvvn.html

[T18] Swift：字符串插值
来源：http://dali.shuidangran.top/Article/details/gtajqvygct.html

"值: \(b)"
来源：http://dali.yueranfly.top/Article/details/gtamjuppxz.html

[T19] Swift：可选绑定
来源：http://dali.yuxming.cn/Article/details/gtumtvrfsk.html

if let n = opt { print(n) }
来源：http://dali.cheryme.top/Article/details/gtiedabfkn.html

[T20] Swift：数组操作
来源：http://dali.xziqi.cn/Article/details/gtagnzlpqf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhiwuduotai.top/Article/details/gtwhoihurh.html

[T21] Swift：遍历
来源：http://dali.tanke756.top/Article/details/gtkjwuvmkd.html

for x in a { print(x) }
来源：http://dali.xziqi.cn/Article/details/gtdzkxdjjv.html

[T22] Swift：字典
来源：http://dali.ydzc1.top/Article/details/gtlocczzgt.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.0kj1m.cn/Article/details/gtsghxqbhk.html

[T23] Swift：函数
来源：http://dali.svipenyu.cn/Article/details/gtjefhguvi.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yj20258.top/Article/details/gtoehdhzue.html

[T24] Swift：闭包
来源：http://dali.mhx1999.top/Article/details/gtrekuhual.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cdnleiting.top/Article/details/gtnhzbpesp.html

[T25] Swift：结构体
来源：http://dali.jqgfzy.top/Article/details/gtlsxzeavj.html

struct P { var x: Int }
来源：http://dali.hammf.cn/Article/details/gtbozlmwbr.html

[T26] Swift：类与重写
来源：http://dali.gzhubu.top/Article/details/gtnngrrqea.html

class A: Base { override func f() {} }
来源：http://dali.zhengqikj.top/Article/details/gtupbiqmol.html

[T27] Swift：错误处理
来源：http://dali.xziqi.cn/Article/details/gtinfzvtku.html

do { try f() } catch { print(error) }
来源：http://dali.wangshuangyany.cn/Article/details/gtlkydxzyy.html

[T28] Swift：枚举
来源：http://dali.jlsjyb.cn/Article/details/gtmkqoisra.html

enum Color { case red, green }
来源：http://dali.pycfn.com/Article/details/gtspyvlbfp.html

[T29] Swift：guard 提前返回
来源：http://dali.shanyushiyangtech.top/Article/details/gthvsiedfi.html

guard let x = opt else { return }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvfdzciie.html

[T30] Swift：协议
来源：http://dali.vqdsnc.cn/Article/details/gtxkudcmkm.html

protocol Shape { func area() -> Double }
来源：http://dali.jiagoushi.top/Article/details/gtuzzwbwph.html

[T31] Lua：Hello World
来源：http://dali.yueranfly.top/Article/details/gttxgpciqz.html

print("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gtbohkubvl.html

[T32] Lua：局部变量
来源：http://dali.dianchejie.cn/Article/details/gtuplprmtk.html

local a = 1
来源：http://dali.0kj1m.cn/Article/details/gtrtznupyj.html

[T33] Lua：表（数组）
来源：http://dali.tian-w.cn/Article/details/gtgzkoefsx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.9152youxi.cn/Article/details/gtlpikapbj.html

[T34] Lua：遍历表
来源：http://dali.ehwqpu.com/Article/details/gtmjfbkjqn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.sxryk.cn/Article/details/gtellsopur.html

[T35] Lua：字典表
来源：http://dali.sweek.top/Article/details/gtvheeuqze.html

local d = { a = 1 };  d.b = 2
来源：http://dali.nwbrower.top/Article/details/gtfrlrgagy.html

[T36] Lua：函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmldewgf.html

function add(a, b) return a + b end
来源：http://dali.9152youxi.cn/Article/details/gtmubbfjoo.html

[T37] Lua：字符串拼接
来源：http://dali.yongpay.top/Article/details/gtcoasnyej.html

"a" .. "b"
来源：http://dali.gogol.net.cn/Article/details/gtoindyqmx.html

[T38] Lua：条件
来源：http://dali.svipenyu.cn/Article/details/gtjcglaipc.html

if x > 0 then print("正") end
来源：http://dali.0kj1m.cn/Article/details/gtqmaxtegk.html

[T39] Lua：模式匹配
来源：http://dali.jqgufenzy.top/Article/details/gtznihgoie.html

string.find(s, "%d+")
来源：http://dali.fzhhl.top/Article/details/gtfddxyeer.html

[T40] Lua：元表
来源：http://dali.guowangkeji.top/Article/details/gtamajqvxx.html

setmetatable({}, { __index = base })
来源：http://dali.smart0.xyz/Article/details/gtmcrxoxpl.html

[T41] Perl：Hello World
来源：http://dali.tanke756.top/Article/details/gttqylrxrx.html

print "Hello\n";
来源：http://dali.316326.xyz/Article/details/gthkprmdzy.html

[T42] Perl：变量类型
来源：http://dali.quarkkingdee.top/Article/details/gtdlbdqhsn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sysykeji.top/Article/details/gtcktsonkx.html

[T43] Perl：字符串插值
来源：http://dali.pycfn.com/Article/details/gtavmxcsrg.html

"值: $a"
来源：http://dali.yonumen.top/Article/details/gtyrrahmwc.html

[T44] Perl：条件
来源：http://dali.xuetiantiany.cn/Article/details/gtqjejrigf.html

if ($a > 0) { print "正"; }
来源：http://dali.chenlongwang.top/Article/details/gthtjdgiad.html

[T45] Perl：数组遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtguykskgq.html

for my $x (@arr) { print $x; }
来源：http://dali.wangshuangyany.cn/Article/details/gtaaaanehx.html

[T46] Perl：哈希操作
来源：http://dali.gogol.net.cn/Article/details/gtifkgozuj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hywenlv.cn/Article/details/gtginzxuff.html

[T47] Perl：正则捕获
来源：http://dali.birdmap.top/Article/details/gtbhtjtgsc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.vqdsnc.cn/Article/details/gtdvngtcrz.html

[T48] Perl：正则替换
来源：http://dali.xuetiantiany.cn/Article/details/gtoibbnqba.html

$s =~ s/old/new/g;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrauiezmp.html

[T49] Perl：函数
来源：http://dali.guowangkeji.top/Article/details/gtdvptusex.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.zdqjudy.top/Article/details/gtrxmlifhn.html

[T50] Perl：逐行读文件
来源：http://dali.jianghu66.top/Article/details/gtmbmezjxz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hywenlv.cn/Article/details/gtsluflfox.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.sysykeji.top/Article/details/gtpmudxsuh.html

[T51] Scala：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtsofztiab.html

println("Hello")
来源：http://dali.sufxvd.cn/Article/details/gtflxxpaqt.html

[T52] Scala：变量
来源：http://dali.sysykeji.top/Article/details/gtknesfltn.html

val a = 1;  var b = 2
来源：http://dali.jinqigufen.top/Article/details/gthfqoozxc.html

[T53] Scala：字符串插值
来源：http://dali.jiagoushi.top/Article/details/gtotvysxqb.html

s"值: $b"
来源：http://dali.kuanghao11.cn/Article/details/gtfzbznekc.html

[T54] Scala：集合映射
来源：http://dali.zdqjudy.top/Article/details/gtljqrbqfh.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtzfckbfsz.html

[T55] Scala：集合过滤
来源：http://dali.mhx1999.top/Article/details/gtfsbzbbni.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.9152youxi.cn/Article/details/gtpeckdcuz.html

[T56] Scala：样例类
来源：http://dali.pycfn.com/Article/details/gtuegpduqv.html

case class User(name: String, age: Int)
来源：http://dali.cashguo.top/Article/details/gtayoarxjy.html

[T57] Scala：模式匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtycxftsxc.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.nanxuanxn.top/Article/details/gtbbdettro.html

[T58] Scala：函数定义
来源：http://dali.hywenlv.cn/Article/details/gtpgvnyayp.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hywenlv.cn/Article/details/gtfbmkbwas.html

[T59] Scala：循环
来源：http://dali.quarkkingdee.top/Article/details/gtxlbidkkk.html

for (i <- 1 to 10) println(i)
来源：http://dali.xylfe.cn/Article/details/gtofmxhfaa.html

[T60] Scala：折叠
来源：http://dali.yj202588.top/Article/details/gtvmafnxju.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.aizwys.cn/Article/details/gtrmharajk.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtexfzvkaq.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.cashguo.top/Article/details/gtsndyafzh.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwxafkfzl.html

[U01] Py：创建虚拟环境
来源：http://dali.kuanghao11.cn/Article/details/gtgkxnerlc.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.gogol.net.cn/Article/details/gtliwsqadl.html

[U02] Py：导出 / 安装依赖
来源：http://dali.sysykeji.top/Article/details/gtdkxhdbgk.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.cqqwz.cn/Article/details/gtichdbgtu.html

[U03] Py：加载 .env 配置
来源：http://dali.kuanghao11.cn/Article/details/gtzcubywfm.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yuanzhike.top/Article/details/gtkowllxyl.html

[U04] Py：变量调试打印
来源：http://dali.cqqwz.cn/Article/details/gtubdxjboi.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.zycfv.cn/Article/details/gtexxmjfqi.html


<!-- 参考信息 -->