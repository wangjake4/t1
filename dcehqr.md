代发 wailian999

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xziqi.cn/Article/details/gt2phrysaax.html

[R66] 定时任务
来源：http://dali.nanxuanxn.top/Article/details/gt2vnqsbqho.html

crontab -e;  crontab -l
来源：http://dali.316326.xyz/Article/details/gt2zkizetli.html

[R67] 生成随机十六进制串
来源：http://dali.jinqigufen.top/Article/details/gt2hhlvlxap.html

openssl rand -hex 16
来源：http://dali.ydzc1.top/Article/details/gt2yznkqoqs.html

[R68] 计算文件校验值
来源：http://dali.havefunace.top/Article/details/gt2tvgssvit.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.birdmap.top/Article/details/gt2vpdsgbna.html

[R69] 生成随机密码
来源：http://dali.xinyue.icu/Article/details/gt2niibsike.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhoulong.xyz/Article/details/gt2ddtgofww.html

[R70] 时间戳与互转
来源：http://dali.jqgufenzy.top/Article/details/gt2mjsgtzxq.html

date +%s;  date -d @1700000000
来源：http://dali.yuxming.cn/Article/details/gt2lmsekruk.html

[R71] 日期格式化
来源：http://dali.fengsongda.top/Article/details/gt2jmbdgyxq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gogol.net.cn/Article/details/gt2vawsalwt.html

[R72] 等待端口就绪
来源：http://dali.ybcxt.top/Article/details/gt2jjehvhfy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hammf.cn/Article/details/gt2yvxcedoy.html

[R73] 分割大日志
来源：http://dali.tianlin.xyz/Article/details/gt2wtglrhrk.html

split -l 1000 big.log part_
来源：http://dali.yj20258.top/Article/details/gt2fbqokguy.html

[R74] 批量重命名
来源：http://dali.zycfv.cn/Article/details/gt2kvaecvao.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sxryk.cn/Article/details/gt2xcumorkr.html

[R75] 导出环境变量
来源：http://dali.xuetiantiany.cn/Article/details/gt2vbcynllr.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gaohongyu789.top/Article/details/gt2mytquwyn.html

[R76] 使用临时文件
来源：http://dali.guannengcc.top/Article/details/gt2jxkywakh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xuanzx.com/Article/details/gt2crvbgytr.html

[R77] 读取用户输入
来源：http://dali.ppjwa.cn/Article/details/gt2kpxhasfk.html

read -rp "请输入: " ans
来源：http://dali.bjfxy.top/Article/details/gt2chjrafhs.html

[R78] 交互式菜单
来源：http://dali.zhengqikj.top/Article/details/gt2qnyujlog.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ppjwa.cn/Article/details/gt2bletrson.html

[R79] 解析命令行选项
来源：http://dali.jiagoushi.top/Article/details/gt2rwkaurzl.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xziqi.cn/Article/details/gt2bnjciimt.html

[R80] 查看脚本执行耗时
来源：http://dali.gzhubu.top/Article/details/gt2sjzdjpan.html

time ./run.sh
来源：http://dali.gzhubu.top/Article/details/gt2yxtmfbzz.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gt2oagdbxus.html

S. C / C++ 专题
来源：http://dali.aizwys.cn/Article/details/gt2yeaifffe.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zaesuqge.html

[S01] C：Hello World
来源：http://dali.daxiang520.top/Article/details/gt2uawtdmxr.html

#include <stdio.h>
来源：http://dali.smart0.xyz/Article/details/gt2vehdcznz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jianghu66.top/Article/details/gt2kmmswomn.html

[S02] C：变量与格式化输出
来源：http://dali.yonumen.top/Article/details/gt2shofllzt.html

int a = 10; printf("%d\n", a);
来源：http://dali.yangfankeji.com/Article/details/gt2zrgukovs.html

[S03] C：读入整数
来源：http://dali.ehwqpu.com/Article/details/gt2jvoxahao.html

int x; scanf("%d", &x);
来源：http://dali.yj20258.top/Article/details/gt2oynnxixu.html

[S04] C：字符串复制
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qiyutgyh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.c1oappe.top/Article/details/gt2zmnqfper.html

