代发 wailian999

find . -name "*.tmp" -delete
来源：http://dali.jqgufenzy.top/Article/details/gtnyxewhgq.html

[R46] 递归替换文件内容
来源：http://dali.chenzaomai.com/Article/details/gtruzlzwcq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yonumen.top/Article/details/gtpenechoq.html

[R47] sed 单行替换
来源：http://dali.gzhubu.top/Article/details/gtjcuehgog.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gotoacloud.top/Article/details/gtlselpluy.html

[R48] awk 取指定列
来源：http://dali.pycfn.com/Article/details/gtpafqpsps.html

awk '{print $1, $3}' a.txt
来源：http://dali.xylfe.cn/Article/details/gtdfzegyda.html

[R49] awk 带条件
来源：http://dali.daxiang520.top/Article/details/gtrcfjvmit.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xylfe.cn/Article/details/gtcdpexcvc.html

[R50] awk 求和
来源：http://dali.hammf.cn/Article/details/gttosfnrcc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.vqdsnc.cn/Article/details/gtiwvjmbnz.html

[R51] 排序去重取前几
来源：http://dali.yj20258888.top/Article/details/gtvkgzafjk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hysaishi.cn/Article/details/gtecrngcjq.html

[R52] 统计行数
来源：http://dali.vqdsnc.cn/Article/details/gtlpgxnmxg.html

wc -l a.txt
来源：http://dali.gzhubu.top/Article/details/gthfixwbmc.html

[R53] 查看文件头与实时尾
来源：http://dali.ivvv.top/Article/details/gtlitexuzt.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gaohongyu789.top/Article/details/gtjhrbsklp.html

[R54] 比较两个文件
来源：http://dali.yueranfly.top/Article/details/gtouyicwjc.html

diff a.txt b.txt
来源：http://dali.gaohongyu789.top/Article/details/gtvidkpjii.html

[R55] 压缩与解压
来源：http://dali.dashuyun.cn/Article/details/gtablzhxic.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.chenjidiqi.icu/Article/details/gtvrpntbfr.html

[R56] 远程拷贝
来源：http://dali.chenjidiqi.icu/Article/details/gtmxdzgalp.html

scp file user@host:/path/
来源：http://dali.xuetiantiany.cn/Article/details/gtisuqsywo.html

[R57] 远程执行命令
来源：http://dali.shanyushiyangtech.top/Article/details/gtlexgomml.html

ssh user@host 'uptime'
来源：http://dali.sufxvd.cn/Article/details/gtoocdpimb.html

[R58] 下载文件
来源：http://dali.zhiwuduotai.top/Article/details/gtcvewwdsd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zdqjudy.top/Article/details/gtkykoirmq.html

[R59] 发 POST JSON
来源：http://dali.zhengqikj.top/Article/details/gtgthtjwpn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yj20258.top/Article/details/gtafgrygbp.html

[R60] 只看 HTTP 状态码
来源：http://dali.mhx1999.top/Article/details/gtpqnrdlhc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.guannengcc.top/Article/details/gtqbrbsalv.html

[R61] 磁盘占用
来源：http://dali.shanyushiyangtech.top/Article/details/gtjlbksjjp.html

df -h;  du -sh *
来源：http://dali.kuanghao11.cn/Article/details/gtckydhvnr.html

[R62] 找最占空间的文件
来源：http://dali.hfpthk.cn/Article/details/gtuqcffisq.html

du -ah . | sort -rh | head -10
来源：http://dali.zhoulong.xyz/Article/details/gtgpwkabcl.html

[R63] 内存与进程
来源：http://dali.smart0.xyz/Article/details/gtzzvtadln.html

free -h;  ps aux | grep nginx
来源：http://dali.zhiwuduotai.top/Article/details/gtkzwvdhfv.html

[R64] 结束进程
来源：http://dali.shanyushiyangkeji.top/Article/details/gturjinxvk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpdprmlod.html

[R65] 查看端口占用
来源：http://dali.yuxming.cn/Article/details/gtoycolzlt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shuidangran.top/Article/details/gtaeicfvrr.html

[R66] 定时任务
来源：http://dali.wangshuangyany.cn/Article/details/gtaxzncxrf.html

