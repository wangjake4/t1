代发 wailian999

find . -name "*.log" -type f
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmxpplqjs.html

[R44] 按修改时间查找
来源：http://dali.snrcjt.cn/Article/details/gtmibgphyv.html

find . -mtime -7 -type f
来源：http://dali.zhoulong.xyz/Article/details/gteldtuwqm.html

[R45] 批量删除
来源：http://dali.ehwqpu.com/Article/details/gtvmoibvlb.html

find . -name "*.tmp" -delete
来源：http://dali.316326.xyz/Article/details/gtywzqdelu.html

[R46] 递归替换文件内容
来源：http://dali.hfpthk.cn/Article/details/gtrpidlqru.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cdnleiting.top/Article/details/gtxpebbbfe.html

[R47] sed 单行替换
来源：http://dali.zdqjudy.top/Article/details/gtkfmjxcdc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yj202588.top/Article/details/gttoghrdty.html

[R48] awk 取指定列
来源：http://dali.gzhubu.top/Article/details/gtulswmwip.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinqigfzy.top/Article/details/gturyppryi.html

[R49] awk 带条件
来源：http://dali.mhx1999.top/Article/details/gtqbriueya.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zycfv.cn/Article/details/gtebtcplfj.html

[R50] awk 求和
来源：http://dali.redwolf501.top/Article/details/gtoshkupgh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.tianlin.xyz/Article/details/gtccoovytk.html

[R51] 排序去重取前几
来源：http://dali.aizwys.cn/Article/details/gtazsflyjk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.haohaochexian.top/Article/details/gttwaqjixa.html

[R52] 统计行数
来源：http://dali.pycfn.com/Article/details/gtflfrwvgs.html

wc -l a.txt
来源：http://dali.fzhhl.top/Article/details/gtunlsyhka.html

[R53] 查看文件头与实时尾
来源：http://dali.nanxinkj.top/Article/details/gtnzgghghe.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhoulong.xyz/Article/details/gthiajcfmi.html

[R54] 比较两个文件
来源：http://dali.yvedp.cn/Article/details/gtuscqrkyh.html

diff a.txt b.txt
来源：http://dali.tianlin.xyz/Article/details/gttvcbnfwu.html

[R55] 压缩与解压
来源：http://dali.guannengcc.top/Article/details/gtswhokutb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinghuilouyu.cn/Article/details/gtqnsbkgpu.html

[R56] 远程拷贝
来源：http://dali.zhengqikj.top/Article/details/gtycpjeknk.html

scp file user@host:/path/
来源：http://dali.daria6918.cn/Article/details/gtrpfzfkla.html

[R57] 远程执行命令
来源：http://dali.yj202588.top/Article/details/gtangtoxgw.html

ssh user@host 'uptime'
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvxwephvl.html

[R58] 下载文件
来源：http://dali.ppjwa.cn/Article/details/gtdxhawxut.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sxryk.cn/Article/details/gtreuozamh.html

[R59] 发 POST JSON
来源：http://dali.shzxlz.cn/Article/details/gtyxycbedq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.9152youxi.cn/Article/details/gtltflgjso.html

[R60] 只看 HTTP 状态码
来源：http://dali.sxryk.cn/Article/details/gtjzclrmsi.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hammf.cn/Article/details/gtqsqpljpp.html

[R61] 磁盘占用
来源：http://dali.zhengqikj.top/Article/details/gtenjaxrnu.html

df -h;  du -sh *
来源：http://dali.yvedp.cn/Article/details/gtquyfmviz.html

[R62] 找最占空间的文件
来源：http://dali.cdnleiting.top/Article/details/gtvlvvrxzx.html

du -ah . | sort -rh | head -10
来源：http://dali.gotoacloud.top/Article/details/gtqiaoeshw.html

[R63] 内存与进程
来源：http://dali.iojbl.cn/Article/details/gtvtrihdmf.html

free -h;  ps aux | grep nginx
来源：http://dali.tianlin.xyz/Article/details/gtytqfakja.html

[R64] 结束进程
来源：http://dali.yuanzhike.top/Article/details/gtbrkduzms.html

kill -9 $(pgrep -f app.py)
来源：http://dali.tian-w.cn/Article/details/gtfuudagbc.html

