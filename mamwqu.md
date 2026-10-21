代发 wailian999

cmd > out.log 2>&1
来源：http://dali.yueranfly.top/Article/details/gtmoaffjwo.html

[R40] 追加写日志
来源：http://dali.jlsjyb.cn/Article/details/gthdsmaqmu.html

echo "log" >> out.log
来源：http://dali.gaohongyu789.top/Article/details/gtgbekogfm.html

[R41] 丢弃输出
来源：http://dali.shanyushiyangtech.top/Article/details/gthavrjtfd.html

cmd >/dev/null 2>&1
来源：http://dali.chenjidiqi.icu/Article/details/gtitofebyy.html

[R42] 输入重定向
来源：http://dali.yangfankeji.com/Article/details/gtxpevnxje.html

wc -l < a.txt
来源：http://dali.yuanzhike.top/Article/details/gtdiyujrjb.html

[R43] 按名字查找文件
来源：http://dali.hywenlv.cn/Article/details/gtkgmddnqj.html

find . -name "*.log" -type f
来源：http://dali.yuxming.cn/Article/details/gtsgluhexu.html

[R44] 按修改时间查找
来源：http://dali.zhengqikj.top/Article/details/gtycrxhbsx.html

find . -mtime -7 -type f
来源：http://dali.wangdashe.top/Article/details/gtsuxptgkx.html

[R45] 批量删除
来源：http://dali.quarkkingdee.top/Article/details/gthipwdjqm.html

find . -name "*.tmp" -delete
来源：http://dali.ppjwa.cn/Article/details/gtivcwqcxr.html

[R46] 递归替换文件内容
来源：http://dali.aizwys.cn/Article/details/gtnhebcill.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shangyingyoupin.top/Article/details/gtosckclvd.html

[R47] sed 单行替换
来源：http://dali.yj20258.top/Article/details/gtvmohecth.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.0kj1m.cn/Article/details/gtrrsmlgib.html

[R48] awk 取指定列
来源：http://dali.jlsjyb.cn/Article/details/gtyupuabqn.html

awk '{print $1, $3}' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gthzmintyy.html

[R49] awk 带条件
来源：http://dali.ydzc1.top/Article/details/gtxjmzmvvk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.aizwys.cn/Article/details/gtxeprxrvn.html

[R50] awk 求和
来源：http://dali.yvedp.cn/Article/details/gtakdyxpmh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zycfv.cn/Article/details/gtvnribtrz.html

[R51] 排序去重取前几
来源：http://dali.pycfn.com/Article/details/gtvgezhtlq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.nanxinkj.top/Article/details/gtsbnrsnio.html

[R52] 统计行数
来源：http://dali.snrcjt.cn/Article/details/gtgectseoc.html

wc -l a.txt
来源：http://dali.hysaishi.cn/Article/details/gtmyduizdx.html

[R53] 查看文件头与实时尾
来源：http://dali.jqgfzy.top/Article/details/gtgikysnwc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cucudq.cn/Article/details/gtdzqocjvm.html

[R54] 比较两个文件
来源：http://dali.pycfn.com/Article/details/gtcqkxjsql.html

diff a.txt b.txt
来源：http://dali.jqgufenzy.top/Article/details/gteadaohzi.html

[R55] 压缩与解压
来源：http://dali.yj20258888.top/Article/details/gtvziabill.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.wangshuangyany.cn/Article/details/gtrrwprxjr.html

[R56] 远程拷贝
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlovvxtps.html

scp file user@host:/path/
来源：http://dali.yj20258.top/Article/details/gtwnvgyvrp.html

[R57] 远程执行命令
来源：http://dali.ivvv.top/Article/details/gtiazaczlu.html

ssh user@host 'uptime'
来源：http://dali.snrcjt.cn/Article/details/gtptlhuasu.html

[R58] 下载文件
来源：http://dali.yvedp.cn/Article/details/gtamempjvq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhengqikj.top/Article/details/gtelrxghib.html

[R59] 发 POST JSON
来源：http://dali.daxiang520.top/Article/details/gtpkwgnrdz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xinyue.icu/Article/details/gtenovtznz.html

[R60] 只看 HTTP 状态码
来源：http://dali.havefunace.top/Article/details/gtmdjledac.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yj20258.top/Article/details/gtldtrrylj.html

