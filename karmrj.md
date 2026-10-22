代发 wailian999

sed -i 's/foo/bar/g' a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtkmwxsywy.html

[R48] awk 取指定列
来源：http://dali.chenlongwang.top/Article/details/gtcdsjbviy.html

awk '{print $1, $3}' a.txt
来源：http://dali.fengsongda.top/Article/details/gtwctnarlt.html

[R49] awk 带条件
来源：http://dali.shangyingyoupin.top/Article/details/gtdguvtick.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.pengpengdd.cyou/Article/details/gtrnsmdbzv.html

[R50] awk 求和
来源：http://dali.xylfe.cn/Article/details/gtsyjnrsmz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.pycfn.com/Article/details/gtxfbvjaya.html

[R51] 排序去重取前几
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwoqekyix.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yvedp.cn/Article/details/gtefawityk.html

[R52] 统计行数
来源：http://dali.daria6918.cn/Article/details/gtjdlwphzq.html

wc -l a.txt
来源：http://dali.9152youxi.cn/Article/details/gtkqwmlqof.html

[R53] 查看文件头与实时尾
来源：http://dali.yanxiufei.cn/Article/details/gtllsovnly.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.svipenyu.cn/Article/details/gtyshphhoq.html

[R54] 比较两个文件
来源：http://dali.yangfankeji.com/Article/details/gtpkhrrxky.html

diff a.txt b.txt
来源：http://dali.nwbrower.top/Article/details/gtjzdomjbn.html

[R55] 压缩与解压
来源：http://dali.pengpengdd.cyou/Article/details/gttxatvdph.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.daxiang520.top/Article/details/gtiwzdhiux.html

[R56] 远程拷贝
来源：http://dali.dianchejie.cn/Article/details/gtbdjipvhv.html

scp file user@host:/path/
来源：http://dali.quarkkingdee.top/Article/details/gtpukzzdeo.html

[R57] 远程执行命令
来源：http://dali.mhx1999.top/Article/details/gtgctspmwo.html

ssh user@host 'uptime'
来源：http://dali.zhengqikj.top/Article/details/gtoicituvr.html

[R58] 下载文件
来源：http://dali.sxryk.cn/Article/details/gtjogoiniv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.wangshuangyany.cn/Article/details/gtvsuunhlm.html

[R59] 发 POST JSON
来源：http://dali.yongpay.top/Article/details/gteerkicqk.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinghuilouyu.cn/Article/details/gtyfjxtmpg.html

[R60] 只看 HTTP 状态码
来源：http://dali.cucudq.cn/Article/details/gttmbhsqln.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.aizwys.cn/Article/details/gthcdqusfc.html

[R61] 磁盘占用
来源：http://dali.cdnleiting.top/Article/details/gtdjdqagpd.html

df -h;  du -sh *
来源：http://dali.hnqzz.top/Article/details/gtjpgexrxl.html

[R62] 找最占空间的文件
来源：http://dali.birdmap.top/Article/details/gtojobibwa.html

du -ah . | sort -rh | head -10
来源：http://dali.xinyue.icu/Article/details/gtbqvxlvpp.html

[R63] 内存与进程
来源：http://dali.jinqigufen.top/Article/details/gtdgcvwzdp.html

free -h;  ps aux | grep nginx
来源：http://dali.birdmap.top/Article/details/gtyqvugnmv.html

[R64] 结束进程
来源：http://dali.xuetiantiany.cn/Article/details/gtoxstvoiw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.316326.xyz/Article/details/gtxtbyyijq.html

[R65] 查看端口占用
来源：http://dali.daria6918.cn/Article/details/gtyeoufxrm.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jyoumei.cn/Article/details/gttnalvusj.html

[R66] 定时任务
来源：http://dali.316326.xyz/Article/details/gtsxnkaxqw.html

crontab -e;  crontab -l
来源：http://dali.jianghu66.top/Article/details/gtgbigurrd.html

[R67] 生成随机十六进制串
来源：http://dali.tanke756.top/Article/details/gtmmtncjmo.html

openssl rand -hex 16
来源：http://dali.yj20258.top/Article/details/gttqdimohe.html

