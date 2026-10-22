代发 wailian999

split -l 1000 big.log part_
来源：http://dali.ybcxt.top/Article/details/gtlbnxdbyj.html

[R74] 批量重命名
来源：http://dali.jqgufenzy.top/Article/details/gtbocsjcdo.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yuxming.cn/Article/details/gtwnpnmtjq.html

[R75] 导出环境变量
来源：http://dali.xinyue.icu/Article/details/gtnmfdioia.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hongshengwenyu.top/Article/details/gtsabviskh.html

[R76] 使用临时文件
来源：http://dali.ehwqpu.com/Article/details/gtddichyyi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhoulong.xyz/Article/details/gtppptawis.html

[R77] 读取用户输入
来源：http://dali.zhixingplan.top/Article/details/gtmnuvpcxs.html

read -rp "请输入: " ans
来源：http://dali.yangfankeji.com/Article/details/gthmbllaiq.html

[R78] 交互式菜单
来源：http://dali.xinyue.icu/Article/details/gtkoaiyfmj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhiwuduotai.top/Article/details/gtnkoloaxw.html

[R79] 解析命令行选项
来源：http://dali.yongpay.top/Article/details/gtdomunckx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ivvv.top/Article/details/gttazxqvfy.html

[R80] 查看脚本执行耗时
来源：http://dali.bjfxy.top/Article/details/gtokohowum.html

time ./run.sh
来源：http://dali.quarkkingdee.top/Article/details/gtjfvrsvuh.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtpvpkbtup.html

S. C / C++ 专题
来源：http://dali.pycfn.com/Article/details/gtwscsschj.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtwkemkxiy.html

[S01] C：Hello World
来源：http://dali.fzhhl.top/Article/details/gtqzochgyt.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gtuzwudfae.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jinqigufen.top/Article/details/gtorwiamme.html

[S02] C：变量与格式化输出
来源：http://dali.smart0.xyz/Article/details/gtpalpymxe.html

int a = 10; printf("%d\n", a);
来源：http://dali.yonumen.top/Article/details/gtkxzmahqe.html

[S03] C：读入整数
来源：http://dali.guowangkeji.top/Article/details/gtwkewaypz.html

int x; scanf("%d", &x);
来源：http://dali.ivvv.top/Article/details/gtxgalitco.html

[S04] C：字符串复制
来源：http://dali.yonumen.top/Article/details/gtypuijhhn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cashguo.top/Article/details/gtuknfnizb.html

[S05] C：字符串长度
来源：http://dali.yj20258.top/Article/details/gtowmhfwkf.html

strlen(s)
来源：http://dali.kuanghao11.cn/Article/details/gtmpvyslms.html

[S06] C：字符串比较
来源：http://dali.hnqzz.top/Article/details/gtiquambsp.html

strcmp(a, b) == 0
来源：http://dali.gogol.net.cn/Article/details/gtojzvrwfi.html

[S07] C：数组遍历求和
来源：http://dali.sufxvd.cn/Article/details/gtboaflecu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xinyue.icu/Article/details/gtjetorjwp.html

[S08] C：动态内存分配与释放
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqyzxpewx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ehwqpu.com/Article/details/gtchtataxy.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gthoxntnmx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ydzc1.top/Article/details/gtekxqdwov.html

[S10] C：指针与解引用
来源：http://dali.zycfv.cn/Article/details/gtmovhemaa.html

int *p = &a;  *p = 5;
来源：http://dali.cheryme.top/Article/details/gtkkhabcyu.html

[S11] C：逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gtgkcofibw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jqgufenzy.top/Article/details/gthayjjmci.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gogol.net.cn/Article/details/gtbuffjena.html

fclose(f);
来源：http://dali.redwolf501.top/Article/details/gttztdmglw.html

[S12] C：写文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqpdhpkvl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.tianlin.xyz/Article/details/gtghhdoxsg.html

[S13] C：宏定义
来源：http://dali.zhoulong.xyz/Article/details/gtvwbctfps.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.quarkkingdee.top/Article/details/gtvibxpolp.html

