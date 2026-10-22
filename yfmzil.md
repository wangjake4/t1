代发 wailian999

INSERT INTO users (name) VALUES ('C');
来源：http://dali.yueranfly.top/Article/details/gt2doktlqcd.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jinqigfzy.top/Article/details/gt2hmdenvzx.html

[Q13] 忽略重复插入
来源：http://dali.snrcjt.cn/Article/details/gt2xmnsrejx.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.pengpengdd.cyou/Article/details/gt2gkkisbph.html

[Q14] 存在则更新（upsert）
来源：http://dali.xinyue.icu/Article/details/gt2mpqomebz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.jyoumei.cn/Article/details/gt2lxxcrcre.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.zhixingplan.top/Article/details/gt2juvbcdua.html

[Q15] 查询全部
来源：http://dali.yanxiufei.cn/Article/details/gt2ifuwksci.html

SELECT * FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gt2npxgknzh.html

[Q16] 查询指定列
来源：http://dali.shangyingyoupin.top/Article/details/gt2qynqdnpj.html

SELECT id, name FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2jpdlxsxp.html

[Q17] 条件查询
来源：http://dali.zhengqikj.top/Article/details/gt2evvsgjhv.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.xinyue.icu/Article/details/gt2blbpmfbd.html

[Q18] 模糊匹配
来源：http://dali.gzhubu.top/Article/details/gt2eagodgqw.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.quarkkingdee.top/Article/details/gt2pjmwudms.html

[Q19] 范围查询
来源：http://dali.shangyingyoupin.top/Article/details/gt2pifsvjvd.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jianghu66.top/Article/details/gt2gcsbghna.html

[Q20] IN 列表
来源：http://dali.hywenlv.cn/Article/details/gt2oanemmum.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.kuanghao11.cn/Article/details/gt2iqwdzlyr.html

[Q21] 空值判断
来源：http://dali.ppjwa.cn/Article/details/gt2gdeqxzoy.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gogol.net.cn/Article/details/gt2fyiuefaf.html

[Q22] 排序
来源：http://dali.jinqigfzy.top/Article/details/gt2uevgraxy.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.fengsongda.top/Article/details/gt2efoytdfd.html

[Q23] 分页
来源：http://dali.chenjidiqi.icu/Article/details/gt2chcbhrft.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cashguo.top/Article/details/gt2vyozbwof.html

[Q24] 去重
来源：http://dali.jqgufenzy.top/Article/details/gt2ociolqqr.html

SELECT DISTINCT city FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gt2yyjdhnlx.html

[Q25] 只取前 N 条
来源：http://dali.tanke756.top/Article/details/gt2lfisesve.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lovscrya.html

[Q26] 计数
来源：http://dali.dashuyun.cn/Article/details/gt2vjjqfmnq.html

SELECT COUNT(*) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2dwzkrntc.html

[Q27] 条件计数
来源：http://dali.fengsongda.top/Article/details/gt2aikhjjro.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2azgrgnby.html

[Q28] 求和与平均
来源：http://dali.redwolf501.top/Article/details/gt2khvplaty.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.iojbl.cn/Article/details/gt2xpqsfczj.html

[Q29] 最大最小值
来源：http://dali.shangyingyoupin.top/Article/details/gt2itiuhrma.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gt2svnuacts.html

[Q30] 分组统计
来源：http://dali.meibo888.top/Article/details/gt2pifsuvqq.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jyoumei.cn/Article/details/gt2ynkusxhf.html

[Q31] 分组后过滤
来源：http://dali.zdqjudy.top/Article/details/gt2icchwyfl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yueranfly.top/Article/details/gt2vfszjrlv.html

[Q32] 分组拼接字符串
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2tjjchfut.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.tanke756.top/Article/details/gt2haigmbul.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.daxiang520.top/Article/details/gt2ycvvgtef.html

[Q33] 多列分组
来源：http://dali.c1oappe.top/Article/details/gt2qsiabcja.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ppjwa.cn/Article/details/gt2bgthvane.html

