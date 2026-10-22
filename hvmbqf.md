代发 wailian999

find . -name "*.log" -type f
来源：http://dali.guowangkeji.top/Article/details/gt2oepemuyk.html

[R44] 按修改时间查找
来源：http://dali.sweek.top/Article/details/gt2elnrjwat.html

find . -mtime -7 -type f
来源：http://dali.ehwqpu.com/Article/details/gt2behdesdq.html

[R45] 批量删除
来源：http://dali.wangdashe.top/Article/details/gt2xlsyfmwi.html

find . -name "*.tmp" -delete
来源：http://dali.sysykeji.top/Article/details/gt2qvpvjptx.html

[R46] 递归替换文件内容
来源：http://dali.cdnleiting.top/Article/details/gt2askexkzw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.316326.xyz/Article/details/gt2ukdawkbd.html

[R47] sed 单行替换
来源：http://dali.smart0.xyz/Article/details/gt2ywqyfyad.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.nwbrower.top/Article/details/gt2xnxbyxtc.html

[R48] awk 取指定列
来源：http://dali.zdqjudy.top/Article/details/gt2irvzczpo.html

awk '{print $1, $3}' a.txt
来源：http://dali.vqdsnc.cn/Article/details/gt2htwfjfdd.html

[R49] awk 带条件
来源：http://dali.pycfn.com/Article/details/gt2zplhwwvn.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yj20258.top/Article/details/gt2ssswcitf.html

[R50] awk 求和
来源：http://dali.gogol.net.cn/Article/details/gt2gizkpeyf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhixingplan.top/Article/details/gt2hlocoujv.html

[R51] 排序去重取前几
来源：http://dali.ybcxt.top/Article/details/gt2iecftslr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ydzc1.top/Article/details/gt2kijgmnqe.html

[R52] 统计行数
来源：http://dali.ppjwa.cn/Article/details/gt2xmpznwft.html

wc -l a.txt
来源：http://dali.vqdsnc.cn/Article/details/gt2hgmalyqo.html

[R53] 查看文件头与实时尾
来源：http://dali.daxiang520.top/Article/details/gt2rgvlhwei.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mtcaegwf.html

[R54] 比较两个文件
来源：http://dali.chenlongwang.top/Article/details/gt2zmckknnt.html

diff a.txt b.txt
来源：http://dali.birdmap.top/Article/details/gt2ioskksud.html

[R55] 压缩与解压
来源：http://dali.jiagoushi.top/Article/details/gt2iawikgjh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.pengpengdd.cyou/Article/details/gt2ssjyyxbf.html

[R56] 远程拷贝
来源：http://dali.xylfe.cn/Article/details/gt2wrzmqjwm.html

scp file user@host:/path/
来源：http://dali.bjfxy.top/Article/details/gt2ghwnsimj.html

[R57] 远程执行命令
来源：http://dali.smart0.xyz/Article/details/gt2uufkvotw.html

ssh user@host 'uptime'
来源：http://dali.meibo888.top/Article/details/gt2buujxlsc.html

[R58] 下载文件
来源：http://dali.jqgufenzy.top/Article/details/gt2tiemsgdr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.dianchejie.cn/Article/details/gt2liigzbun.html

[R59] 发 POST JSON
来源：http://dali.hysaishi.cn/Article/details/gt2softuzjp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hnxiangtu.top/Article/details/gt2ixgmakry.html

[R60] 只看 HTTP 状态码
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2acfgroqi.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jlsjyb.cn/Article/details/gt2bybqqjyw.html

[R61] 磁盘占用
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yufajrxb.html

df -h;  du -sh *
来源：http://dali.pycfn.com/Article/details/gt2rqlufzft.html

[R62] 找最占空间的文件
来源：http://dali.gaohongyu789.top/Article/details/gt2qvtdmwsh.html

du -ah . | sort -rh | head -10
来源：http://dali.yvedp.cn/Article/details/gt2loseduvn.html

[R63] 内存与进程
来源：http://dali.9152youxi.cn/Article/details/gt2quoqwuty.html

free -h;  ps aux | grep nginx
来源：http://dali.ybcxt.top/Article/details/gt2qjdjokny.html

