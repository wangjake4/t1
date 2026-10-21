代发 wailian999

[Q80] 字符串截取
来源：http://dali.sweek.top/Article/details/gtjsfgdogd.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.tanke756.top/Article/details/gthvmtmdbh.html

[Q81] 字符串替换
来源：http://dali.nanxuanxn.top/Article/details/gtqwdyxfvy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtfheqcxdr.html

[Q82] 字符长度与字节长度
来源：http://dali.xuanzx.com/Article/details/gtxiabppyq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtxjlcghmx.html

[Q83] 大小写转换
来源：http://dali.gotoacloud.top/Article/details/gtxkuodbdi.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtacxydarf.html

[Q84] 去除首尾空格
来源：http://dali.jinqigufen.top/Article/details/gtztwydddq.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtxpzsxsgn.html

[Q85] 数值取整
来源：http://dali.9152youxi.cn/Article/details/gtzqsbwvvl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hammf.cn/Article/details/gtwgxjhzdq.html

[Q86] 读取 JSON 字段
来源：http://dali.fengsongda.top/Article/details/gtbapueism.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hongshengwenyu.top/Article/details/gtckawjtui.html

[Q87] JSON 字段做条件
来源：http://dali.yuanzhike.top/Article/details/gtkjxkbmja.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jyoumei.cn/Article/details/gtejdojovn.html

[Q88] 行转列（条件聚合）
来源：http://dali.yangfankeji.com/Article/details/gtgafbbgga.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jinqigufen.top/Article/details/gtlbofwbnr.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.mhx1999.top/Article/details/gtwiwcwqtr.html

[Q89] 判断表是否存在
来源：http://dali.jinqigufen.top/Article/details/gtlikxoijd.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.birdmap.top/Article/details/gtjtwpndmx.html

[Q90] 生成序号列
来源：http://dali.xuanzx.com/Article/details/gtgvqdthce.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.chenzaomai.com/Article/details/gtwwgnlqvr.html

================================================================================
来源：http://dali.zhiwuduotai.top/Article/details/gtpnnrehhs.html

R. Bash 专题
来源：http://dali.fengsongda.top/Article/details/gtyfaoeffh.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtduyfwwzb.html

[R01] shebang 与严格模式
来源：http://dali.316326.xyz/Article/details/gtqdiaxvrq.html

#!/usr/bin/env bash
来源：http://dali.yvedp.cn/Article/details/gtreicydwz.html

set -euo pipefail
来源：http://dali.redwolf501.top/Article/details/gtfysypsmb.html

[R02] 变量赋值与使用
来源：http://dali.fengsongda.top/Article/details/gtezmaeciq.html

name="Tom"; echo "$name"
来源：http://dali.daria6918.cn/Article/details/gtfhqmassc.html

[R03] 只读变量
来源：http://dali.nwbrower.top/Article/details/gtlkwqpgqc.html

readonly PI=3.14
来源：http://dali.yueranfly.top/Article/details/gtrgdflmpr.html

[R04] 位置参数
来源：http://dali.yuxming.cn/Article/details/gtolwdoybr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shuidangran.top/Article/details/gtygbcttcy.html

[R05] 参数默认值
来源：http://dali.chenjidiqi.icu/Article/details/gteyaejrse.html

name="${1:-default}"
来源：http://dali.zhiwuduotai.top/Article/details/gtpgpklqtj.html

[R06] 判断命令是否存在
来源：http://dali.dianchejie.cn/Article/details/gtgedkmqnw.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.wangdashe.top/Article/details/gtjyihhihk.html

[R07] if 判断文件
来源：http://dali.yuanzhike.top/Article/details/gtzhqogxaj.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.tanke756.top/Article/details/gtyxlszwwt.html

[R08] 数值比较
来源：http://dali.fzhhl.top/Article/details/gtsmijskaa.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.havefunace.top/Article/details/gtrqzbufrt.html

[R09] 字符串比较
来源：http://dali.jqgufenzy.top/Article/details/gtdbolhmvl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj20258888.top/Article/details/gtjcvbtoyp.html

