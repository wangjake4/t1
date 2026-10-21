代发 wailian999

echo "${#arr[@]}"
来源：http://dali.tanke756.top/Article/details/gtfklyqpxd.html

[R20] 关联数组（字典）
来源：http://dali.jyoumei.cn/Article/details/gterxchfyt.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhoulong.xyz/Article/details/gtouibdmxb.html

[R21] 字符串长度
来源：http://dali.yuanzhike.top/Article/details/gtcbujzzuw.html

echo "${#s}"
来源：http://dali.chenlongwang.top/Article/details/gtsnsdsofh.html

[R22] 截取子串
来源：http://dali.yj20258888.top/Article/details/gtraduhaoc.html

echo "${s:0:5}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtpjmhodxz.html

[R23] 字符串替换
来源：http://dali.xziqi.cn/Article/details/gteasdobri.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jlsjyb.cn/Article/details/gtvjwrveqh.html

[R24] 大小写转换
来源：http://dali.gaohongyu789.top/Article/details/gtiiziizav.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sufxvd.cn/Article/details/gtzkyetrkj.html

[R25] 去后缀 / 去前缀
来源：http://dali.ydzc1.top/Article/details/gtealjflxe.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgeholfnj.html

[R26] 命令替换
来源：http://dali.ydzc1.top/Article/details/gtsgybiula.html

now=$(date +%F); echo "$now"
来源：http://dali.jinqigfzy.top/Article/details/gtzvrrziww.html

[R27] 算术展开
来源：http://dali.yanxiufei.cn/Article/details/gtluqthxci.html

echo $((1 + 2 * 3))
来源：http://dali.andypj.xyz/Article/details/gtbhkadgib.html

[R28] 浮点运算
来源：http://dali.hnxiangtu.top/Article/details/gtjeicfkoz.html

echo "scale=2; 10/3" | bc
来源：http://dali.yanxiufei.cn/Article/details/gtpsgplkjn.html

[R29] 定义函数
来源：http://dali.316326.xyz/Article/details/gtqutklput.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gzhubu.top/Article/details/gtqlalltaa.html

[R30] 函数返回状态码
来源：http://dali.yanxiufei.cn/Article/details/gtcqovjanh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cucudq.cn/Article/details/gtqiuvqhln.html

[R31] 局部变量
来源：http://dali.cheryme.top/Article/details/gtbslnzkye.html

f() { local x=1; echo "$x"; }
来源：http://dali.sweek.top/Article/details/gtzhjuntxm.html

[R32] 参数个数校验
来源：http://dali.cheryme.top/Article/details/gtubpwgnoa.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.dashuyun.cn/Article/details/gtywxjfjis.html

[R33] 捕获错误并提示行号
来源：http://dali.gogol.net.cn/Article/details/gtucxrmjsz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jianghu66.top/Article/details/gtzctsqoya.html

[R34] 退出时清理
来源：http://dali.jlsjyb.cn/Article/details/gtwaxbavfq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.snrcjt.cn/Article/details/gttmcjptnw.html

[R35] 后台执行并等待
来源：http://dali.zhixingplan.top/Article/details/gtuhsicdhh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhoulong.xyz/Article/details/gtetwwicja.html

[R36] 并发执行多个任务
来源：http://dali.bjfxy.top/Article/details/gtffpfcwmc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yangfankeji.com/Article/details/gtuojfalgt.html

[R37] 把输出赋给变量
来源：http://dali.zhiwuduotai.top/Article/details/gtjgunuwie.html

files=$(ls -1)
来源：http://dali.jqgufenzy.top/Article/details/gtwcfadoap.html

[R38] 管道串联
来源：http://dali.yvedp.cn/Article/details/gtzfybmbbi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yj20258888.top/Article/details/gtuohktpvj.html

[R39] 重定向标准输出与错误
来源：http://dali.zhengqikj.top/Article/details/gtorkdurrr.html

cmd > out.log 2>&1
来源：http://dali.tanke756.top/Article/details/gtvnnjnyyj.html

[R40] 追加写日志
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfaadltbo.html

echo "log" >> out.log
来源：http://dali.yanxiufei.cn/Article/details/gtwwssdrdx.html

