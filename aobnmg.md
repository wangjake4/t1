代发 wailian999

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yangfankeji.com/Article/details/gtnvzrxotm.html

[R60] 只看 HTTP 状态码
来源：http://dali.cqqwz.cn/Article/details/gtenqcwths.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ppjwa.cn/Article/details/gtowxfvlnd.html

[R61] 磁盘占用
来源：http://dali.hnxiangtu.top/Article/details/gtkjvnguki.html

df -h;  du -sh *
来源：http://dali.yuanzhike.top/Article/details/gtamlcekaz.html

[R62] 找最占空间的文件
来源：http://dali.snrcjt.cn/Article/details/gtfycgetzo.html

du -ah . | sort -rh | head -10
来源：http://dali.jyoumei.cn/Article/details/gtazxeqwvg.html

[R63] 内存与进程
来源：http://dali.aizwys.cn/Article/details/gtmawfftzf.html

free -h;  ps aux | grep nginx
来源：http://dali.yongpay.top/Article/details/gtvxijnbma.html

[R64] 结束进程
来源：http://dali.quarkkingdee.top/Article/details/gtshrdqcqg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gotoacloud.top/Article/details/gtpdpftmzh.html

[R65] 查看端口占用
来源：http://dali.pengpengdd.cyou/Article/details/gtjpbjhmbr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.wangdashe.top/Article/details/gtxhorqbzd.html

[R66] 定时任务
来源：http://dali.redwolf501.top/Article/details/gtlrzqloat.html

crontab -e;  crontab -l
来源：http://dali.hfpthk.cn/Article/details/gtvcoszhaz.html

[R67] 生成随机十六进制串
来源：http://dali.xuanzx.com/Article/details/gttccymipw.html

openssl rand -hex 16
来源：http://dali.316326.xyz/Article/details/gtzcgychad.html

[R68] 计算文件校验值
来源：http://dali.zhengqikj.top/Article/details/gteyibmcqe.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yuanzhike.top/Article/details/gtlzznfeeg.html

[R69] 生成随机密码
来源：http://dali.chenzaomai.com/Article/details/gtpbudmpor.html

head -c 16 /dev/urandom | base64
来源：http://dali.tianlin.xyz/Article/details/gtylpnfboc.html

[R70] 时间戳与互转
来源：http://dali.yongpay.top/Article/details/gtdsygmlvm.html

date +%s;  date -d @1700000000
来源：http://dali.gotoacloud.top/Article/details/gtqcjwtldz.html

[R71] 日期格式化
来源：http://dali.jiagoushi.top/Article/details/gtktgwqdbv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.daxiang520.top/Article/details/gtbgwbgnyf.html

[R72] 等待端口就绪
来源：http://dali.jianghu66.top/Article/details/gtytxyoqic.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jqgfzy.top/Article/details/gtunvkjdux.html

[R73] 分割大日志
来源：http://dali.birdmap.top/Article/details/gtbafcpfkq.html

split -l 1000 big.log part_
来源：http://dali.zhiwuduotai.top/Article/details/gtesejcfnd.html

[R74] 批量重命名
来源：http://dali.316326.xyz/Article/details/gtbraexvyv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.chenzaomai.com/Article/details/gtmbiqfedq.html

[R75] 导出环境变量
来源：http://dali.yueranfly.top/Article/details/gtvcmwomef.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhengqikj.top/Article/details/gtgovpxyiq.html

[R76] 使用临时文件
来源：http://dali.bjfxy.top/Article/details/gthyfxaaix.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhengqikj.top/Article/details/gttorfyibm.html

[R77] 读取用户输入
来源：http://dali.zdqjudy.top/Article/details/gtniwrxymc.html

read -rp "请输入: " ans
来源：http://dali.chenlongwang.top/Article/details/gtinflyeda.html

[R78] 交互式菜单
来源：http://dali.cashguo.top/Article/details/gtxpmiihdj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtqggzotah.html

[R79] 解析命令行选项
来源：http://dali.ydzc1.top/Article/details/gttzgarqgc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hysaishi.cn/Article/details/gtylrncqlb.html

[R80] 查看脚本执行耗时
来源：http://dali.hysaishi.cn/Article/details/gtcgynnjfy.html

