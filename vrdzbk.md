代发 wailian999

head -c 16 /dev/urandom | base64
来源：http://dali.zhongyouzk.top/Article/details/gtstehjljx.html

[R70] 时间戳与互转
来源：http://dali.chenlongwang.top/Article/details/gtapmplvhp.html

date +%s;  date -d @1700000000
来源：http://dali.mhx1999.top/Article/details/gtugmoudaf.html

[R71] 日期格式化
来源：http://dali.9152youxi.cn/Article/details/gtmxfgdpzk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sufxvd.cn/Article/details/gtnpnotmxx.html

[R72] 等待端口就绪
来源：http://dali.xziqi.cn/Article/details/gtudwukcjy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hfpthk.cn/Article/details/gtyxxcwjjx.html

[R73] 分割大日志
来源：http://dali.wangshuangyany.cn/Article/details/gtbxfndqto.html

split -l 1000 big.log part_
来源：http://dali.gotoacloud.top/Article/details/gtrrumdvrj.html

[R74] 批量重命名
来源：http://dali.pengpengdd.cyou/Article/details/gtsuorkbar.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhengqikj.top/Article/details/gtuovftunk.html

[R75] 导出环境变量
来源：http://dali.yuxming.cn/Article/details/gtdxxzqccc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yj202588.top/Article/details/gteineqvgo.html

[R76] 使用临时文件
来源：http://dali.nanxinkj.top/Article/details/gtglwbmfie.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.fzhhl.top/Article/details/gtvhxuuhlx.html

[R77] 读取用户输入
来源：http://dali.0kj1m.cn/Article/details/gtrmnxaoxh.html

read -rp "请输入: " ans
来源：http://dali.zdqjudy.top/Article/details/gtaowpskar.html

[R78] 交互式菜单
来源：http://dali.tian-w.cn/Article/details/gthrvnphga.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jqgfzy.top/Article/details/gthujueeha.html

[R79] 解析命令行选项
来源：http://dali.cdnleiting.top/Article/details/gtcqlczqul.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sysykeji.top/Article/details/gtlnauqqpw.html

[R80] 查看脚本执行耗时
来源：http://dali.gaohongyu789.top/Article/details/gtrbmfvvlx.html

time ./run.sh
来源：http://dali.gotoacloud.top/Article/details/gtozpcfynk.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtgreppvuy.html

S. C / C++ 专题
来源：http://dali.cheryme.top/Article/details/gtwvzyftym.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtybozgiww.html

[S01] C：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtsggmpbsq.html

#include <stdio.h>
来源：http://dali.nanxuanxn.top/Article/details/gtprzfffou.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.fzhhl.top/Article/details/gtzzdrwfzc.html

[S02] C：变量与格式化输出
来源：http://dali.zhoulong.xyz/Article/details/gtfvlcehpj.html

int a = 10; printf("%d\n", a);
来源：http://dali.yuanzhike.top/Article/details/gtxphqzqsz.html

[S03] C：读入整数
来源：http://dali.jqgfzy.top/Article/details/gtassjshdo.html

int x; scanf("%d", &x);
来源：http://dali.shzxlz.cn/Article/details/gtcgqyblcn.html

[S04] C：字符串复制
来源：http://dali.ehwqpu.com/Article/details/gtawdgjkei.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shzxlz.cn/Article/details/gtgdultilf.html

[S05] C：字符串长度
来源：http://dali.sufxvd.cn/Article/details/gtespgtbae.html

strlen(s)
来源：http://dali.sweek.top/Article/details/gtwswscowu.html

[S06] C：字符串比较
来源：http://dali.gotoacloud.top/Article/details/gtqkfyyowf.html

strcmp(a, b) == 0
来源：http://dali.zhengqikj.top/Article/details/gtehtjrljt.html

[S07] C：数组遍历求和
来源：http://dali.shanyushiyangtech.top/Article/details/gtuamzoibu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.fzhhl.top/Article/details/gtdpijfiwa.html

[S08] C：动态内存分配与释放
来源：http://dali.redwolf501.top/Article/details/gtnkcgbzdu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.snrcjt.cn/Article/details/gtkfldoire.html