[S14] C：枚举
来源：http://dali.jinqigufen.top/Article/details/gtmxdchyxl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ehwqpu.com/Article/details/gtnebgqfox.html

[S15] C：类型转换
来源：http://dali.hywenlv.cn/Article/details/gtrksddhwh.html

(double) a / b
来源：http://dali.ehwqpu.com/Article/details/gtgajkyhku.html

[S16] C：位操作置位
来源：http://dali.nanxinkj.top/Article/details/gtwiidamue.html

x |= (1 << 3);
来源：http://dali.hnqzz.top/Article/details/gtssaalzrw.html

[S17] C：安全拼接字符串
来源：http://dali.hysaishi.cn/Article/details/gtlevyknzn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhengqikj.top/Article/details/gtefthnedd.html

[S18] C：命令行参数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmbzhfnkd.html

int main(int argc, char **argv)
来源：http://dali.hywenlv.cn/Article/details/gtfuieahrf.html

[S19] C：快速排序
来源：http://dali.kuanghao11.cn/Article/details/gtirexlynp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.dianchejie.cn/Article/details/gtwgcjrgwu.html

[S20] C：二分查找
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzyujdkhp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sysykeji.top/Article/details/gtzystwlyp.html

[S21] C：字符类别判断
来源：http://dali.hnqzz.top/Article/details/gtelrzwthb.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.0kj1m.cn/Article/details/gtpwwxowhp.html

[S22] C：字符串转数字
来源：http://dali.ybcxt.top/Article/details/gtgzfpuhda.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jiagoushi.top/Article/details/gtosrkialh.html

[S23] C：随机数
来源：http://dali.cucudq.cn/Article/details/gtigojbcix.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sysykeji.top/Article/details/gtdjgbyzmw.html

[S24] C：获取本地时间
来源：http://dali.gaohongyu789.top/Article/details/gtkyhbwhok.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj20258888.top/Article/details/gtowwsorbx.html

[S25] C：内存拷贝
来源：http://dali.shzxlz.cn/Article/details/gtgeuqeotq.html

memcpy(dst, src, n);
来源：http://dali.andypj.xyz/Article/details/gtvgfangnh.html

[S26] C：内存清零
来源：http://dali.feifeiyinyue.top/Article/details/gtqvqncijj.html

memset(a, 0, sizeof a);
来源：http://dali.shanyushiyangkeji.top/Article/details/gttjxzchvw.html

[S27] C：定义常量
来源：http://dali.yj20258888.top/Article/details/gtzuogtcui.html

const double PI = 3.14159;
来源：http://dali.hongshengwenyu.top/Article/details/gtwjromwht.html

[S28] C：静态变量
来源：http://dali.shangyingyoupin.top/Article/details/gtroqywcfk.html

static int counter = 0;
来源：http://dali.yanxiufei.cn/Article/details/gtiskxvzie.html

[S29] C：变参函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrvmjudra.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhengqikj.top/Article/details/gtxxmhlqwl.html

[S30] C：头文件保护
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoltzhwyk.html

#ifndef X_H
来源：http://dali.zdqjudy.top/Article/details/gtuektlmid.html

#define X_H
来源：http://dali.jqgfzy.top/Article/details/gtygbsndds.html

#endif
来源：http://dali.zhongyouzk.top/Article/details/gtaiekbprs.html

[S31] C++：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtbremhwvo.html

#include <iostream>
来源：http://dali.zhengqikj.top/Article/details/gtkgobfnvn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.pycfn.com/Article/details/gtrdekbhrt.html

[S32] C++：字符串
来源：http://dali.svipenyu.cn/Article/details/gtmkwuylzn.html

std::string s = "hi";  s += "!";
来源：http://dali.hnqzz.top/Article/details/gtpfvtzext.html

[S33] C++：vector 增删
来源：http://dali.tianlin.xyz/Article/details/gtlmssihfa.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cashguo.top/Article/details/gtuexnaimg.html

[S34] C++：遍历 vector
来源：http://dali.cashguo.top/Article/details/gtyyowbfqe.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hnxiangtu.top/Article/details/gtscrpftke.html

