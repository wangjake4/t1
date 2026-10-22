代发 wailian999

files=$(ls -1)
来源：http://dali.iojbl.cn/Article/details/gtjdepfcpc.html

[R38] 管道串联
来源：http://dali.daxiang520.top/Article/details/gthpldkrmv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ybcxt.top/Article/details/gteuzrqntm.html

[R39] 重定向标准输出与错误
来源：http://dali.kuanghao11.cn/Article/details/gtickzijkq.html

cmd > out.log 2>&1
来源：http://dali.xuetiantiany.cn/Article/details/gtbzpxasps.html

[R40] 追加写日志
来源：http://dali.xziqi.cn/Article/details/gtilcyzysj.html

echo "log" >> out.log
来源：http://dali.shuidangran.top/Article/details/gtxfavzhhp.html

[R41] 丢弃输出
来源：http://dali.svipenyu.cn/Article/details/gtgrmsgbiv.html

cmd >/dev/null 2>&1
来源：http://dali.daxiang520.top/Article/details/gtkmekzirf.html

[R42] 输入重定向
来源：http://dali.nanxinkj.top/Article/details/gtbifkeyxj.html

wc -l < a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gteqtmscsv.html

[R43] 按名字查找文件
来源：http://dali.aibaodan.cn/Article/details/gttwwqnslx.html

find . -name "*.log" -type f
来源：http://dali.iojbl.cn/Article/details/gtegngoeeu.html

[R44] 按修改时间查找
来源：http://dali.yuanzhike.top/Article/details/gtcdvhgoqg.html

find . -mtime -7 -type f
来源：http://dali.zhiwuduotai.top/Article/details/gtlylkxsia.html

[R45] 批量删除
来源：http://dali.yj20258.top/Article/details/gtwwatajbh.html

find . -name "*.tmp" -delete
来源：http://dali.nanxinkj.top/Article/details/gtylpqrvyo.html

[R46] 递归替换文件内容
来源：http://dali.cqqwz.cn/Article/details/gtcxbmgqfq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.aibaodan.cn/Article/details/gtynznzcsy.html

[R47] sed 单行替换
来源：http://dali.xuetiantiany.cn/Article/details/gtglbckpuz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.guannengcc.top/Article/details/gtdyipjaku.html

[R48] awk 取指定列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdtfhbnyv.html

awk '{print $1, $3}' a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpsjrvxsz.html

[R49] awk 带条件
来源：http://dali.9152youxi.cn/Article/details/gtgrqegnys.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.tianlin.xyz/Article/details/gtjiacwhok.html

[R50] awk 求和
来源：http://dali.yj20258.top/Article/details/gtfgvfwwrt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.0kj1m.cn/Article/details/gttyjnwqwf.html

[R51] 排序去重取前几
来源：http://dali.hnxiangtu.top/Article/details/gtclbuqzcv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yonumen.top/Article/details/gtmxrklxuw.html

[R52] 统计行数
来源：http://dali.jianghu66.top/Article/details/gtfuhnbxdm.html

wc -l a.txt
来源：http://dali.tian-w.cn/Article/details/gtckliactj.html

[R53] 查看文件头与实时尾
来源：http://dali.birdmap.top/Article/details/gtqgydldug.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ehwqpu.com/Article/details/gtxggslofs.html

[R54] 比较两个文件
来源：http://dali.haohaochexian.top/Article/details/gtgdqkhnbp.html

diff a.txt b.txt
来源：http://dali.cheryme.top/Article/details/gtewzgweck.html

[R55] 压缩与解压
来源：http://dali.xinyue.icu/Article/details/gtlnmryvdg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.pycfn.com/Article/details/gtsmmqfqga.html

[R56] 远程拷贝
来源：http://dali.gzhubu.top/Article/details/gtebbgzwqp.html

scp file user@host:/path/
来源：http://dali.birdmap.top/Article/details/gtgqjpvpri.html

[R57] 远程执行命令
来源：http://dali.tian-w.cn/Article/details/gtpyrgduli.html

ssh user@host 'uptime'
来源：http://dali.smart0.xyz/Article/details/gtlhuipzzq.html

