代发 wailian999

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sweek.top/Article/details/gt2aafzmryo.html

[R66] 定时任务
来源：http://dali.jianghu66.top/Article/details/gt2xikecjvs.html

crontab -e;  crontab -l
来源：http://dali.pycfn.com/Article/details/gt2mseltsvu.html

[R67] 生成随机十六进制串
来源：http://dali.c1oappe.top/Article/details/gt2dmhxdowf.html

openssl rand -hex 16
来源：http://dali.mhx1999.top/Article/details/gt2mycymkgw.html

[R68] 计算文件校验值
来源：http://dali.jinqigufen.top/Article/details/gt2gttgkfxb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhoulong.xyz/Article/details/gt2bmaixjur.html

[R69] 生成随机密码
来源：http://dali.hysaishi.cn/Article/details/gt2obpllkcz.html

head -c 16 /dev/urandom | base64
来源：http://dali.yonumen.top/Article/details/gt2gfbhgnxu.html

[R70] 时间戳与互转
来源：http://dali.sweek.top/Article/details/gt2jwjyszkg.html

date +%s;  date -d @1700000000
来源：http://dali.havefunace.top/Article/details/gt2mwsvbopt.html

[R71] 日期格式化
来源：http://dali.jyoumei.cn/Article/details/gt2bvokqtll.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xuanzx.com/Article/details/gt2yydjfmrd.html

[R72] 等待端口就绪
来源：http://dali.ehwqpu.com/Article/details/gt2mcuzayox.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uwasfyqq.html

[R73] 分割大日志
来源：http://dali.hywenlv.cn/Article/details/gt2rrxwoeoo.html

split -l 1000 big.log part_
来源：http://dali.yuxming.cn/Article/details/gt2enwrxqar.html

[R74] 批量重命名
来源：http://dali.9152youxi.cn/Article/details/gt2phqqckup.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.bjfxy.top/Article/details/gt2nrdzneue.html

[R75] 导出环境变量
来源：http://dali.sxryk.cn/Article/details/gt2qasyjrje.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhixingplan.top/Article/details/gt2vxriurys.html

[R76] 使用临时文件
来源：http://dali.xylfe.cn/Article/details/gt2ajyombpp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.redwolf501.top/Article/details/gt2vncurukp.html

[R77] 读取用户输入
来源：http://dali.hnqzz.top/Article/details/gt2lfbdeyph.html

read -rp "请输入: " ans
来源：http://dali.meibo888.top/Article/details/gt2crwgeyav.html

[R78] 交互式菜单
来源：http://dali.cucudq.cn/Article/details/gt2iwfuiozz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.0kj1m.cn/Article/details/gt2oqlbxdam.html

[R79] 解析命令行选项
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eydkxulm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinqigufen.top/Article/details/gt2qefmmcwc.html

[R80] 查看脚本执行耗时
来源：http://dali.wangshuangyany.cn/Article/details/gt2vrevawut.html

time ./run.sh
来源：http://dali.yueranfly.top/Article/details/gt2ixiuvhxz.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gt2duonnycq.html

S. C / C++ 专题
来源：http://dali.wangdashe.top/Article/details/gt2hzmvofuo.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2aarhrghw.html

[S01] C：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gt2djuarrvo.html

#include <stdio.h>
来源：http://dali.gotoacloud.top/Article/details/gt2knwubjho.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jianghu66.top/Article/details/gt2snctcpbc.html

[S02] C：变量与格式化输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2htlefkuy.html

int a = 10; printf("%d\n", a);
来源：http://dali.gaohongyu789.top/Article/details/gt2zarkssww.html

[S03] C：读入整数
来源：http://dali.chenlongwang.top/Article/details/gt2mdzwtiyf.html

int x; scanf("%d", &x);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ubojzvqn.html

[S04] C：字符串复制
来源：http://dali.9152youxi.cn/Article/details/gt2xajqjsep.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.xuanzx.com/Article/details/gt2epzcowhs.html

[S05] C：字符串长度
来源：http://dali.jqgufenzy.top/Article/details/gt2xhtrglnu.html

strlen(s)
来源：http://dali.sweek.top/Article/details/gt2qvlschjp.html

