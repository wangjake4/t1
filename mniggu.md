代发 wailian999

INSERT INTO users (name, email) VALUES ('Tom', 'tom@a.com');
来源：http://dali.aibaodan.cn/Article/details/gt2mcfjpiit.html

[Q11] 一次插入多行
来源：http://dali.hnxiangtu.top/Article/details/gt2bgeflpxs.html

INSERT INTO users (name, email) VALUES ('A', 'a@a.com'), ('B', 'b@a.com');
来源：http://dali.c1oappe.top/Article/details/gt2imwykltc.html

[Q12] 插入后取自增 ID
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qvolbohq.html

INSERT INTO users (name) VALUES ('C');
来源：http://dali.zhiwuduotai.top/Article/details/gt2dmhhspdi.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.yvedp.cn/Article/details/gt2hzbbumbt.html

[Q13] 忽略重复插入
来源：http://dali.haohaochexian.top/Article/details/gt2bxshfzxe.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.fengsongda.top/Article/details/gt2elxyrhpm.html

[Q14] 存在则更新（upsert）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2rhfafgcw.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yuxming.cn/Article/details/gt2kmvyccrf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhiwuduotai.top/Article/details/gt2sbwruhhw.html

[Q15] 查询全部
来源：http://dali.xinyue.icu/Article/details/gt2evyfoggn.html

SELECT * FROM users;
来源：http://dali.dashuyun.cn/Article/details/gt2gyiwcppt.html

[Q16] 查询指定列
来源：http://dali.sweek.top/Article/details/gt2fhzoeoqv.html

SELECT id, name FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2oraekyzd.html

[Q17] 条件查询
来源：http://dali.316326.xyz/Article/details/gt2yxkqrubm.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.snrcjt.cn/Article/details/gt2pzujotir.html

[Q18] 模糊匹配
来源：http://dali.sufxvd.cn/Article/details/gt2psctyzmz.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.havefunace.top/Article/details/gt2hubbmqmb.html

[Q19] 范围查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2qesxwthp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.nanxinkj.top/Article/details/gt2ipvrewce.html

[Q20] IN 列表
来源：http://dali.guannengcc.top/Article/details/gt2sysegzxj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.tanke756.top/Article/details/gt2pawppvrh.html

[Q21] 空值判断
来源：http://dali.yongpay.top/Article/details/gt2iflnwyzb.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hongshengwenyu.top/Article/details/gt2mqcpnrnp.html

[Q22] 排序
来源：http://dali.fzhhl.top/Article/details/gt2fiijkjio.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.kuanghao11.cn/Article/details/gt2dclqwjtu.html

[Q23] 分页
来源：http://dali.hnxiangtu.top/Article/details/gt2mggvjaok.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zdqjudy.top/Article/details/gt2ivgexfrz.html

[Q24] 去重
来源：http://dali.smart0.xyz/Article/details/gt2hbiccjbr.html

SELECT DISTINCT city FROM users;
来源：http://dali.pycfn.com/Article/details/gt2rkiezsor.html

[Q25] 只取前 N 条
来源：http://dali.quarkkingdee.top/Article/details/gt2mknlxzud.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhengqikj.top/Article/details/gt2gpzlonsc.html

[Q26] 计数
来源：http://dali.fzhhl.top/Article/details/gt2wilwsjhq.html

SELECT COUNT(*) FROM users;
来源：http://dali.yj202588.top/Article/details/gt2fdsdfxbl.html

[Q27] 条件计数
来源：http://dali.gogol.net.cn/Article/details/gt2swnqbhgw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.chenlongwang.top/Article/details/gt2atwptkaz.html

[Q28] 求和与平均
来源：http://dali.pycfn.com/Article/details/gt2gahpcdsv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gt2sydmvuqs.html

[Q29] 最大最小值
来源：http://dali.nwbrower.top/Article/details/gt2wlqfbpic.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.redwolf501.top/Article/details/gt2awnvinlc.html