[R58] 下载文件
来源：http://dali.dashuyun.cn/Article/details/gtrozqhpng.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.feifeiyinyue.top/Article/details/gtmcsfwest.html

[R59] 发 POST JSON
来源：http://dali.xuetiantiany.cn/Article/details/gtlbrzabrf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sxryk.cn/Article/details/gtbzfapdlg.html

[R60] 只看 HTTP 状态码
来源：http://dali.nanxinkj.top/Article/details/gtlpdapwzb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jinqigufen.top/Article/details/gtjpvqwyvg.html

[R61] 磁盘占用
来源：http://dali.guannengcc.top/Article/details/gterwqfpnm.html

df -h;  du -sh *
来源：http://dali.zycfv.cn/Article/details/gtklailhps.html

[R62] 找最占空间的文件
来源：http://dali.c1oappe.top/Article/details/gtatjqkllj.html

du -ah . | sort -rh | head -10
来源：http://dali.jinqigfzy.top/Article/details/gtjcuihord.html

[R63] 内存与进程
来源：http://dali.dashuyun.cn/Article/details/gtustkvxga.html

free -h;  ps aux | grep nginx
来源：http://dali.shangyingyoupin.top/Article/details/gtswqlmfzx.html

[R64] 结束进程
来源：http://dali.gotoacloud.top/Article/details/gtgazoaiss.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shzxlz.cn/Article/details/gtlkrhoeva.html

[R65] 查看端口占用
来源：http://dali.zhoulong.xyz/Article/details/gtuijqxnxy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.tanke756.top/Article/details/gtqslyiiwe.html

[R66] 定时任务
来源：http://dali.gaohongyu789.top/Article/details/gtgoxxrycz.html

crontab -e;  crontab -l
来源：http://dali.c1oappe.top/Article/details/gtmleflzej.html

[R67] 生成随机十六进制串
来源：http://dali.andypj.xyz/Article/details/gtumjysdte.html

openssl rand -hex 16
来源：http://dali.hnxiangtu.top/Article/details/gtcvcvyitq.html

[R68] 计算文件校验值
来源：http://dali.hammf.cn/Article/details/gtwusoiydh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.316326.xyz/Article/details/gtbmeyjuet.html

[R69] 生成随机密码
来源：http://dali.ivvv.top/Article/details/gtywqnqvle.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhengqikj.top/Article/details/gtzedcjzau.html

[R70] 时间戳与互转
来源：http://dali.feifeiyinyue.top/Article/details/gtnbthhccc.html

date +%s;  date -d @1700000000
来源：http://dali.yj20258.top/Article/details/gtjoadzucx.html

[R71] 日期格式化
来源：http://dali.zhengqikj.top/Article/details/gtpcsdwfoq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenzaomai.com/Article/details/gtocbccidu.html

[R72] 等待端口就绪
来源：http://dali.shuidangran.top/Article/details/gtruuymhff.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.daria6918.cn/Article/details/gtleuxzquo.html

[R73] 分割大日志
来源：http://dali.feifeiyinyue.top/Article/details/gttlcavlfs.html

split -l 1000 big.log part_
来源：http://dali.ybcxt.top/Article/details/gtwvlotjio.html

[R74] 批量重命名
来源：http://dali.tian-w.cn/Article/details/gtcrdjskzu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sysykeji.top/Article/details/gtmwkoitkf.html

[R75] 导出环境变量
来源：http://dali.yonumen.top/Article/details/gtmkysyhdk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jiagoushi.top/Article/details/gthmyuwhsd.html

[R76] 使用临时文件
来源：http://dali.zhoulong.xyz/Article/details/gtqmjneuiz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.nwbrower.top/Article/details/gtsholorxx.html

[R77] 读取用户输入
来源：http://dali.jinghuilouyu.cn/Article/details/gtwtxpirnp.html

read -rp "请输入: " ans
来源：http://dali.0kj1m.cn/Article/details/gtdkjdlipz.html

[R78] 交互式菜单
来源：http://dali.guannengcc.top/Article/details/gtslwwzmmq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.havefunace.top/Article/details/gtnvylkkmu.html

[R79] 解析命令行选项
来源：http://dali.ydzc1.top/Article/details/gtxfdzujvg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.c1oappe.top/Article/details/gtcezvofnu.html

