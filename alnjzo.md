代发 wailian999

find . -name "*.tmp" -delete
来源：http://dali.ivvv.top/Article/details/gtwjsrvrjz.html

[R46] 递归替换文件内容
来源：http://dali.yuxming.cn/Article/details/gtndccsuqe.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhengqikj.top/Article/details/gtgrrnurpb.html

[R47] sed 单行替换
来源：http://dali.fengsongda.top/Article/details/gtjgqzgdwg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.vqdsnc.cn/Article/details/gtxqejermw.html

[R48] awk 取指定列
来源：http://dali.9152youxi.cn/Article/details/gtjdlyfuhz.html

awk '{print $1, $3}' a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtzszvbuou.html

[R49] awk 带条件
来源：http://dali.xuetiantiany.cn/Article/details/gtvezldvmj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.nanxinkj.top/Article/details/gtyevjxwdt.html

[R50] awk 求和
来源：http://dali.snrcjt.cn/Article/details/gtzlwzbbmb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.chenzaomai.com/Article/details/gtdagrisqp.html

[R51] 排序去重取前几
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdwksardo.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.svipenyu.cn/Article/details/gtmbmifstz.html

[R52] 统计行数
来源：http://dali.yj202588.top/Article/details/gtvjgnriiu.html

wc -l a.txt
来源：http://dali.iojbl.cn/Article/details/gtlbfwbdbb.html

[R53] 查看文件头与实时尾
来源：http://dali.yanxiufei.cn/Article/details/gtcgvprrrg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.iojbl.cn/Article/details/gtpmrrspmy.html

[R54] 比较两个文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdostgvmo.html

diff a.txt b.txt
来源：http://dali.meibo888.top/Article/details/gtgbmndwwe.html

[R55] 压缩与解压
来源：http://dali.nwbrower.top/Article/details/gtoqqcypxz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jlsjyb.cn/Article/details/gtrkmdfgzw.html

[R56] 远程拷贝
来源：http://dali.0kj1m.cn/Article/details/gteuqqneks.html

scp file user@host:/path/
来源：http://dali.xuetiantiany.cn/Article/details/gtmgpqonoe.html

[R57] 远程执行命令
来源：http://dali.hysaishi.cn/Article/details/gtbdwnmkvu.html

ssh user@host 'uptime'
来源：http://dali.mhx1999.top/Article/details/gtalrqidzz.html

[R58] 下载文件
来源：http://dali.snrcjt.cn/Article/details/gtzvztqsqm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shanyushiyangtech.top/Article/details/gtnmjjupnf.html

[R59] 发 POST JSON
来源：http://dali.sweek.top/Article/details/gtykinumsv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gaohongyu789.top/Article/details/gtqvopzqwa.html

[R60] 只看 HTTP 状态码
来源：http://dali.sxryk.cn/Article/details/gtmssqaeem.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.feifeiyinyue.top/Article/details/gtgbztnupp.html

[R61] 磁盘占用
来源：http://dali.ivvv.top/Article/details/gtupigcmfy.html

df -h;  du -sh *
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxabbqehz.html

[R62] 找最占空间的文件
来源：http://dali.hfpthk.cn/Article/details/gtjkagiumj.html

du -ah . | sort -rh | head -10
来源：http://dali.jinqigufen.top/Article/details/gtysnzklnj.html

[R63] 内存与进程
来源：http://dali.guowangkeji.top/Article/details/gtwentlybw.html

free -h;  ps aux | grep nginx
来源：http://dali.nwbrower.top/Article/details/gtmideuoqn.html

[R64] 结束进程
来源：http://dali.sufxvd.cn/Article/details/gtjmuiklrp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jlsjyb.cn/Article/details/gtgtmwlolu.html

[R65] 查看端口占用
来源：http://dali.ivvv.top/Article/details/gtfzushfbi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ivvv.top/Article/details/gttjzakluv.html

[R66] 定时任务
来源：http://dali.yvedp.cn/Article/details/gtfxagslmb.html

crontab -e;  crontab -l
来源：http://dali.cdnleiting.top/Article/details/gtvjilqtvh.html

