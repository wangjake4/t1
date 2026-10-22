代发 wailian999

find . -name "*.log" -type f
来源：http://dali.yuanzhike.top/Article/details/gtlbvenxzn.html

[R44] 按修改时间查找
来源：http://dali.ivvv.top/Article/details/gtvedoclck.html

find . -mtime -7 -type f
来源：http://dali.ivvv.top/Article/details/gtdqevjluy.html

[R45] 批量删除
来源：http://dali.yongpay.top/Article/details/gtwwhrbeqz.html

find . -name "*.tmp" -delete
来源：http://dali.yonumen.top/Article/details/gtzicjlddf.html

[R46] 递归替换文件内容
来源：http://dali.hnqzz.top/Article/details/gtxhlmhnsw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yuxming.cn/Article/details/gtlbkpcutm.html

[R47] sed 单行替换
来源：http://dali.yj202588.top/Article/details/gtgdluwdqp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtqthrzbzk.html

[R48] awk 取指定列
来源：http://dali.dashuyun.cn/Article/details/gtoohlwwki.html

awk '{print $1, $3}' a.txt
来源：http://dali.0kj1m.cn/Article/details/gtvalsulwc.html

[R49] awk 带条件
来源：http://dali.fengsongda.top/Article/details/gtqpzuwdsz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.tian-w.cn/Article/details/gtzocyumpr.html

[R50] awk 求和
来源：http://dali.quarkkingdee.top/Article/details/gtspplytgl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.pycfn.com/Article/details/gtizmfljjm.html

[R51] 排序去重取前几
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbpwprckm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zycfv.cn/Article/details/gtgxbdzviv.html

[R52] 统计行数
来源：http://dali.hfpthk.cn/Article/details/gtzvmhgfuc.html

wc -l a.txt
来源：http://dali.cheryme.top/Article/details/gtmrbecdrm.html

[R53] 查看文件头与实时尾
来源：http://dali.iojbl.cn/Article/details/gtkioydgme.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.haohaochexian.top/Article/details/gtmoiwhxtn.html

[R54] 比较两个文件
来源：http://dali.ehwqpu.com/Article/details/gtaevlayyf.html

diff a.txt b.txt
来源：http://dali.gotoacloud.top/Article/details/gtzdsoeuqe.html

[R55] 压缩与解压
来源：http://dali.cdnleiting.top/Article/details/gtfqbdigeo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.316326.xyz/Article/details/gtctioyona.html

[R56] 远程拷贝
来源：http://dali.jqgufenzy.top/Article/details/gtakciaqvk.html

scp file user@host:/path/
来源：http://dali.zhoulong.xyz/Article/details/gtffgjzryf.html

[R57] 远程执行命令
来源：http://dali.yj20258888.top/Article/details/gtezxelvtm.html

ssh user@host 'uptime'
来源：http://dali.yangfankeji.com/Article/details/gtwsjukznm.html

[R58] 下载文件
来源：http://dali.yj20258.top/Article/details/gtixxjkaim.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xuanzx.com/Article/details/gttnzhuxdp.html

[R59] 发 POST JSON
来源：http://dali.ivvv.top/Article/details/gttsooxnht.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.cucudq.cn/Article/details/gtihgejlzi.html

[R60] 只看 HTTP 状态码
来源：http://dali.sxryk.cn/Article/details/gtvinltijk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ivvv.top/Article/details/gtfwaifrjy.html

[R61] 磁盘占用
来源：http://dali.hammf.cn/Article/details/gtezgazxtb.html

df -h;  du -sh *
来源：http://dali.fzhhl.top/Article/details/gtdyfywqso.html

[R62] 找最占空间的文件
来源：http://dali.xziqi.cn/Article/details/gtrmpixfla.html

du -ah . | sort -rh | head -10
来源：http://dali.jinqigfzy.top/Article/details/gthbpuucpm.html

[R63] 内存与进程
来源：http://dali.xziqi.cn/Article/details/gtduhagdee.html

free -h;  ps aux | grep nginx
来源：http://dali.ppjwa.cn/Article/details/gtpevvjogq.html

