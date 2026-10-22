代发 wailian999

free -h;  ps aux | grep nginx
来源：http://dali.hywenlv.cn/Article/details/gt2ydvelefs.html

[R64] 结束进程
来源：http://dali.ehwqpu.com/Article/details/gt2mzheetly.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yanxiufei.cn/Article/details/gt2eoinvdun.html

[R65] 查看端口占用
来源：http://dali.andypj.xyz/Article/details/gt2patgicuy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.fengsongda.top/Article/details/gt2gnzniprb.html

[R66] 定时任务
来源：http://dali.aibaodan.cn/Article/details/gt2oocbahkf.html

crontab -e;  crontab -l
来源：http://dali.jinqigfzy.top/Article/details/gt2ybbeckdt.html

[R67] 生成随机十六进制串
来源：http://dali.snrcjt.cn/Article/details/gt2tbnkyobf.html

openssl rand -hex 16
来源：http://dali.cdnleiting.top/Article/details/gt2qfuhrdgk.html

[R68] 计算文件校验值
来源：http://dali.yonumen.top/Article/details/gt2beuewljr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.andypj.xyz/Article/details/gt2zamyllzj.html

[R69] 生成随机密码
来源：http://dali.svipenyu.cn/Article/details/gt2jfvillwu.html

head -c 16 /dev/urandom | base64
来源：http://dali.sweek.top/Article/details/gt2qkmlqoai.html

[R70] 时间戳与互转
来源：http://dali.zycfv.cn/Article/details/gt2eueevjqm.html

date +%s;  date -d @1700000000
来源：http://dali.chenjidiqi.icu/Article/details/gt2awmassjs.html

[R71] 日期格式化
来源：http://dali.fzhhl.top/Article/details/gt2begbvhix.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gaohongyu789.top/Article/details/gt2gnyyhvqg.html

[R72] 等待端口就绪
来源：http://dali.cqqwz.cn/Article/details/gt2bqemtknp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yonumen.top/Article/details/gt2tbnpkpfn.html

[R73] 分割大日志
来源：http://dali.zhongyouzk.top/Article/details/gt2zvsvgzdk.html

split -l 1000 big.log part_
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2rxtcorkp.html

[R74] 批量重命名
来源：http://dali.shzxlz.cn/Article/details/gt2ewxhwzke.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xylfe.cn/Article/details/gt2jmknrisn.html

[R75] 导出环境变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2lskgsqnm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hnxiangtu.top/Article/details/gt2vicpdkhq.html

[R76] 使用临时文件
来源：http://dali.nanxinkj.top/Article/details/gt2cjjxigbh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jianghu66.top/Article/details/gt2cmgbdeuf.html

[R77] 读取用户输入
来源：http://dali.xziqi.cn/Article/details/gt2wmrvkpka.html

read -rp "请输入: " ans
来源：http://dali.shanyushiyangtech.top/Article/details/gt2njokpuio.html

[R78] 交互式菜单
来源：http://dali.daxiang520.top/Article/details/gt2nygzlzpt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shzxlz.cn/Article/details/gt2dbisxrgb.html

[R79] 解析命令行选项
来源：http://dali.hysaishi.cn/Article/details/gt2rpzaxgnq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.nanxuanxn.top/Article/details/gt2qbzaxahs.html

[R80] 查看脚本执行耗时
来源：http://dali.jianghu66.top/Article/details/gt2tglbmkxn.html

time ./run.sh
来源：http://dali.chenjidiqi.icu/Article/details/gt2puwgsjkj.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2jondnqpi.html

S. C / C++ 专题
来源：http://dali.zycfv.cn/Article/details/gt2bcfwftsb.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gt2rylvscer.html

[S01] C：Hello World
来源：http://dali.yj20258.top/Article/details/gt2onzagjlw.html

#include <stdio.h>
来源：http://dali.xuetiantiany.cn/Article/details/gt2qictftqd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xnwrbkej.html

[S02] C：变量与格式化输出
来源：http://dali.dianchejie.cn/Article/details/gt2rfzuuikc.html

int a = 10; printf("%d\n", a);
来源：http://dali.sweek.top/Article/details/gt2fmktwuqr.html

