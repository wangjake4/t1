代发 wailian999

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.pengpengdd.cyou/Article/details/gtravbbptn.html

[R36] 并发执行多个任务
来源：http://dali.dianchejie.cn/Article/details/gtpnieyatg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cheryme.top/Article/details/gtejvbaofs.html

[R37] 把输出赋给变量
来源：http://dali.gogol.net.cn/Article/details/gtzpvwdhjs.html

files=$(ls -1)
来源：http://dali.shanyushiyangtech.top/Article/details/gtieavwvpt.html

[R38] 管道串联
来源：http://dali.shangyingyoupin.top/Article/details/gtnxzuztwq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yuxming.cn/Article/details/gtbtpbrngr.html

[R39] 重定向标准输出与错误
来源：http://dali.fzhhl.top/Article/details/gtfvyzkcyf.html

cmd > out.log 2>&1
来源：http://dali.zycfv.cn/Article/details/gtselhgyiu.html

[R40] 追加写日志
来源：http://dali.jinqigufen.top/Article/details/gtkexqzaix.html

echo "log" >> out.log
来源：http://dali.nanxinkj.top/Article/details/gtkhqjhwlu.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gtchhdsayg.html

cmd >/dev/null 2>&1
来源：http://dali.yanxiufei.cn/Article/details/gtehureppq.html

[R42] 输入重定向
来源：http://dali.xuetiantiany.cn/Article/details/gtzlmcceiu.html

wc -l < a.txt
来源：http://dali.jqgfzy.top/Article/details/gtgibtjbbl.html

[R43] 按名字查找文件
来源：http://dali.jinqigfzy.top/Article/details/gtzhdtmirl.html

find . -name "*.log" -type f
来源：http://dali.fengsongda.top/Article/details/gtjehovoqt.html

[R44] 按修改时间查找
来源：http://dali.cqqwz.cn/Article/details/gtoymkxcoi.html

find . -mtime -7 -type f
来源：http://dali.chenlongwang.top/Article/details/gtxjafrpll.html

[R45] 批量删除
来源：http://dali.daxiang520.top/Article/details/gtitjdvofn.html

find . -name "*.tmp" -delete
来源：http://dali.yueranfly.top/Article/details/gtaswdmojw.html

[R46] 递归替换文件内容
来源：http://dali.cashguo.top/Article/details/gtgspliagu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.havefunace.top/Article/details/gtkbxglvrz.html

[R47] sed 单行替换
来源：http://dali.yj20258888.top/Article/details/gthpppsnpb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.dianchejie.cn/Article/details/gtbspommhf.html

[R48] awk 取指定列
来源：http://dali.hammf.cn/Article/details/gtgdetmiip.html

awk '{print $1, $3}' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtlpvqyzpy.html

[R49] awk 带条件
来源：http://dali.ybcxt.top/Article/details/gtnosysajg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.316326.xyz/Article/details/gtdyvfrrsx.html

[R50] awk 求和
来源：http://dali.xuetiantiany.cn/Article/details/gtzvrmktrf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ydzc1.top/Article/details/gtcjvxecjr.html

[R51] 排序去重取前几
来源：http://dali.yj202588.top/Article/details/gtrkqixlpy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hysaishi.cn/Article/details/gtcgjwuqgy.html

[R52] 统计行数
来源：http://dali.hfpthk.cn/Article/details/gtkkwrqlfl.html

wc -l a.txt
来源：http://dali.ivvv.top/Article/details/gtgjvtjccv.html

[R53] 查看文件头与实时尾
来源：http://dali.zhiwuduotai.top/Article/details/gtevakaawb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shzxlz.cn/Article/details/gtftpxzosi.html

[R54] 比较两个文件
来源：http://dali.xylfe.cn/Article/details/gtfnwtebdh.html

diff a.txt b.txt
来源：http://dali.cucudq.cn/Article/details/gtbqtzcdag.html

[R55] 压缩与解压
来源：http://dali.nanxinkj.top/Article/details/gtelabxfbw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.fengsongda.top/Article/details/gtcxiltyzr.html

[R56] 远程拷贝
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrqftztbk.html

