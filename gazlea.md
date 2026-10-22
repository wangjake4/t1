代发 wailian999

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.haohaochexian.top/Article/details/gt2ifqbrypk.html

[R50] awk 求和
来源：http://dali.guannengcc.top/Article/details/gt2pbwdpmcf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.tian-w.cn/Article/details/gt2jjviwgsi.html

[R51] 排序去重取前几
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hsbmossz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhiwuduotai.top/Article/details/gt2qovzkvbl.html

[R52] 统计行数
来源：http://dali.yueranfly.top/Article/details/gt2rrcpijwq.html

wc -l a.txt
来源：http://dali.jinqigfzy.top/Article/details/gt2bomwxcpt.html

[R53] 查看文件头与实时尾
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2aibhrrrm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cfixlzxs.html

[R54] 比较两个文件
来源：http://dali.jiagoushi.top/Article/details/gt2kcqoeijn.html

diff a.txt b.txt
来源：http://dali.gzhubu.top/Article/details/gt2dgumxzfl.html

[R55] 压缩与解压
来源：http://dali.gaohongyu789.top/Article/details/gt2nhzzwyyv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.aizwys.cn/Article/details/gt2gpkrklvv.html

[R56] 远程拷贝
来源：http://dali.yj20258888.top/Article/details/gt2gprfghue.html

scp file user@host:/path/
来源：http://dali.yanxiufei.cn/Article/details/gt2uyoiadia.html

[R57] 远程执行命令
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2unoxfnjx.html

ssh user@host 'uptime'
来源：http://dali.hammf.cn/Article/details/gt2rvwjbdba.html

[R58] 下载文件
来源：http://dali.quarkkingdee.top/Article/details/gt2wqhidljf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.kuanghao11.cn/Article/details/gt2trtfafge.html

[R59] 发 POST JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bnthwcia.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.birdmap.top/Article/details/gt2ljfypzsp.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhiwuduotai.top/Article/details/gt2mqeaeyxf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hfpthk.cn/Article/details/gt2znguauwg.html

[R61] 磁盘占用
来源：http://dali.9152youxi.cn/Article/details/gt2qhoerjhu.html

df -h;  du -sh *
来源：http://dali.hysaishi.cn/Article/details/gt2vbnhsbal.html

[R62] 找最占空间的文件
来源：http://dali.haohaochexian.top/Article/details/gt2ljpuhscp.html

du -ah . | sort -rh | head -10
来源：http://dali.redwolf501.top/Article/details/gt2mvelswfx.html

[R63] 内存与进程
来源：http://dali.jqgufenzy.top/Article/details/gt2eksmhixc.html

free -h;  ps aux | grep nginx
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ydxxqiyi.html

[R64] 结束进程
来源：http://dali.kuanghao11.cn/Article/details/gt2jnsnbrvk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shangyingyoupin.top/Article/details/gt2wnhtyuxc.html

[R65] 查看端口占用
来源：http://dali.xuanzx.com/Article/details/gt2oglsmqyz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.iojbl.cn/Article/details/gt2zkbfclkz.html

[R66] 定时任务
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ursuqgoc.html

crontab -e;  crontab -l
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pjoatydz.html

[R67] 生成随机十六进制串
来源：http://dali.quarkkingdee.top/Article/details/gt2fpewafpp.html

openssl rand -hex 16
来源：http://dali.yj20258888.top/Article/details/gt2fnhxnscm.html

[R68] 计算文件校验值
来源：http://dali.chenjidiqi.icu/Article/details/gt2ygiwtpsd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hysaishi.cn/Article/details/gt2mzslryvb.html

[R69] 生成随机密码
来源：http://dali.nanxinkj.top/Article/details/gt2fuwxiosq.html

head -c 16 /dev/urandom | base64
来源：http://dali.yanxiufei.cn/Article/details/gt2atooucxw.html

[R70] 时间戳与互转
来源：http://dali.haohaochexian.top/Article/details/gt2twhqqdqx.html

date +%s;  date -d @1700000000
来源：http://dali.zdqjudy.top/Article/details/gt2frdhkllo.html