[R10] 正则匹配
来源：http://dali.wangshuangyany.cn/Article/details/gttsicehsp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.0kj1m.cn/Article/details/gtcdktixqi.html

[R11] case 多分支
来源：http://dali.hnqzz.top/Article/details/gtvchhwozk.html

case "$1" in
来源：http://dali.yj202588.top/Article/details/gtldaxwezz.html

start) echo "启动" ;;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtckbaragw.html

stop)  echo "停止" ;;
来源：http://dali.ehwqpu.com/Article/details/gtwfujgdfu.html

*)     echo "未知命令" ;;
来源：http://dali.snrcjt.cn/Article/details/gtfjlanwcu.html

esac
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbmipykpe.html

[R12] for 遍历文件
来源：http://dali.daria6918.cn/Article/details/gtayqdnvkf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cashguo.top/Article/details/gtfqcybhec.html

[R13] for 计数循环
来源：http://dali.mhx1999.top/Article/details/gtraxcvfxj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.tian-w.cn/Article/details/gtyyocxsgv.html

[R14] C 风格 for
来源：http://dali.bjfxy.top/Article/details/gtkkcjjmun.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gaohongyu789.top/Article/details/gtjkvwnduk.html

[R15] while 逐行读文件
来源：http://dali.chenlongwang.top/Article/details/gtubkkbkrc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.havefunace.top/Article/details/gteoaatzwr.html

[R16] until 等待条件
来源：http://dali.sxryk.cn/Article/details/gtlzhgxzbf.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cdnleiting.top/Article/details/gtoplsxdqj.html

[R17] 数组定义与取值
来源：http://dali.pycfn.com/Article/details/gtctlcaplh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.cdnleiting.top/Article/details/gtdthzizut.html

[R18] 遍历数组
来源：http://dali.xuanzx.com/Article/details/gtqfcidlvy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.guowangkeji.top/Article/details/gtdoafphzv.html

[R19] 数组长度
来源：http://dali.xinyue.icu/Article/details/gtmxuoeobs.html

echo "${#arr[@]}"
来源：http://dali.hfpthk.cn/Article/details/gtpsmqgkec.html

[R20] 关联数组（字典）
来源：http://dali.daxiang520.top/Article/details/gthpndbibs.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gtbowiwshd.html

[R21] 字符串长度
来源：http://dali.hfpthk.cn/Article/details/gtrzcmfbla.html

echo "${#s}"
来源：http://dali.ybcxt.top/Article/details/gthndgtaur.html

[R22] 截取子串
来源：http://dali.smart0.xyz/Article/details/gtkuozstet.html

echo "${s:0:5}"
来源：http://dali.hysaishi.cn/Article/details/gthybkwwvc.html

[R23] 字符串替换
来源：http://dali.nwbrower.top/Article/details/gtgkjxzilh.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.aizwys.cn/Article/details/gtxyllxbid.html

[R24] 大小写转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcnwmfxlw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jqgufenzy.top/Article/details/gtuiubvbhr.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhongyouzk.top/Article/details/gtzvxgovxi.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ehwqpu.com/Article/details/gtlhponevy.html

[R26] 命令替换
来源：http://dali.sxryk.cn/Article/details/gtjoemshbx.html

now=$(date +%F); echo "$now"
来源：http://dali.yongpay.top/Article/details/gtyarcxzcv.html

[R27] 算术展开
来源：http://dali.0kj1m.cn/Article/details/gtkonoqtpa.html

echo $((1 + 2 * 3))
来源：http://dali.feifeiyinyue.top/Article/details/gtbvtwpzls.html

[R28] 浮点运算
来源：http://dali.havefunace.top/Article/details/gtqdelupxp.html

echo "scale=2; 10/3" | bc
来源：http://dali.kuanghao11.cn/Article/details/gtpddjhyto.html

[R29] 定义函数
来源：http://dali.zhiwuduotai.top/Article/details/gtfiudewrk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.smart0.xyz/Article/details/gtvdxcsbjb.html

[R30] 函数返回状态码
来源：http://dali.meibo888.top/Article/details/gtmkneiasq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yj20258888.top/Article/details/gthgiymscg.html

[R31] 局部变量
来源：http://dali.birdmap.top/Article/details/gtiasxxupj.html

