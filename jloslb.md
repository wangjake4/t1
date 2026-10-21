代发 wailian999

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.cqqwz.cn/Article/details/gtnbeqmfnd.html

[Q20] IN 列表
来源：http://dali.andypj.xyz/Article/details/gtyohfgbfj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.dianchejie.cn/Article/details/gtptbmqwrz.html

[Q21] 空值判断
来源：http://dali.smart0.xyz/Article/details/gtcjjqfpvw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.pengpengdd.cyou/Article/details/gtondmehal.html

[Q22] 排序
来源：http://dali.jqgufenzy.top/Article/details/gtzvsckmli.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jiagoushi.top/Article/details/gtabuokonx.html

[Q23] 分页
来源：http://dali.birdmap.top/Article/details/gtipyxvucm.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ybcxt.top/Article/details/gtteehrghj.html

[Q24] 去重
来源：http://dali.jinqigufen.top/Article/details/gtpwjizfsw.html

SELECT DISTINCT city FROM users;
来源：http://dali.c1oappe.top/Article/details/gtfkozwyyz.html

[Q25] 只取前 N 条
来源：http://dali.zhixingplan.top/Article/details/gtrswfqiij.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gogol.net.cn/Article/details/gtrhzldskj.html

[Q26] 计数
来源：http://dali.fzhhl.top/Article/details/gtfvpspywf.html

SELECT COUNT(*) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtdkhctisp.html

[Q27] 条件计数
来源：http://dali.yonumen.top/Article/details/gtkbbdisyg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwjmxqmib.html

[Q28] 求和与平均
来源：http://dali.cqqwz.cn/Article/details/gtiurxfnfm.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gotoacloud.top/Article/details/gtnzstnjbg.html

[Q29] 最大最小值
来源：http://dali.shzxlz.cn/Article/details/gtmkoxjnzg.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtwbnwfweg.html

[Q30] 分组统计
来源：http://dali.jinqigufen.top/Article/details/gttdbqnefn.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shuidangran.top/Article/details/gtixjyxbvf.html

[Q31] 分组后过滤
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbgsctydt.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinqigufen.top/Article/details/gtjgyttxcz.html

[Q32] 分组拼接字符串
来源：http://dali.guannengcc.top/Article/details/gtqwkbeijj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.0kj1m.cn/Article/details/gtenxodsdh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.haohaochexian.top/Article/details/gtlxjypxnc.html

[Q33] 多列分组
来源：http://dali.0kj1m.cn/Article/details/gtzciiosiv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sufxvd.cn/Article/details/gtgsleevwm.html

[Q34] 每组取第一条
来源：http://dali.zhoulong.xyz/Article/details/gtogpfgwah.html

SELECT * FROM (
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthdtzrhbs.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sysykeji.top/Article/details/gtvfwrkjnz.html

) t WHERE rn = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtlavlinuz.html

[Q35] 内连接
来源：http://dali.jqgfzy.top/Article/details/gtmoevfltg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ivvv.top/Article/details/gtaqilgreo.html

[Q36] 左连接
来源：http://dali.gaohongyu789.top/Article/details/gtgrivqnqf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yvedp.cn/Article/details/gtonzolrmu.html

[Q37] 右连接
来源：http://dali.fengsongda.top/Article/details/gtazdofwmm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jiagoushi.top/Article/details/gtoyrjhreh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.fzhhl.top/Article/details/gtlosgawhh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gogol.net.cn/Article/details/gtytisjpas.html

[Q39] 自连接（查上下级）
来源：http://dali.ybcxt.top/Article/details/gthrrctqzh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hywenlv.cn/Article/details/gtshutrrzj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.gogol.net.cn/Article/details/gtfmwlqlqx.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.wangshuangyany.cn/Article/details/gtdxockvfz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.guowangkeji.top/Article/details/gtfatbgbmq.html

[Q41] 多表连接
来源：http://dali.jinghuilouyu.cn/Article/details/gtxujimpln.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaitvxtnc.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jianghu66.top/Article/details/gthtfbries.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yuanzhike.top/Article/details/gtvhgojdeu.html

[Q42] 连接条件附加过滤
来源：http://dali.yj202588.top/Article/details/gtzhwfewfx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sxryk.cn/Article/details/gttreyfmyu.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.tanke756.top/Article/details/gtwxrqrcbg.html

[Q43] 标量子查询
来源：http://dali.andypj.xyz/Article/details/gtehbanpdp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ivvv.top/Article/details/gtejdyvgvq.html