[R71] 日期格式化
来源：http://dali.hongshengwenyu.top/Article/details/gt2cxfwddms.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.haohaochexian.top/Article/details/gt2qxppngfr.html

[R72] 等待端口就绪
来源：http://dali.jlsjyb.cn/Article/details/gt2rvhlhxnz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.aizwys.cn/Article/details/gt2auoluoam.html

[R73] 分割大日志
来源：http://dali.hongshengwenyu.top/Article/details/gt2ztxlqntr.html

split -l 1000 big.log part_
来源：http://dali.sweek.top/Article/details/gt2ycvyicxn.html

[R74] 批量重命名
来源：http://dali.zhiwuduotai.top/Article/details/gt2yusjyqvz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yangfankeji.com/Article/details/gt2bukwkdjh.html

[R75] 导出环境变量
来源：http://dali.ivvv.top/Article/details/gt2ehwetmgi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.iojbl.cn/Article/details/gt2rmulnlqo.html

[R76] 使用临时文件
来源：http://dali.jinqigfzy.top/Article/details/gt2efwdrsrh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhongyouzk.top/Article/details/gt2esvtthdl.html

[R77] 读取用户输入
来源：http://dali.nwbrower.top/Article/details/gt2tvcgeaiv.html

read -rp "请输入: " ans
来源：http://dali.nanxuanxn.top/Article/details/gt2qxpnxabb.html

[R78] 交互式菜单
来源：http://dali.yj202588.top/Article/details/gt2rurwgpzj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jiagoushi.top/Article/details/gt2swevufmq.html

[R79] 解析命令行选项
来源：http://dali.zhengqikj.top/Article/details/gt2ezcnkxim.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ppjwa.cn/Article/details/gt2amnmmdxf.html

[R80] 查看脚本执行耗时
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rvsnwnvr.html

time ./run.sh
来源：http://dali.shzxlz.cn/Article/details/gt2vnuopmwr.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2mjejyfmt.html

S. C / C++ 专题
来源：http://dali.zhoulong.xyz/Article/details/gt2nxxkaosj.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2mxuurxqt.html

[S01] C：Hello World
来源：http://dali.redwolf501.top/Article/details/gt2pijzdlux.html

#include <stdio.h>
来源：http://dali.sxryk.cn/Article/details/gt2qnktxyeg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zycfv.cn/Article/details/gt2dibxslli.html

[S02] C：变量与格式化输出
来源：http://dali.jqgfzy.top/Article/details/gt2omibhedy.html

int a = 10; printf("%d\n", a);
来源：http://dali.smart0.xyz/Article/details/gt2sqkypobz.html

[S03] C：读入整数
来源：http://dali.cheryme.top/Article/details/gt2xfzsbrnx.html

int x; scanf("%d", &x);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jwyrhsgs.html

[S04] C：字符串复制
来源：http://dali.jyoumei.cn/Article/details/gt2wktvzebt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gogol.net.cn/Article/details/gt2kcsziwza.html

[S05] C：字符串长度
来源：http://dali.fengsongda.top/Article/details/gt2kyskyrbv.html

strlen(s)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fclnplit.html

[S06] C：字符串比较
来源：http://dali.haohaochexian.top/Article/details/gt2ajoyspbr.html

strcmp(a, b) == 0
来源：http://dali.zhixingplan.top/Article/details/gt2tkhkuzkf.html

[S07] C：数组遍历求和
来源：http://dali.yonumen.top/Article/details/gt2crcrsuaj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jianghu66.top/Article/details/gt2ysjjnoup.html

[S08] C：动态内存分配与释放
来源：http://dali.bjfxy.top/Article/details/gt2sokbcqoi.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ivvv.top/Article/details/gt2lkglnetl.html

[S09] C：结构体定义与初始化
来源：http://dali.jqgfzy.top/Article/details/gt2ypuoamct.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhoulong.xyz/Article/details/gt2xmsnoqfv.html

[S10] C：指针与解引用
来源：http://dali.gotoacloud.top/Article/details/gt2sbwcozrx.html

int *p = &a;  *p = 5;
来源：http://dali.yj202588.top/Article/details/gt2latrzgiz.html

