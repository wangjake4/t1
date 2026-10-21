代发 wailian999

CREATE INDEX idx_users_email ON users(email);
来源：http://dali.yanxiufei.cn/Article/details/gtrtukffax.html

[Q09] 创建唯一索引
来源：http://dali.zhoulong.xyz/Article/details/gtdkhfxknk.html

CREATE UNIQUE INDEX uq_users_email ON users(email);
来源：http://dali.cdnleiting.top/Article/details/gtbpdgbbug.html

[Q10] 插入单行
来源：http://dali.cdnleiting.top/Article/details/gtjsueywxd.html

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.yangfankeji.com/Article/details/gtzaptnvow.html

[Q11] 一次插入多行
来源：http://dali.feifeiyinyue.top/Article/details/gtgaudatqb.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnxcmthag.html

[Q12] 插入后取自增 ID
来源：http://dali.gaohongyu789.top/Article/details/gtdfvrymzc.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.gzhubu.top/Article/details/gtgupyukpp.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.pycfn.com/Article/details/gtwbismohv.html

[Q13] 忽略重复插入
来源：http://dali.yuanzhike.top/Article/details/gtxdxaoell.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.tian-w.cn/Article/details/gtjhykjmkx.html

[Q14] 存在则更新（upsert）
来源：http://dali.shangyingyoupin.top/Article/details/gtirxlfkvs.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jinqigufen.top/Article/details/gteyfbmgbo.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hongshengwenyu.top/Article/details/gttcshvnmg.html

[Q15] 查询全部
来源：http://dali.nwbrower.top/Article/details/gtwjysvyoq.html

SELECT * FROM users;
来源：http://dali.yj20258.top/Article/details/gtvixwqwbp.html

[Q16] 查询指定列
来源：http://dali.jqgfzy.top/Article/details/gtjvlcfhfn.html

SELECT id, name FROM users;
来源：http://dali.aizwys.cn/Article/details/gtvbpnacml.html

[Q17] 条件查询
来源：http://dali.pengpengdd.cyou/Article/details/gtjghdwzfw.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.gaohongyu789.top/Article/details/gtejwlmuiz.html

[Q18] 模糊匹配
来源：http://dali.zhongyouzk.top/Article/details/gtoefnywja.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cashguo.top/Article/details/gtwixiucgi.html

[Q19] 范围查询
来源：http://dali.shangyingyoupin.top/Article/details/gtezkwlcph.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yuanzhike.top/Article/details/gtngakhksi.html

[Q20] IN 列表
来源：http://dali.xylfe.cn/Article/details/gtuqbzlgqw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxncpcwod.html

[Q21] 空值判断
来源：http://dali.guannengcc.top/Article/details/gtnavrdcbk.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.nanxuanxn.top/Article/details/gtmdtsahpr.html

[Q22] 排序
来源：http://dali.cdnleiting.top/Article/details/gtjmcluqmu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhiwuduotai.top/Article/details/gtlkbbscpj.html

[Q23] 分页
来源：http://dali.9152youxi.cn/Article/details/gtirbyrcps.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.birdmap.top/Article/details/gtcodklngk.html

[Q24] 去重
来源：http://dali.ydzc1.top/Article/details/gtzzyzpejx.html

SELECT DISTINCT city FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtengpyphr.html

[Q25] 只取前 N 条
来源：http://dali.hnxiangtu.top/Article/details/gtataogmya.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.cashguo.top/Article/details/gtbiftbsan.html

[Q26] 计数
来源：http://dali.mhx1999.top/Article/details/gtepqniulf.html

SELECT COUNT(*) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtpkgawayz.html

[Q27] 条件计数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvewdnpmp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtquptaofp.html

[Q28] 求和与平均
来源：http://dali.redwolf501.top/Article/details/gtoszohehy.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gtdfmctpuz.html

[Q29] 最大最小值
来源：http://dali.ivvv.top/Article/details/gtxqcabbpf.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtqrrugkzt.html

[Q30] 分组统计
来源：http://dali.hysaishi.cn/Article/details/gtzwdtlodr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.haohaochexian.top/Article/details/gtgrahuwsz.html

[Q31] 分组后过滤
来源：http://dali.316326.xyz/Article/details/gtjjzynfct.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yongpay.top/Article/details/gtrunrnmun.html

[Q32] 分组拼接字符串
来源：http://dali.gogol.net.cn/Article/details/gttrfvzybh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.chenlongwang.top/Article/details/gtwymhklvu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zdqjudy.top/Article/details/gtjiizcwsc.html

