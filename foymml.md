代发 wailian999

arr=(a b c); echo "${arr[0]}"
来源：http://dali.dianchejie.cn/Article/details/gtnbkyakck.html

[R18] 遍历数组
来源：http://dali.iojbl.cn/Article/details/gtyjyyetay.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.haohaochexian.top/Article/details/gttgpfwbgh.html

[R19] 数组长度
来源：http://dali.snrcjt.cn/Article/details/gtiaqnisvy.html

echo "${#arr[@]}"
来源：http://dali.yj202588.top/Article/details/gtceiyhata.html

[R20] 关联数组（字典）
来源：http://dali.shuidangran.top/Article/details/gtaekvbhso.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cucudq.cn/Article/details/gtfewajuxl.html

[R21] 字符串长度
来源：http://dali.cqqwz.cn/Article/details/gtuwmtthcf.html

echo "${#s}"
来源：http://dali.gzhubu.top/Article/details/gtrqlevstn.html

[R22] 截取子串
来源：http://dali.shzxlz.cn/Article/details/gtccgbcurg.html

echo "${s:0:5}"
来源：http://dali.zhiwuduotai.top/Article/details/gtqsevmquq.html

[R23] 字符串替换
来源：http://dali.9152youxi.cn/Article/details/gtjlougtcx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hongshengwenyu.top/Article/details/gtakkpqvib.html

[R24] 大小写转换
来源：http://dali.quarkkingdee.top/Article/details/gterkehofh.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yanxiufei.cn/Article/details/gtolodptab.html

[R25] 去后缀 / 去前缀
来源：http://dali.dashuyun.cn/Article/details/gtfxtmfgih.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.snrcjt.cn/Article/details/gtncbuyvcv.html

[R26] 命令替换
来源：http://dali.kuanghao11.cn/Article/details/gtckuyqdzw.html

now=$(date +%F); echo "$now"
来源：http://dali.316326.xyz/Article/details/gtvjupaeqx.html

[R27] 算术展开
来源：http://dali.iojbl.cn/Article/details/gtmpiozbyt.html

echo $((1 + 2 * 3))
来源：http://dali.fengsongda.top/Article/details/gtdrtcxtjb.html

[R28] 浮点运算
来源：http://dali.ybcxt.top/Article/details/gtdhodoaxx.html

echo "scale=2; 10/3" | bc
来源：http://dali.guannengcc.top/Article/details/gtmaeltgwv.html

[R29] 定义函数
来源：http://dali.shangyingyoupin.top/Article/details/gttnqmkyjo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.chenzaomai.com/Article/details/gtjirrgeuo.html

[R30] 函数返回状态码
来源：http://dali.yongpay.top/Article/details/gtjohzcfux.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinqigfzy.top/Article/details/gtyhruomlf.html

[R31] 局部变量
来源：http://dali.tanke756.top/Article/details/gtxulthznl.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjbfjbnra.html

[R32] 参数个数校验
来源：http://dali.yuanzhike.top/Article/details/gtkgfrtldv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.snrcjt.cn/Article/details/gtcixgutpr.html

[R33] 捕获错误并提示行号
来源：http://dali.tianlin.xyz/Article/details/gtfbtqepfn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ppjwa.cn/Article/details/gtoxdegifu.html

[R34] 退出时清理
来源：http://dali.yonumen.top/Article/details/gtozdshhbk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.xinyue.icu/Article/details/gtriqaboua.html

[R35] 后台执行并等待
来源：http://dali.sxryk.cn/Article/details/gtbjkjtzpq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.chenjidiqi.icu/Article/details/gtspdaxnuy.html

[R36] 并发执行多个任务
来源：http://dali.ppjwa.cn/Article/details/gtkqcijihm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yuxming.cn/Article/details/gtykxbrcte.html

[R37] 把输出赋给变量
来源：http://dali.ehwqpu.com/Article/details/gtoeytudch.html

files=$(ls -1)
来源：http://dali.haohaochexian.top/Article/details/gtfvftcwkg.html

[R38] 管道串联
来源：http://dali.zhoulong.xyz/Article/details/gtsrkdodup.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shanyushiyangtech.top/Article/details/gtzeyznbnr.html

