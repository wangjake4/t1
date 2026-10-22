代发 wailian999

[Q84] 去除首尾空格
来源：http://dali.zhixingplan.top/Article/details/gtioxfwwdr.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtwbsyompf.html

[Q85] 数值取整
来源：http://dali.dashuyun.cn/Article/details/gtkqeajpta.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthkvbjpzw.html

[Q86] 读取 JSON 字段
来源：http://dali.tian-w.cn/Article/details/gtsslzvqdz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.daria6918.cn/Article/details/gtmeqpjqoo.html

[Q87] JSON 字段做条件
来源：http://dali.daxiang520.top/Article/details/gttakwipik.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.tianlin.xyz/Article/details/gtumqdhltp.html

[Q88] 行转列（条件聚合）
来源：http://dali.shzxlz.cn/Article/details/gtbkoothvu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jyoumei.cn/Article/details/gtqortdcjd.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.mhx1999.top/Article/details/gtubhlbiey.html

[Q89] 判断表是否存在
来源：http://dali.yj202588.top/Article/details/gtcornjamp.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shangyingyoupin.top/Article/details/gttzsswsiq.html

[Q90] 生成序号列
来源：http://dali.iojbl.cn/Article/details/gtevdzkscf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdkokvtax.html

================================================================================
来源：http://dali.ehwqpu.com/Article/details/gtggsxrobf.html

R. Bash 专题
来源：http://dali.xylfe.cn/Article/details/gtmctogaat.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtdtmqihvf.html

[R01] shebang 与严格模式
来源：http://dali.jinqigfzy.top/Article/details/gtajqjzrfl.html

#!/usr/bin/env bash
来源：http://dali.jqgufenzy.top/Article/details/gteqwbxrsa.html

set -euo pipefail
来源：http://dali.ywan-chungtsiang.top/Article/details/gtemqjhyda.html

[R02] 变量赋值与使用
来源：http://dali.yuanzhike.top/Article/details/gtpphlirva.html

name="Tom"; echo "$name"
来源：http://dali.zhixingplan.top/Article/details/gtnnqpddbz.html

[R03] 只读变量
来源：http://dali.zhongyouzk.top/Article/details/gtvqijuwje.html

readonly PI=3.14
来源：http://dali.dashuyun.cn/Article/details/gtwtgpcakb.html

[R04] 位置参数
来源：http://dali.zhongyouzk.top/Article/details/gtvxjjjbnv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.haohaochexian.top/Article/details/gtdhaavcfs.html

[R05] 参数默认值
来源：http://dali.chenzaomai.com/Article/details/gtvyxikvmu.html

name="${1:-default}"
来源：http://dali.hongshengwenyu.top/Article/details/gtbexbkase.html

[R06] 判断命令是否存在
来源：http://dali.feifeiyinyue.top/Article/details/gtsebwihvq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ivvv.top/Article/details/gtfifbdxjr.html

[R07] if 判断文件
来源：http://dali.cucudq.cn/Article/details/gtbzdisfnv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ppjwa.cn/Article/details/gtuvzaabec.html

[R08] 数值比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gthkdqhxmn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tianlin.xyz/Article/details/gtgecavbtw.html

[R09] 字符串比较
来源：http://dali.dianchejie.cn/Article/details/gtcgpyiolq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmovlhrtr.html

[R10] 正则匹配
来源：http://dali.ppjwa.cn/Article/details/gtvkzvjdta.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.9152youxi.cn/Article/details/gtqqlwkmfg.html

[R11] case 多分支
来源：http://dali.tianlin.xyz/Article/details/gtdtuzjozx.html

case "$1" in
来源：http://dali.meibo888.top/Article/details/gtfukrbmwx.html

start) echo "启动" ;;
来源：http://dali.smart0.xyz/Article/details/gtvggulidz.html

stop)  echo "停止" ;;
来源：http://dali.guowangkeji.top/Article/details/gtcyrcjirf.html

*)     echo "未知命令" ;;
来源：http://dali.havefunace.top/Article/details/gtxsxowmfd.html

