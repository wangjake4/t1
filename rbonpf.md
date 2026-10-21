代发 wailian999

cmd >/dev/null 2>&1
来源：http://dali.daria6918.cn/Article/details/gtbfpeotou.html

[R42] 输入重定向
来源：http://dali.yvedp.cn/Article/details/gtegcaqklu.html

wc -l < a.txt
来源：http://dali.daria6918.cn/Article/details/gtulxtzylg.html

[R43] 按名字查找文件
来源：http://dali.c1oappe.top/Article/details/gtmhxaemvy.html

find . -name "*.log" -type f
来源：http://dali.chenzaomai.com/Article/details/gtlubyjlof.html

[R44] 按修改时间查找
来源：http://dali.redwolf501.top/Article/details/gtujgkyuzd.html

find . -mtime -7 -type f
来源：http://dali.tian-w.cn/Article/details/gtpfjordna.html

[R45] 批量删除
来源：http://dali.yvedp.cn/Article/details/gtqyjcguoa.html

find . -name "*.tmp" -delete
来源：http://dali.chenlongwang.top/Article/details/gtbnmfyqqk.html

[R46] 递归替换文件内容
来源：http://dali.fzhhl.top/Article/details/gtqlmjhvie.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jyoumei.cn/Article/details/gtdldhiynq.html

[R47] sed 单行替换
来源：http://dali.zhoulong.xyz/Article/details/gtutnbtklh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yuanzhike.top/Article/details/gtbabjzzay.html

[R48] awk 取指定列
来源：http://dali.cheryme.top/Article/details/gtuqbdijkw.html

awk '{print $1, $3}' a.txt
来源：http://dali.redwolf501.top/Article/details/gtclzzjrps.html

[R49] awk 带条件
来源：http://dali.daria6918.cn/Article/details/gtjaxcsxpm.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shzxlz.cn/Article/details/gtaywdgsxr.html

[R50] awk 求和
来源：http://dali.hnqzz.top/Article/details/gtaqxbgjhk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtjncgjeif.html

[R51] 排序去重取前几
来源：http://dali.guannengcc.top/Article/details/gtsvaxdowk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.chenjidiqi.icu/Article/details/gtjaiashst.html

[R52] 统计行数
来源：http://dali.hysaishi.cn/Article/details/gtmucwaehi.html

wc -l a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtajpgqfbs.html

[R53] 查看文件头与实时尾
来源：http://dali.quarkkingdee.top/Article/details/gtazsyhqht.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yangfankeji.com/Article/details/gttlnhwkvp.html

[R54] 比较两个文件
来源：http://dali.yueranfly.top/Article/details/gtlsroprip.html

diff a.txt b.txt
来源：http://dali.dashuyun.cn/Article/details/gtrsyzapdg.html

[R55] 压缩与解压
来源：http://dali.cheryme.top/Article/details/gtizgocmvt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shanyushiyangtech.top/Article/details/gtniaqiruf.html

[R56] 远程拷贝
来源：http://dali.cucudq.cn/Article/details/gtfcviengb.html

scp file user@host:/path/
来源：http://dali.fzhhl.top/Article/details/gtfoscihrr.html

[R57] 远程执行命令
来源：http://dali.0kj1m.cn/Article/details/gtljwfhcxk.html

ssh user@host 'uptime'
来源：http://dali.tian-w.cn/Article/details/gtozbetbvw.html

[R58] 下载文件
来源：http://dali.xylfe.cn/Article/details/gtmrqwwsyd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cdnleiting.top/Article/details/gtsalndqof.html

[R59] 发 POST JSON
来源：http://dali.nanxuanxn.top/Article/details/gtswxjlokq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.kuanghao11.cn/Article/details/gtdxjiiydp.html

[R60] 只看 HTTP 状态码
来源：http://dali.wangshuangyany.cn/Article/details/gtbmrtueth.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gaohongyu789.top/Article/details/gttyeuvfxo.html

[R61] 磁盘占用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtikrmyiyj.html

df -h;  du -sh *
来源：http://dali.mhx1999.top/Article/details/gthyaeqkkq.html

[R62] 找最占空间的文件
来源：http://dali.xuanzx.com/Article/details/gtaehlmuoa.html

