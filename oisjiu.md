代发 wailian999

openssl rand -hex 16
来源：http://dali.hnxiangtu.top/Article/details/gt2dnybazoh.html

[R68] 计算文件校验值
来源：http://dali.tianlin.xyz/Article/details/gt2evflvxpt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ivvv.top/Article/details/gt2lypjqizl.html

[R69] 生成随机密码
来源：http://dali.tianlin.xyz/Article/details/gt2wncvieih.html

head -c 16 /dev/urandom | base64
来源：http://dali.yj20258.top/Article/details/gt2mrfdwfjh.html

[R70] 时间戳与互转
来源：http://dali.quarkkingdee.top/Article/details/gt2qfiwgffa.html

date +%s;  date -d @1700000000
来源：http://dali.cashguo.top/Article/details/gt2styipjvr.html

[R71] 日期格式化
来源：http://dali.316326.xyz/Article/details/gt2uxlgawik.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj20258.top/Article/details/gt2dbiqktwk.html

[R72] 等待端口就绪
来源：http://dali.daria6918.cn/Article/details/gt2earndpnh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.meibo888.top/Article/details/gt2djgkjodw.html

[R73] 分割大日志
来源：http://dali.yongpay.top/Article/details/gt2fxiwukvc.html

split -l 1000 big.log part_
来源：http://dali.sweek.top/Article/details/gt2lelpvvmn.html

[R74] 批量重命名
来源：http://dali.yj20258.top/Article/details/gt2bnxmvocd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hongshengwenyu.top/Article/details/gt2qszfcrar.html

[R75] 导出环境变量
来源：http://dali.xinyue.icu/Article/details/gt2dxunsxtu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.0kj1m.cn/Article/details/gt2getidofd.html

[R76] 使用临时文件
来源：http://dali.bjfxy.top/Article/details/gt2nbshidtr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhengqikj.top/Article/details/gt2gjvxxvlk.html

[R77] 读取用户输入
来源：http://dali.cashguo.top/Article/details/gt2tapxrgdi.html

read -rp "请输入: " ans
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rlqduzlg.html

[R78] 交互式菜单
来源：http://dali.bjfxy.top/Article/details/gt2mdnymwyd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.tanke756.top/Article/details/gt2neqhieqn.html

[R79] 解析命令行选项
来源：http://dali.bjfxy.top/Article/details/gt2tzqfbwuy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xuanzx.com/Article/details/gt2wiiaymim.html

[R80] 查看脚本执行耗时
来源：http://dali.chenzaomai.com/Article/details/gt2bmwajvaq.html

time ./run.sh
来源：http://dali.zhiwuduotai.top/Article/details/gt2johvmzyf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tkkjxphu.html

S. C / C++ 专题
来源：http://dali.dashuyun.cn/Article/details/gt2iatvqctw.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gt2lyikgjpw.html

[S01] C：Hello World
来源：http://dali.gotoacloud.top/Article/details/gt2wekgrgwk.html

#include <stdio.h>
来源：http://dali.jyoumei.cn/Article/details/gt2bwiramel.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2wskdaido.html

[S02] C：变量与格式化输出
来源：http://dali.cdnleiting.top/Article/details/gt2bbyurspf.html

int a = 10; printf("%d\n", a);
来源：http://dali.hywenlv.cn/Article/details/gt2uooanwas.html

[S03] C：读入整数
来源：http://dali.meibo888.top/Article/details/gt2jakcfbnn.html

int x; scanf("%d", &x);
来源：http://dali.nwbrower.top/Article/details/gt2ndqmqhqw.html

[S04] C：字符串复制
来源：http://dali.sxryk.cn/Article/details/gt2obudzumy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.fengsongda.top/Article/details/gt2wrauxhgr.html

[S05] C：字符串长度
来源：http://dali.hnxiangtu.top/Article/details/gt2pnfxvkuq.html

strlen(s)
来源：http://dali.jinqigfzy.top/Article/details/gt2puhuqfub.html

[S06] C：字符串比较
来源：http://dali.haohaochexian.top/Article/details/gt2frzxabtd.html

strcmp(a, b) == 0
来源：http://dali.dianchejie.cn/Article/details/gt2hqcovvph.html

