代发 wailian999

split -l 1000 big.log part_
来源：http://dali.jlsjyb.cn/Article/details/gteuiffrpe.html

[R74] 批量重命名
来源：http://dali.meibo888.top/Article/details/gtncygahtp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.316326.xyz/Article/details/gtnmkcggnw.html

[R75] 导出环境变量
来源：http://dali.ybcxt.top/Article/details/gtvcgflcvi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.wangshuangyany.cn/Article/details/gtvsqvtpea.html

[R76] 使用临时文件
来源：http://dali.gotoacloud.top/Article/details/gtgtmiouzv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnxiangtu.top/Article/details/gtvxvgjgpo.html

[R77] 读取用户输入
来源：http://dali.yanxiufei.cn/Article/details/gtjwsnxhig.html

read -rp "请输入: " ans
来源：http://dali.0kj1m.cn/Article/details/gtlxjvdrtd.html

[R78] 交互式菜单
来源：http://dali.hfpthk.cn/Article/details/gtpohlbrhl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpuykvccn.html

[R79] 解析命令行选项
来源：http://dali.gotoacloud.top/Article/details/gtmbggdein.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hfpthk.cn/Article/details/gtwvphutvo.html

[R80] 查看脚本执行耗时
来源：http://dali.vqdsnc.cn/Article/details/gtumejzwyj.html

time ./run.sh
来源：http://dali.jinqigufen.top/Article/details/gtznjqwbvn.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtpogvfahl.html

S. C / C++ 专题
来源：http://dali.xinyue.icu/Article/details/gtprwfzvkp.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gterkhjctl.html

[S01] C：Hello World
来源：http://dali.bjfxy.top/Article/details/gtfwjshkft.html

#include <stdio.h>
来源：http://dali.ybcxt.top/Article/details/gtednhiuwf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cdnleiting.top/Article/details/gtcfmilogf.html

[S02] C：变量与格式化输出
来源：http://dali.cdnleiting.top/Article/details/gtmvzhofbg.html

int a = 10; printf("%d\n", a);
来源：http://dali.haohaochexian.top/Article/details/gtanzvzkrv.html

[S03] C：读入整数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfvezjybp.html

int x; scanf("%d", &x);
来源：http://dali.ybcxt.top/Article/details/gtfgyqiags.html

[S04] C：字符串复制
来源：http://dali.cucudq.cn/Article/details/gtdnsdqemz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gtrrvhjnfa.html

[S05] C：字符串长度
来源：http://dali.jianghu66.top/Article/details/gtsdgizbai.html

strlen(s)
来源：http://dali.yueranfly.top/Article/details/gtykovsgoq.html

[S06] C：字符串比较
来源：http://dali.shangyingyoupin.top/Article/details/gtkxvweylr.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gtrhuvutml.html

[S07] C：数组遍历求和
来源：http://dali.shanyushiyangtech.top/Article/details/gtcdaauefm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.dashuyun.cn/Article/details/gtrhmhvjmt.html

[S08] C：动态内存分配与释放
来源：http://dali.ydzc1.top/Article/details/gtgsnaahpk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhoulong.xyz/Article/details/gtyyuwyqvy.html

[S09] C：结构体定义与初始化
来源：http://dali.zdqjudy.top/Article/details/gtbdkgvvzr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinyuanbaomall.cn/Article/details/gtawnspdzy.html

[S10] C：指针与解引用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtihkcauhq.html

int *p = &a;  *p = 5;
来源：http://dali.chenlongwang.top/Article/details/gtkdkjkkrd.html

[S11] C：逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gtolgywgrm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yuanzhike.top/Article/details/gthikmbqdr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.quarkkingdee.top/Article/details/gtakfldnxo.html

fclose(f);
来源：http://dali.hysaishi.cn/Article/details/gtylptbage.html

[S12] C：写文件
来源：http://dali.316326.xyz/Article/details/gtypyudwvy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.c1oappe.top/Article/details/gtiiolvzju.html

[S13] C：宏定义
来源：http://dali.guannengcc.top/Article/details/gtdfictbiu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gaohongyu789.top/Article/details/gtxkhssylj.html

