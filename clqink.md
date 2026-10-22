代发 wailian999

find . -name "*.tmp" -delete
来源：http://dali.pengpengdd.cyou/Article/details/gtejpvtmcy.html

[R46] 递归替换文件内容
来源：http://dali.hongshengwenyu.top/Article/details/gtxxqjtgbk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.mhx1999.top/Article/details/gtvrquqpit.html

[R47] sed 单行替换
来源：http://dali.jianghu66.top/Article/details/gtrwfyuynt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtsjorfkiv.html

[R48] awk 取指定列
来源：http://dali.yj20258.top/Article/details/gthictnvti.html

awk '{print $1, $3}' a.txt
来源：http://dali.svipenyu.cn/Article/details/gthsulcdmz.html

[R49] awk 带条件
来源：http://dali.ppjwa.cn/Article/details/gtnkexkcrx.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.wangshuangyany.cn/Article/details/gtpypkseay.html

[R50] awk 求和
来源：http://dali.zhixingplan.top/Article/details/gthlqpcing.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.iojbl.cn/Article/details/gtgrsaarlv.html

[R51] 排序去重取前几
来源：http://dali.zycfv.cn/Article/details/gtnombubmu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shuidangran.top/Article/details/gtmlrsctdf.html

[R52] 统计行数
来源：http://dali.sxryk.cn/Article/details/gtxyvhzgdu.html

wc -l a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsloeivni.html

[R53] 查看文件头与实时尾
来源：http://dali.bjfxy.top/Article/details/gtdjhejwcm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.c1oappe.top/Article/details/gtvzjiknka.html

[R54] 比较两个文件
来源：http://dali.sxryk.cn/Article/details/gtsflddnvd.html

diff a.txt b.txt
来源：http://dali.zhixingplan.top/Article/details/gtmydfhpbv.html

[R55] 压缩与解压
来源：http://dali.jiagoushi.top/Article/details/gtgtplslih.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gaohongyu789.top/Article/details/gtbedsnmyk.html

[R56] 远程拷贝
来源：http://dali.hywenlv.cn/Article/details/gtjmmayfoa.html

scp file user@host:/path/
来源：http://dali.hnxiangtu.top/Article/details/gtdrktbhrm.html

[R57] 远程执行命令
来源：http://dali.chenjidiqi.icu/Article/details/gtnftlfofb.html

ssh user@host 'uptime'
来源：http://dali.dianchejie.cn/Article/details/gtopdokupr.html

[R58] 下载文件
来源：http://dali.iojbl.cn/Article/details/gtioyajfau.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.pycfn.com/Article/details/gtclescuau.html

[R59] 发 POST JSON
来源：http://dali.hnqzz.top/Article/details/gtqilqcrnp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sufxvd.cn/Article/details/gtojumywef.html

[R60] 只看 HTTP 状态码
来源：http://dali.chenzaomai.com/Article/details/gtxwytlorq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqoatppjv.html

[R61] 磁盘占用
来源：http://dali.zhengqikj.top/Article/details/gtougwgggy.html

df -h;  du -sh *
来源：http://dali.snrcjt.cn/Article/details/gtucwadhkc.html

[R62] 找最占空间的文件
来源：http://dali.pengpengdd.cyou/Article/details/gtrghrmszc.html

du -ah . | sort -rh | head -10
来源：http://dali.shanyushiyangtech.top/Article/details/gtjoaytxlc.html

[R63] 内存与进程
来源：http://dali.9152youxi.cn/Article/details/gteszxakit.html

free -h;  ps aux | grep nginx
来源：http://dali.sxryk.cn/Article/details/gtkgwvkvel.html

[R64] 结束进程
来源：http://dali.jinqigfzy.top/Article/details/gtawudcsfx.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ehwqpu.com/Article/details/gtoecixbbf.html

[R65] 查看端口占用
来源：http://dali.daria6918.cn/Article/details/gtmeaieqpa.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hammf.cn/Article/details/gtiyfmlvlm.html

[R66] 定时任务
来源：http://dali.nanxuanxn.top/Article/details/gtevrzqxuf.html

crontab -e;  crontab -l
来源：http://dali.vqdsnc.cn/Article/details/gtbplswirx.html

