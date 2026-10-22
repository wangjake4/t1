代发 wailian999

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtodpubtlx.html

[R24] 大小写转换
来源：http://dali.yuxming.cn/Article/details/gtyjujptme.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xuanzx.com/Article/details/gtyotyyukw.html

[R25] 去后缀 / 去前缀
来源：http://dali.jinghuilouyu.cn/Article/details/gtsuncaqdl.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.guowangkeji.top/Article/details/gtrbjzueqo.html

[R26] 命令替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqvjzvccl.html

now=$(date +%F); echo "$now"
来源：http://dali.redwolf501.top/Article/details/gtoldxaoiu.html

[R27] 算术展开
来源：http://dali.shangyingyoupin.top/Article/details/gtshjtmjil.html

echo $((1 + 2 * 3))
来源：http://dali.tanke756.top/Article/details/gttzkmvuvk.html

[R28] 浮点运算
来源：http://dali.vqdsnc.cn/Article/details/gtjdpybmzw.html

echo "scale=2; 10/3" | bc
来源：http://dali.daxiang520.top/Article/details/gtzsqnsako.html

[R29] 定义函数
来源：http://dali.fengsongda.top/Article/details/gtkefmozra.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtoeddfjcg.html

[R30] 函数返回状态码
来源：http://dali.fzhhl.top/Article/details/gtuvszrkvy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cucudq.cn/Article/details/gtbglvtmii.html

[R31] 局部变量
来源：http://dali.yongpay.top/Article/details/gtdpcckxta.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhongyouzk.top/Article/details/gtzrjqvhrf.html

[R32] 参数个数校验
来源：http://dali.daxiang520.top/Article/details/gtslwqcwfs.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtkwthcjew.html

[R33] 捕获错误并提示行号
来源：http://dali.xinyue.icu/Article/details/gtjlwxibto.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.aibaodan.cn/Article/details/gtvhhezlcj.html

[R34] 退出时清理
来源：http://dali.zycfv.cn/Article/details/gtzqipnflf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.aizwys.cn/Article/details/gtqpctgflo.html

[R35] 后台执行并等待
来源：http://dali.ydzc1.top/Article/details/gteygvrnul.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.snrcjt.cn/Article/details/gtzbucbahd.html

[R36] 并发执行多个任务
来源：http://dali.guowangkeji.top/Article/details/gthufqvafi.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ivvv.top/Article/details/gthstxjmsz.html

[R37] 把输出赋给变量
来源：http://dali.jqgfzy.top/Article/details/gtocpucjxy.html

files=$(ls -1)
来源：http://dali.yonumen.top/Article/details/gtifesbkbw.html

[R38] 管道串联
来源：http://dali.hammf.cn/Article/details/gtvogjpvpm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.aibaodan.cn/Article/details/gtomryjgmq.html

[R39] 重定向标准输出与错误
来源：http://dali.9152youxi.cn/Article/details/gtoxnxrjsm.html

cmd > out.log 2>&1
来源：http://dali.cqqwz.cn/Article/details/gtkxhqvelb.html

[R40] 追加写日志
来源：http://dali.guannengcc.top/Article/details/gtnhestxqr.html

echo "log" >> out.log
来源：http://dali.cucudq.cn/Article/details/gtzpafzotm.html

[R41] 丢弃输出
来源：http://dali.shzxlz.cn/Article/details/gthfrbznhi.html

cmd >/dev/null 2>&1
来源：http://dali.svipenyu.cn/Article/details/gtuilzefbk.html

[R42] 输入重定向
来源：http://dali.gaohongyu789.top/Article/details/gthzirnwgb.html

wc -l < a.txt
来源：http://dali.nwbrower.top/Article/details/gtructdztv.html

[R43] 按名字查找文件
来源：http://dali.tianlin.xyz/Article/details/gtfmnotazb.html

find . -name "*.log" -type f
来源：http://dali.tianlin.xyz/Article/details/gtrdhdfvyl.html

[R44] 按修改时间查找
来源：http://dali.ybcxt.top/Article/details/gtavzitida.html

find . -mtime -7 -type f
来源：http://dali.iojbl.cn/Article/details/gtwvztnmbb.html

