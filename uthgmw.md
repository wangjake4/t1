代发 wailian999

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrihydbtf.html

[R36] 并发执行多个任务
来源：http://dali.jqgufenzy.top/Article/details/gthytslndk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.dashuyun.cn/Article/details/gtgmrxotmy.html

[R37] 把输出赋给变量
来源：http://dali.cdnleiting.top/Article/details/gtizjsyimw.html

files=$(ls -1)
来源：http://dali.mhx1999.top/Article/details/gtdwmhynvx.html

[R38] 管道串联
来源：http://dali.feifeiyinyue.top/Article/details/gtijnshkki.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhixingplan.top/Article/details/gttiglzrwh.html

[R39] 重定向标准输出与错误
来源：http://dali.shzxlz.cn/Article/details/gtlmchfros.html

cmd > out.log 2>&1
来源：http://dali.wangdashe.top/Article/details/gtiuraymad.html

[R40] 追加写日志
来源：http://dali.c1oappe.top/Article/details/gtlunhbkki.html

echo "log" >> out.log
来源：http://dali.bjfxy.top/Article/details/gtkcsridbz.html

[R41] 丢弃输出
来源：http://dali.xuetiantiany.cn/Article/details/gtdckpkuos.html

cmd >/dev/null 2>&1
来源：http://dali.kuanghao11.cn/Article/details/gtvcnbgvhp.html

[R42] 输入重定向
来源：http://dali.fzhhl.top/Article/details/gtappgoenq.html

wc -l < a.txt
来源：http://dali.sxryk.cn/Article/details/gtoitvnuff.html

[R43] 按名字查找文件
来源：http://dali.wangdashe.top/Article/details/gthhuxtkck.html

find . -name "*.log" -type f
来源：http://dali.pengpengdd.cyou/Article/details/gtuhvuykkf.html

[R44] 按修改时间查找
来源：http://dali.jlsjyb.cn/Article/details/gtfspjcbta.html

find . -mtime -7 -type f
来源：http://dali.zhoulong.xyz/Article/details/gtpyckahfc.html

[R45] 批量删除
来源：http://dali.cdnleiting.top/Article/details/gtcphmnrzr.html

find . -name "*.tmp" -delete
来源：http://dali.xuetiantiany.cn/Article/details/gtqyxtmarh.html

[R46] 递归替换文件内容
来源：http://dali.yj202588.top/Article/details/gtuskhauyp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.fzhhl.top/Article/details/gtjltfqvcq.html

[R47] sed 单行替换
来源：http://dali.yj202588.top/Article/details/gtdmptncgu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.9152youxi.cn/Article/details/gtvmeecwnv.html

[R48] awk 取指定列
来源：http://dali.jinqigfzy.top/Article/details/gtlwczdvhk.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtzfdfyhhu.html

[R49] awk 带条件
来源：http://dali.sysykeji.top/Article/details/gtdmgfhscd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shanyushiyangtech.top/Article/details/gtsbpjlqhx.html

[R50] awk 求和
来源：http://dali.hysaishi.cn/Article/details/gtwnfkbtoc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.snrcjt.cn/Article/details/gtciizuvqb.html

[R51] 排序去重取前几
来源：http://dali.haohaochexian.top/Article/details/gtibtmnesg.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jyoumei.cn/Article/details/gtcwijvxgq.html

[R52] 统计行数
来源：http://dali.guannengcc.top/Article/details/gtatnktqgy.html

wc -l a.txt
来源：http://dali.daxiang520.top/Article/details/gtneynuuvh.html

[R53] 查看文件头与实时尾
来源：http://dali.xziqi.cn/Article/details/gtnhdqfqyh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yj202588.top/Article/details/gtbhxcsrhz.html

[R54] 比较两个文件
来源：http://dali.fengsongda.top/Article/details/gtlhzppvcz.html

diff a.txt b.txt
来源：http://dali.guannengcc.top/Article/details/gtzeefvvqa.html

[R55] 压缩与解压
来源：http://dali.c1oappe.top/Article/details/gttvtrvfbp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.fengsongda.top/Article/details/gtzxzwpbds.html

