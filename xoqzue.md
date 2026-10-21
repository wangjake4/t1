代发 wailian999

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jinqigfzy.top/Article/details/gtweueijlv.html

[R66] 定时任务
来源：http://dali.yuanzhike.top/Article/details/gtoferhpev.html

crontab -e;  crontab -l
来源：http://dali.xylfe.cn/Article/details/gtespuvrhv.html

[R67] 生成随机十六进制串
来源：http://dali.jinghuilouyu.cn/Article/details/gtnfcaring.html

openssl rand -hex 16
来源：http://dali.sweek.top/Article/details/gtphgcpjte.html

[R68] 计算文件校验值
来源：http://dali.zycfv.cn/Article/details/gtkbubywac.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtqhpqjzav.html

[R69] 生成随机密码
来源：http://dali.nanxuanxn.top/Article/details/gtgagzfcpz.html

head -c 16 /dev/urandom | base64
来源：http://dali.jiagoushi.top/Article/details/gtklsndctw.html

[R70] 时间戳与互转
来源：http://dali.zdqjudy.top/Article/details/gtkdqtllay.html

date +%s;  date -d @1700000000
来源：http://dali.sysykeji.top/Article/details/gtxaldnxsl.html

[R71] 日期格式化
来源：http://dali.zdqjudy.top/Article/details/gtttdxrsap.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gtcnemlgxp.html

[R72] 等待端口就绪
来源：http://dali.wangshuangyany.cn/Article/details/gtqozarptu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj202588.top/Article/details/gttvmoamqz.html

[R73] 分割大日志
来源：http://dali.gzhubu.top/Article/details/gtjhkoanpw.html

split -l 1000 big.log part_
来源：http://dali.gaohongyu789.top/Article/details/gttxdmuyib.html

[R74] 批量重命名
来源：http://dali.jinqigfzy.top/Article/details/gtvihduwvp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xziqi.cn/Article/details/gtsibueawg.html

[R75] 导出环境变量
来源：http://dali.haohaochexian.top/Article/details/gtxisbxxxl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.dashuyun.cn/Article/details/gtqdvejmor.html

[R76] 使用临时文件
来源：http://dali.ybcxt.top/Article/details/gtmctxpngr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cheryme.top/Article/details/gtcmkfyamu.html

[R77] 读取用户输入
来源：http://dali.316326.xyz/Article/details/gtzqufpdeu.html

read -rp "请输入: " ans
来源：http://dali.quarkkingdee.top/Article/details/gttnjovqeg.html

[R78] 交互式菜单
来源：http://dali.hywenlv.cn/Article/details/gtptvrlnlv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yvedp.cn/Article/details/gtrceoocvm.html

[R79] 解析命令行选项
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmypiqrts.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shangyingyoupin.top/Article/details/gtlrgadftc.html

[R80] 查看脚本执行耗时
来源：http://dali.jqgufenzy.top/Article/details/gtxyhvstwr.html

time ./run.sh
来源：http://dali.tianlin.xyz/Article/details/gtjupkpqcv.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtwzkqnxik.html

S. C / C++ 专题
来源：http://dali.cucudq.cn/Article/details/gtqeqpnknh.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtqrdvzask.html

[S01] C：Hello World
来源：http://dali.yongpay.top/Article/details/gtkgrrffhf.html

#include <stdio.h>
来源：http://dali.dashuyun.cn/Article/details/gtkxbwbnay.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.haohaochexian.top/Article/details/gtumwkxqvx.html

[S02] C：变量与格式化输出
来源：http://dali.xinyue.icu/Article/details/gtsjbildok.html

int a = 10; printf("%d\n", a);
来源：http://dali.hongshengwenyu.top/Article/details/gtenenmdps.html

[S03] C：读入整数
来源：http://dali.shzxlz.cn/Article/details/gtzilyieug.html

int x; scanf("%d", &x);
来源：http://dali.tian-w.cn/Article/details/gtfhuxpego.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gttnbjgubw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hammf.cn/Article/details/gtsnummobv.html