[Q30] 分组统计
来源：http://dali.guannengcc.top/Article/details/gt2bmmcuooy.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.svipenyu.cn/Article/details/gt2sksmduen.html

[Q31] 分组后过滤
来源：http://dali.smart0.xyz/Article/details/gt2khssqiqk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.svipenyu.cn/Article/details/gt2userfojb.html

[Q32] 分组拼接字符串
来源：http://dali.hongshengwenyu.top/Article/details/gt2hymdgsjj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xziqi.cn/Article/details/gt2ppdkznmt.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.sufxvd.cn/Article/details/gt2orjwbljq.html

[Q33] 多列分组
来源：http://dali.chenjidiqi.icu/Article/details/gt2clshkmty.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hongshengwenyu.top/Article/details/gt2fxvhreqq.html

[Q34] 每组取第一条
来源：http://dali.ppjwa.cn/Article/details/gt2maqhlzpt.html

SELECT * FROM (
来源：http://dali.dianchejie.cn/Article/details/gt2swurqtxc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yangfankeji.com/Article/details/gt2dxskmuee.html

) t WHERE rn = 1;
来源：http://dali.cqqwz.cn/Article/details/gt2awoxdplu.html

[Q35] 内连接
来源：http://dali.0kj1m.cn/Article/details/gt2ugwiihzn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yongpay.top/Article/details/gt2fxdafdqe.html

[Q36] 左连接
来源：http://dali.jqgufenzy.top/Article/details/gt2wzdeumvo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenlongwang.top/Article/details/gt2ctwexbvh.html

[Q37] 右连接
来源：http://dali.nanxuanxn.top/Article/details/gt2vqdfmzlc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cucudq.cn/Article/details/gt2vpjeifuj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hywenlv.cn/Article/details/gt2asikvilt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shangyingyoupin.top/Article/details/gt2bxzfnxqb.html

[Q39] 自连接（查上下级）
来源：http://dali.yongpay.top/Article/details/gt2eovfwgwo.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hfpthk.cn/Article/details/gt2hwfycfmu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.chenzaomai.com/Article/details/gt2zqelvskd.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gaohongyu789.top/Article/details/gt2hwqiumbe.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.ybcxt.top/Article/details/gt2ioiflnvm.html

[Q41] 多表连接
来源：http://dali.zhijiandao.cn/Article/details/gt2pqdtwzrh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2pqslqcov.html

JOIN users u ON u.id = o.user_id
来源：http://dali.nanxuanxn.top/Article/details/gt2dxwxkboo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bwfvscgn.html

[Q42] 连接条件附加过滤
来源：http://dali.hnxiangtu.top/Article/details/gt2uyimpodr.html

SELECT u.name, o.amount FROM users u
来源：http://dali.birdmap.top/Article/details/gt2hxwhhytj.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jianghu66.top/Article/details/gt2bbdmvtyj.html

[Q43] 标量子查询
来源：http://dali.yanxiufei.cn/Article/details/gt2aspfnspb.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jianghu66.top/Article/details/gt2nfuyyhzn.html

[Q44] IN 子查询
来源：http://dali.jinqigfzy.top/Article/details/gt2pfsrtyho.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.aibaodan.cn/Article/details/gt2llupmdyg.html

[Q45] EXISTS 判断存在
来源：http://dali.zhoulong.xyz/Article/details/gt2pehgzfom.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuanzhike.top/Article/details/gt2ewsrwlrj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shangyingyoupin.top/Article/details/gt2pfocrgja.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gogol.net.cn/Article/details/gt2clwjansq.html

[Q47] 与平均值比较
来源：http://dali.chenzaomai.com/Article/details/gt2oarvnbcu.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.xylfe.cn/Article/details/gt2xcrrpzxu.html

[Q48] CTE 公用表表达式
来源：http://dali.xylfe.cn/Article/details/gt2zepxaokx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.iojbl.cn/Article/details/gt2uzahuwiu.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhixingplan.top/Article/details/gt2lymifmbd.html

