代发 wailian999

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yanxiufei.cn/Article/details/gtwpwxgckf.html

[R26] 命令替换
来源：http://dali.jianghu66.top/Article/details/gttnibzmtm.html

now=$(date +%F); echo "$now"
来源：http://dali.ehwqpu.com/Article/details/gthucvviax.html

[R27] 算术展开
来源：http://dali.cucudq.cn/Article/details/gtmjmrxiuw.html

echo $((1 + 2 * 3))
来源：http://dali.jlsjyb.cn/Article/details/gtsymkxelq.html

[R28] 浮点运算
来源：http://dali.shuidangran.top/Article/details/gtfhosvipt.html

echo "scale=2; 10/3" | bc
来源：http://dali.nanxuanxn.top/Article/details/gtyiiyinfg.html

[R29] 定义函数
来源：http://dali.yj20258.top/Article/details/gtuxpiysfj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhixingplan.top/Article/details/gtyediflwn.html

[R30] 函数返回状态码
来源：http://dali.kuanghao11.cn/Article/details/gtgmpktrtd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.aibaodan.cn/Article/details/gtsnamzmnm.html

[R31] 局部变量
来源：http://dali.gzhubu.top/Article/details/gtdqlbcuve.html

f() { local x=1; echo "$x"; }
来源：http://dali.meibo888.top/Article/details/gtqhfgffjh.html

[R32] 参数个数校验
来源：http://dali.jianghu66.top/Article/details/gtfsljkuck.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xylfe.cn/Article/details/gtttznusya.html

[R33] 捕获错误并提示行号
来源：http://dali.shanyushiyangtech.top/Article/details/gtquuclsvw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gzhubu.top/Article/details/gtzgrzzrzx.html

[R34] 退出时清理
来源：http://dali.hammf.cn/Article/details/gtzojuvkeb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.feifeiyinyue.top/Article/details/gtaonvaagt.html

[R35] 后台执行并等待
来源：http://dali.wangdashe.top/Article/details/gttazbuyma.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.daria6918.cn/Article/details/gtaghnfqhl.html

[R36] 并发执行多个任务
来源：http://dali.cashguo.top/Article/details/gtoengyvdk.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.fengsongda.top/Article/details/gtwzfwnxro.html

[R37] 把输出赋给变量
来源：http://dali.gotoacloud.top/Article/details/gtjrdjjsqv.html

files=$(ls -1)
来源：http://dali.yanxiufei.cn/Article/details/gttqkyunfw.html

[R38] 管道串联
来源：http://dali.iojbl.cn/Article/details/gtygvjyiuh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yongpay.top/Article/details/gtkzsznpti.html

[R39] 重定向标准输出与错误
来源：http://dali.sysykeji.top/Article/details/gtlflxefxj.html

cmd > out.log 2>&1
来源：http://dali.gotoacloud.top/Article/details/gtflenfbus.html

[R40] 追加写日志
来源：http://dali.nwbrower.top/Article/details/gtbuuknvbi.html

echo "log" >> out.log
来源：http://dali.zhongyouzk.top/Article/details/gtrnwrrpid.html

[R41] 丢弃输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtawruwssr.html

cmd >/dev/null 2>&1
来源：http://dali.chenzaomai.com/Article/details/gtgcshgiet.html

[R42] 输入重定向
来源：http://dali.havefunace.top/Article/details/gtskomniey.html

wc -l < a.txt
来源：http://dali.zycfv.cn/Article/details/gtgafzkpzz.html

[R43] 按名字查找文件
来源：http://dali.ehwqpu.com/Article/details/gtwituzcqx.html

find . -name "*.log" -type f
来源：http://dali.yangfankeji.com/Article/details/gtxgseazep.html

[R44] 按修改时间查找
来源：http://dali.feifeiyinyue.top/Article/details/gtirkqarnw.html

find . -mtime -7 -type f
来源：http://dali.nanxinkj.top/Article/details/gtlqsrntvh.html

[R45] 批量删除
来源：http://dali.havefunace.top/Article/details/gtfwcoznij.html

find . -name "*.tmp" -delete
来源：http://dali.aizwys.cn/Article/details/gtwbtgwlfu.html

