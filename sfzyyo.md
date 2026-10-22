代发 wailian999

INSERT INTO users (name) VALUES ('C');
来源：http://dali.9152youxi.cn/Article/details/gt2mrtbkevw.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shzxlz.cn/Article/details/gt2ulyxzquj.html

[Q13] 忽略重复插入
来源：http://dali.feifeiyinyue.top/Article/details/gt2drdtftmq.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.andypj.xyz/Article/details/gt2tgsxwscc.html

[Q14] 存在则更新（upsert）
来源：http://dali.jlsjyb.cn/Article/details/gt2qcgbhjgf.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.cheryme.top/Article/details/gt2tnnewvgs.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.quarkkingdee.top/Article/details/gt2onrfahpf.html

[Q15] 查询全部
来源：http://dali.yvedp.cn/Article/details/gt2sjgakvmg.html

SELECT * FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gt2rehegafq.html

[Q16] 查询指定列
来源：http://dali.yj20258888.top/Article/details/gt2viiyooqx.html

SELECT id, name FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2jqasopbp.html

[Q17] 条件查询
来源：http://dali.zdqjudy.top/Article/details/gt2xbdtmldr.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yongpay.top/Article/details/gt2ckhbubiy.html

[Q18] 模糊匹配
来源：http://dali.zhoulong.xyz/Article/details/gt2iwtwsglp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jqgfzy.top/Article/details/gt2echkymqs.html

[Q19] 范围查询
来源：http://dali.wangshuangyany.cn/Article/details/gt2roownukx.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.316326.xyz/Article/details/gt2nstdwdzz.html

[Q20] IN 列表
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2eehvajmm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cashguo.top/Article/details/gt2zoobkkgd.html

[Q21] 空值判断
来源：http://dali.feifeiyinyue.top/Article/details/gt2paimhjvr.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.haohaochexian.top/Article/details/gt2xhwkkicw.html

[Q22] 排序
来源：http://dali.feifeiyinyue.top/Article/details/gt2vperblcy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.hysaishi.cn/Article/details/gt2borflxkr.html

[Q23] 分页
来源：http://dali.9152youxi.cn/Article/details/gt2ttdkjius.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.vqdsnc.cn/Article/details/gt2dxhbevhm.html

[Q24] 去重
来源：http://dali.c1oappe.top/Article/details/gt2bzqukupb.html

SELECT DISTINCT city FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2cidezkuq.html

[Q25] 只取前 N 条
来源：http://dali.dashuyun.cn/Article/details/gt2cyhoijyy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.sufxvd.cn/Article/details/gt2ijmpyfkv.html

[Q26] 计数
来源：http://dali.yueranfly.top/Article/details/gt2hradhkbm.html

SELECT COUNT(*) FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2havqduts.html

[Q27] 条件计数
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2zzkpbpsg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yj20258.top/Article/details/gt2ouitvegl.html

[Q28] 求和与平均
来源：http://dali.zhiwuduotai.top/Article/details/gt2hpmrrjnu.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xziqi.cn/Article/details/gt2yjnukygg.html

[Q29] 最大最小值
来源：http://dali.nanxuanxn.top/Article/details/gt2fpunykeq.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2ohosfint.html

[Q30] 分组统计
来源：http://dali.aizwys.cn/Article/details/gt2mijlmaix.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yj202588.top/Article/details/gt2afuirjnu.html

[Q31] 分组后过滤
来源：http://dali.ppjwa.cn/Article/details/gt2infuqgsk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.nwbrower.top/Article/details/gt2zpuwoaxp.html

[Q32] 分组拼接字符串
来源：http://dali.sysykeji.top/Article/details/gt2dkucxadp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.wangshuangyany.cn/Article/details/gt2iokgleev.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shangyingyoupin.top/Article/details/gt2ivyqhtii.html

[Q33] 多列分组
来源：http://dali.ybcxt.top/Article/details/gt2eqhrxvsu.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.haohaochexian.top/Article/details/gt2pikizazm.html

