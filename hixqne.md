代发 wailian999

cmd > out.log 2>&1
来源：http://dali.jiagoushi.top/Article/details/gtenldnsbh.html

[R40] 追加写日志
来源：http://dali.ppjwa.cn/Article/details/gtgvizfgsp.html

echo "log" >> out.log
来源：http://dali.xziqi.cn/Article/details/gtnleaysoz.html

[R41] 丢弃输出
来源：http://dali.gzhubu.top/Article/details/gtvaweewog.html

cmd >/dev/null 2>&1
来源：http://dali.nwbrower.top/Article/details/gtdiprognq.html

[R42] 输入重定向
来源：http://dali.nanxinkj.top/Article/details/gtoeomadsn.html

wc -l < a.txt
来源：http://dali.yvedp.cn/Article/details/gtldccerss.html

[R43] 按名字查找文件
来源：http://dali.haohaochexian.top/Article/details/gtqslkdhgn.html

find . -name "*.log" -type f
来源：http://dali.zhixingplan.top/Article/details/gtfqzzdvmj.html

[R44] 按修改时间查找
来源：http://dali.guannengcc.top/Article/details/gtejficbkk.html

find . -mtime -7 -type f
来源：http://dali.redwolf501.top/Article/details/gtczkpkbss.html

[R45] 批量删除
来源：http://dali.sweek.top/Article/details/gtrbqfodrf.html

find . -name "*.tmp" -delete
来源：http://dali.havefunace.top/Article/details/gtrjhdtcfk.html

[R46] 递归替换文件内容
来源：http://dali.nanxuanxn.top/Article/details/gtthuqrhbe.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.tanke756.top/Article/details/gtrirukrin.html

[R47] sed 单行替换
来源：http://dali.havefunace.top/Article/details/gtpqvwpxyt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gogol.net.cn/Article/details/gtnzaksegy.html

[R48] awk 取指定列
来源：http://dali.gzhubu.top/Article/details/gtdasfqwoz.html

awk '{print $1, $3}' a.txt
来源：http://dali.andypj.xyz/Article/details/gtddcydtye.html

[R49] awk 带条件
来源：http://dali.havefunace.top/Article/details/gtvvccnxez.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gaohongyu789.top/Article/details/gtmjennwtm.html

[R50] awk 求和
来源：http://dali.sweek.top/Article/details/gtwmyzrdpx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.9152youxi.cn/Article/details/gtgzjrksiz.html

[R51] 排序去重取前几
来源：http://dali.hnqzz.top/Article/details/gtmgdykxgp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jqgfzy.top/Article/details/gttojzempq.html

[R52] 统计行数
来源：http://dali.zdqjudy.top/Article/details/gtxsnhgxep.html

wc -l a.txt
来源：http://dali.meibo888.top/Article/details/gtajqremns.html

[R53] 查看文件头与实时尾
来源：http://dali.c1oappe.top/Article/details/gtjekgnfei.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.snrcjt.cn/Article/details/gtsajdtufv.html

[R54] 比较两个文件
来源：http://dali.guannengcc.top/Article/details/gtsuzxjbdq.html

diff a.txt b.txt
来源：http://dali.zhengqikj.top/Article/details/gtxxuvnfqy.html

[R55] 压缩与解压
来源：http://dali.nanxinkj.top/Article/details/gtgxbdktlz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shanyushiyangtech.top/Article/details/gtxrrwehbq.html

[R56] 远程拷贝
来源：http://dali.cdnleiting.top/Article/details/gtufzsfilv.html

scp file user@host:/path/
来源：http://dali.xinyue.icu/Article/details/gtwgpsdlyc.html

[R57] 远程执行命令
来源：http://dali.wangdashe.top/Article/details/gtwqjnyeqd.html

ssh user@host 'uptime'
来源：http://dali.yangfankeji.com/Article/details/gtgbfxjvax.html

[R58] 下载文件
来源：http://dali.bjfxy.top/Article/details/gtszndcrna.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.9152youxi.cn/Article/details/gtspukockl.html

[R59] 发 POST JSON
来源：http://dali.shangyingyoupin.top/Article/details/gtavyerzbs.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yongpay.top/Article/details/gtzzsrihqj.html