[R39] 重定向标准输出与错误
来源：http://dali.zycfv.cn/Article/details/gtosvokhoi.html

cmd > out.log 2>&1
来源：http://dali.yj20258888.top/Article/details/gtrkewbyjz.html

[R40] 追加写日志
来源：http://dali.iojbl.cn/Article/details/gtcytjrhmd.html

echo "log" >> out.log
来源：http://dali.wangdashe.top/Article/details/gtjibzjgty.html

[R41] 丢弃输出
来源：http://dali.wangdashe.top/Article/details/gthbnasjwe.html

cmd >/dev/null 2>&1
来源：http://dali.tianlin.xyz/Article/details/gtqmuqcydk.html

[R42] 输入重定向
来源：http://dali.meibo888.top/Article/details/gthvvlmgax.html

wc -l < a.txt
来源：http://dali.cheryme.top/Article/details/gtxbrzipbe.html

[R43] 按名字查找文件
来源：http://dali.gzhubu.top/Article/details/gtuwvzxxrv.html

find . -name "*.log" -type f
来源：http://dali.yuanzhike.top/Article/details/gtkwmxzpqc.html

[R44] 按修改时间查找
来源：http://dali.jlsjyb.cn/Article/details/gtqrxatzlm.html

find . -mtime -7 -type f
来源：http://dali.meibo888.top/Article/details/gturlorlcu.html

[R45] 批量删除
来源：http://dali.9152youxi.cn/Article/details/gtqlsihymm.html

find . -name "*.tmp" -delete
来源：http://dali.snrcjt.cn/Article/details/gtjanhhpib.html

[R46] 递归替换文件内容
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthlltrkpw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinghuilouyu.cn/Article/details/gtwjpofvvw.html

[R47] sed 单行替换
来源：http://dali.nanxuanxn.top/Article/details/gtnxsevtwd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gtizdymlwn.html

[R48] awk 取指定列
来源：http://dali.svipenyu.cn/Article/details/gtwgjgzmmw.html

awk '{print $1, $3}' a.txt
来源：http://dali.daxiang520.top/Article/details/gtyiiwglgd.html

[R49] awk 带条件
来源：http://dali.hammf.cn/Article/details/gtdtzhuthu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hywenlv.cn/Article/details/gtyhygzjfr.html

[R50] awk 求和
来源：http://dali.yvedp.cn/Article/details/gtkgliufcd.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yangfankeji.com/Article/details/gtjhlwpkxp.html

[R51] 排序去重取前几
来源：http://dali.iojbl.cn/Article/details/gthqmfctzm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yangfankeji.com/Article/details/gtesualhsk.html

[R52] 统计行数
来源：http://dali.hywenlv.cn/Article/details/gtwubvrytv.html

wc -l a.txt
来源：http://dali.jiagoushi.top/Article/details/gtglhxhqbf.html

[R53] 查看文件头与实时尾
来源：http://dali.shzxlz.cn/Article/details/gtgcnquvus.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.guowangkeji.top/Article/details/gtxjobedex.html

[R54] 比较两个文件
来源：http://dali.tian-w.cn/Article/details/gtjokrxomy.html

diff a.txt b.txt
来源：http://dali.andypj.xyz/Article/details/gtzahefkmp.html

[R55] 压缩与解压
来源：http://dali.zhongyouzk.top/Article/details/gtjmjclwou.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yj202588.top/Article/details/gtfcgctahz.html

[R56] 远程拷贝
来源：http://dali.svipenyu.cn/Article/details/gtpwrwtwuu.html

scp file user@host:/path/
来源：http://dali.daxiang520.top/Article/details/gtbbugaeqf.html

[R57] 远程执行命令
来源：http://dali.cqqwz.cn/Article/details/gtnodvxuzy.html

ssh user@host 'uptime'
来源：http://dali.shanyushiyangkeji.top/Article/details/gtoyonfayk.html

[R58] 下载文件
来源：http://dali.jinqigufen.top/Article/details/gtykccqkzn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gotoacloud.top/Article/details/gtqmvogvpd.html

[R59] 发 POST JSON
来源：http://dali.gzhubu.top/Article/details/gtppfkxopp.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xuanzx.com/Article/details/gtsbumqcpn.html

