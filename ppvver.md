代发 wailian999

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sxryk.cn/Article/details/gtpdaqnpeg.html

[R34] 退出时清理
来源：http://dali.chenjidiqi.icu/Article/details/gthqczkoxm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hammf.cn/Article/details/gtkmkryrds.html

[R35] 后台执行并等待
来源：http://dali.cdnleiting.top/Article/details/gtitnviuke.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.nanxuanxn.top/Article/details/gtsraxgghh.html

[R36] 并发执行多个任务
来源：http://dali.wangdashe.top/Article/details/gtoduyoiwa.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.havefunace.top/Article/details/gtjjvhsaox.html

[R37] 把输出赋给变量
来源：http://dali.sufxvd.cn/Article/details/gtkmnnhfdy.html

files=$(ls -1)
来源：http://dali.chenzaomai.com/Article/details/gtjyqmlfch.html

[R38] 管道串联
来源：http://dali.havefunace.top/Article/details/gtfwtbmpwz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yvedp.cn/Article/details/gtciphknts.html

[R39] 重定向标准输出与错误
来源：http://dali.zhiwuduotai.top/Article/details/gtbwevgswd.html

cmd > out.log 2>&1
来源：http://dali.xziqi.cn/Article/details/gtnhqoeyiv.html

[R40] 追加写日志
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttlixhkhs.html

echo "log" >> out.log
来源：http://dali.jianghu66.top/Article/details/gtqmotwaza.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gtkxjvtjmh.html

cmd >/dev/null 2>&1
来源：http://dali.aizwys.cn/Article/details/gtvzthidzw.html

[R42] 输入重定向
来源：http://dali.hfpthk.cn/Article/details/gtqraqsnfy.html

wc -l < a.txt
来源：http://dali.mhx1999.top/Article/details/gtyhmgqxdc.html

[R43] 按名字查找文件
来源：http://dali.jinqigfzy.top/Article/details/gtfupmcpid.html

find . -name "*.log" -type f
来源：http://dali.smart0.xyz/Article/details/gtazfubxmx.html

[R44] 按修改时间查找
来源：http://dali.wangshuangyany.cn/Article/details/gtihrirdjx.html

find . -mtime -7 -type f
来源：http://dali.yuxming.cn/Article/details/gtyabkxlda.html

[R45] 批量删除
来源：http://dali.gzhubu.top/Article/details/gtwruzvvmb.html

find . -name "*.tmp" -delete
来源：http://dali.jianghu66.top/Article/details/gtgqbfjncm.html

[R46] 递归替换文件内容
来源：http://dali.cucudq.cn/Article/details/gtgiezxxuq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj202588.top/Article/details/gtruyrumcf.html

[R47] sed 单行替换
来源：http://dali.zhixingplan.top/Article/details/gtreippebn.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.tanke756.top/Article/details/gtrjidizpo.html

[R48] awk 取指定列
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtabmahkvr.html

awk '{print $1, $3}' a.txt
来源：http://dali.chenlongwang.top/Article/details/gteiadpiny.html

[R49] awk 带条件
来源：http://dali.sxryk.cn/Article/details/gtninihxgo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yueranfly.top/Article/details/gtruykmzaf.html

[R50] awk 求和
来源：http://dali.9152youxi.cn/Article/details/gtgrapohyx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtoqbnnuhm.html

[R51] 排序去重取前几
来源：http://dali.xziqi.cn/Article/details/gtieurdkbl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gogol.net.cn/Article/details/gtefxecmno.html

[R52] 统计行数
来源：http://dali.hnxiangtu.top/Article/details/gtobcdovcs.html

wc -l a.txt
来源：http://dali.yj20258888.top/Article/details/gtrmyvqlbu.html

[R53] 查看文件头与实时尾
来源：http://dali.bjfxy.top/Article/details/gttdqwuffz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.guowangkeji.top/Article/details/gtifbwpndp.html

[R54] 比较两个文件
来源：http://dali.kuanghao11.cn/Article/details/gtsjibpmpk.html

diff a.txt b.txt
来源：http://dali.gotoacloud.top/Article/details/gtxsirrejl.html

