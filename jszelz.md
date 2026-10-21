代发 wailian999

[Q14] 存在则更新（upsert）
来源：http://dali.gaohongyu789.top/Article/details/gtsdtrwpby.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxeahrfjt.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xinyue.icu/Article/details/gtbwrhnpye.html

[Q15] 查询全部
来源：http://dali.havefunace.top/Article/details/gtrgfnivlt.html

SELECT * FROM users;
来源：http://dali.mhx1999.top/Article/details/gtlujpypfe.html

[Q16] 查询指定列
来源：http://dali.pycfn.com/Article/details/gtnjntagtc.html

SELECT id, name FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtaysjkufr.html

[Q17] 条件查询
来源：http://dali.guowangkeji.top/Article/details/gtehlgtyiq.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.316326.xyz/Article/details/gtzvijpgwm.html

[Q18] 模糊匹配
来源：http://dali.jiagoushi.top/Article/details/gtcxrqwcxl.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.xinyue.icu/Article/details/gttymbhqoh.html

[Q19] 范围查询
来源：http://dali.sufxvd.cn/Article/details/gtqvbtyufb.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.redwolf501.top/Article/details/gtiqvkfsyo.html

[Q20] IN 列表
来源：http://dali.zdqjudy.top/Article/details/gtexvwnqew.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shanyushiyangkeji.top/Article/details/gtllqkcyld.html

[Q21] 空值判断
来源：http://dali.kuanghao11.cn/Article/details/gtcpfcqnzw.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.hnqzz.top/Article/details/gtupwtergm.html

[Q22] 排序
来源：http://dali.snrcjt.cn/Article/details/gtxtyeesae.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.zhixingplan.top/Article/details/gtijljgnbw.html

[Q23] 分页
来源：http://dali.dianchejie.cn/Article/details/gtlkjiuwdr.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zdqjudy.top/Article/details/gtshdumwwl.html

[Q24] 去重
来源：http://dali.birdmap.top/Article/details/gtuuyzkttw.html

SELECT DISTINCT city FROM users;
来源：http://dali.xinyue.icu/Article/details/gtsdyvvyek.html

[Q25] 只取前 N 条
来源：http://dali.hnxiangtu.top/Article/details/gtvxzipuyd.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gaohongyu789.top/Article/details/gttnhyltae.html

[Q26] 计数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnqerkbpf.html

SELECT COUNT(*) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtgveibpqd.html

[Q27] 条件计数
来源：http://dali.sxryk.cn/Article/details/gtnxlsucla.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtingcfndb.html

[Q28] 求和与平均
来源：http://dali.xinyue.icu/Article/details/gtscyfrsdh.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.tanke756.top/Article/details/gtoudphdxi.html

[Q29] 最大最小值
来源：http://dali.ppjwa.cn/Article/details/gtzylbpmwh.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtvpsxpfts.html

[Q30] 分组统计
来源：http://dali.tian-w.cn/Article/details/gtricrnlct.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.ivvv.top/Article/details/gtnsenxiwu.html

[Q31] 分组后过滤
来源：http://dali.xylfe.cn/Article/details/gtdrhpbsqg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.haohaochexian.top/Article/details/gtqfkmalsg.html

[Q32] 分组拼接字符串
来源：http://dali.xinyue.icu/Article/details/gtjdixhxjv.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.sxryk.cn/Article/details/gtyrvwefty.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cqqwz.cn/Article/details/gtypgnqvrq.html

[Q33] 多列分组
来源：http://dali.sufxvd.cn/Article/details/gtwtmnklbv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.wangshuangyany.cn/Article/details/gtgqbuvvyt.html

[Q34] 每组取第一条
来源：http://dali.sxryk.cn/Article/details/gtdenllifc.html

SELECT * FROM (
来源：http://dali.sweek.top/Article/details/gtjqfdbxcn.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sufxvd.cn/Article/details/gtoqhrvobg.html

) t WHERE rn = 1;
来源：http://dali.aizwys.cn/Article/details/gtjlqoofpy.html

[Q35] 内连接
来源：http://dali.birdmap.top/Article/details/gtilrwfalk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.meibo888.top/Article/details/gtfecicvjg.html

[Q36] 左连接
来源：http://dali.kuanghao11.cn/Article/details/gtzwwrfltm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuxming.cn/Article/details/gttlgvqdqs.html