[S35] C++：map
来源：http://dali.tanke756.top/Article/details/gtdksjhbyd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xinyue.icu/Article/details/gthtzpozkf.html

[S36] C++：unordered_map
来源：http://dali.xziqi.cn/Article/details/gtaybifgjx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.vqdsnc.cn/Article/details/gttnneasoq.html

[S37] C++：set
来源：http://dali.chenlongwang.top/Article/details/gthjbwpwcu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.daxiang520.top/Article/details/gtbnkznwei.html

[S38] C++：排序
来源：http://dali.gogol.net.cn/Article/details/gtkfndwsww.html

std::sort(v.begin(), v.end());
来源：http://dali.hongshengwenyu.top/Article/details/gtwkegdwny.html

[S39] C++：自定义比较器排序
来源：http://dali.zhijiandao.cn/Article/details/gtsryggjjz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yangfankeji.com/Article/details/gtqfvobuhf.html

[S40] C++：查找元素
来源：http://dali.jinqigfzy.top/Article/details/gtnafddeta.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xuanzx.com/Article/details/gteeybzmdt.html

[S41] C++：类与构造函数
来源：http://dali.hywenlv.cn/Article/details/gttaeazocr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yj20258888.top/Article/details/gtnjppxjqc.html

[S42] C++：继承与虚函数
来源：http://dali.zdqjudy.top/Article/details/gtyfutchyx.html

class B : public Base { public: void f() override {} };
来源：http://dali.andypj.xyz/Article/details/gtutvtcfpp.html

[S43] C++：智能指针
来源：http://dali.xuanzx.com/Article/details/gthjbdgugs.html

auto p = std::make_unique<int>(5);
来源：http://dali.sxryk.cn/Article/details/gtbaczcyhn.html

[S44] C++：引用传参
来源：http://dali.aizwys.cn/Article/details/gtrgfbvhrx.html

void inc(int &x) { ++x; }
来源：http://dali.guowangkeji.top/Article/details/gtinwhhrfd.html

[S45] C++：lambda
来源：http://dali.yanxiufei.cn/Article/details/gtobjrufyp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.iojbl.cn/Article/details/gtyjrkdszd.html

[S46] C++：函数模板
来源：http://dali.316326.xyz/Article/details/gtvuvouqch.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yj20258888.top/Article/details/gtluaeejyo.html

[S47] C++：结构化绑定遍历
来源：http://dali.wangshuangyany.cn/Article/details/gtcgesbiqr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cdnleiting.top/Article/details/gtjtskktjb.html

[S48] C++：逐行读文件
来源：http://dali.yonumen.top/Article/details/gtpbyjjhaw.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zdqjudy.top/Article/details/gtenqhiqtu.html

while (std::getline(in, line)) { }
来源：http://dali.ppjwa.cn/Article/details/gtxlsefwaz.html

[S49] C++：写文件
来源：http://dali.ehwqpu.com/Article/details/gtmumxsanp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cheryme.top/Article/details/gtraoqiont.html

[S50] C++：格式化数字
来源：http://dali.xuetiantiany.cn/Article/details/gtievgdfri.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.birdmap.top/Article/details/gtgsefhecq.html

[S51] C++：显式类型转换
来源：http://dali.9152youxi.cn/Article/details/gtwdhzuoup.html

static_cast<double>(a) / b
来源：http://dali.birdmap.top/Article/details/gtczunnsln.html

[S52] C++：const 与 noexcept
来源：http://dali.yanxiufei.cn/Article/details/gtiziizzyz.html

int size() const noexcept { return n_; }
来源：http://dali.zycfv.cn/Article/details/gtocrxliaq.html

[S53] C++：移动语义
来源：http://dali.c1oappe.top/Article/details/gtjlltxmaq.html

std::vector<int> w = std::move(v);
来源：http://dali.cdnleiting.top/Article/details/gtmxeywrgd.html

[S54] C++：异常处理
来源：http://dali.hnqzz.top/Article/details/gtexkpkfqg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.nanxuanxn.top/Article/details/gtpwkxuhnt.html

