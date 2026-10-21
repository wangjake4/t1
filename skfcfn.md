代发 wailian999

SHOW INDEX FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtdovxqciw.html

[Q73] 查看表状态
来源：http://dali.bjfxy.top/Article/details/gtbukxbmvw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ehwqpu.com/Article/details/gtdzwpqquo.html

[Q74] 强制使用索引
来源：http://dali.dashuyun.cn/Article/details/gtpvogwkfq.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.haohaochexian.top/Article/details/gtkxfrzfkh.html

[Q75] 日期格式化
来源：http://dali.hongshengwenyu.top/Article/details/gthlppzech.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtggyocuhv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.snrcjt.cn/Article/details/gtbnkzvgyn.html

[Q76] 按天统计
来源：http://dali.9152youxi.cn/Article/details/gtrjqmluad.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtulmajhve.html

[Q77] 时间加减
来源：http://dali.fengsongda.top/Article/details/gtrjsrjsby.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cucudq.cn/Article/details/gtxelrhfgp.html

[Q78] 当前时间
来源：http://dali.shanyushiyangtech.top/Article/details/gtzbcklusf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.guowangkeji.top/Article/details/gtkoerntwh.html

[Q79] 字符串拼接
来源：http://dali.smart0.xyz/Article/details/gtheazkwfk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.iojbl.cn/Article/details/gtybnqudiv.html

[Q80] 字符串截取
来源：http://dali.zhixingplan.top/Article/details/gtkuufxsug.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.nwbrower.top/Article/details/gtfeevqtet.html

[Q81] 字符串替换
来源：http://dali.316326.xyz/Article/details/gtlankaxpe.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtfgrcruip.html

[Q82] 字符长度与字节长度
来源：http://dali.wangshuangyany.cn/Article/details/gtwfzywkoy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtxagrrhvr.html

[Q83] 大小写转换
来源：http://dali.sweek.top/Article/details/gtewaiswva.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cashguo.top/Article/details/gtaucecnfb.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gtsruoomil.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtzojakeeg.html

[Q85] 数值取整
来源：http://dali.ehwqpu.com/Article/details/gtbjxowcws.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.vqdsnc.cn/Article/details/gtwfajoxqj.html

[Q86] 读取 JSON 字段
来源：http://dali.bjfxy.top/Article/details/gteotrorao.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhixingplan.top/Article/details/gtpjlipewe.html

[Q87] JSON 字段做条件
来源：http://dali.gaohongyu789.top/Article/details/gtczcnfevs.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.chenlongwang.top/Article/details/gtvvbcoueo.html

[Q88] 行转列（条件聚合）
来源：http://dali.hnqzz.top/Article/details/gtjajzqkrg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yvedp.cn/Article/details/gtjjogxnmi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtbsbasmbg.html

[Q89] 判断表是否存在
来源：http://dali.zhixingplan.top/Article/details/gtlhkigskc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.haohaochexian.top/Article/details/gtuxpjkgka.html

[Q90] 生成序号列
来源：http://dali.yanxiufei.cn/Article/details/gtnijiarhp.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.daxiang520.top/Article/details/gtzbaczjva.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtodlqdweo.html

R. Bash 专题
来源：http://dali.gogol.net.cn/Article/details/gtzqkvygdk.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtweouhmey.html

[R01] shebang 与严格模式
来源：http://dali.svipenyu.cn/Article/details/gtwwlygnhl.html

#!/usr/bin/env bash
来源：http://dali.zhoulong.xyz/Article/details/gthlupipas.html

set -euo pipefail
来源：http://dali.zhengqikj.top/Article/details/gtrgcqdnfn.html

[R02] 变量赋值与使用
来源：http://dali.havefunace.top/Article/details/gtfgcbjapk.html

name="Tom"; echo "$name"
来源：http://dali.jyoumei.cn/Article/details/gtilitylzh.html

[R03] 只读变量
来源：http://dali.chenzaomai.com/Article/details/gttnygopaz.html