[R64] 结束进程
来源：http://dali.xylfe.cn/Article/details/gt2rmqoyvgz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jianghu66.top/Article/details/gt2dylcekcx.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2dnuqczbk.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.nanxinkj.top/Article/details/gt2kxiptlpb.html

[R66] 定时任务
来源：http://dali.yanxiufei.cn/Article/details/gt2tcfzdadt.html

crontab -e;  crontab -l
来源：http://dali.feifeiyinyue.top/Article/details/gt2ouobipxn.html

[R67] 生成随机十六进制串
来源：http://dali.jyoumei.cn/Article/details/gt2kjrrvnjs.html

openssl rand -hex 16
来源：http://dali.nwbrower.top/Article/details/gt2ouueqfwj.html

[R68] 计算文件校验值
来源：http://dali.redwolf501.top/Article/details/gt2hlqexuyq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.c1oappe.top/Article/details/gt2xmkzylxm.html

[R69] 生成随机密码
来源：http://dali.vqdsnc.cn/Article/details/gt2djcqqxcc.html

head -c 16 /dev/urandom | base64
来源：http://dali.jyoumei.cn/Article/details/gt2mwbtrxnc.html

[R70] 时间戳与互转
来源：http://dali.chenzaomai.com/Article/details/gt2dxtpeapa.html

date +%s;  date -d @1700000000
来源：http://dali.mhx1999.top/Article/details/gt2dkjqdgbc.html

[R71] 日期格式化
来源：http://dali.shzxlz.cn/Article/details/gt2igvdhlju.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ivvv.top/Article/details/gt2eyjfocgk.html

[R72] 等待端口就绪
来源：http://dali.xuetiantiany.cn/Article/details/gt2bdwgscte.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.havefunace.top/Article/details/gt2mtepxyav.html

[R73] 分割大日志
来源：http://dali.guannengcc.top/Article/details/gt2zowiuujx.html

split -l 1000 big.log part_
来源：http://dali.quarkkingdee.top/Article/details/gt2iaisyvih.html

[R74] 批量重命名
来源：http://dali.andypj.xyz/Article/details/gt2tltpbtih.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yueranfly.top/Article/details/gt2sxoxjrmo.html

[R75] 导出环境变量
来源：http://dali.snrcjt.cn/Article/details/gt2jzuwieou.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.redwolf501.top/Article/details/gt2nrfgixun.html

[R76] 使用临时文件
来源：http://dali.ydzc1.top/Article/details/gt2fmjzskhf.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zycfv.cn/Article/details/gt2wcqymmzb.html

[R77] 读取用户输入
来源：http://dali.vqdsnc.cn/Article/details/gt2mhncutrv.html

read -rp "请输入: " ans
来源：http://dali.cashguo.top/Article/details/gt2gqkvuymo.html

[R78] 交互式菜单
来源：http://dali.iojbl.cn/Article/details/gt2zurriduc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hnxiangtu.top/Article/details/gt2hsucjurx.html

[R79] 解析命令行选项
来源：http://dali.shuidangran.top/Article/details/gt2ysjmargx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dtruseor.html

[R80] 查看脚本执行耗时
来源：http://dali.smart0.xyz/Article/details/gt2uitcwqww.html

time ./run.sh
来源：http://dali.yongpay.top/Article/details/gt2kywnvmho.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2cmztjjnd.html

S. C / C++ 专题
来源：http://dali.pengpengdd.cyou/Article/details/gt2lnvnmjpz.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gt2vvnjsekz.html

[S01] C：Hello World
来源：http://dali.zdqjudy.top/Article/details/gt2hxeztyui.html

#include <stdio.h>
来源：http://dali.xinyue.icu/Article/details/gt2rjhbgqyg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yj20258.top/Article/details/gt2jsmhhpbk.html

[S02] C：变量与格式化输出
来源：http://dali.hfpthk.cn/Article/details/gt2wdsdivpv.html

int a = 10; printf("%d\n", a);
来源：http://dali.tanke756.top/Article/details/gt2bzqwqvcq.html

[S03] C：读入整数
来源：http://dali.yuanzhike.top/Article/details/gt2zlzrwmex.html

int x; scanf("%d", &x);
来源：http://dali.pycfn.com/Article/details/gt2wvwaewwp.html