[Q34] 每组取第一条
来源：http://dali.jqgfzy.top/Article/details/gt2wusffwhs.html

SELECT * FROM (
来源：http://dali.nwbrower.top/Article/details/gt2dyqbpmgf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.mhx1999.top/Article/details/gt2nubqwsnl.html

) t WHERE rn = 1;
来源：http://dali.shangyingyoupin.top/Article/details/gt2vregxfju.html

[Q35] 内连接
来源：http://dali.tian-w.cn/Article/details/gt2vntrhnmi.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.smart0.xyz/Article/details/gt2qjotyuae.html

[Q36] 左连接
来源：http://dali.zhoulong.xyz/Article/details/gt2xjfouzwf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hongshengwenyu.top/Article/details/gt2owwgcuii.html

[Q37] 右连接
来源：http://dali.sweek.top/Article/details/gt2ulbttncp.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.redwolf501.top/Article/details/gt2lifahafr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jqgfzy.top/Article/details/gt2mycqlzfe.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.meibo888.top/Article/details/gt2tbijnuax.html

[Q39] 自连接（查上下级）
来源：http://dali.yj20258888.top/Article/details/gt2lldljeyl.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.havefunace.top/Article/details/gt2qhshlant.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.bjfxy.top/Article/details/gt2gdnwxjmh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hnxiangtu.top/Article/details/gt2eixsxkmk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.pengpengdd.cyou/Article/details/gt2aalgufzd.html

[Q41] 多表连接
来源：http://dali.hammf.cn/Article/details/gt2suldfuuy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.guowangkeji.top/Article/details/gt2qghcffvq.html

JOIN users u ON u.id = o.user_id
来源：http://dali.chenjidiqi.icu/Article/details/gt2xggzkfwy.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.gotoacloud.top/Article/details/gt2fzbkncgh.html

[Q42] 连接条件附加过滤
来源：http://dali.zhoulong.xyz/Article/details/gt2uhmvwtpa.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2yahmilvg.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.tanke756.top/Article/details/gt2uwtcjtjj.html

[Q43] 标量子查询
来源：http://dali.yangfankeji.com/Article/details/gt2bsehimsq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gzhubu.top/Article/details/gt2tlyzibia.html

[Q44] IN 子查询
来源：http://dali.zdqjudy.top/Article/details/gt2wflvlmxx.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinqigfzy.top/Article/details/gt2ftainagf.html

[Q45] EXISTS 判断存在
来源：http://dali.shangyingyoupin.top/Article/details/gt2rfjbwgbt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhengqikj.top/Article/details/gt2asvmscwp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xylfe.cn/Article/details/gt2spoazyxl.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.0kj1m.cn/Article/details/gt2snltmdmt.html

[Q47] 与平均值比较
来源：http://dali.guannengcc.top/Article/details/gt2ugzeikkd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.tianlin.xyz/Article/details/gt2pnasbvzy.html

[Q48] CTE 公用表表达式
来源：http://dali.yangfankeji.com/Article/details/gt2xomylcbd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.daria6918.cn/Article/details/gt2xotctazu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xylfe.cn/Article/details/gt2ezdfuclw.html

[Q49] 更新单行
来源：http://dali.zhengqikj.top/Article/details/gt2qamknyqk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.wangdashe.top/Article/details/gt2rdisisrt.html

[Q50] 批量更新
来源：http://dali.shuidangran.top/Article/details/gt2ddpgbwzw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.shzxlz.cn/Article/details/gt2ahnohlrs.html

[Q51] 用子查询更新
来源：http://dali.gaohongyu789.top/Article/details/gt2lbfsycfv.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yvedp.cn/Article/details/gt2mvoxexmh.html

[Q52] 删除指定行
来源：http://dali.hongshengwenyu.top/Article/details/gt2psoqgthn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2yrvyoqqp.html

