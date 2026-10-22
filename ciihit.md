代发 wailian999

INSERT INTO users (name) VALUES ('C');
来源：http://dali.smart0.xyz/Article/details/gt2oyrmzsjv.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jianghu66.top/Article/details/gt2lfbmzjzt.html

[Q13] 忽略重复插入
来源：http://dali.zdqjudy.top/Article/details/gt2zzdhgjee.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.guowangkeji.top/Article/details/gt2kodjwkjj.html

[Q14] 存在则更新（upsert）
来源：http://dali.chenzaomai.com/Article/details/gt2acolqblx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.yongpay.top/Article/details/gt2azfdwhrx.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.chenzaomai.com/Article/details/gt2ffwqkijd.html

[Q15] 查询全部
来源：http://dali.316326.xyz/Article/details/gt2exahczjt.html

SELECT * FROM users;
来源：http://dali.jiagoushi.top/Article/details/gt2rmmcxtfh.html

[Q16] 查询指定列
来源：http://dali.nanxinkj.top/Article/details/gt2xilbegek.html

SELECT id, name FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2jfjhzpbt.html

[Q17] 条件查询
来源：http://dali.hongshengwenyu.top/Article/details/gt2ywikbiwg.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ivvv.top/Article/details/gt2gyvijldw.html

[Q18] 模糊匹配
来源：http://dali.snrcjt.cn/Article/details/gt2ctsanmdf.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.birdmap.top/Article/details/gt2kmwhuxlq.html

[Q19] 范围查询
来源：http://dali.wangshuangyany.cn/Article/details/gt2tntvtsos.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.gzhubu.top/Article/details/gt2nlqclpny.html

[Q20] IN 列表
来源：http://dali.jinqigfzy.top/Article/details/gt2rrbsbzks.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.birdmap.top/Article/details/gt2uhzkskcy.html

[Q21] 空值判断
来源：http://dali.sysykeji.top/Article/details/gt2mbzmrasc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jyoumei.cn/Article/details/gt2zejbtiuo.html

[Q22] 排序
来源：http://dali.tianlin.xyz/Article/details/gt2yhisezap.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2cnbqxjyv.html

[Q23] 分页
来源：http://dali.xziqi.cn/Article/details/gt2rfwjffzi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.xylfe.cn/Article/details/gt2napygtqv.html

[Q24] 去重
来源：http://dali.zhoulong.xyz/Article/details/gt2phzidsyd.html

SELECT DISTINCT city FROM users;
来源：http://dali.gogol.net.cn/Article/details/gt2fslocvte.html

[Q25] 只取前 N 条
来源：http://dali.feifeiyinyue.top/Article/details/gt2laeszgwy.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jlsjyb.cn/Article/details/gt2nsmyaeiy.html

[Q26] 计数
来源：http://dali.yj20258888.top/Article/details/gt2hgzwszuo.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhengqikj.top/Article/details/gt2ulwukkxz.html

[Q27] 条件计数
来源：http://dali.aizwys.cn/Article/details/gt2frphxtuu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.mhx1999.top/Article/details/gt2jmkrzpku.html

[Q28] 求和与平均
来源：http://dali.vqdsnc.cn/Article/details/gt2oeipbtid.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.yj20258888.top/Article/details/gt2ullmnrlb.html

[Q29] 最大最小值
来源：http://dali.tian-w.cn/Article/details/gt2sxfhmxtz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.dianchejie.cn/Article/details/gt2zyxiqwtt.html

[Q30] 分组统计
来源：http://dali.pycfn.com/Article/details/gt2qersharu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.smart0.xyz/Article/details/gt2mdoijkqv.html

[Q31] 分组后过滤
来源：http://dali.ehwqpu.com/Article/details/gt2nnxhupci.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.0kj1m.cn/Article/details/gt2zbidakas.html

[Q32] 分组拼接字符串
来源：http://dali.zhengqikj.top/Article/details/gt2dercvroq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2jxapmaus.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2duoowlgh.html

