代发 wailian999

[Q82] 字符长度与字节长度
来源：http://dali.zhengqikj.top/Article/details/gtfrggcwle.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtsbkogxbl.html

[Q83] 大小写转换
来源：http://dali.xinyue.icu/Article/details/gtaefuxkpl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtdyhpgzbz.html

[Q84] 去除首尾空格
来源：http://dali.hammf.cn/Article/details/gtthrygwmi.html

SELECT TRIM(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gtshhifvld.html

[Q85] 数值取整
来源：http://dali.svipenyu.cn/Article/details/gtogvdrcpz.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.dianchejie.cn/Article/details/gtvptpsnod.html

[Q86] 读取 JSON 字段
来源：http://dali.guannengcc.top/Article/details/gtckkbarzi.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jqgfzy.top/Article/details/gtuxazwklz.html

[Q87] JSON 字段做条件
来源：http://dali.redwolf501.top/Article/details/gtgjkevlmd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.guannengcc.top/Article/details/gtyorsbvod.html

[Q88] 行转列（条件聚合）
来源：http://dali.pengpengdd.cyou/Article/details/gtikkeqyxv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsouxccsa.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yongpay.top/Article/details/gtjmcmidvq.html

[Q89] 判断表是否存在
来源：http://dali.zhiwuduotai.top/Article/details/gtwzvpmbor.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.aizwys.cn/Article/details/gtafqhitbb.html

[Q90] 生成序号列
来源：http://dali.ywan-chungtsiang.top/Article/details/gthmavhyjh.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yonumen.top/Article/details/gtpehaiatt.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtveipzstl.html

R. Bash 专题
来源：http://dali.yuxming.cn/Article/details/gtopdudjer.html

================================================================================
来源：http://dali.mhx1999.top/Article/details/gtzblnpmoz.html

[R01] shebang 与严格模式
来源：http://dali.c1oappe.top/Article/details/gtiarxygov.html

#!/usr/bin/env bash
来源：http://dali.kuanghao11.cn/Article/details/gtvwplfjfh.html

set -euo pipefail
来源：http://dali.nanxinkj.top/Article/details/gtlliptxbf.html

[R02] 变量赋值与使用
来源：http://dali.haohaochexian.top/Article/details/gtndltszet.html

name="Tom"; echo "$name"
来源：http://dali.yangfankeji.com/Article/details/gtddcdwlaz.html

[R03] 只读变量
来源：http://dali.jyoumei.cn/Article/details/gtlfzzqfgd.html

readonly PI=3.14
来源：http://dali.jianghu66.top/Article/details/gtgtdvvukt.html

[R04] 位置参数
来源：http://dali.zhiwuduotai.top/Article/details/gtzzdsgnes.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.andypj.xyz/Article/details/gtmhptnqvj.html

[R05] 参数默认值
来源：http://dali.shuidangran.top/Article/details/gtxfpfjpmp.html

name="${1:-default}"
来源：http://dali.snrcjt.cn/Article/details/gtdryueiql.html

[R06] 判断命令是否存在
来源：http://dali.zhixingplan.top/Article/details/gtxrfhlafe.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.9152youxi.cn/Article/details/gtozrbxmsv.html

[R07] if 判断文件
来源：http://dali.cashguo.top/Article/details/gthdbxdjnh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.svipenyu.cn/Article/details/gtqlyvsiov.html

[R08] 数值比较
来源：http://dali.c1oappe.top/Article/details/gtvjpznvkb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.pycfn.com/Article/details/gtcuvcuytz.html

[R09] 字符串比较
来源：http://dali.andypj.xyz/Article/details/gtvhxwiufx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.guannengcc.top/Article/details/gtjebmczme.html

[R10] 正则匹配
来源：http://dali.nanxinkj.top/Article/details/gtuwnkwjaa.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yj20258888.top/Article/details/gtdhyupksv.html

[R11] case 多分支
来源：http://dali.shanyushiyangtech.top/Article/details/gtexjzmyfp.html

case "$1" in
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzvrwmxmb.html

start) echo "启动" ;;
来源：http://dali.ydzc1.top/Article/details/gtfjjqjozq.html

