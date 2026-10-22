代发 wailian999

head -c 16 /dev/urandom | base64
来源：http://dali.jianghu66.top/Article/details/gt2fohyqpgy.html

[R70] 时间戳与互转
来源：http://dali.xylfe.cn/Article/details/gt2liphlwts.html

date +%s;  date -d @1700000000
来源：http://dali.tian-w.cn/Article/details/gt2zczolrwu.html

[R71] 日期格式化
来源：http://dali.pengpengdd.cyou/Article/details/gt2mrtemrkh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rqiegdht.html

[R72] 等待端口就绪
来源：http://dali.shangyingyoupin.top/Article/details/gt2ssppdaor.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xziqi.cn/Article/details/gt2slmhuhmr.html

[R73] 分割大日志
来源：http://dali.shangyingyoupin.top/Article/details/gt2evnrpgkw.html

split -l 1000 big.log part_
来源：http://dali.zhoulong.xyz/Article/details/gt2ivjfybzu.html

[R74] 批量重命名
来源：http://dali.ydzc1.top/Article/details/gt2stazsawg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dhnkmlqa.html

[R75] 导出环境变量
来源：http://dali.zhoulong.xyz/Article/details/gt2spbcrrbh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uceaigwb.html

[R76] 使用临时文件
来源：http://dali.yanxiufei.cn/Article/details/gt2ufeniyvj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gzhubu.top/Article/details/gt2txgzriyh.html

[R77] 读取用户输入
来源：http://dali.jqgufenzy.top/Article/details/gt2opuwgriq.html

read -rp "请输入: " ans
来源：http://dali.jlsjyb.cn/Article/details/gt2ymyrxznq.html

[R78] 交互式菜单
来源：http://dali.vqdsnc.cn/Article/details/gt2vodjyams.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sysykeji.top/Article/details/gt2voiwfnyb.html

[R79] 解析命令行选项
来源：http://dali.gaohongyu789.top/Article/details/gt2xsrjwiwa.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wfdecqzi.html

[R80] 查看脚本执行耗时
来源：http://dali.pengpengdd.cyou/Article/details/gt2mhzswepe.html

time ./run.sh
来源：http://dali.gaohongyu789.top/Article/details/gt2uvzwkqgd.html

================================================================================
来源：http://dali.smart0.xyz/Article/details/gt2rmagalbq.html

S. C / C++ 专题
来源：http://dali.zycfv.cn/Article/details/gt2vkireual.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pciyiifm.html

[S01] C：Hello World
来源：http://dali.yangfankeji.com/Article/details/gt2jyjcenmb.html

#include <stdio.h>
来源：http://dali.zycfv.cn/Article/details/gt2lcwxcdrr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yonumen.top/Article/details/gt2exmaopze.html

[S02] C：变量与格式化输出
来源：http://dali.shuidangran.top/Article/details/gt2jjkaloqy.html

int a = 10; printf("%d\n", a);
来源：http://dali.redwolf501.top/Article/details/gt2vcbzbfpp.html

[S03] C：读入整数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nlxpuxwc.html

int x; scanf("%d", &x);
来源：http://dali.hywenlv.cn/Article/details/gt2dagsixzk.html

[S04] C：字符串复制
来源：http://dali.jianghu66.top/Article/details/gt2fsighyez.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cqqwz.cn/Article/details/gt2ezmhaagm.html

[S05] C：字符串长度
来源：http://dali.ybcxt.top/Article/details/gt2sytebjzl.html

strlen(s)
来源：http://dali.quarkkingdee.top/Article/details/gt2bxsyqoym.html

[S06] C：字符串比较
来源：http://dali.yuxming.cn/Article/details/gt2vasxdcmr.html

strcmp(a, b) == 0
来源：http://dali.fengsongda.top/Article/details/gt2buypcnbk.html

[S07] C：数组遍历求和
来源：http://dali.wangdashe.top/Article/details/gt2xaosnxdo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xylfe.cn/Article/details/gt2layddvbe.html

[S08] C：动态内存分配与释放
来源：http://dali.hnqzz.top/Article/details/gt2rajmfsct.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhiwuduotai.top/Article/details/gt2pejznbxu.html

