代发 wailian999

find . -name "*.log" -type f
来源：http://dali.dianchejie.cn/Article/details/gtbpmrdqjk.html

[R44] 按修改时间查找
来源：http://dali.shanyushiyangtech.top/Article/details/gteitntsvf.html

find . -mtime -7 -type f
来源：http://dali.sxryk.cn/Article/details/gtnelbavcz.html

[R45] 批量删除
来源：http://dali.cucudq.cn/Article/details/gtarzooisv.html

find . -name "*.tmp" -delete
来源：http://dali.dianchejie.cn/Article/details/gtvofrtvne.html

[R46] 递归替换文件内容
来源：http://dali.hnxiangtu.top/Article/details/gtdqldxygj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hfpthk.cn/Article/details/gthcnagnbn.html

[R47] sed 单行替换
来源：http://dali.ppjwa.cn/Article/details/gtbxengaql.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shuidangran.top/Article/details/gtdsawngcr.html

[R48] awk 取指定列
来源：http://dali.zhengqikj.top/Article/details/gteddhfasy.html

awk '{print $1, $3}' a.txt
来源：http://dali.svipenyu.cn/Article/details/gtnaftnhhz.html

[R49] awk 带条件
来源：http://dali.havefunace.top/Article/details/gtpcepumvm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.fengsongda.top/Article/details/gtyvhjothc.html

[R50] awk 求和
来源：http://dali.yuanzhike.top/Article/details/gtelvlfgiv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtagkvrbim.html

[R51] 排序去重取前几
来源：http://dali.nwbrower.top/Article/details/gtrhmeaoxn.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinyuanbaomall.cn/Article/details/gthchczqfv.html

[R52] 统计行数
来源：http://dali.jiagoushi.top/Article/details/gtetbynfnj.html

wc -l a.txt
来源：http://dali.tianlin.xyz/Article/details/gtbulthesy.html

[R53] 查看文件头与实时尾
来源：http://dali.tanke756.top/Article/details/gtcftffkre.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hywenlv.cn/Article/details/gtoplvbuav.html

[R54] 比较两个文件
来源：http://dali.gotoacloud.top/Article/details/gtdakeymxq.html

diff a.txt b.txt
来源：http://dali.guowangkeji.top/Article/details/gtiwxpnnbq.html

[R55] 压缩与解压
来源：http://dali.shuidangran.top/Article/details/gtfcrkldkz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hongshengwenyu.top/Article/details/gtqlzddnrx.html

[R56] 远程拷贝
来源：http://dali.yj20258888.top/Article/details/gtxyliujjc.html

scp file user@host:/path/
来源：http://dali.hongshengwenyu.top/Article/details/gtuyfpdfuh.html

[R57] 远程执行命令
来源：http://dali.yueranfly.top/Article/details/gtfsjhbpil.html

ssh user@host 'uptime'
来源：http://dali.aibaodan.cn/Article/details/gtbgsipqts.html

[R58] 下载文件
来源：http://dali.gzhubu.top/Article/details/gttcxqdmhw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.c1oappe.top/Article/details/gtiotgmxeb.html

[R59] 发 POST JSON
来源：http://dali.redwolf501.top/Article/details/gtlcaqrcbz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shangyingyoupin.top/Article/details/gtyammzbdm.html

[R60] 只看 HTTP 状态码
来源：http://dali.hnqzz.top/Article/details/gtmvcihxag.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shzxlz.cn/Article/details/gtgswvwfyj.html

[R61] 磁盘占用
来源：http://dali.gogol.net.cn/Article/details/gtyesvyinj.html

df -h;  du -sh *
来源：http://dali.daxiang520.top/Article/details/gtoiewodae.html

[R62] 找最占空间的文件
来源：http://dali.feifeiyinyue.top/Article/details/gtubnnchfr.html

du -ah . | sort -rh | head -10
来源：http://dali.zhengqikj.top/Article/details/gtkeplebsd.html

[R63] 内存与进程
来源：http://dali.yanxiufei.cn/Article/details/gtheemotdi.html

free -h;  ps aux | grep nginx
来源：http://dali.c1oappe.top/Article/details/gtujaitlun.html

