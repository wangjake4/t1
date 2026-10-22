代发 wailian999

[Q14] 存在则更新（upsert）
来源：http://dali.fzhhl.top/Article/details/gt2czqaygav.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.pengpengdd.cyou/Article/details/gt2ekbdobfa.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.ybcxt.top/Article/details/gt2zxlsoxeo.html

[Q15] 查询全部
来源：http://dali.hammf.cn/Article/details/gt2xptcipjg.html

SELECT * FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2amzpvahk.html

[Q16] 查询指定列
来源：http://dali.sweek.top/Article/details/gt2vatnhmym.html

SELECT id, name FROM users;
来源：http://dali.haohaochexian.top/Article/details/gt2gougtlyx.html

[Q17] 条件查询
来源：http://dali.jlsjyb.cn/Article/details/gt2lnrhfpar.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.nanxuanxn.top/Article/details/gt2kkmweojk.html

[Q18] 模糊匹配
来源：http://dali.yonumen.top/Article/details/gt2xiaibyut.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.feifeiyinyue.top/Article/details/gt2ehhidhcm.html

[Q19] 范围查询
来源：http://dali.jiagoushi.top/Article/details/gt2hkiuxtkk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shuidangran.top/Article/details/gt2wptmqmha.html

[Q20] IN 列表
来源：http://dali.nwbrower.top/Article/details/gt2tjspochj.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.fzhhl.top/Article/details/gt2ejlbqbev.html

[Q21] 空值判断
来源：http://dali.zhixingplan.top/Article/details/gt2ypndjwbz.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.xuetiantiany.cn/Article/details/gt2yqsyhzhg.html

[Q22] 排序
来源：http://dali.cheryme.top/Article/details/gt2rsylfgqq.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yvedp.cn/Article/details/gt2scmtavis.html

[Q23] 分页
来源：http://dali.yj20258888.top/Article/details/gt2woovdagn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.tianlin.xyz/Article/details/gt2cybfkstd.html

[Q24] 去重
来源：http://dali.jqgufenzy.top/Article/details/gt2tqgxwdhs.html

SELECT DISTINCT city FROM users;
来源：http://dali.aibaodan.cn/Article/details/gt2xwluwmvj.html

[Q25] 只取前 N 条
来源：http://dali.yueranfly.top/Article/details/gt2xabrlgao.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.0kj1m.cn/Article/details/gt2nnmpvdxe.html

[Q26] 计数
来源：http://dali.jinqigufen.top/Article/details/gt2hhyoqsvx.html

SELECT COUNT(*) FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2qviuofyc.html

[Q27] 条件计数
来源：http://dali.yonumen.top/Article/details/gt2zipkplux.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gt2esgwjbry.html

[Q28] 求和与平均
来源：http://dali.daxiang520.top/Article/details/gt2uocracbo.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.shuidangran.top/Article/details/gt2dirvqpsu.html

[Q29] 最大最小值
来源：http://dali.zhiwuduotai.top/Article/details/gt2lrzyopac.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.fengsongda.top/Article/details/gt2ufyglcoy.html

[Q30] 分组统计
来源：http://dali.yuanzhike.top/Article/details/gt2myxwgmkr.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.hfpthk.cn/Article/details/gt2mzohlqia.html

[Q31] 分组后过滤
来源：http://dali.shanyushiyangtech.top/Article/details/gt2mnizsdfm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ydzc1.top/Article/details/gt2ydmzkcht.html

[Q32] 分组拼接字符串
来源：http://dali.hnxiangtu.top/Article/details/gt2psufrckp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xylfe.cn/Article/details/gt2iotruijr.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.meibo888.top/Article/details/gt2dcvmrwna.html

[Q33] 多列分组
来源：http://dali.aizwys.cn/Article/details/gt2qjxpvuxa.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jlsjyb.cn/Article/details/gt2ywcsudwm.html

[Q34] 每组取第一条
来源：http://dali.yj20258888.top/Article/details/gt2tccdbcoj.html