[Q34] 每组取第一条
来源：http://dali.9152youxi.cn/Article/details/gt2mnyzjjdb.html

SELECT * FROM (
来源：http://dali.ppjwa.cn/Article/details/gt2djdevqfp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sysykeji.top/Article/details/gt2nefemjeu.html

) t WHERE rn = 1;
来源：http://dali.jinqigfzy.top/Article/details/gt2oozsgrnu.html

[Q35] 内连接
来源：http://dali.jyoumei.cn/Article/details/gt2daiffenk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shzxlz.cn/Article/details/gt2jwrqggac.html

[Q36] 左连接
来源：http://dali.hnqzz.top/Article/details/gt2jpuaerrx.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2wpclcalq.html

[Q37] 右连接
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2gqdavxqi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.dashuyun.cn/Article/details/gt2yillbfhw.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.haohaochexian.top/Article/details/gt2iwqhavvc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.birdmap.top/Article/details/gt2umqtdgff.html

[Q39] 自连接（查上下级）
来源：http://dali.jinghuilouyu.cn/Article/details/gt2nhcfflky.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.tianlin.xyz/Article/details/gt2braeezpe.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2wjukfvjh.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cashguo.top/Article/details/gt2fyepuswu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.guowangkeji.top/Article/details/gt2iazixtfg.html

[Q41] 多表连接
来源：http://dali.zycfv.cn/Article/details/gt2hjgiyhss.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.chenlongwang.top/Article/details/gt2xfjuzwae.html

JOIN users u ON u.id = o.user_id
来源：http://dali.daria6918.cn/Article/details/gt2gibeevex.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.andypj.xyz/Article/details/gt2ozxrfoeq.html

[Q42] 连接条件附加过滤
来源：http://dali.shangyingyoupin.top/Article/details/gt2ajrvicca.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hnxiangtu.top/Article/details/gt2dkupkljz.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.wangshuangyany.cn/Article/details/gt2xazelitu.html

[Q43] 标量子查询
来源：http://dali.ydzc1.top/Article/details/gt2ofikqlcm.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinqigfzy.top/Article/details/gt2xdfiiouz.html

[Q44] IN 子查询
来源：http://dali.shangyingyoupin.top/Article/details/gt2raodpned.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ivvv.top/Article/details/gt2jzqvnark.html

[Q45] EXISTS 判断存在
来源：http://dali.zdqjudy.top/Article/details/gt2fvwoyqav.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.wangshuangyany.cn/Article/details/gt2ucptiqif.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.sufxvd.cn/Article/details/gt2bcuepgoj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2vkdrvcfz.html

[Q47] 与平均值比较
来源：http://dali.andypj.xyz/Article/details/gt2cfxbyywx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.feifeiyinyue.top/Article/details/gt2vjlddhxa.html

[Q48] CTE 公用表表达式
来源：http://dali.fengsongda.top/Article/details/gt2gbfrvqqy.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.dashuyun.cn/Article/details/gt2qyhxwota.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shzxlz.cn/Article/details/gt2hvityaco.html

[Q49] 更新单行
来源：http://dali.pengpengdd.cyou/Article/details/gt2qqcqeqvv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zdqjudy.top/Article/details/gt2kpewkccf.html

[Q50] 批量更新
来源：http://dali.gaohongyu789.top/Article/details/gt2vqpagirt.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hfpthk.cn/Article/details/gt2skonosal.html

[Q51] 用子查询更新
来源：http://dali.gzhubu.top/Article/details/gt2nqpncfkj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.iojbl.cn/Article/details/gt2syxcntet.html

[Q52] 删除指定行
来源：http://dali.c1oappe.top/Article/details/gt2tmuofool.html

DELETE FROM users WHERE id = 10;
来源：http://dali.dashuyun.cn/Article/details/gt2ktelozea.html

[Q53] 按条件删除
来源：http://dali.bjfxy.top/Article/details/gt2ikmezerh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yangfankeji.com/Article/details/gt2ekovhbdf.html

