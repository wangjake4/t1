代发 wailian999

find . -name "*.log" -type f
来源：http://dali.yvedp.cn/Article/details/gtrhxwskqh.html

[R44] 按修改时间查找
来源：http://dali.jyoumei.cn/Article/details/gtmuapvbuj.html

find . -mtime -7 -type f
来源：http://dali.pengpengdd.cyou/Article/details/gtrpblwmay.html

[R45] 批量删除
来源：http://dali.pycfn.com/Article/details/gtsijncqkb.html

find . -name "*.tmp" -delete
来源：http://dali.chenjidiqi.icu/Article/details/gtndtfqegq.html

[R46] 递归替换文件内容
来源：http://dali.redwolf501.top/Article/details/gtkwoltzms.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.guannengcc.top/Article/details/gtvsbbmazw.html

[R47] sed 单行替换
来源：http://dali.hongshengwenyu.top/Article/details/gtsaxvqirw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtktjoutof.html

[R48] awk 取指定列
来源：http://dali.bjfxy.top/Article/details/gtthqmfpmn.html

awk '{print $1, $3}' a.txt
来源：http://dali.nanxinkj.top/Article/details/gtljkjouib.html

[R49] awk 带条件
来源：http://dali.cdnleiting.top/Article/details/gtihwnzbxq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhiwuduotai.top/Article/details/gtxxcmtoam.html

[R50] awk 求和
来源：http://dali.yongpay.top/Article/details/gtfmznagnz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.tian-w.cn/Article/details/gtxrhyohgk.html

[R51] 排序去重取前几
来源：http://dali.jiagoushi.top/Article/details/gtyuwnucog.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.aizwys.cn/Article/details/gtswciwouo.html

[R52] 统计行数
来源：http://dali.yj202588.top/Article/details/gtcwjfjqsb.html

wc -l a.txt
来源：http://dali.ehwqpu.com/Article/details/gtdlfggwkn.html

[R53] 查看文件头与实时尾
来源：http://dali.nanxuanxn.top/Article/details/gtuogpqeet.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zdqjudy.top/Article/details/gtusfxvafl.html

[R54] 比较两个文件
来源：http://dali.tianlin.xyz/Article/details/gtszvsedvu.html

diff a.txt b.txt
来源：http://dali.gotoacloud.top/Article/details/gtnwnheboe.html

[R55] 压缩与解压
来源：http://dali.zdqjudy.top/Article/details/gtszulxfid.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ywan-chungtsiang.top/Article/details/gtixulabwz.html

[R56] 远程拷贝
来源：http://dali.jlsjyb.cn/Article/details/gtdvpetxik.html

scp file user@host:/path/
来源：http://dali.chenjidiqi.icu/Article/details/gtyszwnhjt.html

[R57] 远程执行命令
来源：http://dali.ybcxt.top/Article/details/gtfhxhfnap.html

ssh user@host 'uptime'
来源：http://dali.sxryk.cn/Article/details/gtcvawbdhz.html

[R58] 下载文件
来源：http://dali.shzxlz.cn/Article/details/gtbpcnddhv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xinyue.icu/Article/details/gtqjkyfgmn.html

[R59] 发 POST JSON
来源：http://dali.c1oappe.top/Article/details/gtqmzhiqde.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.dianchejie.cn/Article/details/gtxlcvtkie.html

[R60] 只看 HTTP 状态码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsfnblkem.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.9152youxi.cn/Article/details/gtwookzehw.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gtvuxgdjco.html

df -h;  du -sh *
来源：http://dali.yvedp.cn/Article/details/gtxtiiqmwd.html

[R62] 找最占空间的文件
来源：http://dali.vqdsnc.cn/Article/details/gtljvwegaf.html

du -ah . | sort -rh | head -10
来源：http://dali.aibaodan.cn/Article/details/gtigomstgh.html

[R63] 内存与进程
来源：http://dali.jinqigfzy.top/Article/details/gteuheeefj.html

free -h;  ps aux | grep nginx
来源：http://dali.haohaochexian.top/Article/details/gtzdthrkpp.html

