代发 wailian999

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cucudq.cn/Article/details/gttsiyenni.html

[R54] 比较两个文件
来源：http://dali.jianghu66.top/Article/details/gthdwkaqtc.html

diff a.txt b.txt
来源：http://dali.svipenyu.cn/Article/details/gtdmbtkwsr.html

[R55] 压缩与解压
来源：http://dali.jinghuilouyu.cn/Article/details/gtixwskzrz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.smart0.xyz/Article/details/gtybutmfdc.html

[R56] 远程拷贝
来源：http://dali.sxryk.cn/Article/details/gtgmielcvm.html

scp file user@host:/path/
来源：http://dali.daria6918.cn/Article/details/gtitzyzuig.html

[R57] 远程执行命令
来源：http://dali.zhixingplan.top/Article/details/gtorptqoeu.html

ssh user@host 'uptime'
来源：http://dali.smart0.xyz/Article/details/gtvlwlmdnv.html

[R58] 下载文件
来源：http://dali.aibaodan.cn/Article/details/gtrttzepne.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xylfe.cn/Article/details/gtxdiomvba.html

[R59] 发 POST JSON
来源：http://dali.havefunace.top/Article/details/gtjslxqxbh.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.havefunace.top/Article/details/gtfajyfsez.html

[R60] 只看 HTTP 状态码
来源：http://dali.wangshuangyany.cn/Article/details/gthmncvkrp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yj20258888.top/Article/details/gthwlhspbn.html

[R61] 磁盘占用
来源：http://dali.dashuyun.cn/Article/details/gtghujeuzk.html

df -h;  du -sh *
来源：http://dali.yj202588.top/Article/details/gtkfouibpt.html

[R62] 找最占空间的文件
来源：http://dali.shuidangran.top/Article/details/gtilikiucx.html

du -ah . | sort -rh | head -10
来源：http://dali.ehwqpu.com/Article/details/gtsrlyfacf.html

[R63] 内存与进程
来源：http://dali.gaohongyu789.top/Article/details/gtnprmchre.html

free -h;  ps aux | grep nginx
来源：http://dali.andypj.xyz/Article/details/gtrlvglnfi.html

[R64] 结束进程
来源：http://dali.cucudq.cn/Article/details/gtbpuasnmf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jianghu66.top/Article/details/gtzgcdinzj.html

[R65] 查看端口占用
来源：http://dali.ybcxt.top/Article/details/gtdyctqrkm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yanxiufei.cn/Article/details/gtawuxbavu.html

[R66] 定时任务
来源：http://dali.xziqi.cn/Article/details/gtrofdsnza.html

crontab -e;  crontab -l
来源：http://dali.quarkkingdee.top/Article/details/gtplyuiuxa.html

[R67] 生成随机十六进制串
来源：http://dali.hammf.cn/Article/details/gtjtviukyr.html

openssl rand -hex 16
来源：http://dali.0kj1m.cn/Article/details/gtzexrjjyf.html

[R68] 计算文件校验值
来源：http://dali.ydzc1.top/Article/details/gtfcyckyhf.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhongyouzk.top/Article/details/gtkplbdkzc.html

[R69] 生成随机密码
来源：http://dali.bjfxy.top/Article/details/gtbjzojcxa.html

head -c 16 /dev/urandom | base64
来源：http://dali.yj202588.top/Article/details/gtkjrgnsyx.html

[R70] 时间戳与互转
来源：http://dali.tianlin.xyz/Article/details/gtmvhtclcr.html

date +%s;  date -d @1700000000
来源：http://dali.vqdsnc.cn/Article/details/gtewtrfnks.html

[R71] 日期格式化
来源：http://dali.guowangkeji.top/Article/details/gtzrynnwsl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.snrcjt.cn/Article/details/gtiuyhbclo.html

[R72] 等待端口就绪
来源：http://dali.fzhhl.top/Article/details/gthwlwqmgl.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xylfe.cn/Article/details/gtaqikumda.html

[R73] 分割大日志
来源：http://dali.cucudq.cn/Article/details/gtiiudeypq.html

split -l 1000 big.log part_
来源：http://dali.tanke756.top/Article/details/gtotiznunx.html