[Q54] 清空表
来源：http://dali.quarkkingdee.top/Article/details/gt2yqhrzngi.html

TRUNCATE TABLE logs;
来源：http://dali.gogol.net.cn/Article/details/gt2hwxcbaui.html

[Q55] 排名（并列占位）
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2jxwmeblg.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.sysykeji.top/Article/details/gt2wftdwxed.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xylfe.cn/Article/details/gt2warldvrx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.316326.xyz/Article/details/gt2ujcepvhz.html

[Q57] 行号
来源：http://dali.wangshuangyany.cn/Article/details/gt2ijipqiyb.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2ltnuihnt.html

[Q58] 累计求和
来源：http://dali.smart0.xyz/Article/details/gt2pbjcembt.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xylfe.cn/Article/details/gt2nzyjfiyl.html

[Q59] 分组内累计
来源：http://dali.smart0.xyz/Article/details/gt2ruzrjebw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.c1oappe.top/Article/details/gt2fxzhetht.html

[Q60] 取上一行 / 下一行
来源：http://dali.aizwys.cn/Article/details/gt2dwsxhxbm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yonumen.top/Article/details/gt2xrlcsgme.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zycfv.cn/Article/details/gt2dlqmbvqx.html

[Q61] 移动平均
来源：http://dali.vqdsnc.cn/Article/details/gt2vvkrrbcd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xuanzx.com/Article/details/gt2zwuybizm.html

[Q62] 分组占比
来源：http://dali.feifeiyinyue.top/Article/details/gt2tqvbkinp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xinyue.icu/Article/details/gt2ezfzqxjj.html

[Q63] 开启事务
来源：http://dali.xziqi.cn/Article/details/gt2jwvhbemf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shanyushiyangtech.top/Article/details/gt2nhemdxus.html

[Q64] 提交事务
来源：http://dali.hammf.cn/Article/details/gt2nunrnpwl.html

COMMIT;
来源：http://dali.pengpengdd.cyou/Article/details/gt2rluxsowt.html

[Q65] 回滚事务
来源：http://dali.kuanghao11.cn/Article/details/gt2vxcbhsec.html

ROLLBACK;
来源：http://dali.nwbrower.top/Article/details/gt2wsetrrdi.html

[Q66] 行锁查询
来源：http://dali.xinyue.icu/Article/details/gt2ltpcflbf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jqgfzy.top/Article/details/gt2cqzhgwdz.html

[Q67] 设置隔离级别
来源：http://dali.aizwys.cn/Article/details/gt2wgxdbwqz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.pengpengdd.cyou/Article/details/gt2suxaltqx.html

[Q68] 保存点
来源：http://dali.kuanghao11.cn/Article/details/gt2hnabhwpx.html

SAVEPOINT sp1;
来源：http://dali.chenjidiqi.icu/Article/details/gt2yponpjfo.html

ROLLBACK TO sp1;
来源：http://dali.xuanzx.com/Article/details/gt2bwrxpdyh.html

[Q69] 查看执行计划
来源：http://dali.zhijiandao.cn/Article/details/gt2gefypdfh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.daria6918.cn/Article/details/gt2qhxllqxq.html

[Q70] 更新统计信息
来源：http://dali.xinyue.icu/Article/details/gt2ldqqrxts.html

ANALYZE TABLE users;
来源：http://dali.shangyingyoupin.top/Article/details/gt2bphhfljf.html

[Q71] 查看建表语句
来源：http://dali.yuxming.cn/Article/details/gt2isjbelbx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.guannengcc.top/Article/details/gt2jicphxsv.html

[Q72] 查看索引
来源：http://dali.9152youxi.cn/Article/details/gt2tzlocirz.html

SHOW INDEX FROM users;
来源：http://dali.ivvv.top/Article/details/gt2foixnllt.html

[Q73] 查看表状态
来源：http://dali.yvedp.cn/Article/details/gt2sskgexnv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2bkegegas.html