time ./run.sh
来源：http://dali.mhx1999.top/Article/details/gtdcqgfcwm.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtijmrrvjo.html

S. C / C++ 专题
来源：http://dali.ybcxt.top/Article/details/gtpkjsfeuo.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtlftnppsm.html

[S01] C：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtnmdtrakk.html

#include <stdio.h>
来源：http://dali.yuxming.cn/Article/details/gtxvxzucxy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.smart0.xyz/Article/details/gtadusrrmz.html

[S02] C：变量与格式化输出
来源：http://dali.aibaodan.cn/Article/details/gtfheuwtgo.html

int a = 10; printf("%d\n", a);
来源：http://dali.shanyushiyangkeji.top/Article/details/gthchotrpm.html

[S03] C：读入整数
来源：http://dali.wangdashe.top/Article/details/gtmoynphlh.html

int x; scanf("%d", &x);
来源：http://dali.shangyingyoupin.top/Article/details/gtksrzrupu.html

[S04] C：字符串复制
来源：http://dali.yvedp.cn/Article/details/gtxrmufyuz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yvedp.cn/Article/details/gtitfslkga.html

[S05] C：字符串长度
来源：http://dali.haohaochexian.top/Article/details/gttrsqixtp.html

strlen(s)
来源：http://dali.xziqi.cn/Article/details/gtruhlzxdd.html

[S06] C：字符串比较
来源：http://dali.ivvv.top/Article/details/gtcmygokjv.html

strcmp(a, b) == 0
来源：http://dali.nanxinkj.top/Article/details/gtaptvsuoj.html

[S07] C：数组遍历求和
来源：http://dali.sweek.top/Article/details/gtdwmriztv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.chenjidiqi.icu/Article/details/gthfswnake.html

[S08] C：动态内存分配与释放
来源：http://dali.xinyue.icu/Article/details/gtdubwcnjk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nanxuanxn.top/Article/details/gtwjjxbxrb.html

[S09] C：结构体定义与初始化
来源：http://dali.daxiang520.top/Article/details/gtphigchds.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.redwolf501.top/Article/details/gttubefcwk.html

[S10] C：指针与解引用
来源：http://dali.dianchejie.cn/Article/details/gtgnhwjyus.html

int *p = &a;  *p = 5;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpynclmuv.html

[S11] C：逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gtysgehwpw.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.tanke756.top/Article/details/gtpvmcordf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shangyingyoupin.top/Article/details/gtrxilrdeq.html

fclose(f);
来源：http://dali.yj202588.top/Article/details/gtwuwaohkk.html

[S12] C：写文件
来源：http://dali.bjfxy.top/Article/details/gtdkafektw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cucudq.cn/Article/details/gtukhcqjix.html

[S13] C：宏定义
来源：http://dali.zhengqikj.top/Article/details/gtqyofyvou.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cashguo.top/Article/details/gtnvrxoydz.html

[S14] C：枚举
来源：http://dali.0kj1m.cn/Article/details/gtemmeaiwj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jianghu66.top/Article/details/gtiouwfqys.html

[S15] C：类型转换
来源：http://dali.ppjwa.cn/Article/details/gtydholmvd.html

(double) a / b
来源：http://dali.jinghuilouyu.cn/Article/details/gtetjrhcsa.html

[S16] C：位操作置位
来源：http://dali.c1oappe.top/Article/details/gtnridllqi.html

x |= (1 << 3);
来源：http://dali.fzhhl.top/Article/details/gtckoqbdmx.html

[S17] C：安全拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtgnmekaww.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsmrsacrc.html

[S18] C：命令行参数
来源：http://dali.yueranfly.top/Article/details/gtogkrpfhl.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gtswwgaizi.html

[S19] C：快速排序
来源：http://dali.zhixingplan.top/Article/details/gtrlquuxkb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gtivxhnaui.html

[S20] C：二分查找
来源：http://dali.316326.xyz/Article/details/gtcltducqx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.chenjidiqi.icu/Article/details/gtpmhtrnaa.html

[S21] C：字符类别判断
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxdwlpzct.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jqgufenzy.top/Article/details/gteisdaock.html

