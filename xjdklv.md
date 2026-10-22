代发 wailian999

[Q86] 读取 JSON 字段
来源：http://dali.nanxinkj.top/Article/details/gt2doldpleg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.fzhhl.top/Article/details/gt2yzhufkbn.html

[Q87] JSON 字段做条件
来源：http://dali.ppjwa.cn/Article/details/gt2tqemrcjm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2abfqhgem.html

[Q88] 行转列（条件聚合）
来源：http://dali.daxiang520.top/Article/details/gt2vizunglp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yj202588.top/Article/details/gt2dwqcnxqc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jianghu66.top/Article/details/gt2klasypgw.html

[Q89] 判断表是否存在
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2xzkypgqw.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yanxiufei.cn/Article/details/gt2uxutwlan.html

[Q90] 生成序号列
来源：http://dali.wangdashe.top/Article/details/gt2ejyztjgf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.aizwys.cn/Article/details/gt2jfsexnsf.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gt2eykoxgpz.html

R. Bash 专题
来源：http://dali.chenjidiqi.icu/Article/details/gt2atulxhqf.html

================================================================================
来源：http://dali.ybcxt.top/Article/details/gt2aijshyhp.html

[R01] shebang 与严格模式
来源：http://dali.hywenlv.cn/Article/details/gt2udfqhsbe.html

#!/usr/bin/env bash
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2khyiumre.html

set -euo pipefail
来源：http://dali.iojbl.cn/Article/details/gt2tevnldod.html

[R02] 变量赋值与使用
来源：http://dali.zdqjudy.top/Article/details/gt2qgigpcwt.html

name="Tom"; echo "$name"
来源：http://dali.ppjwa.cn/Article/details/gt2mmyagxnt.html

[R03] 只读变量
来源：http://dali.hongshengwenyu.top/Article/details/gt2hvpyngnm.html

readonly PI=3.14
来源：http://dali.yj20258888.top/Article/details/gt2kpjgnrph.html

[R04] 位置参数
来源：http://dali.gotoacloud.top/Article/details/gt2agdaspic.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shanyushiyangtech.top/Article/details/gt2slsxkbwz.html

[R05] 参数默认值
来源：http://dali.haohaochexian.top/Article/details/gt2qnaxqfug.html

name="${1:-default}"
来源：http://dali.yj202588.top/Article/details/gt2gswrolfz.html

[R06] 判断命令是否存在
来源：http://dali.wangdashe.top/Article/details/gt2vnemcmwa.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.birdmap.top/Article/details/gt2tuaenabw.html

[R07] if 判断文件
来源：http://dali.redwolf501.top/Article/details/gt2vgcegzyw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cucudq.cn/Article/details/gt2dakepuko.html

[R08] 数值比较
来源：http://dali.jiagoushi.top/Article/details/gt2bdwxzxtq.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.c1oappe.top/Article/details/gt2evzfksih.html

[R09] 字符串比较
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zimbjktc.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.0kj1m.cn/Article/details/gt2agrqwdnp.html

[R10] 正则匹配
来源：http://dali.xziqi.cn/Article/details/gt2wlcybunk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xuanzx.com/Article/details/gt2nrhertud.html

[R11] case 多分支
来源：http://dali.yongpay.top/Article/details/gt2jckbqdyk.html

case "$1" in
来源：http://dali.gzhubu.top/Article/details/gt2sagkdddy.html

start) echo "启动" ;;
来源：http://dali.bjfxy.top/Article/details/gt2pbmrabue.html

stop)  echo "停止" ;;
来源：http://dali.yueranfly.top/Article/details/gt2nqvwqqjs.html

*)     echo "未知命令" ;;
来源：http://dali.zhixingplan.top/Article/details/gt2sihnzbnp.html

esac
来源：http://dali.zhixingplan.top/Article/details/gt2uaxqvkry.html

[R12] for 遍历文件
来源：http://dali.snrcjt.cn/Article/details/gt2coyudpqf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.svipenyu.cn/Article/details/gt2qcmgdanm.html