[S09] C：结构体定义与初始化
来源：http://dali.9152youxi.cn/Article/details/gt2lyolodfv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.aizwys.cn/Article/details/gt2fipvxsme.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2dpykunth.html

int *p = &a;  *p = 5;
来源：http://dali.jqgfzy.top/Article/details/gt2vkrjhhky.html

[S11] C：逐行读文件
来源：http://dali.hnqzz.top/Article/details/gt2sgvdwodk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hfpthk.cn/Article/details/gt2fxmkbsio.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jioqjsap.html

fclose(f);
来源：http://dali.snrcjt.cn/Article/details/gt2zvsrmppb.html

[S12] C：写文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ogimnejm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ydzc1.top/Article/details/gt2nslbhftc.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2tdswyzve.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sweek.top/Article/details/gt2ofsdfcit.html

[S14] C：枚举
来源：http://dali.hammf.cn/Article/details/gt2iejabjnk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhengqikj.top/Article/details/gt2omiufniw.html

[S15] C：类型转换
来源：http://dali.daxiang520.top/Article/details/gt2eaehbtro.html

(double) a / b
来源：http://dali.zhengqikj.top/Article/details/gt2jiaaphtv.html

[S16] C：位操作置位
来源：http://dali.zycfv.cn/Article/details/gt2mwbsmdeh.html

x |= (1 << 3);
来源：http://dali.sysykeji.top/Article/details/gt2ldhyxrrc.html

[S17] C：安全拼接字符串
来源：http://dali.redwolf501.top/Article/details/gt2nhqyybki.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhixingplan.top/Article/details/gt2bvemttab.html

[S18] C：命令行参数
来源：http://dali.wangdashe.top/Article/details/gt2iqfapfis.html

int main(int argc, char **argv)
来源：http://dali.gogol.net.cn/Article/details/gt2uoednxat.html

[S19] C：快速排序
来源：http://dali.chenlongwang.top/Article/details/gt2ntijknut.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.tian-w.cn/Article/details/gt2cxaoptib.html

[S20] C：二分查找
来源：http://dali.sxryk.cn/Article/details/gt2cjbpjmqi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.nanxuanxn.top/Article/details/gt2crsajrxp.html

[S21] C：字符类别判断
来源：http://dali.havefunace.top/Article/details/gt2oeynjane.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dsnfeyyr.html

[S22] C：字符串转数字
来源：http://dali.yonumen.top/Article/details/gt2dummvjti.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.kuanghao11.cn/Article/details/gt2dophkrtf.html

[S23] C：随机数
来源：http://dali.jiagoushi.top/Article/details/gt2kkecbtoc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.chenzaomai.com/Article/details/gt2szntmtbf.html

[S24] C：获取本地时间
来源：http://dali.jinqigfzy.top/Article/details/gt2pwcfzrtt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.tanke756.top/Article/details/gt2zwssemzu.html

[S25] C：内存拷贝
来源：http://dali.cheryme.top/Article/details/gt2ohxttjwc.html

memcpy(dst, src, n);
来源：http://dali.chenlongwang.top/Article/details/gt2yeliwaij.html

[S26] C：内存清零
来源：http://dali.zhoulong.xyz/Article/details/gt2rnhtrizs.html

memset(a, 0, sizeof a);
来源：http://dali.nanxuanxn.top/Article/details/gt2ancaryfp.html

[S27] C：定义常量
来源：http://dali.zycfv.cn/Article/details/gt2bmeqqnns.html

const double PI = 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gt2bglxkvoz.html

[S28] C：静态变量
来源：http://dali.yongpay.top/Article/details/gt2garuqgfp.html

static int counter = 0;
来源：http://dali.dashuyun.cn/Article/details/gt2vtvppsol.html

[S29] C：变参函数
来源：http://dali.ybcxt.top/Article/details/gt2dwalzwix.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.chenjidiqi.icu/Article/details/gt2hisrhqcw.html

[S30] C：头文件保护
来源：http://dali.zhongyouzk.top/Article/details/gt2pjcsouxv.html

#ifndef X_H
来源：http://dali.svipenyu.cn/Article/details/gt2aylhdbcq.html