[S11] C：逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uwpkydyg.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xziqi.cn/Article/details/gt2burlsmnb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.feifeiyinyue.top/Article/details/gt2oqlfbpba.html

fclose(f);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2byafmyhu.html

[S12] C：写文件
来源：http://dali.cheryme.top/Article/details/gt2qkwofsoc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xuetiantiany.cn/Article/details/gt2uplcobzr.html

[S13] C：宏定义
来源：http://dali.0kj1m.cn/Article/details/gt2etywvtug.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nqgfvqbr.html

[S14] C：枚举
来源：http://dali.zhoulong.xyz/Article/details/gt2ieoelbvd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hnxiangtu.top/Article/details/gt2uaqqeudl.html

[S15] C：类型转换
来源：http://dali.ivvv.top/Article/details/gt2lhcsmgzq.html

(double) a / b
来源：http://dali.jinqigufen.top/Article/details/gt2pjyoziuv.html

[S16] C：位操作置位
来源：http://dali.zhongyouzk.top/Article/details/gt2wlnmypfb.html

x |= (1 << 3);
来源：http://dali.xinyue.icu/Article/details/gt2bprfjijz.html

[S17] C：安全拼接字符串
来源：http://dali.cashguo.top/Article/details/gt2dhliyiek.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2xaydypkc.html

[S18] C：命令行参数
来源：http://dali.9152youxi.cn/Article/details/gt2gfhripzd.html

int main(int argc, char **argv)
来源：http://dali.tianlin.xyz/Article/details/gt2fyautyre.html

[S19] C：快速排序
来源：http://dali.svipenyu.cn/Article/details/gt2gliasbgl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gt2xxnvndls.html

[S20] C：二分查找
来源：http://dali.sxryk.cn/Article/details/gt2nofqngbd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.haohaochexian.top/Article/details/gt2mcrejlww.html

[S21] C：字符类别判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2nktuwnnw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yuxming.cn/Article/details/gt2ngqdujzf.html

[S22] C：字符串转数字
来源：http://dali.havefunace.top/Article/details/gt2wwcaxkac.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jinqigfzy.top/Article/details/gt2omlvtflt.html

[S23] C：随机数
来源：http://dali.smart0.xyz/Article/details/gt2ijpcxdcf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.vqdsnc.cn/Article/details/gt2zavedvau.html

[S24] C：获取本地时间
来源：http://dali.hongshengwenyu.top/Article/details/gt2qxquseiq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cqqwz.cn/Article/details/gt2ntrzkfhh.html

[S25] C：内存拷贝
来源：http://dali.fengsongda.top/Article/details/gt2wxlcxqvg.html

memcpy(dst, src, n);
来源：http://dali.cheryme.top/Article/details/gt2cajonnyf.html

[S26] C：内存清零
来源：http://dali.jinghuilouyu.cn/Article/details/gt2msqkpyfe.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2phzlcjsp.html

[S27] C：定义常量
来源：http://dali.ehwqpu.com/Article/details/gt2ufhvgcon.html

const double PI = 3.14159;
来源：http://dali.ppjwa.cn/Article/details/gt2fmikhobm.html

[S28] C：静态变量
来源：http://dali.hammf.cn/Article/details/gt2ygdhbqhi.html

static int counter = 0;
来源：http://dali.yj20258.top/Article/details/gt2eypsvifg.html

[S29] C：变参函数
来源：http://dali.jqgfzy.top/Article/details/gt2lxzxdprv.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2pipjuzcq.html

[S30] C：头文件保护
来源：http://dali.yvedp.cn/Article/details/gt2gmhopvdh.html

#ifndef X_H
来源：http://dali.yuxming.cn/Article/details/gt2zttbpjnf.html

#define X_H
来源：http://dali.xuanzx.com/Article/details/gt2unfijnju.html

#endif
来源：http://dali.316326.xyz/Article/details/gt2uleelmuk.html

[S31] C++：Hello World
来源：http://dali.zdqjudy.top/Article/details/gt2idzjgchw.html

#include <iostream>
来源：http://dali.ivvv.top/Article/details/gt2ntnqpgnz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yueranfly.top/Article/details/gt2znswpkmz.html

