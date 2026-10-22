代发 wailian999

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yonumen.top/Article/details/gtwzbklhdv.html

[R30] 函数返回状态码
来源：http://dali.yanxiufei.cn/Article/details/gtmbhfwjoe.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jlsjyb.cn/Article/details/gtycbbsxil.html

[R31] 局部变量
来源：http://dali.fengsongda.top/Article/details/gtlalgoegx.html

f() { local x=1; echo "$x"; }
来源：http://dali.nanxinkj.top/Article/details/gthqhcpgzy.html

[R32] 参数个数校验
来源：http://dali.havefunace.top/Article/details/gtwzdbnwtp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.svipenyu.cn/Article/details/gtpeswjtxu.html

[R33] 捕获错误并提示行号
来源：http://dali.yuxming.cn/Article/details/gtsfmtphbj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhiwuduotai.top/Article/details/gtexpnsbsn.html

[R34] 退出时清理
来源：http://dali.dashuyun.cn/Article/details/gtlsxdfmjs.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgfzy.top/Article/details/gtkpukbthn.html

[R35] 后台执行并等待
来源：http://dali.yj20258888.top/Article/details/gtvjarglbm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gzhubu.top/Article/details/gtuwgvpxpy.html

[R36] 并发执行多个任务
来源：http://dali.c1oappe.top/Article/details/gttxhrezaa.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jqgfzy.top/Article/details/gtmcpqmsvy.html

[R37] 把输出赋给变量
来源：http://dali.meibo888.top/Article/details/gtufysaqgf.html

files=$(ls -1)
来源：http://dali.cashguo.top/Article/details/gttihrogvx.html

[R38] 管道串联
来源：http://dali.smart0.xyz/Article/details/gtvlygexvs.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gaohongyu789.top/Article/details/gtjccdafmt.html

[R39] 重定向标准输出与错误
来源：http://dali.hysaishi.cn/Article/details/gtsggbowql.html

cmd > out.log 2>&1
来源：http://dali.cqqwz.cn/Article/details/gtdpvpadou.html

[R40] 追加写日志
来源：http://dali.yongpay.top/Article/details/gtzefihjfx.html

echo "log" >> out.log
来源：http://dali.xuetiantiany.cn/Article/details/gteomohrms.html

[R41] 丢弃输出
来源：http://dali.fzhhl.top/Article/details/gtiyqefhtt.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gtnlxmwery.html

[R42] 输入重定向
来源：http://dali.smart0.xyz/Article/details/gticjomfqx.html

wc -l < a.txt
来源：http://dali.xinyue.icu/Article/details/gtehfvvino.html

[R43] 按名字查找文件
来源：http://dali.aibaodan.cn/Article/details/gtpjweumvx.html

find . -name "*.log" -type f
来源：http://dali.hnqzz.top/Article/details/gtfucqebwd.html

[R44] 按修改时间查找
来源：http://dali.andypj.xyz/Article/details/gttnvcsnos.html

find . -mtime -7 -type f
来源：http://dali.shzxlz.cn/Article/details/gtniyowoar.html

[R45] 批量删除
来源：http://dali.jqgufenzy.top/Article/details/gtescxteke.html

find . -name "*.tmp" -delete
来源：http://dali.feifeiyinyue.top/Article/details/gtkkcfejgn.html

[R46] 递归替换文件内容
来源：http://dali.kuanghao11.cn/Article/details/gtpyxqemjs.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.gaohongyu789.top/Article/details/gtyywbhsbm.html

[R47] sed 单行替换
来源：http://dali.zhengqikj.top/Article/details/gthdcilqan.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shuidangran.top/Article/details/gtrmxijwts.html

[R48] awk 取指定列
来源：http://dali.quarkkingdee.top/Article/details/gtpiqsfdkt.html

awk '{print $1, $3}' a.txt
来源：http://dali.aizwys.cn/Article/details/gtywcwcars.html

[R49] awk 带条件
来源：http://dali.shanyushiyangtech.top/Article/details/gtdpuynvqt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yueranfly.top/Article/details/gtopgcjhwk.html

[R50] awk 求和
来源：http://dali.chenjidiqi.icu/Article/details/gtcxuemzrx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.daria6918.cn/Article/details/gtlavqliru.html

