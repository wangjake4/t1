代发 wailian999

cmd > out.log 2>&1
来源：http://dali.jinqigfzy.top/Article/details/gtonmftlok.html

[R40] 追加写日志
来源：http://dali.ybcxt.top/Article/details/gthyedyavi.html

echo "log" >> out.log
来源：http://dali.c1oappe.top/Article/details/gtqdatjjxn.html

[R41] 丢弃输出
来源：http://dali.gotoacloud.top/Article/details/gtkprnxfwv.html

cmd >/dev/null 2>&1
来源：http://dali.zhixingplan.top/Article/details/gtqmvboauv.html

[R42] 输入重定向
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsvvmlrko.html

wc -l < a.txt
来源：http://dali.daria6918.cn/Article/details/gtajrppnjf.html

[R43] 按名字查找文件
来源：http://dali.jyoumei.cn/Article/details/gtfrwaohwz.html

find . -name "*.log" -type f
来源：http://dali.sysykeji.top/Article/details/gtvkptokof.html

[R44] 按修改时间查找
来源：http://dali.daxiang520.top/Article/details/gtfnqxjucs.html

find . -mtime -7 -type f
来源：http://dali.tian-w.cn/Article/details/gtxkkvscqz.html

[R45] 批量删除
来源：http://dali.shuidangran.top/Article/details/gtbkweqwma.html

find . -name "*.tmp" -delete
来源：http://dali.hfpthk.cn/Article/details/gtyvdzwzmu.html

[R46] 递归替换文件内容
来源：http://dali.ydzc1.top/Article/details/gtieqnwiuv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.iojbl.cn/Article/details/gtsssaerdr.html

[R47] sed 单行替换
来源：http://dali.yj20258888.top/Article/details/gtgungoebi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.dianchejie.cn/Article/details/gtojgrvwnq.html

[R48] awk 取指定列
来源：http://dali.nanxinkj.top/Article/details/gtlpiqygko.html

awk '{print $1, $3}' a.txt
来源：http://dali.guannengcc.top/Article/details/gtaiaumzec.html

[R49] awk 带条件
来源：http://dali.guowangkeji.top/Article/details/gtkepjrlso.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.redwolf501.top/Article/details/gtfmpkufdo.html

[R50] awk 求和
来源：http://dali.haohaochexian.top/Article/details/gtubgkicgf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sweek.top/Article/details/gteqhkbpwo.html

[R51] 排序去重取前几
来源：http://dali.dianchejie.cn/Article/details/gtgewpwqeq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xylfe.cn/Article/details/gtrajajapc.html

[R52] 统计行数
来源：http://dali.zycfv.cn/Article/details/gtiqgxznzj.html

wc -l a.txt
来源：http://dali.jqgfzy.top/Article/details/gtsjizymos.html

[R53] 查看文件头与实时尾
来源：http://dali.yueranfly.top/Article/details/gtllmlfplc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cheryme.top/Article/details/gtggrxrfqw.html

[R54] 比较两个文件
来源：http://dali.meibo888.top/Article/details/gtuvngennc.html

diff a.txt b.txt
来源：http://dali.nanxinkj.top/Article/details/gtotcxcorr.html

[R55] 压缩与解压
来源：http://dali.bjfxy.top/Article/details/gtkrgozyod.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinqigfzy.top/Article/details/gtmtiokeln.html

[R56] 远程拷贝
来源：http://dali.zhengqikj.top/Article/details/gtjqyxgrec.html

scp file user@host:/path/
来源：http://dali.cucudq.cn/Article/details/gtwmbgvqhy.html

[R57] 远程执行命令
来源：http://dali.xinyue.icu/Article/details/gtikjeovzo.html

ssh user@host 'uptime'
来源：http://dali.hammf.cn/Article/details/gtmiqfynav.html

[R58] 下载文件
来源：http://dali.yonumen.top/Article/details/gtnsyabuzh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sufxvd.cn/Article/details/gtzxdpjwlb.html

[R59] 发 POST JSON
来源：http://dali.yongpay.top/Article/details/gthigxyjcr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.chenjidiqi.icu/Article/details/gtyjjbseni.html

