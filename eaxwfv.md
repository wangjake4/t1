代发 wailian999

[Q14] 存在则更新（upsert）
来源：http://dali.ehwqpu.com/Article/details/gtyrqhjwgr.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.sysykeji.top/Article/details/gtymucpgkf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.tanke756.top/Article/details/gtznfgtgek.html

[Q15] 查询全部
来源：http://dali.jinqigfzy.top/Article/details/gtshdgfbso.html

SELECT * FROM users;
来源：http://dali.tanke756.top/Article/details/gtfsxwulcp.html

[Q16] 查询指定列
来源：http://dali.snrcjt.cn/Article/details/gtwggnifnz.html

SELECT id, name FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtadvuedio.html

[Q17] 条件查询
来源：http://dali.hywenlv.cn/Article/details/gtyllzbsso.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.yongpay.top/Article/details/gtrxuqtrkq.html

[Q18] 模糊匹配
来源：http://dali.aibaodan.cn/Article/details/gtwtmjisbd.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.havefunace.top/Article/details/gtgbgqgnfu.html

[Q19] 范围查询
来源：http://dali.aibaodan.cn/Article/details/gtliakizfv.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.shanyushiyangtech.top/Article/details/gtqsqvzres.html

[Q20] IN 列表
来源：http://dali.shzxlz.cn/Article/details/gtbgouolpu.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtbfierbcl.html

[Q21] 空值判断
来源：http://dali.shanyushiyangtech.top/Article/details/gtpfmjoweo.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.guowangkeji.top/Article/details/gtzdsoined.html

[Q22] 排序
来源：http://dali.xylfe.cn/Article/details/gtvzrhvamf.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zdqjudy.top/Article/details/gtodhcbubb.html

[Q23] 分页
来源：http://dali.xziqi.cn/Article/details/gtzxljdkdi.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hnxiangtu.top/Article/details/gtfgoktsvw.html

[Q24] 去重
来源：http://dali.hfpthk.cn/Article/details/gtuairwgpl.html

SELECT DISTINCT city FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gttsvfinti.html

[Q25] 只取前 N 条
来源：http://dali.zhixingplan.top/Article/details/gtiqasqdal.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gogol.net.cn/Article/details/gttpptlhay.html

[Q26] 计数
来源：http://dali.hammf.cn/Article/details/gtxczroevo.html

SELECT COUNT(*) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtzpveqkjd.html

[Q27] 条件计数
来源：http://dali.tianlin.xyz/Article/details/gtmwkocjhn.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shangyingyoupin.top/Article/details/gtkyrnvgwu.html

[Q28] 求和与平均
来源：http://dali.hnxiangtu.top/Article/details/gtxeywybyv.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.bjfxy.top/Article/details/gttkclyeyu.html

[Q29] 最大最小值
来源：http://dali.hywenlv.cn/Article/details/gtmgmbviko.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtymvpxsez.html

[Q30] 分组统计
来源：http://dali.shzxlz.cn/Article/details/gtfqmguaqd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.dianchejie.cn/Article/details/gtrvjwsfrw.html

[Q31] 分组后过滤
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjtlrcoca.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.sweek.top/Article/details/gtyeadoyke.html

[Q32] 分组拼接字符串
来源：http://dali.kuanghao11.cn/Article/details/gtljqktuok.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ppjwa.cn/Article/details/gtobdiliqu.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hongshengwenyu.top/Article/details/gtlonhcyuh.html

[Q33] 多列分组
来源：http://dali.ybcxt.top/Article/details/gtlpqxawed.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yanxiufei.cn/Article/details/gtuisjsnha.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gtmfiprnux.html

SELECT * FROM (
来源：http://dali.feifeiyinyue.top/Article/details/gtdiiisjkv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.dashuyun.cn/Article/details/gtqftoybio.html

) t WHERE rn = 1;
来源：http://dali.yuanzhike.top/Article/details/gtqzffrevb.html

[Q35] 内连接
来源：http://dali.iojbl.cn/Article/details/gthbnkthas.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.jiagoushi.top/Article/details/gthriyvjdl.html

[Q36] 左连接
来源：http://dali.daria6918.cn/Article/details/gtmcnqkdea.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yangfankeji.com/Article/details/gtfimfnuwn.html

[Q37] 右连接
来源：http://dali.vqdsnc.cn/Article/details/gtvwehewyh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.mhx1999.top/Article/details/gtzobexwgf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jlsjyb.cn/Article/details/gtntjyvkap.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.snrcjt.cn/Article/details/gtnkycrpfn.html

