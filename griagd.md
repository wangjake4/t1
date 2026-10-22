代发 wailian999

cmd >/dev/null 2>&1
来源：http://dali.shzxlz.cn/Article/details/gtaseerzeq.html

[R42] 输入重定向
来源：http://dali.xziqi.cn/Article/details/gtktkpxgjk.html

wc -l < a.txt
来源：http://dali.meibo888.top/Article/details/gtbdmfuxhj.html

[R43] 按名字查找文件
来源：http://dali.tanke756.top/Article/details/gtubpydepl.html

find . -name "*.log" -type f
来源：http://dali.jianghu66.top/Article/details/gtzdhuioox.html

[R44] 按修改时间查找
来源：http://dali.0kj1m.cn/Article/details/gtmcroewih.html

find . -mtime -7 -type f
来源：http://dali.wangshuangyany.cn/Article/details/gtebwnvqxv.html

[R45] 批量删除
来源：http://dali.c1oappe.top/Article/details/gtxjlqvyjm.html

find . -name "*.tmp" -delete
来源：http://dali.sxryk.cn/Article/details/gtqyhbwdua.html

[R46] 递归替换文件内容
来源：http://dali.jinqigfzy.top/Article/details/gtnzwftscq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.pengpengdd.cyou/Article/details/gtdbtdqfip.html

[R47] sed 单行替换
来源：http://dali.tianlin.xyz/Article/details/gtxwuxzoef.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.chenlongwang.top/Article/details/gtzyklorog.html

[R48] awk 取指定列
来源：http://dali.gzhubu.top/Article/details/gtvjdyddvu.html

awk '{print $1, $3}' a.txt
来源：http://dali.jqgfzy.top/Article/details/gtqmzgbtug.html

[R49] awk 带条件
来源：http://dali.guowangkeji.top/Article/details/gtkhyvzdqi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.wangshuangyany.cn/Article/details/gtrqcdbbrj.html

[R50] awk 求和
来源：http://dali.gogol.net.cn/Article/details/gtouhdjxcb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.tian-w.cn/Article/details/gtcjlvnxfd.html

[R51] 排序去重取前几
来源：http://dali.vqdsnc.cn/Article/details/gttnerbgyr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hysaishi.cn/Article/details/gtoxufhydn.html

[R52] 统计行数
来源：http://dali.sxryk.cn/Article/details/gtcuxdhaym.html

wc -l a.txt
来源：http://dali.meibo888.top/Article/details/gtsuxtatxu.html

[R53] 查看文件头与实时尾
来源：http://dali.c1oappe.top/Article/details/gtdknwjtci.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.havefunace.top/Article/details/gtyvmfgade.html

[R54] 比较两个文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthwrgdoxf.html

diff a.txt b.txt
来源：http://dali.ydzc1.top/Article/details/gtyjvmsjtz.html

[R55] 压缩与解压
来源：http://dali.redwolf501.top/Article/details/gtdgazaier.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jiagoushi.top/Article/details/gtpefdregv.html

[R56] 远程拷贝
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdihfcqit.html

scp file user@host:/path/
来源：http://dali.ehwqpu.com/Article/details/gtriutjfku.html

[R57] 远程执行命令
来源：http://dali.yonumen.top/Article/details/gtftnbfnjb.html

ssh user@host 'uptime'
来源：http://dali.guannengcc.top/Article/details/gtxfixiypf.html

[R58] 下载文件
来源：http://dali.zhixingplan.top/Article/details/gtkpiiwqhj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjsmuennz.html

[R59] 发 POST JSON
来源：http://dali.hnqzz.top/Article/details/gtnfgfutbr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jlsjyb.cn/Article/details/gtoexvmbsk.html

[R60] 只看 HTTP 状态码
来源：http://dali.dianchejie.cn/Article/details/gtteyqgtrh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zdqjudy.top/Article/details/gtgtzpgrcg.html

[R61] 磁盘占用
来源：http://dali.xinyue.icu/Article/details/gtsukmahqj.html

df -h;  du -sh *
来源：http://dali.ppjwa.cn/Article/details/gtefutqmip.html

[R62] 找最占空间的文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgroiyhuo.html