[S06] C：字符串比较
来源：http://dali.hywenlv.cn/Article/details/gt2yqxbvtwd.html

strcmp(a, b) == 0
来源：http://dali.zycfv.cn/Article/details/gt2pnpfmfuv.html

[S07] C：数组遍历求和
来源：http://dali.ybcxt.top/Article/details/gt2plrydhyr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wnylracd.html

[S08] C：动态内存分配与释放
来源：http://dali.pengpengdd.cyou/Article/details/gt2shxzruxn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.shangyingyoupin.top/Article/details/gt2ljgtwnqk.html

[S09] C：结构体定义与初始化
来源：http://dali.c1oappe.top/Article/details/gt2qhvjnfdj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sufxvd.cn/Article/details/gt2lojmcdnw.html

[S10] C：指针与解引用
来源：http://dali.meibo888.top/Article/details/gt2rctzaaik.html

int *p = &a;  *p = 5;
来源：http://dali.yueranfly.top/Article/details/gt2gmqsghkk.html

[S11] C：逐行读文件
来源：http://dali.ivvv.top/Article/details/gt2pnezgrkk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ivvv.top/Article/details/gt2eusetkrm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.fzhhl.top/Article/details/gt2vpklzjsh.html

fclose(f);
来源：http://dali.jqgufenzy.top/Article/details/gt2udiahhhw.html

[S12] C：写文件
来源：http://dali.cqqwz.cn/Article/details/gt2qrjphjzt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hnqzz.top/Article/details/gt2bobtvzzp.html

[S13] C：宏定义
来源：http://dali.c1oappe.top/Article/details/gt2fnybkcxh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.316326.xyz/Article/details/gt2npweekmh.html

[S14] C：枚举
来源：http://dali.kuanghao11.cn/Article/details/gt2myzultko.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xuetiantiany.cn/Article/details/gt2momsrgqq.html

[S15] C：类型转换
来源：http://dali.aizwys.cn/Article/details/gt2ykiqwrzi.html

(double) a / b
来源：http://dali.hnqzz.top/Article/details/gt2cojqpvwk.html

[S16] C：位操作置位
来源：http://dali.jianghu66.top/Article/details/gt2lekoxulh.html

x |= (1 << 3);
来源：http://dali.jianghu66.top/Article/details/gt2mrfinjug.html

[S17] C：安全拼接字符串
来源：http://dali.mhx1999.top/Article/details/gt2owanyhgl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinqigfzy.top/Article/details/gt2wnetmprw.html

[S18] C：命令行参数
来源：http://dali.hammf.cn/Article/details/gt2ixlytjca.html

int main(int argc, char **argv)
来源：http://dali.c1oappe.top/Article/details/gt2jzwrcaru.html

[S19] C：快速排序
来源：http://dali.nanxuanxn.top/Article/details/gt2olnjztnt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.mhx1999.top/Article/details/gt2yhahucbj.html

[S20] C：二分查找
来源：http://dali.quarkkingdee.top/Article/details/gt2syrluevg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sufxvd.cn/Article/details/gt2huvpsowe.html

[S21] C：字符类别判断
来源：http://dali.haohaochexian.top/Article/details/gt2puudivkx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pztyjtny.html

[S22] C：字符串转数字
来源：http://dali.jianghu66.top/Article/details/gt2rmbeviyd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wdhgjwyk.html

[S23] C：随机数
来源：http://dali.yj20258888.top/Article/details/gt2kvcxcsvp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gotoacloud.top/Article/details/gt2qfunjadg.html

[S24] C：获取本地时间
来源：http://dali.andypj.xyz/Article/details/gt2jteuzukb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.0kj1m.cn/Article/details/gt2cvvbaxbv.html

[S25] C：内存拷贝
来源：http://dali.hywenlv.cn/Article/details/gt2snlwhali.html

memcpy(dst, src, n);
来源：http://dali.shuidangran.top/Article/details/gt2fkzfuvrm.html

[S26] C：内存清零
来源：http://dali.ppjwa.cn/Article/details/gt2piptrpzh.html

