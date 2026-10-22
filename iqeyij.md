代发 wailian999

[Q84] 去除首尾空格
来源：http://dali.redwolf501.top/Article/details/gt2tmiadnab.html

SELECT TRIM(name) FROM users;
来源：http://dali.316326.xyz/Article/details/gt2lddqgvvo.html

[Q85] 数值取整
来源：http://dali.cheryme.top/Article/details/gt2ulxrwing.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.nwbrower.top/Article/details/gt2xnmdhkio.html

[Q86] 读取 JSON 字段
来源：http://dali.wangshuangyany.cn/Article/details/gt2ovmempwl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.dashuyun.cn/Article/details/gt2jyxcsesn.html

[Q87] JSON 字段做条件
来源：http://dali.birdmap.top/Article/details/gt2yedetqet.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.iojbl.cn/Article/details/gt2qgnbgqal.html

[Q88] 行转列（条件聚合）
来源：http://dali.tianlin.xyz/Article/details/gt2bverdlmi.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ybcxt.top/Article/details/gt2lcqhnooo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cashguo.top/Article/details/gt2xzelmeik.html

[Q89] 判断表是否存在
来源：http://dali.gaohongyu789.top/Article/details/gt2pnexupmm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.quarkkingdee.top/Article/details/gt2ffpgseap.html

[Q90] 生成序号列
来源：http://dali.jiagoushi.top/Article/details/gt2ufuesrok.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hnxiangtu.top/Article/details/gt2lnvtvolb.html

================================================================================
来源：http://dali.316326.xyz/Article/details/gt2achhmojg.html

R. Bash 专题
来源：http://dali.feifeiyinyue.top/Article/details/gt2dkkpzang.html

================================================================================
来源：http://dali.nanxuanxn.top/Article/details/gt2kjqchiia.html

[R01] shebang 与严格模式
来源：http://dali.sxryk.cn/Article/details/gt2rbdkozgl.html

#!/usr/bin/env bash
来源：http://dali.shangyingyoupin.top/Article/details/gt2euqtfsuc.html

set -euo pipefail
来源：http://dali.gotoacloud.top/Article/details/gt2sjvrpanr.html

[R02] 变量赋值与使用
来源：http://dali.vqdsnc.cn/Article/details/gt2kxiiscas.html

name="Tom"; echo "$name"
来源：http://dali.chenjidiqi.icu/Article/details/gt2jyhjonex.html

[R03] 只读变量
来源：http://dali.zdqjudy.top/Article/details/gt2jusiatvc.html

readonly PI=3.14
来源：http://dali.hnxiangtu.top/Article/details/gt2qglwllcq.html

[R04] 位置参数
来源：http://dali.fengsongda.top/Article/details/gt2rynvlpse.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj202588.top/Article/details/gt2dbikmhic.html

[R05] 参数默认值
来源：http://dali.sweek.top/Article/details/gt2aixdyfuk.html

name="${1:-default}"
来源：http://dali.ybcxt.top/Article/details/gt2pkufhddq.html

[R06] 判断命令是否存在
来源：http://dali.chenzaomai.com/Article/details/gt2xugjcisr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jyoumei.cn/Article/details/gt2tvzrnxlq.html

[R07] if 判断文件
来源：http://dali.kuanghao11.cn/Article/details/gt2ercjywbe.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.nanxinkj.top/Article/details/gt2wpxaelvw.html

[R08] 数值比较
来源：http://dali.gaohongyu789.top/Article/details/gt2wmnjecan.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yongpay.top/Article/details/gt2vuwnnrnp.html

[R09] 字符串比较
来源：http://dali.hfpthk.cn/Article/details/gt2awhsbwly.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.iojbl.cn/Article/details/gt2aubtuvvi.html

[R10] 正则匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gt2kwmthuwy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jiagoushi.top/Article/details/gt2swuohmfe.html

[R11] case 多分支
来源：http://dali.yueranfly.top/Article/details/gt2kqjpvgvz.html

case "$1" in
来源：http://dali.hywenlv.cn/Article/details/gt2lgsscmij.html

start) echo "启动" ;;
来源：http://dali.tian-w.cn/Article/details/gt2ssrhanic.html

stop)  echo "停止" ;;
来源：http://dali.ehwqpu.com/Article/details/gt2efhvnzrf.html