f() { local x=1; echo "$x"; }
来源：http://dali.tian-w.cn/Article/details/gtvigvtkpp.html

[R32] 参数个数校验
来源：http://dali.0kj1m.cn/Article/details/gtntkprqfz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jinqigfzy.top/Article/details/gtgyrrulvu.html

[R33] 捕获错误并提示行号
来源：http://dali.yueranfly.top/Article/details/gtkdtpsnap.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.svipenyu.cn/Article/details/gtzslodydp.html

[R34] 退出时清理
来源：http://dali.daria6918.cn/Article/details/gtyfbwhpfo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hywenlv.cn/Article/details/gtuxunzbkt.html

[R35] 后台执行并等待
来源：http://dali.hongshengwenyu.top/Article/details/gtzsaojdsd.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.chenlongwang.top/Article/details/gttufdcqxb.html

[R36] 并发执行多个任务
来源：http://dali.ehwqpu.com/Article/details/gtygkdbfss.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.guannengcc.top/Article/details/gtdmuohhee.html

[R37] 把输出赋给变量
来源：http://dali.yj20258.top/Article/details/gtpnyypsgw.html

files=$(ls -1)
来源：http://dali.xziqi.cn/Article/details/gtqgetlsas.html

[R38] 管道串联
来源：http://dali.sxryk.cn/Article/details/gttgsknggv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.feifeiyinyue.top/Article/details/gtxkkaqvye.html

[R39] 重定向标准输出与错误
来源：http://dali.fengsongda.top/Article/details/gtbavzhtpb.html

cmd > out.log 2>&1
来源：http://dali.hywenlv.cn/Article/details/gtwskygimj.html

[R40] 追加写日志
来源：http://dali.jqgufenzy.top/Article/details/gthkkistrv.html

echo "log" >> out.log
来源：http://dali.shanyushiyangkeji.top/Article/details/gtawnwgkbj.html

[R41] 丢弃输出
来源：http://dali.smart0.xyz/Article/details/gtuakqebrk.html

cmd >/dev/null 2>&1
来源：http://dali.mhx1999.top/Article/details/gtptwsodvw.html

[R42] 输入重定向
来源：http://dali.mhx1999.top/Article/details/gtljkyunpc.html

wc -l < a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtsfiveerq.html

[R43] 按名字查找文件
来源：http://dali.yonumen.top/Article/details/gtfqjxetuh.html

find . -name "*.log" -type f
来源：http://dali.hysaishi.cn/Article/details/gtbqjswoyi.html

[R44] 按修改时间查找
来源：http://dali.meibo888.top/Article/details/gtxjwnhtsy.html

find . -mtime -7 -type f
来源：http://dali.yanxiufei.cn/Article/details/gtkeiryuzs.html

[R45] 批量删除
来源：http://dali.316326.xyz/Article/details/gtrrhrcozh.html

find . -name "*.tmp" -delete
来源：http://dali.aizwys.cn/Article/details/gtvcrnolqo.html

[R46] 递归替换文件内容
来源：http://dali.yj20258888.top/Article/details/gtpzrteyqq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.dianchejie.cn/Article/details/gtvdyyolup.html

[R47] sed 单行替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcquxreyt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.vqdsnc.cn/Article/details/gtrwpkxhor.html

[R48] awk 取指定列
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwkgerlue.html

awk '{print $1, $3}' a.txt
来源：http://dali.hammf.cn/Article/details/gtrzwisctm.html

[R49] awk 带条件
来源：http://dali.hywenlv.cn/Article/details/gtktaqddox.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yueranfly.top/Article/details/gtyuzgiffy.html

[R50] awk 求和
来源：http://dali.guannengcc.top/Article/details/gthknzovdg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.redwolf501.top/Article/details/gtgpajmjhh.html

[R51] 排序去重取前几
来源：http://dali.xylfe.cn/Article/details/gtultphaum.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xuetiantiany.cn/Article/details/gtdqyykdhc.html

[R52] 统计行数
来源：http://dali.daxiang520.top/Article/details/gtpltuuiyd.html

wc -l a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtwlilhgrr.html

