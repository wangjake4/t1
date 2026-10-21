代发 wailian999

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gogol.net.cn/Article/details/gtwhwkcifz.html

[R56] 远程拷贝
来源：http://dali.zhaomingkeji.xyz/Article/details/gtshixrjel.html

scp file user@host:/path/
来源：http://dali.dianchejie.cn/Article/details/gtpeccixnq.html

[R57] 远程执行命令
来源：http://dali.cashguo.top/Article/details/gtprgnfzjn.html

ssh user@host 'uptime'
来源：http://dali.snrcjt.cn/Article/details/gtvnjiyzyt.html

[R58] 下载文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtevdkfooe.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yanxiufei.cn/Article/details/gtlkkyabjk.html

[R59] 发 POST JSON
来源：http://dali.wangdashe.top/Article/details/gtqcmymvto.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shuidangran.top/Article/details/gtxufdobfa.html

[R60] 只看 HTTP 状态码
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnnqhrwef.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hammf.cn/Article/details/gtkzxrtmhh.html

[R61] 磁盘占用
来源：http://dali.guowangkeji.top/Article/details/gthmbbpydy.html

df -h;  du -sh *
来源：http://dali.wangshuangyany.cn/Article/details/gtlemwddbm.html

[R62] 找最占空间的文件
来源：http://dali.shzxlz.cn/Article/details/gtbzzdvrcf.html

du -ah . | sort -rh | head -10
来源：http://dali.tianlin.xyz/Article/details/gtnfwwzuin.html

[R63] 内存与进程
来源：http://dali.sxryk.cn/Article/details/gtbjipujbl.html

free -h;  ps aux | grep nginx
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkukmzswb.html

[R64] 结束进程
来源：http://dali.cheryme.top/Article/details/gtvisabcvx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.haohaochexian.top/Article/details/gtzhocetrw.html

[R65] 查看端口占用
来源：http://dali.gotoacloud.top/Article/details/gtvbxlhjxu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xziqi.cn/Article/details/gtaasboyly.html

[R66] 定时任务
来源：http://dali.yj20258888.top/Article/details/gtpoopbwlm.html

crontab -e;  crontab -l
来源：http://dali.yvedp.cn/Article/details/gtqzbodkke.html

[R67] 生成随机十六进制串
来源：http://dali.316326.xyz/Article/details/gtcaeokenn.html

openssl rand -hex 16
来源：http://dali.jinqigufen.top/Article/details/gtzasxzpup.html

[R68] 计算文件校验值
来源：http://dali.zhoulong.xyz/Article/details/gtexsfemfw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.c1oappe.top/Article/details/gtnzvssepl.html

[R69] 生成随机密码
来源：http://dali.chenzaomai.com/Article/details/gtfissaavf.html

head -c 16 /dev/urandom | base64
来源：http://dali.fengsongda.top/Article/details/gtalbjlumd.html

[R70] 时间戳与互转
来源：http://dali.pengpengdd.cyou/Article/details/gtdzcktijh.html

date +%s;  date -d @1700000000
来源：http://dali.redwolf501.top/Article/details/gtpdfynjsa.html

[R71] 日期格式化
来源：http://dali.cdnleiting.top/Article/details/gtlcgqbzgq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhengqikj.top/Article/details/gtpxefakqu.html

[R72] 等待端口就绪
来源：http://dali.daxiang520.top/Article/details/gtjkxwegfq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.daria6918.cn/Article/details/gtdxddvulv.html

[R73] 分割大日志
来源：http://dali.chenlongwang.top/Article/details/gtwutkiwom.html

split -l 1000 big.log part_
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmaxvyvxe.html

[R74] 批量重命名
来源：http://dali.xuanzx.com/Article/details/gtqvoamhgv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yuanzhike.top/Article/details/gtdtacgeid.html

[R75] 导出环境变量
来源：http://dali.zhixingplan.top/Article/details/gtmblpocyf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrlynxtun.html

[R76] 使用临时文件
来源：http://dali.bjfxy.top/Article/details/gtqnbjeckc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.ydzc1.top/Article/details/gtmumlsoie.html

[R77] 读取用户输入
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkhtynigw.html