[R60] 只看 HTTP 状态码
来源：http://dali.sweek.top/Article/details/gtyxgpvzmf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.aizwys.cn/Article/details/gtysnyfubh.html

[R61] 磁盘占用
来源：http://dali.gotoacloud.top/Article/details/gtkknervtc.html

df -h;  du -sh *
来源：http://dali.jinqigfzy.top/Article/details/gtzabixqvt.html

[R62] 找最占空间的文件
来源：http://dali.vqdsnc.cn/Article/details/gtaowbiczp.html

du -ah . | sort -rh | head -10
来源：http://dali.c1oappe.top/Article/details/gtlvwqqehi.html

[R63] 内存与进程
来源：http://dali.chenlongwang.top/Article/details/gtwkftgudb.html

free -h;  ps aux | grep nginx
来源：http://dali.sysykeji.top/Article/details/gtyteltobs.html

[R64] 结束进程
来源：http://dali.shuidangran.top/Article/details/gtirnzakml.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfbzxuscz.html

[R65] 查看端口占用
来源：http://dali.mhx1999.top/Article/details/gttfrorqhc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ehwqpu.com/Article/details/gtkblsyhaa.html

[R66] 定时任务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvwhnilso.html

crontab -e;  crontab -l
来源：http://dali.zhongyouzk.top/Article/details/gtxmqvayiv.html

[R67] 生成随机十六进制串
来源：http://dali.dashuyun.cn/Article/details/gtrfrtslug.html

openssl rand -hex 16
来源：http://dali.yonumen.top/Article/details/gteauhfpkc.html

[R68] 计算文件校验值
来源：http://dali.chenlongwang.top/Article/details/gtawufmdok.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.andypj.xyz/Article/details/gtyopmnpcl.html

[R69] 生成随机密码
来源：http://dali.cheryme.top/Article/details/gtvjsmzyso.html

head -c 16 /dev/urandom | base64
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjvouncyv.html

[R70] 时间戳与互转
来源：http://dali.daxiang520.top/Article/details/gtyuzywvtk.html

date +%s;  date -d @1700000000
来源：http://dali.yvedp.cn/Article/details/gtbeefztck.html

[R71] 日期格式化
来源：http://dali.jianghu66.top/Article/details/gtloeqkxyr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenlongwang.top/Article/details/gtdrnthimx.html

[R72] 等待端口就绪
来源：http://dali.zhongyouzk.top/Article/details/gtikxirvcv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gotoacloud.top/Article/details/gtjpotwidq.html

[R73] 分割大日志
来源：http://dali.hysaishi.cn/Article/details/gtrigwitfh.html

split -l 1000 big.log part_
来源：http://dali.ehwqpu.com/Article/details/gtfqbscadl.html

[R74] 批量重命名
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtirxhxcrg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hfpthk.cn/Article/details/gttbngpcgr.html

[R75] 导出环境变量
来源：http://dali.yanxiufei.cn/Article/details/gtubotgeqg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jlsjyb.cn/Article/details/gtkkwnakwy.html

[R76] 使用临时文件
来源：http://dali.chenlongwang.top/Article/details/gtznzjdscf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkectdptl.html

[R77] 读取用户输入
来源：http://dali.sweek.top/Article/details/gtyxyrcinj.html

read -rp "请输入: " ans
来源：http://dali.svipenyu.cn/Article/details/gtlutiadgb.html

[R78] 交互式菜单
来源：http://dali.sxryk.cn/Article/details/gtobdexffd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtghkaqtet.html

[R79] 解析命令行选项
来源：http://dali.c1oappe.top/Article/details/gtzfyezpsz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.iojbl.cn/Article/details/gtvbvgcvop.html

[R80] 查看脚本执行耗时
来源：http://dali.zdqjudy.top/Article/details/gtmnklpkka.html

time ./run.sh
来源：http://dali.xziqi.cn/Article/details/gtpcdriprc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gttzymcdzk.html

S. C / C++ 专题
来源：http://dali.cqqwz.cn/Article/details/gtbcoiajub.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtafwmbrsu.html

