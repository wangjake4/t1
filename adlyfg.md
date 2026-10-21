代发 wailian999

find . -name "*.log" -type f
来源：http://dali.aibaodan.cn/Article/details/gtuausjwiu.html

[R44] 按修改时间查找
来源：http://dali.aibaodan.cn/Article/details/gtissgivfd.html

find . -mtime -7 -type f
来源：http://dali.hysaishi.cn/Article/details/gttrhhcgst.html

[R45] 批量删除
来源：http://dali.pycfn.com/Article/details/gtraimlxpk.html

find . -name "*.tmp" -delete
来源：http://dali.andypj.xyz/Article/details/gtojhnwdfe.html

[R46] 递归替换文件内容
来源：http://dali.jiagoushi.top/Article/details/gtqkwvoylz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlmzldsrq.html

[R47] sed 单行替换
来源：http://dali.yonumen.top/Article/details/gtgdvemeit.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.kuanghao11.cn/Article/details/gtxltibbyc.html

[R48] awk 取指定列
来源：http://dali.gaohongyu789.top/Article/details/gtjdfwfoux.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtdntkndev.html

[R49] awk 带条件
来源：http://dali.hywenlv.cn/Article/details/gtxxyzzwut.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gaohongyu789.top/Article/details/gtyhxiqsif.html

[R50] awk 求和
来源：http://dali.316326.xyz/Article/details/gtvreanyvd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zdqjudy.top/Article/details/gtjbiwkkti.html

[R51] 排序去重取前几
来源：http://dali.chenjidiqi.icu/Article/details/gtenslfepr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yj20258.top/Article/details/gtzoguojhu.html

[R52] 统计行数
来源：http://dali.aibaodan.cn/Article/details/gtgpstwlwq.html

wc -l a.txt
来源：http://dali.iojbl.cn/Article/details/gtxkphjqsf.html

[R53] 查看文件头与实时尾
来源：http://dali.jqgfzy.top/Article/details/gtoczuycyw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cheryme.top/Article/details/gtmmfzlyov.html

[R54] 比较两个文件
来源：http://dali.aibaodan.cn/Article/details/gtffvqnlpb.html

diff a.txt b.txt
来源：http://dali.nanxinkj.top/Article/details/gtqjcvdxwg.html

[R55] 压缩与解压
来源：http://dali.wangdashe.top/Article/details/gtuxgsgous.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gthdnwmuey.html

[R56] 远程拷贝
来源：http://dali.andypj.xyz/Article/details/gtszbjhpuc.html

scp file user@host:/path/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthvacsfre.html

[R57] 远程执行命令
来源：http://dali.iojbl.cn/Article/details/gtpwusxttq.html

ssh user@host 'uptime'
来源：http://dali.ydzc1.top/Article/details/gtiqdrbure.html

[R58] 下载文件
来源：http://dali.sysykeji.top/Article/details/gtuuhpljmc.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yvedp.cn/Article/details/gtzkmcmijv.html

[R59] 发 POST JSON
来源：http://dali.nanxinkj.top/Article/details/gttkxdkkae.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.bjfxy.top/Article/details/gtzibmkmvf.html

[R60] 只看 HTTP 状态码
来源：http://dali.dashuyun.cn/Article/details/gtpcsmbhmn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.haohaochexian.top/Article/details/gtvwpxkktf.html

[R61] 磁盘占用
来源：http://dali.bjfxy.top/Article/details/gtwcqtdcsl.html

df -h;  du -sh *
来源：http://dali.zdqjudy.top/Article/details/gtrlnwneed.html

[R62] 找最占空间的文件
来源：http://dali.gogol.net.cn/Article/details/gtmoivieuh.html

du -ah . | sort -rh | head -10
来源：http://dali.sweek.top/Article/details/gtjuuovulg.html

[R63] 内存与进程
来源：http://dali.meibo888.top/Article/details/gtymvinxar.html

free -h;  ps aux | grep nginx
来源：http://dali.fengsongda.top/Article/details/gtmlrvjviw.html

[R64] 结束进程
来源：http://dali.hnxiangtu.top/Article/details/gtgydgblop.html