[S05] C：字符串长度
来源：http://dali.ybcxt.top/Article/details/gtsrzhohhf.html

strlen(s)
来源：http://dali.shanyushiyangtech.top/Article/details/gtxptmbvul.html

[S06] C：字符串比较
来源：http://dali.smart0.xyz/Article/details/gtjkomlfvr.html

strcmp(a, b) == 0
来源：http://dali.xuetiantiany.cn/Article/details/gtlopjdqoh.html

[S07] C：数组遍历求和
来源：http://dali.shanyushiyangtech.top/Article/details/gtszgxwoxc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.wangdashe.top/Article/details/gtycfsnknu.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gtpsstwjex.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.wangdashe.top/Article/details/gtcopyploi.html

[S09] C：结构体定义与初始化
来源：http://dali.yanxiufei.cn/Article/details/gtgmwduuqg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.tanke756.top/Article/details/gttbbczwce.html

[S10] C：指针与解引用
来源：http://dali.zhixingplan.top/Article/details/gthsgquiua.html

int *p = &a;  *p = 5;
来源：http://dali.gogol.net.cn/Article/details/gtvueaocze.html

[S11] C：逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gtpeqrezrl.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinqigufen.top/Article/details/gtbykyxhfw.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sufxvd.cn/Article/details/gtdxcvplsl.html

fclose(f);
来源：http://dali.jiagoushi.top/Article/details/gtyxzgpkqa.html

[S12] C：写文件
来源：http://dali.9152youxi.cn/Article/details/gtppqqhyqz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.guowangkeji.top/Article/details/gtllxjgvpq.html

[S13] C：宏定义
来源：http://dali.daxiang520.top/Article/details/gtsawodcjf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.meibo888.top/Article/details/gtljqikmtv.html

[S14] C：枚举
来源：http://dali.fengsongda.top/Article/details/gtazdobsaf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xylfe.cn/Article/details/gtwwkjywbe.html

[S15] C：类型转换
来源：http://dali.xuanzx.com/Article/details/gtbwzlubri.html

(double) a / b
来源：http://dali.chenzaomai.com/Article/details/gtimevciyb.html

[S16] C：位操作置位
来源：http://dali.jlsjyb.cn/Article/details/gtycybjoqx.html

x |= (1 << 3);
来源：http://dali.yuanzhike.top/Article/details/gtpmuojvol.html

[S17] C：安全拼接字符串
来源：http://dali.0kj1m.cn/Article/details/gtgaqkjlez.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhengqikj.top/Article/details/gtlautekea.html

[S18] C：命令行参数
来源：http://dali.xuetiantiany.cn/Article/details/gtsrmioqfn.html

int main(int argc, char **argv)
来源：http://dali.sweek.top/Article/details/gticaawvsi.html

[S19] C：快速排序
来源：http://dali.fengsongda.top/Article/details/gtqikmuvhe.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinqigfzy.top/Article/details/gtuawewvjd.html

[S20] C：二分查找
来源：http://dali.dianchejie.cn/Article/details/gtcyzsvfdk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.meibo888.top/Article/details/gttilzuodv.html

[S21] C：字符类别判断
来源：http://dali.zhiwuduotai.top/Article/details/gtpatcsudi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhongyouzk.top/Article/details/gtiocnqshr.html

[S22] C：字符串转数字
来源：http://dali.0kj1m.cn/Article/details/gtmyhpccle.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yueranfly.top/Article/details/gtobjrzjhf.html

[S23] C：随机数
来源：http://dali.gogol.net.cn/Article/details/gtwgkhteeh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.9152youxi.cn/Article/details/gtnakkgeaq.html

[S24] C：获取本地时间
来源：http://dali.shuidangran.top/Article/details/gtytioyozo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.nanxinkj.top/Article/details/gtqbgwuvlo.html

[S25] C：内存拷贝
来源：http://dali.pycfn.com/Article/details/gtmzkcwdhi.html

memcpy(dst, src, n);
来源：http://dali.aibaodan.cn/Article/details/gtdxlrbnvt.html

[S26] C：内存清零
来源：http://dali.iojbl.cn/Article/details/gtrigutcsu.html