[S22] C：字符串转数字
来源：http://dali.shzxlz.cn/Article/details/gtvajqeuoa.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.redwolf501.top/Article/details/gtbkuvuaar.html

[S23] C：随机数
来源：http://dali.aizwys.cn/Article/details/gtmqcbrdor.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.vqdsnc.cn/Article/details/gttgvbmvyb.html

[S24] C：获取本地时间
来源：http://dali.daxiang520.top/Article/details/gtrltjjhwq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.pengpengdd.cyou/Article/details/gttpgrysvm.html

[S25] C：内存拷贝
来源：http://dali.yueranfly.top/Article/details/gtfvdbogkr.html

memcpy(dst, src, n);
来源：http://dali.jlsjyb.cn/Article/details/gtfhfusxdm.html

[S26] C：内存清零
来源：http://dali.yj202588.top/Article/details/gtooiyogit.html

memset(a, 0, sizeof a);
来源：http://dali.jinqigfzy.top/Article/details/gtfnpopqcq.html

[S27] C：定义常量
来源：http://dali.chenzaomai.com/Article/details/gtlfvmsvdo.html

const double PI = 3.14159;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbpfhgnjj.html

[S28] C：静态变量
来源：http://dali.9152youxi.cn/Article/details/gtvsmdhfgn.html

static int counter = 0;
来源：http://dali.zhengqikj.top/Article/details/gttcuwexjp.html

[S29] C：变参函数
来源：http://dali.dashuyun.cn/Article/details/gtzhtaqscn.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yj202588.top/Article/details/gtcbytauma.html

[S30] C：头文件保护
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzytzvzec.html

#ifndef X_H
来源：http://dali.hongshengwenyu.top/Article/details/gtvecaocbd.html

#define X_H
来源：http://dali.zycfv.cn/Article/details/gtqwggroru.html

#endif
来源：http://dali.tianlin.xyz/Article/details/gtbaezpofe.html

[S31] C++：Hello World
来源：http://dali.redwolf501.top/Article/details/gtpktgyczr.html

#include <iostream>
来源：http://dali.andypj.xyz/Article/details/gtyehvioij.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.haohaochexian.top/Article/details/gtbblhaluy.html

[S32] C++：字符串
来源：http://dali.zycfv.cn/Article/details/gtcqbuyybj.html

std::string s = "hi";  s += "!";
来源：http://dali.9152youxi.cn/Article/details/gtumgzprtj.html

[S33] C++：vector 增删
来源：http://dali.daria6918.cn/Article/details/gtnwbgmnun.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yangfankeji.com/Article/details/gtgtniwddb.html

[S34] C++：遍历 vector
来源：http://dali.feifeiyinyue.top/Article/details/gtlbcixpux.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xylfe.cn/Article/details/gtzdqcoeal.html

[S35] C++：map
来源：http://dali.cheryme.top/Article/details/gtonmzjswp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gtuwkcvasz.html

[S36] C++：unordered_map
来源：http://dali.zhiwuduotai.top/Article/details/gtuywderbd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.havefunace.top/Article/details/gtqbnmoxql.html

[S37] C++：set
来源：http://dali.sweek.top/Article/details/gtpcjgotyz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.iojbl.cn/Article/details/gtdjcduhxy.html

[S38] C++：排序
来源：http://dali.vqdsnc.cn/Article/details/gtssochbjo.html

std::sort(v.begin(), v.end());
来源：http://dali.jinqigfzy.top/Article/details/gteqfgpmyk.html

[S39] C++：自定义比较器排序
来源：http://dali.vqdsnc.cn/Article/details/gtboxzgnmc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zdqjudy.top/Article/details/gtuhrnxezx.html

[S40] C++：查找元素
来源：http://dali.nanxuanxn.top/Article/details/gthuzjeyhq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yongpay.top/Article/details/gtdpjcltfz.html

[S41] C++：类与构造函数
来源：http://dali.aibaodan.cn/Article/details/gtkrykkqej.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cashguo.top/Article/details/gtkuxorhsq.html

[S42] C++：继承与虚函数
来源：http://dali.hongshengwenyu.top/Article/details/gtxrpivtvr.html