[S14] C：枚举
来源：http://dali.yj20258888.top/Article/details/gtrnelsbuk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.nanxinkj.top/Article/details/gtsootmhzt.html

[S15] C：类型转换
来源：http://dali.hnqzz.top/Article/details/gtvkimiffb.html

(double) a / b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdwtahquw.html

[S16] C：位操作置位
来源：http://dali.andypj.xyz/Article/details/gtubqkfyrf.html

x |= (1 << 3);
来源：http://dali.meibo888.top/Article/details/gteuobvpxe.html

[S17] C：安全拼接字符串
来源：http://dali.sysykeji.top/Article/details/gtizgiihgi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cdnleiting.top/Article/details/gthpttlcqq.html

[S18] C：命令行参数
来源：http://dali.0kj1m.cn/Article/details/gtqiyefmqj.html

int main(int argc, char **argv)
来源：http://dali.zdqjudy.top/Article/details/gtgypoxjpn.html

[S19] C：快速排序
来源：http://dali.nanxinkj.top/Article/details/gtooftxgmh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gtyaqjubes.html

[S20] C：二分查找
来源：http://dali.yanxiufei.cn/Article/details/gtdplbmuev.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yonumen.top/Article/details/gtxxwzouen.html

[S21] C：字符类别判断
来源：http://dali.yongpay.top/Article/details/gtcegrikur.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhoulong.xyz/Article/details/gtlxdgpdpd.html

[S22] C：字符串转数字
来源：http://dali.tanke756.top/Article/details/gtwyglmmhm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.wangshuangyany.cn/Article/details/gtxdgdeppu.html

[S23] C：随机数
来源：http://dali.9152youxi.cn/Article/details/gtavkhgbsh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jianghu66.top/Article/details/gtqbxufhcf.html

[S24] C：获取本地时间
来源：http://dali.jqgfzy.top/Article/details/gturajkcbn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.fengsongda.top/Article/details/gtenevqjdq.html

[S25] C：内存拷贝
来源：http://dali.xuanzx.com/Article/details/gtnyowaujm.html

memcpy(dst, src, n);
来源：http://dali.tian-w.cn/Article/details/gtdecbwecx.html

[S26] C：内存清零
来源：http://dali.hfpthk.cn/Article/details/gtopsqkiao.html

memset(a, 0, sizeof a);
来源：http://dali.zdqjudy.top/Article/details/gtdxopjyfq.html

[S27] C：定义常量
来源：http://dali.yanxiufei.cn/Article/details/gtchizqtqb.html

const double PI = 3.14159;
来源：http://dali.aibaodan.cn/Article/details/gtauvgsqfr.html

[S28] C：静态变量
来源：http://dali.nanxinkj.top/Article/details/gtpkugchhh.html

static int counter = 0;
来源：http://dali.fengsongda.top/Article/details/gtgkwpoygu.html

[S29] C：变参函数
来源：http://dali.xuanzx.com/Article/details/gtiywvdcht.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.iojbl.cn/Article/details/gttbdzsoks.html

[S30] C：头文件保护
来源：http://dali.ppjwa.cn/Article/details/gttaclgopq.html

#ifndef X_H
来源：http://dali.wangdashe.top/Article/details/gteemcswgq.html

#define X_H
来源：http://dali.hywenlv.cn/Article/details/gtlqlzpgcp.html

#endif
来源：http://dali.dianchejie.cn/Article/details/gtkkkoawyw.html

[S31] C++：Hello World
来源：http://dali.bjfxy.top/Article/details/gtivqhrlbd.html

#include <iostream>
来源：http://dali.zhaomingkeji.xyz/Article/details/gteozbaebv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gotoacloud.top/Article/details/gtyzlctotb.html

[S32] C++：字符串
来源：http://dali.yuanzhike.top/Article/details/gttvkadajh.html

std::string s = "hi";  s += "!";
来源：http://dali.jinghuilouyu.cn/Article/details/gtsmotdrqp.html

[S33] C++：vector 增删
来源：http://dali.yanxiufei.cn/Article/details/gtxhyuymyj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xinyue.icu/Article/details/gttelokojn.html

