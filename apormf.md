代发 wailian999

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.fzhhl.top/Article/details/gt2qbnykacz.html

[R66] 定时任务
来源：http://dali.yj20258.top/Article/details/gt2faryyswb.html

crontab -e;  crontab -l
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gmmgnwyz.html

[R67] 生成随机十六进制串
来源：http://dali.gaohongyu789.top/Article/details/gt2ojanvglz.html

openssl rand -hex 16
来源：http://dali.hysaishi.cn/Article/details/gt2aomzooxa.html

[R68] 计算文件校验值
来源：http://dali.cucudq.cn/Article/details/gt2bwdoecgz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2yzeqdgif.html

[R69] 生成随机密码
来源：http://dali.aizwys.cn/Article/details/gt2wtfuenzz.html

head -c 16 /dev/urandom | base64
来源：http://dali.ehwqpu.com/Article/details/gt2wiszvtgz.html

[R70] 时间戳与互转
来源：http://dali.hongshengwenyu.top/Article/details/gt2ctgofpso.html

date +%s;  date -d @1700000000
来源：http://dali.ppjwa.cn/Article/details/gt2whssfaoi.html

[R71] 日期格式化
来源：http://dali.hammf.cn/Article/details/gt2ykarnomm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zycfv.cn/Article/details/gt2yksdlqpr.html

[R72] 等待端口就绪
来源：http://dali.yj20258.top/Article/details/gt2cptzxwom.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj20258888.top/Article/details/gt2fulyenwc.html

[R73] 分割大日志
来源：http://dali.zycfv.cn/Article/details/gt2kdncpfjp.html

split -l 1000 big.log part_
来源：http://dali.daxiang520.top/Article/details/gt2cwvgsnis.html

[R74] 批量重命名
来源：http://dali.iojbl.cn/Article/details/gt2loobagwq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.feifeiyinyue.top/Article/details/gt2bqqhcogj.html

[R75] 导出环境变量
来源：http://dali.smart0.xyz/Article/details/gt2mpolzjff.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xuetiantiany.cn/Article/details/gt2lvwrpqrf.html

[R76] 使用临时文件
来源：http://dali.chenjidiqi.icu/Article/details/gt2darjueyz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuxming.cn/Article/details/gt2neaizdat.html

[R77] 读取用户输入
来源：http://dali.cheryme.top/Article/details/gt2ahdqsofj.html

read -rp "请输入: " ans
来源：http://dali.daxiang520.top/Article/details/gt2oanymeru.html

[R78] 交互式菜单
来源：http://dali.ppjwa.cn/Article/details/gt2jbxhffss.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhongyouzk.top/Article/details/gt2xvmrldsj.html

[R79] 解析命令行选项
来源：http://dali.chenzaomai.com/Article/details/gt2blenzsol.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2odurdkhv.html

[R80] 查看脚本执行耗时
来源：http://dali.ybcxt.top/Article/details/gt2worqwxig.html

time ./run.sh
来源：http://dali.sysykeji.top/Article/details/gt2iodcwvau.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2fkthrchy.html

S. C / C++ 专题
来源：http://dali.gzhubu.top/Article/details/gt2kwuqxygb.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gt2lrmkczti.html

[S01] C：Hello World
来源：http://dali.sufxvd.cn/Article/details/gt2orzandde.html

#include <stdio.h>
来源：http://dali.shangyingyoupin.top/Article/details/gt2dfffisqz.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.0kj1m.cn/Article/details/gt2gcecpssy.html

[S02] C：变量与格式化输出
来源：http://dali.ehwqpu.com/Article/details/gt2allsqhbw.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2istnaawl.html

[S03] C：读入整数
来源：http://dali.yj20258.top/Article/details/gt2aebgrppw.html

int x; scanf("%d", &x);
来源：http://dali.birdmap.top/Article/details/gt2pvzhtvts.html

[S04] C：字符串复制
来源：http://dali.yanxiufei.cn/Article/details/gt2kohjjpqn.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gotoacloud.top/Article/details/gt2hxxywsil.html

[S05] C：字符串长度
来源：http://dali.cdnleiting.top/Article/details/gt2lguurdsd.html

