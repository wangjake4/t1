代发 wailian999

[Q14] 存在则更新（upsert）
来源：http://dali.guannengcc.top/Article/details/gtpqbknmkh.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhijiandao.cn/Article/details/gtggwqalsa.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.nanxuanxn.top/Article/details/gtjduqkcfp.html

[Q15] 查询全部
来源：http://dali.hnxiangtu.top/Article/details/gtcbgnpjic.html

SELECT * FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtcrkyobfs.html

[Q16] 查询指定列
来源：http://dali.xylfe.cn/Article/details/gthjfntgfx.html

SELECT id, name FROM users;
来源：http://dali.fengsongda.top/Article/details/gtzptnwyvu.html

[Q17] 条件查询
来源：http://dali.snrcjt.cn/Article/details/gtujkplxha.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.ehwqpu.com/Article/details/gtehefzpst.html

[Q18] 模糊匹配
来源：http://dali.zhijiandao.cn/Article/details/gtwtczclsu.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.cucudq.cn/Article/details/gtzpvbxmjw.html

[Q19] 范围查询
来源：http://dali.ppjwa.cn/Article/details/gtbyorqpkr.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.feifeiyinyue.top/Article/details/gtagaxchng.html

[Q20] IN 列表
来源：http://dali.pengpengdd.cyou/Article/details/gtfowjwuje.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.hysaishi.cn/Article/details/gtoiqppcfv.html

[Q21] 空值判断
来源：http://dali.feifeiyinyue.top/Article/details/gtlwpvemdx.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jianghu66.top/Article/details/gtrwjqaypl.html

[Q22] 排序
来源：http://dali.nanxinkj.top/Article/details/gteokthixs.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.tian-w.cn/Article/details/gtbjgcwycw.html

[Q23] 分页
来源：http://dali.redwolf501.top/Article/details/gtrzwanxat.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cucudq.cn/Article/details/gtirjboyvf.html

[Q24] 去重
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjbbtdvzk.html

SELECT DISTINCT city FROM users;
来源：http://dali.daxiang520.top/Article/details/gthgfwlvlx.html

[Q25] 只取前 N 条
来源：http://dali.shuidangran.top/Article/details/gtpsnahxcs.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.birdmap.top/Article/details/gtseeuupdm.html

[Q26] 计数
来源：http://dali.zhongyouzk.top/Article/details/gtjqmggbxe.html

SELECT COUNT(*) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtjuvvctyw.html

[Q27] 条件计数
来源：http://dali.shangyingyoupin.top/Article/details/gtfooyfhhi.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtgqamdesm.html

[Q28] 求和与平均
来源：http://dali.nanxinkj.top/Article/details/gtqufxajeq.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gtejamfjgj.html

[Q29] 最大最小值
来源：http://dali.cucudq.cn/Article/details/gtpocayqnb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yj202588.top/Article/details/gtsamicvpj.html

[Q30] 分组统计
来源：http://dali.xinyue.icu/Article/details/gtjrjrytht.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.c1oappe.top/Article/details/gtxdaeccrf.html

[Q31] 分组后过滤
来源：http://dali.shuidangran.top/Article/details/gtoyvohnvd.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jinqigufen.top/Article/details/gtqlgecvzm.html

[Q32] 分组拼接字符串
来源：http://dali.shuidangran.top/Article/details/gtimqvafmh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xinyue.icu/Article/details/gtskntnmql.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cheryme.top/Article/details/gtrtniklen.html

[Q33] 多列分组
来源：http://dali.hysaishi.cn/Article/details/gtbuurqgzk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.sweek.top/Article/details/gtubvkjmsn.html

[Q34] 每组取第一条
来源：http://dali.sufxvd.cn/Article/details/gtwfgetegj.html

SELECT * FROM (
来源：http://dali.bjfxy.top/Article/details/gtlpjpaqsr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.zhixingplan.top/Article/details/gtyrthywfe.html

) t WHERE rn = 1;
来源：http://dali.daria6918.cn/Article/details/gtoljmtwfd.html

[Q35] 内连接
来源：http://dali.pengpengdd.cyou/Article/details/gtrornvrrz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.guannengcc.top/Article/details/gtaspdyony.html

[Q36] 左连接
来源：http://dali.mhx1999.top/Article/details/gtnpxdtjrn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.birdmap.top/Article/details/gtxavbrzoj.html

