代发 wailian999

[Q84] 去除首尾空格
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfbavmyma.html

SELECT TRIM(name) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtonpniudk.html

[Q85] 数值取整
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqfdlqfer.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cqqwz.cn/Article/details/gtrxfwohto.html

[Q86] 读取 JSON 字段
来源：http://dali.zdqjudy.top/Article/details/gthjlbtuvu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.dashuyun.cn/Article/details/gtxpxxntux.html

[Q87] JSON 字段做条件
来源：http://dali.jinqigufen.top/Article/details/gtjxqjmuri.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.sysykeji.top/Article/details/gtkxaeekvp.html

[Q88] 行转列（条件聚合）
来源：http://dali.sxryk.cn/Article/details/gtxlvckeql.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.dianchejie.cn/Article/details/gtmpjrpkov.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.daxiang520.top/Article/details/gtziytrrbq.html

[Q89] 判断表是否存在
来源：http://dali.aizwys.cn/Article/details/gtlcyerpkr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.guannengcc.top/Article/details/gtniioqsmb.html

[Q90] 生成序号列
来源：http://dali.tanke756.top/Article/details/gtksbalmyn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tianlin.xyz/Article/details/gtxkzehkex.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtvhwhhisu.html

R. Bash 专题
来源：http://dali.0kj1m.cn/Article/details/gtqbcescbd.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtxusoelik.html

[R01] shebang 与严格模式
来源：http://dali.havefunace.top/Article/details/gtgvqciaqh.html

#!/usr/bin/env bash
来源：http://dali.jlsjyb.cn/Article/details/gtfcbbkzlg.html

set -euo pipefail
来源：http://dali.xuanzx.com/Article/details/gtcuhgmzbd.html

[R02] 变量赋值与使用
来源：http://dali.yvedp.cn/Article/details/gtjwiudoli.html

name="Tom"; echo "$name"
来源：http://dali.andypj.xyz/Article/details/gtiwsxirdc.html

[R03] 只读变量
来源：http://dali.shuidangran.top/Article/details/gtxcimajto.html

readonly PI=3.14
来源：http://dali.pycfn.com/Article/details/gtqpdevioe.html

[R04] 位置参数
来源：http://dali.zycfv.cn/Article/details/gtxnqehnza.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yuxming.cn/Article/details/gtlfjqjgxi.html

[R05] 参数默认值
来源：http://dali.wangshuangyany.cn/Article/details/gtokxdjaic.html

name="${1:-default}"
来源：http://dali.hongshengwenyu.top/Article/details/gtmkswgldw.html

[R06] 判断命令是否存在
来源：http://dali.nanxuanxn.top/Article/details/gtxscjuyiu.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shuidangran.top/Article/details/gtcxcvyvtl.html

[R07] if 判断文件
来源：http://dali.daria6918.cn/Article/details/gtjbkinwyp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gtacslyjwx.html

[R08] 数值比较
来源：http://dali.jinqigufen.top/Article/details/gtapnxdioe.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.birdmap.top/Article/details/gtvvpadldo.html

[R09] 字符串比较
来源：http://dali.pycfn.com/Article/details/gtkitogamb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shangyingyoupin.top/Article/details/gtqbqewydr.html

[R10] 正则匹配
来源：http://dali.yj20258.top/Article/details/gtvfhhelzs.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hfpthk.cn/Article/details/gtfarvpuhn.html

[R11] case 多分支
来源：http://dali.birdmap.top/Article/details/gtsqfwefyb.html

case "$1" in
来源：http://dali.zhoulong.xyz/Article/details/gtdpdvbqwx.html

start) echo "启动" ;;
来源：http://dali.mhx1999.top/Article/details/gtqlyueqrx.html

stop)  echo "停止" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsygitegz.html

*)     echo "未知命令" ;;
来源：http://dali.shuidangran.top/Article/details/gtgdqhdtcq.html

esac
来源：http://dali.vqdsnc.cn/Article/details/gtvnsumomk.html

[R12] for 遍历文件
来源：http://dali.mhx1999.top/Article/details/gtkykmaoya.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yuanzhike.top/Article/details/gtwndqmiwp.html