[S05] C：字符串长度
来源：http://dali.hywenlv.cn/Article/details/gt2fabqjpps.html

strlen(s)
来源：http://dali.cqqwz.cn/Article/details/gt2nzpdbkqt.html

[S06] C：字符串比较
来源：http://dali.fzhhl.top/Article/details/gt2oeguepcp.html

strcmp(a, b) == 0
来源：http://dali.zhiwuduotai.top/Article/details/gt2dwfddkmj.html

[S07] C：数组遍历求和
来源：http://dali.hammf.cn/Article/details/gt2xhqwkjza.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wphgjmwj.html

[S08] C：动态内存分配与释放
来源：http://dali.jlsjyb.cn/Article/details/gt2bgsidpke.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.tian-w.cn/Article/details/gt2trcgfxwa.html

[S09] C：结构体定义与初始化
来源：http://dali.snrcjt.cn/Article/details/gt2xgewsobg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yvedp.cn/Article/details/gt2srshsynm.html

[S10] C：指针与解引用
来源：http://dali.nwbrower.top/Article/details/gt2netmpoxc.html

int *p = &a;  *p = 5;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xqphdlzb.html

[S11] C：逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gt2vzfybnda.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.tian-w.cn/Article/details/gt2bzfazqrk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yueranfly.top/Article/details/gt2zhsxxtza.html

fclose(f);
来源：http://dali.yvedp.cn/Article/details/gt2rjzbyzhu.html

[S12] C：写文件
来源：http://dali.cheryme.top/Article/details/gt2ztrflwrt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.andypj.xyz/Article/details/gt2hpjzgobo.html

[S13] C：宏定义
来源：http://dali.feifeiyinyue.top/Article/details/gt2xektebfg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cucudq.cn/Article/details/gt2xrrdhbsr.html

[S14] C：枚举
来源：http://dali.xuanzx.com/Article/details/gt2clshosky.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.chenlongwang.top/Article/details/gt2wksmrwnv.html

[S15] C：类型转换
来源：http://dali.bjfxy.top/Article/details/gt2oxdneacf.html

(double) a / b
来源：http://dali.shuidangran.top/Article/details/gt2oqgbqhqt.html

[S16] C：位操作置位
来源：http://dali.chenjidiqi.icu/Article/details/gt2xnneqcxm.html

x |= (1 << 3);
来源：http://dali.iojbl.cn/Article/details/gt2cgirqynt.html

[S17] C：安全拼接字符串
来源：http://dali.hysaishi.cn/Article/details/gt2rwvrusum.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.svipenyu.cn/Article/details/gt2jootxifb.html

[S18] C：命令行参数
来源：http://dali.xuetiantiany.cn/Article/details/gt2lqhoifes.html

int main(int argc, char **argv)
来源：http://dali.tanke756.top/Article/details/gt2haurlwju.html

[S19] C：快速排序
来源：http://dali.jlsjyb.cn/Article/details/gt2byjpwbgq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.quarkkingdee.top/Article/details/gt2ruqjvcgd.html

[S20] C：二分查找
来源：http://dali.gotoacloud.top/Article/details/gt2pdtobkuq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2urjhnzdd.html

[S21] C：字符类别判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mcqduqvo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jqgfzy.top/Article/details/gt2hhobmcmw.html

[S22] C：字符串转数字
来源：http://dali.hnxiangtu.top/Article/details/gt2gnspunsi.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xinyue.icu/Article/details/gt2aexrobck.html

[S23] C：随机数
来源：http://dali.zhixingplan.top/Article/details/gt2khrthhkm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.iojbl.cn/Article/details/gt2cvmbxowm.html

[S24] C：获取本地时间
来源：http://dali.shuidangran.top/Article/details/gt2xsshfltv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gaohongyu789.top/Article/details/gt2fxyxqnxz.html

[S25] C：内存拷贝
来源：http://dali.birdmap.top/Article/details/gt2leuetydx.html

memcpy(dst, src, n);
来源：http://dali.ydzc1.top/Article/details/gt2giqjomcs.html

[S26] C：内存清零
来源：http://dali.jinqigfzy.top/Article/details/gt2hknboqfb.html

