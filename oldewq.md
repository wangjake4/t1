代发 wailian999

find . -name "*.log" -type f
来源：http://dali.ehwqpu.com/Article/details/gtuvzsdecp.html

[R44] 按修改时间查找
来源：http://dali.guowangkeji.top/Article/details/gtrvqkmbyw.html

find . -mtime -7 -type f
来源：http://dali.gaohongyu789.top/Article/details/gtwuiuxalp.html

[R45] 批量删除
来源：http://dali.tian-w.cn/Article/details/gtmevmxygu.html

find . -name "*.tmp" -delete
来源：http://dali.dianchejie.cn/Article/details/gtuthhvunp.html

[R46] 递归替换文件内容
来源：http://dali.zhengqikj.top/Article/details/gtekctkxan.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhengqikj.top/Article/details/gtjaeaibdn.html

[R47] sed 单行替换
来源：http://dali.bjfxy.top/Article/details/gtnoltecwp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtpydlhqqb.html

[R48] awk 取指定列
来源：http://dali.guowangkeji.top/Article/details/gtyauwumrk.html

awk '{print $1, $3}' a.txt
来源：http://dali.yj202588.top/Article/details/gtpvlsombi.html

[R49] awk 带条件
来源：http://dali.iojbl.cn/Article/details/gtlfspmtlo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sxryk.cn/Article/details/gtnznwcrnq.html

[R50] awk 求和
来源：http://dali.0kj1m.cn/Article/details/gtkzyfgtwv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtjcloafbm.html

[R51] 排序去重取前几
来源：http://dali.aibaodan.cn/Article/details/gtczzsocrg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gtltpufzgc.html

[R52] 统计行数
来源：http://dali.guowangkeji.top/Article/details/gtczgeqgfi.html

wc -l a.txt
来源：http://dali.cucudq.cn/Article/details/gtbbowuiud.html

[R53] 查看文件头与实时尾
来源：http://dali.ehwqpu.com/Article/details/gtdsbeznqn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.redwolf501.top/Article/details/gttrsdrhiv.html

[R54] 比较两个文件
来源：http://dali.tanke756.top/Article/details/gtuqkgcbuk.html

diff a.txt b.txt
来源：http://dali.zdqjudy.top/Article/details/gtlbycicut.html

[R55] 压缩与解压
来源：http://dali.meibo888.top/Article/details/gtiovtmyog.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.9152youxi.cn/Article/details/gtmbxpaeao.html

[R56] 远程拷贝
来源：http://dali.zhoulong.xyz/Article/details/gtfyigoyjy.html

scp file user@host:/path/
来源：http://dali.fzhhl.top/Article/details/gtroamqebg.html

[R57] 远程执行命令
来源：http://dali.bjfxy.top/Article/details/gtrxyevavc.html

ssh user@host 'uptime'
来源：http://dali.hnxiangtu.top/Article/details/gtpmqircez.html

[R58] 下载文件
来源：http://dali.havefunace.top/Article/details/gtdyyzayrn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hammf.cn/Article/details/gtacqemmrb.html

[R59] 发 POST JSON
来源：http://dali.yonumen.top/Article/details/gtlnxsvlmd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.316326.xyz/Article/details/gttopxmxnk.html

[R60] 只看 HTTP 状态码
来源：http://dali.zycfv.cn/Article/details/gtuknmlmku.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.aizwys.cn/Article/details/gtcvhylgzt.html

[R61] 磁盘占用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtecwwxbxh.html

df -h;  du -sh *
来源：http://dali.gotoacloud.top/Article/details/gtvkxxacyl.html

[R62] 找最占空间的文件
来源：http://dali.sufxvd.cn/Article/details/gtkkdoeznp.html

du -ah . | sort -rh | head -10
来源：http://dali.yangfankeji.com/Article/details/gtpxgqiddw.html

[R63] 内存与进程
来源：http://dali.gotoacloud.top/Article/details/gtutfxqhhj.html

free -h;  ps aux | grep nginx
来源：http://dali.ybcxt.top/Article/details/gtlyrbtsbj.html

[R64] 结束进程
来源：http://dali.hfpthk.cn/Article/details/gtshzpaxqi.html

