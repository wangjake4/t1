代发 wailian999

INSERT INTO users (name) VALUES ('C');
来源：http://dali.nanxinkj.top/Article/details/gt2nnwxzbwl.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2rjiykuhw.html

[Q13] 忽略重复插入
来源：http://dali.ehwqpu.com/Article/details/gt2tdqnppqw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2itbjajfg.html

[Q14] 存在则更新（upsert）
来源：http://dali.hfpthk.cn/Article/details/gt2kmjhrrtk.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.birdmap.top/Article/details/gt2rfoeefpb.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.hywenlv.cn/Article/details/gt2rsejebwp.html

[Q15] 查询全部
来源：http://dali.zhiwuduotai.top/Article/details/gt2npgryqfw.html

SELECT * FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2jpweqdem.html

[Q16] 查询指定列
来源：http://dali.yuxming.cn/Article/details/gt2wxrbfksz.html

SELECT id, name FROM users;
来源：http://dali.ehwqpu.com/Article/details/gt2dywbykca.html

[Q17] 条件查询
来源：http://dali.shuidangran.top/Article/details/gt2npulqqyf.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ejikvtxz.html

[Q18] 模糊匹配
来源：http://dali.iojbl.cn/Article/details/gt2ffcciezg.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yj20258888.top/Article/details/gt2wkpobkcg.html

[Q19] 范围查询
来源：http://dali.dianchejie.cn/Article/details/gt2cbxjwovh.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.chenzaomai.com/Article/details/gt2adftriub.html

[Q20] IN 列表
来源：http://dali.tianlin.xyz/Article/details/gt2bohbggyt.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.cheryme.top/Article/details/gt2ipeqcbqw.html

[Q21] 空值判断
来源：http://dali.hnqzz.top/Article/details/gt2bycagrga.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.ehwqpu.com/Article/details/gt2xwnihsda.html

[Q22] 排序
来源：http://dali.shuidangran.top/Article/details/gt2vsvzpwjt.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.sxryk.cn/Article/details/gt2pnmefsum.html

[Q23] 分页
来源：http://dali.wangshuangyany.cn/Article/details/gt2cftotrpc.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhiwuduotai.top/Article/details/gt2mrotnlwe.html

[Q24] 去重
来源：http://dali.zhijiandao.cn/Article/details/gt2rpupjalv.html

SELECT DISTINCT city FROM users;
来源：http://dali.birdmap.top/Article/details/gt2idayfngw.html

[Q25] 只取前 N 条
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2ipojyrhm.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.zhengqikj.top/Article/details/gt2jpzyktqc.html

[Q26] 计数
来源：http://dali.shzxlz.cn/Article/details/gt2ihnkwlxa.html

SELECT COUNT(*) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2bnwkudlt.html

[Q27] 条件计数
来源：http://dali.ppjwa.cn/Article/details/gt2afyrzlnd.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2kywlqmbg.html

[Q28] 求和与平均
来源：http://dali.zhijiandao.cn/Article/details/gt2banwkscr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gt2yxilqota.html

[Q29] 最大最小值
来源：http://dali.zhengqikj.top/Article/details/gt2oklrnznr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gt2jilsmxmq.html

[Q30] 分组统计
来源：http://dali.snrcjt.cn/Article/details/gt2zujjmofc.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2mmcnqbri.html

[Q31] 分组后过滤
来源：http://dali.jinqigufen.top/Article/details/gt2ibiscchj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yonumen.top/Article/details/gt2zzutrivb.html

[Q32] 分组拼接字符串
来源：http://dali.guowangkeji.top/Article/details/gt2zdlptbgu.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.zhengqikj.top/Article/details/gt2vmkzgdqq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhixingplan.top/Article/details/gt2bwexfxln.html

[Q33] 多列分组
来源：http://dali.nanxuanxn.top/Article/details/gt2pfjibazm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.guannengcc.top/Article/details/gt2uyoptvtg.html

