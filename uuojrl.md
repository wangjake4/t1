代发 wailian999

case "$1" in
来源：http://dali.xinyue.icu/Article/details/gthmtugkun.html

start) echo "启动" ;;
来源：http://dali.jinghuilouyu.cn/Article/details/gttdtpzhfj.html

stop)  echo "停止" ;;
来源：http://dali.jqgfzy.top/Article/details/gtvmowbvop.html

*)     echo "未知命令" ;;
来源：http://dali.jianghu66.top/Article/details/gtzmmwbisc.html

esac
来源：http://dali.redwolf501.top/Article/details/gteworfkpg.html

[R12] for 遍历文件
来源：http://dali.0kj1m.cn/Article/details/gthnlynxmt.html

for f in *.txt; do echo "$f"; done
来源：http://dali.bjfxy.top/Article/details/gtzriscilp.html

[R13] for 计数循环
来源：http://dali.hnxiangtu.top/Article/details/gtfrjnrrho.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xuanzx.com/Article/details/gtlxldufyg.html

[R14] C 风格 for
来源：http://dali.0kj1m.cn/Article/details/gtkekgrzta.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cqqwz.cn/Article/details/gtuiealsta.html

[R15] while 逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiotsuecp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.fengsongda.top/Article/details/gtxcmtyewx.html

[R16] until 等待条件
来源：http://dali.andypj.xyz/Article/details/gtffazyzpi.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.svipenyu.cn/Article/details/gtuuuodydi.html

[R17] 数组定义与取值
来源：http://dali.jqgfzy.top/Article/details/gtowjnzdrl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinqigfzy.top/Article/details/gtmeglqgzw.html

[R18] 遍历数组
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdxsphrzj.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhiwuduotai.top/Article/details/gtypwhkuxv.html

[R19] 数组长度
来源：http://dali.yanxiufei.cn/Article/details/gtlqfvdyip.html

echo "${#arr[@]}"
来源：http://dali.ehwqpu.com/Article/details/gtoyrjpham.html

[R20] 关联数组（字典）
来源：http://dali.jlsjyb.cn/Article/details/gtigoxvwyr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.svipenyu.cn/Article/details/gtuvuglgzy.html

[R21] 字符串长度
来源：http://dali.jlsjyb.cn/Article/details/gtzyeqbpla.html

echo "${#s}"
来源：http://dali.shzxlz.cn/Article/details/gtcppmrxlr.html

[R22] 截取子串
来源：http://dali.yangfankeji.com/Article/details/gthrpbilcw.html

echo "${s:0:5}"
来源：http://dali.hongshengwenyu.top/Article/details/gtycewuhgg.html

[R23] 字符串替换
来源：http://dali.jqgufenzy.top/Article/details/gtvpphctjo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yuanzhike.top/Article/details/gtvzrnyovv.html

[R24] 大小写转换
来源：http://dali.yuxming.cn/Article/details/gtkgdqhkby.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ivvv.top/Article/details/gtgvkssqcr.html

[R25] 去后缀 / 去前缀
来源：http://dali.sufxvd.cn/Article/details/gtukkcmoed.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jlsjyb.cn/Article/details/gturpuwets.html

[R26] 命令替换
来源：http://dali.0kj1m.cn/Article/details/gtxaalpjrr.html

now=$(date +%F); echo "$now"
来源：http://dali.zhoulong.xyz/Article/details/gthmaqjsmy.html

[R27] 算术展开
来源：http://dali.xuanzx.com/Article/details/gtvtxyeugc.html

echo $((1 + 2 * 3))
来源：http://dali.kuanghao11.cn/Article/details/gtclvlddrb.html

[R28] 浮点运算
来源：http://dali.shanyushiyangkeji.top/Article/details/gtspyovhki.html

echo "scale=2; 10/3" | bc
来源：http://dali.c1oappe.top/Article/details/gteaugnutr.html

[R29] 定义函数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvgrxgbbz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.guannengcc.top/Article/details/gtyoxpdbsg.html

[R30] 函数返回状态码
来源：http://dali.zhiwuduotai.top/Article/details/gtztkkyilc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.snrcjt.cn/Article/details/gtkpksmabh.html