kill -9 $(pgrep -f app.py)
来源：http://dali.aizwys.cn/Article/details/gtdgavusvw.html

[R65] 查看端口占用
来源：http://dali.vqdsnc.cn/Article/details/gtdhrdqstt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ehwqpu.com/Article/details/gtimmyrfiw.html

[R66] 定时任务
来源：http://dali.bjfxy.top/Article/details/gttisagvtd.html

crontab -e;  crontab -l
来源：http://dali.redwolf501.top/Article/details/gtgoasxyzr.html

[R67] 生成随机十六进制串
来源：http://dali.yueranfly.top/Article/details/gtgbzokono.html

openssl rand -hex 16
来源：http://dali.redwolf501.top/Article/details/gtukcdluvc.html

[R68] 计算文件校验值
来源：http://dali.cheryme.top/Article/details/gtcazuxdfj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.aibaodan.cn/Article/details/gtkigazica.html

[R69] 生成随机密码
来源：http://dali.pycfn.com/Article/details/gtgvmedyay.html

head -c 16 /dev/urandom | base64
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnjmuctgc.html

[R70] 时间戳与互转
来源：http://dali.sufxvd.cn/Article/details/gtrgjeisbc.html

date +%s;  date -d @1700000000
来源：http://dali.pengpengdd.cyou/Article/details/gtqjvtlela.html

[R71] 日期格式化
来源：http://dali.hongshengwenyu.top/Article/details/gttkrsrbtg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hnxiangtu.top/Article/details/gtyqewtnkh.html

[R72] 等待端口就绪
来源：http://dali.shzxlz.cn/Article/details/gtqoxpjfhu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yangfankeji.com/Article/details/gtpkgabkmp.html

[R73] 分割大日志
来源：http://dali.ppjwa.cn/Article/details/gtvbivrfuh.html

split -l 1000 big.log part_
来源：http://dali.wangshuangyany.cn/Article/details/gtfnksnhch.html

[R74] 批量重命名
来源：http://dali.wangshuangyany.cn/Article/details/gtdxkiqbrt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.chenjidiqi.icu/Article/details/gtffrijmmy.html

[R75] 导出环境变量
来源：http://dali.sysykeji.top/Article/details/gtdqawnhuw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.cucudq.cn/Article/details/gtfbhgbkws.html

[R76] 使用临时文件
来源：http://dali.haohaochexian.top/Article/details/gtvkloqmoj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.aizwys.cn/Article/details/gtbmvmggtn.html

[R77] 读取用户输入
来源：http://dali.yangfankeji.com/Article/details/gtlnkklzlx.html

read -rp "请输入: " ans
来源：http://dali.yj202588.top/Article/details/gtyjkcdqql.html

[R78] 交互式菜单
来源：http://dali.guannengcc.top/Article/details/gtyiwfebgk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.snrcjt.cn/Article/details/gtodkdidgr.html

[R79] 解析命令行选项
来源：http://dali.zhaomingkeji.xyz/Article/details/gthxxhnqur.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.tian-w.cn/Article/details/gtcdckvpqx.html

[R80] 查看脚本执行耗时
来源：http://dali.xuetiantiany.cn/Article/details/gtnbgsruuz.html

time ./run.sh
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqmfnazkw.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gtkweftdpv.html

S. C / C++ 专题
来源：http://dali.jinghuilouyu.cn/Article/details/gtivrsqebn.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtjqftbxfk.html

[S01] C：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtaijregvs.html

#include <stdio.h>
来源：http://dali.cashguo.top/Article/details/gtdbotqckl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.aibaodan.cn/Article/details/gthlqxwcpd.html

[S02] C：变量与格式化输出
来源：http://dali.hysaishi.cn/Article/details/gtrnhfuhjt.html

int a = 10; printf("%d\n", a);
来源：http://dali.hywenlv.cn/Article/details/gtyeqteucq.html

[S03] C：读入整数
来源：http://dali.shzxlz.cn/Article/details/gtemzujxnh.html

int x; scanf("%d", &x);
来源：http://dali.yj202588.top/Article/details/gtipxncneh.html

[S04] C：字符串复制
来源：http://dali.zhiwuduotai.top/Article/details/gtyqifeogt.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gtezekilau.html

