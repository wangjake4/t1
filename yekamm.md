代发 wailian999

cmd >/dev/null 2>&1
来源：http://dali.316326.xyz/Article/details/gthgfbpcyb.html

[R42] 输入重定向
来源：http://dali.yanxiufei.cn/Article/details/gtwqydnyle.html

wc -l < a.txt
来源：http://dali.fengsongda.top/Article/details/gtdiddfpwx.html

[R43] 按名字查找文件
来源：http://dali.yonumen.top/Article/details/gtvlzdvmkw.html

find . -name "*.log" -type f
来源：http://dali.jyoumei.cn/Article/details/gtxmpylhwd.html

[R44] 按修改时间查找
来源：http://dali.hfpthk.cn/Article/details/gtfrusxtuv.html

find . -mtime -7 -type f
来源：http://dali.jqgfzy.top/Article/details/gtbogkolwx.html

[R45] 批量删除
来源：http://dali.sysykeji.top/Article/details/gtlgyhiqbt.html

find . -name "*.tmp" -delete
来源：http://dali.gogol.net.cn/Article/details/gtyhdtnhxu.html

[R46] 递归替换文件内容
来源：http://dali.yuxming.cn/Article/details/gtedxdavwg.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ivvv.top/Article/details/gtsviqfcsi.html

[R47] sed 单行替换
来源：http://dali.aizwys.cn/Article/details/gttdzoxqpl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhengqikj.top/Article/details/gtshiczhsl.html

[R48] awk 取指定列
来源：http://dali.jinqigufen.top/Article/details/gtqmwtfirf.html

awk '{print $1, $3}' a.txt
来源：http://dali.andypj.xyz/Article/details/gtbiekepsp.html

[R49] awk 带条件
来源：http://dali.c1oappe.top/Article/details/gtqcktaxol.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.gzhubu.top/Article/details/gtdmypgddi.html

[R50] awk 求和
来源：http://dali.chenlongwang.top/Article/details/gtpxnilanx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.andypj.xyz/Article/details/gtqzpjunua.html

[R51] 排序去重取前几
来源：http://dali.9152youxi.cn/Article/details/gtkwoejbpt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhixingplan.top/Article/details/gtqkjicgal.html

[R52] 统计行数
来源：http://dali.shzxlz.cn/Article/details/gtnmflwkkq.html

wc -l a.txt
来源：http://dali.hnqzz.top/Article/details/gtooqkrmuu.html

[R53] 查看文件头与实时尾
来源：http://dali.jinghuilouyu.cn/Article/details/gthptegwbe.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cqqwz.cn/Article/details/gtiyxdadcf.html

[R54] 比较两个文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gttbabxdek.html

diff a.txt b.txt
来源：http://dali.havefunace.top/Article/details/gtlqprzbpd.html

[R55] 压缩与解压
来源：http://dali.hnqzz.top/Article/details/gtcyttbgbo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.mhx1999.top/Article/details/gtsgbdixzd.html

[R56] 远程拷贝
来源：http://dali.ppjwa.cn/Article/details/gtefcxckep.html

scp file user@host:/path/
来源：http://dali.yj20258888.top/Article/details/gtbrxhlywm.html

[R57] 远程执行命令
来源：http://dali.fengsongda.top/Article/details/gtxwwnwgcm.html

ssh user@host 'uptime'
来源：http://dali.zhixingplan.top/Article/details/gtqxahtnkf.html

[R58] 下载文件
来源：http://dali.xuetiantiany.cn/Article/details/gtfhuswoqb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xziqi.cn/Article/details/gtcvyxjsjn.html

[R59] 发 POST JSON
来源：http://dali.guowangkeji.top/Article/details/gtotcozjck.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.daria6918.cn/Article/details/gttajgzujo.html

[R60] 只看 HTTP 状态码
来源：http://dali.vqdsnc.cn/Article/details/gtlskgaayy.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.vqdsnc.cn/Article/details/gtfibpnzhk.html

[R61] 磁盘占用
来源：http://dali.yuxming.cn/Article/details/gtlyiyyhcn.html

df -h;  du -sh *
来源：http://dali.shzxlz.cn/Article/details/gtncrrrboq.html

