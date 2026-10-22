代发 wailian999

find . -name "*.tmp" -delete
来源：http://dali.c1oappe.top/Article/details/gtgkvnsqax.html

[R46] 递归替换文件内容
来源：http://dali.shanyushiyangtech.top/Article/details/gtuznomtbb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sweek.top/Article/details/gtxumuesnf.html

[R47] sed 单行替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtezibmjtr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtifnjffqr.html

[R48] awk 取指定列
来源：http://dali.9152youxi.cn/Article/details/gtogccmrhg.html

awk '{print $1, $3}' a.txt
来源：http://dali.guowangkeji.top/Article/details/gtwcggnilz.html

[R49] awk 带条件
来源：http://dali.0kj1m.cn/Article/details/gtshwjxuwg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhiwuduotai.top/Article/details/gtxeopsaey.html

[R50] awk 求和
来源：http://dali.hnxiangtu.top/Article/details/gtyoxufnkt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.redwolf501.top/Article/details/gtlpucowvs.html

[R51] 排序去重取前几
来源：http://dali.yvedp.cn/Article/details/gtbkrrmzhi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.wangshuangyany.cn/Article/details/gtbirplkem.html

[R52] 统计行数
来源：http://dali.yongpay.top/Article/details/gtgpfvetfg.html

wc -l a.txt
来源：http://dali.havefunace.top/Article/details/gtjiihnccs.html

[R53] 查看文件头与实时尾
来源：http://dali.yj20258.top/Article/details/gtdbsiaxqs.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xuanzx.com/Article/details/gtxdtkulxb.html

[R54] 比较两个文件
来源：http://dali.zhixingplan.top/Article/details/gtnzwxpxfb.html

diff a.txt b.txt
来源：http://dali.iojbl.cn/Article/details/gtvttsueem.html

[R55] 压缩与解压
来源：http://dali.vqdsnc.cn/Article/details/gtdeutecxn.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xziqi.cn/Article/details/gtbgtzjhqq.html

[R56] 远程拷贝
来源：http://dali.hammf.cn/Article/details/gtrvzcofkf.html

scp file user@host:/path/
来源：http://dali.hnqzz.top/Article/details/gtcgrnqbmi.html

[R57] 远程执行命令
来源：http://dali.sufxvd.cn/Article/details/gtculjbgcp.html

ssh user@host 'uptime'
来源：http://dali.mhx1999.top/Article/details/gtoaqopncq.html

[R58] 下载文件
来源：http://dali.chenjidiqi.icu/Article/details/gtdpnqwthx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cashguo.top/Article/details/gtfdhrvlxh.html

[R59] 发 POST JSON
来源：http://dali.jqgufenzy.top/Article/details/gtnrxjmpss.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhoulong.xyz/Article/details/gtxhcjebwe.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhongyouzk.top/Article/details/gtoazeizfu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shanyushiyangtech.top/Article/details/gtihpmfcbm.html

[R61] 磁盘占用
来源：http://dali.gogol.net.cn/Article/details/gtqoibpuuf.html

df -h;  du -sh *
来源：http://dali.yuxming.cn/Article/details/gtowjgaetn.html

[R62] 找最占空间的文件
来源：http://dali.snrcjt.cn/Article/details/gtzomrnezn.html

du -ah . | sort -rh | head -10
来源：http://dali.gotoacloud.top/Article/details/gtuyaugbuw.html

[R63] 内存与进程
来源：http://dali.9152youxi.cn/Article/details/gtveynutgo.html

free -h;  ps aux | grep nginx
来源：http://dali.havefunace.top/Article/details/gtehyyktkh.html

[R64] 结束进程
来源：http://dali.zhixingplan.top/Article/details/gtybppnrjp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.fzhhl.top/Article/details/gtrwwydtlb.html

[R65] 查看端口占用
来源：http://dali.sufxvd.cn/Article/details/gtkapgmtkv.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yangfankeji.com/Article/details/gtnjceqocl.html

[R66] 定时任务
来源：http://dali.gotoacloud.top/Article/details/gtlrwnknnx.html

crontab -e;  crontab -l
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdsudsjnu.html