[S32] C++：字符串
来源：http://dali.cqqwz.cn/Article/details/gt2hgrgjikv.html

std::string s = "hi";  s += "!";
来源：http://dali.dashuyun.cn/Article/details/gt2oemqmqvn.html

[S33] C++：vector 增删
来源：http://dali.xuanzx.com/Article/details/gt2wsmivrer.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jlsjyb.cn/Article/details/gt2inrekchu.html

[S34] C++：遍历 vector
来源：http://dali.jqgfzy.top/Article/details/gt2vtgrorjd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.meibo888.top/Article/details/gt2gtyylqkx.html

[S35] C++：map
来源：http://dali.yanxiufei.cn/Article/details/gt2qehavfiu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nwbrower.top/Article/details/gt2odcrwgyl.html

[S36] C++：unordered_map
来源：http://dali.gogol.net.cn/Article/details/gt2npapadvq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hnqzz.top/Article/details/gt2kohgmove.html

[S37] C++：set
来源：http://dali.chenzaomai.com/Article/details/gt2ykgzymlk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jinqigfzy.top/Article/details/gt2rzpyiaec.html

[S38] C++：排序
来源：http://dali.shzxlz.cn/Article/details/gt2tmzhbnkw.html

std::sort(v.begin(), v.end());
来源：http://dali.ehwqpu.com/Article/details/gt2osvnocgp.html

[S39] C++：自定义比较器排序
来源：http://dali.gogol.net.cn/Article/details/gt2wfymulgr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cqqwz.cn/Article/details/gt2wclpxxdn.html

[S40] C++：查找元素
来源：http://dali.zdqjudy.top/Article/details/gt2aessjfhi.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gotoacloud.top/Article/details/gt2hmgjisxy.html

[S41] C++：类与构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2fieaxtmg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.chenjidiqi.icu/Article/details/gt2lmwuwiog.html

[S42] C++：继承与虚函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2sxhpiedj.html

class B : public Base { public: void f() override {} };
来源：http://dali.pycfn.com/Article/details/gt2pntrgebq.html

[S43] C++：智能指针
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2djzkbrad.html

auto p = std::make_unique<int>(5);
来源：http://dali.haohaochexian.top/Article/details/gt2vqsvrcjt.html

[S44] C++：引用传参
来源：http://dali.jqgufenzy.top/Article/details/gt2japddjax.html

void inc(int &x) { ++x; }
来源：http://dali.shzxlz.cn/Article/details/gt2locxykxg.html

[S45] C++：lambda
来源：http://dali.guowangkeji.top/Article/details/gt2xslayxvj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.c1oappe.top/Article/details/gt2vrzrhbyj.html

[S46] C++：函数模板
来源：http://dali.feifeiyinyue.top/Article/details/gt2muuhklot.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhiwuduotai.top/Article/details/gt2quvmtmmd.html

[S47] C++：结构化绑定遍历
来源：http://dali.nanxuanxn.top/Article/details/gt2ctujaule.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gotoacloud.top/Article/details/gt2rvovltms.html

[S48] C++：逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gt2sktsicgi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cqqwz.cn/Article/details/gt2jqwmwqrk.html

while (std::getline(in, line)) { }
来源：http://dali.wangdashe.top/Article/details/gt2congxwjn.html

[S49] C++：写文件
来源：http://dali.tian-w.cn/Article/details/gt2lwpeclfi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.pycfn.com/Article/details/gt2lfplfhbw.html

[S50] C++：格式化数字
来源：http://dali.zhengqikj.top/Article/details/gt2enwhdaox.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gt2ynhmejde.html

[S51] C++：显式类型转换
来源：http://dali.hammf.cn/Article/details/gt2pqnsqsty.html

static_cast<double>(a) / b
来源：http://dali.sysykeji.top/Article/details/gt2mskbibah.html

[S52] C++：const 与 noexcept
来源：http://dali.yangfankeji.com/Article/details/gt2joiproey.html