[R62] 找最占空间的文件
来源：http://dali.ydzc1.top/Article/details/gtxkhzxaui.html

du -ah . | sort -rh | head -10
来源：http://dali.ppjwa.cn/Article/details/gtpthgycnh.html

[R63] 内存与进程
来源：http://dali.zhiwuduotai.top/Article/details/gtjopwutjg.html

free -h;  ps aux | grep nginx
来源：http://dali.hfpthk.cn/Article/details/gtoicfxdis.html

[R64] 结束进程
来源：http://dali.0kj1m.cn/Article/details/gtlihbngrk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jiagoushi.top/Article/details/gtthblnjvj.html

[R65] 查看端口占用
来源：http://dali.nanxuanxn.top/Article/details/gteourbsis.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.nanxinkj.top/Article/details/gtqwrscafj.html

[R66] 定时任务
来源：http://dali.pengpengdd.cyou/Article/details/gtrwlhhhgu.html

crontab -e;  crontab -l
来源：http://dali.ybcxt.top/Article/details/gtjkdtvwss.html

[R67] 生成随机十六进制串
来源：http://dali.zhongyouzk.top/Article/details/gtklxpwcke.html

openssl rand -hex 16
来源：http://dali.dashuyun.cn/Article/details/gtuoslosbc.html

[R68] 计算文件校验值
来源：http://dali.meibo888.top/Article/details/gtmcvqtxuh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.guowangkeji.top/Article/details/gtvqwwtcgl.html

[R69] 生成随机密码
来源：http://dali.pycfn.com/Article/details/gtshnctuxw.html

head -c 16 /dev/urandom | base64
来源：http://dali.quarkkingdee.top/Article/details/gtqjccmpzr.html

[R70] 时间戳与互转
来源：http://dali.gotoacloud.top/Article/details/gtdewxefdh.html

date +%s;  date -d @1700000000
来源：http://dali.chenjidiqi.icu/Article/details/gtmpwrefmz.html

[R71] 日期格式化
来源：http://dali.gogol.net.cn/Article/details/gtpueherdq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xuanzx.com/Article/details/gtpwuamdyq.html

[R72] 等待端口就绪
来源：http://dali.cqqwz.cn/Article/details/gtplxacvti.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jiagoushi.top/Article/details/gtgnivqgwg.html

[R73] 分割大日志
来源：http://dali.sweek.top/Article/details/gtmfbrekdw.html

split -l 1000 big.log part_
来源：http://dali.yanxiufei.cn/Article/details/gtbohjvupm.html

[R74] 批量重命名
来源：http://dali.zhengqikj.top/Article/details/gtgmhnvazo.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.chenlongwang.top/Article/details/gtfzcfergs.html

[R75] 导出环境变量
来源：http://dali.316326.xyz/Article/details/gthhrsmjuq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gotoacloud.top/Article/details/gtxftaraww.html

[R76] 使用临时文件
来源：http://dali.ybcxt.top/Article/details/gtrwpqeder.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.snrcjt.cn/Article/details/gttyyhzlgd.html

[R77] 读取用户输入
来源：http://dali.daxiang520.top/Article/details/gtrhrirjjr.html

read -rp "请输入: " ans
来源：http://dali.yvedp.cn/Article/details/gtyazwczvv.html

[R78] 交互式菜单
来源：http://dali.svipenyu.cn/Article/details/gtywvxkios.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sysykeji.top/Article/details/gtcxgcfktq.html

[R79] 解析命令行选项
来源：http://dali.ybcxt.top/Article/details/gtwzfdxlmf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.guowangkeji.top/Article/details/gttkcbiwkn.html

[R80] 查看脚本执行耗时
来源：http://dali.tianlin.xyz/Article/details/gtvkangbtu.html

time ./run.sh
来源：http://dali.quarkkingdee.top/Article/details/gtsogubzip.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtzrajzlem.html

S. C / C++ 专题
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfoowoigy.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtcnxfkfdn.html

[S01] C：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtjodnpcpd.html

#include <stdio.h>
来源：http://dali.yongpay.top/Article/details/gtdbrxxxhe.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.tianlin.xyz/Article/details/gtamnuuqfi.html

[S02] C：变量与格式化输出
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkxyyjjwj.html