esac
来源：http://dali.bjfxy.top/Article/details/gtkacfpxzs.html

[R12] for 遍历文件
来源：http://dali.sysykeji.top/Article/details/gttzakhuvk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtqrcqmgob.html

[R13] for 计数循环
来源：http://dali.birdmap.top/Article/details/gtnyodrtdy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhoulong.xyz/Article/details/gttiyfksuv.html

[R14] C 风格 for
来源：http://dali.sysykeji.top/Article/details/gtgwciqbme.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhoulong.xyz/Article/details/gtmgapzraa.html

[R15] while 逐行读文件
来源：http://dali.hfpthk.cn/Article/details/gttngrglsr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinqigfzy.top/Article/details/gtrmfmulov.html

[R16] until 等待条件
来源：http://dali.jqgfzy.top/Article/details/gtqopwthhe.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yj20258.top/Article/details/gtfnvwcaxe.html

[R17] 数组定义与取值
来源：http://dali.cheryme.top/Article/details/gtakbgjhtz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenzaomai.com/Article/details/gtdedimgch.html

[R18] 遍历数组
来源：http://dali.chenjidiqi.icu/Article/details/gtpjnekezk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shangyingyoupin.top/Article/details/gteicpaqfs.html

[R19] 数组长度
来源：http://dali.hnxiangtu.top/Article/details/gtdayxdeul.html

echo "${#arr[@]}"
来源：http://dali.aizwys.cn/Article/details/gtwdappkvu.html

[R20] 关联数组（字典）
来源：http://dali.cashguo.top/Article/details/gtzmxazxnh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cqqwz.cn/Article/details/gtkcxlfyde.html

[R21] 字符串长度
来源：http://dali.yanxiufei.cn/Article/details/gtheovtqnj.html

echo "${#s}"
来源：http://dali.yonumen.top/Article/details/gtocrvjptl.html

[R22] 截取子串
来源：http://dali.bjfxy.top/Article/details/gtsvzxckem.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gtzzzusqyf.html

[R23] 字符串替换
来源：http://dali.cashguo.top/Article/details/gtvakqsqew.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.birdmap.top/Article/details/gtmigtvlad.html

[R24] 大小写转换
来源：http://dali.yonumen.top/Article/details/gtdhzsxszj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yuanzhike.top/Article/details/gtkceosoti.html

[R25] 去后缀 / 去前缀
来源：http://dali.yonumen.top/Article/details/gtzvnszdjo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yonumen.top/Article/details/gtdrtxfbqc.html

[R26] 命令替换
来源：http://dali.quarkkingdee.top/Article/details/gtgnnwrdun.html

now=$(date +%F); echo "$now"
来源：http://dali.feifeiyinyue.top/Article/details/gtqmoyvvdm.html

[R27] 算术展开
来源：http://dali.yonumen.top/Article/details/gtjpjsnwam.html

echo $((1 + 2 * 3))
来源：http://dali.chenjidiqi.icu/Article/details/gtulhyjjag.html

[R28] 浮点运算
来源：http://dali.tanke756.top/Article/details/gtwmcgomvs.html

echo "scale=2; 10/3" | bc
来源：http://dali.jiagoushi.top/Article/details/gtrdibvrxa.html

[R29] 定义函数
来源：http://dali.jinqigufen.top/Article/details/gtwzwbwvjx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.fengsongda.top/Article/details/gtlvhokxux.html

[R30] 函数返回状态码
来源：http://dali.shanyushiyangtech.top/Article/details/gtjvjhykun.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.redwolf501.top/Article/details/gtyeowffyz.html

[R31] 局部变量
来源：http://dali.jinqigfzy.top/Article/details/gtzxwyyivr.html

f() { local x=1; echo "$x"; }
来源：http://dali.nanxinkj.top/Article/details/gtnqwztbxi.html

[R32] 参数个数校验
来源：http://dali.xinyue.icu/Article/details/gtvusttqps.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gttwcxjebm.html

[R33] 捕获错误并提示行号
来源：http://dali.yuanzhike.top/Article/details/gtwkhfdjpd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.feifeiyinyue.top/Article/details/gtcksmcsxn.html