[Q33] 多列分组
来源：http://dali.sxryk.cn/Article/details/gt2cuifljmi.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ppjwa.cn/Article/details/gt2jedzlgwo.html

[Q34] 每组取第一条
来源：http://dali.316326.xyz/Article/details/gt2dwdjtxtg.html

SELECT * FROM (
来源：http://dali.tianlin.xyz/Article/details/gt2isbxsrcv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hnxiangtu.top/Article/details/gt2mlraxozl.html

) t WHERE rn = 1;
来源：http://dali.hnqzz.top/Article/details/gt2zgkaxnmj.html

[Q35] 内连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rxbmvyuf.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gotoacloud.top/Article/details/gt2pazzanmb.html

[Q36] 左连接
来源：http://dali.fengsongda.top/Article/details/gt2dvjcpcuq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xylfe.cn/Article/details/gt2pctvgohx.html

[Q37] 右连接
来源：http://dali.jiagoushi.top/Article/details/gt2wvcruwhm.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.daxiang520.top/Article/details/gt2obierxlc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cashguo.top/Article/details/gt2boiodsfd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.cucudq.cn/Article/details/gt2svgasgon.html

[Q39] 自连接（查上下级）
来源：http://dali.daxiang520.top/Article/details/gt2hellttpz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.sweek.top/Article/details/gt2geaeqiig.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.c1oappe.top/Article/details/gt2ocsdhqyu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gogol.net.cn/Article/details/gt2oqqvzceg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cucudq.cn/Article/details/gt2dwvmsuqi.html

[Q41] 多表连接
来源：http://dali.jinqigufen.top/Article/details/gt2utppcmmp.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2ectsrlmh.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jyoumei.cn/Article/details/gt2vuyoatro.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rkvrtcqh.html

[Q42] 连接条件附加过滤
来源：http://dali.hongshengwenyu.top/Article/details/gt2sdzrnvce.html

SELECT u.name, o.amount FROM users u
来源：http://dali.tanke756.top/Article/details/gt2cjtnppfn.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.nwbrower.top/Article/details/gt2cifuamxe.html

[Q43] 标量子查询
来源：http://dali.ppjwa.cn/Article/details/gt2cpjzkhaf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yonumen.top/Article/details/gt2zknpbxio.html

[Q44] IN 子查询
来源：http://dali.ivvv.top/Article/details/gt2rcxzhmhj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xuanzx.com/Article/details/gt2iybnpeah.html

[Q45] EXISTS 判断存在
来源：http://dali.svipenyu.cn/Article/details/gt2lsptxqsr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.9152youxi.cn/Article/details/gt2liuoadot.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.pengpengdd.cyou/Article/details/gt2hmqurfff.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hfpthk.cn/Article/details/gt2ntopfzci.html

[Q47] 与平均值比较
来源：http://dali.hammf.cn/Article/details/gt2jfsjpdrv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.wangshuangyany.cn/Article/details/gt2dhjlwczj.html

[Q48] CTE 公用表表达式
来源：http://dali.yongpay.top/Article/details/gt2sbyxaxcu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yuanzhike.top/Article/details/gt2ztmevgnd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.aizwys.cn/Article/details/gt2hucqanji.html

[Q49] 更新单行
来源：http://dali.zycfv.cn/Article/details/gt2ukdavges.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cdnleiting.top/Article/details/gt2gzfzpvad.html

[Q50] 批量更新
来源：http://dali.daria6918.cn/Article/details/gt2ksrjhvqq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ivvv.top/Article/details/gt2kyliufqw.html

[Q51] 用子查询更新
来源：http://dali.shuidangran.top/Article/details/gt2nevojped.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.yonumen.top/Article/details/gt2nrfccqwc.html

[Q52] 删除指定行
来源：http://dali.andypj.xyz/Article/details/gt2azmqbrkv.html

DELETE FROM users WHERE id = 10;
来源：http://dali.daria6918.cn/Article/details/gt2jkmzkwre.html