[S01] C：Hello World
来源：http://dali.meibo888.top/Article/details/gtuvbzzevg.html

#include <stdio.h>
来源：http://dali.guannengcc.top/Article/details/gtrbvdlkyn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtshpizudv.html

[S02] C：变量与格式化输出
来源：http://dali.yangfankeji.com/Article/details/gtasziufnb.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinghuilouyu.cn/Article/details/gtcoqghemb.html

[S03] C：读入整数
来源：http://dali.tian-w.cn/Article/details/gtwdeklxqj.html

int x; scanf("%d", &x);
来源：http://dali.316326.xyz/Article/details/gtkchufqnc.html

[S04] C：字符串复制
来源：http://dali.bjfxy.top/Article/details/gtrokhdqgw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.chenlongwang.top/Article/details/gtemusskzj.html

[S05] C：字符串长度
来源：http://dali.xziqi.cn/Article/details/gtymvmpnbr.html

strlen(s)
来源：http://dali.shzxlz.cn/Article/details/gtgnroxzbi.html

[S06] C：字符串比较
来源：http://dali.snrcjt.cn/Article/details/gtxprganjz.html

strcmp(a, b) == 0
来源：http://dali.jiagoushi.top/Article/details/gtpeiprgrb.html

[S07] C：数组遍历求和
来源：http://dali.ehwqpu.com/Article/details/gtxlcjksqu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gaohongyu789.top/Article/details/gtrbuomkir.html

[S08] C：动态内存分配与释放
来源：http://dali.meibo888.top/Article/details/gtantsonzq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yuanzhike.top/Article/details/gtjcwialbo.html

[S09] C：结构体定义与初始化
来源：http://dali.sufxvd.cn/Article/details/gtctitcurc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ybcxt.top/Article/details/gtxqoxlssr.html

[S10] C：指针与解引用
来源：http://dali.sufxvd.cn/Article/details/gtwspptnjq.html

int *p = &a;  *p = 5;
来源：http://dali.ydzc1.top/Article/details/gtnulghvtl.html

[S11] C：逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gtwjbsiura.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cdnleiting.top/Article/details/gttceiavud.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.smart0.xyz/Article/details/gtzwtywobc.html

fclose(f);
来源：http://dali.redwolf501.top/Article/details/gtoteefidf.html

[S12] C：写文件
来源：http://dali.guowangkeji.top/Article/details/gtydhuamwy.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xylfe.cn/Article/details/gtuyqdaznu.html

[S13] C：宏定义
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsplizbdu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gogol.net.cn/Article/details/gtkyvxygbm.html

[S14] C：枚举
来源：http://dali.ivvv.top/Article/details/gtwptetznj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.feifeiyinyue.top/Article/details/gtjdpcprjy.html

[S15] C：类型转换
来源：http://dali.mhx1999.top/Article/details/gtbwrcvrmh.html

(double) a / b
来源：http://dali.shuidangran.top/Article/details/gtdfvqbhrz.html

[S16] C：位操作置位
来源：http://dali.chenjidiqi.icu/Article/details/gtgqfmufvn.html

x |= (1 << 3);
来源：http://dali.gzhubu.top/Article/details/gtrwhmjhaq.html

[S17] C：安全拼接字符串
来源：http://dali.yonumen.top/Article/details/gthwxrzpfd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shzxlz.cn/Article/details/gtwxxsyzax.html

[S18] C：命令行参数
来源：http://dali.smart0.xyz/Article/details/gteusmqkya.html

int main(int argc, char **argv)
来源：http://dali.ybcxt.top/Article/details/gtjmzftaqc.html

[S19] C：快速排序
来源：http://dali.jinghuilouyu.cn/Article/details/gtatbzxgwo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hammf.cn/Article/details/gtizxrglcq.html

[S20] C：二分查找
来源：http://dali.meibo888.top/Article/details/gtqrwohnkl.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cucudq.cn/Article/details/gtxkorknjz.html

[S21] C：字符类别判断
来源：http://dali.zhoulong.xyz/Article/details/gttjrrmnuv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shuidangran.top/Article/details/gtvaadbkxy.html

