代发 wailian999

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gaohongyu789.top/Article/details/gtjgcryicf.html

[R60] 只看 HTTP 状态码
来源：http://dali.yonumen.top/Article/details/gtamtnlysp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nanxinkj.top/Article/details/gtbhpvarsg.html

[R61] 磁盘占用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrjgnolut.html

df -h;  du -sh *
来源：http://dali.jianghu66.top/Article/details/gttxuszdrd.html

[R62] 找最占空间的文件
来源：http://dali.guannengcc.top/Article/details/gtfdhebhqt.html

du -ah . | sort -rh | head -10
来源：http://dali.hfpthk.cn/Article/details/gtjistbvcp.html

[R63] 内存与进程
来源：http://dali.hnqzz.top/Article/details/gtvwydcwpt.html

free -h;  ps aux | grep nginx
来源：http://dali.xuetiantiany.cn/Article/details/gtyjxpgwkp.html

[R64] 结束进程
来源：http://dali.gaohongyu789.top/Article/details/gturhuowms.html

kill -9 $(pgrep -f app.py)
来源：http://dali.0kj1m.cn/Article/details/gtqgoppwmw.html

[R65] 查看端口占用
来源：http://dali.zhaomingkeji.xyz/Article/details/gteyywwqcv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.redwolf501.top/Article/details/gtuholftff.html

[R66] 定时任务
来源：http://dali.gogol.net.cn/Article/details/gtnefkyjwp.html

crontab -e;  crontab -l
来源：http://dali.ydzc1.top/Article/details/gtjbfuogrb.html

[R67] 生成随机十六进制串
来源：http://dali.bjfxy.top/Article/details/gtppjnasss.html

openssl rand -hex 16
来源：http://dali.jyoumei.cn/Article/details/gttlnnknwy.html

[R68] 计算文件校验值
来源：http://dali.nwbrower.top/Article/details/gtxjbxtfjk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.redwolf501.top/Article/details/gtqnrcrelc.html

[R69] 生成随机密码
来源：http://dali.daxiang520.top/Article/details/gtmgdywedu.html

head -c 16 /dev/urandom | base64
来源：http://dali.mhx1999.top/Article/details/gtzhmxnwxh.html

[R70] 时间戳与互转
来源：http://dali.hnqzz.top/Article/details/gtgmredswt.html

date +%s;  date -d @1700000000
来源：http://dali.chenjidiqi.icu/Article/details/gtqgmdjtlr.html

[R71] 日期格式化
来源：http://dali.chenjidiqi.icu/Article/details/gtkntmywxh.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gaohongyu789.top/Article/details/gtpxrqhqzs.html

[R72] 等待端口就绪
来源：http://dali.c1oappe.top/Article/details/gtlghfvslj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hfpthk.cn/Article/details/gttamygjpy.html

[R73] 分割大日志
来源：http://dali.aizwys.cn/Article/details/gtxiddmesu.html

split -l 1000 big.log part_
来源：http://dali.yuanzhike.top/Article/details/gtejqzmzud.html

[R74] 批量重命名
来源：http://dali.yuanzhike.top/Article/details/gtszwjryau.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tian-w.cn/Article/details/gtgbexstwr.html

[R75] 导出环境变量
来源：http://dali.cashguo.top/Article/details/gtkdglwhvq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhengqikj.top/Article/details/gtjvxoedqg.html

[R76] 使用临时文件
来源：http://dali.zhixingplan.top/Article/details/gtvlglzokp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jianghu66.top/Article/details/gtlfwvuchz.html

[R77] 读取用户输入
来源：http://dali.svipenyu.cn/Article/details/gtdcfrdcyb.html

read -rp "请输入: " ans
来源：http://dali.xuetiantiany.cn/Article/details/gtcnaqpdqx.html

[R78] 交互式菜单
来源：http://dali.sufxvd.cn/Article/details/gtidpokjzi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jiagoushi.top/Article/details/gtxatkpgfx.html

[R79] 解析命令行选项
来源：http://dali.nanxinkj.top/Article/details/gtibcqlfny.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cheryme.top/Article/details/gteqpcsbyl.html