[R34] 退出时清理
来源：http://dali.chenlongwang.top/Article/details/gtfqdyxgks.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gaohongyu789.top/Article/details/gtydjzebpp.html

[R35] 后台执行并等待
来源：http://dali.jlsjyb.cn/Article/details/gtfkdwbtdz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jqgfzy.top/Article/details/gtdclowrgi.html

[R36] 并发执行多个任务
来源：http://dali.snrcjt.cn/Article/details/gthccmhffu.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.dianchejie.cn/Article/details/gtlkcjelbe.html

[R37] 把输出赋给变量
来源：http://dali.cdnleiting.top/Article/details/gtnxblekks.html

files=$(ls -1)
来源：http://dali.ivvv.top/Article/details/gtzylsmbbk.html

[R38] 管道串联
来源：http://dali.zhiwuduotai.top/Article/details/gtwpbugcry.html

cat a.txt | grep -i error | wc -l
来源：http://dali.cheryme.top/Article/details/gtblrqbwam.html

[R39] 重定向标准输出与错误
来源：http://dali.hongshengwenyu.top/Article/details/gtxaowdaym.html

cmd > out.log 2>&1
来源：http://dali.yangfankeji.com/Article/details/gthfyytjsv.html

[R40] 追加写日志
来源：http://dali.c1oappe.top/Article/details/gtkocxelxq.html

echo "log" >> out.log
来源：http://dali.yvedp.cn/Article/details/gtoddwwqya.html

[R41] 丢弃输出
来源：http://dali.0kj1m.cn/Article/details/gtubrzagcv.html

cmd >/dev/null 2>&1
来源：http://dali.shanyushiyangtech.top/Article/details/gtlexkfvlm.html

[R42] 输入重定向
来源：http://dali.sufxvd.cn/Article/details/gtieqrnpdx.html

wc -l < a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtrgtgrkms.html

[R43] 按名字查找文件
来源：http://dali.ydzc1.top/Article/details/gtkoprztlo.html

find . -name "*.log" -type f
来源：http://dali.bjfxy.top/Article/details/gtiouvoalf.html

[R44] 按修改时间查找
来源：http://dali.guowangkeji.top/Article/details/gthuyvfwyd.html

find . -mtime -7 -type f
来源：http://dali.jinyuanbaomall.cn/Article/details/gttxpvihoj.html

[R45] 批量删除
来源：http://dali.guannengcc.top/Article/details/gtubiffnhg.html

find . -name "*.tmp" -delete
来源：http://dali.0kj1m.cn/Article/details/gttdnkmffp.html

[R46] 递归替换文件内容
来源：http://dali.gotoacloud.top/Article/details/gtpsjlthms.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ydzc1.top/Article/details/gtnlcenlcp.html

[R47] sed 单行替换
来源：http://dali.snrcjt.cn/Article/details/gtsswbfmkf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gzhubu.top/Article/details/gtjexiyrcv.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gtvykziwcf.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhengqikj.top/Article/details/gtjnuypntc.html

[R49] awk 带条件
来源：http://dali.yongpay.top/Article/details/gtducydhad.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhengqikj.top/Article/details/gtdofdkuyg.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gtjazdnxtc.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.redwolf501.top/Article/details/gtuyqquhqe.html

[R51] 排序去重取前几
来源：http://dali.shzxlz.cn/Article/details/gtrxcpcmyz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.dashuyun.cn/Article/details/gtasmrxkrb.html

[R52] 统计行数
来源：http://dali.ivvv.top/Article/details/gthzckecmf.html

wc -l a.txt
来源：http://dali.zhongyouzk.top/Article/details/gtmtcrxbft.html

[R53] 查看文件头与实时尾
来源：http://dali.redwolf501.top/Article/details/gtgfpaspza.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yvedp.cn/Article/details/gtyfbzclku.html

[R54] 比较两个文件
来源：http://dali.yongpay.top/Article/details/gtxzvthsid.html

diff a.txt b.txt
来源：http://dali.cashguo.top/Article/details/gtknmhuynr.html

