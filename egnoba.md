代发 wailian999

openssl rand -hex 16
来源：http://dali.xylfe.cn/Article/details/gt2wlmzsdpr.html

[R68] 计算文件校验值
来源：http://dali.meibo888.top/Article/details/gt2zpiicqei.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.havefunace.top/Article/details/gt2yoqnwxif.html

[R69] 生成随机密码
来源：http://dali.sxryk.cn/Article/details/gt2dhrkksso.html

head -c 16 /dev/urandom | base64
来源：http://dali.tianlin.xyz/Article/details/gt2entywsam.html

[R70] 时间戳与互转
来源：http://dali.zhongyouzk.top/Article/details/gt2mshbkhrm.html

date +%s;  date -d @1700000000
来源：http://dali.9152youxi.cn/Article/details/gt2pswzzqms.html

[R71] 日期格式化
来源：http://dali.meibo888.top/Article/details/gt2altwqmgn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.cdnleiting.top/Article/details/gt2howfydkq.html

[R72] 等待端口就绪
来源：http://dali.yueranfly.top/Article/details/gt2pnewpguv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.9152youxi.cn/Article/details/gt2bxrjeklq.html

[R73] 分割大日志
来源：http://dali.snrcjt.cn/Article/details/gt2ponbraqz.html

split -l 1000 big.log part_
来源：http://dali.0kj1m.cn/Article/details/gt2sjbmfhlv.html

[R74] 批量重命名
来源：http://dali.0kj1m.cn/Article/details/gt2ufcswxvb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.aibaodan.cn/Article/details/gt2ngobicpe.html

[R75] 导出环境变量
来源：http://dali.c1oappe.top/Article/details/gt2vafvfgef.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jqgfzy.top/Article/details/gt2ceeklnan.html

[R76] 使用临时文件
来源：http://dali.jqgfzy.top/Article/details/gt2sbmjqcmd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2dmdsnjto.html

[R77] 读取用户输入
来源：http://dali.hysaishi.cn/Article/details/gt2dolyrzii.html

read -rp "请输入: " ans
来源：http://dali.hongshengwenyu.top/Article/details/gt2cunnjhky.html

[R78] 交互式菜单
来源：http://dali.feifeiyinyue.top/Article/details/gt2jnoxevpu.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shangyingyoupin.top/Article/details/gt2raoqtwec.html

[R79] 解析命令行选项
来源：http://dali.zhongyouzk.top/Article/details/gt2rngvzauw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yuxming.cn/Article/details/gt2vmfdketi.html

[R80] 查看脚本执行耗时
来源：http://dali.wangdashe.top/Article/details/gt2mifbwxxp.html

time ./run.sh
来源：http://dali.sweek.top/Article/details/gt2nqsrvcaw.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gt2okjslykz.html

S. C / C++ 专题
来源：http://dali.xziqi.cn/Article/details/gt2zbxkrjxb.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gt2yitajngt.html

[S01] C：Hello World
来源：http://dali.sysykeji.top/Article/details/gt2lvzkhjfz.html

#include <stdio.h>
来源：http://dali.sysykeji.top/Article/details/gt2kiimrjrj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cqqwz.cn/Article/details/gt2rcyjdmuf.html

[S02] C：变量与格式化输出
来源：http://dali.svipenyu.cn/Article/details/gt2rfucocvi.html

int a = 10; printf("%d\n", a);
来源：http://dali.0kj1m.cn/Article/details/gt2nanaorxz.html

[S03] C：读入整数
来源：http://dali.nanxuanxn.top/Article/details/gt2jhhtjcpx.html

int x; scanf("%d", &x);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2odxbjydp.html

[S04] C：字符串复制
来源：http://dali.feifeiyinyue.top/Article/details/gt2ejtxpzyx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cqqwz.cn/Article/details/gt2ovughcfn.html

[S05] C：字符串长度
来源：http://dali.pengpengdd.cyou/Article/details/gt2qoiyzqrq.html

strlen(s)
来源：http://dali.tianlin.xyz/Article/details/gt2ffvfjvao.html

[S06] C：字符串比较
来源：http://dali.mhx1999.top/Article/details/gt2yztyvgae.html

