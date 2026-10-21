代发 wailian999

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shangyingyoupin.top/Article/details/gtmkhhfglq.html

[Q90] 生成序号列
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjklbsjrl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tian-w.cn/Article/details/gtnowadhzt.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtwahsrtwb.html

R. Bash 专题
来源：http://dali.xuetiantiany.cn/Article/details/gtjngqanrv.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtymeulhxj.html

[R01] shebang 与严格模式
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtncihczpb.html

#!/usr/bin/env bash
来源：http://dali.sxryk.cn/Article/details/gtbvecgtgr.html

set -euo pipefail
来源：http://dali.zhixingplan.top/Article/details/gtvbuukzht.html

[R02] 变量赋值与使用
来源：http://dali.xinyue.icu/Article/details/gtrmfgdfpp.html

name="Tom"; echo "$name"
来源：http://dali.redwolf501.top/Article/details/gtebmhmmzy.html

[R03] 只读变量
来源：http://dali.hnqzz.top/Article/details/gtjkagaxoy.html

readonly PI=3.14
来源：http://dali.shuidangran.top/Article/details/gtmikltldg.html

[R04] 位置参数
来源：http://dali.gotoacloud.top/Article/details/gtvgsmbjwe.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.andypj.xyz/Article/details/gtgjjltamc.html

[R05] 参数默认值
来源：http://dali.cashguo.top/Article/details/gtxwwoowco.html

name="${1:-default}"
来源：http://dali.andypj.xyz/Article/details/gtxockfyyx.html

[R06] 判断命令是否存在
来源：http://dali.gaohongyu789.top/Article/details/gtzlodulej.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhoulong.xyz/Article/details/gtwsugmwbu.html

[R07] if 判断文件
来源：http://dali.yvedp.cn/Article/details/gtxhzowvmu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.mhx1999.top/Article/details/gtngulkdyb.html

[R08] 数值比较
来源：http://dali.daxiang520.top/Article/details/gtzuapfncm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yanxiufei.cn/Article/details/gtltldeozj.html

[R09] 字符串比较
来源：http://dali.redwolf501.top/Article/details/gtoqtbbjny.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zdqjudy.top/Article/details/gtmssdazfl.html

[R10] 正则匹配
来源：http://dali.hywenlv.cn/Article/details/gtelrbypdu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.daxiang520.top/Article/details/gtxbclmavp.html

[R11] case 多分支
来源：http://dali.shanyushiyangkeji.top/Article/details/gtucffetul.html

case "$1" in
来源：http://dali.gotoacloud.top/Article/details/gtqxbzmiot.html

start) echo "启动" ;;
来源：http://dali.redwolf501.top/Article/details/gtmnhhvjeu.html

stop)  echo "停止" ;;
来源：http://dali.pengpengdd.cyou/Article/details/gtvgexbmme.html

*)     echo "未知命令" ;;
来源：http://dali.fengsongda.top/Article/details/gtnsfjhdtg.html

esac
来源：http://dali.cdnleiting.top/Article/details/gtzsvjuvzb.html

[R12] for 遍历文件
来源：http://dali.yuanzhike.top/Article/details/gtqlxwdeax.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhongyouzk.top/Article/details/gtbtcjyiws.html

[R13] for 计数循环
来源：http://dali.yueranfly.top/Article/details/gtbloschip.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.svipenyu.cn/Article/details/gtjcfkrfre.html

[R14] C 风格 for
来源：http://dali.zhiwuduotai.top/Article/details/gtleqrtqhm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yuxming.cn/Article/details/gtrhggmwcg.html

[R15] while 逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gtktactshd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.dashuyun.cn/Article/details/gttrtdcpog.html

[R16] until 等待条件
来源：http://dali.zycfv.cn/Article/details/gtdscewcgp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jlsjyb.cn/Article/details/gtblqrpxdm.html

[R17] 数组定义与取值
来源：http://dali.ivvv.top/Article/details/gtilwzshyr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jlsjyb.cn/Article/details/gtnazayxvn.html