[R56] 远程拷贝
来源：http://dali.yonumen.top/Article/details/gtykcfqwbr.html

scp file user@host:/path/
来源：http://dali.nanxinkj.top/Article/details/gtobwxqpgg.html

[R57] 远程执行命令
来源：http://dali.yuxming.cn/Article/details/gtvqzvhaho.html

ssh user@host 'uptime'
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoiiagmfj.html

[R58] 下载文件
来源：http://dali.jinqigufen.top/Article/details/gtsjqcyrsa.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cdnleiting.top/Article/details/gtvmlnnghq.html

[R59] 发 POST JSON
来源：http://dali.andypj.xyz/Article/details/gtduutlynf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.snrcjt.cn/Article/details/gtsphjehgq.html

[R60] 只看 HTTP 状态码
来源：http://dali.smart0.xyz/Article/details/gtobnjedpk.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cashguo.top/Article/details/gtttikzago.html

[R61] 磁盘占用
来源：http://dali.hysaishi.cn/Article/details/gtxgefsroz.html

df -h;  du -sh *
来源：http://dali.sxryk.cn/Article/details/gttfesdjac.html

[R62] 找最占空间的文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtigtsiutp.html

du -ah . | sort -rh | head -10
来源：http://dali.xuanzx.com/Article/details/gtqcgmztpj.html

[R63] 内存与进程
来源：http://dali.jyoumei.cn/Article/details/gtjrpqbgzd.html

free -h;  ps aux | grep nginx
来源：http://dali.nwbrower.top/Article/details/gtfthehoad.html

[R64] 结束进程
来源：http://dali.yonumen.top/Article/details/gthbfdivgj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yonumen.top/Article/details/gtfbrzhbcf.html

[R65] 查看端口占用
来源：http://dali.hnqzz.top/Article/details/gtqnrsqequ.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.chenjidiqi.icu/Article/details/gtcvghefrj.html

[R66] 定时任务
来源：http://dali.yangfankeji.com/Article/details/gtvffchdwf.html

crontab -e;  crontab -l
来源：http://dali.cdnleiting.top/Article/details/gttikoeihq.html

[R67] 生成随机十六进制串
来源：http://dali.daxiang520.top/Article/details/gtotkwizyj.html

openssl rand -hex 16
来源：http://dali.jlsjyb.cn/Article/details/gtfutxryhd.html

[R68] 计算文件校验值
来源：http://dali.zhengqikj.top/Article/details/gtllyxgyvx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.daria6918.cn/Article/details/gtnlpzdwco.html

[R69] 生成随机密码
来源：http://dali.wangshuangyany.cn/Article/details/gtdrwettmu.html

head -c 16 /dev/urandom | base64
来源：http://dali.pengpengdd.cyou/Article/details/gtxvrcvftw.html

[R70] 时间戳与互转
来源：http://dali.yongpay.top/Article/details/gtzimqdobb.html

date +%s;  date -d @1700000000
来源：http://dali.yuxming.cn/Article/details/gtwslaqfzi.html

[R71] 日期格式化
来源：http://dali.snrcjt.cn/Article/details/gtcdgrelkx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ehwqpu.com/Article/details/gtpluugocr.html

[R72] 等待端口就绪
来源：http://dali.ivvv.top/Article/details/gtohmlwprn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xinyue.icu/Article/details/gtszjtmshv.html

[R73] 分割大日志
来源：http://dali.haohaochexian.top/Article/details/gttemtfngn.html

split -l 1000 big.log part_
来源：http://dali.daxiang520.top/Article/details/gtgwcibsou.html

[R74] 批量重命名
来源：http://dali.yangfankeji.com/Article/details/gtolgtvens.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.fzhhl.top/Article/details/gtkzinndln.html

[R75] 导出环境变量
来源：http://dali.yj20258888.top/Article/details/gtkhljvdfe.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.c1oappe.top/Article/details/gtsiyjtihm.html

[R76] 使用临时文件
来源：http://dali.shuidangran.top/Article/details/gtdjsfkbnm.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.birdmap.top/Article/details/gtopcvpetk.html

[R77] 读取用户输入
来源：http://dali.vqdsnc.cn/Article/details/gtldgdrqfp.html