[S55] C++：结构化绑定
来源：http://dali.yanxiufei.cn/Article/details/gtarwttwni.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yuanzhike.top/Article/details/gttpmwduaj.html

[S56] C++：optional
来源：http://dali.feifeiyinyue.top/Article/details/gtmpiuwdrt.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.gaohongyu789.top/Article/details/gtjaqcpeli.html

[S57] C++：编译期常量
来源：http://dali.jinqigufen.top/Article/details/gtqkcmlxwk.html

constexpr int N = 10;
来源：http://dali.zhengqikj.top/Article/details/gtqkbemyoj.html

[S58] C++：命名空间
来源：http://dali.cdnleiting.top/Article/details/gtyhbykhrc.html

namespace ns { int f() { return 1; } }
来源：http://dali.wangshuangyany.cn/Article/details/gtqlgowoka.html

[S59] C++：静态断言
来源：http://dali.redwolf501.top/Article/details/gteqcfmzwt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.chenzaomai.com/Article/details/gtxsbminif.html

[S60] C++：遍历并删除元素
来源：http://dali.dashuyun.cn/Article/details/gtfanghmio.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.wangdashe.top/Article/details/gtpyhmpilh.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtahprqbcp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xylfe.cn/Article/details/gtjgwkrtqf.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtoqihnkmt.html

[T01] Kotlin：Hello World
来源：http://dali.zycfv.cn/Article/details/gteimlxxar.html

println("Hello")
来源：http://dali.daxiang520.top/Article/details/gtnqdkvztf.html

[T02] Kotlin：变量
来源：http://dali.tanke756.top/Article/details/gtpxizkvzy.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.dashuyun.cn/Article/details/gtbufbkxoc.html

[T03] Kotlin：字符串模板
来源：http://dali.shanyushiyangtech.top/Article/details/gtzjsnwxes.html

"值: $b"
来源：http://dali.9152youxi.cn/Article/details/gtxeujbfwz.html

[T04] Kotlin：空安全
来源：http://dali.nanxinkj.top/Article/details/gtsldblqef.html

val n: String? = null;  n?.length
来源：http://dali.cqqwz.cn/Article/details/gtkqihzfil.html

[T05] Kotlin：when 表达式
来源：http://dali.gzhubu.top/Article/details/gtalhoatrr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gogol.net.cn/Article/details/gttkplcbgs.html

[T06] Kotlin：集合映射
来源：http://dali.smart0.xyz/Article/details/gtbvsuniye.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenlongwang.top/Article/details/gtkaysagyj.html

[T07] Kotlin：集合过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtstlycudx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ppjwa.cn/Article/details/gtgpkfwmwn.html

[T08] Kotlin：数据类
来源：http://dali.yuxming.cn/Article/details/gtiehobpdy.html

data class User(val name: String, val age: Int)
来源：http://dali.tian-w.cn/Article/details/gthilrqwvl.html

[T09] Kotlin：扩展函数
来源：http://dali.chenjidiqi.icu/Article/details/gtdrbzcudp.html

fun String.exclaim() = this + "!"
来源：http://dali.yvedp.cn/Article/details/gtnkvzorou.html

[T10] Kotlin：默认参数
来源：http://dali.yj202588.top/Article/details/gtsbxfdvep.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.tianlin.xyz/Article/details/gtfsgyqmts.html

[T11] Kotlin：协程
来源：http://dali.chenlongwang.top/Article/details/gtacmxdgqh.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.pengpengdd.cyou/Article/details/gtyuquzfoa.html

[T12] Kotlin：解构声明
来源：http://dali.9152youxi.cn/Article/details/gthcpqeybn.html

val (a, b) = Pair(1, 2)
来源：http://dali.fengsongda.top/Article/details/gtssehofoe.html

[T13] Kotlin：只读 Map
来源：http://dali.xinyue.icu/Article/details/gtxxprhvmh.html

val m = mapOf("a" to 1)
来源：http://dali.smart0.xyz/Article/details/gtphneqssm.html

[T14] Kotlin：循环
来源：http://dali.jqgfzy.top/Article/details/gtjfdfprbo.html