[R65] 查看端口占用
来源：http://dali.nanxinkj.top/Article/details/gtyqphswix.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.tian-w.cn/Article/details/gtiginbota.html

[R66] 定时任务
来源：http://dali.yj20258888.top/Article/details/gtxjuoyrft.html

crontab -e;  crontab -l
来源：http://dali.zhongyouzk.top/Article/details/gttdbwczoj.html

[R67] 生成随机十六进制串
来源：http://dali.dashuyun.cn/Article/details/gtsewpgezl.html

openssl rand -hex 16
来源：http://dali.yvedp.cn/Article/details/gtkebmvpmh.html

[R68] 计算文件校验值
来源：http://dali.tian-w.cn/Article/details/gtglwusetv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hfpthk.cn/Article/details/gtrwrneaux.html

[R69] 生成随机密码
来源：http://dali.xuanzx.com/Article/details/gtbdtsamog.html

head -c 16 /dev/urandom | base64
来源：http://dali.tanke756.top/Article/details/gteabtlyhc.html

[R70] 时间戳与互转
来源：http://dali.sweek.top/Article/details/gtxmmmjdlt.html

date +%s;  date -d @1700000000
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyoaojamo.html

[R71] 日期格式化
来源：http://dali.havefunace.top/Article/details/gtwvmawgdl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.pengpengdd.cyou/Article/details/gttjnctowc.html

[R72] 等待端口就绪
来源：http://dali.wangshuangyany.cn/Article/details/gtbfgsfzsj.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shzxlz.cn/Article/details/gtvljkswlu.html

[R73] 分割大日志
来源：http://dali.cheryme.top/Article/details/gtalizmzel.html

split -l 1000 big.log part_
来源：http://dali.zhiwuduotai.top/Article/details/gtgedkgncy.html

[R74] 批量重命名
来源：http://dali.ivvv.top/Article/details/gtssvmejrq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.andypj.xyz/Article/details/gtmbmrrtgt.html

[R75] 导出环境变量
来源：http://dali.sufxvd.cn/Article/details/gtgzlvrvae.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sysykeji.top/Article/details/gtsvmrmgvh.html

[R76] 使用临时文件
来源：http://dali.yj20258.top/Article/details/gttaazwbdd.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gaohongyu789.top/Article/details/gtfnycolmk.html

[R77] 读取用户输入
来源：http://dali.sysykeji.top/Article/details/gtovfyfckh.html

read -rp "请输入: " ans
来源：http://dali.xuanzx.com/Article/details/gtvnrejxlc.html

[R78] 交互式菜单
来源：http://dali.jinqigfzy.top/Article/details/gtdgdunwpj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinghuilouyu.cn/Article/details/gturtwbatr.html

[R79] 解析命令行选项
来源：http://dali.dianchejie.cn/Article/details/gtioykoccy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ydzc1.top/Article/details/gtiysqtzus.html

[R80] 查看脚本执行耗时
来源：http://dali.zhoulong.xyz/Article/details/gtcswdwbiy.html

time ./run.sh
来源：http://dali.fengsongda.top/Article/details/gtchlqqcxa.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtwoytkmqw.html

S. C / C++ 专题
来源：http://dali.yanxiufei.cn/Article/details/gtlthxgxcq.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gttrekcmtm.html

[S01] C：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtzbeonlxz.html

#include <stdio.h>
来源：http://dali.xylfe.cn/Article/details/gtgnilonrb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.chenjidiqi.icu/Article/details/gtykhymlcw.html

[S02] C：变量与格式化输出
来源：http://dali.yj202588.top/Article/details/gtiqjyyhrc.html

int a = 10; printf("%d\n", a);
来源：http://dali.xylfe.cn/Article/details/gtsgfuwucp.html

[S03] C：读入整数
来源：http://dali.0kj1m.cn/Article/details/gtxmlyanzb.html

int x; scanf("%d", &x);
来源：http://dali.hysaishi.cn/Article/details/gtohjiamtl.html

[S04] C：字符串复制
来源：http://dali.feifeiyinyue.top/Article/details/gtgzumnllh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shuidangran.top/Article/details/gtqcvzupri.html

[S05] C：字符串长度
来源：http://dali.ivvv.top/Article/details/gtcdhgkgjv.html