[Q34] 每组取第一条
来源：http://dali.ppjwa.cn/Article/details/gt2pwvzluhr.html

SELECT * FROM (
来源：http://dali.xziqi.cn/Article/details/gt2egmemqfk.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yuanzhike.top/Article/details/gt2yhlholxp.html

) t WHERE rn = 1;
来源：http://dali.chenlongwang.top/Article/details/gt2fqjstzja.html

[Q35] 内连接
来源：http://dali.cheryme.top/Article/details/gt2qgiswebn.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gogol.net.cn/Article/details/gt2jovwwguc.html

[Q36] 左连接
来源：http://dali.yuxming.cn/Article/details/gt2attzvjml.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.sysykeji.top/Article/details/gt2yrjameic.html

[Q37] 右连接
来源：http://dali.quarkkingdee.top/Article/details/gt2sepvpoqe.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.chenzaomai.com/Article/details/gt2fcncyhls.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yueranfly.top/Article/details/gt2kytrugdy.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shuidangran.top/Article/details/gt2lddbmdrr.html

[Q39] 自连接（查上下级）
来源：http://dali.chenlongwang.top/Article/details/gt2yypojsea.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yonumen.top/Article/details/gt2hymicsvz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zdqjudy.top/Article/details/gt2ncrgvxed.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gotoacloud.top/Article/details/gt2qmgplyia.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xinyue.icu/Article/details/gt2ylosvxvu.html

[Q41] 多表连接
来源：http://dali.yuanzhike.top/Article/details/gt2gkhfkjpk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ybcxt.top/Article/details/gt2zsgdbqdw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.guowangkeji.top/Article/details/gt2naxcchis.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.nwbrower.top/Article/details/gt2moyxgrdn.html

[Q42] 连接条件附加过滤
来源：http://dali.shzxlz.cn/Article/details/gt2gimnwizf.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zdqjudy.top/Article/details/gt2cvcuefef.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.iojbl.cn/Article/details/gt2amlowvwn.html

[Q43] 标量子查询
来源：http://dali.jinqigfzy.top/Article/details/gt2skaxckjp.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.c1oappe.top/Article/details/gt2efefmzga.html

[Q44] IN 子查询
来源：http://dali.shuidangran.top/Article/details/gt2nionfiio.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yj202588.top/Article/details/gt2hqdtzhno.html

[Q45] EXISTS 判断存在
来源：http://dali.xuetiantiany.cn/Article/details/gt2becywtvo.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2xiitbzrh.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.c1oappe.top/Article/details/gt2nvlwnvye.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cashguo.top/Article/details/gt2kgbzrozv.html

[Q47] 与平均值比较
来源：http://dali.guannengcc.top/Article/details/gt2keiqlnzd.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zdqjudy.top/Article/details/gt2hohcvmzl.html

[Q48] CTE 公用表表达式
来源：http://dali.tian-w.cn/Article/details/gt2zkwcaxue.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jqgufenzy.top/Article/details/gt2wxjwodfw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sweek.top/Article/details/gt2oueuresd.html

[Q49] 更新单行
来源：http://dali.snrcjt.cn/Article/details/gt2ssmbhtst.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.hysaishi.cn/Article/details/gt2xmfmmulz.html

[Q50] 批量更新
来源：http://dali.jiagoushi.top/Article/details/gt2ooqhamyz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xylfe.cn/Article/details/gt2fiilqmwf.html

[Q51] 用子查询更新
来源：http://dali.316326.xyz/Article/details/gt2swutwqgf.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.chenjidiqi.icu/Article/details/gt2ubvxmofl.html

[Q52] 删除指定行
来源：http://dali.yj202588.top/Article/details/gt2spuogpyo.html

DELETE FROM users WHERE id = 10;
来源：http://dali.gotoacloud.top/Article/details/gt2oyqjksgd.html

[Q53] 按条件删除
来源：http://dali.hysaishi.cn/Article/details/gt2oywrwgda.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.c1oappe.top/Article/details/gt2urildzkc.html