for (i in 1..10) println(i)
来源：http://dali.quarkkingdee.top/Article/details/gttamqlxow.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gtjtrubtcx.html

interface Shape { fun area(): Double }
来源：http://dali.aizwys.cn/Article/details/gtfpdsljxt.html

[T16] Swift：Hello World
来源：http://dali.sxryk.cn/Article/details/gtrloxkmki.html

print("Hello")
来源：http://dali.hammf.cn/Article/details/gtaeivhjlb.html

[T17] Swift：变量与常量
来源：http://dali.zhixingplan.top/Article/details/gtkzenvgyt.html

var a = 1;  let b = 2
来源：http://dali.nanxuanxn.top/Article/details/gthkyqwugz.html

[T18] Swift：字符串插值
来源：http://dali.pycfn.com/Article/details/gtddifynnf.html

"值: \(b)"
来源：http://dali.fengsongda.top/Article/details/gtapukgtmh.html

[T19] Swift：可选绑定
来源：http://dali.wangshuangyany.cn/Article/details/gtjzhfflea.html

if let n = opt { print(n) }
来源：http://dali.shuidangran.top/Article/details/gtetwomhkn.html

[T20] Swift：数组操作
来源：http://dali.havefunace.top/Article/details/gtdhqvcxlc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shangyingyoupin.top/Article/details/gtlpnvvwbz.html

[T21] Swift：遍历
来源：http://dali.xylfe.cn/Article/details/gtqwpmjdth.html

for x in a { print(x) }
来源：http://dali.redwolf501.top/Article/details/gtigrjvmyc.html

[T22] Swift：字典
来源：http://dali.havefunace.top/Article/details/gtyxjjbwij.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jiagoushi.top/Article/details/gtvlicqtev.html

[T23] Swift：函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gteswfiqku.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xuetiantiany.cn/Article/details/gtikysjbnt.html

[T24] Swift：闭包
来源：http://dali.shzxlz.cn/Article/details/gtxkhldaqh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.9152youxi.cn/Article/details/gtaqxofjps.html

[T25] Swift：结构体
来源：http://dali.yueranfly.top/Article/details/gtgybnzmsc.html

struct P { var x: Int }
来源：http://dali.zhongyouzk.top/Article/details/gtiilwrwbl.html

[T26] Swift：类与重写
来源：http://dali.birdmap.top/Article/details/gtbvhljcwz.html

class A: Base { override func f() {} }
来源：http://dali.bjfxy.top/Article/details/gtlmmioyqa.html

[T27] Swift：错误处理
来源：http://dali.xziqi.cn/Article/details/gttqlxyifh.html

do { try f() } catch { print(error) }
来源：http://dali.zhiwuduotai.top/Article/details/gtzwqpfdcn.html

[T28] Swift：枚举
来源：http://dali.yanxiufei.cn/Article/details/gtogrxzbud.html

enum Color { case red, green }
来源：http://dali.jyoumei.cn/Article/details/gtyvaspjgk.html

[T29] Swift：guard 提前返回
来源：http://dali.aizwys.cn/Article/details/gtsrjrbdzv.html

guard let x = opt else { return }
来源：http://dali.yuanzhike.top/Article/details/gtnnvtngvc.html

[T30] Swift：协议
来源：http://dali.jlsjyb.cn/Article/details/gtprkcjcji.html

protocol Shape { func area() -> Double }
来源：http://dali.tanke756.top/Article/details/gtvgzxhxdn.html

[T31] Lua：Hello World
来源：http://dali.ivvv.top/Article/details/gttrspnvtf.html

print("Hello")
来源：http://dali.havefunace.top/Article/details/gttukoikpm.html

[T32] Lua：局部变量
来源：http://dali.fengsongda.top/Article/details/gtphwygpsl.html

local a = 1
来源：http://dali.xylfe.cn/Article/details/gtwvdtgksd.html

[T33] Lua：表（数组）
来源：http://dali.ydzc1.top/Article/details/gtqejtyuhs.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbxoyemrs.html