strlen(s)
来源：http://dali.fengsongda.top/Article/details/gt2ynpbzeep.html

[S06] C：字符串比较
来源：http://dali.c1oappe.top/Article/details/gt2smzlpzxw.html

strcmp(a, b) == 0
来源：http://dali.shangyingyoupin.top/Article/details/gt2zdoflgli.html

[S07] C：数组遍历求和
来源：http://dali.hnxiangtu.top/Article/details/gt2zgwypnom.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.quarkkingdee.top/Article/details/gt2vhthnebb.html

[S08] C：动态内存分配与释放
来源：http://dali.daxiang520.top/Article/details/gt2azmmoucp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.iojbl.cn/Article/details/gt2nuhrcpbh.html

[S09] C：结构体定义与初始化
来源：http://dali.sxryk.cn/Article/details/gt2xjudgytd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hfpthk.cn/Article/details/gt2jgrspesy.html

[S10] C：指针与解引用
来源：http://dali.feifeiyinyue.top/Article/details/gt2ezgdcfox.html

int *p = &a;  *p = 5;
来源：http://dali.tianlin.xyz/Article/details/gt2teiazfww.html

[S11] C：逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2tjtsgzwi.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cashguo.top/Article/details/gt2yiltkyjt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.dianchejie.cn/Article/details/gt2mhdmvgey.html

fclose(f);
来源：http://dali.jlsjyb.cn/Article/details/gt2asdgbcoy.html

[S12] C：写文件
来源：http://dali.sufxvd.cn/Article/details/gt2ghtfxpgv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jiagoushi.top/Article/details/gt2lusrvexs.html

[S13] C：宏定义
来源：http://dali.guannengcc.top/Article/details/gt2muvbmyyc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.iojbl.cn/Article/details/gt2wuahctaa.html

[S14] C：枚举
来源：http://dali.hfpthk.cn/Article/details/gt2npwygwcj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2prxglzbz.html

[S15] C：类型转换
来源：http://dali.9152youxi.cn/Article/details/gt2smimvxnv.html

(double) a / b
来源：http://dali.zycfv.cn/Article/details/gt2tfrwjhpp.html

[S16] C：位操作置位
来源：http://dali.aibaodan.cn/Article/details/gt2lcpeguqi.html

x |= (1 << 3);
来源：http://dali.jyoumei.cn/Article/details/gt2vxfkexnb.html

[S17] C：安全拼接字符串
来源：http://dali.mhx1999.top/Article/details/gt2tfykwetv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhoulong.xyz/Article/details/gt2teugpjqa.html

[S18] C：命令行参数
来源：http://dali.zhengqikj.top/Article/details/gt2kkdofdmg.html

int main(int argc, char **argv)
来源：http://dali.bjfxy.top/Article/details/gt2izvvmoew.html

[S19] C：快速排序
来源：http://dali.9152youxi.cn/Article/details/gt2kusafxes.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.316326.xyz/Article/details/gt2ubphpvib.html

[S20] C：二分查找
来源：http://dali.pengpengdd.cyou/Article/details/gt2odtgqzbg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hnxiangtu.top/Article/details/gt2zcsjolsl.html

[S21] C：字符类别判断
来源：http://dali.tianlin.xyz/Article/details/gt2kcftkmna.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gotoacloud.top/Article/details/gt2wortosdq.html

[S22] C：字符串转数字
来源：http://dali.shuidangran.top/Article/details/gt2tdzqchxj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yj20258.top/Article/details/gt2eorjwiwf.html

[S23] C：随机数
来源：http://dali.aibaodan.cn/Article/details/gt2jgrzvmzn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.dianchejie.cn/Article/details/gt2vzwtjhuu.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2sunvhplq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shzxlz.cn/Article/details/gt2jazjkspt.html

[S25] C：内存拷贝
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yrhqkyzy.html

memcpy(dst, src, n);
来源：http://dali.ybcxt.top/Article/details/gt2zgaqfhpd.html

[S26] C：内存清零
来源：http://dali.meibo888.top/Article/details/gt2icwfmdso.html

memset(a, 0, sizeof a);
来源：http://dali.ybcxt.top/Article/details/gt2dhsqlchr.html

