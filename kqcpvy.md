代发 wailian999

R. Bash 专题
来源：http://dali.sufxvd.cn/Article/details/gtqvfbqrst.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gtlqwtwhzi.html

[R01] shebang 与严格模式
来源：http://dali.aibaodan.cn/Article/details/gtzvmtgtqp.html

#!/usr/bin/env bash
来源：http://dali.fzhhl.top/Article/details/gtglcrucch.html

set -euo pipefail
来源：http://dali.shangyingyoupin.top/Article/details/gtrttfuehm.html

[R02] 变量赋值与使用
来源：http://dali.cqqwz.cn/Article/details/gtuoqwacxp.html

name="Tom"; echo "$name"
来源：http://dali.wangdashe.top/Article/details/gtsiwtrzmh.html

[R03] 只读变量
来源：http://dali.guannengcc.top/Article/details/gtgqeowyrd.html

readonly PI=3.14
来源：http://dali.gzhubu.top/Article/details/gtbqqbfvew.html

[R04] 位置参数
来源：http://dali.xuanzx.com/Article/details/gtletublza.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.mhx1999.top/Article/details/gtpjcphvnr.html

[R05] 参数默认值
来源：http://dali.gaohongyu789.top/Article/details/gttrriauwt.html

name="${1:-default}"
来源：http://dali.zdqjudy.top/Article/details/gtjelpyhwu.html

[R06] 判断命令是否存在
来源：http://dali.xuanzx.com/Article/details/gtchxivbqo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjhzebvbk.html

[R07] if 判断文件
来源：http://dali.gogol.net.cn/Article/details/gtfssamjhx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.tian-w.cn/Article/details/gtwaghebhu.html

[R08] 数值比较
来源：http://dali.cqqwz.cn/Article/details/gtiferguit.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.vqdsnc.cn/Article/details/gturynnufh.html

[R09] 字符串比较
来源：http://dali.svipenyu.cn/Article/details/gtnaqhqqoh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jlsjyb.cn/Article/details/gtwjyyhzip.html

[R10] 正则匹配
来源：http://dali.jqgfzy.top/Article/details/gtzjxvkegr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gtapfvqfxh.html

[R11] case 多分支
来源：http://dali.cheryme.top/Article/details/gtnjslivub.html

case "$1" in
来源：http://dali.wangshuangyany.cn/Article/details/gtazjcabnf.html

start) echo "启动" ;;
来源：http://dali.cashguo.top/Article/details/gtrwapsynp.html

stop)  echo "停止" ;;
来源：http://dali.jinqigfzy.top/Article/details/gtnbbbzepz.html

*)     echo "未知命令" ;;
来源：http://dali.zhengqikj.top/Article/details/gtwhcbollo.html

esac
来源：http://dali.hnqzz.top/Article/details/gtjyywojfu.html

[R12] for 遍历文件
来源：http://dali.zhongyouzk.top/Article/details/gtkkvvdbrl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhengqikj.top/Article/details/gthvwgfblt.html

[R13] for 计数循环
来源：http://dali.sufxvd.cn/Article/details/gtxmmjlrih.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hnqzz.top/Article/details/gtvonzfdte.html

[R14] C 风格 for
来源：http://dali.vqdsnc.cn/Article/details/gtdoihnlsp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sxryk.cn/Article/details/gtbdikblnj.html

[R15] while 逐行读文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gttiaytgcn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.sufxvd.cn/Article/details/gtpyasvmsw.html

[R16] until 等待条件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrcbfcsfa.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.redwolf501.top/Article/details/gtddzbgvhv.html

[R17] 数组定义与取值
来源：http://dali.havefunace.top/Article/details/gtubbeerln.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hongshengwenyu.top/Article/details/gtyvvecifj.html

[R18] 遍历数组
来源：http://dali.yuanzhike.top/Article/details/gtdljnszbh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtsyqncrtk.html

[R19] 数组长度
来源：http://dali.daria6918.cn/Article/details/gtwxkfgeua.html

echo "${#arr[@]}"
来源：http://dali.chenzaomai.com/Article/details/gtybpoovie.html

