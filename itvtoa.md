代发 wailian999

echo "${#arr[@]}"
来源：http://dali.guowangkeji.top/Article/details/gtwxairrtv.html

[R20] 关联数组（字典）
来源：http://dali.wangshuangyany.cn/Article/details/gtxdclsonq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xinyue.icu/Article/details/gtbofxfrui.html

[R21] 字符串长度
来源：http://dali.jyoumei.cn/Article/details/gtzzytlhlo.html

echo "${#s}"
来源：http://dali.pycfn.com/Article/details/gtxdyrlexx.html

[R22] 截取子串
来源：http://dali.andypj.xyz/Article/details/gtiltcayds.html

echo "${s:0:5}"
来源：http://dali.daria6918.cn/Article/details/gtfweaxjhv.html

[R23] 字符串替换
来源：http://dali.wangshuangyany.cn/Article/details/gtfxzqdbzg.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.ydzc1.top/Article/details/gtyqejvxsd.html

[R24] 大小写转换
来源：http://dali.zhongyouzk.top/Article/details/gtreampnke.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.wangdashe.top/Article/details/gthdpufafi.html

[R25] 去后缀 / 去前缀
来源：http://dali.hongshengwenyu.top/Article/details/gtplpzpgaj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ivvv.top/Article/details/gtetpxblyh.html

[R26] 命令替换
来源：http://dali.iojbl.cn/Article/details/gthtcufdjn.html

now=$(date +%F); echo "$now"
来源：http://dali.tian-w.cn/Article/details/gtesqeokjv.html

[R27] 算术展开
来源：http://dali.zdqjudy.top/Article/details/gtgedxlkxk.html

echo $((1 + 2 * 3))
来源：http://dali.birdmap.top/Article/details/gtmwzbxcdm.html

[R28] 浮点运算
来源：http://dali.birdmap.top/Article/details/gtuqbyacll.html

echo "scale=2; 10/3" | bc
来源：http://dali.jyoumei.cn/Article/details/gttyendefi.html

[R29] 定义函数
来源：http://dali.iojbl.cn/Article/details/gtuucrjfeg.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hysaishi.cn/Article/details/gtpctwemtk.html

[R30] 函数返回状态码
来源：http://dali.xuanzx.com/Article/details/gtjwilrlui.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xylfe.cn/Article/details/gtnmuaanig.html

[R31] 局部变量
来源：http://dali.haohaochexian.top/Article/details/gtwgdgypvl.html

f() { local x=1; echo "$x"; }
来源：http://dali.bjfxy.top/Article/details/gtkodhslyz.html

[R32] 参数个数校验
来源：http://dali.nwbrower.top/Article/details/gtchizyrti.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yangfankeji.com/Article/details/gtqgysvnsz.html

[R33] 捕获错误并提示行号
来源：http://dali.aizwys.cn/Article/details/gtfdxbtbxz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sxryk.cn/Article/details/gtrpzldytx.html

[R34] 退出时清理
来源：http://dali.yanxiufei.cn/Article/details/gtvhbtxxay.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gotoacloud.top/Article/details/gtgzmxtubq.html

[R35] 后台执行并等待
来源：http://dali.hammf.cn/Article/details/gtegnyuzur.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jqgfzy.top/Article/details/gtpkvsndhl.html

[R36] 并发执行多个任务
来源：http://dali.shzxlz.cn/Article/details/gtbsqamryh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hongshengwenyu.top/Article/details/gtpvbzssfw.html

[R37] 把输出赋给变量
来源：http://dali.cucudq.cn/Article/details/gtifgblflc.html

files=$(ls -1)
来源：http://dali.yj20258888.top/Article/details/gtuaiotoow.html

[R38] 管道串联
来源：http://dali.gaohongyu789.top/Article/details/gtjbabnrga.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ivvv.top/Article/details/gtsolsftpo.html

[R39] 重定向标准输出与错误
来源：http://dali.tian-w.cn/Article/details/gtuuaepeow.html

cmd > out.log 2>&1
来源：http://dali.jiagoushi.top/Article/details/gtezdpxaxz.html

[R40] 追加写日志
来源：http://dali.xinyue.icu/Article/details/gtzzrybdvo.html