*)     echo "未知命令" ;;
来源：http://dali.wangdashe.top/Article/details/gt2sojisdvn.html

esac
来源：http://dali.xylfe.cn/Article/details/gt2xyptbznn.html

[R12] for 遍历文件
来源：http://dali.jqgfzy.top/Article/details/gt2qsgpkqqi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mbqdiigb.html

[R13] for 计数循环
来源：http://dali.yvedp.cn/Article/details/gt2qbohgncm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.kuanghao11.cn/Article/details/gt2ibhukjde.html

[R14] C 风格 for
来源：http://dali.guannengcc.top/Article/details/gt2qhbdkkkx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2cisngtvd.html

[R15] while 逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gt2aogylmup.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinqigfzy.top/Article/details/gt2jxdwzfid.html

[R16] until 等待条件
来源：http://dali.yj202588.top/Article/details/gt2qpgpuotk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.aibaodan.cn/Article/details/gt2wjovvzli.html

[R17] 数组定义与取值
来源：http://dali.andypj.xyz/Article/details/gt2eciftsok.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yj202588.top/Article/details/gt2maobsyvy.html

[R18] 遍历数组
来源：http://dali.gaohongyu789.top/Article/details/gt2yblyrupy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hysaishi.cn/Article/details/gt2xrdkspar.html

[R19] 数组长度
来源：http://dali.zhoulong.xyz/Article/details/gt2aqcnjavn.html

echo "${#arr[@]}"
来源：http://dali.c1oappe.top/Article/details/gt2sfsyawbo.html

[R20] 关联数组（字典）
来源：http://dali.yuanzhike.top/Article/details/gt2zwbcinxi.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj20258.top/Article/details/gt2sgrhybsg.html

[R21] 字符串长度
来源：http://dali.zhoulong.xyz/Article/details/gt2uhiawnda.html

echo "${#s}"
来源：http://dali.nwbrower.top/Article/details/gt2clygfwlm.html

[R22] 截取子串
来源：http://dali.jyoumei.cn/Article/details/gt2zhaazlfu.html

echo "${s:0:5}"
来源：http://dali.zhixingplan.top/Article/details/gt2xkbhzgez.html

[R23] 字符串替换
来源：http://dali.tian-w.cn/Article/details/gt2jufiwrln.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gogol.net.cn/Article/details/gt2eihgcawr.html

[R24] 大小写转换
来源：http://dali.guannengcc.top/Article/details/gt2uysyctdd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ivvv.top/Article/details/gt2qkktbotu.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhongyouzk.top/Article/details/gt2rdrlmjbq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xziqi.cn/Article/details/gt2xjigvzqc.html

[R26] 命令替换
来源：http://dali.gotoacloud.top/Article/details/gt2ixrqmbky.html

now=$(date +%F); echo "$now"
来源：http://dali.gaohongyu789.top/Article/details/gt2vvaqjfgf.html

[R27] 算术展开
来源：http://dali.jiagoushi.top/Article/details/gt2ccfeeumg.html

echo $((1 + 2 * 3))
来源：http://dali.jinghuilouyu.cn/Article/details/gt2osycjvgf.html

[R28] 浮点运算
来源：http://dali.smart0.xyz/Article/details/gt2jmgfweyo.html

echo "scale=2; 10/3" | bc
来源：http://dali.mhx1999.top/Article/details/gt2fcagjepl.html

[R29] 定义函数
来源：http://dali.shuidangran.top/Article/details/gt2dmwbjwko.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yj20258.top/Article/details/gt2wysnnwca.html

[R30] 函数返回状态码
来源：http://dali.yanxiufei.cn/Article/details/gt2pvijtwce.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jianghu66.top/Article/details/gt2wrnjrdnb.html

[R31] 局部变量
来源：http://dali.yongpay.top/Article/details/gt2ekyhzpzx.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinqigfzy.top/Article/details/gt2fgbjkllg.html

[R32] 参数个数校验
来源：http://dali.feifeiyinyue.top/Article/details/gt2pxsvtzce.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.nanxuanxn.top/Article/details/gt2pjjhlper.html

[R33] 捕获错误并提示行号
来源：http://dali.nanxuanxn.top/Article/details/gt2uuhujdro.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.nanxuanxn.top/Article/details/gt2nwnssggy.html