memset(a, 0, sizeof a);
来源：http://dali.daxiang520.top/Article/details/gtruqqwgsz.html

[S27] C：定义常量
来源：http://dali.sxryk.cn/Article/details/gtdqkudexx.html

const double PI = 3.14159;
来源：http://dali.fengsongda.top/Article/details/gtkjzckdpg.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gtavlfojka.html

static int counter = 0;
来源：http://dali.guowangkeji.top/Article/details/gtjlctesby.html

[S29] C：变参函数
来源：http://dali.daria6918.cn/Article/details/gtjpspdayn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gzhubu.top/Article/details/gtesoprgtr.html

[S30] C：头文件保护
来源：http://dali.ybcxt.top/Article/details/gtxaxfcqho.html

#ifndef X_H
来源：http://dali.shzxlz.cn/Article/details/gtxzvqqiss.html

#define X_H
来源：http://dali.hnqzz.top/Article/details/gtekxrlrsg.html

#endif
来源：http://dali.bjfxy.top/Article/details/gtvfjxvzal.html

[S31] C++：Hello World
来源：http://dali.yongpay.top/Article/details/gtwpguchpw.html

#include <iostream>
来源：http://dali.zhixingplan.top/Article/details/gtabihztgl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.tian-w.cn/Article/details/gtstlhomdb.html

[S32] C++：字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgvhglxwd.html

std::string s = "hi";  s += "!";
来源：http://dali.zhiwuduotai.top/Article/details/gtyivpugtx.html

[S33] C++：vector 增删
来源：http://dali.smart0.xyz/Article/details/gtxzlakjul.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jlsjyb.cn/Article/details/gtntmvlbyd.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gtjcobnzdn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jinqigufen.top/Article/details/gtdcyzdzqo.html

[S35] C++：map
来源：http://dali.havefunace.top/Article/details/gtdlhmxcvz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gtzlsrrtnk.html

[S36] C++：unordered_map
来源：http://dali.guowangkeji.top/Article/details/gtjsnozhrv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuxming.cn/Article/details/gtevqmwcqi.html

[S37] C++：set
来源：http://dali.chenzaomai.com/Article/details/gtxayiuddr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hywenlv.cn/Article/details/gtwmrskxmb.html

[S38] C++：排序
来源：http://dali.zhongyouzk.top/Article/details/gtpcksmsmg.html

std::sort(v.begin(), v.end());
来源：http://dali.yj202588.top/Article/details/gtafnchoka.html

[S39] C++：自定义比较器排序
来源：http://dali.hnqzz.top/Article/details/gtpiykvekx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenjidiqi.icu/Article/details/gtqtijwfjl.html

[S40] C++：查找元素
来源：http://dali.daria6918.cn/Article/details/gtgetcipcc.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzhbueaxz.html

[S41] C++：类与构造函数
来源：http://dali.jianghu66.top/Article/details/gtufashjge.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.c1oappe.top/Article/details/gttaazlgdv.html

[S42] C++：继承与虚函数
来源：http://dali.sysykeji.top/Article/details/gtctylczqq.html

class B : public Base { public: void f() override {} };
来源：http://dali.shanyushiyangtech.top/Article/details/gtfwfocigy.html

[S43] C++：智能指针
来源：http://dali.shuidangran.top/Article/details/gtekxblsat.html

auto p = std::make_unique<int>(5);
来源：http://dali.ehwqpu.com/Article/details/gtneioacho.html

[S44] C++：引用传参
来源：http://dali.jlsjyb.cn/Article/details/gtkkdbrtxe.html

void inc(int &x) { ++x; }
来源：http://dali.ybcxt.top/Article/details/gttbepktef.html

[S45] C++：lambda
来源：http://dali.aizwys.cn/Article/details/gtkfgybnvx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sysykeji.top/Article/details/gtmxlwstof.html

[S46] C++：函数模板
来源：http://dali.xylfe.cn/Article/details/gtyowyttje.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gzhubu.top/Article/details/gtgyrropqf.html