[R68] 计算文件校验值
来源：http://dali.fengsongda.top/Article/details/gtdymkszoq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.snrcjt.cn/Article/details/gttyybpkmy.html

[R69] 生成随机密码
来源：http://dali.cucudq.cn/Article/details/gtjcyborry.html

head -c 16 /dev/urandom | base64
来源：http://dali.ehwqpu.com/Article/details/gtkmqyexor.html

[R70] 时间戳与互转
来源：http://dali.birdmap.top/Article/details/gtuvxyutvy.html

date +%s;  date -d @1700000000
来源：http://dali.cheryme.top/Article/details/gtqklnhaun.html

[R71] 日期格式化
来源：http://dali.aizwys.cn/Article/details/gtbygarool.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhoulong.xyz/Article/details/gtrkarobzf.html

[R72] 等待端口就绪
来源：http://dali.cucudq.cn/Article/details/gtaficmriw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gzhubu.top/Article/details/gtooibvcbz.html

[R73] 分割大日志
来源：http://dali.hnqzz.top/Article/details/gtxngxhivn.html

split -l 1000 big.log part_
来源：http://dali.yueranfly.top/Article/details/gtluelpqug.html

[R74] 批量重命名
来源：http://dali.sysykeji.top/Article/details/gtcaayznbp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jqgufenzy.top/Article/details/gttrezzkoy.html

[R75] 导出环境变量
来源：http://dali.tianlin.xyz/Article/details/gtzivjzzkw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hfpthk.cn/Article/details/gttgkhnyew.html

[R76] 使用临时文件
来源：http://dali.aizwys.cn/Article/details/gtzhtksnpu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.dashuyun.cn/Article/details/gtlhsbbxzs.html

[R77] 读取用户输入
来源：http://dali.zdqjudy.top/Article/details/gtyyfckkgh.html

read -rp "请输入: " ans
来源：http://dali.redwolf501.top/Article/details/gtiexgvdka.html

[R78] 交互式菜单
来源：http://dali.fengsongda.top/Article/details/gthxotospi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.316326.xyz/Article/details/gtreupkeoy.html

[R79] 解析命令行选项
来源：http://dali.nwbrower.top/Article/details/gtlefgqeap.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcdlshcou.html

[R80] 查看脚本执行耗时
来源：http://dali.chenlongwang.top/Article/details/gtqolnnyqw.html

time ./run.sh
来源：http://dali.jqgfzy.top/Article/details/gtauprimzr.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtztuebigh.html

S. C / C++ 专题
来源：http://dali.hnxiangtu.top/Article/details/gtqcznhoxt.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtczkrnkqz.html

[S01] C：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtthasqrot.html

#include <stdio.h>
来源：http://dali.vqdsnc.cn/Article/details/gttgvzxpuc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.chenjidiqi.icu/Article/details/gtujwwfiyy.html

[S02] C：变量与格式化输出
来源：http://dali.sweek.top/Article/details/gtznppzblo.html

int a = 10; printf("%d\n", a);
来源：http://dali.daxiang520.top/Article/details/gtfbcfiino.html

[S03] C：读入整数
来源：http://dali.havefunace.top/Article/details/gtgmgsslbh.html

int x; scanf("%d", &x);
来源：http://dali.zhengqikj.top/Article/details/gthuuuwisj.html

[S04] C：字符串复制
来源：http://dali.aizwys.cn/Article/details/gtwwcmjzsc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yj202588.top/Article/details/gtinjlpxjw.html

[S05] C：字符串长度
来源：http://dali.snrcjt.cn/Article/details/gtlniwnjbs.html

strlen(s)
来源：http://dali.ydzc1.top/Article/details/gthckvagcc.html

[S06] C：字符串比较
来源：http://dali.iojbl.cn/Article/details/gtwwpjwgei.html

strcmp(a, b) == 0
来源：http://dali.ydzc1.top/Article/details/gtsmodtuut.html

[S07] C：数组遍历求和
来源：http://dali.jyoumei.cn/Article/details/gtfcsbdnfy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yanxiufei.cn/Article/details/gtuhdxzjhh.html