[R45] 批量删除
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwyjolivu.html

find . -name "*.tmp" -delete
来源：http://dali.jyoumei.cn/Article/details/gtquvxtigm.html

[R46] 递归替换文件内容
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjkmcfcpc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.smart0.xyz/Article/details/gtcczuaaqi.html

[R47] sed 单行替换
来源：http://dali.cashguo.top/Article/details/gthialllue.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.tian-w.cn/Article/details/gtteeshxwk.html

[R48] awk 取指定列
来源：http://dali.cheryme.top/Article/details/gtrucafwfj.html

awk '{print $1, $3}' a.txt
来源：http://dali.haohaochexian.top/Article/details/gtmzgrbrse.html

[R49] awk 带条件
来源：http://dali.zhengqikj.top/Article/details/gtudmifrtb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yangfankeji.com/Article/details/gtxahvkxys.html

[R50] awk 求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwiunbegp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.aizwys.cn/Article/details/gtvtewyhxa.html

[R51] 排序去重取前几
来源：http://dali.sxryk.cn/Article/details/gtjsvffkwq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.0kj1m.cn/Article/details/gtljrzdlwv.html

[R52] 统计行数
来源：http://dali.redwolf501.top/Article/details/gthdjusbma.html

wc -l a.txt
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlmeavqan.html

[R53] 查看文件头与实时尾
来源：http://dali.ivvv.top/Article/details/gtfapgcjhv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shzxlz.cn/Article/details/gtrkmbcqjf.html

[R54] 比较两个文件
来源：http://dali.yj20258.top/Article/details/gtenbjfzat.html

diff a.txt b.txt
来源：http://dali.hfpthk.cn/Article/details/gtlpxefpji.html

[R55] 压缩与解压
来源：http://dali.gotoacloud.top/Article/details/gtrruvzoic.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.chenzaomai.com/Article/details/gtjgcfjlxi.html

[R56] 远程拷贝
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcgtzcbmf.html

scp file user@host:/path/
来源：http://dali.sufxvd.cn/Article/details/gtdlrxkaet.html

[R57] 远程执行命令
来源：http://dali.ywan-chungtsiang.top/Article/details/gttwuehezl.html

ssh user@host 'uptime'
来源：http://dali.daria6918.cn/Article/details/gtjejibenu.html

[R58] 下载文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoqzihhig.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.daria6918.cn/Article/details/gtxrmmegwl.html

[R59] 发 POST JSON
来源：http://dali.meibo888.top/Article/details/gthrdyqmbt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.quarkkingdee.top/Article/details/gtmuanhggc.html

[R60] 只看 HTTP 状态码
来源：http://dali.shangyingyoupin.top/Article/details/gtrmyfpjkq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlkloullg.html

[R61] 磁盘占用
来源：http://dali.andypj.xyz/Article/details/gttkimnbpa.html

df -h;  du -sh *
来源：http://dali.yvedp.cn/Article/details/gtlmidqmoo.html

[R62] 找最占空间的文件
来源：http://dali.wangshuangyany.cn/Article/details/gtadyecvma.html

du -ah . | sort -rh | head -10
来源：http://dali.yonumen.top/Article/details/gtjqmxsfeq.html

[R63] 内存与进程
来源：http://dali.aizwys.cn/Article/details/gtpyvlqdwb.html

free -h;  ps aux | grep nginx
来源：http://dali.haohaochexian.top/Article/details/gtqfzvijkx.html

[R64] 结束进程
来源：http://dali.daria6918.cn/Article/details/gtfsclvaec.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhengqikj.top/Article/details/gthrwguimj.html

[R65] 查看端口占用
来源：http://dali.svipenyu.cn/Article/details/gtgmlbmscp.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yj20258.top/Article/details/gtaajcezfd.html

[R66] 定时任务
来源：http://dali.guannengcc.top/Article/details/gtbwhtzwwl.html

crontab -e;  crontab -l
来源：http://dali.yanxiufei.cn/Article/details/gtmzozewnr.html

[R67] 生成随机十六进制串
来源：http://dali.kuanghao11.cn/Article/details/gtsdylgbfk.html