[R51] 排序去重取前几
来源：http://dali.chenlongwang.top/Article/details/gtbljcamjk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.nanxuanxn.top/Article/details/gtaempoqet.html

[R52] 统计行数
来源：http://dali.feifeiyinyue.top/Article/details/gtewbnhbtn.html

wc -l a.txt
来源：http://dali.aibaodan.cn/Article/details/gtvyqrcfjv.html

[R53] 查看文件头与实时尾
来源：http://dali.yueranfly.top/Article/details/gtlkvpttsx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ydzc1.top/Article/details/gtdcowueta.html

[R54] 比较两个文件
来源：http://dali.zhengqikj.top/Article/details/gtueziftql.html

diff a.txt b.txt
来源：http://dali.ehwqpu.com/Article/details/gtqgxewoqm.html

[R55] 压缩与解压
来源：http://dali.ehwqpu.com/Article/details/gtbwvpripj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yuxming.cn/Article/details/gtmrxprrgr.html

[R56] 远程拷贝
来源：http://dali.meibo888.top/Article/details/gtncmwtils.html

scp file user@host:/path/
来源：http://dali.ydzc1.top/Article/details/gtkxwkavrm.html

[R57] 远程执行命令
来源：http://dali.fengsongda.top/Article/details/gtauzmkams.html

ssh user@host 'uptime'
来源：http://dali.aizwys.cn/Article/details/gtxpiobnni.html

[R58] 下载文件
来源：http://dali.yongpay.top/Article/details/gtvcwrbodl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.guowangkeji.top/Article/details/gtxrrtebhh.html

[R59] 发 POST JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthjdiamwp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gzhubu.top/Article/details/gtvzhsostq.html

[R60] 只看 HTTP 状态码
来源：http://dali.jiagoushi.top/Article/details/gtqoonfdue.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hnxiangtu.top/Article/details/gttechsabq.html

[R61] 磁盘占用
来源：http://dali.fzhhl.top/Article/details/gtoxfrnlri.html

df -h;  du -sh *
来源：http://dali.gotoacloud.top/Article/details/gtkuukgynz.html

[R62] 找最占空间的文件
来源：http://dali.tian-w.cn/Article/details/gtuqpesfey.html

du -ah . | sort -rh | head -10
来源：http://dali.ivvv.top/Article/details/gthkhwazct.html

[R63] 内存与进程
来源：http://dali.shangyingyoupin.top/Article/details/gtxmortjbu.html

free -h;  ps aux | grep nginx
来源：http://dali.chenjidiqi.icu/Article/details/gtezwqzoup.html

[R64] 结束进程
来源：http://dali.wangshuangyany.cn/Article/details/gtocdakivh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.tian-w.cn/Article/details/gtsezcetyz.html

[R65] 查看端口占用
来源：http://dali.shzxlz.cn/Article/details/gttsmonmnw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.quarkkingdee.top/Article/details/gtyggboysp.html

[R66] 定时任务
来源：http://dali.guowangkeji.top/Article/details/gtinjkkbed.html

crontab -e;  crontab -l
来源：http://dali.sufxvd.cn/Article/details/gtiadbajbo.html

[R67] 生成随机十六进制串
来源：http://dali.xziqi.cn/Article/details/gttivpypxg.html

openssl rand -hex 16
来源：http://dali.ybcxt.top/Article/details/gtwanaiird.html

[R68] 计算文件校验值
来源：http://dali.xylfe.cn/Article/details/gtrileptwb.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shuidangran.top/Article/details/gtloidtivo.html

[R69] 生成随机密码
来源：http://dali.ehwqpu.com/Article/details/gtcpmnxydg.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhixingplan.top/Article/details/gthiwzkwjs.html

[R70] 时间戳与互转
来源：http://dali.yj20258888.top/Article/details/gtwaikzqjd.html

date +%s;  date -d @1700000000
来源：http://dali.mhx1999.top/Article/details/gtamsgowki.html

[R71] 日期格式化
来源：http://dali.ybcxt.top/Article/details/gternzukou.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hywenlv.cn/Article/details/gtgfvcbitf.html

