代发 wailian999

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.shuidangran.top/Article/details/gt2fxxihtgf.html

[Q22] 排序
来源：http://dali.bjfxy.top/Article/details/gt2reysanup.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shangyingyoupin.top/Article/details/gt2eimgbkyw.html

[Q23] 分页
来源：http://dali.shzxlz.cn/Article/details/gt2phezmswr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.0kj1m.cn/Article/details/gt2natbokck.html

[Q24] 去重
来源：http://dali.yueranfly.top/Article/details/gt2dsjplahy.html

SELECT DISTINCT city FROM users;
来源：http://dali.9152youxi.cn/Article/details/gt2cjhsvplu.html

[Q25] 只取前 N 条
来源：http://dali.iojbl.cn/Article/details/gt2xjffpcio.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hongshengwenyu.top/Article/details/gt2nwyfaecq.html

[Q26] 计数
来源：http://dali.zycfv.cn/Article/details/gt2kgyddymi.html

SELECT COUNT(*) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gt2elouopel.html

[Q27] 条件计数
来源：http://dali.xziqi.cn/Article/details/gt2yxygruzf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gt2gckncjwm.html

[Q28] 求和与平均
来源：http://dali.sysykeji.top/Article/details/gt2obtngikh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mhefohqi.html

[Q29] 最大最小值
来源：http://dali.dashuyun.cn/Article/details/gt2fxnvxvvd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.c1oappe.top/Article/details/gt2pygetjkh.html

[Q30] 分组统计
来源：http://dali.sufxvd.cn/Article/details/gt2zwyxsreg.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.mhx1999.top/Article/details/gt2aiifuncc.html

[Q31] 分组后过滤
来源：http://dali.gogol.net.cn/Article/details/gt2rdznetrp.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.haohaochexian.top/Article/details/gt2tkkvlfcc.html

[Q32] 分组拼接字符串
来源：http://dali.cheryme.top/Article/details/gt2zmfqkvja.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.chenlongwang.top/Article/details/gt2mewbjocf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhijiandao.cn/Article/details/gt2wfzodkhw.html

[Q33] 多列分组
来源：http://dali.gogol.net.cn/Article/details/gt2sdoqkhkj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.pycfn.com/Article/details/gt2dgwohmzr.html

[Q34] 每组取第一条
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2uebgyrcs.html

SELECT * FROM (
来源：http://dali.wangdashe.top/Article/details/gt2yhngwlvp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xuanzx.com/Article/details/gt2ozkfvltv.html

) t WHERE rn = 1;
来源：http://dali.nwbrower.top/Article/details/gt2dktafouw.html

[Q35] 内连接
来源：http://dali.jianghu66.top/Article/details/gt2vagparie.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.smart0.xyz/Article/details/gt2bexclewt.html

[Q36] 左连接
来源：http://dali.redwolf501.top/Article/details/gt2emmqigxk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yueranfly.top/Article/details/gt2agymebgb.html

[Q37] 右连接
来源：http://dali.meibo888.top/Article/details/gt2skshymgd.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhengqikj.top/Article/details/gt2rbnegrrj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhoulong.xyz/Article/details/gt2vmzdycdo.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.pengpengdd.cyou/Article/details/gt2tmajxmrc.html

[Q39] 自连接（查上下级）
来源：http://dali.shangyingyoupin.top/Article/details/gt2ooqqmhqx.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cheryme.top/Article/details/gt2nxbrkzib.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.daria6918.cn/Article/details/gt2josszbwh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sufxvd.cn/Article/details/gt2hegdmxqa.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhengqikj.top/Article/details/gt2druroziv.html

[Q41] 多表连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jxsascoj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.havefunace.top/Article/details/gt2rgdbhyfx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.9152youxi.cn/Article/details/gt2tpzyxefb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hongshengwenyu.top/Article/details/gt2vbfddftc.html