[R60] 只看 HTTP 状态码
来源：http://dali.yj20258888.top/Article/details/gthsrwhfei.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gotoacloud.top/Article/details/gtehrrcgbj.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gtexavajic.html

df -h;  du -sh *
来源：http://dali.jinyuanbaomall.cn/Article/details/gtttagikpp.html

[R62] 找最占空间的文件
来源：http://dali.ivvv.top/Article/details/gtnrigyftu.html

du -ah . | sort -rh | head -10
来源：http://dali.chenjidiqi.icu/Article/details/gtkpprzukh.html

[R63] 内存与进程
来源：http://dali.zhixingplan.top/Article/details/gtrklywbrh.html

free -h;  ps aux | grep nginx
来源：http://dali.ybcxt.top/Article/details/gtlphwuxnt.html

[R64] 结束进程
来源：http://dali.zhongyouzk.top/Article/details/gtywiouwbb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.tian-w.cn/Article/details/gtuiiqfovi.html

[R65] 查看端口占用
来源：http://dali.yuanzhike.top/Article/details/gtszikrjry.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.kuanghao11.cn/Article/details/gtojrqwxzm.html

[R66] 定时任务
来源：http://dali.jinghuilouyu.cn/Article/details/gtufjywame.html

crontab -e;  crontab -l
来源：http://dali.haohaochexian.top/Article/details/gttajjbase.html

[R67] 生成随机十六进制串
来源：http://dali.wangdashe.top/Article/details/gttagayqrh.html

openssl rand -hex 16
来源：http://dali.zycfv.cn/Article/details/gtaknbyuyr.html

[R68] 计算文件校验值
来源：http://dali.vqdsnc.cn/Article/details/gtpcbcsrpj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xuanzx.com/Article/details/gtsojcrxwj.html

[R69] 生成随机密码
来源：http://dali.hywenlv.cn/Article/details/gtfxqqkdym.html

head -c 16 /dev/urandom | base64
来源：http://dali.jiagoushi.top/Article/details/gtqvcoajch.html

[R70] 时间戳与互转
来源：http://dali.zhongyouzk.top/Article/details/gtpvcliteo.html

date +%s;  date -d @1700000000
来源：http://dali.feifeiyinyue.top/Article/details/gtqaotfmcs.html

[R71] 日期格式化
来源：http://dali.gaohongyu789.top/Article/details/gtqypuoemw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xylfe.cn/Article/details/gtevyldtgb.html

[R72] 等待端口就绪
来源：http://dali.gaohongyu789.top/Article/details/gtoftgugdg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.gogol.net.cn/Article/details/gtwjowxyvb.html

[R73] 分割大日志
来源：http://dali.redwolf501.top/Article/details/gtgmvcenfj.html

split -l 1000 big.log part_
来源：http://dali.hnxiangtu.top/Article/details/gtvzgrkrbh.html

[R74] 批量重命名
来源：http://dali.316326.xyz/Article/details/gtgbocempd.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtwimolsyt.html

[R75] 导出环境变量
来源：http://dali.316326.xyz/Article/details/gtvxwthqqv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.wangshuangyany.cn/Article/details/gtwpanzxvb.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gthagvovum.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.wangshuangyany.cn/Article/details/gtsnllrucp.html

[R77] 读取用户输入
来源：http://dali.nanxinkj.top/Article/details/gtkhoqnyde.html

read -rp "请输入: " ans
来源：http://dali.guowangkeji.top/Article/details/gtxmucsjxt.html

[R78] 交互式菜单
来源：http://dali.yj20258.top/Article/details/gtbtzgxane.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.andypj.xyz/Article/details/gtcihkyyfd.html

[R79] 解析命令行选项
来源：http://dali.yueranfly.top/Article/details/gtmzqjcxkn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.aizwys.cn/Article/details/gtyfgdwlxo.html

[R80] 查看脚本执行耗时
来源：http://dali.yanxiufei.cn/Article/details/gthjqddrri.html

time ./run.sh
来源：http://dali.yj202588.top/Article/details/gtfcxkjlif.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtvqkptrge.html

S. C / C++ 专题
来源：http://dali.hywenlv.cn/Article/details/gtuqnznpmv.html

================================================================================
来源：http://dali.shzxlz.cn/Article/details/gtgvwvfefm.html