stop)  echo "停止" ;;
来源：http://dali.ehwqpu.com/Article/details/gtmynzujom.html

*)     echo "未知命令" ;;
来源：http://dali.dianchejie.cn/Article/details/gtnwcvlqnf.html

esac
来源：http://dali.birdmap.top/Article/details/gtmluodsqi.html

[R12] for 遍历文件
来源：http://dali.ppjwa.cn/Article/details/gtorktuihm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.snrcjt.cn/Article/details/gtmsixjuaw.html

[R13] for 计数循环
来源：http://dali.xinyue.icu/Article/details/gtuxrlirem.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhengqikj.top/Article/details/gtqobdszdp.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gtsheowhal.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.mhx1999.top/Article/details/gtzcjhesln.html

[R15] while 逐行读文件
来源：http://dali.smart0.xyz/Article/details/gtkeetxode.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtsuxxemho.html

[R16] until 等待条件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtobydjffz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.nanxinkj.top/Article/details/gtknfadriq.html

[R17] 数组定义与取值
来源：http://dali.9152youxi.cn/Article/details/gtufwrmknl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.gotoacloud.top/Article/details/gtxhhxtrab.html

[R18] 遍历数组
来源：http://dali.gaohongyu789.top/Article/details/gtqeqdutap.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sysykeji.top/Article/details/gtktxqxqxn.html

[R19] 数组长度
来源：http://dali.cucudq.cn/Article/details/gtcueeigoy.html

echo "${#arr[@]}"
来源：http://dali.zhixingplan.top/Article/details/gtibzcttti.html

[R20] 关联数组（字典）
来源：http://dali.yonumen.top/Article/details/gtagsheoeg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gttqwizhdw.html

[R21] 字符串长度
来源：http://dali.xylfe.cn/Article/details/gtgunquaol.html

echo "${#s}"
来源：http://dali.wangshuangyany.cn/Article/details/gtygkteayk.html

[R22] 截取子串
来源：http://dali.fzhhl.top/Article/details/gtpideaxxp.html

echo "${s:0:5}"
来源：http://dali.yonumen.top/Article/details/gtviefzyjv.html

[R23] 字符串替换
来源：http://dali.gaohongyu789.top/Article/details/gtlsnxhdcv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cdnleiting.top/Article/details/gtlbfwlrqj.html

[R24] 大小写转换
来源：http://dali.zhongyouzk.top/Article/details/gtmvtfawvz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hnqzz.top/Article/details/gtecucqqrl.html

[R25] 去后缀 / 去前缀
来源：http://dali.gotoacloud.top/Article/details/gtnojxubrr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yvedp.cn/Article/details/gtbdyzasnz.html

[R26] 命令替换
来源：http://dali.wangdashe.top/Article/details/gtfzzfreqk.html

now=$(date +%F); echo "$now"
来源：http://dali.shzxlz.cn/Article/details/gttufhvpgh.html

[R27] 算术展开
来源：http://dali.gotoacloud.top/Article/details/gtzcwbbpht.html

echo $((1 + 2 * 3))
来源：http://dali.pengpengdd.cyou/Article/details/gthpxnzkdg.html

[R28] 浮点运算
来源：http://dali.zycfv.cn/Article/details/gtrbeetkvo.html

echo "scale=2; 10/3" | bc
来源：http://dali.quarkkingdee.top/Article/details/gtglasjzvs.html

[R29] 定义函数
来源：http://dali.aibaodan.cn/Article/details/gttgsdpttf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhengqikj.top/Article/details/gtlywujvkt.html

[R30] 函数返回状态码
来源：http://dali.jinqigufen.top/Article/details/gtmhgtfdru.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cashguo.top/Article/details/gtugvljksa.html

[R31] 局部变量
来源：http://dali.chenlongwang.top/Article/details/gtjkyqqcgw.html

f() { local x=1; echo "$x"; }
来源：http://dali.andypj.xyz/Article/details/gtbvitpxfc.html