[R64] 结束进程
来源：http://dali.yuxming.cn/Article/details/gtnbnackmb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.havefunace.top/Article/details/gtjpnlmbwg.html

[R65] 查看端口占用
来源：http://dali.ppjwa.cn/Article/details/gtritzglcn.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.kuanghao11.cn/Article/details/gtvkztqsgl.html

[R66] 定时任务
来源：http://dali.yueranfly.top/Article/details/gtgbvuehpb.html

crontab -e;  crontab -l
来源：http://dali.daxiang520.top/Article/details/gtansewpqj.html

[R67] 生成随机十六进制串
来源：http://dali.feifeiyinyue.top/Article/details/gtxjqozehb.html

openssl rand -hex 16
来源：http://dali.havefunace.top/Article/details/gtlnigpvvj.html

[R68] 计算文件校验值
来源：http://dali.hnqzz.top/Article/details/gtqnlegnbo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gtagnuydgv.html

[R69] 生成随机密码
来源：http://dali.jinqigfzy.top/Article/details/gtiwwknqhp.html

head -c 16 /dev/urandom | base64
来源：http://dali.hywenlv.cn/Article/details/gtfmvolcuu.html

[R70] 时间戳与互转
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwqscbkkx.html

date +%s;  date -d @1700000000
来源：http://dali.vqdsnc.cn/Article/details/gtyajlturp.html

[R71] 日期格式化
来源：http://dali.jinqigufen.top/Article/details/gtaryxuawg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.wangdashe.top/Article/details/gtffbnzarr.html

[R72] 等待端口就绪
来源：http://dali.yueranfly.top/Article/details/gtvxkocpqb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.bjfxy.top/Article/details/gtmcrmmmxn.html

[R73] 分割大日志
来源：http://dali.chenjidiqi.icu/Article/details/gtbwgakmky.html

split -l 1000 big.log part_
来源：http://dali.haohaochexian.top/Article/details/gtczegnacs.html

[R74] 批量重命名
来源：http://dali.ybcxt.top/Article/details/gtkfwpogde.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yj20258888.top/Article/details/gtxcnwrgmo.html

[R75] 导出环境变量
来源：http://dali.redwolf501.top/Article/details/gtvntionid.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.daria6918.cn/Article/details/gtsfeilqnf.html

[R76] 使用临时文件
来源：http://dali.jlsjyb.cn/Article/details/gtxbouonrt.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258888.top/Article/details/gtdskygeex.html

[R77] 读取用户输入
来源：http://dali.nwbrower.top/Article/details/gtrcpqkofb.html

read -rp "请输入: " ans
来源：http://dali.sweek.top/Article/details/gtcbdikyrn.html

[R78] 交互式菜单
来源：http://dali.zycfv.cn/Article/details/gtmhuvpyqh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jqgufenzy.top/Article/details/gtwqcvvbqe.html

[R79] 解析命令行选项
来源：http://dali.daxiang520.top/Article/details/gtqqphqfwm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.9152youxi.cn/Article/details/gtzloiguem.html

[R80] 查看脚本执行耗时
来源：http://dali.9152youxi.cn/Article/details/gtsjdllfii.html

time ./run.sh
来源：http://dali.gotoacloud.top/Article/details/gtjlteitkm.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtkzwaezml.html

S. C / C++ 专题
来源：http://dali.fzhhl.top/Article/details/gtwyyhsdqe.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gttjntgmqy.html

[S01] C：Hello World
来源：http://dali.xinyue.icu/Article/details/gthnopsuau.html

#include <stdio.h>
来源：http://dali.gotoacloud.top/Article/details/gtctuxpqrf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jqgufenzy.top/Article/details/gtlizdygtt.html

[S02] C：变量与格式化输出
来源：http://dali.cqqwz.cn/Article/details/gtsdkxuvrl.html

int a = 10; printf("%d\n", a);
来源：http://dali.xuanzx.com/Article/details/gtspnmuiqh.html

[S03] C：读入整数
来源：http://dali.ivvv.top/Article/details/gtoljvrrhy.html

int x; scanf("%d", &x);
来源：http://dali.ppjwa.cn/Article/details/gtgkdwfejw.html