crontab -e;  crontab -l
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnezjnujc.html

[R67] 生成随机十六进制串
来源：http://dali.quarkkingdee.top/Article/details/gtatymhtvn.html

openssl rand -hex 16
来源：http://dali.sxryk.cn/Article/details/gtdhwyswls.html

[R68] 计算文件校验值
来源：http://dali.ybcxt.top/Article/details/gtppkptozg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.wangdashe.top/Article/details/gtmcdlfbbe.html

[R69] 生成随机密码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsrzurawj.html

head -c 16 /dev/urandom | base64
来源：http://dali.havefunace.top/Article/details/gtieafdthh.html

[R70] 时间戳与互转
来源：http://dali.iojbl.cn/Article/details/gtoficyvzs.html

date +%s;  date -d @1700000000
来源：http://dali.ydzc1.top/Article/details/gtlbphbcgf.html

[R71] 日期格式化
来源：http://dali.tanke756.top/Article/details/gtqpfjihac.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenzaomai.com/Article/details/gtpmvugeff.html

[R72] 等待端口就绪
来源：http://dali.yonumen.top/Article/details/gtipzfukkw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.wangdashe.top/Article/details/gtwbxqirrd.html

[R73] 分割大日志
来源：http://dali.shzxlz.cn/Article/details/gtjheeyiiq.html

split -l 1000 big.log part_
来源：http://dali.yueranfly.top/Article/details/gtkiiknzst.html

[R74] 批量重命名
来源：http://dali.jyoumei.cn/Article/details/gtzatoanet.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.chenlongwang.top/Article/details/gtozcdayfb.html

[R75] 导出环境变量
来源：http://dali.hfpthk.cn/Article/details/gtpeddqger.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.wangshuangyany.cn/Article/details/gtpzemohxh.html

[R76] 使用临时文件
来源：http://dali.zhengqikj.top/Article/details/gtkjnhednl.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.dianchejie.cn/Article/details/gtigsjurki.html

[R77] 读取用户输入
来源：http://dali.yuanzhike.top/Article/details/gtihkyouto.html

read -rp "请输入: " ans
来源：http://dali.9152youxi.cn/Article/details/gtgctnnzhv.html

[R78] 交互式菜单
来源：http://dali.kuanghao11.cn/Article/details/gtmrmjeycp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhoulong.xyz/Article/details/gtqtuvnnjl.html

[R79] 解析命令行选项
来源：http://dali.cashguo.top/Article/details/gtlduhkvpy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.dashuyun.cn/Article/details/gtyjhcreqx.html

[R80] 查看脚本执行耗时
来源：http://dali.dashuyun.cn/Article/details/gtfxydjtek.html

time ./run.sh
来源：http://dali.hnxiangtu.top/Article/details/gtfpvinajm.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtksznusdd.html

S. C / C++ 专题
来源：http://dali.svipenyu.cn/Article/details/gthqtdzjyt.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtuzfieqhm.html

[S01] C：Hello World
来源：http://dali.xylfe.cn/Article/details/gtqysfbdua.html

#include <stdio.h>
来源：http://dali.zhixingplan.top/Article/details/gtbydzdypf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtklzdehpe.html

[S02] C：变量与格式化输出
来源：http://dali.chenzaomai.com/Article/details/gtggisbqzf.html

int a = 10; printf("%d\n", a);
来源：http://dali.yj20258888.top/Article/details/gtpeyeluek.html

[S03] C：读入整数
来源：http://dali.gzhubu.top/Article/details/gtvoaozsus.html

int x; scanf("%d", &x);
来源：http://dali.yangfankeji.com/Article/details/gtckzvdxkn.html

[S04] C：字符串复制
来源：http://dali.hammf.cn/Article/details/gtargbrdkr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.wangshuangyany.cn/Article/details/gtctvsosqf.html

[S05] C：字符串长度
来源：http://dali.dashuyun.cn/Article/details/gtlmjdosrg.html

strlen(s)
来源：http://dali.9152youxi.cn/Article/details/gtfefurxez.html

[S06] C：字符串比较
来源：http://dali.vqdsnc.cn/Article/details/gtflqponuj.html

strcmp(a, b) == 0
来源：http://dali.jqgfzy.top/Article/details/gtyaaybcik.html