openssl rand -hex 16
来源：http://dali.hongshengwenyu.top/Article/details/gthvbfxpuz.html

[R68] 计算文件校验值
来源：http://dali.0kj1m.cn/Article/details/gtvxxwebkl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hfpthk.cn/Article/details/gtwhxagmyc.html

[R69] 生成随机密码
来源：http://dali.zhoulong.xyz/Article/details/gteslwdnmg.html

head -c 16 /dev/urandom | base64
来源：http://dali.dashuyun.cn/Article/details/gtqeaheuaq.html

[R70] 时间戳与互转
来源：http://dali.hongshengwenyu.top/Article/details/gtcexwelxj.html

date +%s;  date -d @1700000000
来源：http://dali.gzhubu.top/Article/details/gtbfrfthpj.html

[R71] 日期格式化
来源：http://dali.tanke756.top/Article/details/gtwiwldpiv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yangfankeji.com/Article/details/gtlzqhjxjo.html

[R72] 等待端口就绪
来源：http://dali.fengsongda.top/Article/details/gtapxfrosp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ybcxt.top/Article/details/gtjjbjlfrn.html

[R73] 分割大日志
来源：http://dali.jyoumei.cn/Article/details/gtlpgaxewx.html

split -l 1000 big.log part_
来源：http://dali.zhaomingkeji.xyz/Article/details/gtybcrkykm.html

[R74] 批量重命名
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcyhwftfc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlamspaoq.html

[R75] 导出环境变量
来源：http://dali.9152youxi.cn/Article/details/gtyhkpqjqw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrlcygfgb.html

[R76] 使用临时文件
来源：http://dali.chenjidiqi.icu/Article/details/gtdezcmfik.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.meibo888.top/Article/details/gtaolnhtod.html

[R77] 读取用户输入
来源：http://dali.jiagoushi.top/Article/details/gtfodndute.html

read -rp "请输入: " ans
来源：http://dali.yonumen.top/Article/details/gtjdnkfkhf.html

[R78] 交互式菜单
来源：http://dali.cqqwz.cn/Article/details/gtfgagzoux.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.hammf.cn/Article/details/gtdneeuxvp.html

[R79] 解析命令行选项
来源：http://dali.0kj1m.cn/Article/details/gthxntaxql.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.dianchejie.cn/Article/details/gtcixvwthv.html

[R80] 查看脚本执行耗时
来源：http://dali.0kj1m.cn/Article/details/gttngsgfsq.html

time ./run.sh
来源：http://dali.cashguo.top/Article/details/gttblhwjfy.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfijvezop.html

S. C / C++ 专题
来源：http://dali.tanke756.top/Article/details/gtkfmmkiyt.html

================================================================================
来源：http://dali.zhoulong.xyz/Article/details/gtbmlmaxnb.html

[S01] C：Hello World
来源：http://dali.birdmap.top/Article/details/gtpefbsmpz.html

#include <stdio.h>
来源：http://dali.cqqwz.cn/Article/details/gtxobjhjcs.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jlsjyb.cn/Article/details/gtzzoaaqaq.html

[S02] C：变量与格式化输出
来源：http://dali.sxryk.cn/Article/details/gtugdknnyt.html

int a = 10; printf("%d\n", a);
来源：http://dali.xinyue.icu/Article/details/gtnaafqwiw.html

[S03] C：读入整数
来源：http://dali.dashuyun.cn/Article/details/gtesdbxpuy.html

int x; scanf("%d", &x);
来源：http://dali.ehwqpu.com/Article/details/gthsclfptd.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gtiaznwywq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhoulong.xyz/Article/details/gtbzvxszrq.html

[S05] C：字符串长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkugvawas.html

strlen(s)
来源：http://dali.jiagoushi.top/Article/details/gtxyzlpbgv.html

[S06] C：字符串比较
来源：http://dali.9152youxi.cn/Article/details/gtmemprgky.html

strcmp(a, b) == 0
来源：http://dali.yuxming.cn/Article/details/gteaewoosh.html

