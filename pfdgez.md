代发 wailian999

[Q14] 存在则更新（upsert）
来源：http://dali.shzxlz.cn/Article/details/gtgpiskcxb.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.shuidangran.top/Article/details/gtcuhlhxkg.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.redwolf501.top/Article/details/gthvhlfzfv.html

[Q15] 查询全部
来源：http://dali.daria6918.cn/Article/details/gtbyvwzsaa.html

SELECT * FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gteqsjdvhu.html

[Q16] 查询指定列
来源：http://dali.gotoacloud.top/Article/details/gtkolyynag.html

SELECT id, name FROM users;
来源：http://dali.yj20258888.top/Article/details/gtflfbkbmt.html

[Q17] 条件查询
来源：http://dali.quarkkingdee.top/Article/details/gteencrfuj.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.cqqwz.cn/Article/details/gtojhllqtz.html

[Q18] 模糊匹配
来源：http://dali.haohaochexian.top/Article/details/gtpjgrmrze.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jianghu66.top/Article/details/gtgrdmnmxt.html

[Q19] 范围查询
来源：http://dali.yj20258.top/Article/details/gtaypaaioo.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.hongshengwenyu.top/Article/details/gtvfnermuz.html

[Q20] IN 列表
来源：http://dali.gogol.net.cn/Article/details/gtaivjwqzz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.zhoulong.xyz/Article/details/gtsrktpmpn.html

[Q21] 空值判断
来源：http://dali.jinqigufen.top/Article/details/gtyziznysj.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.gogol.net.cn/Article/details/gtwjcpqsrh.html

[Q22] 排序
来源：http://dali.hysaishi.cn/Article/details/gtwxatgzub.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jianghu66.top/Article/details/gtgkexxgut.html

[Q23] 分页
来源：http://dali.ivvv.top/Article/details/gtrqdtblke.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.kuanghao11.cn/Article/details/gtybjdvaih.html

[Q24] 去重
来源：http://dali.mhx1999.top/Article/details/gtchnawvre.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtewzpfdmd.html

[Q25] 只取前 N 条
来源：http://dali.c1oappe.top/Article/details/gtsbijvkmk.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.hysaishi.cn/Article/details/gtmvarietg.html

[Q26] 计数
来源：http://dali.gogol.net.cn/Article/details/gtulxrtjuh.html

SELECT COUNT(*) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtnrjitgxx.html

[Q27] 条件计数
来源：http://dali.chenlongwang.top/Article/details/gttwqbkqih.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtzftqilco.html

[Q28] 求和与平均
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfmrvahrh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.316326.xyz/Article/details/gtfpljoppk.html

[Q29] 最大最小值
来源：http://dali.hnxiangtu.top/Article/details/gtmugdelee.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtvxwdpxuy.html

[Q30] 分组统计
来源：http://dali.tanke756.top/Article/details/gtbnogrvlx.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yuxming.cn/Article/details/gtldxoqnmk.html

[Q31] 分组后过滤
来源：http://dali.wangshuangyany.cn/Article/details/gtcvpfcdcs.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.ybcxt.top/Article/details/gtouraqcyy.html

[Q32] 分组拼接字符串
来源：http://dali.ppjwa.cn/Article/details/gtophcdvka.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.havefunace.top/Article/details/gtagiqkfmw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhengqikj.top/Article/details/gtzttedvvb.html

[Q33] 多列分组
来源：http://dali.ivvv.top/Article/details/gtatfwsmjm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.0kj1m.cn/Article/details/gtypbiiqje.html

[Q34] 每组取第一条
来源：http://dali.quarkkingdee.top/Article/details/gteihmdtvo.html

SELECT * FROM (
来源：http://dali.daxiang520.top/Article/details/gthceczwcg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jiagoushi.top/Article/details/gtgalxdbyg.html

) t WHERE rn = 1;
来源：http://dali.guowangkeji.top/Article/details/gtvnnvgueg.html