echo "log" >> out.log
来源：http://dali.sxryk.cn/Article/details/gtpvgchbak.html

[R41] 丢弃输出
来源：http://dali.cheryme.top/Article/details/gtwpkcjfah.html

cmd >/dev/null 2>&1
来源：http://dali.shzxlz.cn/Article/details/gteuvixnqx.html

[R42] 输入重定向
来源：http://dali.yuanzhike.top/Article/details/gtyvzeewyr.html

wc -l < a.txt
来源：http://dali.nanxinkj.top/Article/details/gtqdxmeler.html

[R43] 按名字查找文件
来源：http://dali.yongpay.top/Article/details/gtlcmqhait.html

find . -name "*.log" -type f
来源：http://dali.daria6918.cn/Article/details/gtpwjlsbnv.html

[R44] 按修改时间查找
来源：http://dali.cdnleiting.top/Article/details/gtuxibwqzz.html

find . -mtime -7 -type f
来源：http://dali.yj202588.top/Article/details/gtgfxkyxum.html

[R45] 批量删除
来源：http://dali.gzhubu.top/Article/details/gtyzmxjyfp.html

find . -name "*.tmp" -delete
来源：http://dali.nanxinkj.top/Article/details/gtvxpapasj.html

[R46] 递归替换文件内容
来源：http://dali.yj20258888.top/Article/details/gthzfdbvao.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yuanzhike.top/Article/details/gtzajwutat.html

[R47] sed 单行替换
来源：http://dali.redwolf501.top/Article/details/gteshysjyi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cashguo.top/Article/details/gtwdlvwyrw.html

[R48] awk 取指定列
来源：http://dali.tian-w.cn/Article/details/gtlodwmdvj.html

awk '{print $1, $3}' a.txt
来源：http://dali.cucudq.cn/Article/details/gtsszffmky.html

[R49] awk 带条件
来源：http://dali.yueranfly.top/Article/details/gtxfunqkgp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hnxiangtu.top/Article/details/gtikfswwak.html

[R50] awk 求和
来源：http://dali.gaohongyu789.top/Article/details/gttvofohzo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtvtbkktuc.html

[R51] 排序去重取前几
来源：http://dali.hywenlv.cn/Article/details/gtekuxokne.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yj20258.top/Article/details/gtxnsswxfk.html

[R52] 统计行数
来源：http://dali.sweek.top/Article/details/gtqdaxphyt.html

wc -l a.txt
来源：http://dali.yj20258888.top/Article/details/gteicimaqa.html

[R53] 查看文件头与实时尾
来源：http://dali.xinyue.icu/Article/details/gtpfbgosqj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jqgfzy.top/Article/details/gtzvllgcnx.html

[R54] 比较两个文件
来源：http://dali.gotoacloud.top/Article/details/gtpcxbaqbl.html

diff a.txt b.txt
来源：http://dali.smart0.xyz/Article/details/gtlughclyu.html

[R55] 压缩与解压
来源：http://dali.yuanzhike.top/Article/details/gtnatckoci.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jqgufenzy.top/Article/details/gtobwrgggu.html

[R56] 远程拷贝
来源：http://dali.zycfv.cn/Article/details/gtsrabqlux.html

scp file user@host:/path/
来源：http://dali.0kj1m.cn/Article/details/gtibfjalli.html

[R57] 远程执行命令
来源：http://dali.dashuyun.cn/Article/details/gtpcgppfon.html

ssh user@host 'uptime'
来源：http://dali.hnxiangtu.top/Article/details/gtxesvexam.html

[R58] 下载文件
来源：http://dali.ybcxt.top/Article/details/gtlfwtlftu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.dashuyun.cn/Article/details/gteswcqacf.html

[R59] 发 POST JSON
来源：http://dali.daxiang520.top/Article/details/gtebhghtcm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.haohaochexian.top/Article/details/gtopnxglmu.html

[R60] 只看 HTTP 状态码
来源：http://dali.dashuyun.cn/Article/details/gtivoqiwhh.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.nanxuanxn.top/Article/details/gtxptapzqr.html