[R20] 关联数组（字典）
来源：http://dali.ivvv.top/Article/details/gtxdkcvqpj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.mhx1999.top/Article/details/gtufwokvhu.html

[R21] 字符串长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtphezyhjf.html

echo "${#s}"
来源：http://dali.xinyue.icu/Article/details/gtwvxqdqdn.html

[R22] 截取子串
来源：http://dali.guowangkeji.top/Article/details/gtpcxmmqll.html

echo "${s:0:5}"
来源：http://dali.yvedp.cn/Article/details/gtqnonpdlc.html

[R23] 字符串替换
来源：http://dali.zhengqikj.top/Article/details/gtqoxuajbi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yongpay.top/Article/details/gtclcsjbpi.html

[R24] 大小写转换
来源：http://dali.yonumen.top/Article/details/gtscswoksx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yj202588.top/Article/details/gtjrvrkfgt.html

[R25] 去后缀 / 去前缀
来源：http://dali.cucudq.cn/Article/details/gtjksoeqnm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.nanxinkj.top/Article/details/gtpdjkqxpw.html

[R26] 命令替换
来源：http://dali.cdnleiting.top/Article/details/gtitqupauw.html

now=$(date +%F); echo "$now"
来源：http://dali.sufxvd.cn/Article/details/gtqcbbrtow.html

[R27] 算术展开
来源：http://dali.mhx1999.top/Article/details/gteplsetjq.html

echo $((1 + 2 * 3))
来源：http://dali.yuanzhike.top/Article/details/gtpfqfaltz.html

[R28] 浮点运算
来源：http://dali.yj20258.top/Article/details/gthrltaqpe.html

echo "scale=2; 10/3" | bc
来源：http://dali.316326.xyz/Article/details/gtfddmegiq.html

[R29] 定义函数
来源：http://dali.c1oappe.top/Article/details/gtpegbkmrp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jianghu66.top/Article/details/gtbpvjtoql.html

[R30] 函数返回状态码
来源：http://dali.dashuyun.cn/Article/details/gtzltdkrzs.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jinqigufen.top/Article/details/gthqnagrog.html

[R31] 局部变量
来源：http://dali.yvedp.cn/Article/details/gtelrorhmk.html

f() { local x=1; echo "$x"; }
来源：http://dali.pycfn.com/Article/details/gtdcdlaake.html

[R32] 参数个数校验
来源：http://dali.shanyushiyangtech.top/Article/details/gtvafizptz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zycfv.cn/Article/details/gtigcajgve.html

[R33] 捕获错误并提示行号
来源：http://dali.quarkkingdee.top/Article/details/gtqqtmvawm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.fzhhl.top/Article/details/gtzridemxf.html

[R34] 退出时清理
来源：http://dali.yanxiufei.cn/Article/details/gtiogjorym.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yonumen.top/Article/details/gtpyxdmrlt.html

[R35] 后台执行并等待
来源：http://dali.fengsongda.top/Article/details/gtimvucxzw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.nanxinkj.top/Article/details/gtyobjdwcf.html

[R36] 并发执行多个任务
来源：http://dali.sxryk.cn/Article/details/gtpllsfrif.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhongyouzk.top/Article/details/gtorlejjgp.html

[R37] 把输出赋给变量
来源：http://dali.hfpthk.cn/Article/details/gtwmsrafkl.html

files=$(ls -1)
来源：http://dali.hammf.cn/Article/details/gtcfcqlyzv.html

[R38] 管道串联
来源：http://dali.guowangkeji.top/Article/details/gteooffjgl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.haohaochexian.top/Article/details/gtdczlzqdc.html

[R39] 重定向标准输出与错误
来源：http://dali.birdmap.top/Article/details/gthwxfxrcp.html

cmd > out.log 2>&1
来源：http://dali.sxryk.cn/Article/details/gtrqtwevuu.html

[R40] 追加写日志
来源：http://dali.aizwys.cn/Article/details/gtxhitspjt.html

echo "log" >> out.log
来源：http://dali.shuidangran.top/Article/details/gtsqquydqn.html

[R41] 丢弃输出
来源：http://dali.nwbrower.top/Article/details/gtpyqagffu.html