[R61] 磁盘占用
来源：http://dali.jianghu66.top/Article/details/gtkozjsxca.html

df -h;  du -sh *
来源：http://dali.guannengcc.top/Article/details/gtthkqpqco.html

[R62] 找最占空间的文件
来源：http://dali.yj20258888.top/Article/details/gtovctqfki.html

du -ah . | sort -rh | head -10
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgtqelzvj.html

[R63] 内存与进程
来源：http://dali.guannengcc.top/Article/details/gtkvszqlqc.html

free -h;  ps aux | grep nginx
来源：http://dali.haohaochexian.top/Article/details/gtcnvkfutc.html

[R64] 结束进程
来源：http://dali.shangyingyoupin.top/Article/details/gttgywzwsm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.chenzaomai.com/Article/details/gthjmhnsmu.html

[R65] 查看端口占用
来源：http://dali.nanxinkj.top/Article/details/gtwezenxwh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.daria6918.cn/Article/details/gtoszkhema.html

[R66] 定时任务
来源：http://dali.smart0.xyz/Article/details/gtgulzdpty.html

crontab -e;  crontab -l
来源：http://dali.zhengqikj.top/Article/details/gtjieradak.html

[R67] 生成随机十六进制串
来源：http://dali.aizwys.cn/Article/details/gtejhgmoer.html

openssl rand -hex 16
来源：http://dali.daria6918.cn/Article/details/gtldznsgfo.html

[R68] 计算文件校验值
来源：http://dali.hfpthk.cn/Article/details/gttjtqzklh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hysaishi.cn/Article/details/gtbarkqejt.html

[R69] 生成随机密码
来源：http://dali.iojbl.cn/Article/details/gtrqfvorsx.html

head -c 16 /dev/urandom | base64
来源：http://dali.zycfv.cn/Article/details/gtspggvwkn.html

[R70] 时间戳与互转
来源：http://dali.ydzc1.top/Article/details/gtzbpvybpb.html

date +%s;  date -d @1700000000
来源：http://dali.cqqwz.cn/Article/details/gtkrxdoeec.html

[R71] 日期格式化
来源：http://dali.xylfe.cn/Article/details/gtvbejpzgy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.gogol.net.cn/Article/details/gtmedwjcdc.html

[R72] 等待端口就绪
来源：http://dali.chenjidiqi.icu/Article/details/gtuvshsapd.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwdvoyvff.html

[R73] 分割大日志
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdwwcpmhz.html

split -l 1000 big.log part_
来源：http://dali.c1oappe.top/Article/details/gtzcsckqmn.html

[R74] 批量重命名
来源：http://dali.havefunace.top/Article/details/gtnkwhnspa.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinqigufen.top/Article/details/gtkrnmiktw.html

[R75] 导出环境变量
来源：http://dali.aizwys.cn/Article/details/gtahlddysi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.nanxinkj.top/Article/details/gtpsulzics.html

[R76] 使用临时文件
来源：http://dali.birdmap.top/Article/details/gtumeemfxm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.feifeiyinyue.top/Article/details/gtkvmjtieg.html

[R77] 读取用户输入
来源：http://dali.hnqzz.top/Article/details/gtqgpepfuw.html

read -rp "请输入: " ans
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyyxjkvlq.html

[R78] 交互式菜单
来源：http://dali.nanxinkj.top/Article/details/gtvhtglrxv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.pengpengdd.cyou/Article/details/gtlrhhtnqc.html

[R79] 解析命令行选项
来源：http://dali.jiagoushi.top/Article/details/gtkdxxcpoy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.redwolf501.top/Article/details/gtqgeilbps.html

[R80] 查看脚本执行耗时
来源：http://dali.xylfe.cn/Article/details/gtcsuqnxlt.html

time ./run.sh
来源：http://dali.bjfxy.top/Article/details/gtbukasyly.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtgsaihqxw.html

S. C / C++ 专题
来源：http://dali.pycfn.com/Article/details/gtepapwbno.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtomfvxnkd.html

[S01] C：Hello World
来源：http://dali.cashguo.top/Article/details/gtuqkjnirr.html

