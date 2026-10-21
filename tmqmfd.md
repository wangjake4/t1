代发 wailian999

head -c 16 /dev/urandom | base64
来源：http://dali.shangyingyoupin.top/Article/details/gtakizjxnm.html

[R70] 时间戳与互转
来源：http://dali.cheryme.top/Article/details/gtlzutfspk.html

date +%s;  date -d @1700000000
来源：http://dali.guowangkeji.top/Article/details/gtigxbbvnx.html

[R71] 日期格式化
来源：http://dali.snrcjt.cn/Article/details/gthzanabvy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.aizwys.cn/Article/details/gtktqtxxwb.html

[R72] 等待端口就绪
来源：http://dali.zhiwuduotai.top/Article/details/gtpyufdtsx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yangfankeji.com/Article/details/gtznrypnuo.html

[R73] 分割大日志
来源：http://dali.gotoacloud.top/Article/details/gtzdahggok.html

split -l 1000 big.log part_
来源：http://dali.yueranfly.top/Article/details/gtjfiwexeh.html

[R74] 批量重命名
来源：http://dali.xinyue.icu/Article/details/gtrqztfyhn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cdnleiting.top/Article/details/gtjaqjlfdd.html

[R75] 导出环境变量
来源：http://dali.tanke756.top/Article/details/gtyvefvhfu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jiagoushi.top/Article/details/gtcziwrdqv.html

[R76] 使用临时文件
来源：http://dali.tian-w.cn/Article/details/gtkpevesck.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hammf.cn/Article/details/gtpurpjrct.html

[R77] 读取用户输入
来源：http://dali.hnqzz.top/Article/details/gtpveozrzf.html

read -rp "请输入: " ans
来源：http://dali.316326.xyz/Article/details/gtawqparus.html

[R78] 交互式菜单
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbacfmxov.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.haohaochexian.top/Article/details/gtjhkhpcni.html

[R79] 解析命令行选项
来源：http://dali.hnxiangtu.top/Article/details/gtxudzoilx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ivvv.top/Article/details/gtfhpweown.html

[R80] 查看脚本执行耗时
来源：http://dali.yanxiufei.cn/Article/details/gtmdllxiaf.html

time ./run.sh
来源：http://dali.daria6918.cn/Article/details/gtrjlsisdx.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtzaqnxvvp.html

S. C / C++ 专题
来源：http://dali.guowangkeji.top/Article/details/gtpthwfytn.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtgytswvkp.html

[S01] C：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtxpadtjcr.html

#include <stdio.h>
来源：http://dali.cucudq.cn/Article/details/gtnwjnwvrd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hammf.cn/Article/details/gtaczappjt.html

[S02] C：变量与格式化输出
来源：http://dali.redwolf501.top/Article/details/gtzaydmuat.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhongyouzk.top/Article/details/gtaxtqfjlx.html

[S03] C：读入整数
来源：http://dali.aibaodan.cn/Article/details/gtbfsafgyn.html

int x; scanf("%d", &x);
来源：http://dali.smart0.xyz/Article/details/gtnlxxweam.html

[S04] C：字符串复制
来源：http://dali.yanxiufei.cn/Article/details/gtljpnukrv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhiwuduotai.top/Article/details/gtgogqsacd.html

[S05] C：字符串长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtkfcbleya.html

strlen(s)
来源：http://dali.zycfv.cn/Article/details/gtcdwcdxum.html

[S06] C：字符串比较
来源：http://dali.xylfe.cn/Article/details/gtwfbrlodd.html

strcmp(a, b) == 0
来源：http://dali.aizwys.cn/Article/details/gtwrpqtryy.html

[S07] C：数组遍历求和
来源：http://dali.hywenlv.cn/Article/details/gtsmlfndfo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhengqikj.top/Article/details/gtxadynujq.html

[S08] C：动态内存分配与释放
来源：http://dali.xinyue.icu/Article/details/gtjfioerqf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.aizwys.cn/Article/details/gtvsnnsjnr.html

