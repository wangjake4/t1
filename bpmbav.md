代发 wailian999

files=$(ls -1)
来源：http://dali.nanxuanxn.top/Article/details/gtgppmvccu.html

[R38] 管道串联
来源：http://dali.cdnleiting.top/Article/details/gtgfuohrod.html

cat a.txt | grep -i error | wc -l
来源：http://dali.tian-w.cn/Article/details/gtedcewfuj.html

[R39] 重定向标准输出与错误
来源：http://dali.tanke756.top/Article/details/gtppqgkqzm.html

cmd > out.log 2>&1
来源：http://dali.jinqigufen.top/Article/details/gteoyylsvs.html

[R40] 追加写日志
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjjohpbca.html

echo "log" >> out.log
来源：http://dali.feifeiyinyue.top/Article/details/gtsrjjiccl.html

[R41] 丢弃输出
来源：http://dali.ivvv.top/Article/details/gtqocgqfhz.html

cmd >/dev/null 2>&1
来源：http://dali.haohaochexian.top/Article/details/gtalfikvjp.html

[R42] 输入重定向
来源：http://dali.xuanzx.com/Article/details/gtmiqyxtid.html

wc -l < a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjweclgqe.html

[R43] 按名字查找文件
来源：http://dali.meibo888.top/Article/details/gtpfwynvby.html

find . -name "*.log" -type f
来源：http://dali.0kj1m.cn/Article/details/gttjdwvjyi.html

[R44] 按修改时间查找
来源：http://dali.shangyingyoupin.top/Article/details/gtgfwapsry.html

find . -mtime -7 -type f
来源：http://dali.chenzaomai.com/Article/details/gtwhxmkjyz.html

[R45] 批量删除
来源：http://dali.kuanghao11.cn/Article/details/gtltyntqul.html

find . -name "*.tmp" -delete
来源：http://dali.guowangkeji.top/Article/details/gtoyfayndp.html

[R46] 递归替换文件内容
来源：http://dali.snrcjt.cn/Article/details/gtpkqswppo.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinqigfzy.top/Article/details/gtojlsviyz.html

[R47] sed 单行替换
来源：http://dali.xuetiantiany.cn/Article/details/gtoicaelfv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hammf.cn/Article/details/gttdwgeopk.html

[R48] awk 取指定列
来源：http://dali.xinyue.icu/Article/details/gtnoknhhct.html

awk '{print $1, $3}' a.txt
来源：http://dali.gotoacloud.top/Article/details/gtfakuylun.html

[R49] awk 带条件
来源：http://dali.shanyushiyangtech.top/Article/details/gtdplxchol.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sysykeji.top/Article/details/gthjmqylik.html

[R50] awk 求和
来源：http://dali.nwbrower.top/Article/details/gtymjptvwv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gotoacloud.top/Article/details/gtqzsjgafs.html

[R51] 排序去重取前几
来源：http://dali.havefunace.top/Article/details/gtlewzoxku.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.tian-w.cn/Article/details/gtkoghpgqo.html

[R52] 统计行数
来源：http://dali.tian-w.cn/Article/details/gtqfgcsvcc.html

wc -l a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpwbsflrw.html

[R53] 查看文件头与实时尾
来源：http://dali.nwbrower.top/Article/details/gtkdjfocfg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tian-w.cn/Article/details/gtvqmsecma.html

[R54] 比较两个文件
来源：http://dali.nanxinkj.top/Article/details/gtivbdmsyq.html

diff a.txt b.txt
来源：http://dali.xinyue.icu/Article/details/gtosvfcieh.html

[R55] 压缩与解压
来源：http://dali.xylfe.cn/Article/details/gtgtvwckkj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yanxiufei.cn/Article/details/gtspvgruqd.html

[R56] 远程拷贝
来源：http://dali.sxryk.cn/Article/details/gtfbmivtfq.html

scp file user@host:/path/
来源：http://dali.sweek.top/Article/details/gtncmddthx.html

[R57] 远程执行命令
来源：http://dali.iojbl.cn/Article/details/gtkqdnjseo.html

ssh user@host 'uptime'
来源：http://dali.nanxuanxn.top/Article/details/gtnwlbznss.html