[R64] 结束进程
来源：http://dali.hfpthk.cn/Article/details/gtargaowdu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhongyouzk.top/Article/details/gtsfbkyznx.html

[R65] 查看端口占用
来源：http://dali.pengpengdd.cyou/Article/details/gtpxqgimpz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.aibaodan.cn/Article/details/gtblhddfbq.html

[R66] 定时任务
来源：http://dali.jqgfzy.top/Article/details/gtlvbkbljm.html

crontab -e;  crontab -l
来源：http://dali.xinyue.icu/Article/details/gtnlklvybl.html

[R67] 生成随机十六进制串
来源：http://dali.jqgfzy.top/Article/details/gtcfysurfo.html

openssl rand -hex 16
来源：http://dali.andypj.xyz/Article/details/gttbsbwpay.html

[R68] 计算文件校验值
来源：http://dali.smart0.xyz/Article/details/gtajkpdser.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.tianlin.xyz/Article/details/gtbxroowzc.html

[R69] 生成随机密码
来源：http://dali.zhoulong.xyz/Article/details/gtdmvpptcd.html

head -c 16 /dev/urandom | base64
来源：http://dali.c1oappe.top/Article/details/gtieqlwgog.html

[R70] 时间戳与互转
来源：http://dali.yanxiufei.cn/Article/details/gttiknypoa.html

date +%s;  date -d @1700000000
来源：http://dali.jqgufenzy.top/Article/details/gtlqyfuole.html

[R71] 日期格式化
来源：http://dali.nwbrower.top/Article/details/gtfvjyqopn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.feifeiyinyue.top/Article/details/gtxrrrcwkd.html

[R72] 等待端口就绪
来源：http://dali.9152youxi.cn/Article/details/gtjtmzaqsf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cashguo.top/Article/details/gtormgzuma.html

[R73] 分割大日志
来源：http://dali.fzhhl.top/Article/details/gtwbaqryyn.html

split -l 1000 big.log part_
来源：http://dali.nanxinkj.top/Article/details/gtireutqoc.html

[R74] 批量重命名
来源：http://dali.gaohongyu789.top/Article/details/gtgwvtribf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yanxiufei.cn/Article/details/gtwzjvfunu.html

[R75] 导出环境变量
来源：http://dali.sweek.top/Article/details/gtmwgodnjy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.316326.xyz/Article/details/gtiogbqgme.html

[R76] 使用临时文件
来源：http://dali.jinqigfzy.top/Article/details/gtczcydgqt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.andypj.xyz/Article/details/gtajmrzbaw.html

[R77] 读取用户输入
来源：http://dali.aizwys.cn/Article/details/gtkewddvmn.html

read -rp "请输入: " ans
来源：http://dali.mhx1999.top/Article/details/gtiqloipdy.html

[R78] 交互式菜单
来源：http://dali.chenjidiqi.icu/Article/details/gtydgkwnej.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.havefunace.top/Article/details/gtavcsdsus.html

[R79] 解析命令行选项
来源：http://dali.cucudq.cn/Article/details/gtfkhlulsm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.svipenyu.cn/Article/details/gtynfjmloh.html

[R80] 查看脚本执行耗时
来源：http://dali.meibo888.top/Article/details/gtwmvoqgcl.html

time ./run.sh
来源：http://dali.dianchejie.cn/Article/details/gthbkuyowo.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gthfklylju.html

S. C / C++ 专题
来源：http://dali.quarkkingdee.top/Article/details/gtuozxfoxd.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtrlkdxozj.html

[S01] C：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtfjlrgnsb.html

#include <stdio.h>
来源：http://dali.jiagoushi.top/Article/details/gthkmfhjgy.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hnxiangtu.top/Article/details/gtulenkgaf.html

[S02] C：变量与格式化输出
来源：http://dali.cucudq.cn/Article/details/gtcitbjovv.html

int a = 10; printf("%d\n", a);
来源：http://dali.jqgfzy.top/Article/details/gtrhcefwil.html

[S03] C：读入整数
来源：http://dali.zhiwuduotai.top/Article/details/gtpamceetd.html

int x; scanf("%d", &x);
来源：http://dali.andypj.xyz/Article/details/gtfjclindh.html

