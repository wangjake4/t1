代发 wailian999

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ppjwa.cn/Article/details/gtlpduzyis.html

[R36] 并发执行多个任务
来源：http://dali.jiagoushi.top/Article/details/gtakyahayq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hnxiangtu.top/Article/details/gtkrtbeciu.html

[R37] 把输出赋给变量
来源：http://dali.haohaochexian.top/Article/details/gtqukfvigo.html

files=$(ls -1)
来源：http://dali.zhengqikj.top/Article/details/gtsradcraf.html

[R38] 管道串联
来源：http://dali.zhixingplan.top/Article/details/gtcwjuxuic.html

cat a.txt | grep -i error | wc -l
来源：http://dali.c1oappe.top/Article/details/gtxgwjqmoa.html

[R39] 重定向标准输出与错误
来源：http://dali.zycfv.cn/Article/details/gtauxepbfu.html

cmd > out.log 2>&1
来源：http://dali.nwbrower.top/Article/details/gtdkgmokpx.html

[R40] 追加写日志
来源：http://dali.chenlongwang.top/Article/details/gtowyunyph.html

echo "log" >> out.log
来源：http://dali.jinqigufen.top/Article/details/gtmxwypjtm.html

[R41] 丢弃输出
来源：http://dali.xuanzx.com/Article/details/gtwuxaqyen.html

cmd >/dev/null 2>&1
来源：http://dali.havefunace.top/Article/details/gthjtxvmzg.html

[R42] 输入重定向
来源：http://dali.yuxming.cn/Article/details/gtfzungogg.html

wc -l < a.txt
来源：http://dali.yongpay.top/Article/details/gtsjkokjsq.html

[R43] 按名字查找文件
来源：http://dali.redwolf501.top/Article/details/gtmkklipkx.html

find . -name "*.log" -type f
来源：http://dali.shangyingyoupin.top/Article/details/gtvoehkiai.html

[R44] 按修改时间查找
来源：http://dali.zdqjudy.top/Article/details/gtyqxdztyz.html

find . -mtime -7 -type f
来源：http://dali.fzhhl.top/Article/details/gtyaevphtj.html

[R45] 批量删除
来源：http://dali.tianlin.xyz/Article/details/gtjmbtspoe.html

find . -name "*.tmp" -delete
来源：http://dali.shangyingyoupin.top/Article/details/gtdrrqsyil.html

[R46] 递归替换文件内容
来源：http://dali.nanxuanxn.top/Article/details/gtzlymgchl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.tian-w.cn/Article/details/gtllbzwvgk.html

[R47] sed 单行替换
来源：http://dali.hammf.cn/Article/details/gtiqwmoisk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhixingplan.top/Article/details/gtfaqlycmw.html

[R48] awk 取指定列
来源：http://dali.sweek.top/Article/details/gtwqohazuk.html

awk '{print $1, $3}' a.txt
来源：http://dali.nanxinkj.top/Article/details/gtszegzkwn.html

[R49] awk 带条件
来源：http://dali.hnqzz.top/Article/details/gtgvnuhqiq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ivvv.top/Article/details/gtntpwltvl.html

[R50] awk 求和
来源：http://dali.dianchejie.cn/Article/details/gtkzpusybm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xziqi.cn/Article/details/gtxehueumw.html

[R51] 排序去重取前几
来源：http://dali.sysykeji.top/Article/details/gthzcvfidf.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinqigfzy.top/Article/details/gtwstfvwxb.html

[R52] 统计行数
来源：http://dali.gogol.net.cn/Article/details/gtrejhihdh.html

wc -l a.txt
来源：http://dali.daxiang520.top/Article/details/gtzcyuxkxa.html

[R53] 查看文件头与实时尾
来源：http://dali.9152youxi.cn/Article/details/gtjrhhftym.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.aizwys.cn/Article/details/gtcqmxthel.html

[R54] 比较两个文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzvtavkwm.html

diff a.txt b.txt
来源：http://dali.yj20258888.top/Article/details/gthbdocaoz.html

[R55] 压缩与解压
来源：http://dali.yonumen.top/Article/details/gtgqjiwfzg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.9152youxi.cn/Article/details/gtfjvmlttw.html