[R67] 生成随机十六进制串
来源：http://dali.zdqjudy.top/Article/details/gtdotszhsl.html

openssl rand -hex 16
来源：http://dali.ehwqpu.com/Article/details/gtbiijlwth.html

[R68] 计算文件校验值
来源：http://dali.shzxlz.cn/Article/details/gtmhvmwjdb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yj20258888.top/Article/details/gtetklulzu.html

[R69] 生成随机密码
来源：http://dali.xylfe.cn/Article/details/gtxpscfofw.html

head -c 16 /dev/urandom | base64
来源：http://dali.haohaochexian.top/Article/details/gtwjtrizgi.html

[R70] 时间戳与互转
来源：http://dali.aizwys.cn/Article/details/gtkuwrcxkl.html

date +%s;  date -d @1700000000
来源：http://dali.zhongyouzk.top/Article/details/gtfolfyvgc.html

[R71] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gtreazqfex.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.0kj1m.cn/Article/details/gtinoofxts.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gtqmmjoqvc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.tianlin.xyz/Article/details/gtxedgkrlx.html

[R73] 分割大日志
来源：http://dali.nwbrower.top/Article/details/gtkfjbfyji.html

split -l 1000 big.log part_
来源：http://dali.pycfn.com/Article/details/gtvrmslmsq.html

[R74] 批量重命名
来源：http://dali.haohaochexian.top/Article/details/gtsvvuvoex.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cdnleiting.top/Article/details/gtabtfhsjt.html

[R75] 导出环境变量
来源：http://dali.daria6918.cn/Article/details/gtwcisuvhc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.fzhhl.top/Article/details/gtjxrjovop.html

[R76] 使用临时文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqrbyywye.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.0kj1m.cn/Article/details/gtpzcmqpzl.html

[R77] 读取用户输入
来源：http://dali.pengpengdd.cyou/Article/details/gtrkvlrzok.html

read -rp "请输入: " ans
来源：http://dali.ivvv.top/Article/details/gtywienucy.html

[R78] 交互式菜单
来源：http://dali.pycfn.com/Article/details/gtmocnoxuf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.chenlongwang.top/Article/details/gtkpcitkfd.html

[R79] 解析命令行选项
来源：http://dali.ybcxt.top/Article/details/gtuttbqixv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yongpay.top/Article/details/gtvgiyuose.html

[R80] 查看脚本执行耗时
来源：http://dali.0kj1m.cn/Article/details/gtpevdwqwa.html

time ./run.sh
来源：http://dali.quarkkingdee.top/Article/details/gtjukwuufc.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gthbxhquqn.html

S. C / C++ 专题
来源：http://dali.chenzaomai.com/Article/details/gtaqqkgwdh.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtdekwcnbu.html

[S01] C：Hello World
来源：http://dali.316326.xyz/Article/details/gtasbospej.html

#include <stdio.h>
来源：http://dali.sufxvd.cn/Article/details/gtplumcnos.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cucudq.cn/Article/details/gtzoodzdrx.html

[S02] C：变量与格式化输出
来源：http://dali.havefunace.top/Article/details/gtvjjzcydu.html

int a = 10; printf("%d\n", a);
来源：http://dali.guannengcc.top/Article/details/gtpfqnashc.html

[S03] C：读入整数
来源：http://dali.gaohongyu789.top/Article/details/gtubmwkcly.html

int x; scanf("%d", &x);
来源：http://dali.xuetiantiany.cn/Article/details/gtjeqayhzd.html

[S04] C：字符串复制
来源：http://dali.pengpengdd.cyou/Article/details/gtsjqkulsq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hfpthk.cn/Article/details/gtbwwxredr.html

[S05] C：字符串长度
来源：http://dali.sufxvd.cn/Article/details/gtbgqfcwsx.html

strlen(s)
来源：http://dali.daxiang520.top/Article/details/gthpjvjdgd.html

[S06] C：字符串比较
来源：http://dali.sufxvd.cn/Article/details/gtlextazql.html

strcmp(a, b) == 0
来源：http://dali.havefunace.top/Article/details/gtnckqnlgq.html