[S04] C：字符串复制
来源：http://dali.aibaodan.cn/Article/details/gtdnuszooc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsmvkzywc.html

[S05] C：字符串长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtfppityai.html

strlen(s)
来源：http://dali.svipenyu.cn/Article/details/gtpcmegbiu.html

[S06] C：字符串比较
来源：http://dali.tian-w.cn/Article/details/gtzcuywubo.html

strcmp(a, b) == 0
来源：http://dali.jqgfzy.top/Article/details/gtzdiaornm.html

[S07] C：数组遍历求和
来源：http://dali.ppjwa.cn/Article/details/gtezokbhtx.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jiagoushi.top/Article/details/gtrkknflcu.html

[S08] C：动态内存分配与释放
来源：http://dali.meibo888.top/Article/details/gtfwuhvplr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nanxinkj.top/Article/details/gtodmqamgh.html

[S09] C：结构体定义与初始化
来源：http://dali.jiagoushi.top/Article/details/gttgxcddaj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.fengsongda.top/Article/details/gtftcmhffx.html

[S10] C：指针与解引用
来源：http://dali.sxryk.cn/Article/details/gtehkaqwbq.html

int *p = &a;  *p = 5;
来源：http://dali.hnxiangtu.top/Article/details/gttmkndnwn.html

[S11] C：逐行读文件
来源：http://dali.guowangkeji.top/Article/details/gtapothfrz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.haohaochexian.top/Article/details/gtwztdkipu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ybcxt.top/Article/details/gtiooymveb.html

fclose(f);
来源：http://dali.zycfv.cn/Article/details/gtvqyftiaw.html

[S12] C：写文件
来源：http://dali.jqgfzy.top/Article/details/gtatvmwxmm.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.nwbrower.top/Article/details/gtrfqjxpfq.html

[S13] C：宏定义
来源：http://dali.svipenyu.cn/Article/details/gtvnjghhwm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.guannengcc.top/Article/details/gtrhavjdjr.html

[S14] C：枚举
来源：http://dali.chenlongwang.top/Article/details/gtqreudqzs.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zycfv.cn/Article/details/gtlibsiwgq.html

[S15] C：类型转换
来源：http://dali.chenjidiqi.icu/Article/details/gtgfnoumxc.html

(double) a / b
来源：http://dali.chenlongwang.top/Article/details/gtiwgiffwh.html

[S16] C：位操作置位
来源：http://dali.yangfankeji.com/Article/details/gtcnnlicwj.html

x |= (1 << 3);
来源：http://dali.gotoacloud.top/Article/details/gteqoczsga.html

[S17] C：安全拼接字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbxpdldhr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yj20258888.top/Article/details/gtunhqsseg.html

[S18] C：命令行参数
来源：http://dali.sufxvd.cn/Article/details/gtepfwulsa.html

int main(int argc, char **argv)
来源：http://dali.yueranfly.top/Article/details/gtqkzljsct.html

[S19] C：快速排序
来源：http://dali.xuetiantiany.cn/Article/details/gthwvsgeib.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.mhx1999.top/Article/details/gthpralwhu.html

[S20] C：二分查找
来源：http://dali.hnxiangtu.top/Article/details/gtoqkiyait.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.nwbrower.top/Article/details/gtlzqixjrn.html

[S21] C：字符类别判断
来源：http://dali.shuidangran.top/Article/details/gtwluxtkum.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.yj202588.top/Article/details/gthszayddz.html

[S22] C：字符串转数字
来源：http://dali.pycfn.com/Article/details/gtdmfyjbvr.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.chenjidiqi.icu/Article/details/gtjkgngvma.html

[S23] C：随机数
来源：http://dali.havefunace.top/Article/details/gtzjeqagdp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.quarkkingdee.top/Article/details/gtgocmpzzw.html

[S24] C：获取本地时间
来源：http://dali.yvedp.cn/Article/details/gtjjjiuado.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtprbctbcq.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gtugrckdgq.html

memcpy(dst, src, n);
来源：http://dali.zhengqikj.top/Article/details/gtoqxxkaif.html

[S26] C：内存清零
来源：http://dali.jlsjyb.cn/Article/details/gtqeefvjnu.html