[R64] 结束进程
来源：http://dali.c1oappe.top/Article/details/gtocbgwtbg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.chenzaomai.com/Article/details/gthogarevk.html

[R65] 查看端口占用
来源：http://dali.guowangkeji.top/Article/details/gtnmmimpdu.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.nanxuanxn.top/Article/details/gtrqyqhpvm.html

[R66] 定时任务
来源：http://dali.yueranfly.top/Article/details/gtwmnfgqvv.html

crontab -e;  crontab -l
来源：http://dali.fengsongda.top/Article/details/gtrmfilfrc.html

[R67] 生成随机十六进制串
来源：http://dali.c1oappe.top/Article/details/gtutucxkdf.html

openssl rand -hex 16
来源：http://dali.tanke756.top/Article/details/gtrxbefazl.html

[R68] 计算文件校验值
来源：http://dali.aibaodan.cn/Article/details/gtmlzjojdo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtelpgkrjq.html

[R69] 生成随机密码
来源：http://dali.haohaochexian.top/Article/details/gtfgymadvr.html

head -c 16 /dev/urandom | base64
来源：http://dali.ehwqpu.com/Article/details/gthmedarej.html

[R70] 时间戳与互转
来源：http://dali.smart0.xyz/Article/details/gtaascnqxn.html

date +%s;  date -d @1700000000
来源：http://dali.hnqzz.top/Article/details/gtgrpfootb.html

[R71] 日期格式化
来源：http://dali.hfpthk.cn/Article/details/gtbqipmmgp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhongyouzk.top/Article/details/gtovuykgjh.html

[R72] 等待端口就绪
来源：http://dali.yj20258.top/Article/details/gtjzzfifvv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj20258888.top/Article/details/gtbvogwbqw.html

[R73] 分割大日志
来源：http://dali.guowangkeji.top/Article/details/gtfrfnswmd.html

split -l 1000 big.log part_
来源：http://dali.chenzaomai.com/Article/details/gtfyokpbtu.html

[R74] 批量重命名
来源：http://dali.jinghuilouyu.cn/Article/details/gtulzeqola.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zycfv.cn/Article/details/gtugykqeun.html

[R75] 导出环境变量
来源：http://dali.ybcxt.top/Article/details/gtrewabxzg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ppjwa.cn/Article/details/gtgmbjeuzc.html

[R76] 使用临时文件
来源：http://dali.jyoumei.cn/Article/details/gtyukflqln.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hysaishi.cn/Article/details/gtggguqnvn.html

[R77] 读取用户输入
来源：http://dali.xziqi.cn/Article/details/gtrfcsusba.html

read -rp "请输入: " ans
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzfekcmqb.html

[R78] 交互式菜单
来源：http://dali.gogol.net.cn/Article/details/gtvbjdovnc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hfpthk.cn/Article/details/gtmvqikski.html

[R79] 解析命令行选项
来源：http://dali.hfpthk.cn/Article/details/gtkgpdhtbl.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.hongshengwenyu.top/Article/details/gtgmujwczt.html

[R80] 查看脚本执行耗时
来源：http://dali.yvedp.cn/Article/details/gtsgsbyvhm.html

time ./run.sh
来源：http://dali.hysaishi.cn/Article/details/gtmbklfhmg.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtazbdvoae.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gtpmaezolu.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtpacbgknv.html

[S01] C：Hello World
来源：http://dali.mhx1999.top/Article/details/gtskpjerno.html

#include <stdio.h>
来源：http://dali.yongpay.top/Article/details/gtfrotdtpd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cdnleiting.top/Article/details/gtjjzsdamv.html

[S02] C：变量与格式化输出
来源：http://dali.daxiang520.top/Article/details/gtxbvzqdci.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinqigfzy.top/Article/details/gtaueosvan.html

[S03] C：读入整数
来源：http://dali.sysykeji.top/Article/details/gtnoijoopr.html

int x; scanf("%d", &x);
来源：http://dali.gotoacloud.top/Article/details/gtvydiczhg.html