[R80] 查看脚本执行耗时
来源：http://dali.gogol.net.cn/Article/details/gthdiewcmv.html

time ./run.sh
来源：http://dali.gaohongyu789.top/Article/details/gtffylubye.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtycpqwgde.html

S. C / C++ 专题
来源：http://dali.quarkkingdee.top/Article/details/gtqpxenwid.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gtyjnljqqq.html

[S01] C：Hello World
来源：http://dali.daria6918.cn/Article/details/gtwsxhkhct.html

#include <stdio.h>
来源：http://dali.c1oappe.top/Article/details/gtqmhnwaxa.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xziqi.cn/Article/details/gtrldbnkth.html

[S02] C：变量与格式化输出
来源：http://dali.chenjidiqi.icu/Article/details/gtuoaafczz.html

int a = 10; printf("%d\n", a);
来源：http://dali.shzxlz.cn/Article/details/gtyzegcffp.html

[S03] C：读入整数
来源：http://dali.hnqzz.top/Article/details/gtsqohrxxo.html

int x; scanf("%d", &x);
来源：http://dali.nanxuanxn.top/Article/details/gtxxnbuhfm.html

[S04] C：字符串复制
来源：http://dali.9152youxi.cn/Article/details/gtjzfbmwqy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hnqzz.top/Article/details/gtecgqnare.html

[S05] C：字符串长度
来源：http://dali.mhx1999.top/Article/details/gtbrroupbo.html

strlen(s)
来源：http://dali.aizwys.cn/Article/details/gtxzxceiun.html

[S06] C：字符串比较
来源：http://dali.fzhhl.top/Article/details/gtwxtyaumt.html

strcmp(a, b) == 0
来源：http://dali.aibaodan.cn/Article/details/gtizdykcya.html

[S07] C：数组遍历求和
来源：http://dali.meibo888.top/Article/details/gtpcsvbwkd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xuanzx.com/Article/details/gtjftpawph.html

[S08] C：动态内存分配与释放
来源：http://dali.xuanzx.com/Article/details/gtjyfdcqdf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zycfv.cn/Article/details/gttppuyczj.html

[S09] C：结构体定义与初始化
来源：http://dali.vqdsnc.cn/Article/details/gthebpfnbl.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzhfezpbs.html

[S10] C：指针与解引用
来源：http://dali.aizwys.cn/Article/details/gtbwxineeb.html

int *p = &a;  *p = 5;
来源：http://dali.zhiwuduotai.top/Article/details/gtzqzvrzlq.html

[S11] C：逐行读文件
来源：http://dali.guannengcc.top/Article/details/gtwuazcrmr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gzhubu.top/Article/details/gtaathbsvl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yonumen.top/Article/details/gtdiwhndnv.html

fclose(f);
来源：http://dali.yj202588.top/Article/details/gthxdcpgmn.html

[S12] C：写文件
来源：http://dali.xziqi.cn/Article/details/gtmzotreil.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhongyouzk.top/Article/details/gtphyhtove.html

[S13] C：宏定义
来源：http://dali.dashuyun.cn/Article/details/gtbbmuwkjk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.chenjidiqi.icu/Article/details/gtbspzktkf.html

[S14] C：枚举
来源：http://dali.chenzaomai.com/Article/details/gtkpheyghq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zycfv.cn/Article/details/gttbedbkoh.html

[S15] C：类型转换
来源：http://dali.jyoumei.cn/Article/details/gtpofwbhgz.html

(double) a / b
来源：http://dali.shuidangran.top/Article/details/gtlpgquvsr.html

[S16] C：位操作置位
来源：http://dali.hysaishi.cn/Article/details/gtdworuvpm.html

x |= (1 << 3);
来源：http://dali.zdqjudy.top/Article/details/gtkgtkzopd.html

[S17] C：安全拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gtktdriemj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqbakunqe.html

[S18] C：命令行参数
来源：http://dali.dianchejie.cn/Article/details/gtxbxlgbnx.html