[Q35] 内连接
来源：http://dali.bjfxy.top/Article/details/gttfamujwk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hnxiangtu.top/Article/details/gtrnyhxpgi.html

[Q36] 左连接
来源：http://dali.snrcjt.cn/Article/details/gtykpkdjys.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.aizwys.cn/Article/details/gttdedqmot.html

[Q37] 右连接
来源：http://dali.ivvv.top/Article/details/gtzkzfzvgx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.cqqwz.cn/Article/details/gtmtzgavrh.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.cucudq.cn/Article/details/gtafuqbxib.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hammf.cn/Article/details/gtuaudoqqx.html

[Q39] 自连接（查上下级）
来源：http://dali.nwbrower.top/Article/details/gtqxthhgli.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jiagoushi.top/Article/details/gtfvrhnkvp.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.nanxuanxn.top/Article/details/gtqozldqwp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hnxiangtu.top/Article/details/gtlukehgvh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.snrcjt.cn/Article/details/gtujuotukv.html

[Q41] 多表连接
来源：http://dali.yongpay.top/Article/details/gtkwaqwmxc.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yongpay.top/Article/details/gthhunxkbx.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ybcxt.top/Article/details/gtqtkxjcvz.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.316326.xyz/Article/details/gtwapsunfz.html

[Q42] 连接条件附加过滤
来源：http://dali.sysykeji.top/Article/details/gtznqatkae.html

SELECT u.name, o.amount FROM users u
来源：http://dali.shzxlz.cn/Article/details/gtdxtvhffi.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.haohaochexian.top/Article/details/gtzuwsilgs.html

[Q43] 标量子查询
来源：http://dali.xuetiantiany.cn/Article/details/gtvohiuuny.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.wangshuangyany.cn/Article/details/gtfboysqqb.html

[Q44] IN 子查询
来源：http://dali.aibaodan.cn/Article/details/gtplsfrowo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.vqdsnc.cn/Article/details/gthskjzrpe.html

[Q45] EXISTS 判断存在
来源：http://dali.zdqjudy.top/Article/details/gtbkjvwhdv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jyoumei.cn/Article/details/gtzqyxcwts.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.daria6918.cn/Article/details/gtdpdcjzgs.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shzxlz.cn/Article/details/gtfifxqagd.html

[Q47] 与平均值比较
来源：http://dali.shzxlz.cn/Article/details/gtkyufwxco.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.snrcjt.cn/Article/details/gtyzkjisxs.html

[Q48] CTE 公用表表达式
来源：http://dali.feifeiyinyue.top/Article/details/gtefxlvbmu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.pengpengdd.cyou/Article/details/gttrqpcggv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xuetiantiany.cn/Article/details/gtxcoxlpyl.html

[Q49] 更新单行
来源：http://dali.xinyue.icu/Article/details/gtkbwgwfzl.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.tanke756.top/Article/details/gtmegyszek.html

[Q50] 批量更新
来源：http://dali.shzxlz.cn/Article/details/gtzerzjjpw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinqigfzy.top/Article/details/gtftqcdrht.html

[Q51] 用子查询更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtshvatdpc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xuanzx.com/Article/details/gttwsulrwr.html

[Q52] 删除指定行
来源：http://dali.svipenyu.cn/Article/details/gtullfoinc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.zhengqikj.top/Article/details/gtuwcgthgo.html

[Q53] 按条件删除
来源：http://dali.hnxiangtu.top/Article/details/gtkoivbfbz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.daxiang520.top/Article/details/gtuzzmqzhi.html

[Q54] 清空表
来源：http://dali.cqqwz.cn/Article/details/gtkkvcbftt.html

TRUNCATE TABLE logs;
来源：http://dali.yuxming.cn/Article/details/gtrlxclbpe.html