[S08] C：动态内存分配与释放
来源：http://dali.yongpay.top/Article/details/gtvvmhgypx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinqigufen.top/Article/details/gtfmvoduqw.html

[S09] C：结构体定义与初始化
来源：http://dali.yj20258.top/Article/details/gttzriitqr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.haohaochexian.top/Article/details/gtqkxxlrit.html

[S10] C：指针与解引用
来源：http://dali.sweek.top/Article/details/gtmwwshmpc.html

int *p = &a;  *p = 5;
来源：http://dali.xylfe.cn/Article/details/gtfjhvglnb.html

[S11] C：逐行读文件
来源：http://dali.jianghu66.top/Article/details/gtoongwlkq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.chenzaomai.com/Article/details/gthxpbueqk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yonumen.top/Article/details/gtxleusthe.html

fclose(f);
来源：http://dali.yueranfly.top/Article/details/gtpqjbecfm.html

[S12] C：写文件
来源：http://dali.vqdsnc.cn/Article/details/gtpjnjqhku.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.aibaodan.cn/Article/details/gtlanurrfg.html

[S13] C：宏定义
来源：http://dali.gotoacloud.top/Article/details/gtpyhllofa.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.dashuyun.cn/Article/details/gtijvnihja.html

[S14] C：枚举
来源：http://dali.hnxiangtu.top/Article/details/gtekcvnzkf.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yj202588.top/Article/details/gthpsglkvd.html

[S15] C：类型转换
来源：http://dali.jqgufenzy.top/Article/details/gtrlopvlpb.html

(double) a / b
来源：http://dali.jlsjyb.cn/Article/details/gtkwkvzoeg.html

[S16] C：位操作置位
来源：http://dali.bjfxy.top/Article/details/gtzryrmgnt.html

x |= (1 << 3);
来源：http://dali.sufxvd.cn/Article/details/gtggqcsjpk.html

[S17] C：安全拼接字符串
来源：http://dali.shuidangran.top/Article/details/gteorkvooz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.snrcjt.cn/Article/details/gttmlvrruo.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gtuprnuyuu.html

int main(int argc, char **argv)
来源：http://dali.chenjidiqi.icu/Article/details/gtbpkgsjki.html

[S19] C：快速排序
来源：http://dali.sweek.top/Article/details/gttdxdnnfa.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jqgufenzy.top/Article/details/gtckqapvyr.html

[S20] C：二分查找
来源：http://dali.sweek.top/Article/details/gtsxlrluza.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zycfv.cn/Article/details/gtmdnndjij.html

[S21] C：字符类别判断
来源：http://dali.gaohongyu789.top/Article/details/gtmgmvczoa.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.svipenyu.cn/Article/details/gtrqrtcqln.html

[S22] C：字符串转数字
来源：http://dali.shangyingyoupin.top/Article/details/gtcjbozrmh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.cheryme.top/Article/details/gtrslvjznv.html

[S23] C：随机数
来源：http://dali.xuanzx.com/Article/details/gtobhgktok.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.dianchejie.cn/Article/details/gtzomqvepg.html

[S24] C：获取本地时间
来源：http://dali.zhoulong.xyz/Article/details/gtivqhjoso.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zycfv.cn/Article/details/gtbicxfqkt.html

[S25] C：内存拷贝
来源：http://dali.nwbrower.top/Article/details/gtzodtmrdb.html

memcpy(dst, src, n);
来源：http://dali.cdnleiting.top/Article/details/gtfsrsqvoz.html

[S26] C：内存清零
来源：http://dali.yj20258.top/Article/details/gtauvamjau.html

memset(a, 0, sizeof a);
来源：http://dali.chenlongwang.top/Article/details/gtlqibgbmp.html

[S27] C：定义常量
来源：http://dali.hfpthk.cn/Article/details/gtrhcwkthi.html

const double PI = 3.14159;
来源：http://dali.ehwqpu.com/Article/details/gtfstusynp.html

[S28] C：静态变量
来源：http://dali.jqgfzy.top/Article/details/gtpzbtermc.html

static int counter = 0;
来源：http://dali.zhongyouzk.top/Article/details/gtncjqccfe.html

