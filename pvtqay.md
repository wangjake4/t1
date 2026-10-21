代发 wailian999

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtypijmbks.html

[Q18] 模糊匹配
来源：http://dali.wangdashe.top/Article/details/gtbtehvxbo.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.shangyingyoupin.top/Article/details/gtonkuzhdn.html

[Q19] 范围查询
来源：http://dali.jiagoushi.top/Article/details/gtygqsnrlz.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jlsjyb.cn/Article/details/gthafvlimm.html

[Q20] IN 列表
来源：http://dali.cdnleiting.top/Article/details/gtbalrhvor.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.jinghuilouyu.cn/Article/details/gtbipyvlqg.html

[Q21] 空值判断
来源：http://dali.andypj.xyz/Article/details/gtyruhbpvk.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yvedp.cn/Article/details/gtpewdpegq.html

[Q22] 排序
来源：http://dali.cdnleiting.top/Article/details/gtpmizzvnu.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jiagoushi.top/Article/details/gtfrcypbad.html

[Q23] 分页
来源：http://dali.9152youxi.cn/Article/details/gtnyohbzns.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yanxiufei.cn/Article/details/gtvczmwkhr.html

[Q24] 去重
来源：http://dali.jinqigufen.top/Article/details/gtoxgqagsd.html

SELECT DISTINCT city FROM users;
来源：http://dali.yuxming.cn/Article/details/gtbtopivcy.html

[Q25] 只取前 N 条
来源：http://dali.jqgufenzy.top/Article/details/gtxusatpjt.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.aibaodan.cn/Article/details/gtqfdmfyot.html

[Q26] 计数
来源：http://dali.hnqzz.top/Article/details/gtksozmbce.html

SELECT COUNT(*) FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtesgtmqjx.html

[Q27] 条件计数
来源：http://dali.quarkkingdee.top/Article/details/gtlwvoiotl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.tanke756.top/Article/details/gtuwuobnvq.html

[Q28] 求和与平均
来源：http://dali.zhiwuduotai.top/Article/details/gtafrfeyxk.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gtflrermth.html

[Q29] 最大最小值
来源：http://dali.ydzc1.top/Article/details/gtoygrulha.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtikkqcauw.html

[Q30] 分组统计
来源：http://dali.tianlin.xyz/Article/details/gtfesisffa.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.dianchejie.cn/Article/details/gtlnhxtuyc.html

[Q31] 分组后过滤
来源：http://dali.hammf.cn/Article/details/gthktqplri.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.snrcjt.cn/Article/details/gtperzxujb.html

[Q32] 分组拼接字符串
来源：http://dali.zhijiandao.cn/Article/details/gthavejeer.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yanxiufei.cn/Article/details/gtllinrezd.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hongshengwenyu.top/Article/details/gtapxxmqwq.html

[Q33] 多列分组
来源：http://dali.sufxvd.cn/Article/details/gtrgvwtgnj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jiagoushi.top/Article/details/gtzsugmjeh.html

[Q34] 每组取第一条
来源：http://dali.aibaodan.cn/Article/details/gttuabbyus.html

SELECT * FROM (
来源：http://dali.cucudq.cn/Article/details/gtaxbjyoab.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yuanzhike.top/Article/details/gtcojhlljx.html

) t WHERE rn = 1;
来源：http://dali.yvedp.cn/Article/details/gtmlkvchkf.html

[Q35] 内连接
来源：http://dali.sweek.top/Article/details/gttdvdrhxm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.tanke756.top/Article/details/gtaghkqfvi.html

[Q36] 左连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgmvrqngl.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.daria6918.cn/Article/details/gtnwxoslcn.html

[Q37] 右连接
来源：http://dali.yvedp.cn/Article/details/gtpvbgfgwj.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hysaishi.cn/Article/details/gtbfeaanlc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinqigufen.top/Article/details/gtrpbtvacl.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ivvv.top/Article/details/gtmjxdivta.html