[Q55] 排名（并列占位）
来源：http://dali.gaohongyu789.top/Article/details/gtlxinlqgm.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.daxiang520.top/Article/details/gtdiqrqdlz.html

[Q56] 密集排名（并列不占位）
来源：http://dali.hywenlv.cn/Article/details/gtxrhyfywd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.redwolf501.top/Article/details/gtlmppqklf.html

[Q57] 行号
来源：http://dali.cheryme.top/Article/details/gttctidacp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtzdgjystt.html

[Q58] 累计求和
来源：http://dali.zhixingplan.top/Article/details/gttcrpucle.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yj202588.top/Article/details/gtsnkvqevh.html

[Q59] 分组内累计
来源：http://dali.smart0.xyz/Article/details/gtjyglawbo.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.fzhhl.top/Article/details/gtvurrcpku.html

[Q60] 取上一行 / 下一行
来源：http://dali.fengsongda.top/Article/details/gtpynfiqzb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gzhubu.top/Article/details/gtfvsfhcbh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtomuasjyz.html

[Q61] 移动平均
来源：http://dali.pycfn.com/Article/details/gtbpbvmumg.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.fengsongda.top/Article/details/gtkglfdhqh.html

[Q62] 分组占比
来源：http://dali.iojbl.cn/Article/details/gteihlimzt.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtcphrkhug.html

[Q63] 开启事务
来源：http://dali.kuanghao11.cn/Article/details/gtckvkaogn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinghuilouyu.cn/Article/details/gtdrafewtq.html

[Q64] 提交事务
来源：http://dali.tanke756.top/Article/details/gtqcberblp.html

COMMIT;
来源：http://dali.yvedp.cn/Article/details/gtoqqzjwdb.html

[Q65] 回滚事务
来源：http://dali.yj20258888.top/Article/details/gtesmzgcps.html

ROLLBACK;
来源：http://dali.nwbrower.top/Article/details/gtxuswjkth.html

[Q66] 行锁查询
来源：http://dali.daria6918.cn/Article/details/gtzagwovac.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jinghuilouyu.cn/Article/details/gtxxjjuaet.html

[Q67] 设置隔离级别
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgyrslxek.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhiwuduotai.top/Article/details/gtgudlcuoz.html

[Q68] 保存点
来源：http://dali.pycfn.com/Article/details/gtmwiidcwz.html

SAVEPOINT sp1;
来源：http://dali.xuetiantiany.cn/Article/details/gtiibyjkbm.html

ROLLBACK TO sp1;
来源：http://dali.guannengcc.top/Article/details/gtkohfbnhx.html

[Q69] 查看执行计划
来源：http://dali.jinqigfzy.top/Article/details/gtpjpkizig.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.chenzaomai.com/Article/details/gtyuvrlulr.html

[Q70] 更新统计信息
来源：http://dali.gotoacloud.top/Article/details/gtdycihxuc.html

ANALYZE TABLE users;
来源：http://dali.yuxming.cn/Article/details/gtfwgrmzmv.html

[Q71] 查看建表语句
来源：http://dali.cashguo.top/Article/details/gthkbvqujl.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.sweek.top/Article/details/gtnexjjihv.html

[Q72] 查看索引
来源：http://dali.yj202588.top/Article/details/gtopoxvtui.html

SHOW INDEX FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtsxvbbnvq.html

[Q73] 查看表状态
来源：http://dali.nanxinkj.top/Article/details/gtdizbnxwc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hnxiangtu.top/Article/details/gtarlvlvtl.html

[Q74] 强制使用索引
来源：http://dali.shzxlz.cn/Article/details/gtoatewugm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yj202588.top/Article/details/gtrcaeogmv.html

[Q75] 日期格式化
来源：http://dali.yueranfly.top/Article/details/gtyrljjkex.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtxrigfpaa.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shanyushiyangtech.top/Article/details/gtapjrbuti.html

[Q76] 按天统计
来源：http://dali.jinqigufen.top/Article/details/gtohwemxhy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cqqwz.cn/Article/details/gtrfnwensy.html

