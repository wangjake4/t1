代发 wailian999

echo "${#arr[@]}"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ubpjbgop.html

[R20] 关联数组（字典）
来源：http://dali.ybcxt.top/Article/details/gt2okdprrye.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.smart0.xyz/Article/details/gt2jwilvbpy.html

[R21] 字符串长度
来源：http://dali.xuanzx.com/Article/details/gt2phfadhpa.html

echo "${#s}"
来源：http://dali.andypj.xyz/Article/details/gt2tacpejsk.html

[R22] 截取子串
来源：http://dali.fengsongda.top/Article/details/gt2ohgihbfx.html

echo "${s:0:5}"
来源：http://dali.cashguo.top/Article/details/gt2nydlywqd.html

[R23] 字符串替换
来源：http://dali.gaohongyu789.top/Article/details/gt2nmqpitvs.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.bjfxy.top/Article/details/gt2wzzkscbc.html

[R24] 大小写转换
来源：http://dali.yj202588.top/Article/details/gt2guncfffz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hnxiangtu.top/Article/details/gt2lyhkrogc.html

[R25] 去后缀 / 去前缀
来源：http://dali.svipenyu.cn/Article/details/gt2ccxsqyrt.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhixingplan.top/Article/details/gt2hrunlhhs.html

[R26] 命令替换
来源：http://dali.havefunace.top/Article/details/gt2dbhczlox.html

now=$(date +%F); echo "$now"
来源：http://dali.sweek.top/Article/details/gt2wtjytegw.html

[R27] 算术展开
来源：http://dali.cashguo.top/Article/details/gt2vjznpras.html

echo $((1 + 2 * 3))
来源：http://dali.0kj1m.cn/Article/details/gt2xrvswevz.html

[R28] 浮点运算
来源：http://dali.nanxinkj.top/Article/details/gt2ijpwnfuk.html

echo "scale=2; 10/3" | bc
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2sclaiydu.html

[R29] 定义函数
来源：http://dali.ivvv.top/Article/details/gt2vxxrgbnh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhixingplan.top/Article/details/gt2arjpddot.html

[R30] 函数返回状态码
来源：http://dali.yj20258.top/Article/details/gt2kwjzuwnw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gaohongyu789.top/Article/details/gt2nlihgupe.html

[R31] 局部变量
来源：http://dali.ppjwa.cn/Article/details/gt2aakkjybv.html

f() { local x=1; echo "$x"; }
来源：http://dali.9152youxi.cn/Article/details/gt2lhjzyyyt.html

[R32] 参数个数校验
来源：http://dali.chenlongwang.top/Article/details/gt2mngqazgf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.svipenyu.cn/Article/details/gt2ixdzjgyw.html

[R33] 捕获错误并提示行号
来源：http://dali.cashguo.top/Article/details/gt2zkubrmvt.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.tianlin.xyz/Article/details/gt2sbpgfsry.html

[R34] 退出时清理
来源：http://dali.ehwqpu.com/Article/details/gt2cjeequet.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yongpay.top/Article/details/gt2ijcprsqz.html

[R35] 后台执行并等待
来源：http://dali.hywenlv.cn/Article/details/gt2pjumwmaw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.birdmap.top/Article/details/gt2qzudclcz.html

[R36] 并发执行多个任务
来源：http://dali.chenlongwang.top/Article/details/gt2mehahrum.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xinyue.icu/Article/details/gt2njfuxmmy.html

[R37] 把输出赋给变量
来源：http://dali.sufxvd.cn/Article/details/gt2mqitymck.html

files=$(ls -1)
来源：http://dali.zhixingplan.top/Article/details/gt2vgqcdsmf.html

[R38] 管道串联
来源：http://dali.zhoulong.xyz/Article/details/gt2rdnnpuvn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yanxiufei.cn/Article/details/gt2ortkjwsu.html

[R39] 重定向标准输出与错误
来源：http://dali.pycfn.com/Article/details/gt2hngzcnja.html

cmd > out.log 2>&1
来源：http://dali.chenjidiqi.icu/Article/details/gt2ograpjhu.html

[R40] 追加写日志
来源：http://dali.dashuyun.cn/Article/details/gt2fyozoqym.html

echo "log" >> out.log
来源：http://dali.hysaishi.cn/Article/details/gt2svzlmuqm.html

