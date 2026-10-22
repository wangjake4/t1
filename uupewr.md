代发 wailian999

split -l 1000 big.log part_
来源：http://dali.jyoumei.cn/Article/details/gt2ggkdlrti.html

[R74] 批量重命名
来源：http://dali.xuanzx.com/Article/details/gt2wgtxcgbw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.birdmap.top/Article/details/gt2xwganfut.html

[R75] 导出环境变量
来源：http://dali.aizwys.cn/Article/details/gt2hecepjai.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.snrcjt.cn/Article/details/gt2sxfqwfrq.html

[R76] 使用临时文件
来源：http://dali.hammf.cn/Article/details/gt2cdczvvwp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigufen.top/Article/details/gt2flpcisoa.html

[R77] 读取用户输入
来源：http://dali.zhixingplan.top/Article/details/gt2zkeaygro.html

read -rp "请输入: " ans
来源：http://dali.feifeiyinyue.top/Article/details/gt2tzforlfm.html

[R78] 交互式菜单
来源：http://dali.hnxiangtu.top/Article/details/gt2jkxkvrxz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hammf.cn/Article/details/gt2hdtlwyds.html

[R79] 解析命令行选项
来源：http://dali.jqgufenzy.top/Article/details/gt2rvmjcbmi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.kuanghao11.cn/Article/details/gt2awesedeh.html

[R80] 查看脚本执行耗时
来源：http://dali.xinyue.icu/Article/details/gt2rslkneok.html

time ./run.sh
来源：http://dali.yongpay.top/Article/details/gt2lybgeudc.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gt2xlafwdfu.html

S. C / C++ 专题
来源：http://dali.birdmap.top/Article/details/gt2rmdawkzq.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2vdmqfrau.html

[S01] C：Hello World
来源：http://dali.smart0.xyz/Article/details/gt2fnhsgdeo.html

#include <stdio.h>
来源：http://dali.ybcxt.top/Article/details/gt2lcqcruma.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.nanxinkj.top/Article/details/gt2txoxozez.html

[S02] C：变量与格式化输出
来源：http://dali.zhengqikj.top/Article/details/gt2aqcnpupi.html

int a = 10; printf("%d\n", a);
来源：http://dali.cdnleiting.top/Article/details/gt2tkkenlyg.html

[S03] C：读入整数
来源：http://dali.snrcjt.cn/Article/details/gt2xyfpqybx.html

int x; scanf("%d", &x);
来源：http://dali.fengsongda.top/Article/details/gt2mgrewiat.html

[S04] C：字符串复制
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cjpalgoo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xuanzx.com/Article/details/gt2mjndctxz.html

[S05] C：字符串长度
来源：http://dali.c1oappe.top/Article/details/gt2mudszeyl.html

strlen(s)
来源：http://dali.zdqjudy.top/Article/details/gt2pidpexny.html

[S06] C：字符串比较
来源：http://dali.nwbrower.top/Article/details/gt2bqnuleka.html

strcmp(a, b) == 0
来源：http://dali.yuxming.cn/Article/details/gt2jafqqpvu.html

[S07] C：数组遍历求和
来源：http://dali.jinqigfzy.top/Article/details/gt2vmhpttss.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.tianlin.xyz/Article/details/gt2ekgjknun.html

[S08] C：动态内存分配与释放
来源：http://dali.fzhhl.top/Article/details/gt2xkvjvugk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.316326.xyz/Article/details/gt2kzjyleao.html

[S09] C：结构体定义与初始化
来源：http://dali.guannengcc.top/Article/details/gt2xfemlsti.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.meibo888.top/Article/details/gt2dxnukijj.html

[S10] C：指针与解引用
来源：http://dali.xylfe.cn/Article/details/gt2emtdvrja.html

int *p = &a;  *p = 5;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2iyhdykkn.html

[S11] C：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gt2puwwvofv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zycfv.cn/Article/details/gt2szskpdzp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yanxiufei.cn/Article/details/gt2gnpjayqt.html

fclose(f);
来源：http://dali.zdqjudy.top/Article/details/gt2xfotrxzb.html

[S12] C：写文件
来源：http://dali.pycfn.com/Article/details/gt2uyzefsyq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jlsjyb.cn/Article/details/gt2ztblmypd.html

