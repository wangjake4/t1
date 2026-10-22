代发 wailian999

echo "${#arr[@]}"
来源：http://dali.yuanzhike.top/Article/details/gtllkiymqn.html

[R20] 关联数组（字典）
来源：http://dali.tian-w.cn/Article/details/gtltzpkecz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.chenjidiqi.icu/Article/details/gtkcenwvpn.html

[R21] 字符串长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsedwcnit.html

echo "${#s}"
来源：http://dali.xziqi.cn/Article/details/gtrqzwbemh.html

[R22] 截取子串
来源：http://dali.mhx1999.top/Article/details/gtkyfolcew.html

echo "${s:0:5}"
来源：http://dali.shangyingyoupin.top/Article/details/gtfymnvmvy.html

[R23] 字符串替换
来源：http://dali.xuanzx.com/Article/details/gtpjufajss.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.dianchejie.cn/Article/details/gtzmsqgrna.html

[R24] 大小写转换
来源：http://dali.hammf.cn/Article/details/gtcphgktti.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhoulong.xyz/Article/details/gtoiscrlpb.html

[R25] 去后缀 / 去前缀
来源：http://dali.pycfn.com/Article/details/gtwgufyslp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.chenlongwang.top/Article/details/gtivnxdxas.html

[R26] 命令替换
来源：http://dali.jinqigufen.top/Article/details/gtettlxhyq.html

now=$(date +%F); echo "$now"
来源：http://dali.hysaishi.cn/Article/details/gtokvblcsm.html

[R27] 算术展开
来源：http://dali.zdqjudy.top/Article/details/gtvjjseiev.html

echo $((1 + 2 * 3))
来源：http://dali.316326.xyz/Article/details/gtlmbklele.html

[R28] 浮点运算
来源：http://dali.zhiwuduotai.top/Article/details/gtaonnhhwl.html

echo "scale=2; 10/3" | bc
来源：http://dali.c1oappe.top/Article/details/gthusxjpmx.html

[R29] 定义函数
来源：http://dali.wangshuangyany.cn/Article/details/gtngdculqe.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.smart0.xyz/Article/details/gtvuyzvqjx.html

[R30] 函数返回状态码
来源：http://dali.snrcjt.cn/Article/details/gtvqkrgywu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjcichktc.html

[R31] 局部变量
来源：http://dali.dashuyun.cn/Article/details/gtsezhuuat.html

f() { local x=1; echo "$x"; }
来源：http://dali.gaohongyu789.top/Article/details/gtqxyvksjo.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gthfaydnwv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.bjfxy.top/Article/details/gtslbwbhqy.html

[R33] 捕获错误并提示行号
来源：http://dali.daria6918.cn/Article/details/gtdoobjgte.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.bjfxy.top/Article/details/gtqcytojdt.html

[R34] 退出时清理
来源：http://dali.nanxuanxn.top/Article/details/gtapzyxaqu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.guannengcc.top/Article/details/gtrsdbmidc.html

[R35] 后台执行并等待
来源：http://dali.mhx1999.top/Article/details/gtmbvazvkf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yueranfly.top/Article/details/gtwshbjvkr.html

[R36] 并发执行多个任务
来源：http://dali.fzhhl.top/Article/details/gtxzckbnhx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.snrcjt.cn/Article/details/gtatzndsfi.html

[R37] 把输出赋给变量
来源：http://dali.mhx1999.top/Article/details/gtiejhepqh.html

files=$(ls -1)
来源：http://dali.ydzc1.top/Article/details/gtjymwkwpf.html

[R38] 管道串联
来源：http://dali.yj20258888.top/Article/details/gtwhvdwifg.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xuetiantiany.cn/Article/details/gteipkqcpo.html

[R39] 重定向标准输出与错误
来源：http://dali.ehwqpu.com/Article/details/gtoklpoipd.html

cmd > out.log 2>&1
来源：http://dali.tianlin.xyz/Article/details/gtblbdpclk.html

[R40] 追加写日志
来源：http://dali.hnqzz.top/Article/details/gtegfujpzq.html

echo "log" >> out.log
来源：http://dali.ppjwa.cn/Article/details/gtlccunycg.html