[S27] C：定义常量
来源：http://dali.0kj1m.cn/Article/details/gt2tgdzoiac.html

const double PI = 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gt2extujkan.html

[S28] C：静态变量
来源：http://dali.sxryk.cn/Article/details/gt2goqtsgmb.html

static int counter = 0;
来源：http://dali.zhongyouzk.top/Article/details/gt2knisxdxl.html

[S29] C：变参函数
来源：http://dali.mhx1999.top/Article/details/gt2bhqngfuu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.nwbrower.top/Article/details/gt2nbhfvgfw.html

[S30] C：头文件保护
来源：http://dali.hywenlv.cn/Article/details/gt2bacfudpr.html

#ifndef X_H
来源：http://dali.vqdsnc.cn/Article/details/gt2jblnxppv.html

#define X_H
来源：http://dali.snrcjt.cn/Article/details/gt2ftufxaub.html

#endif
来源：http://dali.xinyue.icu/Article/details/gt2wqjsixsc.html

[S31] C++：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gt2yqjullfb.html

#include <iostream>
来源：http://dali.nanxinkj.top/Article/details/gt2armawtog.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hnqzz.top/Article/details/gt2jvurpfep.html

[S32] C++：字符串
来源：http://dali.sxryk.cn/Article/details/gt2vuekhgkc.html

std::string s = "hi";  s += "!";
来源：http://dali.andypj.xyz/Article/details/gt2jkvudtmj.html

[S33] C++：vector 增删
来源：http://dali.dashuyun.cn/Article/details/gt2mbuftukz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jqgufenzy.top/Article/details/gt2zfrjzjam.html

[S34] C++：遍历 vector
来源：http://dali.wangshuangyany.cn/Article/details/gt2fpnfqzwo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.fzhhl.top/Article/details/gt2xxhqclfr.html

[S35] C++：map
来源：http://dali.kuanghao11.cn/Article/details/gt2ksfjfjsc.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cucudq.cn/Article/details/gt2nvtawrhg.html

[S36] C++：unordered_map
来源：http://dali.ehwqpu.com/Article/details/gt2ybucpnjf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gt2lkbrzahb.html

[S37] C++：set
来源：http://dali.redwolf501.top/Article/details/gt2aacqghul.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yangfankeji.com/Article/details/gt2zdhpkmoz.html

[S38] C++：排序
来源：http://dali.tian-w.cn/Article/details/gt2chocygsa.html

std::sort(v.begin(), v.end());
来源：http://dali.shuidangran.top/Article/details/gt2oacjlsyp.html

[S39] C++：自定义比较器排序
来源：http://dali.xuetiantiany.cn/Article/details/gt2lqecbjgi.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.haohaochexian.top/Article/details/gt2szjdgjdy.html

[S40] C++：查找元素
来源：http://dali.daria6918.cn/Article/details/gt2rnvndnss.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.dashuyun.cn/Article/details/gt2kciggysd.html

[S41] C++：类与构造函数
来源：http://dali.cdnleiting.top/Article/details/gt2lhnsrpag.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.quarkkingdee.top/Article/details/gt2wecvtihr.html

[S42] C++：继承与虚函数
来源：http://dali.yj202588.top/Article/details/gt2hoqcmgmx.html

class B : public Base { public: void f() override {} };
来源：http://dali.meibo888.top/Article/details/gt2xaabfgsu.html

[S43] C++：智能指针
来源：http://dali.andypj.xyz/Article/details/gt2caugvbjw.html

auto p = std::make_unique<int>(5);
来源：http://dali.nanxuanxn.top/Article/details/gt2mtnwrvni.html

[S44] C++：引用传参
来源：http://dali.hywenlv.cn/Article/details/gt2fufhaumt.html

void inc(int &x) { ++x; }
来源：http://dali.yj20258888.top/Article/details/gt2mvgdwgbt.html

[S45] C++：lambda
来源：http://dali.smart0.xyz/Article/details/gt2mmlgmtnk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jyoumei.cn/Article/details/gt2peutjanc.html