[R18] 遍历数组
来源：http://dali.hnxiangtu.top/Article/details/gtzumsuicn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jyoumei.cn/Article/details/gtkpmpqfix.html

[R19] 数组长度
来源：http://dali.cdnleiting.top/Article/details/gtofarrlbg.html

echo "${#arr[@]}"
来源：http://dali.daria6918.cn/Article/details/gtqxpvmore.html

[R20] 关联数组（字典）
来源：http://dali.xuetiantiany.cn/Article/details/gtvmrwhwhs.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.redwolf501.top/Article/details/gtsaljstuk.html

[R21] 字符串长度
来源：http://dali.zhongyouzk.top/Article/details/gtbrdefuzt.html

echo "${#s}"
来源：http://dali.aizwys.cn/Article/details/gtqxlmfekt.html

[R22] 截取子串
来源：http://dali.jiagoushi.top/Article/details/gterutkjys.html

echo "${s:0:5}"
来源：http://dali.cucudq.cn/Article/details/gtfnaddzdd.html

[R23] 字符串替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmwquqkzv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.pycfn.com/Article/details/gtlkfpddlg.html

[R24] 大小写转换
来源：http://dali.ppjwa.cn/Article/details/gtdvlntlaw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sweek.top/Article/details/gtmkhxwtbn.html

[R25] 去后缀 / 去前缀
来源：http://dali.yongpay.top/Article/details/gtbwmifhns.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xuetiantiany.cn/Article/details/gtbzqzzzsa.html

[R26] 命令替换
来源：http://dali.hfpthk.cn/Article/details/gtikpqefks.html

now=$(date +%F); echo "$now"
来源：http://dali.quarkkingdee.top/Article/details/gtmatijcbn.html

[R27] 算术展开
来源：http://dali.hysaishi.cn/Article/details/gtshnjrrey.html

echo $((1 + 2 * 3))
来源：http://dali.hammf.cn/Article/details/gtzjrazoyi.html

[R28] 浮点运算
来源：http://dali.smart0.xyz/Article/details/gtgsysfrlh.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinqigfzy.top/Article/details/gtaguysqjr.html

[R29] 定义函数
来源：http://dali.guannengcc.top/Article/details/gtysogbdtn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhengqikj.top/Article/details/gtwwcnnlot.html

[R30] 函数返回状态码
来源：http://dali.cdnleiting.top/Article/details/gtbulubxir.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shanyushiyangtech.top/Article/details/gtyfjwysfg.html

[R31] 局部变量
来源：http://dali.daria6918.cn/Article/details/gtmqrrnclr.html

f() { local x=1; echo "$x"; }
来源：http://dali.hnxiangtu.top/Article/details/gtkfdldndl.html

[R32] 参数个数校验
来源：http://dali.xylfe.cn/Article/details/gtszwljqpq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.hnqzz.top/Article/details/gtzkxhwmwv.html

[R33] 捕获错误并提示行号
来源：http://dali.zhoulong.xyz/Article/details/gtfazlwiek.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yonumen.top/Article/details/gtjbkohkpu.html

[R34] 退出时清理
来源：http://dali.chenjidiqi.icu/Article/details/gtucioxgyl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sufxvd.cn/Article/details/gtgztmtscf.html

[R35] 后台执行并等待
来源：http://dali.jinghuilouyu.cn/Article/details/gtunmbounr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hnxiangtu.top/Article/details/gtiqdrekow.html

[R36] 并发执行多个任务
来源：http://dali.guowangkeji.top/Article/details/gtmgzjhsfz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.wangdashe.top/Article/details/gtmangstsz.html

[R37] 把输出赋给变量
来源：http://dali.svipenyu.cn/Article/details/gtlkgfsyke.html

files=$(ls -1)
来源：http://dali.quarkkingdee.top/Article/details/gtgfbwfndq.html

[R38] 管道串联
来源：http://dali.hysaishi.cn/Article/details/gtztujuidv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.daria6918.cn/Article/details/gtwmmjnqks.html

[R39] 重定向标准输出与错误
来源：http://dali.hnqzz.top/Article/details/gtlcmrkevo.html