[R41] 丢弃输出
来源：http://dali.smart0.xyz/Article/details/gt2rwztqjqp.html

cmd >/dev/null 2>&1
来源：http://dali.shangyingyoupin.top/Article/details/gt2bxsokoqw.html

[R42] 输入重定向
来源：http://dali.bjfxy.top/Article/details/gt2lleocwvb.html

wc -l < a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2klxhfpep.html

[R43] 按名字查找文件
来源：http://dali.haohaochexian.top/Article/details/gt2uitrepgo.html

find . -name "*.log" -type f
来源：http://dali.wangshuangyany.cn/Article/details/gt2trrkxhoj.html

[R44] 按修改时间查找
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2vnffojkj.html

find . -mtime -7 -type f
来源：http://dali.ehwqpu.com/Article/details/gt2srylzmgw.html

[R45] 批量删除
来源：http://dali.gaohongyu789.top/Article/details/gt2mudsrhzj.html

find . -name "*.tmp" -delete
来源：http://dali.xylfe.cn/Article/details/gt2kmsshger.html

[R46] 递归替换文件内容
来源：http://dali.redwolf501.top/Article/details/gt2zxydsxzr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.snrcjt.cn/Article/details/gt2qthuovds.html

[R47] sed 单行替换
来源：http://dali.yongpay.top/Article/details/gt2osxejndm.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.9152youxi.cn/Article/details/gt2ctnhfmqt.html

[R48] awk 取指定列
来源：http://dali.aizwys.cn/Article/details/gt2fwvximye.html

awk '{print $1, $3}' a.txt
来源：http://dali.chenzaomai.com/Article/details/gt2ighiwumg.html

[R49] awk 带条件
来源：http://dali.jyoumei.cn/Article/details/gt2ythvuneo.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shangyingyoupin.top/Article/details/gt2eaqtnwsn.html

[R50] awk 求和
来源：http://dali.feifeiyinyue.top/Article/details/gt2awgxknba.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.wangdashe.top/Article/details/gt2efvpiduw.html

[R51] 排序去重取前几
来源：http://dali.ivvv.top/Article/details/gt2ewyszcox.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yj20258.top/Article/details/gt2qzulkxzm.html

[R52] 统计行数
来源：http://dali.aibaodan.cn/Article/details/gt2pghzpbgo.html

wc -l a.txt
来源：http://dali.guowangkeji.top/Article/details/gt2jekzygce.html

[R53] 查看文件头与实时尾
来源：http://dali.cucudq.cn/Article/details/gt2idrqdfdv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tanke756.top/Article/details/gt2jvjmwdbb.html

[R54] 比较两个文件
来源：http://dali.0kj1m.cn/Article/details/gt2ifobbxpr.html

diff a.txt b.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2dygqijqh.html

[R55] 压缩与解压
来源：http://dali.tian-w.cn/Article/details/gt2kbwqudow.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yongpay.top/Article/details/gt2xqskvket.html

[R56] 远程拷贝
来源：http://dali.xylfe.cn/Article/details/gt2qltaibpj.html

scp file user@host:/path/
来源：http://dali.meibo888.top/Article/details/gt2grbqxkqj.html

[R57] 远程执行命令
来源：http://dali.shuidangran.top/Article/details/gt2tcnguhpt.html

ssh user@host 'uptime'
来源：http://dali.zhengqikj.top/Article/details/gt2enwkylct.html

[R58] 下载文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2geqciosn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gotoacloud.top/Article/details/gt2ivorbshc.html

[R59] 发 POST JSON
来源：http://dali.ehwqpu.com/Article/details/gt2ssjeyiis.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.tianlin.xyz/Article/details/gt2bkjhzclw.html

[R60] 只看 HTTP 状态码
来源：http://dali.nanxuanxn.top/Article/details/gt2atyslnpa.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hfpthk.cn/Article/details/gt2lcxoijgv.html

[R61] 磁盘占用
来源：http://dali.feifeiyinyue.top/Article/details/gt2jrtrpvrc.html

df -h;  du -sh *
来源：http://dali.feifeiyinyue.top/Article/details/gt2asupptrf.html

[R62] 找最占空间的文件
来源：http://dali.chenlongwang.top/Article/details/gt2koogpfwr.html

