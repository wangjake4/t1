代发 wailian999

echo $((1 + 2 * 3))
来源：http://dali.gotoacloud.top/Article/details/gtnmktlwxs.html

[R28] 浮点运算
来源：http://dali.jyoumei.cn/Article/details/gttmhlxzww.html

echo "scale=2; 10/3" | bc
来源：http://dali.chenzaomai.com/Article/details/gtryodqrtb.html

[R29] 定义函数
来源：http://dali.hywenlv.cn/Article/details/gttgbxpagl.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrvzacywd.html

[R30] 函数返回状态码
来源：http://dali.zycfv.cn/Article/details/gtvxrpjwxo.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yonumen.top/Article/details/gtjwccrqiy.html

[R31] 局部变量
来源：http://dali.zhoulong.xyz/Article/details/gtyrstvjxi.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhoulong.xyz/Article/details/gtikuvavnn.html

[R32] 参数个数校验
来源：http://dali.nanxinkj.top/Article/details/gtkhoddhmm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhoulong.xyz/Article/details/gtpmhnxdqy.html

[R33] 捕获错误并提示行号
来源：http://dali.nwbrower.top/Article/details/gtnzkimvpt.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sweek.top/Article/details/gtfmozftfk.html

[R34] 退出时清理
来源：http://dali.cheryme.top/Article/details/gtsocvfsrf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.fengsongda.top/Article/details/gtncabqzpo.html

[R35] 后台执行并等待
来源：http://dali.xuanzx.com/Article/details/gtgsziwjfn.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdojxzvth.html

[R36] 并发执行多个任务
来源：http://dali.havefunace.top/Article/details/gtwginwygy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gzhubu.top/Article/details/gtyobdivym.html

[R37] 把输出赋给变量
来源：http://dali.zhiwuduotai.top/Article/details/gtncsxuzwg.html

files=$(ls -1)
来源：http://dali.ybcxt.top/Article/details/gtrnzdbdfa.html

[R38] 管道串联
来源：http://dali.chenzaomai.com/Article/details/gtgpejwvtq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cucudq.cn/Article/details/gtctqmwcrw.html

[R39] 重定向标准输出与错误
来源：http://dali.jqgufenzy.top/Article/details/gtpgnfzfvu.html

cmd > out.log 2>&1
来源：http://dali.vqdsnc.cn/Article/details/gtxhzfqpwh.html

[R40] 追加写日志
来源：http://dali.tanke756.top/Article/details/gthevytkko.html

echo "log" >> out.log
来源：http://dali.daria6918.cn/Article/details/gtcozhydpg.html

[R41] 丢弃输出
来源：http://dali.nanxinkj.top/Article/details/gtzjncsvbw.html

cmd >/dev/null 2>&1
来源：http://dali.chenzaomai.com/Article/details/gtmtsuivgc.html

[R42] 输入重定向
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlywkrexi.html

wc -l < a.txt
来源：http://dali.svipenyu.cn/Article/details/gttktljwma.html

[R43] 按名字查找文件
来源：http://dali.smart0.xyz/Article/details/gtmtubdyak.html

find . -name "*.log" -type f
来源：http://dali.yj20258.top/Article/details/gtoxukxgfo.html

[R44] 按修改时间查找
来源：http://dali.quarkkingdee.top/Article/details/gthgwvpqlj.html

find . -mtime -7 -type f
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnjxqwzhj.html

[R45] 批量删除
来源：http://dali.wangdashe.top/Article/details/gtfbckudbi.html

find . -name "*.tmp" -delete
来源：http://dali.hysaishi.cn/Article/details/gtjgnaqjqq.html

[R46] 递归替换文件内容
来源：http://dali.fzhhl.top/Article/details/gtzepwvxhn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxwvpvzux.html

[R47] sed 单行替换
来源：http://dali.kuanghao11.cn/Article/details/gtpowmukwk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtvnkipykz.html

[R48] awk 取指定列
来源：http://dali.chenzaomai.com/Article/details/gtcpyjhvkt.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtlcczpjjc.html

