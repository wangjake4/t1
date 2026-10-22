代发 wailian999

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.chenlongwang.top/Article/details/gt2etalqdao.html

[R66] 定时任务
来源：http://dali.zhengqikj.top/Article/details/gt2fdrifhge.html

crontab -e;  crontab -l
来源：http://dali.hywenlv.cn/Article/details/gt2fxlkpllj.html

[R67] 生成随机十六进制串
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nvjtpbnn.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ubvhxhpj.html

[R68] 计算文件校验值
来源：http://dali.zhiwuduotai.top/Article/details/gt2jpfhgeuv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zdqjudy.top/Article/details/gt2uldodhlb.html

[R69] 生成随机密码
来源：http://dali.dianchejie.cn/Article/details/gt2yetzizfd.html

head -c 16 /dev/urandom | base64
来源：http://dali.gogol.net.cn/Article/details/gt2onghzbon.html

[R70] 时间戳与互转
来源：http://dali.meibo888.top/Article/details/gt2hldeohhy.html

date +%s;  date -d @1700000000
来源：http://dali.ehwqpu.com/Article/details/gt2lypgqtox.html

[R71] 日期格式化
来源：http://dali.redwolf501.top/Article/details/gt2ixhrxehc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.bjfxy.top/Article/details/gt2kmaefzgg.html

[R72] 等待端口就绪
来源：http://dali.xylfe.cn/Article/details/gt2nqqpmrxp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hysaishi.cn/Article/details/gt2sdsbtslj.html

[R73] 分割大日志
来源：http://dali.nanxuanxn.top/Article/details/gt2ztoluylq.html

split -l 1000 big.log part_
来源：http://dali.meibo888.top/Article/details/gt2tjbujkvc.html

[R74] 批量重命名
来源：http://dali.xuetiantiany.cn/Article/details/gt2zcevhxhh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yuanzhike.top/Article/details/gt2vcatzzth.html

[R75] 导出环境变量
来源：http://dali.fzhhl.top/Article/details/gt2zkdkoicj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yj20258888.top/Article/details/gt2npjurdkc.html

[R76] 使用临时文件
来源：http://dali.aizwys.cn/Article/details/gt2edsbcytr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rdzxuaoc.html

[R77] 读取用户输入
来源：http://dali.cucudq.cn/Article/details/gt2bcxorqbt.html

read -rp "请输入: " ans
来源：http://dali.meibo888.top/Article/details/gt2ogbvlkfv.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2wnrdouyk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.dashuyun.cn/Article/details/gt2mkiuslnv.html

[R79] 解析命令行选项
来源：http://dali.sweek.top/Article/details/gt2wggvuqvr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jyoumei.cn/Article/details/gt2zmzndzcl.html

[R80] 查看脚本执行耗时
来源：http://dali.yonumen.top/Article/details/gt2xcyehtmb.html

time ./run.sh
来源：http://dali.jianghu66.top/Article/details/gt2xvctsqxw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2czqquewt.html

S. C / C++ 专题
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zhvmidrf.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gt2dwfznpou.html

[S01] C：Hello World
来源：http://dali.havefunace.top/Article/details/gt2mbtgibsg.html

#include <stdio.h>
来源：http://dali.wangshuangyany.cn/Article/details/gt2rmnrtrlf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ppjwa.cn/Article/details/gt2zatspvae.html

[S02] C：变量与格式化输出
来源：http://dali.cdnleiting.top/Article/details/gt2uvcwdeoe.html

int a = 10; printf("%d\n", a);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ppthfmxa.html

[S03] C：读入整数
来源：http://dali.fzhhl.top/Article/details/gt2zadxofrk.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2wstwnahf.html

[S04] C：字符串复制
来源：http://dali.sxryk.cn/Article/details/gt2bjqnfwmf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cqqwz.cn/Article/details/gt2yjifwjni.html

[S05] C：字符串长度
来源：http://dali.zhiwuduotai.top/Article/details/gt2ljmkjlty.html

strlen(s)
来源：http://dali.hywenlv.cn/Article/details/gt2syybpjza.html

[S06] C：字符串比较
来源：http://dali.cqqwz.cn/Article/details/gt2cobfrreo.html

