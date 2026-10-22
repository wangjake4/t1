代发 wailian999

split -l 1000 big.log part_
来源：http://dali.hammf.cn/Article/details/gtaeruoiyy.html

[R74] 批量重命名
来源：http://dali.gzhubu.top/Article/details/gtlibylgml.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gtoqpwszce.html

[R75] 导出环境变量
来源：http://dali.jinqigfzy.top/Article/details/gtjvacjqyb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.birdmap.top/Article/details/gtbqnyubni.html

[R76] 使用临时文件
来源：http://dali.hnqzz.top/Article/details/gtljcphfar.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.haohaochexian.top/Article/details/gtjctaeuuf.html

[R77] 读取用户输入
来源：http://dali.gzhubu.top/Article/details/gtxjzbxmpl.html

read -rp "请输入: " ans
来源：http://dali.sxryk.cn/Article/details/gtvsgjnfmq.html

[R78] 交互式菜单
来源：http://dali.tianlin.xyz/Article/details/gtjxhlzbqu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jiagoushi.top/Article/details/gtlljuojaj.html

[R79] 解析命令行选项
来源：http://dali.yueranfly.top/Article/details/gteyxnymtf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.andypj.xyz/Article/details/gtoaujmyps.html

[R80] 查看脚本执行耗时
来源：http://dali.yj20258.top/Article/details/gtqowailzn.html

time ./run.sh
来源：http://dali.zhengqikj.top/Article/details/gtmfsczwpq.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtnphillxt.html

S. C / C++ 专题
来源：http://dali.nanxuanxn.top/Article/details/gtbmntymcs.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtrnzacnuc.html

[S01] C：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtzewtdbje.html

#include <stdio.h>
来源：http://dali.tanke756.top/Article/details/gtatcchjcz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cheryme.top/Article/details/gtsgicqvoq.html

[S02] C：变量与格式化输出
来源：http://dali.hysaishi.cn/Article/details/gtilhugpip.html

int a = 10; printf("%d\n", a);
来源：http://dali.aibaodan.cn/Article/details/gtkswxtrjr.html

[S03] C：读入整数
来源：http://dali.gzhubu.top/Article/details/gtkzvalfsl.html

int x; scanf("%d", &x);
来源：http://dali.jinghuilouyu.cn/Article/details/gtetelimng.html

[S04] C：字符串复制
来源：http://dali.sweek.top/Article/details/gttqxrmfol.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.nanxinkj.top/Article/details/gtganfqmxk.html

[S05] C：字符串长度
来源：http://dali.ybcxt.top/Article/details/gtumxczzmm.html

strlen(s)
来源：http://dali.iojbl.cn/Article/details/gtexifqwhx.html

[S06] C：字符串比较
来源：http://dali.ivvv.top/Article/details/gtprmwzyos.html

strcmp(a, b) == 0
来源：http://dali.cqqwz.cn/Article/details/gtevjxkqfk.html

[S07] C：数组遍历求和
来源：http://dali.mhx1999.top/Article/details/gtzyhowcqg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sxryk.cn/Article/details/gtucimnpyk.html

[S08] C：动态内存分配与释放
来源：http://dali.0kj1m.cn/Article/details/gtsifgdzjs.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.haohaochexian.top/Article/details/gtenzhiunj.html

[S09] C：结构体定义与初始化
来源：http://dali.yj202588.top/Article/details/gtzscamhhz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hywenlv.cn/Article/details/gtvudadkny.html

[S10] C：指针与解引用
来源：http://dali.aizwys.cn/Article/details/gtytaqcxwt.html

int *p = &a;  *p = 5;
来源：http://dali.cucudq.cn/Article/details/gtocaxbmra.html

[S11] C：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gtlfnjougp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xylfe.cn/Article/details/gtluafonto.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.guowangkeji.top/Article/details/gtvabxhfzm.html

fclose(f);
来源：http://dali.zhengqikj.top/Article/details/gthhydegzd.html

[S12] C：写文件
来源：http://dali.zycfv.cn/Article/details/gtxvshoqjp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yongpay.top/Article/details/gtjbnhorvy.html

