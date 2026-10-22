代发 wailian999

cmd >/dev/null 2>&1
来源：http://dali.gaohongyu789.top/Article/details/gtwraxmpuj.html

[R42] 输入重定向
来源：http://dali.bjfxy.top/Article/details/gticcucczh.html

wc -l < a.txt
来源：http://dali.ybcxt.top/Article/details/gteejqmoln.html

[R43] 按名字查找文件
来源：http://dali.chenlongwang.top/Article/details/gtrrryymkz.html

find . -name "*.log" -type f
来源：http://dali.andypj.xyz/Article/details/gtjgcsqwuc.html

[R44] 按修改时间查找
来源：http://dali.cdnleiting.top/Article/details/gtvkmkkmxr.html

find . -mtime -7 -type f
来源：http://dali.sweek.top/Article/details/gtmbjcfese.html

[R45] 批量删除
来源：http://dali.tianlin.xyz/Article/details/gtgukzawkq.html

find . -name "*.tmp" -delete
来源：http://dali.shangyingyoupin.top/Article/details/gtnbyncsco.html

[R46] 递归替换文件内容
来源：http://dali.iojbl.cn/Article/details/gtykwmauhu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.vqdsnc.cn/Article/details/gtokwzrdqc.html

[R47] sed 单行替换
来源：http://dali.chenlongwang.top/Article/details/gtkazysisy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.mhx1999.top/Article/details/gthlsreakf.html

[R48] awk 取指定列
来源：http://dali.hywenlv.cn/Article/details/gtgubvpafc.html

awk '{print $1, $3}' a.txt
来源：http://dali.smart0.xyz/Article/details/gtthpezofj.html

[R49] awk 带条件
来源：http://dali.yj202588.top/Article/details/gtioamklmf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhixingplan.top/Article/details/gtzpdkstme.html

[R50] awk 求和
来源：http://dali.nanxuanxn.top/Article/details/gtaeeoixwb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yuanzhike.top/Article/details/gtedwrpdxa.html

[R51] 排序去重取前几
来源：http://dali.cucudq.cn/Article/details/gtqqhrnuax.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ivvv.top/Article/details/gtuwsvqlvi.html

[R52] 统计行数
来源：http://dali.zhixingplan.top/Article/details/gtoazzjvym.html

wc -l a.txt
来源：http://dali.xziqi.cn/Article/details/gtunihoash.html

[R53] 查看文件头与实时尾
来源：http://dali.sxryk.cn/Article/details/gtunyyzdxq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.sxryk.cn/Article/details/gtwmtzxtzc.html

[R54] 比较两个文件
来源：http://dali.jinqigufen.top/Article/details/gttggdqunc.html

diff a.txt b.txt
来源：http://dali.fengsongda.top/Article/details/gtjfgakevx.html

[R55] 压缩与解压
来源：http://dali.hnxiangtu.top/Article/details/gtdepjcamq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jianghu66.top/Article/details/gtrhxfshth.html

[R56] 远程拷贝
来源：http://dali.shuidangran.top/Article/details/gtudgvybtb.html

scp file user@host:/path/
来源：http://dali.cqqwz.cn/Article/details/gtfmwyjelu.html

[R57] 远程执行命令
来源：http://dali.tian-w.cn/Article/details/gtefljpfmx.html

ssh user@host 'uptime'
来源：http://dali.dianchejie.cn/Article/details/gtmdprrltr.html

[R58] 下载文件
来源：http://dali.9152youxi.cn/Article/details/gtubxwrzxh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.aizwys.cn/Article/details/gtwelqtclx.html

[R59] 发 POST JSON
来源：http://dali.yuanzhike.top/Article/details/gtbucrbzid.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhixingplan.top/Article/details/gtwixrzggl.html

[R60] 只看 HTTP 状态码
来源：http://dali.yj202588.top/Article/details/gtcpoxfpnz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.aibaodan.cn/Article/details/gtbxiscbnd.html

[R61] 磁盘占用
来源：http://dali.snrcjt.cn/Article/details/gtlnmgixvc.html

df -h;  du -sh *
来源：http://dali.yj20258888.top/Article/details/gtxbyprvgd.html