[S09] C：结构体定义与初始化
来源：http://dali.zhengqikj.top/Article/details/gtzedeaecv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.nanxinkj.top/Article/details/gtrjcawazb.html

[S10] C：指针与解引用
来源：http://dali.daria6918.cn/Article/details/gtuwogohux.html

int *p = &a;  *p = 5;
来源：http://dali.jinqigfzy.top/Article/details/gtkzwecntj.html

[S11] C：逐行读文件
来源：http://dali.cucudq.cn/Article/details/gtytnqvyti.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.haohaochexian.top/Article/details/gtfzlpbokj.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cucudq.cn/Article/details/gtkpdtqyzz.html

fclose(f);
来源：http://dali.sysykeji.top/Article/details/gteccvvhcx.html

[S12] C：写文件
来源：http://dali.dashuyun.cn/Article/details/gtuvuitqhb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yueranfly.top/Article/details/gtxlndbajh.html

[S13] C：宏定义
来源：http://dali.dianchejie.cn/Article/details/gtzozktomo.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.quarkkingdee.top/Article/details/gtmilkfngp.html

[S14] C：枚举
来源：http://dali.chenlongwang.top/Article/details/gtluufzcqf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yonumen.top/Article/details/gtnwagiyit.html

[S15] C：类型转换
来源：http://dali.ydzc1.top/Article/details/gtwttjnikw.html

(double) a / b
来源：http://dali.hywenlv.cn/Article/details/gtaduepkso.html

[S16] C：位操作置位
来源：http://dali.iojbl.cn/Article/details/gtipmbxvcd.html

x |= (1 << 3);
来源：http://dali.dianchejie.cn/Article/details/gtdyqnmvnn.html

[S17] C：安全拼接字符串
来源：http://dali.xuanzx.com/Article/details/gteyyfunuh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hnxiangtu.top/Article/details/gtywunbzqv.html

[S18] C：命令行参数
来源：http://dali.tanke756.top/Article/details/gtuuvwzwpv.html

int main(int argc, char **argv)
来源：http://dali.gotoacloud.top/Article/details/gtepxtxvsr.html

[S19] C：快速排序
来源：http://dali.hnxiangtu.top/Article/details/gtwwoocymb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.aibaodan.cn/Article/details/gtxlsvmrlq.html

[S20] C：二分查找
来源：http://dali.yongpay.top/Article/details/gtdwuevcng.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yj20258.top/Article/details/gtobzjyfkf.html

[S21] C：字符类别判断
来源：http://dali.hysaishi.cn/Article/details/gtquceghoa.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yvedp.cn/Article/details/gtcqpayjqu.html

[S22] C：字符串转数字
来源：http://dali.yj202588.top/Article/details/gtwhszikfh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.tian-w.cn/Article/details/gtsfzekxtu.html

[S23] C：随机数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxuivujgy.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tanke756.top/Article/details/gtuvnvavvs.html

[S24] C：获取本地时间
来源：http://dali.svipenyu.cn/Article/details/gtlwsawuho.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ydzc1.top/Article/details/gtrgcfntyk.html

[S25] C：内存拷贝
来源：http://dali.jinqigfzy.top/Article/details/gtprqyghdp.html

memcpy(dst, src, n);
来源：http://dali.tanke756.top/Article/details/gtijwxjgij.html

[S26] C：内存清零
来源：http://dali.shangyingyoupin.top/Article/details/gtnxycmlnh.html

memset(a, 0, sizeof a);
来源：http://dali.gaohongyu789.top/Article/details/gtkhfedkmj.html

[S27] C：定义常量
来源：http://dali.ydzc1.top/Article/details/gtaxlutcot.html

const double PI = 3.14159;
来源：http://dali.yj20258.top/Article/details/gtiunduptu.html

[S28] C：静态变量
来源：http://dali.xylfe.cn/Article/details/gtfhtkllno.html

static int counter = 0;
来源：http://dali.feifeiyinyue.top/Article/details/gtvsmkyuyg.html