[R72] 等待端口就绪
来源：http://dali.gogol.net.cn/Article/details/gtqmrqeabp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gotoacloud.top/Article/details/gtugmzbluq.html

[R73] 分割大日志
来源：http://dali.fzhhl.top/Article/details/gtvjjiwjeh.html

split -l 1000 big.log part_
来源：http://dali.hammf.cn/Article/details/gtrlvgwzmp.html

[R74] 批量重命名
来源：http://dali.iojbl.cn/Article/details/gththlimve.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhoulong.xyz/Article/details/gtxlvxvvnh.html

[R75] 导出环境变量
来源：http://dali.316326.xyz/Article/details/gtrpkoakmt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.vqdsnc.cn/Article/details/gtbgsfbqsx.html

[R76] 使用临时文件
来源：http://dali.pycfn.com/Article/details/gtejtlseks.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yanxiufei.cn/Article/details/gtvogvkell.html

[R77] 读取用户输入
来源：http://dali.xuanzx.com/Article/details/gtgjvpmmwo.html

read -rp "请输入: " ans
来源：http://dali.guannengcc.top/Article/details/gtnawuzdxj.html

[R78] 交互式菜单
来源：http://dali.feifeiyinyue.top/Article/details/gthormzyjp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ivvv.top/Article/details/gtfrufhedy.html

[R79] 解析命令行选项
来源：http://dali.chenlongwang.top/Article/details/gtwhfalsxd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.xinyue.icu/Article/details/gtoltsdsyc.html

[R80] 查看脚本执行耗时
来源：http://dali.zhixingplan.top/Article/details/gtdxadqdje.html

time ./run.sh
来源：http://dali.ydzc1.top/Article/details/gtqsloqzgj.html

================================================================================
来源：http://dali.9152youxi.cn/Article/details/gtphhefsti.html

S. C / C++ 专题
来源：http://dali.cdnleiting.top/Article/details/gtiflqfsis.html

================================================================================
来源：http://dali.zhengqikj.top/Article/details/gtodzrlgxg.html

[S01] C：Hello World
来源：http://dali.jiagoushi.top/Article/details/gtrlwcpujx.html

#include <stdio.h>
来源：http://dali.dashuyun.cn/Article/details/gturfivkiq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xylfe.cn/Article/details/gtfbdxsupk.html

[S02] C：变量与格式化输出
来源：http://dali.zdqjudy.top/Article/details/gtgvejxktl.html

int a = 10; printf("%d\n", a);
来源：http://dali.jqgfzy.top/Article/details/gtnvnwikge.html

[S03] C：读入整数
来源：http://dali.wangdashe.top/Article/details/gttwgptbfa.html

int x; scanf("%d", &x);
来源：http://dali.daxiang520.top/Article/details/gtbiwnkqwo.html

[S04] C：字符串复制
来源：http://dali.yongpay.top/Article/details/gtlekhhduh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.nanxinkj.top/Article/details/gttfzpoixy.html

[S05] C：字符串长度
来源：http://dali.cdnleiting.top/Article/details/gtkckrlbuh.html

strlen(s)
来源：http://dali.iojbl.cn/Article/details/gtpznvxshv.html

[S06] C：字符串比较
来源：http://dali.ivvv.top/Article/details/gtwschzwbc.html

strcmp(a, b) == 0
来源：http://dali.birdmap.top/Article/details/gtngqvmbov.html

[S07] C：数组遍历求和
来源：http://dali.hfpthk.cn/Article/details/gtwpinnqov.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhixingplan.top/Article/details/gtapnphptt.html

[S08] C：动态内存分配与释放
来源：http://dali.aizwys.cn/Article/details/gtcfsczhbi.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hnxiangtu.top/Article/details/gtsrmtratl.html

[S09] C：结构体定义与初始化
来源：http://dali.yuanzhike.top/Article/details/gtzpqvcwxm.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yueranfly.top/Article/details/gtgpdhicvz.html

[S10] C：指针与解引用
来源：http://dali.jinqigfzy.top/Article/details/gtxkzttptl.html

int *p = &a;  *p = 5;
来源：http://dali.xylfe.cn/Article/details/gttkwibjgd.html