cmd > out.log 2>&1
来源：http://dali.tianlin.xyz/Article/details/gtvbajymhy.html

[R40] 追加写日志
来源：http://dali.jqgfzy.top/Article/details/gtkawgdlxu.html

echo "log" >> out.log
来源：http://dali.feifeiyinyue.top/Article/details/gtwraldych.html

[R41] 丢弃输出
来源：http://dali.gotoacloud.top/Article/details/gtpkisefql.html

cmd >/dev/null 2>&1
来源：http://dali.wangdashe.top/Article/details/gtdqivqnkp.html

[R42] 输入重定向
来源：http://dali.guowangkeji.top/Article/details/gtjuwivazq.html

wc -l < a.txt
来源：http://dali.zycfv.cn/Article/details/gtbiyqgrwa.html

[R43] 按名字查找文件
来源：http://dali.jinqigfzy.top/Article/details/gtrveivdra.html

find . -name "*.log" -type f
来源：http://dali.mhx1999.top/Article/details/gtgwfxctkg.html

[R44] 按修改时间查找
来源：http://dali.dashuyun.cn/Article/details/gtforwpsfv.html

find . -mtime -7 -type f
来源：http://dali.zhoulong.xyz/Article/details/gtzwxqpwcf.html

[R45] 批量删除
来源：http://dali.andypj.xyz/Article/details/gtxbjxkycu.html

find . -name "*.tmp" -delete
来源：http://dali.shzxlz.cn/Article/details/gtktogtptv.html

[R46] 递归替换文件内容
来源：http://dali.jinyuanbaomall.cn/Article/details/gthmvtfaju.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yangfankeji.com/Article/details/gtbpgyqfef.html

[R47] sed 单行替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlsszzrxq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hnqzz.top/Article/details/gtifnyxtzc.html

[R48] awk 取指定列
来源：http://dali.wangdashe.top/Article/details/gtpxzgupby.html

awk '{print $1, $3}' a.txt
来源：http://dali.tanke756.top/Article/details/gtdxgbjvxm.html

[R49] awk 带条件
来源：http://dali.hammf.cn/Article/details/gtxvazaeoi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.mhx1999.top/Article/details/gtmsqdqyvo.html

[R50] awk 求和
来源：http://dali.gotoacloud.top/Article/details/gtjwkgyigw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtshzebaml.html

[R51] 排序去重取前几
来源：http://dali.sysykeji.top/Article/details/gttxtegona.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gzhubu.top/Article/details/gtelvgbdee.html

[R52] 统计行数
来源：http://dali.jyoumei.cn/Article/details/gtebxgkpzl.html

wc -l a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtiqgwzcbm.html

[R53] 查看文件头与实时尾
来源：http://dali.redwolf501.top/Article/details/gtohcmadwz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zycfv.cn/Article/details/gtmhhfznty.html

[R54] 比较两个文件
来源：http://dali.tianlin.xyz/Article/details/gtswekkomj.html

diff a.txt b.txt
来源：http://dali.cucudq.cn/Article/details/gtkmbfghxb.html

[R55] 压缩与解压
来源：http://dali.svipenyu.cn/Article/details/gtijrgduaq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jlsjyb.cn/Article/details/gtmccgbnge.html

[R56] 远程拷贝
来源：http://dali.yonumen.top/Article/details/gtwsusgbqp.html

scp file user@host:/path/
来源：http://dali.aizwys.cn/Article/details/gtmivgfdao.html

[R57] 远程执行命令
来源：http://dali.chenzaomai.com/Article/details/gtrjfdndwj.html

ssh user@host 'uptime'
来源：http://dali.jlsjyb.cn/Article/details/gteioeqryu.html

[R58] 下载文件
来源：http://dali.hnqzz.top/Article/details/gtjjhqzwvd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hfpthk.cn/Article/details/gtaqhvubwr.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gtoclrpbpg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.aizwys.cn/Article/details/gtpjzbdrxf.html

[R60] 只看 HTTP 状态码
来源：http://dali.andypj.xyz/Article/details/gtatmuhnsu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jyoumei.cn/Article/details/gtnndvohck.html