[R55] 压缩与解压
来源：http://dali.hnqzz.top/Article/details/gtppqfnguv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.nanxinkj.top/Article/details/gtoliyonvb.html

[R56] 远程拷贝
来源：http://dali.smart0.xyz/Article/details/gttbihqaqp.html

scp file user@host:/path/
来源：http://dali.yonumen.top/Article/details/gtabwjwods.html

[R57] 远程执行命令
来源：http://dali.nanxuanxn.top/Article/details/gtvccgnpvo.html

ssh user@host 'uptime'
来源：http://dali.shzxlz.cn/Article/details/gthaybbkvw.html

[R58] 下载文件
来源：http://dali.chenzaomai.com/Article/details/gtqljamcqe.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.c1oappe.top/Article/details/gtpkojqyds.html

[R59] 发 POST JSON
来源：http://dali.fengsongda.top/Article/details/gtauwpnflv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xziqi.cn/Article/details/gtyicpthan.html

[R60] 只看 HTTP 状态码
来源：http://dali.kuanghao11.cn/Article/details/gtmqviedah.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.havefunace.top/Article/details/gtxvaspzal.html

[R61] 磁盘占用
来源：http://dali.jinqigfzy.top/Article/details/gtfipjckca.html

df -h;  du -sh *
来源：http://dali.bjfxy.top/Article/details/gtqkftmnpb.html

[R62] 找最占空间的文件
来源：http://dali.hammf.cn/Article/details/gtmrcuynpn.html

du -ah . | sort -rh | head -10
来源：http://dali.xinyue.icu/Article/details/gtmfedoqqd.html

[R63] 内存与进程
来源：http://dali.yueranfly.top/Article/details/gtzlsfecfj.html

free -h;  ps aux | grep nginx
来源：http://dali.gzhubu.top/Article/details/gtppnvuowi.html

[R64] 结束进程
来源：http://dali.snrcjt.cn/Article/details/gtiadbmtri.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hywenlv.cn/Article/details/gtyvltcuff.html

[R65] 查看端口占用
来源：http://dali.tianlin.xyz/Article/details/gtsrmqquuf.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yangfankeji.com/Article/details/gtfytufmzc.html

[R66] 定时任务
来源：http://dali.shangyingyoupin.top/Article/details/gtgmcwbnoy.html

crontab -e;  crontab -l
来源：http://dali.hnqzz.top/Article/details/gttnklsosn.html

[R67] 生成随机十六进制串
来源：http://dali.yangfankeji.com/Article/details/gtovetegnv.html

openssl rand -hex 16
来源：http://dali.jyoumei.cn/Article/details/gtouyrsldl.html

[R68] 计算文件校验值
来源：http://dali.xziqi.cn/Article/details/gtduvhcjso.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenlongwang.top/Article/details/gtgvnzsqaw.html

[R69] 生成随机密码
来源：http://dali.redwolf501.top/Article/details/gtkctruslv.html

head -c 16 /dev/urandom | base64
来源：http://dali.hongshengwenyu.top/Article/details/gttgxvaget.html

[R70] 时间戳与互转
来源：http://dali.0kj1m.cn/Article/details/gtdrjrjoru.html

date +%s;  date -d @1700000000
来源：http://dali.shuidangran.top/Article/details/gtgknajnkk.html

[R71] 日期格式化
来源：http://dali.aizwys.cn/Article/details/gtizbfxtiv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jqgfzy.top/Article/details/gtobgipeae.html

[R72] 等待端口就绪
来源：http://dali.tanke756.top/Article/details/gtziunemxn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.ehwqpu.com/Article/details/gttjojltgc.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gtbgnzjtfl.html

split -l 1000 big.log part_
来源：http://dali.yongpay.top/Article/details/gtftwiailo.html

[R74] 批量重命名
来源：http://dali.jinqigfzy.top/Article/details/gtxpuuqwrw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.tanke756.top/Article/details/gtckbtalwy.html