[Q74] 强制使用索引
来源：http://dali.jlsjyb.cn/Article/details/gt2iqwbhjto.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.haohaochexian.top/Article/details/gt2yffqrazj.html

[Q75] 日期格式化
来源：http://dali.shangyingyoupin.top/Article/details/gt2zlzfgggc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gt2hgzlvdnz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.wangdashe.top/Article/details/gt2ynalcbus.html

[Q76] 按天统计
来源：http://dali.zhoulong.xyz/Article/details/gt2qglinpab.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cucudq.cn/Article/details/gt2vyitkuhp.html

[Q77] 时间加减
来源：http://dali.nwbrower.top/Article/details/gt2tbwdbtqc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.fengsongda.top/Article/details/gt2ihqlikul.html

[Q78] 当前时间
来源：http://dali.jinqigufen.top/Article/details/gt2rmdqxees.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.havefunace.top/Article/details/gt2nfzdkzij.html

[Q79] 字符串拼接
来源：http://dali.jinghuilouyu.cn/Article/details/gt2hnlmcpsa.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.aibaodan.cn/Article/details/gt2vkglsonv.html

[Q80] 字符串截取
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2aztxdvkb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gt2pbxfiffy.html

[Q81] 字符串替换
来源：http://dali.yvedp.cn/Article/details/gt2ypehrpfa.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.9152youxi.cn/Article/details/gt2ttocjiec.html

[Q82] 字符长度与字节长度
来源：http://dali.yj20258888.top/Article/details/gt2ykafekel.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jyoumei.cn/Article/details/gt2gnfriuka.html

[Q83] 大小写转换
来源：http://dali.sxryk.cn/Article/details/gt2cwztujfn.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gt2lkudrpmr.html

[Q84] 去除首尾空格
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pywtiguk.html

SELECT TRIM(name) FROM users;
来源：http://dali.sufxvd.cn/Article/details/gt2ybtpvfoa.html

[Q85] 数值取整
来源：http://dali.hongshengwenyu.top/Article/details/gt2kftocmip.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gaohongyu789.top/Article/details/gt2wemjevqz.html

[Q86] 读取 JSON 字段
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2jeoodoyb.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cdnleiting.top/Article/details/gt2fliloitv.html

[Q87] JSON 字段做条件
来源：http://dali.zycfv.cn/Article/details/gt2xgxwhfws.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shzxlz.cn/Article/details/gt2ugvcavzk.html

[Q88] 行转列（条件聚合）
来源：http://dali.zycfv.cn/Article/details/gt2dekwpedw.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.daxiang520.top/Article/details/gt2oeocyrog.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cdnleiting.top/Article/details/gt2ieriktbz.html

[Q89] 判断表是否存在
来源：http://dali.redwolf501.top/Article/details/gt2alzdioxx.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nanxinkj.top/Article/details/gt2dketdjab.html

[Q90] 生成序号列
来源：http://dali.316326.xyz/Article/details/gt2agwqhqyb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.mhx1999.top/Article/details/gt2cjkdvttc.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gt2gchwxumu.html

R. Bash 专题
来源：http://dali.gaohongyu789.top/Article/details/gt2ormwmemu.html

================================================================================
来源：http://dali.bjfxy.top/Article/details/gt2vfpylvwu.html

[R01] shebang 与严格模式
来源：http://dali.zycfv.cn/Article/details/gt2nqbtzewq.html

#!/usr/bin/env bash
来源：http://dali.zhongyouzk.top/Article/details/gt2giwqjnhr.html

set -euo pipefail
来源：http://dali.hywenlv.cn/Article/details/gt2tdvuavzm.html

[R02] 变量赋值与使用
来源：http://dali.jianghu66.top/Article/details/gt2aahoqbmr.html

name="Tom"; echo "$name"
来源：http://dali.fzhhl.top/Article/details/gt2iyticmlr.html

[R03] 只读变量
来源：http://dali.shuidangran.top/Article/details/gt2pquxxfwy.html

readonly PI=3.14
来源：http://dali.yueranfly.top/Article/details/gt2sbuoogen.html