[R41] 丢弃输出
来源：http://dali.chenjidiqi.icu/Article/details/gtjekwjuph.html

cmd >/dev/null 2>&1
来源：http://dali.yuanzhike.top/Article/details/gtcijhwydz.html

[R42] 输入重定向
来源：http://dali.9152youxi.cn/Article/details/gtulwsjolr.html

wc -l < a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxawxkotl.html

[R43] 按名字查找文件
来源：http://dali.haohaochexian.top/Article/details/gtdwlemnhq.html

find . -name "*.log" -type f
来源：http://dali.cqqwz.cn/Article/details/gthfbufnbh.html

[R44] 按修改时间查找
来源：http://dali.fzhhl.top/Article/details/gtvvgpdpwz.html

find . -mtime -7 -type f
来源：http://dali.yueranfly.top/Article/details/gtqumeeqsw.html

[R45] 批量删除
来源：http://dali.bjfxy.top/Article/details/gtgrzuhgwl.html

find . -name "*.tmp" -delete
来源：http://dali.jianghu66.top/Article/details/gtefboulor.html

[R46] 递归替换文件内容
来源：http://dali.haohaochexian.top/Article/details/gtzbhyibhf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.shanyushiyangtech.top/Article/details/gtbozqcqjt.html

[R47] sed 单行替换
来源：http://dali.xinyue.icu/Article/details/gtxyuogfve.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xylfe.cn/Article/details/gtjpwmykrv.html

[R48] awk 取指定列
来源：http://dali.ydzc1.top/Article/details/gttedrwxok.html

awk '{print $1, $3}' a.txt
来源：http://dali.svipenyu.cn/Article/details/gtzdmocvfn.html

[R49] awk 带条件
来源：http://dali.yuxming.cn/Article/details/gtnvrmudiq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shuidangran.top/Article/details/gtkpebjjjz.html

[R50] awk 求和
来源：http://dali.chenjidiqi.icu/Article/details/gtyzbfpcdg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtcjpehvfa.html

[R51] 排序去重取前几
来源：http://dali.yanxiufei.cn/Article/details/gtallbtbxv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.9152youxi.cn/Article/details/gtuxemdrrs.html

[R52] 统计行数
来源：http://dali.xziqi.cn/Article/details/gtwuvxkmou.html

wc -l a.txt
来源：http://dali.cdnleiting.top/Article/details/gteamomqij.html

[R53] 查看文件头与实时尾
来源：http://dali.cqqwz.cn/Article/details/gttiyrskqs.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.aibaodan.cn/Article/details/gtamtvygus.html

[R54] 比较两个文件
来源：http://dali.iojbl.cn/Article/details/gthbpgscxt.html

diff a.txt b.txt
来源：http://dali.meibo888.top/Article/details/gtjsiyoufh.html

[R55] 压缩与解压
来源：http://dali.svipenyu.cn/Article/details/gtwwzkxmsb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xylfe.cn/Article/details/gtyvdrjqyg.html

[R56] 远程拷贝
来源：http://dali.gaohongyu789.top/Article/details/gtwjacfztn.html

scp file user@host:/path/
来源：http://dali.cashguo.top/Article/details/gtcmoqlqik.html

[R57] 远程执行命令
来源：http://dali.jqgfzy.top/Article/details/gthawnkzps.html

ssh user@host 'uptime'
来源：http://dali.jinqigufen.top/Article/details/gtcsgbowcq.html

[R58] 下载文件
来源：http://dali.gotoacloud.top/Article/details/gtvadpeudu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shanyushiyangtech.top/Article/details/gtavynudem.html

[R59] 发 POST JSON
来源：http://dali.xylfe.cn/Article/details/gtnzjjxnoq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hongshengwenyu.top/Article/details/gtyxohkuuj.html

[R60] 只看 HTTP 状态码
来源：http://dali.gaohongyu789.top/Article/details/gtcmexhjty.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xuanzx.com/Article/details/gtdnfhxkqx.html

[R61] 磁盘占用
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsqraypkl.html

df -h;  du -sh *
来源：http://dali.c1oappe.top/Article/details/gtdxlkophe.html

