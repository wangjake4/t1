代发 wailian999

openssl rand -hex 16
来源：http://dali.chenlongwang.top/Article/details/gt2zbiniaee.html

[R68] 计算文件校验值
来源：http://dali.zycfv.cn/Article/details/gt2veucguey.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.pycfn.com/Article/details/gt2kbxrnguh.html

[R69] 生成随机密码
来源：http://dali.svipenyu.cn/Article/details/gt2dxbtcmwk.html

head -c 16 /dev/urandom | base64
来源：http://dali.yj202588.top/Article/details/gt2vqqemlgc.html

[R70] 时间戳与互转
来源：http://dali.zhiwuduotai.top/Article/details/gt2ibarepyz.html

date +%s;  date -d @1700000000
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wnkubswv.html

[R71] 日期格式化
来源：http://dali.ydzc1.top/Article/details/gt2jyusuazl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenjidiqi.icu/Article/details/gt2lpugrkvt.html

[R72] 等待端口就绪
来源：http://dali.fzhhl.top/Article/details/gt2qacvovyj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhoulong.xyz/Article/details/gt2iiewuzxn.html

[R73] 分割大日志
来源：http://dali.zhengqikj.top/Article/details/gt2uizohshe.html

split -l 1000 big.log part_
来源：http://dali.andypj.xyz/Article/details/gt2pejillbe.html

[R74] 批量重命名
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cphquyex.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hammf.cn/Article/details/gt2jxpwtwbw.html

[R75] 导出环境变量
来源：http://dali.sxryk.cn/Article/details/gt2aupocbae.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.andypj.xyz/Article/details/gt2rtxmiufs.html

[R76] 使用临时文件
来源：http://dali.snrcjt.cn/Article/details/gt2rozmwrdb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sxryk.cn/Article/details/gt2snwxhnhf.html

[R77] 读取用户输入
来源：http://dali.ybcxt.top/Article/details/gt2jqrxtnvk.html

read -rp "请输入: " ans
来源：http://dali.chenjidiqi.icu/Article/details/gt2tleccylq.html

[R78] 交互式菜单
来源：http://dali.kuanghao11.cn/Article/details/gt2fwcxbdbx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jeicynlc.html

[R79] 解析命令行选项
来源：http://dali.ehwqpu.com/Article/details/gt2jsbrpkzo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.fengsongda.top/Article/details/gt2dghodldl.html

[R80] 查看脚本执行耗时
来源：http://dali.zhiwuduotai.top/Article/details/gt2cmwjdonc.html

time ./run.sh
来源：http://dali.shangyingyoupin.top/Article/details/gt2nvhqlbew.html

================================================================================
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kddvjyld.html

S. C / C++ 专题
来源：http://dali.c1oappe.top/Article/details/gt2vaqtltjj.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gt2dphufrow.html

[S01] C：Hello World
来源：http://dali.zhixingplan.top/Article/details/gt2cliobnnt.html

#include <stdio.h>
来源：http://dali.jianghu66.top/Article/details/gt2wdhaskqu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.meibo888.top/Article/details/gt2thyxafsb.html

[S02] C：变量与格式化输出
来源：http://dali.chenzaomai.com/Article/details/gt2jabmisze.html

int a = 10; printf("%d\n", a);
来源：http://dali.gzhubu.top/Article/details/gt2uwokglnt.html

[S03] C：读入整数
来源：http://dali.tanke756.top/Article/details/gt2rpcvpydk.html

int x; scanf("%d", &x);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vqcrprhy.html

[S04] C：字符串复制
来源：http://dali.andypj.xyz/Article/details/gt2gzevmyfa.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qojedrjo.html

[S05] C：字符串长度
来源：http://dali.tianlin.xyz/Article/details/gt2hwyqjbdm.html

strlen(s)
来源：http://dali.jiagoushi.top/Article/details/gt2ufgnrqmv.html

[S06] C：字符串比较
来源：http://dali.dianchejie.cn/Article/details/gt2baunyqcp.html

strcmp(a, b) == 0
来源：http://dali.jinqigfzy.top/Article/details/gt2hklsyazt.html

[S07] C：数组遍历求和
来源：http://dali.vqdsnc.cn/Article/details/gt2kkhqxsby.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wtfuiihm.html