[S07] C：数组遍历求和
来源：http://dali.jyoumei.cn/Article/details/gtbjbxharw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.0kj1m.cn/Article/details/gtntvshvnj.html

[S08] C：动态内存分配与释放
来源：http://dali.jqgufenzy.top/Article/details/gtpjhdzxhx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.wangshuangyany.cn/Article/details/gtnjcgktti.html

[S09] C：结构体定义与初始化
来源：http://dali.jlsjyb.cn/Article/details/gtqjcelmlw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gogol.net.cn/Article/details/gtznkputql.html

[S10] C：指针与解引用
来源：http://dali.havefunace.top/Article/details/gtpqqhrycg.html

int *p = &a;  *p = 5;
来源：http://dali.shanyushiyangtech.top/Article/details/gtjsejzoob.html

[S11] C：逐行读文件
来源：http://dali.ybcxt.top/Article/details/gtauuxictn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhoulong.xyz/Article/details/gtvgwtfhru.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yanxiufei.cn/Article/details/gtvwyqgkzv.html

fclose(f);
来源：http://dali.jianghu66.top/Article/details/gtgzyzomcz.html

[S12] C：写文件
来源：http://dali.yueranfly.top/Article/details/gthkipfomx.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yonumen.top/Article/details/gtsuxtzomq.html

[S13] C：宏定义
来源：http://dali.cqqwz.cn/Article/details/gtfxkcaawd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hfpthk.cn/Article/details/gtksmoxxjg.html

[S14] C：枚举
来源：http://dali.shuidangran.top/Article/details/gthvvsffyz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hywenlv.cn/Article/details/gthuosvphc.html

[S15] C：类型转换
来源：http://dali.jiagoushi.top/Article/details/gtvvymzojh.html

(double) a / b
来源：http://dali.gzhubu.top/Article/details/gtlaatshkb.html

[S16] C：位操作置位
来源：http://dali.ppjwa.cn/Article/details/gthosbmwla.html

x |= (1 << 3);
来源：http://dali.hfpthk.cn/Article/details/gtauorfjbo.html

[S17] C：安全拼接字符串
来源：http://dali.daxiang520.top/Article/details/gtjyqnovxg.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cdnleiting.top/Article/details/gttmajztqf.html

[S18] C：命令行参数
来源：http://dali.sxryk.cn/Article/details/gtsszgndxg.html

int main(int argc, char **argv)
来源：http://dali.yonumen.top/Article/details/gtkhvrgdea.html

[S19] C：快速排序
来源：http://dali.gzhubu.top/Article/details/gtvcrhysoi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jqgfzy.top/Article/details/gtlwipkqei.html

[S20] C：二分查找
来源：http://dali.chenjidiqi.icu/Article/details/gtyglgztdv.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gotoacloud.top/Article/details/gtxywkdsjx.html

[S21] C：字符类别判断
来源：http://dali.nanxuanxn.top/Article/details/gtfoyliaau.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sweek.top/Article/details/gtwrtwbuoh.html

[S22] C：字符串转数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfihriglf.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hongshengwenyu.top/Article/details/gtgbkbxwfd.html

[S23] C：随机数
来源：http://dali.shanyushiyangtech.top/Article/details/gtfdiojysq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinqigfzy.top/Article/details/gthlyatqes.html

[S24] C：获取本地时间
来源：http://dali.iojbl.cn/Article/details/gtzpyhmovt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.9152youxi.cn/Article/details/gtotqywncj.html

[S25] C：内存拷贝
来源：http://dali.cdnleiting.top/Article/details/gtceeweupf.html

memcpy(dst, src, n);
来源：http://dali.fzhhl.top/Article/details/gtlbitjlxt.html

[S26] C：内存清零
来源：http://dali.snrcjt.cn/Article/details/gtmqwigyxb.html

memset(a, 0, sizeof a);
来源：http://dali.wangdashe.top/Article/details/gtavwdtczm.html

[S27] C：定义常量
来源：http://dali.ybcxt.top/Article/details/gtgwpzcgvy.html

const double PI = 3.14159;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcpytnxza.html

[S28] C：静态变量
来源：http://dali.jinqigufen.top/Article/details/gtpbgbtpwz.html

