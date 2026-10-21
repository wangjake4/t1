代发 wailian999

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.chenlongwang.top/Article/details/gttbssqupf.html

[R50] awk 求和
来源：http://dali.ydzc1.top/Article/details/gtjmuurkna.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.haohaochexian.top/Article/details/gtcwirluam.html

[R51] 排序去重取前几
来源：http://dali.smart0.xyz/Article/details/gtyyejkpvg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.wangshuangyany.cn/Article/details/gtnuqrwkty.html

[R52] 统计行数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlmwrcbin.html

wc -l a.txt
来源：http://dali.yongpay.top/Article/details/gtszcbtiqq.html

[R53] 查看文件头与实时尾
来源：http://dali.nanxinkj.top/Article/details/gtfvdpwugi.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cheryme.top/Article/details/gtigzpmgqd.html

[R54] 比较两个文件
来源：http://dali.quarkkingdee.top/Article/details/gtkokgpmui.html

diff a.txt b.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtpduqlhuv.html

[R55] 压缩与解压
来源：http://dali.zhixingplan.top/Article/details/gtwkirrfsa.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yongpay.top/Article/details/gtnwssnqvc.html

[R56] 远程拷贝
来源：http://dali.jqgfzy.top/Article/details/gtjnbqpewe.html

scp file user@host:/path/
来源：http://dali.hongshengwenyu.top/Article/details/gtntokmjfz.html

[R57] 远程执行命令
来源：http://dali.snrcjt.cn/Article/details/gtwmhsrieo.html

ssh user@host 'uptime'
来源：http://dali.sweek.top/Article/details/gtrhmgdjow.html

[R58] 下载文件
来源：http://dali.jianghu66.top/Article/details/gtuatuysro.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cqqwz.cn/Article/details/gtxprdlgkh.html

[R59] 发 POST JSON
来源：http://dali.zdqjudy.top/Article/details/gtpgmhptny.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.tianlin.xyz/Article/details/gtlusitomx.html

[R60] 只看 HTTP 状态码
来源：http://dali.cucudq.cn/Article/details/gtevpfyfwh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hnxiangtu.top/Article/details/gtotnpedam.html

[R61] 磁盘占用
来源：http://dali.gogol.net.cn/Article/details/gtrttohjmn.html

df -h;  du -sh *
来源：http://dali.yongpay.top/Article/details/gtxzpgxpba.html

[R62] 找最占空间的文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtykwtmljk.html

du -ah . | sort -rh | head -10
来源：http://dali.redwolf501.top/Article/details/gtvqrkggwf.html

[R63] 内存与进程
来源：http://dali.xinyue.icu/Article/details/gtdcbusucu.html

free -h;  ps aux | grep nginx
来源：http://dali.c1oappe.top/Article/details/gteosmmwid.html

[R64] 结束进程
来源：http://dali.hnxiangtu.top/Article/details/gthgsdwfjb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yuanzhike.top/Article/details/gthpoappqe.html

[R65] 查看端口占用
来源：http://dali.zhixingplan.top/Article/details/gtvzpwswmm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.svipenyu.cn/Article/details/gtapixovvp.html

[R66] 定时任务
来源：http://dali.aizwys.cn/Article/details/gtffqnjtau.html

crontab -e;  crontab -l
来源：http://dali.hnxiangtu.top/Article/details/gtwyobydxl.html

[R67] 生成随机十六进制串
来源：http://dali.daxiang520.top/Article/details/gtgbxrwnwo.html

openssl rand -hex 16
来源：http://dali.cheryme.top/Article/details/gtyljaovum.html

[R68] 计算文件校验值
来源：http://dali.316326.xyz/Article/details/gtnthuueqx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.meibo888.top/Article/details/gtomrudpsz.html

[R69] 生成随机密码
来源：http://dali.tianlin.xyz/Article/details/gtdwwgbjrt.html

head -c 16 /dev/urandom | base64
来源：http://dali.shanyushiyangtech.top/Article/details/gtctmowahs.html

[R70] 时间戳与互转
来源：http://dali.cqqwz.cn/Article/details/gtvbfhokgu.html