[S29] C：变参函数
来源：http://dali.yj20258888.top/Article/details/gtovvbddnh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.ppjwa.cn/Article/details/gtsbbdmqzo.html

[S30] C：头文件保护
来源：http://dali.zhengqikj.top/Article/details/gthlykaqdt.html

#ifndef X_H
来源：http://dali.ivvv.top/Article/details/gtsxtnrfme.html

#define X_H
来源：http://dali.guowangkeji.top/Article/details/gtppkfqtlj.html

#endif
来源：http://dali.dashuyun.cn/Article/details/gtaqlhyzrx.html

[S31] C++：Hello World
来源：http://dali.cdnleiting.top/Article/details/gtqsvyijeo.html

#include <iostream>
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrrxjsrdr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtntugigve.html

[S32] C++：字符串
来源：http://dali.chenlongwang.top/Article/details/gttpszfiqy.html

std::string s = "hi";  s += "!";
来源：http://dali.cqqwz.cn/Article/details/gteabakacy.html

[S33] C++：vector 增删
来源：http://dali.hywenlv.cn/Article/details/gtayxzwnhq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.9152youxi.cn/Article/details/gtqsyczxrn.html

[S34] C++：遍历 vector
来源：http://dali.hammf.cn/Article/details/gtjkmibgfr.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hysaishi.cn/Article/details/gtalvehjff.html

[S35] C++：map
来源：http://dali.cucudq.cn/Article/details/gtpqbivpno.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.smart0.xyz/Article/details/gturpgnvru.html

[S36] C++：unordered_map
来源：http://dali.jqgfzy.top/Article/details/gtudgwnhhc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtonjbnmbn.html

[S37] C++：set
来源：http://dali.gogol.net.cn/Article/details/gtnglqfolq.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhongyouzk.top/Article/details/gtflxekvwy.html

[S38] C++：排序
来源：http://dali.bjfxy.top/Article/details/gtbkhrouai.html

std::sort(v.begin(), v.end());
来源：http://dali.ivvv.top/Article/details/gtdiqxkzkh.html

[S39] C++：自定义比较器排序
来源：http://dali.daxiang520.top/Article/details/gtltpilbsz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jqgfzy.top/Article/details/gtggbtmfyx.html

[S40] C++：查找元素
来源：http://dali.shzxlz.cn/Article/details/gtucrkueic.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.vqdsnc.cn/Article/details/gtelgrdcsw.html

[S41] C++：类与构造函数
来源：http://dali.andypj.xyz/Article/details/gtoobljgqv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yueranfly.top/Article/details/gtogyefuuh.html

[S42] C++：继承与虚函数
来源：http://dali.cashguo.top/Article/details/gttmvvdncv.html

class B : public Base { public: void f() override {} };
来源：http://dali.nanxinkj.top/Article/details/gtgfedxyme.html

[S43] C++：智能指针
来源：http://dali.xuetiantiany.cn/Article/details/gthqetzdgn.html

auto p = std::make_unique<int>(5);
来源：http://dali.pengpengdd.cyou/Article/details/gtorkkgbjp.html

[S44] C++：引用传参
来源：http://dali.ivvv.top/Article/details/gtkmadnmgo.html

void inc(int &x) { ++x; }
来源：http://dali.havefunace.top/Article/details/gtexjuperf.html

[S45] C++：lambda
来源：http://dali.ydzc1.top/Article/details/gthqlikelv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.havefunace.top/Article/details/gtczzywvqa.html

[S46] C++：函数模板
来源：http://dali.cqqwz.cn/Article/details/gtuefhuitd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.haohaochexian.top/Article/details/gtzgzjjorb.html

[S47] C++：结构化绑定遍历
来源：http://dali.xylfe.cn/Article/details/gtgrncoakd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.gogol.net.cn/Article/details/gtxqijtotz.html

[S48] C++：逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnuphtxpj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.nanxinkj.top/Article/details/gtzwdeqadt.html

while (std::getline(in, line)) { }
来源：http://dali.sysykeji.top/Article/details/gtqujgqmur.html

[S49] C++：写文件
来源：http://dali.zdqjudy.top/Article/details/gtzbfaiwza.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jianghu66.top/Article/details/gtqihyndhd.html