[R32] 参数个数校验
来源：http://dali.jqgufenzy.top/Article/details/gtjpelydvb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.tanke756.top/Article/details/gtpoqkcjic.html

[R33] 捕获错误并提示行号
来源：http://dali.ydzc1.top/Article/details/gtsacamuev.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hongshengwenyu.top/Article/details/gtmpbtxpkw.html

[R34] 退出时清理
来源：http://dali.0kj1m.cn/Article/details/gtyzpdvktj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shanyushiyangtech.top/Article/details/gtrmqjiczi.html

[R35] 后台执行并等待
来源：http://dali.sufxvd.cn/Article/details/gttbwyypon.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yvedp.cn/Article/details/gtllsmxotq.html

[R36] 并发执行多个任务
来源：http://dali.daria6918.cn/Article/details/gtgvsdjdwb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.sxryk.cn/Article/details/gtogbzirmf.html

[R37] 把输出赋给变量
来源：http://dali.chenzaomai.com/Article/details/gtqqffzgbg.html

files=$(ls -1)
来源：http://dali.tanke756.top/Article/details/gtzvlitnpt.html

[R38] 管道串联
来源：http://dali.gogol.net.cn/Article/details/gthfgvcbfp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbqbcoqxr.html

[R39] 重定向标准输出与错误
来源：http://dali.wangdashe.top/Article/details/gtgajuuzlz.html

cmd > out.log 2>&1
来源：http://dali.kuanghao11.cn/Article/details/gtiqewceij.html

[R40] 追加写日志
来源：http://dali.zhoulong.xyz/Article/details/gttiutynpi.html

echo "log" >> out.log
来源：http://dali.guannengcc.top/Article/details/gtduogipxi.html

[R41] 丢弃输出
来源：http://dali.gzhubu.top/Article/details/gtkfceqogs.html

cmd >/dev/null 2>&1
来源：http://dali.jinghuilouyu.cn/Article/details/gtdghunhnb.html

[R42] 输入重定向
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrydurvtz.html

wc -l < a.txt
来源：http://dali.cucudq.cn/Article/details/gttjjvhiou.html

[R43] 按名字查找文件
来源：http://dali.zdqjudy.top/Article/details/gtpljzgzjr.html

find . -name "*.log" -type f
来源：http://dali.9152youxi.cn/Article/details/gtaaihdzmj.html

[R44] 按修改时间查找
来源：http://dali.andypj.xyz/Article/details/gtqebjgnam.html

find . -mtime -7 -type f
来源：http://dali.sysykeji.top/Article/details/gtgkfcrtjs.html

[R45] 批量删除
来源：http://dali.guannengcc.top/Article/details/gtanptixjr.html

find . -name "*.tmp" -delete
来源：http://dali.mhx1999.top/Article/details/gtursfmaqc.html

[R46] 递归替换文件内容
来源：http://dali.daria6918.cn/Article/details/gtzbpsbgre.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hnqzz.top/Article/details/gtlrofgeme.html

[R47] sed 单行替换
来源：http://dali.yonumen.top/Article/details/gtnmlboivp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jiagoushi.top/Article/details/gtostjijuy.html

[R48] awk 取指定列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbwortnrb.html

awk '{print $1, $3}' a.txt
来源：http://dali.cqqwz.cn/Article/details/gtkyuhlhdh.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gthhrgsszg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.daxiang520.top/Article/details/gtwlceuyon.html

[R50] awk 求和
来源：http://dali.gogol.net.cn/Article/details/gtslafqymt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xuanzx.com/Article/details/gtmgidqjoi.html

[R51] 排序去重取前几
来源：http://dali.iojbl.cn/Article/details/gttscazyvs.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.meibo888.top/Article/details/gtkfvjrqeh.html

[R52] 统计行数
来源：http://dali.jqgfzy.top/Article/details/gtqummlplc.html

wc -l a.txt
来源：http://dali.guowangkeji.top/Article/details/gtjpkwbgib.html

[R53] 查看文件头与实时尾
来源：http://dali.feifeiyinyue.top/Article/details/gtlcihzmyv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ehwqpu.com/Article/details/gtolchyude.html