[S22] C：字符串转数字
来源：http://dali.xuetiantiany.cn/Article/details/gtxatpmspq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.haohaochexian.top/Article/details/gtetnkhbfy.html

[S23] C：随机数
来源：http://dali.vqdsnc.cn/Article/details/gtprjedfic.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shuidangran.top/Article/details/gtdigxgdio.html

[S24] C：获取本地时间
来源：http://dali.hnxiangtu.top/Article/details/gtdtpbcisb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sysykeji.top/Article/details/gtxidufqan.html

[S25] C：内存拷贝
来源：http://dali.ydzc1.top/Article/details/gtdnmgtifv.html

memcpy(dst, src, n);
来源：http://dali.c1oappe.top/Article/details/gtpizqbrpm.html

[S26] C：内存清零
来源：http://dali.bjfxy.top/Article/details/gtsutosdwi.html

memset(a, 0, sizeof a);
来源：http://dali.yueranfly.top/Article/details/gtzssgtvfj.html

[S27] C：定义常量
来源：http://dali.zhiwuduotai.top/Article/details/gtuvrukics.html

const double PI = 3.14159;
来源：http://dali.sxryk.cn/Article/details/gtaxxyuoir.html

[S28] C：静态变量
来源：http://dali.dianchejie.cn/Article/details/gtluingnyn.html

static int counter = 0;
来源：http://dali.yongpay.top/Article/details/gtkqjjchtm.html

[S29] C：变参函数
来源：http://dali.bjfxy.top/Article/details/gthxewxqtq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gaohongyu789.top/Article/details/gtnajdpcqi.html

[S30] C：头文件保护
来源：http://dali.pycfn.com/Article/details/gteazgfanf.html

#ifndef X_H
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzgogawhg.html

#define X_H
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzewivycn.html

#endif
来源：http://dali.shuidangran.top/Article/details/gtmrcsphls.html

[S31] C++：Hello World
来源：http://dali.zycfv.cn/Article/details/gtfrkabaaa.html

#include <iostream>
来源：http://dali.ybcxt.top/Article/details/gtkunmznos.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtvuylkupc.html

[S32] C++：字符串
来源：http://dali.hnxiangtu.top/Article/details/gtffqlaemx.html

std::string s = "hi";  s += "!";
来源：http://dali.daxiang520.top/Article/details/gtaiergrfm.html

[S33] C++：vector 增删
来源：http://dali.ydzc1.top/Article/details/gtkbhhrdsr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.pengpengdd.cyou/Article/details/gtslhzlktu.html

[S34] C++：遍历 vector
来源：http://dali.zycfv.cn/Article/details/gtdorbisih.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cashguo.top/Article/details/gtsdodlohl.html

[S35] C++：map
来源：http://dali.zhoulong.xyz/Article/details/gtncniwowp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cucudq.cn/Article/details/gtoqqghavo.html

[S36] C++：unordered_map
来源：http://dali.ehwqpu.com/Article/details/gtofbvfqgb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtutovwiom.html

[S37] C++：set
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmpmmkcza.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hywenlv.cn/Article/details/gtcaqwgero.html

[S38] C++：排序
来源：http://dali.jqgufenzy.top/Article/details/gtchfgyxmg.html

std::sort(v.begin(), v.end());
来源：http://dali.kuanghao11.cn/Article/details/gtlyanotqo.html

[S39] C++：自定义比较器排序
来源：http://dali.daxiang520.top/Article/details/gtqqktabao.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gaohongyu789.top/Article/details/gtiutdpjgg.html

[S40] C++：查找元素
来源：http://dali.nanxuanxn.top/Article/details/gtcdqlaxml.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.redwolf501.top/Article/details/gtzvqpugpg.html

[S41] C++：类与构造函数
来源：http://dali.hysaishi.cn/Article/details/gtnoftrwan.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhijiandao.cn/Article/details/gtbdqulggz.html

[S42] C++：继承与虚函数
来源：http://dali.yuanzhike.top/Article/details/gtuhxxokly.html

class B : public Base { public: void f() override {} };
来源：http://dali.tianlin.xyz/Article/details/gtggawmmxn.html