class B : public Base { public: void f() override {} };
来源：http://dali.sufxvd.cn/Article/details/gtnebutqsp.html

[S43] C++：智能指针
来源：http://dali.tanke756.top/Article/details/gtzbhyxgvk.html

auto p = std::make_unique<int>(5);
来源：http://dali.jyoumei.cn/Article/details/gtmxenionr.html

[S44] C++：引用传参
来源：http://dali.yonumen.top/Article/details/gtdfhudprl.html

void inc(int &x) { ++x; }
来源：http://dali.yj20258888.top/Article/details/gtvtlebsep.html

[S45] C++：lambda
来源：http://dali.bjfxy.top/Article/details/gtcezjcpdt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gaohongyu789.top/Article/details/gtuiyxxyju.html

[S46] C++：函数模板
来源：http://dali.gaohongyu789.top/Article/details/gtnpjvzseo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.aizwys.cn/Article/details/gtbjdmvpal.html

[S47] C++：结构化绑定遍历
来源：http://dali.sysykeji.top/Article/details/gtjwdyrrvd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.chenjidiqi.icu/Article/details/gtjafrbkga.html

[S48] C++：逐行读文件
来源：http://dali.ivvv.top/Article/details/gtlteyoyyj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.0kj1m.cn/Article/details/gtszqjggtk.html

while (std::getline(in, line)) { }
来源：http://dali.nwbrower.top/Article/details/gtqjndfnyl.html

[S49] C++：写文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gthptytmoo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ybcxt.top/Article/details/gtayqcxuvk.html

[S50] C++：格式化数字
来源：http://dali.aibaodan.cn/Article/details/gtusujpvex.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gtygtydlrm.html

[S51] C++：显式类型转换
来源：http://dali.yonumen.top/Article/details/gtepwzyhrd.html

static_cast<double>(a) / b
来源：http://dali.tianlin.xyz/Article/details/gtljgwqdgf.html

[S52] C++：const 与 noexcept
来源：http://dali.haohaochexian.top/Article/details/gtmpdvpqwg.html

int size() const noexcept { return n_; }
来源：http://dali.gogol.net.cn/Article/details/gtzbnimjjc.html

[S53] C++：移动语义
来源：http://dali.snrcjt.cn/Article/details/gtnhqlgtsu.html

std::vector<int> w = std::move(v);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgiglidbo.html

[S54] C++：异常处理
来源：http://dali.birdmap.top/Article/details/gtevnavszk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ppjwa.cn/Article/details/gtpckdmdzq.html

[S55] C++：结构化绑定
来源：http://dali.gaohongyu789.top/Article/details/gtbdqrwrbc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.aibaodan.cn/Article/details/gtzvhkqhck.html

[S56] C++：optional
来源：http://dali.yuxming.cn/Article/details/gtoaongjww.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xinyue.icu/Article/details/gtsbudvljv.html

[S57] C++：编译期常量
来源：http://dali.cqqwz.cn/Article/details/gtxopwsrkk.html

constexpr int N = 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtedovksbg.html

[S58] C++：命名空间
来源：http://dali.sufxvd.cn/Article/details/gtqkigtcpt.html

namespace ns { int f() { return 1; } }
来源：http://dali.shzxlz.cn/Article/details/gthaleskst.html

[S59] C++：静态断言
来源：http://dali.hnxiangtu.top/Article/details/gtbmccxcta.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cqqwz.cn/Article/details/gtytjixeki.html

[S60] C++：遍历并删除元素
来源：http://dali.sufxvd.cn/Article/details/gtmdynuemh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhoulong.xyz/Article/details/gtevyfevqw.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtoqxfpmpe.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jqgfzy.top/Article/details/gtnpjyeymd.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtkfrgvpfd.html

[T01] Kotlin：Hello World
来源：http://dali.shzxlz.cn/Article/details/gteuxjgcil.html

println("Hello")
来源：http://dali.jyoumei.cn/Article/details/gtrybhayxd.html

[T02] Kotlin：变量
来源：http://dali.cqqwz.cn/Article/details/gtvlotyuxm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ydzc1.top/Article/details/gtqpsotkjy.html

[T03] Kotlin：字符串模板
来源：http://dali.cashguo.top/Article/details/gtcrbiqqyc.html