du -ah . | sort -rh | head -10
来源：http://dali.snrcjt.cn/Article/details/gtiikuruht.html

[R63] 内存与进程
来源：http://dali.cheryme.top/Article/details/gtgpkjiqsl.html

free -h;  ps aux | grep nginx
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqlxftzzx.html

[R64] 结束进程
来源：http://dali.tianlin.xyz/Article/details/gteuicldnh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.daxiang520.top/Article/details/gtmiibomsi.html

[R65] 查看端口占用
来源：http://dali.dianchejie.cn/Article/details/gtrjdxsqee.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shanyushiyangtech.top/Article/details/gttjdixrtu.html

[R66] 定时任务
来源：http://dali.shuidangran.top/Article/details/gtcrsiicai.html

crontab -e;  crontab -l
来源：http://dali.hysaishi.cn/Article/details/gtcvepdjev.html

[R67] 生成随机十六进制串
来源：http://dali.hnxiangtu.top/Article/details/gtrkelbbbg.html

openssl rand -hex 16
来源：http://dali.pycfn.com/Article/details/gtwwyayqpt.html

[R68] 计算文件校验值
来源：http://dali.yj202588.top/Article/details/gtjhcxwyny.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.guannengcc.top/Article/details/gtahowwgpz.html

[R69] 生成随机密码
来源：http://dali.birdmap.top/Article/details/gttdzbkyvz.html

head -c 16 /dev/urandom | base64
来源：http://dali.jiagoushi.top/Article/details/gtmcgyhwyh.html

[R70] 时间戳与互转
来源：http://dali.316326.xyz/Article/details/gtwdskmdfd.html

date +%s;  date -d @1700000000
来源：http://dali.316326.xyz/Article/details/gthwzajeoo.html

[R71] 日期格式化
来源：http://dali.gogol.net.cn/Article/details/gtajlungmy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj20258888.top/Article/details/gtpokfadbp.html

[R72] 等待端口就绪
来源：http://dali.iojbl.cn/Article/details/gthvgbutwk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shzxlz.cn/Article/details/gtvzsqabrd.html

[R73] 分割大日志
来源：http://dali.sxryk.cn/Article/details/gtcuaxsrvj.html

split -l 1000 big.log part_
来源：http://dali.hfpthk.cn/Article/details/gtptbehxpe.html

[R74] 批量重命名
来源：http://dali.nanxuanxn.top/Article/details/gtmpqvlltn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xinyue.icu/Article/details/gttxpoxibs.html

[R75] 导出环境变量
来源：http://dali.zycfv.cn/Article/details/gtymtlecav.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hongshengwenyu.top/Article/details/gtqdupuinh.html

[R76] 使用临时文件
来源：http://dali.zdqjudy.top/Article/details/gtpkaqjust.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.pengpengdd.cyou/Article/details/gtpxqxysyd.html

[R77] 读取用户输入
来源：http://dali.jqgufenzy.top/Article/details/gtpfgqrpwq.html

read -rp "请输入: " ans
来源：http://dali.zhixingplan.top/Article/details/gtjfjbscng.html

[R78] 交互式菜单
来源：http://dali.sxryk.cn/Article/details/gtmgzdywbd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.bjfxy.top/Article/details/gtnjssfegk.html

[R79] 解析命令行选项
来源：http://dali.shanyushiyangtech.top/Article/details/gtfzdaosnz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yj202588.top/Article/details/gtlzyalbnf.html

[R80] 查看脚本执行耗时
来源：http://dali.c1oappe.top/Article/details/gtjinpmmyt.html

time ./run.sh
来源：http://dali.pycfn.com/Article/details/gthixqhwim.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtedjmcxtd.html

S. C / C++ 专题
来源：http://dali.aizwys.cn/Article/details/gtggjdpwft.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtotcmkrkj.html

[S01] C：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtetheshhy.html

#include <stdio.h>
来源：http://dali.redwolf501.top/Article/details/gtpscbdhnh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cashguo.top/Article/details/gtvlbibbwh.html

[S02] C：变量与格式化输出
来源：http://dali.shanyushiyangtech.top/Article/details/gtufwlnhib.html