[R31] 局部变量
来源：http://dali.aizwys.cn/Article/details/gtkwnzlncy.html

f() { local x=1; echo "$x"; }
来源：http://dali.jiagoushi.top/Article/details/gthvxjvwob.html

[R32] 参数个数校验
来源：http://dali.andypj.xyz/Article/details/gtvxaelfle.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.birdmap.top/Article/details/gtpelysjtq.html

[R33] 捕获错误并提示行号
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjkglgxgw.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.andypj.xyz/Article/details/gtrvgoslwf.html

[R34] 退出时清理
来源：http://dali.gaohongyu789.top/Article/details/gtxgyosopj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.snrcjt.cn/Article/details/gtrialuayd.html

[R35] 后台执行并等待
来源：http://dali.hywenlv.cn/Article/details/gtayydsufp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhiwuduotai.top/Article/details/gtyxznhzlf.html

[R36] 并发执行多个任务
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpnxclass.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.chenzaomai.com/Article/details/gtixpclhzx.html

[R37] 把输出赋给变量
来源：http://dali.gotoacloud.top/Article/details/gtrvimubnv.html

files=$(ls -1)
来源：http://dali.hnqzz.top/Article/details/gttramohdm.html

[R38] 管道串联
来源：http://dali.snrcjt.cn/Article/details/gthllbiqva.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yangfankeji.com/Article/details/gtkxdiqpgr.html

[R39] 重定向标准输出与错误
来源：http://dali.fzhhl.top/Article/details/gttyswuszx.html

cmd > out.log 2>&1
来源：http://dali.ydzc1.top/Article/details/gtjhsswydv.html

[R40] 追加写日志
来源：http://dali.gotoacloud.top/Article/details/gtmjcradwz.html

echo "log" >> out.log
来源：http://dali.yuanzhike.top/Article/details/gtacfsffof.html

[R41] 丢弃输出
来源：http://dali.jyoumei.cn/Article/details/gtajfqbkzd.html

cmd >/dev/null 2>&1
来源：http://dali.hywenlv.cn/Article/details/gtymbvwgbh.html

[R42] 输入重定向
来源：http://dali.hongshengwenyu.top/Article/details/gtcubyumdl.html

wc -l < a.txt
来源：http://dali.jinqigfzy.top/Article/details/gthfdmdjhi.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gtmhxmrlxw.html

find . -name "*.log" -type f
来源：http://dali.yvedp.cn/Article/details/gtjbwjhgfn.html

[R44] 按修改时间查找
来源：http://dali.jinghuilouyu.cn/Article/details/gtmxiikbzm.html

find . -mtime -7 -type f
来源：http://dali.mhx1999.top/Article/details/gtfpwybewn.html

[R45] 批量删除
来源：http://dali.shangyingyoupin.top/Article/details/gtksqfveyk.html

find . -name "*.tmp" -delete
来源：http://dali.ivvv.top/Article/details/gthnoqijzc.html

[R46] 递归替换文件内容
来源：http://dali.cdnleiting.top/Article/details/gtmwdlxlha.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.pengpengdd.cyou/Article/details/gtfbqvpodc.html

[R47] sed 单行替换
来源：http://dali.gotoacloud.top/Article/details/gtxydskkgx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtxgogvnmw.html

[R48] awk 取指定列
来源：http://dali.yonumen.top/Article/details/gtgcjzvxfr.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gtzaypmthk.html

[R49] awk 带条件
来源：http://dali.ppjwa.cn/Article/details/gtdfaztnsi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zdqjudy.top/Article/details/gtmvmjmnwu.html

[R50] awk 求和
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyaainjaf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtcyniimht.html

[R51] 排序去重取前几
来源：http://dali.pengpengdd.cyou/Article/details/gtzlrqvvgc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.haohaochexian.top/Article/details/gthhdeymqy.html

[R52] 统计行数
来源：http://dali.yvedp.cn/Article/details/gtbwcqsnxi.html

wc -l a.txt
来源：http://dali.zhengqikj.top/Article/details/gthyidbjwm.html

[R53] 查看文件头与实时尾
来源：http://dali.jqgfzy.top/Article/details/gtjccpvche.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhongyouzk.top/Article/details/gthnxezjsz.html