[S08] C：动态内存分配与释放
来源：http://dali.yuanzhike.top/Article/details/gt2dbegggps.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zdqjudy.top/Article/details/gt2srfpkdmb.html

[S09] C：结构体定义与初始化
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2onhauwza.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cashguo.top/Article/details/gt2ntkampgf.html

[S10] C：指针与解引用
来源：http://dali.nanxinkj.top/Article/details/gt2lontsbec.html

int *p = &a;  *p = 5;
来源：http://dali.pengpengdd.cyou/Article/details/gt2avzgmzoq.html

[S11] C：逐行读文件
来源：http://dali.xziqi.cn/Article/details/gt2sdiiiybh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.316326.xyz/Article/details/gt2uviesrtk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cheryme.top/Article/details/gt2wvjzbawt.html

fclose(f);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2opwqgpma.html

[S12] C：写文件
来源：http://dali.hnqzz.top/Article/details/gt2gbyueobt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj20258888.top/Article/details/gt2xkykfduy.html

[S13] C：宏定义
来源：http://dali.birdmap.top/Article/details/gt2qqdtfcwm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yj20258888.top/Article/details/gt2liczpyih.html

[S14] C：枚举
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pthffopm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gaohongyu789.top/Article/details/gt2yixqauly.html

[S15] C：类型转换
来源：http://dali.cdnleiting.top/Article/details/gt2oqggwalk.html

(double) a / b
来源：http://dali.aizwys.cn/Article/details/gt2dxumcoap.html

[S16] C：位操作置位
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2dcxcrrrd.html

x |= (1 << 3);
来源：http://dali.jqgfzy.top/Article/details/gt2qgjponus.html

[S17] C：安全拼接字符串
来源：http://dali.jyoumei.cn/Article/details/gt2buvvbohf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jyoumei.cn/Article/details/gt2etqwftac.html

[S18] C：命令行参数
来源：http://dali.nanxinkj.top/Article/details/gt2zcrclcna.html

int main(int argc, char **argv)
来源：http://dali.yangfankeji.com/Article/details/gt2xplgfbcc.html

[S19] C：快速排序
来源：http://dali.svipenyu.cn/Article/details/gt2pbblucmt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hnxiangtu.top/Article/details/gt2pjbtyjqf.html

[S20] C：二分查找
来源：http://dali.jinqigfzy.top/Article/details/gt2hfzuvrkj.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gt2iubyblli.html

[S21] C：字符类别判断
来源：http://dali.shangyingyoupin.top/Article/details/gt2tgzbhmmv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yj20258888.top/Article/details/gt2yehnsyjr.html

[S22] C：字符串转数字
来源：http://dali.c1oappe.top/Article/details/gt2imkkhxqt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xylfe.cn/Article/details/gt2dliufqvq.html

[S23] C：随机数
来源：http://dali.aibaodan.cn/Article/details/gt2vhzjctqv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gzhubu.top/Article/details/gt2orvvqspk.html

[S24] C：获取本地时间
来源：http://dali.cdnleiting.top/Article/details/gt2awhkstcv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shuidangran.top/Article/details/gt2kvblniwu.html

[S25] C：内存拷贝
来源：http://dali.sweek.top/Article/details/gt2ievkieuo.html

memcpy(dst, src, n);
来源：http://dali.pengpengdd.cyou/Article/details/gt2vbxoqokh.html

[S26] C：内存清零
来源：http://dali.chenzaomai.com/Article/details/gt2yjrgimzw.html

memset(a, 0, sizeof a);
来源：http://dali.havefunace.top/Article/details/gt2racacxdw.html

[S27] C：定义常量
来源：http://dali.dashuyun.cn/Article/details/gt2puapvtnd.html

const double PI = 3.14159;
来源：http://dali.andypj.xyz/Article/details/gt2jeovkovh.html

[S28] C：静态变量
来源：http://dali.yonumen.top/Article/details/gt2vgjuisey.html

static int counter = 0;
来源：http://dali.pengpengdd.cyou/Article/details/gt2byrbjhuq.html

[S29] C：变参函数
来源：http://dali.nanxuanxn.top/Article/details/gt2esqffruh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hysaishi.cn/Article/details/gt2kxtvrnrf.html