[R34] 退出时清理
来源：http://dali.daria6918.cn/Article/details/gt2rbzqkgwm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.nwbrower.top/Article/details/gt2onrvoasq.html

[R35] 后台执行并等待
来源：http://dali.aibaodan.cn/Article/details/gt2oujiipuy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yuanzhike.top/Article/details/gt2yzeharpp.html

[R36] 并发执行多个任务
来源：http://dali.chenzaomai.com/Article/details/gt2ptikqnmx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yuxming.cn/Article/details/gt2miaskzdn.html

[R37] 把输出赋给变量
来源：http://dali.shuidangran.top/Article/details/gt2wexztkfs.html

files=$(ls -1)
来源：http://dali.hongshengwenyu.top/Article/details/gt2jgxighpg.html

[R38] 管道串联
来源：http://dali.jinqigufen.top/Article/details/gt2upxiafrw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hnxiangtu.top/Article/details/gt2skhemclu.html

[R39] 重定向标准输出与错误
来源：http://dali.xylfe.cn/Article/details/gt2glhllwof.html

cmd > out.log 2>&1
来源：http://dali.svipenyu.cn/Article/details/gt2hncxjcum.html

[R40] 追加写日志
来源：http://dali.nanxinkj.top/Article/details/gt2apvffukx.html

echo "log" >> out.log
来源：http://dali.nanxinkj.top/Article/details/gt2nfepgsda.html

[R41] 丢弃输出
来源：http://dali.quarkkingdee.top/Article/details/gt2rmvgrmak.html

cmd >/dev/null 2>&1
来源：http://dali.jyoumei.cn/Article/details/gt2sesffekw.html

[R42] 输入重定向
来源：http://dali.gogol.net.cn/Article/details/gt2kiwgactp.html

wc -l < a.txt
来源：http://dali.0kj1m.cn/Article/details/gt2rscwkfpb.html

[R43] 按名字查找文件
来源：http://dali.daria6918.cn/Article/details/gt2zuvdcsdv.html

find . -name "*.log" -type f
来源：http://dali.shangyingyoupin.top/Article/details/gt2mpttggxu.html

[R44] 按修改时间查找
来源：http://dali.jlsjyb.cn/Article/details/gt2mijukrox.html

find . -mtime -7 -type f
来源：http://dali.nanxinkj.top/Article/details/gt2aifqewuz.html

[R45] 批量删除
来源：http://dali.tianlin.xyz/Article/details/gt2veiflyep.html

find . -name "*.tmp" -delete
来源：http://dali.yangfankeji.com/Article/details/gt2raiziojr.html

[R46] 递归替换文件内容
来源：http://dali.sxryk.cn/Article/details/gt2owwcoght.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.bjfxy.top/Article/details/gt2lqlnjpnl.html

[R47] sed 单行替换
来源：http://dali.havefunace.top/Article/details/gt2nfkosufc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zycfv.cn/Article/details/gt2bmamtsyv.html

[R48] awk 取指定列
来源：http://dali.shangyingyoupin.top/Article/details/gt2ojmmcqgo.html

awk '{print $1, $3}' a.txt
来源：http://dali.0kj1m.cn/Article/details/gt2zjvtkwdb.html

[R49] awk 带条件
来源：http://dali.xylfe.cn/Article/details/gt2uiiiwtnh.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.pengpengdd.cyou/Article/details/gt2dbbfiebn.html

[R50] awk 求和
来源：http://dali.9152youxi.cn/Article/details/gt2hazqbkhz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cqqwz.cn/Article/details/gt2nukklkol.html

[R51] 排序去重取前几
来源：http://dali.xinyue.icu/Article/details/gt2jbogvfgy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.aibaodan.cn/Article/details/gt2nqspzfrc.html

[R52] 统计行数
来源：http://dali.mhx1999.top/Article/details/gt2ssrlynky.html

wc -l a.txt
来源：http://dali.xziqi.cn/Article/details/gt2brrigjha.html

[R53] 查看文件头与实时尾
来源：http://dali.ivvv.top/Article/details/gt2helthvqg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.daria6918.cn/Article/details/gt2djlullip.html