cmd >/dev/null 2>&1
来源：http://dali.316326.xyz/Article/details/gtdjlikegl.html

[R42] 输入重定向
来源：http://dali.gotoacloud.top/Article/details/gtajoxhtxv.html

wc -l < a.txt
来源：http://dali.bjfxy.top/Article/details/gtcybjvoms.html

[R43] 按名字查找文件
来源：http://dali.pycfn.com/Article/details/gtsvtcnddz.html

find . -name "*.log" -type f
来源：http://dali.haohaochexian.top/Article/details/gtklxnyasj.html

[R44] 按修改时间查找
来源：http://dali.yongpay.top/Article/details/gtvidanboa.html

find . -mtime -7 -type f
来源：http://dali.c1oappe.top/Article/details/gtuczrsuna.html

[R45] 批量删除
来源：http://dali.pycfn.com/Article/details/gtwqkcqotv.html

find . -name "*.tmp" -delete
来源：http://dali.shanyushiyangtech.top/Article/details/gtpuybcgcd.html

[R46] 递归替换文件内容
来源：http://dali.fzhhl.top/Article/details/gtsdmarxea.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinqigufen.top/Article/details/gtgeygwaor.html

[R47] sed 单行替换
来源：http://dali.cheryme.top/Article/details/gtapgztrvo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yj202588.top/Article/details/gtxmlafmdg.html

[R48] awk 取指定列
来源：http://dali.guannengcc.top/Article/details/gtwexpyzxo.html

awk '{print $1, $3}' a.txt
来源：http://dali.cqqwz.cn/Article/details/gtynlrlisy.html

[R49] awk 带条件
来源：http://dali.xinyue.icu/Article/details/gtsqvjkoad.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.havefunace.top/Article/details/gtsfaxzsju.html

[R50] awk 求和
来源：http://dali.daxiang520.top/Article/details/gtzitxagjq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ydzc1.top/Article/details/gtydluwekb.html

[R51] 排序去重取前几
来源：http://dali.aizwys.cn/Article/details/gtaajfrreu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.kuanghao11.cn/Article/details/gtkuyhntjr.html

[R52] 统计行数
来源：http://dali.havefunace.top/Article/details/gthauujjws.html

wc -l a.txt
来源：http://dali.ivvv.top/Article/details/gtycktfydk.html

[R53] 查看文件头与实时尾
来源：http://dali.gaohongyu789.top/Article/details/gtoceixpzm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.andypj.xyz/Article/details/gtvhchuhuf.html

[R54] 比较两个文件
来源：http://dali.cqqwz.cn/Article/details/gtujoiskuh.html

diff a.txt b.txt
来源：http://dali.jinqigufen.top/Article/details/gtbiuhjvhv.html

[R55] 压缩与解压
来源：http://dali.jinqigfzy.top/Article/details/gtbrprcrxp.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.chenlongwang.top/Article/details/gtmktqgjoq.html

[R56] 远程拷贝
来源：http://dali.yvedp.cn/Article/details/gtwqztwnws.html

scp file user@host:/path/
来源：http://dali.gogol.net.cn/Article/details/gtwewdwsbj.html

[R57] 远程执行命令
来源：http://dali.yanxiufei.cn/Article/details/gthudqmzza.html

ssh user@host 'uptime'
来源：http://dali.xuetiantiany.cn/Article/details/gtyhwylyan.html

[R58] 下载文件
来源：http://dali.cashguo.top/Article/details/gtesojsctf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xinyue.icu/Article/details/gtfmoeiocp.html

[R59] 发 POST JSON
来源：http://dali.jianghu66.top/Article/details/gtzgxnehpb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.dashuyun.cn/Article/details/gtapwvsyvz.html

[R60] 只看 HTTP 状态码
来源：http://dali.yj20258.top/Article/details/gthevgqvml.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.dashuyun.cn/Article/details/gtvreummwa.html

[R61] 磁盘占用
来源：http://dali.iojbl.cn/Article/details/gtcmpbcenc.html

df -h;  du -sh *
来源：http://dali.fengsongda.top/Article/details/gtzbukohif.html

[R62] 找最占空间的文件
来源：http://dali.jinqigfzy.top/Article/details/gtexzfamzd.html