strcmp(a, b) == 0
来源：http://dali.tanke756.top/Article/details/gt2yqzclxsa.html

[S07] C：数组遍历求和
来源：http://dali.havefunace.top/Article/details/gt2nhwvjzzd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.vqdsnc.cn/Article/details/gt2siecftrp.html

[S08] C：动态内存分配与释放
来源：http://dali.shzxlz.cn/Article/details/gt2hgjfeiui.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.haohaochexian.top/Article/details/gt2bhzmiwgt.html

[S09] C：结构体定义与初始化
来源：http://dali.yueranfly.top/Article/details/gt2xmdpyzzf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shuidangran.top/Article/details/gt2pkcbaxcz.html

[S10] C：指针与解引用
来源：http://dali.iojbl.cn/Article/details/gt2vanfmqbw.html

int *p = &a;  *p = 5;
来源：http://dali.smart0.xyz/Article/details/gt2upiekzwt.html

[S11] C：逐行读文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2uyhhcefd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cashguo.top/Article/details/gt2dychbpyc.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.guannengcc.top/Article/details/gt2ctpelzez.html

fclose(f);
来源：http://dali.hnqzz.top/Article/details/gt2rxtxiurc.html

[S12] C：写文件
来源：http://dali.shzxlz.cn/Article/details/gt2gywpmwgh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.chenzaomai.com/Article/details/gt2cyjfkbhr.html

[S13] C：宏定义
来源：http://dali.zhoulong.xyz/Article/details/gt2czburrrq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gzhubu.top/Article/details/gt2zwvdybbc.html

[S14] C：枚举
来源：http://dali.jinqigufen.top/Article/details/gt2headdkbz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lkztxjrb.html

[S15] C：类型转换
来源：http://dali.chenlongwang.top/Article/details/gt2omppsggj.html

(double) a / b
来源：http://dali.daria6918.cn/Article/details/gt2hvbngvqu.html

[S16] C：位操作置位
来源：http://dali.feifeiyinyue.top/Article/details/gt2vjofrqhb.html

x |= (1 << 3);
来源：http://dali.ppjwa.cn/Article/details/gt2zowphusi.html

[S17] C：安全拼接字符串
来源：http://dali.daxiang520.top/Article/details/gt2cvlhqdbq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sweek.top/Article/details/gt2jgygzbym.html

[S18] C：命令行参数
来源：http://dali.cqqwz.cn/Article/details/gt2foqzqfrz.html

int main(int argc, char **argv)
来源：http://dali.chenlongwang.top/Article/details/gt2vqnubksc.html

[S19] C：快速排序
来源：http://dali.wangdashe.top/Article/details/gt2iocjdive.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.snrcjt.cn/Article/details/gt2amllojct.html

[S20] C：二分查找
来源：http://dali.zhengqikj.top/Article/details/gt2mocjdfsh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.andypj.xyz/Article/details/gt2bakamozq.html

[S21] C：字符类别判断
来源：http://dali.kuanghao11.cn/Article/details/gt2ffxcneeu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hnxiangtu.top/Article/details/gt2fvdhjwum.html

[S22] C：字符串转数字
来源：http://dali.haohaochexian.top/Article/details/gt2tzfceyyl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cashguo.top/Article/details/gt2rhyozhqy.html

[S23] C：随机数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ykrrhpss.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.guowangkeji.top/Article/details/gt2xrsvwcav.html

[S24] C：获取本地时间
来源：http://dali.chenzaomai.com/Article/details/gt2vvejqmdc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lyutwobg.html

[S25] C：内存拷贝
来源：http://dali.gzhubu.top/Article/details/gt2twqzpgbw.html

memcpy(dst, src, n);
来源：http://dali.yuxming.cn/Article/details/gt2hfhbqolg.html

[S26] C：内存清零
来源：http://dali.chenlongwang.top/Article/details/gt2wrvwytot.html

memset(a, 0, sizeof a);
来源：http://dali.wangdashe.top/Article/details/gt2mzcanejc.html

[S27] C：定义常量
来源：http://dali.redwolf501.top/Article/details/gt2ntaixlrx.html