[R13] for 计数循环
来源：http://dali.gotoacloud.top/Article/details/gt2bejampwg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shzxlz.cn/Article/details/gt2sngtzntm.html

[R14] C 风格 for
来源：http://dali.ydzc1.top/Article/details/gt2zyfosnjw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.fzhhl.top/Article/details/gt2nkfxftex.html

[R15] while 逐行读文件
来源：http://dali.nwbrower.top/Article/details/gt2rwhmefhr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.nwbrower.top/Article/details/gt2vhivkogl.html

[R16] until 等待条件
来源：http://dali.chenzaomai.com/Article/details/gt2qvzsyjda.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cashguo.top/Article/details/gt2czbtyibt.html

[R17] 数组定义与取值
来源：http://dali.xylfe.cn/Article/details/gt2rwyefcuq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yuxming.cn/Article/details/gt2fubbzwdt.html

[R18] 遍历数组
来源：http://dali.daria6918.cn/Article/details/gt2kigjwhtr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jianghu66.top/Article/details/gt2ofakechy.html

[R19] 数组长度
来源：http://dali.hywenlv.cn/Article/details/gt2ejsseiec.html

echo "${#arr[@]}"
来源：http://dali.tian-w.cn/Article/details/gt2ovsjehff.html

[R20] 关联数组（字典）
来源：http://dali.hnqzz.top/Article/details/gt2xzwmvyvs.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xylfe.cn/Article/details/gt2dpiaxhml.html

[R21] 字符串长度
来源：http://dali.yuxming.cn/Article/details/gt2xpvmpuph.html

echo "${#s}"
来源：http://dali.tianlin.xyz/Article/details/gt2brrzjxxu.html

[R22] 截取子串
来源：http://dali.yj202588.top/Article/details/gt2gsptrlzc.html

echo "${s:0:5}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uuwvjvtv.html

[R23] 字符串替换
来源：http://dali.guowangkeji.top/Article/details/gt2netvqspj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.meibo888.top/Article/details/gt2xzbrrxxv.html

[R24] 大小写转换
来源：http://dali.jianghu66.top/Article/details/gt2qkgsxhzm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.iojbl.cn/Article/details/gt2tdkejadz.html

[R25] 去后缀 / 去前缀
来源：http://dali.zdqjudy.top/Article/details/gt2jduurxlo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2rmkzxzai.html

[R26] 命令替换
来源：http://dali.haohaochexian.top/Article/details/gt2fxjvmmhc.html

now=$(date +%F); echo "$now"
来源：http://dali.meibo888.top/Article/details/gt2anzncgar.html

[R27] 算术展开
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wvspwgvb.html

echo $((1 + 2 * 3))
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2edxkggic.html

[R28] 浮点运算
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sqitkesw.html

echo "scale=2; 10/3" | bc
来源：http://dali.wangshuangyany.cn/Article/details/gt2wnutkguj.html

[R29] 定义函数
来源：http://dali.pengpengdd.cyou/Article/details/gt2jfztbczf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.fengsongda.top/Article/details/gt2grrlbtvk.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zmgeflnw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yuxming.cn/Article/details/gt2iuejqxrc.html

[R31] 局部变量
来源：http://dali.hammf.cn/Article/details/gt2gfadfmzv.html

f() { local x=1; echo "$x"; }
来源：http://dali.ydzc1.top/Article/details/gt2upwiofqq.html

[R32] 参数个数校验
来源：http://dali.chenlongwang.top/Article/details/gt2xkqfakuv.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jqgfzy.top/Article/details/gt2jiawhpou.html

[R33] 捕获错误并提示行号
来源：http://dali.meibo888.top/Article/details/gt2xoagxsjn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zycfv.cn/Article/details/gt2mfqhbgjd.html

[R34] 退出时清理
来源：http://dali.hnxiangtu.top/Article/details/gt2tldbywtc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258888.top/Article/details/gt2tmpbivyp.html

[R35] 后台执行并等待
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2gwtfpeav.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yuanzhike.top/Article/details/gt2iesrxkwr.html