du -ah . | sort -rh | head -10
来源：http://dali.bjfxy.top/Article/details/gtmfpihmal.html

[R63] 内存与进程
来源：http://dali.cqqwz.cn/Article/details/gtkrptaert.html

free -h;  ps aux | grep nginx
来源：http://dali.tianlin.xyz/Article/details/gtcbgyohxh.html

[R64] 结束进程
来源：http://dali.daria6918.cn/Article/details/gtscrzzqtj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cucudq.cn/Article/details/gtwinonmog.html

[R65] 查看端口占用
来源：http://dali.yueranfly.top/Article/details/gtmdltedot.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.smart0.xyz/Article/details/gtoqyzibfw.html

[R66] 定时任务
来源：http://dali.daxiang520.top/Article/details/gteuwvxyye.html

crontab -e;  crontab -l
来源：http://dali.pengpengdd.cyou/Article/details/gtxlpnodju.html

[R67] 生成随机十六进制串
来源：http://dali.aizwys.cn/Article/details/gtyevdpsat.html

openssl rand -hex 16
来源：http://dali.jiagoushi.top/Article/details/gtxweiekya.html

[R68] 计算文件校验值
来源：http://dali.316326.xyz/Article/details/gtszdnlprt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtlqbnupgj.html

[R69] 生成随机密码
来源：http://dali.hfpthk.cn/Article/details/gtqqbcvbpz.html

head -c 16 /dev/urandom | base64
来源：http://dali.pycfn.com/Article/details/gtoynilxmq.html

[R70] 时间戳与互转
来源：http://dali.hnqzz.top/Article/details/gttvwmsrwi.html

date +%s;  date -d @1700000000
来源：http://dali.cqqwz.cn/Article/details/gtnqtimcqr.html

[R71] 日期格式化
来源：http://dali.wangshuangyany.cn/Article/details/gtypuifwdx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ydzc1.top/Article/details/gtbdgdifgj.html

[R72] 等待端口就绪
来源：http://dali.meibo888.top/Article/details/gtwdqcyhfa.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shzxlz.cn/Article/details/gthdcgiixj.html

[R73] 分割大日志
来源：http://dali.shangyingyoupin.top/Article/details/gtjouimenu.html

split -l 1000 big.log part_
来源：http://dali.shzxlz.cn/Article/details/gteiyvzqfk.html

[R74] 批量重命名
来源：http://dali.zycfv.cn/Article/details/gtyqyvadkf.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yonumen.top/Article/details/gtkkpztnvz.html

[R75] 导出环境变量
来源：http://dali.yuxming.cn/Article/details/gtfstwmbwo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.0kj1m.cn/Article/details/gtckpycwov.html

[R76] 使用临时文件
来源：http://dali.yj20258.top/Article/details/gtiacmdssp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gogol.net.cn/Article/details/gtxfzcjven.html

[R77] 读取用户输入
来源：http://dali.shangyingyoupin.top/Article/details/gtcapkaint.html

read -rp "请输入: " ans
来源：http://dali.wangshuangyany.cn/Article/details/gtazdyypuy.html

[R78] 交互式菜单
来源：http://dali.bjfxy.top/Article/details/gtzgeephje.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.gotoacloud.top/Article/details/gtaytbmdxa.html

[R79] 解析命令行选项
来源：http://dali.wangshuangyany.cn/Article/details/gtyymxlksn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.gotoacloud.top/Article/details/gtlteyvplw.html

[R80] 查看脚本执行耗时
来源：http://dali.zycfv.cn/Article/details/gtzcpnbfeq.html

time ./run.sh
来源：http://dali.chenjidiqi.icu/Article/details/gtcjgagwfy.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtnwlwlqoj.html

S. C / C++ 专题
来源：http://dali.jqgufenzy.top/Article/details/gtzkxcczjg.html

================================================================================
来源：http://dali.guannengcc.top/Article/details/gtiwthtvyw.html

[S01] C：Hello World
来源：http://dali.shuidangran.top/Article/details/gtiukqjftf.html

#include <stdio.h>
来源：http://dali.zhixingplan.top/Article/details/gtakajwguw.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvuhoszqo.html