[S34] C++：遍历 vector
来源：http://dali.snrcjt.cn/Article/details/gtrkfzaqde.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.daxiang520.top/Article/details/gtlzchwwmw.html

[S35] C++：map
来源：http://dali.zhengqikj.top/Article/details/gthxcpmndo.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtgtxgqlvy.html

[S36] C++：unordered_map
来源：http://dali.andypj.xyz/Article/details/gtojowomsk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gzhubu.top/Article/details/gtopqcwriq.html

[S37] C++：set
来源：http://dali.yongpay.top/Article/details/gtoyxbsxsz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinqigfzy.top/Article/details/gtoiakhaft.html

[S38] C++：排序
来源：http://dali.mhx1999.top/Article/details/gtfcfkowvh.html

std::sort(v.begin(), v.end());
来源：http://dali.chenlongwang.top/Article/details/gtrhmsfecy.html

[S39] C++：自定义比较器排序
来源：http://dali.zhiwuduotai.top/Article/details/gthvtmqxon.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmpifyldf.html

[S40] C++：查找元素
来源：http://dali.nwbrower.top/Article/details/gtxdbhchav.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xuanzx.com/Article/details/gtdgmlxget.html

[S41] C++：类与构造函数
来源：http://dali.316326.xyz/Article/details/gthkqekuib.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zdqjudy.top/Article/details/gtjdmlgopw.html

[S42] C++：继承与虚函数
来源：http://dali.chenjidiqi.icu/Article/details/gtemlvtyic.html

class B : public Base { public: void f() override {} };
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyxaqmlwd.html

[S43] C++：智能指针
来源：http://dali.aizwys.cn/Article/details/gtignygrgp.html

auto p = std::make_unique<int>(5);
来源：http://dali.snrcjt.cn/Article/details/gtrrouweli.html

[S44] C++：引用传参
来源：http://dali.nanxuanxn.top/Article/details/gtmjhlfojv.html

void inc(int &x) { ++x; }
来源：http://dali.cdnleiting.top/Article/details/gtiljdvspn.html

[S45] C++：lambda
来源：http://dali.nanxinkj.top/Article/details/gtncvcjpjb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.feifeiyinyue.top/Article/details/gthtcioptq.html

[S46] C++：函数模板
来源：http://dali.ppjwa.cn/Article/details/gtpbghydwk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ppjwa.cn/Article/details/gtqagzmfbg.html

[S47] C++：结构化绑定遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbifmhdsd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sufxvd.cn/Article/details/gtozgxheps.html

[S48] C++：逐行读文件
来源：http://dali.wangdashe.top/Article/details/gtdhrstwto.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.tian-w.cn/Article/details/gtxxgkftla.html

while (std::getline(in, line)) { }
来源：http://dali.316326.xyz/Article/details/gttshijyvi.html

[S49] C++：写文件
来源：http://dali.shzxlz.cn/Article/details/gtdnhflflq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cheryme.top/Article/details/gterdspxon.html

[S50] C++：格式化数字
来源：http://dali.xziqi.cn/Article/details/gtbgteeoou.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gthbeoaorl.html

[S51] C++：显式类型转换
来源：http://dali.gaohongyu789.top/Article/details/gtwlctsxhl.html

static_cast<double>(a) / b
来源：http://dali.xuetiantiany.cn/Article/details/gtrownrdtt.html

[S52] C++：const 与 noexcept
来源：http://dali.jqgufenzy.top/Article/details/gtslpunvrb.html

int size() const noexcept { return n_; }
来源：http://dali.meibo888.top/Article/details/gtchlepcqm.html

[S53] C++：移动语义
来源：http://dali.hywenlv.cn/Article/details/gtuickdinl.html

std::vector<int> w = std::move(v);
来源：http://dali.dashuyun.cn/Article/details/gtunoalgkc.html

[S54] C++：异常处理
来源：http://dali.jqgfzy.top/Article/details/gtklollojy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cheryme.top/Article/details/gthetmhypv.html