du -ah . | sort -rh | head -10
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqkbuinfq.html

[R63] 内存与进程
来源：http://dali.haohaochexian.top/Article/details/gthcenjtwj.html

free -h;  ps aux | grep nginx
来源：http://dali.hammf.cn/Article/details/gtuehlutny.html

[R64] 结束进程
来源：http://dali.xziqi.cn/Article/details/gtdiwcissh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhengqikj.top/Article/details/gtbzcyxpzq.html

[R65] 查看端口占用
来源：http://dali.xylfe.cn/Article/details/gtgcvonxcz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.tianlin.xyz/Article/details/gtbxcwsoky.html

[R66] 定时任务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbupyeili.html

crontab -e;  crontab -l
来源：http://dali.c1oappe.top/Article/details/gtklwkxofx.html

[R67] 生成随机十六进制串
来源：http://dali.meibo888.top/Article/details/gtbjitapld.html

openssl rand -hex 16
来源：http://dali.tian-w.cn/Article/details/gtshvwfckw.html

[R68] 计算文件校验值
来源：http://dali.havefunace.top/Article/details/gtduycsrzj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yj20258888.top/Article/details/gtkmlstkfi.html

[R69] 生成随机密码
来源：http://dali.yj20258888.top/Article/details/gtetdnqbay.html

head -c 16 /dev/urandom | base64
来源：http://dali.tanke756.top/Article/details/gtgwwrbxuv.html

[R70] 时间戳与互转
来源：http://dali.quarkkingdee.top/Article/details/gtjwlitbna.html

date +%s;  date -d @1700000000
来源：http://dali.wangdashe.top/Article/details/gtkhuhisxx.html

[R71] 日期格式化
来源：http://dali.yvedp.cn/Article/details/gtgmqfqrri.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xziqi.cn/Article/details/gtoqjaudkg.html

[R72] 等待端口就绪
来源：http://dali.cheryme.top/Article/details/gtnyfagsft.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.vqdsnc.cn/Article/details/gtmlslcyiq.html

[R73] 分割大日志
来源：http://dali.ydzc1.top/Article/details/gtnyozvtbs.html

split -l 1000 big.log part_
来源：http://dali.0kj1m.cn/Article/details/gtovoazgwr.html

[R74] 批量重命名
来源：http://dali.zhiwuduotai.top/Article/details/gtgstnnhkn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shuidangran.top/Article/details/gtqewvdmly.html

[R75] 导出环境变量
来源：http://dali.chenlongwang.top/Article/details/gttdrdaiim.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zycfv.cn/Article/details/gtmcrfpmho.html

[R76] 使用临时文件
来源：http://dali.cashguo.top/Article/details/gtlublvehx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgufenzy.top/Article/details/gtnebsjasj.html

[R77] 读取用户输入
来源：http://dali.hongshengwenyu.top/Article/details/gteezaeedt.html

read -rp "请输入: " ans
来源：http://dali.xziqi.cn/Article/details/gtfvkjsdti.html

[R78] 交互式菜单
来源：http://dali.jqgfzy.top/Article/details/gtopdabuet.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.feifeiyinyue.top/Article/details/gttdzrirys.html

[R79] 解析命令行选项
来源：http://dali.chenjidiqi.icu/Article/details/gtokacxpmr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.daxiang520.top/Article/details/gttnnilxkh.html

[R80] 查看脚本执行耗时
来源：http://dali.tanke756.top/Article/details/gtjovahybo.html

time ./run.sh
来源：http://dali.ivvv.top/Article/details/gtsimagaln.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gttovgywsv.html

S. C / C++ 专题
来源：http://dali.xinyue.icu/Article/details/gtdzjfpcoe.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtuscnehmb.html

[S01] C：Hello World
来源：http://dali.hysaishi.cn/Article/details/gtcbsdardi.html

#include <stdio.h>
来源：http://dali.zycfv.cn/Article/details/gtsnfxanmv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gaohongyu789.top/Article/details/gthpxosaer.html

[S02] C：变量与格式化输出
来源：http://dali.hongshengwenyu.top/Article/details/gtjitzgmjt.html

int a = 10; printf("%d\n", a);
来源：http://dali.dashuyun.cn/Article/details/gthgrrnazp.html