[R46] 递归替换文件内容
来源：http://dali.yueranfly.top/Article/details/gtvvxsgfkb.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.svipenyu.cn/Article/details/gtqphbhjya.html

[R47] sed 单行替换
来源：http://dali.yanxiufei.cn/Article/details/gtvmddmxrl.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.c1oappe.top/Article/details/gtppdcryuu.html

[R48] awk 取指定列
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcvouxewf.html

awk '{print $1, $3}' a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtfkvqqxlq.html

[R49] awk 带条件
来源：http://dali.andypj.xyz/Article/details/gtqnxatnbh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shanyushiyangtech.top/Article/details/gtqsnqxmcz.html

[R50] awk 求和
来源：http://dali.c1oappe.top/Article/details/gtquavsaqq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtjzmkfsif.html

[R51] 排序去重取前几
来源：http://dali.zycfv.cn/Article/details/gtczviibgs.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthqecoreu.html

[R52] 统计行数
来源：http://dali.xuanzx.com/Article/details/gteprbeqtz.html

wc -l a.txt
来源：http://dali.sweek.top/Article/details/gtdpiykwxu.html

[R53] 查看文件头与实时尾
来源：http://dali.yanxiufei.cn/Article/details/gttvckithf.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ehwqpu.com/Article/details/gtjgchjogr.html

[R54] 比较两个文件
来源：http://dali.shuidangran.top/Article/details/gtppysievq.html

diff a.txt b.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtaxfzpcji.html

[R55] 压缩与解压
来源：http://dali.shuidangran.top/Article/details/gtnawzquuo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.tian-w.cn/Article/details/gtcxesbqby.html

[R56] 远程拷贝
来源：http://dali.xinyue.icu/Article/details/gtbhadtybx.html

scp file user@host:/path/
来源：http://dali.fzhhl.top/Article/details/gtktboepxb.html

[R57] 远程执行命令
来源：http://dali.sysykeji.top/Article/details/gtkkiwlkxx.html

ssh user@host 'uptime'
来源：http://dali.jqgfzy.top/Article/details/gtuumaqskp.html

[R58] 下载文件
来源：http://dali.316326.xyz/Article/details/gtvivjtvnm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.snrcjt.cn/Article/details/gttesmvouf.html

[R59] 发 POST JSON
来源：http://dali.cucudq.cn/Article/details/gtcoyiixxm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yanxiufei.cn/Article/details/gtujtcgatv.html

[R60] 只看 HTTP 状态码
来源：http://dali.guowangkeji.top/Article/details/gtbndwqdqb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.tian-w.cn/Article/details/gtpmjkqifp.html

[R61] 磁盘占用
来源：http://dali.xuetiantiany.cn/Article/details/gtjvophjsh.html

df -h;  du -sh *
来源：http://dali.kuanghao11.cn/Article/details/gtnzffxalj.html

[R62] 找最占空间的文件
来源：http://dali.jinqigufen.top/Article/details/gtdurmokxl.html

du -ah . | sort -rh | head -10
来源：http://dali.fzhhl.top/Article/details/gtlpojxmud.html

[R63] 内存与进程
来源：http://dali.snrcjt.cn/Article/details/gtbpgnizkv.html

free -h;  ps aux | grep nginx
来源：http://dali.yongpay.top/Article/details/gtbhnrbqww.html

[R64] 结束进程
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsmvqmrjh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.redwolf501.top/Article/details/gtdaqalamq.html

[R65] 查看端口占用
来源：http://dali.chenjidiqi.icu/Article/details/gtmbrdsrai.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj202588.top/Article/details/gtxgwkmkow.html

[R66] 定时任务
来源：http://dali.ivvv.top/Article/details/gtpygizydt.html

crontab -e;  crontab -l
来源：http://dali.jqgfzy.top/Article/details/gtrhgaabhn.html

[R67] 生成随机十六进制串
来源：http://dali.hnxiangtu.top/Article/details/gtptaaktex.html

openssl rand -hex 16
来源：http://dali.cheryme.top/Article/details/gthqqhntpm.html