read -rp "请输入: " ans
来源：http://dali.gogol.net.cn/Article/details/gtsbdmjfjj.html

[R78] 交互式菜单
来源：http://dali.shanyushiyangtech.top/Article/details/gtlxaukqtf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtprepebfm.html

[R79] 解析命令行选项
来源：http://dali.vqdsnc.cn/Article/details/gtvsaqimcu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xylfe.cn/Article/details/gtjucrwcnh.html

[R80] 查看脚本执行耗时
来源：http://dali.yanxiufei.cn/Article/details/gtkwltvbvz.html

time ./run.sh
来源：http://dali.jianghu66.top/Article/details/gtchjnanyp.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtdsdvshfb.html

S. C / C++ 专题
来源：http://dali.daria6918.cn/Article/details/gtqzlsnllb.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtdkgkmmrt.html

[S01] C：Hello World
来源：http://dali.daria6918.cn/Article/details/gtfraokysj.html

#include <stdio.h>
来源：http://dali.cucudq.cn/Article/details/gteqafdlfr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdkmggeuh.html

[S02] C：变量与格式化输出
来源：http://dali.quarkkingdee.top/Article/details/gtmiuqruav.html

int a = 10; printf("%d\n", a);
来源：http://dali.andypj.xyz/Article/details/gttzhekqbo.html

[S03] C：读入整数
来源：http://dali.yanxiufei.cn/Article/details/gtzykklrjy.html

int x; scanf("%d", &x);
来源：http://dali.cheryme.top/Article/details/gthxojumlg.html

[S04] C：字符串复制
来源：http://dali.nanxuanxn.top/Article/details/gtdksnzzse.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jqgufenzy.top/Article/details/gttcpschjd.html

[S05] C：字符串长度
来源：http://dali.guowangkeji.top/Article/details/gtbwlczzut.html

strlen(s)
来源：http://dali.nanxuanxn.top/Article/details/gtnxxbwvro.html

[S06] C：字符串比较
来源：http://dali.ppjwa.cn/Article/details/gtyuelmskb.html

strcmp(a, b) == 0
来源：http://dali.wangshuangyany.cn/Article/details/gtvmmymkwt.html

[S07] C：数组遍历求和
来源：http://dali.shangyingyoupin.top/Article/details/gtcosulrha.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yongpay.top/Article/details/gtjergsnrf.html

[S08] C：动态内存分配与释放
来源：http://dali.cqqwz.cn/Article/details/gtcgmidzds.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cashguo.top/Article/details/gtvpvjaytl.html

[S09] C：结构体定义与初始化
来源：http://dali.xziqi.cn/Article/details/gtkkhavhqc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.daria6918.cn/Article/details/gtdwcrpbhy.html

[S10] C：指针与解引用
来源：http://dali.chenjidiqi.icu/Article/details/gtfnaulkwp.html

int *p = &a;  *p = 5;
来源：http://dali.cheryme.top/Article/details/gtlytuufde.html

[S11] C：逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtomkekxwf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jiagoushi.top/Article/details/gtzgvncota.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jqgfzy.top/Article/details/gtxsfzazwh.html

fclose(f);
来源：http://dali.pycfn.com/Article/details/gtbxotjogy.html

[S12] C：写文件
来源：http://dali.yongpay.top/Article/details/gtypkavgvi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sxryk.cn/Article/details/gtzrsvufzc.html

[S13] C：宏定义
来源：http://dali.gogol.net.cn/Article/details/gtwarfvnwy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jianghu66.top/Article/details/gtaymwvhvb.html

[S14] C：枚举
来源：http://dali.shanyushiyangtech.top/Article/details/gtzzdgtakp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gotoacloud.top/Article/details/gtelugtnrq.html

[S15] C：类型转换
来源：http://dali.yanxiufei.cn/Article/details/gtrchfppdw.html

(double) a / b
来源：http://dali.0kj1m.cn/Article/details/gtqtsdvhjz.html

[S16] C：位操作置位
来源：http://dali.fengsongda.top/Article/details/gtpsnhcqff.html

x |= (1 << 3);
来源：http://dali.ppjwa.cn/Article/details/gtzgazuwtt.html