[S50] C++：格式化数字
来源：http://dali.chenjidiqi.icu/Article/details/gtcvdchvwx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shangyingyoupin.top/Article/details/gtkvdlrcgg.html

[S51] C++：显式类型转换
来源：http://dali.hysaishi.cn/Article/details/gtvizhhvzt.html

static_cast<double>(a) / b
来源：http://dali.chenzaomai.com/Article/details/gtheankmgh.html

[S52] C++：const 与 noexcept
来源：http://dali.zhoulong.xyz/Article/details/gtamwrrcnx.html

int size() const noexcept { return n_; }
来源：http://dali.yangfankeji.com/Article/details/gtpqgjiarc.html

[S53] C++：移动语义
来源：http://dali.jinghuilouyu.cn/Article/details/gtpexqxaln.html

std::vector<int> w = std::move(v);
来源：http://dali.sweek.top/Article/details/gtiepeflfl.html

[S54] C++：异常处理
来源：http://dali.svipenyu.cn/Article/details/gtqlzalavt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yuxming.cn/Article/details/gtdjprrqeg.html

[S55] C++：结构化绑定
来源：http://dali.andypj.xyz/Article/details/gtzsxiphij.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ehwqpu.com/Article/details/gteuejxawm.html

[S56] C++：optional
来源：http://dali.ppjwa.cn/Article/details/gtzrxglynx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yj20258.top/Article/details/gtuvychlmy.html

[S57] C++：编译期常量
来源：http://dali.fzhhl.top/Article/details/gtultdbcgv.html

constexpr int N = 10;
来源：http://dali.316326.xyz/Article/details/gtqqhiitgc.html

[S58] C++：命名空间
来源：http://dali.0kj1m.cn/Article/details/gtinatmamb.html

namespace ns { int f() { return 1; } }
来源：http://dali.hammf.cn/Article/details/gtnjxjgbit.html

[S59] C++：静态断言
来源：http://dali.sweek.top/Article/details/gtkoqqisyr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.kuanghao11.cn/Article/details/gtwakuntfe.html

[S60] C++：遍历并删除元素
来源：http://dali.svipenyu.cn/Article/details/gtzvjmfoyu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhiwuduotai.top/Article/details/gtgrbdzhrf.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtrvwmkwsj.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xylfe.cn/Article/details/gtazvtuouj.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtnuzsqqqw.html

[T01] Kotlin：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtottbvgst.html

println("Hello")
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtktfqyfoc.html

[T02] Kotlin：变量
来源：http://dali.fzhhl.top/Article/details/gtdhcdschj.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.pycfn.com/Article/details/gtgpbpfaqu.html

[T03] Kotlin：字符串模板
来源：http://dali.zhaomingkeji.xyz/Article/details/gtarjyrzze.html

"值: $b"
来源：http://dali.cashguo.top/Article/details/gtyzukoekp.html

[T04] Kotlin：空安全
来源：http://dali.birdmap.top/Article/details/gtrmcfpoye.html

val n: String? = null;  n?.length
来源：http://dali.fzhhl.top/Article/details/gtmlbmtbdj.html

[T05] Kotlin：when 表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgfkgwyib.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jianghu66.top/Article/details/gtahfzroqh.html

[T06] Kotlin：集合映射
来源：http://dali.redwolf501.top/Article/details/gtunkuykps.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnhszxjzb.html

[T07] Kotlin：集合过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gtneqgjpkn.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hysaishi.cn/Article/details/gtgpvmalfc.html

[T08] Kotlin：数据类
来源：http://dali.c1oappe.top/Article/details/gtdhngbmwz.html

data class User(val name: String, val age: Int)
来源：http://dali.shangyingyoupin.top/Article/details/gtmrjysyvz.html

[T09] Kotlin：扩展函数
来源：http://dali.feifeiyinyue.top/Article/details/gtcnpxujxw.html

fun String.exclaim() = this + "!"
来源：http://dali.9152youxi.cn/Article/details/gtauaevixl.html

[T10] Kotlin：默认参数
来源：http://dali.yuanzhike.top/Article/details/gtwekkxbqp.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.mhx1999.top/Article/details/gtakmhxzkd.html