[S30] C：头文件保护
来源：http://dali.feifeiyinyue.top/Article/details/gt2kmafikat.html

#ifndef X_H
来源：http://dali.fzhhl.top/Article/details/gt2loulxuak.html

#define X_H
来源：http://dali.cdnleiting.top/Article/details/gt2yeybzskq.html

#endif
来源：http://dali.xuetiantiany.cn/Article/details/gt2lnakdydg.html

[S31] C++：Hello World
来源：http://dali.c1oappe.top/Article/details/gt2yqsxkiyd.html

#include <iostream>
来源：http://dali.dashuyun.cn/Article/details/gt2xskzhgyb.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cqqwz.cn/Article/details/gt2gtcbiedq.html

[S32] C++：字符串
来源：http://dali.xinyue.icu/Article/details/gt2drrbrbqf.html

std::string s = "hi";  s += "!";
来源：http://dali.ppjwa.cn/Article/details/gt2vpoouvir.html

[S33] C++：vector 增删
来源：http://dali.ehwqpu.com/Article/details/gt2wrzbqvnh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.iojbl.cn/Article/details/gt2peybapdi.html

[S34] C++：遍历 vector
来源：http://dali.316326.xyz/Article/details/gt2qwxtdzmp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.daxiang520.top/Article/details/gt2hntqnddp.html

[S35] C++：map
来源：http://dali.sweek.top/Article/details/gt2agrincgz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenzaomai.com/Article/details/gt2nmaxbnlw.html

[S36] C++：unordered_map
来源：http://dali.meibo888.top/Article/details/gt2yhnalsvp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxuanxn.top/Article/details/gt2yttbvksn.html

[S37] C++：set
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ppzexnsz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2wsicpuvw.html

[S38] C++：排序
来源：http://dali.nanxuanxn.top/Article/details/gt2ajnvnrra.html

std::sort(v.begin(), v.end());
来源：http://dali.zhixingplan.top/Article/details/gt2zhqdmwyy.html

[S39] C++：自定义比较器排序
来源：http://dali.jinqigfzy.top/Article/details/gt2jlbbxhgg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenzaomai.com/Article/details/gt2hyeuepgg.html

[S40] C++：查找元素
来源：http://dali.tian-w.cn/Article/details/gt2rakhqgns.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gzhubu.top/Article/details/gt2smdmxejl.html

[S41] C++：类与构造函数
来源：http://dali.chenzaomai.com/Article/details/gt2guuxjnwx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shangyingyoupin.top/Article/details/gt2iklstehb.html

[S42] C++：继承与虚函数
来源：http://dali.quarkkingdee.top/Article/details/gt2mfcpylds.html

class B : public Base { public: void f() override {} };
来源：http://dali.shangyingyoupin.top/Article/details/gt2jfxbykxh.html

[S43] C++：智能指针
来源：http://dali.fengsongda.top/Article/details/gt2nvaaxyao.html

auto p = std::make_unique<int>(5);
来源：http://dali.yueranfly.top/Article/details/gt2ynnbfewu.html

[S44] C++：引用传参
来源：http://dali.svipenyu.cn/Article/details/gt2qpcfwjct.html

void inc(int &x) { ++x; }
来源：http://dali.ydzc1.top/Article/details/gt2yxiadhgo.html

[S45] C++：lambda
来源：http://dali.shuidangran.top/Article/details/gt2ikzolzza.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.feifeiyinyue.top/Article/details/gt2pyyzqpkp.html

[S46] C++：函数模板
来源：http://dali.cashguo.top/Article/details/gt2ugehyihk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.tanke756.top/Article/details/gt2pbcwnvak.html

[S47] C++：结构化绑定遍历
来源：http://dali.tanke756.top/Article/details/gt2vfnqsroo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj20258.top/Article/details/gt2vpdkbhco.html

[S48] C++：逐行读文件
来源：http://dali.gogol.net.cn/Article/details/gt2sbcmsjlu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.birdmap.top/Article/details/gt2mkzragxc.html

while (std::getline(in, line)) { }
来源：http://dali.jyoumei.cn/Article/details/gt2pyxaabwz.html