kill -9 $(pgrep -f app.py)
来源：http://dali.tian-w.cn/Article/details/gtyqihfqmy.html

[R65] 查看端口占用
来源：http://dali.kuanghao11.cn/Article/details/gtxsvwhbbs.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.daxiang520.top/Article/details/gtbhdkgvpj.html

[R66] 定时任务
来源：http://dali.fzhhl.top/Article/details/gtmqfwajfx.html

crontab -e;  crontab -l
来源：http://dali.gotoacloud.top/Article/details/gtlgzysbhi.html

[R67] 生成随机十六进制串
来源：http://dali.jianghu66.top/Article/details/gtnygveoto.html

openssl rand -hex 16
来源：http://dali.jianghu66.top/Article/details/gtardvyrwd.html

[R68] 计算文件校验值
来源：http://dali.redwolf501.top/Article/details/gtvnwbctyk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenlongwang.top/Article/details/gtgoxyehpa.html

[R69] 生成随机密码
来源：http://dali.xuetiantiany.cn/Article/details/gtlhiqclja.html

head -c 16 /dev/urandom | base64
来源：http://dali.c1oappe.top/Article/details/gtjeqnpzee.html

[R70] 时间戳与互转
来源：http://dali.gogol.net.cn/Article/details/gtagxnrxue.html

date +%s;  date -d @1700000000
来源：http://dali.bjfxy.top/Article/details/gtjakcsgft.html

[R71] 日期格式化
来源：http://dali.cdnleiting.top/Article/details/gtvjmmbxyt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.birdmap.top/Article/details/gtmorhyxkz.html

[R72] 等待端口就绪
来源：http://dali.yangfankeji.com/Article/details/gtnqhcaqna.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jyoumei.cn/Article/details/gtwcocexoh.html

[R73] 分割大日志
来源：http://dali.gzhubu.top/Article/details/gtvayopdrx.html

split -l 1000 big.log part_
来源：http://dali.yj20258888.top/Article/details/gtrgftxpqg.html

[R74] 批量重命名
来源：http://dali.shanyushiyangtech.top/Article/details/gtzhzjykeg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.316326.xyz/Article/details/gtyzwklzoa.html

[R75] 导出环境变量
来源：http://dali.zhiwuduotai.top/Article/details/gtsvdkanwu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hongshengwenyu.top/Article/details/gtxabatfzj.html

[R76] 使用临时文件
来源：http://dali.yueranfly.top/Article/details/gtvzrgoxei.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xylfe.cn/Article/details/gtmfjyhkzv.html

[R77] 读取用户输入
来源：http://dali.mhx1999.top/Article/details/gtatnwqche.html

read -rp "请输入: " ans
来源：http://dali.zhengqikj.top/Article/details/gtyumpxxih.html

[R78] 交互式菜单
来源：http://dali.birdmap.top/Article/details/gtiibmesum.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.nwbrower.top/Article/details/gtxzabjrnz.html

[R79] 解析命令行选项
来源：http://dali.xylfe.cn/Article/details/gtfbswvbdm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gaohongyu789.top/Article/details/gtuettlwjc.html

[R80] 查看脚本执行耗时
来源：http://dali.jiagoushi.top/Article/details/gtqnpqmkqe.html

time ./run.sh
来源：http://dali.hywenlv.cn/Article/details/gtdkxmzhhd.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gttlglppvg.html

S. C / C++ 专题
来源：http://dali.guannengcc.top/Article/details/gtowielhxk.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtmiitinhy.html

[S01] C：Hello World
来源：http://dali.svipenyu.cn/Article/details/gtclkokluj.html

#include <stdio.h>
来源：http://dali.smart0.xyz/Article/details/gtlxwxbnre.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.sufxvd.cn/Article/details/gtnownsghm.html

[S02] C：变量与格式化输出
来源：http://dali.hywenlv.cn/Article/details/gtefnobtuz.html

int a = 10; printf("%d\n", a);
来源：http://dali.hongshengwenyu.top/Article/details/gttlqalcgx.html

[S03] C：读入整数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtutofbfqo.html

