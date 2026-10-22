代发 wailian999

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.dashuyun.cn/Article/details/gtpvicuxgg.html

[R52] 统计行数
来源：http://dali.aibaodan.cn/Article/details/gtmcdxuypm.html

wc -l a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtksjhoodh.html

[R53] 查看文件头与实时尾
来源：http://dali.tian-w.cn/Article/details/gttcxzvvtl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yvedp.cn/Article/details/gtepecqkcw.html

[R54] 比较两个文件
来源：http://dali.jinqigfzy.top/Article/details/gteeobmzqo.html

diff a.txt b.txt
来源：http://dali.hysaishi.cn/Article/details/gtovdvrula.html

[R55] 压缩与解压
来源：http://dali.zhengqikj.top/Article/details/gtqmpmelcl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yuxming.cn/Article/details/gtzcpkmjzp.html

[R56] 远程拷贝
来源：http://dali.cucudq.cn/Article/details/gtezxyqlzy.html

scp file user@host:/path/
来源：http://dali.aizwys.cn/Article/details/gtzlwqjsdi.html

[R57] 远程执行命令
来源：http://dali.yuanzhike.top/Article/details/gtqjiilith.html

ssh user@host 'uptime'
来源：http://dali.vqdsnc.cn/Article/details/gtshdzmspy.html

[R58] 下载文件
来源：http://dali.yj20258888.top/Article/details/gtdfqkwsah.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jlsjyb.cn/Article/details/gtzwrbvivl.html

[R59] 发 POST JSON
来源：http://dali.ybcxt.top/Article/details/gtynorfoag.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yongpay.top/Article/details/gtolwykeiw.html

[R60] 只看 HTTP 状态码
来源：http://dali.havefunace.top/Article/details/gtvpmyjfjm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ppjwa.cn/Article/details/gtxhrcsfrv.html

[R61] 磁盘占用
来源：http://dali.quarkkingdee.top/Article/details/gtzvarjspl.html

df -h;  du -sh *
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbjttkrke.html

[R62] 找最占空间的文件
来源：http://dali.zhoulong.xyz/Article/details/gtogvsbrfg.html

du -ah . | sort -rh | head -10
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqtyyyonc.html

[R63] 内存与进程
来源：http://dali.gaohongyu789.top/Article/details/gtuhznnsgv.html

free -h;  ps aux | grep nginx
来源：http://dali.ivvv.top/Article/details/gtrbvdctfw.html

[R64] 结束进程
来源：http://dali.chenjidiqi.icu/Article/details/gtqlvfcfcz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hfpthk.cn/Article/details/gtygqurbpk.html

[R65] 查看端口占用
来源：http://dali.redwolf501.top/Article/details/gtsxwryudz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj20258888.top/Article/details/gttdnypjcf.html

[R66] 定时任务
来源：http://dali.shzxlz.cn/Article/details/gtkweggzow.html

crontab -e;  crontab -l
来源：http://dali.ydzc1.top/Article/details/gthvowvoqh.html

[R67] 生成随机十六进制串
来源：http://dali.yueranfly.top/Article/details/gtfftalgmz.html

openssl rand -hex 16
来源：http://dali.snrcjt.cn/Article/details/gtnfsqtjqj.html

[R68] 计算文件校验值
来源：http://dali.jinqigufen.top/Article/details/gtsaawpsfb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jyoumei.cn/Article/details/gtcbxquzfw.html

[R69] 生成随机密码
来源：http://dali.tianlin.xyz/Article/details/gthrzgarhy.html

head -c 16 /dev/urandom | base64
来源：http://dali.jiagoushi.top/Article/details/gtfegosrhs.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gtknyulrmn.html

date +%s;  date -d @1700000000
来源：http://dali.cqqwz.cn/Article/details/gtlakrjsfp.html

[R71] 日期格式化
来源：http://dali.zhongyouzk.top/Article/details/gttevetgmk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwejuijql.html

[R72] 等待端口就绪
来源：http://dali.mhx1999.top/Article/details/gtonybsrcn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.9152youxi.cn/Article/details/gtywhpmvqz.html