[S04] C：字符串复制
来源：http://dali.chenjidiqi.icu/Article/details/gt2kjpmdiqi.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hywenlv.cn/Article/details/gt2grfovodo.html

[S05] C：字符串长度
来源：http://dali.xuanzx.com/Article/details/gt2ailzdmua.html

strlen(s)
来源：http://dali.yj202588.top/Article/details/gt2bjfwxdno.html

[S06] C：字符串比较
来源：http://dali.cashguo.top/Article/details/gt2bgtjgufo.html

strcmp(a, b) == 0
来源：http://dali.hongshengwenyu.top/Article/details/gt2ymhhqhzu.html

[S07] C：数组遍历求和
来源：http://dali.jinqigfzy.top/Article/details/gt2mqogwoxl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.sxryk.cn/Article/details/gt2dytpwdsm.html

[S08] C：动态内存分配与释放
来源：http://dali.cdnleiting.top/Article/details/gt2jdnoyyks.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.andypj.xyz/Article/details/gt2urfczvln.html

[S09] C：结构体定义与初始化
来源：http://dali.jlsjyb.cn/Article/details/gt2cycprnyn.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.fengsongda.top/Article/details/gt2rdqmfhuh.html

[S10] C：指针与解引用
来源：http://dali.meibo888.top/Article/details/gt2odmvgnff.html

int *p = &a;  *p = 5;
来源：http://dali.svipenyu.cn/Article/details/gt2frpokrom.html

[S11] C：逐行读文件
来源：http://dali.yj202588.top/Article/details/gt2ederozdb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.daxiang520.top/Article/details/gt2tjjknawg.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.tianlin.xyz/Article/details/gt2qjxmdjwr.html

fclose(f);
来源：http://dali.xylfe.cn/Article/details/gt2qdsrxazx.html

[S12] C：写文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lfvmifbk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xylfe.cn/Article/details/gt2lqjawthk.html

[S13] C：宏定义
来源：http://dali.dashuyun.cn/Article/details/gt2eopteugq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xuetiantiany.cn/Article/details/gt2zqvrhvdt.html

[S14] C：枚举
来源：http://dali.hammf.cn/Article/details/gt2zexarcwl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jianghu66.top/Article/details/gt2mrfmykyv.html

[S15] C：类型转换
来源：http://dali.nanxinkj.top/Article/details/gt2kwnolgqa.html

(double) a / b
来源：http://dali.ybcxt.top/Article/details/gt2ocmqecna.html

[S16] C：位操作置位
来源：http://dali.fzhhl.top/Article/details/gt2vpsvcxrr.html

x |= (1 << 3);
来源：http://dali.daria6918.cn/Article/details/gt2drzlhbmr.html

[S17] C：安全拼接字符串
来源：http://dali.zycfv.cn/Article/details/gt2xtlokhfm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.guannengcc.top/Article/details/gt2kqohdmyr.html

[S18] C：命令行参数
来源：http://dali.jiagoushi.top/Article/details/gt2vpvkfugs.html

int main(int argc, char **argv)
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sgsfuoch.html

[S19] C：快速排序
来源：http://dali.yanxiufei.cn/Article/details/gt2mozszphx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhoulong.xyz/Article/details/gt2hvfqcahk.html

[S20] C：二分查找
来源：http://dali.havefunace.top/Article/details/gt2heyelkie.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.wangdashe.top/Article/details/gt2wleydjjv.html

[S21] C：字符类别判断
来源：http://dali.pycfn.com/Article/details/gt2rjhakhfi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.guowangkeji.top/Article/details/gt2tgemaweq.html

[S22] C：字符串转数字
来源：http://dali.sxryk.cn/Article/details/gt2wjqizhgv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cheryme.top/Article/details/gt2xykfater.html

[S23] C：随机数
来源：http://dali.daxiang520.top/Article/details/gt2fwgpclxf.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.0kj1m.cn/Article/details/gt2iawmoqmo.html

[S24] C：获取本地时间
来源：http://dali.chenzaomai.com/Article/details/gt2pzwitkdh.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cqqwz.cn/Article/details/gt2dymnooot.html

