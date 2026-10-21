代发 wailian999

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.0kj1m.cn/Article/details/gtuujjsvxh.html

[R34] 退出时清理
来源：http://dali.sufxvd.cn/Article/details/gtbykpnfml.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.guannengcc.top/Article/details/gtgggbvmlq.html

[R35] 后台执行并等待
来源：http://dali.zhiwuduotai.top/Article/details/gtqoktbsit.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.sufxvd.cn/Article/details/gtnktacpwq.html

[R36] 并发执行多个任务
来源：http://dali.jianghu66.top/Article/details/gtntmngdre.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.316326.xyz/Article/details/gtlscxknxm.html

[R37] 把输出赋给变量
来源：http://dali.cqqwz.cn/Article/details/gtnalhjlgx.html

files=$(ls -1)
来源：http://dali.jqgfzy.top/Article/details/gtywxgahiv.html

[R38] 管道串联
来源：http://dali.havefunace.top/Article/details/gtfypvewsa.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shzxlz.cn/Article/details/gtiidlyprm.html

[R39] 重定向标准输出与错误
来源：http://dali.yanxiufei.cn/Article/details/gtczfsbfsy.html

cmd > out.log 2>&1
来源：http://dali.ydzc1.top/Article/details/gtbuotmyfu.html

[R40] 追加写日志
来源：http://dali.cdnleiting.top/Article/details/gtxfppcjza.html

echo "log" >> out.log
来源：http://dali.wangdashe.top/Article/details/gtdgrctsrf.html

[R41] 丢弃输出
来源：http://dali.xziqi.cn/Article/details/gtlhiepluj.html

cmd >/dev/null 2>&1
来源：http://dali.andypj.xyz/Article/details/gtpcguexlm.html

[R42] 输入重定向
来源：http://dali.vqdsnc.cn/Article/details/gtbrloulzk.html

wc -l < a.txt
来源：http://dali.aibaodan.cn/Article/details/gtcgmejzuf.html

[R43] 按名字查找文件
来源：http://dali.zhiwuduotai.top/Article/details/gtxtyhirxc.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gtwimigepk.html

[R44] 按修改时间查找
来源：http://dali.shzxlz.cn/Article/details/gthsxkcggo.html

find . -mtime -7 -type f
来源：http://dali.yangfankeji.com/Article/details/gtyznircev.html

[R45] 批量删除
来源：http://dali.xylfe.cn/Article/details/gtyqvnwiax.html

find . -name "*.tmp" -delete
来源：http://dali.c1oappe.top/Article/details/gtbztrpary.html

[R46] 递归替换文件内容
来源：http://dali.redwolf501.top/Article/details/gtsnzqakic.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zdqjudy.top/Article/details/gtikrbthnz.html

[R47] sed 单行替换
来源：http://dali.kuanghao11.cn/Article/details/gtbffiszht.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.ehwqpu.com/Article/details/gtymvnqtjc.html

[R48] awk 取指定列
来源：http://dali.yj20258888.top/Article/details/gtjdtwparf.html

awk '{print $1, $3}' a.txt
来源：http://dali.ybcxt.top/Article/details/gtpsvjwrfj.html

[R49] awk 带条件
来源：http://dali.yj202588.top/Article/details/gtnvmbzouo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.dianchejie.cn/Article/details/gtqloxpsaj.html

[R50] awk 求和
来源：http://dali.smart0.xyz/Article/details/gtqujitbvh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtnepmhyin.html

[R51] 排序去重取前几
来源：http://dali.pengpengdd.cyou/Article/details/gtzgkzpqua.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ybcxt.top/Article/details/gtetfragdk.html

[R52] 统计行数
来源：http://dali.tianlin.xyz/Article/details/gtzmmgsbfz.html

wc -l a.txt
来源：http://dali.hysaishi.cn/Article/details/gtalxceain.html

[R53] 查看文件头与实时尾
来源：http://dali.sxryk.cn/Article/details/gtzzqhbyza.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinyuanbaomall.cn/Article/details/gtehtsjilr.html

[R54] 比较两个文件
来源：http://dali.ydzc1.top/Article/details/gtgnoypiha.html