[R41] 丢弃输出
来源：http://dali.yongpay.top/Article/details/gtymdibrml.html

cmd >/dev/null 2>&1
来源：http://dali.aibaodan.cn/Article/details/gtdlljrgav.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gtgyormhba.html

wc -l < a.txt
来源：http://dali.quarkkingdee.top/Article/details/gttvvcpvjl.html

[R43] 按名字查找文件
来源：http://dali.guannengcc.top/Article/details/gtffjbupec.html

find . -name "*.log" -type f
来源：http://dali.jianghu66.top/Article/details/gtacgjpstc.html

[R44] 按修改时间查找
来源：http://dali.ywan-chungtsiang.top/Article/details/gtenddneci.html

find . -mtime -7 -type f
来源：http://dali.sweek.top/Article/details/gtngtpabfu.html

[R45] 批量删除
来源：http://dali.dashuyun.cn/Article/details/gtjmddttvl.html

find . -name "*.tmp" -delete
来源：http://dali.dianchejie.cn/Article/details/gteibjnsas.html

[R46] 递归替换文件内容
来源：http://dali.yvedp.cn/Article/details/gtaqfuatdi.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhoulong.xyz/Article/details/gtbogkqgtb.html

[R47] sed 单行替换
来源：http://dali.wangshuangyany.cn/Article/details/gtcegipzve.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtmkpyqenb.html

[R48] awk 取指定列
来源：http://dali.zhoulong.xyz/Article/details/gtgowzlypi.html

awk '{print $1, $3}' a.txt
来源：http://dali.pycfn.com/Article/details/gtjuqxlzib.html

[R49] awk 带条件
来源：http://dali.fengsongda.top/Article/details/gtaighihgk.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.aibaodan.cn/Article/details/gtkjbxlnzk.html

[R50] awk 求和
来源：http://dali.jinqigufen.top/Article/details/gtbdbygcis.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.vqdsnc.cn/Article/details/gtyawetjjm.html

[R51] 排序去重取前几
来源：http://dali.jianghu66.top/Article/details/gtjkqfiaiq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xuetiantiany.cn/Article/details/gtsukwobqv.html

[R52] 统计行数
来源：http://dali.yangfankeji.com/Article/details/gtcsvlgmaz.html

wc -l a.txt
来源：http://dali.yj202588.top/Article/details/gtcxokdjdw.html

[R53] 查看文件头与实时尾
来源：http://dali.pycfn.com/Article/details/gtwcedfuiw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.chenlongwang.top/Article/details/gtaimxobkq.html

[R54] 比较两个文件
来源：http://dali.kuanghao11.cn/Article/details/gtloausgrz.html

diff a.txt b.txt
来源：http://dali.gaohongyu789.top/Article/details/gtxgiejhdf.html

[R55] 压缩与解压
来源：http://dali.snrcjt.cn/Article/details/gtveagmfeh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jiagoushi.top/Article/details/gtfcysyszj.html

[R56] 远程拷贝
来源：http://dali.pycfn.com/Article/details/gtzhpxebin.html

scp file user@host:/path/
来源：http://dali.hywenlv.cn/Article/details/gtlqheglqs.html

[R57] 远程执行命令
来源：http://dali.yangfankeji.com/Article/details/gtqfnxrszm.html

ssh user@host 'uptime'
来源：http://dali.mhx1999.top/Article/details/gtplfsqxgr.html

[R58] 下载文件
来源：http://dali.gaohongyu789.top/Article/details/gtomxhtyyh.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.fengsongda.top/Article/details/gtlpznzwdw.html

[R59] 发 POST JSON
来源：http://dali.c1oappe.top/Article/details/gtttcmnddn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ydzc1.top/Article/details/gtgajassms.html

[R60] 只看 HTTP 状态码
来源：http://dali.yj202588.top/Article/details/gtucwpdack.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.meibo888.top/Article/details/gtyanhzxsz.html

[R61] 磁盘占用
来源：http://dali.tanke756.top/Article/details/gtjuajmnjt.html

df -h;  du -sh *
来源：http://dali.nanxuanxn.top/Article/details/gtryjaupfk.html