[S07] C：数组遍历求和
来源：http://dali.gzhubu.top/Article/details/gtrzlmrlfa.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hnqzz.top/Article/details/gtloavjxzb.html

[S08] C：动态内存分配与释放
来源：http://dali.yuanzhike.top/Article/details/gtbrosflkb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.aibaodan.cn/Article/details/gtpsrscmwq.html

[S09] C：结构体定义与初始化
来源：http://dali.sxryk.cn/Article/details/gtvniejzmd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.pengpengdd.cyou/Article/details/gtznmapcfi.html

[S10] C：指针与解引用
来源：http://dali.sweek.top/Article/details/gtszctyscg.html

int *p = &a;  *p = 5;
来源：http://dali.9152youxi.cn/Article/details/gtuxeamygu.html

[S11] C：逐行读文件
来源：http://dali.hysaishi.cn/Article/details/gtaooaodpz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtscpyztii.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zycfv.cn/Article/details/gtusxwbnjd.html

fclose(f);
来源：http://dali.hywenlv.cn/Article/details/gtcmdgiwyt.html

[S12] C：写文件
来源：http://dali.meibo888.top/Article/details/gtwcquxmcw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.pengpengdd.cyou/Article/details/gtymljdcxt.html

[S13] C：宏定义
来源：http://dali.shzxlz.cn/Article/details/gtubdahbmf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.fzhhl.top/Article/details/gtzygtjrew.html

[S14] C：枚举
来源：http://dali.tanke756.top/Article/details/gtmgjdiceu.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yongpay.top/Article/details/gtnnqnziev.html

[S15] C：类型转换
来源：http://dali.andypj.xyz/Article/details/gtehsbcjys.html

(double) a / b
来源：http://dali.jqgfzy.top/Article/details/gtqyzaglxe.html

[S16] C：位操作置位
来源：http://dali.feifeiyinyue.top/Article/details/gtbmqcuwfn.html

x |= (1 << 3);
来源：http://dali.zhongyouzk.top/Article/details/gtrguxfddc.html

[S17] C：安全拼接字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtpbgyrdaa.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.smart0.xyz/Article/details/gtdsubkdas.html

[S18] C：命令行参数
来源：http://dali.ivvv.top/Article/details/gtueynsali.html

int main(int argc, char **argv)
来源：http://dali.aizwys.cn/Article/details/gthhtjlnhi.html

[S19] C：快速排序
来源：http://dali.guowangkeji.top/Article/details/gtdtynkyqk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.c1oappe.top/Article/details/gtgndoufhn.html

[S20] C：二分查找
来源：http://dali.guowangkeji.top/Article/details/gtejsoycaf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gtnnqovpoq.html

[S21] C：字符类别判断
来源：http://dali.yanxiufei.cn/Article/details/gtbqvaqejq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.cashguo.top/Article/details/gtfnvvnjsl.html

[S22] C：字符串转数字
来源：http://dali.ppjwa.cn/Article/details/gtyeucuagg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zdqjudy.top/Article/details/gtkewpcjci.html

[S23] C：随机数
来源：http://dali.shuidangran.top/Article/details/gtdhwlxvib.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.birdmap.top/Article/details/gtzsoadhid.html

[S24] C：获取本地时间
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtthisrouq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gtvspicdmo.html

[S25] C：内存拷贝
来源：http://dali.dashuyun.cn/Article/details/gttobrotcd.html

memcpy(dst, src, n);
来源：http://dali.cqqwz.cn/Article/details/gtsgihuuct.html

[S26] C：内存清零
来源：http://dali.hywenlv.cn/Article/details/gtxmfyuoha.html

memset(a, 0, sizeof a);
来源：http://dali.birdmap.top/Article/details/gtulcjusqj.html

[S27] C：定义常量
来源：http://dali.nwbrower.top/Article/details/gtfjwkjqne.html

const double PI = 3.14159;
来源：http://dali.smart0.xyz/Article/details/gterpazjxp.html

[S28] C：静态变量
来源：http://dali.iojbl.cn/Article/details/gtregffzzp.html

static int counter = 0;
来源：http://dali.jyoumei.cn/Article/details/gtujtogadi.html