[R58] 下载文件
来源：http://dali.dianchejie.cn/Article/details/gtcwvgeqks.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.iojbl.cn/Article/details/gtucbfbfhc.html

[R59] 发 POST JSON
来源：http://dali.jqgfzy.top/Article/details/gtnsbocnxe.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sysykeji.top/Article/details/gtotlpgynn.html

[R60] 只看 HTTP 状态码
来源：http://dali.iojbl.cn/Article/details/gtwdxrruok.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.aizwys.cn/Article/details/gtwdjzrpte.html

[R61] 磁盘占用
来源：http://dali.ydzc1.top/Article/details/gtzbilbctj.html

df -h;  du -sh *
来源：http://dali.shangyingyoupin.top/Article/details/gtspmdhxac.html

[R62] 找最占空间的文件
来源：http://dali.jlsjyb.cn/Article/details/gtmdanximq.html

du -ah . | sort -rh | head -10
来源：http://dali.pengpengdd.cyou/Article/details/gtjettiynt.html

[R63] 内存与进程
来源：http://dali.gogol.net.cn/Article/details/gtizycnrog.html

free -h;  ps aux | grep nginx
来源：http://dali.chenzaomai.com/Article/details/gtvitzmsvi.html

[R64] 结束进程
来源：http://dali.yvedp.cn/Article/details/gtvcqvlbkh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zycfv.cn/Article/details/gthgggncum.html

[R65] 查看端口占用
来源：http://dali.9152youxi.cn/Article/details/gtindqyumw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.pycfn.com/Article/details/gttzvngoci.html

[R66] 定时任务
来源：http://dali.shzxlz.cn/Article/details/gtlqhwuloz.html

crontab -e;  crontab -l
来源：http://dali.gotoacloud.top/Article/details/gtlomyhtzq.html

[R67] 生成随机十六进制串
来源：http://dali.wangshuangyany.cn/Article/details/gtldysyngr.html

openssl rand -hex 16
来源：http://dali.tanke756.top/Article/details/gtrwzbyrgy.html

[R68] 计算文件校验值
来源：http://dali.xylfe.cn/Article/details/gthrnozncs.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hywenlv.cn/Article/details/gtuumecbnj.html

[R69] 生成随机密码
来源：http://dali.wangshuangyany.cn/Article/details/gtqjddgrmo.html

head -c 16 /dev/urandom | base64
来源：http://dali.iojbl.cn/Article/details/gtbqgijzti.html

[R70] 时间戳与互转
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvnrilwyn.html

date +%s;  date -d @1700000000
来源：http://dali.hnqzz.top/Article/details/gtxnufvxuv.html

[R71] 日期格式化
来源：http://dali.iojbl.cn/Article/details/gtvbrynvvg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yangfankeji.com/Article/details/gtpxlhughy.html

[R72] 等待端口就绪
来源：http://dali.zhoulong.xyz/Article/details/gtgwgtfqkc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jqgfzy.top/Article/details/gtvkkuenvu.html

[R73] 分割大日志
来源：http://dali.bjfxy.top/Article/details/gtxosparld.html

split -l 1000 big.log part_
来源：http://dali.hywenlv.cn/Article/details/gtzmkmtoaz.html

[R74] 批量重命名
来源：http://dali.pycfn.com/Article/details/gthxyxteca.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sysykeji.top/Article/details/gtmhgfwtyy.html

[R75] 导出环境变量
来源：http://dali.jiagoushi.top/Article/details/gtmogmfnrn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yueranfly.top/Article/details/gtumarqwsv.html

[R76] 使用临时文件
来源：http://dali.guowangkeji.top/Article/details/gttchpkyox.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yongpay.top/Article/details/gtzjvbtqhr.html

[R77] 读取用户输入
来源：http://dali.jinqigufen.top/Article/details/gttyxphpjs.html

read -rp "请输入: " ans
来源：http://dali.zhixingplan.top/Article/details/gtqflogbrv.html

[R78] 交互式菜单
来源：http://dali.wangshuangyany.cn/Article/details/gtcajkacxb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.dashuyun.cn/Article/details/gtycqkxjuf.html