[R53] 查看文件头与实时尾
来源：http://dali.pycfn.com/Article/details/gtpzrgmkck.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shangyingyoupin.top/Article/details/gtumlkoqex.html

[R54] 比较两个文件
来源：http://dali.hnqzz.top/Article/details/gtsondjaeo.html

diff a.txt b.txt
来源：http://dali.shuidangran.top/Article/details/gtkgduxinl.html

[R55] 压缩与解压
来源：http://dali.hnxiangtu.top/Article/details/gtcdxfwhyl.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.redwolf501.top/Article/details/gtgsdjhbwd.html

[R56] 远程拷贝
来源：http://dali.sysykeji.top/Article/details/gtsxulhoab.html

scp file user@host:/path/
来源：http://dali.zhixingplan.top/Article/details/gtjteoxyzs.html

[R57] 远程执行命令
来源：http://dali.hnxiangtu.top/Article/details/gtzbyzwuaw.html

ssh user@host 'uptime'
来源：http://dali.andypj.xyz/Article/details/gtogzopmji.html

[R58] 下载文件
来源：http://dali.xylfe.cn/Article/details/gtwikicqhv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cdnleiting.top/Article/details/gtwfnstnzj.html

[R59] 发 POST JSON
来源：http://dali.yonumen.top/Article/details/gtuwnpuzvj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.fzhhl.top/Article/details/gtureywxxq.html

[R60] 只看 HTTP 状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwusjcyeo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.andypj.xyz/Article/details/gtipwcamdd.html

[R61] 磁盘占用
来源：http://dali.hnqzz.top/Article/details/gtavsfcjny.html

df -h;  du -sh *
来源：http://dali.yanxiufei.cn/Article/details/gtjcrxvfld.html

[R62] 找最占空间的文件
来源：http://dali.zhongyouzk.top/Article/details/gtayhssnco.html

du -ah . | sort -rh | head -10
来源：http://dali.vqdsnc.cn/Article/details/gtkzsxpevj.html

[R63] 内存与进程
来源：http://dali.zdqjudy.top/Article/details/gtzupeijnz.html

free -h;  ps aux | grep nginx
来源：http://dali.iojbl.cn/Article/details/gtbnpqxzes.html

[R64] 结束进程
来源：http://dali.yuxming.cn/Article/details/gtqwyfvrgq.html

kill -9 $(pgrep -f app.py)
来源：http://dali.haohaochexian.top/Article/details/gtgamgwsbu.html

[R65] 查看端口占用
来源：http://dali.mhx1999.top/Article/details/gtawicxeef.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.fzhhl.top/Article/details/gtnopycvum.html

[R66] 定时任务
来源：http://dali.daria6918.cn/Article/details/gtnnspxpls.html

crontab -e;  crontab -l
来源：http://dali.fzhhl.top/Article/details/gtnngiaosf.html

[R67] 生成随机十六进制串
来源：http://dali.guowangkeji.top/Article/details/gtxzevbbaz.html

openssl rand -hex 16
来源：http://dali.yj20258888.top/Article/details/gtzxchgddz.html

[R68] 计算文件校验值
来源：http://dali.zycfv.cn/Article/details/gtcpatsqdm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.aibaodan.cn/Article/details/gtgcluanfh.html

[R69] 生成随机密码
来源：http://dali.yueranfly.top/Article/details/gtgruahplv.html

head -c 16 /dev/urandom | base64
来源：http://dali.0kj1m.cn/Article/details/gtzzoyorvj.html

[R70] 时间戳与互转
来源：http://dali.gogol.net.cn/Article/details/gtltxhwhfk.html

date +%s;  date -d @1700000000
来源：http://dali.xziqi.cn/Article/details/gtrhyaldtb.html

[R71] 日期格式化
来源：http://dali.snrcjt.cn/Article/details/gtjjzhaect.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jianghu66.top/Article/details/gthgegftvi.html

[R72] 等待端口就绪
来源：http://dali.cdnleiting.top/Article/details/gtazalehau.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.jinqigufen.top/Article/details/gtnoztubei.html