SELECT * FROM (
来源：http://dali.hongshengwenyu.top/Article/details/gt2shlalyot.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sysykeji.top/Article/details/gt2xkusiknb.html

) t WHERE rn = 1;
来源：http://dali.yuxming.cn/Article/details/gt2odsiasjm.html

[Q35] 内连接
来源：http://dali.nanxuanxn.top/Article/details/gt2fxuilvbp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.daria6918.cn/Article/details/gt2bxjmxozd.html

[Q36] 左连接
来源：http://dali.redwolf501.top/Article/details/gt2yvutpdgd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.andypj.xyz/Article/details/gt2xyiqvcve.html

[Q37] 右连接
来源：http://dali.nanxuanxn.top/Article/details/gt2nkiwiasf.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zdqjudy.top/Article/details/gt2jvewizdh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.shangyingyoupin.top/Article/details/gt2mmywqzlr.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.wangdashe.top/Article/details/gt2oiysbtjv.html

[Q39] 自连接（查上下级）
来源：http://dali.zhongyouzk.top/Article/details/gt2zjnkhlxz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hywenlv.cn/Article/details/gt2gdjxabmo.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.wangdashe.top/Article/details/gt2qihwgaxc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yvedp.cn/Article/details/gt2qhrbnjyk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.9152youxi.cn/Article/details/gt2fmhxjwjg.html

[Q41] 多表连接
来源：http://dali.fzhhl.top/Article/details/gt2bpcdxvfl.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.guannengcc.top/Article/details/gt2qylaaljx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.hysaishi.cn/Article/details/gt2onefrvla.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.smart0.xyz/Article/details/gt2vzuxmxjd.html

[Q42] 连接条件附加过滤
来源：http://dali.c1oappe.top/Article/details/gt2pconrktw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hnxiangtu.top/Article/details/gt2mutgezcp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.cheryme.top/Article/details/gt2hvieundy.html

[Q43] 标量子查询
来源：http://dali.yuxming.cn/Article/details/gt2doqpdcrt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xuanzx.com/Article/details/gt2emgjxkhq.html

[Q44] IN 子查询
来源：http://dali.yongpay.top/Article/details/gt2zgtfftgh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hammf.cn/Article/details/gt2yumvwvfl.html

[Q45] EXISTS 判断存在
来源：http://dali.fzhhl.top/Article/details/gt2uttkodng.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.smart0.xyz/Article/details/gt2otipzhzv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hywenlv.cn/Article/details/gt2zjcsfijd.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sysykeji.top/Article/details/gt2urijqbyy.html

[Q47] 与平均值比较
来源：http://dali.wangdashe.top/Article/details/gt2mzvtdfac.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yuanzhike.top/Article/details/gt2suojmwjp.html

[Q48] CTE 公用表表达式
来源：http://dali.ehwqpu.com/Article/details/gt2rjzfxmap.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.svipenyu.cn/Article/details/gt2gshffcip.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jinqigfzy.top/Article/details/gt2puqlrpch.html

[Q49] 更新单行
来源：http://dali.zhoulong.xyz/Article/details/gt2cczhzicy.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cqqwz.cn/Article/details/gt2dsyjwblf.html

[Q50] 批量更新
来源：http://dali.jinqigufen.top/Article/details/gt2xnzrrvub.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gogol.net.cn/Article/details/gt2eplnehxk.html

[Q51] 用子查询更新
来源：http://dali.kuanghao11.cn/Article/details/gt2qsubikli.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jqgfzy.top/Article/details/gt2mzciavnn.html

[Q52] 删除指定行
来源：http://dali.smart0.xyz/Article/details/gt2gytidumt.html

DELETE FROM users WHERE id = 10;
来源：http://dali.andypj.xyz/Article/details/gt2rjsqwdfh.html

[Q53] 按条件删除
来源：http://dali.bjfxy.top/Article/details/gt2tyuaggny.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shuidangran.top/Article/details/gt2kytmujuz.html

[Q54] 清空表
来源：http://dali.fengsongda.top/Article/details/gt2kvotmfes.html

TRUNCATE TABLE logs;
来源：http://dali.guowangkeji.top/Article/details/gt2jcinwqex.html