[Q49] 更新单行
来源：http://dali.cheryme.top/Article/details/gt2yrubschx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.havefunace.top/Article/details/gt2onhqflju.html

[Q50] 批量更新
来源：http://dali.zhengqikj.top/Article/details/gt2svxzpdvx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.feifeiyinyue.top/Article/details/gt2oftsfuoq.html

[Q51] 用子查询更新
来源：http://dali.gzhubu.top/Article/details/gt2pnqukptb.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhoulong.xyz/Article/details/gt2tixyznjq.html

[Q52] 删除指定行
来源：http://dali.cheryme.top/Article/details/gt2rlorhfjj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.quarkkingdee.top/Article/details/gt2vyxodgwl.html

[Q53] 按条件删除
来源：http://dali.wangshuangyany.cn/Article/details/gt2wymgbaoi.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gzhubu.top/Article/details/gt2evxonsoi.html

[Q54] 清空表
来源：http://dali.gogol.net.cn/Article/details/gt2eujxmkds.html

TRUNCATE TABLE logs;
来源：http://dali.zhiwuduotai.top/Article/details/gt2qtwpygpi.html

[Q55] 排名（并列占位）
来源：http://dali.bjfxy.top/Article/details/gt2meehxsga.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gaohongyu789.top/Article/details/gt2meytsyvn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.gaohongyu789.top/Article/details/gt2uqimhnlr.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jqgufenzy.top/Article/details/gt2nkwzxdzv.html

[Q57] 行号
来源：http://dali.ppjwa.cn/Article/details/gt2trwxliqo.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2rauwmbri.html

[Q58] 累计求和
来源：http://dali.ivvv.top/Article/details/gt2aafnlynm.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yongpay.top/Article/details/gt2cpfpaqdg.html

[Q59] 分组内累计
来源：http://dali.shuidangran.top/Article/details/gt2vpwgzkjn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.shangyingyoupin.top/Article/details/gt2xjcvmewc.html

[Q60] 取上一行 / 下一行
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lkprrefn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.dianchejie.cn/Article/details/gt2hdprzyzg.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yongpay.top/Article/details/gt2ucnmqmqc.html

[Q61] 移动平均
来源：http://dali.jqgufenzy.top/Article/details/gt2akxatydx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yongpay.top/Article/details/gt2lgdodoil.html

[Q62] 分组占比
来源：http://dali.aibaodan.cn/Article/details/gt2vhnflxst.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gt2oluhyagp.html

[Q63] 开启事务
来源：http://dali.daxiang520.top/Article/details/gt2brzolukw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhoulong.xyz/Article/details/gt2qquyojif.html

[Q64] 提交事务
来源：http://dali.xylfe.cn/Article/details/gt2lvpnwdqg.html

COMMIT;
来源：http://dali.yj20258.top/Article/details/gt2urwutvfj.html

[Q65] 回滚事务
来源：http://dali.gaohongyu789.top/Article/details/gt2ogsrjdfi.html

ROLLBACK;
来源：http://dali.guowangkeji.top/Article/details/gt2xijdvvbs.html

[Q66] 行锁查询
来源：http://dali.0kj1m.cn/Article/details/gt2velemqcv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.kuanghao11.cn/Article/details/gt2ulnhcrtw.html

[Q67] 设置隔离级别
来源：http://dali.hongshengwenyu.top/Article/details/gt2jorjgzhq.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yvedp.cn/Article/details/gt2snkageql.html

[Q68] 保存点
来源：http://dali.wangdashe.top/Article/details/gt2lyojrkrz.html

SAVEPOINT sp1;
来源：http://dali.xylfe.cn/Article/details/gt2qxlosxwx.html

ROLLBACK TO sp1;
来源：http://dali.aizwys.cn/Article/details/gt2ltayiaps.html

[Q69] 查看执行计划
来源：http://dali.tian-w.cn/Article/details/gt2civwokvs.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhiwuduotai.top/Article/details/gt2vksayzdb.html

