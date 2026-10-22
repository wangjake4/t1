代发 wailian999

find . -name "*.tmp" -delete
来源：http://dali.ppjwa.cn/Article/details/gt2iupnnapg.html

[R46] 递归替换文件内容
来源：http://dali.sweek.top/Article/details/gt2xtndrtvv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2qdppoepf.html

[R47] sed 单行替换
来源：http://dali.haohaochexian.top/Article/details/gt2pdvkmrec.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xziqi.cn/Article/details/gt2dpuxltnt.html

[R48] awk 取指定列
来源：http://dali.shzxlz.cn/Article/details/gt2yvdwnkij.html

awk '{print $1, $3}' a.txt
来源：http://dali.meibo888.top/Article/details/gt2waevasrc.html

[R49] awk 带条件
来源：http://dali.yuanzhike.top/Article/details/gt2mvfolkdp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.aizwys.cn/Article/details/gt2tkgkpiiq.html

[R50] awk 求和
来源：http://dali.yangfankeji.com/Article/details/gt2wprhipzj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dqpzynwj.html

[R51] 排序去重取前几
来源：http://dali.tianlin.xyz/Article/details/gt2kebjmlzr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yuxming.cn/Article/details/gt2jdjmveve.html

[R52] 统计行数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ncmdhjts.html

wc -l a.txt
来源：http://dali.wangdashe.top/Article/details/gt2vwnppwcg.html

[R53] 查看文件头与实时尾
来源：http://dali.jqgfzy.top/Article/details/gt2dovkzcbg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shuidangran.top/Article/details/gt2gieyaetd.html

[R54] 比较两个文件
来源：http://dali.fzhhl.top/Article/details/gt2bmgzpgvy.html

diff a.txt b.txt
来源：http://dali.gaohongyu789.top/Article/details/gt2lokoyoxr.html

[R55] 压缩与解压
来源：http://dali.aizwys.cn/Article/details/gt2yaxfwbpr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hammf.cn/Article/details/gt2pknkrsdf.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2plxhjvqa.html

scp file user@host:/path/
来源：http://dali.fzhhl.top/Article/details/gt2orwsuxmv.html

[R57] 远程执行命令
来源：http://dali.dianchejie.cn/Article/details/gt2qjkukqfa.html

ssh user@host 'uptime'
来源：http://dali.gotoacloud.top/Article/details/gt2ywcyqgeo.html

[R58] 下载文件
来源：http://dali.hongshengwenyu.top/Article/details/gt2wzcpokic.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jianghu66.top/Article/details/gt2tspgeker.html

[R59] 发 POST JSON
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2yhkbppqb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.tianlin.xyz/Article/details/gt2tqjcjxon.html

[R60] 只看 HTTP 状态码
来源：http://dali.xuetiantiany.cn/Article/details/gt2xgrfiqgl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gotoacloud.top/Article/details/gt2ghbwyoyw.html

[R61] 磁盘占用
来源：http://dali.cheryme.top/Article/details/gt2bhpksggz.html

df -h;  du -sh *
来源：http://dali.shzxlz.cn/Article/details/gt2wlwzsejp.html

[R62] 找最占空间的文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2jzozqfbh.html

du -ah . | sort -rh | head -10
来源：http://dali.cheryme.top/Article/details/gt2jgomyyad.html

[R63] 内存与进程
来源：http://dali.fengsongda.top/Article/details/gt2rwcdspdm.html

free -h;  ps aux | grep nginx
来源：http://dali.tian-w.cn/Article/details/gt2fuasunlm.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ndmvqghl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhongyouzk.top/Article/details/gt2wsozyvae.html

[R65] 查看端口占用
来源：http://dali.andypj.xyz/Article/details/gt2ioqdnuft.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zdqjudy.top/Article/details/gt2gwiprgwl.html

[R66] 定时任务
来源：http://dali.fengsongda.top/Article/details/gt2wzxavwxt.html

crontab -e;  crontab -l
来源：http://dali.svipenyu.cn/Article/details/gt2kdersswb.html

[R67] 生成随机十六进制串
来源：http://dali.daria6918.cn/Article/details/gt2yqulktai.html