[R61] 磁盘占用
来源：http://dali.hywenlv.cn/Article/details/gtgogpefqp.html

df -h;  du -sh *
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmtdvqohl.html

[R62] 找最占空间的文件
来源：http://dali.jinqigfzy.top/Article/details/gtdvxtuhqs.html

du -ah . | sort -rh | head -10
来源：http://dali.sweek.top/Article/details/gtobumuoqu.html

[R63] 内存与进程
来源：http://dali.quarkkingdee.top/Article/details/gtmvvsophy.html

free -h;  ps aux | grep nginx
来源：http://dali.meibo888.top/Article/details/gtvubvgrpd.html

[R64] 结束进程
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpttfbjxn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ydzc1.top/Article/details/gtgwtczeyn.html

[R65] 查看端口占用
来源：http://dali.sweek.top/Article/details/gtxncmivht.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.guannengcc.top/Article/details/gtdapltxkq.html

[R66] 定时任务
来源：http://dali.xziqi.cn/Article/details/gtqmhxzjml.html

crontab -e;  crontab -l
来源：http://dali.zycfv.cn/Article/details/gtgffgkdop.html

[R67] 生成随机十六进制串
来源：http://dali.sysykeji.top/Article/details/gtfixncssz.html

openssl rand -hex 16
来源：http://dali.shzxlz.cn/Article/details/gtlugyxejw.html

[R68] 计算文件校验值
来源：http://dali.shzxlz.cn/Article/details/gtgbpkpdca.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yvedp.cn/Article/details/gtgnpaylrf.html

[R69] 生成随机密码
来源：http://dali.shzxlz.cn/Article/details/gtkesnydfm.html

head -c 16 /dev/urandom | base64
来源：http://dali.hywenlv.cn/Article/details/gtkdxtixvi.html

[R70] 时间戳与互转
来源：http://dali.fengsongda.top/Article/details/gtswxismje.html

date +%s;  date -d @1700000000
来源：http://dali.xuetiantiany.cn/Article/details/gtufnqrgrp.html

[R71] 日期格式化
来源：http://dali.yj20258.top/Article/details/gtgspcqpge.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtziajonns.html

[R72] 等待端口就绪
来源：http://dali.hnxiangtu.top/Article/details/gtxdcfcgkm.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cashguo.top/Article/details/gthggwcddq.html

[R73] 分割大日志
来源：http://dali.fengsongda.top/Article/details/gtgfohpnbg.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gtpvhzufnv.html

[R74] 批量重命名
来源：http://dali.meibo888.top/Article/details/gtemlsccda.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.snrcjt.cn/Article/details/gttqvxpmcb.html

[R75] 导出环境变量
来源：http://dali.gzhubu.top/Article/details/gtyociukrl.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.andypj.xyz/Article/details/gtiblcnyxa.html

[R76] 使用临时文件
来源：http://dali.chenjidiqi.icu/Article/details/gtpnjkptfg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenlongwang.top/Article/details/gtutzmrdsa.html

[R77] 读取用户输入
来源：http://dali.jinqigfzy.top/Article/details/gthqcqanqo.html

read -rp "请输入: " ans
来源：http://dali.c1oappe.top/Article/details/gtowlhhhib.html

[R78] 交互式菜单
来源：http://dali.xuanzx.com/Article/details/gtfxvzkrvn.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.xuanzx.com/Article/details/gthtranwwf.html

[R79] 解析命令行选项
来源：http://dali.daria6918.cn/Article/details/gtbaadfbox.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.wangdashe.top/Article/details/gtcutdcevg.html

[R80] 查看脚本执行耗时
来源：http://dali.kuanghao11.cn/Article/details/gtrgoyokcs.html

time ./run.sh
来源：http://dali.zhongyouzk.top/Article/details/gthnsootcb.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtxbcsomco.html

S. C / C++ 专题
来源：http://dali.sysykeji.top/Article/details/gtahftrrbb.html

================================================================================
来源：http://dali.dashuyun.cn/Article/details/gtjvmbfgdz.html

[S01] C：Hello World
来源：http://dali.daxiang520.top/Article/details/gtdnxjxkfj.html