memset(a, 0, sizeof a);
来源：http://dali.haohaochexian.top/Article/details/gt2pmshcoyl.html

[S27] C：定义常量
来源：http://dali.snrcjt.cn/Article/details/gt2xnoxeiuj.html

const double PI = 3.14159;
来源：http://dali.sufxvd.cn/Article/details/gt2vivrwvdz.html

[S28] C：静态变量
来源：http://dali.andypj.xyz/Article/details/gt2diggyyxm.html

static int counter = 0;
来源：http://dali.xuetiantiany.cn/Article/details/gt2zgdkqmjy.html

[S29] C：变参函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2ldfoasjq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sxryk.cn/Article/details/gt2bhcmnyte.html

[S30] C：头文件保护
来源：http://dali.nwbrower.top/Article/details/gt2zqomcwro.html

#ifndef X_H
来源：http://dali.jianghu66.top/Article/details/gt2xtuoosol.html

#define X_H
来源：http://dali.tanke756.top/Article/details/gt2uwkivyeh.html

#endif
来源：http://dali.yanxiufei.cn/Article/details/gt2qubhlauy.html

[S31] C++：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gt2sfmazuwq.html

#include <iostream>
来源：http://dali.pengpengdd.cyou/Article/details/gt2xxrajvdj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.aibaodan.cn/Article/details/gt2zsbjvvgw.html

[S32] C++：字符串
来源：http://dali.quarkkingdee.top/Article/details/gt2heubohlh.html

std::string s = "hi";  s += "!";
来源：http://dali.yj20258888.top/Article/details/gt2aczatvsn.html

[S33] C++：vector 增删
来源：http://dali.jinqigufen.top/Article/details/gt2myoskfgu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vgijyakx.html

[S34] C++：遍历 vector
来源：http://dali.yj20258888.top/Article/details/gt2flxrrqmt.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.snrcjt.cn/Article/details/gt2dgngamdk.html

[S35] C++：map
来源：http://dali.xylfe.cn/Article/details/gt2wnpffkyq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gt2cobaefxn.html

[S36] C++：unordered_map
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2afkirbyk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.havefunace.top/Article/details/gt2vnvoigxi.html

[S37] C++：set
来源：http://dali.smart0.xyz/Article/details/gt2xerzkkvw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhengqikj.top/Article/details/gt2nrlwsmhe.html

[S38] C++：排序
来源：http://dali.cheryme.top/Article/details/gt2lgejfpze.html

std::sort(v.begin(), v.end());
来源：http://dali.daria6918.cn/Article/details/gt2kvswjbnn.html

[S39] C++：自定义比较器排序
来源：http://dali.zhiwuduotai.top/Article/details/gt2jxpugkyh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.smart0.xyz/Article/details/gt2pghdvfbh.html

[S40] C++：查找元素
来源：http://dali.gzhubu.top/Article/details/gt2vhnogvmx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.pycfn.com/Article/details/gt2kbgnhjdg.html

[S41] C++：类与构造函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yuubiwsd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.tian-w.cn/Article/details/gt2fsaojuwo.html

[S42] C++：继承与虚函数
来源：http://dali.yj20258888.top/Article/details/gt2okmlpgfj.html

class B : public Base { public: void f() override {} };
来源：http://dali.ydzc1.top/Article/details/gt2wkabyjdu.html

[S43] C++：智能指针
来源：http://dali.jyoumei.cn/Article/details/gt2ebequwef.html

auto p = std::make_unique<int>(5);
来源：http://dali.chenjidiqi.icu/Article/details/gt2mskooacx.html

[S44] C++：引用传参
来源：http://dali.xziqi.cn/Article/details/gt2zamzbtck.html

void inc(int &x) { ++x; }
来源：http://dali.daria6918.cn/Article/details/gt2schlzmil.html

[S45] C++：lambda
来源：http://dali.jinqigfzy.top/Article/details/gt2ecshcxaa.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sysykeji.top/Article/details/gt2tgllixie.html

[S46] C++：函数模板
来源：http://dali.yvedp.cn/Article/details/gt2wbgxpudm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhoulong.xyz/Article/details/gt2ofpktwco.html