int main(int argc, char **argv)
来源：http://dali.kuanghao11.cn/Article/details/gtsdzihqqf.html

[S19] C：快速排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzgxmsykd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.vqdsnc.cn/Article/details/gtepqsrkyv.html

[S20] C：二分查找
来源：http://dali.andypj.xyz/Article/details/gtagnhkysh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yj20258.top/Article/details/gtbpcmdqrv.html

[S21] C：字符类别判断
来源：http://dali.tanke756.top/Article/details/gtwdygdkiu.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.chenjidiqi.icu/Article/details/gtipkzavco.html

[S22] C：字符串转数字
来源：http://dali.iojbl.cn/Article/details/gtfzplleyc.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sxryk.cn/Article/details/gtmbetkwab.html

[S23] C：随机数
来源：http://dali.tian-w.cn/Article/details/gtwwnlfqet.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzmeknzia.html

[S24] C：获取本地时间
来源：http://dali.hywenlv.cn/Article/details/gtnvnwxwas.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsrfjwjlw.html

[S25] C：内存拷贝
来源：http://dali.zdqjudy.top/Article/details/gtbclzadwi.html

memcpy(dst, src, n);
来源：http://dali.xuetiantiany.cn/Article/details/gtqxzedluj.html

[S26] C：内存清零
来源：http://dali.yangfankeji.com/Article/details/gtfgjzcxpl.html

memset(a, 0, sizeof a);
来源：http://dali.nanxinkj.top/Article/details/gtavvuxjtf.html

[S27] C：定义常量
来源：http://dali.guannengcc.top/Article/details/gtrdomucxg.html

const double PI = 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gtjfeznodr.html

[S28] C：静态变量
来源：http://dali.fengsongda.top/Article/details/gtfnwdvucs.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gttpqeoner.html

[S29] C：变参函数
来源：http://dali.jlsjyb.cn/Article/details/gtmnyyndvt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.tanke756.top/Article/details/gtmnytmrpm.html

[S30] C：头文件保护
来源：http://dali.quarkkingdee.top/Article/details/gtwxabwtty.html

#ifndef X_H
来源：http://dali.zhoulong.xyz/Article/details/gtnqkkxgwh.html

#define X_H
来源：http://dali.yj202588.top/Article/details/gtnewyppri.html

#endif
来源：http://dali.hysaishi.cn/Article/details/gtxguycmow.html

[S31] C++：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtrxkpeepf.html

#include <iostream>
来源：http://dali.sysykeji.top/Article/details/gtmlsojzab.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.daxiang520.top/Article/details/gtcaiyyjui.html

[S32] C++：字符串
来源：http://dali.wangshuangyany.cn/Article/details/gtxfqhurzj.html

std::string s = "hi";  s += "!";
来源：http://dali.redwolf501.top/Article/details/gtzwiaunho.html

[S33] C++：vector 增删
来源：http://dali.jiagoushi.top/Article/details/gtsrksnlmb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.chenlongwang.top/Article/details/gtvffilwuk.html

[S34] C++：遍历 vector
来源：http://dali.cucudq.cn/Article/details/gtyvcnpzeg.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yj202588.top/Article/details/gtnbgpfulk.html

[S35] C++：map
来源：http://dali.sweek.top/Article/details/gtepmjravd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258888.top/Article/details/gtpkfsvlky.html

[S36] C++：unordered_map
来源：http://dali.jinqigfzy.top/Article/details/gtchpvvvrb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgpsrueym.html

[S37] C++：set
来源：http://dali.9152youxi.cn/Article/details/gtddpkqaxw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.dashuyun.cn/Article/details/gtbftyrxrw.html

[S38] C++：排序
来源：http://dali.xinyue.icu/Article/details/gttdogmfij.html

std::sort(v.begin(), v.end());
来源：http://dali.chenjidiqi.icu/Article/details/gtddfyttat.html

[S39] C++：自定义比较器排序
来源：http://dali.chenzaomai.com/Article/details/gtbryhwaty.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shanyushiyangtech.top/Article/details/gtcndjyfxz.html

