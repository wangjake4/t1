代发 wailian999

[Q14] 存在则更新（upsert）
来源：http://dali.nanxuanxn.top/Article/details/gtxqvxmgoz.html

INSERT INTO users (email, name) VALUES ('a@a.com', 'A')
来源：http://dali.zhiwuduotai.top/Article/details/gthotyvssf.html

ON DUPLICATE KEY UPDATE name = VALUES(name);
来源：http://dali.xinyue.icu/Article/details/gtpwudaakq.html

[Q15] 查询全部
来源：http://dali.havefunace.top/Article/details/gtybucgehy.html

SELECT * FROM users;
来源：http://dali.nwbrower.top/Article/details/gtfikprdbz.html

[Q16] 查询指定列
来源：http://dali.aizwys.cn/Article/details/gtvhtlkduw.html

SELECT id, name FROM users;
来源：http://dali.guannengcc.top/Article/details/gttedoznvy.html

[Q17] 条件查询
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqiuxqrtk.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.wangshuangyany.cn/Article/details/gtkaepkpbu.html

[Q18] 模糊匹配
来源：http://dali.tian-w.cn/Article/details/gtthffzjqb.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.andypj.xyz/Article/details/gtvlociscv.html

[Q19] 范围查询
来源：http://dali.smart0.xyz/Article/details/gtjubflraz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.aizwys.cn/Article/details/gtrwyujlgi.html

[Q20] IN 列表
来源：http://dali.shuidangran.top/Article/details/gtrpajdpkt.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.guannengcc.top/Article/details/gtxetzsoqe.html

[Q21] 空值判断
来源：http://dali.zhoulong.xyz/Article/details/gttdqusjel.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jianghu66.top/Article/details/gtqugqiclt.html

[Q22] 排序
来源：http://dali.yj20258.top/Article/details/gtxzhuytqu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gogol.net.cn/Article/details/gtcfaopytk.html

[Q23] 分页
来源：http://dali.zhongyouzk.top/Article/details/gtskkflzob.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ybcxt.top/Article/details/gtqujiqigb.html

[Q24] 去重
来源：http://dali.cqqwz.cn/Article/details/gticsnunvn.html

SELECT DISTINCT city FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtqjtoclnr.html

[Q25] 只取前 N 条
来源：http://dali.tanke756.top/Article/details/gtevypcqch.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.yuxming.cn/Article/details/gtlxcvwsuo.html

[Q26] 计数
来源：http://dali.nwbrower.top/Article/details/gtaqhcrjai.html

SELECT COUNT(*) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtncmqblqg.html

[Q27] 条件计数
来源：http://dali.bjfxy.top/Article/details/gtgedysqqh.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtnuoylowy.html

[Q28] 求和与平均
来源：http://dali.yvedp.cn/Article/details/gtoeaowrpn.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gtleqxjxvn.html

[Q29] 最大最小值
来源：http://dali.cheryme.top/Article/details/gtsbsgzzpu.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gttnvbbhih.html

[Q30] 分组统计
来源：http://dali.zycfv.cn/Article/details/gtdqfomzpa.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shuidangran.top/Article/details/gtuhwojlcd.html

[Q31] 分组后过滤
来源：http://dali.guowangkeji.top/Article/details/gtrxnzakuk.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.pengpengdd.cyou/Article/details/gtemvghddx.html

[Q32] 分组拼接字符串
来源：http://dali.ppjwa.cn/Article/details/gtslqvawuc.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jlsjyb.cn/Article/details/gtlnvsovpt.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.xziqi.cn/Article/details/gtkrcxuyyj.html

[Q33] 多列分组
来源：http://dali.yvedp.cn/Article/details/gtcuvesbdz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.gzhubu.top/Article/details/gtmoljeisi.html

[Q34] 每组取第一条
来源：http://dali.316326.xyz/Article/details/gtceaqmtlb.html