[S05] C：字符串长度
来源：http://dali.gotoacloud.top/Article/details/gtvvrwrzpt.html

strlen(s)
来源：http://dali.xuanzx.com/Article/details/gtoqckvyth.html

[S06] C：字符串比较
来源：http://dali.pengpengdd.cyou/Article/details/gtapqwlzyr.html

strcmp(a, b) == 0
来源：http://dali.ydzc1.top/Article/details/gtluudolim.html

[S07] C：数组遍历求和
来源：http://dali.pycfn.com/Article/details/gtghwwtpzn.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.andypj.xyz/Article/details/gtkawzwbxe.html

[S08] C：动态内存分配与释放
来源：http://dali.cdnleiting.top/Article/details/gtfxfkcpod.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yangfankeji.com/Article/details/gthqxfuidc.html

[S09] C：结构体定义与初始化
来源：http://dali.vqdsnc.cn/Article/details/gtlwaiwlsr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhengqikj.top/Article/details/gtzmzvhgvm.html

[S10] C：指针与解引用
来源：http://dali.zhongyouzk.top/Article/details/gtvjqvshen.html

int *p = &a;  *p = 5;
来源：http://dali.hnxiangtu.top/Article/details/gtjovhkqhj.html

[S11] C：逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gthitdogaa.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yj202588.top/Article/details/gtjmairxbz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sufxvd.cn/Article/details/gtrnvtjwro.html

fclose(f);
来源：http://dali.zhengqikj.top/Article/details/gtqwkruhye.html

[S12] C：写文件
来源：http://dali.birdmap.top/Article/details/gtgrcdlzfq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xziqi.cn/Article/details/gtimgraeqr.html

[S13] C：宏定义
来源：http://dali.shuidangran.top/Article/details/gtlmgmhgof.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yanxiufei.cn/Article/details/gtapkifjyb.html

[S14] C：枚举
来源：http://dali.316326.xyz/Article/details/gtpsorliqj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.dashuyun.cn/Article/details/gtuepubpam.html

[S15] C：类型转换
来源：http://dali.yanxiufei.cn/Article/details/gtjeatdooo.html

(double) a / b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlupkwkcf.html

[S16] C：位操作置位
来源：http://dali.yangfankeji.com/Article/details/gtqeyfzkcp.html

x |= (1 << 3);
来源：http://dali.ybcxt.top/Article/details/gtrfmxguxn.html

[S17] C：安全拼接字符串
来源：http://dali.chenzaomai.com/Article/details/gtnkdcdjjm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.wangdashe.top/Article/details/gtnwimfcfh.html

[S18] C：命令行参数
来源：http://dali.zhengqikj.top/Article/details/gtqcnfwlxc.html

int main(int argc, char **argv)
来源：http://dali.sxryk.cn/Article/details/gtyrqehzkm.html

[S19] C：快速排序
来源：http://dali.ppjwa.cn/Article/details/gtguiotrts.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.meibo888.top/Article/details/gtctomlrni.html

[S20] C：二分查找
来源：http://dali.chenlongwang.top/Article/details/gthkyeoqha.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cucudq.cn/Article/details/gthcbzdrjt.html

[S21] C：字符类别判断
来源：http://dali.jinqigufen.top/Article/details/gthqizteuj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hnqzz.top/Article/details/gturuhenin.html

[S22] C：字符串转数字
来源：http://dali.jinghuilouyu.cn/Article/details/gttbmkmyev.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhiwuduotai.top/Article/details/gtrtgdhxwp.html

[S23] C：随机数
来源：http://dali.yvedp.cn/Article/details/gtpmsyszqt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xylfe.cn/Article/details/gtiiaxwlqo.html

[S24] C：获取本地时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtopebotwp.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.tianlin.xyz/Article/details/gtqhbohrwk.html

[S25] C：内存拷贝
来源：http://dali.kuanghao11.cn/Article/details/gtarmulhmu.html

memcpy(dst, src, n);
来源：http://dali.jyoumei.cn/Article/details/gtqboimpmn.html

[S26] C：内存清零
来源：http://dali.shangyingyoupin.top/Article/details/gtvbeflvhp.html