[S55] C++：结构化绑定
来源：http://dali.birdmap.top/Article/details/gtocmqbhxz.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jyoumei.cn/Article/details/gtjafkvxbj.html

[S56] C++：optional
来源：http://dali.yangfankeji.com/Article/details/gtkhnjrgot.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zycfv.cn/Article/details/gtwaditmfw.html

[S57] C++：编译期常量
来源：http://dali.aizwys.cn/Article/details/gtimepejol.html

constexpr int N = 10;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgyyxfyjq.html

[S58] C++：命名空间
来源：http://dali.ydzc1.top/Article/details/gtykzmvsfx.html

namespace ns { int f() { return 1; } }
来源：http://dali.yuxming.cn/Article/details/gtcbujrqhx.html

[S59] C++：静态断言
来源：http://dali.zhijiandao.cn/Article/details/gtoeaviade.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shuidangran.top/Article/details/gtjlbbswgo.html

[S60] C++：遍历并删除元素
来源：http://dali.snrcjt.cn/Article/details/gtxealstwl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xuetiantiany.cn/Article/details/gtjtzvhyha.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtshremhdb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sweek.top/Article/details/gtwwppppfi.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtiudzhutl.html

[T01] Kotlin：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtgobstlis.html

println("Hello")
来源：http://dali.fengsongda.top/Article/details/gtzfcbytcj.html

[T02] Kotlin：变量
来源：http://dali.dashuyun.cn/Article/details/gtkmpylkas.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.pycfn.com/Article/details/gtdbrppzml.html

[T03] Kotlin：字符串模板
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthzgbwsbg.html

"值: $b"
来源：http://dali.nanxinkj.top/Article/details/gtgatjegfk.html

[T04] Kotlin：空安全
来源：http://dali.yuanzhike.top/Article/details/gtoigefkqn.html

val n: String? = null;  n?.length
来源：http://dali.chenlongwang.top/Article/details/gtcvqrcfpx.html

[T05] Kotlin：when 表达式
来源：http://dali.gzhubu.top/Article/details/gtwyfhucog.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.chenzaomai.com/Article/details/gttrjbufxq.html

[T06] Kotlin：集合映射
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqbolexps.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.pycfn.com/Article/details/gtwnwnakte.html

[T07] Kotlin：集合过滤
来源：http://dali.cucudq.cn/Article/details/gthlwzclyh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.chenlongwang.top/Article/details/gtixmwhwmc.html

[T08] Kotlin：数据类
来源：http://dali.zhongyouzk.top/Article/details/gtozhldecl.html

data class User(val name: String, val age: Int)
来源：http://dali.shuidangran.top/Article/details/gtmbvmtlmr.html

[T09] Kotlin：扩展函数
来源：http://dali.yanxiufei.cn/Article/details/gtwqpkzjbh.html

fun String.exclaim() = this + "!"
来源：http://dali.nanxuanxn.top/Article/details/gtierjpltx.html

[T10] Kotlin：默认参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gthjxtawrz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hnxiangtu.top/Article/details/gterwiflec.html

[T11] Kotlin：协程
来源：http://dali.jqgufenzy.top/Article/details/gttpvvvmpv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhixingplan.top/Article/details/gteraprlvn.html

[T12] Kotlin：解构声明
来源：http://dali.zhijiandao.cn/Article/details/gtbccxjawr.html

val (a, b) = Pair(1, 2)
来源：http://dali.yongpay.top/Article/details/gtxyfussqo.html

[T13] Kotlin：只读 Map
来源：http://dali.andypj.xyz/Article/details/gtonlryubz.html

val m = mapOf("a" to 1)
来源：http://dali.feifeiyinyue.top/Article/details/gthbfuxyzu.html

[T14] Kotlin：循环
来源：http://dali.iojbl.cn/Article/details/gtfggzwyqp.html

for (i in 1..10) println(i)
来源：http://dali.0kj1m.cn/Article/details/gtfrtfrohn.html

[T15] Kotlin：接口
来源：http://dali.kuanghao11.cn/Article/details/gtmputxjgv.html