[R54] 比较两个文件
来源：http://dali.xuanzx.com/Article/details/gt2kplnmtur.html

diff a.txt b.txt
来源：http://dali.aizwys.cn/Article/details/gt2mifrxbbw.html

[R55] 压缩与解压
来源：http://dali.0kj1m.cn/Article/details/gt2xfwyvxmi.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.mhx1999.top/Article/details/gt2rrrqirmq.html

[R56] 远程拷贝
来源：http://dali.gaohongyu789.top/Article/details/gt2unwbvbub.html

scp file user@host:/path/
来源：http://dali.nanxinkj.top/Article/details/gt2unhzrxpl.html

[R57] 远程执行命令
来源：http://dali.feifeiyinyue.top/Article/details/gt2ukvmieut.html

ssh user@host 'uptime'
来源：http://dali.jqgufenzy.top/Article/details/gt2wxqzglll.html

[R58] 下载文件
来源：http://dali.jqgufenzy.top/Article/details/gt2gqzhypos.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.jiagoushi.top/Article/details/gt2bqompxuc.html

[R59] 发 POST JSON
来源：http://dali.pycfn.com/Article/details/gt2qscdpxsn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sgpioijl.html

[R60] 只看 HTTP 状态码
来源：http://dali.jqgufenzy.top/Article/details/gt2iunfnxdz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cashguo.top/Article/details/gt2klgklzfk.html

[R61] 磁盘占用
来源：http://dali.yvedp.cn/Article/details/gt2yukdpjnm.html

df -h;  du -sh *
来源：http://dali.ydzc1.top/Article/details/gt2dvvxjkiy.html

[R62] 找最占空间的文件
来源：http://dali.xinyue.icu/Article/details/gt2fiazmyuw.html

du -ah . | sort -rh | head -10
来源：http://dali.daria6918.cn/Article/details/gt2hfibsbdm.html

[R63] 内存与进程
来源：http://dali.iojbl.cn/Article/details/gt2aimgshwl.html

free -h;  ps aux | grep nginx
来源：http://dali.aizwys.cn/Article/details/gt2abuflida.html

[R64] 结束进程
来源：http://dali.jqgfzy.top/Article/details/gt2jxaesmkb.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhongyouzk.top/Article/details/gt2rujxcwrp.html

[R65] 查看端口占用
来源：http://dali.cheryme.top/Article/details/gt2usyvsiht.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sysykeji.top/Article/details/gt2qcdhifec.html

[R66] 定时任务
来源：http://dali.smart0.xyz/Article/details/gt2cphotyln.html

crontab -e;  crontab -l
来源：http://dali.yonumen.top/Article/details/gt2iqpcuqxb.html

[R67] 生成随机十六进制串
来源：http://dali.ehwqpu.com/Article/details/gt2xepuuwqw.html

openssl rand -hex 16
来源：http://dali.xinyue.icu/Article/details/gt2ckjkxmvo.html

[R68] 计算文件校验值
来源：http://dali.yonumen.top/Article/details/gt2eoldirrw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cucudq.cn/Article/details/gt2mhbxxbyt.html

[R69] 生成随机密码
来源：http://dali.yangfankeji.com/Article/details/gt2baxinkmd.html

head -c 16 /dev/urandom | base64
来源：http://dali.0kj1m.cn/Article/details/gt2timjskgw.html

[R70] 时间戳与互转
来源：http://dali.gzhubu.top/Article/details/gt2jbbsltcf.html

date +%s;  date -d @1700000000
来源：http://dali.9152youxi.cn/Article/details/gt2dzylbeqh.html

[R71] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gt2ghvwokbv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.sxryk.cn/Article/details/gt2cjypitot.html

[R72] 等待端口就绪
来源：http://dali.redwolf501.top/Article/details/gt2pdfoqhno.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xuanzx.com/Article/details/gt2hsqzlnkl.html

[R73] 分割大日志
来源：http://dali.yangfankeji.com/Article/details/gt2ydccbzlb.html

split -l 1000 big.log part_
来源：http://dali.yj202588.top/Article/details/gt2gfwbrquw.html

[R74] 批量重命名
来源：http://dali.0kj1m.cn/Article/details/gt2rvaxywek.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.yongpay.top/Article/details/gt2edacwpch.html

