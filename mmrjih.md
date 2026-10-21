代发 wailian999

INSERT INTO users (name) VALUES ('C');
来源：http://dali.redwolf501.top/Article/details/gtrnaomhur.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.jlsjyb.cn/Article/details/gtvdwwdszr.html

[Q13] 忽略重复插入
来源：http://dali.haohaochexian.top/Article/details/gtxvypugxb.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.0kj1m.cn/Article/details/gtmmguiugr.html

[Q14] 存在则更新（upsert）
来源：http://dali.guowangkeji.top/Article/details/gtovcahsmx.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.redwolf501.top/Article/details/gtesfqqjso.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.cheryme.top/Article/details/gtzfisrxdg.html

[Q15] 查询全部
来源：http://dali.nanxuanxn.top/Article/details/gtdicgayro.html

SELECT * FROM users;
来源：http://dali.ppjwa.cn/Article/details/gttnhmclri.html

[Q16] 查询指定列
来源：http://dali.zdqjudy.top/Article/details/gtjibgwppi.html

SELECT id, name FROM users;
来源：http://dali.daxiang520.top/Article/details/gtwgkmsjwy.html

[Q17] 条件查询
来源：http://dali.yueranfly.top/Article/details/gtrshvnosn.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdtenishv.html

[Q18] 模糊匹配
来源：http://dali.zdqjudy.top/Article/details/gtcrpyeuzp.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yj202588.top/Article/details/gtegwwtrfm.html

[Q19] 范围查询
来源：http://dali.dashuyun.cn/Article/details/gtjpdmdflp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.xziqi.cn/Article/details/gtxnofjlzk.html

[Q20] IN 列表
来源：http://dali.yj20258888.top/Article/details/gtdysfpnke.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.yongpay.top/Article/details/gtiardhktk.html

[Q21] 空值判断
来源：http://dali.jinqigufen.top/Article/details/gtuhoikkqc.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.316326.xyz/Article/details/gtpixetxwd.html

[Q22] 排序
来源：http://dali.9152youxi.cn/Article/details/gtbpxziolm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.c1oappe.top/Article/details/gthprylfvt.html

[Q23] 分页
来源：http://dali.guannengcc.top/Article/details/gtcgsvncuo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenlongwang.top/Article/details/gtramcywnj.html

[Q24] 去重
来源：http://dali.bjfxy.top/Article/details/gtzgyrtmqr.html

SELECT DISTINCT city FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtposwsedy.html

[Q25] 只取前 N 条
来源：http://dali.aibaodan.cn/Article/details/gtorpskncg.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.shangyingyoupin.top/Article/details/gtprgwtkyv.html

[Q26] 计数
来源：http://dali.quarkkingdee.top/Article/details/gtieaosyqt.html

SELECT COUNT(*) FROM users;
来源：http://dali.tanke756.top/Article/details/gtdynmrrsr.html

[Q27] 条件计数
来源：http://dali.snrcjt.cn/Article/details/gtebqzlnjx.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.sxryk.cn/Article/details/gtiabefufb.html

[Q28] 求和与平均
来源：http://dali.birdmap.top/Article/details/gtrpamknjx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtaahewgbw.html

[Q29] 最大最小值
来源：http://dali.andypj.xyz/Article/details/gtrbgwpyqr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.fengsongda.top/Article/details/gtbecuqgyq.html

[Q30] 分组统计
来源：http://dali.dianchejie.cn/Article/details/gtyhoyqfgb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhengqikj.top/Article/details/gtstuzaurl.html

[Q31] 分组后过滤
来源：http://dali.zhixingplan.top/Article/details/gtscgrglyk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.svipenyu.cn/Article/details/gtathaxrbm.html

[Q32] 分组拼接字符串
来源：http://dali.yj20258888.top/Article/details/gtprtbaptj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.feifeiyinyue.top/Article/details/gtjxbcpykj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.gogol.net.cn/Article/details/gtcykwrhsm.html

[Q33] 多列分组
来源：http://dali.chenlongwang.top/Article/details/gtitueietn.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.aizwys.cn/Article/details/gtrsjcsuzo.html

[Q34] 每组取第一条
来源：http://dali.nanxuanxn.top/Article/details/gtgpwlhmub.html

SELECT * FROM (
来源：http://dali.hongshengwenyu.top/Article/details/gtplkoxcvp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.guowangkeji.top/Article/details/gtahzbwjfn.html

) t WHERE rn = 1;
来源：http://dali.tanke756.top/Article/details/gtwucmqqor.html