[Q70] 更新统计信息
来源：http://dali.ydzc1.top/Article/details/gt2luqwxzym.html

ANALYZE TABLE users;
来源：http://dali.hywenlv.cn/Article/details/gt2ktskfmcm.html

[Q71] 查看建表语句
来源：http://dali.dashuyun.cn/Article/details/gt2uzdzmuxn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ybcxt.top/Article/details/gt2kvunfran.html

[Q72] 查看索引
来源：http://dali.jiagoushi.top/Article/details/gt2haxnavyn.html

SHOW INDEX FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2raawmpqr.html

[Q73] 查看表状态
来源：http://dali.vqdsnc.cn/Article/details/gt2ydvksmbj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhongyouzk.top/Article/details/gt2ilkpqdfw.html

[Q74] 强制使用索引
来源：http://dali.fengsongda.top/Article/details/gt2ttcdpwxi.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.cucudq.cn/Article/details/gt2gzsqyycr.html

[Q75] 日期格式化
来源：http://dali.hongshengwenyu.top/Article/details/gt2sgkscowq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2qymidipo.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.c1oappe.top/Article/details/gt2egzmzsnv.html

[Q76] 按天统计
来源：http://dali.yvedp.cn/Article/details/gt2pfbjjdxu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.andypj.xyz/Article/details/gt2cagawtes.html

[Q77] 时间加减
来源：http://dali.zycfv.cn/Article/details/gt2wjtdcvui.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nztchccw.html

[Q78] 当前时间
来源：http://dali.c1oappe.top/Article/details/gt2ohfourac.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.316326.xyz/Article/details/gt2lqbootjl.html

[Q79] 字符串拼接
来源：http://dali.nwbrower.top/Article/details/gt2dtmxjgya.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.tianlin.xyz/Article/details/gt2krgcljwy.html

[Q80] 字符串截取
来源：http://dali.c1oappe.top/Article/details/gt2bwlgloag.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.andypj.xyz/Article/details/gt2mmnrsuiy.html

[Q81] 字符串替换
来源：http://dali.aizwys.cn/Article/details/gt2neyygjvc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hammf.cn/Article/details/gt2geejxyrr.html

[Q82] 字符长度与字节长度
来源：http://dali.andypj.xyz/Article/details/gt2lbdrjwal.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gt2xldbezhu.html

[Q83] 大小写转换
来源：http://dali.jiagoushi.top/Article/details/gt2uizefgck.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sweek.top/Article/details/gt2gcxpttji.html

[Q84] 去除首尾空格
来源：http://dali.wangdashe.top/Article/details/gt2ovqwuoxr.html

SELECT TRIM(name) FROM users;
来源：http://dali.9152youxi.cn/Article/details/gt2btszncpf.html

[Q85] 数值取整
来源：http://dali.yvedp.cn/Article/details/gt2hhqgtqip.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.chenjidiqi.icu/Article/details/gt2kvmusuxd.html

[Q86] 读取 JSON 字段
来源：http://dali.daria6918.cn/Article/details/gt2mbhesydx.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shuidangran.top/Article/details/gt2lmezhhgl.html

[Q87] JSON 字段做条件
来源：http://dali.aibaodan.cn/Article/details/gt2dtftzyqb.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hnxiangtu.top/Article/details/gt2njfdpidw.html

[Q88] 行转列（条件聚合）
来源：http://dali.ppjwa.cn/Article/details/gt2racfaawz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jlsjyb.cn/Article/details/gt2zavmvaar.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sweek.top/Article/details/gt2dterrpdv.html

[Q89] 判断表是否存在
来源：http://dali.daria6918.cn/Article/details/gt2fcsudimb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhoulong.xyz/Article/details/gt2hbrdyjhx.html

[Q90] 生成序号列
来源：http://dali.xuetiantiany.cn/Article/details/gt2bdtotmez.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gdxncsog.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2ngejmtan.html

R. Bash 专题
来源：http://dali.ehwqpu.com/Article/details/gt2mzpiiokw.html