diff a.txt b.txt
来源：http://dali.cashguo.top/Article/details/gtxkmokjwh.html

[R55] 压缩与解压
来源：http://dali.snrcjt.cn/Article/details/gtniagzqrf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hysaishi.cn/Article/details/gtwvholsuf.html

[R56] 远程拷贝
来源：http://dali.hongshengwenyu.top/Article/details/gtemsiccwi.html

scp file user@host:/path/
来源：http://dali.hnqzz.top/Article/details/gtltwbfxfr.html

[R57] 远程执行命令
来源：http://dali.jlsjyb.cn/Article/details/gtvyedyppr.html

ssh user@host 'uptime'
来源：http://dali.aibaodan.cn/Article/details/gtvcxejogw.html

[R58] 下载文件
来源：http://dali.feifeiyinyue.top/Article/details/gtcjijedae.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.c1oappe.top/Article/details/gtjwvivqzo.html

[R59] 发 POST JSON
来源：http://dali.xinyue.icu/Article/details/gtsbrvvrrd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zdqjudy.top/Article/details/gtxyyusqmf.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhongyouzk.top/Article/details/gtoumlwvrj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.chenjidiqi.icu/Article/details/gtfigbrlyh.html

[R61] 磁盘占用
来源：http://dali.zdqjudy.top/Article/details/gtmzphtgbj.html

df -h;  du -sh *
来源：http://dali.fengsongda.top/Article/details/gtkqxuhdbb.html

[R62] 找最占空间的文件
来源：http://dali.hnxiangtu.top/Article/details/gtrdeiwqhc.html

du -ah . | sort -rh | head -10
来源：http://dali.chenjidiqi.icu/Article/details/gtrieyvogd.html

[R63] 内存与进程
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrvgpjyjg.html

free -h;  ps aux | grep nginx
来源：http://dali.mhx1999.top/Article/details/gtgzzxkkfs.html

[R64] 结束进程
来源：http://dali.tanke756.top/Article/details/gtctwrqgnu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.vqdsnc.cn/Article/details/gtiswqvnsf.html

[R65] 查看端口占用
来源：http://dali.c1oappe.top/Article/details/gtzzvvbqkj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.aizwys.cn/Article/details/gtmquofhrt.html

[R66] 定时任务
来源：http://dali.cucudq.cn/Article/details/gtejzxhvlh.html

crontab -e;  crontab -l
来源：http://dali.fzhhl.top/Article/details/gtxbwxubjo.html

[R67] 生成随机十六进制串
来源：http://dali.hongshengwenyu.top/Article/details/gtopqakgte.html

openssl rand -hex 16
来源：http://dali.svipenyu.cn/Article/details/gtgenqwzmo.html

[R68] 计算文件校验值
来源：http://dali.daxiang520.top/Article/details/gtmlgzmxff.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.bjfxy.top/Article/details/gtnjdetifk.html

[R69] 生成随机密码
来源：http://dali.chenzaomai.com/Article/details/gtwmxpvmao.html

head -c 16 /dev/urandom | base64
来源：http://dali.meibo888.top/Article/details/gtzpywjyjc.html

[R70] 时间戳与互转
来源：http://dali.9152youxi.cn/Article/details/gtqtglifir.html

date +%s;  date -d @1700000000
来源：http://dali.gotoacloud.top/Article/details/gtwifvvjkk.html

[R71] 日期格式化
来源：http://dali.yj20258888.top/Article/details/gtojpaytfb.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xziqi.cn/Article/details/gtgfrqfhyz.html

[R72] 等待端口就绪
来源：http://dali.cashguo.top/Article/details/gtopeerwse.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zdqjudy.top/Article/details/gticfkerac.html

[R73] 分割大日志
来源：http://dali.zhixingplan.top/Article/details/gttkeujano.html

split -l 1000 big.log part_
来源：http://dali.yongpay.top/Article/details/gtbldkuygg.html

[R74] 批量重命名
来源：http://dali.daxiang520.top/Article/details/gtxwcbolzt.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jlsjyb.cn/Article/details/gtxsakkvqe.html

[R75] 导出环境变量
来源：http://dali.cashguo.top/Article/details/gtrscxiqrz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hywenlv.cn/Article/details/gtfcvydyak.html