int x; scanf("%d", &x);
来源：http://dali.aibaodan.cn/Article/details/gtaaruwlpw.html

[S04] C：字符串复制
来源：http://dali.zhiwuduotai.top/Article/details/gtzybmcnae.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.aibaodan.cn/Article/details/gtviyxeokr.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gtnrdrkhmi.html

strlen(s)
来源：http://dali.c1oappe.top/Article/details/gtxctnhgxo.html

[S06] C：字符串比较
来源：http://dali.yuxming.cn/Article/details/gtrexejgtv.html

strcmp(a, b) == 0
来源：http://dali.havefunace.top/Article/details/gtoltajxqn.html

[S07] C：数组遍历求和
来源：http://dali.gaohongyu789.top/Article/details/gthftvuohj.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shangyingyoupin.top/Article/details/gtzmsrcnkv.html

[S08] C：动态内存分配与释放
来源：http://dali.fzhhl.top/Article/details/gtrkuubgux.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhengqikj.top/Article/details/gtxpecnzfz.html

[S09] C：结构体定义与初始化
来源：http://dali.shanyushiyangtech.top/Article/details/gtcoxkegmj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.iojbl.cn/Article/details/gtxxnuqsgf.html

[S10] C：指针与解引用
来源：http://dali.chenlongwang.top/Article/details/gtjqubunnw.html

int *p = &a;  *p = 5;
来源：http://dali.ivvv.top/Article/details/gtezyepkqt.html

[S11] C：逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gttymhqhuq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.aizwys.cn/Article/details/gtujyzgpax.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhengqikj.top/Article/details/gtxvideaqb.html

fclose(f);
来源：http://dali.xziqi.cn/Article/details/gtnhzabegn.html

[S12] C：写文件
来源：http://dali.jinqigfzy.top/Article/details/gtoinikrnh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.andypj.xyz/Article/details/gtavrvvpwt.html

[S13] C：宏定义
来源：http://dali.jqgufenzy.top/Article/details/gtezsglfcg.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.havefunace.top/Article/details/gtpijjgmno.html

[S14] C：枚举
来源：http://dali.zhixingplan.top/Article/details/gtjheemygn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.daxiang520.top/Article/details/gtcfzqhhnl.html

[S15] C：类型转换
来源：http://dali.ybcxt.top/Article/details/gtoigzfgus.html

(double) a / b
来源：http://dali.tian-w.cn/Article/details/gtdnjnzyvu.html

[S16] C：位操作置位
来源：http://dali.daxiang520.top/Article/details/gtqismttcz.html

x |= (1 << 3);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbxhbtyaj.html

[S17] C：安全拼接字符串
来源：http://dali.tianlin.xyz/Article/details/gtdgrjoqms.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yj20258888.top/Article/details/gtfyfblbih.html

[S18] C：命令行参数
来源：http://dali.xziqi.cn/Article/details/gtoesvtzpf.html

int main(int argc, char **argv)
来源：http://dali.ydzc1.top/Article/details/gtuusglikd.html

[S19] C：快速排序
来源：http://dali.zycfv.cn/Article/details/gtrtxavyyp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.chenzaomai.com/Article/details/gtwuglutua.html

[S20] C：二分查找
来源：http://dali.meibo888.top/Article/details/gthssmefci.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.aibaodan.cn/Article/details/gtfedsmnav.html

[S21] C：字符类别判断
来源：http://dali.tian-w.cn/Article/details/gtyqslownm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.havefunace.top/Article/details/gtasjuvnnu.html

[S22] C：字符串转数字
来源：http://dali.shanyushiyangkeji.top/Article/details/gtckefdpjb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yuanzhike.top/Article/details/gtvrmgzeka.html

[S23] C：随机数
来源：http://dali.gogol.net.cn/Article/details/gtgvizphgn.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.daxiang520.top/Article/details/gtnnpgnmad.html

[S24] C：获取本地时间
来源：http://dali.andypj.xyz/Article/details/gtcxnwvasu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmghegize.html

[S25] C：内存拷贝
来源：http://dali.haohaochexian.top/Article/details/gttchkhwye.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gtbstjchvw.html

[S26] C：内存清零
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrtxxyrhq.html