[R54] 比较两个文件
来源：http://dali.tianlin.xyz/Article/details/gtphcyisvq.html

diff a.txt b.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtmzqjujid.html

[R55] 压缩与解压
来源：http://dali.kuanghao11.cn/Article/details/gtroaiziot.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gaohongyu789.top/Article/details/gtoriiweml.html

[R56] 远程拷贝
来源：http://dali.yj20258888.top/Article/details/gtygobqivl.html

scp file user@host:/path/
来源：http://dali.cqqwz.cn/Article/details/gtjgsvtrxm.html

[R57] 远程执行命令
来源：http://dali.yonumen.top/Article/details/gtvtrxkcwi.html

ssh user@host 'uptime'
来源：http://dali.hnqzz.top/Article/details/gtthbpenks.html

[R58] 下载文件
来源：http://dali.yanxiufei.cn/Article/details/gtblxezdmd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.quarkkingdee.top/Article/details/gtftjytisa.html

[R59] 发 POST JSON
来源：http://dali.sxryk.cn/Article/details/gterutdcpu.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gogol.net.cn/Article/details/gteoksvloy.html

[R60] 只看 HTTP 状态码
来源：http://dali.tanke756.top/Article/details/gtoreisaxt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hnqzz.top/Article/details/gthfzrupoj.html

[R61] 磁盘占用
来源：http://dali.meibo888.top/Article/details/gtainlglph.html

df -h;  du -sh *
来源：http://dali.tian-w.cn/Article/details/gteewunehd.html

[R62] 找最占空间的文件
来源：http://dali.ppjwa.cn/Article/details/gtgqqigrxp.html

du -ah . | sort -rh | head -10
来源：http://dali.chenlongwang.top/Article/details/gtnutbquic.html

[R63] 内存与进程
来源：http://dali.fengsongda.top/Article/details/gtinorgeir.html

free -h;  ps aux | grep nginx
来源：http://dali.jinghuilouyu.cn/Article/details/gtpodjhcso.html

[R64] 结束进程
来源：http://dali.ivvv.top/Article/details/gtjpxznqcn.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cheryme.top/Article/details/gtffvmxkqp.html

[R65] 查看端口占用
来源：http://dali.aibaodan.cn/Article/details/gtgryimxwe.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.iojbl.cn/Article/details/gtmuthvvbq.html

[R66] 定时任务
来源：http://dali.zhongyouzk.top/Article/details/gtrqxenfio.html

crontab -e;  crontab -l
来源：http://dali.cucudq.cn/Article/details/gtqmliuqnt.html

[R67] 生成随机十六进制串
来源：http://dali.sysykeji.top/Article/details/gtndevsrjf.html

openssl rand -hex 16
来源：http://dali.cashguo.top/Article/details/gtunyjtobu.html

[R68] 计算文件校验值
来源：http://dali.nanxinkj.top/Article/details/gtvmkhxeyj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtimfumsgf.html

[R69] 生成随机密码
来源：http://dali.9152youxi.cn/Article/details/gtkpxwnxhv.html

head -c 16 /dev/urandom | base64
来源：http://dali.birdmap.top/Article/details/gtkkzqkvba.html

[R70] 时间戳与互转
来源：http://dali.316326.xyz/Article/details/gtljbdhkvb.html

date +%s;  date -d @1700000000
来源：http://dali.yongpay.top/Article/details/gtognkallo.html

[R71] 日期格式化
来源：http://dali.cucudq.cn/Article/details/gtpbrvqiti.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhoulong.xyz/Article/details/gtbhwmfslj.html

[R72] 等待端口就绪
来源：http://dali.ivvv.top/Article/details/gtuhdijinu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj202588.top/Article/details/gtfeghjdaf.html

[R73] 分割大日志
来源：http://dali.yuanzhike.top/Article/details/gtssbwobhc.html

split -l 1000 big.log part_
来源：http://dali.nanxinkj.top/Article/details/gtksdrmcsv.html

