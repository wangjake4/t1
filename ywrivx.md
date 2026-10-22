代发 wailian999

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2zcofvtiw.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2vqsnhcqg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jcuaxmwu.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2senpqbke.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2tjzsgdjb.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2wtkdeybp.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2ngzohtib.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2wcfbamoj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2zsznilgs.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjvuwbm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2rbfvqoqr.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2ygihqhic.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kabiqbyw.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2cqoupeia.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oinwwrik.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2hsswkefe.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2awffxete.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2jursqcpc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2uarndhxz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2kfaejsjq.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2lhwafoxr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2zraffqxf.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2vixuumft.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2cbmkvaar.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wgrffasu.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2zlraoprh.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2byotqhlr.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2fukyibgz.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dfswqmod.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnbihrpt.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2kswfvnvj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2kstccpwl.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2fnkfkeoh.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2xysnctee.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2etwfdyss.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2djoxdmcc.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfvolbwy.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2maejwgql.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2vjoaeuzg.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2ojkfsbue.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbjgooil.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2yjyouowh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2wnfzzros.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zrabjbmi.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2uhbbdzlu.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2sgnhqjhu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2pwgnbojs.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpvcakn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2rvjazplk.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ugoyokhl.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2azlxaide.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2cumpnbri.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2rfjylncs.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2msowwrxd.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2dgyxaaxr.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2lfdhcsds.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2cozbvmzv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2bcltdgwi.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2cdokadwg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2hdonfjdk.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2nizvskgp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2rekdxszk.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2phkwdkpz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zdughmtw.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xcqkndij.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zhagnfeq.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wxzbradj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xvlsusdf.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2bfqaoyet.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hdvuuroa.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2mdzfqhcy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2tjdngjnd.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2wbhghtpd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2lahbqakj.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2pgwsybxj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2umzpvcsg.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2sauyolmq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2hnpacjhu.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2cnicjzaa.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rhpnzkmj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2uytdumsp.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2ulhykelt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2mxblelgq.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2axvwfujn.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2lewnqjjl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qhumftrl.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ixvzreih.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2jcswqcyh.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2uthiqnoz.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2pfxdmbix.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2oddcrdik.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2atxwufkx.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2imypnmli.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2ncykjvke.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2vgguejxb.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2sixznkxm.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jcbuonpk.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2jlevskvf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2htlfpbqq.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ecdsazkk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nhsjsjae.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2ywdtcqgu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2xqkinepb.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wfqxktmq.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2rkhnphis.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2qmxnmslo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tqpufdua.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2luskufsp.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2oxksnnlv.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzrorwsf.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2fxfmbzie.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2bgcpzahv.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2gkfifkpy.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yyryxggl.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dwfdpkun.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2eotpdube.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ocxyenni.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2vgkjloji.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mkncaqoq.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xhtgrlcy.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tbzcoktn.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2anoymwsb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2abjwbvhc.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2piypthyq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qqgfuofi.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2srzpbiuk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hsvhnouq.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2qpvwvfhm.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2cuichnfr.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2rnsmhbgz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xwljnhvf.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2jwoqktef.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yltmjhtv.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2gscbtldh.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tkdohxtg.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2gaknxoza.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2pdubzgpt.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cnjayteu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2pdwjmagb.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2gwiniuux.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2apysothy.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2voysukhb.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2xvbynwff.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2zwjslfox.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2ajcbrwaq.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2jmkhlqsu.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2aczjlztt.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pejxpheq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2styexzhx.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mmqiwbuk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2zqdqpyrv.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rclqijnt.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2loalkvnr.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2cmqwrzeg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2olmmxjop.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgialym.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2enehtqoz.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2nspzuoyf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2aatsmbsi.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2euvrbrpu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2tvhaogqz.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rkwiisyr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2rniebzpm.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2ziynyvbf.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2uoowceri.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2nkjpvuik.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2emuujsvs.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2cuvexiju.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2daeolmyr.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2sbfmxwqe.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2omirpyfj.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2rvvqzxpg.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2weymojfm.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2qvkufkgn.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2lxcdaywy.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlbgdzb.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2hqcvmyrp.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2aypfnfiz.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2ipztkglb.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2crrgqxvl.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2vwispuzx.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2zhdgcojc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2dqmsfwni.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2oyquljgv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2wezpfukm.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2qsjxqyfo.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hxxcunca.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2igneyoks.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjclhbx.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ndpnyulf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mcsrzklt.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2zjmrlivw.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ziqfcpjr.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2uvzyaxtp.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ctfoxpla.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2lnijfapd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2abaclmzb.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jpbakanf.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fbihnbfu.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2tlrjhenb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2hupbcmut.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ikenbpkq.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2nzcakzca.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2knzxirsr.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2gijcvokw.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ouxvgbas.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2onfbunvm.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2wfagbwmx.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2iegvciwb.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2htcvegkl.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2dobalrtn.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2nejmtxbx.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2rlboevif.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2cydjpfpk.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2vjfghnay.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2gilgnrki.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2orujgcvx.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2qtzcimtw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2swqhanug.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2cczkquud.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2caeommoj.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2zwcyilgf.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2yplmnlih.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2takqwxlf.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2zdwndxnp.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2hhkxqcas.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2qsqkiesn.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2qyvrotso.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2obgsrywl.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2zglpkesl.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2npoheugu.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bapiotzg.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ufgfxfbd.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2xrktwdpu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vmgrbzha.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ymvaafcw.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2plzlfotf.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2qvjuwvrm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2kxcymokn.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2apyjjsxd.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2aiulcuky.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2qkzncdbc.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2mymvtfhp.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2cjiaakfu.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjwatit.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2kgvtpixv.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jjostofm.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2rxpplxxd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qlqsyyuj.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2aokirkxd.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2azfqfkph.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2itekcykw.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2rchspcqk.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2tzdmltso.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2yhcesyel.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2dzltkcbj.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ppgqtkte.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2odhhfgwj.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2oidqwpsi.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2zjvvjwhv.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2lqiwvodd.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2orgcmzzs.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2exdzjrmx.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fbkquagg.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2acyqhllp.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2uqiyowbj.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2wqqpayfq.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2egilxoxe.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2rrjtrmxa.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2nhsovouc.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2gbmbennx.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2kdrqmzlr.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2bmsmiogh.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2cjqzfcfy.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2htrpibly.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2akyyymgh.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2hnaqoumb.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2fdkebayo.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ibjxfxby.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xnvhackd.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zaunnrrn.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2mlsdkdod.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2blmrrxcl.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2tjywriso.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2drmpgoue.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2sklgnzib.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2hoonvivz.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2kkhgrmyp.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ybpphyqj.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2xdjgeaai.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2qnuygmfu.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2albnoyod.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2qrhajcio.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbqnacl.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2xtlkucaw.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2noejaqht.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2ufbhnzfe.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2yiogycmw.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhjswnlt.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2cvcqwkxj.html


<!-- 参考信息 -->