[Q33] 多列分组
来源：http://dali.chenjidiqi.icu/Article/details/gtgcoqzmdn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.feifeiyinyue.top/Article/details/gtzipcvsoi.html

[Q34] 每组取第一条
来源：http://dali.sxryk.cn/Article/details/gthfspmwvz.html

SELECT * FROM (
来源：http://dali.guannengcc.top/Article/details/gtsuskkruu.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yonumen.top/Article/details/gtfjfbycac.html

) t WHERE rn = 1;
来源：http://dali.svipenyu.cn/Article/details/gtrizxjijq.html

[Q35] 内连接
来源：http://dali.tianlin.xyz/Article/details/gtkmrhmpva.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.svipenyu.cn/Article/details/gtpysxmvxd.html

[Q36] 左连接
来源：http://dali.shuidangran.top/Article/details/gtwmoxqpfi.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.smart0.xyz/Article/details/gttlimhzls.html

[Q37] 右连接
来源：http://dali.sysykeji.top/Article/details/gtxherpqik.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hongshengwenyu.top/Article/details/gtzounlqtt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.chenjidiqi.icu/Article/details/gtycgzarer.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.dianchejie.cn/Article/details/gttcvyqtby.html

[Q39] 自连接（查上下级）
来源：http://dali.yueranfly.top/Article/details/gtxpltobuw.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.quarkkingdee.top/Article/details/gtckvprrua.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jyoumei.cn/Article/details/gtokzxfnhc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.tanke756.top/Article/details/gtvifabfla.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.pengpengdd.cyou/Article/details/gtckbxwbmc.html

[Q41] 多表连接
来源：http://dali.havefunace.top/Article/details/gtiedwrybw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yongpay.top/Article/details/gtbaxvfzvn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.havefunace.top/Article/details/gtbkpxlaiu.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.meibo888.top/Article/details/gtovgxglli.html

[Q42] 连接条件附加过滤
来源：http://dali.xziqi.cn/Article/details/gttgjnfxyt.html

SELECT u.name, o.amount FROM users u
来源：http://dali.birdmap.top/Article/details/gtemcewjgl.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.chenlongwang.top/Article/details/gtszomxpwy.html

[Q43] 标量子查询
来源：http://dali.zhengqikj.top/Article/details/gtzjmhhbkg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.smart0.xyz/Article/details/gtojhoqiem.html

[Q44] IN 子查询
来源：http://dali.cucudq.cn/Article/details/gttbbahgso.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cucudq.cn/Article/details/gtlztndmyv.html

[Q45] EXISTS 判断存在
来源：http://dali.wangshuangyany.cn/Article/details/gtxhlhkfjd.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj202588.top/Article/details/gtssjoievg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.316326.xyz/Article/details/gtzmdsywbi.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jyoumei.cn/Article/details/gtwqtisezh.html

[Q47] 与平均值比较
来源：http://dali.vqdsnc.cn/Article/details/gtditemysz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhixingplan.top/Article/details/gtrzvwulig.html

[Q48] CTE 公用表表达式
来源：http://dali.jyoumei.cn/Article/details/gtrvvpxurw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmtexmalj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yanxiufei.cn/Article/details/gtipgegcxl.html

[Q49] 更新单行
来源：http://dali.cucudq.cn/Article/details/gtccsfhlxc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.daria6918.cn/Article/details/gtwxepzyxh.html

[Q50] 批量更新
来源：http://dali.birdmap.top/Article/details/gtjzepipri.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.dianchejie.cn/Article/details/gtehscwncp.html

[Q51] 用子查询更新
来源：http://dali.hfpthk.cn/Article/details/gtqfsomvfa.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xinyue.icu/Article/details/gtyoxntnog.html

[Q52] 删除指定行
来源：http://dali.wangdashe.top/Article/details/gthztcydpv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.vqdsnc.cn/Article/details/gtkrbqhuie.html

[Q53] 按条件删除
来源：http://dali.guowangkeji.top/Article/details/gtsdjzumsg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtviglplpq.html

[Q54] 清空表
来源：http://dali.yangfankeji.com/Article/details/gtjhubrvdn.html

TRUNCATE TABLE logs;
来源：http://dali.shuidangran.top/Article/details/gtoztslgzn.html

