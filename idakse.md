代发 wailian999

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2xlzjplse.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2uvmciokp.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2krvnqpqs.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2smcdqrmj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2bacwvnul.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2gjpekpbq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2xssomudb.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2xbretnfm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xukzhknz.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2axknnhgl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gbzpskhy.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2yjzbrlhq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ovzczuhh.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxovrox.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2edwthjvc.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ravcpazk.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2zsebfhjb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hsnalicm.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2csvzakpo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2fmljzohh.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jztggrbl.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2ojefmzrh.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2osftwzbk.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2uxyytqfj.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ryuxjlwl.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2loxpnajo.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lnjidaks.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2cusguecf.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2jyeubmro.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2xuntcwvz.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2qhyvqpnn.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ongnxgud.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmdjowam.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2feshaldw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2qqvnqybf.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2cixsiofv.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2apfkrzqj.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2qepbjdve.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2teearrpj.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2hfpyhsum.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ggeyvpmz.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ztcvcjvs.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2znwlreqb.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dxzrbymp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2rwonajgb.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2zxqveeje.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2eolrilnm.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2nscdafgp.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2yllfiydz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibnehayr.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2cwphaiwu.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2ccltauyl.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2aljdcgnf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2lmhehbxp.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbyqtmg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2caigiwxe.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2mvtjyloy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2jkhugvzo.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2otutjveq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyqemqfx.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2inhmhmtu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pnpiuitq.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2bjpvmnpa.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vnazngzy.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2bejqdfit.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bofgpzfc.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2xpxpkhgy.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2dxognnod.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2jfvrifzj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2xvlqktim.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2vhcpresd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2wdroqrll.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2jissggdb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2illiarui.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kuuxnbrv.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2nhjnqyau.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2ofhvurge.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2qjehqpws.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2soukdeim.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2vzuyaxgu.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2pojsrbpi.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kwinjhos.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2zcucnjyz.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2tfvxaojp.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2ladlupil.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2xcxriddo.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2jegndoqg.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fswyrxps.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2jwcopdiv.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2tbougxpa.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2djijcygq.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2avsqadya.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ajuhwtqo.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2fwpzhqah.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uiursvmz.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2yflcartw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2orajhhen.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2esewjydm.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2qfkbyynk.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2axkamvfk.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ejxtktax.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2picbqyve.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2iktzotfe.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2wtdbmcua.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2zvsneraq.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2gqvelnxl.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqxmwycr.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjeoljn.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2sgifreys.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2pagnqnxj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xldhkkom.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2hjqhyhdf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iczxnxfj.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2kfbgreco.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xtaixtuz.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2erlijmok.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2vfluyrcq.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2wounimcl.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2zzwkfsio.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2itqzavkz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2njctbftg.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2xnkynkuz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ljwfvltp.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2oqjjkbel.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vtlhobld.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2pszsylum.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jfvgrltp.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2okpkwrua.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vvcoxeff.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2lbdtegok.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2vehgwotg.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jojqkhhn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2xebhgwjp.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2xyuyhjwt.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2iystzgac.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzgzxhb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jyvwyjbk.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2flawubvr.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2pbstgiou.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2eznylums.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2xoeoddli.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2avhryamd.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2vjnpbnos.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2lxhgcxzd.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2olhjfrew.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2kbronibp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2okxqzern.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2obrmpaqa.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pjrkhqxv.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jusqiqbg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2uimkhwfx.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2oxqsegpz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2gqyanljb.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2vxrrsxuh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2ipmeavjr.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2euizesjv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2btohwwsg.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2werhdyuc.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2jbvcmjjf.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vjxwtkam.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ybqmotad.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2pzkxwsxl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2vkqauqcn.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2mkwoxmcu.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2mrwezdgo.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jrhvqllj.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2iepeqvcs.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ghobstkh.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2gwuubqnv.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2ttbdjbka.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ctvsgduh.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2elmtwjax.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gvollhzt.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2uguggvry.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2phznnlqj.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2nyahqkld.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2gzudkozk.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2mwguriqr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2lxdxsvmd.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2olelwjdb.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nlsesbpr.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2yqyjjhva.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ziaxzapi.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kxymaqii.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2gkyokpko.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bjiiqspn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kxpuaenl.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2hwxdspay.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2ffolvaja.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2wuybjbuu.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ebshvhdi.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2tocvnulg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2wdyvmdun.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uwvykncx.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fpdgbcpg.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2rnauvhfm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2xstqkklm.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ktbnlscg.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2fgydbtoa.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2dfbnwigz.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2dashugmx.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kxdjomxf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2ipwwqecg.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2yyunwiln.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ufjwbeoe.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2umdgccyz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ikypjyzm.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2oenazgiz.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2uqmlbwah.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wwfgsghv.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2qykdiwgn.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2hdvjjcgq.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2hpzkmeek.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2drlykegl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqoncfg.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2auzuglml.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2dtwaulsa.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2bwzzcpfk.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2bkdrflny.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2plbopsii.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2wrtivlqn.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2ebczagwe.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2uncrdisd.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2gjykvuqn.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2rzvpanap.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2amltotdu.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2kzoveffi.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2wgbucyup.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2kzyrlssf.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2dmukbcwy.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2syymnsgj.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2mzktadgn.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2dyzdghhy.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2hbsiionl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2ftljkklb.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2uicvndag.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2mpxenjtb.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vfzdieov.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2xwdelhqh.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2icdcejsd.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2vtojdpew.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2avaxakak.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2hdchrigo.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2tursxbkv.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vvplanwq.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2lzrccfts.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2hkobwmln.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2faacjuyt.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2wpqgpgqj.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2gygcgubz.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2fzvsagvv.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2bjoddlnm.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2eoxeukjc.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ieltlwtu.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2vsfzfdsn.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2pzmgolti.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2eysdfbii.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2bxklbbzx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2zhhtwibu.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2fllksmcr.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2glutkkxl.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2fatlvsae.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2ecwomsmn.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ywwquoch.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2jdltmcdu.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2lvrwnavx.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2bkejfjlh.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2sycivtbs.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2egzpword.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2ejymykjm.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2hbidkxpj.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2kfxxqixn.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2bzurgydx.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2lnsndmgh.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2runuvzyw.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2eehobqyv.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2vhyncgea.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2xvdtgpka.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2jeopgqey.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2isajreoq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2fdzckjbh.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2zlnqphei.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rxrqclhv.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2npihmadf.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2ltpkjpsf.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2evuzyyoz.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2kffbusha.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2vzoolwes.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2rgjmrpkj.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2lksjnakm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2fuzkajwu.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2girlriqr.html

bsearch(&key, a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2euqzawla.html

[S21] C：字符类别判断
来源：http://dali.zhijiandao.cn/Article/details/gt2auvdrtsg.html

isdigit(c);  isalpha(c);  isspace(c);
来源：http://dali.zhijiandao.cn/Article/details/gt2pevkokkx.html

[S22] C：字符串转数字
来源：http://dali.zhijiandao.cn/Article/details/gt2jjmffxgd.html

atoi("42");  strtod("3.14", NULL);
来源：http://dali.zhijiandao.cn/Article/details/gt2zfatecfu.html

[S23] C：随机数
来源：http://dali.zhijiandao.cn/Article/details/gt2xzfajrlg.html

srand(time(NULL));  int r = rand() % 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2rorzkxco.html

[S24] C：获取本地时间
来源：http://dali.zhijiandao.cn/Article/details/gt2kdtvekyw.html


<!-- 参考信息 -->