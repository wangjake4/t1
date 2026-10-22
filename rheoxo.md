代发 wailian999

find . -name "*.log" -type f
来源：http://dali.jinqigufen.top/Article/details/gtqpdjvqpj.html

[R44] 按修改时间查找
来源：http://dali.zhiwuduotai.top/Article/details/gtxxhakmxj.html

find . -mtime -7 -type f
来源：http://dali.meibo888.top/Article/details/gtqcwkikyk.html

[R45] 批量删除
来源：http://dali.ehwqpu.com/Article/details/gtwjslldev.html

find . -name "*.tmp" -delete
来源：http://dali.yonumen.top/Article/details/gtqsngnuqn.html

[R46] 递归替换文件内容
来源：http://dali.9152youxi.cn/Article/details/gtyexlwhat.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hnqzz.top/Article/details/gtoftaqvgu.html

[R47] sed 单行替换
来源：http://dali.c1oappe.top/Article/details/gtmxhkknmz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhengqikj.top/Article/details/gtlncaalmf.html

[R48] awk 取指定列
来源：http://dali.svipenyu.cn/Article/details/gtgyjmofhz.html

awk '{print $1, $3}' a.txt
来源：http://dali.nanxinkj.top/Article/details/gtaseczqpc.html

[R49] awk 带条件
来源：http://dali.gaohongyu789.top/Article/details/gtzwlsedrn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ppjwa.cn/Article/details/gtlluoonvd.html

[R50] awk 求和
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlysqavfq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.9152youxi.cn/Article/details/gtvvpvdefn.html

[R51] 排序去重取前几
来源：http://dali.tian-w.cn/Article/details/gtylpcwass.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.c1oappe.top/Article/details/gthdheythr.html

[R52] 统计行数
来源：http://dali.xylfe.cn/Article/details/gtcbvsqjgb.html

wc -l a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtaqechlql.html

[R53] 查看文件头与实时尾
来源：http://dali.316326.xyz/Article/details/gtujojrsvu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.guannengcc.top/Article/details/gtkvelxbnm.html

[R54] 比较两个文件
来源：http://dali.redwolf501.top/Article/details/gtdzsvexph.html

diff a.txt b.txt
来源：http://dali.smart0.xyz/Article/details/gtjfnfypwi.html

[R55] 压缩与解压
来源：http://dali.yonumen.top/Article/details/gthcglputu.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.dashuyun.cn/Article/details/gtefgnfuhh.html

[R56] 远程拷贝
来源：http://dali.xylfe.cn/Article/details/gtgwywsjia.html

scp file user@host:/path/
来源：http://dali.ppjwa.cn/Article/details/gtyrmgcfrr.html

[R57] 远程执行命令
来源：http://dali.aibaodan.cn/Article/details/gtnifegxjl.html

ssh user@host 'uptime'
来源：http://dali.sxryk.cn/Article/details/gtcfilvpdj.html

[R58] 下载文件
来源：http://dali.jyoumei.cn/Article/details/gtskwpbhpq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nanxuanxn.top/Article/details/gtuxfydzdc.html

[R59] 发 POST JSON
来源：http://dali.nwbrower.top/Article/details/gtzubcfsbd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.tianlin.xyz/Article/details/gthwajevxn.html

[R60] 只看 HTTP 状态码
来源：http://dali.tianlin.xyz/Article/details/gtctzsrehb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.redwolf501.top/Article/details/gtsqswdedu.html

[R61] 磁盘占用
来源：http://dali.yj20258.top/Article/details/gthwoilham.html

df -h;  du -sh *
来源：http://dali.jinqigufen.top/Article/details/gtflosjggn.html

[R62] 找最占空间的文件
来源：http://dali.pycfn.com/Article/details/gtjbcxbyql.html

du -ah . | sort -rh | head -10
来源：http://dali.iojbl.cn/Article/details/gtziekbtje.html

[R63] 内存与进程
来源：http://dali.guannengcc.top/Article/details/gtfiqkhesb.html

free -h;  ps aux | grep nginx
来源：http://dali.gotoacloud.top/Article/details/gtkmndpqts.html