[R74] 批量重命名
来源：http://dali.ydzc1.top/Article/details/gtjrghzhre.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zdqjudy.top/Article/details/gtxyljlnaq.html

[R75] 导出环境变量
来源：http://dali.redwolf501.top/Article/details/gtlvfngpor.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hfpthk.cn/Article/details/gtmmouiqus.html

[R76] 使用临时文件
来源：http://dali.andypj.xyz/Article/details/gttpjhecfk.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shuidangran.top/Article/details/gtqawinhfv.html

[R77] 读取用户输入
来源：http://dali.sweek.top/Article/details/gtebrbxhjk.html

read -rp "请输入: " ans
来源：http://dali.jlsjyb.cn/Article/details/gtytyrfooh.html

[R78] 交互式菜单
来源：http://dali.gaohongyu789.top/Article/details/gtwhusdjdx.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ppjwa.cn/Article/details/gtmbsmwalr.html

[R79] 解析命令行选项
来源：http://dali.zycfv.cn/Article/details/gtxaazfeuv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.316326.xyz/Article/details/gtszwwfvcr.html

[R80] 查看脚本执行耗时
来源：http://dali.zhixingplan.top/Article/details/gtutmuydsi.html

time ./run.sh
来源：http://dali.kuanghao11.cn/Article/details/gtwjvlnlxx.html

================================================================================
来源：http://dali.jinghuilouyu.cn/Article/details/gtrznpxzrm.html

S. C / C++ 专题
来源：http://dali.havefunace.top/Article/details/gtoapvlwmk.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtbihsdyoz.html

[S01] C：Hello World
来源：http://dali.yongpay.top/Article/details/gtbhwnblgn.html

#include <stdio.h>
来源：http://dali.0kj1m.cn/Article/details/gtzwltekvc.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.snrcjt.cn/Article/details/gtjladuefu.html

[S02] C：变量与格式化输出
来源：http://dali.yj20258.top/Article/details/gtopdwfsuy.html

int a = 10; printf("%d\n", a);
来源：http://dali.ybcxt.top/Article/details/gtcfqnntag.html

[S03] C：读入整数
来源：http://dali.pycfn.com/Article/details/gtahdifxwz.html

int x; scanf("%d", &x);
来源：http://dali.316326.xyz/Article/details/gtsnbhlnwz.html

[S04] C：字符串复制
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdahxeuao.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.fengsongda.top/Article/details/gtohumdopr.html

[S05] C：字符串长度
来源：http://dali.pycfn.com/Article/details/gtdhsxsvni.html

strlen(s)
来源：http://dali.xuetiantiany.cn/Article/details/gtictmuwtb.html

[S06] C：字符串比较
来源：http://dali.nanxinkj.top/Article/details/gtbsqghksf.html

strcmp(a, b) == 0
来源：http://dali.ybcxt.top/Article/details/gtahsvuxwb.html

[S07] C：数组遍历求和
来源：http://dali.fzhhl.top/Article/details/gtajeepric.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.vqdsnc.cn/Article/details/gtdduvcsnd.html

[S08] C：动态内存分配与释放
来源：http://dali.zhoulong.xyz/Article/details/gtudynycbe.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jyoumei.cn/Article/details/gtzwngnoyj.html

[S09] C：结构体定义与初始化
来源：http://dali.yonumen.top/Article/details/gtvmdakvch.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.hnqzz.top/Article/details/gtmxawumvp.html

[S10] C：指针与解引用
来源：http://dali.fzhhl.top/Article/details/gtaslerdnm.html

int *p = &a;  *p = 5;
来源：http://dali.guannengcc.top/Article/details/gtrfmzopqu.html

[S11] C：逐行读文件
来源：http://dali.tanke756.top/Article/details/gtbjryhxhy.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinghuilouyu.cn/Article/details/gtrqplnfvl.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.gzhubu.top/Article/details/gtsfwdiicx.html

fclose(f);
来源：http://dali.cashguo.top/Article/details/gtmkrxovfz.html