[S03] C：读入整数
来源：http://dali.zhoulong.xyz/Article/details/gt2fknzhrvr.html

int x; scanf("%d", &x);
来源：http://dali.feifeiyinyue.top/Article/details/gt2xcfzjuez.html

[S04] C：字符串复制
来源：http://dali.zhixingplan.top/Article/details/gt2tbhjahwh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhengqikj.top/Article/details/gt2cxakoifq.html

[S05] C：字符串长度
来源：http://dali.yuxming.cn/Article/details/gt2vkplgqys.html

strlen(s)
来源：http://dali.aizwys.cn/Article/details/gt2hmizfyau.html

[S06] C：字符串比较
来源：http://dali.jqgufenzy.top/Article/details/gt2ipipuyjd.html

strcmp(a, b) == 0
来源：http://dali.sxryk.cn/Article/details/gt2zftsrkgv.html

[S07] C：数组遍历求和
来源：http://dali.hongshengwenyu.top/Article/details/gt2jktnqsuz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.daria6918.cn/Article/details/gt2afkacfmj.html

[S08] C：动态内存分配与释放
来源：http://dali.ybcxt.top/Article/details/gt2ccxwrkgn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hysaishi.cn/Article/details/gt2wosqcdfz.html

[S09] C：结构体定义与初始化
来源：http://dali.yonumen.top/Article/details/gt2fqhzavpz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hammf.cn/Article/details/gt2qnspoxej.html

[S10] C：指针与解引用
来源：http://dali.jyoumei.cn/Article/details/gt2mctscxub.html

int *p = &a;  *p = 5;
来源：http://dali.redwolf501.top/Article/details/gt2mqslgyfa.html

[S11] C：逐行读文件
来源：http://dali.yongpay.top/Article/details/gt2dgegsxxw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yuxming.cn/Article/details/gt2yxezlzhx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cqqwz.cn/Article/details/gt2elcuucgb.html

fclose(f);
来源：http://dali.cashguo.top/Article/details/gt2zgriullp.html

[S12] C：写文件
来源：http://dali.sufxvd.cn/Article/details/gt2mfbmfmfj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yongpay.top/Article/details/gt2sapncyln.html

[S13] C：宏定义
来源：http://dali.gogol.net.cn/Article/details/gt2ldouuxve.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhongyouzk.top/Article/details/gt2pnlamvlq.html

[S14] C：枚举
来源：http://dali.nwbrower.top/Article/details/gt2bjcagnef.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.havefunace.top/Article/details/gt2btrkxoph.html

[S15] C：类型转换
来源：http://dali.yuanzhike.top/Article/details/gt2qatelmhe.html

(double) a / b
来源：http://dali.jiagoushi.top/Article/details/gt2ywdsxqsx.html

[S16] C：位操作置位
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qmorphes.html

x |= (1 << 3);
来源：http://dali.xuanzx.com/Article/details/gt2hihvozsy.html

[S17] C：安全拼接字符串
来源：http://dali.meibo888.top/Article/details/gt2ekondokn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.mhx1999.top/Article/details/gt2yahgnvih.html

[S18] C：命令行参数
来源：http://dali.zhiwuduotai.top/Article/details/gt2svlcjepm.html

int main(int argc, char **argv)
来源：http://dali.yangfankeji.com/Article/details/gt2pejydkrx.html

[S19] C：快速排序
来源：http://dali.iojbl.cn/Article/details/gt2eyxqlmno.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.sysykeji.top/Article/details/gt2lyodxfwt.html

[S20] C：二分查找
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2gccqionc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gt2jqxyxtut.html

[S21] C：字符类别判断
来源：http://dali.zhengqikj.top/Article/details/gt2dgxkeawx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sweek.top/Article/details/gt2zfuxkxdm.html

[S22] C：字符串转数字
来源：http://dali.zhixingplan.top/Article/details/gt2uetsljyx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xinyue.icu/Article/details/gt2qztwkgwj.html

[S23] C：随机数
来源：http://dali.cqqwz.cn/Article/details/gt2mbcmxsfl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2yvhqhbje.html

[S24] C：获取本地时间
来源：http://dali.hammf.cn/Article/details/gt2cswnchss.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zycfv.cn/Article/details/gt2osbandxl.html