[R61] 磁盘占用
来源：http://dali.daria6918.cn/Article/details/gtpobjramc.html

df -h;  du -sh *
来源：http://dali.gzhubu.top/Article/details/gtnebqrnih.html

[R62] 找最占空间的文件
来源：http://dali.bjfxy.top/Article/details/gtcoyzemcl.html

du -ah . | sort -rh | head -10
来源：http://dali.quarkkingdee.top/Article/details/gtizmhydsi.html

[R63] 内存与进程
来源：http://dali.hammf.cn/Article/details/gttdpwxeum.html

free -h;  ps aux | grep nginx
来源：http://dali.andypj.xyz/Article/details/gthelhjkuw.html

[R64] 结束进程
来源：http://dali.tian-w.cn/Article/details/gtzytpzxoo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzgxmjmeg.html

[R65] 查看端口占用
来源：http://dali.sysykeji.top/Article/details/gtedkyvhoy.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.dashuyun.cn/Article/details/gtsnddtvjy.html

[R66] 定时任务
来源：http://dali.gotoacloud.top/Article/details/gticdqxgnp.html

crontab -e;  crontab -l
来源：http://dali.jyoumei.cn/Article/details/gtsodjwrbs.html

[R67] 生成随机十六进制串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwlglgwcr.html

openssl rand -hex 16
来源：http://dali.yuxming.cn/Article/details/gtnzvjndxj.html

[R68] 计算文件校验值
来源：http://dali.gogol.net.cn/Article/details/gtjcghoeqv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xinyue.icu/Article/details/gtxxpumwzh.html

[R69] 生成随机密码
来源：http://dali.feifeiyinyue.top/Article/details/gtsrkiudhx.html

head -c 16 /dev/urandom | base64
来源：http://dali.sweek.top/Article/details/gtjyhhupyj.html

[R70] 时间戳与互转
来源：http://dali.bjfxy.top/Article/details/gtdyvavbap.html

date +%s;  date -d @1700000000
来源：http://dali.snrcjt.cn/Article/details/gttzqvdaql.html

[R71] 日期格式化
来源：http://dali.jiagoushi.top/Article/details/gtfzzjkdhq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.snrcjt.cn/Article/details/gtijakkuln.html

[R72] 等待端口就绪
来源：http://dali.jlsjyb.cn/Article/details/gtqeybcgkk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yangfankeji.com/Article/details/gtwexjlbhl.html

[R73] 分割大日志
来源：http://dali.vqdsnc.cn/Article/details/gtedgmmavs.html

split -l 1000 big.log part_
来源：http://dali.zhengqikj.top/Article/details/gtzrgjsets.html

[R74] 批量重命名
来源：http://dali.yvedp.cn/Article/details/gtxzzmrhdb.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sweek.top/Article/details/gtdjaxqkzx.html

[R75] 导出环境变量
来源：http://dali.cheryme.top/Article/details/gthoskibvh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.iojbl.cn/Article/details/gtvcgzlphz.html

[R76] 使用临时文件
来源：http://dali.chenjidiqi.icu/Article/details/gttorybjmn.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhengqikj.top/Article/details/gteefdtosc.html

[R77] 读取用户输入
来源：http://dali.pycfn.com/Article/details/gthqlsivqu.html

read -rp "请输入: " ans
来源：http://dali.tanke756.top/Article/details/gtiwqmkrsg.html

[R78] 交互式菜单
来源：http://dali.tianlin.xyz/Article/details/gtrbyxapgc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.aibaodan.cn/Article/details/gtwfghatrl.html

[R79] 解析命令行选项
来源：http://dali.jinghuilouyu.cn/Article/details/gtcwjnsigp.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yuxming.cn/Article/details/gtfnolfzwv.html

[R80] 查看脚本执行耗时
来源：http://dali.316326.xyz/Article/details/gtfmefoglj.html

time ./run.sh
来源：http://dali.yangfankeji.com/Article/details/gtuygknxxp.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtqrrhqzdw.html

S. C / C++ 专题
来源：http://dali.gzhubu.top/Article/details/gtjykcqxfh.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrrrqrshq.html

[S01] C：Hello World
来源：http://dali.fzhhl.top/Article/details/gtbcqwlexr.html

