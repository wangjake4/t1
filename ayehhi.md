代发 wailian999

find . -name "*.log" -type f
来源：http://dali.xziqi.cn/Article/details/gt2ystqjfzb.html

[R44] 按修改时间查找
来源：http://dali.jqgfzy.top/Article/details/gt2hheuscda.html

find . -mtime -7 -type f
来源：http://dali.aibaodan.cn/Article/details/gt2grkywhjm.html

[R45] 批量删除
来源：http://dali.tanke756.top/Article/details/gt2ogjedoup.html

find . -name "*.tmp" -delete
来源：http://dali.zycfv.cn/Article/details/gt2sqopcjdm.html

[R46] 递归替换文件内容
来源：http://dali.cashguo.top/Article/details/gt2ebuvdrzh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zdqjudy.top/Article/details/gt2iytogizd.html

[R47] sed 单行替换
来源：http://dali.meibo888.top/Article/details/gt2sahjuuxw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2apxitoal.html

[R48] awk 取指定列
来源：http://dali.zdqjudy.top/Article/details/gt2htxshciw.html

awk '{print $1, $3}' a.txt
来源：http://dali.gzhubu.top/Article/details/gt2jivquixe.html

[R49] awk 带条件
来源：http://dali.sweek.top/Article/details/gt2sufuryfc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yonumen.top/Article/details/gt2nyxugswi.html

[R50] awk 求和
来源：http://dali.ivvv.top/Article/details/gt2wbzipuwz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shzxlz.cn/Article/details/gt2ruevbzrs.html

[R51] 排序去重取前几
来源：http://dali.0kj1m.cn/Article/details/gt2ibvjlmrt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xziqi.cn/Article/details/gt2hqvebltl.html

[R52] 统计行数
来源：http://dali.nanxuanxn.top/Article/details/gt2sbhulemi.html

wc -l a.txt
来源：http://dali.zhongyouzk.top/Article/details/gt2vjmwzmvp.html

[R53] 查看文件头与实时尾
来源：http://dali.cdnleiting.top/Article/details/gt2cjzmozls.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tianlin.xyz/Article/details/gt2mlmzszkr.html

[R54] 比较两个文件
来源：http://dali.yuanzhike.top/Article/details/gt2qovxrctl.html

diff a.txt b.txt
来源：http://dali.cheryme.top/Article/details/gt2kiaodgax.html

[R55] 压缩与解压
来源：http://dali.ybcxt.top/Article/details/gt2opqmcnzp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.316326.xyz/Article/details/gt2avyfzyfs.html

[R56] 远程拷贝
来源：http://dali.hywenlv.cn/Article/details/gt2eacrisiy.html

scp file user@host:/path/
来源：http://dali.sxryk.cn/Article/details/gt2ppegbzmt.html

[R57] 远程执行命令
来源：http://dali.nanxuanxn.top/Article/details/gt2ffqcojlh.html

ssh user@host 'uptime'
来源：http://dali.zdqjudy.top/Article/details/gt2huectaex.html

[R58] 下载文件
来源：http://dali.cucudq.cn/Article/details/gt2lxqjtple.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hongshengwenyu.top/Article/details/gt2aeakvkgv.html

[R59] 发 POST JSON
来源：http://dali.quarkkingdee.top/Article/details/gt2xzzfuywy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ivvv.top/Article/details/gt2aojdiiiw.html

[R60] 只看 HTTP 状态码
来源：http://dali.andypj.xyz/Article/details/gt2kopsfxap.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ehwqpu.com/Article/details/gt2ljuablee.html

[R61] 磁盘占用
来源：http://dali.guowangkeji.top/Article/details/gt2czwvqpgn.html

df -h;  du -sh *
来源：http://dali.andypj.xyz/Article/details/gt2iobkucob.html

[R62] 找最占空间的文件
来源：http://dali.iojbl.cn/Article/details/gt2qwvfmhzc.html

du -ah . | sort -rh | head -10
来源：http://dali.chenzaomai.com/Article/details/gt2xebqntpw.html

[R63] 内存与进程
来源：http://dali.nanxinkj.top/Article/details/gt2utkleiqb.html

free -h;  ps aux | grep nginx
来源：http://dali.sxryk.cn/Article/details/gt2yqzvehtw.html