[Q37] 右连接
来源：http://dali.fengsongda.top/Article/details/gtmcnjztsh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yvedp.cn/Article/details/gtvsdnmbnc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.nanxuanxn.top/Article/details/gtgatvozhy.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.sweek.top/Article/details/gtpupbqzdg.html

[Q39] 自连接（查上下级）
来源：http://dali.yangfankeji.com/Article/details/gttiwyvkys.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.aizwys.cn/Article/details/gtukbfqyak.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jlsjyb.cn/Article/details/gtpdlatldw.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.tian-w.cn/Article/details/gtzvqjqecj.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.chenlongwang.top/Article/details/gtqcjmprav.html

[Q41] 多表连接
来源：http://dali.jqgufenzy.top/Article/details/gtwfuqwpkk.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrohnkmkm.html

JOIN users u ON u.id = o.user_id
来源：http://dali.bjfxy.top/Article/details/gthpzmlyte.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zdqjudy.top/Article/details/gtvemhyrmf.html

[Q42] 连接条件附加过滤
来源：http://dali.kuanghao11.cn/Article/details/gtmotqkgzq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yj202588.top/Article/details/gtnuyxqpbk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnrkveuou.html

[Q43] 标量子查询
来源：http://dali.svipenyu.cn/Article/details/gtrwvrsume.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.9152youxi.cn/Article/details/gtqwoqtwya.html

[Q44] IN 子查询
来源：http://dali.ybcxt.top/Article/details/gttpddohpu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdkdkapac.html

[Q45] EXISTS 判断存在
来源：http://dali.aizwys.cn/Article/details/gtaloradua.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jiagoushi.top/Article/details/gtfyunxsmb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.andypj.xyz/Article/details/gtakaregxp.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258.top/Article/details/gtbbujwoyz.html

[Q47] 与平均值比较
来源：http://dali.snrcjt.cn/Article/details/gtdnhkjdvx.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gzhubu.top/Article/details/gtkakhijtg.html

[Q48] CTE 公用表表达式
来源：http://dali.yangfankeji.com/Article/details/gtyvbhqjnf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yanxiufei.cn/Article/details/gtxtfzyqvp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shanyushiyangtech.top/Article/details/gtyzsauhtz.html

[Q49] 更新单行
来源：http://dali.zycfv.cn/Article/details/gtdjmqyrad.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinqigfzy.top/Article/details/gteytapzhx.html

[Q50] 批量更新
来源：http://dali.xylfe.cn/Article/details/gtbflqjuwx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cqqwz.cn/Article/details/gtykalwxzx.html

[Q51] 用子查询更新
来源：http://dali.hnxiangtu.top/Article/details/gtiijkkwnw.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.havefunace.top/Article/details/gtvdmvsksh.html

[Q52] 删除指定行
来源：http://dali.xziqi.cn/Article/details/gtjwfvabzt.html

DELETE FROM users WHERE id = 10;
来源：http://dali.vqdsnc.cn/Article/details/gtczncsyyc.html

[Q53] 按条件删除
来源：http://dali.kuanghao11.cn/Article/details/gtfghxuruj.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.quarkkingdee.top/Article/details/gttlxkmofc.html

[Q54] 清空表
来源：http://dali.quarkkingdee.top/Article/details/gtuilcqbdv.html

TRUNCATE TABLE logs;
来源：http://dali.hnqzz.top/Article/details/gtquoesyzh.html

[Q55] 排名（并列占位）
来源：http://dali.yueranfly.top/Article/details/gtyaeclhdu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jlsjyb.cn/Article/details/gtpldidttn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sweek.top/Article/details/gtobecgifo.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nanxuanxn.top/Article/details/gtvwuggzqc.html

[Q57] 行号
来源：http://dali.yonumen.top/Article/details/gtppsmixvi.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yongpay.top/Article/details/gtslzbpeqh.html

[Q58] 累计求和
来源：http://dali.shangyingyoupin.top/Article/details/gtyqzdahak.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtukabtbnp.html

[Q59] 分组内累计
来源：http://dali.cheryme.top/Article/details/gtxmlrcdzf.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.nanxinkj.top/Article/details/gtbxxujibd.html

[Q60] 取上一行 / 下一行
来源：http://dali.fzhhl.top/Article/details/gtbpmxpjxc.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.daxiang520.top/Article/details/gtsuyttzzk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtalmsagxi.html

[Q61] 移动平均
来源：http://dali.mhx1999.top/Article/details/gtzfdzzjph.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yuxming.cn/Article/details/gtkglmonjk.html