[S25] C：内存拷贝
来源：http://dali.hfpthk.cn/Article/details/gt2optaisrh.html

memcpy(dst, src, n);
来源：http://dali.jinqigfzy.top/Article/details/gt2fsarhoxs.html

[S26] C：内存清零
来源：http://dali.pengpengdd.cyou/Article/details/gt2rhlaaspm.html

memset(a, 0, sizeof a);
来源：http://dali.jinqigufen.top/Article/details/gt2kmirojfg.html

[S27] C：定义常量
来源：http://dali.xylfe.cn/Article/details/gt2cpsfacvd.html

const double PI = 3.14159;
来源：http://dali.pycfn.com/Article/details/gt2gflqeics.html

[S28] C：静态变量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jzfmhlva.html

static int counter = 0;
来源：http://dali.wangshuangyany.cn/Article/details/gt2yjmohruy.html

[S29] C：变参函数
来源：http://dali.shzxlz.cn/Article/details/gt2idjbynrh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhixingplan.top/Article/details/gt2jmvvypyt.html

[S30] C：头文件保护
来源：http://dali.guowangkeji.top/Article/details/gt2iqwczxwm.html

#ifndef X_H
来源：http://dali.cucudq.cn/Article/details/gt2cunfewkk.html

#define X_H
来源：http://dali.xinyue.icu/Article/details/gt2ghjvdeus.html

#endif
来源：http://dali.zhengqikj.top/Article/details/gt2nqazokuj.html

[S31] C++：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gt2dkkbeprd.html

#include <iostream>
来源：http://dali.wangshuangyany.cn/Article/details/gt2jtheoolu.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yanxiufei.cn/Article/details/gt2xaxtcmce.html

[S32] C++：字符串
来源：http://dali.shzxlz.cn/Article/details/gt2frjnewkh.html

std::string s = "hi";  s += "!";
来源：http://dali.cqqwz.cn/Article/details/gt2hdrqdhjm.html

[S33] C++：vector 增删
来源：http://dali.c1oappe.top/Article/details/gt2xqoqvwok.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cdnleiting.top/Article/details/gt2qyoyizgk.html

[S34] C++：遍历 vector
来源：http://dali.jqgufenzy.top/Article/details/gt2gplthots.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jianghu66.top/Article/details/gt2cadeduxx.html

[S35] C++：map
来源：http://dali.chenjidiqi.icu/Article/details/gt2nadaqyyd.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.bjfxy.top/Article/details/gt2tnaedkdg.html

[S36] C++：unordered_map
来源：http://dali.xinyue.icu/Article/details/gt2mimzeboo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jianghu66.top/Article/details/gt2fknsmrrt.html

[S37] C++：set
来源：http://dali.chenjidiqi.icu/Article/details/gt2unsufdbk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yj202588.top/Article/details/gt2yvztpchx.html

[S38] C++：排序
来源：http://dali.fengsongda.top/Article/details/gt2svoqjfry.html

std::sort(v.begin(), v.end());
来源：http://dali.cqqwz.cn/Article/details/gt2sxmjxmkn.html

[S39] C++：自定义比较器排序
来源：http://dali.bjfxy.top/Article/details/gt2uopaodsy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.aizwys.cn/Article/details/gt2akebkovf.html

[S40] C++：查找元素
来源：http://dali.jinqigufen.top/Article/details/gt2zrxfpcdd.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xuetiantiany.cn/Article/details/gt2hbgdgato.html

[S41] C++：类与构造函数
来源：http://dali.chenzaomai.com/Article/details/gt2qtymcgnb.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jiagoushi.top/Article/details/gt2qkosimnf.html

[S42] C++：继承与虚函数
来源：http://dali.ehwqpu.com/Article/details/gt2ncjrftil.html

class B : public Base { public: void f() override {} };
来源：http://dali.chenzaomai.com/Article/details/gt2xesnsqgm.html

[S43] C++：智能指针
来源：http://dali.tianlin.xyz/Article/details/gt2fjotczxw.html

auto p = std::make_unique<int>(5);
来源：http://dali.nanxuanxn.top/Article/details/gt2rxrmadnc.html

[S44] C++：引用传参
来源：http://dali.snrcjt.cn/Article/details/gt2zbxbkufm.html