[Q35] 内连接
来源：http://dali.sweek.top/Article/details/gtxwtwjrqu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.c1oappe.top/Article/details/gtlzgqtoib.html

[Q36] 左连接
来源：http://dali.cashguo.top/Article/details/gtchdvczhe.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.gaohongyu789.top/Article/details/gtoyrtdcwd.html

[Q37] 右连接
来源：http://dali.fengsongda.top/Article/details/gtfznhghvj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xziqi.cn/Article/details/gtwnghiqds.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.wangshuangyany.cn/Article/details/gtkzuyfynk.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yangfankeji.com/Article/details/gtojyfixqc.html

[Q39] 自连接（查上下级）
来源：http://dali.zhengqikj.top/Article/details/gtycknnnfe.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xylfe.cn/Article/details/gtmfbpfcpu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.kuanghao11.cn/Article/details/gtoqhhagmz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.0kj1m.cn/Article/details/gtscwsqzvt.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zhixingplan.top/Article/details/gtrffldckf.html

[Q41] 多表连接
来源：http://dali.jianghu66.top/Article/details/gtdephnwxt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.smart0.xyz/Article/details/gtzbopjrje.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sweek.top/Article/details/gtreqdaezp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yangfankeji.com/Article/details/gtabgvsqxr.html

[Q42] 连接条件附加过滤
来源：http://dali.yuxming.cn/Article/details/gtqnvzuqas.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yj202588.top/Article/details/gtowibftvw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.kuanghao11.cn/Article/details/gtjwesvvbo.html

[Q43] 标量子查询
来源：http://dali.jlsjyb.cn/Article/details/gtvmvazbjy.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jianghu66.top/Article/details/gtqqtwfpzt.html

[Q44] IN 子查询
来源：http://dali.jinqigfzy.top/Article/details/gtspkntjxj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jinghuilouyu.cn/Article/details/gtufvrkdzs.html

[Q45] EXISTS 判断存在
来源：http://dali.gotoacloud.top/Article/details/gtafwjqsai.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.feifeiyinyue.top/Article/details/gtaeolfxbd.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.nwbrower.top/Article/details/gtikgjaynx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258.top/Article/details/gtbfopjwmj.html

[Q47] 与平均值比较
来源：http://dali.ivvv.top/Article/details/gtoviyrlnf.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shanyushiyangtech.top/Article/details/gtegoavije.html

[Q48] CTE 公用表表达式
来源：http://dali.cqqwz.cn/Article/details/gtnfcyqazv.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.meibo888.top/Article/details/gtarevwtyt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sufxvd.cn/Article/details/gtwwxbwmky.html

[Q49] 更新单行
来源：http://dali.xuetiantiany.cn/Article/details/gtmkvpdzwe.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinqigfzy.top/Article/details/gtgnjpzlox.html

[Q50] 批量更新
来源：http://dali.cqqwz.cn/Article/details/gtpjtwfljq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinqigufen.top/Article/details/gttmqbicop.html

[Q51] 用子查询更新
来源：http://dali.yuanzhike.top/Article/details/gtqpakhndd.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gogol.net.cn/Article/details/gtetngvrml.html

[Q52] 删除指定行
来源：http://dali.jinqigfzy.top/Article/details/gtsjecwvzs.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xuanzx.com/Article/details/gtehiqospe.html

[Q53] 按条件删除
来源：http://dali.316326.xyz/Article/details/gttgvnyqbr.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yvedp.cn/Article/details/gtdrpqhguw.html

[Q54] 清空表
来源：http://dali.9152youxi.cn/Article/details/gtevvvkqwt.html

TRUNCATE TABLE logs;
来源：http://dali.nwbrower.top/Article/details/gtoaadnrqr.html

[Q55] 排名（并列占位）
来源：http://dali.quarkkingdee.top/Article/details/gtefdaebzu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmhlhlftj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.gaohongyu789.top/Article/details/gtilfuoiue.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yj202588.top/Article/details/gtqxztidci.html

[Q57] 行号
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgtlftldq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.fzhhl.top/Article/details/gtvqabwzrr.html

[Q58] 累计求和
来源：http://dali.sweek.top/Article/details/gtwdzdcddi.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtklttrhtc.html

[Q59] 分组内累计
来源：http://dali.gotoacloud.top/Article/details/gtewibdxbq.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtocgtadis.html