[S46] C++：函数模板
来源：http://dali.yvedp.cn/Article/details/gt2itkjmgzl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.aibaodan.cn/Article/details/gt2llrmbhwr.html

[S47] C++：结构化绑定遍历
来源：http://dali.yanxiufei.cn/Article/details/gt2qkshseas.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cqqwz.cn/Article/details/gt2nxkobxjz.html

[S48] C++：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2futtweer.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yongpay.top/Article/details/gt2xntdugms.html

while (std::getline(in, line)) { }
来源：http://dali.yj202588.top/Article/details/gt2dmbkachv.html

[S49] C++：写文件
来源：http://dali.dianchejie.cn/Article/details/gt2irokowbj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yvedp.cn/Article/details/gt2sibxkuro.html

[S50] C++：格式化数字
来源：http://dali.jyoumei.cn/Article/details/gt2snzubhfr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gaohongyu789.top/Article/details/gt2ljlbpadx.html

[S51] C++：显式类型转换
来源：http://dali.wangdashe.top/Article/details/gt2ojemojgs.html

static_cast<double>(a) / b
来源：http://dali.316326.xyz/Article/details/gt2fcbxogxw.html

[S52] C++：const 与 noexcept
来源：http://dali.cucudq.cn/Article/details/gt2fgvyugwu.html

int size() const noexcept { return n_; }
来源：http://dali.dianchejie.cn/Article/details/gt2gllladkz.html

[S53] C++：移动语义
来源：http://dali.yj20258.top/Article/details/gt2lqwystej.html

std::vector<int> w = std::move(v);
来源：http://dali.hongshengwenyu.top/Article/details/gt2acoetyev.html

[S54] C++：异常处理
来源：http://dali.ydzc1.top/Article/details/gt2nrbmvzid.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.bjfxy.top/Article/details/gt2egjmhxtz.html

[S55] C++：结构化绑定
来源：http://dali.jiagoushi.top/Article/details/gt2oufvuwzj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hysaishi.cn/Article/details/gt2erqzxvyi.html

[S56] C++：optional
来源：http://dali.tanke756.top/Article/details/gt2okkfxtif.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.0kj1m.cn/Article/details/gt2cjpnauqw.html

[S57] C++：编译期常量
来源：http://dali.hywenlv.cn/Article/details/gt2lrfkfere.html

constexpr int N = 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2whcccolk.html

[S58] C++：命名空间
来源：http://dali.svipenyu.cn/Article/details/gt2xqtgfxaw.html

namespace ns { int f() { return 1; } }
来源：http://dali.nanxinkj.top/Article/details/gt2pvvhehzq.html

[S59] C++：静态断言
来源：http://dali.guannengcc.top/Article/details/gt2sfnffwus.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qjkjefgc.html

[S60] C++：遍历并删除元素
来源：http://dali.zdqjudy.top/Article/details/gt2bkccaqni.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.daxiang520.top/Article/details/gt2zbzaqtfl.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2aqcmdurq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ydzc1.top/Article/details/gt2rovedewb.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gt2gywkkmiu.html

[T01] Kotlin：Hello World
来源：http://dali.wangdashe.top/Article/details/gt2uaiedddf.html

println("Hello")
来源：http://dali.ehwqpu.com/Article/details/gt2kujmczqt.html

[T02] Kotlin：变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2pzqctsdn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.sweek.top/Article/details/gt2ayltqpts.html

[T03] Kotlin：字符串模板
来源：http://dali.cucudq.cn/Article/details/gt2msmwuimc.html

"值: $b"
来源：http://dali.zhiwuduotai.top/Article/details/gt2mdajxuel.html

[T04] Kotlin：空安全
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gosgjzur.html

val n: String? = null;  n?.length
来源：http://dali.c1oappe.top/Article/details/gt2aapkpjld.html

[T05] Kotlin：when 表达式
来源：http://dali.jqgfzy.top/Article/details/gt2hmixdkdf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jqgufenzy.top/Article/details/gt2bqabibwk.html

[T06] Kotlin：集合映射
来源：http://dali.shuidangran.top/Article/details/gt2zflaviwr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.guannengcc.top/Article/details/gt2gyeqjgvw.html

