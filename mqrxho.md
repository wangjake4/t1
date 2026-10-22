代发 wailian999

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2fbpnzqlh.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2ehqglmcf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2cknjkmwk.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2wupzoazw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxdtxvfn.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2quxddpdf.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xitgjtjw.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ewjbyoxb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2muhnkqox.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2einprqiu.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2chvnynef.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2bgnvwsnx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2jqhzgetf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2einotmno.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2pgzibaaq.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2owkblizm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2divrdyjm.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2wkwxftyc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xaglanmj.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2okozndja.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2irtjhgpw.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2qrkckpyw.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2ttduewpl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2yqlrwedj.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2osknodhs.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fwyeukxh.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ufekgmcj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2etcffegp.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2zmnxnini.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2duxalieu.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wasqugsw.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2cvaeitdx.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2wldvyrqk.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2kdaerhdp.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2uwyfzwxv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2oukwynvv.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2utaezzbl.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2vufewvfq.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2tnctyizt.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2emhdphno.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rizkncfh.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2lpuchisq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2fafhikoc.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2yicxmgqt.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2xfrkupni.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2rzlspcol.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2oyqpectr.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jckcgvun.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2exwipirm.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2spvqthpk.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2qxezqjpq.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2offjvooj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2kvcujwei.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2qvfzbhpx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2vakibbal.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2wvsyjzar.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2qujpubsf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2dzukiulp.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2qekbqcfp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2tktcrcup.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2xgfdlaeq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2vpwlkjjh.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2cyuxtkux.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2mtlzqlih.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2vasggffz.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixeivlay.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lwhvpkod.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2tzquugmw.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2arpdsenn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2weffcqbq.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2nbzxynkm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yiaakmhf.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2viqhzqvi.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zzenxryk.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2oaydrknm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmadbziy.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2vlzgzrhx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2aakmmlzx.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xgwbctbm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2xosrwnuy.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2lhpwriaq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2zbxrlzyn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qkreqink.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2hglkzxnj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2jlbbpqly.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2dwozscfl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2nibutnjl.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kfmazohk.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2tawwnjpe.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2stjeswyr.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2isvszgyg.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2uajxvwuu.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2pwqndido.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2pfhvudok.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2ctizauoh.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2vmtbqrzh.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2hhqazhqt.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2kdbkblkf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2wmqhwulz.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2rbyfhsxv.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rjjljojt.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2awztalmf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2bwynynon.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2auenbwty.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2zqvmqfgs.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2thpdsdmg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2tknqkrpy.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2tylaidkg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gbaezwle.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2gdqqenfx.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2etecnvzy.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2pbujgkhr.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2txyqeyey.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2vexscrol.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ogjiulrp.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpgnupxe.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2onameerq.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zjdgvetd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2norxfvbv.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2geusucxn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2bzcnuyss.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2ozlcpnsm.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qegoxkwi.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2bbvvkcfg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ljkhafag.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2bhsyrsxq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2vgnemitx.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2nmiechgc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dgyfywms.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2aiiztbmc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjuylif.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mgssjsps.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2sasynwmp.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2vpfcablf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zbzrspjv.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2iegvbyxy.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tgpldnyq.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2dcgqizcq.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2leyffbot.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2tyfwuqqi.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2quneeatd.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2cejaloxv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qhgjebna.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfwpeus.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2yipbyfpa.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2jysgsciw.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2mdjtjbsw.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2hueamiet.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2scbzryvr.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2nmjrlqpa.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2jadnzevl.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2pkqkintf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2nqbidglc.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2wpskbrse.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2znbauibl.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2zzvpazeg.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2lontpxeu.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2ryfhyhac.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2pigsnbqg.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2qpplqcmx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2kncngrdv.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2jvnvfrpk.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2beksmksu.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2gaxrolql.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2pxhciiji.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2rvchmwsq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2vssnpwww.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2qxmrozcu.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2fiszoulf.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2ggvsjrse.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2eoqqxabk.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2skbohcfr.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2foqcyipy.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2cvukbkkm.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2iqpouinv.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2thetitzw.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2kwlllvfr.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2aeogujkm.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xrooenpl.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2czuxmjoz.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2rfyqmczc.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ysxmjplr.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2lcbanjel.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2clpcuaql.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2tfzvsbjj.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2snwomfmf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2efvgtodo.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2krcagylk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2odzowulu.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2wigosima.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2blntgbxu.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2oitnzmcr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ntwltqus.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2bermcgqj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jizelurb.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2eezhtybl.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2emewkcla.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2nqlivkmk.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yqpopxfr.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2yrkzyjzr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2zhbdjclg.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2tlozhabt.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2fwtolxbr.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2jmgukudo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2zathtksb.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xsttavza.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2kctccotv.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2wkfaemro.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2oqhnmorx.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zoxtauhl.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2tqhhrzsw.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2ttvlomzj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2xcowbjan.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2zazyubkn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ayaxthxd.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2gyhegokl.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2bartqoxe.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2phptyllo.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2hzpwyzgs.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2qdjnucjz.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2qcjguxdz.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2bifhpxnd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2zgjizmvb.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2ybgpbiwo.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2bcrkqzgk.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2jacprqsk.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2tlnomgae.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2dsddujmo.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2yvznmein.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2xdazyofv.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2mjzbdota.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2zfaweedk.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2usmjhzwk.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2osdeyoeh.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2srcpopzs.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ypivfbtv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2kbeempcf.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2dtybmsfc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fikzjjjw.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2dwfsqnli.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2ubjfyefe.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2nsmcufly.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2yfckwxaw.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cnbwtpbk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2eimjfapi.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wpcitzie.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2lmhxyjzj.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2ljonlyrx.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2iacjtggv.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2mzmgrbgj.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2qkdjofje.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2adywwjax.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2basfpwnl.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2wnvhlpxe.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2koacfsny.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ukfvfjtw.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2nfmzhtjd.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2yzxvtayj.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2giogtvoj.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2fdslfcjs.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2xtmxggis.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2otntdeeu.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2vkephysc.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2nmhkyqff.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2nhppqupt.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2xlcoebrx.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2wjuungqv.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2xwjcieie.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2gpzcggiu.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xkgnlzyj.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2btdfgkyy.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tkrueugq.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2xbruipre.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ljqlkxhr.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2esgbfqaf.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2naaeqeyt.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2rdkxnydk.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2igznngsi.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2opzowwiu.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jtvacqqf.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2opygcplu.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2ddqlkijx.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2ymqoywmy.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ybjifveu.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2gjkyyvsl.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2vmrjjyuz.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2vrruzwkv.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2zosvuweq.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2mtgpfifr.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2wmzlldmo.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2dahdpxlh.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2azevduaa.html

x |= (1 << 3);
来源：http://dali.zhijiandao.cn/Article/details/gt2kyutdrin.html

[S17] C：安全拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gt2zfsaweyd.html

snprintf(buf, sizeof buf, "%s%s", a, b);
来源：http://dali.zhijiandao.cn/Article/details/gt2urabothd.html

[S18] C：命令行参数
来源：http://dali.zhijiandao.cn/Article/details/gt2uoayauwb.html

int main(int argc, char **argv)
来源：http://dali.zhijiandao.cn/Article/details/gt2mezpmjvd.html

[S19] C：快速排序
来源：http://dali.zhijiandao.cn/Article/details/gt2qqvbhvdm.html

qsort(a, n, sizeof(int), cmp);
来源：http://dali.zhijiandao.cn/Article/details/gt2rmuqxgik.html

[S20] C：二分查找
来源：http://dali.zhijiandao.cn/Article/details/gt2shswbzoa.html


<!-- 参考信息 -->