du -ah . | sort -rh | head -10
来源：http://dali.sysykeji.top/Article/details/gt2gitbqbbu.html

[R63] 内存与进程
来源：http://dali.9152youxi.cn/Article/details/gt2ijtdnfcg.html

free -h;  ps aux | grep nginx
来源：http://dali.gogol.net.cn/Article/details/gt2ivwhlzvl.html

[R64] 结束进程
来源：http://dali.zhoulong.xyz/Article/details/gt2zdqqtlyh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sweek.top/Article/details/gt2qkrkqtbp.html

[R65] 查看端口占用
来源：http://dali.tanke756.top/Article/details/gt2wuhulzsi.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hfpthk.cn/Article/details/gt2hpnfzztq.html

[R66] 定时任务
来源：http://dali.jinqigfzy.top/Article/details/gt2ircsqlgf.html

crontab -e;  crontab -l
来源：http://dali.nwbrower.top/Article/details/gt2pvhxekpd.html

[R67] 生成随机十六进制串
来源：http://dali.snrcjt.cn/Article/details/gt2fzualsws.html

openssl rand -hex 16
来源：http://dali.ivvv.top/Article/details/gt2bdholonp.html

[R68] 计算文件校验值
来源：http://dali.ppjwa.cn/Article/details/gt2xiydcrld.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yj20258888.top/Article/details/gt2bqtwxnws.html

[R69] 生成随机密码
来源：http://dali.0kj1m.cn/Article/details/gt2xeynvuuv.html

head -c 16 /dev/urandom | base64
来源：http://dali.yj20258.top/Article/details/gt2reunsryk.html

[R70] 时间戳与互转
来源：http://dali.yuxming.cn/Article/details/gt2tmsbchui.html

date +%s;  date -d @1700000000
来源：http://dali.tanke756.top/Article/details/gt2vueruwld.html

[R71] 日期格式化
来源：http://dali.yj20258.top/Article/details/gt2jtvcdtvg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj20258888.top/Article/details/gt2budwgnya.html

[R72] 等待端口就绪
来源：http://dali.yj20258888.top/Article/details/gt2ycqycpbw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cdnleiting.top/Article/details/gt2mgqqgkge.html

[R73] 分割大日志
来源：http://dali.chenlongwang.top/Article/details/gt2qamuuoil.html

split -l 1000 big.log part_
来源：http://dali.jqgufenzy.top/Article/details/gt2emsczaut.html

[R74] 批量重命名
来源：http://dali.dianchejie.cn/Article/details/gt2ujhdhcqf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sweek.top/Article/details/gt2lsnfnetj.html

[R75] 导出环境变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2omwsjqsy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zycfv.cn/Article/details/gt2xlyjixpy.html

[R76] 使用临时文件
来源：http://dali.jinqigfzy.top/Article/details/gt2tjkdsktb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.svipenyu.cn/Article/details/gt2sucppsqj.html

[R77] 读取用户输入
来源：http://dali.vqdsnc.cn/Article/details/gt2dfutadoo.html

read -rp "请输入: " ans
来源：http://dali.wangdashe.top/Article/details/gt2wnfmabyl.html

[R78] 交互式菜单
来源：http://dali.andypj.xyz/Article/details/gt2slrdlbst.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.316326.xyz/Article/details/gt2hmnouyvu.html

[R79] 解析命令行选项
来源：http://dali.9152youxi.cn/Article/details/gt2qcttlkui.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jinghuilouyu.cn/Article/details/gt2vafzbjyg.html

[R80] 查看脚本执行耗时
来源：http://dali.ybcxt.top/Article/details/gt2sytjgjvp.html

time ./run.sh
来源：http://dali.tian-w.cn/Article/details/gt2ntmbqhez.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gt2yjtpikwq.html

S. C / C++ 专题
来源：http://dali.shangyingyoupin.top/Article/details/gt2icgiqyiy.html

================================================================================
来源：http://dali.hammf.cn/Article/details/gt2daxulxdu.html

[S01] C：Hello World
来源：http://dali.quarkkingdee.top/Article/details/gt2nmpytxyo.html

#include <stdio.h>
来源：http://dali.daxiang520.top/Article/details/gt2uscxpnot.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zycfv.cn/Article/details/gt2covwnqlf.html