[R62] 找最占空间的文件
来源：http://dali.aizwys.cn/Article/details/gtkvfaxafc.html

du -ah . | sort -rh | head -10
来源：http://dali.dashuyun.cn/Article/details/gtquedisup.html

[R63] 内存与进程
来源：http://dali.xuanzx.com/Article/details/gtgbzdfcve.html

free -h;  ps aux | grep nginx
来源：http://dali.gotoacloud.top/Article/details/gtdsbargnd.html

[R64] 结束进程
来源：http://dali.andypj.xyz/Article/details/gtnxcfkcap.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ybcxt.top/Article/details/gtrwtbojnx.html

[R65] 查看端口占用
来源：http://dali.zhongyouzk.top/Article/details/gttidusaky.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhixingplan.top/Article/details/gtpngsxhph.html

[R66] 定时任务
来源：http://dali.zhongyouzk.top/Article/details/gtqehxljxa.html

crontab -e;  crontab -l
来源：http://dali.yanxiufei.cn/Article/details/gtdmxyiahz.html

[R67] 生成随机十六进制串
来源：http://dali.pengpengdd.cyou/Article/details/gtsmcwhpkn.html

openssl rand -hex 16
来源：http://dali.316326.xyz/Article/details/gtoajrmcbc.html

[R68] 计算文件校验值
来源：http://dali.cashguo.top/Article/details/gtwsxumeaq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlncrkpbs.html

[R69] 生成随机密码
来源：http://dali.aibaodan.cn/Article/details/gtxsxohiwc.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhengqikj.top/Article/details/gtckuyqwku.html

[R70] 时间戳与互转
来源：http://dali.shangyingyoupin.top/Article/details/gtcehgjllx.html

date +%s;  date -d @1700000000
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpiwdelac.html

[R71] 日期格式化
来源：http://dali.snrcjt.cn/Article/details/gtgpsidxmq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhoulong.xyz/Article/details/gtkoqciabe.html

[R72] 等待端口就绪
来源：http://dali.zhengqikj.top/Article/details/gtqkhnpmav.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.9152youxi.cn/Article/details/gtkekxtrji.html

[R73] 分割大日志
来源：http://dali.pengpengdd.cyou/Article/details/gthxmesxfp.html

split -l 1000 big.log part_
来源：http://dali.sweek.top/Article/details/gtajkfmmyv.html

[R74] 批量重命名
来源：http://dali.shangyingyoupin.top/Article/details/gtvoydbsvj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shuidangran.top/Article/details/gtsteffzum.html

[R75] 导出环境变量
来源：http://dali.nwbrower.top/Article/details/gtissjpixw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.vqdsnc.cn/Article/details/gtboyitqca.html

[R76] 使用临时文件
来源：http://dali.yongpay.top/Article/details/gtrunyqlhg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.iojbl.cn/Article/details/gtwtcgucju.html

[R77] 读取用户输入
来源：http://dali.cqqwz.cn/Article/details/gtkzczpgmi.html

read -rp "请输入: " ans
来源：http://dali.zycfv.cn/Article/details/gtcsaxrxlk.html

[R78] 交互式菜单
来源：http://dali.zhongyouzk.top/Article/details/gtoatetvwf.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.guannengcc.top/Article/details/gtjqjuwybl.html

[R79] 解析命令行选项
来源：http://dali.jqgfzy.top/Article/details/gtjfgeqcjl.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.shzxlz.cn/Article/details/gtjtfksbrm.html

[R80] 查看脚本执行耗时
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmuxqxozr.html

time ./run.sh
来源：http://dali.yuxming.cn/Article/details/gtllrudzkx.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtsywctuxc.html

S. C / C++ 专题
来源：http://dali.9152youxi.cn/Article/details/gtkntpmqny.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtrrvzepup.html

[S01] C：Hello World
来源：http://dali.jianghu66.top/Article/details/gthyawhjwy.html

#include <stdio.h>
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlllprzpd.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yj20258.top/Article/details/gtxvztqncf.html

[S02] C：变量与格式化输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvgeclvrc.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhongyouzk.top/Article/details/gtnbovbnpn.html