int a = 10; printf("%d\n", a);
来源：http://dali.sxryk.cn/Article/details/gtvqvyhjii.html

[S03] C：读入整数
来源：http://dali.pycfn.com/Article/details/gtqsfgqfzc.html

int x; scanf("%d", &x);
来源：http://dali.yuxming.cn/Article/details/gtdtkqxjpc.html

[S04] C：字符串复制
来源：http://dali.hnxiangtu.top/Article/details/gtkrkjkzcw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhoulong.xyz/Article/details/gtihfevbae.html

[S05] C：字符串长度
来源：http://dali.yueranfly.top/Article/details/gteoneoonf.html

strlen(s)
来源：http://dali.zhiwuduotai.top/Article/details/gtbpqupupk.html

[S06] C：字符串比较
来源：http://dali.redwolf501.top/Article/details/gtjooensed.html

strcmp(a, b) == 0
来源：http://dali.gzhubu.top/Article/details/gtgbtyitix.html

[S07] C：数组遍历求和
来源：http://dali.sufxvd.cn/Article/details/gtnyhaqxjq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.havefunace.top/Article/details/gtrgqxmupa.html

[S08] C：动态内存分配与释放
来源：http://dali.jiagoushi.top/Article/details/gtbiemsqgu.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yj202588.top/Article/details/gttlobtkwb.html

[S09] C：结构体定义与初始化
来源：http://dali.hfpthk.cn/Article/details/gtcptfvsgv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.aibaodan.cn/Article/details/gtpupptfry.html

[S10] C：指针与解引用
来源：http://dali.zdqjudy.top/Article/details/gtdxgexrkj.html

int *p = &a;  *p = 5;
来源：http://dali.feifeiyinyue.top/Article/details/gtjuzhexex.html

[S11] C：逐行读文件
来源：http://dali.mhx1999.top/Article/details/gtmlgcmwsy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhengqikj.top/Article/details/gtkqwbsvir.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.meibo888.top/Article/details/gtfmjuptje.html

fclose(f);
来源：http://dali.hongshengwenyu.top/Article/details/gtsustiych.html

[S12] C：写文件
来源：http://dali.jqgfzy.top/Article/details/gtdmwodltt.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.haohaochexian.top/Article/details/gtmlznyzzg.html

[S13] C：宏定义
来源：http://dali.ybcxt.top/Article/details/gtdbhucwce.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.svipenyu.cn/Article/details/gtikbbotfd.html

[S14] C：枚举
来源：http://dali.zhoulong.xyz/Article/details/gtqwjtbsuw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cucudq.cn/Article/details/gtgfggnyvb.html

[S15] C：类型转换
来源：http://dali.jyoumei.cn/Article/details/gtozzjtkih.html

(double) a / b
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbrrnxtwe.html

[S16] C：位操作置位
来源：http://dali.yvedp.cn/Article/details/gtwuxvrvul.html

