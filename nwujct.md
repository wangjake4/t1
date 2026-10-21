代发 wailian999

find . -name "*.tmp" -delete
来源：http://dali.jyoumei.cn/Article/details/gtiwrrplia.html

[R46] 递归替换文件内容
来源：http://dali.cqqwz.cn/Article/details/gtpkexrmfu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.0kj1m.cn/Article/details/gthdoxxfgs.html

[R47] sed 单行替换
来源：http://dali.vqdsnc.cn/Article/details/gtfvgbdljr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtqmexpxkm.html

[R48] awk 取指定列
来源：http://dali.tanke756.top/Article/details/gtjfsvtekq.html

awk '{print $1, $3}' a.txt
来源：http://dali.c1oappe.top/Article/details/gtqfkdhxog.html

[R49] awk 带条件
来源：http://dali.jinqigfzy.top/Article/details/gtisjgqowr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.bjfxy.top/Article/details/gtpqokansv.html

[R50] awk 求和
来源：http://dali.ivvv.top/Article/details/gtfygcddkp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.aizwys.cn/Article/details/gtpzgcynld.html

[R51] 排序去重取前几
来源：http://dali.jinghuilouyu.cn/Article/details/gtnplyytvz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yj20258.top/Article/details/gtijluivzp.html

[R52] 统计行数
来源：http://dali.yj20258.top/Article/details/gtxrlwngbz.html

wc -l a.txt
来源：http://dali.andypj.xyz/Article/details/gtnhkbfcdf.html

[R53] 查看文件头与实时尾
来源：http://dali.aizwys.cn/Article/details/gtuyqoopbn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cashguo.top/Article/details/gttbmnbbxs.html

[R54] 比较两个文件
来源：http://dali.bjfxy.top/Article/details/gtqvktvdes.html

diff a.txt b.txt
来源：http://dali.yj20258.top/Article/details/gtssofioti.html

[R55] 压缩与解压
来源：http://dali.cashguo.top/Article/details/gttuszmtto.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.havefunace.top/Article/details/gtlmpyidyv.html

[R56] 远程拷贝
来源：http://dali.redwolf501.top/Article/details/gtmbtbjyqw.html

scp file user@host:/path/
来源：http://dali.jinqigufen.top/Article/details/gthlxlcjwa.html

[R57] 远程执行命令
来源：http://dali.chenlongwang.top/Article/details/gtmbdxtgnn.html

ssh user@host 'uptime'
来源：http://dali.fzhhl.top/Article/details/gtrzrcceoi.html

[R58] 下载文件
来源：http://dali.zhongyouzk.top/Article/details/gtcnrrmqqg.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.birdmap.top/Article/details/gtkfiksbqr.html

[R59] 发 POST JSON
来源：http://dali.cqqwz.cn/Article/details/gtwwokufgs.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhiwuduotai.top/Article/details/gtqhmskijl.html

[R60] 只看 HTTP 状态码
来源：http://dali.fengsongda.top/Article/details/gtbfcpjizq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gtjbzaekax.html

[R61] 磁盘占用
来源：http://dali.jinghuilouyu.cn/Article/details/gtgvflgxjs.html

df -h;  du -sh *
来源：http://dali.tanke756.top/Article/details/gtxphnsjzn.html

[R62] 找最占空间的文件
来源：http://dali.yueranfly.top/Article/details/gtjvdtfhgh.html

du -ah . | sort -rh | head -10
来源：http://dali.sweek.top/Article/details/gtuaiusgcu.html

[R63] 内存与进程
来源：http://dali.jiagoushi.top/Article/details/gtlwfrwvmo.html

free -h;  ps aux | grep nginx
来源：http://dali.tianlin.xyz/Article/details/gtjcwyskqd.html

[R64] 结束进程
来源：http://dali.tanke756.top/Article/details/gtqyjwavsa.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hongshengwenyu.top/Article/details/gthgossurw.html

[R65] 查看端口占用
来源：http://dali.yanxiufei.cn/Article/details/gtuyxzvwdw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yanxiufei.cn/Article/details/gtezogzdrf.html

[R66] 定时任务
来源：http://dali.haohaochexian.top/Article/details/gtmqymkdrc.html