#include <stdio.h>
来源：http://dali.chenjidiqi.icu/Article/details/gtiumuofyr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jyoumei.cn/Article/details/gtolwplgow.html

[S02] C：变量与格式化输出
来源：http://dali.pengpengdd.cyou/Article/details/gtshtbnzqz.html

int a = 10; printf("%d\n", a);
来源：http://dali.cashguo.top/Article/details/gtfeagwzdj.html

[S03] C：读入整数
来源：http://dali.jinqigfzy.top/Article/details/gtaamhmgio.html

int x; scanf("%d", &x);
来源：http://dali.andypj.xyz/Article/details/gtkpjevxzy.html

[S04] C：字符串复制
来源：http://dali.shzxlz.cn/Article/details/gtfzssrwbs.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbjchirql.html

[S05] C：字符串长度
来源：http://dali.yueranfly.top/Article/details/gtadpxepws.html

strlen(s)
来源：http://dali.yj20258888.top/Article/details/gtyrphnqaw.html

[S06] C：字符串比较
来源：http://dali.xuanzx.com/Article/details/gtvftvdvxs.html

strcmp(a, b) == 0
来源：http://dali.xziqi.cn/Article/details/gtlmqddrhl.html

[S07] C：数组遍历求和
来源：http://dali.yj202588.top/Article/details/gtxfamflbp.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.mhx1999.top/Article/details/gtjssibufe.html

[S08] C：动态内存分配与释放
来源：http://dali.fengsongda.top/Article/details/gtdrymrnvo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cdnleiting.top/Article/details/gthhfgvmia.html

[S09] C：结构体定义与初始化
来源：http://dali.yanxiufei.cn/Article/details/gtxxdjwprp.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jyoumei.cn/Article/details/gttmptyysz.html

[S10] C：指针与解引用
来源：http://dali.zhongyouzk.top/Article/details/gtgyxdgvdg.html

int *p = &a;  *p = 5;
来源：http://dali.iojbl.cn/Article/details/gtubdecwji.html

[S11] C：逐行读文件
来源：http://dali.xylfe.cn/Article/details/gtwcdrqmde.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jlsjyb.cn/Article/details/gtejhkjsgx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.0kj1m.cn/Article/details/gtbcfvmfbe.html

fclose(f);
来源：http://dali.gaohongyu789.top/Article/details/gtsttpormg.html

[S12] C：写文件
来源：http://dali.birdmap.top/Article/details/gtwggsfexp.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.andypj.xyz/Article/details/gtsvfbvwjl.html

[S13] C：宏定义
来源：http://dali.guannengcc.top/Article/details/gtbuikrdtl.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.sweek.top/Article/details/gtbrjskedp.html

[S14] C：枚举
来源：http://dali.meibo888.top/Article/details/gtjczqmkpy.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yj202588.top/Article/details/gtameufqib.html

[S15] C：类型转换
来源：http://dali.birdmap.top/Article/details/gthrqplvtj.html

(double) a / b
来源：http://dali.nanxuanxn.top/Article/details/gtgberlyhp.html

[S16] C：位操作置位
来源：http://dali.cheryme.top/Article/details/gtqvjepoui.html

x |= (1 << 3);
来源：http://dali.andypj.xyz/Article/details/gtddeuzauf.html

[S17] C：安全拼接字符串
来源：http://dali.fzhhl.top/Article/details/gtcrgdzhky.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sufxvd.cn/Article/details/gtradwkqay.html

[S18] C：命令行参数
来源：http://dali.redwolf501.top/Article/details/gtqbuwlvqy.html

int main(int argc, char **argv)
来源：http://dali.shzxlz.cn/Article/details/gtrzwdvyoo.html

[S19] C：快速排序
来源：http://dali.mhx1999.top/Article/details/gtescqlilk.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.meibo888.top/Article/details/gtmxfxpxvn.html

[S20] C：二分查找
来源：http://dali.pengpengdd.cyou/Article/details/gtoreslawa.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinqigufen.top/Article/details/gtkultzsxk.html

[S21] C：字符类别判断
来源：http://dali.jinqigufen.top/Article/details/gtxonsfwre.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.daxiang520.top/Article/details/gtoytjjugs.html