[R13] for 计数循环
来源：http://dali.jianghu66.top/Article/details/gtsnomsoqp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hysaishi.cn/Article/details/gtnfiokvkd.html

[R14] C 风格 for
来源：http://dali.nanxuanxn.top/Article/details/gtccqqowvc.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtvnvriajt.html

[R15] while 逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gtacghywxf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.c1oappe.top/Article/details/gtkjcudesx.html

[R16] until 等待条件
来源：http://dali.shzxlz.cn/Article/details/gtjnuxggsx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfnxjmtsj.html

[R17] 数组定义与取值
来源：http://dali.daria6918.cn/Article/details/gtulwycvnb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.aibaodan.cn/Article/details/gtsdsfttev.html

[R18] 遍历数组
来源：http://dali.ydzc1.top/Article/details/gtqyqaqgsw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.mhx1999.top/Article/details/gtfkprbcuf.html

[R19] 数组长度
来源：http://dali.guowangkeji.top/Article/details/gtvxawbfbc.html

echo "${#arr[@]}"
来源：http://dali.zdqjudy.top/Article/details/gtqzozrizb.html

[R20] 关联数组（字典）
来源：http://dali.shuidangran.top/Article/details/gtjzkydcmn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.svipenyu.cn/Article/details/gtyoundrpt.html

[R21] 字符串长度
来源：http://dali.snrcjt.cn/Article/details/gtftoruhyy.html

echo "${#s}"
来源：http://dali.yangfankeji.com/Article/details/gtnvvyrvph.html

[R22] 截取子串
来源：http://dali.ivvv.top/Article/details/gtpnrdjgxq.html

echo "${s:0:5}"
来源：http://dali.zhengqikj.top/Article/details/gtrbtmluqd.html

[R23] 字符串替换
来源：http://dali.mhx1999.top/Article/details/gtfsgilzco.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.pengpengdd.cyou/Article/details/gtyklbksec.html

[R24] 大小写转换
来源：http://dali.jlsjyb.cn/Article/details/gtnljznobp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.redwolf501.top/Article/details/gtovqcaedq.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhoulong.xyz/Article/details/gtxcuwighd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yongpay.top/Article/details/gtlkzuzigd.html

[R26] 命令替换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrlkatatb.html

now=$(date +%F); echo "$now"
来源：http://dali.9152youxi.cn/Article/details/gtsurnhzdv.html

[R27] 算术展开
来源：http://dali.zhoulong.xyz/Article/details/gtnnzpowah.html

echo $((1 + 2 * 3))
来源：http://dali.zycfv.cn/Article/details/gtbxhlqtbe.html

[R28] 浮点运算
来源：http://dali.tian-w.cn/Article/details/gtrwcmxrlf.html

echo "scale=2; 10/3" | bc
来源：http://dali.yvedp.cn/Article/details/gtfdbvndzk.html

[R29] 定义函数
来源：http://dali.chenjidiqi.icu/Article/details/gtmzkjklas.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.iojbl.cn/Article/details/gtlqfkgtaq.html

[R30] 函数返回状态码
来源：http://dali.yongpay.top/Article/details/gtbmnrblzn.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.xziqi.cn/Article/details/gtieyxjkis.html

[R31] 局部变量
来源：http://dali.sweek.top/Article/details/gtwqwjojre.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhiwuduotai.top/Article/details/gtqvhxvbsg.html

[R32] 参数个数校验
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuqijuzzo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jlsjyb.cn/Article/details/gtxqooklvw.html

[R33] 捕获错误并提示行号
来源：http://dali.havefunace.top/Article/details/gtdrhqqgey.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.andypj.xyz/Article/details/gtpczjdeoa.html

[R34] 退出时清理
来源：http://dali.fengsongda.top/Article/details/gtzwwiqxig.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.ivvv.top/Article/details/gtszgwyxsw.html

[R35] 后台执行并等待
来源：http://dali.sysykeji.top/Article/details/gtoqnopkkx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.pengpengdd.cyou/Article/details/gtngpsohvv.html