[S49] C++：写文件
来源：http://dali.wangshuangyany.cn/Article/details/gt2bmqqqsbv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xuetiantiany.cn/Article/details/gt2uzzthdhn.html

[S50] C++：格式化数字
来源：http://dali.gogol.net.cn/Article/details/gt2kqkngxzd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.9152youxi.cn/Article/details/gt2rvmisdrw.html

[S51] C++：显式类型转换
来源：http://dali.ehwqpu.com/Article/details/gt2bqsrdpim.html

static_cast<double>(a) / b
来源：http://dali.xylfe.cn/Article/details/gt2ukamblyl.html

[S52] C++：const 与 noexcept
来源：http://dali.fengsongda.top/Article/details/gt2nwwiqzye.html

int size() const noexcept { return n_; }
来源：http://dali.ybcxt.top/Article/details/gt2scldoyna.html

[S53] C++：移动语义
来源：http://dali.cashguo.top/Article/details/gt2lstrouzc.html

std::vector<int> w = std::move(v);
来源：http://dali.quarkkingdee.top/Article/details/gt2agykqozf.html

[S54] C++：异常处理
来源：http://dali.hywenlv.cn/Article/details/gt2dsfrrsrm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.c1oappe.top/Article/details/gt2ndcajpzu.html

[S55] C++：结构化绑定
来源：http://dali.zhijiandao.cn/Article/details/gt2ylwvliuv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.aibaodan.cn/Article/details/gt2dhxqjrgm.html

[S56] C++：optional
来源：http://dali.wangdashe.top/Article/details/gt2cdijczae.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yonumen.top/Article/details/gt2pornyusm.html

[S57] C++：编译期常量
来源：http://dali.nanxinkj.top/Article/details/gt2vnblbkwp.html

constexpr int N = 10;
来源：http://dali.fengsongda.top/Article/details/gt2tkxkthlw.html

[S58] C++：命名空间
来源：http://dali.gzhubu.top/Article/details/gt2qciaryuo.html

namespace ns { int f() { return 1; } }
来源：http://dali.316326.xyz/Article/details/gt2oijzfehw.html

[S59] C++：静态断言
来源：http://dali.tanke756.top/Article/details/gt2kgzqzyrf.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sweek.top/Article/details/gt2xivdnhte.html

[S60] C++：遍历并删除元素
来源：http://dali.xziqi.cn/Article/details/gt2zhlemook.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.quarkkingdee.top/Article/details/gt2tdfhpnun.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2riayomwt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.redwolf501.top/Article/details/gt2khtwnngb.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2pmiwzyts.html

[T01] Kotlin：Hello World
来源：http://dali.yj202588.top/Article/details/gt2immhemdu.html

println("Hello")
来源：http://dali.yueranfly.top/Article/details/gt2xkqpqmwp.html

[T02] Kotlin：变量
来源：http://dali.aizwys.cn/Article/details/gt2wkxuqsiu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.sweek.top/Article/details/gt2znhsdyst.html

[T03] Kotlin：字符串模板
来源：http://dali.guowangkeji.top/Article/details/gt2cvjsgkxo.html

"值: $b"
来源：http://dali.xziqi.cn/Article/details/gt2emqadlgj.html

[T04] Kotlin：空安全
来源：http://dali.zhixingplan.top/Article/details/gt2zqtozokb.html

val n: String? = null;  n?.length
来源：http://dali.jlsjyb.cn/Article/details/gt2exqnijhm.html

[T05] Kotlin：when 表达式
来源：http://dali.havefunace.top/Article/details/gt2tvkklapo.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jqgufenzy.top/Article/details/gt2kyjguysl.html

[T06] Kotlin：集合映射
来源：http://dali.daria6918.cn/Article/details/gt2guczmtdh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ivvv.top/Article/details/gt2jrbdbhdl.html

[T07] Kotlin：集合过滤
来源：http://dali.ppjwa.cn/Article/details/gt2rqduneor.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.0kj1m.cn/Article/details/gt2jobsmudt.html

[T08] Kotlin：数据类
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kavxmqlo.html

data class User(val name: String, val age: Int)
来源：http://dali.ydzc1.top/Article/details/gt2duatqqpl.html