[S47] C++：结构化绑定遍历
来源：http://dali.c1oappe.top/Article/details/gtnfzrnlsu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cucudq.cn/Article/details/gtqmhmraae.html

[S48] C++：逐行读文件
来源：http://dali.316326.xyz/Article/details/gtcguozrob.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.316326.xyz/Article/details/gteeuqstjv.html

while (std::getline(in, line)) { }
来源：http://dali.tianlin.xyz/Article/details/gtjhvoywkz.html

[S49] C++：写文件
来源：http://dali.cashguo.top/Article/details/gtgbmtbter.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sxryk.cn/Article/details/gtdtjtzpst.html

[S50] C++：格式化数字
来源：http://dali.dashuyun.cn/Article/details/gtrolmjbqe.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.guannengcc.top/Article/details/gtmumpfavi.html

[S51] C++：显式类型转换
来源：http://dali.mhx1999.top/Article/details/gtlntmtgvk.html

static_cast<double>(a) / b
来源：http://dali.xylfe.cn/Article/details/gtjepagwdt.html

[S52] C++：const 与 noexcept
来源：http://dali.sysykeji.top/Article/details/gtfmjrkmrb.html

int size() const noexcept { return n_; }
来源：http://dali.cucudq.cn/Article/details/gteyitbwrh.html

[S53] C++：移动语义
来源：http://dali.yangfankeji.com/Article/details/gtnyslpmsa.html

std::vector<int> w = std::move(v);
来源：http://dali.c1oappe.top/Article/details/gtxrwglcbi.html

[S54] C++：异常处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbisvtbgd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yueranfly.top/Article/details/gtqfdmzfvc.html

[S55] C++：结构化绑定
来源：http://dali.jqgufenzy.top/Article/details/gtmzgfvmkm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xuetiantiany.cn/Article/details/gtslrdzlur.html

[S56] C++：optional
来源：http://dali.sufxvd.cn/Article/details/gtejbieipi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shangyingyoupin.top/Article/details/gtlxhsdhiq.html

[S57] C++：编译期常量
来源：http://dali.gotoacloud.top/Article/details/gtrydwcuow.html

constexpr int N = 10;
来源：http://dali.chenlongwang.top/Article/details/gturilezyg.html

[S58] C++：命名空间
来源：http://dali.nanxinkj.top/Article/details/gtbmltmebx.html

namespace ns { int f() { return 1; } }
来源：http://dali.birdmap.top/Article/details/gthhgjvdow.html

[S59] C++：静态断言
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkyxcnnkl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.vqdsnc.cn/Article/details/gtwsywaier.html

[S60] C++：遍历并删除元素
来源：http://dali.chenlongwang.top/Article/details/gtqzhcmibn.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xinyue.icu/Article/details/gtffouikou.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtdmvqtoak.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cashguo.top/Article/details/gtsfeiusxy.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtkxuriyjk.html

[T01] Kotlin：Hello World
来源：http://dali.hysaishi.cn/Article/details/gtugkelddv.html

println("Hello")
来源：http://dali.pycfn.com/Article/details/gtayvbrcvh.html

[T02] Kotlin：变量
来源：http://dali.sysykeji.top/Article/details/gtzgrdpbyy.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ybcxt.top/Article/details/gtxpwahrdm.html

[T03] Kotlin：字符串模板
来源：http://dali.aibaodan.cn/Article/details/gtpespxsya.html

"值: $b"
来源：http://dali.gzhubu.top/Article/details/gtdguospbg.html

[T04] Kotlin：空安全
来源：http://dali.nwbrower.top/Article/details/gtxlwknthu.html

val n: String? = null;  n?.length
来源：http://dali.zhiwuduotai.top/Article/details/gtoftypxbe.html

[T05] Kotlin：when 表达式
来源：http://dali.guowangkeji.top/Article/details/gttilfxpoe.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtunbhfeme.html

[T06] Kotlin：集合映射
来源：http://dali.yuxming.cn/Article/details/gtbunaxlrd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.ydzc1.top/Article/details/gtyhtplvjv.html