#define X_H
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2phowoqya.html

#endif
来源：http://dali.birdmap.top/Article/details/gt2rmjplgxi.html

[S31] C++：Hello World
来源：http://dali.xinyue.icu/Article/details/gt2lcwifyaf.html

#include <iostream>
来源：http://dali.yuxming.cn/Article/details/gt2vnfsbszh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2rsnmrryv.html

[S32] C++：字符串
来源：http://dali.daria6918.cn/Article/details/gt2lzgebtxl.html

std::string s = "hi";  s += "!";
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2naiuebby.html

[S33] C++：vector 增删
来源：http://dali.nanxinkj.top/Article/details/gt2oqvxajsv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lgakfmuf.html

[S34] C++：遍历 vector
来源：http://dali.sweek.top/Article/details/gt2xpntemoo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.kuanghao11.cn/Article/details/gt2jqvadrvx.html

[S35] C++：map
来源：http://dali.cheryme.top/Article/details/gt2irxkbzeu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.mhx1999.top/Article/details/gt2loselklu.html

[S36] C++：unordered_map
来源：http://dali.yongpay.top/Article/details/gt2wdmzkhze.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.meibo888.top/Article/details/gt2lsyjrxbo.html

[S37] C++：set
来源：http://dali.hnxiangtu.top/Article/details/gt2rmodiezy.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.havefunace.top/Article/details/gt2ofqdqldk.html

[S38] C++：排序
来源：http://dali.andypj.xyz/Article/details/gt2vuwxcxpe.html

std::sort(v.begin(), v.end());
来源：http://dali.redwolf501.top/Article/details/gt2jqwgdfoc.html

[S39] C++：自定义比较器排序
来源：http://dali.quarkkingdee.top/Article/details/gt2qxfltprb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sweek.top/Article/details/gt2rovneygw.html

[S40] C++：查找元素
来源：http://dali.redwolf501.top/Article/details/gt2hbslczjs.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cjvmbiqp.html

[S41] C++：类与构造函数
来源：http://dali.bjfxy.top/Article/details/gt2nckncztl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.bjfxy.top/Article/details/gt2uxkfdpzk.html

[S42] C++：继承与虚函数
来源：http://dali.zhixingplan.top/Article/details/gt2agnqiofg.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhongyouzk.top/Article/details/gt2nkyygtjx.html

[S43] C++：智能指针
来源：http://dali.kuanghao11.cn/Article/details/gt2rmiczeod.html

auto p = std::make_unique<int>(5);
来源：http://dali.hysaishi.cn/Article/details/gt2kvkvrlpo.html

[S44] C++：引用传参
来源：http://dali.xinyue.icu/Article/details/gt2qsrxnjuo.html

void inc(int &x) { ++x; }
来源：http://dali.guannengcc.top/Article/details/gt2rfngyijb.html

[S45] C++：lambda
来源：http://dali.yueranfly.top/Article/details/gt2fifkvwxy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cheryme.top/Article/details/gt2farcbtdt.html

[S46] C++：函数模板
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kyzvtqdx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zhkuoiom.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhengqikj.top/Article/details/gt2fvvpgwsz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.tian-w.cn/Article/details/gt2ryigaolh.html

[S48] C++：逐行读文件
来源：http://dali.xziqi.cn/Article/details/gt2stsddyih.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yuanzhike.top/Article/details/gt2amvlhjng.html

while (std::getline(in, line)) { }
来源：http://dali.gotoacloud.top/Article/details/gt2ialqjhqc.html

[S49] C++：写文件
来源：http://dali.guowangkeji.top/Article/details/gt2nvoaipdw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.havefunace.top/Article/details/gt2drsfxoap.html

[S50] C++：格式化数字
来源：http://dali.yj20258888.top/Article/details/gt2dvrqjxcb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gt2uhfpjpkq.html

[S51] C++：显式类型转换
来源：http://dali.cucudq.cn/Article/details/gt2ofzrigjq.html

static_cast<double>(a) / b
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kkqfifop.html

[S52] C++：const 与 noexcept
来源：http://dali.ppjwa.cn/Article/details/gt2ryhyqhki.html