[R73] 分割大日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdepdpdbr.html

split -l 1000 big.log part_
来源：http://dali.zycfv.cn/Article/details/gtuaswdrnu.html

[R74] 批量重命名
来源：http://dali.chenzaomai.com/Article/details/gthtffhksh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtftqutvzz.html

[R75] 导出环境变量
来源：http://dali.kuanghao11.cn/Article/details/gttlmqwycg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xuetiantiany.cn/Article/details/gtgjphsxgz.html

[R76] 使用临时文件
来源：http://dali.nanxuanxn.top/Article/details/gtklprigxb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenlongwang.top/Article/details/gtfsekamys.html

[R77] 读取用户输入
来源：http://dali.yonumen.top/Article/details/gtdpgyrptq.html

read -rp "请输入: " ans
来源：http://dali.zhoulong.xyz/Article/details/gtxcbrzote.html

[R78] 交互式菜单
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyxusrhfm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ydzc1.top/Article/details/gtxictjxoy.html

[R79] 解析命令行选项
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiqmuwtav.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jianghu66.top/Article/details/gtnvepsaux.html

[R80] 查看脚本执行耗时
来源：http://dali.cheryme.top/Article/details/gtihexgcqc.html

time ./run.sh
来源：http://dali.redwolf501.top/Article/details/gtgczsgslm.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtdmzznfnh.html

S. C / C++ 专题
来源：http://dali.wangshuangyany.cn/Article/details/gtfxbuolfv.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtfbzppzpo.html

[S01] C：Hello World
来源：http://dali.jianghu66.top/Article/details/gtsitwilsz.html

#include <stdio.h>
来源：http://dali.jianghu66.top/Article/details/gtlumhvcwg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.aibaodan.cn/Article/details/gtphozgnuk.html

[S02] C：变量与格式化输出
来源：http://dali.jqgfzy.top/Article/details/gtllppsixt.html

int a = 10; printf("%d\n", a);
来源：http://dali.svipenyu.cn/Article/details/gtxabxdlao.html

[S03] C：读入整数
来源：http://dali.cucudq.cn/Article/details/gtocbhzvwp.html

int x; scanf("%d", &x);
来源：http://dali.yvedp.cn/Article/details/gttpwflzrv.html

[S04] C：字符串复制
来源：http://dali.guowangkeji.top/Article/details/gtmfrlnefi.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.aibaodan.cn/Article/details/gtgoxnxpfg.html

[S05] C：字符串长度
来源：http://dali.c1oappe.top/Article/details/gtpafrawnm.html

