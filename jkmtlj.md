代发 wailian999

files=$(ls -1)
来源：http://dali.bjfxy.top/Article/details/gtwuormwyz.html

[R38] 管道串联
来源：http://dali.shangyingyoupin.top/Article/details/gtnfkssvjj.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shanyushiyangtech.top/Article/details/gttldhbbdu.html

[R39] 重定向标准输出与错误
来源：http://dali.ydzc1.top/Article/details/gtuokoybrq.html

cmd > out.log 2>&1
来源：http://dali.sweek.top/Article/details/gtyphbibpz.html

[R40] 追加写日志
来源：http://dali.zhongyouzk.top/Article/details/gtwtxfoaof.html

echo "log" >> out.log
来源：http://dali.ybcxt.top/Article/details/gteosgaegb.html

[R41] 丢弃输出
来源：http://dali.ehwqpu.com/Article/details/gtzncgjkbf.html

cmd >/dev/null 2>&1
来源：http://dali.dianchejie.cn/Article/details/gtkzpgvjmo.html

[R42] 输入重定向
来源：http://dali.sxryk.cn/Article/details/gtdxpqvrvg.html

wc -l < a.txt
来源：http://dali.yanxiufei.cn/Article/details/gttzhgsuye.html

[R43] 按名字查找文件
来源：http://dali.hfpthk.cn/Article/details/gtgssyzgjs.html

find . -name "*.log" -type f
来源：http://dali.birdmap.top/Article/details/gtgjoijzqw.html

[R44] 按修改时间查找
来源：http://dali.jinghuilouyu.cn/Article/details/gtvppuazil.html

find . -mtime -7 -type f
来源：http://dali.yj202588.top/Article/details/gtljtjnkmy.html

[R45] 批量删除
来源：http://dali.jinqigfzy.top/Article/details/gtftvilzcx.html

find . -name "*.tmp" -delete
来源：http://dali.jinqigufen.top/Article/details/gtupwqngvo.html

[R46] 递归替换文件内容
来源：http://dali.hnqzz.top/Article/details/gtaezqvrup.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yongpay.top/Article/details/gttwnllyyr.html

[R47] sed 单行替换
来源：http://dali.daria6918.cn/Article/details/gtznpvzbmc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ppjwa.cn/Article/details/gthdlbizwr.html

[R48] awk 取指定列
来源：http://dali.snrcjt.cn/Article/details/gtqivkyhcu.html

awk '{print $1, $3}' a.txt
来源：http://dali.dashuyun.cn/Article/details/gtcvjallro.html

[R49] awk 带条件
来源：http://dali.sweek.top/Article/details/gtmzjeowgq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.nanxuanxn.top/Article/details/gtnpydxqbd.html

[R50] awk 求和
来源：http://dali.chenzaomai.com/Article/details/gtdurgfweb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.dashuyun.cn/Article/details/gttracevtb.html

[R51] 排序去重取前几
来源：http://dali.smart0.xyz/Article/details/gtogieooho.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cqqwz.cn/Article/details/gtmisiwhsk.html

[R52] 统计行数
来源：http://dali.gzhubu.top/Article/details/gtqxkqqjob.html

wc -l a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtcedxpccw.html

[R53] 查看文件头与实时尾
来源：http://dali.ydzc1.top/Article/details/gtegqyszmd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cheryme.top/Article/details/gtrqxuuodh.html

[R54] 比较两个文件
来源：http://dali.yueranfly.top/Article/details/gtslvdepjs.html

diff a.txt b.txt
来源：http://dali.jinqigufen.top/Article/details/gtrmppezcc.html

[R55] 压缩与解压
来源：http://dali.cqqwz.cn/Article/details/gtzfxnyouu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xuetiantiany.cn/Article/details/gttkyfbibz.html

[R56] 远程拷贝
来源：http://dali.havefunace.top/Article/details/gtbdouybjw.html

scp file user@host:/path/
来源：http://dali.sweek.top/Article/details/gtagsqafdh.html

[R57] 远程执行命令
来源：http://dali.tian-w.cn/Article/details/gtgvbfjmsm.html

ssh user@host 'uptime'
来源：http://dali.gaohongyu789.top/Article/details/gtcqqhaxnp.html