scp file user@host:/path/
来源：http://dali.cdnleiting.top/Article/details/gtznsmyasf.html

[R57] 远程执行命令
来源：http://dali.shangyingyoupin.top/Article/details/gtmqyeugxj.html

ssh user@host 'uptime'
来源：http://dali.ehwqpu.com/Article/details/gtzrtqxwlg.html

[R58] 下载文件
来源：http://dali.hnqzz.top/Article/details/gtvdpimcsr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jqgfzy.top/Article/details/gtfphseopr.html

[R59] 发 POST JSON
来源：http://dali.daria6918.cn/Article/details/gtdyyfkbtb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.tanke756.top/Article/details/gtaypoimto.html

[R60] 只看 HTTP 状态码
来源：http://dali.dianchejie.cn/Article/details/gtkzavzydo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yueranfly.top/Article/details/gthtojhvyt.html

[R61] 磁盘占用
来源：http://dali.svipenyu.cn/Article/details/gtaelzajcr.html

df -h;  du -sh *
来源：http://dali.gzhubu.top/Article/details/gtpehsicke.html

[R62] 找最占空间的文件
来源：http://dali.jlsjyb.cn/Article/details/gtpkkgxqdt.html

du -ah . | sort -rh | head -10
来源：http://dali.yonumen.top/Article/details/gtatdrqdhe.html

[R63] 内存与进程
来源：http://dali.hnxiangtu.top/Article/details/gtursxrkdv.html

free -h;  ps aux | grep nginx
来源：http://dali.yueranfly.top/Article/details/gtaxlepvty.html

[R64] 结束进程
来源：http://dali.guowangkeji.top/Article/details/gtrqagjdnj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.pycfn.com/Article/details/gtionkmqxw.html

[R65] 查看端口占用
来源：http://dali.svipenyu.cn/Article/details/gtqgfjykgq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.feifeiyinyue.top/Article/details/gtjtfddaty.html

[R66] 定时任务
来源：http://dali.ehwqpu.com/Article/details/gtqkyfkysp.html

crontab -e;  crontab -l
来源：http://dali.xinyue.icu/Article/details/gtznwtmfmy.html

[R67] 生成随机十六进制串
来源：http://dali.jianghu66.top/Article/details/gtdquzdhsr.html

openssl rand -hex 16
来源：http://dali.aibaodan.cn/Article/details/gteajggtzy.html

[R68] 计算文件校验值
来源：http://dali.iojbl.cn/Article/details/gtldetrzyb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbjvehfwb.html

[R69] 生成随机密码
来源：http://dali.ivvv.top/Article/details/gtdzorcnmn.html

head -c 16 /dev/urandom | base64
来源：http://dali.cheryme.top/Article/details/gtbjfelvcq.html

[R70] 时间戳与互转
来源：http://dali.jinghuilouyu.cn/Article/details/gtwumwokpn.html

date +%s;  date -d @1700000000
来源：http://dali.andypj.xyz/Article/details/gtlhazhhlo.html

[R71] 日期格式化
来源：http://dali.ppjwa.cn/Article/details/gtgxljhgpp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hammf.cn/Article/details/gterwxtatu.html

[R72] 等待端口就绪
来源：http://dali.hammf.cn/Article/details/gtinnqqyee.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.pengpengdd.cyou/Article/details/gtexkzrjdm.html

[R73] 分割大日志
来源：http://dali.yj20258888.top/Article/details/gtxkxikkrl.html

split -l 1000 big.log part_
来源：http://dali.gogol.net.cn/Article/details/gtesrvupoj.html

[R74] 批量重命名
来源：http://dali.tanke756.top/Article/details/gtiazmofgl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yuxming.cn/Article/details/gthvjnretx.html

[R75] 导出环境变量
来源：http://dali.sysykeji.top/Article/details/gtgbujrvwb.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtimwqnrjx.html

[R76] 使用临时文件
来源：http://dali.hammf.cn/Article/details/gtrcctgftq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.bjfxy.top/Article/details/gtxzeljkox.html

[R77] 读取用户输入
来源：http://dali.tanke756.top/Article/details/gtvnsgttpu.html