[Q53] 按条件删除
来源：http://dali.cdnleiting.top/Article/details/gt2yiuwjuwd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.tian-w.cn/Article/details/gt2oushgkjp.html

[Q54] 清空表
来源：http://dali.zdqjudy.top/Article/details/gt2akpjnjur.html

TRUNCATE TABLE logs;
来源：http://dali.jinqigfzy.top/Article/details/gt2bngshhzx.html

[Q55] 排名（并列占位）
来源：http://dali.guowangkeji.top/Article/details/gt2yzhzmlze.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hnqzz.top/Article/details/gt2aacuaaep.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jinqigfzy.top/Article/details/gt2qqibpxzi.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shzxlz.cn/Article/details/gt2fjprfmtb.html

[Q57] 行号
来源：http://dali.jiagoushi.top/Article/details/gt2vwgyrqtx.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cashguo.top/Article/details/gt2cugylhpq.html

[Q58] 累计求和
来源：http://dali.jinghuilouyu.cn/Article/details/gt2rbbqzanh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ivvv.top/Article/details/gt2omilnjfg.html

[Q59] 分组内累计
来源：http://dali.feifeiyinyue.top/Article/details/gt2zuxmurfz.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gt2kocwhoym.html

[Q60] 取上一行 / 下一行
来源：http://dali.dashuyun.cn/Article/details/gt2zzimnmty.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yj20258.top/Article/details/gt2kdotwafo.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.birdmap.top/Article/details/gt2qtzbdqnj.html

[Q61] 移动平均
来源：http://dali.fzhhl.top/Article/details/gt2tfdcqetz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.fengsongda.top/Article/details/gt2cpxcteel.html

[Q62] 分组占比
来源：http://dali.ehwqpu.com/Article/details/gt2irearywj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.tian-w.cn/Article/details/gt2usiyisgu.html

[Q63] 开启事务
来源：http://dali.yvedp.cn/Article/details/gt2sgnpeeyp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hnqzz.top/Article/details/gt2bmjwvcwl.html

[Q64] 提交事务
来源：http://dali.hongshengwenyu.top/Article/details/gt2pekbxjly.html

COMMIT;
来源：http://dali.hnxiangtu.top/Article/details/gt2knpnxhbp.html

[Q65] 回滚事务
来源：http://dali.zdqjudy.top/Article/details/gt2ncasmrah.html

ROLLBACK;
来源：http://dali.cucudq.cn/Article/details/gt2gehdjsen.html

[Q66] 行锁查询
来源：http://dali.shzxlz.cn/Article/details/gt2iwwntuav.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ivvv.top/Article/details/gt2vwosclkl.html

[Q67] 设置隔离级别
来源：http://dali.shzxlz.cn/Article/details/gt2uttmymqs.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.tian-w.cn/Article/details/gt2xrwrafej.html

[Q68] 保存点
来源：http://dali.aibaodan.cn/Article/details/gt2ylevxrnr.html

SAVEPOINT sp1;
来源：http://dali.fengsongda.top/Article/details/gt2caloiygs.html

ROLLBACK TO sp1;
来源：http://dali.smart0.xyz/Article/details/gt2aeeimlrq.html

[Q69] 查看执行计划
来源：http://dali.xylfe.cn/Article/details/gt2xyzvsyvb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.zhoulong.xyz/Article/details/gt2fnjszjlh.html

[Q70] 更新统计信息
来源：http://dali.zdqjudy.top/Article/details/gt2ktpozrnr.html

ANALYZE TABLE users;
来源：http://dali.yangfankeji.com/Article/details/gt2luovddrv.html

[Q71] 查看建表语句
来源：http://dali.kuanghao11.cn/Article/details/gt2bopczuya.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2mjvksshi.html

[Q72] 查看索引
来源：http://dali.yangfankeji.com/Article/details/gt2gnuvdgav.html

SHOW INDEX FROM users;
来源：http://dali.xziqi.cn/Article/details/gt2pqwjppif.html

