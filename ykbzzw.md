代发 wailian999

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.bjfxy.top/Article/details/gtlqrcxrpc.html

[R54] 比较两个文件
来源：http://dali.yonumen.top/Article/details/gttqwqvjbr.html

diff a.txt b.txt
来源：http://dali.cdnleiting.top/Article/details/gtsyiywiaq.html

[R55] 压缩与解压
来源：http://dali.tanke756.top/Article/details/gtfjzieaet.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xuanzx.com/Article/details/gtsntllqce.html

[R56] 远程拷贝
来源：http://dali.jyoumei.cn/Article/details/gtbpcrrmbo.html

scp file user@host:/path/
来源：http://dali.zycfv.cn/Article/details/gtperwqxrr.html

[R57] 远程执行命令
来源：http://dali.316326.xyz/Article/details/gtihtitpde.html

ssh user@host 'uptime'
来源：http://dali.snrcjt.cn/Article/details/gtcgqdzpzq.html

[R58] 下载文件
来源：http://dali.shzxlz.cn/Article/details/gtfoozodbj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hysaishi.cn/Article/details/gtfjobqbrs.html

[R59] 发 POST JSON
来源：http://dali.wangdashe.top/Article/details/gtckzixtmn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jyoumei.cn/Article/details/gtlygayytg.html

[R60] 只看 HTTP 状态码
来源：http://dali.gzhubu.top/Article/details/gtxzfbskcq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nanxuanxn.top/Article/details/gtkwwiscln.html

[R61] 磁盘占用
来源：http://dali.zhongyouzk.top/Article/details/gthydidhge.html

df -h;  du -sh *
来源：http://dali.pengpengdd.cyou/Article/details/gtrzctcawo.html

[R62] 找最占空间的文件
来源：http://dali.zycfv.cn/Article/details/gtxfabvtue.html

du -ah . | sort -rh | head -10
来源：http://dali.zhengqikj.top/Article/details/gtfendqnfg.html

[R63] 内存与进程
来源：http://dali.mhx1999.top/Article/details/gtpwaufwor.html

free -h;  ps aux | grep nginx
来源：http://dali.9152youxi.cn/Article/details/gtxexhzwcg.html

[R64] 结束进程
来源：http://dali.jinqigufen.top/Article/details/gtvbibidjq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xylfe.cn/Article/details/gtavrlqtcv.html

[R65] 查看端口占用
来源：http://dali.yuxming.cn/Article/details/gtplxrcjki.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jlsjyb.cn/Article/details/gttkfrsmld.html

[R66] 定时任务
来源：http://dali.ydzc1.top/Article/details/gtxccqpebg.html

crontab -e;  crontab -l
来源：http://dali.cashguo.top/Article/details/gtsvqfilem.html

[R67] 生成随机十六进制串
来源：http://dali.fengsongda.top/Article/details/gtrhddolyb.html

openssl rand -hex 16
来源：http://dali.c1oappe.top/Article/details/gtzjrusaht.html

[R68] 计算文件校验值
来源：http://dali.cheryme.top/Article/details/gtmwjgciij.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ivvv.top/Article/details/gtjevsesss.html

[R69] 生成随机密码
来源：http://dali.chenjidiqi.icu/Article/details/gtyssiwouo.html

head -c 16 /dev/urandom | base64
来源：http://dali.guannengcc.top/Article/details/gtblucwmmi.html

[R70] 时间戳与互转
来源：http://dali.pengpengdd.cyou/Article/details/gtmbowzlqw.html

date +%s;  date -d @1700000000
来源：http://dali.zdqjudy.top/Article/details/gtpsulgizc.html

[R71] 日期格式化
来源：http://dali.hnxiangtu.top/Article/details/gtqnowgsmg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhixingplan.top/Article/details/gtchmhnyrq.html

[R72] 等待端口就绪
来源：http://dali.yuxming.cn/Article/details/gtsbqjqbdf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.tanke756.top/Article/details/gtekjghzay.html

[R73] 分割大日志
来源：http://dali.dashuyun.cn/Article/details/gtnmjclaxz.html

split -l 1000 big.log part_
来源：http://dali.mhx1999.top/Article/details/gtwfxkydtm.html