[S29] C：变参函数
来源：http://dali.xuetiantiany.cn/Article/details/gtymymtmcw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yj20258.top/Article/details/gttsubyoxz.html

[S30] C：头文件保护
来源：http://dali.cqqwz.cn/Article/details/gtvfjwyvch.html

#ifndef X_H
来源：http://dali.vqdsnc.cn/Article/details/gtackasdcy.html

#define X_H
来源：http://dali.shzxlz.cn/Article/details/gtougyglmy.html

#endif
来源：http://dali.nwbrower.top/Article/details/gtmctfsfuw.html

[S31] C++：Hello World
来源：http://dali.cashguo.top/Article/details/gtsisvgzol.html

#include <iostream>
来源：http://dali.quarkkingdee.top/Article/details/gtejgmhknq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.fengsongda.top/Article/details/gtpvfaosse.html

[S32] C++：字符串
来源：http://dali.meibo888.top/Article/details/gtwionmhrq.html

std::string s = "hi";  s += "!";
来源：http://dali.bjfxy.top/Article/details/gtcowhlgxd.html

[S33] C++：vector 增删
来源：http://dali.aizwys.cn/Article/details/gtwxbrzmqu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.nwbrower.top/Article/details/gtuxxzxebh.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gtioqwxytq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jianghu66.top/Article/details/gtlyqrgshh.html

[S35] C++：map
来源：http://dali.9152youxi.cn/Article/details/gtzbobegkk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gtuhnqekdd.html

[S36] C++：unordered_map
来源：http://dali.pycfn.com/Article/details/gtdfsacpnf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sweek.top/Article/details/gteeupkbwx.html

[S37] C++：set
来源：http://dali.cqqwz.cn/Article/details/gtjeiuaefz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ehwqpu.com/Article/details/gtbggopbmb.html

[S38] C++：排序
来源：http://dali.redwolf501.top/Article/details/gtofleuqyl.html

std::sort(v.begin(), v.end());
来源：http://dali.wangshuangyany.cn/Article/details/gtwixpptal.html

[S39] C++：自定义比较器排序
来源：http://dali.jinqigfzy.top/Article/details/gtivfeazmm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.iojbl.cn/Article/details/gtiivxydox.html

[S40] C++：查找元素
来源：http://dali.tanke756.top/Article/details/gtkrclgjbx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ehwqpu.com/Article/details/gthlbkqmte.html

[S41] C++：类与构造函数
来源：http://dali.xziqi.cn/Article/details/gtwzvcfqdy.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hfpthk.cn/Article/details/gtheejjsfr.html

[S42] C++：继承与虚函数
来源：http://dali.xuanzx.com/Article/details/gtqqnududo.html

class B : public Base { public: void f() override {} };
来源：http://dali.nanxinkj.top/Article/details/gtdazumune.html

[S43] C++：智能指针
来源：http://dali.cucudq.cn/Article/details/gtwjyaxhiq.html

auto p = std::make_unique<int>(5);
来源：http://dali.shzxlz.cn/Article/details/gtsnxtvcky.html

[S44] C++：引用传参
来源：http://dali.aizwys.cn/Article/details/gtueftmyct.html

void inc(int &x) { ++x; }
来源：http://dali.feifeiyinyue.top/Article/details/gtdopfqyvt.html

[S45] C++：lambda
来源：http://dali.shanyushiyangtech.top/Article/details/gtkawfizgm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yvedp.cn/Article/details/gtchjxbjee.html

[S46] C++：函数模板
来源：http://dali.yvedp.cn/Article/details/gtxrqgqrko.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shuidangran.top/Article/details/gtoncughwq.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinqigfzy.top/Article/details/gtyonqhugi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.dianchejie.cn/Article/details/gtmzdfqocm.html

[S48] C++：逐行读文件
来源：http://dali.yueranfly.top/Article/details/gtspdodlio.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jyoumei.cn/Article/details/gtdhbuuvzv.html

while (std::getline(in, line)) { }
来源：http://dali.shuidangran.top/Article/details/gtdpwkgfzn.html

