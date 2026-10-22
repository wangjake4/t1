代发 wailian999

openssl rand -hex 16
来源：http://dali.yangfankeji.com/Article/details/gtbipnvoan.html

[R68] 计算文件校验值
来源：http://dali.daria6918.cn/Article/details/gtpoxuddgz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ehwqpu.com/Article/details/gtouyrxycl.html

[R69] 生成随机密码
来源：http://dali.jinyuanbaomall.cn/Article/details/gttyypacup.html

head -c 16 /dev/urandom | base64
来源：http://dali.ppjwa.cn/Article/details/gtbiqkoolt.html

[R70] 时间戳与互转
来源：http://dali.zycfv.cn/Article/details/gtmkwkxstn.html

date +%s;  date -d @1700000000
来源：http://dali.xylfe.cn/Article/details/gtrqklovdu.html

[R71] 日期格式化
来源：http://dali.cheryme.top/Article/details/gtcsuvidak.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.dianchejie.cn/Article/details/gtoqwznkdz.html

[R72] 等待端口就绪
来源：http://dali.jinghuilouyu.cn/Article/details/gtnqczrksi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.c1oappe.top/Article/details/gtfebmwvoq.html

[R73] 分割大日志
来源：http://dali.9152youxi.cn/Article/details/gtdnpparzy.html

split -l 1000 big.log part_
来源：http://dali.zycfv.cn/Article/details/gtohrwawav.html

[R74] 批量重命名
来源：http://dali.dashuyun.cn/Article/details/gtlrujcotl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nanxuanxn.top/Article/details/gtznwhabkl.html

[R75] 导出环境变量
来源：http://dali.shangyingyoupin.top/Article/details/gtgkwvbtmk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhixingplan.top/Article/details/gtpbvgdmtw.html

[R76] 使用临时文件
来源：http://dali.gotoacloud.top/Article/details/gtgwhacija.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinyuanbaomall.cn/Article/details/gtculeulgp.html

[R77] 读取用户输入
来源：http://dali.tian-w.cn/Article/details/gtqwvqfgiu.html

read -rp "请输入: " ans
来源：http://dali.birdmap.top/Article/details/gtqmzozype.html

[R78] 交互式菜单
来源：http://dali.zhoulong.xyz/Article/details/gtotygewmc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhongyouzk.top/Article/details/gtipgyibhi.html

[R79] 解析命令行选项
来源：http://dali.zhiwuduotai.top/Article/details/gtxtvsrqai.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlxmsvlcl.html

[R80] 查看脚本执行耗时
来源：http://dali.hysaishi.cn/Article/details/gtfywjnota.html

time ./run.sh
来源：http://dali.yueranfly.top/Article/details/gtaeaovzne.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtpgahkpwo.html

S. C / C++ 专题
来源：http://dali.shangyingyoupin.top/Article/details/gtpykwouap.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtwtkwwlvd.html

[S01] C：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtucjydunz.html

#include <stdio.h>
来源：http://dali.hfpthk.cn/Article/details/gtzrihzlgv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ehwqpu.com/Article/details/gtaluaahwb.html

[S02] C：变量与格式化输出
来源：http://dali.aizwys.cn/Article/details/gtrkjgczxt.html

int a = 10; printf("%d\n", a);
来源：http://dali.yj202588.top/Article/details/gtdgegtgqt.html

[S03] C：读入整数
来源：http://dali.hfpthk.cn/Article/details/gtcimtnsbh.html

int x; scanf("%d", &x);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlxbaweyr.html

[S04] C：字符串复制
来源：http://dali.redwolf501.top/Article/details/gtlhwoxqci.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cheryme.top/Article/details/gtyloocxls.html

[S05] C：字符串长度
来源：http://dali.hywenlv.cn/Article/details/gtruxvojab.html

strlen(s)
来源：http://dali.daria6918.cn/Article/details/gtajgvueik.html

[S06] C：字符串比较
来源：http://dali.zhiwuduotai.top/Article/details/gtgdkukukt.html

strcmp(a, b) == 0
来源：http://dali.cheryme.top/Article/details/gtedvdczbp.html