[R62] 找最占空间的文件
来源：http://dali.tianlin.xyz/Article/details/gtyhjnmmxy.html

du -ah . | sort -rh | head -10
来源：http://dali.wangdashe.top/Article/details/gtsjpczjjw.html

[R63] 内存与进程
来源：http://dali.zycfv.cn/Article/details/gtwrkfjfvl.html

free -h;  ps aux | grep nginx
来源：http://dali.9152youxi.cn/Article/details/gtglphgosa.html

[R64] 结束进程
来源：http://dali.zhiwuduotai.top/Article/details/gthaymqchk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.daxiang520.top/Article/details/gtkbahygml.html

[R65] 查看端口占用
来源：http://dali.jinqigufen.top/Article/details/gtmcdjebpy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cheryme.top/Article/details/gtjshubblq.html

[R66] 定时任务
来源：http://dali.jinqigufen.top/Article/details/gtntkhmlbq.html

crontab -e;  crontab -l
来源：http://dali.yj20258888.top/Article/details/gtpoaeqsma.html

[R67] 生成随机十六进制串
来源：http://dali.tianlin.xyz/Article/details/gtsmdfoiud.html

openssl rand -hex 16
来源：http://dali.daxiang520.top/Article/details/gthhanslac.html

[R68] 计算文件校验值
来源：http://dali.zhiwuduotai.top/Article/details/gtcupallsk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtzadqnjdt.html

[R69] 生成随机密码
来源：http://dali.dianchejie.cn/Article/details/gtjtatxzss.html

head -c 16 /dev/urandom | base64
来源：http://dali.sxryk.cn/Article/details/gtawpgjxmb.html

[R70] 时间戳与互转
来源：http://dali.pengpengdd.cyou/Article/details/gtyhizlruf.html

date +%s;  date -d @1700000000
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcgagdhhf.html

[R71] 日期格式化
来源：http://dali.ehwqpu.com/Article/details/gtatyaskvv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.haohaochexian.top/Article/details/gtzeqwwbtk.html

[R72] 等待端口就绪
来源：http://dali.zhoulong.xyz/Article/details/gtnuhibmrv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ppjwa.cn/Article/details/gtzuqrkghu.html

[R73] 分割大日志
来源：http://dali.zhengqikj.top/Article/details/gtszctgpdj.html

split -l 1000 big.log part_
来源：http://dali.ywan-chungtsiang.top/Article/details/gtowsnyfja.html

[R74] 批量重命名
来源：http://dali.guowangkeji.top/Article/details/gtlmmsihuq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.quarkkingdee.top/Article/details/gtguanlctt.html

[R75] 导出环境变量
来源：http://dali.nanxuanxn.top/Article/details/gtfgoaoaoj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jinqigfzy.top/Article/details/gtrdnjlnew.html

[R76] 使用临时文件
来源：http://dali.chenjidiqi.icu/Article/details/gtjsjxghve.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sysykeji.top/Article/details/gtxqygacgy.html

[R77] 读取用户输入
来源：http://dali.sxryk.cn/Article/details/gtuzjedmyg.html

read -rp "请输入: " ans
来源：http://dali.jyoumei.cn/Article/details/gtpypxikgf.html

[R78] 交互式菜单
来源：http://dali.jianghu66.top/Article/details/gtwomnwhcc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jianghu66.top/Article/details/gtjqtogdwb.html

[R79] 解析命令行选项
来源：http://dali.jianghu66.top/Article/details/gtzrnuyjkr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yueranfly.top/Article/details/gtfkidimyo.html

[R80] 查看脚本执行耗时
来源：http://dali.zdqjudy.top/Article/details/gtuzgkfzzr.html

time ./run.sh
来源：http://dali.sufxvd.cn/Article/details/gtsgsikxgo.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtclorgswn.html

S. C / C++ 专题
来源：http://dali.gotoacloud.top/Article/details/gttchzyaru.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpodohmnl.html

[S01] C：Hello World
来源：http://dali.nwbrower.top/Article/details/gtheyjxgqs.html

#include <stdio.h>
来源：http://dali.smart0.xyz/Article/details/gtucubagqs.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yj202588.top/Article/details/gtmryetbtu.html

