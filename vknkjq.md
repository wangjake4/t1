代发 wailian999

files=$(ls -1)
来源：http://dali.sysykeji.top/Article/details/gtpgznotnm.html

[R38] 管道串联
来源：http://dali.jinqigufen.top/Article/details/gtfrpsaffs.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jinghuilouyu.cn/Article/details/gtzitauldx.html

[R39] 重定向标准输出与错误
来源：http://dali.wangdashe.top/Article/details/gtwvpeipuj.html

cmd > out.log 2>&1
来源：http://dali.pycfn.com/Article/details/gtxsiguana.html

[R40] 追加写日志
来源：http://dali.shanyushiyangtech.top/Article/details/gtamvjhlwt.html

echo "log" >> out.log
来源：http://dali.haohaochexian.top/Article/details/gtlteerrcj.html

[R41] 丢弃输出
来源：http://dali.ehwqpu.com/Article/details/gtmydurcji.html

cmd >/dev/null 2>&1
来源：http://dali.smart0.xyz/Article/details/gtnqewkvug.html

[R42] 输入重定向
来源：http://dali.zhaomingkeji.xyz/Article/details/gtklajtvhd.html

wc -l < a.txt
来源：http://dali.vqdsnc.cn/Article/details/gtmezgqfzq.html

[R43] 按名字查找文件
来源：http://dali.shuidangran.top/Article/details/gtejazgltn.html

find . -name "*.log" -type f
来源：http://dali.pycfn.com/Article/details/gtiqemazfh.html

[R44] 按修改时间查找
来源：http://dali.xuetiantiany.cn/Article/details/gtdbimxizv.html

find . -mtime -7 -type f
来源：http://dali.yongpay.top/Article/details/gtgedouljp.html

[R45] 批量删除
来源：http://dali.zhiwuduotai.top/Article/details/gthtstmbac.html

find . -name "*.tmp" -delete
来源：http://dali.jlsjyb.cn/Article/details/gtqzopwluk.html

[R46] 递归替换文件内容
来源：http://dali.tian-w.cn/Article/details/gtzqskcegi.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.mhx1999.top/Article/details/gtzebazbun.html

[R47] sed 单行替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtthpkzkau.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.havefunace.top/Article/details/gtxyyqqyzp.html

[R48] awk 取指定列
来源：http://dali.yvedp.cn/Article/details/gtgghdxdsw.html

awk '{print $1, $3}' a.txt
来源：http://dali.fengsongda.top/Article/details/gternivqta.html

[R49] awk 带条件
来源：http://dali.ppjwa.cn/Article/details/gtqxodshle.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.havefunace.top/Article/details/gtytbbgtag.html

[R50] awk 求和
来源：http://dali.wangshuangyany.cn/Article/details/gtxjhiybib.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.haohaochexian.top/Article/details/gtlilyflhh.html

[R51] 排序去重取前几
来源：http://dali.jqgfzy.top/Article/details/gtdffzldxm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ivvv.top/Article/details/gtvpbwbtqc.html

[R52] 统计行数
来源：http://dali.tanke756.top/Article/details/gtjfgqnqig.html

wc -l a.txt
来源：http://dali.snrcjt.cn/Article/details/gtrvmjmqfb.html

[R53] 查看文件头与实时尾
来源：http://dali.wangdashe.top/Article/details/gtifjsufyk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hfpthk.cn/Article/details/gtdwlnbvxw.html

[R54] 比较两个文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtgxbjfcbv.html

diff a.txt b.txt
来源：http://dali.gogol.net.cn/Article/details/gtlqpdlbcl.html

[R55] 压缩与解压
来源：http://dali.mhx1999.top/Article/details/gtmpunmmda.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhengqikj.top/Article/details/gtfnxntirz.html

[R56] 远程拷贝
来源：http://dali.hywenlv.cn/Article/details/gtnfxqyxhj.html

scp file user@host:/path/
来源：http://dali.hongshengwenyu.top/Article/details/gtgjzmspgk.html

[R57] 远程执行命令
来源：http://dali.yangfankeji.com/Article/details/gtqadmmsob.html

ssh user@host 'uptime'
来源：http://dali.gzhubu.top/Article/details/gtgwvkhfqy.html