[Q55] 排名（并列占位）
来源：http://dali.ydzc1.top/Article/details/gt2bywtrdxw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.fzhhl.top/Article/details/gt2yvvyagtq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.pycfn.com/Article/details/gt2mhpmadsx.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shanyushiyangtech.top/Article/details/gt2bmlcilil.html

[Q57] 行号
来源：http://dali.fzhhl.top/Article/details/gt2asnaypki.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gzhubu.top/Article/details/gt2bphlfdxd.html

[Q58] 累计求和
来源：http://dali.yj20258.top/Article/details/gt2xdvlsugq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.316326.xyz/Article/details/gt2fgqeyjpv.html

[Q59] 分组内累计
来源：http://dali.jyoumei.cn/Article/details/gt2lidepmhb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ivvv.top/Article/details/gt2cpqmvvgq.html

[Q60] 取上一行 / 下一行
来源：http://dali.aibaodan.cn/Article/details/gt2cdclwobo.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gogol.net.cn/Article/details/gt2pmhhpvge.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gt2rahsurva.html

[Q61] 移动平均
来源：http://dali.hongshengwenyu.top/Article/details/gt2evtgrbzj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.fengsongda.top/Article/details/gt2umrewhjv.html

[Q62] 分组占比
来源：http://dali.jiagoushi.top/Article/details/gt2ndorbgrx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.fzhhl.top/Article/details/gt2gdnqhwdx.html

[Q63] 开启事务
来源：http://dali.yuxming.cn/Article/details/gt2sljrgatz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2reivvdml.html

[Q64] 提交事务
来源：http://dali.jiagoushi.top/Article/details/gt2ziyimzem.html

COMMIT;
来源：http://dali.ehwqpu.com/Article/details/gt2fhleqrjg.html

[Q65] 回滚事务
来源：http://dali.gaohongyu789.top/Article/details/gt2rmrwzaeh.html

ROLLBACK;
来源：http://dali.sysykeji.top/Article/details/gt2bfcqzdff.html

[Q66] 行锁查询
来源：http://dali.jqgfzy.top/Article/details/gt2pzdjegza.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cqqwz.cn/Article/details/gt2djxmocrs.html

[Q67] 设置隔离级别
来源：http://dali.hysaishi.cn/Article/details/gt2acumnalx.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zycfv.cn/Article/details/gt2nlbolaxf.html

[Q68] 保存点
来源：http://dali.wangshuangyany.cn/Article/details/gt2iazaebgw.html

SAVEPOINT sp1;
来源：http://dali.tian-w.cn/Article/details/gt2ipvxjole.html

ROLLBACK TO sp1;
来源：http://dali.cashguo.top/Article/details/gt2xalrbrcd.html

[Q69] 查看执行计划
来源：http://dali.chenjidiqi.icu/Article/details/gt2hexavspi.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.mhx1999.top/Article/details/gt2kabjxfqq.html

[Q70] 更新统计信息
来源：http://dali.wangdashe.top/Article/details/gt2uieyusra.html

ANALYZE TABLE users;
来源：http://dali.gotoacloud.top/Article/details/gt2qwcupttp.html

[Q71] 查看建表语句
来源：http://dali.dianchejie.cn/Article/details/gt2bfsdvrzn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yangfankeji.com/Article/details/gt2pwmusqqv.html

[Q72] 查看索引
来源：http://dali.bjfxy.top/Article/details/gt2loxyezda.html

SHOW INDEX FROM users;
来源：http://dali.zhixingplan.top/Article/details/gt2dywbbalo.html

[Q73] 查看表状态
来源：http://dali.yanxiufei.cn/Article/details/gt2rtbwsrel.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yonumen.top/Article/details/gt2gejszaai.html

[Q74] 强制使用索引
来源：http://dali.ppjwa.cn/Article/details/gt2qtfmhpih.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.dashuyun.cn/Article/details/gt2djafsxig.html

[Q75] 日期格式化
来源：http://dali.yvedp.cn/Article/details/gt2vikhgche.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hammf.cn/Article/details/gt2fyqprdyb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.andypj.xyz/Article/details/gt2pqvorcvp.html