[R79] 解析命令行选项
来源：http://dali.zhiwuduotai.top/Article/details/gtmpqfojtv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gzhubu.top/Article/details/gtogdyrhol.html

[R80] 查看脚本执行耗时
来源：http://dali.hfpthk.cn/Article/details/gtznplratw.html

time ./run.sh
来源：http://dali.zhengqikj.top/Article/details/gtzkcgnqbw.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtklnocork.html

S. C / C++ 专题
来源：http://dali.hongshengwenyu.top/Article/details/gtmygfoxjq.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtergqhtyu.html

[S01] C：Hello World
来源：http://dali.dianchejie.cn/Article/details/gtawalxwld.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gtuowztvrm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.ivvv.top/Article/details/gtjytkxedp.html

[S02] C：变量与格式化输出
来源：http://dali.yongpay.top/Article/details/gthkmoyjyl.html

int a = 10; printf("%d\n", a);
来源：http://dali.gaohongyu789.top/Article/details/gtvjvyvscl.html

[S03] C：读入整数
来源：http://dali.ydzc1.top/Article/details/gtcomjdzjg.html

int x; scanf("%d", &x);
来源：http://dali.zhongyouzk.top/Article/details/gtyrntggmn.html

[S04] C：字符串复制
来源：http://dali.tanke756.top/Article/details/gtchiuertk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.9152youxi.cn/Article/details/gtjyssavmm.html

[S05] C：字符串长度
来源：http://dali.hfpthk.cn/Article/details/gtpnjswspa.html

strlen(s)
来源：http://dali.ivvv.top/Article/details/gthfwjdgfc.html

[S06] C：字符串比较
来源：http://dali.smart0.xyz/Article/details/gtpjmurihk.html

strcmp(a, b) == 0
来源：http://dali.nwbrower.top/Article/details/gtjxkzinwu.html

[S07] C：数组遍历求和
来源：http://dali.cqqwz.cn/Article/details/gtqhpjihze.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hongshengwenyu.top/Article/details/gtgojmfvig.html

[S08] C：动态内存分配与释放
来源：http://dali.chenzaomai.com/Article/details/gtlboqerse.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yuxming.cn/Article/details/gtucmoatrr.html

[S09] C：结构体定义与初始化
来源：http://dali.nanxuanxn.top/Article/details/gtwyvolyet.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhoulong.xyz/Article/details/gtpsrrsljs.html

[S10] C：指针与解引用
来源：http://dali.xziqi.cn/Article/details/gtmovmdtqi.html

int *p = &a;  *p = 5;
来源：http://dali.mhx1999.top/Article/details/gtjcudwwfg.html

[S11] C：逐行读文件
来源：http://dali.guannengcc.top/Article/details/gtyyuspize.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zdqjudy.top/Article/details/gtciroynbp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.tian-w.cn/Article/details/gtweifugni.html

fclose(f);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtiktpvkdn.html

[S12] C：写文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxswnznqk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhixingplan.top/Article/details/gtgfzsjhav.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gtiyifvbkx.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinghuilouyu.cn/Article/details/gtxiedmdrc.html

[S14] C：枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxxgvqsqg.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.feifeiyinyue.top/Article/details/gtybqovrqi.html

[S15] C：类型转换
来源：http://dali.zdqjudy.top/Article/details/gtvadjlqyh.html

(double) a / b
来源：http://dali.yj20258.top/Article/details/gtbpkfefdr.html

[S16] C：位操作置位
来源：http://dali.shzxlz.cn/Article/details/gtdeuavuel.html

x |= (1 << 3);
来源：http://dali.chenlongwang.top/Article/details/gtwxxehmef.html

[S17] C：安全拼接字符串
来源：http://dali.yuxming.cn/Article/details/gtjaikcukc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yueranfly.top/Article/details/gtmcjjuunt.html

[S18] C：命令行参数
来源：http://dali.fzhhl.top/Article/details/gtwlcryifz.html

int main(int argc, char **argv)
来源：http://dali.shzxlz.cn/Article/details/gtaypmvkjj.html

[S19] C：快速排序
来源：http://dali.pengpengdd.cyou/Article/details/gtvekhfryo.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xuanzx.com/Article/details/gtdxwvdbir.html

