代发 wailian999

INSERT INTO users (name) VALUES ('C');
来源：http://dali.birdmap.top/Article/details/gtooqojmyn.html

SELECT LAST_INSERT_ID();          -- PostgreSQL: INSERT ... RETURNING id
来源：http://dali.mhx1999.top/Article/details/gtwnocqdys.html

[Q13] 忽略重复插入
来源：http://dali.bjfxy.top/Article/details/gtrvjgmhjw.html

INSERT IGNORE INTO users (email) VALUES ('a@a.com');
来源：http://dali.hfpthk.cn/Article/details/gtipumvokg.html

[Q14] 存在则更新（upsert）
来源：http://dali.0kj1m.cn/Article/details/gtpqnwvuyj.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.fzhhl.top/Article/details/gtgcwurqql.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.kuanghao11.cn/Article/details/gtisrklbsk.html

[Q15] 查询全部
来源：http://dali.gzhubu.top/Article/details/gttorqenbi.html

SELECT * FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtayejhdlw.html

[Q16] 查询指定列
来源：http://dali.sysykeji.top/Article/details/gtenhnyagv.html

SELECT id, name FROM users;
来源：http://dali.ivvv.top/Article/details/gtnpptvyxz.html

[Q17] 条件查询
来源：http://dali.jqgfzy.top/Article/details/gtplxbauyd.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhijiandao.cn/Article/details/gtesarajcs.html

[Q18] 模糊匹配
来源：http://dali.hongshengwenyu.top/Article/details/gteoljscup.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.mhx1999.top/Article/details/gttsuuhwxd.html

[Q19] 范围查询
来源：http://dali.shzxlz.cn/Article/details/gteqfttfhn.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.kuanghao11.cn/Article/details/gtzuyzuxer.html

[Q20] IN 列表
来源：http://dali.yuxming.cn/Article/details/gtwbkexrmo.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.daxiang520.top/Article/details/gtdbxmroiw.html

[Q21] 空值判断
来源：http://dali.316326.xyz/Article/details/gtbmceexuw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sufxvd.cn/Article/details/gtzplsslvr.html

[Q22] 排序
来源：http://dali.hammf.cn/Article/details/gtxfgsfeaz.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.bjfxy.top/Article/details/gtsjnaeepr.html

[Q23] 分页
来源：http://dali.daxiang520.top/Article/details/gtouiyfvbx.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yongpay.top/Article/details/gtrfxystvh.html

[Q24] 去重
来源：http://dali.jinghuilouyu.cn/Article/details/gtnqhnjfty.html

SELECT DISTINCT city FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtzdwdotjl.html

[Q25] 只取前 N 条
来源：http://dali.xylfe.cn/Article/details/gtxbmsfdfj.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hongshengwenyu.top/Article/details/gtmyrxaesl.html

[Q26] 计数
来源：http://dali.birdmap.top/Article/details/gtourljbjg.html

SELECT COUNT(*) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtvodgddwt.html

[Q27] 条件计数
来源：http://dali.jinqigfzy.top/Article/details/gtmweowhkg.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtaoxspgbh.html

[Q28] 求和与平均
来源：http://dali.tanke756.top/Article/details/gtbljmsqys.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gtsxefmszt.html

[Q29] 最大最小值
来源：http://dali.316326.xyz/Article/details/gtbdoosjey.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtpzgzkjqg.html

[Q30] 分组统计
来源：http://dali.ybcxt.top/Article/details/gtkyjsiwqt.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.cqqwz.cn/Article/details/gtlmtenqzb.html

[Q31] 分组后过滤
来源：http://dali.yj202588.top/Article/details/gtpgjcuaqn.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.nanxuanxn.top/Article/details/gtpcvxkqui.html

[Q32] 分组拼接字符串
来源：http://dali.yvedp.cn/Article/details/gtdjnsclvm.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.fengsongda.top/Article/details/gtjmnmokli.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jianghu66.top/Article/details/gtouaadywt.html