strcmp(a, b) == 0
来源：http://dali.xziqi.cn/Article/details/gt2hrfhrlrn.html

[S07] C：数组遍历求和
来源：http://dali.shuidangran.top/Article/details/gt2icjgkurw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.iojbl.cn/Article/details/gt2aopbefgy.html

[S08] C：动态内存分配与释放
来源：http://dali.chenlongwang.top/Article/details/gt2xgzrawqg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yvedp.cn/Article/details/gt2cjkbhiqw.html

[S09] C：结构体定义与初始化
来源：http://dali.0kj1m.cn/Article/details/gt2pzdpejwl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2vbsoedni.html

[S10] C：指针与解引用
来源：http://dali.haohaochexian.top/Article/details/gt2fphskjbe.html

int *p = &a;  *p = 5;
来源：http://dali.xylfe.cn/Article/details/gt2etqvbfuz.html

[S11] C：逐行读文件
来源：http://dali.sxryk.cn/Article/details/gt2ziftlteu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yangfankeji.com/Article/details/gt2gacmftix.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shuidangran.top/Article/details/gt2brspwajm.html

fclose(f);
来源：http://dali.chenzaomai.com/Article/details/gt2imitdtlb.html

[S12] C：写文件
来源：http://dali.ivvv.top/Article/details/gt2qoftbqaq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.pycfn.com/Article/details/gt2rjbckimf.html

[S13] C：宏定义
来源：http://dali.yangfankeji.com/Article/details/gt2fysnbkpa.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.redwolf501.top/Article/details/gt2hckgmmwf.html

[S14] C：枚举
来源：http://dali.guannengcc.top/Article/details/gt2fecjxvdd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.tianlin.xyz/Article/details/gt2pfnfmkmt.html

[S15] C：类型转换
来源：http://dali.dianchejie.cn/Article/details/gt2cdvszvdk.html

(double) a / b
来源：http://dali.redwolf501.top/Article/details/gt2rnpicewa.html

[S16] C：位操作置位
来源：http://dali.nanxuanxn.top/Article/details/gt2ndsjmeza.html

x |= (1 << 3);
来源：http://dali.yj20258888.top/Article/details/gt2axsyocrg.html

[S17] C：安全拼接字符串
来源：http://dali.hnqzz.top/Article/details/gt2pntlncnp.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.nanxinkj.top/Article/details/gt2ynrstkin.html

[S18] C：命令行参数
来源：http://dali.jyoumei.cn/Article/details/gt2ozodcrau.html

int main(int argc, char **argv)
来源：http://dali.aibaodan.cn/Article/details/gt2edierjja.html

[S19] C：快速排序
来源：http://dali.xylfe.cn/Article/details/gt2qwnozonf.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.9152youxi.cn/Article/details/gt2fgddkfbp.html

[S20] C：二分查找
来源：http://dali.gogol.net.cn/Article/details/gt2dfqlaeme.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.mhx1999.top/Article/details/gt2harkdnsf.html

[S21] C：字符类别判断
来源：http://dali.xylfe.cn/Article/details/gt2uaexobmm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fevpzdkn.html

[S22] C：字符串转数字
来源：http://dali.chenzaomai.com/Article/details/gt2ctxeberj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sysykeji.top/Article/details/gt2ekvccvxq.html

[S23] C：随机数
来源：http://dali.redwolf501.top/Article/details/gt2wfdssmrl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yongpay.top/Article/details/gt2fthfyrgs.html

[S24] C：获取本地时间
来源：http://dali.sufxvd.cn/Article/details/gt2lbfksarx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.daxiang520.top/Article/details/gt2jevijfza.html

[S25] C：内存拷贝
来源：http://dali.nanxinkj.top/Article/details/gt2raljdvip.html

memcpy(dst, src, n);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kralvhom.html

[S26] C：内存清零
来源：http://dali.316326.xyz/Article/details/gt2osxrsoef.html

memset(a, 0, sizeof a);
来源：http://dali.yj20258.top/Article/details/gt2wbonuhjy.html

[S27] C：定义常量
来源：http://dali.pengpengdd.cyou/Article/details/gt2dzzpglff.html

const double PI = 3.14159;
来源：http://dali.316326.xyz/Article/details/gt2bguyxofu.html