[Q39] 自连接（查上下级）
来源：http://dali.chenlongwang.top/Article/details/gtprtddyky.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cqqwz.cn/Article/details/gtehvtxsdc.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xinyue.icu/Article/details/gtarwgydlr.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.redwolf501.top/Article/details/gtwnkovxor.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yuanzhike.top/Article/details/gtsvjvnvqi.html

[Q41] 多表连接
来源：http://dali.xuetiantiany.cn/Article/details/gtmyhtidqn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.cashguo.top/Article/details/gtygqixyht.html

JOIN users u ON u.id = o.user_id
来源：http://dali.tian-w.cn/Article/details/gtkrowxpnf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.nanxuanxn.top/Article/details/gtzoisatoq.html

[Q42] 连接条件附加过滤
来源：http://dali.jinqigufen.top/Article/details/gtolarjwzo.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hnqzz.top/Article/details/gtwqgerqgt.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yuanzhike.top/Article/details/gtuuxkzbio.html

[Q43] 标量子查询
来源：http://dali.0kj1m.cn/Article/details/gtfvmmxlir.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.wangshuangyany.cn/Article/details/gtkvfwcnvx.html

[Q44] IN 子查询
来源：http://dali.cucudq.cn/Article/details/gtubwsvrbm.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtndelfrxh.html

[Q45] EXISTS 判断存在
来源：http://dali.cucudq.cn/Article/details/gtfpuhhxwv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jyoumei.cn/Article/details/gtbzoznacl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.chenlongwang.top/Article/details/gtejnqszud.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xylfe.cn/Article/details/gtvynrpiid.html

[Q47] 与平均值比较
来源：http://dali.zhaomingkeji.xyz/Article/details/gtbxqtvhek.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvbldnpdg.html

[Q48] CTE 公用表表达式
来源：http://dali.nanxuanxn.top/Article/details/gtoervdmsl.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.ivvv.top/Article/details/gtokpvjiwx.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.iojbl.cn/Article/details/gtazlifslr.html

[Q49] 更新单行
来源：http://dali.ybcxt.top/Article/details/gtxfadjqdj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.iojbl.cn/Article/details/gtqlahktvy.html

[Q50] 批量更新
来源：http://dali.tian-w.cn/Article/details/gtaviddrvy.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhengqikj.top/Article/details/gtvkfgktvt.html

[Q51] 用子查询更新
来源：http://dali.zhongyouzk.top/Article/details/gtrkzjstdt.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ppjwa.cn/Article/details/gtghyxavzb.html

[Q52] 删除指定行
来源：http://dali.wangshuangyany.cn/Article/details/gtzxwkrkry.html

DELETE FROM users WHERE id = 10;
来源：http://dali.fengsongda.top/Article/details/gtwfygswll.html

[Q53] 按条件删除
来源：http://dali.sweek.top/Article/details/gtgvklqztt.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.mhx1999.top/Article/details/gtsugsyxwc.html

[Q54] 清空表
来源：http://dali.chenjidiqi.icu/Article/details/gtjdawvjks.html

TRUNCATE TABLE logs;
来源：http://dali.gotoacloud.top/Article/details/gtsmselyzg.html

[Q55] 排名（并列占位）
来源：http://dali.jinqigufen.top/Article/details/gtzjxomhze.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.vqdsnc.cn/Article/details/gtpqlzmnjw.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yongpay.top/Article/details/gtkucwznoq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.kuanghao11.cn/Article/details/gtxxpsgqhx.html

[Q57] 行号
来源：http://dali.xuetiantiany.cn/Article/details/gtwllzzzqq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.cashguo.top/Article/details/gtvrofseru.html

[Q58] 累计求和
来源：http://dali.jqgfzy.top/Article/details/gtheaxosfq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gtlzmxivkb.html

[Q59] 分组内累计
来源：http://dali.nwbrower.top/Article/details/gtjjapnayy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtdagyaegh.html