[Q76] 按天统计
来源：http://dali.jlsjyb.cn/Article/details/gt2benowmbl.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cheryme.top/Article/details/gt2tkntxvrj.html

[Q77] 时间加减
来源：http://dali.ppjwa.cn/Article/details/gt2jwthenul.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.chenjidiqi.icu/Article/details/gt2fczgrpiu.html

[Q78] 当前时间
来源：http://dali.mhx1999.top/Article/details/gt2npylpaww.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.havefunace.top/Article/details/gt2rmuvzaiy.html

[Q79] 字符串拼接
来源：http://dali.hnxiangtu.top/Article/details/gt2hfinrrvb.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yueranfly.top/Article/details/gt2qoqgkjvs.html

[Q80] 字符串截取
来源：http://dali.yuanzhike.top/Article/details/gt2aixrbrbf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gt2vchtowbu.html

[Q81] 字符串替换
来源：http://dali.yuxming.cn/Article/details/gt2hfvjtcjf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gt2sjffnbyg.html

[Q82] 字符长度与字节长度
来源：http://dali.tianlin.xyz/Article/details/gt2cgcsitfh.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jqgfzy.top/Article/details/gt2fjhecdeg.html

[Q83] 大小写转换
来源：http://dali.hammf.cn/Article/details/gt2ovwnfxgj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gt2hkjshdlh.html

[Q84] 去除首尾空格
来源：http://dali.zhengqikj.top/Article/details/gt2pxwbcfhu.html

SELECT TRIM(name) FROM users;
来源：http://dali.wangdashe.top/Article/details/gt2hpvxbgaa.html

[Q85] 数值取整
来源：http://dali.hywenlv.cn/Article/details/gt2tsoxyfgv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gaohongyu789.top/Article/details/gt2roohttyf.html

[Q86] 读取 JSON 字段
来源：http://dali.zhongyouzk.top/Article/details/gt2gncpalwo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jianghu66.top/Article/details/gt2osdsuckc.html

[Q87] JSON 字段做条件
来源：http://dali.yueranfly.top/Article/details/gt2afgeysyh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.quarkkingdee.top/Article/details/gt2sbgpuafd.html

[Q88] 行转列（条件聚合）
来源：http://dali.yanxiufei.cn/Article/details/gt2tqubptnz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.guowangkeji.top/Article/details/gt2gnqevvjl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gt2nxpyjhqp.html

[Q89] 判断表是否存在
来源：http://dali.shuidangran.top/Article/details/gt2alvjacdm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nanxinkj.top/Article/details/gt2yiybkgeo.html

[Q90] 生成序号列
来源：http://dali.gzhubu.top/Article/details/gt2psnndvmw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zycfv.cn/Article/details/gt2erhqyrtw.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gt2mwcfdycg.html

R. Bash 专题
来源：http://dali.guowangkeji.top/Article/details/gt2wtstasvl.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gt2bkdzrscx.html

[R01] shebang 与严格模式
来源：http://dali.chenzaomai.com/Article/details/gt2xokujcoa.html

#!/usr/bin/env bash
来源：http://dali.kuanghao11.cn/Article/details/gt2xsqcjrtd.html

set -euo pipefail
来源：http://dali.zhoulong.xyz/Article/details/gt2lulxsjyi.html

[R02] 变量赋值与使用
来源：http://dali.birdmap.top/Article/details/gt2qkcixpkt.html

name="Tom"; echo "$name"
来源：http://dali.dashuyun.cn/Article/details/gt2cgaonqgn.html

[R03] 只读变量
来源：http://dali.smart0.xyz/Article/details/gt2tvicdrwk.html

readonly PI=3.14
来源：http://dali.jiagoushi.top/Article/details/gt2xhvupntt.html

[R04] 位置参数
来源：http://dali.vqdsnc.cn/Article/details/gt2qoxvzliw.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.snrcjt.cn/Article/details/gt2jgwjwaqv.html