[S20] C：二分查找
来源：http://dali.jinqigfzy.top/Article/details/gtergdfqqq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yangfankeji.com/Article/details/gtxeoiflzp.html

[S21] C：字符类别判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvhcgvpud.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sysykeji.top/Article/details/gtmbcblade.html

[S22] C：字符串转数字
来源：http://dali.jiagoushi.top/Article/details/gtoobmjmmk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ydzc1.top/Article/details/gthstjnofz.html

[S23] C：随机数
来源：http://dali.pycfn.com/Article/details/gtbnydhmxu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhongyouzk.top/Article/details/gtdfwsgyvj.html

[S24] C：获取本地时间
来源：http://dali.ehwqpu.com/Article/details/gtudqzvfvc.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ehwqpu.com/Article/details/gtktdxhbfp.html

[S25] C：内存拷贝
来源：http://dali.zycfv.cn/Article/details/gtoxsgfyrh.html

memcpy(dst, src, n);
来源：http://dali.nanxuanxn.top/Article/details/gtvktieqnp.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gtkmulfhpc.html

memset(a, 0, sizeof a);
来源：http://dali.andypj.xyz/Article/details/gtnucfdzai.html

[S27] C：定义常量
来源：http://dali.iojbl.cn/Article/details/gtcbnkxzqh.html

const double PI = 3.14159;
来源：http://dali.mhx1999.top/Article/details/gtlhqkbkou.html

[S28] C：静态变量
来源：http://dali.jinqigfzy.top/Article/details/gtsamanhaf.html

static int counter = 0;
来源：http://dali.sweek.top/Article/details/gtsewcdncz.html

[S29] C：变参函数
来源：http://dali.hammf.cn/Article/details/gtsermgavx.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.guowangkeji.top/Article/details/gtmjmuqjoy.html

[S30] C：头文件保护
来源：http://dali.tianlin.xyz/Article/details/gtyyvnziok.html

#ifndef X_H
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzeoigtog.html

#define X_H
来源：http://dali.dashuyun.cn/Article/details/gtnwkzfagk.html

#endif
来源：http://dali.guowangkeji.top/Article/details/gtrzuibvrc.html

[S31] C++：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtvqngxyrr.html

#include <iostream>
来源：http://dali.shangyingyoupin.top/Article/details/gtusfpmnkr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.guannengcc.top/Article/details/gtrvkobvij.html

[S32] C++：字符串
来源：http://dali.xuanzx.com/Article/details/gtubaxsjoe.html

std::string s = "hi";  s += "!";
来源：http://dali.yongpay.top/Article/details/gtlppdaour.html

[S33] C++：vector 增删
来源：http://dali.andypj.xyz/Article/details/gtlqevvbgc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.havefunace.top/Article/details/gtpkpzetau.html

[S34] C++：遍历 vector
来源：http://dali.chenjidiqi.icu/Article/details/gtwcjghjjb.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtraawrdyy.html

[S35] C++：map
来源：http://dali.dianchejie.cn/Article/details/gtzxkdtuyb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zdqjudy.top/Article/details/gtwdsktzze.html

[S36] C++：unordered_map
来源：http://dali.nwbrower.top/Article/details/gtondtinrv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtwarydarv.html

[S37] C++：set
来源：http://dali.gotoacloud.top/Article/details/gtgvnsfglw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhengqikj.top/Article/details/gtqpjdemxo.html

[S38] C++：排序
来源：http://dali.daria6918.cn/Article/details/gtykshjtrr.html

std::sort(v.begin(), v.end());
来源：http://dali.jinqigfzy.top/Article/details/gtttrdjwox.html

[S39] C++：自定义比较器排序
来源：http://dali.wangdashe.top/Article/details/gtufrprtas.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yvedp.cn/Article/details/gtkkhqtctd.html

[S40] C++：查找元素
来源：http://dali.yuxming.cn/Article/details/gteksoktqi.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.meibo888.top/Article/details/gtyvfkckav.html

[S41] C++：类与构造函数
来源：http://dali.shanyushiyangtech.top/Article/details/gtyhpfixjl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xylfe.cn/Article/details/gtlwapptqn.html