int size() const noexcept { return n_; }
来源：http://dali.mhx1999.top/Article/details/gt2asmzjjjm.html

[S53] C++：移动语义
来源：http://dali.gotoacloud.top/Article/details/gt2medvteje.html

std::vector<int> w = std::move(v);
来源：http://dali.sweek.top/Article/details/gt2vfsiuaji.html

[S54] C++：异常处理
来源：http://dali.ydzc1.top/Article/details/gt2ralvzzsi.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jiagoushi.top/Article/details/gt2sqlnewkb.html

[S55] C++：结构化绑定
来源：http://dali.zhengqikj.top/Article/details/gt2dcodfcdd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhoulong.xyz/Article/details/gt2hclsltce.html

[S56] C++：optional
来源：http://dali.316326.xyz/Article/details/gt2mtokyfqp.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2aewiuftw.html

[S57] C++：编译期常量
来源：http://dali.shuidangran.top/Article/details/gt2ndahlrvn.html

constexpr int N = 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vuiyzuff.html

[S58] C++：命名空间
来源：http://dali.yangfankeji.com/Article/details/gt2hivrmmsl.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj20258888.top/Article/details/gt2rpntgons.html

[S59] C++：静态断言
来源：http://dali.hongshengwenyu.top/Article/details/gt2tztqquoo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhoulong.xyz/Article/details/gt2jmagyrcz.html

[S60] C++：遍历并删除元素
来源：http://dali.chenlongwang.top/Article/details/gt2ogrvzbkr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hywenlv.cn/Article/details/gt2wnfqmqny.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2qdzbyiux.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hongshengwenyu.top/Article/details/gt2mgscgovh.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2fnvucuyu.html

[T01] Kotlin：Hello World
来源：http://dali.cucudq.cn/Article/details/gt2pvidboho.html

println("Hello")
来源：http://dali.ybcxt.top/Article/details/gt2kpjkzwxh.html

[T02] Kotlin：变量
来源：http://dali.jiagoushi.top/Article/details/gt2uxslhzea.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aturelds.html

[T03] Kotlin：字符串模板
来源：http://dali.andypj.xyz/Article/details/gt2rftljfgo.html

"值: $b"
来源：http://dali.hfpthk.cn/Article/details/gt2hpebiueu.html

[T04] Kotlin：空安全
来源：http://dali.quarkkingdee.top/Article/details/gt2vprqisdj.html

val n: String? = null;  n?.length
来源：http://dali.bjfxy.top/Article/details/gt2mrmuvgyr.html

[T05] Kotlin：when 表达式
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wupyemaw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.chenlongwang.top/Article/details/gt2kynogwgh.html

[T06] Kotlin：集合映射
来源：http://dali.zdqjudy.top/Article/details/gt2ceiixtex.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.daria6918.cn/Article/details/gt2btydwttg.html

[T07] Kotlin：集合过滤
来源：http://dali.ybcxt.top/Article/details/gt2arfaibpr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj202588.top/Article/details/gt2doetuofq.html

[T08] Kotlin：数据类
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fnnofpew.html

data class User(val name: String, val age: Int)
来源：http://dali.ivvv.top/Article/details/gt2ruyjcjvo.html

[T09] Kotlin：扩展函数
来源：http://dali.shzxlz.cn/Article/details/gt2lmsorbsz.html

fun String.exclaim() = this + "!"
来源：http://dali.feifeiyinyue.top/Article/details/gt2fmibssuo.html

[T10] Kotlin：默认参数
来源：http://dali.jinqigfzy.top/Article/details/gt2oxahtrpz.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hfpthk.cn/Article/details/gt2jbvmeokr.html

[T11] Kotlin：协程
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gqmrongb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.chenzaomai.com/Article/details/gt2htuigfsk.html

[T12] Kotlin：解构声明
来源：http://dali.hnqzz.top/Article/details/gt2cooofuro.html