memset(a, 0, sizeof a);
来源：http://dali.jyoumei.cn/Article/details/gtnifbeuup.html

[S27] C：定义常量
来源：http://dali.shzxlz.cn/Article/details/gtuoshivqk.html

const double PI = 3.14159;
来源：http://dali.jianghu66.top/Article/details/gtyrmvdtkw.html

[S28] C：静态变量
来源：http://dali.hnxiangtu.top/Article/details/gtxmfnubdr.html

static int counter = 0;
来源：http://dali.vqdsnc.cn/Article/details/gtmwfbqifb.html

[S29] C：变参函数
来源：http://dali.daxiang520.top/Article/details/gtaiazvuve.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cqqwz.cn/Article/details/gtrglvtduj.html

[S30] C：头文件保护
来源：http://dali.daxiang520.top/Article/details/gttbwvnsaq.html

#ifndef X_H
来源：http://dali.jqgfzy.top/Article/details/gtyzjejqbt.html

#define X_H
来源：http://dali.jinqigufen.top/Article/details/gtxhwgtfev.html

#endif
来源：http://dali.jinghuilouyu.cn/Article/details/gtogyzghkq.html

[S31] C++：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtopgiqtrs.html

#include <iostream>
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzyugzhyk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.gotoacloud.top/Article/details/gtkrbjoelc.html

[S32] C++：字符串
来源：http://dali.daria6918.cn/Article/details/gtpksfhdxt.html

std::string s = "hi";  s += "!";
来源：http://dali.9152youxi.cn/Article/details/gtrlnbpzvj.html

[S33] C++：vector 增删
来源：http://dali.jqgfzy.top/Article/details/gthbdvdnmm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jqgfzy.top/Article/details/gtnznowhlx.html

[S34] C++：遍历 vector
来源：http://dali.zhiwuduotai.top/Article/details/gtloxqpiss.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.daria6918.cn/Article/details/gtpetxjdiy.html

[S35] C++：map
来源：http://dali.jianghu66.top/Article/details/gtvmjkdbcm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gtrdfypkfr.html

[S36] C++：unordered_map
来源：http://dali.guowangkeji.top/Article/details/gtrgsplpun.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hysaishi.cn/Article/details/gtpvwugmgq.html

[S37] C++：set
来源：http://dali.ppjwa.cn/Article/details/gtkagxfbte.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.chenlongwang.top/Article/details/gtfmvwwdpv.html

[S38] C++：排序
来源：http://dali.wangdashe.top/Article/details/gtfmwkwzxt.html

std::sort(v.begin(), v.end());
来源：http://dali.quarkkingdee.top/Article/details/gtkvcrbulc.html

[S39] C++：自定义比较器排序
来源：http://dali.jinghuilouyu.cn/Article/details/gtapqxuzrh.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.iojbl.cn/Article/details/gtwpqkloyu.html

[S40] C++：查找元素
来源：http://dali.snrcjt.cn/Article/details/gtrcplnsay.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hysaishi.cn/Article/details/gtazlrhpup.html

[S41] C++：类与构造函数
来源：http://dali.chenlongwang.top/Article/details/gtdziwxtfb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.0kj1m.cn/Article/details/gtdyqrwiwr.html

[S42] C++：继承与虚函数
来源：http://dali.chenlongwang.top/Article/details/gtfzjwqnge.html

class B : public Base { public: void f() override {} };
来源：http://dali.9152youxi.cn/Article/details/gtvontovkj.html

[S43] C++：智能指针
来源：http://dali.cashguo.top/Article/details/gthnwobzdl.html

auto p = std::make_unique<int>(5);
来源：http://dali.hnqzz.top/Article/details/gttuwowtpx.html

[S44] C++：引用传参
来源：http://dali.yj202588.top/Article/details/gttzcgvsbr.html

void inc(int &x) { ++x; }
来源：http://dali.havefunace.top/Article/details/gtoxepudrh.html

[S45] C++：lambda
来源：http://dali.cqqwz.cn/Article/details/gtdxnwjtnr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jyoumei.cn/Article/details/gtgekuucjb.html