[S09] C：结构体定义与初始化
来源：http://dali.iojbl.cn/Article/details/gtnbsraxkl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.smart0.xyz/Article/details/gtkvyaclzw.html

[S10] C：指针与解引用
来源：http://dali.havefunace.top/Article/details/gtwtneyfeu.html

int *p = &a;  *p = 5;
来源：http://dali.smart0.xyz/Article/details/gtwhkfimom.html

[S11] C：逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gtucvcmfyj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gzhubu.top/Article/details/gttzolvsih.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yongpay.top/Article/details/gtbxxqcrna.html

fclose(f);
来源：http://dali.cheryme.top/Article/details/gthroaburg.html

[S12] C：写文件
来源：http://dali.jqgfzy.top/Article/details/gtjaafzkvf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jqgufenzy.top/Article/details/gtullesidb.html

[S13] C：宏定义
来源：http://dali.jqgfzy.top/Article/details/gtpvcymlrl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shanyushiyangtech.top/Article/details/gtlsmoneql.html

[S14] C：枚举
来源：http://dali.jianghu66.top/Article/details/gtzdetzvjw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.tian-w.cn/Article/details/gtvxvwmpgx.html

[S15] C：类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtesoqjotu.html

(double) a / b
来源：http://dali.yanxiufei.cn/Article/details/gtauqmdszy.html

[S16] C：位操作置位
来源：http://dali.gzhubu.top/Article/details/gtybuuohiv.html

x |= (1 << 3);
来源：http://dali.gzhubu.top/Article/details/gtihgjsrhk.html

[S17] C：安全拼接字符串
来源：http://dali.yonumen.top/Article/details/gtnuwrmbqs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shanyushiyangtech.top/Article/details/gtymdxgrsf.html

[S18] C：命令行参数
来源：http://dali.wangshuangyany.cn/Article/details/gtvhaduyij.html

int main(int argc, char **argv)
来源：http://dali.jinqigfzy.top/Article/details/gtshzdaiwr.html

[S19] C：快速排序
来源：http://dali.zhoulong.xyz/Article/details/gtdbscsiaj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.chenzaomai.com/Article/details/gtolksacju.html

[S20] C：二分查找
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvrnucxlv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cucudq.cn/Article/details/gtrzqgjayi.html

[S21] C：字符类别判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gthppyryup.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.nwbrower.top/Article/details/gtjhziovvx.html

[S22] C：字符串转数字
来源：http://dali.bjfxy.top/Article/details/gtkufsnjfx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sufxvd.cn/Article/details/gteqsogejy.html

[S23] C：随机数
来源：http://dali.meibo888.top/Article/details/gtklnpmbbd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.birdmap.top/Article/details/gtvabueibo.html

[S24] C：获取本地时间
来源：http://dali.xuetiantiany.cn/Article/details/gtluvttlrr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sufxvd.cn/Article/details/gtvwlhhutg.html

[S25] C：内存拷贝
来源：http://dali.shzxlz.cn/Article/details/gtjkymmllh.html

memcpy(dst, src, n);
来源：http://dali.9152youxi.cn/Article/details/gtlepzwihb.html

[S26] C：内存清零
来源：http://dali.cqqwz.cn/Article/details/gthswovosf.html

memset(a, 0, sizeof a);
来源：http://dali.sysykeji.top/Article/details/gtejleiocn.html

[S27] C：定义常量
来源：http://dali.cheryme.top/Article/details/gthbuyghnv.html

const double PI = 3.14159;
来源：http://dali.chenzaomai.com/Article/details/gtngiyxgns.html

[S28] C：静态变量
来源：http://dali.hongshengwenyu.top/Article/details/gtmdelreyj.html

static int counter = 0;
来源：http://dali.zhongyouzk.top/Article/details/gtdeqeystq.html

[S29] C：变参函数
来源：http://dali.chenzaomai.com/Article/details/gtfrtumfqr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yj202588.top/Article/details/gtrlylzodo.html

[S30] C：头文件保护
来源：http://dali.fzhhl.top/Article/details/gtchsyasqp.html

#ifndef X_H
来源：http://dali.c1oappe.top/Article/details/gtlattsrne.html