[S13] C：宏定义
来源：http://dali.jqgufenzy.top/Article/details/gt2pnypdwig.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.dashuyun.cn/Article/details/gt2uucnzrqk.html

[S14] C：枚举
来源：http://dali.vqdsnc.cn/Article/details/gt2mxibdyai.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.c1oappe.top/Article/details/gt2vvkodkgq.html

[S15] C：类型转换
来源：http://dali.cucudq.cn/Article/details/gt2zhznpyup.html

(double) a / b
来源：http://dali.ivvv.top/Article/details/gt2zdqpuswf.html

[S16] C：位操作置位
来源：http://dali.ybcxt.top/Article/details/gt2vzqvctbe.html

x |= (1 << 3);
来源：http://dali.hammf.cn/Article/details/gt2gdeylbcg.html

[S17] C：安全拼接字符串
来源：http://dali.andypj.xyz/Article/details/gt2ozltbqhk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.nanxinkj.top/Article/details/gt2vnefljjv.html

[S18] C：命令行参数
来源：http://dali.cqqwz.cn/Article/details/gt2rbvnuqyi.html

int main(int argc, char **argv)
来源：http://dali.yvedp.cn/Article/details/gt2gojmoicl.html

[S19] C：快速排序
来源：http://dali.quarkkingdee.top/Article/details/gt2jhqxboyh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cdnleiting.top/Article/details/gt2knhresyr.html

[S20] C：二分查找
来源：http://dali.jinqigufen.top/Article/details/gt2qwpkdqzd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.daria6918.cn/Article/details/gt2zynyqomv.html

[S21] C：字符类别判断
来源：http://dali.xziqi.cn/Article/details/gt2ktnufaxr.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dubfkgkc.html

[S22] C：字符串转数字
来源：http://dali.wangdashe.top/Article/details/gt2aqmfgviw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenzaomai.com/Article/details/gt2tuoyaeug.html

[S23] C：随机数
来源：http://dali.jlsjyb.cn/Article/details/gt2uxrequvr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.nanxinkj.top/Article/details/gt2irnqkspw.html

[S24] C：获取本地时间
来源：http://dali.havefunace.top/Article/details/gt2fubrdljx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gzhubu.top/Article/details/gt2omcedzfi.html

[S25] C：内存拷贝
来源：http://dali.hywenlv.cn/Article/details/gt2bfhjdgob.html

memcpy(dst, src, n);
来源：http://dali.xuanzx.com/Article/details/gt2masgyvbq.html

[S26] C：内存清零
来源：http://dali.daxiang520.top/Article/details/gt2khcshuao.html

memset(a, 0, sizeof a);
来源：http://dali.iojbl.cn/Article/details/gt2ttvjfueg.html

[S27] C：定义常量
来源：http://dali.ydzc1.top/Article/details/gt2nzwmofwu.html

const double PI = 3.14159;
来源：http://dali.wangshuangyany.cn/Article/details/gt2verkxpjo.html

[S28] C：静态变量
来源：http://dali.hysaishi.cn/Article/details/gt2gvwlmpkc.html

static int counter = 0;
来源：http://dali.dianchejie.cn/Article/details/gt2qacwalte.html

[S29] C：变参函数
来源：http://dali.quarkkingdee.top/Article/details/gt2siroogcq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cqqwz.cn/Article/details/gt2jfmspjjy.html

[S30] C：头文件保护
来源：http://dali.fengsongda.top/Article/details/gt2cvbgdexl.html

#ifndef X_H
来源：http://dali.sufxvd.cn/Article/details/gt2trxyanwh.html

#define X_H
来源：http://dali.sxryk.cn/Article/details/gt2hyviffok.html

#endif
来源：http://dali.sxryk.cn/Article/details/gt2ktgsrphy.html

[S31] C++：Hello World
来源：http://dali.hnqzz.top/Article/details/gt2bfykxebm.html

#include <iostream>
来源：http://dali.xylfe.cn/Article/details/gt2qivyavcg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shzxlz.cn/Article/details/gt2ahyhsvvs.html

[S32] C++：字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2fwkznmgr.html

std::string s = "hi";  s += "!";
来源：http://dali.feifeiyinyue.top/Article/details/gt2gtksyhbs.html

