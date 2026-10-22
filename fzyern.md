代发 wailian999

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lifrmapv.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2tkarrozp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2igqgwlgf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dciemlhg.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2apagwvjk.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2aktpgukc.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdmrtuv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvxpxnon.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ffxuivtk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2mimaopir.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2lgnampnu.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixssdizu.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2qutzutli.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2teblxrhu.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2wjnzizli.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2qackcjbh.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2ieipxgbp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2mscblrbt.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2iodzblmo.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2gvljxvbt.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nukpuijq.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2uxgnbdnp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2zmhmkjtx.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2mtydfpti.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbwrlysm.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2pceiecbc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2qvfmnwmk.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2msdezjtz.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2amlumzyq.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2gzgivmeb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2tlecjvnh.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2aqptqjdz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2inylbben.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2stpdztys.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2baknxxui.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2ouhfrqnm.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2tsxwlojd.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2rwrpqtnz.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2orjfkars.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ecfnezfe.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2nprkbikf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2yzygmsfn.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2odrjqupj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2lqntkqmx.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2bojvfugj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ojbpepat.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2uoagpfac.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cmildxah.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lutxljqj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxbvuua.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2eblniwho.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2unwozwhe.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqctusu.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzzoocod.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2kxfruvcj.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2jtryqnaz.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2imgojguz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2vinghftx.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2gckynbtu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbwjvgsl.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2zepukncx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2szdhskni.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2axlubsye.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2gtjhnxtn.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2xlowkvvp.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2djldyztb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2ajkrbrwx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bhghbnlm.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2bezbcesb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hkwlxgaf.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2suaiocxn.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2wafvsbrf.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2zkwasipn.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2wrryvuiw.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjuuubi.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2euzafcui.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ehodflwu.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2hgropxsm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2mlaxtkar.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2qmyreyop.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nymlequb.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kttblzyh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2irogdhfo.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hitgjxju.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xxsxksex.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2eaowuurl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2umlczcdd.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wjdkccuo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wiltukiu.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2oqpkochk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dpkhuivu.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2wewqjnbc.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2mofojgiq.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqawrzzj.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vouyxtcu.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2sdppmqun.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2fcjerniy.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vwlchslp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bhdlcffc.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2cgsolggu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jadmspdr.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ihfouhif.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbtoqul.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mjctpbsn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sfgostii.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2stzygiuc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ishbxwtp.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2vzfahude.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yrgtvjqr.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqvyhbm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ktwbawet.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yyjkcihh.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zpwdrqom.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2ycohltff.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xeqrlxun.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hadfdepx.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bmkrqarf.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2wclpitny.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yvavxzeu.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vwhvhzui.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iwgnfjux.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ippimffk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2telfreqo.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2xtizslvw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wxuozpyn.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dxtuapzr.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2efunvoyc.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2tigbxjts.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2crxxjqtc.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2aelkvvte.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2icbhchbc.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ccqlyrxf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2iwonglex.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2iodypllx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2megyxlmy.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bdpthikg.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ymbbjqzg.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2eehffdjz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wpfrqkeb.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2wjfxqvof.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2cbltppcz.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2kyabovcp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2mjqxxdad.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ffoypzpf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2coiadgfm.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xftkbfyx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2woifinak.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2myjqjimk.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2odopvxld.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2jcxcveqa.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqedrus.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kxzifojw.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwcnuvp.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qxkkoqwe.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2niwebwbs.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2osjbzipp.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2xniorsbx.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2bzkzfzzb.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dzkvazbf.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ewbplxei.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2tmomxknb.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2rmepubar.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ibulshsb.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2oefcntqx.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2wktryzio.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2nxspkfwz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2sylwjuhl.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gggqjkzo.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ermdluav.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2aizgoapc.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ujzhyjuk.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hgmcxyxp.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2rrsdalrt.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ouvcytou.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bvqbbalv.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2clkarvte.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2mwuistpn.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2dttjbsyl.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ovwrzfgq.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2mbdjdfjs.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2raxzvltl.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kvhwhqmt.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqrggdd.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2tdgcdujo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2qylbsive.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2klavagwu.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2smtfmjqd.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2gvhhbbdr.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrfyjkb.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hirkbjsw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2tlqptbmw.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2hjjbznub.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ifsrlzky.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2fuffugam.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ppnufjfl.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ursjhuiz.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2dhiyzpoz.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ybuiqjhj.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2sgjykqeo.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2cgkhtttw.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2uizehqcs.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2asjinrjs.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2befrmbqj.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2noxqcqvt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2wompkflo.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjlqmfc.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2agtfeqtk.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2altkopme.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2mzpzhcau.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2vjizavxw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2obsqgxdx.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2gsjbtknf.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2jjrglgpq.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2mpytiulu.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2geknzezi.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2oefbyqgw.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2bracqlgy.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2gslrexnp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vjiwxjzs.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ptiivavt.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2qnwdaibq.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2yhxztcpy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qnhymgsk.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rtzqepyf.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ctkgwzyt.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2fsgtnxaz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2xsgnspaf.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2jebrydqp.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2msksmdqz.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2amnwrjkt.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eytldpif.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2rxalaxie.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2awaipvaa.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2zezkhnun.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2pobnhjsn.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2iposdcqu.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2zkpmqozg.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gbgblmkt.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2hcrdoydr.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2abgpoupg.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2qhyrcefz.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xantyoaf.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2erimjowl.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2vsxfzypo.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2zojhmkij.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2svshjwkj.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ameptfvs.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2tmencybe.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2lqnraxsb.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2usbbvkxk.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2nrgzyugd.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwtxxye.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2dlcjhuyt.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2qwbjkxff.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2yaaadvmc.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2tnmvvunu.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2usfijsyl.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2mbiyaijd.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2pcxiuysf.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dwsugzoa.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2qocqayux.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2yxcimgew.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2eyqsptui.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gvikjrpf.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2pbyeqgoo.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2dnxliyce.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2puptadwa.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ambbkpzn.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2jykkdszd.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wsjjkywx.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2pqumqrjg.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2zttsdhqb.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibtkvlwp.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2okkkxjsk.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2hgrxbtza.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rljtwins.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2sacgozji.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2mjsepbuh.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngqmnjvl.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2cyeyowwm.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2rnvsdnks.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2zlyyqrze.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2wcyplqdj.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2vzbogjbl.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbigxae.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2ftehstyx.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2faruvyki.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2kpgagjnx.html