void inc(int &x) { ++x; }
来源：http://dali.cdnleiting.top/Article/details/gt2evqddwwm.html

[S45] C++：lambda
来源：http://dali.gaohongyu789.top/Article/details/gt2azoefgjd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.wangdashe.top/Article/details/gt2mugaoolg.html

[S46] C++：函数模板
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qsxdykbq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenlongwang.top/Article/details/gt2ulnyoije.html

[S47] C++：结构化绑定遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yxmiamzf.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.iojbl.cn/Article/details/gt2elnpeyua.html

[S48] C++：逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gt2rvbwppqr.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.9152youxi.cn/Article/details/gt2xyjlogps.html

while (std::getline(in, line)) { }
来源：http://dali.gzhubu.top/Article/details/gt2vwimfrtq.html

[S49] C++：写文件
来源：http://dali.daria6918.cn/Article/details/gt2bzacuihb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhengqikj.top/Article/details/gt2bwpngqoi.html

[S50] C++：格式化数字
来源：http://dali.yj20258888.top/Article/details/gt2cjhceluk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ydzc1.top/Article/details/gt2gblqwxna.html

[S51] C++：显式类型转换
来源：http://dali.yj202588.top/Article/details/gt2vwahsuyr.html

static_cast<double>(a) / b
来源：http://dali.wangdashe.top/Article/details/gt2tianofut.html

[S52] C++：const 与 noexcept
来源：http://dali.zhoulong.xyz/Article/details/gt2ldwamwvr.html

int size() const noexcept { return n_; }
来源：http://dali.9152youxi.cn/Article/details/gt2twrqcrfc.html

[S53] C++：移动语义
来源：http://dali.hammf.cn/Article/details/gt2rtmcijkn.html

std::vector<int> w = std::move(v);
来源：http://dali.yongpay.top/Article/details/gt2cybmukjv.html

[S54] C++：异常处理
来源：http://dali.daria6918.cn/Article/details/gt2bgutiwzw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.dianchejie.cn/Article/details/gt2huylhhrh.html

[S55] C++：结构化绑定
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zvegwrip.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cheryme.top/Article/details/gt2xfursydc.html

[S56] C++：optional
来源：http://dali.andypj.xyz/Article/details/gt2xuehoyjf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.redwolf501.top/Article/details/gt2vjcdxicd.html

[S57] C++：编译期常量
来源：http://dali.nanxinkj.top/Article/details/gt2whnzwbai.html

constexpr int N = 10;
来源：http://dali.nanxuanxn.top/Article/details/gt2ezvtzvyc.html

[S58] C++：命名空间
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2glurheex.html

namespace ns { int f() { return 1; } }
来源：http://dali.pengpengdd.cyou/Article/details/gt2pnqsiauj.html

[S59] C++：静态断言
来源：http://dali.zdqjudy.top/Article/details/gt2drgzemaj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.0kj1m.cn/Article/details/gt2zflvqpyg.html

[S60] C++：遍历并删除元素
来源：http://dali.jqgufenzy.top/Article/details/gt2qzygpcjy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.dashuyun.cn/Article/details/gt2ajtrrqld.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2jdmdxxhy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yuxming.cn/Article/details/gt2ydclczrv.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gt2xofodzjg.html

[T01] Kotlin：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gt2xhxkknrl.html

println("Hello")
来源：http://dali.cqqwz.cn/Article/details/gt2hrfjzznl.html

[T02] Kotlin：变量
来源：http://dali.jlsjyb.cn/Article/details/gt2ewmlweje.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jinqigufen.top/Article/details/gt2awztwfdt.html

[T03] Kotlin：字符串模板
来源：http://dali.haohaochexian.top/Article/details/gt2vmuqurob.html

"值: $b"
来源：http://dali.aibaodan.cn/Article/details/gt2hzkrmifr.html

[T04] Kotlin：空安全
来源：http://dali.pycfn.com/Article/details/gt2nqcndcpu.html

val n: String? = null;  n?.length
来源：http://dali.hongshengwenyu.top/Article/details/gt2kdfqcsgk.html

[T05] Kotlin：when 表达式
来源：http://dali.tanke756.top/Article/details/gt2gqfbzsia.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.pengpengdd.cyou/Article/details/gt2bwkjguty.html