[R62] 找最占空间的文件
来源：http://dali.chenjidiqi.icu/Article/details/gtpahdnamu.html

du -ah . | sort -rh | head -10
来源：http://dali.316326.xyz/Article/details/gtenzgkoyw.html

[R63] 内存与进程
来源：http://dali.yangfankeji.com/Article/details/gtyydojpaq.html

free -h;  ps aux | grep nginx
来源：http://dali.birdmap.top/Article/details/gtgbqekssr.html

[R64] 结束进程
来源：http://dali.hongshengwenyu.top/Article/details/gtssvinupo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xuetiantiany.cn/Article/details/gtwfouckme.html

[R65] 查看端口占用
来源：http://dali.fzhhl.top/Article/details/gtmkxefdyd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.wangshuangyany.cn/Article/details/gtijzhaubg.html

[R66] 定时任务
来源：http://dali.316326.xyz/Article/details/gtgkqntwrl.html

crontab -e;  crontab -l
来源：http://dali.yanxiufei.cn/Article/details/gthvgkzxco.html

[R67] 生成随机十六进制串
来源：http://dali.aibaodan.cn/Article/details/gtlezrlojz.html

openssl rand -hex 16
来源：http://dali.dianchejie.cn/Article/details/gtalnrjrnr.html

[R68] 计算文件校验值
来源：http://dali.havefunace.top/Article/details/gtlyafmxhz.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtqozrdrzh.html

[R69] 生成随机密码
来源：http://dali.c1oappe.top/Article/details/gtkojcfhgh.html

head -c 16 /dev/urandom | base64
来源：http://dali.aizwys.cn/Article/details/gtuaivrvcs.html

[R70] 时间戳与互转
来源：http://dali.hnxiangtu.top/Article/details/gtlbmbrbvt.html

date +%s;  date -d @1700000000
来源：http://dali.gotoacloud.top/Article/details/gtaaeafkhf.html

[R71] 日期格式化
来源：http://dali.nwbrower.top/Article/details/gtnqifmwir.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hywenlv.cn/Article/details/gtuwlflnjq.html

[R72] 等待端口就绪
来源：http://dali.zhengqikj.top/Article/details/gtvtvqxnvi.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.kuanghao11.cn/Article/details/gtqnnsmseu.html

[R73] 分割大日志
来源：http://dali.tian-w.cn/Article/details/gtnzmxfkbn.html

split -l 1000 big.log part_
来源：http://dali.wangshuangyany.cn/Article/details/gtbxtgcirv.html

[R74] 批量重命名
来源：http://dali.jinqigfzy.top/Article/details/gteuqealuz.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.iojbl.cn/Article/details/gtnqrhpuoi.html

[R75] 导出环境变量
来源：http://dali.shzxlz.cn/Article/details/gtdiftsqed.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shuidangran.top/Article/details/gtrnceuayi.html

[R76] 使用临时文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgehsaqaw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigfzy.top/Article/details/gtocsvsmse.html

[R77] 读取用户输入
来源：http://dali.wangshuangyany.cn/Article/details/gtbxzbexsx.html

read -rp "请输入: " ans
来源：http://dali.sweek.top/Article/details/gtxfmoehng.html

[R78] 交互式菜单
来源：http://dali.yuxming.cn/Article/details/gtgdeemzfl.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.havefunace.top/Article/details/gtkbrotrse.html

[R79] 解析命令行选项
来源：http://dali.fzhhl.top/Article/details/gtdkjlomgq.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ehwqpu.com/Article/details/gtfvfqejgf.html

[R80] 查看脚本执行耗时
来源：http://dali.smart0.xyz/Article/details/gtyyytuuhz.html

time ./run.sh
来源：http://dali.zdqjudy.top/Article/details/gtqukcnptw.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtkvidnhbk.html

S. C / C++ 专题
来源：http://dali.yanxiufei.cn/Article/details/gtprcrxvwd.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtrhgekjuz.html

[S01] C：Hello World
来源：http://dali.haohaochexian.top/Article/details/gtrwtaljic.html

#include <stdio.h>
来源：http://dali.guannengcc.top/Article/details/gtatfnlxuh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yanxiufei.cn/Article/details/gtcbuywrbi.html

