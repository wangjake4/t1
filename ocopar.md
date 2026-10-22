代发 wailian999

ANALYZE TABLE users;
来源：http://dali.zhixingplan.top/Article/details/gtpkbkivgo.html

[Q71] 查看建表语句
来源：http://dali.zycfv.cn/Article/details/gthcfgqftk.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jinqigfzy.top/Article/details/gtsohlgven.html

[Q72] 查看索引
来源：http://dali.tianlin.xyz/Article/details/gtvqamesib.html

SHOW INDEX FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtfitsegvt.html

[Q73] 查看表状态
来源：http://dali.chenjidiqi.icu/Article/details/gtpkskuzzj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jqgufenzy.top/Article/details/gtudgmprjj.html

[Q74] 强制使用索引
来源：http://dali.xylfe.cn/Article/details/gtlgjcwbpo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yueranfly.top/Article/details/gtqyojqnhk.html

[Q75] 日期格式化
来源：http://dali.jinqigfzy.top/Article/details/gtltcytapb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtbetmhmzm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjdmqqoyo.html

[Q76] 按天统计
来源：http://dali.xylfe.cn/Article/details/gtsgbxlvyf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.meibo888.top/Article/details/gtqormrjsl.html

[Q77] 时间加减
来源：http://dali.fzhhl.top/Article/details/gtxikwypqv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shanyushiyangtech.top/Article/details/gtzucvjsxw.html

[Q78] 当前时间
来源：http://dali.gaohongyu789.top/Article/details/gtvufzcplf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.tian-w.cn/Article/details/gtuizpwmwp.html

[Q79] 字符串拼接
来源：http://dali.tianlin.xyz/Article/details/gtjzboxvrk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hammf.cn/Article/details/gtmiutujic.html

[Q80] 字符串截取
来源：http://dali.tianlin.xyz/Article/details/gtgvrdlgzo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtjgeuefmc.html

[Q81] 字符串替换
来源：http://dali.havefunace.top/Article/details/gtpkkawqbr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtldlizukg.html

[Q82] 字符长度与字节长度
来源：http://dali.chenjidiqi.icu/Article/details/gtzoicyawh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgrncinrz.html

[Q83] 大小写转换
来源：http://dali.gaohongyu789.top/Article/details/gtxhqufvrf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.iojbl.cn/Article/details/gtvkqztipt.html

[Q84] 去除首尾空格
来源：http://dali.quarkkingdee.top/Article/details/gtzrxowdft.html

SELECT TRIM(name) FROM users;
来源：http://dali.xuanzx.com/Article/details/gtvfvlzhls.html

[Q85] 数值取整
来源：http://dali.hfpthk.cn/Article/details/gttphaothh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hammf.cn/Article/details/gtdfazglgd.html

[Q86] 读取 JSON 字段
来源：http://dali.haohaochexian.top/Article/details/gtjhtxadrd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shanyushiyangtech.top/Article/details/gtjhgpwspu.html

[Q87] JSON 字段做条件
来源：http://dali.chenlongwang.top/Article/details/gteqhleqmj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.mhx1999.top/Article/details/gtuqiihhvz.html

[Q88] 行转列（条件聚合）
来源：http://dali.andypj.xyz/Article/details/gtqctxbxcs.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhongyouzk.top/Article/details/gtynbxsoyj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.andypj.xyz/Article/details/gtmojgsiqt.html

[Q89] 判断表是否存在
来源：http://dali.daxiang520.top/Article/details/gtgqhpgpyu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhoulong.xyz/Article/details/gtiloaxioy.html

[Q90] 生成序号列
来源：http://dali.zhongyouzk.top/Article/details/gtofnfbouj.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jyoumei.cn/Article/details/gtcikyjbgz.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtosbgjzgq.html

R. Bash 专题
来源：http://dali.guannengcc.top/Article/details/gtitkksdvf.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gtirzrsnkb.html

[R01] shebang 与严格模式
来源：http://dali.guowangkeji.top/Article/details/gtjluhkoji.html

#!/usr/bin/env bash
来源：http://dali.wangdashe.top/Article/details/gtigkmknbv.html