================================================================================
来源：http://dali.shangyingyoupin.top/Article/details/gt2zimborlo.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gt2wdofmxvt.html

#!/usr/bin/env bash
来源：http://dali.yj20258.top/Article/details/gt2fqarodyl.html

set -euo pipefail
来源：http://dali.xuetiantiany.cn/Article/details/gt2swazfhxq.html

[R02] 变量赋值与使用
来源：http://dali.cdnleiting.top/Article/details/gt2ocrapsea.html

name="Tom"; echo "$name"
来源：http://dali.sweek.top/Article/details/gt2fiwlbfca.html

[R03] 只读变量
来源：http://dali.shzxlz.cn/Article/details/gt2ribfajmn.html

readonly PI=3.14
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2gxqnofkd.html

[R04] 位置参数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wlhvuqsr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhongyouzk.top/Article/details/gt2jddsqnmk.html

[R05] 参数默认值
来源：http://dali.andypj.xyz/Article/details/gt2einadukn.html

name="${1:-default}"
来源：http://dali.yanxiufei.cn/Article/details/gt2ydjngxiy.html

[R06] 判断命令是否存在
来源：http://dali.ppjwa.cn/Article/details/gt2cjrhrvfm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.wangdashe.top/Article/details/gt2bqknvtwo.html

[R07] if 判断文件
来源：http://dali.hysaishi.cn/Article/details/gt2skcxcowf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.pycfn.com/Article/details/gt2rifxoyjx.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gt2xzxagegj.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.havefunace.top/Article/details/gt2cpyhzihb.html

[R09] 字符串比较
来源：http://dali.gotoacloud.top/Article/details/gt2nzkcierl.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yongpay.top/Article/details/gt2kwuvhrpg.html

[R10] 正则匹配
来源：http://dali.jinghuilouyu.cn/Article/details/gt2bxhujwhc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.gogol.net.cn/Article/details/gt2oepmfxzm.html

[R11] case 多分支
来源：http://dali.redwolf501.top/Article/details/gt2pldugnxt.html

case "$1" in
来源：http://dali.zhongyouzk.top/Article/details/gt2wrrczfbf.html

start) echo "启动" ;;
来源：http://dali.shangyingyoupin.top/Article/details/gt2bgyybgis.html

stop)  echo "停止" ;;
来源：http://dali.hnqzz.top/Article/details/gt2mktjvvel.html

*)     echo "未知命令" ;;
来源：http://dali.shangyingyoupin.top/Article/details/gt2vyjtenak.html

esac
来源：http://dali.sysykeji.top/Article/details/gt2smwjvhoi.html

[R12] for 遍历文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2jbpmvweu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.9152youxi.cn/Article/details/gt2jbkvowlg.html

[R13] for 计数循环
来源：http://dali.shuidangran.top/Article/details/gt2gppelwjj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yangfankeji.com/Article/details/gt2ihmelbrf.html

[R14] C 风格 for
来源：http://dali.hywenlv.cn/Article/details/gt2fzjmatyi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tian-w.cn/Article/details/gt2yavxsbor.html

[R15] while 逐行读文件
来源：http://dali.aibaodan.cn/Article/details/gt2xlhyrmhz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cashguo.top/Article/details/gt2dbqmmrfg.html

[R16] until 等待条件
来源：http://dali.chenjidiqi.icu/Article/details/gt2zyqskwcp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jqgufenzy.top/Article/details/gt2yikprmjc.html

[R17] 数组定义与取值
来源：http://dali.ppjwa.cn/Article/details/gt2qcxjujef.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.gotoacloud.top/Article/details/gt2zaezpbzl.html

[R18] 遍历数组
来源：http://dali.hywenlv.cn/Article/details/gt2gfandtqo.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jlsjyb.cn/Article/details/gt2dgflawro.html

[R19] 数组长度
来源：http://dali.nwbrower.top/Article/details/gt2qeuzlota.html