[Q44] IN 子查询
来源：http://dali.jinqigfzy.top/Article/details/gtzkchsivz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yuxming.cn/Article/details/gtvaqvctig.html

[Q45] EXISTS 判断存在
来源：http://dali.svipenyu.cn/Article/details/gtubdufaeg.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xinyue.icu/Article/details/gtryflxhoo.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hnxiangtu.top/Article/details/gttnyjngmu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.feifeiyinyue.top/Article/details/gtewyrnlkn.html

[Q47] 与平均值比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnuuvcjry.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhengqikj.top/Article/details/gtwsdefykm.html

[Q48] CTE 公用表表达式
来源：http://dali.hnxiangtu.top/Article/details/gtpsivunax.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.quarkkingdee.top/Article/details/gtahtpgctp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.birdmap.top/Article/details/gttjplmuet.html

[Q49] 更新单行
来源：http://dali.bjfxy.top/Article/details/gtvgwdregt.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jiagoushi.top/Article/details/gtvqctsrst.html

[Q50] 批量更新
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcsuvqnif.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.bjfxy.top/Article/details/gtsrdcmedx.html

[Q51] 用子查询更新
来源：http://dali.birdmap.top/Article/details/gtzfboiggk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.316326.xyz/Article/details/gtrhzlbuxx.html

[Q52] 删除指定行
来源：http://dali.fengsongda.top/Article/details/gtwbqytbwk.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yanxiufei.cn/Article/details/gtmmyxkdhk.html

[Q53] 按条件删除
来源：http://dali.fzhhl.top/Article/details/gtbvtxnqcp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jqgufenzy.top/Article/details/gtipbcnanu.html

[Q54] 清空表
来源：http://dali.chenzaomai.com/Article/details/gtcufcawgo.html

TRUNCATE TABLE logs;
来源：http://dali.birdmap.top/Article/details/gtwjuzdttc.html

[Q55] 排名（并列占位）
来源：http://dali.sweek.top/Article/details/gtnzvoquhy.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.daria6918.cn/Article/details/gtuxajprss.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xuanzx.com/Article/details/gtawowbhuu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhoulong.xyz/Article/details/gtuoxrjbtq.html

[Q57] 行号
来源：http://dali.yonumen.top/Article/details/gttucoutqp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnpazqhxg.html

[Q58] 累计求和
来源：http://dali.havefunace.top/Article/details/gtwtsnpkyc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gtyhvtakjl.html

[Q59] 分组内累计
来源：http://dali.nanxuanxn.top/Article/details/gtlwakiziv.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtqvqdgulw.html

[Q60] 取上一行 / 下一行
来源：http://dali.hnqzz.top/Article/details/gtotbiedeu.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yuanzhike.top/Article/details/gtkmwyoyjp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.gzhubu.top/Article/details/gtaccpclrm.html

[Q61] 移动平均
来源：http://dali.shuidangran.top/Article/details/gtomrmlhma.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtdxnkgfps.html

[Q62] 分组占比
来源：http://dali.sysykeji.top/Article/details/gtbwvhbgri.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yanxiufei.cn/Article/details/gtzkstsjow.html

[Q63] 开启事务
来源：http://dali.xziqi.cn/Article/details/gtmjkghqql.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.haohaochexian.top/Article/details/gtguraaswl.html

[Q64] 提交事务
来源：http://dali.mhx1999.top/Article/details/gtknjdfixb.html

COMMIT;
来源：http://dali.yueranfly.top/Article/details/gtksfugcxz.html

[Q65] 回滚事务
来源：http://dali.snrcjt.cn/Article/details/gtgucfitss.html

ROLLBACK;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnfzsjuqy.html

[Q66] 行锁查询
来源：http://dali.yvedp.cn/Article/details/gtztvzzwzy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yuxming.cn/Article/details/gtliftpqtw.html

[Q67] 设置隔离级别
来源：http://dali.xuanzx.com/Article/details/gtjpyjtmev.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cashguo.top/Article/details/gtjuvzpppp.html

[Q68] 保存点
来源：http://dali.xinyue.icu/Article/details/gtwuyreifk.html

SAVEPOINT sp1;
来源：http://dali.hywenlv.cn/Article/details/gteohrtxcu.html

ROLLBACK TO sp1;
来源：http://dali.sweek.top/Article/details/gtztszoicv.html

[Q69] 查看执行计划
来源：http://dali.jinqigufen.top/Article/details/gtbqeaaamb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jyoumei.cn/Article/details/gtpmxdrypj.html