openssl rand -hex 16
来源：http://dali.cdnleiting.top/Article/details/gt2pylktwjs.html

[R68] 计算文件校验值
来源：http://dali.xuanzx.com/Article/details/gt2fgzilqjm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.nwbrower.top/Article/details/gt2sfesfvpe.html

[R69] 生成随机密码
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2irhdvkod.html

head -c 16 /dev/urandom | base64
来源：http://dali.meibo888.top/Article/details/gt2pnrlhmyj.html

[R70] 时间戳与互转
来源：http://dali.jinqigfzy.top/Article/details/gt2saukkmqh.html

date +%s;  date -d @1700000000
来源：http://dali.cheryme.top/Article/details/gt2warwkflr.html

[R71] 日期格式化
来源：http://dali.nanxinkj.top/Article/details/gt2nutzmuik.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinqigufen.top/Article/details/gt2rwlgdtiu.html

[R72] 等待端口就绪
来源：http://dali.9152youxi.cn/Article/details/gt2iqqaeqge.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2vyoxuded.html

[R73] 分割大日志
来源：http://dali.hnxiangtu.top/Article/details/gt2ghtoahha.html

split -l 1000 big.log part_
来源：http://dali.kuanghao11.cn/Article/details/gt2amvwsmvb.html

[R74] 批量重命名
来源：http://dali.hnqzz.top/Article/details/gt2lqfcbhmn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zimpvwja.html

[R75] 导出环境变量
来源：http://dali.ydzc1.top/Article/details/gt2qmkqqtwl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yj202588.top/Article/details/gt2mzwxvkgj.html

[R76] 使用临时文件
来源：http://dali.hnxiangtu.top/Article/details/gt2dexjoxrt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jianghu66.top/Article/details/gt2mbmvekfl.html

[R77] 读取用户输入
来源：http://dali.gogol.net.cn/Article/details/gt2qhylhhfc.html

read -rp "请输入: " ans
来源：http://dali.snrcjt.cn/Article/details/gt2stpxclwu.html

[R78] 交互式菜单
来源：http://dali.hammf.cn/Article/details/gt2clfhcnfl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.pycfn.com/Article/details/gt2xrvjnign.html

[R79] 解析命令行选项
来源：http://dali.gogol.net.cn/Article/details/gt2uaflmifc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.redwolf501.top/Article/details/gt2zgpzyweg.html

[R80] 查看脚本执行耗时
来源：http://dali.yvedp.cn/Article/details/gt2gdynsaey.html

time ./run.sh
来源：http://dali.gogol.net.cn/Article/details/gt2obaofups.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2cmwppjlj.html

S. C / C++ 专题
来源：http://dali.gotoacloud.top/Article/details/gt2ezwltqaz.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gt2sssiochj.html

[S01] C：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ckxqidjy.html

#include <stdio.h>
来源：http://dali.hnqzz.top/Article/details/gt2qnzyhpab.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2njzzrrjb.html

[S02] C：变量与格式化输出
来源：http://dali.cucudq.cn/Article/details/gt2mawqqknj.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinqigfzy.top/Article/details/gt2nznwuopu.html

[S03] C：读入整数
来源：http://dali.yuanzhike.top/Article/details/gt2qjyvupks.html

int x; scanf("%d", &x);
来源：http://dali.yuxming.cn/Article/details/gt2dluccinh.html

[S04] C：字符串复制
来源：http://dali.daria6918.cn/Article/details/gt2buyyothe.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.tian-w.cn/Article/details/gt2yduszzog.html

[S05] C：字符串长度
来源：http://dali.nanxinkj.top/Article/details/gt2jwruuybp.html

strlen(s)
来源：http://dali.jianghu66.top/Article/details/gt2orjxjtdm.html

[S06] C：字符串比较
来源：http://dali.wangshuangyany.cn/Article/details/gt2gyppiyec.html

strcmp(a, b) == 0
来源：http://dali.jlsjyb.cn/Article/details/gt2xfambisq.html

[S07] C：数组遍历求和
来源：http://dali.sufxvd.cn/Article/details/gt2xgaqnpuo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.gaohongyu789.top/Article/details/gt2biczfnlk.html

[S08] C：动态内存分配与释放
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uqynscmy.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinqigufen.top/Article/details/gt2tlarzlhc.html