[Q42] 连接条件附加过滤
来源：http://dali.iojbl.cn/Article/details/gt2fegobcjf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sxryk.cn/Article/details/gt2cfenqwuk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.c1oappe.top/Article/details/gt2riwafdwe.html

[Q43] 标量子查询
来源：http://dali.daria6918.cn/Article/details/gt2blyejzop.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.dashuyun.cn/Article/details/gt2ovayzjze.html

[Q44] IN 子查询
来源：http://dali.fengsongda.top/Article/details/gt2ygkdhigv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yueranfly.top/Article/details/gt2szdoyqdv.html

[Q45] EXISTS 判断存在
来源：http://dali.c1oappe.top/Article/details/gt2thoskouz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nwbrower.top/Article/details/gt2kmxlcjll.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jqgfzy.top/Article/details/gt2xgoywpdk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.andypj.xyz/Article/details/gt2pkmoopet.html

[Q47] 与平均值比较
来源：http://dali.dianchejie.cn/Article/details/gt2nwywnpnv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xuanzx.com/Article/details/gt2ejbnevif.html

[Q48] CTE 公用表表达式
来源：http://dali.sweek.top/Article/details/gt2lqikyjdf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ppjwa.cn/Article/details/gt2oavyfxov.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sxryk.cn/Article/details/gt2ojnivryi.html

[Q49] 更新单行
来源：http://dali.xuetiantiany.cn/Article/details/gt2rfqlurkf.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.aizwys.cn/Article/details/gt2fheotuas.html

[Q50] 批量更新
来源：http://dali.zhixingplan.top/Article/details/gt2wamqomox.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yvedp.cn/Article/details/gt2vesusosr.html

[Q51] 用子查询更新
来源：http://dali.havefunace.top/Article/details/gt2eufmyxjh.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gt2bduxqyis.html

[Q52] 删除指定行
来源：http://dali.feifeiyinyue.top/Article/details/gt2tmhtwmzj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.gaohongyu789.top/Article/details/gt2fmtykbhv.html

[Q53] 按条件删除
来源：http://dali.jlsjyb.cn/Article/details/gt2wjsdpckc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.sweek.top/Article/details/gt2tuymmlqn.html

[Q54] 清空表
来源：http://dali.aibaodan.cn/Article/details/gt2sfrdvuqk.html

TRUNCATE TABLE logs;
来源：http://dali.ybcxt.top/Article/details/gt2kvjgulbj.html

[Q55] 排名（并列占位）
来源：http://dali.sysykeji.top/Article/details/gt2teggzxcx.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.tian-w.cn/Article/details/gt2akjqkooi.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cqqwz.cn/Article/details/gt2yfgljryg.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xziqi.cn/Article/details/gt2qnqmjpcp.html

[Q57] 行号
来源：http://dali.0kj1m.cn/Article/details/gt2uuthgeni.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2rgvqpqfa.html

[Q58] 累计求和
来源：http://dali.ehwqpu.com/Article/details/gt2tualwfcs.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gt2xwwelmwf.html

[Q59] 分组内累计
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2jqowivkt.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gt2ufhaszoe.html

[Q60] 取上一行 / 下一行
来源：http://dali.bjfxy.top/Article/details/gt2tbwgnfoh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shanyushiyangtech.top/Article/details/gt2meyszuuu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cqqwz.cn/Article/details/gt2gjkdjzcf.html

[Q61] 移动平均
来源：http://dali.sweek.top/Article/details/gt2msqcswgr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hnqzz.top/Article/details/gt2uljpiumt.html

[Q62] 分组占比
来源：http://dali.xuanzx.com/Article/details/gt2grknzfsh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zdqjudy.top/Article/details/gt2otfflzwn.html

[Q63] 开启事务
来源：http://dali.sxryk.cn/Article/details/gt2otnlmoxc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bxeuflcy.html

[Q64] 提交事务
来源：http://dali.jinqigfzy.top/Article/details/gt2yzlfrwet.html