[S04] C：字符串复制
来源：http://dali.yj202588.top/Article/details/gtuhmcvgcq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.daxiang520.top/Article/details/gtvaxjxwev.html

[S05] C：字符串长度
来源：http://dali.jyoumei.cn/Article/details/gtdivrepxt.html

strlen(s)
来源：http://dali.cucudq.cn/Article/details/gtpekfugpe.html

[S06] C：字符串比较
来源：http://dali.gotoacloud.top/Article/details/gtyxsjanxm.html

strcmp(a, b) == 0
来源：http://dali.havefunace.top/Article/details/gtvkcspqin.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gtltdwjxdt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yangfankeji.com/Article/details/gteqooswon.html

[S08] C：动态内存分配与释放
来源：http://dali.jinqigufen.top/Article/details/gtxzxddfrb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hongshengwenyu.top/Article/details/gtaaytsink.html

[S09] C：结构体定义与初始化
来源：http://dali.hnxiangtu.top/Article/details/gtcduzihol.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xuanzx.com/Article/details/gtjgggevgv.html

[S10] C：指针与解引用
来源：http://dali.yuanzhike.top/Article/details/gtrbrgnyzv.html

int *p = &a;  *p = 5;
来源：http://dali.aizwys.cn/Article/details/gttjopcoyf.html

[S11] C：逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gtmxpulfro.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhixingplan.top/Article/details/gtssjmrzbt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlybepmoe.html

fclose(f);
来源：http://dali.pycfn.com/Article/details/gttfduvpyp.html

[S12] C：写文件
来源：http://dali.jinqigfzy.top/Article/details/gtplatfyjn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xziqi.cn/Article/details/gtmwhalatm.html

[S13] C：宏定义
来源：http://dali.cqqwz.cn/Article/details/gtwmmoocms.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cheryme.top/Article/details/gtxlwdugud.html

[S14] C：枚举
来源：http://dali.sufxvd.cn/Article/details/gtcvffabut.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.andypj.xyz/Article/details/gtwlpcgdcl.html

[S15] C：类型转换
来源：http://dali.sysykeji.top/Article/details/gtqtuqixme.html

(double) a / b
来源：http://dali.bjfxy.top/Article/details/gtdnembvtr.html

[S16] C：位操作置位
来源：http://dali.quarkkingdee.top/Article/details/gtdsqeviig.html

x |= (1 << 3);
来源：http://dali.dianchejie.cn/Article/details/gtdajliygw.html

[S17] C：安全拼接字符串
来源：http://dali.cheryme.top/Article/details/gtekrceulb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hnqzz.top/Article/details/gtoymzvanc.html

[S18] C：命令行参数
来源：http://dali.shzxlz.cn/Article/details/gtfiykphko.html

int main(int argc, char **argv)
来源：http://dali.yanxiufei.cn/Article/details/gthdecfjrd.html

[S19] C：快速排序
来源：http://dali.cqqwz.cn/Article/details/gtwdnulvfz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.tianlin.xyz/Article/details/gtstxsoxax.html

[S20] C：二分查找
来源：http://dali.wangdashe.top/Article/details/gtaonvultf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.0kj1m.cn/Article/details/gtuarmqhme.html

[S21] C：字符类别判断
来源：http://dali.jinqigufen.top/Article/details/gtykhlqzik.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.wangshuangyany.cn/Article/details/gtwvsanzin.html

[S22] C：字符串转数字
来源：http://dali.aizwys.cn/Article/details/gtcdbnqfun.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ppjwa.cn/Article/details/gtsceqnusl.html

[S23] C：随机数
来源：http://dali.shzxlz.cn/Article/details/gtllxzkqch.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.9152youxi.cn/Article/details/gtxwuecqaj.html

[S24] C：获取本地时间
来源：http://dali.hysaishi.cn/Article/details/gtsrxrenel.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.fengsongda.top/Article/details/gtcnqjvfrz.html

[S25] C：内存拷贝
来源：http://dali.guannengcc.top/Article/details/gtqftmyqwo.html

memcpy(dst, src, n);
来源：http://dali.quarkkingdee.top/Article/details/gtncktousr.html