[Q70] 更新统计信息
来源：http://dali.hfpthk.cn/Article/details/gtpuammqqg.html

ANALYZE TABLE users;
来源：http://dali.aibaodan.cn/Article/details/gtqjnnwwzd.html

[Q71] 查看建表语句
来源：http://dali.jqgfzy.top/Article/details/gteotibvzz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.smart0.xyz/Article/details/gtqivxqukz.html

[Q72] 查看索引
来源：http://dali.fengsongda.top/Article/details/gtqowjsqkm.html

SHOW INDEX FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtskivfpkr.html

[Q73] 查看表状态
来源：http://dali.gaohongyu789.top/Article/details/gtfabvqusc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hnqzz.top/Article/details/gtepqmodft.html

[Q74] 强制使用索引
来源：http://dali.yonumen.top/Article/details/gtubpwvkst.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhixingplan.top/Article/details/gtliqoxnqa.html

[Q75] 日期格式化
来源：http://dali.xuetiantiany.cn/Article/details/gtubgwerzb.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yuanzhike.top/Article/details/gtaywkzpti.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.tanke756.top/Article/details/gtnjzmogdj.html

[Q76] 按天统计
来源：http://dali.sweek.top/Article/details/gtnqmsjrhf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sufxvd.cn/Article/details/gtdjobcuhb.html

[Q77] 时间加减
来源：http://dali.wangshuangyany.cn/Article/details/gtvienridw.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.guowangkeji.top/Article/details/gtilgwhlcn.html

[Q78] 当前时间
来源：http://dali.shuidangran.top/Article/details/gtzrhndbwe.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cheryme.top/Article/details/gtthypcjwl.html

[Q79] 字符串拼接
来源：http://dali.yongpay.top/Article/details/gtcqqwtlyo.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.bjfxy.top/Article/details/gtlivlucjf.html

[Q80] 字符串截取
来源：http://dali.zhoulong.xyz/Article/details/gtdgngpwxj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.tanke756.top/Article/details/gtotajjbey.html

[Q81] 字符串替换
来源：http://dali.nanxuanxn.top/Article/details/gtlxuqzovq.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ydzc1.top/Article/details/gtrojhcvis.html

[Q82] 字符长度与字节长度
来源：http://dali.ehwqpu.com/Article/details/gtgfluiegz.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.birdmap.top/Article/details/gtbfalutmu.html

[Q83] 大小写转换
来源：http://dali.yanxiufei.cn/Article/details/gtzydqdexh.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yj202588.top/Article/details/gtckjtphcd.html

[Q84] 去除首尾空格
来源：http://dali.sxryk.cn/Article/details/gtmvooydyr.html

SELECT TRIM(name) FROM users;
来源：http://dali.tian-w.cn/Article/details/gttdccwwxh.html

[Q85] 数值取整
来源：http://dali.ppjwa.cn/Article/details/gtwmjjmhye.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.snrcjt.cn/Article/details/gtiflinbac.html

[Q86] 读取 JSON 字段
来源：http://dali.jinqigufen.top/Article/details/gtpquykfax.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ydzc1.top/Article/details/gtjgsajrbp.html

[Q87] JSON 字段做条件
来源：http://dali.jlsjyb.cn/Article/details/gttgfshnpl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gogol.net.cn/Article/details/gtfjckokjm.html

[Q88] 行转列（条件聚合）
来源：http://dali.xuetiantiany.cn/Article/details/gtshvrgfki.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.daria6918.cn/Article/details/gtksntrffv.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sweek.top/Article/details/gtnwyzjsyz.html

[Q89] 判断表是否存在
来源：http://dali.0kj1m.cn/Article/details/gthqaitiya.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hnqzz.top/Article/details/gtxiwblmnl.html

[Q90] 生成序号列
来源：http://dali.birdmap.top/Article/details/gtbbseowqc.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jianghu66.top/Article/details/gtidwujelt.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtrddynaui.html

R. Bash 专题
来源：http://dali.shangyingyoupin.top/Article/details/gttvllssvf.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtrcinzdmy.html

[R01] shebang 与严格模式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwpbiijvc.html

#!/usr/bin/env bash
来源：http://dali.cheryme.top/Article/details/gtrhhyjerm.html

set -euo pipefail
来源：http://dali.mhx1999.top/Article/details/gthtfogxyd.html

[R02] 变量赋值与使用
来源：http://dali.feifeiyinyue.top/Article/details/gtkvxglhmn.html