[R67] 生成随机十六进制串
来源：http://dali.ehwqpu.com/Article/details/gtmogtypqt.html

openssl rand -hex 16
来源：http://dali.yj202588.top/Article/details/gtxzmfhuvq.html

[R68] 计算文件校验值
来源：http://dali.yueranfly.top/Article/details/gtsbzhgbwc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.fengsongda.top/Article/details/gtmqlzezkp.html

[R69] 生成随机密码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmkgmqyby.html

head -c 16 /dev/urandom | base64
来源：http://dali.vqdsnc.cn/Article/details/gtstgabzfx.html

[R70] 时间戳与互转
来源：http://dali.gogol.net.cn/Article/details/gtjbfdbeno.html

date +%s;  date -d @1700000000
来源：http://dali.zdqjudy.top/Article/details/gtcjmmhnry.html

[R71] 日期格式化
来源：http://dali.nwbrower.top/Article/details/gtwpheaddk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jlsjyb.cn/Article/details/gtwaajktck.html

[R72] 等待端口就绪
来源：http://dali.0kj1m.cn/Article/details/gtutikuefe.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jqgfzy.top/Article/details/gtzdoveimn.html

[R73] 分割大日志
来源：http://dali.vqdsnc.cn/Article/details/gtziudxmsy.html

split -l 1000 big.log part_
来源：http://dali.jlsjyb.cn/Article/details/gtglpntkjw.html

[R74] 批量重命名
来源：http://dali.aizwys.cn/Article/details/gtkwgvfftk.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sysykeji.top/Article/details/gtxcqoiyyc.html

[R75] 导出环境变量
来源：http://dali.daxiang520.top/Article/details/gtcrhefywx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jqgufenzy.top/Article/details/gtasmetytq.html

[R76] 使用临时文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gthclgzpce.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgfzy.top/Article/details/gtqlkuxxnw.html

[R77] 读取用户输入
来源：http://dali.mhx1999.top/Article/details/gtpquxcaby.html

read -rp "请输入: " ans
来源：http://dali.pycfn.com/Article/details/gtutgddmhy.html

[R78] 交互式菜单
来源：http://dali.pengpengdd.cyou/Article/details/gtybvbfbjx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hfpthk.cn/Article/details/gteyhbnqzx.html

[R79] 解析命令行选项
来源：http://dali.c1oappe.top/Article/details/gtopdwjffv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ppjwa.cn/Article/details/gtqlniswmf.html

[R80] 查看脚本执行耗时
来源：http://dali.sysykeji.top/Article/details/gtmokgpypf.html

time ./run.sh
来源：http://dali.zhoulong.xyz/Article/details/gtwtzezrcv.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtmbvvmncf.html

S. C / C++ 专题
来源：http://dali.bjfxy.top/Article/details/gtjzgzjkmt.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtvkyxjytc.html

[S01] C：Hello World
来源：http://dali.yonumen.top/Article/details/gtrtkfffpd.html

#include <stdio.h>
来源：http://dali.iojbl.cn/Article/details/gtyixfiqay.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xuanzx.com/Article/details/gtnbrzuzhl.html

[S02] C：变量与格式化输出
来源：http://dali.wangdashe.top/Article/details/gtgnplijzo.html

int a = 10; printf("%d\n", a);
来源：http://dali.316326.xyz/Article/details/gtmekbtmis.html

[S03] C：读入整数
来源：http://dali.sufxvd.cn/Article/details/gtzlirvfws.html

int x; scanf("%d", &x);
来源：http://dali.jqgufenzy.top/Article/details/gtatgeazbx.html

[S04] C：字符串复制
来源：http://dali.nwbrower.top/Article/details/gtvjwasgdb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jianghu66.top/Article/details/gtnnphhnkr.html

[S05] C：字符串长度
来源：http://dali.jyoumei.cn/Article/details/gttsfsfkls.html

strlen(s)
来源：http://dali.xziqi.cn/Article/details/gtofizbnce.html

[S06] C：字符串比较
来源：http://dali.hongshengwenyu.top/Article/details/gtlkxbozou.html

strcmp(a, b) == 0
来源：http://dali.snrcjt.cn/Article/details/gtdxlftdtn.html