[S03] C：读入整数
来源：http://dali.nanxuanxn.top/Article/details/gtoiynnmtw.html

int x; scanf("%d", &x);
来源：http://dali.ydzc1.top/Article/details/gtuvtztpeu.html

[S04] C：字符串复制
来源：http://dali.yuxming.cn/Article/details/gtzcjcoszw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.dashuyun.cn/Article/details/gtznxttevt.html

[S05] C：字符串长度
来源：http://dali.hfpthk.cn/Article/details/gtjevhlniw.html

strlen(s)
来源：http://dali.nanxuanxn.top/Article/details/gtwnsollvr.html

[S06] C：字符串比较
来源：http://dali.chenzaomai.com/Article/details/gtvrtgeldt.html

strcmp(a, b) == 0
来源：http://dali.tanke756.top/Article/details/gtucktvcbn.html

[S07] C：数组遍历求和
来源：http://dali.yj20258.top/Article/details/gtvlpxrxwr.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shuidangran.top/Article/details/gtevvhdpkz.html

[S08] C：动态内存分配与释放
来源：http://dali.hnxiangtu.top/Article/details/gtoalmfarw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.tanke756.top/Article/details/gtnwuhnnib.html

[S09] C：结构体定义与初始化
来源：http://dali.yueranfly.top/Article/details/gtoxirkxlt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.svipenyu.cn/Article/details/gtepezbkto.html

[S10] C：指针与解引用
来源：http://dali.ybcxt.top/Article/details/gtzpvcldjl.html

int *p = &a;  *p = 5;
来源：http://dali.pycfn.com/Article/details/gtxkpevogj.html

[S11] C：逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gtbuppjndo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.iojbl.cn/Article/details/gtxzwdiscv.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.havefunace.top/Article/details/gtitfalbdc.html

fclose(f);
来源：http://dali.xinyue.icu/Article/details/gtuifslozr.html

[S12] C：写文件
来源：http://dali.hfpthk.cn/Article/details/gtcyxieszm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.guannengcc.top/Article/details/gtvjybacqx.html

[S13] C：宏定义
来源：http://dali.pycfn.com/Article/details/gtcphrvnzz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinqigfzy.top/Article/details/gtfarmbweg.html

[S14] C：枚举
来源：http://dali.kuanghao11.cn/Article/details/gtkkecanjr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.316326.xyz/Article/details/gtyjspsxkh.html

[S15] C：类型转换
来源：http://dali.daria6918.cn/Article/details/gtasgzndgj.html

(double) a / b
来源：http://dali.yangfankeji.com/Article/details/gttupzghyn.html

[S16] C：位操作置位
来源：http://dali.9152youxi.cn/Article/details/gtrfqkjpku.html

x |= (1 << 3);
来源：http://dali.wangdashe.top/Article/details/gtapdgqnbq.html

[S17] C：安全拼接字符串
来源：http://dali.zhongyouzk.top/Article/details/gtyddokfia.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xziqi.cn/Article/details/gtgqbdmtrl.html

[S18] C：命令行参数
来源：http://dali.jqgfzy.top/Article/details/gtzcbehpcl.html

int main(int argc, char **argv)
来源：http://dali.ybcxt.top/Article/details/gtuohscwkf.html

[S19] C：快速排序
来源：http://dali.iojbl.cn/Article/details/gtbjpgxugs.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.meibo888.top/Article/details/gtavrfcdaj.html

[S20] C：二分查找
来源：http://dali.aibaodan.cn/Article/details/gtqpdukxeq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtalrsoymv.html

[S21] C：字符类别判断
来源：http://dali.pengpengdd.cyou/Article/details/gtyqxpizlf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.tian-w.cn/Article/details/gtpvxodutk.html

[S22] C：字符串转数字
来源：http://dali.yonumen.top/Article/details/gtlhjzjjua.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.aizwys.cn/Article/details/gtlyowkvgf.html

[S23] C：随机数
来源：http://dali.chenzaomai.com/Article/details/gtlmbmnpjk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yvedp.cn/Article/details/gtwcnwqsmo.html

[S24] C：获取本地时间
来源：http://dali.tian-w.cn/Article/details/gtqbgjduca.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.aibaodan.cn/Article/details/gtdvjqizwl.html