[S02] C：变量与格式化输出
来源：http://dali.shanyushiyangtech.top/Article/details/gtxbpurrgh.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhiwuduotai.top/Article/details/gtlhagvplr.html

[S03] C：读入整数
来源：http://dali.zhengqikj.top/Article/details/gtszcgsowm.html

int x; scanf("%d", &x);
来源：http://dali.9152youxi.cn/Article/details/gtfkffndfm.html

[S04] C：字符串复制
来源：http://dali.xuanzx.com/Article/details/gtxtquvnhr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shangyingyoupin.top/Article/details/gtcoqsgfqf.html

[S05] C：字符串长度
来源：http://dali.birdmap.top/Article/details/gtydpisnvy.html

strlen(s)
来源：http://dali.jinqigfzy.top/Article/details/gtchrvsblr.html

[S06] C：字符串比较
来源：http://dali.nanxuanxn.top/Article/details/gtavvgyimo.html

strcmp(a, b) == 0
来源：http://dali.sweek.top/Article/details/gtkwhwttjl.html

[S07] C：数组遍历求和
来源：http://dali.xziqi.cn/Article/details/gtocefywzs.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.ydzc1.top/Article/details/gtybvtbbig.html

[S08] C：动态内存分配与释放
来源：http://dali.hysaishi.cn/Article/details/gtetmnsbvc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gzhubu.top/Article/details/gttbwgcgcp.html

[S09] C：结构体定义与初始化
来源：http://dali.xinyue.icu/Article/details/gtrzzofeev.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ybcxt.top/Article/details/gtrkowebyf.html

[S10] C：指针与解引用
来源：http://dali.hongshengwenyu.top/Article/details/gtyojddwct.html

int *p = &a;  *p = 5;
来源：http://dali.hfpthk.cn/Article/details/gtjzudmrll.html

[S11] C：逐行读文件
来源：http://dali.tian-w.cn/Article/details/gtjtdnyiec.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yuxming.cn/Article/details/gtgopanfba.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ybcxt.top/Article/details/gtrboienez.html

fclose(f);
来源：http://dali.cashguo.top/Article/details/gtbgwizbdv.html

[S12] C：写文件
来源：http://dali.zhoulong.xyz/Article/details/gtoldukgrs.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xziqi.cn/Article/details/gtnvuwvklj.html

[S13] C：宏定义
来源：http://dali.nanxuanxn.top/Article/details/gtsryudzik.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hongshengwenyu.top/Article/details/gtcqcwbsza.html

[S14] C：枚举
来源：http://dali.shangyingyoupin.top/Article/details/gtbpdihwrb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yanxiufei.cn/Article/details/gtzbfujgzn.html

[S15] C：类型转换
来源：http://dali.kuanghao11.cn/Article/details/gtplwkpckq.html

(double) a / b
来源：http://dali.aizwys.cn/Article/details/gtuuudofyl.html

[S16] C：位操作置位
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlfauadpp.html

x |= (1 << 3);
来源：http://dali.meibo888.top/Article/details/gtkntexufa.html

[S17] C：安全拼接字符串
来源：http://dali.quarkkingdee.top/Article/details/gtqlszbnne.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.316326.xyz/Article/details/gtmfhepqzk.html

[S18] C：命令行参数
来源：http://dali.tian-w.cn/Article/details/gtddnveuag.html

int main(int argc, char **argv)
来源：http://dali.shanyushiyangtech.top/Article/details/gtthpmgnak.html

[S19] C：快速排序
来源：http://dali.shuidangran.top/Article/details/gtylmbdgwm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.nanxinkj.top/Article/details/gtmteodxcy.html

[S20] C：二分查找
来源：http://dali.sxryk.cn/Article/details/gtnbhhkvdm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.aibaodan.cn/Article/details/gtuakvkmwn.html

[S21] C：字符类别判断
来源：http://dali.haohaochexian.top/Article/details/gtzrvlvsdh.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xuetiantiany.cn/Article/details/gtpszxoptk.html

[S22] C：字符串转数字
来源：http://dali.zhiwuduotai.top/Article/details/gtfwgzanvk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.sweek.top/Article/details/gthbqztpqt.html