echo "${#arr[@]}"
来源：http://dali.zhongyouzk.top/Article/details/gt2hybzpwoo.html

[R20] 关联数组（字典）
来源：http://dali.yj20258888.top/Article/details/gt2rtkxukca.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.9152youxi.cn/Article/details/gt2uyjghdlb.html

[R21] 字符串长度
来源：http://dali.dashuyun.cn/Article/details/gt2zeumaoin.html

echo "${#s}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2thsfqpmj.html

[R22] 截取子串
来源：http://dali.fengsongda.top/Article/details/gt2zckmbfub.html

echo "${s:0:5}"
来源：http://dali.svipenyu.cn/Article/details/gt2wgpddrgp.html

[R23] 字符串替换
来源：http://dali.jqgufenzy.top/Article/details/gt2ffiapbel.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2usbprvlw.html

[R24] 大小写转换
来源：http://dali.cucudq.cn/Article/details/gt2yplqtyuo.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.nanxinkj.top/Article/details/gt2knpefxaw.html

[R25] 去后缀 / 去前缀
来源：http://dali.xuanzx.com/Article/details/gt2fphmsqbb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jlsjyb.cn/Article/details/gt2yvmqhdob.html

[R26] 命令替换
来源：http://dali.nwbrower.top/Article/details/gt2viaumidy.html

now=$(date +%F); echo "$now"
来源：http://dali.sysykeji.top/Article/details/gt2bnrinpom.html

[R27] 算术展开
来源：http://dali.hysaishi.cn/Article/details/gt2cbgnkwdj.html

echo $((1 + 2 * 3))
来源：http://dali.0kj1m.cn/Article/details/gt2dtkjxosv.html

[R28] 浮点运算
来源：http://dali.haohaochexian.top/Article/details/gt2ejildpyy.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinghuilouyu.cn/Article/details/gt2zdiyykoh.html

[R29] 定义函数
来源：http://dali.bjfxy.top/Article/details/gt2gldjctex.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ivvv.top/Article/details/gt2mobdikjk.html

[R30] 函数返回状态码
来源：http://dali.yuxming.cn/Article/details/gt2epsmgafb.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.nanxuanxn.top/Article/details/gt2bimxhvyd.html

[R31] 局部变量
来源：http://dali.yueranfly.top/Article/details/gt2yywvgpvt.html

f() { local x=1; echo "$x"; }
来源：http://dali.fzhhl.top/Article/details/gt2rvhvitlj.html

[R32] 参数个数校验
来源：http://dali.daxiang520.top/Article/details/gt2agiesxlz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jianghu66.top/Article/details/gt2qawndddl.html

[R33] 捕获错误并提示行号
来源：http://dali.shzxlz.cn/Article/details/gt2fjpphxgt.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenzaomai.com/Article/details/gt2chqnaajd.html

[R34] 退出时清理
来源：http://dali.cdnleiting.top/Article/details/gt2blkmwrnq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.shuidangran.top/Article/details/gt2plurhivk.html

[R35] 后台执行并等待
来源：http://dali.tianlin.xyz/Article/details/gt2ibslwoug.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yanxiufei.cn/Article/details/gt2yyeauadg.html

[R36] 并发执行多个任务
来源：http://dali.kuanghao11.cn/Article/details/gt2rxfgplzl.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cucudq.cn/Article/details/gt2qbaxavfh.html

[R37] 把输出赋给变量
来源：http://dali.smart0.xyz/Article/details/gt2npzxtzkp.html

files=$(ls -1)
来源：http://dali.hammf.cn/Article/details/gt2mebntcot.html

[R38] 管道串联
来源：http://dali.gaohongyu789.top/Article/details/gt2fjnrtivp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.dashuyun.cn/Article/details/gt2toeszwjf.html

[R39] 重定向标准输出与错误
来源：http://dali.daria6918.cn/Article/details/gt2wpqwprlx.html

cmd > out.log 2>&1
来源：http://dali.yuxming.cn/Article/details/gt2zzpwydzl.html