[Q60] 取上一行 / 下一行
来源：http://dali.jqgufenzy.top/Article/details/gtemegjnnq.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinghuilouyu.cn/Article/details/gtivkhbcjd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtburtxbwu.html

[Q61] 移动平均
来源：http://dali.chenzaomai.com/Article/details/gtljyjswjs.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtgqwfesht.html

[Q62] 分组占比
来源：http://dali.nwbrower.top/Article/details/gttyhyhlvc.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.wangshuangyany.cn/Article/details/gtpfndylrp.html

[Q63] 开启事务
来源：http://dali.ydzc1.top/Article/details/gtadfeltts.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gogol.net.cn/Article/details/gthbfaynbv.html

[Q64] 提交事务
来源：http://dali.xinyue.icu/Article/details/gtqsynmxwp.html

COMMIT;
来源：http://dali.yj20258.top/Article/details/gtqeqntgpm.html

[Q65] 回滚事务
来源：http://dali.meibo888.top/Article/details/gtnybsfbsf.html

ROLLBACK;
来源：http://dali.pycfn.com/Article/details/gtfdsvbtco.html

[Q66] 行锁查询
来源：http://dali.ppjwa.cn/Article/details/gtxiruotgd.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.tian-w.cn/Article/details/gtpneloyxb.html

[Q67] 设置隔离级别
来源：http://dali.kuanghao11.cn/Article/details/gtirvenoeu.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xuanzx.com/Article/details/gtmestdjbn.html

[Q68] 保存点
来源：http://dali.xuanzx.com/Article/details/gtjwixlrtc.html

SAVEPOINT sp1;
来源：http://dali.jinqigfzy.top/Article/details/gtomcgfaif.html

ROLLBACK TO sp1;
来源：http://dali.yanxiufei.cn/Article/details/gtiqeewklj.html

[Q69] 查看执行计划
来源：http://dali.cdnleiting.top/Article/details/gtvnwaxkff.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ppjwa.cn/Article/details/gtssoufyho.html

[Q70] 更新统计信息
来源：http://dali.wangshuangyany.cn/Article/details/gtxuoenrwn.html

ANALYZE TABLE users;
来源：http://dali.redwolf501.top/Article/details/gtnwcgkeyj.html

[Q71] 查看建表语句
来源：http://dali.jiagoushi.top/Article/details/gtgrabfgfm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jinghuilouyu.cn/Article/details/gtmdceyqbf.html

[Q72] 查看索引
来源：http://dali.chenzaomai.com/Article/details/gtjfvrqsry.html

SHOW INDEX FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtonjqacye.html

[Q73] 查看表状态
来源：http://dali.jinqigufen.top/Article/details/gtibenwkmm.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cucudq.cn/Article/details/gtxypzblol.html

[Q74] 强制使用索引
来源：http://dali.meibo888.top/Article/details/gtxozmshac.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yuanzhike.top/Article/details/gtujzarpdm.html

[Q75] 日期格式化
来源：http://dali.dashuyun.cn/Article/details/gtwtayhgkk.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gtesbnkcrl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cdnleiting.top/Article/details/gtytyuysba.html

[Q76] 按天统计
来源：http://dali.yonumen.top/Article/details/gtzowmncsr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhijiandao.cn/Article/details/gtnnnejegk.html

[Q77] 时间加减
来源：http://dali.kuanghao11.cn/Article/details/gtadtzbapy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.dashuyun.cn/Article/details/gtrpfgelsd.html

[Q78] 当前时间
来源：http://dali.0kj1m.cn/Article/details/gtnojiuaid.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinqigufen.top/Article/details/gtzxllzebx.html

[Q79] 字符串拼接
来源：http://dali.hnxiangtu.top/Article/details/gtcczvccky.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.tianlin.xyz/Article/details/gtplvzkxvn.html

[Q80] 字符串截取
来源：http://dali.bjfxy.top/Article/details/gtcfseuqmo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtbxuixncl.html