set -euo pipefail
来源：http://dali.hnxiangtu.top/Article/details/gtuarkfoaz.html

[R02] 变量赋值与使用
来源：http://dali.xziqi.cn/Article/details/gtxzowftho.html

name="Tom"; echo "$name"
来源：http://dali.sufxvd.cn/Article/details/gtchuwxfms.html

[R03] 只读变量
来源：http://dali.wangdashe.top/Article/details/gtcqeerctu.html

readonly PI=3.14
来源：http://dali.wangdashe.top/Article/details/gtlgthxcsw.html

[R04] 位置参数
来源：http://dali.tian-w.cn/Article/details/gtjlycddoz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hammf.cn/Article/details/gteteicbwk.html

[R05] 参数默认值
来源：http://dali.ivvv.top/Article/details/gtpkipcvbs.html

name="${1:-default}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtgdpizbci.html

[R06] 判断命令是否存在
来源：http://dali.hysaishi.cn/Article/details/gtefsosjrh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj202588.top/Article/details/gtyndonkjo.html

[R07] if 判断文件
来源：http://dali.jianghu66.top/Article/details/gtdnikjpcx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.0kj1m.cn/Article/details/gttixmqqgo.html

[R08] 数值比较
来源：http://dali.nwbrower.top/Article/details/gtdevuxkto.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jqgfzy.top/Article/details/gtlsujtflz.html

[R09] 字符串比较
来源：http://dali.xuetiantiany.cn/Article/details/gtjfvpdbgm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.haohaochexian.top/Article/details/gtrhcxucjv.html

[R10] 正则匹配
来源：http://dali.316326.xyz/Article/details/gtjuujload.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hywenlv.cn/Article/details/gtytuqcjyq.html

[R11] case 多分支
来源：http://dali.yanxiufei.cn/Article/details/gtwmkmwicf.html

case "$1" in
来源：http://dali.wangshuangyany.cn/Article/details/gtrobrgihr.html

start) echo "启动" ;;
来源：http://dali.yueranfly.top/Article/details/gtsqcfgdco.html

stop)  echo "停止" ;;
来源：http://dali.shanyushiyangtech.top/Article/details/gthimdgfba.html

*)     echo "未知命令" ;;
来源：http://dali.ydzc1.top/Article/details/gtbglwhwhi.html

esac
来源：http://dali.sxryk.cn/Article/details/gtidhrwswx.html

[R12] for 遍历文件
来源：http://dali.fzhhl.top/Article/details/gtlioalwar.html

for f in *.txt; do echo "$f"; done
来源：http://dali.svipenyu.cn/Article/details/gtkldvahso.html

[R13] for 计数循环
来源：http://dali.hfpthk.cn/Article/details/gtmcwyoflk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cqqwz.cn/Article/details/gtbggaukom.html

[R14] C 风格 for
来源：http://dali.hammf.cn/Article/details/gtjmugybjr.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcbwnknhy.html

[R15] while 逐行读文件
来源：http://dali.fengsongda.top/Article/details/gtexkjywzw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.fengsongda.top/Article/details/gtkfqwhqhi.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gtwwvsetgr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.guowangkeji.top/Article/details/gtxsdaffsu.html

[R17] 数组定义与取值
来源：http://dali.shzxlz.cn/Article/details/gtzcbidpbq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.chenlongwang.top/Article/details/gtxkgzknhr.html

[R18] 遍历数组
来源：http://dali.gaohongyu789.top/Article/details/gtxjrcdicb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hfpthk.cn/Article/details/gtiyxvpldh.html

[R19] 数组长度
来源：http://dali.hysaishi.cn/Article/details/gtprkrfqjp.html

echo "${#arr[@]}"
来源：http://dali.yonumen.top/Article/details/gtngodpqhx.html

[R20] 关联数组（字典）
来源：http://dali.yj202588.top/Article/details/gthcwyklxz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ybcxt.top/Article/details/gtwjguchpi.html

[R21] 字符串长度
来源：http://dali.gotoacloud.top/Article/details/gtiyhqvamq.html

