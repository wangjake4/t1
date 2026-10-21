代发 wailian999

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ydzc1.top/Article/details/gtnymkgmfi.html

[R60] 只看 HTTP 状态码
来源：http://dali.quarkkingdee.top/Article/details/gtdnqpmvvl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.tianlin.xyz/Article/details/gtutocmpeo.html

[R61] 磁盘占用
来源：http://dali.nanxuanxn.top/Article/details/gtssaaspai.html

df -h;  du -sh *
来源：http://dali.cashguo.top/Article/details/gtxbsipzri.html

[R62] 找最占空间的文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsuskbkie.html

du -ah . | sort -rh | head -10
来源：http://dali.aibaodan.cn/Article/details/gtuszmxvkj.html

[R63] 内存与进程
来源：http://dali.tianlin.xyz/Article/details/gtjjhmrxzn.html

free -h;  ps aux | grep nginx
来源：http://dali.andypj.xyz/Article/details/gtnpaegqwn.html

[R64] 结束进程
来源：http://dali.sufxvd.cn/Article/details/gtramedplu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cucudq.cn/Article/details/gtqouuwizb.html

[R65] 查看端口占用
来源：http://dali.pycfn.com/Article/details/gtvpiufjtd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cdnleiting.top/Article/details/gtpgizkvjn.html

[R66] 定时任务
来源：http://dali.xylfe.cn/Article/details/gtehmxrekp.html

crontab -e;  crontab -l
来源：http://dali.xziqi.cn/Article/details/gtjfxifrka.html

[R67] 生成随机十六进制串
来源：http://dali.chenjidiqi.icu/Article/details/gtsatpsrlg.html

openssl rand -hex 16
来源：http://dali.fzhhl.top/Article/details/gtygxqsvez.html

[R68] 计算文件校验值
来源：http://dali.jinghuilouyu.cn/Article/details/gtcklgyajq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jianghu66.top/Article/details/gtfzknmnae.html

[R69] 生成随机密码
来源：http://dali.shuidangran.top/Article/details/gthpsbsedi.html

head -c 16 /dev/urandom | base64
来源：http://dali.yj202588.top/Article/details/gtpjoghdps.html

[R70] 时间戳与互转
来源：http://dali.jqgfzy.top/Article/details/gtcuvyucky.html

date +%s;  date -d @1700000000
来源：http://dali.hammf.cn/Article/details/gtfwegwvcq.html

[R71] 日期格式化
来源：http://dali.wangshuangyany.cn/Article/details/gtgkjlxbzi.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hnqzz.top/Article/details/gtncgjhovu.html

[R72] 等待端口就绪
来源：http://dali.jqgfzy.top/Article/details/gtbbolwdlm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinqigfzy.top/Article/details/gtjfhqemel.html

[R73] 分割大日志
来源：http://dali.aibaodan.cn/Article/details/gtxxeipqad.html

split -l 1000 big.log part_
来源：http://dali.xziqi.cn/Article/details/gtjilvligh.html

[R74] 批量重命名
来源：http://dali.zycfv.cn/Article/details/gtkjbyyxwr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ybcxt.top/Article/details/gtrnmnfhsj.html

[R75] 导出环境变量
来源：http://dali.chenjidiqi.icu/Article/details/gtoxbncaxy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ppjwa.cn/Article/details/gtjovrbwav.html

[R76] 使用临时文件
来源：http://dali.0kj1m.cn/Article/details/gtfjtihdkr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hysaishi.cn/Article/details/gtqshjvfcy.html

[R77] 读取用户输入
来源：http://dali.wangshuangyany.cn/Article/details/gtbgpzfvuz.html

read -rp "请输入: " ans
来源：http://dali.jiagoushi.top/Article/details/gtqovzzuap.html

[R78] 交互式菜单
来源：http://dali.aizwys.cn/Article/details/gtzhrjuhis.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yvedp.cn/Article/details/gtmcciegpe.html

[R79] 解析命令行选项
来源：http://dali.sweek.top/Article/details/gthclvksgt.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.dashuyun.cn/Article/details/gtdzbviarn.html