[R36] 并发执行多个任务
来源：http://dali.jiagoushi.top/Article/details/gt2urqcwjkg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.birdmap.top/Article/details/gt2xejhmkcs.html

[R37] 把输出赋给变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2ocbxadsw.html

files=$(ls -1)
来源：http://dali.yj202588.top/Article/details/gt2sqgkfrue.html

[R38] 管道串联
来源：http://dali.xuanzx.com/Article/details/gt2hivqzdph.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yangfankeji.com/Article/details/gt2ieyfhrxp.html

[R39] 重定向标准输出与错误
来源：http://dali.andypj.xyz/Article/details/gt2dabdwaqz.html

cmd > out.log 2>&1
来源：http://dali.ppjwa.cn/Article/details/gt2dfmyxdkm.html

[R40] 追加写日志
来源：http://dali.xuanzx.com/Article/details/gt2qyysdrbd.html

echo "log" >> out.log
来源：http://dali.316326.xyz/Article/details/gt2xjuhzjxm.html

[R41] 丢弃输出
来源：http://dali.cucudq.cn/Article/details/gt2aqvfywok.html

cmd >/dev/null 2>&1
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2nclbmomd.html

[R42] 输入重定向
来源：http://dali.svipenyu.cn/Article/details/gt2ayzgobza.html

wc -l < a.txt
来源：http://dali.ehwqpu.com/Article/details/gt2lnsxrqvn.html

[R43] 按名字查找文件
来源：http://dali.xuanzx.com/Article/details/gt2eeupbjhd.html

find . -name "*.log" -type f
来源：http://dali.jqgfzy.top/Article/details/gt2cqsykrvo.html

[R44] 按修改时间查找
来源：http://dali.gzhubu.top/Article/details/gt2ogbhnbkt.html

find . -mtime -7 -type f
来源：http://dali.gotoacloud.top/Article/details/gt2rvgjhxyb.html

[R45] 批量删除
来源：http://dali.aibaodan.cn/Article/details/gt2gfosuhan.html

find . -name "*.tmp" -delete
来源：http://dali.jlsjyb.cn/Article/details/gt2dmcgkahl.html

[R46] 递归替换文件内容
来源：http://dali.cdnleiting.top/Article/details/gt2wfjccnks.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yuanzhike.top/Article/details/gt2jxbwiivg.html

[R47] sed 单行替换
来源：http://dali.snrcjt.cn/Article/details/gt2djsgqyyy.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hammf.cn/Article/details/gt2emeeucmw.html

[R48] awk 取指定列
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ybbesfhi.html

awk '{print $1, $3}' a.txt
来源：http://dali.yuxming.cn/Article/details/gt2zoplfudj.html

[R49] awk 带条件
来源：http://dali.kuanghao11.cn/Article/details/gt2wrvnvfei.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.fzhhl.top/Article/details/gt2abehpwkl.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2soalvzjq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ppjwa.cn/Article/details/gt2cvznokal.html

[R51] 排序去重取前几
来源：http://dali.ydzc1.top/Article/details/gt2egnrjumu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yonumen.top/Article/details/gt2xmxxqtst.html

[R52] 统计行数
来源：http://dali.bjfxy.top/Article/details/gt2znocmfra.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2rrloirub.html

[R53] 查看文件头与实时尾
来源：http://dali.cheryme.top/Article/details/gt2uodbqewh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gogol.net.cn/Article/details/gt2dsjugucj.html

[R54] 比较两个文件
来源：http://dali.cqqwz.cn/Article/details/gt2hezbktqg.html

diff a.txt b.txt
来源：http://dali.snrcjt.cn/Article/details/gt2fpaywiwn.html

[R55] 压缩与解压
来源：http://dali.xylfe.cn/Article/details/gt2skmxwldd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhengqikj.top/Article/details/gt2cmxwbyef.html

[R56] 远程拷贝
来源：http://dali.quarkkingdee.top/Article/details/gt2sycxrewy.html

scp file user@host:/path/
来源：http://dali.xinyue.icu/Article/details/gt2nxadngrp.html

[R57] 远程执行命令
来源：http://dali.jinqigfzy.top/Article/details/gt2tskvmcqb.html