[S43] C++：智能指针
来源：http://dali.sweek.top/Article/details/gtogmtuyjh.html

auto p = std::make_unique<int>(5);
来源：http://dali.hysaishi.cn/Article/details/gtfcjvlwvk.html

[S44] C++：引用传参
来源：http://dali.jqgufenzy.top/Article/details/gtggpnnokf.html

void inc(int &x) { ++x; }
来源：http://dali.jiagoushi.top/Article/details/gtqvrrudiu.html

[S45] C++：lambda
来源：http://dali.tanke756.top/Article/details/gthqwafoxp.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hywenlv.cn/Article/details/gtzkyfurjd.html

[S46] C++：函数模板
来源：http://dali.xuanzx.com/Article/details/gtkbjylgjs.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.snrcjt.cn/Article/details/gtippsyxdw.html

[S47] C++：结构化绑定遍历
来源：http://dali.xuanzx.com/Article/details/gttjvmungo.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cucudq.cn/Article/details/gtuwofncie.html

[S48] C++：逐行读文件
来源：http://dali.smart0.xyz/Article/details/gtalckbxxt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zycfv.cn/Article/details/gtvsgxkktm.html

while (std::getline(in, line)) { }
来源：http://dali.yj20258888.top/Article/details/gtrjxafqwi.html

[S49] C++：写文件
来源：http://dali.zhengqikj.top/Article/details/gtswqnunjo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.aibaodan.cn/Article/details/gtsjnrpbuo.html

[S50] C++：格式化数字
来源：http://dali.yvedp.cn/Article/details/gtuememufe.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gteheewodh.html

[S51] C++：显式类型转换
来源：http://dali.dianchejie.cn/Article/details/gtjrflasoa.html

static_cast<double>(a) / b
来源：http://dali.c1oappe.top/Article/details/gtpzopltud.html

[S52] C++：const 与 noexcept
来源：http://dali.wangdashe.top/Article/details/gtfdikceme.html

int size() const noexcept { return n_; }
来源：http://dali.cashguo.top/Article/details/gtipvddaqm.html

[S53] C++：移动语义
来源：http://dali.yuanzhike.top/Article/details/gtoywwmhcw.html

std::vector<int> w = std::move(v);
来源：http://dali.jqgufenzy.top/Article/details/gtvwvmhajl.html

[S54] C++：异常处理
来源：http://dali.yongpay.top/Article/details/gtzyqdbvlg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.wangdashe.top/Article/details/gtdmscqmns.html

[S55] C++：结构化绑定
来源：http://dali.sysykeji.top/Article/details/gtqmbftjow.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhoulong.xyz/Article/details/gtwyewtrql.html

[S56] C++：optional
来源：http://dali.guowangkeji.top/Article/details/gtncgjasrm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yanxiufei.cn/Article/details/gtedusljfd.html

[S57] C++：编译期常量
来源：http://dali.jqgfzy.top/Article/details/gtvcavxhna.html

constexpr int N = 10;
来源：http://dali.bjfxy.top/Article/details/gtqnoyihxj.html

[S58] C++：命名空间
来源：http://dali.svipenyu.cn/Article/details/gtnmmvuggc.html

namespace ns { int f() { return 1; } }
来源：http://dali.wangdashe.top/Article/details/gtdoggihks.html

[S59] C++：静态断言
来源：http://dali.snrcjt.cn/Article/details/gtksatkmdm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hnqzz.top/Article/details/gtcokfnunp.html

[S60] C++：遍历并删除元素
来源：http://dali.hywenlv.cn/Article/details/gtrbfdxyqw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cdnleiting.top/Article/details/gtwokmavls.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtldxwiwsz.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cheryme.top/Article/details/gtpjeuoqvs.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gteguydyjo.html

[T01] Kotlin：Hello World
来源：http://dali.mhx1999.top/Article/details/gtjhuxolcw.html

println("Hello")
来源：http://dali.birdmap.top/Article/details/gtpsiepkcs.html

[T02] Kotlin：变量
来源：http://dali.cheryme.top/Article/details/gtjjzmvknu.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.vqdsnc.cn/Article/details/gtxmptniia.html