[S09] C：结构体定义与初始化
来源：http://dali.aizwys.cn/Article/details/gt2cqcbxgrb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.aizwys.cn/Article/details/gt2ppcudfve.html

[S10] C：指针与解引用
来源：http://dali.yj20258.top/Article/details/gt2cfmpyaze.html

int *p = &a;  *p = 5;
来源：http://dali.tianlin.xyz/Article/details/gt2lgfufnwl.html

[S11] C：逐行读文件
来源：http://dali.jyoumei.cn/Article/details/gt2mshclzmh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sxryk.cn/Article/details/gt2zebsviwz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.birdmap.top/Article/details/gt2qzbgfgrw.html

fclose(f);
来源：http://dali.havefunace.top/Article/details/gt2shkkbhry.html

[S12] C：写文件
来源：http://dali.316326.xyz/Article/details/gt2leyrsnzh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cucudq.cn/Article/details/gt2ffjldfsz.html

[S13] C：宏定义
来源：http://dali.cheryme.top/Article/details/gt2fueegbil.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pxjdanbu.html

[S14] C：枚举
来源：http://dali.havefunace.top/Article/details/gt2rxformyp.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hywenlv.cn/Article/details/gt2lesewseh.html

[S15] C：类型转换
来源：http://dali.nwbrower.top/Article/details/gt2mvvbebxi.html

(double) a / b
来源：http://dali.pengpengdd.cyou/Article/details/gt2ikblueho.html

[S16] C：位操作置位
来源：http://dali.jianghu66.top/Article/details/gt2lbvnhmrc.html

x |= (1 << 3);
来源：http://dali.smart0.xyz/Article/details/gt2erzvkdws.html

[S17] C：安全拼接字符串
来源：http://dali.jianghu66.top/Article/details/gt2mjtntems.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.svipenyu.cn/Article/details/gt2twuhralu.html

[S18] C：命令行参数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2infywpra.html

int main(int argc, char **argv)
来源：http://dali.aibaodan.cn/Article/details/gt2btadkrwo.html

[S19] C：快速排序
来源：http://dali.ybcxt.top/Article/details/gt2oqdhqgjt.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.nanxuanxn.top/Article/details/gt2fdyxwwsw.html

[S20] C：二分查找
来源：http://dali.bjfxy.top/Article/details/gt2gebixpvi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhongyouzk.top/Article/details/gt2ctxnodgd.html

[S21] C：字符类别判断
来源：http://dali.cdnleiting.top/Article/details/gt2xuouhdxo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.gaohongyu789.top/Article/details/gt2bwztngdt.html

[S22] C：字符串转数字
来源：http://dali.yj20258.top/Article/details/gt2ygvnqqzy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zyrbphyo.html

[S23] C：随机数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2ahakplbk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.fengsongda.top/Article/details/gt2jvalvakq.html

[S24] C：获取本地时间
来源：http://dali.cdnleiting.top/Article/details/gt2qpzuklnj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.gogol.net.cn/Article/details/gt2mlvtxdmw.html

[S25] C：内存拷贝
来源：http://dali.c1oappe.top/Article/details/gt2qkwbjhzs.html

memcpy(dst, src, n);
来源：http://dali.tian-w.cn/Article/details/gt2fgissfxg.html

[S26] C：内存清零
来源：http://dali.sufxvd.cn/Article/details/gt2ckmcgxkw.html

memset(a, 0, sizeof a);
来源：http://dali.quarkkingdee.top/Article/details/gt2fkgzefle.html

[S27] C：定义常量
来源：http://dali.yj202588.top/Article/details/gt2eixaaypg.html

const double PI = 3.14159;
来源：http://dali.hammf.cn/Article/details/gt2mpaldlcz.html

[S28] C：静态变量
来源：http://dali.ybcxt.top/Article/details/gt2zmzezpil.html

static int counter = 0;
来源：http://dali.aizwys.cn/Article/details/gt2dpuxpuxe.html

[S29] C：变参函数
来源：http://dali.xinyue.icu/Article/details/gt2oxjkinbw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hnxiangtu.top/Article/details/gt2khkyijnv.html