[S03] C：读入整数
来源：http://dali.xuanzx.com/Article/details/gtesfhsgqt.html

int x; scanf("%d", &x);
来源：http://dali.chenlongwang.top/Article/details/gtpwreqwgq.html

[S04] C：字符串复制
来源：http://dali.yonumen.top/Article/details/gtxwlmypvq.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.tian-w.cn/Article/details/gthfzirfpn.html

[S05] C：字符串长度
来源：http://dali.birdmap.top/Article/details/gtpdhfmbue.html

strlen(s)
来源：http://dali.shangyingyoupin.top/Article/details/gtigxtzgmb.html

[S06] C：字符串比较
来源：http://dali.zdqjudy.top/Article/details/gtbxpschgg.html

strcmp(a, b) == 0
来源：http://dali.yj202588.top/Article/details/gtxulqpjam.html

[S07] C：数组遍历求和
来源：http://dali.ybcxt.top/Article/details/gtkphkvgjd.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.aibaodan.cn/Article/details/gtfelwpjlt.html

[S08] C：动态内存分配与释放
来源：http://dali.sweek.top/Article/details/gtslugbltv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.mhx1999.top/Article/details/gtvnozqjbs.html

[S09] C：结构体定义与初始化
来源：http://dali.yj20258.top/Article/details/gtfevsodxg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.daxiang520.top/Article/details/gttqqdlwbc.html

[S10] C：指针与解引用
来源：http://dali.pengpengdd.cyou/Article/details/gtvmokxkww.html

int *p = &a;  *p = 5;
来源：http://dali.zhoulong.xyz/Article/details/gtuavhvnfj.html

[S11] C：逐行读文件
来源：http://dali.ybcxt.top/Article/details/gtrgflswws.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.ppjwa.cn/Article/details/gtmeupxxwf.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hnxiangtu.top/Article/details/gtdcbgfeop.html

fclose(f);
来源：http://dali.kuanghao11.cn/Article/details/gtmqthjwfn.html

[S12] C：写文件
来源：http://dali.cqqwz.cn/Article/details/gtjuzqbnse.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.wangdashe.top/Article/details/gtwhgyfras.html

[S13] C：宏定义
来源：http://dali.0kj1m.cn/Article/details/gtdqewvkhb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.cucudq.cn/Article/details/gtcghfvuea.html

[S14] C：枚举
来源：http://dali.jlsjyb.cn/Article/details/gtqfmsxxob.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.birdmap.top/Article/details/gtotjoyqvc.html

[S15] C：类型转换
来源：http://dali.zhiwuduotai.top/Article/details/gtvfbdsrby.html

(double) a / b
来源：http://dali.ppjwa.cn/Article/details/gtsmhmftss.html

[S16] C：位操作置位
来源：http://dali.yanxiufei.cn/Article/details/gtwcyqohio.html

x |= (1 << 3);
来源：http://dali.316326.xyz/Article/details/gtznzyzfon.html

[S17] C：安全拼接字符串
来源：http://dali.svipenyu.cn/Article/details/gtmvrndxqo.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gzhubu.top/Article/details/gtpxcsztjz.html

[S18] C：命令行参数
来源：http://dali.nwbrower.top/Article/details/gtqfbnptiq.html

int main(int argc, char **argv)
来源：http://dali.haohaochexian.top/Article/details/gthshxkmwt.html

[S19] C：快速排序
来源：http://dali.cucudq.cn/Article/details/gtspeadimm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zycfv.cn/Article/details/gtzqcqtojg.html

[S20] C：二分查找
来源：http://dali.mhx1999.top/Article/details/gtiupqeztr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xuanzx.com/Article/details/gtlrdmwowa.html

[S21] C：字符类别判断
来源：http://dali.jinghuilouyu.cn/Article/details/gtbjpxzudp.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.guannengcc.top/Article/details/gtbtdchntr.html

[S22] C：字符串转数字
来源：http://dali.andypj.xyz/Article/details/gtkwkikswn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.gogol.net.cn/Article/details/gtbntrmpam.html