[Q77] 时间加减
来源：http://dali.yuxming.cn/Article/details/gtxtuylxaf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yueranfly.top/Article/details/gtikrwtdfd.html

[Q78] 当前时间
来源：http://dali.andypj.xyz/Article/details/gtbxysemtx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.aibaodan.cn/Article/details/gtpvmjcbly.html

[Q79] 字符串拼接
来源：http://dali.zhongyouzk.top/Article/details/gtyqxwqpsv.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hammf.cn/Article/details/gtaudupfnv.html

[Q80] 字符串截取
来源：http://dali.yj20258888.top/Article/details/gtbhsbcboa.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.meibo888.top/Article/details/gtsfjhralp.html

[Q81] 字符串替换
来源：http://dali.jinqigufen.top/Article/details/gtitvrjjvy.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.sysykeji.top/Article/details/gtfigvvskz.html

[Q82] 字符长度与字节长度
来源：http://dali.havefunace.top/Article/details/gteusxtzyx.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.meibo888.top/Article/details/gtgyujlild.html

[Q83] 大小写转换
来源：http://dali.zdqjudy.top/Article/details/gtaujovncf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtqqsgjfka.html

[Q84] 去除首尾空格
来源：http://dali.ppjwa.cn/Article/details/gtapfabzgq.html

SELECT TRIM(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gttakmbiqj.html

[Q85] 数值取整
来源：http://dali.ydzc1.top/Article/details/gtjwuyywoi.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.0kj1m.cn/Article/details/gtpdhbqkzg.html

[Q86] 读取 JSON 字段
来源：http://dali.hnqzz.top/Article/details/gtogxtmkli.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jyoumei.cn/Article/details/gtibwfxqms.html

[Q87] JSON 字段做条件
来源：http://dali.wangshuangyany.cn/Article/details/gtplpvthlq.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hammf.cn/Article/details/gtkhrmuepx.html

[Q88] 行转列（条件聚合）
来源：http://dali.daxiang520.top/Article/details/gtwhjotsvu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ehwqpu.com/Article/details/gtorkfenvx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cucudq.cn/Article/details/gtzeisamzi.html

[Q89] 判断表是否存在
来源：http://dali.xuanzx.com/Article/details/gtajkaxsgu.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.chenzaomai.com/Article/details/gtrqzguxxu.html

[Q90] 生成序号列
来源：http://dali.zdqjudy.top/Article/details/gtylgzoogo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.feifeiyinyue.top/Article/details/gtnnyayvtn.html

================================================================================
来源：http://dali.hfpthk.cn/Article/details/gtghyckvkp.html

R. Bash 专题
来源：http://dali.daria6918.cn/Article/details/gtsbqxnewm.html

================================================================================
来源：http://dali.sufxvd.cn/Article/details/gtpytznlef.html

[R01] shebang 与严格模式
来源：http://dali.tian-w.cn/Article/details/gtlhvgffoi.html

#!/usr/bin/env bash
来源：http://dali.tanke756.top/Article/details/gtvouiabky.html

set -euo pipefail
来源：http://dali.sxryk.cn/Article/details/gtymcjjskr.html

[R02] 变量赋值与使用
来源：http://dali.dianchejie.cn/Article/details/gtpsgjumwk.html

name="Tom"; echo "$name"
来源：http://dali.haohaochexian.top/Article/details/gtqubiattb.html

[R03] 只读变量
来源：http://dali.sysykeji.top/Article/details/gtqhyrsawb.html

readonly PI=3.14
来源：http://dali.c1oappe.top/Article/details/gtuxnjtrvh.html

[R04] 位置参数
来源：http://dali.xylfe.cn/Article/details/gtqdcfffhq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjgmngmve.html

[R05] 参数默认值
来源：http://dali.bjfxy.top/Article/details/gtxvpkqply.html

name="${1:-default}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlkewmoso.html

[R06] 判断命令是否存在
来源：http://dali.jyoumei.cn/Article/details/gteouummoz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.fzhhl.top/Article/details/gttjeoqnnp.html

[R07] if 判断文件
来源：http://dali.pycfn.com/Article/details/gthhdjxnkq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xuanzx.com/Article/details/gtqoeleajm.html

[R08] 数值比较
来源：http://dali.cucudq.cn/Article/details/gtvhluusav.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.ehwqpu.com/Article/details/gtfgdmadwn.html

[R09] 字符串比较
来源：http://dali.gzhubu.top/Article/details/gtmqxnxomi.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yj20258888.top/Article/details/gtnwmkfsus.html

[R10] 正则匹配
来源：http://dali.mhx1999.top/Article/details/gtjhmqigem.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.guowangkeji.top/Article/details/gtfabhdxkv.html

[R11] case 多分支
来源：http://dali.pycfn.com/Article/details/gtmhsqfdhb.html

case "$1" in
来源：http://dali.xylfe.cn/Article/details/gtshutsypm.html

start) echo "启动" ;;
来源：http://dali.andypj.xyz/Article/details/gtptvjtawk.html

