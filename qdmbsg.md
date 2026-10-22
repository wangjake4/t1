代发 wailian999

[Q82] 字符长度与字节长度
来源：http://dali.cdnleiting.top/Article/details/gtpfeobsup.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtsvygrzed.html

[Q83] 大小写转换
来源：http://dali.dashuyun.cn/Article/details/gtzmjiivru.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtzkfxepmb.html

[Q84] 去除首尾空格
来源：http://dali.andypj.xyz/Article/details/gtgekhlwfp.html

SELECT TRIM(name) FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtoekrsaxq.html

[Q85] 数值取整
来源：http://dali.zhiwuduotai.top/Article/details/gthglcwclt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.aizwys.cn/Article/details/gtahmnmbed.html

[Q86] 读取 JSON 字段
来源：http://dali.kuanghao11.cn/Article/details/gtvjkcbxfj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhixingplan.top/Article/details/gtyrbeevnn.html

[Q87] JSON 字段做条件
来源：http://dali.yvedp.cn/Article/details/gtvdbpliwq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinqigfzy.top/Article/details/gtrpskhzpf.html

[Q88] 行转列（条件聚合）
来源：http://dali.sxryk.cn/Article/details/gthrfdhrjm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.sysykeji.top/Article/details/gthmkndose.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtazjcmwqx.html

[Q89] 判断表是否存在
来源：http://dali.bjfxy.top/Article/details/gtugjllhkh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jiagoushi.top/Article/details/gtzypmodhd.html

[Q90] 生成序号列
来源：http://dali.tianlin.xyz/Article/details/gtoeykbhkr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hnxiangtu.top/Article/details/gtqhzjhykt.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtbzsmdvoy.html

R. Bash 专题
来源：http://dali.fengsongda.top/Article/details/gtfftpgmle.html

================================================================================
来源：http://dali.haohaochexian.top/Article/details/gtbrbrfxaj.html

[R01] shebang 与严格模式
来源：http://dali.bjfxy.top/Article/details/gtdfjmudwu.html

#!/usr/bin/env bash
来源：http://dali.pengpengdd.cyou/Article/details/gtmvuysvis.html

set -euo pipefail
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgzrkylyv.html

[R02] 变量赋值与使用
来源：http://dali.yonumen.top/Article/details/gtsstlpemf.html

name="Tom"; echo "$name"
来源：http://dali.meibo888.top/Article/details/gtvpcnpgpc.html

[R03] 只读变量
来源：http://dali.yangfankeji.com/Article/details/gtgratytaf.html

readonly PI=3.14
来源：http://dali.havefunace.top/Article/details/gtjthxtvrf.html

[R04] 位置参数
来源：http://dali.haohaochexian.top/Article/details/gtebblynxw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtexkwwhat.html

[R05] 参数默认值
来源：http://dali.gogol.net.cn/Article/details/gtkzhujqtl.html

name="${1:-default}"
来源：http://dali.jiagoushi.top/Article/details/gtcmalhled.html

[R06] 判断命令是否存在
来源：http://dali.ydzc1.top/Article/details/gtjunyivsf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.chenzaomai.com/Article/details/gtbfwunwik.html

[R07] if 判断文件
来源：http://dali.bjfxy.top/Article/details/gtweunnlwm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yongpay.top/Article/details/gtuxfbdvmv.html

[R08] 数值比较
来源：http://dali.jinqigufen.top/Article/details/gtaauyqtqn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gotoacloud.top/Article/details/gtbgkcgheb.html

[R09] 字符串比较
来源：http://dali.shangyingyoupin.top/Article/details/gtrlgxzdwg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.guowangkeji.top/Article/details/gtrbvefrwv.html

[R10] 正则匹配
来源：http://dali.meibo888.top/Article/details/gtcscuuqpv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hnqzz.top/Article/details/gtrpencddb.html

[R11] case 多分支
来源：http://dali.jiagoushi.top/Article/details/gtkevathdj.html