[R04] 位置参数
来源：http://dali.meibo888.top/Article/details/gt2jstvfnjr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xvsyvltk.html

[R05] 参数默认值
来源：http://dali.zhongyouzk.top/Article/details/gt2chywtmzr.html

name="${1:-default}"
来源：http://dali.ppjwa.cn/Article/details/gt2aegdngld.html

[R06] 判断命令是否存在
来源：http://dali.yongpay.top/Article/details/gt2nvkgysmr.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.dashuyun.cn/Article/details/gt2zraabtos.html

[R07] if 判断文件
来源：http://dali.nanxuanxn.top/Article/details/gt2tmhzjyvh.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.daxiang520.top/Article/details/gt2fmwmegwp.html

[R08] 数值比较
来源：http://dali.daria6918.cn/Article/details/gt2uzqljzcg.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hysaishi.cn/Article/details/gt2ruxgtwvi.html

[R09] 字符串比较
来源：http://dali.cdnleiting.top/Article/details/gt2yfwnoeru.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.nanxinkj.top/Article/details/gt2biocqzfe.html

[R10] 正则匹配
来源：http://dali.cdnleiting.top/Article/details/gt2edccfmjp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.daria6918.cn/Article/details/gt2rphfbgjv.html

[R11] case 多分支
来源：http://dali.sxryk.cn/Article/details/gt2gsbpaudb.html

case "$1" in
来源：http://dali.birdmap.top/Article/details/gt2pjbhgtyq.html

start) echo "启动" ;;
来源：http://dali.yueranfly.top/Article/details/gt2ydhtnalr.html

stop)  echo "停止" ;;
来源：http://dali.smart0.xyz/Article/details/gt2qxiceukc.html

*)     echo "未知命令" ;;
来源：http://dali.jlsjyb.cn/Article/details/gt2bkgbjlmx.html

esac
来源：http://dali.dianchejie.cn/Article/details/gt2cymkiekz.html

[R12] for 遍历文件
来源：http://dali.hnqzz.top/Article/details/gt2dhosywqu.html

for f in *.txt; do echo "$f"; done
来源：http://dali.chenlongwang.top/Article/details/gt2vtqjmyuu.html

[R13] for 计数循环
来源：http://dali.sxryk.cn/Article/details/gt2krsiresn.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhoulong.xyz/Article/details/gt2rfebrnaj.html

[R14] C 风格 for
来源：http://dali.nanxinkj.top/Article/details/gt2wbhamhhf.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hongshengwenyu.top/Article/details/gt2plbhosto.html

[R15] while 逐行读文件
来源：http://dali.zhijiandao.cn/Article/details/gt2jqfctlhz.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.quarkkingdee.top/Article/details/gt2kcrdlvfm.html

[R16] until 等待条件
来源：http://dali.yonumen.top/Article/details/gt2tlydeqhs.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhijiandao.cn/Article/details/gt2tseigwof.html

[R17] 数组定义与取值
来源：http://dali.jianghu66.top/Article/details/gt2eaunjbmq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.gzhubu.top/Article/details/gt2ptcpeauk.html

[R18] 遍历数组
来源：http://dali.316326.xyz/Article/details/gt2jwoudkns.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hnxiangtu.top/Article/details/gt2edztwaas.html

[R19] 数组长度
来源：http://dali.jlsjyb.cn/Article/details/gt2kegspufa.html

echo "${#arr[@]}"
来源：http://dali.dashuyun.cn/Article/details/gt2brlcvhte.html

[R20] 关联数组（字典）
来源：http://dali.shanyushiyangtech.top/Article/details/gt2amdylwcu.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cheryme.top/Article/details/gt2slbavvdn.html

[R21] 字符串长度
来源：http://dali.zhijiandao.cn/Article/details/gt2ybbgtcjo.html

echo "${#s}"
来源：http://dali.ydzc1.top/Article/details/gt2kaxxemnb.html