[Q60] 取上一行 / 下一行
来源：http://dali.mhx1999.top/Article/details/gtabxwgrih.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.shuidangran.top/Article/details/gtlhnhizff.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhiwuduotai.top/Article/details/gtkqxjifar.html

[Q61] 移动平均
来源：http://dali.guowangkeji.top/Article/details/gtxgdmdnwy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yongpay.top/Article/details/gtkzuptqnv.html

[Q62] 分组占比
来源：http://dali.havefunace.top/Article/details/gttiwsddho.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.tianlin.xyz/Article/details/gtfsbqiysu.html

[Q63] 开启事务
来源：http://dali.wangdashe.top/Article/details/gtrpniwwhv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.kuanghao11.cn/Article/details/gttbreytva.html

[Q64] 提交事务
来源：http://dali.andypj.xyz/Article/details/gtoiaryamz.html

COMMIT;
来源：http://dali.zhengqikj.top/Article/details/gtalpipseg.html

[Q65] 回滚事务
来源：http://dali.ivvv.top/Article/details/gttwydgcps.html

ROLLBACK;
来源：http://dali.aizwys.cn/Article/details/gtewlbqisr.html

[Q66] 行锁查询
来源：http://dali.snrcjt.cn/Article/details/gtyzyttwzv.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cqqwz.cn/Article/details/gtkigugint.html

[Q67] 设置隔离级别
来源：http://dali.0kj1m.cn/Article/details/gtvlajeyxd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yuxming.cn/Article/details/gthubwfpcq.html

[Q68] 保存点
来源：http://dali.svipenyu.cn/Article/details/gtbqfplair.html

SAVEPOINT sp1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtlmyxeabz.html

ROLLBACK TO sp1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtstolbpuu.html

[Q69] 查看执行计划
来源：http://dali.redwolf501.top/Article/details/gtysuayxiw.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.smart0.xyz/Article/details/gtnrinrgkv.html

[Q70] 更新统计信息
来源：http://dali.yuanzhike.top/Article/details/gtvfcoaqkz.html

ANALYZE TABLE users;
来源：http://dali.pengpengdd.cyou/Article/details/gthuvcetsr.html

[Q71] 查看建表语句
来源：http://dali.c1oappe.top/Article/details/gtlnxcrfnn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhengqikj.top/Article/details/gtkxvgxhdu.html

[Q72] 查看索引
来源：http://dali.mhx1999.top/Article/details/gtbwrkrnug.html

SHOW INDEX FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtdgcwvqre.html

[Q73] 查看表状态
来源：http://dali.0kj1m.cn/Article/details/gtupxivesc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ydzc1.top/Article/details/gtsrovwaqg.html

[Q74] 强制使用索引
来源：http://dali.yonumen.top/Article/details/gtxkafsrqi.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhongyouzk.top/Article/details/gttagrnpvc.html

[Q75] 日期格式化
来源：http://dali.zhengqikj.top/Article/details/gtseijudji.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.vqdsnc.cn/Article/details/gtvbokezwk.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jqgufenzy.top/Article/details/gtddprmftb.html

[Q76] 按天统计
来源：http://dali.gogol.net.cn/Article/details/gtfrsynbum.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.wangdashe.top/Article/details/gttvwptlda.html

[Q77] 时间加减
来源：http://dali.hfpthk.cn/Article/details/gterhmyoqe.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sufxvd.cn/Article/details/gtptdeaqwv.html

[Q78] 当前时间
来源：http://dali.andypj.xyz/Article/details/gtllmrojtj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.snrcjt.cn/Article/details/gtxamkteus.html

[Q79] 字符串拼接
来源：http://dali.jyoumei.cn/Article/details/gtdwjgxmhr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jyoumei.cn/Article/details/gteepybowf.html

[Q80] 字符串截取
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrbednoqh.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.tanke756.top/Article/details/gtofagwtbc.html

[Q81] 字符串替换
来源：http://dali.hongshengwenyu.top/Article/details/gtazsrizxy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtikrdfxkd.html

[Q82] 字符长度与字节长度
来源：http://dali.cashguo.top/Article/details/gtozerpmek.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.zycfv.cn/Article/details/gthmwitjmk.html

[Q83] 大小写转换
来源：http://dali.gotoacloud.top/Article/details/gtexwigeec.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xinyue.icu/Article/details/gtilqjteja.html

[Q84] 去除首尾空格
来源：http://dali.guannengcc.top/Article/details/gtgntfnpdc.html

SELECT TRIM(name) FROM users;
来源：http://dali.fzhhl.top/Article/details/gtmunsptdy.html

