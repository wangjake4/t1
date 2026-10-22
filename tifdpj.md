代发 wailian999

free -h;  ps aux | grep nginx
来源：http://dali.xinyue.icu/Article/details/gt2pigevxgv.html

[R64] 结束进程
来源：http://dali.0kj1m.cn/Article/details/gt2nddfzbcw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinqigfzy.top/Article/details/gt2pkmirvqr.html

[R65] 查看端口占用
来源：http://dali.hywenlv.cn/Article/details/gt2aaumnjob.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.svipenyu.cn/Article/details/gt2wwyyfrro.html

[R66] 定时任务
来源：http://dali.bjfxy.top/Article/details/gt2hmdnxiib.html

crontab -e;  crontab -l
来源：http://dali.hammf.cn/Article/details/gt2tjcdvafh.html

[R67] 生成随机十六进制串
来源：http://dali.ydzc1.top/Article/details/gt2gsjhieaa.html

openssl rand -hex 16
来源：http://dali.xylfe.cn/Article/details/gt2epmseypi.html

[R68] 计算文件校验值
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gwtvwdxp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gt2huqplwxn.html

[R69] 生成随机密码
来源：http://dali.ehwqpu.com/Article/details/gt2fpnjvxzx.html

head -c 16 /dev/urandom | base64
来源：http://dali.wangdashe.top/Article/details/gt2zusmgala.html

[R70] 时间戳与互转
来源：http://dali.aizwys.cn/Article/details/gt2xlkmsojz.html

date +%s;  date -d @1700000000
来源：http://dali.xylfe.cn/Article/details/gt2bgcynqte.html

[R71] 日期格式化
来源：http://dali.chenzaomai.com/Article/details/gt2kmjrzjaa.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jlsjyb.cn/Article/details/gt2runaygyq.html

[R72] 等待端口就绪
来源：http://dali.chenzaomai.com/Article/details/gt2jghvkrfd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.dashuyun.cn/Article/details/gt2nqgrcncb.html

[R73] 分割大日志
来源：http://dali.shuidangran.top/Article/details/gt2zobnidef.html

split -l 1000 big.log part_
来源：http://dali.chenzaomai.com/Article/details/gt2lgcxzfco.html

[R74] 批量重命名
来源：http://dali.nwbrower.top/Article/details/gt2ujqifgbo.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sxryk.cn/Article/details/gt2obrdxalx.html

[R75] 导出环境变量
来源：http://dali.tianlin.xyz/Article/details/gt2riiliyep.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sxryk.cn/Article/details/gt2botjxovn.html

[R76] 使用临时文件
来源：http://dali.jianghu66.top/Article/details/gt2jekmsttw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.pengpengdd.cyou/Article/details/gt2hzadfoiv.html

[R77] 读取用户输入
来源：http://dali.snrcjt.cn/Article/details/gt2pmurzuwn.html

read -rp "请输入: " ans
来源：http://dali.gaohongyu789.top/Article/details/gt2yzxotnye.html

[R78] 交互式菜单
来源：http://dali.tanke756.top/Article/details/gt2mhnkcndy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhiwuduotai.top/Article/details/gt2rwfrlozu.html

[R79] 解析命令行选项
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vujxnqbq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinqigfzy.top/Article/details/gt2nnvrvzdo.html

[R80] 查看脚本执行耗时
来源：http://dali.tianlin.xyz/Article/details/gt2scpyhxnc.html

time ./run.sh
来源：http://dali.haohaochexian.top/Article/details/gt2jeaelyuu.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gt2gkagegbz.html

S. C / C++ 专题
来源：http://dali.ehwqpu.com/Article/details/gt2vxcfykvz.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2bhiffzdj.html

[S01] C：Hello World
来源：http://dali.yuxming.cn/Article/details/gt2sssueyfe.html

#include <stdio.h>
来源：http://dali.andypj.xyz/Article/details/gt2mhfjzumu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yongpay.top/Article/details/gt2tlglipuo.html

[S02] C：变量与格式化输出
来源：http://dali.jyoumei.cn/Article/details/gt2ygtrplie.html