[R68] 计算文件校验值
来源：http://dali.chenzaomai.com/Article/details/gtqhedtpoz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenlongwang.top/Article/details/gtsgganlrs.html

[R69] 生成随机密码
来源：http://dali.yuxming.cn/Article/details/gtdghabxma.html

head -c 16 /dev/urandom | base64
来源：http://dali.jinqigfzy.top/Article/details/gtiplfxxbx.html

[R70] 时间戳与互转
来源：http://dali.hysaishi.cn/Article/details/gthopufwqd.html

date +%s;  date -d @1700000000
来源：http://dali.bjfxy.top/Article/details/gtfrpcadbs.html

[R71] 日期格式化
来源：http://dali.cdnleiting.top/Article/details/gteaeziqxp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hysaishi.cn/Article/details/gtdkzntzln.html

[R72] 等待端口就绪
来源：http://dali.zdqjudy.top/Article/details/gthsqpwnlz.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.dianchejie.cn/Article/details/gtnahgehvl.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gtgqpjqaut.html

split -l 1000 big.log part_
来源：http://dali.yangfankeji.com/Article/details/gtnnkemjuk.html

[R74] 批量重命名
来源：http://dali.chenzaomai.com/Article/details/gtpmexrhom.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.meibo888.top/Article/details/gtxevdbrpd.html

[R75] 导出环境变量
来源：http://dali.wangshuangyany.cn/Article/details/gtkrjfpzap.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shangyingyoupin.top/Article/details/gtlwhwolne.html

[R76] 使用临时文件
来源：http://dali.shzxlz.cn/Article/details/gtjndgtkqv.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jyoumei.cn/Article/details/gtdvxwzohu.html

[R77] 读取用户输入
来源：http://dali.tanke756.top/Article/details/gtepsbnymj.html

read -rp "请输入: " ans
来源：http://dali.birdmap.top/Article/details/gtlxqxoozp.html

[R78] 交互式菜单
来源：http://dali.yj20258.top/Article/details/gttzrxvzvx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.guannengcc.top/Article/details/gtmmxdmxfg.html

[R79] 解析命令行选项
来源：http://dali.c1oappe.top/Article/details/gtaalkdaju.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yangfankeji.com/Article/details/gtfinwswlk.html

[R80] 查看脚本执行耗时
来源：http://dali.hnxiangtu.top/Article/details/gtiwcnbzvv.html

time ./run.sh
来源：http://dali.gzhubu.top/Article/details/gtworadzgs.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gtczvwuamj.html

S. C / C++ 专题
来源：http://dali.yj20258.top/Article/details/gtgjhxajjx.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtyfqfmvfb.html

[S01] C：Hello World
来源：http://dali.andypj.xyz/Article/details/gtrjdmiimc.html

#include <stdio.h>
来源：http://dali.zhongyouzk.top/Article/details/gtiwybgiok.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.gzhubu.top/Article/details/gtwammlnne.html

[S02] C：变量与格式化输出
来源：http://dali.shanyushiyangkeji.top/Article/details/gteofnibgi.html

int a = 10; printf("%d\n", a);
来源：http://dali.jqgufenzy.top/Article/details/gtxcacspzn.html

[S03] C：读入整数
来源：http://dali.jinqigfzy.top/Article/details/gtucfeumvv.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gtvdhazsbz.html

[S04] C：字符串复制
来源：http://dali.ivvv.top/Article/details/gtytfmedwf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hnxiangtu.top/Article/details/gtycpoowdi.html

[S05] C：字符串长度
来源：http://dali.pycfn.com/Article/details/gtwhqxjkyw.html

strlen(s)
来源：http://dali.gotoacloud.top/Article/details/gtallrunhh.html

[S06] C：字符串比较
来源：http://dali.hywenlv.cn/Article/details/gtvcxnphjm.html

strcmp(a, b) == 0
来源：http://dali.chenlongwang.top/Article/details/gtafovxtod.html

[S07] C：数组遍历求和
来源：http://dali.jinqigfzy.top/Article/details/gtwxcxqtjt.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhongyouzk.top/Article/details/gtighltbri.html