name="Tom"; echo "$name"
来源：http://dali.yuxming.cn/Article/details/gtppqsomxu.html

[R03] 只读变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtjcqakgkq.html

readonly PI=3.14
来源：http://dali.shanyushiyangtech.top/Article/details/gtcklgezvj.html

[R04] 位置参数
来源：http://dali.yvedp.cn/Article/details/gtxahjhkxd.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.c1oappe.top/Article/details/gtfaxtnnyf.html

[R05] 参数默认值
来源：http://dali.ybcxt.top/Article/details/gtudgqmslb.html

name="${1:-default}"
来源：http://dali.jianghu66.top/Article/details/gtyeakvzwc.html

[R06] 判断命令是否存在
来源：http://dali.meibo888.top/Article/details/gtrhbnpvpq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yongpay.top/Article/details/gtqerjblke.html

[R07] if 判断文件
来源：http://dali.sweek.top/Article/details/gtowywbcti.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.ybcxt.top/Article/details/gtyjpwdddy.html

[R08] 数值比较
来源：http://dali.gaohongyu789.top/Article/details/gtpzczfwjn.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yvedp.cn/Article/details/gtvygewuct.html

[R09] 字符串比较
来源：http://dali.gogol.net.cn/Article/details/gtpzgdywan.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj20258888.top/Article/details/gtuhxpshfj.html

[R10] 正则匹配
来源：http://dali.quarkkingdee.top/Article/details/gtgxtresqw.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.cdnleiting.top/Article/details/gtsjneqgxl.html

[R11] case 多分支
来源：http://dali.hnqzz.top/Article/details/gtwitqmhle.html

case "$1" in
来源：http://dali.bjfxy.top/Article/details/gtxoxabmoq.html

start) echo "启动" ;;
来源：http://dali.yueranfly.top/Article/details/gtemhwyngv.html

stop)  echo "停止" ;;
来源：http://dali.ybcxt.top/Article/details/gtzlaycluv.html

*)     echo "未知命令" ;;
来源：http://dali.yj202588.top/Article/details/gtahdarorq.html

esac
来源：http://dali.xuetiantiany.cn/Article/details/gthfeamyye.html

[R12] for 遍历文件
来源：http://dali.zhiwuduotai.top/Article/details/gtdyonjzjz.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtimwpljbm.html

[R13] for 计数循环
来源：http://dali.xuanzx.com/Article/details/gtqebohxth.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yongpay.top/Article/details/gtywrnmusy.html

[R14] C 风格 for
来源：http://dali.vqdsnc.cn/Article/details/gtqxfnlpdq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.smart0.xyz/Article/details/gtfsmtmgbi.html

[R15] while 逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gtdqrbppha.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.chenlongwang.top/Article/details/gtkbdyprht.html

[R16] until 等待条件
来源：http://dali.tianlin.xyz/Article/details/gtriiiinvy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hywenlv.cn/Article/details/gtpinzcjrx.html

[R17] 数组定义与取值
来源：http://dali.dashuyun.cn/Article/details/gtxrsqsnqa.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.gotoacloud.top/Article/details/gtounchgyq.html

[R18] 遍历数组
来源：http://dali.xylfe.cn/Article/details/gtasslhmzp.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtjutrgzbb.html

[R19] 数组长度
来源：http://dali.yj20258.top/Article/details/gtwdaxurnq.html

echo "${#arr[@]}"
来源：http://dali.ybcxt.top/Article/details/gtaboxffve.html

[R20] 关联数组（字典）
来源：http://dali.shangyingyoupin.top/Article/details/gtplneechq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.haohaochexian.top/Article/details/gtcdztvrmu.html

[R21] 字符串长度
来源：http://dali.tianlin.xyz/Article/details/gtmufthmij.html

echo "${#s}"
来源：http://dali.wangshuangyany.cn/Article/details/gtnsdumkzy.html

[R22] 截取子串
来源：http://dali.hnqzz.top/Article/details/gtbcqfgrbm.html

echo "${s:0:5}"
来源：http://dali.daria6918.cn/Article/details/gtvoionvcy.html

[R23] 字符串替换
来源：http://dali.pengpengdd.cyou/Article/details/gttdbzspef.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jqgfzy.top/Article/details/gtzhbtcvaa.html

[R24] 大小写转换
来源：http://dali.sweek.top/Article/details/gtlvvgruzr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hnxiangtu.top/Article/details/gtpbqoabco.html