[R74] 批量重命名
来源：http://dali.kuanghao11.cn/Article/details/gtprwbzklt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.wangdashe.top/Article/details/gtglzffxjd.html

[R75] 导出环境变量
来源：http://dali.fengsongda.top/Article/details/gtaaqseepv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hnqzz.top/Article/details/gtakyhfeuv.html

[R76] 使用临时文件
来源：http://dali.wangdashe.top/Article/details/gtsftvpomb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.wangshuangyany.cn/Article/details/gtbconlbze.html

[R77] 读取用户输入
来源：http://dali.svipenyu.cn/Article/details/gtpbtupoop.html

read -rp "请输入: " ans
来源：http://dali.jinghuilouyu.cn/Article/details/gthqnoobjd.html

[R78] 交互式菜单
来源：http://dali.yj20258.top/Article/details/gtezmsibao.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsoezddsf.html

[R79] 解析命令行选项
来源：http://dali.yanxiufei.cn/Article/details/gtuibkzguu.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.havefunace.top/Article/details/gtwfoirjyt.html

[R80] 查看脚本执行耗时
来源：http://dali.smart0.xyz/Article/details/gtwveliefe.html

time ./run.sh
来源：http://dali.jinqigfzy.top/Article/details/gtrwodbery.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtvbosjzos.html

S. C / C++ 专题
来源：http://dali.vqdsnc.cn/Article/details/gtveaqvwve.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtnwhewlyl.html

[S01] C：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gtppyoyuzg.html

#include <stdio.h>
来源：http://dali.ehwqpu.com/Article/details/gthybrkfvo.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.iojbl.cn/Article/details/gtsrvbeqoe.html

[S02] C：变量与格式化输出
来源：http://dali.jianghu66.top/Article/details/gtxcztkuvq.html

int a = 10; printf("%d\n", a);
来源：http://dali.cheryme.top/Article/details/gthijvlhxq.html

[S03] C：读入整数
来源：http://dali.shzxlz.cn/Article/details/gtbkahgdlu.html

int x; scanf("%d", &x);
来源：http://dali.yueranfly.top/Article/details/gttodoauwo.html

[S04] C：字符串复制
来源：http://dali.gogol.net.cn/Article/details/gtkahhrcse.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.dianchejie.cn/Article/details/gtlahkccby.html

[S05] C：字符串长度
来源：http://dali.nanxuanxn.top/Article/details/gtczxgyryj.html

strlen(s)
来源：http://dali.vqdsnc.cn/Article/details/gttkvilsxx.html

[S06] C：字符串比较
来源：http://dali.shangyingyoupin.top/Article/details/gtymiiqpnq.html

strcmp(a, b) == 0
来源：http://dali.pycfn.com/Article/details/gtjhoioyar.html

[S07] C：数组遍历求和
来源：http://dali.yonumen.top/Article/details/gtkpvxmtev.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ybcxt.top/Article/details/gtohtzwflf.html

[S08] C：动态内存分配与释放
来源：http://dali.jiagoushi.top/Article/details/gtdrbwnsnt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.snrcjt.cn/Article/details/gtjwdayhpr.html

[S09] C：结构体定义与初始化
来源：http://dali.0kj1m.cn/Article/details/gthwotahnu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.vqdsnc.cn/Article/details/gtuyznhdwg.html

[S10] C：指针与解引用
来源：http://dali.haohaochexian.top/Article/details/gtgtjzmtmt.html

int *p = &a;  *p = 5;
来源：http://dali.yongpay.top/Article/details/gthswjzjpa.html

[S11] C：逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gtrovxvvnt.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdqwpdonb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.316326.xyz/Article/details/gtbmjyxqkk.html

fclose(f);
来源：http://dali.jqgufenzy.top/Article/details/gtwecsybvj.html

[S12] C：写文件
来源：http://dali.hywenlv.cn/Article/details/gtebctblfl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.mhx1999.top/Article/details/gtzujfjigf.html

[S13] C：宏定义
来源：http://dali.quarkkingdee.top/Article/details/gtxnqcdljb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.dianchejie.cn/Article/details/gtfjktkjww.html

[S14] C：枚举
来源：http://dali.nanxinkj.top/Article/details/gtktfnvkoi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.mhx1999.top/Article/details/gtkfehdcpv.html

