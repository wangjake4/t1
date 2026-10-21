代发 wailian999

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yj20258888.top/Article/details/gtxxzzcyvh.html

[R36] 并发执行多个任务
来源：http://dali.svipenyu.cn/Article/details/gtcticsthg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.wangshuangyany.cn/Article/details/gtltczgvjl.html

[R37] 把输出赋给变量
来源：http://dali.tanke756.top/Article/details/gtdphzcyot.html

files=$(ls -1)
来源：http://dali.wangdashe.top/Article/details/gtrerpnzlx.html

[R38] 管道串联
来源：http://dali.ehwqpu.com/Article/details/gttuzofqnc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.tianlin.xyz/Article/details/gtvzbvryqp.html

[R39] 重定向标准输出与错误
来源：http://dali.kuanghao11.cn/Article/details/gtncfiahkg.html

cmd > out.log 2>&1
来源：http://dali.gogol.net.cn/Article/details/gtlsfznxpw.html

[R40] 追加写日志
来源：http://dali.ybcxt.top/Article/details/gtqlzololu.html

echo "log" >> out.log
来源：http://dali.hywenlv.cn/Article/details/gtqcofsibf.html

[R41] 丢弃输出
来源：http://dali.jinqigfzy.top/Article/details/gtwodcehlj.html

cmd >/dev/null 2>&1
来源：http://dali.kuanghao11.cn/Article/details/gtxeqpjzmu.html

[R42] 输入重定向
来源：http://dali.yonumen.top/Article/details/gtjoqzenuj.html

wc -l < a.txt
来源：http://dali.zhongyouzk.top/Article/details/gthrbgmerb.html

[R43] 按名字查找文件
来源：http://dali.hnqzz.top/Article/details/gtkboiqgzs.html

find . -name "*.log" -type f
来源：http://dali.chenjidiqi.icu/Article/details/gtwlxezudj.html

[R44] 按修改时间查找
来源：http://dali.jinghuilouyu.cn/Article/details/gtdfxlpufy.html

find . -mtime -7 -type f
来源：http://dali.jiagoushi.top/Article/details/gtltpscdpb.html

[R45] 批量删除
来源：http://dali.sysykeji.top/Article/details/gtpnaaiyeo.html

find . -name "*.tmp" -delete
来源：http://dali.wangdashe.top/Article/details/gtpafnfoxm.html

[R46] 递归替换文件内容
来源：http://dali.smart0.xyz/Article/details/gtrfpzkweb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhixingplan.top/Article/details/gtbjqnqszb.html

[R47] sed 单行替换
来源：http://dali.wangshuangyany.cn/Article/details/gthtlevrux.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.daria6918.cn/Article/details/gtycfqlpoi.html

[R48] awk 取指定列
来源：http://dali.yj202588.top/Article/details/gtntyqgxad.html

awk '{print $1, $3}' a.txt
来源：http://dali.0kj1m.cn/Article/details/gtkglglckz.html

[R49] awk 带条件
来源：http://dali.pycfn.com/Article/details/gtltqopczt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.guannengcc.top/Article/details/gtajvjiykg.html

[R50] awk 求和
来源：http://dali.haohaochexian.top/Article/details/gtepqpntap.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gotoacloud.top/Article/details/gtnhueemik.html

[R51] 排序去重取前几
来源：http://dali.shangyingyoupin.top/Article/details/gtnlcbddxs.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.aizwys.cn/Article/details/gtktwxuunb.html

[R52] 统计行数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtafndyjvy.html

wc -l a.txt
来源：http://dali.xuanzx.com/Article/details/gtonfoczya.html

[R53] 查看文件头与实时尾
来源：http://dali.quarkkingdee.top/Article/details/gtbzvqtmpl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yongpay.top/Article/details/gtohoaaiul.html

[R54] 比较两个文件
来源：http://dali.cheryme.top/Article/details/gtukpgughi.html

diff a.txt b.txt
来源：http://dali.snrcjt.cn/Article/details/gtbseepgei.html

[R55] 压缩与解压
来源：http://dali.sxryk.cn/Article/details/gturlzyzej.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.dashuyun.cn/Article/details/gtfgaiwzxs.html