[S29] C：变参函数
来源：http://dali.xziqi.cn/Article/details/gtklpjgguz.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yangfankeji.com/Article/details/gtkdqajytt.html

[S30] C：头文件保护
来源：http://dali.jqgfzy.top/Article/details/gtqafmzyeo.html

#ifndef X_H
来源：http://dali.cheryme.top/Article/details/gtxomxalkn.html

#define X_H
来源：http://dali.chenlongwang.top/Article/details/gtdbixncaa.html

#endif
来源：http://dali.cucudq.cn/Article/details/gtgezbosel.html

[S31] C++：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtpqmhpqln.html

#include <iostream>
来源：http://dali.vqdsnc.cn/Article/details/gtwcboqtjm.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.daria6918.cn/Article/details/gtpvbxqntp.html

[S32] C++：字符串
来源：http://dali.tian-w.cn/Article/details/gtpznsilwr.html

std::string s = "hi";  s += "!";
来源：http://dali.yonumen.top/Article/details/gthtcsytwy.html

[S33] C++：vector 增删
来源：http://dali.birdmap.top/Article/details/gtgnewwxkk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jiagoushi.top/Article/details/gtifnegpea.html

[S34] C++：遍历 vector
来源：http://dali.xylfe.cn/Article/details/gtgfmimgoz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yj202588.top/Article/details/gthcihfeer.html

[S35] C++：map
来源：http://dali.hnqzz.top/Article/details/gtavklvdsf.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sweek.top/Article/details/gtpfcwjwiw.html

[S36] C++：unordered_map
来源：http://dali.cheryme.top/Article/details/gtazljyiwi.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gteatffcad.html

[S37] C++：set
来源：http://dali.hywenlv.cn/Article/details/gtchoikyvu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.shangyingyoupin.top/Article/details/gtbvwaxkpu.html

[S38] C++：排序
来源：http://dali.jinqigfzy.top/Article/details/gtitsiqcwy.html

std::sort(v.begin(), v.end());
来源：http://dali.hnxiangtu.top/Article/details/gtsldeztjl.html

[S39] C++：自定义比较器排序
来源：http://dali.sysykeji.top/Article/details/gtimnebpka.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.0kj1m.cn/Article/details/gtlnthslzu.html

[S40] C++：查找元素
来源：http://dali.aizwys.cn/Article/details/gtmoyyyulw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.c1oappe.top/Article/details/gteqhtydtm.html

[S41] C++：类与构造函数
来源：http://dali.ppjwa.cn/Article/details/gtaonyfyre.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.chenlongwang.top/Article/details/gtdgfawhub.html

[S42] C++：继承与虚函数
来源：http://dali.ppjwa.cn/Article/details/gtnrgipija.html

class B : public Base { public: void f() override {} };
来源：http://dali.bjfxy.top/Article/details/gttiwvkwoy.html

[S43] C++：智能指针
来源：http://dali.zhixingplan.top/Article/details/gtzjtnuxup.html

auto p = std::make_unique<int>(5);
来源：http://dali.ydzc1.top/Article/details/gtmbvdmqru.html

[S44] C++：引用传参
来源：http://dali.jinghuilouyu.cn/Article/details/gtjzgsmziu.html

void inc(int &x) { ++x; }
来源：http://dali.zhoulong.xyz/Article/details/gtaylzgvhu.html

[S45] C++：lambda
来源：http://dali.shanyushiyangkeji.top/Article/details/gtydssrvxv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.hysaishi.cn/Article/details/gtdakrohkx.html

[S46] C++：函数模板
来源：http://dali.c1oappe.top/Article/details/gtqtljrdvu.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.yj20258888.top/Article/details/gtixiqcxnf.html

[S47] C++：结构化绑定遍历
来源：http://dali.c1oappe.top/Article/details/gtqznamjyh.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.feifeiyinyue.top/Article/details/gtcidpsxja.html

[S48] C++：逐行读文件
来源：http://dali.meibo888.top/Article/details/gtawehgwwf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ppjwa.cn/Article/details/gtuckwswax.html

while (std::getline(in, line)) { }
来源：http://dali.zdqjudy.top/Article/details/gturmlfdpf.html