[R25] 去后缀 / 去前缀
来源：http://dali.jianghu66.top/Article/details/gtqzzpahpw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.smart0.xyz/Article/details/gtlmgyjzfg.html

[R26] 命令替换
来源：http://dali.tian-w.cn/Article/details/gtkcmozedk.html

now=$(date +%F); echo "$now"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlqymxqrj.html

[R27] 算术展开
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwnwwwhrs.html

echo $((1 + 2 * 3))
来源：http://dali.fengsongda.top/Article/details/gtjtmvqpsx.html

[R28] 浮点运算
来源：http://dali.hysaishi.cn/Article/details/gtlfylehee.html

echo "scale=2; 10/3" | bc
来源：http://dali.ydzc1.top/Article/details/gtjbkiacsj.html

[R29] 定义函数
来源：http://dali.hysaishi.cn/Article/details/gtbhsmhngy.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hammf.cn/Article/details/gtssbpdule.html

[R30] 函数返回状态码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzrbeoadb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sweek.top/Article/details/gtjomppmcp.html

[R31] 局部变量
来源：http://dali.jyoumei.cn/Article/details/gtqcgktkvf.html

f() { local x=1; echo "$x"; }
来源：http://dali.jinqigfzy.top/Article/details/gtwbpfcdkv.html

[R32] 参数个数校验
来源：http://dali.jqgufenzy.top/Article/details/gtcsluipbq.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.aizwys.cn/Article/details/gttlqdtdxa.html

[R33] 捕获错误并提示行号
来源：http://dali.hywenlv.cn/Article/details/gtskxgesnl.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ehwqpu.com/Article/details/gtabvzlnij.html

[R34] 退出时清理
来源：http://dali.cheryme.top/Article/details/gtexqjdfnp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.gogol.net.cn/Article/details/gtnavpdzve.html

[R35] 后台执行并等待
来源：http://dali.sufxvd.cn/Article/details/gtkvozedtm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jlsjyb.cn/Article/details/gtngvueisl.html

[R36] 并发执行多个任务
来源：http://dali.chenjidiqi.icu/Article/details/gtgvhcwfix.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nanxuanxn.top/Article/details/gtxfivirbb.html

[R37] 把输出赋给变量
来源：http://dali.hnqzz.top/Article/details/gtkmpscluk.html

files=$(ls -1)
来源：http://dali.haohaochexian.top/Article/details/gtzngmpqxy.html

[R38] 管道串联
来源：http://dali.pycfn.com/Article/details/gtctwigyra.html

cat a.txt | grep -i error | wc -l
来源：http://dali.zhijiandao.cn/Article/details/gtdkqeesla.html

[R39] 重定向标准输出与错误
来源：http://dali.meibo888.top/Article/details/gtckshusak.html

cmd > out.log 2>&1
来源：http://dali.yanxiufei.cn/Article/details/gtascjsjxb.html

[R40] 追加写日志
来源：http://dali.guowangkeji.top/Article/details/gtwpoafwvb.html

echo "log" >> out.log
来源：http://dali.snrcjt.cn/Article/details/gtaltgvxgw.html

[R41] 丢弃输出
来源：http://dali.kuanghao11.cn/Article/details/gtnnlcsqld.html

cmd >/dev/null 2>&1
来源：http://dali.sweek.top/Article/details/gttqvvqhpx.html

[R42] 输入重定向
来源：http://dali.gaohongyu789.top/Article/details/gtyqhyjkii.html

wc -l < a.txt
来源：http://dali.zhijiandao.cn/Article/details/gtnfjpozqp.html

[R43] 按名字查找文件
来源：http://dali.mhx1999.top/Article/details/gtjfkqfrud.html

find . -name "*.log" -type f
来源：http://dali.yangfankeji.com/Article/details/gtciewexxl.html

[R44] 按修改时间查找
来源：http://dali.wangshuangyany.cn/Article/details/gtruhygzgv.html

find . -mtime -7 -type f
来源：http://dali.shzxlz.cn/Article/details/gtgnrtgklc.html

[R45] 批量删除
来源：http://dali.quarkkingdee.top/Article/details/gtaosoorpm.html

find . -name "*.tmp" -delete
来源：http://dali.cashguo.top/Article/details/gtwghalhsp.html

[R46] 递归替换文件内容
来源：http://dali.tanke756.top/Article/details/gtyhlaudaw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xziqi.cn/Article/details/gtmlvplnjt.html