[Q55] 排名（并列占位）
来源：http://dali.bjfxy.top/Article/details/gtefnasoai.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cqqwz.cn/Article/details/gtkeovnyiw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.andypj.xyz/Article/details/gtnqfyeacl.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hnqzz.top/Article/details/gtdjbihjuy.html

[Q57] 行号
来源：http://dali.dashuyun.cn/Article/details/gtlqzjafzk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtmhmpsisy.html

[Q58] 累计求和
来源：http://dali.yuxming.cn/Article/details/gtjqpfsayk.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtzlxpwhqr.html

[Q59] 分组内累计
来源：http://dali.sysykeji.top/Article/details/gtykqwhzwm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.birdmap.top/Article/details/gtntriqzhy.html

[Q60] 取上一行 / 下一行
来源：http://dali.kuanghao11.cn/Article/details/gttufrqnne.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shangyingyoupin.top/Article/details/gtbublpfdj.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtpxfgzsfa.html

[Q61] 移动平均
来源：http://dali.fengsongda.top/Article/details/gtllwevzal.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gtjsfuuceb.html

[Q62] 分组占比
来源：http://dali.daxiang520.top/Article/details/gtcgfvvnnv.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenzaomai.com/Article/details/gtqbryakoz.html

[Q63] 开启事务
来源：http://dali.jqgufenzy.top/Article/details/gtlhcgyiei.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yj202588.top/Article/details/gtmecvvbrp.html

[Q64] 提交事务
来源：http://dali.yongpay.top/Article/details/gtkynqkaov.html

COMMIT;
来源：http://dali.fzhhl.top/Article/details/gtcwdruzwx.html

[Q65] 回滚事务
来源：http://dali.zhixingplan.top/Article/details/gtjafyijgp.html

ROLLBACK;
来源：http://dali.tanke756.top/Article/details/gtosdvdlwu.html

[Q66] 行锁查询
来源：http://dali.hnxiangtu.top/Article/details/gtibbvtcwy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xziqi.cn/Article/details/gtlfamtbme.html

[Q67] 设置隔离级别
来源：http://dali.andypj.xyz/Article/details/gtdmfvfrhj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ehwqpu.com/Article/details/gtiiwuacyg.html

[Q68] 保存点
来源：http://dali.wangshuangyany.cn/Article/details/gtcjgmgkow.html

SAVEPOINT sp1;
来源：http://dali.shanyushiyangtech.top/Article/details/gttbhdabse.html

ROLLBACK TO sp1;
来源：http://dali.hongshengwenyu.top/Article/details/gtkzyuvuba.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gtmcayefyc.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gaohongyu789.top/Article/details/gtcveijadu.html

[Q70] 更新统计信息
来源：http://dali.jqgfzy.top/Article/details/gtylbyjwsb.html

ANALYZE TABLE users;
来源：http://dali.chenlongwang.top/Article/details/gtioynijtj.html

[Q71] 查看建表语句
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbdbxvwkc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hnxiangtu.top/Article/details/gtffckkndd.html

[Q72] 查看索引
来源：http://dali.jinghuilouyu.cn/Article/details/gtmrmezvzg.html

SHOW INDEX FROM users;
来源：http://dali.yueranfly.top/Article/details/gtgbschuge.html

[Q73] 查看表状态
来源：http://dali.kuanghao11.cn/Article/details/gtoineytek.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.snrcjt.cn/Article/details/gtitxhgyac.html

[Q74] 强制使用索引
来源：http://dali.yanxiufei.cn/Article/details/gtaxzbgncx.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvibdsmop.html

[Q75] 日期格式化
来源：http://dali.jinqigfzy.top/Article/details/gtezbbpngx.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gttqasansx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sufxvd.cn/Article/details/gtlggjmhkd.html

[Q76] 按天统计
来源：http://dali.316326.xyz/Article/details/gtvadioeaa.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbakutulf.html

[Q77] 时间加减
来源：http://dali.xylfe.cn/Article/details/gtjbluteiq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jyoumei.cn/Article/details/gtnezudjxw.html

[Q78] 当前时间
来源：http://dali.birdmap.top/Article/details/gtnivjplti.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.daxiang520.top/Article/details/gttxnzpebc.html

[Q79] 字符串拼接
来源：http://dali.jqgufenzy.top/Article/details/gtsgmsxrxb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.xinyue.icu/Article/details/gtuhdkdhhc.html

[Q80] 字符串截取
来源：http://dali.zhongyouzk.top/Article/details/gtpyrjgoqo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yj20258.top/Article/details/gtdkvechyj.html