[R67] 生成随机十六进制串
来源：http://dali.jlsjyb.cn/Article/details/gtlvjsdmtc.html

openssl rand -hex 16
来源：http://dali.shuidangran.top/Article/details/gtnzctthed.html

[R68] 计算文件校验值
来源：http://dali.xinyue.icu/Article/details/gthmcanxqg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ehwqpu.com/Article/details/gtawkkpiri.html

[R69] 生成随机密码
来源：http://dali.mhx1999.top/Article/details/gtiwghytli.html

head -c 16 /dev/urandom | base64
来源：http://dali.chenlongwang.top/Article/details/gtnbjcgcog.html

[R70] 时间戳与互转
来源：http://dali.andypj.xyz/Article/details/gtamztpxow.html

date +%s;  date -d @1700000000
来源：http://dali.cucudq.cn/Article/details/gtxjvlxazp.html

[R71] 日期格式化
来源：http://dali.sysykeji.top/Article/details/gtzxyjoeao.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shangyingyoupin.top/Article/details/gtsoiiucsv.html

[R72] 等待端口就绪
来源：http://dali.gaohongyu789.top/Article/details/gtpzdcddsa.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yvedp.cn/Article/details/gtefezxlhi.html

[R73] 分割大日志
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgbeskxbo.html

split -l 1000 big.log part_
来源：http://dali.aizwys.cn/Article/details/gtzkodqkdp.html

[R74] 批量重命名
来源：http://dali.snrcjt.cn/Article/details/gtpdetvdcf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yuanzhike.top/Article/details/gtebcacacg.html

[R75] 导出环境变量
来源：http://dali.sxryk.cn/Article/details/gttsmpbbyg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.vqdsnc.cn/Article/details/gtjwaxppca.html

[R76] 使用临时文件
来源：http://dali.guowangkeji.top/Article/details/gtotlguppl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhongyouzk.top/Article/details/gtvgngsohg.html

[R77] 读取用户输入
来源：http://dali.haohaochexian.top/Article/details/gtiobytchz.html

read -rp "请输入: " ans
来源：http://dali.yj20258888.top/Article/details/gtzdlvqzie.html

[R78] 交互式菜单
来源：http://dali.sufxvd.cn/Article/details/gtxvzcjxve.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ppjwa.cn/Article/details/gtlubyharu.html

[R79] 解析命令行选项
来源：http://dali.redwolf501.top/Article/details/gtzuqbjejd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinqigufen.top/Article/details/gtdfrwrhns.html

[R80] 查看脚本执行耗时
来源：http://dali.yongpay.top/Article/details/gtavdpobzf.html

time ./run.sh
来源：http://dali.daxiang520.top/Article/details/gtiqxaeevz.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtkvbscadb.html

S. C / C++ 专题
来源：http://dali.sufxvd.cn/Article/details/gtggvlofdn.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtdtbvsova.html

[S01] C：Hello World
来源：http://dali.fengsongda.top/Article/details/gtbgsfymhh.html

#include <stdio.h>
来源：http://dali.fzhhl.top/Article/details/gtmiivjzfe.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.chenlongwang.top/Article/details/gtmhaghjsg.html

[S02] C：变量与格式化输出
来源：http://dali.chenlongwang.top/Article/details/gtulrpblen.html

int a = 10; printf("%d\n", a);
来源：http://dali.yonumen.top/Article/details/gtxmpovput.html

[S03] C：读入整数
来源：http://dali.hysaishi.cn/Article/details/gtzbnwshrs.html

int x; scanf("%d", &x);
来源：http://dali.hongshengwenyu.top/Article/details/gtjmpfpnak.html

[S04] C：字符串复制
来源：http://dali.jlsjyb.cn/Article/details/gtieypvfme.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.cashguo.top/Article/details/gtgfuxywwt.html

[S05] C：字符串长度
来源：http://dali.xinyue.icu/Article/details/gtkxwpfxfi.html

strlen(s)
来源：http://dali.yj202588.top/Article/details/gtxufcxdfc.html

[S06] C：字符串比较
来源：http://dali.nanxinkj.top/Article/details/gtssqywrak.html