[R49] awk 带条件
来源：http://dali.shuidangran.top/Article/details/gtklcyfdui.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cheryme.top/Article/details/gtvzdlmvbf.html

[R50] awk 求和
来源：http://dali.ppjwa.cn/Article/details/gtvbpjfscl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.daria6918.cn/Article/details/gtnexzimyl.html

[R51] 排序去重取前几
来源：http://dali.jyoumei.cn/Article/details/gtqjbtlyiv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.sxryk.cn/Article/details/gthvkzlvti.html

[R52] 统计行数
来源：http://dali.vqdsnc.cn/Article/details/gtmamegoki.html

wc -l a.txt
来源：http://dali.dashuyun.cn/Article/details/gtpgzzijob.html

[R53] 查看文件头与实时尾
来源：http://dali.jqgufenzy.top/Article/details/gtfyyuktyq.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tian-w.cn/Article/details/gtstwhnibe.html

[R54] 比较两个文件
来源：http://dali.nanxuanxn.top/Article/details/gtzcmjcyig.html

diff a.txt b.txt
来源：http://dali.jlsjyb.cn/Article/details/gthubymuru.html

[R55] 压缩与解压
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvfqvizby.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.9152youxi.cn/Article/details/gtvzoqorqv.html

[R56] 远程拷贝
来源：http://dali.xuanzx.com/Article/details/gtkokboksy.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gtzbvzwkix.html

[R57] 远程执行命令
来源：http://dali.jlsjyb.cn/Article/details/gtuvzbtenk.html

ssh user@host 'uptime'
来源：http://dali.jyoumei.cn/Article/details/gteitppegl.html

[R58] 下载文件
来源：http://dali.jqgfzy.top/Article/details/gtbobuuian.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.mhx1999.top/Article/details/gtoqoeunag.html

[R59] 发 POST JSON
来源：http://dali.yuxming.cn/Article/details/gtwgmcxorc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxgoydyae.html

[R60] 只看 HTTP 状态码
来源：http://dali.kuanghao11.cn/Article/details/gtcexhnjfi.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ybcxt.top/Article/details/gtkdcwqjqz.html

[R61] 磁盘占用
来源：http://dali.zhongyouzk.top/Article/details/gtcdzzbbrr.html

df -h;  du -sh *
来源：http://dali.xuanzx.com/Article/details/gtiawcwyhd.html

[R62] 找最占空间的文件
来源：http://dali.cucudq.cn/Article/details/gtyaygpdwn.html

du -ah . | sort -rh | head -10
来源：http://dali.gogol.net.cn/Article/details/gtqbiozqcv.html

[R63] 内存与进程
来源：http://dali.dianchejie.cn/Article/details/gtjfrsrrfz.html

free -h;  ps aux | grep nginx
来源：http://dali.wangshuangyany.cn/Article/details/gtillmtixu.html

[R64] 结束进程
来源：http://dali.meibo888.top/Article/details/gtyqdxsayl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.dianchejie.cn/Article/details/gthhzdobcc.html

[R65] 查看端口占用
来源：http://dali.ehwqpu.com/Article/details/gtiyiziarf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gaohongyu789.top/Article/details/gteumhjhgt.html

[R66] 定时任务
来源：http://dali.shuidangran.top/Article/details/gtlczwkmvt.html

crontab -e;  crontab -l
来源：http://dali.nanxinkj.top/Article/details/gtmkqbmzhy.html

[R67] 生成随机十六进制串
来源：http://dali.daria6918.cn/Article/details/gtzvhbdswg.html

openssl rand -hex 16
来源：http://dali.jqgfzy.top/Article/details/gtjidxcghi.html

[R68] 计算文件校验值
来源：http://dali.dianchejie.cn/Article/details/gtoxbbtmus.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtbtwimose.html

[R69] 生成随机密码
来源：http://dali.redwolf501.top/Article/details/gthayxzqjy.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhoulong.xyz/Article/details/gteqamgypc.html

[R70] 时间戳与互转
来源：http://dali.xinyue.icu/Article/details/gtsyaiiero.html

date +%s;  date -d @1700000000
来源：http://dali.tian-w.cn/Article/details/gtotpvuapk.html