[Q37] 右连接
来源：http://dali.cheryme.top/Article/details/gtbsghiaue.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhoulong.xyz/Article/details/gtaopudmtg.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.daxiang520.top/Article/details/gtigobvjma.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gogol.net.cn/Article/details/gtjylqilhl.html

[Q39] 自连接（查上下级）
来源：http://dali.wangshuangyany.cn/Article/details/gtsgoexooj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.andypj.xyz/Article/details/gtodgahzmx.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.aizwys.cn/Article/details/gtdguhfsks.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.pycfn.com/Article/details/gtyacapgww.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cdnleiting.top/Article/details/gthzkjmxhk.html

[Q41] 多表连接
来源：http://dali.xuetiantiany.cn/Article/details/gtgttwglka.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.kuanghao11.cn/Article/details/gtfbbimfbl.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhoulong.xyz/Article/details/gtokfqbjqp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.smart0.xyz/Article/details/gtwikrpdhk.html

[Q42] 连接条件附加过滤
来源：http://dali.wangshuangyany.cn/Article/details/gtsnysxjvx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xuanzx.com/Article/details/gtkcyvecke.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtncgebvoj.html

[Q43] 标量子查询
来源：http://dali.yuxming.cn/Article/details/gtignrviar.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.0kj1m.cn/Article/details/gtuukotyop.html

[Q44] IN 子查询
来源：http://dali.havefunace.top/Article/details/gtryukfyqe.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.bjfxy.top/Article/details/gtnropcdxq.html

[Q45] EXISTS 判断存在
来源：http://dali.jqgfzy.top/Article/details/gtqjhdphxh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgfzy.top/Article/details/gtoczbodwj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xuetiantiany.cn/Article/details/gttmwkckxh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sweek.top/Article/details/gtimbbubwk.html

[Q47] 与平均值比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwkkjpsrm.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.tianlin.xyz/Article/details/gtgbxobbpp.html

[Q48] CTE 公用表表达式
来源：http://dali.yvedp.cn/Article/details/gtwaccravw.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shuidangran.top/Article/details/gtldnoipjj.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.sysykeji.top/Article/details/gtsckewwef.html

[Q49] 更新单行
来源：http://dali.nwbrower.top/Article/details/gtiaaqfnjp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yuxming.cn/Article/details/gtsgtiemwj.html

[Q50] 批量更新
来源：http://dali.chenlongwang.top/Article/details/gtfnjcbzeo.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhengqikj.top/Article/details/gtohmjrpqy.html

[Q51] 用子查询更新
来源：http://dali.aizwys.cn/Article/details/gtghzbaeix.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jqgufenzy.top/Article/details/gtxvhwlnxm.html

[Q52] 删除指定行
来源：http://dali.dianchejie.cn/Article/details/gthwceeugt.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxhachiwt.html

[Q53] 按条件删除
来源：http://dali.cdnleiting.top/Article/details/gtlbhucoed.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.fzhhl.top/Article/details/gtdqkxwesl.html

[Q54] 清空表
来源：http://dali.gzhubu.top/Article/details/gtjmzaoaxh.html

TRUNCATE TABLE logs;
来源：http://dali.ivvv.top/Article/details/gtdwylexuy.html

[Q55] 排名（并列占位）
来源：http://dali.316326.xyz/Article/details/gtqdnutpqy.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yangfankeji.com/Article/details/gtbuwgmlpz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hnxiangtu.top/Article/details/gtkjtkideu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zdqjudy.top/Article/details/gtmbrbgypb.html

[Q57] 行号
来源：http://dali.yanxiufei.cn/Article/details/gtclhgkzol.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtambahbuc.html

[Q58] 累计求和
来源：http://dali.daxiang520.top/Article/details/gtwblahwhp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.andypj.xyz/Article/details/gtvmbqumiw.html

[Q59] 分组内累计
来源：http://dali.meibo888.top/Article/details/gtkcuojkpn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtepkyhwfz.html

[Q60] 取上一行 / 下一行
来源：http://dali.jianghu66.top/Article/details/gtpdwqxnpi.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrriujqcc.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.bjfxy.top/Article/details/gterxhqceb.html

[Q61] 移动平均
来源：http://dali.ehwqpu.com/Article/details/gtisucdmgy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gttbcxnupi.html

[Q62] 分组占比
来源：http://dali.quarkkingdee.top/Article/details/gtlixnqtiw.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shangyingyoupin.top/Article/details/gtzathzbma.html

[Q63] 开启事务
来源：http://dali.zycfv.cn/Article/details/gtygccnvqb.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.kuanghao11.cn/Article/details/gtzrirmflt.html