echo "${#s}"
来源：http://dali.nanxinkj.top/Article/details/gtzsmxewru.html

[R22] 截取子串
来源：http://dali.tianlin.xyz/Article/details/gtxpbbdypm.html

echo "${s:0:5}"
来源：http://dali.jqgfzy.top/Article/details/gtcgodopie.html

[R23] 字符串替换
来源：http://dali.fzhhl.top/Article/details/gtascgmfll.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shzxlz.cn/Article/details/gthxlulwwt.html

[R24] 大小写转换
来源：http://dali.kuanghao11.cn/Article/details/gtklsptijj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hammf.cn/Article/details/gtynpseeyt.html

[R25] 去后缀 / 去前缀
来源：http://dali.sysykeji.top/Article/details/gttaimvqrn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ivvv.top/Article/details/gtmmhmhhmu.html

[R26] 命令替换
来源：http://dali.andypj.xyz/Article/details/gtgdyypqxr.html

now=$(date +%F); echo "$now"
来源：http://dali.andypj.xyz/Article/details/gtusooqfcp.html

[R27] 算术展开
来源：http://dali.zhiwuduotai.top/Article/details/gtrthzklop.html

echo $((1 + 2 * 3))
来源：http://dali.9152youxi.cn/Article/details/gtttajarvm.html

[R28] 浮点运算
来源：http://dali.nwbrower.top/Article/details/gtnfiicgke.html

echo "scale=2; 10/3" | bc
来源：http://dali.guowangkeji.top/Article/details/gtjuwgcozt.html

[R29] 定义函数
来源：http://dali.yj202588.top/Article/details/gtqqiiqlfb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.meibo888.top/Article/details/gtfqvafaxd.html

[R30] 函数返回状态码
来源：http://dali.316326.xyz/Article/details/gtdjmpqrlb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tian-w.cn/Article/details/gtyviclpju.html

[R31] 局部变量
来源：http://dali.vqdsnc.cn/Article/details/gtqoveqvrv.html

f() { local x=1; echo "$x"; }
来源：http://dali.birdmap.top/Article/details/gtmijdaeho.html

[R32] 参数个数校验
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfhbdndue.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.fengsongda.top/Article/details/gtzkddjabo.html

[R33] 捕获错误并提示行号
来源：http://dali.cucudq.cn/Article/details/gtmoejtilt.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yueranfly.top/Article/details/gtxzcwgxvy.html

[R34] 退出时清理
来源：http://dali.cucudq.cn/Article/details/gtxbivzbrl.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yueranfly.top/Article/details/gtjzndvkpq.html

[R35] 后台执行并等待
来源：http://dali.birdmap.top/Article/details/gtncxdenxe.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.wangdashe.top/Article/details/gtqmwljhnw.html

[R36] 并发执行多个任务
来源：http://dali.xuanzx.com/Article/details/gtfqoghsio.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jiagoushi.top/Article/details/gtkggthefs.html

[R37] 把输出赋给变量
来源：http://dali.hnqzz.top/Article/details/gtgvodznce.html

files=$(ls -1)
来源：http://dali.cheryme.top/Article/details/gtpvkqlyim.html

[R38] 管道串联
来源：http://dali.yuxming.cn/Article/details/gtoeilixbt.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hammf.cn/Article/details/gtvvwsnalt.html

[R39] 重定向标准输出与错误
来源：http://dali.zhongyouzk.top/Article/details/gtpurziejj.html

cmd > out.log 2>&1
来源：http://dali.yj20258.top/Article/details/gtnvlzsgxt.html

[R40] 追加写日志
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbewyxpsq.html

echo "log" >> out.log
来源：http://dali.yanxiufei.cn/Article/details/gtquqaasgc.html

[R41] 丢弃输出
来源：http://dali.zhengqikj.top/Article/details/gtygipscqt.html

cmd >/dev/null 2>&1
来源：http://dali.gaohongyu789.top/Article/details/gtkkvdrnik.html

[R42] 输入重定向
来源：http://dali.bjfxy.top/Article/details/gtarjmrsyk.html