[S46] C++：函数模板
来源：http://dali.ybcxt.top/Article/details/gtmzmfjnhj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xinyue.icu/Article/details/gtfzytwwbf.html

[S47] C++：结构化绑定遍历
来源：http://dali.c1oappe.top/Article/details/gtwqeikapv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinqigufen.top/Article/details/gtacihiciv.html

[S48] C++：逐行读文件
来源：http://dali.xziqi.cn/Article/details/gtzcdlfkvo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gotoacloud.top/Article/details/gtefrrdled.html

while (std::getline(in, line)) { }
来源：http://dali.tianlin.xyz/Article/details/gtplsluuso.html

[S49] C++：写文件
来源：http://dali.nwbrower.top/Article/details/gtqywdvypi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.feifeiyinyue.top/Article/details/gtenvyhroy.html

[S50] C++：格式化数字
来源：http://dali.wangshuangyany.cn/Article/details/gtsdkqrycr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jqgfzy.top/Article/details/gtvbltxrxv.html

[S51] C++：显式类型转换
来源：http://dali.kuanghao11.cn/Article/details/gtjooghozy.html

static_cast<double>(a) / b
来源：http://dali.jinqigfzy.top/Article/details/gtuewqemdj.html

[S52] C++：const 与 noexcept
来源：http://dali.aibaodan.cn/Article/details/gthujavfzt.html

int size() const noexcept { return n_; }
来源：http://dali.xuetiantiany.cn/Article/details/gtlsgghnyp.html

[S53] C++：移动语义
来源：http://dali.shuidangran.top/Article/details/gtvkenxsja.html

std::vector<int> w = std::move(v);
来源：http://dali.pycfn.com/Article/details/gtmjlenpdi.html

[S54] C++：异常处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiyfkipll.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenlongwang.top/Article/details/gtolcbpjen.html

[S55] C++：结构化绑定
来源：http://dali.zhengqikj.top/Article/details/gtcdhhepgw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gotoacloud.top/Article/details/gtukszqhuh.html

[S56] C++：optional
来源：http://dali.gaohongyu789.top/Article/details/gttafohehb.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cucudq.cn/Article/details/gtsadljtla.html

[S57] C++：编译期常量
来源：http://dali.ybcxt.top/Article/details/gtcpnsnjfd.html

constexpr int N = 10;
来源：http://dali.zdqjudy.top/Article/details/gtikwiucnr.html

[S58] C++：命名空间
来源：http://dali.chenlongwang.top/Article/details/gtlslmebya.html

namespace ns { int f() { return 1; } }
来源：http://dali.cqqwz.cn/Article/details/gttkosnjes.html

[S59] C++：静态断言
来源：http://dali.andypj.xyz/Article/details/gtsxqwzgfi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.gotoacloud.top/Article/details/gtfeengwxf.html

[S60] C++：遍历并删除元素
来源：http://dali.kuanghao11.cn/Article/details/gtwucolhvd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhixingplan.top/Article/details/gtwsrciuan.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtozqrbjwq.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gzhubu.top/Article/details/gttjdsbjdp.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtezsfksvz.html

[T01] Kotlin：Hello World
来源：http://dali.cdnleiting.top/Article/details/gtoaskkgzd.html

println("Hello")
来源：http://dali.jianghu66.top/Article/details/gtfvqpmqco.html

[T02] Kotlin：变量
来源：http://dali.zhengqikj.top/Article/details/gtaimoilab.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shuidangran.top/Article/details/gtjepgkvrt.html

[T03] Kotlin：字符串模板
来源：http://dali.cqqwz.cn/Article/details/gtzmahfjpa.html

"值: $b"
来源：http://dali.shzxlz.cn/Article/details/gtlqlvrmvy.html

[T04] Kotlin：空安全
来源：http://dali.feifeiyinyue.top/Article/details/gtedrpfmwx.html

val n: String? = null;  n?.length
来源：http://dali.xinyue.icu/Article/details/gtnyatwzpc.html

[T05] Kotlin：when 表达式
来源：http://dali.aibaodan.cn/Article/details/gtiqxjbczm.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.smart0.xyz/Article/details/gtckkafgqw.html

