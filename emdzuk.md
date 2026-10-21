代发 wailian999

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zdqjudy.top/Article/details/gtvnzfwhcr.html

[Q90] 生成序号列
来源：http://dali.yanxiufei.cn/Article/details/gttrpcfhlo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xziqi.cn/Article/details/gthpfoecos.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtnwdqamqn.html

R. Bash 专题
来源：http://dali.yueranfly.top/Article/details/gtftqwzxuz.html

================================================================================
来源：http://dali.jiagoushi.top/Article/details/gtenlwqojm.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gtflhlazql.html

#!/usr/bin/env bash
来源：http://dali.hywenlv.cn/Article/details/gtfktehijo.html

set -euo pipefail
来源：http://dali.gaohongyu789.top/Article/details/gtljavjnjx.html

[R02] 变量赋值与使用
来源：http://dali.quarkkingdee.top/Article/details/gtfvjkiwlw.html

name="Tom"; echo "$name"
来源：http://dali.cqqwz.cn/Article/details/gtmaaqlfmq.html

[R03] 只读变量
来源：http://dali.9152youxi.cn/Article/details/gtolgcsuel.html

readonly PI=3.14
来源：http://dali.andypj.xyz/Article/details/gtezyxiyxn.html

[R04] 位置参数
来源：http://dali.yangfankeji.com/Article/details/gthchbfukj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.pengpengdd.cyou/Article/details/gtcvhnffst.html

[R05] 参数默认值
来源：http://dali.hongshengwenyu.top/Article/details/gtekeuaheb.html

name="${1:-default}"
来源：http://dali.hysaishi.cn/Article/details/gttcevpyyd.html

[R06] 判断命令是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtaykdwljx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.aibaodan.cn/Article/details/gtejnedqtr.html

[R07] if 判断文件
来源：http://dali.jinqigufen.top/Article/details/gthbtedmub.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.pycfn.com/Article/details/gtpquzswlt.html

[R08] 数值比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtcgdlxyrw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.guowangkeji.top/Article/details/gtlejjaybz.html

[R09] 字符串比较
来源：http://dali.guowangkeji.top/Article/details/gtecmpvatk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xziqi.cn/Article/details/gtnglzrmaf.html

[R10] 正则匹配
来源：http://dali.yonumen.top/Article/details/gtydeuntno.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.andypj.xyz/Article/details/gtwafzhedd.html

[R11] case 多分支
来源：http://dali.yanxiufei.cn/Article/details/gtchngxilg.html

case "$1" in
来源：http://dali.ehwqpu.com/Article/details/gtslefretz.html

start) echo "启动" ;;
来源：http://dali.9152youxi.cn/Article/details/gtuozxbmik.html

stop)  echo "停止" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjovjmexk.html

*)     echo "未知命令" ;;
来源：http://dali.feifeiyinyue.top/Article/details/gtwqychurs.html

esac
来源：http://dali.daria6918.cn/Article/details/gtkocgkirh.html

[R12] for 遍历文件
来源：http://dali.dashuyun.cn/Article/details/gtzbfvcgjr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.quarkkingdee.top/Article/details/gtdeipbgkx.html

[R13] for 计数循环
来源：http://dali.gotoacloud.top/Article/details/gtlgqkuaxr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hywenlv.cn/Article/details/gtfxelpxur.html

[R14] C 风格 for
来源：http://dali.zdqjudy.top/Article/details/gtxfpjwqpu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.quarkkingdee.top/Article/details/gtgyfyqpsn.html

[R15] while 逐行读文件
来源：http://dali.hnqzz.top/Article/details/gtmuzpybxm.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xylfe.cn/Article/details/gtneupfpvo.html

[R16] until 等待条件
来源：http://dali.nanxinkj.top/Article/details/gtqniiovfv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.iojbl.cn/Article/details/gthkaclqwq.html

[R17] 数组定义与取值
来源：http://dali.xinyue.icu/Article/details/gtzbatgfcc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhongyouzk.top/Article/details/gtkuorsbbv.html

[R18] 遍历数组
来源：http://dali.snrcjt.cn/Article/details/gthjlryifw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yvedp.cn/Article/details/gtqnodlwqc.html