[S17] C：安全拼接字符串
来源：http://dali.gzhubu.top/Article/details/gtwwkrkudd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.0kj1m.cn/Article/details/gthihpcahn.html

[S18] C：命令行参数
来源：http://dali.birdmap.top/Article/details/gteujdyvjw.html

int main(int argc, char **argv)
来源：http://dali.ydzc1.top/Article/details/gtyxwhkras.html

[S19] C：快速排序
来源：http://dali.jianghu66.top/Article/details/gtzskzxkzj.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.smart0.xyz/Article/details/gtgfndsozb.html

[S20] C：二分查找
来源：http://dali.shzxlz.cn/Article/details/gtvgaweocp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gotoacloud.top/Article/details/gtygigjbzu.html

[S21] C：字符类别判断
来源：http://dali.cdnleiting.top/Article/details/gtslbuwznk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sweek.top/Article/details/gtlqclqpil.html

[S22] C：字符串转数字
来源：http://dali.shangyingyoupin.top/Article/details/gtdizbllsv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.316326.xyz/Article/details/gtbcgpozfw.html

[S23] C：随机数
来源：http://dali.ydzc1.top/Article/details/gtgatmvgtj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.fengsongda.top/Article/details/gtqclxjqyc.html

[S24] C：获取本地时间
来源：http://dali.shanyushiyangtech.top/Article/details/gtqvmdyxjp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.kuanghao11.cn/Article/details/gtsacicmfr.html

[S25] C：内存拷贝
来源：http://dali.fengsongda.top/Article/details/gtjrefdruf.html

memcpy(dst, src, n);
来源：http://dali.wangdashe.top/Article/details/gtgthqgipq.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gtguvcgumq.html

memset(a, 0, sizeof a);
来源：http://dali.hnqzz.top/Article/details/gtdkwdldji.html

[S27] C：定义常量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcgzhdpay.html

const double PI = 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gtsgbhzgzt.html

[S28] C：静态变量
来源：http://dali.pycfn.com/Article/details/gtsnfvgosj.html

static int counter = 0;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtswsagmwh.html

[S29] C：变参函数
来源：http://dali.yuanzhike.top/Article/details/gtcirpmuae.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yvedp.cn/Article/details/gtuximxtbq.html

[S30] C：头文件保护
来源：http://dali.cucudq.cn/Article/details/gtowkvpyjx.html

#ifndef X_H
来源：http://dali.9152youxi.cn/Article/details/gtiwpzwzlx.html

#define X_H
来源：http://dali.ivvv.top/Article/details/gtfzssluaf.html

#endif
来源：http://dali.tianlin.xyz/Article/details/gtlasfnwgz.html

[S31] C++：Hello World
来源：http://dali.yonumen.top/Article/details/gtgaroshnl.html

#include <iostream>
来源：http://dali.jqgufenzy.top/Article/details/gtchamggdg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shzxlz.cn/Article/details/gtfraqnbib.html

[S32] C++：字符串
来源：http://dali.daria6918.cn/Article/details/gtraoeudds.html

std::string s = "hi";  s += "!";
来源：http://dali.yanxiufei.cn/Article/details/gtimmnskhh.html

[S33] C++：vector 增删
来源：http://dali.iojbl.cn/Article/details/gtcezalchz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtopakjdqc.html

[S34] C++：遍历 vector
来源：http://dali.hysaishi.cn/Article/details/gtishxxnag.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.nwbrower.top/Article/details/gtlrkexpxv.html

[S35] C++：map
来源：http://dali.ehwqpu.com/Article/details/gtiexlfzvm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangdashe.top/Article/details/gtdkzxyuer.html

[S36] C++：unordered_map
来源：http://dali.smart0.xyz/Article/details/gtjngflppq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sweek.top/Article/details/gtvwxnxtic.html

[S37] C++：set
来源：http://dali.yongpay.top/Article/details/gtwowjixos.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.daria6918.cn/Article/details/gtdzfpgvlz.html

[S38] C++：排序
来源：http://dali.quarkkingdee.top/Article/details/gtkikxntbv.html

std::sort(v.begin(), v.end());
来源：http://dali.xinyue.icu/Article/details/gtxeywfbvn.html