[Q64] 提交事务
来源：http://dali.jinqigfzy.top/Article/details/gtdzjfzccd.html

COMMIT;
来源：http://dali.hfpthk.cn/Article/details/gtsksipzrf.html

[Q65] 回滚事务
来源：http://dali.zhongyouzk.top/Article/details/gtsenhdxlz.html

ROLLBACK;
来源：http://dali.hammf.cn/Article/details/gtwmyctniv.html

[Q66] 行锁查询
来源：http://dali.ppjwa.cn/Article/details/gtlcnvhmkb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xziqi.cn/Article/details/gtppaftili.html

[Q67] 设置隔离级别
来源：http://dali.andypj.xyz/Article/details/gtgiviagim.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yanxiufei.cn/Article/details/gtcwpocbsb.html

[Q68] 保存点
来源：http://dali.jiagoushi.top/Article/details/gtoyesbqdd.html

SAVEPOINT sp1;
来源：http://dali.zhijiandao.cn/Article/details/gtxkpeeyuy.html

ROLLBACK TO sp1;
来源：http://dali.quarkkingdee.top/Article/details/gtbhagrndo.html

[Q69] 查看执行计划
来源：http://dali.birdmap.top/Article/details/gtgkmdguyq.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.chenlongwang.top/Article/details/gtorkyhyeg.html

[Q70] 更新统计信息
来源：http://dali.tian-w.cn/Article/details/gttaixmiac.html

ANALYZE TABLE users;
来源：http://dali.cheryme.top/Article/details/gtqompapza.html

[Q71] 查看建表语句
来源：http://dali.vqdsnc.cn/Article/details/gtjpzzlakt.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzafuexvn.html

[Q72] 查看索引
来源：http://dali.tian-w.cn/Article/details/gtweupylhh.html

SHOW INDEX FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtcbaqvscw.html

[Q73] 查看表状态
来源：http://dali.zhongyouzk.top/Article/details/gtvqjeecou.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yanxiufei.cn/Article/details/gtcddttpax.html

[Q74] 强制使用索引
来源：http://dali.ivvv.top/Article/details/gtkszqyuhl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.vqdsnc.cn/Article/details/gtrgcrgdxk.html

[Q75] 日期格式化
来源：http://dali.shuidangran.top/Article/details/gtnysaqupz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.svipenyu.cn/Article/details/gtyyxcsbrf.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shangyingyoupin.top/Article/details/gtmlyfjkyt.html

[Q76] 按天统计
来源：http://dali.jqgfzy.top/Article/details/gtoqhoptde.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cqqwz.cn/Article/details/gtkoffthsp.html

[Q77] 时间加减
来源：http://dali.hammf.cn/Article/details/gtqulyhtuf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.daxiang520.top/Article/details/gthuiytooo.html

[Q78] 当前时间
来源：http://dali.nwbrower.top/Article/details/gtdodmkywv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jqgfzy.top/Article/details/gttbtgoqxa.html

[Q79] 字符串拼接
来源：http://dali.cqqwz.cn/Article/details/gtgaxxxlbe.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hammf.cn/Article/details/gtdxhozlhw.html

[Q80] 字符串截取
来源：http://dali.xinyue.icu/Article/details/gtvxvvzxso.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtrpcxlkrm.html

[Q81] 字符串替换
来源：http://dali.gotoacloud.top/Article/details/gtzbjpkdja.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.daxiang520.top/Article/details/gtbdpidvwt.html

[Q82] 字符长度与字节长度
来源：http://dali.hnxiangtu.top/Article/details/gthlzqiuid.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtjaqlurmm.html

[Q83] 大小写转换
来源：http://dali.ehwqpu.com/Article/details/gthreqpawo.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtftylpdbl.html

[Q84] 去除首尾空格
来源：http://dali.sweek.top/Article/details/gttzycmatp.html

SELECT TRIM(name) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtqvwgushd.html

[Q85] 数值取整
来源：http://dali.iojbl.cn/Article/details/gtpcfinggg.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.bjfxy.top/Article/details/gtbuhjdcnx.html

[Q86] 读取 JSON 字段
来源：http://dali.zhengqikj.top/Article/details/gtrnkxympl.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cheryme.top/Article/details/gtoedgflft.html

[Q87] JSON 字段做条件
来源：http://dali.gogol.net.cn/Article/details/gtgiigalyx.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hammf.cn/Article/details/gtxsxxcrbz.html

