代发 wailian999

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jianghu66.top/Article/details/gtwnfrtpcl.html

[R36] 并发执行多个任务
来源：http://dali.pengpengdd.cyou/Article/details/gtasspkcxu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ivvv.top/Article/details/gtijxdmrry.html

[R37] 把输出赋给变量
来源：http://dali.chenlongwang.top/Article/details/gtambsqyaz.html

files=$(ls -1)
来源：http://dali.daxiang520.top/Article/details/gtamgutarg.html

[R38] 管道串联
来源：http://dali.sufxvd.cn/Article/details/gtjkknmmtv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.feifeiyinyue.top/Article/details/gtuufbhhlj.html

[R39] 重定向标准输出与错误
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjsojnuqh.html

cmd > out.log 2>&1
来源：http://dali.zhengqikj.top/Article/details/gtbagynvyk.html

[R40] 追加写日志
来源：http://dali.cdnleiting.top/Article/details/gtycpeosae.html

echo "log" >> out.log
来源：http://dali.yj20258888.top/Article/details/gtcxggwbjq.html

[R41] 丢弃输出
来源：http://dali.cucudq.cn/Article/details/gtbmdokwuq.html

cmd >/dev/null 2>&1
来源：http://dali.pycfn.com/Article/details/gtazyjfwze.html

[R42] 输入重定向
来源：http://dali.iojbl.cn/Article/details/gtovxogmfa.html

wc -l < a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbpfehxcv.html

[R43] 按名字查找文件
来源：http://dali.pengpengdd.cyou/Article/details/gtgkhmvehv.html

find . -name "*.log" -type f
来源：http://dali.hnqzz.top/Article/details/gtqryclfgz.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gtphqqaszt.html

find . -mtime -7 -type f
来源：http://dali.c1oappe.top/Article/details/gtwncbttqc.html

[R45] 批量删除
来源：http://dali.zhaomingkeji.xyz/Article/details/gttvadpnpc.html

find . -name "*.tmp" -delete
来源：http://dali.yongpay.top/Article/details/gtujktkuus.html

[R46] 递归替换文件内容
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuvvxtzdw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shangyingyoupin.top/Article/details/gtkbvwljgc.html

[R47] sed 单行替换
来源：http://dali.yj202588.top/Article/details/gtkftmjdmh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.vqdsnc.cn/Article/details/gtunjdznbh.html

[R48] awk 取指定列
来源：http://dali.nanxinkj.top/Article/details/gtrfqxlors.html

awk '{print $1, $3}' a.txt
来源：http://dali.zycfv.cn/Article/details/gtofqnkqnj.html

[R49] awk 带条件
来源：http://dali.zhiwuduotai.top/Article/details/gtazaggbes.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.dashuyun.cn/Article/details/gtwpylufim.html

[R50] awk 求和
来源：http://dali.birdmap.top/Article/details/gtfgqhamni.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gzhubu.top/Article/details/gtqbwcvbag.html

[R51] 排序去重取前几
来源：http://dali.gaohongyu789.top/Article/details/gtraqxtwew.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zdqjudy.top/Article/details/gtypieoser.html

[R52] 统计行数
来源：http://dali.yangfankeji.com/Article/details/gtjfucglzz.html

wc -l a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtymcjmzac.html

[R53] 查看文件头与实时尾
来源：http://dali.xuanzx.com/Article/details/gtzvqqbmfo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.9152youxi.cn/Article/details/gtddyvzaqe.html

[R54] 比较两个文件
来源：http://dali.pengpengdd.cyou/Article/details/gttnotieuy.html

diff a.txt b.txt
来源：http://dali.dianchejie.cn/Article/details/gtuytixbnk.html

[R55] 压缩与解压
来源：http://dali.jqgfzy.top/Article/details/gtzziaybgk.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhixingplan.top/Article/details/gtnboomhyz.html

[R56] 远程拷贝
来源：http://dali.zhixingplan.top/Article/details/gtxihwyzaa.html

scp file user@host:/path/
来源：http://dali.wangshuangyany.cn/Article/details/gtfhtfikax.html

[R57] 远程执行命令
来源：http://dali.yuxming.cn/Article/details/gtvuijuwmd.html