[R60] 只看 HTTP 状态码
来源：http://dali.mhx1999.top/Article/details/gtuipmcpgc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shzxlz.cn/Article/details/gtyoavipdt.html

[R61] 磁盘占用
来源：http://dali.zhengqikj.top/Article/details/gtejqafbyp.html

df -h;  du -sh *
来源：http://dali.hnqzz.top/Article/details/gtngoyjnst.html

[R62] 找最占空间的文件
来源：http://dali.jlsjyb.cn/Article/details/gtqznhusdh.html

du -ah . | sort -rh | head -10
来源：http://dali.wangshuangyany.cn/Article/details/gtqvvmmdfo.html

[R63] 内存与进程
来源：http://dali.yj20258.top/Article/details/gtekeqrkvy.html

free -h;  ps aux | grep nginx
来源：http://dali.jinqigfzy.top/Article/details/gthpbrnuiv.html

[R64] 结束进程
来源：http://dali.pengpengdd.cyou/Article/details/gtmseaavqr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hongshengwenyu.top/Article/details/gtibcmzsgn.html

[R65] 查看端口占用
来源：http://dali.smart0.xyz/Article/details/gtfafidizz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhengqikj.top/Article/details/gtwsljvewl.html

[R66] 定时任务
来源：http://dali.shzxlz.cn/Article/details/gtudlnafcb.html

crontab -e;  crontab -l
来源：http://dali.yj20258888.top/Article/details/gtdhpaaipw.html

[R67] 生成随机十六进制串
来源：http://dali.yongpay.top/Article/details/gtdklwdrxb.html

openssl rand -hex 16
来源：http://dali.dashuyun.cn/Article/details/gtqajaextg.html

[R68] 计算文件校验值
来源：http://dali.quarkkingdee.top/Article/details/gtueqlohxz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gzhubu.top/Article/details/gthhhanoml.html

[R69] 生成随机密码
来源：http://dali.cucudq.cn/Article/details/gtmzhewssh.html

head -c 16 /dev/urandom | base64
来源：http://dali.tian-w.cn/Article/details/gtzgfpcpks.html

[R70] 时间戳与互转
来源：http://dali.0kj1m.cn/Article/details/gtfopmusaq.html

date +%s;  date -d @1700000000
来源：http://dali.yvedp.cn/Article/details/gtpxeazttc.html

[R71] 日期格式化
来源：http://dali.smart0.xyz/Article/details/gtzgohfarg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hysaishi.cn/Article/details/gtzcpntpoo.html

[R72] 等待端口就绪
来源：http://dali.shanyushiyangtech.top/Article/details/gtuofjntdm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.hywenlv.cn/Article/details/gtyejjostx.html

[R73] 分割大日志
来源：http://dali.yuxming.cn/Article/details/gtpwfrvwgr.html

split -l 1000 big.log part_
来源：http://dali.jianghu66.top/Article/details/gtjyavjoda.html

[R74] 批量重命名
来源：http://dali.shzxlz.cn/Article/details/gtagvplgsy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cheryme.top/Article/details/gtwmxgucbe.html

[R75] 导出环境变量
来源：http://dali.nanxinkj.top/Article/details/gtckdewnkd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.fzhhl.top/Article/details/gtwwsmgrbp.html

[R76] 使用临时文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtowgnkedi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinghuilouyu.cn/Article/details/gteyyvxoue.html

[R77] 读取用户输入
来源：http://dali.shzxlz.cn/Article/details/gtkfglfjfb.html

read -rp "请输入: " ans
来源：http://dali.wangshuangyany.cn/Article/details/gtmikowpxs.html

[R78] 交互式菜单
来源：http://dali.jiagoushi.top/Article/details/gtzblwkdjd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gaohongyu789.top/Article/details/gtsmfdsyqt.html

[R79] 解析命令行选项
来源：http://dali.yvedp.cn/Article/details/gtklklryic.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.smart0.xyz/Article/details/gtvonnkejl.html

[R80] 查看脚本执行耗时
来源：http://dali.jinqigufen.top/Article/details/gtkjgrirof.html