interface Shape { fun area(): Double }
来源：http://dali.xuetiantiany.cn/Article/details/gtfgiavszk.html

[T16] Swift：Hello World
来源：http://dali.havefunace.top/Article/details/gtgbjbgxwu.html

print("Hello")
来源：http://dali.fzhhl.top/Article/details/gtmwswljwx.html

[T17] Swift：变量与常量
来源：http://dali.haohaochexian.top/Article/details/gtrvazsrkr.html

var a = 1;  let b = 2
来源：http://dali.yuanzhike.top/Article/details/gtuxkqchej.html

[T18] Swift：字符串插值
来源：http://dali.dashuyun.cn/Article/details/gthazdwpiv.html

"值: \(b)"
来源：http://dali.xuanzx.com/Article/details/gtnsfdocig.html

[T19] Swift：可选绑定
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrrokmhgu.html

if let n = opt { print(n) }
来源：http://dali.hywenlv.cn/Article/details/gtelokyszb.html

[T20] Swift：数组操作
来源：http://dali.cqqwz.cn/Article/details/gtlblfyzcg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.bjfxy.top/Article/details/gtbqpobgyc.html

[T21] Swift：遍历
来源：http://dali.mhx1999.top/Article/details/gtkcnxmtsd.html

for x in a { print(x) }
来源：http://dali.nanxuanxn.top/Article/details/gtywmqybrx.html

[T22] Swift：字典
来源：http://dali.ehwqpu.com/Article/details/gtwvozaudq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.nanxinkj.top/Article/details/gtipvhjcyw.html

[T23] Swift：函数
来源：http://dali.xuetiantiany.cn/Article/details/gtszfrzcur.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.iojbl.cn/Article/details/gtakgbzzmz.html

[T24] Swift：闭包
来源：http://dali.tanke756.top/Article/details/gthzeotaxs.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jqgufenzy.top/Article/details/gthhdweejk.html

[T25] Swift：结构体
来源：http://dali.vqdsnc.cn/Article/details/gtvxszychz.html

struct P { var x: Int }
来源：http://dali.xuetiantiany.cn/Article/details/gtnctbyzup.html

[T26] Swift：类与重写
来源：http://dali.gotoacloud.top/Article/details/gtlodlefnh.html

class A: Base { override func f() {} }
来源：http://dali.chenzaomai.com/Article/details/gtkhksmeuf.html

[T27] Swift：错误处理
来源：http://dali.smart0.xyz/Article/details/gtiimwihyn.html

do { try f() } catch { print(error) }
来源：http://dali.hysaishi.cn/Article/details/gtyiioryko.html

[T28] Swift：枚举
来源：http://dali.nwbrower.top/Article/details/gttlbpdlzm.html

enum Color { case red, green }
来源：http://dali.jinyuanbaomall.cn/Article/details/gthsuyaeqp.html

[T29] Swift：guard 提前返回
来源：http://dali.jinghuilouyu.cn/Article/details/gtrulxwnhi.html

guard let x = opt else { return }
来源：http://dali.yvedp.cn/Article/details/gtfthgzuyk.html

[T30] Swift：协议
来源：http://dali.wangdashe.top/Article/details/gtzbspeise.html

protocol Shape { func area() -> Double }
来源：http://dali.gaohongyu789.top/Article/details/gtvacbjjfn.html

[T31] Lua：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtkgoiypzj.html

print("Hello")
来源：http://dali.dashuyun.cn/Article/details/gteacfqxnk.html

[T32] Lua：局部变量
来源：http://dali.yongpay.top/Article/details/gtkzmmzfeg.html

local a = 1
来源：http://dali.xuanzx.com/Article/details/gtuuwqetig.html

[T33] Lua：表（数组）
来源：http://dali.yongpay.top/Article/details/gtrgjncudt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.dashuyun.cn/Article/details/gtiipyvrwm.html

[T34] Lua：遍历表
来源：http://dali.chenlongwang.top/Article/details/gtjkknkqzn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shangyingyoupin.top/Article/details/gtopewyppa.html

[T35] Lua：字典表
来源：http://dali.gaohongyu789.top/Article/details/gtcflbmnpo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cucudq.cn/Article/details/gtaycovwyr.html