wc -l < a.txt
来源：http://dali.cheryme.top/Article/details/gtekaszohg.html

[R43] 按名字查找文件
来源：http://dali.haohaochexian.top/Article/details/gtcqpoprak.html

find . -name "*.log" -type f
来源：http://dali.yongpay.top/Article/details/gtsdsxyfom.html

[R44] 按修改时间查找
来源：http://dali.gaohongyu789.top/Article/details/gtuaamujjr.html

find . -mtime -7 -type f
来源：http://dali.svipenyu.cn/Article/details/gtyqvlbzwo.html

[R45] 批量删除
来源：http://dali.fzhhl.top/Article/details/gtwppgyhqc.html

find . -name "*.tmp" -delete
来源：http://dali.xylfe.cn/Article/details/gtscfokwxz.html

[R46] 递归替换文件内容
来源：http://dali.zhixingplan.top/Article/details/gtooiniodx.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cucudq.cn/Article/details/gtwpfvvkac.html

[R47] sed 单行替换
来源：http://dali.xziqi.cn/Article/details/gtlbtzaetx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.tanke756.top/Article/details/gtgnndhund.html

[R48] awk 取指定列
来源：http://dali.yj20258.top/Article/details/gtasmlksxz.html

awk '{print $1, $3}' a.txt
来源：http://dali.jinqigufen.top/Article/details/gtmxoqvvdv.html

[R49] awk 带条件
来源：http://dali.hongshengwenyu.top/Article/details/gtvlnupcql.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sxryk.cn/Article/details/gtjfvqtcqk.html

[R50] awk 求和
来源：http://dali.yangfankeji.com/Article/details/gtpgbgvjcy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yvedp.cn/Article/details/gtyhhpikuh.html

[R51] 排序去重取前几
来源：http://dali.zhixingplan.top/Article/details/gtxasnhgyx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjxbwiixu.html

[R52] 统计行数
来源：http://dali.9152youxi.cn/Article/details/gtmooyfazj.html

wc -l a.txt
来源：http://dali.zdqjudy.top/Article/details/gtzojmsnnv.html

[R53] 查看文件头与实时尾
来源：http://dali.nanxinkj.top/Article/details/gtfsjooogj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.aizwys.cn/Article/details/gtsmqzvhsa.html

[R54] 比较两个文件
来源：http://dali.zhengqikj.top/Article/details/gtrtosmvxj.html

diff a.txt b.txt
来源：http://dali.zhengqikj.top/Article/details/gtvwmwqovl.html

[R55] 压缩与解压
来源：http://dali.bjfxy.top/Article/details/gtmdwjhvve.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gotoacloud.top/Article/details/gtmecdifwf.html

[R56] 远程拷贝
来源：http://dali.kuanghao11.cn/Article/details/gtcncaoxvx.html

scp file user@host:/path/
来源：http://dali.jianghu66.top/Article/details/gtugisljji.html

[R57] 远程执行命令
来源：http://dali.shanyushiyangtech.top/Article/details/gtnustzqld.html

ssh user@host 'uptime'
来源：http://dali.jinghuilouyu.cn/Article/details/gtbpbziijs.html

[R58] 下载文件
来源：http://dali.316326.xyz/Article/details/gthyscfxtx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.iojbl.cn/Article/details/gtlaujowwl.html

[R59] 发 POST JSON
来源：http://dali.daxiang520.top/Article/details/gtjxfkccxz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xziqi.cn/Article/details/gteimsnkor.html

[R60] 只看 HTTP 状态码
来源：http://dali.birdmap.top/Article/details/gtbdvoccde.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.tianlin.xyz/Article/details/gtlgcjaqfp.html

[R61] 磁盘占用
来源：http://dali.guannengcc.top/Article/details/gtavndocrz.html

df -h;  du -sh *
来源：http://dali.fzhhl.top/Article/details/gtdisrelpy.html

[R62] 找最占空间的文件
来源：http://dali.yuanzhike.top/Article/details/gtrzecxsmj.html