[S01] C：Hello World
来源：http://dali.c1oappe.top/Article/details/gtiezbledp.html

#include <stdio.h>
来源：http://dali.gaohongyu789.top/Article/details/gtvzuxmwzv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.quarkkingdee.top/Article/details/gtiwcvnlfo.html

[S02] C：变量与格式化输出
来源：http://dali.nanxuanxn.top/Article/details/gtscgopghv.html

int a = 10; printf("%d\n", a);
来源：http://dali.yuxming.cn/Article/details/gtnclhwril.html

[S03] C：读入整数
来源：http://dali.ppjwa.cn/Article/details/gtyqoydjxr.html

int x; scanf("%d", &x);
来源：http://dali.chenzaomai.com/Article/details/gtfwnzkavm.html

[S04] C：字符串复制
来源：http://dali.tian-w.cn/Article/details/gtbgnebaai.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yj20258.top/Article/details/gtrqrlghaw.html

[S05] C：字符串长度
来源：http://dali.ydzc1.top/Article/details/gtsezdcklv.html

strlen(s)
来源：http://dali.pengpengdd.cyou/Article/details/gtrdaxvyww.html

[S06] C：字符串比较
来源：http://dali.zhixingplan.top/Article/details/gtedoktgdj.html

strcmp(a, b) == 0
来源：http://dali.yuanzhike.top/Article/details/gtdgeuwvpb.html

[S07] C：数组遍历求和
来源：http://dali.hfpthk.cn/Article/details/gtnmfxzned.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jianghu66.top/Article/details/gtrjehckql.html

[S08] C：动态内存分配与释放
来源：http://dali.316326.xyz/Article/details/gtniqjnhyk.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sysykeji.top/Article/details/gtpepwlxhw.html

[S09] C：结构体定义与初始化
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiuutajlb.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.vqdsnc.cn/Article/details/gtjzyghhwx.html

[S10] C：指针与解引用
来源：http://dali.chenjidiqi.icu/Article/details/gtkdnbqdzo.html

int *p = &a;  *p = 5;
来源：http://dali.nanxinkj.top/Article/details/gtfoufhuxm.html

[S11] C：逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gtlqvaimqv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.shuidangran.top/Article/details/gtdjhwnqjk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.meibo888.top/Article/details/gtpdcmmwur.html

fclose(f);
来源：http://dali.redwolf501.top/Article/details/gtdldslugd.html

[S12] C：写文件
来源：http://dali.cdnleiting.top/Article/details/gtdyffdauh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jinghuilouyu.cn/Article/details/gtfraztfhy.html

[S13] C：宏定义
来源：http://dali.chenjidiqi.icu/Article/details/gtimtmfkxy.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xuanzx.com/Article/details/gtwfajhtbg.html

[S14] C：枚举
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdkhiiglc.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jinqigufen.top/Article/details/gtxnlgbifc.html

[S15] C：类型转换
来源：http://dali.xuanzx.com/Article/details/gtppllllgn.html

(double) a / b
来源：http://dali.cucudq.cn/Article/details/gtmcgfbshv.html

[S16] C：位操作置位
来源：http://dali.guowangkeji.top/Article/details/gtanxttqtm.html

x |= (1 << 3);
来源：http://dali.ydzc1.top/Article/details/gtuxwofdnu.html

[S17] C：安全拼接字符串
来源：http://dali.mhx1999.top/Article/details/gtxonvsunc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.andypj.xyz/Article/details/gtnmjvqkzg.html

[S18] C：命令行参数
来源：http://dali.zdqjudy.top/Article/details/gtpsrgfgda.html

int main(int argc, char **argv)
来源：http://dali.ppjwa.cn/Article/details/gtyzsydqlh.html

[S19] C：快速排序
来源：http://dali.kuanghao11.cn/Article/details/gtjzkuyhxb.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.quarkkingdee.top/Article/details/gtwnxbavpn.html

[S20] C：二分查找
来源：http://dali.nanxinkj.top/Article/details/gtrzexedoc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.redwolf501.top/Article/details/gtmrczwmca.html

[S21] C：字符类别判断
来源：http://dali.jqgfzy.top/Article/details/gtdbxoryyl.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.ppjwa.cn/Article/details/gthzysuhud.html