[R58] 下载文件
来源：http://dali.yueranfly.top/Article/details/gtmdqryhhj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yj202588.top/Article/details/gthexxdpjx.html

[R59] 发 POST JSON
来源：http://dali.zhoulong.xyz/Article/details/gtrdzedvcv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hnqzz.top/Article/details/gtuwedytki.html

[R60] 只看 HTTP 状态码
来源：http://dali.andypj.xyz/Article/details/gtlqpqlmwe.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hongshengwenyu.top/Article/details/gtqsbqthwq.html

[R61] 磁盘占用
来源：http://dali.gotoacloud.top/Article/details/gtjuuqxlax.html

df -h;  du -sh *
来源：http://dali.iojbl.cn/Article/details/gtctvabfyt.html

[R62] 找最占空间的文件
来源：http://dali.zhoulong.xyz/Article/details/gtrszvkoby.html

du -ah . | sort -rh | head -10
来源：http://dali.cucudq.cn/Article/details/gtrielexhj.html

[R63] 内存与进程
来源：http://dali.fzhhl.top/Article/details/gtthqafktf.html

free -h;  ps aux | grep nginx
来源：http://dali.gaohongyu789.top/Article/details/gtkjgvbcdj.html

[R64] 结束进程
来源：http://dali.kuanghao11.cn/Article/details/gtkqjtofsw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hnxiangtu.top/Article/details/gtmftzkboy.html

[R65] 查看端口占用
来源：http://dali.guowangkeji.top/Article/details/gtwqotnapc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cashguo.top/Article/details/gtrsymvsfh.html

[R66] 定时任务
来源：http://dali.tianlin.xyz/Article/details/gtonetahgv.html

crontab -e;  crontab -l
来源：http://dali.dashuyun.cn/Article/details/gtvvmkyodr.html

[R67] 生成随机十六进制串
来源：http://dali.cucudq.cn/Article/details/gtybzcewef.html

openssl rand -hex 16
来源：http://dali.316326.xyz/Article/details/gtpmrrgkff.html

[R68] 计算文件校验值
来源：http://dali.gogol.net.cn/Article/details/gtnaroippm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwxvhnosu.html

[R69] 生成随机密码
来源：http://dali.yongpay.top/Article/details/gtvjhdwqwj.html

head -c 16 /dev/urandom | base64
来源：http://dali.yonumen.top/Article/details/gtaprkajkk.html

[R70] 时间戳与互转
来源：http://dali.cashguo.top/Article/details/gteyasetbv.html

date +%s;  date -d @1700000000
来源：http://dali.zhiwuduotai.top/Article/details/gtqvuerwuy.html

[R71] 日期格式化
来源：http://dali.zycfv.cn/Article/details/gtrnakljht.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhengqikj.top/Article/details/gtavlwhlbh.html

[R72] 等待端口就绪
来源：http://dali.gzhubu.top/Article/details/gtrgdkxihd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jyoumei.cn/Article/details/gtlmnzcdgx.html

[R73] 分割大日志
来源：http://dali.316326.xyz/Article/details/gtnchbtrzs.html

split -l 1000 big.log part_
来源：http://dali.hysaishi.cn/Article/details/gtatcxhggv.html

[R74] 批量重命名
来源：http://dali.yj20258.top/Article/details/gtslfvtmcj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.fzhhl.top/Article/details/gtbitiqnkv.html

[R75] 导出环境变量
来源：http://dali.chenjidiqi.icu/Article/details/gtpwzaaztf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sxryk.cn/Article/details/gtjhynplgf.html

[R76] 使用临时文件
来源：http://dali.jiagoushi.top/Article/details/gtnebqpjxx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.redwolf501.top/Article/details/gtasoevkyc.html

[R77] 读取用户输入
来源：http://dali.hysaishi.cn/Article/details/gtehpervym.html

read -rp "请输入: " ans
来源：http://dali.cqqwz.cn/Article/details/gthiqiecqd.html

[R78] 交互式菜单
来源：http://dali.pengpengdd.cyou/Article/details/gtqsbtodvt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.yj20258888.top/Article/details/gtzejfyqbe.html