[T36] Lua：函数
来源：http://dali.pengpengdd.cyou/Article/details/gtrfdrzjoj.html

function add(a, b) return a + b end
来源：http://dali.hfpthk.cn/Article/details/gtnsbazlkj.html

[T37] Lua：字符串拼接
来源：http://dali.jinghuilouyu.cn/Article/details/gtnwamyzwg.html

"a" .. "b"
来源：http://dali.sufxvd.cn/Article/details/gttbikslrr.html

[T38] Lua：条件
来源：http://dali.tianlin.xyz/Article/details/gtaspxtcxo.html

if x > 0 then print("正") end
来源：http://dali.daxiang520.top/Article/details/gtmuxlwnqu.html

[T39] Lua：模式匹配
来源：http://dali.zhongyouzk.top/Article/details/gtrfghddhm.html

string.find(s, "%d+")
来源：http://dali.9152youxi.cn/Article/details/gtwtyntxhm.html

[T40] Lua：元表
来源：http://dali.gaohongyu789.top/Article/details/gtblkkjqtx.html

setmetatable({}, { __index = base })
来源：http://dali.shangyingyoupin.top/Article/details/gthmbvidjj.html

[T41] Perl：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtkhkgvpxs.html

print "Hello\n";
来源：http://dali.snrcjt.cn/Article/details/gthnbpfqno.html

[T42] Perl：变量类型
来源：http://dali.zhijiandao.cn/Article/details/gtjxcyffvc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.kuanghao11.cn/Article/details/gtqefkmtui.html

[T43] Perl：字符串插值
来源：http://dali.chenjidiqi.icu/Article/details/gtbdmwsgck.html

"值: $a"
来源：http://dali.ehwqpu.com/Article/details/gtddeeelld.html

[T44] Perl：条件
来源：http://dali.nwbrower.top/Article/details/gtpstydimq.html

if ($a > 0) { print "正"; }
来源：http://dali.hnqzz.top/Article/details/gtrtpjnwzl.html

[T45] Perl：数组遍历
来源：http://dali.guannengcc.top/Article/details/gtyikxggbf.html

for my $x (@arr) { print $x; }
来源：http://dali.sweek.top/Article/details/gtscwrdqzt.html

[T46] Perl：哈希操作
来源：http://dali.zhoulong.xyz/Article/details/gttkwyenvf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.pycfn.com/Article/details/gtdubxmjxb.html

[T47] Perl：正则捕获
来源：http://dali.chenzaomai.com/Article/details/gtuezeovil.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.shzxlz.cn/Article/details/gtcgnxpsdg.html

[T48] Perl：正则替换
来源：http://dali.jyoumei.cn/Article/details/gtnjkncwxs.html

$s =~ s/old/new/g;
来源：http://dali.smart0.xyz/Article/details/gtojvpfstu.html

[T49] Perl：函数
来源：http://dali.fzhhl.top/Article/details/gtgrobpsqd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtobvyxebd.html

[T50] Perl：逐行读文件
来源：http://dali.daria6918.cn/Article/details/gtpksvvfdt.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.sysykeji.top/Article/details/gtxblsrtxi.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cqqwz.cn/Article/details/gtljdldvip.html

[T51] Scala：Hello World
来源：http://dali.cheryme.top/Article/details/gtjsgimgsr.html

println("Hello")
来源：http://dali.9152youxi.cn/Article/details/gttymqhzys.html

[T52] Scala：变量
来源：http://dali.chenzaomai.com/Article/details/gtgxtvnazk.html

val a = 1;  var b = 2
来源：http://dali.smart0.xyz/Article/details/gtzgznfoik.html

[T53] Scala：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gtmjfhzclg.html

s"值: $b"
来源：http://dali.feifeiyinyue.top/Article/details/gteqywelwd.html

[T54] Scala：集合映射
来源：http://dali.xylfe.cn/Article/details/gtzuolwqza.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cucudq.cn/Article/details/gtnwpnpvll.html