[Q81] 字符串替换
来源：http://dali.tanke756.top/Article/details/gtvxsjcfgz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtuhajhvcp.html

[Q82] 字符长度与字节长度
来源：http://dali.zdqjudy.top/Article/details/gtwbvidspl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtoihoqgup.html

[Q83] 大小写转换
来源：http://dali.nwbrower.top/Article/details/gtljexqyie.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtbhdtrxai.html

[Q84] 去除首尾空格
来源：http://dali.pycfn.com/Article/details/gtgfmpjorv.html

SELECT TRIM(name) FROM users;
来源：http://dali.birdmap.top/Article/details/gthffilowm.html

[Q85] 数值取整
来源：http://dali.fzhhl.top/Article/details/gtbwfvmdcr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cdnleiting.top/Article/details/gtmkvzjbjj.html

[Q86] 读取 JSON 字段
来源：http://dali.redwolf501.top/Article/details/gtylkftkdd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.chenzaomai.com/Article/details/gtqohyyago.html

[Q87] JSON 字段做条件
来源：http://dali.jqgufenzy.top/Article/details/gtqinqisup.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.zhoulong.xyz/Article/details/gtmykmytdg.html

[Q88] 行转列（条件聚合）
来源：http://dali.yueranfly.top/Article/details/gtcxmbekzm.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shuidangran.top/Article/details/gteznvnhgx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.wangdashe.top/Article/details/gtmrdobndf.html

[Q89] 判断表是否存在
来源：http://dali.aizwys.cn/Article/details/gthlhaesfm.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvlopzllf.html

[Q90] 生成序号列
来源：http://dali.ppjwa.cn/Article/details/gtvwnfpfnw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.fzhhl.top/Article/details/gtzdhngyfs.html

================================================================================
来源：http://dali.aizwys.cn/Article/details/gtyppicohh.html

R. Bash 专题
来源：http://dali.nanxuanxn.top/Article/details/gtwibeodyt.html

================================================================================
来源：http://dali.yj20258.top/Article/details/gtbqpgefyj.html

[R01] shebang 与严格模式
来源：http://dali.andypj.xyz/Article/details/gtkautklum.html

#!/usr/bin/env bash
来源：http://dali.wangdashe.top/Article/details/gttaemarso.html

set -euo pipefail
来源：http://dali.jyoumei.cn/Article/details/gtpjgmdmsu.html

[R02] 变量赋值与使用
来源：http://dali.dashuyun.cn/Article/details/gtxwpjxrpi.html

name="Tom"; echo "$name"
来源：http://dali.jqgufenzy.top/Article/details/gtbhwzlrfl.html

[R03] 只读变量
来源：http://dali.fzhhl.top/Article/details/gtpikodyyy.html

readonly PI=3.14
来源：http://dali.kuanghao11.cn/Article/details/gtgcudfvaa.html

[R04] 位置参数
来源：http://dali.yj20258888.top/Article/details/gtesuwhyng.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shangyingyoupin.top/Article/details/gtmemtcaje.html

[R05] 参数默认值
来源：http://dali.svipenyu.cn/Article/details/gtabmdocvi.html

name="${1:-default}"
来源：http://dali.shzxlz.cn/Article/details/gtzfrhrpde.html

[R06] 判断命令是否存在
来源：http://dali.xuetiantiany.cn/Article/details/gtyrkhiktb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.dashuyun.cn/Article/details/gtqeavgfuf.html

[R07] if 判断文件
来源：http://dali.316326.xyz/Article/details/gtgjzpkusa.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xinyue.icu/Article/details/gtftpjqcnd.html

[R08] 数值比较
来源：http://dali.wangdashe.top/Article/details/gtqgqsjlit.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yangfankeji.com/Article/details/gtznzgvlps.html

[R09] 字符串比较
来源：http://dali.ydzc1.top/Article/details/gtgpktefkf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hnqzz.top/Article/details/gtsjrbsasm.html