[S25] C：内存拷贝
来源：http://dali.chenlongwang.top/Article/details/gtelqxhazh.html

memcpy(dst, src, n);
来源：http://dali.sysykeji.top/Article/details/gtmvoiqvmc.html

[S26] C：内存清零
来源：http://dali.hnqzz.top/Article/details/gticypiiqd.html

memset(a, 0, sizeof a);
来源：http://dali.tian-w.cn/Article/details/gtwpdjqdeu.html

[S27] C：定义常量
来源：http://dali.hfpthk.cn/Article/details/gtaydlfeey.html

const double PI = 3.14159;
来源：http://dali.zhongyouzk.top/Article/details/gtaccbixei.html

[S28] C：静态变量
来源：http://dali.xziqi.cn/Article/details/gtjatflfbs.html

static int counter = 0;
来源：http://dali.yangfankeji.com/Article/details/gtbdmfsvqy.html

[S29] C：变参函数
来源：http://dali.cucudq.cn/Article/details/gtlnqqkmbc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yuxming.cn/Article/details/gtmcbmmcet.html

[S30] C：头文件保护
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdvwxkqpl.html

#ifndef X_H
来源：http://dali.tian-w.cn/Article/details/gtkkhjynfq.html

#define X_H
来源：http://dali.wangdashe.top/Article/details/gtqwfxtllv.html

#endif
来源：http://dali.zhongyouzk.top/Article/details/gtwqirftae.html

[S31] C++：Hello World
来源：http://dali.snrcjt.cn/Article/details/gtbxiirjor.html

#include <iostream>
来源：http://dali.shanyushiyangtech.top/Article/details/gttwhrvrwq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jqgufenzy.top/Article/details/gtdrekukmd.html

[S32] C++：字符串
来源：http://dali.sxryk.cn/Article/details/gtiyexebrx.html

std::string s = "hi";  s += "!";
来源：http://dali.chenzaomai.com/Article/details/gtejglklze.html

[S33] C++：vector 增删
来源：http://dali.andypj.xyz/Article/details/gtvdwhvpgs.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gtdmvwckaw.html

[S34] C++：遍历 vector
来源：http://dali.hysaishi.cn/Article/details/gthsbgaqdp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cqqwz.cn/Article/details/gtotgqkxej.html

[S35] C++：map
来源：http://dali.kuanghao11.cn/Article/details/gtpzyauorq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhongyouzk.top/Article/details/gtaqyzhoxl.html

[S36] C++：unordered_map
来源：http://dali.shuidangran.top/Article/details/gtzponmbmu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gtwalbgmki.html

[S37] C++：set
来源：http://dali.tianlin.xyz/Article/details/gtclogswtc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yuxming.cn/Article/details/gtkppxruzt.html

[S38] C++：排序
来源：http://dali.xinyue.icu/Article/details/gtgxztlyqi.html

std::sort(v.begin(), v.end());
来源：http://dali.andypj.xyz/Article/details/gtewbytpuz.html

[S39] C++：自定义比较器排序
来源：http://dali.tianlin.xyz/Article/details/gtocwvaxcw.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sweek.top/Article/details/gtdvpksemn.html

[S40] C++：查找元素
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzzoxtoiz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.smart0.xyz/Article/details/gtvmkcjgxy.html

[S41] C++：类与构造函数
来源：http://dali.sysykeji.top/Article/details/gtjibgxitm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hfpthk.cn/Article/details/gtqcamolrb.html

[S42] C++：继承与虚函数
来源：http://dali.zhoulong.xyz/Article/details/gtaeyqbdbt.html

class B : public Base { public: void f() override {} };
来源：http://dali.gogol.net.cn/Article/details/gtakxfvqrm.html

[S43] C++：智能指针
来源：http://dali.jiagoushi.top/Article/details/gtzyesxtxa.html

auto p = std::make_unique<int>(5);
来源：http://dali.gzhubu.top/Article/details/gtwmpsntvk.html

[S44] C++：引用传参
来源：http://dali.shangyingyoupin.top/Article/details/gtshlwmltw.html

void inc(int &x) { ++x; }
来源：http://dali.bjfxy.top/Article/details/gtabzmgvbk.html