[S07] C：数组遍历求和
来源：http://dali.hnxiangtu.top/Article/details/gtlwcaiowb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.guannengcc.top/Article/details/gtbwrcnqvp.html

[S08] C：动态内存分配与释放
来源：http://dali.svipenyu.cn/Article/details/gtkcravjhm.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jlsjyb.cn/Article/details/gtexddxpbp.html

[S09] C：结构体定义与初始化
来源：http://dali.ybcxt.top/Article/details/gtcztnppyi.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hammf.cn/Article/details/gtiumgnydz.html

[S10] C：指针与解引用
来源：http://dali.9152youxi.cn/Article/details/gtlnzybynw.html

int *p = &a;  *p = 5;
来源：http://dali.jqgfzy.top/Article/details/gtzwfzfxzl.html

[S11] C：逐行读文件
来源：http://dali.jqgfzy.top/Article/details/gtpavxtucu.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.birdmap.top/Article/details/gtioyoesqm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sufxvd.cn/Article/details/gtqgtceroq.html

fclose(f);
来源：http://dali.ppjwa.cn/Article/details/gtnbtxkcww.html

[S12] C：写文件
来源：http://dali.svipenyu.cn/Article/details/gtzexhanud.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jqgfzy.top/Article/details/gtyuyeqajp.html

[S13] C：宏定义
来源：http://dali.andypj.xyz/Article/details/gtvkvbzrrz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.haohaochexian.top/Article/details/gtdcsfbiir.html

[S14] C：枚举
来源：http://dali.guannengcc.top/Article/details/gtwgvbnnxb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.tanke756.top/Article/details/gtgwrzgkhb.html

[S15] C：类型转换
来源：http://dali.zycfv.cn/Article/details/gtzfhsplis.html

(double) a / b
来源：http://dali.yj202588.top/Article/details/gtsurbzhon.html

[S16] C：位操作置位
来源：http://dali.hongshengwenyu.top/Article/details/gtfihimkex.html

x |= (1 << 3);
来源：http://dali.dashuyun.cn/Article/details/gttxhtwgcm.html

[S17] C：安全拼接字符串
来源：http://dali.haohaochexian.top/Article/details/gtvuenrtzs.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.tianlin.xyz/Article/details/gtaoqqyrcs.html

[S18] C：命令行参数
来源：http://dali.0kj1m.cn/Article/details/gtmisankci.html

int main(int argc, char **argv)
来源：http://dali.chenlongwang.top/Article/details/gtbjrqwsch.html

[S19] C：快速排序
来源：http://dali.snrcjt.cn/Article/details/gtvbwngxwg.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gaohongyu789.top/Article/details/gtqkgvchfg.html

[S20] C：二分查找
来源：http://dali.haohaochexian.top/Article/details/gtldxqwiex.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.svipenyu.cn/Article/details/gtehcnjsaz.html

[S21] C：字符类别判断
来源：http://dali.daxiang520.top/Article/details/gtnrvtzclt.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.vqdsnc.cn/Article/details/gtjfkkevsl.html

[S22] C：字符串转数字
来源：http://dali.zhoulong.xyz/Article/details/gtyeeypdkd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.xuetiantiany.cn/Article/details/gtbrqsrden.html

[S23] C：随机数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtquribzsh.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.wangdashe.top/Article/details/gtgxrgwzjq.html

[S24] C：获取本地时间
来源：http://dali.yuanzhike.top/Article/details/gtszzuvgka.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yvedp.cn/Article/details/gtzibnjesw.html

[S25] C：内存拷贝
来源：http://dali.wangshuangyany.cn/Article/details/gtsetiualo.html

memcpy(dst, src, n);
来源：http://dali.dianchejie.cn/Article/details/gthbryaiet.html

[S26] C：内存清零
来源：http://dali.cashguo.top/Article/details/gtmugeembi.html

memset(a, 0, sizeof a);
来源：http://dali.mhx1999.top/Article/details/gtmdkpmkaf.html

[S27] C：定义常量
来源：http://dali.gaohongyu789.top/Article/details/gtrfdntjqn.html

const double PI = 3.14159;
来源：http://dali.yj20258888.top/Article/details/gtmyxhzfnz.html