[R76] 使用临时文件
来源：http://dali.aizwys.cn/Article/details/gtfqbocvtv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenlongwang.top/Article/details/gtptkozfbk.html

[R77] 读取用户输入
来源：http://dali.pycfn.com/Article/details/gtrqigtfon.html

read -rp "请输入: " ans
来源：http://dali.xuetiantiany.cn/Article/details/gtkulqtwut.html

[R78] 交互式菜单
来源：http://dali.zhoulong.xyz/Article/details/gtiyepzdqm.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.havefunace.top/Article/details/gtdguoencz.html

[R79] 解析命令行选项
来源：http://dali.zhongyouzk.top/Article/details/gtlllqvbyy.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yj20258.top/Article/details/gthyzhqpcf.html

[R80] 查看脚本执行耗时
来源：http://dali.havefunace.top/Article/details/gtbjebbjtz.html

time ./run.sh
来源：http://dali.sufxvd.cn/Article/details/gtnttzswxe.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtderoabbx.html

S. C / C++ 专题
来源：http://dali.chenzaomai.com/Article/details/gtzpgejlob.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtelgmovye.html

[S01] C：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtpjatzckb.html

#include <stdio.h>
来源：http://dali.9152youxi.cn/Article/details/gttlkatosb.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hnxiangtu.top/Article/details/gtiyqfvuxm.html

[S02] C：变量与格式化输出
来源：http://dali.zhengqikj.top/Article/details/gtcotwfisr.html

int a = 10; printf("%d\n", a);
来源：http://dali.cashguo.top/Article/details/gtqjcrzoap.html

[S03] C：读入整数
来源：http://dali.shzxlz.cn/Article/details/gtbsnyoyqj.html

int x; scanf("%d", &x);
来源：http://dali.gaohongyu789.top/Article/details/gthmxalpro.html

[S04] C：字符串复制
来源：http://dali.svipenyu.cn/Article/details/gtslyajgzw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.ehwqpu.com/Article/details/gttcbdffax.html

[S05] C：字符串长度
来源：http://dali.nanxinkj.top/Article/details/gtmoyeiuoj.html

strlen(s)
来源：http://dali.hongshengwenyu.top/Article/details/gtterrobvr.html

[S06] C：字符串比较
来源：http://dali.sufxvd.cn/Article/details/gtiwfygvfx.html

strcmp(a, b) == 0
来源：http://dali.yj202588.top/Article/details/gtckhgwzsa.html

[S07] C：数组遍历求和
来源：http://dali.hongshengwenyu.top/Article/details/gtjsltliof.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.chenzaomai.com/Article/details/gtkchdnydo.html

[S08] C：动态内存分配与释放
来源：http://dali.chenzaomai.com/Article/details/gtaxfqddco.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.xziqi.cn/Article/details/gtwmaqcygc.html

[S09] C：结构体定义与初始化
来源：http://dali.ehwqpu.com/Article/details/gtpyltvtal.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jqgufenzy.top/Article/details/gtoopaqwon.html

[S10] C：指针与解引用
来源：http://dali.yuanzhike.top/Article/details/gtrxmcbazb.html

int *p = &a;  *p = 5;
来源：http://dali.xuanzx.com/Article/details/gtwjmlmuoa.html

[S11] C：逐行读文件
来源：http://dali.hongshengwenyu.top/Article/details/gtyzuaruea.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hywenlv.cn/Article/details/gtaiebeymi.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsvckable.html

fclose(f);
来源：http://dali.vqdsnc.cn/Article/details/gtqwosbcke.html

[S12] C：写文件
来源：http://dali.ehwqpu.com/Article/details/gtfnvwqejg.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhiwuduotai.top/Article/details/gtgeuajjry.html

[S13] C：宏定义
来源：http://dali.ydzc1.top/Article/details/gthajyfxmh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jqgfzy.top/Article/details/gtsamacslq.html

[S14] C：枚举
来源：http://dali.gaohongyu789.top/Article/details/gtzvtenpgq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yonumen.top/Article/details/gtkniinskq.html

[S15] C：类型转换
来源：http://dali.xziqi.cn/Article/details/gtydqulsfd.html