[S11] C：逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gtrougwbxm.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.0kj1m.cn/Article/details/gtvwbilzlt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gotoacloud.top/Article/details/gtrywxksqr.html

fclose(f);
来源：http://dali.jinqigfzy.top/Article/details/gtzixjgbjl.html

[S12] C：写文件
来源：http://dali.guannengcc.top/Article/details/gtxpwurowb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinyuanbaomall.cn/Article/details/gthsizqfpu.html

[S13] C：宏定义
来源：http://dali.haohaochexian.top/Article/details/gtrtgezeqk.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.nwbrower.top/Article/details/gturfgajlg.html

[S14] C：枚举
来源：http://dali.tian-w.cn/Article/details/gtjrmqouro.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hysaishi.cn/Article/details/gtpznltmke.html

[S15] C：类型转换
来源：http://dali.yangfankeji.com/Article/details/gtmdqfycsx.html

(double) a / b
来源：http://dali.hysaishi.cn/Article/details/gtqrlxbafa.html

[S16] C：位操作置位
来源：http://dali.fengsongda.top/Article/details/gtriqobriz.html

x |= (1 << 3);
来源：http://dali.gogol.net.cn/Article/details/gtbukttpjr.html

[S17] C：安全拼接字符串
来源：http://dali.nwbrower.top/Article/details/gtpahdrpry.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.smart0.xyz/Article/details/gttgvwxzok.html

[S18] C：命令行参数
来源：http://dali.yj20258.top/Article/details/gtafpcludt.html

int main(int argc, char **argv)
来源：http://dali.316326.xyz/Article/details/gtizayress.html

[S19] C：快速排序
来源：http://dali.sufxvd.cn/Article/details/gtdxjwuzfc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.yonumen.top/Article/details/gttaplktsy.html

[S20] C：二分查找
来源：http://dali.sxryk.cn/Article/details/gtjeagkfyw.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.hywenlv.cn/Article/details/gthuzfolzi.html

[S21] C：字符类别判断
来源：http://dali.andypj.xyz/Article/details/gtypnnrvdp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hammf.cn/Article/details/gtdgsguqeq.html

[S22] C：字符串转数字
来源：http://dali.zhiwuduotai.top/Article/details/gtvfhqlvii.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.snrcjt.cn/Article/details/gtckcgdlji.html

[S23] C：随机数
来源：http://dali.feifeiyinyue.top/Article/details/gtaruyqbfl.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.aizwys.cn/Article/details/gtbxjqqezf.html

[S24] C：获取本地时间
来源：http://dali.pengpengdd.cyou/Article/details/gthtujmoqe.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shanyushiyangtech.top/Article/details/gtlkhdrsqf.html

[S25] C：内存拷贝
来源：http://dali.svipenyu.cn/Article/details/gtlxilwszk.html

memcpy(dst, src, n);
来源：http://dali.shzxlz.cn/Article/details/gtlububmae.html

[S26] C：内存清零
来源：http://dali.yj20258.top/Article/details/gtgrokwlcb.html

memset(a, 0, sizeof a);
来源：http://dali.andypj.xyz/Article/details/gtuvxnaikm.html

[S27] C：定义常量
来源：http://dali.chenlongwang.top/Article/details/gtghjhwrxn.html

const double PI = 3.14159;
来源：http://dali.birdmap.top/Article/details/gttkmkbejw.html

[S28] C：静态变量
来源：http://dali.jinqigufen.top/Article/details/gttibncfin.html

static int counter = 0;
来源：http://dali.iojbl.cn/Article/details/gtduiycllt.html

[S29] C：变参函数
来源：http://dali.smart0.xyz/Article/details/gtjooyyqrr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.birdmap.top/Article/details/gtibjhjjek.html

[S30] C：头文件保护
来源：http://dali.jqgufenzy.top/Article/details/gtdospvurn.html

#ifndef X_H
来源：http://dali.meibo888.top/Article/details/gtpoagqvlz.html

#define X_H
来源：http://dali.sweek.top/Article/details/gtrrzqugvd.html

#endif
来源：http://dali.c1oappe.top/Article/details/gtqmkjgkan.html

[S31] C++：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtcndmxgje.html

#include <iostream>
来源：http://dali.jqgfzy.top/Article/details/gtpdnzmkun.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zdqjudy.top/Article/details/gtmnncfcvc.html