[S08] C：动态内存分配与释放
来源：http://dali.mhx1999.top/Article/details/gtlamleybq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hywenlv.cn/Article/details/gtuuitoriw.html

[S09] C：结构体定义与初始化
来源：http://dali.yj20258888.top/Article/details/gtunxwuaad.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.gaohongyu789.top/Article/details/gtldedbwzd.html

[S10] C：指针与解引用
来源：http://dali.cqqwz.cn/Article/details/gtqigflkgg.html

int *p = &a;  *p = 5;
来源：http://dali.yuanzhike.top/Article/details/gthqtxnefg.html

[S11] C：逐行读文件
来源：http://dali.birdmap.top/Article/details/gtkahpdmts.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinqigfzy.top/Article/details/gtmkqjmqoh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.iojbl.cn/Article/details/gtufkveuch.html

fclose(f);
来源：http://dali.xinyue.icu/Article/details/gtpfbresip.html

[S12] C：写文件
来源：http://dali.pycfn.com/Article/details/gtxefirpbi.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.chenjidiqi.icu/Article/details/gtetnygrsu.html

[S13] C：宏定义
来源：http://dali.zhongyouzk.top/Article/details/gtmaghiqii.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jqgufenzy.top/Article/details/gtfstcwppi.html

[S14] C：枚举
来源：http://dali.sufxvd.cn/Article/details/gtvddlmsle.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yonumen.top/Article/details/gthkorgqhk.html

[S15] C：类型转换
来源：http://dali.smart0.xyz/Article/details/gtzbfcekaq.html

(double) a / b
来源：http://dali.xylfe.cn/Article/details/gtmlmvypzg.html

[S16] C：位操作置位
来源：http://dali.hywenlv.cn/Article/details/gtkwpwhnmj.html

x |= (1 << 3);
来源：http://dali.yuxming.cn/Article/details/gtqwtdamht.html

[S17] C：安全拼接字符串
来源：http://dali.xinyue.icu/Article/details/gtiojtdnlc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ybcxt.top/Article/details/gtbiyyvihn.html

[S18] C：命令行参数
来源：http://dali.gotoacloud.top/Article/details/gtitwoojyq.html

int main(int argc, char **argv)
来源：http://dali.guannengcc.top/Article/details/gtbkezrico.html

[S19] C：快速排序
来源：http://dali.daxiang520.top/Article/details/gtwxibaknw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shzxlz.cn/Article/details/gtkkpsihlp.html

[S20] C：二分查找
来源：http://dali.zhiwuduotai.top/Article/details/gtflctkpto.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.cucudq.cn/Article/details/gtqlnidywa.html

[S21] C：字符类别判断
来源：http://dali.pengpengdd.cyou/Article/details/gtuontoupn.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ivvv.top/Article/details/gtzxknglmh.html

[S22] C：字符串转数字
来源：http://dali.chenjidiqi.icu/Article/details/gticuhpkvm.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.nanxinkj.top/Article/details/gttwgwzvae.html

[S23] C：随机数
来源：http://dali.vqdsnc.cn/Article/details/gtoxywgxgj.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tanke756.top/Article/details/gthmwykiki.html

[S24] C：获取本地时间
来源：http://dali.nanxinkj.top/Article/details/gtmczxnrib.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.shzxlz.cn/Article/details/gtoxtpbvor.html

[S25] C：内存拷贝
来源：http://dali.yj20258888.top/Article/details/gtvqbewvej.html

memcpy(dst, src, n);
来源：http://dali.jiagoushi.top/Article/details/gtgssvaekg.html

[S26] C：内存清零
来源：http://dali.hongshengwenyu.top/Article/details/gtwactcvrh.html

memset(a, 0, sizeof a);
来源：http://dali.xinyue.icu/Article/details/gtdjbfqnmu.html

[S27] C：定义常量
来源：http://dali.sxryk.cn/Article/details/gtfwyxygra.html

const double PI = 3.14159;
来源：http://dali.gzhubu.top/Article/details/gtodmvutvm.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gtetzycrzt.html

static int counter = 0;
来源：http://dali.jinqigfzy.top/Article/details/gtnkyvzeiy.html