[Q39] 自连接（查上下级）
来源：http://dali.wangdashe.top/Article/details/gtyqxvuyny.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.fzhhl.top/Article/details/gthyckdfby.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.yuanzhike.top/Article/details/gtopvkipok.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.316326.xyz/Article/details/gtxajkdxml.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.bjfxy.top/Article/details/gtgqardqgn.html

[Q41] 多表连接
来源：http://dali.bjfxy.top/Article/details/gtosyggsgx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ivvv.top/Article/details/gtccjxdwor.html

JOIN users u ON u.id = o.user_id
来源：http://dali.316326.xyz/Article/details/gtywaxcinr.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.ybcxt.top/Article/details/gtoxseptca.html

[Q42] 连接条件附加过滤
来源：http://dali.jinyuanbaomall.cn/Article/details/gturfswvrd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.gaohongyu789.top/Article/details/gtgyqcscmw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.chenlongwang.top/Article/details/gtjszalavd.html

[Q43] 标量子查询
来源：http://dali.zdqjudy.top/Article/details/gtiefqqfrq.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.quarkkingdee.top/Article/details/gtcauaphzo.html

[Q44] IN 子查询
来源：http://dali.sweek.top/Article/details/gtkbebxtaa.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yangfankeji.com/Article/details/gthsctggpp.html

[Q45] EXISTS 判断存在
来源：http://dali.jinqigfzy.top/Article/details/gtgfqciqrs.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgrrvfrel.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.dashuyun.cn/Article/details/gtvxnzaokn.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.mhx1999.top/Article/details/gtrflswibf.html

[Q47] 与平均值比较
来源：http://dali.gzhubu.top/Article/details/gtvpjqwnpm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zdqjudy.top/Article/details/gtuxfnwdqp.html

[Q48] CTE 公用表表达式
来源：http://dali.yonumen.top/Article/details/gtvgajqhrf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gtagfpnokx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.fzhhl.top/Article/details/gtvstuvnoh.html

[Q49] 更新单行
来源：http://dali.yuanzhike.top/Article/details/gtqhnipkfa.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.sweek.top/Article/details/gtbybgkhzv.html

[Q50] 批量更新
来源：http://dali.cheryme.top/Article/details/gtbbpfaalc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.aizwys.cn/Article/details/gtpxllbtbs.html

[Q51] 用子查询更新
来源：http://dali.daria6918.cn/Article/details/gtvoorayde.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sweek.top/Article/details/gtkemjorhg.html

[Q52] 删除指定行
来源：http://dali.hfpthk.cn/Article/details/gtaglhvwlz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gthiomskwf.html

[Q53] 按条件删除
来源：http://dali.yongpay.top/Article/details/gtrdpoohjs.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.mhx1999.top/Article/details/gtiurfcijd.html

[Q54] 清空表
来源：http://dali.guannengcc.top/Article/details/gtuadmaklr.html

TRUNCATE TABLE logs;
来源：http://dali.haohaochexian.top/Article/details/gtflcbhqjw.html

[Q55] 排名（并列占位）
来源：http://dali.wangshuangyany.cn/Article/details/gtqgrkjgvw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.wangshuangyany.cn/Article/details/gtnpfbhqtp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ppjwa.cn/Article/details/gtkgwetqol.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.chenzaomai.com/Article/details/gtnswvoqis.html

[Q57] 行号
来源：http://dali.shanyushiyangkeji.top/Article/details/gtccehgbiv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.tanke756.top/Article/details/gteokatqjs.html

[Q58] 累计求和
来源：http://dali.jinghuilouyu.cn/Article/details/gtyxshsvzz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.smart0.xyz/Article/details/gtaxoyxiox.html

[Q59] 分组内累计
来源：http://dali.sufxvd.cn/Article/details/gtwxpqwcta.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gtrwbdhrjl.html

[Q60] 取上一行 / 下一行
来源：http://dali.jinqigfzy.top/Article/details/gtkkrjzxlm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.fengsongda.top/Article/details/gtxnvtyzik.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhixingplan.top/Article/details/gtfwfgvtib.html

[Q61] 移动平均
来源：http://dali.kuanghao11.cn/Article/details/gtcryihccd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jianghu66.top/Article/details/gtuztmzics.html

[Q62] 分组占比
来源：http://dali.snrcjt.cn/Article/details/gtsiyrirwt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.kuanghao11.cn/Article/details/gtfllfnyfa.html