int size() const noexcept { return n_; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tfftinpg.html

[S53] C++：移动语义
来源：http://dali.birdmap.top/Article/details/gt2ovecxpcx.html

std::vector<int> w = std::move(v);
来源：http://dali.sufxvd.cn/Article/details/gt2vbqfxxnj.html

[S54] C++：异常处理
来源：http://dali.yj202588.top/Article/details/gt2yibwtkgm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xuanzx.com/Article/details/gt2qdabesvq.html

[S55] C++：结构化绑定
来源：http://dali.wangdashe.top/Article/details/gt2tjlpyfxl.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.fzhhl.top/Article/details/gt2fffvpwsk.html

[S56] C++：optional
来源：http://dali.jlsjyb.cn/Article/details/gt2snfbjdwg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yueranfly.top/Article/details/gt2hmbgxupx.html

[S57] C++：编译期常量
来源：http://dali.shzxlz.cn/Article/details/gt2clnzavaf.html

constexpr int N = 10;
来源：http://dali.hammf.cn/Article/details/gt2spaogywk.html

[S58] C++：命名空间
来源：http://dali.yueranfly.top/Article/details/gt2vnzcvzfr.html

namespace ns { int f() { return 1; } }
来源：http://dali.tian-w.cn/Article/details/gt2dnnmvxgh.html

[S59] C++：静态断言
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ljbecssb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.tianlin.xyz/Article/details/gt2mqqopsog.html

[S60] C++：遍历并删除元素
来源：http://dali.sufxvd.cn/Article/details/gt2jdjpfgui.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cucudq.cn/Article/details/gt2jtacciiy.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gt2srfdtdfm.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jiagoushi.top/Article/details/gt2uinkdlxe.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2ozqoygqm.html

[T01] Kotlin：Hello World
来源：http://dali.yvedp.cn/Article/details/gt2ilaidleo.html

println("Hello")
来源：http://dali.tian-w.cn/Article/details/gt2igrvzkcf.html

[T02] Kotlin：变量
来源：http://dali.daxiang520.top/Article/details/gt2gheljsym.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yongpay.top/Article/details/gt2acqekyow.html

[T03] Kotlin：字符串模板
来源：http://dali.shanyushiyangtech.top/Article/details/gt2uxpekorc.html

"值: $b"
来源：http://dali.ydzc1.top/Article/details/gt2bdkfpova.html

[T04] Kotlin：空安全
来源：http://dali.daxiang520.top/Article/details/gt2ryvelqxj.html

val n: String? = null;  n?.length
来源：http://dali.fzhhl.top/Article/details/gt2hxdgpcvq.html

[T05] Kotlin：when 表达式
来源：http://dali.meibo888.top/Article/details/gt2ewyeiczt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sweek.top/Article/details/gt2ikpkzgvn.html

[T06] Kotlin：集合映射
来源：http://dali.hywenlv.cn/Article/details/gt2sxzbaekr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.redwolf501.top/Article/details/gt2whsmurqi.html

[T07] Kotlin：集合过滤
来源：http://dali.ivvv.top/Article/details/gt2cqdkyfkf.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gotoacloud.top/Article/details/gt2gjrtcwcv.html

[T08] Kotlin：数据类
来源：http://dali.hywenlv.cn/Article/details/gt2ffajbchk.html

data class User(val name: String, val age: Int)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2viulkxcb.html

[T09] Kotlin：扩展函数
来源：http://dali.yuxming.cn/Article/details/gt2chuvjuwb.html

fun String.exclaim() = this + "!"
来源：http://dali.gzhubu.top/Article/details/gt2pwrgufgw.html

[T10] Kotlin：默认参数
来源：http://dali.nanxinkj.top/Article/details/gt2hexlbwic.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.aibaodan.cn/Article/details/gt2kwqborqy.html

[T11] Kotlin：协程
来源：http://dali.gzhubu.top/Article/details/gt2lupcufch.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.yangfankeji.com/Article/details/gt2ifbpxrgy.html

[T12] Kotlin：解构声明
来源：http://dali.guowangkeji.top/Article/details/gt2unpyyojl.html

val (a, b) = Pair(1, 2)
来源：http://dali.jqgfzy.top/Article/details/gt2ynsumgux.html

[T13] Kotlin：只读 Map
来源：http://dali.nanxinkj.top/Article/details/gt2jpgeqhox.html

val m = mapOf("a" to 1)
来源：http://dali.jqgfzy.top/Article/details/gt2lkjultgx.html

[T14] Kotlin：循环
来源：http://dali.dashuyun.cn/Article/details/gt2dkuunddz.html

for (i in 1..10) println(i)
来源：http://dali.svipenyu.cn/Article/details/gt2jrzdazzn.html

[T15] Kotlin：接口
来源：http://dali.gogol.net.cn/Article/details/gt2vrbjgfom.html

interface Shape { fun area(): Double }
来源：http://dali.redwolf501.top/Article/details/gt2zjqlovwd.html

[T16] Swift：Hello World
来源：http://dali.aibaodan.cn/Article/details/gt2gxklhnos.html

print("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gt2bwmlbrih.html

[T17] Swift：变量与常量
来源：http://dali.jyoumei.cn/Article/details/gt2fsgpemxx.html

var a = 1;  let b = 2
来源：http://dali.bjfxy.top/Article/details/gt2geknnxuo.html

[T18] Swift：字符串插值
来源：http://dali.shuidangran.top/Article/details/gt2aevkdbnr.html

"值: \(b)"
来源：http://dali.fzhhl.top/Article/details/gt2sdsmockp.html

[T19] Swift：可选绑定
来源：http://dali.tian-w.cn/Article/details/gt2vjswipmf.html

if let n = opt { print(n) }
来源：http://dali.feifeiyinyue.top/Article/details/gt2fhwtrecv.html

[T20] Swift：数组操作
来源：http://dali.jqgufenzy.top/Article/details/gt2xjreruel.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.mhx1999.top/Article/details/gt2avamygoa.html

[T21] Swift：遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2bhiybnvb.html

for x in a { print(x) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2hlgcmtbh.html

[T22] Swift：字典
来源：http://dali.jqgufenzy.top/Article/details/gt2cmynychy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.redwolf501.top/Article/details/gt2vhuaxocc.html

[T23] Swift：函数
来源：http://dali.dashuyun.cn/Article/details/gt2sikhgfpk.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.9152youxi.cn/Article/details/gt2ezdepppk.html

[T24] Swift：闭包
来源：http://dali.daria6918.cn/Article/details/gt2vuoxemtb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hnqzz.top/Article/details/gt2pyrbvzwy.html

[T25] Swift：结构体
来源：http://dali.cqqwz.cn/Article/details/gt2ubvjvhib.html

struct P { var x: Int }
来源：http://dali.iojbl.cn/Article/details/gt2pjmsizgc.html

[T26] Swift：类与重写
来源：http://dali.sysykeji.top/Article/details/gt2cpjeueab.html

class A: Base { override func f() {} }
来源：http://dali.cheryme.top/Article/details/gt2homichly.html

[T27] Swift：错误处理
来源：http://dali.xuanzx.com/Article/details/gt2mlrmlfsj.html

do { try f() } catch { print(error) }
来源：http://dali.shuidangran.top/Article/details/gt2fgcjovgs.html

[T28] Swift：枚举
来源：http://dali.gzhubu.top/Article/details/gt2udntebxt.html

enum Color { case red, green }
来源：http://dali.tanke756.top/Article/details/gt2atqutxgn.html

[T29] Swift：guard 提前返回
来源：http://dali.ydzc1.top/Article/details/gt2scwhgnnq.html

guard let x = opt else { return }
来源：http://dali.xuanzx.com/Article/details/gt2kdixnhcz.html

[T30] Swift：协议
来源：http://dali.iojbl.cn/Article/details/gt2wrklahnq.html

protocol Shape { func area() -> Double }
来源：http://dali.svipenyu.cn/Article/details/gt2zmkbxcwv.html

[T31] Lua：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cztsvadj.html

print("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gt2zsdybgkf.html

[T32] Lua：局部变量
来源：http://dali.kuanghao11.cn/Article/details/gt2nbjvwcag.html

local a = 1
来源：http://dali.hnxiangtu.top/Article/details/gt2bdjybqns.html

[T33] Lua：表（数组）
来源：http://dali.andypj.xyz/Article/details/gt2kghtpfnm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.ehwqpu.com/Article/details/gt2yfbidewx.html

[T34] Lua：遍历表
来源：http://dali.pengpengdd.cyou/Article/details/gt2kxesnbhy.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.aizwys.cn/Article/details/gt2nwrjxjgq.html

[T35] Lua：字典表
来源：http://dali.zhongyouzk.top/Article/details/gt2eizwcskj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shangyingyoupin.top/Article/details/gt2zymgxtgt.html

[T36] Lua：函数
来源：http://dali.yj20258888.top/Article/details/gt2nfgnmbwt.html

function add(a, b) return a + b end
来源：http://dali.yongpay.top/Article/details/gt2dktxsaku.html

[T37] Lua：字符串拼接
来源：http://dali.xziqi.cn/Article/details/gt2jjcmcxwl.html

"a" .. "b"
来源：http://dali.dashuyun.cn/Article/details/gt2texsczwc.html

[T38] Lua：条件
来源：http://dali.xuanzx.com/Article/details/gt2iucnilwx.html

if x > 0 then print("正") end
来源：http://dali.c1oappe.top/Article/details/gt2usvlmaqs.html

[T39] Lua：模式匹配
来源：http://dali.yuxming.cn/Article/details/gt2uyrxiqfp.html

string.find(s, "%d+")
来源：http://dali.cucudq.cn/Article/details/gt2yhfxvvfa.html

[T40] Lua：元表
来源：http://dali.kuanghao11.cn/Article/details/gt2awpinppk.html

setmetatable({}, { __index = base })
来源：http://dali.vqdsnc.cn/Article/details/gt2szlrmyor.html

[T41] Perl：Hello World
来源：http://dali.gaohongyu789.top/Article/details/gt2xeuybyfy.html

print "Hello\n";
来源：http://dali.ppjwa.cn/Article/details/gt2puhnltng.html

[T42] Perl：变量类型
来源：http://dali.yonumen.top/Article/details/gt2lgctfqte.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.chenzaomai.com/Article/details/gt2aydhceth.html

[T43] Perl：字符串插值
来源：http://dali.svipenyu.cn/Article/details/gt2gkheeiqy.html

"值: $a"
来源：http://dali.gogol.net.cn/Article/details/gt2ewsvyikl.html

[T44] Perl：条件
来源：http://dali.bjfxy.top/Article/details/gt2ukcquwek.html

if ($a > 0) { print "正"; }
来源：http://dali.ppjwa.cn/Article/details/gt2ibtmptso.html

[T45] Perl：数组遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hleyqvhx.html

for my $x (@arr) { print $x; }
来源：http://dali.yongpay.top/Article/details/gt2vrldyjik.html

[T46] Perl：哈希操作
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rvdsfhrz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.xziqi.cn/Article/details/gt2mympcctj.html

[T47] Perl：正则捕获
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2pdphoknj.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.kuanghao11.cn/Article/details/gt2mzrqetdw.html

[T48] Perl：正则替换
来源：http://dali.yuxming.cn/Article/details/gt2uzdetykk.html

$s =~ s/old/new/g;
来源：http://dali.tianlin.xyz/Article/details/gt2ntjpykxk.html

[T49] Perl：函数
来源：http://dali.cucudq.cn/Article/details/gt2odtknixf.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.sweek.top/Article/details/gt2ejknhmha.html

[T50] Perl：逐行读文件
来源：http://dali.bjfxy.top/Article/details/gt2hucxexrh.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.redwolf501.top/Article/details/gt2wuxnzhom.html

while (my $line = <$fh>) { print $line; }
来源：http://dali.yongpay.top/Article/details/gt2ufxcoqin.html

[T51] Scala：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2rvkztkqm.html

println("Hello")
来源：http://dali.chenzaomai.com/Article/details/gt2pvuavzfs.html

[T52] Scala：变量
来源：http://dali.pengpengdd.cyou/Article/details/gt2xizlvwik.html


<!-- 参考信息 -->