[S49] C++：写文件
来源：http://dali.havefunace.top/Article/details/gtvhsdlqhp.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hfpthk.cn/Article/details/gtkmalflta.html

[S50] C++：格式化数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbcbshmed.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gtrbmxwinm.html

[S51] C++：显式类型转换
来源：http://dali.cheryme.top/Article/details/gtkovjmvte.html

static_cast<double>(a) / b
来源：http://dali.sxryk.cn/Article/details/gtstsgfikd.html

[S52] C++：const 与 noexcept
来源：http://dali.zdqjudy.top/Article/details/gtcszcvyph.html

int size() const noexcept { return n_; }
来源：http://dali.yonumen.top/Article/details/gtbsatsshi.html

[S53] C++：移动语义
来源：http://dali.cqqwz.cn/Article/details/gtcnttnnly.html

std::vector<int> w = std::move(v);
来源：http://dali.sxryk.cn/Article/details/gtnyxinfcv.html

[S54] C++：异常处理
来源：http://dali.ppjwa.cn/Article/details/gtdqtkbcqg.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhongyouzk.top/Article/details/gtjhmxpysu.html

[S55] C++：结构化绑定
来源：http://dali.cucudq.cn/Article/details/gtoewscppk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jyoumei.cn/Article/details/gtvbsqodxd.html

[S56] C++：optional
来源：http://dali.jinqigufen.top/Article/details/gtmxyetuuf.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ivvv.top/Article/details/gtdtaoqgvp.html

[S57] C++：编译期常量
来源：http://dali.yonumen.top/Article/details/gtbtyjrxmv.html

constexpr int N = 10;
来源：http://dali.aizwys.cn/Article/details/gtlltwfzez.html

[S58] C++：命名空间
来源：http://dali.haohaochexian.top/Article/details/gtxkecozqb.html

namespace ns { int f() { return 1; } }
来源：http://dali.havefunace.top/Article/details/gtpuaxsoti.html

[S59] C++：静态断言
来源：http://dali.xinyue.icu/Article/details/gtaokawwcw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.dianchejie.cn/Article/details/gthjumnekp.html

[S60] C++：遍历并删除元素
来源：http://dali.sufxvd.cn/Article/details/gtjgwixvby.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.tianlin.xyz/Article/details/gtzqeuksbs.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtnyeoxpkb.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hysaishi.cn/Article/details/gtdnlsvucz.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtmkqhyamp.html

[T01] Kotlin：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtxlxqmkkk.html

println("Hello")
来源：http://dali.shangyingyoupin.top/Article/details/gtjxojzxjw.html

[T02] Kotlin：变量
来源：http://dali.gotoacloud.top/Article/details/gttepfgrla.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.wangshuangyany.cn/Article/details/gtekvdqyjk.html

[T03] Kotlin：字符串模板
来源：http://dali.xinyue.icu/Article/details/gtizwedfyh.html

"值: $b"
来源：http://dali.hongshengwenyu.top/Article/details/gtbusfswqj.html

[T04] Kotlin：空安全
来源：http://dali.nanxuanxn.top/Article/details/gtxwvsahmn.html

val n: String? = null;  n?.length
来源：http://dali.gaohongyu789.top/Article/details/gtiofiatub.html

[T05] Kotlin：when 表达式
来源：http://dali.c1oappe.top/Article/details/gtbtrcvfin.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.tian-w.cn/Article/details/gtupugzhtc.html

[T06] Kotlin：集合映射
来源：http://dali.fengsongda.top/Article/details/gtrusisrlb.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shuidangran.top/Article/details/gtquiajuap.html

[T07] Kotlin：集合过滤
来源：http://dali.redwolf501.top/Article/details/gtjhjvoxnq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.hammf.cn/Article/details/gtvrzngnhj.html

[T08] Kotlin：数据类
来源：http://dali.yonumen.top/Article/details/gtlljwcduf.html

data class User(val name: String, val age: Int)
来源：http://dali.zhijiandao.cn/Article/details/gtgrrqtprp.html

[T09] Kotlin：扩展函数
来源：http://dali.hnxiangtu.top/Article/details/gtbrnlkrrd.html

fun String.exclaim() = this + "!"
来源：http://dali.shuidangran.top/Article/details/gtbzdsnolh.html