[S28] C：静态变量
来源：http://dali.wangdashe.top/Article/details/gt2jkplxofv.html

static int counter = 0;
来源：http://dali.pengpengdd.cyou/Article/details/gt2nrheulha.html

[S29] C：变参函数
来源：http://dali.jianghu66.top/Article/details/gt2ecapnbho.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.nanxinkj.top/Article/details/gt2zatrhnwi.html

[S30] C：头文件保护
来源：http://dali.guannengcc.top/Article/details/gt2ciuszybk.html

#ifndef X_H
来源：http://dali.daxiang520.top/Article/details/gt2vlivckdz.html

#define X_H
来源：http://dali.yonumen.top/Article/details/gt2zpsqhhts.html

#endif
来源：http://dali.gotoacloud.top/Article/details/gt2fzfajvcq.html

[S31] C++：Hello World
来源：http://dali.guowangkeji.top/Article/details/gt2dmvhuvkh.html

#include <iostream>
来源：http://dali.yonumen.top/Article/details/gt2saiikyso.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yvedp.cn/Article/details/gt2ogbjvved.html

[S32] C++：字符串
来源：http://dali.pycfn.com/Article/details/gt2xnpehvjj.html

std::string s = "hi";  s += "!";
来源：http://dali.fzhhl.top/Article/details/gt2asdihzzt.html

[S33] C++：vector 增删
来源：http://dali.yj20258.top/Article/details/gt2wggoaigj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ehwqpu.com/Article/details/gt2rndrypmx.html

[S34] C++：遍历 vector
来源：http://dali.quarkkingdee.top/Article/details/gt2iikqdfjp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.fzhhl.top/Article/details/gt2nyhupyyh.html

[S35] C++：map
来源：http://dali.xziqi.cn/Article/details/gt2tnubddug.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tian-w.cn/Article/details/gt2eocktbpu.html

[S36] C++：unordered_map
来源：http://dali.cashguo.top/Article/details/gt2uubhdddx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ehwqpu.com/Article/details/gt2agsryyrj.html

[S37] C++：set
来源：http://dali.guowangkeji.top/Article/details/gt2deskbbuv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.andypj.xyz/Article/details/gt2gakaacpj.html

[S38] C++：排序
来源：http://dali.cdnleiting.top/Article/details/gt2pwhsyvnn.html

std::sort(v.begin(), v.end());
来源：http://dali.zhiwuduotai.top/Article/details/gt2wdvafvmj.html

[S39] C++：自定义比较器排序
来源：http://dali.hnxiangtu.top/Article/details/gt2uusxmvhp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cashguo.top/Article/details/gt2yawfolxt.html

[S40] C++：查找元素
来源：http://dali.nanxuanxn.top/Article/details/gt2lnvduret.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cdnleiting.top/Article/details/gt2wxbtsqzm.html

[S41] C++：类与构造函数
来源：http://dali.zhengqikj.top/Article/details/gt2glxyxfvk.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.andypj.xyz/Article/details/gt2ksopwcoo.html

[S42] C++：继承与虚函数
来源：http://dali.pycfn.com/Article/details/gt2girwjxko.html

class B : public Base { public: void f() override {} };
来源：http://dali.aibaodan.cn/Article/details/gt2wojtjgfx.html

[S43] C++：智能指针
来源：http://dali.ydzc1.top/Article/details/gt2kwfbeoym.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinqigufen.top/Article/details/gt2toosesra.html

[S44] C++：引用传参
来源：http://dali.ydzc1.top/Article/details/gt2qttyixex.html

void inc(int &x) { ++x; }
来源：http://dali.meibo888.top/Article/details/gt2glrzeeay.html

[S45] C++：lambda
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nubkqjki.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.guowangkeji.top/Article/details/gt2dhrtgnkh.html

[S46] C++：函数模板
来源：http://dali.yonumen.top/Article/details/gt2nzenauoz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yj20258888.top/Article/details/gt2fmswxiue.html

[S47] C++：结构化绑定遍历
来源：http://dali.shzxlz.cn/Article/details/gt2tvjfacbx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jyoumei.cn/Article/details/gt2fzkkxzgm.html