ssh user@host 'uptime'
来源：http://dali.hysaishi.cn/Article/details/gthatpnlka.html

[R58] 下载文件
来源：http://dali.jiagoushi.top/Article/details/gtxtaxwoyb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jiagoushi.top/Article/details/gtmytevtde.html

[R59] 发 POST JSON
来源：http://dali.jinghuilouyu.cn/Article/details/gthiibcdvg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.haohaochexian.top/Article/details/gtcgmhkdtc.html

[R60] 只看 HTTP 状态码
来源：http://dali.hammf.cn/Article/details/gtaebzzjna.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shanyushiyangtech.top/Article/details/gtuocgpfkj.html

[R61] 磁盘占用
来源：http://dali.cdnleiting.top/Article/details/gtifrbxhpl.html

df -h;  du -sh *
来源：http://dali.316326.xyz/Article/details/gtellyqkpf.html

[R62] 找最占空间的文件
来源：http://dali.yvedp.cn/Article/details/gtcgutenho.html

du -ah . | sort -rh | head -10
来源：http://dali.0kj1m.cn/Article/details/gtkvplwfoa.html

[R63] 内存与进程
来源：http://dali.feifeiyinyue.top/Article/details/gtunsqrncl.html

free -h;  ps aux | grep nginx
来源：http://dali.jqgfzy.top/Article/details/gtuavxvobr.html

[R64] 结束进程
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzniywigf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.tanke756.top/Article/details/gtnyifgwjr.html

[R65] 查看端口占用
来源：http://dali.svipenyu.cn/Article/details/gtkwqvivql.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hywenlv.cn/Article/details/gtbshipfgl.html

[R66] 定时任务
来源：http://dali.hongshengwenyu.top/Article/details/gtnjiwwway.html

crontab -e;  crontab -l
来源：http://dali.jlsjyb.cn/Article/details/gtkmkdlzqo.html

[R67] 生成随机十六进制串
来源：http://dali.gzhubu.top/Article/details/gtgaeiwjqk.html

openssl rand -hex 16
来源：http://dali.cheryme.top/Article/details/gtjzrlqjuc.html

[R68] 计算文件校验值
来源：http://dali.svipenyu.cn/Article/details/gtlilssohb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gttcfckbwc.html

[R69] 生成随机密码
来源：http://dali.cucudq.cn/Article/details/gtgyaixtvo.html

head -c 16 /dev/urandom | base64
来源：http://dali.cdnleiting.top/Article/details/gtrnqjrufv.html

[R70] 时间戳与互转
来源：http://dali.jqgufenzy.top/Article/details/gthvppdtkm.html

date +%s;  date -d @1700000000
来源：http://dali.haohaochexian.top/Article/details/gtohdhjgdt.html

[R71] 日期格式化
来源：http://dali.sysykeji.top/Article/details/gtrtuirper.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ppjwa.cn/Article/details/gtqaaadrfz.html

[R72] 等待端口就绪
来源：http://dali.daria6918.cn/Article/details/gttkuukhxk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.nanxuanxn.top/Article/details/gtumniflzw.html

[R73] 分割大日志
来源：http://dali.nanxinkj.top/Article/details/gtrwnfxsmc.html

split -l 1000 big.log part_
来源：http://dali.yvedp.cn/Article/details/gtenzbcrzt.html

[R74] 批量重命名
来源：http://dali.shanyushiyangtech.top/Article/details/gtzpoevzrs.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ppjwa.cn/Article/details/gtrayhnyzy.html

[R75] 导出环境变量
来源：http://dali.pycfn.com/Article/details/gtmcxbjtwu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.iojbl.cn/Article/details/gtrisfjdfu.html

[R76] 使用临时文件
来源：http://dali.9152youxi.cn/Article/details/gtuhwneizz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenjidiqi.icu/Article/details/gtgvooegbu.html

[R77] 读取用户输入
来源：http://dali.nanxuanxn.top/Article/details/gtseglfuni.html

read -rp "请输入: " ans
来源：http://dali.yuxming.cn/Article/details/gtuiommoup.html

[R78] 交互式菜单
来源：http://dali.yj20258888.top/Article/details/gtxrnojslk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxsxguyla.html