read -rp "请输入: " ans
来源：http://dali.yj202588.top/Article/details/gtbksldmbk.html

[R78] 交互式菜单
来源：http://dali.jyoumei.cn/Article/details/gtgzseauip.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xziqi.cn/Article/details/gtdpkzqley.html

[R79] 解析命令行选项
来源：http://dali.zhengqikj.top/Article/details/gtgltblopi.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yangfankeji.com/Article/details/gtmtmiugbd.html

[R80] 查看脚本执行耗时
来源：http://dali.ehwqpu.com/Article/details/gtjzjllmct.html

time ./run.sh
来源：http://dali.aibaodan.cn/Article/details/gthpudaalz.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtxkxxbdsr.html

S. C / C++ 专题
来源：http://dali.hnqzz.top/Article/details/gtatficgzc.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtgmqmutdh.html

[S01] C：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtowvleclv.html

#include <stdio.h>
来源：http://dali.chenlongwang.top/Article/details/gtxnvfkqws.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gogol.net.cn/Article/details/gtmgokjbiu.html

[S02] C：变量与格式化输出
来源：http://dali.aibaodan.cn/Article/details/gtiwwvapwm.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhixingplan.top/Article/details/gtogdxztmg.html

[S03] C：读入整数
来源：http://dali.ybcxt.top/Article/details/gtlpcqocvl.html

int x; scanf("%d", &x);
来源：http://dali.fzhhl.top/Article/details/gtxkpjzbsj.html

[S04] C：字符串复制
来源：http://dali.cqqwz.cn/Article/details/gtmrksaldp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.sysykeji.top/Article/details/gtnzjhfdnu.html

[S05] C：字符串长度
来源：http://dali.shuidangran.top/Article/details/gtpkdrpvbr.html

strlen(s)
来源：http://dali.wangdashe.top/Article/details/gtvhvgztid.html

[S06] C：字符串比较
来源：http://dali.jiagoushi.top/Article/details/gtbvfknwqi.html

strcmp(a, b) == 0
来源：http://dali.gotoacloud.top/Article/details/gtagqmoiyo.html

[S07] C：数组遍历求和
来源：http://dali.cucudq.cn/Article/details/gtgehxdxsu.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.haohaochexian.top/Article/details/gtqvxrbsur.html

[S08] C：动态内存分配与释放
来源：http://dali.dashuyun.cn/Article/details/gtftcwhesn.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zdqjudy.top/Article/details/gtfcyuarcv.html

[S09] C：结构体定义与初始化
来源：http://dali.shanyushiyangkeji.top/Article/details/gttgdmyhvx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xylfe.cn/Article/details/gthsbhakvx.html

[S10] C：指针与解引用
来源：http://dali.chenlongwang.top/Article/details/gtacbjnlkc.html

int *p = &a;  *p = 5;
来源：http://dali.cdnleiting.top/Article/details/gtkmcnjwwy.html

[S11] C：逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gtaancpbdp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.tian-w.cn/Article/details/gtftuavwym.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yangfankeji.com/Article/details/gtgabmcjtp.html

fclose(f);
来源：http://dali.tian-w.cn/Article/details/gttyroighe.html

[S12] C：写文件
来源：http://dali.redwolf501.top/Article/details/gtqvrzckwi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.fengsongda.top/Article/details/gtrjxykceo.html

[S13] C：宏定义
来源：http://dali.yangfankeji.com/Article/details/gtrqhjglgr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.svipenyu.cn/Article/details/gttxdujitf.html

[S14] C：枚举
来源：http://dali.gaohongyu789.top/Article/details/gtybfwohht.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.andypj.xyz/Article/details/gtiqxfavqa.html

[S15] C：类型转换
来源：http://dali.redwolf501.top/Article/details/gtibirqjew.html

(double) a / b
来源：http://dali.daria6918.cn/Article/details/gtnjcotirs.html

[S16] C：位操作置位
来源：http://dali.cashguo.top/Article/details/gtwwbpvrpc.html

x |= (1 << 3);
来源：http://dali.nanxinkj.top/Article/details/gtvvwnlyac.html