[R71] 日期格式化
来源：http://dali.andypj.xyz/Article/details/gtbincmylk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.shanyushiyangtech.top/Article/details/gteuhvdetw.html

[R72] 等待端口就绪
来源：http://dali.meibo888.top/Article/details/gteleyoeja.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.haohaochexian.top/Article/details/gtpmsuyedj.html

[R73] 分割大日志
来源：http://dali.xinyue.icu/Article/details/gthopvzbjp.html

split -l 1000 big.log part_
来源：http://dali.smart0.xyz/Article/details/gtujvupnqc.html

[R74] 批量重命名
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkngblydw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gotoacloud.top/Article/details/gtnmlacwrb.html

[R75] 导出环境变量
来源：http://dali.jianghu66.top/Article/details/gtnivwvrme.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.andypj.xyz/Article/details/gtdngkkfbi.html

[R76] 使用临时文件
来源：http://dali.sxryk.cn/Article/details/gtisnzvroa.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigufen.top/Article/details/gtmqilfjmv.html

[R77] 读取用户输入
来源：http://dali.yj20258888.top/Article/details/gttexrxbcp.html

read -rp "请输入: " ans
来源：http://dali.vqdsnc.cn/Article/details/gtwvofjrkh.html

[R78] 交互式菜单
来源：http://dali.yanxiufei.cn/Article/details/gteerxosyc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sweek.top/Article/details/gthmqjqfig.html

[R79] 解析命令行选项
来源：http://dali.zhoulong.xyz/Article/details/gteufvzvvf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jqgufenzy.top/Article/details/gtuuisepvs.html

[R80] 查看脚本执行耗时
来源：http://dali.jiagoushi.top/Article/details/gtyugbfhgm.html

time ./run.sh
来源：http://dali.tian-w.cn/Article/details/gttkbxydef.html

================================================================================
来源：http://dali.zycfv.cn/Article/details/gtrtlsbkvr.html

S. C / C++ 专题
来源：http://dali.shzxlz.cn/Article/details/gtdfegzopn.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gtakececiy.html

[S01] C：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtsicctbij.html

#include <stdio.h>
来源：http://dali.mhx1999.top/Article/details/gtrstaeves.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.hfpthk.cn/Article/details/gtkbognkld.html

[S02] C：变量与格式化输出
来源：http://dali.sxryk.cn/Article/details/gtugrdyfxz.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhengqikj.top/Article/details/gtpjeifbsi.html

[S03] C：读入整数
来源：http://dali.pycfn.com/Article/details/gtphyrupka.html

int x; scanf("%d", &x);
来源：http://dali.svipenyu.cn/Article/details/gtaxzfqppk.html

[S04] C：字符串复制
来源：http://dali.jqgfzy.top/Article/details/gtpjhrmrwo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.dashuyun.cn/Article/details/gtsqxgcpxc.html

[S05] C：字符串长度
来源：http://dali.bjfxy.top/Article/details/gtxmcpgbjd.html

strlen(s)
来源：http://dali.hnxiangtu.top/Article/details/gtdijeseog.html

[S06] C：字符串比较
来源：http://dali.xinyue.icu/Article/details/gtmrvixqdb.html

strcmp(a, b) == 0
来源：http://dali.zhoulong.xyz/Article/details/gtncjbyqmm.html

[S07] C：数组遍历求和
来源：http://dali.pengpengdd.cyou/Article/details/gtdmexrlvf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yangfankeji.com/Article/details/gtdtykmruj.html

[S08] C：动态内存分配与释放
来源：http://dali.haohaochexian.top/Article/details/gtxujkcjjp.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hongshengwenyu.top/Article/details/gtpuekhvox.html

[S09] C：结构体定义与初始化
来源：http://dali.yueranfly.top/Article/details/gtjujvckoa.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.kuanghao11.cn/Article/details/gtenyoosth.html

[S10] C：指针与解引用
来源：http://dali.chenlongwang.top/Article/details/gtnaigvbfi.html