[R10] 正则匹配
来源：http://dali.jianghu66.top/Article/details/gtgpqbstzz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzrokbdjg.html

[R11] case 多分支
来源：http://dali.hfpthk.cn/Article/details/gtbnqchuzw.html

case "$1" in
来源：http://dali.xylfe.cn/Article/details/gtddqcmpfh.html

start) echo "启动" ;;
来源：http://dali.birdmap.top/Article/details/gtovbwxcoq.html

stop)  echo "停止" ;;
来源：http://dali.zhoulong.xyz/Article/details/gtklatvqkh.html

*)     echo "未知命令" ;;
来源：http://dali.aizwys.cn/Article/details/gtiegjvfqj.html

esac
来源：http://dali.feifeiyinyue.top/Article/details/gtsmjcwynx.html

[R12] for 遍历文件
来源：http://dali.redwolf501.top/Article/details/gtydcchbpo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yangfankeji.com/Article/details/gtlaakdwbj.html

[R13] for 计数循环
来源：http://dali.daria6918.cn/Article/details/gtxixzhoes.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xziqi.cn/Article/details/gtjvxruknk.html

[R14] C 风格 for
来源：http://dali.pengpengdd.cyou/Article/details/gtwearwlfh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtwfzqdqmj.html

[R15] while 逐行读文件
来源：http://dali.chenzaomai.com/Article/details/gtbbqcjhsn.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hywenlv.cn/Article/details/gtbpsftcfh.html

[R16] until 等待条件
来源：http://dali.smart0.xyz/Article/details/gtvpesyigs.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.shzxlz.cn/Article/details/gtbsibhjfy.html

[R17] 数组定义与取值
来源：http://dali.guannengcc.top/Article/details/gtodygdrfc.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hongshengwenyu.top/Article/details/gtqfzhnkqs.html

[R18] 遍历数组
来源：http://dali.tian-w.cn/Article/details/gtaqkuwywn.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.hnqzz.top/Article/details/gtfvzejrij.html

[R19] 数组长度
来源：http://dali.jinqigfzy.top/Article/details/gtecotpqke.html

echo "${#arr[@]}"
来源：http://dali.hfpthk.cn/Article/details/gttgjaklgw.html

[R20] 关联数组（字典）
来源：http://dali.aizwys.cn/Article/details/gtrnnbmzoq.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.daxiang520.top/Article/details/gtuxhtjybn.html

[R21] 字符串长度
来源：http://dali.c1oappe.top/Article/details/gtkfrrewuk.html

echo "${#s}"
来源：http://dali.quarkkingdee.top/Article/details/gtkejezvcy.html

[R22] 截取子串
来源：http://dali.shuidangran.top/Article/details/gtdipbzwym.html

echo "${s:0:5}"
来源：http://dali.gzhubu.top/Article/details/gtavcjnlic.html

[R23] 字符串替换
来源：http://dali.jiagoushi.top/Article/details/gtmfgmwxte.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.0kj1m.cn/Article/details/gtpsqypycb.html

[R24] 大小写转换
来源：http://dali.shuidangran.top/Article/details/gtynipfyrq.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ybcxt.top/Article/details/gthykcrele.html

[R25] 去后缀 / 去前缀
来源：http://dali.yangfankeji.com/Article/details/gtkpuvvnkq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jianghu66.top/Article/details/gthsxnnbvh.html

[R26] 命令替换
来源：http://dali.dashuyun.cn/Article/details/gtujivetor.html

now=$(date +%F); echo "$now"
来源：http://dali.jianghu66.top/Article/details/gtvkelbppy.html

[R27] 算术展开
来源：http://dali.dianchejie.cn/Article/details/gtcmlswjvc.html

echo $((1 + 2 * 3))
来源：http://dali.hongshengwenyu.top/Article/details/gtmoygiocg.html