[S12] C：写文件
来源：http://dali.aibaodan.cn/Article/details/gtlbqsfixo.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.bjfxy.top/Article/details/gtuokvzvud.html

[S13] C：宏定义
来源：http://dali.quarkkingdee.top/Article/details/gtuojmrpqd.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.aibaodan.cn/Article/details/gtmppzkard.html

[S14] C：枚举
来源：http://dali.c1oappe.top/Article/details/gtmfrxecoi.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.vqdsnc.cn/Article/details/gtcidrckbq.html

[S15] C：类型转换
来源：http://dali.feifeiyinyue.top/Article/details/gtsuyvzuij.html

(double) a / b
来源：http://dali.ivvv.top/Article/details/gtouxphblq.html

[S16] C：位操作置位
来源：http://dali.dashuyun.cn/Article/details/gtwzcdawod.html

x |= (1 << 3);
来源：http://dali.snrcjt.cn/Article/details/gtkmtqczpp.html

[S17] C：安全拼接字符串
来源：http://dali.sweek.top/Article/details/gtuiyuovgh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.316326.xyz/Article/details/gtcsslegtz.html

[S18] C：命令行参数
来源：http://dali.xziqi.cn/Article/details/gtvcsrkmcy.html

int main(int argc, char **argv)
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvbykjxdw.html

[S19] C：快速排序
来源：http://dali.cqqwz.cn/Article/details/gttnuhtyco.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hywenlv.cn/Article/details/gtijleapns.html

[S20] C：二分查找
来源：http://dali.xuanzx.com/Article/details/gtjcumwhph.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.dashuyun.cn/Article/details/gtgihwfodi.html

[S21] C：字符类别判断
来源：http://dali.aibaodan.cn/Article/details/gtqqkxbxsm.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhixingplan.top/Article/details/gtbitvokon.html

[S22] C：字符串转数字
来源：http://dali.kuanghao11.cn/Article/details/gtiwulrliv.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.snrcjt.cn/Article/details/gtqworousa.html

[S23] C：随机数
来源：http://dali.zycfv.cn/Article/details/gttjhdehbc.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yvedp.cn/Article/details/gtshwsmbdl.html

[S24] C：获取本地时间
来源：http://dali.hongshengwenyu.top/Article/details/gtftvfwumn.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.tian-w.cn/Article/details/gtqktivmsz.html

[S25] C：内存拷贝
来源：http://dali.yj20258.top/Article/details/gtidaaovfb.html

memcpy(dst, src, n);
来源：http://dali.meibo888.top/Article/details/gtmdevlyaq.html

[S26] C：内存清零
来源：http://dali.tian-w.cn/Article/details/gtphmkxxnt.html

memset(a, 0, sizeof a);
来源：http://dali.birdmap.top/Article/details/gtstisxosk.html

[S27] C：定义常量
来源：http://dali.xylfe.cn/Article/details/gtwkmxxdvi.html

const double PI = 3.14159;
来源：http://dali.nanxinkj.top/Article/details/gtyncflhdf.html

[S28] C：静态变量
来源：http://dali.jqgfzy.top/Article/details/gtobpcwzgc.html

static int counter = 0;
来源：http://dali.0kj1m.cn/Article/details/gtgucxavjp.html

[S29] C：变参函数
来源：http://dali.yongpay.top/Article/details/gtkvftvbfc.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.tian-w.cn/Article/details/gtkjxhrbta.html

[S30] C：头文件保护
来源：http://dali.cashguo.top/Article/details/gtsdtsfgyp.html

#ifndef X_H
来源：http://dali.gogol.net.cn/Article/details/gtjiytpogr.html

#define X_H
来源：http://dali.shanyushiyangtech.top/Article/details/gtnirxfbbn.html

#endif
来源：http://dali.smart0.xyz/Article/details/gtqiwhduqc.html

[S31] C++：Hello World
来源：http://dali.pycfn.com/Article/details/gtgjwrtjhg.html

#include <iostream>
来源：http://dali.yj20258.top/Article/details/gtpncjhsve.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.sysykeji.top/Article/details/gtzypdrwhs.html