[R64] 结束进程
来源：http://dali.jiagoushi.top/Article/details/gt2stuvxxnu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhongyouzk.top/Article/details/gt2yhlogzkw.html

[R65] 查看端口占用
来源：http://dali.daria6918.cn/Article/details/gt2zrqjxwtw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ppjwa.cn/Article/details/gt2trhdmvgr.html

[R66] 定时任务
来源：http://dali.cucudq.cn/Article/details/gt2bogwxyfa.html

crontab -e;  crontab -l
来源：http://dali.shzxlz.cn/Article/details/gt2znsfouxa.html

[R67] 生成随机十六进制串
来源：http://dali.yueranfly.top/Article/details/gt2cpbdrpzs.html

openssl rand -hex 16
来源：http://dali.ppjwa.cn/Article/details/gt2lhggwokb.html

[R68] 计算文件校验值
来源：http://dali.iojbl.cn/Article/details/gt2thuxnmoq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jqgufenzy.top/Article/details/gt2vrpwejxk.html

[R69] 生成随机密码
来源：http://dali.haohaochexian.top/Article/details/gt2flvrqcgq.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ykqqsybs.html

[R70] 时间戳与互转
来源：http://dali.zhixingplan.top/Article/details/gt2zsrbajoz.html

date +%s;  date -d @1700000000
来源：http://dali.feifeiyinyue.top/Article/details/gt2hbrblzcj.html

[R71] 日期格式化
来源：http://dali.guannengcc.top/Article/details/gt2busknqix.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yonumen.top/Article/details/gt2lhcbaxng.html

[R72] 等待端口就绪
来源：http://dali.chenjidiqi.icu/Article/details/gt2eswmyeew.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.wangshuangyany.cn/Article/details/gt2ergvrwnn.html

[R73] 分割大日志
来源：http://dali.cheryme.top/Article/details/gt2wynnzfyi.html

split -l 1000 big.log part_
来源：http://dali.yvedp.cn/Article/details/gt2phsubcld.html

[R74] 批量重命名
来源：http://dali.nanxuanxn.top/Article/details/gt2anjskagx.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.smart0.xyz/Article/details/gt2yyycpzsw.html

[R75] 导出环境变量
来源：http://dali.jqgfzy.top/Article/details/gt2qtfhiwdy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.wangdashe.top/Article/details/gt2axevkytk.html

[R76] 使用临时文件
来源：http://dali.quarkkingdee.top/Article/details/gt2xzvsimqj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.iojbl.cn/Article/details/gt2bhssshxc.html

[R77] 读取用户输入
来源：http://dali.jinqigfzy.top/Article/details/gt2zimasgbq.html

read -rp "请输入: " ans
来源：http://dali.jinghuilouyu.cn/Article/details/gt2luhismro.html

[R78] 交互式菜单
来源：http://dali.guowangkeji.top/Article/details/gt2vvjnjmvm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.fzhhl.top/Article/details/gt2ihcazjxe.html

[R79] 解析命令行选项
来源：http://dali.yuxming.cn/Article/details/gt2enqrzzyz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.c1oappe.top/Article/details/gt2ajizudxz.html

[R80] 查看脚本执行耗时
来源：http://dali.kuanghao11.cn/Article/details/gt2gfoeimpr.html

time ./run.sh
来源：http://dali.xuanzx.com/Article/details/gt2jkiksdyv.html

================================================================================
来源：http://dali.chenjidiqi.icu/Article/details/gt2gzmwinli.html

S. C / C++ 专题
来源：http://dali.birdmap.top/Article/details/gt2gmpsbbuz.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gt2xjvxqhqs.html

[S01] C：Hello World
来源：http://dali.jiagoushi.top/Article/details/gt2acioiuff.html

#include <stdio.h>
来源：http://dali.hammf.cn/Article/details/gt2jrantcnm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.nwbrower.top/Article/details/gt2fbkjcnph.html

[S02] C：变量与格式化输出
来源：http://dali.dashuyun.cn/Article/details/gt2zmgpymaj.html

int a = 10; printf("%d\n", a);
来源：http://dali.shangyingyoupin.top/Article/details/gt2jpygplcl.html

[S03] C：读入整数
来源：http://dali.daxiang520.top/Article/details/gt2ssozqjfq.html