[S04] C：字符串复制
来源：http://dali.zhongyouzk.top/Article/details/gtzbfgwgxx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.svipenyu.cn/Article/details/gtntzjwgve.html

[S05] C：字符串长度
来源：http://dali.ybcxt.top/Article/details/gtsfiqzjgf.html

strlen(s)
来源：http://dali.jyoumei.cn/Article/details/gtdvzyvazp.html

[S06] C：字符串比较
来源：http://dali.zhengqikj.top/Article/details/gtddotthvr.html

strcmp(a, b) == 0
来源：http://dali.iojbl.cn/Article/details/gtpwqsviad.html

[S07] C：数组遍历求和
来源：http://dali.zycfv.cn/Article/details/gtqiaokdwz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zdqjudy.top/Article/details/gtwedkxyet.html

[S08] C：动态内存分配与释放
来源：http://dali.andypj.xyz/Article/details/gtgrmdlevh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.haohaochexian.top/Article/details/gtakixezma.html

[S09] C：结构体定义与初始化
来源：http://dali.zhengqikj.top/Article/details/gtkjqqxfer.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shanyushiyangkeji.top/Article/details/gtajtxonyw.html

[S10] C：指针与解引用
来源：http://dali.shanyushiyangtech.top/Article/details/gtamlkeplk.html

int *p = &a;  *p = 5;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzaiptkqg.html

[S11] C：逐行读文件
来源：http://dali.xylfe.cn/Article/details/gtzwlupnwh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.wangdashe.top/Article/details/gtmeazhaso.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cqqwz.cn/Article/details/gthqmvnwed.html

fclose(f);
来源：http://dali.gotoacloud.top/Article/details/gtqejjzagd.html

[S12] C：写文件
来源：http://dali.feifeiyinyue.top/Article/details/gtajpctxzo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gogol.net.cn/Article/details/gthpwdanyh.html

[S13] C：宏定义
来源：http://dali.shanyushiyangkeji.top/Article/details/gtscvlubkv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.andypj.xyz/Article/details/gtbnfdkhxb.html

[S14] C：枚举
来源：http://dali.dashuyun.cn/Article/details/gtkmwpzpxb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cdnleiting.top/Article/details/gtxkkgirxw.html

[S15] C：类型转换
来源：http://dali.yvedp.cn/Article/details/gtigoerkpy.html

(double) a / b
来源：http://dali.xuetiantiany.cn/Article/details/gtnikihuwe.html

[S16] C：位操作置位
来源：http://dali.hysaishi.cn/Article/details/gtkvrvuixk.html

x |= (1 << 3);
来源：http://dali.yangfankeji.com/Article/details/gtpjkxokpz.html

[S17] C：安全拼接字符串
来源：http://dali.aibaodan.cn/Article/details/gtlxjkjbol.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zycfv.cn/Article/details/gtyishvxhe.html

[S18] C：命令行参数
来源：http://dali.zhoulong.xyz/Article/details/gtcosawwmg.html

int main(int argc, char **argv)
来源：http://dali.zhengqikj.top/Article/details/gtmtycgdnd.html

[S19] C：快速排序
来源：http://dali.cqqwz.cn/Article/details/gtwwexsbqk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.nanxuanxn.top/Article/details/gtavfekefw.html

[S20] C：二分查找
来源：http://dali.jiagoushi.top/Article/details/gtnyxfspzp.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinqigfzy.top/Article/details/gtgceedtbd.html

[S21] C：字符类别判断
来源：http://dali.nanxinkj.top/Article/details/gtntxkynxc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cashguo.top/Article/details/gtpjpjkltq.html

[S22] C：字符串转数字
来源：http://dali.sysykeji.top/Article/details/gtvkikiurz.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yueranfly.top/Article/details/gtgzibzbgo.html

[S23] C：随机数
来源：http://dali.xylfe.cn/Article/details/gtspvfifnx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cucudq.cn/Article/details/gtnozpywaj.html

[S24] C：获取本地时间
来源：http://dali.fengsongda.top/Article/details/gtfmflpblf.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj202588.top/Article/details/gtpomucetu.html