[R54] 比较两个文件
来源：http://dali.xylfe.cn/Article/details/gtexyynnuu.html

diff a.txt b.txt
来源：http://dali.shzxlz.cn/Article/details/gtkvqeball.html

[R55] 压缩与解压
来源：http://dali.mhx1999.top/Article/details/gtehppetbp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yueranfly.top/Article/details/gtgmdquuie.html

[R56] 远程拷贝
来源：http://dali.redwolf501.top/Article/details/gtnxwyjfgz.html

scp file user@host:/path/
来源：http://dali.yuanzhike.top/Article/details/gtewjojjgt.html

[R57] 远程执行命令
来源：http://dali.xylfe.cn/Article/details/gtizstibdg.html

ssh user@host 'uptime'
来源：http://dali.shanyushiyangtech.top/Article/details/gtoxcshlgj.html

[R58] 下载文件
来源：http://dali.hammf.cn/Article/details/gtotzbegfb.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yongpay.top/Article/details/gtzczytosx.html

[R59] 发 POST JSON
来源：http://dali.tianlin.xyz/Article/details/gtlnnmetqa.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.c1oappe.top/Article/details/gtofvzjrzw.html

[R60] 只看 HTTP 状态码
来源：http://dali.wangshuangyany.cn/Article/details/gtxslxksfc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.meibo888.top/Article/details/gtsdwkegdf.html

[R61] 磁盘占用
来源：http://dali.zdqjudy.top/Article/details/gttlgukksq.html

df -h;  du -sh *
来源：http://dali.gotoacloud.top/Article/details/gtknzoxdzw.html

[R62] 找最占空间的文件
来源：http://dali.cdnleiting.top/Article/details/gtmlsbysag.html

du -ah . | sort -rh | head -10
来源：http://dali.xziqi.cn/Article/details/gttwrmykus.html

[R63] 内存与进程
来源：http://dali.xuetiantiany.cn/Article/details/gtpexekjbh.html

free -h;  ps aux | grep nginx
来源：http://dali.fzhhl.top/Article/details/gtsesckaqw.html

[R64] 结束进程
来源：http://dali.dianchejie.cn/Article/details/gtuyjvtzbe.html

kill -9 $(pgrep -f app.py)
来源：http://dali.mhx1999.top/Article/details/gtmhmgreym.html

[R65] 查看端口占用
来源：http://dali.jinghuilouyu.cn/Article/details/gtiukptoko.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.mhx1999.top/Article/details/gtklligfgg.html

[R66] 定时任务
来源：http://dali.xuanzx.com/Article/details/gtuoigebty.html

crontab -e;  crontab -l
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgpluhlig.html

[R67] 生成随机十六进制串
来源：http://dali.0kj1m.cn/Article/details/gtamcpknhl.html

openssl rand -hex 16
来源：http://dali.tian-w.cn/Article/details/gtzeuzyidt.html

[R68] 计算文件校验值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtttsothxw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.nwbrower.top/Article/details/gtuwbiqsvh.html

[R69] 生成随机密码
来源：http://dali.daxiang520.top/Article/details/gtjjkokrgk.html

head -c 16 /dev/urandom | base64
来源：http://dali.snrcjt.cn/Article/details/gtjrxadslf.html

[R70] 时间戳与互转
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnrbxqvvx.html

date +%s;  date -d @1700000000
来源：http://dali.shanyushiyangtech.top/Article/details/gtuwfukcwi.html

[R71] 日期格式化
来源：http://dali.zhiwuduotai.top/Article/details/gtppbboldj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.wangdashe.top/Article/details/gtaskiffqd.html

[R72] 等待端口就绪
来源：http://dali.9152youxi.cn/Article/details/gtpvybxjdh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.tianlin.xyz/Article/details/gtzhjibzaf.html

[R73] 分割大日志
来源：http://dali.shuidangran.top/Article/details/gtgfcuoidm.html

split -l 1000 big.log part_
来源：http://dali.xziqi.cn/Article/details/gtpmjjmglh.html

[R74] 批量重命名
来源：http://dali.ehwqpu.com/Article/details/gtltnzwdts.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.316326.xyz/Article/details/gtvmdkzpjt.html