[R58] 下载文件
来源：http://dali.cdnleiting.top/Article/details/gtrapkwbvm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.316326.xyz/Article/details/gtlmzuhbny.html

[R59] 发 POST JSON
来源：http://dali.sysykeji.top/Article/details/gtzqobrzsz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.snrcjt.cn/Article/details/gtocsderwl.html

[R60] 只看 HTTP 状态码
来源：http://dali.hfpthk.cn/Article/details/gtafjjocig.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.redwolf501.top/Article/details/gtssbnztjb.html

[R61] 磁盘占用
来源：http://dali.jinghuilouyu.cn/Article/details/gtrouvyuke.html

df -h;  du -sh *
来源：http://dali.hfpthk.cn/Article/details/gtnuovqccy.html

[R62] 找最占空间的文件
来源：http://dali.sufxvd.cn/Article/details/gtqycahmui.html

du -ah . | sort -rh | head -10
来源：http://dali.yongpay.top/Article/details/gtleuojhro.html

[R63] 内存与进程
来源：http://dali.havefunace.top/Article/details/gtubeifwtf.html

free -h;  ps aux | grep nginx
来源：http://dali.xuetiantiany.cn/Article/details/gtahdkagms.html

[R64] 结束进程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzkissecy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.9152youxi.cn/Article/details/gthtedztcl.html

[R65] 查看端口占用
来源：http://dali.ivvv.top/Article/details/gtqvxwqxwt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yangfankeji.com/Article/details/gtwdrjkkhy.html

[R66] 定时任务
来源：http://dali.xziqi.cn/Article/details/gtamboygfa.html

crontab -e;  crontab -l
来源：http://dali.chenjidiqi.icu/Article/details/gtsizkamvc.html

[R67] 生成随机十六进制串
来源：http://dali.aibaodan.cn/Article/details/gtumpwxnwo.html

openssl rand -hex 16
来源：http://dali.cashguo.top/Article/details/gtmxigesgb.html

[R68] 计算文件校验值
来源：http://dali.shangyingyoupin.top/Article/details/gtqsbfoczq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.vqdsnc.cn/Article/details/gtflhrfigy.html

[R69] 生成随机密码
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqrbuecqs.html

head -c 16 /dev/urandom | base64
来源：http://dali.gogol.net.cn/Article/details/gtmnmwijzh.html

[R70] 时间戳与互转
来源：http://dali.xziqi.cn/Article/details/gtikdwzcxx.html

date +%s;  date -d @1700000000
来源：http://dali.chenjidiqi.icu/Article/details/gtsxxtpzjb.html

[R71] 日期格式化
来源：http://dali.jlsjyb.cn/Article/details/gtjxlhcncc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.quarkkingdee.top/Article/details/gtydnbafnu.html

[R72] 等待端口就绪
来源：http://dali.chenlongwang.top/Article/details/gtwqlpxxgn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jqgfzy.top/Article/details/gtzukpxixp.html

[R73] 分割大日志
来源：http://dali.jinqigfzy.top/Article/details/gtyiliiiaa.html

split -l 1000 big.log part_
来源：http://dali.quarkkingdee.top/Article/details/gtmjspafvg.html

[R74] 批量重命名
来源：http://dali.gogol.net.cn/Article/details/gtuivlvfhj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.cdnleiting.top/Article/details/gtadxeegzm.html

[R75] 导出环境变量
来源：http://dali.xylfe.cn/Article/details/gtzjoxoehn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yuanzhike.top/Article/details/gtzokmuott.html

[R76] 使用临时文件
来源：http://dali.chenlongwang.top/Article/details/gtnqesqsww.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.sweek.top/Article/details/gtolkyopfg.html

[R77] 读取用户输入
来源：http://dali.wangdashe.top/Article/details/gtbprgnjqv.html

read -rp "请输入: " ans
来源：http://dali.guannengcc.top/Article/details/gtgohatsfv.html

[R78] 交互式菜单
来源：http://dali.zhixingplan.top/Article/details/gtfmgerzfk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zycfv.cn/Article/details/gtowyzoyhw.html

[R79] 解析命令行选项
来源：http://dali.birdmap.top/Article/details/gtrdaubnau.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhiwuduotai.top/Article/details/gtprcsxffx.html