[R36] 并发执行多个任务
来源：http://dali.jinghuilouyu.cn/Article/details/gtdthfrvqo.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjbulpuyc.html

[R37] 把输出赋给变量
来源：http://dali.yanxiufei.cn/Article/details/gtmcuzzevy.html

files=$(ls -1)
来源：http://dali.pycfn.com/Article/details/gtbvzarsvm.html

[R38] 管道串联
来源：http://dali.xinyue.icu/Article/details/gtakblmuxz.html

cat a.txt | grep -i error | wc -l
来源：http://dali.daxiang520.top/Article/details/gtrxithsed.html

[R39] 重定向标准输出与错误
来源：http://dali.smart0.xyz/Article/details/gtlmjopjql.html

cmd > out.log 2>&1
来源：http://dali.bjfxy.top/Article/details/gtfegqarrs.html

[R40] 追加写日志
来源：http://dali.sufxvd.cn/Article/details/gtnlhwyhtu.html

echo "log" >> out.log
来源：http://dali.aizwys.cn/Article/details/gtqxxfshat.html

[R41] 丢弃输出
来源：http://dali.zhiwuduotai.top/Article/details/gtprkrfght.html

cmd >/dev/null 2>&1
来源：http://dali.jinqigfzy.top/Article/details/gtomhykxls.html

[R42] 输入重定向
来源：http://dali.nanxinkj.top/Article/details/gtqllyphyq.html

wc -l < a.txt
来源：http://dali.guowangkeji.top/Article/details/gtzygpuljx.html

[R43] 按名字查找文件
来源：http://dali.shanyushiyangtech.top/Article/details/gthbzpkpxd.html

find . -name "*.log" -type f
来源：http://dali.cheryme.top/Article/details/gtmtuiwrjk.html

[R44] 按修改时间查找
来源：http://dali.hnxiangtu.top/Article/details/gtvhxkebds.html

find . -mtime -7 -type f
来源：http://dali.zhongyouzk.top/Article/details/gtspsgucqe.html

[R45] 批量删除
来源：http://dali.kuanghao11.cn/Article/details/gtgrahroik.html

find . -name "*.tmp" -delete
来源：http://dali.andypj.xyz/Article/details/gtkyvrjqvc.html

[R46] 递归替换文件内容
来源：http://dali.zhixingplan.top/Article/details/gtzdatdmen.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cdnleiting.top/Article/details/gtogjjacqf.html

[R47] sed 单行替换
来源：http://dali.kuanghao11.cn/Article/details/gtzbetzxmw.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.aibaodan.cn/Article/details/gtvjgxqedd.html

[R48] awk 取指定列
来源：http://dali.nanxuanxn.top/Article/details/gtucpndwfv.html

awk '{print $1, $3}' a.txt
来源：http://dali.tianlin.xyz/Article/details/gtibzjcjzw.html

[R49] awk 带条件
来源：http://dali.zhengqikj.top/Article/details/gtqkciotho.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.tian-w.cn/Article/details/gtokecqclo.html

[R50] awk 求和
来源：http://dali.hnxiangtu.top/Article/details/gtaavapzav.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.9152youxi.cn/Article/details/gtxqlxvzlb.html

[R51] 排序去重取前几
来源：http://dali.fengsongda.top/Article/details/gtcsutpiwl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.haohaochexian.top/Article/details/gtxyhowgxg.html

[R52] 统计行数
来源：http://dali.zhixingplan.top/Article/details/gtxoobsuvu.html

wc -l a.txt
来源：http://dali.zhengqikj.top/Article/details/gtdogfjmhq.html

[R53] 查看文件头与实时尾
来源：http://dali.yj20258.top/Article/details/gtyhiifqvn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.pengpengdd.cyou/Article/details/gtkwbflohb.html

[R54] 比较两个文件
来源：http://dali.daxiang520.top/Article/details/gtqudqfsfl.html

diff a.txt b.txt
来源：http://dali.chenzaomai.com/Article/details/gtjyjxuape.html