[S17] C：安全拼接字符串
来源：http://dali.yj202588.top/Article/details/gtnpjkvmoa.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.wangshuangyany.cn/Article/details/gtvlohgumq.html

[S18] C：命令行参数
来源：http://dali.tanke756.top/Article/details/gttqdqydnc.html

int main(int argc, char **argv)
来源：http://dali.316326.xyz/Article/details/gtblzbvptc.html

[S19] C：快速排序
来源：http://dali.sxryk.cn/Article/details/gtrssgtutg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhixingplan.top/Article/details/gtnezkjqjs.html

[S20] C：二分查找
来源：http://dali.hongshengwenyu.top/Article/details/gtbxpfpliw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gtgtudibww.html

[S21] C：字符类别判断
来源：http://dali.0kj1m.cn/Article/details/gtxnpnnwie.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.pengpengdd.cyou/Article/details/gtftobbuww.html

[S22] C：字符串转数字
来源：http://dali.gaohongyu789.top/Article/details/gttfzhddds.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.fengsongda.top/Article/details/gtcaxkzwth.html

[S23] C：随机数
来源：http://dali.cdnleiting.top/Article/details/gtfuvxnjfu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.daxiang520.top/Article/details/gtqyqjmbal.html

[S24] C：获取本地时间
来源：http://dali.shanyushiyangtech.top/Article/details/gtzjkaqedg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yuxming.cn/Article/details/gtcuihvnjk.html

[S25] C：内存拷贝
来源：http://dali.ehwqpu.com/Article/details/gtzlsbdouj.html

memcpy(dst, src, n);
来源：http://dali.aizwys.cn/Article/details/gtbbbgshik.html

[S26] C：内存清零
来源：http://dali.iojbl.cn/Article/details/gtteefumnj.html

memset(a, 0, sizeof a);
来源：http://dali.hywenlv.cn/Article/details/gtyjvnmzth.html

[S27] C：定义常量
来源：http://dali.hammf.cn/Article/details/gtuvbkhwuk.html

const double PI = 3.14159;
来源：http://dali.xuanzx.com/Article/details/gtmmxvjrsy.html

[S28] C：静态变量
来源：http://dali.jlsjyb.cn/Article/details/gtbwizsyhv.html

static int counter = 0;
来源：http://dali.meibo888.top/Article/details/gtsrmgnrol.html

[S29] C：变参函数
来源：http://dali.daxiang520.top/Article/details/gtrqarpelf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sxryk.cn/Article/details/gtifbjwcjr.html

[S30] C：头文件保护
来源：http://dali.svipenyu.cn/Article/details/gtrkereyjm.html

#ifndef X_H
来源：http://dali.yj20258888.top/Article/details/gtrdbctigq.html

#define X_H
来源：http://dali.ehwqpu.com/Article/details/gtewzzkjni.html

#endif
来源：http://dali.kuanghao11.cn/Article/details/gtmjrufcbf.html

[S31] C++：Hello World
来源：http://dali.jinqigfzy.top/Article/details/gtwqwydxzu.html

#include <iostream>
来源：http://dali.ydzc1.top/Article/details/gtxbyeyzsa.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sweek.top/Article/details/gtvzvhibar.html

[S32] C++：字符串
来源：http://dali.meibo888.top/Article/details/gtrvujutmu.html

std::string s = "hi";  s += "!";
来源：http://dali.dianchejie.cn/Article/details/gtyrosonid.html

[S33] C++：vector 增删
来源：http://dali.hongshengwenyu.top/Article/details/gtmqcawkyf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.fengsongda.top/Article/details/gtzkhxjxht.html

[S34] C++：遍历 vector
来源：http://dali.pengpengdd.cyou/Article/details/gtdhlcldge.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jyoumei.cn/Article/details/gtugndsbgb.html

[S35] C++：map
来源：http://dali.yuxming.cn/Article/details/gtivnkirpj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gtclytohxb.html

[S36] C++：unordered_map
来源：http://dali.meibo888.top/Article/details/gtrvykopsc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.havefunace.top/Article/details/gtwfifnpov.html