[S07] C：数组遍历求和
来源：http://dali.jlsjyb.cn/Article/details/gtdnmiykih.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yangfankeji.com/Article/details/gtwnurpkzy.html

[S08] C：动态内存分配与释放
来源：http://dali.zhongyouzk.top/Article/details/gtbxgnqeqj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.feifeiyinyue.top/Article/details/gtgxcfanic.html

[S09] C：结构体定义与初始化
来源：http://dali.wangshuangyany.cn/Article/details/gtddhgiguk.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkwwedljc.html

[S10] C：指针与解引用
来源：http://dali.tian-w.cn/Article/details/gtqrfyzowm.html

int *p = &a;  *p = 5;
来源：http://dali.andypj.xyz/Article/details/gtsymtjsue.html

[S11] C：逐行读文件
来源：http://dali.yuanzhike.top/Article/details/gthwijsbxu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.redwolf501.top/Article/details/gtltadmcym.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.smart0.xyz/Article/details/gtnddrczyw.html

fclose(f);
来源：http://dali.jinqigfzy.top/Article/details/gtvoduvrlk.html

[S12] C：写文件
来源：http://dali.yueranfly.top/Article/details/gtvfoskwij.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jianghu66.top/Article/details/gtbuangykc.html

[S13] C：宏定义
来源：http://dali.cheryme.top/Article/details/gtwlpizfpt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.guowangkeji.top/Article/details/gtdtnyhevk.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gtylpqkhmx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cqqwz.cn/Article/details/gtamrzihvv.html

[S15] C：类型转换
来源：http://dali.xinyue.icu/Article/details/gtxzpvaxgk.html

(double) a / b
来源：http://dali.jinqigfzy.top/Article/details/gtsfoeentd.html

[S16] C：位操作置位
来源：http://dali.ydzc1.top/Article/details/gtflhwkttx.html

x |= (1 << 3);
来源：http://dali.jqgfzy.top/Article/details/gthuzpkzqd.html

[S17] C：安全拼接字符串
来源：http://dali.zhongyouzk.top/Article/details/gtfanganhq.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.chenlongwang.top/Article/details/gtfnezqlsg.html

[S18] C：命令行参数
来源：http://dali.bjfxy.top/Article/details/gtjicoaysu.html

int main(int argc, char **argv)
来源：http://dali.hnxiangtu.top/Article/details/gtgwntwbcw.html

[S19] C：快速排序
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtreiyfbtt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gtayqadquh.html

[S20] C：二分查找
来源：http://dali.jyoumei.cn/Article/details/gtwkqbjdvg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.chenzaomai.com/Article/details/gtdhtlflwa.html

[S21] C：字符类别判断
来源：http://dali.gzhubu.top/Article/details/gtucuuwwqj.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jiagoushi.top/Article/details/gtzjjdsguy.html

[S22] C：字符串转数字
来源：http://dali.smart0.xyz/Article/details/gtckzpabml.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hysaishi.cn/Article/details/gtkjnwtech.html

[S23] C：随机数
来源：http://dali.chenjidiqi.icu/Article/details/gtmuoujjbp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hywenlv.cn/Article/details/gtyhsaurul.html

[S24] C：获取本地时间
来源：http://dali.chenlongwang.top/Article/details/gtmgumkcdc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yj202588.top/Article/details/gtcwppmvlm.html

[S25] C：内存拷贝
来源：http://dali.chenjidiqi.icu/Article/details/gtuziudzfa.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gtwjhozltl.html

[S26] C：内存清零
来源：http://dali.jqgfzy.top/Article/details/gtufwutuon.html

memset(a, 0, sizeof a);
来源：http://dali.guannengcc.top/Article/details/gtbmgrdkby.html

[S27] C：定义常量
来源：http://dali.gogol.net.cn/Article/details/gtgkdwpdyj.html

const double PI = 3.14159;
来源：http://dali.cashguo.top/Article/details/gtgamsbpyn.html

[S28] C：静态变量
来源：http://dali.9152youxi.cn/Article/details/gtgyidiznl.html

static int counter = 0;
来源：http://dali.yvedp.cn/Article/details/gtzgdxxlnf.html