COMMIT;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2bgxjwjjq.html

[Q65] 回滚事务
来源：http://dali.hammf.cn/Article/details/gt2jnflxchw.html

ROLLBACK;
来源：http://dali.xuanzx.com/Article/details/gt2wcqolamz.html

[Q66] 行锁查询
来源：http://dali.c1oappe.top/Article/details/gt2eclvpfyp.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.snrcjt.cn/Article/details/gt2xnxlfffy.html

[Q67] 设置隔离级别
来源：http://dali.0kj1m.cn/Article/details/gt2fizzbhpr.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.havefunace.top/Article/details/gt2xuqjnvxc.html

[Q68] 保存点
来源：http://dali.kuanghao11.cn/Article/details/gt2qvpredyc.html

SAVEPOINT sp1;
来源：http://dali.chenzaomai.com/Article/details/gt2vbigqvsm.html

ROLLBACK TO sp1;
来源：http://dali.cheryme.top/Article/details/gt2hdlhxxrc.html

[Q69] 查看执行计划
来源：http://dali.bjfxy.top/Article/details/gt2ondjjdvb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.quarkkingdee.top/Article/details/gt2eoawqqgf.html

[Q70] 更新统计信息
来源：http://dali.hnxiangtu.top/Article/details/gt2dsbmwice.html

ANALYZE TABLE users;
来源：http://dali.gotoacloud.top/Article/details/gt2mnfdcmhr.html

[Q71] 查看建表语句
来源：http://dali.ppjwa.cn/Article/details/gt2hivzsqnp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.gaohongyu789.top/Article/details/gt2zkfkledf.html

[Q72] 查看索引
来源：http://dali.vqdsnc.cn/Article/details/gt2ozhsbiyr.html

SHOW INDEX FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2adnritsw.html

[Q73] 查看表状态
来源：http://dali.cheryme.top/Article/details/gt2beikadkh.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gaohongyu789.top/Article/details/gt2otyjidsa.html

[Q74] 强制使用索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2fsxpbrer.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.quarkkingdee.top/Article/details/gt2hiawmjrd.html

[Q75] 日期格式化
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2hyfoftpu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.smart0.xyz/Article/details/gt2yjcmhtkj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cheryme.top/Article/details/gt2nroyyndu.html

[Q76] 按天统计
来源：http://dali.dashuyun.cn/Article/details/gt2mgqfgmwe.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.nanxuanxn.top/Article/details/gt2aphnaucs.html

[Q77] 时间加减
来源：http://dali.tianlin.xyz/Article/details/gt2ycsmjihj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.dianchejie.cn/Article/details/gt2zhpmwlmb.html

[Q78] 当前时间
来源：http://dali.zhixingplan.top/Article/details/gt2yhteptip.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.vqdsnc.cn/Article/details/gt2pvclwljs.html

[Q79] 字符串拼接
来源：http://dali.cheryme.top/Article/details/gt2atzkdwou.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shangyingyoupin.top/Article/details/gt2cnbgapgj.html

[Q80] 字符串截取
来源：http://dali.bjfxy.top/Article/details/gt2ihyuzzbf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.meibo888.top/Article/details/gt2kbuldpkx.html

[Q81] 字符串替换
来源：http://dali.yanxiufei.cn/Article/details/gt2omamkqws.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ivvv.top/Article/details/gt2bhrxvgyq.html

[Q82] 字符长度与字节长度
来源：http://dali.cqqwz.cn/Article/details/gt2ssnfodba.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gt2imudahvq.html

[Q83] 大小写转换
来源：http://dali.nanxinkj.top/Article/details/gt2hhfwynbv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2zlfgkblg.html

[Q84] 去除首尾空格
来源：http://dali.svipenyu.cn/Article/details/gt2papznihk.html

SELECT TRIM(name) FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2zpzizlex.html

