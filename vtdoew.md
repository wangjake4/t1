代发 wailian999

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhijiandao.cn/Article/details/gt2rrugnrcg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gt2dlifmsry.html

[Q47] 与平均值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2qeswrisi.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhijiandao.cn/Article/details/gt2apuioibr.html

[Q48] CTE 公用表表达式
来源：http://dali.zhijiandao.cn/Article/details/gt2sjvydrys.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gt2dyslttpy.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2nttuvxrb.html

[Q49] 更新单行
来源：http://dali.zhijiandao.cn/Article/details/gt2chegacsu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2jxgvtxko.html

[Q50] 批量更新
来源：http://dali.zhijiandao.cn/Article/details/gt2msvldxsf.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2nqkfzres.html

[Q51] 用子查询更新
来源：http://dali.zhijiandao.cn/Article/details/gt2rxtxjnft.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhijiandao.cn/Article/details/gt2rfbccatl.html

[Q52] 删除指定行
来源：http://dali.zhijiandao.cn/Article/details/gt2hhdgoxxj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gt2aijgyhom.html

[Q53] 按条件删除
来源：http://dali.zhijiandao.cn/Article/details/gt2jjtrcuzg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gt2sbggdcll.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gt2wvegjxhe.html

TRUNCATE TABLE logs;
来源：http://dali.zhijiandao.cn/Article/details/gt2dtrigaxn.html

[Q55] 排名（并列占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2hfapwihx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2licqulcr.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhijiandao.cn/Article/details/gt2wvcbjyci.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhijiandao.cn/Article/details/gt2ukpnmvor.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gt2mupsztce.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2ejclynrp.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gt2pystzcmb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2ohvclizh.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gt2xhwdzpgs.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2oawudmrv.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gt2zuooxzlh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhijiandao.cn/Article/details/gt2oyizllej.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2fyocadap.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gt2vfbqvmnz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2wftosavv.html

[Q62] 分组占比
来源：http://dali.zhijiandao.cn/Article/details/gt2xxhctlrt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhijiandao.cn/Article/details/gt2nmqoocsf.html

[Q63] 开启事务
来源：http://dali.zhijiandao.cn/Article/details/gt2dcjqjtqt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhijiandao.cn/Article/details/gt2svhdphsp.html

[Q64] 提交事务
来源：http://dali.zhijiandao.cn/Article/details/gt2sziqzchr.html

COMMIT;
来源：http://dali.zhijiandao.cn/Article/details/gt2nopnontc.html

[Q65] 回滚事务
来源：http://dali.zhijiandao.cn/Article/details/gt2gnoikqyf.html

ROLLBACK;
来源：http://dali.zhijiandao.cn/Article/details/gt2fdjplwvp.html

[Q66] 行锁查询
来源：http://dali.zhijiandao.cn/Article/details/gt2lrsdhjup.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zhijiandao.cn/Article/details/gt2thyjhini.html

[Q67] 设置隔离级别
来源：http://dali.zhijiandao.cn/Article/details/gt2jisuneel.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gt2qagsbeex.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gt2spslljvy.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2xgueaqyl.html

ROLLBACK TO sp1;
来源：http://dali.zhijiandao.cn/Article/details/gt2wfpuxgat.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2ztfdkmrw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhijiandao.cn/Article/details/gt2jtnwvhla.html

[Q70] 更新统计信息
来源：http://dali.zhijiandao.cn/Article/details/gt2yqmxganf.html

ANALYZE TABLE users;
来源：http://dali.zhijiandao.cn/Article/details/gt2kzjujbri.html

[Q71] 查看建表语句
来源：http://dali.zhijiandao.cn/Article/details/gt2rvgycjbo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gt2bjrbeaig.html

[Q72] 查看索引
来源：http://dali.zhijiandao.cn/Article/details/gt2wsofsiul.html

SHOW INDEX FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2enzlmpxi.html

[Q73] 查看表状态
来源：http://dali.zhijiandao.cn/Article/details/gt2widyvgrr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2yxzzfrmx.html

[Q74] 强制使用索引
来源：http://dali.zhijiandao.cn/Article/details/gt2dsixcced.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gt2mxkwxjxk.html

[Q75] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2umscxbly.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gt2lqczynpk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gt2memumytw.html

[Q76] 按天统计
来源：http://dali.zhijiandao.cn/Article/details/gt2fmysifri.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gt2kvdchpfu.html