[R73] 分割大日志
来源：http://dali.ywan-chungtsiang.top/Article/details/gteuhhljfs.html

split -l 1000 big.log part_
来源：http://dali.316326.xyz/Article/details/gtgdgckxsg.html

[R74] 批量重命名
来源：http://dali.shanyushiyangkeji.top/Article/details/gtclidfyax.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtffiyuixu.html

[R75] 导出环境变量
来源：http://dali.ydzc1.top/Article/details/gtlmimtlxv.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gtmvtnxygv.html

[R76] 使用临时文件
来源：http://dali.xuetiantiany.cn/Article/details/gtfuhvlkos.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.pengpengdd.cyou/Article/details/gtxbdauziv.html

[R77] 读取用户输入
来源：http://dali.aibaodan.cn/Article/details/gteudcxmwd.html

read -rp "请输入: " ans
来源：http://dali.vqdsnc.cn/Article/details/gtzdkjsfwz.html

[R78] 交互式菜单
来源：http://dali.daxiang520.top/Article/details/gtjxbtdjno.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.chenjidiqi.icu/Article/details/gtckfxasbj.html

[R79] 解析命令行选项
来源：http://dali.chenzaomai.com/Article/details/gtffybjojx.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.tanke756.top/Article/details/gtyiajuysj.html

[R80] 查看脚本执行耗时
来源：http://dali.yueranfly.top/Article/details/gttswhmpbh.html

time ./run.sh
来源：http://dali.yonumen.top/Article/details/gtccjqghvy.html

================================================================================
来源：http://dali.cqqwz.cn/Article/details/gtlwhxmvso.html

S. C / C++ 专题
来源：http://dali.shanyushiyangtech.top/Article/details/gtvuzatglj.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtmgdqdwnd.html

[S01] C：Hello World
来源：http://dali.cheryme.top/Article/details/gtbwcbgznm.html

#include <stdio.h>
来源：http://dali.redwolf501.top/Article/details/gtcrtuartl.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yuxming.cn/Article/details/gtlcodruzz.html

[S02] C：变量与格式化输出
来源：http://dali.haohaochexian.top/Article/details/gtajbstanp.html

int a = 10; printf("%d\n", a);
来源：http://dali.ppjwa.cn/Article/details/gtqcrgilbr.html

[S03] C：读入整数
来源：http://dali.316326.xyz/Article/details/gtuaqwzwis.html

int x; scanf("%d", &x);
来源：http://dali.cheryme.top/Article/details/gtmmlagiee.html

[S04] C：字符串复制
来源：http://dali.yueranfly.top/Article/details/gtzlbhossm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.shanyushiyangtech.top/Article/details/gteffpwkxm.html

[S05] C：字符串长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtebpbdrhe.html

strlen(s)
来源：http://dali.wangdashe.top/Article/details/gtmhqrhqcl.html

[S06] C：字符串比较
来源：http://dali.zhixingplan.top/Article/details/gtobxxznnv.html

strcmp(a, b) == 0
来源：http://dali.hnqzz.top/Article/details/gtyzwppcts.html

[S07] C：数组遍历求和
来源：http://dali.gogol.net.cn/Article/details/gtklmvkbvw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.kuanghao11.cn/Article/details/gtqpvdfvxp.html

[S08] C：动态内存分配与释放
来源：http://dali.redwolf501.top/Article/details/gtfaivybel.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.nanxuanxn.top/Article/details/gtcxkfnkvn.html

[S09] C：结构体定义与初始化
来源：http://dali.sxryk.cn/Article/details/gtgegmjnlt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.yanxiufei.cn/Article/details/gtslgthflu.html

[S10] C：指针与解引用
来源：http://dali.jlsjyb.cn/Article/details/gtwspedpxr.html

int *p = &a;  *p = 5;
来源：http://dali.ivvv.top/Article/details/gtqpomcuty.html

[S11] C：逐行读文件
来源：http://dali.xuanzx.com/Article/details/gtxnwsxnmh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.jinghuilouyu.cn/Article/details/gtkjrpeogb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.yanxiufei.cn/Article/details/gtofvtyabk.html

fclose(f);
来源：http://dali.cashguo.top/Article/details/gtbxwpwvvn.html