[Q53] 按条件删除
来源：http://dali.shangyingyoupin.top/Article/details/gt2kiepgmtp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shanyushiyangtech.top/Article/details/gt2tmeyftiu.html

[Q54] 清空表
来源：http://dali.yonumen.top/Article/details/gt2mnfpdrwz.html

TRUNCATE TABLE logs;
来源：http://dali.meibo888.top/Article/details/gt2urmohire.html

[Q55] 排名（并列占位）
来源：http://dali.pengpengdd.cyou/Article/details/gt2zvvhnjuq.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cheryme.top/Article/details/gt2wafxolhg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2lwiztcgf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ppjwa.cn/Article/details/gt2fuitvlpn.html

[Q57] 行号
来源：http://dali.yj202588.top/Article/details/gt2jmnegbre.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yvedp.cn/Article/details/gt2ghygyuye.html

[Q58] 累计求和
来源：http://dali.wangshuangyany.cn/Article/details/gt2ynbidnmo.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.havefunace.top/Article/details/gt2atbgiqki.html

[Q59] 分组内累计
来源：http://dali.daria6918.cn/Article/details/gt2gvosgphd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.aizwys.cn/Article/details/gt2iefxefxc.html

[Q60] 取上一行 / 下一行
来源：http://dali.smart0.xyz/Article/details/gt2qwpiirco.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yongpay.top/Article/details/gt2hgftdnlz.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cashguo.top/Article/details/gt2lknppfey.html

[Q61] 移动平均
来源：http://dali.hammf.cn/Article/details/gt2ngnbebpb.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gt2neupnyxw.html

[Q62] 分组占比
来源：http://dali.fengsongda.top/Article/details/gt2yhxsibji.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.pycfn.com/Article/details/gt2rmoswdmo.html

[Q63] 开启事务
来源：http://dali.yj202588.top/Article/details/gt2tujlikse.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sysykeji.top/Article/details/gt2pfvqxjdk.html

[Q64] 提交事务
来源：http://dali.nwbrower.top/Article/details/gt2fmduixxa.html

COMMIT;
来源：http://dali.ydzc1.top/Article/details/gt2fpcxhzgy.html

[Q65] 回滚事务
来源：http://dali.zhixingplan.top/Article/details/gt2wviljkjs.html

ROLLBACK;
来源：http://dali.hfpthk.cn/Article/details/gt2aqerrwry.html

[Q66] 行锁查询
来源：http://dali.chenzaomai.com/Article/details/gt2cavcchel.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ywenpdnh.html

[Q67] 设置隔离级别
来源：http://dali.ivvv.top/Article/details/gt2azdxxuky.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cqqwz.cn/Article/details/gt2eapvsqpn.html

[Q68] 保存点
来源：http://dali.sxryk.cn/Article/details/gt2ikqpwalr.html

SAVEPOINT sp1;
来源：http://dali.jinqigfzy.top/Article/details/gt2nvhgkuit.html

ROLLBACK TO sp1;
来源：http://dali.cashguo.top/Article/details/gt2gbdqfzzq.html

[Q69] 查看执行计划
来源：http://dali.xylfe.cn/Article/details/gt2litqephi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.bjfxy.top/Article/details/gt2kigxdznk.html

[Q70] 更新统计信息
来源：http://dali.fengsongda.top/Article/details/gt2cqwcswxv.html

ANALYZE TABLE users;
来源：http://dali.meibo888.top/Article/details/gt2ucnbjwll.html

[Q71] 查看建表语句
来源：http://dali.daria6918.cn/Article/details/gt2mwzcrilt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhiwuduotai.top/Article/details/gt2aijjaior.html

[Q72] 查看索引
来源：http://dali.daria6918.cn/Article/details/gt2sojatkrc.html

SHOW INDEX FROM users;
来源：http://dali.cashguo.top/Article/details/gt2grwzfphi.html