[R56] 远程拷贝
来源：http://dali.zhiwuduotai.top/Article/details/gtcawswmrz.html

scp file user@host:/path/
来源：http://dali.gogol.net.cn/Article/details/gtofuscetk.html

[R57] 远程执行命令
来源：http://dali.jlsjyb.cn/Article/details/gtfupxldwb.html

ssh user@host 'uptime'
来源：http://dali.jianghu66.top/Article/details/gthnmtdamo.html

[R58] 下载文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcwugtqfs.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.quarkkingdee.top/Article/details/gtsicoliju.html

[R59] 发 POST JSON
来源：http://dali.fzhhl.top/Article/details/gtwuvpjuki.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yj202588.top/Article/details/gtojrcsmzs.html

[R60] 只看 HTTP 状态码
来源：http://dali.shzxlz.cn/Article/details/gtctwidqjq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sufxvd.cn/Article/details/gtkbgyrrnr.html

[R61] 磁盘占用
来源：http://dali.ybcxt.top/Article/details/gttkokwxqo.html

df -h;  du -sh *
来源：http://dali.zycfv.cn/Article/details/gthijzbpkp.html

[R62] 找最占空间的文件
来源：http://dali.shzxlz.cn/Article/details/gtoyaefiqj.html

du -ah . | sort -rh | head -10
来源：http://dali.ivvv.top/Article/details/gtdsffnrkg.html

[R63] 内存与进程
来源：http://dali.yuxming.cn/Article/details/gtnxlyzgfr.html

free -h;  ps aux | grep nginx
来源：http://dali.feifeiyinyue.top/Article/details/gtyeyrpaed.html

[R64] 结束进程
来源：http://dali.snrcjt.cn/Article/details/gttmqncomg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.9152youxi.cn/Article/details/gtvszfvsiw.html

[R65] 查看端口占用
来源：http://dali.yj20258888.top/Article/details/gtjxeezukf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hammf.cn/Article/details/gtjcjabkdm.html

[R66] 定时任务
来源：http://dali.zhengqikj.top/Article/details/gtkfgvprjt.html

crontab -e;  crontab -l
来源：http://dali.ehwqpu.com/Article/details/gtpxjipdig.html

[R67] 生成随机十六进制串
来源：http://dali.yonumen.top/Article/details/gtcrdjlmgj.html

openssl rand -hex 16
来源：http://dali.ehwqpu.com/Article/details/gtguhfzmcu.html

[R68] 计算文件校验值
来源：http://dali.sweek.top/Article/details/gtvuxvdtkk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shzxlz.cn/Article/details/gtqawfhuag.html

[R69] 生成随机密码
来源：http://dali.chenlongwang.top/Article/details/gtdpdzfnuy.html

head -c 16 /dev/urandom | base64
来源：http://dali.smart0.xyz/Article/details/gtvagwffxn.html

[R70] 时间戳与互转
来源：http://dali.zhiwuduotai.top/Article/details/gttdnirbyb.html

date +%s;  date -d @1700000000
来源：http://dali.xylfe.cn/Article/details/gtvhqwydye.html

[R71] 日期格式化
来源：http://dali.cucudq.cn/Article/details/gthqiuaoze.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.daria6918.cn/Article/details/gtioxlxhbe.html

[R72] 等待端口就绪
来源：http://dali.hammf.cn/Article/details/gtkocfhyoq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.pengpengdd.cyou/Article/details/gtfefzyepd.html

[R73] 分割大日志
来源：http://dali.cqqwz.cn/Article/details/gtddfbyepq.html

split -l 1000 big.log part_
来源：http://dali.9152youxi.cn/Article/details/gtbetcfwbp.html

[R74] 批量重命名
来源：http://dali.smart0.xyz/Article/details/gtgpbryxen.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.aizwys.cn/Article/details/gtqcwwmzjn.html

[R75] 导出环境变量
来源：http://dali.jinghuilouyu.cn/Article/details/gtufzlfszx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.yangfankeji.com/Article/details/gtpelfcamg.html

[R76] 使用临时文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtylemdvyy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.quarkkingdee.top/Article/details/gtlckmglzh.html

[R77] 读取用户输入
来源：http://dali.yonumen.top/Article/details/gturjwqaag.html