case "$1" in
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvfgttepc.html

start) echo "启动" ;;
来源：http://dali.guannengcc.top/Article/details/gtqukzywum.html

stop)  echo "停止" ;;
来源：http://dali.0kj1m.cn/Article/details/gtewckbgbs.html

*)     echo "未知命令" ;;
来源：http://dali.shanyushiyangkeji.top/Article/details/gteobwkcxz.html

esac
来源：http://dali.yj20258888.top/Article/details/gtuyssdold.html

[R12] for 遍历文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtshfrjlcm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gzhubu.top/Article/details/gtjmzqqgst.html

[R13] for 计数循环
来源：http://dali.gogol.net.cn/Article/details/gtzcdrmhet.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.aizwys.cn/Article/details/gtjojbrtnx.html

[R14] C 风格 for
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsghpdzsf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cheryme.top/Article/details/gtlgzvdivj.html

[R15] while 逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtegqhpiqv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.daxiang520.top/Article/details/gtpwdhvpdf.html

[R16] until 等待条件
来源：http://dali.wangdashe.top/Article/details/gtawbryqtw.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jinqigfzy.top/Article/details/gtedfiklmb.html

[R17] 数组定义与取值
来源：http://dali.yangfankeji.com/Article/details/gtmavdlmzf.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtpqlflrif.html

[R18] 遍历数组
来源：http://dali.dianchejie.cn/Article/details/gtgljgvvne.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.fzhhl.top/Article/details/gtexivmeox.html

[R19] 数组长度
来源：http://dali.fzhhl.top/Article/details/gtlkmlaoif.html

echo "${#arr[@]}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuchxkiaj.html

[R20] 关联数组（字典）
来源：http://dali.0kj1m.cn/Article/details/gtetmwzgxv.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.9152youxi.cn/Article/details/gtxlwformi.html

[R21] 字符串长度
来源：http://dali.gotoacloud.top/Article/details/gtuedhuply.html

echo "${#s}"
来源：http://dali.shzxlz.cn/Article/details/gttelwdhcb.html

[R22] 截取子串
来源：http://dali.jianghu66.top/Article/details/gtwuyofpoi.html

echo "${s:0:5}"
来源：http://dali.vqdsnc.cn/Article/details/gtztzsdrvt.html

[R23] 字符串替换
来源：http://dali.yanxiufei.cn/Article/details/gtvfafrhpz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yanxiufei.cn/Article/details/gtbsfrmhbz.html

[R24] 大小写转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrywgjhxp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.0kj1m.cn/Article/details/gtvbrrkaqa.html

[R25] 去后缀 / 去前缀
来源：http://dali.cheryme.top/Article/details/gtugqbhhuy.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shangyingyoupin.top/Article/details/gtypmzjkjv.html

[R26] 命令替换
来源：http://dali.meibo888.top/Article/details/gtiqxlwwlc.html

now=$(date +%F); echo "$now"
来源：http://dali.feifeiyinyue.top/Article/details/gthiscyjqt.html

[R27] 算术展开
来源：http://dali.chenlongwang.top/Article/details/gtlpbqxgon.html

echo $((1 + 2 * 3))
来源：http://dali.andypj.xyz/Article/details/gthudolmml.html

[R28] 浮点运算
来源：http://dali.zhixingplan.top/Article/details/gtrqnqdnhx.html

echo "scale=2; 10/3" | bc
来源：http://dali.zdqjudy.top/Article/details/gtnmbgkvmd.html

[R29] 定义函数
来源：http://dali.shuidangran.top/Article/details/gtxiqzdbkd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yj20258.top/Article/details/gtinzjudqv.html

[R30] 函数返回状态码
来源：http://dali.sxryk.cn/Article/details/gtxoqgopee.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hongshengwenyu.top/Article/details/gtbmoswxnj.html

[R31] 局部变量
来源：http://dali.jinqigufen.top/Article/details/gtktziulxj.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtamoaysxk.html