[R56] 远程拷贝
来源：http://dali.cdnleiting.top/Article/details/gtclozghvd.html

scp file user@host:/path/
来源：http://dali.tian-w.cn/Article/details/gtldmjojjx.html

[R57] 远程执行命令
来源：http://dali.yuanzhike.top/Article/details/gthatsvajr.html

ssh user@host 'uptime'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpxqgkfab.html

[R58] 下载文件
来源：http://dali.jianghu66.top/Article/details/gtcszeirsm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xinyue.icu/Article/details/gtpmxgssrn.html

[R59] 发 POST JSON
来源：http://dali.meibo888.top/Article/details/gtkagxqdiz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yueranfly.top/Article/details/gtpqzlxqff.html

[R60] 只看 HTTP 状态码
来源：http://dali.tianlin.xyz/Article/details/gthgpszqfd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jinqigfzy.top/Article/details/gtrixltfuz.html

[R61] 磁盘占用
来源：http://dali.kuanghao11.cn/Article/details/gtapsnyuwr.html

df -h;  du -sh *
来源：http://dali.yueranfly.top/Article/details/gtybnfpopz.html

[R62] 找最占空间的文件
来源：http://dali.jyoumei.cn/Article/details/gtzjdawlqm.html

du -ah . | sort -rh | head -10
来源：http://dali.sufxvd.cn/Article/details/gtwtbnpgbv.html

[R63] 内存与进程
来源：http://dali.hywenlv.cn/Article/details/gtgneymjpu.html

free -h;  ps aux | grep nginx
来源：http://dali.yj20258.top/Article/details/gthsvpmjek.html

[R64] 结束进程
来源：http://dali.yueranfly.top/Article/details/gtvlmfxkvz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.nwbrower.top/Article/details/gtqcovcehr.html

[R65] 查看端口占用
来源：http://dali.hongshengwenyu.top/Article/details/gtgkjmyqcd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ybcxt.top/Article/details/gttuqralpq.html

[R66] 定时任务
来源：http://dali.iojbl.cn/Article/details/gtmqlkbhlq.html

crontab -e;  crontab -l
来源：http://dali.gogol.net.cn/Article/details/gtyoroxnmv.html

[R67] 生成随机十六进制串
来源：http://dali.jinghuilouyu.cn/Article/details/gtuohhzqli.html

openssl rand -hex 16
来源：http://dali.hfpthk.cn/Article/details/gtljyniwhb.html

[R68] 计算文件校验值
来源：http://dali.jlsjyb.cn/Article/details/gtispfkohc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hammf.cn/Article/details/gtdimwwnta.html

[R69] 生成随机密码
来源：http://dali.jqgfzy.top/Article/details/gtqrxfhafy.html

head -c 16 /dev/urandom | base64
来源：http://dali.daria6918.cn/Article/details/gtuzwecjuj.html

[R70] 时间戳与互转
来源：http://dali.jinqigufen.top/Article/details/gtfvuufqit.html

date +%s;  date -d @1700000000
来源：http://dali.xziqi.cn/Article/details/gtfculgfup.html

[R71] 日期格式化
来源：http://dali.andypj.xyz/Article/details/gtoygcxnvl.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenzaomai.com/Article/details/gtpbpnvuer.html

[R72] 等待端口就绪
来源：http://dali.zhaomingkeji.xyz/Article/details/gtazctxezo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.chenlongwang.top/Article/details/gtktkilsyg.html

[R73] 分割大日志
来源：http://dali.jiagoushi.top/Article/details/gtwsxoazfy.html

split -l 1000 big.log part_
来源：http://dali.bjfxy.top/Article/details/gttogtvxcr.html

[R74] 批量重命名
来源：http://dali.ppjwa.cn/Article/details/gtvpbtfepg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xylfe.cn/Article/details/gtolfmlxnb.html

[R75] 导出环境变量
来源：http://dali.xuetiantiany.cn/Article/details/gtjvpyaiiv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yj202588.top/Article/details/gtaxrtwqba.html

[R76] 使用临时文件
来源：http://dali.haohaochexian.top/Article/details/gtkzcxodib.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.dianchejie.cn/Article/details/gtwipnuznw.html