[R74] 批量重命名
来源：http://dali.jlsjyb.cn/Article/details/gtoygphwss.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.daxiang520.top/Article/details/gtufwipeld.html

[R75] 导出环境变量
来源：http://dali.yangfankeji.com/Article/details/gtrheuzegc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yuanzhike.top/Article/details/gtcqulghme.html

[R76] 使用临时文件
来源：http://dali.mhx1999.top/Article/details/gtrvcrumyq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.meibo888.top/Article/details/gtwocdovdv.html

[R77] 读取用户输入
来源：http://dali.316326.xyz/Article/details/gtyecndboz.html

read -rp "请输入: " ans
来源：http://dali.zdqjudy.top/Article/details/gtvlfkyyhr.html

[R78] 交互式菜单
来源：http://dali.shangyingyoupin.top/Article/details/gtfhbwwzqb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xziqi.cn/Article/details/gtvygpspkv.html

[R79] 解析命令行选项
来源：http://dali.xziqi.cn/Article/details/gtoliqwtfh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cheryme.top/Article/details/gtkinognaa.html

[R80] 查看脚本执行耗时
来源：http://dali.hnxiangtu.top/Article/details/gtmyuscunt.html

time ./run.sh
来源：http://dali.kuanghao11.cn/Article/details/gtvwzccnxh.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtsdwzsbys.html

S. C / C++ 专题
来源：http://dali.snrcjt.cn/Article/details/gthrkkzcsw.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtadcuilio.html

[S01] C：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtelzixfpr.html

#include <stdio.h>
来源：http://dali.chenjidiqi.icu/Article/details/gtnbrxofsx.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.tianlin.xyz/Article/details/gtfrvvgxmx.html

[S02] C：变量与格式化输出
来源：http://dali.c1oappe.top/Article/details/gtnqfnpyuh.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhiwuduotai.top/Article/details/gttzzkingn.html

[S03] C：读入整数
来源：http://dali.ydzc1.top/Article/details/gtljukctnh.html

int x; scanf("%d", &x);
来源：http://dali.kuanghao11.cn/Article/details/gtdjwxqtem.html

[S04] C：字符串复制
来源：http://dali.cashguo.top/Article/details/gttaolpmwe.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinqigufen.top/Article/details/gtsdxsmxca.html

[S05] C：字符串长度
来源：http://dali.0kj1m.cn/Article/details/gtqqcuujup.html

strlen(s)
来源：http://dali.shuidangran.top/Article/details/gtnjeoqoaa.html

[S06] C：字符串比较
来源：http://dali.havefunace.top/Article/details/gtnghxsxqq.html

strcmp(a, b) == 0
来源：http://dali.sysykeji.top/Article/details/gtfbfwpook.html

[S07] C：数组遍历求和
来源：http://dali.jqgufenzy.top/Article/details/gtmuuaeuxs.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.daxiang520.top/Article/details/gtonncwszr.html

[S08] C：动态内存分配与释放
来源：http://dali.9152youxi.cn/Article/details/gtpaxbxetl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cheryme.top/Article/details/gtyozeebdy.html

[S09] C：结构体定义与初始化
来源：http://dali.vqdsnc.cn/Article/details/gtoctrjeli.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.pycfn.com/Article/details/gtmroousaz.html

[S10] C：指针与解引用
来源：http://dali.xinyue.icu/Article/details/gtjmpuedgh.html

int *p = &a;  *p = 5;
来源：http://dali.guowangkeji.top/Article/details/gtdohezmvc.html

[S11] C：逐行读文件
来源：http://dali.ppjwa.cn/Article/details/gtirfhuydn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.chenlongwang.top/Article/details/gtzslvssur.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yanxiufei.cn/Article/details/gtofpegdry.html

fclose(f);
来源：http://dali.zdqjudy.top/Article/details/gtmkwplwnv.html

[S12] C：写文件
来源：http://dali.snrcjt.cn/Article/details/gtchmqoawb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.bjfxy.top/Article/details/gtdeiprjqt.html

[S13] C：宏定义
来源：http://dali.nanxinkj.top/Article/details/gtrupucjxq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhiwuduotai.top/Article/details/gtwjmarhuz.html