[S13] C：宏定义
来源：http://dali.shanyushiyangtech.top/Article/details/gtktvqzanx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yonumen.top/Article/details/gtdrryqksj.html

[S14] C：枚举
来源：http://dali.ywan-chungtsiang.top/Article/details/gtifetnvqp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yuanzhike.top/Article/details/gtpzufkeqa.html

[S15] C：类型转换
来源：http://dali.fzhhl.top/Article/details/gtsscmarua.html

(double) a / b
来源：http://dali.haohaochexian.top/Article/details/gtsxcffqjw.html

[S16] C：位操作置位
来源：http://dali.shzxlz.cn/Article/details/gtkxznmgny.html

x |= (1 << 3);
来源：http://dali.0kj1m.cn/Article/details/gthzuppylz.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gtakaecxjm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sweek.top/Article/details/gtgvvfxqje.html

[S18] C：命令行参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgzsjrtsk.html

int main(int argc, char **argv)
来源：http://dali.hongshengwenyu.top/Article/details/gtkuvswiom.html

[S19] C：快速排序
来源：http://dali.jianghu66.top/Article/details/gtqqniobes.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.tanke756.top/Article/details/gtmhhmonbi.html

[S20] C：二分查找
来源：http://dali.pycfn.com/Article/details/gtazcpfltv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gtbwknyxer.html

[S21] C：字符类别判断
来源：http://dali.yanxiufei.cn/Article/details/gtkpulwsvf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xuetiantiany.cn/Article/details/gtaojomyhj.html

[S22] C：字符串转数字
来源：http://dali.shuidangran.top/Article/details/gtugfmvwdj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.nanxuanxn.top/Article/details/gtuhlgpubb.html

[S23] C：随机数
来源：http://dali.quarkkingdee.top/Article/details/gtixtatgov.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yueranfly.top/Article/details/gtondvxpdl.html

[S24] C：获取本地时间
来源：http://dali.shuidangran.top/Article/details/gtstnqagnd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jlsjyb.cn/Article/details/gtdvchxyoy.html

[S25] C：内存拷贝
来源：http://dali.wangdashe.top/Article/details/gtwsqyslwk.html

memcpy(dst, src, n);
来源：http://dali.daxiang520.top/Article/details/gthuuzriia.html

[S26] C：内存清零
来源：http://dali.wangdashe.top/Article/details/gtembfpsmd.html

memset(a, 0, sizeof a);
来源：http://dali.wangshuangyany.cn/Article/details/gtwrkbrdbu.html

[S27] C：定义常量
来源：http://dali.shuidangran.top/Article/details/gtalwpleos.html

const double PI = 3.14159;
来源：http://dali.yj20258.top/Article/details/gtiaaegziv.html

[S28] C：静态变量
来源：http://dali.sxryk.cn/Article/details/gtvpigmlee.html

static int counter = 0;
来源：http://dali.daria6918.cn/Article/details/gtihglxuvb.html

[S29] C：变参函数
来源：http://dali.fzhhl.top/Article/details/gttnjtyzrb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ehwqpu.com/Article/details/gtvqynnqju.html

[S30] C：头文件保护
来源：http://dali.ydzc1.top/Article/details/gtchhkdhib.html

#ifndef X_H
来源：http://dali.tian-w.cn/Article/details/gtbdcylboy.html

#define X_H
来源：http://dali.yangfankeji.com/Article/details/gtuqcnjyvo.html

#endif
来源：http://dali.jinghuilouyu.cn/Article/details/gtyiwdaczt.html

[S31] C++：Hello World
来源：http://dali.yvedp.cn/Article/details/gtidxuwmax.html

#include <iostream>
来源：http://dali.svipenyu.cn/Article/details/gtaahjvioa.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.tian-w.cn/Article/details/gtndnjvyvg.html

[S32] C++：字符串
来源：http://dali.ybcxt.top/Article/details/gtpqztcnek.html

std::string s = "hi";  s += "!";
来源：http://dali.hnxiangtu.top/Article/details/gtyoxmxolv.html