[S07] C：数组遍历求和
来源：http://dali.sysykeji.top/Article/details/gt2szgwbvwc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhiwuduotai.top/Article/details/gt2auqkqtsz.html

[S08] C：动态内存分配与释放
来源：http://dali.jlsjyb.cn/Article/details/gt2jrqkvkwb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.birdmap.top/Article/details/gt2omdibata.html

[S09] C：结构体定义与初始化
来源：http://dali.zhongyouzk.top/Article/details/gt2oflsbrsz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.vqdsnc.cn/Article/details/gt2strvzgqs.html

[S10] C：指针与解引用
来源：http://dali.yj20258.top/Article/details/gt2hikhljqg.html

int *p = &a;  *p = 5;
来源：http://dali.snrcjt.cn/Article/details/gt2vszwnfxd.html

[S11] C：逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gt2nbtpdsum.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shangyingyoupin.top/Article/details/gt2ghpqojon.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sxryk.cn/Article/details/gt2mjwtmpou.html

fclose(f);
来源：http://dali.yuanzhike.top/Article/details/gt2aorqdcdm.html

[S12] C：写文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2dvkkovmd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yj202588.top/Article/details/gt2rzjqkamb.html

[S13] C：宏定义
来源：http://dali.yongpay.top/Article/details/gt2uilfsmij.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jyoumei.cn/Article/details/gt2cyigqbes.html

[S14] C：枚举
来源：http://dali.yongpay.top/Article/details/gt2avmiczep.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xinyue.icu/Article/details/gt2juakpywz.html

[S15] C：类型转换
来源：http://dali.hysaishi.cn/Article/details/gt2dgjcwkxu.html

(double) a / b
来源：http://dali.yuanzhike.top/Article/details/gt2xtfnxwoh.html

[S16] C：位操作置位
来源：http://dali.xylfe.cn/Article/details/gt2rqrvmlbk.html

x |= (1 << 3);
来源：http://dali.chenjidiqi.icu/Article/details/gt2pbnqxhbk.html

[S17] C：安全拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gt2eckvryrf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.svipenyu.cn/Article/details/gt2vfyrvjsq.html

[S18] C：命令行参数
来源：http://dali.chenzaomai.com/Article/details/gt2lebjksmw.html

int main(int argc, char **argv)
来源：http://dali.jinqigufen.top/Article/details/gt2wwarkrwc.html

[S19] C：快速排序
来源：http://dali.yueranfly.top/Article/details/gt2lbuaexaf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.redwolf501.top/Article/details/gt2lwwapslk.html

[S20] C：二分查找
来源：http://dali.sxryk.cn/Article/details/gt2hheokfjs.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.guannengcc.top/Article/details/gt2kpavbnry.html

[S21] C：字符类别判断
来源：http://dali.shangyingyoupin.top/Article/details/gt2cgglxngw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinqigfzy.top/Article/details/gt2xdttvgxm.html

[S22] C：字符串转数字
来源：http://dali.tianlin.xyz/Article/details/gt2qmgyxipx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.316326.xyz/Article/details/gt2wehfgify.html

[S23] C：随机数
来源：http://dali.cashguo.top/Article/details/gt2zretzjfi.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.chenjidiqi.icu/Article/details/gt2rbjfsgxl.html

[S24] C：获取本地时间
来源：http://dali.yuxming.cn/Article/details/gt2qawfvvmk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shuidangran.top/Article/details/gt2fntvdcwr.html

[S25] C：内存拷贝
来源：http://dali.jiagoushi.top/Article/details/gt2camktjwn.html

memcpy(dst, src, n);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yhegnfzx.html

[S26] C：内存清零
来源：http://dali.cdnleiting.top/Article/details/gt2uewxbsxk.html

memset(a, 0, sizeof a);
来源：http://dali.hnqzz.top/Article/details/gt2ikhibahe.html

[S27] C：定义常量
来源：http://dali.fzhhl.top/Article/details/gt2vrsncrkx.html

const double PI = 3.14159;
来源：http://dali.zhoulong.xyz/Article/details/gt2doqpbcqf.html