[S22] C：字符串转数字
来源：http://dali.jyoumei.cn/Article/details/gtxfhbraak.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.ydzc1.top/Article/details/gtmffgkuvg.html

[S23] C：随机数
来源：http://dali.cashguo.top/Article/details/gtiwirqzow.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yangfankeji.com/Article/details/gtosjjtjrm.html

[S24] C：获取本地时间
来源：http://dali.zhiwuduotai.top/Article/details/gtteufzywi.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shangyingyoupin.top/Article/details/gtohxjzlht.html

[S25] C：内存拷贝
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmiruidvq.html

memcpy(dst, src, n);
来源：http://dali.zhiwuduotai.top/Article/details/gtbwfsfaqc.html

[S26] C：内存清零
来源：http://dali.fzhhl.top/Article/details/gtupzisusi.html

memset(a, 0, sizeof a);
来源：http://dali.chenjidiqi.icu/Article/details/gtgginojdu.html

[S27] C：定义常量
来源：http://dali.mhx1999.top/Article/details/gtkjhhumll.html

const double PI = 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gtglyohlzu.html

[S28] C：静态变量
来源：http://dali.daxiang520.top/Article/details/gtgliegwsq.html

static int counter = 0;
来源：http://dali.kuanghao11.cn/Article/details/gtaxddovex.html

[S29] C：变参函数
来源：http://dali.nwbrower.top/Article/details/gteonriedw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shanyushiyangtech.top/Article/details/gtompkcydz.html

[S30] C：头文件保护
来源：http://dali.fzhhl.top/Article/details/gtpminjpbg.html

#ifndef X_H
来源：http://dali.pycfn.com/Article/details/gtjdetkijo.html

#define X_H
来源：http://dali.vqdsnc.cn/Article/details/gttaagngni.html

#endif
来源：http://dali.ybcxt.top/Article/details/gtwhipnjeg.html

[S31] C++：Hello World
来源：http://dali.xylfe.cn/Article/details/gtabaqritk.html

#include <iostream>
来源：http://dali.nanxinkj.top/Article/details/gtbnwwudis.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.andypj.xyz/Article/details/gtervdhtgf.html

[S32] C++：字符串
来源：http://dali.0kj1m.cn/Article/details/gttcgixikm.html

std::string s = "hi";  s += "!";
来源：http://dali.yonumen.top/Article/details/gtgacbgeuf.html

[S33] C++：vector 增删
来源：http://dali.yonumen.top/Article/details/gtcazqyjan.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shangyingyoupin.top/Article/details/gtefvewloy.html

[S34] C++：遍历 vector
来源：http://dali.gotoacloud.top/Article/details/gtkixsmntd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuuvyqvtd.html

[S35] C++：map
来源：http://dali.hongshengwenyu.top/Article/details/gtrtgpvtot.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.meibo888.top/Article/details/gtjjewcebx.html

[S36] C++：unordered_map
来源：http://dali.ybcxt.top/Article/details/gtrxtnovtp.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guowangkeji.top/Article/details/gtpzkqgfbb.html

[S37] C++：set
来源：http://dali.fengsongda.top/Article/details/gtgwysghtm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.snrcjt.cn/Article/details/gtysednays.html

[S38] C++：排序
来源：http://dali.gogol.net.cn/Article/details/gtalkqxbxa.html

std::sort(v.begin(), v.end());
来源：http://dali.feifeiyinyue.top/Article/details/gtxnpzzjrd.html

[S39] C++：自定义比较器排序
来源：http://dali.fengsongda.top/Article/details/gthycurlgn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.wangshuangyany.cn/Article/details/gtfugszgfa.html

[S40] C++：查找元素
来源：http://dali.gaohongyu789.top/Article/details/gtwjnivkcp.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.chenzaomai.com/Article/details/gtwslholxm.html

[S41] C++：类与构造函数
来源：http://dali.tanke756.top/Article/details/gtytdgyuey.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.nwbrower.top/Article/details/gtjmthnfws.html

[S42] C++：继承与虚函数
来源：http://dali.pycfn.com/Article/details/gtkddvwjwx.html

class B : public Base { public: void f() override {} };
来源：http://dali.jqgufenzy.top/Article/details/gtpploxvox.html

[S43] C++：智能指针
来源：http://dali.yongpay.top/Article/details/gtlxnriayg.html