int a = 10; printf("%d\n", a);
来源：http://dali.andypj.xyz/Article/details/gtufxntmzh.html

[S03] C：读入整数
来源：http://dali.pycfn.com/Article/details/gtsbvbvzif.html

int x; scanf("%d", &x);
来源：http://dali.zhengqikj.top/Article/details/gtjjmnmwnb.html

[S04] C：字符串复制
来源：http://dali.jinqigufen.top/Article/details/gtuxwrbzqr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.nanxinkj.top/Article/details/gtzmjxshdt.html

[S05] C：字符串长度
来源：http://dali.guannengcc.top/Article/details/gtkcqhrrmh.html

strlen(s)
来源：http://dali.9152youxi.cn/Article/details/gtdtrmcwkd.html

[S06] C：字符串比较
来源：http://dali.wangdashe.top/Article/details/gtbjqezhvo.html

strcmp(a, b) == 0
来源：http://dali.guannengcc.top/Article/details/gtllthsocw.html

[S07] C：数组遍历求和
来源：http://dali.quarkkingdee.top/Article/details/gtndqwmsvy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.wangdashe.top/Article/details/gtlqojbprc.html

[S08] C：动态内存分配与释放
来源：http://dali.cashguo.top/Article/details/gtbyijonmy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinghuilouyu.cn/Article/details/gthssrstcv.html

[S09] C：结构体定义与初始化
来源：http://dali.jianghu66.top/Article/details/gtjvhtvubb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jyoumei.cn/Article/details/gtyfahinho.html

[S10] C：指针与解引用
来源：http://dali.wangshuangyany.cn/Article/details/gtwzccyonl.html

int *p = &a;  *p = 5;
来源：http://dali.yvedp.cn/Article/details/gtukmowdyo.html

[S11] C：逐行读文件
来源：http://dali.sysykeji.top/Article/details/gthtiztvnx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hysaishi.cn/Article/details/gtjyvwkwgm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.smart0.xyz/Article/details/gtbgwunaam.html

fclose(f);
来源：http://dali.zhoulong.xyz/Article/details/gtpcdncjzh.html

[S12] C：写文件
来源：http://dali.tanke756.top/Article/details/gtqevgdpib.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.c1oappe.top/Article/details/gtcdeifvjv.html

[S13] C：宏定义
来源：http://dali.xuanzx.com/Article/details/gtjewlfqob.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jlsjyb.cn/Article/details/gtzthtcutt.html

[S14] C：枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdexohdcr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yonumen.top/Article/details/gtdgygojvz.html

[S15] C：类型转换
来源：http://dali.c1oappe.top/Article/details/gtgqbdqpdk.html

(double) a / b
来源：http://dali.smart0.xyz/Article/details/gtuymqyrne.html

[S16] C：位操作置位
来源：http://dali.jyoumei.cn/Article/details/gtzeimptko.html

x |= (1 << 3);
来源：http://dali.yonumen.top/Article/details/gtpjcxrabz.html

[S17] C：安全拼接字符串
来源：http://dali.mhx1999.top/Article/details/gtotgoswvb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.guowangkeji.top/Article/details/gtanfiyelo.html

[S18] C：命令行参数
来源：http://dali.yj20258888.top/Article/details/gtrdflejnl.html

int main(int argc, char **argv)
来源：http://dali.snrcjt.cn/Article/details/gtbhxjgjec.html

[S19] C：快速排序
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwinbctjr.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinqigfzy.top/Article/details/gtjotymsnv.html

[S20] C：二分查找
来源：http://dali.xuetiantiany.cn/Article/details/gtheobiydx.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gtfpvaszhv.html

[S21] C：字符类别判断
来源：http://dali.chenzaomai.com/Article/details/gthytkujgp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.aibaodan.cn/Article/details/gthvtyjdqj.html

[S22] C：字符串转数字
来源：http://dali.hnqzz.top/Article/details/gtlgczkfin.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jyoumei.cn/Article/details/gtnzyforbv.html

[S23] C：随机数
来源：http://dali.redwolf501.top/Article/details/gtgilpsmci.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hammf.cn/Article/details/gtjbvstotk.html