[S48] C++：逐行读文件
来源：http://dali.ybcxt.top/Article/details/gt2rqznugzc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cucudq.cn/Article/details/gt2bjtkhhjm.html

while (std::getline(in, line)) { }
来源：http://dali.redwolf501.top/Article/details/gt2qklqvscx.html

[S49] C++：写文件
来源：http://dali.wangdashe.top/Article/details/gt2hyeaivmb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fuvhqiez.html

[S50] C++：格式化数字
来源：http://dali.jqgfzy.top/Article/details/gt2mczpeghd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2pxhrnvtw.html

[S51] C++：显式类型转换
来源：http://dali.ybcxt.top/Article/details/gt2fiwfxdls.html

static_cast<double>(a) / b
来源：http://dali.havefunace.top/Article/details/gt2aoavsxiq.html

[S52] C++：const 与 noexcept
来源：http://dali.gaohongyu789.top/Article/details/gt2uzpzdlef.html

int size() const noexcept { return n_; }
来源：http://dali.guowangkeji.top/Article/details/gt2mzndcepa.html

[S53] C++：移动语义
来源：http://dali.hongshengwenyu.top/Article/details/gt2xkvlcltm.html

std::vector<int> w = std::move(v);
来源：http://dali.iojbl.cn/Article/details/gt2bxviynud.html

[S54] C++：异常处理
来源：http://dali.nanxuanxn.top/Article/details/gt2rwydcckp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.aizwys.cn/Article/details/gt2vynjotmj.html

[S55] C++：结构化绑定
来源：http://dali.guannengcc.top/Article/details/gt2gwjeibwp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.quarkkingdee.top/Article/details/gt2kprvvepd.html

[S56] C++：optional
来源：http://dali.aizwys.cn/Article/details/gt2odhbzsyz.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.dianchejie.cn/Article/details/gt2lghenpqx.html

[S57] C++：编译期常量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wddpsqww.html

constexpr int N = 10;
来源：http://dali.yangfankeji.com/Article/details/gt2nwstlrfk.html

[S58] C++：命名空间
来源：http://dali.jinqigfzy.top/Article/details/gt2pgdhbbrc.html

namespace ns { int f() { return 1; } }
来源：http://dali.vqdsnc.cn/Article/details/gt2kvexipfc.html

[S59] C++：静态断言
来源：http://dali.zycfv.cn/Article/details/gt2etxpmsqx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhixingplan.top/Article/details/gt2bcrajoty.html

[S60] C++：遍历并删除元素
来源：http://dali.yongpay.top/Article/details/gt2uczyuzee.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.hysaishi.cn/Article/details/gt2jqeebnpu.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2bflvmmaa.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hnxiangtu.top/Article/details/gt2wljjzzfk.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gt2mfqwmncv.html

[T01] Kotlin：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gt2xhnhjilf.html

println("Hello")
来源：http://dali.shanyushiyangtech.top/Article/details/gt2heszohmz.html

[T02] Kotlin：变量
来源：http://dali.gzhubu.top/Article/details/gt2zlnzhvrr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yongpay.top/Article/details/gt2rktkvihi.html

[T03] Kotlin：字符串模板
来源：http://dali.havefunace.top/Article/details/gt2aqswrpdg.html

"值: $b"
来源：http://dali.guowangkeji.top/Article/details/gt2wrchaftl.html

[T04] Kotlin：空安全
来源：http://dali.ppjwa.cn/Article/details/gt2qhvkqvii.html

val n: String? = null;  n?.length
来源：http://dali.ydzc1.top/Article/details/gt2tqxkkani.html

[T05] Kotlin：when 表达式
来源：http://dali.yueranfly.top/Article/details/gt2tziayltl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ywyebsgr.html

[T06] Kotlin：集合映射
来源：http://dali.havefunace.top/Article/details/gt2aqvbwjeq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gt2oqdrbfjp.html

[T07] Kotlin：集合过滤
来源：http://dali.hnqzz.top/Article/details/gt2oxrcrweq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shangyingyoupin.top/Article/details/gt2nnewzvvj.html

[T08] Kotlin：数据类
来源：http://dali.xuanzx.com/Article/details/gt2vozxited.html