[R80] 查看脚本执行耗时
来源：http://dali.hfpthk.cn/Article/details/gttcvvbqkh.html

time ./run.sh
来源：http://dali.yj20258.top/Article/details/gtafrvlkcu.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtrwjgetxn.html

S. C / C++ 专题
来源：http://dali.ybcxt.top/Article/details/gtkwfjqocu.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqbxjvufm.html

[S01] C：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtjplxbsfk.html

#include <stdio.h>
来源：http://dali.sweek.top/Article/details/gtanfofdem.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jyoumei.cn/Article/details/gtabtnvzuf.html

[S02] C：变量与格式化输出
来源：http://dali.zhengqikj.top/Article/details/gtfigqsrso.html

int a = 10; printf("%d\n", a);
来源：http://dali.haohaochexian.top/Article/details/gtzoblbyku.html

[S03] C：读入整数
来源：http://dali.andypj.xyz/Article/details/gtqiuydjoo.html

int x; scanf("%d", &x);
来源：http://dali.gotoacloud.top/Article/details/gtdnrlyaaj.html

[S04] C：字符串复制
来源：http://dali.9152youxi.cn/Article/details/gtaotbybvw.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shanyushiyangtech.top/Article/details/gtypfqzzfw.html

[S05] C：字符串长度
来源：http://dali.zhiwuduotai.top/Article/details/gtpveutuql.html

strlen(s)
来源：http://dali.wangshuangyany.cn/Article/details/gtlkqcjxjm.html

[S06] C：字符串比较
来源：http://dali.dashuyun.cn/Article/details/gtxhevxeqg.html

strcmp(a, b) == 0
来源：http://dali.guowangkeji.top/Article/details/gtirunicvo.html

[S07] C：数组遍历求和
来源：http://dali.gotoacloud.top/Article/details/gtdcaruppf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shangyingyoupin.top/Article/details/gtfuhmqhbs.html

[S08] C：动态内存分配与释放
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsqcqyadj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yj20258888.top/Article/details/gtxoqgafki.html

[S09] C：结构体定义与初始化
来源：http://dali.xylfe.cn/Article/details/gtbkgunoew.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jqgfzy.top/Article/details/gtonixaqmo.html

[S10] C：指针与解引用
来源：http://dali.wangdashe.top/Article/details/gtqbufxsdm.html

int *p = &a;  *p = 5;
来源：http://dali.ybcxt.top/Article/details/gtajrqzkty.html

[S11] C：逐行读文件
来源：http://dali.zhongyouzk.top/Article/details/gtlsrarpsn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sysykeji.top/Article/details/gtgrhcavyp.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xylfe.cn/Article/details/gtoopkmoez.html

fclose(f);
来源：http://dali.aizwys.cn/Article/details/gtxdvnhcuf.html

[S12] C：写文件
来源：http://dali.sweek.top/Article/details/gtoboftzca.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.redwolf501.top/Article/details/gtzbmppxkz.html

[S13] C：宏定义
来源：http://dali.ehwqpu.com/Article/details/gtfeurqebz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jinghuilouyu.cn/Article/details/gtfliowluy.html

[S14] C：枚举
来源：http://dali.aibaodan.cn/Article/details/gtknhxdaeh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yangfankeji.com/Article/details/gtgeupvgdh.html

[S15] C：类型转换
来源：http://dali.redwolf501.top/Article/details/gtjpuqpdbq.html

(double) a / b
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxoskgokk.html

[S16] C：位操作置位
来源：http://dali.sufxvd.cn/Article/details/gtoevfpbiq.html

x |= (1 << 3);
来源：http://dali.yuxming.cn/Article/details/gtxacvqwpy.html

[S17] C：安全拼接字符串
来源：http://dali.xziqi.cn/Article/details/gtmmgntvfi.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.quarkkingdee.top/Article/details/gtqixxpbmt.html

[S18] C：命令行参数
来源：http://dali.yuxming.cn/Article/details/gtbzzkfyub.html

int main(int argc, char **argv)
来源：http://dali.tian-w.cn/Article/details/gtljdrjopt.html