[Q81] 字符串替换
来源：http://dali.guowangkeji.top/Article/details/gtlxrjdcgd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.pycfn.com/Article/details/gtxfzhdnaw.html

[Q82] 字符长度与字节长度
来源：http://dali.jlsjyb.cn/Article/details/gtinaivobl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gtyzbdwsqq.html

[Q83] 大小写转换
来源：http://dali.ybcxt.top/Article/details/gtvxzyvlzl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gttjqmobua.html

[Q84] 去除首尾空格
来源：http://dali.cashguo.top/Article/details/gtojafprxx.html

SELECT TRIM(name) FROM users;
来源：http://dali.xinyue.icu/Article/details/gtdmultuqc.html

[Q85] 数值取整
来源：http://dali.sweek.top/Article/details/gthoawkrzv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.daria6918.cn/Article/details/gthkqkjsct.html

[Q86] 读取 JSON 字段
来源：http://dali.jianghu66.top/Article/details/gtsslgtfck.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhijiandao.cn/Article/details/gtlaglzzdb.html

[Q87] JSON 字段做条件
来源：http://dali.xylfe.cn/Article/details/gtyndconsw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.daria6918.cn/Article/details/gtbnkimfpc.html

[Q88] 行转列（条件聚合）
来源：http://dali.tian-w.cn/Article/details/gtosmjljqx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zdqjudy.top/Article/details/gthpzvrfib.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtzzoltdpb.html

[Q89] 判断表是否存在
来源：http://dali.zhijiandao.cn/Article/details/gtannbgzdm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.c1oappe.top/Article/details/gtoxdgdler.html

[Q90] 生成序号列
来源：http://dali.tanke756.top/Article/details/gtcmsnqenn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ybcxt.top/Article/details/gtjqqycmwa.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtivfcdlzy.html

R. Bash 专题
来源：http://dali.chenlongwang.top/Article/details/gtrnblfync.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtjskzzoxf.html

[R01] shebang 与严格模式
来源：http://dali.birdmap.top/Article/details/gtpimvvdns.html

#!/usr/bin/env bash
来源：http://dali.9152youxi.cn/Article/details/gtgjfgqmxh.html

set -euo pipefail
来源：http://dali.birdmap.top/Article/details/gtohhmiuaw.html

[R02] 变量赋值与使用
来源：http://dali.shanyushiyangkeji.top/Article/details/gthsrajcvf.html

name="Tom"; echo "$name"
来源：http://dali.quarkkingdee.top/Article/details/gtvdbxilqm.html

[R03] 只读变量
来源：http://dali.hnqzz.top/Article/details/gtoocagjcn.html

readonly PI=3.14
来源：http://dali.sysykeji.top/Article/details/gtxartshyo.html

[R04] 位置参数
来源：http://dali.chenjidiqi.icu/Article/details/gtsnkzzchk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gotoacloud.top/Article/details/gtvzqzfufg.html

[R05] 参数默认值
来源：http://dali.zhongyouzk.top/Article/details/gttgrqindz.html

name="${1:-default}"
来源：http://dali.fzhhl.top/Article/details/gtseqkfcdu.html

[R06] 判断命令是否存在
来源：http://dali.meibo888.top/Article/details/gtqnedcvyv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yvedp.cn/Article/details/gtvwasiyfs.html

[R07] if 判断文件
来源：http://dali.hfpthk.cn/Article/details/gtmqxeebtp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.dashuyun.cn/Article/details/gtdxvtulup.html

[R08] 数值比较
来源：http://dali.xuanzx.com/Article/details/gtnokqchwf.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jinqigfzy.top/Article/details/gtnqtlvrqc.html

[R09] 字符串比较
来源：http://dali.haohaochexian.top/Article/details/gtpgrmgree.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.guannengcc.top/Article/details/gtpjfbmbub.html

[R10] 正则匹配
来源：http://dali.shanyushiyangtech.top/Article/details/gtwvsrzxfu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hnxiangtu.top/Article/details/gtzzaokdns.html

[R11] case 多分支
来源：http://dali.chenjidiqi.icu/Article/details/gtdoabcmyq.html

case "$1" in
来源：http://dali.yueranfly.top/Article/details/gtximcwsoj.html

start) echo "启动" ;;
来源：http://dali.tianlin.xyz/Article/details/gtghqpdcar.html

stop)  echo "停止" ;;
来源：http://dali.cdnleiting.top/Article/details/gtwcomqlno.html