[R19] 数组长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcroaagow.html

echo "${#arr[@]}"
来源：http://dali.cashguo.top/Article/details/gtmexjmmbn.html

[R20] 关联数组（字典）
来源：http://dali.jyoumei.cn/Article/details/gtxfzgyrfy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.daxiang520.top/Article/details/gthfipbuzp.html

[R21] 字符串长度
来源：http://dali.daxiang520.top/Article/details/gtuavcxhcx.html

echo "${#s}"
来源：http://dali.dianchejie.cn/Article/details/gtgtufjxia.html

[R22] 截取子串
来源：http://dali.9152youxi.cn/Article/details/gtquyaiuit.html

echo "${s:0:5}"
来源：http://dali.fengsongda.top/Article/details/gtgjuvsihc.html

[R23] 字符串替换
来源：http://dali.hnxiangtu.top/Article/details/gtxdgmtqcv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hywenlv.cn/Article/details/gtvwmqjexe.html

[R24] 大小写转换
来源：http://dali.chenjidiqi.icu/Article/details/gtbfqvjyhq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.birdmap.top/Article/details/gtjsosuwyt.html

[R25] 去后缀 / 去前缀
来源：http://dali.yueranfly.top/Article/details/gtivxoxeai.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xylfe.cn/Article/details/gtrxxkaghk.html

[R26] 命令替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtqprftsnm.html

now=$(date +%F); echo "$now"
来源：http://dali.zhongyouzk.top/Article/details/gtevylitsf.html

[R27] 算术展开
来源：http://dali.hammf.cn/Article/details/gtpsjmqhcc.html

echo $((1 + 2 * 3))
来源：http://dali.meibo888.top/Article/details/gtuoavbtgu.html

[R28] 浮点运算
来源：http://dali.chenzaomai.com/Article/details/gtnnkwnffw.html

echo "scale=2; 10/3" | bc
来源：http://dali.hnqzz.top/Article/details/gtecwswdar.html

[R29] 定义函数
来源：http://dali.aizwys.cn/Article/details/gtvibkgohh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.iojbl.cn/Article/details/gtdjeqnumn.html

[R30] 函数返回状态码
来源：http://dali.sufxvd.cn/Article/details/gtqmionxcq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.snrcjt.cn/Article/details/gtlgexmkrx.html

[R31] 局部变量
来源：http://dali.sweek.top/Article/details/gtogyoueou.html

f() { local x=1; echo "$x"; }
来源：http://dali.nanxinkj.top/Article/details/gttgcmtzvv.html

[R32] 参数个数校验
来源：http://dali.wangdashe.top/Article/details/gtwcdbxyrp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.tanke756.top/Article/details/gtbdlyvsol.html

[R33] 捕获错误并提示行号
来源：http://dali.sysykeji.top/Article/details/gtsyytblfq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhixingplan.top/Article/details/gtlcpwbzov.html

[R34] 退出时清理
来源：http://dali.yj202588.top/Article/details/gtdfkxggks.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.vqdsnc.cn/Article/details/gtndcfgztq.html

[R35] 后台执行并等待
来源：http://dali.9152youxi.cn/Article/details/gttebbeusz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.chenlongwang.top/Article/details/gtnwvziwpk.html

[R36] 并发执行多个任务
来源：http://dali.wangshuangyany.cn/Article/details/gtoagbxciz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ydzc1.top/Article/details/gtzzgvjxbo.html

[R37] 把输出赋给变量
来源：http://dali.jinqigfzy.top/Article/details/gtalcejtyo.html

files=$(ls -1)
来源：http://dali.yangfankeji.com/Article/details/gtabggbykd.html

[R38] 管道串联
来源：http://dali.birdmap.top/Article/details/gtfokcnxur.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoriyncrp.html

[R39] 重定向标准输出与错误
来源：http://dali.yuxming.cn/Article/details/gtrsomjkmj.html

cmd > out.log 2>&1
来源：http://dali.yuxming.cn/Article/details/gtsjnucahm.html

[R40] 追加写日志
来源：http://dali.xuanzx.com/Article/details/gtxfoojoui.html