[R75] 导出环境变量
来源：http://dali.mhx1999.top/Article/details/gt2mgzlqyno.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.sysykeji.top/Article/details/gt2tuntueun.html

[R76] 使用临时文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2ufvcrust.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.bjfxy.top/Article/details/gt2qncgngki.html

[R77] 读取用户输入
来源：http://dali.ehwqpu.com/Article/details/gt2fyznyhnw.html

read -rp "请输入: " ans
来源：http://dali.xylfe.cn/Article/details/gt2emzfqmzj.html

[R78] 交互式菜单
来源：http://dali.jqgufenzy.top/Article/details/gt2fkfbtvzg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jiagoushi.top/Article/details/gt2rlzuaqor.html

[R79] 解析命令行选项
来源：http://dali.wangshuangyany.cn/Article/details/gt2siyuoejz.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yvedp.cn/Article/details/gt2dmxtvjxi.html

[R80] 查看脚本执行耗时
来源：http://dali.hammf.cn/Article/details/gt2bfkktnkd.html

time ./run.sh
来源：http://dali.hnqzz.top/Article/details/gt2pgqhxvag.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2ojegjcqc.html

S. C / C++ 专题
来源：http://dali.daxiang520.top/Article/details/gt2utkinnjr.html

================================================================================
来源：http://dali.jyoumei.cn/Article/details/gt2tkxrjcnr.html

[S01] C：Hello World
来源：http://dali.kuanghao11.cn/Article/details/gt2dwitkhdk.html

#include <stdio.h>
来源：http://dali.iojbl.cn/Article/details/gt2epjhhfqm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jinqigfzy.top/Article/details/gt2jwlmuscm.html

[S02] C：变量与格式化输出
来源：http://dali.haohaochexian.top/Article/details/gt2uxaspmpa.html

int a = 10; printf("%d\n", a);
来源：http://dali.daria6918.cn/Article/details/gt2gmbkmofc.html

[S03] C：读入整数
来源：http://dali.aibaodan.cn/Article/details/gt2fkpogkum.html

int x; scanf("%d", &x);
来源：http://dali.tian-w.cn/Article/details/gt2htxckbgn.html

[S04] C：字符串复制
来源：http://dali.jqgfzy.top/Article/details/gt2gploexuj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.hfpthk.cn/Article/details/gt2zpxgtllz.html

[S05] C：字符串长度
来源：http://dali.yonumen.top/Article/details/gt2znfqwjly.html

strlen(s)
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2vmvsjrrb.html

[S06] C：字符串比较
来源：http://dali.aizwys.cn/Article/details/gt2iwaaipbd.html

strcmp(a, b) == 0
来源：http://dali.chenlongwang.top/Article/details/gt2cwezsget.html

[S07] C：数组遍历求和
来源：http://dali.fengsongda.top/Article/details/gt2zixyirrb.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.jianghu66.top/Article/details/gt2gwoigvix.html

[S08] C：动态内存分配与释放
来源：http://dali.yuxming.cn/Article/details/gt2dlnbxksg.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.sxryk.cn/Article/details/gt2wbgvvfon.html

[S09] C：结构体定义与初始化
来源：http://dali.redwolf501.top/Article/details/gt2swyizbhf.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yueranfly.top/Article/details/gt2rporvjwu.html

[S10] C：指针与解引用
来源：http://dali.mhx1999.top/Article/details/gt2vzagvnnd.html

int *p = &a;  *p = 5;
来源：http://dali.birdmap.top/Article/details/gt2drbegwwd.html

[S11] C：逐行读文件
来源：http://dali.pycfn.com/Article/details/gt2mnvmsdfz.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.pycfn.com/Article/details/gt2esxwllbx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.feifeiyinyue.top/Article/details/gt2jxedsujd.html

fclose(f);
来源：http://dali.cqqwz.cn/Article/details/gt2fhducqno.html

[S12] C：写文件
来源：http://dali.aibaodan.cn/Article/details/gt2rzvawwxf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2dfjtpkxp.html

[S13] C：宏定义
来源：http://dali.gzhubu.top/Article/details/gt2dkhldutv.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.xziqi.cn/Article/details/gt2madfdvnv.html

[S14] C：枚举
来源：http://dali.iojbl.cn/Article/details/gt2jwslflip.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.jinghuilouyu.cn/Article/details/gt2yysonlee.html