(double) a / b
来源：http://dali.yueranfly.top/Article/details/gtugwahfxy.html

[S16] C：位操作置位
来源：http://dali.guannengcc.top/Article/details/gtrexqnbhf.html

x |= (1 << 3);
来源：http://dali.yongpay.top/Article/details/gtmdsxfyls.html

[S17] C：安全拼接字符串
来源：http://dali.nanxinkj.top/Article/details/gtlxrjeorz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.vqdsnc.cn/Article/details/gtukfosjgj.html

[S18] C：命令行参数
来源：http://dali.feifeiyinyue.top/Article/details/gtwqcvqobn.html

int main(int argc, char **argv)
来源：http://dali.pengpengdd.cyou/Article/details/gtrxempwax.html

[S19] C：快速排序
来源：http://dali.guannengcc.top/Article/details/gtsmwkhrbx.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xuanzx.com/Article/details/gtsfaekbqy.html

[S20] C：二分查找
来源：http://dali.yongpay.top/Article/details/gtilvjnftu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.wangdashe.top/Article/details/gtapnjgcpv.html

[S21] C：字符类别判断
来源：http://dali.snrcjt.cn/Article/details/gtiulxdrid.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhoulong.xyz/Article/details/gtnyhmqxgj.html

[S22] C：字符串转数字
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyldhxnpd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xinyue.icu/Article/details/gtgkvwnuba.html

[S23] C：随机数
来源：http://dali.iojbl.cn/Article/details/gtbfprcdlq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqicefobz.html

[S24] C：获取本地时间
来源：http://dali.tianlin.xyz/Article/details/gtgnhkfcbu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.xziqi.cn/Article/details/gtnjqeclox.html

[S25] C：内存拷贝
来源：http://dali.0kj1m.cn/Article/details/gtewofryrq.html

memcpy(dst, src, n);
来源：http://dali.ppjwa.cn/Article/details/gtthihbbzp.html

[S26] C：内存清零
来源：http://dali.ydzc1.top/Article/details/gtraztdpun.html

memset(a, 0, sizeof a);
来源：http://dali.jinghuilouyu.cn/Article/details/gtafgtnsqm.html

[S27] C：定义常量
来源：http://dali.nwbrower.top/Article/details/gtgjqxbsdc.html

const double PI = 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gtihpbvxuo.html

[S28] C：静态变量
来源：http://dali.haohaochexian.top/Article/details/gthzfmxmkl.html

static int counter = 0;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiexomzzw.html

[S29] C：变参函数
来源：http://dali.dianchejie.cn/Article/details/gtpzsmhynu.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.jqgufenzy.top/Article/details/gtjdsmbewp.html

[S30] C：头文件保护
来源：http://dali.sxryk.cn/Article/details/gtasvywigg.html

#ifndef X_H
来源：http://dali.sysykeji.top/Article/details/gtlnlvxglv.html

#define X_H
来源：http://dali.gotoacloud.top/Article/details/gtpqqlqavf.html

#endif
来源：http://dali.xinyue.icu/Article/details/gttwvappii.html

[S31] C++：Hello World
来源：http://dali.tianlin.xyz/Article/details/gthnhjuakh.html

#include <iostream>
来源：http://dali.yonumen.top/Article/details/gthrdezwlj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.guowangkeji.top/Article/details/gtoyajwjff.html

[S32] C++：字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaovsphda.html

std::string s = "hi";  s += "!";
来源：http://dali.shzxlz.cn/Article/details/gthhxqozgu.html

[S33] C++：vector 增删
来源：http://dali.snrcjt.cn/Article/details/gtzpgwvhps.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.iojbl.cn/Article/details/gthcjbbqhp.html

[S34] C++：遍历 vector
来源：http://dali.haohaochexian.top/Article/details/gtjqsrzyfl.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgtzploms.html

[S35] C++：map
来源：http://dali.zhiwuduotai.top/Article/details/gtvomgauax.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.chenlongwang.top/Article/details/gtfgleoggl.html

[S36] C++：unordered_map
来源：http://dali.dashuyun.cn/Article/details/gtlmucmxrx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuxming.cn/Article/details/gthyrxkvxh.html