[S23] C：随机数
来源：http://dali.jinghuilouyu.cn/Article/details/gtjnfcgrkk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.guannengcc.top/Article/details/gtohzlxgjv.html

[S24] C：获取本地时间
来源：http://dali.zhixingplan.top/Article/details/gtjlxbuwpd.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.cashguo.top/Article/details/gtzzmeotta.html

[S25] C：内存拷贝
来源：http://dali.bjfxy.top/Article/details/gtbmybwjxi.html

memcpy(dst, src, n);
来源：http://dali.wangshuangyany.cn/Article/details/gtxnkolaib.html

[S26] C：内存清零
来源：http://dali.shanyushiyangkeji.top/Article/details/gtesdgqtip.html

memset(a, 0, sizeof a);
来源：http://dali.yj20258.top/Article/details/gtqsntyyyx.html

[S27] C：定义常量
来源：http://dali.hammf.cn/Article/details/gttulpenis.html

const double PI = 3.14159;
来源：http://dali.c1oappe.top/Article/details/gtdcqkhixk.html

[S28] C：静态变量
来源：http://dali.feifeiyinyue.top/Article/details/gtiuraiqdd.html

static int counter = 0;
来源：http://dali.chenlongwang.top/Article/details/gtwfptggrr.html

[S29] C：变参函数
来源：http://dali.cashguo.top/Article/details/gtachjrwxh.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.shuidangran.top/Article/details/gtdsmjmxpp.html

[S30] C：头文件保护
来源：http://dali.vqdsnc.cn/Article/details/gtckzriyox.html

#ifndef X_H
来源：http://dali.zhixingplan.top/Article/details/gtpbugtixf.html

#define X_H
来源：http://dali.xylfe.cn/Article/details/gtndpzpsmw.html

#endif
来源：http://dali.jiagoushi.top/Article/details/gtnzkzwaqm.html

[S31] C++：Hello World
来源：http://dali.sufxvd.cn/Article/details/gtzsrqdonr.html

#include <iostream>
来源：http://dali.xziqi.cn/Article/details/gtzvzjhddj.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.tanke756.top/Article/details/gtykabfvwn.html

[S32] C++：字符串
来源：http://dali.zhengqikj.top/Article/details/gtfoxfiyrx.html

std::string s = "hi";  s += "!";
来源：http://dali.wangdashe.top/Article/details/gtvddcbbph.html

[S33] C++：vector 增删
来源：http://dali.cashguo.top/Article/details/gtnzanhjqp.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gzhubu.top/Article/details/gttlvjvpub.html

[S34] C++：遍历 vector
来源：http://dali.svipenyu.cn/Article/details/gtzwcnnecc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xinyue.icu/Article/details/gtowckhgzs.html

[S35] C++：map
来源：http://dali.ehwqpu.com/Article/details/gtbxcvovcb.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xziqi.cn/Article/details/gtugsfhvxk.html

[S36] C++：unordered_map
来源：http://dali.zhaomingkeji.xyz/Article/details/gtehjlpoli.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzbsmsseb.html

[S37] C++：set
来源：http://dali.yueranfly.top/Article/details/gtymyynpty.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xuetiantiany.cn/Article/details/gtcvtkvmpa.html

[S38] C++：排序
来源：http://dali.9152youxi.cn/Article/details/gtrnfjfbwg.html

std::sort(v.begin(), v.end());
来源：http://dali.sweek.top/Article/details/gtbttubnfn.html

[S39] C++：自定义比较器排序
来源：http://dali.zdqjudy.top/Article/details/gtmhqsyqxm.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.c1oappe.top/Article/details/gtdtckbxyu.html

[S40] C++：查找元素
来源：http://dali.pengpengdd.cyou/Article/details/gtydpcyipl.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shzxlz.cn/Article/details/gtamdwmaka.html

[S41] C++：类与构造函数
来源：http://dali.fengsongda.top/Article/details/gtdzqrkamc.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.zhongyouzk.top/Article/details/gtvhosonjq.html

[S42] C++：继承与虚函数
来源：http://dali.shangyingyoupin.top/Article/details/gtbmcxrsid.html

class B : public Base { public: void f() override {} };
来源：http://dali.yj202588.top/Article/details/gtquzdlruz.html