strcmp(a, b) == 0
来源：http://dali.jinghuilouyu.cn/Article/details/gtajqarfsj.html

[S07] C：数组遍历求和
来源：http://dali.yonumen.top/Article/details/gtracmkdmt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yonumen.top/Article/details/gthkvgbkdk.html

[S08] C：动态内存分配与释放
来源：http://dali.smart0.xyz/Article/details/gtqmjtuwpx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yj202588.top/Article/details/gtybzglypk.html

[S09] C：结构体定义与初始化
来源：http://dali.birdmap.top/Article/details/gtppobqzic.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.iojbl.cn/Article/details/gtktynghxe.html

[S10] C：指针与解引用
来源：http://dali.sweek.top/Article/details/gtuxhuozjo.html

int *p = &a;  *p = 5;
来源：http://dali.cucudq.cn/Article/details/gttnxbvsyh.html

[S11] C：逐行读文件
来源：http://dali.pengpengdd.cyou/Article/details/gtqdbnmqps.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.guowangkeji.top/Article/details/gtijjgrlyr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yj202588.top/Article/details/gtdilicwib.html

fclose(f);
来源：http://dali.jianghu66.top/Article/details/gtatbsusct.html

[S12] C：写文件
来源：http://dali.hnqzz.top/Article/details/gtliqwweej.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinqigufen.top/Article/details/gtayrqqpmu.html

[S13] C：宏定义
来源：http://dali.svipenyu.cn/Article/details/gtusrditon.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shangyingyoupin.top/Article/details/gtdttretaj.html

[S14] C：枚举
来源：http://dali.guowangkeji.top/Article/details/gtibrscilu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hnxiangtu.top/Article/details/gtturxyzny.html

[S15] C：类型转换
来源：http://dali.sysykeji.top/Article/details/gtcfabhypc.html

(double) a / b
来源：http://dali.shangyingyoupin.top/Article/details/gtnpdanome.html

[S16] C：位操作置位
来源：http://dali.yongpay.top/Article/details/gtdeytkyxm.html

x |= (1 << 3);
来源：http://dali.yj20258.top/Article/details/gtwttsfzml.html

[S17] C：安全拼接字符串
来源：http://dali.sysykeji.top/Article/details/gttitsasle.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shzxlz.cn/Article/details/gtdxhrwpfv.html

[S18] C：命令行参数
来源：http://dali.dashuyun.cn/Article/details/gtkvyuugpw.html

int main(int argc, char **argv)
来源：http://dali.cheryme.top/Article/details/gtocltohqd.html

[S19] C：快速排序
来源：http://dali.sufxvd.cn/Article/details/gtvjnasfjq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yueranfly.top/Article/details/gtgzhtllpr.html

[S20] C：二分查找
来源：http://dali.daria6918.cn/Article/details/gtxwjlenbo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gttcayiais.html

[S21] C：字符类别判断
来源：http://dali.hnqzz.top/Article/details/gtchrazbek.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hongshengwenyu.top/Article/details/gtocaapanr.html

[S22] C：字符串转数字
来源：http://dali.aibaodan.cn/Article/details/gtfnjuyitu.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.svipenyu.cn/Article/details/gteuedkmhq.html

[S23] C：随机数
来源：http://dali.yonumen.top/Article/details/gttchjdfyz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gaohongyu789.top/Article/details/gttthmjhog.html

[S24] C：获取本地时间
来源：http://dali.nanxinkj.top/Article/details/gtwqyyntrh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.vqdsnc.cn/Article/details/gtnfixekfn.html

[S25] C：内存拷贝
来源：http://dali.hysaishi.cn/Article/details/gtvdnovtqo.html

memcpy(dst, src, n);
来源：http://dali.guowangkeji.top/Article/details/gthdogtciz.html

[S26] C：内存清零
来源：http://dali.aizwys.cn/Article/details/gtrfdbmmxy.html

memset(a, 0, sizeof a);
来源：http://dali.svipenyu.cn/Article/details/gtxwubkunc.html

[S27] C：定义常量
来源：http://dali.svipenyu.cn/Article/details/gtcyprzbpe.html