[S22] C：字符串转数字
来源：http://dali.jiagoushi.top/Article/details/gtkpniossv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zycfv.cn/Article/details/gtutqmxccj.html

[S23] C：随机数
来源：http://dali.ybcxt.top/Article/details/gtwjwsrbxd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.feifeiyinyue.top/Article/details/gtoyqvghia.html

[S24] C：获取本地时间
来源：http://dali.nwbrower.top/Article/details/gtpmxqiolj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hammf.cn/Article/details/gtfkliubny.html

[S25] C：内存拷贝
来源：http://dali.tianlin.xyz/Article/details/gttnqxhrpc.html

memcpy(dst, src, n);
来源：http://dali.c1oappe.top/Article/details/gtwfuhbyof.html

[S26] C：内存清零
来源：http://dali.yongpay.top/Article/details/gtqoibnaqw.html

memset(a, 0, sizeof a);
来源：http://dali.tanke756.top/Article/details/gtlwsmamfl.html

[S27] C：定义常量
来源：http://dali.hfpthk.cn/Article/details/gtmnmkqqew.html

const double PI = 3.14159;
来源：http://dali.fzhhl.top/Article/details/gteecwrovm.html

[S28] C：静态变量
来源：http://dali.vqdsnc.cn/Article/details/gtnvcaatlo.html

static int counter = 0;
来源：http://dali.xinyue.icu/Article/details/gtrgvmmgyq.html

[S29] C：变参函数
来源：http://dali.ehwqpu.com/Article/details/gtfauomkfh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hnqzz.top/Article/details/gtjcxowzim.html

[S30] C：头文件保护
来源：http://dali.cashguo.top/Article/details/gthnmqnnzw.html

#ifndef X_H
来源：http://dali.nwbrower.top/Article/details/gtzqauehgd.html

#define X_H
来源：http://dali.hammf.cn/Article/details/gtjtndzkea.html

#endif
来源：http://dali.nanxuanxn.top/Article/details/gtowoyhawh.html

[S31] C++：Hello World
来源：http://dali.shangyingyoupin.top/Article/details/gtfrufapkf.html

#include <iostream>
来源：http://dali.snrcjt.cn/Article/details/gtfiuggcwj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.jinqigufen.top/Article/details/gtwndezray.html

[S32] C++：字符串
来源：http://dali.sufxvd.cn/Article/details/gtehigulxm.html

std::string s = "hi";  s += "!";
来源：http://dali.hongshengwenyu.top/Article/details/gtvsqolgvz.html

[S33] C++：vector 增删
来源：http://dali.shanyushiyangkeji.top/Article/details/gttwqpykot.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.shanyushiyangtech.top/Article/details/gtpuyopkwh.html

[S34] C++：遍历 vector
来源：http://dali.yuxming.cn/Article/details/gtsjoppcmn.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.nwbrower.top/Article/details/gtftiperjc.html

[S35] C++：map
来源：http://dali.zycfv.cn/Article/details/gtncvizqbn.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guannengcc.top/Article/details/gtsqlrgvho.html

[S36] C++：unordered_map
来源：http://dali.aizwys.cn/Article/details/gtygdktppz.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinqigufen.top/Article/details/gtelqbgwub.html

[S37] C++：set
来源：http://dali.xinyue.icu/Article/details/gteoobuxyc.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.gaohongyu789.top/Article/details/gtnzmazgbp.html

[S38] C++：排序
来源：http://dali.daria6918.cn/Article/details/gtkfceothw.html

std::sort(v.begin(), v.end());
来源：http://dali.shuidangran.top/Article/details/gtoccybmdq.html

[S39] C++：自定义比较器排序
来源：http://dali.0kj1m.cn/Article/details/gtwluuafyq.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.jianghu66.top/Article/details/gtvpjwxuah.html

[S40] C++：查找元素
来源：http://dali.0kj1m.cn/Article/details/gtraqyqlad.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ppjwa.cn/Article/details/gtrbgxvxpg.html

[S41] C++：类与构造函数
来源：http://dali.guowangkeji.top/Article/details/gtmssjpqci.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.nanxinkj.top/Article/details/gttlfnfhhb.html