strlen(s)
来源：http://dali.yonumen.top/Article/details/gtatnvukdg.html

[S06] C：字符串比较
来源：http://dali.jinghuilouyu.cn/Article/details/gtarpypzge.html

strcmp(a, b) == 0
来源：http://dali.ivvv.top/Article/details/gtbvabwlfb.html

[S07] C：数组遍历求和
来源：http://dali.c1oappe.top/Article/details/gtujkbrtar.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jianghu66.top/Article/details/gtpwvfrqmb.html

[S08] C：动态内存分配与释放
来源：http://dali.hongshengwenyu.top/Article/details/gticxsyyvt.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.pengpengdd.cyou/Article/details/gtnfxwpwls.html

[S09] C：结构体定义与初始化
来源：http://dali.pengpengdd.cyou/Article/details/gtpjjmmzpj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cashguo.top/Article/details/gtesbubweq.html

[S10] C：指针与解引用
来源：http://dali.ivvv.top/Article/details/gtezqyhwcr.html

int *p = &a;  *p = 5;
来源：http://dali.wangshuangyany.cn/Article/details/gtxoecmijf.html

[S11] C：逐行读文件
来源：http://dali.smart0.xyz/Article/details/gtjqkhnqbp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinghuilouyu.cn/Article/details/gtlpcbqgbi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cheryme.top/Article/details/gtwwbssqou.html

fclose(f);
来源：http://dali.fengsongda.top/Article/details/gtfhipielo.html

[S12] C：写文件
来源：http://dali.xziqi.cn/Article/details/gtlsiharjn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.ybcxt.top/Article/details/gtppgaxvyt.html

[S13] C：宏定义
来源：http://dali.shanyushiyangtech.top/Article/details/gtekbumjuc.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hammf.cn/Article/details/gtvmaimrgh.html

[S14] C：枚举
来源：http://dali.sufxvd.cn/Article/details/gtpxsajnvm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.0kj1m.cn/Article/details/gtbedibfvd.html

[S15] C：类型转换
来源：http://dali.sysykeji.top/Article/details/gtexqwzngc.html

(double) a / b
来源：http://dali.gzhubu.top/Article/details/gtpdykcjjf.html

[S16] C：位操作置位
来源：http://dali.zhongyouzk.top/Article/details/gtefvuxcft.html

x |= (1 << 3);
来源：http://dali.kuanghao11.cn/Article/details/gtcrqikwho.html

[S17] C：安全拼接字符串
来源：http://dali.feifeiyinyue.top/Article/details/gtclqjftjl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xinyue.icu/Article/details/gtutkvozoo.html

[S18] C：命令行参数
来源：http://dali.yangfankeji.com/Article/details/gtogqnrkua.html

int main(int argc, char **argv)
来源：http://dali.sweek.top/Article/details/gtubywujsi.html

[S19] C：快速排序
来源：http://dali.haohaochexian.top/Article/details/gtfxlujzox.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.daria6918.cn/Article/details/gteolxqjcw.html

[S20] C：二分查找
来源：http://dali.redwolf501.top/Article/details/gtqpkksick.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hfpthk.cn/Article/details/gtzxxlhesu.html

[S21] C：字符类别判断
来源：http://dali.hysaishi.cn/Article/details/gthkjzwzec.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.kuanghao11.cn/Article/details/gtsxkqqlxj.html

[S22] C：字符串转数字
来源：http://dali.cucudq.cn/Article/details/gteuhfvydy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.nanxuanxn.top/Article/details/gtxkrgbmpb.html

[S23] C：随机数
来源：http://dali.hnqzz.top/Article/details/gtfzbgpuxt.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.guowangkeji.top/Article/details/gtuxgmidro.html

[S24] C：获取本地时间
来源：http://dali.jqgufenzy.top/Article/details/gtkermbhiz.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xuetiantiany.cn/Article/details/gtbqayhiar.html

[S25] C：内存拷贝
来源：http://dali.chenzaomai.com/Article/details/gtoblrdgom.html

memcpy(dst, src, n);
来源：http://dali.jlsjyb.cn/Article/details/gtajverskx.html

[S26] C：内存清零
来源：http://dali.yongpay.top/Article/details/gtxtuhanmk.html

