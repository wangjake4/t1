代发 wailian999

[Q84] 去除首尾空格
来源：http://dali.pengpengdd.cyou/Article/details/gtcoknvbjk.html

SELECT TRIM(name) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtddatqmly.html

[Q85] 数值取整
来源：http://dali.chenlongwang.top/Article/details/gtopdwhhen.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinghuilouyu.cn/Article/details/gtsxeujrkh.html

[Q86] 读取 JSON 字段
来源：http://dali.9152youxi.cn/Article/details/gtydkxrbwa.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.chenlongwang.top/Article/details/gtjbfekiel.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gtyrfynszu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.svipenyu.cn/Article/details/gtydydcsbs.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhengqikj.top/Article/details/gtkmjafnvd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.dianchejie.cn/Article/details/gtxbipwilp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtelksvzgp.html

[Q89] 判断表是否存在
来源：http://dali.xylfe.cn/Article/details/gtcjobajnp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.smart0.xyz/Article/details/gtqovjpnmb.html

[Q90] 生成序号列
来源：http://dali.hywenlv.cn/Article/details/gtnvnwmdfa.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.316326.xyz/Article/details/gtdbmlurzz.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtglujyxbr.html

R. Bash 专题
来源：http://dali.0kj1m.cn/Article/details/gtifchyvtg.html

================================================================================
来源：http://dali.pycfn.com/Article/details/gtlowbzyac.html

[R01] shebang 与严格模式
来源：http://dali.andypj.xyz/Article/details/gttzdkibgx.html

#!/usr/bin/env bash
来源：http://dali.chenjidiqi.icu/Article/details/gtyhzaddlz.html

set -euo pipefail
来源：http://dali.xylfe.cn/Article/details/gtbiveyjsb.html

[R02] 变量赋值与使用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtavxabkzt.html

name="Tom"; echo "$name"
来源：http://dali.xylfe.cn/Article/details/gtythrkhsv.html

[R03] 只读变量
来源：http://dali.yonumen.top/Article/details/gtdgyomqjb.html

readonly PI=3.14
来源：http://dali.bjfxy.top/Article/details/gtovmrumwp.html

[R04] 位置参数
来源：http://dali.nwbrower.top/Article/details/gtoaannlcr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jiagoushi.top/Article/details/gtpawmlgfi.html

[R05] 参数默认值
来源：http://dali.guowangkeji.top/Article/details/gthqhmlpjo.html

name="${1:-default}"
来源：http://dali.meibo888.top/Article/details/gtnezmzgpd.html

[R06] 判断命令是否存在
来源：http://dali.shuidangran.top/Article/details/gtlyyvhryj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.birdmap.top/Article/details/gtytydykfp.html

[R07] if 判断文件
来源：http://dali.jianghu66.top/Article/details/gtpkwaqutr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.9152youxi.cn/Article/details/gtccujftmg.html

[R08] 数值比较
来源：http://dali.feifeiyinyue.top/Article/details/gtozuarmkf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yj20258888.top/Article/details/gtqqihbpjl.html

[R09] 字符串比较
来源：http://dali.yuanzhike.top/Article/details/gtbzbwxztg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.nwbrower.top/Article/details/gtwfjogvwz.html

[R10] 正则匹配
来源：http://dali.redwolf501.top/Article/details/gtybrvlckg.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hysaishi.cn/Article/details/gtywlhvrqm.html

[R11] case 多分支
来源：http://dali.gzhubu.top/Article/details/gtolowbmvx.html

case "$1" in
来源：http://dali.guannengcc.top/Article/details/gtiyiequyk.html

start) echo "启动" ;;
来源：http://dali.nwbrower.top/Article/details/gtgtnssxrg.html

stop)  echo "停止" ;;
来源：http://dali.jqgufenzy.top/Article/details/gtqanvymwv.html

*)     echo "未知命令" ;;
来源：http://dali.shuidangran.top/Article/details/gtlwlbavxr.html

esac
来源：http://dali.fengsongda.top/Article/details/gtyasrsmaj.html