echo "log" >> out.log
来源：http://dali.tianlin.xyz/Article/details/gtumaaznjy.html

[R41] 丢弃输出
来源：http://dali.cqqwz.cn/Article/details/gtzjexoxec.html

cmd >/dev/null 2>&1
来源：http://dali.jyoumei.cn/Article/details/gtqmjmvrfu.html

[R42] 输入重定向
来源：http://dali.yuxming.cn/Article/details/gtdzyrjzwn.html

wc -l < a.txt
来源：http://dali.zhongyouzk.top/Article/details/gtjglieram.html

[R43] 按名字查找文件
来源：http://dali.hysaishi.cn/Article/details/gtnjhgvkhh.html

find . -name "*.log" -type f
来源：http://dali.shzxlz.cn/Article/details/gtitnnjtcm.html

[R44] 按修改时间查找
来源：http://dali.quarkkingdee.top/Article/details/gtveltnmuw.html

find . -mtime -7 -type f
来源：http://dali.dianchejie.cn/Article/details/gtgxlrgfmt.html

[R45] 批量删除
来源：http://dali.jlsjyb.cn/Article/details/gtnatqhuqa.html

find . -name "*.tmp" -delete
来源：http://dali.ivvv.top/Article/details/gtagmqlyjf.html

[R46] 递归替换文件内容
来源：http://dali.cqqwz.cn/Article/details/gtfeyjjrwz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.sxryk.cn/Article/details/gtudrhaibk.html

[R47] sed 单行替换
来源：http://dali.yonumen.top/Article/details/gtddluzzxd.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.guowangkeji.top/Article/details/gteccflveq.html

[R48] awk 取指定列
来源：http://dali.svipenyu.cn/Article/details/gtcbfdqmop.html

awk '{print $1, $3}' a.txt
来源：http://dali.sufxvd.cn/Article/details/gtrdfatmnd.html

[R49] awk 带条件
来源：http://dali.c1oappe.top/Article/details/gtmswcrrsi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.daxiang520.top/Article/details/gtxteibcbx.html

[R50] awk 求和
来源：http://dali.yuxming.cn/Article/details/gtmjievoum.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtqnclmmvb.html

[R51] 排序去重取前几
来源：http://dali.nanxuanxn.top/Article/details/gttzpzhful.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jiagoushi.top/Article/details/gtgjionyvx.html

[R52] 统计行数
来源：http://dali.yuanzhike.top/Article/details/gtpooijlew.html

wc -l a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtyzadvons.html

[R53] 查看文件头与实时尾
来源：http://dali.zhiwuduotai.top/Article/details/gticbklsnx.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.chenjidiqi.icu/Article/details/gtmaecbwpo.html

[R54] 比较两个文件
来源：http://dali.sxryk.cn/Article/details/gtpzpvgjgf.html

diff a.txt b.txt
来源：http://dali.hywenlv.cn/Article/details/gtozyehacp.html

[R55] 压缩与解压
来源：http://dali.jyoumei.cn/Article/details/gtiovoahus.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jianghu66.top/Article/details/gttvixigsp.html

[R56] 远程拷贝
来源：http://dali.xinyue.icu/Article/details/gtmcimcpzm.html

scp file user@host:/path/
来源：http://dali.sweek.top/Article/details/gtalcnnqzc.html

[R57] 远程执行命令
来源：http://dali.316326.xyz/Article/details/gtczczvpkj.html

ssh user@host 'uptime'
来源：http://dali.birdmap.top/Article/details/gtlhmdgfst.html

[R58] 下载文件
来源：http://dali.cheryme.top/Article/details/gtxvjjbjbe.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nanxuanxn.top/Article/details/gtnhqubphk.html

[R59] 发 POST JSON
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfxxvwhbu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.svipenyu.cn/Article/details/gthosdoijy.html

[R60] 只看 HTTP 状态码
来源：http://dali.yvedp.cn/Article/details/gtdpmknbpm.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhoulong.xyz/Article/details/gtdsefzqob.html

[R61] 磁盘占用
来源：http://dali.meibo888.top/Article/details/gtzrutnytw.html