[S49] C++：写文件
来源：http://dali.daria6918.cn/Article/details/gtyyggrfek.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xinyue.icu/Article/details/gtxvgsdztc.html

[S50] C++：格式化数字
来源：http://dali.chenlongwang.top/Article/details/gtxbtzuibh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tian-w.cn/Article/details/gtdybvkszr.html

[S51] C++：显式类型转换
来源：http://dali.shuidangran.top/Article/details/gtwpbbcjyw.html

static_cast<double>(a) / b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaocqpdxh.html

[S52] C++：const 与 noexcept
来源：http://dali.guannengcc.top/Article/details/gtkzozxhnz.html

int size() const noexcept { return n_; }
来源：http://dali.dashuyun.cn/Article/details/gthvuhoewm.html

[S53] C++：移动语义
来源：http://dali.jianghu66.top/Article/details/gtxcvoaiez.html

std::vector<int> w = std::move(v);
来源：http://dali.yj20258888.top/Article/details/gtjtdwrrnu.html

[S54] C++：异常处理
来源：http://dali.zhiwuduotai.top/Article/details/gtcqqyqsuz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xinyue.icu/Article/details/gtxfqryobu.html

[S55] C++：结构化绑定
来源：http://dali.zhengqikj.top/Article/details/gtlsphmtjx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yj20258.top/Article/details/gtpwmgvyzi.html

[S56] C++：optional
来源：http://dali.chenlongwang.top/Article/details/gtkuhobmdr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.dashuyun.cn/Article/details/gtyorfvqbh.html

[S57] C++：编译期常量
来源：http://dali.xuetiantiany.cn/Article/details/gtdpamronh.html

constexpr int N = 10;
来源：http://dali.yanxiufei.cn/Article/details/gtvjwjwdxl.html

[S58] C++：命名空间
来源：http://dali.ivvv.top/Article/details/gtqhzrpruf.html

namespace ns { int f() { return 1; } }
来源：http://dali.chenjidiqi.icu/Article/details/gtrmmxocqx.html

[S59] C++：静态断言
来源：http://dali.shzxlz.cn/Article/details/gtvqutbxnp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.316326.xyz/Article/details/gtosphadty.html

[S60] C++：遍历并删除元素
来源：http://dali.dashuyun.cn/Article/details/gtgvkgzszh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.svipenyu.cn/Article/details/gtntonfwjb.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtcwakunui.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xziqi.cn/Article/details/gtqrddfomj.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyvpgmprf.html

[T01] Kotlin：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtjbdyfuvf.html

println("Hello")
来源：http://dali.xuanzx.com/Article/details/gtwnaujeth.html

[T02] Kotlin：变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoobaszdg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gogol.net.cn/Article/details/gtkuhpxvau.html

[T03] Kotlin：字符串模板
来源：http://dali.jiagoushi.top/Article/details/gtmawpumua.html

"值: $b"
来源：http://dali.0kj1m.cn/Article/details/gtjchqxpit.html

[T04] Kotlin：空安全
来源：http://dali.cucudq.cn/Article/details/gthqnrxarj.html

val n: String? = null;  n?.length
来源：http://dali.zycfv.cn/Article/details/gtzixxpfrc.html

[T05] Kotlin：when 表达式
来源：http://dali.haohaochexian.top/Article/details/gtktpwcyrv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhiwuduotai.top/Article/details/gtowzbzcyj.html

[T06] Kotlin：集合映射
来源：http://dali.chenlongwang.top/Article/details/gtatakjbll.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xylfe.cn/Article/details/gtiooifciz.html

[T07] Kotlin：集合过滤
来源：http://dali.tian-w.cn/Article/details/gtirhegfkx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.tianlin.xyz/Article/details/gtbmrufnrt.html

[T08] Kotlin：数据类
来源：http://dali.dashuyun.cn/Article/details/gtcvnvcakg.html

data class User(val name: String, val age: Int)
来源：http://dali.xinyue.icu/Article/details/gtmjcugklg.html

[T09] Kotlin：扩展函数
来源：http://dali.bjfxy.top/Article/details/gtkqmzbqdc.html