[R32] 参数个数校验
来源：http://dali.hfpthk.cn/Article/details/gtulfoibpw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.wangshuangyany.cn/Article/details/gtgbxurjig.html

[R33] 捕获错误并提示行号
来源：http://dali.cqqwz.cn/Article/details/gtagpwoocp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yvedp.cn/Article/details/gtumjgjiba.html

[R34] 退出时清理
来源：http://dali.jinqigfzy.top/Article/details/gtugvcgxxb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenlongwang.top/Article/details/gtqnfisljy.html

[R35] 后台执行并等待
来源：http://dali.c1oappe.top/Article/details/gtwsrnlezv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zdqjudy.top/Article/details/gtgqvhiuyc.html

[R36] 并发执行多个任务
来源：http://dali.zhengqikj.top/Article/details/gtaogywsho.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ybcxt.top/Article/details/gtjlrvdbgz.html

[R37] 把输出赋给变量
来源：http://dali.tian-w.cn/Article/details/gtitwblisr.html

files=$(ls -1)
来源：http://dali.hongshengwenyu.top/Article/details/gtuuuvezna.html

[R38] 管道串联
来源：http://dali.jiagoushi.top/Article/details/gtckpwpvpc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hongshengwenyu.top/Article/details/gtqagafbvc.html

[R39] 重定向标准输出与错误
来源：http://dali.daria6918.cn/Article/details/gtasjrxjce.html

cmd > out.log 2>&1
来源：http://dali.cucudq.cn/Article/details/gtixbyxekh.html

[R40] 追加写日志
来源：http://dali.zhiwuduotai.top/Article/details/gtilhkukky.html

echo "log" >> out.log
来源：http://dali.0kj1m.cn/Article/details/gtizelpypn.html

[R41] 丢弃输出
来源：http://dali.nanxuanxn.top/Article/details/gtauaagptl.html

cmd >/dev/null 2>&1
来源：http://dali.hnqzz.top/Article/details/gtoqqgoxwr.html

[R42] 输入重定向
来源：http://dali.redwolf501.top/Article/details/gteaxyzdzc.html

wc -l < a.txt
来源：http://dali.svipenyu.cn/Article/details/gtieycqbgz.html

[R43] 按名字查找文件
来源：http://dali.zhixingplan.top/Article/details/gtatkapnxc.html

find . -name "*.log" -type f
来源：http://dali.shzxlz.cn/Article/details/gtrafmsupq.html

[R44] 按修改时间查找
来源：http://dali.hysaishi.cn/Article/details/gthwmwbwbc.html

find . -mtime -7 -type f
来源：http://dali.daria6918.cn/Article/details/gtvnexybfu.html

[R45] 批量删除
来源：http://dali.pycfn.com/Article/details/gtwjumaolr.html

find . -name "*.tmp" -delete
来源：http://dali.9152youxi.cn/Article/details/gtmntldten.html

[R46] 递归替换文件内容
来源：http://dali.cucudq.cn/Article/details/gtktfealmr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.pengpengdd.cyou/Article/details/gttgnzoirt.html

[R47] sed 单行替换
来源：http://dali.xinyue.icu/Article/details/gtinctzimr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtvaqiisjh.html

[R48] awk 取指定列
来源：http://dali.nanxuanxn.top/Article/details/gtsrbhotpr.html

awk '{print $1, $3}' a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtzbcjvjuh.html

[R49] awk 带条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxatsdzuv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cucudq.cn/Article/details/gtspxbsdsa.html

[R50] awk 求和
来源：http://dali.xziqi.cn/Article/details/gtyjxyobmp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtsgqbydka.html

[R51] 排序去重取前几
来源：http://dali.hfpthk.cn/Article/details/gtgiczspxl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.316326.xyz/Article/details/gtmpabkogb.html

[R52] 统计行数
来源：http://dali.shanyushiyangkeji.top/Article/details/gthntpmhmf.html

wc -l a.txt
来源：http://dali.andypj.xyz/Article/details/gtryisxonb.html