[S02] C：变量与格式化输出
来源：http://dali.guowangkeji.top/Article/details/gt2sqkpudtk.html

int a = 10; printf("%d\n", a);
来源：http://dali.sxryk.cn/Article/details/gt2zmrvokhf.html

[S03] C：读入整数
来源：http://dali.yj202588.top/Article/details/gt2sdffysat.html

int x; scanf("%d", &x);
来源：http://dali.mhx1999.top/Article/details/gt2czwdabtf.html

[S04] C：字符串复制
来源：http://dali.iojbl.cn/Article/details/gt2plybcooh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jyoumei.cn/Article/details/gt2bitdngev.html

[S05] C：字符串长度
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ikbsggag.html

strlen(s)
来源：http://dali.jqgufenzy.top/Article/details/gt2umezgrvp.html

[S06] C：字符串比较
来源：http://dali.daxiang520.top/Article/details/gt2fsgetknc.html

strcmp(a, b) == 0
来源：http://dali.gogol.net.cn/Article/details/gt2uacmkrfb.html

[S07] C：数组遍历求和
来源：http://dali.xuanzx.com/Article/details/gt2vpspbodf.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xuetiantiany.cn/Article/details/gt2ctmdclqu.html

[S08] C：动态内存分配与释放
来源：http://dali.dashuyun.cn/Article/details/gt2tzyqwhoq.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.chenlongwang.top/Article/details/gt2pafqogdj.html

[S09] C：结构体定义与初始化
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2cmvoagpw.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hnqzz.top/Article/details/gt2vhgwwsao.html

[S10] C：指针与解引用
来源：http://dali.meibo888.top/Article/details/gt2uqymxbfu.html

int *p = &a;  *p = 5;
来源：http://dali.hammf.cn/Article/details/gt2uzrzyrhx.html

[S11] C：逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gt2vjujedki.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.gaohongyu789.top/Article/details/gt2bykawxeh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.fengsongda.top/Article/details/gt2mdqbvoft.html

fclose(f);
来源：http://dali.zycfv.cn/Article/details/gt2aqgwvryt.html

[S12] C：写文件
来源：http://dali.tianlin.xyz/Article/details/gt2mxbwmtfc.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.vqdsnc.cn/Article/details/gt2iuqsbthq.html

[S13] C：宏定义
来源：http://dali.gzhubu.top/Article/details/gt2sastpylu.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.0kj1m.cn/Article/details/gt2wrrmsozr.html

[S14] C：枚举
来源：http://dali.yueranfly.top/Article/details/gt2wenxoxrm.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.nanxinkj.top/Article/details/gt2wgciaxvi.html

[S15] C：类型转换
来源：http://dali.daria6918.cn/Article/details/gt2isnqrhqg.html

(double) a / b
来源：http://dali.ehwqpu.com/Article/details/gt2gffsxqjd.html

[S16] C：位操作置位
来源：http://dali.wangshuangyany.cn/Article/details/gt2tohfvzks.html

x |= (1 << 3);
来源：http://dali.hfpthk.cn/Article/details/gt2exjqjizx.html

[S17] C：安全拼接字符串
来源：http://dali.fengsongda.top/Article/details/gt2nakxkfid.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yangfankeji.com/Article/details/gt2eprddctd.html

[S18] C：命令行参数
来源：http://dali.hnxiangtu.top/Article/details/gt2gthihyem.html

int main(int argc, char **argv)
来源：http://dali.havefunace.top/Article/details/gt2ponvgrgl.html

[S19] C：快速排序
来源：http://dali.svipenyu.cn/Article/details/gt2ehlxwzaa.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.ppjwa.cn/Article/details/gt2gmkavfby.html

[S20] C：二分查找
来源：http://dali.yuxming.cn/Article/details/gt2eztykxiu.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.jinqigufen.top/Article/details/gt2xdomgxzs.html

[S21] C：字符类别判断
来源：http://dali.zycfv.cn/Article/details/gt2yoirutqo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.mhx1999.top/Article/details/gt2hpbrqjbu.html

[S22] C：字符串转数字
来源：http://dali.redwolf501.top/Article/details/gt2axyocolw.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.aizwys.cn/Article/details/gt2bamrnhvg.html

[S23] C：随机数
来源：http://dali.chenlongwang.top/Article/details/gt2yefunhbi.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.hywenlv.cn/Article/details/gt2aanylzub.html