[T06] Kotlin：集合映射
来源：http://dali.cheryme.top/Article/details/gtbropzjeg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhixingplan.top/Article/details/gtlostopfu.html

[T07] Kotlin：集合过滤
来源：http://dali.cashguo.top/Article/details/gtsafjwdwv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hysaishi.cn/Article/details/gtnxezdowx.html

[T08] Kotlin：数据类
来源：http://dali.wangdashe.top/Article/details/gtcpczaisq.html

data class User(val name: String, val age: Int)
来源：http://dali.cashguo.top/Article/details/gtytqezegr.html

[T09] Kotlin：扩展函数
来源：http://dali.pycfn.com/Article/details/gtdvhepjeg.html

fun String.exclaim() = this + "!"
来源：http://dali.guannengcc.top/Article/details/gtkbkqpqcc.html

[T10] Kotlin：默认参数
来源：http://dali.yvedp.cn/Article/details/gtzlujwtex.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shuidangran.top/Article/details/gthelvxqcy.html

[T11] Kotlin：协程
来源：http://dali.meibo888.top/Article/details/gtfcjsuvqy.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.fzhhl.top/Article/details/gtoffqvweh.html

[T12] Kotlin：解构声明
来源：http://dali.aizwys.cn/Article/details/gtaioiysvo.html

val (a, b) = Pair(1, 2)
来源：http://dali.xuetiantiany.cn/Article/details/gtfkthmacz.html

[T13] Kotlin：只读 Map
来源：http://dali.svipenyu.cn/Article/details/gtkfwvvicr.html

val m = mapOf("a" to 1)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkbukdyig.html

[T14] Kotlin：循环
来源：http://dali.wangdashe.top/Article/details/gtaxuzoofe.html

for (i in 1..10) println(i)
来源：http://dali.cashguo.top/Article/details/gtckrvbyin.html

[T15] Kotlin：接口
来源：http://dali.sweek.top/Article/details/gteylclmcd.html

interface Shape { fun area(): Double }
来源：http://dali.wangshuangyany.cn/Article/details/gtmpkydfal.html

[T16] Swift：Hello World
来源：http://dali.birdmap.top/Article/details/gtpsaaezai.html

print("Hello")
来源：http://dali.yj20258.top/Article/details/gtngpekmlv.html

[T17] Swift：变量与常量
来源：http://dali.dianchejie.cn/Article/details/gtlpsxwgsl.html

var a = 1;  let b = 2
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzupdnczk.html

[T18] Swift：字符串插值
来源：http://dali.vqdsnc.cn/Article/details/gtxujptyak.html

"值: \(b)"
来源：http://dali.daxiang520.top/Article/details/gtmikfymex.html

[T19] Swift：可选绑定
来源：http://dali.cheryme.top/Article/details/gtcpbevpcm.html

if let n = opt { print(n) }
来源：http://dali.gaohongyu789.top/Article/details/gtphygglpn.html

[T20] Swift：数组操作
来源：http://dali.nwbrower.top/Article/details/gtlzfypnpc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shuidangran.top/Article/details/gtdokyxpap.html

[T21] Swift：遍历
来源：http://dali.sxryk.cn/Article/details/gtaewfcyml.html

for x in a { print(x) }
来源：http://dali.xylfe.cn/Article/details/gtwdtedmth.html

[T22] Swift：字典
来源：http://dali.nwbrower.top/Article/details/gthxlskqmh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.chenjidiqi.icu/Article/details/gtnynqnlvq.html

[T23] Swift：函数
来源：http://dali.xinyue.icu/Article/details/gtzhwmeuyq.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrlrjirhi.html

[T24] Swift：闭包
来源：http://dali.tianlin.xyz/Article/details/gtncttxrbf.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.guowangkeji.top/Article/details/gtuznhciis.html

[T25] Swift：结构体
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjihcajeo.html

struct P { var x: Int }
来源：http://dali.shzxlz.cn/Article/details/gtpfqqbxum.html

[T26] Swift：类与重写
来源：http://dali.hywenlv.cn/Article/details/gtjdpumpke.html

class A: Base { override func f() {} }
来源：http://dali.iojbl.cn/Article/details/gtsgnzixec.html