SELECT * FROM (
来源：http://dali.jinyuanbaomall.cn/Article/details/gtikhgcwtv.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shzxlz.cn/Article/details/gtnylgbbic.html

) t WHERE rn = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkafdpztb.html

[Q35] 内连接
来源：http://dali.jqgfzy.top/Article/details/gtuovzogao.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.yonumen.top/Article/details/gttydabsdx.html

[Q36] 左连接
来源：http://dali.zhongyouzk.top/Article/details/gtaesojrpt.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yangfankeji.com/Article/details/gtejsnkrca.html

[Q37] 右连接
来源：http://dali.jiagoushi.top/Article/details/gtbikygjtv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xuetiantiany.cn/Article/details/gtjtlxhxwt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhengqikj.top/Article/details/gtqxzrwbwl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jqgfzy.top/Article/details/gtflhxeezi.html

[Q39] 自连接（查上下级）
来源：http://dali.cdnleiting.top/Article/details/gtvbdmvwht.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.nanxuanxn.top/Article/details/gtqjsstbai.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.sysykeji.top/Article/details/gtslmjzajt.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.svipenyu.cn/Article/details/gtduvlgfjl.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.pycfn.com/Article/details/gtrgmtbpup.html

[Q41] 多表连接
来源：http://dali.yvedp.cn/Article/details/gtvfhwdrkb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xuanzx.com/Article/details/gtnywuidgy.html

JOIN users u ON u.id = o.user_id
来源：http://dali.c1oappe.top/Article/details/gtxbbxcfqv.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sxryk.cn/Article/details/gtippnlstr.html

[Q42] 连接条件附加过滤
来源：http://dali.svipenyu.cn/Article/details/gtklwgkdqn.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cucudq.cn/Article/details/gtyszfdsgr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hammf.cn/Article/details/gtijauxrzl.html

[Q43] 标量子查询
来源：http://dali.wangshuangyany.cn/Article/details/gtqlyjthdd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.gogol.net.cn/Article/details/gtniyxekrd.html

[Q44] IN 子查询
来源：http://dali.yanxiufei.cn/Article/details/gtdaozbsmu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.ydzc1.top/Article/details/gtcfygyoer.html

[Q45] EXISTS 判断存在
来源：http://dali.fengsongda.top/Article/details/gtwfsuyudv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhixingplan.top/Article/details/gtnqpqnhgz.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jlsjyb.cn/Article/details/gtwcpydhxw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nwbrower.top/Article/details/gtgxwmuggq.html

[Q47] 与平均值比较
来源：http://dali.smart0.xyz/Article/details/gtcakigcsv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sxryk.cn/Article/details/gtgmdpxbyl.html

[Q48] CTE 公用表表达式
来源：http://dali.hfpthk.cn/Article/details/gtbsfkrshj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.meibo888.top/Article/details/gtfhpgikrw.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zhengqikj.top/Article/details/gtawcgowcx.html

[Q49] 更新单行
来源：http://dali.yongpay.top/Article/details/gtquozrtmu.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.haohaochexian.top/Article/details/gtrcxiydzc.html

[Q50] 批量更新
来源：http://dali.tian-w.cn/Article/details/gtloggkwiy.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.guowangkeji.top/Article/details/gtplxdbroi.html

[Q51] 用子查询更新
来源：http://dali.zdqjudy.top/Article/details/gtxecjsuzy.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhiwuduotai.top/Article/details/gtcpdxwslv.html

[Q52] 删除指定行
来源：http://dali.shangyingyoupin.top/Article/details/gtblyvmslx.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cqqwz.cn/Article/details/gtckcwlbsf.html

[Q53] 按条件删除
来源：http://dali.jinqigufen.top/Article/details/gttrhmlsoy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xuetiantiany.cn/Article/details/gtvgoxlgbm.html

[Q54] 清空表
来源：http://dali.ppjwa.cn/Article/details/gttyjmldsn.html