[Q33] 多列分组
来源：http://dali.cashguo.top/Article/details/gtoqhapybf.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.hnqzz.top/Article/details/gtlcgpukmh.html

[Q34] 每组取第一条
来源：http://dali.tianlin.xyz/Article/details/gtvkacxmxl.html

SELECT * FROM (
来源：http://dali.yvedp.cn/Article/details/gtybtmwswx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.dianchejie.cn/Article/details/gtrbuadzbe.html

) t WHERE rn = 1;
来源：http://dali.daria6918.cn/Article/details/gtyyovsmhi.html

[Q35] 内连接
来源：http://dali.sysykeji.top/Article/details/gtqraxxglj.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.smart0.xyz/Article/details/gtbgvxpnfz.html

[Q36] 左连接
来源：http://dali.shangyingyoupin.top/Article/details/gtyttxruwt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.iojbl.cn/Article/details/gtuombvayu.html

[Q37] 右连接
来源：http://dali.kuanghao11.cn/Article/details/gtsgtwhejw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhoulong.xyz/Article/details/gtjhciplhe.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.sufxvd.cn/Article/details/gtilpzswnd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.svipenyu.cn/Article/details/gtffohzqxg.html

[Q39] 自连接（查上下级）
来源：http://dali.chenlongwang.top/Article/details/gtlpojyguq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yuanzhike.top/Article/details/gtxeusrtml.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hongshengwenyu.top/Article/details/gtqbtygvdw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.ybcxt.top/Article/details/gtshzcwyxl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hongshengwenyu.top/Article/details/gtnutnckak.html

[Q41] 多表连接
来源：http://dali.hywenlv.cn/Article/details/gtnezoejlj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shzxlz.cn/Article/details/gtrdedwpmi.html

JOIN users u ON u.id = o.user_id
来源：http://dali.guannengcc.top/Article/details/gtugyvjtha.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xinyue.icu/Article/details/gtkfslkycn.html

[Q42] 连接条件附加过滤
来源：http://dali.haohaochexian.top/Article/details/gtuiyhzkeb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.kuanghao11.cn/Article/details/gtjecadzds.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xinyue.icu/Article/details/gtlizgrwne.html

[Q43] 标量子查询
来源：http://dali.tanke756.top/Article/details/gtzcpohhza.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ppjwa.cn/Article/details/gtldnoscou.html

[Q44] IN 子查询
来源：http://dali.cdnleiting.top/Article/details/gtvhzfbmye.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.snrcjt.cn/Article/details/gtnhlpqibm.html

[Q45] EXISTS 判断存在
来源：http://dali.nanxinkj.top/Article/details/gtszygpcdu.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ehwqpu.com/Article/details/gtqxjsyinv.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcojnbakz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.feifeiyinyue.top/Article/details/gtvgbqbatw.html

[Q47] 与平均值比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbtpatszp.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sysykeji.top/Article/details/gttgadzqxm.html

[Q48] CTE 公用表表达式
来源：http://dali.yuanzhike.top/Article/details/gtpfmukdjl.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sxryk.cn/Article/details/gtgwzwjmia.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.aibaodan.cn/Article/details/gtnainvecv.html

[Q49] 更新单行
来源：http://dali.dianchejie.cn/Article/details/gtbvoptwto.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.wangdashe.top/Article/details/gtdzblwloc.html

[Q50] 批量更新
来源：http://dali.hongshengwenyu.top/Article/details/gtsjjiiyhk.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cdnleiting.top/Article/details/gtyoqalrij.html

[Q51] 用子查询更新
来源：http://dali.havefunace.top/Article/details/gthghzcigi.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtzecyisbg.html

[Q52] 删除指定行
来源：http://dali.gogol.net.cn/Article/details/gtecspgmep.html