[R55] 压缩与解压
来源：http://dali.feifeiyinyue.top/Article/details/gterqwdajp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ppjwa.cn/Article/details/gtjkxzfrpb.html

[R56] 远程拷贝
来源：http://dali.hnqzz.top/Article/details/gtqizvdazn.html

scp file user@host:/path/
来源：http://dali.meibo888.top/Article/details/gtpbrrpyjm.html

[R57] 远程执行命令
来源：http://dali.ydzc1.top/Article/details/gtwafedexy.html

ssh user@host 'uptime'
来源：http://dali.dashuyun.cn/Article/details/gtxwgknwxe.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gtoaexzrnj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yvedp.cn/Article/details/gtrmmloblh.html

[R59] 发 POST JSON
来源：http://dali.xuanzx.com/Article/details/gtlkbrmnmq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hammf.cn/Article/details/gtmasmhopd.html

[R60] 只看 HTTP 状态码
来源：http://dali.sxryk.cn/Article/details/gthgidozxn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hywenlv.cn/Article/details/gtikrzxhts.html

[R61] 磁盘占用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgaotnaal.html

df -h;  du -sh *
来源：http://dali.gotoacloud.top/Article/details/gtsqhjhzqx.html

[R62] 找最占空间的文件
来源：http://dali.xylfe.cn/Article/details/gtbgowxuqq.html

du -ah . | sort -rh | head -10
来源：http://dali.ppjwa.cn/Article/details/gtnmolnnlx.html

[R63] 内存与进程
来源：http://dali.9152youxi.cn/Article/details/gtvldaezcs.html

free -h;  ps aux | grep nginx
来源：http://dali.pycfn.com/Article/details/gtnwjcslhy.html

[R64] 结束进程
来源：http://dali.zycfv.cn/Article/details/gtasmhyphy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xylfe.cn/Article/details/gtmzchtvop.html

[R65] 查看端口占用
来源：http://dali.cashguo.top/Article/details/gthvzcllhf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sweek.top/Article/details/gtldgrzvcc.html

[R66] 定时任务
来源：http://dali.cqqwz.cn/Article/details/gtqruqpeus.html

crontab -e;  crontab -l
来源：http://dali.vqdsnc.cn/Article/details/gtxhnrtmyu.html

[R67] 生成随机十六进制串
来源：http://dali.zdqjudy.top/Article/details/gtvhugrfgs.html

openssl rand -hex 16
来源：http://dali.smart0.xyz/Article/details/gtkpjmmmwk.html

[R68] 计算文件校验值
来源：http://dali.yuxming.cn/Article/details/gtapefxjrp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtrogdbemr.html

[R69] 生成随机密码
来源：http://dali.shzxlz.cn/Article/details/gtmjornkgr.html

head -c 16 /dev/urandom | base64
来源：http://dali.hysaishi.cn/Article/details/gtsujznoou.html

[R70] 时间戳与互转
来源：http://dali.aizwys.cn/Article/details/gtlqnuessx.html

date +%s;  date -d @1700000000
来源：http://dali.cdnleiting.top/Article/details/gtcoiullio.html

[R71] 日期格式化
来源：http://dali.dianchejie.cn/Article/details/gtcnlrjbcn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gtzilbcxic.html

[R72] 等待端口就绪
来源：http://dali.andypj.xyz/Article/details/gtkslzafdk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ydzc1.top/Article/details/gtsfzziwvl.html

[R73] 分割大日志
来源：http://dali.andypj.xyz/Article/details/gtygjtvrqb.html

split -l 1000 big.log part_
来源：http://dali.svipenyu.cn/Article/details/gtajvqkdky.html

[R74] 批量重命名
来源：http://dali.tian-w.cn/Article/details/gtpvunnnsm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhongyouzk.top/Article/details/gtcwpqqtgz.html

[R75] 导出环境变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmvxmbbsy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.birdmap.top/Article/details/gtsxzshgii.html

[R76] 使用临时文件
来源：http://dali.zhengqikj.top/Article/details/gtgeoetegw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.tanke756.top/Article/details/gtpmsznqqm.html

[R77] 读取用户输入
来源：http://dali.xinyue.icu/Article/details/gtcagmhtvr.html