[S19] C：快速排序
来源：http://dali.jqgufenzy.top/Article/details/gtwcimrqwl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthkrmoumr.html

[S20] C：二分查找
来源：http://dali.guowangkeji.top/Article/details/gtcsywmjud.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yonumen.top/Article/details/gtpxbigbkh.html

[S21] C：字符类别判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdzxmfkun.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.pycfn.com/Article/details/gtpvvsxrdy.html

[S22] C：字符串转数字
来源：http://dali.tanke756.top/Article/details/gtzgzhkhib.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yj20258.top/Article/details/gtoezeqovf.html

[S23] C：随机数
来源：http://dali.mhx1999.top/Article/details/gtkwxdwkne.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.0kj1m.cn/Article/details/gtaythcwff.html

[S24] C：获取本地时间
来源：http://dali.redwolf501.top/Article/details/gteyyygbty.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.tian-w.cn/Article/details/gtigmuklax.html

[S25] C：内存拷贝
来源：http://dali.zhengqikj.top/Article/details/gtdplvzlbg.html

memcpy(dst, src, n);
来源：http://dali.jinghuilouyu.cn/Article/details/gtzlssfrhf.html

[S26] C：内存清零
来源：http://dali.smart0.xyz/Article/details/gtuhlxbsnt.html

memset(a, 0, sizeof a);
来源：http://dali.feifeiyinyue.top/Article/details/gttokfqpfq.html

[S27] C：定义常量
来源：http://dali.snrcjt.cn/Article/details/gtzhozqivc.html

const double PI = 3.14159;
来源：http://dali.cucudq.cn/Article/details/gtvsjcqnxq.html

[S28] C：静态变量
来源：http://dali.daria6918.cn/Article/details/gtxqbjkrbn.html

static int counter = 0;
来源：http://dali.dashuyun.cn/Article/details/gtetjkugke.html

[S29] C：变参函数
来源：http://dali.sufxvd.cn/Article/details/gtmzsgfbcg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhoulong.xyz/Article/details/gtypfdomyj.html

[S30] C：头文件保护
来源：http://dali.andypj.xyz/Article/details/gtqxlzahmn.html

#ifndef X_H
来源：http://dali.jlsjyb.cn/Article/details/gtsyndebkk.html

#define X_H
来源：http://dali.quarkkingdee.top/Article/details/gtadatnxbi.html

#endif
来源：http://dali.birdmap.top/Article/details/gtpeyfxnue.html

[S31] C++：Hello World
来源：http://dali.nanxinkj.top/Article/details/gtcyafnrad.html

#include <iostream>
来源：http://dali.xylfe.cn/Article/details/gtncrnbpak.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yongpay.top/Article/details/gtoekvztzm.html

[S32] C++：字符串
来源：http://dali.yueranfly.top/Article/details/gtouqrysmc.html

std::string s = "hi";  s += "!";
来源：http://dali.tian-w.cn/Article/details/gtxrtwwqab.html

[S33] C++：vector 增删
来源：http://dali.0kj1m.cn/Article/details/gtfsspctqf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.meibo888.top/Article/details/gtctqlxvxs.html

[S34] C++：遍历 vector
来源：http://dali.xylfe.cn/Article/details/gtiylsttvx.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.daxiang520.top/Article/details/gtxgokoxxl.html

[S35] C++：map
来源：http://dali.yanxiufei.cn/Article/details/gtbljalwvy.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.bjfxy.top/Article/details/gtrenrznvu.html

[S36] C++：unordered_map
来源：http://dali.ehwqpu.com/Article/details/gtbzpowzrq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yuanzhike.top/Article/details/gtuktcysxs.html

[S37] C++：set
来源：http://dali.vqdsnc.cn/Article/details/gtfzwlojou.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjvnwhnni.html

[S38] C++：排序
来源：http://dali.fzhhl.top/Article/details/gtvukabvcx.html

std::sort(v.begin(), v.end());
来源：http://dali.dashuyun.cn/Article/details/gtcpqqhoya.html

[S39] C++：自定义比较器排序
来源：http://dali.316326.xyz/Article/details/gtmvjxoxqj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenjidiqi.icu/Article/details/gtahnofsgp.html