[S30] C：头文件保护
来源：http://dali.birdmap.top/Article/details/gt2rrzxedui.html

#ifndef X_H
来源：http://dali.birdmap.top/Article/details/gt2yridmyhs.html

#define X_H
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2znrhzsue.html

#endif
来源：http://dali.nanxuanxn.top/Article/details/gt2arpmyeyt.html

[S31] C++：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gt2pwjhwuun.html

#include <iostream>
来源：http://dali.wangshuangyany.cn/Article/details/gt2ctmkrdrm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.c1oappe.top/Article/details/gt2ykjyvlnm.html

[S32] C++：字符串
来源：http://dali.yj20258888.top/Article/details/gt2itutdszf.html

std::string s = "hi";  s += "!";
来源：http://dali.chenjidiqi.icu/Article/details/gt2tdlqfhph.html

[S33] C++：vector 增删
来源：http://dali.yueranfly.top/Article/details/gt2wmoijtne.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shangyingyoupin.top/Article/details/gt2hknlxhov.html

[S34] C++：遍历 vector
来源：http://dali.cucudq.cn/Article/details/gt2baaaqasy.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.birdmap.top/Article/details/gt2ianolrvt.html

[S35] C++：map
来源：http://dali.feifeiyinyue.top/Article/details/gt2jipiefuq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ydzc1.top/Article/details/gt2tewoqoqf.html

[S36] C++：unordered_map
来源：http://dali.yuxming.cn/Article/details/gt2lxiqluar.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.gaohongyu789.top/Article/details/gt2zactcvhj.html

[S37] C++：set
来源：http://dali.aizwys.cn/Article/details/gt2kkacbzwt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.guannengcc.top/Article/details/gt2zoxvurwq.html

[S38] C++：排序
来源：http://dali.shangyingyoupin.top/Article/details/gt2jqbiaprs.html

std::sort(v.begin(), v.end());
来源：http://dali.cashguo.top/Article/details/gt2trfrismr.html

[S39] C++：自定义比较器排序
来源：http://dali.yj20258.top/Article/details/gt2baoebfvv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hnqzz.top/Article/details/gt2clecrabh.html

[S40] C++：查找元素
来源：http://dali.quarkkingdee.top/Article/details/gt2vaqwtykm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hammf.cn/Article/details/gt2msdyweby.html

[S41] C++：类与构造函数
来源：http://dali.chenlongwang.top/Article/details/gt2qcomorrz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.iojbl.cn/Article/details/gt2rrawpdar.html

[S42] C++：继承与虚函数
来源：http://dali.jianghu66.top/Article/details/gt2gxezcwxo.html

class B : public Base { public: void f() override {} };
来源：http://dali.shangyingyoupin.top/Article/details/gt2rfalkyrf.html

[S43] C++：智能指针
来源：http://dali.yvedp.cn/Article/details/gt2etsbdjlb.html

auto p = std::make_unique<int>(5);
来源：http://dali.cqqwz.cn/Article/details/gt2twyoqgqv.html

[S44] C++：引用传参
来源：http://dali.zdqjudy.top/Article/details/gt2fqumrgyg.html

void inc(int &x) { ++x; }
来源：http://dali.tianlin.xyz/Article/details/gt2hnmiehav.html

[S45] C++：lambda
来源：http://dali.svipenyu.cn/Article/details/gt2gfqsgcie.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.chenjidiqi.icu/Article/details/gt2hfusdftb.html

[S46] C++：函数模板
来源：http://dali.cashguo.top/Article/details/gt2zmwlptme.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.bjfxy.top/Article/details/gt2ffdyhkah.html

[S47] C++：结构化绑定遍历
来源：http://dali.wangshuangyany.cn/Article/details/gt2ifwvahhn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yueranfly.top/Article/details/gt2qexbpxgs.html

[S48] C++：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gt2urkvlzva.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.aizwys.cn/Article/details/gt2etwoecvu.html

while (std::getline(in, line)) { }
来源：http://dali.zhiwuduotai.top/Article/details/gt2bcljnjhh.html

[S49] C++：写文件
来源：http://dali.feifeiyinyue.top/Article/details/gt2rnmdabjr.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.mhx1999.top/Article/details/gt2kanjxwle.html