[R28] 浮点运算
来源：http://dali.yj20258888.top/Article/details/gtwgvchdqv.html

echo "scale=2; 10/3" | bc
来源：http://dali.yj202588.top/Article/details/gtgdavqmlm.html

[R29] 定义函数
来源：http://dali.yuanzhike.top/Article/details/gtcypdzqkx.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.tian-w.cn/Article/details/gtoshtnmrz.html

[R30] 函数返回状态码
来源：http://dali.zdqjudy.top/Article/details/gttuvcovul.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hongshengwenyu.top/Article/details/gtusvdvyip.html

[R31] 局部变量
来源：http://dali.hfpthk.cn/Article/details/gtkuitbfac.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhijiandao.cn/Article/details/gtfnntjsga.html

[R32] 参数个数校验
来源：http://dali.zhixingplan.top/Article/details/gtsnopkgyj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yj202588.top/Article/details/gtimzergge.html

[R33] 捕获错误并提示行号
来源：http://dali.jinqigufen.top/Article/details/gtryugubec.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hnqzz.top/Article/details/gtokblekwn.html

[R34] 退出时清理
来源：http://dali.9152youxi.cn/Article/details/gtjrasefpv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.iojbl.cn/Article/details/gtswviksjq.html

[R35] 后台执行并等待
来源：http://dali.yuxming.cn/Article/details/gtnbzbtnyc.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gogol.net.cn/Article/details/gthkwbbysq.html

[R36] 并发执行多个任务
来源：http://dali.haohaochexian.top/Article/details/gtkivxlxlb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.hnxiangtu.top/Article/details/gtvacfumad.html

[R37] 把输出赋给变量
来源：http://dali.hfpthk.cn/Article/details/gtknecfhyk.html

files=$(ls -1)
来源：http://dali.yangfankeji.com/Article/details/gtiafzffwf.html

[R38] 管道串联
来源：http://dali.daria6918.cn/Article/details/gtrydyppww.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hnqzz.top/Article/details/gtxdjuwdvy.html

[R39] 重定向标准输出与错误
来源：http://dali.yj20258888.top/Article/details/gtmzavfdon.html

cmd > out.log 2>&1
来源：http://dali.daria6918.cn/Article/details/gtjsvjzcsk.html

[R40] 追加写日志
来源：http://dali.mhx1999.top/Article/details/gtqiyysdyk.html

echo "log" >> out.log
来源：http://dali.sweek.top/Article/details/gtdxhdkara.html

[R41] 丢弃输出
来源：http://dali.feifeiyinyue.top/Article/details/gtzxcaejtu.html

cmd >/dev/null 2>&1
来源：http://dali.jqgufenzy.top/Article/details/gttuombtod.html

[R42] 输入重定向
来源：http://dali.dianchejie.cn/Article/details/gtdjkswtey.html

wc -l < a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtblgofyhr.html

[R43] 按名字查找文件
来源：http://dali.nwbrower.top/Article/details/gtwwrlsvvf.html

find . -name "*.log" -type f
来源：http://dali.hnxiangtu.top/Article/details/gtyqrvzonb.html

[R44] 按修改时间查找
来源：http://dali.jqgufenzy.top/Article/details/gtpcirapyz.html

find . -mtime -7 -type f
来源：http://dali.cdnleiting.top/Article/details/gtmiqfindb.html

[R45] 批量删除
来源：http://dali.chenjidiqi.icu/Article/details/gtfhrzgkzd.html

find . -name "*.tmp" -delete
来源：http://dali.zhijiandao.cn/Article/details/gtqglhjelr.html

[R46] 递归替换文件内容
来源：http://dali.ppjwa.cn/Article/details/gtoegrzjvf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.fengsongda.top/Article/details/gtbrbjuxih.html

[R47] sed 单行替换
来源：http://dali.yj20258.top/Article/details/gtrfxfudia.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yonumen.top/Article/details/gthttlhbyv.html