[Q62] 分组占比
来源：http://dali.sysykeji.top/Article/details/gtjwbrplok.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.xziqi.cn/Article/details/gtyazobggu.html

[Q63] 开启事务
来源：http://dali.sxryk.cn/Article/details/gtvjliletm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.havefunace.top/Article/details/gtjwifsvzk.html

[Q64] 提交事务
来源：http://dali.cdnleiting.top/Article/details/gtebnacywp.html

COMMIT;
来源：http://dali.tian-w.cn/Article/details/gtlamucyha.html

[Q65] 回滚事务
来源：http://dali.daria6918.cn/Article/details/gtxzkvwqgh.html

ROLLBACK;
来源：http://dali.jiagoushi.top/Article/details/gtqkoozodz.html

[Q66] 行锁查询
来源：http://dali.zhixingplan.top/Article/details/gtpwbprjqi.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.guowangkeji.top/Article/details/gtlyaxssfs.html

[Q67] 设置隔离级别
来源：http://dali.shuidangran.top/Article/details/gtnoysgyti.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yj202588.top/Article/details/gtyomnajio.html

[Q68] 保存点
来源：http://dali.316326.xyz/Article/details/gtahmalkxk.html

SAVEPOINT sp1;
来源：http://dali.hnxiangtu.top/Article/details/gtplcfcxhs.html

ROLLBACK TO sp1;
来源：http://dali.cashguo.top/Article/details/gtdialsmdu.html

[Q69] 查看执行计划
来源：http://dali.cheryme.top/Article/details/gtzylayeiv.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinyuanbaomall.cn/Article/details/gtumgdygio.html

[Q70] 更新统计信息
来源：http://dali.ydzc1.top/Article/details/gtjwtwkpnx.html

ANALYZE TABLE users;
来源：http://dali.aibaodan.cn/Article/details/gtfiubfqvq.html

[Q71] 查看建表语句
来源：http://dali.zdqjudy.top/Article/details/gtywpofszb.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ppjwa.cn/Article/details/gtihdljjzd.html

[Q72] 查看索引
来源：http://dali.ybcxt.top/Article/details/gtcoosdtza.html

SHOW INDEX FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtffzvjvxu.html

[Q73] 查看表状态
来源：http://dali.daxiang520.top/Article/details/gtpwwbnygt.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmgqqkcyd.html

[Q74] 强制使用索引
来源：http://dali.snrcjt.cn/Article/details/gtezbllgkv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.tanke756.top/Article/details/gttesdnmsa.html

[Q75] 日期格式化
来源：http://dali.sufxvd.cn/Article/details/gtykhjvfse.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtqepzbcec.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmibtrphn.html

[Q76] 按天统计
来源：http://dali.hfpthk.cn/Article/details/gtqaitfwqy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.nanxuanxn.top/Article/details/gtaasrqqkz.html

[Q77] 时间加减
来源：http://dali.shuidangran.top/Article/details/gtgwonzida.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sweek.top/Article/details/gtodrlvvxd.html

[Q78] 当前时间
来源：http://dali.chenlongwang.top/Article/details/gtgdripxbv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cucudq.cn/Article/details/gtivrnmehw.html

[Q79] 字符串拼接
来源：http://dali.jyoumei.cn/Article/details/gtikjrbswz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.dianchejie.cn/Article/details/gtxyykanvi.html

[Q80] 字符串截取
来源：http://dali.jyoumei.cn/Article/details/gtciykdhcl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtbjvrgojt.html

[Q81] 字符串替换
来源：http://dali.nwbrower.top/Article/details/gtuflvaaoc.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.mhx1999.top/Article/details/gtqshvlqmy.html

[Q82] 字符长度与字节长度
来源：http://dali.yj20258.top/Article/details/gttmjdajxg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtebyhzbvg.html

[Q83] 大小写转换
来源：http://dali.bjfxy.top/Article/details/gtfzvzuyfu.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cashguo.top/Article/details/gtepzuwwko.html

[Q84] 去除首尾空格
来源：http://dali.zhixingplan.top/Article/details/gtpwgdojar.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtoppzljaz.html

[Q85] 数值取整
来源：http://dali.birdmap.top/Article/details/gtbjszllqv.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.guowangkeji.top/Article/details/gtfdnlhofi.html

[Q86] 读取 JSON 字段
来源：http://dali.ppjwa.cn/Article/details/gtkkjknibd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.cdnleiting.top/Article/details/gtjmocptiy.html

[Q87] JSON 字段做条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnaflfutu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.daria6918.cn/Article/details/gtdeztjkut.html