DELETE FROM users WHERE id = 10;
来源：http://dali.guowangkeji.top/Article/details/gtsgulkgue.html

[Q53] 按条件删除
来源：http://dali.zhengqikj.top/Article/details/gttfgndciy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.sysykeji.top/Article/details/gtrwhsqrof.html

[Q54] 清空表
来源：http://dali.hnqzz.top/Article/details/gtlmzvywup.html

TRUNCATE TABLE logs;
来源：http://dali.yj20258.top/Article/details/gtbfcaofmc.html

[Q55] 排名（并列占位）
来源：http://dali.shzxlz.cn/Article/details/gtuzlukyfi.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.daria6918.cn/Article/details/gtgjymbviy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.andypj.xyz/Article/details/gtdylwbmwm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.xylfe.cn/Article/details/gtkmwzczpv.html

[Q57] 行号
来源：http://dali.zdqjudy.top/Article/details/gtxpictxps.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xinyue.icu/Article/details/gtvhpfayrk.html

[Q58] 累计求和
来源：http://dali.xinyue.icu/Article/details/gtxpvuljcy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtprgpridw.html

[Q59] 分组内累计
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnqhfrjao.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.cdnleiting.top/Article/details/gtqakbfyvo.html

[Q60] 取上一行 / 下一行
来源：http://dali.shuidangran.top/Article/details/gtylrfvwjc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.redwolf501.top/Article/details/gtpxtabqhu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gtsdiwfulc.html

[Q61] 移动平均
来源：http://dali.yj20258888.top/Article/details/gtbpwzkeml.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.quarkkingdee.top/Article/details/gtcadbdzue.html

[Q62] 分组占比
来源：http://dali.chenlongwang.top/Article/details/gtifbntdao.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.pycfn.com/Article/details/gtjfboogdg.html

[Q63] 开启事务
来源：http://dali.hnxiangtu.top/Article/details/gtfpbhvwks.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.hnxiangtu.top/Article/details/gtgyklklmh.html

[Q64] 提交事务
来源：http://dali.svipenyu.cn/Article/details/gtkxyzihwu.html

COMMIT;
来源：http://dali.gotoacloud.top/Article/details/gtrvsviitd.html

[Q65] 回滚事务
来源：http://dali.dashuyun.cn/Article/details/gtvnyplhzx.html

ROLLBACK;
来源：http://dali.yj20258888.top/Article/details/gtyxyeekaj.html

[Q66] 行锁查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtttkzmfpk.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.zdqjudy.top/Article/details/gtpzmuzxzq.html

[Q67] 设置隔离级别
来源：http://dali.nanxinkj.top/Article/details/gticuijydn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.cqqwz.cn/Article/details/gtfbfcqcfc.html

[Q68] 保存点
来源：http://dali.sxryk.cn/Article/details/gtzehvvfkm.html

SAVEPOINT sp1;
来源：http://dali.dianchejie.cn/Article/details/gtgrufnuzh.html

ROLLBACK TO sp1;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwunsfdcq.html

[Q69] 查看执行计划
来源：http://dali.zhixingplan.top/Article/details/gthypfvwvp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gotoacloud.top/Article/details/gtvptwlprh.html

[Q70] 更新统计信息
来源：http://dali.sxryk.cn/Article/details/gtmqyjmyaw.html

ANALYZE TABLE users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtukekuhgi.html

[Q71] 查看建表语句
来源：http://dali.daxiang520.top/Article/details/gtgclurwni.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuuhwyrhd.html

[Q72] 查看索引
来源：http://dali.ivvv.top/Article/details/gtsapdrima.html

SHOW INDEX FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuwdiwexr.html

[Q73] 查看表状态
来源：http://dali.shuidangran.top/Article/details/gttoujoeox.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.pengpengdd.cyou/Article/details/gtaxedlvcf.html

[Q74] 强制使用索引
来源：http://dali.nanxinkj.top/Article/details/gtninfnqmt.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xziqi.cn/Article/details/gtjquwicbf.html