[S12] C：写文件
来源：http://dali.zhengqikj.top/Article/details/gtokkasnxh.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.pengpengdd.cyou/Article/details/gtimmrsljp.html

[S13] C：宏定义
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnlfivmha.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.snrcjt.cn/Article/details/gtzkboqyen.html

[S14] C：枚举
来源：http://dali.yuanzhike.top/Article/details/gttrqvirnr.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.sufxvd.cn/Article/details/gtxhlibzwx.html

[S15] C：类型转换
来源：http://dali.xinyue.icu/Article/details/gtacctimus.html

(double) a / b
来源：http://dali.yj202588.top/Article/details/gtjuncfwwq.html

[S16] C：位操作置位
来源：http://dali.0kj1m.cn/Article/details/gtbyltgkxn.html

x |= (1 << 3);
来源：http://dali.sysykeji.top/Article/details/gtjfpldsgs.html

[S17] C：安全拼接字符串
来源：http://dali.0kj1m.cn/Article/details/gtozdkvegh.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.sysykeji.top/Article/details/gtgjifstri.html

[S18] C：命令行参数
来源：http://dali.ivvv.top/Article/details/gtxryglexy.html

int main(int argc, char **argv)
来源：http://dali.guannengcc.top/Article/details/gtfbyoolfc.html

[S19] C：快速排序
来源：http://dali.yongpay.top/Article/details/gtomjfaeyq.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.guannengcc.top/Article/details/gtcvsikhfu.html

[S20] C：二分查找
来源：http://dali.hfpthk.cn/Article/details/gtuukjzqxa.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.xuetiantiany.cn/Article/details/gtynlyvzmh.html

[S21] C：字符类别判断
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtsjwbryef.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.redwolf501.top/Article/details/gtarqflfws.html

[S22] C：字符串转数字
来源：http://dali.meibo888.top/Article/details/gtsimfuwxp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.kuanghao11.cn/Article/details/gthknnrdjt.html

[S23] C：随机数
来源：http://dali.yvedp.cn/Article/details/gtpclpliss.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.ehwqpu.com/Article/details/gtzhkxfvfs.html

[S24] C：获取本地时间
来源：http://dali.ybcxt.top/Article/details/gtesdnyzwg.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.chenzaomai.com/Article/details/gtfrblnwhy.html

[S25] C：内存拷贝
来源：http://dali.shzxlz.cn/Article/details/gtrrhbnjre.html

memcpy(dst, src, n);
来源：http://dali.meibo888.top/Article/details/gtjchvbmel.html

[S26] C：内存清零
来源：http://dali.sxryk.cn/Article/details/gtbdmfodct.html

memset(a, 0, sizeof a);
来源：http://dali.sysykeji.top/Article/details/gtqfdrlmtx.html

[S27] C：定义常量
来源：http://dali.hywenlv.cn/Article/details/gtamddgqxw.html

const double PI = 3.14159;
来源：http://dali.redwolf501.top/Article/details/gtcbasfznn.html

[S28] C：静态变量
来源：http://dali.zdqjudy.top/Article/details/gtcqxprrfl.html

static int counter = 0;
来源：http://dali.nanxinkj.top/Article/details/gtksnzlmfe.html

[S29] C：变参函数
来源：http://dali.jqgfzy.top/Article/details/gtemmtqdbr.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.nanxinkj.top/Article/details/gtnotmqjxz.html

[S30] C：头文件保护
来源：http://dali.yj20258888.top/Article/details/gtpbsitalv.html

#ifndef X_H
来源：http://dali.feifeiyinyue.top/Article/details/gtevmljruw.html

#define X_H
来源：http://dali.sufxvd.cn/Article/details/gthcfdhqof.html

#endif
来源：http://dali.pengpengdd.cyou/Article/details/gtfpkgejul.html

[S31] C++：Hello World
来源：http://dali.yanxiufei.cn/Article/details/gtxzqzgzuj.html

#include <iostream>
来源：http://dali.bjfxy.top/Article/details/gtugqeopug.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.mhx1999.top/Article/details/gtrhmmhbzy.html