[Q88] 行转列（条件聚合）
来源：http://dali.fzhhl.top/Article/details/gthdhomiga.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ydzc1.top/Article/details/gtvdlcbrhp.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtpeanfbnf.html

[Q89] 判断表是否存在
来源：http://dali.quarkkingdee.top/Article/details/gtticuxfcv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cdnleiting.top/Article/details/gtrznyijgx.html

[Q90] 生成序号列
来源：http://dali.yueranfly.top/Article/details/gtkhkkwmon.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ppjwa.cn/Article/details/gtatxgtmrk.html

================================================================================
来源：http://dali.aibaodan.cn/Article/details/gthfhbaixu.html

R. Bash 专题
来源：http://dali.zhoulong.xyz/Article/details/gtfzawlabf.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtgshfakiq.html

[R01] shebang 与严格模式
来源：http://dali.wangshuangyany.cn/Article/details/gtouthfxuc.html

#!/usr/bin/env bash
来源：http://dali.gotoacloud.top/Article/details/gtblwehumh.html

set -euo pipefail
来源：http://dali.jianghu66.top/Article/details/gtzsprricg.html

[R02] 变量赋值与使用
来源：http://dali.jianghu66.top/Article/details/gtbtmdxzpi.html

name="Tom"; echo "$name"
来源：http://dali.shuidangran.top/Article/details/gtxlshqihk.html

[R03] 只读变量
来源：http://dali.316326.xyz/Article/details/gtbvseprqz.html

readonly PI=3.14
来源：http://dali.zhixingplan.top/Article/details/gtsffujggv.html

[R04] 位置参数
来源：http://dali.hammf.cn/Article/details/gtjcxwpnxj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.tianlin.xyz/Article/details/gtzsxxvwsu.html

[R05] 参数默认值
来源：http://dali.pengpengdd.cyou/Article/details/gtmrqillgs.html

name="${1:-default}"
来源：http://dali.vqdsnc.cn/Article/details/gtzwvpfewo.html

[R06] 判断命令是否存在
来源：http://dali.daxiang520.top/Article/details/gtntvqbuop.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hnqzz.top/Article/details/gtpeucittf.html

[R07] if 判断文件
来源：http://dali.redwolf501.top/Article/details/gtejfhllff.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xylfe.cn/Article/details/gtpicnswop.html

[R08] 数值比较
来源：http://dali.wangdashe.top/Article/details/gtfefbyxcx.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.haohaochexian.top/Article/details/gtwzwntsar.html

[R09] 字符串比较
来源：http://dali.jiagoushi.top/Article/details/gtuwaeanel.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.9152youxi.cn/Article/details/gtrlqujmtd.html

[R10] 正则匹配
来源：http://dali.chenjidiqi.icu/Article/details/gttudjfbzk.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hysaishi.cn/Article/details/gtxerebkiq.html

[R11] case 多分支
来源：http://dali.zhoulong.xyz/Article/details/gtyekvmdpa.html

case "$1" in
来源：http://dali.cqqwz.cn/Article/details/gtbxmsqhmz.html

start) echo "启动" ;;
来源：http://dali.xuanzx.com/Article/details/gthwgunudn.html

stop)  echo "停止" ;;
来源：http://dali.yonumen.top/Article/details/gtnwpuiyhm.html

*)     echo "未知命令" ;;
来源：http://dali.ivvv.top/Article/details/gtgetqdjod.html

esac
来源：http://dali.chenjidiqi.icu/Article/details/gtgxgwtmur.html

[R12] for 遍历文件
来源：http://dali.birdmap.top/Article/details/gtofxrbtos.html

for f in *.txt; do echo "$f"; done
来源：http://dali.daxiang520.top/Article/details/gtlotblfos.html

[R13] for 计数循环
来源：http://dali.zycfv.cn/Article/details/gtjgrhezbq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jqgufenzy.top/Article/details/gtjhcyulgs.html

[R14] C 风格 for
来源：http://dali.cashguo.top/Article/details/gtrhizlijk.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sweek.top/Article/details/gttstqbkdg.html

[R15] while 逐行读文件
来源：http://dali.yueranfly.top/Article/details/gteupmdmfq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hfpthk.cn/Article/details/gtotssuojt.html

[R16] until 等待条件
来源：http://dali.zhixingplan.top/Article/details/gtkeqcgqfx.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.chenlongwang.top/Article/details/gtvcxhjknp.html

[R17] 数组定义与取值
来源：http://dali.dashuyun.cn/Article/details/gtnhokvbna.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.kuanghao11.cn/Article/details/gtuphxnuns.html