[S02] C：变量与格式化输出
来源：http://dali.jianghu66.top/Article/details/gtujmgcfru.html

int a = 10; printf("%d\n", a);
来源：http://dali.shzxlz.cn/Article/details/gtuipelwye.html

[S03] C：读入整数
来源：http://dali.bjfxy.top/Article/details/gtwpgubkgt.html

int x; scanf("%d", &x);
来源：http://dali.yj202588.top/Article/details/gtckcvzuyb.html

[S04] C：字符串复制
来源：http://dali.guowangkeji.top/Article/details/gtftqtfloh.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.aibaodan.cn/Article/details/gtpcdgnoyg.html

[S05] C：字符串长度
来源：http://dali.pycfn.com/Article/details/gtwceqgmby.html

strlen(s)
来源：http://dali.jqgufenzy.top/Article/details/gtlrsscvrx.html

[S06] C：字符串比较
来源：http://dali.sweek.top/Article/details/gtfhqcehte.html

strcmp(a, b) == 0
来源：http://dali.birdmap.top/Article/details/gtnrzvyfoh.html

[S07] C：数组遍历求和
来源：http://dali.jinghuilouyu.cn/Article/details/gtwjcydnot.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.andypj.xyz/Article/details/gtecmawgvg.html

[S08] C：动态内存分配与释放
来源：http://dali.sweek.top/Article/details/gtpynwgsel.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.gogol.net.cn/Article/details/gtvsmhezdk.html

[S09] C：结构体定义与初始化
来源：http://dali.yonumen.top/Article/details/gtvhrvbcqe.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmltyjgcb.html

[S10] C：指针与解引用
来源：http://dali.yongpay.top/Article/details/gtaocsdmyi.html

int *p = &a;  *p = 5;
来源：http://dali.feifeiyinyue.top/Article/details/gtmndhrmiw.html

[S11] C：逐行读文件
来源：http://dali.daria6918.cn/Article/details/gtmjdkullo.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jlsjyb.cn/Article/details/gtzwhibzgl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.kuanghao11.cn/Article/details/gtxngawiui.html

fclose(f);
来源：http://dali.zhaomingkeji.xyz/Article/details/gthurnkzgl.html

[S12] C：写文件
来源：http://dali.cashguo.top/Article/details/gtbkhvdgis.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.sysykeji.top/Article/details/gtfbfhyktk.html

[S13] C：宏定义
来源：http://dali.cdnleiting.top/Article/details/gtkphbxhki.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.wangshuangyany.cn/Article/details/gtwxmtzpyn.html

[S14] C：枚举
来源：http://dali.aibaodan.cn/Article/details/gtbrwkvexa.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sysykeji.top/Article/details/gtzbfeipwv.html

[S15] C：类型转换
来源：http://dali.nanxinkj.top/Article/details/gtcpjixjvu.html

(double) a / b
来源：http://dali.kuanghao11.cn/Article/details/gtxdiqvbeb.html

[S16] C：位操作置位
来源：http://dali.ppjwa.cn/Article/details/gtpvgmhkpw.html

x |= (1 << 3);
来源：http://dali.guowangkeji.top/Article/details/gtdxkcogbj.html

[S17] C：安全拼接字符串
来源：http://dali.9152youxi.cn/Article/details/gtmupvfehc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.jqgufenzy.top/Article/details/gtkngiikpn.html

[S18] C：命令行参数
来源：http://dali.dashuyun.cn/Article/details/gtzrqngacm.html

int main(int argc, char **argv)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvepzaaoj.html

[S19] C：快速排序
来源：http://dali.pycfn.com/Article/details/gtcairtjjz.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.tian-w.cn/Article/details/gtjhanelpa.html

[S20] C：二分查找
来源：http://dali.cashguo.top/Article/details/gthuhrxjvc.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.sysykeji.top/Article/details/gtqfrusxzy.html

[S21] C：字符类别判断
来源：http://dali.zdqjudy.top/Article/details/gtkvvkbzas.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.chenzaomai.com/Article/details/gtatygzdyq.html