[T55] Scala：集合过滤
来源：http://dali.wangshuangyany.cn/Article/details/gtavmpngxl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.daxiang520.top/Article/details/gtcrnmiyzf.html

[T56] Scala：样例类
来源：http://dali.jinqigufen.top/Article/details/gtjdicwpto.html

case class User(name: String, age: Int)
来源：http://dali.aibaodan.cn/Article/details/gtbqhiupum.html

[T57] Scala：模式匹配
来源：http://dali.hammf.cn/Article/details/gtyuygnbts.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yj202588.top/Article/details/gtcahcrkan.html

[T58] Scala：函数定义
来源：http://dali.zhixingplan.top/Article/details/gthzkjxqww.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.pycfn.com/Article/details/gtirzjddvj.html

[T59] Scala：循环
来源：http://dali.smart0.xyz/Article/details/gtelnkpmix.html

for (i <- 1 to 10) println(i)
来源：http://dali.ybcxt.top/Article/details/gtgeirlhgk.html

[T60] Scala：折叠
来源：http://dali.guannengcc.top/Article/details/gtfyyacosk.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.iojbl.cn/Article/details/gtfpskccma.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gtmzdosgyy.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.pycfn.com/Article/details/gtddcbaejt.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gthinaadtt.html

[U01] Py：创建虚拟环境
来源：http://dali.nwbrower.top/Article/details/gtmfipqutn.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hysaishi.cn/Article/details/gtivjfaeqq.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zdqjudy.top/Article/details/gtjtoqnxey.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.quarkkingdee.top/Article/details/gtebvctkjw.html

[U03] Py：加载 .env 配置
来源：http://dali.zdqjudy.top/Article/details/gtddsyzjew.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jiagoushi.top/Article/details/gtfkghcqoe.html

[U04] Py：变量调试打印
来源：http://dali.birdmap.top/Article/details/gtzgzwxadh.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.xinyue.icu/Article/details/gticvprzyx.html

[U05] Py：列表去重且保序
来源：http://dali.ehwqpu.com/Article/details/gtipuhonzb.html

list(dict.fromkeys(arr))
来源：http://dali.sufxvd.cn/Article/details/gtwttdpfmf.html

[U06] Py：合并两个字典
来源：http://dali.jyoumei.cn/Article/details/gtcdxisthp.html

{**a, **b}
来源：http://dali.sufxvd.cn/Article/details/gtixgnwrxy.html

[U07] Py：反转字典键值
来源：http://dali.shangyingyoupin.top/Article/details/gtrijrvauv.html

{v: k for k, v in d.items()}
来源：http://dali.shangyingyoupin.top/Article/details/gtevuencpy.html

[U08] Py：展平二维列表
来源：http://dali.tanke756.top/Article/details/gtivgbwebb.html

[y for x in nested for y in x]
来源：http://dali.hywenlv.cn/Article/details/gtbkexwpam.html

[U09] Py：字典取最大值的键
来源：http://dali.0kj1m.cn/Article/details/gtgpaeflvn.html

max(d, key=d.get)
来源：http://dali.cucudq.cn/Article/details/gtkzhqxvdr.html

[U10] Py：按值排序字典
来源：http://dali.hfpthk.cn/Article/details/gtumkwyynt.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.svipenyu.cn/Article/details/gtkgellnkz.html

[U11] Py：生成器表达式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoecjopao.html

(x * 2 for x in arr)
来源：http://dali.dianchejie.cn/Article/details/gtjqdhapas.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.c1oappe.top/Article/details/gtyfxhtwhx.html

Counter(arr).most_common(3)
来源：http://dali.fzhhl.top/Article/details/gtbzsjybir.html

[U13] Py：固定长度队列
来源：http://dali.xuetiantiany.cn/Article/details/gtycftegmc.html

deque(maxlen=10)
来源：http://dali.hammf.cn/Article/details/gtomxhkcsx.html

[U14] Py：分组收集到列表
来源：http://dali.cdnleiting.top/Article/details/gtmwizkptf.html

defaultdict(list)
来源：http://dali.yj20258888.top/Article/details/gtwjyptjgk.html


<!-- 参考信息 -->