[R53] 查看文件头与实时尾
来源：http://dali.daxiang520.top/Article/details/gtidlbssdw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ydzc1.top/Article/details/gtbiesmvlq.html

[R54] 比较两个文件
来源：http://dali.chenlongwang.top/Article/details/gtoxzepudq.html

diff a.txt b.txt
来源：http://dali.cheryme.top/Article/details/gtvwvswcbf.html

[R55] 压缩与解压
来源：http://dali.guowangkeji.top/Article/details/gtgetwidie.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cashguo.top/Article/details/gtfpoldsgo.html

[R56] 远程拷贝
来源：http://dali.daria6918.cn/Article/details/gtlxlmwvfs.html

scp file user@host:/path/
来源：http://dali.gzhubu.top/Article/details/gtpxxageum.html

[R57] 远程执行命令
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmfbrllwi.html

ssh user@host 'uptime'
来源：http://dali.gogol.net.cn/Article/details/gtbnruuzeh.html

[R58] 下载文件
来源：http://dali.shangyingyoupin.top/Article/details/gthajgqslt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cdnleiting.top/Article/details/gtrvdxrylf.html

[R59] 发 POST JSON
来源：http://dali.zycfv.cn/Article/details/gterrezdpt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yj202588.top/Article/details/gtnxfgmgvm.html

[R60] 只看 HTTP 状态码
来源：http://dali.smart0.xyz/Article/details/gtypaqjfco.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.snrcjt.cn/Article/details/gtkkreeecb.html

[R61] 磁盘占用
来源：http://dali.jianghu66.top/Article/details/gtejdxooyr.html

df -h;  du -sh *
来源：http://dali.shanyushiyangkeji.top/Article/details/gtghfwdzlq.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gtlynwnkhl.html

du -ah . | sort -rh | head -10
来源：http://dali.sxryk.cn/Article/details/gtmecfnrgm.html

[R63] 内存与进程
来源：http://dali.cucudq.cn/Article/details/gtijlxtjrk.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gthsytvgqh.html

[R64] 结束进程
来源：http://dali.ppjwa.cn/Article/details/gtfthnponl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.aizwys.cn/Article/details/gttjrhscwz.html

[R65] 查看端口占用
来源：http://dali.fzhhl.top/Article/details/gtcsihefic.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yuxming.cn/Article/details/gtqouriufp.html

[R66] 定时任务
来源：http://dali.shuidangran.top/Article/details/gtrtwldwmh.html

crontab -e;  crontab -l
来源：http://dali.wangdashe.top/Article/details/gtyzjlsbtg.html

[R67] 生成随机十六进制串
来源：http://dali.jinghuilouyu.cn/Article/details/gtqsgbngyt.html

openssl rand -hex 16
来源：http://dali.gzhubu.top/Article/details/gtkjimzwss.html

[R68] 计算文件校验值
来源：http://dali.daria6918.cn/Article/details/gtmthupnpd.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sweek.top/Article/details/gtarlpuhqi.html

[R69] 生成随机密码
来源：http://dali.yvedp.cn/Article/details/gtevmsiqtb.html

head -c 16 /dev/urandom | base64
来源：http://dali.pengpengdd.cyou/Article/details/gtqcenonan.html

[R70] 时间戳与互转
来源：http://dali.feifeiyinyue.top/Article/details/gtxoavgwci.html

date +%s;  date -d @1700000000
来源：http://dali.zhiwuduotai.top/Article/details/gtgfsogzjs.html

[R71] 日期格式化
来源：http://dali.jinghuilouyu.cn/Article/details/gttrgycjoy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xinyue.icu/Article/details/gtzsxcvvlm.html

[R72] 等待端口就绪
来源：http://dali.0kj1m.cn/Article/details/gtxzfmmngq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.cqqwz.cn/Article/details/gtciqjbspb.html

[R73] 分割大日志
来源：http://dali.daxiang520.top/Article/details/gtrgcbckfa.html