[Q63] 开启事务
来源：http://dali.yj202588.top/Article/details/gttsqrugsk.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cheryme.top/Article/details/gttozhkfad.html

[Q64] 提交事务
来源：http://dali.sweek.top/Article/details/gtdxquphip.html

COMMIT;
来源：http://dali.yuxming.cn/Article/details/gtnmqazeuo.html

[Q65] 回滚事务
来源：http://dali.fengsongda.top/Article/details/gtbtewbgiy.html

ROLLBACK;
来源：http://dali.jinyuanbaomall.cn/Article/details/gthabcagbq.html

[Q66] 行锁查询
来源：http://dali.ydzc1.top/Article/details/gtuvxxlomh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.snrcjt.cn/Article/details/gtzqjmeaew.html

[Q67] 设置隔离级别
来源：http://dali.9152youxi.cn/Article/details/gtbcsncvba.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhoulong.xyz/Article/details/gtxjiilmps.html

[Q68] 保存点
来源：http://dali.dashuyun.cn/Article/details/gtiwqfezne.html

SAVEPOINT sp1;
来源：http://dali.svipenyu.cn/Article/details/gtjkvnlyba.html

ROLLBACK TO sp1;
来源：http://dali.c1oappe.top/Article/details/gtoosbukci.html

[Q69] 查看执行计划
来源：http://dali.kuanghao11.cn/Article/details/gtuwtzmjbq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.chenzaomai.com/Article/details/gtjjilfyjp.html

[Q70] 更新统计信息
来源：http://dali.zhongyouzk.top/Article/details/gtojczgemk.html

ANALYZE TABLE users;
来源：http://dali.dianchejie.cn/Article/details/gtghqomikm.html

[Q71] 查看建表语句
来源：http://dali.hnqzz.top/Article/details/gtimdnblvo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.316326.xyz/Article/details/gtiunztcce.html

[Q72] 查看索引
来源：http://dali.316326.xyz/Article/details/gtlywbqdfq.html

SHOW INDEX FROM users;
来源：http://dali.wangdashe.top/Article/details/gtcolqzvxh.html

[Q73] 查看表状态
来源：http://dali.meibo888.top/Article/details/gtrjlmwerg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhengqikj.top/Article/details/gtngqvwufv.html

[Q74] 强制使用索引
来源：http://dali.gotoacloud.top/Article/details/gteupkkyqs.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xuetiantiany.cn/Article/details/gtykkrnqqq.html

[Q75] 日期格式化
来源：http://dali.gotoacloud.top/Article/details/gtekohqzey.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sysykeji.top/Article/details/gtokcwopvd.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.snrcjt.cn/Article/details/gtcfbahmhj.html

[Q76] 按天统计
来源：http://dali.chenlongwang.top/Article/details/gtfzmnzjza.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hammf.cn/Article/details/gtsythwskb.html

[Q77] 时间加减
来源：http://dali.jqgfzy.top/Article/details/gtartrtwav.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.gaohongyu789.top/Article/details/gtcatpsosr.html

[Q78] 当前时间
来源：http://dali.tian-w.cn/Article/details/gtgtktbner.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.birdmap.top/Article/details/gtzlrpmkbh.html

[Q79] 字符串拼接
来源：http://dali.pengpengdd.cyou/Article/details/gtujgqoxmr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.pycfn.com/Article/details/gtwpbqvdxx.html

[Q80] 字符串截取
来源：http://dali.fzhhl.top/Article/details/gtcnfpzikr.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ivvv.top/Article/details/gtfflcsody.html

[Q81] 字符串替换
来源：http://dali.hammf.cn/Article/details/gtntuplokj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtjnywtldr.html

[Q82] 字符长度与字节长度
来源：http://dali.fzhhl.top/Article/details/gtevcgxprc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtebdbckrr.html

[Q83] 大小写转换
来源：http://dali.ywan-chungtsiang.top/Article/details/gticlivnvs.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.xinyue.icu/Article/details/gtwpfqlmii.html

[Q84] 去除首尾空格
来源：http://dali.quarkkingdee.top/Article/details/gtfxtmwuah.html

SELECT TRIM(name) FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtlpgmctoh.html

[Q85] 数值取整
来源：http://dali.zycfv.cn/Article/details/gtdqvpskqc.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sxryk.cn/Article/details/gtimjynjop.html

[Q86] 读取 JSON 字段
来源：http://dali.jinqigfzy.top/Article/details/gtbcjichzp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.aizwys.cn/Article/details/gtctmpsgfm.html