int x; scanf("%d", &x);
来源：http://dali.dianchejie.cn/Article/details/gt2xxjihwst.html

[S04] C：字符串复制
来源：http://dali.svipenyu.cn/Article/details/gt2fkylkxqp.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhoulong.xyz/Article/details/gt2mcqbckbm.html

[S05] C：字符串长度
来源：http://dali.ydzc1.top/Article/details/gt2ahhdofee.html

strlen(s)
来源：http://dali.zhixingplan.top/Article/details/gt2gmmeiirk.html

[S06] C：字符串比较
来源：http://dali.aibaodan.cn/Article/details/gt2hlhwwsmp.html

strcmp(a, b) == 0
来源：http://dali.pengpengdd.cyou/Article/details/gt2nhkzfpit.html

[S07] C：数组遍历求和
来源：http://dali.hysaishi.cn/Article/details/gt2fasdckei.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.snrcjt.cn/Article/details/gt2lgauuffd.html

[S08] C：动态内存分配与释放
来源：http://dali.yonumen.top/Article/details/gt2bxfffzri.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinqigufen.top/Article/details/gt2xhwzumnu.html

[S09] C：结构体定义与初始化
来源：http://dali.wangshuangyany.cn/Article/details/gt2kufhkolu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yj20258.top/Article/details/gt2jnunajex.html

[S10] C：指针与解引用
来源：http://dali.fengsongda.top/Article/details/gt2rrxoajoi.html

int *p = &a;  *p = 5;
来源：http://dali.daria6918.cn/Article/details/gt2oixstdvp.html

[S11] C：逐行读文件
来源：http://dali.redwolf501.top/Article/details/gt2mxsfbhrx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.birdmap.top/Article/details/gt2wgjfqmvt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xziqi.cn/Article/details/gt2tuojzezg.html

fclose(f);
来源：http://dali.hfpthk.cn/Article/details/gt2fbbxapqa.html

[S12] C：写文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pgykkwdh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jqgfzy.top/Article/details/gt2xsfylqgl.html

[S13] C：宏定义
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2qijumvoz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hnxiangtu.top/Article/details/gt2gkurhero.html

[S14] C：枚举
来源：http://dali.snrcjt.cn/Article/details/gt2lghzorve.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.tian-w.cn/Article/details/gt2ybayyuml.html

[S15] C：类型转换
来源：http://dali.tianlin.xyz/Article/details/gt2ocvzrnov.html

(double) a / b
来源：http://dali.dianchejie.cn/Article/details/gt2leyhqleb.html

[S16] C：位操作置位
来源：http://dali.feifeiyinyue.top/Article/details/gt2buqtekxz.html

x |= (1 << 3);
来源：http://dali.iojbl.cn/Article/details/gt2aggsmlci.html

[S17] C：安全拼接字符串
来源：http://dali.chenlongwang.top/Article/details/gt2hilitzky.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xziqi.cn/Article/details/gt2yrcmahjo.html

[S18] C：命令行参数
来源：http://dali.zhoulong.xyz/Article/details/gt2kyhcochf.html

int main(int argc, char **argv)
来源：http://dali.cashguo.top/Article/details/gt2eutsnsgt.html

[S19] C：快速排序
来源：http://dali.zhongyouzk.top/Article/details/gt2opolfqtb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ybcxt.top/Article/details/gt2oakgrtus.html

[S20] C：二分查找
来源：http://dali.jiagoushi.top/Article/details/gt2psotwxue.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinqigufen.top/Article/details/gt2cczwdkrh.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yarpmlad.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhixingplan.top/Article/details/gt2evitermj.html

[S22] C：字符串转数字
来源：http://dali.wangdashe.top/Article/details/gt2nvzwikbn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.svipenyu.cn/Article/details/gt2umkngrqk.html

[S23] C：随机数
来源：http://dali.yj20258888.top/Article/details/gt2vdfotzmu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hnqzz.top/Article/details/gt2barfindv.html

[S24] C：获取本地时间
来源：http://dali.gzhubu.top/Article/details/gt2tenswyud.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.guannengcc.top/Article/details/gt2xyehalgc.html

[S25] C：内存拷贝
来源：http://dali.cucudq.cn/Article/details/gt2qwqtfpin.html

memcpy(dst, src, n);
来源：http://dali.yangfankeji.com/Article/details/gt2bjgmjcrn.html