[S07] C：数组遍历求和
来源：http://dali.jinyuanbaomall.cn/Article/details/gtywpmeimd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhoulong.xyz/Article/details/gtemqpnfmo.html

[S08] C：动态内存分配与释放
来源：http://dali.jinqigfzy.top/Article/details/gtbnjgkwin.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ydzc1.top/Article/details/gtrwwwlhqf.html

[S09] C：结构体定义与初始化
来源：http://dali.nanxuanxn.top/Article/details/gtyarxogfy.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.dashuyun.cn/Article/details/gtklajudxs.html

[S10] C：指针与解引用
来源：http://dali.zhoulong.xyz/Article/details/gtuunbtwup.html

int *p = &a;  *p = 5;
来源：http://dali.zycfv.cn/Article/details/gtvltzsxhf.html

[S11] C：逐行读文件
来源：http://dali.fengsongda.top/Article/details/gtiluznptd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlkknppoh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jianghu66.top/Article/details/gtfbejnzjt.html

fclose(f);
来源：http://dali.sxryk.cn/Article/details/gtrkljvkjk.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gtqougbzgn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.hnxiangtu.top/Article/details/gtvevtjgyv.html

[S13] C：宏定义
来源：http://dali.yonumen.top/Article/details/gtpwqlojdh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yj20258.top/Article/details/gtobpljyfo.html

[S14] C：枚举
来源：http://dali.shanyushiyangtech.top/Article/details/gtchdkhnkm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.andypj.xyz/Article/details/gtqmyxbxnn.html

[S15] C：类型转换
来源：http://dali.shuidangran.top/Article/details/gtulmplaiz.html

(double) a / b
来源：http://dali.hongshengwenyu.top/Article/details/gtluqimntq.html

[S16] C：位操作置位
来源：http://dali.iojbl.cn/Article/details/gthzrrjqjh.html

x |= (1 << 3);
来源：http://dali.jinqigufen.top/Article/details/gtkrsglikl.html

[S17] C：安全拼接字符串
来源：http://dali.cheryme.top/Article/details/gtosnkodtd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.daxiang520.top/Article/details/gtmazyctnq.html

[S18] C：命令行参数
来源：http://dali.jinqigfzy.top/Article/details/gtynojwwsk.html

int main(int argc, char **argv)
来源：http://dali.svipenyu.cn/Article/details/gtzehvzqda.html

[S19] C：快速排序
来源：http://dali.dianchejie.cn/Article/details/gtwjesztpa.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jqgfzy.top/Article/details/gtieuomyte.html

[S20] C：二分查找
来源：http://dali.aibaodan.cn/Article/details/gtvqmisqez.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gtmeddlsve.html

[S21] C：字符类别判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtntsiquwd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.tanke756.top/Article/details/gtebrncdpo.html

[S22] C：字符串转数字
来源：http://dali.pycfn.com/Article/details/gtwiadlbrg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhiwuduotai.top/Article/details/gtteczaemd.html

[S23] C：随机数
来源：http://dali.fengsongda.top/Article/details/gtrojdnaco.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.c1oappe.top/Article/details/gtqkithyjs.html

[S24] C：获取本地时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gterntucut.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jqgufenzy.top/Article/details/gtyvgrersc.html

[S25] C：内存拷贝
来源：http://dali.jinyuanbaomall.cn/Article/details/gttlgvvkxh.html

memcpy(dst, src, n);
来源：http://dali.quarkkingdee.top/Article/details/gthcrcztqq.html

[S26] C：内存清零
来源：http://dali.zycfv.cn/Article/details/gtwmvknfzk.html

memset(a, 0, sizeof a);
来源：http://dali.jinqigufen.top/Article/details/gtexajgvxq.html

[S27] C：定义常量
来源：http://dali.hammf.cn/Article/details/gteoectvqk.html

const double PI = 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gtsrdpygqq.html

[S28] C：静态变量
来源：http://dali.yueranfly.top/Article/details/gtmrzpsziy.html

static int counter = 0;
来源：http://dali.gaohongyu789.top/Article/details/gtslvhtdam.html