[S25] C：内存拷贝
来源：http://dali.zhongyouzk.top/Article/details/gt2dmpdxhkj.html

memcpy(dst, src, n);
来源：http://dali.zhiwuduotai.top/Article/details/gt2vkkhhqyd.html

[S26] C：内存清零
来源：http://dali.yueranfly.top/Article/details/gt2frwkkydy.html

memset(a, 0, sizeof a);
来源：http://dali.zhiwuduotai.top/Article/details/gt2hqlqarsm.html

[S27] C：定义常量
来源：http://dali.xziqi.cn/Article/details/gt2rmygebln.html

const double PI = 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gt2dmhpodhp.html

[S28] C：静态变量
来源：http://dali.wangshuangyany.cn/Article/details/gt2snjcktex.html

static int counter = 0;
来源：http://dali.gaohongyu789.top/Article/details/gt2xavogmak.html

[S29] C：变参函数
来源：http://dali.tian-w.cn/Article/details/gt2azpfukau.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sufxvd.cn/Article/details/gt2taxkgkuu.html

[S30] C：头文件保护
来源：http://dali.cucudq.cn/Article/details/gt2dnvbzpnk.html

#ifndef X_H
来源：http://dali.tian-w.cn/Article/details/gt2ehqnfclz.html

#define X_H
来源：http://dali.yj20258.top/Article/details/gt2edxgmgzj.html

#endif
来源：http://dali.iojbl.cn/Article/details/gt2fuhudwrb.html

[S31] C++：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gt2eotngpoz.html

#include <iostream>
来源：http://dali.yj20258888.top/Article/details/gt2otdhmesw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gzhubu.top/Article/details/gt2mqedhbse.html

[S32] C++：字符串
来源：http://dali.dashuyun.cn/Article/details/gt2ixtzjhse.html

std::string s = "hi";  s += "!";
来源：http://dali.yueranfly.top/Article/details/gt2mlvxpojm.html

[S33] C++：vector 增删
来源：http://dali.chenzaomai.com/Article/details/gt2xwugynsu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.birdmap.top/Article/details/gt2opgbnkly.html

[S34] C++：遍历 vector
来源：http://dali.zhixingplan.top/Article/details/gt2lrviegsr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.daxiang520.top/Article/details/gt2ylsmbypd.html

[S35] C++：map
来源：http://dali.dashuyun.cn/Article/details/gt2doeyfhmd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hammf.cn/Article/details/gt2txpfgrkc.html

[S36] C++：unordered_map
来源：http://dali.redwolf501.top/Article/details/gt2bwjzmziu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aizwys.cn/Article/details/gt2sraaimbh.html

[S37] C++：set
来源：http://dali.gaohongyu789.top/Article/details/gt2gtvkfiwy.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.haohaochexian.top/Article/details/gt2oczaawrw.html

[S38] C++：排序
来源：http://dali.dashuyun.cn/Article/details/gt2ptsghtrp.html

std::sort(v.begin(), v.end());
来源：http://dali.hongshengwenyu.top/Article/details/gt2hqnimchz.html

[S39] C++：自定义比较器排序
来源：http://dali.xuetiantiany.cn/Article/details/gt2vcmfhgcm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ivvv.top/Article/details/gt2zoyarmfi.html

[S40] C++：查找元素
来源：http://dali.chenlongwang.top/Article/details/gt2kihbyuhz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2owqbkjxm.html

[S41] C++：类与构造函数
来源：http://dali.sufxvd.cn/Article/details/gt2praadiss.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yvedp.cn/Article/details/gt2svjgczbo.html

[S42] C++：继承与虚函数
来源：http://dali.smart0.xyz/Article/details/gt2jcfmnxki.html

class B : public Base { public: void f() override {} };
来源：http://dali.cashguo.top/Article/details/gt2ddmqdmyj.html

[S43] C++：智能指针
来源：http://dali.nanxinkj.top/Article/details/gt2dsqwucgm.html