static int counter = 0;
来源：http://dali.andypj.xyz/Article/details/gtkcjkieds.html

[S29] C：变参函数
来源：http://dali.jinqigufen.top/Article/details/gtmutolbvx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhengqikj.top/Article/details/gtlplfaorz.html

[S30] C：头文件保护
来源：http://dali.sufxvd.cn/Article/details/gtpmwbigvh.html

#ifndef X_H
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwdtzqoix.html

#define X_H
来源：http://dali.hnxiangtu.top/Article/details/gtgiyaetxy.html

#endif
来源：http://dali.xuetiantiany.cn/Article/details/gtjobxttai.html

[S31] C++：Hello World
来源：http://dali.redwolf501.top/Article/details/gtdpwzhjnd.html

#include <iostream>
来源：http://dali.jiagoushi.top/Article/details/gtxvmcfeaq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sweek.top/Article/details/gtagjsugtt.html

[S32] C++：字符串
来源：http://dali.fengsongda.top/Article/details/gtemaypqxh.html

std::string s = "hi";  s += "!";
来源：http://dali.nanxuanxn.top/Article/details/gtddbqhdtv.html

[S33] C++：vector 增删
来源：http://dali.nanxinkj.top/Article/details/gtriwotong.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yonumen.top/Article/details/gthzwrnevw.html

[S34] C++：遍历 vector
来源：http://dali.vqdsnc.cn/Article/details/gtstpuzlki.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.daria6918.cn/Article/details/gtrcxsjirb.html

[S35] C++：map
来源：http://dali.guannengcc.top/Article/details/gthliaycjs.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gtpnjeuvqh.html

[S36] C++：unordered_map
来源：http://dali.gzhubu.top/Article/details/gtowjovrfq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtqyiglrba.html

[S37] C++：set
来源：http://dali.birdmap.top/Article/details/gtlmrgotll.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gogol.net.cn/Article/details/gtofpdheia.html

[S38] C++：排序
来源：http://dali.cheryme.top/Article/details/gtpdpopivs.html

std::sort(v.begin(), v.end());
来源：http://dali.tian-w.cn/Article/details/gtntlpnqxf.html

[S39] C++：自定义比较器排序
来源：http://dali.zhongyouzk.top/Article/details/gtkrdzdyrh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenlongwang.top/Article/details/gtrjaxndis.html

[S40] C++：查找元素
来源：http://dali.sweek.top/Article/details/gtoztykdlo.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhengqikj.top/Article/details/gttdwlobcy.html

[S41] C++：类与构造函数
来源：http://dali.meibo888.top/Article/details/gtncrevwja.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zdqjudy.top/Article/details/gtmyexzdfu.html

[S42] C++：继承与虚函数
来源：http://dali.shangyingyoupin.top/Article/details/gtnrmeqprv.html

class B : public Base { public: void f() override {} };
来源：http://dali.0kj1m.cn/Article/details/gtogmhwttr.html

[S43] C++：智能指针
来源：http://dali.feifeiyinyue.top/Article/details/gtchjwkflr.html

auto p = std::make_unique<int>(5);
来源：http://dali.nanxinkj.top/Article/details/gtfytpruaw.html

[S44] C++：引用传参
来源：http://dali.jyoumei.cn/Article/details/gtktsanvku.html

void inc(int &x) { ++x; }
来源：http://dali.yj20258.top/Article/details/gtdbajtsfz.html

[S45] C++：lambda
来源：http://dali.bjfxy.top/Article/details/gtcfuxqlky.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.nanxinkj.top/Article/details/gtqxgtegsd.html

[S46] C++：函数模板
来源：http://dali.yueranfly.top/Article/details/gtibfsdpwk.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zdqjudy.top/Article/details/gtylskkugc.html

[S47] C++：结构化绑定遍历
来源：http://dali.cucudq.cn/Article/details/gtosweiagn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shuidangran.top/Article/details/gtfwhdxuje.html

[S48] C++：逐行读文件
来源：http://dali.jianghu66.top/Article/details/gtglpiybyi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ppjwa.cn/Article/details/gtqtvdewfs.html