readonly PI=3.14
来源：http://dali.guannengcc.top/Article/details/gtfvxutyqd.html

[R04] 位置参数
来源：http://dali.zycfv.cn/Article/details/gtwrtfuufz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yj202588.top/Article/details/gtjwnblcwc.html

[R05] 参数默认值
来源：http://dali.daria6918.cn/Article/details/gtqmkgkynv.html

name="${1:-default}"
来源：http://dali.xylfe.cn/Article/details/gtxknyglib.html

[R06] 判断命令是否存在
来源：http://dali.ehwqpu.com/Article/details/gtbpwohdth.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shuidangran.top/Article/details/gthsbqhkau.html

[R07] if 判断文件
来源：http://dali.zycfv.cn/Article/details/gtwbfuqppy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yonumen.top/Article/details/gtzwxhwzaw.html

[R08] 数值比较
来源：http://dali.zhoulong.xyz/Article/details/gtkkxsekfs.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.0kj1m.cn/Article/details/gtdpcggcqv.html

[R09] 字符串比较
来源：http://dali.zhiwuduotai.top/Article/details/gtabxngqdb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gtwgemeyly.html

[R10] 正则匹配
来源：http://dali.fengsongda.top/Article/details/gthvvlfrpt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.jinqigufen.top/Article/details/gtkjbcicyz.html

[R11] case 多分支
来源：http://dali.hammf.cn/Article/details/gtcyydjrnu.html

case "$1" in
来源：http://dali.ehwqpu.com/Article/details/gtuvdnqwvc.html

start) echo "启动" ;;
来源：http://dali.jyoumei.cn/Article/details/gtscztndkp.html

stop)  echo "停止" ;;
来源：http://dali.chenlongwang.top/Article/details/gtrmjsuzvc.html

*)     echo "未知命令" ;;
来源：http://dali.hammf.cn/Article/details/gteixhodbl.html

esac
来源：http://dali.nanxinkj.top/Article/details/gtwoaqgpel.html

[R12] for 遍历文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlntnzhst.html

for f in *.txt; do echo "$f"; done
来源：http://dali.wangdashe.top/Article/details/gtcgjzhucj.html

[R13] for 计数循环
来源：http://dali.guannengcc.top/Article/details/gtpomtcxyq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhaomingkeji.xyz/Article/details/gteeoemghg.html

[R14] C 风格 for
来源：http://dali.shuidangran.top/Article/details/gtapkdrlmq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yuanzhike.top/Article/details/gttxekgiki.html

[R15] while 逐行读文件
来源：http://dali.0kj1m.cn/Article/details/gtepcecroa.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.svipenyu.cn/Article/details/gtpmvxaxaj.html

[R16] until 等待条件
来源：http://dali.haohaochexian.top/Article/details/gtftmwlper.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ivvv.top/Article/details/gtszkrqjuf.html

[R17] 数组定义与取值
来源：http://dali.fzhhl.top/Article/details/gtplqmflvu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinqigfzy.top/Article/details/gtejuitwjh.html

[R18] 遍历数组
来源：http://dali.cheryme.top/Article/details/gtvitykpfl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.smart0.xyz/Article/details/gtfarivhvo.html

[R19] 数组长度
来源：http://dali.quarkkingdee.top/Article/details/gtlueaxmdn.html

echo "${#arr[@]}"
来源：http://dali.wangdashe.top/Article/details/gtjsxlqvjo.html

[R20] 关联数组（字典）
来源：http://dali.nanxuanxn.top/Article/details/gtnmhsrkcc.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.9152youxi.cn/Article/details/gtzwihqyuy.html

[R21] 字符串长度
来源：http://dali.feifeiyinyue.top/Article/details/gtlhimgnxp.html

echo "${#s}"
来源：http://dali.svipenyu.cn/Article/details/gtsywzjjae.html

[R22] 截取子串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbzmuxket.html

echo "${s:0:5}"
来源：http://dali.zhengqikj.top/Article/details/gtwuaqkhjs.html