[R05] 参数默认值
来源：http://dali.yanxiufei.cn/Article/details/gt2arztksjw.html

name="${1:-default}"
来源：http://dali.jinghuilouyu.cn/Article/details/gt2uyriddlf.html

[R06] 判断命令是否存在
来源：http://dali.smart0.xyz/Article/details/gt2lawytdvf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.tian-w.cn/Article/details/gt2fdfasprf.html

[R07] if 判断文件
来源：http://dali.guannengcc.top/Article/details/gt2dfzfmhld.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zhongyouzk.top/Article/details/gt2znozstnc.html

[R08] 数值比较
来源：http://dali.bjfxy.top/Article/details/gt2yqohqout.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.haohaochexian.top/Article/details/gt2ylzzoqbe.html

[R09] 字符串比较
来源：http://dali.0kj1m.cn/Article/details/gt2batrkifu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.snrcjt.cn/Article/details/gt2bzahcmnn.html

[R10] 正则匹配
来源：http://dali.havefunace.top/Article/details/gt2lxtpdyum.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zycfv.cn/Article/details/gt2ugttznwk.html

[R11] case 多分支
来源：http://dali.chenjidiqi.icu/Article/details/gt2boirlyjq.html

case "$1" in
来源：http://dali.yueranfly.top/Article/details/gt2yfiqagih.html

start) echo "启动" ;;
来源：http://dali.aibaodan.cn/Article/details/gt2odvmvspc.html

stop)  echo "停止" ;;
来源：http://dali.hnqzz.top/Article/details/gt2vrgrzher.html

*)     echo "未知命令" ;;
来源：http://dali.c1oappe.top/Article/details/gt2fuicnvei.html

esac
来源：http://dali.aibaodan.cn/Article/details/gt2groaaojp.html

[R12] for 遍历文件
来源：http://dali.yangfankeji.com/Article/details/gt2uzkvyabj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sysykeji.top/Article/details/gt2fwltafyl.html

[R13] for 计数循环
来源：http://dali.snrcjt.cn/Article/details/gt2mkjgqtnh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.chenjidiqi.icu/Article/details/gt2rpzaoczc.html

[R14] C 风格 for
来源：http://dali.yj20258888.top/Article/details/gt2hfzugbwj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yj202588.top/Article/details/gt2synnfmrq.html

[R15] while 逐行读文件
来源：http://dali.pengpengdd.cyou/Article/details/gt2xpslmefd.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gt2ugeemvur.html

[R16] until 等待条件
来源：http://dali.yj20258888.top/Article/details/gt2wjjpaqxk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhongyouzk.top/Article/details/gt2vehpgmct.html

[R17] 数组定义与取值
来源：http://dali.xylfe.cn/Article/details/gt2qxbtxgat.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.nanxuanxn.top/Article/details/gt2gmbhxmoe.html

[R18] 遍历数组
来源：http://dali.aibaodan.cn/Article/details/gt2fcacgmnd.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zhongyouzk.top/Article/details/gt2uqqinkzr.html

[R19] 数组长度
来源：http://dali.mhx1999.top/Article/details/gt2urnwkdch.html

echo "${#arr[@]}"
来源：http://dali.zycfv.cn/Article/details/gt2qmhcpttz.html

[R20] 关联数组（字典）
来源：http://dali.cucudq.cn/Article/details/gt2qlvbdhdy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.9152youxi.cn/Article/details/gt2haytbmvo.html

[R21] 字符串长度
来源：http://dali.gotoacloud.top/Article/details/gt2seafzckf.html

echo "${#s}"
来源：http://dali.redwolf501.top/Article/details/gt2tqhpngav.html

[R22] 截取子串
来源：http://dali.chenzaomai.com/Article/details/gt2expjbesz.html

echo "${s:0:5}"
来源：http://dali.meibo888.top/Article/details/gt2almeukfd.html

[R23] 字符串替换
来源：http://dali.yuanzhike.top/Article/details/gt2jnsczdda.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gzhubu.top/Article/details/gt2urkbfpkc.html