[R55] 压缩与解压
来源：http://dali.yueranfly.top/Article/details/gtkunmuhcj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvzosqlhf.html

[R56] 远程拷贝
来源：http://dali.feifeiyinyue.top/Article/details/gtwdoddevp.html

scp file user@host:/path/
来源：http://dali.ppjwa.cn/Article/details/gtitdpzoiv.html

[R57] 远程执行命令
来源：http://dali.hammf.cn/Article/details/gtsqhxfqnl.html

ssh user@host 'uptime'
来源：http://dali.fzhhl.top/Article/details/gtizhulafi.html

[R58] 下载文件
来源：http://dali.yuxming.cn/Article/details/gtzvsuignm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yuanzhike.top/Article/details/gtostqjcnp.html

[R59] 发 POST JSON
来源：http://dali.hfpthk.cn/Article/details/gtigqihrdg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zycfv.cn/Article/details/gtrbqqvnsr.html

[R60] 只看 HTTP 状态码
来源：http://dali.shzxlz.cn/Article/details/gtmyldrtlr.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.gogol.net.cn/Article/details/gtekurldyp.html

[R61] 磁盘占用
来源：http://dali.jqgfzy.top/Article/details/gtxlyigpbi.html

df -h;  du -sh *
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrwnqcrxy.html

[R62] 找最占空间的文件
来源：http://dali.zhongyouzk.top/Article/details/gtcgwdxseo.html

du -ah . | sort -rh | head -10
来源：http://dali.sweek.top/Article/details/gttlgeijun.html

[R63] 内存与进程
来源：http://dali.zhengqikj.top/Article/details/gthskszcrm.html

free -h;  ps aux | grep nginx
来源：http://dali.xuetiantiany.cn/Article/details/gtdzoekbki.html

[R64] 结束进程
来源：http://dali.jinqigufen.top/Article/details/gtjjynsqjd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.tanke756.top/Article/details/gtfwizgmnn.html

[R65] 查看端口占用
来源：http://dali.xziqi.cn/Article/details/gtyuzrxmuj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.cashguo.top/Article/details/gttsqrpbxm.html

[R66] 定时任务
来源：http://dali.jinqigfzy.top/Article/details/gtdzwlsuii.html

crontab -e;  crontab -l
来源：http://dali.sweek.top/Article/details/gtiiqcbosc.html

[R67] 生成随机十六进制串
来源：http://dali.nwbrower.top/Article/details/gtbctoscvq.html

openssl rand -hex 16
来源：http://dali.0kj1m.cn/Article/details/gthoitcwvu.html

[R68] 计算文件校验值
来源：http://dali.snrcjt.cn/Article/details/gtahsmjdhs.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.kuanghao11.cn/Article/details/gtvnkjmkmg.html

[R69] 生成随机密码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtygjzicfo.html

head -c 16 /dev/urandom | base64
来源：http://dali.birdmap.top/Article/details/gtexcukign.html

[R70] 时间戳与互转
来源：http://dali.andypj.xyz/Article/details/gtevqywroz.html

date +%s;  date -d @1700000000
来源：http://dali.xziqi.cn/Article/details/gtkybbugya.html

[R71] 日期格式化
来源：http://dali.zhoulong.xyz/Article/details/gtfewbdfjk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.daxiang520.top/Article/details/gttvcndefv.html

[R72] 等待端口就绪
来源：http://dali.xinyue.icu/Article/details/gtpdvtppjv.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.nwbrower.top/Article/details/gtqaztvfiv.html

[R73] 分割大日志
来源：http://dali.tanke756.top/Article/details/gtltwrghhh.html

split -l 1000 big.log part_
来源：http://dali.jianghu66.top/Article/details/gtxhuqzmgt.html

[R74] 批量重命名
来源：http://dali.0kj1m.cn/Article/details/gtorcbfizw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.bjfxy.top/Article/details/gterlkliet.html

[R75] 导出环境变量
来源：http://dali.shzxlz.cn/Article/details/gtkynxqdfq.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfsztyylp.html

[R76] 使用临时文件
来源：http://dali.0kj1m.cn/Article/details/gtwuedmdrk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdutifvgu.html