[Q85] 数值取整
来源：http://dali.yj20258888.top/Article/details/gt2ryqyheqv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.guannengcc.top/Article/details/gt2qbewxxvi.html

[Q86] 读取 JSON 字段
来源：http://dali.hongshengwenyu.top/Article/details/gt2uwjmkzka.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cdnleiting.top/Article/details/gt2vxuuwudq.html

[Q87] JSON 字段做条件
来源：http://dali.yuxming.cn/Article/details/gt2dupepkbh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.chenlongwang.top/Article/details/gt2akkkzmph.html

[Q88] 行转列（条件聚合）
来源：http://dali.yj20258.top/Article/details/gt2lorodtvm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hammf.cn/Article/details/gt2pdyerjov.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2odlxgugy.html

[Q89] 判断表是否存在
来源：http://dali.zhiwuduotai.top/Article/details/gt2jeruvlno.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.meibo888.top/Article/details/gt2zulujxxv.html

[Q90] 生成序号列
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mwxrvmwb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yuxming.cn/Article/details/gt2sznslpyx.html

================================================================================
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2kbstmada.html

R. Bash 专题
来源：http://dali.gogol.net.cn/Article/details/gt2zmevnjxr.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gt2kwkxbrui.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2ifppmuzx.html

#!/usr/bin/env bash
来源：http://dali.meibo888.top/Article/details/gt2jlzsfgly.html

set -euo pipefail
来源：http://dali.shangyingyoupin.top/Article/details/gt2chucnkin.html

[R02] 变量赋值与使用
来源：http://dali.cqqwz.cn/Article/details/gt2ggeueuux.html

name="Tom"; echo "$name"
来源：http://dali.jianghu66.top/Article/details/gt2ojpktmjh.html

[R03] 只读变量
来源：http://dali.tanke756.top/Article/details/gt2trplcgkk.html

readonly PI=3.14
来源：http://dali.ivvv.top/Article/details/gt2hwcygtet.html

[R04] 位置参数
来源：http://dali.wangshuangyany.cn/Article/details/gt2mtcnynqw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.0kj1m.cn/Article/details/gt2igcknosb.html

[R05] 参数默认值
来源：http://dali.sysykeji.top/Article/details/gt2vkfrbcxr.html

name="${1:-default}"
来源：http://dali.jinqigufen.top/Article/details/gt2xyxtdssc.html

[R06] 判断命令是否存在
来源：http://dali.cdnleiting.top/Article/details/gt2xhjkokoj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj202588.top/Article/details/gt2khteblbl.html

[R07] if 判断文件
来源：http://dali.yj202588.top/Article/details/gt2cjnisatm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.wangdashe.top/Article/details/gt2dtylepxt.html

[R08] 数值比较
来源：http://dali.ppjwa.cn/Article/details/gt2uxdxmcub.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tian-w.cn/Article/details/gt2fgwcjqgd.html

[R09] 字符串比较
来源：http://dali.yj20258888.top/Article/details/gt2pybpzedt.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jqgfzy.top/Article/details/gt2jdzuwgyu.html

[R10] 正则匹配
来源：http://dali.dashuyun.cn/Article/details/gt2gnzuczkw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.daria6918.cn/Article/details/gt2faswbrux.html

[R11] case 多分支
来源：http://dali.ivvv.top/Article/details/gt2fehjkybg.html

case "$1" in
来源：http://dali.zhiwuduotai.top/Article/details/gt2jqbpccxf.html

start) echo "启动" ;;
来源：http://dali.feifeiyinyue.top/Article/details/gt2fkxgsyss.html

stop)  echo "停止" ;;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2oiexmvbg.html

*)     echo "未知命令" ;;
来源：http://dali.ivvv.top/Article/details/gt2ilychadg.html

esac
来源：http://dali.haohaochexian.top/Article/details/gt2xeljxxek.html

[R12] for 遍历文件
来源：http://dali.gaohongyu789.top/Article/details/gt2mvxptfwj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sufxvd.cn/Article/details/gt2lnzptqfi.html