"值: $b"
来源：http://dali.xziqi.cn/Article/details/gtnpkfnemw.html

[T04] Kotlin：空安全
来源：http://dali.tianlin.xyz/Article/details/gtdrjbbftl.html

val n: String? = null;  n?.length
来源：http://dali.yueranfly.top/Article/details/gtotdpxnoa.html

[T05] Kotlin：when 表达式
来源：http://dali.jianghu66.top/Article/details/gtdrjtkhyi.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.meibo888.top/Article/details/gtxxupcgaq.html

[T06] Kotlin：集合映射
来源：http://dali.xuanzx.com/Article/details/gtnlvpjaex.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.c1oappe.top/Article/details/gtybqatgdg.html

[T07] Kotlin：集合过滤
来源：http://dali.gotoacloud.top/Article/details/gtmxtunarg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yj202588.top/Article/details/gtkagbianm.html

[T08] Kotlin：数据类
来源：http://dali.xinyue.icu/Article/details/gtqqphjiaq.html

data class User(val name: String, val age: Int)
来源：http://dali.gzhubu.top/Article/details/gtglsmmpvs.html

[T09] Kotlin：扩展函数
来源：http://dali.sxryk.cn/Article/details/gtkfofhwkq.html

fun String.exclaim() = this + "!"
来源：http://dali.zhoulong.xyz/Article/details/gtwjjyqudg.html

[T10] Kotlin：默认参数
来源：http://dali.yangfankeji.com/Article/details/gtwypwoftm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.c1oappe.top/Article/details/gtmsdkiwjr.html

[T11] Kotlin：协程
来源：http://dali.fzhhl.top/Article/details/gtuuxypeiq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cashguo.top/Article/details/gtcdodqhia.html

[T12] Kotlin：解构声明
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkuxwomrf.html

val (a, b) = Pair(1, 2)
来源：http://dali.xylfe.cn/Article/details/gtpqocjpwh.html

[T13] Kotlin：只读 Map
来源：http://dali.daxiang520.top/Article/details/gtsvcozkoc.html

val m = mapOf("a" to 1)
来源：http://dali.nanxuanxn.top/Article/details/gtwzggzfed.html

[T14] Kotlin：循环
来源：http://dali.hfpthk.cn/Article/details/gtwsjdrpuy.html

for (i in 1..10) println(i)
来源：http://dali.yueranfly.top/Article/details/gtheezizwc.html

[T15] Kotlin：接口
来源：http://dali.jinqigfzy.top/Article/details/gtahftexsc.html

interface Shape { fun area(): Double }
来源：http://dali.yj202588.top/Article/details/gtxqimforv.html

[T16] Swift：Hello World
来源：http://dali.cdnleiting.top/Article/details/gtfbxgmlkn.html

print("Hello")
来源：http://dali.gaohongyu789.top/Article/details/gtbjlsfoll.html

[T17] Swift：变量与常量
来源：http://dali.ivvv.top/Article/details/gtmqeipphh.html

var a = 1;  let b = 2
来源：http://dali.gotoacloud.top/Article/details/gtqigbpxva.html

[T18] Swift：字符串插值
来源：http://dali.yj202588.top/Article/details/gtisighoem.html

"值: \(b)"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtubndjedg.html

[T19] Swift：可选绑定
来源：http://dali.jinqigfzy.top/Article/details/gtfcftbvdx.html

if let n = opt { print(n) }
来源：http://dali.birdmap.top/Article/details/gtwcktyvii.html

[T20] Swift：数组操作
来源：http://dali.jinqigufen.top/Article/details/gtjxefnrrp.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.quarkkingdee.top/Article/details/gtokxbvuhg.html

[T21] Swift：遍历
来源：http://dali.chenlongwang.top/Article/details/gtolepnxjt.html

for x in a { print(x) }
来源：http://dali.nwbrower.top/Article/details/gtbvbdsslg.html

[T22] Swift：字典
来源：http://dali.jinghuilouyu.cn/Article/details/gtwqdyhnze.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jyoumei.cn/Article/details/gtsjyfxseu.html