[S14] C：枚举
来源：http://dali.snrcjt.cn/Article/details/gtoftuvzlt.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yongpay.top/Article/details/gtkoorcdsh.html

[S15] C：类型转换
来源：http://dali.sweek.top/Article/details/gtrmwibpfe.html

(double) a / b
来源：http://dali.birdmap.top/Article/details/gtdyikiykk.html

[S16] C：位操作置位
来源：http://dali.zhixingplan.top/Article/details/gtdslcvfmu.html

x |= (1 << 3);
来源：http://dali.0kj1m.cn/Article/details/gtxcwunznr.html

[S17] C：安全拼接字符串
来源：http://dali.shuidangran.top/Article/details/gtpgceeioh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkamvmwiy.html

[S18] C：命令行参数
来源：http://dali.daria6918.cn/Article/details/gtidruhxvi.html

int main(int argc, char **argv)
来源：http://dali.gotoacloud.top/Article/details/gtodjudktl.html

[S19] C：快速排序
来源：http://dali.jinqigfzy.top/Article/details/gtmblkfrom.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xinyue.icu/Article/details/gteohxvvfe.html

[S20] C：二分查找
来源：http://dali.zhixingplan.top/Article/details/gtattblntk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gaohongyu789.top/Article/details/gtdpnjruwp.html

[S21] C：字符类别判断
来源：http://dali.zhixingplan.top/Article/details/gtzrjmfvwx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.dashuyun.cn/Article/details/gtqnuvmblv.html

[S22] C：字符串转数字
来源：http://dali.xuanzx.com/Article/details/gtmsnpuedr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ivvv.top/Article/details/gtxulignjl.html

[S23] C：随机数
来源：http://dali.andypj.xyz/Article/details/gtypzxzbfw.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ppjwa.cn/Article/details/gtmmnwexfz.html

[S24] C：获取本地时间
来源：http://dali.yangfankeji.com/Article/details/gtmkaivmoq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sxryk.cn/Article/details/gtnzyfcnok.html

[S25] C：内存拷贝
来源：http://dali.zhiwuduotai.top/Article/details/gtnbfsndmx.html

memcpy(dst, src, n);
来源：http://dali.iojbl.cn/Article/details/gtzyhdczmd.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gtruhhsmjg.html

memset(a, 0, sizeof a);
来源：http://dali.shuidangran.top/Article/details/gtkmsgknac.html

[S27] C：定义常量
来源：http://dali.gogol.net.cn/Article/details/gtqoxhbkog.html

const double PI = 3.14159;
来源：http://dali.yanxiufei.cn/Article/details/gtsmdqmful.html

[S28] C：静态变量
来源：http://dali.birdmap.top/Article/details/gtmsjkiiek.html

static int counter = 0;
来源：http://dali.zhiwuduotai.top/Article/details/gtrhnnousb.html

[S29] C：变参函数
来源：http://dali.sweek.top/Article/details/gtjimwqzpn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cucudq.cn/Article/details/gtsvnpzxyy.html

[S30] C：头文件保护
来源：http://dali.yvedp.cn/Article/details/gtvpksfpal.html

#ifndef X_H
来源：http://dali.jianghu66.top/Article/details/gtogjsoova.html

#define X_H
来源：http://dali.gogol.net.cn/Article/details/gtssuvickc.html

#endif
来源：http://dali.aibaodan.cn/Article/details/gtktjpovou.html

[S31] C++：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtlcmzmjxe.html

#include <iostream>
来源：http://dali.shanyushiyangtech.top/Article/details/gtqfveuvie.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhengqikj.top/Article/details/gtliksnnef.html

[S32] C++：字符串
来源：http://dali.havefunace.top/Article/details/gtjnglfuei.html

std::string s = "hi";  s += "!";
来源：http://dali.tanke756.top/Article/details/gtewosmtej.html

[S33] C++：vector 增删
来源：http://dali.jinqigfzy.top/Article/details/gtdkddymte.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ivvv.top/Article/details/gttbyvqhis.html