[S26] C：内存清零
来源：http://dali.xylfe.cn/Article/details/gt2gtbjvpcr.html

memset(a, 0, sizeof a);
来源：http://dali.jianghu66.top/Article/details/gt2prmmldxd.html

[S27] C：定义常量
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rfwhndrk.html

const double PI = 3.14159;
来源：http://dali.0kj1m.cn/Article/details/gt2adshazxn.html

[S28] C：静态变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2ewwfcedb.html

static int counter = 0;
来源：http://dali.xylfe.cn/Article/details/gt2zkxhysbs.html

[S29] C：变参函数
来源：http://dali.nanxinkj.top/Article/details/gt2ueiyrgyw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yonumen.top/Article/details/gt2rctrxhhr.html

[S30] C：头文件保护
来源：http://dali.c1oappe.top/Article/details/gt2mhhvavqu.html

#ifndef X_H
来源：http://dali.zhixingplan.top/Article/details/gt2rwuzlzwk.html

#define X_H
来源：http://dali.havefunace.top/Article/details/gt2ietuskgc.html

#endif
来源：http://dali.zdqjudy.top/Article/details/gt2znkmammi.html

[S31] C++：Hello World
来源：http://dali.jianghu66.top/Article/details/gt2jyhjtzbd.html

#include <iostream>
来源：http://dali.jinqigufen.top/Article/details/gt2fwzdnoda.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.ybcxt.top/Article/details/gt2filxhnxf.html

[S32] C++：字符串
来源：http://dali.xuanzx.com/Article/details/gt2hkedbzpe.html

std::string s = "hi";  s += "!";
来源：http://dali.cqqwz.cn/Article/details/gt2fkmoihtf.html

[S33] C++：vector 增删
来源：http://dali.quarkkingdee.top/Article/details/gt2jlbgfoae.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.bjfxy.top/Article/details/gt2weojxqrn.html

[S34] C++：遍历 vector
来源：http://dali.pycfn.com/Article/details/gt2djdbljsm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.kuanghao11.cn/Article/details/gt2vebuousz.html

[S35] C++：map
来源：http://dali.316326.xyz/Article/details/gt2faukvzwq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yonumen.top/Article/details/gt2ecyvahad.html

[S36] C++：unordered_map
来源：http://dali.c1oappe.top/Article/details/gt2lgbzhsdw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yonumen.top/Article/details/gt2bkquujvh.html

[S37] C++：set
来源：http://dali.havefunace.top/Article/details/gt2tjvihypa.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sufxvd.cn/Article/details/gt2vwjucdxu.html

[S38] C++：排序
来源：http://dali.dianchejie.cn/Article/details/gt2leygcvci.html

std::sort(v.begin(), v.end());
来源：http://dali.jinqigfzy.top/Article/details/gt2uoiaqdaz.html

[S39] C++：自定义比较器排序
来源：http://dali.xinyue.icu/Article/details/gt2nlfygymp.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.fzhhl.top/Article/details/gt2ejjnlocp.html

[S40] C++：查找元素
来源：http://dali.nanxinkj.top/Article/details/gt2ufqawsmt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cheryme.top/Article/details/gt2urmomhmp.html

[S41] C++：类与构造函数
来源：http://dali.9152youxi.cn/Article/details/gt2wsxhckwr.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.chenlongwang.top/Article/details/gt2dejeeqvm.html

[S42] C++：继承与虚函数
来源：http://dali.guannengcc.top/Article/details/gt2byblrypd.html

class B : public Base { public: void f() override {} };
来源：http://dali.quarkkingdee.top/Article/details/gt2umrjpwud.html

[S43] C++：智能指针
来源：http://dali.haohaochexian.top/Article/details/gt2kbvlwpiw.html

auto p = std::make_unique<int>(5);
来源：http://dali.iojbl.cn/Article/details/gt2huizdrxy.html

[S44] C++：引用传参
来源：http://dali.hfpthk.cn/Article/details/gt2ccubdmyy.html

void inc(int &x) { ++x; }
来源：http://dali.xuanzx.com/Article/details/gt2zewwxqfv.html

[S45] C++：lambda
来源：http://dali.fzhhl.top/Article/details/gt2rtuukuez.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.guowangkeji.top/Article/details/gt2dbjughtg.html