[T09] Kotlin：扩展函数
来源：http://dali.nanxinkj.top/Article/details/gt2pjkwegcr.html

fun String.exclaim() = this + "!"
来源：http://dali.svipenyu.cn/Article/details/gt2uougffyo.html

[T10] Kotlin：默认参数
来源：http://dali.feifeiyinyue.top/Article/details/gt2vpwyzfao.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xylfe.cn/Article/details/gt2rhojcjhy.html

[T11] Kotlin：协程
来源：http://dali.wangshuangyany.cn/Article/details/gt2juecvucz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2grakmgcy.html

[T12] Kotlin：解构声明
来源：http://dali.kuanghao11.cn/Article/details/gt2swozyxss.html

val (a, b) = Pair(1, 2)
来源：http://dali.guannengcc.top/Article/details/gt2cveyrsql.html

[T13] Kotlin：只读 Map
来源：http://dali.gaohongyu789.top/Article/details/gt2ckjgokow.html

val m = mapOf("a" to 1)
来源：http://dali.zhixingplan.top/Article/details/gt2tphfdzwk.html

[T14] Kotlin：循环
来源：http://dali.pycfn.com/Article/details/gt2tqzdnphb.html

for (i in 1..10) println(i)
来源：http://dali.hnxiangtu.top/Article/details/gt2fhtazxer.html

[T15] Kotlin：接口
来源：http://dali.yongpay.top/Article/details/gt2gboshape.html

interface Shape { fun area(): Double }
来源：http://dali.cqqwz.cn/Article/details/gt2plsztmxb.html

[T16] Swift：Hello World
来源：http://dali.wangdashe.top/Article/details/gt2kvymgobu.html

print("Hello")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vlnlorvq.html

[T17] Swift：变量与常量
来源：http://dali.hammf.cn/Article/details/gt2dapyqqcn.html

var a = 1;  let b = 2
来源：http://dali.yueranfly.top/Article/details/gt2ewznqscn.html

[T18] Swift：字符串插值
来源：http://dali.chenzaomai.com/Article/details/gt2hbrvlmxb.html

"值: \(b)"
来源：http://dali.yuanzhike.top/Article/details/gt2eicsxkox.html

[T19] Swift：可选绑定
来源：http://dali.jianghu66.top/Article/details/gt2zwdrykjm.html

if let n = opt { print(n) }
来源：http://dali.gogol.net.cn/Article/details/gt2hivyymxp.html

[T20] Swift：数组操作
来源：http://dali.haohaochexian.top/Article/details/gt2zmejjiot.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhoulong.xyz/Article/details/gt2kyqpppki.html

[T21] Swift：遍历
来源：http://dali.hongshengwenyu.top/Article/details/gt2xovlgudo.html

for x in a { print(x) }
来源：http://dali.zycfv.cn/Article/details/gt2qqrwzrwo.html

[T22] Swift：字典
来源：http://dali.cqqwz.cn/Article/details/gt2epxvgcqv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.sweek.top/Article/details/gt2xiwtmpln.html

[T23] Swift：函数
来源：http://dali.haohaochexian.top/Article/details/gt2bxziqiom.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ivvv.top/Article/details/gt2bhoaudge.html

[T24] Swift：闭包
来源：http://dali.dashuyun.cn/Article/details/gt2unfvcsrr.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xinyue.icu/Article/details/gt2rksjobbi.html

[T25] Swift：结构体
来源：http://dali.fzhhl.top/Article/details/gt2awfqzijh.html

struct P { var x: Int }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2oxcczyva.html

[T26] Swift：类与重写
来源：http://dali.zhongyouzk.top/Article/details/gt2xclvkdhn.html

class A: Base { override func f() {} }
来源：http://dali.kuanghao11.cn/Article/details/gt2bvxempiu.html

[T27] Swift：错误处理
来源：http://dali.jqgfzy.top/Article/details/gt2nnabnfvq.html

do { try f() } catch { print(error) }
来源：http://dali.shuidangran.top/Article/details/gt2gvsvwwjf.html

[T28] Swift：枚举
来源：http://dali.sysykeji.top/Article/details/gt2bpjcgupw.html

enum Color { case red, green }
来源：http://dali.chenlongwang.top/Article/details/gt2tculadax.html