[Q88] 行转列（条件聚合）
来源：http://dali.pengpengdd.cyou/Article/details/gtjchnnboj.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.guannengcc.top/Article/details/gtmmpcbaeo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shzxlz.cn/Article/details/gthwzjctzg.html

[Q89] 判断表是否存在
来源：http://dali.cheryme.top/Article/details/gtpoxodjta.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.daxiang520.top/Article/details/gttmkwjxyn.html

[Q90] 生成序号列
来源：http://dali.c1oappe.top/Article/details/gtxetqswqo.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.pycfn.com/Article/details/gtwsrwtdgn.html

================================================================================
来源：http://dali.yj20258888.top/Article/details/gtvcegwhif.html

R. Bash 专题
来源：http://dali.cashguo.top/Article/details/gtjmgnlhye.html

================================================================================
来源：http://dali.yangfankeji.com/Article/details/gtffhzkvos.html

[R01] shebang 与严格模式
来源：http://dali.yj20258888.top/Article/details/gtvylvypxj.html

#!/usr/bin/env bash
来源：http://dali.xinyue.icu/Article/details/gthsbvrckf.html

set -euo pipefail
来源：http://dali.jlsjyb.cn/Article/details/gtlirryyvr.html

[R02] 变量赋值与使用
来源：http://dali.hammf.cn/Article/details/gtivbjjmuc.html

name="Tom"; echo "$name"
来源：http://dali.jinqigufen.top/Article/details/gtgmuwpefz.html

[R03] 只读变量
来源：http://dali.gzhubu.top/Article/details/gtntfbsngc.html

readonly PI=3.14
来源：http://dali.jianghu66.top/Article/details/gtghliqtti.html

[R04] 位置参数
来源：http://dali.hongshengwenyu.top/Article/details/gtpmaetqec.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.chenjidiqi.icu/Article/details/gtijqdkwlo.html

[R05] 参数默认值
来源：http://dali.yuxming.cn/Article/details/gtkziumpfl.html

name="${1:-default}"
来源：http://dali.hnqzz.top/Article/details/gtxmsvuvte.html

[R06] 判断命令是否存在
来源：http://dali.yonumen.top/Article/details/gtyoiasaat.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzpjjculg.html

[R07] if 判断文件
来源：http://dali.chenjidiqi.icu/Article/details/gtphvtetau.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.c1oappe.top/Article/details/gtflsxxfdy.html

[R08] 数值比较
来源：http://dali.xuanzx.com/Article/details/gtijsdtnrl.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yj202588.top/Article/details/gtwyblxade.html

[R09] 字符串比较
来源：http://dali.cashguo.top/Article/details/gtztqihviy.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.cashguo.top/Article/details/gtyvpebval.html

[R10] 正则匹配
来源：http://dali.yangfankeji.com/Article/details/gtipsspiws.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yongpay.top/Article/details/gtvzdvsnwv.html

[R11] case 多分支
来源：http://dali.c1oappe.top/Article/details/gtzapkorwd.html

case "$1" in
来源：http://dali.dashuyun.cn/Article/details/gtowothhhx.html

start) echo "启动" ;;
来源：http://dali.bjfxy.top/Article/details/gtkfcfhhld.html

stop)  echo "停止" ;;
来源：http://dali.jqgfzy.top/Article/details/gtcjzsynvh.html

*)     echo "未知命令" ;;
来源：http://dali.feifeiyinyue.top/Article/details/gtegzdkypm.html

esac
来源：http://dali.andypj.xyz/Article/details/gtokrhifpx.html

[R12] for 遍历文件
来源：http://dali.dianchejie.cn/Article/details/gtubqeyclo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cdnleiting.top/Article/details/gtjakqegaj.html

[R13] for 计数循环
来源：http://dali.sysykeji.top/Article/details/gtlodiaiwc.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.chenzaomai.com/Article/details/gtrvtvlltf.html

[R14] C 风格 for
来源：http://dali.iojbl.cn/Article/details/gtlgiseese.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sysykeji.top/Article/details/gttoppzgup.html

[R15] while 逐行读文件
来源：http://dali.iojbl.cn/Article/details/gtgbtlabyu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.0kj1m.cn/Article/details/gtrxlezbvm.html

[R16] until 等待条件
来源：http://dali.daxiang520.top/Article/details/gtkzjcgdfs.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hnxiangtu.top/Article/details/gtvjdsvwdt.html