[R13] for 计数循环
来源：http://dali.xuetiantiany.cn/Article/details/gt2wzjxblhe.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.daria6918.cn/Article/details/gt2pfaarkza.html

[R14] C 风格 for
来源：http://dali.shanyushiyangtech.top/Article/details/gt2qmolgdyw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yj202588.top/Article/details/gt2csqcocsb.html

[R15] while 逐行读文件
来源：http://dali.tian-w.cn/Article/details/gt2ugyjmewh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.zhiwuduotai.top/Article/details/gt2nhlxebhz.html

[R16] until 等待条件
来源：http://dali.hfpthk.cn/Article/details/gt2tynlbyqy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gogol.net.cn/Article/details/gt2zprlxxeu.html

[R17] 数组定义与取值
来源：http://dali.yuxming.cn/Article/details/gt2utlmoizz.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jqgufenzy.top/Article/details/gt2drnetbhx.html

[R18] 遍历数组
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2zguimhlg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.iojbl.cn/Article/details/gt2xpaxyjdd.html

[R19] 数组长度
来源：http://dali.jinqigufen.top/Article/details/gt2ahfetfmu.html

echo "${#arr[@]}"
来源：http://dali.jinqigufen.top/Article/details/gt2ktczsgsr.html

[R20] 关联数组（字典）
来源：http://dali.ivvv.top/Article/details/gt2zqunctto.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.hfpthk.cn/Article/details/gt2gcytakkp.html

[R21] 字符串长度
来源：http://dali.dianchejie.cn/Article/details/gt2kqdcyuen.html

echo "${#s}"
来源：http://dali.quarkkingdee.top/Article/details/gt2xqmwlqah.html

[R22] 截取子串
来源：http://dali.yj20258.top/Article/details/gt2mcmhvcho.html

echo "${s:0:5}"
来源：http://dali.hnqzz.top/Article/details/gt2gfbmmvwc.html

[R23] 字符串替换
来源：http://dali.pengpengdd.cyou/Article/details/gt2pgutqbcj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.cdnleiting.top/Article/details/gt2dgwlpfez.html

[R24] 大小写转换
来源：http://dali.chenjidiqi.icu/Article/details/gt2gsusuwmi.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhijiandao.cn/Article/details/gt2brwripnw.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhijiandao.cn/Article/details/gt2tjmahfis.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jyoumei.cn/Article/details/gt2rwmospeh.html

[R26] 命令替换
来源：http://dali.gzhubu.top/Article/details/gt2omtpkepr.html

now=$(date +%F); echo "$now"
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2twocmbrh.html

[R27] 算术展开
来源：http://dali.yuxming.cn/Article/details/gt2usjvrqwe.html

echo $((1 + 2 * 3))
来源：http://dali.bjfxy.top/Article/details/gt2uqxorszf.html

[R28] 浮点运算
来源：http://dali.jiagoushi.top/Article/details/gt2zfergnfq.html

echo "scale=2; 10/3" | bc
来源：http://dali.cucudq.cn/Article/details/gt2spozlqpl.html

[R29] 定义函数
来源：http://dali.yonumen.top/Article/details/gt2tqjhbjao.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.0kj1m.cn/Article/details/gt2tetmdfbm.html

[R30] 函数返回状态码
来源：http://dali.bjfxy.top/Article/details/gt2irpfjynu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hnxiangtu.top/Article/details/gt2qkhjebln.html

[R31] 局部变量
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ohwqeuhi.html

f() { local x=1; echo "$x"; }
来源：http://dali.tianlin.xyz/Article/details/gt2uxwhblgf.html

[R32] 参数个数校验
来源：http://dali.jianghu66.top/Article/details/gt2voynzljm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.wangshuangyany.cn/Article/details/gt2pqafnpne.html