[T11] Kotlin：协程
来源：http://dali.pycfn.com/Article/details/gtnpewebaq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.hysaishi.cn/Article/details/gtjbaemqqq.html

[T12] Kotlin：解构声明
来源：http://dali.zhongyouzk.top/Article/details/gtmuzefmng.html

val (a, b) = Pair(1, 2)
来源：http://dali.zdqjudy.top/Article/details/gtmrfgudej.html

[T13] Kotlin：只读 Map
来源：http://dali.sxryk.cn/Article/details/gtlsyqsrhg.html

val m = mapOf("a" to 1)
来源：http://dali.zycfv.cn/Article/details/gtsqfvedto.html

[T14] Kotlin：循环
来源：http://dali.316326.xyz/Article/details/gtxytvwkiu.html

for (i in 1..10) println(i)
来源：http://dali.ppjwa.cn/Article/details/gttmohsaeq.html

[T15] Kotlin：接口
来源：http://dali.0kj1m.cn/Article/details/gtljgjjyeg.html

interface Shape { fun area(): Double }
来源：http://dali.andypj.xyz/Article/details/gtezmargqg.html

[T16] Swift：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gtsbqgchtv.html

print("Hello")
来源：http://dali.gotoacloud.top/Article/details/gtigusijdg.html

[T17] Swift：变量与常量
来源：http://dali.shzxlz.cn/Article/details/gtslnusihg.html

var a = 1;  let b = 2
来源：http://dali.gotoacloud.top/Article/details/gtswsclaoj.html

[T18] Swift：字符串插值
来源：http://dali.gzhubu.top/Article/details/gtlmzwvlso.html

"值: \(b)"
来源：http://dali.yangfankeji.com/Article/details/gtirvbgoow.html

[T19] Swift：可选绑定
来源：http://dali.meibo888.top/Article/details/gtskcxrkuu.html

if let n = opt { print(n) }
来源：http://dali.snrcjt.cn/Article/details/gtvuahlhkq.html

[T20] Swift：数组操作
来源：http://dali.hammf.cn/Article/details/gtepcxrlyx.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj202588.top/Article/details/gttzdiwzku.html

[T21] Swift：遍历
来源：http://dali.quarkkingdee.top/Article/details/gtgnhrqcgk.html

for x in a { print(x) }
来源：http://dali.vqdsnc.cn/Article/details/gtwxmequyl.html

[T22] Swift：字典
来源：http://dali.ehwqpu.com/Article/details/gtkkozjkzf.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.sweek.top/Article/details/gtjttsvelm.html

[T23] Swift：函数
来源：http://dali.hysaishi.cn/Article/details/gtmapnlixf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.redwolf501.top/Article/details/gtiwahbmga.html

[T24] Swift：闭包
来源：http://dali.jiagoushi.top/Article/details/gtenlzyorh.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.c1oappe.top/Article/details/gtshuamzvj.html

[T25] Swift：结构体
来源：http://dali.316326.xyz/Article/details/gteppmnahw.html

struct P { var x: Int }
来源：http://dali.yj20258888.top/Article/details/gtbfumeqqa.html

[T26] Swift：类与重写
来源：http://dali.dashuyun.cn/Article/details/gtobllxyby.html

class A: Base { override func f() {} }
来源：http://dali.zhiwuduotai.top/Article/details/gtsmgigvuq.html

[T27] Swift：错误处理
来源：http://dali.aibaodan.cn/Article/details/gtlzjqpleg.html

do { try f() } catch { print(error) }
来源：http://dali.nanxinkj.top/Article/details/gtisnkotuk.html

[T28] Swift：枚举
来源：http://dali.cdnleiting.top/Article/details/gtczrjwbls.html

enum Color { case red, green }
来源：http://dali.yj20258.top/Article/details/gtzzkuqrra.html

[T29] Swift：guard 提前返回
来源：http://dali.guannengcc.top/Article/details/gtqggxcfxb.html

guard let x = opt else { return }
来源：http://dali.yj20258888.top/Article/details/gtcpdroseo.html

[T30] Swift：协议
来源：http://dali.c1oappe.top/Article/details/gtpqiqpmnb.html