#include <stdio.h>
来源：http://dali.hammf.cn/Article/details/gtltbairhe.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.feifeiyinyue.top/Article/details/gtcmxchqny.html

[S02] C：变量与格式化输出
来源：http://dali.yongpay.top/Article/details/gtdtalggti.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhoulong.xyz/Article/details/gtntsglixq.html

[S03] C：读入整数
来源：http://dali.jinqigfzy.top/Article/details/gthlrphvql.html

int x; scanf("%d", &x);
来源：http://dali.sxryk.cn/Article/details/gtsjiolbon.html

[S04] C：字符串复制
来源：http://dali.yangfankeji.com/Article/details/gtwwzvupmy.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhiwuduotai.top/Article/details/gtqivvujkw.html

[S05] C：字符串长度
来源：http://dali.pycfn.com/Article/details/gtezgfxnbj.html

strlen(s)
来源：http://dali.fengsongda.top/Article/details/gtbymeudak.html

[S06] C：字符串比较
来源：http://dali.jinqigfzy.top/Article/details/gtbbuelmxi.html

strcmp(a, b) == 0
来源：http://dali.zhoulong.xyz/Article/details/gtxdjbgmcx.html

[S07] C：数组遍历求和
来源：http://dali.sufxvd.cn/Article/details/gtzkyogdtm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.svipenyu.cn/Article/details/gtukwhmvzd.html

[S08] C：动态内存分配与释放
来源：http://dali.tanke756.top/Article/details/gtqwktmxrz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.dianchejie.cn/Article/details/gtmckcgfsk.html

[S09] C：结构体定义与初始化
来源：http://dali.birdmap.top/Article/details/gtagalkqqf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.tian-w.cn/Article/details/gthbzhiyvs.html

[S10] C：指针与解引用
来源：http://dali.daria6918.cn/Article/details/gtjzyjxsbe.html

int *p = &a;  *p = 5;
来源：http://dali.zhengqikj.top/Article/details/gtyodxfyuq.html

[S11] C：逐行读文件
来源：http://dali.shuidangran.top/Article/details/gthbhfhuej.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.daria6918.cn/Article/details/gttqrqfipr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.shuidangran.top/Article/details/gtueigrsgr.html

fclose(f);
来源：http://dali.gaohongyu789.top/Article/details/gtgqhndbor.html

[S12] C：写文件
来源：http://dali.pengpengdd.cyou/Article/details/gtzuuvbkxj.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.wangdashe.top/Article/details/gtjarqnjja.html

[S13] C：宏定义
来源：http://dali.guannengcc.top/Article/details/gtablxznhb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.svipenyu.cn/Article/details/gtcuuwnued.html

[S14] C：枚举
来源：http://dali.smart0.xyz/Article/details/gtleffxehj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yj20258.top/Article/details/gtbwhxgurp.html

[S15] C：类型转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcntwerna.html

(double) a / b
来源：http://dali.svipenyu.cn/Article/details/gtlzwsrxpo.html

[S16] C：位操作置位
来源：http://dali.xylfe.cn/Article/details/gteivtxcnv.html

x |= (1 << 3);
来源：http://dali.chenzaomai.com/Article/details/gtfpysscdc.html

[S17] C：安全拼接字符串
来源：http://dali.xuanzx.com/Article/details/gthrtubeib.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhoulong.xyz/Article/details/gtaivcbbfr.html

[S18] C：命令行参数
来源：http://dali.yueranfly.top/Article/details/gttejmrbpj.html

int main(int argc, char **argv)
来源：http://dali.316326.xyz/Article/details/gttcltidto.html

[S19] C：快速排序
来源：http://dali.pycfn.com/Article/details/gtpygreouw.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.shangyingyoupin.top/Article/details/gtimbthbza.html

[S20] C：二分查找
来源：http://dali.havefunace.top/Article/details/gtxtodoybq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinghuilouyu.cn/Article/details/gtdltijnhx.html

[S21] C：字符类别判断
来源：http://dali.snrcjt.cn/Article/details/gtgwdmwcih.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.chenjidiqi.icu/Article/details/gtccdixabe.html