read -rp "请输入: " ans
来源：http://dali.shangyingyoupin.top/Article/details/gtxslokeqk.html

[R78] 交互式菜单
来源：http://dali.guannengcc.top/Article/details/gtjjochpuh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sysykeji.top/Article/details/gtsijvgcar.html

[R79] 解析命令行选项
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwbvbmhcg.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.daxiang520.top/Article/details/gtkpvghdna.html

[R80] 查看脚本执行耗时
来源：http://dali.chenjidiqi.icu/Article/details/gtuponefbb.html

time ./run.sh
来源：http://dali.xylfe.cn/Article/details/gtbjzobagx.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtuonvnruo.html

S. C / C++ 专题
来源：http://dali.zhiwuduotai.top/Article/details/gtscjsbkyj.html

================================================================================
来源：http://dali.hnxiangtu.top/Article/details/gtxfbhtffx.html

[S01] C：Hello World
来源：http://dali.ivvv.top/Article/details/gtdlkisqds.html

#include <stdio.h>
来源：http://dali.zycfv.cn/Article/details/gtoibnyguq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.nanxuanxn.top/Article/details/gtfukfgrmb.html

[S02] C：变量与格式化输出
来源：http://dali.daxiang520.top/Article/details/gtdcsflwfm.html

int a = 10; printf("%d\n", a);
来源：http://dali.ybcxt.top/Article/details/gtukvxypkg.html

[S03] C：读入整数
来源：http://dali.smart0.xyz/Article/details/gtbltbywme.html

int x; scanf("%d", &x);
来源：http://dali.xziqi.cn/Article/details/gtblgmdhcb.html

[S04] C：字符串复制
来源：http://dali.316326.xyz/Article/details/gtzhgnwcmx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.tianlin.xyz/Article/details/gtmeitxggp.html

[S05] C：字符串长度
来源：http://dali.kuanghao11.cn/Article/details/gtirpfpxzj.html

strlen(s)
来源：http://dali.yj202588.top/Article/details/gtwvviihli.html

[S06] C：字符串比较
来源：http://dali.hywenlv.cn/Article/details/gtemafyllp.html

strcmp(a, b) == 0
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnyptgudo.html

[S07] C：数组遍历求和
来源：http://dali.cqqwz.cn/Article/details/gtluapejgw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cashguo.top/Article/details/gtwqorvpte.html

[S08] C：动态内存分配与释放
来源：http://dali.daxiang520.top/Article/details/gtuanwokta.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.9152youxi.cn/Article/details/gtdryebynb.html

[S09] C：结构体定义与初始化
来源：http://dali.mhx1999.top/Article/details/gtnfkqfqjx.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ehwqpu.com/Article/details/gtybhkjicb.html

[S10] C：指针与解引用
来源：http://dali.vqdsnc.cn/Article/details/gtimalxazc.html

int *p = &a;  *p = 5;
来源：http://dali.aizwys.cn/Article/details/gtgtfoslip.html

[S11] C：逐行读文件
来源：http://dali.daria6918.cn/Article/details/gtandkbdet.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.pengpengdd.cyou/Article/details/gtggwbzbqe.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.9152youxi.cn/Article/details/gtcyaxtiwu.html

fclose(f);
来源：http://dali.kuanghao11.cn/Article/details/gtqortyvnw.html

[S12] C：写文件
来源：http://dali.0kj1m.cn/Article/details/gttjukdoal.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.nanxinkj.top/Article/details/gthgdyieaq.html

[S13] C：宏定义
来源：http://dali.yvedp.cn/Article/details/gtcfvwvdhm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cashguo.top/Article/details/gtrodmthdq.html

[S14] C：枚举
来源：http://dali.jiagoushi.top/Article/details/gtykdvqsxw.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.gaohongyu789.top/Article/details/gttgzfbjgl.html

[S15] C：类型转换
来源：http://dali.cdnleiting.top/Article/details/gteprcvban.html

(double) a / b
来源：http://dali.shzxlz.cn/Article/details/gtdixiinck.html

[S16] C：位操作置位
来源：http://dali.dianchejie.cn/Article/details/gtuvoicxne.html