[R22] 截取子串
来源：http://dali.meibo888.top/Article/details/gt2zgqgulwe.html

echo "${s:0:5}"
来源：http://dali.ybcxt.top/Article/details/gt2ivviasks.html

[R23] 字符串替换
来源：http://dali.yueranfly.top/Article/details/gt2bhwavkdb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.yangfankeji.com/Article/details/gt2unikpqch.html

[R24] 大小写转换
来源：http://dali.snrcjt.cn/Article/details/gt2yutfmdlb.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jiagoushi.top/Article/details/gt2aetsijcy.html

[R25] 去后缀 / 去前缀
来源：http://dali.316326.xyz/Article/details/gt2qqxiqqyb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ppjwa.cn/Article/details/gt2kahmktva.html

[R26] 命令替换
来源：http://dali.hongshengwenyu.top/Article/details/gt2xwuzpxub.html

now=$(date +%F); echo "$now"
来源：http://dali.yj20258888.top/Article/details/gt2zccixumi.html

[R27] 算术展开
来源：http://dali.yueranfly.top/Article/details/gt2ipwsztam.html

echo $((1 + 2 * 3))
来源：http://dali.zhongyouzk.top/Article/details/gt2smwaohqw.html

[R28] 浮点运算
来源：http://dali.yueranfly.top/Article/details/gt2ckbvcqdh.html

echo "scale=2; 10/3" | bc
来源：http://dali.zhixingplan.top/Article/details/gt2vtrtyphc.html

[R29] 定义函数
来源：http://dali.zycfv.cn/Article/details/gt2uvypuggb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xuanzx.com/Article/details/gt2ttzlomgr.html

[R30] 函数返回状态码
来源：http://dali.pengpengdd.cyou/Article/details/gt2wszplbjj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhijiandao.cn/Article/details/gt2fiudkufn.html

[R31] 局部变量
来源：http://dali.xuetiantiany.cn/Article/details/gt2fdupavzk.html

f() { local x=1; echo "$x"; }
来源：http://dali.ivvv.top/Article/details/gt2lvkxrvwo.html

[R32] 参数个数校验
来源：http://dali.yj20258.top/Article/details/gt2opgbbkvm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.snrcjt.cn/Article/details/gt2bgofhcgm.html

[R33] 捕获错误并提示行号
来源：http://dali.xinyue.icu/Article/details/gt2idongyuj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yueranfly.top/Article/details/gt2aurdzidv.html

[R34] 退出时清理
来源：http://dali.xuetiantiany.cn/Article/details/gt2slilwwkh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hywenlv.cn/Article/details/gt2qrnjwjwt.html

[R35] 后台执行并等待
来源：http://dali.guannengcc.top/Article/details/gt2xckbckzu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ydzc1.top/Article/details/gt2gdqnvvah.html

[R36] 并发执行多个任务
来源：http://dali.jqgufenzy.top/Article/details/gt2ffftxpiz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.cqqwz.cn/Article/details/gt2hecwiilg.html

[R37] 把输出赋给变量
来源：http://dali.jlsjyb.cn/Article/details/gt2zdlldnaw.html

files=$(ls -1)
来源：http://dali.yvedp.cn/Article/details/gt2iqxukqvi.html

[R38] 管道串联
来源：http://dali.jinghuilouyu.cn/Article/details/gt2wdxeuvbe.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ivvv.top/Article/details/gt2czrfrsvb.html

[R39] 重定向标准输出与错误
来源：http://dali.andypj.xyz/Article/details/gt2jyjupdrd.html

cmd > out.log 2>&1
来源：http://dali.ybcxt.top/Article/details/gt2yhzeodsv.html

[R40] 追加写日志
来源：http://dali.zhongyouzk.top/Article/details/gt2cxvjikme.html

echo "log" >> out.log
来源：http://dali.yj20258888.top/Article/details/gt2bbtpwkhd.html

[R41] 丢弃输出
来源：http://dali.shuidangran.top/Article/details/gt2vqcuysyc.html