[S28] C：静态变量
来源：http://dali.tanke756.top/Article/details/gtehwsywvx.html

static int counter = 0;
来源：http://dali.gzhubu.top/Article/details/gtpbcmpwji.html

[S29] C：变参函数
来源：http://dali.xuanzx.com/Article/details/gtmqbdkuul.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hammf.cn/Article/details/gtwipxntqz.html

[S30] C：头文件保护
来源：http://dali.sweek.top/Article/details/gtoaxookih.html

#ifndef X_H
来源：http://dali.kuanghao11.cn/Article/details/gtibyipbts.html

#define X_H
来源：http://dali.yuxming.cn/Article/details/gtmthjceyz.html

#endif
来源：http://dali.jlsjyb.cn/Article/details/gtovhmiwmt.html

[S31] C++：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtbdmofljc.html

#include <iostream>
来源：http://dali.gzhubu.top/Article/details/gtjhqslyuw.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.snrcjt.cn/Article/details/gtwijkeysx.html

[S32] C++：字符串
来源：http://dali.xylfe.cn/Article/details/gtvqpybexj.html

std::string s = "hi";  s += "!";
来源：http://dali.zycfv.cn/Article/details/gtfdozqgrq.html

[S33] C++：vector 增删
来源：http://dali.shangyingyoupin.top/Article/details/gtnsizqejm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hfpthk.cn/Article/details/gtvobrdmmf.html

[S34] C++：遍历 vector
来源：http://dali.zhengqikj.top/Article/details/gtugaqwkzv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yonumen.top/Article/details/gtqaykkpgo.html

[S35] C++：map
来源：http://dali.yuanzhike.top/Article/details/gtedmzupwr.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ehwqpu.com/Article/details/gtgzlrkany.html

[S36] C++：unordered_map
来源：http://dali.xuetiantiany.cn/Article/details/gttehnfuus.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.daria6918.cn/Article/details/gtctqgoozy.html

[S37] C++：set
来源：http://dali.xinyue.icu/Article/details/gtuiqpdjay.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.ydzc1.top/Article/details/gtscwhewth.html

[S38] C++：排序
来源：http://dali.dianchejie.cn/Article/details/gtwdnlrcam.html

std::sort(v.begin(), v.end());
来源：http://dali.jinqigfzy.top/Article/details/gtvayzqsyh.html

[S39] C++：自定义比较器排序
来源：http://dali.yuanzhike.top/Article/details/gtpwozgrlb.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.dianchejie.cn/Article/details/gtnhjsccwa.html

[S40] C++：查找元素
来源：http://dali.gotoacloud.top/Article/details/gtlcwjqcdw.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yj20258888.top/Article/details/gtoqwqjsuj.html

[S41] C++：类与构造函数
来源：http://dali.hongshengwenyu.top/Article/details/gtdobbtucm.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.hnqzz.top/Article/details/gtjqzwcskl.html

[S42] C++：继承与虚函数
来源：http://dali.yueranfly.top/Article/details/gtwmccgcor.html

class B : public Base { public: void f() override {} };
来源：http://dali.pengpengdd.cyou/Article/details/gtqbevayzq.html

[S43] C++：智能指针
来源：http://dali.cqqwz.cn/Article/details/gtzwustuah.html

auto p = std::make_unique<int>(5);
来源：http://dali.nanxinkj.top/Article/details/gtymvwqglb.html

[S44] C++：引用传参
来源：http://dali.yanxiufei.cn/Article/details/gtgligihlu.html

void inc(int &x) { ++x; }
来源：http://dali.yongpay.top/Article/details/gtgrsvtcho.html

[S45] C++：lambda
来源：http://dali.dashuyun.cn/Article/details/gtzhrscrzd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xinyue.icu/Article/details/gtrsppigls.html

[S46] C++：函数模板
来源：http://dali.meibo888.top/Article/details/gtaxzmvuci.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.meibo888.top/Article/details/gtlmpkjyzt.html

[S47] C++：结构化绑定遍历
来源：http://dali.cheryme.top/Article/details/gtezgmysbl.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.hnxiangtu.top/Article/details/gtqlksfcnn.html