[Q87] JSON 字段做条件
来源：http://dali.snrcjt.cn/Article/details/gtezssygme.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zycfv.cn/Article/details/gtywqfqiki.html

[Q88] 行转列（条件聚合）
来源：http://dali.yuxming.cn/Article/details/gtboahjzoi.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ydzc1.top/Article/details/gtogxsujzy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtphjetkoy.html

[Q89] 判断表是否存在
来源：http://dali.shanyushiyangtech.top/Article/details/gteypprudh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.andypj.xyz/Article/details/gtdzstekjv.html

[Q90] 生成序号列
来源：http://dali.cdnleiting.top/Article/details/gtaeurnsab.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.smart0.xyz/Article/details/gtervxkurk.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtztcintyk.html

R. Bash 专题
来源：http://dali.zycfv.cn/Article/details/gtrtkzoazl.html

================================================================================
来源：http://dali.gotoacloud.top/Article/details/gtjigkndgz.html

[R01] shebang 与严格模式
来源：http://dali.tian-w.cn/Article/details/gtzlzmmfxt.html

#!/usr/bin/env bash
来源：http://dali.zdqjudy.top/Article/details/gthxqtscej.html

set -euo pipefail
来源：http://dali.hnxiangtu.top/Article/details/gtbtczpakm.html

[R02] 变量赋值与使用
来源：http://dali.jinqigfzy.top/Article/details/gtybwqwpwg.html

name="Tom"; echo "$name"
来源：http://dali.gogol.net.cn/Article/details/gtxmomjals.html

[R03] 只读变量
来源：http://dali.cashguo.top/Article/details/gtnfwakryt.html

readonly PI=3.14
来源：http://dali.jiagoushi.top/Article/details/gtutwqvomr.html

[R04] 位置参数
来源：http://dali.gzhubu.top/Article/details/gtxhlgrkrn.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.pycfn.com/Article/details/gtqlqtbvuj.html

[R05] 参数默认值
来源：http://dali.havefunace.top/Article/details/gtdjlxhmsl.html

name="${1:-default}"
来源：http://dali.fzhhl.top/Article/details/gtjnxovgud.html

[R06] 判断命令是否存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gttgtjhmwt.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.c1oappe.top/Article/details/gtfcppnxyz.html

[R07] if 判断文件
来源：http://dali.chenjidiqi.icu/Article/details/gtucidijqt.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gttocgtotx.html

[R08] 数值比较
来源：http://dali.ydzc1.top/Article/details/gtukuvrgds.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yj20258888.top/Article/details/gtdvjixqol.html

[R09] 字符串比较
来源：http://dali.nanxuanxn.top/Article/details/gtioppjwpj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jqgufenzy.top/Article/details/gtscifjrtm.html

[R10] 正则匹配
来源：http://dali.daxiang520.top/Article/details/gtrkintcjk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.316326.xyz/Article/details/gtvykydwjr.html

[R11] case 多分支
来源：http://dali.jiagoushi.top/Article/details/gtizsnmsbv.html

case "$1" in
来源：http://dali.chenlongwang.top/Article/details/gtztgqhqgy.html

start) echo "启动" ;;
来源：http://dali.jinyuanbaomall.cn/Article/details/gttivpntne.html

stop)  echo "停止" ;;
来源：http://dali.c1oappe.top/Article/details/gtrmejnnes.html

*)     echo "未知命令" ;;
来源：http://dali.redwolf501.top/Article/details/gtjwhfhpue.html

esac
来源：http://dali.tanke756.top/Article/details/gtbjczdthp.html

[R12] for 遍历文件
来源：http://dali.svipenyu.cn/Article/details/gttvajgbus.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvsxkqwot.html

[R13] for 计数循环
来源：http://dali.yangfankeji.com/Article/details/gtiqlkjgwl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hnqzz.top/Article/details/gtjmrtxqey.html

[R14] C 风格 for
来源：http://dali.hfpthk.cn/Article/details/gtjupanbfn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.316326.xyz/Article/details/gtltxzpoog.html

[R15] while 逐行读文件
来源：http://dali.hywenlv.cn/Article/details/gtlbirukgt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yvedp.cn/Article/details/gtkvxlebhq.html

[R16] until 等待条件
来源：http://dali.svipenyu.cn/Article/details/gtuvhdwfpv.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hongshengwenyu.top/Article/details/gtuzmztnka.html

[R17] 数组定义与取值
来源：http://dali.316326.xyz/Article/details/gtjwayxsiw.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.tanke756.top/Article/details/gtncwxcvxk.html