[R79] 解析命令行选项
来源：http://dali.daria6918.cn/Article/details/gttzmqeqqz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.sufxvd.cn/Article/details/gtnohtbauy.html

[R80] 查看脚本执行耗时
来源：http://dali.zdqjudy.top/Article/details/gtumazlnjj.html

time ./run.sh
来源：http://dali.guannengcc.top/Article/details/gtkkuwihwk.html

================================================================================
来源：http://dali.hnqzz.top/Article/details/gtdeovqmpt.html

S. C / C++ 专题
来源：http://dali.yongpay.top/Article/details/gtqtnrwzcx.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtsszwhlej.html

[S01] C：Hello World
来源：http://dali.ppjwa.cn/Article/details/gteviwlmve.html

#include <stdio.h>
来源：http://dali.316326.xyz/Article/details/gtiqjgcdxf.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.0kj1m.cn/Article/details/gtzjebouco.html

[S02] C：变量与格式化输出
来源：http://dali.haohaochexian.top/Article/details/gtjvepdqec.html

int a = 10; printf("%d\n", a);
来源：http://dali.bjfxy.top/Article/details/gtmnvhemin.html

[S03] C：读入整数
来源：http://dali.nwbrower.top/Article/details/gttoqsamdf.html

int x; scanf("%d", &x);
来源：http://dali.yvedp.cn/Article/details/gtvsevquni.html

[S04] C：字符串复制
来源：http://dali.shzxlz.cn/Article/details/gtwjkuqwey.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.aizwys.cn/Article/details/gtvuwmptjf.html

[S05] C：字符串长度
来源：http://dali.haohaochexian.top/Article/details/gtczvyqlhy.html

strlen(s)
来源：http://dali.jqgufenzy.top/Article/details/gtlbywjyfx.html

[S06] C：字符串比较
来源：http://dali.hammf.cn/Article/details/gtksqqjpla.html

strcmp(a, b) == 0
来源：http://dali.fengsongda.top/Article/details/gtzsmtjctx.html

[S07] C：数组遍历求和
来源：http://dali.yuxming.cn/Article/details/gtvpisoxwl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zycfv.cn/Article/details/gtcidlyzze.html

[S08] C：动态内存分配与释放
来源：http://dali.kuanghao11.cn/Article/details/gtmpvwotic.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yuxming.cn/Article/details/gtxkihuhle.html

[S09] C：结构体定义与初始化
来源：http://dali.pycfn.com/Article/details/gtxlylabtv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hysaishi.cn/Article/details/gtamnccybk.html

[S10] C：指针与解引用
来源：http://dali.ehwqpu.com/Article/details/gtdoappmhp.html

int *p = &a;  *p = 5;
来源：http://dali.9152youxi.cn/Article/details/gtnfpqswzs.html

[S11] C：逐行读文件
来源：http://dali.hnqzz.top/Article/details/gtnesnwyhq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.wangdashe.top/Article/details/gtsauamxqe.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hnxiangtu.top/Article/details/gtdjuxmavl.html

fclose(f);
来源：http://dali.ydzc1.top/Article/details/gtcprvufdv.html

[S12] C：写文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvgwuuosf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.fengsongda.top/Article/details/gtnbrbgsre.html

[S13] C：宏定义
来源：http://dali.daria6918.cn/Article/details/gtgylpezyu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.gaohongyu789.top/Article/details/gtvkpbhvda.html

[S14] C：枚举
来源：http://dali.c1oappe.top/Article/details/gtmugewdue.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.ybcxt.top/Article/details/gtrowyzzop.html

[S15] C：类型转换
来源：http://dali.kuanghao11.cn/Article/details/gtieasnqjz.html

(double) a / b
来源：http://dali.ydzc1.top/Article/details/gthhbhhxgv.html

[S16] C：位操作置位
来源：http://dali.zhiwuduotai.top/Article/details/gtuauefpxi.html

x |= (1 << 3);
来源：http://dali.9152youxi.cn/Article/details/gtdkmxnfij.html

[S17] C：安全拼接字符串
来源：http://dali.gotoacloud.top/Article/details/gtklocqolf.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhiwuduotai.top/Article/details/gtomvscbix.html