[S15] C：类型转换
来源：http://dali.ivvv.top/Article/details/gt2rbqyifcc.html

(double) a / b
来源：http://dali.chenjidiqi.icu/Article/details/gt2rmhoqupd.html

[S16] C：位操作置位
来源：http://dali.jinghuilouyu.cn/Article/details/gt2fynsbkev.html

x |= (1 << 3);
来源：http://dali.mhx1999.top/Article/details/gt2ukmdeozj.html

[S17] C：安全拼接字符串
来源：http://dali.vqdsnc.cn/Article/details/gt2nsakhmdz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2sditqazd.html

[S18] C：命令行参数
来源：http://dali.hfpthk.cn/Article/details/gt2pmliplbr.html

int main(int argc, char **argv)
来源：http://dali.gzhubu.top/Article/details/gt2fqrvvucz.html

[S19] C：快速排序
来源：http://dali.c1oappe.top/Article/details/gt2qrejphvy.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.gzhubu.top/Article/details/gt2hgjhcpnv.html

[S20] C：二分查找
来源：http://dali.hnxiangtu.top/Article/details/gt2jhquteiz.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.shuidangran.top/Article/details/gt2xgpehqoh.html

[S21] C：字符类别判断
来源：http://dali.wangshuangyany.cn/Article/details/gt2saavpeoz.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.hfpthk.cn/Article/details/gt2mhcvjdta.html

[S22] C：字符串转数字
来源：http://dali.ydzc1.top/Article/details/gt2nabxtvfn.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ppuxaelx.html

[S23] C：随机数
来源：http://dali.nanxuanxn.top/Article/details/gt2ngmwzemm.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cqqwz.cn/Article/details/gt2urhmddib.html

[S24] C：获取本地时间
来源：http://dali.zhoulong.xyz/Article/details/gt2rogbxpwo.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.chenzaomai.com/Article/details/gt2rgltciog.html

[S25] C：内存拷贝
来源：http://dali.sxryk.cn/Article/details/gt2iuibjyzx.html

memcpy(dst, src, n);
来源：http://dali.ydzc1.top/Article/details/gt2ikqbrutz.html

[S26] C：内存清零
来源：http://dali.kuanghao11.cn/Article/details/gt2ifdgcryo.html

memset(a, 0, sizeof a);
来源：http://dali.haohaochexian.top/Article/details/gt2nbdyzpnj.html

[S27] C：定义常量
来源：http://dali.aibaodan.cn/Article/details/gt2bbaycevb.html

const double PI = 3.14159;
来源：http://dali.tanke756.top/Article/details/gt2flbyyvqi.html

[S28] C：静态变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2rdozevvd.html

static int counter = 0;
来源：http://dali.iojbl.cn/Article/details/gt2mjkqfbrs.html

[S29] C：变参函数
来源：http://dali.havefunace.top/Article/details/gt2xyuijrqt.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.cqqwz.cn/Article/details/gt2rcmhqhxq.html

[S30] C：头文件保护
来源：http://dali.dianchejie.cn/Article/details/gt2xaiqtmfo.html

#ifndef X_H
来源：http://dali.havefunace.top/Article/details/gt2nbljjsiu.html

#define X_H
来源：http://dali.jinqigufen.top/Article/details/gt2dxlozgda.html

#endif
来源：http://dali.ehwqpu.com/Article/details/gt2ibovzebu.html

[S31] C++：Hello World
来源：http://dali.sysykeji.top/Article/details/gt2vowhpdsz.html

#include <iostream>
来源：http://dali.sweek.top/Article/details/gt2oprykmro.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.fzhhl.top/Article/details/gt2weotztvf.html

[S32] C++：字符串
来源：http://dali.havefunace.top/Article/details/gt2zkdvlliw.html

std::string s = "hi";  s += "!";
来源：http://dali.cheryme.top/Article/details/gt2ythevgdw.html

[S33] C++：vector 增删
来源：http://dali.jianghu66.top/Article/details/gt2pclgxlmm.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.mhx1999.top/Article/details/gt2xguzepbo.html

[S34] C++：遍历 vector
来源：http://dali.guowangkeji.top/Article/details/gt2xnnynbwi.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.xziqi.cn/Article/details/gt2nnjrjqes.html