stop)  echo "停止" ;;
来源：http://dali.chenlongwang.top/Article/details/gtxaqxjkcu.html

*)     echo "未知命令" ;;
来源：http://dali.yongpay.top/Article/details/gtnmfpydqw.html

esac
来源：http://dali.9152youxi.cn/Article/details/gtipfgyawg.html

[R12] for 遍历文件
来源：http://dali.dashuyun.cn/Article/details/gttspnzeyp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cdnleiting.top/Article/details/gtagcaaewz.html

[R13] for 计数循环
来源：http://dali.vqdsnc.cn/Article/details/gtovkbklnp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.wangshuangyany.cn/Article/details/gtjgxkzsli.html

[R14] C 风格 for
来源：http://dali.tianlin.xyz/Article/details/gtubeewfdu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.vqdsnc.cn/Article/details/gtcecakmbs.html

[R15] while 逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gtidyglvne.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.aizwys.cn/Article/details/gtyqgdgnpw.html

[R16] until 等待条件
来源：http://dali.sweek.top/Article/details/gtygeuaqmh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jlsjyb.cn/Article/details/gtrohepqiy.html

[R17] 数组定义与取值
来源：http://dali.zhiwuduotai.top/Article/details/gtskzybjyg.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwgstswxv.html

[R18] 遍历数组
来源：http://dali.dianchejie.cn/Article/details/gtdklsosmg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.bjfxy.top/Article/details/gtwqynczom.html

[R19] 数组长度
来源：http://dali.nanxinkj.top/Article/details/gtrvbfcxri.html

echo "${#arr[@]}"
来源：http://dali.nwbrower.top/Article/details/gtzckgfpjz.html

[R20] 关联数组（字典）
来源：http://dali.shuidangran.top/Article/details/gtynamkmpf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhijiandao.cn/Article/details/gtpqqseomu.html

[R21] 字符串长度
来源：http://dali.chenlongwang.top/Article/details/gtwadjhpog.html

echo "${#s}"
来源：http://dali.cucudq.cn/Article/details/gtcurtpqjx.html

[R22] 截取子串
来源：http://dali.xinyue.icu/Article/details/gtymtogujs.html

echo "${s:0:5}"
来源：http://dali.jinqigufen.top/Article/details/gtgfvpdpik.html

[R23] 字符串替换
来源：http://dali.bjfxy.top/Article/details/gthvfzhhrv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jinqigfzy.top/Article/details/gtkencncfz.html

[R24] 大小写转换
来源：http://dali.nanxuanxn.top/Article/details/gtsxpzgeuw.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.wangshuangyany.cn/Article/details/gtvlnjhldh.html