[R23] 字符串替换
来源：http://dali.zdqjudy.top/Article/details/gtshguqsno.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.nanxuanxn.top/Article/details/gtrbkzjgmf.html

[R24] 大小写转换
来源：http://dali.guowangkeji.top/Article/details/gthzxrxmca.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.mhx1999.top/Article/details/gthdhiiplg.html

[R25] 去后缀 / 去前缀
来源：http://dali.xuanzx.com/Article/details/gtujdozdec.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhixingplan.top/Article/details/gtyqnmdgmb.html

[R26] 命令替换
来源：http://dali.hongshengwenyu.top/Article/details/gthpbjmxex.html

now=$(date +%F); echo "$now"
来源：http://dali.aibaodan.cn/Article/details/gteptttjrb.html

[R27] 算术展开
来源：http://dali.hongshengwenyu.top/Article/details/gtjvudozgz.html

echo $((1 + 2 * 3))
来源：http://dali.zdqjudy.top/Article/details/gtjclgxhjm.html

[R28] 浮点运算
来源：http://dali.hysaishi.cn/Article/details/gtbeubxoko.html

echo "scale=2; 10/3" | bc
来源：http://dali.nanxinkj.top/Article/details/gtyokeynqe.html

[R29] 定义函数
来源：http://dali.xinyue.icu/Article/details/gtfrkojkow.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cucudq.cn/Article/details/gtmpbputie.html

[R30] 函数返回状态码
来源：http://dali.daxiang520.top/Article/details/gtfotedycy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cheryme.top/Article/details/gtnnpmysjw.html

[R31] 局部变量
来源：http://dali.c1oappe.top/Article/details/gtgbyxwdmj.html

f() { local x=1; echo "$x"; }
来源：http://dali.jlsjyb.cn/Article/details/gtuldwqxfs.html

[R32] 参数个数校验
来源：http://dali.tian-w.cn/Article/details/gtnkbrjakr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtngsnnyom.html

[R33] 捕获错误并提示行号
来源：http://dali.havefunace.top/Article/details/gtfvqpzulu.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gzhubu.top/Article/details/gtinqfutlh.html

[R34] 退出时清理
来源：http://dali.gotoacloud.top/Article/details/gtzdyfxsqm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.c1oappe.top/Article/details/gtcqxkjwdx.html

[R35] 后台执行并等待
来源：http://dali.jinqigufen.top/Article/details/gtrsgjsmxo.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yj202588.top/Article/details/gtuendrdbg.html

[R36] 并发执行多个任务
来源：http://dali.shanyushiyangtech.top/Article/details/gtryacmvjq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jinqigfzy.top/Article/details/gteyqmdied.html

[R37] 把输出赋给变量
来源：http://dali.fengsongda.top/Article/details/gtstbztrck.html

files=$(ls -1)
来源：http://dali.dashuyun.cn/Article/details/gtmxcssiol.html

[R38] 管道串联
来源：http://dali.ydzc1.top/Article/details/gtubyyldma.html

cat a.txt | grep -i error | wc -l
来源：http://dali.nwbrower.top/Article/details/gtnueabzuo.html

[R39] 重定向标准输出与错误
来源：http://dali.wangdashe.top/Article/details/gtyvuhtozt.html

cmd > out.log 2>&1
来源：http://dali.shangyingyoupin.top/Article/details/gturuaccjg.html

[R40] 追加写日志
来源：http://dali.havefunace.top/Article/details/gtcyostqup.html

echo "log" >> out.log
来源：http://dali.yanxiufei.cn/Article/details/gtjnlctwgu.html

[R41] 丢弃输出
来源：http://dali.chenlongwang.top/Article/details/gtfwwxqljh.html

cmd >/dev/null 2>&1
来源：http://dali.feifeiyinyue.top/Article/details/gtfsmgnzbx.html

[R42] 输入重定向
来源：http://dali.chenlongwang.top/Article/details/gtzuszwxyr.html

wc -l < a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtwftdvtjg.html