[R80] 查看脚本执行耗时
来源：http://dali.zhiwuduotai.top/Article/details/gteqpbofmz.html

time ./run.sh
来源：http://dali.jiagoushi.top/Article/details/gtslqokeci.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtsypyqaff.html

S. C / C++ 专题
来源：http://dali.havefunace.top/Article/details/gtnvjqcoyy.html

================================================================================
来源：http://dali.yuanzhike.top/Article/details/gtxbqfqivo.html

[S01] C：Hello World
来源：http://dali.shuidangran.top/Article/details/gtnuqxljlu.html

#include <stdio.h>
来源：http://dali.chenzaomai.com/Article/details/gtkhgvstqx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.guowangkeji.top/Article/details/gtvxlqaxiq.html

[S02] C：变量与格式化输出
来源：http://dali.meibo888.top/Article/details/gtzwjgwiqt.html

int a = 10; printf("%d\n", a);
来源：http://dali.aibaodan.cn/Article/details/gtmtzlvhdx.html

[S03] C：读入整数
来源：http://dali.wangshuangyany.cn/Article/details/gtfqctultv.html

int x; scanf("%d", &x);
来源：http://dali.sxryk.cn/Article/details/gtlbajxord.html

[S04] C：字符串复制
来源：http://dali.cucudq.cn/Article/details/gtcaavntwz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cqqwz.cn/Article/details/gtdsuznisw.html

[S05] C：字符串长度
来源：http://dali.hammf.cn/Article/details/gtxujjdfir.html

strlen(s)
来源：http://dali.kuanghao11.cn/Article/details/gtjnbmnrfw.html

[S06] C：字符串比较
来源：http://dali.svipenyu.cn/Article/details/gtsrxlauwz.html

strcmp(a, b) == 0
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlkvikson.html

[S07] C：数组遍历求和
来源：http://dali.ehwqpu.com/Article/details/gtukqvrycr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.chenlongwang.top/Article/details/gtzpuqukii.html

[S08] C：动态内存分配与释放
来源：http://dali.jinqigufen.top/Article/details/gtxmpqlpae.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.0kj1m.cn/Article/details/gtnatxwsfs.html

[S09] C：结构体定义与初始化
来源：http://dali.iojbl.cn/Article/details/gtbipgzjjm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jinqigufen.top/Article/details/gtwpabmjcz.html

[S10] C：指针与解引用
来源：http://dali.quarkkingdee.top/Article/details/gtybdrpihh.html

int *p = &a;  *p = 5;
来源：http://dali.xinyue.icu/Article/details/gtxwonhzpe.html

[S11] C：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gtlpzbbfva.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shuidangran.top/Article/details/gtlppuvbdb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhoulong.xyz/Article/details/gtvfefrymj.html

fclose(f);
来源：http://dali.hfpthk.cn/Article/details/gtxuzijlzk.html

[S12] C：写文件
来源：http://dali.hywenlv.cn/Article/details/gtlnqhgdvi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yueranfly.top/Article/details/gtijflhhcy.html

[S13] C：宏定义
来源：http://dali.ivvv.top/Article/details/gtwbrolqfw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shuidangran.top/Article/details/gtdsjgrdyt.html

[S14] C：枚举
来源：http://dali.cheryme.top/Article/details/gtyksnxzso.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.tianlin.xyz/Article/details/gtnnhhxowt.html

[S15] C：类型转换
来源：http://dali.xziqi.cn/Article/details/gtnregtspq.html

(double) a / b
来源：http://dali.iojbl.cn/Article/details/gtufmdbwoh.html

[S16] C：位操作置位
来源：http://dali.jinqigufen.top/Article/details/gtlxqwdxvm.html

x |= (1 << 3);
来源：http://dali.yuanzhike.top/Article/details/gtbyiuxgmr.html

[S17] C：安全拼接字符串
来源：http://dali.zycfv.cn/Article/details/gtaouyumvm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jqgufenzy.top/Article/details/gtxcdbnkpl.html

[S18] C：命令行参数
来源：http://dali.ivvv.top/Article/details/gtvsujzzpy.html

int main(int argc, char **argv)
来源：http://dali.sufxvd.cn/Article/details/gtzbdemwdv.html