[S26] C：内存清零
来源：http://dali.jlsjyb.cn/Article/details/gtgzlwsmgt.html

memset(a, 0, sizeof a);
来源：http://dali.andypj.xyz/Article/details/gtiiqwqmvw.html

[S27] C：定义常量
来源：http://dali.yueranfly.top/Article/details/gtlcvhwywf.html

const double PI = 3.14159;
来源：http://dali.jinqigfzy.top/Article/details/gteptjxlri.html

[S28] C：静态变量
来源：http://dali.cdnleiting.top/Article/details/gtgptjnaah.html

static int counter = 0;
来源：http://dali.ybcxt.top/Article/details/gtkmskaivl.html

[S29] C：变参函数
来源：http://dali.yvedp.cn/Article/details/gthpauspyt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.wangdashe.top/Article/details/gtctfvzgzf.html

[S30] C：头文件保护
来源：http://dali.xuetiantiany.cn/Article/details/gtydjkiirg.html

#ifndef X_H
来源：http://dali.aizwys.cn/Article/details/gtznibehmd.html

#define X_H
来源：http://dali.chenlongwang.top/Article/details/gtyjtnvuhs.html

#endif
来源：http://dali.jlsjyb.cn/Article/details/gtsevhvdoo.html

[S31] C++：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtonktmdyg.html

#include <iostream>
来源：http://dali.ivvv.top/Article/details/gticlopyim.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zycfv.cn/Article/details/gtkfxmgdik.html

[S32] C++：字符串
来源：http://dali.xziqi.cn/Article/details/gtzabfudjf.html

std::string s = "hi";  s += "!";
来源：http://dali.xuetiantiany.cn/Article/details/gtibtncadv.html

[S33] C++：vector 增删
来源：http://dali.redwolf501.top/Article/details/gtbrstmmqo.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.havefunace.top/Article/details/gtrsmlaetm.html

[S34] C++：遍历 vector
来源：http://dali.chenzaomai.com/Article/details/gtozirpkxo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zdqjudy.top/Article/details/gtehomqfqz.html

[S35] C++：map
来源：http://dali.sxryk.cn/Article/details/gttoodfcbl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pycfn.com/Article/details/gtinvugdbg.html

[S36] C++：unordered_map
来源：http://dali.redwolf501.top/Article/details/gtangajmev.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtkirdjygb.html

[S37] C++：set
来源：http://dali.jinqigufen.top/Article/details/gtuopgonhr.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yueranfly.top/Article/details/gtfvsimdyb.html

[S38] C++：排序
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoscmmvge.html

std::sort(v.begin(), v.end());
来源：http://dali.hysaishi.cn/Article/details/gtufykihuc.html

[S39] C++：自定义比较器排序
来源：http://dali.sufxvd.cn/Article/details/gtexilqnnk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.gogol.net.cn/Article/details/gtojrmlvcq.html

[S40] C++：查找元素
来源：http://dali.c1oappe.top/Article/details/gtynxrowln.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yj202588.top/Article/details/gtxyvvxtyf.html

[S41] C++：类与构造函数
来源：http://dali.zhixingplan.top/Article/details/gtefqiphgn.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cheryme.top/Article/details/gtnscodjno.html

[S42] C++：继承与虚函数
来源：http://dali.hammf.cn/Article/details/gtsxdddjlw.html

class B : public Base { public: void f() override {} };
来源：http://dali.redwolf501.top/Article/details/gtxrehvqwc.html

[S43] C++：智能指针
来源：http://dali.pycfn.com/Article/details/gtiipfwiil.html

auto p = std::make_unique<int>(5);
来源：http://dali.yanxiufei.cn/Article/details/gtkpkcejti.html

[S44] C++：引用传参
来源：http://dali.jiagoushi.top/Article/details/gtqkncmqyw.html

void inc(int &x) { ++x; }
来源：http://dali.yangfankeji.com/Article/details/gtdteqftqp.html

[S45] C++：lambda
来源：http://dali.jianghu66.top/Article/details/gtfpxdiesf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnlbjhbjd.html

[S46] C++：函数模板
来源：http://dali.yuxming.cn/Article/details/gtexoivweb.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.0kj1m.cn/Article/details/gtrnozwjrq.html