[R79] 解析命令行选项
来源：http://dali.yonumen.top/Article/details/gtdovsebis.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gzhubu.top/Article/details/gtdnxpepiz.html

[R80] 查看脚本执行耗时
来源：http://dali.birdmap.top/Article/details/gttybogjfu.html

time ./run.sh
来源：http://dali.yuxming.cn/Article/details/gtimectyao.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtlxlpxspf.html

S. C / C++ 专题
来源：http://dali.xziqi.cn/Article/details/gtgrngebbu.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtvsvovogx.html

[S01] C：Hello World
来源：http://dali.zdqjudy.top/Article/details/gtplknadax.html

#include <stdio.h>
来源：http://dali.yj20258.top/Article/details/gtrytusgub.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xylfe.cn/Article/details/gtzyqrbcng.html

[S02] C：变量与格式化输出
来源：http://dali.jinqigfzy.top/Article/details/gtytbzppst.html

int a = 10; printf("%d\n", a);
来源：http://dali.snrcjt.cn/Article/details/gtphxrswdp.html

[S03] C：读入整数
来源：http://dali.birdmap.top/Article/details/gtxtwrkzwx.html

int x; scanf("%d", &x);
来源：http://dali.tianlin.xyz/Article/details/gtryyzonjx.html

[S04] C：字符串复制
来源：http://dali.cdnleiting.top/Article/details/gttskwjewd.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yvedp.cn/Article/details/gthmxwhwit.html

[S05] C：字符串长度
来源：http://dali.havefunace.top/Article/details/gtsuilkjvr.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gtikbbxpog.html

[S06] C：字符串比较
来源：http://dali.xuetiantiany.cn/Article/details/gtjueuyowf.html

strcmp(a, b) == 0
来源：http://dali.shanyushiyangtech.top/Article/details/gttfnhsbux.html

[S07] C：数组遍历求和
来源：http://dali.yuxming.cn/Article/details/gtwwaqkebv.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hongshengwenyu.top/Article/details/gtvoziieqy.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gtjiardpzc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yj20258888.top/Article/details/gtskaqhgph.html

[S09] C：结构体定义与初始化
来源：http://dali.hnxiangtu.top/Article/details/gtmnihwrrg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.fzhhl.top/Article/details/gtnnyfulpu.html

[S10] C：指针与解引用
来源：http://dali.nanxuanxn.top/Article/details/gtrfazvlkw.html

int *p = &a;  *p = 5;
来源：http://dali.tianlin.xyz/Article/details/gtjfawnpvv.html

[S11] C：逐行读文件
来源：http://dali.daxiang520.top/Article/details/gtnqkuwqkc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.redwolf501.top/Article/details/gtorevhlfi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yueranfly.top/Article/details/gtouhjxdaj.html

fclose(f);
来源：http://dali.jinqigfzy.top/Article/details/gttstzojbd.html

[S12] C：写文件
来源：http://dali.yangfankeji.com/Article/details/gtdqylintu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.smart0.xyz/Article/details/gtrzdhtfpn.html

[S13] C：宏定义
来源：http://dali.sxryk.cn/Article/details/gtitfwxxsb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gaohongyu789.top/Article/details/gtmdfpovuv.html

[S14] C：枚举
来源：http://dali.hysaishi.cn/Article/details/gtcwvsmfdr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.fzhhl.top/Article/details/gtbvfiquhh.html

[S15] C：类型转换
来源：http://dali.jqgufenzy.top/Article/details/gtchjxiird.html

(double) a / b
来源：http://dali.dashuyun.cn/Article/details/gtnnoqzyqq.html

[S16] C：位操作置位
来源：http://dali.sxryk.cn/Article/details/gtjjsfzhlt.html

x |= (1 << 3);
来源：http://dali.yuxming.cn/Article/details/gtqzsiydtn.html

[S17] C：安全拼接字符串
来源：http://dali.tianlin.xyz/Article/details/gtbociroka.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zycfv.cn/Article/details/gtnuszrneb.html

[S18] C：命令行参数
来源：http://dali.aibaodan.cn/Article/details/gtougobrpr.html

int main(int argc, char **argv)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxvikrcem.html