[S42] C++：继承与虚函数
来源：http://dali.kuanghao11.cn/Article/details/gtszfxulte.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhengqikj.top/Article/details/gtwvddwwit.html

[S43] C++：智能指针
来源：http://dali.zhiwuduotai.top/Article/details/gtrkxvmhrv.html

auto p = std::make_unique<int>(5);
来源：http://dali.yanxiufei.cn/Article/details/gtoyehijdh.html

[S44] C++：引用传参
来源：http://dali.quarkkingdee.top/Article/details/gtwkytqqgh.html

void inc(int &x) { ++x; }
来源：http://dali.shuidangran.top/Article/details/gtqwunkbeb.html

[S45] C++：lambda
来源：http://dali.fengsongda.top/Article/details/gtkxfqqfru.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.wangdashe.top/Article/details/gtrbgwccrr.html

[S46] C++：函数模板
来源：http://dali.yonumen.top/Article/details/gtyommgshh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.iojbl.cn/Article/details/gtqhzsmbvw.html

[S47] C++：结构化绑定遍历
来源：http://dali.chenzaomai.com/Article/details/gtjjaeutkp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.daxiang520.top/Article/details/gthfxbprzg.html

[S48] C++：逐行读文件
来源：http://dali.zdqjudy.top/Article/details/gtvojmnfko.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gaohongyu789.top/Article/details/gtjtdieolb.html