[Q54] 清空表
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2lmasjrya.html

TRUNCATE TABLE logs;
来源：http://dali.wangshuangyany.cn/Article/details/gt2ohnirlxt.html

[Q55] 排名（并列占位）
来源：http://dali.yangfankeji.com/Article/details/gt2oxokocvk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.0kj1m.cn/Article/details/gt2umwzbcna.html

[Q56] 密集排名（并列不占位）
来源：http://dali.kuanghao11.cn/Article/details/gt2rzpfyemd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xinyue.icu/Article/details/gt2szvdxkir.html

[Q57] 行号
来源：http://dali.ppjwa.cn/Article/details/gt2abseoeaf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cheryme.top/Article/details/gt2aiimzqcj.html

[Q58] 累计求和
来源：http://dali.ivvv.top/Article/details/gt2sudypxil.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gt2vpxnbuhh.html

[Q59] 分组内累计
来源：http://dali.yonumen.top/Article/details/gt2djxgvgel.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gt2qhhryjpr.html

[Q60] 取上一行 / 下一行
来源：http://dali.yueranfly.top/Article/details/gt2onxtwavh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.kuanghao11.cn/Article/details/gt2npzzzqds.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.316326.xyz/Article/details/gt2dtejplpm.html

[Q61] 移动平均
来源：http://dali.jlsjyb.cn/Article/details/gt2sfybmkhy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2axtutack.html

[Q62] 分组占比
来源：http://dali.cashguo.top/Article/details/gt2bxpvdkgp.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.chenjidiqi.icu/Article/details/gt2vepiijzt.html

[Q63] 开启事务
来源：http://dali.jlsjyb.cn/Article/details/gt2lfnlsryf.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.vqdsnc.cn/Article/details/gt2anatzsgf.html

[Q64] 提交事务
来源：http://dali.chenzaomai.com/Article/details/gt2tpsqpaqp.html

COMMIT;
来源：http://dali.aizwys.cn/Article/details/gt2nlidowkv.html

[Q65] 回滚事务
来源：http://dali.shzxlz.cn/Article/details/gt2fopvxqpf.html

ROLLBACK;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2fhrniomy.html

[Q66] 行锁查询
来源：http://dali.ppjwa.cn/Article/details/gt2xavcemcm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.gogol.net.cn/Article/details/gt2melagtnb.html

[Q67] 设置隔离级别
来源：http://dali.hysaishi.cn/Article/details/gt2mjsxsuhy.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.aibaodan.cn/Article/details/gt2hgpqvedr.html

[Q68] 保存点
来源：http://dali.sufxvd.cn/Article/details/gt2iirofrun.html

SAVEPOINT sp1;
来源：http://dali.jinghuilouyu.cn/Article/details/gt2whyrlqqy.html

ROLLBACK TO sp1;
来源：http://dali.sxryk.cn/Article/details/gt2ysgferig.html

[Q69] 查看执行计划
来源：http://dali.gogol.net.cn/Article/details/gt2pdaayiyi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yuanzhike.top/Article/details/gt2qdcbhtlz.html

[Q70] 更新统计信息
来源：http://dali.mhx1999.top/Article/details/gt2izpjiozg.html

ANALYZE TABLE users;
来源：http://dali.zhongyouzk.top/Article/details/gt2shsvysct.html

[Q71] 查看建表语句
来源：http://dali.yj202588.top/Article/details/gt2zrcybyrl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2shrhugzb.html

[Q72] 查看索引
来源：http://dali.dianchejie.cn/Article/details/gt2jlnzrhly.html

SHOW INDEX FROM users;
来源：http://dali.xylfe.cn/Article/details/gt2ytyvfaqm.html

[Q73] 查看表状态
来源：http://dali.yj202588.top/Article/details/gt2mngaazcn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.tian-w.cn/Article/details/gt2vhtrogqz.html