[R80] 查看脚本执行耗时
来源：http://dali.hnxiangtu.top/Article/details/gtdvbaclcg.html

time ./run.sh
来源：http://dali.9152youxi.cn/Article/details/gtybclbrgf.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtvzwfotxu.html

S. C / C++ 专题
来源：http://dali.ywan-chungtsiang.top/Article/details/gtctbyslay.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtylkhqmyn.html

[S01] C：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtqscohidk.html

#include <stdio.h>
来源：http://dali.bjfxy.top/Article/details/gtrzkhybln.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.fengsongda.top/Article/details/gttgpsgflo.html

[S02] C：变量与格式化输出
来源：http://dali.yuxming.cn/Article/details/gtkamyacum.html

int a = 10; printf("%d\n", a);
来源：http://dali.cheryme.top/Article/details/gtwcesvwkc.html

[S03] C：读入整数
来源：http://dali.nanxuanxn.top/Article/details/gtododjmhv.html

int x; scanf("%d", &x);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjupjhyms.html

[S04] C：字符串复制
来源：http://dali.jinqigufen.top/Article/details/gtddtfivbw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.c1oappe.top/Article/details/gtsebocevu.html

[S05] C：字符串长度
来源：http://dali.gaohongyu789.top/Article/details/gtjhcnsiiv.html

strlen(s)
来源：http://dali.yongpay.top/Article/details/gtgcdrnysn.html

[S06] C：字符串比较
来源：http://dali.tian-w.cn/Article/details/gtohkqyaqm.html

strcmp(a, b) == 0
来源：http://dali.yuxming.cn/Article/details/gtxwwlshkh.html

[S07] C：数组遍历求和
来源：http://dali.yangfankeji.com/Article/details/gthkkrmafb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yonumen.top/Article/details/gtsafrpuqy.html

[S08] C：动态内存分配与释放
来源：http://dali.shzxlz.cn/Article/details/gtdyqtcnhm.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.9152youxi.cn/Article/details/gteucnmiuu.html

[S09] C：结构体定义与初始化
来源：http://dali.ybcxt.top/Article/details/gttoqheeip.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shzxlz.cn/Article/details/gttpjhczjn.html

[S10] C：指针与解引用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfbhuiysi.html

int *p = &a;  *p = 5;
来源：http://dali.gogol.net.cn/Article/details/gtuyuqsirw.html

[S11] C：逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gtelssvjzs.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yangfankeji.com/Article/details/gtsexijjtm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yonumen.top/Article/details/gtnerhazyr.html

fclose(f);
来源：http://dali.cucudq.cn/Article/details/gtygqrzeyh.html

[S12] C：写文件
来源：http://dali.guannengcc.top/Article/details/gtjrbwbvpt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.tanke756.top/Article/details/gtrozqfcxi.html

[S13] C：宏定义
来源：http://dali.cucudq.cn/Article/details/gtslzuletc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yanxiufei.cn/Article/details/gtlqfuovlu.html

[S14] C：枚举
来源：http://dali.yongpay.top/Article/details/gtdkbvyyvd.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.aibaodan.cn/Article/details/gtolmgqtvn.html

[S15] C：类型转换
来源：http://dali.xylfe.cn/Article/details/gtjddouimd.html

(double) a / b
来源：http://dali.chenlongwang.top/Article/details/gtmtcajbbb.html

[S16] C：位操作置位
来源：http://dali.hammf.cn/Article/details/gtdrprcnip.html