memset(a, 0, sizeof a);
来源：http://dali.chenlongwang.top/Article/details/gt2ynktoyqy.html

[S27] C：定义常量
来源：http://dali.yuanzhike.top/Article/details/gt2ssfmbxkv.html

const double PI = 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gt2yrnfdisr.html

[S28] C：静态变量
来源：http://dali.sweek.top/Article/details/gt2ojybgxbv.html

static int counter = 0;
来源：http://dali.fengsongda.top/Article/details/gt2skfhntjb.html

[S29] C：变参函数
来源：http://dali.birdmap.top/Article/details/gt2tdzwxhvk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.svipenyu.cn/Article/details/gt2hlggzqma.html

[S30] C：头文件保护
来源：http://dali.yongpay.top/Article/details/gt2zmwqxwqx.html

#ifndef X_H
来源：http://dali.gogol.net.cn/Article/details/gt2ibmbyljw.html

#define X_H
来源：http://dali.zhoulong.xyz/Article/details/gt2aqsugeec.html

#endif
来源：http://dali.xuanzx.com/Article/details/gt2edioekwo.html

[S31] C++：Hello World
来源：http://dali.yj202588.top/Article/details/gt2vlsirwtu.html

#include <iostream>
来源：http://dali.zhoulong.xyz/Article/details/gt2vivbkbqa.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yuxming.cn/Article/details/gt2puhcmtuz.html

[S32] C++：字符串
来源：http://dali.wangshuangyany.cn/Article/details/gt2kvtndbpo.html

std::string s = "hi";  s += "!";
来源：http://dali.shuidangran.top/Article/details/gt2joizjegu.html

[S33] C++：vector 增删
来源：http://dali.feifeiyinyue.top/Article/details/gt2lycrnmuz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ydzc1.top/Article/details/gt2zcqoqjfu.html

[S34] C++：遍历 vector
来源：http://dali.zhixingplan.top/Article/details/gt2qmucebsh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.wangdashe.top/Article/details/gt2imruspxc.html

[S35] C++：map
来源：http://dali.fzhhl.top/Article/details/gt2fopvrehs.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gt2mdyypitu.html

[S36] C++：unordered_map
来源：http://dali.jianghu66.top/Article/details/gt2dnhqxwfi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gzhubu.top/Article/details/gt2sqvxgswd.html

[S37] C++：set
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bafszteh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sysykeji.top/Article/details/gt2wictilsy.html

[S38] C++：排序
来源：http://dali.hongshengwenyu.top/Article/details/gt2kxomrksm.html

std::sort(v.begin(), v.end());
来源：http://dali.ehwqpu.com/Article/details/gt2oxihwhcz.html

[S39] C++：自定义比较器排序
来源：http://dali.hnxiangtu.top/Article/details/gt2itihpxej.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hnqzz.top/Article/details/gt2jomdqvks.html

[S40] C++：查找元素
来源：http://dali.jianghu66.top/Article/details/gt2qfwnfzyn.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jiagoushi.top/Article/details/gt2sboxtdjo.html

[S41] C++：类与构造函数
来源：http://dali.c1oappe.top/Article/details/gt2sceobwqo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.9152youxi.cn/Article/details/gt2kicjmfdy.html

[S42] C++：继承与虚函数
来源：http://dali.xinyue.icu/Article/details/gt2eergiwgz.html

class B : public Base { public: void f() override {} };
来源：http://dali.bjfxy.top/Article/details/gt2qllkkiiv.html

[S43] C++：智能指针
来源：http://dali.fzhhl.top/Article/details/gt2gjkeoeen.html

auto p = std::make_unique<int>(5);
来源：http://dali.jqgufenzy.top/Article/details/gt2pwjzjngc.html

[S44] C++：引用传参
来源：http://dali.yueranfly.top/Article/details/gt2ciufskul.html

void inc(int &x) { ++x; }
来源：http://dali.tianlin.xyz/Article/details/gt2yaicqsjb.html

[S45] C++：lambda
来源：http://dali.sysykeji.top/Article/details/gt2gavkpstv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yongpay.top/Article/details/gt2ruxumbhy.html