[S29] C：变参函数
来源：http://dali.ybcxt.top/Article/details/gtcnxbqbeg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.nanxuanxn.top/Article/details/gtnohyjduk.html

[S30] C：头文件保护
来源：http://dali.wangdashe.top/Article/details/gtuqezmidl.html

#ifndef X_H
来源：http://dali.pengpengdd.cyou/Article/details/gtaveabugd.html

#define X_H
来源：http://dali.tianlin.xyz/Article/details/gtgjhqamnc.html

#endif
来源：http://dali.wangshuangyany.cn/Article/details/gtguqfvvgz.html

[S31] C++：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzffzkilz.html

#include <iostream>
来源：http://dali.pycfn.com/Article/details/gtvrxwcggk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ydzc1.top/Article/details/gtkfcxfagl.html

[S32] C++：字符串
来源：http://dali.xylfe.cn/Article/details/gtdzawgizl.html

std::string s = "hi";  s += "!";
来源：http://dali.daxiang520.top/Article/details/gtnoanbzvz.html

[S33] C++：vector 增删
来源：http://dali.jyoumei.cn/Article/details/gtedxemvhb.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.fzhhl.top/Article/details/gtbnlmwcjt.html

[S34] C++：遍历 vector
来源：http://dali.cashguo.top/Article/details/gtkygkmlij.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtslgadxdi.html

[S35] C++：map
来源：http://dali.aizwys.cn/Article/details/gtqwrnmnsp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.smart0.xyz/Article/details/gtttpmrrct.html

[S36] C++：unordered_map
来源：http://dali.zhongyouzk.top/Article/details/gtdkhklvih.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.mhx1999.top/Article/details/gthnxettcf.html

[S37] C++：set
来源：http://dali.birdmap.top/Article/details/gtsyesgvfh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.svipenyu.cn/Article/details/gtdsksxiyo.html

[S38] C++：排序
来源：http://dali.sxryk.cn/Article/details/gtewalfgwx.html

std::sort(v.begin(), v.end());
来源：http://dali.cucudq.cn/Article/details/gtqhzndhfm.html

[S39] C++：自定义比较器排序
来源：http://dali.ivvv.top/Article/details/gtlenqxzyq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.guowangkeji.top/Article/details/gtpnbdifjy.html

[S40] C++：查找元素
来源：http://dali.shanyushiyangtech.top/Article/details/gtochplbpx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.dianchejie.cn/Article/details/gtcokrykij.html

[S41] C++：类与构造函数
来源：http://dali.cucudq.cn/Article/details/gtswzahspc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.dashuyun.cn/Article/details/gtcfkwsvll.html

[S42] C++：继承与虚函数
来源：http://dali.9152youxi.cn/Article/details/gtxhxgcmut.html

class B : public Base { public: void f() override {} };
来源：http://dali.shangyingyoupin.top/Article/details/gtjglsferz.html

[S43] C++：智能指针
来源：http://dali.hfpthk.cn/Article/details/gttdwxacqa.html

auto p = std::make_unique<int>(5);
来源：http://dali.mhx1999.top/Article/details/gtpldeqlif.html

[S44] C++：引用传参
来源：http://dali.tianlin.xyz/Article/details/gtphcyoybx.html

void inc(int &x) { ++x; }
来源：http://dali.kuanghao11.cn/Article/details/gtcjfpnwxn.html

[S45] C++：lambda
来源：http://dali.yueranfly.top/Article/details/gtwdsvzxut.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hongshengwenyu.top/Article/details/gtlurquvsj.html

[S46] C++：函数模板
来源：http://dali.ybcxt.top/Article/details/gtrtweyzph.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.0kj1m.cn/Article/details/gtbzfxvwsp.html

[S47] C++：结构化绑定遍历
来源：http://dali.svipenyu.cn/Article/details/gtuykeylvh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.meibo888.top/Article/details/gtgslkzbao.html

[S48] C++：逐行读文件
来源：http://dali.yongpay.top/Article/details/gtcgffjysu.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jianghu66.top/Article/details/gtytduefwa.html

while (std::getline(in, line)) { }
来源：http://dali.shangyingyoupin.top/Article/details/gtbmnwbnab.html