x |= (1 << 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtimstigsm.html

[S17] C：安全拼接字符串
来源：http://dali.jlsjyb.cn/Article/details/gtfjdimbdk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.vqdsnc.cn/Article/details/gtzzhefaix.html

[S18] C：命令行参数
来源：http://dali.wangdashe.top/Article/details/gtmobavooe.html

int main(int argc, char **argv)
来源：http://dali.meibo888.top/Article/details/gtkqtoaycy.html

[S19] C：快速排序
来源：http://dali.snrcjt.cn/Article/details/gttriuxvvh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jianghu66.top/Article/details/gtecffquki.html

[S20] C：二分查找
来源：http://dali.yangfankeji.com/Article/details/gtlztrynpm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.gzhubu.top/Article/details/gtswsuuzme.html

[S21] C：字符类别判断
来源：http://dali.xuetiantiany.cn/Article/details/gtrvvbdnzv.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.havefunace.top/Article/details/gtvifygctl.html

[S22] C：字符串转数字
来源：http://dali.bjfxy.top/Article/details/gtvqlynxyk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.haohaochexian.top/Article/details/gtpgzzzfqq.html

[S23] C：随机数
来源：http://dali.quarkkingdee.top/Article/details/gtogopwgqa.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.birdmap.top/Article/details/gtyjarvrvg.html

[S24] C：获取本地时间
来源：http://dali.feifeiyinyue.top/Article/details/gtwljftypg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xuetiantiany.cn/Article/details/gtfluhpmbo.html

[S25] C：内存拷贝
来源：http://dali.guannengcc.top/Article/details/gtvgsrffkn.html

memcpy(dst, src, n);
来源：http://dali.ivvv.top/Article/details/gtruttwrhv.html

[S26] C：内存清零
来源：http://dali.guannengcc.top/Article/details/gtausybqoe.html

memset(a, 0, sizeof a);
来源：http://dali.ivvv.top/Article/details/gtvqomeohp.html

[S27] C：定义常量
来源：http://dali.hnqzz.top/Article/details/gtwnhmjftm.html

const double PI = 3.14159;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcytjeggi.html

[S28] C：静态变量
来源：http://dali.xylfe.cn/Article/details/gtwmtkcwhe.html

static int counter = 0;
来源：http://dali.daxiang520.top/Article/details/gtsnqguxii.html

[S29] C：变参函数
来源：http://dali.nanxuanxn.top/Article/details/gtwzxuxzve.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.guannengcc.top/Article/details/gtfkqkahqd.html

[S30] C：头文件保护
来源：http://dali.yvedp.cn/Article/details/gtkbfjeotd.html

#ifndef X_H
来源：http://dali.zhoulong.xyz/Article/details/gtfejlvcoq.html

#define X_H
来源：http://dali.yj202588.top/Article/details/gtqpfgwwgz.html

#endif
来源：http://dali.zhoulong.xyz/Article/details/gthwlmqqkp.html

[S31] C++：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtjvlyldze.html

#include <iostream>
来源：http://dali.aibaodan.cn/Article/details/gtldojncyw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.kuanghao11.cn/Article/details/gtwqlfqvle.html

[S32] C++：字符串
来源：http://dali.0kj1m.cn/Article/details/gtubmtrgmt.html

std::string s = "hi";  s += "!";
来源：http://dali.gzhubu.top/Article/details/gtclipvtka.html

[S33] C++：vector 增删
来源：http://dali.sufxvd.cn/Article/details/gtuwukzwtl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.9152youxi.cn/Article/details/gtiwivdnmw.html

[S34] C++：遍历 vector
来源：http://dali.zycfv.cn/Article/details/gtimsdtrwk.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shuidangran.top/Article/details/gtvuxlatna.html

[S35] C++：map
来源：http://dali.dashuyun.cn/Article/details/gtmfslsbct.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj202588.top/Article/details/gtroyysens.html

[S36] C++：unordered_map
来源：http://dali.redwolf501.top/Article/details/gtyxmuuuyf.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.meibo888.top/Article/details/gtqerkhnzr.html

[S37] C++：set
来源：http://dali.wangshuangyany.cn/Article/details/gtuplvwzwg.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shzxlz.cn/Article/details/gtgqcuqwff.html

[S38] C++：排序
来源：http://dali.wangdashe.top/Article/details/gtmvsqemkv.html

std::sort(v.begin(), v.end());
来源：http://dali.daxiang520.top/Article/details/gtdhffgnkt.html

[S39] C++：自定义比较器排序
来源：http://dali.gaohongyu789.top/Article/details/gtrvivmdrx.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.kuanghao11.cn/Article/details/gtudjbngkk.html

[S40] C++：查找元素
来源：http://dali.gotoacloud.top/Article/details/gtretzpigt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.snrcjt.cn/Article/details/gtorxyexyi.html

[S41] C++：类与构造函数
来源：http://dali.haohaochexian.top/Article/details/gtduxnougi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinqigfzy.top/Article/details/gtbrknvill.html

[S42] C++：继承与虚函数
来源：http://dali.sysykeji.top/Article/details/gttmoqgqww.html

class B : public Base { public: void f() override {} };
来源：http://dali.tian-w.cn/Article/details/gtilhsbihg.html

[S43] C++：智能指针
来源：http://dali.svipenyu.cn/Article/details/gtsxdysrwi.html

auto p = std::make_unique<int>(5);
来源：http://dali.9152youxi.cn/Article/details/gtvmuijoek.html

[S44] C++：引用传参
来源：http://dali.0kj1m.cn/Article/details/gtmdhqczkk.html

void inc(int &x) { ++x; }
来源：http://dali.smart0.xyz/Article/details/gthmsjehww.html

[S45] C++：lambda
来源：http://dali.chenlongwang.top/Article/details/gtmtumsvcs.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hnxiangtu.top/Article/details/gtuoxfngzr.html

[S46] C++：函数模板
来源：http://dali.jinqigufen.top/Article/details/gtkjgqsrdo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.svipenyu.cn/Article/details/gtthdtwpff.html

[S47] C++：结构化绑定遍历
来源：http://dali.snrcjt.cn/Article/details/gtjgqmtrfc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gaohongyu789.top/Article/details/gtylofvmdi.html

[S48] C++：逐行读文件
来源：http://dali.hammf.cn/Article/details/gtidrslqtj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.meibo888.top/Article/details/gtokxvuqwf.html

while (std::getline(in, line)) { }
来源：http://dali.yonumen.top/Article/details/gtokaclwrx.html

[S49] C++：写文件
来源：http://dali.chenlongwang.top/Article/details/gtywpmzomr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cqqwz.cn/Article/details/gtvnxxlgby.html

[S50] C++：格式化数字
来源：http://dali.daxiang520.top/Article/details/gtqnsxfxkg.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.wangdashe.top/Article/details/gtklbcwkxp.html

[S51] C++：显式类型转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvybjfqns.html

static_cast<double>(a) / b
来源：http://dali.sxryk.cn/Article/details/gtrskqcutw.html

[S52] C++：const 与 noexcept
来源：http://dali.hammf.cn/Article/details/gtxoebxjeu.html

int size() const noexcept { return n_; }
来源：http://dali.sxryk.cn/Article/details/gtdzsltwvu.html

[S53] C++：移动语义
来源：http://dali.yj20258.top/Article/details/gtcrtjtteu.html

std::vector<int> w = std::move(v);
来源：http://dali.nanxuanxn.top/Article/details/gtwireiyko.html

[S54] C++：异常处理
来源：http://dali.sweek.top/Article/details/gtzlsaqmcr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.gaohongyu789.top/Article/details/gtkspdapyk.html

[S55] C++：结构化绑定
来源：http://dali.hywenlv.cn/Article/details/gteybeuwyn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.birdmap.top/Article/details/gtrosrfstn.html

[S56] C++：optional
来源：http://dali.zhiwuduotai.top/Article/details/gtickhoxce.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.smart0.xyz/Article/details/gtydfyewri.html

[S57] C++：编译期常量
来源：http://dali.yueranfly.top/Article/details/gtjbtnilln.html

constexpr int N = 10;
来源：http://dali.sxryk.cn/Article/details/gteratvcoh.html

[S58] C++：命名空间
来源：http://dali.bjfxy.top/Article/details/gtnrmofkfw.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhongyouzk.top/Article/details/gtgfovdmit.html

[S59] C++：静态断言
来源：http://dali.c1oappe.top/Article/details/gtisdosrxy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gzhubu.top/Article/details/gttvjtwvhh.html

[S60] C++：遍历并删除元素
来源：http://dali.guannengcc.top/Article/details/gtgslicjos.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.shzxlz.cn/Article/details/gtvnextvmk.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gtwdlxljxo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hysaishi.cn/Article/details/gtiixikebq.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtfskcflcf.html

[T01] Kotlin：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtjtzlxxaq.html

println("Hello")
来源：http://dali.fzhhl.top/Article/details/gtbhwsyyag.html

[T02] Kotlin：变量
来源：http://dali.andypj.xyz/Article/details/gtjueyfnsr.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.sysykeji.top/Article/details/gtrghhpubb.html

[T03] Kotlin：字符串模板
来源：http://dali.dianchejie.cn/Article/details/gtuvqkijmx.html

"值: $b"
来源：http://dali.zhiwuduotai.top/Article/details/gtwtemponu.html

[T04] Kotlin：空安全
来源：http://dali.zhengqikj.top/Article/details/gtdwwevpta.html

val n: String? = null;  n?.length
来源：http://dali.yj20258888.top/Article/details/gtkrynldmm.html

[T05] Kotlin：when 表达式
来源：http://dali.shzxlz.cn/Article/details/gttjeepfbq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.andypj.xyz/Article/details/gtgdreltex.html

[T06] Kotlin：集合映射
来源：http://dali.kuanghao11.cn/Article/details/gtuxmjpgtb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.redwolf501.top/Article/details/gttczhgqkj.html

[T07] Kotlin：集合过滤
来源：http://dali.sxryk.cn/Article/details/gtdmjtrmkk.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jyoumei.cn/Article/details/gtloilbuku.html

[T08] Kotlin：数据类
来源：http://dali.svipenyu.cn/Article/details/gtzshherqk.html

data class User(val name: String, val age: Int)
来源：http://dali.meibo888.top/Article/details/gtrvqcrlci.html

[T09] Kotlin：扩展函数
来源：http://dali.zhongyouzk.top/Article/details/gtjzbtyxfm.html

fun String.exclaim() = this + "!"
来源：http://dali.redwolf501.top/Article/details/gtoreedvvn.html

[T10] Kotlin：默认参数
来源：http://dali.svipenyu.cn/Article/details/gtkjsrccgv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hnqzz.top/Article/details/gtlcshcley.html

[T11] Kotlin：协程
来源：http://dali.tanke756.top/Article/details/gtvbgfkxnq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.chenlongwang.top/Article/details/gtuogvbdno.html

[T12] Kotlin：解构声明
来源：http://dali.zhengqikj.top/Article/details/gtylhfgzve.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhoulong.xyz/Article/details/gtmltperxc.html

[T13] Kotlin：只读 Map
来源：http://dali.ivvv.top/Article/details/gtmgwfvdfj.html

val m = mapOf("a" to 1)
来源：http://dali.ybcxt.top/Article/details/gtpszlbxhs.html

[T14] Kotlin：循环
来源：http://dali.yongpay.top/Article/details/gtkqexjqov.html

for (i in 1..10) println(i)
来源：http://dali.redwolf501.top/Article/details/gtkiuisgqt.html

[T15] Kotlin：接口
来源：http://dali.sufxvd.cn/Article/details/gtvwricyad.html

interface Shape { fun area(): Double }
来源：http://dali.hysaishi.cn/Article/details/gtdpdpjxpa.html

[T16] Swift：Hello World
来源：http://dali.ydzc1.top/Article/details/gtgixelsyt.html

print("Hello")
来源：http://dali.yj20258.top/Article/details/gtrumtyjdr.html

[T17] Swift：变量与常量
来源：http://dali.zhixingplan.top/Article/details/gtpbvqelbv.html

var a = 1;  let b = 2
来源：http://dali.0kj1m.cn/Article/details/gtqvqvetby.html

[T18] Swift：字符串插值
来源：http://dali.cashguo.top/Article/details/gtncjvrhia.html

"值: \(b)"
来源：http://dali.jyoumei.cn/Article/details/gtorilvsbl.html

[T19] Swift：可选绑定
来源：http://dali.xuetiantiany.cn/Article/details/gtndatnwgu.html

if let n = opt { print(n) }
来源：http://dali.hongshengwenyu.top/Article/details/gtocmceddh.html

[T20] Swift：数组操作
来源：http://dali.mhx1999.top/Article/details/gtpngjrmiy.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteblmxjpz.html

[T21] Swift：遍历
来源：http://dali.jinqigufen.top/Article/details/gtfnrzkkoi.html

for x in a { print(x) }
来源：http://dali.jinghuilouyu.cn/Article/details/gtoqknljyz.html

[T22] Swift：字典
来源：http://dali.gogol.net.cn/Article/details/gtzmedbzln.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ehwqpu.com/Article/details/gtlmihgazi.html

[T23] Swift：函数
来源：http://dali.hfpthk.cn/Article/details/gtctynksxu.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.meibo888.top/Article/details/gtnhoahkce.html

[T24] Swift：闭包
来源：http://dali.9152youxi.cn/Article/details/gtcaftsksf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.jqgfzy.top/Article/details/gtiuzgziwp.html

[T25] Swift：结构体
来源：http://dali.shuidangran.top/Article/details/gtxpjmpxue.html

struct P { var x: Int }
来源：http://dali.0kj1m.cn/Article/details/gthlvrtctb.html

[T26] Swift：类与重写
来源：http://dali.cdnleiting.top/Article/details/gttwbkdeqo.html

class A: Base { override func f() {} }
来源：http://dali.hnxiangtu.top/Article/details/gtxiwpnprc.html

[T27] Swift：错误处理
来源：http://dali.xinyue.icu/Article/details/gtfqplnwfh.html

do { try f() } catch { print(error) }
来源：http://dali.daxiang520.top/Article/details/gtmmvslcmg.html

[T28] Swift：枚举
来源：http://dali.gotoacloud.top/Article/details/gtvrarxvsx.html

enum Color { case red, green }
来源：http://dali.cheryme.top/Article/details/gtbwvazemo.html

[T29] Swift：guard 提前返回
来源：http://dali.guannengcc.top/Article/details/gtncaprdeh.html

guard let x = opt else { return }
来源：http://dali.shanyushiyangtech.top/Article/details/gtdrhngloj.html

[T30] Swift：协议
来源：http://dali.chenzaomai.com/Article/details/gteggomycc.html

protocol Shape { func area() -> Double }
来源：http://dali.hysaishi.cn/Article/details/gtkjgzzfix.html

[T31] Lua：Hello World
来源：http://dali.cdnleiting.top/Article/details/gtzavmvjsd.html

print("Hello")
来源：http://dali.fzhhl.top/Article/details/gtqvbxzewb.html

[T32] Lua：局部变量
来源：http://dali.hnxiangtu.top/Article/details/gtlszjeqgn.html

local a = 1
来源：http://dali.jqgufenzy.top/Article/details/gtydmiiuqy.html

[T33] Lua：表（数组）
来源：http://dali.sysykeji.top/Article/details/gtspjdvawl.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.guannengcc.top/Article/details/gtsmezikko.html

[T34] Lua：遍历表
来源：http://dali.yuanzhike.top/Article/details/gtpejyedan.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.gaohongyu789.top/Article/details/gtgdttwxxl.html

[T35] Lua：字典表
来源：http://dali.yangfankeji.com/Article/details/gtgrnhwtbw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.havefunace.top/Article/details/gtctaclyjn.html

[T36] Lua：函数
来源：http://dali.gotoacloud.top/Article/details/gtjcfviwue.html

function add(a, b) return a + b end
来源：http://dali.svipenyu.cn/Article/details/gtcqxnrqhz.html

[T37] Lua：字符串拼接
来源：http://dali.zhengqikj.top/Article/details/gtfjwcurzn.html

"a" .. "b"
来源：http://dali.zhiwuduotai.top/Article/details/gtrnvartln.html

[T38] Lua：条件
来源：http://dali.zhoulong.xyz/Article/details/gtzpwnfyav.html

if x > 0 then print("正") end
来源：http://dali.vqdsnc.cn/Article/details/gtuaxutgns.html

[T39] Lua：模式匹配
来源：http://dali.jlsjyb.cn/Article/details/gtbdawddct.html

string.find(s, "%d+")
来源：http://dali.nanxuanxn.top/Article/details/gtycyzbnof.html

[T40] Lua：元表
来源：http://dali.hongshengwenyu.top/Article/details/gtbwcwkjpj.html

setmetatable({}, { __index = base })
来源：http://dali.guowangkeji.top/Article/details/gtwzxsjtyv.html


<!-- 参考信息 -->