x |= (1 << 3);
来源：http://dali.cheryme.top/Article/details/gtgznpkwuj.html

[S17] C：安全拼接字符串
来源：http://dali.yvedp.cn/Article/details/gtifwihmaj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.wangdashe.top/Article/details/gttgozohhz.html

[S18] C：命令行参数
来源：http://dali.aizwys.cn/Article/details/gtxlhphqio.html

int main(int argc, char **argv)
来源：http://dali.fzhhl.top/Article/details/gthsnbgmuw.html

[S19] C：快速排序
来源：http://dali.jqgufenzy.top/Article/details/gtfxmmvvfb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.guowangkeji.top/Article/details/gtwludijjb.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gtebtnjarq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.chenlongwang.top/Article/details/gtgzlywfsn.html

[S21] C：字符类别判断
来源：http://dali.jinghuilouyu.cn/Article/details/gtmppgaevq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.tian-w.cn/Article/details/gtmirjmjij.html

[S22] C：字符串转数字
来源：http://dali.xinyue.icu/Article/details/gtyjessolq.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.jyoumei.cn/Article/details/gtuiefoabj.html

[S23] C：随机数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpstkxlrh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.jinqigufen.top/Article/details/gtjttdolgi.html

[S24] C：获取本地时间
来源：http://dali.jinqigufen.top/Article/details/gtdqqzvatl.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.snrcjt.cn/Article/details/gtjczebthy.html

[S25] C：内存拷贝
来源：http://dali.yj20258.top/Article/details/gtfsroptgm.html

memcpy(dst, src, n);
来源：http://dali.xuetiantiany.cn/Article/details/gtcdcxplzv.html

[S26] C：内存清零
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlzfkrral.html

memset(a, 0, sizeof a);
来源：http://dali.nanxuanxn.top/Article/details/gtadcidzja.html

[S27] C：定义常量
来源：http://dali.sysykeji.top/Article/details/gthxtfydep.html

const double PI = 3.14159;
来源：http://dali.nwbrower.top/Article/details/gtmhpcyxny.html

[S28] C：静态变量
来源：http://dali.dashuyun.cn/Article/details/gtvlumzqty.html

static int counter = 0;
来源：http://dali.jqgufenzy.top/Article/details/gtvvkxeaze.html

[S29] C：变参函数
来源：http://dali.c1oappe.top/Article/details/gtalettnsw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.yangfankeji.com/Article/details/gtwvhhrjey.html

[S30] C：头文件保护
来源：http://dali.hnqzz.top/Article/details/gtpzqxfjlb.html

#ifndef X_H
来源：http://dali.dianchejie.cn/Article/details/gtrtilzgwn.html

#define X_H
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzwklumff.html

#endif
来源：http://dali.shuidangran.top/Article/details/gtfjvafrbt.html

[S31] C++：Hello World
来源：http://dali.jlsjyb.cn/Article/details/gtgmzpvzfs.html

#include <iostream>
来源：http://dali.hnxiangtu.top/Article/details/gtewcfkyvq.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaqbuhels.html

[S32] C++：字符串
来源：http://dali.zycfv.cn/Article/details/gtzgwphwzn.html

std::string s = "hi";  s += "!";
来源：http://dali.c1oappe.top/Article/details/gtwhtqmtle.html

[S33] C++：vector 增删
来源：http://dali.jyoumei.cn/Article/details/gtrrccmxcz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.9152youxi.cn/Article/details/gthfsndxsj.html

[S34] C++：遍历 vector
来源：http://dali.nwbrower.top/Article/details/gtplindzjd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.tian-w.cn/Article/details/gtbwcmxtzg.html

[S35] C++：map
来源：http://dali.wangshuangyany.cn/Article/details/gtkldjzowm.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tanke756.top/Article/details/gtnvkcyfqh.html

[S36] C++：unordered_map
来源：http://dali.zhoulong.xyz/Article/details/gtahvjmpfn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.cucudq.cn/Article/details/gtshfvmbij.html

[S37] C++：set
来源：http://dali.yanxiufei.cn/Article/details/gtldoszztf.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.vqdsnc.cn/Article/details/gtazohnksg.html

[S38] C++：排序
来源：http://dali.jinghuilouyu.cn/Article/details/gtszkddpog.html