time ./run.sh
来源：http://dali.guowangkeji.top/Article/details/gtugsyjsmd.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtzibdpcji.html

S. C / C++ 专题
来源：http://dali.ivvv.top/Article/details/gtqdyxjvto.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtqlpktlkw.html

[S01] C：Hello World
来源：http://dali.316326.xyz/Article/details/gtxbpunbrm.html

#include <stdio.h>
来源：http://dali.ydzc1.top/Article/details/gtnkqwrnwi.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yueranfly.top/Article/details/gtzmpkicca.html

[S02] C：变量与格式化输出
来源：http://dali.jqgufenzy.top/Article/details/gtmxgfabhu.html

int a = 10; printf("%d\n", a);
来源：http://dali.shangyingyoupin.top/Article/details/gtqpfwxmig.html

[S03] C：读入整数
来源：http://dali.hongshengwenyu.top/Article/details/gtnhantxiq.html

int x; scanf("%d", &x);
来源：http://dali.yanxiufei.cn/Article/details/gthsjwsqhr.html

[S04] C：字符串复制
来源：http://dali.yj20258.top/Article/details/gtiusxbjff.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jiagoushi.top/Article/details/gtkbudnjru.html

[S05] C：字符串长度
来源：http://dali.gogol.net.cn/Article/details/gtrusgthml.html

strlen(s)
来源：http://dali.yueranfly.top/Article/details/gtoxlccfri.html

[S06] C：字符串比较
来源：http://dali.jinqigfzy.top/Article/details/gtwyzncwhx.html

strcmp(a, b) == 0
来源：http://dali.yj202588.top/Article/details/gtptmmlmhw.html

[S07] C：数组遍历求和
来源：http://dali.yj20258.top/Article/details/gtbnzbxqxo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.fengsongda.top/Article/details/gtqvdlbwnv.html

[S08] C：动态内存分配与释放
来源：http://dali.chenlongwang.top/Article/details/gtlkqdspbv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yonumen.top/Article/details/gtjbuqplek.html

[S09] C：结构体定义与初始化
来源：http://dali.shangyingyoupin.top/Article/details/gtwdhckxae.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.wangdashe.top/Article/details/gtisxrnwgq.html

[S10] C：指针与解引用
来源：http://dali.jqgufenzy.top/Article/details/gtvbajulnv.html

int *p = &a;  *p = 5;
来源：http://dali.tanke756.top/Article/details/gturjkeugf.html

[S11] C：逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gtvyaykstd.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.guannengcc.top/Article/details/gtzvfuwlni.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.pengpengdd.cyou/Article/details/gtcfauvjuk.html

fclose(f);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtezilexjg.html

[S12] C：写文件
来源：http://dali.cdnleiting.top/Article/details/gtpgyyhqib.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.bjfxy.top/Article/details/gtkbrjbjzs.html

[S13] C：宏定义
来源：http://dali.ydzc1.top/Article/details/gtcjaapalc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xinyue.icu/Article/details/gtjesprfyc.html

[S14] C：枚举
来源：http://dali.yj20258888.top/Article/details/gtlvzedaok.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jlsjyb.cn/Article/details/gteyttjfdz.html

[S15] C：类型转换
来源：http://dali.fengsongda.top/Article/details/gtthsqcsqk.html

(double) a / b
来源：http://dali.sxryk.cn/Article/details/gtxewkqzbr.html

[S16] C：位操作置位
来源：http://dali.hfpthk.cn/Article/details/gtmplssufl.html

x |= (1 << 3);
来源：http://dali.sufxvd.cn/Article/details/gtgkcueaqa.html

[S17] C：安全拼接字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtjkefkqlh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gaohongyu789.top/Article/details/gtkiavnqwd.html

[S18] C：命令行参数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzfllovdn.html

int main(int argc, char **argv)
来源：http://dali.chenjidiqi.icu/Article/details/gttdblfkhu.html

[S19] C：快速排序
来源：http://dali.yj20258888.top/Article/details/gtqjvhzdxd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.kuanghao11.cn/Article/details/gtzoxozsqm.html

[S20] C：二分查找
来源：http://dali.sysykeji.top/Article/details/gteolwkakt.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yongpay.top/Article/details/gtinoumzpd.html