[S02] C：变量与格式化输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttaqtdgix.html

int a = 10; printf("%d\n", a);
来源：http://dali.fengsongda.top/Article/details/gtjytgnxrz.html

[S03] C：读入整数
来源：http://dali.ybcxt.top/Article/details/gtdgukgzke.html

int x; scanf("%d", &x);
来源：http://dali.hywenlv.cn/Article/details/gtqekjqadu.html

[S04] C：字符串复制
来源：http://dali.aibaodan.cn/Article/details/gtfouvqvjx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcphmprhb.html

[S05] C：字符串长度
来源：http://dali.hysaishi.cn/Article/details/gtmpjzdzwd.html

strlen(s)
来源：http://dali.nanxinkj.top/Article/details/gtxcqvwvml.html

[S06] C：字符串比较
来源：http://dali.birdmap.top/Article/details/gtonbjndif.html

strcmp(a, b) == 0
来源：http://dali.smart0.xyz/Article/details/gtvkumtucg.html

[S07] C：数组遍历求和
来源：http://dali.sweek.top/Article/details/gthnvbufii.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shuidangran.top/Article/details/gtwktkzgps.html

[S08] C：动态内存分配与释放
来源：http://dali.ydzc1.top/Article/details/gtxbouizdz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhengqikj.top/Article/details/gthtwwmgbu.html

[S09] C：结构体定义与初始化
来源：http://dali.ivvv.top/Article/details/gtljftpbws.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.svipenyu.cn/Article/details/gtousvbfle.html

[S10] C：指针与解引用
来源：http://dali.zhoulong.xyz/Article/details/gtqdeydzgg.html

int *p = &a;  *p = 5;
来源：http://dali.sysykeji.top/Article/details/gturlhcxvi.html

[S11] C：逐行读文件
来源：http://dali.tanke756.top/Article/details/gtevxitwsb.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.yuxming.cn/Article/details/gtgpdrmgkr.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.chenjidiqi.icu/Article/details/gtkssoiolb.html

fclose(f);
来源：http://dali.dianchejie.cn/Article/details/gttuiefsdz.html

[S12] C：写文件
来源：http://dali.pycfn.com/Article/details/gtfvqpdpbc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.mhx1999.top/Article/details/gttavvyxku.html

[S13] C：宏定义
来源：http://dali.birdmap.top/Article/details/gtvajsoaym.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.chenzaomai.com/Article/details/gtzjxyomos.html

[S14] C：枚举
来源：http://dali.sufxvd.cn/Article/details/gtgplcditn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jianghu66.top/Article/details/gtavfwzkzk.html

[S15] C：类型转换
来源：http://dali.zhoulong.xyz/Article/details/gtoaroeojc.html

(double) a / b
来源：http://dali.fengsongda.top/Article/details/gtqljbnazf.html

[S16] C：位操作置位
来源：http://dali.chenjidiqi.icu/Article/details/gtyeofsmxc.html

x |= (1 << 3);
来源：http://dali.jyoumei.cn/Article/details/gtqldargyb.html

[S17] C：安全拼接字符串
来源：http://dali.jyoumei.cn/Article/details/gthrswxlet.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sufxvd.cn/Article/details/gtiutbrczk.html

[S18] C：命令行参数
来源：http://dali.cucudq.cn/Article/details/gtkdzpwwpx.html

int main(int argc, char **argv)
来源：http://dali.hammf.cn/Article/details/gtysdbonpc.html

[S19] C：快速排序
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdwilixoc.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.chenlongwang.top/Article/details/gtjasalxte.html

[S20] C：二分查找
来源：http://dali.bjfxy.top/Article/details/gtuekgpaed.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinqigfzy.top/Article/details/gtowzyyfeb.html

[S21] C：字符类别判断
来源：http://dali.tianlin.xyz/Article/details/gtcabpttgf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.aibaodan.cn/Article/details/gtgvzziteg.html

[S22] C：字符串转数字
来源：http://dali.sufxvd.cn/Article/details/gtnoiqluqb.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.aibaodan.cn/Article/details/gtvrlrorwf.html