ssh user@host 'uptime'
来源：http://dali.gotoacloud.top/Article/details/gt2iqntjkzv.html

[R58] 下载文件
来源：http://dali.cheryme.top/Article/details/gt2necmqnmy.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xziqi.cn/Article/details/gt2npaotykp.html

[R59] 发 POST JSON
来源：http://dali.zycfv.cn/Article/details/gt2cjcksfog.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jlsjyb.cn/Article/details/gt2tkpejxdj.html

[R60] 只看 HTTP 状态码
来源：http://dali.gogol.net.cn/Article/details/gt2cyntmdjq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ydzc1.top/Article/details/gt2hizhzind.html

[R61] 磁盘占用
来源：http://dali.yj20258.top/Article/details/gt2prixzgdv.html

df -h;  du -sh *
来源：http://dali.ivvv.top/Article/details/gt2dgsfamjo.html

[R62] 找最占空间的文件
来源：http://dali.hywenlv.cn/Article/details/gt2zuchaxlx.html

du -ah . | sort -rh | head -10
来源：http://dali.gaohongyu789.top/Article/details/gt2aedolujm.html

[R63] 内存与进程
来源：http://dali.xziqi.cn/Article/details/gt2fbsngdlj.html

free -h;  ps aux | grep nginx
来源：http://dali.cashguo.top/Article/details/gt2kztdxkke.html

[R64] 结束进程
来源：http://dali.bjfxy.top/Article/details/gt2kjyuowvi.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hysaishi.cn/Article/details/gt2broxfgnh.html

[R65] 查看端口占用
来源：http://dali.vqdsnc.cn/Article/details/gt2oowhaizw.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cashguo.top/Article/details/gt2ycmfbxql.html

[R66] 定时任务
来源：http://dali.yvedp.cn/Article/details/gt2kflzxnth.html

crontab -e;  crontab -l
来源：http://dali.cdnleiting.top/Article/details/gt2ilwyucft.html

[R67] 生成随机十六进制串
来源：http://dali.pycfn.com/Article/details/gt2csdnfimu.html

openssl rand -hex 16
来源：http://dali.zhengqikj.top/Article/details/gt2hfojlqip.html

[R68] 计算文件校验值
来源：http://dali.jianghu66.top/Article/details/gt2ncgfaaln.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.meibo888.top/Article/details/gt2tzmmqnmo.html

[R69] 生成随机密码
来源：http://dali.daxiang520.top/Article/details/gt2oankskwe.html

head -c 16 /dev/urandom | base64
来源：http://dali.yvedp.cn/Article/details/gt2itwhbewc.html

[R70] 时间戳与互转
来源：http://dali.zhengqikj.top/Article/details/gt2qzprcuws.html

date +%s;  date -d @1700000000
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lznrheap.html

[R71] 日期格式化
来源：http://dali.316326.xyz/Article/details/gt2tbehvtry.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jianghu66.top/Article/details/gt2ejkczdif.html

[R72] 等待端口就绪
来源：http://dali.zhengqikj.top/Article/details/gt2hadnnvgq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.svipenyu.cn/Article/details/gt2hrhwvkan.html

[R73] 分割大日志
来源：http://dali.gaohongyu789.top/Article/details/gt2faciacot.html

split -l 1000 big.log part_
来源：http://dali.cashguo.top/Article/details/gt2dbguoqrq.html

[R74] 批量重命名
来源：http://dali.zhoulong.xyz/Article/details/gt2txyqikhp.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.nanxuanxn.top/Article/details/gt2flfcsofe.html

[R75] 导出环境变量
来源：http://dali.yangfankeji.com/Article/details/gt2cvtmoeub.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.gaohongyu789.top/Article/details/gt2lcumdhhf.html

[R76] 使用临时文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2hqgsfxoh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuanzhike.top/Article/details/gt2pkusymbx.html

[R77] 读取用户输入
来源：http://dali.quarkkingdee.top/Article/details/gt2qscppsvg.html

read -rp "请输入: " ans
来源：http://dali.hammf.cn/Article/details/gt2akjcxnyb.html