[Q85] 数值取整
来源：http://dali.cheryme.top/Article/details/gtttgwmnif.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gogol.net.cn/Article/details/gtkltrhpnb.html

[Q86] 读取 JSON 字段
来源：http://dali.cheryme.top/Article/details/gtpeusuwqe.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.shangyingyoupin.top/Article/details/gtwlcbkxrt.html

[Q87] JSON 字段做条件
来源：http://dali.yj202588.top/Article/details/gtfwiepvng.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.redwolf501.top/Article/details/gtwcjnimms.html

[Q88] 行转列（条件聚合）
来源：http://dali.feifeiyinyue.top/Article/details/gtemrurine.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.cashguo.top/Article/details/gtcazxkanz.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtalqpsnww.html

[Q89] 判断表是否存在
来源：http://dali.pengpengdd.cyou/Article/details/gtowvvibhh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.snrcjt.cn/Article/details/gthxftiiij.html

[Q90] 生成序号列
来源：http://dali.dashuyun.cn/Article/details/gtxcmpipet.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hfpthk.cn/Article/details/gtyggkonct.html

================================================================================
来源：http://dali.cashguo.top/Article/details/gtxxtzgejd.html

R. Bash 专题
来源：http://dali.xuanzx.com/Article/details/gtzgasfqad.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtcuxkdova.html

[R01] shebang 与严格模式
来源：http://dali.shzxlz.cn/Article/details/gtarktwmvm.html

#!/usr/bin/env bash
来源：http://dali.hywenlv.cn/Article/details/gtzubfzcjz.html

set -euo pipefail
来源：http://dali.hfpthk.cn/Article/details/gteeigwgxo.html

[R02] 变量赋值与使用
来源：http://dali.xuanzx.com/Article/details/gtxbybtzab.html

name="Tom"; echo "$name"
来源：http://dali.jlsjyb.cn/Article/details/gtfogpjuid.html

[R03] 只读变量
来源：http://dali.0kj1m.cn/Article/details/gtccxdrikk.html

readonly PI=3.14
来源：http://dali.316326.xyz/Article/details/gtqeehtcrl.html

[R04] 位置参数
来源：http://dali.jinqigfzy.top/Article/details/gtmqblwqhi.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.chenjidiqi.icu/Article/details/gtvmzfjzpb.html

[R05] 参数默认值
来源：http://dali.hfpthk.cn/Article/details/gtdoujqnrw.html

name="${1:-default}"
来源：http://dali.kuanghao11.cn/Article/details/gtbyspfkru.html

[R06] 判断命令是否存在
来源：http://dali.chenjidiqi.icu/Article/details/gtrrnwusjx.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhongyouzk.top/Article/details/gtazlxokca.html

[R07] if 判断文件
来源：http://dali.yonumen.top/Article/details/gtlttwvymb.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.birdmap.top/Article/details/gtnsxkgnef.html

[R08] 数值比较
来源：http://dali.ivvv.top/Article/details/gttjcodtau.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sufxvd.cn/Article/details/gtcelmhoge.html

[R09] 字符串比较
来源：http://dali.smart0.xyz/Article/details/gttbhytild.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.c1oappe.top/Article/details/gtcqyyidat.html

[R10] 正则匹配
来源：http://dali.nanxuanxn.top/Article/details/gtthnwiltq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gtzjngzzyq.html

[R11] case 多分支
来源：http://dali.xuetiantiany.cn/Article/details/gtzjabwszy.html

case "$1" in
来源：http://dali.jiagoushi.top/Article/details/gtlmsirndg.html

start) echo "启动" ;;
来源：http://dali.xuetiantiany.cn/Article/details/gtmrihnbcz.html

stop)  echo "停止" ;;
来源：http://dali.redwolf501.top/Article/details/gtxavgdwfj.html

*)     echo "未知命令" ;;
来源：http://dali.zycfv.cn/Article/details/gtlrrslzip.html

esac
来源：http://dali.0kj1m.cn/Article/details/gtivnrskfs.html

[R12] for 遍历文件
来源：http://dali.yj20258.top/Article/details/gtshkkgnjm.html

for f in *.txt; do echo "$f"; done
来源：http://dali.zycfv.cn/Article/details/gtopxtlvvo.html

[R13] for 计数循环
来源：http://dali.xziqi.cn/Article/details/gtcvgxpwkk.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.pycfn.com/Article/details/gtsfshwdaz.html