data class User(val name: String, val age: Int)
来源：http://dali.gogol.net.cn/Article/details/gt2qftbgpqc.html

[T09] Kotlin：扩展函数
来源：http://dali.yuanzhike.top/Article/details/gt2nnrmmvnf.html

fun String.exclaim() = this + "!"
来源：http://dali.jqgfzy.top/Article/details/gt2iqwpwxfa.html

[T10] Kotlin：默认参数
来源：http://dali.hnqzz.top/Article/details/gt2xonjknpj.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.mhx1999.top/Article/details/gt2cyfzjdcn.html

[T11] Kotlin：协程
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ycqetexp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nyfeulib.html

[T12] Kotlin：解构声明
来源：http://dali.gogol.net.cn/Article/details/gt2fvnzbxmg.html

val (a, b) = Pair(1, 2)
来源：http://dali.jyoumei.cn/Article/details/gt2ssihyjae.html

[T13] Kotlin：只读 Map
来源：http://dali.yuxming.cn/Article/details/gt2vliesxac.html

val m = mapOf("a" to 1)
来源：http://dali.shangyingyoupin.top/Article/details/gt2hzpolosy.html

[T14] Kotlin：循环
来源：http://dali.yj20258888.top/Article/details/gt2alrkwulq.html

for (i in 1..10) println(i)
来源：http://dali.yj20258.top/Article/details/gt2dicvxrmi.html

[T15] Kotlin：接口
来源：http://dali.guannengcc.top/Article/details/gt2ymnotypm.html

interface Shape { fun area(): Double }
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vnpgpggo.html

[T16] Swift：Hello World
来源：http://dali.wangdashe.top/Article/details/gt2mvuzejvz.html

print("Hello")
来源：http://dali.ybcxt.top/Article/details/gt2ymgnmlgr.html

[T17] Swift：变量与常量
来源：http://dali.pengpengdd.cyou/Article/details/gt2lznfkdyh.html

var a = 1;  let b = 2
来源：http://dali.hongshengwenyu.top/Article/details/gt2lrshqmfe.html

[T18] Swift：字符串插值
来源：http://dali.fengsongda.top/Article/details/gt2demcbhjg.html

"值: \(b)"
来源：http://dali.nanxinkj.top/Article/details/gt2eoclfazz.html

[T19] Swift：可选绑定
来源：http://dali.yj202588.top/Article/details/gt2ahgsfbju.html

if let n = opt { print(n) }
来源：http://dali.cqqwz.cn/Article/details/gt2loosrtqg.html

[T20] Swift：数组操作
来源：http://dali.0kj1m.cn/Article/details/gt2djzmahbr.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hysaishi.cn/Article/details/gt2eyngdyac.html

[T21] Swift：遍历
来源：http://dali.hywenlv.cn/Article/details/gt2yogzavxw.html

for x in a { print(x) }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ylesftig.html

[T22] Swift：字典
来源：http://dali.ppjwa.cn/Article/details/gt2tyulkohh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.mhx1999.top/Article/details/gt2mymdrmih.html

[T23] Swift：函数
来源：http://dali.cheryme.top/Article/details/gt2yrnhgwur.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.daria6918.cn/Article/details/gt2ngqmdcey.html

[T24] Swift：闭包
来源：http://dali.andypj.xyz/Article/details/gt2ccifbutq.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.tianlin.xyz/Article/details/gt2qqpsiuhm.html

[T25] Swift：结构体
来源：http://dali.tian-w.cn/Article/details/gt2uklvubcm.html

struct P { var x: Int }
来源：http://dali.bjfxy.top/Article/details/gt2gohhcjxw.html

[T26] Swift：类与重写
来源：http://dali.wangshuangyany.cn/Article/details/gt2zxrjhhjp.html

class A: Base { override func f() {} }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cvsacnyf.html

[T27] Swift：错误处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gdwzrtpz.html

do { try f() } catch { print(error) }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ldhmzztn.html

[T28] Swift：枚举
来源：http://dali.daria6918.cn/Article/details/gt2ylmrlzeu.html

enum Color { case red, green }
来源：http://dali.shangyingyoupin.top/Article/details/gt2nrpxbtly.html