[S23] C：随机数
来源：http://dali.zhoulong.xyz/Article/details/gtqdwtkqyp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.aizwys.cn/Article/details/gtolhmpcpw.html

[S24] C：获取本地时间
来源：http://dali.yuxming.cn/Article/details/gtfpxybjxo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinqigufen.top/Article/details/gtxdxpofkq.html

[S25] C：内存拷贝
来源：http://dali.guannengcc.top/Article/details/gtzduxrndy.html

memcpy(dst, src, n);
来源：http://dali.c1oappe.top/Article/details/gtdqbydsnk.html

[S26] C：内存清零
来源：http://dali.ybcxt.top/Article/details/gtexdprtpd.html

memset(a, 0, sizeof a);
来源：http://dali.feifeiyinyue.top/Article/details/gtuviehoxl.html

[S27] C：定义常量
来源：http://dali.c1oappe.top/Article/details/gtlgpofize.html

const double PI = 3.14159;
来源：http://dali.dianchejie.cn/Article/details/gtpmmocqam.html

[S28] C：静态变量
来源：http://dali.daxiang520.top/Article/details/gtwkcnliuj.html

static int counter = 0;
来源：http://dali.andypj.xyz/Article/details/gtncpifqeh.html

[S29] C：变参函数
来源：http://dali.vqdsnc.cn/Article/details/gtelvbamcq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.quarkkingdee.top/Article/details/gtjxnqgjxh.html

[S30] C：头文件保护
来源：http://dali.yongpay.top/Article/details/gtmrostsll.html

#ifndef X_H
来源：http://dali.cdnleiting.top/Article/details/gtpcmjjsqi.html

#define X_H
来源：http://dali.chenjidiqi.icu/Article/details/gtvqshsjpy.html

#endif
来源：http://dali.kuanghao11.cn/Article/details/gtvcfkcujd.html

[S31] C++：Hello World
来源：http://dali.meibo888.top/Article/details/gtytepcqpa.html

#include <iostream>
来源：http://dali.hfpthk.cn/Article/details/gtygghmsdm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.pycfn.com/Article/details/gtndmfztbp.html

[S32] C++：字符串
来源：http://dali.0kj1m.cn/Article/details/gtissviqht.html

std::string s = "hi";  s += "!";
来源：http://dali.zhoulong.xyz/Article/details/gtgdscdrko.html

[S33] C++：vector 增删
来源：http://dali.zhoulong.xyz/Article/details/gtkfsezwmy.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.birdmap.top/Article/details/gtennlpitx.html

[S34] C++：遍历 vector
来源：http://dali.jianghu66.top/Article/details/gtzlrnezaf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.sysykeji.top/Article/details/gtsrglixmf.html

[S35] C++：map
来源：http://dali.9152youxi.cn/Article/details/gtupcgatbw.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yvedp.cn/Article/details/gtnqfbdzhm.html

[S36] C++：unordered_map
来源：http://dali.jyoumei.cn/Article/details/gtpwsjpsgn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gogol.net.cn/Article/details/gtmkeosoqt.html

[S37] C++：set
来源：http://dali.fzhhl.top/Article/details/gtegamqqkf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ppjwa.cn/Article/details/gtriethshp.html

[S38] C++：排序
来源：http://dali.xinyue.icu/Article/details/gtypgmdwbd.html

std::sort(v.begin(), v.end());
来源：http://dali.cqqwz.cn/Article/details/gtidkoqmgi.html

[S39] C++：自定义比较器排序
来源：http://dali.chenjidiqi.icu/Article/details/gttcsapiew.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.birdmap.top/Article/details/gtpqvhmnzy.html

[S40] C++：查找元素
来源：http://dali.cashguo.top/Article/details/gtahbfdnzu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.wangdashe.top/Article/details/gtbblieswu.html

[S41] C++：类与构造函数
来源：http://dali.pycfn.com/Article/details/gtcscsuewg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.nwbrower.top/Article/details/gteixzmsec.html

[S42] C++：继承与虚函数
来源：http://dali.redwolf501.top/Article/details/gtbhgjzifd.html

class B : public Base { public: void f() override {} };
来源：http://dali.yanxiufei.cn/Article/details/gtgfaskzej.html