[S33] C++：vector 增删
来源：http://dali.gzhubu.top/Article/details/gt2ltpcvwyo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hnxiangtu.top/Article/details/gt2rstucmfr.html

[S34] C++：遍历 vector
来源：http://dali.wangdashe.top/Article/details/gt2lheeajkx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.redwolf501.top/Article/details/gt2rfrdqxqq.html

[S35] C++：map
来源：http://dali.aibaodan.cn/Article/details/gt2peyugiiw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jianghu66.top/Article/details/gt2qqqcksfy.html

[S36] C++：unordered_map
来源：http://dali.zhoulong.xyz/Article/details/gt2nhpbmgik.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.smart0.xyz/Article/details/gt2sgisrnix.html

[S37] C++：set
来源：http://dali.zhoulong.xyz/Article/details/gt2vsjgnnhm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cqqwz.cn/Article/details/gt2qvwxvhmu.html

[S38] C++：排序
来源：http://dali.tian-w.cn/Article/details/gt2xsapodwo.html

std::sort(v.begin(), v.end());
来源：http://dali.fengsongda.top/Article/details/gt2ongnelub.html

[S39] C++：自定义比较器排序
来源：http://dali.yj202588.top/Article/details/gt2wtlqqlvl.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.quarkkingdee.top/Article/details/gt2jeykayrf.html

[S40] C++：查找元素
来源：http://dali.zdqjudy.top/Article/details/gt2ayunakyd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sufxvd.cn/Article/details/gt2kgzxogmv.html

[S41] C++：类与构造函数
来源：http://dali.jinqigfzy.top/Article/details/gt2ayhztygr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xziqi.cn/Article/details/gt2losgwztn.html

[S42] C++：继承与虚函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uxlouooi.html

class B : public Base { public: void f() override {} };
来源：http://dali.zycfv.cn/Article/details/gt2jszpmccm.html

[S43] C++：智能指针
来源：http://dali.redwolf501.top/Article/details/gt2tpjisnvw.html

auto p = std::make_unique<int>(5);
来源：http://dali.sufxvd.cn/Article/details/gt2ehqkzsri.html

[S44] C++：引用传参
来源：http://dali.sufxvd.cn/Article/details/gt2ozpsreor.html

void inc(int &x) { ++x; }
来源：http://dali.quarkkingdee.top/Article/details/gt2pnfcwvrd.html

[S45] C++：lambda
来源：http://dali.daxiang520.top/Article/details/gt2xrvenffc.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yj202588.top/Article/details/gt2enbfkfgk.html

[S46] C++：函数模板
来源：http://dali.jiagoushi.top/Article/details/gt2tgmxztkv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.nanxinkj.top/Article/details/gt2mykfxicd.html

[S47] C++：结构化绑定遍历
来源：http://dali.kuanghao11.cn/Article/details/gt2nwcssvgo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jqgfzy.top/Article/details/gt2zleafmll.html

[S48] C++：逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gt2auabhszm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cmeoalhq.html

while (std::getline(in, line)) { }
来源：http://dali.shangyingyoupin.top/Article/details/gt2wwpftkvo.html

[S49] C++：写文件
来源：http://dali.daxiang520.top/Article/details/gt2qewlhwvi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hysaishi.cn/Article/details/gt2ytdqnlfp.html

[S50] C++：格式化数字
来源：http://dali.redwolf501.top/Article/details/gt2nmdnnkad.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gt2xfwnpwkd.html

[S51] C++：显式类型转换
来源：http://dali.jinqigufen.top/Article/details/gt2nutrebdf.html

static_cast<double>(a) / b
来源：http://dali.hongshengwenyu.top/Article/details/gt2yekplokd.html

[S52] C++：const 与 noexcept
来源：http://dali.hfpthk.cn/Article/details/gt2pusxshkk.html

int size() const noexcept { return n_; }
来源：http://dali.xziqi.cn/Article/details/gt2soqjgvkv.html

[S53] C++：移动语义
来源：http://dali.fengsongda.top/Article/details/gt2uhrffqfg.html

std::vector<int> w = std::move(v);
来源：http://dali.316326.xyz/Article/details/gt2vfixckkr.html