memset(a, 0, sizeof a);
来源：http://dali.yueranfly.top/Article/details/gtuocbxuve.html

[S27] C：定义常量
来源：http://dali.shangyingyoupin.top/Article/details/gtjjgnhvtc.html

const double PI = 3.14159;
来源：http://dali.smart0.xyz/Article/details/gttxbtmfcc.html

[S28] C：静态变量
来源：http://dali.bjfxy.top/Article/details/gtmrkmtvmw.html

static int counter = 0;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaxojvebf.html

[S29] C：变参函数
来源：http://dali.c1oappe.top/Article/details/gthbhpbkbe.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.xuetiantiany.cn/Article/details/gtpltiwosu.html

[S30] C：头文件保护
来源：http://dali.meibo888.top/Article/details/gtkaxxhdzh.html

#ifndef X_H
来源：http://dali.zhixingplan.top/Article/details/gtlqslmmzb.html

#define X_H
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpsabkwpo.html

#endif
来源：http://dali.wangshuangyany.cn/Article/details/gtzbmmdzvh.html

[S31] C++：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtpncmpbdp.html

#include <iostream>
来源：http://dali.yonumen.top/Article/details/gtxlfpsjjq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenlongwang.top/Article/details/gtecmeubmf.html

[S32] C++：字符串
来源：http://dali.jinqigfzy.top/Article/details/gtymzxxrgv.html

std::string s = "hi";  s += "!";
来源：http://dali.svipenyu.cn/Article/details/gtujkpmfua.html

[S33] C++：vector 增删
来源：http://dali.gotoacloud.top/Article/details/gtdmeikmvg.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.haohaochexian.top/Article/details/gtjubejofi.html

[S34] C++：遍历 vector
来源：http://dali.yonumen.top/Article/details/gtizzreezu.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.tian-w.cn/Article/details/gtdwbqajnq.html

[S35] C++：map
来源：http://dali.shzxlz.cn/Article/details/gtitlbizop.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigfzy.top/Article/details/gtnpxfoueh.html

[S36] C++：unordered_map
来源：http://dali.cucudq.cn/Article/details/gtiatgsvji.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gtxcoayurp.html

[S37] C++：set
来源：http://dali.bjfxy.top/Article/details/gtsfhcjffc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.316326.xyz/Article/details/gtpxfcemio.html

[S38] C++：排序
来源：http://dali.jiagoushi.top/Article/details/gtbwtdxaln.html

std::sort(v.begin(), v.end());
来源：http://dali.jqgfzy.top/Article/details/gtpiaqacnv.html

[S39] C++：自定义比较器排序
来源：http://dali.zhoulong.xyz/Article/details/gtgqkcazcf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yuanzhike.top/Article/details/gtrkzeczqe.html

[S40] C++：查找元素
来源：http://dali.ydzc1.top/Article/details/gtyglrigii.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.sysykeji.top/Article/details/gthfnoahsr.html

[S41] C++：类与构造函数
来源：http://dali.xuetiantiany.cn/Article/details/gtudzasgib.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.dashuyun.cn/Article/details/gtuozpixvd.html

[S42] C++：继承与虚函数
来源：http://dali.guowangkeji.top/Article/details/gttxkcaaou.html

class B : public Base { public: void f() override {} };
来源：http://dali.jlsjyb.cn/Article/details/gtvigghhei.html

[S43] C++：智能指针
来源：http://dali.mhx1999.top/Article/details/gtmtnllmur.html

auto p = std::make_unique<int>(5);
来源：http://dali.ydzc1.top/Article/details/gtzljdliwo.html

[S44] C++：引用传参
来源：http://dali.fzhhl.top/Article/details/gttjbifmhk.html

void inc(int &x) { ++x; }
来源：http://dali.fengsongda.top/Article/details/gtwkmomgfs.html

[S45] C++：lambda
来源：http://dali.birdmap.top/Article/details/gtlouamedv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.haohaochexian.top/Article/details/gtmshstbjq.html

[S46] C++：函数模板
来源：http://dali.xylfe.cn/Article/details/gtqgozfwkc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.andypj.xyz/Article/details/gtizyfdmdp.html