[S32] C++：字符串
来源：http://dali.chenzaomai.com/Article/details/gtdbeenhye.html

std::string s = "hi";  s += "!";
来源：http://dali.zdqjudy.top/Article/details/gtxqxgfruu.html

[S33] C++：vector 增删
来源：http://dali.smart0.xyz/Article/details/gtzuarqiyv.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.pycfn.com/Article/details/gthiorxaya.html

[S34] C++：遍历 vector
来源：http://dali.nanxinkj.top/Article/details/gtoxezeldw.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cqqwz.cn/Article/details/gthinykyzy.html

[S35] C++：map
来源：http://dali.dashuyun.cn/Article/details/gtnkjezxhe.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.guowangkeji.top/Article/details/gtpihkwdbj.html

[S36] C++：unordered_map
来源：http://dali.gzhubu.top/Article/details/gtfftbdrwo.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.fengsongda.top/Article/details/gtxdqocxir.html

[S37] C++：set
来源：http://dali.jyoumei.cn/Article/details/gtvgtasibt.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.andypj.xyz/Article/details/gtjjysbesr.html

[S38] C++：排序
来源：http://dali.jyoumei.cn/Article/details/gtroewthph.html

std::sort(v.begin(), v.end());
来源：http://dali.jinyuanbaomall.cn/Article/details/gttjqmunfq.html

[S39] C++：自定义比较器排序
来源：http://dali.pengpengdd.cyou/Article/details/gtomsjydoy.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.cucudq.cn/Article/details/gtkdarpaim.html

[S40] C++：查找元素
来源：http://dali.jiagoushi.top/Article/details/gtmgcnvxiq.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.xziqi.cn/Article/details/gtbbihfoek.html

[S41] C++：类与构造函数
来源：http://dali.tian-w.cn/Article/details/gtchueoayg.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.cashguo.top/Article/details/gthxayayix.html

[S42] C++：继承与虚函数
来源：http://dali.dashuyun.cn/Article/details/gtpwepwyen.html

class B : public Base { public: void f() override {} };
来源：http://dali.zhixingplan.top/Article/details/gtrtxsxpjx.html

[S43] C++：智能指针
来源：http://dali.nwbrower.top/Article/details/gthezsyghw.html

auto p = std::make_unique<int>(5);
来源：http://dali.sufxvd.cn/Article/details/gtxbpofaqu.html

[S44] C++：引用传参
来源：http://dali.cashguo.top/Article/details/gtbfcfyiza.html

void inc(int &x) { ++x; }
来源：http://dali.jqgfzy.top/Article/details/gtiecunbbp.html

[S45] C++：lambda
来源：http://dali.shuidangran.top/Article/details/gttnorucfj.html

auto add = [](int a, int b) { return a + b; };
来源：http://dali.xinyue.icu/Article/details/gtcicdybfq.html

[S46] C++：函数模板
来源：http://dali.redwolf501.top/Article/details/gthnvtgeni.html

template <typename T> T maxv(T a, T b) { return a > b ? a : b; }
来源：http://dali.tian-w.cn/Article/details/gtpuzkdwmd.html

[S47] C++：结构化绑定遍历
来源：http://dali.jinyuanbaomall.cn/Article/details/gtepyymxdi.html

for (const auto &[k, v] : m) { std::cout << k << v; }
来源：http://dali.shangyingyoupin.top/Article/details/gttentaosn.html

[S48] C++：逐行读文件
来源：http://dali.hfpthk.cn/Article/details/gtiabjfnjf.html

std::ifstream in("a.txt");  std::string line;
来源：http://dali.sweek.top/Article/details/gtkteoavpb.html

while (std::getline(in, line)) { }
来源：http://dali.quarkkingdee.top/Article/details/gtpvxbuvor.html

[S49] C++：写文件
来源：http://dali.hfpthk.cn/Article/details/gtojkakikc.html

std::ofstream out("a.txt");  out << "hi\n";
来源：http://dali.shzxlz.cn/Article/details/gtrcbriyos.html

[S50] C++：格式化数字
来源：http://dali.c1oappe.top/Article/details/gtbwtvcjug.html


<!-- 参考信息 -->