[S21] C：字符类别判断
来源：http://dali.tian-w.cn/Article/details/gtordnrzyd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.daxiang520.top/Article/details/gtokvoclzn.html

[S22] C：字符串转数字
来源：http://dali.fzhhl.top/Article/details/gtzbcfsmjs.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.daxiang520.top/Article/details/gtycrlqroe.html

[S23] C：随机数
来源：http://dali.gaohongyu789.top/Article/details/gtzdmkobqg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cashguo.top/Article/details/gtmkitawxs.html

[S24] C：获取本地时间
来源：http://dali.jianghu66.top/Article/details/gtmqtqoces.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zdqjudy.top/Article/details/gtzvwvgett.html

[S25] C：内存拷贝
来源：http://dali.guannengcc.top/Article/details/gtwvmuqhhh.html

memcpy(dst, src, n);
来源：http://dali.yj202588.top/Article/details/gtlwaihhwo.html

[S26] C：内存清零
来源：http://dali.andypj.xyz/Article/details/gtufoezvng.html

memset(a, 0, sizeof a);
来源：http://dali.daxiang520.top/Article/details/gtbyhhoohs.html

[S27] C：定义常量
来源：http://dali.yvedp.cn/Article/details/gtrfbcdcem.html

const double PI = 3.14159;
来源：http://dali.yuxming.cn/Article/details/gtyzugjktj.html

[S28] C：静态变量
来源：http://dali.ydzc1.top/Article/details/gtcrwindjj.html

static int counter = 0;
来源：http://dali.0kj1m.cn/Article/details/gtwvqghbpr.html

[S29] C：变参函数
来源：http://dali.xziqi.cn/Article/details/gtrtjroimw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.snrcjt.cn/Article/details/gtygoefyby.html

[S30] C：头文件保护
来源：http://dali.dianchejie.cn/Article/details/gtiyusaolg.html

#ifndef X_H
来源：http://dali.sxryk.cn/Article/details/gtorbnnyvc.html

#define X_H
来源：http://dali.tanke756.top/Article/details/gtzaximigb.html

#endif
来源：http://dali.haohaochexian.top/Article/details/gtjuqqfseg.html

[S31] C++：Hello World
来源：http://dali.sweek.top/Article/details/gtsqktrcbh.html

#include <iostream>
来源：http://dali.ehwqpu.com/Article/details/gtennhwmsp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yvedp.cn/Article/details/gtqspjayia.html

[S32] C++：字符串
来源：http://dali.hnqzz.top/Article/details/gtsplfhutg.html

std::string s = "hi";  s += "!";
来源：http://dali.vqdsnc.cn/Article/details/gtbgxwujgk.html

[S33] C++：vector 增删
来源：http://dali.ivvv.top/Article/details/gtyymnawem.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ydzc1.top/Article/details/gtyzswmvsy.html

[S34] C++：遍历 vector
来源：http://dali.nanxuanxn.top/Article/details/gtdfveoszq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hywenlv.cn/Article/details/gtmqxjrjiu.html

[S35] C++：map
来源：http://dali.mhx1999.top/Article/details/gtorvhoyql.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gthvlbpkvf.html

[S36] C++：unordered_map
来源：http://dali.hongshengwenyu.top/Article/details/gtgudsmoil.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aizwys.cn/Article/details/gtvbizurwq.html

[S37] C++：set
来源：http://dali.haohaochexian.top/Article/details/gthyupjyod.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yuxming.cn/Article/details/gtscgbbdae.html

[S38] C++：排序
来源：http://dali.feifeiyinyue.top/Article/details/gtorysplij.html

std::sort(v.begin(), v.end());
来源：http://dali.chenzaomai.com/Article/details/gtihvcsbns.html

[S39] C++：自定义比较器排序
来源：http://dali.jqgfzy.top/Article/details/gtarjyudhb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.dianchejie.cn/Article/details/gtkbekpsoc.html

[S40] C++：查找元素
来源：http://dali.hfpthk.cn/Article/details/gtwwoujthj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ivvv.top/Article/details/gthuobgopg.html