[Q77] 时间加减
来源：http://dali.zhijiandao.cn/Article/details/gt2nazasliz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhijiandao.cn/Article/details/gt2djcoqdrg.html

[Q78] 当前时间
来源：http://dali.zhijiandao.cn/Article/details/gt2kyfprgsp.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhijiandao.cn/Article/details/gt2ysamnhuv.html

[Q79] 字符串拼接
来源：http://dali.zhijiandao.cn/Article/details/gt2tqznlhcz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhijiandao.cn/Article/details/gt2jsouxlql.html

[Q80] 字符串截取
来源：http://dali.zhijiandao.cn/Article/details/gt2zxxvqhli.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2sbpkoqko.html

[Q81] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2mljdgbqy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2coohlkgl.html

[Q82] 字符长度与字节长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rhoxtdwy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2oeqhfuyz.html

[Q83] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ohfqvljx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qfscwdzz.html

[Q84] 去除首尾空格
来源：http://dali.zhijiandao.cn/Article/details/gt2decuibud.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2vvpehspd.html

[Q85] 数值取整
来源：http://dali.zhijiandao.cn/Article/details/gt2uvqcekow.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gt2zykmuijw.html

[Q86] 读取 JSON 字段
来源：http://dali.zhijiandao.cn/Article/details/gt2kcqmaclz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gt2qonopgno.html

[Q87] JSON 字段做条件
来源：http://dali.zhijiandao.cn/Article/details/gt2kaayohri.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhijiandao.cn/Article/details/gt2oprohlff.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhijiandao.cn/Article/details/gt2yvkukoqs.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhijiandao.cn/Article/details/gt2hybmtlvt.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2aiszhiez.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2vwxdacjh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhijiandao.cn/Article/details/gt2yvuxiyki.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gt2pwcigqsl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gt2aixhvxzx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nugdfced.html

R. Bash 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2pvqxiyaw.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2kutyvbit.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2roaguchq.html

#!/usr/bin/env bash
来源：http://dali.zhijiandao.cn/Article/details/gt2rzftttjx.html

set -euo pipefail
来源：http://dali.zhijiandao.cn/Article/details/gt2vgajphfn.html

[R02] 变量赋值与使用
来源：http://dali.zhijiandao.cn/Article/details/gt2awaoifpx.html

name="Tom"; echo "$name"
来源：http://dali.zhijiandao.cn/Article/details/gt2yevlqmex.html

[R03] 只读变量
来源：http://dali.zhijiandao.cn/Article/details/gt2cahkqwxn.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gt2xkktqeen.html

[R04] 位置参数
来源：http://dali.zhijiandao.cn/Article/details/gt2rtjjjybh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhijiandao.cn/Article/details/gt2bjnivgmw.html

[R05] 参数默认值
来源：http://dali.zhijiandao.cn/Article/details/gt2jwsxjnuy.html

name="${1:-default}"
来源：http://dali.zhijiandao.cn/Article/details/gt2utefzypa.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gt2lxihcngg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2wxabnvan.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2utdtjoxp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2nnimscxw.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2iuhtnsws.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2mwsbmsgp.html

[R09] 字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2wuqipkrs.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2apngzzyn.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gt2nsycheqh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zhijiandao.cn/Article/details/gt2jtauoxhl.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gt2ansuvhnx.html

case "$1" in
来源：http://dali.zhijiandao.cn/Article/details/gt2blsmhyag.html

start) echo "启动" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2wwytmbny.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2tupynzqu.html

*)     echo "未知命令" ;;
来源：http://dali.zhijiandao.cn/Article/details/gt2ewpmmyvv.html

esac
来源：http://dali.zhijiandao.cn/Article/details/gt2ygtiofpo.html

[R12] for 遍历文件
来源：http://dali.zhijiandao.cn/Article/details/gt2zhvamqjb.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xahqvviu.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2ejesydcj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2fpcxjqvj.html

[R14] C 风格 for
来源：http://dali.zhijiandao.cn/Article/details/gt2nnetwmou.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2pmbqinsj.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2gvuwyoew.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2kaakqssz.html

[R16] until 等待条件
来源：http://dali.zhijiandao.cn/Article/details/gt2tswwqrnz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2sungbonq.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gt2wpfotbdl.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2oqaynvdn.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gt2rfptqsiw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2srrdghvv.html

[R19] 数组长度
来源：http://dali.zhijiandao.cn/Article/details/gt2czdxanrj.html