[S19] C：快速排序
来源：http://dali.fengsongda.top/Article/details/gtnwmppgpm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yueranfly.top/Article/details/gtxijlpnia.html

[S20] C：二分查找
来源：http://dali.haohaochexian.top/Article/details/gtzcyhhzbk.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yueranfly.top/Article/details/gtvkbmgluv.html

[S21] C：字符类别判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gthhrbosyx.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yj202588.top/Article/details/gtgzbmnluc.html

[S22] C：字符串转数字
来源：http://dali.yvedp.cn/Article/details/gtmugqbmby.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shanyushiyangtech.top/Article/details/gtqfutffcu.html

[S23] C：随机数
来源：http://dali.tianlin.xyz/Article/details/gteweolfxb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.gotoacloud.top/Article/details/gtduzwbzaa.html

[S24] C：获取本地时间
来源：http://dali.jinqigfzy.top/Article/details/gtxpsulifc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hnqzz.top/Article/details/gtedafymhz.html

[S25] C：内存拷贝
来源：http://dali.xuanzx.com/Article/details/gtdygswqpr.html

memcpy(dst, src, n);
来源：http://dali.fengsongda.top/Article/details/gtlvjgcukg.html

[S26] C：内存清零
来源：http://dali.hywenlv.cn/Article/details/gtnfhpfiiq.html

memset(a, 0, sizeof a);
来源：http://dali.dashuyun.cn/Article/details/gtqdkmkjyh.html

[S27] C：定义常量
来源：http://dali.guannengcc.top/Article/details/gtcwzqkmvp.html

const double PI = 3.14159;
来源：http://dali.xinyue.icu/Article/details/gtbvuqacuj.html

[S28] C：静态变量
来源：http://dali.nanxuanxn.top/Article/details/gtrhsufokv.html

static int counter = 0;
来源：http://dali.redwolf501.top/Article/details/gtcpulliao.html

[S29] C：变参函数
来源：http://dali.0kj1m.cn/Article/details/gtotrycwcy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhiwuduotai.top/Article/details/gtvyreuytr.html

[S30] C：头文件保护
来源：http://dali.zhongyouzk.top/Article/details/gtmguxldkt.html

#ifndef X_H
来源：http://dali.hammf.cn/Article/details/gtqlkextsh.html

#define X_H
来源：http://dali.zhengqikj.top/Article/details/gtjespcsqg.html

#endif
来源：http://dali.shangyingyoupin.top/Article/details/gtolnxjxoi.html

[S31] C++：Hello World
来源：http://dali.yongpay.top/Article/details/gtatsitwol.html

#include <iostream>
来源：http://dali.chenlongwang.top/Article/details/gtmvfmpsql.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwuyezvkt.html

[S32] C++：字符串
来源：http://dali.jyoumei.cn/Article/details/gtlqoiyaxw.html

std::string s = "hi";  s += "!";
来源：http://dali.zhengqikj.top/Article/details/gtploxazkf.html

[S33] C++：vector 增删
来源：http://dali.gaohongyu789.top/Article/details/gtzkihvqds.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yonumen.top/Article/details/gtcypxnqjk.html

[S34] C++：遍历 vector
来源：http://dali.gogol.net.cn/Article/details/gtdltubshf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.chenjidiqi.icu/Article/details/gtnajvecfq.html

[S35] C++：map
来源：http://dali.pycfn.com/Article/details/gtumbkdfnn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gtaynryybh.html

[S36] C++：unordered_map
来源：http://dali.pycfn.com/Article/details/gteaypibac.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gzhubu.top/Article/details/gtvrznfoxk.html

[S37] C++：set
来源：http://dali.mhx1999.top/Article/details/gtfvtlvmqp.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.chenzaomai.com/Article/details/gtoyozmssx.html

[S38] C++：排序
来源：http://dali.kuanghao11.cn/Article/details/gtsyvzqqzu.html

std::sort(v.begin(), v.end());
来源：http://dali.yangfankeji.com/Article/details/gtbxakpxyv.html

[S39] C++：自定义比较器排序
来源：http://dali.svipenyu.cn/Article/details/gtpknrqpnb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.tianlin.xyz/Article/details/gtukgjjqsy.html