[S46] C++：函数模板
来源：http://dali.sysykeji.top/Article/details/gt2dqiltjtk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhengqikj.top/Article/details/gt2fckcjhey.html

[S47] C++：结构化绑定遍历
来源：http://dali.xuanzx.com/Article/details/gt2vxsmznxj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sxryk.cn/Article/details/gt2bwdpnjqt.html

[S48] C++：逐行读文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mfzajcww.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sweek.top/Article/details/gt2ufprktkb.html

while (std::getline(in, line)) { }
来源：http://dali.jinqigfzy.top/Article/details/gt2gcwlphzd.html

[S49] C++：写文件
来源：http://dali.zycfv.cn/Article/details/gt2prmfhqys.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.aibaodan.cn/Article/details/gt2zaxdzgkm.html

[S50] C++：格式化数字
来源：http://dali.cqqwz.cn/Article/details/gt2lhztjorm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gjwpyjha.html

[S51] C++：显式类型转换
来源：http://dali.iojbl.cn/Article/details/gt2xfzcgqep.html

static_cast<double>(a) / b
来源：http://dali.hywenlv.cn/Article/details/gt2ppzjhumk.html

[S52] C++：const 与 noexcept
来源：http://dali.sysykeji.top/Article/details/gt2lveeuows.html

int size() const noexcept { return n_; }
来源：http://dali.yvedp.cn/Article/details/gt2tandjcxk.html

[S53] C++：移动语义
来源：http://dali.meibo888.top/Article/details/gt2yrcenznz.html

std::vector<int> w = std::move(v);
来源：http://dali.daxiang520.top/Article/details/gt2zmepmdto.html

[S54] C++：异常处理
来源：http://dali.yj20258.top/Article/details/gt2zvohhvnp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhoulong.xyz/Article/details/gt2lzqvjqqm.html

[S55] C++：结构化绑定
来源：http://dali.aibaodan.cn/Article/details/gt2bceqhwlm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.aibaodan.cn/Article/details/gt2kmnkpcfd.html

[S56] C++：optional
来源：http://dali.hammf.cn/Article/details/gt2bcfleirr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hammf.cn/Article/details/gt2wnftkjfu.html

[S57] C++：编译期常量
来源：http://dali.gzhubu.top/Article/details/gt2ocbjotvh.html

constexpr int N = 10;
来源：http://dali.fzhhl.top/Article/details/gt2dytyfvfp.html

[S58] C++：命名空间
来源：http://dali.pycfn.com/Article/details/gt2rjctvvbe.html

namespace ns { int f() { return 1; } }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vqhaaqrj.html

[S59] C++：静态断言
来源：http://dali.yuanzhike.top/Article/details/gt2ojioushe.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cqqwz.cn/Article/details/gt2gfwrdynb.html

[S60] C++：遍历并删除元素
来源：http://dali.yuxming.cn/Article/details/gt2ivvtmizv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.vqdsnc.cn/Article/details/gt2hhhbncge.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gt2nzhxtrwg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.havefunace.top/Article/details/gt2nznwkksl.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2xtdbfehf.html

[T01] Kotlin：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gt2zwpuiwpa.html

println("Hello")
来源：http://dali.havefunace.top/Article/details/gt2eoakzwqo.html

[T02] Kotlin：变量
来源：http://dali.iojbl.cn/Article/details/gt2bqbckjdb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.sysykeji.top/Article/details/gt2vqoschug.html

[T03] Kotlin：字符串模板
来源：http://dali.feifeiyinyue.top/Article/details/gt2nvkpglli.html

"值: $b"
来源：http://dali.quarkkingdee.top/Article/details/gt2uqqvnqqm.html

[T04] Kotlin：空安全
来源：http://dali.yanxiufei.cn/Article/details/gt2vzjlsgay.html

val n: String? = null;  n?.length
来源：http://dali.cdnleiting.top/Article/details/gt2pnnmtsab.html

[T05] Kotlin：when 表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gt2apxepvvf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jqgfzy.top/Article/details/gt2tgquyown.html