[S45] C++：lambda
来源：http://dali.cashguo.top/Article/details/gtdzyatrjr.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.fzhhl.top/Article/details/gtzniytzns.html

[S46] C++：函数模板
来源：http://dali.vqdsnc.cn/Article/details/gtprothxhw.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gotoacloud.top/Article/details/gtrupllmrz.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhixingplan.top/Article/details/gtootsbyfv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sysykeji.top/Article/details/gtybusyqcd.html

[S48] C++：逐行读文件
来源：http://dali.gzhubu.top/Article/details/gtntwxpepz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yueranfly.top/Article/details/gtpsxccpgu.html

while (std::getline(in, line)) { }
来源：http://dali.shzxlz.cn/Article/details/gttvbtkykm.html

[S49] C++：写文件
来源：http://dali.hywenlv.cn/Article/details/gtoggiqubu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.smart0.xyz/Article/details/gtpbixfcim.html

[S50] C++：格式化数字
来源：http://dali.zhiwuduotai.top/Article/details/gtmuvsvoob.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.feifeiyinyue.top/Article/details/gtusaknsfk.html

[S51] C++：显式类型转换
来源：http://dali.yuxming.cn/Article/details/gtngmnbdsy.html

static_cast<double>(a) / b
来源：http://dali.gotoacloud.top/Article/details/gtnhbotxge.html

[S52] C++：const 与 noexcept
来源：http://dali.aibaodan.cn/Article/details/gtcazplwgh.html

int size() const noexcept { return n_; }
来源：http://dali.wangshuangyany.cn/Article/details/gtglvalfcy.html

[S53] C++：移动语义
来源：http://dali.jqgufenzy.top/Article/details/gtcyuezviy.html

std::vector<int> w = std::move(v);
来源：http://dali.tianlin.xyz/Article/details/gtlocgnywp.html

[S54] C++：异常处理
来源：http://dali.pengpengdd.cyou/Article/details/gtcokzcrhj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.birdmap.top/Article/details/gtjrnikold.html

[S55] C++：结构化绑定
来源：http://dali.shuidangran.top/Article/details/gtwzhdmxzj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xuetiantiany.cn/Article/details/gthyzevrzn.html

[S56] C++：optional
来源：http://dali.fengsongda.top/Article/details/gtesxwunru.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.snrcjt.cn/Article/details/gtyuipludg.html

[S57] C++：编译期常量
来源：http://dali.xuanzx.com/Article/details/gtdfmbdpap.html

constexpr int N = 10;
来源：http://dali.jinqigfzy.top/Article/details/gtodiahpjf.html

[S58] C++：命名空间
来源：http://dali.yvedp.cn/Article/details/gtkczibscl.html

namespace ns { int f() { return 1; } }
来源：http://dali.jqgfzy.top/Article/details/gtptdjwcoc.html

[S59] C++：静态断言
来源：http://dali.yj20258.top/Article/details/gtlagiaaju.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.kuanghao11.cn/Article/details/gtdrfyzonh.html

[S60] C++：遍历并删除元素
来源：http://dali.wangshuangyany.cn/Article/details/gtktjbxask.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cqqwz.cn/Article/details/gtnxlnvvfh.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtnscaantl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.xinyue.icu/Article/details/gtcqyawzpr.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtolbzbkfp.html

[T01] Kotlin：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gtdkzhvywo.html

println("Hello")
来源：http://dali.zhoulong.xyz/Article/details/gtsekenkqb.html

[T02] Kotlin：变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtedpegtpt.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xylfe.cn/Article/details/gtfomjspmq.html

[T03] Kotlin：字符串模板
来源：http://dali.cashguo.top/Article/details/gtgutomtme.html

"值: $b"
来源：http://dali.aizwys.cn/Article/details/gtvtxmoqzw.html

[T04] Kotlin：空安全
来源：http://dali.bjfxy.top/Article/details/gtbsdjqlgs.html

val n: String? = null;  n?.length
来源：http://dali.jqgfzy.top/Article/details/gtmpowesft.html

[T05] Kotlin：when 表达式
来源：http://dali.vqdsnc.cn/Article/details/gtjmprohjs.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.nwbrower.top/Article/details/gtakfmsclv.html