echo "${#arr[@]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2lmazzjjc.html

[R20] 关联数组（字典）
来源：http://dali.zhijiandao.cn/Article/details/gt2yzsjfuty.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gt2tumvvvpr.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2rochdgdp.html

echo "${#s}"
来源：http://dali.zhijiandao.cn/Article/details/gt2ycogskal.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gt2yohutsyg.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gt2knpzssut.html

[R23] 字符串替换
来源：http://dali.zhijiandao.cn/Article/details/gt2sjuausxr.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gt2yoenynjx.html

[R24] 大小写转换
来源：http://dali.zhijiandao.cn/Article/details/gt2ozskveqa.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2dpkvvyds.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2thgrlmbf.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhijiandao.cn/Article/details/gt2nzzcizqm.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gt2idkyfpid.html

now=$(date +%F); echo "$now"
来源：http://dali.zhijiandao.cn/Article/details/gt2xstiamzi.html

[R27] 算术展开
来源：http://dali.zhijiandao.cn/Article/details/gt2lelltgcs.html

echo $((1 + 2 * 3))
来源：http://dali.zhijiandao.cn/Article/details/gt2qzwaorzf.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gt2hhwbnenh.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhijiandao.cn/Article/details/gt2xjcdibgz.html

[R29] 定义函数
来源：http://dali.zhijiandao.cn/Article/details/gt2abwbvfuz.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gt2kyneredu.html

[R30] 函数返回状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2dotsdtzx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2qwykyekc.html

[R31] 局部变量
来源：http://dali.zhijiandao.cn/Article/details/gt2xuoynrza.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gt2cwqnmrgv.html

[R32] 参数个数校验
来源：http://dali.zhijiandao.cn/Article/details/gt2jrzewhvj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gt2dwctkdox.html

[R33] 捕获错误并提示行号
来源：http://dali.zhijiandao.cn/Article/details/gt2rbkhhegt.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhijiandao.cn/Article/details/gt2wjlucqym.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gt2iambxwsm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rrfocrix.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gt2icsbnyjl.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhijiandao.cn/Article/details/gt2chrkdfsd.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gt2qyzbmptr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhijiandao.cn/Article/details/gt2tjcetjub.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2eojbrgyr.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gt2ahyuyach.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gt2wrwlwejm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gt2enricabl.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gt2yqojrein.html

cmd > out.log 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2opputjdn.html

[R40] 追加写日志
来源：http://dali.zhijiandao.cn/Article/details/gt2zegzjxen.html

echo "log" >> out.log
来源：http://dali.zhijiandao.cn/Article/details/gt2gnalbhaj.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gt2srkgmhau.html

cmd >/dev/null 2>&1
来源：http://dali.zhijiandao.cn/Article/details/gt2efdalvzh.html

[R42] 输入重定向
来源：http://dali.zhijiandao.cn/Article/details/gt2gjrmuhqd.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2ltxfxqqr.html

[R43] 按名字查找文件
来源：http://dali.zhijiandao.cn/Article/details/gt2xofrgimg.html

find . -name "*.log" -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2mdijnpak.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2ftjejktw.html

find . -mtime -7 -type f
来源：http://dali.zhijiandao.cn/Article/details/gt2xutqwpil.html

[R45] 批量删除
来源：http://dali.zhijiandao.cn/Article/details/gt2lzdnhblb.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gt2spwqdlwi.html

[R46] 递归替换文件内容
来源：http://dali.zhijiandao.cn/Article/details/gt2srgaadyc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gt2eypclgbx.html

[R47] sed 单行替换
来源：http://dali.zhijiandao.cn/Article/details/gt2hkfbunxx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2xbhypfbt.html

[R48] awk 取指定列
来源：http://dali.zhijiandao.cn/Article/details/gt2ujebyhep.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2yxvpxggb.html

[R49] awk 带条件
来源：http://dali.zhijiandao.cn/Article/details/gt2rndbldcy.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2josqhhnm.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gt2tryulxsy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2dknrsejd.html

[R51] 排序去重取前几
来源：http://dali.zhijiandao.cn/Article/details/gt2btdfotgi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhijiandao.cn/Article/details/gt2nulddvrx.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gt2enlekrww.html

wc -l a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2sjlaaghb.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gt2lxeitsgv.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zhijiandao.cn/Article/details/gt2xpbmmkpj.html