const double PI = 3.14159;
来源：http://dali.gzhubu.top/Article/details/gt2ratyrihy.html

[S28] C：静态变量
来源：http://dali.xziqi.cn/Article/details/gt2adrnttzv.html

static int counter = 0;
来源：http://dali.havefunace.top/Article/details/gt2ksvysngl.html

[S29] C：变参函数
来源：http://dali.aizwys.cn/Article/details/gt2vkgskyfl.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yanxiufei.cn/Article/details/gt2eeouvxye.html

[S30] C：头文件保护
来源：http://dali.iojbl.cn/Article/details/gt2mfvdbrrh.html

#ifndef X_H
来源：http://dali.fzhhl.top/Article/details/gt2gwiwbupo.html

#define X_H
来源：http://dali.jinqigufen.top/Article/details/gt2raivmcpv.html

#endif
来源：http://dali.cqqwz.cn/Article/details/gt2uzojrczb.html

[S31] C++：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gt2mrsfexss.html

#include <iostream>
来源：http://dali.chenzaomai.com/Article/details/gt2kqoypuqx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ehwqpu.com/Article/details/gt2bdevyujr.html

[S32] C++：字符串
来源：http://dali.sufxvd.cn/Article/details/gt2udnklery.html

std::string s = "hi";  s += "!";
来源：http://dali.shuidangran.top/Article/details/gt2xydlutit.html

[S33] C++：vector 增删
来源：http://dali.chenzaomai.com/Article/details/gt2svgocrzv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2oaqfomsz.html

[S34] C++：遍历 vector
来源：http://dali.quarkkingdee.top/Article/details/gt2odyzagxf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yanxiufei.cn/Article/details/gt2hxdbeqds.html

[S35] C++：map
来源：http://dali.snrcjt.cn/Article/details/gt2aeewqhpr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.c1oappe.top/Article/details/gt2niznhbvx.html

[S36] C++：unordered_map
来源：http://dali.zycfv.cn/Article/details/gt2qjbijsyr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.daxiang520.top/Article/details/gt2wuumadrh.html

[S37] C++：set
来源：http://dali.gogol.net.cn/Article/details/gt2lhqfwbbc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sysykeji.top/Article/details/gt2qddprahc.html

[S38] C++：排序
来源：http://dali.xinyue.icu/Article/details/gt2rkqfviqw.html

std::sort(v.begin(), v.end());
来源：http://dali.jlsjyb.cn/Article/details/gt2uicglgvu.html

[S39] C++：自定义比较器排序
来源：http://dali.shuidangran.top/Article/details/gt2wwmbdxqv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cqqwz.cn/Article/details/gt2ywuqfiwr.html

[S40] C++：查找元素
来源：http://dali.feifeiyinyue.top/Article/details/gt2akgcyldg.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.316326.xyz/Article/details/gt2nlzokohm.html

[S41] C++：类与构造函数
来源：http://dali.yonumen.top/Article/details/gt2afwsqkse.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.0kj1m.cn/Article/details/gt2ekltedcb.html

[S42] C++：继承与虚函数
来源：http://dali.hysaishi.cn/Article/details/gt2fuzykuns.html

class B : public Base { public: void f() override {} };
来源：http://dali.dashuyun.cn/Article/details/gt2qjszvrde.html

[S43] C++：智能指针
来源：http://dali.jinqigufen.top/Article/details/gt2rgkxjcpb.html

auto p = std::make_unique<int>(5);
来源：http://dali.jyoumei.cn/Article/details/gt2jsfgohdc.html

[S44] C++：引用传参
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2crablvgc.html

void inc(int &x) { ++x; }
来源：http://dali.cucudq.cn/Article/details/gt2bteitznv.html

[S45] C++：lambda
来源：http://dali.cheryme.top/Article/details/gt2nmrflbph.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.chenjidiqi.icu/Article/details/gt2ydpqhwbq.html

[S46] C++：函数模板
来源：http://dali.vqdsnc.cn/Article/details/gt2saqdxpip.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.ppjwa.cn/Article/details/gt2lobgxrlk.html