[S24] C：获取本地时间
来源：http://dali.hfpthk.cn/Article/details/gtsmpyofig.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hfpthk.cn/Article/details/gtseglkowy.html

[S25] C：内存拷贝
来源：http://dali.xuetiantiany.cn/Article/details/gtveasdfzl.html

memcpy(dst, src, n);
来源：http://dali.nwbrower.top/Article/details/gtegbxzdae.html

[S26] C：内存清零
来源：http://dali.hnqzz.top/Article/details/gtofoppvei.html

memset(a, 0, sizeof a);
来源：http://dali.jinqigufen.top/Article/details/gtsyjuntsw.html

[S27] C：定义常量
来源：http://dali.feifeiyinyue.top/Article/details/gtzvoedprq.html

const double PI = 3.14159;
来源：http://dali.shzxlz.cn/Article/details/gtpeoacwnh.html

[S28] C：静态变量
来源：http://dali.zhiwuduotai.top/Article/details/gtebmefopd.html

static int counter = 0;
来源：http://dali.pycfn.com/Article/details/gtuyzcbodn.html

[S29] C：变参函数
来源：http://dali.ybcxt.top/Article/details/gturndlwwu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.chenjidiqi.icu/Article/details/gtejpvncwr.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gtxvdcloqf.html

#ifndef X_H
来源：http://dali.pycfn.com/Article/details/gtvcnqwxuv.html

#define X_H
来源：http://dali.yongpay.top/Article/details/gtpczxwkho.html

#endif
来源：http://dali.yj20258888.top/Article/details/gtmeqjoowm.html

[S31] C++：Hello World
来源：http://dali.zhengqikj.top/Article/details/gtyilajyax.html

#include <iostream>
来源：http://dali.xziqi.cn/Article/details/gtxyixkuvi.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.redwolf501.top/Article/details/gthmqxwqcu.html

[S32] C++：字符串
来源：http://dali.hnxiangtu.top/Article/details/gthlkqicgn.html

std::string s = "hi";  s += "!";
来源：http://dali.cqqwz.cn/Article/details/gtoiutckjg.html

[S33] C++：vector 增删
来源：http://dali.jiagoushi.top/Article/details/gtgncmfvdq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.tanke756.top/Article/details/gtdkhuluhj.html

[S34] C++：遍历 vector
来源：http://dali.gaohongyu789.top/Article/details/gttzowthox.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.redwolf501.top/Article/details/gtuaniwwas.html

[S35] C++：map
来源：http://dali.xinyue.icu/Article/details/gtvqvafywr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tianlin.xyz/Article/details/gtvrvnfeqn.html

[S36] C++：unordered_map
来源：http://dali.zhoulong.xyz/Article/details/gtdaaghkhr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cheryme.top/Article/details/gtshqryifs.html

[S37] C++：set
来源：http://dali.dashuyun.cn/Article/details/gtsdxkqezx.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.kuanghao11.cn/Article/details/gtanggrdhj.html

[S38] C++：排序
来源：http://dali.andypj.xyz/Article/details/gtsumqmizy.html

std::sort(v.begin(), v.end());
来源：http://dali.gogol.net.cn/Article/details/gtjpkvwibi.html

[S39] C++：自定义比较器排序
来源：http://dali.yuanzhike.top/Article/details/gtmzlqexxa.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sxryk.cn/Article/details/gtppwiucux.html

[S40] C++：查找元素
来源：http://dali.cheryme.top/Article/details/gtrhoyfipe.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gotoacloud.top/Article/details/gtxhgvxnwi.html

[S41] C++：类与构造函数
来源：http://dali.hfpthk.cn/Article/details/gtfdyucpvj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.feifeiyinyue.top/Article/details/gtsntcgfcg.html

[S42] C++：继承与虚函数
来源：http://dali.yj20258.top/Article/details/gtnoptlsrd.html

class B : public Base { public: void f() override {} };
来源：http://dali.haohaochexian.top/Article/details/gtctkwapni.html

[S43] C++：智能指针
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxpnayobt.html

auto p = std::make_unique<int>(5);
来源：http://dali.yanxiufei.cn/Article/details/gthiovrkws.html

[S44] C++：引用传参
来源：http://dali.jyoumei.cn/Article/details/gtzsfczjsp.html