[R43] 按名字查找文件
来源：http://dali.jqgfzy.top/Article/details/gtzbtajsqg.html

find . -name "*.log" -type f
来源：http://dali.vqdsnc.cn/Article/details/gtffyhjsfg.html

[R44] 按修改时间查找
来源：http://dali.cheryme.top/Article/details/gtojucunld.html

find . -mtime -7 -type f
来源：http://dali.yj202588.top/Article/details/gtevpmgubl.html

[R45] 批量删除
来源：http://dali.cucudq.cn/Article/details/gtnjujjtwa.html

find . -name "*.tmp" -delete
来源：http://dali.redwolf501.top/Article/details/gteeddsfhe.html

[R46] 递归替换文件内容
来源：http://dali.c1oappe.top/Article/details/gtiicxplkq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.0kj1m.cn/Article/details/gttnoehjuk.html

[R47] sed 单行替换
来源：http://dali.shzxlz.cn/Article/details/gtlanfisft.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gogol.net.cn/Article/details/gtrblxohuj.html

[R48] awk 取指定列
来源：http://dali.xuanzx.com/Article/details/gtavvpbith.html

awk '{print $1, $3}' a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtyaifaknj.html

[R49] awk 带条件
来源：http://dali.aizwys.cn/Article/details/gtwzklliok.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ybcxt.top/Article/details/gtfcixqrrs.html

[R50] awk 求和
来源：http://dali.wangdashe.top/Article/details/gtfxxywpvh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.tian-w.cn/Article/details/gtfsftptgn.html

[R51] 排序去重取前几
来源：http://dali.nwbrower.top/Article/details/gtmwvebjcq.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.daria6918.cn/Article/details/gtyuljpxhr.html

[R52] 统计行数
来源：http://dali.cucudq.cn/Article/details/gtjbjmaiyi.html

wc -l a.txt
来源：http://dali.ivvv.top/Article/details/gtojqhocob.html

[R53] 查看文件头与实时尾
来源：http://dali.9152youxi.cn/Article/details/gtmeglzjpm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shangyingyoupin.top/Article/details/gtzgcfirxi.html

[R54] 比较两个文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtfeyxolgu.html

diff a.txt b.txt
来源：http://dali.chenjidiqi.icu/Article/details/gtdyspbxko.html

[R55] 压缩与解压
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbqwlfvpg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yvedp.cn/Article/details/gtkwtrtepe.html

[R56] 远程拷贝
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkgowpycx.html

scp file user@host:/path/
来源：http://dali.nwbrower.top/Article/details/gtmureexhv.html

[R57] 远程执行命令
来源：http://dali.cheryme.top/Article/details/gtbemlridn.html

ssh user@host 'uptime'
来源：http://dali.yj20258.top/Article/details/gtokkipgav.html

[R58] 下载文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtelfwqjvn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.haohaochexian.top/Article/details/gtxfnipquu.html

[R59] 发 POST JSON
来源：http://dali.yj202588.top/Article/details/gtokbrovjg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.meibo888.top/Article/details/gtpwcvemrw.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhixingplan.top/Article/details/gttauqwglc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.daria6918.cn/Article/details/gtfjdugrto.html

[R61] 磁盘占用
来源：http://dali.feifeiyinyue.top/Article/details/gteymbrfsi.html

df -h;  du -sh *
来源：http://dali.yj20258888.top/Article/details/gtytsupxbr.html

[R62] 找最占空间的文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdttwufns.html

du -ah . | sort -rh | head -10
来源：http://dali.cqqwz.cn/Article/details/gtsrdxvbff.html

[R63] 内存与进程
来源：http://dali.xinyue.icu/Article/details/gtmfgnkebj.html

free -h;  ps aux | grep nginx
来源：http://dali.daria6918.cn/Article/details/gtuknthszu.html

[R64] 结束进程
来源：http://dali.fengsongda.top/Article/details/gtrceujfti.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hysaishi.cn/Article/details/gtrmaddeei.html