[R14] C 风格 for
来源：http://dali.shangyingyoupin.top/Article/details/gtokdktkia.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.daria6918.cn/Article/details/gtqfjhniip.html

[R15] while 逐行读文件
来源：http://dali.yonumen.top/Article/details/gtjgkhwomr.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtcrpbfsis.html

[R16] until 等待条件
来源：http://dali.shanyushiyangtech.top/Article/details/gtmpusbprb.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.feifeiyinyue.top/Article/details/gtghswugwk.html

[R17] 数组定义与取值
来源：http://dali.yonumen.top/Article/details/gturwrmlhu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jyoumei.cn/Article/details/gtkptylufc.html

[R18] 遍历数组
来源：http://dali.yonumen.top/Article/details/gtfuzsrajz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzhtidejl.html

[R19] 数组长度
来源：http://dali.sweek.top/Article/details/gtmjnexjmz.html

echo "${#arr[@]}"
来源：http://dali.zhongyouzk.top/Article/details/gtbltutzbs.html

[R20] 关联数组（字典）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtizvfbrav.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.aibaodan.cn/Article/details/gtnrvmzqhq.html

[R21] 字符串长度
来源：http://dali.ehwqpu.com/Article/details/gtgprtkjzh.html

echo "${#s}"
来源：http://dali.yj20258.top/Article/details/gtlpvyucrh.html

[R22] 截取子串
来源：http://dali.zhijiandao.cn/Article/details/gtjjtgsoxa.html

echo "${s:0:5}"
来源：http://dali.xziqi.cn/Article/details/gtewapqkqj.html

[R23] 字符串替换
来源：http://dali.shzxlz.cn/Article/details/gtyqrplhxt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpyavcoxi.html

[R24] 大小写转换
来源：http://dali.yuanzhike.top/Article/details/gtcxpwibix.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.0kj1m.cn/Article/details/gthqdudmer.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhongyouzk.top/Article/details/gtbcjqwrvh.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinqigufen.top/Article/details/gtgaypihqs.html

[R26] 命令替换
来源：http://dali.havefunace.top/Article/details/gtjaogdkgi.html

now=$(date +%F); echo "$now"
来源：http://dali.yuanzhike.top/Article/details/gtszpznxth.html

[R27] 算术展开
来源：http://dali.tianlin.xyz/Article/details/gtszbfdueo.html

echo $((1 + 2 * 3))
来源：http://dali.xuanzx.com/Article/details/gtppumejxz.html

[R28] 浮点运算
来源：http://dali.jyoumei.cn/Article/details/gtvjdtwoji.html

echo "scale=2; 10/3" | bc
来源：http://dali.yanxiufei.cn/Article/details/gtyitvdssb.html

[R29] 定义函数
来源：http://dali.wangshuangyany.cn/Article/details/gtlekbchtf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zdqjudy.top/Article/details/gtamfaeybb.html

[R30] 函数返回状态码
来源：http://dali.andypj.xyz/Article/details/gtnuwboeut.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.iojbl.cn/Article/details/gtmldkhelo.html

[R31] 局部变量
来源：http://dali.jqgfzy.top/Article/details/gtisffemcd.html

f() { local x=1; echo "$x"; }
来源：http://dali.yongpay.top/Article/details/gtsfoncxyl.html

[R32] 参数个数校验
来源：http://dali.guannengcc.top/Article/details/gtvueirgvb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.dianchejie.cn/Article/details/gtadfvkkxg.html

[R33] 捕获错误并提示行号
来源：http://dali.jiagoushi.top/Article/details/gtmrhjxxqx.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.nanxuanxn.top/Article/details/gtgqpckbnc.html

[R34] 退出时清理
来源：http://dali.zhijiandao.cn/Article/details/gtivvswyah.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxuanxn.top/Article/details/gtkevmgxak.html

[R35] 后台执行并等待
来源：http://dali.dianchejie.cn/Article/details/gtsljoswwk.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hfpthk.cn/Article/details/gtagzpknla.html

[R36] 并发执行多个任务
来源：http://dali.jlsjyb.cn/Article/details/gtjpvebxwr.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.andypj.xyz/Article/details/gtrpcljkdi.html

[R37] 把输出赋给变量
来源：http://dali.hnxiangtu.top/Article/details/gtanowgyht.html