cmd >/dev/null 2>&1
来源：http://dali.sysykeji.top/Article/details/gt2ekuwanlx.html

[R42] 输入重定向
来源：http://dali.hywenlv.cn/Article/details/gt2nlrlrjxt.html

wc -l < a.txt
来源：http://dali.bjfxy.top/Article/details/gt2rjtnmqbo.html

[R43] 按名字查找文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2yigvwbrl.html

find . -name "*.log" -type f
来源：http://dali.cashguo.top/Article/details/gt2cfcxvzjb.html

[R44] 按修改时间查找
来源：http://dali.dashuyun.cn/Article/details/gt2johtlvxr.html

find . -mtime -7 -type f
来源：http://dali.chenjidiqi.icu/Article/details/gt2ghxsigzn.html

[R45] 批量删除
来源：http://dali.hywenlv.cn/Article/details/gt2hyhtyjyp.html

find . -name "*.tmp" -delete
来源：http://dali.bjfxy.top/Article/details/gt2hbqbheot.html

[R46] 递归替换文件内容
来源：http://dali.yangfankeji.com/Article/details/gt2natzbmdw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.redwolf501.top/Article/details/gt2bzrutarx.html

[R47] sed 单行替换
来源：http://dali.wangdashe.top/Article/details/gt2gbtzrwoh.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.iojbl.cn/Article/details/gt2rhhtduff.html

[R48] awk 取指定列
来源：http://dali.cheryme.top/Article/details/gt2tkixxhhn.html

awk '{print $1, $3}' a.txt
来源：http://dali.tianlin.xyz/Article/details/gt2nqunqocp.html

[R49] awk 带条件
来源：http://dali.ppjwa.cn/Article/details/gt2ahynaafr.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jqgfzy.top/Article/details/gt2rycxjhrf.html

[R50] awk 求和
来源：http://dali.xuetiantiany.cn/Article/details/gt2zpoqvktf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sysykeji.top/Article/details/gt2ivnikbrk.html

[R51] 排序去重取前几
来源：http://dali.9152youxi.cn/Article/details/gt2sktsuxkv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.fengsongda.top/Article/details/gt2tanwsunc.html

[R52] 统计行数
来源：http://dali.shanyushiyangtech.top/Article/details/gt2cltppvzl.html

wc -l a.txt
来源：http://dali.tianlin.xyz/Article/details/gt2hcuqdtgi.html

[R53] 查看文件头与实时尾
来源：http://dali.zhixingplan.top/Article/details/gt2bnlwegaz.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gzhubu.top/Article/details/gt2pmuxmxzl.html

[R54] 比较两个文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2pknuddnv.html

diff a.txt b.txt
来源：http://dali.dianchejie.cn/Article/details/gt2wqeuwwmd.html

[R55] 压缩与解压
来源：http://dali.jiagoushi.top/Article/details/gt2fuvkbpkr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.c1oappe.top/Article/details/gt2kktrdxtk.html

[R56] 远程拷贝
来源：http://dali.cqqwz.cn/Article/details/gt2eifuwjga.html

scp file user@host:/path/
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2ymqtiuix.html

[R57] 远程执行命令
来源：http://dali.jianghu66.top/Article/details/gt2osixdwqz.html

ssh user@host 'uptime'
来源：http://dali.9152youxi.cn/Article/details/gt2mdybzxcg.html

[R58] 下载文件
来源：http://dali.hfpthk.cn/Article/details/gt2ipizbvyv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xuanzx.com/Article/details/gt2fvqfyxuk.html

[R59] 发 POST JSON
来源：http://dali.ydzc1.top/Article/details/gt2stcntvgi.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ppjwa.cn/Article/details/gt2dceforii.html

[R60] 只看 HTTP 状态码
来源：http://dali.yuanzhike.top/Article/details/gt2oedwddwf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hnqzz.top/Article/details/gt2nnotefim.html

[R61] 磁盘占用
来源：http://dali.xuetiantiany.cn/Article/details/gt2xhgasmni.html


<!-- 参考信息 -->