[S39] C++：自定义比较器排序
来源：http://dali.yj20258888.top/Article/details/gtjdgvtral.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yuanzhike.top/Article/details/gtkdwgrjxu.html

[S40] C++：查找元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvsjqywbb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.daxiang520.top/Article/details/gtomekeqwt.html

[S41] C++：类与构造函数
来源：http://dali.jlsjyb.cn/Article/details/gtihcnozfa.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yuxming.cn/Article/details/gtumzgvodj.html

[S42] C++：继承与虚函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlurflbyk.html

class B : public Base { public: void f() override {} };
来源：http://dali.xinyue.icu/Article/details/gthqyrwhjb.html

[S43] C++：智能指针
来源：http://dali.jlsjyb.cn/Article/details/gtthmhxswc.html

auto p = std::make_unique<int>(5);
来源：http://dali.gzhubu.top/Article/details/gtrlqttdvi.html

[S44] C++：引用传参
来源：http://dali.jyoumei.cn/Article/details/gtxdacwltk.html

void inc(int &x) { ++x; }
来源：http://dali.zhongyouzk.top/Article/details/gtxtrdetow.html

[S45] C++：lambda
来源：http://dali.fengsongda.top/Article/details/gtzgminwyv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhixingplan.top/Article/details/gtzblrgjlp.html

[S46] C++：函数模板
来源：http://dali.sufxvd.cn/Article/details/gtfdsnzezk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.quarkkingdee.top/Article/details/gtcterrvxr.html

[S47] C++：结构化绑定遍历
来源：http://dali.nwbrower.top/Article/details/gtiplajqgj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.0kj1m.cn/Article/details/gtttlwaztr.html

[S48] C++：逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gtrqtptccy.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gogol.net.cn/Article/details/gtoowzqvgg.html

while (std::getline(in, line)) { }
来源：http://dali.sweek.top/Article/details/gtjlgogilj.html

[S49] C++：写文件
来源：http://dali.dashuyun.cn/Article/details/gtpekmbkva.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sysykeji.top/Article/details/gtwlscbwbu.html

[S50] C++：格式化数字
来源：http://dali.xuanzx.com/Article/details/gtdpnwrhua.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gtjgactnoo.html

[S51] C++：显式类型转换
来源：http://dali.jqgfzy.top/Article/details/gtrzrmnbqx.html

static_cast<double>(a) / b
来源：http://dali.hongshengwenyu.top/Article/details/gtygnnqxir.html

[S52] C++：const 与 noexcept
来源：http://dali.yuanzhike.top/Article/details/gtixnpdkrj.html

int size() const noexcept { return n_; }
来源：http://dali.ehwqpu.com/Article/details/gtzbkjdyoz.html

[S53] C++：移动语义
来源：http://dali.yangfankeji.com/Article/details/gtvgnhfrri.html

std::vector<int> w = std::move(v);
来源：http://dali.9152youxi.cn/Article/details/gtvejyjiow.html

[S54] C++：异常处理
来源：http://dali.jinqigfzy.top/Article/details/gtrvamjcpf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.iojbl.cn/Article/details/gtnrybildy.html

[S55] C++：结构化绑定
来源：http://dali.ydzc1.top/Article/details/gthwbsraha.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.snrcjt.cn/Article/details/gtekrocevi.html

[S56] C++：optional
来源：http://dali.pycfn.com/Article/details/gtyeynvueb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.feifeiyinyue.top/Article/details/gtxkoljlde.html

[S57] C++：编译期常量
来源：http://dali.daria6918.cn/Article/details/gtxtrmubzx.html

constexpr int N = 10;
来源：http://dali.hnxiangtu.top/Article/details/gtwehatahm.html

[S58] C++：命名空间
来源：http://dali.nanxuanxn.top/Article/details/gtzusntnyw.html

namespace ns { int f() { return 1; } }
来源：http://dali.yuanzhike.top/Article/details/gtzypwznjr.html

[S59] C++：静态断言
来源：http://dali.feifeiyinyue.top/Article/details/gtxgzqbbym.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.pycfn.com/Article/details/gtvssxuesi.html