[S50] C++：格式化数字
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jwtocbgs.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gotoacloud.top/Article/details/gt2fltpiiqn.html

[S51] C++：显式类型转换
来源：http://dali.xuetiantiany.cn/Article/details/gt2keqednlp.html

static_cast<double>(a) / b
来源：http://dali.xinyue.icu/Article/details/gt2hfgxywzy.html

[S52] C++：const 与 noexcept
来源：http://dali.nanxuanxn.top/Article/details/gt2ejgmkatv.html

int size() const noexcept { return n_; }
来源：http://dali.yj202588.top/Article/details/gt2gvhbhslx.html

[S53] C++：移动语义
来源：http://dali.yj20258.top/Article/details/gt2jnnhmqoq.html

std::vector<int> w = std::move(v);
来源：http://dali.pycfn.com/Article/details/gt2cvrbklqo.html

[S54] C++：异常处理
来源：http://dali.yuxming.cn/Article/details/gt2tkxntghv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.nwbrower.top/Article/details/gt2kurgebsy.html

[S55] C++：结构化绑定
来源：http://dali.shanyushiyangtech.top/Article/details/gt2gwqgbwrb.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.316326.xyz/Article/details/gt2taikvgor.html

[S56] C++：optional
来源：http://dali.nwbrower.top/Article/details/gt2ghzotwna.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.haohaochexian.top/Article/details/gt2anygzxwt.html

[S57] C++：编译期常量
来源：http://dali.yj20258.top/Article/details/gt2tyzhmato.html

constexpr int N = 10;
来源：http://dali.haohaochexian.top/Article/details/gt2rtbhlvgc.html

[S58] C++：命名空间
来源：http://dali.sysykeji.top/Article/details/gt2htfciqvl.html

namespace ns { int f() { return 1; } }
来源：http://dali.yuanzhike.top/Article/details/gt2stooqlvw.html

[S59] C++：静态断言
来源：http://dali.xziqi.cn/Article/details/gt2zzulrfqy.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xylfe.cn/Article/details/gt2vlwqakfd.html

[S60] C++：遍历并删除元素
来源：http://dali.xinyue.icu/Article/details/gt2nukfhqlz.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.nanxuanxn.top/Article/details/gt2thnynluz.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2wtmmjygb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.dianchejie.cn/Article/details/gt2mfwevfcz.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gt2kfssprrd.html

[T01] Kotlin：Hello World
来源：http://dali.aibaodan.cn/Article/details/gt2uccrxdha.html

println("Hello")
来源：http://dali.yj202588.top/Article/details/gt2jucxwhmy.html

[T02] Kotlin：变量
来源：http://dali.ybcxt.top/Article/details/gt2ygvoldbm.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2svcfsbpn.html

[T03] Kotlin：字符串模板
来源：http://dali.nanxinkj.top/Article/details/gt2dqnygtkl.html

"值: $b"
来源：http://dali.shangyingyoupin.top/Article/details/gt2ryywimyb.html

[T04] Kotlin：空安全
来源：http://dali.svipenyu.cn/Article/details/gt2vspydhgr.html

val n: String? = null;  n?.length
来源：http://dali.kuanghao11.cn/Article/details/gt2hebvojlx.html

[T05] Kotlin：when 表达式
来源：http://dali.sxryk.cn/Article/details/gt2lqcupjqe.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.birdmap.top/Article/details/gt2jkgmyvrn.html

[T06] Kotlin：集合映射
来源：http://dali.yanxiufei.cn/Article/details/gt2jlwzevye.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hywenlv.cn/Article/details/gt2iovwiflg.html

[T07] Kotlin：集合过滤
来源：http://dali.snrcjt.cn/Article/details/gt2nvwvcufi.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.dashuyun.cn/Article/details/gt2eythksru.html

[T08] Kotlin：数据类
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ecughmef.html

data class User(val name: String, val age: Int)
来源：http://dali.yangfankeji.com/Article/details/gt2hhlbxhtw.html

[T09] Kotlin：扩展函数
来源：http://dali.zdqjudy.top/Article/details/gt2qnepcqxa.html

fun String.exclaim() = this + "!"
来源：http://dali.daria6918.cn/Article/details/gt2lyufwsgd.html