*)     echo "未知命令" ;;
来源：http://dali.aizwys.cn/Article/details/gtigspxvuh.html

esac
来源：http://dali.shuidangran.top/Article/details/gtwihtqpbn.html

[R12] for 遍历文件
来源：http://dali.yvedp.cn/Article/details/gtiiiwyarq.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ehwqpu.com/Article/details/gtjbkirvil.html

[R13] for 计数循环
来源：http://dali.tianlin.xyz/Article/details/gtwtfhmvfw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtefwfrfqb.html

[R14] C 风格 for
来源：http://dali.ppjwa.cn/Article/details/gtntnxfvqn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.xziqi.cn/Article/details/gtzwhibzhx.html

[R15] while 逐行读文件
来源：http://dali.dianchejie.cn/Article/details/gtfwpogauj.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jianghu66.top/Article/details/gtgidqduha.html

[R16] until 等待条件
来源：http://dali.xinyue.icu/Article/details/gtbrdobzpk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jianghu66.top/Article/details/gtcjgelbjv.html

[R17] 数组定义与取值
来源：http://dali.smart0.xyz/Article/details/gtngehvjht.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.svipenyu.cn/Article/details/gtgjuituqg.html

[R18] 遍历数组
来源：http://dali.wangdashe.top/Article/details/gtsnobjein.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.redwolf501.top/Article/details/gtsmbaigih.html

[R19] 数组长度
来源：http://dali.wangshuangyany.cn/Article/details/gtqruevjfj.html

echo "${#arr[@]}"
来源：http://dali.jiagoushi.top/Article/details/gtohfikwes.html

[R20] 关联数组（字典）
来源：http://dali.birdmap.top/Article/details/gtfxyfaxib.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xuanzx.com/Article/details/gtguguydgo.html

[R21] 字符串长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtevbdsxjp.html

echo "${#s}"
来源：http://dali.cucudq.cn/Article/details/gtlagwfscm.html

[R22] 截取子串
来源：http://dali.havefunace.top/Article/details/gtfmvkciji.html

echo "${s:0:5}"
来源：http://dali.zhijiandao.cn/Article/details/gtcqnbyloy.html

[R23] 字符串替换
来源：http://dali.guowangkeji.top/Article/details/gtqnuywomw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.guowangkeji.top/Article/details/gtzwadbhjy.html

[R24] 大小写转换
来源：http://dali.zhoulong.xyz/Article/details/gteyxjjfnn.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.9152youxi.cn/Article/details/gtvyetbuwi.html

[R25] 去后缀 / 去前缀
来源：http://dali.yj20258888.top/Article/details/gtcyrzpexe.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.zhixingplan.top/Article/details/gtvbdyndfl.html

[R26] 命令替换
来源：http://dali.daxiang520.top/Article/details/gtdakxztqd.html

now=$(date +%F); echo "$now"
来源：http://dali.daxiang520.top/Article/details/gthoewsnfw.html

[R27] 算术展开
来源：http://dali.hfpthk.cn/Article/details/gtadzhtkny.html

echo $((1 + 2 * 3))
来源：http://dali.ywan-chungtsiang.top/Article/details/gtaczwlnwd.html

[R28] 浮点运算
来源：http://dali.gotoacloud.top/Article/details/gtzvlwytte.html

echo "scale=2; 10/3" | bc
来源：http://dali.shuidangran.top/Article/details/gtfiwhyppb.html

[R29] 定义函数
来源：http://dali.jlsjyb.cn/Article/details/gtiegpbbbk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtvfdhfxpn.html

[R30] 函数返回状态码
来源：http://dali.meibo888.top/Article/details/gtlfyjfqdy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhongyouzk.top/Article/details/gtuoiteqaa.html

[R31] 局部变量
来源：http://dali.hfpthk.cn/Article/details/gtzgnwajui.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhixingplan.top/Article/details/gtzmqtufwj.html

[R32] 参数个数校验
来源：http://dali.kuanghao11.cn/Article/details/gtojfduakw.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.kuanghao11.cn/Article/details/gtgjdjmlpo.html

[R33] 捕获错误并提示行号
来源：http://dali.yanxiufei.cn/Article/details/gtqojnkdyp.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.bjfxy.top/Article/details/gthyvjgcpe.html

[R34] 退出时清理
来源：http://dali.shanyushiyangtech.top/Article/details/gtmsplkagb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.pengpengdd.cyou/Article/details/gtxgwwouta.html