TRUNCATE TABLE logs;
来源：http://dali.guannengcc.top/Article/details/gthmtozanc.html

[Q55] 排名（并列占位）
来源：http://dali.andypj.xyz/Article/details/gtbbxojqfh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shangyingyoupin.top/Article/details/gtoawilfvi.html

[Q56] 密集排名（并列不占位）
来源：http://dali.daxiang520.top/Article/details/gtfcqypime.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yueranfly.top/Article/details/gtpozumqwu.html

[Q57] 行号
来源：http://dali.zhiwuduotai.top/Article/details/gtcckipcab.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtegfoypzd.html

[Q58] 累计求和
来源：http://dali.chenzaomai.com/Article/details/gtdzvhxwec.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.sysykeji.top/Article/details/gttumtrgsy.html

[Q59] 分组内累计
来源：http://dali.zdqjudy.top/Article/details/gticfkxolu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtrgftulyr.html

[Q60] 取上一行 / 下一行
来源：http://dali.andypj.xyz/Article/details/gtiwkdtjze.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.aibaodan.cn/Article/details/gtkaiwsyrq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gtgigjrwpz.html

[Q61] 移动平均
来源：http://dali.aibaodan.cn/Article/details/gtjmvgmjuw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtkevoflyv.html

[Q62] 分组占比
来源：http://dali.gaohongyu789.top/Article/details/gtodwtmfns.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.9152youxi.cn/Article/details/gtivmgffmd.html

[Q63] 开启事务
来源：http://dali.yonumen.top/Article/details/gtngkwtaom.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.ydzc1.top/Article/details/gtjkxckqvh.html

[Q64] 提交事务
来源：http://dali.ydzc1.top/Article/details/gtraydjtbu.html

COMMIT;
来源：http://dali.shanyushiyangtech.top/Article/details/gtjyrimymc.html

[Q65] 回滚事务
来源：http://dali.tanke756.top/Article/details/gtlmvwxvzv.html

ROLLBACK;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtoaiohpna.html

[Q66] 行锁查询
来源：http://dali.xuetiantiany.cn/Article/details/gtuvaxegxf.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cdnleiting.top/Article/details/gtbkieqxku.html

[Q67] 设置隔离级别
来源：http://dali.redwolf501.top/Article/details/gtohxoywkt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.gaohongyu789.top/Article/details/gtdrjunwtn.html

[Q68] 保存点
来源：http://dali.jlsjyb.cn/Article/details/gtpexblzay.html

SAVEPOINT sp1;
来源：http://dali.nwbrower.top/Article/details/gtevfhgoqw.html

ROLLBACK TO sp1;
来源：http://dali.tianlin.xyz/Article/details/gtqjirhttu.html

[Q69] 查看执行计划
来源：http://dali.yuxming.cn/Article/details/gttqxxhprb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jianghu66.top/Article/details/gtiqzefwzw.html

[Q70] 更新统计信息
来源：http://dali.shangyingyoupin.top/Article/details/gtcenvabtd.html

ANALYZE TABLE users;
来源：http://dali.zdqjudy.top/Article/details/gtoofllxnd.html

[Q71] 查看建表语句
来源：http://dali.yj20258.top/Article/details/gtfmokeqlr.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.tanke756.top/Article/details/gtgjaajwtn.html

[Q72] 查看索引
来源：http://dali.jianghu66.top/Article/details/gtnpabwqbu.html

SHOW INDEX FROM users;
来源：http://dali.pengpengdd.cyou/Article/details/gtplntosvg.html

[Q73] 查看表状态
来源：http://dali.sweek.top/Article/details/gtotfaolxb.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cucudq.cn/Article/details/gtnxywyegi.html

[Q74] 强制使用索引
来源：http://dali.guannengcc.top/Article/details/gtvvxauvcm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.sxryk.cn/Article/details/gtkaeplvrp.html