[S60] C++：遍历并删除元素
来源：http://dali.tian-w.cn/Article/details/gtswijlbkv.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.nwbrower.top/Article/details/gtnzwohweh.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtdcdygiul.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nanxinkj.top/Article/details/gtxnjjyech.html

================================================================================
来源：http://dali.hongshengwenyu.top/Article/details/gteqrjuuzm.html

[T01] Kotlin：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtegvfiuiz.html

println("Hello")
来源：http://dali.cashguo.top/Article/details/gtwacwmuuz.html

[T02] Kotlin：变量
来源：http://dali.mhx1999.top/Article/details/gtjyuqjkgt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhoulong.xyz/Article/details/gtlqewcxto.html

[T03] Kotlin：字符串模板
来源：http://dali.jianghu66.top/Article/details/gtelgvnllg.html

"值: $b"
来源：http://dali.yuxming.cn/Article/details/gtvldysfcz.html

[T04] Kotlin：空安全
来源：http://dali.zhijiandao.cn/Article/details/gteftccuby.html

val n: String? = null;  n?.length
来源：http://dali.ydzc1.top/Article/details/gtkcjetokp.html

[T05] Kotlin：when 表达式
来源：http://dali.ydzc1.top/Article/details/gtezmwxfmz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jyoumei.cn/Article/details/gtzkxyjfsl.html

[T06] Kotlin：集合映射
来源：http://dali.hnqzz.top/Article/details/gtklsakyto.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cheryme.top/Article/details/gtcauykzaz.html

[T07] Kotlin：集合过滤
来源：http://dali.fzhhl.top/Article/details/gthknrivsf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jlsjyb.cn/Article/details/gtoptfwqmf.html

[T08] Kotlin：数据类
来源：http://dali.yvedp.cn/Article/details/gtthhupysq.html

data class User(val name: String, val age: Int)
来源：http://dali.haohaochexian.top/Article/details/gtpdatpcey.html

[T09] Kotlin：扩展函数
来源：http://dali.hnxiangtu.top/Article/details/gttmmnxfhb.html

fun String.exclaim() = this + "!"
来源：http://dali.jinqigufen.top/Article/details/gtzjdrazpl.html

[T10] Kotlin：默认参数
来源：http://dali.zhiwuduotai.top/Article/details/gtdyurumbw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yangfankeji.com/Article/details/gtqkfyjewj.html

[T11] Kotlin：协程
来源：http://dali.jinqigfzy.top/Article/details/gttidcvxfm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yueranfly.top/Article/details/gtofhljfia.html

[T12] Kotlin：解构声明
来源：http://dali.shuidangran.top/Article/details/gtosqcxvpz.html

val (a, b) = Pair(1, 2)
来源：http://dali.9152youxi.cn/Article/details/gtzhbspcoz.html

[T13] Kotlin：只读 Map
来源：http://dali.svipenyu.cn/Article/details/gtrfmfygrc.html

val m = mapOf("a" to 1)
来源：http://dali.hongshengwenyu.top/Article/details/gtisutfsiu.html

[T14] Kotlin：循环
来源：http://dali.zhiwuduotai.top/Article/details/gtucdspqgk.html

for (i in 1..10) println(i)
来源：http://dali.yueranfly.top/Article/details/gtjseynwst.html

[T15] Kotlin：接口
来源：http://dali.yueranfly.top/Article/details/gtmhjiffkf.html

interface Shape { fun area(): Double }
来源：http://dali.chenzaomai.com/Article/details/gtpztxpnsw.html

[T16] Swift：Hello World
来源：http://dali.nanxinkj.top/Article/details/gtjfybdzvc.html

print("Hello")
来源：http://dali.cucudq.cn/Article/details/gtevizgrcx.html

[T17] Swift：变量与常量
来源：http://dali.gaohongyu789.top/Article/details/gtgldmqmtb.html

var a = 1;  let b = 2
来源：http://dali.dianchejie.cn/Article/details/gtcjzgkbam.html

[T18] Swift：字符串插值
来源：http://dali.cashguo.top/Article/details/gtvgydtdan.html

"值: \(b)"
来源：http://dali.sweek.top/Article/details/gtdistlyrq.html