[S40] C++：查找元素
来源：http://dali.dianchejie.cn/Article/details/gtniqooaje.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.meibo888.top/Article/details/gtpeifnsgv.html

[S41] C++：类与构造函数
来源：http://dali.smart0.xyz/Article/details/gtfzzrgpdm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jianghu66.top/Article/details/gtnitwvcsn.html

[S42] C++：继承与虚函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtunmpdcmq.html

class B : public Base { public: void f() override {} };
来源：http://dali.wangdashe.top/Article/details/gthsmhaklk.html

[S43] C++：智能指针
来源：http://dali.cdnleiting.top/Article/details/gtaaitaowg.html

auto p = std::make_unique<int>(5);
来源：http://dali.hnqzz.top/Article/details/gtedaexiog.html

[S44] C++：引用传参
来源：http://dali.nanxinkj.top/Article/details/gthdfwxgyo.html

void inc(int &x) { ++x; }
来源：http://dali.chenlongwang.top/Article/details/gtzmojagmh.html

[S45] C++：lambda
来源：http://dali.tianlin.xyz/Article/details/gtcempobnb.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.fzhhl.top/Article/details/gtfbjouhwq.html

[S46] C++：函数模板
来源：http://dali.andypj.xyz/Article/details/gtpqdlllke.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.smart0.xyz/Article/details/gtsjyleuei.html

[S47] C++：结构化绑定遍历
来源：http://dali.bjfxy.top/Article/details/gteuczoiao.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yueranfly.top/Article/details/gtabfrzbjb.html

[S48] C++：逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gtidwtgouz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.dashuyun.cn/Article/details/gtyegqjvxc.html

while (std::getline(in, line)) { }
来源：http://dali.sxryk.cn/Article/details/gtttzlaopr.html

[S49] C++：写文件
来源：http://dali.cucudq.cn/Article/details/gtbqomjuzw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.nwbrower.top/Article/details/gtkpiilqju.html

[S50] C++：格式化数字
来源：http://dali.hfpthk.cn/Article/details/gtsbdlvpzi.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.hammf.cn/Article/details/gtonqcmuft.html

[S51] C++：显式类型转换
来源：http://dali.xuanzx.com/Article/details/gtjyuojwjj.html

static_cast<double>(a) / b
来源：http://dali.zdqjudy.top/Article/details/gtslwrtlvf.html

[S52] C++：const 与 noexcept
来源：http://dali.hnqzz.top/Article/details/gtbxxswsts.html

int size() const noexcept { return n_; }
来源：http://dali.yueranfly.top/Article/details/gteojzlhtc.html

[S53] C++：移动语义
来源：http://dali.vqdsnc.cn/Article/details/gtsmuqkfze.html

std::vector<int> w = std::move(v);
来源：http://dali.yongpay.top/Article/details/gtcztczpvg.html

[S54] C++：异常处理
来源：http://dali.gzhubu.top/Article/details/gtmdnbjzun.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.yuxming.cn/Article/details/gtyresypih.html

[S55] C++：结构化绑定
来源：http://dali.sufxvd.cn/Article/details/gtxirgubel.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.iojbl.cn/Article/details/gtwdgmlowu.html

[S56] C++：optional
来源：http://dali.daxiang520.top/Article/details/gtbiyzsxul.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.fengsongda.top/Article/details/gtpihsgctr.html

[S57] C++：编译期常量
来源：http://dali.guowangkeji.top/Article/details/gtiibtjjfs.html

constexpr int N = 10;
来源：http://dali.yonumen.top/Article/details/gtilnypknx.html

[S58] C++：命名空间
来源：http://dali.yj20258888.top/Article/details/gtfcikucee.html

namespace ns { int f() { return 1; } }
来源：http://dali.yongpay.top/Article/details/gtcfexmbmu.html

[S59] C++：静态断言
来源：http://dali.zhixingplan.top/Article/details/gtpylytapa.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhaomingkeji.xyz/Article/details/gteqeuqwsf.html

[S60] C++：遍历并删除元素
来源：http://dali.sxryk.cn/Article/details/gtpuwsjpnx.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.feifeiyinyue.top/Article/details/gtmahjsuti.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtlfmotvnf.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.jinqigufen.top/Article/details/gtqdgjbvwv.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gtibkyicrj.html