read -rp "请输入: " ans
来源：http://dali.yonumen.top/Article/details/gtsvjxjdiw.html

[R78] 交互式菜单
来源：http://dali.jlsjyb.cn/Article/details/gtfwnzsxqh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jinqigufen.top/Article/details/gtizaroiks.html

[R79] 解析命令行选项
来源：http://dali.zdqjudy.top/Article/details/gtnqxsscnm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuvqqtvpc.html

[R80] 查看脚本执行耗时
来源：http://dali.yanxiufei.cn/Article/details/gtekosasox.html

time ./run.sh
来源：http://dali.jinghuilouyu.cn/Article/details/gtepbrswdk.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlmldvzqn.html

S. C / C++ 专题
来源：http://dali.yuanzhike.top/Article/details/gtkpzymien.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuyqvggfi.html

[S01] C：Hello World
来源：http://dali.vqdsnc.cn/Article/details/gtkiemvhjr.html

#include <stdio.h>
来源：http://dali.havefunace.top/Article/details/gtcualjiug.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.daxiang520.top/Article/details/gtkuyfzizn.html

[S02] C：变量与格式化输出
来源：http://dali.dashuyun.cn/Article/details/gtsduanlzt.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhoulong.xyz/Article/details/gtxcazvybc.html

[S03] C：读入整数
来源：http://dali.hysaishi.cn/Article/details/gtbnvuwtlz.html

int x; scanf("%d", &x);
来源：http://dali.guannengcc.top/Article/details/gtnhlcvxjk.html

[S04] C：字符串复制
来源：http://dali.fengsongda.top/Article/details/gtsmdvhivu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jqgufenzy.top/Article/details/gtjvomdfic.html

[S05] C：字符串长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgeqmrspx.html

strlen(s)
来源：http://dali.yj20258888.top/Article/details/gtictfjqer.html

[S06] C：字符串比较
来源：http://dali.havefunace.top/Article/details/gtzslsrqjv.html

strcmp(a, b) == 0
来源：http://dali.zhoulong.xyz/Article/details/gtjwgkojiu.html

[S07] C：数组遍历求和
来源：http://dali.nwbrower.top/Article/details/gtaiklsjxs.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.wangdashe.top/Article/details/gthfvqusqz.html

[S08] C：动态内存分配与释放
来源：http://dali.jinghuilouyu.cn/Article/details/gthzphlmxj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.yonumen.top/Article/details/gtjknicgbj.html

[S09] C：结构体定义与初始化
来源：http://dali.svipenyu.cn/Article/details/gtdjzyrues.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ivvv.top/Article/details/gtqabllccx.html

[S10] C：指针与解引用
来源：http://dali.zhaomingkeji.xyz/Article/details/gtysdwzxga.html

int *p = &a;  *p = 5;
来源：http://dali.feifeiyinyue.top/Article/details/gtwzxvaemg.html

[S11] C：逐行读文件
来源：http://dali.c1oappe.top/Article/details/gtdlzbzbst.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.haohaochexian.top/Article/details/gtnflulbml.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hysaishi.cn/Article/details/gttnmswpxj.html

fclose(f);
来源：http://dali.shangyingyoupin.top/Article/details/gtviotrmrx.html

[S12] C：写文件
来源：http://dali.daria6918.cn/Article/details/gtzlgggikj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.nwbrower.top/Article/details/gtkrkdeqnp.html

[S13] C：宏定义
来源：http://dali.zycfv.cn/Article/details/gtjfkgtqyj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yj20258888.top/Article/details/gthdwxhpov.html

[S14] C：枚举
来源：http://dali.yvedp.cn/Article/details/gtgnptqqjx.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.cqqwz.cn/Article/details/gtfzfoqclu.html

[S15] C：类型转换
来源：http://dali.cucudq.cn/Article/details/gtijcxdqnd.html

(double) a / b
来源：http://dali.yj20258888.top/Article/details/gtqdororxd.html

[S16] C：位操作置位
来源：http://dali.haohaochexian.top/Article/details/gtrlvpoaxx.html

x |= (1 << 3);
来源：http://dali.daxiang520.top/Article/details/gtusijxanj.html