[R24] 大小写转换
来源：http://dali.yangfankeji.com/Article/details/gt2wpgtxaht.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.snrcjt.cn/Article/details/gt2pswhsvkk.html

[R25] 去后缀 / 去前缀
来源：http://dali.yj20258888.top/Article/details/gt2hlultvps.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shangyingyoupin.top/Article/details/gt2uuzmmfss.html

[R26] 命令替换
来源：http://dali.zhoulong.xyz/Article/details/gt2blzwxjww.html

now=$(date +%F); echo "$now"
来源：http://dali.feifeiyinyue.top/Article/details/gt2righgmov.html

[R27] 算术展开
来源：http://dali.birdmap.top/Article/details/gt2cubjmzcm.html

echo $((1 + 2 * 3))
来源：http://dali.yj20258888.top/Article/details/gt2pjvpsuxh.html

[R28] 浮点运算
来源：http://dali.pycfn.com/Article/details/gt2jchejxih.html

echo "scale=2; 10/3" | bc
来源：http://dali.bjfxy.top/Article/details/gt2ylswaqwb.html

[R29] 定义函数
来源：http://dali.9152youxi.cn/Article/details/gt2tvphrcjj.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.bjfxy.top/Article/details/gt2zfdzzxjl.html

[R30] 函数返回状态码
来源：http://dali.svipenyu.cn/Article/details/gt2gfgfaheq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shanyushiyangkeji.top/Article/details/gt2lxdvasbh.html

[R31] 局部变量
来源：http://dali.cucudq.cn/Article/details/gt2nqubrbzx.html

f() { local x=1; echo "$x"; }
来源：http://dali.shanyushiyangtech.top/Article/details/gt2egrgdvnh.html

[R32] 参数个数校验
来源：http://dali.yuanzhike.top/Article/details/gt2mfbyxtft.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.chenlongwang.top/Article/details/gt2kzlpppsr.html

[R33] 捕获错误并提示行号
来源：http://dali.quarkkingdee.top/Article/details/gt2stzpcvhh.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.nanxinkj.top/Article/details/gt2mmpklrgu.html

[R34] 退出时清理
来源：http://dali.xinyue.icu/Article/details/gt2hslflyel.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuanzhike.top/Article/details/gt2gcdlyhwi.html

[R35] 后台执行并等待
来源：http://dali.jlsjyb.cn/Article/details/gt2vqdkvzbm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.sxryk.cn/Article/details/gt2zwxvgdlx.html

[R36] 并发执行多个任务
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2cvolvmwt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ivvv.top/Article/details/gt2jseorhnc.html

[R37] 把输出赋给变量
来源：http://dali.zhijiandao.cn/Article/details/gt2olafyqtt.html

files=$(ls -1)
来源：http://dali.zhoulong.xyz/Article/details/gt2zdfqumfk.html

[R38] 管道串联
来源：http://dali.dianchejie.cn/Article/details/gt2rwrasshq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.gzhubu.top/Article/details/gt2drwzjmgt.html

[R39] 重定向标准输出与错误
来源：http://dali.yanxiufei.cn/Article/details/gt2ojzylknm.html

cmd > out.log 2>&1
来源：http://dali.aibaodan.cn/Article/details/gt2dllxovzi.html

[R40] 追加写日志
来源：http://dali.yj20258.top/Article/details/gt2oxpdewsc.html

echo "log" >> out.log
来源：http://dali.meibo888.top/Article/details/gt2bzxxilnt.html

[R41] 丢弃输出
来源：http://dali.jinyuanbaomall.cn/Article/details/gt2wwhurhhe.html

cmd >/dev/null 2>&1
来源：http://dali.aizwys.cn/Article/details/gt2bmcsnlbx.html

[R42] 输入重定向
来源：http://dali.ppjwa.cn/Article/details/gt2qjwabqnw.html

wc -l < a.txt
来源：http://dali.mhx1999.top/Article/details/gt2jmzuxfei.html

[R43] 按名字查找文件
来源：http://dali.guannengcc.top/Article/details/gt2luqplutd.html