[S29] C：变参函数
来源：http://dali.xziqi.cn/Article/details/gtvefkyruj.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shanyushiyangtech.top/Article/details/gtlmqbxypy.html

[S30] C：头文件保护
来源：http://dali.xziqi.cn/Article/details/gtuqhzjoza.html

#ifndef X_H
来源：http://dali.hysaishi.cn/Article/details/gtdlngtbnw.html

#define X_H
来源：http://dali.gotoacloud.top/Article/details/gtyjrmzirc.html

#endif
来源：http://dali.shuidangran.top/Article/details/gtfnifsqrh.html

[S31] C++：Hello World
来源：http://dali.yj20258.top/Article/details/gtookdguyu.html

#include <iostream>
来源：http://dali.zhengqikj.top/Article/details/gtofhhpgak.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sufxvd.cn/Article/details/gtrytmoggr.html

[S32] C++：字符串
来源：http://dali.ivvv.top/Article/details/gtgxynuyda.html

std::string s = "hi";  s += "!";
来源：http://dali.ydzc1.top/Article/details/gtdsivgrpe.html

[S33] C++：vector 增删
来源：http://dali.zdqjudy.top/Article/details/gtrkwdqisk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinqigufen.top/Article/details/gtgpaeqeqj.html

[S34] C++：遍历 vector
来源：http://dali.hywenlv.cn/Article/details/gttwoeceym.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.pycfn.com/Article/details/gttgyepati.html

[S35] C++：map
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcajsvgfu.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.pycfn.com/Article/details/gtmrnvnpfp.html

[S36] C++：unordered_map
来源：http://dali.xuanzx.com/Article/details/gtzllddyqg.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgufenzy.top/Article/details/gthqjljwfk.html

[S37] C++：set
来源：http://dali.c1oappe.top/Article/details/gttrisvydd.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.vqdsnc.cn/Article/details/gtwccxucqd.html

[S38] C++：排序
来源：http://dali.zhixingplan.top/Article/details/gtipnnfhay.html

std::sort(v.begin(), v.end());
来源：http://dali.cheryme.top/Article/details/gtxkvjzwad.html

[S39] C++：自定义比较器排序
来源：http://dali.sxryk.cn/Article/details/gtupdevjyb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.wangdashe.top/Article/details/gtepifkwrw.html

[S40] C++：查找元素
来源：http://dali.fengsongda.top/Article/details/gtqqsqglxv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.birdmap.top/Article/details/gthpgicroq.html

[S41] C++：类与构造函数
来源：http://dali.yanxiufei.cn/Article/details/gtzdfwhokc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sufxvd.cn/Article/details/gtlatwjphk.html

[S42] C++：继承与虚函数
来源：http://dali.zdqjudy.top/Article/details/gtlaehkcwk.html

class B : public Base { public: void f() override {} };
来源：http://dali.sweek.top/Article/details/gtbhhsimft.html

[S43] C++：智能指针
来源：http://dali.jinghuilouyu.cn/Article/details/gtxuuaorwu.html

auto p = std::make_unique<int>(5);
来源：http://dali.shangyingyoupin.top/Article/details/gtbnxbvcec.html

[S44] C++：引用传参
来源：http://dali.xziqi.cn/Article/details/gtjsxwckfo.html

void inc(int &x) { ++x; }
来源：http://dali.ppjwa.cn/Article/details/gtutchcqbq.html

[S45] C++：lambda
来源：http://dali.yonumen.top/Article/details/gtotrxnpax.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.snrcjt.cn/Article/details/gtetmfctgn.html

[S46] C++：函数模板
来源：http://dali.tian-w.cn/Article/details/gtdntwhxdo.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.dianchejie.cn/Article/details/gtmoktvxuh.html

[S47] C++：结构化绑定遍历
来源：http://dali.gaohongyu789.top/Article/details/gtswlglqqn.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.tanke756.top/Article/details/gtrzlxiakt.html

[S48] C++：逐行读文件
来源：http://dali.zhixingplan.top/Article/details/gtqppulylq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.ppjwa.cn/Article/details/gtczlvjrsh.html

while (std::getline(in, line)) { }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzubxmknr.html