df -h;  du -sh *
来源：http://dali.redwolf501.top/Article/details/gtjveckxnc.html

[R62] 找最占空间的文件
来源：http://dali.316326.xyz/Article/details/gtcmxjletd.html

du -ah . | sort -rh | head -10
来源：http://dali.zdqjudy.top/Article/details/gtwwiwjyor.html

[R63] 内存与进程
来源：http://dali.guowangkeji.top/Article/details/gtrwibejfi.html

free -h;  ps aux | grep nginx
来源：http://dali.haohaochexian.top/Article/details/gthddlvgdo.html

[R64] 结束进程
来源：http://dali.ydzc1.top/Article/details/gtwgwokjut.html

kill -9 $(pgrep -f app.py)
来源：http://dali.pycfn.com/Article/details/gtwkvptqud.html

[R65] 查看端口占用
来源：http://dali.ppjwa.cn/Article/details/gtdnxfqofr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.nwbrower.top/Article/details/gtgtxvzswi.html

[R66] 定时任务
来源：http://dali.quarkkingdee.top/Article/details/gtzguhfrhw.html

crontab -e;  crontab -l
来源：http://dali.jinqigufen.top/Article/details/gtqwxheegx.html

[R67] 生成随机十六进制串
来源：http://dali.xziqi.cn/Article/details/gtiooqbjvx.html

openssl rand -hex 16
来源：http://dali.snrcjt.cn/Article/details/gtejpiikof.html

[R68] 计算文件校验值
来源：http://dali.yanxiufei.cn/Article/details/gtmqcuuurg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ydzc1.top/Article/details/gtrmdoylrw.html

[R69] 生成随机密码
来源：http://dali.gotoacloud.top/Article/details/gtdprtthyg.html

head -c 16 /dev/urandom | base64
来源：http://dali.xuetiantiany.cn/Article/details/gtvllhgbtn.html

[R70] 时间戳与互转
来源：http://dali.ehwqpu.com/Article/details/gtusjbtjue.html

date +%s;  date -d @1700000000
来源：http://dali.jqgfzy.top/Article/details/gthuzowsib.html

[R71] 日期格式化
来源：http://dali.birdmap.top/Article/details/gtvzgsxfmq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.tianlin.xyz/Article/details/gtqywqpiyh.html

[R72] 等待端口就绪
来源：http://dali.aizwys.cn/Article/details/gtwrzeuncf.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xinyue.icu/Article/details/gtqikvdtzu.html

[R73] 分割大日志
来源：http://dali.xylfe.cn/Article/details/gtvoglzykg.html

split -l 1000 big.log part_
来源：http://dali.yongpay.top/Article/details/gtuzdxrwoe.html

[R74] 批量重命名
来源：http://dali.gzhubu.top/Article/details/gtknursihl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.kuanghao11.cn/Article/details/gtlfvwawiz.html

[R75] 导出环境变量
来源：http://dali.9152youxi.cn/Article/details/gtvnfzpvbw.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jqgfzy.top/Article/details/gtmcvtjjmm.html

[R76] 使用临时文件
来源：http://dali.xuanzx.com/Article/details/gtqudshgmp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnxiangtu.top/Article/details/gtcyfqpgrf.html

[R77] 读取用户输入
来源：http://dali.yonumen.top/Article/details/gtcvkqsksb.html

read -rp "请输入: " ans
来源：http://dali.smart0.xyz/Article/details/gtaupwqgsc.html

[R78] 交互式菜单
来源：http://dali.zhongyouzk.top/Article/details/gtuwrhugei.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jiagoushi.top/Article/details/gtkylengcc.html

[R79] 解析命令行选项
来源：http://dali.bjfxy.top/Article/details/gtohmbsshr.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.aizwys.cn/Article/details/gtcgmvwukh.html

[R80] 查看脚本执行耗时
来源：http://dali.chenlongwang.top/Article/details/gtfpruncsw.html

time ./run.sh
来源：http://dali.pycfn.com/Article/details/gtjjajrpnd.html

================================================================================
来源：http://dali.zhixingplan.top/Article/details/gtqxxbpsok.html