[S47] C++：结构化绑定遍历
来源：http://dali.sufxvd.cn/Article/details/gttyzqlqtj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.feifeiyinyue.top/Article/details/gtbqhfxmvn.html

[S48] C++：逐行读文件
来源：http://dali.svipenyu.cn/Article/details/gtjkpjyxnk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.shangyingyoupin.top/Article/details/gtpxnoeecr.html

while (std::getline(in, line)) { }
来源：http://dali.aibaodan.cn/Article/details/gtszizcnbk.html

[S49] C++：写文件
来源：http://dali.daxiang520.top/Article/details/gtggwriiwb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.pycfn.com/Article/details/gtbsvfxuzi.html

[S50] C++：格式化数字
来源：http://dali.kuanghao11.cn/Article/details/gteqpilkrp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gtcnsgslaf.html

[S51] C++：显式类型转换
来源：http://dali.nanxinkj.top/Article/details/gtmuxjarpm.html

static_cast<double>(a) / b
来源：http://dali.zycfv.cn/Article/details/gtceegyqno.html

[S52] C++：const 与 noexcept
来源：http://dali.ywan-chungtsiang.top/Article/details/gtipyxjtjd.html

int size() const noexcept { return n_; }
来源：http://dali.jlsjyb.cn/Article/details/gtvgqyfxoo.html

[S53] C++：移动语义
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbkqaxpba.html

std::vector<int> w = std::move(v);
来源：http://dali.xylfe.cn/Article/details/gtrnnejipn.html

[S54] C++：异常处理
来源：http://dali.jiagoushi.top/Article/details/gtbthafnab.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.nwbrower.top/Article/details/gtjjnmhyoz.html

[S55] C++：结构化绑定
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthgdjiqij.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.0kj1m.cn/Article/details/gtscalhxdm.html

[S56] C++：optional
来源：http://dali.zhoulong.xyz/Article/details/gtegnvkodw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jyoumei.cn/Article/details/gtjutweiti.html

[S57] C++：编译期常量
来源：http://dali.tanke756.top/Article/details/gtqmxijupa.html

constexpr int N = 10;
来源：http://dali.quarkkingdee.top/Article/details/gtbltzqyxz.html

[S58] C++：命名空间
来源：http://dali.havefunace.top/Article/details/gtpkjiehvm.html

namespace ns { int f() { return 1; } }
来源：http://dali.yvedp.cn/Article/details/gtumnngfpd.html

[S59] C++：静态断言
来源：http://dali.gzhubu.top/Article/details/gtxsdmbjgn.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.andypj.xyz/Article/details/gtwbcyleaj.html

[S60] C++：遍历并删除元素
来源：http://dali.nanxuanxn.top/Article/details/gtdtgctufm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.xuanzx.com/Article/details/gtvdhmdzkr.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtqwqqbspa.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shzxlz.cn/Article/details/gtanataffb.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gtudasfsio.html

[T01] Kotlin：Hello World
来源：http://dali.yuxming.cn/Article/details/gtgfqemful.html

println("Hello")
来源：http://dali.hysaishi.cn/Article/details/gtzmucudku.html

[T02] Kotlin：变量
来源：http://dali.kuanghao11.cn/Article/details/gtghicaaxm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cucudq.cn/Article/details/gttzuczdng.html

[T03] Kotlin：字符串模板
来源：http://dali.daria6918.cn/Article/details/gtzeexscps.html

"值: $b"
来源：http://dali.yvedp.cn/Article/details/gtfblhmtec.html

[T04] Kotlin：空安全
来源：http://dali.vqdsnc.cn/Article/details/gtikztzaxr.html

val n: String? = null;  n?.length
来源：http://dali.ybcxt.top/Article/details/gtiduqzbmb.html

[T05] Kotlin：when 表达式
来源：http://dali.zhixingplan.top/Article/details/gtapnkvkci.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yvedp.cn/Article/details/gtdgfmgekw.html

[T06] Kotlin：集合映射
来源：http://dali.zhijiandao.cn/Article/details/gtqjusmfnf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xziqi.cn/Article/details/gtlcgdyjqc.html