auto p = std::make_unique<int>(5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nwlnkmef.html

[S44] C++：引用传参
来源：http://dali.aibaodan.cn/Article/details/gt2zmjqxhab.html

void inc(int &x) { ++x; }
来源：http://dali.gogol.net.cn/Article/details/gt2otqnyylj.html

[S45] C++：lambda
来源：http://dali.nwbrower.top/Article/details/gt2ttsmdsna.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nanxinkj.top/Article/details/gt2qmrdisdn.html

[S46] C++：函数模板
来源：http://dali.tianlin.xyz/Article/details/gt2lmdhufrj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.haohaochexian.top/Article/details/gt2wcnsluny.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinqigufen.top/Article/details/gt2ysbafobh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xinyue.icu/Article/details/gt2beqbdwhd.html

[S48] C++：逐行读文件
来源：http://dali.iojbl.cn/Article/details/gt2nloqfdsb.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jyoumei.cn/Article/details/gt2fufxxhid.html

while (std::getline(in, line)) { }
来源：http://dali.zhiwuduotai.top/Article/details/gt2oxlunail.html

[S49] C++：写文件
来源：http://dali.kuanghao11.cn/Article/details/gt2icwhichb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xziqi.cn/Article/details/gt2nendnofh.html

[S50] C++：格式化数字
来源：http://dali.yangfankeji.com/Article/details/gt2ailuietb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2xkczkhbj.html

[S51] C++：显式类型转换
来源：http://dali.gaohongyu789.top/Article/details/gt2bydyymru.html

static_cast<double>(a) / b
来源：http://dali.pycfn.com/Article/details/gt2rikxhnnc.html

[S52] C++：const 与 noexcept
来源：http://dali.jqgfzy.top/Article/details/gt2zapuppkm.html

int size() const noexcept { return n_; }
来源：http://dali.iojbl.cn/Article/details/gt2ssapsmmo.html

[S53] C++：移动语义
来源：http://dali.nwbrower.top/Article/details/gt2gpnjhcob.html

std::vector<int> w = std::move(v);
来源：http://dali.shangyingyoupin.top/Article/details/gt2qhjhlpag.html

[S54] C++：异常处理
来源：http://dali.0kj1m.cn/Article/details/gt2qlbooxoe.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yonumen.top/Article/details/gt2gjkjwknj.html

[S55] C++：结构化绑定
来源：http://dali.pycfn.com/Article/details/gt2vbsytlfe.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yonumen.top/Article/details/gt2njrscsdk.html

[S56] C++：optional
来源：http://dali.aizwys.cn/Article/details/gt2jolopfru.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ivvv.top/Article/details/gt2znqrtvja.html

[S57] C++：编译期常量
来源：http://dali.snrcjt.cn/Article/details/gt2aluxlrrb.html

constexpr int N = 10;
来源：http://dali.cdnleiting.top/Article/details/gt2eslpakif.html

[S58] C++：命名空间
来源：http://dali.bjfxy.top/Article/details/gt2dddsdlfp.html

namespace ns { int f() { return 1; } }
来源：http://dali.jiagoushi.top/Article/details/gt2rnbeeszk.html

[S59] C++：静态断言
来源：http://dali.hysaishi.cn/Article/details/gt2efsmfzha.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.wangdashe.top/Article/details/gt2zliwnnxg.html

[S60] C++：遍历并删除元素
来源：http://dali.yonumen.top/Article/details/gt2wepaugav.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sweek.top/Article/details/gt2yzxetufe.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2hiextqcb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.fzhhl.top/Article/details/gt2vnwogevi.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gt2oglbontd.html

[T01] Kotlin：Hello World
来源：http://dali.tianlin.xyz/Article/details/gt2ucqrxtlk.html

println("Hello")
来源：http://dali.zhoulong.xyz/Article/details/gt2oqkvvszo.html

[T02] Kotlin：变量
来源：http://dali.jianghu66.top/Article/details/gt2rszelffp.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pcgpaotz.html

[T03] Kotlin：字符串模板
来源：http://dali.hnxiangtu.top/Article/details/gt2xvznidhi.html

"值: $b"
来源：http://dali.andypj.xyz/Article/details/gt2jyruorbo.html

[T04] Kotlin：空安全
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2othvvjts.html

val n: String? = null;  n?.length
来源：http://dali.hywenlv.cn/Article/details/gt2icxkgodh.html

[T05] Kotlin：when 表达式
来源：http://dali.yj20258.top/Article/details/gt2xszsouot.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.birdmap.top/Article/details/gt2khmycdzz.html

[T06] Kotlin：集合映射
来源：http://dali.shangyingyoupin.top/Article/details/gt2aggbgdgp.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hfpthk.cn/Article/details/gt2dojzduqb.html

[T07] Kotlin：集合过滤
来源：http://dali.hywenlv.cn/Article/details/gt2niktihyj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.tanke756.top/Article/details/gt2bvrdiehl.html

[T08] Kotlin：数据类
来源：http://dali.hnxiangtu.top/Article/details/gt2ggjwhhwm.html

data class User(val name: String, val age: Int)
来源：http://dali.mhx1999.top/Article/details/gt2epkvdvus.html

[T09] Kotlin：扩展函数
来源：http://dali.c1oappe.top/Article/details/gt2bbegdzzj.html

fun String.exclaim() = this + "!"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2jmfoqrbt.html

[T10] Kotlin：默认参数
来源：http://dali.tian-w.cn/Article/details/gt2bmjdkwbo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yongpay.top/Article/details/gt2yzipqhrf.html

[T11] Kotlin：协程
来源：http://dali.haohaochexian.top/Article/details/gt2sppljuiy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.mhx1999.top/Article/details/gt2gojibyed.html

[T12] Kotlin：解构声明
来源：http://dali.ehwqpu.com/Article/details/gt2wrsewrgk.html

val (a, b) = Pair(1, 2)
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2uutfwmfn.html

[T13] Kotlin：只读 Map
来源：http://dali.chenlongwang.top/Article/details/gt2dwvwetxn.html

val m = mapOf("a" to 1)
来源：http://dali.zhixingplan.top/Article/details/gt2fxgbglre.html

[T14] Kotlin：循环
来源：http://dali.xinyue.icu/Article/details/gt2mzdcsofw.html

for (i in 1..10) println(i)
来源：http://dali.smart0.xyz/Article/details/gt2xtwcvwno.html

[T15] Kotlin：接口
来源：http://dali.yongpay.top/Article/details/gt2rmnnruam.html

interface Shape { fun area(): Double }
来源：http://dali.xinyue.icu/Article/details/gt2ihsrteix.html

[T16] Swift：Hello World
来源：http://dali.bjfxy.top/Article/details/gt2shnskjse.html

print("Hello")
来源：http://dali.pengpengdd.cyou/Article/details/gt2stfljahq.html

[T17] Swift：变量与常量
来源：http://dali.jlsjyb.cn/Article/details/gt2cmgaeovm.html

var a = 1;  let b = 2
来源：http://dali.meibo888.top/Article/details/gt2ybqeunct.html

[T18] Swift：字符串插值
来源：http://dali.shangyingyoupin.top/Article/details/gt2ctefybdi.html

"值: \(b)"
来源：http://dali.ydzc1.top/Article/details/gt2jhnaefqr.html

[T19] Swift：可选绑定
来源：http://dali.aibaodan.cn/Article/details/gt2cdczsfue.html

if let n = opt { print(n) }
来源：http://dali.yuxming.cn/Article/details/gt2kduxbgpu.html

[T20] Swift：数组操作
来源：http://dali.ybcxt.top/Article/details/gt2nqjglztk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.svipenyu.cn/Article/details/gt2ldufdzls.html

[T21] Swift：遍历
来源：http://dali.hfpthk.cn/Article/details/gt2krxqbreg.html

for x in a { print(x) }
来源：http://dali.0kj1m.cn/Article/details/gt2aztdsjjg.html

[T22] Swift：字典
来源：http://dali.xuanzx.com/Article/details/gt2jyfmvccg.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.tanke756.top/Article/details/gt2hxytryrg.html

[T23] Swift：函数
来源：http://dali.vqdsnc.cn/Article/details/gt2xmqnpkoh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhiwuduotai.top/Article/details/gt2xravtemz.html

[T24] Swift：闭包
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2bqfdxzry.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yanxiufei.cn/Article/details/gt2qnfrrgor.html

[T25] Swift：结构体
来源：http://dali.yanxiufei.cn/Article/details/gt2ulfixwac.html

struct P { var x: Int }
来源：http://dali.chenlongwang.top/Article/details/gt2eixnutdk.html

[T26] Swift：类与重写
来源：http://dali.nwbrower.top/Article/details/gt2mvhwfubt.html

class A: Base { override func f() {} }
来源：http://dali.zycfv.cn/Article/details/gt2yguatnic.html

[T27] Swift：错误处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2hobqjnxr.html

do { try f() } catch { print(error) }
来源：http://dali.havefunace.top/Article/details/gt2poonmdwz.html

[T28] Swift：枚举
来源：http://dali.jyoumei.cn/Article/details/gt2ywjsmxvn.html

enum Color { case red, green }
来源：http://dali.ehwqpu.com/Article/details/gt2ivehgxua.html

[T29] Swift：guard 提前返回
来源：http://dali.tianlin.xyz/Article/details/gt2ygaaniwl.html

guard let x = opt else { return }
来源：http://dali.mhx1999.top/Article/details/gt2twdbmlws.html

[T30] Swift：协议
来源：http://dali.cheryme.top/Article/details/gt2rmimzuvy.html

protocol Shape { func area() -> Double }
来源：http://dali.hongshengwenyu.top/Article/details/gt2wtkadudc.html

[T31] Lua：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gt2djqzqlzv.html

print("Hello")
来源：http://dali.smart0.xyz/Article/details/gt2retxomqg.html

[T32] Lua：局部变量
来源：http://dali.ppjwa.cn/Article/details/gt2mqjovjtm.html

local a = 1
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ihmmomvx.html

[T33] Lua：表（数组）
来源：http://dali.ivvv.top/Article/details/gt2dkvhiupz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.guowangkeji.top/Article/details/gt2utartzee.html

[T34] Lua：遍历表
来源：http://dali.hnxiangtu.top/Article/details/gt2cjupdkxx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2trzgqeed.html

[T35] Lua：字典表
来源：http://dali.hfpthk.cn/Article/details/gt2qvdmqdcw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.haohaochexian.top/Article/details/gt2mykmexjw.html

[T36] Lua：函数
来源：http://dali.jlsjyb.cn/Article/details/gt2cwumqwum.html

function add(a, b) return a + b end
来源：http://dali.smart0.xyz/Article/details/gt2jfvvlkmp.html

[T37] Lua：字符串拼接
来源：http://dali.9152youxi.cn/Article/details/gt2bnighthh.html

"a" .. "b"
来源：http://dali.jinqigfzy.top/Article/details/gt2ybvhegko.html

[T38] Lua：条件
来源：http://dali.xziqi.cn/Article/details/gt2iotetpff.html

if x > 0 then print("正") end
来源：http://dali.nwbrower.top/Article/details/gt2eazgllgk.html

[T39] Lua：模式匹配
来源：http://dali.jianghu66.top/Article/details/gt2ymekynzb.html

string.find(s, "%d+")
来源：http://dali.shzxlz.cn/Article/details/gt2mdiferor.html

[T40] Lua：元表
来源：http://dali.sweek.top/Article/details/gt2udbqtpoy.html

setmetatable({}, { __index = base })
来源：http://dali.quarkkingdee.top/Article/details/gt2cvoaklob.html

[T41] Perl：Hello World
来源：http://dali.cucudq.cn/Article/details/gt2rouwebeo.html

print "Hello\n";
来源：http://dali.ydzc1.top/Article/details/gt2yhrsdnnf.html

[T42] Perl：变量类型
来源：http://dali.dashuyun.cn/Article/details/gt2wurpusgi.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.smart0.xyz/Article/details/gt2iiencdfu.html

[T43] Perl：字符串插值
来源：http://dali.yvedp.cn/Article/details/gt2bfypzzrs.html

"值: $a"
来源：http://dali.zhengqikj.top/Article/details/gt2gesgacyc.html

[T44] Perl：条件
来源：http://dali.chenjidiqi.icu/Article/details/gt2miqfwcjr.html

if ($a > 0) { print "正"; }
来源：http://dali.hammf.cn/Article/details/gt2aoccmgta.html

[T45] Perl：数组遍历
来源：http://dali.nanxuanxn.top/Article/details/gt2gdtswtbp.html

for my $x (@arr) { print $x; }
来源：http://dali.jinqigfzy.top/Article/details/gt2gnsqozfz.html

[T46] Perl：哈希操作
来源：http://dali.zhengqikj.top/Article/details/gt2iqgpjmgu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yuanzhike.top/Article/details/gt2jtigaerg.html

[T47] Perl：正则捕获
来源：http://dali.nanxuanxn.top/Article/details/gt2ydfxgzcc.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.0kj1m.cn/Article/details/gt2xlelnkte.html

[T48] Perl：正则替换
来源：http://dali.sysykeji.top/Article/details/gt2jhnlkkiu.html

$s =~ s/old/new/g;
来源：http://dali.xuetiantiany.cn/Article/details/gt2pwvaqeiy.html

[T49] Perl：函数
来源：http://dali.yanxiufei.cn/Article/details/gt2waebvmpx.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.mhx1999.top/Article/details/gt2qenwaoqt.html

[T50] Perl：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jzvjrtmz.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.feifeiyinyue.top/Article/details/gt2muhwfyah.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.haohaochexian.top/Article/details/gt2zapupxiv.html

[T51] Scala：Hello World
来源：http://dali.dashuyun.cn/Article/details/gt2usismefy.html

println("Hello")
来源：http://dali.jinqigufen.top/Article/details/gt2uyeiycrp.html

[T52] Scala：变量
来源：http://dali.yanxiufei.cn/Article/details/gt2qxjmphvl.html

val a = 1;  var b = 2
来源：http://dali.shangyingyoupin.top/Article/details/gt2zfonhipa.html

[T53] Scala：字符串插值
来源：http://dali.feifeiyinyue.top/Article/details/gt2vhffgypt.html

s"值: $b"
来源：http://dali.wangshuangyany.cn/Article/details/gt2mwfsjqrf.html

[T54] Scala：集合映射
来源：http://dali.yonumen.top/Article/details/gt2uairyfod.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.jqgufenzy.top/Article/details/gt2hwmlgueu.html

[T55] Scala：集合过滤
来源：http://dali.jiagoushi.top/Article/details/gt2dsbkxxir.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.hfpthk.cn/Article/details/gt2tlghiwqa.html

[T56] Scala：样例类
来源：http://dali.zdqjudy.top/Article/details/gt2iojakhlc.html

case class User(name: String, age: Int)
来源：http://dali.sxryk.cn/Article/details/gt2uxithmmk.html

[T57] Scala：模式匹配
来源：http://dali.nanxuanxn.top/Article/details/gt2qxzeqjob.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.fengsongda.top/Article/details/gt2chztwgja.html

[T58] Scala：函数定义
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hhxtzuec.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.hammf.cn/Article/details/gt2sawyooxk.html

[T59] Scala：循环
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ydelszjl.html

for (i <- 1 to 10) println(i)
来源：http://dali.pycfn.com/Article/details/gt2kycvumxv.html

[T60] Scala：折叠
来源：http://dali.aibaodan.cn/Article/details/gt2dysaafgn.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2nimeysyt.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gt2mtvobcpk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.dashuyun.cn/Article/details/gt2liqwwpjg.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gt2immabyhb.html

[U01] Py：创建虚拟环境
来源：http://dali.cdnleiting.top/Article/details/gt2fcqbigmq.html

python -m venv .venv && source .venv/bin/activate
来源：http://dali.fengsongda.top/Article/details/gt2hvgfbgjs.html

[U02] Py：导出 / 安装依赖
来源：http://dali.zhiwuduotai.top/Article/details/gt2tpddwjan.html

pip freeze > requirements.txt;  pip install -r requirements.txt
来源：http://dali.dashuyun.cn/Article/details/gt2xnbmmmle.html

[U03] Py：加载 .env 配置
来源：http://dali.daxiang520.top/Article/details/gt2oqxgchmn.html

from dotenv import load_dotenv; load_dotenv()
来源：http://dali.jiagoushi.top/Article/details/gt2whskntvk.html

[U04] Py：变量调试打印
来源：http://dali.hywenlv.cn/Article/details/gt2tyaizsuk.html

print(f"{x=}")            # 输出 x=值，Python 3.8+
来源：http://dali.chenzaomai.com/Article/details/gt2agxaafhe.html


<!-- 参考信息 -->