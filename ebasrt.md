代发 wailian999

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhijiandao.cn/Article/details/gt2wvcwzbod.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhijiandao.cn/Article/details/gt2wtvpbmyy.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmcrszrz.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2akhbmxho.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2wocsdmcg.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2wrrgmjwz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2pmroxlmp.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2yzsadujw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2hanrfzoe.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2jexrpowv.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2qohuhbqg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2zpofunqh.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2ewprbeui.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2eiewqkuf.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2pmlqywvd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2fpqihaye.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2kabipgxi.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2vwdvuppx.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2alkgrzjp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2vthomsqj.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2szpsgkof.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2mhmtdvec.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2qpenffav.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2ksavjvof.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2pfixqjcj.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rdlxgdnr.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2kqtzbxet.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2iwohbpxz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ccglleqo.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2uzsnlssy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhfygusn.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2goyfpqtg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2djtauvly.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2qebxdqwx.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqxltfas.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2wrmtrhbe.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ptybdcid.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2pwesvsaj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2tnjzblbf.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2dogynrjs.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sduxywni.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2srdocwdi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2aomzjqtv.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2fgfbwsol.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2gtlaihyy.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2feafubcn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2cwvuhhod.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2mvixqyxy.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2mbeqoqyz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2uqzotxfv.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ebmaubod.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ibijpdwp.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2jhakthun.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2izfivdtx.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2xgcpszej.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2fqyewycr.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2knivttmd.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2sacnjnpi.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2cbiagyak.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2hehwvwrb.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2oymgobtj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2qvnosozl.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2sbyphanu.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2znqqqeqj.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2qgwavymi.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2dpldcofz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2ucyytfwl.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2czoehspn.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vjoehbpk.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2djhukomf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2subgavkz.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2zslkkusr.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2nqjmgcmm.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2msdpfuza.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2zrbjqmds.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2jdtapfmh.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2pgfxfwyq.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2ydjldroe.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2hcbgwvbz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2vkeilwqd.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2xphkkqbw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2boeitxvx.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2osjpgoku.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2wtwjpbou.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2dtsryahn.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2xsphephp.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2ekrszbbt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2qltvyhlf.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2vzdvtrac.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2efafvjkc.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2honqoksl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ckxkjgne.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yuywgcgs.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2yxyiwhgg.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2dtjhmutz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2urhnssft.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2ldfcpyip.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hoqbvphr.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2xlfyqybn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2jzlmcpil.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2efcwzkbl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2gkiuwigt.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2xqefikow.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2zipnrnsm.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2gxeqfdwd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2ideiebmc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wqvqilpm.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2iczpjpwm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2rhjabgvc.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2hwgmnkym.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2vupvedaf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2phmvzurs.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2pjufkhia.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nugekfnu.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2lgrngyme.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ygvsglfw.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2seeatguf.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2qadgcleo.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2epzksbtm.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2fdyxkxea.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2awxoyyig.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2gwslaucs.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2ttnhhmdm.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2rdnxxexi.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2jrsjzmnu.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2unkyfaag.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2guuycexv.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2vkazcsob.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2ysoyhcki.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yjnhmuku.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2lmntbozp.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mcjmbehu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2frxbywfa.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2wfpjfyxp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mgeylidv.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2pyujltfs.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2dokukeot.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2klsuzcog.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2amzaldqo.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2cguwrgai.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ljcsazbq.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wcyvseuu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2wbsybdvh.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ourisnlc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2mmylmpbx.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2djsaqdqg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2antnsxlg.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2trpqwqvr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2pcdrygbu.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2ijyodcje.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2stcfafqk.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2lygrdhls.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wxsmxvgn.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2doqiemxb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cumpurrq.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rzxfaoik.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2hrkjioqd.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2nxxvhekw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wnubjauw.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mmizephe.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tphtzaor.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2vlxcazuc.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2bwxbukub.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2qqyulusl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2whinfmkf.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2vookdobd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2zfbzuksw.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2okeychlk.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qgtccevc.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2lltxcfsn.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2kjuapczk.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2dcvghtcl.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2rmakxuab.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2exbnxffy.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2gdcbruzc.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2nxipswqq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2snuyzkso.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2mkkcnjgj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2jfxzluxn.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2rhdwjqce.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2tllxjdcd.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2kfdnyizi.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wyiezodg.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2uxuntkte.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2hctvexeq.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2poyeutsz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2hylszhty.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2gqvkuetf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2ccjjzree.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2ejydbuqi.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2aytcesvp.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2kjlthpvy.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2flhvcoav.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2gptehqik.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2hhxrhhvw.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zditvbcc.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2qtsvrswx.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2jebvhkyp.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2krlygcsv.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2xtgbtqly.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2dxevtwsa.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2xdgexfil.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2otbipctn.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jpvtivii.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2namiahcb.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2cssbhboz.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2gttwqurs.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2sdmfagrs.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2fgaebbkw.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2pkxnkkcz.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2riwylmfv.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2zfjzrxik.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kagamujm.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2bsyrticg.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xlbmdsiy.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2jsjhxebj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2vypvygbh.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2czsvxmws.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2nruikgrn.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2ejaiyxmp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2hxkrorqp.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2zvlkrawn.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2khhddtdq.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2qiedqmoh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gggimmaj.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ytvceyyy.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2tqlwvdep.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2lsqrhtdz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2gpvqkgrg.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2ynocqknl.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2byozhdge.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2tuletvkr.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2uzaitfol.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nllgtmpu.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2axziaiso.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2fiyinngc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2fcljfipl.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2kwquubjc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2rbvpptuu.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vyjtgvbz.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2ozubhxdp.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2ntapebqq.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2uvbkvmib.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2jtwlgsff.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2urqoxuqc.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2rfagzdjh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2mawyohex.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2vrxyrnfa.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2kdlygkzh.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2flgwuxce.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2ihyyhjwe.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2utxydnvv.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2ygnjocsb.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2bavpoyav.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2najiajid.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2oxfrucbe.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2lngmpfmk.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2ykafuypw.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2whkeizkb.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2hvyyepat.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2ilulekza.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2kktpveuk.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2eibfnaua.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zvykeqnb.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2brthtkxw.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2enfewrfe.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2lwvqdnrq.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2hospcaoh.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2rywjcyxr.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nrihzxmu.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2crzrepiz.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2gyjrwnuv.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2pejkrsoo.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2qprwljel.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2perwzrrz.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2ugkbvhbb.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2azmkydxo.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2tmdqlzdm.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2oontisih.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2ocfychnz.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2ygzylstf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2aekwobqf.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2icinvbgv.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2gsvbafny.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dyqkhpmu.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2ukzdrpgy.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2riudclqb.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2rlpkqdrt.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ichdcnkm.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2avoslepc.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2vqwqncsx.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2gnvxyhio.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2nxdiwkly.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2omyqqpjs.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2htmurjkd.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2ulvkerwc.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2dykkuiek.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2xzijeprw.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2mejecwoo.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2tiiowzia.html


<!-- 参考信息 -->