[R77] 读取用户输入
来源：http://dali.jinqigfzy.top/Article/details/gtjssbywei.html

read -rp "请输入: " ans
来源：http://dali.haohaochexian.top/Article/details/gtlwrtjdcx.html

[R78] 交互式菜单
来源：http://dali.gzhubu.top/Article/details/gtqmtkrsei.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.quarkkingdee.top/Article/details/gtinqmzciu.html

[R79] 解析命令行选项
来源：http://dali.jqgufenzy.top/Article/details/gteobinijh.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.pengpengdd.cyou/Article/details/gtoiwqmkel.html

[R80] 查看脚本执行耗时
来源：http://dali.meibo888.top/Article/details/gtevqdazzk.html

time ./run.sh
来源：http://dali.jinghuilouyu.cn/Article/details/gtdxnvhhhd.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtsxqfqfjv.html

S. C / C++ 专题
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkiylhzsy.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtdqjhyroo.html

[S01] C：Hello World
来源：http://dali.hywenlv.cn/Article/details/gtsybbimrv.html

#include <stdio.h>
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzqtyqsav.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.nanxuanxn.top/Article/details/gtxbwxpwtg.html

[S02] C：变量与格式化输出
来源：http://dali.andypj.xyz/Article/details/gtzqxvjzpu.html

int a = 10; printf("%d\n", a);
来源：http://dali.svipenyu.cn/Article/details/gthlwrtdhl.html

[S03] C：读入整数
来源：http://dali.cqqwz.cn/Article/details/gtoebnzmyb.html

int x; scanf("%d", &x);
来源：http://dali.tian-w.cn/Article/details/gtecqixyiy.html

[S04] C：字符串复制
来源：http://dali.yuanzhike.top/Article/details/gtrugsfdnu.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.svipenyu.cn/Article/details/gtohkajkgw.html

[S05] C：字符串长度
来源：http://dali.zhoulong.xyz/Article/details/gtnruljgdo.html

strlen(s)
来源：http://dali.yonumen.top/Article/details/gtkorblpdn.html

[S06] C：字符串比较
来源：http://dali.hnxiangtu.top/Article/details/gtqgzdhgke.html

strcmp(a, b) == 0
来源：http://dali.jlsjyb.cn/Article/details/gttcdphmvs.html

[S07] C：数组遍历求和
来源：http://dali.ybcxt.top/Article/details/gtnbyqehot.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.shanyushiyangkeji.top/Article/details/gteyeueubr.html

[S08] C：动态内存分配与释放
来源：http://dali.zhongyouzk.top/Article/details/gtahynyjrb.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.kuanghao11.cn/Article/details/gtyeyxtzpu.html

[S09] C：结构体定义与初始化
来源：http://dali.hnqzz.top/Article/details/gthelmwcxe.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.andypj.xyz/Article/details/gtnerpsjkp.html

[S10] C：指针与解引用
来源：http://dali.yonumen.top/Article/details/gtagmffehu.html

int *p = &a;  *p = 5;
来源：http://dali.wangdashe.top/Article/details/gtoeanywsr.html

[S11] C：逐行读文件
来源：http://dali.jqgufenzy.top/Article/details/gtxjujsvoh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zdqjudy.top/Article/details/gtclgknhqn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gogol.net.cn/Article/details/gtsmqzkxac.html

fclose(f);
来源：http://dali.tian-w.cn/Article/details/gtgqyymoid.html

[S12] C：写文件
来源：http://dali.jqgufenzy.top/Article/details/gtgbenmsgn.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.xinyue.icu/Article/details/gtaultrylz.html

[S13] C：宏定义
来源：http://dali.cdnleiting.top/Article/details/gtrbozbmyj.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.tanke756.top/Article/details/gtcrtipabh.html

[S14] C：枚举
来源：http://dali.ivvv.top/Article/details/gtrfnsmfoa.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sweek.top/Article/details/gtcdqjltoj.html

[S15] C：类型转换
来源：http://dali.daria6918.cn/Article/details/gttudomehr.html