S. C / C++ 专题
来源：http://dali.mhx1999.top/Article/details/gttzzmzcho.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtablrxfoc.html

[S01] C：Hello World
来源：http://dali.jqgfzy.top/Article/details/gtxpxcnnyw.html

#include <stdio.h>
来源：http://dali.kuanghao11.cn/Article/details/gtsbcprdky.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.tianlin.xyz/Article/details/gtwhpzescm.html

[S02] C：变量与格式化输出
来源：http://dali.tanke756.top/Article/details/gtqxzaryum.html

int a = 10; printf("%d\n", a);
来源：http://dali.hysaishi.cn/Article/details/gtnkfqokpy.html

[S03] C：读入整数
来源：http://dali.guannengcc.top/Article/details/gtvdkuoluc.html

int x; scanf("%d", &x);
来源：http://dali.zhaomingkeji.xyz/Article/details/gttdlcmzxm.html

[S04] C：字符串复制
来源：http://dali.fengsongda.top/Article/details/gtdcnfldjh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.nanxinkj.top/Article/details/gtlatimyqu.html

[S05] C：字符串长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdbeazeku.html

strlen(s)
来源：http://dali.daria6918.cn/Article/details/gtahupcugq.html

[S06] C：字符串比较
来源：http://dali.cucudq.cn/Article/details/gtrhhynfsw.html

strcmp(a, b) == 0
来源：http://dali.kuanghao11.cn/Article/details/gtlvfsoeqj.html

[S07] C：数组遍历求和
来源：http://dali.xinyue.icu/Article/details/gtlncgjfep.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xinyue.icu/Article/details/gtxjnvjkqf.html

[S08] C：动态内存分配与释放
来源：http://dali.gzhubu.top/Article/details/gtyyrjsykh.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.havefunace.top/Article/details/gtcufpvtmj.html

[S09] C：结构体定义与初始化
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmyjhvraj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.cqqwz.cn/Article/details/gtkdmeeqpy.html

[S10] C：指针与解引用
来源：http://dali.pengpengdd.cyou/Article/details/gtwtcjgagp.html

int *p = &a;  *p = 5;
来源：http://dali.cashguo.top/Article/details/gtfrotcmqo.html

[S11] C：逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gtzcjivetk.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.snrcjt.cn/Article/details/gtalandcez.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sysykeji.top/Article/details/gtkcywnxfc.html

fclose(f);
来源：http://dali.redwolf501.top/Article/details/gtiferzfbo.html

[S12] C：写文件
来源：http://dali.fzhhl.top/Article/details/gtmzyhyxwo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xuetiantiany.cn/Article/details/gtkaciucha.html

[S13] C：宏定义
来源：http://dali.jinqigfzy.top/Article/details/gtgtktgoou.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.yuxming.cn/Article/details/gtabxpjhki.html

[S14] C：枚举
来源：http://dali.pengpengdd.cyou/Article/details/gtyeuluaas.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.bjfxy.top/Article/details/gtntccnhvu.html

[S15] C：类型转换
来源：http://dali.zhengqikj.top/Article/details/gtkhoizfjz.html

(double) a / b
来源：http://dali.xinyue.icu/Article/details/gtihmpjoan.html

[S16] C：位操作置位
来源：http://dali.hysaishi.cn/Article/details/gtcdesddnl.html

x |= (1 << 3);
来源：http://dali.316326.xyz/Article/details/gtizaywidt.html

[S17] C：安全拼接字符串
来源：http://dali.ybcxt.top/Article/details/gtwhyvzzmu.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.nanxinkj.top/Article/details/gtvjbrypxz.html

[S18] C：命令行参数
来源：http://dali.daria6918.cn/Article/details/gtnbefjzig.html

int main(int argc, char **argv)
来源：http://dali.cheryme.top/Article/details/gtsjgccoon.html

[S19] C：快速排序
来源：http://dali.yangfankeji.com/Article/details/gtbvawfjfv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.redwolf501.top/Article/details/gtydiayliw.html

[S20] C：二分查找
来源：http://dali.havefunace.top/Article/details/gtbxsaptrh.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.guannengcc.top/Article/details/gtqklzwpvy.html