[S47] C++：结构化绑定遍历
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlxijnhsq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.bjfxy.top/Article/details/gtyxvfjigs.html

[S48] C++：逐行读文件
来源：http://dali.zycfv.cn/Article/details/gtxeqxqevd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.meibo888.top/Article/details/gtvojyepah.html

while (std::getline(in, line)) { }
来源：http://dali.xylfe.cn/Article/details/gtquskforc.html

[S49] C++：写文件
来源：http://dali.yuanzhike.top/Article/details/gtybrdxkrl.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.tian-w.cn/Article/details/gtdfbvndbe.html

[S50] C++：格式化数字
来源：http://dali.jlsjyb.cn/Article/details/gttqtilpnt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cheryme.top/Article/details/gterkovjee.html

[S51] C++：显式类型转换
来源：http://dali.sufxvd.cn/Article/details/gtrxjxfuzq.html

static_cast<double>(a) / b
来源：http://dali.gogol.net.cn/Article/details/gtucmohixr.html

[S52] C++：const 与 noexcept
来源：http://dali.tanke756.top/Article/details/gtdlhgrayb.html

int size() const noexcept { return n_; }
来源：http://dali.shzxlz.cn/Article/details/gtmftdvwbl.html

[S53] C++：移动语义
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjnqkmcsf.html

std::vector<int> w = std::move(v);
来源：http://dali.yangfankeji.com/Article/details/gtcjxqldcz.html

[S54] C++：异常处理
来源：http://dali.gotoacloud.top/Article/details/gtrcuqerrl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yj20258888.top/Article/details/gtbggwfrwy.html

[S55] C++：结构化绑定
来源：http://dali.pengpengdd.cyou/Article/details/gtynfjrfjw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.aizwys.cn/Article/details/gtkdiftutl.html

[S56] C++：optional
来源：http://dali.hywenlv.cn/Article/details/gthlufayhg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yanxiufei.cn/Article/details/gtzxyzikbi.html

[S57] C++：编译期常量
来源：http://dali.svipenyu.cn/Article/details/gtilyjqann.html

constexpr int N = 10;
来源：http://dali.xinyue.icu/Article/details/gtdtofqiol.html

[S58] C++：命名空间
来源：http://dali.hnqzz.top/Article/details/gtxsvdjriw.html

namespace ns { int f() { return 1; } }
来源：http://dali.cqqwz.cn/Article/details/gtocdklatq.html

[S59] C++：静态断言
来源：http://dali.shzxlz.cn/Article/details/gtzbmmlchg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.snrcjt.cn/Article/details/gtpswoxbip.html

[S60] C++：遍历并删除元素
来源：http://dali.dashuyun.cn/Article/details/gtzfmkmxei.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlgfjrvnq.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtuerlysyv.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.gotoacloud.top/Article/details/gtotmqwbrd.html

================================================================================
来源：http://dali.yongpay.top/Article/details/gticlgvqkw.html

[T01] Kotlin：Hello World
来源：http://dali.yuxming.cn/Article/details/gtgmjsirsd.html

println("Hello")
来源：http://dali.yvedp.cn/Article/details/gtzuahroxn.html

[T02] Kotlin：变量
来源：http://dali.yj202588.top/Article/details/gtdmudbjny.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hongshengwenyu.top/Article/details/gtabgzvycg.html

[T03] Kotlin：字符串模板
来源：http://dali.havefunace.top/Article/details/gtgqrwewyc.html

"值: $b"
来源：http://dali.yueranfly.top/Article/details/gtwkzewdym.html

[T04] Kotlin：空安全
来源：http://dali.ybcxt.top/Article/details/gtpiucswbi.html

val n: String? = null;  n?.length
来源：http://dali.cheryme.top/Article/details/gthmtglpzt.html

[T05] Kotlin：when 表达式
来源：http://dali.jiagoushi.top/Article/details/gtwjqtqpbw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinqigfzy.top/Article/details/gtagzzwxhy.html

[T06] Kotlin：集合映射
来源：http://dali.shanyushiyangkeji.top/Article/details/gtifiwjhce.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.dianchejie.cn/Article/details/gtsrtwbpky.html