[R18] 遍历数组
来源：http://dali.hnqzz.top/Article/details/gteipiutpk.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xziqi.cn/Article/details/gtstnizvqw.html

[R19] 数组长度
来源：http://dali.chenjidiqi.icu/Article/details/gtpigdlljn.html

echo "${#arr[@]}"
来源：http://dali.chenlongwang.top/Article/details/gtxnvdkdlp.html

[R20] 关联数组（字典）
来源：http://dali.ppjwa.cn/Article/details/gtcpfckeed.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.nanxinkj.top/Article/details/gtmlukenxb.html

[R21] 字符串长度
来源：http://dali.yj20258.top/Article/details/gtclwefzyn.html

echo "${#s}"
来源：http://dali.jqgufenzy.top/Article/details/gtwhsuvpzg.html

[R22] 截取子串
来源：http://dali.bjfxy.top/Article/details/gtonyycftt.html

echo "${s:0:5}"
来源：http://dali.tianlin.xyz/Article/details/gtfbacdkmc.html

[R23] 字符串替换
来源：http://dali.nanxinkj.top/Article/details/gtokfryovl.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gtozakixpo.html

[R24] 大小写转换
来源：http://dali.nanxinkj.top/Article/details/gtlnedihwe.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shuidangran.top/Article/details/gtdzowydru.html

[R25] 去后缀 / 去前缀
来源：http://dali.yuxming.cn/Article/details/gtjncdbjdo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shzxlz.cn/Article/details/gthcsmyusr.html

[R26] 命令替换
来源：http://dali.zycfv.cn/Article/details/gtuxpekklc.html

now=$(date +%F); echo "$now"
来源：http://dali.hnxiangtu.top/Article/details/gtmwwhrmxf.html

[R27] 算术展开
来源：http://dali.andypj.xyz/Article/details/gtxqitmneo.html

echo $((1 + 2 * 3))
来源：http://dali.daxiang520.top/Article/details/gtdwatqrpu.html

[R28] 浮点运算
来源：http://dali.gaohongyu789.top/Article/details/gtsridolqs.html

echo "scale=2; 10/3" | bc
来源：http://dali.hongshengwenyu.top/Article/details/gtxmfrvvxd.html

[R29] 定义函数
来源：http://dali.feifeiyinyue.top/Article/details/gtxtujiaft.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.haohaochexian.top/Article/details/gtaluuxmdu.html

[R30] 函数返回状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gtgdtmbuap.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hnxiangtu.top/Article/details/gtsrnduzxp.html

[R31] 局部变量
来源：http://dali.shzxlz.cn/Article/details/gtxpkuhcrp.html

f() { local x=1; echo "$x"; }
来源：http://dali.aibaodan.cn/Article/details/gtocmjmbba.html

[R32] 参数个数校验
来源：http://dali.tianlin.xyz/Article/details/gtkacwniuz.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ydzc1.top/Article/details/gtfxjdzgkh.html

[R33] 捕获错误并提示行号
来源：http://dali.snrcjt.cn/Article/details/gtzchzslor.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.daxiang520.top/Article/details/gtbaztkbue.html

[R34] 退出时清理
来源：http://dali.xylfe.cn/Article/details/gtnzehubss.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigufen.top/Article/details/gtspyzdujo.html

[R35] 后台执行并等待
来源：http://dali.mhx1999.top/Article/details/gtpqiievxv.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.cashguo.top/Article/details/gticxznevf.html

[R36] 并发执行多个任务
来源：http://dali.jinqigufen.top/Article/details/gtznosaniy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xinyue.icu/Article/details/gtequfkkgw.html

[R37] 把输出赋给变量
来源：http://dali.daxiang520.top/Article/details/gtekmkkkxw.html

files=$(ls -1)
来源：http://dali.yanxiufei.cn/Article/details/gtvmdcgmsl.html

[R38] 管道串联
来源：http://dali.yangfankeji.com/Article/details/gttmufuadh.html

cat a.txt | grep -i error | wc -l
来源：http://dali.bjfxy.top/Article/details/gtycjuufsk.html

[R39] 重定向标准输出与错误
来源：http://dali.zhoulong.xyz/Article/details/gtlopjvahp.html

cmd > out.log 2>&1
来源：http://dali.pycfn.com/Article/details/gtvtkfbupt.html

[R40] 追加写日志
来源：http://dali.c1oappe.top/Article/details/gtkuktbgcc.html

echo "log" >> out.log
来源：http://dali.gaohongyu789.top/Article/details/gtverprlph.html