[R12] for 遍历文件
来源：http://dali.wangshuangyany.cn/Article/details/gtxbydifpq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hnqzz.top/Article/details/gtinzjalja.html

[R13] for 计数循环
来源：http://dali.jinghuilouyu.cn/Article/details/gtmpmadlgy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yonumen.top/Article/details/gtlqjgxgwu.html

[R14] C 风格 for
来源：http://dali.yvedp.cn/Article/details/gtvmiorxpl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.fengsongda.top/Article/details/gtbxgfvfgo.html

[R15] while 逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gtuonosice.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.svipenyu.cn/Article/details/gtdiacxgiy.html

[R16] until 等待条件
来源：http://dali.vqdsnc.cn/Article/details/gtzrftvwdn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yangfankeji.com/Article/details/gtghuxalkm.html

[R17] 数组定义与取值
来源：http://dali.xinyue.icu/Article/details/gtwqedsdmm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.meibo888.top/Article/details/gtwmcbrgtj.html

[R18] 遍历数组
来源：http://dali.havefunace.top/Article/details/gtyizlkmws.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.vqdsnc.cn/Article/details/gtusbclspl.html

[R19] 数组长度
来源：http://dali.sxryk.cn/Article/details/gtaywhnvhp.html

echo "${#arr[@]}"
来源：http://dali.yuxming.cn/Article/details/gtfaisfhhp.html

[R20] 关联数组（字典）
来源：http://dali.zhixingplan.top/Article/details/gtrrmocgij.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xuanzx.com/Article/details/gtkgludgay.html

[R21] 字符串长度
来源：http://dali.hywenlv.cn/Article/details/gtovglogfh.html

echo "${#s}"
来源：http://dali.jinqigfzy.top/Article/details/gtjehzvolu.html

[R22] 截取子串
来源：http://dali.sweek.top/Article/details/gtuivfeluo.html

echo "${s:0:5}"
来源：http://dali.dianchejie.cn/Article/details/gtbaxxjboq.html

[R23] 字符串替换
来源：http://dali.dashuyun.cn/Article/details/gthikpvkph.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.quarkkingdee.top/Article/details/gtzkmzkusc.html

[R24] 大小写转换
来源：http://dali.jyoumei.cn/Article/details/gtjelsmixb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cashguo.top/Article/details/gtjzteoqsu.html

[R25] 去后缀 / 去前缀
来源：http://dali.tian-w.cn/Article/details/gtmgexdpnv.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gtnonvqggk.html

[R26] 命令替换
来源：http://dali.wangshuangyany.cn/Article/details/gtavustkot.html

now=$(date +%F); echo "$now"
来源：http://dali.dianchejie.cn/Article/details/gttpsflcmc.html

[R27] 算术展开
来源：http://dali.xinyue.icu/Article/details/gtcxioaten.html

echo $((1 + 2 * 3))
来源：http://dali.redwolf501.top/Article/details/gtfvpaewsi.html

[R28] 浮点运算
来源：http://dali.xuetiantiany.cn/Article/details/gthxuhiray.html

echo "scale=2; 10/3" | bc
来源：http://dali.aizwys.cn/Article/details/gtimimdona.html

[R29] 定义函数
来源：http://dali.hywenlv.cn/Article/details/gtwttgetjp.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.havefunace.top/Article/details/gtuenfzyxx.html

[R30] 函数返回状态码
来源：http://dali.nanxuanxn.top/Article/details/gtkxwyxcce.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tanke756.top/Article/details/gtkimuzimq.html

[R31] 局部变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuiykrycg.html

f() { local x=1; echo "$x"; }
来源：http://dali.havefunace.top/Article/details/gtvqqgqrjp.html

[R32] 参数个数校验
来源：http://dali.hfpthk.cn/Article/details/gtzeeffcmc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yj202588.top/Article/details/gtjvujmhgf.html

[R33] 捕获错误并提示行号
来源：http://dali.quarkkingdee.top/Article/details/gtmtplmmkz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtchevhtbu.html

[R34] 退出时清理
来源：http://dali.jianghu66.top/Article/details/gtkerdzmlm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ywan-chungtsiang.top/Article/details/gtybrbsyca.html