[T01] Kotlin：Hello World
来源：http://dali.nanxinkj.top/Article/details/gtqcqpoltg.html

println("Hello")
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkyheqyck.html

[T02] Kotlin：变量
来源：http://dali.ppjwa.cn/Article/details/gtqwthppas.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.aibaodan.cn/Article/details/gtdesqnuhs.html

[T03] Kotlin：字符串模板
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlpyxlgot.html

"值: $b"
来源：http://dali.yanxiufei.cn/Article/details/gtshpuoowq.html

[T04] Kotlin：空安全
来源：http://dali.svipenyu.cn/Article/details/gtryhpnkik.html

val n: String? = null;  n?.length
来源：http://dali.haohaochexian.top/Article/details/gtmvzjrxyy.html

[T05] Kotlin：when 表达式
来源：http://dali.ppjwa.cn/Article/details/gtgmthypkb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jiagoushi.top/Article/details/gtbkehpwxl.html

[T06] Kotlin：集合映射
来源：http://dali.cucudq.cn/Article/details/gtvvclbjty.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hysaishi.cn/Article/details/gtgwrzgaad.html

[T07] Kotlin：集合过滤
来源：http://dali.smart0.xyz/Article/details/gtojlzhrhl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.guowangkeji.top/Article/details/gtvwqgymez.html

[T08] Kotlin：数据类
来源：http://dali.dashuyun.cn/Article/details/gtuckvpdpc.html

data class User(val name: String, val age: Int)
来源：http://dali.aizwys.cn/Article/details/gtrfyuggjq.html

[T09] Kotlin：扩展函数
来源：http://dali.tian-w.cn/Article/details/gtcjycgqkg.html

fun String.exclaim() = this + "!"
来源：http://dali.jinqigfzy.top/Article/details/gtkckeuitv.html

[T10] Kotlin：默认参数
来源：http://dali.chenjidiqi.icu/Article/details/gtnfriqvhc.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shangyingyoupin.top/Article/details/gtwwkusbdi.html

[T11] Kotlin：协程
来源：http://dali.birdmap.top/Article/details/gtffcrodsb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.redwolf501.top/Article/details/gtktayknjs.html

[T12] Kotlin：解构声明
来源：http://dali.chenjidiqi.icu/Article/details/gthedsndyi.html

val (a, b) = Pair(1, 2)
来源：http://dali.xuanzx.com/Article/details/gtpzonffss.html

[T13] Kotlin：只读 Map
来源：http://dali.jinqigfzy.top/Article/details/gtlckbvjbq.html

val m = mapOf("a" to 1)
来源：http://dali.xylfe.cn/Article/details/gtzylhvriw.html

[T14] Kotlin：循环
来源：http://dali.aizwys.cn/Article/details/gtzlnuvzrf.html

for (i in 1..10) println(i)
来源：http://dali.chenzaomai.com/Article/details/gtoqvuekej.html

[T15] Kotlin：接口
来源：http://dali.shanyushiyangtech.top/Article/details/gtfefyxndi.html

interface Shape { fun area(): Double }
来源：http://dali.jqgfzy.top/Article/details/gtyujrowyi.html

[T16] Swift：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtfsfbboyx.html

print("Hello")
来源：http://dali.birdmap.top/Article/details/gtfiwomext.html

[T17] Swift：变量与常量
来源：http://dali.snrcjt.cn/Article/details/gtalljszth.html

var a = 1;  let b = 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtatbycrcc.html

[T18] Swift：字符串插值
来源：http://dali.ybcxt.top/Article/details/gtbgcirfdy.html

"值: \(b)"
来源：http://dali.shangyingyoupin.top/Article/details/gtagrzwlur.html

[T19] Swift：可选绑定
来源：http://dali.xuetiantiany.cn/Article/details/gtblmgdnlb.html

if let n = opt { print(n) }
来源：http://dali.havefunace.top/Article/details/gtlrokewgg.html

[T20] Swift：数组操作
来源：http://dali.jqgfzy.top/Article/details/gtfsvxvgtd.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hfpthk.cn/Article/details/gtldlyivfg.html

[T21] Swift：遍历
来源：http://dali.yuxming.cn/Article/details/gtwlbvzbfn.html