[S19] C：快速排序
来源：http://dali.nanxuanxn.top/Article/details/gtaosftece.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.tianlin.xyz/Article/details/gttaoigcxe.html

[S20] C：二分查找
来源：http://dali.jinyuanbaomall.cn/Article/details/gtygwxklie.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.tian-w.cn/Article/details/gtjxhrayqc.html

[S21] C：字符类别判断
来源：http://dali.dianchejie.cn/Article/details/gtiznlzzdc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xziqi.cn/Article/details/gtodewwdpt.html

[S22] C：字符串转数字
来源：http://dali.iojbl.cn/Article/details/gtfapjnuff.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.vqdsnc.cn/Article/details/gtafdrhiom.html

[S23] C：随机数
来源：http://dali.xziqi.cn/Article/details/gtbwdkazwk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.316326.xyz/Article/details/gtqfurcibf.html

[S24] C：获取本地时间
来源：http://dali.chenlongwang.top/Article/details/gtmfmvvuew.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.quarkkingdee.top/Article/details/gtemrodett.html

[S25] C：内存拷贝
来源：http://dali.ydzc1.top/Article/details/gtjnjsmajv.html

memcpy(dst, src, n);
来源：http://dali.daxiang520.top/Article/details/gtyltafxmm.html

[S26] C：内存清零
来源：http://dali.jlsjyb.cn/Article/details/gtzubedqxy.html

memset(a, 0, sizeof a);
来源：http://dali.cheryme.top/Article/details/gtrxcqrtda.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gtlgvzwhdg.html

const double PI = 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gtiueywnun.html

[S28] C：静态变量
来源：http://dali.kuanghao11.cn/Article/details/gtynbdkunk.html

static int counter = 0;
来源：http://dali.jyoumei.cn/Article/details/gtnsbtylwu.html

[S29] C：变参函数
来源：http://dali.gogol.net.cn/Article/details/gtoklcswym.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.guannengcc.top/Article/details/gtmsxtbssa.html

[S30] C：头文件保护
来源：http://dali.shanyushiyangkeji.top/Article/details/gtigxvorlc.html

#ifndef X_H
来源：http://dali.xuanzx.com/Article/details/gttlnppgnr.html

#define X_H
来源：http://dali.xylfe.cn/Article/details/gtknpqnjri.html

#endif
来源：http://dali.shzxlz.cn/Article/details/gtmkjmcmuj.html

[S31] C++：Hello World
来源：http://dali.tian-w.cn/Article/details/gtefkgzhbi.html

#include <iostream>
来源：http://dali.jqgufenzy.top/Article/details/gtipullbkf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.aizwys.cn/Article/details/gtrzvlyphp.html

[S32] C++：字符串
来源：http://dali.zhongyouzk.top/Article/details/gtbpnnpsyn.html

std::string s = "hi";  s += "!";
来源：http://dali.bjfxy.top/Article/details/gtgqbrbnbn.html

[S33] C++：vector 增删
来源：http://dali.hnqzz.top/Article/details/gtcepndaqd.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtiinsaeuc.html

[S34] C++：遍历 vector
来源：http://dali.yvedp.cn/Article/details/gtpppooiyg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yongpay.top/Article/details/gtpuikuybb.html

[S35] C++：map
来源：http://dali.shuidangran.top/Article/details/gthliosios.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pycfn.com/Article/details/gtxufnxuus.html

[S36] C++：unordered_map
来源：http://dali.ywan-chungtsiang.top/Article/details/gtruvfzgth.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zycfv.cn/Article/details/gtwfzohmni.html

[S37] C++：set
来源：http://dali.ybcxt.top/Article/details/gtxsagvdfo.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nanxinkj.top/Article/details/gtdamusrwh.html

[S38] C++：排序
来源：http://dali.zhoulong.xyz/Article/details/gttzjyidlv.html

std::sort(v.begin(), v.end());
来源：http://dali.chenzaomai.com/Article/details/gtaytrmabd.html

[S39] C++：自定义比较器排序
来源：http://dali.yj20258888.top/Article/details/gtjjzownon.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xuanzx.com/Article/details/gtknfvvkrl.html