[S43] C++：智能指针
来源：http://dali.sysykeji.top/Article/details/gtamfdrrgm.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinghuilouyu.cn/Article/details/gtsswjaqmn.html

[S44] C++：引用传参
来源：http://dali.gotoacloud.top/Article/details/gtaboondnd.html

void inc(int &x) { ++x; }
来源：http://dali.iojbl.cn/Article/details/gtsmnzvral.html

[S45] C++：lambda
来源：http://dali.yvedp.cn/Article/details/gtkcwvzhqy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhijiandao.cn/Article/details/gtkskhqdpj.html

[S46] C++：函数模板
来源：http://dali.gotoacloud.top/Article/details/gtadbxfsjt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.redwolf501.top/Article/details/gtwkztdegf.html

[S47] C++：结构化绑定遍历
来源：http://dali.cheryme.top/Article/details/gtvzkkzogf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xziqi.cn/Article/details/gtjgrlxwhs.html

[S48] C++：逐行读文件
来源：http://dali.yueranfly.top/Article/details/gtpnnfrqow.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shzxlz.cn/Article/details/gtmbpiptnz.html

while (std::getline(in, line)) { }
来源：http://dali.tanke756.top/Article/details/gtocpiguol.html

[S49] C++：写文件
来源：http://dali.ppjwa.cn/Article/details/gtirkpagel.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.pycfn.com/Article/details/gtylfnsrxv.html

[S50] C++：格式化数字
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtluwbyblw.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hnxiangtu.top/Article/details/gtrlnybsas.html

[S51] C++：显式类型转换
来源：http://dali.shanyushiyangtech.top/Article/details/gttbcvspsj.html

static_cast<double>(a) / b
来源：http://dali.zhixingplan.top/Article/details/gtpfkjthmd.html

[S52] C++：const 与 noexcept
来源：http://dali.cqqwz.cn/Article/details/gtbtklsdhz.html

int size() const noexcept { return n_; }
来源：http://dali.hfpthk.cn/Article/details/gtingcmcti.html

[S53] C++：移动语义
来源：http://dali.jlsjyb.cn/Article/details/gtsfrstekw.html

std::vector<int> w = std::move(v);
来源：http://dali.jyoumei.cn/Article/details/gthawqtlad.html

[S54] C++：异常处理
来源：http://dali.gotoacloud.top/Article/details/gtuctoauew.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gtnaflplwm.html

[S55] C++：结构化绑定
来源：http://dali.yj20258.top/Article/details/gtzimjnlft.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yj202588.top/Article/details/gtunchcohp.html

[S56] C++：optional
来源：http://dali.pycfn.com/Article/details/gtouksgpvx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.havefunace.top/Article/details/gtndtwgzqv.html

[S57] C++：编译期常量
来源：http://dali.hysaishi.cn/Article/details/gtjkpkzuug.html

constexpr int N = 10;
来源：http://dali.dianchejie.cn/Article/details/gtdozztdty.html

[S58] C++：命名空间
来源：http://dali.0kj1m.cn/Article/details/gtvjpojvwp.html

namespace ns { int f() { return 1; } }
来源：http://dali.gotoacloud.top/Article/details/gtvxsgxwgz.html

[S59] C++：静态断言
来源：http://dali.jlsjyb.cn/Article/details/gteifffnjw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxukgowzf.html

[S60] C++：遍历并删除元素
来源：http://dali.jqgufenzy.top/Article/details/gtowhxnifg.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yangfankeji.com/Article/details/gtdjxhybcc.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtxvfscjhs.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.wangdashe.top/Article/details/gtkdssglbf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtodgzjbnj.html

[T01] Kotlin：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtsdosvtio.html

println("Hello")
来源：http://dali.daria6918.cn/Article/details/gtyqafrund.html

[T02] Kotlin：变量
来源：http://dali.cashguo.top/Article/details/gtarhvvxyv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ybcxt.top/Article/details/gtdclidotc.html

[T03] Kotlin：字符串模板
来源：http://dali.gotoacloud.top/Article/details/gtgpxmkqia.html

"值: $b"
来源：http://dali.sysykeji.top/Article/details/gtgvkxbxkv.html