const double PI = 3.14159;
来源：http://dali.daria6918.cn/Article/details/gtobtkxfbo.html

[S28] C：静态变量
来源：http://dali.yuanzhike.top/Article/details/gtmhljxbcg.html

static int counter = 0;
来源：http://dali.yueranfly.top/Article/details/gtimfunweh.html

[S29] C：变参函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzbzysetd.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.mhx1999.top/Article/details/gtskldlzvs.html

[S30] C：头文件保护
来源：http://dali.tanke756.top/Article/details/gtaekqvnrx.html

#ifndef X_H
来源：http://dali.0kj1m.cn/Article/details/gtaenmpury.html

#define X_H
来源：http://dali.snrcjt.cn/Article/details/gtqcnockbd.html

#endif
来源：http://dali.quarkkingdee.top/Article/details/gtuurbrmlv.html

[S31] C++：Hello World
来源：http://dali.pycfn.com/Article/details/gtyrytbhot.html

#include <iostream>
来源：http://dali.dashuyun.cn/Article/details/gtskktoppt.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yj20258.top/Article/details/gtcylyozll.html

[S32] C++：字符串
来源：http://dali.iojbl.cn/Article/details/gtqqcbyryi.html

std::string s = "hi";  s += "!";
来源：http://dali.sysykeji.top/Article/details/gtsvsouwgq.html

[S33] C++：vector 增删
来源：http://dali.yueranfly.top/Article/details/gtkmxtkydh.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsqkbslmj.html

[S34] C++：遍历 vector
来源：http://dali.yvedp.cn/Article/details/gtcyczgpwq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.andypj.xyz/Article/details/gtwkldqnqu.html

[S35] C++：map
来源：http://dali.nanxinkj.top/Article/details/gtcyvaxzoi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtnpiylsvb.html

[S36] C++：unordered_map
来源：http://dali.feifeiyinyue.top/Article/details/gtzcsbzxfk.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jiagoushi.top/Article/details/gtqkmqutkf.html

[S37] C++：set
来源：http://dali.ivvv.top/Article/details/gtovkckiin.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.daria6918.cn/Article/details/gtejqbmdgn.html

[S38] C++：排序
来源：http://dali.cdnleiting.top/Article/details/gtdshabnxg.html

std::sort(v.begin(), v.end());
来源：http://dali.xziqi.cn/Article/details/gtmawydbzy.html

[S39] C++：自定义比较器排序
来源：http://dali.redwolf501.top/Article/details/gtjbfaspio.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.mhx1999.top/Article/details/gtskvrnqoo.html

[S40] C++：查找元素
来源：http://dali.ppjwa.cn/Article/details/gthcxhhnnb.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.0kj1m.cn/Article/details/gtjaaqfzlu.html

[S41] C++：类与构造函数
来源：http://dali.meibo888.top/Article/details/gtnlidlvxl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.andypj.xyz/Article/details/gtppnzilju.html

[S42] C++：继承与虚函数
来源：http://dali.tianlin.xyz/Article/details/gtottnklmi.html

class B : public Base { public: void f() override {} };
来源：http://dali.ppjwa.cn/Article/details/gtlwbsvsfe.html

[S43] C++：智能指针
来源：http://dali.jlsjyb.cn/Article/details/gtpbcxgjlk.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhoulong.xyz/Article/details/gtjhicexpt.html

[S44] C++：引用传参
来源：http://dali.jinqigufen.top/Article/details/gtjiabymys.html

void inc(int &x) { ++x; }
来源：http://dali.yj20258.top/Article/details/gtivsbwuzs.html

[S45] C++：lambda
来源：http://dali.kuanghao11.cn/Article/details/gttzbbnrcx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.redwolf501.top/Article/details/gtihdrkvdb.html

[S46] C++：函数模板
来源：http://dali.xuanzx.com/Article/details/gtkbdbehko.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhengqikj.top/Article/details/gtxfykujab.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhengqikj.top/Article/details/gtbrsnqtdt.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.chenjidiqi.icu/Article/details/gtqtgyipqq.html

[S48] C++：逐行读文件
来源：http://dali.cashguo.top/Article/details/gtexsaimoq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.nanxuanxn.top/Article/details/gtusoplvus.html