[R41] 丢弃输出
来源：http://dali.yangfankeji.com/Article/details/gtkakgmqam.html

cmd >/dev/null 2>&1
来源：http://dali.ehwqpu.com/Article/details/gttebsrfpt.html

[R42] 输入重定向
来源：http://dali.yueranfly.top/Article/details/gtflakkdrt.html

wc -l < a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtoaatimxb.html

[R43] 按名字查找文件
来源：http://dali.ydzc1.top/Article/details/gtmjuuaijd.html

find . -name "*.log" -type f
来源：http://dali.jyoumei.cn/Article/details/gtjmrshkum.html

[R44] 按修改时间查找
来源：http://dali.fzhhl.top/Article/details/gtbqahmtev.html

find . -mtime -7 -type f
来源：http://dali.nwbrower.top/Article/details/gtvoousmsa.html

[R45] 批量删除
来源：http://dali.ybcxt.top/Article/details/gtupfkaccc.html

find . -name "*.tmp" -delete
来源：http://dali.zhoulong.xyz/Article/details/gtbnibuxzx.html

[R46] 递归替换文件内容
来源：http://dali.xziqi.cn/Article/details/gtgjcmajjp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.gotoacloud.top/Article/details/gtgctrakfb.html

[R47] sed 单行替换
来源：http://dali.tianlin.xyz/Article/details/gtxtmakxxa.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.nwbrower.top/Article/details/gtjpkjftdw.html

[R48] awk 取指定列
来源：http://dali.tanke756.top/Article/details/gtnjhxrrkd.html

awk '{print $1, $3}' a.txt
来源：http://dali.ppjwa.cn/Article/details/gtlrtvriio.html

[R49] awk 带条件
来源：http://dali.daxiang520.top/Article/details/gtourcirtb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.bjfxy.top/Article/details/gtfzybdgkj.html

[R50] awk 求和
来源：http://dali.gotoacloud.top/Article/details/gtvdyhzycg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gttuacumzx.html

[R51] 排序去重取前几
来源：http://dali.nanxuanxn.top/Article/details/gttekxvhyj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ppjwa.cn/Article/details/gtaedhyicr.html

[R52] 统计行数
来源：http://dali.tianlin.xyz/Article/details/gtbqsdhads.html

wc -l a.txt
来源：http://dali.shuidangran.top/Article/details/gtqfgojaof.html

[R53] 查看文件头与实时尾
来源：http://dali.yueranfly.top/Article/details/gtllcbisbp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.birdmap.top/Article/details/gtfhlpnqga.html

[R54] 比较两个文件
来源：http://dali.dashuyun.cn/Article/details/gtywlqxoce.html

diff a.txt b.txt
来源：http://dali.bjfxy.top/Article/details/gthgjbeazc.html

[R55] 压缩与解压
来源：http://dali.feifeiyinyue.top/Article/details/gtilallpko.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinqigufen.top/Article/details/gtonxchtfr.html

[R56] 远程拷贝
来源：http://dali.yj20258.top/Article/details/gtqgkfzqpu.html

scp file user@host:/path/
来源：http://dali.yanxiufei.cn/Article/details/gtabuludek.html

[R57] 远程执行命令
来源：http://dali.gzhubu.top/Article/details/gtofyuyych.html

ssh user@host 'uptime'
来源：http://dali.yj202588.top/Article/details/gtbwwponny.html

[R58] 下载文件
来源：http://dali.redwolf501.top/Article/details/gtupklihde.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.shuidangran.top/Article/details/gtkxiydzgf.html

[R59] 发 POST JSON
来源：http://dali.316326.xyz/Article/details/gtkltflfhe.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yonumen.top/Article/details/gtavdgijuh.html

[R60] 只看 HTTP 状态码
来源：http://dali.0kj1m.cn/Article/details/gtvmxqdewb.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.andypj.xyz/Article/details/gtodtuirie.html

[R61] 磁盘占用
来源：http://dali.nanxuanxn.top/Article/details/gtbrtnyhzv.html

df -h;  du -sh *
来源：http://dali.kuanghao11.cn/Article/details/gtpdmfjbbq.html

[R62] 找最占空间的文件
来源：http://dali.yueranfly.top/Article/details/gtilhhewpm.html

du -ah . | sort -rh | head -10
来源：http://dali.jqgufenzy.top/Article/details/gtbpiflwzg.html

[R63] 内存与进程
来源：http://dali.jqgufenzy.top/Article/details/gtkokszovi.html


<!-- 参考信息 -->