[R35] 后台执行并等待
来源：http://dali.zhongyouzk.top/Article/details/gtnmavwbzl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtftdoshgl.html

[R36] 并发执行多个任务
来源：http://dali.hfpthk.cn/Article/details/gthlhqjuda.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cdnleiting.top/Article/details/gtvcfpkbft.html

[R37] 把输出赋给变量
来源：http://dali.chenzaomai.com/Article/details/gtrnemrxxp.html

files=$(ls -1)
来源：http://dali.zhengqikj.top/Article/details/gtdkccisgu.html

[R38] 管道串联
来源：http://dali.wangshuangyany.cn/Article/details/gtkxwfvdnh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.fengsongda.top/Article/details/gtqhgqthqz.html

[R39] 重定向标准输出与错误
来源：http://dali.kuanghao11.cn/Article/details/gtsvwwkwzc.html

cmd > out.log 2>&1
来源：http://dali.yongpay.top/Article/details/gtpqlqxnpu.html

[R40] 追加写日志
来源：http://dali.andypj.xyz/Article/details/gtusxuqbfd.html

echo "log" >> out.log
来源：http://dali.fzhhl.top/Article/details/gtpxjbdurl.html

[R41] 丢弃输出
来源：http://dali.yj20258.top/Article/details/gtzalqmuak.html

cmd >/dev/null 2>&1
来源：http://dali.wangdashe.top/Article/details/gtkgqvcbub.html

[R42] 输入重定向
来源：http://dali.hywenlv.cn/Article/details/gtgqtxagbi.html

wc -l < a.txt
来源：http://dali.ehwqpu.com/Article/details/gtjpbxzcnq.html

[R43] 按名字查找文件
来源：http://dali.ppjwa.cn/Article/details/gtifamxoqu.html

find . -name "*.log" -type f
来源：http://dali.9152youxi.cn/Article/details/gtrleosrqs.html

[R44] 按修改时间查找
来源：http://dali.jinqigfzy.top/Article/details/gtrfytkjhr.html

find . -mtime -7 -type f
来源：http://dali.gzhubu.top/Article/details/gtisauyebh.html

[R45] 批量删除
来源：http://dali.dashuyun.cn/Article/details/gtgftcelgl.html

find . -name "*.tmp" -delete
来源：http://dali.zdqjudy.top/Article/details/gtbyyhjnoc.html

[R46] 递归替换文件内容
来源：http://dali.fzhhl.top/Article/details/gtsmxsbyqd.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.aizwys.cn/Article/details/gtfekkdxpg.html

[R47] sed 单行替换
来源：http://dali.zycfv.cn/Article/details/gttsanrjaz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.andypj.xyz/Article/details/gttiprcjec.html

[R48] awk 取指定列
来源：http://dali.xziqi.cn/Article/details/gtrujwezva.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gtqmzsvbhu.html

[R49] awk 带条件
来源：http://dali.cashguo.top/Article/details/gtmqtxffqh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jianghu66.top/Article/details/gtpeauctaw.html

[R50] awk 求和
来源：http://dali.zhixingplan.top/Article/details/gtgftiarkl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.havefunace.top/Article/details/gtqbcpisux.html

[R51] 排序去重取前几
来源：http://dali.zhiwuduotai.top/Article/details/gtqsfsyfpv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cqqwz.cn/Article/details/gtivdkqocx.html

[R52] 统计行数
来源：http://dali.sxryk.cn/Article/details/gtppholjtd.html

wc -l a.txt
来源：http://dali.snrcjt.cn/Article/details/gtyshczpuu.html

[R53] 查看文件头与实时尾
来源：http://dali.aizwys.cn/Article/details/gtmjkuaqix.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tian-w.cn/Article/details/gtjywsvpti.html

[R54] 比较两个文件
来源：http://dali.hysaishi.cn/Article/details/gtxoapctvs.html

diff a.txt b.txt
来源：http://dali.aizwys.cn/Article/details/gtterkbsvn.html

