代发 wailian999

head -c 16 /dev/urandom | base64
来源：http://dali.vqdsnc.cn/Article/details/gt2fwzxyypa.html

[R70] 时间戳与互转
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2govcwfrb.html

date +%s;  date -d @1700000000
来源：http://dali.yongpay.top/Article/details/gt2nafablbs.html

[R71] 日期格式化
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wilsurzj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xziqi.cn/Article/details/gt2qvknxbdi.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2wghugmif.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gotoacloud.top/Article/details/gt2gzpqraqg.html

[R73] 分割大日志
来源：http://dali.wangdashe.top/Article/details/gt2smefafsl.html

split -l 1000 big.log part_
来源：http://dali.zhixingplan.top/Article/details/gt2kwxlysoc.html

[R74] 批量重命名
来源：http://dali.xuanzx.com/Article/details/gt2egvkesiw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.havefunace.top/Article/details/gt2fbhtnxio.html

[R75] 导出环境变量
来源：http://dali.feifeiyinyue.top/Article/details/gt2rwvktkwi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yonumen.top/Article/details/gt2nhujecni.html

[R76] 使用临时文件
来源：http://dali.zdqjudy.top/Article/details/gt2neictejg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.0kj1m.cn/Article/details/gt2mgdcqybl.html

[R77] 读取用户输入
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2omujefcm.html

read -rp "请输入: " ans
来源：http://dali.wangdashe.top/Article/details/gt2wnhsfkjz.html

[R78] 交互式菜单
来源：http://dali.kuanghao11.cn/Article/details/gt2xdjhhyvo.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.fzhhl.top/Article/details/gt2ngzdgibv.html

[R79] 解析命令行选项
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2swaumfog.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cqqwz.cn/Article/details/gt2dcerwnjo.html

[R80] 查看脚本执行耗时
来源：http://dali.yvedp.cn/Article/details/gt2mpivfvtz.html

time ./run.sh
来源：http://dali.hywenlv.cn/Article/details/gt2fwgosibm.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2tjvnwahy.html

S. C / C++ 专题
来源：http://dali.nanxinkj.top/Article/details/gt2fqzsrdvf.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gt2cduoxkhm.html

[S01] C：Hello World
来源：http://dali.tianlin.xyz/Article/details/gt2hzylwgll.html

#include <stdio.h>
来源：http://dali.sufxvd.cn/Article/details/gt2hlijehbl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.svipenyu.cn/Article/details/gt2vokvpqgw.html

[S02] C：变量与格式化输出
来源：http://dali.yvedp.cn/Article/details/gt2nbundcyi.html

int a = 10; printf("%d\n", a);
来源：http://dali.snrcjt.cn/Article/details/gt2scnkpnci.html

[S03] C：读入整数
来源：http://dali.jinqigfzy.top/Article/details/gt2ldxlebuy.html

int x; scanf("%d", &x);
来源：http://dali.yueranfly.top/Article/details/gt2bxtfcusc.html

[S04] C：字符串复制
来源：http://dali.ydzc1.top/Article/details/gt2drisqyii.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.havefunace.top/Article/details/gt2ivmbdjlf.html

[S05] C：字符串长度
来源：http://dali.yvedp.cn/Article/details/gt2ztzeclav.html