[Q74] 强制使用索引
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2nixvssgf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.nanxuanxn.top/Article/details/gt2sycedlwi.html

[Q75] 日期格式化
来源：http://dali.kuanghao11.cn/Article/details/gt2wmfuyvzw.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gt2ngvlpbxr.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.daxiang520.top/Article/details/gt2gehucroc.html

[Q76] 按天统计
来源：http://dali.nanxinkj.top/Article/details/gt2yhfrzztu.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.aizwys.cn/Article/details/gt2uwshxorv.html

[Q77] 时间加减
来源：http://dali.redwolf501.top/Article/details/gt2pytpxrxs.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.meibo888.top/Article/details/gt2ccwmhlxj.html

[Q78] 当前时间
来源：http://dali.jqgufenzy.top/Article/details/gt2gvtiivzt.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhongyouzk.top/Article/details/gt2hafvhyja.html

[Q79] 字符串拼接
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2kjlpjwwt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.havefunace.top/Article/details/gt2jqlesadm.html

[Q80] 字符串截取
来源：http://dali.wangdashe.top/Article/details/gt2jwpskjwj.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2uqfplbgy.html

[Q81] 字符串替换
来源：http://dali.ybcxt.top/Article/details/gt2mmxmgwvx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.pycfn.com/Article/details/gt2wqdurqcu.html

[Q82] 字符长度与字节长度
来源：http://dali.cdnleiting.top/Article/details/gt2luflqrhw.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gt2qmmknyxj.html

[Q83] 大小写转换
来源：http://dali.jqgufenzy.top/Article/details/gt2ntrolzex.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gt2bmirezlo.html

[Q84] 去除首尾空格
来源：http://dali.nanxuanxn.top/Article/details/gt2wfvusrdp.html

SELECT TRIM(name) FROM users;
来源：http://dali.xuanzx.com/Article/details/gt2iweycuzg.html

[Q85] 数值取整
来源：http://dali.yj20258888.top/Article/details/gt2osvvggco.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.haohaochexian.top/Article/details/gt2hqvvxkuh.html

[Q86] 读取 JSON 字段
来源：http://dali.yangfankeji.com/Article/details/gt2hsmlmrmd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.ppjwa.cn/Article/details/gt2mtvlojrd.html

[Q87] JSON 字段做条件
来源：http://dali.hammf.cn/Article/details/gt2hdfwifqk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.ivvv.top/Article/details/gt2yybtmzbr.html

[Q88] 行转列（条件聚合）
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2eqjwkrhe.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.sxryk.cn/Article/details/gt2xsicgxre.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2etbufflj.html

[Q89] 判断表是否存在
来源：http://dali.ehwqpu.com/Article/details/gt2dymrapqb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2vrctiubl.html

[Q90] 生成序号列
来源：http://dali.hongshengwenyu.top/Article/details/gt2gbcpcpvm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.tanke756.top/Article/details/gt2ldwtrovt.html

================================================================================
来源：http://dali.sxryk.cn/Article/details/gt2uerobmfb.html

R. Bash 专题
来源：http://dali.zdqjudy.top/Article/details/gt2tijdghvx.html

================================================================================
来源：http://dali.tanke756.top/Article/details/gt2oyeogyvw.html

[R01] shebang 与严格模式
来源：http://dali.vqdsnc.cn/Article/details/gt2vzqvszue.html

#!/usr/bin/env bash
来源：http://dali.yj20258.top/Article/details/gt2akebewax.html

set -euo pipefail
来源：http://dali.yuanzhike.top/Article/details/gt2mzdrycxr.html

[R02] 变量赋值与使用
来源：http://dali.hongshengwenyu.top/Article/details/gt2tavqejof.html

name="Tom"; echo "$name"
来源：http://dali.iojbl.cn/Article/details/gt2ocjohvqc.html

[R03] 只读变量
来源：http://dali.316326.xyz/Article/details/gt2jvpinjvs.html

readonly PI=3.14
来源：http://dali.snrcjt.cn/Article/details/gt2lyponqyj.html