x |= (1 << 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqnwakhvb.html

[S17] C：安全拼接字符串
来源：http://dali.jinqigufen.top/Article/details/gtrsceuath.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jlsjyb.cn/Article/details/gtvwuiqcwd.html

[S18] C：命令行参数
来源：http://dali.wangshuangyany.cn/Article/details/gtxgxpqshg.html

int main(int argc, char **argv)
来源：http://dali.shzxlz.cn/Article/details/gtsfegnvor.html

[S19] C：快速排序
来源：http://dali.hnxiangtu.top/Article/details/gtybnmgusa.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhoulong.xyz/Article/details/gtvkloncpd.html

[S20] C：二分查找
来源：http://dali.fzhhl.top/Article/details/gtsogdcmws.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hnxiangtu.top/Article/details/gtneixpwna.html

[S21] C：字符类别判断
来源：http://dali.316326.xyz/Article/details/gtawsminwc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.meibo888.top/Article/details/gtuincqjtn.html

[S22] C：字符串转数字
来源：http://dali.zhongyouzk.top/Article/details/gttmzkcvsk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ehwqpu.com/Article/details/gtyjpsjoot.html

[S23] C：随机数
来源：http://dali.sufxvd.cn/Article/details/gtfdhqozhi.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.wangshuangyany.cn/Article/details/gtzydeqsqx.html

[S24] C：获取本地时间
来源：http://dali.dashuyun.cn/Article/details/gtfdjitzsq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.sxryk.cn/Article/details/gtcqlclzhd.html

[S25] C：内存拷贝
来源：http://dali.jinqigfzy.top/Article/details/gthrkawask.html

memcpy(dst, src, n);
来源：http://dali.xziqi.cn/Article/details/gtgffwppaj.html

[S26] C：内存清零
来源：http://dali.yonumen.top/Article/details/gtwuxlbiiu.html

memset(a, 0, sizeof a);
来源：http://dali.aizwys.cn/Article/details/gtayscoacq.html

[S27] C：定义常量
来源：http://dali.hongshengwenyu.top/Article/details/gtleubagjb.html

const double PI = 3.14159;
来源：http://dali.yj20258.top/Article/details/gtnteigvas.html

[S28] C：静态变量
来源：http://dali.ybcxt.top/Article/details/gttluzrenz.html

static int counter = 0;
来源：http://dali.ivvv.top/Article/details/gtqdaugzno.html

[S29] C：变参函数
来源：http://dali.gaohongyu789.top/Article/details/gtbynxruhf.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.wangdashe.top/Article/details/gtefzveqxs.html

[S30] C：头文件保护
来源：http://dali.yuxming.cn/Article/details/gtlillmnlf.html

#ifndef X_H
来源：http://dali.gotoacloud.top/Article/details/gtavwxskyn.html

#define X_H
来源：http://dali.yuanzhike.top/Article/details/gtbgtikyfj.html

#endif
来源：http://dali.tanke756.top/Article/details/gtzvgolhfu.html

[S31] C++：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtklacqnmk.html

#include <iostream>
来源：http://dali.tanke756.top/Article/details/gttzwfzmft.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtcyqrckjd.html

[S32] C++：字符串
来源：http://dali.gotoacloud.top/Article/details/gtpxpjaiai.html

std::string s = "hi";  s += "!";
来源：http://dali.hnqzz.top/Article/details/gtkatjsnqw.html

[S33] C++：vector 增删
来源：http://dali.jinghuilouyu.cn/Article/details/gtdncowwak.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.mhx1999.top/Article/details/gttleodsoz.html

[S34] C++：遍历 vector
来源：http://dali.yangfankeji.com/Article/details/gtssrdccsq.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.smart0.xyz/Article/details/gtaoaivdsg.html

[S35] C++：map
来源：http://dali.feifeiyinyue.top/Article/details/gtopovjezx.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.daria6918.cn/Article/details/gtxouttxzn.html

[S36] C++：unordered_map
来源：http://dali.andypj.xyz/Article/details/gtqgueeezt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdvtxdluk.html

[S37] C++：set
来源：http://dali.gaohongyu789.top/Article/details/gtgskhwpwi.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.iojbl.cn/Article/details/gtfaisqkxo.html

[S38] C++：排序
来源：http://dali.hammf.cn/Article/details/gthoraopku.html

std::sort(v.begin(), v.end());
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqesyorlz.html

[S39] C++：自定义比较器排序
来源：http://dali.nanxinkj.top/Article/details/gtohxrnbpo.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.wangshuangyany.cn/Article/details/gtxdtbynmu.html

[S40] C++：查找元素
来源：http://dali.tianlin.xyz/Article/details/gtrjylhrvm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhengqikj.top/Article/details/gtxdajxpkf.html

[S41] C++：类与构造函数
来源：http://dali.xuanzx.com/Article/details/gtfqfxgqar.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hysaishi.cn/Article/details/gtlcxkizxt.html

[S42] C++：继承与虚函数
来源：http://dali.chenjidiqi.icu/Article/details/gtrvmzcngy.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinqigfzy.top/Article/details/gtvuisrpbp.html

[S43] C++：智能指针
来源：http://dali.jyoumei.cn/Article/details/gtgevgloqu.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinqigufen.top/Article/details/gtmssmrvjn.html

[S44] C++：引用传参
来源：http://dali.cqqwz.cn/Article/details/gtnkeyguub.html

void inc(int &x) { ++x; }
来源：http://dali.chenlongwang.top/Article/details/gttdjarhut.html

[S45] C++：lambda
来源：http://dali.meibo888.top/Article/details/gtarpprtil.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shangyingyoupin.top/Article/details/gtoldutmvt.html

[S46] C++：函数模板
来源：http://dali.cqqwz.cn/Article/details/gthltqzcae.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hfpthk.cn/Article/details/gtmfkxfnoe.html

[S47] C++：结构化绑定遍历
来源：http://dali.sufxvd.cn/Article/details/gthovbfebn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shangyingyoupin.top/Article/details/gtuxcxooqf.html

[S48] C++：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gttltxgkfz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.aibaodan.cn/Article/details/gtxgffmjqd.html

while (std::getline(in, line)) { }
来源：http://dali.chenlongwang.top/Article/details/gtujizhcrs.html

[S49] C++：写文件
来源：http://dali.yueranfly.top/Article/details/gtrzidesoi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jianghu66.top/Article/details/gtujyotojh.html

[S50] C++：格式化数字
来源：http://dali.meibo888.top/Article/details/gtqdnuplvm.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gtxifjkeoo.html

[S51] C++：显式类型转换
来源：http://dali.yj20258.top/Article/details/gtlheioquc.html

static_cast<double>(a) / b
来源：http://dali.cucudq.cn/Article/details/gtnulbyrdv.html

[S52] C++：const 与 noexcept
来源：http://dali.sxryk.cn/Article/details/gtslwkkqtb.html

int size() const noexcept { return n_; }
来源：http://dali.chenzaomai.com/Article/details/gtqurbhcvx.html

[S53] C++：移动语义
来源：http://dali.gotoacloud.top/Article/details/gtneosmxye.html

std::vector<int> w = std::move(v);
来源：http://dali.chenlongwang.top/Article/details/gtdfsevpbo.html

[S54] C++：异常处理
来源：http://dali.yj20258.top/Article/details/gtoegszsfg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hywenlv.cn/Article/details/gtwihdxiyp.html

[S55] C++：结构化绑定
来源：http://dali.cashguo.top/Article/details/gtebbcasfn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhengqikj.top/Article/details/gtlyneavfa.html

[S56] C++：optional
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmfvrsvwe.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.snrcjt.cn/Article/details/gttxqynziz.html

[S57] C++：编译期常量
来源：http://dali.cucudq.cn/Article/details/gtxlcxanlt.html

constexpr int N = 10;
来源：http://dali.hfpthk.cn/Article/details/gtwriwstpe.html

[S58] C++：命名空间
来源：http://dali.hnxiangtu.top/Article/details/gtmcdqtuqb.html

namespace ns { int f() { return 1; } }
来源：http://dali.xylfe.cn/Article/details/gtgziwzdhv.html

[S59] C++：静态断言
来源：http://dali.cucudq.cn/Article/details/gthvtyfqfc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.birdmap.top/Article/details/gtndnzzzjf.html

[S60] C++：遍历并删除元素
来源：http://dali.shzxlz.cn/Article/details/gtmedyurjy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.meibo888.top/Article/details/gtokivqkzf.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtebaostro.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hongshengwenyu.top/Article/details/gtwrgglwiy.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtxvezbjfh.html

[T01] Kotlin：Hello World
来源：http://dali.andypj.xyz/Article/details/gtdvzqguiz.html

println("Hello")
来源：http://dali.aizwys.cn/Article/details/gtibajhxrf.html

[T02] Kotlin：变量
来源：http://dali.316326.xyz/Article/details/gtabawtglz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.chenjidiqi.icu/Article/details/gtodbubvog.html

[T03] Kotlin：字符串模板
来源：http://dali.svipenyu.cn/Article/details/gtcmebsfxp.html

"值: $b"
来源：http://dali.cdnleiting.top/Article/details/gtyrvwzvpe.html

[T04] Kotlin：空安全
来源：http://dali.chenjidiqi.icu/Article/details/gtyovpbsgj.html

val n: String? = null;  n?.length
来源：http://dali.fengsongda.top/Article/details/gtistisjdl.html

[T05] Kotlin：when 表达式
来源：http://dali.jyoumei.cn/Article/details/gtdkznzmxa.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.pengpengdd.cyou/Article/details/gtmllqxbao.html

[T06] Kotlin：集合映射
来源：http://dali.sysykeji.top/Article/details/gtludajpiv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xinyue.icu/Article/details/gtnhlxzqej.html

[T07] Kotlin：集合过滤
来源：http://dali.cdnleiting.top/Article/details/gtocukwfqe.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.mhx1999.top/Article/details/gtpokuhadc.html

[T08] Kotlin：数据类
来源：http://dali.tian-w.cn/Article/details/gtulxpcocn.html

data class User(val name: String, val age: Int)
来源：http://dali.pycfn.com/Article/details/gtulkpsrmx.html

[T09] Kotlin：扩展函数
来源：http://dali.kuanghao11.cn/Article/details/gteoxecbsd.html

fun String.exclaim() = this + "!"
来源：http://dali.zhixingplan.top/Article/details/gtltbkegrs.html

[T10] Kotlin：默认参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzucniuym.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.dashuyun.cn/Article/details/gtloshybny.html

[T11] Kotlin：协程
来源：http://dali.tanke756.top/Article/details/gtfipfexlm.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtctbnpafl.html

[T12] Kotlin：解构声明
来源：http://dali.iojbl.cn/Article/details/gtfoqeblvk.html

val (a, b) = Pair(1, 2)
来源：http://dali.daria6918.cn/Article/details/gtweciojeo.html

[T13] Kotlin：只读 Map
来源：http://dali.nanxuanxn.top/Article/details/gtjurgogna.html

val m = mapOf("a" to 1)
来源：http://dali.fzhhl.top/Article/details/gtiygynbek.html

[T14] Kotlin：循环
来源：http://dali.zdqjudy.top/Article/details/gtpmhuynfw.html

for (i in 1..10) println(i)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuyedyhpi.html

[T15] Kotlin：接口
来源：http://dali.xinyue.icu/Article/details/gttpqpnfpa.html

interface Shape { fun area(): Double }
来源：http://dali.aizwys.cn/Article/details/gtuaeexuji.html

[T16] Swift：Hello World
来源：http://dali.pycfn.com/Article/details/gtmcfdimul.html

print("Hello")
来源：http://dali.shuidangran.top/Article/details/gtdcnkaliu.html

[T17] Swift：变量与常量
来源：http://dali.quarkkingdee.top/Article/details/gtlpctjhzy.html

var a = 1;  let b = 2
来源：http://dali.gogol.net.cn/Article/details/gtiyroixrs.html

[T18] Swift：字符串插值
来源：http://dali.wangshuangyany.cn/Article/details/gtlalogwot.html

"值: \(b)"
来源：http://dali.zhongyouzk.top/Article/details/gthnllbovv.html

[T19] Swift：可选绑定
来源：http://dali.yj202588.top/Article/details/gtoqzluzkx.html

if let n = opt { print(n) }
来源：http://dali.andypj.xyz/Article/details/gtvflaofeu.html

[T20] Swift：数组操作
来源：http://dali.zhoulong.xyz/Article/details/gtujiyteap.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj20258.top/Article/details/gtioejsmbu.html

[T21] Swift：遍历
来源：http://dali.chenlongwang.top/Article/details/gtjcsogpcf.html

for x in a { print(x) }
来源：http://dali.quarkkingdee.top/Article/details/gtnzwdhruy.html

[T22] Swift：字典
来源：http://dali.zhixingplan.top/Article/details/gtglmpimne.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.pycfn.com/Article/details/gttqfmgljn.html

[T23] Swift：函数
来源：http://dali.jinqigufen.top/Article/details/gtwdziouuc.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.chenzaomai.com/Article/details/gtkpxhxoxr.html

[T24] Swift：闭包
来源：http://dali.jlsjyb.cn/Article/details/gtcdrzmrmc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.316326.xyz/Article/details/gtjcvkgcbz.html

[T25] Swift：结构体
来源：http://dali.xuanzx.com/Article/details/gtnhgvczrn.html

struct P { var x: Int }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjjglcvbl.html

[T26] Swift：类与重写
来源：http://dali.jqgufenzy.top/Article/details/gtowpswpfd.html

class A: Base { override func f() {} }
来源：http://dali.zhongyouzk.top/Article/details/gtexevluem.html

[T27] Swift：错误处理
来源：http://dali.andypj.xyz/Article/details/gtvvwhljsv.html

do { try f() } catch { print(error) }
来源：http://dali.xuetiantiany.cn/Article/details/gtirtxiwbq.html

[T28] Swift：枚举
来源：http://dali.nwbrower.top/Article/details/gtlkdqleuj.html

enum Color { case red, green }
来源：http://dali.cucudq.cn/Article/details/gtfatfwykp.html

[T29] Swift：guard 提前返回
来源：http://dali.zhiwuduotai.top/Article/details/gtxhkbbucf.html

guard let x = opt else { return }
来源：http://dali.xinyue.icu/Article/details/gtcgjtssri.html

[T30] Swift：协议
来源：http://dali.jinqigfzy.top/Article/details/gtajmmqwww.html

protocol Shape { func area() -> Double }
来源：http://dali.yj20258.top/Article/details/gtxwdvevih.html

[T31] Lua：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtdgfzkdvx.html

print("Hello")
来源：http://dali.chenzaomai.com/Article/details/gtjmtlyeib.html

[T32] Lua：局部变量
来源：http://dali.jinqigufen.top/Article/details/gtgefuehhj.html

local a = 1
来源：http://dali.tianlin.xyz/Article/details/gtnffxmofo.html

[T33] Lua：表（数组）
来源：http://dali.yuanzhike.top/Article/details/gtekyhzalg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yuanzhike.top/Article/details/gtyscuxeir.html

[T34] Lua：遍历表
来源：http://dali.tanke756.top/Article/details/gtyvnocuql.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ivvv.top/Article/details/gtwsupglos.html

[T35] Lua：字典表
来源：http://dali.zhongyouzk.top/Article/details/gtvldbjizq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shangyingyoupin.top/Article/details/gtmmsmybff.html

[T36] Lua：函数
来源：http://dali.hysaishi.cn/Article/details/gturwktuzz.html

function add(a, b) return a + b end
来源：http://dali.cucudq.cn/Article/details/gtimhoytqj.html

[T37] Lua：字符串拼接
来源：http://dali.daria6918.cn/Article/details/gtaeezaoka.html

"a" .. "b"
来源：http://dali.guowangkeji.top/Article/details/gtqfanrujr.html

[T38] Lua：条件
来源：http://dali.fengsongda.top/Article/details/gtlljxisxh.html

if x > 0 then print("正") end
来源：http://dali.316326.xyz/Article/details/gtgbcpfrsq.html

[T39] Lua：模式匹配
来源：http://dali.ehwqpu.com/Article/details/gtdfhejqcq.html

string.find(s, "%d+")
来源：http://dali.tianlin.xyz/Article/details/gtrvkdgnto.html

[T40] Lua：元表
来源：http://dali.ydzc1.top/Article/details/gtybkanjnr.html

setmetatable({}, { __index = base })
来源：http://dali.zhixingplan.top/Article/details/gtilmhkbca.html

[T41] Perl：Hello World
来源：http://dali.gzhubu.top/Article/details/gtvkfkmkny.html

print "Hello\n";
来源：http://dali.ivvv.top/Article/details/gtvghistqa.html

[T42] Perl：变量类型
来源：http://dali.pengpengdd.cyou/Article/details/gtibzfacig.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cashguo.top/Article/details/gtiepspokl.html

[T43] Perl：字符串插值
来源：http://dali.zhoulong.xyz/Article/details/gtmywquayb.html

"值: $a"
来源：http://dali.zhoulong.xyz/Article/details/gtbzjuecvo.html

[T44] Perl：条件
来源：http://dali.bjfxy.top/Article/details/gtpyreqzaw.html

if ($a > 0) { print "正"; }
来源：http://dali.shuidangran.top/Article/details/gtxqpfjwia.html


<!-- 参考信息 -->