[S24] C：获取本地时间
来源：http://dali.daxiang520.top/Article/details/gt2ipaztqsq.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hfpthk.cn/Article/details/gt2zslrjalh.html

[S25] C：内存拷贝
来源：http://dali.gotoacloud.top/Article/details/gt2snkaliib.html

memcpy(dst, src, n);
来源：http://dali.c1oappe.top/Article/details/gt2hqvigbxc.html

[S26] C：内存清零
来源：http://dali.yonumen.top/Article/details/gt2ocugyfzl.html

memset(a, 0, sizeof a);
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hwdifpmg.html

[S27] C：定义常量
来源：http://dali.nwbrower.top/Article/details/gt2iebmkwjh.html

const double PI = 3.14159;
来源：http://dali.quarkkingdee.top/Article/details/gt2krsmfnuv.html

[S28] C：静态变量
来源：http://dali.birdmap.top/Article/details/gt2djmeqwxy.html

static int counter = 0;
来源：http://dali.mhx1999.top/Article/details/gt2nnpiunrh.html

[S29] C：变参函数
来源：http://dali.guowangkeji.top/Article/details/gt2eesdouzo.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zdqjudy.top/Article/details/gt2cgoncxtl.html

[S30] C：头文件保护
来源：http://dali.snrcjt.cn/Article/details/gt2ekavudee.html

#ifndef X_H
来源：http://dali.chenjidiqi.icu/Article/details/gt2jybxpbhc.html

#define X_H
来源：http://dali.zhiwuduotai.top/Article/details/gt2izljagva.html

#endif
来源：http://dali.cqqwz.cn/Article/details/gt2bxddetxe.html

[S31] C++：Hello World
来源：http://dali.jqgfzy.top/Article/details/gt2waiepalz.html

#include <iostream>
来源：http://dali.mhx1999.top/Article/details/gt2rmlwhaxv.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.0kj1m.cn/Article/details/gt2lkbczzjt.html

[S32] C++：字符串
来源：http://dali.jqgfzy.top/Article/details/gt2umadpjnp.html

std::string s = "hi";  s += "!";
来源：http://dali.yuxming.cn/Article/details/gt2morucriq.html

[S33] C++：vector 增删
来源：http://dali.jinqigfzy.top/Article/details/gt2eozeqdie.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.svipenyu.cn/Article/details/gt2cqfjxleq.html

[S34] C++：遍历 vector
来源：http://dali.hongshengwenyu.top/Article/details/gt2wyvdgjbv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nthnunxr.html

[S35] C++：map
来源：http://dali.fengsongda.top/Article/details/gt2cstaecxh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.sufxvd.cn/Article/details/gt2jxeeohdi.html

[S36] C++：unordered_map
来源：http://dali.fengsongda.top/Article/details/gt2wucwfjzn.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xziqi.cn/Article/details/gt2babscger.html

[S37] C++：set
来源：http://dali.xuanzx.com/Article/details/gt2luerjyka.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.jlsjyb.cn/Article/details/gt2ifhwctpt.html

[S38] C++：排序
来源：http://dali.redwolf501.top/Article/details/gt2jindlhkh.html

std::sort(v.begin(), v.end());
来源：http://dali.nanxinkj.top/Article/details/gt2mmadieyg.html

[S39] C++：自定义比较器排序
来源：http://dali.zdqjudy.top/Article/details/gt2qdvdvzmk.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.tianlin.xyz/Article/details/gt2guowbmww.html

[S40] C++：查找元素
来源：http://dali.chenlongwang.top/Article/details/gt2rszokeha.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.chenlongwang.top/Article/details/gt2yhnjymta.html

[S41] C++：类与构造函数
来源：http://dali.nanxuanxn.top/Article/details/gt2axfkvtqg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.sxryk.cn/Article/details/gt2wwvpfnet.html

[S42] C++：继承与虚函数
来源：http://dali.haohaochexian.top/Article/details/gt2byjjbbby.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhijiandao.cn/Article/details/gt2iebakctz.html

[S43] C++：智能指针
来源：http://dali.guowangkeji.top/Article/details/gt2wqxmhyyc.html

auto p = std::make_unique<int>(5);
来源：http://dali.cqqwz.cn/Article/details/gt2hnidcmbu.html