[S32] C++：字符串
来源：http://dali.yj20258.top/Article/details/gtwftuhepz.html

std::string s = "hi";  s += "!";
来源：http://dali.9152youxi.cn/Article/details/gtuyysemwf.html

[S33] C++：vector 增删
来源：http://dali.smart0.xyz/Article/details/gtosnflcrz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.guowangkeji.top/Article/details/gtgeonvjgr.html

[S34] C++：遍历 vector
来源：http://dali.pengpengdd.cyou/Article/details/gtqleajphm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.hnqzz.top/Article/details/gtvohgplxe.html

[S35] C++：map
来源：http://dali.pycfn.com/Article/details/gtxvvtppcl.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.kuanghao11.cn/Article/details/gttqhljebr.html

[S36] C++：unordered_map
来源：http://dali.zdqjudy.top/Article/details/gtrifbwdoy.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zdqjudy.top/Article/details/gtyxnhfglb.html

[S37] C++：set
来源：http://dali.birdmap.top/Article/details/gtuxiyseni.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.bjfxy.top/Article/details/gtbqshernu.html

[S38] C++：排序
来源：http://dali.hnqzz.top/Article/details/gtocbwlbgw.html

std::sort(v.begin(), v.end());
来源：http://dali.pengpengdd.cyou/Article/details/gtirxpalqo.html

[S39] C++：自定义比较器排序
来源：http://dali.kuanghao11.cn/Article/details/gtilamejdz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sxryk.cn/Article/details/gthwhcbnax.html

[S40] C++：查找元素
来源：http://dali.cheryme.top/Article/details/gtvnacrfgl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.bjfxy.top/Article/details/gtxjytlhan.html

[S41] C++：类与构造函数
来源：http://dali.nwbrower.top/Article/details/gtzcvmcsoz.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shanyushiyangtech.top/Article/details/gtavefcesq.html

[S42] C++：继承与虚函数
来源：http://dali.quarkkingdee.top/Article/details/gtazmsykku.html

class B : public Base { public: void f() override {} };
来源：http://dali.birdmap.top/Article/details/gtqufphxev.html

[S43] C++：智能指针
来源：http://dali.meibo888.top/Article/details/gtivzygtgd.html

auto p = std::make_unique<int>(5);
来源：http://dali.chenjidiqi.icu/Article/details/gtwfdzwroy.html

[S44] C++：引用传参
来源：http://dali.yangfankeji.com/Article/details/gthesmxwfh.html

void inc(int &x) { ++x; }
来源：http://dali.shangyingyoupin.top/Article/details/gtyshekxbe.html

[S45] C++：lambda
来源：http://dali.tianlin.xyz/Article/details/gtpyljelpm.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.yj20258888.top/Article/details/gtmcakifum.html

[S46] C++：函数模板
来源：http://dali.birdmap.top/Article/details/gtqvjvjwat.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.mhx1999.top/Article/details/gtsfteglys.html

[S47] C++：结构化绑定遍历
来源：http://dali.bjfxy.top/Article/details/gtiihcghlp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shuidangran.top/Article/details/gtvbfzsngd.html

[S48] C++：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gtgarxrcmq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jqgufenzy.top/Article/details/gtykzkqvkb.html

while (std::getline(in, line)) { }
来源：http://dali.chenlongwang.top/Article/details/gtxbfbqmmb.html

[S49] C++：写文件
来源：http://dali.quarkkingdee.top/Article/details/gtjaqayxbt.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hysaishi.cn/Article/details/gtvzkjvalv.html

[S50] C++：格式化数字
来源：http://dali.zhaomingkeji.xyz/Article/details/gtikxyzaay.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gtxdayfkgn.html

[S51] C++：显式类型转换
来源：http://dali.aizwys.cn/Article/details/gtkjxulsgp.html

static_cast<double>(a) / b
来源：http://dali.jinqigufen.top/Article/details/gtowjhclad.html

[S52] C++：const 与 noexcept
来源：http://dali.gogol.net.cn/Article/details/gtfhecueyn.html

int size() const noexcept { return n_; }
来源：http://dali.pengpengdd.cyou/Article/details/gtbllahtdz.html