[Q75] 日期格式化
来源：http://dali.svipenyu.cn/Article/details/gtiupjudli.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gtxryairzp.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ehwqpu.com/Article/details/gtgortasmk.html

[Q76] 按天统计
来源：http://dali.zhiwuduotai.top/Article/details/gtrwtriijf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.feifeiyinyue.top/Article/details/gtkbhcctxc.html

[Q77] 时间加减
来源：http://dali.c1oappe.top/Article/details/gtdmxnvasf.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.sysykeji.top/Article/details/gtdmtcxgtz.html

[Q78] 当前时间
来源：http://dali.yuxming.cn/Article/details/gtbkudguny.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.quarkkingdee.top/Article/details/gtnnwmpglt.html

[Q79] 字符串拼接
来源：http://dali.dianchejie.cn/Article/details/gtsdhwcmiq.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.hfpthk.cn/Article/details/gtbxmxffcf.html

[Q80] 字符串截取
来源：http://dali.jqgfzy.top/Article/details/gtrdkxlbfb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtrbjljsdp.html

[Q81] 字符串替换
来源：http://dali.guowangkeji.top/Article/details/gtcsbvjopd.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtzufkjqpl.html

[Q82] 字符长度与字节长度
来源：http://dali.yuxming.cn/Article/details/gtyojgsxgr.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtsaovkqic.html

[Q83] 大小写转换
来源：http://dali.sxryk.cn/Article/details/gtofvncnve.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.havefunace.top/Article/details/gtjeswpqqi.html

[Q84] 去除首尾空格
来源：http://dali.zdqjudy.top/Article/details/gtiescwmta.html

SELECT TRIM(name) FROM users;
来源：http://dali.xinyue.icu/Article/details/gtqqyjftjm.html

[Q85] 数值取整
来源：http://dali.andypj.xyz/Article/details/gttqkotcil.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zdqjudy.top/Article/details/gtcbizeeqc.html

[Q86] 读取 JSON 字段
来源：http://dali.hnqzz.top/Article/details/gtijawqrsp.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinqigfzy.top/Article/details/gtorjplfeb.html

[Q87] JSON 字段做条件
来源：http://dali.smart0.xyz/Article/details/gtsgeputan.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.yongpay.top/Article/details/gtexazauxw.html

[Q88] 行转列（条件聚合）
来源：http://dali.shangyingyoupin.top/Article/details/gtwwzyscpf.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yanxiufei.cn/Article/details/gtmamxxutl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gttvyvghce.html

[Q89] 判断表是否存在
来源：http://dali.yangfankeji.com/Article/details/gtmqduyvpy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.smart0.xyz/Article/details/gtrcyiwfuy.html

[Q90] 生成序号列
来源：http://dali.yueranfly.top/Article/details/gteuyzkkly.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.yvedp.cn/Article/details/gttsrgkeoy.html

================================================================================
来源：http://dali.iojbl.cn/Article/details/gtvwjvrwtb.html

R. Bash 专题
来源：http://dali.jinqigfzy.top/Article/details/gtmusemgdw.html

================================================================================
来源：http://dali.ivvv.top/Article/details/gtczlbuotx.html

[R01] shebang 与严格模式
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwnqwfvdb.html

#!/usr/bin/env bash
来源：http://dali.chenjidiqi.icu/Article/details/gtvdkzdrkd.html

set -euo pipefail
来源：http://dali.wangdashe.top/Article/details/gttxjcjtmh.html

[R02] 变量赋值与使用
来源：http://dali.jqgufenzy.top/Article/details/gtxmbueuih.html

name="Tom"; echo "$name"
来源：http://dali.ydzc1.top/Article/details/gtnphdgtog.html

[R03] 只读变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtddacjqxp.html

readonly PI=3.14
来源：http://dali.guowangkeji.top/Article/details/gtotjgywoi.html

[R04] 位置参数
来源：http://dali.aizwys.cn/Article/details/gtjywdoagp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.9152youxi.cn/Article/details/gtssofidtu.html