[S46] C++：函数模板
来源：http://dali.havefunace.top/Article/details/gt2pwvdkahd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.zycfv.cn/Article/details/gt2daiqruuv.html

[S47] C++：结构化绑定遍历
来源：http://dali.jiagoushi.top/Article/details/gt2wyokyahg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shuidangran.top/Article/details/gt2kyvpfpgi.html

[S48] C++：逐行读文件
来源：http://dali.cqqwz.cn/Article/details/gt2miaoftjk.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.316326.xyz/Article/details/gt2uptqpwuq.html

while (std::getline(in, line)) { }
来源：http://dali.haohaochexian.top/Article/details/gt2xezuwshk.html

[S49] C++：写文件
来源：http://dali.jqgfzy.top/Article/details/gt2ojkdobbd.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yvedp.cn/Article/details/gt2ofgeythy.html

[S50] C++：格式化数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bzmoqnfx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yj20258.top/Article/details/gt2ivoikgas.html

[S51] C++：显式类型转换
来源：http://dali.havefunace.top/Article/details/gt2dxcicjlq.html

static_cast<double>(a) / b
来源：http://dali.ehwqpu.com/Article/details/gt2ccdirdgj.html

[S52] C++：const 与 noexcept
来源：http://dali.ehwqpu.com/Article/details/gt2izpcvxbq.html

int size() const noexcept { return n_; }
来源：http://dali.jinqigufen.top/Article/details/gt2kmyhljji.html

[S53] C++：移动语义
来源：http://dali.snrcjt.cn/Article/details/gt2ixrfjdpp.html

std::vector<int> w = std::move(v);
来源：http://dali.cqqwz.cn/Article/details/gt2mbxafupv.html

[S54] C++：异常处理
来源：http://dali.tianlin.xyz/Article/details/gt2bmoxwhax.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.smart0.xyz/Article/details/gt2aazipjpo.html

[S55] C++：结构化绑定
来源：http://dali.gogol.net.cn/Article/details/gt2dbjsldjd.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jyoumei.cn/Article/details/gt2mdnbvavo.html

[S56] C++：optional
来源：http://dali.yueranfly.top/Article/details/gt2cvzbacyt.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.0kj1m.cn/Article/details/gt2xusedaci.html

[S57] C++：编译期常量
来源：http://dali.xylfe.cn/Article/details/gt2sdzjjiqh.html

constexpr int N = 10;
来源：http://dali.guannengcc.top/Article/details/gt2ogobbmfs.html

[S58] C++：命名空间
来源：http://dali.feifeiyinyue.top/Article/details/gt2xutkgnhz.html

namespace ns { int f() { return 1; } }
来源：http://dali.c1oappe.top/Article/details/gt2hnwtkorl.html

[S59] C++：静态断言
来源：http://dali.nanxuanxn.top/Article/details/gt2iaxyrrny.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.sxryk.cn/Article/details/gt2vrxqrexx.html

[S60] C++：遍历并删除元素
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ojgttfdo.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.fzhhl.top/Article/details/gt2zsqxoqoj.html

================================================================================
来源：http://dali.jlsjyb.cn/Article/details/gt2xydatppa.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zhijiandao.cn/Article/details/gt2aahyryjr.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gt2bdcwhyur.html

[T01] Kotlin：Hello World
来源：http://dali.hongshengwenyu.top/Article/details/gt2adxsdjjk.html

println("Hello")
来源：http://dali.dianchejie.cn/Article/details/gt2sxmkqvts.html

[T02] Kotlin：变量
来源：http://dali.snrcjt.cn/Article/details/gt2hkptpkkb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.jlsjyb.cn/Article/details/gt2orhdnbdf.html

[T03] Kotlin：字符串模板
来源：http://dali.guowangkeji.top/Article/details/gt2xkvrheip.html

"值: $b"
来源：http://dali.cashguo.top/Article/details/gt2yoccxzxj.html

[T04] Kotlin：空安全
来源：http://dali.ivvv.top/Article/details/gt2dwjcrgzu.html

val n: String? = null;  n?.length
来源：http://dali.yj20258.top/Article/details/gt2qyigyfei.html

[T05] Kotlin：when 表达式
来源：http://dali.birdmap.top/Article/details/gt2crgxvayz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhongyouzk.top/Article/details/gt2fwsechen.html

