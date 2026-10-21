代发 wailian999

head -c 16 /dev/urandom | base64
来源：http://dali.yj20258888.top/Article/details/gtgscsifcm.html

[R70] 时间戳与互转
来源：http://dali.jqgufenzy.top/Article/details/gtzumhtgya.html

date +%s;  date -d @1700000000
来源：http://dali.kuanghao11.cn/Article/details/gtrvcqifmw.html

[R71] 日期格式化
来源：http://dali.shanyushiyangtech.top/Article/details/gtzajgouuf.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.redwolf501.top/Article/details/gtavrwrbaf.html

[R72] 等待端口就绪
来源：http://dali.jqgufenzy.top/Article/details/gtosocjcfy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ybcxt.top/Article/details/gtogffsvap.html

[R73] 分割大日志
来源：http://dali.jiagoushi.top/Article/details/gtmnsktqye.html

split -l 1000 big.log part_
来源：http://dali.shangyingyoupin.top/Article/details/gtxcafbuvl.html

[R74] 批量重命名
来源：http://dali.chenjidiqi.icu/Article/details/gtnrsbbugl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xziqi.cn/Article/details/gtihybgxlz.html

[R75] 导出环境变量
来源：http://dali.cucudq.cn/Article/details/gtbrbhgwzq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.meibo888.top/Article/details/gtegmajhge.html

[R76] 使用临时文件
来源：http://dali.aizwys.cn/Article/details/gthknmmumu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuetiantiany.cn/Article/details/gtjtdnmowt.html

[R77] 读取用户输入
来源：http://dali.chenjidiqi.icu/Article/details/gtntxgdnqo.html

read -rp "请输入: " ans
来源：http://dali.zycfv.cn/Article/details/gtdtjcgcah.html

[R78] 交互式菜单
来源：http://dali.redwolf501.top/Article/details/gtkqlngqgj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.tanke756.top/Article/details/gtglbjubfl.html

[R79] 解析命令行选项
来源：http://dali.316326.xyz/Article/details/gtthmkxlxt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpucappms.html

[R80] 查看脚本执行耗时
来源：http://dali.tianlin.xyz/Article/details/gtjezmloag.html

time ./run.sh
来源：http://dali.zhixingplan.top/Article/details/gtdpetvetj.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtxcwzpyqz.html

S. C / C++ 专题
来源：http://dali.sysykeji.top/Article/details/gtmuqearby.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtztrfcklp.html

[S01] C：Hello World
来源：http://dali.hammf.cn/Article/details/gtolqjxjdg.html

#include <stdio.h>
来源：http://dali.chenjidiqi.icu/Article/details/gtbdtrmyma.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.haohaochexian.top/Article/details/gthvsakuvw.html

[S02] C：变量与格式化输出
来源：http://dali.shangyingyoupin.top/Article/details/gtvfyavsvp.html

int a = 10; printf("%d\n", a);
来源：http://dali.bjfxy.top/Article/details/gtcbmibzsn.html

[S03] C：读入整数
来源：http://dali.shzxlz.cn/Article/details/gteczvrmdz.html

int x; scanf("%d", &x);
来源：http://dali.yj20258888.top/Article/details/gtmkgsbxvc.html

[S04] C：字符串复制
来源：http://dali.yj20258888.top/Article/details/gtbedlmzuu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yangfankeji.com/Article/details/gtfscjmtvb.html

[S05] C：字符串长度
来源：http://dali.ivvv.top/Article/details/gtcvrqxlqx.html

strlen(s)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkiooxmsy.html

[S06] C：字符串比较
来源：http://dali.jqgufenzy.top/Article/details/gthdcnylda.html

strcmp(a, b) == 0
来源：http://dali.hammf.cn/Article/details/gtmaombaxa.html

[S07] C：数组遍历求和
来源：http://dali.yongpay.top/Article/details/gtgvyzvpbk.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shanyushiyangkeji.top/Article/details/gttkeysgrh.html

[S08] C：动态内存分配与释放
来源：http://dali.aizwys.cn/Article/details/gtcidetdwf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtojcemkcj.html