strlen(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2rgzhsaey.html

[S06] C：字符串比较
来源：http://dali.cheryme.top/Article/details/gt2boxwjsfp.html

strcmp(a, b) == 0
来源：http://dali.yvedp.cn/Article/details/gt2lfnaajzw.html

[S07] C：数组遍历求和
来源：http://dali.birdmap.top/Article/details/gt2zqwvyqiw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ivvv.top/Article/details/gt2pzyjzdzs.html

[S08] C：动态内存分配与释放
来源：http://dali.aibaodan.cn/Article/details/gt2mdrsqdwj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xylfe.cn/Article/details/gt2anxjwynq.html

[S09] C：结构体定义与初始化
来源：http://dali.tianlin.xyz/Article/details/gt2ejkjftvd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gzhubu.top/Article/details/gt2panxhowi.html

[S10] C：指针与解引用
来源：http://dali.jqgufenzy.top/Article/details/gt2jujyebwo.html

int *p = &a;  *p = 5;
来源：http://dali.xinyue.icu/Article/details/gt2mpzglcir.html

[S11] C：逐行读文件
来源：http://dali.yj20258888.top/Article/details/gt2etbdkvgf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.svipenyu.cn/Article/details/gt2axherqvk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.smart0.xyz/Article/details/gt2dnclxanb.html

fclose(f);
来源：http://dali.shzxlz.cn/Article/details/gt2xunzbqmk.html

[S12] C：写文件
来源：http://dali.zhoulong.xyz/Article/details/gt2hnvojulz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.nanxuanxn.top/Article/details/gt2owuvejgi.html

[S13] C：宏定义
来源：http://dali.gogol.net.cn/Article/details/gt2blbfpixb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yuanzhike.top/Article/details/gt2orjwowan.html

[S14] C：枚举
来源：http://dali.yj20258888.top/Article/details/gt2fdjcfxlg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jiagoushi.top/Article/details/gt2lsvfwtuc.html

[S15] C：类型转换
来源：http://dali.nwbrower.top/Article/details/gt2zvxmnfis.html

(double) a / b
来源：http://dali.snrcjt.cn/Article/details/gt2mjamwgfa.html

[S16] C：位操作置位
来源：http://dali.zhengqikj.top/Article/details/gt2zwhhqvhm.html

x |= (1 << 3);
来源：http://dali.kuanghao11.cn/Article/details/gt2eqkmdayp.html

[S17] C：安全拼接字符串
来源：http://dali.xinyue.icu/Article/details/gt2osmunulj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenzaomai.com/Article/details/gt2ddmczoro.html

[S18] C：命令行参数
来源：http://dali.cashguo.top/Article/details/gt2qweyfyom.html

int main(int argc, char **argv)
来源：http://dali.tanke756.top/Article/details/gt2uonmwbup.html

[S19] C：快速排序
来源：http://dali.guannengcc.top/Article/details/gt2owlrzgyy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jlsjyb.cn/Article/details/gt2dbhfvxos.html

[S20] C：二分查找
来源：http://dali.bjfxy.top/Article/details/gt2ksdvinga.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jiagoushi.top/Article/details/gt2yuxplwvv.html

[S21] C：字符类别判断
来源：http://dali.xylfe.cn/Article/details/gt2avylanvy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xziqi.cn/Article/details/gt2cneutrdp.html

[S22] C：字符串转数字
来源：http://dali.bjfxy.top/Article/details/gt2nhtxfoqj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.9152youxi.cn/Article/details/gt2mrlzflza.html

[S23] C：随机数
来源：http://dali.zhixingplan.top/Article/details/gt2sdksjubk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xmmojcec.html

[S24] C：获取本地时间
来源：http://dali.meibo888.top/Article/details/gt2crtpkghq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xuetiantiany.cn/Article/details/gt2pwlrkrqx.html

[S25] C：内存拷贝
来源：http://dali.kuanghao11.cn/Article/details/gt2lpooettf.html

memcpy(dst, src, n);
来源：http://dali.ehwqpu.com/Article/details/gt2cwbqkthy.html

[S26] C：内存清零
来源：http://dali.shanyushiyangtech.top/Article/details/gt2idufprqq.html

memset(a, 0, sizeof a);
来源：http://dali.shzxlz.cn/Article/details/gt2gzgaofqu.html

[S27] C：定义常量
来源：http://dali.andypj.xyz/Article/details/gt2qfamzkoe.html

const double PI = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gt2dkzpwcrk.html

[S28] C：静态变量
来源：http://dali.ppjwa.cn/Article/details/gt2pqzipgta.html

static int counter = 0;
来源：http://dali.c1oappe.top/Article/details/gt2vdhtpcbt.html

[S29] C：变参函数
来源：http://dali.hammf.cn/Article/details/gt2ftyrzhfp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.dashuyun.cn/Article/details/gt2dspufscv.html

[S30] C：头文件保护
来源：http://dali.sxryk.cn/Article/details/gt2qqrgxsko.html

#ifndef X_H
来源：http://dali.yj20258888.top/Article/details/gt2rgkjemnj.html

#define X_H
来源：http://dali.xuanzx.com/Article/details/gt2nfyqawfx.html

#endif
来源：http://dali.redwolf501.top/Article/details/gt2gvowuxhw.html

[S31] C++：Hello World
来源：http://dali.gotoacloud.top/Article/details/gt2ulrndgce.html

#include <iostream>
来源：http://dali.chenlongwang.top/Article/details/gt2bcaagimx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yongpay.top/Article/details/gt2jqezhsny.html

[S32] C++：字符串
来源：http://dali.wangdashe.top/Article/details/gt2dvyvmqqh.html

std::string s = "hi";  s += "!";
来源：http://dali.hysaishi.cn/Article/details/gt2wkpebmuk.html

[S33] C++：vector 增删
来源：http://dali.ydzc1.top/Article/details/gt2wqnhknpz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yueranfly.top/Article/details/gt2anqustnj.html

[S34] C++：遍历 vector
来源：http://dali.pycfn.com/Article/details/gt2ubijwzpu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shzxlz.cn/Article/details/gt2rkbrsuyf.html

[S35] C++：map
来源：http://dali.bjfxy.top/Article/details/gt2kdtsevgk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gt2drzundnz.html

[S36] C++：unordered_map
来源：http://dali.fzhhl.top/Article/details/gt2hkybtiyt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tanke756.top/Article/details/gt2lspnrvkl.html

[S37] C++：set
来源：http://dali.havefunace.top/Article/details/gt2lxynwzrv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jgrcogzy.html

[S38] C++：排序
来源：http://dali.redwolf501.top/Article/details/gt2iisctako.html

std::sort(v.begin(), v.end());
来源：http://dali.dianchejie.cn/Article/details/gt2adodradn.html

[S39] C++：自定义比较器排序
来源：http://dali.jinqigufen.top/Article/details/gt2jiieafav.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.havefunace.top/Article/details/gt2weplcojm.html

[S40] C++：查找元素
来源：http://dali.hammf.cn/Article/details/gt2isxxyzti.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.9152youxi.cn/Article/details/gt2cndpgdiu.html

[S41] C++：类与构造函数
来源：http://dali.ppjwa.cn/Article/details/gt2reqajwrk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yuanzhike.top/Article/details/gt2zbyglboe.html

[S42] C++：继承与虚函数
来源：http://dali.yueranfly.top/Article/details/gt2nrcrggcc.html

class B : public Base { public: void f() override {} };
来源：http://dali.cashguo.top/Article/details/gt2kcrhjicu.html

[S43] C++：智能指针
来源：http://dali.tianlin.xyz/Article/details/gt2sgtohqca.html

auto p = std::make_unique<int>(5);
来源：http://dali.sweek.top/Article/details/gt2dqnxqxrx.html

[S44] C++：引用传参
来源：http://dali.yuxming.cn/Article/details/gt2dbshhlgs.html

void inc(int &x) { ++x; }
来源：http://dali.fzhhl.top/Article/details/gt2iaadchnw.html

[S45] C++：lambda
来源：http://dali.9152youxi.cn/Article/details/gt2arfsnkws.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.haohaochexian.top/Article/details/gt2quxwbqvx.html

[S46] C++：函数模板
来源：http://dali.vqdsnc.cn/Article/details/gt2onrdnvok.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2handypua.html

[S47] C++：结构化绑定遍历
来源：http://dali.chenjidiqi.icu/Article/details/gt2fcinkivc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.dashuyun.cn/Article/details/gt2kbkzvaaf.html

[S48] C++：逐行读文件
来源：http://dali.hnxiangtu.top/Article/details/gt2cqyabzqz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.pengpengdd.cyou/Article/details/gt2amptpyju.html

while (std::getline(in, line)) { }
来源：http://dali.daxiang520.top/Article/details/gt2ezalxttj.html

[S49] C++：写文件
来源：http://dali.yanxiufei.cn/Article/details/gt2rtyotbjn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.nanxinkj.top/Article/details/gt2yputuzvx.html

[S50] C++：格式化数字
来源：http://dali.yj20258888.top/Article/details/gt2ksqonuyr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yongpay.top/Article/details/gt2fynwkaap.html

[S51] C++：显式类型转换
来源：http://dali.havefunace.top/Article/details/gt2qxsquyzy.html

static_cast<double>(a) / b
来源：http://dali.tianlin.xyz/Article/details/gt2bafyarhd.html

[S52] C++：const 与 noexcept
来源：http://dali.cucudq.cn/Article/details/gt2zzpdyxrm.html

int size() const noexcept { return n_; }
来源：http://dali.0kj1m.cn/Article/details/gt2rpfgimox.html

[S53] C++：移动语义
来源：http://dali.xziqi.cn/Article/details/gt2qfkozrhj.html

std::vector<int> w = std::move(v);
来源：http://dali.zhongyouzk.top/Article/details/gt2dtkrbmnh.html

[S54] C++：异常处理
来源：http://dali.hysaishi.cn/Article/details/gt2lguzwfpy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ivvv.top/Article/details/gt2jdeojfsn.html

[S55] C++：结构化绑定
来源：http://dali.gzhubu.top/Article/details/gt2ksduukfx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.aibaodan.cn/Article/details/gt2kpjrzovu.html

[S56] C++：optional
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cyvhctxf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cdnleiting.top/Article/details/gt2nefpctmg.html

[S57] C++：编译期常量
来源：http://dali.ehwqpu.com/Article/details/gt2uinqfwhz.html

constexpr int N = 10;
来源：http://dali.gotoacloud.top/Article/details/gt2hzpvhqzb.html

[S58] C++：命名空间
来源：http://dali.sufxvd.cn/Article/details/gt2gsrshwgg.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj202588.top/Article/details/gt2tksknnld.html

[S59] C++：静态断言
来源：http://dali.jqgfzy.top/Article/details/gt2iaktsana.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.chenzaomai.com/Article/details/gt2gyddoavh.html

[S60] C++：遍历并删除元素
来源：http://dali.svipenyu.cn/Article/details/gt2ocybebxu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yueranfly.top/Article/details/gt2epafcgmx.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gt2tfpvccvq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jcgoapqi.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gt2cdxhwhrc.html

[T01] Kotlin：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wwtemasa.html

println("Hello")
来源：http://dali.jinqigfzy.top/Article/details/gt2nezxbdsa.html

[T02] Kotlin：变量
来源：http://dali.316326.xyz/Article/details/gt2pqrmaljj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.fzhhl.top/Article/details/gt2ruitgvtu.html

[T03] Kotlin：字符串模板
来源：http://dali.xziqi.cn/Article/details/gt2thqpljna.html

"值: $b"
来源：http://dali.ivvv.top/Article/details/gt2fpnavhsm.html

[T04] Kotlin：空安全
来源：http://dali.iojbl.cn/Article/details/gt2zzjwbhkr.html

val n: String? = null;  n?.length
来源：http://dali.chenzaomai.com/Article/details/gt2blomwftp.html

[T05] Kotlin：when 表达式
来源：http://dali.aizwys.cn/Article/details/gt2tydywhoz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hywenlv.cn/Article/details/gt2agkybdzs.html

[T06] Kotlin：集合映射
来源：http://dali.zhixingplan.top/Article/details/gt2hppffacl.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.tanke756.top/Article/details/gt2ibpotufw.html

[T07] Kotlin：集合过滤
来源：http://dali.pycfn.com/Article/details/gt2ddvlqevm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hfpthk.cn/Article/details/gt2iukvzfph.html

[T08] Kotlin：数据类
来源：http://dali.zhijiandao.cn/Article/details/gt2uwccmcis.html

data class User(val name: String, val age: Int)
来源：http://dali.sysykeji.top/Article/details/gt2bhbiyjyx.html

[T09] Kotlin：扩展函数
来源：http://dali.aizwys.cn/Article/details/gt2cxlmmjmb.html

fun String.exclaim() = this + "!"
来源：http://dali.tanke756.top/Article/details/gt2pyvvgdqt.html

[T10] Kotlin：默认参数
来源：http://dali.hammf.cn/Article/details/gt2wepgetty.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.gotoacloud.top/Article/details/gt2ssxseqnz.html

[T11] Kotlin：协程
来源：http://dali.daxiang520.top/Article/details/gt2ymahauus.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.redwolf501.top/Article/details/gt2txqipbdt.html

[T12] Kotlin：解构声明
来源：http://dali.birdmap.top/Article/details/gt2xqakbxhc.html

val (a, b) = Pair(1, 2)
来源：http://dali.yuanzhike.top/Article/details/gt2lkbeatsr.html

[T13] Kotlin：只读 Map
来源：http://dali.pengpengdd.cyou/Article/details/gt2sivxfsqg.html

val m = mapOf("a" to 1)
来源：http://dali.snrcjt.cn/Article/details/gt2cjabiyoo.html

[T14] Kotlin：循环
来源：http://dali.dashuyun.cn/Article/details/gt2inqyvvsy.html

for (i in 1..10) println(i)
来源：http://dali.birdmap.top/Article/details/gt2rgacophz.html

[T15] Kotlin：接口
来源：http://dali.jinqigufen.top/Article/details/gt2yblilork.html

interface Shape { fun area(): Double }
来源：http://dali.yuxming.cn/Article/details/gt2nrefehvx.html

[T16] Swift：Hello World
来源：http://dali.tianlin.xyz/Article/details/gt2gwianebp.html

print("Hello")
来源：http://dali.cqqwz.cn/Article/details/gt2vomcdonr.html

[T17] Swift：变量与常量
来源：http://dali.yangfankeji.com/Article/details/gt2hihmxiqz.html

var a = 1;  let b = 2
来源：http://dali.fzhhl.top/Article/details/gt2yfkaxkmm.html

[T18] Swift：字符串插值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ijhnacaa.html

"值: \(b)"
来源：http://dali.hammf.cn/Article/details/gt2hnnyflvj.html

[T19] Swift：可选绑定
来源：http://dali.redwolf501.top/Article/details/gt2osgbeynf.html

if let n = opt { print(n) }
来源：http://dali.wangdashe.top/Article/details/gt2gaskodya.html

[T20] Swift：数组操作
来源：http://dali.wangshuangyany.cn/Article/details/gt2gbeaxnrj.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cashguo.top/Article/details/gt2mcopjxwk.html

[T21] Swift：遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dbfzqcxq.html

for x in a { print(x) }
来源：http://dali.nanxuanxn.top/Article/details/gt2oracdvqu.html

[T22] Swift：字典
来源：http://dali.jinqigfzy.top/Article/details/gt2yvkqpthk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cqqwz.cn/Article/details/gt2zjdqhsvw.html

[T23] Swift：函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vfjvgavk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xziqi.cn/Article/details/gt2eljpqrxy.html

[T24] Swift：闭包
来源：http://dali.yonumen.top/Article/details/gt2uzsdkhzw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ydzc1.top/Article/details/gt2sxcfzaat.html

[T25] Swift：结构体
来源：http://dali.aizwys.cn/Article/details/gt2qvcdbtxw.html

struct P { var x: Int }
来源：http://dali.cashguo.top/Article/details/gt2vzpdnabh.html

[T26] Swift：类与重写
来源：http://dali.pycfn.com/Article/details/gt2xlaklaac.html

class A: Base { override func f() {} }
来源：http://dali.nanxinkj.top/Article/details/gt2guiysmat.html

[T27] Swift：错误处理
来源：http://dali.shuidangran.top/Article/details/gt2htnzlrxl.html

do { try f() } catch { print(error) }
来源：http://dali.nanxuanxn.top/Article/details/gt2ulnqlyzl.html

[T28] Swift：枚举
来源：http://dali.tian-w.cn/Article/details/gt2henazlqn.html

enum Color { case red, green }
来源：http://dali.daria6918.cn/Article/details/gt2bcdkptno.html

[T29] Swift：guard 提前返回
来源：http://dali.cdnleiting.top/Article/details/gt2avfehhcq.html

guard let x = opt else { return }
来源：http://dali.gotoacloud.top/Article/details/gt2wphzsjyd.html

[T30] Swift：协议
来源：http://dali.quarkkingdee.top/Article/details/gt2gvxeomsp.html

protocol Shape { func area() -> Double }
来源：http://dali.guowangkeji.top/Article/details/gt2lixnbdwz.html

[T31] Lua：Hello World
来源：http://dali.9152youxi.cn/Article/details/gt2gzzvbhyk.html

print("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gt2ndbezaxs.html

[T32] Lua：局部变量
来源：http://dali.yuanzhike.top/Article/details/gt2epbkigqi.html

local a = 1
来源：http://dali.wangdashe.top/Article/details/gt2ayrmnvdc.html

[T33] Lua：表（数组）
来源：http://dali.dashuyun.cn/Article/details/gt2qqsppghu.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.tanke756.top/Article/details/gt2lvzlsbqn.html

[T34] Lua：遍历表
来源：http://dali.chenlongwang.top/Article/details/gt2dqoverto.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.tanke756.top/Article/details/gt2frkwvtrj.html

[T35] Lua：字典表
来源：http://dali.cashguo.top/Article/details/gt2zesdguii.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yuxming.cn/Article/details/gt2gjcfudhg.html

[T36] Lua：函数
来源：http://dali.dashuyun.cn/Article/details/gt2rjomfynv.html

function add(a, b) return a + b end
来源：http://dali.daria6918.cn/Article/details/gt2nrshmjjb.html

[T37] Lua：字符串拼接
来源：http://dali.hammf.cn/Article/details/gt2sxrkbanu.html

"a" .. "b"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2judutilr.html

[T38] Lua：条件
来源：http://dali.wangdashe.top/Article/details/gt2lwomlero.html

if x > 0 then print("正") end
来源：http://dali.mhx1999.top/Article/details/gt2cacphcrj.html

[T39] Lua：模式匹配
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bgqxqzzq.html

string.find(s, "%d+")
来源：http://dali.yangfankeji.com/Article/details/gt2dtmbugae.html

[T40] Lua：元表
来源：http://dali.dashuyun.cn/Article/details/gt2hsdphrzi.html

setmetatable({}, { __index = base })
来源：http://dali.mhx1999.top/Article/details/gt2ibrmkkfk.html

[T41] Perl：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rnppptdz.html

print "Hello\n";
来源：http://dali.tianlin.xyz/Article/details/gt2yjtxcotu.html

[T42] Perl：变量类型
来源：http://dali.feifeiyinyue.top/Article/details/gt2iqtnshgb.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhengqikj.top/Article/details/gt2gfjsvkga.html

[T43] Perl：字符串插值
来源：http://dali.316326.xyz/Article/details/gt2fonyqweu.html

"值: $a"
来源：http://dali.zhongyouzk.top/Article/details/gt2nqnwnmlb.html

[T44] Perl：条件
来源：http://dali.chenzaomai.com/Article/details/gt2gjurcfyq.html

if ($a > 0) { print "正"; }
来源：http://dali.fengsongda.top/Article/details/gt2gzhcvygu.html

[T45] Perl：数组遍历
来源：http://dali.sysykeji.top/Article/details/gt2wahsojcb.html

for my $x (@arr) { print $x; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2tzzawgqf.html

[T46] Perl：哈希操作
来源：http://dali.zhongyouzk.top/Article/details/gt2acltahvj.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.meibo888.top/Article/details/gt2uwenagqr.html

[T47] Perl：正则捕获
来源：http://dali.kuanghao11.cn/Article/details/gt2vmadpbvl.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.9152youxi.cn/Article/details/gt2ggnfkcgs.html

[T48] Perl：正则替换
来源：http://dali.hongshengwenyu.top/Article/details/gt2rzrrizao.html

$s =~ s/old/new/g;
来源：http://dali.sufxvd.cn/Article/details/gt2ikecpqvz.html

[T49] Perl：函数
来源：http://dali.fzhhl.top/Article/details/gt2xaguccre.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jqgufenzy.top/Article/details/gt2zkbnxybd.html

[T50] Perl：逐行读文件
来源：http://dali.yuxming.cn/Article/details/gt2dbjgwmio.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hnxiangtu.top/Article/details/gt2mipmuklc.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yangfankeji.com/Article/details/gt2kuvcldra.html

[T51] Scala：Hello World
来源：http://dali.guannengcc.top/Article/details/gt2qhlnzllq.html

println("Hello")
来源：http://dali.ybcxt.top/Article/details/gt2qbjlvwzj.html

[T52] Scala：变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qiaoyrnm.html

val a = 1;  var b = 2
来源：http://dali.hnqzz.top/Article/details/gt2okvpiaxc.html

[T53] Scala：字符串插值
来源：http://dali.sysykeji.top/Article/details/gt2hhikaotv.html

s"值: $b"
来源：http://dali.tanke756.top/Article/details/gt2dtipwfyn.html

[T54] Scala：集合映射
来源：http://dali.sysykeji.top/Article/details/gt2zxjnfkys.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.bjfxy.top/Article/details/gt2lfjhqwvf.html

[T55] Scala：集合过滤
来源：http://dali.bjfxy.top/Article/details/gt2ahpfgbis.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ybcxt.top/Article/details/gt2ldozuidd.html

[T56] Scala：样例类
来源：http://dali.zhixingplan.top/Article/details/gt2iwvitaeo.html

case class User(name: String, age: Int)
来源：http://dali.tianlin.xyz/Article/details/gt2xvjkbkvd.html

[T57] Scala：模式匹配
来源：http://dali.jlsjyb.cn/Article/details/gt2wjbgepsk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.chenjidiqi.icu/Article/details/gt2oajmdqft.html

[T58] Scala：函数定义
来源：http://dali.pycfn.com/Article/details/gt2gjdaveyv.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cdnleiting.top/Article/details/gt2dvgmiaba.html

[T59] Scala：循环
来源：http://dali.chenjidiqi.icu/Article/details/gt2jkqbmzxp.html

for (i <- 1 to 10) println(i)
来源：http://dali.xziqi.cn/Article/details/gt2swkvzdlk.html

[T60] Scala：折叠
来源：http://dali.hnqzz.top/Article/details/gt2jemhqjnk.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.gzhubu.top/Article/details/gt2mihnztyg.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2qzdafbap.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.andypj.xyz/Article/details/gt2qpewokup.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2iomvbiwp.html

[U01] Py：创建虚拟环境
来源：http://dali.zdqjudy.top/Article/details/gt2twauepwy.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.hywenlv.cn/Article/details/gt2tuefjlcv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rhcpgygw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.ppjwa.cn/Article/details/gt2jhpvzhfy.html

[U03] Py：加载 .env 配置
来源：http://dali.xuetiantiany.cn/Article/details/gt2wngltsin.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.svipenyu.cn/Article/details/gt2rdjmijax.html

[U04] Py：变量调试打印
来源：http://dali.gogol.net.cn/Article/details/gt2yzkcqyma.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ewhgmnny.html

[U05] Py：列表去重且保序
来源：http://dali.hnqzz.top/Article/details/gt2rfwxqrui.html

list(dict.fromkeys(arr))
来源：http://dali.jiagoushi.top/Article/details/gt2ymcqqinj.html

[U06] Py：合并两个字典
来源：http://dali.ybcxt.top/Article/details/gt2hkxjxerr.html

{**a, **b}
来源：http://dali.jianghu66.top/Article/details/gt2dulswvdd.html

[U07] Py：反转字典键值
来源：http://dali.yj20258888.top/Article/details/gt2qyhrzlrd.html

{v: k for k, v in d.items()}
来源：http://dali.316326.xyz/Article/details/gt2wdzpexyg.html

[U08] Py：展平二维列表
来源：http://dali.c1oappe.top/Article/details/gt2zvhneveg.html

[y for x in nested for y in x]
来源：http://dali.feifeiyinyue.top/Article/details/gt2fpdmriif.html

[U09] Py：字典取最大值的键
来源：http://dali.hywenlv.cn/Article/details/gt2umkliuzh.html

max(d, key=d.get)
来源：http://dali.tianlin.xyz/Article/details/gt2rduuodyq.html

[U10] Py：按值排序字典
来源：http://dali.zhijiandao.cn/Article/details/gt2vmfbobkk.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.xziqi.cn/Article/details/gt2mkxlevpl.html


<!-- 参考信息 -->