[S37] C++：set
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzoumqhyk.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gzhubu.top/Article/details/gtncltubrh.html

[S38] C++：排序
来源：http://dali.dianchejie.cn/Article/details/gtgxhkdxuz.html

std::sort(v.begin(), v.end());
来源：http://dali.gotoacloud.top/Article/details/gtjikkznhe.html

[S39] C++：自定义比较器排序
来源：http://dali.yuanzhike.top/Article/details/gtixkwifin.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cashguo.top/Article/details/gtkgkbfyae.html

[S40] C++：查找元素
来源：http://dali.zhoulong.xyz/Article/details/gtruihpupf.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.chenjidiqi.icu/Article/details/gtctfdmkaz.html

[S41] C++：类与构造函数
来源：http://dali.316326.xyz/Article/details/gthgpeddkl.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.haohaochexian.top/Article/details/gtlarptzpw.html

[S42] C++：继承与虚函数
来源：http://dali.jqgfzy.top/Article/details/gtxukyfart.html

class B : public Base { public: void f() override {} };
来源：http://dali.shangyingyoupin.top/Article/details/gtonjldutn.html

[S43] C++：智能指针
来源：http://dali.yongpay.top/Article/details/gturjcfpkz.html

auto p = std::make_unique<int>(5);
来源：http://dali.jqgufenzy.top/Article/details/gtudvwphfs.html

[S44] C++：引用传参
来源：http://dali.daria6918.cn/Article/details/gtgunvowze.html

void inc(int &x) { ++x; }
来源：http://dali.zhengqikj.top/Article/details/gtiitfcpcb.html

[S45] C++：lambda
来源：http://dali.sxryk.cn/Article/details/gtwfrbbobq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.cdnleiting.top/Article/details/gtoxqwjwxn.html

[S46] C++：函数模板
来源：http://dali.yangfankeji.com/Article/details/gtsdjgchsc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.daxiang520.top/Article/details/gtdtijazen.html

[S47] C++：结构化绑定遍历
来源：http://dali.haohaochexian.top/Article/details/gtpqtfpvlr.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xinyue.icu/Article/details/gtwinmfznr.html

[S48] C++：逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gtsavjildt.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xziqi.cn/Article/details/gtqdzbdmsn.html

while (std::getline(in, line)) { }
来源：http://dali.sufxvd.cn/Article/details/gtwexnkhgq.html

[S49] C++：写文件
来源：http://dali.9152youxi.cn/Article/details/gtuuaeyyln.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.aibaodan.cn/Article/details/gtmoglatit.html

[S50] C++：格式化数字
来源：http://dali.tanke756.top/Article/details/gtqikhbmrx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nwbrower.top/Article/details/gtqcorkczn.html

[S51] C++：显式类型转换
来源：http://dali.tian-w.cn/Article/details/gtxzdvekfb.html

static_cast<double>(a) / b
来源：http://dali.daxiang520.top/Article/details/gtjxpjzrwu.html

[S52] C++：const 与 noexcept
来源：http://dali.9152youxi.cn/Article/details/gtbqihbnst.html

int size() const noexcept { return n_; }
来源：http://dali.ydzc1.top/Article/details/gtffzqgdiw.html

[S53] C++：移动语义
来源：http://dali.nanxinkj.top/Article/details/gtdouaenny.html

std::vector<int> w = std::move(v);
来源：http://dali.ydzc1.top/Article/details/gtchuusjwx.html

[S54] C++：异常处理
来源：http://dali.sweek.top/Article/details/gtgwzekqqw.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.snrcjt.cn/Article/details/gtuzdldocp.html

[S55] C++：结构化绑定
来源：http://dali.yuanzhike.top/Article/details/gtmuxxukfw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.aizwys.cn/Article/details/gtdwkcwgrp.html

[S56] C++：optional
来源：http://dali.zhongyouzk.top/Article/details/gtvqduamjk.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.daxiang520.top/Article/details/gtoagypqhu.html

[S57] C++：编译期常量
来源：http://dali.bjfxy.top/Article/details/gteuitmylg.html

constexpr int N = 10;
来源：http://dali.shanyushiyangtech.top/Article/details/gttmvzgfuq.html