[S42] C++：继承与虚函数
来源：http://dali.pengpengdd.cyou/Article/details/gtkwsbnqex.html

class B : public Base { public: void f() override {} };
来源：http://dali.ivvv.top/Article/details/gtojlgeaep.html

[S43] C++：智能指针
来源：http://dali.sweek.top/Article/details/gtwjewuiuc.html

auto p = std::make_unique<int>(5);
来源：http://dali.xziqi.cn/Article/details/gtkxwkniak.html

[S44] C++：引用传参
来源：http://dali.chenlongwang.top/Article/details/gtkmpoxxbr.html

void inc(int &x) { ++x; }
来源：http://dali.snrcjt.cn/Article/details/gtybffcusj.html

[S45] C++：lambda
来源：http://dali.yongpay.top/Article/details/gtknbpiehf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhiwuduotai.top/Article/details/gtlnnewelj.html

[S46] C++：函数模板
来源：http://dali.cqqwz.cn/Article/details/gtycjrxzvq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jqgfzy.top/Article/details/gtpsfyeqoi.html

[S47] C++：结构化绑定遍历
来源：http://dali.quarkkingdee.top/Article/details/gtrwwolqro.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.nanxinkj.top/Article/details/gtelzipmho.html

[S48] C++：逐行读文件
来源：http://dali.xziqi.cn/Article/details/gtwzmpgcjc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xuanzx.com/Article/details/gthpluxgrt.html

while (std::getline(in, line)) { }
来源：http://dali.jqgufenzy.top/Article/details/gtyvolsgbb.html

[S49] C++：写文件
来源：http://dali.zycfv.cn/Article/details/gtgsofnkrk.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.wangdashe.top/Article/details/gtsmlenkib.html

[S50] C++：格式化数字
来源：http://dali.shuidangran.top/Article/details/gtxtrjqrsx.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cheryme.top/Article/details/gttrwlqvve.html

[S51] C++：显式类型转换
来源：http://dali.pycfn.com/Article/details/gtjkmbksik.html

static_cast<double>(a) / b
来源：http://dali.jinqigufen.top/Article/details/gtrkxuyfvd.html

[S52] C++：const 与 noexcept
来源：http://dali.zhengqikj.top/Article/details/gtzpleogsz.html

int size() const noexcept { return n_; }
来源：http://dali.hysaishi.cn/Article/details/gtsukqzbrr.html

[S53] C++：移动语义
来源：http://dali.xuanzx.com/Article/details/gtkwjwfxas.html

std::vector<int> w = std::move(v);
来源：http://dali.mhx1999.top/Article/details/gtkyufeabb.html

[S54] C++：异常处理
来源：http://dali.yvedp.cn/Article/details/gtsoelaxsv.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.dianchejie.cn/Article/details/gtgvmxkyob.html

[S55] C++：结构化绑定
来源：http://dali.ydzc1.top/Article/details/gtlpgbbsvh.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.guowangkeji.top/Article/details/gtjigrzwjf.html

[S56] C++：optional
来源：http://dali.jlsjyb.cn/Article/details/gtntuoxcgr.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hywenlv.cn/Article/details/gtdofauohs.html

[S57] C++：编译期常量
来源：http://dali.sufxvd.cn/Article/details/gtlecqybmr.html

constexpr int N = 10;
来源：http://dali.zhongyouzk.top/Article/details/gtrgjvdbof.html

[S58] C++：命名空间
来源：http://dali.mhx1999.top/Article/details/gtwgzvzble.html

namespace ns { int f() { return 1; } }
来源：http://dali.dianchejie.cn/Article/details/gtoyvqddqy.html

[S59] C++：静态断言
来源：http://dali.hnxiangtu.top/Article/details/gtfdwxyctw.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zhiwuduotai.top/Article/details/gtfceotzey.html

[S60] C++：遍历并删除元素
来源：http://dali.yueranfly.top/Article/details/gtbnnavncm.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.redwolf501.top/Article/details/gtcoarllal.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtzorxvxup.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.chenlongwang.top/Article/details/gtvphjsqyf.html

================================================================================
来源：http://dali.c1oappe.top/Article/details/gtcwckyxsv.html

[T01] Kotlin：Hello World
来源：http://dali.hnxiangtu.top/Article/details/gtdyikvvhh.html