[R04] 位置参数
来源：http://dali.pycfn.com/Article/details/gt2ubqhmebi.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.pycfn.com/Article/details/gt2hkjjbark.html

[R05] 参数默认值
来源：http://dali.haohaochexian.top/Article/details/gt2sqsxfcif.html

name="${1:-default}"
来源：http://dali.xziqi.cn/Article/details/gt2nmtpmogr.html

[R06] 判断命令是否存在
来源：http://dali.jyoumei.cn/Article/details/gt2sgkdyrkm.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.meibo888.top/Article/details/gt2ngyykwdb.html

[R07] if 判断文件
来源：http://dali.yuanzhike.top/Article/details/gt2hgtiaxry.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.iojbl.cn/Article/details/gt2mjvqlctp.html

[R08] 数值比较
来源：http://dali.aibaodan.cn/Article/details/gt2tgxdvfer.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.mhx1999.top/Article/details/gt2ujueraqd.html

[R09] 字符串比较
来源：http://dali.tianlin.xyz/Article/details/gt2boeqorgw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.guannengcc.top/Article/details/gt2bkiquydj.html

[R10] 正则匹配
来源：http://dali.birdmap.top/Article/details/gt2fiiluuud.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.haohaochexian.top/Article/details/gt2irffacuw.html

[R11] case 多分支
来源：http://dali.sysykeji.top/Article/details/gt2ebxljxmq.html

case "$1" in
来源：http://dali.ehwqpu.com/Article/details/gt2xjqeveoe.html

start) echo "启动" ;;
来源：http://dali.zhiwuduotai.top/Article/details/gt2lququgvk.html

stop)  echo "停止" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gt2uqzakuyj.html

*)     echo "未知命令" ;;
来源：http://dali.redwolf501.top/Article/details/gt2ohtbvbzd.html

esac
来源：http://dali.jianghu66.top/Article/details/gt2swqvmqbw.html

[R12] for 遍历文件
来源：http://dali.aibaodan.cn/Article/details/gt2nxlxownh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.wangshuangyany.cn/Article/details/gt2xvhadgfb.html

[R13] for 计数循环
来源：http://dali.jyoumei.cn/Article/details/gt2xorsjsdf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.c1oappe.top/Article/details/gt2nbirlzxw.html

[R14] C 风格 for
来源：http://dali.yj20258.top/Article/details/gt2sejseuvp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sysykeji.top/Article/details/gt2dhzbthwd.html

[R15] while 逐行读文件
来源：http://dali.zhiwuduotai.top/Article/details/gt2ysautymp.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.feifeiyinyue.top/Article/details/gt2sbehefcg.html

[R16] until 等待条件
来源：http://dali.bjfxy.top/Article/details/gt2cuhhndlx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.guowangkeji.top/Article/details/gt2ymdsvqvk.html

[R17] 数组定义与取值
来源：http://dali.ybcxt.top/Article/details/gt2hvqyakwc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.tian-w.cn/Article/details/gt2gafbecav.html

[R18] 遍历数组
来源：http://dali.nwbrower.top/Article/details/gt2wdfmizun.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yuanzhike.top/Article/details/gt2rzbbowup.html

[R19] 数组长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gt2uptldtdn.html

echo "${#arr[@]}"
来源：http://dali.hnxiangtu.top/Article/details/gt2kqqgrsgt.html

[R20] 关联数组（字典）
来源：http://dali.ybcxt.top/Article/details/gt2hwnptcau.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.daria6918.cn/Article/details/gt2xxccfnxc.html

[R21] 字符串长度
来源：http://dali.ppjwa.cn/Article/details/gt2ngtqbchr.html

echo "${#s}"
来源：http://dali.hongshengwenyu.top/Article/details/gt2nvokuivi.html

[R22] 截取子串
来源：http://dali.sxryk.cn/Article/details/gt2oemhvjsd.html