val (a, b) = Pair(1, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2gqbmlhmp.html

[T13] Kotlin：只读 Map
来源：http://dali.zdqjudy.top/Article/details/gt2ufkuytkl.html

val m = mapOf("a" to 1)
来源：http://dali.hnqzz.top/Article/details/gt2zqzowiar.html

[T14] Kotlin：循环
来源：http://dali.feifeiyinyue.top/Article/details/gt2bcfuutmz.html

for (i in 1..10) println(i)
来源：http://dali.zdqjudy.top/Article/details/gt2hhkidser.html

[T15] Kotlin：接口
来源：http://dali.316326.xyz/Article/details/gt2exnknusc.html

interface Shape { fun area(): Double }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2bvoponfn.html

[T16] Swift：Hello World
来源：http://dali.dashuyun.cn/Article/details/gt2rrnqbcmm.html

print("Hello")
来源：http://dali.9152youxi.cn/Article/details/gt2bccldhsi.html

[T17] Swift：变量与常量
来源：http://dali.gogol.net.cn/Article/details/gt2thzhfget.html

var a = 1;  let b = 2
来源：http://dali.sweek.top/Article/details/gt2chhbxqes.html

[T18] Swift：字符串插值
来源：http://dali.hongshengwenyu.top/Article/details/gt2fxhlkuxh.html

"值: \(b)"
来源：http://dali.zycfv.cn/Article/details/gt2ebhdhctn.html

[T19] Swift：可选绑定
来源：http://dali.jlsjyb.cn/Article/details/gt2tsqotknl.html

if let n = opt { print(n) }
来源：http://dali.quarkkingdee.top/Article/details/gt2tzhjjezh.html

[T20] Swift：数组操作
来源：http://dali.yonumen.top/Article/details/gt2pdwnvczg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.mhx1999.top/Article/details/gt2uclmtkdx.html

[T21] Swift：遍历
来源：http://dali.zdqjudy.top/Article/details/gt2grqsunxf.html

for x in a { print(x) }
来源：http://dali.shzxlz.cn/Article/details/gt2dghgjqnt.html

[T22] Swift：字典
来源：http://dali.jqgfzy.top/Article/details/gt2mbefxlar.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hfpthk.cn/Article/details/gt2wiomuoba.html

[T23] Swift：函数
来源：http://dali.jinqigfzy.top/Article/details/gt2qkxbatsx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.feifeiyinyue.top/Article/details/gt2zubvnten.html

[T24] Swift：闭包
来源：http://dali.xinyue.icu/Article/details/gt2fvmeqmkk.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.fzhhl.top/Article/details/gt2lgfjscta.html

[T25] Swift：结构体
来源：http://dali.hongshengwenyu.top/Article/details/gt2fiqvzpic.html

struct P { var x: Int }
来源：http://dali.nanxuanxn.top/Article/details/gt2yqgeyhtw.html

[T26] Swift：类与重写
来源：http://dali.9152youxi.cn/Article/details/gt2faigdjul.html

class A: Base { override func f() {} }
来源：http://dali.cqqwz.cn/Article/details/gt2wuzvmwew.html

[T27] Swift：错误处理
来源：http://dali.zhiwuduotai.top/Article/details/gt2qgwzgnxe.html

do { try f() } catch { print(error) }
来源：http://dali.shzxlz.cn/Article/details/gt2kpdirzup.html

[T28] Swift：枚举
来源：http://dali.gaohongyu789.top/Article/details/gt2qngnuoop.html

enum Color { case red, green }
来源：http://dali.kuanghao11.cn/Article/details/gt2fvvzgjrx.html

[T29] Swift：guard 提前返回
来源：http://dali.yj20258888.top/Article/details/gt2haiqwqhb.html

guard let x = opt else { return }
来源：http://dali.hywenlv.cn/Article/details/gt2jujfsvbq.html

[T30] Swift：协议
来源：http://dali.yvedp.cn/Article/details/gt2onjtilqu.html

protocol Shape { func area() -> Double }
来源：http://dali.fzhhl.top/Article/details/gt2hpuekgkn.html

[T31] Lua：Hello World
来源：http://dali.cheryme.top/Article/details/gt2zrahjocr.html

print("Hello")
来源：http://dali.yvedp.cn/Article/details/gt2rortgbgb.html

[T32] Lua：局部变量
来源：http://dali.havefunace.top/Article/details/gt2tzldhdzz.html

local a = 1
来源：http://dali.aizwys.cn/Article/details/gt2jkeutgub.html

[T33] Lua：表（数组）
来源：http://dali.yj202588.top/Article/details/gt2glpibhen.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jiagoushi.top/Article/details/gt2qzkccqdm.html

[T34] Lua：遍历表
来源：http://dali.yonumen.top/Article/details/gt2hlvqzmle.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jiagoushi.top/Article/details/gt2qabqsskf.html

[T35] Lua：字典表
来源：http://dali.ybcxt.top/Article/details/gt2ukxeoudv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.sxryk.cn/Article/details/gt2tsgdfugi.html

[T36] Lua：函数
来源：http://dali.smart0.xyz/Article/details/gt2wsyfmkae.html

function add(a, b) return a + b end
来源：http://dali.fzhhl.top/Article/details/gt2hstzzjeu.html

[T37] Lua：字符串拼接
来源：http://dali.xuanzx.com/Article/details/gt2kmzuiaxu.html

"a" .. "b"
来源：http://dali.c1oappe.top/Article/details/gt2jicixllj.html

[T38] Lua：条件
来源：http://dali.tianlin.xyz/Article/details/gt2zlhfpedw.html

if x > 0 then print("正") end
来源：http://dali.nwbrower.top/Article/details/gt2bzaqrzsu.html

[T39] Lua：模式匹配
来源：http://dali.yj202588.top/Article/details/gt2kalklwzr.html

string.find(s, "%d+")
来源：http://dali.0kj1m.cn/Article/details/gt2mpubvrha.html

[T40] Lua：元表
来源：http://dali.yj20258.top/Article/details/gt2cpugrdii.html

setmetatable({}, { __index = base })
来源：http://dali.jinghuilouyu.cn/Article/details/gt2tqwpeyyw.html

[T41] Perl：Hello World
来源：http://dali.xuanzx.com/Article/details/gt2gahhfntj.html

print "Hello\n";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mxexybzo.html

[T42] Perl：变量类型
来源：http://dali.gzhubu.top/Article/details/gt2hchkcwue.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jinqigufen.top/Article/details/gt2azdocosj.html

[T43] Perl：字符串插值
来源：http://dali.xziqi.cn/Article/details/gt2abbbsiev.html

"值: $a"
来源：http://dali.xinyue.icu/Article/details/gt2zpvytipd.html

[T44] Perl：条件
来源：http://dali.birdmap.top/Article/details/gt2ddzlbdxa.html

if ($a > 0) { print "正"; }
来源：http://dali.yangfankeji.com/Article/details/gt2urqfurkv.html

[T45] Perl：数组遍历
来源：http://dali.yongpay.top/Article/details/gt2aujtbvhx.html

for my $x (@arr) { print $x; }
来源：http://dali.guowangkeji.top/Article/details/gt2ofogbyqm.html

[T46] Perl：哈希操作
来源：http://dali.hnxiangtu.top/Article/details/gt2shtiufme.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shangyingyoupin.top/Article/details/gt2vpqzeuuw.html

[T47] Perl：正则捕获
来源：http://dali.daria6918.cn/Article/details/gt2vssiklps.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xylfe.cn/Article/details/gt2pgggsjjq.html

[T48] Perl：正则替换
来源：http://dali.aibaodan.cn/Article/details/gt2tsgfhxai.html

$s =~ s/old/new/g;
来源：http://dali.zycfv.cn/Article/details/gt2lxkktivf.html

[T49] Perl：函数
来源：http://dali.cdnleiting.top/Article/details/gt2qlvpyopi.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hammf.cn/Article/details/gt2jfrqjzxa.html

[T50] Perl：逐行读文件
来源：http://dali.jianghu66.top/Article/details/gt2olkhxyvr.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.pycfn.com/Article/details/gt2gvjzbsmg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cheryme.top/Article/details/gt2gjitteak.html

[T51] Scala：Hello World
来源：http://dali.sysykeji.top/Article/details/gt2ifgdqqvl.html

println("Hello")
来源：http://dali.havefunace.top/Article/details/gt2jqqmvwnq.html

[T52] Scala：变量
来源：http://dali.chenlongwang.top/Article/details/gt2qbzjtauu.html

val a = 1;  var b = 2
来源：http://dali.xylfe.cn/Article/details/gt2txuiyqrr.html

[T53] Scala：字符串插值
来源：http://dali.tianlin.xyz/Article/details/gt2rgvcwbvo.html

s"值: $b"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pdeobtli.html

[T54] Scala：集合映射
来源：http://dali.iojbl.cn/Article/details/gt2fyfuypik.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.shuidangran.top/Article/details/gt2tuyctovj.html

[T55] Scala：集合过滤
来源：http://dali.sxryk.cn/Article/details/gt2ftpcdyxx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.chenlongwang.top/Article/details/gt2cobeifgm.html

[T56] Scala：样例类
来源：http://dali.mhx1999.top/Article/details/gt2lylimzht.html

case class User(name: String, age: Int)
来源：http://dali.redwolf501.top/Article/details/gt2wumfiafw.html

[T57] Scala：模式匹配
来源：http://dali.birdmap.top/Article/details/gt2txxqghup.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.yueranfly.top/Article/details/gt2vmmvngqj.html

[T58] Scala：函数定义
来源：http://dali.0kj1m.cn/Article/details/gt2cynxronq.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.dianchejie.cn/Article/details/gt2mfwkljyh.html

[T59] Scala：循环
来源：http://dali.yvedp.cn/Article/details/gt2isvlykre.html

for (i <- 1 to 10) println(i)
来源：http://dali.ehwqpu.com/Article/details/gt2anxkfdly.html

[T60] Scala：折叠
来源：http://dali.iojbl.cn/Article/details/gt2pwsvffsu.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.yj20258.top/Article/details/gt2fruahjae.html

================================================================================
来源：http://dali.cdnleiting.top/Article/details/gt2uygfhgal.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.andypj.xyz/Article/details/gt2hytnrpin.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2igtldmjt.html

[U01] Py：创建虚拟环境
来源：http://dali.gaohongyu789.top/Article/details/gt2ryhcccxi.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.xuetiantiany.cn/Article/details/gt2vfzofuos.html

[U02] Py：导出 / 安装依赖
来源：http://dali.bjfxy.top/Article/details/gt2rgfvxdto.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.nwbrower.top/Article/details/gt2txdsdxfg.html

[U03] Py：加载 .env 配置
来源：http://dali.ybcxt.top/Article/details/gt2emefiisf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.andypj.xyz/Article/details/gt2uzelxoop.html

[U04] Py：变量调试打印
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gpvwfzoz.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.bjfxy.top/Article/details/gt2efeokoxr.html

[U05] Py：列表去重且保序
来源：http://dali.zhengqikj.top/Article/details/gt2sjxgvwkw.html

list(dict.fromkeys(arr))
来源：http://dali.vqdsnc.cn/Article/details/gt2tzsnnczw.html

[U06] Py：合并两个字典
来源：http://dali.chenjidiqi.icu/Article/details/gt2xjtqsdld.html

{**a, **b}
来源：http://dali.nanxinkj.top/Article/details/gt2jlpnfkdr.html

[U07] Py：反转字典键值
来源：http://dali.dashuyun.cn/Article/details/gt2iubfzslz.html

{v: k for k, v in d.items()}
来源：http://dali.zhengqikj.top/Article/details/gt2yjqfjvlh.html

[U08] Py：展平二维列表
来源：http://dali.ehwqpu.com/Article/details/gt2stdkyvzo.html

[y for x in nested for y in x]
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cmudqbea.html

[U09] Py：字典取最大值的键
来源：http://dali.yonumen.top/Article/details/gt2llknonrd.html

max(d, key=d.get)
来源：http://dali.gogol.net.cn/Article/details/gt2oalrzqhc.html

[U10] Py：按值排序字典
来源：http://dali.wangshuangyany.cn/Article/details/gt2twhjdnzt.html

dict(sorted(d.items(), key=lambda kv: kv[1]))
来源：http://dali.andypj.xyz/Article/details/gt2eqyptepm.html


<!-- 参考信息 -->