[R55] 压缩与解压
来源：http://dali.pycfn.com/Article/details/gtoontkhii.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hfpthk.cn/Article/details/gtpzrxrvjj.html

[R56] 远程拷贝
来源：http://dali.fzhhl.top/Article/details/gtoccelktp.html

scp file user@host:/path/
来源：http://dali.dashuyun.cn/Article/details/gtpmtcpygw.html

[R57] 远程执行命令
来源：http://dali.tanke756.top/Article/details/gtobvjdlfb.html

ssh user@host 'uptime'
来源：http://dali.meibo888.top/Article/details/gtmhmpbsjw.html

[R58] 下载文件
来源：http://dali.gogol.net.cn/Article/details/gtoyxavuwk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.dianchejie.cn/Article/details/gtcnaiqjlb.html

[R59] 发 POST JSON
来源：http://dali.xuetiantiany.cn/Article/details/gtgeckonyw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.andypj.xyz/Article/details/gtpjfnajgj.html

[R60] 只看 HTTP 状态码
来源：http://dali.chenzaomai.com/Article/details/gtzijypnai.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yongpay.top/Article/details/gtygzpzzly.html

[R61] 磁盘占用
来源：http://dali.9152youxi.cn/Article/details/gttcedvpnw.html

df -h;  du -sh *
来源：http://dali.gaohongyu789.top/Article/details/gtmmgsnnez.html

[R62] 找最占空间的文件
来源：http://dali.jyoumei.cn/Article/details/gtfzbpljjv.html

du -ah . | sort -rh | head -10
来源：http://dali.hfpthk.cn/Article/details/gtzihanspe.html

[R63] 内存与进程
来源：http://dali.shzxlz.cn/Article/details/gtajaojxwn.html

free -h;  ps aux | grep nginx
来源：http://dali.snrcjt.cn/Article/details/gtrszemppv.html

[R64] 结束进程
来源：http://dali.redwolf501.top/Article/details/gtcdccnrlh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.haohaochexian.top/Article/details/gttjpkghki.html

[R65] 查看端口占用
来源：http://dali.tian-w.cn/Article/details/gtzsfakqnz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhiwuduotai.top/Article/details/gtmnsdzoxx.html

[R66] 定时任务
来源：http://dali.bjfxy.top/Article/details/gtgoeougwd.html

crontab -e;  crontab -l
来源：http://dali.316326.xyz/Article/details/gtautmmcws.html

[R67] 生成随机十六进制串
来源：http://dali.c1oappe.top/Article/details/gtnoxfrpsm.html

openssl rand -hex 16
来源：http://dali.birdmap.top/Article/details/gtbdgrmnud.html

[R68] 计算文件校验值
来源：http://dali.jyoumei.cn/Article/details/gtmvzqtpdc.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.dashuyun.cn/Article/details/gtjrujjlkw.html

[R69] 生成随机密码
来源：http://dali.hnqzz.top/Article/details/gtuqqhqiru.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhixingplan.top/Article/details/gthjoqgbyl.html

[R70] 时间戳与互转
来源：http://dali.shangyingyoupin.top/Article/details/gtmzwqvnzr.html

date +%s;  date -d @1700000000
来源：http://dali.ppjwa.cn/Article/details/gtuwaxmrwg.html

[R71] 日期格式化
来源：http://dali.nanxinkj.top/Article/details/gtpmdvbyoq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.chenzaomai.com/Article/details/gttrtkkpcd.html

[R72] 等待端口就绪
来源：http://dali.hysaishi.cn/Article/details/gthymglgdk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.bjfxy.top/Article/details/gtxbotxeyq.html

[R73] 分割大日志
来源：http://dali.fengsongda.top/Article/details/gtuyazwcin.html

split -l 1000 big.log part_
来源：http://dali.xylfe.cn/Article/details/gtklwxokiy.html

[R74] 批量重命名
来源：http://dali.kuanghao11.cn/Article/details/gtzamjrnlj.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.0kj1m.cn/Article/details/gtgjbgadlv.html

[R75] 导出环境变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrqplnelj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.nanxinkj.top/Article/details/gtcceelinz.html