auto p = std::make_unique<int>(5);
来源：http://dali.vqdsnc.cn/Article/details/gtukoszidp.html

[S44] C++：引用传参
来源：http://dali.feifeiyinyue.top/Article/details/gtyeqhsrur.html

void inc(int &x) { ++x; }
来源：http://dali.jqgufenzy.top/Article/details/gtqwzmpzqn.html

[S45] C++：lambda
来源：http://dali.xinyue.icu/Article/details/gtqksdutcl.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.pycfn.com/Article/details/gtmfatrjxp.html

[S46] C++：函数模板
来源：http://dali.nanxinkj.top/Article/details/gtoupelrbl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinqigfzy.top/Article/details/gtscugclvq.html

[S47] C++：结构化绑定遍历
来源：http://dali.hfpthk.cn/Article/details/gtibqgaeul.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.quarkkingdee.top/Article/details/gtrwyleiqo.html

[S48] C++：逐行读文件
来源：http://dali.snrcjt.cn/Article/details/gtiirxocvn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jianghu66.top/Article/details/gtdkehztav.html

while (std::getline(in, line)) { }
来源：http://dali.ivvv.top/Article/details/gtfmrniwgg.html

[S49] C++：写文件
来源：http://dali.zhongyouzk.top/Article/details/gtdpkdfhwe.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.tianlin.xyz/Article/details/gtzxkuocdr.html

[S50] C++：格式化数字
来源：http://dali.yj202588.top/Article/details/gtlwfvtfqf.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.wangdashe.top/Article/details/gtkaerlrop.html

[S51] C++：显式类型转换
来源：http://dali.guowangkeji.top/Article/details/gtgmcglqzh.html

static_cast<double>(a) / b
来源：http://dali.iojbl.cn/Article/details/gtlbgmnbvi.html

[S52] C++：const 与 noexcept
来源：http://dali.vqdsnc.cn/Article/details/gtwgvvyzrv.html

int size() const noexcept { return n_; }
来源：http://dali.gaohongyu789.top/Article/details/gtyopyqwbc.html

[S53] C++：移动语义
来源：http://dali.xylfe.cn/Article/details/gtcnllrnjw.html

std::vector<int> w = std::move(v);
来源：http://dali.ybcxt.top/Article/details/gtslrxprwx.html

[S54] C++：异常处理
来源：http://dali.hammf.cn/Article/details/gtnxandtwo.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhijiandao.cn/Article/details/gtcbwmpfbx.html

[S55] C++：结构化绑定
来源：http://dali.yueranfly.top/Article/details/gtgupuumos.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yueranfly.top/Article/details/gtfmyexrcc.html

[S56] C++：optional
来源：http://dali.yuanzhike.top/Article/details/gttaxgasws.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xinyue.icu/Article/details/gthdooevlx.html

[S57] C++：编译期常量
来源：http://dali.gzhubu.top/Article/details/gtxkofbvkg.html

constexpr int N = 10;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdxisozew.html

[S58] C++：命名空间
来源：http://dali.shuidangran.top/Article/details/gttntlwheg.html

namespace ns { int f() { return 1; } }
来源：http://dali.jlsjyb.cn/Article/details/gtrdopvofu.html

[S59] C++：静态断言
来源：http://dali.cqqwz.cn/Article/details/gtctpgvhrz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.fzhhl.top/Article/details/gtbajzffmo.html

[S60] C++：遍历并删除元素
来源：http://dali.xuetiantiany.cn/Article/details/gtlcpgxyjr.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jqgufenzy.top/Article/details/gtqwzeoosv.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gtfhnzhkku.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zdqjudy.top/Article/details/gtkqqocamx.html

================================================================================
来源：http://dali.hysaishi.cn/Article/details/gtnbevnqwh.html

[T01] Kotlin：Hello World
来源：http://dali.sweek.top/Article/details/gtsdhtaivb.html

println("Hello")
来源：http://dali.mhx1999.top/Article/details/gthqnxirvd.html

[T02] Kotlin：变量
来源：http://dali.havefunace.top/Article/details/gtdtrizdsq.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yj20258.top/Article/details/gtulfibvjf.html