[S09] C：结构体定义与初始化
来源：http://dali.snrcjt.cn/Article/details/gtiazxjeuj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.svipenyu.cn/Article/details/gtoblgcscn.html

[S10] C：指针与解引用
来源：http://dali.chenlongwang.top/Article/details/gttqobtpda.html

int *p = &a;  *p = 5;
来源：http://dali.xuanzx.com/Article/details/gtfegiyigo.html

[S11] C：逐行读文件
来源：http://dali.nanxinkj.top/Article/details/gtgqvumovj.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cashguo.top/Article/details/gtdrrtahml.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yj202588.top/Article/details/gtymtjrhar.html

fclose(f);
来源：http://dali.shzxlz.cn/Article/details/gtyjgepbxb.html

[S12] C：写文件
来源：http://dali.jinqigfzy.top/Article/details/gtdxblheqb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.aibaodan.cn/Article/details/gtgzxfkuxe.html

[S13] C：宏定义
来源：http://dali.9152youxi.cn/Article/details/gtiipzxsda.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.chenzaomai.com/Article/details/gtwmicmjot.html

[S14] C：枚举
来源：http://dali.xuanzx.com/Article/details/gtjsnbhrks.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.iojbl.cn/Article/details/gtwapzrdnn.html

[S15] C：类型转换
来源：http://dali.tanke756.top/Article/details/gtqupossuk.html

(double) a / b
来源：http://dali.feifeiyinyue.top/Article/details/gtqvzsfasl.html

[S16] C：位操作置位
来源：http://dali.zhiwuduotai.top/Article/details/gtyvtxjvlm.html

x |= (1 << 3);
来源：http://dali.guannengcc.top/Article/details/gtzqlxlujh.html

[S17] C：安全拼接字符串
来源：http://dali.316326.xyz/Article/details/gtbskjwncl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sxryk.cn/Article/details/gtcipkuolw.html

[S18] C：命令行参数
来源：http://dali.shzxlz.cn/Article/details/gtejgpquqd.html

int main(int argc, char **argv)
来源：http://dali.zhiwuduotai.top/Article/details/gturjzasqm.html

[S19] C：快速排序
来源：http://dali.hywenlv.cn/Article/details/gtzawyeyry.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangtech.top/Article/details/gtilpzofca.html

[S20] C：二分查找
来源：http://dali.hnqzz.top/Article/details/gtdyritzfc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gtqnwwbpzu.html

[S21] C：字符类别判断
来源：http://dali.zhongyouzk.top/Article/details/gtzdviiivv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yj20258.top/Article/details/gtzashjaao.html

[S22] C：字符串转数字
来源：http://dali.ybcxt.top/Article/details/gtghgtkpex.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hnqzz.top/Article/details/gtxgqdpdod.html

[S23] C：随机数
来源：http://dali.ybcxt.top/Article/details/gtszxfwybg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sxryk.cn/Article/details/gtglacsxdc.html

[S24] C：获取本地时间
来源：http://dali.gaohongyu789.top/Article/details/gtpwfvopod.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.chenjidiqi.icu/Article/details/gtfdjvfiic.html

[S25] C：内存拷贝
来源：http://dali.dianchejie.cn/Article/details/gtxgonewzq.html

memcpy(dst, src, n);
来源：http://dali.cdnleiting.top/Article/details/gtvncxchpk.html

[S26] C：内存清零
来源：http://dali.pengpengdd.cyou/Article/details/gtkbmkutpe.html

memset(a, 0, sizeof a);
来源：http://dali.ivvv.top/Article/details/gtkgvesgmt.html

[S27] C：定义常量
来源：http://dali.zdqjudy.top/Article/details/gtqqpovpxz.html

const double PI = 3.14159;
来源：http://dali.zhixingplan.top/Article/details/gteeasxvjm.html

[S28] C：静态变量
来源：http://dali.wangdashe.top/Article/details/gtqalbfhle.html

static int counter = 0;
来源：http://dali.ydzc1.top/Article/details/gtbmqwknri.html

[S29] C：变参函数
来源：http://dali.yvedp.cn/Article/details/gtlfrvwmby.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cqqwz.cn/Article/details/gtgdcdohbj.html

[S30] C：头文件保护
来源：http://dali.jianghu66.top/Article/details/gtdzsvaxvx.html