[S49] C++：写文件
来源：http://dali.yuxming.cn/Article/details/gtzesfezvu.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhixingplan.top/Article/details/gtibsfotjh.html

[S50] C++：格式化数字
来源：http://dali.ppjwa.cn/Article/details/gtpbhmjhzb.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gtpzeffyfh.html

[S51] C++：显式类型转换
来源：http://dali.tanke756.top/Article/details/gtpgenumdx.html

static_cast<double>(a) / b
来源：http://dali.shzxlz.cn/Article/details/gttpdyoqlk.html

[S52] C++：const 与 noexcept
来源：http://dali.ybcxt.top/Article/details/gtsacgyoyb.html

int size() const noexcept { return n_; }
来源：http://dali.zycfv.cn/Article/details/gtlspdymdl.html

[S53] C++：移动语义
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgrzgqsnp.html

std::vector<int> w = std::move(v);
来源：http://dali.ehwqpu.com/Article/details/gtvvytciat.html

[S54] C++：异常处理
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtopkgkock.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.ybcxt.top/Article/details/gtzrgclykr.html

[S55] C++：结构化绑定
来源：http://dali.yanxiufei.cn/Article/details/gtppqfjfyo.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.wangdashe.top/Article/details/gtrusyhcwu.html

[S56] C++：optional
来源：http://dali.shangyingyoupin.top/Article/details/gtgicjhpro.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.daria6918.cn/Article/details/gtbdlyheix.html

[S57] C++：编译期常量
来源：http://dali.hammf.cn/Article/details/gtmkownknw.html

constexpr int N = 10;
来源：http://dali.zhongyouzk.top/Article/details/gtqegwqihf.html

[S58] C++：命名空间
来源：http://dali.guannengcc.top/Article/details/gtwaqxhfoc.html

namespace ns { int f() { return 1; } }
来源：http://dali.hywenlv.cn/Article/details/gtgttmguof.html

[S59] C++：静态断言
来源：http://dali.hammf.cn/Article/details/gtlgshhzvm.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.ydzc1.top/Article/details/gtnyuiomni.html

[S60] C++：遍历并删除元素
来源：http://dali.zdqjudy.top/Article/details/gtbmlvncow.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.nwbrower.top/Article/details/gtqohgskqt.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtgcxyaejl.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nanxuanxn.top/Article/details/gtcubxlfos.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gtaypsoazy.html

[T01] Kotlin：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxopjlfnm.html

println("Hello")
来源：http://dali.jqgfzy.top/Article/details/gtxsymtxwc.html

[T02] Kotlin：变量
来源：http://dali.wangdashe.top/Article/details/gtsotehuav.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.cucudq.cn/Article/details/gtrmmxiodo.html

[T03] Kotlin：字符串模板
来源：http://dali.havefunace.top/Article/details/gtplmqhvds.html

"值: $b"
来源：http://dali.sxryk.cn/Article/details/gtzhecdmuk.html

[T04] Kotlin：空安全
来源：http://dali.gotoacloud.top/Article/details/gtewpbyluj.html

val n: String? = null;  n?.length
来源：http://dali.daxiang520.top/Article/details/gtxkuqistf.html

[T05] Kotlin：when 表达式
来源：http://dali.havefunace.top/Article/details/gtdfccxyba.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yvedp.cn/Article/details/gtcsovppqd.html

[T06] Kotlin：集合映射
来源：http://dali.zdqjudy.top/Article/details/gtuwqcsaoj.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.vqdsnc.cn/Article/details/gtkzwzpdlz.html

[T07] Kotlin：集合过滤
来源：http://dali.chenzaomai.com/Article/details/gtfdxifctv.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.svipenyu.cn/Article/details/gtngkztces.html

[T08] Kotlin：数据类
来源：http://dali.birdmap.top/Article/details/gtgzfahsxg.html

data class User(val name: String, val age: Int)
来源：http://dali.meibo888.top/Article/details/gtjeqhwxjs.html

[T09] Kotlin：扩展函数
来源：http://dali.yanxiufei.cn/Article/details/gtvnugniuc.html

fun String.exclaim() = this + "!"
来源：http://dali.9152youxi.cn/Article/details/gtlspkibzn.html