[S48] C++：逐行读文件
来源：http://dali.hnqzz.top/Article/details/gtncttorcd.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.jqgufenzy.top/Article/details/gtcldmijme.html

while (std::getline(in, line)) { }
来源：http://dali.aibaodan.cn/Article/details/gtvtbigrex.html

[S49] C++：写文件
来源：http://dali.yj20258.top/Article/details/gtwniehqbw.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hnxiangtu.top/Article/details/gtjuwbyywu.html

[S50] C++：格式化数字
来源：http://dali.sufxvd.cn/Article/details/gtaxdczrha.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.sysykeji.top/Article/details/gthwfefvcv.html

[S51] C++：显式类型转换
来源：http://dali.tian-w.cn/Article/details/gtkymddher.html

static_cast<double>(a) / b
来源：http://dali.ybcxt.top/Article/details/gtxggccvrk.html

[S52] C++：const 与 noexcept
来源：http://dali.pycfn.com/Article/details/gttgsrmtrq.html

int size() const noexcept { return n_; }
来源：http://dali.ivvv.top/Article/details/gtqsjwevvj.html

[S53] C++：移动语义
来源：http://dali.yanxiufei.cn/Article/details/gtztqgsyuz.html

std::vector<int> w = std::move(v);
来源：http://dali.jiagoushi.top/Article/details/gtrvqnzaaw.html

[S54] C++：异常处理
来源：http://dali.hnqzz.top/Article/details/gtawcxjyhm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jyoumei.cn/Article/details/gtxcccjuap.html

[S55] C++：结构化绑定
来源：http://dali.guannengcc.top/Article/details/gtpfufxplv.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.aibaodan.cn/Article/details/gtijtdxpqf.html

[S56] C++：optional
来源：http://dali.ybcxt.top/Article/details/gtbjkiafhc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.jqgufenzy.top/Article/details/gtklwtdwzr.html

[S57] C++：编译期常量
来源：http://dali.ivvv.top/Article/details/gtgmmiojah.html

constexpr int N = 10;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuuhyuznk.html

[S58] C++：命名空间
来源：http://dali.jinghuilouyu.cn/Article/details/gtzqfpwsqq.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhengqikj.top/Article/details/gtpbwuzdmb.html

[S59] C++：静态断言
来源：http://dali.jinyuanbaomall.cn/Article/details/gtirymgvna.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shuidangran.top/Article/details/gtcqgalmvl.html

[S60] C++：遍历并删除元素
来源：http://dali.0kj1m.cn/Article/details/gtvtmwrvcd.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.fengsongda.top/Article/details/gtdruccwql.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtdsntmihu.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.daxiang520.top/Article/details/gtmjzoruxp.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtevwuedrx.html

[T01] Kotlin：Hello World
来源：http://dali.gotoacloud.top/Article/details/gtifewputx.html

println("Hello")
来源：http://dali.fengsongda.top/Article/details/gttwkubpjg.html

[T02] Kotlin：变量
来源：http://dali.sxryk.cn/Article/details/gtxuwnbqif.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.iojbl.cn/Article/details/gtncptqijb.html

[T03] Kotlin：字符串模板
来源：http://dali.aizwys.cn/Article/details/gtvdcjekqy.html

"值: $b"
来源：http://dali.chenlongwang.top/Article/details/gtnffbsnrk.html

[T04] Kotlin：空安全
来源：http://dali.dianchejie.cn/Article/details/gtjjoneihq.html

val n: String? = null;  n?.length
来源：http://dali.yueranfly.top/Article/details/gtspjjrtnr.html

[T05] Kotlin：when 表达式
来源：http://dali.chenzaomai.com/Article/details/gtyqqlamjb.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.hongshengwenyu.top/Article/details/gtsbfnmqwc.html

[T06] Kotlin：集合映射
来源：http://dali.cheryme.top/Article/details/gtwqhzvhzh.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthvmobanz.html

[T07] Kotlin：集合过滤
来源：http://dali.yuxming.cn/Article/details/gtjhswjsne.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zdqjudy.top/Article/details/gtcubjzmla.html