[R40] 追加写日志
来源：http://dali.jlsjyb.cn/Article/details/gt2mulmiuds.html

echo "log" >> out.log
来源：http://dali.jqgufenzy.top/Article/details/gt2giprpvwa.html

[R41] 丢弃输出
来源：http://dali.snrcjt.cn/Article/details/gt2avmenvcj.html

cmd >/dev/null 2>&1
来源：http://dali.cheryme.top/Article/details/gt2irkroolb.html

[R42] 输入重定向
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2johxnqrp.html

wc -l < a.txt
来源：http://dali.hongshengwenyu.top/Article/details/gt2ziozbzpl.html

[R43] 按名字查找文件
来源：http://dali.yangfankeji.com/Article/details/gt2grqnefhk.html

find . -name "*.log" -type f
来源：http://dali.jinqigfzy.top/Article/details/gt2kdyvjbik.html

[R44] 按修改时间查找
来源：http://dali.shzxlz.cn/Article/details/gt2kpydqwbx.html

find . -mtime -7 -type f
来源：http://dali.jiagoushi.top/Article/details/gt2moxucppo.html

[R45] 批量删除
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jiznaecn.html

find . -name "*.tmp" -delete
来源：http://dali.zhongyouzk.top/Article/details/gt2evpxjrvb.html

[R46] 递归替换文件内容
来源：http://dali.gzhubu.top/Article/details/gt2ajlxsvzj.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhiwuduotai.top/Article/details/gt2vvoajrgt.html

[R47] sed 单行替换
来源：http://dali.daria6918.cn/Article/details/gt2gsyaviax.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yj20258888.top/Article/details/gt2hbakfsax.html

[R48] awk 取指定列
来源：http://dali.hammf.cn/Article/details/gt2hbjdoiaw.html

awk '{print $1, $3}' a.txt
来源：http://dali.bjfxy.top/Article/details/gt2qjnrvfqy.html

[R49] awk 带条件
来源：http://dali.nanxinkj.top/Article/details/gt2yxbifgjs.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sxryk.cn/Article/details/gt2dwckmcgv.html

[R50] awk 求和
来源：http://dali.shuidangran.top/Article/details/gt2znsqzypn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.daria6918.cn/Article/details/gt2sgigwgzb.html

[R51] 排序去重取前几
来源：http://dali.nwbrower.top/Article/details/gt2dabrrvvc.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.sufxvd.cn/Article/details/gt2uoszbsyu.html

[R52] 统计行数
来源：http://dali.hammf.cn/Article/details/gt2cgvocxmb.html

wc -l a.txt
来源：http://dali.9152youxi.cn/Article/details/gt2pwochatm.html

[R53] 查看文件头与实时尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cintocyo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yongpay.top/Article/details/gt2fgcivpar.html

[R54] 比较两个文件
来源：http://dali.xinyue.icu/Article/details/gt2svomvgjv.html

diff a.txt b.txt
来源：http://dali.yueranfly.top/Article/details/gt2ggipwkwa.html

[R55] 压缩与解压
来源：http://dali.yj202588.top/Article/details/gt2bcemllqs.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.chenzaomai.com/Article/details/gt2iisoujml.html

[R56] 远程拷贝
来源：http://dali.jianghu66.top/Article/details/gt2jojjiudq.html

scp file user@host:/path/
来源：http://dali.zhixingplan.top/Article/details/gt2dqdowlxp.html

[R57] 远程执行命令
来源：http://dali.gaohongyu789.top/Article/details/gt2hbhtkfly.html

ssh user@host 'uptime'
来源：http://dali.snrcjt.cn/Article/details/gt2uozeuqtd.html

[R58] 下载文件
来源：http://dali.yonumen.top/Article/details/gt2cgmsfbeq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cucudq.cn/Article/details/gt2wgkozroy.html

[R59] 发 POST JSON
来源：http://dali.yuanzhike.top/Article/details/gt2xelooprh.html


<!-- 参考信息 -->