[T19] Swift：可选绑定
来源：http://dali.hnqzz.top/Article/details/gtsffasiho.html

if let n = opt { print(n) }
来源：http://dali.cashguo.top/Article/details/gtfmzokkrf.html

[T20] Swift：数组操作
来源：http://dali.gogol.net.cn/Article/details/gtuuzkqpvl.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yvedp.cn/Article/details/gtgupjaxnm.html

[T21] Swift：遍历
来源：http://dali.kuanghao11.cn/Article/details/gtkcntimcd.html

for x in a { print(x) }
来源：http://dali.xylfe.cn/Article/details/gtgjpycjvr.html

[T22] Swift：字典
来源：http://dali.chenjidiqi.icu/Article/details/gtxcnlzeti.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.sufxvd.cn/Article/details/gtqjagcuce.html

[T23] Swift：函数
来源：http://dali.yongpay.top/Article/details/gtwvpecahw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hammf.cn/Article/details/gtwjogxmpq.html

[T24] Swift：闭包
来源：http://dali.kuanghao11.cn/Article/details/gtigsfvzfm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yuanzhike.top/Article/details/gtkhokxsru.html

[T25] Swift：结构体
来源：http://dali.guowangkeji.top/Article/details/gtgpzwonxl.html

struct P { var x: Int }
来源：http://dali.bjfxy.top/Article/details/gtuuevnwgr.html

[T26] Swift：类与重写
来源：http://dali.jiagoushi.top/Article/details/gtdpiqjcso.html

class A: Base { override func f() {} }
来源：http://dali.meibo888.top/Article/details/gtcbquhqhs.html

[T27] Swift：错误处理
来源：http://dali.jinghuilouyu.cn/Article/details/gtcpjdnric.html

do { try f() } catch { print(error) }
来源：http://dali.zdqjudy.top/Article/details/gtmynbrccb.html

[T28] Swift：枚举
来源：http://dali.hnqzz.top/Article/details/gtdrvscohd.html

enum Color { case red, green }
来源：http://dali.gaohongyu789.top/Article/details/gtuzxsfbau.html

[T29] Swift：guard 提前返回
来源：http://dali.ehwqpu.com/Article/details/gtcxodbsru.html

guard let x = opt else { return }
来源：http://dali.zhoulong.xyz/Article/details/gttqbgothr.html

[T30] Swift：协议
来源：http://dali.cdnleiting.top/Article/details/gtnbizkrwq.html

protocol Shape { func area() -> Double }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkfqktosq.html

[T31] Lua：Hello World
来源：http://dali.c1oappe.top/Article/details/gthsvugcxt.html

print("Hello")
来源：http://dali.jianghu66.top/Article/details/gtwephepkd.html

[T32] Lua：局部变量
来源：http://dali.sweek.top/Article/details/gtjohxbfjl.html

local a = 1
来源：http://dali.iojbl.cn/Article/details/gtwgcfjnff.html

[T33] Lua：表（数组）
来源：http://dali.zhiwuduotai.top/Article/details/gtrauupcvt.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xuetiantiany.cn/Article/details/gtlkgsxdlo.html

[T34] Lua：遍历表
来源：http://dali.svipenyu.cn/Article/details/gtiiatxptn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jinqigufen.top/Article/details/gtdycxuidc.html

[T35] Lua：字典表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqhcbatky.html

local d = { a = 1 };  d.b = 2
来源：http://dali.gzhubu.top/Article/details/gtinkaasee.html

[T36] Lua：函数
来源：http://dali.tianlin.xyz/Article/details/gteslrbewq.html

function add(a, b) return a + b end
来源：http://dali.pycfn.com/Article/details/gtsgxvqkbx.html

[T37] Lua：字符串拼接
来源：http://dali.jinqigfzy.top/Article/details/gtlhdtwcnz.html

"a" .. "b"
来源：http://dali.daria6918.cn/Article/details/gtzordcgyz.html

[T38] Lua：条件
来源：http://dali.meibo888.top/Article/details/gtuvzzigic.html

if x > 0 then print("正") end
来源：http://dali.hnxiangtu.top/Article/details/gtufcylnav.html