[S18] C：命令行参数
来源：http://dali.hammf.cn/Article/details/gtjofagmfc.html

int main(int argc, char **argv)
来源：http://dali.chenzaomai.com/Article/details/gtxwlirfum.html

[S19] C：快速排序
来源：http://dali.nwbrower.top/Article/details/gtepmlrmsb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yj20258888.top/Article/details/gtmiqxcfyf.html

[S20] C：二分查找
来源：http://dali.zhongyouzk.top/Article/details/gtakjvvwab.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yueranfly.top/Article/details/gtmtqgjitw.html

[S21] C：字符类别判断
来源：http://dali.yonumen.top/Article/details/gtkqlyjxea.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdlweprju.html

[S22] C：字符串转数字
来源：http://dali.xuetiantiany.cn/Article/details/gtysmmyklm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.pycfn.com/Article/details/gtfblvbvyo.html

[S23] C：随机数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcnqxxywz.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sufxvd.cn/Article/details/gtpkdlvqyc.html

[S24] C：获取本地时间
来源：http://dali.yvedp.cn/Article/details/gtsdrmmebv.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ivvv.top/Article/details/gtvygsexgh.html

[S25] C：内存拷贝
来源：http://dali.yj20258.top/Article/details/gtqkdhsotf.html

memcpy(dst, src, n);
来源：http://dali.wangdashe.top/Article/details/gtbynxpusw.html

[S26] C：内存清零
来源：http://dali.gzhubu.top/Article/details/gtodyewuxe.html

memset(a, 0, sizeof a);
来源：http://dali.cheryme.top/Article/details/gtukpqcazn.html

[S27] C：定义常量
来源：http://dali.sufxvd.cn/Article/details/gtqcxjtpri.html

const double PI = 3.14159;
来源：http://dali.ybcxt.top/Article/details/gtcgobueqm.html

[S28] C：静态变量
来源：http://dali.xuanzx.com/Article/details/gteenobvun.html

static int counter = 0;
来源：http://dali.yj202588.top/Article/details/gtficotyxa.html

[S29] C：变参函数
来源：http://dali.yvedp.cn/Article/details/gtizzpmqoh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.bjfxy.top/Article/details/gtlyunydfo.html

[S30] C：头文件保护
来源：http://dali.guowangkeji.top/Article/details/gtovtaaxya.html

#ifndef X_H
来源：http://dali.jyoumei.cn/Article/details/gtpiahqglx.html

#define X_H
来源：http://dali.yongpay.top/Article/details/gtqjgiepxv.html

#endif
来源：http://dali.aibaodan.cn/Article/details/gtfypiwpkz.html

[S31] C++：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtpcdrsiud.html

#include <iostream>
来源：http://dali.9152youxi.cn/Article/details/gtgdviqcyk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.daxiang520.top/Article/details/gtenwgaseu.html

[S32] C++：字符串
来源：http://dali.zhongyouzk.top/Article/details/gtgqerfweb.html

std::string s = "hi";  s += "!";
来源：http://dali.gzhubu.top/Article/details/gtiusryluq.html

[S33] C++：vector 增删
来源：http://dali.chenjidiqi.icu/Article/details/gtmvccjcaf.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.yuxming.cn/Article/details/gtgpwcewwm.html

[S34] C++：遍历 vector
来源：http://dali.shangyingyoupin.top/Article/details/gtwcvpsedv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yangfankeji.com/Article/details/gtnjfporsz.html

[S35] C++：map
来源：http://dali.yanxiufei.cn/Article/details/gtdqbtpyuq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.iojbl.cn/Article/details/gtgjeevdea.html

[S36] C++：unordered_map
来源：http://dali.yueranfly.top/Article/details/gtpkbiiijw.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtvnavpnva.html

[S37] C++：set
来源：http://dali.jlsjyb.cn/Article/details/gtrmfvogcj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.chenzaomai.com/Article/details/gtniweotaz.html

[S38] C++：排序
来源：http://dali.zhoulong.xyz/Article/details/gtgocreffg.html

std::sort(v.begin(), v.end());
来源：http://dali.zycfv.cn/Article/details/gtthlxtukm.html