#include <stdio.h>
来源：http://dali.zdqjudy.top/Article/details/gtsdmsokub.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwynvrogn.html

[S02] C：变量与格式化输出
来源：http://dali.jinqigufen.top/Article/details/gtrwczntpe.html

int a = 10; printf("%d\n", a);
来源：http://dali.guannengcc.top/Article/details/gtsvfthexb.html

[S03] C：读入整数
来源：http://dali.guowangkeji.top/Article/details/gtjhvtwskq.html

int x; scanf("%d", &x);
来源：http://dali.tian-w.cn/Article/details/gtpeayuhwh.html

[S04] C：字符串复制
来源：http://dali.chenlongwang.top/Article/details/gtbpwfjdzl.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.mhx1999.top/Article/details/gtukhccsov.html

[S05] C：字符串长度
来源：http://dali.haohaochexian.top/Article/details/gtzfjkzwhr.html

strlen(s)
来源：http://dali.yanxiufei.cn/Article/details/gtgwjvjxvc.html

[S06] C：字符串比较
来源：http://dali.smart0.xyz/Article/details/gtwnuxgars.html

strcmp(a, b) == 0
来源：http://dali.jinghuilouyu.cn/Article/details/gtnugvwxdx.html

[S07] C：数组遍历求和
来源：http://dali.sufxvd.cn/Article/details/gttfjayser.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.chenjidiqi.icu/Article/details/gtrpiljrxj.html

[S08] C：动态内存分配与释放
来源：http://dali.redwolf501.top/Article/details/gtmzpzftlo.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.0kj1m.cn/Article/details/gtnlecxcew.html

[S09] C：结构体定义与初始化
来源：http://dali.hongshengwenyu.top/Article/details/gtywkopijj.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.chenzaomai.com/Article/details/gtocrruaiw.html

[S10] C：指针与解引用
来源：http://dali.kuanghao11.cn/Article/details/gtnnnfhnvw.html

int *p = &a;  *p = 5;
来源：http://dali.nwbrower.top/Article/details/gtvgrhdiap.html

[S11] C：逐行读文件
来源：http://dali.gotoacloud.top/Article/details/gtkyovkocf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hfpthk.cn/Article/details/gtztuwrotk.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.cqqwz.cn/Article/details/gtolxqpihj.html

fclose(f);
来源：http://dali.gaohongyu789.top/Article/details/gtytkjtqhn.html

[S12] C：写文件
来源：http://dali.chenjidiqi.icu/Article/details/gttfzhznmn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.cucudq.cn/Article/details/gtyphzlzhf.html

[S13] C：宏定义
来源：http://dali.shanyushiyangkeji.top/Article/details/gtumzoglsq.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.jlsjyb.cn/Article/details/gtxjymgxmv.html

[S14] C：枚举
来源：http://dali.daria6918.cn/Article/details/gtjauoredj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.yongpay.top/Article/details/gtwcgbqlgf.html

[S15] C：类型转换
来源：http://dali.smart0.xyz/Article/details/gtmxgirsjx.html

(double) a / b
来源：http://dali.gzhubu.top/Article/details/gtbqpuscwj.html

[S16] C：位操作置位
来源：http://dali.yuanzhike.top/Article/details/gthjcboamb.html

x |= (1 << 3);
来源：http://dali.hnqzz.top/Article/details/gtowclxljf.html

[S17] C：安全拼接字符串
来源：http://dali.shzxlz.cn/Article/details/gtqmygrdli.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtihaozedu.html

[S18] C：命令行参数
来源：http://dali.yueranfly.top/Article/details/gtwkdymrbj.html

int main(int argc, char **argv)
来源：http://dali.daxiang520.top/Article/details/gtiolodhwi.html

[S19] C：快速排序
来源：http://dali.316326.xyz/Article/details/gthbbzvztv.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.cdnleiting.top/Article/details/gtafxqnmzo.html

[S20] C：二分查找
来源：http://dali.jqgufenzy.top/Article/details/gtffqoiack.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.0kj1m.cn/Article/details/gtnwpfdmnh.html