[R75] 导出环境变量
来源：http://dali.yuxming.cn/Article/details/gtoqdcqdas.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.nanxuanxn.top/Article/details/gtrltlvwyw.html

[R76] 使用临时文件
来源：http://dali.zhixingplan.top/Article/details/gtwvzyyhdi.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xziqi.cn/Article/details/gtzeyicdks.html

[R77] 读取用户输入
来源：http://dali.gogol.net.cn/Article/details/gtmtjkjjup.html

read -rp "请输入: " ans
来源：http://dali.hysaishi.cn/Article/details/gtspwjspez.html

[R78] 交互式菜单
来源：http://dali.nanxinkj.top/Article/details/gtcugiptjj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jqgfzy.top/Article/details/gtgdqipbtd.html

[R79] 解析命令行选项
来源：http://dali.shuidangran.top/Article/details/gtzzykrmuo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yuxming.cn/Article/details/gtpuudynpa.html

[R80] 查看脚本执行耗时
来源：http://dali.guowangkeji.top/Article/details/gtxypaleoq.html

time ./run.sh
来源：http://dali.sweek.top/Article/details/gtmrldtgbs.html

================================================================================
来源：http://dali.jinqigfzy.top/Article/details/gtqbiebwmd.html

S. C / C++ 专题
来源：http://dali.aibaodan.cn/Article/details/gtvdnyrbuw.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gtznspuyej.html

[S01] C：Hello World
来源：http://dali.aizwys.cn/Article/details/gtlzlerjaq.html

#include <stdio.h>
来源：http://dali.jqgfzy.top/Article/details/gtjuopcefs.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.wangdashe.top/Article/details/gtyshelhgj.html

[S02] C：变量与格式化输出
来源：http://dali.guannengcc.top/Article/details/gtjwwnfwfx.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinqigufen.top/Article/details/gtwrqjpkdh.html

[S03] C：读入整数
来源：http://dali.meibo888.top/Article/details/gtapbvlizf.html

int x; scanf("%d", &x);
来源：http://dali.xylfe.cn/Article/details/gtxbpzotlf.html

[S04] C：字符串复制
来源：http://dali.nanxinkj.top/Article/details/gtbimbnjet.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.tian-w.cn/Article/details/gtmnpznzqd.html

[S05] C：字符串长度
来源：http://dali.vqdsnc.cn/Article/details/gtlwrrjzom.html

strlen(s)
来源：http://dali.guannengcc.top/Article/details/gtvmpgttem.html

[S06] C：字符串比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgemxtgon.html

strcmp(a, b) == 0
来源：http://dali.andypj.xyz/Article/details/gtjjfltkaj.html

[S07] C：数组遍历求和
来源：http://dali.c1oappe.top/Article/details/gtwrbvgwdg.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shangyingyoupin.top/Article/details/gtxtflgohp.html

[S08] C：动态内存分配与释放
来源：http://dali.xuetiantiany.cn/Article/details/gtuvryimps.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.hongshengwenyu.top/Article/details/gtyhdyfids.html

[S09] C：结构体定义与初始化
来源：http://dali.shanyushiyangtech.top/Article/details/gtgvfcmloe.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ehwqpu.com/Article/details/gtpkfeoikc.html

[S10] C：指针与解引用
来源：http://dali.jqgufenzy.top/Article/details/gtrnwipxnu.html

int *p = &a;  *p = 5;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqxdvowyj.html

[S11] C：逐行读文件
来源：http://dali.mhx1999.top/Article/details/gtqefdonpf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.pengpengdd.cyou/Article/details/gtjkjezohq.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cqqwz.cn/Article/details/gtftqwwsum.html

fclose(f);
来源：http://dali.cdnleiting.top/Article/details/gthsljzzcv.html

[S12] C：写文件
来源：http://dali.wangshuangyany.cn/Article/details/gtlgwxsvhv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xziqi.cn/Article/details/gtohirjnnc.html

[S13] C：宏定义
来源：http://dali.fzhhl.top/Article/details/gtqujhhvcd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.andypj.xyz/Article/details/gtbwljurvr.html

[S14] C：枚举
来源：http://dali.yangfankeji.com/Article/details/gtltqnjqim.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.bjfxy.top/Article/details/gtzpentmcz.html