[T10] Kotlin：默认参数
来源：http://dali.cdnleiting.top/Article/details/gt2twgynbfn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.dashuyun.cn/Article/details/gt2twxexwuc.html

[T11] Kotlin：协程
来源：http://dali.jlsjyb.cn/Article/details/gt2ttfrhtdu.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.wangdashe.top/Article/details/gt2fdudgkij.html

[T12] Kotlin：解构声明
来源：http://dali.ybcxt.top/Article/details/gt2bssshezo.html

val (a, b) = Pair(1, 2)
来源：http://dali.pengpengdd.cyou/Article/details/gt2avrgonym.html

[T13] Kotlin：只读 Map
来源：http://dali.fengsongda.top/Article/details/gt2izdookvs.html

val m = mapOf("a" to 1)
来源：http://dali.jianghu66.top/Article/details/gt2zeponkhz.html

[T14] Kotlin：循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lzkgoclj.html

for (i in 1..10) println(i)
来源：http://dali.xylfe.cn/Article/details/gt2ccanueyr.html

[T15] Kotlin：接口
来源：http://dali.iojbl.cn/Article/details/gt2bqehehge.html

interface Shape { fun area(): Double }
来源：http://dali.ivvv.top/Article/details/gt2xwmorrnq.html

[T16] Swift：Hello World
来源：http://dali.sysykeji.top/Article/details/gt2fnhcabak.html

print("Hello")
来源：http://dali.xinyue.icu/Article/details/gt2grtwmaca.html

[T17] Swift：变量与常量
来源：http://dali.aibaodan.cn/Article/details/gt2uvkszlzr.html

var a = 1;  let b = 2
来源：http://dali.zhixingplan.top/Article/details/gt2ehlwzkwa.html

[T18] Swift：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gt2vumpdqth.html

"值: \(b)"
来源：http://dali.chenjidiqi.icu/Article/details/gt2vwbuqmuw.html

[T19] Swift：可选绑定
来源：http://dali.yj202588.top/Article/details/gt2gmgicjze.html

if let n = opt { print(n) }
来源：http://dali.c1oappe.top/Article/details/gt2qeozhmzi.html

[T20] Swift：数组操作
来源：http://dali.nanxuanxn.top/Article/details/gt2jkxuxtzn.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.svipenyu.cn/Article/details/gt2nzmabusl.html

[T21] Swift：遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2xpreafic.html

for x in a { print(x) }
来源：http://dali.ybcxt.top/Article/details/gt2hhlsrzah.html

[T22] Swift：字典
来源：http://dali.gotoacloud.top/Article/details/gt2hrmjduir.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jlsjyb.cn/Article/details/gt2wqzssjnu.html

[T23] Swift：函数
来源：http://dali.yvedp.cn/Article/details/gt2empcfvdn.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sysykeji.top/Article/details/gt2slnhdujk.html

[T24] Swift：闭包
来源：http://dali.cucudq.cn/Article/details/gt2zhgucqey.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.pycfn.com/Article/details/gt2ttisyjtq.html

[T25] Swift：结构体
来源：http://dali.yanxiufei.cn/Article/details/gt2patplmee.html

struct P { var x: Int }
来源：http://dali.sxryk.cn/Article/details/gt2rqzlguyk.html

[T26] Swift：类与重写
来源：http://dali.ivvv.top/Article/details/gt2wxwoonre.html

class A: Base { override func f() {} }
来源：http://dali.gotoacloud.top/Article/details/gt2erwbzurz.html

[T27] Swift：错误处理
来源：http://dali.zhongyouzk.top/Article/details/gt2uworfahc.html

do { try f() } catch { print(error) }
来源：http://dali.gaohongyu789.top/Article/details/gt2reqjzxbl.html

[T28] Swift：枚举
来源：http://dali.meibo888.top/Article/details/gt2hhxihbmi.html

enum Color { case red, green }
来源：http://dali.jianghu66.top/Article/details/gt2noiwkmgw.html

[T29] Swift：guard 提前返回
来源：http://dali.ppjwa.cn/Article/details/gt2yjkqetpg.html

guard let x = opt else { return }
来源：http://dali.guowangkeji.top/Article/details/gt2dpyrxomj.html