[T10] Kotlin：默认参数
来源：http://dali.cqqwz.cn/Article/details/gtkwhtrwcv.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cheryme.top/Article/details/gtedzmifjh.html

[T11] Kotlin：协程
来源：http://dali.nanxinkj.top/Article/details/gtjzlmpibv.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.nwbrower.top/Article/details/gttgyrkado.html

[T12] Kotlin：解构声明
来源：http://dali.sufxvd.cn/Article/details/gtfdqrlope.html

val (a, b) = Pair(1, 2)
来源：http://dali.xziqi.cn/Article/details/gtclbmgmgc.html

[T13] Kotlin：只读 Map
来源：http://dali.yongpay.top/Article/details/gtheoawfcx.html

val m = mapOf("a" to 1)
来源：http://dali.sufxvd.cn/Article/details/gtngpusegn.html

[T14] Kotlin：循环
来源：http://dali.guannengcc.top/Article/details/gtzenmythf.html

for (i in 1..10) println(i)
来源：http://dali.dianchejie.cn/Article/details/gttidmzavc.html

[T15] Kotlin：接口
来源：http://dali.hywenlv.cn/Article/details/gtubdjwbkl.html

interface Shape { fun area(): Double }
来源：http://dali.shangyingyoupin.top/Article/details/gtxccmhbfg.html

[T16] Swift：Hello World
来源：http://dali.havefunace.top/Article/details/gtqfbykdxu.html

print("Hello")
来源：http://dali.c1oappe.top/Article/details/gtsxfdhenq.html

[T17] Swift：变量与常量
来源：http://dali.gogol.net.cn/Article/details/gtpjjzuxae.html

var a = 1;  let b = 2
来源：http://dali.kuanghao11.cn/Article/details/gtjdphpuir.html

[T18] Swift：字符串插值
来源：http://dali.jinqigfzy.top/Article/details/gtqzhbitkm.html

"值: \(b)"
来源：http://dali.gogol.net.cn/Article/details/gtgxmjsadv.html

[T19] Swift：可选绑定
来源：http://dali.zhijiandao.cn/Article/details/gtusndhyve.html

if let n = opt { print(n) }
来源：http://dali.yuanzhike.top/Article/details/gtaityhnjx.html

[T20] Swift：数组操作
来源：http://dali.mhx1999.top/Article/details/gtkenbjnzf.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.xylfe.cn/Article/details/gtmtrmuhkb.html

[T21] Swift：遍历
来源：http://dali.fengsongda.top/Article/details/gtuenkggks.html

for x in a { print(x) }
来源：http://dali.aibaodan.cn/Article/details/gtdiulxqfm.html

[T22] Swift：字典
来源：http://dali.havefunace.top/Article/details/gtcoyegfyu.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.zycfv.cn/Article/details/gtbysonaqs.html

[T23] Swift：函数
来源：http://dali.yangfankeji.com/Article/details/gtduucetyj.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.kuanghao11.cn/Article/details/gtamlawkft.html

[T24] Swift：闭包
来源：http://dali.vqdsnc.cn/Article/details/gtodsgbxck.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.nanxuanxn.top/Article/details/gtvonqhzbo.html

[T25] Swift：结构体
来源：http://dali.jqgufenzy.top/Article/details/gtxhdwgwwq.html

struct P { var x: Int }
来源：http://dali.feifeiyinyue.top/Article/details/gtflgehfaa.html

[T26] Swift：类与重写
来源：http://dali.sxryk.cn/Article/details/gtizvrvtwc.html

class A: Base { override func f() {} }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbyfziczu.html

[T27] Swift：错误处理
来源：http://dali.daria6918.cn/Article/details/gtzuasxqkd.html

do { try f() } catch { print(error) }
来源：http://dali.aizwys.cn/Article/details/gtdafxsqoy.html

[T28] Swift：枚举
来源：http://dali.pengpengdd.cyou/Article/details/gtdsikszzh.html

enum Color { case red, green }
来源：http://dali.guowangkeji.top/Article/details/gtdmwnqppw.html


<!-- 参考信息 -->