[T03] Kotlin：字符串模板
来源：http://dali.tianlin.xyz/Article/details/gtqyvoacar.html

"值: $b"
来源：http://dali.tanke756.top/Article/details/gtirqmyvpu.html

[T04] Kotlin：空安全
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbpyciwvx.html

val n: String? = null;  n?.length
来源：http://dali.cucudq.cn/Article/details/gtmlftvqdl.html

[T05] Kotlin：when 表达式
来源：http://dali.dianchejie.cn/Article/details/gtlltmwqoy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.chenjidiqi.icu/Article/details/gtaktxdzol.html

[T06] Kotlin：集合映射
来源：http://dali.chenjidiqi.icu/Article/details/gtwakjppnn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.9152youxi.cn/Article/details/gtdgxzfqnr.html

[T07] Kotlin：集合过滤
来源：http://dali.chenjidiqi.icu/Article/details/gtrsegriqd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ehwqpu.com/Article/details/gtyoxqfdvw.html

[T08] Kotlin：数据类
来源：http://dali.jinqigufen.top/Article/details/gtwsdtgrmc.html

data class User(val name: String, val age: Int)
来源：http://dali.yanxiufei.cn/Article/details/gtmpwxsnwd.html

[T09] Kotlin：扩展函数
来源：http://dali.birdmap.top/Article/details/gtfppmqsku.html

fun String.exclaim() = this + "!"
来源：http://dali.zhixingplan.top/Article/details/gtzfbrjsnk.html

[T10] Kotlin：默认参数
来源：http://dali.chenzaomai.com/Article/details/gtktkiimpi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.chenlongwang.top/Article/details/gtxzdnqqye.html

[T11] Kotlin：协程
来源：http://dali.zhengqikj.top/Article/details/gtocsxhfph.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbqdspqpg.html

[T12] Kotlin：解构声明
来源：http://dali.zycfv.cn/Article/details/gtorazzxhh.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinqigfzy.top/Article/details/gtydhdycyd.html

[T13] Kotlin：只读 Map
来源：http://dali.gogol.net.cn/Article/details/gtmdozgrvw.html

val m = mapOf("a" to 1)
来源：http://dali.gogol.net.cn/Article/details/gtcpatpzhl.html

[T14] Kotlin：循环
来源：http://dali.yvedp.cn/Article/details/gtuzxpqmtq.html

for (i in 1..10) println(i)
来源：http://dali.dianchejie.cn/Article/details/gtmvplkanf.html

[T15] Kotlin：接口
来源：http://dali.hnqzz.top/Article/details/gtshhmzuuw.html

interface Shape { fun area(): Double }
来源：http://dali.cheryme.top/Article/details/gtjabsscpa.html

[T16] Swift：Hello World
来源：http://dali.xinyue.icu/Article/details/gthfozqowi.html