[S22] C：字符串转数字
来源：http://dali.pycfn.com/Article/details/gtkrljjrww.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.daria6918.cn/Article/details/gtsjjidnap.html

[S23] C：随机数
来源：http://dali.nwbrower.top/Article/details/gtiowwftep.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrmarqyun.html

[S24] C：获取本地时间
来源：http://dali.snrcjt.cn/Article/details/gttjluimot.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ppjwa.cn/Article/details/gtbxpjvyhl.html

[S25] C：内存拷贝
来源：http://dali.xuetiantiany.cn/Article/details/gtehuostcu.html

memcpy(dst, src, n);
来源：http://dali.nanxuanxn.top/Article/details/gttrmqbnng.html

[S26] C：内存清零
来源：http://dali.yuanzhike.top/Article/details/gtpwosirqp.html

memset(a, 0, sizeof a);
来源：http://dali.ydzc1.top/Article/details/gtkhsuzjcp.html

[S27] C：定义常量
来源：http://dali.bjfxy.top/Article/details/gtdgddycxa.html

const double PI = 3.14159;
来源：http://dali.tianlin.xyz/Article/details/gtflxarbcj.html

[S28] C：静态变量
来源：http://dali.yvedp.cn/Article/details/gtyzqzggya.html

static int counter = 0;
来源：http://dali.iojbl.cn/Article/details/gtehrvwcgd.html

[S29] C：变参函数
来源：http://dali.nanxuanxn.top/Article/details/gtraycecew.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.gotoacloud.top/Article/details/gttibrkniw.html

[S30] C：头文件保护
来源：http://dali.zhixingplan.top/Article/details/gtsgqrgtae.html

#ifndef X_H
来源：http://dali.shuidangran.top/Article/details/gtpkhjguzc.html

#define X_H
来源：http://dali.zhiwuduotai.top/Article/details/gtgxioojmk.html

#endif
来源：http://dali.yvedp.cn/Article/details/gtdpuxbtpi.html

[S31] C++：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtrjnmrafs.html

#include <iostream>
来源：http://dali.316326.xyz/Article/details/gtneulhvlp.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cheryme.top/Article/details/gtqdzlqtvk.html

[S32] C++：字符串
来源：http://dali.haohaochexian.top/Article/details/gtyekmqfmp.html

std::string s = "hi";  s += "!";
来源：http://dali.shzxlz.cn/Article/details/gtorybcrkx.html

[S33] C++：vector 增删
来源：http://dali.aibaodan.cn/Article/details/gtlbeszrto.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.bjfxy.top/Article/details/gtvfuffdwc.html

[S34] C++：遍历 vector
来源：http://dali.xuetiantiany.cn/Article/details/gtqgtlqioc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.jyoumei.cn/Article/details/gtjfozeivv.html

[S35] C++：map
来源：http://dali.aizwys.cn/Article/details/gtayhcmfma.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.wangdashe.top/Article/details/gtluoaunha.html

[S36] C++：unordered_map
来源：http://dali.sxryk.cn/Article/details/gthlaazgfc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ydzc1.top/Article/details/gtfrdjfija.html

[S37] C++：set
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnxwxfhut.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.meibo888.top/Article/details/gtwiwoicba.html

[S38] C++：排序
来源：http://dali.zhengqikj.top/Article/details/gtbacdwcra.html

std::sort(v.begin(), v.end());
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxwbcwikz.html

[S39] C++：自定义比较器排序
来源：http://dali.jinqigfzy.top/Article/details/gtljvojodm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yj20258.top/Article/details/gtdvuatgnm.html

[S40] C++：查找元素
来源：http://dali.redwolf501.top/Article/details/gtjsyddhbv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbkffovlf.html

[S41] C++：类与构造函数
来源：http://dali.jlsjyb.cn/Article/details/gtxaivbwhu.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.xziqi.cn/Article/details/gtyzoavujy.html

[S42] C++：继承与虚函数
来源：http://dali.sweek.top/Article/details/gtlrcqulto.html

class B : public Base { public: void f() override {} };
来源：http://dali.aizwys.cn/Article/details/gtbqgxnzls.html

