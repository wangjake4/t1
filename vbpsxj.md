代发 wailian999

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2anomxdgj.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2drrroafg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2wduirkwg.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2jbrwktdv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wxnzqsgb.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2honshedt.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2vcrtwgaw.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2fsvbxomt.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2brcngqek.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2sfazzimt.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2wifqyxyz.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2nomwhpgt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2amktanhu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtizvgc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2dfcefzld.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2paosqotf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jozjdayy.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xkngmsso.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2csqdhyhu.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2sljawuvc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oyajdyij.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2dyilttqm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2udumfkil.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xmvxbwio.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2tnaoohfy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vamwzeha.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2bhnzrwmz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjvkezni.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2orcoqlmg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmjwuem.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2untijxeb.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2bedatqdl.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2izcyaxhy.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfgimdxf.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2tffqxhza.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmljcid.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2lvnnoufm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2gszleyrm.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2oszpzlgy.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2axioagnm.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2pllwdhha.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2zbtlcsfm.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2jkekcnoy.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2mounjlnq.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ncfamxpj.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2eoywiaay.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2antfawhf.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2yfwqxxfi.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mlbowzyk.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2gwywqvnr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2hkxlskgx.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2znfvumwg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2ymrqtrcq.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2rxblvhna.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwidixtk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2zjyazlil.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2sacywlok.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewsmyasv.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2hyljwlcn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2phfijtnh.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dbtdnbyw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ijzknngu.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2icgzdmmj.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2rrmxxrpo.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2xbwdvmhe.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxrbkxkt.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2bypjrczf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uozwrtxi.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ksuzpyqu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljpqgpwy.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vvddrjik.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzwuabsx.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2odpoqphz.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jklcecfm.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2zjoelnkd.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxolxscm.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ebiublnt.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ehztsnbz.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tiojanug.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2mknwjvll.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2imnyeger.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2nlvpsont.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pzhdopop.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqhvyoi.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2xlnyhdkn.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2hjdtyupz.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2siutdefc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2jjwskukn.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jltwmijt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2zuceuxwy.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2gjgvpzwq.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2nvcyddfv.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2pimptpra.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2ieuknbtq.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2xjhkirxw.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hvgxdnsa.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2ssawdidj.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vwfjdjeb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2onwvwdyz.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ppfoihfa.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uuchclzz.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tpyisnhj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2nazrygwr.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2swctzlyp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2dgunxptq.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2iltpcbwj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gyavnuiu.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nqyshnbs.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ljfsvhpb.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2zekvckxf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqzeabd.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2cyeakicx.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2muarzice.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrkvctp.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtmqyibs.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2utegkwmb.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2onhjrcmc.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bmsskxbc.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ysdjpzse.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2aytokwzl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2aryzbbcg.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2hlrrgxwd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2axfceztf.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2svzfedfl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hjszqqqo.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ynlxernn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tglojiht.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2robzyjzr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zdbdkflj.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2biiwkfzt.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ydfbrtkr.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uyccjdzn.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tunzfvev.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2vuuymddo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qpfdbgkn.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rqmeosoa.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vxlbkyxg.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2whmqmbyg.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2knpfhbbv.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yjsycwqz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qdomwosq.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bupwgedx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gzxfkfbf.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ftwhdour.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eveyyhzu.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ppqrxjjz.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2pkhzukcw.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2uyypttps.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2akntiydq.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2jhlpakir.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2shjdvcmu.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sremjjkd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2jpuzupzy.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zeoninjj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2gfsrkfli.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xlntuvdb.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cjeisatk.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2yecqmpzz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dorclbgt.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2tvszkwem.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2macsglcy.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2cptrmbtd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2fufkcvby.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2rcorwsoj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2uymassvw.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2auujjccn.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2vrfmroty.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uzlgzbnc.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2devtzdrm.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2cncqhppi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2smijkxon.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kaquyngf.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2mlyuwnwh.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2tceouxhw.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2tdhobafj.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2smiazfrg.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ctpyazjq.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2vspnuuxb.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pkiifgtf.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gavhuyck.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2sqjerpsd.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ltiivywh.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzryqdc.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2smrkngeg.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2abfqmodp.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxkrvuk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2sdrxcask.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2djmykzfb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hztsdrxd.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2igeugfjs.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bbpicwyr.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ehwtdvlt.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2zmuuuldz.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vzopbcpg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uwimnwqf.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2iimuxcay.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2mpfrtfiu.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2qbqllhbl.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dewkhzxh.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2vvmuscpc.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2pysllytx.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2atnpaukn.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xljoxgre.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2amoykvot.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2wngjuctm.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2fvqvdkla.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2jpseihfj.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2tofgopob.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ifbhedqv.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eprrypri.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2gaqrdrqy.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2kmmduytr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2beumaqqx.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2nqyvcuys.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2fmbpeqhy.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2dobdajck.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ylalwssi.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wszpjepf.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2argrghvo.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2fujmtivx.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2dpuoymph.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2ecpcuxti.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2btambwrg.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ihqekrpo.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2ecibughm.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ljueuonz.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2izwugikp.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2okkidlbz.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2mdwjzsgp.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcjdrbg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2phmpfyzw.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2esfwnvad.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2bzceuxku.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2zlrcyehl.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2ciotofts.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2byzqngjt.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2vhgifowf.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2qlzpwhih.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2anehnlzy.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2nfkpfqzo.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2njogsuup.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2kmozmucy.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ipatbfro.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2mqcerawy.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2wbraoaao.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bxtlxxtg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2dfzqiazb.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2wqkpojvj.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ookhyrsl.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2aburnjhk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nginlurs.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2cwtvblyf.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fgzexjck.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2mxdbrffv.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2zsevfusc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2bizroscv.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xbkuaqrl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ormhzsmw.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2oipyfmhu.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2oydkrpnr.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2hcobwuqd.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zmkklcug.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2ycjekghq.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdzbmlr.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2scojqlhu.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2qtdgshqk.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgewaif.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2nadbgzji.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2vdxinuyt.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ccxjpojr.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ieivjehs.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ilhfzxto.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2vqttdobm.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxhtbpz.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2exlkgtls.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2aohemizd.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2xyiqilda.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2fqrgwnnx.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbfihxq.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mlrdxvzx.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2kgmycwag.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lusggaub.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2uyijmviv.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vzahkqpk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2yknjnqqp.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xbybhosh.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2nasyusnm.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2uzdbvizj.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2lbatlrvs.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gykmqvpq.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2wofjvezf.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2qldnmuxq.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2sjopbyys.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2ypysyskd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2ghijzouo.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2jxuhdngg.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2tfzaqdcj.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2kpaqdkev.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xraeusxx.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2tgucllif.html


<!-- 参考信息 -->