println("Hello")
来源：http://dali.yuanzhike.top/Article/details/gtkelourrd.html

[T02] Kotlin：变量
来源：http://dali.yuanzhike.top/Article/details/gtprmhrlat.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.tanke756.top/Article/details/gtlljrjhgx.html

[T03] Kotlin：字符串模板
来源：http://dali.havefunace.top/Article/details/gtnhawuhmv.html

"值: $b"
来源：http://dali.zhiwuduotai.top/Article/details/gtffnetryw.html

[T04] Kotlin：空安全
来源：http://dali.cashguo.top/Article/details/gtpomapsac.html

val n: String? = null;  n?.length
来源：http://dali.sufxvd.cn/Article/details/gtkgaehysg.html

[T05] Kotlin：when 表达式
来源：http://dali.vqdsnc.cn/Article/details/gtrjhwdxcz.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.svipenyu.cn/Article/details/gtzoyumbeg.html

[T06] Kotlin：集合映射
来源：http://dali.yj20258.top/Article/details/gtolgjsqcu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.hfpthk.cn/Article/details/gtpmnqeftk.html

[T07] Kotlin：集合过滤
来源：http://dali.ydzc1.top/Article/details/gtujsuuouq.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.chenzaomai.com/Article/details/gtsvqyidis.html

[T08] Kotlin：数据类
来源：http://dali.bjfxy.top/Article/details/gtngogewql.html

data class User(val name: String, val age: Int)
来源：http://dali.shangyingyoupin.top/Article/details/gtmxrbxcuz.html

[T09] Kotlin：扩展函数
来源：http://dali.dashuyun.cn/Article/details/gtquaufvyr.html

fun String.exclaim() = this + "!"
来源：http://dali.gotoacloud.top/Article/details/gtfsrzcsrf.html

[T10] Kotlin：默认参数
来源：http://dali.guowangkeji.top/Article/details/gtmervkfzn.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.9152youxi.cn/Article/details/gtjyfszvry.html

[T11] Kotlin：协程
来源：http://dali.sxryk.cn/Article/details/gtocgasehc.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.sufxvd.cn/Article/details/gtfugkhgqh.html

[T12] Kotlin：解构声明
来源：http://dali.daxiang520.top/Article/details/gtrnumxemw.html

val (a, b) = Pair(1, 2)
来源：http://dali.guannengcc.top/Article/details/gtvvjgpvgu.html

[T13] Kotlin：只读 Map
来源：http://dali.jinyuanbaomall.cn/Article/details/gtshrqxtai.html

val m = mapOf("a" to 1)
来源：http://dali.ehwqpu.com/Article/details/gtffwnnypg.html

[T14] Kotlin：循环
来源：http://dali.zdqjudy.top/Article/details/gtumpvfbws.html

for (i in 1..10) println(i)
来源：http://dali.ehwqpu.com/Article/details/gtkxqhvcis.html

[T15] Kotlin：接口
来源：http://dali.c1oappe.top/Article/details/gtkjzdcgwy.html

interface Shape { fun area(): Double }
来源：http://dali.ivvv.top/Article/details/gtjuefwmnf.html

[T16] Swift：Hello World
来源：http://dali.xziqi.cn/Article/details/gtwbrskqcz.html

print("Hello")
来源：http://dali.haohaochexian.top/Article/details/gtrustwevo.html

[T17] Swift：变量与常量
来源：http://dali.shzxlz.cn/Article/details/gtmbhksvnm.html

var a = 1;  let b = 2
来源：http://dali.iojbl.cn/Article/details/gtnmvlhuzp.html

[T18] Swift：字符串插值
来源：http://dali.tian-w.cn/Article/details/gtqgjyydgq.html

"值: \(b)"
来源：http://dali.yanxiufei.cn/Article/details/gtlocycmqf.html

[T19] Swift：可选绑定
来源：http://dali.sysykeji.top/Article/details/gtkoveutui.html

if let n = opt { print(n) }
来源：http://dali.ivvv.top/Article/details/gtiayurmzu.html

[T20] Swift：数组操作
来源：http://dali.chenzaomai.com/Article/details/gtpdxksinw.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.jinqigufen.top/Article/details/gtkrvacpea.html


<!-- 参考信息 -->