[T29] Swift：guard 提前返回
来源：http://dali.shanyushiyangtech.top/Article/details/gt2raucwbja.html

guard let x = opt else { return }
来源：http://dali.yuanzhike.top/Article/details/gt2anobcaqj.html

[T30] Swift：协议
来源：http://dali.daria6918.cn/Article/details/gt2jjdmbsyf.html

protocol Shape { func area() -> Double }
来源：http://dali.smart0.xyz/Article/details/gt2dsgmdlqc.html

[T31] Lua：Hello World
来源：http://dali.yuanzhike.top/Article/details/gt2qazsebqc.html

print("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gt2wnbgibez.html

[T32] Lua：局部变量
来源：http://dali.aizwys.cn/Article/details/gt2rlklgakw.html

local a = 1
来源：http://dali.chenjidiqi.icu/Article/details/gt2ctsvrrha.html

[T33] Lua：表（数组）
来源：http://dali.yangfankeji.com/Article/details/gt2hxipstai.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.meibo888.top/Article/details/gt2pngmscgv.html

[T34] Lua：遍历表
来源：http://dali.yj20258888.top/Article/details/gt2jhboukox.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.guowangkeji.top/Article/details/gt2dkyvphsi.html

[T35] Lua：字典表
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ffnzomht.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2agbcxnqi.html

[T36] Lua：函数
来源：http://dali.smart0.xyz/Article/details/gt2lrswyvmu.html

function add(a, b) return a + b end
来源：http://dali.kuanghao11.cn/Article/details/gt2dzmcdczp.html

[T37] Lua：字符串拼接
来源：http://dali.xylfe.cn/Article/details/gt2hnlzerej.html

"a" .. "b"
来源：http://dali.wangshuangyany.cn/Article/details/gt2qxxlzsfx.html

[T38] Lua：条件
来源：http://dali.yonumen.top/Article/details/gt2pckcoxqo.html

if x > 0 then print("正") end
来源：http://dali.hongshengwenyu.top/Article/details/gt2sufbqkck.html

[T39] Lua：模式匹配
来源：http://dali.yangfankeji.com/Article/details/gt2wrtvoqsj.html

string.find(s, "%d+")
来源：http://dali.shangyingyoupin.top/Article/details/gt2knspkkqz.html

[T40] Lua：元表
来源：http://dali.yonumen.top/Article/details/gt2pwcvaenn.html

setmetatable({}, { __index = base })
来源：http://dali.yj202588.top/Article/details/gt2qaejbrtl.html

[T41] Perl：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gt2akyduzdk.html

print "Hello\n";
来源：http://dali.vqdsnc.cn/Article/details/gt2fkkqewcq.html

[T42] Perl：变量类型
来源：http://dali.meibo888.top/Article/details/gt2atotvzix.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.vqdsnc.cn/Article/details/gt2zltsjzzo.html

[T43] Perl：字符串插值
来源：http://dali.fengsongda.top/Article/details/gt2apofpxfp.html

"值: $a"
来源：http://dali.chenjidiqi.icu/Article/details/gt2rdwaehgs.html

[T44] Perl：条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2wxrtjdyp.html

if ($a > 0) { print "正"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2wgeiafti.html

[T45] Perl：数组遍历
来源：http://dali.zhoulong.xyz/Article/details/gt2jspgnexg.html

for my $x (@arr) { print $x; }
来源：http://dali.cqqwz.cn/Article/details/gt2cfltbcnm.html

[T46] Perl：哈希操作
来源：http://dali.svipenyu.cn/Article/details/gt2qdhqkowf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cashguo.top/Article/details/gt2jqqdrpff.html

[T47] Perl：正则捕获
来源：http://dali.hnxiangtu.top/Article/details/gt2diabgzor.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.xziqi.cn/Article/details/gt2cttzyger.html

[T48] Perl：正则替换
来源：http://dali.hnqzz.top/Article/details/gt2jjmpmslz.html

$s =~ s/old/new/g;
来源：http://dali.smart0.xyz/Article/details/gt2lcxtlvqa.html

[T49] Perl：函数
来源：http://dali.ehwqpu.com/Article/details/gt2kpjacjdp.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sweek.top/Article/details/gt2ssoirskn.html

[T50] Perl：逐行读文件
来源：http://dali.yuxming.cn/Article/details/gt2bjifbpxp.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ydzc1.top/Article/details/gt2cinefujg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.mhx1999.top/Article/details/gt2qecdwzfp.html

[T51] Scala：Hello World
来源：http://dali.ivvv.top/Article/details/gt2brjgtrmk.html

println("Hello")
来源：http://dali.nanxuanxn.top/Article/details/gt2qpyzhtza.html

[T52] Scala：变量
来源：http://dali.zhixingplan.top/Article/details/gt2qhhgjwmi.html

val a = 1;  var b = 2
来源：http://dali.zhixingplan.top/Article/details/gt2ikmmyakp.html

[T53] Scala：字符串插值
来源：http://dali.hfpthk.cn/Article/details/gt2dtfsofau.html

s"值: $b"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lzyjiume.html

[T54] Scala：集合映射
来源：http://dali.hywenlv.cn/Article/details/gt2zmmnpdsf.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gzhubu.top/Article/details/gt2fnpbwnvi.html

[T55] Scala：集合过滤
来源：http://dali.aizwys.cn/Article/details/gt2yzpdoomk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hammf.cn/Article/details/gt2esrlcbiz.html

[T56] Scala：样例类
来源：http://dali.nanxinkj.top/Article/details/gt2uwbzkosq.html

case class User(name: String, age: Int)
来源：http://dali.zhiwuduotai.top/Article/details/gt2akkhnusy.html

[T57] Scala：模式匹配
来源：http://dali.smart0.xyz/Article/details/gt2aihwyium.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xuanzx.com/Article/details/gt2xwhyjlrv.html

[T58] Scala：函数定义
来源：http://dali.fengsongda.top/Article/details/gt2qpzcpaqu.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.shzxlz.cn/Article/details/gt2apxuevgo.html

[T59] Scala：循环
来源：http://dali.zhongyouzk.top/Article/details/gt2cddungos.html

for (i <- 1 to 10) println(i)
来源：http://dali.birdmap.top/Article/details/gt2ymarllvi.html

[T60] Scala：折叠
来源：http://dali.fzhhl.top/Article/details/gt2ixosaugl.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.jyoumei.cn/Article/details/gt2cislgeyc.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eecwkllw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.jqgfzy.top/Article/details/gt2oovbfpku.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2bhkzeggj.html

[U01] Py：创建虚拟环境
来源：http://dali.aizwys.cn/Article/details/gt2bhgnrxcg.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.fzhhl.top/Article/details/gt2uenglhim.html

[U02] Py：导出 / 安装依赖
来源：http://dali.0kj1m.cn/Article/details/gt2uvlcxdey.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.iojbl.cn/Article/details/gt2ecxfurvo.html

[U03] Py：加载 .env 配置
来源：http://dali.zhoulong.xyz/Article/details/gt2mnjzjjxf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.daxiang520.top/Article/details/gt2cpzufkrg.html

[U04] Py：变量调试打印
来源：http://dali.daxiang520.top/Article/details/gt2qtjxbrpw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.yj20258.top/Article/details/gt2csfgomun.html

[U05] Py：列表去重且保序
来源：http://dali.ehwqpu.com/Article/details/gt2degqgqlb.html

list(dict.fromkeys(arr))
来源：http://dali.pengpengdd.cyou/Article/details/gt2wscepfpy.html

[U06] Py：合并两个字典
来源：http://dali.nanxinkj.top/Article/details/gt2ympnoqls.html

{**a, **b}
来源：http://dali.vqdsnc.cn/Article/details/gt2puhwvjvf.html

[U07] Py：反转字典键值
来源：http://dali.quarkkingdee.top/Article/details/gt2qbekypoa.html

{v: k for k, v in d.items()}
来源：http://dali.zycfv.cn/Article/details/gt2dvzyljcg.html

[U08] Py：展平二维列表
来源：http://dali.xziqi.cn/Article/details/gt2sdpcvgmy.html

[y for x in nested for y in x]
来源：http://dali.hongshengwenyu.top/Article/details/gt2hlozwrsh.html


<!-- 参考信息 -->