[T04] Kotlin：空安全
来源：http://dali.sysykeji.top/Article/details/gttfedorzg.html

val n: String? = null;  n?.length
来源：http://dali.jiagoushi.top/Article/details/gtnmplduee.html

[T05] Kotlin：when 表达式
来源：http://dali.yanxiufei.cn/Article/details/gtfdmvancd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.andypj.xyz/Article/details/gtowqvjqfu.html

[T06] Kotlin：集合映射
来源：http://dali.guannengcc.top/Article/details/gtbqzntskx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.dashuyun.cn/Article/details/gtnclcdynw.html

[T07] Kotlin：集合过滤
来源：http://dali.zycfv.cn/Article/details/gtdfdvopsh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.quarkkingdee.top/Article/details/gtdrptsjnt.html

[T08] Kotlin：数据类
来源：http://dali.shangyingyoupin.top/Article/details/gtfyvvosik.html

data class User(val name: String, val age: Int)
来源：http://dali.hnxiangtu.top/Article/details/gtsyqbwilp.html

[T09] Kotlin：扩展函数
来源：http://dali.quarkkingdee.top/Article/details/gtnddpcxkl.html

fun String.exclaim() = this + "!"
来源：http://dali.ehwqpu.com/Article/details/gtbxfdbgtr.html

[T10] Kotlin：默认参数
来源：http://dali.hongshengwenyu.top/Article/details/gtcbigsfxd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shzxlz.cn/Article/details/gtpifdenvh.html

[T11] Kotlin：协程
来源：http://dali.jqgufenzy.top/Article/details/gtqejwgsug.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhiwuduotai.top/Article/details/gtzqnvmvtn.html

[T12] Kotlin：解构声明
来源：http://dali.cdnleiting.top/Article/details/gtaldoafuo.html

val (a, b) = Pair(1, 2)
来源：http://dali.daxiang520.top/Article/details/gtvydnvotc.html

[T13] Kotlin：只读 Map
来源：http://dali.wangshuangyany.cn/Article/details/gtcsspzagi.html

val m = mapOf("a" to 1)
来源：http://dali.ehwqpu.com/Article/details/gteigicyem.html

[T14] Kotlin：循环
来源：http://dali.tianlin.xyz/Article/details/gtweewwjjr.html

for (i in 1..10) println(i)
来源：http://dali.sxryk.cn/Article/details/gtdlajgjya.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gtghqxybkc.html

interface Shape { fun area(): Double }
来源：http://dali.zhengqikj.top/Article/details/gtcsudstgm.html

[T16] Swift：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtkapfnhqw.html

print("Hello")
来源：http://dali.zdqjudy.top/Article/details/gtpqggsdzz.html

[T17] Swift：变量与常量
来源：http://dali.cqqwz.cn/Article/details/gtwiazaubo.html

var a = 1;  let b = 2
来源：http://dali.mhx1999.top/Article/details/gtelcoytlk.html

[T18] Swift：字符串插值
来源：http://dali.yonumen.top/Article/details/gtxexicshj.html

"值: \(b)"
来源：http://dali.zhixingplan.top/Article/details/gtwmdecjcs.html

[T19] Swift：可选绑定
来源：http://dali.aizwys.cn/Article/details/gtyiysysmk.html

if let n = opt { print(n) }
来源：http://dali.xuanzx.com/Article/details/gttbzzdzlq.html

[T20] Swift：数组操作
来源：http://dali.meibo888.top/Article/details/gtktotjcva.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yuanzhike.top/Article/details/gturoprwtj.html

[T21] Swift：遍历
来源：http://dali.meibo888.top/Article/details/gtbuxgojbp.html

for x in a { print(x) }
来源：http://dali.jinqigufen.top/Article/details/gtznxuxogj.html

[T22] Swift：字典
来源：http://dali.shangyingyoupin.top/Article/details/gtfxirepdd.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jyoumei.cn/Article/details/gtkwcgbvld.html

[T23] Swift：函数
来源：http://dali.yj202588.top/Article/details/gtlwdjsxeg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zycfv.cn/Article/details/gtaxrumenx.html

[T24] Swift：闭包
来源：http://dali.gzhubu.top/Article/details/gtwxklorqb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkyxtvgqw.html