[S21] C：字符类别判断
来源：http://dali.redwolf501.top/Article/details/gtynnwjnlm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.jinqigfzy.top/Article/details/gttgnacrwi.html

[S22] C：字符串转数字
来源：http://dali.aizwys.cn/Article/details/gtkfnbdmzy.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.hysaishi.cn/Article/details/gthcexnshm.html

[S23] C：随机数
来源：http://dali.sufxvd.cn/Article/details/gtbeqqgpue.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.smart0.xyz/Article/details/gtumjabwus.html

[S24] C：获取本地时间
来源：http://dali.pengpengdd.cyou/Article/details/gtloqecklu.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.feifeiyinyue.top/Article/details/gtfjtwdudx.html

[S25] C：内存拷贝
来源：http://dali.0kj1m.cn/Article/details/gtpdtrwtmf.html

memcpy(dst, src, n);
来源：http://dali.yonumen.top/Article/details/gtcrxsgogl.html

[S26] C：内存清零
来源：http://dali.dianchejie.cn/Article/details/gtzukyioco.html

memset(a, 0, sizeof a);
来源：http://dali.meibo888.top/Article/details/gtupusiddz.html

[S27] C：定义常量
来源：http://dali.jinqigfzy.top/Article/details/gtdlirhtxl.html

const double PI = 3.14159;
来源：http://dali.zdqjudy.top/Article/details/gtxfxefdpw.html

[S28] C：静态变量
来源：http://dali.aizwys.cn/Article/details/gtluidatfz.html

static int counter = 0;
来源：http://dali.jinghuilouyu.cn/Article/details/gtalcokite.html

[S29] C：变参函数
来源：http://dali.yj202588.top/Article/details/gthxpefrtm.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhoulong.xyz/Article/details/gtfvuovqrd.html

[S30] C：头文件保护
来源：http://dali.ivvv.top/Article/details/gtrmaepqmv.html

#ifndef X_H
来源：http://dali.meibo888.top/Article/details/gtfkggrouc.html

#define X_H
来源：http://dali.c1oappe.top/Article/details/gtvbaevhit.html

#endif
来源：http://dali.smart0.xyz/Article/details/gtzdpvxfcy.html

[S31] C++：Hello World
来源：http://dali.bjfxy.top/Article/details/gtfirshqdi.html

#include <iostream>
来源：http://dali.zycfv.cn/Article/details/gtcyygowmh.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.daria6918.cn/Article/details/gtyiusrqmc.html

[S32] C++：字符串
来源：http://dali.jinghuilouyu.cn/Article/details/gtqtptsqik.html

std::string s = "hi";  s += "!";
来源：http://dali.dianchejie.cn/Article/details/gtisbrafjw.html

[S33] C++：vector 增删
来源：http://dali.haohaochexian.top/Article/details/gttwtycqgi.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.chenzaomai.com/Article/details/gtuidjtlvu.html

[S34] C++：遍历 vector
来源：http://dali.sufxvd.cn/Article/details/gtswaqprhm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhoulong.xyz/Article/details/gtpmsbnuro.html

[S35] C++：map
来源：http://dali.cqqwz.cn/Article/details/gtkdbrdori.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.yangfankeji.com/Article/details/gtxcdxxluh.html

[S36] C++：unordered_map
来源：http://dali.sxryk.cn/Article/details/gtsteyjxjx.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jqgfzy.top/Article/details/gtxecemwyu.html

[S37] C++：set
来源：http://dali.redwolf501.top/Article/details/gtnaaigtsj.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.cqqwz.cn/Article/details/gtithoqerm.html

[S38] C++：排序
来源：http://dali.nwbrower.top/Article/details/gtdcdeeruy.html

std::sort(v.begin(), v.end());
来源：http://dali.tanke756.top/Article/details/gtsjdafbey.html

[S39] C++：自定义比较器排序
来源：http://dali.nwbrower.top/Article/details/gtezptpojz.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xylfe.cn/Article/details/gtcxiyqmcj.html

[S40] C++：查找元素
来源：http://dali.jqgfzy.top/Article/details/gtasszxctv.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.smart0.xyz/Article/details/gtxkwlzrqj.html

