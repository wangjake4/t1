代发 wailian999

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2baxzbzlp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2klpwaxyf.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2gsefjjls.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2onssrjpu.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2mkgijqxz.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2thilrogl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2mfoenfqq.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2jhkvexex.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vtgcckst.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2dovpbgne.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2kbazzzic.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2lkihvonh.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uepqypxt.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2tttwmqcr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ivrisvhk.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxsoabs.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2rqtbrjrx.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2cjsgejlj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hxwyyvld.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2redpxhaa.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2laddtofr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2thqeasrc.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2rqccpojt.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2fzjdavgv.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2tnetkfxc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2cmlrznla.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2cqlboyzv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2ngnqfiev.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2dvgcuxug.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqjxeudg.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uadzvhkw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fzwdlfjl.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fxenljio.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ecaqzgvc.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vsttzkqj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hpwcckzr.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2nnwqrjwb.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lbhakouz.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkkgmkg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2jcyjkloz.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2kdnnerlz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2fslxtowx.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bppfcnnb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijiizlfl.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2tjvslxok.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsplvdx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ufnpmhnh.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2egrtxkkk.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2mlnzmvgs.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2nnhbvitw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2guqpokzp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ywgisinp.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2txnpdxam.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vauqxuho.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2limanjbk.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2kclbscun.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2lyvingvb.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2otyopzgv.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2kxadsukb.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wtzlkakf.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2mkvqrgzj.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2skxyffpi.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2rsrucejf.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2dpknenay.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dhsnimib.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mynfsevo.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2slfqxfti.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nmpbxckc.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hvpidxfw.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vppekxdt.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2btpdzual.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2dzahdtqh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hugiarwx.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2rxcwvgzt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rwgwykqx.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ffwyalis.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2lypubfhh.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lpcobzkk.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2xccrdrpr.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jlujvhos.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2puasodhk.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxbgplp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ryxyhnga.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2mxunipji.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tgxjfxfe.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2yxxukwwv.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aailmtki.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2alaulbwh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2edrxcdqb.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ftcubler.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqozjqn.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2jbkzlitr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtfwzjb.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2bfcqgcsx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xchaoxyv.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ocsmnslj.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gdsvhqgy.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2vrjiblfu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ikfomags.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ydvdldyd.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2txrjvcms.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2kysxxajc.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xpkilaiq.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mohsuqtb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zvhagbup.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dblfqyrf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vmsnfkwc.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2eanhxhto.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2piigljwi.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yorchcvn.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2ltvmhhof.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2nmujjjlz.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2mqlynvdc.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2wedrwxdz.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2minfpxrh.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ktrecunf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2ynmoajep.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ckjhjhfz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2vqsldhuf.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vufukrvu.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2drowzdoz.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2xmnakwep.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qvpewlym.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2nkuimglr.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2hesdvhpr.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2hfubufwa.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2griyxrqo.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2sxdybgnb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2uymzzcdd.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2krpmhqrb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2nrxiwzvn.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ebrcvuyr.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2njpvmfdr.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2bpcfctab.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2olytgdzo.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzrcbhf.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2zhzdzcuh.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nworlgrf.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2tmpumrvr.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2iwsqghhe.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2yvscogow.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2fcoglcsw.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kodouwys.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dxrqoptc.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2evmtnmqo.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2brvrruuu.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2vnjlzfwj.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2qwosozqv.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2kmfoqxdl.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2rqhelhzm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2etafuggq.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xelwcvva.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pzucoqkq.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2giavxili.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2gylkdcpz.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2sfhqpzzy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2pgkzyylk.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2uvxjizlu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhzqdfc.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ydslnovi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2yrrgxinm.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2uxmqgxag.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fmjvkzyk.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2gcflarzp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2abtaamsp.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xetefiwb.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xouwnbov.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2gswadikf.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2rzsnmpbp.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2hqwgyksg.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2olbdeczo.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2mszuoori.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2dejdcdha.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zemgwpht.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2kskxdaid.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hirbufto.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2jkyphoud.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2poodyybg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xqrmgaqr.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2oruxdsuc.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2symehuqk.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ljijtcjr.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2bphdjfsc.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2inemclic.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ksaihmqx.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2plyjdcxf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2rkslhxte.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2wtoobuff.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2hhckkpzn.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2urakzgqs.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2nwiibtjq.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2okwpjunv.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2nxvcqqnm.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2rhqcqyyw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ecjmxevr.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2tkxcczic.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2clbsfcic.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2fpjcevua.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2orhrtbno.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2kiwmfcdc.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2pmfpokmj.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2zazkvjxq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ueezkmnp.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cmswnuhp.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2dymnkvvm.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2plpkdure.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lszdzmub.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfbxqhx.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2sdxspreg.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2acipbrqg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2lgdtztvy.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2wntamqhn.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2gmxodmiw.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2sutqbsci.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dvygrvpp.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2kencbbun.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2chouvnwz.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2wsucndgk.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ihoecmcj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lflthqsc.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vppodvhs.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ucluwtkm.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qooqsyqq.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2ytrjaauh.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ssevikmz.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wufsskcl.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2hxhhfhus.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2blzwtnbv.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2pwaxgeft.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2ekwoyhdz.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2idvyttax.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2egubmvxh.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tyrkiyyu.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yqltjauu.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ufcempgv.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2uvshbkfw.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2hfehwulh.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2gdahcoki.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2vtvytuxv.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2nedgteru.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2laaevyqx.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2xtsdwewx.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfztnuby.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bmddonvx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2ilgdhzki.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2kvbqrapp.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2reyibqod.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hmcyfuuk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2elpoiutc.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2iqnqiztp.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2rdzwxtyt.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zuyseydv.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvxhyxi.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2efdfcnyx.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2tyolhati.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2epqpwatr.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2rayjvhqa.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2hcngifdv.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2smekvnoe.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rrhnobnj.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2stbusqyh.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qjihdswn.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2tkussdnt.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2rllbzjrb.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ivziscjw.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2jqzlucvk.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwgsjvvt.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2diyszdha.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycfqwgcl.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkduobq.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqmvqle.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2vqpwmtup.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2tesuktha.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xgvxhthe.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2qjsvvqof.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2ruizpvgo.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2zeplijcs.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2maswjyiy.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2utqskxca.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ylsauqtq.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2rcrcctvm.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2viqytnwk.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfwqimj.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2oponmley.html