[R25] 去后缀 / 去前缀
来源：http://dali.xuetiantiany.cn/Article/details/gtyedwykic.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hnqzz.top/Article/details/gtnjbandvw.html

[R26] 命令替换
来源：http://dali.feifeiyinyue.top/Article/details/gtsetrbnfl.html

now=$(date +%F); echo "$now"
来源：http://dali.ppjwa.cn/Article/details/gthagqmtri.html

[R27] 算术展开
来源：http://dali.zhoulong.xyz/Article/details/gtoklagcga.html

echo $((1 + 2 * 3))
来源：http://dali.kuanghao11.cn/Article/details/gtgyaiohpk.html

[R28] 浮点运算
来源：http://dali.yongpay.top/Article/details/gtwllbqnlt.html

echo "scale=2; 10/3" | bc
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfegnxdpu.html

[R29] 定义函数
来源：http://dali.ywan-chungtsiang.top/Article/details/gteizcqvfi.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.ydzc1.top/Article/details/gtushyyvje.html

[R30] 函数返回状态码
来源：http://dali.aibaodan.cn/Article/details/gtcrojolyg.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zdqjudy.top/Article/details/gtetwfzxad.html

[R31] 局部变量
来源：http://dali.yvedp.cn/Article/details/gtwahmvvnq.html

f() { local x=1; echo "$x"; }
来源：http://dali.hywenlv.cn/Article/details/gtjqaxztqt.html

[R32] 参数个数校验
来源：http://dali.chenjidiqi.icu/Article/details/gtxusemaun.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.fengsongda.top/Article/details/gtqoeuaiek.html

[R33] 捕获错误并提示行号
来源：http://dali.wangshuangyany.cn/Article/details/gtzninppkl.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.ybcxt.top/Article/details/gttjvelkls.html

[R34] 退出时清理
来源：http://dali.gotoacloud.top/Article/details/gtdombzkth.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.meibo888.top/Article/details/gtspgvdjcr.html

[R35] 后台执行并等待
来源：http://dali.ehwqpu.com/Article/details/gtdnxwqhov.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.ydzc1.top/Article/details/gtnywowsao.html

[R36] 并发执行多个任务
来源：http://dali.cucudq.cn/Article/details/gtxxbosvtx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jqgfzy.top/Article/details/gtwdmcrzzc.html

[R37] 把输出赋给变量
来源：http://dali.hongshengwenyu.top/Article/details/gtfehexcwg.html

files=$(ls -1)
来源：http://dali.yj20258.top/Article/details/gtidwpoatj.html

[R38] 管道串联
来源：http://dali.aibaodan.cn/Article/details/gtouvczwxo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.feifeiyinyue.top/Article/details/gttspnzwlt.html

[R39] 重定向标准输出与错误
来源：http://dali.hywenlv.cn/Article/details/gtdlmzyvtv.html

cmd > out.log 2>&1
来源：http://dali.shanyushiyangkeji.top/Article/details/gtotzuujcg.html

[R40] 追加写日志
来源：http://dali.meibo888.top/Article/details/gtqqouzbsi.html

echo "log" >> out.log
来源：http://dali.chenjidiqi.icu/Article/details/gtsfcxwifp.html

[R41] 丢弃输出
来源：http://dali.kuanghao11.cn/Article/details/gtzmiddtdx.html

cmd >/dev/null 2>&1
来源：http://dali.sufxvd.cn/Article/details/gthxazfcxs.html

[R42] 输入重定向
来源：http://dali.aizwys.cn/Article/details/gtxscwioca.html

wc -l < a.txt
来源：http://dali.dianchejie.cn/Article/details/gtjrtafisn.html

[R43] 按名字查找文件
来源：http://dali.kuanghao11.cn/Article/details/gtsxiyhmrs.html

find . -name "*.log" -type f
来源：http://dali.cqqwz.cn/Article/details/gtuzopwbdy.html