read -rp "请输入: " ans
来源：http://dali.shanyushiyangtech.top/Article/details/gtnlemdrtl.html

[R78] 交互式菜单
来源：http://dali.guowangkeji.top/Article/details/gtsieishtp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gtqxpmcldy.html

[R79] 解析命令行选项
来源：http://dali.jyoumei.cn/Article/details/gttlqpdaag.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shzxlz.cn/Article/details/gtjnthvinn.html

[R80] 查看脚本执行耗时
来源：http://dali.mhx1999.top/Article/details/gtktqxeewg.html

time ./run.sh
来源：http://dali.9152youxi.cn/Article/details/gtnoefhcfb.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtnhslhmom.html

S. C / C++ 专题
来源：http://dali.redwolf501.top/Article/details/gttkonkgif.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtlrvwgaat.html

[S01] C：Hello World
来源：http://dali.smart0.xyz/Article/details/gttvggsvyd.html

#include <stdio.h>
来源：http://dali.zhengqikj.top/Article/details/gtaystejwj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jiagoushi.top/Article/details/gtxunuwtdy.html

[S02] C：变量与格式化输出
来源：http://dali.wangdashe.top/Article/details/gtnmzbuaqp.html

int a = 10; printf("%d\n", a);
来源：http://dali.yuxming.cn/Article/details/gtlzilpasw.html

[S03] C：读入整数
来源：http://dali.c1oappe.top/Article/details/gtgvpbpehl.html

int x; scanf("%d", &x);
来源：http://dali.chenzaomai.com/Article/details/gtilfeoqnd.html

[S04] C：字符串复制
来源：http://dali.quarkkingdee.top/Article/details/gthnjrneox.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinqigufen.top/Article/details/gtmpvvxxrc.html

[S05] C：字符串长度
来源：http://dali.ydzc1.top/Article/details/gtqkyumjpc.html

strlen(s)
来源：http://dali.hammf.cn/Article/details/gtuxqsmcok.html

[S06] C：字符串比较
来源：http://dali.iojbl.cn/Article/details/gtxnytbgav.html

strcmp(a, b) == 0
来源：http://dali.jyoumei.cn/Article/details/gtpxpomonu.html

[S07] C：数组遍历求和
来源：http://dali.nanxuanxn.top/Article/details/gtvnvmgihg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.tianlin.xyz/Article/details/gtqxeheirt.html

[S08] C：动态内存分配与释放
来源：http://dali.jianghu66.top/Article/details/gtvaunmiql.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.wangdashe.top/Article/details/gtciuhlnga.html

[S09] C：结构体定义与初始化
来源：http://dali.jianghu66.top/Article/details/gtijiciwhd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hammf.cn/Article/details/gtcwlxkiwv.html

[S10] C：指针与解引用
来源：http://dali.quarkkingdee.top/Article/details/gtxafadyep.html

int *p = &a;  *p = 5;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlgrbnfzl.html

[S11] C：逐行读文件
来源：http://dali.zhiwuduotai.top/Article/details/gttipehzbp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sweek.top/Article/details/gtuchspojs.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ehwqpu.com/Article/details/gtsrwwdovl.html

fclose(f);
来源：http://dali.tian-w.cn/Article/details/gtarxvdqxm.html

[S12] C：写文件
来源：http://dali.sysykeji.top/Article/details/gtpfnunheq.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.dashuyun.cn/Article/details/gtlqfjwttw.html

[S13] C：宏定义
来源：http://dali.shanyushiyangtech.top/Article/details/gtscrxzkml.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmjzkvphn.html

[S14] C：枚举
来源：http://dali.chenjidiqi.icu/Article/details/gtiyhrbmam.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.wangdashe.top/Article/details/gtdfzetmjg.html

[S15] C：类型转换
来源：http://dali.jqgufenzy.top/Article/details/gtehlxxarc.html

(double) a / b
来源：http://dali.haohaochexian.top/Article/details/gtexfvxhqt.html

[S16] C：位操作置位
来源：http://dali.nanxinkj.top/Article/details/gtyqdxlois.html

x |= (1 << 3);
来源：http://dali.zhiwuduotai.top/Article/details/gtgzyicqvt.html