[R17] 数组定义与取值
来源：http://dali.yanxiufei.cn/Article/details/gtetemwxbq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinqigufen.top/Article/details/gtmeyygsmc.html

[R18] 遍历数组
来源：http://dali.jqgufenzy.top/Article/details/gtwlrkahlg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shangyingyoupin.top/Article/details/gteaxmuwmq.html

[R19] 数组长度
来源：http://dali.zhengqikj.top/Article/details/gtdlssflce.html

echo "${#arr[@]}"
来源：http://dali.yj202588.top/Article/details/gthrkbkdvw.html

[R20] 关联数组（字典）
来源：http://dali.yongpay.top/Article/details/gtvusxapdz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.ehwqpu.com/Article/details/gtgobrwyyh.html

[R21] 字符串长度
来源：http://dali.yj20258888.top/Article/details/gtvbbncwmb.html

echo "${#s}"
来源：http://dali.yj20258888.top/Article/details/gtvvericuq.html

[R22] 截取子串
来源：http://dali.yanxiufei.cn/Article/details/gtbbjdkvrh.html

echo "${s:0:5}"
来源：http://dali.jianghu66.top/Article/details/gtzytrasjp.html

[R23] 字符串替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzalcmtby.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gaohongyu789.top/Article/details/gtafyqbflr.html

[R24] 大小写转换
来源：http://dali.cqqwz.cn/Article/details/gtlnxrncdy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cqqwz.cn/Article/details/gtbtwxaciu.html

[R25] 去后缀 / 去前缀
来源：http://dali.jianghu66.top/Article/details/gtprsylvpr.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.nwbrower.top/Article/details/gtjaufssbz.html

[R26] 命令替换
来源：http://dali.fzhhl.top/Article/details/gtrxugwhfr.html

now=$(date +%F); echo "$now"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqviuubql.html

[R27] 算术展开
来源：http://dali.ydzc1.top/Article/details/gtnsdqbupc.html

echo $((1 + 2 * 3))
来源：http://dali.yonumen.top/Article/details/gtsxatgoif.html

[R28] 浮点运算
来源：http://dali.mhx1999.top/Article/details/gthqlvnhkv.html

echo "scale=2; 10/3" | bc
来源：http://dali.shuidangran.top/Article/details/gtsoeogtcd.html

[R29] 定义函数
来源：http://dali.nwbrower.top/Article/details/gtayfmlfop.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhengqikj.top/Article/details/gtviixpgww.html

[R30] 函数返回状态码
来源：http://dali.smart0.xyz/Article/details/gtlvytdnlx.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.guowangkeji.top/Article/details/gtcuqmbrqm.html

[R31] 局部变量
来源：http://dali.snrcjt.cn/Article/details/gtdsvtomyl.html

f() { local x=1; echo "$x"; }
来源：http://dali.guannengcc.top/Article/details/gtvepuoemn.html

[R32] 参数个数校验
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdydovbxo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jqgfzy.top/Article/details/gtxkcvlktu.html

[R33] 捕获错误并提示行号
来源：http://dali.zycfv.cn/Article/details/gtwsknowlc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.316326.xyz/Article/details/gtsawlzqac.html

[R34] 退出时清理
来源：http://dali.dianchejie.cn/Article/details/gtrzotmisn.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hongshengwenyu.top/Article/details/gtuaomklfc.html

[R35] 后台执行并等待
来源：http://dali.jiagoushi.top/Article/details/gtuntltjgf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.sysykeji.top/Article/details/gtbzwtcftu.html

[R36] 并发执行多个任务
来源：http://dali.meibo888.top/Article/details/gtlziofdgh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xziqi.cn/Article/details/gtyfxbkplt.html

[R37] 把输出赋给变量
来源：http://dali.wangshuangyany.cn/Article/details/gthtgzjunb.html