[S41] C++：类与构造函数
来源：http://dali.jiagoushi.top/Article/details/gtqzlobtwr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.316326.xyz/Article/details/gthanpfrow.html

[S42] C++：继承与虚函数
来源：http://dali.0kj1m.cn/Article/details/gtllafpkjk.html

class B : public Base { public: void f() override {} };
来源：http://dali.shuidangran.top/Article/details/gtmvvdawmd.html

[S43] C++：智能指针
来源：http://dali.c1oappe.top/Article/details/gtqbstshvj.html

auto p = std::make_unique<int>(5);
来源：http://dali.tanke756.top/Article/details/gteyuehmqw.html

[S44] C++：引用传参
来源：http://dali.svipenyu.cn/Article/details/gthhyhyyps.html

void inc(int &x) { ++x; }
来源：http://dali.zhixingplan.top/Article/details/gtncmlybxu.html

[S45] C++：lambda
来源：http://dali.c1oappe.top/Article/details/gtjhxmjvkb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jyoumei.cn/Article/details/gttnsgzgxj.html

[S46] C++：函数模板
来源：http://dali.hnqzz.top/Article/details/gtqipbqmic.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yj202588.top/Article/details/gtnmeoddfg.html

[S47] C++：结构化绑定遍历
来源：http://dali.birdmap.top/Article/details/gtrkweghaj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.fzhhl.top/Article/details/gtqetrtacj.html

[S48] C++：逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gthtpxnsyu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyrwzzteq.html

while (std::getline(in, line)) { }
来源：http://dali.gogol.net.cn/Article/details/gtsdbmfqks.html

[S49] C++：写文件
来源：http://dali.nanxinkj.top/Article/details/gtsuqeuytv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.redwolf501.top/Article/details/gtdllssoyd.html

[S50] C++：格式化数字
来源：http://dali.jyoumei.cn/Article/details/gtzyowojnc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yuxming.cn/Article/details/gtwkjvzvlq.html

[S51] C++：显式类型转换
来源：http://dali.smart0.xyz/Article/details/gtljykweli.html

static_cast<double>(a) / b
来源：http://dali.havefunace.top/Article/details/gtbtufvvdd.html

[S52] C++：const 与 noexcept
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtakxfhpsj.html