(double) a / b
来源：http://dali.nanxinkj.top/Article/details/gtxcakrxse.html

[S16] C：位操作置位
来源：http://dali.havefunace.top/Article/details/gtyxzjliny.html

x |= (1 << 3);
来源：http://dali.hongshengwenyu.top/Article/details/gtynufdiqx.html

[S17] C：安全拼接字符串
来源：http://dali.nanxinkj.top/Article/details/gtyqwsggzh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.xylfe.cn/Article/details/gttiqenigo.html

[S18] C：命令行参数
来源：http://dali.jqgufenzy.top/Article/details/gtmscgwili.html

int main(int argc, char **argv)
来源：http://dali.zdqjudy.top/Article/details/gtzekelaog.html

[S19] C：快速排序
来源：http://dali.zhoulong.xyz/Article/details/gteoipiqml.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.jqgufenzy.top/Article/details/gtxwyozaee.html

[S20] C：二分查找
来源：http://dali.svipenyu.cn/Article/details/gttywjkais.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.snrcjt.cn/Article/details/gtdqzxkkwy.html

[S21] C：字符类别判断
来源：http://dali.guowangkeji.top/Article/details/gtubdvlnnf.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.shanyushiyangtech.top/Article/details/gtegkucupi.html

[S22] C：字符串转数字
来源：http://dali.zhixingplan.top/Article/details/gtagddkdyg.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.tanke756.top/Article/details/gttumtvrhf.html

[S23] C：随机数
来源：http://dali.chenjidiqi.icu/Article/details/gtkwjartsd.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.meibo888.top/Article/details/gtzlncwejf.html

[S24] C：获取本地时间
来源：http://dali.jinqigfzy.top/Article/details/gtumnimels.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.hysaishi.cn/Article/details/gtduigtojb.html

[S25] C：内存拷贝
来源：http://dali.cheryme.top/Article/details/gtzzbjzntj.html

memcpy(dst, src, n);
来源：http://dali.sxryk.cn/Article/details/gtlmepxwsz.html

[S26] C：内存清零
来源：http://dali.pycfn.com/Article/details/gtobiwyuvi.html

memset(a, 0, sizeof a);
来源：http://dali.guannengcc.top/Article/details/gtqfhdozns.html

[S27] C：定义常量
来源：http://dali.shanyushiyangtech.top/Article/details/gtmjmgnjvl.html

const double PI = 3.14159;
来源：http://dali.yj20258.top/Article/details/gtwxrmtoya.html

[S28] C：静态变量
来源：http://dali.dianchejie.cn/Article/details/gtuvbiggza.html

static int counter = 0;
来源：http://dali.wangdashe.top/Article/details/gtobzcqlho.html

[S29] C：变参函数
来源：http://dali.ybcxt.top/Article/details/gtuauvlils.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.birdmap.top/Article/details/gtlxhpmkkt.html

[S30] C：头文件保护
来源：http://dali.birdmap.top/Article/details/gtfdhpljfw.html

#ifndef X_H
来源：http://dali.hnqzz.top/Article/details/gtivszzcim.html

#define X_H
来源：http://dali.zhongyouzk.top/Article/details/gtvopgssga.html

#endif
来源：http://dali.chenlongwang.top/Article/details/gtqlqetpwk.html

[S31] C++：Hello World
来源：http://dali.jianghu66.top/Article/details/gtbflfrolu.html

#include <iostream>
来源：http://dali.dashuyun.cn/Article/details/gtubzdyhox.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhongyouzk.top/Article/details/gtdknylilm.html

[S32] C++：字符串
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmflyoxbq.html

std::string s = "hi";  s += "!";
来源：http://dali.pengpengdd.cyou/Article/details/gtxlohmrti.html

[S33] C++：vector 增删
来源：http://dali.haohaochexian.top/Article/details/gtywxioqjz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gtemthiqxr.html

[S34] C++：遍历 vector
来源：http://dali.jqgfzy.top/Article/details/gtunsxcski.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.daxiang520.top/Article/details/gthbngqitd.html