[T29] Swift：guard 提前返回
来源：http://dali.ivvv.top/Article/details/gt2jiknqexe.html

guard let x = opt else { return }
来源：http://dali.jqgfzy.top/Article/details/gt2qpyaxxao.html

[T30] Swift：协议
来源：http://dali.cashguo.top/Article/details/gt2wmfmnamv.html

protocol Shape { func area() -> Double }
来源：http://dali.yj20258.top/Article/details/gt2mkppmuea.html

[T31] Lua：Hello World
来源：http://dali.yonumen.top/Article/details/gt2kbzpqrnx.html

print("Hello")
来源：http://dali.yvedp.cn/Article/details/gt2mpwcqfrl.html

[T32] Lua：局部变量
来源：http://dali.tanke756.top/Article/details/gt2ddbvnusw.html

local a = 1
来源：http://dali.haohaochexian.top/Article/details/gt2yzqhtdph.html

[T33] Lua：表（数组）
来源：http://dali.jiagoushi.top/Article/details/gt2vcviunmj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.aizwys.cn/Article/details/gt2kwaluitz.html

[T34] Lua：遍历表
来源：http://dali.zhiwuduotai.top/Article/details/gt2alhvzvjr.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xziqi.cn/Article/details/gt2umtprsgm.html

[T35] Lua：字典表
来源：http://dali.shuidangran.top/Article/details/gt2agtrgzcv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shzxlz.cn/Article/details/gt2khvqggas.html

[T36] Lua：函数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ienhjvdn.html

function add(a, b) return a + b end
来源：http://dali.aibaodan.cn/Article/details/gt2ixjkmorn.html

[T37] Lua：字符串拼接
来源：http://dali.tian-w.cn/Article/details/gt2gxarkxqb.html

"a" .. "b"
来源：http://dali.vqdsnc.cn/Article/details/gt2mbbqmsvp.html

[T38] Lua：条件
来源：http://dali.haohaochexian.top/Article/details/gt2agbtsoqm.html

if x > 0 then print("正") end
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nvmbgqna.html

[T39] Lua：模式匹配
来源：http://dali.jqgfzy.top/Article/details/gt2zivyqjtg.html

string.find(s, "%d+")
来源：http://dali.chenlongwang.top/Article/details/gt2jttwdryp.html

[T40] Lua：元表
来源：http://dali.jqgfzy.top/Article/details/gt2gzzfwxby.html

setmetatable({}, { __index = base })
来源：http://dali.jyoumei.cn/Article/details/gt2ftalrslu.html

[T41] Perl：Hello World
来源：http://dali.fengsongda.top/Article/details/gt2usouyuwt.html

print "Hello\n";
来源：http://dali.jinqigfzy.top/Article/details/gt2feqbqmyb.html

[T42] Perl：变量类型
来源：http://dali.yangfankeji.com/Article/details/gt2ewizcohz.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.havefunace.top/Article/details/gt2kucryaxd.html

[T43] Perl：字符串插值
来源：http://dali.cashguo.top/Article/details/gt2pihveyhx.html

"值: $a"
来源：http://dali.9152youxi.cn/Article/details/gt2vddbzkia.html

[T44] Perl：条件
来源：http://dali.zhoulong.xyz/Article/details/gt2jgtqxbey.html

if ($a > 0) { print "正"; }
来源：http://dali.hfpthk.cn/Article/details/gt2unuhiqjg.html

[T45] Perl：数组遍历
来源：http://dali.yangfankeji.com/Article/details/gt2eoevipbo.html

for my $x (@arr) { print $x; }
来源：http://dali.ehwqpu.com/Article/details/gt2ylkgdmge.html

[T46] Perl：哈希操作
来源：http://dali.jyoumei.cn/Article/details/gt2feibpvju.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yj202588.top/Article/details/gt2mwvgbcyy.html

[T47] Perl：正则捕获
来源：http://dali.zhongyouzk.top/Article/details/gt2arwmsiop.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yj20258888.top/Article/details/gt2oouwucdt.html

[T48] Perl：正则替换
来源：http://dali.yuanzhike.top/Article/details/gt2pdaqoumv.html