[R05] 参数默认值
来源：http://dali.snrcjt.cn/Article/details/gtwlmydfis.html

name="${1:-default}"
来源：http://dali.tianlin.xyz/Article/details/gtylgwztcj.html

[R06] 判断命令是否存在
来源：http://dali.xinyue.icu/Article/details/gtuzzvfpyf.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xuanzx.com/Article/details/gtxqctpllc.html

[R07] if 判断文件
来源：http://dali.ehwqpu.com/Article/details/gthwckpxby.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.nanxinkj.top/Article/details/gttojdclqa.html

[R08] 数值比较
来源：http://dali.shanyushiyangtech.top/Article/details/gtvtlxkgso.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jlsjyb.cn/Article/details/gtkazpkara.html

[R09] 字符串比较
来源：http://dali.yj202588.top/Article/details/gtosuwtzuf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.yuxming.cn/Article/details/gtydqxwgrc.html

[R10] 正则匹配
来源：http://dali.guannengcc.top/Article/details/gttlcsmumh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.mhx1999.top/Article/details/gtsjihcevz.html

[R11] case 多分支
来源：http://dali.meibo888.top/Article/details/gtspynosqk.html

case "$1" in
来源：http://dali.snrcjt.cn/Article/details/gtfgmguemx.html

start) echo "启动" ;;
来源：http://dali.yvedp.cn/Article/details/gtrdpupdpu.html

stop)  echo "停止" ;;
来源：http://dali.yvedp.cn/Article/details/gtiukyknnb.html

*)     echo "未知命令" ;;
来源：http://dali.zhiwuduotai.top/Article/details/gtuuaiodmx.html

esac
来源：http://dali.zhengqikj.top/Article/details/gttutuqoux.html

[R12] for 遍历文件
来源：http://dali.yuxming.cn/Article/details/gtbrgjyoca.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzpcwhfhe.html

[R13] for 计数循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqrovztfe.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhengqikj.top/Article/details/gtwevuhhjp.html

[R14] C 风格 for
来源：http://dali.zhongyouzk.top/Article/details/gtlrtfhpuu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ydzc1.top/Article/details/gtuosftowb.html

[R15] while 逐行读文件
来源：http://dali.sufxvd.cn/Article/details/gtzggkfgau.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jqgfzy.top/Article/details/gtqrufkppu.html

[R16] until 等待条件
来源：http://dali.ydzc1.top/Article/details/gtgrnfjxgr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.nwbrower.top/Article/details/gtannhwlaf.html

[R17] 数组定义与取值
来源：http://dali.jyoumei.cn/Article/details/gttidzagrv.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gttyvydcts.html

[R18] 遍历数组
来源：http://dali.gaohongyu789.top/Article/details/gtjvnakavb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gotoacloud.top/Article/details/gttrizyvuo.html

[R19] 数组长度
来源：http://dali.yangfankeji.com/Article/details/gtrtcaatpi.html

echo "${#arr[@]}"
来源：http://dali.yanxiufei.cn/Article/details/gthmqplvox.html

[R20] 关联数组（字典）
来源：http://dali.iojbl.cn/Article/details/gttybcdwvd.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xinyue.icu/Article/details/gthmkipyta.html

[R21] 字符串长度
来源：http://dali.feifeiyinyue.top/Article/details/gtaznoumyf.html

echo "${#s}"
来源：http://dali.andypj.xyz/Article/details/gtpetsimjv.html

[R22] 截取子串
来源：http://dali.yuxming.cn/Article/details/gtssxtqggx.html

echo "${s:0:5}"
来源：http://dali.gogol.net.cn/Article/details/gtrnrkving.html

[R23] 字符串替换
来源：http://dali.birdmap.top/Article/details/gtocusygif.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.meibo888.top/Article/details/gttjayeofb.html