[T08] Kotlin：数据类
来源：http://dali.yongpay.top/Article/details/gtjfctmulu.html

data class User(val name: String, val age: Int)
来源：http://dali.chenlongwang.top/Article/details/gtwjzavmrl.html

[T09] Kotlin：扩展函数
来源：http://dali.cashguo.top/Article/details/gtcespemfz.html

fun String.exclaim() = this + "!"
来源：http://dali.meibo888.top/Article/details/gtpnwiecem.html

[T10] Kotlin：默认参数
来源：http://dali.hywenlv.cn/Article/details/gtpwtczbhh.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.hongshengwenyu.top/Article/details/gtgxxnhxbp.html

[T11] Kotlin：协程
来源：http://dali.daria6918.cn/Article/details/gtohozgtju.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.ehwqpu.com/Article/details/gtrylvuagz.html

[T12] Kotlin：解构声明
来源：http://dali.jinghuilouyu.cn/Article/details/gtbfumxlex.html

val (a, b) = Pair(1, 2)
来源：http://dali.wangdashe.top/Article/details/gtnqybugyc.html

[T13] Kotlin：只读 Map
来源：http://dali.snrcjt.cn/Article/details/gtwenledtb.html

val m = mapOf("a" to 1)
来源：http://dali.svipenyu.cn/Article/details/gtrqgtsgfk.html

[T14] Kotlin：循环
来源：http://dali.jqgfzy.top/Article/details/gttddjmoyh.html

for (i in 1..10) println(i)
来源：http://dali.xuanzx.com/Article/details/gthddzafxl.html

[T15] Kotlin：接口
来源：http://dali.sweek.top/Article/details/gtzbwchdhp.html

interface Shape { fun area(): Double }
来源：http://dali.aibaodan.cn/Article/details/gtxdhdgsix.html

[T16] Swift：Hello World
来源：http://dali.jqgufenzy.top/Article/details/gtsayoayjn.html

print("Hello")
来源：http://dali.ehwqpu.com/Article/details/gtbeorwrcj.html

[T17] Swift：变量与常量
来源：http://dali.tianlin.xyz/Article/details/gtpjsfqidv.html

var a = 1;  let b = 2
来源：http://dali.shangyingyoupin.top/Article/details/gtybfhxslb.html

[T18] Swift：字符串插值
来源：http://dali.fengsongda.top/Article/details/gtowxdogwi.html

"值: \(b)"
来源：http://dali.xuetiantiany.cn/Article/details/gtgmsxkjrz.html

[T19] Swift：可选绑定
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyopxcdwr.html

if let n = opt { print(n) }
来源：http://dali.hammf.cn/Article/details/gtpnfqbbir.html

[T20] Swift：数组操作
来源：http://dali.jqgufenzy.top/Article/details/gtavmjuxpc.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zhaomingkeji.xyz/Article/details/gthwcybuuz.html

[T21] Swift：遍历
来源：http://dali.xylfe.cn/Article/details/gtebbacyck.html

for x in a { print(x) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwtdzlyrm.html

[T22] Swift：字典
来源：http://dali.fzhhl.top/Article/details/gtnssflbeq.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.tianlin.xyz/Article/details/gtqssmmnep.html

[T23] Swift：函数
来源：http://dali.yuxming.cn/Article/details/gthglzubre.html

func add(_ a: Int, _ b: Int) -> Int { a + b }
来源：http://dali.zhaomingkeji.xyz/Article/details/gthvilsitj.html

[T24] Swift：闭包
来源：http://dali.shanyushiyangkeji.top/Article/details/gttywuwcyj.html

let f = { (x: Int) -> Int in x * 2 }
来源：http://dali.birdmap.top/Article/details/gtvkynuuoz.html

[T25] Swift：结构体
来源：http://dali.hywenlv.cn/Article/details/gtumedeico.html

struct P { var x: Int }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtddizmsyd.html

[T26] Swift：类与重写
来源：http://dali.birdmap.top/Article/details/gtmzsrhuiv.html

class A: Base { override func f() {} }
来源：http://dali.aizwys.cn/Article/details/gtyyhsjgao.html


<!-- 参考信息 -->