[R64] 结束进程
来源：http://dali.chenlongwang.top/Article/details/gtfuygcuwo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhixingplan.top/Article/details/gtzzfakmrx.html

[R65] 查看端口占用
来源：http://dali.sxryk.cn/Article/details/gtrdwqphuo.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jqgfzy.top/Article/details/gtemwclknq.html

[R66] 定时任务
来源：http://dali.jinqigfzy.top/Article/details/gtcrudtwgt.html

crontab -e;  crontab -l
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpcwpkckq.html

[R67] 生成随机十六进制串
来源：http://dali.jianghu66.top/Article/details/gthwpiqjev.html

openssl rand -hex 16
来源：http://dali.hfpthk.cn/Article/details/gtvqwzjgng.html

[R68] 计算文件校验值
来源：http://dali.gotoacloud.top/Article/details/gtozstsnhh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xuanzx.com/Article/details/gtowljqgcn.html

[R69] 生成随机密码
来源：http://dali.chenjidiqi.icu/Article/details/gtsekolage.html

head -c 16 /dev/urandom | base64
来源：http://dali.xziqi.cn/Article/details/gtnbcuknrf.html

[R70] 时间戳与互转
来源：http://dali.yonumen.top/Article/details/gtqralngki.html

date +%s;  date -d @1700000000
来源：http://dali.pengpengdd.cyou/Article/details/gtkcsyicor.html

[R71] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gticaauvpj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhoulong.xyz/Article/details/gthteexbob.html

[R72] 等待端口就绪
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwhiwmlke.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sufxvd.cn/Article/details/gtntlyancz.html

[R73] 分割大日志
来源：http://dali.hnxiangtu.top/Article/details/gtwaphubai.html

split -l 1000 big.log part_
来源：http://dali.jqgufenzy.top/Article/details/gtbfuiruuh.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gtdkdgiauw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.havefunace.top/Article/details/gtwimsxpnn.html

[R75] 导出环境变量
来源：http://dali.pengpengdd.cyou/Article/details/gtjnqetqys.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.nwbrower.top/Article/details/gtlqfdfipe.html

[R76] 使用临时文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtslujjksu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhiwuduotai.top/Article/details/gttyevcdwy.html

[R77] 读取用户输入
来源：http://dali.yj202588.top/Article/details/gtxxlqmeby.html

read -rp "请输入: " ans
来源：http://dali.meibo888.top/Article/details/gtweqdkipj.html

[R78] 交互式菜单
来源：http://dali.cqqwz.cn/Article/details/gtgqowxbra.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.pycfn.com/Article/details/gtjsppkgrh.html

[R79] 解析命令行选项
来源：http://dali.chenlongwang.top/Article/details/gthycjaegg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yvedp.cn/Article/details/gthwiembnp.html

[R80] 查看脚本执行耗时
来源：http://dali.yonumen.top/Article/details/gtruaxjfnr.html

time ./run.sh
来源：http://dali.yonumen.top/Article/details/gtjsjxlzma.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtargfoiov.html

S. C / C++ 专题
来源：http://dali.ydzc1.top/Article/details/gtcdtvntrh.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtkrtpqqsi.html

[S01] C：Hello World
来源：http://dali.sweek.top/Article/details/gtnalfwldw.html

#include <stdio.h>
来源：http://dali.zhongyouzk.top/Article/details/gthboktiim.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yonumen.top/Article/details/gthhiwsiau.html

[S02] C：变量与格式化输出
来源：http://dali.quarkkingdee.top/Article/details/gtloiqvhhg.html

int a = 10; printf("%d\n", a);
来源：http://dali.wangshuangyany.cn/Article/details/gthlpfhtqi.html

[S03] C：读入整数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkexjlmfq.html

int x; scanf("%d", &x);
来源：http://dali.fengsongda.top/Article/details/gtqazlsxyh.html

[S04] C：字符串复制
来源：http://dali.shzxlz.cn/Article/details/gtqhhmzzfh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.0kj1m.cn/Article/details/gtypjwgxzq.html