[S53] C++：移动语义
来源：http://dali.nanxuanxn.top/Article/details/gttmtagdtk.html

std::vector<int> w = std::move(v);
来源：http://dali.cqqwz.cn/Article/details/gtqxzskwhm.html

[S54] C++：异常处理
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfnerdiyr.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.pengpengdd.cyou/Article/details/gtjwpjcxxz.html

[S55] C++：结构化绑定
来源：http://dali.guannengcc.top/Article/details/gtbnylnxte.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hongshengwenyu.top/Article/details/gtplklrxec.html

[S56] C++：optional
来源：http://dali.birdmap.top/Article/details/gtdygbsria.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.iojbl.cn/Article/details/gttddlmhtw.html

[S57] C++：编译期常量
来源：http://dali.aizwys.cn/Article/details/gtgnmvmqun.html

constexpr int N = 10;
来源：http://dali.chenzaomai.com/Article/details/gtblxthyio.html

[S58] C++：命名空间
来源：http://dali.ehwqpu.com/Article/details/gtsgpiidhf.html

namespace ns { int f() { return 1; } }
来源：http://dali.wangdashe.top/Article/details/gtebwbrvgi.html

[S59] C++：静态断言
来源：http://dali.hywenlv.cn/Article/details/gtxagqzvjt.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zycfv.cn/Article/details/gtnxneishj.html

[S60] C++：遍历并删除元素
来源：http://dali.cheryme.top/Article/details/gtejhdijwc.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.chenlongwang.top/Article/details/gtvusgaqlf.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtjtkltkii.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ivvv.top/Article/details/gtyltvgzfi.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtbclbzhbn.html

[T01] Kotlin：Hello World
来源：http://dali.yuanzhike.top/Article/details/gtsolbmasc.html

println("Hello")
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmyldnwvt.html

[T02] Kotlin：变量
来源：http://dali.quarkkingdee.top/Article/details/gtgwwlvwdc.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.fzhhl.top/Article/details/gtjuhioimo.html

[T03] Kotlin：字符串模板
来源：http://dali.sweek.top/Article/details/gtkcfyuksd.html

"值: $b"
来源：http://dali.zhijiandao.cn/Article/details/gtflngjcek.html

[T04] Kotlin：空安全
来源：http://dali.shzxlz.cn/Article/details/gttxxfmkli.html

val n: String? = null;  n?.length
来源：http://dali.snrcjt.cn/Article/details/gtccvtouof.html

[T05] Kotlin：when 表达式
来源：http://dali.zhiwuduotai.top/Article/details/gtoprnualw.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hnxiangtu.top/Article/details/gtaibvdzwy.html

[T06] Kotlin：集合映射
来源：http://dali.fengsongda.top/Article/details/gtwcyxowdx.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gaohongyu789.top/Article/details/gtqmocbbmr.html

[T07] Kotlin：集合过滤
来源：http://dali.pengpengdd.cyou/Article/details/gtisrwpqcx.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.ybcxt.top/Article/details/gtbaorpacq.html

[T08] Kotlin：数据类
来源：http://dali.ppjwa.cn/Article/details/gtrwgtfmyz.html

data class User(val name: String, val age: Int)
来源：http://dali.gotoacloud.top/Article/details/gtivoukmzw.html

[T09] Kotlin：扩展函数
来源：http://dali.mhx1999.top/Article/details/gtamytftrt.html

fun String.exclaim() = this + "!"
来源：http://dali.jiagoushi.top/Article/details/gtsxokfqkx.html

[T10] Kotlin：默认参数
来源：http://dali.zhixingplan.top/Article/details/gtduhczcad.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.jlsjyb.cn/Article/details/gtpvbfyhdq.html

[T11] Kotlin：协程
来源：http://dali.zhoulong.xyz/Article/details/gtedxzregb.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.zdqjudy.top/Article/details/gtlgjkkbbj.html

[T12] Kotlin：解构声明
来源：http://dali.nanxuanxn.top/Article/details/gtokdptlex.html

val (a, b) = Pair(1, 2)
来源：http://dali.hnqzz.top/Article/details/gtvpajtchm.html