[S28] C：静态变量
来源：http://dali.cheryme.top/Article/details/gt2xgksaxwe.html

static int counter = 0;
来源：http://dali.pengpengdd.cyou/Article/details/gt2cfrwfctz.html

[S29] C：变参函数
来源：http://dali.fzhhl.top/Article/details/gt2aeoahdfp.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shuidangran.top/Article/details/gt2xtslyqrh.html

[S30] C：头文件保护
来源：http://dali.yj20258.top/Article/details/gt2eshoqlpl.html

#ifndef X_H
来源：http://dali.316326.xyz/Article/details/gt2vlnozqyy.html

#define X_H
来源：http://dali.yuxming.cn/Article/details/gt2omsuowym.html

#endif
来源：http://dali.hysaishi.cn/Article/details/gt2cdwnvomz.html

[S31] C++：Hello World
来源：http://dali.xziqi.cn/Article/details/gt2khgkfopc.html

#include <iostream>
来源：http://dali.yanxiufei.cn/Article/details/gt2rikbgrss.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.fengsongda.top/Article/details/gt2dtpgkgra.html

[S32] C++：字符串
来源：http://dali.pengpengdd.cyou/Article/details/gt2mzmsxele.html

std::string s = "hi";  s += "!";
来源：http://dali.bjfxy.top/Article/details/gt2atuwvkjv.html

[S33] C++：vector 增删
来源：http://dali.yangfankeji.com/Article/details/gt2tfgugzsr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yangfankeji.com/Article/details/gt2myxgnbrl.html

[S34] C++：遍历 vector
来源：http://dali.xziqi.cn/Article/details/gt2aiuxkacp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.feifeiyinyue.top/Article/details/gt2howrfgfv.html

[S35] C++：map
来源：http://dali.hongshengwenyu.top/Article/details/gt2vngeedzg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xziqi.cn/Article/details/gt2xvkxzouy.html

[S36] C++：unordered_map
来源：http://dali.quarkkingdee.top/Article/details/gt2wtpndtfk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cucudq.cn/Article/details/gt2dtwswzni.html

[S37] C++：set
来源：http://dali.hammf.cn/Article/details/gt2loirkumd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jiagoushi.top/Article/details/gt2gyqkwhct.html

[S38] C++：排序
来源：http://dali.9152youxi.cn/Article/details/gt2evaiylvf.html

std::sort(v.begin(), v.end());
来源：http://dali.ivvv.top/Article/details/gt2kjgqzgxj.html

[S39] C++：自定义比较器排序
来源：http://dali.pycfn.com/Article/details/gt2bupccvbj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.0kj1m.cn/Article/details/gt2wpxuxnui.html

[S40] C++：查找元素
来源：http://dali.sxryk.cn/Article/details/gt2omlvwjcu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yj202588.top/Article/details/gt2qtzqveko.html

[S41] C++：类与构造函数
来源：http://dali.gaohongyu789.top/Article/details/gt2fjapdeax.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gt2xkvnreyv.html

[S42] C++：继承与虚函数
来源：http://dali.havefunace.top/Article/details/gt2xysptkma.html

class B : public Base { public: void f() override {} };
来源：http://dali.smart0.xyz/Article/details/gt2svyxspca.html

[S43] C++：智能指针
来源：http://dali.jinqigufen.top/Article/details/gt2zyvigmpe.html

auto p = std::make_unique<int>(5);
来源：http://dali.yuxming.cn/Article/details/gt2zstbkxeb.html

[S44] C++：引用传参
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wdmefeyi.html

void inc(int &x) { ++x; }
来源：http://dali.jlsjyb.cn/Article/details/gt2mipsruge.html

[S45] C++：lambda
来源：http://dali.xuetiantiany.cn/Article/details/gt2qtrjcjgj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yanxiufei.cn/Article/details/gt2jrqsszmk.html

[S46] C++：函数模板
来源：http://dali.hfpthk.cn/Article/details/gt2elxquaoi.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yuanzhike.top/Article/details/gt2bxoojtif.html

[S47] C++：结构化绑定遍历
来源：http://dali.hysaishi.cn/Article/details/gt2ctndhgtq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xziqi.cn/Article/details/gt2vwmoebtn.html