[S49] C++：写文件
来源：http://dali.chenlongwang.top/Article/details/gttzosvnal.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.316326.xyz/Article/details/gtaskzdvly.html

[S50] C++：格式化数字
来源：http://dali.zhengqikj.top/Article/details/gtzcixscet.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.xinyue.icu/Article/details/gtleahgwdj.html

[S51] C++：显式类型转换
来源：http://dali.redwolf501.top/Article/details/gtxgovggib.html

static_cast<double>(a) / b
来源：http://dali.quarkkingdee.top/Article/details/gtwmhhmwlk.html

[S52] C++：const 与 noexcept
来源：http://dali.xuetiantiany.cn/Article/details/gtoxqbfdcw.html

int size() const noexcept { return n_; }
来源：http://dali.sxryk.cn/Article/details/gtmbsqxjfg.html

[S53] C++：移动语义
来源：http://dali.jinghuilouyu.cn/Article/details/gtsmyvwiml.html

std::vector<int> w = std::move(v);
来源：http://dali.bjfxy.top/Article/details/gtizemsemb.html

[S54] C++：异常处理
来源：http://dali.jianghu66.top/Article/details/gtpwtkzevp.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.andypj.xyz/Article/details/gtevwmdtct.html

[S55] C++：结构化绑定
来源：http://dali.sufxvd.cn/Article/details/gtxaltpaig.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hnxiangtu.top/Article/details/gtvgurefop.html

[S56] C++：optional
来源：http://dali.jinghuilouyu.cn/Article/details/gtapfyvhbm.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ehwqpu.com/Article/details/gtrjanyguc.html

[S57] C++：编译期常量
来源：http://dali.aibaodan.cn/Article/details/gthyhrecbz.html

constexpr int N = 10;
来源：http://dali.nanxinkj.top/Article/details/gtrblpwstz.html

[S58] C++：命名空间
来源：http://dali.yongpay.top/Article/details/gtokskokcl.html

namespace ns { int f() { return 1; } }
来源：http://dali.sufxvd.cn/Article/details/gtwaiukalr.html

[S59] C++：静态断言
来源：http://dali.fengsongda.top/Article/details/gtqhxiruyw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.birdmap.top/Article/details/gthlwrsroo.html

[S60] C++：遍历并删除元素
来源：http://dali.hfpthk.cn/Article/details/gtyfmlabhz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jiagoushi.top/Article/details/gtbkwbsljh.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtmwtzonqc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.yuanzhike.top/Article/details/gtyspojmtl.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtmsdvezpn.html

[T01] Kotlin：Hello World
来源：http://dali.yongpay.top/Article/details/gtdllgniru.html

println("Hello")
来源：http://dali.jinqigufen.top/Article/details/gtnhvrezjq.html

[T02] Kotlin：变量
来源：http://dali.andypj.xyz/Article/details/gtlmmnkmun.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shanyushiyangtech.top/Article/details/gtggyqmonw.html

[T03] Kotlin：字符串模板
来源：http://dali.nwbrower.top/Article/details/gtzizlmecl.html

"值: $b"
来源：http://dali.yonumen.top/Article/details/gtyeymwnky.html

[T04] Kotlin：空安全
来源：http://dali.zdqjudy.top/Article/details/gtiquhgegt.html

val n: String? = null;  n?.length
来源：http://dali.hywenlv.cn/Article/details/gtihegrcsp.html

[T05] Kotlin：when 表达式
来源：http://dali.shzxlz.cn/Article/details/gtdtobajjr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinghuilouyu.cn/Article/details/gtlwhrrfqq.html

[T06] Kotlin：集合映射
来源：http://dali.yangfankeji.com/Article/details/gtarzhupcc.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shangyingyoupin.top/Article/details/gtkonpxppg.html

[T07] Kotlin：集合过滤
来源：http://dali.yueranfly.top/Article/details/gtgayuiskj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hammf.cn/Article/details/gtkerpzefp.html

[T08] Kotlin：数据类
来源：http://dali.yvedp.cn/Article/details/gtfoiheqks.html