fun String.exclaim() = this + "!"
来源：http://dali.hfpthk.cn/Article/details/gtxoczvehc.html

[T10] Kotlin：默认参数
来源：http://dali.nanxuanxn.top/Article/details/gtlenzctok.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.smart0.xyz/Article/details/gtrywjciid.html

[T11] Kotlin：协程
来源：http://dali.xuetiantiany.cn/Article/details/gtnekgzmvq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.pengpengdd.cyou/Article/details/gtrgetneur.html

[T12] Kotlin：解构声明
来源：http://dali.redwolf501.top/Article/details/gtxeozykmq.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhixingplan.top/Article/details/gtcivjkyhi.html

[T13] Kotlin：只读 Map
来源：http://dali.gzhubu.top/Article/details/gtmpcmvqoo.html

val m = mapOf("a" to 1)
来源：http://dali.tanke756.top/Article/details/gtvfbcdoqa.html

[T14] Kotlin：循环
来源：http://dali.jqgfzy.top/Article/details/gtqkxykudv.html

for (i in 1..10) println(i)
来源：http://dali.jianghu66.top/Article/details/gtpkadpbwd.html

[T15] Kotlin：接口
来源：http://dali.kuanghao11.cn/Article/details/gtluhapmpa.html

interface Shape { fun area(): Double }
来源：http://dali.redwolf501.top/Article/details/gtlhcsncru.html

[T16] Swift：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtylwtzslu.html