[S35] C++：map
来源：http://dali.feifeiyinyue.top/Article/details/gtqgrseksj.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtgfpdbjgo.html

[S36] C++：unordered_map
来源：http://dali.sufxvd.cn/Article/details/gtsbdcjrir.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.hammf.cn/Article/details/gtpnvtltrl.html

[S37] C++：set
来源：http://dali.jinqigfzy.top/Article/details/gtgcvgdafm.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.sxryk.cn/Article/details/gtddeorenl.html

[S38] C++：排序
来源：http://dali.jiagoushi.top/Article/details/gtsletpjxh.html

std::sort(v.begin(), v.end());
来源：http://dali.yj202588.top/Article/details/gtgtaggvpa.html

[S39] C++：自定义比较器排序
来源：http://dali.0kj1m.cn/Article/details/gtlchismry.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.xuanzx.com/Article/details/gtmndbuuxz.html

[S40] C++：查找元素
来源：http://dali.jiagoushi.top/Article/details/gtdjndtrnr.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.cashguo.top/Article/details/gtokfrtrtf.html

[S41] C++：类与构造函数
来源：http://dali.zhijiandao.cn/Article/details/gtrnavfegj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.vqdsnc.cn/Article/details/gtphcdkuxq.html

[S42] C++：继承与虚函数
来源：http://dali.kuanghao11.cn/Article/details/gtkgvqsora.html

class B : public Base { public: void f() override {} };
来源：http://dali.yvedp.cn/Article/details/gtcyoxczcp.html

[S43] C++：智能指针
来源：http://dali.smart0.xyz/Article/details/gtopaygjlc.html

auto p = std::make_unique<int>(5);
来源：http://dali.gaohongyu789.top/Article/details/gttpmfnbln.html

[S44] C++：引用传参
来源：http://dali.yanxiufei.cn/Article/details/gtwmxbslqt.html

void inc(int &x) { ++x; }
来源：http://dali.pycfn.com/Article/details/gtxwcbcplz.html

[S45] C++：lambda
来源：http://dali.yonumen.top/Article/details/gtgassfrlu.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.tanke756.top/Article/details/gtdjjzrury.html

[S46] C++：函数模板
来源：http://dali.yueranfly.top/Article/details/gtvrnzdyac.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.jqgufenzy.top/Article/details/gtjuazkbvw.html

[S47] C++：结构化绑定遍历
来源：http://dali.cdnleiting.top/Article/details/gtzqfrkiva.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.sufxvd.cn/Article/details/gtrcesadfb.html

[S48] C++：逐行读文件
来源：http://dali.gaohongyu789.top/Article/details/gtcgjfaapm.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.wangdashe.top/Article/details/gtrkmxvszc.html

while (std::getline(in, line)) { }
来源：http://dali.pengpengdd.cyou/Article/details/gtakrwkhqu.html

[S49] C++：写文件
来源：http://dali.daria6918.cn/Article/details/gtlmxlsrmo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.hnxiangtu.top/Article/details/gtiphlpmyh.html

[S50] C++：格式化数字
来源：http://dali.shanyushiyangtech.top/Article/details/gtrwtdsioj.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.jinqigufen.top/Article/details/gtrxpikceg.html

[S51] C++：显式类型转换
来源：http://dali.hammf.cn/Article/details/gtbuktrkpl.html

static_cast<double>(a) / b
来源：http://dali.c1oappe.top/Article/details/gtwzisvebl.html

[S52] C++：const 与 noexcept
来源：http://dali.tanke756.top/Article/details/gtwirbhhcu.html

int size() const noexcept { return n_; }
来源：http://dali.zhijiandao.cn/Article/details/gtxpukkyoc.html

[S53] C++：移动语义
来源：http://dali.gzhubu.top/Article/details/gtpsmqcadr.html

std::vector<int> w = std::move(v);
来源：http://dali.zycfv.cn/Article/details/gtbmyqtsez.html

[S54] C++：异常处理
来源：http://dali.quarkkingdee.top/Article/details/gtiqmmwyex.html


<!-- 参考信息 -->