[S21] C：字符类别判断
来源：http://dali.feifeiyinyue.top/Article/details/gteyxlupip.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.chenzaomai.com/Article/details/gthuybayab.html

[S22] C：字符串转数字
来源：http://dali.shanyushiyangtech.top/Article/details/gtlpxwvtnn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.svipenyu.cn/Article/details/gtynjtaign.html

[S23] C：随机数
来源：http://dali.gotoacloud.top/Article/details/gtuorcjqmp.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.vqdsnc.cn/Article/details/gtyhpnfnac.html

[S24] C：获取本地时间
来源：http://dali.ivvv.top/Article/details/gtxtmrmhpe.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yonumen.top/Article/details/gttxvtzugb.html

[S25] C：内存拷贝
来源：http://dali.vqdsnc.cn/Article/details/gtpylmpyql.html

memcpy(dst, src, n);
来源：http://dali.redwolf501.top/Article/details/gtzffegoia.html

[S26] C：内存清零
来源：http://dali.nwbrower.top/Article/details/gtjtdodmwq.html

memset(a, 0, sizeof a);
来源：http://dali.shzxlz.cn/Article/details/gthrpftxho.html

[S27] C：定义常量
来源：http://dali.316326.xyz/Article/details/gttuiqfrwy.html

const double PI = 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gtdwnzoulq.html

[S28] C：静态变量
来源：http://dali.c1oappe.top/Article/details/gtlezpeasb.html

static int counter = 0;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlakzwhfl.html

[S29] C：变参函数
来源：http://dali.yanxiufei.cn/Article/details/gtsdjcrovc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.chenlongwang.top/Article/details/gtspteeccw.html

[S30] C：头文件保护
来源：http://dali.9152youxi.cn/Article/details/gteqtryhji.html

#ifndef X_H
来源：http://dali.jqgufenzy.top/Article/details/gtsqoqwauw.html

#define X_H
来源：http://dali.yuanzhike.top/Article/details/gtihudwoyk.html

#endif
来源：http://dali.jyoumei.cn/Article/details/gtmdysivkv.html

[S31] C++：Hello World
来源：http://dali.yj20258.top/Article/details/gtcbdwdgtb.html

#include <iostream>
来源：http://dali.nanxuanxn.top/Article/details/gtkjlhczuc.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.shzxlz.cn/Article/details/gtkqncuqdu.html

[S32] C++：字符串
来源：http://dali.jianghu66.top/Article/details/gttyewjecp.html

std::string s = "hi";  s += "!";
来源：http://dali.tanke756.top/Article/details/gtipejcfdx.html

[S33] C++：vector 增删
来源：http://dali.iojbl.cn/Article/details/gtijeabmfk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.pengpengdd.cyou/Article/details/gtmcyfvtpi.html

[S34] C++：遍历 vector
来源：http://dali.nanxuanxn.top/Article/details/gtqzfhvpbc.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.gogol.net.cn/Article/details/gtkirbvdww.html

[S35] C++：map
来源：http://dali.yangfankeji.com/Article/details/gtzexocneq.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgomsbncb.html

[S36] C++：unordered_map
来源：http://dali.tanke756.top/Article/details/gtsqgusbpt.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.aibaodan.cn/Article/details/gtmwrgcams.html

[S37] C++：set
来源：http://dali.hammf.cn/Article/details/gthbkrvkec.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.vqdsnc.cn/Article/details/gtnahrzkob.html

[S38] C++：排序
来源：http://dali.birdmap.top/Article/details/gtxkyiyino.html

std::sort(v.begin(), v.end());
来源：http://dali.gaohongyu789.top/Article/details/gtyvkljwqu.html

[S39] C++：自定义比较器排序
来源：http://dali.9152youxi.cn/Article/details/gtzyssiizd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ivvv.top/Article/details/gtwmzyryke.html

[S40] C++：查找元素
来源：http://dali.svipenyu.cn/Article/details/gtoudlofeq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxptdarwf.html

[S41] C++：类与构造函数
来源：http://dali.nwbrower.top/Article/details/gtiifzeqee.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gtayunmlky.html