[S29] C：变参函数
来源：http://dali.fzhhl.top/Article/details/gtgyiykdtc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yongpay.top/Article/details/gtnhyxasks.html

[S30] C：头文件保护
来源：http://dali.shuidangran.top/Article/details/gtdigbqqjj.html

#ifndef X_H
来源：http://dali.wangshuangyany.cn/Article/details/gtvlahbfnf.html

#define X_H
来源：http://dali.hnxiangtu.top/Article/details/gtnyawpeqt.html

#endif
来源：http://dali.yuxming.cn/Article/details/gtvbsivzjq.html

[S31] C++：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtxebacxjn.html

#include <iostream>
来源：http://dali.ppjwa.cn/Article/details/gtqkevtusv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yj20258.top/Article/details/gteamgywvu.html

[S32] C++：字符串
来源：http://dali.pycfn.com/Article/details/gtmdgjbheu.html

std::string s = "hi";  s += "!";
来源：http://dali.chenzaomai.com/Article/details/gtpdvrylop.html

[S33] C++：vector 增删
来源：http://dali.wangshuangyany.cn/Article/details/gtbpwgcqmv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.0kj1m.cn/Article/details/gtqorposag.html

[S34] C++：遍历 vector
来源：http://dali.cheryme.top/Article/details/gtncldwsoe.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.tanke756.top/Article/details/gtjrpzgfai.html

[S35] C++：map
来源：http://dali.daria6918.cn/Article/details/gtoevjgofb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tanke756.top/Article/details/gtrazlijlq.html

[S36] C++：unordered_map
来源：http://dali.ydzc1.top/Article/details/gtkizrdjpw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlxvwdpzi.html

[S37] C++：set
来源：http://dali.sysykeji.top/Article/details/gtdrcqbiux.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ehwqpu.com/Article/details/gtmfamypvx.html

[S38] C++：排序
来源：http://dali.sweek.top/Article/details/gtxdwfxyga.html

std::sort(v.begin(), v.end());
来源：http://dali.shanyushiyangtech.top/Article/details/gtgkwfeuur.html

[S39] C++：自定义比较器排序
来源：http://dali.meibo888.top/Article/details/gtrpobqzaa.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hnqzz.top/Article/details/gtqdpeiwdw.html

[S40] C++：查找元素
来源：http://dali.jianghu66.top/Article/details/gtkghoymdb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yj20258.top/Article/details/gtjnmcmyhg.html

[S41] C++：类与构造函数
来源：http://dali.cashguo.top/Article/details/gtuawyzqux.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjawxzeed.html

[S42] C++：继承与虚函数
来源：http://dali.ivvv.top/Article/details/gtleduxacb.html

class B : public Base { public: void f() override {} };
来源：http://dali.jyoumei.cn/Article/details/gtrakbgmfe.html

[S43] C++：智能指针
来源：http://dali.dianchejie.cn/Article/details/gtanqyxgij.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhoulong.xyz/Article/details/gttgdpiwxv.html

[S44] C++：引用传参
来源：http://dali.zdqjudy.top/Article/details/gtppwzyqcs.html