memset(a, 0, sizeof a);
来源：http://dali.jyoumei.cn/Article/details/gtphwfqroc.html

[S27] C：定义常量
来源：http://dali.shzxlz.cn/Article/details/gtglkwqoxr.html

const double PI = 3.14159;
来源：http://dali.iojbl.cn/Article/details/gtxjgelivm.html

[S28] C：静态变量
来源：http://dali.9152youxi.cn/Article/details/gtwnsckigv.html

static int counter = 0;
来源：http://dali.gogol.net.cn/Article/details/gtktileesc.html

[S29] C：变参函数
来源：http://dali.zhiwuduotai.top/Article/details/gtgyvoejqr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.svipenyu.cn/Article/details/gtdyguzmze.html

[S30] C：头文件保护
来源：http://dali.mhx1999.top/Article/details/gtufabgozk.html

#ifndef X_H
来源：http://dali.jianghu66.top/Article/details/gttasrbvkx.html

#define X_H
来源：http://dali.jlsjyb.cn/Article/details/gtqhllklqf.html

#endif
来源：http://dali.gotoacloud.top/Article/details/gtbwadpuoa.html

[S31] C++：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtnaupysxx.html

#include <iostream>
来源：http://dali.xuanzx.com/Article/details/gthfdeugqc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.dashuyun.cn/Article/details/gtlelbedcy.html

[S32] C++：字符串
来源：http://dali.jqgfzy.top/Article/details/gtqfbtcbep.html

std::string s = "hi";  s += "!";
来源：http://dali.jinghuilouyu.cn/Article/details/gtwimxusmw.html

[S33] C++：vector 增删
来源：http://dali.cdnleiting.top/Article/details/gtewwubsrr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.guannengcc.top/Article/details/gtivptzssy.html

[S34] C++：遍历 vector
来源：http://dali.shangyingyoupin.top/Article/details/gtvvjhulaa.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xuanzx.com/Article/details/gtuposqdyf.html

[S35] C++：map
来源：http://dali.meibo888.top/Article/details/gtkyqolaud.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ppjwa.cn/Article/details/gtqlixfoax.html

[S36] C++：unordered_map
来源：http://dali.ybcxt.top/Article/details/gtmuyahxls.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cashguo.top/Article/details/gtlsiwrgxk.html

[S37] C++：set
来源：http://dali.guowangkeji.top/Article/details/gtytzztgzb.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcnpwxjgi.html

[S38] C++：排序
来源：http://dali.aibaodan.cn/Article/details/gtystvdobu.html

std::sort(v.begin(), v.end());
来源：http://dali.xziqi.cn/Article/details/gtqcnkevxy.html

[S39] C++：自定义比较器排序
来源：http://dali.sxryk.cn/Article/details/gtrdjxxkxr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjgxfjroj.html

[S40] C++：查找元素
来源：http://dali.fengsongda.top/Article/details/gtkzvyzidi.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yj202588.top/Article/details/gtkihqohci.html

[S41] C++：类与构造函数
来源：http://dali.cqqwz.cn/Article/details/gtdevzicbn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cheryme.top/Article/details/gtmrbajtpp.html

[S42] C++：继承与虚函数
来源：http://dali.sufxvd.cn/Article/details/gtzzhlqqmh.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhoulong.xyz/Article/details/gtaabnyzbq.html

[S43] C++：智能指针
来源：http://dali.ppjwa.cn/Article/details/gtwtlxnwsb.html

auto p = std::make_unique<int>(5);
来源：http://dali.cashguo.top/Article/details/gtdxqmiisu.html

[S44] C++：引用传参
来源：http://dali.svipenyu.cn/Article/details/gtsaqjpwai.html

void inc(int &x) { ++x; }
来源：http://dali.dianchejie.cn/Article/details/gtsaezfboh.html

[S45] C++：lambda
来源：http://dali.gaohongyu789.top/Article/details/gtiotnsgvy.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhongyouzk.top/Article/details/gtgrvgrawu.html

[S46] C++：函数模板
来源：http://dali.gzhubu.top/Article/details/gtmgojbrut.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jlsjyb.cn/Article/details/gtpoaoxrym.html