[R77] 读取用户输入
来源：http://dali.9152youxi.cn/Article/details/gtdzuplswh.html

read -rp "请输入: " ans
来源：http://dali.shuidangran.top/Article/details/gtzhkjiraj.html

[R78] 交互式菜单
来源：http://dali.tanke756.top/Article/details/gtyeulqrpq.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shangyingyoupin.top/Article/details/gtxchazosq.html

[R79] 解析命令行选项
来源：http://dali.hfpthk.cn/Article/details/gtxurkbxbc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.316326.xyz/Article/details/gtxtbqrapq.html

[R80] 查看脚本执行耗时
来源：http://dali.nanxinkj.top/Article/details/gtsqhwuyfs.html

time ./run.sh
来源：http://dali.fengsongda.top/Article/details/gtlayoqnfa.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gthnfqfpaz.html

S. C / C++ 专题
来源：http://dali.aizwys.cn/Article/details/gtruuvibja.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtkjxopwde.html

[S01] C：Hello World
来源：http://dali.pycfn.com/Article/details/gtbayiepdf.html

#include <stdio.h>
来源：http://dali.cashguo.top/Article/details/gtebcuqptu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jlsjyb.cn/Article/details/gtkwnwmvzo.html

[S02] C：变量与格式化输出
来源：http://dali.svipenyu.cn/Article/details/gtknffnjxw.html

int a = 10; printf("%d\n", a);
来源：http://dali.cheryme.top/Article/details/gtizvvzzuw.html

[S03] C：读入整数
来源：http://dali.yj202588.top/Article/details/gtkjzsigct.html

int x; scanf("%d", &x);
来源：http://dali.guannengcc.top/Article/details/gtvnzwtabc.html

[S04] C：字符串复制
来源：http://dali.xuanzx.com/Article/details/gtskodxzpa.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zdqjudy.top/Article/details/gtlkxkzyxa.html

[S05] C：字符串长度
来源：http://dali.daxiang520.top/Article/details/gtvovfnqkg.html

strlen(s)
来源：http://dali.dashuyun.cn/Article/details/gtjibfdaqg.html

[S06] C：字符串比较
来源：http://dali.shzxlz.cn/Article/details/gtxfxuidnl.html

strcmp(a, b) == 0
来源：http://dali.wangshuangyany.cn/Article/details/gtyqjnxjrp.html

[S07] C：数组遍历求和
来源：http://dali.fzhhl.top/Article/details/gtamobdhwe.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jqgufenzy.top/Article/details/gtsedygiqz.html

[S08] C：动态内存分配与释放
来源：http://dali.yongpay.top/Article/details/gtqebdtqct.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhixingplan.top/Article/details/gterllholc.html

[S09] C：结构体定义与初始化
来源：http://dali.cqqwz.cn/Article/details/gtaywxtbhz.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.xylfe.cn/Article/details/gtmkwvxoeq.html

[S10] C：指针与解引用
来源：http://dali.ydzc1.top/Article/details/gtfrurqdgw.html

int *p = &a;  *p = 5;
来源：http://dali.zhiwuduotai.top/Article/details/gtpfdhqsxp.html

[S11] C：逐行读文件
来源：http://dali.tanke756.top/Article/details/gtztokudlp.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hnqzz.top/Article/details/gtuodgkyul.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.chenlongwang.top/Article/details/gtzfpvmhlh.html

fclose(f);
来源：http://dali.tanke756.top/Article/details/gtqlkervpy.html

[S12] C：写文件
来源：http://dali.vqdsnc.cn/Article/details/gtspyzfmzi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xinyue.icu/Article/details/gtzxcodgki.html

[S13] C：宏定义
来源：http://dali.shanyushiyangkeji.top/Article/details/gteniujppk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.andypj.xyz/Article/details/gtuwdbmjmq.html

[S14] C：枚举
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzhyhnuod.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.fengsongda.top/Article/details/gtkvxjiwbu.html

[S15] C：类型转换
来源：http://dali.nanxinkj.top/Article/details/gtqoxecyrq.html

(double) a / b
来源：http://dali.jinyuanbaomall.cn/Article/details/gtncboqinh.html