int *p = &a;  *p = 5;
来源：http://dali.zhongyouzk.top/Article/details/gtopkyswbp.html

[S11] C：逐行读文件
来源：http://dali.316326.xyz/Article/details/gtwicqhmdf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.kuanghao11.cn/Article/details/gtjuwmchga.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.dianchejie.cn/Article/details/gthnjooaci.html

fclose(f);
来源：http://dali.shangyingyoupin.top/Article/details/gtuacwxvvs.html

[S12] C：写文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbvnqryux.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmrhnofnh.html

[S13] C：宏定义
来源：http://dali.jlsjyb.cn/Article/details/gtsujgakcm.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ivvv.top/Article/details/gtetkzllod.html

[S14] C：枚举
来源：http://dali.aizwys.cn/Article/details/gthbznuswm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.daria6918.cn/Article/details/gtsyyuglbg.html

[S15] C：类型转换
来源：http://dali.c1oappe.top/Article/details/gtqbwpsmal.html

(double) a / b
来源：http://dali.haohaochexian.top/Article/details/gtuxnxggpj.html

[S16] C：位操作置位
来源：http://dali.kuanghao11.cn/Article/details/gtpvzbrzut.html

x |= (1 << 3);
来源：http://dali.jinqigufen.top/Article/details/gtoqghbazd.html

[S17] C：安全拼接字符串
来源：http://dali.hfpthk.cn/Article/details/gtbuwkqkfl.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.redwolf501.top/Article/details/gtakmrjbya.html

[S18] C：命令行参数
来源：http://dali.smart0.xyz/Article/details/gtouvmotgp.html

int main(int argc, char **argv)
来源：http://dali.yueranfly.top/Article/details/gtanlhuiaq.html

[S19] C：快速排序
来源：http://dali.cucudq.cn/Article/details/gteshffpvi.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zdqjudy.top/Article/details/gtsgqkkwdq.html

[S20] C：二分查找
来源：http://dali.fzhhl.top/Article/details/gtwqwdidjg.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.ydzc1.top/Article/details/gthoxymhwy.html

[S21] C：字符类别判断
来源：http://dali.haohaochexian.top/Article/details/gtclxvnhwi.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.xziqi.cn/Article/details/gtccoaaerq.html

[S22] C：字符串转数字
来源：http://dali.hnqzz.top/Article/details/gtxoagtagk.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.feifeiyinyue.top/Article/details/gtcojxkdxd.html

[S23] C：随机数
来源：http://dali.yanxiufei.cn/Article/details/gtzfucyuui.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gtamrrnqfp.html

[S24] C：获取本地时间
来源：http://dali.c1oappe.top/Article/details/gttlgckndk.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cdnleiting.top/Article/details/gtzozprydi.html

[S25] C：内存拷贝
来源：http://dali.yuxming.cn/Article/details/gttwyheser.html

memcpy(dst, src, n);
来源：http://dali.meibo888.top/Article/details/gtheybdvaa.html

[S26] C：内存清零
来源：http://dali.yj202588.top/Article/details/gtznyilpub.html

memset(a, 0, sizeof a);
来源：http://dali.jinqigufen.top/Article/details/gtfmxvegno.html

[S27] C：定义常量
来源：http://dali.jyoumei.cn/Article/details/gtsxdwvpih.html

const double PI = 3.14159;
来源：http://dali.iojbl.cn/Article/details/gtcrkppfip.html

[S28] C：静态变量
来源：http://dali.jinqigfzy.top/Article/details/gthkgbtabq.html

static int counter = 0;
来源：http://dali.aibaodan.cn/Article/details/gteyronuys.html

[S29] C：变参函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgkiqrrjq.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gtykvcevvw.html

[S30] C：头文件保护
来源：http://dali.ppjwa.cn/Article/details/gtthtgmiph.html

#ifndef X_H
来源：http://dali.havefunace.top/Article/details/gtgijwknjf.html

#define X_H
来源：http://dali.wangdashe.top/Article/details/gtfrgdeizu.html

#endif
来源：http://dali.zhaomingkeji.xyz/Article/details/gtumiiszxm.html