time_t t = time(NULL);  struct tm *tm = localtime(&t);
来源：http://dali.zhijiandao.cn/Article/details/gt2ofqmzqau.html

[S25] C：内存拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2brakwiea.html

memcpy(dst, src, n);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqbqxeyu.html

[S26] C：内存清零
来源：http://dali.zhijiandao.cn/Article/details/gt2hjxjpzuj.html

memset(a, 0, sizeof a);
来源：http://dali.zhijiandao.cn/Article/details/gt2bsuqknzw.html

[S27] C：定义常量
来源：http://dali.zhijiandao.cn/Article/details/gt2mgsoowrg.html

const double PI = 3.14159;
来源：http://dali.zhijiandao.cn/Article/details/gt2lddiyjyd.html

[S28] C：静态变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dtllgslo.html

static int counter = 0;
来源：http://dali.zhijiandao.cn/Article/details/gt2iobkrdig.html

[S29] C：变参函数
来源：http://dali.zhijiandao.cn/Article/details/gt2chfwxrho.html

va_list ap; va_start(ap, fmt); vprintf(fmt, ap); va_end(ap);
来源：http://dali.zhijiandao.cn/Article/details/gt2jpsmpigl.html

[S30] C：头文件保护
来源：http://dali.zhijiandao.cn/Article/details/gt2sceasgae.html


<!-- 参考信息 -->