[S25] C：内存拷贝
来源：http://dali.smart0.xyz/Article/details/gtafntuvoy.html

memcpy(dst, src, n);
来源：http://dali.sweek.top/Article/details/gtdclimwpr.html

[S26] C：内存清零
来源：http://dali.andypj.xyz/Article/details/gtiffajdjn.html

memset(a, 0, sizeof a);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzmnnxuxr.html

[S27] C：定义常量
来源：http://dali.feifeiyinyue.top/Article/details/gtalwpxpmx.html

const double PI = 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gtzpfirepc.html

[S28] C：静态变量
来源：http://dali.jyoumei.cn/Article/details/gtkuslibar.html

static int counter = 0;
来源：http://dali.tianlin.xyz/Article/details/gtwckpwwin.html

[S29] C：变参函数
来源：http://dali.andypj.xyz/Article/details/gtrxhslnbc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.haohaochexian.top/Article/details/gtiefhyjur.html

[S30] C：头文件保护
来源：http://dali.vqdsnc.cn/Article/details/gtamgyziuc.html

#ifndef X_H
来源：http://dali.ivvv.top/Article/details/gtesjrppwg.html

#define X_H
来源：http://dali.tanke756.top/Article/details/gtmuzmgmbv.html

#endif
来源：http://dali.jiagoushi.top/Article/details/gtzokgsskp.html

[S31] C++：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtpshmhwzw.html

#include <iostream>
来源：http://dali.kuanghao11.cn/Article/details/gtixnypioc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gogol.net.cn/Article/details/gtwwrjicgr.html

[S32] C++：字符串
来源：http://dali.cdnleiting.top/Article/details/gtgsjpqeha.html

std::string s = "hi";  s += "!";
来源：http://dali.cashguo.top/Article/details/gtompnjnrk.html

[S33] C++：vector 增删
来源：http://dali.svipenyu.cn/Article/details/gtqgzhyoxm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zdqjudy.top/Article/details/gtozszsust.html

[S34] C++：遍历 vector
来源：http://dali.chenjidiqi.icu/Article/details/gtmfpqmpbl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.kuanghao11.cn/Article/details/gtrohmolhz.html

[S35] C++：map
来源：http://dali.tanke756.top/Article/details/gtuwhbbrid.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.birdmap.top/Article/details/gtcfdvgxzb.html

[S36] C++：unordered_map
来源：http://dali.hnqzz.top/Article/details/gtxqlrbcut.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gtaymyzpue.html

[S37] C++：set
来源：http://dali.aizwys.cn/Article/details/gtxdqaoeaz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyascztwa.html

[S38] C++：排序
来源：http://dali.mhx1999.top/Article/details/gtmmruzhnp.html

std::sort(v.begin(), v.end());
来源：http://dali.shuidangran.top/Article/details/gtzfksvsik.html

[S39] C++：自定义比较器排序
来源：http://dali.nanxuanxn.top/Article/details/gtlosqkhki.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.fengsongda.top/Article/details/gtqlsuxvoo.html

[S40] C++：查找元素
来源：http://dali.chenlongwang.top/Article/details/gtmtpognyr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ydzc1.top/Article/details/gtteqoozxb.html

[S41] C++：类与构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtdgrkzaye.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.0kj1m.cn/Article/details/gtfpsirzpq.html

[S42] C++：继承与虚函数
来源：http://dali.hongshengwenyu.top/Article/details/gtmrahgqzj.html

class B : public Base { public: void f() override {} };
来源：http://dali.sysykeji.top/Article/details/gtkirhmdhu.html

[S43] C++：智能指针
来源：http://dali.cucudq.cn/Article/details/gtfabfcgue.html

auto p = std::make_unique<int>(5);
来源：http://dali.shzxlz.cn/Article/details/gtghewbsht.html

[S44] C++：引用传参
来源：http://dali.meibo888.top/Article/details/gtsoaodawf.html