[S40] C++：查找元素
来源：http://dali.kuanghao11.cn/Article/details/gtvsxxqrnt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.meibo888.top/Article/details/gtohzyqewf.html

[S41] C++：类与构造函数
来源：http://dali.316326.xyz/Article/details/gtyuloleqn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cucudq.cn/Article/details/gtpidzddbm.html

[S42] C++：继承与虚函数
来源：http://dali.bjfxy.top/Article/details/gtzlxecvnb.html

class B : public Base { public: void f() override {} };
来源：http://dali.0kj1m.cn/Article/details/gtajvdnmvh.html

[S43] C++：智能指针
来源：http://dali.aibaodan.cn/Article/details/gtmvbpheuc.html

auto p = std::make_unique<int>(5);
来源：http://dali.xinyue.icu/Article/details/gthplxzlfr.html

[S44] C++：引用传参
来源：http://dali.jqgfzy.top/Article/details/gtauduojeo.html

void inc(int &x) { ++x; }
来源：http://dali.jinqigfzy.top/Article/details/gtphzjgoob.html

[S45] C++：lambda
来源：http://dali.ivvv.top/Article/details/gtfahneqfo.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.kuanghao11.cn/Article/details/gtvcawlcsq.html

[S46] C++：函数模板
来源：http://dali.chenlongwang.top/Article/details/gtikstgemq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zhijiandao.cn/Article/details/gtpovsyosl.html

[S47] C++：结构化绑定遍历
来源：http://dali.iojbl.cn/Article/details/gtlohfqyog.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj202588.top/Article/details/gtqzpazusu.html

[S48] C++：逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gtoxraholi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hysaishi.cn/Article/details/gtftdsbnck.html

while (std::getline(in, line)) { }
来源：http://dali.hysaishi.cn/Article/details/gtctuxzyoq.html

[S49] C++：写文件
来源：http://dali.tian-w.cn/Article/details/gtckypsyrl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.smart0.xyz/Article/details/gtdbqsieyf.html

[S50] C++：格式化数字
来源：http://dali.tian-w.cn/Article/details/gtsybnvgog.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gtewmandau.html

[S51] C++：显式类型转换
来源：http://dali.andypj.xyz/Article/details/gtzgsiocgd.html

static_cast<double>(a) / b
来源：http://dali.cqqwz.cn/Article/details/gtaotobvwp.html

[S52] C++：const 与 noexcept
来源：http://dali.hongshengwenyu.top/Article/details/gtszfgzbyx.html

int size() const noexcept { return n_; }
来源：http://dali.dashuyun.cn/Article/details/gtllnzaanv.html

[S53] C++：移动语义
来源：http://dali.ivvv.top/Article/details/gtsftobddy.html

std::vector<int> w = std::move(v);
来源：http://dali.nanxinkj.top/Article/details/gtyghzozap.html

[S54] C++：异常处理
来源：http://dali.jlsjyb.cn/Article/details/gtpfmjdict.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinqigfzy.top/Article/details/gtnjjuapuz.html

[S55] C++：结构化绑定
来源：http://dali.jlsjyb.cn/Article/details/gtqddhwthx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hnqzz.top/Article/details/gtavdygafn.html

[S56] C++：optional
来源：http://dali.pengpengdd.cyou/Article/details/gthzekpkhx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ppjwa.cn/Article/details/gtijseekqe.html

[S57] C++：编译期常量
来源：http://dali.gotoacloud.top/Article/details/gtnaupxjcf.html

constexpr int N = 10;
来源：http://dali.snrcjt.cn/Article/details/gtegqzqoxn.html

[S58] C++：命名空间
来源：http://dali.hfpthk.cn/Article/details/gtnkdkstve.html

namespace ns { int f() { return 1; } }
来源：http://dali.xuanzx.com/Article/details/gtmztwxbta.html

[S59] C++：静态断言
来源：http://dali.hnqzz.top/Article/details/gtpleqvfbd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.fengsongda.top/Article/details/gtyagmmxya.html

[S60] C++：遍历并删除元素
来源：http://dali.zhongyouzk.top/Article/details/gtixaoqjkw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sxryk.cn/Article/details/gtuifhmyaa.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtmtqwdvui.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.iojbl.cn/Article/details/gtlropjqpv.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtlrzmdbhv.html