memset(a, 0, sizeof a);
来源：http://dali.c1oappe.top/Article/details/gtqdrpymnw.html

[S27] C：定义常量
来源：http://dali.nanxinkj.top/Article/details/gtjkmpmfdj.html

const double PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gttucgegep.html

[S28] C：静态变量
来源：http://dali.c1oappe.top/Article/details/gtgztlpfdk.html

static int counter = 0;
来源：http://dali.sweek.top/Article/details/gtfoyflrbn.html

[S29] C：变参函数
来源：http://dali.cqqwz.cn/Article/details/gtgjhrgswm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yonumen.top/Article/details/gtvwrxskhu.html

[S30] C：头文件保护
来源：http://dali.zhengqikj.top/Article/details/gtedamitgk.html

#ifndef X_H
来源：http://dali.shuidangran.top/Article/details/gtysicknbg.html

#define X_H
来源：http://dali.vqdsnc.cn/Article/details/gtdewgqvoc.html

#endif
来源：http://dali.mhx1999.top/Article/details/gtmbcxqffe.html

[S31] C++：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gthrpmbvxg.html

#include <iostream>
来源：http://dali.aibaodan.cn/Article/details/gtehqxvebx.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zycfv.cn/Article/details/gtchvqlhbx.html

[S32] C++：字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrkpbulgg.html

std::string s = "hi";  s += "!";
来源：http://dali.daxiang520.top/Article/details/gtlrvondst.html

[S33] C++：vector 增删
来源：http://dali.gogol.net.cn/Article/details/gtqgeyjytr.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yonumen.top/Article/details/gthwynsvre.html

[S34] C++：遍历 vector
来源：http://dali.nanxuanxn.top/Article/details/gtizrjrbxw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.mhx1999.top/Article/details/gteqhedhuc.html

[S35] C++：map
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlfteanlt.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtfzyosohu.html

[S36] C++：unordered_map
来源：http://dali.yangfankeji.com/Article/details/gtbxcbxbgr.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.dianchejie.cn/Article/details/gttbnqqysw.html

[S37] C++：set
来源：http://dali.hfpthk.cn/Article/details/gtzsjoruog.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.nanxuanxn.top/Article/details/gtnneufzhj.html

[S38] C++：排序
来源：http://dali.dianchejie.cn/Article/details/gttxeyiyvf.html

std::sort(v.begin(), v.end());
来源：http://dali.ydzc1.top/Article/details/gtjprbqcwp.html

[S39] C++：自定义比较器排序
来源：http://dali.cqqwz.cn/Article/details/gtljzdwyhy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.quarkkingdee.top/Article/details/gtqhdfyyva.html

[S40] C++：查找元素
来源：http://dali.jinqigfzy.top/Article/details/gtulvgjuqj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.mhx1999.top/Article/details/gtnkntggfk.html

[S41] C++：类与构造函数
来源：http://dali.jinqigufen.top/Article/details/gtfjenplsz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hysaishi.cn/Article/details/gtosqgikho.html

[S42] C++：继承与虚函数
来源：http://dali.birdmap.top/Article/details/gtxtawjizj.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtueygtbih.html

[S43] C++：智能指针
来源：http://dali.yangfankeji.com/Article/details/gtcgubzkkg.html

auto p = std::make_unique<int>(5);
来源：http://dali.hfpthk.cn/Article/details/gtilfgiaeg.html

[S44] C++：引用传参
来源：http://dali.jinqigufen.top/Article/details/gtrblezgyl.html

void inc(int &x) { ++x; }
来源：http://dali.aibaodan.cn/Article/details/gtoyotiwhd.html

[S45] C++：lambda
来源：http://dali.cheryme.top/Article/details/gtsvczjzwf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shzxlz.cn/Article/details/gtmlnwyoaw.html

[S46] C++：函数模板
来源：http://dali.hnqzz.top/Article/details/gtnmmtwmlx.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtosvkkgip.html

[S47] C++：结构化绑定遍历
来源：http://dali.yangfankeji.com/Article/details/gtbxpblsss.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jlsjyb.cn/Article/details/gtickvfbyb.html