[T07] Kotlin：集合过滤
来源：http://dali.smart0.xyz/Article/details/gt2jtajlixl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.quarkkingdee.top/Article/details/gt2xiadrbyf.html

[T08] Kotlin：数据类
来源：http://dali.cqqwz.cn/Article/details/gt2ibdayqfv.html

data class User(val name: String, val age: Int)
来源：http://dali.jianghu66.top/Article/details/gt2njvciktb.html

[T09] Kotlin：扩展函数
来源：http://dali.yuanzhike.top/Article/details/gt2geiaejns.html

fun String.exclaim() = this + "!"
来源：http://dali.sysykeji.top/Article/details/gt2xseeictj.html

[T10] Kotlin：默认参数
来源：http://dali.yuanzhike.top/Article/details/gt2xmnhevlo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwprkrp.html

[T11] Kotlin：协程
来源：http://dali.svipenyu.cn/Article/details/gt2lpweyelr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xuanzx.com/Article/details/gt2cssbnimk.html

[T12] Kotlin：解构声明
来源：http://dali.hongshengwenyu.top/Article/details/gt2gbwsetov.html

val (a, b) = Pair(1, 2)
来源：http://dali.dashuyun.cn/Article/details/gt2vvnushyg.html

[T13] Kotlin：只读 Map
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2gftvlgon.html

val m = mapOf("a" to 1)
来源：http://dali.yueranfly.top/Article/details/gt2wqlrvtjn.html

[T14] Kotlin：循环
来源：http://dali.hfpthk.cn/Article/details/gt2pvcqckar.html

for (i in 1..10) println(i)
来源：http://dali.zdqjudy.top/Article/details/gt2btgezhct.html

[T15] Kotlin：接口
来源：http://dali.wangdashe.top/Article/details/gt2auhjwiih.html

interface Shape { fun area(): Double }
来源：http://dali.gzhubu.top/Article/details/gt2seshlmwf.html

[T16] Swift：Hello World
来源：http://dali.yonumen.top/Article/details/gt2eaalvins.html

print("Hello")
来源：http://dali.hysaishi.cn/Article/details/gt2opultfol.html

[T17] Swift：变量与常量
来源：http://dali.shzxlz.cn/Article/details/gt2ptmjspry.html

var a = 1;  let b = 2
来源：http://dali.shuidangran.top/Article/details/gt2rmsowciz.html

[T18] Swift：字符串插值
来源：http://dali.fengsongda.top/Article/details/gt2putykppj.html

"值: \(b)"
来源：http://dali.cqqwz.cn/Article/details/gt2ekdxvplr.html

[T19] Swift：可选绑定
来源：http://dali.havefunace.top/Article/details/gt2ozclfmay.html

if let n = opt { print(n) }
来源：http://dali.ppjwa.cn/Article/details/gt2ruwrrfyu.html

[T20] Swift：数组操作
来源：http://dali.mhx1999.top/Article/details/gt2ytjcmgzx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hongshengwenyu.top/Article/details/gt2pkrvronv.html

[T21] Swift：遍历
来源：http://dali.yangfankeji.com/Article/details/gt2geeqpqpl.html

for x in a { print(x) }
来源：http://dali.birdmap.top/Article/details/gt2quebxtmk.html

[T22] Swift：字典
来源：http://dali.ydzc1.top/Article/details/gt2obonrrzw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cucudq.cn/Article/details/gt2dgznlrgd.html

[T23] Swift：函数
来源：http://dali.iojbl.cn/Article/details/gt2uzunnuqk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.wangdashe.top/Article/details/gt2jprwhjej.html

[T24] Swift：闭包
来源：http://dali.wangdashe.top/Article/details/gt2fjivdjzq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.316326.xyz/Article/details/gt2issijkgn.html

[T25] Swift：结构体
来源：http://dali.hywenlv.cn/Article/details/gt2cjugrvbk.html

struct P { var x: Int }
来源：http://dali.chenjidiqi.icu/Article/details/gt2eubagbkp.html

[T26] Swift：类与重写
来源：http://dali.hysaishi.cn/Article/details/gt2tuxgevbb.html

class A: Base { override func f() {} }
来源：http://dali.cqqwz.cn/Article/details/gt2uslvkevc.html