[R54] 比较两个文件
来源：http://dali.zhijiandao.cn/Article/details/gt2wrumncuh.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2csdprlgp.html

[R55] 压缩与解压
来源：http://dali.zhijiandao.cn/Article/details/gt2gsedymgs.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhijiandao.cn/Article/details/gt2vuldmtlh.html

[R56] 远程拷贝
来源：http://dali.zhijiandao.cn/Article/details/gt2xuxawokt.html

scp file user@host:/path/
来源：http://dali.zhijiandao.cn/Article/details/gt2tdzhbxln.html

[R57] 远程执行命令
来源：http://dali.zhijiandao.cn/Article/details/gt2mjyjxaog.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gt2hckteapu.html

[R58] 下载文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mxcefuge.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhijiandao.cn/Article/details/gt2jbioefgo.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gt2psaaewpd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gt2iajqibto.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhijiandao.cn/Article/details/gt2iaksjsde.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gt2gkwkxyzm.html

[R61] 磁盘占用
来源：http://dali.zhijiandao.cn/Article/details/gt2yhhbfsyi.html

df -h;  du -sh *
来源：http://dali.zhijiandao.cn/Article/details/gt2necxhjew.html

[R62] 找最占空间的文件
来源：http://dali.zhijiandao.cn/Article/details/gt2picyhtyu.html

du -ah . | sort -rh | head -10
来源：http://dali.zhijiandao.cn/Article/details/gt2hjkzeplq.html

[R63] 内存与进程
来源：http://dali.zhijiandao.cn/Article/details/gt2eomvinje.html

free -h;  ps aux | grep nginx
来源：http://dali.zhijiandao.cn/Article/details/gt2vnxaaacz.html

[R64] 结束进程
来源：http://dali.zhijiandao.cn/Article/details/gt2hjsjrieu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhijiandao.cn/Article/details/gt2mgxstzip.html

[R65] 查看端口占用
来源：http://dali.zhijiandao.cn/Article/details/gt2nyoujbto.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zhijiandao.cn/Article/details/gt2lkqmjsdm.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gt2vldaquyd.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gt2pakqqrvu.html

[R67] 生成随机十六进制串
来源：http://dali.zhijiandao.cn/Article/details/gt2ftekuxrx.html

openssl rand -hex 16
来源：http://dali.zhijiandao.cn/Article/details/gt2crmlsvjb.html

[R68] 计算文件校验值
来源：http://dali.zhijiandao.cn/Article/details/gt2vqtrlmuj.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.zhijiandao.cn/Article/details/gt2drfwpzik.html

[R69] 生成随机密码
来源：http://dali.zhijiandao.cn/Article/details/gt2kqwgoozr.html

head -c 16 /dev/urandom | base64
来源：http://dali.zhijiandao.cn/Article/details/gt2hdkqzrqh.html

[R70] 时间戳与互转
来源：http://dali.zhijiandao.cn/Article/details/gt2wnbmfger.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gt2bjzyxpuw.html

[R71] 日期格式化
来源：http://dali.zhijiandao.cn/Article/details/gt2eakbsbmr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.zhijiandao.cn/Article/details/gt2hhoieqsi.html

[R72] 等待端口就绪
来源：http://dali.zhijiandao.cn/Article/details/gt2eywvvwsx.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2nnxsgaoy.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gt2oitccdzj.html

split -l 1000 big.log part_
来源：http://dali.zhijiandao.cn/Article/details/gt2pcgzheay.html

[R74] 批量重命名
来源：http://dali.zhijiandao.cn/Article/details/gt2miuguudg.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhijiandao.cn/Article/details/gt2rrqlgcan.html

[R75] 导出环境变量
来源：http://dali.zhijiandao.cn/Article/details/gt2wohfingz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhijiandao.cn/Article/details/gt2neizfsfh.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gt2mhsspedo.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gt2rdndzjae.html

[R77] 读取用户输入
来源：http://dali.zhijiandao.cn/Article/details/gt2lkqfxdbo.html

read -rp "请输入: " ans
来源：http://dali.zhijiandao.cn/Article/details/gt2bhvgsudq.html

[R78] 交互式菜单
来源：http://dali.zhijiandao.cn/Article/details/gt2ojhbhkib.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhijiandao.cn/Article/details/gt2dvukieoq.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gt2hsakvers.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.zhijiandao.cn/Article/details/gt2xtbarlau.html