[S05] C：字符串长度
来源：http://dali.jlsjyb.cn/Article/details/gtglpbnpeh.html

strlen(s)
来源：http://dali.tanke756.top/Article/details/gtuzynzcco.html

[S06] C：字符串比较
来源：http://dali.hywenlv.cn/Article/details/gtoyvhpvcz.html

strcmp(a, b) == 0
来源：http://dali.sysykeji.top/Article/details/gtrltpcvyy.html

[S07] C：数组遍历求和
来源：http://dali.chenzaomai.com/Article/details/gtxqafyboz.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhoulong.xyz/Article/details/gtaedqnffw.html

[S08] C：动态内存分配与释放
来源：http://dali.cheryme.top/Article/details/gtfnykqaeq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqyfkitsg.html

[S09] C：结构体定义与初始化
来源：http://dali.hongshengwenyu.top/Article/details/gtxkedwgfd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shuidangran.top/Article/details/gtoheftbpd.html

[S10] C：指针与解引用
来源：http://dali.hfpthk.cn/Article/details/gtvplowkjt.html

int *p = &a;  *p = 5;
来源：http://dali.316326.xyz/Article/details/gtrpaxwzqk.html

[S11] C：逐行读文件
来源：http://dali.smart0.xyz/Article/details/gttogcjttr.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.guowangkeji.top/Article/details/gtvxhlidhr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinqigufen.top/Article/details/gtxvicblsj.html

fclose(f);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqqsrzsir.html

[S12] C：写文件
来源：http://dali.jianghu66.top/Article/details/gtlhjddqyi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jqgfzy.top/Article/details/gtixozkkac.html

[S13] C：宏定义
来源：http://dali.sxryk.cn/Article/details/gtbmvdajmw.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gotoacloud.top/Article/details/gtqdbcnetv.html

[S14] C：枚举
来源：http://dali.yj202588.top/Article/details/gtupkqbups.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gogol.net.cn/Article/details/gthmahokdd.html

[S15] C：类型转换
来源：http://dali.cdnleiting.top/Article/details/gtathpocda.html

(double) a / b
来源：http://dali.0kj1m.cn/Article/details/gtlelaynch.html

[S16] C：位操作置位
来源：http://dali.yueranfly.top/Article/details/gtodpepomk.html

x |= (1 << 3);
来源：http://dali.xinyue.icu/Article/details/gtiwsahows.html

[S17] C：安全拼接字符串
来源：http://dali.birdmap.top/Article/details/gtaqaoipiv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.cdnleiting.top/Article/details/gtopldmlug.html

[S18] C：命令行参数
来源：http://dali.cheryme.top/Article/details/gttxqvozea.html

int main(int argc, char **argv)
来源：http://dali.ehwqpu.com/Article/details/gtzmfjqqzz.html

[S19] C：快速排序
来源：http://dali.bjfxy.top/Article/details/gtqxqzooum.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinqigufen.top/Article/details/gtpjkdsepf.html

[S20] C：二分查找
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnxbtayad.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.fzhhl.top/Article/details/gtsnkgxqky.html

[S21] C：字符类别判断
来源：http://dali.gzhubu.top/Article/details/gtjznujahy.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.guowangkeji.top/Article/details/gtndvninaj.html

[S22] C：字符串转数字
来源：http://dali.yj20258.top/Article/details/gtyhujnhdl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shanyushiyangtech.top/Article/details/gtfbaafzlj.html

[S23] C：随机数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqebwkset.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.haohaochexian.top/Article/details/gtbunmnyds.html

[S24] C：获取本地时间
来源：http://dali.jianghu66.top/Article/details/gtwdhmxrml.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.bjfxy.top/Article/details/gtepenagds.html

[S25] C：内存拷贝
来源：http://dali.snrcjt.cn/Article/details/gtlgiqrqks.html

memcpy(dst, src, n);
来源：http://dali.guannengcc.top/Article/details/gtbtfxulxt.html

[S26] C：内存清零
来源：http://dali.nwbrower.top/Article/details/gtezlowcye.html

memset(a, 0, sizeof a);
来源：http://dali.cheryme.top/Article/details/gtxkoylxbl.html