[T07] Kotlin：集合过滤
来源：http://dali.cdnleiting.top/Article/details/gtspgjdxbh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zycfv.cn/Article/details/gthhqujuns.html

[T08] Kotlin：数据类
来源：http://dali.cqqwz.cn/Article/details/gtnhmbnbxb.html

data class User(val name: String, val age: Int)
来源：http://dali.iojbl.cn/Article/details/gtcfxgxtpn.html

[T09] Kotlin：扩展函数
来源：http://dali.ybcxt.top/Article/details/gtlzkrbnyu.html

fun String.exclaim() = this + "!"
来源：http://dali.shangyingyoupin.top/Article/details/gtcwzuzeit.html

[T10] Kotlin：默认参数
来源：http://dali.tanke756.top/Article/details/gtwgaukpra.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.feifeiyinyue.top/Article/details/gtlinqomtb.html

[T11] Kotlin：协程
来源：http://dali.jiagoushi.top/Article/details/gtudhwrekn.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhiwuduotai.top/Article/details/gtajqwzgpb.html

[T12] Kotlin：解构声明
来源：http://dali.gzhubu.top/Article/details/gtzfxulkco.html

val (a, b) = Pair(1, 2)
来源：http://dali.316326.xyz/Article/details/gtavxfaxib.html

[T13] Kotlin：只读 Map
来源：http://dali.tian-w.cn/Article/details/gtlyugfswn.html

val m = mapOf("a" to 1)
来源：http://dali.svipenyu.cn/Article/details/gtearjpcpj.html

[T14] Kotlin：循环
来源：http://dali.daxiang520.top/Article/details/gtqgzsltlr.html

for (i in 1..10) println(i)
来源：http://dali.zdqjudy.top/Article/details/gtydzifado.html

[T15] Kotlin：接口
来源：http://dali.tian-w.cn/Article/details/gtyrzbzptp.html

interface Shape { fun area(): Double }
来源：http://dali.xuanzx.com/Article/details/gtliqnsehv.html

[T16] Swift：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtmkaaqfep.html

print("Hello")
来源：http://dali.xylfe.cn/Article/details/gteluhciqv.html

[T17] Swift：变量与常量
来源：http://dali.smart0.xyz/Article/details/gtaejdlzgh.html

var a = 1;  let b = 2
来源：http://dali.yuanzhike.top/Article/details/gtzgebcuoz.html

[T18] Swift：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gtdoflucmp.html

"值: \(b)"
来源：http://dali.redwolf501.top/Article/details/gthswayyjr.html

[T19] Swift：可选绑定
来源：http://dali.andypj.xyz/Article/details/gtzsuflmel.html

if let n = opt { print(n) }
来源：http://dali.cqqwz.cn/Article/details/gtgkmbljbk.html

[T20] Swift：数组操作
来源：http://dali.chenzaomai.com/Article/details/gtdsrqjfki.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hammf.cn/Article/details/gtjanxvrlw.html

[T21] Swift：遍历
来源：http://dali.zhengqikj.top/Article/details/gtxkflzdvz.html

for x in a { print(x) }
来源：http://dali.shzxlz.cn/Article/details/gtlvdfkmqj.html

[T22] Swift：字典
来源：http://dali.yj20258.top/Article/details/gtioqygccm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.tian-w.cn/Article/details/gtaqoparma.html

[T23] Swift：函数
来源：http://dali.yongpay.top/Article/details/gtmxtauzif.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hysaishi.cn/Article/details/gtrdjganle.html

[T24] Swift：闭包
来源：http://dali.svipenyu.cn/Article/details/gtkvvhhepv.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.gogol.net.cn/Article/details/gtwusjzygd.html

[T25] Swift：结构体
来源：http://dali.ydzc1.top/Article/details/gtcmaywvbn.html

struct P { var x: Int }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzaswhcva.html

[T26] Swift：类与重写
来源：http://dali.bjfxy.top/Article/details/gtbzrlcsfc.html

class A: Base { override func f() {} }
来源：http://dali.daxiang520.top/Article/details/gtdcmfmwsk.html