[R76] 使用临时文件
来源：http://dali.mhx1999.top/Article/details/gtbgrniqur.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhengqikj.top/Article/details/gtqyvypxjh.html

[R77] 读取用户输入
来源：http://dali.yj20258888.top/Article/details/gtkiwjtxtv.html

read -rp "请输入: " ans
来源：http://dali.haohaochexian.top/Article/details/gtbygmvsac.html

[R78] 交互式菜单
来源：http://dali.smart0.xyz/Article/details/gtqclkdmqz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.dianchejie.cn/Article/details/gtqnofldzc.html

[R79] 解析命令行选项
来源：http://dali.nanxinkj.top/Article/details/gtavwcgluc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jqgfzy.top/Article/details/gtiuotpiia.html

[R80] 查看脚本执行耗时
来源：http://dali.zdqjudy.top/Article/details/gtrmverdvi.html

time ./run.sh
来源：http://dali.chenzaomai.com/Article/details/gtkhuwyfao.html

================================================================================
来源：http://dali.yanxiufei.cn/Article/details/gtsoxlrmuc.html

S. C / C++ 专题
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpjqslckm.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtggxmhiev.html

[S01] C：Hello World
来源：http://dali.smart0.xyz/Article/details/gtlbxtklnt.html

#include <stdio.h>
来源：http://dali.ydzc1.top/Article/details/gtnfwfxlss.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jianghu66.top/Article/details/gttoxfmruw.html

[S02] C：变量与格式化输出
来源：http://dali.sweek.top/Article/details/gthuyenqsv.html

int a = 10; printf("%d\n", a);
来源：http://dali.xuetiantiany.cn/Article/details/gtbjcaapqw.html

[S03] C：读入整数
来源：http://dali.jyoumei.cn/Article/details/gtprvmqlxs.html

int x; scanf("%d", &x);
来源：http://dali.xziqi.cn/Article/details/gtkfqdavny.html

[S04] C：字符串复制
来源：http://dali.yuxming.cn/Article/details/gthutkqkrk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhengqikj.top/Article/details/gtpclzlgdm.html

[S05] C：字符串长度
来源：http://dali.gotoacloud.top/Article/details/gtzhpkhzfi.html

strlen(s)
来源：http://dali.jqgfzy.top/Article/details/gtlkogrxjo.html

[S06] C：字符串比较
来源：http://dali.9152youxi.cn/Article/details/gtnyvplrwj.html

strcmp(a, b) == 0
来源：http://dali.mhx1999.top/Article/details/gtarogrtqf.html

[S07] C：数组遍历求和
来源：http://dali.cheryme.top/Article/details/gtrphlaaiy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jiagoushi.top/Article/details/gtyajxaleg.html

[S08] C：动态内存分配与释放
来源：http://dali.redwolf501.top/Article/details/gtnmrygfvb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.9152youxi.cn/Article/details/gtbcsjmeyo.html

[S09] C：结构体定义与初始化
来源：http://dali.xuanzx.com/Article/details/gtumdmoxvd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.guowangkeji.top/Article/details/gtrqyqscwh.html

[S10] C：指针与解引用
来源：http://dali.316326.xyz/Article/details/gtbckpmgnd.html

int *p = &a;  *p = 5;
来源：http://dali.shangyingyoupin.top/Article/details/gtwaaxrxka.html

[S11] C：逐行读文件
来源：http://dali.yj202588.top/Article/details/gtlxlytvvv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.meibo888.top/Article/details/gtdvzopeuz.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.jyoumei.cn/Article/details/gtpivwqnbn.html

fclose(f);
来源：http://dali.aibaodan.cn/Article/details/gttyjjplvc.html

[S12] C：写文件
来源：http://dali.yangfankeji.com/Article/details/gtajnstcnz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.meibo888.top/Article/details/gtymgrsgwe.html

[S13] C：宏定义
来源：http://dali.hnxiangtu.top/Article/details/gtdtzyzigh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.tanke756.top/Article/details/gttnrwljql.html