[T06] Kotlin：集合映射
来源：http://dali.xylfe.cn/Article/details/gtvarlnqyr.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.dianchejie.cn/Article/details/gtajzdgbhf.html

[T07] Kotlin：集合过滤
来源：http://dali.jlsjyb.cn/Article/details/gttkjfcygj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.gzhubu.top/Article/details/gtgzebiord.html

[T08] Kotlin：数据类
来源：http://dali.daria6918.cn/Article/details/gtdlhogypc.html

data class User(val name: String, val age: Int)
来源：http://dali.jqgufenzy.top/Article/details/gtcgfanmbx.html

[T09] Kotlin：扩展函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gthdfkmwcb.html

fun String.exclaim() = this + "!"
来源：http://dali.yj202588.top/Article/details/gteolorqjh.html

[T10] Kotlin：默认参数
来源：http://dali.quarkkingdee.top/Article/details/gtrnmuvejr.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.feifeiyinyue.top/Article/details/gtlufjyruj.html

[T11] Kotlin：协程
来源：http://dali.ybcxt.top/Article/details/gtbwbfabik.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shanyushiyangtech.top/Article/details/gtrpyqutie.html

[T12] Kotlin：解构声明
来源：http://dali.hysaishi.cn/Article/details/gtigbdevat.html

val (a, b) = Pair(1, 2)
来源：http://dali.yuanzhike.top/Article/details/gtrbfjrlyq.html

[T13] Kotlin：只读 Map
来源：http://dali.zdqjudy.top/Article/details/gtxtujbaat.html

val m = mapOf("a" to 1)
来源：http://dali.mhx1999.top/Article/details/gtbrcuguby.html

[T14] Kotlin：循环
来源：http://dali.ivvv.top/Article/details/gtlrzgnjzi.html

for (i in 1..10) println(i)
来源：http://dali.wangshuangyany.cn/Article/details/gtitgculsv.html

[T15] Kotlin：接口
来源：http://dali.ppjwa.cn/Article/details/gtaofkfmoq.html

interface Shape { fun area(): Double }
来源：http://dali.cdnleiting.top/Article/details/gtuwuhdkdv.html

[T16] Swift：Hello World
来源：http://dali.guannengcc.top/Article/details/gthlowzzfp.html

print("Hello")
来源：http://dali.jinqigfzy.top/Article/details/gtzfzlvnpy.html

[T17] Swift：变量与常量
来源：http://dali.hnqzz.top/Article/details/gtdkzouxzw.html

var a = 1;  let b = 2
来源：http://dali.smart0.xyz/Article/details/gtnnrxpwpd.html

[T18] Swift：字符串插值
来源：http://dali.andypj.xyz/Article/details/gtfjycbcdw.html

"值: \(b)"
来源：http://dali.smart0.xyz/Article/details/gtrmpvjojp.html

[T19] Swift：可选绑定
来源：http://dali.zhoulong.xyz/Article/details/gtaiwteuqe.html

if let n = opt { print(n) }
来源：http://dali.svipenyu.cn/Article/details/gtiqogwxch.html

[T20] Swift：数组操作
来源：http://dali.guowangkeji.top/Article/details/gtnzzjvvmm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.dianchejie.cn/Article/details/gtjhevfaot.html

[T21] Swift：遍历
来源：http://dali.tian-w.cn/Article/details/gtyvotxfne.html

for x in a { print(x) }
来源：http://dali.jqgfzy.top/Article/details/gtpsnhntoi.html

[T22] Swift：字典
来源：http://dali.sufxvd.cn/Article/details/gttveqvfni.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.meibo888.top/Article/details/gtgfoozmsp.html

[T23] Swift：函数
来源：http://dali.yueranfly.top/Article/details/gtmriunyid.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.wangshuangyany.cn/Article/details/gttlvlxqyr.html

[T24] Swift：闭包
来源：http://dali.ywan-chungtsiang.top/Article/details/gthikckbzb.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.sxryk.cn/Article/details/gtuqstwotx.html

[T25] Swift：结构体
来源：http://dali.yueranfly.top/Article/details/gtqqmmpllq.html