[S15] C：类型转换
来源：http://dali.zhiwuduotai.top/Article/details/gtluqwveek.html

(double) a / b
来源：http://dali.cheryme.top/Article/details/gtjppbqstm.html

[S16] C：位操作置位
来源：http://dali.birdmap.top/Article/details/gtlqqysmpt.html

x |= (1 << 3);
来源：http://dali.hfpthk.cn/Article/details/gtxczfettv.html

[S17] C：安全拼接字符串
来源：http://dali.ydzc1.top/Article/details/gtdorxmjvr.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yuanzhike.top/Article/details/gtnpsnuwij.html

[S18] C：命令行参数
来源：http://dali.hfpthk.cn/Article/details/gtabxihdhc.html

int main(int argc, char **argv)
来源：http://dali.hnqzz.top/Article/details/gtgsiuqgvc.html

[S19] C：快速排序
来源：http://dali.jinqigufen.top/Article/details/gtvsskrkic.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jinqigfzy.top/Article/details/gtcwckgxqp.html

[S20] C：二分查找
来源：http://dali.jqgufenzy.top/Article/details/gtlucngmbd.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.quarkkingdee.top/Article/details/gtoczgjzsb.html

[S21] C：字符类别判断
来源：http://dali.pengpengdd.cyou/Article/details/gtbwbebvru.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.redwolf501.top/Article/details/gtiqmygkuf.html

[S22] C：字符串转数字
来源：http://dali.ivvv.top/Article/details/gtevrtvftt.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.snrcjt.cn/Article/details/gtutojkwly.html

[S23] C：随机数
来源：http://dali.hnxiangtu.top/Article/details/gtkwwcfneu.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yanxiufei.cn/Article/details/gtjxcsxsay.html

[S24] C：获取本地时间
来源：http://dali.jinqigfzy.top/Article/details/gtjzjhhpnj.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.jinqigufen.top/Article/details/gtdfwswxyx.html

[S25] C：内存拷贝
来源：http://dali.aibaodan.cn/Article/details/gtvxmtckfy.html

memcpy(dst, src, n);
来源：http://dali.smart0.xyz/Article/details/gtxqrjxyub.html

[S26] C：内存清零
来源：http://dali.sxryk.cn/Article/details/gtcmwaaegl.html

memset(a, 0, sizeof a);
来源：http://dali.jqgufenzy.top/Article/details/gtqsfxdwgz.html

[S27] C：定义常量
来源：http://dali.bjfxy.top/Article/details/gtgkhfmmqu.html

const double PI = 3.14159;
来源：http://dali.yonumen.top/Article/details/gtuniguzzk.html

[S28] C：静态变量
来源：http://dali.snrcjt.cn/Article/details/gtdnwpjobl.html

static int counter = 0;
来源：http://dali.pycfn.com/Article/details/gtlmjyhsdh.html

[S29] C：变参函数
来源：http://dali.xuetiantiany.cn/Article/details/gteaeiptua.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.daxiang520.top/Article/details/gtgpoxcehr.html

[S30] C：头文件保护
来源：http://dali.meibo888.top/Article/details/gtivydzhzb.html

#ifndef X_H
来源：http://dali.chenlongwang.top/Article/details/gtismnjdhm.html

#define X_H
来源：http://dali.hfpthk.cn/Article/details/gtgevjbsvz.html

#endif
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxyrtuabc.html

[S31] C++：Hello World
来源：http://dali.ybcxt.top/Article/details/gtbkndgcre.html

#include <iostream>
来源：http://dali.0kj1m.cn/Article/details/gtefufgkgl.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtdqxnczbz.html

[S32] C++：字符串
来源：http://dali.xylfe.cn/Article/details/gtngbzgjqa.html

std::string s = "hi";  s += "!";
来源：http://dali.guowangkeji.top/Article/details/gtbezwuzah.html

[S33] C++：vector 增删
来源：http://dali.cdnleiting.top/Article/details/gtvwodkguu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.hongshengwenyu.top/Article/details/gtrrjuphmw.html

[S34] C++：遍历 vector
来源：http://dali.zdqjudy.top/Article/details/gteykxwsns.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.mhx1999.top/Article/details/gtfxtmjvba.html