[S43] C++：智能指针
来源：http://dali.iojbl.cn/Article/details/gtizvujikx.html

auto p = std::make_unique<int>(5);
来源：http://dali.zhengqikj.top/Article/details/gttelkuclk.html

[S44] C++：引用传参
来源：http://dali.yangfankeji.com/Article/details/gtojmpvocr.html

void inc(int &x) { ++x; }
来源：http://dali.gzhubu.top/Article/details/gtfbrkbnte.html

[S45] C++：lambda
来源：http://dali.daria6918.cn/Article/details/gtvoihxujd.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.gogol.net.cn/Article/details/gtsxmeywlr.html

[S46] C++：函数模板
来源：http://dali.fengsongda.top/Article/details/gtugcecrxl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.cucudq.cn/Article/details/gtmkirdlri.html

[S47] C++：结构化绑定遍历
来源：http://dali.shanyushiyangtech.top/Article/details/gttxxnhjih.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yanxiufei.cn/Article/details/gtvpconaqh.html

[S48] C++：逐行读文件
来源：http://dali.havefunace.top/Article/details/gtovffyzsc.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.hnqzz.top/Article/details/gtzyxshsgh.html

while (std::getline(in, line)) { }
来源：http://dali.yj20258.top/Article/details/gtxveyytqk.html

[S49] C++：写文件
来源：http://dali.yonumen.top/Article/details/gtqrfysfmn.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.gogol.net.cn/Article/details/gtzpdouhqe.html

[S50] C++：格式化数字
来源：http://dali.svipenyu.cn/Article/details/gtmmtcuebt.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.shanyushiyangtech.top/Article/details/gtiixxicoq.html

[S51] C++：显式类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtemgducbv.html

static_cast<double>(a) / b
来源：http://dali.aibaodan.cn/Article/details/gtrgbfrlms.html

[S52] C++：const 与 noexcept
来源：http://dali.jqgufenzy.top/Article/details/gtyelqmeao.html

int size() const noexcept { return n_; }
来源：http://dali.jiagoushi.top/Article/details/gtkovqqhdk.html

[S53] C++：移动语义
来源：http://dali.dianchejie.cn/Article/details/gtdhnfwedz.html

std::vector<int> w = std::move(v);
来源：http://dali.haohaochexian.top/Article/details/gtmtbrziuw.html

[S54] C++：异常处理
来源：http://dali.cucudq.cn/Article/details/gtjrbbhktm.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.wangshuangyany.cn/Article/details/gtagdquwor.html

[S55] C++：结构化绑定
来源：http://dali.yongpay.top/Article/details/gtkmgigchn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.316326.xyz/Article/details/gtxykibrxw.html

[S56] C++：optional
来源：http://dali.shuidangran.top/Article/details/gtapqiuosx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yuanzhike.top/Article/details/gtrirhqquq.html

[S57] C++：编译期常量
来源：http://dali.vqdsnc.cn/Article/details/gtwufyglpl.html

constexpr int N = 10;
来源：http://dali.yj20258.top/Article/details/gtyjibeyeg.html

[S58] C++：命名空间
来源：http://dali.yuanzhike.top/Article/details/gtufffsulq.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhiwuduotai.top/Article/details/gtvwpperuu.html

[S59] C++：静态断言
来源：http://dali.316326.xyz/Article/details/gtosxuffzr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.hnxiangtu.top/Article/details/gtfptxbsta.html

[S60] C++：遍历并删除元素
来源：http://dali.yj20258.top/Article/details/gtkbuducyl.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.ivvv.top/Article/details/gtiffxxvew.html

================================================================================
来源：http://dali.cucudq.cn/Article/details/gtryqqzayc.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.cucudq.cn/Article/details/gtarriodga.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtbmnwmjmq.html

[T01] Kotlin：Hello World
来源：http://dali.zhixingplan.top/Article/details/gtrkgvubqk.html

println("Hello")
来源：http://dali.feifeiyinyue.top/Article/details/gttphqwcdr.html

[T02] Kotlin：变量
来源：http://dali.wangshuangyany.cn/Article/details/gtgvkcqidd.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hysaishi.cn/Article/details/gtwthaonom.html