echo "${s:0:5}"
来源：http://dali.hammf.cn/Article/details/gt2qmnpxjbr.html

[R23] 字符串替换
来源：http://dali.birdmap.top/Article/details/gt2bgckfmcf.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gogol.net.cn/Article/details/gt2fcknnsxs.html

[R24] 大小写转换
来源：http://dali.sweek.top/Article/details/gt2bpuzpfif.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.birdmap.top/Article/details/gt2rolutohn.html

[R25] 去后缀 / 去前缀
来源：http://dali.zycfv.cn/Article/details/gt2zlrgiigq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hfpthk.cn/Article/details/gt2fwsklwnm.html

[R26] 命令替换
来源：http://dali.yonumen.top/Article/details/gt2episneon.html

now=$(date +%F); echo "$now"
来源：http://dali.fengsongda.top/Article/details/gt2vadksnzl.html

[R27] 算术展开
来源：http://dali.chenjidiqi.icu/Article/details/gt2uewuhwhe.html

echo $((1 + 2 * 3))
来源：http://dali.havefunace.top/Article/details/gt2plcoqnyp.html

[R28] 浮点运算
来源：http://dali.jinqigfzy.top/Article/details/gt2dkhrmgxv.html

echo "scale=2; 10/3" | bc
来源：http://dali.guowangkeji.top/Article/details/gt2ljcwmxep.html

[R29] 定义函数
来源：http://dali.xuetiantiany.cn/Article/details/gt2xvuzguwo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.wangshuangyany.cn/Article/details/gt2rknhcncu.html

[R30] 函数返回状态码
来源：http://dali.andypj.xyz/Article/details/gt2onqgcdgq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.aizwys.cn/Article/details/gt2mmesioox.html

[R31] 局部变量
来源：http://dali.hnxiangtu.top/Article/details/gt2kbjswjvq.html

f() { local x=1; echo "$x"; }
来源：http://dali.chenjidiqi.icu/Article/details/gt2tfrdtceo.html

[R32] 参数个数校验
来源：http://dali.chenzaomai.com/Article/details/gt2vfgqgspt.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ivvv.top/Article/details/gt2ozglxhdj.html

[R33] 捕获错误并提示行号
来源：http://dali.jinqigfzy.top/Article/details/gt2ovrvzzmg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2dtrgjehi.html

[R34] 退出时清理
来源：http://dali.dashuyun.cn/Article/details/gt2byfwavnn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuxming.cn/Article/details/gt2fenwyjzy.html

[R35] 后台执行并等待
来源：http://dali.quarkkingdee.top/Article/details/gt2yrlzjjym.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.fzhhl.top/Article/details/gt2gvguehdk.html

[R36] 并发执行多个任务
来源：http://dali.cqqwz.cn/Article/details/gt2frebeqxg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hysaishi.cn/Article/details/gt2fjgatdam.html

[R37] 把输出赋给变量
来源：http://dali.yj20258888.top/Article/details/gt2ekxvodrs.html

files=$(ls -1)
来源：http://dali.ehwqpu.com/Article/details/gt2aiekqgjd.html

[R38] 管道串联
来源：http://dali.havefunace.top/Article/details/gt2wybvdxqr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hnqzz.top/Article/details/gt2uijxrdfq.html

[R39] 重定向标准输出与错误
来源：http://dali.fengsongda.top/Article/details/gt2eehggcsw.html

cmd > out.log 2>&1
来源：http://dali.tianlin.xyz/Article/details/gt2xkiltuus.html

[R40] 追加写日志
来源：http://dali.xuanzx.com/Article/details/gt2woyzqxpv.html

echo "log" >> out.log
来源：http://dali.hnqzz.top/Article/details/gt2iasvwcyh.html

[R41] 丢弃输出
来源：http://dali.yj20258.top/Article/details/gt2axfsepdw.html

cmd >/dev/null 2>&1
来源：http://dali.chenjidiqi.icu/Article/details/gt2nvrmkukg.html