[S17] C：安全拼接字符串
来源：http://dali.ehwqpu.com/Article/details/gtbgfjruyu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.iojbl.cn/Article/details/gtglgmbvjd.html

[S18] C：命令行参数
来源：http://dali.316326.xyz/Article/details/gtowwrmeir.html

int main(int argc, char **argv)
来源：http://dali.ybcxt.top/Article/details/gtqbunbxdp.html

[S19] C：快速排序
来源：http://dali.yj20258.top/Article/details/gtvxuvbbdp.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jyoumei.cn/Article/details/gtkrkjfapr.html

[S20] C：二分查找
来源：http://dali.quarkkingdee.top/Article/details/gtrsrxbaqm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hnxiangtu.top/Article/details/gtlhrcajol.html

[S21] C：字符类别判断
来源：http://dali.wangdashe.top/Article/details/gtpkdrptky.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jqgfzy.top/Article/details/gtawqslwpm.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gtnzwsvtls.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhengqikj.top/Article/details/gtnjdiksuz.html

[S23] C：随机数
来源：http://dali.jlsjyb.cn/Article/details/gtnmzjpign.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cucudq.cn/Article/details/gtamxcrqxf.html

[S24] C：获取本地时间
来源：http://dali.c1oappe.top/Article/details/gtqmxmsypw.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yuxming.cn/Article/details/gtsoydshhh.html

[S25] C：内存拷贝
来源：http://dali.hywenlv.cn/Article/details/gtctpqucsy.html

memcpy(dst, src, n);
来源：http://dali.ehwqpu.com/Article/details/gtopohwenm.html

[S26] C：内存清零
来源：http://dali.redwolf501.top/Article/details/gtrahricpu.html

memset(a, 0, sizeof a);
来源：http://dali.svipenyu.cn/Article/details/gtfcnwfbtf.html

[S27] C：定义常量
来源：http://dali.yuxming.cn/Article/details/gtbtcwuwrf.html

const double PI = 3.14159;
来源：http://dali.xinyue.icu/Article/details/gtqnciodkk.html

[S28] C：静态变量
来源：http://dali.dashuyun.cn/Article/details/gtazqgvsit.html

static int counter = 0;
来源：http://dali.quarkkingdee.top/Article/details/gtvggltabu.html

[S29] C：变参函数
来源：http://dali.snrcjt.cn/Article/details/gtjsbagoob.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhiwuduotai.top/Article/details/gtiioydzst.html

[S30] C：头文件保护
来源：http://dali.zhiwuduotai.top/Article/details/gttrslggdq.html

#ifndef X_H
来源：http://dali.chenzaomai.com/Article/details/gtihlswbxj.html

#define X_H
来源：http://dali.kuanghao11.cn/Article/details/gtzqzwrgsr.html

#endif
来源：http://dali.ehwqpu.com/Article/details/gtotgreugj.html

[S31] C++：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtyycdcovk.html

#include <iostream>
来源：http://dali.aibaodan.cn/Article/details/gttamqyxws.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtyxeqmqeh.html

[S32] C++：字符串
来源：http://dali.wangdashe.top/Article/details/gtmpazqxkp.html

std::string s = "hi";  s += "!";
来源：http://dali.jianghu66.top/Article/details/gtmijsnjpe.html

[S33] C++：vector 增删
来源：http://dali.xinyue.icu/Article/details/gtyygxhbyl.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ehwqpu.com/Article/details/gtpdykrlog.html

[S34] C++：遍历 vector
来源：http://dali.vqdsnc.cn/Article/details/gtymuixqvj.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.andypj.xyz/Article/details/gtlmwlmyta.html

[S35] C++：map
来源：http://dali.svipenyu.cn/Article/details/gteljyrwwg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtkernzzjr.html

[S36] C++：unordered_map
来源：http://dali.pycfn.com/Article/details/gtplbyboci.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nwbrower.top/Article/details/gtvxbidmfz.html

[S37] C++：set
来源：http://dali.c1oappe.top/Article/details/gtjymkruhh.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cqqwz.cn/Article/details/gtynfzlpad.html