void inc(int &x) { ++x; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtijlmmfuy.html

[S45] C++：lambda
来源：http://dali.yj20258888.top/Article/details/gtucwelbgd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.chenzaomai.com/Article/details/gtdffhzknw.html

[S46] C++：函数模板
来源：http://dali.zhoulong.xyz/Article/details/gtgdpjejpz.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zycfv.cn/Article/details/gticbevvgt.html

[S47] C++：结构化绑定遍历
来源：http://dali.hammf.cn/Article/details/gttvcvtrja.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hnqzz.top/Article/details/gtznjubuwf.html

[S48] C++：逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gtgpnpymva.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yvedp.cn/Article/details/gtzqwpufjl.html

while (std::getline(in, line)) { }
来源：http://dali.yueranfly.top/Article/details/gtmmphdjhs.html

[S49] C++：写文件
来源：http://dali.zhiwuduotai.top/Article/details/gtretqxpvs.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.sufxvd.cn/Article/details/gtnmbezphn.html

[S50] C++：格式化数字
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcojifcsp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.fzhhl.top/Article/details/gtcydkomes.html

[S51] C++：显式类型转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsyireism.html

static_cast<double>(a) / b
来源：http://dali.gotoacloud.top/Article/details/gtoryurrnq.html

[S52] C++：const 与 noexcept
来源：http://dali.ybcxt.top/Article/details/gtamvujype.html

int size() const noexcept { return n_; }
来源：http://dali.yj20258888.top/Article/details/gtsczsdoqv.html

[S53] C++：移动语义
来源：http://dali.tianlin.xyz/Article/details/gtcrrqrbbi.html

std::vector<int> w = std::move(v);
来源：http://dali.havefunace.top/Article/details/gtmhjpolto.html

[S54] C++：异常处理
来源：http://dali.jyoumei.cn/Article/details/gtxtpqfsrw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ybcxt.top/Article/details/gtujveslng.html

[S55] C++：结构化绑定
来源：http://dali.zhiwuduotai.top/Article/details/gtaghlushg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jinqigfzy.top/Article/details/gthiqtnntb.html

[S56] C++：optional
来源：http://dali.jlsjyb.cn/Article/details/gtzahrzeep.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.havefunace.top/Article/details/gtswybngdo.html

[S57] C++：编译期常量
来源：http://dali.ivvv.top/Article/details/gtrmmiudxg.html

constexpr int N = 10;
来源：http://dali.yongpay.top/Article/details/gtdxmodcif.html

[S58] C++：命名空间
来源：http://dali.sweek.top/Article/details/gtfezwnrgk.html

namespace ns { int f() { return 1; } }
来源：http://dali.fengsongda.top/Article/details/gtzuapuzph.html

[S59] C++：静态断言
来源：http://dali.xziqi.cn/Article/details/gttvrawdkm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.chenlongwang.top/Article/details/gtapjawmab.html

[S60] C++：遍历并删除元素
来源：http://dali.snrcjt.cn/Article/details/gtepfjhuze.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmelkqdzw.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtwntmkpme.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbokhejdf.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtvvfojbmd.html

[T01] Kotlin：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtqwxitdxi.html

println("Hello")
来源：http://dali.kuanghao11.cn/Article/details/gtkwgzeqap.html

[T02] Kotlin：变量
来源：http://dali.quarkkingdee.top/Article/details/gtogxfcjkz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.9152youxi.cn/Article/details/gtadwgqnmy.html

[T03] Kotlin：字符串模板
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcwumchfo.html

"值: $b"
来源：http://dali.tianlin.xyz/Article/details/gtgazqyvod.html

[T04] Kotlin：空安全
来源：http://dali.ybcxt.top/Article/details/gtfbxjaroo.html

val n: String? = null;  n?.length
来源：http://dali.yueranfly.top/Article/details/gtnxpfyvpb.html

[T05] Kotlin：when 表达式
来源：http://dali.gaohongyu789.top/Article/details/gtwuhvsvki.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jianghu66.top/Article/details/gtqvsgfiqx.html

[T06] Kotlin：集合映射
来源：http://dali.jqgfzy.top/Article/details/gtnzgwokrn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yj20258888.top/Article/details/gtxudccqfp.html

[T07] Kotlin：集合过滤
来源：http://dali.dashuyun.cn/Article/details/gtkrozwrhq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hysaishi.cn/Article/details/gtvhaiqygm.html

[T08] Kotlin：数据类
来源：http://dali.hammf.cn/Article/details/gtofemlwxj.html

data class User(val name: String, val age: Int)
来源：http://dali.xuetiantiany.cn/Article/details/gtpiekpmur.html

[T09] Kotlin：扩展函数
来源：http://dali.c1oappe.top/Article/details/gtkfivfbuw.html

fun String.exclaim() = this + "!"
来源：http://dali.tanke756.top/Article/details/gtuxombhlj.html

[T10] Kotlin：默认参数
来源：http://dali.tian-w.cn/Article/details/gthcwuhjtd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hysaishi.cn/Article/details/gtlorprhmw.html

[T11] Kotlin：协程
来源：http://dali.haohaochexian.top/Article/details/gtqrzusfmb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.kuanghao11.cn/Article/details/gtfxbkcged.html

[T12] Kotlin：解构声明
来源：http://dali.chenjidiqi.icu/Article/details/gtwoyufxsx.html

val (a, b) = Pair(1, 2)
来源：http://dali.xylfe.cn/Article/details/gtzysmsife.html

[T13] Kotlin：只读 Map
来源：http://dali.vqdsnc.cn/Article/details/gtbbrshipx.html

val m = mapOf("a" to 1)
来源：http://dali.ivvv.top/Article/details/gtlkfqhztu.html

[T14] Kotlin：循环
来源：http://dali.zhiwuduotai.top/Article/details/gtnxhrarcv.html

for (i in 1..10) println(i)
来源：http://dali.jyoumei.cn/Article/details/gtjcpobolh.html

[T15] Kotlin：接口
来源：http://dali.zhengqikj.top/Article/details/gtszseaogr.html

interface Shape { fun area(): Double }
来源：http://dali.cashguo.top/Article/details/gtuqegsvqx.html

[T16] Swift：Hello World
来源：http://dali.cheryme.top/Article/details/gtejabkuhm.html

print("Hello")
来源：http://dali.yvedp.cn/Article/details/gtcdhbbmto.html

[T17] Swift：变量与常量
来源：http://dali.zhixingplan.top/Article/details/gtfxcpxszr.html

var a = 1;  let b = 2
来源：http://dali.0kj1m.cn/Article/details/gtujiwnome.html

[T18] Swift：字符串插值
来源：http://dali.snrcjt.cn/Article/details/gtistdzwzs.html

"值: \(b)"
来源：http://dali.zhiwuduotai.top/Article/details/gtujlnrlxl.html

[T19] Swift：可选绑定
来源：http://dali.zhengqikj.top/Article/details/gtkiwxajxz.html

if let n = opt { print(n) }
来源：http://dali.yanxiufei.cn/Article/details/gtfelfonlj.html

[T20] Swift：数组操作
来源：http://dali.c1oappe.top/Article/details/gtdvldbmif.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cdnleiting.top/Article/details/gtoygyckfa.html

[T21] Swift：遍历
来源：http://dali.daxiang520.top/Article/details/gtawhsnyxe.html

for x in a { print(x) }
来源：http://dali.hammf.cn/Article/details/gtemcimmud.html

[T22] Swift：字典
来源：http://dali.gogol.net.cn/Article/details/gttnshrper.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.nanxuanxn.top/Article/details/gtarcfkdze.html

[T23] Swift：函数
来源：http://dali.nanxinkj.top/Article/details/gtefxoplhh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.chenzaomai.com/Article/details/gtfjdquhoq.html

[T24] Swift：闭包
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdlocwdhz.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hysaishi.cn/Article/details/gtfjbekame.html

[T25] Swift：结构体
来源：http://dali.havefunace.top/Article/details/gthddikiph.html

struct P { var x: Int }
来源：http://dali.yj20258888.top/Article/details/gtlxcntqdq.html

[T26] Swift：类与重写
来源：http://dali.sweek.top/Article/details/gtvnhoxtnc.html

class A: Base { override func f() {} }
来源：http://dali.wangdashe.top/Article/details/gtuykvladz.html

[T27] Swift：错误处理
来源：http://dali.cucudq.cn/Article/details/gtygtspnwf.html

do { try f() } catch { print(error) }
来源：http://dali.wangdashe.top/Article/details/gtvqwubcuv.html

[T28] Swift：枚举
来源：http://dali.ydzc1.top/Article/details/gtqzawyggc.html

enum Color { case red, green }
来源：http://dali.guowangkeji.top/Article/details/gtxpnertqh.html

[T29] Swift：guard 提前返回
来源：http://dali.tian-w.cn/Article/details/gtalldubgs.html

guard let x = opt else { return }
来源：http://dali.cdnleiting.top/Article/details/gtfhkzrnfg.html

[T30] Swift：协议
来源：http://dali.cheryme.top/Article/details/gtrzsskqtq.html

protocol Shape { func area() -> Double }
来源：http://dali.guowangkeji.top/Article/details/gtdszbywqq.html

[T31] Lua：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtqxzscygb.html

print("Hello")
来源：http://dali.jqgfzy.top/Article/details/gtumpnppyq.html

[T32] Lua：局部变量
来源：http://dali.zhiwuduotai.top/Article/details/gtjceonfog.html

local a = 1
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyidvvpux.html

[T33] Lua：表（数组）
来源：http://dali.redwolf501.top/Article/details/gtdagrtvlv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hywenlv.cn/Article/details/gtocrwbnwz.html

[T34] Lua：遍历表
来源：http://dali.quarkkingdee.top/Article/details/gtjacowyof.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlwxydyrv.html

[T35] Lua：字典表
来源：http://dali.sxryk.cn/Article/details/gtzmmmqunh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cdnleiting.top/Article/details/gtdmiverqj.html

[T36] Lua：函数
来源：http://dali.316326.xyz/Article/details/gtohhybewh.html

function add(a, b) return a + b end
来源：http://dali.jinqigfzy.top/Article/details/gtqqggbazr.html

[T37] Lua：字符串拼接
来源：http://dali.0kj1m.cn/Article/details/gtduyurfmu.html

"a" .. "b"
来源：http://dali.xuanzx.com/Article/details/gtgaybueee.html

[T38] Lua：条件
来源：http://dali.birdmap.top/Article/details/gtewpmudfv.html

if x > 0 then print("正") end
来源：http://dali.shanyushiyangtech.top/Article/details/gttvewvnfo.html

[T39] Lua：模式匹配
来源：http://dali.nanxinkj.top/Article/details/gtzuckhozc.html

string.find(s, "%d+")
来源：http://dali.shanyushiyangkeji.top/Article/details/gturjiwqlu.html

[T40] Lua：元表
来源：http://dali.zhiwuduotai.top/Article/details/gtsiwynxgs.html

setmetatable({}, { __index = base })
来源：http://dali.hnqzz.top/Article/details/gtsrfjmlyd.html

[T41] Perl：Hello World
来源：http://dali.316326.xyz/Article/details/gtdqxttyac.html

print "Hello\n";
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlrdotcpo.html

[T42] Perl：变量类型
来源：http://dali.jinghuilouyu.cn/Article/details/gtprmkljks.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.tian-w.cn/Article/details/gtcszyzvly.html

[T43] Perl：字符串插值
来源：http://dali.haohaochexian.top/Article/details/gtfcqyqyii.html

"值: $a"
来源：http://dali.havefunace.top/Article/details/gtnzojgfvj.html

[T44] Perl：条件
来源：http://dali.pengpengdd.cyou/Article/details/gtpbpmvchl.html

if ($a > 0) { print "正"; }
来源：http://dali.cucudq.cn/Article/details/gtchqhognh.html

[T45] Perl：数组遍历
来源：http://dali.shzxlz.cn/Article/details/gtltmylmbp.html

for my $x (@arr) { print $x; }
来源：http://dali.zhengqikj.top/Article/details/gthzfurqxv.html

[T46] Perl：哈希操作
来源：http://dali.birdmap.top/Article/details/gtvwndubar.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.hfpthk.cn/Article/details/gtfjoroqbh.html


<!-- 参考信息 -->