#define X_H
来源：http://dali.jianghu66.top/Article/details/gtijjptiol.html

#endif
来源：http://dali.nanxuanxn.top/Article/details/gthkasjjsv.html

[S31] C++：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtnuvvcwmn.html

#include <iostream>
来源：http://dali.yangfankeji.com/Article/details/gtigccoyxf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.mhx1999.top/Article/details/gtaljmdhcs.html

[S32] C++：字符串
来源：http://dali.pengpengdd.cyou/Article/details/gtqxzrfaby.html

std::string s = "hi";  s += "!";
来源：http://dali.yonumen.top/Article/details/gthnkqqfjr.html

[S33] C++：vector 增删
来源：http://dali.ydzc1.top/Article/details/gtddrvoonc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xylfe.cn/Article/details/gtootxkqyl.html

[S34] C++：遍历 vector
来源：http://dali.sysykeji.top/Article/details/gtmwohljqh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.guannengcc.top/Article/details/gtvajreiea.html

[S35] C++：map
来源：http://dali.chenjidiqi.icu/Article/details/gtavkmezth.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tanke756.top/Article/details/gtfjvjdbcz.html

[S36] C++：unordered_map
来源：http://dali.jqgufenzy.top/Article/details/gtpaaknbzi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gthzijoebm.html

[S37] C++：set
来源：http://dali.xylfe.cn/Article/details/gtkbqwzblc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.mhx1999.top/Article/details/gtlkhmxyte.html

[S38] C++：排序
来源：http://dali.cashguo.top/Article/details/gtusbibygf.html

std::sort(v.begin(), v.end());
来源：http://dali.ybcxt.top/Article/details/gthiwpngrh.html

[S39] C++：自定义比较器排序
来源：http://dali.svipenyu.cn/Article/details/gtjotecwio.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ybcxt.top/Article/details/gtjlfjgvue.html

[S40] C++：查找元素
来源：http://dali.xylfe.cn/Article/details/gtodtxfosp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ybcxt.top/Article/details/gtctnaccjy.html

[S41] C++：类与构造函数
来源：http://dali.tianlin.xyz/Article/details/gteqiepoud.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hysaishi.cn/Article/details/gttusrcmkp.html

[S42] C++：继承与虚函数
来源：http://dali.sweek.top/Article/details/gtuocmhltf.html

class B : public Base { public: void f() override {} };
来源：http://dali.daxiang520.top/Article/details/gtyzmzzwxt.html

[S43] C++：智能指针
来源：http://dali.wangdashe.top/Article/details/gtghmqulzl.html

auto p = std::make_unique<int>(5);
来源：http://dali.sysykeji.top/Article/details/gthmoorhdo.html

[S44] C++：引用传参
来源：http://dali.ivvv.top/Article/details/gtzgodzbtg.html

void inc(int &x) { ++x; }
来源：http://dali.sysykeji.top/Article/details/gtpavogyez.html

[S45] C++：lambda
来源：http://dali.nanxuanxn.top/Article/details/gtjzfyfjhh.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhongyouzk.top/Article/details/gtsvyadcij.html

[S46] C++：函数模板
来源：http://dali.yj20258888.top/Article/details/gtlufmxpyo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cashguo.top/Article/details/gtjcawgnnu.html

[S47] C++：结构化绑定遍历
来源：http://dali.aibaodan.cn/Article/details/gtpxwhiizg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xuetiantiany.cn/Article/details/gtxjujlhbs.html

[S48] C++：逐行读文件
来源：http://dali.nwbrower.top/Article/details/gtsntyiolx.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfjolyall.html

while (std::getline(in, line)) { }
来源：http://dali.jqgfzy.top/Article/details/gtmpuheadj.html

[S49] C++：写文件
来源：http://dali.sufxvd.cn/Article/details/gtbhiigxqn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.bjfxy.top/Article/details/gtbyvktizv.html

[S50] C++：格式化数字
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpgblxupf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.316326.xyz/Article/details/gtgthvrdyj.html