[S34] C++：遍历 vector
来源：http://dali.chenjidiqi.icu/Article/details/gtcagzzmcs.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhongyouzk.top/Article/details/gthemvknan.html

[S35] C++：map
来源：http://dali.yj20258888.top/Article/details/gtqxecvszs.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cashguo.top/Article/details/gtvwildhht.html

[S36] C++：unordered_map
来源：http://dali.tianlin.xyz/Article/details/gtaaudsfvn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gttrvplatp.html

[S37] C++：set
来源：http://dali.cheryme.top/Article/details/gtxucaogni.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xinyue.icu/Article/details/gtswchkzhj.html

[S38] C++：排序
来源：http://dali.dianchejie.cn/Article/details/gtrmfmybho.html

std::sort(v.begin(), v.end());
来源：http://dali.yueranfly.top/Article/details/gtzgeucfrq.html

[S39] C++：自定义比较器排序
来源：http://dali.ivvv.top/Article/details/gtlxbpsebh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shanyushiyangkeji.top/Article/details/gthjbeskii.html

[S40] C++：查找元素
来源：http://dali.xziqi.cn/Article/details/gtrhqapkfm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yvedp.cn/Article/details/gtkimwagnu.html

[S41] C++：类与构造函数
来源：http://dali.hysaishi.cn/Article/details/gtqwvzvaqg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.kuanghao11.cn/Article/details/gtehngdmiz.html

[S42] C++：继承与虚函数
来源：http://dali.gogol.net.cn/Article/details/gtflozxluh.html

class B : public Base { public: void f() override {} };
来源：http://dali.cheryme.top/Article/details/gtwcyswscn.html

[S43] C++：智能指针
来源：http://dali.nwbrower.top/Article/details/gtrfxjsoch.html

auto p = std::make_unique<int>(5);
来源：http://dali.yj20258.top/Article/details/gtgnfqrzdw.html

[S44] C++：引用传参
来源：http://dali.tanke756.top/Article/details/gtobhrpcig.html

void inc(int &x) { ++x; }
来源：http://dali.yonumen.top/Article/details/gtvxtkmido.html

[S45] C++：lambda
来源：http://dali.tian-w.cn/Article/details/gtryelylvw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.aizwys.cn/Article/details/gtezefkixj.html

[S46] C++：函数模板
来源：http://dali.sufxvd.cn/Article/details/gtntctjbjq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.sweek.top/Article/details/gtodxwknph.html

[S47] C++：结构化绑定遍历
来源：http://dali.yj202588.top/Article/details/gtlxvoclzo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xziqi.cn/Article/details/gttbbqmmii.html

[S48] C++：逐行读文件
来源：http://dali.sysykeji.top/Article/details/gtzjlvvnyi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.vqdsnc.cn/Article/details/gtfrykckvb.html

while (std::getline(in, line)) { }
来源：http://dali.feifeiyinyue.top/Article/details/gtqrahuych.html

[S49] C++：写文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtbevbrftx.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.quarkkingdee.top/Article/details/gttphrhphe.html

[S50] C++：格式化数字
来源：http://dali.tianlin.xyz/Article/details/gtcfwyaets.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ydzc1.top/Article/details/gtjjfykktt.html

[S51] C++：显式类型转换
来源：http://dali.haohaochexian.top/Article/details/gtytcaghqf.html

static_cast<double>(a) / b
来源：http://dali.xziqi.cn/Article/details/gtoqhvjtjm.html

[S52] C++：const 与 noexcept
来源：http://dali.mhx1999.top/Article/details/gtgxfonyns.html

int size() const noexcept { return n_; }
来源：http://dali.hywenlv.cn/Article/details/gtxxllykbw.html

[S53] C++：移动语义
来源：http://dali.guowangkeji.top/Article/details/gtenkhyrwf.html

std::vector<int> w = std::move(v);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtygmeifqi.html

[S54] C++：异常处理
来源：http://dali.haohaochexian.top/Article/details/gtkzacxsaf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hnxiangtu.top/Article/details/gtlhnjjkhj.html

[S55] C++：结构化绑定
来源：http://dali.yvedp.cn/Article/details/gtilisunxp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.chenzaomai.com/Article/details/gthzpvrgfa.html