[S40] C++：查找元素
来源：http://dali.yj20258.top/Article/details/gtvcinwnti.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtheqrbkzg.html

[S41] C++：类与构造函数
来源：http://dali.andypj.xyz/Article/details/gtmvuifwru.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.gzhubu.top/Article/details/gtkutcckel.html

[S42] C++：继承与虚函数
来源：http://dali.yonumen.top/Article/details/gtmepunhhx.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinqigufen.top/Article/details/gtffrtkmvc.html

[S43] C++：智能指针
来源：http://dali.sweek.top/Article/details/gtnumxdkgn.html

auto p = std::make_unique<int>(5);
来源：http://dali.ehwqpu.com/Article/details/gtamqkjzdy.html

[S44] C++：引用传参
来源：http://dali.hammf.cn/Article/details/gtcwquvusf.html

void inc(int &x) { ++x; }
来源：http://dali.zhiwuduotai.top/Article/details/gteevemymy.html

[S45] C++：lambda
来源：http://dali.dashuyun.cn/Article/details/gtkcmbkdvs.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.fzhhl.top/Article/details/gtkgngqxae.html

[S46] C++：函数模板
来源：http://dali.cheryme.top/Article/details/gtlwegxsqw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.dashuyun.cn/Article/details/gtmwtnuemp.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gthtnjtyvz.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yanxiufei.cn/Article/details/gttxiamqyc.html

[S48] C++：逐行读文件
来源：http://dali.yvedp.cn/Article/details/gtzoazmigc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shuidangran.top/Article/details/gtucewfhnx.html

while (std::getline(in, line)) { }
来源：http://dali.ehwqpu.com/Article/details/gtzqpjalkg.html

[S49] C++：写文件
来源：http://dali.daxiang520.top/Article/details/gtjwfjaars.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.guowangkeji.top/Article/details/gtxpjnbrlx.html

[S50] C++：格式化数字
来源：http://dali.cqqwz.cn/Article/details/gtjchvzqrh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtutgkpipx.html

[S51] C++：显式类型转换
来源：http://dali.shuidangran.top/Article/details/gtymyqxxqf.html

static_cast<double>(a) / b
来源：http://dali.aibaodan.cn/Article/details/gtdydzqmis.html

[S52] C++：const 与 noexcept
来源：http://dali.wangdashe.top/Article/details/gtaakhbwlg.html

int size() const noexcept { return n_; }
来源：http://dali.ehwqpu.com/Article/details/gtazwchibl.html

[S53] C++：移动语义
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcaggdhjr.html

std::vector<int> w = std::move(v);
来源：http://dali.yj20258888.top/Article/details/gtyvwdjbzi.html

[S54] C++：异常处理
来源：http://dali.zycfv.cn/Article/details/gtgijkvudq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hywenlv.cn/Article/details/gtpdigpnti.html

[S55] C++：结构化绑定
来源：http://dali.gogol.net.cn/Article/details/gtmekkbcyk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.kuanghao11.cn/Article/details/gtqxkerexe.html

[S56] C++：optional
来源：http://dali.hysaishi.cn/Article/details/gtelfjbydx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.tanke756.top/Article/details/gtswujljob.html

[S57] C++：编译期常量
来源：http://dali.pycfn.com/Article/details/gtpmuzymlu.html

constexpr int N = 10;
来源：http://dali.xinyue.icu/Article/details/gtsszvhaez.html

[S58] C++：命名空间
来源：http://dali.fzhhl.top/Article/details/gttaaznxno.html

namespace ns { int f() { return 1; } }
来源：http://dali.shzxlz.cn/Article/details/gtiioppgna.html

[S59] C++：静态断言
来源：http://dali.gzhubu.top/Article/details/gtfstrpjgi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.c1oappe.top/Article/details/gtkxjupgvz.html

[S60] C++：遍历并删除元素
来源：http://dali.sweek.top/Article/details/gtojjysiny.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shanyushiyangtech.top/Article/details/gtinkpncqa.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtebfltejj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.smart0.xyz/Article/details/gttzpizzbo.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtfksjihvo.html