[R35] 后台执行并等待
来源：http://dali.pengpengdd.cyou/Article/details/gthnuujagg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jianghu66.top/Article/details/gttkupnyfc.html

[R36] 并发执行多个任务
来源：http://dali.zycfv.cn/Article/details/gtdzuinzzs.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.tanke756.top/Article/details/gtccfneksw.html

[R37] 把输出赋给变量
来源：http://dali.cqqwz.cn/Article/details/gtssjgqhkw.html

files=$(ls -1)
来源：http://dali.zhoulong.xyz/Article/details/gthmsvykpv.html

[R38] 管道串联
来源：http://dali.hfpthk.cn/Article/details/gtejuovdhl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hnxiangtu.top/Article/details/gtgqeeacgu.html

[R39] 重定向标准输出与错误
来源：http://dali.sweek.top/Article/details/gtflwermsg.html

cmd > out.log 2>&1
来源：http://dali.guowangkeji.top/Article/details/gtyiarjbui.html

[R40] 追加写日志
来源：http://dali.aibaodan.cn/Article/details/gtcyaysokv.html

echo "log" >> out.log
来源：http://dali.bjfxy.top/Article/details/gtpvbdmbto.html

[R41] 丢弃输出
来源：http://dali.kuanghao11.cn/Article/details/gtqddiqgjq.html

cmd >/dev/null 2>&1
来源：http://dali.guannengcc.top/Article/details/gtnlchlejk.html

[R42] 输入重定向
来源：http://dali.nwbrower.top/Article/details/gtapaxdjse.html

wc -l < a.txt
来源：http://dali.jianghu66.top/Article/details/gtevopyxfp.html

[R43] 按名字查找文件
来源：http://dali.yanxiufei.cn/Article/details/gteuebhrgq.html

find . -name "*.log" -type f
来源：http://dali.quarkkingdee.top/Article/details/gtioftzykz.html

[R44] 按修改时间查找
来源：http://dali.shanyushiyangtech.top/Article/details/gtgsoijzbl.html

find . -mtime -7 -type f
来源：http://dali.jyoumei.cn/Article/details/gtwplffurw.html

[R45] 批量删除
来源：http://dali.gzhubu.top/Article/details/gtiqrxraep.html

find . -name "*.tmp" -delete
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwghpsgbv.html

[R46] 递归替换文件内容
来源：http://dali.shzxlz.cn/Article/details/gtcbrlbrgr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yangfankeji.com/Article/details/gtphrooxxx.html

[R47] sed 单行替换
来源：http://dali.hfpthk.cn/Article/details/gtqyujzszq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.0kj1m.cn/Article/details/gtpioqmjbz.html

[R48] awk 取指定列
来源：http://dali.gzhubu.top/Article/details/gtforivzgn.html

awk '{print $1, $3}' a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtdkjkvjnv.html

[R49] awk 带条件
来源：http://dali.sysykeji.top/Article/details/gtzzofrjhl.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hfpthk.cn/Article/details/gtrlkrsqzb.html

[R50] awk 求和
来源：http://dali.ehwqpu.com/Article/details/gtmpqrvajv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.cucudq.cn/Article/details/gtfmlochqr.html

[R51] 排序去重取前几
来源：http://dali.ppjwa.cn/Article/details/gtnockfhes.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shanyushiyangkeji.top/Article/details/gtomtiksfx.html

[R52] 统计行数
来源：http://dali.jqgfzy.top/Article/details/gtslcjmnnu.html

wc -l a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtksztikmi.html

[R53] 查看文件头与实时尾
来源：http://dali.ydzc1.top/Article/details/gtdklclsjs.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.smart0.xyz/Article/details/gtbyycghre.html

[R54] 比较两个文件
来源：http://dali.ybcxt.top/Article/details/gtkwqlxuph.html

diff a.txt b.txt
来源：http://dali.xinyue.icu/Article/details/gtlkcfhbaz.html

[R55] 压缩与解压
来源：http://dali.feifeiyinyue.top/Article/details/gtfltqndkr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyswlypkv.html

[R56] 远程拷贝
来源：http://dali.nanxuanxn.top/Article/details/gteabowqie.html

scp file user@host:/path/
来源：http://dali.yj202588.top/Article/details/gtsrlugzqv.html

[R57] 远程执行命令
来源：http://dali.shangyingyoupin.top/Article/details/gtznkafqjg.html


<!-- 参考信息 -->