[S27] C：定义常量
来源：http://dali.pycfn.com/Article/details/gtamtpqask.html

const double PI = 3.14159;
来源：http://dali.xziqi.cn/Article/details/gtcgqytrhr.html

[S28] C：静态变量
来源：http://dali.pycfn.com/Article/details/gtpynrfubw.html

static int counter = 0;
来源：http://dali.gzhubu.top/Article/details/gtfemunlnf.html

[S29] C：变参函数
来源：http://dali.sufxvd.cn/Article/details/gtbruwyhlq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hnxiangtu.top/Article/details/gteybbobro.html

[S30] C：头文件保护
来源：http://dali.daria6918.cn/Article/details/gtfxwpjjka.html

#ifndef X_H
来源：http://dali.yj20258888.top/Article/details/gtgbqkksnb.html

#define X_H
来源：http://dali.gaohongyu789.top/Article/details/gtnnqvlrux.html

#endif
来源：http://dali.jinqigfzy.top/Article/details/gtnqegctah.html

[S31] C++：Hello World
来源：http://dali.birdmap.top/Article/details/gtujqgkfqn.html

#include <iostream>
来源：http://dali.hnxiangtu.top/Article/details/gtnaizvltn.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.wangshuangyany.cn/Article/details/gtdyffhmso.html

[S32] C++：字符串
来源：http://dali.cqqwz.cn/Article/details/gtuwoddevq.html

std::string s = "hi";  s += "!";
来源：http://dali.yueranfly.top/Article/details/gtmylvnsbm.html

[S33] C++：vector 增删
来源：http://dali.cashguo.top/Article/details/gtnrdoxrsf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cdnleiting.top/Article/details/gtdxvlwmgh.html

[S34] C++：遍历 vector
来源：http://dali.xuetiantiany.cn/Article/details/gtfznsafax.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ppjwa.cn/Article/details/gtgyvlruie.html

[S35] C++：map
来源：http://dali.mhx1999.top/Article/details/gtzzoakuvf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtedzlyroy.html

[S36] C++：unordered_map
来源：http://dali.meibo888.top/Article/details/gtaixraway.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhixingplan.top/Article/details/gtlqpiucbq.html

[S37] C++：set
来源：http://dali.shanyushiyangtech.top/Article/details/gtugcmszhz.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.pycfn.com/Article/details/gtgdfqzuwp.html

[S38] C++：排序
来源：http://dali.jinqigfzy.top/Article/details/gtpneoduop.html

std::sort(v.begin(), v.end());
来源：http://dali.daxiang520.top/Article/details/gtrlhoxglq.html

[S39] C++：自定义比较器排序
来源：http://dali.bjfxy.top/Article/details/gtheslslnp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.tian-w.cn/Article/details/gtltjvemcm.html

[S40] C++：查找元素
来源：http://dali.tanke756.top/Article/details/gtqwhxhtfs.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cdnleiting.top/Article/details/gtbwibmnli.html

[S41] C++：类与构造函数
来源：http://dali.meibo888.top/Article/details/gtqerjkkoj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yanxiufei.cn/Article/details/gtriohmdoc.html

[S42] C++：继承与虚函数
来源：http://dali.smart0.xyz/Article/details/gtrwpleapb.html

class B : public Base { public: void f() override {} };
来源：http://dali.nwbrower.top/Article/details/gtzmjfpnsc.html

[S43] C++：智能指针
来源：http://dali.yonumen.top/Article/details/gtjjrnkthg.html

auto p = std::make_unique<int>(5);
来源：http://dali.yj20258888.top/Article/details/gtflkvfvcl.html

[S44] C++：引用传参
来源：http://dali.daxiang520.top/Article/details/gtutvkivlg.html