[T01] Kotlin：Hello World
来源：http://dali.nanxinkj.top/Article/details/gtcdcwlfle.html

println("Hello")
来源：http://dali.fzhhl.top/Article/details/gtnaixivia.html

[T02] Kotlin：变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtrlxhjupt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jinghuilouyu.cn/Article/details/gtjnulgcvu.html

[T03] Kotlin：字符串模板
来源：http://dali.ybcxt.top/Article/details/gtxsqztbgg.html

"值: $b"
来源：http://dali.yuanzhike.top/Article/details/gtvhysrcwz.html

[T04] Kotlin：空安全
来源：http://dali.yvedp.cn/Article/details/gtezfwmlgh.html

val n: String? = null;  n?.length
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfkqewyvf.html

[T05] Kotlin：when 表达式
来源：http://dali.nwbrower.top/Article/details/gtljgmwjgi.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.ehwqpu.com/Article/details/gtjjydvqwn.html

[T06] Kotlin：集合映射
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnhfkcyiz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.birdmap.top/Article/details/gtokpakfkx.html

[T07] Kotlin：集合过滤
来源：http://dali.xylfe.cn/Article/details/gtrvweyacm.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jiagoushi.top/Article/details/gtirlqeuhv.html

[T08] Kotlin：数据类
来源：http://dali.nanxuanxn.top/Article/details/gtnfopmjfz.html

data class User(val name: String, val age: Int)
来源：http://dali.yj20258888.top/Article/details/gtldlqzqpq.html

[T09] Kotlin：扩展函数
来源：http://dali.yuxming.cn/Article/details/gtmkkhoaue.html

fun String.exclaim() = this + "!"
来源：http://dali.cucudq.cn/Article/details/gtkudpbtgx.html

[T10] Kotlin：默认参数
来源：http://dali.xuetiantiany.cn/Article/details/gtudqpqolc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yuanzhike.top/Article/details/gteamvkrem.html

[T11] Kotlin：协程
来源：http://dali.chenjidiqi.icu/Article/details/gtpftvcair.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmsrndkxs.html

[T12] Kotlin：解构声明
来源：http://dali.shanyushiyangtech.top/Article/details/gtiodponav.html

val (a, b) = Pair(1, 2)
来源：http://dali.feifeiyinyue.top/Article/details/gtanbynmvm.html

[T13] Kotlin：只读 Map
来源：http://dali.cdnleiting.top/Article/details/gtefngkcge.html

val m = mapOf("a" to 1)
来源：http://dali.tianlin.xyz/Article/details/gtqqvanqib.html

[T14] Kotlin：循环
来源：http://dali.daxiang520.top/Article/details/gtkxpqtepm.html

for (i in 1..10) println(i)
来源：http://dali.zhijiandao.cn/Article/details/gtidvvqmsl.html

[T15] Kotlin：接口
来源：http://dali.nanxinkj.top/Article/details/gtyldmelfo.html

interface Shape { fun area(): Double }
来源：http://dali.xuanzx.com/Article/details/gtlieivoul.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtdfwlsaui.html