[T06] Kotlin：集合映射
来源：http://dali.nanxinkj.top/Article/details/gt2owqiptqd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.tianlin.xyz/Article/details/gt2iupkvrfu.html

[T07] Kotlin：集合过滤
来源：http://dali.nanxuanxn.top/Article/details/gt2fdzucaer.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cdnleiting.top/Article/details/gt2ysusmhju.html

[T08] Kotlin：数据类
来源：http://dali.hnqzz.top/Article/details/gt2nxwmmcvs.html

data class User(val name: String, val age: Int)
来源：http://dali.gaohongyu789.top/Article/details/gt2uldnpbpv.html

[T09] Kotlin：扩展函数
来源：http://dali.hfpthk.cn/Article/details/gt2eieamdgy.html

fun String.exclaim() = this + "!"
来源：http://dali.hammf.cn/Article/details/gt2oaqjnfgz.html

[T10] Kotlin：默认参数
来源：http://dali.shzxlz.cn/Article/details/gt2jfjrbhrj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hnxiangtu.top/Article/details/gt2fedkayll.html

[T11] Kotlin：协程
来源：http://dali.zycfv.cn/Article/details/gt2yfnptuhj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gotoacloud.top/Article/details/gt2frkkjwis.html

[T12] Kotlin：解构声明
来源：http://dali.daria6918.cn/Article/details/gt2vpycjhex.html

val (a, b) = Pair(1, 2)
来源：http://dali.tian-w.cn/Article/details/gt2reexgxjy.html

[T13] Kotlin：只读 Map
来源：http://dali.aibaodan.cn/Article/details/gt2vabzcxmv.html

val m = mapOf("a" to 1)
来源：http://dali.meibo888.top/Article/details/gt2vnukukgo.html

[T14] Kotlin：循环
来源：http://dali.shuidangran.top/Article/details/gt2hzxgddmh.html

for (i in 1..10) println(i)
来源：http://dali.yj20258888.top/Article/details/gt2ozgrifev.html

[T15] Kotlin：接口
来源：http://dali.snrcjt.cn/Article/details/gt2azjmabdp.html

interface Shape { fun area(): Double }
来源：http://dali.gotoacloud.top/Article/details/gt2zotsvviq.html

[T16] Swift：Hello World
来源：http://dali.sysykeji.top/Article/details/gt2ldmabdvf.html

print("Hello")
来源：http://dali.sufxvd.cn/Article/details/gt2nenqoyld.html

[T17] Swift：变量与常量
来源：http://dali.jqgufenzy.top/Article/details/gt2qckdxsnl.html

var a = 1;  let b = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2yrrmuylf.html

[T18] Swift：字符串插值
来源：http://dali.hammf.cn/Article/details/gt2yutstbum.html

"值: \(b)"
来源：http://dali.cdnleiting.top/Article/details/gt2ruwbsyhx.html

[T19] Swift：可选绑定
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ukqqauhd.html

if let n = opt { print(n) }
来源：http://dali.yvedp.cn/Article/details/gt2zqmexmma.html

[T20] Swift：数组操作
来源：http://dali.jlsjyb.cn/Article/details/gt2rjgnlfvv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ehwqpu.com/Article/details/gt2erpcbzrg.html

[T21] Swift：遍历
来源：http://dali.jiagoushi.top/Article/details/gt2fwikelxd.html

for x in a { print(x) }
来源：http://dali.tian-w.cn/Article/details/gt2tdioeegu.html

[T22] Swift：字典
来源：http://dali.svipenyu.cn/Article/details/gt2plsyegtx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jqgfzy.top/Article/details/gt2pmxpmppm.html

[T23] Swift：函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2huiyjhma.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.aibaodan.cn/Article/details/gt2ezdipvsb.html

[T24] Swift：闭包
来源：http://dali.zhixingplan.top/Article/details/gt2ddrufmzj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sweek.top/Article/details/gt2iqrovzax.html

[T25] Swift：结构体
来源：http://dali.gaohongyu789.top/Article/details/gt2yotaauvm.html

struct P { var x: Int }
来源：http://dali.wangshuangyany.cn/Article/details/gt2vqptpygv.html

[T26] Swift：类与重写
来源：http://dali.gzhubu.top/Article/details/gt2nmuuxzjx.html