while (std::getline(in, line)) { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdhptyhta.html

[S49] C++：写文件
来源：http://dali.nanxinkj.top/Article/details/gtkcaoyevd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zycfv.cn/Article/details/gtbkvqmwua.html

[S50] C++：格式化数字
来源：http://dali.yongpay.top/Article/details/gthyjaoohi.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ybcxt.top/Article/details/gtrfumgjif.html

[S51] C++：显式类型转换
来源：http://dali.vqdsnc.cn/Article/details/gtkwzdbjte.html

static_cast<double>(a) / b
来源：http://dali.yj202588.top/Article/details/gtkppfcbbf.html

[S52] C++：const 与 noexcept
来源：http://dali.jiagoushi.top/Article/details/gtffwjardc.html

int size() const noexcept { return n_; }
来源：http://dali.jinghuilouyu.cn/Article/details/gthfguvtlo.html

[S53] C++：移动语义
来源：http://dali.jyoumei.cn/Article/details/gthgkjicjw.html

std::vector<int> w = std::move(v);
来源：http://dali.hnqzz.top/Article/details/gthiemnmgp.html

[S54] C++：异常处理
来源：http://dali.sufxvd.cn/Article/details/gtszjrdget.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sweek.top/Article/details/gtkpqqhfyc.html

[S55] C++：结构化绑定
来源：http://dali.pengpengdd.cyou/Article/details/gtobijrrmw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hysaishi.cn/Article/details/gtlroundra.html

[S56] C++：optional
来源：http://dali.zhongyouzk.top/Article/details/gtfvilglmg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.cheryme.top/Article/details/gtxdcjstdx.html

[S57] C++：编译期常量
来源：http://dali.jinqigufen.top/Article/details/gtybvztlca.html

constexpr int N = 10;
来源：http://dali.sysykeji.top/Article/details/gtmqvwbmxt.html

[S58] C++：命名空间
来源：http://dali.cqqwz.cn/Article/details/gtocpuwdho.html

namespace ns { int f() { return 1; } }
来源：http://dali.ehwqpu.com/Article/details/gttnnfetqf.html

[S59] C++：静态断言
来源：http://dali.feifeiyinyue.top/Article/details/gtoelqbulj.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sweek.top/Article/details/gtrlwahfnc.html

[S60] C++：遍历并删除元素
来源：http://dali.ydzc1.top/Article/details/gtexkbggzw.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.sweek.top/Article/details/gtpvndeozd.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtuipphwxc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.birdmap.top/Article/details/gtpugzjhqa.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtuqjgmpsu.html

[T01] Kotlin：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtaggrabtc.html

println("Hello")
来源：http://dali.zdqjudy.top/Article/details/gtvghsqbjb.html

[T02] Kotlin：变量
来源：http://dali.yangfankeji.com/Article/details/gtlmclvjyg.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jyoumei.cn/Article/details/gtpwvfnnai.html

[T03] Kotlin：字符串模板
来源：http://dali.jianghu66.top/Article/details/gtzjqslzfj.html

"值: $b"
来源：http://dali.kuanghao11.cn/Article/details/gtwrfeulnr.html

[T04] Kotlin：空安全
来源：http://dali.yueranfly.top/Article/details/gtgxhcgotv.html

val n: String? = null;  n?.length
来源：http://dali.feifeiyinyue.top/Article/details/gtlnvatefh.html

[T05] Kotlin：when 表达式
来源：http://dali.0kj1m.cn/Article/details/gttqojluoo.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jiagoushi.top/Article/details/gtuxwlftas.html

[T06] Kotlin：集合映射
来源：http://dali.hywenlv.cn/Article/details/gtqqovnurb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.sweek.top/Article/details/gtpxkoxtcb.html

[T07] Kotlin：集合过滤
来源：http://dali.aibaodan.cn/Article/details/gtihlbuwxd.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.nanxuanxn.top/Article/details/gtlicigofr.html

[T08] Kotlin：数据类
来源：http://dali.jinghuilouyu.cn/Article/details/gtftcvqklm.html

data class User(val name: String, val age: Int)
来源：http://dali.jinghuilouyu.cn/Article/details/gtcrwhighy.html

[T09] Kotlin：扩展函数
来源：http://dali.quarkkingdee.top/Article/details/gtblazumxs.html

fun String.exclaim() = this + "!"
来源：http://dali.yvedp.cn/Article/details/gtudmzfvid.html

[T10] Kotlin：默认参数
来源：http://dali.yanxiufei.cn/Article/details/gtzizbrjeo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.ppjwa.cn/Article/details/gtizejlrps.html

[T11] Kotlin：协程
来源：http://dali.hnxiangtu.top/Article/details/gtnoyunatq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ydzc1.top/Article/details/gtlfomqzgj.html

[T12] Kotlin：解构声明
来源：http://dali.wangdashe.top/Article/details/gtvpewpcqx.html

val (a, b) = Pair(1, 2)
来源：http://dali.ydzc1.top/Article/details/gtiidtvvsj.html

[T13] Kotlin：只读 Map
来源：http://dali.zdqjudy.top/Article/details/gtqqddkkcz.html

val m = mapOf("a" to 1)
来源：http://dali.cdnleiting.top/Article/details/gtjuvpcydf.html

[T14] Kotlin：循环
来源：http://dali.ybcxt.top/Article/details/gttjikjmom.html

for (i in 1..10) println(i)
来源：http://dali.pycfn.com/Article/details/gtubvykhyy.html

[T15] Kotlin：接口
来源：http://dali.zhijiandao.cn/Article/details/gtfzmrcvgm.html

interface Shape { fun area(): Double }
来源：http://dali.wangdashe.top/Article/details/gttbolugdw.html

[T16] Swift：Hello World
来源：http://dali.9152youxi.cn/Article/details/gtzzogbmmt.html

print("Hello")
来源：http://dali.jiagoushi.top/Article/details/gtbdqbujrk.html

[T17] Swift：变量与常量
来源：http://dali.daxiang520.top/Article/details/gtvvupwgmr.html

var a = 1;  let b = 2
来源：http://dali.shanyushiyangtech.top/Article/details/gtjvtizzop.html

[T18] Swift：字符串插值
来源：http://dali.gotoacloud.top/Article/details/gtnoogtkyk.html

"值: \(b)"
来源：http://dali.hongshengwenyu.top/Article/details/gtpmziaswi.html

[T19] Swift：可选绑定
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpyplliiz.html

if let n = opt { print(n) }
来源：http://dali.jyoumei.cn/Article/details/gtqpzsjpik.html

[T20] Swift：数组操作
来源：http://dali.sysykeji.top/Article/details/gtxmrwllcd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jyoumei.cn/Article/details/gtxwtkkzmr.html

[T21] Swift：遍历
来源：http://dali.c1oappe.top/Article/details/gtxodnwrmc.html

for x in a { print(x) }
来源：http://dali.zhongyouzk.top/Article/details/gtvzestmjd.html

[T22] Swift：字典
来源：http://dali.bjfxy.top/Article/details/gtvvdrwjsj.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.feifeiyinyue.top/Article/details/gtdhctsvif.html

[T23] Swift：函数
来源：http://dali.jqgufenzy.top/Article/details/gttqsawwzf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.wangdashe.top/Article/details/gtbqjmpkvg.html

[T24] Swift：闭包
来源：http://dali.xuanzx.com/Article/details/gtczkjtrqj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.birdmap.top/Article/details/gtascnykiv.html

[T25] Swift：结构体
来源：http://dali.hongshengwenyu.top/Article/details/gtfhnduhps.html

struct P { var x: Int }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxqnbelao.html

[T26] Swift：类与重写
来源：http://dali.yanxiufei.cn/Article/details/gtbovaihcp.html

class A: Base { override func f() {} }
来源：http://dali.nanxinkj.top/Article/details/gtkfrtelmc.html

[T27] Swift：错误处理
来源：http://dali.tanke756.top/Article/details/gtbedfwlyk.html

do { try f() } catch { print(error) }
来源：http://dali.andypj.xyz/Article/details/gtxwrfeoin.html

[T28] Swift：枚举
来源：http://dali.ydzc1.top/Article/details/gtuoipudxy.html

enum Color { case red, green }
来源：http://dali.xziqi.cn/Article/details/gtpquehlac.html

[T29] Swift：guard 提前返回
来源：http://dali.mhx1999.top/Article/details/gtafmdqovu.html

guard let x = opt else { return }
来源：http://dali.yanxiufei.cn/Article/details/gtlkuabbba.html

[T30] Swift：协议
来源：http://dali.haohaochexian.top/Article/details/gtqwazaaub.html

protocol Shape { func area() -> Double }
来源：http://dali.dashuyun.cn/Article/details/gtnjaugrdi.html

[T31] Lua：Hello World
来源：http://dali.yj202588.top/Article/details/gtgpfyonpu.html

print("Hello")
来源：http://dali.9152youxi.cn/Article/details/gtcqgnbvhr.html

[T32] Lua：局部变量
来源：http://dali.yj202588.top/Article/details/gtgzkypbby.html

local a = 1
来源：http://dali.zhoulong.xyz/Article/details/gtvisxrrhq.html

[T33] Lua：表（数组）
来源：http://dali.yj202588.top/Article/details/gtvdwxiqdn.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhiwuduotai.top/Article/details/gtkbpytwcv.html

[T34] Lua：遍历表
来源：http://dali.zhongyouzk.top/Article/details/gtqxcxtbfq.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.yj20258.top/Article/details/gtfqgomyel.html

[T35] Lua：字典表
来源：http://dali.nanxuanxn.top/Article/details/gtwzvgjwjj.html

local d = { a = 1 };  d.b = 2
来源：http://dali.nwbrower.top/Article/details/gtabiwhgea.html

[T36] Lua：函数
来源：http://dali.shuidangran.top/Article/details/gtvkdlqdsl.html

function add(a, b) return a + b end
来源：http://dali.gaohongyu789.top/Article/details/gtplcebdfg.html

[T37] Lua：字符串拼接
来源：http://dali.yj202588.top/Article/details/gtsfylxsyx.html

"a" .. "b"
来源：http://dali.cqqwz.cn/Article/details/gtnvrmaipe.html

[T38] Lua：条件
来源：http://dali.ydzc1.top/Article/details/gtgzxyuatr.html

if x > 0 then print("正") end
来源：http://dali.zdqjudy.top/Article/details/gtamcsnful.html

[T39] Lua：模式匹配
来源：http://dali.hnxiangtu.top/Article/details/gtytdswbis.html

string.find(s, "%d+")
来源：http://dali.yueranfly.top/Article/details/gtbeqozhct.html

[T40] Lua：元表
来源：http://dali.birdmap.top/Article/details/gtyigxishv.html

setmetatable({}, { __index = base })
来源：http://dali.havefunace.top/Article/details/gtdcyfrjnh.html


<!-- 参考信息 -->