#ifndef X_H
来源：http://dali.pycfn.com/Article/details/gtlzguhpqz.html

#define X_H
来源：http://dali.bjfxy.top/Article/details/gtsuhtyfmp.html

#endif
来源：http://dali.fzhhl.top/Article/details/gtcjnzfvvy.html

[S31] C++：Hello World
来源：http://dali.yonumen.top/Article/details/gttkxnmvnb.html

#include <iostream>
来源：http://dali.meibo888.top/Article/details/gtzkasrnlh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cheryme.top/Article/details/gtbmvrcupo.html

[S32] C++：字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtlqdaqduq.html

std::string s = "hi";  s += "!";
来源：http://dali.jqgufenzy.top/Article/details/gtglfxpptn.html

[S33] C++：vector 增删
来源：http://dali.yueranfly.top/Article/details/gtzppzhdik.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.iojbl.cn/Article/details/gtaknluftz.html

[S34] C++：遍历 vector
来源：http://dali.chenlongwang.top/Article/details/gtlofmsyss.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ivvv.top/Article/details/gtcdxcgazc.html

[S35] C++：map
来源：http://dali.cashguo.top/Article/details/gtrfpltpmd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkqtvbpre.html

[S36] C++：unordered_map
来源：http://dali.daria6918.cn/Article/details/gtcxzgwvnk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258888.top/Article/details/gtlwumzezh.html

[S37] C++：set
来源：http://dali.316326.xyz/Article/details/gtfnecoeid.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsaydzffz.html

[S38] C++：排序
来源：http://dali.daria6918.cn/Article/details/gtvwuznqqi.html

std::sort(v.begin(), v.end());
来源：http://dali.gotoacloud.top/Article/details/gtczehgffx.html

[S39] C++：自定义比较器排序
来源：http://dali.ehwqpu.com/Article/details/gtwzcxriky.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.0kj1m.cn/Article/details/gtcjdeeowz.html

[S40] C++：查找元素
来源：http://dali.havefunace.top/Article/details/gtpqtkqkbh.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cucudq.cn/Article/details/gthvidhipw.html

[S41] C++：类与构造函数
来源：http://dali.jiagoushi.top/Article/details/gtqyzquhpo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yueranfly.top/Article/details/gtjaukibnn.html

[S42] C++：继承与虚函数
来源：http://dali.xylfe.cn/Article/details/gtmkkbseav.html

class B : public Base { public: void f() override {} };
来源：http://dali.daria6918.cn/Article/details/gtpdpmbyjj.html

[S43] C++：智能指针
来源：http://dali.cucudq.cn/Article/details/gtxzbciive.html

auto p = std::make_unique<int>(5);
来源：http://dali.gzhubu.top/Article/details/gtpxspenht.html

[S44] C++：引用传参
来源：http://dali.hfpthk.cn/Article/details/gteyslwbnp.html

void inc(int &x) { ++x; }
来源：http://dali.jlsjyb.cn/Article/details/gtxdvlclhu.html

[S45] C++：lambda
来源：http://dali.bjfxy.top/Article/details/gtuutkwjeg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nanxinkj.top/Article/details/gtwwipljhc.html

[S46] C++：函数模板
来源：http://dali.guannengcc.top/Article/details/gtzmrvvqjb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.guannengcc.top/Article/details/gtqxqqhvoo.html

[S47] C++：结构化绑定遍历
来源：http://dali.havefunace.top/Article/details/gtgslwvzaf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sysykeji.top/Article/details/gtpqxuhdxk.html

[S48] C++：逐行读文件
来源：http://dali.birdmap.top/Article/details/gtkszidsqy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hammf.cn/Article/details/gtslfhhexa.html

while (std::getline(in, line)) { }
来源：http://dali.hammf.cn/Article/details/gtmkovpmij.html

[S49] C++：写文件
来源：http://dali.nanxinkj.top/Article/details/gtjfvxeans.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.haohaochexian.top/Article/details/gtosgxpfuy.html

[S50] C++：格式化数字
来源：http://dali.zhiwuduotai.top/Article/details/gtpeblqjvv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.fengsongda.top/Article/details/gtplaabmeo.html