[S48] C++：逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gthstgeulo.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.yj20258888.top/Article/details/gtdgdwdfbh.html

while (std::getline(in, line)) { }
来源：http://dali.zhengqikj.top/Article/details/gttqcdettw.html

[S49] C++：写文件
来源：http://dali.xziqi.cn/Article/details/gtnxwqdgtz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.andypj.xyz/Article/details/gtokqyclwc.html

[S50] C++：格式化数字
来源：http://dali.gaohongyu789.top/Article/details/gtccmswowz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gtpgaldyxp.html

[S51] C++：显式类型转换
来源：http://dali.pengpengdd.cyou/Article/details/gtwmsyqgbo.html

static_cast<double>(a) / b
来源：http://dali.havefunace.top/Article/details/gtneanomhq.html

[S52] C++：const 与 noexcept
来源：http://dali.ivvv.top/Article/details/gtujcaonlh.html

int size() const noexcept { return n_; }
来源：http://dali.yangfankeji.com/Article/details/gtqijuyktz.html

[S53] C++：移动语义
来源：http://dali.snrcjt.cn/Article/details/gtirqomgmy.html

std::vector<int> w = std::move(v);
来源：http://dali.fengsongda.top/Article/details/gtvbofpeqd.html

[S54] C++：异常处理
来源：http://dali.dashuyun.cn/Article/details/gtpbasaflr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhengqikj.top/Article/details/gtndccswhg.html

[S55] C++：结构化绑定
来源：http://dali.yuxming.cn/Article/details/gtnrgkggpe.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.ydzc1.top/Article/details/gthlftpcbn.html

[S56] C++：optional
来源：http://dali.bjfxy.top/Article/details/gtovmmunxu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yongpay.top/Article/details/gtlqouztqy.html

[S57] C++：编译期常量
来源：http://dali.ybcxt.top/Article/details/gtenlsfsvk.html

constexpr int N = 10;
来源：http://dali.jqgufenzy.top/Article/details/gthruuigxy.html

[S58] C++：命名空间
来源：http://dali.jqgufenzy.top/Article/details/gtfycksykk.html

namespace ns { int f() { return 1; } }
来源：http://dali.chenlongwang.top/Article/details/gtyzbochwa.html

[S59] C++：静态断言
来源：http://dali.ehwqpu.com/Article/details/gtwyskgopx.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ybcxt.top/Article/details/gtjuolfjsz.html

[S60] C++：遍历并删除元素
来源：http://dali.guannengcc.top/Article/details/gtflvkcjat.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.svipenyu.cn/Article/details/gtqtuuebqz.html

================================================================================
来源：http://dali.xinyue.icu/Article/details/gtfzzagdxy.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.sweek.top/Article/details/gteitzvwpl.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtexictdsh.html

[T01] Kotlin：Hello World
来源：http://dali.ivvv.top/Article/details/gtevqimjxc.html

println("Hello")
来源：http://dali.hywenlv.cn/Article/details/gtohzjprhs.html

[T02] Kotlin：变量
来源：http://dali.zhengqikj.top/Article/details/gtyvrfsdlw.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.wangshuangyany.cn/Article/details/gtcqtoobxf.html

[T03] Kotlin：字符串模板
来源：http://dali.jianghu66.top/Article/details/gtqfrxjpcu.html

"值: $b"
来源：http://dali.jqgufenzy.top/Article/details/gttkxtqvow.html

[T04] Kotlin：空安全
来源：http://dali.cucudq.cn/Article/details/gtfkwtehif.html

val n: String? = null;  n?.length
来源：http://dali.ivvv.top/Article/details/gtjmxvbqqc.html

[T05] Kotlin：when 表达式
来源：http://dali.yuanzhike.top/Article/details/gtkfuntryd.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yj202588.top/Article/details/gtilzcntdv.html

[T06] Kotlin：集合映射
来源：http://dali.gaohongyu789.top/Article/details/gtghxsbicx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hnqzz.top/Article/details/gtftualkvi.html

[T07] Kotlin：集合过滤
来源：http://dali.yonumen.top/Article/details/gtnsefexho.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.yuanzhike.top/Article/details/gtrsstzwcw.html