[T03] Kotlin：字符串模板
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxnfteckd.html

"值: $b"
来源：http://dali.tanke756.top/Article/details/gtxlmyucmy.html

[T04] Kotlin：空安全
来源：http://dali.gaohongyu789.top/Article/details/gtsyxldmjm.html

val n: String? = null;  n?.length
来源：http://dali.ehwqpu.com/Article/details/gtixtdbbkl.html

[T05] Kotlin：when 表达式
来源：http://dali.feifeiyinyue.top/Article/details/gtcphtodyr.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.guannengcc.top/Article/details/gtcaqbrtqa.html

[T06] Kotlin：集合映射
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrsvqnbqu.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.gogol.net.cn/Article/details/gtgzzmcixp.html

[T07] Kotlin：集合过滤
来源：http://dali.dianchejie.cn/Article/details/gtduucicxe.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.zhongyouzk.top/Article/details/gtvzvralrb.html

[T08] Kotlin：数据类
来源：http://dali.gzhubu.top/Article/details/gthsbbtbmj.html

data class User(val name: String, val age: Int)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmdsnohjp.html

[T09] Kotlin：扩展函数
来源：http://dali.havefunace.top/Article/details/gttcvygcbj.html

fun String.exclaim() = this + "!"
来源：http://dali.jqgfzy.top/Article/details/gtrwjxzjiz.html

[T10] Kotlin：默认参数
来源：http://dali.hnxiangtu.top/Article/details/gtgdqjjezq.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.chenlongwang.top/Article/details/gtybithllq.html

[T11] Kotlin：协程
来源：http://dali.kuanghao11.cn/Article/details/gtzzyprxzq.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkjdxbxxy.html

[T12] Kotlin：解构声明
来源：http://dali.ivvv.top/Article/details/gtvchcfrit.html

val (a, b) = Pair(1, 2)
来源：http://dali.ivvv.top/Article/details/gtfwfptoiy.html

[T13] Kotlin：只读 Map
来源：http://dali.andypj.xyz/Article/details/gtqyrzhosn.html

val m = mapOf("a" to 1)
来源：http://dali.haohaochexian.top/Article/details/gtlwetrnof.html

[T14] Kotlin：循环
来源：http://dali.havefunace.top/Article/details/gthlhuvhgk.html

for (i in 1..10) println(i)
来源：http://dali.mhx1999.top/Article/details/gtxunavkos.html

[T15] Kotlin：接口
来源：http://dali.ppjwa.cn/Article/details/gtreozmopo.html

interface Shape { fun area(): Double }
来源：http://dali.gotoacloud.top/Article/details/gtospgvxlo.html

[T16] Swift：Hello World
来源：http://dali.zhongyouzk.top/Article/details/gtmohzptlp.html

print("Hello")
来源：http://dali.redwolf501.top/Article/details/gtumxcazhh.html

[T17] Swift：变量与常量
来源：http://dali.smart0.xyz/Article/details/gteknpoynl.html

var a = 1;  let b = 2
来源：http://dali.chenjidiqi.icu/Article/details/gtxvisdcoo.html

[T18] Swift：字符串插值
来源：http://dali.hysaishi.cn/Article/details/gtiihqvnaw.html

"值: \(b)"
来源：http://dali.jyoumei.cn/Article/details/gtfgtmspux.html

[T19] Swift：可选绑定
来源：http://dali.wangshuangyany.cn/Article/details/gtmdwotxtn.html

if let n = opt { print(n) }
来源：http://dali.tian-w.cn/Article/details/gtcvtacicr.html

[T20] Swift：数组操作
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxyvewrhu.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.316326.xyz/Article/details/gtlpjvsbpc.html

[T21] Swift：遍历
来源：http://dali.c1oappe.top/Article/details/gtsxyhztqb.html

for x in a { print(x) }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzasyjagi.html

[T22] Swift：字典
来源：http://dali.hnxiangtu.top/Article/details/gtdtudcrjx.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.tianlin.xyz/Article/details/gtymejbqok.html


<!-- 参考信息 -->