[S56] C++：optional
来源：http://dali.havefunace.top/Article/details/gtkiohkoro.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.pengpengdd.cyou/Article/details/gtjtutaqkp.html

[S57] C++：编译期常量
来源：http://dali.chenlongwang.top/Article/details/gtxmakeflr.html

constexpr int N = 10;
来源：http://dali.daxiang520.top/Article/details/gtsavqzyhu.html

[S58] C++：命名空间
来源：http://dali.shuidangran.top/Article/details/gtwoobgdyw.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhoulong.xyz/Article/details/gtvgeuxqfr.html

[S59] C++：静态断言
来源：http://dali.quarkkingdee.top/Article/details/gtgobpqijq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.iojbl.cn/Article/details/gtveufvhlt.html

[S60] C++：遍历并删除元素
来源：http://dali.yuxming.cn/Article/details/gtxrzockmy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.mhx1999.top/Article/details/gtzewknitq.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtcvaavaat.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.quarkkingdee.top/Article/details/gtkkdurlhl.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtbqhkirhg.html

[T01] Kotlin：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtlhjnnndp.html

println("Hello")
来源：http://dali.redwolf501.top/Article/details/gtocwdvmdp.html

[T02] Kotlin：变量
来源：http://dali.quarkkingdee.top/Article/details/gtkeuckbpq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shangyingyoupin.top/Article/details/gtuudalvhy.html

[T03] Kotlin：字符串模板
来源：http://dali.andypj.xyz/Article/details/gtnpfnnlop.html

"值: $b"
来源：http://dali.xuetiantiany.cn/Article/details/gtlvuzhori.html

[T04] Kotlin：空安全
来源：http://dali.birdmap.top/Article/details/gtbzgibqlc.html

val n: String? = null;  n?.length
来源：http://dali.xinyue.icu/Article/details/gtyjbkgezy.html

[T05] Kotlin：when 表达式
来源：http://dali.yj20258.top/Article/details/gtqxowqeme.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gaohongyu789.top/Article/details/gtrwywndgy.html

[T06] Kotlin：集合映射
来源：http://dali.smart0.xyz/Article/details/gtinooqour.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.iojbl.cn/Article/details/gtnwerivsc.html

[T07] Kotlin：集合过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gtbfselgmp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sweek.top/Article/details/gtsoynrqfp.html

[T08] Kotlin：数据类
来源：http://dali.hnxiangtu.top/Article/details/gtuzqaokoa.html

data class User(val name: String, val age: Int)
来源：http://dali.gogol.net.cn/Article/details/gtwqdcrguc.html

[T09] Kotlin：扩展函数
来源：http://dali.xziqi.cn/Article/details/gtpobaqxep.html

fun String.exclaim() = this + "!"
来源：http://dali.dashuyun.cn/Article/details/gtefpuqgak.html

[T10] Kotlin：默认参数
来源：http://dali.9152youxi.cn/Article/details/gtevhuiymm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.nwbrower.top/Article/details/gtmyqkkvxp.html

[T11] Kotlin：协程
来源：http://dali.aizwys.cn/Article/details/gtmvbeyhrm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yangfankeji.com/Article/details/gttlnasavr.html

[T12] Kotlin：解构声明
来源：http://dali.hfpthk.cn/Article/details/gtcflypaur.html

val (a, b) = Pair(1, 2)
来源：http://dali.0kj1m.cn/Article/details/gtqkwdayhc.html

[T13] Kotlin：只读 Map
来源：http://dali.nanxinkj.top/Article/details/gtponnythh.html

val m = mapOf("a" to 1)
来源：http://dali.yuanzhike.top/Article/details/gtykdcueov.html

[T14] Kotlin：循环
来源：http://dali.tianlin.xyz/Article/details/gtholqmoxs.html

for (i in 1..10) println(i)
来源：http://dali.hysaishi.cn/Article/details/gtqliodxwn.html

[T15] Kotlin：接口
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcwyudsym.html

interface Shape { fun area(): Double }
来源：http://dali.chenlongwang.top/Article/details/gtviqzecrj.html

[T16] Swift：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtsobetrca.html