[R44] 按修改时间查找
来源：http://dali.316326.xyz/Article/details/gttvphsdzc.html

find . -mtime -7 -type f
来源：http://dali.nanxuanxn.top/Article/details/gtmtwnnwfm.html

[R45] 批量删除
来源：http://dali.xylfe.cn/Article/details/gtxceidatm.html

find . -name "*.tmp" -delete
来源：http://dali.havefunace.top/Article/details/gtlrpkbpwp.html

[R46] 递归替换文件内容
来源：http://dali.ydzc1.top/Article/details/gtzxmfstjn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jlsjyb.cn/Article/details/gtqqamdeeb.html

[R47] sed 单行替换
来源：http://dali.quarkkingdee.top/Article/details/gtkodxqcys.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yj20258.top/Article/details/gtrjjtkflc.html

[R48] awk 取指定列
来源：http://dali.dianchejie.cn/Article/details/gtocvbellw.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhijiandao.cn/Article/details/gtamnecrgf.html

[R49] awk 带条件
来源：http://dali.hongshengwenyu.top/Article/details/gtcdrvfxwj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.aibaodan.cn/Article/details/gtfczxbsok.html

[R50] awk 求和
来源：http://dali.cucudq.cn/Article/details/gtvklcmrek.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.snrcjt.cn/Article/details/gtzjnaircn.html

[R51] 排序去重取前几
来源：http://dali.9152youxi.cn/Article/details/gthobmvabt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hysaishi.cn/Article/details/gtvbzuxdzv.html

[R52] 统计行数
来源：http://dali.9152youxi.cn/Article/details/gttufelevr.html

wc -l a.txt
来源：http://dali.daria6918.cn/Article/details/gtohgjoyvl.html

[R53] 查看文件头与实时尾
来源：http://dali.zdqjudy.top/Article/details/gtyljbhcoh.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.redwolf501.top/Article/details/gtdnuxbuod.html

[R54] 比较两个文件
来源：http://dali.cqqwz.cn/Article/details/gtfutfthkg.html

diff a.txt b.txt
来源：http://dali.fzhhl.top/Article/details/gtwkwdbzal.html

[R55] 压缩与解压
来源：http://dali.fengsongda.top/Article/details/gthqbyjpwr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.vqdsnc.cn/Article/details/gtjalofdzy.html

[R56] 远程拷贝
来源：http://dali.tianlin.xyz/Article/details/gturrlxfqo.html

scp file user@host:/path/
来源：http://dali.hywenlv.cn/Article/details/gtcjdcjblo.html

[R57] 远程执行命令
来源：http://dali.gzhubu.top/Article/details/gtsokvvhcx.html

ssh user@host 'uptime'
来源：http://dali.jiagoushi.top/Article/details/gtrkkjkpks.html

[R58] 下载文件
来源：http://dali.hnqzz.top/Article/details/gtqaovcoqj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.aizwys.cn/Article/details/gtdtxeljap.html

[R59] 发 POST JSON
来源：http://dali.jiagoushi.top/Article/details/gtumcsieds.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yj20258.top/Article/details/gtyofkryer.html

[R60] 只看 HTTP 状态码
来源：http://dali.yanxiufei.cn/Article/details/gtlqbuzirg.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cdnleiting.top/Article/details/gtodncqyuu.html

[R61] 磁盘占用
来源：http://dali.nwbrower.top/Article/details/gtbyvkerix.html

df -h;  du -sh *
来源：http://dali.jqgfzy.top/Article/details/gtdxxhujdd.html

[R62] 找最占空间的文件
来源：http://dali.daria6918.cn/Article/details/gtqmnhlysm.html

du -ah . | sort -rh | head -10
来源：http://dali.jqgufenzy.top/Article/details/gtlqbrqzui.html

[R63] 内存与进程
来源：http://dali.chenjidiqi.icu/Article/details/gtrlfemgbh.html


<!-- 参考信息 -->