[T03] Kotlin：字符串模板
来源：http://dali.pengpengdd.cyou/Article/details/gtjekeapcf.html

"值: $b"
来源：http://dali.hnqzz.top/Article/details/gtydrtessi.html

[T04] Kotlin：空安全
来源：http://dali.hysaishi.cn/Article/details/gtinpbzeli.html

val n: String? = null;  n?.length
来源：http://dali.zhoulong.xyz/Article/details/gthucnxoop.html

[T05] Kotlin：when 表达式
来源：http://dali.guannengcc.top/Article/details/gtbscvnxpn.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yanxiufei.cn/Article/details/gtxqznvcvx.html

[T06] Kotlin：集合映射
来源：http://dali.hongshengwenyu.top/Article/details/gtqesnotrk.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jqgfzy.top/Article/details/gtfshljczf.html

[T07] Kotlin：集合过滤
来源：http://dali.ybcxt.top/Article/details/gtzcrbstwg.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cucudq.cn/Article/details/gteutcspim.html

[T08] Kotlin：数据类
来源：http://dali.jlsjyb.cn/Article/details/gtjzzlmrsp.html

data class User(val name: String, val age: Int)
来源：http://dali.ppjwa.cn/Article/details/gtwpaugsoy.html

[T09] Kotlin：扩展函数
来源：http://dali.jlsjyb.cn/Article/details/gtnwaqnach.html

fun String.exclaim() = this + "!"
来源：http://dali.yueranfly.top/Article/details/gtcptkccjm.html

[T10] Kotlin：默认参数
来源：http://dali.shangyingyoupin.top/Article/details/gtrthfjsop.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.chenjidiqi.icu/Article/details/gtcpiywaap.html

[T11] Kotlin：协程
来源：http://dali.tian-w.cn/Article/details/gtxhinslvl.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.jianghu66.top/Article/details/gtqocjyhef.html

[T12] Kotlin：解构声明
来源：http://dali.shuidangran.top/Article/details/gtlzgogffx.html

val (a, b) = Pair(1, 2)
来源：http://dali.xziqi.cn/Article/details/gtxwkjdhzy.html

[T13] Kotlin：只读 Map
来源：http://dali.jqgufenzy.top/Article/details/gtheqjmfoa.html

val m = mapOf("a" to 1)
来源：http://dali.pycfn.com/Article/details/gtsmnwwuqx.html

[T14] Kotlin：循环
来源：http://dali.bjfxy.top/Article/details/gteuwmankd.html

for (i in 1..10) println(i)
来源：http://dali.zdqjudy.top/Article/details/gtxxunelot.html

[T15] Kotlin：接口
来源：http://dali.ywan-chungtsiang.top/Article/details/gthkxkkoei.html

interface Shape { fun area(): Double }
来源：http://dali.ivvv.top/Article/details/gtnayrwjof.html

[T16] Swift：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtqylwgvnu.html

print("Hello")
来源：http://dali.hysaishi.cn/Article/details/gtzshxipxo.html

[T17] Swift：变量与常量
来源：http://dali.wangshuangyany.cn/Article/details/gtizypxoit.html

var a = 1;  let b = 2
来源：http://dali.xuetiantiany.cn/Article/details/gtiquqmmrt.html

[T18] Swift：字符串插值
来源：http://dali.jinghuilouyu.cn/Article/details/gtfacbizhl.html

"值: \(b)"
来源：http://dali.yuanzhike.top/Article/details/gtzlwywyni.html

[T19] Swift：可选绑定
来源：http://dali.yongpay.top/Article/details/gtlncojnzk.html

if let n = opt { print(n) }
来源：http://dali.mhx1999.top/Article/details/gtpwjtcmrb.html

[T20] Swift：数组操作
来源：http://dali.sysykeji.top/Article/details/gteoaudbrc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj20258888.top/Article/details/gtkwrddhen.html

[T21] Swift：遍历
来源：http://dali.xuanzx.com/Article/details/gtibasyhsa.html

for x in a { print(x) }
来源：http://dali.9152youxi.cn/Article/details/gtohrosmdz.html

[T22] Swift：字典
来源：http://dali.quarkkingdee.top/Article/details/gtapyobylk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.pycfn.com/Article/details/gtrdqajicr.html