[T06] Kotlin：集合映射
来源：http://dali.havefunace.top/Article/details/gt2iqacmitw.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.cucudq.cn/Article/details/gt2jopjtiph.html

[T07] Kotlin：集合过滤
来源：http://dali.hnqzz.top/Article/details/gt2bedwxnst.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jyoumei.cn/Article/details/gt2jzaqicmj.html

[T08] Kotlin：数据类
来源：http://dali.gzhubu.top/Article/details/gt2lybesadd.html

data class User(val name: String, val age: Int)
来源：http://dali.ehwqpu.com/Article/details/gt2mzvuxziw.html

[T09] Kotlin：扩展函数
来源：http://dali.svipenyu.cn/Article/details/gt2tuzrtyzx.html

fun String.exclaim() = this + "!"
来源：http://dali.vqdsnc.cn/Article/details/gt2duhutytr.html

[T10] Kotlin：默认参数
来源：http://dali.fengsongda.top/Article/details/gt2mlirpqgh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dzautlxx.html

[T11] Kotlin：协程
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vmalqfme.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ivvv.top/Article/details/gt2chxxxmkf.html

[T12] Kotlin：解构声明
来源：http://dali.ehwqpu.com/Article/details/gt2eukbqmiu.html

val (a, b) = Pair(1, 2)
来源：http://dali.tianlin.xyz/Article/details/gt2yozzzqrh.html

[T13] Kotlin：只读 Map
来源：http://dali.yvedp.cn/Article/details/gt2fvzgoqok.html

val m = mapOf("a" to 1)
来源：http://dali.bjfxy.top/Article/details/gt2byhyvxzu.html

[T14] Kotlin：循环
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dzxrvtge.html

for (i in 1..10) println(i)
来源：http://dali.xinyue.icu/Article/details/gt2hakxciwf.html

[T15] Kotlin：接口
来源：http://dali.ybcxt.top/Article/details/gt2fesgivuc.html

interface Shape { fun area(): Double }
来源：http://dali.hnqzz.top/Article/details/gt2jttozfvj.html

[T16] Swift：Hello World
来源：http://dali.sufxvd.cn/Article/details/gt2yzcisioa.html

print("Hello")
来源：http://dali.0kj1m.cn/Article/details/gt2rqgocuch.html

[T17] Swift：变量与常量
来源：http://dali.cheryme.top/Article/details/gt2pzqavmix.html

var a = 1;  let b = 2
来源：http://dali.yj202588.top/Article/details/gt2bluvrgid.html

[T18] Swift：字符串插值
来源：http://dali.yj20258888.top/Article/details/gt2mfklwfnj.html

"值: \(b)"
来源：http://dali.feifeiyinyue.top/Article/details/gt2kghbhawi.html

[T19] Swift：可选绑定
来源：http://dali.jqgfzy.top/Article/details/gt2owuhlokd.html

if let n = opt { print(n) }
来源：http://dali.feifeiyinyue.top/Article/details/gt2epzkcqvt.html

[T20] Swift：数组操作
来源：http://dali.meibo888.top/Article/details/gt2smdojtnq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.nanxuanxn.top/Article/details/gt2gtykpidi.html

[T21] Swift：遍历
来源：http://dali.tian-w.cn/Article/details/gt2doladlfi.html

for x in a { print(x) }
来源：http://dali.andypj.xyz/Article/details/gt2rtdudfbv.html

[T22] Swift：字典
来源：http://dali.chenzaomai.com/Article/details/gt2pfecbrfs.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.haohaochexian.top/Article/details/gt2xcxdfmpp.html

[T23] Swift：函数
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vbbeowhw.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ybcxt.top/Article/details/gt2gjemqdua.html

[T24] Swift：闭包
来源：http://dali.tian-w.cn/Article/details/gt2ancjrnez.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zycfv.cn/Article/details/gt2ownblsba.html

[T25] Swift：结构体
来源：http://dali.bjfxy.top/Article/details/gt2ytoomigh.html

struct P { var x: Int }
来源：http://dali.jianghu66.top/Article/details/gt2mouonhgf.html

[T26] Swift：类与重写
来源：http://dali.cashguo.top/Article/details/gt2bgyfxsxt.html

class A: Base { override func f() {} }
来源：http://dali.xylfe.cn/Article/details/gt2wcsztolp.html