crontab -e;  crontab -l
来源：http://dali.xuanzx.com/Article/details/gtwgnsyurx.html

[R67] 生成随机十六进制串
来源：http://dali.haohaochexian.top/Article/details/gtqftkwaqw.html

openssl rand -hex 16
来源：http://dali.shangyingyoupin.top/Article/details/gtdfbgjgtq.html

[R68] 计算文件校验值
来源：http://dali.jqgfzy.top/Article/details/gtzddjirre.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtuwbkffzc.html

[R69] 生成随机密码
来源：http://dali.birdmap.top/Article/details/gtvdcbpadf.html

head -c 16 /dev/urandom | base64
来源：http://dali.mhx1999.top/Article/details/gthtzbngpr.html

[R70] 时间戳与互转
来源：http://dali.cqqwz.cn/Article/details/gtahkpgtze.html

date +%s;  date -d @1700000000
来源：http://dali.daxiang520.top/Article/details/gtljijhdpf.html

[R71] 日期格式化
来源：http://dali.meibo888.top/Article/details/gtfqocerzz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.guannengcc.top/Article/details/gtbdogzddb.html

[R72] 等待端口就绪
来源：http://dali.hywenlv.cn/Article/details/gtotogvjyl.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jianghu66.top/Article/details/gtqpsopzns.html

[R73] 分割大日志
来源：http://dali.yueranfly.top/Article/details/gtrnssxssz.html

split -l 1000 big.log part_
来源：http://dali.chenlongwang.top/Article/details/gtjfqefkwr.html

[R74] 批量重命名
来源：http://dali.guowangkeji.top/Article/details/gtcdemhtrf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.fengsongda.top/Article/details/gtncdbxxpo.html

[R75] 导出环境变量
来源：http://dali.ehwqpu.com/Article/details/gtwnphechx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.mhx1999.top/Article/details/gtjrzncqqn.html

[R76] 使用临时文件
来源：http://dali.yuxming.cn/Article/details/gttbfnhzpk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgfzy.top/Article/details/gtzvazqhni.html

[R77] 读取用户输入
来源：http://dali.wangdashe.top/Article/details/gtttofeimp.html

read -rp "请输入: " ans
来源：http://dali.chenjidiqi.icu/Article/details/gtujokmmzm.html

[R78] 交互式菜单
来源：http://dali.tian-w.cn/Article/details/gtkmnckhpr.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.fzhhl.top/Article/details/gtorepcfom.html

[R79] 解析命令行选项
来源：http://dali.gaohongyu789.top/Article/details/gttzijikda.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yj20258.top/Article/details/gtehcaqbhz.html

[R80] 查看脚本执行耗时
来源：http://dali.yongpay.top/Article/details/gtkqzjexsp.html

time ./run.sh
来源：http://dali.ybcxt.top/Article/details/gtjmnammuy.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gthqfvsvsc.html

S. C / C++ 专题
来源：http://dali.316326.xyz/Article/details/gtoxodixsh.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtumgpvwjt.html

[S01] C：Hello World
来源：http://dali.xinyue.icu/Article/details/gtjaxzqhpp.html

#include <stdio.h>
来源：http://dali.shanyushiyangkeji.top/Article/details/gtybwljbuo.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cashguo.top/Article/details/gtkcfgwkvt.html

[S02] C：变量与格式化输出
来源：http://dali.aibaodan.cn/Article/details/gtvwutygts.html

int a = 10; printf("%d\n", a);
来源：http://dali.316326.xyz/Article/details/gtebyidibl.html

[S03] C：读入整数
来源：http://dali.hfpthk.cn/Article/details/gtnvnebejt.html

int x; scanf("%d", &x);
来源：http://dali.dianchejie.cn/Article/details/gturnzgpfr.html

[S04] C：字符串复制
来源：http://dali.nwbrower.top/Article/details/gtwxmafjom.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.aibaodan.cn/Article/details/gtsjducfah.html

[S05] C：字符串长度
来源：http://dali.wangshuangyany.cn/Article/details/gttimlevcv.html