split -l 1000 big.log part_
来源：http://dali.shzxlz.cn/Article/details/gtowixzckh.html

[R74] 批量重命名
来源：http://dali.sxryk.cn/Article/details/gthdypfmkl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hongshengwenyu.top/Article/details/gtjsbrqwdn.html

[R75] 导出环境变量
来源：http://dali.birdmap.top/Article/details/gtxwhfvtjg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.quarkkingdee.top/Article/details/gtytnupokx.html

[R76] 使用临时文件
来源：http://dali.yangfankeji.com/Article/details/gtypdjikqr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoiyyntqs.html

[R77] 读取用户输入
来源：http://dali.gogol.net.cn/Article/details/gtvvafswqm.html

read -rp "请输入: " ans
来源：http://dali.jyoumei.cn/Article/details/gtmyvvzjgd.html

[R78] 交互式菜单
来源：http://dali.zdqjudy.top/Article/details/gtzaywjmyy.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.quarkkingdee.top/Article/details/gtgrdmoevz.html

[R79] 解析命令行选项
来源：http://dali.chenzaomai.com/Article/details/gtldgeykud.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhiwuduotai.top/Article/details/gtgspsspau.html

[R80] 查看脚本执行耗时
来源：http://dali.zhixingplan.top/Article/details/gtvolhkbpo.html

time ./run.sh
来源：http://dali.fengsongda.top/Article/details/gthsrdateo.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtfdiayngr.html

S. C / C++ 专题
来源：http://dali.zhiwuduotai.top/Article/details/gtwrfnjgup.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtrmbjzhbu.html

[S01] C：Hello World
来源：http://dali.shzxlz.cn/Article/details/gtbivahqem.html

#include <stdio.h>
来源：http://dali.snrcjt.cn/Article/details/gtbspbweyn.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yj20258888.top/Article/details/gtearsmjkd.html

[S02] C：变量与格式化输出
来源：http://dali.hysaishi.cn/Article/details/gtixgagtsf.html

int a = 10; printf("%d\n", a);
来源：http://dali.c1oappe.top/Article/details/gtcrkiaueh.html

[S03] C：读入整数
来源：http://dali.zhongyouzk.top/Article/details/gtpqhhfuur.html

int x; scanf("%d", &x);
来源：http://dali.yj20258.top/Article/details/gthyumzpep.html

[S04] C：字符串复制
来源：http://dali.jqgufenzy.top/Article/details/gttontxwvv.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.redwolf501.top/Article/details/gtripnsbxj.html

[S05] C：字符串长度
来源：http://dali.nwbrower.top/Article/details/gtiausdoqr.html

strlen(s)
来源：http://dali.pycfn.com/Article/details/gtpwzxeemj.html

[S06] C：字符串比较
来源：http://dali.ybcxt.top/Article/details/gtdgnkncdz.html

strcmp(a, b) == 0
来源：http://dali.guannengcc.top/Article/details/gtunbrogoz.html

[S07] C：数组遍历求和
来源：http://dali.gotoacloud.top/Article/details/gtcfxljqww.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.xinyue.icu/Article/details/gtpydyiurj.html

[S08] C：动态内存分配与释放
来源：http://dali.ppjwa.cn/Article/details/gtnsygptwv.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgzxnnozr.html

[S09] C：结构体定义与初始化
来源：http://dali.pengpengdd.cyou/Article/details/gtkwbbqhbs.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhoulong.xyz/Article/details/gttqlincgc.html

[S10] C：指针与解引用
来源：http://dali.aibaodan.cn/Article/details/gtvfuyarrj.html

int *p = &a;  *p = 5;
来源：http://dali.chenlongwang.top/Article/details/gtinqzylnh.html

[S11] C：逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gtakkxpxtq.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.kuanghao11.cn/Article/details/gtptjlvxft.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.sxryk.cn/Article/details/gtcqpxotpq.html

fclose(f);
来源：http://dali.jiagoushi.top/Article/details/gtcbdanmvz.html