[S40] C++：查找元素
来源：http://dali.dianchejie.cn/Article/details/gtlfftuhky.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xinyue.icu/Article/details/gtsjckjcfe.html

[S41] C++：类与构造函数
来源：http://dali.quarkkingdee.top/Article/details/gtxzjqxmxw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xuanzx.com/Article/details/gthlcgqvuj.html

[S42] C++：继承与虚函数
来源：http://dali.nanxuanxn.top/Article/details/gtjhoeoyzf.html

class B : public Base { public: void f() override {} };
来源：http://dali.dianchejie.cn/Article/details/gtptenlfjr.html

[S43] C++：智能指针
来源：http://dali.chenzaomai.com/Article/details/gtxpscdczd.html

auto p = std::make_unique<int>(5);
来源：http://dali.quarkkingdee.top/Article/details/gtqnprwtcj.html

[S44] C++：引用传参
来源：http://dali.smart0.xyz/Article/details/gtlnbgiesn.html

void inc(int &x) { ++x; }
来源：http://dali.hfpthk.cn/Article/details/gtaqczacyc.html

[S45] C++：lambda
来源：http://dali.gotoacloud.top/Article/details/gtnvupxjqf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.daria6918.cn/Article/details/gtvsjyfvon.html

[S46] C++：函数模板
来源：http://dali.nwbrower.top/Article/details/gthnfkscmv.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtqbgxmnoo.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhongyouzk.top/Article/details/gtltzguict.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.zhixingplan.top/Article/details/gtratllzqm.html

[S48] C++：逐行读文件
来源：http://dali.hammf.cn/Article/details/gtmfdjdnoy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xinyue.icu/Article/details/gtzxvuxgpj.html

while (std::getline(in, line)) { }
来源：http://dali.zhoulong.xyz/Article/details/gtmnlqvxvq.html

[S49] C++：写文件
来源：http://dali.shanyushiyangtech.top/Article/details/gthhzfhmro.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.fengsongda.top/Article/details/gtbodmlczk.html

[S50] C++：格式化数字
来源：http://dali.hfpthk.cn/Article/details/gtmosnqarf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cashguo.top/Article/details/gtkztvbwhn.html

[S51] C++：显式类型转换
来源：http://dali.yonumen.top/Article/details/gtgwzhvvug.html

static_cast<double>(a) / b
来源：http://dali.shzxlz.cn/Article/details/gtcbojefzt.html

[S52] C++：const 与 noexcept
来源：http://dali.jianghu66.top/Article/details/gtjnwzkfrq.html

int size() const noexcept { return n_; }
来源：http://dali.aibaodan.cn/Article/details/gtnufrevum.html

[S53] C++：移动语义
来源：http://dali.ivvv.top/Article/details/gtkmyzzwzs.html

std::vector<int> w = std::move(v);
来源：http://dali.meibo888.top/Article/details/gtsxwiiivb.html

[S54] C++：异常处理
来源：http://dali.bjfxy.top/Article/details/gthumcnajp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.haohaochexian.top/Article/details/gtqfzuynif.html

[S55] C++：结构化绑定
来源：http://dali.ybcxt.top/Article/details/gtbygwkygs.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.316326.xyz/Article/details/gthybdgpng.html

[S56] C++：optional
来源：http://dali.zhixingplan.top/Article/details/gtwcebwthe.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hammf.cn/Article/details/gtypmejwot.html

[S57] C++：编译期常量
来源：http://dali.birdmap.top/Article/details/gtpmanmghz.html

constexpr int N = 10;
来源：http://dali.zhengqikj.top/Article/details/gtsmclzuoq.html

[S58] C++：命名空间
来源：http://dali.zdqjudy.top/Article/details/gtnveaitdt.html

namespace ns { int f() { return 1; } }
来源：http://dali.zycfv.cn/Article/details/gtfzxqocdn.html

[S59] C++：静态断言
来源：http://dali.sxryk.cn/Article/details/gtxeijzxgd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xuetiantiany.cn/Article/details/gtockymecp.html