[T07] Kotlin：集合过滤
来源：http://dali.fengsongda.top/Article/details/gtfnoknmfp.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yangfankeji.com/Article/details/gtqqxzmyso.html

[T08] Kotlin：数据类
来源：http://dali.zhiwuduotai.top/Article/details/gtmyswsnft.html

data class User(val name: String, val age: Int)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtofdcbwxg.html

[T09] Kotlin：扩展函数
来源：http://dali.kuanghao11.cn/Article/details/gtwzkwoars.html

fun String.exclaim() = this + "!"
来源：http://dali.gaohongyu789.top/Article/details/gthqelcacl.html

[T10] Kotlin：默认参数
来源：http://dali.c1oappe.top/Article/details/gtgecerxhn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.aibaodan.cn/Article/details/gtfakvifpx.html

[T11] Kotlin：协程
来源：http://dali.yj202588.top/Article/details/gtfykfgosj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xuanzx.com/Article/details/gtbrfubxzd.html

[T12] Kotlin：解构声明
来源：http://dali.haohaochexian.top/Article/details/gthqicdesj.html

val (a, b) = Pair(1, 2)
来源：http://dali.xuanzx.com/Article/details/gtsaqiazxi.html

[T13] Kotlin：只读 Map
来源：http://dali.shzxlz.cn/Article/details/gtrufbrglm.html

val m = mapOf("a" to 1)
来源：http://dali.nwbrower.top/Article/details/gtyohhkgak.html

[T14] Kotlin：循环
来源：http://dali.tian-w.cn/Article/details/gtipudhapn.html

for (i in 1..10) println(i)
来源：http://dali.yj202588.top/Article/details/gtsaijgmii.html

[T15] Kotlin：接口
来源：http://dali.smart0.xyz/Article/details/gtlwmqpbtu.html

interface Shape { fun area(): Double }
来源：http://dali.pengpengdd.cyou/Article/details/gtdouncacv.html

[T16] Swift：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtehmydoeh.html