void inc(int &x) { ++x; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtidhhlmbc.html

[S45] C++：lambda
来源：http://dali.shzxlz.cn/Article/details/gtkuuldtnv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shangyingyoupin.top/Article/details/gtstwycqfg.html

[S46] C++：函数模板
来源：http://dali.ppjwa.cn/Article/details/gtxvmxpzjd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.pycfn.com/Article/details/gtylamdayf.html

[S47] C++：结构化绑定遍历
来源：http://dali.yonumen.top/Article/details/gtceihpakq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yj202588.top/Article/details/gtcljecbwn.html

[S48] C++：逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gttuwrmmhi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shanyushiyangtech.top/Article/details/gtjbhhabie.html

while (std::getline(in, line)) { }
来源：http://dali.chenzaomai.com/Article/details/gtkzdrndnd.html

[S49] C++：写文件
来源：http://dali.gogol.net.cn/Article/details/gtwopqigvq.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.guowangkeji.top/Article/details/gtapfuyuzd.html

[S50] C++：格式化数字
来源：http://dali.svipenyu.cn/Article/details/gttlvtdnmv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yangfankeji.com/Article/details/gtjazqaxvk.html

[S51] C++：显式类型转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsdoncwly.html

static_cast<double>(a) / b
来源：http://dali.dashuyun.cn/Article/details/gtqsxblonf.html

[S52] C++：const 与 noexcept
来源：http://dali.jianghu66.top/Article/details/gtrknsvewk.html

int size() const noexcept { return n_; }
来源：http://dali.pycfn.com/Article/details/gtfxpuziag.html

[S53] C++：移动语义
来源：http://dali.sysykeji.top/Article/details/gthgcxnpoh.html

std::vector<int> w = std::move(v);
来源：http://dali.redwolf501.top/Article/details/gtybfwwbbf.html

[S54] C++：异常处理
来源：http://dali.svipenyu.cn/Article/details/gtnmqmhkgk.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.dashuyun.cn/Article/details/gtyucmfstn.html

[S55] C++：结构化绑定
来源：http://dali.xuanzx.com/Article/details/gtsvvwlmuy.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.havefunace.top/Article/details/gtysrabtew.html

[S56] C++：optional
来源：http://dali.jyoumei.cn/Article/details/gtugilgufo.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yvedp.cn/Article/details/gthdbuveim.html

[S57] C++：编译期常量
来源：http://dali.yonumen.top/Article/details/gtlbibwtlp.html

constexpr int N = 10;
来源：http://dali.dashuyun.cn/Article/details/gtdcjwsefo.html

[S58] C++：命名空间
来源：http://dali.wangdashe.top/Article/details/gtoxuhlbzm.html

namespace ns { int f() { return 1; } }
来源：http://dali.smart0.xyz/Article/details/gtcmvlguoy.html

[S59] C++：静态断言
来源：http://dali.hfpthk.cn/Article/details/gtiwuhxaen.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.pycfn.com/Article/details/gtlgbjfqzr.html

[S60] C++：遍历并删除元素
来源：http://dali.tian-w.cn/Article/details/gtjsdyoyzk.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.tian-w.cn/Article/details/gtokpchdpa.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gtzhuqfezg.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.daria6918.cn/Article/details/gtashzkgfz.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gthflpvhse.html

[T01] Kotlin：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtfazlxqpm.html

println("Hello")
来源：http://dali.tianlin.xyz/Article/details/gtazovszkn.html

[T02] Kotlin：变量
来源：http://dali.jlsjyb.cn/Article/details/gtymcwuxpz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.sxryk.cn/Article/details/gteeoqroxr.html

[T03] Kotlin：字符串模板
来源：http://dali.shangyingyoupin.top/Article/details/gtlmqqnmil.html

"值: $b"
来源：http://dali.yangfankeji.com/Article/details/gtytiblpzq.html

[T04] Kotlin：空安全
来源：http://dali.zhengqikj.top/Article/details/gtrmnwerir.html

val n: String? = null;  n?.length
来源：http://dali.sufxvd.cn/Article/details/gtbbqlkejb.html

[T05] Kotlin：when 表达式
来源：http://dali.jiagoushi.top/Article/details/gtxnizaqgt.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhongyouzk.top/Article/details/gtwctzunjq.html

[T06] Kotlin：集合映射
来源：http://dali.hnqzz.top/Article/details/gtnqdacaic.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yj202588.top/Article/details/gtutrthpvu.html

[T07] Kotlin：集合过滤
来源：http://dali.cashguo.top/Article/details/gtitvfshye.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.chenlongwang.top/Article/details/gtsijrnott.html

[T08] Kotlin：数据类
来源：http://dali.snrcjt.cn/Article/details/gtkotchziv.html

data class User(val name: String, val age: Int)
来源：http://dali.feifeiyinyue.top/Article/details/gtdbgsymey.html

[T09] Kotlin：扩展函数
来源：http://dali.ybcxt.top/Article/details/gtlgjraxts.html

fun String.exclaim() = this + "!"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcrkpbgiv.html

[T10] Kotlin：默认参数
来源：http://dali.zhongyouzk.top/Article/details/gtkpviwibn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ehwqpu.com/Article/details/gttjxfupxl.html

[T11] Kotlin：协程
来源：http://dali.zhoulong.xyz/Article/details/gtxalikkka.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sweek.top/Article/details/gtnevhkgyz.html

[T12] Kotlin：解构声明
来源：http://dali.shanyushiyangkeji.top/Article/details/gthbydqosw.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhengqikj.top/Article/details/gtwsydxvxg.html

[T13] Kotlin：只读 Map
来源：http://dali.nanxuanxn.top/Article/details/gtjcdykfea.html

val m = mapOf("a" to 1)
来源：http://dali.pycfn.com/Article/details/gtnuitgrvu.html

[T14] Kotlin：循环
来源：http://dali.daxiang520.top/Article/details/gtsghdnoam.html

for (i in 1..10) println(i)
来源：http://dali.sufxvd.cn/Article/details/gtfkurhflg.html

[T15] Kotlin：接口
来源：http://dali.yvedp.cn/Article/details/gttzkjybgw.html

interface Shape { fun area(): Double }
来源：http://dali.shangyingyoupin.top/Article/details/gtpqqgteof.html

[T16] Swift：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtvinqacos.html

print("Hello")
来源：http://dali.shzxlz.cn/Article/details/gthupiclog.html

[T17] Swift：变量与常量
来源：http://dali.tian-w.cn/Article/details/gtnjvjoyjo.html

var a = 1;  let b = 2
来源：http://dali.zhijiandao.cn/Article/details/gtcdxrtbwq.html

[T18] Swift：字符串插值
来源：http://dali.yonumen.top/Article/details/gthoyhroqx.html

"值: \(b)"
来源：http://dali.xylfe.cn/Article/details/gtzogdpcbz.html

[T19] Swift：可选绑定
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgsmdqgky.html

if let n = opt { print(n) }
来源：http://dali.zhoulong.xyz/Article/details/gteydtlvtm.html

[T20] Swift：数组操作
来源：http://dali.dianchejie.cn/Article/details/gtaamxqnbt.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtubrxkxlw.html

[T21] Swift：遍历
来源：http://dali.gogol.net.cn/Article/details/gtnnwiqlht.html

for x in a { print(x) }
来源：http://dali.pycfn.com/Article/details/gtefhvfntk.html

[T22] Swift：字典
来源：http://dali.yuxming.cn/Article/details/gtfnqxozpn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.cheryme.top/Article/details/gtujxrgkbv.html

[T23] Swift：函数
来源：http://dali.bjfxy.top/Article/details/gtlnsinpfi.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.cashguo.top/Article/details/gtbnsmlmmz.html

[T24] Swift：闭包
来源：http://dali.bjfxy.top/Article/details/gtjfvmjuwm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.ppjwa.cn/Article/details/gtaugihrpq.html

[T25] Swift：结构体
来源：http://dali.tian-w.cn/Article/details/gtdhrvxukv.html

struct P { var x: Int }
来源：http://dali.jinqigfzy.top/Article/details/gtbudxotpa.html

[T26] Swift：类与重写
来源：http://dali.cashguo.top/Article/details/gtahlnohxf.html

class A: Base { override func f() {} }
来源：http://dali.shzxlz.cn/Article/details/gtotnlnxlb.html

[T27] Swift：错误处理
来源：http://dali.yongpay.top/Article/details/gtahiiteui.html

do { try f() } catch { print(error) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtiqvpawve.html

[T28] Swift：枚举
来源：http://dali.9152youxi.cn/Article/details/gtwzdmckpk.html

enum Color { case red, green }
来源：http://dali.kuanghao11.cn/Article/details/gtmandxbza.html

[T29] Swift：guard 提前返回
来源：http://dali.kuanghao11.cn/Article/details/gtuatmdqhx.html

guard let x = opt else { return }
来源：http://dali.316326.xyz/Article/details/gtaygciaaa.html

[T30] Swift：协议
来源：http://dali.yj20258.top/Article/details/gtkzvglzmy.html

protocol Shape { func area() -> Double }
来源：http://dali.guannengcc.top/Article/details/gttlaulihy.html

[T31] Lua：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtvvqgofoa.html

print("Hello")
来源：http://dali.hysaishi.cn/Article/details/gtcvganyel.html

[T32] Lua：局部变量
来源：http://dali.wangshuangyany.cn/Article/details/gthpvtwdqr.html

local a = 1
来源：http://dali.yueranfly.top/Article/details/gtdnxagaaa.html

[T33] Lua：表（数组）
来源：http://dali.vqdsnc.cn/Article/details/gtuphfxden.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.snrcjt.cn/Article/details/gtnltmlulf.html

[T34] Lua：遍历表
来源：http://dali.nanxinkj.top/Article/details/gtyvvuaeeo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jinyuanbaomall.cn/Article/details/gteidjuooc.html

[T35] Lua：字典表
来源：http://dali.xuetiantiany.cn/Article/details/gtnmeggrby.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yangfankeji.com/Article/details/gtnyzaolni.html

[T36] Lua：函数
来源：http://dali.zdqjudy.top/Article/details/gtrdcfyusy.html

function add(a, b) return a + b end
来源：http://dali.havefunace.top/Article/details/gtixhknoke.html

[T37] Lua：字符串拼接
来源：http://dali.zycfv.cn/Article/details/gtiplwhqgk.html

"a" .. "b"
来源：http://dali.zhixingplan.top/Article/details/gtqegvtovl.html

[T38] Lua：条件
来源：http://dali.gotoacloud.top/Article/details/gtpdcwaeht.html

if x > 0 then print("正") end
来源：http://dali.fzhhl.top/Article/details/gtnybrapfz.html

[T39] Lua：模式匹配
来源：http://dali.smart0.xyz/Article/details/gtmtkidtcw.html

string.find(s, "%d+")
来源：http://dali.zhengqikj.top/Article/details/gtwrmnpbcs.html

[T40] Lua：元表
来源：http://dali.kuanghao11.cn/Article/details/gtcgwjcial.html

setmetatable({}, { __index = base })
来源：http://dali.yonumen.top/Article/details/gtsadeehxn.html

[T41] Perl：Hello World
来源：http://dali.xylfe.cn/Article/details/gtkfzhdtpk.html

print "Hello\n";
来源：http://dali.gaohongyu789.top/Article/details/gtaktgqzwx.html

[T42] Perl：变量类型
来源：http://dali.9152youxi.cn/Article/details/gtftjjceeo.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.zhongyouzk.top/Article/details/gtizcufonk.html

[T43] Perl：字符串插值
来源：http://dali.hnqzz.top/Article/details/gtkcbbzhxh.html

"值: $a"
来源：http://dali.dashuyun.cn/Article/details/gtijbbyagf.html

[T44] Perl：条件
来源：http://dali.dashuyun.cn/Article/details/gtedxgfuvc.html

if ($a > 0) { print "正"; }
来源：http://dali.havefunace.top/Article/details/gtceqqommc.html

[T45] Perl：数组遍历
来源：http://dali.aibaodan.cn/Article/details/gtckugpmyn.html

for my $x (@arr) { print $x; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgonjqtva.html

[T46] Perl：哈希操作
来源：http://dali.yuxming.cn/Article/details/gtuzgjohcw.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.nwbrower.top/Article/details/gtqnnigfmb.html


<!-- 参考信息 -->