[S48] C++：逐行读文件
来源：http://dali.yueranfly.top/Article/details/gt2mjltxzfm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jianghu66.top/Article/details/gt2yysfxirz.html

while (std::getline(in, line)) { }
来源：http://dali.ybcxt.top/Article/details/gt2mqfnmclr.html

[S49] C++：写文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2ikbkyhss.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.guowangkeji.top/Article/details/gt2yohjfvef.html

[S50] C++：格式化数字
来源：http://dali.0kj1m.cn/Article/details/gt2dovrtmvf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sysykeji.top/Article/details/gt2kmxxqxsc.html

[S51] C++：显式类型转换
来源：http://dali.shangyingyoupin.top/Article/details/gt2sfmvipvv.html

static_cast<double>(a) / b
来源：http://dali.yangfankeji.com/Article/details/gt2axbnmdse.html

[S52] C++：const 与 noexcept
来源：http://dali.nwbrower.top/Article/details/gt2hrnhloiq.html

int size() const noexcept { return n_; }
来源：http://dali.gotoacloud.top/Article/details/gt2uwimjzkr.html

[S53] C++：移动语义
来源：http://dali.pengpengdd.cyou/Article/details/gt2sgshwykg.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gt2mjwsmamw.html

[S54] C++：异常处理
来源：http://dali.hfpthk.cn/Article/details/gt2wzqitggz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jianghu66.top/Article/details/gt2rhhabztr.html

[S55] C++：结构化绑定
来源：http://dali.nwbrower.top/Article/details/gt2txjxxpbq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cdnleiting.top/Article/details/gt2lautngwq.html

[S56] C++：optional
来源：http://dali.jlsjyb.cn/Article/details/gt2qfnllmpl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hysaishi.cn/Article/details/gt2uortdjrb.html

[S57] C++：编译期常量
来源：http://dali.nanxuanxn.top/Article/details/gt2tdsmdxkk.html

constexpr int N = 10;
来源：http://dali.ehwqpu.com/Article/details/gt2pmspclgz.html

[S58] C++：命名空间
来源：http://dali.gogol.net.cn/Article/details/gt2fnrzoasf.html

namespace ns { int f() { return 1; } }
来源：http://dali.sweek.top/Article/details/gt2oktcnvkv.html

[S59] C++：静态断言
来源：http://dali.tanke756.top/Article/details/gt2vqzluvtw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jianghu66.top/Article/details/gt2zotxrxil.html

[S60] C++：遍历并删除元素
来源：http://dali.nanxinkj.top/Article/details/gt2mrqomrap.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.andypj.xyz/Article/details/gt2ogxagyqw.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2msdmgpzp.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wdlczllj.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gt2sirndzmx.html

[T01] Kotlin：Hello World
来源：http://dali.smart0.xyz/Article/details/gt2rxjdwnag.html

println("Hello")
来源：http://dali.tianlin.xyz/Article/details/gt2nwfteohe.html

[T02] Kotlin：变量
来源：http://dali.ybcxt.top/Article/details/gt2gufmsjih.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhongyouzk.top/Article/details/gt2dtlnpenb.html

[T03] Kotlin：字符串模板
来源：http://dali.sweek.top/Article/details/gt2rdswvsbm.html

"值: $b"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jpodinle.html

[T04] Kotlin：空安全
来源：http://dali.yangfankeji.com/Article/details/gt2yxknhaar.html

val n: String? = null;  n?.length
来源：http://dali.yuanzhike.top/Article/details/gt2zmntwopa.html

[T05] Kotlin：when 表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gt2fkdadjak.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xziqi.cn/Article/details/gt2dwodezua.html

[T06] Kotlin：集合映射
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nskmssof.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenzaomai.com/Article/details/gt2bjjzmtmv.html

[T07] Kotlin：集合过滤
来源：http://dali.vqdsnc.cn/Article/details/gt2quprufyq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2flzataue.html

[T08] Kotlin：数据类
来源：http://dali.hysaishi.cn/Article/details/gt2itmipjfg.html

data class User(val name: String, val age: Int)
来源：http://dali.wangshuangyany.cn/Article/details/gt2mcepibfo.html