[T13] Kotlin：只读 Map
来源：http://dali.shzxlz.cn/Article/details/gtreuaerkl.html

val m = mapOf("a" to 1)
来源：http://dali.shzxlz.cn/Article/details/gtrieofpas.html

[T14] Kotlin：循环
来源：http://dali.guannengcc.top/Article/details/gtyljpktjj.html

for (i in 1..10) println(i)
来源：http://dali.wangdashe.top/Article/details/gtfurgddar.html

[T15] Kotlin：接口
来源：http://dali.xziqi.cn/Article/details/gtaqusgolz.html

interface Shape { fun area(): Double }
来源：http://dali.yongpay.top/Article/details/gtwepjcuyl.html

[T16] Swift：Hello World
来源：http://dali.tanke756.top/Article/details/gtijbnyode.html

print("Hello")
来源：http://dali.xinyue.icu/Article/details/gtqhhhlrvd.html

[T17] Swift：变量与常量
来源：http://dali.sweek.top/Article/details/gtjiyyfqoj.html

var a = 1;  let b = 2
来源：http://dali.nwbrower.top/Article/details/gtsdtrzyti.html

[T18] Swift：字符串插值
来源：http://dali.cdnleiting.top/Article/details/gttxyptpqf.html

"值: \(b)"
来源：http://dali.vqdsnc.cn/Article/details/gtixnqpbrb.html

[T19] Swift：可选绑定
来源：http://dali.ivvv.top/Article/details/gtrvjbkaje.html

if let n = opt { print(n) }
来源：http://dali.guowangkeji.top/Article/details/gtiyyglwmt.html

[T20] Swift：数组操作
来源：http://dali.zhongyouzk.top/Article/details/gtvdnjepth.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.daria6918.cn/Article/details/gtwjjlbigi.html

[T21] Swift：遍历
来源：http://dali.cucudq.cn/Article/details/gtzaqqndtk.html

for x in a { print(x) }
来源：http://dali.aizwys.cn/Article/details/gtdavpkkan.html

[T22] Swift：字典
来源：http://dali.c1oappe.top/Article/details/gtoykuydsy.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.yj20258888.top/Article/details/gtwtdgyybm.html

[T23] Swift：函数
来源：http://dali.yj20258.top/Article/details/gtnwarpxcd.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.sufxvd.cn/Article/details/gtkpxmxirp.html

[T24] Swift：闭包
来源：http://dali.pycfn.com/Article/details/gtpupvpsek.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.fzhhl.top/Article/details/gtmafxukqc.html

[T25] Swift：结构体
来源：http://dali.ydzc1.top/Article/details/gtjjzxcjpu.html

struct P { var x: Int }
来源：http://dali.sweek.top/Article/details/gthnslppwm.html

[T26] Swift：类与重写
来源：http://dali.feifeiyinyue.top/Article/details/gtqjnxuqlv.html

class A: Base { override func f() {} }
来源：http://dali.sxryk.cn/Article/details/gtopruhdsf.html

[T27] Swift：错误处理
来源：http://dali.jinqigufen.top/Article/details/gtjjorjanh.html

do { try f() } catch { print(error) }
来源：http://dali.fzhhl.top/Article/details/gthmleutbw.html

[T28] Swift：枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjoknrtai.html

enum Color { case red, green }
来源：http://dali.ivvv.top/Article/details/gtyfxnhzfn.html

[T29] Swift：guard 提前返回
来源：http://dali.yongpay.top/Article/details/gtuehxllth.html

guard let x = opt else { return }
来源：http://dali.yanxiufei.cn/Article/details/gtzoykemih.html

[T30] Swift：协议
来源：http://dali.yvedp.cn/Article/details/gtvmidtzby.html

protocol Shape { func area() -> Double }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsljnsrlc.html

[T31] Lua：Hello World
来源：http://dali.nanxinkj.top/Article/details/gtukzenspv.html

print("Hello")
来源：http://dali.daxiang520.top/Article/details/gtutasnzcj.html

[T32] Lua：局部变量
来源：http://dali.gotoacloud.top/Article/details/gtfzveqfky.html

local a = 1
来源：http://dali.zhixingplan.top/Article/details/gtzshqqtmg.html


<!-- 参考信息 -->