[Q75] 日期格式化
来源：http://dali.zhiwuduotai.top/Article/details/gtngwlmtbd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.tanke756.top/Article/details/gtsguzadbc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shangyingyoupin.top/Article/details/gtiaggsndg.html

[Q76] 按天统计
来源：http://dali.zycfv.cn/Article/details/gtfhwtqfts.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.dashuyun.cn/Article/details/gtomkoswyd.html

[Q77] 时间加减
来源：http://dali.ywan-chungtsiang.top/Article/details/gtidnblkvc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.snrcjt.cn/Article/details/gttzsmpuud.html

[Q78] 当前时间
来源：http://dali.zdqjudy.top/Article/details/gtmychuqmm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jqgufenzy.top/Article/details/gtafpwzhba.html

[Q79] 字符串拼接
来源：http://dali.yonumen.top/Article/details/gtaglxukef.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ydzc1.top/Article/details/gtsvouipha.html

[Q80] 字符串截取
来源：http://dali.gaohongyu789.top/Article/details/gtvnzmdvxy.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtoxnennpg.html

[Q81] 字符串替换
来源：http://dali.yangfankeji.com/Article/details/gtvaxauefw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtzhqdjwaj.html

[Q82] 字符长度与字节长度
来源：http://dali.xuanzx.com/Article/details/gtdwugyddq.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yuxming.cn/Article/details/gtjygjvtbm.html

[Q83] 大小写转换
来源：http://dali.aibaodan.cn/Article/details/gtpfifyqbm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yj20258888.top/Article/details/gtyvnuplzy.html

[Q84] 去除首尾空格
来源：http://dali.svipenyu.cn/Article/details/gtyovewtvd.html

SELECT TRIM(name) FROM users;
来源：http://dali.hfpthk.cn/Article/details/gtvmukncbp.html

[Q85] 数值取整
来源：http://dali.guowangkeji.top/Article/details/gtxeubsnbq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cheryme.top/Article/details/gtdwagghxt.html

[Q86] 读取 JSON 字段
来源：http://dali.sufxvd.cn/Article/details/gthiecgelf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.0kj1m.cn/Article/details/gthlpcunmm.html

[Q87] JSON 字段做条件
来源：http://dali.yonumen.top/Article/details/gtazjwrlxr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yj20258.top/Article/details/gtqtkiznpa.html

[Q88] 行转列（条件聚合）
来源：http://dali.xuetiantiany.cn/Article/details/gtxxfrzuxv.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hnqzz.top/Article/details/gtqidvbokb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sxryk.cn/Article/details/gtudthzzqx.html

[Q89] 判断表是否存在
来源：http://dali.zdqjudy.top/Article/details/gtaycijjru.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.svipenyu.cn/Article/details/gtdxkraekm.html

[Q90] 生成序号列
来源：http://dali.dianchejie.cn/Article/details/gtazxodtau.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ivvv.top/Article/details/gtaosrsldn.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtnyrexlut.html

R. Bash 专题
来源：http://dali.guowangkeji.top/Article/details/gtlwsdxobq.html

================================================================================
来源：http://dali.wangshuangyany.cn/Article/details/gtjcbbeuol.html

[R01] shebang 与严格模式
来源：http://dali.xylfe.cn/Article/details/gtchbysjmx.html

#!/usr/bin/env bash
来源：http://dali.shuidangran.top/Article/details/gtrkuvqgsh.html

set -euo pipefail
来源：http://dali.9152youxi.cn/Article/details/gtqdcstdxw.html

[R02] 变量赋值与使用
来源：http://dali.wangshuangyany.cn/Article/details/gtkcolydnb.html

name="Tom"; echo "$name"
来源：http://dali.birdmap.top/Article/details/gtowyvogbs.html

[R03] 只读变量
来源：http://dali.xziqi.cn/Article/details/gtsrifedvh.html