print("Hello")
来源：http://dali.gotoacloud.top/Article/details/gthegxckim.html

[T17] Swift：变量与常量
来源：http://dali.mhx1999.top/Article/details/gtakbuxyll.html

var a = 1;  let b = 2
来源：http://dali.sxryk.cn/Article/details/gtispqmgum.html

[T18] Swift：字符串插值
来源：http://dali.jlsjyb.cn/Article/details/gtwhdncqmj.html

"值: \(b)"
来源：http://dali.xylfe.cn/Article/details/gtbqlqnhyu.html

[T19] Swift：可选绑定
来源：http://dali.vqdsnc.cn/Article/details/gtggxmxpfm.html

if let n = opt { print(n) }
来源：http://dali.pengpengdd.cyou/Article/details/gtvvhoeinf.html

[T20] Swift：数组操作
来源：http://dali.chenzaomai.com/Article/details/gtmveoxlxe.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.nanxinkj.top/Article/details/gtlsfkuyjy.html

[T21] Swift：遍历
来源：http://dali.shangyingyoupin.top/Article/details/gtqziztrqq.html

for x in a { print(x) }
来源：http://dali.tanke756.top/Article/details/gthcdglmvc.html

[T22] Swift：字典
来源：http://dali.kuanghao11.cn/Article/details/gtvbanvejn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.9152youxi.cn/Article/details/gtqujvdemd.html

[T23] Swift：函数
来源：http://dali.316326.xyz/Article/details/gthgbvsogu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.dashuyun.cn/Article/details/gtircxverf.html

[T24] Swift：闭包
来源：http://dali.tian-w.cn/Article/details/gtgoxojoad.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhijiandao.cn/Article/details/gtbwssojfe.html

[T25] Swift：结构体
来源：http://dali.iojbl.cn/Article/details/gtjattuvjk.html

struct P { var x: Int }
来源：http://dali.yj20258888.top/Article/details/gtlaubdhua.html

[T26] Swift：类与重写
来源：http://dali.zhijiandao.cn/Article/details/gtsvhrrjtq.html

class A: Base { override func f() {} }
来源：http://dali.0kj1m.cn/Article/details/gtdghvfyxf.html

[T27] Swift：错误处理
来源：http://dali.zhiwuduotai.top/Article/details/gtamxktnol.html

do { try f() } catch { print(error) }
来源：http://dali.tanke756.top/Article/details/gtyllxbtqd.html

[T28] Swift：枚举
来源：http://dali.mhx1999.top/Article/details/gtvqipveis.html

enum Color { case red, green }
来源：http://dali.wangshuangyany.cn/Article/details/gtlhfoqlux.html

[T29] Swift：guard 提前返回
来源：http://dali.xinyue.icu/Article/details/gthmcukiwg.html

guard let x = opt else { return }
来源：http://dali.jyoumei.cn/Article/details/gtotckegab.html

[T30] Swift：协议
来源：http://dali.316326.xyz/Article/details/gtjiogynly.html

protocol Shape { func area() -> Double }
来源：http://dali.dashuyun.cn/Article/details/gtyepngceq.html

[T31] Lua：Hello World
来源：http://dali.fzhhl.top/Article/details/gtlibvftlg.html

print("Hello")
来源：http://dali.yvedp.cn/Article/details/gtryppheon.html

[T32] Lua：局部变量
来源：http://dali.nwbrower.top/Article/details/gttbtstkir.html

local a = 1
来源：http://dali.hfpthk.cn/Article/details/gtzaufgxru.html

[T33] Lua：表（数组）
来源：http://dali.316326.xyz/Article/details/gtuzuzqvow.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.haohaochexian.top/Article/details/gtfmuimunj.html

[T34] Lua：遍历表
来源：http://dali.yuxming.cn/Article/details/gthfqjhmpm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.pengpengdd.cyou/Article/details/gttdfsrvqu.html

[T35] Lua：字典表
来源：http://dali.yvedp.cn/Article/details/gtvdmkubhj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.dianchejie.cn/Article/details/gtovyzoxbo.html

[T36] Lua：函数
来源：http://dali.hysaishi.cn/Article/details/gtafsueahi.html