[R65] 查看端口占用
来源：http://dali.jqgufenzy.top/Article/details/gtfxtflmxl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jyoumei.cn/Article/details/gtrzaluhnx.html

[R66] 定时任务
来源：http://dali.zycfv.cn/Article/details/gtcwhfuchv.html

crontab -e;  crontab -l
来源：http://dali.guannengcc.top/Article/details/gtloltlvbt.html

[R67] 生成随机十六进制串
来源：http://dali.jiagoushi.top/Article/details/gtzexatyrh.html

openssl rand -hex 16
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjmisqtez.html

[R68] 计算文件校验值
来源：http://dali.gaohongyu789.top/Article/details/gtpypiendp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xinyue.icu/Article/details/gtliirxuur.html

[R69] 生成随机密码
来源：http://dali.zhixingplan.top/Article/details/gtbepkkydd.html

head -c 16 /dev/urandom | base64
来源：http://dali.xuanzx.com/Article/details/gtvsptaxts.html

[R70] 时间戳与互转
来源：http://dali.chenzaomai.com/Article/details/gtnjisxwlt.html

date +%s;  date -d @1700000000
来源：http://dali.ehwqpu.com/Article/details/gttdjsshjg.html

[R71] 日期格式化
来源：http://dali.jinqigfzy.top/Article/details/gtqntzhnzj.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gteaggtkxj.html

[R72] 等待端口就绪
来源：http://dali.sysykeji.top/Article/details/gtfkxuiyyo.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.xinyue.icu/Article/details/gtejeyujol.html

[R73] 分割大日志
来源：http://dali.snrcjt.cn/Article/details/gtsljeawgd.html

split -l 1000 big.log part_
来源：http://dali.snrcjt.cn/Article/details/gtoixxkvxc.html

[R74] 批量重命名
来源：http://dali.xylfe.cn/Article/details/gtjncxmobm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.0kj1m.cn/Article/details/gteldtbmnd.html

[R75] 导出环境变量
来源：http://dali.pengpengdd.cyou/Article/details/gtptawcodc.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.tanke756.top/Article/details/gtdnhvhjve.html

[R76] 使用临时文件
来源：http://dali.smart0.xyz/Article/details/gtnizqaxgu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hammf.cn/Article/details/gtevqzvvru.html

[R77] 读取用户输入
来源：http://dali.yangfankeji.com/Article/details/gtdknayfwe.html

read -rp "请输入: " ans
来源：http://dali.yangfankeji.com/Article/details/gtakdrbuzg.html

[R78] 交互式菜单
来源：http://dali.yongpay.top/Article/details/gthqjubdrv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shuidangran.top/Article/details/gtjfavbone.html

[R79] 解析命令行选项
来源：http://dali.snrcjt.cn/Article/details/gtalzmfups.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.yvedp.cn/Article/details/gtezvxghot.html

[R80] 查看脚本执行耗时
来源：http://dali.0kj1m.cn/Article/details/gtjhjlwpoe.html

time ./run.sh
来源：http://dali.cqqwz.cn/Article/details/gtvnhzvumr.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gthvtbqoop.html

S. C / C++ 专题
来源：http://dali.zhixingplan.top/Article/details/gtwdaxxgue.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtgpykvehq.html

[S01] C：Hello World
来源：http://dali.birdmap.top/Article/details/gtdgxuxlrw.html

#include <stdio.h>
来源：http://dali.jinghuilouyu.cn/Article/details/gtxkydhvoq.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jlsjyb.cn/Article/details/gtdpiigdfb.html

[S02] C：变量与格式化输出
来源：http://dali.pycfn.com/Article/details/gtlcvhmspd.html

int a = 10; printf("%d\n", a);
来源：http://dali.jinqigfzy.top/Article/details/gtzobjulwv.html

[S03] C：读入整数
来源：http://dali.gotoacloud.top/Article/details/gtcuwnexox.html

int x; scanf("%d", &x);
来源：http://dali.dianchejie.cn/Article/details/gtbcxpdjmp.html