struct P { var x: Int }
来源：http://dali.chenzaomai.com/Article/details/gtavgykcxw.html

[T26] Swift：类与重写
来源：http://dali.zhiwuduotai.top/Article/details/gtijfogsyk.html

class A: Base { override func f() {} }
来源：http://dali.0kj1m.cn/Article/details/gtsiuidith.html

[T27] Swift：错误处理
来源：http://dali.cheryme.top/Article/details/gtawhwnuhs.html

do { try f() } catch { print(error) }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgczdzrsw.html

[T28] Swift：枚举
来源：http://dali.gogol.net.cn/Article/details/gtlbgmlelf.html

enum Color { case red, green }
来源：http://dali.zhongyouzk.top/Article/details/gtyhxbdmkq.html

[T29] Swift：guard 提前返回
来源：http://dali.jinyuanbaomall.cn/Article/details/gthkkazmsu.html

guard let x = opt else { return }
来源：http://dali.hysaishi.cn/Article/details/gtyljlqgct.html

[T30] Swift：协议
来源：http://dali.gogol.net.cn/Article/details/gtkrmduqho.html

protocol Shape { func area() -> Double }
来源：http://dali.zycfv.cn/Article/details/gtwjkthict.html

[T31] Lua：Hello World
来源：http://dali.ivvv.top/Article/details/gtldxqeuoc.html

print("Hello")
来源：http://dali.hongshengwenyu.top/Article/details/gtusbcgqmj.html

[T32] Lua：局部变量
来源：http://dali.yuanzhike.top/Article/details/gtwkshesxa.html

local a = 1
来源：http://dali.yj20258888.top/Article/details/gtgsavgoiy.html

[T33] Lua：表（数组）
来源：http://dali.0kj1m.cn/Article/details/gtqdpkncqi.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.bjfxy.top/Article/details/gtjbetlqyk.html

[T34] Lua：遍历表
来源：http://dali.aibaodan.cn/Article/details/gtctrbqzrt.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.fzhhl.top/Article/details/gtykyzyjke.html

[T35] Lua：字典表
来源：http://dali.hongshengwenyu.top/Article/details/gtgulvlzzl.html

local d = { a = 1 };  d.b = 2
来源：http://dali.nwbrower.top/Article/details/gtdoenusph.html

[T36] Lua：函数
来源：http://dali.cheryme.top/Article/details/gtqflfzaqf.html

function add(a, b) return a + b end
来源：http://dali.c1oappe.top/Article/details/gtmbotyczj.html

[T37] Lua：字符串拼接
来源：http://dali.wangdashe.top/Article/details/gtyvvwpcmp.html

"a" .. "b"
来源：http://dali.shzxlz.cn/Article/details/gtosesjqxm.html

[T38] Lua：条件
来源：http://dali.ybcxt.top/Article/details/gtfgyugpdk.html

if x > 0 then print("正") end
来源：http://dali.hongshengwenyu.top/Article/details/gtvbpuzvvk.html

[T39] Lua：模式匹配
来源：http://dali.nanxuanxn.top/Article/details/gtksyyvzuc.html

string.find(s, "%d+")
来源：http://dali.shzxlz.cn/Article/details/gtulwqpczo.html

[T40] Lua：元表
来源：http://dali.zhongyouzk.top/Article/details/gtsatytkoj.html

setmetatable({}, { __index = base })
来源：http://dali.gaohongyu789.top/Article/details/gtomtaphpm.html

[T41] Perl：Hello World
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwnrtlqqg.html

print "Hello\n";
来源：http://dali.hywenlv.cn/Article/details/gtilryqgmc.html

[T42] Perl：变量类型
来源：http://dali.ppjwa.cn/Article/details/gtatsvnewe.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.yvedp.cn/Article/details/gtmruqdaxw.html

[T43] Perl：字符串插值
来源：http://dali.xylfe.cn/Article/details/gtleirklun.html

"值: $a"
来源：http://dali.birdmap.top/Article/details/gtvkvohidt.html

[T44] Perl：条件
来源：http://dali.nanxuanxn.top/Article/details/gtuekzbrov.html

if ($a > 0) { print "正"; }
来源：http://dali.jyoumei.cn/Article/details/gtepskklhj.html


<!-- 参考信息 -->