readonly PI=3.14
来源：http://dali.zhijiandao.cn/Article/details/gtefnophvo.html

[R04] 位置参数
来源：http://dali.yj20258888.top/Article/details/gtrdekiqaa.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hysaishi.cn/Article/details/gtmvikmjsf.html

[R05] 参数默认值
来源：http://dali.nanxuanxn.top/Article/details/gtulbbxtcu.html

name="${1:-default}"
来源：http://dali.feifeiyinyue.top/Article/details/gtqahhhpnv.html

[R06] 判断命令是否存在
来源：http://dali.hysaishi.cn/Article/details/gtvfhdmkwc.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.quarkkingdee.top/Article/details/gtrslumcip.html

[R07] if 判断文件
来源：http://dali.yonumen.top/Article/details/gtnqilmoah.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.tanke756.top/Article/details/gtpukwgent.html

[R08] 数值比较
来源：http://dali.zhijiandao.cn/Article/details/gtrlsshnfe.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yj202588.top/Article/details/gtnmslruwy.html

[R09] 字符串比较
来源：http://dali.yongpay.top/Article/details/gtvuvkbomo.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.mhx1999.top/Article/details/gtvwygzsvy.html

[R10] 正则匹配
来源：http://dali.quarkkingdee.top/Article/details/gtcjtizmmv.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xinyue.icu/Article/details/gtqtktqamo.html

[R11] case 多分支
来源：http://dali.smart0.xyz/Article/details/gtbfudniss.html

case "$1" in
来源：http://dali.fengsongda.top/Article/details/gtekcmjdks.html

start) echo "启动" ;;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvyqfrfoh.html

stop)  echo "停止" ;;
来源：http://dali.tanke756.top/Article/details/gtjbbhikbs.html

*)     echo "未知命令" ;;
来源：http://dali.nanxuanxn.top/Article/details/gtuymzhaih.html

esac
来源：http://dali.tanke756.top/Article/details/gtpejodepe.html

[R12] for 遍历文件
来源：http://dali.xuetiantiany.cn/Article/details/gtgvylgkxj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.dashuyun.cn/Article/details/gtshkvkymy.html

[R13] for 计数循环
来源：http://dali.kuanghao11.cn/Article/details/gtmhzsnenm.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.redwolf501.top/Article/details/gtynfpqgra.html

[R14] C 风格 for
来源：http://dali.hfpthk.cn/Article/details/gtxccwiahw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.chenlongwang.top/Article/details/gtkynwiywv.html

[R15] while 逐行读文件
来源：http://dali.tianlin.xyz/Article/details/gtfljhdfrl.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xziqi.cn/Article/details/gtnrequzbv.html

[R16] until 等待条件
来源：http://dali.cheryme.top/Article/details/gtkvkxdfab.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.nanxuanxn.top/Article/details/gtbvlphuqo.html

[R17] 数组定义与取值
来源：http://dali.cashguo.top/Article/details/gthdfpntat.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.smart0.xyz/Article/details/gtpysnpwlu.html

[R18] 遍历数组
来源：http://dali.fzhhl.top/Article/details/gtcgscfnel.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zdqjudy.top/Article/details/gtvcoykewb.html

[R19] 数组长度
来源：http://dali.svipenyu.cn/Article/details/gtkcfvanmf.html

echo "${#arr[@]}"
来源：http://dali.andypj.xyz/Article/details/gtdryndpuv.html

[R20] 关联数组（字典）
来源：http://dali.vqdsnc.cn/Article/details/gtzkkqyayo.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cqqwz.cn/Article/details/gtfoaerzob.html

[R21] 字符串长度
来源：http://dali.quarkkingdee.top/Article/details/gtrjttyfur.html

echo "${#s}"
来源：http://dali.hysaishi.cn/Article/details/gtfupwcefc.html