[R75] 导出环境变量
来源：http://dali.ybcxt.top/Article/details/gtxpkvitvf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xziqi.cn/Article/details/gtogijdgrt.html

[R76] 使用临时文件
来源：http://dali.xylfe.cn/Article/details/gtvtymablu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xylfe.cn/Article/details/gtuzmzgnjy.html

[R77] 读取用户输入
来源：http://dali.shangyingyoupin.top/Article/details/gtyitohxwo.html

read -rp "请输入: " ans
来源：http://dali.hammf.cn/Article/details/gtknlejtqt.html

[R78] 交互式菜单
来源：http://dali.yj20258888.top/Article/details/gtictihnkd.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.cheryme.top/Article/details/gtenfgcdys.html

[R79] 解析命令行选项
来源：http://dali.nanxuanxn.top/Article/details/gtedeqjmuk.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jqgufenzy.top/Article/details/gthxeifqyo.html

[R80] 查看脚本执行耗时
来源：http://dali.xuetiantiany.cn/Article/details/gtykgeotil.html

time ./run.sh
来源：http://dali.nwbrower.top/Article/details/gtxlmoirmy.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtszzkdmro.html

S. C / C++ 专题
来源：http://dali.smart0.xyz/Article/details/gtknopxiiw.html

================================================================================
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsheojtes.html

[S01] C：Hello World
来源：http://dali.chenjidiqi.icu/Article/details/gthdbxdxtb.html

#include <stdio.h>
来源：http://dali.ydzc1.top/Article/details/gtthlgsvvh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.cucudq.cn/Article/details/gtpwomufud.html

[S02] C：变量与格式化输出
来源：http://dali.vqdsnc.cn/Article/details/gtcaauholf.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinghuilouyu.cn/Article/details/gtytgooeiu.html

[S03] C：读入整数
来源：http://dali.haohaochexian.top/Article/details/gtfkrmbylq.html

int x; scanf("%d", &x);
来源：http://dali.nanxinkj.top/Article/details/gtstvmxedx.html

[S04] C：字符串复制
来源：http://dali.chenzaomai.com/Article/details/gtrtbkqfpb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.gaohongyu789.top/Article/details/gttlxwhtjq.html

[S05] C：字符串长度
来源：http://dali.yonumen.top/Article/details/gtihlvoxyz.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gtcwsnbzdk.html

[S06] C：字符串比较
来源：http://dali.chenjidiqi.icu/Article/details/gtopmjplco.html

strcmp(a, b) == 0
来源：http://dali.jianghu66.top/Article/details/gtlkraqncz.html

[S07] C：数组遍历求和
来源：http://dali.gotoacloud.top/Article/details/gthgympqne.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.cucudq.cn/Article/details/gtmglkonpj.html

[S08] C：动态内存分配与释放
来源：http://dali.yonumen.top/Article/details/gtkgtgqixj.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.jinqigfzy.top/Article/details/gthzrjhjwz.html

[S09] C：结构体定义与初始化
来源：http://dali.yongpay.top/Article/details/gtjtcfozmt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.jqgufenzy.top/Article/details/gtwwiourja.html

[S10] C：指针与解引用
来源：http://dali.jinqigufen.top/Article/details/gtppedgfcx.html

int *p = &a;  *p = 5;
来源：http://dali.shanyushiyangtech.top/Article/details/gtmupkilqh.html

[S11] C：逐行读文件
来源：http://dali.yangfankeji.com/Article/details/gtassxcooa.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.hnxiangtu.top/Article/details/gtwdjvtynn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.xylfe.cn/Article/details/gtdyjqncft.html

fclose(f);
来源：http://dali.xuanzx.com/Article/details/gttcsyydue.html

[S12] C：写文件
来源：http://dali.pycfn.com/Article/details/gtgvnlltfe.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.gotoacloud.top/Article/details/gtqshxrkkp.html

[S13] C：宏定义
来源：http://dali.yj20258888.top/Article/details/gtcznpeshb.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hfpthk.cn/Article/details/gtxiwndiqb.html

[S14] C：枚举
来源：http://dali.jqgufenzy.top/Article/details/gtsnjxbvdl.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.redwolf501.top/Article/details/gtpadwyuei.html