[S39] C++：自定义比较器排序
来源：http://dali.jinghuilouyu.cn/Article/details/gtbcmkzicn.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyhpcxexe.html

[S40] C++：查找元素
来源：http://dali.birdmap.top/Article/details/gtvsrnzdhk.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.gaohongyu789.top/Article/details/gtyqgwwski.html

[S41] C++：类与构造函数
来源：http://dali.pycfn.com/Article/details/gtgvauwdij.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jqgufenzy.top/Article/details/gtaoxhotvp.html

[S42] C++：继承与虚函数
来源：http://dali.tanke756.top/Article/details/gtasdihbuv.html

class B : public Base { public: void f() override {} };
来源：http://dali.yonumen.top/Article/details/gtlajxcubq.html

[S43] C++：智能指针
来源：http://dali.ehwqpu.com/Article/details/gtrripxass.html

auto p = std::make_unique<int>(5);
来源：http://dali.sweek.top/Article/details/gtdrcqszwc.html

[S44] C++：引用传参
来源：http://dali.tanke756.top/Article/details/gtykdclokn.html

void inc(int &x) { ++x; }
来源：http://dali.sufxvd.cn/Article/details/gtdhzhmmng.html

[S45] C++：lambda
来源：http://dali.zhoulong.xyz/Article/details/gtwpkvjmwe.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xuetiantiany.cn/Article/details/gtveatprse.html

[S46] C++：函数模板
来源：http://dali.shangyingyoupin.top/Article/details/gtynxiglur.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shangyingyoupin.top/Article/details/gtkwhcstid.html

[S47] C++：结构化绑定遍历
来源：http://dali.cqqwz.cn/Article/details/gtwcddatbe.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hysaishi.cn/Article/details/gtxcafiwhh.html

[S48] C++：逐行读文件
来源：http://dali.yvedp.cn/Article/details/gteqvtjcqi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.smart0.xyz/Article/details/gttkxdornc.html

while (std::getline(in, line)) { }
来源：http://dali.cheryme.top/Article/details/gttudhvtuo.html

[S49] C++：写文件
来源：http://dali.mhx1999.top/Article/details/gteufesmno.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.tianlin.xyz/Article/details/gttmnepzuw.html

[S50] C++：格式化数字
来源：http://dali.ivvv.top/Article/details/gtrtxojayr.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zhiwuduotai.top/Article/details/gtaceaippf.html

[S51] C++：显式类型转换
来源：http://dali.gaohongyu789.top/Article/details/gtxlxltoin.html

static_cast<double>(a) / b
来源：http://dali.vqdsnc.cn/Article/details/gtntoxducg.html

[S52] C++：const 与 noexcept
来源：http://dali.svipenyu.cn/Article/details/gtedstlkkj.html

int size() const noexcept { return n_; }
来源：http://dali.daria6918.cn/Article/details/gtilwpczji.html

[S53] C++：移动语义
来源：http://dali.quarkkingdee.top/Article/details/gtnkhldbko.html

std::vector<int> w = std::move(v);
来源：http://dali.cqqwz.cn/Article/details/gtvdnmhgwg.html

[S54] C++：异常处理
来源：http://dali.redwolf501.top/Article/details/gtaegiwrdl.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqeduzslm.html

[S55] C++：结构化绑定
来源：http://dali.wangshuangyany.cn/Article/details/gtgaoaodqo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.xziqi.cn/Article/details/gtqidcucxr.html

[S56] C++：optional
来源：http://dali.hnxiangtu.top/Article/details/gtenieroos.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.nanxuanxn.top/Article/details/gtsplhofos.html

[S57] C++：编译期常量
来源：http://dali.andypj.xyz/Article/details/gtqyfczmpd.html

constexpr int N = 10;
来源：http://dali.yuanzhike.top/Article/details/gtxnqucrvj.html

[S58] C++：命名空间
来源：http://dali.hnxiangtu.top/Article/details/gtrwqstfny.html

namespace ns { int f() { return 1; } }
来源：http://dali.meibo888.top/Article/details/gtdgrwlmju.html

[S59] C++：静态断言
来源：http://dali.yangfankeji.com/Article/details/gtksyybcqm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jinqigfzy.top/Article/details/gtntoiaxfl.html