[S35] C++：map
来源：http://dali.pycfn.com/Article/details/gt2xwervouh.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gt2nqzgtkuw.html

[S36] C++：unordered_map
来源：http://dali.hongshengwenyu.top/Article/details/gt2dqsezsko.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.quarkkingdee.top/Article/details/gt2sosfdzqs.html

[S37] C++：set
来源：http://dali.yj20258888.top/Article/details/gt2noisxete.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.guowangkeji.top/Article/details/gt2sdblnrym.html

[S38] C++：排序
来源：http://dali.yuxming.cn/Article/details/gt2wcngekes.html

std::sort(v.begin(), v.end());
来源：http://dali.nanxuanxn.top/Article/details/gt2rpjtvcpk.html

[S39] C++：自定义比较器排序
来源：http://dali.ybcxt.top/Article/details/gt2tgfvivfj.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.chenjidiqi.icu/Article/details/gt2tfhxtpso.html

[S40] C++：查找元素
来源：http://dali.chenzaomai.com/Article/details/gt2grkcjgpx.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.vqdsnc.cn/Article/details/gt2ktxmpyft.html

[S41] C++：类与构造函数
来源：http://dali.aibaodan.cn/Article/details/gt2bccmhcdi.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2jrurzicg.html

[S42] C++：继承与虚函数
来源：http://dali.yanxiufei.cn/Article/details/gt2hnuvykls.html

class B : public Base { public: void f() override {} };
来源：http://dali.snrcjt.cn/Article/details/gt2evawqbgz.html

[S43] C++：智能指针
来源：http://dali.jiagoushi.top/Article/details/gt2gbalwpsm.html

auto p = std::make_unique<int>(5);
来源：http://dali.yj20258888.top/Article/details/gt2ayzxdjzy.html

[S44] C++：引用传参
来源：http://dali.xinyue.icu/Article/details/gt2hlyslbiv.html

void inc(int &x) { ++x; }
来源：http://dali.gzhubu.top/Article/details/gt2ougffcxs.html

[S45] C++：lambda
来源：http://dali.meibo888.top/Article/details/gt2zcmbsxtt.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.daxiang520.top/Article/details/gt2qeqeawpg.html

[S46] C++：函数模板
来源：http://dali.xziqi.cn/Article/details/gt2irfpvqcg.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bofwxdcf.html

[S47] C++：结构化绑定遍历
来源：http://dali.yvedp.cn/Article/details/gt2oizarguj.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.yuxming.cn/Article/details/gt2zechesuj.html

[S48] C++：逐行读文件
来源：http://dali.tanke756.top/Article/details/gt2mcjlneca.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.wangshuangyany.cn/Article/details/gt2rbhzkvwm.html

while (std::getline(in, line)) { }
来源：http://dali.xuetiantiany.cn/Article/details/gt2izjwbqda.html

[S49] C++：写文件
来源：http://dali.ppjwa.cn/Article/details/gt2oleesybs.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.cheryme.top/Article/details/gt2kfhfvrnz.html

[S50] C++：格式化数字
来源：http://dali.daria6918.cn/Article/details/gt2avdawvbp.html

std::ostringstream os;  os << std::fixed << std::setprecision(2) << 3.14159;
来源：http://dali.chenlongwang.top/Article/details/gt2rlipdeej.html

[S51] C++：显式类型转换
来源：http://dali.jinqigufen.top/Article/details/gt2dktgwces.html

static_cast<double>(a) / b
来源：http://dali.daria6918.cn/Article/details/gt2bqallivc.html

[S52] C++：const 与 noexcept
来源：http://dali.jiagoushi.top/Article/details/gt2fxxqbpgv.html

int size() const noexcept { return n_; }
来源：http://dali.gaohongyu789.top/Article/details/gt2rvqmqqas.html

[S53] C++：移动语义
来源：http://dali.dianchejie.cn/Article/details/gt2thimgqyw.html

std::vector<int> w = std::move(v);
来源：http://dali.guowangkeji.top/Article/details/gt2aiqbcfmy.html

[S54] C++：异常处理
来源：http://dali.vqdsnc.cn/Article/details/gt2asweordb.html


<!-- 参考信息 -->