[S15] C：类型转换
来源：http://dali.zhoulong.xyz/Article/details/gtxtryvbtf.html

(double) a / b
来源：http://dali.0kj1m.cn/Article/details/gtcpkdbxyt.html

[S16] C：位操作置位
来源：http://dali.ydzc1.top/Article/details/gtlzolbzpl.html

x |= (1 << 3);
来源：http://dali.xuanzx.com/Article/details/gtnkiilaic.html

[S17] C：安全拼接字符串
来源：http://dali.vqdsnc.cn/Article/details/gtapmhbkjx.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.feifeiyinyue.top/Article/details/gtpupoqmrf.html

[S18] C：命令行参数
来源：http://dali.shuidangran.top/Article/details/gttaecsspw.html

int main(int argc, char **argv)
来源：http://dali.snrcjt.cn/Article/details/gtbwppthbn.html

[S19] C：快速排序
来源：http://dali.yangfankeji.com/Article/details/gtsfbqquem.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gogol.net.cn/Article/details/gtjptjimmz.html

[S20] C：二分查找
来源：http://dali.shanyushiyangtech.top/Article/details/gtrxlqqjfb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.pengpengdd.cyou/Article/details/gtnzhnfbjp.html

[S21] C：字符类别判断
来源：http://dali.tanke756.top/Article/details/gtotgapzbd.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.9152youxi.cn/Article/details/gtpkbnqdrg.html

[S22] C：字符串转数字
来源：http://dali.yonumen.top/Article/details/gtwhzdmtcj.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yonumen.top/Article/details/gttcbkvnkh.html

[S23] C：随机数
来源：http://dali.0kj1m.cn/Article/details/gtwdopcgwk.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.wangshuangyany.cn/Article/details/gtzgcchuio.html

[S24] C：获取本地时间
来源：http://dali.316326.xyz/Article/details/gtvswawudy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yongpay.top/Article/details/gtcdwuuwea.html

[S25] C：内存拷贝
来源：http://dali.jyoumei.cn/Article/details/gtmhtbrntb.html

memcpy(dst, src, n);
来源：http://dali.xziqi.cn/Article/details/gtnlfzftvm.html

[S26] C：内存清零
来源：http://dali.jianghu66.top/Article/details/gtmqbnbvuy.html

memset(a, 0, sizeof a);
来源：http://dali.wangshuangyany.cn/Article/details/gtrbpuokpb.html

[S27] C：定义常量
来源：http://dali.birdmap.top/Article/details/gtlusjitwf.html

const double PI = 3.14159;
来源：http://dali.birdmap.top/Article/details/gtbpvzoetv.html

[S28] C：静态变量
来源：http://dali.aibaodan.cn/Article/details/gtmqcicyus.html

static int counter = 0;
来源：http://dali.hnqzz.top/Article/details/gtnimzpegi.html

[S29] C：变参函数
来源：http://dali.yuanzhike.top/Article/details/gtunskpqbs.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.hysaishi.cn/Article/details/gtlnknsihh.html

[S30] C：头文件保护
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmjvrosfw.html

#ifndef X_H
来源：http://dali.shzxlz.cn/Article/details/gtbgzafznz.html

#define X_H
来源：http://dali.jinghuilouyu.cn/Article/details/gtgxxlpxfw.html

#endif
来源：http://dali.snrcjt.cn/Article/details/gtdtmuuaro.html

[S31] C++：Hello World
来源：http://dali.cashguo.top/Article/details/gtqnkgkedp.html

#include <iostream>
来源：http://dali.yj20258888.top/Article/details/gtuwthefuf.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.daria6918.cn/Article/details/gtzrkuuftf.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gtxhtkoatc.html

std::string s = "hi";  s += "!";
来源：http://dali.xinyue.icu/Article/details/gtcuoibkcp.html

[S33] C++：vector 增删
来源：http://dali.zdqjudy.top/Article/details/gtswtkalvk.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtewzfivic.html