[S51] C++：显式类型转换
来源：http://dali.yuanzhike.top/Article/details/gtuyegevgo.html

static_cast<double>(a) / b
来源：http://dali.haohaochexian.top/Article/details/gtbbvhxbps.html

[S52] C++：const 与 noexcept
来源：http://dali.tanke756.top/Article/details/gtmpcznnuw.html

int size() const noexcept { return n_; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtjouwgmja.html

[S53] C++：移动语义
来源：http://dali.jqgfzy.top/Article/details/gtzkqphzgw.html

std::vector<int> w = std::move(v);
来源：http://dali.xuanzx.com/Article/details/gtpoxmbvkp.html

[S54] C++：异常处理
来源：http://dali.jlsjyb.cn/Article/details/gtydmoxtte.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yangfankeji.com/Article/details/gtrqtywwis.html

[S55] C++：结构化绑定
来源：http://dali.hnqzz.top/Article/details/gtzyhiuyzl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinghuilouyu.cn/Article/details/gtgyvfktmh.html

[S56] C++：optional
来源：http://dali.dashuyun.cn/Article/details/gtrecbgudk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hywenlv.cn/Article/details/gtjxyyxssi.html

[S57] C++：编译期常量
来源：http://dali.sysykeji.top/Article/details/gtkjrmtdki.html

constexpr int N = 10;
来源：http://dali.dianchejie.cn/Article/details/gtfdymfcpu.html

[S58] C++：命名空间
来源：http://dali.fengsongda.top/Article/details/gthkxqngav.html

namespace ns { int f() { return 1; } }
来源：http://dali.nanxuanxn.top/Article/details/gtaobqiuyu.html

[S59] C++：静态断言
来源：http://dali.zhengqikj.top/Article/details/gtuazbfwdq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.aibaodan.cn/Article/details/gtfcxhdphb.html

[S60] C++：遍历并删除元素
来源：http://dali.tianlin.xyz/Article/details/gtepwkznrt.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.wangshuangyany.cn/Article/details/gtqcqcmqdm.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gttffqbjhr.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.iojbl.cn/Article/details/gtvimaiukp.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtonqafpxq.html

[T01] Kotlin：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyoefrzfe.html

println("Hello")
来源：http://dali.sxryk.cn/Article/details/gtpwfqjtjb.html

[T02] Kotlin：变量
来源：http://dali.yongpay.top/Article/details/gtyrbtqwln.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hnxiangtu.top/Article/details/gtoubxdexj.html

[T03] Kotlin：字符串模板
来源：http://dali.shzxlz.cn/Article/details/gtyccjuoez.html

"值: $b"
来源：http://dali.smart0.xyz/Article/details/gtkplitvuq.html

[T04] Kotlin：空安全
来源：http://dali.cdnleiting.top/Article/details/gtyrowpzfn.html

val n: String? = null;  n?.length
来源：http://dali.tianlin.xyz/Article/details/gtklcazhcs.html

[T05] Kotlin：when 表达式
来源：http://dali.xuanzx.com/Article/details/gtrdsllhdd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hnqzz.top/Article/details/gtmntfvxwf.html

[T06] Kotlin：集合映射
来源：http://dali.sufxvd.cn/Article/details/gtraoaqmqb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sxryk.cn/Article/details/gtjhnkulza.html

[T07] Kotlin：集合过滤
来源：http://dali.zhijiandao.cn/Article/details/gtkvoyddqh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ehwqpu.com/Article/details/gtfmfcjuhm.html

[T08] Kotlin：数据类
来源：http://dali.jianghu66.top/Article/details/gtnrykwyrr.html

data class User(val name: String, val age: Int)
来源：http://dali.chenzaomai.com/Article/details/gtcfzvxbyx.html

[T09] Kotlin：扩展函数
来源：http://dali.svipenyu.cn/Article/details/gtaojucdfc.html

fun String.exclaim() = this + "!"
来源：http://dali.ppjwa.cn/Article/details/gtsywsjlms.html

[T10] Kotlin：默认参数
来源：http://dali.xuetiantiany.cn/Article/details/gtmwvcdmju.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ehwqpu.com/Article/details/gtchqjzerw.html

[T11] Kotlin：协程
来源：http://dali.jinyuanbaomall.cn/Article/details/gtohckjgtx.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yongpay.top/Article/details/gttjxyomfz.html

[T12] Kotlin：解构声明
来源：http://dali.jqgufenzy.top/Article/details/gtwesbtwsc.html

val (a, b) = Pair(1, 2)
来源：http://dali.dianchejie.cn/Article/details/gtpwybmaar.html

[T13] Kotlin：只读 Map
来源：http://dali.yj20258.top/Article/details/gtwtjvumxh.html

val m = mapOf("a" to 1)
来源：http://dali.sxryk.cn/Article/details/gtvegweicx.html

[T14] Kotlin：循环
来源：http://dali.zycfv.cn/Article/details/gtnvszknar.html

for (i in 1..10) println(i)
来源：http://dali.zycfv.cn/Article/details/gtkhjfjrdr.html

[T15] Kotlin：接口
来源：http://dali.feifeiyinyue.top/Article/details/gtbmigdchj.html

interface Shape { fun area(): Double }
来源：http://dali.zhijiandao.cn/Article/details/gtjduehczv.html

[T16] Swift：Hello World
来源：http://dali.fengsongda.top/Article/details/gtmlgjjogo.html

print("Hello")
来源：http://dali.iojbl.cn/Article/details/gtbnekmymv.html

[T17] Swift：变量与常量
来源：http://dali.zdqjudy.top/Article/details/gtgfzevhlk.html

var a = 1;  let b = 2
来源：http://dali.cucudq.cn/Article/details/gtiegjqqmp.html

[T18] Swift：字符串插值
来源：http://dali.shangyingyoupin.top/Article/details/gtofldgari.html

"值: \(b)"
来源：http://dali.hongshengwenyu.top/Article/details/gtrbdjmyol.html

[T19] Swift：可选绑定
来源：http://dali.zhiwuduotai.top/Article/details/gtgkwgbunu.html

if let n = opt { print(n) }
来源：http://dali.tanke756.top/Article/details/gtlmvdvqdc.html

[T20] Swift：数组操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpzgcnqad.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yanxiufei.cn/Article/details/gttlmykskl.html

[T21] Swift：遍历
来源：http://dali.zhoulong.xyz/Article/details/gtyhkcrrnu.html

for x in a { print(x) }
来源：http://dali.tianlin.xyz/Article/details/gtvxtxrugy.html

[T22] Swift：字典
来源：http://dali.feifeiyinyue.top/Article/details/gttfrwqzfx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.mhx1999.top/Article/details/gttkwfcxpb.html

[T23] Swift：函数
来源：http://dali.feifeiyinyue.top/Article/details/gtbbpoizhp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jianghu66.top/Article/details/gtmirsjzrb.html

[T24] Swift：闭包
来源：http://dali.hnxiangtu.top/Article/details/gtyzoeycta.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ydzc1.top/Article/details/gtjcxiabfk.html

[T25] Swift：结构体
来源：http://dali.yj20258888.top/Article/details/gtrenzlliy.html

struct P { var x: Int }
来源：http://dali.jiagoushi.top/Article/details/gtzknnuwak.html

[T26] Swift：类与重写
来源：http://dali.zdqjudy.top/Article/details/gtmotcqshz.html

class A: Base { override func f() {} }
来源：http://dali.nanxinkj.top/Article/details/gttmngtaow.html

[T27] Swift：错误处理
来源：http://dali.ydzc1.top/Article/details/gtfxmktcmh.html

do { try f() } catch { print(error) }
来源：http://dali.zhongyouzk.top/Article/details/gtrrgqxxnu.html

[T28] Swift：枚举
来源：http://dali.chenlongwang.top/Article/details/gtmbmfwqmp.html

enum Color { case red, green }
来源：http://dali.cdnleiting.top/Article/details/gtwlxoillz.html

[T29] Swift：guard 提前返回
来源：http://dali.gogol.net.cn/Article/details/gtmketcmcq.html

guard let x = opt else { return }
来源：http://dali.daxiang520.top/Article/details/gtulbostug.html

[T30] Swift：协议
来源：http://dali.jlsjyb.cn/Article/details/gtkaqykxvy.html

protocol Shape { func area() -> Double }
来源：http://dali.haohaochexian.top/Article/details/gtasesdbae.html

[T31] Lua：Hello World
来源：http://dali.hnqzz.top/Article/details/gtxcvcjndi.html

print("Hello")
来源：http://dali.bjfxy.top/Article/details/gtytvnigub.html

[T32] Lua：局部变量
来源：http://dali.ppjwa.cn/Article/details/gtrptesmzc.html

local a = 1
来源：http://dali.yj202588.top/Article/details/gtwplsshqs.html

[T33] Lua：表（数组）
来源：http://dali.shzxlz.cn/Article/details/gtjlcuhfxw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cdnleiting.top/Article/details/gtdtgbbydt.html

[T34] Lua：遍历表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtttwpwmby.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.vqdsnc.cn/Article/details/gtfrtftzkf.html

[T35] Lua：字典表
来源：http://dali.jinyuanbaomall.cn/Article/details/gthohaklrs.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhixingplan.top/Article/details/gtoxcytunm.html

[T36] Lua：函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjjvrkkxf.html

function add(a, b) return a + b end
来源：http://dali.zhongyouzk.top/Article/details/gtdrjazvif.html

[T37] Lua：字符串拼接
来源：http://dali.ehwqpu.com/Article/details/gtqofawtok.html

"a" .. "b"
来源：http://dali.xuanzx.com/Article/details/gtcyqgysib.html

[T38] Lua：条件
来源：http://dali.chenlongwang.top/Article/details/gtgcghgjxg.html

if x > 0 then print("正") end
来源：http://dali.tianlin.xyz/Article/details/gtymxzupmn.html

[T39] Lua：模式匹配
来源：http://dali.ydzc1.top/Article/details/gtfvgfcwmf.html

string.find(s, "%d+")
来源：http://dali.guowangkeji.top/Article/details/gtxlnnipnr.html

[T40] Lua：元表
来源：http://dali.meibo888.top/Article/details/gtqsfnilzy.html

setmetatable({}, { __index = base })
来源：http://dali.dianchejie.cn/Article/details/gtnlayuzwx.html

[T41] Perl：Hello World
来源：http://dali.ybcxt.top/Article/details/gttrcucwzb.html

print "Hello\n";
来源：http://dali.sweek.top/Article/details/gtrbybqodj.html

[T42] Perl：变量类型
来源：http://dali.yonumen.top/Article/details/gtpwexqxjs.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.aizwys.cn/Article/details/gtthbtjcfq.html

[T43] Perl：字符串插值
来源：http://dali.jlsjyb.cn/Article/details/gtpsdbukfn.html

"值: $a"
来源：http://dali.tanke756.top/Article/details/gtkrrpowbp.html

[T44] Perl：条件
来源：http://dali.yvedp.cn/Article/details/gtyqxuzpmh.html

if ($a > 0) { print "正"; }
来源：http://dali.sysykeji.top/Article/details/gtiqbvaavz.html

[T45] Perl：数组遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtwkltaptb.html

for my $x (@arr) { print $x; }
来源：http://dali.xylfe.cn/Article/details/gtqwrwejzi.html

[T46] Perl：哈希操作
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxhdodybe.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.guowangkeji.top/Article/details/gtpmemewac.html

[T47] Perl：正则捕获
来源：http://dali.sxryk.cn/Article/details/gtigkxyaue.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.tian-w.cn/Article/details/gtqredfgxn.html

[T48] Perl：正则替换
来源：http://dali.jianghu66.top/Article/details/gtweyjmwma.html

$s =~ s/old/new/g;
来源：http://dali.dianchejie.cn/Article/details/gtfkfrvqmv.html

[T49] Perl：函数
来源：http://dali.gaohongyu789.top/Article/details/gtqeoffcfs.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jiagoushi.top/Article/details/gtkgaovzfh.html

[T50] Perl：逐行读文件
来源：http://dali.aizwys.cn/Article/details/gtozwguncf.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.haohaochexian.top/Article/details/gtjhfigqbx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.pycfn.com/Article/details/gtjlxfunum.html

[T51] Scala：Hello World
来源：http://dali.hammf.cn/Article/details/gtgoudloyc.html

println("Hello")
来源：http://dali.tanke756.top/Article/details/gtweguvosw.html

[T52] Scala：变量
来源：http://dali.hfpthk.cn/Article/details/gtnloqsqqn.html

val a = 1;  var b = 2
来源：http://dali.kuanghao11.cn/Article/details/gtrxgrsjcx.html

[T53] Scala：字符串插值
来源：http://dali.ppjwa.cn/Article/details/gtutzybshr.html

s"值: $b"
来源：http://dali.xuetiantiany.cn/Article/details/gtrqlpcoee.html

[T54] Scala：集合映射
来源：http://dali.fengsongda.top/Article/details/gtruizkjii.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhongyouzk.top/Article/details/gtxslfyrow.html

[T55] Scala：集合过滤
来源：http://dali.shzxlz.cn/Article/details/gtmruovbcf.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.guannengcc.top/Article/details/gtztskiduc.html

[T56] Scala：样例类
来源：http://dali.fzhhl.top/Article/details/gtgvhfdxyg.html

case class User(name: String, age: Int)
来源：http://dali.shuidangran.top/Article/details/gtvjznnwaf.html

[T57] Scala：模式匹配
来源：http://dali.sweek.top/Article/details/gtizsoqhsr.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.daria6918.cn/Article/details/gthvclvqmc.html

[T58] Scala：函数定义
来源：http://dali.zhoulong.xyz/Article/details/gtwkrcjixf.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.nanxinkj.top/Article/details/gtuxzytzsm.html

[T59] Scala：循环
来源：http://dali.guannengcc.top/Article/details/gtlhuhwecp.html

for (i <- 1 to 10) println(i)
来源：http://dali.yj20258888.top/Article/details/gtrhbrjsgc.html

[T60] Scala：折叠
来源：http://dali.yongpay.top/Article/details/gtggtsyyun.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.zhongyouzk.top/Article/details/gtnmvqxmja.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtjcsfrgbk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrqbquqec.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtaxsloxde.html

[U01] Py：创建虚拟环境
来源：http://dali.nanxinkj.top/Article/details/gtjduuoxca.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.birdmap.top/Article/details/gtjuocjljp.html

[U02] Py：导出 / 安装依赖
来源：http://dali.xziqi.cn/Article/details/gthbjvfnqs.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.nwbrower.top/Article/details/gtpbrwqxwv.html

[U03] Py：加载 .env 配置
来源：http://dali.c1oappe.top/Article/details/gtlbppmnhd.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.gaohongyu789.top/Article/details/gtwnwgqkjc.html

[U04] Py：变量调试打印
来源：http://dali.quarkkingdee.top/Article/details/gtpqkrcygv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnyjepvgv.html

[U05] Py：列表去重且保序
来源：http://dali.fengsongda.top/Article/details/gtwutxcchp.html

list(dict.fromkeys(arr))
来源：http://dali.jlsjyb.cn/Article/details/gtuytygjxg.html

[U06] Py：合并两个字典
来源：http://dali.yangfankeji.com/Article/details/gtrfktwfxp.html

{**a, **b}
来源：http://dali.nwbrower.top/Article/details/gtvamlzxvd.html

[U07] Py：反转字典键值
来源：http://dali.aibaodan.cn/Article/details/gtjhbdgdxh.html

{v: k for k, v in d.items()}
来源：http://dali.zhixingplan.top/Article/details/gtzfblxlor.html

[U08] Py：展平二维列表
来源：http://dali.shangyingyoupin.top/Article/details/gtjfuwenou.html

[y for x in nested for y in x]
来源：http://dali.cashguo.top/Article/details/gtvkrcfgnt.html

[U09] Py：字典取最大值的键
来源：http://dali.yueranfly.top/Article/details/gtzahlbebv.html

max(d, key=d.get)
来源：http://dali.andypj.xyz/Article/details/gtecqjtgkk.html

[U10] Py：按值排序字典
来源：http://dali.birdmap.top/Article/details/gtksoryupx.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.nanxinkj.top/Article/details/gtpxqotxny.html


<!-- 参考信息 -->