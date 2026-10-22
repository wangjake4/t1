代发 wailian999

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gphvadai.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2bphkdaqe.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2erbblufb.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2xhofkntp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2tiyotrry.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2utcydcoo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2dpcpjcrb.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2kgrgzsly.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2isyqgsjv.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2lhejpbcg.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2krtjtrvq.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2qlgpksfo.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2qejzorox.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ezngzkyr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2amurqbpv.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2pqshinfd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwtahjvn.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tjuqdpga.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sxnlrexf.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2lequhfpk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2taasvwmo.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdbzugk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2dfvflsve.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifewcjzr.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2frpmuvmu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cplzxafj.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2zaocqqbz.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2brhjvtxa.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2utsjumcu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2cmwvvoli.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2cqgibbem.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2snjjpsbe.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jabnnsdp.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2xbettczf.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mujcxlfe.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2wcbnrsxy.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2hxcszrjw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2svbnuohn.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2aavytizt.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqblepjw.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hkcuakjl.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2twdmbmxh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2riqmrwjg.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2vcunpxmz.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bplwaqec.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2npgwivfl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2efnbrjra.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2rmdeihgf.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oydiyvlb.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2zyglgrtt.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ccotnmoi.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2nunctcjv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2vnuraacs.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2syatkncc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vlicedor.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2xyoctdco.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2lzpryzxu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2hzmobojm.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2sssbldwq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2fnvcyskp.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2lymlawvs.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2cdrbryiv.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ttxhrsdb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2gngyrosz.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2puvzsgtx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tcbsxaqr.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hxorwrsa.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2akhxmqmz.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2uroledvl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2gxzhfsan.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gqdsobom.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbjbckne.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2fnxpkolw.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pljqhnqd.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2eshbzwuw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2uskqwksv.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ozxwzvxq.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2tkaokhkw.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bqkjwhcc.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnodcpdt.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ncjbqrcp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2lezzaybv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ywqgirws.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2itiwinby.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvfsymr.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2abvqpltt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpvvwru.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmwhdfv.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2qsrbowgp.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2okmntdze.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2jaubjtli.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2pcptomph.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2kzvmvbak.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2vcznzisw.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2lqbxzuqr.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vpvjalwl.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2zfzadddz.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2avpydlta.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfzxfwr.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2fnbgfpxh.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2regavwlq.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2ssflzsbc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wckyhtfh.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2hoxgpafp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2hwwyijfj.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2nzyvyhov.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2yovzbfnz.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2iojyjnwp.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2fldegbwn.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gdsqxgsx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ipdkyxht.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ognfawkd.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2lofitaro.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jekhnanu.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmowbrmh.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2exoureyg.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2vzehnljt.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tqmtixab.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2arlklcao.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2eyjoznff.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2siomdwqd.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2cbvcxbyp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tlkbhuja.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qshujrrj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qscviign.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2btcnixgc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ztqswtql.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2vusuvrvg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yzhinggg.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2kmtahkpu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uxtqmpbc.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hvlglixa.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oxziaqnw.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2fsokbtdu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tmadqvqw.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cefkwatn.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ftyimfen.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2xcoiqcfp.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wsyfgtak.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tugoishi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2nvennbiz.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cvmzduaq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dlxtpehe.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2cbtkznzu.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yczvqbpi.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xrhivydt.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2rphmzrok.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2stkazcyw.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2cbcrkcfa.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2okordkos.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2udnqoccz.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2bcfdvyxb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2zpylycjy.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2djsfgucm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2ykxcwmtj.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2oronvwkm.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2yykwegyo.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2iqornpix.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iohwuwfd.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2bhwvhbmj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2mcpztclt.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2przypddn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2kqfrylzh.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2wjovkyfc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2bczzbzlb.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2gxscxuev.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2ctnrhjub.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2jwtxmiaf.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2gxkxncbr.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2tpcjzaxq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2hdhkrzco.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zwuzesmr.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2ypggotkv.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2smfmsjxq.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2pcjnpzej.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2fyyqejct.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2lgxawzph.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2rldurzay.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2osbwlaah.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lgoqsbuv.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2fkelcdim.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2iisvfnlz.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2xqignsio.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2dwvkyplv.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2tcizkrin.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2acgshyij.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2mwzwhdqp.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gyxprdar.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2didlbdyj.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxmzlyw.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2bilgfovi.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2hreskvoy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2jroovrwm.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mqhnwmja.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kxrtwbob.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2fqzhxygm.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2jnbkwiui.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2oabfkahg.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qtmfoied.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2pljwrwjl.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2btbmgczg.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mbkhkmup.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ibklgjbe.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2abprzifi.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlhgzku.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2pckajrdd.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2aqcpfqzp.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2tbdsoped.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2tomyqphl.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dasbhcql.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ywriaftn.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2eikudndt.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2amfumwzw.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2vgwbjfcu.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2zvppicxx.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ynhxbyqc.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2qlsypefo.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2txkrccpg.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ttjduluk.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2lcxpghal.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2ijnxcgkf.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2wwhlzgci.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2shbhxryn.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2advynhfo.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2lgyuqqyb.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2urdmudri.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2perzogwa.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2gatzfmtj.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2klztyhji.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ilqqyljn.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vmzdpljt.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2pxwbvsbr.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2rhlhfqfi.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2lhvulakg.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2jjhaphsn.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2durdytzd.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2qnmhvzvp.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2rqsvqiys.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ilkfevyy.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2edvebobt.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2hyjxmpim.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqmhccm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ydbuulaq.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2lkadtyah.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhlhdqm.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jvxjmmnb.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2khblqxar.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2rdermmcq.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2kszaxbbh.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2cpxbiqoi.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eddrmmze.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ttazjfwo.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xnabxksk.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2hgendbhl.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2ydkanicj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ovmpwgfd.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2inadmoyj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kkregurd.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2izplkoxl.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2dnmlrcmm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2awdafiwx.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ovudjtou.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2cyiiqpwh.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zyqrrjfq.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmngyoq.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2znfcvyeo.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qlegsqzs.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2hnmwslgi.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2tjusbciz.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wccvybzk.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ucqfvkjq.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2nvjrpvot.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2kdiprdat.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2afmfyewm.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2kdkspiwb.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2onmkqxjv.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ffswfazy.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2fbylysgd.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbavbapx.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eridnkjv.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2eownuwtm.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2bomaghdn.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2nfvxafbq.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2etsbudfl.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2jyblgbxr.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mwljiijf.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2rhyigoua.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2vxnapxhz.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2uzobjgmu.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xomvogpo.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2yjqxupko.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2lherxuks.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ngesdlyq.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2mtrkpttz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2zaymbdlf.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dswboito.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2leyspirn.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2fsdmatdu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2vorrkxqj.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2vctyvqcq.html


<!-- 参考信息 -->