[T06] Kotlin：集合映射
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ywazbvty.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vehbftiv.html

[T07] Kotlin：集合过滤
来源：http://dali.nanxinkj.top/Article/details/gt2lppestta.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cheryme.top/Article/details/gt2gurvbszw.html

[T08] Kotlin：数据类
来源：http://dali.andypj.xyz/Article/details/gt2kgzmsdse.html

data class User(val name: String, val age: Int)
来源：http://dali.jlsjyb.cn/Article/details/gt2nigpahuq.html

[T09] Kotlin：扩展函数
来源：http://dali.bjfxy.top/Article/details/gt2mktfvxkh.html

fun String.exclaim() = this + "!"
来源：http://dali.sxryk.cn/Article/details/gt2ujypsilj.html

[T10] Kotlin：默认参数
来源：http://dali.fengsongda.top/Article/details/gt2drhdtqml.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhiwuduotai.top/Article/details/gt2xqkghwhz.html

[T11] Kotlin：协程
来源：http://dali.xuanzx.com/Article/details/gt2znrlciwi.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhixingplan.top/Article/details/gt2qbbeqohp.html

[T12] Kotlin：解构声明
来源：http://dali.sxryk.cn/Article/details/gt2uwegzzak.html

val (a, b) = Pair(1, 2)
来源：http://dali.shanyushiyangtech.top/Article/details/gt2deglgqzr.html

[T13] Kotlin：只读 Map
来源：http://dali.yanxiufei.cn/Article/details/gt2efqwuzaq.html

val m = mapOf("a" to 1)
来源：http://dali.jyoumei.cn/Article/details/gt2fayvrqfm.html

[T14] Kotlin：循环
来源：http://dali.cheryme.top/Article/details/gt2fsicvlfj.html

for (i in 1..10) println(i)
来源：http://dali.kuanghao11.cn/Article/details/gt2kxhatpwq.html

[T15] Kotlin：接口
来源：http://dali.tian-w.cn/Article/details/gt2mlphgutx.html

interface Shape { fun area(): Double }
来源：http://dali.chenjidiqi.icu/Article/details/gt2rkogosxf.html

[T16] Swift：Hello World
来源：http://dali.yj20258888.top/Article/details/gt2trmmbcee.html

print("Hello")
来源：http://dali.ehwqpu.com/Article/details/gt2dwnrsblw.html

[T17] Swift：变量与常量
来源：http://dali.ivvv.top/Article/details/gt2wtnlcser.html

var a = 1;  let b = 2
来源：http://dali.yj202588.top/Article/details/gt2bprdlbnv.html

[T18] Swift：字符串插值
来源：http://dali.9152youxi.cn/Article/details/gt2esqknlsf.html

"值: \(b)"
来源：http://dali.0kj1m.cn/Article/details/gt2ozazmckp.html

[T19] Swift：可选绑定
来源：http://dali.meibo888.top/Article/details/gt2dbotjill.html

if let n = opt { print(n) }
来源：http://dali.feifeiyinyue.top/Article/details/gt2yfpuclbl.html

[T20] Swift：数组操作
来源：http://dali.yonumen.top/Article/details/gt2hvbkltwc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.kuanghao11.cn/Article/details/gt2fikygmce.html

[T21] Swift：遍历
来源：http://dali.yj20258888.top/Article/details/gt2dlohxfrp.html

for x in a { print(x) }
来源：http://dali.chenlongwang.top/Article/details/gt2tazcxkdz.html

[T22] Swift：字典
来源：http://dali.tanke756.top/Article/details/gt2pbvtsjbu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jqgufenzy.top/Article/details/gt2tohubayq.html

[T23] Swift：函数
来源：http://dali.chenjidiqi.icu/Article/details/gt2tepnvabc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zycfv.cn/Article/details/gt2shfwdnec.html

[T24] Swift：闭包
来源：http://dali.bjfxy.top/Article/details/gt2kveltuji.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zdqjudy.top/Article/details/gt2hyhpbmea.html

[T25] Swift：结构体
来源：http://dali.tian-w.cn/Article/details/gt2drnshiik.html