[S43] C++：智能指针
来源：http://dali.ivvv.top/Article/details/gtjvxptgsv.html

auto p = std::make_unique<int>(5);
来源：http://dali.chenjidiqi.icu/Article/details/gtatevmemn.html

[S44] C++：引用传参
来源：http://dali.0kj1m.cn/Article/details/gtwjifgjow.html

void inc(int &x) { ++x; }
来源：http://dali.fzhhl.top/Article/details/gtnizlrkjp.html

[S45] C++：lambda
来源：http://dali.cucudq.cn/Article/details/gtbhcqamnw.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwihbakjd.html

[S46] C++：函数模板
来源：http://dali.fengsongda.top/Article/details/gtbrgypbex.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cheryme.top/Article/details/gtfpfhwvjc.html

[S47] C++：结构化绑定遍历
来源：http://dali.sweek.top/Article/details/gtznwyaeds.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yuxming.cn/Article/details/gtdmrztvrq.html

[S48] C++：逐行读文件
来源：http://dali.hammf.cn/Article/details/gthjnbohbq.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.316326.xyz/Article/details/gtsaqhjeew.html

while (std::getline(in, line)) { }
来源：http://dali.iojbl.cn/Article/details/gtmczdyggk.html

[S49] C++：写文件
来源：http://dali.svipenyu.cn/Article/details/gtsgctdnqn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.yongpay.top/Article/details/gtfavlzooj.html

[S50] C++：格式化数字
来源：http://dali.wangshuangyany.cn/Article/details/gtpleeiyyt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.ydzc1.top/Article/details/gteovfhfbd.html

[S51] C++：显式类型转换
来源：http://dali.daria6918.cn/Article/details/gtztgpxcge.html

static_cast<double>(a) / b
来源：http://dali.ehwqpu.com/Article/details/gtitsxukpb.html

[S52] C++：const 与 noexcept
来源：http://dali.fzhhl.top/Article/details/gtdxvucaxj.html

int size() const noexcept { return n_; }
来源：http://dali.zhoulong.xyz/Article/details/gttyqnukgd.html

[S53] C++：移动语义
来源：http://dali.birdmap.top/Article/details/gttvzfsked.html

std::vector<int> w = std::move(v);
来源：http://dali.nanxinkj.top/Article/details/gtzhomilvo.html

[S54] C++：异常处理
来源：http://dali.chenjidiqi.icu/Article/details/gtudhohtzd.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.chenlongwang.top/Article/details/gtcmupxfvf.html

[S55] C++：结构化绑定
来源：http://dali.havefunace.top/Article/details/gtdiirbcyp.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hysaishi.cn/Article/details/gtmdzgrisc.html

[S56] C++：optional
来源：http://dali.jinqigfzy.top/Article/details/gteibmijbu.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttwnejqss.html

[S57] C++：编译期常量
来源：http://dali.shzxlz.cn/Article/details/gtudzykoyw.html

constexpr int N = 10;
来源：http://dali.iojbl.cn/Article/details/gtxyqbeerl.html

[S58] C++：命名空间
来源：http://dali.xinyue.icu/Article/details/gtxiffiwew.html

namespace ns { int f() { return 1; } }
来源：http://dali.vqdsnc.cn/Article/details/gttcjwppyc.html

[S59] C++：静态断言
来源：http://dali.yueranfly.top/Article/details/gtmifmfcwi.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.shanyushiyangtech.top/Article/details/gtuymztnzd.html

[S60] C++：遍历并删除元素
来源：http://dali.dianchejie.cn/Article/details/gtzqwqzoad.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.nanxinkj.top/Article/details/gtbrgobmsu.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtqcddnkzh.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ppjwa.cn/Article/details/gtixknxnbs.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtkmyazxhp.html

[T01] Kotlin：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtdzubrshw.html

println("Hello")
来源：http://dali.yj20258888.top/Article/details/gtobarssam.html

[T02] Kotlin：变量
来源：http://dali.jqgfzy.top/Article/details/gtcnfgfzyb.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.yanxiufei.cn/Article/details/gtpsccllrs.html

[T03] Kotlin：字符串模板
来源：http://dali.redwolf501.top/Article/details/gtlkvrmuku.html