[S33] C++：vector 增删
来源：http://dali.hnqzz.top/Article/details/gtzydpmlqz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gtsgltoxtv.html

[S34] C++：遍历 vector
来源：http://dali.gogol.net.cn/Article/details/gtwjnevkfi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhoulong.xyz/Article/details/gtaondwedq.html

[S35] C++：map
来源：http://dali.xuanzx.com/Article/details/gtkulqoisj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ybcxt.top/Article/details/gtoqogcndu.html

[S36] C++：unordered_map
来源：http://dali.smart0.xyz/Article/details/gtqdyaqnpk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtgxunagmi.html

[S37] C++：set
来源：http://dali.zhoulong.xyz/Article/details/gtgbcmdljt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sufxvd.cn/Article/details/gtvyyoxyne.html

[S38] C++：排序
来源：http://dali.xinyue.icu/Article/details/gtixeabont.html

std::sort(v.begin(), v.end());
来源：http://dali.yj20258888.top/Article/details/gtsumsfyig.html

[S39] C++：自定义比较器排序
来源：http://dali.zhiwuduotai.top/Article/details/gtdjyjuphk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ywan-chungtsiang.top/Article/details/gtplhtelwn.html

[S40] C++：查找元素
来源：http://dali.gzhubu.top/Article/details/gthwtnlthf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yj202588.top/Article/details/gtvnzuiopa.html

[S41] C++：类与构造函数
来源：http://dali.hfpthk.cn/Article/details/gtfpdpwgif.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhengqikj.top/Article/details/gtqzmjqsep.html

[S42] C++：继承与虚函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcmqflles.html

class B : public Base { public: void f() override {} };
来源：http://dali.shzxlz.cn/Article/details/gtvshyuslr.html

[S43] C++：智能指针
来源：http://dali.mhx1999.top/Article/details/gtpacoyvqx.html

auto p = std::make_unique<int>(5);
来源：http://dali.shangyingyoupin.top/Article/details/gttvmcfmof.html

[S44] C++：引用传参
来源：http://dali.redwolf501.top/Article/details/gtzsqxryno.html