while (std::getline(in, line)) { }
来源：http://dali.vqdsnc.cn/Article/details/gtbzvjzvln.html

[S49] C++：写文件
来源：http://dali.shangyingyoupin.top/Article/details/gtvfdxxwzg.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.chenzaomai.com/Article/details/gtgaeqivqw.html

[S50] C++：格式化数字
来源：http://dali.pycfn.com/Article/details/gtuxomlaro.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yongpay.top/Article/details/gturwrmvlx.html

[S51] C++：显式类型转换
来源：http://dali.jianghu66.top/Article/details/gtvedcwxth.html

static_cast<double>(a) / b
来源：http://dali.jianghu66.top/Article/details/gthshypvke.html

[S52] C++：const 与 noexcept
来源：http://dali.svipenyu.cn/Article/details/gtpwirsuoa.html

int size() const noexcept { return n_; }
来源：http://dali.bjfxy.top/Article/details/gtuefjszqc.html

[S53] C++：移动语义
来源：http://dali.ivvv.top/Article/details/gtpjmomcrw.html

std::vector<int> w = std::move(v);
来源：http://dali.yonumen.top/Article/details/gtsddmkufz.html

[S54] C++：异常处理
来源：http://dali.redwolf501.top/Article/details/gtsfabzpqe.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.nanxuanxn.top/Article/details/gtctvcoytw.html

[S55] C++：结构化绑定
来源：http://dali.birdmap.top/Article/details/gtigwdeswb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhengqikj.top/Article/details/gtffknqoea.html

[S56] C++：optional
来源：http://dali.andypj.xyz/Article/details/gtigoqokrx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hongshengwenyu.top/Article/details/gtxkwezskw.html

[S57] C++：编译期常量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtytkyjdub.html

constexpr int N = 10;
来源：http://dali.birdmap.top/Article/details/gtmvshwyiz.html

[S58] C++：命名空间
来源：http://dali.cashguo.top/Article/details/gtnvauefox.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinghuilouyu.cn/Article/details/gtexcgxldr.html

[S59] C++：静态断言
来源：http://dali.jianghu66.top/Article/details/gtgqkjbzai.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jyoumei.cn/Article/details/gtecnudbih.html

[S60] C++：遍历并删除元素
来源：http://dali.cdnleiting.top/Article/details/gtuuxjpuxl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.aizwys.cn/Article/details/gtxodbouvm.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gttdsapksn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenjidiqi.icu/Article/details/gtaczsdocq.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtjtelzhxl.html

[T01] Kotlin：Hello World
来源：http://dali.tian-w.cn/Article/details/gtgscmnzim.html

println("Hello")
来源：http://dali.aibaodan.cn/Article/details/gtsfuphedd.html

[T02] Kotlin：变量
来源：http://dali.chenjidiqi.icu/Article/details/gtwfmxottd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.chenzaomai.com/Article/details/gtxsaokxki.html

[T03] Kotlin：字符串模板
来源：http://dali.fzhhl.top/Article/details/gtjakoxsah.html

"值: $b"
来源：http://dali.feifeiyinyue.top/Article/details/gtedczmwco.html

[T04] Kotlin：空安全
来源：http://dali.quarkkingdee.top/Article/details/gtlogfhbja.html

val n: String? = null;  n?.length
来源：http://dali.jiagoushi.top/Article/details/gtjfuodwsk.html

[T05] Kotlin：when 表达式
来源：http://dali.daxiang520.top/Article/details/gtsjpdowtk.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shanyushiyangtech.top/Article/details/gtkhkirpay.html

[T06] Kotlin：集合映射
来源：http://dali.pycfn.com/Article/details/gtbirfsupn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtubskgplt.html

[T07] Kotlin：集合过滤
来源：http://dali.chenzaomai.com/Article/details/gtxdfvideb.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.tianlin.xyz/Article/details/gtrgilbhos.html

[T08] Kotlin：数据类
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteqwjbvxp.html

data class User(val name: String, val age: Int)
来源：http://dali.yj20258888.top/Article/details/gtrnfmxkkb.html