du -ah . | sort -rh | head -10
来源：http://dali.yueranfly.top/Article/details/gtbwnbqwfa.html

[R63] 内存与进程
来源：http://dali.gzhubu.top/Article/details/gtgslamfrt.html

free -h;  ps aux | grep nginx
来源：http://dali.xziqi.cn/Article/details/gtohnhthqi.html

[R64] 结束进程
来源：http://dali.tian-w.cn/Article/details/gtjsffyqrr.html

kill -9 $(pgrep -f app.py)
来源：http://dali.kuanghao11.cn/Article/details/gtsypinqud.html

[R65] 查看端口占用
来源：http://dali.svipenyu.cn/Article/details/gtknxfqhtd.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.dianchejie.cn/Article/details/gtcvzfhkxb.html

[R66] 定时任务
来源：http://dali.zdqjudy.top/Article/details/gtyjvfmnwd.html

crontab -e;  crontab -l
来源：http://dali.wangshuangyany.cn/Article/details/gtdrounyvk.html

[R67] 生成随机十六进制串
来源：http://dali.chenlongwang.top/Article/details/gttnhbjzyp.html

openssl rand -hex 16
来源：http://dali.pengpengdd.cyou/Article/details/gtnbrmuuzw.html

[R68] 计算文件校验值
来源：http://dali.pengpengdd.cyou/Article/details/gtyexwztrq.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xinyue.icu/Article/details/gtcibkrybd.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gtjexiuduq.html

head -c 16 /dev/urandom | base64
来源：http://dali.guannengcc.top/Article/details/gtidbscafa.html

[R70] 时间戳与互转
来源：http://dali.svipenyu.cn/Article/details/gthozgcrwf.html

date +%s;  date -d @1700000000
来源：http://dali.0kj1m.cn/Article/details/gtlaxerbjf.html

[R71] 日期格式化
来源：http://dali.xziqi.cn/Article/details/gtfdqciooz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj202588.top/Article/details/gtudzcfehk.html

[R72] 等待端口就绪
来源：http://dali.yj20258.top/Article/details/gtgxmmgvgw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.smart0.xyz/Article/details/gtxcldwlhl.html

[R73] 分割大日志
来源：http://dali.cdnleiting.top/Article/details/gtamqiwbzd.html

split -l 1000 big.log part_
来源：http://dali.sysykeji.top/Article/details/gtuybkxebq.html

[R74] 批量重命名
来源：http://dali.yanxiufei.cn/Article/details/gttqhtjmuw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.jlsjyb.cn/Article/details/gttboiteie.html

[R75] 导出环境变量
来源：http://dali.yanxiufei.cn/Article/details/gtvqzkrspo.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.c1oappe.top/Article/details/gtgmmltrss.html

[R76] 使用临时文件
来源：http://dali.cdnleiting.top/Article/details/gtjwwjhizy.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xinyue.icu/Article/details/gtrbylhdgi.html

[R77] 读取用户输入
来源：http://dali.pycfn.com/Article/details/gtjblwdhvo.html

read -rp "请输入: " ans
来源：http://dali.yonumen.top/Article/details/gtnjysxzkb.html

[R78] 交互式菜单
来源：http://dali.shangyingyoupin.top/Article/details/gtctjkbrjp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.pengpengdd.cyou/Article/details/gtvxnjrlgr.html

[R79] 解析命令行选项
来源：http://dali.fengsongda.top/Article/details/gtjcsvvwje.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.dianchejie.cn/Article/details/gtrfeqtoxq.html

[R80] 查看脚本执行耗时
来源：http://dali.guowangkeji.top/Article/details/gtzknnwpfh.html

time ./run.sh
来源：http://dali.fzhhl.top/Article/details/gteqlklxmu.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gtwcyrypbz.html

S. C / C++ 专题
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsjtnqajw.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gttjwzrepo.html

[S01] C：Hello World
来源：http://dali.wangshuangyany.cn/Article/details/gtwapalemu.html

#include <stdio.h>
来源：http://dali.xylfe.cn/Article/details/gtyguilbxv.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yvedp.cn/Article/details/gtwfiwjnww.html