data class User(val name: String, val age: Int)
来源：http://dali.jlsjyb.cn/Article/details/gteqxwtisy.html

[T09] Kotlin：扩展函数
来源：http://dali.feifeiyinyue.top/Article/details/gtbvbdorqc.html

fun String.exclaim() = this + "!"
来源：http://dali.gaohongyu789.top/Article/details/gtdwhjdtvc.html

[T10] Kotlin：默认参数
来源：http://dali.shuidangran.top/Article/details/gtzvltvqvm.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shanyushiyangtech.top/Article/details/gtibewlhph.html

[T11] Kotlin：协程
来源：http://dali.hysaishi.cn/Article/details/gtndnatbuw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jinqigufen.top/Article/details/gtipopkrgs.html

[T12] Kotlin：解构声明
来源：http://dali.gzhubu.top/Article/details/gtftleykka.html

val (a, b) = Pair(1, 2)
来源：http://dali.jinqigfzy.top/Article/details/gtggrldily.html

[T13] Kotlin：只读 Map
来源：http://dali.yangfankeji.com/Article/details/gtavecvxni.html

val m = mapOf("a" to 1)
来源：http://dali.sufxvd.cn/Article/details/gtjrwdnxdo.html

[T14] Kotlin：循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsihjckkz.html

for (i in 1..10) println(i)
来源：http://dali.hongshengwenyu.top/Article/details/gtdwalmego.html

[T15] Kotlin：接口
来源：http://dali.meibo888.top/Article/details/gtbaydblkr.html

interface Shape { fun area(): Double }
来源：http://dali.yj202588.top/Article/details/gtxofodmvb.html

[T16] Swift：Hello World
来源：http://dali.iojbl.cn/Article/details/gtkbxoumcn.html

print("Hello")
来源：http://dali.9152youxi.cn/Article/details/gtczfsthfk.html

[T17] Swift：变量与常量
来源：http://dali.birdmap.top/Article/details/gtvvfgmwej.html

var a = 1;  let b = 2
来源：http://dali.feifeiyinyue.top/Article/details/gtyhszzxeq.html

[T18] Swift：字符串插值
来源：http://dali.jinqigfzy.top/Article/details/gtunodhybj.html

"值: \(b)"
来源：http://dali.zhiwuduotai.top/Article/details/gtqnszyuzl.html

[T19] Swift：可选绑定
来源：http://dali.zhengqikj.top/Article/details/gtyvzcgpqz.html

if let n = opt { print(n) }
来源：http://dali.wangshuangyany.cn/Article/details/gtymrqmhxo.html

[T20] Swift：数组操作
来源：http://dali.andypj.xyz/Article/details/gtcvkrvyac.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.9152youxi.cn/Article/details/gtnffrnzja.html

[T21] Swift：遍历
来源：http://dali.chenlongwang.top/Article/details/gtmuqwsboj.html