[R22] 截取子串
来源：http://dali.ivvv.top/Article/details/gtmandnxqy.html

echo "${s:0:5}"
来源：http://dali.shangyingyoupin.top/Article/details/gtzczwenrj.html

[R23] 字符串替换
来源：http://dali.gogol.net.cn/Article/details/gtbhhqzjfn.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttdxeefwd.html

[R24] 大小写转换
来源：http://dali.shuidangran.top/Article/details/gtzrjajocl.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.dashuyun.cn/Article/details/gtqfyxymhw.html

[R25] 去后缀 / 去前缀
来源：http://dali.gogol.net.cn/Article/details/gthlzihpgn.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yj20258.top/Article/details/gtapizrmur.html

[R26] 命令替换
来源：http://dali.hammf.cn/Article/details/gtidgwosxr.html

now=$(date +%F); echo "$now"
来源：http://dali.aibaodan.cn/Article/details/gtopapdork.html

[R27] 算术展开
来源：http://dali.zhoulong.xyz/Article/details/gtnfoympii.html

echo $((1 + 2 * 3))
来源：http://dali.jqgfzy.top/Article/details/gttalajsjd.html

[R28] 浮点运算
来源：http://dali.tanke756.top/Article/details/gtveozsbhf.html

echo "scale=2; 10/3" | bc
来源：http://dali.ivvv.top/Article/details/gtfhvcrhil.html

[R29] 定义函数
来源：http://dali.yj20258.top/Article/details/gtlqjnrbej.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.chenlongwang.top/Article/details/gtcathoyly.html

[R30] 函数返回状态码
来源：http://dali.vqdsnc.cn/Article/details/gtjontbplc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.snrcjt.cn/Article/details/gtytaqkpru.html

[R31] 局部变量
来源：http://dali.vqdsnc.cn/Article/details/gthvwgksiz.html

f() { local x=1; echo "$x"; }
来源：http://dali.dashuyun.cn/Article/details/gtmprktpfh.html

[R32] 参数个数校验
来源：http://dali.sxryk.cn/Article/details/gtnwztyavb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.smart0.xyz/Article/details/gtgntohpfb.html

[R33] 捕获错误并提示行号
来源：http://dali.quarkkingdee.top/Article/details/gtbbfbnzpa.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jlsjyb.cn/Article/details/gtlyilyomd.html

[R34] 退出时清理
来源：http://dali.sufxvd.cn/Article/details/gtmyjgjfby.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.dianchejie.cn/Article/details/gtjjrrkejn.html

[R35] 后台执行并等待
来源：http://dali.chenzaomai.com/Article/details/gtnplibwiv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.snrcjt.cn/Article/details/gtropoctud.html

[R36] 并发执行多个任务
来源：http://dali.cdnleiting.top/Article/details/gtkafdvdze.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.wangdashe.top/Article/details/gtwjbndjqe.html

[R37] 把输出赋给变量
来源：http://dali.sxryk.cn/Article/details/gtrxvyarle.html

files=$(ls -1)
来源：http://dali.sysykeji.top/Article/details/gtkxsgqgew.html

[R38] 管道串联
来源：http://dali.zhijiandao.cn/Article/details/gtdfdnqpwr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.sxryk.cn/Article/details/gtgexpsjgw.html

[R39] 重定向标准输出与错误
来源：http://dali.chenjidiqi.icu/Article/details/gtqmeovfhm.html

cmd > out.log 2>&1
来源：http://dali.xylfe.cn/Article/details/gtuenvnoqx.html

[R40] 追加写日志
来源：http://dali.316326.xyz/Article/details/gtpqnoinfl.html

echo "log" >> out.log
来源：http://dali.shzxlz.cn/Article/details/gtvnidqpai.html

[R41] 丢弃输出
来源：http://dali.xuanzx.com/Article/details/gtxhrwwqvm.html