[S37] C++：set
来源：http://dali.tianlin.xyz/Article/details/gtzguwohmn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.chenlongwang.top/Article/details/gtvbyndqqn.html

[S38] C++：排序
来源：http://dali.hywenlv.cn/Article/details/gtcabpfrfd.html

std::sort(v.begin(), v.end());
来源：http://dali.guannengcc.top/Article/details/gttcjiwxac.html

[S39] C++：自定义比较器排序
来源：http://dali.xuanzx.com/Article/details/gtvhglrkel.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdnehduex.html

[S40] C++：查找元素
来源：http://dali.tanke756.top/Article/details/gtirchtbnq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.nanxuanxn.top/Article/details/gtyozeidsb.html

[S41] C++：类与构造函数
来源：http://dali.xziqi.cn/Article/details/gtnomgbbgs.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cashguo.top/Article/details/gtvidgltpd.html

[S42] C++：继承与虚函数
来源：http://dali.andypj.xyz/Article/details/gtbsqylswi.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinqigufen.top/Article/details/gtzgusyzwf.html

[S43] C++：智能指针
来源：http://dali.hongshengwenyu.top/Article/details/gtunmssjrr.html

auto p = std::make_unique<int>(5);
来源：http://dali.hysaishi.cn/Article/details/gtzdytzchu.html

[S44] C++：引用传参
来源：http://dali.ppjwa.cn/Article/details/gtpuyahxcc.html

void inc(int &x) { ++x; }
来源：http://dali.chenlongwang.top/Article/details/gtxxcljthq.html

[S45] C++：lambda
来源：http://dali.cheryme.top/Article/details/gtnupikxzl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.fengsongda.top/Article/details/gtnkesfwuj.html

[S46] C++：函数模板
来源：http://dali.zycfv.cn/Article/details/gtteymkfpj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yj20258.top/Article/details/gtsqafeese.html

[S47] C++：结构化绑定遍历
来源：http://dali.ybcxt.top/Article/details/gtxrswsqws.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.bjfxy.top/Article/details/gtybrcvkns.html

[S48] C++：逐行读文件
来源：http://dali.ivvv.top/Article/details/gtxaeemkqk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.chenlongwang.top/Article/details/gtoosnoslv.html

while (std::getline(in, line)) { }
来源：http://dali.jianghu66.top/Article/details/gtumlbddyj.html

[S49] C++：写文件
来源：http://dali.ydzc1.top/Article/details/gtuhflzlod.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.pengpengdd.cyou/Article/details/gthdizogzr.html

[S50] C++：格式化数字
来源：http://dali.hnqzz.top/Article/details/gtbfveorms.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xinyue.icu/Article/details/gttjzlrktu.html

[S51] C++：显式类型转换
来源：http://dali.zhoulong.xyz/Article/details/gtkhrqcibn.html

static_cast<double>(a) / b
来源：http://dali.9152youxi.cn/Article/details/gtpvcguxnb.html

[S52] C++：const 与 noexcept
来源：http://dali.yvedp.cn/Article/details/gtzyyjfhvq.html

int size() const noexcept { return n_; }
来源：http://dali.hywenlv.cn/Article/details/gtjnitszib.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gtirxtlwhj.html

std::vector<int> w = std::move(v);
来源：http://dali.haohaochexian.top/Article/details/gtckaxtgsx.html

[S54] C++：异常处理
来源：http://dali.ehwqpu.com/Article/details/gtzzbsbxwv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnlieeeqe.html

[S55] C++：结构化绑定
来源：http://dali.shangyingyoupin.top/Article/details/gtrfyzqmgx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yangfankeji.com/Article/details/gtjfklzqbn.html

[S56] C++：optional
来源：http://dali.shzxlz.cn/Article/details/gtesxsjtvs.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jianghu66.top/Article/details/gtdficmcfe.html

[S57] C++：编译期常量
来源：http://dali.pycfn.com/Article/details/gtbcghmbyu.html

constexpr int N = 10;
来源：http://dali.guannengcc.top/Article/details/gtdqafxhdt.html

[S58] C++：命名空间
来源：http://dali.andypj.xyz/Article/details/gtazfixwls.html

namespace ns { int f() { return 1; } }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjpdvuzfm.html