class A: Base { override func f() {} }
来源：http://dali.gzhubu.top/Article/details/gt2frkqofrg.html

[T27] Swift：错误处理
来源：http://dali.daxiang520.top/Article/details/gt2uelshnkz.html

do { try f() } catch { print(error) }
来源：http://dali.cucudq.cn/Article/details/gt2wtonpvek.html

[T28] Swift：枚举
来源：http://dali.hammf.cn/Article/details/gt2etscnkxy.html

enum Color { case red, green }
来源：http://dali.yanxiufei.cn/Article/details/gt2fxtguifp.html

[T29] Swift：guard 提前返回
来源：http://dali.tianlin.xyz/Article/details/gt2ufkezigx.html

guard let x = opt else { return }
来源：http://dali.haohaochexian.top/Article/details/gt2hvvdyuuu.html

[T30] Swift：协议
来源：http://dali.c1oappe.top/Article/details/gt2vquqxrww.html

protocol Shape { func area() -> Double }
来源：http://dali.nanxuanxn.top/Article/details/gt2dycvqaoq.html

[T31] Lua：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gt2vduvhzlf.html

print("Hello")
来源：http://dali.zdqjudy.top/Article/details/gt2zhjgiitd.html

[T32] Lua：局部变量
来源：http://dali.pycfn.com/Article/details/gt2zbbsxctk.html

local a = 1
来源：http://dali.yanxiufei.cn/Article/details/gt2dqfydwwu.html

[T33] Lua：表（数组）
来源：http://dali.cqqwz.cn/Article/details/gt2hyhpccmn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ydzc1.top/Article/details/gt2paehftmx.html

[T34] Lua：遍历表
来源：http://dali.yonumen.top/Article/details/gt2qvczitqf.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.tianlin.xyz/Article/details/gt2ipplnlqu.html

[T35] Lua：字典表
来源：http://dali.yonumen.top/Article/details/gt2vqytytil.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cheryme.top/Article/details/gt2ltcqzysp.html

[T36] Lua：函数
来源：http://dali.jinqigufen.top/Article/details/gt2afscfrmm.html

function add(a, b) return a + b end
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uashmnvh.html

[T37] Lua：字符串拼接
来源：http://dali.xuanzx.com/Article/details/gt2xeunffst.html

"a" .. "b"
来源：http://dali.chenjidiqi.icu/Article/details/gt2kzusgvyx.html

[T38] Lua：条件
来源：http://dali.yj20258888.top/Article/details/gt2civluitb.html

if x > 0 then print("正") end
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nrlctyum.html

[T39] Lua：模式匹配
来源：http://dali.cheryme.top/Article/details/gt2mqmavkrt.html

string.find(s, "%d+")
来源：http://dali.cqqwz.cn/Article/details/gt2badqgvuv.html

[T40] Lua：元表
来源：http://dali.quarkkingdee.top/Article/details/gt2yyppuimp.html

setmetatable({}, { __index = base })
来源：http://dali.shangyingyoupin.top/Article/details/gt2vypmwxsu.html

[T41] Perl：Hello World
来源：http://dali.gotoacloud.top/Article/details/gt2dvjvrgkw.html

print "Hello\n";
来源：http://dali.nanxuanxn.top/Article/details/gt2rblmhkbf.html

[T42] Perl：变量类型
来源：http://dali.9152youxi.cn/Article/details/gt2ipwxndhj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xziqi.cn/Article/details/gt2fipytklz.html

[T43] Perl：字符串插值
来源：http://dali.zhengqikj.top/Article/details/gt2bewvulam.html

"值: $a"
来源：http://dali.yanxiufei.cn/Article/details/gt2sagpuhpb.html

[T44] Perl：条件
来源：http://dali.guowangkeji.top/Article/details/gt2dbrlmcex.html