struct P { var x: Int }
来源：http://dali.chenlongwang.top/Article/details/gt2hzzfhlho.html

[T26] Swift：类与重写
来源：http://dali.0kj1m.cn/Article/details/gt2zuxixdos.html

class A: Base { override func f() {} }
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fzfnidte.html

[T27] Swift：错误处理
来源：http://dali.smart0.xyz/Article/details/gt2cdksbdgw.html

do { try f() } catch { print(error) }
来源：http://dali.wangshuangyany.cn/Article/details/gt2ietzwycv.html

[T28] Swift：枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qcnqufed.html

enum Color { case red, green }
来源：http://dali.hysaishi.cn/Article/details/gt2annqcnbx.html

[T29] Swift：guard 提前返回
来源：http://dali.nanxinkj.top/Article/details/gt2dhmofrge.html

guard let x = opt else { return }
来源：http://dali.nanxinkj.top/Article/details/gt2igdoawms.html

[T30] Swift：协议
来源：http://dali.hysaishi.cn/Article/details/gt2nxlohrtg.html

protocol Shape { func area() -> Double }
来源：http://dali.snrcjt.cn/Article/details/gt2vioyxxio.html

[T31] Lua：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gt2atygxpie.html

print("Hello")
来源：http://dali.pycfn.com/Article/details/gt2btutyhrk.html

[T32] Lua：局部变量
来源：http://dali.jqgufenzy.top/Article/details/gt2uvpdcyri.html

local a = 1
来源：http://dali.gogol.net.cn/Article/details/gt2adyihfvi.html

[T33] Lua：表（数组）
来源：http://dali.zhixingplan.top/Article/details/gt2wtabcbsi.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.chenzaomai.com/Article/details/gt2msulujje.html

[T34] Lua：遍历表
来源：http://dali.jyoumei.cn/Article/details/gt2hpevjagb.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jyoumei.cn/Article/details/gt2vavzewjh.html

[T35] Lua：字典表
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tskkhtyw.html

local d = { a = 1 };  d.b = 2
来源：http://dali.birdmap.top/Article/details/gt2plfrmpii.html

[T36] Lua：函数
来源：http://dali.gogol.net.cn/Article/details/gt2iztshmol.html

function add(a, b) return a + b end
来源：http://dali.ppjwa.cn/Article/details/gt2xuaojcry.html

[T37] Lua：字符串拼接
来源：http://dali.cqqwz.cn/Article/details/gt2tzxbzamh.html

"a" .. "b"
来源：http://dali.zhoulong.xyz/Article/details/gt2onotrgam.html

[T38] Lua：条件
来源：http://dali.vqdsnc.cn/Article/details/gt2radcriui.html

if x > 0 then print("正") end
来源：http://dali.gotoacloud.top/Article/details/gt2nhukmhpt.html

[T39] Lua：模式匹配
来源：http://dali.yueranfly.top/Article/details/gt2hqjowpie.html

string.find(s, "%d+")
来源：http://dali.nwbrower.top/Article/details/gt2fbjopcmq.html

[T40] Lua：元表
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2niblpevq.html

setmetatable({}, { __index = base })
来源：http://dali.chenzaomai.com/Article/details/gt2crjcqprt.html

[T41] Perl：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gt2jtvbaaqf.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gt2tineqcgy.html

[T42] Perl：变量类型
来源：http://dali.bjfxy.top/Article/details/gt2mjmvdkfc.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ojwcbzkf.html

[T43] Perl：字符串插值
来源：http://dali.snrcjt.cn/Article/details/gt2hawjoulo.html

"值: $a"
来源：http://dali.zhiwuduotai.top/Article/details/gt2pfcfsiwq.html

[T44] Perl：条件
来源：http://dali.haohaochexian.top/Article/details/gt2qscivzhf.html

if ($a > 0) { print "正"; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2punwwugy.html

[T45] Perl：数组遍历
来源：http://dali.jqgufenzy.top/Article/details/gt2beviuywh.html

for my $x (@arr) { print $x; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tjwhkuvx.html

[T46] Perl：哈希操作
来源：http://dali.tian-w.cn/Article/details/gt2rxflfkpz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yj20258.top/Article/details/gt2kojpfowx.html


<!-- 参考信息 -->