[T27] Swift：错误处理
来源：http://dali.hammf.cn/Article/details/gtqlihbdir.html

do { try f() } catch { print(error) }
来源：http://dali.xinyue.icu/Article/details/gtaufxwfql.html

[T28] Swift：枚举
来源：http://dali.aizwys.cn/Article/details/gtyugcoojv.html

enum Color { case red, green }
来源：http://dali.ydzc1.top/Article/details/gtfilfxwiy.html

[T29] Swift：guard 提前返回
来源：http://dali.yuanzhike.top/Article/details/gtubpktnwc.html

guard let x = opt else { return }
来源：http://dali.xuanzx.com/Article/details/gttcsbzcju.html

[T30] Swift：协议
来源：http://dali.hywenlv.cn/Article/details/gthdhbgfls.html

protocol Shape { func area() -> Double }
来源：http://dali.yj20258.top/Article/details/gtnnziewjw.html

[T31] Lua：Hello World
来源：http://dali.316326.xyz/Article/details/gtuiyybnuc.html

print("Hello")
来源：http://dali.zycfv.cn/Article/details/gtsrnykuir.html

[T32] Lua：局部变量
来源：http://dali.gzhubu.top/Article/details/gtpyzmqtoy.html

local a = 1
来源：http://dali.fengsongda.top/Article/details/gtmedwwfhw.html

[T33] Lua：表（数组）
来源：http://dali.zhixingplan.top/Article/details/gtuujxbkqg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.sysykeji.top/Article/details/gtptjjwkqh.html

[T34] Lua：遍历表
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuwjdarcd.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhoulong.xyz/Article/details/gtxycnoqsn.html

[T35] Lua：字典表
来源：http://dali.tanke756.top/Article/details/gtinnxlwvm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hfpthk.cn/Article/details/gtevkebnoe.html

[T36] Lua：函数
来源：http://dali.yuxming.cn/Article/details/gtobfktpel.html

function add(a, b) return a + b end
来源：http://dali.zdqjudy.top/Article/details/gtrrsujyai.html

[T37] Lua：字符串拼接
来源：http://dali.yuanzhike.top/Article/details/gtbjvligae.html

"a" .. "b"
来源：http://dali.xuanzx.com/Article/details/gtnyjkfpjc.html

[T38] Lua：条件
来源：http://dali.xuetiantiany.cn/Article/details/gtsjidwisg.html

if x > 0 then print("正") end
来源：http://dali.9152youxi.cn/Article/details/gtoishxrlo.html

[T39] Lua：模式匹配
来源：http://dali.xinyue.icu/Article/details/gtcegpcsqh.html

string.find(s, "%d+")
来源：http://dali.gotoacloud.top/Article/details/gttkuprtdc.html

[T40] Lua：元表
来源：http://dali.jinqigfzy.top/Article/details/gthgxcupym.html

setmetatable({}, { __index = base })
来源：http://dali.bjfxy.top/Article/details/gtrcjpwrro.html

[T41] Perl：Hello World
来源：http://dali.jiagoushi.top/Article/details/gthskswioe.html

print "Hello\n";
来源：http://dali.gotoacloud.top/Article/details/gtjlewbris.html

[T42] Perl：变量类型
来源：http://dali.haohaochexian.top/Article/details/gttbvigzbd.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.redwolf501.top/Article/details/gtjtyuhmsf.html

[T43] Perl：字符串插值
来源：http://dali.ybcxt.top/Article/details/gtoatenryv.html

"值: $a"
来源：http://dali.smart0.xyz/Article/details/gtoxpjkxaf.html

[T44] Perl：条件
来源：http://dali.andypj.xyz/Article/details/gtiptwyosn.html

if ($a > 0) { print "正"; }
来源：http://dali.jqgufenzy.top/Article/details/gtkmosaaun.html

[T45] Perl：数组遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzrvsdwum.html

for my $x (@arr) { print $x; }
来源：http://dali.yj20258888.top/Article/details/gtyymbiqsp.html

[T46] Perl：哈希操作
来源：http://dali.chenzaomai.com/Article/details/gtygdhkemm.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtwtaaesuu.html


<!-- 参考信息 -->