std::sort(v.begin(), v.end());
来源：http://dali.andypj.xyz/Article/details/gtdppzidnw.html

[S39] C++：自定义比较器排序
来源：http://dali.xziqi.cn/Article/details/gtlvpjmsrf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sxryk.cn/Article/details/gtavmbazae.html

[S40] C++：查找元素
来源：http://dali.nanxinkj.top/Article/details/gtdgmdpuma.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.iojbl.cn/Article/details/gtnbuyqwmn.html

[S41] C++：类与构造函数
来源：http://dali.pengpengdd.cyou/Article/details/gtiarowlne.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.guannengcc.top/Article/details/gtypdlwzwd.html

[S42] C++：继承与虚函数
来源：http://dali.yongpay.top/Article/details/gtscntornz.html

class B : public Base { public: void f() override {} };
来源：http://dali.guowangkeji.top/Article/details/gtoywjixku.html

[S43] C++：智能指针
来源：http://dali.yangfankeji.com/Article/details/gtbfpmcxij.html

auto p = std::make_unique<int>(5);
来源：http://dali.kuanghao11.cn/Article/details/gtlnbleotb.html

[S44] C++：引用传参
来源：http://dali.hfpthk.cn/Article/details/gtcqurcoxl.html

void inc(int &x) { ++x; }
来源：http://dali.jianghu66.top/Article/details/gtjrjmsvsj.html

[S45] C++：lambda
来源：http://dali.zhongyouzk.top/Article/details/gtbcxozfbj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.chenjidiqi.icu/Article/details/gtfxpzwcam.html

[S46] C++：函数模板
来源：http://dali.cheryme.top/Article/details/gtonrqmcns.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.pengpengdd.cyou/Article/details/gtyejpdisf.html

[S47] C++：结构化绑定遍历
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmmgiylje.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.fengsongda.top/Article/details/gtdmokuigr.html

[S48] C++：逐行读文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfqanqpwi.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zhongyouzk.top/Article/details/gtflnyotko.html

while (std::getline(in, line)) { }
来源：http://dali.jlsjyb.cn/Article/details/gtsxlfujub.html

[S49] C++：写文件
来源：http://dali.yj20258888.top/Article/details/gtgrgqrisi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jqgfzy.top/Article/details/gtyimjhuif.html

[S50] C++：格式化数字
来源：http://dali.hongshengwenyu.top/Article/details/gttqcfmxep.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yuxming.cn/Article/details/gtmhxzpbtw.html

[S51] C++：显式类型转换
来源：http://dali.xuanzx.com/Article/details/gtkawgwuym.html

static_cast<double>(a) / b
来源：http://dali.nanxuanxn.top/Article/details/gtlpjwigko.html

[S52] C++：const 与 noexcept
来源：http://dali.xuetiantiany.cn/Article/details/gtozhhbruz.html

int size() const noexcept { return n_; }
来源：http://dali.cheryme.top/Article/details/gtfoeurkwg.html

[S53] C++：移动语义
来源：http://dali.iojbl.cn/Article/details/gthnocjaug.html

std::vector<int> w = std::move(v);
来源：http://dali.yj20258.top/Article/details/gtuolwmegr.html

[S54] C++：异常处理
来源：http://dali.ivvv.top/Article/details/gtzogfzkrh.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.tianlin.xyz/Article/details/gttarfoqga.html

[S55] C++：结构化绑定
来源：http://dali.ybcxt.top/Article/details/gtdtlebhij.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jlsjyb.cn/Article/details/gtndbtjdrh.html

[S56] C++：optional
来源：http://dali.ivvv.top/Article/details/gtaljdgvnw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.shanyushiyangtech.top/Article/details/gtmjxesqvv.html

[S57] C++：编译期常量
来源：http://dali.fengsongda.top/Article/details/gtylcopqux.html

constexpr int N = 10;
来源：http://dali.zhengqikj.top/Article/details/gtfqkktnge.html

[S58] C++：命名空间
来源：http://dali.pengpengdd.cyou/Article/details/gtiexwpyoe.html

namespace ns { int f() { return 1; } }
来源：http://dali.jinqigufen.top/Article/details/gtmovlyfoe.html