[T25] Swift：结构体
来源：http://dali.cucudq.cn/Article/details/gtyunmqlhu.html

struct P { var x: Int }
来源：http://dali.shuidangran.top/Article/details/gtsprbhaco.html

[T26] Swift：类与重写
来源：http://dali.zhixingplan.top/Article/details/gteliloifz.html

class A: Base { override func f() {} }
来源：http://dali.jinqigufen.top/Article/details/gtqwbdnisg.html

[T27] Swift：错误处理
来源：http://dali.jinqigufen.top/Article/details/gtizwqaxcm.html

do { try f() } catch { print(error) }
来源：http://dali.yj20258888.top/Article/details/gtalermrgb.html

[T28] Swift：枚举
来源：http://dali.yonumen.top/Article/details/gtapbguzkg.html

enum Color { case red, green }
来源：http://dali.316326.xyz/Article/details/gtdyhcrpxa.html

[T29] Swift：guard 提前返回
来源：http://dali.bjfxy.top/Article/details/gtaklklcpl.html

guard let x = opt else { return }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkkeflsjd.html

[T30] Swift：协议
来源：http://dali.cucudq.cn/Article/details/gtqivspolk.html

protocol Shape { func area() -> Double }
来源：http://dali.daria6918.cn/Article/details/gtsyiovsiq.html

[T31] Lua：Hello World
来源：http://dali.xuanzx.com/Article/details/gtwirinmeu.html

print("Hello")
来源：http://dali.zhijiandao.cn/Article/details/gtxnwhjbqq.html

[T32] Lua：局部变量
来源：http://dali.xylfe.cn/Article/details/gtuxgbnbzk.html

local a = 1
来源：http://dali.kuanghao11.cn/Article/details/gtanrpomzo.html

[T33] Lua：表（数组）
来源：http://dali.smart0.xyz/Article/details/gtnmomuktg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.fengsongda.top/Article/details/gtvgnbljfo.html

[T34] Lua：遍历表
来源：http://dali.yangfankeji.com/Article/details/gtsqjitszo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.redwolf501.top/Article/details/gtzqflgjdo.html

[T35] Lua：字典表
来源：http://dali.fzhhl.top/Article/details/gtuprjryjo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.mhx1999.top/Article/details/gtsjaxaejd.html

[T36] Lua：函数
来源：http://dali.nwbrower.top/Article/details/gtavufndxh.html

function add(a, b) return a + b end
来源：http://dali.yongpay.top/Article/details/gtjlrtwghg.html

[T37] Lua：字符串拼接
来源：http://dali.cdnleiting.top/Article/details/gtznkoawes.html

"a" .. "b"
来源：http://dali.dashuyun.cn/Article/details/gtarjmoebx.html

[T38] Lua：条件
来源：http://dali.nwbrower.top/Article/details/gtrhamltyf.html

if x > 0 then print("正") end
来源：http://dali.cucudq.cn/Article/details/gtpnpzwdib.html

[T39] Lua：模式匹配
来源：http://dali.xinyue.icu/Article/details/gtlbhopceo.html

string.find(s, "%d+")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrldrbnpz.html

[T40] Lua：元表
来源：http://dali.chenzaomai.com/Article/details/gtcfddzpya.html

setmetatable({}, { __index = base })
来源：http://dali.bjfxy.top/Article/details/gtcypzgcth.html

[T41] Perl：Hello World
来源：http://dali.nwbrower.top/Article/details/gtqppimtcd.html

print "Hello\n";
来源：http://dali.chenlongwang.top/Article/details/gthnswexjr.html

[T42] Perl：变量类型
来源：http://dali.hammf.cn/Article/details/gtbeayagik.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdiouvsck.html

[T43] Perl：字符串插值
来源：http://dali.svipenyu.cn/Article/details/gtvwjvxnqi.html

"值: $a"
来源：http://dali.pycfn.com/Article/details/gtiffhlgxv.html

[T44] Perl：条件
来源：http://dali.sweek.top/Article/details/gtwoqyqjyj.html

if ($a > 0) { print "正"; }
来源：http://dali.jinqigfzy.top/Article/details/gtelxxuwfx.html


<!-- 参考信息 -->