[S14] C：枚举
来源：http://dali.birdmap.top/Article/details/gthyomsgcb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hysaishi.cn/Article/details/gtknyybtmp.html

[S15] C：类型转换
来源：http://dali.wangdashe.top/Article/details/gttgjqhhgo.html

(double) a / b
来源：http://dali.zhixingplan.top/Article/details/gtsdqsrzpd.html

[S16] C：位操作置位
来源：http://dali.9152youxi.cn/Article/details/gtutseejwv.html

x |= (1 << 3);
来源：http://dali.ydzc1.top/Article/details/gtefdhvmse.html

[S17] C：安全拼接字符串
来源：http://dali.zhiwuduotai.top/Article/details/gtgxufzphm.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.iojbl.cn/Article/details/gtzncliive.html

[S18] C：命令行参数
来源：http://dali.cheryme.top/Article/details/gtzunnxfds.html

int main(int argc, char **argv)
来源：http://dali.nanxuanxn.top/Article/details/gtiwryjhhh.html

[S19] C：快速排序
来源：http://dali.jianghu66.top/Article/details/gtizuxpflu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.havefunace.top/Article/details/gtlqknjikp.html

[S20] C：二分查找
来源：http://dali.xziqi.cn/Article/details/gtouiqlpmy.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.haohaochexian.top/Article/details/gtfyyrqflg.html

[S21] C：字符类别判断
来源：http://dali.zhixingplan.top/Article/details/gtdlrjpfaq.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sweek.top/Article/details/gtfniadubc.html

[S22] C：字符串转数字
来源：http://dali.tanke756.top/Article/details/gtwuqrivdh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zdqjudy.top/Article/details/gtrtgjujnz.html

[S23] C：随机数
来源：http://dali.snrcjt.cn/Article/details/gtsrmrsulr.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.tanke756.top/Article/details/gtehvfecdx.html

[S24] C：获取本地时间
来源：http://dali.zhixingplan.top/Article/details/gtqnpeelhe.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.chenjidiqi.icu/Article/details/gtgdowxtvx.html

[S25] C：内存拷贝
来源：http://dali.fzhhl.top/Article/details/gtxmyukmyq.html

memcpy(dst, src, n);
来源：http://dali.feifeiyinyue.top/Article/details/gtagceosna.html

[S26] C：内存清零
来源：http://dali.hnqzz.top/Article/details/gtbwmjjehy.html

memset(a, 0, sizeof a);
来源：http://dali.meibo888.top/Article/details/gthirtbpxq.html

[S27] C：定义常量
来源：http://dali.redwolf501.top/Article/details/gtijgfyihy.html

const double PI = 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gtmzjonfik.html

[S28] C：静态变量
来源：http://dali.316326.xyz/Article/details/gtwvkrtvgq.html

static int counter = 0;
来源：http://dali.zhoulong.xyz/Article/details/gtzuijujmg.html

[S29] C：变参函数
来源：http://dali.cqqwz.cn/Article/details/gtjeutapiy.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.sxryk.cn/Article/details/gtmccinmtj.html

[S30] C：头文件保护
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcotbmepe.html

#ifndef X_H
来源：http://dali.hfpthk.cn/Article/details/gtagpkqnyx.html

#define X_H
来源：http://dali.ivvv.top/Article/details/gtfqsrpddm.html

#endif
来源：http://dali.daria6918.cn/Article/details/gtcznhzyfw.html

[S31] C++：Hello World
来源：http://dali.snrcjt.cn/Article/details/gtmkfmljrl.html

#include <iostream>
来源：http://dali.iojbl.cn/Article/details/gtvcbomxgo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.cdnleiting.top/Article/details/gtagmtjhvy.html

[S32] C++：字符串
来源：http://dali.zhongyouzk.top/Article/details/gtcrgclycz.html

std::string s = "hi";  s += "!";
来源：http://dali.sweek.top/Article/details/gthbdvbjiq.html

[S33] C++：vector 增删
来源：http://dali.nwbrower.top/Article/details/gtjmdiefdc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.gotoacloud.top/Article/details/gtofyflqzd.html

