代发 wailian999

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqpkbmpo.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2moapoiid.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2sjcprohv.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2htfhqedw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjuzour.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2apwftphu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2sfuoxkqe.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2hniavook.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2jmyziado.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2toxgdpko.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2emdfcduk.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2lmmpiaim.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnomdjxw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2ycwumhnc.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfptvohg.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2wffzfnkm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2znysludp.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wrylejzp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yffwwsja.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2bhazsram.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2dbimlnry.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2phoiondx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2kqsxljbk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oqrjkhvy.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2dmoomvtz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ciqtoxip.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2oybmdlmm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2trfkejbp.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2pwreagfx.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2acnmhtyj.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2vointpgu.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxbrfbu.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gacnmukw.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmikqwmg.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vbreccrr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2gpsdeqys.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2opkzvwvb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2pthlnuqa.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2kcutjxuc.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hfhxbxwp.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hjlvllug.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2tovdeyke.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2rdnlggfi.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2rfcxqmib.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2plczjzmq.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ikgjrfxs.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2wouqxaii.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2klzsghbx.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2coaxvban.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2lrhisqdb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2jsqsvlvk.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2knfcjuhb.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2fijukneq.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ythsdrel.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xpldhhvw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2nflpzuyq.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2ayvcbwdb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2yituohru.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2yndmyqse.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2cqzsgrcm.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2jntbncnz.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2sctcqkqa.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ilshvlyz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2vepricom.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2xgzvudkh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmyrqrnn.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2dkjiqjlk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vwasqbrm.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qfclmjjv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ijgnrlia.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ucutsiun.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2saaqcuka.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2tdbsqsqu.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2awhhtlvl.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2nlyqdnmb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2xrsudssm.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2ivkxqlwh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2kbaijegv.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzwcvin.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2qhkcvzjj.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2fzzyjnxd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2jalqihza.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcqevqei.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jswhqhmz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2xbiunrpa.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2cphfugrr.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2bwurzkym.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2wxtudayi.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2vvnoliyf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2pcuqualu.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2jjkdkfsx.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2qcvtazry.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2gtcfdahx.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2cjwfpqjr.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2nnmzkuoh.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2njfwobml.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2goefqmac.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2grmmotoq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2vjhkomsg.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2hjzpllnw.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2eshbudnf.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2qhtctlkl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mrixdirs.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vngjmexn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ssrxtfek.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2rwekrelw.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfakiwf.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mnkwbhen.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgnygcd.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2fgxxsseu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vtebcddd.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2yemycadq.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2qxayrfaq.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jrpiyodv.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2trmragol.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2dmcuxsdr.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2yqsrinqt.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2rvbsceup.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sgleslrl.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2frmaqgir.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bbcumvqd.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2snvbpohn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ogvzfhlo.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xnfvrdne.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lqadrdoi.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2qaqfvbkn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rrkfufxv.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2fxgfvkkj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2evhupptv.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2srbuzqjy.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fhsgripr.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2lkvcowfq.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vujvqwwn.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2hftjwdbg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2uupjewfr.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xkpcqcqq.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2khutolcw.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2meafadlx.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zutajxyl.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2etyvhcuu.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2eesphmhs.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2pfplkgdg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jwfrdejk.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2faosslif.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2fytvagwk.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2rvtkgtob.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2byvcrqqi.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2dnndyqcz.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2jirejllj.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ufarnmoo.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2kvddovay.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2sgujipmo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2gyrmgkvq.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2lkfqdmrs.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2hfcilmhx.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ftuxnikd.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xxaxzekt.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwktczz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cbnnufin.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2fhfijhzd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2vsuedvpr.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2zliirdmo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ehfxfeup.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2wervzjkj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2zeutwool.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2mjjfcjpg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2mefakwbj.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2bvgcemrm.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2hgyapzvk.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2wqcaoqaf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2jgweppdn.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2kibeogkv.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2yyfdflfw.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2qrcjqaas.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2qbplqzei.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2gdrazgjt.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2uzqiqyxf.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2qopjnghw.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qejxurvy.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qlezoocs.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2lfyssqcf.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2pjijmnhx.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2asdxjxxs.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2zuqylmbk.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2rrlgownn.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2pdkspqfz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2txkihuhc.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2czrdspjt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ltlnsoob.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2oftxdmyg.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sagbwdig.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mroksifr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2zyocsbkh.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2qhmosjbl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2udwkxgwh.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2yfcqkaly.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2eqhwqxyk.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2gcqlccqo.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mqfpquev.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2hatjpsnv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2nitsgbpo.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqidnpq.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2thjachdb.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2lvffkzhi.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2sbblusie.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2efkrnlxu.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2mejshnzo.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2pqonhrxi.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2ktxjkbtf.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qqfmvzcr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2wzxzmtfp.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ugguomvj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2udrjgefw.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2aulapmzf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2duavorwu.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2gjsfhxgl.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2hizdypmu.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jnrijghj.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2nqncybvt.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2tjirltfy.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2splkhzcs.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2qwupotch.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2exeksrci.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2rvhjqboq.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2vvxejpbt.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2wxyftulz.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2unqpsfah.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ypacvpim.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2isjirwni.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2inttdyhx.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ailrqhfz.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2fyccasla.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2siyaufwx.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2imijsjsn.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2zavvhsab.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2glmqzkiq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2vxcuuwvf.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2sccoispb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mlcizmyd.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2lryvhukb.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2czodycto.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2qsgakodq.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mkrbnxxp.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ddjawpyz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2cmrhbkuv.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qbgsuycz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ohixojdf.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2bjbuvjov.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2dvdiaoux.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2fdleukis.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fhtgxgni.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2xwyearmn.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jcjceenn.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2gjftilxc.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2rivnzabw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hnapgaao.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2hasbplzh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2etnrskje.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2zxsgnelc.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2upnhbxct.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cgfjtudw.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2lvvwqlis.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2djmjodwg.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2waqphgcr.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2wayoswqj.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2mfvvfqcs.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2sbkegjli.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fvgfyrfq.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2msddzrau.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2vlomtirn.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2uambpbwj.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2yqzjvuhl.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2qaqyzkqg.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2pujdxqbl.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2cxbdnrsm.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2gjwhekfc.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2nyveemmb.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2hamuvufo.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2amvqmfnf.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pezucact.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2mivqupto.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2qwooexsw.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ximgmzpb.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ypxatxuw.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2errcibbe.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2pwxibjot.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2unoifgrm.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2ghxcrbew.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2vvqglmvj.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2gkttgmoo.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2vgkowrmc.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2kzeukest.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2lblqzwtk.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2fahxbthb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2qfqhhvyj.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2eljfbcup.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2kfwwzutv.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2dekvimqu.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2svphaijy.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2zsrbeuhl.html


<!-- 参考信息 -->