[R24] 大小写转换
来源：http://dali.sxryk.cn/Article/details/gtlirrbqls.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtzgdxlzjz.html

[R25] 去后缀 / 去前缀
来源：http://dali.pengpengdd.cyou/Article/details/gtcbopuxvb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.cucudq.cn/Article/details/gtlgttnuqf.html

[R26] 命令替换
来源：http://dali.316326.xyz/Article/details/gtdyxabdei.html

now=$(date +%F); echo "$now"
来源：http://dali.mhx1999.top/Article/details/gtzmgxnirm.html

[R27] 算术展开
来源：http://dali.gotoacloud.top/Article/details/gtonkvruco.html

echo $((1 + 2 * 3))
来源：http://dali.guowangkeji.top/Article/details/gtlsuortnf.html

[R28] 浮点运算
来源：http://dali.nanxuanxn.top/Article/details/gttbmdmtgf.html

echo "scale=2; 10/3" | bc
来源：http://dali.yonumen.top/Article/details/gtgrvdqsmr.html

[R29] 定义函数
来源：http://dali.shanyushiyangkeji.top/Article/details/gtydqhrobn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.smart0.xyz/Article/details/gtnmmsgkeu.html

[R30] 函数返回状态码
来源：http://dali.guannengcc.top/Article/details/gtprkiezuk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ybcxt.top/Article/details/gtaregorgt.html

[R31] 局部变量
来源：http://dali.snrcjt.cn/Article/details/gtpndoegkb.html

f() { local x=1; echo "$x"; }
来源：http://dali.hnxiangtu.top/Article/details/gtwctaibsp.html

[R32] 参数个数校验
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoucmzwlg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xylfe.cn/Article/details/gtksdgbcma.html

[R33] 捕获错误并提示行号
来源：http://dali.tian-w.cn/Article/details/gtaxrtnadc.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hammf.cn/Article/details/gtevmfnups.html

[R34] 退出时清理
来源：http://dali.jinyuanbaomall.cn/Article/details/gtanfzdfhr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.iojbl.cn/Article/details/gtxkdqhuov.html

[R35] 后台执行并等待
来源：http://dali.quarkkingdee.top/Article/details/gtxrdsqyzr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jqgufenzy.top/Article/details/gtkealdcdp.html

[R36] 并发执行多个任务
来源：http://dali.andypj.xyz/Article/details/gtlcuqullp.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zycfv.cn/Article/details/gtxlxlmpkv.html

[R37] 把输出赋给变量
来源：http://dali.hongshengwenyu.top/Article/details/gtsozpegmu.html

files=$(ls -1)
来源：http://dali.zhoulong.xyz/Article/details/gtwgmlmuag.html

[R38] 管道串联
来源：http://dali.andypj.xyz/Article/details/gtaghmlxuq.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ydzc1.top/Article/details/gtgabhoalv.html

[R39] 重定向标准输出与错误
来源：http://dali.gzhubu.top/Article/details/gtguqowcso.html

cmd > out.log 2>&1
来源：http://dali.ybcxt.top/Article/details/gtwligppgz.html

[R40] 追加写日志
来源：http://dali.guowangkeji.top/Article/details/gtdtzymmjr.html

echo "log" >> out.log
来源：http://dali.yuxming.cn/Article/details/gtttlctktn.html

[R41] 丢弃输出
来源：http://dali.nwbrower.top/Article/details/gtpcjuaoxb.html

cmd >/dev/null 2>&1
来源：http://dali.tian-w.cn/Article/details/gtdltcbetk.html

[R42] 输入重定向
来源：http://dali.tianlin.xyz/Article/details/gttvvdrbge.html

wc -l < a.txt
来源：http://dali.zycfv.cn/Article/details/gtbducicke.html

[R43] 按名字查找文件
来源：http://dali.gogol.net.cn/Article/details/gtcipnjdbt.html