function add(a, b) return a + b end
来源：http://dali.birdmap.top/Article/details/gtbdwzvygj.html

[T37] Lua：字符串拼接
来源：http://dali.zhoulong.xyz/Article/details/gtkbyxqzzz.html

"a" .. "b"
来源：http://dali.hfpthk.cn/Article/details/gthbnkmnsu.html

[T38] Lua：条件
来源：http://dali.sufxvd.cn/Article/details/gtsrgmndiq.html

if x > 0 then print("正") end
来源：http://dali.quarkkingdee.top/Article/details/gtzjrmbbej.html

[T39] Lua：模式匹配
来源：http://dali.hongshengwenyu.top/Article/details/gtspjlxuwz.html

string.find(s, "%d+")
来源：http://dali.yj202588.top/Article/details/gttmppivdg.html

[T40] Lua：元表
来源：http://dali.hysaishi.cn/Article/details/gtdbpzwbyq.html

setmetatable({}, { __index = base })
来源：http://dali.meibo888.top/Article/details/gtvoycotkb.html

[T41] Perl：Hello World
来源：http://dali.yj20258888.top/Article/details/gtvhqjjmrm.html

print "Hello\n";
来源：http://dali.chenjidiqi.icu/Article/details/gtuhyrgkks.html

[T42] Perl：变量类型
来源：http://dali.ybcxt.top/Article/details/gtswpousye.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.havefunace.top/Article/details/gthtnapfcr.html

[T43] Perl：字符串插值
来源：http://dali.zhengqikj.top/Article/details/gtbfotgywf.html

"值: $a"
来源：http://dali.tian-w.cn/Article/details/gttvzgltpo.html

[T44] Perl：条件
来源：http://dali.hywenlv.cn/Article/details/gtrpcajjul.html

if ($a > 0) { print "正"; }
来源：http://dali.hnxiangtu.top/Article/details/gtryjyqtsi.html

[T45] Perl：数组遍历
来源：http://dali.shzxlz.cn/Article/details/gtnvrulhlm.html

for my $x (@arr) { print $x; }
来源：http://dali.xuanzx.com/Article/details/gtabsdeznl.html

[T46] Perl：哈希操作
来源：http://dali.shangyingyoupin.top/Article/details/gtycjdzsrx.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.shzxlz.cn/Article/details/gtbcrdecpm.html

[T47] Perl：正则捕获
来源：http://dali.havefunace.top/Article/details/gtqvkjsghl.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhoulong.xyz/Article/details/gtjokctgks.html

[T48] Perl：正则替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbvgghuhp.html

$s =~ s/old/new/g;
来源：http://dali.zhongyouzk.top/Article/details/gtokscaycr.html

[T49] Perl：函数
来源：http://dali.hfpthk.cn/Article/details/gtxdvvyvaj.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.hfpthk.cn/Article/details/gtrowqzbxn.html

[T50] Perl：逐行读文件
来源：http://dali.gzhubu.top/Article/details/gthwsqgnud.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yuanzhike.top/Article/details/gtwenjwyza.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yanxiufei.cn/Article/details/gtwfsvdbec.html

[T51] Scala：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gthocbssfh.html

println("Hello")
来源：http://dali.pengpengdd.cyou/Article/details/gtmyqfsroc.html

[T52] Scala：变量
来源：http://dali.yj20258888.top/Article/details/gtgoiwkrjm.html

val a = 1;  var b = 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtdabkszxr.html

[T53] Scala：字符串插值
来源：http://dali.gzhubu.top/Article/details/gtyuymzjyv.html

s"值: $b"
来源：http://dali.mhx1999.top/Article/details/gtilkfzuwb.html

[T54] Scala：集合映射
来源：http://dali.cheryme.top/Article/details/gtodydcitr.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.cqqwz.cn/Article/details/gtlzziawvx.html

[T55] Scala：集合过滤
来源：http://dali.bjfxy.top/Article/details/gttdrtcgua.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.smart0.xyz/Article/details/gtaaxvhmhh.html

[T56] Scala：样例类
来源：http://dali.hongshengwenyu.top/Article/details/gtmskfmwya.html


<!-- 参考信息 -->