[S17] C：安全拼接字符串
来源：http://dali.iojbl.cn/Article/details/gtqqurybjy.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.daria6918.cn/Article/details/gtgcbxzdcw.html

[S18] C：命令行参数
来源：http://dali.bjfxy.top/Article/details/gtadochelq.html

int main(int argc, char **argv)
来源：http://dali.hysaishi.cn/Article/details/gtlbxjhueb.html

[S19] C：快速排序
来源：http://dali.dashuyun.cn/Article/details/gttjfulesw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gtuodimuyy.html

[S20] C：二分查找
来源：http://dali.chenzaomai.com/Article/details/gtdgwacexo.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjslcjttb.html

[S21] C：字符类别判断
来源：http://dali.zhaomingkeji.xyz/Article/details/gtohjqvbxm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.quarkkingdee.top/Article/details/gtfscpirna.html

[S22] C：字符串转数字
来源：http://dali.9152youxi.cn/Article/details/gtoiynafdw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.redwolf501.top/Article/details/gtvjoswwaw.html

[S23] C：随机数
来源：http://dali.zhiwuduotai.top/Article/details/gtakcefpbr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.aizwys.cn/Article/details/gtidmvxreo.html

[S24] C：获取本地时间
来源：http://dali.yj20258888.top/Article/details/gtmuuooiex.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ybcxt.top/Article/details/gtpkvnwadf.html

[S25] C：内存拷贝
来源：http://dali.andypj.xyz/Article/details/gtfathjijx.html

memcpy(dst, src, n);
来源：http://dali.bjfxy.top/Article/details/gttbzxijek.html

[S26] C：内存清零
来源：http://dali.cheryme.top/Article/details/gtfanvblmp.html

memset(a, 0, sizeof a);
来源：http://dali.jyoumei.cn/Article/details/gtdhcwclwx.html

[S27] C：定义常量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxprcpmar.html

const double PI = 3.14159;
来源：http://dali.xylfe.cn/Article/details/gtcmarlqlo.html

[S28] C：静态变量
来源：http://dali.zycfv.cn/Article/details/gtxkawntfw.html

static int counter = 0;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmlatpuun.html

[S29] C：变参函数
来源：http://dali.quarkkingdee.top/Article/details/gtaorrcpna.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hnqzz.top/Article/details/gtdzutqfpx.html

[S30] C：头文件保护
来源：http://dali.svipenyu.cn/Article/details/gtaceswtgc.html

#ifndef X_H
来源：http://dali.shanyushiyangtech.top/Article/details/gtkhcawpzg.html

#define X_H
来源：http://dali.316326.xyz/Article/details/gtpcvnpdiv.html

#endif
来源：http://dali.yonumen.top/Article/details/gtkahuopqw.html

[S31] C++：Hello World
来源：http://dali.guowangkeji.top/Article/details/gtdzyacfpj.html

#include <iostream>
来源：http://dali.mhx1999.top/Article/details/gtsobszade.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.havefunace.top/Article/details/gtlcoxbidz.html

[S32] C++：字符串
来源：http://dali.jqgfzy.top/Article/details/gtuaqmnhra.html

std::string s = "hi";  s += "!";
来源：http://dali.fengsongda.top/Article/details/gtsnaotkhs.html

[S33] C++：vector 增删
来源：http://dali.wangdashe.top/Article/details/gtzbtqctrq.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinqigufen.top/Article/details/gtxzycoqlq.html

[S34] C++：遍历 vector
来源：http://dali.yj202588.top/Article/details/gtprwaxffo.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yuxming.cn/Article/details/gtjkrtvenn.html

[S35] C++：map
来源：http://dali.shanyushiyangtech.top/Article/details/gtyxyvhodp.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ppjwa.cn/Article/details/gtoitnvskc.html

[S36] C++：unordered_map
来源：http://dali.zycfv.cn/Article/details/gtrfroikzu.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yj20258.top/Article/details/gtkyeztack.html

[S37] C++：set
来源：http://dali.havefunace.top/Article/details/gtucgqbvwy.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.yuxming.cn/Article/details/gtyjeqbpge.html

[S38] C++：排序
来源：http://dali.wangdashe.top/Article/details/gtbepuhbef.html