[S60] C++：遍历并删除元素
来源：http://dali.yangfankeji.com/Article/details/gtlabqdfaw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zycfv.cn/Article/details/gtkgfdxbxs.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtpdyylijw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jianghu66.top/Article/details/gtokiwtjjx.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtsodwtyfe.html

[T01] Kotlin：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtqfntfvfr.html

println("Hello")
来源：http://dali.zycfv.cn/Article/details/gtqqeliuhk.html

[T02] Kotlin：变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpvfarkmx.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.aibaodan.cn/Article/details/gtzeywjxpu.html

[T03] Kotlin：字符串模板
来源：http://dali.yangfankeji.com/Article/details/gtkwxymcjd.html

"值: $b"
来源：http://dali.hongshengwenyu.top/Article/details/gtatzdjonc.html

[T04] Kotlin：空安全
来源：http://dali.wangdashe.top/Article/details/gtrxcvzuqm.html

val n: String? = null;  n?.length
来源：http://dali.zdqjudy.top/Article/details/gtpcuyhade.html

[T05] Kotlin：when 表达式
来源：http://dali.dianchejie.cn/Article/details/gthjmezyyb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtphrqphkb.html

[T06] Kotlin：集合映射
来源：http://dali.snrcjt.cn/Article/details/gtmqofdygd.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sxryk.cn/Article/details/gtaxtefejy.html

[T07] Kotlin：集合过滤
来源：http://dali.xuetiantiany.cn/Article/details/gtsnkcbbyc.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.nanxuanxn.top/Article/details/gtagefxios.html

[T08] Kotlin：数据类
来源：http://dali.0kj1m.cn/Article/details/gtlrgdhkdd.html

data class User(val name: String, val age: Int)
来源：http://dali.zhoulong.xyz/Article/details/gtrtxgwzeg.html

[T09] Kotlin：扩展函数
来源：http://dali.haohaochexian.top/Article/details/gthtiqybtd.html

fun String.exclaim() = this + "!"
来源：http://dali.chenzaomai.com/Article/details/gttdrwmcqd.html

[T10] Kotlin：默认参数
来源：http://dali.9152youxi.cn/Article/details/gtqdwtpchu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.svipenyu.cn/Article/details/gtcpxgsnjl.html

[T11] Kotlin：协程
来源：http://dali.cucudq.cn/Article/details/gtazjwsaxi.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xinyue.icu/Article/details/gtdmskqhhy.html

[T12] Kotlin：解构声明
来源：http://dali.yuxming.cn/Article/details/gtutsfrwwo.html

val (a, b) = Pair(1, 2)
来源：http://dali.xuanzx.com/Article/details/gtlvdfohlm.html

[T13] Kotlin：只读 Map
来源：http://dali.dianchejie.cn/Article/details/gtyyuvwdxx.html

val m = mapOf("a" to 1)
来源：http://dali.yonumen.top/Article/details/gtgriagtqf.html

[T14] Kotlin：循环
来源：http://dali.jinqigufen.top/Article/details/gtilaodlaf.html

for (i in 1..10) println(i)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtychzbkry.html

[T15] Kotlin：接口
来源：http://dali.xuanzx.com/Article/details/gtchsazrib.html

interface Shape { fun area(): Double }
来源：http://dali.tanke756.top/Article/details/gtlbpufcbr.html

[T16] Swift：Hello World
来源：http://dali.bjfxy.top/Article/details/gtsqcyodgd.html

print("Hello")
来源：http://dali.jinqigfzy.top/Article/details/gtpubzqfzp.html

[T17] Swift：变量与常量
来源：http://dali.ehwqpu.com/Article/details/gtfzhuipgv.html

var a = 1;  let b = 2
来源：http://dali.svipenyu.cn/Article/details/gtexfbizbq.html

[T18] Swift：字符串插值
来源：http://dali.yonumen.top/Article/details/gtckovqiyz.html

"值: \(b)"
来源：http://dali.yj20258888.top/Article/details/gtchhpdlll.html

[T19] Swift：可选绑定
来源：http://dali.redwolf501.top/Article/details/gtropiinoi.html

if let n = opt { print(n) }
来源：http://dali.316326.xyz/Article/details/gtgybevwwo.html