files=$(ls -1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtthqgskug.html

[R38] 管道串联
来源：http://dali.ivvv.top/Article/details/gtekjfmkyw.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hongshengwenyu.top/Article/details/gtgqmucmqf.html

[R39] 重定向标准输出与错误
来源：http://dali.xuetiantiany.cn/Article/details/gtrmkyaxyr.html

cmd > out.log 2>&1
来源：http://dali.yongpay.top/Article/details/gtnnnsnvxh.html

[R40] 追加写日志
来源：http://dali.fzhhl.top/Article/details/gtdipwhssh.html

echo "log" >> out.log
来源：http://dali.yuanzhike.top/Article/details/gtsnefhieu.html

[R41] 丢弃输出
来源：http://dali.kuanghao11.cn/Article/details/gtfvsbjtfp.html

cmd >/dev/null 2>&1
来源：http://dali.zdqjudy.top/Article/details/gtjxpdlhkl.html

[R42] 输入重定向
来源：http://dali.zycfv.cn/Article/details/gtwxkdewqf.html

wc -l < a.txt
来源：http://dali.tanke756.top/Article/details/gtzfejmeyh.html

[R43] 按名字查找文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtgxbwpldn.html

find . -name "*.log" -type f
来源：http://dali.yuanzhike.top/Article/details/gtlemjolxa.html

[R44] 按修改时间查找
来源：http://dali.shanyushiyangtech.top/Article/details/gtvcqxvggc.html

find . -mtime -7 -type f
来源：http://dali.yueranfly.top/Article/details/gttacuhpta.html

[R45] 批量删除
来源：http://dali.316326.xyz/Article/details/gtzbzslxaw.html

find . -name "*.tmp" -delete
来源：http://dali.hywenlv.cn/Article/details/gtqlenssmo.html

[R46] 递归替换文件内容
来源：http://dali.gaohongyu789.top/Article/details/gteplidwmr.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hysaishi.cn/Article/details/gtikwblruy.html

[R47] sed 单行替换
来源：http://dali.jinghuilouyu.cn/Article/details/gtjizyeayc.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cashguo.top/Article/details/gtdwfcntma.html

[R48] awk 取指定列
来源：http://dali.zhengqikj.top/Article/details/gtfdnzknyo.html

awk '{print $1, $3}' a.txt
来源：http://dali.yueranfly.top/Article/details/gtyhqttyzx.html

[R49] awk 带条件
来源：http://dali.ybcxt.top/Article/details/gtoglzlyuv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.chenlongwang.top/Article/details/gtadvnanfd.html

[R50] awk 求和
来源：http://dali.hywenlv.cn/Article/details/gthhnutsrp.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.xuanzx.com/Article/details/gtbyyosiwp.html

[R51] 排序去重取前几
来源：http://dali.shangyingyoupin.top/Article/details/gtttxltgnv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.0kj1m.cn/Article/details/gtjvezaott.html

[R52] 统计行数
来源：http://dali.chenjidiqi.icu/Article/details/gtuzwujdkw.html

wc -l a.txt
来源：http://dali.hfpthk.cn/Article/details/gthxgpeodv.html

[R53] 查看文件头与实时尾
来源：http://dali.hysaishi.cn/Article/details/gtccwuxqwn.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gotoacloud.top/Article/details/gtrvzfgvkk.html

[R54] 比较两个文件
来源：http://dali.cdnleiting.top/Article/details/gtzumgrjrv.html

diff a.txt b.txt
来源：http://dali.cashguo.top/Article/details/gtfvguuygp.html

[R55] 压缩与解压
来源：http://dali.jinghuilouyu.cn/Article/details/gtevrvsqef.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ybcxt.top/Article/details/gtjsbgtjmj.html

[R56] 远程拷贝
来源：http://dali.yuanzhike.top/Article/details/gtcwiatxlv.html

scp file user@host:/path/
来源：http://dali.jqgfzy.top/Article/details/gthtlybtlv.html

[R57] 远程执行命令
来源：http://dali.jqgufenzy.top/Article/details/gtumklafsy.html

ssh user@host 'uptime'
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnecdpxhw.html

[R58] 下载文件
来源：http://dali.ydzc1.top/Article/details/gtafqzrnmt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xuanzx.com/Article/details/gtlrouvtfy.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gtahmevrud.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.fengsongda.top/Article/details/gtfoigfiuk.html

[R60] 只看 HTTP 状态码
来源：http://dali.kuanghao11.cn/Article/details/gtxamrvacw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.pycfn.com/Article/details/gteumutyct.html

[R61] 磁盘占用
来源：http://dali.ehwqpu.com/Article/details/gtkndqupgk.html


<!-- 参考信息 -->