[T27] Swift：错误处理
来源：http://dali.jiagoushi.top/Article/details/gt2evblcgzq.html

do { try f() } catch { print(error) }
来源：http://dali.sxryk.cn/Article/details/gt2pxqvaivh.html

[T28] Swift：枚举
来源：http://dali.fzhhl.top/Article/details/gt2vjvymcqs.html

enum Color { case red, green }
来源：http://dali.smart0.xyz/Article/details/gt2iflwueqg.html

[T29] Swift：guard 提前返回
来源：http://dali.zdqjudy.top/Article/details/gt2ampyhixm.html

guard let x = opt else { return }
来源：http://dali.aibaodan.cn/Article/details/gt2mxrhjfbi.html

[T30] Swift：协议
来源：http://dali.fzhhl.top/Article/details/gt2wxztajeb.html

protocol Shape { func area() -> Double }
来源：http://dali.c1oappe.top/Article/details/gt2xbnoykkl.html

[T31] Lua：Hello World
来源：http://dali.fzhhl.top/Article/details/gt2dsnbmkam.html

print("Hello")
来源：http://dali.jlsjyb.cn/Article/details/gt2wjmqqwld.html

[T32] Lua：局部变量
来源：http://dali.hysaishi.cn/Article/details/gt2usosijer.html

local a = 1
来源：http://dali.hywenlv.cn/Article/details/gt2wazkokkq.html

[T33] Lua：表（数组）
来源：http://dali.guannengcc.top/Article/details/gt2zkxjxetd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.wangdashe.top/Article/details/gt2hwxryjhy.html

[T34] Lua：遍历表
来源：http://dali.tianlin.xyz/Article/details/gt2wqximqmm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zdqjudy.top/Article/details/gt2yzsqfqbs.html

[T35] Lua：字典表
来源：http://dali.sxryk.cn/Article/details/gt2zmibyqjm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2weydzram.html

[T36] Lua：函数
来源：http://dali.hysaishi.cn/Article/details/gt2xinycwsd.html

function add(a, b) return a + b end
来源：http://dali.cashguo.top/Article/details/gt2avsnlwwm.html

[T37] Lua：字符串拼接
来源：http://dali.sxryk.cn/Article/details/gt2lpbqvlig.html

"a" .. "b"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ceekllrk.html

[T38] Lua：条件
来源：http://dali.gaohongyu789.top/Article/details/gt2mrcxzkwb.html

if x > 0 then print("正") end
来源：http://dali.cdnleiting.top/Article/details/gt2aykrkemh.html

[T39] Lua：模式匹配
来源：http://dali.yonumen.top/Article/details/gt2fcmwqznc.html

string.find(s, "%d+")
来源：http://dali.ybcxt.top/Article/details/gt2unwnnvyb.html

[T40] Lua：元表
来源：http://dali.bjfxy.top/Article/details/gt2klxjjjfi.html

setmetatable({}, { __index = base })
来源：http://dali.hnxiangtu.top/Article/details/gt2lqvdbwdq.html

[T41] Perl：Hello World
来源：http://dali.gotoacloud.top/Article/details/gt2wasdjlye.html

print "Hello\n";
来源：http://dali.tian-w.cn/Article/details/gt2vyhlmcfj.html

[T42] Perl：变量类型
来源：http://dali.shzxlz.cn/Article/details/gt2nrollizn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.wangdashe.top/Article/details/gt2nktpexhu.html

[T43] Perl：字符串插值
来源：http://dali.xuanzx.com/Article/details/gt2eoujwjmz.html

"值: $a"
来源：http://dali.jianghu66.top/Article/details/gt2ulaynoxx.html

[T44] Perl：条件
来源：http://dali.smart0.xyz/Article/details/gt2zgxfaldu.html

if ($a > 0) { print "正"; }
来源：http://dali.chenzaomai.com/Article/details/gt2oiopxypi.html

[T45] Perl：数组遍历
来源：http://dali.svipenyu.cn/Article/details/gt2sjsfswvb.html