[T09] Kotlin：扩展函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jfavvxci.html

fun String.exclaim() = this + "!"
来源：http://dali.xylfe.cn/Article/details/gt2zosywqrq.html

[T10] Kotlin：默认参数
来源：http://dali.yj20258888.top/Article/details/gt2vhagspxl.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jiagoushi.top/Article/details/gt2moccjiam.html

[T11] Kotlin：协程
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tefusjys.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xuanzx.com/Article/details/gt2eljuusuf.html

[T12] Kotlin：解构声明
来源：http://dali.wangdashe.top/Article/details/gt2zdkemtjd.html

val (a, b) = Pair(1, 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2mffolzsw.html

[T13] Kotlin：只读 Map
来源：http://dali.shangyingyoupin.top/Article/details/gt2baenbaes.html

val m = mapOf("a" to 1)
来源：http://dali.haohaochexian.top/Article/details/gt2dxphmnmn.html

[T14] Kotlin：循环
来源：http://dali.shangyingyoupin.top/Article/details/gt2gcgmaiqn.html

for (i in 1..10) println(i)
来源：http://dali.havefunace.top/Article/details/gt2ijvudhof.html

[T15] Kotlin：接口
来源：http://dali.gogol.net.cn/Article/details/gt2oztpnydk.html

interface Shape { fun area(): Double }
来源：http://dali.jinqigufen.top/Article/details/gt2dbvtabts.html

[T16] Swift：Hello World
来源：http://dali.chenzaomai.com/Article/details/gt2pewrblri.html

print("Hello")
来源：http://dali.andypj.xyz/Article/details/gt2xqbfjdup.html

[T17] Swift：变量与常量
来源：http://dali.cucudq.cn/Article/details/gt2piljwrjq.html

var a = 1;  let b = 2
来源：http://dali.shzxlz.cn/Article/details/gt2mmuqqnnq.html

[T18] Swift：字符串插值
来源：http://dali.zdqjudy.top/Article/details/gt2hsqewuid.html

"值: \(b)"
来源：http://dali.feifeiyinyue.top/Article/details/gt2equxsqlk.html

[T19] Swift：可选绑定
来源：http://dali.shangyingyoupin.top/Article/details/gt2lcjwxvqe.html

if let n = opt { print(n) }
来源：http://dali.sweek.top/Article/details/gt2mwpcnklo.html

[T20] Swift：数组操作
来源：http://dali.haohaochexian.top/Article/details/gt2zcsqjeph.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zwbnjajh.html

[T21] Swift：遍历
来源：http://dali.iojbl.cn/Article/details/gt2ihxzacaq.html

for x in a { print(x) }
来源：http://dali.daria6918.cn/Article/details/gt2yeqzwgng.html

[T22] Swift：字典
来源：http://dali.sxryk.cn/Article/details/gt2mbroxnqn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xuetiantiany.cn/Article/details/gt2qivcdcug.html

[T23] Swift：函数
来源：http://dali.feifeiyinyue.top/Article/details/gt2urqjwrna.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jinqigfzy.top/Article/details/gt2kuuvyxxq.html

[T24] Swift：闭包
来源：http://dali.fengsongda.top/Article/details/gt2zlrrfswj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.nwbrower.top/Article/details/gt2givyqsqs.html

[T25] Swift：结构体
来源：http://dali.yj202588.top/Article/details/gt2lbnatagw.html

struct P { var x: Int }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2phvpzvaq.html

[T26] Swift：类与重写
来源：http://dali.nanxinkj.top/Article/details/gt2ympnzyds.html

class A: Base { override func f() {} }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nbvnobny.html

[T27] Swift：错误处理
来源：http://dali.hnxiangtu.top/Article/details/gt2cwxodniq.html

do { try f() } catch { print(error) }
来源：http://dali.jqgfzy.top/Article/details/gt2dqliqhst.html

[T28] Swift：枚举
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bpzbxzol.html

enum Color { case red, green }
来源：http://dali.nanxinkj.top/Article/details/gt2fzpjiqbz.html

[T29] Swift：guard 提前返回
来源：http://dali.ydzc1.top/Article/details/gt2gtsqbpcw.html

guard let x = opt else { return }
来源：http://dali.zhixingplan.top/Article/details/gt2zrtgnhet.html

[T30] Swift：协议
来源：http://dali.svipenyu.cn/Article/details/gt2onmegmif.html

protocol Shape { func area() -> Double }
来源：http://dali.zdqjudy.top/Article/details/gt2nzsxabsd.html

[T31] Lua：Hello World
来源：http://dali.sxryk.cn/Article/details/gt2cwiwsxad.html

print("Hello")
来源：http://dali.ybcxt.top/Article/details/gt2evrfkorz.html

[T32] Lua：局部变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cqrqvjyq.html

local a = 1
来源：http://dali.sxryk.cn/Article/details/gt2skggatip.html

[T33] Lua：表（数组）
来源：http://dali.jyoumei.cn/Article/details/gt2edrpccts.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.sufxvd.cn/Article/details/gt2dxenmlvl.html

[T34] Lua：遍历表
来源：http://dali.ybcxt.top/Article/details/gt2tocwebzl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.tanke756.top/Article/details/gt2hfvkexim.html

[T35] Lua：字典表
来源：http://dali.gzhubu.top/Article/details/gt2pzfeircd.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qhszuany.html

[T36] Lua：函数
来源：http://dali.tanke756.top/Article/details/gt2fpfyakbm.html

function add(a, b) return a + b end
来源：http://dali.zdqjudy.top/Article/details/gt2mnqdaiev.html

[T37] Lua：字符串拼接
来源：http://dali.guannengcc.top/Article/details/gt2zjwgvodm.html

"a" .. "b"
来源：http://dali.mhx1999.top/Article/details/gt2wkzydvev.html

[T38] Lua：条件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xrgbmhcc.html

if x > 0 then print("正") end
来源：http://dali.smart0.xyz/Article/details/gt2uiaeljqz.html

[T39] Lua：模式匹配
来源：http://dali.shangyingyoupin.top/Article/details/gt2bfpiqbmx.html

string.find(s, "%d+")
来源：http://dali.quarkkingdee.top/Article/details/gt2dyxtejjm.html

[T40] Lua：元表
来源：http://dali.hywenlv.cn/Article/details/gt2rzyihufc.html

setmetatable({}, { __index = base })
来源：http://dali.feifeiyinyue.top/Article/details/gt2xdkzpqfa.html

[T41] Perl：Hello World
来源：http://dali.jqgfzy.top/Article/details/gt2galbomia.html

print "Hello\n";
来源：http://dali.birdmap.top/Article/details/gt2ycxyffrl.html

[T42] Perl：变量类型
来源：http://dali.cashguo.top/Article/details/gt2tcxvweoo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xuanzx.com/Article/details/gt2givlbzuq.html

[T43] Perl：字符串插值
来源：http://dali.jianghu66.top/Article/details/gt2qwawghyq.html

"值: $a"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2frtowdit.html

[T44] Perl：条件
来源：http://dali.sweek.top/Article/details/gt2sosdmrpm.html

if ($a > 0) { print "正"; }
来源：http://dali.snrcjt.cn/Article/details/gt2wvparbjl.html

[T45] Perl：数组遍历
来源：http://dali.0kj1m.cn/Article/details/gt2grufmawv.html

for my $x (@arr) { print $x; }
来源：http://dali.fzhhl.top/Article/details/gt2mxcnhdez.html

[T46] Perl：哈希操作
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fibfcsxx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ybcxt.top/Article/details/gt2zngypncr.html

[T47] Perl：正则捕获
来源：http://dali.gaohongyu789.top/Article/details/gt2pzxvlldn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.nwbrower.top/Article/details/gt2wnvskugj.html

[T48] Perl：正则替换
来源：http://dali.dashuyun.cn/Article/details/gt2pjrnigia.html

$s =~ s/old/new/g;
来源：http://dali.wangshuangyany.cn/Article/details/gt2liidzxfe.html

[T49] Perl：函数
来源：http://dali.svipenyu.cn/Article/details/gt2kqqxasia.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.jlsjyb.cn/Article/details/gt2weoaflqw.html

[T50] Perl：逐行读文件
来源：http://dali.daria6918.cn/Article/details/gt2gkwyziyd.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.zhoulong.xyz/Article/details/gt2dojivorh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.nanxuanxn.top/Article/details/gt2vvikkgje.html

[T51] Scala：Hello World
来源：http://dali.nanxinkj.top/Article/details/gt2wpogoday.html

println("Hello")
来源：http://dali.wangdashe.top/Article/details/gt2qopmtzxv.html

[T52] Scala：变量
来源：http://dali.hysaishi.cn/Article/details/gt2putetinl.html

val a = 1;  var b = 2
来源：http://dali.zhongyouzk.top/Article/details/gt2sfybmuci.html

[T53] Scala：字符串插值
来源：http://dali.sysykeji.top/Article/details/gt2wkfnafuj.html

s"值: $b"
来源：http://dali.ybcxt.top/Article/details/gt2arogzwqn.html

[T54] Scala：集合映射
来源：http://dali.0kj1m.cn/Article/details/gt2vqyqtsgu.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.gogol.net.cn/Article/details/gt2qqrwyopi.html

[T55] Scala：集合过滤
来源：http://dali.andypj.xyz/Article/details/gt2zonlsxex.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.dashuyun.cn/Article/details/gt2yneexxqq.html

[T56] Scala：样例类
来源：http://dali.daxiang520.top/Article/details/gt2ntspjlnd.html

case class User(name: String, age: Int)
来源：http://dali.havefunace.top/Article/details/gt2oddkzbde.html

[T57] Scala：模式匹配
来源：http://dali.haohaochexian.top/Article/details/gt2moijxenk.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.sweek.top/Article/details/gt2eefakhlk.html

[T58] Scala：函数定义
来源：http://dali.sweek.top/Article/details/gt2kkhlidmc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.tanke756.top/Article/details/gt2eihbhzey.html

[T59] Scala：循环
来源：http://dali.chenlongwang.top/Article/details/gt2fybkppja.html

for (i <- 1 to 10) println(i)
来源：http://dali.xinyue.icu/Article/details/gt2mwnlobuz.html

[T60] Scala：折叠
来源：http://dali.cdnleiting.top/Article/details/gt2jxewkvdl.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.andypj.xyz/Article/details/gt2oqkhqclv.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2ltplebqv.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.guowangkeji.top/Article/details/gt2drjewxwa.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2udmpafgg.html

[U01] Py：创建虚拟环境
来源：http://dali.andypj.xyz/Article/details/gt2uqhyjemw.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jinqigfzy.top/Article/details/gt2eeobasin.html

[U02] Py：导出 / 安装依赖
来源：http://dali.yongpay.top/Article/details/gt2ivktirsw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.gzhubu.top/Article/details/gt2ezmmudan.html

[U03] Py：加载 .env 配置
来源：http://dali.xuanzx.com/Article/details/gt2kurnhojn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.yonumen.top/Article/details/gt2kfualikn.html

[U04] Py：变量调试打印
来源：http://dali.hnxiangtu.top/Article/details/gt2bwkwmtyw.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.shangyingyoupin.top/Article/details/gt2yvxirzal.html

[U05] Py：列表去重且保序
来源：http://dali.wangshuangyany.cn/Article/details/gt2wybusziz.html

list(dict.fromkeys(arr))
来源：http://dali.yonumen.top/Article/details/gt2lovkzfza.html

[U06] Py：合并两个字典
来源：http://dali.yj202588.top/Article/details/gt2rhxpcmxh.html

{**a, **b}
来源：http://dali.havefunace.top/Article/details/gt2eafbtzcb.html

[U07] Py：反转字典键值
来源：http://dali.316326.xyz/Article/details/gt2oczxeieg.html

{v: k for k, v in d.items()}
来源：http://dali.cqqwz.cn/Article/details/gt2pbniuxrv.html

[U08] Py：展平二维列表
来源：http://dali.hysaishi.cn/Article/details/gt2diizsfcp.html

[y for x in nested for y in x]
来源：http://dali.nanxinkj.top/Article/details/gt2bswjnyka.html


<!-- 参考信息 -->