[T08] Kotlin：数据类
来源：http://dali.jinqigufen.top/Article/details/gtvvquxtwy.html

data class User(val name: String, val age: Int)
来源：http://dali.jianghu66.top/Article/details/gtsmmepfln.html

[T09] Kotlin：扩展函数
来源：http://dali.yj202588.top/Article/details/gtnzlhzwqs.html

fun String.exclaim() = this + "!"
来源：http://dali.sxryk.cn/Article/details/gtryweehxp.html

[T10] Kotlin：默认参数
来源：http://dali.gotoacloud.top/Article/details/gtxjyckfmg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.smart0.xyz/Article/details/gtgjcadhtg.html

[T11] Kotlin：协程
来源：http://dali.hongshengwenyu.top/Article/details/gtczqhmxok.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.nwbrower.top/Article/details/gtarjumyjj.html

[T12] Kotlin：解构声明
来源：http://dali.jiagoushi.top/Article/details/gttvplklnd.html

val (a, b) = Pair(1, 2)
来源：http://dali.tian-w.cn/Article/details/gtjuouwemr.html

[T13] Kotlin：只读 Map
来源：http://dali.ybcxt.top/Article/details/gtctcefcvl.html

val m = mapOf("a" to 1)
来源：http://dali.hysaishi.cn/Article/details/gtlxmrunjp.html

[T14] Kotlin：循环
来源：http://dali.aizwys.cn/Article/details/gtqyulzeuh.html

for (i in 1..10) println(i)
来源：http://dali.hongshengwenyu.top/Article/details/gtgcysmomm.html

[T15] Kotlin：接口
来源：http://dali.0kj1m.cn/Article/details/gtwnecplbd.html

interface Shape { fun area(): Double }
来源：http://dali.yangfankeji.com/Article/details/gtvcrigpyi.html

[T16] Swift：Hello World
来源：http://dali.aizwys.cn/Article/details/gtyfkqnjri.html

print("Hello")
来源：http://dali.fengsongda.top/Article/details/gthmusuzrq.html

[T17] Swift：变量与常量
来源：http://dali.nanxinkj.top/Article/details/gtfewbbsvx.html

var a = 1;  let b = 2
来源：http://dali.tian-w.cn/Article/details/gtrikwfxdi.html

[T18] Swift：字符串插值
来源：http://dali.xziqi.cn/Article/details/gtmqlxhocc.html

"值: \(b)"
来源：http://dali.aizwys.cn/Article/details/gtuocqxprh.html

[T19] Swift：可选绑定
来源：http://dali.mhx1999.top/Article/details/gtsgodyous.html

if let n = opt { print(n) }
来源：http://dali.nwbrower.top/Article/details/gtiofylhgj.html

[T20] Swift：数组操作
来源：http://dali.aizwys.cn/Article/details/gtjwjvbjhc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkdapkcya.html

[T21] Swift：遍历
来源：http://dali.hnxiangtu.top/Article/details/gtorteoymt.html

for x in a { print(x) }
来源：http://dali.tianlin.xyz/Article/details/gtqmyjtzzo.html

[T22] Swift：字典
来源：http://dali.gotoacloud.top/Article/details/gtvozrruus.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.vqdsnc.cn/Article/details/gtqsoiobdb.html

[T23] Swift：函数
来源：http://dali.wangdashe.top/Article/details/gtxyvjknan.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sweek.top/Article/details/gthnerpvnp.html

[T24] Swift：闭包
来源：http://dali.wangshuangyany.cn/Article/details/gtviaghlyg.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.tianlin.xyz/Article/details/gtemsjoojx.html

[T25] Swift：结构体
来源：http://dali.pycfn.com/Article/details/gtftqabbjr.html

struct P { var x: Int }
来源：http://dali.redwolf501.top/Article/details/gtckroikpp.html

[T26] Swift：类与重写
来源：http://dali.xylfe.cn/Article/details/gtgsxlnciv.html

class A: Base { override func f() {} }
来源：http://dali.bjfxy.top/Article/details/gtbnozbkpq.html

[T27] Swift：错误处理
来源：http://dali.shuidangran.top/Article/details/gtywbnclmw.html