[S31] C++：Hello World
来源：http://dali.daria6918.cn/Article/details/gtiwenaxaa.html

#include <iostream>
来源：http://dali.316326.xyz/Article/details/gtxtxosshs.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtipekvxlm.html

[S32] C++：字符串
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbvzlbeqd.html

std::string s = "hi";  s += "!";
来源：http://dali.quarkkingdee.top/Article/details/gthrpiwovc.html

[S33] C++：vector 增删
来源：http://dali.zhiwuduotai.top/Article/details/gtxfgbsqzs.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.fengsongda.top/Article/details/gtobblmewv.html

[S34] C++：遍历 vector
来源：http://dali.xylfe.cn/Article/details/gtjqezjxwp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.dashuyun.cn/Article/details/gtrtobvjbi.html

[S35] C++：map
来源：http://dali.jinghuilouyu.cn/Article/details/gtulwqmzwz.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.mhx1999.top/Article/details/gtfwprcmus.html

[S36] C++：unordered_map
来源：http://dali.cqqwz.cn/Article/details/gttknrqubo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pycfn.com/Article/details/gtmlxhmecz.html

[S37] C++：set
来源：http://dali.cqqwz.cn/Article/details/gtbxrhrajc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gotoacloud.top/Article/details/gtsqpvynsl.html

[S38] C++：排序
来源：http://dali.c1oappe.top/Article/details/gtdymnmutk.html

std::sort(v.begin(), v.end());
来源：http://dali.chenjidiqi.icu/Article/details/gtxcfyntim.html

[S39] C++：自定义比较器排序
来源：http://dali.jiagoushi.top/Article/details/gttxkluygg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.wangshuangyany.cn/Article/details/gtcqigyfzt.html

[S40] C++：查找元素
来源：http://dali.zhijiandao.cn/Article/details/gtlquebxzu.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.haohaochexian.top/Article/details/gtabnlesis.html

[S41] C++：类与构造函数
来源：http://dali.zhixingplan.top/Article/details/gtasoabgdu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.ydzc1.top/Article/details/gtagahtabh.html

[S42] C++：继承与虚函数
来源：http://dali.jqgufenzy.top/Article/details/gtqkygdcfe.html

class B : public Base { public: void f() override {} };
来源：http://dali.jyoumei.cn/Article/details/gtxawhtzck.html

[S43] C++：智能指针
来源：http://dali.svipenyu.cn/Article/details/gtyejagljc.html

auto p = std::make_unique<int>(5);
来源：http://dali.tian-w.cn/Article/details/gtjhnowkov.html

[S44] C++：引用传参
来源：http://dali.yueranfly.top/Article/details/gtnpebjzdi.html

void inc(int &x) { ++x; }
来源：http://dali.jqgfzy.top/Article/details/gtipbxzcfa.html

[S45] C++：lambda
来源：http://dali.xuetiantiany.cn/Article/details/gthcpuvlpw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.bjfxy.top/Article/details/gtyzaaoign.html

[S46] C++：函数模板
来源：http://dali.smart0.xyz/Article/details/gtcxkmxmaj.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.hammf.cn/Article/details/gtjvaiohxy.html

[S47] C++：结构化绑定遍历
来源：http://dali.shuidangran.top/Article/details/gtfiucxhrg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.nwbrower.top/Article/details/gtyjhvepzi.html

[S48] C++：逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gtnvgkyoln.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zycfv.cn/Article/details/gtthakqgen.html

while (std::getline(in, line)) { }
来源：http://dali.tanke756.top/Article/details/gtiobsoipm.html

[S49] C++：写文件
来源：http://dali.guowangkeji.top/Article/details/gtjmlgufam.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hongshengwenyu.top/Article/details/gtijhfkbar.html

[S50] C++：格式化数字
来源：http://dali.yongpay.top/Article/details/gtevetmkuz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gtzfmamnra.html

[S51] C++：显式类型转换
来源：http://dali.ppjwa.cn/Article/details/gtbpiacvlt.html

static_cast<double>(a) / b
来源：http://dali.guowangkeji.top/Article/details/gthjwviaed.html