[T34] Lua：遍历表
来源：http://dali.hywenlv.cn/Article/details/gtspxajmmr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zdqjudy.top/Article/details/gtdguicdhl.html

[T35] Lua：字典表
来源：http://dali.guowangkeji.top/Article/details/gtohroytcp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hammf.cn/Article/details/gtmekosxfu.html

[T36] Lua：函数
来源：http://dali.ybcxt.top/Article/details/gtdmidfrva.html

function add(a, b) return a + b end
来源：http://dali.guowangkeji.top/Article/details/gtdapihois.html

[T37] Lua：字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gtkoburrri.html

"a" .. "b"
来源：http://dali.jiagoushi.top/Article/details/gtzoenvpkt.html

[T38] Lua：条件
来源：http://dali.gaohongyu789.top/Article/details/gtseqitidm.html

if x > 0 then print("正") end
来源：http://dali.yuxming.cn/Article/details/gtkhxscind.html

[T39] Lua：模式匹配
来源：http://dali.jyoumei.cn/Article/details/gtptwryixd.html

string.find(s, "%d+")
来源：http://dali.yj20258.top/Article/details/gtoohzsqpt.html

[T40] Lua：元表
来源：http://dali.meibo888.top/Article/details/gtaxjldpez.html

setmetatable({}, { __index = base })
来源：http://dali.xziqi.cn/Article/details/gtkysijrhy.html

[T41] Perl：Hello World
来源：http://dali.yueranfly.top/Article/details/gtuzrhycvs.html

print "Hello\n";
来源：http://dali.cashguo.top/Article/details/gtgqfgsdbl.html

[T42] Perl：变量类型
来源：http://dali.ybcxt.top/Article/details/gtcjlcjkyc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xuanzx.com/Article/details/gtubynzlbh.html

[T43] Perl：字符串插值
来源：http://dali.hammf.cn/Article/details/gtweqdxrtj.html

"值: $a"
来源：http://dali.ehwqpu.com/Article/details/gtembkfldg.html

[T44] Perl：条件
来源：http://dali.sweek.top/Article/details/gtepbfpiyz.html