[T27] Swift：错误处理
来源：http://dali.tanke756.top/Article/details/gt2xubxgvta.html

do { try f() } catch { print(error) }
来源：http://dali.zycfv.cn/Article/details/gt2ondasgfn.html

[T28] Swift：枚举
来源：http://dali.yj20258.top/Article/details/gt2qfdnunee.html

enum Color { case red, green }
来源：http://dali.shangyingyoupin.top/Article/details/gt2imbkihzh.html

[T29] Swift：guard 提前返回
来源：http://dali.shzxlz.cn/Article/details/gt2epblgyvk.html

guard let x = opt else { return }
来源：http://dali.quarkkingdee.top/Article/details/gt2vtqshrqp.html

[T30] Swift：协议
来源：http://dali.tianlin.xyz/Article/details/gt2hfxfmiym.html

protocol Shape { func area() -> Double }
来源：http://dali.yvedp.cn/Article/details/gt2zxtqgqfw.html

[T31] Lua：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gt2koegvpns.html

print("Hello")
来源：http://dali.nwbrower.top/Article/details/gt2lfseobal.html

[T32] Lua：局部变量
来源：http://dali.cqqwz.cn/Article/details/gt2smvekdyv.html

local a = 1
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uybabnno.html

[T33] Lua：表（数组）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2eszrjgll.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.snrcjt.cn/Article/details/gt2mwlqtawd.html

[T34] Lua：遍历表
来源：http://dali.chenlongwang.top/Article/details/gt2gvhcdpud.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zycfv.cn/Article/details/gt2fvinrtug.html

[T35] Lua：字典表
来源：http://dali.9152youxi.cn/Article/details/gt2vsfreent.html

local d = { a = 1 };  d.b = 2
来源：http://dali.gzhubu.top/Article/details/gt2poaskgbu.html

[T36] Lua：函数
来源：http://dali.zhongyouzk.top/Article/details/gt2mfubskrr.html

function add(a, b) return a + b end
来源：http://dali.ydzc1.top/Article/details/gt2lwhvvbma.html

[T37] Lua：字符串拼接
来源：http://dali.pengpengdd.cyou/Article/details/gt2jtxkocva.html

"a" .. "b"
来源：http://dali.xziqi.cn/Article/details/gt2ddvbrjwc.html

[T38] Lua：条件
来源：http://dali.jinqigfzy.top/Article/details/gt2jijyttrv.html

if x > 0 then print("正") end
来源：http://dali.nanxuanxn.top/Article/details/gt2qsfjklbv.html

[T39] Lua：模式匹配
来源：http://dali.aizwys.cn/Article/details/gt2mcegxflw.html

string.find(s, "%d+")
来源：http://dali.yuxming.cn/Article/details/gt2djpgchps.html

[T40] Lua：元表
来源：http://dali.zhiwuduotai.top/Article/details/gt2ddurzjvr.html

setmetatable({}, { __index = base })
来源：http://dali.jiagoushi.top/Article/details/gt2nmjqknab.html

[T41] Perl：Hello World
来源：http://dali.bjfxy.top/Article/details/gt2rurmpjnz.html

print "Hello\n";
来源：http://dali.hnxiangtu.top/Article/details/gt2ohgeyazm.html

[T42] Perl：变量类型
来源：http://dali.ybcxt.top/Article/details/gt2rjtdhhjn.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ypafdbtb.html

[T43] Perl：字符串插值
来源：http://dali.daxiang520.top/Article/details/gt2rvusovkh.html

"值: $a"
来源：http://dali.c1oappe.top/Article/details/gt2vlgqgmhz.html

[T44] Perl：条件
来源：http://dali.hfpthk.cn/Article/details/gt2wuikfinw.html

if ($a > 0) { print "正"; }
来源：http://dali.gzhubu.top/Article/details/gt2pxeyjolb.html

[T45] Perl：数组遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bvlmmjls.html

for my $x (@arr) { print $x; }
来源：http://dali.zhoulong.xyz/Article/details/gt2nwonapbi.html

[T46] Perl：哈希操作
来源：http://dali.aizwys.cn/Article/details/gt2tmpzmgqu.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.mhx1999.top/Article/details/gt2dafkjari.html


<!-- 参考信息 -->