[S34] C++：遍历 vector
来源：http://dali.hnxiangtu.top/Article/details/gtbimzlerd.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.nanxuanxn.top/Article/details/gtjrtfuucj.html

[S35] C++：map
来源：http://dali.sweek.top/Article/details/gtdndkuqoi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtiqmroovv.html

[S36] C++：unordered_map
来源：http://dali.mhx1999.top/Article/details/gtchmtracq.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmjamqmsk.html

[S37] C++：set
来源：http://dali.chenjidiqi.icu/Article/details/gtkliahalw.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.dianchejie.cn/Article/details/gtjktepiew.html

[S38] C++：排序
来源：http://dali.gzhubu.top/Article/details/gtccbqcqsb.html

std::sort(v.begin(), v.end());
来源：http://dali.jiagoushi.top/Article/details/gtyeyptvbe.html

[S39] C++：自定义比较器排序
来源：http://dali.yj202588.top/Article/details/gtuedalpfr.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.hywenlv.cn/Article/details/gtxwndeonl.html

[S40] C++：查找元素
来源：http://dali.xziqi.cn/Article/details/gtqugmatvi.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtuuzvogkz.html

[S41] C++：类与构造函数
来源：http://dali.gaohongyu789.top/Article/details/gtrpqsspdj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.yvedp.cn/Article/details/gtkrfpiozh.html

[S42] C++：继承与虚函数
来源：http://dali.zhongyouzk.top/Article/details/gtaynwpcek.html

class B : public Base { public: void f() override {} };
来源：http://dali.aizwys.cn/Article/details/gtuvqjnqxq.html

[S43] C++：智能指针
来源：http://dali.quarkkingdee.top/Article/details/gtegkrnvwb.html

auto p = std::make_unique<int>(5);
来源：http://dali.gotoacloud.top/Article/details/gtkktidbgv.html

[S44] C++：引用传参
来源：http://dali.wangshuangyany.cn/Article/details/gtrcxnqnxe.html

void inc(int &x) { ++x; }
来源：http://dali.zhongyouzk.top/Article/details/gthbmvlxyy.html

[S45] C++：lambda
来源：http://dali.guowangkeji.top/Article/details/gtswfpcnqq.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.ehwqpu.com/Article/details/gtcforsugu.html

[S46] C++：函数模板
来源：http://dali.sysykeji.top/Article/details/gtoogjlljs.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.xziqi.cn/Article/details/gtojxxmwsm.html

[S47] C++：结构化绑定遍历
来源：http://dali.sweek.top/Article/details/gtahcaeuuu.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.ydzc1.top/Article/details/gtxsluiqdb.html

[S48] C++：逐行读文件
来源：http://dali.yj20258888.top/Article/details/gtcibbsbrz.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.chenlongwang.top/Article/details/gtdvrxrrke.html

while (std::getline(in, line)) { }
来源：http://dali.gaohongyu789.top/Article/details/gtpxrmznmu.html

[S49] C++：写文件
来源：http://dali.zhixingplan.top/Article/details/gtwzimbopi.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cqqwz.cn/Article/details/gtqtmxptln.html

[S50] C++：格式化数字
来源：http://dali.xuanzx.com/Article/details/gttomekmac.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.yj202588.top/Article/details/gtjmdylxzs.html

[S51] C++：显式类型转换
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzvcomepx.html

static_cast<double>(a) / b
来源：http://dali.chenzaomai.com/Article/details/gtbgwqcwdg.html

[S52] C++：const 与 noexcept
来源：http://dali.jinyuanbaomall.cn/Article/details/gtiviqtxww.html

int size() const noexcept { return n_; }
来源：http://dali.wangshuangyany.cn/Article/details/gtdezfbhxr.html

[S53] C++：移动语义
来源：http://dali.c1oappe.top/Article/details/gtnxxqjgrr.html

std::vector<int> w = std::move(v);
来源：http://dali.nwbrower.top/Article/details/gtcssdfgdr.html

[S54] C++：异常处理
来源：http://dali.guannengcc.top/Article/details/gtkqfbaosc.html


<!-- 参考信息 -->