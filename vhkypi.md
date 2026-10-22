代发 wailian999

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhijiandao.cn/Article/details/gt2owsxirse.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhijiandao.cn/Article/details/gt2whkjiphc.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhijiandao.cn/Article/details/gt2ljimnkog.html

[Q42] 连接条件附加过滤
来源：http://dali.zhijiandao.cn/Article/details/gt2ymifjjlh.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhijiandao.cn/Article/details/gt2eerybdct.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhijiandao.cn/Article/details/gt2aqowdqtm.html

[Q43] 标量子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2aohjlsxi.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zhijiandao.cn/Article/details/gt2cymebhrs.html

[Q44] IN 子查询
来源：http://dali.zhijiandao.cn/Article/details/gt2mlfxstmd.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhijiandao.cn/Article/details/gt2qyiczwjb.html

[Q45] EXISTS 判断存在
来源：http://dali.zhijiandao.cn/Article/details/gt2mgfyoold.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2imlrxkuw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2houijpjr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2gklcqkfg.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mjhkncvg.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2fiaudrkh.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2oprpgxcp.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2ouedggmd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2vfcnktkb.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2bbxlwzfv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2xkgkbcfo.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2pvuiptut.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2qpepkwse.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2humfdspp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2hucftoje.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2hvqsyhgp.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2hnptaqsf.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2ddzvneye.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2jkofazrx.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2aeedchdu.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2oxbayysk.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2oqkodwvp.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ynnbjukw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2qhbujbew.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2hhlpoaej.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2udkriivf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2iedodmti.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2xqpuhxoa.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lytklhwl.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2ongyijmk.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2koyxkrqu.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2daagusmv.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2hdlygyjh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2rmrkpitu.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2bjxohhgy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wpurvmyf.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2ctuqpgmt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2ixoxhvje.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2hydiuacr.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2owmrxnav.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2ifnhssrd.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2hghtwjiy.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2mbqqfxhj.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2zsotajke.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2vlwisgyh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2hugjubsu.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2jeopvazu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2ifyruiwg.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2eunxmzui.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2ehkuhgoi.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rpgizjbn.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2rmhvzrnn.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2hjvinzhn.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2gcutxprw.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2hchgnpse.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2ddvwtkga.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2sawysnzi.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2bqltfxqo.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2wiburdrn.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2ozruxpyi.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2xlvhzhiv.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2okpwytnn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2noxctnnn.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2bqggnhfe.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2xnkeqjfp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2orwnyldj.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2wiijzxiq.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2juxrtumy.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2qatsfwhg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2gxedvxrt.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2cxkdbwmb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2vgvgcsws.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2aoebtylk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2htrwaycn.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2zxjbmrvu.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2myvidsmn.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2iukyfrmq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2zikmwwzh.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2admiijku.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvpwtfv.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kdvqswxn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2pxkmqvvi.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2cjljrvli.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qnymkjvz.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2tydjijmb.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2akzgdkhm.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2frwqouts.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2ccaanlcw.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2udlrvzdg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2tlriqxvz.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2vzraxspg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2bpeozacw.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kocvxtnc.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2tvjkdpve.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2jccpqsxp.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2tyjurhhq.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2fjruylpa.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hyideocm.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2xgljnftb.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2hxokapfl.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2yxfipunv.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2ghyyrbsc.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2cdqtmdlk.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2nszgxqxt.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2cjdyeojg.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2nswozamv.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2pztmouyc.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2iqocefor.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2tfmrpumm.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2lstxmtrp.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2rdhajjex.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2titoquph.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2irduhlna.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zdioyaio.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2gfomcdte.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qsmzlpzz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2vkurmhrn.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2yqfyeuvg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2kcjdssyy.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2jbjvegbn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2peladnoz.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2smvpnszb.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2pmyhlwer.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2lnzhqhzb.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tfoqznod.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2klqnoxuw.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2lpnmjpit.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2otzjcsps.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rrwzdkrv.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2dvpaeuvp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2neqwmhcu.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2hvfxfena.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2cqwokjvr.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2celyyuiw.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kvmouprd.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2mobplhfy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2iwzwmvzd.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2egzhqbgz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2qluqqtpx.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2shyhfgzx.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2whzpndup.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2htfmvuho.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2wkuatjsm.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2vmnzmkzq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2gdtvufgv.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2yfddqxew.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2xwzhgzif.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2qlnujnil.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2alntjjhi.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2kkadjart.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ronacmnb.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2icptcedb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2squwuset.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2ymnakqhl.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2easirezu.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2ftaaymyd.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2mogbhvzx.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2bwbjwpxw.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2oupqzevb.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2wpuvhwja.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2clmohcga.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2ysjidouj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2vistbbiu.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2eutwfwzt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2eznvikzu.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wymcejed.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2atofgrza.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2yrqqzgck.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2iuexohdd.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2tftrahod.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2hvhdwlhu.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2qtirxgoi.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2gfkvmipt.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2xjrkidei.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2woweffcn.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2xdxwcipg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2dzpbjlju.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2gommgkhz.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2rjnctwmj.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2dbecqkgf.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2aloqavih.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2zgilumdi.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2crdfodcx.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2ktmtjzku.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2jogrconr.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2wzatdwzf.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2jsztoipp.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2yezklvtk.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dacehsys.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2spjcbglo.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2zgojrjem.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2yhcpnihl.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2lznukgdl.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2dkfvdmwl.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2slrekadz.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2ggzeokia.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2petrujgq.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2vlalcuyk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jmrgbnme.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2yneemyms.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2jfddmhis.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2nlqklvsd.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2ynnkwish.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2mbehokos.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2eeifuoex.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2sspgrout.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2lfpzmmbk.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2kyzmfwli.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2zjssfugo.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2ztsorkua.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2hvusbggh.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lcilvecm.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2msdetlxt.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2armhibea.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2fzkuicfe.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2opxywzqf.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2sxbtupcb.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2btfosvrd.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2zazafues.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2htvkkhxe.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2guizpkxl.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2mtpftfcw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2ndpefvch.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2ipnyfupx.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2usbxrxxd.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2rnmeutik.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2egwbhnnn.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2dfbrstzb.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2hgeqprnb.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2npodeiqv.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2lhagwidx.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2voxmjvzp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2dilneard.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2szaqdiye.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2crvoxusq.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2cevsexwt.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2xflojlad.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2bgsvgnjp.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2jsbvspuy.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2npudtpgk.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2hmbthxqy.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2vontjfpx.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2elnjrdzk.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2plpvsyyp.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2tuijtocm.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2xagjcfhm.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2znvwrtax.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2dechauzh.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fucylbnx.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2fyxlnucu.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2tnxulewf.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2gpyvpwdg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2irneznyf.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2btmnadse.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2kkfxkaya.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2uzfqjazq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2iweomenb.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2zejygwqw.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2usyjwftv.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2krbtvfah.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rquhssen.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2cwmugbon.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2djelgcrr.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2scdhmhgg.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2pfvjsgfh.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2lyhksqul.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2mafcoxqf.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2srqfocii.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2adtfvntk.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2iszpnguu.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2jetjogaw.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2kpxuxpyf.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2yalbhrvr.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2ntqzmydf.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2xzdfzsvm.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2geudaezi.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2onpookfp.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2glkhcauq.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2cntaabim.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2lbjrgusy.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2efcnndri.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2khpdmpse.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2jzjwrgvw.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2ulenlhsd.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2klrbtqpp.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2tjkjcupo.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2eqlzxftq.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2yjwcxxfo.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2bmaqvunj.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2sgnkdpvl.html


<!-- 参考信息 -->