do { try f() } catch { print(error) }
来源：http://dali.jqgfzy.top/Article/details/gtiokcdcnl.html

[T28] Swift：枚举
来源：http://dali.zycfv.cn/Article/details/gtvdfrmhsz.html

enum Color { case red, green }
来源：http://dali.ybcxt.top/Article/details/gtllztfsuy.html

[T29] Swift：guard 提前返回
来源：http://dali.zhengqikj.top/Article/details/gtnofacptk.html

guard let x = opt else { return }
来源：http://dali.yueranfly.top/Article/details/gtjlujqtex.html

[T30] Swift：协议
来源：http://dali.cqqwz.cn/Article/details/gtgpunbpap.html

protocol Shape { func area() -> Double }
来源：http://dali.guowangkeji.top/Article/details/gtdpntmtja.html

[T31] Lua：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnbdbmzgm.html

print("Hello")
来源：http://dali.gogol.net.cn/Article/details/gtdmfkiric.html

[T32] Lua：局部变量
来源：http://dali.smart0.xyz/Article/details/gtxwfpuvxd.html

local a = 1
来源：http://dali.dashuyun.cn/Article/details/gtzeehcrlh.html

[T33] Lua：表（数组）
来源：http://dali.xziqi.cn/Article/details/gtmboreaey.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.sufxvd.cn/Article/details/gtyvuhjiny.html

[T34] Lua：遍历表
来源：http://dali.chenzaomai.com/Article/details/gteflbyizn.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.haohaochexian.top/Article/details/gtijtehifb.html

[T35] Lua：字典表
来源：http://dali.tianlin.xyz/Article/details/gtpiigcgfg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.guannengcc.top/Article/details/gtdlgoxihd.html

[T36] Lua：函数
来源：http://dali.cdnleiting.top/Article/details/gtmxnxkttv.html

function add(a, b) return a + b end
来源：http://dali.ywan-chungtsiang.top/Article/details/gteypabxca.html

[T37] Lua：字符串拼接
来源：http://dali.daxiang520.top/Article/details/gtnlbzlyrd.html

"a" .. "b"
来源：http://dali.bjfxy.top/Article/details/gtfeyisqup.html

[T38] Lua：条件
来源：http://dali.zycfv.cn/Article/details/gtzzwaucrk.html

if x > 0 then print("正") end
来源：http://dali.iojbl.cn/Article/details/gtnxlreqgb.html

[T39] Lua：模式匹配
来源：http://dali.sysykeji.top/Article/details/gtrqfazbfj.html

string.find(s, "%d+")
来源：http://dali.shuidangran.top/Article/details/gtmzigvqvv.html

[T40] Lua：元表
来源：http://dali.hfpthk.cn/Article/details/gtqawbhmpw.html

setmetatable({}, { __index = base })
来源：http://dali.zhongyouzk.top/Article/details/gtbtcbrbzd.html

[T41] Perl：Hello World
来源：http://dali.feifeiyinyue.top/Article/details/gtpdxzcsjt.html

print "Hello\n";
来源：http://dali.vqdsnc.cn/Article/details/gtkaplopzx.html

[T42] Perl：变量类型
来源：http://dali.9152youxi.cn/Article/details/gtmevzjtjp.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.hammf.cn/Article/details/gtfpaculfm.html

[T43] Perl：字符串插值
来源：http://dali.redwolf501.top/Article/details/gtokfnwlau.html

"值: $a"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfjiafygd.html

[T44] Perl：条件
来源：http://dali.pengpengdd.cyou/Article/details/gtrzaatner.html

if ($a > 0) { print "正"; }
来源：http://dali.zhongyouzk.top/Article/details/gtmgrklixr.html

[T45] Perl：数组遍历
来源：http://dali.jlsjyb.cn/Article/details/gthzijjzpf.html

for my $x (@arr) { print $x; }
来源：http://dali.tian-w.cn/Article/details/gtsimeovyh.html

[T46] Perl：哈希操作
来源：http://dali.jqgfzy.top/Article/details/gtqlwcrnga.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.guannengcc.top/Article/details/gtqzgoimul.html


<!-- 参考信息 -->