[Q73] 查看表状态
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lofgzkit.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gaohongyu789.top/Article/details/gt2eoknnajz.html

[Q74] 强制使用索引
来源：http://dali.smart0.xyz/Article/details/gt2btpkfrpc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.c1oappe.top/Article/details/gt2iikrfgvw.html

[Q75] 日期格式化
来源：http://dali.wangdashe.top/Article/details/gt2qjvdrlmu.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gt2dydllaus.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2qqvigity.html

[Q76] 按天统计
来源：http://dali.pycfn.com/Article/details/gt2qqprdyqn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yangfankeji.com/Article/details/gt2krdosuut.html

[Q77] 时间加减
来源：http://dali.dianchejie.cn/Article/details/gt2qzsixumo.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cdnleiting.top/Article/details/gt2vcsmrzui.html

[Q78] 当前时间
来源：http://dali.dianchejie.cn/Article/details/gt2eahyczvv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shuidangran.top/Article/details/gt2vckxerlr.html

[Q79] 字符串拼接
来源：http://dali.dashuyun.cn/Article/details/gt2dvsstiph.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.fzhhl.top/Article/details/gt2wpdjuhrh.html

[Q80] 字符串截取
来源：http://dali.wangshuangyany.cn/Article/details/gt2obkpnfcf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yj20258888.top/Article/details/gt2ncubdscl.html

[Q81] 字符串替换
来源：http://dali.zhengqikj.top/Article/details/gt2vteppgeu.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ivvv.top/Article/details/gt2aoiutnej.html

[Q82] 字符长度与字节长度
来源：http://dali.vqdsnc.cn/Article/details/gt2dquveude.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.sweek.top/Article/details/gt2uzzjhpuc.html

[Q83] 大小写转换
来源：http://dali.vqdsnc.cn/Article/details/gt2coocikai.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.smart0.xyz/Article/details/gt2rwrzfajh.html

[Q84] 去除首尾空格
来源：http://dali.pengpengdd.cyou/Article/details/gt2ntzmtilj.html

SELECT TRIM(name) FROM users;
来源：http://dali.birdmap.top/Article/details/gt2mjklzxfm.html

[Q85] 数值取整
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2rrbpmfkm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ydzc1.top/Article/details/gt2kihwjoav.html

[Q86] 读取 JSON 字段
来源：http://dali.jinqigufen.top/Article/details/gt2tethzglv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhixingplan.top/Article/details/gt2rklyeldo.html

[Q87] JSON 字段做条件
来源：http://dali.daxiang520.top/Article/details/gt2fhvlzgea.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.snrcjt.cn/Article/details/gt2kbcmdbkv.html

[Q88] 行转列（条件聚合）
来源：http://dali.jqgufenzy.top/Article/details/gt2jstzywio.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yj202588.top/Article/details/gt2wolroahi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2ahoodrug.html

[Q89] 判断表是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gt2lkfetsvr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yongpay.top/Article/details/gt2jjcermoh.html

[Q90] 生成序号列
来源：http://dali.yj20258888.top/Article/details/gt2smtgyhwo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinqigfzy.top/Article/details/gt2wcdlajgh.html

================================================================================
来源：http://dali.kuanghao11.cn/Article/details/gt2fcemlple.html

R. Bash 专题
来源：http://dali.yueranfly.top/Article/details/gt2xnnrqzcw.html

================================================================================
来源：http://dali.vqdsnc.cn/Article/details/gt2erdfsmiy.html

[R01] shebang 与严格模式
来源：http://dali.chenzaomai.com/Article/details/gt2aoypeicq.html

#!/usr/bin/env bash
来源：http://dali.bjfxy.top/Article/details/gt2hxqxseyv.html

set -euo pipefail
来源：http://dali.aibaodan.cn/Article/details/gt2jfukhbwb.html

[R02] 变量赋值与使用
来源：http://dali.andypj.xyz/Article/details/gt2wobinbaa.html

name="Tom"; echo "$name"
来源：http://dali.mhx1999.top/Article/details/gt2rfwaruzl.html