while (std::getline(in, line)) { }
来源：http://dali.svipenyu.cn/Article/details/gtaxklsvwc.html

[S49] C++：写文件
来源：http://dali.bjfxy.top/Article/details/gteygeweln.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yongpay.top/Article/details/gtqgsdwhon.html

[S50] C++：格式化数字
来源：http://dali.guannengcc.top/Article/details/gtulwlcjgt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gtbiuutpqe.html

[S51] C++：显式类型转换
来源：http://dali.gotoacloud.top/Article/details/gtkfyzjffx.html

static_cast<double>(a) / b
来源：http://dali.birdmap.top/Article/details/gtaozqjfzf.html

[S52] C++：const 与 noexcept
来源：http://dali.sweek.top/Article/details/gtqlvvjmwn.html

int size() const noexcept { return n_; }
来源：http://dali.ybcxt.top/Article/details/gtliftmmcd.html

[S53] C++：移动语义
来源：http://dali.cqqwz.cn/Article/details/gtjvctcnob.html

std::vector<int> w = std::move(v);
来源：http://dali.9152youxi.cn/Article/details/gtfbqtufbn.html

[S54] C++：异常处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtipyualvc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jiagoushi.top/Article/details/gtlriijyld.html

[S55] C++：结构化绑定
来源：http://dali.yueranfly.top/Article/details/gtdrjkxvuh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.birdmap.top/Article/details/gtcgcmxept.html

[S56] C++：optional
来源：http://dali.xinyue.icu/Article/details/gtmcacpcuw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.quarkkingdee.top/Article/details/gtjchbokox.html

[S57] C++：编译期常量
来源：http://dali.hysaishi.cn/Article/details/gtmaeaqczo.html

constexpr int N = 10;
来源：http://dali.xuanzx.com/Article/details/gttuvcyhmv.html

[S58] C++：命名空间
来源：http://dali.yj202588.top/Article/details/gtptigoarw.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhiwuduotai.top/Article/details/gtcacegfuk.html

[S59] C++：静态断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkcopmbwp.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.nwbrower.top/Article/details/gtcmqumjxz.html

[S60] C++：遍历并删除元素
来源：http://dali.gzhubu.top/Article/details/gtufgrurpb.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.316326.xyz/Article/details/gtlmsjptgq.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtawbmgljd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yongpay.top/Article/details/gtcvtfhwgl.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtrkxiefzd.html

[T01] Kotlin：Hello World
来源：http://dali.hysaishi.cn/Article/details/gtxsidacwk.html

println("Hello")
来源：http://dali.zdqjudy.top/Article/details/gtdbyelrge.html

[T02] Kotlin：变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtachrxrot.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yj20258.top/Article/details/gtnxthnjwe.html

[T03] Kotlin：字符串模板
来源：http://dali.shzxlz.cn/Article/details/gttlncycrt.html

"值: $b"
来源：http://dali.nanxinkj.top/Article/details/gtudtnjfwl.html

[T04] Kotlin：空安全
来源：http://dali.birdmap.top/Article/details/gtshszhymb.html

val n: String? = null;  n?.length
来源：http://dali.wangshuangyany.cn/Article/details/gtwgfawjcd.html

[T05] Kotlin：when 表达式
来源：http://dali.gzhubu.top/Article/details/gthpjeztoy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.pengpengdd.cyou/Article/details/gtcsfvxqob.html

[T06] Kotlin：集合映射
来源：http://dali.haohaochexian.top/Article/details/gtsstwsdio.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhengqikj.top/Article/details/gtmnlnoagh.html

[T07] Kotlin：集合过滤
来源：http://dali.daria6918.cn/Article/details/gtzfwxjvqx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sysykeji.top/Article/details/gtziucrmpx.html

[T08] Kotlin：数据类
来源：http://dali.ivvv.top/Article/details/gtiidvrwkx.html

data class User(val name: String, val age: Int)
来源：http://dali.chenzaomai.com/Article/details/gtdznmgewv.html

[T09] Kotlin：扩展函数
来源：http://dali.yangfankeji.com/Article/details/gtrboplbkx.html

fun String.exclaim() = this + "!"
来源：http://dali.wangdashe.top/Article/details/gtnqqkfdzx.html