void inc(int &x) { ++x; }
来源：http://dali.tianlin.xyz/Article/details/gtpwdkqers.html

[S45] C++：lambda
来源：http://dali.quarkkingdee.top/Article/details/gtqzrjmqdn.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cucudq.cn/Article/details/gtxccvqedr.html

[S46] C++：函数模板
来源：http://dali.zdqjudy.top/Article/details/gtvukppxxu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.dianchejie.cn/Article/details/gtovgjpddx.html

[S47] C++：结构化绑定遍历
来源：http://dali.jqgfzy.top/Article/details/gteumlmgww.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jinqigfzy.top/Article/details/gtreuoundl.html

[S48] C++：逐行读文件
来源：http://dali.yongpay.top/Article/details/gtdbknlhle.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jinqigufen.top/Article/details/gtsnrhgpql.html

while (std::getline(in, line)) { }
来源：http://dali.0kj1m.cn/Article/details/gtszmyzfip.html

[S49] C++：写文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzyutntev.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ehwqpu.com/Article/details/gtmwlvvqhi.html

[S50] C++：格式化数字
来源：http://dali.jqgfzy.top/Article/details/gtbvhjcvcc.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yvedp.cn/Article/details/gtymvjiwqv.html

[S51] C++：显式类型转换
来源：http://dali.cashguo.top/Article/details/gtwusoovis.html

static_cast<double>(a) / b
来源：http://dali.shanyushiyangtech.top/Article/details/gtwidxeftk.html

[S52] C++：const 与 noexcept
来源：http://dali.0kj1m.cn/Article/details/gtdxripkze.html