[T23] Swift：函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjkkgcdgf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.tanke756.top/Article/details/gtnlltwmoj.html

[T24] Swift：闭包
来源：http://dali.xuanzx.com/Article/details/gtppodkvjw.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.hfpthk.cn/Article/details/gteqjbyunh.html

[T25] Swift：结构体
来源：http://dali.dashuyun.cn/Article/details/gtbnidkoaz.html

struct P { var x: Int }
来源：http://dali.hnxiangtu.top/Article/details/gtqpxtdukc.html

[T26] Swift：类与重写
来源：http://dali.redwolf501.top/Article/details/gtjbdchyto.html

class A: Base { override func f() {} }
来源：http://dali.hongshengwenyu.top/Article/details/gtepnqoolm.html

[T27] Swift：错误处理
来源：http://dali.jiagoushi.top/Article/details/gtctnbtxou.html

do { try f() } catch { print(error) }
来源：http://dali.tianlin.xyz/Article/details/gttqdkekcg.html

[T28] Swift：枚举
来源：http://dali.jlsjyb.cn/Article/details/gtbblzcmev.html

enum Color { case red, green }
来源：http://dali.jyoumei.cn/Article/details/gtkwllywpd.html

[T29] Swift：guard 提前返回
来源：http://dali.jqgufenzy.top/Article/details/gtnuihhrbt.html

guard let x = opt else { return }
来源：http://dali.hywenlv.cn/Article/details/gtiswhqypo.html

[T30] Swift：协议
来源：http://dali.316326.xyz/Article/details/gthqjwrlhv.html

protocol Shape { func area() -> Double }
来源：http://dali.birdmap.top/Article/details/gtmosjkpfd.html

[T31] Lua：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtorjdwvcb.html

print("Hello")
来源：http://dali.aizwys.cn/Article/details/gtbkgyhhyr.html

[T32] Lua：局部变量
来源：http://dali.xinyue.icu/Article/details/gttfrfzmip.html

local a = 1
来源：http://dali.jianghu66.top/Article/details/gtnpgillgv.html

[T33] Lua：表（数组）
来源：http://dali.snrcjt.cn/Article/details/gtmkqveyrx.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.haohaochexian.top/Article/details/gtfndsdngj.html

[T34] Lua：遍历表
来源：http://dali.9152youxi.cn/Article/details/gtbudmcvdj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jyoumei.cn/Article/details/gtouyujlza.html

[T35] Lua：字典表
来源：http://dali.xylfe.cn/Article/details/gtmzyzsqmm.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhoulong.xyz/Article/details/gtbgthiyfl.html

[T36] Lua：函数
来源：http://dali.jqgufenzy.top/Article/details/gtvkoxwaqc.html

function add(a, b) return a + b end
来源：http://dali.ydzc1.top/Article/details/gtpgtudfnv.html

[T37] Lua：字符串拼接
来源：http://dali.iojbl.cn/Article/details/gtogocfrep.html

"a" .. "b"
来源：http://dali.guowangkeji.top/Article/details/gtelsxxqqg.html

[T38] Lua：条件
来源：http://dali.yuanzhike.top/Article/details/gthezhvzfh.html

if x > 0 then print("正") end
来源：http://dali.shangyingyoupin.top/Article/details/gtjitroteu.html

[T39] Lua：模式匹配
来源：http://dali.tian-w.cn/Article/details/gtltxjbufg.html

string.find(s, "%d+")
来源：http://dali.shanyushiyangkeji.top/Article/details/gtznhmhxcm.html

[T40] Lua：元表
来源：http://dali.cucudq.cn/Article/details/gtakooioui.html

setmetatable({}, { __index = base })
来源：http://dali.ivvv.top/Article/details/gtxvdqrlth.html

[T41] Perl：Hello World
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsgpzxijk.html

print "Hello\n";
来源：http://dali.birdmap.top/Article/details/gtthvtjcjc.html

[T42] Perl：变量类型
来源：http://dali.quarkkingdee.top/Article/details/gtmqpflsmj.html

my $a = 1;  my @arr = (1, 2, 3);  my %h = (a => 1);
来源：http://dali.jqgufenzy.top/Article/details/gtkbudjrqn.html


<!-- 参考信息 -->