[S47] C++：结构化绑定遍历
来源：http://dali.hammf.cn/Article/details/gtajyhmfii.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.bjfxy.top/Article/details/gtfubbjudr.html

[S48] C++：逐行读文件
来源：http://dali.ehwqpu.com/Article/details/gtkfnqlzfm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.guowangkeji.top/Article/details/gtcswvevjy.html

while (std::getline(in, line)) { }
来源：http://dali.redwolf501.top/Article/details/gtsrifabxi.html

[S49] C++：写文件
来源：http://dali.jqgufenzy.top/Article/details/gtzlxwwhpi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.daria6918.cn/Article/details/gtcuyrrfoo.html

[S50] C++：格式化数字
来源：http://dali.zhongyouzk.top/Article/details/gtucivgdoc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.316326.xyz/Article/details/gthnegpcur.html

[S51] C++：显式类型转换
来源：http://dali.hammf.cn/Article/details/gttwerhean.html

static_cast<double>(a) / b
来源：http://dali.guannengcc.top/Article/details/gtgyptroey.html

[S52] C++：const 与 noexcept
来源：http://dali.hfpthk.cn/Article/details/gthhncxego.html

int size() const noexcept { return n_; }
来源：http://dali.c1oappe.top/Article/details/gtqfmsypfs.html

[S53] C++：移动语义
来源：http://dali.haohaochexian.top/Article/details/gtjcbjtgah.html

std::vector<int> w = std::move(v);
来源：http://dali.cheryme.top/Article/details/gtzobrhlgt.html

[S54] C++：异常处理
来源：http://dali.yj20258.top/Article/details/gtguqdtybx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenlongwang.top/Article/details/gtvaeltira.html

[S55] C++：结构化绑定
来源：http://dali.chenjidiqi.icu/Article/details/gtltuzihkx.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hnqzz.top/Article/details/gtqvzezykt.html

[S56] C++：optional
来源：http://dali.ivvv.top/Article/details/gtnwbsocbg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.bjfxy.top/Article/details/gtjgjkpddg.html

[S57] C++：编译期常量
来源：http://dali.zhoulong.xyz/Article/details/gtvyeusegb.html

constexpr int N = 10;
来源：http://dali.cdnleiting.top/Article/details/gtbiyexsgh.html

[S58] C++：命名空间
来源：http://dali.tian-w.cn/Article/details/gtadldahoh.html

namespace ns { int f() { return 1; } }
来源：http://dali.chenlongwang.top/Article/details/gtozemkxag.html

[S59] C++：静态断言
来源：http://dali.hammf.cn/Article/details/gtzjhqonnm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.kuanghao11.cn/Article/details/gtqfmtbebt.html

[S60] C++：遍历并删除元素
来源：http://dali.mhx1999.top/Article/details/gtyxpzckli.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.gaohongyu789.top/Article/details/gthwsiuezp.html

================================================================================
来源：http://dali.quarkkingdee.top/Article/details/gtfefcmpji.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xuetiantiany.cn/Article/details/gtskzdqjed.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtvdvjialp.html

[T01] Kotlin：Hello World
来源：http://dali.sweek.top/Article/details/gtzsfijjgh.html

println("Hello")
来源：http://dali.zycfv.cn/Article/details/gtwxnumssm.html

[T02] Kotlin：变量
来源：http://dali.shuidangran.top/Article/details/gtavpiyztk.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jinqigufen.top/Article/details/gtdekiqsme.html

[T03] Kotlin：字符串模板
来源：http://dali.zycfv.cn/Article/details/gtvuypcewi.html

"值: $b"
来源：http://dali.hnxiangtu.top/Article/details/gtkzngther.html

[T04] Kotlin：空安全
来源：http://dali.0kj1m.cn/Article/details/gtcgzuaqzs.html

val n: String? = null;  n?.length
来源：http://dali.shanyushiyangtech.top/Article/details/gtyppghvvx.html

[T05] Kotlin：when 表达式
来源：http://dali.daria6918.cn/Article/details/gtgifvqxow.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.dianchejie.cn/Article/details/gthqxkfzug.html

[T06] Kotlin：集合映射
来源：http://dali.nanxinkj.top/Article/details/gtfjvlzgso.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yangfankeji.com/Article/details/gtcrvzfsjs.html