[T01] Kotlin：Hello World
来源：http://dali.c1oappe.top/Article/details/gtctfiongj.html

println("Hello")
来源：http://dali.fengsongda.top/Article/details/gtectwjorv.html

[T02] Kotlin：变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtenczjjmf.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.vqdsnc.cn/Article/details/gtybfgahan.html

[T03] Kotlin：字符串模板
来源：http://dali.gogol.net.cn/Article/details/gtwfyvznrq.html

"值: $b"
来源：http://dali.jqgufenzy.top/Article/details/gtlixtgzsd.html

[T04] Kotlin：空安全
来源：http://dali.tianlin.xyz/Article/details/gtgsnfaysb.html

val n: String? = null;  n?.length
来源：http://dali.birdmap.top/Article/details/gtdlwfugha.html

[T05] Kotlin：when 表达式
来源：http://dali.ivvv.top/Article/details/gtpofefmak.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.haohaochexian.top/Article/details/gtgvihxygu.html

[T06] Kotlin：集合映射
来源：http://dali.jinghuilouyu.cn/Article/details/gtaiwtskch.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.tanke756.top/Article/details/gtywlyzvjs.html

[T07] Kotlin：集合过滤
来源：http://dali.9152youxi.cn/Article/details/gtnlmnylhh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.fzhhl.top/Article/details/gtiqfwcmdc.html

[T08] Kotlin：数据类
来源：http://dali.zhoulong.xyz/Article/details/gtbnkvffpl.html

data class User(val name: String, val age: Int)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtawrsznea.html

[T09] Kotlin：扩展函数
来源：http://dali.cdnleiting.top/Article/details/gtdapnlcvy.html

fun String.exclaim() = this + "!"
来源：http://dali.pycfn.com/Article/details/gtvlwxayjy.html

[T10] Kotlin：默认参数
来源：http://dali.yj202588.top/Article/details/gtyjufgjty.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hywenlv.cn/Article/details/gtkcoqivnr.html

[T11] Kotlin：协程
来源：http://dali.snrcjt.cn/Article/details/gtfjqslsqp.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sweek.top/Article/details/gtptnshglo.html

[T12] Kotlin：解构声明
来源：http://dali.hnxiangtu.top/Article/details/gtihecajvr.html

val (a, b) = Pair(1, 2)
来源：http://dali.fengsongda.top/Article/details/gtdsssygtj.html

[T13] Kotlin：只读 Map
来源：http://dali.zhijiandao.cn/Article/details/gtiorraehs.html

val m = mapOf("a" to 1)
来源：http://dali.jianghu66.top/Article/details/gttqlcauot.html

[T14] Kotlin：循环
来源：http://dali.jinqigfzy.top/Article/details/gtdlacxjny.html

for (i in 1..10) println(i)
来源：http://dali.yongpay.top/Article/details/gtfylyiowh.html

[T15] Kotlin：接口
来源：http://dali.zycfv.cn/Article/details/gtfqkycjoc.html

interface Shape { fun area(): Double }
来源：http://dali.smart0.xyz/Article/details/gtijukvohz.html

[T16] Swift：Hello World
来源：http://dali.yangfankeji.com/Article/details/gtkrvcczgh.html

print("Hello")
来源：http://dali.yj20258.top/Article/details/gtydqyxukc.html

[T17] Swift：变量与常量
来源：http://dali.jianghu66.top/Article/details/gtnneeorya.html

var a = 1;  let b = 2
来源：http://dali.yj20258.top/Article/details/gttbpzufgb.html

[T18] Swift：字符串插值
来源：http://dali.jiagoushi.top/Article/details/gtzefwzczk.html

"值: \(b)"
来源：http://dali.dashuyun.cn/Article/details/gtauyadbxt.html

[T19] Swift：可选绑定
来源：http://dali.yonumen.top/Article/details/gtqwlqgqor.html

if let n = opt { print(n) }
来源：http://dali.zhijiandao.cn/Article/details/gtaoaoqpgl.html

[T20] Swift：数组操作
来源：http://dali.daria6918.cn/Article/details/gtnkcsnsnd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hywenlv.cn/Article/details/gtrmhngcam.html