[S47] C++：结构化绑定遍历
来源：http://dali.kuanghao11.cn/Article/details/gt2dhufjugw.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yanxiufei.cn/Article/details/gt2jblqligv.html

[S48] C++：逐行读文件
来源：http://dali.hammf.cn/Article/details/gt2godfnyty.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.quarkkingdee.top/Article/details/gt2lrtbbuni.html

while (std::getline(in, line)) { }
来源：http://dali.guowangkeji.top/Article/details/gt2ippharss.html

[S49] C++：写文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2qiflotfo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yj20258.top/Article/details/gt2btpofjjs.html

[S50] C++：格式化数字
来源：http://dali.havefunace.top/Article/details/gt2qnygxdpx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sxryk.cn/Article/details/gt2yrfhxgha.html

[S51] C++：显式类型转换
来源：http://dali.jqgfzy.top/Article/details/gt2fhkewmee.html

static_cast<double>(a) / b
来源：http://dali.zdqjudy.top/Article/details/gt2ostvlxra.html

[S52] C++：const 与 noexcept
来源：http://dali.yuxming.cn/Article/details/gt2mkfnzxod.html

int size() const noexcept { return n_; }
来源：http://dali.yvedp.cn/Article/details/gt2fzlwuypb.html

[S53] C++：移动语义
来源：http://dali.hysaishi.cn/Article/details/gt2qdisxmbp.html

std::vector<int> w = std::move(v);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pyvirtvm.html

[S54] C++：异常处理
来源：http://dali.birdmap.top/Article/details/gt2sibhzlto.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenlongwang.top/Article/details/gt2ewpiniit.html

[S55] C++：结构化绑定
来源：http://dali.havefunace.top/Article/details/gt2kzwsovyw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jqgufenzy.top/Article/details/gt2ouxeruec.html

[S56] C++：optional
来源：http://dali.ivvv.top/Article/details/gt2pgrhgwrr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ydzc1.top/Article/details/gt2wfdakeaa.html

[S57] C++：编译期常量
来源：http://dali.chenlongwang.top/Article/details/gt2ksoyomvo.html

constexpr int N = 10;
来源：http://dali.hnqzz.top/Article/details/gt2qeyjgpjv.html

[S58] C++：命名空间
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2wleyxiqi.html

namespace ns { int f() { return 1; } }
来源：http://dali.nanxuanxn.top/Article/details/gt2ddqhohzr.html

[S59] C++：静态断言
来源：http://dali.yuxming.cn/Article/details/gt2mtgafkxn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hywenlv.cn/Article/details/gt2vtigvoyr.html

[S60] C++：遍历并删除元素
来源：http://dali.hfpthk.cn/Article/details/gt2kouygxkb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.nanxuanxn.top/Article/details/gt2zzhmaszq.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2cgzdszpx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.iojbl.cn/Article/details/gt2xognkjhx.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gt2rrgvdvuy.html

[T01] Kotlin：Hello World
来源：http://dali.hnqzz.top/Article/details/gt2lqtlumck.html