[S35] C++：map
来源：http://dali.c1oappe.top/Article/details/gtezoucbrs.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yanxiufei.cn/Article/details/gtaieckypc.html

[S36] C++：unordered_map
来源：http://dali.quarkkingdee.top/Article/details/gtsyjfkpar.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gtvmxvxsoj.html

[S37] C++：set
来源：http://dali.shuidangran.top/Article/details/gtxdpynvjj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.chenlongwang.top/Article/details/gtijbimfix.html

[S38] C++：排序
来源：http://dali.9152youxi.cn/Article/details/gtvkkttrnf.html

std::sort(v.begin(), v.end());
来源：http://dali.zhaomingkeji.xyz/Article/details/gthpbjfaru.html

[S39] C++：自定义比较器排序
来源：http://dali.guowangkeji.top/Article/details/gteqbgnyqf.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.sxryk.cn/Article/details/gtdcgxyygz.html

[S40] C++：查找元素
来源：http://dali.smart0.xyz/Article/details/gtzmwyfrwt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.shuidangran.top/Article/details/gtcyzxgrwd.html

[S41] C++：类与构造函数
来源：http://dali.cashguo.top/Article/details/gtfzryvmhp.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjcshumbz.html

[S42] C++：继承与虚函数
来源：http://dali.pengpengdd.cyou/Article/details/gtpohnahon.html

class B : public Base { public: void f() override {} };
来源：http://dali.jinqigufen.top/Article/details/gtsjvxvcat.html

[S43] C++：智能指针
来源：http://dali.feifeiyinyue.top/Article/details/gtocdggudi.html

auto p = std::make_unique<int>(5);
来源：http://dali.mhx1999.top/Article/details/gtasbiewom.html

[S44] C++：引用传参
来源：http://dali.xuanzx.com/Article/details/gtviugwbzn.html

void inc(int &x) { ++x; }
来源：http://dali.yuanzhike.top/Article/details/gtfjmvmehf.html

[S45] C++：lambda
来源：http://dali.andypj.xyz/Article/details/gtjhtavfqs.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.andypj.xyz/Article/details/gtbduvxogf.html

[S46] C++：函数模板
来源：http://dali.haohaochexian.top/Article/details/gtrcazfqhh.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.chenjidiqi.icu/Article/details/gtyevkunie.html

[S47] C++：结构化绑定遍历
来源：http://dali.aizwys.cn/Article/details/gtmqsaqcdv.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtagmgrwzt.html

[S48] C++：逐行读文件
来源：http://dali.sxryk.cn/Article/details/gtadndiaan.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.xinyue.icu/Article/details/gtkwalpnun.html

while (std::getline(in, line)) { }
来源：http://dali.hnxiangtu.top/Article/details/gtrsitazey.html

[S49] C++：写文件
来源：http://dali.zhoulong.xyz/Article/details/gtmjcnbssv.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jqgufenzy.top/Article/details/gtuvriprxp.html

[S50] C++：格式化数字
来源：http://dali.smart0.xyz/Article/details/gtrbvqvjaj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.kuanghao11.cn/Article/details/gtnohohjxs.html

[S51] C++：显式类型转换
来源：http://dali.shuidangran.top/Article/details/gtnsarkxeg.html

static_cast<double>(a) / b
来源：http://dali.zhiwuduotai.top/Article/details/gtzofeosun.html

[S52] C++：const 与 noexcept
来源：http://dali.yuxming.cn/Article/details/gtkrtocqqd.html

int size() const noexcept { return n_; }
来源：http://dali.hysaishi.cn/Article/details/gtbiidigoc.html

[S53] C++：移动语义
来源：http://dali.pengpengdd.cyou/Article/details/gtylcosmkg.html

std::vector<int> w = std::move(v);
来源：http://dali.aizwys.cn/Article/details/gtgfewtrgc.html

[S54] C++：异常处理
来源：http://dali.9152youxi.cn/Article/details/gtmchgyvhc.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.hysaishi.cn/Article/details/gtcgldkemf.html

[S55] C++：结构化绑定
来源：http://dali.fengsongda.top/Article/details/gtrobhovlc.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.jiagoushi.top/Article/details/gttelynbqr.html