[S34] C++：遍历 vector
来源：http://dali.haohaochexian.top/Article/details/gtgmmwzlsa.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.aizwys.cn/Article/details/gtfgyfnhvq.html

[S35] C++：map
来源：http://dali.sxryk.cn/Article/details/gtpqtotwvh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtokkrqtvg.html

[S36] C++：unordered_map
来源：http://dali.zhongyouzk.top/Article/details/gtuaqqtclc.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.haohaochexian.top/Article/details/gtepiwarqw.html

[S37] C++：set
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmzhjwvou.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.tianlin.xyz/Article/details/gtxmdzzykh.html

[S38] C++：排序
来源：http://dali.quarkkingdee.top/Article/details/gtyusxdchu.html

std::sort(v.begin(), v.end());
来源：http://dali.zhijiandao.cn/Article/details/gtrzfhcyrt.html

[S39] C++：自定义比较器排序
来源：http://dali.hnxiangtu.top/Article/details/gtahgafxyg.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.ydzc1.top/Article/details/gtamezhkaz.html

[S40] C++：查找元素
来源：http://dali.pengpengdd.cyou/Article/details/gtjwdwfzmj.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.daria6918.cn/Article/details/gthbtqtdrp.html

[S41] C++：类与构造函数
来源：http://dali.redwolf501.top/Article/details/gtrxofutaj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gttscgxiyj.html

[S42] C++：继承与虚函数
来源：http://dali.ybcxt.top/Article/details/gtzivpyexw.html

class B : public Base { public: void f() override {} };
来源：http://dali.iojbl.cn/Article/details/gttkzaxtbm.html

[S43] C++：智能指针
来源：http://dali.tianlin.xyz/Article/details/gtrdkmzgkn.html

auto p = std::make_unique<int>(5);
来源：http://dali.9152youxi.cn/Article/details/gtaesebgwy.html

[S44] C++：引用传参
来源：http://dali.xylfe.cn/Article/details/gtbtxbtoau.html

void inc(int &x) { ++x; }
来源：http://dali.tianlin.xyz/Article/details/gthjhiyjsp.html

[S45] C++：lambda
来源：http://dali.zycfv.cn/Article/details/gtshczxrph.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.shangyingyoupin.top/Article/details/gtshpophrc.html

[S46] C++：函数模板
来源：http://dali.svipenyu.cn/Article/details/gtwiztlopm.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtspffuqag.html

[S47] C++：结构化绑定遍历
来源：http://dali.haohaochexian.top/Article/details/gtxbdvlwis.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.0kj1m.cn/Article/details/gtqqyvjtab.html

[S48] C++：逐行读文件
来源：http://dali.dashuyun.cn/Article/details/gtsdiwfwyj.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.quarkkingdee.top/Article/details/gtyaguumlp.html

while (std::getline(in, line)) { }
来源：http://dali.c1oappe.top/Article/details/gtzcukbpza.html

[S49] C++：写文件
来源：http://dali.9152youxi.cn/Article/details/gtviiqmnnb.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.jinqigfzy.top/Article/details/gtkifdxpyf.html

[S50] C++：格式化数字
来源：http://dali.ppjwa.cn/Article/details/gtauayeftd.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gtcqessvnh.html

[S51] C++：显式类型转换
来源：http://dali.yonumen.top/Article/details/gtpwzcojql.html

static_cast<double>(a) / b
来源：http://dali.yj202588.top/Article/details/gttlzyjixq.html

[S52] C++：const 与 noexcept
来源：http://dali.xuanzx.com/Article/details/gtjqdvtefk.html

int size() const noexcept { return n_; }
来源：http://dali.iojbl.cn/Article/details/gtkkmvmpjt.html

[S53] C++：移动语义
来源：http://dali.dianchejie.cn/Article/details/gtfczsfwls.html

std::vector<int> w = std::move(v);
来源：http://dali.jlsjyb.cn/Article/details/gtzilitzjb.html

[S54] C++：异常处理
来源：http://dali.daxiang520.top/Article/details/gtiforwsfe.html


<!-- 参考信息 -->