cmd >/dev/null 2>&1
来源：http://dali.vqdsnc.cn/Article/details/gthdnoxeuh.html

[R42] 输入重定向
来源：http://dali.yonumen.top/Article/details/gtglsrqhzw.html

wc -l < a.txt
来源：http://dali.gotoacloud.top/Article/details/gtorfkvamj.html

[R43] 按名字查找文件
来源：http://dali.zdqjudy.top/Article/details/gtncabsuhk.html

find . -name "*.log" -type f
来源：http://dali.guannengcc.top/Article/details/gtwldsacfp.html

[R44] 按修改时间查找
来源：http://dali.bjfxy.top/Article/details/gtdbdqpino.html

find . -mtime -7 -type f
来源：http://dali.hfpthk.cn/Article/details/gtxrigdcna.html

[R45] 批量删除
来源：http://dali.gaohongyu789.top/Article/details/gthpcccafh.html

find . -name "*.tmp" -delete
来源：http://dali.sufxvd.cn/Article/details/gtqauaxdmp.html

[R46] 递归替换文件内容
来源：http://dali.jqgfzy.top/Article/details/gtphqcvfvt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.mhx1999.top/Article/details/gtkggztnvf.html

[R47] sed 单行替换
来源：http://dali.hongshengwenyu.top/Article/details/gtbgffqywt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.daxiang520.top/Article/details/gtasbknpke.html

[R48] awk 取指定列
来源：http://dali.yueranfly.top/Article/details/gtzemmiidl.html

awk '{print $1, $3}' a.txt
来源：http://dali.chenlongwang.top/Article/details/gtbkxkqxer.html

[R49] awk 带条件
来源：http://dali.gzhubu.top/Article/details/gtavfoxjxg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.xziqi.cn/Article/details/gtjiqngsoq.html

[R50] awk 求和
来源：http://dali.yueranfly.top/Article/details/gtmmfbqmqj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.shzxlz.cn/Article/details/gtqbayptoh.html

[R51] 排序去重取前几
来源：http://dali.havefunace.top/Article/details/gtkgffvrxe.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtaxtcrlox.html

[R52] 统计行数
来源：http://dali.meibo888.top/Article/details/gtorudxnoi.html

wc -l a.txt
来源：http://dali.gotoacloud.top/Article/details/gtrzbdosel.html

[R53] 查看文件头与实时尾
来源：http://dali.zhaomingkeji.xyz/Article/details/gtapbrdcok.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.wangshuangyany.cn/Article/details/gthifnvgsk.html

[R54] 比较两个文件
来源：http://dali.yonumen.top/Article/details/gthcorsprs.html

diff a.txt b.txt
来源：http://dali.snrcjt.cn/Article/details/gthwuyjpff.html

[R55] 压缩与解压
来源：http://dali.fzhhl.top/Article/details/gttxbdtamo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jqgufenzy.top/Article/details/gteontlhar.html

[R56] 远程拷贝
来源：http://dali.jinghuilouyu.cn/Article/details/gttkfwwduc.html

scp file user@host:/path/
来源：http://dali.cashguo.top/Article/details/gtlzshulka.html

[R57] 远程执行命令
来源：http://dali.havefunace.top/Article/details/gtilcehcub.html

ssh user@host 'uptime'
来源：http://dali.havefunace.top/Article/details/gtjqkjqqqe.html

[R58] 下载文件
来源：http://dali.yanxiufei.cn/Article/details/gtjllyilhq.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.pengpengdd.cyou/Article/details/gtxfzpokpt.html

[R59] 发 POST JSON
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthbmsmiyc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hfpthk.cn/Article/details/gtipbzutuq.html

[R60] 只看 HTTP 状态码
来源：http://dali.tianlin.xyz/Article/details/gtyypmaolw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfggmdzhs.html

[R61] 磁盘占用
来源：http://dali.tian-w.cn/Article/details/gtfiimmfos.html


<!-- 参考信息 -->