std::sort(v.begin(), v.end());
来源：http://dali.c1oappe.top/Article/details/gtrfoeeauj.html

[S39] C++：自定义比较器排序
来源：http://dali.gaohongyu789.top/Article/details/gtjyikdkay.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.zhongyouzk.top/Article/details/gtvcarbdcj.html

[S40] C++：查找元素
来源：http://dali.shzxlz.cn/Article/details/gtjvgtzfwa.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xuetiantiany.cn/Article/details/gtorihjjqx.html

[S41] C++：类与构造函数
来源：http://dali.cucudq.cn/Article/details/gtifzyszeo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.nwbrower.top/Article/details/gtnzlmwgzf.html

[S42] C++：继承与虚函数
来源：http://dali.cqqwz.cn/Article/details/gthzjjmgpn.html

class B : public Base { public: void f() override {} };
来源：http://dali.hfpthk.cn/Article/details/gtvcpmhjrb.html

[S43] C++：智能指针
来源：http://dali.dianchejie.cn/Article/details/gtpcgmyglu.html

auto p = std::make_unique<int>(5);
来源：http://dali.tianlin.xyz/Article/details/gtxzmeimus.html

[S44] C++：引用传参
来源：http://dali.quarkkingdee.top/Article/details/gtvgaxulrk.html

void inc(int &x) { ++x; }
来源：http://dali.zycfv.cn/Article/details/gtrenevebt.html

[S45] C++：lambda
来源：http://dali.yj20258.top/Article/details/gtaqverfbt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.jinqigufen.top/Article/details/gtmejbdhnw.html

[S46] C++：函数模板
来源：http://dali.hfpthk.cn/Article/details/gtmcjrndkg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.gogol.net.cn/Article/details/gtgznengsb.html

[S47] C++：结构化绑定遍历
来源：http://dali.birdmap.top/Article/details/gtrbndioun.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.jiagoushi.top/Article/details/gtvhymksdh.html

[S48] C++：逐行读文件
来源：http://dali.shzxlz.cn/Article/details/gtqsspovzl.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.gzhubu.top/Article/details/gtsjwakfqn.html

while (std::getline(in, line)) { }
来源：http://dali.yonumen.top/Article/details/gtegxktyzz.html

[S49] C++：写文件
来源：http://dali.quarkkingdee.top/Article/details/gtmylvochh.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinghuilouyu.cn/Article/details/gtnhptbkyc.html

[S50] C++：格式化数字
来源：http://dali.gotoacloud.top/Article/details/gtwhdwryxh.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.iojbl.cn/Article/details/gtmnebvvgo.html

[S51] C++：显式类型转换
来源：http://dali.aibaodan.cn/Article/details/gtzhjjajvf.html

static_cast<double>(a) / b
来源：http://dali.hnqzz.top/Article/details/gtixgmyskw.html

[S52] C++：const 与 noexcept
来源：http://dali.pengpengdd.cyou/Article/details/gtlzahpsff.html

int size() const noexcept { return n_; }
来源：http://dali.sxryk.cn/Article/details/gtbsixqclt.html

[S53] C++：移动语义
来源：http://dali.gotoacloud.top/Article/details/gtiahxzhdn.html

std::vector<int> w = std::move(v);
来源：http://dali.mhx1999.top/Article/details/gtnohsjjgo.html

[S54] C++：异常处理
来源：http://dali.jinqigufen.top/Article/details/gtztnpeglq.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.zhixingplan.top/Article/details/gtvjftdrzp.html

[S55] C++：结构化绑定
来源：http://dali.bjfxy.top/Article/details/gtdfqtvtlc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.aibaodan.cn/Article/details/gtyxmbffvk.html

[S56] C++：optional
来源：http://dali.shanyushiyangtech.top/Article/details/gtrzieaxzg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.zhoulong.xyz/Article/details/gthirhwhjl.html

[S57] C++：编译期常量
来源：http://dali.daria6918.cn/Article/details/gtrytdnzyc.html

constexpr int N = 10;
来源：http://dali.chenzaomai.com/Article/details/gtqddvprhz.html