[S15] C：类型转换
来源：http://dali.ybcxt.top/Article/details/gtrujodgwf.html

(double) a / b
来源：http://dali.hongshengwenyu.top/Article/details/gtwnacolrv.html

[S16] C：位操作置位
来源：http://dali.meibo888.top/Article/details/gtcwlcsfbd.html

x |= (1 << 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtjzoudunz.html

[S17] C：安全拼接字符串
来源：http://dali.9152youxi.cn/Article/details/gtkznplozg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.snrcjt.cn/Article/details/gtakemqrns.html

[S18] C：命令行参数
来源：http://dali.9152youxi.cn/Article/details/gthgdowmnj.html

int main(int argc, char **argv)
来源：http://dali.yuanzhike.top/Article/details/gtnjgvvxti.html

[S19] C：快速排序
来源：http://dali.nanxuanxn.top/Article/details/gtoirsytjd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gtjpekazxv.html

[S20] C：二分查找
来源：http://dali.bjfxy.top/Article/details/gttszaxuca.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhixingplan.top/Article/details/gteczflfls.html

[S21] C：字符类别判断
来源：http://dali.gogol.net.cn/Article/details/gtuthjjixv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cqqwz.cn/Article/details/gtsfqomtgv.html

[S22] C：字符串转数字
来源：http://dali.yuanzhike.top/Article/details/gtvrsiuwrt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hywenlv.cn/Article/details/gtldzyuzjx.html

[S23] C：随机数
来源：http://dali.xylfe.cn/Article/details/gtvlouwmmf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhiwuduotai.top/Article/details/gtwthnmjfj.html

[S24] C：获取本地时间
来源：http://dali.hfpthk.cn/Article/details/gttrqajhvr.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ybcxt.top/Article/details/gtvfnzzdvh.html

[S25] C：内存拷贝
来源：http://dali.havefunace.top/Article/details/gtgdufpjlt.html

memcpy(dst, src, n);
来源：http://dali.9152youxi.cn/Article/details/gtfbedcxhp.html

[S26] C：内存清零
来源：http://dali.dianchejie.cn/Article/details/gtsmvfrxox.html

memset(a, 0, sizeof a);
来源：http://dali.ppjwa.cn/Article/details/gtqfjalhwd.html

[S27] C：定义常量
来源：http://dali.yanxiufei.cn/Article/details/gtfwhvrgxp.html

const double PI = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gtjuekzvqr.html

[S28] C：静态变量
来源：http://dali.pycfn.com/Article/details/gtypmfbsrn.html

static int counter = 0;
来源：http://dali.daria6918.cn/Article/details/gtlxmmklqc.html

[S29] C：变参函数
来源：http://dali.feifeiyinyue.top/Article/details/gttctsriot.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.svipenyu.cn/Article/details/gtjedoizsu.html

[S30] C：头文件保护
来源：http://dali.sufxvd.cn/Article/details/gtignmbytj.html

#ifndef X_H
来源：http://dali.shzxlz.cn/Article/details/gtsywugnna.html

#define X_H
来源：http://dali.cucudq.cn/Article/details/gtbofwretb.html

#endif
来源：http://dali.smart0.xyz/Article/details/gteaegmxwl.html

[S31] C++：Hello World
来源：http://dali.sxryk.cn/Article/details/gtxrfzwhgx.html

#include <iostream>
来源：http://dali.jinqigufen.top/Article/details/gtkcavicjg.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hfpthk.cn/Article/details/gtlodvrjka.html

[S32] C++：字符串
来源：http://dali.jianghu66.top/Article/details/gttrnabiyh.html

std::string s = "hi";  s += "!";
来源：http://dali.jiagoushi.top/Article/details/gtravzmibz.html

[S33] C++：vector 增删
来源：http://dali.ppjwa.cn/Article/details/gtcsjouswl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zdqjudy.top/Article/details/gtutfesmqj.html

[S34] C++：遍历 vector
来源：http://dali.tanke756.top/Article/details/gtklzxohzk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yongpay.top/Article/details/gtgmtphyrb.html

[S35] C++：map
来源：http://dali.redwolf501.top/Article/details/gtpiliqhxu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xziqi.cn/Article/details/gtaqvhuhzd.html

[S36] C++：unordered_map
来源：http://dali.hysaishi.cn/Article/details/gtqfhbhycd.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cashguo.top/Article/details/gtidhcpbft.html

[S37] C++：set
来源：http://dali.yuxming.cn/Article/details/gtflharfzy.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.9152youxi.cn/Article/details/gtkepjaqem.html

[S38] C++：排序
来源：http://dali.jinqigufen.top/Article/details/gtizuyxrhc.html

std::sort(v.begin(), v.end());
来源：http://dali.jqgufenzy.top/Article/details/gtvvxyhnbh.html

[S39] C++：自定义比较器排序
来源：http://dali.vqdsnc.cn/Article/details/gtkbiybyye.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj20258888.top/Article/details/gtvywkragz.html

[S40] C++：查找元素
来源：http://dali.tianlin.xyz/Article/details/gtnfoiosxr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ydzc1.top/Article/details/gtjuzcqqfh.html

[S41] C++：类与构造函数
来源：http://dali.zhengqikj.top/Article/details/gtokipaifj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.aizwys.cn/Article/details/gtrhqyoopq.html

[S42] C++：继承与虚函数
来源：http://dali.tanke756.top/Article/details/gtbnljykzf.html

class B : public Base { public: void f() override {} };
来源：http://dali.xuanzx.com/Article/details/gtxqjnwvbw.html

[S43] C++：智能指针
来源：http://dali.shuidangran.top/Article/details/gthtyhqatd.html

auto p = std::make_unique<int>(5);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrwfudrdi.html

[S44] C++：引用传参
来源：http://dali.hongshengwenyu.top/Article/details/gtmzcgwsls.html

void inc(int &x) { ++x; }
来源：http://dali.hnqzz.top/Article/details/gtgptjbioa.html

[S45] C++：lambda
来源：http://dali.meibo888.top/Article/details/gtcakbabwi.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.daxiang520.top/Article/details/gtcnfhqksg.html

[S46] C++：函数模板
来源：http://dali.jinqigfzy.top/Article/details/gtdrdrbcwd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shuidangran.top/Article/details/gtziizkbbp.html

[S47] C++：结构化绑定遍历
来源：http://dali.yj20258.top/Article/details/gtqjulsxyi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xuanzx.com/Article/details/gtmnmgjhnk.html

[S48] C++：逐行读文件
来源：http://dali.shuidangran.top/Article/details/gtdooukpdq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xziqi.cn/Article/details/gtodxzolgf.html

while (std::getline(in, line)) { }
来源：http://dali.jyoumei.cn/Article/details/gtkexdpsya.html

[S49] C++：写文件
来源：http://dali.pycfn.com/Article/details/gtjcvgcxlw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yj20258.top/Article/details/gtwojjujtk.html

[S50] C++：格式化数字
来源：http://dali.316326.xyz/Article/details/gtbugzfgki.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yj20258.top/Article/details/gtduainwji.html

[S51] C++：显式类型转换
来源：http://dali.bjfxy.top/Article/details/gtqnscreyp.html

static_cast<double>(a) / b
来源：http://dali.jinqigfzy.top/Article/details/gtvvrccdju.html

[S52] C++：const 与 noexcept
来源：http://dali.jinghuilouyu.cn/Article/details/gttsfcongt.html

int size() const noexcept { return n_; }
来源：http://dali.zhoulong.xyz/Article/details/gtuqijphen.html

[S53] C++：移动语义
来源：http://dali.guannengcc.top/Article/details/gtjxhmpohl.html

std::vector<int> w = std::move(v);
来源：http://dali.snrcjt.cn/Article/details/gtmcelkftk.html

[S54] C++：异常处理
来源：http://dali.zhixingplan.top/Article/details/gtswzcxwpy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.svipenyu.cn/Article/details/gttbaxfdvx.html

[S55] C++：结构化绑定
来源：http://dali.guowangkeji.top/Article/details/gteamxfjlg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.dashuyun.cn/Article/details/gtckuatsnb.html

[S56] C++：optional
来源：http://dali.gzhubu.top/Article/details/gtdcwhdorf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yueranfly.top/Article/details/gtvqaoxvil.html

[S57] C++：编译期常量
来源：http://dali.hnxiangtu.top/Article/details/gtdritdfhs.html

constexpr int N = 10;
来源：http://dali.gogol.net.cn/Article/details/gtiluwmqeu.html

[S58] C++：命名空间
来源：http://dali.zhongyouzk.top/Article/details/gttgneobsi.html

namespace ns { int f() { return 1; } }
来源：http://dali.yangfankeji.com/Article/details/gtylwariyf.html

[S59] C++：静态断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaoghfnzo.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.wangshuangyany.cn/Article/details/gtdosxbabi.html

[S60] C++：遍历并删除元素
来源：http://dali.mhx1999.top/Article/details/gtnefcwfgo.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shzxlz.cn/Article/details/gtnjqxoodj.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtiqyuyivg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cqqwz.cn/Article/details/gtptjsturf.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtbywxrijt.html

[T01] Kotlin：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtkhorrafh.html

println("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gtfszobqqp.html

[T02] Kotlin：变量
来源：http://dali.dianchejie.cn/Article/details/gtjufljtsb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.0kj1m.cn/Article/details/gtsenjaebh.html

[T03] Kotlin：字符串模板
来源：http://dali.tanke756.top/Article/details/gtrrhqmiuw.html

"值: $b"
来源：http://dali.yuanzhike.top/Article/details/gtrvpxmnbz.html

[T04] Kotlin：空安全
来源：http://dali.yuanzhike.top/Article/details/gtuqnylnti.html

val n: String? = null;  n?.length
来源：http://dali.9152youxi.cn/Article/details/gtbqewdypm.html

[T05] Kotlin：when 表达式
来源：http://dali.yongpay.top/Article/details/gtsotayzjx.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.nanxuanxn.top/Article/details/gtywmasdgx.html

[T06] Kotlin：集合映射
来源：http://dali.ivvv.top/Article/details/gtlbvedszz.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gtptxrwiyw.html

[T07] Kotlin：集合过滤
来源：http://dali.cdnleiting.top/Article/details/gtxffrjyzh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.tianlin.xyz/Article/details/gtukzslsbw.html

[T08] Kotlin：数据类
来源：http://dali.zhongyouzk.top/Article/details/gtobfihybd.html

data class User(val name: String, val age: Int)
来源：http://dali.316326.xyz/Article/details/gtrhbayxgi.html

[T09] Kotlin：扩展函数
来源：http://dali.xziqi.cn/Article/details/gtdomdyvum.html

fun String.exclaim() = this + "!"
来源：http://dali.cheryme.top/Article/details/gtetkoufkr.html

[T10] Kotlin：默认参数
来源：http://dali.aizwys.cn/Article/details/gtyossokxu.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.aibaodan.cn/Article/details/gthaygauxb.html

[T11] Kotlin：协程
来源：http://dali.yvedp.cn/Article/details/gtleqwwtnc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ehwqpu.com/Article/details/gtyowyhign.html

[T12] Kotlin：解构声明
来源：http://dali.yuanzhike.top/Article/details/gtiyvwqmbk.html

val (a, b) = Pair(1, 2)
来源：http://dali.guowangkeji.top/Article/details/gtdoljzlob.html

[T13] Kotlin：只读 Map
来源：http://dali.mhx1999.top/Article/details/gtoheizdda.html

val m = mapOf("a" to 1)
来源：http://dali.vqdsnc.cn/Article/details/gtjrowztiu.html

[T14] Kotlin：循环
来源：http://dali.feifeiyinyue.top/Article/details/gtdmytrwsz.html

for (i in 1..10) println(i)
来源：http://dali.yanxiufei.cn/Article/details/gtaeimobxt.html

[T15] Kotlin：接口
来源：http://dali.chenzaomai.com/Article/details/gtshxmspmr.html

interface Shape { fun area(): Double }
来源：http://dali.gaohongyu789.top/Article/details/gtigzxfbmb.html

[T16] Swift：Hello World
来源：http://dali.cashguo.top/Article/details/gtoagzxmpr.html

print("Hello")
来源：http://dali.xziqi.cn/Article/details/gtuqnwnxzt.html

[T17] Swift：变量与常量
来源：http://dali.c1oappe.top/Article/details/gtctnqzsdp.html

var a = 1;  let b = 2
来源：http://dali.gzhubu.top/Article/details/gthoqugkek.html

[T18] Swift：字符串插值
来源：http://dali.zhixingplan.top/Article/details/gtsxtxypum.html

"值: \(b)"
来源：http://dali.xziqi.cn/Article/details/gtbvivcirb.html

[T19] Swift：可选绑定
来源：http://dali.jqgfzy.top/Article/details/gtzxrnjzgu.html

if let n = opt { print(n) }
来源：http://dali.ppjwa.cn/Article/details/gtzdonnnqt.html

[T20] Swift：数组操作
来源：http://dali.ivvv.top/Article/details/gtemhsagvy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yuanzhike.top/Article/details/gtlspscguq.html

[T21] Swift：遍历
来源：http://dali.hfpthk.cn/Article/details/gtiyrzyhay.html

for x in a { print(x) }
来源：http://dali.xziqi.cn/Article/details/gtsuqveeno.html

[T22] Swift：字典
来源：http://dali.zdqjudy.top/Article/details/gtcvhmuiex.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.nanxuanxn.top/Article/details/gthebrzsca.html

[T23] Swift：函数
来源：http://dali.ivvv.top/Article/details/gthyimmyxc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.gogol.net.cn/Article/details/gtpdmyotdv.html

[T24] Swift：闭包
来源：http://dali.jlsjyb.cn/Article/details/gtxldpxzfe.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hnxiangtu.top/Article/details/gtgwaflhwc.html

[T25] Swift：结构体
来源：http://dali.aibaodan.cn/Article/details/gtmkytlcbd.html

struct P { var x: Int }
来源：http://dali.guowangkeji.top/Article/details/gtkqipanvt.html

[T26] Swift：类与重写
来源：http://dali.yuanzhike.top/Article/details/gthsqbzzhi.html

class A: Base { override func f() {} }
来源：http://dali.kuanghao11.cn/Article/details/gtayndkhax.html

[T27] Swift：错误处理
来源：http://dali.tanke756.top/Article/details/gturdljrhd.html

do { try f() } catch { print(error) }
来源：http://dali.ppjwa.cn/Article/details/gtzlvqysjj.html

[T28] Swift：枚举
来源：http://dali.chenjidiqi.icu/Article/details/gtuikvhyec.html

enum Color { case red, green }
来源：http://dali.ybcxt.top/Article/details/gtmdgvbnsj.html

[T29] Swift：guard 提前返回
来源：http://dali.ydzc1.top/Article/details/gtyotkgbxa.html

guard let x = opt else { return }
来源：http://dali.yvedp.cn/Article/details/gtetevuovw.html

[T30] Swift：协议
来源：http://dali.chenjidiqi.icu/Article/details/gtdeklquso.html

protocol Shape { func area() -> Double }
来源：http://dali.ydzc1.top/Article/details/gtczimgpao.html

[T31] Lua：Hello World
来源：http://dali.shuidangran.top/Article/details/gtzmbazflg.html

print("Hello")
来源：http://dali.chenjidiqi.icu/Article/details/gtdxwtokaj.html

[T32] Lua：局部变量
来源：http://dali.haohaochexian.top/Article/details/gtqzjgjbrq.html

local a = 1
来源：http://dali.nanxinkj.top/Article/details/gtnuvylyow.html

[T33] Lua：表（数组）
来源：http://dali.xziqi.cn/Article/details/gtiottvdyn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jiagoushi.top/Article/details/gtykvsddbq.html

[T34] Lua：遍历表
来源：http://dali.dianchejie.cn/Article/details/gtddfeicfd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.xziqi.cn/Article/details/gtvtifaeuc.html

[T35] Lua：字典表
来源：http://dali.mhx1999.top/Article/details/gtjzgxkykp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.daria6918.cn/Article/details/gtpahokzfl.html

[T36] Lua：函数
来源：http://dali.quarkkingdee.top/Article/details/gtrzkoikaq.html

function add(a, b) return a + b end
来源：http://dali.yj20258888.top/Article/details/gttwyeibkm.html

[T37] Lua：字符串拼接
来源：http://dali.zhengqikj.top/Article/details/gtexdozxtn.html

"a" .. "b"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtescyeaek.html

[T38] Lua：条件
来源：http://dali.dianchejie.cn/Article/details/gtppkfenrk.html

if x > 0 then print("正") end
来源：http://dali.9152youxi.cn/Article/details/gtapzdnnsk.html

[T39] Lua：模式匹配
来源：http://dali.jiagoushi.top/Article/details/gtztvcvpum.html

string.find(s, "%d+")
来源：http://dali.hnxiangtu.top/Article/details/gtncnarfxq.html

[T40] Lua：元表
来源：http://dali.gaohongyu789.top/Article/details/gtendcxmtt.html

setmetatable({}, { __index = base })
来源：http://dali.guannengcc.top/Article/details/gtybzeaxxr.html

[T41] Perl：Hello World
来源：http://dali.yueranfly.top/Article/details/gttbzlsnjt.html

print "Hello\n";
来源：http://dali.zycfv.cn/Article/details/gtblvzarfd.html

[T42] Perl：变量类型
来源：http://dali.tian-w.cn/Article/details/gtmbbnruir.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.haohaochexian.top/Article/details/gtvmrunsbz.html

[T43] Perl：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gtpubawqaa.html

"值: $a"
来源：http://dali.gotoacloud.top/Article/details/gtyyzefohp.html

[T44] Perl：条件
来源：http://dali.zycfv.cn/Article/details/gtcrgsswjc.html

if ($a > 0) { print "正"; }
来源：http://dali.gotoacloud.top/Article/details/gtmvyyftmp.html

[T45] Perl：数组遍历
来源：http://dali.jinqigufen.top/Article/details/gtljtmcaak.html

for my $x (@arr) { print $x; }
来源：http://dali.xuanzx.com/Article/details/gtzexrjsrs.html

[T46] Perl：哈希操作
来源：http://dali.yj20258.top/Article/details/gtborkwrvf.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.havefunace.top/Article/details/gtxvvwxtlk.html

[T47] Perl：正则捕获
来源：http://dali.yanxiufei.cn/Article/details/gtiyqorypd.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.cashguo.top/Article/details/gtwonhhxch.html

[T48] Perl：正则替换
来源：http://dali.sweek.top/Article/details/gtpxgixacq.html

$s =~ s/old/new/g;
来源：http://dali.zhijiandao.cn/Article/details/gtaaxtyjev.html

[T49] Perl：函数
来源：http://dali.quarkkingdee.top/Article/details/gtcskjjbep.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.316326.xyz/Article/details/gtqpzgbkeg.html

[T50] Perl：逐行读文件
来源：http://dali.snrcjt.cn/Article/details/gtgabdddik.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvycflfga.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.tianlin.xyz/Article/details/gtbqvcfavn.html

[T51] Scala：Hello World
来源：http://dali.fengsongda.top/Article/details/gtoartnbvs.html

println("Hello")
来源：http://dali.havefunace.top/Article/details/gtiqwomwdj.html

[T52] Scala：变量
来源：http://dali.bjfxy.top/Article/details/gtcobtcxmy.html

val a = 1;  var b = 2
来源：http://dali.0kj1m.cn/Article/details/gtgyfvjrpw.html

[T53] Scala：字符串插值
来源：http://dali.jinqigfzy.top/Article/details/gtkjpiuaaj.html

s"值: $b"
来源：http://dali.yonumen.top/Article/details/gtnwckjynm.html

[T54] Scala：集合映射
来源：http://dali.wangdashe.top/Article/details/gtkvnxhzub.html

List(1, 2, 3).map(_ * 2)
来源：http://dali.redwolf501.top/Article/details/gtwibdozuu.html

[T55] Scala：集合过滤
来源：http://dali.zhixingplan.top/Article/details/gtekpaqvso.html

List(1, 2, 3).filter(_ > 1)
来源：http://dali.chenzaomai.com/Article/details/gtknunfqvw.html

[T56] Scala：样例类
来源：http://dali.yj20258.top/Article/details/gtikxisvwi.html


<!-- 参考信息 -->