[R78] 交互式菜单
来源：http://dali.fengsongda.top/Article/details/gt2mydfmfyb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.daxiang520.top/Article/details/gt2gxjdabak.html

[R79] 解析命令行选项
来源：http://dali.wangdashe.top/Article/details/gt2gvseplzv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jiagoushi.top/Article/details/gt2woyotuca.html

[R80] 查看脚本执行耗时
来源：http://dali.yj20258.top/Article/details/gt2xkgotnrt.html

time ./run.sh
来源：http://dali.yuanzhike.top/Article/details/gt2oysuhvxf.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2fxvvcjmq.html

S. C / C++ 专题
来源：http://dali.gotoacloud.top/Article/details/gt2odcbwwym.html

================================================================================
来源：http://dali.tianlin.xyz/Article/details/gt2ymceglfq.html

[S01] C：Hello World
来源：http://dali.yueranfly.top/Article/details/gt2dmuvxnol.html

#include <stdio.h>
来源：http://dali.snrcjt.cn/Article/details/gt2rkqcpagj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jhpvxoxv.html

[S02] C：变量与格式化输出
来源：http://dali.yj202588.top/Article/details/gt2wwaicdde.html

int a = 10; printf("%d\n", a);
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gxmqduzt.html

[S03] C：读入整数
来源：http://dali.shangyingyoupin.top/Article/details/gt2briceaap.html

int x; scanf("%d", &x);
来源：http://dali.birdmap.top/Article/details/gt2rwkyjivr.html

[S04] C：字符串复制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wmmxahhf.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhixingplan.top/Article/details/gt2ajgwbtiy.html

[S05] C：字符串长度
来源：http://dali.hysaishi.cn/Article/details/gt2wyzrlemm.html

strlen(s)
来源：http://dali.chenjidiqi.icu/Article/details/gt2xvnkhrld.html

[S06] C：字符串比较
来源：http://dali.chenzaomai.com/Article/details/gt2pbvoshpq.html

strcmp(a, b) == 0
来源：http://dali.yueranfly.top/Article/details/gt2cjjxjdav.html

[S07] C：数组遍历求和
来源：http://dali.kuanghao11.cn/Article/details/gt2rgmgicda.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.hfpthk.cn/Article/details/gt2pkfthqbm.html

[S08] C：动态内存分配与释放
来源：http://dali.feifeiyinyue.top/Article/details/gt2qrxjwmfg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.ybcxt.top/Article/details/gt2tcxlckwf.html

[S09] C：结构体定义与初始化
来源：http://dali.gzhubu.top/Article/details/gt2irimmqzc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zdqjudy.top/Article/details/gt2acsnfumx.html

[S10] C：指针与解引用
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2zgdbswab.html

int *p = &a;  *p = 5;
来源：http://dali.316326.xyz/Article/details/gt2ybtjphbe.html

[S11] C：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gt2ngeftzhi.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.cashguo.top/Article/details/gt2zaaixjxm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.haohaochexian.top/Article/details/gt2fuamymiz.html

fclose(f);
来源：http://dali.yonumen.top/Article/details/gt2aatxpdua.html

[S12] C：写文件
来源：http://dali.ydzc1.top/Article/details/gt2xaupqllz.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.shzxlz.cn/Article/details/gt2dhvkcgck.html

[S13] C：宏定义
来源：http://dali.haohaochexian.top/Article/details/gt2eoysasyt.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ivvv.top/Article/details/gt2sdybqlfo.html

[S14] C：枚举
来源：http://dali.guannengcc.top/Article/details/gt2ivybrdcz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2vcwygbli.html

[S15] C：类型转换
来源：http://dali.zhixingplan.top/Article/details/gt2mzgtvtdm.html

(double) a / b
来源：http://dali.redwolf501.top/Article/details/gt2xhuhzdej.html

[S16] C：位操作置位
来源：http://dali.bjfxy.top/Article/details/gt2uqpwrmge.html

x |= (1 << 3);
来源：http://dali.ydzc1.top/Article/details/gt2tbrbiwqu.html