[S59] C++：静态断言
来源：http://dali.zdqjudy.top/Article/details/gtelzgfmrc.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cqqwz.cn/Article/details/gttnjbkkkd.html

[S60] C++：遍历并删除元素
来源：http://dali.kuanghao11.cn/Article/details/gtodwekshm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.nanxuanxn.top/Article/details/gtlacnheoy.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtclhjikng.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.mhx1999.top/Article/details/gtexphuxtm.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtphrqsvma.html

[T01] Kotlin：Hello World
来源：http://dali.aibaodan.cn/Article/details/gttixjofuh.html

println("Hello")
来源：http://dali.smart0.xyz/Article/details/gtpvyrskyb.html

[T02] Kotlin：变量
来源：http://dali.hfpthk.cn/Article/details/gtxlcxtnpl.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.9152youxi.cn/Article/details/gtsfbofjnr.html

[T03] Kotlin：字符串模板
来源：http://dali.snrcjt.cn/Article/details/gtrvqbxznj.html

"值: $b"
来源：http://dali.zycfv.cn/Article/details/gtkucrsorn.html

[T04] Kotlin：空安全
来源：http://dali.nwbrower.top/Article/details/gtunrzdcdu.html

val n: String? = null;  n?.length
来源：http://dali.andypj.xyz/Article/details/gtiigvdtbi.html

[T05] Kotlin：when 表达式
来源：http://dali.aizwys.cn/Article/details/gtrywygxhz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.zhixingplan.top/Article/details/gtondkfieq.html

[T06] Kotlin：集合映射
来源：http://dali.aizwys.cn/Article/details/gtuvvbzmbg.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.aibaodan.cn/Article/details/gturcbbolu.html

[T07] Kotlin：集合过滤
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttdbwmghh.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtinlyahwi.html

[T08] Kotlin：数据类
来源：http://dali.redwolf501.top/Article/details/gtalsystaw.html

data class User(val name: String, val age: Int)
来源：http://dali.dianchejie.cn/Article/details/gtugryyeou.html

[T09] Kotlin：扩展函数
来源：http://dali.nanxuanxn.top/Article/details/gtqchkgttu.html

fun String.exclaim() = this + "!"
来源：http://dali.birdmap.top/Article/details/gthxfxmosv.html

[T10] Kotlin：默认参数
来源：http://dali.kuanghao11.cn/Article/details/gtnygcaueb.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.yanxiufei.cn/Article/details/gtrbsxojbg.html

[T11] Kotlin：协程
来源：http://dali.xinyue.icu/Article/details/gtgfdwuyle.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.andypj.xyz/Article/details/gtgbqjbayz.html

[T12] Kotlin：解构声明
来源：http://dali.yonumen.top/Article/details/gtkbbuetsq.html

val (a, b) = Pair(1, 2)
来源：http://dali.gzhubu.top/Article/details/gthunimnwf.html

[T13] Kotlin：只读 Map
来源：http://dali.cdnleiting.top/Article/details/gthxgdffpw.html

val m = mapOf("a" to 1)
来源：http://dali.wangdashe.top/Article/details/gtunjabqjh.html

[T14] Kotlin：循环
来源：http://dali.jinqigufen.top/Article/details/gtmcowrhml.html

for (i in 1..10) println(i)
来源：http://dali.zhixingplan.top/Article/details/gtwqybtxvh.html

[T15] Kotlin：接口
来源：http://dali.iojbl.cn/Article/details/gtgukiuxdy.html

interface Shape { fun area(): Double }
来源：http://dali.nwbrower.top/Article/details/gtnoltyzzy.html

[T16] Swift：Hello World
来源：http://dali.hfpthk.cn/Article/details/gtnnfmlmyf.html

print("Hello")
来源：http://dali.birdmap.top/Article/details/gtbplxyncc.html

[T17] Swift：变量与常量
来源：http://dali.sufxvd.cn/Article/details/gtwzndzswo.html

var a = 1;  let b = 2
来源：http://dali.ydzc1.top/Article/details/gtkprbqyzo.html

[T18] Swift：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gtclotqsdf.html

"值: \(b)"
来源：http://dali.9152youxi.cn/Article/details/gthkvensho.html