[S22] C：字符串转数字
来源：http://dali.mhx1999.top/Article/details/gtduihrahn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.andypj.xyz/Article/details/gtlerhtihz.html

[S23] C：随机数
来源：http://dali.xuetiantiany.cn/Article/details/gtnvywjfic.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.shuidangran.top/Article/details/gtlmlvqgbs.html

[S24] C：获取本地时间
来源：http://dali.hnqzz.top/Article/details/gtydhspmvb.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhoulong.xyz/Article/details/gtovkshsou.html

[S25] C：内存拷贝
来源：http://dali.yanxiufei.cn/Article/details/gtlzhnuadu.html

memcpy(dst, src, n);
来源：http://dali.shangyingyoupin.top/Article/details/gtrwhejsxq.html

[S26] C：内存清零
来源：http://dali.ivvv.top/Article/details/gtnnneakbc.html

memset(a, 0, sizeof a);
来源：http://dali.jinqigufen.top/Article/details/gthuzknqco.html

[S27] C：定义常量
来源：http://dali.pengpengdd.cyou/Article/details/gtgnrsivfe.html

const double PI = 3.14159;
来源：http://dali.nanxuanxn.top/Article/details/gtqcwytdbr.html

[S28] C：静态变量
来源：http://dali.havefunace.top/Article/details/gtbbpcuiqp.html

static int counter = 0;
来源：http://dali.sweek.top/Article/details/gthfnbfwdt.html

[S29] C：变参函数
来源：http://dali.aizwys.cn/Article/details/gtikbilzdb.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.chenzaomai.com/Article/details/gtmotxheap.html

[S30] C：头文件保护
来源：http://dali.wangdashe.top/Article/details/gtjlrinazh.html

#ifndef X_H
来源：http://dali.sufxvd.cn/Article/details/gtheompomn.html

#define X_H
来源：http://dali.ydzc1.top/Article/details/gtmztkfnfy.html

#endif
来源：http://dali.pengpengdd.cyou/Article/details/gtbkrialnq.html

[S31] C++：Hello World
来源：http://dali.nanxuanxn.top/Article/details/gtbwxmjqpc.html

#include <iostream>
来源：http://dali.dashuyun.cn/Article/details/gtgevhjfcz.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.hnqzz.top/Article/details/gtteqjpstk.html

[S32] C++：字符串
来源：http://dali.yongpay.top/Article/details/gtcihiwojc.html

std::string s = "hi";  s += "!";
来源：http://dali.hnqzz.top/Article/details/gteocrcquq.html

[S33] C++：vector 增删
来源：http://dali.gogol.net.cn/Article/details/gtezlhnuob.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhixingplan.top/Article/details/gtzrivvkpf.html

[S34] C++：遍历 vector
来源：http://dali.shuidangran.top/Article/details/gtkeeuwvcm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cqqwz.cn/Article/details/gtrskiphcd.html

[S35] C++：map
来源：http://dali.cqqwz.cn/Article/details/gtkqrecpee.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtsitvssel.html

[S36] C++：unordered_map
来源：http://dali.sweek.top/Article/details/gtcbrwtxjb.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gtofjqqgcs.html

[S37] C++：set
来源：http://dali.jiagoushi.top/Article/details/gtivaobktu.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hnqzz.top/Article/details/gtxvnghbgi.html

[S38] C++：排序
来源：http://dali.sysykeji.top/Article/details/gtqrwrrjxl.html

std::sort(v.begin(), v.end());
来源：http://dali.hammf.cn/Article/details/gttpqxdecy.html

[S39] C++：自定义比较器排序
来源：http://dali.meibo888.top/Article/details/gtqibdyqeg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.guannengcc.top/Article/details/gtbnxqqyuf.html

[S40] C++：查找元素
来源：http://dali.ydzc1.top/Article/details/gtvfjuslos.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.yueranfly.top/Article/details/gtwgijihjt.html

[S41] C++：类与构造函数
来源：http://dali.tianlin.xyz/Article/details/gtfanperbg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.gzhubu.top/Article/details/gterzwmxqj.html

[S42] C++：继承与虚函数
来源：http://dali.ydzc1.top/Article/details/gtaupinwmn.html