date +%s;  date -d @1700000000
来源：http://dali.nanxuanxn.top/Article/details/gtoqhdaxnb.html

[R71] 日期格式化
来源：http://dali.hfpthk.cn/Article/details/gteumtmpiz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenzaomai.com/Article/details/gtbuikajgw.html

[R72] 等待端口就绪
来源：http://dali.cashguo.top/Article/details/gthlkfnpvf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hywenlv.cn/Article/details/gtflgkbxqj.html

[R73] 分割大日志
来源：http://dali.jqgfzy.top/Article/details/gtbxqatodx.html

split -l 1000 big.log part_
来源：http://dali.xylfe.cn/Article/details/gthxjrptfl.html

[R74] 批量重命名
来源：http://dali.yuxming.cn/Article/details/gtqzkcswlk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhixingplan.top/Article/details/gtoriwvnmg.html

[R75] 导出环境变量
来源：http://dali.ppjwa.cn/Article/details/gtpsifiykt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.meibo888.top/Article/details/gtubhdlqit.html

[R76] 使用临时文件
来源：http://dali.316326.xyz/Article/details/gtzeohqnzd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yueranfly.top/Article/details/gtlzabjnyp.html

[R77] 读取用户输入
来源：http://dali.9152youxi.cn/Article/details/gtmxpzftuh.html

read -rp "请输入: " ans
来源：http://dali.cqqwz.cn/Article/details/gtrnfbbetb.html

[R78] 交互式菜单
来源：http://dali.shangyingyoupin.top/Article/details/gtgnbewuwt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhoulong.xyz/Article/details/gtukzyhdyn.html

[R79] 解析命令行选项
来源：http://dali.yuanzhike.top/Article/details/gtqkclqmzc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvwcvflmw.html

[R80] 查看脚本执行耗时
来源：http://dali.andypj.xyz/Article/details/gtnbiyyzvo.html

time ./run.sh
来源：http://dali.tanke756.top/Article/details/gtdcvvlwqq.html

================================================================================
来源：http://dali.redwolf501.top/Article/details/gtcpajxfuw.html

S. C / C++ 专题
来源：http://dali.ivvv.top/Article/details/gtijllynqf.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtorxdtikv.html

[S01] C：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtdpdtmyrk.html

#include <stdio.h>
来源：http://dali.yuxming.cn/Article/details/gtbhrykgbh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xinyue.icu/Article/details/gtsnzvpxdu.html

[S02] C：变量与格式化输出
来源：http://dali.xuanzx.com/Article/details/gtlwnotajw.html

int a = 10; printf("%d\n", a);
来源：http://dali.xziqi.cn/Article/details/gtehypsqxf.html

[S03] C：读入整数
来源：http://dali.iojbl.cn/Article/details/gtfspncxjz.html

int x; scanf("%d", &x);
来源：http://dali.jinqigufen.top/Article/details/gtulusckni.html

[S04] C：字符串复制
来源：http://dali.zhoulong.xyz/Article/details/gtcevvkzfh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ivvv.top/Article/details/gtxizykdzj.html

[S05] C：字符串长度
来源：http://dali.chenzaomai.com/Article/details/gthrkyrkut.html

strlen(s)
来源：http://dali.yueranfly.top/Article/details/gttafxhflw.html

[S06] C：字符串比较
来源：http://dali.jqgufenzy.top/Article/details/gtxazeltqg.html

strcmp(a, b) == 0
来源：http://dali.daria6918.cn/Article/details/gtnbsosgrx.html

[S07] C：数组遍历求和
来源：http://dali.jinyuanbaomall.cn/Article/details/gtitgqoiys.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cqqwz.cn/Article/details/gtxvokjcms.html

[S08] C：动态内存分配与释放
来源：http://dali.jqgfzy.top/Article/details/gtwxjsfeyr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlnrzrtxl.html

[S09] C：结构体定义与初始化
来源：http://dali.yangfankeji.com/Article/details/gtjljtnabk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ehwqpu.com/Article/details/gtgagztreh.html

[S10] C：指针与解引用
来源：http://dali.yanxiufei.cn/Article/details/gtladrfimm.html

int *p = &a;  *p = 5;
来源：http://dali.zhoulong.xyz/Article/details/gtppsiidan.html