[S44] C++：引用传参
来源：http://dali.shanyushiyangtech.top/Article/details/gt2xwzdglnf.html

void inc(int &x) { ++x; }
来源：http://dali.yj202588.top/Article/details/gt2zdoivjvo.html

[S45] C++：lambda
来源：http://dali.sysykeji.top/Article/details/gt2nfckmajq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.sysykeji.top/Article/details/gt2amczhmcy.html

[S46] C++：函数模板
来源：http://dali.xuanzx.com/Article/details/gt2lfvjfvnt.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.9152youxi.cn/Article/details/gt2bgxwvmap.html

[S47] C++：结构化绑定遍历
来源：http://dali.fzhhl.top/Article/details/gt2kgkxsusc.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xuanzx.com/Article/details/gt2uablestk.html

[S48] C++：逐行读文件
来源：http://dali.hfpthk.cn/Article/details/gt2apsakgdn.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.zycfv.cn/Article/details/gt2opjxuaht.html

while (std::getline(in, line)) { }
来源：http://dali.guowangkeji.top/Article/details/gt2gejdwznw.html

[S49] C++：写文件
来源：http://dali.shangyingyoupin.top/Article/details/gt2eucwvrmj.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shzxlz.cn/Article/details/gt2vdnfbpxl.html

[S50] C++：格式化数字
来源：http://dali.xziqi.cn/Article/details/gt2qntiwhxs.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lxyugfdh.html

[S51] C++：显式类型转换
来源：http://dali.hfpthk.cn/Article/details/gt2hlqmiemj.html

static_cast<double>(a) / b
来源：http://dali.iojbl.cn/Article/details/gt2wubdiliv.html

[S52] C++：const 与 noexcept
来源：http://dali.shzxlz.cn/Article/details/gt2jdxnfpjq.html

int size() const noexcept { return n_; }
来源：http://dali.nwbrower.top/Article/details/gt2xcycrjeg.html

[S53] C++：移动语义
来源：http://dali.chenzaomai.com/Article/details/gt2mwdrxyqu.html

std::vector<int> w = std::move(v);
来源：http://dali.zdqjudy.top/Article/details/gt2pshddmcl.html

[S54] C++：异常处理
来源：http://dali.daria6918.cn/Article/details/gt2wjpvnmls.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.dianchejie.cn/Article/details/gt2lirospmt.html

[S55] C++：结构化绑定
来源：http://dali.gaohongyu789.top/Article/details/gt2mqbdbozn.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.cqqwz.cn/Article/details/gt2ezzbnokx.html

[S56] C++：optional
来源：http://dali.xziqi.cn/Article/details/gt2vaurtqvw.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yueranfly.top/Article/details/gt2kjlulghi.html

[S57] C++：编译期常量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vjrjjprx.html

constexpr int N = 10;
来源：http://dali.shuidangran.top/Article/details/gt2fycechtb.html

[S58] C++：命名空间
来源：http://dali.andypj.xyz/Article/details/gt2gpjqyoef.html

namespace ns { int f() { return 1; } }
来源：http://dali.yvedp.cn/Article/details/gt2xxsuarjv.html

[S59] C++：静态断言
来源：http://dali.sufxvd.cn/Article/details/gt2khpvnkdd.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.zycfv.cn/Article/details/gt2tkspqctz.html

[S60] C++：遍历并删除元素
来源：http://dali.yuxming.cn/Article/details/gt2ozsguwda.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.andypj.xyz/Article/details/gt2hnvoxdjh.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gt2srgzmaqn.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.ivvv.top/Article/details/gt2buzikexv.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gt2uvufivev.html

[T01] Kotlin：Hello World
来源：http://dali.yj20258888.top/Article/details/gt2ejdywspm.html

println("Hello")
来源：http://dali.hywenlv.cn/Article/details/gt2iniwkayc.html

[T02] Kotlin：变量
来源：http://dali.hnqzz.top/Article/details/gt2pwvdxkts.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.9152youxi.cn/Article/details/gt2tthozije.html

[T03] Kotlin：字符串模板
来源：http://dali.jinghuilouyu.cn/Article/details/gt2mtgpglqi.html

"值: $b"
来源：http://dali.cucudq.cn/Article/details/gt2xwaorwuv.html