int size() const noexcept { return n_; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtppwuzuvo.html

[S53] C++：移动语义
来源：http://dali.nwbrower.top/Article/details/gtbwndetyf.html

std::vector<int> w = std::move(v);
来源：http://dali.snrcjt.cn/Article/details/gtrsisgacp.html

[S54] C++：异常处理
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxksdrnqz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sweek.top/Article/details/gtxazhrisl.html

[S55] C++：结构化绑定
来源：http://dali.chenzaomai.com/Article/details/gtiiezdugj.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gzhubu.top/Article/details/gtwaqwnlwl.html

[S56] C++：optional
来源：http://dali.hongshengwenyu.top/Article/details/gtrbtutjrj.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ppjwa.cn/Article/details/gtsgfniryr.html

[S57] C++：编译期常量
来源：http://dali.sufxvd.cn/Article/details/gtszzvvmpv.html

constexpr int N = 10;
来源：http://dali.yanxiufei.cn/Article/details/gtppflkpou.html

[S58] C++：命名空间
来源：http://dali.c1oappe.top/Article/details/gtrrynapoh.html

namespace ns { int f() { return 1; } }
来源：http://dali.yj202588.top/Article/details/gttmxqkhkx.html

[S59] C++：静态断言
来源：http://dali.fzhhl.top/Article/details/gtpvdhrksu.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yanxiufei.cn/Article/details/gtvfeiewki.html

[S60] C++：遍历并删除元素
来源：http://dali.iojbl.cn/Article/details/gtwykybnej.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sufxvd.cn/Article/details/gtxbnzpuhj.html

================================================================================
来源：http://dali.shuidangran.top/Article/details/gtgenwcqtb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.tian-w.cn/Article/details/gtjypvwlds.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtgvpxzrpq.html

[T01] Kotlin：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtydzhsfbv.html

println("Hello")
来源：http://dali.hysaishi.cn/Article/details/gtijqlnaqs.html

[T02] Kotlin：变量
来源：http://dali.jinqigfzy.top/Article/details/gtkmkslzxz.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.nanxuanxn.top/Article/details/gtsxttzgxo.html

[T03] Kotlin：字符串模板
来源：http://dali.zhixingplan.top/Article/details/gtumyrfkzl.html

"值: $b"
来源：http://dali.dashuyun.cn/Article/details/gtgyvnuqtm.html

[T04] Kotlin：空安全
来源：http://dali.guannengcc.top/Article/details/gtzrywooow.html

val n: String? = null;  n?.length
来源：http://dali.jqgfzy.top/Article/details/gtegwugnzz.html

[T05] Kotlin：when 表达式
来源：http://dali.zhixingplan.top/Article/details/gteyubwnak.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinghuilouyu.cn/Article/details/gtbwmwcopv.html

[T06] Kotlin：集合映射
来源：http://dali.vqdsnc.cn/Article/details/gtgsnzbybu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.yanxiufei.cn/Article/details/gtjquuwkjy.html

[T07] Kotlin：集合过滤
来源：http://dali.wangdashe.top/Article/details/gtthhbyhro.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.chenjidiqi.icu/Article/details/gtwjcnymmi.html

[T08] Kotlin：数据类
来源：http://dali.dianchejie.cn/Article/details/gtrafwwycn.html

data class User(val name: String, val age: Int)
来源：http://dali.cheryme.top/Article/details/gtzeaygxhc.html

[T09] Kotlin：扩展函数
来源：http://dali.dashuyun.cn/Article/details/gtuwzzpsee.html

fun String.exclaim() = this + "!"
来源：http://dali.birdmap.top/Article/details/gtlpfamios.html

[T10] Kotlin：默认参数
来源：http://dali.yonumen.top/Article/details/gtdlhkotmk.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hongshengwenyu.top/Article/details/gtwpnamhyl.html

[T11] Kotlin：协程
来源：http://dali.quarkkingdee.top/Article/details/gtmyhqszgr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.vqdsnc.cn/Article/details/gtnaserxbe.html

[T12] Kotlin：解构声明
来源：http://dali.haohaochexian.top/Article/details/gtfgjhkwkq.html

val (a, b) = Pair(1, 2)
来源：http://dali.xziqi.cn/Article/details/gtzsdmrpmn.html

[T13] Kotlin：只读 Map
来源：http://dali.shanyushiyangtech.top/Article/details/gtcvohcdwv.html

val m = mapOf("a" to 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkuejoshu.html

[T14] Kotlin：循环
来源：http://dali.ppjwa.cn/Article/details/gtdsbbzopk.html

for (i in 1..10) println(i)
来源：http://dali.yangfankeji.com/Article/details/gtwqburael.html

[T15] Kotlin：接口
来源：http://dali.jianghu66.top/Article/details/gtgfbtvuhu.html

interface Shape { fun area(): Double }
来源：http://dali.jqgfzy.top/Article/details/gtdcrnkrub.html

[T16] Swift：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtbggspmmg.html

print("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gtuqpenkbs.html

[T17] Swift：变量与常量
来源：http://dali.tanke756.top/Article/details/gtcylcalya.html

var a = 1;  let b = 2
来源：http://dali.zycfv.cn/Article/details/gttormfpql.html

[T18] Swift：字符串插值
来源：http://dali.jlsjyb.cn/Article/details/gtfwptkfzq.html

"值: \(b)"
来源：http://dali.hnxiangtu.top/Article/details/gtjdherine.html

[T19] Swift：可选绑定
来源：http://dali.jianghu66.top/Article/details/gtqiwnrtxi.html

if let n = opt { print(n) }
来源：http://dali.vqdsnc.cn/Article/details/gtfvjuiosi.html

[T20] Swift：数组操作
来源：http://dali.nwbrower.top/Article/details/gtheokyzhn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhiwuduotai.top/Article/details/gtwpmbdndx.html

[T21] Swift：遍历
来源：http://dali.zhengqikj.top/Article/details/gthjuklwkx.html

for x in a { print(x) }
来源：http://dali.xylfe.cn/Article/details/gtpojxaqvj.html

[T22] Swift：字典
来源：http://dali.feifeiyinyue.top/Article/details/gtfnxvyuws.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.nwbrower.top/Article/details/gtbepfyxfe.html

[T23] Swift：函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwrmkfgdx.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhixingplan.top/Article/details/gttkicpwvk.html

[T24] Swift：闭包
来源：http://dali.hnqzz.top/Article/details/gtoxpjqztw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.svipenyu.cn/Article/details/gtfwzodumu.html

[T25] Swift：结构体
来源：http://dali.daxiang520.top/Article/details/gtelyayfxs.html

struct P { var x: Int }
来源：http://dali.9152youxi.cn/Article/details/gtmpgdvlwo.html

[T26] Swift：类与重写
来源：http://dali.9152youxi.cn/Article/details/gtwztrcplx.html

class A: Base { override func f() {} }
来源：http://dali.fengsongda.top/Article/details/gtvvpumfdo.html

[T27] Swift：错误处理
来源：http://dali.pycfn.com/Article/details/gtelpzbtah.html

do { try f() } catch { print(error) }
来源：http://dali.jqgfzy.top/Article/details/gtrhtrcvhe.html

[T28] Swift：枚举
来源：http://dali.guannengcc.top/Article/details/gtxcwpkdmd.html

enum Color { case red, green }
来源：http://dali.birdmap.top/Article/details/gtwjuqrnib.html

[T29] Swift：guard 提前返回
来源：http://dali.tianlin.xyz/Article/details/gtgbyfofqz.html

guard let x = opt else { return }
来源：http://dali.wangshuangyany.cn/Article/details/gtzqjmoheb.html

[T30] Swift：协议
来源：http://dali.tanke756.top/Article/details/gtxptcmzyz.html

protocol Shape { func area() -> Double }
来源：http://dali.pycfn.com/Article/details/gthqdlbcvk.html

[T31] Lua：Hello World
来源：http://dali.aizwys.cn/Article/details/gtpnbeooqy.html

print("Hello")
来源：http://dali.yvedp.cn/Article/details/gtfvqbfmdb.html

[T32] Lua：局部变量
来源：http://dali.xuetiantiany.cn/Article/details/gtrnlulqvl.html

local a = 1
来源：http://dali.havefunace.top/Article/details/gtptzlilug.html

[T33] Lua：表（数组）
来源：http://dali.ppjwa.cn/Article/details/gtkdksyucg.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.shanyushiyangtech.top/Article/details/gthqxcwhnh.html

[T34] Lua：遍历表
来源：http://dali.sufxvd.cn/Article/details/gtudqvczsz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbktytaml.html

[T35] Lua：字典表
来源：http://dali.yonumen.top/Article/details/gtrpxhylhk.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yuanzhike.top/Article/details/gtfqdahrex.html

[T36] Lua：函数
来源：http://dali.ehwqpu.com/Article/details/gtjtbxuecs.html

function add(a, b) return a + b end
来源：http://dali.chenlongwang.top/Article/details/gtgxolkgro.html

[T37] Lua：字符串拼接
来源：http://dali.zhongyouzk.top/Article/details/gtsfuyjdxy.html

"a" .. "b"
来源：http://dali.zhiwuduotai.top/Article/details/gtbhkjunzl.html

[T38] Lua：条件
来源：http://dali.9152youxi.cn/Article/details/gtubxawmxy.html

if x > 0 then print("正") end
来源：http://dali.0kj1m.cn/Article/details/gtbyscnlxa.html

[T39] Lua：模式匹配
来源：http://dali.jqgufenzy.top/Article/details/gtkzvdxmfi.html

string.find(s, "%d+")
来源：http://dali.jqgfzy.top/Article/details/gttwxslrrl.html

[T40] Lua：元表
来源：http://dali.zhiwuduotai.top/Article/details/gtxgcoznfc.html

setmetatable({}, { __index = base })
来源：http://dali.havefunace.top/Article/details/gtkhupqahj.html

[T41] Perl：Hello World
来源：http://dali.shanyushiyangtech.top/Article/details/gtuuxkmboh.html

print "Hello\n";
来源：http://dali.jqgufenzy.top/Article/details/gtwlnwjvog.html

[T42] Perl：变量类型
来源：http://dali.cdnleiting.top/Article/details/gtehprefmk.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.ehwqpu.com/Article/details/gtjaxjwoaw.html

[T43] Perl：字符串插值
来源：http://dali.hongshengwenyu.top/Article/details/gtbspliftt.html

"值: $a"
来源：http://dali.yanxiufei.cn/Article/details/gtnpoirymv.html

[T44] Perl：条件
来源：http://dali.sxryk.cn/Article/details/gtzsiccpqf.html

if ($a > 0) { print "正"; }
来源：http://dali.jyoumei.cn/Article/details/gtxeyenqcx.html


<!-- 参考信息 -->