println("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2qfxsexgo.html

[T02] Kotlin：变量
来源：http://dali.fengsongda.top/Article/details/gt2mjugxvgb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.meibo888.top/Article/details/gt2cykeerdj.html

[T03] Kotlin：字符串模板
来源：http://dali.sweek.top/Article/details/gt2ftstqebq.html

"值: $b"
来源：http://dali.yonumen.top/Article/details/gt2haibxbqr.html

[T04] Kotlin：空安全
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zhuujgpv.html

val n: String? = null;  n?.length
来源：http://dali.gogol.net.cn/Article/details/gt2qbgxzudi.html

[T05] Kotlin：when 表达式
来源：http://dali.xuetiantiany.cn/Article/details/gt2qlqdzyuv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.kuanghao11.cn/Article/details/gt2zofpbgaw.html

[T06] Kotlin：集合映射
来源：http://dali.sufxvd.cn/Article/details/gt2vcblzcco.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gt2zvnfkzau.html

[T07] Kotlin：集合过滤
来源：http://dali.316326.xyz/Article/details/gt2dtkjmrug.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.daxiang520.top/Article/details/gt2fhchfhwk.html

[T08] Kotlin：数据类
来源：http://dali.chenjidiqi.icu/Article/details/gt2czagwueu.html

data class User(val name: String, val age: Int)
来源：http://dali.0kj1m.cn/Article/details/gt2aibbezoy.html

[T09] Kotlin：扩展函数
来源：http://dali.andypj.xyz/Article/details/gt2dftisthg.html

fun String.exclaim() = this + "!"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ymhccrzf.html

[T10] Kotlin：默认参数
来源：http://dali.ybcxt.top/Article/details/gt2prpuhpxu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yueranfly.top/Article/details/gt2bfrehayq.html

[T11] Kotlin：协程
来源：http://dali.ybcxt.top/Article/details/gt2ttusvfgr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.quarkkingdee.top/Article/details/gt2pzbrnids.html

[T12] Kotlin：解构声明
来源：http://dali.xuetiantiany.cn/Article/details/gt2hlhwhjok.html

val (a, b) = Pair(1, 2)
来源：http://dali.shuidangran.top/Article/details/gt2mxlzyypu.html

[T13] Kotlin：只读 Map
来源：http://dali.zhoulong.xyz/Article/details/gt2bddmpzjc.html

val m = mapOf("a" to 1)
来源：http://dali.gaohongyu789.top/Article/details/gt2btqqyyqo.html

[T14] Kotlin：循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2iyzgtsfr.html

for (i in 1..10) println(i)
来源：http://dali.zycfv.cn/Article/details/gt2rkqzlmbs.html

[T15] Kotlin：接口
来源：http://dali.chenjidiqi.icu/Article/details/gt2arulolqs.html

interface Shape { fun area(): Double }
来源：http://dali.hfpthk.cn/Article/details/gt2qejwaonr.html

[T16] Swift：Hello World
来源：http://dali.jqgfzy.top/Article/details/gt2jqtzyont.html

print("Hello")
来源：http://dali.guowangkeji.top/Article/details/gt2rhjyygeb.html

[T17] Swift：变量与常量
来源：http://dali.gotoacloud.top/Article/details/gt2uashilix.html

var a = 1;  let b = 2
来源：http://dali.bjfxy.top/Article/details/gt2amwekzor.html

[T18] Swift：字符串插值
来源：http://dali.yvedp.cn/Article/details/gt2nwagwqqd.html

"值: \(b)"
来源：http://dali.wangshuangyany.cn/Article/details/gt2rjfezfsn.html

[T19] Swift：可选绑定
来源：http://dali.yj20258888.top/Article/details/gt2wsnagbus.html

if let n = opt { print(n) }
来源：http://dali.nwbrower.top/Article/details/gt2vohgfwjn.html

[T20] Swift：数组操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gdmxxfwo.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.snrcjt.cn/Article/details/gt2pzxwyvvw.html

[T21] Swift：遍历
来源：http://dali.jlsjyb.cn/Article/details/gt2yhfxpagj.html

for x in a { print(x) }
来源：http://dali.316326.xyz/Article/details/gt2eaaadfpj.html

[T22] Swift：字典
来源：http://dali.nanxuanxn.top/Article/details/gt2velwqleu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.hammf.cn/Article/details/gt2ncbsgjle.html

[T23] Swift：函数
来源：http://dali.vqdsnc.cn/Article/details/gt2vlzifcez.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.andypj.xyz/Article/details/gt2nycblhnx.html

[T24] Swift：闭包
来源：http://dali.gogol.net.cn/Article/details/gt2izsvbhzf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2uqqsvvkp.html

[T25] Swift：结构体
来源：http://dali.sxryk.cn/Article/details/gt2xcrxzvnj.html

struct P { var x: Int }
来源：http://dali.ivvv.top/Article/details/gt2zhpfytmk.html

[T26] Swift：类与重写
来源：http://dali.gogol.net.cn/Article/details/gt2nupjgdiz.html

class A: Base { override func f() {} }
来源：http://dali.jlsjyb.cn/Article/details/gt2ittsybrh.html

[T27] Swift：错误处理
来源：http://dali.yangfankeji.com/Article/details/gt2odyqogwa.html

do { try f() } catch { print(error) }
来源：http://dali.cdnleiting.top/Article/details/gt2lirmdkzp.html

[T28] Swift：枚举
来源：http://dali.shzxlz.cn/Article/details/gt2ijipqbjy.html

enum Color { case red, green }
来源：http://dali.tanke756.top/Article/details/gt2zjaolcmm.html

[T29] Swift：guard 提前返回
来源：http://dali.316326.xyz/Article/details/gt2wpegjvgy.html

guard let x = opt else { return }
来源：http://dali.birdmap.top/Article/details/gt2lqpgngrn.html

[T30] Swift：协议
来源：http://dali.zhoulong.xyz/Article/details/gt2ignxdtot.html

protocol Shape { func area() -> Double }
来源：http://dali.gzhubu.top/Article/details/gt2gzxwxgkh.html

[T31] Lua：Hello World
来源：http://dali.hysaishi.cn/Article/details/gt2rsvxnywx.html

print("Hello")
来源：http://dali.mhx1999.top/Article/details/gt2ocizyzzy.html

[T32] Lua：局部变量
来源：http://dali.chenjidiqi.icu/Article/details/gt2zbmujqde.html

local a = 1
来源：http://dali.sysykeji.top/Article/details/gt2kntqsutp.html

[T33] Lua：表（数组）
来源：http://dali.cdnleiting.top/Article/details/gt2nqehdmwd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bkvjuknw.html

[T34] Lua：遍历表
来源：http://dali.smart0.xyz/Article/details/gt2dunxbbws.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rbegsubw.html

[T35] Lua：字典表
来源：http://dali.316326.xyz/Article/details/gt2oviljesq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nrydfwyt.html

[T36] Lua：函数
来源：http://dali.yangfankeji.com/Article/details/gt2dwyzrner.html

function add(a, b) return a + b end
来源：http://dali.jiagoushi.top/Article/details/gt2lhtblhix.html

[T37] Lua：字符串拼接
来源：http://dali.birdmap.top/Article/details/gt2scbouhcu.html

"a" .. "b"
来源：http://dali.iojbl.cn/Article/details/gt2diweweua.html

[T38] Lua：条件
来源：http://dali.guowangkeji.top/Article/details/gt2zxsukhdh.html

if x > 0 then print("正") end
来源：http://dali.yj20258888.top/Article/details/gt2xmkfvsnh.html

[T39] Lua：模式匹配
来源：http://dali.jqgufenzy.top/Article/details/gt2xxhznfeg.html

string.find(s, "%d+")
来源：http://dali.haohaochexian.top/Article/details/gt2bsgcoayc.html

[T40] Lua：元表
来源：http://dali.wangdashe.top/Article/details/gt2kpunjnru.html

setmetatable({}, { __index = base })
来源：http://dali.hywenlv.cn/Article/details/gt2ykyfimvz.html

[T41] Perl：Hello World
来源：http://dali.tanke756.top/Article/details/gt2ojbeqqgh.html

print "Hello\n";
来源：http://dali.guowangkeji.top/Article/details/gt2rtfoaldg.html

[T42] Perl：变量类型
来源：http://dali.sxryk.cn/Article/details/gt2xremjbqz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.svipenyu.cn/Article/details/gt2eyggjqea.html

[T43] Perl：字符串插值
来源：http://dali.jinqigufen.top/Article/details/gt2aymalelp.html

"值: $a"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2hbilezcr.html

[T44] Perl：条件
来源：http://dali.hammf.cn/Article/details/gt2yzkpzirh.html

if ($a > 0) { print "正"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eszebhlf.html

[T45] Perl：数组遍历
来源：http://dali.hammf.cn/Article/details/gt2nmateoal.html

for my $x (@arr) { print $x; }
来源：http://dali.shzxlz.cn/Article/details/gt2shgjqedz.html

[T46] Perl：哈希操作
来源：http://dali.tianlin.xyz/Article/details/gt2byufstcp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.0kj1m.cn/Article/details/gt2aunsfqzf.html

[T47] Perl：正则捕获
来源：http://dali.quarkkingdee.top/Article/details/gt2cknldrli.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.shzxlz.cn/Article/details/gt2jtwkbpwn.html

[T48] Perl：正则替换
来源：http://dali.guowangkeji.top/Article/details/gt2jnubypyy.html

$s =~ s/old/new/g;
来源：http://dali.dianchejie.cn/Article/details/gt2hzxjyqou.html

[T49] Perl：函数
来源：http://dali.meibo888.top/Article/details/gt2bjbdacbw.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.havefunace.top/Article/details/gt2ffweyetu.html

[T50] Perl：逐行读文件
来源：http://dali.wangdashe.top/Article/details/gt2qmgimlsq.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xylfe.cn/Article/details/gt2vrcladfu.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.birdmap.top/Article/details/gt2wolchuli.html

[T51] Scala：Hello World
来源：http://dali.hysaishi.cn/Article/details/gt2lpfoindg.html

println("Hello")
来源：http://dali.wangdashe.top/Article/details/gt2ueycrwep.html

[T52] Scala：变量
来源：http://dali.sysykeji.top/Article/details/gt2iutaaciv.html

val a = 1;  var b = 2
来源：http://dali.gogol.net.cn/Article/details/gt2wepshvti.html

[T53] Scala：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gt2whmvynim.html

s"值: $b"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2quzodftp.html

[T54] Scala：集合映射
来源：http://dali.pengpengdd.cyou/Article/details/gt2xrkwwslq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cheryme.top/Article/details/gt2sgaifiij.html

[T55] Scala：集合过滤
来源：http://dali.nanxuanxn.top/Article/details/gt2wkuzdswx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhongyouzk.top/Article/details/gt2popvpkly.html

[T56] Scala：样例类
来源：http://dali.tanke756.top/Article/details/gt2codilhnn.html

case class User(name: String, age: Int)
来源：http://dali.sufxvd.cn/Article/details/gt2nunoaafe.html

[T57] Scala：模式匹配
来源：http://dali.cashguo.top/Article/details/gt2yxdkcbwy.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.cdnleiting.top/Article/details/gt2hodtpbvj.html

[T58] Scala：函数定义
来源：http://dali.hnxiangtu.top/Article/details/gt2pbeqbrzc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.haohaochexian.top/Article/details/gt2knrdzjsn.html

[T59] Scala：循环
来源：http://dali.cheryme.top/Article/details/gt2yqtxtswg.html

for (i <- 1 to 10) println(i)
来源：http://dali.nanxuanxn.top/Article/details/gt2qgaqcipn.html

[T60] Scala：折叠
来源：http://dali.wangdashe.top/Article/details/gt2kolfedrt.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.feifeiyinyue.top/Article/details/gt2cthqqjtm.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gt2cvtpxhlh.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.wangdashe.top/Article/details/gt2jlhsfvgp.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2meswxqqy.html

[U01] Py：创建虚拟环境
来源：http://dali.c1oappe.top/Article/details/gt2xoupazuz.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.andypj.xyz/Article/details/gt2ncbmrriu.html

[U02] Py：导出 / 安装依赖
来源：http://dali.gaohongyu789.top/Article/details/gt2ufvgvmqh.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hnqzz.top/Article/details/gt2isxboibf.html

[U03] Py：加载 .env 配置
来源：http://dali.yueranfly.top/Article/details/gt2tuiqlawu.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.haohaochexian.top/Article/details/gt2aglwpwha.html

[U04] Py：变量调试打印
来源：http://dali.jinqigufen.top/Article/details/gt2zdeahghf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.nanxuanxn.top/Article/details/gt2dcrjiqfa.html

[U05] Py：列表去重且保序
来源：http://dali.yanxiufei.cn/Article/details/gt2myltpwdj.html

list(dict.fromkeys(arr))
来源：http://dali.zhoulong.xyz/Article/details/gt2ftbwwzve.html

[U06] Py：合并两个字典
来源：http://dali.fzhhl.top/Article/details/gt2kpbqfjbd.html

{**a, **b}
来源：http://dali.sysykeji.top/Article/details/gt2atdctioc.html


<!-- 参考信息 -->