[S32] C++：字符串
来源：http://dali.iojbl.cn/Article/details/gtyjkowgdr.html

std::string s = "hi";  s += "!";
来源：http://dali.jiagoushi.top/Article/details/gtkvjhjeph.html

[S33] C++：vector 增删
来源：http://dali.yvedp.cn/Article/details/gtadsidygz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.vqdsnc.cn/Article/details/gtdcenwaam.html

[S34] C++：遍历 vector
来源：http://dali.mhx1999.top/Article/details/gtxonwciyv.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.tian-w.cn/Article/details/gtixiqathr.html

[S35] C++：map
来源：http://dali.fzhhl.top/Article/details/gttoxkggto.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.bjfxy.top/Article/details/gtpifjnkxs.html

[S36] C++：unordered_map
来源：http://dali.ywan-chungtsiang.top/Article/details/gtewbtoxki.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.feifeiyinyue.top/Article/details/gtkdqdqizh.html

[S37] C++：set
来源：http://dali.havefunace.top/Article/details/gtpztimiig.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.wangshuangyany.cn/Article/details/gtetvthyhe.html

[S38] C++：排序
来源：http://dali.yuxming.cn/Article/details/gtzmsjgwcu.html

std::sort(v.begin(), v.end());
来源：http://dali.quarkkingdee.top/Article/details/gtvawetcng.html

[S39] C++：自定义比较器排序
来源：http://dali.gzhubu.top/Article/details/gtvlhcmgrc.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yangfankeji.com/Article/details/gthbxsjlmf.html

[S40] C++：查找元素
来源：http://dali.yangfankeji.com/Article/details/gtnhmutcpi.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jlsjyb.cn/Article/details/gtorukkuri.html

[S41] C++：类与构造函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfwrupefg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.haohaochexian.top/Article/details/gtvptshixw.html

[S42] C++：继承与虚函数
来源：http://dali.andypj.xyz/Article/details/gtvmznkple.html

class B : public Base { public: void f() override {} };
来源：http://dali.yuxming.cn/Article/details/gtjtdhzngz.html

[S43] C++：智能指针
来源：http://dali.meibo888.top/Article/details/gtokdmicxs.html

auto p = std::make_unique<int>(5);
来源：http://dali.gogol.net.cn/Article/details/gtdkblslue.html

[S44] C++：引用传参
来源：http://dali.meibo888.top/Article/details/gtkykfzdhk.html

void inc(int &x) { ++x; }
来源：http://dali.sweek.top/Article/details/gtbpazawot.html

[S45] C++：lambda
来源：http://dali.shangyingyoupin.top/Article/details/gtnjtstucg.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.quarkkingdee.top/Article/details/gtobuieswr.html

[S46] C++：函数模板
来源：http://dali.wangshuangyany.cn/Article/details/gtftchsbwe.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.tian-w.cn/Article/details/gtqlwbyalk.html

[S47] C++：结构化绑定遍历
来源：http://dali.fzhhl.top/Article/details/gteuuiwyvd.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yanxiufei.cn/Article/details/gtenpjnweq.html

[S48] C++：逐行读文件
来源：http://dali.nanxuanxn.top/Article/details/gthtxekrad.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.dashuyun.cn/Article/details/gtszdyocyz.html

while (std::getline(in, line)) { }
来源：http://dali.feifeiyinyue.top/Article/details/gtbmxtpqxh.html

[S49] C++：写文件
来源：http://dali.xziqi.cn/Article/details/gtgppzwmzo.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.bjfxy.top/Article/details/gtqamcjlnf.html

[S50] C++：格式化数字
来源：http://dali.nanxinkj.top/Article/details/gtkjihjeyk.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.gogol.net.cn/Article/details/gtytzomncf.html

[S51] C++：显式类型转换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwcvgsgez.html

static_cast<double>(a) / b
来源：http://dali.feifeiyinyue.top/Article/details/gtodwjblie.html

[S52] C++：const 与 noexcept
来源：http://dali.mhx1999.top/Article/details/gtrirrnutb.html


<!-- 参考信息 -->