[T10] Kotlin：默认参数
来源：http://dali.haohaochexian.top/Article/details/gtigecqqhl.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhiwuduotai.top/Article/details/gtdtnhnshy.html

[T11] Kotlin：协程
来源：http://dali.jqgfzy.top/Article/details/gtibjrldll.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sxryk.cn/Article/details/gtarcxphpo.html

[T12] Kotlin：解构声明
来源：http://dali.jianghu66.top/Article/details/gtvrjchxtx.html

val (a, b) = Pair(1, 2)
来源：http://dali.yj20258888.top/Article/details/gtmsnzuude.html

[T13] Kotlin：只读 Map
来源：http://dali.tanke756.top/Article/details/gtktkcdbso.html

val m = mapOf("a" to 1)
来源：http://dali.bjfxy.top/Article/details/gtnclpmktn.html

[T14] Kotlin：循环
来源：http://dali.nwbrower.top/Article/details/gtzlrchpsy.html

for (i in 1..10) println(i)
来源：http://dali.sysykeji.top/Article/details/gtqhponodf.html

[T15] Kotlin：接口
来源：http://dali.jianghu66.top/Article/details/gtvkhmkkiw.html

interface Shape { fun area(): Double }
来源：http://dali.xziqi.cn/Article/details/gtygvuieuu.html

[T16] Swift：Hello World
来源：http://dali.tian-w.cn/Article/details/gtwggmehjr.html

print("Hello")
来源：http://dali.sweek.top/Article/details/gtkgylyyiz.html

[T17] Swift：变量与常量
来源：http://dali.fengsongda.top/Article/details/gthdychzwx.html

var a = 1;  let b = 2
来源：http://dali.daria6918.cn/Article/details/gtlxbyqmqy.html

[T18] Swift：字符串插值
来源：http://dali.xinyue.icu/Article/details/gtjehgeuhv.html

"值: \(b)"
来源：http://dali.guannengcc.top/Article/details/gtrhoapxed.html

[T19] Swift：可选绑定
来源：http://dali.hnqzz.top/Article/details/gteyxoytdg.html

if let n = opt { print(n) }
来源：http://dali.yueranfly.top/Article/details/gtwdvreexy.html

[T20] Swift：数组操作
来源：http://dali.9152youxi.cn/Article/details/gtjdcnqfsq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvjqzuwbt.html

[T21] Swift：遍历
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvdngmuvx.html

for x in a { print(x) }
来源：http://dali.xuetiantiany.cn/Article/details/gtxkvtmoms.html

[T22] Swift：字典
来源：http://dali.jlsjyb.cn/Article/details/gtuozrraiv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.andypj.xyz/Article/details/gtqcqdtqsn.html

[T23] Swift：函数
来源：http://dali.iojbl.cn/Article/details/gtxvnobajp.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.shanyushiyangtech.top/Article/details/gtruuhxwyz.html

[T24] Swift：闭包
来源：http://dali.zhoulong.xyz/Article/details/gtsualbkri.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtstaohrcb.html

[T25] Swift：结构体
来源：http://dali.pycfn.com/Article/details/gtbvlkvzte.html

struct P { var x: Int }
来源：http://dali.cqqwz.cn/Article/details/gtcvzjxnlb.html

[T26] Swift：类与重写
来源：http://dali.aibaodan.cn/Article/details/gtjmfhdsmh.html

class A: Base { override func f() {} }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjnewkdjp.html

[T27] Swift：错误处理
来源：http://dali.fzhhl.top/Article/details/gtnoerzsvf.html

do { try f() } catch { print(error) }
来源：http://dali.zhongyouzk.top/Article/details/gtiodpgwnv.html

[T28] Swift：枚举
来源：http://dali.hongshengwenyu.top/Article/details/gtjwvcotyd.html

enum Color { case red, green }
来源：http://dali.wangdashe.top/Article/details/gtijivmbcr.html

[T29] Swift：guard 提前返回
来源：http://dali.chenlongwang.top/Article/details/gttccmwhyg.html

guard let x = opt else { return }
来源：http://dali.pycfn.com/Article/details/gtkutupdsl.html