[S59] C++：静态断言
来源：http://dali.fengsongda.top/Article/details/gtxrxwxpaw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xinyue.icu/Article/details/gtpasntvxo.html

[S60] C++：遍历并删除元素
来源：http://dali.shanyushiyangtech.top/Article/details/gtpahlovye.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gzhubu.top/Article/details/gtacapmxkp.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtccotgqsq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gtrufsumjf.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtlsdicpau.html

[T01] Kotlin：Hello World
来源：http://dali.cashguo.top/Article/details/gtltzoneko.html

println("Hello")
来源：http://dali.shzxlz.cn/Article/details/gtccpuvwyc.html

[T02] Kotlin：变量
来源：http://dali.yj202588.top/Article/details/gtwgnetoje.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.sweek.top/Article/details/gtlvtetxsw.html

[T03] Kotlin：字符串模板
来源：http://dali.jinghuilouyu.cn/Article/details/gtbzkxaqjx.html

"值: $b"
来源：http://dali.cdnleiting.top/Article/details/gthgnrvmet.html

[T04] Kotlin：空安全
来源：http://dali.hfpthk.cn/Article/details/gtpbemllvt.html

val n: String? = null;  n?.length
来源：http://dali.zhongyouzk.top/Article/details/gtgyujayci.html

[T05] Kotlin：when 表达式
来源：http://dali.ydzc1.top/Article/details/gtbjzvangm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.gzhubu.top/Article/details/gtnslkjhwo.html

[T06] Kotlin：集合映射
来源：http://dali.sweek.top/Article/details/gtkwekovff.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cashguo.top/Article/details/gteaxaidig.html

[T07] Kotlin：集合过滤
来源：http://dali.wangdashe.top/Article/details/gtyhmvqlgs.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hnqzz.top/Article/details/gtlqszehkp.html

[T08] Kotlin：数据类
来源：http://dali.fzhhl.top/Article/details/gtwezdcjgy.html

data class User(val name: String, val age: Int)
来源：http://dali.redwolf501.top/Article/details/gtydjsvmfr.html

[T09] Kotlin：扩展函数
来源：http://dali.xylfe.cn/Article/details/gthordskjj.html

fun String.exclaim() = this + "!"
来源：http://dali.0kj1m.cn/Article/details/gtpwbkjfun.html

[T10] Kotlin：默认参数
来源：http://dali.hnqzz.top/Article/details/gtnsgmshms.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.feifeiyinyue.top/Article/details/gturmfoghh.html

[T11] Kotlin：协程
来源：http://dali.jqgfzy.top/Article/details/gtxuuyjkbc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.haohaochexian.top/Article/details/gttclcrryu.html

[T12] Kotlin：解构声明
来源：http://dali.jyoumei.cn/Article/details/gtlswxgksa.html

val (a, b) = Pair(1, 2)
来源：http://dali.sysykeji.top/Article/details/gtfymqbmmv.html

[T13] Kotlin：只读 Map
来源：http://dali.sufxvd.cn/Article/details/gtcfhizstt.html

val m = mapOf("a" to 1)
来源：http://dali.iojbl.cn/Article/details/gtqpykqfwy.html

[T14] Kotlin：循环
来源：http://dali.xziqi.cn/Article/details/gtttmyzuts.html

for (i in 1..10) println(i)
来源：http://dali.shangyingyoupin.top/Article/details/gtyemvhmhg.html

[T15] Kotlin：接口
来源：http://dali.cqqwz.cn/Article/details/gtelhbheut.html

interface Shape { fun area(): Double }
来源：http://dali.shuidangran.top/Article/details/gtuyhvvmqe.html

[T16] Swift：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtaxbhagmj.html

print("Hello")
来源：http://dali.dianchejie.cn/Article/details/gtehooebdo.html

[T17] Swift：变量与常量
来源：http://dali.zdqjudy.top/Article/details/gtifttbjok.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gtvjlhjxpy.html

[T18] Swift：字符串插值
来源：http://dali.zycfv.cn/Article/details/gtledhmpcd.html