[T19] Swift：可选绑定
来源：http://dali.birdmap.top/Article/details/gtwidxlvvu.html

if let n = opt { print(n) }
来源：http://dali.zhoulong.xyz/Article/details/gtlputdtgn.html

[T20] Swift：数组操作
来源：http://dali.hammf.cn/Article/details/gtqyxaujwv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.cdnleiting.top/Article/details/gtwwdjtwkw.html

[T21] Swift：遍历
来源：http://dali.cdnleiting.top/Article/details/gtsemzatpi.html

for x in a { print(x) }
来源：http://dali.jlsjyb.cn/Article/details/gtzejjpjzl.html

[T22] Swift：字典
来源：http://dali.zhoulong.xyz/Article/details/gtrcdshbxv.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.xuanzx.com/Article/details/gtvgpasvsa.html

[T23] Swift：函数
来源：http://dali.yanxiufei.cn/Article/details/gthbcudnet.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.hammf.cn/Article/details/gtxwspftgc.html

[T24] Swift：闭包
来源：http://dali.hammf.cn/Article/details/gthexqzlui.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.nanxinkj.top/Article/details/gtbealoipj.html

[T25] Swift：结构体
来源：http://dali.hammf.cn/Article/details/gtdhdiwjss.html

struct P { var x: Int }
来源：http://dali.redwolf501.top/Article/details/gtfaufyfia.html

[T26] Swift：类与重写
来源：http://dali.dashuyun.cn/Article/details/gtajbafdej.html

class A: Base { override func f() {} }
来源：http://dali.wangdashe.top/Article/details/gtwuaenepp.html

[T27] Swift：错误处理
来源：http://dali.cdnleiting.top/Article/details/gthheltqtt.html

do { try f() } catch { print(error) }
来源：http://dali.hywenlv.cn/Article/details/gtlkybvwki.html

[T28] Swift：枚举
来源：http://dali.kuanghao11.cn/Article/details/gtieotajem.html

enum Color { case red, green }
来源：http://dali.gogol.net.cn/Article/details/gtortqvtew.html

[T29] Swift：guard 提前返回
来源：http://dali.yanxiufei.cn/Article/details/gtoxnnpgnk.html

guard let x = opt else { return }
来源：http://dali.yueranfly.top/Article/details/gtqymcwcej.html

[T30] Swift：协议
来源：http://dali.yj202588.top/Article/details/gtmuvoovpc.html

protocol Shape { func area() -> Double }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxcdcdhnk.html

[T31] Lua：Hello World
来源：http://dali.xylfe.cn/Article/details/gtjmzmwqkv.html

print("Hello")
来源：http://dali.vqdsnc.cn/Article/details/gtjlfelgbk.html

[T32] Lua：局部变量
来源：http://dali.redwolf501.top/Article/details/gtzbmdmexn.html

local a = 1
来源：http://dali.quarkkingdee.top/Article/details/gtbcilwfdk.html

[T33] Lua：表（数组）
来源：http://dali.birdmap.top/Article/details/gtdnatbffv.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.jqgufenzy.top/Article/details/gtggtxhebs.html

[T34] Lua：遍历表
来源：http://dali.jiagoushi.top/Article/details/gtrjewjpdc.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.jqgfzy.top/Article/details/gtvlhlbysz.html

[T35] Lua：字典表
来源：http://dali.dianchejie.cn/Article/details/gtexeywnky.html

local d = { a = 1 };  d.b = 2
来源：http://dali.dianchejie.cn/Article/details/gtqekazcbp.html

[T36] Lua：函数
来源：http://dali.hywenlv.cn/Article/details/gtnoocfcgc.html

function add(a, b) return a + b end
来源：http://dali.quarkkingdee.top/Article/details/gtziftwkje.html

[T37] Lua：字符串拼接
来源：http://dali.c1oappe.top/Article/details/gtnjfzteau.html

"a" .. "b"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqewwjcnz.html

[T38] Lua：条件
来源：http://dali.ydzc1.top/Article/details/gtzuruysjj.html

if x > 0 then print("正") end
来源：http://dali.zhengqikj.top/Article/details/gtsozzwplv.html


<!-- 参考信息 -->