[S54] C++：异常处理
来源：http://dali.hnqzz.top/Article/details/gt2lzksdfyf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.316326.xyz/Article/details/gt2sceeycob.html

[S55] C++：结构化绑定
来源：http://dali.c1oappe.top/Article/details/gt2glllivfm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cashguo.top/Article/details/gt2qrewnzqn.html

[S56] C++：optional
来源：http://dali.fengsongda.top/Article/details/gt2yfyvorpj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yanxiufei.cn/Article/details/gt2loljlivk.html

[S57] C++：编译期常量
来源：http://dali.zhongyouzk.top/Article/details/gt2fcwvypdb.html

constexpr int N = 10;
来源：http://dali.yanxiufei.cn/Article/details/gt2eddwyebf.html

[S58] C++：命名空间
来源：http://dali.nanxinkj.top/Article/details/gt2pjsmfauo.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhoulong.xyz/Article/details/gt2jvguurng.html

[S59] C++：静态断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wpvsbnse.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.tian-w.cn/Article/details/gt2eggkxjcb.html

[S60] C++：遍历并删除元素
来源：http://dali.hnxiangtu.top/Article/details/gt2pgeekmmr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jyoumei.cn/Article/details/gt2auptcwbg.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2mqvrkbgo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gogol.net.cn/Article/details/gt2sgpvojgr.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gt2amcyonpk.html

[T01] Kotlin：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gt2kwxjjtsr.html

println("Hello")
来源：http://dali.gzhubu.top/Article/details/gt2latimtjb.html

[T02] Kotlin：变量
来源：http://dali.yueranfly.top/Article/details/gt2ysuoyfnz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hammf.cn/Article/details/gt2iulxcegi.html

[T03] Kotlin：字符串模板
来源：http://dali.yanxiufei.cn/Article/details/gt2yzhqsenq.html

"值: $b"
来源：http://dali.c1oappe.top/Article/details/gt2oddrfhst.html

[T04] Kotlin：空安全
来源：http://dali.yj20258.top/Article/details/gt2ecdjsggk.html

val n: String? = null;  n?.length
来源：http://dali.shzxlz.cn/Article/details/gt2ufobvnmg.html

[T05] Kotlin：when 表达式
来源：http://dali.fengsongda.top/Article/details/gt2vrpwtarz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.316326.xyz/Article/details/gt2lyfaldzh.html

[T06] Kotlin：集合映射
来源：http://dali.gzhubu.top/Article/details/gt2ofnmfcqb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sysykeji.top/Article/details/gt2nogdoena.html

[T07] Kotlin：集合过滤
来源：http://dali.cqqwz.cn/Article/details/gt2fwmpovys.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yanxiufei.cn/Article/details/gt2hmhebgbe.html

[T08] Kotlin：数据类
来源：http://dali.cdnleiting.top/Article/details/gt2edkvptaf.html

data class User(val name: String, val age: Int)
来源：http://dali.smart0.xyz/Article/details/gt2fqkwettc.html

[T09] Kotlin：扩展函数
来源：http://dali.gaohongyu789.top/Article/details/gt2uljbtipq.html

fun String.exclaim() = this + "!"
来源：http://dali.chenjidiqi.icu/Article/details/gt2cfdnuirs.html

[T10] Kotlin：默认参数
来源：http://dali.dashuyun.cn/Article/details/gt2xdbvluqj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.wangdashe.top/Article/details/gt2tbcsvwtg.html

[T11] Kotlin：协程
来源：http://dali.c1oappe.top/Article/details/gt2lsnurajm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.bjfxy.top/Article/details/gt2wknyajcb.html

[T12] Kotlin：解构声明
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yrxuyjer.html

val (a, b) = Pair(1, 2)
来源：http://dali.kuanghao11.cn/Article/details/gt2zblvdbof.html

[T13] Kotlin：只读 Map
来源：http://dali.redwolf501.top/Article/details/gt2ckvyfglt.html

val m = mapOf("a" to 1)
来源：http://dali.yvedp.cn/Article/details/gt2sgnefvgd.html

[T14] Kotlin：循环
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pammkqol.html

for (i in 1..10) println(i)
来源：http://dali.c1oappe.top/Article/details/gt2zpkgcpni.html