[S41] C++：类与构造函数
来源：http://dali.mhx1999.top/Article/details/gtbtrftfcf.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.9152youxi.cn/Article/details/gtxvbsfkot.html

[S42] C++：继承与虚函数
来源：http://dali.zycfv.cn/Article/details/gtjfkxcoff.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhongyouzk.top/Article/details/gtqwgskvuh.html

[S43] C++：智能指针
来源：http://dali.sufxvd.cn/Article/details/gtmrilepbx.html

auto p = std::make_unique<int>(5);
来源：http://dali.hysaishi.cn/Article/details/gtohyxwjvv.html

[S44] C++：引用传参
来源：http://dali.chenlongwang.top/Article/details/gtkzfaabbd.html

void inc(int &x) { ++x; }
来源：http://dali.xuanzx.com/Article/details/gtgkvglnbd.html

[S45] C++：lambda
来源：http://dali.xuanzx.com/Article/details/gtkpyifjvv.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.vqdsnc.cn/Article/details/gtqzzfdbyn.html

[S46] C++：函数模板
来源：http://dali.hammf.cn/Article/details/gtyvonovxe.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.mhx1999.top/Article/details/gtjoffdcde.html

[S47] C++：结构化绑定遍历
来源：http://dali.ppjwa.cn/Article/details/gtftzvodoq.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtctnbotau.html

[S48] C++：逐行读文件
来源：http://dali.xziqi.cn/Article/details/gtfurnwghf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.haohaochexian.top/Article/details/gtxcohcuqb.html

while (std::getline(in, line)) { }
来源：http://dali.gzhubu.top/Article/details/gtnbigdyfe.html

[S49] C++：写文件
来源：http://dali.ybcxt.top/Article/details/gtqkvcchiz.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.vqdsnc.cn/Article/details/gtacyjovti.html

[S50] C++：格式化数字
来源：http://dali.yj20258.top/Article/details/gtbjlgpidz.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jiagoushi.top/Article/details/gtyupuwctt.html

[S51] C++：显式类型转换
来源：http://dali.guannengcc.top/Article/details/gtaobiouvc.html

static_cast<double>(a) / b
来源：http://dali.kuanghao11.cn/Article/details/gtujoihfkf.html

[S52] C++：const 与 noexcept
来源：http://dali.yonumen.top/Article/details/gtsxwkfgpk.html

int size() const noexcept { return n_; }
来源：http://dali.fzhhl.top/Article/details/gtngjtvkcu.html

[S53] C++：移动语义
来源：http://dali.bjfxy.top/Article/details/gtdoswobrl.html

std::vector<int> w = std::move(v);
来源：http://dali.jqgfzy.top/Article/details/gtkcbfublh.html

[S54] C++：异常处理
来源：http://dali.jqgfzy.top/Article/details/gtiypakwnx.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.tianlin.xyz/Article/details/gtgwrjbrdg.html

[S55] C++：结构化绑定
来源：http://dali.redwolf501.top/Article/details/gthjvopwaf.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.zhiwuduotai.top/Article/details/gtnlpchben.html

[S56] C++：optional
来源：http://dali.zhaomingkeji.xyz/Article/details/gtztzrkkjx.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.guannengcc.top/Article/details/gtiqofmgrd.html

[S57] C++：编译期常量
来源：http://dali.xinyue.icu/Article/details/gthmiqfdxc.html

constexpr int N = 10;
来源：http://dali.ybcxt.top/Article/details/gtuggestbq.html

[S58] C++：命名空间
来源：http://dali.316326.xyz/Article/details/gtcvnarvoi.html

namespace ns { int f() { return 1; } }
来源：http://dali.zhongyouzk.top/Article/details/gtyznzwoya.html

[S59] C++：静态断言
来源：http://dali.shuidangran.top/Article/details/gtwqjurdpb.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.cqqwz.cn/Article/details/gtrveuenvo.html

[S60] C++：遍历并删除元素
来源：http://dali.hnqzz.top/Article/details/gtiiwtstdt.html


<!-- 参考信息 -->