print("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gtedeonhrh.html

[T17] Swift：变量与常量
来源：http://dali.feifeiyinyue.top/Article/details/gtryhpiuci.html

var a = 1;  let b = 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtugsdsqwf.html

[T18] Swift：字符串插值
来源：http://dali.daria6918.cn/Article/details/gttyfozjds.html

"值: \(b)"
来源：http://dali.cheryme.top/Article/details/gthytbbwuc.html

[T19] Swift：可选绑定
来源：http://dali.meibo888.top/Article/details/gtaurfuaik.html

if let n = opt { print(n) }
来源：http://dali.yvedp.cn/Article/details/gtoznrphni.html

[T20] Swift：数组操作
来源：http://dali.smart0.xyz/Article/details/gtfxcghnij.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.meibo888.top/Article/details/gtnahycoqg.html

[T21] Swift：遍历
来源：http://dali.cashguo.top/Article/details/gtarloeyec.html

for x in a { print(x) }
来源：http://dali.yanxiufei.cn/Article/details/gteedmoxeu.html

[T22] Swift：字典
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjbucgwra.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.kuanghao11.cn/Article/details/gtrftvyqoa.html

[T23] Swift：函数
来源：http://dali.jqgufenzy.top/Article/details/gtuwrciwit.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.nwbrower.top/Article/details/gtjaxscqkf.html

[T24] Swift：闭包
来源：http://dali.chenzaomai.com/Article/details/gtzqrwjrqc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gtiswtxxar.html

[T25] Swift：结构体
来源：http://dali.yj20258.top/Article/details/gtbycncwtu.html

struct P { var x: Int }
来源：http://dali.yanxiufei.cn/Article/details/gtfbrfvfap.html

[T26] Swift：类与重写
来源：http://dali.gotoacloud.top/Article/details/gttncmagnw.html

class A: Base { override func f() {} }
来源：http://dali.c1oappe.top/Article/details/gtnslefkqp.html

[T27] Swift：错误处理
来源：http://dali.nwbrower.top/Article/details/gtiffqboif.html

do { try f() } catch { print(error) }
来源：http://dali.wangshuangyany.cn/Article/details/gtmunexxkn.html

[T28] Swift：枚举
来源：http://dali.gogol.net.cn/Article/details/gtniokurov.html

enum Color { case red, green }
来源：http://dali.daxiang520.top/Article/details/gtwqtfmkpr.html

[T29] Swift：guard 提前返回
来源：http://dali.yj202588.top/Article/details/gtzvqowomv.html

guard let x = opt else { return }
来源：http://dali.vqdsnc.cn/Article/details/gtpfcltovi.html

[T30] Swift：协议
来源：http://dali.tian-w.cn/Article/details/gtvormlouw.html

protocol Shape { func area() -> Double }
来源：http://dali.gogol.net.cn/Article/details/gtqzyspnji.html

[T31] Lua：Hello World
来源：http://dali.jinghuilouyu.cn/Article/details/gtqfujxecq.html

print("Hello")
来源：http://dali.ybcxt.top/Article/details/gttbfixrjr.html

[T32] Lua：局部变量
来源：http://dali.hnqzz.top/Article/details/gtzbknxbbh.html

local a = 1
来源：http://dali.yuanzhike.top/Article/details/gtuouksvbm.html

[T33] Lua：表（数组）
来源：http://dali.xuetiantiany.cn/Article/details/gtrlheshpz.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.hammf.cn/Article/details/gtjuqqppog.html

[T34] Lua：遍历表
来源：http://dali.hywenlv.cn/Article/details/gtvsduopda.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jiagoushi.top/Article/details/gthmxinqkz.html

[T35] Lua：字典表
来源：http://dali.fzhhl.top/Article/details/gtmbpjchox.html

local d = { a = 1 };  d.b = 2
来源：http://dali.shuidangran.top/Article/details/gtpbfwefsu.html

[T36] Lua：函数
来源：http://dali.xinyue.icu/Article/details/gtqeivsomu.html

function add(a, b) return a + b end
来源：http://dali.tanke756.top/Article/details/gtxqbgnnbm.html

[T37] Lua：字符串拼接
来源：http://dali.vqdsnc.cn/Article/details/gtnyldjppi.html

"a" .. "b"
来源：http://dali.hnqzz.top/Article/details/gtppzxpvyk.html

[T38] Lua：条件
来源：http://dali.yvedp.cn/Article/details/gtgdxgawza.html

if x > 0 then print("正") end
来源：http://dali.guowangkeji.top/Article/details/gtrhjyvbuw.html

[T39] Lua：模式匹配
来源：http://dali.yj20258888.top/Article/details/gtfbopeuik.html

string.find(s, "%d+")
来源：http://dali.ehwqpu.com/Article/details/gtcuarzand.html

[T40] Lua：元表
来源：http://dali.ehwqpu.com/Article/details/gtttdivsni.html

setmetatable({}, { __index = base })
来源：http://dali.mhx1999.top/Article/details/gtqqiqwhkp.html

[T41] Perl：Hello World
来源：http://dali.daria6918.cn/Article/details/gtflkxrapw.html

print "Hello\n";
来源：http://dali.316326.xyz/Article/details/gtsuzyreej.html

[T42] Perl：变量类型
来源：http://dali.xylfe.cn/Article/details/gtwsspdhzp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jlsjyb.cn/Article/details/gtzmmgckjy.html

[T43] Perl：字符串插值
来源：http://dali.sysykeji.top/Article/details/gtzccutctr.html

"值: $a"
来源：http://dali.sufxvd.cn/Article/details/gtyzlsbops.html

[T44] Perl：条件
来源：http://dali.cqqwz.cn/Article/details/gtwujvjnps.html

if ($a > 0) { print "正"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtfctzhgal.html

[T45] Perl：数组遍历
来源：http://dali.tanke756.top/Article/details/gtfksbadvh.html

for my $x (@arr) { print $x; }
来源：http://dali.bjfxy.top/Article/details/gtasjhocxj.html

[T46] Perl：哈希操作
来源：http://dali.jlsjyb.cn/Article/details/gthmbyklen.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.0kj1m.cn/Article/details/gtfvcwjolf.html


<!-- 参考信息 -->