[S58] C++：命名空间
来源：http://dali.ybcxt.top/Article/details/gtyxsmndwt.html

namespace ns { int f() { return 1; } }
来源：http://dali.yvedp.cn/Article/details/gtmpjkryco.html

[S59] C++：静态断言
来源：http://dali.c1oappe.top/Article/details/gtfkgkrsar.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.jyoumei.cn/Article/details/gtemldyums.html

[S60] C++：遍历并删除元素
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnpfookqy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.andypj.xyz/Article/details/gtwxdmmufq.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtmilrongw.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shanyushiyangtech.top/Article/details/gtkyuejuhj.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtadlkghkk.html

[T01] Kotlin：Hello World
来源：http://dali.yonumen.top/Article/details/gtmgnkofpb.html

println("Hello")
来源：http://dali.aizwys.cn/Article/details/gtvkvnkbdm.html

[T02] Kotlin：变量
来源：http://dali.gogol.net.cn/Article/details/gtyawqssqe.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yj202588.top/Article/details/gtzjzbpmxp.html

[T03] Kotlin：字符串模板
来源：http://dali.smart0.xyz/Article/details/gtspjpfomi.html

"值: $b"
来源：http://dali.9152youxi.cn/Article/details/gtuybazady.html

[T04] Kotlin：空安全
来源：http://dali.hywenlv.cn/Article/details/gtajdlnpcf.html

val n: String? = null;  n?.length
来源：http://dali.0kj1m.cn/Article/details/gtvbynllww.html

[T05] Kotlin：when 表达式
来源：http://dali.andypj.xyz/Article/details/gtvgmmnogp.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.shzxlz.cn/Article/details/gtelsghrao.html

[T06] Kotlin：集合映射
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtutttjptn.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.c1oappe.top/Article/details/gtfmdwkxrd.html

[T07] Kotlin：集合过滤
来源：http://dali.zhixingplan.top/Article/details/gtqkbwdjsw.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.tianlin.xyz/Article/details/gtyqearwqb.html

[T08] Kotlin：数据类
来源：http://dali.meibo888.top/Article/details/gtuethmfyy.html

data class User(val name: String, val age: Int)
来源：http://dali.wangdashe.top/Article/details/gtljarvnkr.html

[T09] Kotlin：扩展函数
来源：http://dali.birdmap.top/Article/details/gtuhrmusch.html

fun String.exclaim() = this + "!"
来源：http://dali.yuanzhike.top/Article/details/gtqmanuulp.html

[T10] Kotlin：默认参数
来源：http://dali.meibo888.top/Article/details/gtnhmwozci.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.shuidangran.top/Article/details/gtlqmmzhys.html

[T11] Kotlin：协程
来源：http://dali.guannengcc.top/Article/details/gtqegtheip.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zhongyouzk.top/Article/details/gtyqijywry.html

[T12] Kotlin：解构声明
来源：http://dali.ydzc1.top/Article/details/gtnqqqiesj.html

val (a, b) = Pair(1, 2)
来源：http://dali.zhongyouzk.top/Article/details/gtqiwzyacj.html

[T13] Kotlin：只读 Map
来源：http://dali.shuidangran.top/Article/details/gtzsmajtea.html

val m = mapOf("a" to 1)
来源：http://dali.shuidangran.top/Article/details/gtwhrfmebk.html

[T14] Kotlin：循环
来源：http://dali.sweek.top/Article/details/gtspbovobe.html

for (i in 1..10) println(i)
来源：http://dali.jyoumei.cn/Article/details/gtjbjrydwl.html

[T15] Kotlin：接口
来源：http://dali.ivvv.top/Article/details/gtpcacmooh.html

interface Shape { fun area(): Double }
来源：http://dali.zhongyouzk.top/Article/details/gtmplkumpn.html

[T16] Swift：Hello World
来源：http://dali.cqqwz.cn/Article/details/gtpqbuovka.html

print("Hello")
来源：http://dali.jqgufenzy.top/Article/details/gtoqfdryfm.html

[T17] Swift：变量与常量
来源：http://dali.tanke756.top/Article/details/gtmrtwslag.html

var a = 1;  let b = 2
来源：http://dali.dianchejie.cn/Article/details/gtsjvkofel.html