[S02] C：变量与格式化输出
来源：http://dali.nanxuanxn.top/Article/details/gtqodxksuf.html

int a = 10; printf("%d\n", a);
来源：http://dali.havefunace.top/Article/details/gtxpyecgkx.html

[S03] C：读入整数
来源：http://dali.0kj1m.cn/Article/details/gtaehnmini.html

int x; scanf("%d", &x);
来源：http://dali.gaohongyu789.top/Article/details/gtitwouoqo.html

[S04] C：字符串复制
来源：http://dali.zdqjudy.top/Article/details/gtwytnggcb.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.jinqigufen.top/Article/details/gtpbgoslgn.html

[S05] C：字符串长度
来源：http://dali.ppjwa.cn/Article/details/gtqcwlpvuz.html

strlen(s)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuyapgipv.html

[S06] C：字符串比较
来源：http://dali.smart0.xyz/Article/details/gtyudyymtf.html

strcmp(a, b) == 0
来源：http://dali.shanyushiyangkeji.top/Article/details/gtozkyuplx.html

[S07] C：数组遍历求和
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsqqznemm.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.yuxming.cn/Article/details/gticlqhidm.html

[S08] C：动态内存分配与释放
来源：http://dali.zhixingplan.top/Article/details/gtcxjqpymm.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.cdnleiting.top/Article/details/gttuhoprsm.html

[S09] C：结构体定义与初始化
来源：http://dali.wangdashe.top/Article/details/gtydhdmrqg.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.shuidangran.top/Article/details/gtlaibfysv.html

[S10] C：指针与解引用
来源：http://dali.birdmap.top/Article/details/gtpsabdycj.html

int *p = &a;  *p = 5;
来源：http://dali.zdqjudy.top/Article/details/gtvmsdytpl.html

[S11] C：逐行读文件
来源：http://dali.kuanghao11.cn/Article/details/gtzeuceuly.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.sxryk.cn/Article/details/gtxcjtcojt.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzibrzptb.html

fclose(f);
来源：http://dali.mhx1999.top/Article/details/gthlenspqm.html

[S12] C：写文件
来源：http://dali.redwolf501.top/Article/details/gtizpaqiut.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.tianlin.xyz/Article/details/gtrtlcjtxe.html

[S13] C：宏定义
来源：http://dali.cheryme.top/Article/details/gtkfrfwikn.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.hongshengwenyu.top/Article/details/gtacxhveof.html

[S14] C：枚举
来源：http://dali.fengsongda.top/Article/details/gteqdenhmb.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhongyouzk.top/Article/details/gtfodahkuo.html

[S15] C：类型转换
来源：http://dali.yanxiufei.cn/Article/details/gtdvmcpljo.html

(double) a / b
来源：http://dali.tian-w.cn/Article/details/gtrrytjcab.html

[S16] C：位操作置位
来源：http://dali.9152youxi.cn/Article/details/gtujglhwpe.html

x |= (1 << 3);
来源：http://dali.fzhhl.top/Article/details/gtanbidmlw.html

[S17] C：安全拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gttgkdafuc.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.hywenlv.cn/Article/details/gtoiqjpspg.html

[S18] C：命令行参数
来源：http://dali.hongshengwenyu.top/Article/details/gtowcteycy.html

int main(int argc, char **argv)
来源：http://dali.yj202588.top/Article/details/gtdaathdhg.html

[S19] C：快速排序
来源：http://dali.fengsongda.top/Article/details/gtcmsnbgjd.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.hfpthk.cn/Article/details/gtfkqxtuso.html

[S20] C：二分查找
来源：http://dali.jinqigfzy.top/Article/details/gtykffybxq.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.aizwys.cn/Article/details/gtpbdhbgeg.html

[S21] C：字符类别判断
来源：http://dali.xuetiantiany.cn/Article/details/gtuepzmmel.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.pengpengdd.cyou/Article/details/gthfimxeuv.html

[S22] C：字符串转数字
来源：http://dali.jinqigufen.top/Article/details/gtczfqmjts.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.yj20258888.top/Article/details/gtgwgnmmbx.html