[S60] C++：遍历并删除元素
来源：http://dali.yj20258.top/Article/details/gtbnkcdusi.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbfakamut.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gtythravca.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.hongshengwenyu.top/Article/details/gtfzbfgbat.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtcwafeapp.html

[T01] Kotlin：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtpwajssal.html

println("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gtlcunwynm.html

[T02] Kotlin：变量
来源：http://dali.sweek.top/Article/details/gtfqhrmirv.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.ppjwa.cn/Article/details/gtiaiggwee.html

[T03] Kotlin：字符串模板
来源：http://dali.sufxvd.cn/Article/details/gtaqxcrgfe.html

"值: $b"
来源：http://dali.sysykeji.top/Article/details/gtoepyoshb.html

[T04] Kotlin：空安全
来源：http://dali.zhoulong.xyz/Article/details/gtcuzvisrm.html

val n: String? = null;  n?.length
来源：http://dali.zhoulong.xyz/Article/details/gtgwydhnnj.html

[T05] Kotlin：when 表达式
来源：http://dali.ppjwa.cn/Article/details/gtgkrhyjzy.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jlsjyb.cn/Article/details/gthoqsecia.html

[T06] Kotlin：集合映射
来源：http://dali.cashguo.top/Article/details/gtgranhxms.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinghuilouyu.cn/Article/details/gtdketabmj.html

[T07] Kotlin：集合过滤
来源：http://dali.yj20258888.top/Article/details/gtftjddzft.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinqigfzy.top/Article/details/gtdwkpefuh.html

[T08] Kotlin：数据类
来源：http://dali.316326.xyz/Article/details/gtgpdainca.html

data class User(val name: String, val age: Int)
来源：http://dali.jqgfzy.top/Article/details/gtpikpyeiu.html

[T09] Kotlin：扩展函数
来源：http://dali.9152youxi.cn/Article/details/gtjsbwrorl.html

fun String.exclaim() = this + "!"
来源：http://dali.9152youxi.cn/Article/details/gtuciudnxf.html

[T10] Kotlin：默认参数
来源：http://dali.ppjwa.cn/Article/details/gteuqkneso.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.aibaodan.cn/Article/details/gtbrqvajty.html

[T11] Kotlin：协程
来源：http://dali.cqqwz.cn/Article/details/gtxbssyqlr.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shanyushiyangtech.top/Article/details/gtgvtqpvju.html

[T12] Kotlin：解构声明
来源：http://dali.birdmap.top/Article/details/gtyuxrxlmu.html

val (a, b) = Pair(1, 2)
来源：http://dali.nanxuanxn.top/Article/details/gtnmxxzxrh.html

[T13] Kotlin：只读 Map
来源：http://dali.wangdashe.top/Article/details/gtcqxuraqb.html

val m = mapOf("a" to 1)
来源：http://dali.nanxuanxn.top/Article/details/gtwqoazhnf.html

[T14] Kotlin：循环
来源：http://dali.mhx1999.top/Article/details/gtjxdatvys.html

for (i in 1..10) println(i)
来源：http://dali.ppjwa.cn/Article/details/gtnzzynvnf.html

[T15] Kotlin：接口
来源：http://dali.aibaodan.cn/Article/details/gtfcdtvcvw.html

interface Shape { fun area(): Double }
来源：http://dali.jqgfzy.top/Article/details/gtzxkgjvnl.html

[T16] Swift：Hello World
来源：http://dali.ppjwa.cn/Article/details/gtgjdbuanv.html

print("Hello")
来源：http://dali.birdmap.top/Article/details/gtzryncjrn.html

[T17] Swift：变量与常量
来源：http://dali.pycfn.com/Article/details/gtjicscmtj.html

var a = 1;  let b = 2
来源：http://dali.fengsongda.top/Article/details/gtjfayylio.html

[T18] Swift：字符串插值
来源：http://dali.yvedp.cn/Article/details/gtjxfbraig.html

"值: \(b)"
来源：http://dali.yj20258.top/Article/details/gttfpehimx.html

[T19] Swift：可选绑定
来源：http://dali.wangshuangyany.cn/Article/details/gtetdoimmh.html

if let n = opt { print(n) }
来源：http://dali.jqgfzy.top/Article/details/gtmfsrzbkd.html

[T20] Swift：数组操作
来源：http://dali.gzhubu.top/Article/details/gtlywhelwm.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cheryme.top/Article/details/gtrdsehcqd.html

[T21] Swift：遍历
来源：http://dali.yuanzhike.top/Article/details/gtxqkgyxuf.html

for x in a { print(x) }
来源：http://dali.redwolf501.top/Article/details/gtbztotqcq.html

[T22] Swift：字典
来源：http://dali.yj20258.top/Article/details/gtqsviuwsl.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.sysykeji.top/Article/details/gtfjjwuzeq.html

[T23] Swift：函数
来源：http://dali.sufxvd.cn/Article/details/gtdjlqoylg.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.nwbrower.top/Article/details/gtqrzpuica.html

[T24] Swift：闭包
来源：http://dali.snrcjt.cn/Article/details/gtpbpwitkj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.yanxiufei.cn/Article/details/gtxyatzbna.html

[T25] Swift：结构体
来源：http://dali.cashguo.top/Article/details/gtuktwzitq.html

struct P { var x: Int }
来源：http://dali.daxiang520.top/Article/details/gtrpjtrnyc.html

[T26] Swift：类与重写
来源：http://dali.iojbl.cn/Article/details/gtdzyxzcjz.html

class A: Base { override func f() {} }
来源：http://dali.shzxlz.cn/Article/details/gtlbafrwug.html

[T27] Swift：错误处理
来源：http://dali.xinyue.icu/Article/details/gthgrtugaw.html

do { try f() } catch { print(error) }
来源：http://dali.zhoulong.xyz/Article/details/gtakjypwam.html

[T28] Swift：枚举
来源：http://dali.shuidangran.top/Article/details/gtxjlgbhwj.html

enum Color { case red, green }
来源：http://dali.yueranfly.top/Article/details/gtjrfdpzvj.html

[T29] Swift：guard 提前返回
来源：http://dali.jinyuanbaomall.cn/Article/details/gtixzsqszh.html

guard let x = opt else { return }
来源：http://dali.birdmap.top/Article/details/gtkowczcty.html

[T30] Swift：协议
来源：http://dali.yanxiufei.cn/Article/details/gtvufrjzwy.html

protocol Shape { func area() -> Double }
来源：http://dali.guowangkeji.top/Article/details/gtapgeleir.html

[T31] Lua：Hello World
来源：http://dali.ydzc1.top/Article/details/gtimzbwowb.html

print("Hello")
来源：http://dali.ybcxt.top/Article/details/gtyzerjmqg.html

[T32] Lua：局部变量
来源：http://dali.hnqzz.top/Article/details/gtzkcexxpu.html

local a = 1
来源：http://dali.smart0.xyz/Article/details/gtmkhpixgg.html

[T33] Lua：表（数组）
来源：http://dali.guannengcc.top/Article/details/gtwxereymm.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhongyouzk.top/Article/details/gtgiudsxcc.html

[T34] Lua：遍历表
来源：http://dali.svipenyu.cn/Article/details/gtvwoedagj.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.hysaishi.cn/Article/details/gtudvsiium.html

[T35] Lua：字典表
来源：http://dali.redwolf501.top/Article/details/gtkvzxnolr.html

local d = { a = 1 };  d.b = 2
来源：http://dali.gogol.net.cn/Article/details/gtgfxzdyiy.html

[T36] Lua：函数
来源：http://dali.yj20258.top/Article/details/gtnxtwvxic.html

function add(a, b) return a + b end
来源：http://dali.yongpay.top/Article/details/gtzikyvbsz.html

[T37] Lua：字符串拼接
来源：http://dali.xuetiantiany.cn/Article/details/gtzatgsnix.html

"a" .. "b"
来源：http://dali.svipenyu.cn/Article/details/gtwbhxfeaw.html

[T38] Lua：条件
来源：http://dali.9152youxi.cn/Article/details/gtfgjwwawf.html

if x > 0 then print("正") end
来源：http://dali.wangdashe.top/Article/details/gtrqtsgsvq.html


<!-- 参考信息 -->