[S42] C++：继承与虚函数
来源：http://dali.hnqzz.top/Article/details/gtqfavoorg.html

class B : public Base { public: void f() override {} };
来源：http://dali.snrcjt.cn/Article/details/gtplgugaor.html

[S43] C++：智能指针
来源：http://dali.yongpay.top/Article/details/gtxaflzmzo.html

auto p = std::make_unique<int>(5);
来源：http://dali.sysykeji.top/Article/details/gtbhegvaok.html

[S44] C++：引用传参
来源：http://dali.shanyushiyangtech.top/Article/details/gtophscczv.html

void inc(int &x) { ++x; }
来源：http://dali.yvedp.cn/Article/details/gtzdevjksa.html

[S45] C++：lambda
来源：http://dali.jinqigufen.top/Article/details/gtuwjidqrz.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.svipenyu.cn/Article/details/gtgvkecqkb.html

[S46] C++：函数模板
来源：http://dali.svipenyu.cn/Article/details/gtjmfxwfcq.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtokrxhowm.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhoulong.xyz/Article/details/gtjsmxahcg.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.aibaodan.cn/Article/details/gteuxlzupj.html

[S48] C++：逐行读文件
来源：http://dali.daria6918.cn/Article/details/gtshvxdark.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.dianchejie.cn/Article/details/gtpxyczdxa.html

while (std::getline(in, line)) { }
来源：http://dali.yj20258.top/Article/details/gtejspejva.html

[S49] C++：写文件
来源：http://dali.shangyingyoupin.top/Article/details/gtgziwreao.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.xuetiantiany.cn/Article/details/gteolmepse.html

[S50] C++：格式化数字
来源：http://dali.jqgufenzy.top/Article/details/gtmcgolpye.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.cucudq.cn/Article/details/gtswwnfsjy.html

[S51] C++：显式类型转换
来源：http://dali.hongshengwenyu.top/Article/details/gtpgelrvlk.html

static_cast<double>(a) / b
来源：http://dali.shzxlz.cn/Article/details/gtehprteoz.html

[S52] C++：const 与 noexcept
来源：http://dali.ydzc1.top/Article/details/gtrmqehndf.html

int size() const noexcept { return n_; }
来源：http://dali.hongshengwenyu.top/Article/details/gttbrdrgil.html

[S53] C++：移动语义
来源：http://dali.yangfankeji.com/Article/details/gtcyjbdtbq.html

std::vector<int> w = std::move(v);
来源：http://dali.gzhubu.top/Article/details/gtlhywsfws.html

[S54] C++：异常处理
来源：http://dali.cashguo.top/Article/details/gtbojmmmwy.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.jianghu66.top/Article/details/gtmqbwvjtl.html

[S55] C++：结构化绑定
来源：http://dali.dianchejie.cn/Article/details/gtpvjabjzk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.hfpthk.cn/Article/details/gtcfkmtogj.html

[S56] C++：optional
来源：http://dali.jinqigfzy.top/Article/details/gtyiztazlc.html

std::optional<int> o = 5;  if (o) { int v = *o; }
来源：http://dali.yueranfly.top/Article/details/gtfkwmcyte.html

[S57] C++：编译期常量
来源：http://dali.pengpengdd.cyou/Article/details/gtnpulccwr.html

constexpr int N = 10;
来源：http://dali.tianlin.xyz/Article/details/gtooevmbsx.html

[S58] C++：命名空间
来源：http://dali.guowangkeji.top/Article/details/gtzualcobq.html

namespace ns { int f() { return 1; } }
来源：http://dali.sufxvd.cn/Article/details/gtdtetwvot.html

[S59] C++：静态断言
来源：http://dali.haohaochexian.top/Article/details/gttmfjlxhv.html

static_assert(sizeof(int) == 4, "int 必须 4 字节");
来源：http://dali.tianlin.xyz/Article/details/gtynamaumo.html

[S60] C++：遍历并删除元素
来源：http://dali.sysykeji.top/Article/details/gtwnfkbxui.html


<!-- 参考信息 -->