$s =~ s/old/new/g;
来源：http://dali.zhixingplan.top/Article/details/gt2ollaxydf.html

[T49] Perl：函数
来源：http://dali.yanxiufei.cn/Article/details/gt2jnslpfjl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xinyue.icu/Article/details/gt2dfgdvdmk.html

[T50] Perl：逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gt2dfhvbvhc.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.hnqzz.top/Article/details/gt2rovbfozn.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.havefunace.top/Article/details/gt2djbazkem.html

[T51] Scala：Hello World
来源：http://dali.hysaishi.cn/Article/details/gt2gbuecdjg.html

println("Hello")
来源：http://dali.ppjwa.cn/Article/details/gt2ioumzfmk.html

[T52] Scala：变量
来源：http://dali.gzhubu.top/Article/details/gt2tvvvxsvg.html

val a = 1;  var b = 2
来源：http://dali.fzhhl.top/Article/details/gt2dqnzkaow.html

[T53] Scala：字符串插值
来源：http://dali.guowangkeji.top/Article/details/gt2ramdbjvx.html

s"值: $b"
来源：http://dali.birdmap.top/Article/details/gt2zzofdteg.html

[T54] Scala：集合映射
来源：http://dali.ivvv.top/Article/details/gt2vxlxsrkq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mipbgzlr.html

[T55] Scala：集合过滤
来源：http://dali.aibaodan.cn/Article/details/gt2vfjmwxsl.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.sufxvd.cn/Article/details/gt2myexxdjv.html

[T56] Scala：样例类
来源：http://dali.dianchejie.cn/Article/details/gt2vhygcvzf.html

case class User(name: String, age: Int)
来源：http://dali.gzhubu.top/Article/details/gt2spnattlz.html

[T57] Scala：模式匹配
来源：http://dali.cashguo.top/Article/details/gt2fevrvrvf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.kuanghao11.cn/Article/details/gt2vrpparku.html

[T58] Scala：函数定义
来源：http://dali.dianchejie.cn/Article/details/gt2egmcxebc.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cqqwz.cn/Article/details/gt2npjvlcva.html

[T59] Scala：循环
来源：http://dali.yj202588.top/Article/details/gt2agomwfeb.html

for (i <- 1 to 10) println(i)
来源：http://dali.guowangkeji.top/Article/details/gt2ehkkfuup.html

[T60] Scala：折叠
来源：http://dali.shuidangran.top/Article/details/gt2ikdrgwbm.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sjxeggha.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2guhwjufk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yanxiufei.cn/Article/details/gt2kjjyeige.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gt2czskkdov.html

[U01] Py：创建虚拟环境
来源：http://dali.dashuyun.cn/Article/details/gt2fhhbnikv.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.daria6918.cn/Article/details/gt2epvkzkal.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zycfv.cn/Article/details/gt2pktgebfe.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.birdmap.top/Article/details/gt2zkrjwrju.html

[U03] Py：加载 .env 配置
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jqrgbgtj.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jianghu66.top/Article/details/gt2cmjzxocm.html

[U04] Py：变量调试打印
来源：http://dali.smart0.xyz/Article/details/gt2lefmyarq.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.hongshengwenyu.top/Article/details/gt2dqevhebs.html

[U05] Py：列表去重且保序
来源：http://dali.9152youxi.cn/Article/details/gt2jspimbsb.html

list(dict.fromkeys(arr))
来源：http://dali.chenjidiqi.icu/Article/details/gt2icgnarcz.html

[U06] Py：合并两个字典
来源：http://dali.yvedp.cn/Article/details/gt2zdixebqj.html

{**a, **b}
来源：http://dali.jlsjyb.cn/Article/details/gt2gyprflod.html

[U07] Py：反转字典键值
来源：http://dali.zhiwuduotai.top/Article/details/gt2aanflqcg.html

{v: k for k, v in d.items()}
来源：http://dali.feifeiyinyue.top/Article/details/gt2dayfmvod.html

[U08] Py：展平二维列表
来源：http://dali.hongshengwenyu.top/Article/details/gt2nxywvbym.html

[y for x in nested for y in x]
来源：http://dali.hnqzz.top/Article/details/gt2ynodiqvt.html


<!-- 参考信息 -->