[R47] sed 单行替换
来源：http://dali.shuidangran.top/Article/details/gtxfmnkqzu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.haohaochexian.top/Article/details/gtaoxcfezp.html

[R48] awk 取指定列
来源：http://dali.mhx1999.top/Article/details/gtmeupqmpf.html

awk '{print $1, $3}' a.txt
来源：http://dali.sxryk.cn/Article/details/gtgmymzsjl.html

[R49] awk 带条件
来源：http://dali.meibo888.top/Article/details/gtgaypekau.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.daxiang520.top/Article/details/gtxyftkevp.html

[R50] awk 求和
来源：http://dali.yangfankeji.com/Article/details/gtkprqrcgx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gogol.net.cn/Article/details/gtxajpcjgc.html

[R51] 排序去重取前几
来源：http://dali.andypj.xyz/Article/details/gtwcuzjttv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinqigfzy.top/Article/details/gtwrmsxfra.html

[R52] 统计行数
来源：http://dali.yj202588.top/Article/details/gtebzropzo.html

wc -l a.txt
来源：http://dali.hammf.cn/Article/details/gtjbpamebq.html

[R53] 查看文件头与实时尾
来源：http://dali.sysykeji.top/Article/details/gtplhdjgtm.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinghuilouyu.cn/Article/details/gtevjxwejt.html

[R54] 比较两个文件
来源：http://dali.hysaishi.cn/Article/details/gttovwzrok.html

diff a.txt b.txt
来源：http://dali.zycfv.cn/Article/details/gtmmazyuip.html

[R55] 压缩与解压
来源：http://dali.yvedp.cn/Article/details/gtypxcgtmh.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.aibaodan.cn/Article/details/gtoxaaorka.html

[R56] 远程拷贝
来源：http://dali.meibo888.top/Article/details/gtbypxjznx.html

scp file user@host:/path/
来源：http://dali.jinqigufen.top/Article/details/gtkunoihsn.html

[R57] 远程执行命令
来源：http://dali.bjfxy.top/Article/details/gtgtsjkuoq.html

ssh user@host 'uptime'
来源：http://dali.ppjwa.cn/Article/details/gtproavmpl.html

[R58] 下载文件
来源：http://dali.yonumen.top/Article/details/gtkrhayqur.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvimxprjp.html

[R59] 发 POST JSON
来源：http://dali.shanyushiyangtech.top/Article/details/gtgssnrpmr.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sufxvd.cn/Article/details/gtjgkuodgv.html

[R60] 只看 HTTP 状态码
来源：http://dali.zycfv.cn/Article/details/gtgsszpwau.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.bjfxy.top/Article/details/gtsndepzjx.html

[R61] 磁盘占用
来源：http://dali.jinqigufen.top/Article/details/gtcoeevppk.html

df -h;  du -sh *
来源：http://dali.gaohongyu789.top/Article/details/gtnygygdgg.html

[R62] 找最占空间的文件
来源：http://dali.c1oappe.top/Article/details/gttlhyczwe.html

du -ah . | sort -rh | head -10
来源：http://dali.cucudq.cn/Article/details/gtrbqpikyv.html

[R63] 内存与进程
来源：http://dali.xylfe.cn/Article/details/gttecvxyej.html

free -h;  ps aux | grep nginx
来源：http://dali.hammf.cn/Article/details/gtuujgaywg.html

[R64] 结束进程
来源：http://dali.jqgufenzy.top/Article/details/gtdzpycmzs.html

kill -9 $(pgrep -f app.py)
来源：http://dali.316326.xyz/Article/details/gtggfvbpts.html

[R65] 查看端口占用
来源：http://dali.jinghuilouyu.cn/Article/details/gtxiqtvaky.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.sweek.top/Article/details/gtxpyenmpr.html

[R66] 定时任务
来源：http://dali.nanxinkj.top/Article/details/gtghxbieyn.html

crontab -e;  crontab -l
来源：http://dali.zhengqikj.top/Article/details/gtmlbfhsty.html

[R67] 生成随机十六进制串
来源：http://dali.hysaishi.cn/Article/details/gtaycfcyrt.html

openssl rand -hex 16
来源：http://dali.andypj.xyz/Article/details/gtmuitqxlg.html

[R68] 计算文件校验值
来源：http://dali.feifeiyinyue.top/Article/details/gtkidwzszp.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ivvv.top/Article/details/gtgtiejnqv.html

[R69] 生成随机密码
来源：http://dali.meibo888.top/Article/details/gtkhdlpnca.html


<!-- 参考信息 -->