[T15] Kotlin：接口
来源：http://dali.yuxming.cn/Article/details/gt2qhuuxpwi.html

interface Shape { fun area(): Double }
来源：http://dali.pycfn.com/Article/details/gt2saqphprv.html

[T16] Swift：Hello World
来源：http://dali.jinqigufen.top/Article/details/gt2pqhwizmt.html

print("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gt2cmwyvxxo.html

[T17] Swift：变量与常量
来源：http://dali.hnxiangtu.top/Article/details/gt2cingizrs.html

var a = 1;  let b = 2
来源：http://dali.daxiang520.top/Article/details/gt2qmyzolrq.html

[T18] Swift：字符串插值
来源：http://dali.mhx1999.top/Article/details/gt2oejavepd.html

"值: \(b)"
来源：http://dali.aizwys.cn/Article/details/gt2dlbzxcfc.html

[T19] Swift：可选绑定
来源：http://dali.cheryme.top/Article/details/gt2cojqeviu.html

if let n = opt { print(n) }
来源：http://dali.cqqwz.cn/Article/details/gt2yedjmcsr.html

[T20] Swift：数组操作
来源：http://dali.hnqzz.top/Article/details/gt2nuwouqpl.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.chenlongwang.top/Article/details/gt2mdarjuzc.html

[T21] Swift：遍历
来源：http://dali.tian-w.cn/Article/details/gt2saliolnc.html

for x in a { print(x) }
来源：http://dali.zhengqikj.top/Article/details/gt2lvxxwhon.html

[T22] Swift：字典
来源：http://dali.ppjwa.cn/Article/details/gt2udrztyqs.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jianghu66.top/Article/details/gt2lznwugba.html

[T23] Swift：函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vyeshone.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ppjwa.cn/Article/details/gt2zzneoaxi.html

[T24] Swift：闭包
来源：http://dali.ybcxt.top/Article/details/gt2vsnfjchg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sufxvd.cn/Article/details/gt2anwdxqxz.html

[T25] Swift：结构体
来源：http://dali.andypj.xyz/Article/details/gt2ppfiobpp.html

struct P { var x: Int }
来源：http://dali.wangshuangyany.cn/Article/details/gt2zagdracz.html

[T26] Swift：类与重写
来源：http://dali.kuanghao11.cn/Article/details/gt2dewzevdm.html

class A: Base { override func f() {} }
来源：http://dali.yj20258.top/Article/details/gt2eogoplum.html

[T27] Swift：错误处理
来源：http://dali.zhiwuduotai.top/Article/details/gt2wciuvxqr.html

do { try f() } catch { print(error) }
来源：http://dali.zycfv.cn/Article/details/gt2uzdomtag.html

[T28] Swift：枚举
来源：http://dali.xuetiantiany.cn/Article/details/gt2kjbkdhip.html

enum Color { case red, green }
来源：http://dali.dianchejie.cn/Article/details/gt2fzaoclfk.html

[T29] Swift：guard 提前返回
来源：http://dali.zhengqikj.top/Article/details/gt2afvsmfbv.html

guard let x = opt else { return }
来源：http://dali.aibaodan.cn/Article/details/gt2woetmhlj.html

[T30] Swift：协议
来源：http://dali.chenlongwang.top/Article/details/gt2rtqdnush.html

protocol Shape { func area() -> Double }
来源：http://dali.jqgufenzy.top/Article/details/gt2ktrvesqe.html

[T31] Lua：Hello World
来源：http://dali.xylfe.cn/Article/details/gt2ezksorzf.html

print("Hello")
来源：http://dali.ybcxt.top/Article/details/gt2kjgvkbvj.html

[T32] Lua：局部变量
来源：http://dali.yuxming.cn/Article/details/gt2ldvdyxvo.html

local a = 1
来源：http://dali.zhongyouzk.top/Article/details/gt2uqxqehev.html

[T33] Lua：表（数组）
来源：http://dali.fengsongda.top/Article/details/gt2ihbwxusn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.guowangkeji.top/Article/details/gt2rgfferze.html

[T34] Lua：遍历表
来源：http://dali.smart0.xyz/Article/details/gt2teziuavg.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.redwolf501.top/Article/details/gt2fhrwzslp.html

[T35] Lua：字典表
来源：http://dali.aibaodan.cn/Article/details/gt2ycthrlyc.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shzxlz.cn/Article/details/gt2ncberufn.html

[T36] Lua：函数
来源：http://dali.ehwqpu.com/Article/details/gt2ntmndvcl.html

function add(a, b) return a + b end
来源：http://dali.cheryme.top/Article/details/gt2ziiqwdxj.html

[T37] Lua：字符串拼接
来源：http://dali.0kj1m.cn/Article/details/gt2cnqefmvr.html

"a" .. "b"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2idjwhtzz.html

[T38] Lua：条件
来源：http://dali.chenlongwang.top/Article/details/gt2wtztnzwt.html

if x > 0 then print("正") end
来源：http://dali.hongshengwenyu.top/Article/details/gt2usxetwia.html

[T39] Lua：模式匹配
来源：http://dali.zdqjudy.top/Article/details/gt2abvudztt.html

string.find(s, "%d+")
来源：http://dali.yonumen.top/Article/details/gt2xnpstzkd.html

[T40] Lua：元表
来源：http://dali.yongpay.top/Article/details/gt2kqeaxslo.html

setmetatable({}, { __index = base })
来源：http://dali.shzxlz.cn/Article/details/gt2egsbvihy.html

[T41] Perl：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2bzxmevhx.html

print "Hello\n";
来源：http://dali.0kj1m.cn/Article/details/gt2uywjoohu.html

[T42] Perl：变量类型
来源：http://dali.yj20258888.top/Article/details/gt2wmjdkvpq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.feifeiyinyue.top/Article/details/gt2iaoswotr.html

[T43] Perl：字符串插值
来源：http://dali.hammf.cn/Article/details/gt2enblxzyh.html

"值: $a"
来源：http://dali.jinqigfzy.top/Article/details/gt2rlqohhio.html

[T44] Perl：条件
来源：http://dali.xuanzx.com/Article/details/gt2iezexjpm.html

if ($a > 0) { print "正"; }
来源：http://dali.nanxuanxn.top/Article/details/gt2dylkxzqa.html

[T45] Perl：数组遍历
来源：http://dali.nanxinkj.top/Article/details/gt2hlwrunjf.html

for my $x (@arr) { print $x; }
来源：http://dali.dianchejie.cn/Article/details/gt2cidahtaa.html

[T46] Perl：哈希操作
来源：http://dali.nanxinkj.top/Article/details/gt2wlphzlfm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ivvv.top/Article/details/gt2aekbfibf.html

[T47] Perl：正则捕获
来源：http://dali.wangshuangyany.cn/Article/details/gt2bojxvqoh.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.hammf.cn/Article/details/gt2ciybzlom.html

[T48] Perl：正则替换
来源：http://dali.hfpthk.cn/Article/details/gt2dztpgdwe.html

$s =~ s/old/new/g;
来源：http://dali.cashguo.top/Article/details/gt2awbpuydw.html

[T49] Perl：函数
来源：http://dali.haohaochexian.top/Article/details/gt2clkvzigc.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.yuanzhike.top/Article/details/gt2eayqdgii.html

[T50] Perl：逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2rtddsdvg.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2sddncamo.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ivvv.top/Article/details/gt2yxuhybsv.html

[T51] Scala：Hello World
来源：http://dali.tanke756.top/Article/details/gt2xaovlehq.html

println("Hello")
来源：http://dali.0kj1m.cn/Article/details/gt2kfvomseg.html

[T52] Scala：变量
来源：http://dali.cashguo.top/Article/details/gt2pfctiwvm.html

val a = 1;  var b = 2
来源：http://dali.feifeiyinyue.top/Article/details/gt2tyetkaot.html

[T53] Scala：字符串插值
来源：http://dali.wangshuangyany.cn/Article/details/gt2koharxoh.html

s"值: $b"
来源：http://dali.yongpay.top/Article/details/gt2ttvxsjip.html

[T54] Scala：集合映射
来源：http://dali.aizwys.cn/Article/details/gt2hoyqbllf.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.zhengqikj.top/Article/details/gt2vocpcnho.html

[T55] Scala：集合过滤
来源：http://dali.ybcxt.top/Article/details/gt2xtzcobtr.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.tanke756.top/Article/details/gt2jbmshknt.html

[T56] Scala：样例类
来源：http://dali.cqqwz.cn/Article/details/gt2yuqucwdq.html

case class User(name: String, age: Int)
来源：http://dali.jqgufenzy.top/Article/details/gt2midxeadk.html

[T57] Scala：模式匹配
来源：http://dali.yangfankeji.com/Article/details/gt2hiykeyvn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.jqgfzy.top/Article/details/gt2bssqojff.html

[T58] Scala：函数定义
来源：http://dali.birdmap.top/Article/details/gt2rskoamhz.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.svipenyu.cn/Article/details/gt2neovkxvv.html

[T59] Scala：循环
来源：http://dali.sxryk.cn/Article/details/gt2khqxydjz.html

for (i <- 1 to 10) println(i)
来源：http://dali.hnqzz.top/Article/details/gt2smxtreta.html

[T60] Scala：折叠
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rbgzkxkz.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yongpay.top/Article/details/gt2qeseuibb.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vwkkypnu.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yonumen.top/Article/details/gt2vuyguavv.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2vsppcfeu.html

[U01] Py：创建虚拟环境
来源：http://dali.yongpay.top/Article/details/gt2gswakbth.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.zdqjudy.top/Article/details/gt2tcvcpgap.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hfpthk.cn/Article/details/gt2cogwosff.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hywenlv.cn/Article/details/gt2zdjpugoj.html

[U03] Py：加载 .env 配置
来源：http://dali.shzxlz.cn/Article/details/gt2nabvgpto.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.zhongyouzk.top/Article/details/gt2piqcemrr.html

[U04] Py：变量调试打印
来源：http://dali.zhixingplan.top/Article/details/gt2rebbeldv.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yj202588.top/Article/details/gt2crddhblf.html

[U05] Py：列表去重且保序
来源：http://dali.yongpay.top/Article/details/gt2zsgfphcs.html

list(dict.fromkeys(arr))
来源：http://dali.wangdashe.top/Article/details/gt2tqyjxfol.html

[U06] Py：合并两个字典
来源：http://dali.cdnleiting.top/Article/details/gt2vbqfxjdi.html

{**a, **b}
来源：http://dali.hongshengwenyu.top/Article/details/gt2gqbzzqpp.html

[U07] Py：反转字典键值
来源：http://dali.kuanghao11.cn/Article/details/gt2gpmuounz.html

{v: k for k, v in d.items()}
来源：http://dali.chenjidiqi.icu/Article/details/gt2hilfslft.html

[U08] Py：展平二维列表
来源：http://dali.daxiang520.top/Article/details/gt2tpatzgwx.html

[y for x in nested for y in x]
来源：http://dali.xinyue.icu/Article/details/gt2znzaoxcy.html

[U09] Py：字典取最大值的键
来源：http://dali.vqdsnc.cn/Article/details/gt2mzjnucis.html

max(d, key=d.get)
来源：http://dali.mhx1999.top/Article/details/gt2gmnepgvk.html

[U10] Py：按值排序字典
来源：http://dali.ehwqpu.com/Article/details/gt2qqgvlsmo.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.yj20258.top/Article/details/gt2hiezajrn.html

[U11] Py：生成器表达式
来源：http://dali.feifeiyinyue.top/Article/details/gt2ksuowevp.html

(x * 2 for x in arr)
来源：http://dali.0kj1m.cn/Article/details/gt2upxdtgww.html

[U12] Py：取出现最多的 3 个元素
来源：http://dali.yj20258.top/Article/details/gt2ldqlgrip.html

Counter(arr).most_common(3)
来源：http://dali.havefunace.top/Article/details/gt2cnxbgttf.html

[U13] Py：固定长度队列
来源：http://dali.jinghuilouyu.cn/Article/details/gt2plmoemvx.html

deque(maxlen=10)
来源：http://dali.hywenlv.cn/Article/details/gt2yoxkqtmi.html

[U14] Py：分组收集到列表
来源：http://dali.svipenyu.cn/Article/details/gt2hwlumetf.html

defaultdict(list)
来源：http://dali.tianlin.xyz/Article/details/gt2uhhkadmw.html


<!-- 参考信息 -->