void inc(int &x) { ++x; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtckathgdb.html

[S45] C++：lambda
来源：http://dali.svipenyu.cn/Article/details/gtycscriwq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.kuanghao11.cn/Article/details/gtxtpxnxts.html

[S46] C++：函数模板
来源：http://dali.chenjidiqi.icu/Article/details/gtmzaqlane.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.guowangkeji.top/Article/details/gtblvgiueq.html

[S47] C++：结构化绑定遍历
来源：http://dali.smart0.xyz/Article/details/gtzvcrwulk.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.c1oappe.top/Article/details/gtrlkmlznv.html

[S48] C++：逐行读文件
来源：http://dali.feifeiyinyue.top/Article/details/gtwuxjzkkr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.tanke756.top/Article/details/gtnojkogzq.html

while (std::getline(in, line)) { }
来源：http://dali.quarkkingdee.top/Article/details/gtrssxkcbq.html

[S49] C++：写文件
来源：http://dali.cqqwz.cn/Article/details/gtzakoazxn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ydzc1.top/Article/details/gtdpyhxxsr.html

[S50] C++：格式化数字
来源：http://dali.jinqigufen.top/Article/details/gtcmjyipfc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cashguo.top/Article/details/gtovlpxzbo.html

[S51] C++：显式类型转换
来源：http://dali.c1oappe.top/Article/details/gtpoazzhth.html

static_cast<double>(a) / b
来源：http://dali.9152youxi.cn/Article/details/gtbqlmqumg.html

[S52] C++：const 与 noexcept
来源：http://dali.chenzaomai.com/Article/details/gttrfjczal.html

int size() const noexcept { return n_; }
来源：http://dali.chenlongwang.top/Article/details/gtciruydej.html

[S53] C++：移动语义
来源：http://dali.haohaochexian.top/Article/details/gtnbywegzk.html

std::vector<int> w = std::move(v);
来源：http://dali.shanyushiyangtech.top/Article/details/gtygyzxywz.html

[S54] C++：异常处理
来源：http://dali.mhx1999.top/Article/details/gtivcecaqe.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.daria6918.cn/Article/details/gtygazuxre.html

[S55] C++：结构化绑定
来源：http://dali.tian-w.cn/Article/details/gtusvulndm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ivvv.top/Article/details/gtonqocegt.html

[S56] C++：optional
来源：http://dali.jinghuilouyu.cn/Article/details/gtsoonifvu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.kuanghao11.cn/Article/details/gtmxqbmiil.html

[S57] C++：编译期常量
来源：http://dali.shanyushiyangtech.top/Article/details/gttsarniyo.html

constexpr int N = 10;
来源：http://dali.guowangkeji.top/Article/details/gtzgtdwfsg.html

[S58] C++：命名空间
来源：http://dali.zdqjudy.top/Article/details/gtyxbizalx.html

namespace ns { int f() { return 1; } }
来源：http://dali.yvedp.cn/Article/details/gtfcfmobka.html

[S59] C++：静态断言
来源：http://dali.ehwqpu.com/Article/details/gtlhmzthnf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yongpay.top/Article/details/gtqnccixwe.html

[S60] C++：遍历并删除元素
来源：http://dali.sxryk.cn/Article/details/gtntzcpjoe.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ydzc1.top/Article/details/gtdsejjmnr.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtttxwhoyu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gtjwlxcfxs.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtjkzysfra.html

[T01] Kotlin：Hello World
来源：http://dali.xuanzx.com/Article/details/gtjsijkhgn.html

println("Hello")
来源：http://dali.zhixingplan.top/Article/details/gthemzykgc.html

[T02] Kotlin：变量
来源：http://dali.aizwys.cn/Article/details/gtrqvbeoqt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhijiandao.cn/Article/details/gtnomrfakx.html

[T03] Kotlin：字符串模板
来源：http://dali.dashuyun.cn/Article/details/gtmainuusa.html

"值: $b"
来源：http://dali.yongpay.top/Article/details/gtgwxrldgy.html

[T04] Kotlin：空安全
来源：http://dali.9152youxi.cn/Article/details/gtkwqjwpfw.html

val n: String? = null;  n?.length
来源：http://dali.hongshengwenyu.top/Article/details/gtlaeagymh.html

[T05] Kotlin：when 表达式
来源：http://dali.aizwys.cn/Article/details/gtrcdcubne.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.birdmap.top/Article/details/gtfnwhxgrh.html

[T06] Kotlin：集合映射
来源：http://dali.tian-w.cn/Article/details/gthhzeuqum.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.wangdashe.top/Article/details/gtlwezjpik.html

[T07] Kotlin：集合过滤
来源：http://dali.jqgfzy.top/Article/details/gtahpsguzx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhongyouzk.top/Article/details/gtudhtbhyw.html

[T08] Kotlin：数据类
来源：http://dali.ydzc1.top/Article/details/gtomcdhalf.html

data class User(val name: String, val age: Int)
来源：http://dali.tianlin.xyz/Article/details/gtnnyjozuy.html

[T09] Kotlin：扩展函数
来源：http://dali.sufxvd.cn/Article/details/gtebrrotkk.html

fun String.exclaim() = this + "!"
来源：http://dali.shuidangran.top/Article/details/gtttjblkpf.html

[T10] Kotlin：默认参数
来源：http://dali.gzhubu.top/Article/details/gtbqfitcxk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.mhx1999.top/Article/details/gttykwcdca.html

[T11] Kotlin：协程
来源：http://dali.zhixingplan.top/Article/details/gtlfaskfxz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgjghcmvv.html

[T12] Kotlin：解构声明
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpkezbyzf.html

val (a, b) = Pair(1, 2)
来源：http://dali.xuanzx.com/Article/details/gtnzqwgfrp.html

[T13] Kotlin：只读 Map
来源：http://dali.yj202588.top/Article/details/gtfygtkwzw.html

val m = mapOf("a" to 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtszgvvszt.html

[T14] Kotlin：循环
来源：http://dali.yueranfly.top/Article/details/gtziaiqotj.html

for (i in 1..10) println(i)
来源：http://dali.jinghuilouyu.cn/Article/details/gtvaseavza.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gtctasjwiy.html

interface Shape { fun area(): Double }
来源：http://dali.shanyushiyangtech.top/Article/details/gtsyirmiuh.html

[T16] Swift：Hello World
来源：http://dali.mhx1999.top/Article/details/gtyjsjectt.html

print("Hello")
来源：http://dali.aibaodan.cn/Article/details/gtsqdifgjy.html

[T17] Swift：变量与常量
来源：http://dali.nanxuanxn.top/Article/details/gtjlncvqrc.html

var a = 1;  let b = 2
来源：http://dali.gaohongyu789.top/Article/details/gtdukzdhhw.html

[T18] Swift：字符串插值
来源：http://dali.hnqzz.top/Article/details/gtxjlzuvvl.html

"值: \(b)"
来源：http://dali.hammf.cn/Article/details/gtfkefnxjn.html

[T19] Swift：可选绑定
来源：http://dali.shangyingyoupin.top/Article/details/gtdxmtrgow.html

if let n = opt { print(n) }
来源：http://dali.yangfankeji.com/Article/details/gtvpfmayvr.html

[T20] Swift：数组操作
来源：http://dali.yanxiufei.cn/Article/details/gtgpanrlkf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shzxlz.cn/Article/details/gtrbcpotwo.html

[T21] Swift：遍历
来源：http://dali.aizwys.cn/Article/details/gtoxpoaede.html

for x in a { print(x) }
来源：http://dali.meibo888.top/Article/details/gtkvoisixv.html

[T22] Swift：字典
来源：http://dali.ehwqpu.com/Article/details/gtfwqcwfip.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.wangdashe.top/Article/details/gtyokyuqtm.html

[T23] Swift：函数
来源：http://dali.tanke756.top/Article/details/gtiygbivbq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ppjwa.cn/Article/details/gtxfrbbljx.html

[T24] Swift：闭包
来源：http://dali.andypj.xyz/Article/details/gtzevzrdzu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.mhx1999.top/Article/details/gthyasigrm.html

[T25] Swift：结构体
来源：http://dali.aizwys.cn/Article/details/gtieootqkd.html

struct P { var x: Int }
来源：http://dali.0kj1m.cn/Article/details/gtjrlysaye.html

[T26] Swift：类与重写
来源：http://dali.pengpengdd.cyou/Article/details/gtrztououa.html

class A: Base { override func f() {} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlstphmao.html

[T27] Swift：错误处理
来源：http://dali.nanxinkj.top/Article/details/gtqiukulqe.html

do { try f() } catch { print(error) }
来源：http://dali.zhongyouzk.top/Article/details/gtqlxraraf.html

[T28] Swift：枚举
来源：http://dali.quarkkingdee.top/Article/details/gtugfbdgsh.html

enum Color { case red, green }
来源：http://dali.daria6918.cn/Article/details/gtsisttrrb.html

[T29] Swift：guard 提前返回
来源：http://dali.chenlongwang.top/Article/details/gtowmbtide.html

guard let x = opt else { return }
来源：http://dali.guannengcc.top/Article/details/gtgcwmozku.html

[T30] Swift：协议
来源：http://dali.xziqi.cn/Article/details/gthzrcyptz.html

protocol Shape { func area() -> Double }
来源：http://dali.zhongyouzk.top/Article/details/gtvqmdlrzf.html

[T31] Lua：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtadygeudl.html

print("Hello")
来源：http://dali.tanke756.top/Article/details/gtbzxqjlts.html

[T32] Lua：局部变量
来源：http://dali.yangfankeji.com/Article/details/gtbjcnhsas.html

local a = 1
来源：http://dali.zhengqikj.top/Article/details/gtgujglyqf.html

[T33] Lua：表（数组）
来源：http://dali.guowangkeji.top/Article/details/gteggbbsdh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hfpthk.cn/Article/details/gtbmpxgsjc.html

[T34] Lua：遍历表
来源：http://dali.wangdashe.top/Article/details/gtwvbgfwjt.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ivvv.top/Article/details/gtoruullip.html

[T35] Lua：字典表
来源：http://dali.nanxinkj.top/Article/details/gtdpeerxgy.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yanxiufei.cn/Article/details/gtleexzdhf.html

[T36] Lua：函数
来源：http://dali.yj20258.top/Article/details/gtlsaohxnc.html

function add(a, b) return a + b end
来源：http://dali.yvedp.cn/Article/details/gtynfhjnjc.html

[T37] Lua：字符串拼接
来源：http://dali.jianghu66.top/Article/details/gtymolvktl.html

"a" .. "b"
来源：http://dali.guowangkeji.top/Article/details/gthcmpphmx.html

[T38] Lua：条件
来源：http://dali.hywenlv.cn/Article/details/gtsibcnjtc.html

if x > 0 then print("正") end
来源：http://dali.shangyingyoupin.top/Article/details/gtoxldwfyl.html

[T39] Lua：模式匹配
来源：http://dali.smart0.xyz/Article/details/gtakjterjz.html

string.find(s, "%d+")
来源：http://dali.svipenyu.cn/Article/details/gtszxwdska.html

[T40] Lua：元表
来源：http://dali.yanxiufei.cn/Article/details/gttyxitkwl.html

setmetatable({}, { __index = base })
来源：http://dali.daria6918.cn/Article/details/gtohvmiunj.html

[T41] Perl：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtjhlgalgl.html

print "Hello\n";
来源：http://dali.iojbl.cn/Article/details/gtitskftts.html

[T42] Perl：变量类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzurdbhvh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.quarkkingdee.top/Article/details/gtihceslwc.html

[T43] Perl：字符串插值
来源：http://dali.hongshengwenyu.top/Article/details/gtzprwnsup.html

"值: $a"
来源：http://dali.chenjidiqi.icu/Article/details/gtwanfqcix.html

[T44] Perl：条件
来源：http://dali.316326.xyz/Article/details/gtjupjwham.html

if ($a > 0) { print "正"; }
来源：http://dali.ydzc1.top/Article/details/gtockgydsp.html

[T45] Perl：数组遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtijqzdksc.html

for my $x (@arr) { print $x; }
来源：http://dali.iojbl.cn/Article/details/gtmpzqmvsf.html

[T46] Perl：哈希操作
来源：http://dali.zhongyouzk.top/Article/details/gtkrriapvc.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shzxlz.cn/Article/details/gtafuljqrv.html

[T47] Perl：正则捕获
来源：http://dali.yongpay.top/Article/details/gtxubrnimq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.vqdsnc.cn/Article/details/gtreaowbki.html

[T48] Perl：正则替换
来源：http://dali.yj202588.top/Article/details/gtnmouokrm.html

$s =~ s/old/new/g;
来源：http://dali.316326.xyz/Article/details/gtyfbokkpb.html

[T49] Perl：函数
来源：http://dali.fengsongda.top/Article/details/gtnuudhoiz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yvedp.cn/Article/details/gtyyomhlle.html

[T50] Perl：逐行读文件
来源：http://dali.shzxlz.cn/Article/details/gtlwubrdqw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.pengpengdd.cyou/Article/details/gtiozsgezt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yonumen.top/Article/details/gtajvsxxtg.html

[T51] Scala：Hello World
来源：http://dali.yonumen.top/Article/details/gtaesaosid.html

println("Hello")
来源：http://dali.zhiwuduotai.top/Article/details/gtibkoeysn.html

[T52] Scala：变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlihnygig.html

val a = 1;  var b = 2
来源：http://dali.wangdashe.top/Article/details/gtrsnztuwt.html

[T53] Scala：字符串插值
来源：http://dali.daria6918.cn/Article/details/gtbomvzdim.html

s"值: $b"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtctsfifyo.html

[T54] Scala：集合映射
来源：http://dali.hfpthk.cn/Article/details/gtaciiffdu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.sxryk.cn/Article/details/gtqmulgdgk.html

[T55] Scala：集合过滤
来源：http://dali.andypj.xyz/Article/details/gtpahqgoym.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jyoumei.cn/Article/details/gtzmfokghk.html

[T56] Scala：样例类
来源：http://dali.chenjidiqi.icu/Article/details/gtoxnlkwxx.html

case class User(name: String, age: Int)
来源：http://dali.yuanzhike.top/Article/details/gtjyaofqma.html

[T57] Scala：模式匹配
来源：http://dali.nwbrower.top/Article/details/gtuwrtmxkl.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.daria6918.cn/Article/details/gtebtxlwxa.html

[T58] Scala：函数定义
来源：http://dali.hnxiangtu.top/Article/details/gtslkltxsa.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.c1oappe.top/Article/details/gtxwyqvycx.html

[T59] Scala：循环
来源：http://dali.guowangkeji.top/Article/details/gtqhfiwpvo.html

for (i <- 1 to 10) println(i)
来源：http://dali.wangdashe.top/Article/details/gtcvqyasrk.html

[T60] Scala：折叠
来源：http://dali.yj20258888.top/Article/details/gtdbjbpzoo.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.cashguo.top/Article/details/gtjnaujaqm.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtgchtqgqs.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.svipenyu.cn/Article/details/gtuloueumw.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtuudsuxiz.html

[U01] Py：创建虚拟环境
来源：http://dali.ydzc1.top/Article/details/gtenwsjteu.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.cheryme.top/Article/details/gtdhdgdicz.html

[U02] Py：导出 / 安装依赖
来源：http://dali.haohaochexian.top/Article/details/gtzafkcmbn.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.shangyingyoupin.top/Article/details/gteszswxda.html

[U03] Py：加载 .env 配置
来源：http://dali.ybcxt.top/Article/details/gtnlgiyezl.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.feifeiyinyue.top/Article/details/gtvrqqqpzy.html

[U04] Py：变量调试打印
来源：http://dali.jqgufenzy.top/Article/details/gtzafksimp.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.shzxlz.cn/Article/details/gtpujppzma.html

[U05] Py：列表去重且保序
来源：http://dali.wangdashe.top/Article/details/gtnalzvrya.html

list(dict.fromkeys(arr))
来源：http://dali.zhongyouzk.top/Article/details/gtuyftuyxe.html

[U06] Py：合并两个字典
来源：http://dali.zhijiandao.cn/Article/details/gtwbnlzwxh.html

{**a, **b}
来源：http://dali.iojbl.cn/Article/details/gtxnjcufhf.html

[U07] Py：反转字典键值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzcailzda.html

{v: k for k, v in d.items()}
来源：http://dali.wangdashe.top/Article/details/gtowbafczc.html

[U08] Py：展平二维列表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrfsadchb.html

[y for x in nested for y in x]
来源：http://dali.yj202588.top/Article/details/gttjkmmfzs.html

[U09] Py：字典取最大值的键
来源：http://dali.tanke756.top/Article/details/gtytzzxfac.html

max(d, key=d.get)
来源：http://dali.chenlongwang.top/Article/details/gtbsrwhbjh.html

[U10] Py：按值排序字典
来源：http://dali.xuetiantiany.cn/Article/details/gtgtxsplmg.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.haohaochexian.top/Article/details/gtfwirsfoo.html

[U11] Py：生成器表达式
来源：http://dali.gotoacloud.top/Article/details/gtbwrpqnmv.html

(x * 2 for x in arr)
来源：http://dali.andypj.xyz/Article/details/gtcsdecbvj.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.svipenyu.cn/Article/details/gtlinhjmis.html

Counter(arr).most_common(3)
来源：http://dali.hammf.cn/Article/details/gtexjrvhub.html

[U13] Py：固定长度队列
来源：http://dali.chenzaomai.com/Article/details/gtmvqhnbsf.html

deque(maxlen=10)
来源：http://dali.zhiwuduotai.top/Article/details/gtkamkjbay.html

[U14] Py：分组收集到列表
来源：http://dali.c1oappe.top/Article/details/gtmgfchedy.html

defaultdict(list)
来源：http://dali.hnqzz.top/Article/details/gtvldrzkwo.html


<!-- 参考信息 -->