int size() const noexcept { return n_; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtkdzrgfwn.html

[S53] C++：移动语义
来源：http://dali.bjfxy.top/Article/details/gtwsdvmyfo.html

std::vector<int> w = std::move(v);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmxxhjwzn.html

[S54] C++：异常处理
来源：http://dali.xylfe.cn/Article/details/gtxfvudoya.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.c1oappe.top/Article/details/gtjjsjfcrx.html

[S55] C++：结构化绑定
来源：http://dali.andypj.xyz/Article/details/gtxfthcxll.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yj202588.top/Article/details/gtsfgxwysq.html

[S56] C++：optional
来源：http://dali.snrcjt.cn/Article/details/gtxnngytbq.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtklkytcyl.html

[S57] C++：编译期常量
来源：http://dali.bjfxy.top/Article/details/gtiyxwalng.html

constexpr int N = 10;
来源：http://dali.cdnleiting.top/Article/details/gtgcpxfmct.html

[S58] C++：命名空间
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlooywezp.html

namespace ns { int f() { return 1; } }
来源：http://dali.sweek.top/Article/details/gttfqwxztb.html

[S59] C++：静态断言
来源：http://dali.yuxming.cn/Article/details/gthlgedyyy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.pengpengdd.cyou/Article/details/gteevakpwm.html

[S60] C++：遍历并删除元素
来源：http://dali.yj20258.top/Article/details/gtniiwcoww.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yanxiufei.cn/Article/details/gtgttejxcq.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtbvjzvlpf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cdnleiting.top/Article/details/gtqyovfmkd.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gteuglobik.html

[T01] Kotlin：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gtmjsxzzix.html

println("Hello")
来源：http://dali.quarkkingdee.top/Article/details/gtxhllgohq.html

[T02] Kotlin：变量
来源：http://dali.kuanghao11.cn/Article/details/gtibxzrioj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hongshengwenyu.top/Article/details/gteepmuizs.html

[T03] Kotlin：字符串模板
来源：http://dali.yj202588.top/Article/details/gtrgybqqpi.html

"值: $b"
来源：http://dali.zhengqikj.top/Article/details/gteykxqran.html

[T04] Kotlin：空安全
来源：http://dali.gotoacloud.top/Article/details/gtfatgnwmq.html

val n: String? = null;  n?.length
来源：http://dali.iojbl.cn/Article/details/gtzifyygqz.html

[T05] Kotlin：when 表达式
来源：http://dali.yj202588.top/Article/details/gtpoosapgf.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.xziqi.cn/Article/details/gtwfovnnsn.html

[T06] Kotlin：集合映射
来源：http://dali.sufxvd.cn/Article/details/gtabqeyprw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xylfe.cn/Article/details/gttedpnrkr.html

[T07] Kotlin：集合过滤
来源：http://dali.andypj.xyz/Article/details/gtjabqwkjw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.tian-w.cn/Article/details/gtgpjbxpoe.html

[T08] Kotlin：数据类
来源：http://dali.andypj.xyz/Article/details/gtpphomusl.html

data class User(val name: String, val age: Int)
来源：http://dali.xinyue.icu/Article/details/gtdisbafmi.html

[T09] Kotlin：扩展函数
来源：http://dali.zhongyouzk.top/Article/details/gttonenisb.html

fun String.exclaim() = this + "!"
来源：http://dali.svipenyu.cn/Article/details/gtpanuojxt.html

[T10] Kotlin：默认参数
来源：http://dali.daria6918.cn/Article/details/gtjjmynall.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hnxiangtu.top/Article/details/gtomodbifi.html

[T11] Kotlin：协程
来源：http://dali.tianlin.xyz/Article/details/gtmdbsktvs.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhiwuduotai.top/Article/details/gtbjhxmjrb.html

[T12] Kotlin：解构声明
来源：http://dali.cqqwz.cn/Article/details/gtkkrkyrbu.html

val (a, b) = Pair(1, 2)
来源：http://dali.cdnleiting.top/Article/details/gtlkcnkbnc.html

[T13] Kotlin：只读 Map
来源：http://dali.jyoumei.cn/Article/details/gtshubmsph.html

val m = mapOf("a" to 1)
来源：http://dali.jyoumei.cn/Article/details/gtyojxmrla.html

[T14] Kotlin：循环
来源：http://dali.gzhubu.top/Article/details/gtwbtkjhau.html

for (i in 1..10) println(i)
来源：http://dali.jinqigfzy.top/Article/details/gtcamcyqsa.html

[T15] Kotlin：接口
来源：http://dali.zhiwuduotai.top/Article/details/gtlgfaujvx.html

interface Shape { fun area(): Double }
来源：http://dali.nwbrower.top/Article/details/gtzmggrkri.html

[T16] Swift：Hello World
来源：http://dali.redwolf501.top/Article/details/gtlbmhueln.html

print("Hello")
来源：http://dali.sxryk.cn/Article/details/gtropyipop.html

[T17] Swift：变量与常量
来源：http://dali.chenlongwang.top/Article/details/gtlryzytve.html

var a = 1;  let b = 2
来源：http://dali.kuanghao11.cn/Article/details/gtvcfbzzdl.html

[T18] Swift：字符串插值
来源：http://dali.xuanzx.com/Article/details/gtftfjdajy.html

"值: \(b)"
来源：http://dali.cashguo.top/Article/details/gtqqxbrzfy.html

[T19] Swift：可选绑定
来源：http://dali.gogol.net.cn/Article/details/gtgscxauan.html

if let n = opt { print(n) }
来源：http://dali.wangdashe.top/Article/details/gtqwtjwldh.html

[T20] Swift：数组操作
来源：http://dali.iojbl.cn/Article/details/gtdhptlzos.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.snrcjt.cn/Article/details/gtbbrvjdjt.html

[T21] Swift：遍历
来源：http://dali.sweek.top/Article/details/gtaxoqxbad.html

for x in a { print(x) }
来源：http://dali.hysaishi.cn/Article/details/gtevzbxkus.html

[T22] Swift：字典
来源：http://dali.sweek.top/Article/details/gtwrzdqpnh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.tian-w.cn/Article/details/gtleesmads.html

[T23] Swift：函数
来源：http://dali.smart0.xyz/Article/details/gthmoevhqr.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.yanxiufei.cn/Article/details/gthgmuzmrn.html

[T24] Swift：闭包
来源：http://dali.yueranfly.top/Article/details/gtspyqezjb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.fzhhl.top/Article/details/gtvwmrjkkf.html

[T25] Swift：结构体
来源：http://dali.smart0.xyz/Article/details/gtoursgmbi.html

struct P { var x: Int }
来源：http://dali.ppjwa.cn/Article/details/gtajpqgrku.html

[T26] Swift：类与重写
来源：http://dali.ivvv.top/Article/details/gtrnbefjgc.html

class A: Base { override func f() {} }
来源：http://dali.cqqwz.cn/Article/details/gtxontkbzw.html

[T27] Swift：错误处理
来源：http://dali.gzhubu.top/Article/details/gtqdhytwlr.html

do { try f() } catch { print(error) }
来源：http://dali.yuxming.cn/Article/details/gtcmsrkenm.html

[T28] Swift：枚举
来源：http://dali.yangfankeji.com/Article/details/gtdveinhey.html

enum Color { case red, green }
来源：http://dali.fzhhl.top/Article/details/gtttcggvqv.html

[T29] Swift：guard 提前返回
来源：http://dali.jlsjyb.cn/Article/details/gtpwcrtgzx.html

guard let x = opt else { return }
来源：http://dali.andypj.xyz/Article/details/gtdvgyfhrw.html

[T30] Swift：协议
来源：http://dali.ehwqpu.com/Article/details/gtqbkljjms.html

protocol Shape { func area() -> Double }
来源：http://dali.gzhubu.top/Article/details/gtpnukxjbv.html

[T31] Lua：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtkfxlxonu.html

print("Hello")
来源：http://dali.gotoacloud.top/Article/details/gtpmejdlnh.html

[T32] Lua：局部变量
来源：http://dali.yuanzhike.top/Article/details/gtjuvtjwcm.html

local a = 1
来源：http://dali.zhoulong.xyz/Article/details/gtcuvtrlfd.html

[T33] Lua：表（数组）
来源：http://dali.nanxinkj.top/Article/details/gtrvosmihh.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.c1oappe.top/Article/details/gtyzgzomez.html

[T34] Lua：遍历表
来源：http://dali.birdmap.top/Article/details/gtbngnryew.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ybcxt.top/Article/details/gtldposzpw.html

[T35] Lua：字典表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjmsvqyhh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hnxiangtu.top/Article/details/gtfvheurcq.html

[T36] Lua：函数
来源：http://dali.pengpengdd.cyou/Article/details/gtxaymuljl.html

function add(a, b) return a + b end
来源：http://dali.jlsjyb.cn/Article/details/gtoodvzjzb.html

[T37] Lua：字符串拼接
来源：http://dali.dashuyun.cn/Article/details/gtxibdmntb.html

"a" .. "b"
来源：http://dali.snrcjt.cn/Article/details/gtklkklbzw.html

[T38] Lua：条件
来源：http://dali.zhongyouzk.top/Article/details/gtfusfbdtp.html

if x > 0 then print("正") end
来源：http://dali.ehwqpu.com/Article/details/gtqdfylyou.html

[T39] Lua：模式匹配
来源：http://dali.tanke756.top/Article/details/gtpdgskmqp.html

string.find(s, "%d+")
来源：http://dali.jlsjyb.cn/Article/details/gtkikrzuub.html

[T40] Lua：元表
来源：http://dali.gogol.net.cn/Article/details/gtehnchooa.html

setmetatable({}, { __index = base })
来源：http://dali.tanke756.top/Article/details/gtbymjpera.html

[T41] Perl：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gtcwwttyxl.html

print "Hello\n";
来源：http://dali.ywan-chungtsiang.top/Article/details/gtklsdfocx.html

[T42] Perl：变量类型
来源：http://dali.tian-w.cn/Article/details/gtkbuzbuvj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.quarkkingdee.top/Article/details/gtrxstiimv.html


<!-- 参考信息 -->