[T07] Kotlin：集合过滤
来源：http://dali.havefunace.top/Article/details/gtrftieebg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcuohstfb.html

[T08] Kotlin：数据类
来源：http://dali.jlsjyb.cn/Article/details/gtlhqineej.html

data class User(val name: String, val age: Int)
来源：http://dali.aibaodan.cn/Article/details/gtnhpfzico.html

[T09] Kotlin：扩展函数
来源：http://dali.smart0.xyz/Article/details/gteprtlgub.html

fun String.exclaim() = this + "!"
来源：http://dali.tanke756.top/Article/details/gtpktazraq.html

[T10] Kotlin：默认参数
来源：http://dali.cucudq.cn/Article/details/gtweegolyf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.chenlongwang.top/Article/details/gtnxfrfsvy.html

[T11] Kotlin：协程
来源：http://dali.andypj.xyz/Article/details/gtgvqeaqhv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yueranfly.top/Article/details/gtcswyqcye.html

[T12] Kotlin：解构声明
来源：http://dali.sxryk.cn/Article/details/gtddoqllch.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinghuilouyu.cn/Article/details/gtgcjjexbm.html

[T13] Kotlin：只读 Map
来源：http://dali.9152youxi.cn/Article/details/gtvutkxdzo.html

val m = mapOf("a" to 1)
来源：http://dali.jqgufenzy.top/Article/details/gthzqxjefw.html

[T14] Kotlin：循环
来源：http://dali.iojbl.cn/Article/details/gtmnaujgnq.html

for (i in 1..10) println(i)
来源：http://dali.hysaishi.cn/Article/details/gtparvnexz.html

[T15] Kotlin：接口
来源：http://dali.hnqzz.top/Article/details/gtjoxjgjnw.html

interface Shape { fun area(): Double }
来源：http://dali.yuanzhike.top/Article/details/gtlpietjfh.html

[T16] Swift：Hello World
来源：http://dali.smart0.xyz/Article/details/gtsrcfpufp.html

print("Hello")
来源：http://dali.0kj1m.cn/Article/details/gthysjyvrz.html

[T17] Swift：变量与常量
来源：http://dali.zhijiandao.cn/Article/details/gticwlipls.html

var a = 1;  let b = 2
来源：http://dali.dashuyun.cn/Article/details/gtrrgwtwoy.html

[T18] Swift：字符串插值
来源：http://dali.nwbrower.top/Article/details/gtmiylynyt.html

"值: \(b)"
来源：http://dali.nwbrower.top/Article/details/gtleywzsmp.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gtwssxzywn.html

if let n = opt { print(n) }
来源：http://dali.gotoacloud.top/Article/details/gtyufamucp.html

[T20] Swift：数组操作
来源：http://dali.iojbl.cn/Article/details/gtylumbyhv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cashguo.top/Article/details/gtfrgcclbd.html

[T21] Swift：遍历
来源：http://dali.quarkkingdee.top/Article/details/gtdqxylamt.html

for x in a { print(x) }
来源：http://dali.yj202588.top/Article/details/gtohhdxbco.html

[T22] Swift：字典
来源：http://dali.dashuyun.cn/Article/details/gtkhlydrvg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.redwolf501.top/Article/details/gtfyhxganf.html

[T23] Swift：函数
来源：http://dali.yj20258.top/Article/details/gtnkpcbvge.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shanyushiyangkeji.top/Article/details/gthyqupevk.html

[T24] Swift：闭包
来源：http://dali.yanxiufei.cn/Article/details/gtqarxrmer.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhoulong.xyz/Article/details/gtnjwutrrc.html

[T25] Swift：结构体
来源：http://dali.quarkkingdee.top/Article/details/gtsbbenuav.html

struct P { var x: Int }
来源：http://dali.nanxuanxn.top/Article/details/gtvpqiqvrc.html

[T26] Swift：类与重写
来源：http://dali.xuanzx.com/Article/details/gtatgtdwxs.html

class A: Base { override func f() {} }
来源：http://dali.cheryme.top/Article/details/gtjrapjzzw.html