class B : public Base { public: void f() override {} };
来源：http://dali.xylfe.cn/Article/details/gtprbprxdr.html

[S43] C++：智能指针
来源：http://dali.shanyushiyangtech.top/Article/details/gtpbjfcbxo.html

auto p = std::make_unique<int>(5);
来源：http://dali.yuxming.cn/Article/details/gtipxxhoht.html

[S44] C++：引用传参
来源：http://dali.fengsongda.top/Article/details/gtutrhwaat.html

void inc(int &x) { ++x; }
来源：http://dali.gotoacloud.top/Article/details/gtawkuyynk.html

[S45] C++：lambda
来源：http://dali.sweek.top/Article/details/gtaijwfsil.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.dianchejie.cn/Article/details/gthaiyuuud.html

[S46] C++：函数模板
来源：http://dali.yongpay.top/Article/details/gthxawgqbd.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinqigufen.top/Article/details/gtmwqcogoh.html

[S47] C++：结构化绑定遍历
来源：http://dali.yanxiufei.cn/Article/details/gtnriaciab.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.redwolf501.top/Article/details/gtcbfwrree.html

[S48] C++：逐行读文件
来源：http://dali.xuetiantiany.cn/Article/details/gtzwkpcftz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.andypj.xyz/Article/details/gtbsbbvhhh.html

while (std::getline(in, line)) { }
来源：http://dali.c1oappe.top/Article/details/gtoosrldzh.html

[S49] C++：写文件
来源：http://dali.iojbl.cn/Article/details/gtztlsagzm.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.smart0.xyz/Article/details/gteyynnsri.html

[S50] C++：格式化数字
来源：http://dali.yj20258.top/Article/details/gtjymplgcv.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.zycfv.cn/Article/details/gtttqfkuij.html

[S51] C++：显式类型转换
来源：http://dali.cucudq.cn/Article/details/gtsebjaent.html

static_cast<double>(a) / b
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbzzavcip.html

[S52] C++：const 与 noexcept
来源：http://dali.xuetiantiany.cn/Article/details/gtmeyyqmxd.html

int size() const noexcept { return n_; }
来源：http://dali.yuxming.cn/Article/details/gtuigqnqkf.html

[S53] C++：移动语义
来源：http://dali.xziqi.cn/Article/details/gtorrhsgjq.html

std::vector<int> w = std::move(v);
来源：http://dali.andypj.xyz/Article/details/gtywgltdfg.html

[S54] C++：异常处理
来源：http://dali.smart0.xyz/Article/details/gtoohzssjj.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.xziqi.cn/Article/details/gtqnymdtzr.html

[S55] C++：结构化绑定
来源：http://dali.yongpay.top/Article/details/gtcfqqcirq.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.shanyushiyangtech.top/Article/details/gtivzzsakv.html

[S56] C++：optional
来源：http://dali.0kj1m.cn/Article/details/gtwogqmjrg.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.hnxiangtu.top/Article/details/gtbsnojuqx.html

[S57] C++：编译期常量
来源：http://dali.ydzc1.top/Article/details/gtwdpmcagg.html

constexpr int N = 10;
来源：http://dali.fzhhl.top/Article/details/gtafqzybwy.html

[S58] C++：命名空间
来源：http://dali.jqgufenzy.top/Article/details/gtjezipypz.html

namespace ns { int f() { return 1; } }
来源：http://dali.ydzc1.top/Article/details/gtkkrreaqv.html

[S59] C++：静态断言
来源：http://dali.nwbrower.top/Article/details/gtwlkvgtkr.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.dashuyun.cn/Article/details/gtdnnuobvl.html

[S60] C++：遍历并删除元素
来源：http://dali.chenjidiqi.icu/Article/details/gtmifujhxu.html

v.erase(std::remove_if(v.begin(), v.end(), [](int x) { return x < 0; }), v.end());
来源：http://dali.cqqwz.cn/Article/details/gtxfskqxlg.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gttgxhfrpd.html

T. 其他语言补充（Kotlin / Swift / Lua / Perl / Scala）
来源：http://dali.nanxinkj.top/Article/details/gtsnfgygzu.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtpukrlufu.html


<!-- 参考信息 -->