print("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiuhvskwt.html

[T17] Swift：变量与常量
来源：http://dali.wangshuangyany.cn/Article/details/gtetpgdgck.html

var a = 1;  let b = 2
来源：http://dali.xinyue.icu/Article/details/gthnvftbkj.html

[T18] Swift：字符串插值
来源：http://dali.wangshuangyany.cn/Article/details/gtshjitsut.html

"值: \(b)"
来源：http://dali.pycfn.com/Article/details/gtfmhrsscz.html

[T19] Swift：可选绑定
来源：http://dali.dianchejie.cn/Article/details/gtoajadrwy.html

if let n = opt { print(n) }
来源：http://dali.havefunace.top/Article/details/gtkmugsxun.html

[T20] Swift：数组操作
来源：http://dali.zhiwuduotai.top/Article/details/gtoxaqybjg.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cucudq.cn/Article/details/gtjizkpcvx.html

[T21] Swift：遍历
来源：http://dali.guowangkeji.top/Article/details/gtoujzjufy.html

for x in a { print(x) }
来源：http://dali.fengsongda.top/Article/details/gtyfjbjouy.html

[T22] Swift：字典
来源：http://dali.hywenlv.cn/Article/details/gttcevmsbf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ivvv.top/Article/details/gtavqiezfk.html

[T23] Swift：函数
来源：http://dali.haohaochexian.top/Article/details/gtggzqgwye.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.jinqigufen.top/Article/details/gtfayidgfu.html

[T24] Swift：闭包
来源：http://dali.sxryk.cn/Article/details/gtutetwosg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.daria6918.cn/Article/details/gtycjmvrne.html

[T25] Swift：结构体
来源：http://dali.jianghu66.top/Article/details/gtggvbbjzl.html

struct P { var x: Int }
来源：http://dali.c1oappe.top/Article/details/gtpypaxuii.html

[T26] Swift：类与重写
来源：http://dali.yanxiufei.cn/Article/details/gtvurrmnil.html

class A: Base { override func f() {} }
来源：http://dali.xinyue.icu/Article/details/gtiddgpdym.html

[T27] Swift：错误处理
来源：http://dali.sweek.top/Article/details/gtmuravjnv.html

do { try f() } catch { print(error) }
来源：http://dali.chenzaomai.com/Article/details/gterqjhguj.html

[T28] Swift：枚举
来源：http://dali.gaohongyu789.top/Article/details/gtkvgaudbq.html

enum Color { case red, green }
来源：http://dali.zhongyouzk.top/Article/details/gtwnrlbqmf.html

[T29] Swift：guard 提前返回
来源：http://dali.yj202588.top/Article/details/gtbuvaueqp.html

guard let x = opt else { return }
来源：http://dali.pycfn.com/Article/details/gtcldjlwgl.html

[T30] Swift：协议
来源：http://dali.andypj.xyz/Article/details/gtpaecznav.html

protocol Shape { func area() -> Double }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqeijyhnn.html

[T31] Lua：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtthxugrgc.html

print("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gtjzclmblt.html

[T32] Lua：局部变量
来源：http://dali.feifeiyinyue.top/Article/details/gtcuqbstot.html

local a = 1
来源：http://dali.sweek.top/Article/details/gttuxmvxpx.html

[T33] Lua：表（数组）
来源：http://dali.yj20258888.top/Article/details/gtuofjugaq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.feifeiyinyue.top/Article/details/gteuteykiv.html

[T34] Lua：遍历表
来源：http://dali.cucudq.cn/Article/details/gtanayotfd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.tanke756.top/Article/details/gtmatfpmxz.html

[T35] Lua：字典表
来源：http://dali.yvedp.cn/Article/details/gtvuvsgbsu.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cdnleiting.top/Article/details/gtnetoeedu.html

[T36] Lua：函数
来源：http://dali.cdnleiting.top/Article/details/gtykoecpqw.html

function add(a, b) return a + b end
来源：http://dali.hfpthk.cn/Article/details/gtjyrucldf.html

[T37] Lua：字符串拼接
来源：http://dali.xziqi.cn/Article/details/gtqzciafye.html

"a" .. "b"
来源：http://dali.gzhubu.top/Article/details/gttsrqvzsp.html

[T38] Lua：条件
来源：http://dali.yanxiufei.cn/Article/details/gtuxwdjzwk.html

if x > 0 then print("正") end
来源：http://dali.gzhubu.top/Article/details/gtkfhhnvdx.html

[T39] Lua：模式匹配
来源：http://dali.hnqzz.top/Article/details/gtlhnmbqym.html

string.find(s, "%d+")
来源：http://dali.hywenlv.cn/Article/details/gtkcpqezbg.html

[T40] Lua：元表
来源：http://dali.ivvv.top/Article/details/gtcffxetee.html

setmetatable({}, { __index = base })
来源：http://dali.xuetiantiany.cn/Article/details/gtcpbkdkog.html

[T41] Perl：Hello World
来源：http://dali.yueranfly.top/Article/details/gtfuvbxmru.html

print "Hello\n";
来源：http://dali.gotoacloud.top/Article/details/gtmcclmodd.html

[T42] Perl：变量类型
来源：http://dali.ydzc1.top/Article/details/gtoreqjrub.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ehwqpu.com/Article/details/gtobrdxmrp.html


<!-- 参考信息 -->