[S23] C：随机数
来源：http://dali.sweek.top/Article/details/gtmphtugfi.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.0kj1m.cn/Article/details/gtepohlbvu.html

[S24] C：获取本地时间
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjepjobos.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ehwqpu.com/Article/details/gtdoddyjdf.html

[S25] C：内存拷贝
来源：http://dali.chenjidiqi.icu/Article/details/gtfzaltvvq.html

memcpy(dst, src, n);
来源：http://dali.andypj.xyz/Article/details/gthmbngwji.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gtovytenhy.html

memset(a, 0, sizeof a);
来源：http://dali.chenlongwang.top/Article/details/gtyqppdrfw.html

[S27] C：定义常量
来源：http://dali.hywenlv.cn/Article/details/gttzoveljn.html

const double PI = 3.14159;
来源：http://dali.fengsongda.top/Article/details/gtftyioiwt.html

[S28] C：静态变量
来源：http://dali.pycfn.com/Article/details/gtmsquxskp.html

static int counter = 0;
来源：http://dali.meibo888.top/Article/details/gtztccctsm.html

[S29] C：变参函数
来源：http://dali.yonumen.top/Article/details/gtxlserkxw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.fzhhl.top/Article/details/gtahmsytmt.html

[S30] C：头文件保护
来源：http://dali.yanxiufei.cn/Article/details/gtarvyiqia.html

#ifndef X_H
来源：http://dali.iojbl.cn/Article/details/gtdlxtmjcg.html

#define X_H
来源：http://dali.zhongyouzk.top/Article/details/gtaqbcwzny.html

#endif
来源：http://dali.haohaochexian.top/Article/details/gtdvzqdany.html

[S31] C++：Hello World
来源：http://dali.zhiwuduotai.top/Article/details/gtjocbdynf.html

#include <iostream>
来源：http://dali.yvedp.cn/Article/details/gtowlxpycr.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.aizwys.cn/Article/details/gtzagsfxds.html

[S32] C++：字符串
来源：http://dali.shuidangran.top/Article/details/gtckxfrcbn.html

std::string s = "hi";  s += "!";
来源：http://dali.ybcxt.top/Article/details/gtjluuzifv.html

[S33] C++：vector 增删
来源：http://dali.yvedp.cn/Article/details/gttryitwqx.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gtxgileyuy.html

[S34] C++：遍历 vector
来源：http://dali.mhx1999.top/Article/details/gtbvobzkca.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.fzhhl.top/Article/details/gtkzpjzzsv.html

[S35] C++：map
来源：http://dali.shzxlz.cn/Article/details/gtoxmiqvju.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gtdmerrueh.html

[S36] C++：unordered_map
来源：http://dali.aibaodan.cn/Article/details/gtmwyheffe.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gtcplbcexk.html

[S37] C++：set
来源：http://dali.xuetiantiany.cn/Article/details/gttaxxpjtn.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hfpthk.cn/Article/details/gtatyfazzm.html

[S38] C++：排序
来源：http://dali.nwbrower.top/Article/details/gtrnkruizx.html

std::sort(v.begin(), v.end());
来源：http://dali.chenzaomai.com/Article/details/gtnacirkxd.html

[S39] C++：自定义比较器排序
来源：http://dali.tian-w.cn/Article/details/gtvddrapyu.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shzxlz.cn/Article/details/gtvtomnbft.html

[S40] C++：查找元素
来源：http://dali.chenlongwang.top/Article/details/gtghsgsofm.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.kuanghao11.cn/Article/details/gtcjfmactk.html

[S41] C++：类与构造函数
来源：http://dali.jianghu66.top/Article/details/gtoqlmvdyd.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.andypj.xyz/Article/details/gtcrcgwppo.html

[S42] C++：继承与虚函数
来源：http://dali.yongpay.top/Article/details/gtcdoepegf.html

class B : public Base { public: void f() override {} };
来源：http://dali.yanxiufei.cn/Article/details/gtefvodspo.html

[S43] C++：智能指针
来源：http://dali.jyoumei.cn/Article/details/gtrlnzkrop.html