[R48] awk 取指定列
来源：http://dali.nanxuanxn.top/Article/details/gtdwhqfgjo.html

awk '{print $1, $3}' a.txt
来源：http://dali.gogol.net.cn/Article/details/gtjgvgcxgy.html

[R49] awk 带条件
来源：http://dali.xylfe.cn/Article/details/gtogwmplag.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hnxiangtu.top/Article/details/gtyqpwndhy.html

[R50] awk 求和
来源：http://dali.zhaomingkeji.xyz/Article/details/gtablazfbo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtwrsxndpu.html

[R51] 排序去重取前几
来源：http://dali.jyoumei.cn/Article/details/gtsbaaqcbi.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yuanzhike.top/Article/details/gtfitisbjp.html

[R52] 统计行数
来源：http://dali.sysykeji.top/Article/details/gtfwycxvqi.html

wc -l a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtsghfmnuo.html

[R53] 查看文件头与实时尾
来源：http://dali.316326.xyz/Article/details/gtktstgefe.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.redwolf501.top/Article/details/gtvfnmzuhq.html

[R54] 比较两个文件
来源：http://dali.gaohongyu789.top/Article/details/gtqjsqzgkm.html

diff a.txt b.txt
来源：http://dali.gotoacloud.top/Article/details/gtpifquylb.html

[R55] 压缩与解压
来源：http://dali.yueranfly.top/Article/details/gtuguiolya.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.sweek.top/Article/details/gtsskeexmr.html

[R56] 远程拷贝
来源：http://dali.kuanghao11.cn/Article/details/gtgilqmrrw.html

scp file user@host:/path/
来源：http://dali.jianghu66.top/Article/details/gtlkidmodx.html

[R57] 远程执行命令
来源：http://dali.jiagoushi.top/Article/details/gtwvyjonhx.html

ssh user@host 'uptime'
来源：http://dali.daxiang520.top/Article/details/gtmpgrrjxz.html

[R58] 下载文件
来源：http://dali.feifeiyinyue.top/Article/details/gtknhdxbea.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhongyouzk.top/Article/details/gtuuaxivln.html

[R59] 发 POST JSON
来源：http://dali.shuidangran.top/Article/details/gtlogmvfuy.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhongyouzk.top/Article/details/gtdrclroco.html

[R60] 只看 HTTP 状态码
来源：http://dali.haohaochexian.top/Article/details/gtqmjhtwsz.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhijiandao.cn/Article/details/gttthlvhsx.html

[R61] 磁盘占用
来源：http://dali.chenzaomai.com/Article/details/gtwhckbwhq.html

df -h;  du -sh *
来源：http://dali.kuanghao11.cn/Article/details/gtvvycpnbe.html

[R62] 找最占空间的文件
来源：http://dali.bjfxy.top/Article/details/gtieicasum.html

du -ah . | sort -rh | head -10
来源：http://dali.shangyingyoupin.top/Article/details/gtwmobguhg.html

[R63] 内存与进程
来源：http://dali.tanke756.top/Article/details/gtrvkhwqxc.html

free -h;  ps aux | grep nginx
来源：http://dali.hysaishi.cn/Article/details/gtqgeiuiqu.html

[R64] 结束进程
来源：http://dali.jlsjyb.cn/Article/details/gtmtknuigm.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sysykeji.top/Article/details/gtsqbsmwaw.html

[R65] 查看端口占用
来源：http://dali.fzhhl.top/Article/details/gtnkotsijj.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.birdmap.top/Article/details/gtzzkeqxvu.html

[R66] 定时任务
来源：http://dali.pengpengdd.cyou/Article/details/gtjanwrcxh.html

crontab -e;  crontab -l
来源：http://dali.cqqwz.cn/Article/details/gtsbrmynum.html

[R67] 生成随机十六进制串
来源：http://dali.dashuyun.cn/Article/details/gtwavxctcx.html


<!-- 参考信息 -->