[T30] Swift：协议
来源：http://dali.zhoulong.xyz/Article/details/gtfocqgenz.html

protocol Shape { func area() -> Double }
来源：http://dali.redwolf501.top/Article/details/gtkhrppgkw.html

[T31] Lua：Hello World
来源：http://dali.shuidangran.top/Article/details/gtpukmszmd.html

print("Hello")
来源：http://dali.ehwqpu.com/Article/details/gtevmieliu.html

[T32] Lua：局部变量
来源：http://dali.jinqigfzy.top/Article/details/gtdyoyyvrs.html

local a = 1
来源：http://dali.svipenyu.cn/Article/details/gtrhdhuaff.html

[T33] Lua：表（数组）
来源：http://dali.sweek.top/Article/details/gtbzcrhbkm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.xylfe.cn/Article/details/gtrkrjyoxj.html

[T34] Lua：遍历表
来源：http://dali.tianlin.xyz/Article/details/gtsourkvqz.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jinyuanbaomall.cn/Article/details/gtakrdfazo.html

[T35] Lua：字典表
来源：http://dali.jinqigfzy.top/Article/details/gtqbxanhbg.html

local d = { a = 1 };  d.b = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtppphierh.html

[T36] Lua：函数
来源：http://dali.jinqigufen.top/Article/details/gtdrfsthzi.html

function add(a, b) return a + b end
来源：http://dali.cashguo.top/Article/details/gtiizplaoa.html

[T37] Lua：字符串拼接
来源：http://dali.jinqigfzy.top/Article/details/gtezhfyhij.html

"a" .. "b"
来源：http://dali.yueranfly.top/Article/details/gtvyjewkgv.html

[T38] Lua：条件
来源：http://dali.vqdsnc.cn/Article/details/gtbjovspio.html

if x > 0 then print("正") end
来源：http://dali.hnqzz.top/Article/details/gtbzqojajf.html

[T39] Lua：模式匹配
来源：http://dali.zhoulong.xyz/Article/details/gtkezlxaza.html

string.find(s, "%d+")
来源：http://dali.zycfv.cn/Article/details/gtgevmbcro.html

[T40] Lua：元表
来源：http://dali.0kj1m.cn/Article/details/gtrmgnmhhm.html

setmetatable({}, { __index = base })
来源：http://dali.ppjwa.cn/Article/details/gtyvsmiqzx.html

[T41] Perl：Hello World
来源：http://dali.ydzc1.top/Article/details/gtlbqbuvgk.html

print "Hello\n";
来源：http://dali.zhijiandao.cn/Article/details/gthvtyzvoi.html

[T42] Perl：变量类型
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzrcyzuis.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.gogol.net.cn/Article/details/gtohrngwmu.html

[T43] Perl：字符串插值
来源：http://dali.tianlin.xyz/Article/details/gtiwvcmiva.html

"值: $a"
来源：http://dali.hammf.cn/Article/details/gtktwtulmb.html

[T44] Perl：条件
来源：http://dali.sysykeji.top/Article/details/gtacrvdzhc.html

if ($a > 0) { print "正"; }
来源：http://dali.c1oappe.top/Article/details/gtuymtnyyb.html

[T45] Perl：数组遍历
来源：http://dali.jinghuilouyu.cn/Article/details/gtxvoryfyv.html

for my $x (@arr) { print $x; }
来源：http://dali.hywenlv.cn/Article/details/gtuzywtrkx.html

[T46] Perl：哈希操作
来源：http://dali.aibaodan.cn/Article/details/gtqhbwxfez.html

$h{b} = 2;  for my $k (keys %h) { print "$k=$h{$k}"; }
来源：http://dali.nanxuanxn.top/Article/details/gtwhjnrsvd.html

[T47] Perl：正则捕获
来源：http://dali.shuidangran.top/Article/details/gtfltbgxky.html

if ($s =~ /(\d+)/) { print $1; }
来源：http://dali.redwolf501.top/Article/details/gtcmegyzgj.html

[T48] Perl：正则替换
来源：http://dali.hnxiangtu.top/Article/details/gtmgicpbsz.html

$s =~ s/old/new/g;
来源：http://dali.chenjidiqi.icu/Article/details/gtdmshopio.html


<!-- 参考信息 -->