for x in a { print(x) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gttgytwrcz.html

[T22] Swift：字典
来源：http://dali.jinqigfzy.top/Article/details/gtobmvovdj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaxyzwkgb.html

[T23] Swift：函数
来源：http://dali.yueranfly.top/Article/details/gtimxqbony.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.bjfxy.top/Article/details/gtkpfszmrz.html

[T24] Swift：闭包
来源：http://dali.yueranfly.top/Article/details/gtqxovdhoy.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sufxvd.cn/Article/details/gtxpncxvvf.html

[T25] Swift：结构体
来源：http://dali.hywenlv.cn/Article/details/gtaofhjotq.html

struct P { var x: Int }
来源：http://dali.birdmap.top/Article/details/gtzxmuvfbb.html

[T26] Swift：类与重写
来源：http://dali.yueranfly.top/Article/details/gtaiqjsqnw.html

class A: Base { override func f() {} }
来源：http://dali.yangfankeji.com/Article/details/gtgvfhruuz.html

[T27] Swift：错误处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtipldohmb.html

do { try f() } catch { print(error) }
来源：http://dali.fengsongda.top/Article/details/gtbytpkhzz.html

[T28] Swift：枚举
来源：http://dali.birdmap.top/Article/details/gtwountxey.html

enum Color { case red, green }
来源：http://dali.xuanzx.com/Article/details/gtaamxhvfv.html

[T29] Swift：guard 提前返回
来源：http://dali.yuanzhike.top/Article/details/gtkxkxjnzi.html

guard let x = opt else { return }
来源：http://dali.quarkkingdee.top/Article/details/gtqlwwvnxl.html

[T30] Swift：协议
来源：http://dali.aizwys.cn/Article/details/gtlhtputql.html

protocol Shape { func area() -> Double }
来源：http://dali.pycfn.com/Article/details/gtblkhaawo.html

[T31] Lua：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gthkqoiozm.html

print("Hello")
来源：http://dali.jinyuanbaomall.cn/Article/details/gtakgztuah.html

[T32] Lua：局部变量
来源：http://dali.chenjidiqi.icu/Article/details/gthesktsfi.html

local a = 1
来源：http://dali.zhijiandao.cn/Article/details/gtfnkjdfmc.html

[T33] Lua：表（数组）
来源：http://dali.shangyingyoupin.top/Article/details/gtzairvpaw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjotkbfkj.html

[T34] Lua：遍历表
来源：http://dali.ivvv.top/Article/details/gtppkorbml.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.sysykeji.top/Article/details/gtrfttvlbv.html

[T35] Lua：字典表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwsssbegb.html

local d = { a = 1 };  d.b = 2
来源：http://dali.nanxuanxn.top/Article/details/gtqqjxvrak.html

[T36] Lua：函数
来源：http://dali.xuanzx.com/Article/details/gtpijzvujs.html

function add(a, b) return a + b end
来源：http://dali.redwolf501.top/Article/details/gtbmjolcat.html

[T37] Lua：字符串拼接
来源：http://dali.kuanghao11.cn/Article/details/gtvjugwbvx.html

"a" .. "b"
来源：http://dali.yonumen.top/Article/details/gtsijihumi.html

[T38] Lua：条件
来源：http://dali.gotoacloud.top/Article/details/gteztjuhyp.html

if x > 0 then print("正") end
来源：http://dali.tanke756.top/Article/details/gtwubqskid.html

[T39] Lua：模式匹配
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdmggxfsa.html

string.find(s, "%d+")
来源：http://dali.haohaochexian.top/Article/details/gtzqyiznol.html

[T40] Lua：元表
来源：http://dali.pycfn.com/Article/details/gtksiukqyv.html

setmetatable({}, { __index = base })
来源：http://dali.nwbrower.top/Article/details/gtotcgpnws.html

[T41] Perl：Hello World
来源：http://dali.316326.xyz/Article/details/gtxlowlhrw.html

print "Hello\n";
来源：http://dali.pengpengdd.cyou/Article/details/gtnlqqaaxl.html

[T42] Perl：变量类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkpvbwrrr.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yanxiufei.cn/Article/details/gtgykqulgy.html

[T43] Perl：字符串插值
来源：http://dali.ivvv.top/Article/details/gtskvbaokr.html

"值: $a"
来源：http://dali.wangdashe.top/Article/details/gtbiblpomy.html

[T44] Perl：条件
来源：http://dali.jyoumei.cn/Article/details/gtclbwzjht.html

if ($a > 0) { print "正"; }
来源：http://dali.jianghu66.top/Article/details/gturvfvrbb.html

[T45] Perl：数组遍历
来源：http://dali.yj202588.top/Article/details/gtigngcwok.html

for my $x (@arr) { print $x; }
来源：http://dali.yanxiufei.cn/Article/details/gtsjxmclvo.html

[T46] Perl：哈希操作
来源：http://dali.jqgufenzy.top/Article/details/gtectwxkbz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yj20258.top/Article/details/gtxduqzcfn.html

[T47] Perl：正则捕获
来源：http://dali.hywenlv.cn/Article/details/gteuubfjap.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.meibo888.top/Article/details/gtxddywzpk.html

[T48] Perl：正则替换
来源：http://dali.guowangkeji.top/Article/details/gtfeeeolhi.html

$s =~ s/old/new/g;
来源：http://dali.sxryk.cn/Article/details/gtgcbmysve.html


<!-- 参考信息 -->