[Q73] 查看表状态
来源：http://dali.daxiang520.top/Article/details/gt2fknueukd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jinqigfzy.top/Article/details/gt2lmcvzyab.html

[Q74] 强制使用索引
来源：http://dali.yj202588.top/Article/details/gt2daadkeou.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jqgufenzy.top/Article/details/gt2pfivztll.html

[Q75] 日期格式化
来源：http://dali.jiagoushi.top/Article/details/gt2hrasvjho.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jianghu66.top/Article/details/gt2fnznqpyo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.meibo888.top/Article/details/gt2xnhpsaed.html

[Q76] 按天统计
来源：http://dali.zycfv.cn/Article/details/gt2wtndspby.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yj20258.top/Article/details/gt2wpmbqmtx.html

[Q77] 时间加减
来源：http://dali.daxiang520.top/Article/details/gt2lnkplssg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yanxiufei.cn/Article/details/gt2vuaplibr.html

[Q78] 当前时间
来源：http://dali.tianlin.xyz/Article/details/gt2hsuahxht.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.svipenyu.cn/Article/details/gt2ccczrmif.html

[Q79] 字符串拼接
来源：http://dali.hammf.cn/Article/details/gt2ofmmfoml.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2mpqbkmky.html

[Q80] 字符串截取
来源：http://dali.xylfe.cn/Article/details/gt2raithxzn.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gt2gewricvc.html

[Q81] 字符串替换
来源：http://dali.andypj.xyz/Article/details/gt2yhajbhws.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2yzfaqalf.html

[Q82] 字符长度与字节长度
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mgnpaqsg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.daxiang520.top/Article/details/gt2pcjryutw.html

[Q83] 大小写转换
来源：http://dali.wangdashe.top/Article/details/gt2axvobtgu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gt2kbeutgdk.html

[Q84] 去除首尾空格
来源：http://dali.sweek.top/Article/details/gt2rqbxnugg.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gt2xgttjduo.html

[Q85] 数值取整
来源：http://dali.shzxlz.cn/Article/details/gt2jbpnqbrn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.quarkkingdee.top/Article/details/gt2zewvxvdf.html

[Q86] 读取 JSON 字段
来源：http://dali.yvedp.cn/Article/details/gt2yzcsixsm.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.c1oappe.top/Article/details/gt2vjfymdgn.html

[Q87] JSON 字段做条件
来源：http://dali.hnxiangtu.top/Article/details/gt2kzvlhqcv.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zycfv.cn/Article/details/gt2enkpdqaf.html

[Q88] 行转列（条件聚合）
来源：http://dali.ppjwa.cn/Article/details/gt2idwzzbwv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.havefunace.top/Article/details/gt2llstmykg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gt2ogqtvvbi.html

[Q89] 判断表是否存在
来源：http://dali.hysaishi.cn/Article/details/gt2vnkifzea.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sufxvd.cn/Article/details/gt2zajuthmp.html

[Q90] 生成序号列
来源：http://dali.bjfxy.top/Article/details/gt2prjabmzl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.vqdsnc.cn/Article/details/gt2wvkfxdni.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gt2srhkwyxq.html

R. Bash 专题
来源：http://dali.nwbrower.top/Article/details/gt2sdfeqxhv.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2yvegvojy.html

[R01] shebang 与严格模式
来源：http://dali.guowangkeji.top/Article/details/gt2dusjmxuq.html

#!/usr/bin/env bash
来源：http://dali.bjfxy.top/Article/details/gt2yyxrluyd.html

set -euo pipefail
来源：http://dali.cqqwz.cn/Article/details/gt2wuwiqkoc.html

[R02] 变量赋值与使用
来源：http://dali.sysykeji.top/Article/details/gt2yaxihnug.html

name="Tom"; echo "$name"
来源：http://dali.jlsjyb.cn/Article/details/gt2uarvmleg.html

[R03] 只读变量
来源：http://dali.shangyingyoupin.top/Article/details/gt2plsonfyb.html