[T27] Swift：错误处理
来源：http://dali.smart0.xyz/Article/details/gtpkknmfxq.html

do { try f() } catch { print(error) }
来源：http://dali.feifeiyinyue.top/Article/details/gtadqbdpqy.html

[T28] Swift：枚举
来源：http://dali.xylfe.cn/Article/details/gtvkdhluha.html

enum Color { case red, green }
来源：http://dali.quarkkingdee.top/Article/details/gttcarsimh.html

[T29] Swift：guard 提前返回
来源：http://dali.gogol.net.cn/Article/details/gtdjtknzpn.html

guard let x = opt else { return }
来源：http://dali.havefunace.top/Article/details/gtdopkdxcm.html

[T30] Swift：协议
来源：http://dali.birdmap.top/Article/details/gttwhvuwet.html

protocol Shape { func area() -> Double }
来源：http://dali.chenjidiqi.icu/Article/details/gtfigrwpoa.html

[T31] Lua：Hello World
来源：http://dali.havefunace.top/Article/details/gtraxhdymf.html

print("Hello")
来源：http://dali.birdmap.top/Article/details/gtzlrcwafa.html

[T32] Lua：局部变量
来源：http://dali.meibo888.top/Article/details/gtiufdzafx.html

local a = 1
来源：http://dali.jqgfzy.top/Article/details/gtmukoskck.html

[T33] Lua：表（数组）
来源：http://dali.hongshengwenyu.top/Article/details/gtfjenqagr.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cheryme.top/Article/details/gtdgokyekr.html

[T34] Lua：遍历表
来源：http://dali.dashuyun.cn/Article/details/gtsgoiedav.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xuetiantiany.cn/Article/details/gtnyoxkzey.html

[T35] Lua：字典表
来源：http://dali.redwolf501.top/Article/details/gtcasjmxnl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnzvjvpwg.html

[T36] Lua：函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtsvcldodi.html

function add(a, b) return a + b end
来源：http://dali.fzhhl.top/Article/details/gtihirizhl.html

[T37] Lua：字符串拼接
来源：http://dali.yj20258.top/Article/details/gtdyuouhqb.html

"a" .. "b"
来源：http://dali.jianghu66.top/Article/details/gtyaddvjkx.html

[T38] Lua：条件
来源：http://dali.yj20258.top/Article/details/gtfzsshudq.html

if x > 0 then print("正") end
来源：http://dali.wangshuangyany.cn/Article/details/gthppcdxor.html

[T39] Lua：模式匹配
来源：http://dali.gogol.net.cn/Article/details/gtpyuuiqxw.html

string.find(s, "%d+")
来源：http://dali.cashguo.top/Article/details/gteplmtifn.html

[T40] Lua：元表
来源：http://dali.gogol.net.cn/Article/details/gtewdywdqw.html

setmetatable({}, { __index = base })
来源：http://dali.wangdashe.top/Article/details/gtrnqnlkgz.html

[T41] Perl：Hello World
来源：http://dali.yvedp.cn/Article/details/gtooimtgvb.html

print "Hello\n";
来源：http://dali.chenlongwang.top/Article/details/gtdbhsugmb.html

[T42] Perl：变量类型
来源：http://dali.redwolf501.top/Article/details/gtyeqolqmn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhijiandao.cn/Article/details/gtjpwmkyqs.html

[T43] Perl：字符串插值
来源：http://dali.nwbrower.top/Article/details/gtkshgnzjr.html

"值: $a"
来源：http://dali.zhoulong.xyz/Article/details/gttybxnhbx.html

[T44] Perl：条件
来源：http://dali.316326.xyz/Article/details/gtsnhiddcs.html

if ($a > 0) { print "正"; }
来源：http://dali.sxryk.cn/Article/details/gtajtiyqcl.html

[T45] Perl：数组遍历
来源：http://dali.guowangkeji.top/Article/details/gtteawvukb.html

for my $x (@arr) { print $x; }
来源：http://dali.feifeiyinyue.top/Article/details/gtlcjeljfa.html