[S16] C：位操作置位
来源：http://dali.0kj1m.cn/Article/details/gtejyzlgce.html

x |= (1 << 3);
来源：http://dali.yj20258.top/Article/details/gtvjaokaxq.html

[S17] C：安全拼接字符串
来源：http://dali.yueranfly.top/Article/details/gtykebziky.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xuanzx.com/Article/details/gtebraefoj.html

[S18] C：命令行参数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmjmhjapi.html

int main(int argc, char **argv)
来源：http://dali.ehwqpu.com/Article/details/gtgmnznnqe.html

[S19] C：快速排序
来源：http://dali.316326.xyz/Article/details/gtaubftjbl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.aibaodan.cn/Article/details/gtkgudgbtq.html

[S20] C：二分查找
来源：http://dali.ehwqpu.com/Article/details/gtubcinlgi.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yvedp.cn/Article/details/gtbbddsmqn.html

[S21] C：字符类别判断
来源：http://dali.jiagoushi.top/Article/details/gtoinzrepf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shangyingyoupin.top/Article/details/gtwaddzapi.html

[S22] C：字符串转数字
来源：http://dali.shanyushiyangtech.top/Article/details/gtacbhgsfy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yongpay.top/Article/details/gtrgqxklmv.html

[S23] C：随机数
来源：http://dali.tian-w.cn/Article/details/gtmutwkbzq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.sweek.top/Article/details/gtzpkqtjml.html

[S24] C：获取本地时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkufplzou.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.birdmap.top/Article/details/gtlhoimnzo.html

[S25] C：内存拷贝
来源：http://dali.svipenyu.cn/Article/details/gtsnrahzcg.html

memcpy(dst, src, n);
来源：http://dali.sysykeji.top/Article/details/gtqpmtaoow.html

[S26] C：内存清零
来源：http://dali.yj20258.top/Article/details/gtlnxieivi.html

memset(a, 0, sizeof a);
来源：http://dali.jinghuilouyu.cn/Article/details/gthilshfxa.html

[S27] C：定义常量
来源：http://dali.yueranfly.top/Article/details/gtdpcdnfut.html

const double PI = 3.14159;
来源：http://dali.cdnleiting.top/Article/details/gtbmtwtvia.html

[S28] C：静态变量
来源：http://dali.nanxinkj.top/Article/details/gtawqpbnxe.html

static int counter = 0;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcceoibbm.html

[S29] C：变参函数
来源：http://dali.hnqzz.top/Article/details/gtqjpfxpwi.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhongyouzk.top/Article/details/gtmotzsrix.html

[S30] C：头文件保护
来源：http://dali.andypj.xyz/Article/details/gtwhrzywns.html

#ifndef X_H
来源：http://dali.xuetiantiany.cn/Article/details/gtdeqbhngi.html

#define X_H
来源：http://dali.tian-w.cn/Article/details/gtfkhkmcym.html

#endif
来源：http://dali.hnxiangtu.top/Article/details/gtokdaebil.html

[S31] C++：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtbnqlxqkf.html

#include <iostream>
来源：http://dali.jinqigfzy.top/Article/details/gtassvpyqc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yj20258888.top/Article/details/gtghjwiyac.html

[S32] C++：字符串
来源：http://dali.yj20258888.top/Article/details/gtdtcsuwle.html

std::string s = "hi";  s += "!";
来源：http://dali.sufxvd.cn/Article/details/gtqsqyyhyx.html

[S33] C++：vector 增删
来源：http://dali.hnxiangtu.top/Article/details/gtswfkvvic.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.xinyue.icu/Article/details/gtpavxpvmy.html

[S34] C++：遍历 vector
来源：http://dali.zhengqikj.top/Article/details/gtshfroquz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.aizwys.cn/Article/details/gtrmmsvldt.html

[S35] C++：map
来源：http://dali.jqgfzy.top/Article/details/gtyutvuxhk.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tanke756.top/Article/details/gtsmjudeir.html

[S36] C++：unordered_map
来源：http://dali.yanxiufei.cn/Article/details/gtkeuyhbwy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ivvv.top/Article/details/gtzsiohtca.html