find . -name "*.log" -type f
来源：http://dali.tian-w.cn/Article/details/gtuuseoisg.html

[R44] 按修改时间查找
来源：http://dali.aizwys.cn/Article/details/gtsaizmlzo.html

find . -mtime -7 -type f
来源：http://dali.haohaochexian.top/Article/details/gtshkporaf.html

[R45] 批量删除
来源：http://dali.gaohongyu789.top/Article/details/gtmcyeagmx.html

find . -name "*.tmp" -delete
来源：http://dali.nwbrower.top/Article/details/gtlferprlg.html

[R46] 递归替换文件内容
来源：http://dali.wangdashe.top/Article/details/gtjhnudtzc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ehwqpu.com/Article/details/gtuezujsuq.html

[R47] sed 单行替换
来源：http://dali.pycfn.com/Article/details/gtvfzfxwvg.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.fzhhl.top/Article/details/gtozvawmji.html

[R48] awk 取指定列
来源：http://dali.zhixingplan.top/Article/details/gtkhhpoyez.html

awk '{print $1, $3}' a.txt
来源：http://dali.cucudq.cn/Article/details/gtcsjxkfnh.html

[R49] awk 带条件
来源：http://dali.zhengqikj.top/Article/details/gtshioibto.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.quarkkingdee.top/Article/details/gtxykxvoup.html

[R50] awk 求和
来源：http://dali.aibaodan.cn/Article/details/gtvgumqyxr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.c1oappe.top/Article/details/gttqrmhuec.html

[R51] 排序去重取前几
来源：http://dali.hammf.cn/Article/details/gtqqbzgioz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.hammf.cn/Article/details/gtyokvwgtz.html

[R52] 统计行数
来源：http://dali.guowangkeji.top/Article/details/gtgpayccqy.html

wc -l a.txt
来源：http://dali.zhongyouzk.top/Article/details/gtkmhjldjn.html

[R53] 查看文件头与实时尾
来源：http://dali.yj202588.top/Article/details/gtnditxdar.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.snrcjt.cn/Article/details/gtxdnlbigz.html

[R54] 比较两个文件
来源：http://dali.hywenlv.cn/Article/details/gtqzcapovd.html

diff a.txt b.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpfglmqks.html

[R55] 压缩与解压
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdfyxqrei.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shuidangran.top/Article/details/gtzbkpsudk.html

[R56] 远程拷贝
来源：http://dali.andypj.xyz/Article/details/gtuypbrwpp.html

scp file user@host:/path/
来源：http://dali.zhengqikj.top/Article/details/gtpxvrlapb.html

[R57] 远程执行命令
来源：http://dali.hywenlv.cn/Article/details/gtdaqsotkd.html

ssh user@host 'uptime'
来源：http://dali.jqgufenzy.top/Article/details/gtrvwidqxo.html

[R58] 下载文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gttcjgndbx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.ivvv.top/Article/details/gttxmqacns.html

[R59] 发 POST JSON
来源：http://dali.vqdsnc.cn/Article/details/gtjvbfaezc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.kuanghao11.cn/Article/details/gtwyfqhqgt.html

[R60] 只看 HTTP 状态码
来源：http://dali.aibaodan.cn/Article/details/gtmrqutcdc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shanyushiyangkeji.top/Article/details/gtnqoaenwn.html

[R61] 磁盘占用
来源：http://dali.hongshengwenyu.top/Article/details/gtzilufcpf.html

df -h;  du -sh *
来源：http://dali.nanxuanxn.top/Article/details/gtqdnrlxzw.html

[R62] 找最占空间的文件
来源：http://dali.hfpthk.cn/Article/details/gtyuwynytm.html

du -ah . | sort -rh | head -10
来源：http://dali.zhoulong.xyz/Article/details/gtbzsxsneo.html

[R63] 内存与进程
来源：http://dali.tianlin.xyz/Article/details/gtfrvsrwqk.html


<!-- 参考信息 -->