[S11] C：逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gtyvbvlodi.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ppjwa.cn/Article/details/gtvmlnddop.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.wangshuangyany.cn/Article/details/gtmzxtxrok.html

fclose(f);
来源：http://dali.sxryk.cn/Article/details/gthdqymtxh.html

[S12] C：写文件
来源：http://dali.cqqwz.cn/Article/details/gtbaigdkin.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xuanzx.com/Article/details/gtiebblwsj.html

[S13] C：宏定义
来源：http://dali.aizwys.cn/Article/details/gtqlyltllx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.dashuyun.cn/Article/details/gtbxbzmyzh.html

[S14] C：枚举
来源：http://dali.daria6918.cn/Article/details/gtzczoscwi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yongpay.top/Article/details/gtexsawvmk.html

[S15] C：类型转换
来源：http://dali.zhongyouzk.top/Article/details/gtfizrapfn.html

(double) a / b
来源：http://dali.ydzc1.top/Article/details/gttjufadnw.html

[S16] C：位操作置位
来源：http://dali.nanxuanxn.top/Article/details/gtbttailbz.html

x |= (1 << 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtmaelugij.html

[S17] C：安全拼接字符串
来源：http://dali.vqdsnc.cn/Article/details/gtdggjlanr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yj20258888.top/Article/details/gtswwxzlvx.html

[S18] C：命令行参数
来源：http://dali.c1oappe.top/Article/details/gtoukifeul.html

int main(int argc, char **argv)
来源：http://dali.ppjwa.cn/Article/details/gtsheuuflq.html

[S19] C：快速排序
来源：http://dali.zhongyouzk.top/Article/details/gtrktpycmk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.aizwys.cn/Article/details/gtsgenaebd.html

[S20] C：二分查找
来源：http://dali.wangshuangyany.cn/Article/details/gtiqhsdpxe.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.kuanghao11.cn/Article/details/gtaezfhqar.html

[S21] C：字符类别判断
来源：http://dali.guowangkeji.top/Article/details/gttcinvhfz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.pycfn.com/Article/details/gtoxtdafmn.html

[S22] C：字符串转数字
来源：http://dali.yj20258888.top/Article/details/gtghscgqxm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhengqikj.top/Article/details/gtcnxdodeh.html

[S23] C：随机数
来源：http://dali.jiagoushi.top/Article/details/gtxeaggohv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shuidangran.top/Article/details/gtxwftxdcr.html

[S24] C：获取本地时间
来源：http://dali.kuanghao11.cn/Article/details/gtpzetlqze.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.0kj1m.cn/Article/details/gtxiwvhuix.html

[S25] C：内存拷贝
来源：http://dali.zhengqikj.top/Article/details/gtgaijoujk.html

memcpy(dst, src, n);
来源：http://dali.jinqigfzy.top/Article/details/gtbrkzwfpq.html

[S26] C：内存清零
来源：http://dali.gogol.net.cn/Article/details/gtcvxvohsf.html

memset(a, 0, sizeof a);
来源：http://dali.hfpthk.cn/Article/details/gthcssxcby.html

[S27] C：定义常量
来源：http://dali.cashguo.top/Article/details/gtunbhrzad.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gtdpvqsxoy.html

[S28] C：静态变量
来源：http://dali.cucudq.cn/Article/details/gtnebiuhjl.html

static int counter = 0;
来源：http://dali.316326.xyz/Article/details/gtiiummuam.html

[S29] C：变参函数
来源：http://dali.chenjidiqi.icu/Article/details/gtjwkbxtbq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yonumen.top/Article/details/gtnivckqis.html

[S30] C：头文件保护
来源：http://dali.gogol.net.cn/Article/details/gttyqwlisv.html

#ifndef X_H
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtduxuszaa.html

#define X_H
来源：http://dali.kuanghao11.cn/Article/details/gtkbgbklje.html

#endif
来源：http://dali.xuetiantiany.cn/Article/details/gtxdmvyhzh.html

[S31] C++：Hello World
来源：http://dali.yongpay.top/Article/details/gtpptylbjp.html

#include <iostream>
来源：http://dali.svipenyu.cn/Article/details/gtrkmljfwl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sysykeji.top/Article/details/gthmwxazme.html

[S32] C++：字符串
来源：http://dali.yonumen.top/Article/details/gtlufhfqvu.html

std::string s = "hi";  s += "!";
来源：http://dali.fengsongda.top/Article/details/gtbftxficz.html

[S33] C++：vector 增删
来源：http://dali.feifeiyinyue.top/Article/details/gtmsehzvpi.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yuanzhike.top/Article/details/gtssejesfs.html

[S34] C++：遍历 vector
来源：http://dali.daria6918.cn/Article/details/gtoghwlbrh.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.nanxinkj.top/Article/details/gtqvnhlhyk.html

[S35] C++：map
来源：http://dali.yj20258.top/Article/details/gtmvlgmfkn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuxming.cn/Article/details/gtnrczaxiv.html

[S36] C++：unordered_map
来源：http://dali.gogol.net.cn/Article/details/gtrmagizci.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gtleobevby.html

[S37] C++：set
来源：http://dali.xziqi.cn/Article/details/gtkfdpmzgm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sufxvd.cn/Article/details/gtdxzuszso.html

[S38] C++：排序
来源：http://dali.yangfankeji.com/Article/details/gttyisjdzx.html

std::sort(v.begin(), v.end());
来源：http://dali.havefunace.top/Article/details/gtvzknifxs.html

[S39] C++：自定义比较器排序
来源：http://dali.c1oappe.top/Article/details/gtvfewuzvh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhijiandao.cn/Article/details/gtoodgxrhc.html

[S40] C++：查找元素
来源：http://dali.iojbl.cn/Article/details/gtkevgujlj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zdqjudy.top/Article/details/gtaesfyewi.html

[S41] C++：类与构造函数
来源：http://dali.yangfankeji.com/Article/details/gtnqzrkhjb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yueranfly.top/Article/details/gtvwsxwaes.html

[S42] C++：继承与虚函数
来源：http://dali.havefunace.top/Article/details/gtcebqsrbi.html

class B : public Base { public: void f() override {} };
来源：http://dali.birdmap.top/Article/details/gtaqczlnow.html

[S43] C++：智能指针
来源：http://dali.nwbrower.top/Article/details/gtvrgzzzxk.html

auto p = std::make_unique<int>(5);
来源：http://dali.haohaochexian.top/Article/details/gtitnynksm.html

[S44] C++：引用传参
来源：http://dali.gotoacloud.top/Article/details/gtktfnywdi.html

void inc(int &x) { ++x; }
来源：http://dali.tanke756.top/Article/details/gtnjzbmlwr.html

[S45] C++：lambda
来源：http://dali.dashuyun.cn/Article/details/gtclfmccdn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shzxlz.cn/Article/details/gteyygxwmw.html

[S46] C++：函数模板
来源：http://dali.0kj1m.cn/Article/details/gtbnfozvkq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gogol.net.cn/Article/details/gtvzmyevzq.html

[S47] C++：结构化绑定遍历
来源：http://dali.guowangkeji.top/Article/details/gtsprccafu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yongpay.top/Article/details/gtpbmntmku.html

[S48] C++：逐行读文件
来源：http://dali.xziqi.cn/Article/details/gttfzypoug.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.birdmap.top/Article/details/gtzjyulsbf.html

while (std::getline(in, line)) { }
来源：http://dali.havefunace.top/Article/details/gtikvedhtk.html

[S49] C++：写文件
来源：http://dali.zhiwuduotai.top/Article/details/gtpwiwalpn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.fzhhl.top/Article/details/gtwvjebnsg.html

[S50] C++：格式化数字
来源：http://dali.wangshuangyany.cn/Article/details/gtzsmvuypb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.birdmap.top/Article/details/gtrzhtltmb.html

[S51] C++：显式类型转换
来源：http://dali.chenzaomai.com/Article/details/gtlvwscsem.html

static_cast<double>(a) / b
来源：http://dali.nanxinkj.top/Article/details/gtrydlugwx.html

[S52] C++：const 与 noexcept
来源：http://dali.zhengqikj.top/Article/details/gtvkpumjgj.html

int size() const noexcept { return n_; }
来源：http://dali.yonumen.top/Article/details/gtlntmxuld.html

[S53] C++：移动语义
来源：http://dali.yj202588.top/Article/details/gtlzirithj.html

std::vector<int> w = std::move(v);
来源：http://dali.hongshengwenyu.top/Article/details/gtfioesaba.html

[S54] C++：异常处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gttpmxmybf.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gtxlezorgu.html

[S55] C++：结构化绑定
来源：http://dali.jinqigfzy.top/Article/details/gttcnazlxf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gaohongyu789.top/Article/details/gtydpcdxdi.html

[S56] C++：optional
来源：http://dali.ppjwa.cn/Article/details/gttlfeshbi.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtemvhzrtm.html

[S57] C++：编译期常量
来源：http://dali.hammf.cn/Article/details/gtcblqugwe.html

constexpr int N = 10;
来源：http://dali.sufxvd.cn/Article/details/gtccfirshb.html

[S58] C++：命名空间
来源：http://dali.feifeiyinyue.top/Article/details/gtjoaicmle.html

namespace ns { int f() { return 1; } }
来源：http://dali.tanke756.top/Article/details/gtgwlnalvp.html

[S59] C++：静态断言
来源：http://dali.cqqwz.cn/Article/details/gtorrxcupw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.meibo888.top/Article/details/gtsyiyagnj.html

[S60] C++：遍历并删除元素
来源：http://dali.dashuyun.cn/Article/details/gtuhxhaouo.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.nanxinkj.top/Article/details/gtfkqoqjzi.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtglcjcwwo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tianlin.xyz/Article/details/gtcdetmpyl.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtnswdthff.html

[T01] Kotlin：Hello World
来源：http://dali.sysykeji.top/Article/details/gtoofzphai.html

println("Hello")
来源：http://dali.nanxinkj.top/Article/details/gtavobdmws.html

[T02] Kotlin：变量
来源：http://dali.ivvv.top/Article/details/gtlgwfglqa.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jyoumei.cn/Article/details/gtvuaraqdi.html

[T03] Kotlin：字符串模板
来源：http://dali.gotoacloud.top/Article/details/gtmbhbqxvq.html

"值: $b"
来源：http://dali.tian-w.cn/Article/details/gtjytlulqu.html

[T04] Kotlin：空安全
来源：http://dali.dashuyun.cn/Article/details/gtcbrkwkem.html

val n: String? = null;  n?.length
来源：http://dali.xinyue.icu/Article/details/gtjcchddzr.html

[T05] Kotlin：when 表达式
来源：http://dali.sufxvd.cn/Article/details/gtsbhritzd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.havefunace.top/Article/details/gtxnorwkzb.html

[T06] Kotlin：集合映射
来源：http://dali.aizwys.cn/Article/details/gtykdqrrev.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yangfankeji.com/Article/details/gtzwuoipng.html

[T07] Kotlin：集合过滤
来源：http://dali.zdqjudy.top/Article/details/gtldpfsvra.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.nanxinkj.top/Article/details/gtvpdkvfrn.html

[T08] Kotlin：数据类
来源：http://dali.wangshuangyany.cn/Article/details/gteyodzcom.html

data class User(val name: String, val age: Int)
来源：http://dali.9152youxi.cn/Article/details/gtjsadmszs.html

[T09] Kotlin：扩展函数
来源：http://dali.hnqzz.top/Article/details/gtjladgxot.html

fun String.exclaim() = this + "!"
来源：http://dali.hnxiangtu.top/Article/details/gttmtkncfp.html

[T10] Kotlin：默认参数
来源：http://dali.yj20258888.top/Article/details/gtncsqqkhy.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.guowangkeji.top/Article/details/gtpdgnmjap.html

[T11] Kotlin：协程
来源：http://dali.chenzaomai.com/Article/details/gtywkgbdgu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.cucudq.cn/Article/details/gtqekqyblr.html

[T12] Kotlin：解构声明
来源：http://dali.pengpengdd.cyou/Article/details/gtijuhfvyr.html

val (a, b) = Pair(1, 2)
来源：http://dali.daria6918.cn/Article/details/gtrvpzteek.html

[T13] Kotlin：只读 Map
来源：http://dali.gotoacloud.top/Article/details/gtnfbyqzpq.html

val m = mapOf("a" to 1)
来源：http://dali.kuanghao11.cn/Article/details/gtpuuljmzw.html

[T14] Kotlin：循环
来源：http://dali.meibo888.top/Article/details/gtvbgxszpv.html

for (i in 1..10) println(i)
来源：http://dali.zhengqikj.top/Article/details/gtnaexqhlk.html

[T15] Kotlin：接口
来源：http://dali.smart0.xyz/Article/details/gtmsjlpmkt.html

interface Shape { fun area(): Double }
来源：http://dali.yuxming.cn/Article/details/gtvveveifx.html

[T16] Swift：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkwlozrrm.html

print("Hello")
来源：http://dali.smart0.xyz/Article/details/gtvumfpeom.html

[T17] Swift：变量与常量
来源：http://dali.cheryme.top/Article/details/gtgxfbvmmo.html

var a = 1;  let b = 2
来源：http://dali.nwbrower.top/Article/details/gtweqwkzwx.html

[T18] Swift：字符串插值
来源：http://dali.nanxinkj.top/Article/details/gtxjjdcfan.html

"值: \(b)"
来源：http://dali.yueranfly.top/Article/details/gtxtpfriwk.html

[T19] Swift：可选绑定
来源：http://dali.birdmap.top/Article/details/gtzyzrxzzv.html

if let n = opt { print(n) }
来源：http://dali.shuidangran.top/Article/details/gtmvjgubwx.html

[T20] Swift：数组操作
来源：http://dali.shanyushiyangtech.top/Article/details/gtkznfyvtd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.dashuyun.cn/Article/details/gtrlrzobff.html

[T21] Swift：遍历
来源：http://dali.nanxinkj.top/Article/details/gtamxxichq.html

for x in a { print(x) }
来源：http://dali.yueranfly.top/Article/details/gtyxzncjqy.html

[T22] Swift：字典
来源：http://dali.xuanzx.com/Article/details/gtvvgqbjsl.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xuetiantiany.cn/Article/details/gtbjigbuxs.html

[T23] Swift：函数
来源：http://dali.dianchejie.cn/Article/details/gtpucfggky.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.nanxinkj.top/Article/details/gtcthwwrob.html

[T24] Swift：闭包
来源：http://dali.shzxlz.cn/Article/details/gtamdabjvc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jiagoushi.top/Article/details/gtnswldyxq.html

[T25] Swift：结构体
来源：http://dali.zhongyouzk.top/Article/details/gtnaujvcaj.html

struct P { var x: Int }
来源：http://dali.jlsjyb.cn/Article/details/gtjmdqxjxu.html

[T26] Swift：类与重写
来源：http://dali.yuxming.cn/Article/details/gtxivrdkno.html

class A: Base { override func f() {} }
来源：http://dali.andypj.xyz/Article/details/gtcvekczll.html

[T27] Swift：错误处理
来源：http://dali.bjfxy.top/Article/details/gtxodrpgwk.html

do { try f() } catch { print(error) }
来源：http://dali.xylfe.cn/Article/details/gtisuauyhg.html

[T28] Swift：枚举
来源：http://dali.wangshuangyany.cn/Article/details/gtrwtvfuxb.html

enum Color { case red, green }
来源：http://dali.yj20258888.top/Article/details/gttzcyjeos.html

[T29] Swift：guard 提前返回
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjjqbedv.html

guard let x = opt else { return }
来源：http://dali.hywenlv.cn/Article/details/gttqmkkhpm.html

[T30] Swift：协议
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyoypqsao.html

protocol Shape { func area() -> Double }
来源：http://dali.tianlin.xyz/Article/details/gtojgqwwsi.html

[T31] Lua：Hello World
来源：http://dali.havefunace.top/Article/details/gthubjkztl.html

print("Hello")
来源：http://dali.sxryk.cn/Article/details/gtpkvubfbi.html

[T32] Lua：局部变量
来源：http://dali.hysaishi.cn/Article/details/gthsnsiujq.html

local a = 1
来源：http://dali.zdqjudy.top/Article/details/gtylthjwxk.html

[T33] Lua：表（数组）
来源：http://dali.jinghuilouyu.cn/Article/details/gtubiycecy.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.sufxvd.cn/Article/details/gtegywcobf.html

[T34] Lua：遍历表
来源：http://dali.hysaishi.cn/Article/details/gtcmryjjjc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.aibaodan.cn/Article/details/gtnsjhqdmh.html

[T35] Lua：字典表
来源：http://dali.kuanghao11.cn/Article/details/gtwsbndxkr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yvedp.cn/Article/details/gtgnpmkarj.html

[T36] Lua：函数
来源：http://dali.pycfn.com/Article/details/gtesdjetak.html

function add(a, b) return a + b end
来源：http://dali.birdmap.top/Article/details/gtawvnbgrj.html

[T37] Lua：字符串拼接
来源：http://dali.xinyue.icu/Article/details/gtwmleumhv.html

"a" .. "b"
来源：http://dali.jinqigfzy.top/Article/details/gtctfyvhge.html

[T38] Lua：条件
来源：http://dali.sweek.top/Article/details/gtinsgacif.html

if x > 0 then print("正") end
来源：http://dali.ydzc1.top/Article/details/gttqsbczqz.html

[T39] Lua：模式匹配
来源：http://dali.meibo888.top/Article/details/gtqrfgxkxu.html

string.find(s, "%d+")
来源：http://dali.zhijiandao.cn/Article/details/gtoknhxoyt.html

[T40] Lua：元表
来源：http://dali.fzhhl.top/Article/details/gtmxojurzt.html

setmetatable({}, { __index = base })
来源：http://dali.svipenyu.cn/Article/details/gtzjefadqk.html

[T41] Perl：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtbbtaceqr.html

print "Hello\n";
来源：http://dali.yanxiufei.cn/Article/details/gtwngpkhia.html

[T42] Perl：变量类型
来源：http://dali.aibaodan.cn/Article/details/gtqjjoiojj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hywenlv.cn/Article/details/gtpaoxieop.html

[T43] Perl：字符串插值
来源：http://dali.havefunace.top/Article/details/gtmdipbvxs.html

"值: $a"
来源：http://dali.sysykeji.top/Article/details/gtintbocjq.html

[T44] Perl：条件
来源：http://dali.aibaodan.cn/Article/details/gtkpbytjgz.html

if ($a > 0) { print "正"; }
来源：http://dali.ybcxt.top/Article/details/gtsziehvqa.html

[T45] Perl：数组遍历
来源：http://dali.9152youxi.cn/Article/details/gtapvwskjc.html

for my $x (@arr) { print $x; }
来源：http://dali.yongpay.top/Article/details/gthxaisjen.html

[T46] Perl：哈希操作
来源：http://dali.feifeiyinyue.top/Article/details/gtwwycwfbr.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.gotoacloud.top/Article/details/gtefndackj.html

[T47] Perl：正则捕获
来源：http://dali.gaohongyu789.top/Article/details/gtmxxoxats.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.zhongyouzk.top/Article/details/gtgaacjtcr.html

[T48] Perl：正则替换
来源：http://dali.andypj.xyz/Article/details/gteqqpcwml.html

$s =~ s/old/new/g;
来源：http://dali.sxryk.cn/Article/details/gtqccpgdrp.html

[T49] Perl：函数
来源：http://dali.andypj.xyz/Article/details/gtwjizsmmm.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.c1oappe.top/Article/details/gtebwqpttd.html

[T50] Perl：逐行读文件
来源：http://dali.c1oappe.top/Article/details/gtiiltpzfk.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yueranfly.top/Article/details/gtgqwkecad.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.birdmap.top/Article/details/gtnlowswvz.html

[T51] Scala：Hello World
来源：http://dali.gogol.net.cn/Article/details/gtxltoguff.html

println("Hello")
来源：http://dali.shzxlz.cn/Article/details/gtgnnmvpef.html

[T52] Scala：变量
来源：http://dali.shuidangran.top/Article/details/gtfkqjtkyb.html


<!-- 参考信息 -->