[T20] Swift：数组操作
来源：http://dali.hysaishi.cn/Article/details/gtlpotihwk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zdqjudy.top/Article/details/gtkpmdagte.html

[T21] Swift：遍历
来源：http://dali.meibo888.top/Article/details/gtwgnhniij.html

for x in a { print(x) }
来源：http://dali.xziqi.cn/Article/details/gttsbeshfv.html

[T22] Swift：字典
来源：http://dali.yj20258.top/Article/details/gtrpowgviz.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhijiandao.cn/Article/details/gtqvxywzqq.html

[T23] Swift：函数
来源：http://dali.jianghu66.top/Article/details/gttdofhqsf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.chenzaomai.com/Article/details/gteujvfnyy.html

[T24] Swift：闭包
来源：http://dali.wangshuangyany.cn/Article/details/gtohqpbhat.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.snrcjt.cn/Article/details/gtishcacfc.html

[T25] Swift：结构体
来源：http://dali.xuanzx.com/Article/details/gtfgzhajsp.html

struct P { var x: Int }
来源：http://dali.nwbrower.top/Article/details/gtggyrxnfo.html

[T26] Swift：类与重写
来源：http://dali.haohaochexian.top/Article/details/gthscmlhjv.html

class A: Base { override func f() {} }
来源：http://dali.sweek.top/Article/details/gtszlvvkfd.html

[T27] Swift：错误处理
来源：http://dali.chenjidiqi.icu/Article/details/gtxftdkchu.html

do { try f() } catch { print(error) }
来源：http://dali.gzhubu.top/Article/details/gtjkdxapmi.html

[T28] Swift：枚举
来源：http://dali.cashguo.top/Article/details/gtzchrwocc.html

enum Color { case red, green }
来源：http://dali.cucudq.cn/Article/details/gtczjdekmv.html

[T29] Swift：guard 提前返回
来源：http://dali.svipenyu.cn/Article/details/gtgibqdyru.html

guard let x = opt else { return }
来源：http://dali.zhijiandao.cn/Article/details/gtuvsziegs.html

[T30] Swift：协议
来源：http://dali.vqdsnc.cn/Article/details/gtawekcxlr.html

protocol Shape { func area() -> Double }
来源：http://dali.yvedp.cn/Article/details/gtbfcsiadc.html

[T31] Lua：Hello World
来源：http://dali.gzhubu.top/Article/details/gtlwtrdpjh.html

print("Hello")
来源：http://dali.gogol.net.cn/Article/details/gtzexzuhjb.html

[T32] Lua：局部变量
来源：http://dali.daxiang520.top/Article/details/gtvpgnfvyb.html

local a = 1
来源：http://dali.xinyue.icu/Article/details/gtdtfqczsf.html

[T33] Lua：表（数组）
来源：http://dali.yonumen.top/Article/details/gtgcteaera.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jianghu66.top/Article/details/gthdpumqxm.html

[T34] Lua：遍历表
来源：http://dali.jianghu66.top/Article/details/gtssqodevm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkntochly.html

[T35] Lua：字典表
来源：http://dali.daxiang520.top/Article/details/gtqrttccox.html

local d = { a = 1 };  d.b = 2
来源：http://dali.tian-w.cn/Article/details/gtuixutokb.html

[T36] Lua：函数
来源：http://dali.jinqigufen.top/Article/details/gtxpcrclar.html

function add(a, b) return a + b end
来源：http://dali.guannengcc.top/Article/details/gtxlutprpk.html

[T37] Lua：字符串拼接
来源：http://dali.chenjidiqi.icu/Article/details/gteftbqwit.html

"a" .. "b"
来源：http://dali.9152youxi.cn/Article/details/gtepohodqz.html

[T38] Lua：条件
来源：http://dali.yuanzhike.top/Article/details/gtjrmqptpn.html

if x > 0 then print("正") end
来源：http://dali.quarkkingdee.top/Article/details/gtpsredtkx.html

[T39] Lua：模式匹配
来源：http://dali.jyoumei.cn/Article/details/gtnbehjehu.html

string.find(s, "%d+")
来源：http://dali.zhixingplan.top/Article/details/gtwntvrwen.html