auto p = std::make_unique<int>(5);
来源：http://dali.jinghuilouyu.cn/Article/details/gtuoxrmfti.html

[S44] C++：引用传参
来源：http://dali.sweek.top/Article/details/gtnqvgloov.html

void inc(int &x) { ++x; }
来源：http://dali.dashuyun.cn/Article/details/gtkslchswy.html

[S45] C++：lambda
来源：http://dali.svipenyu.cn/Article/details/gtxsnsxlwf.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.tian-w.cn/Article/details/gtnajstcnu.html

[S46] C++：函数模板
来源：http://dali.yj20258.top/Article/details/gtevvpkboe.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.haohaochexian.top/Article/details/gtucgtgdmc.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhongyouzk.top/Article/details/gttzjgxxva.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.wangdashe.top/Article/details/gtnaccivqn.html

[S48] C++：逐行读文件
来源：http://dali.yj20258888.top/Article/details/gtezytawwv.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.tanke756.top/Article/details/gtsugckzbu.html

while (std::getline(in, line)) { }
来源：http://dali.yangfankeji.com/Article/details/gthcwxlmkc.html

[S49] C++：写文件
来源：http://dali.wangdashe.top/Article/details/gtkjxwoqru.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.zhongyouzk.top/Article/details/gtftdortif.html

[S50] C++：格式化数字
来源：http://dali.bjfxy.top/Article/details/gtzvkeaqww.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.snrcjt.cn/Article/details/gtcvhsaojc.html

[S51] C++：显式类型转换
来源：http://dali.0kj1m.cn/Article/details/gtqzhwedjt.html

static_cast<double>(a) / b
来源：http://dali.zhixingplan.top/Article/details/gtiebqulyi.html

[S52] C++：const 与 noexcept
来源：http://dali.mhx1999.top/Article/details/gtlcrcdwae.html

int size() const noexcept { return n_; }
来源：http://dali.meibo888.top/Article/details/gtnahgazwv.html

[S53] C++：移动语义
来源：http://dali.xuetiantiany.cn/Article/details/gtlnxvgpgi.html

std::vector<int> w = std::move(v);
来源：http://dali.jiagoushi.top/Article/details/gtytqplqvc.html

[S54] C++：异常处理
来源：http://dali.sxryk.cn/Article/details/gtlrshqicu.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.shuidangran.top/Article/details/gtwtyjfuzx.html

[S55] C++：结构化绑定
来源：http://dali.hfpthk.cn/Article/details/gtttqcymsg.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.svipenyu.cn/Article/details/gtyrsvsqhe.html

[S56] C++：optional
来源：http://dali.pycfn.com/Article/details/gtgdxjrnks.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yongpay.top/Article/details/gttmcflrin.html

[S57] C++：编译期常量
来源：http://dali.dianchejie.cn/Article/details/gtlyidhbgc.html

constexpr int N = 10;
来源：http://dali.cdnleiting.top/Article/details/gtasehgpkg.html

[S58] C++：命名空间
来源：http://dali.fengsongda.top/Article/details/gtyjikmqcx.html

namespace ns { int f() { return 1; } }
来源：http://dali.wangdashe.top/Article/details/gtpcjygbaz.html

[S59] C++：静态断言
来源：http://dali.wangshuangyany.cn/Article/details/gtsufgxdrl.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.xuetiantiany.cn/Article/details/gtnyollkjd.html

[S60] C++：遍历并删除元素
来源：http://dali.hammf.cn/Article/details/gtvrvyooaj.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.haohaochexian.top/Article/details/gtiavjjvpe.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtmzwxsbjk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.zdqjudy.top/Article/details/gtnusshfvz.html

================================================================================
来源：http://dali.zdqjudy.top/Article/details/gtoxzummga.html

[T01] Kotlin：Hello World
来源：http://dali.chenlongwang.top/Article/details/gtcbxkayah.html

println("Hello")
来源：http://dali.yanxiufei.cn/Article/details/gtgcxhgskk.html

[T02] Kotlin：变量
来源：http://dali.hysaishi.cn/Article/details/gtuzovgghn.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.hnqzz.top/Article/details/gtlxxxwziy.html