[S17] C：安全拼接字符串
来源：http://dali.cucudq.cn/Article/details/gt2yhqnqykn.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.yueranfly.top/Article/details/gt2tpynsajp.html

[S18] C：命令行参数
来源：http://dali.meibo888.top/Article/details/gt2cjbenmmc.html

int main(int argc, char **argv)
来源：http://dali.jianghu66.top/Article/details/gt2qowcybhf.html

[S19] C：快速排序
来源：http://dali.aizwys.cn/Article/details/gt2otozuqce.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gt2vdgblwzb.html

[S20] C：二分查找
来源：http://dali.jqgufenzy.top/Article/details/gt2asefoahf.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.yuanzhike.top/Article/details/gt2qzwodhvl.html

[S21] C：字符类别判断
来源：http://dali.hysaishi.cn/Article/details/gt2ybywarjo.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.havefunace.top/Article/details/gt2uftczdea.html

[S22] C：字符串转数字
来源：http://dali.wangshuangyany.cn/Article/details/gt2bbcuyeeh.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.redwolf501.top/Article/details/gt2twtpioqn.html

[S23] C：随机数
来源：http://dali.xylfe.cn/Article/details/gt2ojzscgun.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.birdmap.top/Article/details/gt2wdeoznnl.html

[S24] C：获取本地时间
来源：http://dali.pycfn.com/Article/details/gt2gyidgmce.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.ivvv.top/Article/details/gt2syhkmccb.html

[S25] C：内存拷贝
来源：http://dali.zhengqikj.top/Article/details/gt2mcahcwfv.html

memcpy(dst, src, n);
来源：http://dali.nanxinkj.top/Article/details/gt2wmfydmcg.html

[S26] C：内存清零
来源：http://dali.tanke756.top/Article/details/gt2excshlse.html

memset(a, 0, sizeof a);
来源：http://dali.cashguo.top/Article/details/gt2vgzhtfxa.html

[S27] C：定义常量
来源：http://dali.0kj1m.cn/Article/details/gt2edvbebjh.html

const double PI = 3.14159;
来源：http://dali.svipenyu.cn/Article/details/gt2uzyhokaa.html

[S28] C：静态变量
来源：http://dali.shanyushiyangtech.top/Article/details/gt2sytczwhx.html

static int counter = 0;
来源：http://dali.shangyingyoupin.top/Article/details/gt2hfcehcvw.html

[S29] C：变参函数
来源：http://dali.dianchejie.cn/Article/details/gt2rtastfrk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.316326.xyz/Article/details/gt2ppfibecd.html

[S30] C：头文件保护
来源：http://dali.snrcjt.cn/Article/details/gt2sdbbrmcv.html

#ifndef X_H
来源：http://dali.zhengqikj.top/Article/details/gt2eviwlbya.html

#define X_H
来源：http://dali.nanxuanxn.top/Article/details/gt2sjafkhjz.html

#endif
来源：http://dali.vqdsnc.cn/Article/details/gt2yfibpgxr.html

[S31] C++：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gt2hbpwxhck.html

#include <iostream>
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2zswkepte.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.wangdashe.top/Article/details/gt2gyzcasio.html

[S32] C++：字符串
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rgdqvxkf.html

std::string s = "hi";  s += "!";
来源：http://dali.sufxvd.cn/Article/details/gt2iqzodutf.html

[S33] C++：vector 增删
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ldghztqm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.sufxvd.cn/Article/details/gt2ykbhibde.html

[S34] C++：遍历 vector
来源：http://dali.hnxiangtu.top/Article/details/gt2bflmlwsi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cucudq.cn/Article/details/gt2rcaeapuf.html

[S35] C++：map
来源：http://dali.xylfe.cn/Article/details/gt2mchbzjei.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.tian-w.cn/Article/details/gt2lbmdoiwb.html

[S36] C++：unordered_map
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2czepbnqv.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vpotpiqq.html

[S37] C++：set
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2pvidkams.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.zycfv.cn/Article/details/gt2lifavoix.html

[S38] C++：排序
来源：http://dali.cucudq.cn/Article/details/gt2xqiodlow.html