[T23] Swift：函数
来源：http://dali.svipenyu.cn/Article/details/gtvymwupig.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.wangshuangyany.cn/Article/details/gtyhkracli.html

[T24] Swift：闭包
来源：http://dali.nanxinkj.top/Article/details/gtckqkvgnh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaddevtfi.html

[T25] Swift：结构体
来源：http://dali.hammf.cn/Article/details/gtsmpgwgyb.html

struct P { var x: Int }
来源：http://dali.nanxinkj.top/Article/details/gtfzbpqqch.html

[T26] Swift：类与重写
来源：http://dali.yuxming.cn/Article/details/gtaqqzsgzc.html

class A: Base { override func f() {} }
来源：http://dali.9152youxi.cn/Article/details/gtnrlalubc.html

[T27] Swift：错误处理
来源：http://dali.shangyingyoupin.top/Article/details/gtftdydfcl.html

do { try f() } catch { print(error) }
来源：http://dali.gotoacloud.top/Article/details/gthmzblyqo.html

[T28] Swift：枚举
来源：http://dali.cucudq.cn/Article/details/gtgcclhdrq.html

enum Color { case red, green }
来源：http://dali.jinqigfzy.top/Article/details/gtztkwnred.html

[T29] Swift：guard 提前返回
来源：http://dali.yvedp.cn/Article/details/gtkbpnihqm.html

guard let x = opt else { return }
来源：http://dali.pycfn.com/Article/details/gtwjhrszqs.html

[T30] Swift：协议
来源：http://dali.ppjwa.cn/Article/details/gtrunctgdk.html

protocol Shape { func area() -> Double }
来源：http://dali.tianlin.xyz/Article/details/gteengmrlc.html

[T31] Lua：Hello World
来源：http://dali.ehwqpu.com/Article/details/gtpoiuyjln.html

print("Hello")
来源：http://dali.cashguo.top/Article/details/gtnmzjxsqe.html

[T32] Lua：局部变量
来源：http://dali.chenlongwang.top/Article/details/gtgwahqhjd.html

local a = 1
来源：http://dali.cdnleiting.top/Article/details/gtslwkpjqd.html

[T33] Lua：表（数组）
来源：http://dali.jqgfzy.top/Article/details/gtkijnzedz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.dashuyun.cn/Article/details/gtmxfkvaxj.html

[T34] Lua：遍历表
来源：http://dali.gogol.net.cn/Article/details/gtcgsaqlov.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hywenlv.cn/Article/details/gtwjmpwoww.html

[T35] Lua：字典表
来源：http://dali.smart0.xyz/Article/details/gtulofqjzm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhixingplan.top/Article/details/gtdteugwrf.html

[T36] Lua：函数
来源：http://dali.snrcjt.cn/Article/details/gtwtwqdrkj.html

function add(a, b) return a + b end
来源：http://dali.sweek.top/Article/details/gtftigksvt.html

[T37] Lua：字符串拼接
来源：http://dali.dianchejie.cn/Article/details/gtpxbnymhv.html

"a" .. "b"
来源：http://dali.yuxming.cn/Article/details/gtiaopobck.html

[T38] Lua：条件
来源：http://dali.yonumen.top/Article/details/gtenhufitz.html

if x > 0 then print("正") end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkrkqjkyf.html

[T39] Lua：模式匹配
来源：http://dali.yuanzhike.top/Article/details/gthqmcrhhe.html

string.find(s, "%d+")
来源：http://dali.gogol.net.cn/Article/details/gthelhipel.html

[T40] Lua：元表
来源：http://dali.zdqjudy.top/Article/details/gtwdvcvbyf.html

setmetatable({}, { __index = base })
来源：http://dali.smart0.xyz/Article/details/gtwlnrdstb.html

[T41] Perl：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtuexgjzeh.html

print "Hello\n";
来源：http://dali.gaohongyu789.top/Article/details/gthieyukfq.html

[T42] Perl：变量类型
来源：http://dali.hnxiangtu.top/Article/details/gtcgcxfkwk.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.nwbrower.top/Article/details/gtovmtyezm.html

[T43] Perl：字符串插值
来源：http://dali.nanxuanxn.top/Article/details/gtrnjigsrt.html