[S51] C++：显式类型转换
来源：http://dali.guannengcc.top/Article/details/gtodtfpeqr.html

static_cast<double>(a) / b
来源：http://dali.guannengcc.top/Article/details/gtluhggavc.html

[S52] C++：const 与 noexcept
来源：http://dali.zhoulong.xyz/Article/details/gtkozlwhnv.html

int size() const noexcept { return n_; }
来源：http://dali.xuanzx.com/Article/details/gtvxxxlhqc.html

[S53] C++：移动语义
来源：http://dali.ehwqpu.com/Article/details/gtsujumsxz.html

std::vector<int> w = std::move(v);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuqzpexom.html

[S54] C++：异常处理
来源：http://dali.havefunace.top/Article/details/gtgwndunrl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shangyingyoupin.top/Article/details/gtohygfsrh.html

[S55] C++：结构化绑定
来源：http://dali.jinqigufen.top/Article/details/gtfltuqcfj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yuanzhike.top/Article/details/gtpwnsncxn.html

[S56] C++：optional
来源：http://dali.smart0.xyz/Article/details/gtlxwfqmup.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hysaishi.cn/Article/details/gtsbftieaw.html

[S57] C++：编译期常量
来源：http://dali.yueranfly.top/Article/details/gtafsoquaq.html

constexpr int N = 10;
来源：http://dali.quarkkingdee.top/Article/details/gtinvapofb.html

[S58] C++：命名空间
来源：http://dali.wangshuangyany.cn/Article/details/gtuctylgfr.html

namespace ns { int f() { return 1; } }
来源：http://dali.xylfe.cn/Article/details/gtwvnshzgq.html

[S59] C++：静态断言
来源：http://dali.yvedp.cn/Article/details/gtrflybyue.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yuxming.cn/Article/details/gtpdwudsnm.html

[S60] C++：遍历并删除元素
来源：http://dali.hnxiangtu.top/Article/details/gtjgffheti.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.316326.xyz/Article/details/gtajigiqzn.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtkzzfbnkt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sufxvd.cn/Article/details/gtjxavdqef.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtgxasaimc.html

[T01] Kotlin：Hello World
来源：http://dali.yongpay.top/Article/details/gtkuivnqkv.html