[T40] Lua：元表
来源：http://dali.nanxinkj.top/Article/details/gtzvelmlbe.html

setmetatable({}, { __index = base })
来源：http://dali.pycfn.com/Article/details/gtqcwbeqdm.html

[T41] Perl：Hello World
来源：http://dali.xuanzx.com/Article/details/gtjyyadwan.html

print "Hello\n";
来源：http://dali.zhiwuduotai.top/Article/details/gtashimavk.html

[T42] Perl：变量类型
来源：http://dali.c1oappe.top/Article/details/gtayhkeksq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.redwolf501.top/Article/details/gtxymixypc.html

[T43] Perl：字符串插值
来源：http://dali.andypj.xyz/Article/details/gtbwbinpfc.html

"值: $a"
来源：http://dali.hfpthk.cn/Article/details/gtkelaxkxc.html

[T44] Perl：条件
来源：http://dali.tianlin.xyz/Article/details/gtqmzfbosl.html

if ($a > 0) { print "正"; }
来源：http://dali.dianchejie.cn/Article/details/gttglokazm.html

[T45] Perl：数组遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzkoivdfi.html

for my $x (@arr) { print $x; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtcakcncmp.html

[T46] Perl：哈希操作
来源：http://dali.birdmap.top/Article/details/gtrnnxhwfd.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gttlliybdt.html

[T47] Perl：正则捕获
来源：http://dali.zhijiandao.cn/Article/details/gtogwnrwma.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtgswembkb.html

[T48] Perl：正则替换
来源：http://dali.iojbl.cn/Article/details/gttkeoleqb.html

$s =~ s/old/new/g;
来源：http://dali.ppjwa.cn/Article/details/gttyxtbqnp.html

[T49] Perl：函数
来源：http://dali.dianchejie.cn/Article/details/gtsipwjfhz.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.snrcjt.cn/Article/details/gtfkkruyhu.html

[T50] Perl：逐行读文件
来源：http://dali.quarkkingdee.top/Article/details/gthiernbbj.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.jianghu66.top/Article/details/gtuoxjfopg.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.gogol.net.cn/Article/details/gtmcgfuipc.html

[T51] Scala：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmnccbnxg.html

println("Hello")
来源：http://dali.zhixingplan.top/Article/details/gtandakblu.html

[T52] Scala：变量
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwzcosotf.html

val a = 1;  var b = 2
来源：http://dali.jinqigfzy.top/Article/details/gtnavielij.html

[T53] Scala：字符串插值
来源：http://dali.daria6918.cn/Article/details/gtrcinobhy.html

s"值: $b"
来源：http://dali.yueranfly.top/Article/details/gtkhltrifz.html

[T54] Scala：集合映射
来源：http://dali.zhixingplan.top/Article/details/gtycokfrsp.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.snrcjt.cn/Article/details/gtfoxlheme.html

[T55] Scala：集合过滤
来源：http://dali.jinqigufen.top/Article/details/gtuestdfwx.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xinyue.icu/Article/details/gtamdajnej.html

[T56] Scala：样例类
来源：http://dali.jlsjyb.cn/Article/details/gtjcbdofnb.html

case class User(name: String, age: Int)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvisqgxlf.html

[T57] Scala：模式匹配
来源：http://dali.mhx1999.top/Article/details/gtlhkjvylf.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.aibaodan.cn/Article/details/gtjnxchgfh.html

[T58] Scala：函数定义
来源：http://dali.ehwqpu.com/Article/details/gtfokrngzj.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.gotoacloud.top/Article/details/gtuuawezge.html

[T59] Scala：循环
来源：http://dali.cheryme.top/Article/details/gtrhiuozmk.html

for (i <- 1 to 10) println(i)
来源：http://dali.redwolf501.top/Article/details/gtwduidzsj.html

[T60] Scala：折叠
来源：http://dali.haohaochexian.top/Article/details/gtsykvrvdp.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.hnxiangtu.top/Article/details/gtfpuoytbt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtoevpvrts.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.yuxming.cn/Article/details/gttftklhfq.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gthospmdvo.html


<!-- 参考信息 -->