[R80] 查看脚本执行耗时
来源：http://dali.zhijiandao.cn/Article/details/gt2hkeawoyc.html

time ./run.sh
来源：http://dali.zhijiandao.cn/Article/details/gt2pjuptgam.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2qeyndrsb.html

S. C / C++ 专题
来源：http://dali.zhijiandao.cn/Article/details/gt2jkdmylum.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gt2nsgrzyyd.html

[S01] C：Hello World
来源：http://dali.zhijiandao.cn/Article/details/gt2qfjjlfek.html

#include <stdio.h>
来源：http://dali.zhijiandao.cn/Article/details/gt2yajzvwna.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.zhijiandao.cn/Article/details/gt2ykglapur.html

[S02] C：变量与格式化输出
来源：http://dali.zhijiandao.cn/Article/details/gt2igfinfcl.html

int a = 10; printf("%d\n", a);
来源：http://dali.zhijiandao.cn/Article/details/gt2vowuxfrd.html

[S03] C：读入整数
来源：http://dali.zhijiandao.cn/Article/details/gt2kxttglak.html

int x; scanf("%d", &x);
来源：http://dali.zhijiandao.cn/Article/details/gt2ugjsduxl.html

[S04] C：字符串复制
来源：http://dali.zhijiandao.cn/Article/details/gt2pyqdxysr.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.zhijiandao.cn/Article/details/gt2qslfhbyk.html

[S05] C：字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2mkceegse.html

strlen(s)
来源：http://dali.zhijiandao.cn/Article/details/gt2sdkoghvl.html

[S06] C：字符串比较
来源：http://dali.zhijiandao.cn/Article/details/gt2mwtxpmwg.html

strcmp(a, b) == 0
来源：http://dali.zhijiandao.cn/Article/details/gt2hshpisqv.html

[S07] C：数组遍历求和
来源：http://dali.zhijiandao.cn/Article/details/gt2exqzrbdo.html

for (int i = 0; i < n; i++) sum += a[i];
来源：http://dali.zhijiandao.cn/Article/details/gt2wtqpjcpj.html

[S08] C：动态内存分配与释放
来源：http://dali.zhijiandao.cn/Article/details/gt2bpxxskue.html

int *p = malloc(sizeof(int) * n); ... free(p);
来源：http://dali.zhijiandao.cn/Article/details/gt2yqhzhmcq.html

[S09] C：结构体定义与初始化
来源：http://dali.zhijiandao.cn/Article/details/gt2wwgggcln.html

struct Point { int x, y; };  struct Point p = {1, 2};
来源：http://dali.zhijiandao.cn/Article/details/gt2ysgojura.html

[S10] C：指针与解引用
来源：http://dali.zhijiandao.cn/Article/details/gt2oiclajwx.html

int *p = &a;  *p = 5;
来源：http://dali.zhijiandao.cn/Article/details/gt2ikdzjlcb.html

[S11] C：逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lrihpxfc.html

FILE *f = fopen("a.txt", "r");
来源：http://dali.zhijiandao.cn/Article/details/gt2dgtnjbrn.html

while (fgets(buf, sizeof buf, f)) { }
来源：http://dali.zhijiandao.cn/Article/details/gt2tnpmstbv.html

fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2zpbptuql.html

[S12] C：写文件
来源：http://dali.zhijiandao.cn/Article/details/gt2nmfogtug.html

FILE *f = fopen("a.txt", "w");  fprintf(f, "hi\n");  fclose(f);
来源：http://dali.zhijiandao.cn/Article/details/gt2klpapfzp.html

[S13] C：宏定义
来源：http://dali.zhijiandao.cn/Article/details/gt2bcgjbfrr.html

#define MAX(a, b) ((a) > (b) ? (a) : (b))
来源：http://dali.zhijiandao.cn/Article/details/gt2dwzlvgyz.html

[S14] C：枚举
来源：http://dali.zhijiandao.cn/Article/details/gt2etjwqyro.html

enum Color { RED, GREEN, BLUE };
来源：http://dali.zhijiandao.cn/Article/details/gt2efithhrf.html

[S15] C：类型转换
来源：http://dali.zhijiandao.cn/Article/details/gt2kzmonqoi.html

(double) a / b
来源：http://dali.zhijiandao.cn/Article/details/gt2rfnbrcgk.html

[S16] C：位操作置位
来源：http://dali.zhijiandao.cn/Article/details/gt2xeifqlhc.html


<!-- 参考信息 -->