for x in a { print(x) }
来源：http://dali.xinyue.icu/Article/details/gtqexzcfmp.html

[T22] Swift：字典
来源：http://dali.shangyingyoupin.top/Article/details/gticusuwnh.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.vqdsnc.cn/Article/details/gtoomhobkk.html

[T23] Swift：函数
来源：http://dali.gotoacloud.top/Article/details/gtrfmbjooh.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.birdmap.top/Article/details/gtrgqgaygw.html

[T24] Swift：闭包
来源：http://dali.jinqigfzy.top/Article/details/gthramnjzi.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.guannengcc.top/Article/details/gtahfoibww.html

[T25] Swift：结构体
来源：http://dali.xinyue.icu/Article/details/gtjixerpzf.html

struct P { var x: Int }
来源：http://dali.hfpthk.cn/Article/details/gtrzvpxcpc.html

[T26] Swift：类与重写
来源：http://dali.sxryk.cn/Article/details/gtdcmwdkid.html

class A: Base { override func f() {} }
来源：http://dali.jinqigfzy.top/Article/details/gtlmovounw.html

[T27] Swift：错误处理
来源：http://dali.cqqwz.cn/Article/details/gtspfpectx.html

do { try f() } catch { print(error) }
来源：http://dali.gaohongyu789.top/Article/details/gtqaeeycrp.html

[T28] Swift：枚举
来源：http://dali.gogol.net.cn/Article/details/gtxjgivmqi.html

enum Color { case red, green }
来源：http://dali.zhongyouzk.top/Article/details/gtwjxsyudk.html

[T29] Swift：guard 提前返回
来源：http://dali.zhixingplan.top/Article/details/gthrdjospp.html

guard let x = opt else { return }
来源：http://dali.sweek.top/Article/details/gthvxwixel.html

[T30] Swift：协议
来源：http://dali.cqqwz.cn/Article/details/gtaseceyuz.html

protocol Shape { func area() -> Double }
来源：http://dali.316326.xyz/Article/details/gtfzjajjks.html

[T31] Lua：Hello World
来源：http://dali.zhoulong.xyz/Article/details/gtzpvwjgrp.html

print("Hello")
来源：http://dali.jianghu66.top/Article/details/gtcnavzlxy.html

[T32] Lua：局部变量
来源：http://dali.vqdsnc.cn/Article/details/gtbpvwqdfy.html

local a = 1
来源：http://dali.hongshengwenyu.top/Article/details/gtbljtseul.html

[T33] Lua：表（数组）
来源：http://dali.sxryk.cn/Article/details/gtwhawhlbq.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhijiandao.cn/Article/details/gtzjthuguj.html

[T34] Lua：遍历表
来源：http://dali.jinghuilouyu.cn/Article/details/gtjonzapof.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jianghu66.top/Article/details/gtltcnbtic.html

[T35] Lua：字典表
来源：http://dali.zhoulong.xyz/Article/details/gtzgoioceh.html

local d = { a = 1 };  d.b = 2
来源：http://dali.nwbrower.top/Article/details/gttysviisf.html

[T36] Lua：函数
来源：http://dali.xuetiantiany.cn/Article/details/gtzkklmzun.html

function add(a, b) return a + b end
来源：http://dali.xuanzx.com/Article/details/gtfvknhjpv.html

[T37] Lua：字符串拼接
来源：http://dali.hfpthk.cn/Article/details/gtvhiphswj.html

"a" .. "b"
来源：http://dali.ivvv.top/Article/details/gtiwlieovm.html

[T38] Lua：条件
来源：http://dali.0kj1m.cn/Article/details/gtkwzurcvv.html

if x > 0 then print("正") end
来源：http://dali.jinqigufen.top/Article/details/gtzhswaluu.html

[T39] Lua：模式匹配
来源：http://dali.c1oappe.top/Article/details/gtkcsbmmno.html

string.find(s, "%d+")
来源：http://dali.pengpengdd.cyou/Article/details/gtectejitf.html

[T40] Lua：元表
来源：http://dali.meibo888.top/Article/details/gtgzqjssti.html

setmetatable({}, { __index = base })
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuwwooizk.html


<!-- 参考信息 -->