println("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwebqswkk.html

[T02] Kotlin：变量
来源：http://dali.fengsongda.top/Article/details/gtdzxjchkm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.vqdsnc.cn/Article/details/gtywxbjtta.html

[T03] Kotlin：字符串模板
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdwtcwqxt.html

"值: $b"
来源：http://dali.gaohongyu789.top/Article/details/gtxvatgnqc.html

[T04] Kotlin：空安全
来源：http://dali.xinyue.icu/Article/details/gtkirgyjsa.html

val n: String? = null;  n?.length
来源：http://dali.andypj.xyz/Article/details/gtyupvqtoj.html

[T05] Kotlin：when 表达式
来源：http://dali.yonumen.top/Article/details/gtkhnlmfkk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yongpay.top/Article/details/gtumumllov.html

[T06] Kotlin：集合映射
来源：http://dali.pengpengdd.cyou/Article/details/gtmfquhyzc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenzaomai.com/Article/details/gtjxcrfjpo.html

[T07] Kotlin：集合过滤
来源：http://dali.hysaishi.cn/Article/details/gtezbkmqoo.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yuanzhike.top/Article/details/gtdvqhnnsk.html

[T08] Kotlin：数据类
来源：http://dali.jyoumei.cn/Article/details/gtojmmiory.html

data class User(val name: String, val age: Int)
来源：http://dali.9152youxi.cn/Article/details/gtkrulshcd.html

[T09] Kotlin：扩展函数
来源：http://dali.dashuyun.cn/Article/details/gtmmeucvml.html

fun String.exclaim() = this + "!"
来源：http://dali.zhengqikj.top/Article/details/gtsdafhfyo.html

[T10] Kotlin：默认参数
来源：http://dali.daxiang520.top/Article/details/gtzlrursvr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jianghu66.top/Article/details/gtqzjzesxf.html

[T11] Kotlin：协程
来源：http://dali.yangfankeji.com/Article/details/gtusmbnxcl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jiagoushi.top/Article/details/gtlcrmislu.html

[T12] Kotlin：解构声明
来源：http://dali.cashguo.top/Article/details/gtohnqjfjf.html

val (a, b) = Pair(1, 2)
来源：http://dali.yuxming.cn/Article/details/gtmryjfals.html

[T13] Kotlin：只读 Map
来源：http://dali.birdmap.top/Article/details/gtehireytz.html

val m = mapOf("a" to 1)
来源：http://dali.zhengqikj.top/Article/details/gtoklfbxwk.html

[T14] Kotlin：循环
来源：http://dali.dashuyun.cn/Article/details/gtkoxqzswe.html

for (i in 1..10) println(i)
来源：http://dali.hammf.cn/Article/details/gtmgjfqhbx.html

[T15] Kotlin：接口
来源：http://dali.jiagoushi.top/Article/details/gteqzrwgkn.html

interface Shape { fun area(): Double }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthppjuhid.html

[T16] Swift：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtbrehdfix.html

print("Hello")
来源：http://dali.yvedp.cn/Article/details/gtrworcrum.html

[T17] Swift：变量与常量
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqzvejafx.html

var a = 1;  let b = 2
来源：http://dali.smart0.xyz/Article/details/gtcegekmrv.html

[T18] Swift：字符串插值
来源：http://dali.ppjwa.cn/Article/details/gtrfgbyjjs.html

"值: \(b)"
来源：http://dali.tianlin.xyz/Article/details/gtlmqysbjx.html

[T19] Swift：可选绑定
来源：http://dali.feifeiyinyue.top/Article/details/gtrgfyawzm.html

if let n = opt { print(n) }
来源：http://dali.yangfankeji.com/Article/details/gtraxontvf.html

[T20] Swift：数组操作
来源：http://dali.wangshuangyany.cn/Article/details/gtpfzsoeca.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jinqigufen.top/Article/details/gtzajadwfs.html

[T21] Swift：遍历
来源：http://dali.mhx1999.top/Article/details/gtyxphjutn.html

for x in a { print(x) }
来源：http://dali.zdqjudy.top/Article/details/gtqcvcbguj.html

[T22] Swift：字典
来源：http://dali.cheryme.top/Article/details/gtznbsnlzq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ydzc1.top/Article/details/gtfzyutorg.html

[T23] Swift：函数
来源：http://dali.guowangkeji.top/Article/details/gtmowioxsj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.mhx1999.top/Article/details/gtcftylmmz.html

[T24] Swift：闭包
来源：http://dali.ybcxt.top/Article/details/gtcnzyuvcy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yuxming.cn/Article/details/gtdhufppef.html

[T25] Swift：结构体
来源：http://dali.tianlin.xyz/Article/details/gtbsflfnal.html

struct P { var x: Int }
来源：http://dali.cucudq.cn/Article/details/gtljxdurfs.html

[T26] Swift：类与重写
来源：http://dali.9152youxi.cn/Article/details/gteiguhrcc.html

class A: Base { override func f() {} }
来源：http://dali.yueranfly.top/Article/details/gtevpwcvgh.html

[T27] Swift：错误处理
来源：http://dali.hnxiangtu.top/Article/details/gtrdswezyq.html

do { try f() } catch { print(error) }
来源：http://dali.0kj1m.cn/Article/details/gtajtxkpgl.html

[T28] Swift：枚举
来源：http://dali.yonumen.top/Article/details/gtfgmaitow.html

enum Color { case red, green }
来源：http://dali.zhixingplan.top/Article/details/gtlzjdzxio.html

[T29] Swift：guard 提前返回
来源：http://dali.yuxming.cn/Article/details/gtvocfetbj.html

guard let x = opt else { return }
来源：http://dali.guowangkeji.top/Article/details/gtujtunnse.html

[T30] Swift：协议
来源：http://dali.dashuyun.cn/Article/details/gtcndrphzo.html

protocol Shape { func area() -> Double }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxcinelhn.html

[T31] Lua：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtotggnaip.html

print("Hello")
来源：http://dali.cqqwz.cn/Article/details/gtfkjxsihv.html

[T32] Lua：局部变量
来源：http://dali.zycfv.cn/Article/details/gtxhqlixtg.html

local a = 1
来源：http://dali.fengsongda.top/Article/details/gtfevfjidx.html

[T33] Lua：表（数组）
来源：http://dali.gzhubu.top/Article/details/gtjfcmmuaf.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cucudq.cn/Article/details/gtdkucdxqi.html

[T34] Lua：遍历表
来源：http://dali.jqgufenzy.top/Article/details/gtfuhiuzqt.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.daria6918.cn/Article/details/gtzrcdevyl.html

[T35] Lua：字典表
来源：http://dali.guannengcc.top/Article/details/gtnawpfuue.html

local d = { a = 1 };  d.b = 2
来源：http://dali.nanxuanxn.top/Article/details/gtputiaaii.html

[T36] Lua：函数
来源：http://dali.cqqwz.cn/Article/details/gtlbbjlivk.html

function add(a, b) return a + b end
来源：http://dali.cqqwz.cn/Article/details/gtwwyetiwq.html

[T37] Lua：字符串拼接
来源：http://dali.andypj.xyz/Article/details/gtuandmviu.html

"a" .. "b"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjxwusdeu.html

[T38] Lua：条件
来源：http://dali.ehwqpu.com/Article/details/gtfhutifwo.html

if x > 0 then print("正") end
来源：http://dali.zhoulong.xyz/Article/details/gtdmuzyzvb.html

[T39] Lua：模式匹配
来源：http://dali.zhengqikj.top/Article/details/gtxazbsodp.html

string.find(s, "%d+")
来源：http://dali.gogol.net.cn/Article/details/gtkorvxzyu.html

[T40] Lua：元表
来源：http://dali.meibo888.top/Article/details/gtqivdfprs.html

setmetatable({}, { __index = base })
来源：http://dali.yj20258.top/Article/details/gtkonnhqto.html

[T41] Perl：Hello World
来源：http://dali.cucudq.cn/Article/details/gthbpwsgah.html

print "Hello\n";
来源：http://dali.aizwys.cn/Article/details/gtsrnvjosg.html

[T42] Perl：变量类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtobotxlqy.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.havefunace.top/Article/details/gtnnztjhwt.html

[T43] Perl：字符串插值
来源：http://dali.316326.xyz/Article/details/gttcppvicf.html

"值: $a"
来源：http://dali.ybcxt.top/Article/details/gtgbuihvqr.html

[T44] Perl：条件
来源：http://dali.zhiwuduotai.top/Article/details/gtmowrzpks.html

if ($a > 0) { print "正"; }
来源：http://dali.xinyue.icu/Article/details/gtuajixwxo.html

[T45] Perl：数组遍历
来源：http://dali.sufxvd.cn/Article/details/gtrwtngomg.html

for my $x (@arr) { print $x; }
来源：http://dali.yongpay.top/Article/details/gtfsxidigg.html

[T46] Perl：哈希操作
来源：http://dali.nwbrower.top/Article/details/gtjeznsljm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yongpay.top/Article/details/gtkfjqcgym.html

[T47] Perl：正则捕获
来源：http://dali.fzhhl.top/Article/details/gtspcfhuin.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.chenlongwang.top/Article/details/gttualmcco.html

[T48] Perl：正则替换
来源：http://dali.sxryk.cn/Article/details/gtykooaatw.html

$s =~ s/old/new/g;
来源：http://dali.nanxinkj.top/Article/details/gtvuauaecx.html

[T49] Perl：函数
来源：http://dali.andypj.xyz/Article/details/gtzwftovoe.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yanxiufei.cn/Article/details/gtuliuvojy.html

[T50] Perl：逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gtlswdpxij.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.sweek.top/Article/details/gtjybwnjid.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.316326.xyz/Article/details/gtgavcttln.html

[T51] Scala：Hello World
来源：http://dali.hammf.cn/Article/details/gtjoexuzka.html

println("Hello")
来源：http://dali.zdqjudy.top/Article/details/gtnqefcvnw.html

[T52] Scala：变量
来源：http://dali.dashuyun.cn/Article/details/gtapelxafi.html

val a = 1;  var b = 2
来源：http://dali.sysykeji.top/Article/details/gtefukwfbv.html

[T53] Scala：字符串插值
来源：http://dali.pycfn.com/Article/details/gtyupiicrz.html

s"值: $b"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsaeizknh.html

[T54] Scala：集合映射
来源：http://dali.havefunace.top/Article/details/gtibhiaejd.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.mhx1999.top/Article/details/gtthwjevqt.html

[T55] Scala：集合过滤
来源：http://dali.gaohongyu789.top/Article/details/gtlagcmbjl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.wangshuangyany.cn/Article/details/gtgxhrevqq.html

[T56] Scala：样例类
来源：http://dali.jianghu66.top/Article/details/gtvjmwecit.html

case class User(name: String, age: Int)
来源：http://dali.jyoumei.cn/Article/details/gtzglpslhy.html

[T57] Scala：模式匹配
来源：http://dali.cqqwz.cn/Article/details/gthnhshkpn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.guowangkeji.top/Article/details/gtstrvoatd.html

[T58] Scala：函数定义
来源：http://dali.iojbl.cn/Article/details/gttumhnvuh.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.yj202588.top/Article/details/gtfvndsmpg.html

[T59] Scala：循环
来源：http://dali.9152youxi.cn/Article/details/gtzzaoszgl.html

for (i <- 1 to 10) println(i)
来源：http://dali.jiagoushi.top/Article/details/gtdehqbeuu.html

[T60] Scala：折叠
来源：http://dali.yuanzhike.top/Article/details/gtrjpbcsxj.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpyyzhpgp.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtlhgdblzl.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhiwuduotai.top/Article/details/gtfnduyiqh.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtnlcvdmmm.html

[U01] Py：创建虚拟环境
来源：http://dali.hfpthk.cn/Article/details/gtaxmgiubv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xuetiantiany.cn/Article/details/gtdgwnazbb.html

[U02] Py：导出 / 安装依赖
来源：http://dali.havefunace.top/Article/details/gtbzvrmmas.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gtboeflkwj.html

[U03] Py：加载 .env 配置
来源：http://dali.shangyingyoupin.top/Article/details/gtnbbmnxcw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhoulong.xyz/Article/details/gtrippbuya.html

[U04] Py：变量调试打印
来源：http://dali.yj20258888.top/Article/details/gtvuwdwxic.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yj20258888.top/Article/details/gtwxqvilit.html

[U05] Py：列表去重且保序
来源：http://dali.jiagoushi.top/Article/details/gtolxiojtr.html

list(dict.fromkeys(arr))
来源：http://dali.chenjidiqi.icu/Article/details/gtzsjcaiqn.html

[U06] Py：合并两个字典
来源：http://dali.gzhubu.top/Article/details/gtjqdmnmxp.html

{**a, **b}
来源：http://dali.tianlin.xyz/Article/details/gtzluiqjds.html

[U07] Py：反转字典键值
来源：http://dali.zhixingplan.top/Article/details/gtpnbuozfu.html

{v: k for k, v in d.items()}
来源：http://dali.dianchejie.cn/Article/details/gtcgedeevy.html

[U08] Py：展平二维列表
来源：http://dali.316326.xyz/Article/details/gthglxdcxx.html

[y for x in nested for y in x]
来源：http://dali.chenlongwang.top/Article/details/gtjxeggxus.html

[U09] Py：字典取最大值的键
来源：http://dali.shangyingyoupin.top/Article/details/gtewgmcmnk.html

max(d, key=d.get)
来源：http://dali.haohaochexian.top/Article/details/gtsdhlecrv.html

[U10] Py：按值排序字典
来源：http://dali.gzhubu.top/Article/details/gtaqtmucoh.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.jiagoushi.top/Article/details/gtnmtrcmcc.html


<!-- 参考信息 -->