[R03] 只读变量
来源：http://dali.zhongyouzk.top/Article/details/gt2vimtnupd.html

readonly PI=3.14
来源：http://dali.wangshuangyany.cn/Article/details/gt2utjsqkct.html

[R04] 位置参数
来源：http://dali.fengsongda.top/Article/details/gt2xrkuypze.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xuanzx.com/Article/details/gt2ttopppng.html

[R05] 参数默认值
来源：http://dali.c1oappe.top/Article/details/gt2akespsgb.html

name="${1:-default}"
来源：http://dali.jianghu66.top/Article/details/gt2ogqilbcl.html

[R06] 判断命令是否存在
来源：http://dali.fzhhl.top/Article/details/gt2gsppppcd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.daxiang520.top/Article/details/gt2lwawomzk.html

[R07] if 判断文件
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2ntdailjl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.havefunace.top/Article/details/gt2wbqiwijv.html

[R08] 数值比较
来源：http://dali.nanxuanxn.top/Article/details/gt2vyavuvkg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.snrcjt.cn/Article/details/gt2tiozdief.html

[R09] 字符串比较
来源：http://dali.mhx1999.top/Article/details/gt2kitkfsdx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.vqdsnc.cn/Article/details/gt2xjfqqhez.html

[R10] 正则匹配
来源：http://dali.ehwqpu.com/Article/details/gt2iwirbfvy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.smart0.xyz/Article/details/gt2zccxxdat.html

[R11] case 多分支
来源：http://dali.pycfn.com/Article/details/gt2yvnzqgdi.html

case "$1" in
来源：http://dali.zhengqikj.top/Article/details/gt2bysanoeg.html

start) echo "启动" ;;
来源：http://dali.gaohongyu789.top/Article/details/gt2tfjnzatn.html

stop)  echo "停止" ;;
来源：http://dali.ydzc1.top/Article/details/gt2jblqygcc.html

*)     echo "未知命令" ;;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2tvvjrxjp.html

esac
来源：http://dali.zhengqikj.top/Article/details/gt2axnjwbcd.html

[R12] for 遍历文件
来源：http://dali.wangdashe.top/Article/details/gt2rnyywras.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hongshengwenyu.top/Article/details/gt2sxlyspgh.html

[R13] for 计数循环
来源：http://dali.jinqigufen.top/Article/details/gt2duvckmeh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.mhx1999.top/Article/details/gt2ljjggnge.html

[R14] C 风格 for
来源：http://dali.jqgfzy.top/Article/details/gt2edaampux.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jiagoushi.top/Article/details/gt2zncvgzbs.html

[R15] while 逐行读文件
来源：http://dali.gzhubu.top/Article/details/gt2hrvxfknv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.wangdashe.top/Article/details/gt2gksfrvmt.html

[R16] until 等待条件
来源：http://dali.iojbl.cn/Article/details/gt2ycutmlgb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.guowangkeji.top/Article/details/gt2jirqfkej.html

[R17] 数组定义与取值
来源：http://dali.ivvv.top/Article/details/gt2uxylbtfi.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.smart0.xyz/Article/details/gt2ywevqndo.html

[R18] 遍历数组
来源：http://dali.cucudq.cn/Article/details/gt2flcncgjr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shzxlz.cn/Article/details/gt2ioevqnfz.html

[R19] 数组长度
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vtxbknfi.html

echo "${#arr[@]}"
来源：http://dali.zhiwuduotai.top/Article/details/gt2opeiaitr.html

[R20] 关联数组（字典）
来源：http://dali.tanke756.top/Article/details/gt2jqbpqneh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj20258.top/Article/details/gt2eoifqsyd.html

[R21] 字符串长度
来源：http://dali.jinghuilouyu.cn/Article/details/gt2gqdaelwb.html

echo "${#s}"
来源：http://dali.sxryk.cn/Article/details/gt2houlzbnj.html