readonly PI=3.14
来源：http://dali.zhoulong.xyz/Article/details/gt2oclvhalc.html

[R04] 位置参数
来源：http://dali.iojbl.cn/Article/details/gt2splzqkfc.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.dashuyun.cn/Article/details/gt2jcekiypb.html

[R05] 参数默认值
来源：http://dali.pycfn.com/Article/details/gt2xeybbbfe.html

name="${1:-default}"
来源：http://dali.andypj.xyz/Article/details/gt2hjrkfozx.html

[R06] 判断命令是否存在
来源：http://dali.yj20258888.top/Article/details/gt2myrlennl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.svipenyu.cn/Article/details/gt2eagqipmq.html

[R07] if 判断文件
来源：http://dali.zhijiandao.cn/Article/details/gt2lyjiolkt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.meibo888.top/Article/details/gt2iigyhpee.html

[R08] 数值比较
来源：http://dali.sxryk.cn/Article/details/gt2fqhdeshb.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jianghu66.top/Article/details/gt2ldoecddv.html

[R09] 字符串比较
来源：http://dali.pengpengdd.cyou/Article/details/gt2vadqjhig.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xuanzx.com/Article/details/gt2ltnhvlku.html

[R10] 正则匹配
来源：http://dali.yj202588.top/Article/details/gt2biskapqh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.kuanghao11.cn/Article/details/gt2vdiwqkab.html

[R11] case 多分支
来源：http://dali.gotoacloud.top/Article/details/gt2uhroygpk.html

case "$1" in
来源：http://dali.jiagoushi.top/Article/details/gt2gaxjneph.html

start) echo "启动" ;;
来源：http://dali.ydzc1.top/Article/details/gt2aispjuwv.html

stop)  echo "停止" ;;
来源：http://dali.yuxming.cn/Article/details/gt2yqxohbtf.html

*)     echo "未知命令" ;;
来源：http://dali.shuidangran.top/Article/details/gt2rggqvopz.html

esac
来源：http://dali.zhixingplan.top/Article/details/gt2dzokzlwz.html

[R12] for 遍历文件
来源：http://dali.quarkkingdee.top/Article/details/gt2jjpddazr.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ehwqpu.com/Article/details/gt2azczfsxu.html

[R13] for 计数循环
来源：http://dali.zhijiandao.cn/Article/details/gt2frkgswph.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cheryme.top/Article/details/gt2qjviyygy.html

[R14] C 风格 for
来源：http://dali.xylfe.cn/Article/details/gt2barfncck.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yangfankeji.com/Article/details/gt2vnsbsfpz.html

[R15] while 逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gt2apzrnaxs.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cdnleiting.top/Article/details/gt2eepedmbn.html

[R16] until 等待条件
来源：http://dali.snrcjt.cn/Article/details/gt2fpzugnzz.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.svipenyu.cn/Article/details/gt2ctrlctpo.html

[R17] 数组定义与取值
来源：http://dali.nanxinkj.top/Article/details/gt2elmjyzfy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jlsjyb.cn/Article/details/gt2afrrtycc.html

[R18] 遍历数组
来源：http://dali.gzhubu.top/Article/details/gt2cnehpmrk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.tian-w.cn/Article/details/gt2kndashle.html

[R19] 数组长度
来源：http://dali.jqgufenzy.top/Article/details/gt2hmexbnjc.html

echo "${#arr[@]}"
来源：http://dali.aibaodan.cn/Article/details/gt2bfmmrnjz.html

[R20] 关联数组（字典）
来源：http://dali.nanxinkj.top/Article/details/gt2iolkaqjd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yuanzhike.top/Article/details/gt2svfjucnv.html

[R21] 字符串长度
来源：http://dali.meibo888.top/Article/details/gt2aixtxrfe.html

echo "${#s}"
来源：http://dali.cashguo.top/Article/details/gt2kzkceizq.html