[S38] C++：排序
来源：http://dali.zdqjudy.top/Article/details/gtrqylnjwr.html

std::sort(v.begin(), v.end());
来源：http://dali.pycfn.com/Article/details/gtkhiffftl.html

[S39] C++：自定义比较器排序
来源：http://dali.cdnleiting.top/Article/details/gtrnjluuxv.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.daxiang520.top/Article/details/gttaufxixu.html

[S40] C++：查找元素
来源：http://dali.shanyushiyangtech.top/Article/details/gtlakrefwx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cashguo.top/Article/details/gtywifinzh.html

[S41] C++：类与构造函数
来源：http://dali.gotoacloud.top/Article/details/gtxhqqylfx.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jqgfzy.top/Article/details/gtpfjjizsw.html

[S42] C++：继承与虚函数
来源：http://dali.bjfxy.top/Article/details/gtamngenbc.html

class B : public Base { public: void f() override {} };
来源：http://dali.shzxlz.cn/Article/details/gtvoqwvlwq.html

[S43] C++：智能指针
来源：http://dali.meibo888.top/Article/details/gtticbuwbn.html

auto p = std::make_unique<int>(5);
来源：http://dali.xuetiantiany.cn/Article/details/gteecivobr.html

[S44] C++：引用传参
来源：http://dali.shanyushiyangtech.top/Article/details/gtoliluffa.html

void inc(int &x) { ++x; }
来源：http://dali.9152youxi.cn/Article/details/gtjthzokki.html

[S45] C++：lambda
来源：http://dali.yj20258888.top/Article/details/gtqqjxwbhs.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.kuanghao11.cn/Article/details/gtnmrihkgf.html

[S46] C++：函数模板
来源：http://dali.fengsongda.top/Article/details/gthpghsqoc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hnxiangtu.top/Article/details/gtwjcdbdiz.html

[S47] C++：结构化绑定遍历
来源：http://dali.feifeiyinyue.top/Article/details/gtjutkqark.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.guannengcc.top/Article/details/gtzfdkyqtq.html

[S48] C++：逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gtsqrgddpi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.fzhhl.top/Article/details/gtozgxustn.html

while (std::getline(in, line)) { }
来源：http://dali.shanyushiyangtech.top/Article/details/gttaqnisou.html

[S49] C++：写文件
来源：http://dali.xinyue.icu/Article/details/gtmjgybowo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.chenjidiqi.icu/Article/details/gtvhpejjga.html

[S50] C++：格式化数字
来源：http://dali.redwolf501.top/Article/details/gtrjpimlaj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yongpay.top/Article/details/gtbsqcuudq.html

[S51] C++：显式类型转换
来源：http://dali.yj20258.top/Article/details/gtacaebhxw.html

static_cast<double>(a) / b
来源：http://dali.jinghuilouyu.cn/Article/details/gtzvrghbmb.html

[S52] C++：const 与 noexcept
来源：http://dali.yj20258888.top/Article/details/gtxzdljzjb.html

int size() const noexcept { return n_; }
来源：http://dali.mhx1999.top/Article/details/gtpfysxbak.html

[S53] C++：移动语义
来源：http://dali.chenlongwang.top/Article/details/gtgdbpkvvw.html

std::vector<int> w = std::move(v);
来源：http://dali.jinqigfzy.top/Article/details/gtzshabfey.html

[S54] C++：异常处理
来源：http://dali.dianchejie.cn/Article/details/gtjwpvbtjt.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xziqi.cn/Article/details/gtkbrvmsej.html

[S55] C++：结构化绑定
来源：http://dali.jianghu66.top/Article/details/gtishfplbw.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.yj20258.top/Article/details/gtaztwvcjr.html

[S56] C++：optional
来源：http://dali.ydzc1.top/Article/details/gtbnoizbea.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yueranfly.top/Article/details/gtreheflse.html

[S57] C++：编译期常量
来源：http://dali.wangdashe.top/Article/details/gtvawnhrwk.html

constexpr int N = 10;
来源：http://dali.chenzaomai.com/Article/details/gtgtlomxzj.html

[S58] C++：命名空间
来源：http://dali.ybcxt.top/Article/details/gtfslacgyq.html