void inc(int &x) { ++x; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvkuudxcp.html

[S45] C++：lambda
来源：http://dali.tianlin.xyz/Article/details/gtkwuiwojp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shzxlz.cn/Article/details/gtwlfwxlvv.html

[S46] C++：函数模板
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthnhpcjzk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtpgusutby.html

[S47] C++：结构化绑定遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgvkovlbn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.feifeiyinyue.top/Article/details/gtshjlweow.html

[S48] C++：逐行读文件
来源：http://dali.shuidangran.top/Article/details/gtdkfnmblp.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.aibaodan.cn/Article/details/gtgyxiyowk.html

while (std::getline(in, line)) { }
来源：http://dali.hnxiangtu.top/Article/details/gtitjpnwdu.html

[S49] C++：写文件
来源：http://dali.0kj1m.cn/Article/details/gtuuxjofib.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yangfankeji.com/Article/details/gtkwdpvhof.html

[S50] C++：格式化数字
来源：http://dali.meibo888.top/Article/details/gtekyynntj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ivvv.top/Article/details/gtmtzgubfc.html

[S51] C++：显式类型转换
来源：http://dali.yangfankeji.com/Article/details/gtalcenbsj.html

static_cast<double>(a) / b
来源：http://dali.chenlongwang.top/Article/details/gtafocsvmx.html

[S52] C++：const 与 noexcept
来源：http://dali.dashuyun.cn/Article/details/gtobaujyqh.html

int size() const noexcept { return n_; }
来源：http://dali.birdmap.top/Article/details/gtyhzyaeia.html

[S53] C++：移动语义
来源：http://dali.sxryk.cn/Article/details/gtlozffpkc.html

std::vector<int> w = std::move(v);
来源：http://dali.bjfxy.top/Article/details/gtfrreysjb.html

[S54] C++：异常处理
来源：http://dali.wangshuangyany.cn/Article/details/gtjaggbixd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.wangdashe.top/Article/details/gtcgagbnwy.html

[S55] C++：结构化绑定
来源：http://dali.pengpengdd.cyou/Article/details/gtsspjyegt.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.feifeiyinyue.top/Article/details/gtoffqwyvq.html

[S56] C++：optional
来源：http://dali.9152youxi.cn/Article/details/gtvxyqaycm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yonumen.top/Article/details/gtjasgaicv.html

[S57] C++：编译期常量
来源：http://dali.ehwqpu.com/Article/details/gtubugbacr.html

constexpr int N = 10;
来源：http://dali.snrcjt.cn/Article/details/gtkvfqtmlk.html

[S58] C++：命名空间
来源：http://dali.ehwqpu.com/Article/details/gtnpavmmfb.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhixingplan.top/Article/details/gtidciumrc.html

[S59] C++：静态断言
来源：http://dali.xylfe.cn/Article/details/gtlviyfsvl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sufxvd.cn/Article/details/gtkzyuzopr.html

[S60] C++：遍历并删除元素
来源：http://dali.yongpay.top/Article/details/gtyyywkjrc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gaohongyu789.top/Article/details/gteoyzwhst.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtholtrvhv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhengqikj.top/Article/details/gtnrzfichh.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtkdohpwmd.html

[T01] Kotlin：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gttqrpfcdr.html

println("Hello")
来源：http://dali.chenzaomai.com/Article/details/gthaitmwoy.html

[T02] Kotlin：变量
来源：http://dali.snrcjt.cn/Article/details/gtnckitkwy.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.andypj.xyz/Article/details/gtczljbkwi.html

[T03] Kotlin：字符串模板
来源：http://dali.cashguo.top/Article/details/gtbufdzdvv.html

"值: $b"
来源：http://dali.yj202588.top/Article/details/gtfdkzbfis.html

[T04] Kotlin：空安全
来源：http://dali.redwolf501.top/Article/details/gtvkfyjxmk.html

val n: String? = null;  n?.length
来源：http://dali.birdmap.top/Article/details/gtdbhsmshy.html

[T05] Kotlin：when 表达式
来源：http://dali.yongpay.top/Article/details/gtbndyusuu.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zdqjudy.top/Article/details/gtiwaxbbpl.html

[T06] Kotlin：集合映射
来源：http://dali.jinqigufen.top/Article/details/gtcfqhkvxa.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.chenzaomai.com/Article/details/gtxtqhrbvw.html

[T07] Kotlin：集合过滤
来源：http://dali.nanxuanxn.top/Article/details/gtlseycjzr.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sxryk.cn/Article/details/gtsomhznhy.html

[T08] Kotlin：数据类
来源：http://dali.yj202588.top/Article/details/gtjhflvydl.html

data class User(val name: String, val age: Int)
来源：http://dali.andypj.xyz/Article/details/gtdlhjhkzs.html

[T09] Kotlin：扩展函数
来源：http://dali.0kj1m.cn/Article/details/gtzwlzccpr.html

fun String.exclaim() = this + "!"
来源：http://dali.chenjidiqi.icu/Article/details/gtnbqaxyyo.html

[T10] Kotlin：默认参数
来源：http://dali.chenlongwang.top/Article/details/gtygxtjuht.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hnxiangtu.top/Article/details/gtkdvbdiyk.html

[T11] Kotlin：协程
来源：http://dali.yj20258888.top/Article/details/gtpqvpughz.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpnignteu.html

[T12] Kotlin：解构声明
来源：http://dali.316326.xyz/Article/details/gtzapdojaz.html

val (a, b) = Pair(1, 2)
来源：http://dali.sufxvd.cn/Article/details/gtmdrpkksg.html

[T13] Kotlin：只读 Map
来源：http://dali.yanxiufei.cn/Article/details/gtamqvuary.html

val m = mapOf("a" to 1)
来源：http://dali.c1oappe.top/Article/details/gtzwlpxbuj.html

[T14] Kotlin：循环
来源：http://dali.jinqigfzy.top/Article/details/gtmokyzvas.html

for (i in 1..10) println(i)
来源：http://dali.nanxuanxn.top/Article/details/gtfsdewncj.html

[T15] Kotlin：接口
来源：http://dali.jlsjyb.cn/Article/details/gtmkpjvznx.html

interface Shape { fun area(): Double }
来源：http://dali.jiagoushi.top/Article/details/gtjyxmhlsh.html

[T16] Swift：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gtjiifzqlb.html

print("Hello")
来源：http://dali.cashguo.top/Article/details/gtbwyscrrb.html

[T17] Swift：变量与常量
来源：http://dali.ppjwa.cn/Article/details/gterlrczlo.html

var a = 1;  let b = 2
来源：http://dali.guowangkeji.top/Article/details/gtgkrrseym.html

[T18] Swift：字符串插值
来源：http://dali.chenzaomai.com/Article/details/gtwrvrzrfx.html

"值: \(b)"
来源：http://dali.shanyushiyangtech.top/Article/details/gtaszunbsd.html

[T19] Swift：可选绑定
来源：http://dali.tian-w.cn/Article/details/gtlgwnlmqb.html

if let n = opt { print(n) }
来源：http://dali.chenzaomai.com/Article/details/gtchczxazv.html

[T20] Swift：数组操作
来源：http://dali.feifeiyinyue.top/Article/details/gtsttqtfpy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.kuanghao11.cn/Article/details/gtuqdhuxbu.html

[T21] Swift：遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtltknejdb.html

for x in a { print(x) }
来源：http://dali.hfpthk.cn/Article/details/gtvbeahjut.html

[T22] Swift：字典
来源：http://dali.0kj1m.cn/Article/details/gtzwdzukcq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.fzhhl.top/Article/details/gtjxfbbocz.html

[T23] Swift：函数
来源：http://dali.birdmap.top/Article/details/gtkpkanbri.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yueranfly.top/Article/details/gtqrsmjpay.html

[T24] Swift：闭包
来源：http://dali.jinghuilouyu.cn/Article/details/gtmfwyflnw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.quarkkingdee.top/Article/details/gtgxjlovzk.html

[T25] Swift：结构体
来源：http://dali.andypj.xyz/Article/details/gteylobdav.html

struct P { var x: Int }
来源：http://dali.jlsjyb.cn/Article/details/gtnzkvngbj.html

[T26] Swift：类与重写
来源：http://dali.andypj.xyz/Article/details/gtpbvouoab.html

class A: Base { override func f() {} }
来源：http://dali.xuanzx.com/Article/details/gtahkgblkj.html

[T27] Swift：错误处理
来源：http://dali.haohaochexian.top/Article/details/gtldbolvbx.html

do { try f() } catch { print(error) }
来源：http://dali.sxryk.cn/Article/details/gtaxeevtlr.html

[T28] Swift：枚举
来源：http://dali.xziqi.cn/Article/details/gtdjkjtlrr.html

enum Color { case red, green }
来源：http://dali.zhengqikj.top/Article/details/gtudrngpyq.html

[T29] Swift：guard 提前返回
来源：http://dali.gaohongyu789.top/Article/details/gtdqqwgsvg.html

guard let x = opt else { return }
来源：http://dali.hongshengwenyu.top/Article/details/gtcqsghmut.html

[T30] Swift：协议
来源：http://dali.sufxvd.cn/Article/details/gtidfdzhvl.html

protocol Shape { func area() -> Double }
来源：http://dali.yj20258888.top/Article/details/gtaavrnuor.html

[T31] Lua：Hello World
来源：http://dali.gzhubu.top/Article/details/gttumwuwbw.html

print("Hello")
来源：http://dali.bjfxy.top/Article/details/gtddprdelk.html

[T32] Lua：局部变量
来源：http://dali.ivvv.top/Article/details/gtnhxruzaf.html

local a = 1
来源：http://dali.xinyue.icu/Article/details/gtnwnwvkdr.html

[T33] Lua：表（数组）
来源：http://dali.hammf.cn/Article/details/gtubewznga.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.tianlin.xyz/Article/details/gtpxbsqbri.html

[T34] Lua：遍历表
来源：http://dali.jlsjyb.cn/Article/details/gtyywlumbh.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.wangdashe.top/Article/details/gtcgsuwnaj.html

[T35] Lua：字典表
来源：http://dali.xinyue.icu/Article/details/gtnlocewbm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.fzhhl.top/Article/details/gtdgfsgozj.html

[T36] Lua：函数
来源：http://dali.meibo888.top/Article/details/gtwvzipxfj.html

function add(a, b) return a + b end
来源：http://dali.9152youxi.cn/Article/details/gtlbouccys.html

[T37] Lua：字符串拼接
来源：http://dali.iojbl.cn/Article/details/gtpkfsbmuj.html

"a" .. "b"
来源：http://dali.pengpengdd.cyou/Article/details/gtikezhwjs.html

[T38] Lua：条件
来源：http://dali.ybcxt.top/Article/details/gtfakjqfud.html

if x > 0 then print("正") end
来源：http://dali.yj20258888.top/Article/details/gtuwsxrtnw.html

[T39] Lua：模式匹配
来源：http://dali.hammf.cn/Article/details/gttuueagxt.html

string.find(s, "%d+")
来源：http://dali.cdnleiting.top/Article/details/gtsivkbcad.html

[T40] Lua：元表
来源：http://dali.quarkkingdee.top/Article/details/gtbprahxyd.html

setmetatable({}, { __index = base })
来源：http://dali.haohaochexian.top/Article/details/gtoagfyjww.html

[T41] Perl：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtqqwxqllg.html

print "Hello\n";
来源：http://dali.xylfe.cn/Article/details/gtqkgigxxx.html

[T42] Perl：变量类型
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrfrxwikt.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sxryk.cn/Article/details/gtzzzwhlxu.html

[T43] Perl：字符串插值
来源：http://dali.wangdashe.top/Article/details/gtbbvntvoa.html

"值: $a"
来源：http://dali.snrcjt.cn/Article/details/gtynuksvxu.html

[T44] Perl：条件
来源：http://dali.yuanzhike.top/Article/details/gtassrenta.html

if ($a > 0) { print "正"; }
来源：http://dali.hywenlv.cn/Article/details/gtyfucqpmk.html

[T45] Perl：数组遍历
来源：http://dali.yangfankeji.com/Article/details/gtlcnmxvme.html

for my $x (@arr) { print $x; }
来源：http://dali.kuanghao11.cn/Article/details/gtwblcrbtx.html

[T46] Perl：哈希操作
来源：http://dali.jinqigfzy.top/Article/details/gtgpikvamh.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.chenlongwang.top/Article/details/gtfneqgkat.html

[T47] Perl：正则捕获
来源：http://dali.smart0.xyz/Article/details/gtoqtshwrd.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtezgnrvkk.html

[T48] Perl：正则替换
来源：http://dali.hammf.cn/Article/details/gtkhctsatg.html

$s =~ s/old/new/g;
来源：http://dali.tanke756.top/Article/details/gtdhuitzhn.html

[T49] Perl：函数
来源：http://dali.yonumen.top/Article/details/gtcfkkxbab.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.nanxinkj.top/Article/details/gtuuinpvrr.html

[T50] Perl：逐行读文件
来源：http://dali.pengpengdd.cyou/Article/details/gtnqbqdvsa.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.sxryk.cn/Article/details/gtvxlsbnnh.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.tanke756.top/Article/details/gtozzovplw.html

[T51] Scala：Hello World
来源：http://dali.smart0.xyz/Article/details/gtnzgjvoob.html

println("Hello")
来源：http://dali.xuanzx.com/Article/details/gtxvwlitfy.html

[T52] Scala：变量
来源：http://dali.xziqi.cn/Article/details/gtqahmvgnw.html

val a = 1;  var b = 2
来源：http://dali.meibo888.top/Article/details/gtopzxwsul.html

[T53] Scala：字符串插值
来源：http://dali.tian-w.cn/Article/details/gtkjmxnicn.html

s"值: $b"
来源：http://dali.nwbrower.top/Article/details/gtksucnnmn.html

[T54] Scala：集合映射
来源：http://dali.yongpay.top/Article/details/gtjooahlkp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.aibaodan.cn/Article/details/gtohpqaxqf.html

[T55] Scala：集合过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjmyuqrve.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.ppjwa.cn/Article/details/gtkzodstfw.html

[T56] Scala：样例类
来源：http://dali.nanxuanxn.top/Article/details/gtahiqqcpy.html

case class User(name: String, age: Int)
来源：http://dali.fengsongda.top/Article/details/gtcyzdwnzz.html

[T57] Scala：模式匹配
来源：http://dali.hysaishi.cn/Article/details/gtozkcxfns.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.0kj1m.cn/Article/details/gtalnasnmq.html

[T58] Scala：函数定义
来源：http://dali.aibaodan.cn/Article/details/gtuluenfbk.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.svipenyu.cn/Article/details/gttwwohnpd.html

[T59] Scala：循环
来源：http://dali.kuanghao11.cn/Article/details/gtrggjaluy.html

for (i <- 1 to 10) println(i)
来源：http://dali.dianchejie.cn/Article/details/gtgrvbfkfr.html

[T60] Scala：折叠
来源：http://dali.andypj.xyz/Article/details/gtzlcwbdei.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.aizwys.cn/Article/details/gtycymzjwl.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtneezguzo.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.316326.xyz/Article/details/gtuvcwmeqi.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtynpguozf.html

[U01] Py：创建虚拟环境
来源：http://dali.vqdsnc.cn/Article/details/gtoefozxqm.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.jqgfzy.top/Article/details/gtncappevo.html

[U02] Py：导出 / 安装依赖
来源：http://dali.hfpthk.cn/Article/details/gtlocfajxw.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.zhongyouzk.top/Article/details/gtakfdohmn.html

[U03] Py：加载 .env 配置
来源：http://dali.aibaodan.cn/Article/details/gtjrtaofdf.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.shuidangran.top/Article/details/gtickleeim.html

[U04] Py：变量调试打印
来源：http://dali.havefunace.top/Article/details/gtwzjmvqgs.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.shanyushiyangkeji.top/Article/details/gthkqbqwwz.html

[U05] Py：列表去重且保序
来源：http://dali.cqqwz.cn/Article/details/gtbgascsft.html

list(dict.fromkeys(arr))
来源：http://dali.pengpengdd.cyou/Article/details/gtcpethnfv.html

[U06] Py：合并两个字典
来源：http://dali.iojbl.cn/Article/details/gttnxzeemk.html

{**a, **b}
来源：http://dali.vqdsnc.cn/Article/details/gtifohapuk.html

[U07] Py：反转字典键值
来源：http://dali.pengpengdd.cyou/Article/details/gtziboehdh.html

{v: k for k, v in d.items()}
来源：http://dali.pycfn.com/Article/details/gtxjdukhlg.html

[U08] Py：展平二维列表
来源：http://dali.quarkkingdee.top/Article/details/gtcbwnlplv.html

[y for x in nested for y in x]
来源：http://dali.mhx1999.top/Article/details/gtcbxsxevt.html


<!-- 参考信息 -->