[S47] C++：结构化绑定遍历
来源：http://dali.yonumen.top/Article/details/gt2xjebtemj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.fzhhl.top/Article/details/gt2juidpmjw.html

[S48] C++：逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gt2jazkrkch.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hongshengwenyu.top/Article/details/gt2sgdvsoyp.html

while (std::getline(in, line)) { }
来源：http://dali.meibo888.top/Article/details/gt2ljtirdam.html

[S49] C++：写文件
来源：http://dali.0kj1m.cn/Article/details/gt2jvpexamk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zdqjudy.top/Article/details/gt2xrimsvhv.html

[S50] C++：格式化数字
来源：http://dali.yonumen.top/Article/details/gt2uvrcpddj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sxryk.cn/Article/details/gt2xyjjycsl.html

[S51] C++：显式类型转换
来源：http://dali.hfpthk.cn/Article/details/gt2agyfbfwu.html

static_cast<double>(a) / b
来源：http://dali.chenlongwang.top/Article/details/gt2mbzbglnn.html

[S52] C++：const 与 noexcept
来源：http://dali.chenjidiqi.icu/Article/details/gt2hafcorfa.html

int size() const noexcept { return n_; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2izgiuzpu.html

[S53] C++：移动语义
来源：http://dali.tanke756.top/Article/details/gt2zesgplhr.html

std::vector<int> w = std::move(v);
来源：http://dali.daria6918.cn/Article/details/gt2ozdxpnwd.html

[S54] C++：异常处理
来源：http://dali.snrcjt.cn/Article/details/gt2obpbtakw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.pengpengdd.cyou/Article/details/gt2mngiewip.html

[S55] C++：结构化绑定
来源：http://dali.316326.xyz/Article/details/gt2vzhyqjes.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhijiandao.cn/Article/details/gt2lidysziy.html

[S56] C++：optional
来源：http://dali.guannengcc.top/Article/details/gt2wmtgwusj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.svipenyu.cn/Article/details/gt2tweopzqc.html

[S57] C++：编译期常量
来源：http://dali.andypj.xyz/Article/details/gt2hnztjdrq.html

constexpr int N = 10;
来源：http://dali.wangdashe.top/Article/details/gt2pzpkagcn.html

[S58] C++：命名空间
来源：http://dali.zhixingplan.top/Article/details/gt2jjribfnh.html

namespace ns { int f() { return 1; } }
来源：http://dali.zdqjudy.top/Article/details/gt2plwifurz.html

[S59] C++：静态断言
来源：http://dali.aibaodan.cn/Article/details/gt2zybytbnp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yj20258.top/Article/details/gt2lzfhonrj.html

[S60] C++：遍历并删除元素
来源：http://dali.meibo888.top/Article/details/gt2oqhatlet.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xziqi.cn/Article/details/gt2xfiywgqg.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2hzvazowy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xuetiantiany.cn/Article/details/gt2wefcmccm.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2oavsxoac.html

[T01] Kotlin：Hello World
来源：http://dali.pycfn.com/Article/details/gt2gsauipdp.html

println("Hello")
来源：http://dali.wangdashe.top/Article/details/gt2qouubcer.html

[T02] Kotlin：变量
来源：http://dali.yuxming.cn/Article/details/gt2ooxifktq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.redwolf501.top/Article/details/gt2ghbgrxuc.html

[T03] Kotlin：字符串模板
来源：http://dali.yvedp.cn/Article/details/gt2qltlkrdk.html

"值: $b"
来源：http://dali.dashuyun.cn/Article/details/gt2grhhkpgq.html

[T04] Kotlin：空安全
来源：http://dali.xziqi.cn/Article/details/gt2kkfxsixt.html

val n: String? = null;  n?.length
来源：http://dali.iojbl.cn/Article/details/gt2uqbvxpyw.html

[T05] Kotlin：when 表达式
来源：http://dali.yuxming.cn/Article/details/gt2jkdlxckd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sufxvd.cn/Article/details/gt2ichgnjlw.html

[T06] Kotlin：集合映射
来源：http://dali.xylfe.cn/Article/details/gt2xiwvjjzq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cucudq.cn/Article/details/gt2kpctekca.html

[T07] Kotlin：集合过滤
来源：http://dali.jinqigfzy.top/Article/details/gt2efmtqcpi.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zamlsswo.html

[T08] Kotlin：数据类
来源：http://dali.jyoumei.cn/Article/details/gt2nipoctff.html

data class User(val name: String, val age: Int)
来源：http://dali.birdmap.top/Article/details/gt2wiqkwqpk.html

[T09] Kotlin：扩展函数
来源：http://dali.cheryme.top/Article/details/gt2usnbeqvp.html

fun String.exclaim() = this + "!"
来源：http://dali.svipenyu.cn/Article/details/gt2tfcpjwpy.html

[T10] Kotlin：默认参数
来源：http://dali.hnqzz.top/Article/details/gt2ohswozvn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.guowangkeji.top/Article/details/gt2uaxbfuus.html

[T11] Kotlin：协程
来源：http://dali.xuanzx.com/Article/details/gt2ijkbgric.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gaohongyu789.top/Article/details/gt2wwaugrpy.html

[T12] Kotlin：解构声明
来源：http://dali.zhiwuduotai.top/Article/details/gt2ghkrwfut.html

val (a, b) = Pair(1, 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2lkkrvfxh.html

[T13] Kotlin：只读 Map
来源：http://dali.ivvv.top/Article/details/gt2euyucyzx.html

val m = mapOf("a" to 1)
来源：http://dali.zhengqikj.top/Article/details/gt2ipzgyzuy.html

[T14] Kotlin：循环
来源：http://dali.yongpay.top/Article/details/gt2adnlppsi.html

for (i in 1..10) println(i)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gurtmedp.html

[T15] Kotlin：接口
来源：http://dali.zycfv.cn/Article/details/gt2fzcswplw.html

interface Shape { fun area(): Double }
来源：http://dali.jyoumei.cn/Article/details/gt2kqznosrw.html

[T16] Swift：Hello World
来源：http://dali.zhixingplan.top/Article/details/gt2hccitwsa.html

print("Hello")
来源：http://dali.xuetiantiany.cn/Article/details/gt2vogaupcs.html

[T17] Swift：变量与常量
来源：http://dali.nanxinkj.top/Article/details/gt2mwulsyve.html

var a = 1;  let b = 2
来源：http://dali.svipenyu.cn/Article/details/gt2imwfvvxi.html

[T18] Swift：字符串插值
来源：http://dali.guowangkeji.top/Article/details/gt2szkohkmh.html

"值: \(b)"
来源：http://dali.xuetiantiany.cn/Article/details/gt2kgoervve.html

[T19] Swift：可选绑定
来源：http://dali.yanxiufei.cn/Article/details/gt2ehxetzle.html

if let n = opt { print(n) }
来源：http://dali.wangdashe.top/Article/details/gt2uwesyene.html

[T20] Swift：数组操作
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ljvanyrr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.9152youxi.cn/Article/details/gt2qzbmlksl.html

[T21] Swift：遍历
来源：http://dali.yanxiufei.cn/Article/details/gt2vlsnoapa.html

for x in a { print(x) }
来源：http://dali.ydzc1.top/Article/details/gt2hqstmjdx.html

[T22] Swift：字典
来源：http://dali.dianchejie.cn/Article/details/gt2wspubfuj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yonumen.top/Article/details/gt2scxjqwhj.html

[T23] Swift：函数
来源：http://dali.nanxuanxn.top/Article/details/gt2orlrxnzc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hnxiangtu.top/Article/details/gt2utvgixpw.html

[T24] Swift：闭包
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2efpyhtqv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.cucudq.cn/Article/details/gt2cewbneiy.html

[T25] Swift：结构体
来源：http://dali.cdnleiting.top/Article/details/gt2gcvwfzwt.html

struct P { var x: Int }
来源：http://dali.wangdashe.top/Article/details/gt2kuhsnpzj.html

[T26] Swift：类与重写
来源：http://dali.yueranfly.top/Article/details/gt2myikasvl.html

class A: Base { override func f() {} }
来源：http://dali.bjfxy.top/Article/details/gt2hbxaiiim.html

[T27] Swift：错误处理
来源：http://dali.ybcxt.top/Article/details/gt2fxadsrjn.html

do { try f() } catch { print(error) }
来源：http://dali.meibo888.top/Article/details/gt2tkkvdcoy.html

[T28] Swift：枚举
来源：http://dali.jqgufenzy.top/Article/details/gt2bmqdmywa.html

enum Color { case red, green }
来源：http://dali.jinqigufen.top/Article/details/gt2tjidacrx.html

[T29] Swift：guard 提前返回
来源：http://dali.wangshuangyany.cn/Article/details/gt2bketoyqs.html

guard let x = opt else { return }
来源：http://dali.sysykeji.top/Article/details/gt2hkxhfyez.html

[T30] Swift：协议
来源：http://dali.316326.xyz/Article/details/gt2mgwkgdhm.html

protocol Shape { func area() -> Double }
来源：http://dali.jqgufenzy.top/Article/details/gt2ogwuwcjf.html

[T31] Lua：Hello World
来源：http://dali.tanke756.top/Article/details/gt2fczulnzc.html

print("Hello")
来源：http://dali.jqgfzy.top/Article/details/gt2tlwkijqr.html

[T32] Lua：局部变量
来源：http://dali.smart0.xyz/Article/details/gt2zywxviye.html

local a = 1
来源：http://dali.yanxiufei.cn/Article/details/gt2uhfjefbl.html

[T33] Lua：表（数组）
来源：http://dali.daxiang520.top/Article/details/gt2ypeciecy.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xinyue.icu/Article/details/gt2vrkjxqmp.html

[T34] Lua：遍历表
来源：http://dali.redwolf501.top/Article/details/gt2efjlzjth.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hnxiangtu.top/Article/details/gt2clrwwlac.html

[T35] Lua：字典表
来源：http://dali.redwolf501.top/Article/details/gt2ysmscbjw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.c1oappe.top/Article/details/gt2nqzfeynq.html

[T36] Lua：函数
来源：http://dali.quarkkingdee.top/Article/details/gt2vxtjfkwp.html

function add(a, b) return a + b end
来源：http://dali.daria6918.cn/Article/details/gt2sqjscccz.html

[T37] Lua：字符串拼接
来源：http://dali.guannengcc.top/Article/details/gt2xhcskagc.html

"a" .. "b"
来源：http://dali.sxryk.cn/Article/details/gt2wdeyzqzq.html

[T38] Lua：条件
来源：http://dali.sweek.top/Article/details/gt2ogfbfesx.html

if x > 0 then print("正") end
来源：http://dali.hnxiangtu.top/Article/details/gt2kratwkiw.html

[T39] Lua：模式匹配
来源：http://dali.yuanzhike.top/Article/details/gt2qagesmvx.html

string.find(s, "%d+")
来源：http://dali.yangfankeji.com/Article/details/gt2zuwosdtx.html

[T40] Lua：元表
来源：http://dali.yueranfly.top/Article/details/gt2llkedalw.html

setmetatable({}, { __index = base })
来源：http://dali.aibaodan.cn/Article/details/gt2nqqzalel.html

[T41] Perl：Hello World
来源：http://dali.nwbrower.top/Article/details/gt2vktsbwbq.html

print "Hello\n";
来源：http://dali.aizwys.cn/Article/details/gt2yketfbte.html

[T42] Perl：变量类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2npzvhuhf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhengqikj.top/Article/details/gt2ldgfgtis.html

[T43] Perl：字符串插值
来源：http://dali.xinyue.icu/Article/details/gt2ucuuhhrg.html

"值: $a"
来源：http://dali.cheryme.top/Article/details/gt2hmamsbbc.html

[T44] Perl：条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wtszkmpd.html

if ($a > 0) { print "正"; }
来源：http://dali.zycfv.cn/Article/details/gt2rinwxdwu.html

[T45] Perl：数组遍历
来源：http://dali.zhiwuduotai.top/Article/details/gt2jsqeirnr.html

for my $x (@arr) { print $x; }
来源：http://dali.gogol.net.cn/Article/details/gt2ueafwzzf.html

[T46] Perl：哈希操作
来源：http://dali.guowangkeji.top/Article/details/gt2pnpatmfl.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.iojbl.cn/Article/details/gt2amzjdbyc.html

[T47] Perl：正则捕获
来源：http://dali.andypj.xyz/Article/details/gt2ocqdxdoa.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jvimwmvi.html

[T48] Perl：正则替换
来源：http://dali.sysykeji.top/Article/details/gt2fmqkswrp.html

$s =~ s/old/new/g;
来源：http://dali.nanxuanxn.top/Article/details/gt2tctoxpkg.html

[T49] Perl：函数
来源：http://dali.jyoumei.cn/Article/details/gt2ynzehuqd.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.smart0.xyz/Article/details/gt2egfedjoc.html

[T50] Perl：逐行读文件
来源：http://dali.yonumen.top/Article/details/gt2dslqwprh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yvedp.cn/Article/details/gt2pxhilbbx.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.cucudq.cn/Article/details/gt2ihohlnaa.html

[T51] Scala：Hello World
来源：http://dali.chenlongwang.top/Article/details/gt2ufrmkjte.html

println("Hello")
来源：http://dali.andypj.xyz/Article/details/gt2uixmouiw.html

[T52] Scala：变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2prhydhrn.html

val a = 1;  var b = 2
来源：http://dali.cdnleiting.top/Article/details/gt2bxceoipd.html

[T53] Scala：字符串插值
来源：http://dali.gotoacloud.top/Article/details/gt2nvkqmkvp.html

s"值: $b"
来源：http://dali.wangdashe.top/Article/details/gt2bzzjmkis.html

[T54] Scala：集合映射
来源：http://dali.gzhubu.top/Article/details/gt2wfzbegiy.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.birdmap.top/Article/details/gt2nadbxdnv.html

[T55] Scala：集合过滤
来源：http://dali.zdqjudy.top/Article/details/gt2nvpugpgd.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.tianlin.xyz/Article/details/gt2khgewiwp.html

[T56] Scala：样例类
来源：http://dali.jlsjyb.cn/Article/details/gt2aibxrxcd.html

case class User(name: String, age: Int)
来源：http://dali.hammf.cn/Article/details/gt2onfvafnk.html

[T57] Scala：模式匹配
来源：http://dali.ivvv.top/Article/details/gt2gihkntkt.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.chenzaomai.com/Article/details/gt2pujpgegl.html

[T58] Scala：函数定义
来源：http://dali.yvedp.cn/Article/details/gt2haylirsl.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.svipenyu.cn/Article/details/gt2pukazphx.html

[T59] Scala：循环
来源：http://dali.ehwqpu.com/Article/details/gt2qfasuhwl.html

for (i <- 1 to 10) println(i)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2llqmhpje.html

[T60] Scala：折叠
来源：http://dali.gaohongyu789.top/Article/details/gt2ckmdszya.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.bjfxy.top/Article/details/gt2kvqpnrbg.html

================================================================================
来源：http://dali.daxiang520.top/Article/details/gt2uanksegz.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.bjfxy.top/Article/details/gt2pjesdsxl.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gt2nmqqnjir.html

[U01] Py：创建虚拟环境
来源：http://dali.pengpengdd.cyou/Article/details/gt2rktozzwf.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.gotoacloud.top/Article/details/gt2bdiugacv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.jiagoushi.top/Article/details/gt2ideccoaj.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.snrcjt.cn/Article/details/gt2arekdmig.html

[U03] Py：加载 .env 配置
来源：http://dali.jyoumei.cn/Article/details/gt2pslculcw.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.sufxvd.cn/Article/details/gt2vvfuazoh.html

[U04] Py：变量调试打印
来源：http://dali.yj20258.top/Article/details/gt2xqnqizvo.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yanxiufei.cn/Article/details/gt2nmjzydih.html

[U05] Py：列表去重且保序
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2azemyhep.html

list(dict.fromkeys(arr))
来源：http://dali.jyoumei.cn/Article/details/gt2uwcvwyqb.html

[U06] Py：合并两个字典
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mckhukcz.html

{**a, **b}
来源：http://dali.jinqigfzy.top/Article/details/gt2jloduluh.html


<!-- 参考信息 -->