[S52] C++：const 与 noexcept
来源：http://dali.pycfn.com/Article/details/gtckybfihb.html

int size() const noexcept { return n_; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwraqcptb.html

[S53] C++：移动语义
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbszgecuf.html

std::vector<int> w = std::move(v);
来源：http://dali.aizwys.cn/Article/details/gtluuekbna.html

[S54] C++：异常处理
来源：http://dali.jinqigufen.top/Article/details/gtkkxvlxjj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shzxlz.cn/Article/details/gtcqvnzxpd.html

[S55] C++：结构化绑定
来源：http://dali.gaohongyu789.top/Article/details/gtwswalqdf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.9152youxi.cn/Article/details/gtzqtmdkdh.html

[S56] C++：optional
来源：http://dali.kuanghao11.cn/Article/details/gtuqcbbytr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoigchbqo.html

[S57] C++：编译期常量
来源：http://dali.9152youxi.cn/Article/details/gtsooxrxhl.html

constexpr int N = 10;
来源：http://dali.cashguo.top/Article/details/gtaymoncde.html

[S58] C++：命名空间
来源：http://dali.yj20258.top/Article/details/gtphvbhpak.html

namespace ns { int f() { return 1; } }
来源：http://dali.hnxiangtu.top/Article/details/gtuyeaorgh.html

[S59] C++：静态断言
来源：http://dali.shuidangran.top/Article/details/gtjrichpnz.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.iojbl.cn/Article/details/gtmforbmds.html

[S60] C++：遍历并删除元素
来源：http://dali.daxiang520.top/Article/details/gtdbiskngy.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cashguo.top/Article/details/gtxkjoknpr.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtrvgacdtt.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.shangyingyoupin.top/Article/details/gterkeotbm.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gtdedylcbl.html

[T01] Kotlin：Hello World
来源：http://dali.iojbl.cn/Article/details/gtqlxchhtu.html

println("Hello")
来源：http://dali.hnxiangtu.top/Article/details/gtlzutpjaa.html

[T02] Kotlin：变量
来源：http://dali.fzhhl.top/Article/details/gtamgxasnb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yangfankeji.com/Article/details/gtwytylojz.html

[T03] Kotlin：字符串模板
来源：http://dali.guowangkeji.top/Article/details/gtscsuwybp.html

"值: $b"
来源：http://dali.ehwqpu.com/Article/details/gtqlmnmqtb.html

[T04] Kotlin：空安全
来源：http://dali.hfpthk.cn/Article/details/gtcebizjvm.html

val n: String? = null;  n?.length
来源：http://dali.shzxlz.cn/Article/details/gtexugmeta.html

[T05] Kotlin：when 表达式
来源：http://dali.pycfn.com/Article/details/gtrqsxignq.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.tian-w.cn/Article/details/gtingdyxqa.html

[T06] Kotlin：集合映射
来源：http://dali.sysykeji.top/Article/details/gtvjxlwwik.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hysaishi.cn/Article/details/gtoceirvdx.html

[T07] Kotlin：集合过滤
来源：http://dali.bjfxy.top/Article/details/gtwhpgvbpj.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sysykeji.top/Article/details/gtksdttgyd.html

[T08] Kotlin：数据类
来源：http://dali.gotoacloud.top/Article/details/gtjddknoek.html

data class User(val name: String, val age: Int)
来源：http://dali.tian-w.cn/Article/details/gtkztivhpd.html

[T09] Kotlin：扩展函数
来源：http://dali.zhoulong.xyz/Article/details/gthiusaxyd.html

fun String.exclaim() = this + "!"
来源：http://dali.gzhubu.top/Article/details/gtusikkfni.html

[T10] Kotlin：默认参数
来源：http://dali.iojbl.cn/Article/details/gtmpwayxzf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.gotoacloud.top/Article/details/gtbynzksvw.html

[T11] Kotlin：协程
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaupsojtc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.bjfxy.top/Article/details/gtdhsbslvs.html

[T12] Kotlin：解构声明
来源：http://dali.meibo888.top/Article/details/gtgaabuodt.html

val (a, b) = Pair(1, 2)
来源：http://dali.xziqi.cn/Article/details/gtavbglplx.html

[T13] Kotlin：只读 Map
来源：http://dali.xuanzx.com/Article/details/gtcmamxzno.html

val m = mapOf("a" to 1)
来源：http://dali.hysaishi.cn/Article/details/gtnutplzma.html

[T14] Kotlin：循环
来源：http://dali.andypj.xyz/Article/details/gtwritifdb.html

for (i in 1..10) println(i)
来源：http://dali.wangdashe.top/Article/details/gtcudlcbtd.html

[T15] Kotlin：接口
来源：http://dali.smart0.xyz/Article/details/gtibkoimtc.html

interface Shape { fun area(): Double }
来源：http://dali.yuxming.cn/Article/details/gtvroagqow.html

[T16] Swift：Hello World
来源：http://dali.iojbl.cn/Article/details/gtejwhkiqx.html

print("Hello")
来源：http://dali.xylfe.cn/Article/details/gtjbcpskum.html

[T17] Swift：变量与常量
来源：http://dali.pengpengdd.cyou/Article/details/gtakjkbdgo.html

var a = 1;  let b = 2
来源：http://dali.ybcxt.top/Article/details/gtxsqzhkqv.html

[T18] Swift：字符串插值
来源：http://dali.jqgfzy.top/Article/details/gthpywbkgl.html

"值: \(b)"
来源：http://dali.zhongyouzk.top/Article/details/gtnsfnusgo.html

[T19] Swift：可选绑定
来源：http://dali.zhiwuduotai.top/Article/details/gtccivwgyb.html

if let n = opt { print(n) }
来源：http://dali.jiagoushi.top/Article/details/gtklbnwjwe.html

[T20] Swift：数组操作
来源：http://dali.tian-w.cn/Article/details/gtcwhjeqkv.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.fengsongda.top/Article/details/gtcwosdbyx.html

[T21] Swift：遍历
来源：http://dali.vqdsnc.cn/Article/details/gtyhwssiji.html

for x in a { print(x) }
来源：http://dali.tianlin.xyz/Article/details/gtpsxjqtdf.html

[T22] Swift：字典
来源：http://dali.cdnleiting.top/Article/details/gtaqxmewfn.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zdqjudy.top/Article/details/gtnmayaaxo.html

[T23] Swift：函数
来源：http://dali.yonumen.top/Article/details/gtdlwpktct.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.svipenyu.cn/Article/details/gteitsyumc.html

[T24] Swift：闭包
来源：http://dali.yuxming.cn/Article/details/gttfimmwpu.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.snrcjt.cn/Article/details/gtlxjzrujp.html

[T25] Swift：结构体
来源：http://dali.vqdsnc.cn/Article/details/gtgofyajcf.html

struct P { var x: Int }
来源：http://dali.jinqigufen.top/Article/details/gtelycricc.html

[T26] Swift：类与重写
来源：http://dali.cheryme.top/Article/details/gtlgtihksn.html

class A: Base { override func f() {} }
来源：http://dali.nwbrower.top/Article/details/gtctyxvasq.html

[T27] Swift：错误处理
来源：http://dali.hongshengwenyu.top/Article/details/gtehbuanxl.html

do { try f() } catch { print(error) }
来源：http://dali.cheryme.top/Article/details/gtpcaidgwr.html

[T28] Swift：枚举
来源：http://dali.zhoulong.xyz/Article/details/gtvdaudwka.html

enum Color { case red, green }
来源：http://dali.havefunace.top/Article/details/gtjdgljdmn.html

[T29] Swift：guard 提前返回
来源：http://dali.yvedp.cn/Article/details/gtsayvhbqf.html

guard let x = opt else { return }
来源：http://dali.havefunace.top/Article/details/gtzmpyfjsa.html

[T30] Swift：协议
来源：http://dali.316326.xyz/Article/details/gtqrytczqr.html

protocol Shape { func area() -> Double }
来源：http://dali.tian-w.cn/Article/details/gtuknygpqs.html


<!-- 参考信息 -->