[S58] C++：命名空间
来源：http://dali.yvedp.cn/Article/details/gtpjqidaqq.html

namespace ns { int f() { return 1; } }
来源：http://dali.fengsongda.top/Article/details/gtvbbjxzru.html

[S59] C++：静态断言
来源：http://dali.jiagoushi.top/Article/details/gtvlptrrqg.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.yonumen.top/Article/details/gtrqenxtgu.html

[S60] C++：遍历并删除元素
来源：http://dali.xinyue.icu/Article/details/gttvyxuoht.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinghuilouyu.cn/Article/details/gtixjcgtxt.html

================================================================================
来源：http://dali.jqgfzy.top/Article/details/gtvwvesklo.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.andypj.xyz/Article/details/gtcsqkmvsb.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtleiwnrtb.html

[T01] Kotlin：Hello World
来源：http://dali.dashuyun.cn/Article/details/gtnxyzutxm.html

println("Hello")
来源：http://dali.zycfv.cn/Article/details/gtimbzbspu.html

[T02] Kotlin：变量
来源：http://dali.zhengqikj.top/Article/details/gtipqqfyss.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.xziqi.cn/Article/details/gtnpsuepxf.html

[T03] Kotlin：字符串模板
来源：http://dali.cashguo.top/Article/details/gtifrroxqy.html

"值: $b"
来源：http://dali.sweek.top/Article/details/gtiantqadt.html

[T04] Kotlin：空安全
来源：http://dali.jianghu66.top/Article/details/gtabynvjow.html

val n: String? = null;  n?.length
来源：http://dali.bjfxy.top/Article/details/gtuhtlnjpn.html

[T05] Kotlin：when 表达式
来源：http://dali.jinyuanbaomall.cn/Article/details/gtznshbcgh.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.snrcjt.cn/Article/details/gtgrcfwpwb.html

[T06] Kotlin：集合映射
来源：http://dali.cucudq.cn/Article/details/gtbojxpyfv.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.guowangkeji.top/Article/details/gtuaxkwmvk.html

[T07] Kotlin：集合过滤
来源：http://dali.quarkkingdee.top/Article/details/gttszhsiqh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.nanxuanxn.top/Article/details/gtcffrdirz.html

[T08] Kotlin：数据类
来源：http://dali.zdqjudy.top/Article/details/gtvuynedjd.html

data class User(val name: String, val age: Int)
来源：http://dali.iojbl.cn/Article/details/gtuilqtjhf.html

[T09] Kotlin：扩展函数
来源：http://dali.jianghu66.top/Article/details/gtiogegysc.html

fun String.exclaim() = this + "!"
来源：http://dali.nanxinkj.top/Article/details/gtisambwgi.html

[T10] Kotlin：默认参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gttzncrysi.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.wangshuangyany.cn/Article/details/gtejcriyjv.html

[T11] Kotlin：协程
来源：http://dali.zhijiandao.cn/Article/details/gtxxocsdad.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.xinyue.icu/Article/details/gtgfquevcd.html

[T12] Kotlin：解构声明
来源：http://dali.jqgufenzy.top/Article/details/gtdjdsgnzb.html

val (a, b) = Pair(1, 2)
来源：http://dali.bjfxy.top/Article/details/gtifgtohcx.html

[T13] Kotlin：只读 Map
来源：http://dali.zhoulong.xyz/Article/details/gtbjoxtnxl.html

val m = mapOf("a" to 1)
来源：http://dali.yuanzhike.top/Article/details/gtrivzluhf.html

[T14] Kotlin：循环
来源：http://dali.feifeiyinyue.top/Article/details/gtzcleizne.html

for (i in 1..10) println(i)
来源：http://dali.smart0.xyz/Article/details/gtsiwcjoal.html

[T15] Kotlin：接口
来源：http://dali.hfpthk.cn/Article/details/gtnqtmizra.html

interface Shape { fun area(): Double }
来源：http://dali.jlsjyb.cn/Article/details/gtkkuscgpt.html

[T16] Swift：Hello World
来源：http://dali.daxiang520.top/Article/details/gtptqwbotf.html

print("Hello")
来源：http://dali.ivvv.top/Article/details/gtscqursos.html