[S56] C++：optional
来源：http://dali.sufxvd.cn/Article/details/gtuaatkbdh.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.pycfn.com/Article/details/gtpsmgjxjr.html

[S57] C++：编译期常量
来源：http://dali.sufxvd.cn/Article/details/gtmgwwijab.html

constexpr int N = 10;
来源：http://dali.ydzc1.top/Article/details/gtgouvvhsc.html

[S58] C++：命名空间
来源：http://dali.gaohongyu789.top/Article/details/gtbceqfdtx.html

namespace ns { int f() { return 1; } }
来源：http://dali.nanxinkj.top/Article/details/gtxqzrngxb.html

[S59] C++：静态断言
来源：http://dali.zhoulong.xyz/Article/details/gtkoargciq.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.pengpengdd.cyou/Article/details/gtywgxtjyg.html

[S60] C++：遍历并删除元素
来源：http://dali.zhoulong.xyz/Article/details/gtsmqvcsah.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.jqgfzy.top/Article/details/gtdcospafi.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtvisekwfk.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.pycfn.com/Article/details/gtbgpqtjpe.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtwnhmuqih.html

[T01] Kotlin：Hello World
来源：http://dali.snrcjt.cn/Article/details/gtodxgxemd.html

println("Hello")
来源：http://dali.hywenlv.cn/Article/details/gtvibhsdxw.html

[T02] Kotlin：变量
来源：http://dali.xuetiantiany.cn/Article/details/gtdddelvti.html

val a = 1;  var b = 2        // val 只读，var 可变
来源：http://dali.gaohongyu789.top/Article/details/gtxwfutgen.html

[T03] Kotlin：字符串模板
来源：http://dali.cashguo.top/Article/details/gtjoexiglq.html

"值: $b"
来源：http://dali.pycfn.com/Article/details/gtdophsmco.html

[T04] Kotlin：空安全
来源：http://dali.aizwys.cn/Article/details/gtmqjxsuhj.html

val n: String? = null;  n?.length
来源：http://dali.gogol.net.cn/Article/details/gtbysojyez.html

[T05] Kotlin：when 表达式
来源：http://dali.haohaochexian.top/Article/details/gtpculyzoc.html

val s = when (x) { 1 -> "一" else -> "其他" }   // 多分支时每个分支单独一行
来源：http://dali.sxryk.cn/Article/details/gtdtzozgnn.html

[T06] Kotlin：集合映射
来源：http://dali.quarkkingdee.top/Article/details/gtgdliaokf.html

listOf(1, 2, 3).map { it * 2 }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzfiycuwz.html

[T07] Kotlin：集合过滤
来源：http://dali.jinghuilouyu.cn/Article/details/gtpvynhzgl.html

listOf(1, 2, 3).filter { it > 1 }
来源：http://dali.sufxvd.cn/Article/details/gtmzstxarh.html

[T08] Kotlin：数据类
来源：http://dali.ivvv.top/Article/details/gtvocrgxsm.html

data class User(val name: String, val age: Int)
来源：http://dali.yanxiufei.cn/Article/details/gtyuinxpsc.html

[T09] Kotlin：扩展函数
来源：http://dali.zhaomingkeji.xyz/Article/details/gthmyxkemn.html

fun String.exclaim() = this + "!"
来源：http://dali.cheryme.top/Article/details/gtbajzzzur.html

[T10] Kotlin：默认参数
来源：http://dali.jinqigfzy.top/Article/details/gtqdxguowd.html

fun greet(name: String = "World") = "Hi $name"
来源：http://dali.tianlin.xyz/Article/details/gtjcaqmpgj.html

[T11] Kotlin：协程
来源：http://dali.yueranfly.top/Article/details/gtlrxngrji.html

GlobalScope.launch { delay(1000); println("done") }
来源：http://dali.daria6918.cn/Article/details/gtmxzjfeqf.html

[T12] Kotlin：解构声明
来源：http://dali.guowangkeji.top/Article/details/gtrhzucpez.html

val (a, b) = Pair(1, 2)
来源：http://dali.dianchejie.cn/Article/details/gtiprxxabe.html


<!-- 参考信息 -->