[T03] Kotlin：字符串模板
来源：http://dali.ivvv.top/Article/details/gtciwycook.html

"值: $b"
来源：http://dali.shanyushiyangtech.top/Article/details/gtiapbkykw.html

[T04] Kotlin：空安全
来源：http://dali.wangdashe.top/Article/details/gtorslmxuu.html

val n: String? = null;  n?.length
来源：http://dali.gaohongyu789.top/Article/details/gtfdnzbslw.html

[T05] Kotlin：when 表达式
来源：http://dali.zhijiandao.cn/Article/details/gtmwkqvzbj.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.jinqigfzy.top/Article/details/gtlsetpwsz.html

[T06] Kotlin：集合映射
来源：http://dali.shanyushiyangtech.top/Article/details/gtotvboyvf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.iojbl.cn/Article/details/gtkssxiacc.html

[T07] Kotlin：集合过滤
来源：http://dali.ehwqpu.com/Article/details/gtyfyowike.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.shuidangran.top/Article/details/gtcpbcutjn.html

[T08] Kotlin：数据类
来源：http://dali.cqqwz.cn/Article/details/gtlldvlekz.html

data class User(val name: String, val age: Int)
来源：http://dali.hnxiangtu.top/Article/details/gtuwthzwph.html

[T09] Kotlin：扩展函数
来源：http://dali.smart0.xyz/Article/details/gtapcypjer.html

fun String.exclaim() = this + "!"
来源：http://dali.nanxuanxn.top/Article/details/gtvwhtbcpb.html

[T10] Kotlin：默认参数
来源：http://dali.haohaochexian.top/Article/details/gtmtfkvemg.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.gzhubu.top/Article/details/gtbxnksfpb.html

[T11] Kotlin：协程
来源：http://dali.shzxlz.cn/Article/details/gtijtemexw.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.gotoacloud.top/Article/details/gtjzdrgelt.html

[T12] Kotlin：解构声明
来源：http://dali.c1oappe.top/Article/details/gtzdtnvafr.html

val (a, b) = Pair(1, 2)
来源：http://dali.redwolf501.top/Article/details/gtenzulijb.html

[T13] Kotlin：只读 Map
来源：http://dali.ivvv.top/Article/details/gtahocvums.html

val m = mapOf("a" to 1)
来源：http://dali.nanxuanxn.top/Article/details/gtphmortjl.html

[T14] Kotlin：循环
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfeeeorpz.html

for (i in 1..10) println(i)
来源：http://dali.sxryk.cn/Article/details/gtzgprispv.html

[T15] Kotlin：接口
来源：http://dali.nwbrower.top/Article/details/gtcwywxaed.html

interface Shape { fun area(): Double }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtozdqesqn.html

[T16] Swift：Hello World
来源：http://dali.guannengcc.top/Article/details/gtyyhatxqj.html

print("Hello")
来源：http://dali.jinghuilouyu.cn/Article/details/gtjwiipjpt.html

[T17] Swift：变量与常量
来源：http://dali.ppjwa.cn/Article/details/gtttuwnvif.html

var a = 1;  let b = 2
来源：http://dali.zdqjudy.top/Article/details/gtsfhvwveg.html

[T18] Swift：字符串插值
来源：http://dali.9152youxi.cn/Article/details/gtcuavggel.html

"值: \(b)"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdexczjog.html

[T19] Swift：可选绑定
来源：http://dali.kuanghao11.cn/Article/details/gtwjdcmket.html

if let n = opt { print(n) }
来源：http://dali.jqgufenzy.top/Article/details/gtcvboouve.html

[T20] Swift：数组操作
来源：http://dali.xylfe.cn/Article/details/gtwtalpqod.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.fengsongda.top/Article/details/gtqavofhnb.html

[T21] Swift：遍历
来源：http://dali.bjfxy.top/Article/details/gtxwzqmpsq.html

for x in a { print(x) }
来源：http://dali.chenlongwang.top/Article/details/gtbjgexbqk.html

[T22] Swift：字典
来源：http://dali.zycfv.cn/Article/details/gtxzxriszl.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.quarkkingdee.top/Article/details/gtjygijlal.html


<!-- 参考信息 -->