"值: \(b)"
来源：http://dali.jinqigufen.top/Article/details/gtkkosjfhp.html

[T19] Swift：可选绑定
来源：http://dali.iojbl.cn/Article/details/gthhczfyww.html

if let n = opt { print(n) }
来源：http://dali.ybcxt.top/Article/details/gtxhvnkxfa.html

[T20] Swift：数组操作
来源：http://dali.snrcjt.cn/Article/details/gtwxymhsnc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jianghu66.top/Article/details/gtenttzbgq.html

[T21] Swift：遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwmylccoj.html

for x in a { print(x) }
来源：http://dali.gzhubu.top/Article/details/gtxsrdorpw.html

[T22] Swift：字典
来源：http://dali.shzxlz.cn/Article/details/gtbdoylzdj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.tianlin.xyz/Article/details/gtxgdhxghb.html

[T23] Swift：函数
来源：http://dali.hnxiangtu.top/Article/details/gtdnkvqbne.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.mhx1999.top/Article/details/gthgspafdj.html

[T24] Swift：闭包
来源：http://dali.meibo888.top/Article/details/gtxjrmvewa.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.smart0.xyz/Article/details/gtccwacygu.html

[T25] Swift：结构体
来源：http://dali.xuanzx.com/Article/details/gtyipljdqp.html

struct P { var x: Int }
来源：http://dali.haohaochexian.top/Article/details/gtsbfyyjhb.html

[T26] Swift：类与重写
来源：http://dali.chenjidiqi.icu/Article/details/gtrpvwgkhm.html

class A: Base { override func f() {} }
来源：http://dali.havefunace.top/Article/details/gtcuvmnjcj.html

[T27] Swift：错误处理
来源：http://dali.wangdashe.top/Article/details/gtolirbzeq.html

do { try f() } catch { print(error) }
来源：http://dali.cashguo.top/Article/details/gtuzrhbjra.html

[T28] Swift：枚举
来源：http://dali.havefunace.top/Article/details/gtmmutyayb.html

enum Color { case red, green }
来源：http://dali.havefunace.top/Article/details/gtjeckuibh.html

[T29] Swift：guard 提前返回
来源：http://dali.yj202588.top/Article/details/gtiqionojg.html

guard let x = opt else { return }
来源：http://dali.vqdsnc.cn/Article/details/gtufijpeat.html

[T30] Swift：协议
来源：http://dali.daxiang520.top/Article/details/gtqmieaovk.html

protocol Shape { func area() -> Double }
来源：http://dali.sysykeji.top/Article/details/gtxpaaniwp.html

[T31] Lua：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtgcrwxqfo.html

print("Hello")
来源：http://dali.yongpay.top/Article/details/gtecqfwjds.html

[T32] Lua：局部变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtegjrglgm.html

local a = 1
来源：http://dali.yongpay.top/Article/details/gthqudvaxg.html

[T33] Lua：表（数组）
来源：http://dali.iojbl.cn/Article/details/gtjhkkcpuk.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hfpthk.cn/Article/details/gturgyhyqp.html

[T34] Lua：遍历表
来源：http://dali.c1oappe.top/Article/details/gtajpfjvbm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yvedp.cn/Article/details/gtnwhnmzfa.html

[T35] Lua：字典表
来源：http://dali.nanxuanxn.top/Article/details/gtgiqffhfa.html

local d = { a = 1 };  d.b = 2
来源：http://dali.daria6918.cn/Article/details/gtbkldciys.html

[T36] Lua：函数
来源：http://dali.feifeiyinyue.top/Article/details/gttxrjltca.html

function add(a, b) return a + b end
来源：http://dali.ydzc1.top/Article/details/gtfthgxesi.html

[T37] Lua：字符串拼接
来源：http://dali.gaohongyu789.top/Article/details/gthypjbnsw.html

"a" .. "b"
来源：http://dali.meibo888.top/Article/details/gtwlhkjevn.html

[T38] Lua：条件
来源：http://dali.zhoulong.xyz/Article/details/gtrxgovlup.html

if x > 0 then print("正") end
来源：http://dali.yj202588.top/Article/details/gtbbvtjmld.html


<!-- 参考信息 -->