for my $x (@arr) { print $x; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zqilaprj.html

[T46] Perl：哈希操作
来源：http://dali.aibaodan.cn/Article/details/gt2nikqssty.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jiagoushi.top/Article/details/gt2akcklynn.html

[T47] Perl：正则捕获
来源：http://dali.nanxuanxn.top/Article/details/gt2wslpvolu.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.tianlin.xyz/Article/details/gt2yneagftv.html

[T48] Perl：正则替换
来源：http://dali.jinghuilouyu.cn/Article/details/gt2osqrfjfp.html

$s =~ s/old/new/g;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ttikgunm.html

[T49] Perl：函数
来源：http://dali.iojbl.cn/Article/details/gt2beoamxod.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xuanzx.com/Article/details/gt2nqkojjcq.html

[T50] Perl：逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gt2kaqgpzoe.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.cqqwz.cn/Article/details/gt2ptafzptm.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xuanzx.com/Article/details/gt2xqgmbpbj.html

[T51] Scala：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mbdgcwar.html

println("Hello")
来源：http://dali.yongpay.top/Article/details/gt2kmwhqzxw.html

[T52] Scala：变量
来源：http://dali.daria6918.cn/Article/details/gt2xblwrokn.html

val a = 1;  var b = 2
来源：http://dali.hysaishi.cn/Article/details/gt2ndbebzkg.html

[T53] Scala：字符串插值
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2kdmujvyb.html

s"值: $b"
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2oadqumhk.html

[T54] Scala：集合映射
来源：http://dali.chenlongwang.top/Article/details/gt2dfuhlhxm.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jinqigufen.top/Article/details/gt2zyhzdnzk.html

[T55] Scala：集合过滤
来源：http://dali.feifeiyinyue.top/Article/details/gt2zlvtxhzl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.zhongyouzk.top/Article/details/gt2pdlzlfsa.html

[T56] Scala：样例类
来源：http://dali.yj20258.top/Article/details/gt2pkwerdsj.html

case class User(name: String, age: Int)
来源：http://dali.xylfe.cn/Article/details/gt2wsyebnuu.html

[T57] Scala：模式匹配
来源：http://dali.guannengcc.top/Article/details/gt2isdhwbzn.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.xylfe.cn/Article/details/gt2xmrcnedo.html

[T58] Scala：函数定义
来源：http://dali.xuetiantiany.cn/Article/details/gt2gjajtowh.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.wangdashe.top/Article/details/gt2dzuwumbf.html

[T59] Scala：循环
来源：http://dali.xinyue.icu/Article/details/gt2krppjhvm.html

for (i <- 1 to 10) println(i)
来源：http://dali.chenjidiqi.icu/Article/details/gt2sknhyafd.html

[T60] Scala：折叠
来源：http://dali.yj202588.top/Article/details/gt2ipqaksmh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sysykeji.top/Article/details/gt2qxmxkrwq.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gt2mxgtwfcg.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.zhongyouzk.top/Article/details/gt2kzqyyhdg.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2conprgrg.html

[U01] Py：创建虚拟环境
来源：http://dali.guannengcc.top/Article/details/gt2ittfmpfl.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.haohaochexian.top/Article/details/gt2uquyfcsv.html

[U02] Py：导出 / 安装依赖
来源：http://dali.cqqwz.cn/Article/details/gt2inpxxami.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kvruufsk.html

[U03] Py：加载 .env 配置
来源：http://dali.hongshengwenyu.top/Article/details/gt2tzbvdrbr.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.mhx1999.top/Article/details/gt2qkeclwlf.html

[U04] Py：变量调试打印
来源：http://dali.redwolf501.top/Article/details/gt2btaffyrq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.fengsongda.top/Article/details/gt2kjdyfver.html

[U05] Py：列表去重且保序
来源：http://dali.hnqzz.top/Article/details/gt2ceptkvla.html

list(dict.fromkeys(arr))
来源：http://dali.nanxuanxn.top/Article/details/gt2wnuphfrv.html

[U06] Py：合并两个字典
来源：http://dali.jinghuilouyu.cn/Article/details/gt2kuwwvait.html

{**a, **b}
来源：http://dali.kuanghao11.cn/Article/details/gt2bhhyzgwg.html


<!-- 参考信息 -->