[R22] 截取子串
来源：http://dali.birdmap.top/Article/details/gt2ajtnikde.html

echo "${s:0:5}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2gnumhvdd.html

[R23] 字符串替换
来源：http://dali.ydzc1.top/Article/details/gt2tkbvbaho.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shzxlz.cn/Article/details/gt2ixsllxhh.html

[R24] 大小写转换
来源：http://dali.redwolf501.top/Article/details/gt2pkzdimpm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sufxvd.cn/Article/details/gt2rcwurern.html

[R25] 去后缀 / 去前缀
来源：http://dali.xuetiantiany.cn/Article/details/gt2hlorhtbx.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.0kj1m.cn/Article/details/gt2ztvmaccr.html

[R26] 命令替换
来源：http://dali.ppjwa.cn/Article/details/gt2altufgpj.html

now=$(date +%F); echo "$now"
来源：http://dali.mhx1999.top/Article/details/gt2emaccdct.html

[R27] 算术展开
来源：http://dali.tanke756.top/Article/details/gt2negdszsm.html

echo $((1 + 2 * 3))
来源：http://dali.mhx1999.top/Article/details/gt2mpyjfzfi.html

[R28] 浮点运算
来源：http://dali.tian-w.cn/Article/details/gt2xzbekdaz.html

echo "scale=2; 10/3" | bc
来源：http://dali.xuanzx.com/Article/details/gt2adcvyqye.html

[R29] 定义函数
来源：http://dali.jyoumei.cn/Article/details/gt2bgbfgdsn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yj20258.top/Article/details/gt2xivbgmeh.html

[R30] 函数返回状态码
来源：http://dali.mhx1999.top/Article/details/gt2ntpszmeh.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yj202588.top/Article/details/gt2ngyrptjt.html

[R31] 局部变量
来源：http://dali.yueranfly.top/Article/details/gt2rmjntltn.html

f() { local x=1; echo "$x"; }
来源：http://dali.bjfxy.top/Article/details/gt2qwnzyptc.html

[R32] 参数个数校验
来源：http://dali.jinqigufen.top/Article/details/gt2lbljnjhf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ehwqpu.com/Article/details/gt2ssldarfd.html

[R33] 捕获错误并提示行号
来源：http://dali.jinqigfzy.top/Article/details/gt2sgzlvxip.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.haohaochexian.top/Article/details/gt2wyvrnywo.html

[R34] 退出时清理
来源：http://dali.zhengqikj.top/Article/details/gt2aufgzofp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.9152youxi.cn/Article/details/gt2ynwaalmt.html

[R35] 后台执行并等待
来源：http://dali.dianchejie.cn/Article/details/gt2edyyekkq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2efvwpcqr.html

[R36] 并发执行多个任务
来源：http://dali.haohaochexian.top/Article/details/gt2tzhjqkne.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.vqdsnc.cn/Article/details/gt2hsprhygo.html

[R37] 把输出赋给变量
来源：http://dali.gaohongyu789.top/Article/details/gt2zacdcwbk.html

files=$(ls -1)
来源：http://dali.yangfankeji.com/Article/details/gt2rkyezywx.html

[R38] 管道串联
来源：http://dali.hfpthk.cn/Article/details/gt2yzddzqpb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hammf.cn/Article/details/gt2vqbfbogp.html

[R39] 重定向标准输出与错误
来源：http://dali.sysykeji.top/Article/details/gt2uxptsito.html

cmd > out.log 2>&1
来源：http://dali.9152youxi.cn/Article/details/gt2prvlnuok.html

[R40] 追加写日志
来源：http://dali.yanxiufei.cn/Article/details/gt2pzgdjqyw.html

echo "log" >> out.log
来源：http://dali.yvedp.cn/Article/details/gt2qhtuzudj.html

[R41] 丢弃输出
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2mvjaeukk.html

cmd >/dev/null 2>&1
来源：http://dali.pycfn.com/Article/details/gt2bdoafoee.html