[S04] C：字符串复制
来源：http://dali.shanyushiyangtech.top/Article/details/gtdmalwbsx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.chenzaomai.com/Article/details/gtgxoxgdmk.html

[S05] C：字符串长度
来源：http://dali.shanyushiyangtech.top/Article/details/gtstzmseea.html

strlen(s)
来源：http://dali.jyoumei.cn/Article/details/gtivbgbcui.html

[S06] C：字符串比较
来源：http://dali.zhiwuduotai.top/Article/details/gtrdjvtnyj.html

strcmp(a, b) == 0
来源：http://dali.fengsongda.top/Article/details/gtwijqviap.html

[S07] C：数组遍历求和
来源：http://dali.yvedp.cn/Article/details/gtjqlvwbfy.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.daria6918.cn/Article/details/gtfgzdgvfv.html

[S08] C：动态内存分配与释放
来源：http://dali.zhongyouzk.top/Article/details/gttwpifiqf.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.daria6918.cn/Article/details/gthyiarqrw.html

[S09] C：结构体定义与初始化
来源：http://dali.xylfe.cn/Article/details/gtodzhrorv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.ppjwa.cn/Article/details/gtuvzsxqoe.html

[S10] C：指针与解引用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtejwoozrz.html

int *p = &a;  *p = 5;
来源：http://dali.zdqjudy.top/Article/details/gtpxkphaym.html

[S11] C：逐行读文件
来源：http://dali.316326.xyz/Article/details/gtnucsjpol.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlkfqwxbh.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.hywenlv.cn/Article/details/gtcvnxenxi.html

fclose(f);
来源：http://dali.yj20258.top/Article/details/gtglagxxbm.html

[S12] C：写文件
来源：http://dali.chenlongwang.top/Article/details/gtfyrnppve.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.jqgufenzy.top/Article/details/gtvggcohyp.html

[S13] C：宏定义
来源：http://dali.wangshuangyany.cn/Article/details/gtqhedecbs.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtczhuwuda.html

[S14] C：枚举
来源：http://dali.jianghu66.top/Article/details/gtrhkfsiht.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.xziqi.cn/Article/details/gttxdvdydz.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gtudfpommt.html

(double) a / b
来源：http://dali.shuidangran.top/Article/details/gtpdzkldtc.html

[S16] C：位操作置位
来源：http://dali.jiagoushi.top/Article/details/gtkdbhrgvt.html

x |= (1 << 3);
来源：http://dali.shzxlz.cn/Article/details/gtejvjaymz.html

[S17] C：安全拼接字符串
来源：http://dali.cqqwz.cn/Article/details/gtetdzrzcj.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.gogol.net.cn/Article/details/gtgrxbyqon.html

[S18] C：命令行参数
来源：http://dali.daxiang520.top/Article/details/gtbsghrwqi.html

int main(int argc, char **argv)
来源：http://dali.mhx1999.top/Article/details/gtecbzhwjn.html

[S19] C：快速排序
来源：http://dali.mhx1999.top/Article/details/gtmvsqzbki.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhiwuduotai.top/Article/details/gteavqpsnp.html

[S20] C：二分查找
来源：http://dali.xuanzx.com/Article/details/gtpvnapysb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.fzhhl.top/Article/details/gtrrzoqdtf.html

[S21] C：字符类别判断
来源：http://dali.shanyushiyangkeji.top/Article/details/gttrvvaarc.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.fzhhl.top/Article/details/gtmsporewt.html

[S22] C：字符串转数字
来源：http://dali.xinyue.icu/Article/details/gtdjngxgtp.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.svipenyu.cn/Article/details/gtrzxdxprg.html

[S23] C：随机数
来源：http://dali.gotoacloud.top/Article/details/gttogadklb.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.yvedp.cn/Article/details/gtndakrcyp.html

[S24] C：获取本地时间
来源：http://dali.yvedp.cn/Article/details/gtzuwwiprt.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.yuanzhike.top/Article/details/gttjlkjtkt.html