int a = 10; printf("%d\n", a);
来源：http://dali.sufxvd.cn/Article/details/gt2jnvbozep.html

[S03] C：读入整数
来源：http://dali.tianlin.xyz/Article/details/gt2iewmkors.html

int x; scanf("%d", &x);
来源：http://dali.ybcxt.top/Article/details/gt2vpnatalu.html

[S04] C：字符串复制
来源：http://dali.jqgufenzy.top/Article/details/gt2wxxczbrj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yj20258888.top/Article/details/gt2wptjbcfg.html

[S05] C：字符串长度
来源：http://dali.feifeiyinyue.top/Article/details/gt2zghfpwrs.html

strlen(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vnqofysz.html

[S06] C：字符串比较
来源：http://dali.nanxinkj.top/Article/details/gt2ysxgqeoe.html

strcmp(a, b) == 0
来源：http://dali.zhongyouzk.top/Article/details/gt2rvteqwke.html

[S07] C：数组遍历求和
来源：http://dali.kuanghao11.cn/Article/details/gt2kykztdbu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zycfv.cn/Article/details/gt2iuomftox.html

[S08] C：动态内存分配与释放
来源：http://dali.zhongyouzk.top/Article/details/gt2vdantlly.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hnxiangtu.top/Article/details/gt2xefcblxe.html

[S09] C：结构体定义与初始化
来源：http://dali.hysaishi.cn/Article/details/gt2axvxengv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.wangdashe.top/Article/details/gt2urncbdld.html

[S10] C：指针与解引用
来源：http://dali.xuanzx.com/Article/details/gt2vqtoihpm.html

int *p = &a;  *p = 5;
来源：http://dali.jianghu66.top/Article/details/gt2tgydajjg.html

[S11] C：逐行读文件
来源：http://dali.yj202588.top/Article/details/gt2atmpbdgu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.chenjidiqi.icu/Article/details/gt2cfxeizdb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zycfv.cn/Article/details/gt2vmycuvbq.html

fclose(f);
来源：http://dali.hywenlv.cn/Article/details/gt2jylalxyc.html

[S12] C：写文件
来源：http://dali.hfpthk.cn/Article/details/gt2qfuxwvue.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shzxlz.cn/Article/details/gt2hhcixtea.html

[S13] C：宏定义
来源：http://dali.iojbl.cn/Article/details/gt2rbmiqdqx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.meibo888.top/Article/details/gt2pdgzlwhh.html

[S14] C：枚举
来源：http://dali.nanxinkj.top/Article/details/gt2chptctua.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.0kj1m.cn/Article/details/gt2onpqdoam.html

[S15] C：类型转换
来源：http://dali.jqgfzy.top/Article/details/gt2sjbvqwto.html

(double) a / b
来源：http://dali.jiagoushi.top/Article/details/gt2srwivjly.html

[S16] C：位操作置位
来源：http://dali.chenzaomai.com/Article/details/gt2zpfrrubw.html

x |= (1 << 3);
来源：http://dali.nanxuanxn.top/Article/details/gt2mykjilel.html

[S17] C：安全拼接字符串
来源：http://dali.bjfxy.top/Article/details/gt2kgtkwsjc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gjhjblca.html

[S18] C：命令行参数
来源：http://dali.c1oappe.top/Article/details/gt2hxxrsfcc.html

int main(int argc, char **argv)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xfzroudu.html

[S19] C：快速排序
来源：http://dali.xziqi.cn/Article/details/gt2gwpnrqkx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.mhx1999.top/Article/details/gt2ytdwpplz.html

[S20] C：二分查找
来源：http://dali.cucudq.cn/Article/details/gt2tnabiews.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.dianchejie.cn/Article/details/gt2vkgacucr.html

[S21] C：字符类别判断
来源：http://dali.zhongyouzk.top/Article/details/gt2ctbfhjwo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.chenjidiqi.icu/Article/details/gt2mcvjouhe.html

[S22] C：字符串转数字
来源：http://dali.fengsongda.top/Article/details/gt2jkomcdyk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.haohaochexian.top/Article/details/gt2gjlwjbat.html

[S23] C：随机数
来源：http://dali.zhiwuduotai.top/Article/details/gt2xjbftjzh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ydzc1.top/Article/details/gt2qhinhvgb.html

[S24] C：获取本地时间
来源：http://dali.hysaishi.cn/Article/details/gt2nwrldrhn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hnxiangtu.top/Article/details/gt2blakppnm.html

[S25] C：内存拷贝
来源：http://dali.yongpay.top/Article/details/gt2qlhmnqdn.html

memcpy(dst, src, n);
来源：http://dali.zhixingplan.top/Article/details/gt2njqqhhct.html

[S26] C：内存清零
来源：http://dali.daxiang520.top/Article/details/gt2xrewucxb.html

memset(a, 0, sizeof a);
来源：http://dali.hammf.cn/Article/details/gt2pisjsvdn.html

[S27] C：定义常量
来源：http://dali.yongpay.top/Article/details/gt2hauevvaf.html

const double PI = 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gt2jgflxuie.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rbnnwutm.html

static int counter = 0;
来源：http://dali.9152youxi.cn/Article/details/gt2svjmdzzw.html

[S29] C：变参函数
来源：http://dali.cdnleiting.top/Article/details/gt2exewnzfi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.316326.xyz/Article/details/gt2sytoiveq.html

[S30] C：头文件保护
来源：http://dali.chenlongwang.top/Article/details/gt2bohsfgbz.html

#ifndef X_H
来源：http://dali.iojbl.cn/Article/details/gt2bujghtga.html

#define X_H
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wpcoqwmv.html

#endif
来源：http://dali.pycfn.com/Article/details/gt2hivdptaz.html

[S31] C++：Hello World
来源：http://dali.zhixingplan.top/Article/details/gt2ittwijqk.html

#include <iostream>
来源：http://dali.sweek.top/Article/details/gt2gvyjncon.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jlsjyb.cn/Article/details/gt2sptetehy.html

[S32] C++：字符串
来源：http://dali.smart0.xyz/Article/details/gt2xkijoltv.html

std::string s = "hi";  s += "!";
来源：http://dali.xziqi.cn/Article/details/gt2zozacoli.html

[S33] C++：vector 增删
来源：http://dali.ivvv.top/Article/details/gt2aisuhdqq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.havefunace.top/Article/details/gt2jcjomcpw.html

[S34] C++：遍历 vector
来源：http://dali.gaohongyu789.top/Article/details/gt2fmlyugkc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cdnleiting.top/Article/details/gt2pgqdfoud.html

[S35] C++：map
来源：http://dali.bjfxy.top/Article/details/gt2zienhjhn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guannengcc.top/Article/details/gt2vhlynfjc.html

[S36] C++：unordered_map
来源：http://dali.dianchejie.cn/Article/details/gt2zvmwrmxv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gt2bhodtabe.html

[S37] C++：set
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yhqhagrk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hammf.cn/Article/details/gt2jiljkhfy.html

[S38] C++：排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lyfbxays.html

std::sort(v.begin(), v.end());
来源：http://dali.bjfxy.top/Article/details/gt2txvdnntb.html

[S39] C++：自定义比较器排序
来源：http://dali.meibo888.top/Article/details/gt2ioxgpkys.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.316326.xyz/Article/details/gt2hvkpjlce.html

[S40] C++：查找元素
来源：http://dali.chenzaomai.com/Article/details/gt2oxvlogva.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hysaishi.cn/Article/details/gt2xrmuvlvr.html

[S41] C++：类与构造函数
来源：http://dali.dashuyun.cn/Article/details/gt2bonyylmy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wdfgxsyu.html

[S42] C++：继承与虚函数
来源：http://dali.aibaodan.cn/Article/details/gt2aqknstwn.html

class B : public Base { public: void f() override {} };
来源：http://dali.shzxlz.cn/Article/details/gt2sejibdxj.html

[S43] C++：智能指针
来源：http://dali.haohaochexian.top/Article/details/gt2mfgvcgoh.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinqigfzy.top/Article/details/gt2ywiiwahv.html

[S44] C++：引用传参
来源：http://dali.zhixingplan.top/Article/details/gt2cotokmuk.html

void inc(int &x) { ++x; }
来源：http://dali.daria6918.cn/Article/details/gt2wacjlffg.html

[S45] C++：lambda
来源：http://dali.cucudq.cn/Article/details/gt2jjxhetby.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sysykeji.top/Article/details/gt2xkppsknf.html

[S46] C++：函数模板
来源：http://dali.redwolf501.top/Article/details/gt2ywgfbwkj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yanxiufei.cn/Article/details/gt2uqygbhko.html

[S47] C++：结构化绑定遍历
来源：http://dali.chenlongwang.top/Article/details/gt2ftvkxdbe.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jqgfzy.top/Article/details/gt2mjslwrsm.html

[S48] C++：逐行读文件
来源：http://dali.snrcjt.cn/Article/details/gt2fwtwwejk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.chenlongwang.top/Article/details/gt2kqlbbutp.html

while (std::getline(in, line)) { }
来源：http://dali.sweek.top/Article/details/gt2worbfrjl.html

[S49] C++：写文件
来源：http://dali.vqdsnc.cn/Article/details/gt2ugdftiev.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.andypj.xyz/Article/details/gt2xodobsqa.html

[S50] C++：格式化数字
来源：http://dali.fzhhl.top/Article/details/gt2oqtbekws.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.pycfn.com/Article/details/gt2jqralevs.html

[S51] C++：显式类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ziobwzka.html

static_cast<double>(a) / b
来源：http://dali.mhx1999.top/Article/details/gt2xnzxlrch.html

[S52] C++：const 与 noexcept
来源：http://dali.zdqjudy.top/Article/details/gt2pmmlkhcg.html

int size() const noexcept { return n_; }
来源：http://dali.cheryme.top/Article/details/gt2kyblnhru.html

[S53] C++：移动语义
来源：http://dali.hongshengwenyu.top/Article/details/gt2huhtddlq.html

std::vector<int> w = std::move(v);
来源：http://dali.zhiwuduotai.top/Article/details/gt2dbqmgaei.html

[S54] C++：异常处理
来源：http://dali.jyoumei.cn/Article/details/gt2buvfpxaq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.snrcjt.cn/Article/details/gt2ofmhmcpr.html

[S55] C++：结构化绑定
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zypwhsic.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zytxqzep.html

[S56] C++：optional
来源：http://dali.xylfe.cn/Article/details/gt2numrafig.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xpndrihd.html

[S57] C++：编译期常量
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2inqlvtzh.html

constexpr int N = 10;
来源：http://dali.wangshuangyany.cn/Article/details/gt2iucgesdm.html

[S58] C++：命名空间
来源：http://dali.zhijiandao.cn/Article/details/gt2zynvuxkg.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinqigfzy.top/Article/details/gt2ydmqeukp.html

[S59] C++：静态断言
来源：http://dali.smart0.xyz/Article/details/gt2akyygpyg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hnqzz.top/Article/details/gt2psseumdg.html

[S60] C++：遍历并删除元素
来源：http://dali.cdnleiting.top/Article/details/gt2tvywiykm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xziqi.cn/Article/details/gt2hrguwvjt.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gt2ssklutqt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zdqjudy.top/Article/details/gt2ndwoxjqt.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gt2zrskfqws.html

[T01] Kotlin：Hello World
来源：http://dali.dianchejie.cn/Article/details/gt2jmykiaif.html

println("Hello")
来源：http://dali.jinqigfzy.top/Article/details/gt2ksynaoci.html

[T02] Kotlin：变量
来源：http://dali.snrcjt.cn/Article/details/gt2oukfgztm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.nanxinkj.top/Article/details/gt2oqlnscjx.html

[T03] Kotlin：字符串模板
来源：http://dali.yj20258.top/Article/details/gt2vhxldymp.html

"值: $b"
来源：http://dali.cheryme.top/Article/details/gt2cafmjvpq.html

[T04] Kotlin：空安全
来源：http://dali.smart0.xyz/Article/details/gt2xbndmjts.html

val n: String? = null;  n?.length
来源：http://dali.shuidangran.top/Article/details/gt2cenzzdou.html

[T05] Kotlin：when 表达式
来源：http://dali.quarkkingdee.top/Article/details/gt2urlehndr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hywenlv.cn/Article/details/gt2ziwcxppd.html

[T06] Kotlin：集合映射
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cvqocrok.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hnqzz.top/Article/details/gt2rominaql.html

[T07] Kotlin：集合过滤
来源：http://dali.gaohongyu789.top/Article/details/gt2vajpmdoy.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.kuanghao11.cn/Article/details/gt2jyiohjnl.html

[T08] Kotlin：数据类
来源：http://dali.shangyingyoupin.top/Article/details/gt2qgkqpqhl.html

data class User(val name: String, val age: Int)
来源：http://dali.xuanzx.com/Article/details/gt2swgupkye.html

[T09] Kotlin：扩展函数
来源：http://dali.havefunace.top/Article/details/gt2ofjwwaxd.html

fun String.exclaim() = this + "!"
来源：http://dali.feifeiyinyue.top/Article/details/gt2mzcecctm.html

[T10] Kotlin：默认参数
来源：http://dali.haohaochexian.top/Article/details/gt2ltzkveeu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.wangshuangyany.cn/Article/details/gt2fzvumkxx.html

[T11] Kotlin：协程
来源：http://dali.ydzc1.top/Article/details/gt2upsyoahp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gaohongyu789.top/Article/details/gt2smsislbt.html

[T12] Kotlin：解构声明
来源：http://dali.zycfv.cn/Article/details/gt2ghcobkky.html

val (a, b) = Pair(1, 2)
来源：http://dali.hongshengwenyu.top/Article/details/gt2noxuljwx.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gt2chsoloyl.html

val m = mapOf("a" to 1)
来源：http://dali.jinqigfzy.top/Article/details/gt2tguaykzc.html

[T14] Kotlin：循环
来源：http://dali.shzxlz.cn/Article/details/gt2hgfuwjvg.html

for (i in 1..10) println(i)
来源：http://dali.ybcxt.top/Article/details/gt2qteebtos.html

[T15] Kotlin：接口
来源：http://dali.gotoacloud.top/Article/details/gt2lzqawipd.html

interface Shape { fun area(): Double }
来源：http://dali.sysykeji.top/Article/details/gt2uglfnlco.html

[T16] Swift：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vosibnbt.html

print("Hello")
来源：http://dali.sufxvd.cn/Article/details/gt2xjagbcmi.html

[T17] Swift：变量与常量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xrvpcrsi.html

var a = 1;  let b = 2
来源：http://dali.wangdashe.top/Article/details/gt2nmmpofft.html

[T18] Swift：字符串插值
来源：http://dali.316326.xyz/Article/details/gt2qhekmukq.html

"值: \(b)"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2thvuaebo.html

[T19] Swift：可选绑定
来源：http://dali.hysaishi.cn/Article/details/gt2xlesmash.html

if let n = opt { print(n) }
来源：http://dali.zhoulong.xyz/Article/details/gt2ripmdojj.html

[T20] Swift：数组操作
来源：http://dali.wangdashe.top/Article/details/gt2xrgravvl.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jianghu66.top/Article/details/gt2kzalukhu.html

[T21] Swift：遍历
来源：http://dali.wangshuangyany.cn/Article/details/gt2itpfzjsd.html

for x in a { print(x) }
来源：http://dali.xylfe.cn/Article/details/gt2gddkhqep.html

[T22] Swift：字典
来源：http://dali.dashuyun.cn/Article/details/gt2eygazruc.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.redwolf501.top/Article/details/gt2odzlumet.html

[T23] Swift：函数
来源：http://dali.guowangkeji.top/Article/details/gt2fnaurnas.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cheryme.top/Article/details/gt2maibvgon.html

[T24] Swift：闭包
来源：http://dali.jianghu66.top/Article/details/gt2whntlixi.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cqqwz.cn/Article/details/gt2piyviadd.html

[T25] Swift：结构体
来源：http://dali.hammf.cn/Article/details/gt2tgpeqmjj.html

struct P { var x: Int }
来源：http://dali.yuanzhike.top/Article/details/gt2rnklside.html

[T26] Swift：类与重写
来源：http://dali.zhoulong.xyz/Article/details/gt2irtgubqj.html

class A: Base { override func f() {} }
来源：http://dali.chenjidiqi.icu/Article/details/gt2hedrrmmf.html

[T27] Swift：错误处理
来源：http://dali.jianghu66.top/Article/details/gt2awfzvclk.html

do { try f() } catch { print(error) }
来源：http://dali.birdmap.top/Article/details/gt2jhicesij.html

[T28] Swift：枚举
来源：http://dali.yj20258.top/Article/details/gt2nutbsnfn.html

enum Color { case red, green }
来源：http://dali.sufxvd.cn/Article/details/gt2wemduvvo.html

[T29] Swift：guard 提前返回
来源：http://dali.fzhhl.top/Article/details/gt2nzrltujl.html

guard let x = opt else { return }
来源：http://dali.nwbrower.top/Article/details/gt2wswcgaov.html

[T30] Swift：协议
来源：http://dali.tanke756.top/Article/details/gt2bpzflpgr.html

protocol Shape { func area() -> Double }
来源：http://dali.0kj1m.cn/Article/details/gt2erkagclm.html

[T31] Lua：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gt2stwagudj.html

print("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gt2mxznlqmw.html

[T32] Lua：局部变量
来源：http://dali.guowangkeji.top/Article/details/gt2fllvzihi.html

local a = 1
来源：http://dali.daria6918.cn/Article/details/gt2wcvzpgns.html

[T33] Lua：表（数组）
来源：http://dali.smart0.xyz/Article/details/gt2whdcyhtn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.redwolf501.top/Article/details/gt2suhiaqra.html

[T34] Lua：遍历表
来源：http://dali.fengsongda.top/Article/details/gt2vlfeeljl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.smart0.xyz/Article/details/gt2hxkhhsyh.html

[T35] Lua：字典表
来源：http://dali.kuanghao11.cn/Article/details/gt2fdtssmxj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.smart0.xyz/Article/details/gt2schjqgym.html

[T36] Lua：函数
来源：http://dali.fengsongda.top/Article/details/gt2wmhwdsrx.html

function add(a, b) return a + b end
来源：http://dali.0kj1m.cn/Article/details/gt2foxyifof.html

[T37] Lua：字符串拼接
来源：http://dali.zhengqikj.top/Article/details/gt2wtmedhwg.html

"a" .. "b"
来源：http://dali.birdmap.top/Article/details/gt2lcxakbjs.html

[T38] Lua：条件
来源：http://dali.zhijiandao.cn/Article/details/gt2frtqpwit.html

if x > 0 then print("正") end
来源：http://dali.zdqjudy.top/Article/details/gt2hvnvmrqq.html

[T39] Lua：模式匹配
来源：http://dali.c1oappe.top/Article/details/gt2zzjhtxfp.html

string.find(s, "%d+")
来源：http://dali.shzxlz.cn/Article/details/gt2rignnddq.html

[T40] Lua：元表
来源：http://dali.zhengqikj.top/Article/details/gt2xgjiyvlp.html

setmetatable({}, { __index = base })
来源：http://dali.yj202588.top/Article/details/gt2yhlcdpbe.html

[T41] Perl：Hello World
来源：http://dali.dianchejie.cn/Article/details/gt2ggvpmacm.html

print "Hello\n";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dvvjgkyd.html

[T42] Perl：变量类型
来源：http://dali.cqqwz.cn/Article/details/gt2onuvitws.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ppjwa.cn/Article/details/gt2lhstboct.html

[T43] Perl：字符串插值
来源：http://dali.cucudq.cn/Article/details/gt2sregbbhh.html

"值: $a"
来源：http://dali.9152youxi.cn/Article/details/gt2yhwboxka.html

[T44] Perl：条件
来源：http://dali.zycfv.cn/Article/details/gt2avbjcvgn.html

if ($a > 0) { print "正"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wrroqlrx.html

[T45] Perl：数组遍历
来源：http://dali.smart0.xyz/Article/details/gt2kwowogiy.html

for my $x (@arr) { print $x; }
来源：http://dali.birdmap.top/Article/details/gt2gmmabxjn.html

[T46] Perl：哈希操作
来源：http://dali.chenzaomai.com/Article/details/gt2foogkddk.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.guowangkeji.top/Article/details/gt2navoyoem.html

[T47] Perl：正则捕获
来源：http://dali.chenjidiqi.icu/Article/details/gt2wifvstwd.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.shzxlz.cn/Article/details/gt2hwzzipsx.html

[T48] Perl：正则替换
来源：http://dali.zdqjudy.top/Article/details/gt2zrqajfvv.html

$s =~ s/old/new/g;
来源：http://dali.sysykeji.top/Article/details/gt2ekiemcoe.html

[T49] Perl：函数
来源：http://dali.gaohongyu789.top/Article/details/gt2cyotenat.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sufxvd.cn/Article/details/gt2tevxhvvc.html

[T50] Perl：逐行读文件
来源：http://dali.ydzc1.top/Article/details/gt2yevfhkow.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yj20258888.top/Article/details/gt2fapdafoh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.chenzaomai.com/Article/details/gt2dyluxmsi.html

[T51] Scala：Hello World
来源：http://dali.redwolf501.top/Article/details/gt2sfuzkprt.html

println("Hello")
来源：http://dali.smart0.xyz/Article/details/gt2jsttrczv.html

[T52] Scala：变量
来源：http://dali.ppjwa.cn/Article/details/gt2rsadcgte.html

val a = 1;  var b = 2
来源：http://dali.hammf.cn/Article/details/gt2dpxcfqsu.html

[T53] Scala：字符串插值
来源：http://dali.aizwys.cn/Article/details/gt2jvxgoktn.html

s"值: $b"
来源：http://dali.zdqjudy.top/Article/details/gt2xfcvhjrp.html

[T54] Scala：集合映射
来源：http://dali.nwbrower.top/Article/details/gt2uslczpyo.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hywenlv.cn/Article/details/gt2nejcrddo.html

[T55] Scala：集合过滤
来源：http://dali.shuidangran.top/Article/details/gt2fqeniywm.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.cheryme.top/Article/details/gt2iwsuxywp.html

[T56] Scala：样例类
来源：http://dali.xinyue.icu/Article/details/gt2qrjzgrad.html

case class User(name: String, age: Int)
来源：http://dali.chenlongwang.top/Article/details/gt2ziadauhn.html

[T57] Scala：模式匹配
来源：http://dali.chenlongwang.top/Article/details/gt2vxdzpjre.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.dashuyun.cn/Article/details/gt2zjwpvabn.html

[T58] Scala：函数定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vykkuyec.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.jinqigufen.top/Article/details/gt2cpjaqjwk.html

[T59] Scala：循环
来源：http://dali.hnxiangtu.top/Article/details/gt2rhvvcsaq.html

for (i <- 1 to 10) println(i)
来源：http://dali.zdqjudy.top/Article/details/gt2ifbubrgn.html

[T60] Scala：折叠
来源：http://dali.zhongyouzk.top/Article/details/gt2mcxizwis.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.svipenyu.cn/Article/details/gt2revsxotz.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2jhxugueb.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zdqjudy.top/Article/details/gt2mcuzgthj.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2loocvqev.html

[U01] Py：创建虚拟环境
来源：http://dali.jinqigfzy.top/Article/details/gt2nxezmxav.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.daria6918.cn/Article/details/gt2rkrvetzf.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jinqigfzy.top/Article/details/gt2kkfxemcn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.svipenyu.cn/Article/details/gt2vltojfwf.html

[U03] Py：加载 .env 配置
来源：http://dali.xuetiantiany.cn/Article/details/gt2egccxbyg.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ejxyhdpc.html

[U04] Py：变量调试打印
来源：http://dali.jianghu66.top/Article/details/gt2hvheqjxb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.shzxlz.cn/Article/details/gt2xtwbdjkw.html


<!-- 参考信息 -->