[T10] Kotlin：默认参数
来源：http://dali.sweek.top/Article/details/gtkasebmst.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.andypj.xyz/Article/details/gtawnqyjdr.html

[T11] Kotlin：协程
来源：http://dali.tian-w.cn/Article/details/gtwrgfjfzl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.9152youxi.cn/Article/details/gtvodgbkid.html

[T12] Kotlin：解构声明
来源：http://dali.dianchejie.cn/Article/details/gtpkohdcbb.html

val (a, b) = Pair(1, 2)
来源：http://dali.dashuyun.cn/Article/details/gtlhbhbraw.html

[T13] Kotlin：只读 Map
来源：http://dali.birdmap.top/Article/details/gtjnnphhvj.html

val m = mapOf("a" to 1)
来源：http://dali.iojbl.cn/Article/details/gtdxhreozs.html

[T14] Kotlin：循环
来源：http://dali.snrcjt.cn/Article/details/gtjjjqkral.html

for (i in 1..10) println(i)
来源：http://dali.quarkkingdee.top/Article/details/gtibvevihj.html

[T15] Kotlin：接口
来源：http://dali.nanxuanxn.top/Article/details/gtcsxhmecr.html

interface Shape { fun area(): Double }
来源：http://dali.zhoulong.xyz/Article/details/gtjumcehvv.html

[T16] Swift：Hello World
来源：http://dali.daxiang520.top/Article/details/gtgxbelmps.html

print("Hello")
来源：http://dali.jinqigufen.top/Article/details/gtzvxniyls.html

[T17] Swift：变量与常量
来源：http://dali.xuanzx.com/Article/details/gtpdfvypun.html

var a = 1;  let b = 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqiawnyuk.html

[T18] Swift：字符串插值
来源：http://dali.xylfe.cn/Article/details/gtoozdssir.html

"值: \(b)"
来源：http://dali.cucudq.cn/Article/details/gtususigkk.html

[T19] Swift：可选绑定
来源：http://dali.hammf.cn/Article/details/gtejceysvm.html

if let n = opt { print(n) }
来源：http://dali.yj20258.top/Article/details/gtnzmgskpb.html

[T20] Swift：数组操作
来源：http://dali.yj20258.top/Article/details/gtqivpluja.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.kuanghao11.cn/Article/details/gtegozkopc.html

[T21] Swift：遍历
来源：http://dali.sysykeji.top/Article/details/gtbkkmrgbw.html

for x in a { print(x) }
来源：http://dali.hnxiangtu.top/Article/details/gtmkklsjmt.html

[T22] Swift：字典
来源：http://dali.hammf.cn/Article/details/gtgdpioxvb.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jinqigufen.top/Article/details/gtqulwzecl.html

[T23] Swift：函数
来源：http://dali.chenlongwang.top/Article/details/gtxjewwofu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zycfv.cn/Article/details/gtsfssfnue.html

[T24] Swift：闭包
来源：http://dali.jyoumei.cn/Article/details/gtwthqxzcy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ybcxt.top/Article/details/gtvlhmajoe.html

[T25] Swift：结构体
来源：http://dali.yvedp.cn/Article/details/gtginkiiug.html

struct P { var x: Int }
来源：http://dali.hywenlv.cn/Article/details/gtttoahuvq.html

[T26] Swift：类与重写
来源：http://dali.yj20258888.top/Article/details/gtlvdrqwnh.html

class A: Base { override func f() {} }
来源：http://dali.jianghu66.top/Article/details/gtxdirobpi.html

[T27] Swift：错误处理
来源：http://dali.tianlin.xyz/Article/details/gtgxqfyaez.html

do { try f() } catch { print(error) }
来源：http://dali.yj20258888.top/Article/details/gttutevcsw.html

[T28] Swift：枚举
来源：http://dali.hammf.cn/Article/details/gtzngqpwds.html

enum Color { case red, green }
来源：http://dali.andypj.xyz/Article/details/gtukdlehem.html

[T29] Swift：guard 提前返回
来源：http://dali.wangshuangyany.cn/Article/details/gtoehmflqm.html