[T09] Kotlin：扩展函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsxrcqqiv.html

fun String.exclaim() = this + "!"
来源：http://dali.gzhubu.top/Article/details/gtxwzdsnrf.html

[T10] Kotlin：默认参数
来源：http://dali.aibaodan.cn/Article/details/gtjmptlgkw.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.gzhubu.top/Article/details/gtrmtswbob.html

[T11] Kotlin：协程
来源：http://dali.zycfv.cn/Article/details/gtjgihvmyv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ivvv.top/Article/details/gtiumjwouu.html

[T12] Kotlin：解构声明
来源：http://dali.zhongyouzk.top/Article/details/gtzafjadar.html

val (a, b) = Pair(1, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoqhawzpr.html

[T13] Kotlin：只读 Map
来源：http://dali.daxiang520.top/Article/details/gtljgzcoyw.html

val m = mapOf("a" to 1)
来源：http://dali.aibaodan.cn/Article/details/gtjkhclezm.html

[T14] Kotlin：循环
来源：http://dali.zdqjudy.top/Article/details/gtcxhmraan.html

for (i in 1..10) println(i)
来源：http://dali.xuanzx.com/Article/details/gtaglzbjvm.html

[T15] Kotlin：接口
来源：http://dali.nanxinkj.top/Article/details/gthwsmdrso.html

interface Shape { fun area(): Double }
来源：http://dali.hnxiangtu.top/Article/details/gtzecgryzx.html

[T16] Swift：Hello World
来源：http://dali.snrcjt.cn/Article/details/gtwuljahmc.html

print("Hello")
来源：http://dali.zhiwuduotai.top/Article/details/gtlviuhqzk.html

[T17] Swift：变量与常量
来源：http://dali.fzhhl.top/Article/details/gtxerlkeuq.html

var a = 1;  let b = 2
来源：http://dali.ivvv.top/Article/details/gtnpzqzpgh.html

[T18] Swift：字符串插值
来源：http://dali.wangshuangyany.cn/Article/details/gtslifuruz.html

"值: \(b)"
来源：http://dali.aibaodan.cn/Article/details/gttsbldagv.html

[T19] Swift：可选绑定
来源：http://dali.feifeiyinyue.top/Article/details/gtbeunuwtz.html

if let n = opt { print(n) }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtppgkrcml.html

[T20] Swift：数组操作
来源：http://dali.jianghu66.top/Article/details/gtapotjogn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.pycfn.com/Article/details/gtrgdilfpp.html

[T21] Swift：遍历
来源：http://dali.jlsjyb.cn/Article/details/gtembjexoo.html

for x in a { print(x) }
来源：http://dali.meibo888.top/Article/details/gtvoknghbj.html

[T22] Swift：字典
来源：http://dali.shzxlz.cn/Article/details/gtqymstbyw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xinyue.icu/Article/details/gtfrydcdsu.html

[T23] Swift：函数
来源：http://dali.zhoulong.xyz/Article/details/gtgmerickx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.guowangkeji.top/Article/details/gtzzqojgog.html

[T24] Swift：闭包
来源：http://dali.fzhhl.top/Article/details/gtkwvtcoyx.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.nanxinkj.top/Article/details/gthtilopyj.html

[T25] Swift：结构体
来源：http://dali.tianlin.xyz/Article/details/gtfeeakpjt.html

struct P { var x: Int }
来源：http://dali.guannengcc.top/Article/details/gtjkiuooyj.html

[T26] Swift：类与重写
来源：http://dali.svipenyu.cn/Article/details/gtvosoezll.html

class A: Base { override func f() {} }
来源：http://dali.andypj.xyz/Article/details/gtawqizgux.html

[T27] Swift：错误处理
来源：http://dali.redwolf501.top/Article/details/gtwwsosjtd.html

do { try f() } catch { print(error) }
来源：http://dali.wangdashe.top/Article/details/gtenzrlwey.html

[T28] Swift：枚举
来源：http://dali.yj20258.top/Article/details/gtoummgtrb.html

enum Color { case red, green }
来源：http://dali.sysykeji.top/Article/details/gtgizdxzuu.html

[T29] Swift：guard 提前返回
来源：http://dali.gotoacloud.top/Article/details/gtvxcpuwyc.html

guard let x = opt else { return }
来源：http://dali.316326.xyz/Article/details/gtxnqphroy.html

[T30] Swift：协议
来源：http://dali.iojbl.cn/Article/details/gtviuhrauf.html

protocol Shape { func area() -> Double }
来源：http://dali.iojbl.cn/Article/details/gtkdihjtfc.html

[T31] Lua：Hello World
来源：http://dali.yj20258888.top/Article/details/gtetzetnlu.html

print("Hello")
来源：http://dali.hnqzz.top/Article/details/gtfafvwepm.html

[T32] Lua：局部变量
来源：http://dali.haohaochexian.top/Article/details/gtpfzisemz.html

local a = 1
来源：http://dali.yj20258888.top/Article/details/gtkkdrgqod.html

[T33] Lua：表（数组）
来源：http://dali.0kj1m.cn/Article/details/gtovhthoff.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cheryme.top/Article/details/gtusavyjcm.html

[T34] Lua：遍历表
来源：http://dali.redwolf501.top/Article/details/gthestvqrt.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.fzhhl.top/Article/details/gtfkstazyb.html

[T35] Lua：字典表
来源：http://dali.9152youxi.cn/Article/details/gtoztgumug.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyowadqts.html

[T36] Lua：函数
来源：http://dali.shuidangran.top/Article/details/gtbbolbczz.html

function add(a, b) return a + b end
来源：http://dali.ydzc1.top/Article/details/gtyloksqic.html

[T37] Lua：字符串拼接
来源：http://dali.jianghu66.top/Article/details/gtinrqkids.html

"a" .. "b"
来源：http://dali.zhixingplan.top/Article/details/gtacwguigl.html

[T38] Lua：条件
来源：http://dali.316326.xyz/Article/details/gtxyxohrrm.html

if x > 0 then print("正") end
来源：http://dali.yvedp.cn/Article/details/gtcsgqvswk.html

[T39] Lua：模式匹配
来源：http://dali.yongpay.top/Article/details/gtrpjpinzo.html

string.find(s, "%d+")
来源：http://dali.316326.xyz/Article/details/gtmyddbtvs.html

[T40] Lua：元表
来源：http://dali.wangshuangyany.cn/Article/details/gtmxgwgsgw.html

setmetatable({}, { __index = base })
来源：http://dali.birdmap.top/Article/details/gtutgyiisw.html

[T41] Perl：Hello World
来源：http://dali.guannengcc.top/Article/details/gtgqoxouzu.html

print "Hello\n";
来源：http://dali.gaohongyu789.top/Article/details/gtuhnfzboy.html

[T42] Perl：变量类型
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsmkcdwbf.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.guowangkeji.top/Article/details/gtowhgozpp.html

[T43] Perl：字符串插值
来源：http://dali.gaohongyu789.top/Article/details/gtfgksrnah.html

"值: $a"
来源：http://dali.zhengqikj.top/Article/details/gtdqlqvahp.html

[T44] Perl：条件
来源：http://dali.ivvv.top/Article/details/gtusmmqprc.html

if ($a > 0) { print "正"; }
来源：http://dali.bjfxy.top/Article/details/gtmkdtxqbt.html

[T45] Perl：数组遍历
来源：http://dali.zhongyouzk.top/Article/details/gtwtgytpjw.html

for my $x (@arr) { print $x; }
来源：http://dali.yj20258888.top/Article/details/gtxwvpnysj.html

[T46] Perl：哈希操作
来源：http://dali.dianchejie.cn/Article/details/gtcnmouday.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdasuwzba.html

[T47] Perl：正则捕获
来源：http://dali.ybcxt.top/Article/details/gthsqfmkjn.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.tanke756.top/Article/details/gtgqidyyzn.html

[T48] Perl：正则替换
来源：http://dali.chenjidiqi.icu/Article/details/gtrhrxvwcw.html

$s =~ s/old/new/g;
来源：http://dali.gotoacloud.top/Article/details/gtmulzbbuu.html


<!-- 参考信息 -->