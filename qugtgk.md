代发 wailian999

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2eibsbomu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2tpqwmsel.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2itwotbcm.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2datslbbh.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhstdvol.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2uhgfemno.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qqtcfqtm.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ovlqhyrd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2btmyhkgy.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2mfsldpud.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2owknzwhk.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2smfzdvkl.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2zppghlyf.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2kysojwdd.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2rgijimlk.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2olapopmd.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2wkfyrvpi.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2gqoowada.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2eurjmsgj.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2jtmvvqpd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mnxtiocf.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2vcacimvd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnrleyyk.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2glveinhu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2tvlzklfj.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2wzqgakgk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2cmbjsdjd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsgzbwib.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2bprkhabq.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gfwnxeaj.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2nkpjbnjo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcppgcau.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2htgrkfbm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2xyagoerd.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2bwskzskm.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2sulienoc.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hhfmvxvo.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2quryebmx.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2nnsynfls.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2wmvyhypt.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2rqrvfarz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2sckdvmav.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2fhvjyniy.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhjblxa.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rqcefquc.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ezxvuauy.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2uigigbpi.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2udyvredl.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zczqybpr.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2xjrwcmxt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2ftqnyfnv.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2fpfcmdsa.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2eocizbqz.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2dzwkricy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2oneyzgpy.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bsrupthu.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2fzhtznvr.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2edtlqkkq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2sgnwrlls.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2tqwlwhtx.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2gttyfgbq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqojazyo.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2tnqmhbwu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2uuytqjfq.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xhbcurkc.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2bkmkjjii.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ffuogvtq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2iblyopnf.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2ltmmjqpt.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yyghlchy.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qohljsxe.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2mhwkaips.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2splgttnv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wneutvof.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vmxujezg.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pesjickr.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2uzkhzbiu.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rtyrrdil.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2ftsgcqgr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2jnxtdsxc.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2hkcwqqzx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2mgoiqpmx.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wnkjwboq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2iilfqhqh.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2ntkfhech.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ggcpfrwj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2webwhvxw.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcukpgu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2emgqxhcl.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2etfgsmjf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2tifenusx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vihhicui.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2iopnhwdj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2imeogjdl.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ixsxtibf.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2jpmideza.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2wutiobca.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2oliwnblb.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2jknymzob.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2dsxdevmk.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2kxodpakj.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2dckmxyxm.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2twuqlycz.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2ywbgklib.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qsfewlrg.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hvtdycwm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2psztybdg.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dxozoshy.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2uwxaznod.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2cbupvycb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2upmdeosp.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2egryayqi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nqmbanfr.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jvjmxwrj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tcotnizj.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2dhoqcsfh.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2ljabcoux.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2swqdmfhg.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhzhhxrk.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2amwvjwvj.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2znffojeh.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yngfwiur.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ldwhcnjw.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2pigtkybf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hbvctssv.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2zdtdaxqm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ruxnrroq.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2igvgizkv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ofysnlee.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rxantqfn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qcadmwkc.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2fhknyxtj.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2argncomm.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2twolthin.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dlzxbjkg.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2bxzgpbpy.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zxeontbe.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2vhvmhvib.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oeotllwf.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2sixmfrob.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2plvkcczj.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2xoqpewls.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jqwysipg.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jhbczacf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2keniohvl.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2rbzyiosk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nngwbefw.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2yecfjqku.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xhompzdk.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iofuihpy.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2stjxnqhh.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2wzkjtiyz.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2cowgjoid.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2ljoefogd.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2cldnjerl.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2zghlnyps.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2yuerofxa.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2urjaqxnr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2vykevfrt.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2figtuzzu.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2mbposwrv.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jynlqrlp.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uxaqonmf.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2igtvohgy.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2wxsleiav.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2wldvwwcn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2yvjapopm.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2ajhrrlsr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2laimqwuj.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2uzvjbdrj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2begfuwmi.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2tckroopi.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2kifyvupd.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2catxjjxt.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2elfchwhk.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2atrgjgyk.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2fronsvng.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2xcyrgsvl.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2uuqdiqag.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2zuyzsjxt.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2eskyjcqb.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2jgpxdycx.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pztjhooz.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yniqnxkn.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2xmaregfa.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2yquzykid.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zbwcmnnv.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2yefmrjfd.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2cceaxbvm.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2lwdpdcqu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2uwnoullj.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2fodgsoax.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2btyfvyvx.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2vjlxvjbq.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jdevvfdp.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ydiewnng.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2puxnlyvc.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2sykmunrl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qkrdyobn.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2pidggegr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2thikbjph.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2qivazhds.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2iyyonqmv.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2morvvlkw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2lcftcueg.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zoqvmrhj.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ltptokix.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2uittxfmt.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2ehhvwxeu.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2onjxlols.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2ujyjsmra.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2lgbpffwb.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2giromksl.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pomtzhwu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2zgazthxw.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2auoweuew.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2mtcngmil.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ojycfrcj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2kjatshrs.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2nxdwdhdk.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcgbdmr.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zowtijxc.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2ehynlbtf.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2bnjtphzl.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2jpdvdrej.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2izleheyg.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2ubhtqxlg.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ephiceql.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2xmqworhy.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zdesbpxm.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2pywbvgsb.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2heeclfkw.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2peecoiwy.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2xanrculk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qxsiefex.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2nnfqqffj.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2horsomvv.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ugvwsnlh.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2zimxxbue.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ofxgswaz.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2kovmureb.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2vfkwytid.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tjpcgxiz.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jqrcgdsv.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2gsqfpbdi.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2mhchrech.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2khgpasnu.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kqlwuyfi.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2ymocwwwf.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zikncttp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2knphrwjd.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ujltkicl.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2wdinvusk.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2rtsflkuw.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zuyulscm.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfdytog.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2uivlmamj.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2fghgkzlx.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2jljdgsmc.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2xnputscn.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2eosajkjt.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2deopkoed.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qeyvokbj.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2qvdztska.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2essshedc.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2huhqaqwq.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2gsdgtvyl.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2mobhozfh.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2sayglqxs.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2mwihqrhm.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2kmijdkfm.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2cfesjcsg.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2mimsbayp.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tamlwvtb.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2csgzpoge.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2fjmljbet.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2ytjdjgeh.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2emuzuasc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2esyuyhyy.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2nwkgqnri.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2rxdsjybr.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ottxrenh.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2juhggmzh.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ogpfsvvf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2blmsoako.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2hedabfin.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2emudqcee.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tazztrbk.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2klyputsa.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vkmjieca.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2vmohoxgy.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2bjqkzweh.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2vhnhoevz.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xbvufono.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2ifjnhrbu.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2tspvgehl.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2cmhaxkgg.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2yzdyrcwb.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2vcfrnvge.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2aovgixhg.html


<!-- 参考信息 -->