namespace ns { int f() { return 1; } }
来源：http://dali.havefunace.top/Article/details/gthwyrfefc.html

[S59] C++：静态断言
来源：http://dali.hongshengwenyu.top/Article/details/gtfcxdcqth.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.wangdashe.top/Article/details/gtndlbwfft.html

[S60] C++：遍历并删除元素
来源：http://dali.hywenlv.cn/Article/details/gthpdcknyd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.aibaodan.cn/Article/details/gtjigfnqvc.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtbanqgqyx.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.316326.xyz/Article/details/gtpkvleizc.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtouwsijuf.html

[T01] Kotlin：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzfazrzqv.html

println("Hello")
来源：http://dali.cdnleiting.top/Article/details/gtbjhmafpd.html

[T02] Kotlin：变量
来源：http://dali.mhx1999.top/Article/details/gtbbxmrmds.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shanyushiyangtech.top/Article/details/gtdajwrits.html

[T03] Kotlin：字符串模板
来源：http://dali.0kj1m.cn/Article/details/gtavdxcmbi.html

"值: $b"
来源：http://dali.iojbl.cn/Article/details/gtowiqqkzs.html

[T04] Kotlin：空安全
来源：http://dali.redwolf501.top/Article/details/gtzwkfyary.html

val n: String? = null;  n?.length
来源：http://dali.zhongyouzk.top/Article/details/gtmypfecrj.html

[T05] Kotlin：when 表达式
来源：http://dali.sysykeji.top/Article/details/gteqloommw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yangfankeji.com/Article/details/gtekyegyvp.html

[T06] Kotlin：集合映射
来源：http://dali.316326.xyz/Article/details/gtrfjcizxu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.zhixingplan.top/Article/details/gttljhfvgf.html

[T07] Kotlin：集合过滤
来源：http://dali.nwbrower.top/Article/details/gtedsvpdwi.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.dianchejie.cn/Article/details/gthxtzyfgi.html

[T08] Kotlin：数据类
来源：http://dali.havefunace.top/Article/details/gtpdrdgjpe.html

data class User(val name: String, val age: Int)
来源：http://dali.zhiwuduotai.top/Article/details/gtufzwfdyd.html

[T09] Kotlin：扩展函数
来源：http://dali.chenlongwang.top/Article/details/gtqianudhl.html

fun String.exclaim() = this + "!"
来源：http://dali.bjfxy.top/Article/details/gtizsppqzp.html

[T10] Kotlin：默认参数
来源：http://dali.snrcjt.cn/Article/details/gtyyojpqeo.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hfpthk.cn/Article/details/gtjrqvjvba.html

[T11] Kotlin：协程
来源：http://dali.zhixingplan.top/Article/details/gtlivjwsne.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtesitmysi.html

[T12] Kotlin：解构声明
来源：http://dali.gotoacloud.top/Article/details/gtlsxcmfkf.html

val (a, b) = Pair(1, 2)
来源：http://dali.gzhubu.top/Article/details/gtdjmzuzii.html

[T13] Kotlin：只读 Map
来源：http://dali.shzxlz.cn/Article/details/gtmgdzpagw.html