files=$(ls -1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgebgjznz.html

[R38] 管道串联
来源：http://dali.zhixingplan.top/Article/details/gtahtrrubo.html

cat a.txt | grep -i error | wc -l
来源：http://dali.316326.xyz/Article/details/gttpktjyty.html

[R39] 重定向标准输出与错误
来源：http://dali.zhixingplan.top/Article/details/gticpaikqv.html

cmd > out.log 2>&1
来源：http://dali.fengsongda.top/Article/details/gtfthzvykn.html

[R40] 追加写日志
来源：http://dali.guannengcc.top/Article/details/gtpnkzxnkp.html

echo "log" >> out.log
来源：http://dali.shanyushiyangtech.top/Article/details/gtlbrksfru.html

[R41] 丢弃输出
来源：http://dali.sysykeji.top/Article/details/gtnbwetsbt.html

cmd >/dev/null 2>&1
来源：http://dali.yueranfly.top/Article/details/gtzzjgfsjg.html

[R42] 输入重定向
来源：http://dali.ivvv.top/Article/details/gtcpkvhkec.html

wc -l < a.txt
来源：http://dali.shangyingyoupin.top/Article/details/gtzqdybcmj.html

[R43] 按名字查找文件
来源：http://dali.vqdsnc.cn/Article/details/gtxwjmwuhe.html

find . -name "*.log" -type f
来源：http://dali.hywenlv.cn/Article/details/gtezkpeavq.html

[R44] 按修改时间查找
来源：http://dali.jianghu66.top/Article/details/gtgxovgtou.html

find . -mtime -7 -type f
来源：http://dali.xziqi.cn/Article/details/gtwdcjpvfp.html

[R45] 批量删除
来源：http://dali.yonumen.top/Article/details/gtsoxekotd.html

find . -name "*.tmp" -delete
来源：http://dali.yongpay.top/Article/details/gtclomklnq.html

[R46] 递归替换文件内容
来源：http://dali.zycfv.cn/Article/details/gtthmvcmgq.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.chenlongwang.top/Article/details/gtxsevhesf.html

[R47] sed 单行替换
来源：http://dali.gzhubu.top/Article/details/gtdagjmdkp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtlaiapded.html

[R48] awk 取指定列
来源：http://dali.guowangkeji.top/Article/details/gtysruposf.html

awk '{print $1, $3}' a.txt
来源：http://dali.jyoumei.cn/Article/details/gthxheesmd.html

[R49] awk 带条件
来源：http://dali.yuxming.cn/Article/details/gtyythpppe.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.quarkkingdee.top/Article/details/gtjstveqmi.html

[R50] awk 求和
来源：http://dali.ybcxt.top/Article/details/gtujzxepcz.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jiagoushi.top/Article/details/gtalqdjzmk.html

[R51] 排序去重取前几
来源：http://dali.yvedp.cn/Article/details/gtgnoebmto.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jqgufenzy.top/Article/details/gtitowwhun.html

[R52] 统计行数
来源：http://dali.yongpay.top/Article/details/gtlympkbiv.html

wc -l a.txt
来源：http://dali.ehwqpu.com/Article/details/gtmdekdvdj.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gtlcyyzukd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.mhx1999.top/Article/details/gthwqeldsz.html

[R54] 比较两个文件
来源：http://dali.ehwqpu.com/Article/details/gtbdcpjmmc.html

diff a.txt b.txt
来源：http://dali.316326.xyz/Article/details/gtkxgndoap.html

[R55] 压缩与解压
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlicgglfr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhiwuduotai.top/Article/details/gtyaczuitu.html

[R56] 远程拷贝
来源：http://dali.cheryme.top/Article/details/gtnkrknhei.html

scp file user@host:/path/
来源：http://dali.jinghuilouyu.cn/Article/details/gtwqjkemhn.html

[R57] 远程执行命令
来源：http://dali.jinghuilouyu.cn/Article/details/gtrdxtjfif.html

ssh user@host 'uptime'
来源：http://dali.feifeiyinyue.top/Article/details/gtrtwuzkkl.html

[R58] 下载文件
来源：http://dali.316326.xyz/Article/details/gtkbryzctk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xuetiantiany.cn/Article/details/gtrqluydit.html

[R59] 发 POST JSON
来源：http://dali.sweek.top/Article/details/gtddsmlpfa.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.ydzc1.top/Article/details/gtsippjijb.html

[R60] 只看 HTTP 状态码
来源：http://dali.9152youxi.cn/Article/details/gtmleubbca.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhixingplan.top/Article/details/gtyvlyjckb.html

[R61] 磁盘占用
来源：http://dali.ybcxt.top/Article/details/gtktllmycf.html

df -h;  du -sh *
来源：http://dali.andypj.xyz/Article/details/gtlaskvwhc.html

[R62] 找最占空间的文件
来源：http://dali.sxryk.cn/Article/details/gtbkyvqpsl.html

du -ah . | sort -rh | head -10
来源：http://dali.cdnleiting.top/Article/details/gtggunbfra.html

[R63] 内存与进程
来源：http://dali.xinyue.icu/Article/details/gtuohoiysz.html


<!-- 参考信息 -->