[T07] Kotlin：集合过滤
来源：http://dali.bjfxy.top/Article/details/gtkmwvyiwj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.chenzaomai.com/Article/details/gtugnchcep.html

[T08] Kotlin：数据类
来源：http://dali.fzhhl.top/Article/details/gtpniqbkyp.html

data class User(val name: String, val age: Int)
来源：http://dali.jlsjyb.cn/Article/details/gtdpclgirv.html

[T09] Kotlin：扩展函数
来源：http://dali.andypj.xyz/Article/details/gtkcdgwhgf.html

fun String.exclaim() = this + "!"
来源：http://dali.gaohongyu789.top/Article/details/gtuwymshxe.html

[T10] Kotlin：默认参数
来源：http://dali.wangshuangyany.cn/Article/details/gtfmllyuaf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhoulong.xyz/Article/details/gtrkxeckni.html

[T11] Kotlin：协程
来源：http://dali.xuetiantiany.cn/Article/details/gtxxhfzonl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xinyue.icu/Article/details/gtijomkxgx.html

[T12] Kotlin：解构声明
来源：http://dali.xinyue.icu/Article/details/gtqmzfosbc.html

val (a, b) = Pair(1, 2)
来源：http://dali.quarkkingdee.top/Article/details/gttdoypxwc.html

[T13] Kotlin：只读 Map
来源：http://dali.gzhubu.top/Article/details/gtdcwxbqev.html

val m = mapOf("a" to 1)
来源：http://dali.shzxlz.cn/Article/details/gtrirmpmdw.html

[T14] Kotlin：循环
来源：http://dali.haohaochexian.top/Article/details/gtsvidimwg.html

for (i in 1..10) println(i)
来源：http://dali.gotoacloud.top/Article/details/gtacfupydo.html

[T15] Kotlin：接口
来源：http://dali.yj202588.top/Article/details/gtpsezsmhd.html

interface Shape { fun area(): Double }
来源：http://dali.jqgfzy.top/Article/details/gtolvvnnqo.html

[T16] Swift：Hello World
来源：http://dali.hysaishi.cn/Article/details/gtcegdxpvx.html

print("Hello")
来源：http://dali.hysaishi.cn/Article/details/gthjjfbkdl.html

[T17] Swift：变量与常量
来源：http://dali.xuanzx.com/Article/details/gtopkajbqq.html

var a = 1;  let b = 2
来源：http://dali.xuanzx.com/Article/details/gtycwywcqe.html

[T18] Swift：字符串插值
来源：http://dali.wangshuangyany.cn/Article/details/gtqqzdozdd.html

"值: \(b)"
来源：http://dali.svipenyu.cn/Article/details/gtkmjibocz.html

[T19] Swift：可选绑定
来源：http://dali.0kj1m.cn/Article/details/gtvkgevipb.html

if let n = opt { print(n) }
来源：http://dali.jiagoushi.top/Article/details/gtynokpdvt.html

[T20] Swift：数组操作
来源：http://dali.hammf.cn/Article/details/gtjtlhkknl.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj20258888.top/Article/details/gthztktcxd.html

[T21] Swift：遍历
来源：http://dali.jinqigufen.top/Article/details/gtpmwvfewi.html

for x in a { print(x) }
来源：http://dali.c1oappe.top/Article/details/gtwbguyind.html

[T22] Swift：字典
来源：http://dali.nanxinkj.top/Article/details/gtzdqdoimu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yongpay.top/Article/details/gtrceunjij.html

[T23] Swift：函数
来源：http://dali.zhengqikj.top/Article/details/gtrrtbstbf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zdqjudy.top/Article/details/gtdlmsdddk.html

[T24] Swift：闭包
来源：http://dali.zhiwuduotai.top/Article/details/gtwyywbmoo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.gotoacloud.top/Article/details/gthbaniupb.html

[T25] Swift：结构体
来源：http://dali.cucudq.cn/Article/details/gtxisfjepp.html

struct P { var x: Int }
来源：http://dali.xuanzx.com/Article/details/gthfjawewq.html

[T26] Swift：类与重写
来源：http://dali.sysykeji.top/Article/details/gtptpzazuj.html

class A: Base { override func f() {} }
来源：http://dali.andypj.xyz/Article/details/gtqbuxfnuf.html