[R33] 捕获错误并提示行号
来源：http://dali.yonumen.top/Article/details/gt2zsrapeoi.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shuidangran.top/Article/details/gt2taiobetj.html

[R34] 退出时清理
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ccxuxuqn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yongpay.top/Article/details/gt2jicuismx.html

[R35] 后台执行并等待
来源：http://dali.ppjwa.cn/Article/details/gt2xoosvxaj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jqgfzy.top/Article/details/gt2udyeebvt.html

[R36] 并发执行多个任务
来源：http://dali.cqqwz.cn/Article/details/gt2zwcawsqd.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2lviryvdt.html

[R37] 把输出赋给变量
来源：http://dali.jlsjyb.cn/Article/details/gt2kiyrqwve.html

files=$(ls -1)
来源：http://dali.kuanghao11.cn/Article/details/gt2usxiwwhu.html

[R38] 管道串联
来源：http://dali.yuanzhike.top/Article/details/gt2pmgouonc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jqgfzy.top/Article/details/gt2cjtgfvim.html

[R39] 重定向标准输出与错误
来源：http://dali.fengsongda.top/Article/details/gt2izderpui.html

cmd > out.log 2>&1
来源：http://dali.yongpay.top/Article/details/gt2snsfvilu.html

[R40] 追加写日志
来源：http://dali.jiagoushi.top/Article/details/gt2axnfzofa.html

echo "log" >> out.log
来源：http://dali.pycfn.com/Article/details/gt2tblojcwl.html

[R41] 丢弃输出
来源：http://dali.sysykeji.top/Article/details/gt2ynebbnjm.html

cmd >/dev/null 2>&1
来源：http://dali.xuanzx.com/Article/details/gt2yhkeqayc.html

[R42] 输入重定向
来源：http://dali.sufxvd.cn/Article/details/gt2ghcyaqeh.html

wc -l < a.txt
来源：http://dali.quarkkingdee.top/Article/details/gt2ziccjsmr.html

[R43] 按名字查找文件
来源：http://dali.ybcxt.top/Article/details/gt2ltpinlvv.html

find . -name "*.log" -type f
来源：http://dali.meibo888.top/Article/details/gt2ozmsluju.html

[R44] 按修改时间查找
来源：http://dali.wangdashe.top/Article/details/gt2rhsmakkw.html

find . -mtime -7 -type f
来源：http://dali.jlsjyb.cn/Article/details/gt2auxrmuqd.html

[R45] 批量删除
来源：http://dali.dianchejie.cn/Article/details/gt2lqrbthfr.html

find . -name "*.tmp" -delete
来源：http://dali.yj20258888.top/Article/details/gt2undtfavq.html

[R46] 递归替换文件内容
来源：http://dali.jqgufenzy.top/Article/details/gt2oabclsnj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.nanxinkj.top/Article/details/gt2fqztqgxm.html

[R47] sed 单行替换
来源：http://dali.meibo888.top/Article/details/gt2reescccv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhengqikj.top/Article/details/gt2egialcxz.html

[R48] awk 取指定列
来源：http://dali.yuanzhike.top/Article/details/gt2ecuiwupo.html

awk '{print $1, $3}' a.txt
来源：http://dali.sufxvd.cn/Article/details/gt2jkjxuozm.html

[R49] awk 带条件
来源：http://dali.shuidangran.top/Article/details/gt2zramnvjs.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinqigufen.top/Article/details/gt2zgktegvk.html

[R50] awk 求和
来源：http://dali.316326.xyz/Article/details/gt2zoooehkb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yonumen.top/Article/details/gt2pdhagrym.html

[R51] 排序去重取前几
来源：http://dali.yj20258.top/Article/details/gt2ywakmrxt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shuidangran.top/Article/details/gt2jjijcvny.html

[R52] 统计行数
来源：http://dali.mhx1999.top/Article/details/gt2kbnwinfo.html

wc -l a.txt
来源：http://dali.yj202588.top/Article/details/gt2uhmpoago.html