[T18] Swift：字符串插值
来源：http://dali.shzxlz.cn/Article/details/gtyuffvvhp.html

"值: \(b)"
来源：http://dali.gaohongyu789.top/Article/details/gtncdadizs.html

[T19] Swift：可选绑定
来源：http://dali.yueranfly.top/Article/details/gtiqmqeaqz.html

if let n = opt { print(n) }
来源：http://dali.aibaodan.cn/Article/details/gtyzbtfjdw.html

[T20] Swift：数组操作
来源：http://dali.yj202588.top/Article/details/gtpqogvuho.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.hongshengwenyu.top/Article/details/gtqgycllpv.html

[T21] Swift：遍历
来源：http://dali.zhengqikj.top/Article/details/gtmcrwwgmj.html

for x in a { print(x) }
来源：http://dali.316326.xyz/Article/details/gtfagoofpy.html

[T22] Swift：字典
来源：http://dali.xuanzx.com/Article/details/gtveqnazpu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.guowangkeji.top/Article/details/gtjadcngji.html

[T23] Swift：函数
来源：http://dali.yuanzhike.top/Article/details/gtvcxpjbmb.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.xinyue.icu/Article/details/gtsndkapmw.html

[T24] Swift：闭包
来源：http://dali.jqgfzy.top/Article/details/gtxjuardfc.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.xziqi.cn/Article/details/gtkoqaxecm.html

[T25] Swift：结构体
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxvrmgdvi.html

struct P { var x: Int }
来源：http://dali.xylfe.cn/Article/details/gtiedhrzzh.html

[T26] Swift：类与重写
来源：http://dali.ppjwa.cn/Article/details/gtmocmfsqm.html

class A: Base { override func f() {} }
来源：http://dali.pengpengdd.cyou/Article/details/gticcsakhq.html

[T27] Swift：错误处理
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdizgnvvj.html

do { try f() } catch { print(error) }
来源：http://dali.yanxiufei.cn/Article/details/gtvxraewgx.html

[T28] Swift：枚举
来源：http://dali.ehwqpu.com/Article/details/gtrdssmmfr.html

enum Color { case red, green }
来源：http://dali.ppjwa.cn/Article/details/gtrvozsrdg.html

[T29] Swift：guard 提前返回
来源：http://dali.fzhhl.top/Article/details/gtxqneuqpr.html

guard let x = opt else { return }
来源：http://dali.dashuyun.cn/Article/details/gttkejnnhs.html

[T30] Swift：协议
来源：http://dali.hongshengwenyu.top/Article/details/gtqsngxlss.html

protocol Shape { func area() -> Double }
来源：http://dali.haohaochexian.top/Article/details/gtfbhrrmfo.html

[T31] Lua：Hello World
来源：http://dali.yj202588.top/Article/details/gttblzmshs.html

print("Hello")
来源：http://dali.meibo888.top/Article/details/gtrtuqzpcc.html

[T32] Lua：局部变量
来源：http://dali.jianghu66.top/Article/details/gtrknvqknw.html

local a = 1
来源：http://dali.meibo888.top/Article/details/gtbcqrvvmo.html

[T33] Lua：表（数组）
来源：http://dali.hfpthk.cn/Article/details/gttbdrkoob.html

local t = {1, 2, 3};  t[4] = 4
来源：http://dali.cucudq.cn/Article/details/gtpyzcuhlw.html

[T34] Lua：遍历表
来源：http://dali.snrcjt.cn/Article/details/gtzdkcrfvy.html

for i, v in ipairs(t) do print(i, v) end
来源：http://dali.ivvv.top/Article/details/gtttskkzxk.html

[T35] Lua：字典表
来源：http://dali.quarkkingdee.top/Article/details/gtildbjojv.html

local d = { a = 1 };  d.b = 2
来源：http://dali.jinqigfzy.top/Article/details/gtsuywfkuo.html

[T36] Lua：函数
来源：http://dali.wangshuangyany.cn/Article/details/gtqkhihfoh.html

function add(a, b) return a + b end
来源：http://dali.sysykeji.top/Article/details/gtvbnttrol.html


<!-- 参考信息 -->