[T27] Swift：错误处理
来源：http://dali.zhoulong.xyz/Article/details/gtjsutlnhu.html

do { try f() } catch { print(error) }
来源：http://dali.wangdashe.top/Article/details/gtesgzzsor.html

[T28] Swift：枚举
来源：http://dali.yj20258.top/Article/details/gtwjwqcucj.html

enum Color { case red, green }
来源：http://dali.chenlongwang.top/Article/details/gtncwnsvaw.html

[T29] Swift：guard 提前返回
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbzztlefx.html

guard let x = opt else { return }
来源：http://dali.vqdsnc.cn/Article/details/gtkpahjbcw.html

[T30] Swift：协议
来源：http://dali.kuanghao11.cn/Article/details/gtqhqgpquy.html

protocol Shape { func area() -> Double }
来源：http://dali.jianghu66.top/Article/details/gtbyglxpqc.html

[T31] Lua：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtkymrcnda.html

print("Hello")
来源：http://dali.quarkkingdee.top/Article/details/gtopnmuaxv.html

[T32] Lua：局部变量
来源：http://dali.iojbl.cn/Article/details/gtyxqmofue.html

local a = 1
来源：http://dali.xuanzx.com/Article/details/gttgiynelh.html

[T33] Lua：表（数组）
来源：http://dali.wangshuangyany.cn/Article/details/gteeqbiaph.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.chenzaomai.com/Article/details/gtqnmyzezw.html

[T34] Lua：遍历表
来源：http://dali.chenlongwang.top/Article/details/gthyfnwouo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hnxiangtu.top/Article/details/gttbjwodjo.html

[T35] Lua：字典表
来源：http://dali.meibo888.top/Article/details/gtchgxebpe.html

local d = { a = 1 };  d.b = 2
来源：http://dali.dashuyun.cn/Article/details/gtsjsimtxr.html

[T36] Lua：函数
来源：http://dali.jinqigufen.top/Article/details/gtessjnhnn.html

function add(a, b) return a + b end
来源：http://dali.gaohongyu789.top/Article/details/gtadybltdw.html

[T37] Lua：字符串拼接
来源：http://dali.svipenyu.cn/Article/details/gtysgfqsss.html

"a" .. "b"
来源：http://dali.c1oappe.top/Article/details/gtwsdfkonv.html

[T38] Lua：条件
来源：http://dali.hfpthk.cn/Article/details/gtujifjrhn.html

if x > 0 then print("正") end
来源：http://dali.fengsongda.top/Article/details/gtooslnuiv.html

[T39] Lua：模式匹配
来源：http://dali.yueranfly.top/Article/details/gtxbjlftmb.html

string.find(s, "%d+")
来源：http://dali.guannengcc.top/Article/details/gtlvbgssnd.html

[T40] Lua：元表
来源：http://dali.gotoacloud.top/Article/details/gtkgpudsty.html

setmetatable({}, { __index = base })
来源：http://dali.zhongyouzk.top/Article/details/gtylyazqvl.html

[T41] Perl：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtnzzjtrxr.html

print "Hello\n";
来源：http://dali.zhongyouzk.top/Article/details/gtxignbbyw.html

[T42] Perl：变量类型
来源：http://dali.yvedp.cn/Article/details/gtxwzwzeub.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.316326.xyz/Article/details/gtktlvfphm.html

[T43] Perl：字符串插值
来源：http://dali.dianchejie.cn/Article/details/gturleihbr.html

"值: $a"
来源：http://dali.gzhubu.top/Article/details/gttzphbjpc.html

[T44] Perl：条件
来源：http://dali.yj20258.top/Article/details/gtaesjqwud.html

if ($a > 0) { print "正"; }
来源：http://dali.hywenlv.cn/Article/details/gtlznktoai.html

[T45] Perl：数组遍历
来源：http://dali.hysaishi.cn/Article/details/gtlmutghwa.html

for my $x (@arr) { print $x; }
来源：http://dali.haohaochexian.top/Article/details/gtozfrpnqu.html

[T46] Perl：哈希操作
来源：http://dali.dashuyun.cn/Article/details/gtbpuekhpi.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.pycfn.com/Article/details/gttibnxtvc.html


<!-- 参考信息 -->