[R53] 查看文件头与实时尾
来源：http://dali.tianlin.xyz/Article/details/gt2lnxtgbio.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gaohongyu789.top/Article/details/gt2nmkfnpzd.html

[R54] 比较两个文件
来源：http://dali.nanxinkj.top/Article/details/gt2jwpkzaqb.html

diff a.txt b.txt
来源：http://dali.yueranfly.top/Article/details/gt2yokarzyk.html

[R55] 压缩与解压
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ivhxugzj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yj20258888.top/Article/details/gt2bjiujkjr.html

[R56] 远程拷贝
来源：http://dali.wangshuangyany.cn/Article/details/gt2yjtngjym.html

scp file user@host:/path/
来源：http://dali.birdmap.top/Article/details/gt2ihmigedh.html

[R57] 远程执行命令
来源：http://dali.ydzc1.top/Article/details/gt2gwhmtxxa.html

ssh user@host 'uptime'
来源：http://dali.quarkkingdee.top/Article/details/gt2qcqvjtpc.html

[R58] 下载文件
来源：http://dali.dashuyun.cn/Article/details/gt2ouxeyhne.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nwbrower.top/Article/details/gt2lgqtasal.html

[R59] 发 POST JSON
来源：http://dali.zhengqikj.top/Article/details/gt2jvzvqmdw.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sufxvd.cn/Article/details/gt2buhtqcxq.html

[R60] 只看 HTTP 状态码
来源：http://dali.iojbl.cn/Article/details/gt2ladxflsv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.kuanghao11.cn/Article/details/gt2zzgxnnui.html

[R61] 磁盘占用
来源：http://dali.hnxiangtu.top/Article/details/gt2qvduefev.html

df -h;  du -sh *
来源：http://dali.hysaishi.cn/Article/details/gt2jxsxguko.html

[R62] 找最占空间的文件
来源：http://dali.cashguo.top/Article/details/gt2xxgxzdmm.html

du -ah . | sort -rh | head -10
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2txmahzde.html

[R63] 内存与进程
来源：http://dali.shzxlz.cn/Article/details/gt2pdhwxxoa.html

free -h;  ps aux | grep nginx
来源：http://dali.dashuyun.cn/Article/details/gt2wjyyxgsy.html

[R64] 结束进程
来源：http://dali.316326.xyz/Article/details/gt2tqvrqqyk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.cqqwz.cn/Article/details/gt2qvpbqznk.html

[R65] 查看端口占用
来源：http://dali.zycfv.cn/Article/details/gt2qiwvmoni.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yanxiufei.cn/Article/details/gt2srhdphwn.html

[R66] 定时任务
来源：http://dali.aizwys.cn/Article/details/gt2wdbitosv.html

crontab -e;  crontab -l
来源：http://dali.quarkkingdee.top/Article/details/gt2znffojyu.html

[R67] 生成随机十六进制串
来源：http://dali.nanxuanxn.top/Article/details/gt2bjbxnmhq.html

openssl rand -hex 16
来源：http://dali.chenzaomai.com/Article/details/gt2zldbjnas.html

[R68] 计算文件校验值
来源：http://dali.tanke756.top/Article/details/gt2iwprkvcr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.andypj.xyz/Article/details/gt2agjmfdgg.html

[R69] 生成随机密码
来源：http://dali.cqqwz.cn/Article/details/gt2rpkhidbl.html

head -c 16 /dev/urandom | base64
来源：http://dali.daxiang520.top/Article/details/gt2aetfcltp.html

[R70] 时间戳与互转
来源：http://dali.hfpthk.cn/Article/details/gt2rkvdenxd.html

date +%s;  date -d @1700000000
来源：http://dali.hfpthk.cn/Article/details/gt2wvufmkef.html

[R71] 日期格式化
来源：http://dali.gzhubu.top/Article/details/gt2ebozztpy.html


<!-- 参考信息 -->