if ($a > 0) { print "正"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2joumvrox.html

[T45] Perl：数组遍历
来源：http://dali.sxryk.cn/Article/details/gt2gljlsmnz.html

for my $x (@arr) { print $x; }
来源：http://dali.gaohongyu789.top/Article/details/gt2csnwpgut.html

[T46] Perl：哈希操作
来源：http://dali.zhoulong.xyz/Article/details/gt2gzvrsydm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yj20258888.top/Article/details/gt2xvsusytj.html

[T47] Perl：正则捕获
来源：http://dali.chenlongwang.top/Article/details/gt2iycgoean.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.kuanghao11.cn/Article/details/gt2hqprmbgv.html

[T48] Perl：正则替换
来源：http://dali.sxryk.cn/Article/details/gt2razpckdh.html

$s =~ s/old/new/g;
来源：http://dali.0kj1m.cn/Article/details/gt2djpwhkqh.html

[T49] Perl：函数
来源：http://dali.daxiang520.top/Article/details/gt2sihmrviv.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.gzhubu.top/Article/details/gt2wicifhep.html

[T50] Perl：逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gt2gklgixyy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2chxekkxt.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.shzxlz.cn/Article/details/gt2nvdifngk.html

[T51] Scala：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gt2zxkhtzpy.html

println("Hello")
来源：http://dali.316326.xyz/Article/details/gt2olbnxgqy.html

[T52] Scala：变量
来源：http://dali.ehwqpu.com/Article/details/gt2rujamrek.html

val a = 1;  var b = 2
来源：http://dali.ppjwa.cn/Article/details/gt2mykbtcyw.html

[T53] Scala：字符串插值
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ilwcghbb.html

s"值: $b"
来源：http://dali.xinyue.icu/Article/details/gt2exlioced.html

[T54] Scala：集合映射
来源：http://dali.kuanghao11.cn/Article/details/gt2dpalhcqc.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jianghu66.top/Article/details/gt2fuhcjybk.html

[T55] Scala：集合过滤
来源：http://dali.zhoulong.xyz/Article/details/gt2uaoklpwo.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hammf.cn/Article/details/gt2dltsisao.html

[T56] Scala：样例类
来源：http://dali.daxiang520.top/Article/details/gt2ojryrddq.html

case class User(name: String, age: Int)
来源：http://dali.zhiwuduotai.top/Article/details/gt2lcjxxsos.html

[T57] Scala：模式匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pmoyctot.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.aibaodan.cn/Article/details/gt2spelymeu.html

[T58] Scala：函数定义
来源：http://dali.pengpengdd.cyou/Article/details/gt2zgrowqxt.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.pengpengdd.cyou/Article/details/gt2ajnpeyrv.html

[T59] Scala：循环
来源：http://dali.ppjwa.cn/Article/details/gt2kthsauww.html

for (i <- 1 to 10) println(i)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xdoqtvvv.html

[T60] Scala：折叠
来源：http://dali.guowangkeji.top/Article/details/gt2xlkptmuh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.tanke756.top/Article/details/gt2ugsgtmtw.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gt2rwmlxkha.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.fzhhl.top/Article/details/gt2hvidweur.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gt2jhjtviat.html

[U01] Py：创建虚拟环境
来源：http://dali.yj202588.top/Article/details/gt2lkzynkkj.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.shangyingyoupin.top/Article/details/gt2hywtxcek.html

[U02] Py：导出 / 安装依赖
来源：http://dali.redwolf501.top/Article/details/gt2lgiekrtf.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.hongshengwenyu.top/Article/details/gt2otblgknt.html

[U03] Py：加载 .env 配置
来源：http://dali.xuetiantiany.cn/Article/details/gt2qjofocew.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yuxming.cn/Article/details/gt2anqkjquu.html

[U04] Py：变量调试打印
来源：http://dali.ehwqpu.com/Article/details/gt2ojwttojf.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.ivvv.top/Article/details/gt2msyukvxg.html

[U05] Py：列表去重且保序
来源：http://dali.bjfxy.top/Article/details/gt2vehsrgfs.html

list(dict.fromkeys(arr))
来源：http://dali.cashguo.top/Article/details/gt2zdmaanzh.html

[U06] Py：合并两个字典
来源：http://dali.ehwqpu.com/Article/details/gt2jddnszed.html

{**a, **b}
来源：http://dali.hnxiangtu.top/Article/details/gt2neorkbbx.html


<!-- 参考信息 -->