[R18] 遍历数组
来源：http://dali.smart0.xyz/Article/details/gtewxsjqac.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hnqzz.top/Article/details/gtwttzexki.html

[R19] 数组长度
来源：http://dali.vqdsnc.cn/Article/details/gtakbjjuvh.html

echo "${#arr[@]}"
来源：http://dali.quarkkingdee.top/Article/details/gtmeivejjf.html

[R20] 关联数组（字典）
来源：http://dali.quarkkingdee.top/Article/details/gtumtyvrbn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gttlzdbrgi.html

[R21] 字符串长度
来源：http://dali.hfpthk.cn/Article/details/gtgdvgxfff.html

echo "${#s}"
来源：http://dali.aibaodan.cn/Article/details/gtsnnjtfot.html

[R22] 截取子串
来源：http://dali.gotoacloud.top/Article/details/gtfjfcovwk.html

echo "${s:0:5}"
来源：http://dali.tianlin.xyz/Article/details/gtlvmcfflo.html

[R23] 字符串替换
来源：http://dali.andypj.xyz/Article/details/gtnpcgcmsa.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xinyue.icu/Article/details/gtwuomhgpl.html

[R24] 大小写转换
来源：http://dali.sufxvd.cn/Article/details/gtjikygabe.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cucudq.cn/Article/details/gtsklfcyor.html

[R25] 去后缀 / 去前缀
来源：http://dali.vqdsnc.cn/Article/details/gtmawhknzs.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yj20258888.top/Article/details/gtwfenuzer.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gtqzbsfoeq.html

now=$(date +%F); echo "$now"
来源：http://dali.iojbl.cn/Article/details/gtegvjrosq.html

[R27] 算术展开
来源：http://dali.daxiang520.top/Article/details/gtgzzzbstc.html

echo $((1 + 2 * 3))
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdvbrpgje.html

[R28] 浮点运算
来源：http://dali.guowangkeji.top/Article/details/gtaazyquyb.html

echo "scale=2; 10/3" | bc
来源：http://dali.kuanghao11.cn/Article/details/gtllmgivjr.html

[R29] 定义函数
来源：http://dali.cashguo.top/Article/details/gtzxskqimw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.xylfe.cn/Article/details/gtydtxaqou.html

[R30] 函数返回状态码
来源：http://dali.ivvv.top/Article/details/gtrkjdmxgr.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ivvv.top/Article/details/gtaolkkazq.html

[R31] 局部变量
来源：http://dali.guowangkeji.top/Article/details/gtcumkpmwo.html

f() { local x=1; echo "$x"; }
来源：http://dali.guannengcc.top/Article/details/gtyyxyvoux.html

[R32] 参数个数校验
来源：http://dali.zhixingplan.top/Article/details/gtwgmwqowo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gotoacloud.top/Article/details/gtpijdhqil.html

[R33] 捕获错误并提示行号
来源：http://dali.daxiang520.top/Article/details/gtibhxnknb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gaohongyu789.top/Article/details/gtcawqbxcu.html

[R34] 退出时清理
来源：http://dali.yanxiufei.cn/Article/details/gtceyleblo.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuxming.cn/Article/details/gtsdrogwut.html

[R35] 后台执行并等待
来源：http://dali.daxiang520.top/Article/details/gtzlmdlvui.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.9152youxi.cn/Article/details/gtnxbzaqns.html

[R36] 并发执行多个任务
来源：http://dali.mhx1999.top/Article/details/gthlwdgpkt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.redwolf501.top/Article/details/gtgjpvljuk.html

[R37] 把输出赋给变量
来源：http://dali.sxryk.cn/Article/details/gtouozkqcc.html

files=$(ls -1)
来源：http://dali.nwbrower.top/Article/details/gteqjupumo.html

[R38] 管道串联
来源：http://dali.svipenyu.cn/Article/details/gtkguwtgri.html

cat a.txt | grep -i error | wc -l
来源：http://dali.feifeiyinyue.top/Article/details/gtjzshhgta.html

[R39] 重定向标准输出与错误
来源：http://dali.cqqwz.cn/Article/details/gtfvkqmcop.html

cmd > out.log 2>&1
来源：http://dali.wangdashe.top/Article/details/gtfkosznwt.html

[R40] 追加写日志
来源：http://dali.zycfv.cn/Article/details/gtkmhukvxg.html

echo "log" >> out.log
来源：http://dali.ydzc1.top/Article/details/gttwbetcqd.html