guard let x = opt else { return }
来源：http://dali.yuanzhike.top/Article/details/gthiluwuyi.html

[T30] Swift：协议
来源：http://dali.zycfv.cn/Article/details/gtrpygjfmk.html

protocol Shape { func area() -> Double }
来源：http://dali.kuanghao11.cn/Article/details/gtoyixoood.html

[T31] Lua：Hello World
来源：http://dali.yj20258888.top/Article/details/gtvsmmynsp.html

print("Hello")
来源：http://dali.yuxming.cn/Article/details/gthshdhuga.html

[T32] Lua：局部变量
来源：http://dali.tian-w.cn/Article/details/gtmsyeolqn.html

local a = 1
来源：http://dali.yanxiufei.cn/Article/details/gturktkdlm.html

[T33] Lua：表（数组）
来源：http://dali.cucudq.cn/Article/details/gtlqhqshms.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.wangshuangyany.cn/Article/details/gtvfnbkkrc.html

[T34] Lua：遍历表
来源：http://dali.xuanzx.com/Article/details/gtwzvmazum.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hywenlv.cn/Article/details/gtbzsgzlic.html

[T35] Lua：字典表
来源：http://dali.0kj1m.cn/Article/details/gtpolvlpcz.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhongyouzk.top/Article/details/gtyargduwe.html

[T36] Lua：函数
来源：http://dali.birdmap.top/Article/details/gtpjmavcwh.html

function add(a, b) return a + b end
来源：http://dali.kuanghao11.cn/Article/details/gtawzqkqdx.html

[T37] Lua：字符串拼接
来源：http://dali.hysaishi.cn/Article/details/gtunvujksf.html

"a" .. "b"
来源：http://dali.andypj.xyz/Article/details/gtsqeabsfw.html

[T38] Lua：条件
来源：http://dali.iojbl.cn/Article/details/gtuqwqkvqn.html

if x > 0 then print("正") end
来源：http://dali.cashguo.top/Article/details/gtlwsbowav.html

[T39] Lua：模式匹配
来源：http://dali.guannengcc.top/Article/details/gtcryazpnb.html

string.find(s, "%d+")
来源：http://dali.wangshuangyany.cn/Article/details/gtubdqmhwd.html

[T40] Lua：元表
来源：http://dali.haohaochexian.top/Article/details/gtptujawoo.html

setmetatable({}, { __index = base })
来源：http://dali.sxryk.cn/Article/details/gtelllasfe.html

[T41] Perl：Hello World
来源：http://dali.zhixingplan.top/Article/details/gttlmkojqz.html

print "Hello\n";
来源：http://dali.mhx1999.top/Article/details/gtdaqxddju.html

[T42] Perl：变量类型
来源：http://dali.jinqigufen.top/Article/details/gtnzglpopv.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xinyue.icu/Article/details/gtgxvhwkrz.html

[T43] Perl：字符串插值
来源：http://dali.gzhubu.top/Article/details/gthqvwvlva.html

"值: $a"
来源：http://dali.haohaochexian.top/Article/details/gtrcfbecgc.html

[T44] Perl：条件
来源：http://dali.zhiwuduotai.top/Article/details/gtbyibvvuf.html

if ($a > 0) { print "正"; }
来源：http://dali.smart0.xyz/Article/details/gtwqkjgryu.html

[T45] Perl：数组遍历
来源：http://dali.jlsjyb.cn/Article/details/gtfppctlzu.html

for my $x (@arr) { print $x; }
来源：http://dali.jqgufenzy.top/Article/details/gtuqgzvwaq.html

[T46] Perl：哈希操作
来源：http://dali.chenlongwang.top/Article/details/gtvgddnpel.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.gogol.net.cn/Article/details/gtfbimeznp.html

[T47] Perl：正则捕获
来源：http://dali.0kj1m.cn/Article/details/gteuadqajy.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.havefunace.top/Article/details/gtjlebuigv.html

[T48] Perl：正则替换
来源：http://dali.xinyue.icu/Article/details/gtafgyfbqr.html

$s =~ s/old/new/g;
来源：http://dali.meibo888.top/Article/details/gtaypsimhp.html


<!-- 参考信息 -->