[R22] 截取子串
来源：http://dali.yangfankeji.com/Article/details/gt2jydiuxat.html

echo "${s:0:5}"
来源：http://dali.ybcxt.top/Article/details/gt2bjkurvdb.html

[R23] 字符串替换
来源：http://dali.gzhubu.top/Article/details/gt2pdmhovja.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yvedp.cn/Article/details/gt2bdiqoxvk.html

[R24] 大小写转换
来源：http://dali.jianghu66.top/Article/details/gt2wmdluvjn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.vqdsnc.cn/Article/details/gt2ymiwnvyc.html

[R25] 去后缀 / 去前缀
来源：http://dali.xziqi.cn/Article/details/gt2wvzxcuye.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hnqzz.top/Article/details/gt2cqqzqdcs.html

[R26] 命令替换
来源：http://dali.shzxlz.cn/Article/details/gt2fiodekzs.html

now=$(date +%F); echo "$now"
来源：http://dali.zhongyouzk.top/Article/details/gt2lxidpamc.html

[R27] 算术展开
来源：http://dali.gaohongyu789.top/Article/details/gt2gptqsssg.html

echo $((1 + 2 * 3))
来源：http://dali.mhx1999.top/Article/details/gt2anxwqojy.html

[R28] 浮点运算
来源：http://dali.cucudq.cn/Article/details/gt2yzdkatvx.html

echo "scale=2; 10/3" | bc
来源：http://dali.pengpengdd.cyou/Article/details/gt2meswrxpj.html

[R29] 定义函数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2skeyeczf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ehwqpu.com/Article/details/gt2hyjedfjm.html

[R30] 函数返回状态码
来源：http://dali.gzhubu.top/Article/details/gt2mxcvoswf.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.jianghu66.top/Article/details/gt2mecdrsrb.html

[R31] 局部变量
来源：http://dali.jinqigufen.top/Article/details/gt2tybihgwt.html

f() { local x=1; echo "$x"; }
来源：http://dali.gotoacloud.top/Article/details/gt2giwjsfxq.html

[R32] 参数个数校验
来源：http://dali.cucudq.cn/Article/details/gt2ctwvdvzc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ehwqpu.com/Article/details/gt2oabtkkcn.html

[R33] 捕获错误并提示行号
来源：http://dali.jianghu66.top/Article/details/gt2azbfoije.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cergpnho.html

[R34] 退出时清理
来源：http://dali.hammf.cn/Article/details/gt2thckunqu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.wangshuangyany.cn/Article/details/gt2bezyktmd.html

[R35] 后台执行并等待
来源：http://dali.zycfv.cn/Article/details/gt2soitrduj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jinqigufen.top/Article/details/gt2kngxczug.html

[R36] 并发执行多个任务
来源：http://dali.gotoacloud.top/Article/details/gt2pncjppzr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hnqzz.top/Article/details/gt2jtbicyvc.html

[R37] 把输出赋给变量
来源：http://dali.hammf.cn/Article/details/gt2cqjnvxmr.html

files=$(ls -1)
来源：http://dali.xinyue.icu/Article/details/gt2eqttykzg.html

[R38] 管道串联
来源：http://dali.guowangkeji.top/Article/details/gt2qkdrhktc.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yvedp.cn/Article/details/gt2pnzmopin.html

[R39] 重定向标准输出与错误
来源：http://dali.xylfe.cn/Article/details/gt2ffxxmneg.html

cmd > out.log 2>&1
来源：http://dali.tanke756.top/Article/details/gt2nybbhgvn.html

[R40] 追加写日志
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rmfoeymn.html

echo "log" >> out.log
来源：http://dali.tianlin.xyz/Article/details/gt2pwobqixd.html

[R41] 丢弃输出
来源：http://dali.zdqjudy.top/Article/details/gt2dqtrbitb.html

cmd >/dev/null 2>&1
来源：http://dali.birdmap.top/Article/details/gt2buxdmuxm.html