[T39] Lua：模式匹配
来源：http://dali.gotoacloud.top/Article/details/gtlkugimje.html

string.find(s, "%d+")
来源：http://dali.cucudq.cn/Article/details/gtbyubhqzo.html

[T40] Lua：元表
来源：http://dali.redwolf501.top/Article/details/gtkqfxkadk.html

setmetatable({}, { __index = base })
来源：http://dali.wangdashe.top/Article/details/gtjjwlfeml.html

[T41] Perl：Hello World
来源：http://dali.yueranfly.top/Article/details/gtmbjvbsjv.html

print "Hello\n";
来源：http://dali.c1oappe.top/Article/details/gtgkhchwnt.html

[T42] Perl：变量类型
来源：http://dali.hfpthk.cn/Article/details/gtajarjaqq.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhengqikj.top/Article/details/gthpwiwgwh.html

[T43] Perl：字符串插值
来源：http://dali.316326.xyz/Article/details/gtylsbjdpb.html

"值: $a"
来源：http://dali.gogol.net.cn/Article/details/gteqelhart.html

[T44] Perl：条件
来源：http://dali.iojbl.cn/Article/details/gtqoidrqau.html

if ($a > 0) { print "正"; }
来源：http://dali.sysykeji.top/Article/details/gthxywzsqg.html

[T45] Perl：数组遍历
来源：http://dali.tianlin.xyz/Article/details/gtxrndlxxu.html

for my $x (@arr) { print $x; }
来源：http://dali.gzhubu.top/Article/details/gtwnooqhqn.html

[T46] Perl：哈希操作
来源：http://dali.jinghuilouyu.cn/Article/details/gtfjnxohds.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.haohaochexian.top/Article/details/gtchgrboaq.html

[T47] Perl：正则捕获
来源：http://dali.guannengcc.top/Article/details/gtiyhhvdut.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.bjfxy.top/Article/details/gtbmatovqv.html

[T48] Perl：正则替换
来源：http://dali.mhx1999.top/Article/details/gtvthuxjcj.html

$s =~ s/old/new/g;
来源：http://dali.tianlin.xyz/Article/details/gtuxtwfopf.html

[T49] Perl：函数
来源：http://dali.aibaodan.cn/Article/details/gtphfyyiag.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xuetiantiany.cn/Article/details/gtegexogxr.html

[T50] Perl：逐行读文件
来源：http://dali.yangfankeji.com/Article/details/gtrhjtxzpy.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.guannengcc.top/Article/details/gtmolvoisp.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.daxiang520.top/Article/details/gtgpzkerro.html

[T51] Scala：Hello World
来源：http://dali.tianlin.xyz/Article/details/gtncrxvjag.html

println("Hello")
来源：http://dali.sxryk.cn/Article/details/gtwivsogep.html

[T52] Scala：变量
来源：http://dali.quarkkingdee.top/Article/details/gtdvxfqjsf.html

val a = 1;  var b = 2
来源：http://dali.zhongyouzk.top/Article/details/gtrzuxfztk.html

[T53] Scala：字符串插值
来源：http://dali.jiagoushi.top/Article/details/gtejgkezoo.html

s"值: $b"
来源：http://dali.sufxvd.cn/Article/details/gtrpucujzo.html

[T54] Scala：集合映射
来源：http://dali.havefunace.top/Article/details/gtewlnffsq.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.yuanzhike.top/Article/details/gtxcfpelzm.html

[T55] Scala：集合过滤
来源：http://dali.kuanghao11.cn/Article/details/gtkuhsfesi.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gterljmlxb.html

[T56] Scala：样例类
来源：http://dali.quarkkingdee.top/Article/details/gtqrfsuvfw.html

case class User(name: String, age: Int)
来源：http://dali.havefunace.top/Article/details/gtrtajetoc.html

[T57] Scala：模式匹配
来源：http://dali.havefunace.top/Article/details/gtpcosahyd.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.meibo888.top/Article/details/gtpmvcftgd.html

[T58] Scala：函数定义
来源：http://dali.xuanzx.com/Article/details/gtxhrhkssa.html


<!-- 参考信息 -->