protocol Shape { func area() -> Double }
来源：http://dali.cheryme.top/Article/details/gtsazvamyx.html

[T31] Lua：Hello World
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtevqhbfcm.html

print("Hello")
来源：http://dali.aibaodan.cn/Article/details/gtrphcazpx.html

[T32] Lua：局部变量
来源：http://dali.yj20258.top/Article/details/gtqoxbywxx.html

local a = 1
来源：http://dali.mhx1999.top/Article/details/gtylnibsif.html

[T33] Lua：表（数组）
来源：http://dali.tanke756.top/Article/details/gtnjllcgaj.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.pengpengdd.cyou/Article/details/gtpuazxmfz.html

[T34] Lua：遍历表
来源：http://dali.ppjwa.cn/Article/details/gtvhgneepc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhijiandao.cn/Article/details/gtydthmhsh.html

[T35] Lua：字典表
来源：http://dali.bjfxy.top/Article/details/gtutljtvqo.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jqgfzy.top/Article/details/gtmzlfitfu.html

[T36] Lua：函数
来源：http://dali.redwolf501.top/Article/details/gtxyafbyqd.html

function add(a, b) return a + b end
来源：http://dali.cdnleiting.top/Article/details/gtkjmmerbz.html

[T37] Lua：字符串拼接
来源：http://dali.sysykeji.top/Article/details/gtgighljqx.html

"a" .. "b"
来源：http://dali.yj20258.top/Article/details/gtrhcfklda.html

[T38] Lua：条件
来源：http://dali.hongshengwenyu.top/Article/details/gtgsofwozy.html

if x > 0 then print("正") end
来源：http://dali.daxiang520.top/Article/details/gtbkssafva.html

[T39] Lua：模式匹配
来源：http://dali.ybcxt.top/Article/details/gtgjirngux.html

string.find(s, "%d+")
来源：http://dali.tanke756.top/Article/details/gtbpenbqqg.html

[T40] Lua：元表
来源：http://dali.xylfe.cn/Article/details/gtrdeviwgz.html

setmetatable({}, { __index = base })
来源：http://dali.zhongyouzk.top/Article/details/gtjohzrpoy.html

[T41] Perl：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtmvneqxdk.html

print "Hello\n";
来源：http://dali.pycfn.com/Article/details/gtitxrfdtf.html

[T42] Perl：变量类型
来源：http://dali.daria6918.cn/Article/details/gthuzrbgvs.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.gotoacloud.top/Article/details/gtfcrafugg.html

[T43] Perl：字符串插值
来源：http://dali.guannengcc.top/Article/details/gtrbwghtyh.html

"值: $a"
来源：http://dali.shangyingyoupin.top/Article/details/gtzzewqzfk.html

[T44] Perl：条件
来源：http://dali.yuxming.cn/Article/details/gtqjwwgtiy.html

if ($a > 0) { print "正"; }
来源：http://dali.pengpengdd.cyou/Article/details/gtfvbhzvwj.html

[T45] Perl：数组遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtrvoiwivf.html

for my $x (@arr) { print $x; }
来源：http://dali.0kj1m.cn/Article/details/gtxtnswokg.html

[T46] Perl：哈希操作
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteujplkgp.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.zhijiandao.cn/Article/details/gtenssojqd.html

[T47] Perl：正则捕获
来源：http://dali.mhx1999.top/Article/details/gtzmevngof.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yueranfly.top/Article/details/gtygmhwvpj.html

[T48] Perl：正则替换
来源：http://dali.zhengqikj.top/Article/details/gtdrhliuxt.html

$s =~ s/old/new/g;
来源：http://dali.jqgfzy.top/Article/details/gtmjaemakb.html

[T49] Perl：函数
来源：http://dali.shzxlz.cn/Article/details/gtmeyafunl.html

sub add { my ($a, $b) = @_; return $a + $b; }
来源：http://dali.nanxuanxn.top/Article/details/gtrkefdhcv.html

[T50] Perl：逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gtjamxyiez.html

open my $fh, "<", "a.txt" or die $!;
来源：http://dali.yuxming.cn/Article/details/gttphdtzij.html


<!-- 参考信息 -->