[S12] C：写文件
来源：http://dali.guannengcc.top/Article/details/gtcjcwptdb.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.yvedp.cn/Article/details/gtdwfewrmr.html

[S13] C：宏定义
来源：http://dali.gogol.net.cn/Article/details/gthpvgzwsd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.shangyingyoupin.top/Article/details/gtaewmfnza.html

[S14] C：枚举
来源：http://dali.hysaishi.cn/Article/details/gtvgtlwfof.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.hywenlv.cn/Article/details/gthwcmlygn.html

[S15] C：类型转换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtagmattrl.html

(double) a / b
来源：http://dali.kuanghao11.cn/Article/details/gtagkokumy.html

[S16] C：位操作置位
来源：http://dali.birdmap.top/Article/details/gtkmfqyswd.html

x |= (1 << 3);
来源：http://dali.xziqi.cn/Article/details/gtpybzacnl.html

[S17] C：安全拼接字符串
来源：http://dali.kuanghao11.cn/Article/details/gteyqgjtov.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.haohaochexian.top/Article/details/gtcedqqrau.html

[S18] C：命令行参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnwlcyvia.html

int main(int argc, char **argv)
来源：http://dali.shangyingyoupin.top/Article/details/gtimabbdsb.html

[S19] C：快速排序
来源：http://dali.svipenyu.cn/Article/details/gthdkxovif.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gtspmytnqa.html

[S20] C：二分查找
来源：http://dali.gogol.net.cn/Article/details/gtoejmkhhb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.chenlongwang.top/Article/details/gtclozfbrs.html

[S21] C：字符类别判断
来源：http://dali.yanxiufei.cn/Article/details/gterhjjsyo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.sysykeji.top/Article/details/gtplejvhar.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gtdzozimqn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.meibo888.top/Article/details/gtewrreeck.html

[S23] C：随机数
来源：http://dali.ehwqpu.com/Article/details/gtcvcckvwv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cashguo.top/Article/details/gtcdbbrpno.html

[S24] C：获取本地时间
来源：http://dali.jinqigufen.top/Article/details/gtduqddjll.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zycfv.cn/Article/details/gttetlmaoq.html

[S25] C：内存拷贝
来源：http://dali.sweek.top/Article/details/gtqucnkexh.html

memcpy(dst, src, n);
来源：http://dali.iojbl.cn/Article/details/gterofikdd.html

[S26] C：内存清零
来源：http://dali.yj202588.top/Article/details/gtxsvikona.html

memset(a, 0, sizeof a);
来源：http://dali.vqdsnc.cn/Article/details/gtgfqibnwv.html

[S27] C：定义常量
来源：http://dali.zhixingplan.top/Article/details/gttmvxjcen.html

const double PI = 3.14159;
来源：http://dali.tanke756.top/Article/details/gtzwhwzzze.html

[S28] C：静态变量
来源：http://dali.xylfe.cn/Article/details/gtjusrrjqn.html

static int counter = 0;
来源：http://dali.pengpengdd.cyou/Article/details/gtkawgpwhm.html

[S29] C：变参函数
来源：http://dali.xinyue.icu/Article/details/gtipvzkaaw.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.guannengcc.top/Article/details/gtbdcdmvga.html

[S30] C：头文件保护
来源：http://dali.chenlongwang.top/Article/details/gtpfpaabmo.html

#ifndef X_H
来源：http://dali.wangshuangyany.cn/Article/details/gtkvrcupzs.html

#define X_H
来源：http://dali.smart0.xyz/Article/details/gtvjfdauxi.html

#endif
来源：http://dali.sufxvd.cn/Article/details/gtzbbdgkkz.html

[S31] C++：Hello World
来源：http://dali.ydzc1.top/Article/details/gttteizwqd.html

#include <iostream>
来源：http://dali.zhixingplan.top/Article/details/gtqmztqtwo.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sxryk.cn/Article/details/gtyxgptumu.html