[T27] Swift：错误处理
来源：http://dali.jqgfzy.top/Article/details/gtmvnzoofk.html

do { try f() } catch { print(error) }
来源：http://dali.xuanzx.com/Article/details/gtemwfpkpt.html

[T28] Swift：枚举
来源：http://dali.haohaochexian.top/Article/details/gtdmlkdhoj.html

enum Color { case red, green }
来源：http://dali.smart0.xyz/Article/details/gtkajdzzco.html

[T29] Swift：guard 提前返回
来源：http://dali.dashuyun.cn/Article/details/gtbaapmujf.html

guard let x = opt else { return }
来源：http://dali.shzxlz.cn/Article/details/gtcqjlvpct.html

[T30] Swift：协议
来源：http://dali.mhx1999.top/Article/details/gtgglgiwda.html

protocol Shape { func area() -> Double }
来源：http://dali.cashguo.top/Article/details/gtmivacxra.html

[T31] Lua：Hello World
来源：http://dali.jinqigufen.top/Article/details/gtgultyjgb.html

print("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgzmdscbn.html

[T32] Lua：局部变量
来源：http://dali.redwolf501.top/Article/details/gtvpuxidmw.html

local a = 1
来源：http://dali.jlsjyb.cn/Article/details/gtidyqkjhy.html

[T33] Lua：表（数组）
来源：http://dali.aizwys.cn/Article/details/gtrcbnmgfd.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.yj20258888.top/Article/details/gtqomwfsph.html

[T34] Lua：遍历表
来源：http://dali.yj20258.top/Article/details/gtstjudswi.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.havefunace.top/Article/details/gtbmqshjtr.html

[T35] Lua：字典表
来源：http://dali.jlsjyb.cn/Article/details/gtmpvmpjrq.html

local d = { a = 1 };  d.b = 2
来源：http://dali.cashguo.top/Article/details/gtffpenaxp.html

[T36] Lua：函数
来源：http://dali.iojbl.cn/Article/details/gtakzuylcd.html

function add(a, b) return a + b end
来源：http://dali.9152youxi.cn/Article/details/gtyqtmsftf.html

[T37] Lua：字符串拼接
来源：http://dali.dashuyun.cn/Article/details/gtnzacmrqn.html

"a" .. "b"
来源：http://dali.zhengqikj.top/Article/details/gtzaesajtw.html

[T38] Lua：条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtecrvqwkb.html

if x > 0 then print("正") end
来源：http://dali.feifeiyinyue.top/Article/details/gtvxcfgacf.html

[T39] Lua：模式匹配
来源：http://dali.gzhubu.top/Article/details/gtdaqlviao.html

string.find(s, "%d+")
来源：http://dali.0kj1m.cn/Article/details/gtazduansa.html

[T40] Lua：元表
来源：http://dali.aizwys.cn/Article/details/gtoapxlove.html

setmetatable({}, { __index = base })
来源：http://dali.xuetiantiany.cn/Article/details/gtdftitnrk.html

[T41] Perl：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtuwkmxsst.html

print "Hello\n";
来源：http://dali.tian-w.cn/Article/details/gtltnprpza.html

[T42] Perl：变量类型
来源：http://dali.jinqigufen.top/Article/details/gtcseprmhh.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.cashguo.top/Article/details/gtbbaesvki.html

[T43] Perl：字符串插值
来源：http://dali.sysykeji.top/Article/details/gtdjaitcya.html

"值: $a"
来源：http://dali.nanxuanxn.top/Article/details/gtvscqxkaa.html

[T44] Perl：条件
来源：http://dali.c1oappe.top/Article/details/gtqjvnecgv.html

if ($a > 0) { print "正"; }
来源：http://dali.nanxinkj.top/Article/details/gtojlwikln.html

[T45] Perl：数组遍历
来源：http://dali.nwbrower.top/Article/details/gtscicmots.html

for my $x (@arr) { print $x; }
来源：http://dali.xylfe.cn/Article/details/gtmzmdcuqb.html

[T46] Perl：哈希操作
来源：http://dali.316326.xyz/Article/details/gtuxgxxyit.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.yuanzhike.top/Article/details/gtulibfjjk.html


<!-- 参考信息 -->