[R42] 输入重定向
来源：http://dali.aizwys.cn/Article/details/gt2tsucwcag.html

wc -l < a.txt
来源：http://dali.zdqjudy.top/Article/details/gt2tmbdcyat.html

[R43] 按名字查找文件
来源：http://dali.fengsongda.top/Article/details/gt2vfrjtvle.html

find . -name "*.log" -type f
来源：http://dali.ybcxt.top/Article/details/gt2yzdhmpfo.html

[R44] 按修改时间查找
来源：http://dali.zhijiandao.cn/Article/details/gt2rrpmkqtq.html

find . -mtime -7 -type f
来源：http://dali.tanke756.top/Article/details/gt2dtxdofhh.html

[R45] 批量删除
来源：http://dali.gogol.net.cn/Article/details/gt2bxsblhci.html

find . -name "*.tmp" -delete
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2anhtazyn.html

[R46] 递归替换文件内容
来源：http://dali.yueranfly.top/Article/details/gt2esfpcazu.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinqigufen.top/Article/details/gt2xgfgarmw.html

[R47] sed 单行替换
来源：http://dali.fzhhl.top/Article/details/gt2vkgpzras.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.hfpthk.cn/Article/details/gt2jujprlxz.html

[R48] awk 取指定列
来源：http://dali.yvedp.cn/Article/details/gt2olhvxlxj.html

awk '{print $1, $3}' a.txt
来源：http://dali.smart0.xyz/Article/details/gt2mnomutnf.html

[R49] awk 带条件
来源：http://dali.zhoulong.xyz/Article/details/gt2klurubat.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ywan-chungtsiang.top/Article/details/gt2tbzkuhpi.html

[R50] awk 求和
来源：http://dali.shangyingyoupin.top/Article/details/gt2zbsecsfy.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yongpay.top/Article/details/gt2usidheap.html

[R51] 排序去重取前几
来源：http://dali.ivvv.top/Article/details/gt2wbenrtib.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yj20258888.top/Article/details/gt2xuklrgin.html

[R52] 统计行数
来源：http://dali.hnqzz.top/Article/details/gt2fczfrnnw.html

wc -l a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gt2tftkrbwb.html

[R53] 查看文件头与实时尾
来源：http://dali.haohaochexian.top/Article/details/gt2jcnvzkkr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.dianchejie.cn/Article/details/gt2pemkoujt.html

[R54] 比较两个文件
来源：http://dali.nwbrower.top/Article/details/gt2vkloatkh.html

diff a.txt b.txt
来源：http://dali.svipenyu.cn/Article/details/gt2hmkjglqy.html

[R55] 压缩与解压
来源：http://dali.jinqigfzy.top/Article/details/gt2oiweibvi.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.andypj.xyz/Article/details/gt2ccfuoulz.html

[R56] 远程拷贝
来源：http://dali.sxryk.cn/Article/details/gt2ycgkyses.html

scp file user@host:/path/
来源：http://dali.wangshuangyany.cn/Article/details/gt2admvchnc.html

[R57] 远程执行命令
来源：http://dali.cqqwz.cn/Article/details/gt2xbwwoqtt.html

ssh user@host 'uptime'
来源：http://dali.andypj.xyz/Article/details/gt2oijfkhpc.html

[R58] 下载文件
来源：http://dali.yj20258.top/Article/details/gt2mmzmpker.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nwbrower.top/Article/details/gt2pognpyms.html

[R59] 发 POST JSON
来源：http://dali.316326.xyz/Article/details/gt2cvpfntaf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.tianlin.xyz/Article/details/gt2vmqaypcu.html

[R60] 只看 HTTP 状态码
来源：http://dali.yuanzhike.top/Article/details/gt2lgkwwmgt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.snrcjt.cn/Article/details/gt2vprueknb.html

[R61] 磁盘占用
来源：http://dali.guannengcc.top/Article/details/gt2ronkwaeb.html


<!-- 参考信息 -->