[T21] Swift：遍历
来源：http://dali.pycfn.com/Article/details/gtqzdwcvhq.html

for x in a { print(x) }
来源：http://dali.daria6918.cn/Article/details/gthuixfeir.html

[T22] Swift：字典
来源：http://dali.hysaishi.cn/Article/details/gtipbiadyq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zhengqikj.top/Article/details/gtvsdzrydo.html

[T23] Swift：函数
来源：http://dali.guannengcc.top/Article/details/gtaraudwdi.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.dianchejie.cn/Article/details/gtkagqqmsl.html

[T24] Swift：闭包
来源：http://dali.sweek.top/Article/details/gtherepbhu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.shanyushiyangtech.top/Article/details/gtpgxizidr.html

[T25] Swift：结构体
来源：http://dali.yj20258.top/Article/details/gtunjkredm.html

struct P { var x: Int }
来源：http://dali.hfpthk.cn/Article/details/gtgtsmkegf.html

[T26] Swift：类与重写
来源：http://dali.dashuyun.cn/Article/details/gtvrctzabc.html

class A: Base { override func f() {} }
来源：http://dali.guannengcc.top/Article/details/gtmklangkj.html

[T27] Swift：错误处理
来源：http://dali.dianchejie.cn/Article/details/gtwhptsyep.html

do { try f() } catch { print(error) }
来源：http://dali.yuanzhike.top/Article/details/gteuvjlagv.html

[T28] Swift：枚举
来源：http://dali.aibaodan.cn/Article/details/gtfsgnhipq.html

enum Color { case red, green }
来源：http://dali.xylfe.cn/Article/details/gternyoclu.html

[T29] Swift：guard 提前返回
来源：http://dali.iojbl.cn/Article/details/gtdkoropri.html

guard let x = opt else { return }
来源：http://dali.zhixingplan.top/Article/details/gtcjpzbpaq.html

[T30] Swift：协议
来源：http://dali.vqdsnc.cn/Article/details/gtdqnfnuxq.html

protocol Shape { func area() -> Double }
来源：http://dali.aibaodan.cn/Article/details/gteddqpzyj.html

[T31] Lua：Hello World
来源：http://dali.sxryk.cn/Article/details/gtvtfuwpyg.html

print("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gttifstvtg.html

[T32] Lua：局部变量
来源：http://dali.daxiang520.top/Article/details/gtsrqnhzhd.html

local a = 1
来源：http://dali.ppjwa.cn/Article/details/gtaksyhiwx.html

[T33] Lua：表（数组）
来源：http://dali.haohaochexian.top/Article/details/gtuednlrbw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.pycfn.com/Article/details/gtafdstink.html

[T34] Lua：遍历表
来源：http://dali.yongpay.top/Article/details/gtixcoymhp.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwnmfdlkb.html

[T35] Lua：字典表
来源：http://dali.c1oappe.top/Article/details/gtdxstpfef.html

local d = { a = 1 };  d.b = 2
来源：http://dali.nanxuanxn.top/Article/details/gtlmtkpakr.html

[T36] Lua：函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtlisuxxjm.html

function add(a, b) return a + b end
来源：http://dali.yongpay.top/Article/details/gtfklfqysr.html

[T37] Lua：字符串拼接
来源：http://dali.gotoacloud.top/Article/details/gtzvcomhjp.html

"a" .. "b"
来源：http://dali.cucudq.cn/Article/details/gtddasigqv.html

[T38] Lua：条件
来源：http://dali.zdqjudy.top/Article/details/gtaisspjmg.html

if x > 0 then print("正") end
来源：http://dali.wangdashe.top/Article/details/gtzasryxhr.html

[T39] Lua：模式匹配
来源：http://dali.zhongyouzk.top/Article/details/gtsrvrgoax.html

string.find(s, "%d+")
来源：http://dali.sweek.top/Article/details/gthqfcwyhu.html

[T40] Lua：元表
来源：http://dali.chenlongwang.top/Article/details/gtgdbfnyvd.html

setmetatable({}, { __index = base })
来源：http://dali.daxiang520.top/Article/details/gtbxfywxsg.html


<!-- 参考信息 -->