#ifndef X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2qwgzoemf.html

#define X_H
来源：http://dali.zhijiandao.cn/Article/details/gt2ibwuaboi.html

#endif
来源：http://dali.zhijiandao.cn/Article/details/gt2hsbgxkci.html

[S31] C++：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yalavvhw.html

#include <iostream>
来源：http://dali.zhijiandao.cn/Article/details/gt2dfjfvlno.html

int main() { std::cout << "Hello\n"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2gzvkhbsc.html

[S32] C++：字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2dmxlxkmk.html

std::string s = "hi";  s += "!";
来源：http://dali.zhijiandao.cn/Article/details/gt2kitfdypu.html

[S33] C++：vector 增删
来源：http://dali.zhijiandao.cn/Article/details/gt2bkrhxunc.html

std::vector<int> v{1, 2, 3};  v.push_back(4);
来源：http://dali.zhijiandao.cn/Article/details/gt2vlqmqmnu.html

[S34] C++：遍历 vector
来源：http://dali.zhijiandao.cn/Article/details/gt2orlwtuqm.html

for (auto &x : v) { std::cout << x; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lznlrbwo.html

[S35] C++：map
来源：http://dali.zhijiandao.cn/Article/details/gt2mkyztaoi.html

std::map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxxmpjh.html

[S36] C++：unordered_map
来源：http://dali.zhijiandao.cn/Article/details/gt2fvftnfel.html

std::unordered_map<std::string, int> m;  m["a"] = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qdmyccej.html


<!-- 参考信息 -->