if ($a > 0) { print "正"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiepcuzqw.html

[T45] Perl：数组遍历
来源：http://dali.jqgfzy.top/Article/details/gtaxzzxuib.html

for my $x (@arr) { print $x; }
来源：http://dali.meibo888.top/Article/details/gtpamqqdem.html

[T46] Perl：哈希操作
来源：http://dali.hongshengwenyu.top/Article/details/gthtbgtrrd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xinyue.icu/Article/details/gtxrohlmqi.html

[T47] Perl：正则捕获
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkylnkkop.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.gaohongyu789.top/Article/details/gtfkjdrnyq.html

[T48] Perl：正则替换
来源：http://dali.xziqi.cn/Article/details/gtwanlabwh.html

$s =~ s/old/new/g;
来源：http://dali.nanxinkj.top/Article/details/gtpworpfcg.html

[T49] Perl：函数
来源：http://dali.xuanzx.com/Article/details/gtjdveegod.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.nanxinkj.top/Article/details/gtvmogqjug.html

[T50] Perl：逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gtsjjvormd.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yongpay.top/Article/details/gtprsrrocx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.shzxlz.cn/Article/details/gtukvaxufe.html

[T51] Scala：Hello World
来源：http://dali.chenzaomai.com/Article/details/gtpadtixyy.html

println("Hello")
来源：http://dali.yueranfly.top/Article/details/gteilkahci.html

[T52] Scala：变量
来源：http://dali.dashuyun.cn/Article/details/gtqymfzkzn.html

val a = 1;  var b = 2
来源：http://dali.ydzc1.top/Article/details/gtxskpesqq.html

[T53] Scala：字符串插值
来源：http://dali.redwolf501.top/Article/details/gtftjhpbmo.html

s"值: $b"
来源：http://dali.ivvv.top/Article/details/gtszfjbxdp.html

[T54] Scala：集合映射
来源：http://dali.tanke756.top/Article/details/gtqihrhbju.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbniclete.html

[T55] Scala：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gtawhyvrcn.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.daria6918.cn/Article/details/gtgceuerqd.html

[T56] Scala：样例类
来源：http://dali.jinqigfzy.top/Article/details/gtjmaloioj.html

case class User(name: String, age: Int)
来源：http://dali.hysaishi.cn/Article/details/gtfydlhmak.html

[T57] Scala：模式匹配
来源：http://dali.jlsjyb.cn/Article/details/gtvucertah.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xziqi.cn/Article/details/gtbwomgjgn.html

[T58] Scala：函数定义
来源：http://dali.gzhubu.top/Article/details/gtjljikrtp.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.chenlongwang.top/Article/details/gtjcsdgfjp.html

[T59] Scala：循环
来源：http://dali.gaohongyu789.top/Article/details/gtwhjllakk.html

for (i <- 1 to 10) println(i)
来源：http://dali.wangshuangyany.cn/Article/details/gtyyuvfajx.html

[T60] Scala：折叠
来源：http://dali.pengpengdd.cyou/Article/details/gtvmlqsspe.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sufxvd.cn/Article/details/gtonyvvpnx.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtyvoiuadt.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.redwolf501.top/Article/details/gthdkmqlnw.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtylwbzxfb.html

[U01] Py：创建虚拟环境
来源：http://dali.0kj1m.cn/Article/details/gtkdqpbuqq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zdqjudy.top/Article/details/gtyqerlehg.html

[U02] Py：导出 / 安装依赖
来源：http://dali.ydzc1.top/Article/details/gtbgltavjw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.yanxiufei.cn/Article/details/gtxznostts.html

[U03] Py：加载 .env 配置
来源：http://dali.ppjwa.cn/Article/details/gthzwvgfxr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.aibaodan.cn/Article/details/gtjlyggycd.html

[U04] Py：变量调试打印
来源：http://dali.shzxlz.cn/Article/details/gtvcvasbrb.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yonumen.top/Article/details/gtgvzangye.html

[U05] Py：列表去重且保序
来源：http://dali.ivvv.top/Article/details/gtcbkhlfxh.html

list(dict.fromkeys(arr))
来源：http://dali.nanxuanxn.top/Article/details/gtvfwepvhn.html

[U06] Py：合并两个字典
来源：http://dali.cucudq.cn/Article/details/gtjosmdktt.html

{**a, **b}
来源：http://dali.0kj1m.cn/Article/details/gtaglcfndx.html

[U07] Py：反转字典键值
来源：http://dali.quarkkingdee.top/Article/details/gtjbawcijf.html

{v: k for k, v in d.items()}
来源：http://dali.snrcjt.cn/Article/details/gtkqzxigel.html

[U08] Py：展平二维列表
来源：http://dali.yanxiufei.cn/Article/details/gtaqdlfynx.html

[y for x in nested for y in x]
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkuqdxzcg.html

[U09] Py：字典取最大值的键
来源：http://dali.jinghuilouyu.cn/Article/details/gtwrzavzwh.html

max(d, key=d.get)
来源：http://dali.havefunace.top/Article/details/gtxqdrkkcl.html

[U10] Py：按值排序字典
来源：http://dali.haohaochexian.top/Article/details/gtkofpzsvz.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.ivvv.top/Article/details/gtjfcyingi.html

[U11] Py：生成器表达式
来源：http://dali.ppjwa.cn/Article/details/gtjgxeadio.html

(x * 2 for x in arr)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcdnmqqso.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.jianghu66.top/Article/details/gtqnlplvqn.html

Counter(arr).most_common(3)
来源：http://dali.zhiwuduotai.top/Article/details/gtbrhbtnpu.html

[U13] Py：固定长度队列
来源：http://dali.aizwys.cn/Article/details/gtygovbpil.html

deque(maxlen=10)
来源：http://dali.pycfn.com/Article/details/gttrdxhhww.html

[U14] Py：分组收集到列表
来源：http://dali.guowangkeji.top/Article/details/gtvvptvprj.html

defaultdict(list)
来源：http://dali.yj20258.top/Article/details/gtmesdchbh.html


<!-- 参考信息 -->