print("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gtabiuzuzv.html

[T17] Swift：变量与常量
来源：http://dali.yongpay.top/Article/details/gtfwldzfpm.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gtudsgnnbo.html

[T18] Swift：字符串插值
来源：http://dali.birdmap.top/Article/details/gttmtiqzbi.html

"值: \(b)"
来源：http://dali.quarkkingdee.top/Article/details/gtqhqxycel.html

[T19] Swift：可选绑定
来源：http://dali.ivvv.top/Article/details/gthdxehkfy.html

if let n = opt { print(n) }
来源：http://dali.dashuyun.cn/Article/details/gtgcbjgcdm.html

[T20] Swift：数组操作
来源：http://dali.meibo888.top/Article/details/gtosnannaq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtypwqrpcy.html

[T21] Swift：遍历
来源：http://dali.yj20258.top/Article/details/gtizrwhrlj.html

for x in a { print(x) }
来源：http://dali.tianlin.xyz/Article/details/gtgqqwpyct.html

[T22] Swift：字典
来源：http://dali.wangdashe.top/Article/details/gtsvxrvqiq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jinqigufen.top/Article/details/gtdrnxefjm.html

[T23] Swift：函数
来源：http://dali.sysykeji.top/Article/details/gtobfdyogo.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.fzhhl.top/Article/details/gtmtwdhhnr.html

[T24] Swift：闭包
来源：http://dali.316326.xyz/Article/details/gtxiklxgdt.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gtqyexcfpa.html

[T25] Swift：结构体
来源：http://dali.chenjidiqi.icu/Article/details/gttbkusqrb.html

struct P { var x: Int }
来源：http://dali.9152youxi.cn/Article/details/gtumxgbogq.html

[T26] Swift：类与重写
来源：http://dali.wangshuangyany.cn/Article/details/gtqyfwlbla.html

class A: Base { override func f() {} }
来源：http://dali.cheryme.top/Article/details/gtylpydtrs.html

[T27] Swift：错误处理
来源：http://dali.zhiwuduotai.top/Article/details/gtzzrqpjdb.html

do { try f() } catch { print(error) }
来源：http://dali.daria6918.cn/Article/details/gtuuutsbew.html

[T28] Swift：枚举
来源：http://dali.mhx1999.top/Article/details/gtxvdchiec.html

enum Color { case red, green }
来源：http://dali.jinghuilouyu.cn/Article/details/gtegbxlaya.html

[T29] Swift：guard 提前返回
来源：http://dali.yueranfly.top/Article/details/gtmvlljtdt.html

guard let x = opt else { return }
来源：http://dali.dianchejie.cn/Article/details/gtrmsuulyb.html

[T30] Swift：协议
来源：http://dali.zhixingplan.top/Article/details/gtjaitmzxe.html

protocol Shape { func area() -> Double }
来源：http://dali.aizwys.cn/Article/details/gtlzpzppkx.html

[T31] Lua：Hello World
来源：http://dali.pycfn.com/Article/details/gtqbgtgtwn.html

print("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gtwzrzbnmw.html

[T32] Lua：局部变量
来源：http://dali.zhiwuduotai.top/Article/details/gtzisvuzwu.html

local a = 1
来源：http://dali.daria6918.cn/Article/details/gttuirxxrs.html

[T33] Lua：表（数组）
来源：http://dali.ybcxt.top/Article/details/gtoiccgtvb.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cdnleiting.top/Article/details/gtjnwhsnav.html

[T34] Lua：遍历表
来源：http://dali.xylfe.cn/Article/details/gtrwugjwat.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.gzhubu.top/Article/details/gtcjvywawc.html

[T35] Lua：字典表
来源：http://dali.smart0.xyz/Article/details/gtukndmani.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrdihhdei.html

[T36] Lua：函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlymhmiuw.html

function add(a, b) return a + b end
来源：http://dali.yonumen.top/Article/details/gtrhjjgkjm.html

[T37] Lua：字符串拼接
来源：http://dali.birdmap.top/Article/details/gtfrbkmuve.html

"a" .. "b"
来源：http://dali.redwolf501.top/Article/details/gtdoovqtwm.html

[T38] Lua：条件
来源：http://dali.redwolf501.top/Article/details/gtxbrjcozu.html

if x > 0 then print("正") end
来源：http://dali.yangfankeji.com/Article/details/gtgubhqjox.html

[T39] Lua：模式匹配
来源：http://dali.yueranfly.top/Article/details/gtcqvfrmbp.html

string.find(s, "%d+")
来源：http://dali.jqgfzy.top/Article/details/gtdbxfuevn.html

[T40] Lua：元表
来源：http://dali.fzhhl.top/Article/details/gtpmpmrwvh.html

setmetatable({}, { __index = base })
来源：http://dali.fzhhl.top/Article/details/gtgoaqvfzh.html

[T41] Perl：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtqyzhawej.html

print "Hello\n";
来源：http://dali.tianlin.xyz/Article/details/gtaonnazph.html

[T42] Perl：变量类型
来源：http://dali.gogol.net.cn/Article/details/gtedahbort.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.nanxinkj.top/Article/details/gtowyvsmny.html

[T43] Perl：字符串插值
来源：http://dali.gaohongyu789.top/Article/details/gtjgwvtspm.html

"值: $a"
来源：http://dali.shuidangran.top/Article/details/gtgwtmuxct.html

[T44] Perl：条件
来源：http://dali.jqgfzy.top/Article/details/gtuikbcdbo.html

if ($a > 0) { print "正"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtxbxdwvcu.html

[T45] Perl：数组遍历
来源：http://dali.nanxuanxn.top/Article/details/gtkybomgca.html

for my $x (@arr) { print $x; }
来源：http://dali.dianchejie.cn/Article/details/gtdgnfitso.html

[T46] Perl：哈希操作
来源：http://dali.meibo888.top/Article/details/gtpigtctta.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gtkyebopix.html

[T47] Perl：正则捕获
来源：http://dali.yongpay.top/Article/details/gtplerdtqy.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.shuidangran.top/Article/details/gtiwibifkk.html

[T48] Perl：正则替换
来源：http://dali.yj202588.top/Article/details/gtabpoetqt.html

$s =~ s/old/new/g;
来源：http://dali.birdmap.top/Article/details/gtpgmunejz.html

[T49] Perl：函数
来源：http://dali.redwolf501.top/Article/details/gtqixhzyky.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.cucudq.cn/Article/details/gttbifmuvq.html

[T50] Perl：逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gtratyojbf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.nwbrower.top/Article/details/gthqpzuxmo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xylfe.cn/Article/details/gtjazkjhvw.html

[T51] Scala：Hello World
来源：http://dali.yj20258888.top/Article/details/gtdlhpgxru.html

println("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gtpxhpaivu.html

[T52] Scala：变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtycyezzjt.html

val a = 1;  var b = 2
来源：http://dali.ppjwa.cn/Article/details/gtgqhdtstj.html

[T53] Scala：字符串插值
来源：http://dali.gaohongyu789.top/Article/details/gtridtkrgd.html

s"值: $b"
来源：http://dali.jqgufenzy.top/Article/details/gtnvxwgljt.html

[T54] Scala：集合映射
来源：http://dali.xylfe.cn/Article/details/gthyvdzysb.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yueranfly.top/Article/details/gttgqiikcu.html

[T55] Scala：集合过滤
来源：http://dali.yj20258.top/Article/details/gtlnhvlaqg.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ivvv.top/Article/details/gtamdygfvk.html

[T56] Scala：样例类
来源：http://dali.xylfe.cn/Article/details/gtablxcpso.html

case class User(name: String, age: Int)
来源：http://dali.gzhubu.top/Article/details/gtjwpqvrlf.html

[T57] Scala：模式匹配
来源：http://dali.xziqi.cn/Article/details/gtktybaqqm.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yuxming.cn/Article/details/gtdflxcccg.html

[T58] Scala：函数定义
来源：http://dali.shangyingyoupin.top/Article/details/gtjxyzlwky.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.aizwys.cn/Article/details/gtarztagzl.html

[T59] Scala：循环
来源：http://dali.nanxuanxn.top/Article/details/gthmtdbamg.html

for (i <- 1 to 10) println(i)
来源：http://dali.jinqigfzy.top/Article/details/gtvstasctk.html

[T60] Scala：折叠
来源：http://dali.jinqigufen.top/Article/details/gtbpztgwjn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiaryjzge.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtermvzkht.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.shangyingyoupin.top/Article/details/gtqrhbvkjt.html

================================================================================
来源：http://dali.sweek.top/Article/details/gteoinwyfe.html

[U01] Py：创建虚拟环境
来源：http://dali.ywan-chungtsiang.top/Article/details/gtifmwqihv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.yongpay.top/Article/details/gtueaopbia.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cucudq.cn/Article/details/gtkxipbgka.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.xuanzx.com/Article/details/gtaammpflw.html

[U03] Py：加载 .env 配置
来源：http://dali.haohaochexian.top/Article/details/gtzjcjoyvz.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.smart0.xyz/Article/details/gtjxiuwbpm.html

[U04] Py：变量调试打印
来源：http://dali.hfpthk.cn/Article/details/gtwesgomja.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.0kj1m.cn/Article/details/gtfwpkcqmd.html

[U05] Py：列表去重且保序
来源：http://dali.c1oappe.top/Article/details/gttbcmbgjd.html

list(dict.fromkeys(arr))
来源：http://dali.cdnleiting.top/Article/details/gtvurhrmls.html

[U06] Py：合并两个字典
来源：http://dali.shuidangran.top/Article/details/gtedvvkfos.html

{**a, **b}
来源：http://dali.tanke756.top/Article/details/gtdjpjzzey.html

[U07] Py：反转字典键值
来源：http://dali.shzxlz.cn/Article/details/gtwvmvflfe.html

{v: k for k, v in d.items()}
来源：http://dali.nanxuanxn.top/Article/details/gtiqdtwfmv.html

[U08] Py：展平二维列表
来源：http://dali.aizwys.cn/Article/details/gtkbqytush.html

[y for x in nested for y in x]
来源：http://dali.xylfe.cn/Article/details/gtaecooski.html

[U09] Py：字典取最大值的键
来源：http://dali.hongshengwenyu.top/Article/details/gtcblnossj.html

max(d, key=d.get)
来源：http://dali.jianghu66.top/Article/details/gtecnxcqkx.html

[U10] Py：按值排序字典
来源：http://dali.ydzc1.top/Article/details/gtfityqkqv.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.zycfv.cn/Article/details/gtakkwwwdl.html


<!-- 参考信息 -->