val m = mapOf("a" to 1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqghzioyq.html

[T14] Kotlin：循环
来源：http://dali.ydzc1.top/Article/details/gtqpypwzll.html

for (i in 1..10) println(i)
来源：http://dali.ivvv.top/Article/details/gtigzupcqb.html

[T15] Kotlin：接口
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcmzucnfz.html

interface Shape { fun area(): Double }
来源：http://dali.tianlin.xyz/Article/details/gthmxjzkor.html

[T16] Swift：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtjexqypev.html

print("Hello")
来源：http://dali.hywenlv.cn/Article/details/gtlpdwybdr.html

[T17] Swift：变量与常量
来源：http://dali.jlsjyb.cn/Article/details/gtoluryjbz.html

var a = 1;  let b = 2
来源：http://dali.ywan-chungtsiang.top/Article/details/gtncbonbzh.html

[T18] Swift：字符串插值
来源：http://dali.zhijiandao.cn/Article/details/gtndhtyvvc.html

"值: \(b)"
来源：http://dali.daria6918.cn/Article/details/gtqlugpwvf.html

[T19] Swift：可选绑定
来源：http://dali.cheryme.top/Article/details/gtgpgebicy.html

if let n = opt { print(n) }
来源：http://dali.haohaochexian.top/Article/details/gtfaaqwhdq.html

[T20] Swift：数组操作
来源：http://dali.jinghuilouyu.cn/Article/details/gtyioldxfk.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cheryme.top/Article/details/gtundmnlqo.html

[T21] Swift：遍历
来源：http://dali.xuanzx.com/Article/details/gtepuctuyb.html

for x in a { print(x) }
来源：http://dali.haohaochexian.top/Article/details/gtbdwfvcav.html

[T22] Swift：字典
来源：http://dali.zdqjudy.top/Article/details/gtyuzttuvn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.vqdsnc.cn/Article/details/gtuswtktoz.html

[T23] Swift：函数
来源：http://dali.cucudq.cn/Article/details/gtrygadubm.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.dianchejie.cn/Article/details/gtnbeqpbkd.html

[T24] Swift：闭包
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtisdrpueo.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.chenjidiqi.icu/Article/details/gtvezapvuc.html

[T25] Swift：结构体
来源：http://dali.cashguo.top/Article/details/gtprveqjxl.html

struct P { var x: Int }
来源：http://dali.haohaochexian.top/Article/details/gtxqmktmld.html

[T26] Swift：类与重写
来源：http://dali.fengsongda.top/Article/details/gtjctvrnqh.html

class A: Base { override func f() {} }
来源：http://dali.xuetiantiany.cn/Article/details/gtfnjtyyam.html

[T27] Swift：错误处理
来源：http://dali.xinyue.icu/Article/details/gtnyhmtwxl.html

do { try f() } catch { print(error) }
来源：http://dali.chenjidiqi.icu/Article/details/gtvatbnjye.html

[T28] Swift：枚举
来源：http://dali.c1oappe.top/Article/details/gthqreyttn.html

enum Color { case red, green }
来源：http://dali.xinyue.icu/Article/details/gtxfveawdf.html

[T29] Swift：guard 提前返回
来源：http://dali.yueranfly.top/Article/details/gtrtdpjupq.html

guard let x = opt else { return }
来源：http://dali.gzhubu.top/Article/details/gtzjbwjhnr.html

[T30] Swift：协议
来源：http://dali.xinyue.icu/Article/details/gteofwxixd.html

protocol Shape { func area() -> Double }
来源：http://dali.havefunace.top/Article/details/gthlfdgcio.html

[T31] Lua：Hello World
来源：http://dali.xylfe.cn/Article/details/gtoluaztul.html

print("Hello")
来源：http://dali.bjfxy.top/Article/details/gtltfvdhjl.html

[T32] Lua：局部变量
来源：http://dali.sxryk.cn/Article/details/gtpfedqszg.html

local a = 1
来源：http://dali.fzhhl.top/Article/details/gttgwqbxth.html

[T33] Lua：表（数组）
来源：http://dali.dashuyun.cn/Article/details/gtgrdriswi.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.feifeiyinyue.top/Article/details/gtefyvjqoa.html

[T34] Lua：遍历表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpgxgrvpm.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.c1oappe.top/Article/details/gtkqqpbfhe.html

[T35] Lua：字典表
来源：http://dali.tanke756.top/Article/details/gtpoqltzbr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.smart0.xyz/Article/details/gtwgfrljzr.html

[T36] Lua：函数
来源：http://dali.redwolf501.top/Article/details/gtwtjxibks.html

function add(a, b) return a + b end
来源：http://dali.c1oappe.top/Article/details/gtpzaklfuf.html

[T37] Lua：字符串拼接
来源：http://dali.wangshuangyany.cn/Article/details/gteifaqmtu.html

"a" .. "b"
来源：http://dali.yuxming.cn/Article/details/gtolbtyqin.html

[T38] Lua：条件
来源：http://dali.gzhubu.top/Article/details/gtnhzhjcwt.html

if x > 0 then print("正") end
来源：http://dali.ppjwa.cn/Article/details/gtdjvjgpsu.html


<!-- 参考信息 -->