[S37] C++：set
来源：http://dali.sxryk.cn/Article/details/gtankcfhlv.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.c1oappe.top/Article/details/gtkusrkrto.html

[S38] C++：排序
来源：http://dali.gotoacloud.top/Article/details/gtxepkordy.html

std::sort(v.begin(), v.end());
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpcjjaobv.html

[S39] C++：自定义比较器排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gterqrlovb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.tian-w.cn/Article/details/gtzcnrkgff.html

[S40] C++：查找元素
来源：http://dali.jiagoushi.top/Article/details/gtsduixbiz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zhongyouzk.top/Article/details/gtmbtppqpd.html

[S41] C++：类与构造函数
来源：http://dali.nanxinkj.top/Article/details/gtwbxmfaww.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jqgfzy.top/Article/details/gtdxkcpwqc.html

[S42] C++：继承与虚函数
来源：http://dali.jinghuilouyu.cn/Article/details/gtghygnish.html

class B : public Base { public: void f() override {} };
来源：http://dali.0kj1m.cn/Article/details/gtbvbzqmzf.html

[S43] C++：智能指针
来源：http://dali.shangyingyoupin.top/Article/details/gtfyjihklh.html

auto p = std::make_unique<int>(5);
来源：http://dali.yj20258888.top/Article/details/gtlxwgpjup.html

[S44] C++：引用传参
来源：http://dali.hammf.cn/Article/details/gtjyrelemu.html

void inc(int &x) { ++x; }
来源：http://dali.pycfn.com/Article/details/gtuzyoywwx.html

[S45] C++：lambda
来源：http://dali.sysykeji.top/Article/details/gtpmbwtggm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.aizwys.cn/Article/details/gtazryftae.html

[S46] C++：函数模板
来源：http://dali.vqdsnc.cn/Article/details/gtllxxlcdc.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hongshengwenyu.top/Article/details/gtrwiiazco.html

[S47] C++：结构化绑定遍历
来源：http://dali.hongshengwenyu.top/Article/details/gtcufvumgi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.cucudq.cn/Article/details/gtnkidkepz.html

[S48] C++：逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gtahxbbekl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhongyouzk.top/Article/details/gtmbyaojfe.html

while (std::getline(in, line)) { }
来源：http://dali.shangyingyoupin.top/Article/details/gtompgefaf.html

[S49] C++：写文件
来源：http://dali.yueranfly.top/Article/details/gtqfjcknec.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shzxlz.cn/Article/details/gtqntemkgw.html

[S50] C++：格式化数字
来源：http://dali.hfpthk.cn/Article/details/gtvuknlhih.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.dianchejie.cn/Article/details/gttgrubqsj.html

[S51] C++：显式类型转换
来源：http://dali.ydzc1.top/Article/details/gtdtwenmim.html

static_cast<double>(a) / b
来源：http://dali.zdqjudy.top/Article/details/gtpuwpvakf.html

[S52] C++：const 与 noexcept
来源：http://dali.yj202588.top/Article/details/gtckenagoo.html