[T46] Perl：哈希操作
来源：http://dali.ybcxt.top/Article/details/gtrxvppnhq.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zycfv.cn/Article/details/gthgxwutwq.html

[T47] Perl：正则捕获
来源：http://dali.xuanzx.com/Article/details/gttecopqpq.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.pengpengdd.cyou/Article/details/gtadduczwy.html

[T48] Perl：正则替换
来源：http://dali.tian-w.cn/Article/details/gtzmgxgepq.html

$s =~ s/old/new/g;
来源：http://dali.tian-w.cn/Article/details/gtsijbbtqx.html

[T49] Perl：函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjmierkge.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.svipenyu.cn/Article/details/gtxyklnmrg.html

[T50] Perl：逐行读文件
来源：http://dali.jinqigfzy.top/Article/details/gtxsiyzqgw.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttzuttpur.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.ivvv.top/Article/details/gtsagtggte.html

[T51] Scala：Hello World
来源：http://dali.pengpengdd.cyou/Article/details/gtbalmorlb.html

println("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gtaqxvrdqa.html

[T52] Scala：变量
来源：http://dali.nanxinkj.top/Article/details/gtyafiocbm.html

val a = 1;  var b = 2
来源：http://dali.nanxinkj.top/Article/details/gtzgmmpsxu.html

[T53] Scala：字符串插值
来源：http://dali.zhixingplan.top/Article/details/gttvzuvhak.html

s"值: $b"
来源：http://dali.havefunace.top/Article/details/gtjvuvaeph.html

[T54] Scala：集合映射
来源：http://dali.jqgfzy.top/Article/details/gtotziajyz.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cdnleiting.top/Article/details/gtnofjffaw.html

[T55] Scala：集合过滤
来源：http://dali.cashguo.top/Article/details/gtofgzneco.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.0kj1m.cn/Article/details/gtuhgojboq.html

[T56] Scala：样例类
来源：http://dali.jinghuilouyu.cn/Article/details/gtnkbezkhq.html

case class User(name: String, age: Int)
来源：http://dali.0kj1m.cn/Article/details/gtgojuauvj.html

[T57] Scala：模式匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtiydnajjd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.shangyingyoupin.top/Article/details/gtxyeilggz.html

[T58] Scala：函数定义
来源：http://dali.quarkkingdee.top/Article/details/gtauvgeivb.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.snrcjt.cn/Article/details/gtasdeoyrq.html

[T59] Scala：循环
来源：http://dali.zhongyouzk.top/Article/details/gteawphqfx.html

for (i <- 1 to 10) println(i)
来源：http://dali.mhx1999.top/Article/details/gtgrqxyxen.html

[T60] Scala：折叠
来源：http://dali.pycfn.com/Article/details/gtngzbjhgv.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.vqdsnc.cn/Article/details/gtsyikrrmo.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtquogtdca.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yueranfly.top/Article/details/gtrzybpbff.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtikzkntfu.html

[U01] Py：创建虚拟环境
来源：http://dali.gzhubu.top/Article/details/gtxhpgdxgd.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.cashguo.top/Article/details/gtemoqxmnt.html

[U02] Py：导出 / 安装依赖
来源：http://dali.guowangkeji.top/Article/details/gtggyrruxi.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.havefunace.top/Article/details/gtmvwcvavu.html

[U03] Py：加载 .env 配置
来源：http://dali.yueranfly.top/Article/details/gtveqyjwhm.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.gzhubu.top/Article/details/gtnxdxlwfm.html

[U04] Py：变量调试打印
来源：http://dali.chenlongwang.top/Article/details/gtapgahcby.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.jqgfzy.top/Article/details/gtadpsglkc.html

[U05] Py：列表去重且保序
来源：http://dali.tian-w.cn/Article/details/gtkelbwqeq.html

list(dict.fromkeys(arr))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlbxscluc.html

[U06] Py：合并两个字典
来源：http://dali.jiagoushi.top/Article/details/gtyshzfovr.html

{**a, **b}
来源：http://dali.jinqigfzy.top/Article/details/gtewhldlco.html


<!-- 参考信息 -->