"值: $b"
来源：http://dali.nwbrower.top/Article/details/gtlxpckyav.html

[T04] Kotlin：空安全
来源：http://dali.ehwqpu.com/Article/details/gtnmihqobd.html

val n: String? = null;  n?.length
来源：http://dali.shangyingyoupin.top/Article/details/gttdzwhxss.html

[T05] Kotlin：when 表达式
来源：http://dali.nanxinkj.top/Article/details/gtkyhodirl.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.chenlongwang.top/Article/details/gteotqmcwp.html

[T06] Kotlin：集合映射
来源：http://dali.nanxuanxn.top/Article/details/gtutckddck.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gotoacloud.top/Article/details/gtfgbhaeas.html

[T07] Kotlin：集合过滤
来源：http://dali.snrcjt.cn/Article/details/gttovclvue.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.cucudq.cn/Article/details/gtpiumanqa.html

[T08] Kotlin：数据类
来源：http://dali.kuanghao11.cn/Article/details/gthffudieh.html

data class User(val name: String, val age: Int)
来源：http://dali.316326.xyz/Article/details/gthdarddgo.html

[T09] Kotlin：扩展函数
来源：http://dali.chenzaomai.com/Article/details/gtcecmvwdg.html

fun String.exclaim() = this + "!"
来源：http://dali.jlsjyb.cn/Article/details/gtaaygtqse.html

[T10] Kotlin：默认参数
来源：http://dali.yj20258.top/Article/details/gtypaffbco.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.cdnleiting.top/Article/details/gtxtxirblk.html

[T11] Kotlin：协程
来源：http://dali.jinyuanbaomall.cn/Article/details/gtydlbobww.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.chenlongwang.top/Article/details/gtdcioqaxr.html

[T12] Kotlin：解构声明
来源：http://dali.cashguo.top/Article/details/gtqzimqrxv.html

val (a, b) = Pair(1, 2)
来源：http://dali.zycfv.cn/Article/details/gtxehuqrcl.html

[T13] Kotlin：只读 Map
来源：http://dali.ivvv.top/Article/details/gtmdbsnwdc.html

val m = mapOf("a" to 1)
来源：http://dali.zhongyouzk.top/Article/details/gtohkdepxb.html

[T14] Kotlin：循环
来源：http://dali.yueranfly.top/Article/details/gtappfkelh.html

for (i in 1..10) println(i)
来源：http://dali.chenjidiqi.icu/Article/details/gtgcicbfei.html

[T15] Kotlin：接口
来源：http://dali.jinqigufen.top/Article/details/gtkiqhvsmy.html

interface Shape { fun area(): Double }
来源：http://dali.jlsjyb.cn/Article/details/gtpyjneblq.html

[T16] Swift：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtgrjifrol.html

print("Hello")
来源：http://dali.yvedp.cn/Article/details/gtochczddz.html

[T17] Swift：变量与常量
来源：http://dali.xziqi.cn/Article/details/gtsqoelnyc.html

var a = 1;  let b = 2
来源：http://dali.jianghu66.top/Article/details/gtvdjwoeya.html

[T18] Swift：字符串插值
来源：http://dali.tianlin.xyz/Article/details/gtgxmpqmgm.html

"值: \(b)"
来源：http://dali.kuanghao11.cn/Article/details/gtlrwtrcwh.html

[T19] Swift：可选绑定
来源：http://dali.andypj.xyz/Article/details/gtkxixgtii.html

if let n = opt { print(n) }
来源：http://dali.aibaodan.cn/Article/details/gtubgtchgt.html

[T20] Swift：数组操作
来源：http://dali.xinyue.icu/Article/details/gtzlqzgqra.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.yj20258888.top/Article/details/gtcapnogme.html

[T21] Swift：遍历
来源：http://dali.haohaochexian.top/Article/details/gtefwglpbm.html

for x in a { print(x) }
来源：http://dali.jiagoushi.top/Article/details/gtjjkxniip.html

[T22] Swift：字典
来源：http://dali.nanxinkj.top/Article/details/gtsdhpjhnk.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.ivvv.top/Article/details/gtlfjkkiid.html


<!-- 参考信息 -->