[T30] Swift：协议
来源：http://dali.wangshuangyany.cn/Article/details/gt2jfqjeonf.html

protocol Shape { func area() -> Double }
来源：http://dali.xuetiantiany.cn/Article/details/gt2wunevnqn.html

[T31] Lua：Hello World
来源：http://dali.daxiang520.top/Article/details/gt2fuiagyln.html

print("Hello")
来源：http://dali.meibo888.top/Article/details/gt2kbhglfcc.html

[T32] Lua：局部变量
来源：http://dali.zycfv.cn/Article/details/gt2cqjbcvgb.html

local a = 1
来源：http://dali.shzxlz.cn/Article/details/gt2dbyhcupq.html

[T33] Lua：表（数组）
来源：http://dali.yueranfly.top/Article/details/gt2jevgoimo.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hongshengwenyu.top/Article/details/gt2szigbiwy.html

[T34] Lua：遍历表
来源：http://dali.hywenlv.cn/Article/details/gt2sodkgxqa.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.birdmap.top/Article/details/gt2gkhzemld.html

[T35] Lua：字典表
来源：http://dali.cdnleiting.top/Article/details/gt2oswdupso.html

local d = { a = 1 };  d.b = 2
来源：http://dali.hywenlv.cn/Article/details/gt2dmolemkl.html

[T36] Lua：函数
来源：http://dali.wangshuangyany.cn/Article/details/gt2riekowpi.html

function add(a, b) return a + b end
来源：http://dali.yj20258.top/Article/details/gt2altijfri.html

[T37] Lua：字符串拼接
来源：http://dali.yuanzhike.top/Article/details/gt2eyurkckv.html

"a" .. "b"
来源：http://dali.cheryme.top/Article/details/gt2oiaejqik.html

[T38] Lua：条件
来源：http://dali.chenjidiqi.icu/Article/details/gt2bejlidwd.html

if x > 0 then print("正") end
来源：http://dali.jianghu66.top/Article/details/gt2evplbjtc.html

[T39] Lua：模式匹配
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2teskakcc.html

string.find(s, "%d+")
来源：http://dali.ydzc1.top/Article/details/gt2chmnclbi.html

[T40] Lua：元表
来源：http://dali.zdqjudy.top/Article/details/gt2lymqprva.html

setmetatable({}, { __index = base })
来源：http://dali.jinqigufen.top/Article/details/gt2kulqeozq.html

[T41] Perl：Hello World
来源：http://dali.nwbrower.top/Article/details/gt2elswvwxr.html

print "Hello\n";
来源：http://dali.shuidangran.top/Article/details/gt2zycfwula.html

[T42] Perl：变量类型
来源：http://dali.jyoumei.cn/Article/details/gt2lzlredac.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jqgfzy.top/Article/details/gt2lrxmgrqw.html

[T43] Perl：字符串插值
来源：http://dali.redwolf501.top/Article/details/gt2qvcanbfb.html

"值: $a"
来源：http://dali.mhx1999.top/Article/details/gt2unmwqeaq.html

[T44] Perl：条件
来源：http://dali.guowangkeji.top/Article/details/gt2mqmztkzw.html

if ($a > 0) { print "正"; }
来源：http://dali.fzhhl.top/Article/details/gt2riwajxcr.html

[T45] Perl：数组遍历
来源：http://dali.tian-w.cn/Article/details/gt2txlxcnoi.html

for my $x (@arr) { print $x; }
来源：http://dali.hammf.cn/Article/details/gt2dofwlbcz.html

[T46] Perl：哈希操作
来源：http://dali.daria6918.cn/Article/details/gt2xypqavmz.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.dianchejie.cn/Article/details/gt2tnaejhkq.html

[T47] Perl：正则捕获
来源：http://dali.ybcxt.top/Article/details/gt2xnqynjzp.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.yj20258888.top/Article/details/gt2uqsbtkwr.html

[T48] Perl：正则替换
来源：http://dali.ehwqpu.com/Article/details/gt2sezqrsnk.html

$s =~ s/old/new/g;
来源：http://dali.zhixingplan.top/Article/details/gt2eglnxgql.html


<!-- 参考信息 -->