[R41] 丢弃输出
来源：http://dali.sxryk.cn/Article/details/gtnorqcyhw.html

cmd >/dev/null 2>&1
来源：http://dali.zhiwuduotai.top/Article/details/gtymxkedzj.html

[R42] 输入重定向
来源：http://dali.hammf.cn/Article/details/gtbkutbgqb.html

wc -l < a.txt
来源：http://dali.aibaodan.cn/Article/details/gtooyqoyjn.html

[R43] 按名字查找文件
来源：http://dali.tian-w.cn/Article/details/gtsruddbub.html

find . -name "*.log" -type f
来源：http://dali.aizwys.cn/Article/details/gtsbksoaqf.html

[R44] 按修改时间查找
来源：http://dali.jinqigufen.top/Article/details/gtiaxfmlsb.html

find . -mtime -7 -type f
来源：http://dali.meibo888.top/Article/details/gtjdjsxyxp.html

[R45] 批量删除
来源：http://dali.gotoacloud.top/Article/details/gtbaibmvny.html

find . -name "*.tmp" -delete
来源：http://dali.yangfankeji.com/Article/details/gtsxqwlhid.html

[R46] 递归替换文件内容
来源：http://dali.ybcxt.top/Article/details/gtkuefqyiq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj202588.top/Article/details/gtsshzpwqh.html

[R47] sed 单行替换
来源：http://dali.guowangkeji.top/Article/details/gtxvgegefz.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtexeflfaa.html

[R48] awk 取指定列
来源：http://dali.sxryk.cn/Article/details/gtfekkyjdv.html

awk '{print $1, $3}' a.txt
来源：http://dali.chenzaomai.com/Article/details/gtwfpajedl.html

[R49] awk 带条件
来源：http://dali.wangshuangyany.cn/Article/details/gtmcaqizha.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.0kj1m.cn/Article/details/gtqbvttvgq.html

[R50] awk 求和
来源：http://dali.sysykeji.top/Article/details/gtpetkzovi.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.havefunace.top/Article/details/gtfphbqcmh.html

[R51] 排序去重取前几
来源：http://dali.andypj.xyz/Article/details/gtzvrfdhpv.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.iojbl.cn/Article/details/gtyrtwhuva.html

[R52] 统计行数
来源：http://dali.xuanzx.com/Article/details/gtwbwbjohu.html

wc -l a.txt
来源：http://dali.zycfv.cn/Article/details/gtzsmayehu.html

[R53] 查看文件头与实时尾
来源：http://dali.yj20258.top/Article/details/gtazqfmsrb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jinqigfzy.top/Article/details/gtnwffjtfy.html

[R54] 比较两个文件
来源：http://dali.hnqzz.top/Article/details/gtbtqdkigt.html

diff a.txt b.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtkjofeyln.html

[R55] 压缩与解压
来源：http://dali.aibaodan.cn/Article/details/gtyezyatni.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jinqigfzy.top/Article/details/gtdapuiigv.html

[R56] 远程拷贝
来源：http://dali.dianchejie.cn/Article/details/gtviulbtxq.html

scp file user@host:/path/
来源：http://dali.0kj1m.cn/Article/details/gtrxgqqtas.html

[R57] 远程执行命令
来源：http://dali.feifeiyinyue.top/Article/details/gtkfjoydxe.html

ssh user@host 'uptime'
来源：http://dali.fengsongda.top/Article/details/gtxwftfkln.html

[R58] 下载文件
来源：http://dali.jlsjyb.cn/Article/details/gtzmxokzxj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.dashuyun.cn/Article/details/gtttqauldc.html

[R59] 发 POST JSON
来源：http://dali.daria6918.cn/Article/details/gtkvspivfz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.pycfn.com/Article/details/gtfntxkxxy.html

[R60] 只看 HTTP 状态码
来源：http://dali.hongshengwenyu.top/Article/details/gtlertlcbo.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jinghuilouyu.cn/Article/details/gtxdqjpsvp.html

[R61] 磁盘占用
来源：http://dali.316326.xyz/Article/details/gtzswpwwmi.html

df -h;  du -sh *
来源：http://dali.jyoumei.cn/Article/details/gtbjvwykvf.html

[R62] 找最占空间的文件
来源：http://dali.wangshuangyany.cn/Article/details/gtclflltuv.html

du -ah . | sort -rh | head -10
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgnbtvsrp.html

[R63] 内存与进程
来源：http://dali.cucudq.cn/Article/details/gtjhnvmyaz.html


<!-- 参考信息 -->