[S23] C：随机数
来源：http://dali.gaohongyu789.top/Article/details/gtfwybdkvv.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.cashguo.top/Article/details/gtnwrxqyrs.html

[S24] C：获取本地时间
来源：http://dali.yj20258.top/Article/details/gtrnridiwy.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.smart0.xyz/Article/details/gtgzruboao.html

[S25] C：内存拷贝
来源：http://dali.tianlin.xyz/Article/details/gtdbgeccxx.html

memcpy(dst, src, n);
来源：http://dali.jinghuilouyu.cn/Article/details/gtjkjgeewh.html

[S26] C：内存清零
来源：http://dali.aizwys.cn/Article/details/gtdvomsdii.html

memset(a, 0, sizeof a);
来源：http://dali.bjfxy.top/Article/details/gtlwgvxbuo.html

[S27] C：定义常量
来源：http://dali.yvedp.cn/Article/details/gtuogeyqme.html

const double PI = 3.14159;
来源：http://dali.jlsjyb.cn/Article/details/gtnweappgp.html

[S28] C：静态变量
来源：http://dali.svipenyu.cn/Article/details/gtwudeaykm.html

static int counter = 0;
来源：http://dali.sxryk.cn/Article/details/gtkdymqxyp.html

[S29] C：变参函数
来源：http://dali.hfpthk.cn/Article/details/gtsvlgdxlk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.tanke756.top/Article/details/gtorurzbcg.html

[S30] C：头文件保护
来源：http://dali.tianlin.xyz/Article/details/gtuywqkfar.html

#ifndef X_H
来源：http://dali.chenlongwang.top/Article/details/gtaujceopb.html

#define X_H
来源：http://dali.tanke756.top/Article/details/gtygtctwkf.html

#endif
来源：http://dali.zhoulong.xyz/Article/details/gteumhzjms.html

[S31] C++：Hello World
来源：http://dali.xuetiantiany.cn/Article/details/gtyyajimss.html

#include <iostream>
来源：http://dali.redwolf501.top/Article/details/gtapvobhck.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.kuanghao11.cn/Article/details/gtgjoazqos.html

[S32] C++：字符串
来源：http://dali.dashuyun.cn/Article/details/gtzjqdxtru.html

std::string s = "hi";  s += "!";
来源：http://dali.sweek.top/Article/details/gtacdncvjy.html

[S33] C++：vector 增删
来源：http://dali.wangshuangyany.cn/Article/details/gthujnqvqz.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpwjaqwxi.html

[S34] C++：遍历 vector
来源：http://dali.dashuyun.cn/Article/details/gtkslhglzf.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.cucudq.cn/Article/details/gtbpmsmqhj.html

[S35] C++：map
来源：http://dali.jinqigfzy.top/Article/details/gteybwzxib.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.bjfxy.top/Article/details/gtgdibcbhq.html

[S36] C++：unordered_map
来源：http://dali.jiagoushi.top/Article/details/gtkkfxipqa.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.svipenyu.cn/Article/details/gtgbjtxxvs.html

[S37] C++：set
来源：http://dali.andypj.xyz/Article/details/gtnnlhajco.html

std::set<int> s{1, 2, 3};  s.insert(4);
来源：http://dali.xinyue.icu/Article/details/gtttlbbonp.html

[S38] C++：排序
来源：http://dali.mhx1999.top/Article/details/gthekhrfor.html

std::sort(v.begin(), v.end());
来源：http://dali.smart0.xyz/Article/details/gtokmhcpju.html

[S39] C++：自定义比较器排序
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqlhkqhkd.html

std::sort(v.begin(), v.end(), [](int a, int b) { return a > b; });
来源：http://dali.yuanzhike.top/Article/details/gtswgzqomo.html

[S40] C++：查找元素
来源：http://dali.xziqi.cn/Article/details/gtomqqzned.html

auto it = std::find(v.begin(), v.end(), 3);
来源：http://dali.quarkkingdee.top/Article/details/gtdtlbmriu.html


<!-- 参考信息 -->