[T17] Swift：变量与常量
来源：http://dali.hnqzz.top/Article/details/gtwpvoygrv.html

var a = 1;  let b = 2
来源：http://dali.havefunace.top/Article/details/gtlultvbkc.html

[T18] Swift：字符串插值
来源：http://dali.svipenyu.cn/Article/details/gtbdlfxbul.html

"值: \(b)"
来源：http://dali.yongpay.top/Article/details/gtetgjoidh.html

[T19] Swift：可选绑定
来源：http://dali.kuanghao11.cn/Article/details/gtqyrawkfy.html

if let n = opt { print(n) }
来源：http://dali.shanyushiyangtech.top/Article/details/gtqfkpkmjl.html

[T20] Swift：数组操作
来源：http://dali.zhixingplan.top/Article/details/gtueivotpi.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtflxqggpe.html

[T21] Swift：遍历
来源：http://dali.zhiwuduotai.top/Article/details/gtnccnjlrl.html

for x in a { print(x) }
来源：http://dali.feifeiyinyue.top/Article/details/gthynrkffm.html

[T22] Swift：字典
来源：http://dali.havefunace.top/Article/details/gtzxxgfnqm.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqnoouvxx.html

[T23] Swift：函数
来源：http://dali.zhiwuduotai.top/Article/details/gtmkfpkeym.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.chenzaomai.com/Article/details/gtdqouzcdo.html

[T24] Swift：闭包
来源：http://dali.zycfv.cn/Article/details/gtxvhzefgm.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.wangshuangyany.cn/Article/details/gtyupstati.html

[T25] Swift：结构体
来源：http://dali.hysaishi.cn/Article/details/gtsgvzmtzl.html

struct P { var x: Int }
来源：http://dali.dianchejie.cn/Article/details/gtrfowmebi.html

[T26] Swift：类与重写
来源：http://dali.hnxiangtu.top/Article/details/gtwjivuksb.html

class A: Base { override func f() {} }
来源：http://dali.wangdashe.top/Article/details/gtvfrcjrcv.html

[T27] Swift：错误处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtojsgqelp.html

do { try f() } catch { print(error) }
来源：http://dali.ybcxt.top/Article/details/gttylfswez.html

[T28] Swift：枚举
来源：http://dali.daxiang520.top/Article/details/gtlajrragf.html

enum Color { case red, green }
来源：http://dali.yj20258888.top/Article/details/gtywpmmmoy.html

[T29] Swift：guard 提前返回
来源：http://dali.hnxiangtu.top/Article/details/gtdwypzdcm.html

guard let x = opt else { return }
来源：http://dali.cqqwz.cn/Article/details/gtnkpnrbiw.html

[T30] Swift：协议
来源：http://dali.shzxlz.cn/Article/details/gtiyqqdywf.html

protocol Shape { func area() -> Double }
来源：http://dali.hnxiangtu.top/Article/details/gtooezqhtc.html

[T31] Lua：Hello World
来源：http://dali.cheryme.top/Article/details/gtearsmjuq.html

print("Hello")
来源：http://dali.jinqigfzy.top/Article/details/gtcjsqgoyz.html

[T32] Lua：局部变量
来源：http://dali.jlsjyb.cn/Article/details/gttsetshwh.html

local a = 1
来源：http://dali.hysaishi.cn/Article/details/gtqltkavdz.html

[T33] Lua：表（数组）
来源：http://dali.hysaishi.cn/Article/details/gtvlxvhtpm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gtrtvkfkdy.html

[T34] Lua：遍历表
来源：http://dali.aibaodan.cn/Article/details/gtyeibdkci.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.kuanghao11.cn/Article/details/gtjuyjpfcn.html

[T35] Lua：字典表
来源：http://dali.kuanghao11.cn/Article/details/gtzoznowta.html

local d = { a = 1 };  d.b = 2
来源：http://dali.zhiwuduotai.top/Article/details/gtgiijoruo.html

[T36] Lua：函数
来源：http://dali.smart0.xyz/Article/details/gthvmuhyug.html

function add(a, b) return a + b end
来源：http://dali.birdmap.top/Article/details/gtobiclyiv.html


<!-- 参考信息 -->