"值: $a"
来源：http://dali.xylfe.cn/Article/details/gtfmgmwjua.html

[T44] Perl：条件
来源：http://dali.zdqjudy.top/Article/details/gtmmvhlmbw.html

if ($a > 0) { print "正"; }
来源：http://dali.hfpthk.cn/Article/details/gtewugxnwd.html

[T45] Perl：数组遍历
来源：http://dali.xinyue.icu/Article/details/gtqqyjdtmo.html

for my $x (@arr) { print $x; }
来源：http://dali.hammf.cn/Article/details/gtdavkekdj.html

[T46] Perl：哈希操作
来源：http://dali.yj202588.top/Article/details/gtqlmwazwi.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.jqgufenzy.top/Article/details/gtvnblsqqg.html

[T47] Perl：正则捕获
来源：http://dali.jqgufenzy.top/Article/details/gthicqptmw.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.daria6918.cn/Article/details/gtyxppylwa.html

[T48] Perl：正则替换
来源：http://dali.birdmap.top/Article/details/gtcgbvgrzy.html

$s =~ s/old/new/g;
来源：http://dali.cqqwz.cn/Article/details/gtcgvgmniv.html

[T49] Perl：函数
来源：http://dali.zhoulong.xyz/Article/details/gtavlsakdk.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.dashuyun.cn/Article/details/gtmpmgkfam.html

[T50] Perl：逐行读文件
来源：http://dali.zhixingplan.top/Article/details/gtfdchmaqa.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.xinyue.icu/Article/details/gtkuwlngpl.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.daria6918.cn/Article/details/gttawlfdse.html

[T51] Scala：Hello World
来源：http://dali.yongpay.top/Article/details/gtlbyokvfk.html

println("Hello")
来源：http://dali.bjfxy.top/Article/details/gtlmapqihm.html

[T52] Scala：变量
来源：http://dali.xinyue.icu/Article/details/gtylksrpyz.html

val a = 1;  var b = 2
来源：http://dali.nwbrower.top/Article/details/gtczufbnud.html

[T53] Scala：字符串插值
来源：http://dali.kuanghao11.cn/Article/details/gtebwwcvnu.html

s"值: $b"
来源：http://dali.zhoulong.xyz/Article/details/gtmaqlywmv.html

[T54] Scala：集合映射
来源：http://dali.gaohongyu789.top/Article/details/gtkubrdvih.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.hywenlv.cn/Article/details/gtxzbkxqry.html

[T55] Scala：集合过滤
来源：http://dali.jiagoushi.top/Article/details/gtkaxchqsk.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.jiagoushi.top/Article/details/gtfughrwru.html

[T56] Scala：样例类
来源：http://dali.yj20258888.top/Article/details/gtzeztulwg.html

case class User(name: String, age: Int)
来源：http://dali.zhixingplan.top/Article/details/gtkuqewuny.html

[T57] Scala：模式匹配
来源：http://dali.dashuyun.cn/Article/details/gtuowtvwac.html

x match { case 1 => "一"; case _ => "其他" }
来源：http://dali.hongshengwenyu.top/Article/details/gtynqfeaoz.html

[T58] Scala：函数定义
来源：http://dali.smart0.xyz/Article/details/gtmfvwpxqu.html

def add(a: Int, b: Int): Int = a + b
来源：http://dali.cashguo.top/Article/details/gtmpumnkyv.html

[T59] Scala：循环
来源：http://dali.gaohongyu789.top/Article/details/gtlkjjjnuu.html

for (i <- 1 to 10) println(i)
来源：http://dali.vqdsnc.cn/Article/details/gtbvngbgza.html

[T60] Scala：折叠
来源：http://dali.dashuyun.cn/Article/details/gtwmlgbxzb.html

List(1, 2, 3).foldLeft(0)(_ + _)
来源：http://dali.sysykeji.top/Article/details/gtbbszygqc.html

================================================================================
来源：http://dali.nanxinkj.top/Article/details/gtnpqysyyk.html

U. 高频实用片段（Python / PHP / JavaScript 各 40 条）
来源：http://dali.feifeiyinyue.top/Article/details/gtotmwtheb.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtijqknrhy.html


<!-- 参考信息 -->