[S25] C：内存拷贝
来源：http://dali.daxiang520.top/Article/details/gtpjqzbcdt.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gtledpuhah.html

[S26] C：内存清零
来源：http://dali.pengpengdd.cyou/Article/details/gtvjvqpwrc.html

memset(a, 0, sizeof a);
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgyyodkyd.html

[S27] C：定义常量
来源：http://dali.dashuyun.cn/Article/details/gtkwujzxtv.html

const double PI = 3.14159;
来源：http://dali.yuxming.cn/Article/details/gtvxhdphpu.html

[S28] C：静态变量
来源：http://dali.wangdashe.top/Article/details/gtjgcxidqr.html

static int counter = 0;
来源：http://dali.gotoacloud.top/Article/details/gtstxfyeoo.html

[S29] C：变参函数
来源：http://dali.snrcjt.cn/Article/details/gttflsktzg.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zdqjudy.top/Article/details/gttrjgpjma.html

[S30] C：头文件保护
来源：http://dali.pengpengdd.cyou/Article/details/gtavouuipr.html

#ifndef X_H
来源：http://dali.zycfv.cn/Article/details/gttyuzkqnj.html

#define X_H
来源：http://dali.cashguo.top/Article/details/gtotuooqgw.html

#endif
来源：http://dali.jinqigfzy.top/Article/details/gtsvidzkxx.html

[S31] C++：Hello World
来源：http://dali.jyoumei.cn/Article/details/gtbbcpjsds.html

#include <iostream>
来源：http://dali.hywenlv.cn/Article/details/gtqrukcoqk.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.yuxming.cn/Article/details/gtqcpvdioa.html

[S32] C++：字符串
来源：http://dali.jianghu66.top/Article/details/gtjtyxltzl.html

std::string s = "hi";  s += "!";
来源：http://dali.guannengcc.top/Article/details/gtvatbbciy.html

[S33] C++：vector 增删
来源：http://dali.ivvv.top/Article/details/gtsyrkdzfu.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.cashguo.top/Article/details/gtormwexxz.html

[S34] C++：遍历 vector
来源：http://dali.iojbl.cn/Article/details/gtasjwaoaz.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.haohaochexian.top/Article/details/gtmkivgwwc.html

[S35] C++：map
来源：http://dali.hongshengwenyu.top/Article/details/gtnnqonrgg.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.316326.xyz/Article/details/gttblszugh.html

[S36] C++：unordered_map
来源：http://dali.yangfankeji.com/Article/details/gtyesgsoer.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.jlsjyb.cn/Article/details/gtriplaoev.html

[S37] C++：set
来源：http://dali.yangfankeji.com/Article/details/gtpvbgmyqs.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.hnqzz.top/Article/details/gtjjlubjxk.html

[S38] C++：排序
来源：http://dali.yonumen.top/Article/details/gtknykeemk.html

std::sort(v.begin(), v.end());
来源：http://dali.ybcxt.top/Article/details/gtzfncufgs.html

[S39] C++：自定义比较器排序
来源：http://dali.cqqwz.cn/Article/details/gtqjeplbwd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.meibo888.top/Article/details/gtubkqnkjc.html

[S40] C++：查找元素
来源：http://dali.jlsjyb.cn/Article/details/gtcbfftjpt.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.zycfv.cn/Article/details/gtqmljlpnr.html

[S41] C++：类与构造函数
来源：http://dali.0kj1m.cn/Article/details/gtpjyzpsmj.html

class A { public: A(int v) : x_(v) {} int get() const { return x_; } private: int x_; };
来源：http://dali.vqdsnc.cn/Article/details/gtldvuguhx.html

[S42] C++：继承与虚函数
来源：http://dali.aibaodan.cn/Article/details/gtdpiurkua.html

class B : public Base { public: void f() override {} };
来源：http://dali.snrcjt.cn/Article/details/gtgxltguow.html


<!-- 参考信息 -->