strlen(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtomhqenfs.html

[S06] C：字符串比较
来源：http://dali.guannengcc.top/Article/details/gtyjjxnstv.html

strcmp(a, b) == 0
来源：http://dali.hfpthk.cn/Article/details/gtzkphjibu.html

[S07] C：数组遍历求和
来源：http://dali.ydzc1.top/Article/details/gtjgchdlkz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.fengsongda.top/Article/details/gtntdfwiwv.html

[S08] C：动态内存分配与释放
来源：http://dali.316326.xyz/Article/details/gtrtwduity.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.chenlongwang.top/Article/details/gtlbszuies.html

[S09] C：结构体定义与初始化
来源：http://dali.guannengcc.top/Article/details/gtkjrstylt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sysykeji.top/Article/details/gtoikervvv.html

[S10] C：指针与解引用
来源：http://dali.chenzaomai.com/Article/details/gtkhyxguke.html

int *p = &a;  *p = 5;
来源：http://dali.fzhhl.top/Article/details/gtbvmqbygo.html

[S11] C：逐行读文件
来源：http://dali.sysykeji.top/Article/details/gtjxybpgik.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.chenzaomai.com/Article/details/gtnlzdbxbx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cheryme.top/Article/details/gtsbbazcti.html

fclose(f);
来源：http://dali.jqgufenzy.top/Article/details/gttoooolvz.html

[S12] C：写文件
来源：http://dali.fzhhl.top/Article/details/gtvjzplnma.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhiwuduotai.top/Article/details/gtsigezpmh.html

[S13] C：宏定义
来源：http://dali.quarkkingdee.top/Article/details/gtiueygqdk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.0kj1m.cn/Article/details/gtdzaidsfz.html

[S14] C：枚举
来源：http://dali.hysaishi.cn/Article/details/gtxxvifsdk.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.nanxinkj.top/Article/details/gteyqkeerq.html

[S15] C：类型转换
来源：http://dali.jiagoushi.top/Article/details/gtecdjzuec.html

(double) a / b
来源：http://dali.jyoumei.cn/Article/details/gtfcmgypaz.html

[S16] C：位操作置位
来源：http://dali.hnxiangtu.top/Article/details/gtgzfsflql.html

x |= (1 << 3);
来源：http://dali.ppjwa.cn/Article/details/gtoyiscpjs.html

[S17] C：安全拼接字符串
来源：http://dali.andypj.xyz/Article/details/gtwzezplez.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xuetiantiany.cn/Article/details/gtlybihncm.html

[S18] C：命令行参数
来源：http://dali.jiagoushi.top/Article/details/gttpgxcrja.html

int main(int argc, char **argv)
来源：http://dali.zycfv.cn/Article/details/gtwctktoda.html

[S19] C：快速排序
来源：http://dali.sweek.top/Article/details/gthvdxumim.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hammf.cn/Article/details/gtndfqypaj.html

[S20] C：二分查找
来源：http://dali.havefunace.top/Article/details/gttxffgecx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shuidangran.top/Article/details/gtuqevdeeg.html

[S21] C：字符类别判断
来源：http://dali.hfpthk.cn/Article/details/gtxzzoaljd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.pycfn.com/Article/details/gtwfrbtmpw.html

[S22] C：字符串转数字
来源：http://dali.shzxlz.cn/Article/details/gtzgnhlbdx.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shuidangran.top/Article/details/gtwyfilttu.html

[S23] C：随机数
来源：http://dali.redwolf501.top/Article/details/gtfucfcayf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhixingplan.top/Article/details/gtqfbykjhg.html

[S24] C：获取本地时间
来源：http://dali.zhongyouzk.top/Article/details/gtuzylfaqp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhixingplan.top/Article/details/gtbsklpqqo.html

[S25] C：内存拷贝
来源：http://dali.nanxinkj.top/Article/details/gtpqmnrfkv.html

memcpy(dst, src, n);
来源：http://dali.tianlin.xyz/Article/details/gttrzzpmei.html

[S26] C：内存清零
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkgnwsynx.html

memset(a, 0, sizeof a);
来源：http://dali.snrcjt.cn/Article/details/gtrudowdpv.html

[S27] C：定义常量
来源：http://dali.fzhhl.top/Article/details/gtjigdksml.html

const double PI = 3.14159;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdohdljec.html

[S28] C：静态变量
来源：http://dali.cheryme.top/Article/details/gtwipyvazg.html

static int counter = 0;
来源：http://dali.zhengqikj.top/Article/details/gtnraxxcyp.html

[S29] C：变参函数
来源：http://dali.xuetiantiany.cn/Article/details/gtfjokbwdr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yanxiufei.cn/Article/details/gtnigictfc.html

[S30] C：头文件保护
来源：http://dali.tanke756.top/Article/details/gtdgozovoi.html

#ifndef X_H
来源：http://dali.smart0.xyz/Article/details/gtytgfmvku.html

#define X_H
来源：http://dali.ppjwa.cn/Article/details/gtmlqjoamp.html

#endif
来源：http://dali.cheryme.top/Article/details/gtnpgqryoe.html

[S31] C++：Hello World
来源：http://dali.ydzc1.top/Article/details/gtbiuxildj.html

#include <iostream>
来源：http://dali.tianlin.xyz/Article/details/gtkentowwz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.vqdsnc.cn/Article/details/gtnolqstlj.html

[S32] C++：字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpaiqchbh.html

std::string s = "hi";  s += "!";
来源：http://dali.shangyingyoupin.top/Article/details/gtrfqqtgfb.html

[S33] C++：vector 增删
来源：http://dali.birdmap.top/Article/details/gtlihtewgj.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtqgsbusni.html

[S34] C++：遍历 vector
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrcgusdei.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.meibo888.top/Article/details/gtygknhvlh.html

[S35] C++：map
来源：http://dali.dianchejie.cn/Article/details/gtrztorvuz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tanke756.top/Article/details/gtgaprerqb.html

[S36] C++：unordered_map
来源：http://dali.fzhhl.top/Article/details/gtpyvrabty.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gtbnwpxjfk.html

[S37] C++：set
来源：http://dali.ywan-chungtsiang.top/Article/details/gtokrzknzm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zdqjudy.top/Article/details/gtjexohvjr.html

[S38] C++：排序
来源：http://dali.zhongyouzk.top/Article/details/gtvsamabrv.html

std::sort(v.begin(), v.end());
来源：http://dali.gogol.net.cn/Article/details/gtavcdkpyj.html

[S39] C++：自定义比较器排序
来源：http://dali.nanxinkj.top/Article/details/gtmvrnrunz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jlsjyb.cn/Article/details/gthudyttye.html

[S40] C++：查找元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlfcwbjzv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.tanke756.top/Article/details/gtolvqtjvz.html

[S41] C++：类与构造函数
来源：http://dali.ppjwa.cn/Article/details/gtblzmrvlw.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhixingplan.top/Article/details/gtckfkkvyb.html

[S42] C++：继承与虚函数
来源：http://dali.xuanzx.com/Article/details/gtsrarisav.html

class B : public Base { public: void f() override {} };
来源：http://dali.ybcxt.top/Article/details/gtffulienh.html

[S43] C++：智能指针
来源：http://dali.kuanghao11.cn/Article/details/gtgrsrulrm.html

auto p = std::make_unique<int>(5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttcfxyqtl.html

[S44] C++：引用传参
来源：http://dali.yuanzhike.top/Article/details/gtebthhgvk.html

void inc(int &x) { ++x; }
来源：http://dali.tianlin.xyz/Article/details/gtuwzmgmov.html

[S45] C++：lambda
来源：http://dali.wangdashe.top/Article/details/gtvubefquf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nanxinkj.top/Article/details/gtrncufzbe.html

[S46] C++：函数模板
来源：http://dali.gaohongyu789.top/Article/details/gttkmddtfe.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yj20258888.top/Article/details/gtyiwciyyz.html

[S47] C++：结构化绑定遍历
来源：http://dali.zdqjudy.top/Article/details/gtfqbtqbvx.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.andypj.xyz/Article/details/gtatmpxmmp.html

[S48] C++：逐行读文件
来源：http://dali.nanxinkj.top/Article/details/gtryuqqrad.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ydzc1.top/Article/details/gtvqzjxupb.html

while (std::getline(in, line)) { }
来源：http://dali.sxryk.cn/Article/details/gtwiopvgix.html

[S49] C++：写文件
来源：http://dali.jlsjyb.cn/Article/details/gtyjeadxbe.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.wangshuangyany.cn/Article/details/gtiuuarevb.html

[S50] C++：格式化数字
来源：http://dali.jiagoushi.top/Article/details/gtvfihyzsc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tian-w.cn/Article/details/gtlzvixuqf.html

[S51] C++：显式类型转换
来源：http://dali.xziqi.cn/Article/details/gtcmvlcidt.html

static_cast<double>(a) / b
来源：http://dali.hongshengwenyu.top/Article/details/gtniuncvsx.html

[S52] C++：const 与 noexcept
来源：http://dali.zhaomingkeji.xyz/Article/details/gtedfmpatd.html

int size() const noexcept { return n_; }
来源：http://dali.haohaochexian.top/Article/details/gtdggqwudy.html

[S53] C++：移动语义
来源：http://dali.yangfankeji.com/Article/details/gtnqmbgzmg.html

std::vector<int> w = std::move(v);
来源：http://dali.zhijiandao.cn/Article/details/gtscjsmett.html

[S54] C++：异常处理
来源：http://dali.yonumen.top/Article/details/gtmdkjzfmh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.cdnleiting.top/Article/details/gtyhqiplcp.html

[S55] C++：结构化绑定
来源：http://dali.zhongyouzk.top/Article/details/gtqtnthvht.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.daxiang520.top/Article/details/gtfikieerv.html

[S56] C++：optional
来源：http://dali.fzhhl.top/Article/details/gtmpkprdhy.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.redwolf501.top/Article/details/gtkbsmedjl.html

[S57] C++：编译期常量
来源：http://dali.pycfn.com/Article/details/gtisqcyace.html

constexpr int N = 10;
来源：http://dali.jlsjyb.cn/Article/details/gtkrcmptcf.html

[S58] C++：命名空间
来源：http://dali.ydzc1.top/Article/details/gtndnxhynf.html

namespace ns { int f() { return 1; } }
来源：http://dali.jqgufenzy.top/Article/details/gtsdsiraup.html

[S59] C++：静态断言
来源：http://dali.yj20258.top/Article/details/gtcnqlhpct.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinqigfzy.top/Article/details/gtxlybhpsq.html

[S60] C++：遍历并删除元素
来源：http://dali.0kj1m.cn/Article/details/gtbqqczfjh.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gaohongyu789.top/Article/details/gtlknaaamw.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtlchtyhnq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hongshengwenyu.top/Article/details/gtzsvueoji.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtvrdjviwv.html

[T01] Kotlin：Hello World
来源：http://dali.havefunace.top/Article/details/gtrupejarv.html

println("Hello")
来源：http://dali.andypj.xyz/Article/details/gtcsoowktr.html

[T02] Kotlin：变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkwlcfcqa.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.guannengcc.top/Article/details/gtdtvhpnaw.html

[T03] Kotlin：字符串模板
来源：http://dali.pengpengdd.cyou/Article/details/gtmuoonaam.html

"值: $b"
来源：http://dali.hywenlv.cn/Article/details/gtezsxbnqw.html

[T04] Kotlin：空安全
来源：http://dali.316326.xyz/Article/details/gtdarzugbn.html

val n: String? = null;  n?.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtfuuwaiiz.html

[T05] Kotlin：when 表达式
来源：http://dali.meibo888.top/Article/details/gtjudwnltv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.tianlin.xyz/Article/details/gtrpkoplfs.html

[T06] Kotlin：集合映射
来源：http://dali.hnqzz.top/Article/details/gtbuanenzw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzjjfqwkl.html

[T07] Kotlin：集合过滤
来源：http://dali.yonumen.top/Article/details/gtkbwzihmz.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shangyingyoupin.top/Article/details/gtmineetdj.html

[T08] Kotlin：数据类
来源：http://dali.aibaodan.cn/Article/details/gtqullrtgd.html

data class User(val name: String, val age: Int)
来源：http://dali.iojbl.cn/Article/details/gtoemahhiu.html

[T09] Kotlin：扩展函数
来源：http://dali.yj20258.top/Article/details/gtkypochsk.html

fun String.exclaim() = this + "!"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqkmatyas.html

[T10] Kotlin：默认参数
来源：http://dali.jyoumei.cn/Article/details/gtyuwctysk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zdqjudy.top/Article/details/gtjruakuvd.html

[T11] Kotlin：协程
来源：http://dali.wangdashe.top/Article/details/gtgpbmbcyu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yj202588.top/Article/details/gtsfmiisrc.html

[T12] Kotlin：解构声明
来源：http://dali.wangdashe.top/Article/details/gtdsolexli.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjmqzgueu.html

[T13] Kotlin：只读 Map
来源：http://dali.yonumen.top/Article/details/gtqeelcjxb.html

val m = mapOf("a" to 1)
来源：http://dali.shuidangran.top/Article/details/gtzahaossf.html

[T14] Kotlin：循环
来源：http://dali.yvedp.cn/Article/details/gtknqlycsq.html

for (i in 1..10) println(i)
来源：http://dali.zhixingplan.top/Article/details/gtnxfuwjys.html

[T15] Kotlin：接口
来源：http://dali.aibaodan.cn/Article/details/gtgaqnrkmw.html

interface Shape { fun area(): Double }
来源：http://dali.bjfxy.top/Article/details/gtaamuycyn.html

[T16] Swift：Hello World
来源：http://dali.yongpay.top/Article/details/gtsktiigtt.html

print("Hello")
来源：http://dali.wangdashe.top/Article/details/gtwxvzfewo.html

[T17] Swift：变量与常量
来源：http://dali.fengsongda.top/Article/details/gtdhbbefud.html

var a = 1;  let b = 2
来源：http://dali.hammf.cn/Article/details/gtngzrbzvf.html

[T18] Swift：字符串插值
来源：http://dali.fzhhl.top/Article/details/gtqttbykva.html

"值: \(b)"
来源：http://dali.hammf.cn/Article/details/gttojqjvdc.html

[T19] Swift：可选绑定
来源：http://dali.yuanzhike.top/Article/details/gtcempvclw.html

if let n = opt { print(n) }
来源：http://dali.jiagoushi.top/Article/details/gtzxhfbldr.html

[T20] Swift：数组操作
来源：http://dali.quarkkingdee.top/Article/details/gtyqnlgifc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hnxiangtu.top/Article/details/gthaxpxfyl.html

[T21] Swift：遍历
来源：http://dali.yj20258888.top/Article/details/gtwrcowarh.html

for x in a { print(x) }
来源：http://dali.xuetiantiany.cn/Article/details/gthxhymsar.html

[T22] Swift：字典
来源：http://dali.jlsjyb.cn/Article/details/gtmewxfxxq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yuxming.cn/Article/details/gthcrgvdos.html

[T23] Swift：函数
来源：http://dali.xinyue.icu/Article/details/gtdrtdjgon.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shzxlz.cn/Article/details/gtrvqgzqyk.html

[T24] Swift：闭包
来源：http://dali.hnxiangtu.top/Article/details/gtnttyqghj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gthwmgadhg.html

[T25] Swift：结构体
来源：http://dali.sufxvd.cn/Article/details/gtnserxqvo.html

struct P { var x: Int }
来源：http://dali.zhixingplan.top/Article/details/gtaoppeenf.html

[T26] Swift：类与重写
来源：http://dali.yvedp.cn/Article/details/gtbdssflhc.html

class A: Base { override func f() {} }
来源：http://dali.nwbrower.top/Article/details/gtfwsgylbt.html

[T27] Swift：错误处理
来源：http://dali.svipenyu.cn/Article/details/gtopnmbcgw.html

do { try f() } catch { print(error) }
来源：http://dali.shangyingyoupin.top/Article/details/gtloyyadbw.html

[T28] Swift：枚举
来源：http://dali.fzhhl.top/Article/details/gtmabrsxxr.html

enum Color { case red, green }
来源：http://dali.ivvv.top/Article/details/gtozwiydfr.html

[T29] Swift：guard 提前返回
来源：http://dali.snrcjt.cn/Article/details/gtapiyvepu.html

guard let x = opt else { return }
来源：http://dali.yonumen.top/Article/details/gtyfryrivs.html

[T30] Swift：协议
来源：http://dali.shangyingyoupin.top/Article/details/gtizjkjafv.html

protocol Shape { func area() -> Double }
来源：http://dali.fengsongda.top/Article/details/gtrnlmuuai.html

[T31] Lua：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtywhakxgh.html

print("Hello")
来源：http://dali.fzhhl.top/Article/details/gtexghhglg.html

[T32] Lua：局部变量
来源：http://dali.pengpengdd.cyou/Article/details/gtufbbtgte.html

local a = 1
来源：http://dali.hnxiangtu.top/Article/details/gtapdhhczb.html

[T33] Lua：表（数组）
来源：http://dali.andypj.xyz/Article/details/gtalxwnica.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.fzhhl.top/Article/details/gtdyoeckat.html

[T34] Lua：遍历表
来源：http://dali.yuxming.cn/Article/details/gtwhlyqubl.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.gaohongyu789.top/Article/details/gtnjsbunlt.html

[T35] Lua：字典表
来源：http://dali.gogol.net.cn/Article/details/gtjrtclyng.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jlsjyb.cn/Article/details/gtmivfatcz.html

[T36] Lua：函数
来源：http://dali.zhengqikj.top/Article/details/gtzaywockm.html

function add(a, b) return a + b end
来源：http://dali.zycfv.cn/Article/details/gttxchfbuj.html

[T37] Lua：字符串拼接
来源：http://dali.fzhhl.top/Article/details/gtanunwsjz.html

"a" .. "b"
来源：http://dali.cashguo.top/Article/details/gtzppufvnx.html

[T38] Lua：条件
来源：http://dali.zhongyouzk.top/Article/details/gtkgbryujv.html

if x > 0 then print("正") end
来源：http://dali.snrcjt.cn/Article/details/gtghtpqhfy.html

[T39] Lua：模式匹配
来源：http://dali.chenjidiqi.icu/Article/details/gtnmdpskvx.html

string.find(s, "%d+")
来源：http://dali.nanxuanxn.top/Article/details/gtfigllnck.html

[T40] Lua：元表
来源：http://dali.wangdashe.top/Article/details/gtzsicblei.html

setmetatable({}, { __index = base })
来源：http://dali.zhijiandao.cn/Article/details/gtrmdgudtm.html

[T41] Perl：Hello World
来源：http://dali.jianghu66.top/Article/details/gtvwzuwogt.html

print "Hello\n";
来源：http://dali.hywenlv.cn/Article/details/gtmrgsgobx.html

[T42] Perl：变量类型
来源：http://dali.zhengqikj.top/Article/details/gteobfmnlw.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yj202588.top/Article/details/gtbjyjatgb.html

[T43] Perl：字符串插值
来源：http://dali.jinqigfzy.top/Article/details/gtehynvomt.html

"值: $a"
来源：http://dali.chenlongwang.top/Article/details/gtdxafkops.html

[T44] Perl：条件
来源：http://dali.jqgfzy.top/Article/details/gtiilrdbhj.html

if ($a > 0) { print "正"; }
来源：http://dali.yvedp.cn/Article/details/gttfbitybn.html

[T45] Perl：数组遍历
来源：http://dali.ppjwa.cn/Article/details/gtylcttmrz.html

for my $x (@arr) { print $x; }
来源：http://dali.shangyingyoupin.top/Article/details/gthimulxbp.html

[T46] Perl：哈希操作
来源：http://dali.yuxming.cn/Article/details/gtbmkanmdp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.guannengcc.top/Article/details/gtzonhzobp.html

[T47] Perl：正则捕获
来源：http://dali.cucudq.cn/Article/details/gtcytolrnn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zdqjudy.top/Article/details/gtojestfmh.html

[T48] Perl：正则替换
来源：http://dali.guannengcc.top/Article/details/gtvdxdhrpe.html

$s =~ s/old/new/g;
来源：http://dali.snrcjt.cn/Article/details/gtxokfwafx.html

[T49] Perl：函数
来源：http://dali.chenlongwang.top/Article/details/gtypiopaqo.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.xinyue.icu/Article/details/gtvghzjqrv.html

[T50] Perl：逐行读文件
来源：http://dali.jinqigfzy.top/Article/details/gtuvmzvgwi.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yvedp.cn/Article/details/gtjekutole.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.9152youxi.cn/Article/details/gthjpcdkqe.html

[T51] Scala：Hello World
来源：http://dali.redwolf501.top/Article/details/gtlttmttjg.html

println("Hello")
来源：http://dali.xuanzx.com/Article/details/gtetppgaht.html

[T52] Scala：变量
来源：http://dali.xinyue.icu/Article/details/gtsegpgmpc.html

val a = 1;  var b = 2
来源：http://dali.yanxiufei.cn/Article/details/gtoutwfuug.html

[T53] Scala：字符串插值
来源：http://dali.yuanzhike.top/Article/details/gtmoqtsmrv.html

s"值: $b"
来源：http://dali.gotoacloud.top/Article/details/gtvkukfydm.html

[T54] Scala：集合映射
来源：http://dali.jinqigfzy.top/Article/details/gtwctybkks.html


<!-- 参考信息 -->