[T04] Kotlin：空安全
来源：http://dali.svipenyu.cn/Article/details/gt2fzmtemzs.html

val n: String? = null;  n?.length
来源：http://dali.cucudq.cn/Article/details/gt2flhzdxzd.html

[T05] Kotlin：when 表达式
来源：http://dali.jlsjyb.cn/Article/details/gt2hzyvcttv.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.yj202588.top/Article/details/gt2cikhlbxi.html

[T06] Kotlin：集合映射
来源：http://dali.316326.xyz/Article/details/gt2ydpaamcq.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ybugrsnm.html

[T07] Kotlin：集合过滤
来源：http://dali.chenlongwang.top/Article/details/gt2tvacfkan.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.xylfe.cn/Article/details/gt2ilsrjzdy.html

[T08] Kotlin：数据类
来源：http://dali.nwbrower.top/Article/details/gt2ruetxchs.html

data class User(val name: String, val age: Int)
来源：http://dali.daria6918.cn/Article/details/gt2egkrcbkk.html

[T09] Kotlin：扩展函数
来源：http://dali.pycfn.com/Article/details/gt2wtskrsgt.html

fun String.exclaim() = this + "!"
来源：http://dali.mhx1999.top/Article/details/gt2zzlydbtj.html

[T10] Kotlin：默认参数
来源：http://dali.nwbrower.top/Article/details/gt2mstuknvf.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.vqdsnc.cn/Article/details/gt2zukqyhqv.html

[T11] Kotlin：协程
来源：http://dali.aizwys.cn/Article/details/gt2oghwdyuj.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.andypj.xyz/Article/details/gt2odgakrre.html

[T12] Kotlin：解构声明
来源：http://dali.fengsongda.top/Article/details/gt2nrwfptlb.html

val (a, b) = Pair(1, 2)
来源：http://dali.ybcxt.top/Article/details/gt2murdteqh.html

[T13] Kotlin：只读 Map
来源：http://dali.gaohongyu789.top/Article/details/gt2opnqewnb.html

val m = mapOf("a" to 1)
来源：http://dali.gogol.net.cn/Article/details/gt2twsufxwy.html

[T14] Kotlin：循环
来源：http://dali.ivvv.top/Article/details/gt2dyijjlvv.html

for (i in 1..10) println(i)
来源：http://dali.sxryk.cn/Article/details/gt2lagmlnxd.html

[T15] Kotlin：接口
来源：http://dali.chenlongwang.top/Article/details/gt2acqdrcgn.html

interface Shape { fun area(): Double }
来源：http://dali.cheryme.top/Article/details/gt2yhnhescy.html

[T16] Swift：Hello World
来源：http://dali.guannengcc.top/Article/details/gt2jybcfwyz.html

print("Hello")
来源：http://dali.hnqzz.top/Article/details/gt2oewygvve.html

[T17] Swift：变量与常量
来源：http://dali.pengpengdd.cyou/Article/details/gt2skkrgiba.html

var a = 1;  let b = 2
来源：http://dali.guowangkeji.top/Article/details/gt2grycfhyq.html

[T18] Swift：字符串插值
来源：http://dali.ybcxt.top/Article/details/gt2wvboyuzo.html

"值: \(b)"
来源：http://dali.c1oappe.top/Article/details/gt2hxpmmhhk.html

[T19] Swift：可选绑定
来源：http://dali.hywenlv.cn/Article/details/gt2dcymnewt.html

if let n = opt { print(n) }
来源：http://dali.chenjidiqi.icu/Article/details/gt2hczdbsdk.html

[T20] Swift：数组操作
来源：http://dali.0kj1m.cn/Article/details/gt2ozhzfehq.html

var a = [1, 2, 3];  a.append(4)
来源：http://dali.zdqjudy.top/Article/details/gt2bpturcdt.html

[T21] Swift：遍历
来源：http://dali.jiagoushi.top/Article/details/gt2wfefeqyh.html

for x in a { print(x) }
来源：http://dali.dianchejie.cn/Article/details/gt2kyjubzud.html

[T22] Swift：字典
来源：http://dali.jyoumei.cn/Article/details/gt2bjnxdbai.html

var d = ["a": 1];  d["b"] = 2
来源：http://dali.jyoumei.cn/Article/details/gt2vaofhnvr.html


<!-- 参考信息 -->