[R42] 输入重定向
来源：http://dali.ydzc1.top/Article/details/gt2rcpgyuvy.html

wc -l < a.txt
来源：http://dali.sweek.top/Article/details/gt2sjktgcsj.html

[R43] 按名字查找文件
来源：http://dali.9152youxi.cn/Article/details/gt2svzleqoy.html

find . -name "*.log" -type f
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ccatwvjm.html

[R44] 按修改时间查找
来源：http://dali.ppjwa.cn/Article/details/gt2lnfdpwgt.html

find . -mtime -7 -type f
来源：http://dali.jqgufenzy.top/Article/details/gt2wicrifhx.html

[R45] 批量删除
来源：http://dali.9152youxi.cn/Article/details/gt2uwosscwm.html

find . -name "*.tmp" -delete
来源：http://dali.fengsongda.top/Article/details/gt2svpxhhlm.html

[R46] 递归替换文件内容
来源：http://dali.redwolf501.top/Article/details/gt2bkwgraod.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.fzhhl.top/Article/details/gt2zmxizbkb.html

[R47] sed 单行替换
来源：http://dali.shangyingyoupin.top/Article/details/gt2pbtxeifx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yvedp.cn/Article/details/gt2prarvgzk.html

[R48] awk 取指定列
来源：http://dali.fzhhl.top/Article/details/gt2oammybjg.html

awk '{print $1, $3}' a.txt
来源：http://dali.redwolf501.top/Article/details/gt2rtwomvhr.html

[R49] awk 带条件
来源：http://dali.yuanzhike.top/Article/details/gt2xbmnfffg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zdqjudy.top/Article/details/gt2oxizuqis.html

[R50] awk 求和
来源：http://dali.xziqi.cn/Article/details/gt2gzcdnfth.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mmebjzyn.html

[R51] 排序去重取前几
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ffeluolc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jyoumei.cn/Article/details/gt2ruuhvran.html

[R52] 统计行数
来源：http://dali.hywenlv.cn/Article/details/gt2rxqfgkjo.html

wc -l a.txt
来源：http://dali.hnxiangtu.top/Article/details/gt2ailctefq.html

[R53] 查看文件头与实时尾
来源：http://dali.feifeiyinyue.top/Article/details/gt2bqhrrocs.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yj20258.top/Article/details/gt2whbrsbjn.html

[R54] 比较两个文件
来源：http://dali.guowangkeji.top/Article/details/gt2occgcbwi.html

diff a.txt b.txt
来源：http://dali.cheryme.top/Article/details/gt2nxscddut.html

[R55] 压缩与解压
来源：http://dali.yanxiufei.cn/Article/details/gt2xwecyezv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.chenzaomai.com/Article/details/gt2eebehjrd.html

[R56] 远程拷贝
来源：http://dali.hfpthk.cn/Article/details/gt2lwyufjhi.html

scp file user@host:/path/
来源：http://dali.feifeiyinyue.top/Article/details/gt2hgrmckez.html

[R57] 远程执行命令
来源：http://dali.jiagoushi.top/Article/details/gt2lyhrmbal.html

ssh user@host 'uptime'
来源：http://dali.aizwys.cn/Article/details/gt2szlmqfna.html

[R58] 下载文件
来源：http://dali.yvedp.cn/Article/details/gt2xzbtowjr.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.andypj.xyz/Article/details/gt2yfqwfhtd.html

[R59] 发 POST JSON
来源：http://dali.nanxinkj.top/Article/details/gt2qfcpsrpi.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinqigfzy.top/Article/details/gt2quqjrnhh.html

[R60] 只看 HTTP 状态码
来源：http://dali.xuanzx.com/Article/details/gt2ehubnses.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.guannengcc.top/Article/details/gt2nypphxdl.html

[R61] 磁盘占用
来源：http://dali.fengsongda.top/Article/details/gt2fprsbbjr.html


<!-- 参考信息 -->