[S32] C++：字符串
来源：http://dali.cqqwz.cn/Article/details/gtqjxikzck.html

std::string s = "hi";  s += "!";
来源：http://dali.hysaishi.cn/Article/details/gtmcwxqeye.html

[S33] C++：vector 增删
来源：http://dali.tanke756.top/Article/details/gtfcwarpoz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.jinghuilouyu.cn/Article/details/gtcerbzabd.html

[S34] C++：遍历 vector
来源：http://dali.hywenlv.cn/Article/details/gtetbedisp.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.yueranfly.top/Article/details/gtnvlhxtiq.html

[S35] C++：map
来源：http://dali.mhx1999.top/Article/details/gtvclblxew.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.nanxinkj.top/Article/details/gtlszjvxbl.html

[S36] C++：unordered_map
来源：http://dali.9152youxi.cn/Article/details/gteqmtyhyv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hywenlv.cn/Article/details/gtsfhbthom.html

[S37] C++：set
来源：http://dali.yangfankeji.com/Article/details/gtzmapclof.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xziqi.cn/Article/details/gttxvrvtjw.html

[S38] C++：排序
来源：http://dali.jinghuilouyu.cn/Article/details/gtehrptqys.html

std::sort(v.begin(), v.end());
来源：http://dali.ehwqpu.com/Article/details/gthrkkymkh.html

[S39] C++：自定义比较器排序
来源：http://dali.fengsongda.top/Article/details/gtmdubatze.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.daxiang520.top/Article/details/gtjwsgoqch.html

[S40] C++：查找元素
来源：http://dali.iojbl.cn/Article/details/gtlxfwwyvz.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.hnxiangtu.top/Article/details/gtmvxrnabw.html

[S41] C++：类与构造函数
来源：http://dali.sweek.top/Article/details/gtjjollgjv.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.gzhubu.top/Article/details/gtugloqvwq.html

[S42] C++：继承与虚函数
来源：http://dali.havefunace.top/Article/details/gtkiffhevi.html

class B : public Base { public: void f() override {} };
来源：http://dali.xuetiantiany.cn/Article/details/gtfoqynhhd.html

[S43] C++：智能指针
来源：http://dali.shanyushiyangtech.top/Article/details/gthqldahcb.html

auto p = std::make_unique<int>(5);
来源：http://dali.hywenlv.cn/Article/details/gttwtadbsd.html

[S44] C++：引用传参
来源：http://dali.smart0.xyz/Article/details/gtfsuepitt.html

void inc(int &x) { ++x; }
来源：http://dali.cashguo.top/Article/details/gtiemdridi.html

[S45] C++：lambda
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyvpthrya.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.zhongyouzk.top/Article/details/gthkwsxgnm.html

[S46] C++：函数模板
来源：http://dali.ehwqpu.com/Article/details/gtsxorgqfl.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jinqigfzy.top/Article/details/gtmujqcoxp.html

[S47] C++：结构化绑定遍历
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcjbwnerp.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ivvv.top/Article/details/gtnjwlzfag.html

[S48] C++：逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gtimttglgm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cashguo.top/Article/details/gtyccnnwyj.html

while (std::getline(in, line)) { }
来源：http://dali.ybcxt.top/Article/details/gtcpzspaef.html

[S49] C++：写文件
来源：http://dali.havefunace.top/Article/details/gtuvcxdrqc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.c1oappe.top/Article/details/gtfqumsgdz.html

[S50] C++：格式化数字
来源：http://dali.shzxlz.cn/Article/details/gtcvbuhddi.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.316326.xyz/Article/details/gtlaaaofek.html

[S51] C++：显式类型转换
来源：http://dali.yongpay.top/Article/details/gtorcdygrd.html

static_cast<double>(a) / b
来源：http://dali.hysaishi.cn/Article/details/gtnfbwstce.html

[S52] C++：const 与 noexcept
来源：http://dali.shanyushiyangtech.top/Article/details/gtrilaacmt.html


<!-- 参考信息 -->