strlen(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqhnzobga.html

[S06] C：字符串比较
来源：http://dali.yangfankeji.com/Article/details/gtlzzmmuoa.html

strcmp(a, b) == 0
来源：http://dali.sxryk.cn/Article/details/gtesnracvy.html

[S07] C：数组遍历求和
来源：http://dali.xziqi.cn/Article/details/gtvdeyjvzz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zycfv.cn/Article/details/gtpnkmisms.html

[S08] C：动态内存分配与释放
来源：http://dali.hongshengwenyu.top/Article/details/gtwoaccxja.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cashguo.top/Article/details/gtvmdylxdk.html

[S09] C：结构体定义与初始化
来源：http://dali.yj202588.top/Article/details/gtsagowocm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.sxryk.cn/Article/details/gtjchyklay.html

[S10] C：指针与解引用
来源：http://dali.pycfn.com/Article/details/gtsdwyyrvx.html

int *p = &a;  *p = 5;
来源：http://dali.pycfn.com/Article/details/gtsfwbmdkv.html

[S11] C：逐行读文件
来源：http://dali.zhixingplan.top/Article/details/gtrvemhkza.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.aizwys.cn/Article/details/gtgtjszqnn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhixingplan.top/Article/details/gtiurayrqc.html

fclose(f);
来源：http://dali.yonumen.top/Article/details/gtlfmjqktv.html

[S12] C：写文件
来源：http://dali.zhiwuduotai.top/Article/details/gthzkrqigl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sufxvd.cn/Article/details/gtpzpyycgz.html

[S13] C：宏定义
来源：http://dali.pengpengdd.cyou/Article/details/gtmaoupcye.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.snrcjt.cn/Article/details/gtyapffkiz.html

[S14] C：枚举
来源：http://dali.chenlongwang.top/Article/details/gtmfrhiilu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jianghu66.top/Article/details/gtrblepjsw.html

[S15] C：类型转换
来源：http://dali.quarkkingdee.top/Article/details/gtwozypawl.html

(double) a / b
来源：http://dali.yangfankeji.com/Article/details/gtkrybvwml.html

[S16] C：位操作置位
来源：http://dali.kuanghao11.cn/Article/details/gtrlqmowcq.html

x |= (1 << 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtihwtbthv.html

[S17] C：安全拼接字符串
来源：http://dali.tianlin.xyz/Article/details/gtquwycjep.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hywenlv.cn/Article/details/gtviohytqn.html

[S18] C：命令行参数
来源：http://dali.mhx1999.top/Article/details/gtyzxdbwrc.html

int main(int argc, char **argv)
来源：http://dali.jinqigfzy.top/Article/details/gtebzvkhyl.html

[S19] C：快速排序
来源：http://dali.gogol.net.cn/Article/details/gtmgyzzjag.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hfpthk.cn/Article/details/gtfrffqywx.html

[S20] C：二分查找
来源：http://dali.nwbrower.top/Article/details/gtatweewkt.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jiagoushi.top/Article/details/gtsbvfmqmp.html

[S21] C：字符类别判断
来源：http://dali.guowangkeji.top/Article/details/gtshbjqpeg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvppzwxfu.html

[S22] C：字符串转数字
来源：http://dali.guowangkeji.top/Article/details/gthoivjzvf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hnxiangtu.top/Article/details/gtuwqidpkb.html

[S23] C：随机数
来源：http://dali.zycfv.cn/Article/details/gtcajeakgc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cashguo.top/Article/details/gteauwdubr.html

[S24] C：获取本地时间
来源：http://dali.yj20258.top/Article/details/gtxmlwyxpk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhengqikj.top/Article/details/gtxzqrweye.html

[S25] C：内存拷贝
来源：http://dali.jinqigfzy.top/Article/details/gtwrgyhfos.html

memcpy(dst, src, n);
来源：http://dali.birdmap.top/Article/details/gtuhpykekl.html

[S26] C：内存清零
来源：http://dali.yvedp.cn/Article/details/gtiyszmxfd.html

memset(a, 0, sizeof a);
来源：http://dali.nanxinkj.top/Article/details/gtvtvypurv.html

[S27] C：定义常量
来源：http://dali.redwolf501.top/Article/details/gtbrzvdqtn.html

const double PI = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gtwvibcvxk.html

[S28] C：静态变量
来源：http://dali.dashuyun.cn/Article/details/gtsrtfgvei.html

static int counter = 0;
来源：http://dali.xziqi.cn/Article/details/gtdmdwkysk.html

[S29] C：变参函数
来源：http://dali.sweek.top/Article/details/gttlowdlkz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqbpyayeh.html

[S30] C：头文件保护
来源：http://dali.smart0.xyz/Article/details/gtjujhwxdn.html

#ifndef X_H
来源：http://dali.chenjidiqi.icu/Article/details/gtzfmvlwkq.html

#define X_H
来源：http://dali.yonumen.top/Article/details/gtchaabmma.html

#endif
来源：http://dali.xuanzx.com/Article/details/gthicwgaod.html

[S31] C++：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtzziqpzpr.html

#include <iostream>
来源：http://dali.daxiang520.top/Article/details/gtjweefodo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jinqigfzy.top/Article/details/gtpjbipdxk.html

[S32] C++：字符串
来源：http://dali.gzhubu.top/Article/details/gtqrwwvekk.html

std::string s = "hi";  s += "!";
来源：http://dali.hysaishi.cn/Article/details/gtvvlnqosz.html

[S33] C++：vector 增删
来源：http://dali.sufxvd.cn/Article/details/gtvsjvggld.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.fengsongda.top/Article/details/gtfuccthro.html

[S34] C++：遍历 vector
来源：http://dali.gzhubu.top/Article/details/gtugivkbvu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.redwolf501.top/Article/details/gtgbzhwwrf.html

[S35] C++：map
来源：http://dali.pycfn.com/Article/details/gtivbjacfm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gtlqldongw.html

[S36] C++：unordered_map
来源：http://dali.sysykeji.top/Article/details/gtsxlxovku.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.snrcjt.cn/Article/details/gtmooegdfw.html

[S37] C++：set
来源：http://dali.yj20258.top/Article/details/gteikmjnrt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ydzc1.top/Article/details/gtwxotgzvy.html

[S38] C++：排序
来源：http://dali.yuanzhike.top/Article/details/gtliwryxqm.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gtgrtupnmi.html

[S39] C++：自定义比较器排序
来源：http://dali.xuetiantiany.cn/Article/details/gtjaahnhws.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.nanxuanxn.top/Article/details/gtyxmukaej.html

[S40] C++：查找元素
来源：http://dali.xuanzx.com/Article/details/gtoooafmao.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.vqdsnc.cn/Article/details/gtyhsropwi.html

[S41] C++：类与构造函数
来源：http://dali.yongpay.top/Article/details/gtkhmnjonj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.daxiang520.top/Article/details/gtxhzlezeg.html

[S42] C++：继承与虚函数
来源：http://dali.guannengcc.top/Article/details/gtrnizcaro.html

class B : public Base { public: void f() override {} };
来源：http://dali.xziqi.cn/Article/details/gtmcozrhbm.html

[S43] C++：智能指针
来源：http://dali.jqgfzy.top/Article/details/gtobuetokb.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhengqikj.top/Article/details/gtzvxqfrqd.html

[S44] C++：引用传参
来源：http://dali.hongshengwenyu.top/Article/details/gtrkdrxxbc.html

void inc(int &x) { ++x; }
来源：http://dali.shangyingyoupin.top/Article/details/gtmeiemfrp.html

[S45] C++：lambda
来源：http://dali.daxiang520.top/Article/details/gtsusobzzx.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xinyue.icu/Article/details/gtotbaclje.html

[S46] C++：函数模板
来源：http://dali.ehwqpu.com/Article/details/gtmflntnzp.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gtczvtjsrq.html

[S47] C++：结构化绑定遍历
来源：http://dali.ivvv.top/Article/details/gtbjxvbsdi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ehwqpu.com/Article/details/gtjrzqjhyl.html

[S48] C++：逐行读文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtllexjegu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.dashuyun.cn/Article/details/gtpvolbujg.html

while (std::getline(in, line)) { }
来源：http://dali.gogol.net.cn/Article/details/gttqlqoigx.html

[S49] C++：写文件
来源：http://dali.tanke756.top/Article/details/gtwutkopmr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yonumen.top/Article/details/gtdsjituop.html

[S50] C++：格式化数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdvnllnbk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.redwolf501.top/Article/details/gtiimbxmue.html

[S51] C++：显式类型转换
来源：http://dali.c1oappe.top/Article/details/gtgnzzvajc.html

static_cast<double>(a) / b
来源：http://dali.svipenyu.cn/Article/details/gtprqmfeql.html

[S52] C++：const 与 noexcept
来源：http://dali.yangfankeji.com/Article/details/gtgwestbne.html

int size() const noexcept { return n_; }
来源：http://dali.sysykeji.top/Article/details/gtzaxsqgik.html

[S53] C++：移动语义
来源：http://dali.yvedp.cn/Article/details/gterpqzmdm.html

std::vector<int> w = std::move(v);
来源：http://dali.zhengqikj.top/Article/details/gtsedjoeqf.html

[S54] C++：异常处理
来源：http://dali.jlsjyb.cn/Article/details/gtnvehwptn.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.vqdsnc.cn/Article/details/gtbxnhxnwe.html

[S55] C++：结构化绑定
来源：http://dali.andypj.xyz/Article/details/gtviepfsla.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jiagoushi.top/Article/details/gtmmjefpbf.html

[S56] C++：optional
来源：http://dali.yueranfly.top/Article/details/gtbojqvaxl.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shangyingyoupin.top/Article/details/gtzcewkrlg.html

[S57] C++：编译期常量
来源：http://dali.tianlin.xyz/Article/details/gtzmeujpqo.html

constexpr int N = 10;
来源：http://dali.aizwys.cn/Article/details/gtnzabixjl.html

[S58] C++：命名空间
来源：http://dali.wangshuangyany.cn/Article/details/gtacykrteg.html

namespace ns { int f() { return 1; } }
来源：http://dali.snrcjt.cn/Article/details/gtwjtbbksl.html

[S59] C++：静态断言
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiinapybp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.9152youxi.cn/Article/details/gtpnrevvdn.html

[S60] C++：遍历并删除元素
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvzpvaang.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ehwqpu.com/Article/details/gtndremljg.html

================================================================================
来源：http://dali.sweek.top/Article/details/gteqzgbfvu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenjidiqi.icu/Article/details/gtxddjbmgp.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gttokjsxch.html

[T01] Kotlin：Hello World
来源：http://dali.guannengcc.top/Article/details/gtykgtdajy.html

println("Hello")
来源：http://dali.xziqi.cn/Article/details/gtehttavym.html

[T02] Kotlin：变量
来源：http://dali.cqqwz.cn/Article/details/gtnhgghtlv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cucudq.cn/Article/details/gtgtxqdvtj.html

[T03] Kotlin：字符串模板
来源：http://dali.wangdashe.top/Article/details/gtrnjzvrpt.html

"值: $b"
来源：http://dali.shuidangran.top/Article/details/gtspildbql.html

[T04] Kotlin：空安全
来源：http://dali.chenjidiqi.icu/Article/details/gtnrztrbxn.html

val n: String? = null;  n?.length
来源：http://dali.jianghu66.top/Article/details/gtirtrtajh.html

[T05] Kotlin：when 表达式
来源：http://dali.yj202588.top/Article/details/gtkdbrcxkm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sysykeji.top/Article/details/gtbrbqukue.html

[T06] Kotlin：集合映射
来源：http://dali.dianchejie.cn/Article/details/gtrzetffny.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hongshengwenyu.top/Article/details/gtumrjqhbm.html

[T07] Kotlin：集合过滤
来源：http://dali.fengsongda.top/Article/details/gtzsupvdif.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sysykeji.top/Article/details/gtxalxfldh.html

[T08] Kotlin：数据类
来源：http://dali.kuanghao11.cn/Article/details/gtwxwhfuyh.html

data class User(val name: String, val age: Int)
来源：http://dali.jinqigufen.top/Article/details/gtzvltfplz.html

[T09] Kotlin：扩展函数
来源：http://dali.yueranfly.top/Article/details/gteddsobzv.html

fun String.exclaim() = this + "!"
来源：http://dali.zycfv.cn/Article/details/gtfgdbaqbc.html

[T10] Kotlin：默认参数
来源：http://dali.wangdashe.top/Article/details/gtxscxgxew.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.xylfe.cn/Article/details/gtljldlayp.html

[T11] Kotlin：协程
来源：http://dali.yj20258.top/Article/details/gtcquiisch.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sweek.top/Article/details/gtzhjlbjmq.html

[T12] Kotlin：解构声明
来源：http://dali.xylfe.cn/Article/details/gtayxbvute.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhijiandao.cn/Article/details/gtbstfvaes.html

[T13] Kotlin：只读 Map
来源：http://dali.xylfe.cn/Article/details/gtugnusxcs.html

val m = mapOf("a" to 1)
来源：http://dali.sufxvd.cn/Article/details/gteoyvkxem.html

[T14] Kotlin：循环
来源：http://dali.hnqzz.top/Article/details/gtlbxqtcah.html

for (i in 1..10) println(i)
来源：http://dali.hammf.cn/Article/details/gtkxxkyetv.html

[T15] Kotlin：接口
来源：http://dali.hongshengwenyu.top/Article/details/gtmkbaeumi.html

interface Shape { fun area(): Double }
来源：http://dali.yuanzhike.top/Article/details/gtdmmvnbal.html

[T16] Swift：Hello World
来源：http://dali.sweek.top/Article/details/gtxlajoope.html

print("Hello")
来源：http://dali.zhiwuduotai.top/Article/details/gtamoyehjp.html

[T17] Swift：变量与常量
来源：http://dali.birdmap.top/Article/details/gtbcdkopoi.html

var a = 1;  let b = 2
来源：http://dali.chenlongwang.top/Article/details/gtckcetend.html

[T18] Swift：字符串插值
来源：http://dali.c1oappe.top/Article/details/gtcaybzdzm.html

"值: \(b)"
来源：http://dali.yuanzhike.top/Article/details/gtvsvnngux.html

[T19] Swift：可选绑定
来源：http://dali.meibo888.top/Article/details/gtkqjkbqts.html

if let n = opt { print(n) }
来源：http://dali.haohaochexian.top/Article/details/gtusqyruci.html

[T20] Swift：数组操作
来源：http://dali.tianlin.xyz/Article/details/gtrwkwhxgf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hnxiangtu.top/Article/details/gtkknryqws.html

[T21] Swift：遍历
来源：http://dali.birdmap.top/Article/details/gtmqnejnlf.html

for x in a { print(x) }
来源：http://dali.smart0.xyz/Article/details/gtjjfkilph.html

[T22] Swift：字典
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdjiysubw.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrgixxohp.html

[T23] Swift：函数
来源：http://dali.xuanzx.com/Article/details/gtqqgwucgr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yvedp.cn/Article/details/gtkrwwadrj.html

[T24] Swift：闭包
来源：http://dali.shangyingyoupin.top/Article/details/gtqhqchndh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.iojbl.cn/Article/details/gtwnzmnele.html

[T25] Swift：结构体
来源：http://dali.cdnleiting.top/Article/details/gtwydusrit.html

struct P { var x: Int }
来源：http://dali.jyoumei.cn/Article/details/gtvgldmeyf.html

[T26] Swift：类与重写
来源：http://dali.jqgufenzy.top/Article/details/gtmslccvyn.html

class A: Base { override func f() {} }
来源：http://dali.chenjidiqi.icu/Article/details/gtkpokxvsf.html

[T27] Swift：错误处理
来源：http://dali.jinqigfzy.top/Article/details/gtkzcnikxh.html

do { try f() } catch { print(error) }
来源：http://dali.dashuyun.cn/Article/details/gtsrsazbnt.html

[T28] Swift：枚举
来源：http://dali.bjfxy.top/Article/details/gtikvgxlpx.html

enum Color { case red, green }
来源：http://dali.svipenyu.cn/Article/details/gtsyfhcxot.html

[T29] Swift：guard 提前返回
来源：http://dali.mhx1999.top/Article/details/gthpzydpqu.html

guard let x = opt else { return }
来源：http://dali.nwbrower.top/Article/details/gtqthgfvic.html

[T30] Swift：协议
来源：http://dali.jinqigufen.top/Article/details/gtcnnexxta.html

protocol Shape { func area() -> Double }
来源：http://dali.yueranfly.top/Article/details/gthmdeaofc.html

[T31] Lua：Hello World
来源：http://dali.birdmap.top/Article/details/gtdalqpncr.html

print("Hello")
来源：http://dali.sweek.top/Article/details/gtrxlzgdyx.html

[T32] Lua：局部变量
来源：http://dali.guannengcc.top/Article/details/gtuayphxos.html

local a = 1
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxlnvcljz.html

[T33] Lua：表（数组）
来源：http://dali.gzhubu.top/Article/details/gtbbjcoodi.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.0kj1m.cn/Article/details/gtjqwmbays.html

[T34] Lua：遍历表
来源：http://dali.xinyue.icu/Article/details/gtevckavbx.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yonumen.top/Article/details/gtcccutnru.html

[T35] Lua：字典表
来源：http://dali.0kj1m.cn/Article/details/gtrkshifip.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhoulong.xyz/Article/details/gtykaogwew.html

[T36] Lua：函数
来源：http://dali.gogol.net.cn/Article/details/gticdffqeq.html

function add(a, b) return a + b end
来源：http://dali.haohaochexian.top/Article/details/gtyqcmvijy.html

[T37] Lua：字符串拼接
来源：http://dali.guowangkeji.top/Article/details/gtgbtejzvk.html

"a" .. "b"
来源：http://dali.hammf.cn/Article/details/gtvhccvyov.html

[T38] Lua：条件
来源：http://dali.ybcxt.top/Article/details/gtpmajibhd.html

if x > 0 then print("正") end
来源：http://dali.chenlongwang.top/Article/details/gtnwldlshj.html

[T39] Lua：模式匹配
来源：http://dali.mhx1999.top/Article/details/gtmfqtbgtj.html

string.find(s, "%d+")
来源：http://dali.yvedp.cn/Article/details/gthggyzaxc.html

[T40] Lua：元表
来源：http://dali.jinyuanbaomall.cn/Article/details/gtffcsjrto.html

setmetatable({}, { __index = base })
来源：http://dali.shzxlz.cn/Article/details/gtshxrhawp.html

[T41] Perl：Hello World
来源：http://dali.cdnleiting.top/Article/details/gtyjfrkdfc.html

print "Hello\n";
来源：http://dali.yvedp.cn/Article/details/gtomjczyit.html

[T42] Perl：变量类型
来源：http://dali.redwolf501.top/Article/details/gtjrzqsxml.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.shzxlz.cn/Article/details/gttaloohpn.html

[T43] Perl：字符串插值
来源：http://dali.xziqi.cn/Article/details/gtafpxzfil.html

"值: $a"
来源：http://dali.zhongyouzk.top/Article/details/gtxshvozhx.html

[T44] Perl：条件
来源：http://dali.andypj.xyz/Article/details/gtoazvbizb.html

if ($a > 0) { print "正"; }
来源：http://dali.tianlin.xyz/Article/details/gtcqacduxi.html

[T45] Perl：数组遍历
来源：http://dali.hywenlv.cn/Article/details/gtwnckeags.html

for my $x (@arr) { print $x; }
来源：http://dali.ppjwa.cn/Article/details/gtbfieylfz.html

[T46] Perl：哈希操作
来源：http://dali.yonumen.top/Article/details/gtfwquobbi.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.cqqwz.cn/Article/details/gtsxledlrh.html

[T47] Perl：正则捕获
来源：http://dali.jyoumei.cn/Article/details/gtjpuwbeig.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.jyoumei.cn/Article/details/gtsjgcvyih.html

[T48] Perl：正则替换
来源：http://dali.sweek.top/Article/details/gtamhvyxtn.html

$s =~ s/old/new/g;
来源：http://dali.aizwys.cn/Article/details/gtdmdatumc.html


<!-- 参考信息 -->