std::sort(v.begin(), v.end());
来源：http://dali.nwbrower.top/Article/details/gt2ioajyiiw.html

[S39] C++：自定义比较器排序
来源：http://dali.zdqjudy.top/Article/details/gt2fntdhoch.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.shanyushiyangtech.top/Article/details/gt2zxrxbciu.html

[S40] C++：查找元素
来源：http://dali.xuetiantiany.cn/Article/details/gt2oqkrofur.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.smart0.xyz/Article/details/gt2lvunxfci.html

[S41] C++：类与构造函数
来源：http://dali.jianghu66.top/Article/details/gt2gxerkzvo.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.quarkkingdee.top/Article/details/gt2vbygdtbv.html

[S42] C++：继承与虚函数
来源：http://dali.pycfn.com/Article/details/gt2kdyhzblz.html

class B : public Base { public: void f() override {} };
来源：http://dali.daxiang520.top/Article/details/gt2vaveykui.html

[S43] C++：智能指针
来源：http://dali.nanxuanxn.top/Article/details/gt2jtbudfdq.html

auto p = std::make_unique<int>(5);
来源：http://dali.yonumen.top/Article/details/gt2gxtwrvmn.html

[S44] C++：引用传参
来源：http://dali.yj202588.top/Article/details/gt2nwvxzoos.html

void inc(int &x) { ++x; }
来源：http://dali.tian-w.cn/Article/details/gt2xgiytbqi.html

[S45] C++：lambda
来源：http://dali.nanxuanxn.top/Article/details/gt2qzumpwyk.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.guannengcc.top/Article/details/gt2adjhczxb.html

[S46] C++：函数模板
来源：http://dali.guannengcc.top/Article/details/gt2xhufnzdg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.bjfxy.top/Article/details/gt2babjella.html

[S47] C++：结构化绑定遍历
来源：http://dali.cheryme.top/Article/details/gt2nsbxyosi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ivvv.top/Article/details/gt2bjafjiew.html

[S48] C++：逐行读文件
来源：http://dali.shuidangran.top/Article/details/gt2durrtazh.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.cashguo.top/Article/details/gt2pprrmthp.html

while (std::getline(in, line)) { }
来源：http://dali.shuidangran.top/Article/details/gt2sldeywty.html

[S49] C++：写文件
来源：http://dali.sysykeji.top/Article/details/gt2yqqzzpey.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.ppjwa.cn/Article/details/gt2kwngrljp.html

[S50] C++：格式化数字
来源：http://dali.gaohongyu789.top/Article/details/gt2nipjpxdn.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.chenjidiqi.icu/Article/details/gt2frkffidn.html

[S51] C++：显式类型转换
来源：http://dali.jlsjyb.cn/Article/details/gt2tjtcumap.html

static_cast<double>(a) / b
来源：http://dali.fengsongda.top/Article/details/gt2dxhrkvbl.html

[S52] C++：const 与 noexcept
来源：http://dali.yvedp.cn/Article/details/gt2oyhvbnwf.html

int size() const noexcept { return n_; }
来源：http://dali.fzhhl.top/Article/details/gt2yvwkmsgj.html

[S53] C++：移动语义
来源：http://dali.meibo888.top/Article/details/gt2ehaslugl.html

std::vector<int> w = std::move(v);
来源：http://dali.yueranfly.top/Article/details/gt2wuppzwoz.html

[S54] C++：异常处理
来源：http://dali.meibo888.top/Article/details/gt2cgwlfyzz.html

try { throw std::runtime_error("x"); } catch (const std::exception &e) { }
来源：http://dali.sysykeji.top/Article/details/gt2tarcxzow.html

[S55] C++：结构化绑定
来源：http://dali.hnxiangtu.top/Article/details/gt2allmotkk.html

auto [a, b] = std::make_pair(1, 2);
来源：http://dali.guannengcc.top/Article/details/gt2nikexyvm.html

[S56] C++：optional
来源：http://dali.xuanzx.com/Article/details/gt2huevlmva.html


<!-- 参考信息 -->