find . -name "*.log" -type f
来源：http://dali.zhiwuduotai.top/Article/details/gt2yxrgsgrt.html

[R44] 按修改时间查找
来源：http://dali.gaohongyu789.top/Article/details/gt2kxrwtoqd.html

find . -mtime -7 -type f
来源：http://dali.sxryk.cn/Article/details/gt2tuzowsaz.html

[R45] 批量删除
来源：http://dali.xinyue.icu/Article/details/gt2mpmtecii.html

find . -name "*.tmp" -delete
来源：http://dali.zhixingplan.top/Article/details/gt2lazgprsw.html

[R46] 递归替换文件内容
来源：http://dali.redwolf501.top/Article/details/gt2kzpoqlnh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinqigfzy.top/Article/details/gt2pdbsqfwa.html

[R47] sed 单行替换
来源：http://dali.xinyue.icu/Article/details/gt2blokvzbk.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shuidangran.top/Article/details/gt2buqrdhzs.html

[R48] awk 取指定列
来源：http://dali.hfpthk.cn/Article/details/gt2brxcsprn.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhongyouzk.top/Article/details/gt2bjaeqjsg.html

[R49] awk 带条件
来源：http://dali.ydzc1.top/Article/details/gt2ltvmcywi.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.zhijiandao.cn/Article/details/gt2xbjaqvku.html

[R50] awk 求和
来源：http://dali.hammf.cn/Article/details/gt2uvwpitwe.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sysykeji.top/Article/details/gt2udtydrqd.html

[R51] 排序去重取前几
来源：http://dali.ydzc1.top/Article/details/gt2qnppzshv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hongshengwenyu.top/Article/details/gt2cpltuqtu.html

[R52] 统计行数
来源：http://dali.tianlin.xyz/Article/details/gt2uizmnctz.html

wc -l a.txt
来源：http://dali.tianlin.xyz/Article/details/gt2zkugfpdx.html

[R53] 查看文件头与实时尾
来源：http://dali.jiagoushi.top/Article/details/gt2vlplvirr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.cqqwz.cn/Article/details/gt2xcematzb.html

[R54] 比较两个文件
来源：http://dali.jinghuilouyu.cn/Article/details/gt2lveutito.html

diff a.txt b.txt
来源：http://dali.zhixingplan.top/Article/details/gt2fgltcfue.html

[R55] 压缩与解压
来源：http://dali.smart0.xyz/Article/details/gt2egxgkrni.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.guowangkeji.top/Article/details/gt2vzvazjqt.html

[R56] 远程拷贝
来源：http://dali.c1oappe.top/Article/details/gt2qrpkucpx.html

scp file user@host:/path/
来源：http://dali.sweek.top/Article/details/gt2fwfyzyco.html

[R57] 远程执行命令
来源：http://dali.sysykeji.top/Article/details/gt2ogapffjv.html

ssh user@host 'uptime'
来源：http://dali.cdnleiting.top/Article/details/gt2ywnsratx.html

[R58] 下载文件
来源：http://dali.316326.xyz/Article/details/gt2xsjzrgau.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.iojbl.cn/Article/details/gt2ptksrfwe.html

[R59] 发 POST JSON
来源：http://dali.hammf.cn/Article/details/gt2bwplhmot.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinqigfzy.top/Article/details/gt2maykybfx.html

[R60] 只看 HTTP 状态码
来源：http://dali.gzhubu.top/Article/details/gt2marygexf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhongyouzk.top/Article/details/gt2memjpjkw.html

[R61] 磁盘占用
来源：http://dali.bjfxy.top/Article/details/gt2cknghvzp.html

df -h;  du -sh *
来源：http://dali.daria6918.cn/Article/details/gt2gadzween.html

[R62] 找最占空间的文件
来源：http://dali.gotoacloud.top/Article/details/gt2plrmlnfb.html

du -ah . | sort -rh | head -10
来源：http://dali.hongshengwenyu.top/Article/details/gt2deoptzrp.html

[R63] 内存与进程
来源：http://dali.shangyingyoupin.top/Article/details/gt2toqgmjsd.html


<!-- 参考信息 -->