[R42] 输入重定向
来源：http://dali.jinqigfzy.top/Article/details/gt2dxehcwzt.html

wc -l < a.txt
来源：http://dali.zhongyouzk.top/Article/details/gt2wtucnpkg.html

[R43] 按名字查找文件
来源：http://dali.bjfxy.top/Article/details/gt2tqtteedx.html

find . -name "*.log" -type f
来源：http://dali.vqdsnc.cn/Article/details/gt2uooksxbd.html

[R44] 按修改时间查找
来源：http://dali.sufxvd.cn/Article/details/gt2nnxzfbei.html

find . -mtime -7 -type f
来源：http://dali.pengpengdd.cyou/Article/details/gt2sveftbiz.html

[R45] 批量删除
来源：http://dali.guowangkeji.top/Article/details/gt2qrfnpdqv.html

find . -name "*.tmp" -delete
来源：http://dali.cheryme.top/Article/details/gt2wnxgpksj.html

[R46] 递归替换文件内容
来源：http://dali.hysaishi.cn/Article/details/gt2ksinxtzr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hysaishi.cn/Article/details/gt2lobpvhph.html

[R47] sed 单行替换
来源：http://dali.ehwqpu.com/Article/details/gt2tvxogzgr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.316326.xyz/Article/details/gt2hdmeawni.html

[R48] awk 取指定列
来源：http://dali.9152youxi.cn/Article/details/gt2wahuadra.html

awk '{print $1, $3}' a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gt2orjhebnb.html

[R49] awk 带条件
来源：http://dali.guowangkeji.top/Article/details/gt2towkfxcf.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jlsjyb.cn/Article/details/gt2bqguzrng.html

[R50] awk 求和
来源：http://dali.316326.xyz/Article/details/gt2ndgjbnch.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.chenzaomai.com/Article/details/gt2daflxjyu.html

[R51] 排序去重取前几
来源：http://dali.cucudq.cn/Article/details/gt2ejjhiowu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.tanke756.top/Article/details/gt2hqybjfzg.html

[R52] 统计行数
来源：http://dali.zhiwuduotai.top/Article/details/gt2cakysfgg.html

wc -l a.txt
来源：http://dali.gaohongyu789.top/Article/details/gt2rnuhgyrt.html

[R53] 查看文件头与实时尾
来源：http://dali.gotoacloud.top/Article/details/gt2teqqlgzk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jyoumei.cn/Article/details/gt2qgdtsefq.html

[R54] 比较两个文件
来源：http://dali.cheryme.top/Article/details/gt2xfjlesxx.html

diff a.txt b.txt
来源：http://dali.hnxiangtu.top/Article/details/gt2iwcskiki.html

[R55] 压缩与解压
来源：http://dali.gotoacloud.top/Article/details/gt2vachgzit.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.wangdashe.top/Article/details/gt2rkscgbtg.html

[R56] 远程拷贝
来源：http://dali.sufxvd.cn/Article/details/gt2xosxkwuo.html

scp file user@host:/path/
来源：http://dali.zhengqikj.top/Article/details/gt2rjpbpqwh.html

[R57] 远程执行命令
来源：http://dali.xuetiantiany.cn/Article/details/gt2avxrxgbe.html

ssh user@host 'uptime'
来源：http://dali.jqgfzy.top/Article/details/gt2etlmcerl.html

[R58] 下载文件
来源：http://dali.zhongyouzk.top/Article/details/gt2vujpbpph.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zdqjudy.top/Article/details/gt2cuylscih.html

[R59] 发 POST JSON
来源：http://dali.jiagoushi.top/Article/details/gt2ymctpefg.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gogol.net.cn/Article/details/gt2itqmgcft.html

[R60] 只看 HTTP 状态码
来源：http://dali.quarkkingdee.top/Article/details/gt2hoopezrv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yuanzhike.top/Article/details/gt2rojaspvi.html

[R61] 磁盘占用
来源：http://dali.sysykeji.top/Article/details/gt2lerpvwse.html


<!-- 参考信息 -->