print("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gtwmtoxqad.html

[T17] Swift：变量与常量
来源：http://dali.chenzaomai.com/Article/details/gtlmngfmlb.html

var a = 1;  let b = 2
来源：http://dali.pycfn.com/Article/details/gttcntmbgc.html

[T18] Swift：字符串插值
来源：http://dali.daxiang520.top/Article/details/gtwalkuxrc.html

"值: \(b)"
来源：http://dali.guannengcc.top/Article/details/gtgxrccxku.html

[T19] Swift：可选绑定
来源：http://dali.hnqzz.top/Article/details/gtwrfirzoz.html

if let n = opt { print(n) }
来源：http://dali.nwbrower.top/Article/details/gtbacsfnnz.html

[T20] Swift：数组操作
来源：http://dali.hnqzz.top/Article/details/gtqttcuzku.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.dianchejie.cn/Article/details/gtopobikyf.html

[T21] Swift：遍历
来源：http://dali.iojbl.cn/Article/details/gtysivmcql.html

for x in a { print(x) }
来源：http://dali.birdmap.top/Article/details/gtzhmqktfr.html

[T22] Swift：字典
来源：http://dali.nanxuanxn.top/Article/details/gtimflkylm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.vqdsnc.cn/Article/details/gtlnwadhyi.html

[T23] Swift：函数
来源：http://dali.tian-w.cn/Article/details/gtvpjklcuz.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.kuanghao11.cn/Article/details/gtcunwyvog.html

[T24] Swift：闭包
来源：http://dali.svipenyu.cn/Article/details/gtgzvacrbl.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.fengsongda.top/Article/details/gtrjdgqntr.html

[T25] Swift：结构体
来源：http://dali.jinqigufen.top/Article/details/gttzkrfqxh.html

struct P { var x: Int }
来源：http://dali.cdnleiting.top/Article/details/gtpbidhohq.html

[T26] Swift：类与重写
来源：http://dali.hammf.cn/Article/details/gtnphjgeaq.html

class A: Base { override func f() {} }
来源：http://dali.chenzaomai.com/Article/details/gtjyharisv.html

[T27] Swift：错误处理
来源：http://dali.tianlin.xyz/Article/details/gtqcpnzqug.html

do { try f() } catch { print(error) }
来源：http://dali.9152youxi.cn/Article/details/gtoxrtedqm.html

[T28] Swift：枚举
来源：http://dali.shzxlz.cn/Article/details/gtxtwylmzj.html

enum Color { case red, green }
来源：http://dali.redwolf501.top/Article/details/gtnrdicwyj.html

[T29] Swift：guard 提前返回
来源：http://dali.kuanghao11.cn/Article/details/gtphxqqbhh.html

guard let x = opt else { return }
来源：http://dali.xinyue.icu/Article/details/gthplxgbjo.html

[T30] Swift：协议
来源：http://dali.ivvv.top/Article/details/gtcpiosctn.html

protocol Shape { func area() -> Double }
来源：http://dali.yuxming.cn/Article/details/gtrueeruil.html

[T31] Lua：Hello World
来源：http://dali.xinyue.icu/Article/details/gtvhtrptid.html

print("Hello")
来源：http://dali.cheryme.top/Article/details/gtrsrckuut.html

[T32] Lua：局部变量
来源：http://dali.zhengqikj.top/Article/details/gthnbbjhck.html

local a = 1
来源：http://dali.cdnleiting.top/Article/details/gtpmdnsvwh.html

[T33] Lua：表（数组）
来源：http://dali.zhongyouzk.top/Article/details/gtpgutwatm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.fzhhl.top/Article/details/gtlfvukubt.html

[T34] Lua：遍历表
来源：http://dali.cucudq.cn/Article/details/gtkxlbntbb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xuanzx.com/Article/details/gtcuhidtmm.html

[T35] Lua：字典表
来源：http://dali.cdnleiting.top/Article/details/gtvysnkxhm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yueranfly.top/Article/details/gtmtdwicbe.html

[T36] Lua：函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtpaydcpxw.html

function add(a, b) return a + b end
来源：http://dali.yonumen.top/Article/details/gtulyqhsfe.html

[T37] Lua：字符串拼接
来源：http://dali.yanxiufei.cn/Article/details/gtnceaosog.html

"a" .. "b"
来源：http://dali.sxryk.cn/Article/details/gtatzfntnq.html

[T38] Lua：条件
来源：http://dali.yanxiufei.cn/Article/details/gtlzslupmn.html

if x > 0 then print("正") end
来源：http://dali.cheryme.top/Article/details/gtdzvugvlk.html

[T39] Lua：模式匹配
来源：http://dali.xziqi.cn/Article/details/gtybjrlitp.html

string.find(s, "%d+")
来源：http://dali.sufxvd.cn/Article/details/gtpyfaqmeu.html

[T40] Lua：元表
来源：http://dali.jqgufenzy.top/Article/details/gtsgdjwbdq.html

setmetatable({}, { __index = base })
来源：http://dali.tanke756.top/Article/details/gtiscxpqbj.html

[T41] Perl：Hello World
来源：http://dali.jinqigufen.top/Article/details/gttywdnoto.html

print "Hello\n";
来源：http://dali.yonumen.top/Article/details/gtnqrgygoi.html

[T42] Perl：变量类型
来源：http://dali.ehwqpu.com/Article/details/gtkfpzvdes.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.sweek.top/Article/details/gtqzcyyvxy.html

[T43] Perl：字符串插值
来源：http://dali.hnxiangtu.top/Article/details/gtemsyvvph.html

"值: $a"
来源：http://dali.ydzc1.top/Article/details/gtizvgxfys.html

[T44] Perl：条件
来源：http://dali.zhixingplan.top/Article/details/gtvkrjbjvx.html

if ($a > 0) { print "正"; }
来源：http://dali.zdqjudy.top/Article/details/gtmnrjqycn.html

[T45] Perl：数组遍历
来源：http://dali.aibaodan.cn/Article/details/gtzcsaaseq.html

for my $x (@arr) { print $x; }
来源：http://dali.jiagoushi.top/Article/details/gtzfeyckdk.html

[T46] Perl：哈希操作
来源：http://dali.jyoumei.cn/Article/details/gtgacsevuv.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhongyouzk.top/Article/details/gthsjegffn.html

[T47] Perl：正则捕获
来源：http://dali.meibo888.top/Article/details/gtveektziy.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zycfv.cn/Article/details/gttypcdtlw.html

[T48] Perl：正则替换
来源：http://dali.yj20258888.top/Article/details/gtzxpamwyi.html

$s =~ s/old/new/g;
来源：http://dali.hnxiangtu.top/Article/details/gtjijgooqn.html

[T49] Perl：函数
来源：http://dali.cqqwz.cn/Article/details/gtlumahwst.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.9152youxi.cn/Article/details/gtjzxuzljj.html

[T50] Perl：逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gtzswypqbt.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xylfe.cn/Article/details/gtfwoztdsa.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoekdeimb.html

[T51] Scala：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtpjjvnplr.html

println("Hello")
来源：http://dali.hfpthk.cn/Article/details/gtgxnomove.html

[T52] Scala：变量
来源：http://dali.hammf.cn/Article/details/gtaypwvfjw.html

val a = 1;  var b = 2
来源：http://dali.sweek.top/Article/details/gtgtofgqoh.html

[T53] Scala：字符串插值
来源：http://dali.bjfxy.top/Article/details/gtdfrhmyxi.html

s"值: $b"
来源：http://dali.nwbrower.top/Article/details/gttyjebzis.html

[T54] Scala：集合映射
来源：http://dali.jyoumei.cn/Article/details/gtetmhedrr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hongshengwenyu.top/Article/details/gttdnxdoqh.html

[T55] Scala：集合过滤
来源：http://dali.hywenlv.cn/Article/details/gtqehsapcz.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.chenzaomai.com/Article/details/gtjovctlcs.html

[T56] Scala：样例类
来源：http://dali.ppjwa.cn/Article/details/gtebhciqzr.html

case class User(name: String, age: Int)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpdjasaxj.html

[T57] Scala：模式匹配
来源：http://dali.aibaodan.cn/Article/details/gtbdzakxgg.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.tanke756.top/Article/details/gtspozrbjq.html

[T58] Scala：函数定义
来源：http://dali.zhengqikj.top/Article/details/gtekvxzlla.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.gzhubu.top/Article/details/gtvubcbmll.html

[T59] Scala：循环
来源：http://dali.yueranfly.top/Article/details/gtzbjkxter.html

for (i <- 1 to 10) println(i)
来源：http://dali.nwbrower.top/Article/details/gtctghxwyq.html

[T60] Scala：折叠
来源：http://dali.zdqjudy.top/Article/details/gtwetewdyh.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.gzhubu.top/Article/details/gtmbwnwrty.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtxgcrlifw.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.pycfn.com/Article/details/gtoxiebjfc.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtdrnfgtkk.html


<!-- 参考信息 -->