int size() const noexcept { return n_; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjzcxddgs.html

[S53] C++：移动语义
来源：http://dali.zhijiandao.cn/Article/details/gtvomutmkc.html

std::vector<int> w = std::move(v);
来源：http://dali.zdqjudy.top/Article/details/gtrsnkbwrb.html

[S54] C++：异常处理
来源：http://dali.ybcxt.top/Article/details/gtqytkiftx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.snrcjt.cn/Article/details/gtpvhjymem.html

[S55] C++：结构化绑定
来源：http://dali.tianlin.xyz/Article/details/gtxhhbwtlm.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.gaohongyu789.top/Article/details/gtczqvqrfu.html

[S56] C++：optional
来源：http://dali.bjfxy.top/Article/details/gtvekhyrav.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.redwolf501.top/Article/details/gtggrwwplq.html

[S57] C++：编译期常量
来源：http://dali.gogol.net.cn/Article/details/gtpefufrqe.html

constexpr int N = 10;
来源：http://dali.yuxming.cn/Article/details/gthnjqezcq.html

[S58] C++：命名空间
来源：http://dali.daria6918.cn/Article/details/gttmpjwmmu.html

namespace ns { int f() { return 1; } }
来源：http://dali.aibaodan.cn/Article/details/gtarfefnji.html

[S59] C++：静态断言
来源：http://dali.hammf.cn/Article/details/gtsibiakit.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jianghu66.top/Article/details/gtcwkhycgo.html

[S60] C++：遍历并删除元素
来源：http://dali.jinqigfzy.top/Article/details/gtvgkzktld.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.yvedp.cn/Article/details/gtnfobjxkz.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtgnbwoumt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.aizwys.cn/Article/details/gtyddcivfs.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gttdlatvql.html

[T01] Kotlin：Hello World
来源：http://dali.yj20258888.top/Article/details/gtfmlolqey.html

println("Hello")
来源：http://dali.wangshuangyany.cn/Article/details/gteikvkwgu.html

[T02] Kotlin：变量
来源：http://dali.jinqigfzy.top/Article/details/gtyycghkod.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.shanyushiyangtech.top/Article/details/gtqtfmmyis.html

[T03] Kotlin：字符串模板
来源：http://dali.zhoulong.xyz/Article/details/gtwpaoofkg.html

"值: $b"
来源：http://dali.guowangkeji.top/Article/details/gtzwybmvmx.html

[T04] Kotlin：空安全
来源：http://dali.chenlongwang.top/Article/details/gtuhvuykhy.html

val n: String? = null;  n?.length
来源：http://dali.jyoumei.cn/Article/details/gtoexonjbz.html

[T05] Kotlin：when 表达式
来源：http://dali.haohaochexian.top/Article/details/gtcidrdxuz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shuidangran.top/Article/details/gttsiibtda.html

[T06] Kotlin：集合映射
来源：http://dali.ehwqpu.com/Article/details/gtmqcvucnu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkyuuwspu.html

[T07] Kotlin：集合过滤
来源：http://dali.xuanzx.com/Article/details/gthjwljgwx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.fengsongda.top/Article/details/gthlxhxmts.html

[T08] Kotlin：数据类
来源：http://dali.redwolf501.top/Article/details/gtxdtzmudt.html

data class User(val name: String, val age: Int)
来源：http://dali.jqgufenzy.top/Article/details/gtxsdbvdmc.html

[T09] Kotlin：扩展函数
来源：http://dali.snrcjt.cn/Article/details/gtvifdddyq.html

fun String.exclaim() = this + "!"
来源：http://dali.wangdashe.top/Article/details/gtfjomvvje.html

[T10] Kotlin：默认参数
来源：http://dali.jyoumei.cn/Article/details/gtlylzlbju.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.zhijiandao.cn/Article/details/gteafexuox.html

[T11] Kotlin：协程
来源：http://dali.ywan-chungtsiang.top/Article/details/gtosgzawbs.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zycfv.cn/Article/details/gtiljlqkpi.html

[T12] Kotlin：解构声明
来源：http://dali.guannengcc.top/Article/details/gtitqkowjs.html

val (a, b) = Pair(1, 2)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttxomhqza.html

[T13] Kotlin：只读 Map
来源：http://dali.yueranfly.top/Article/details/gtfawtqdfu.html

val m = mapOf("a" to 1)
来源：http://dali.chenzaomai.com/Article/details/gtpptveecb.html

[T14] Kotlin：循环
来源：http://dali.pengpengdd.cyou/Article/details/gthexvszqb.html

for (i in 1..10) println(i)
来源：http://dali.pengpengdd.cyou/Article/details/gtdhwrcfyo.html

[T15] Kotlin：接口
来源：http://dali.xuanzx.com/Article/details/gtexbalkrp.html

interface Shape { fun area(): Double }
来源：http://dali.aizwys.cn/Article/details/gtqesbilha.html

[T16] Swift：Hello World
来源：http://dali.aizwys.cn/Article/details/gtpxtdwifl.html

print("Hello")
来源：http://dali.xinyue.icu/Article/details/gtoiryrmgh.html

[T17] Swift：变量与常量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthiqworis.html

var a = 1;  let b = 2
来源：http://dali.quarkkingdee.top/Article/details/gtaijovqmk.html

[T18] Swift：字符串插值
来源：http://dali.zhongyouzk.top/Article/details/gttxllqgrt.html

"值: \(b)"
来源：http://dali.fzhhl.top/Article/details/gtebyobrag.html

[T19] Swift：可选绑定
来源：http://dali.zhoulong.xyz/Article/details/gtcgpgqtte.html

if let n = opt { print(n) }
来源：http://dali.daxiang520.top/Article/details/gtdxlgwgls.html

[T20] Swift：数组操作
来源：http://dali.zhiwuduotai.top/Article/details/gtcbhenkgu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hysaishi.cn/Article/details/gtrjmjvnji.html

[T21] Swift：遍历
来源：http://dali.yueranfly.top/Article/details/gtsnthzugx.html

for x in a { print(x) }
来源：http://dali.hnqzz.top/Article/details/gtqvhpmhvh.html

[T22] Swift：字典
来源：http://dali.xuetiantiany.cn/Article/details/gtwvzhposv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zdqjudy.top/Article/details/gtjjgchimn.html

[T23] Swift：函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtubogjlxf.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjyktokme.html

[T24] Swift：闭包
来源：http://dali.gotoacloud.top/Article/details/gtqjpachca.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.tian-w.cn/Article/details/gtwpqchbxd.html

[T25] Swift：结构体
来源：http://dali.shuidangran.top/Article/details/gtzrsvqjrt.html

struct P { var x: Int }
来源：http://dali.dashuyun.cn/Article/details/gtmrehdfsh.html

[T26] Swift：类与重写
来源：http://dali.hysaishi.cn/Article/details/gtnmwgotvj.html

class A: Base { override func f() {} }
来源：http://dali.yongpay.top/Article/details/gtaolxzbwn.html

[T27] Swift：错误处理
来源：http://dali.tianlin.xyz/Article/details/gtnjdyrgee.html

do { try f() } catch { print(error) }
来源：http://dali.tianlin.xyz/Article/details/gtcyguyxct.html

[T28] Swift：枚举
来源：http://dali.yvedp.cn/Article/details/gtumvupvbf.html

enum Color { case red, green }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpnizchty.html

[T29] Swift：guard 提前返回
来源：http://dali.pycfn.com/Article/details/gtypfudqgp.html

guard let x = opt else { return }
来源：http://dali.hnxiangtu.top/Article/details/gtbxwwzrde.html

[T30] Swift：协议
来源：http://dali.nanxinkj.top/Article/details/gtqxceiscj.html

protocol Shape { func area() -> Double }
来源：http://dali.hongshengwenyu.top/Article/details/gtjlbibtci.html

[T31] Lua：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtkhoqkskz.html

print("Hello")
来源：http://dali.yangfankeji.com/Article/details/gtgdunrhcc.html

[T32] Lua：局部变量
来源：http://dali.haohaochexian.top/Article/details/gtnkewmwem.html

local a = 1
来源：http://dali.jqgfzy.top/Article/details/gtkffqatmo.html

[T33] Lua：表（数组）
来源：http://dali.zhongyouzk.top/Article/details/gtnzwsctpw.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.zhengqikj.top/Article/details/gtzffdyrns.html

[T34] Lua：遍历表
来源：http://dali.zdqjudy.top/Article/details/gtftgbhnyo.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.zhixingplan.top/Article/details/gtpbeecfmc.html

[T35] Lua：字典表
来源：http://dali.andypj.xyz/Article/details/gtkrypxsjp.html

local d = { a = 1 };  d.b = 2
来源：http://dali.yuanzhike.top/Article/details/gtifdxduse.html

[T36] Lua：函数
来源：http://dali.sweek.top/Article/details/gtullkfvqg.html

function add(a, b) return a + b end
来源：http://dali.cdnleiting.top/Article/details/gtwuhragbr.html

[T37] Lua：字符串拼接
来源：http://dali.daria6918.cn/Article/details/gtaifyoveq.html

"a" .. "b"
来源：http://dali.zhoulong.xyz/Article/details/gtfcxbpduo.html

[T38] Lua：条件
来源：http://dali.quarkkingdee.top/Article/details/gtnritoczm.html

if x > 0 then print("正") end
来源：http://dali.gotoacloud.top/Article/details/gtstnkzqsz.html


<!-- 参考信息 -->