代发 wailian999

SELECT * FROM users;
来源：http://dali.aizwys.cn/Article/details/gtubscnszz.html

[Q16] 查询指定列
来源：http://dali.daria6918.cn/Article/details/gtccwehmpv.html

SELECT id, name FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtswydfqjj.html

[Q17] 条件查询
来源：http://dali.andypj.xyz/Article/details/gttuctokcb.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.tian-w.cn/Article/details/gtfqbgqnpr.html

[Q18] 模糊匹配
来源：http://dali.gotoacloud.top/Article/details/gtytgniqbm.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yuxming.cn/Article/details/gtpwyyorqi.html

[Q19] 范围查询
来源：http://dali.havefunace.top/Article/details/gtmmdsxiqk.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.jianghu66.top/Article/details/gtebgntwtz.html

[Q20] IN 列表
来源：http://dali.nanxinkj.top/Article/details/gtjszwxjfm.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.gaohongyu789.top/Article/details/gtmsrvrsbp.html

[Q21] 空值判断
来源：http://dali.shzxlz.cn/Article/details/gtgbioxior.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.svipenyu.cn/Article/details/gtahnxzeok.html

[Q22] 排序
来源：http://dali.wangshuangyany.cn/Article/details/gtmziaqqet.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.iojbl.cn/Article/details/gtjqpjpdww.html

[Q23] 分页
来源：http://dali.guowangkeji.top/Article/details/gtdjhedexh.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.zhongyouzk.top/Article/details/gtxvweewle.html

[Q24] 去重
来源：http://dali.smart0.xyz/Article/details/gtwjobpiiw.html

SELECT DISTINCT city FROM users;
来源：http://dali.zhixingplan.top/Article/details/gthwrlrhhi.html

[Q25] 只取前 N 条
来源：http://dali.sysykeji.top/Article/details/gtxugalyiz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.vqdsnc.cn/Article/details/gtqspnprte.html

[Q26] 计数
来源：http://dali.ivvv.top/Article/details/gtarwhqwtk.html

SELECT COUNT(*) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtpuviytkj.html

[Q27] 条件计数
来源：http://dali.birdmap.top/Article/details/gtzvpbacza.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtgknjivdg.html

[Q28] 求和与平均
来源：http://dali.316326.xyz/Article/details/gtqswmbxap.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtewzshtfk.html

[Q29] 最大最小值
来源：http://dali.jyoumei.cn/Article/details/gtnwdzfdfc.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtlbvlddyc.html

[Q30] 分组统计
来源：http://dali.pengpengdd.cyou/Article/details/gtosbwtave.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jinqigfzy.top/Article/details/gtutssziba.html

[Q31] 分组后过滤
来源：http://dali.zhijiandao.cn/Article/details/gtnzhtvxwg.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.zhoulong.xyz/Article/details/gtjmizjxrb.html

[Q32] 分组拼接字符串
来源：http://dali.cashguo.top/Article/details/gtbmpiotrj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.sweek.top/Article/details/gteyjtoopl.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.tian-w.cn/Article/details/gtefqvvifa.html

[Q33] 多列分组
来源：http://dali.ydzc1.top/Article/details/gtxzoyfldc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.0kj1m.cn/Article/details/gtunyhksgn.html

[Q34] 每组取第一条
来源：http://dali.haohaochexian.top/Article/details/gtizkfwhro.html

SELECT * FROM (
来源：http://dali.shangyingyoupin.top/Article/details/gthgnjerhm.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jinqigufen.top/Article/details/gtfourkhgq.html

) t WHERE rn = 1;
来源：http://dali.nanxinkj.top/Article/details/gtqgwzlrbf.html

[Q35] 内连接
来源：http://dali.0kj1m.cn/Article/details/gtirsarwte.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gogol.net.cn/Article/details/gtfrnaeijx.html

[Q36] 左连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtibwdbgwh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.haohaochexian.top/Article/details/gtnthyitfp.html

[Q37] 右连接
来源：http://dali.snrcjt.cn/Article/details/gthnyekqyb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhixingplan.top/Article/details/gtjhgsoweq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hammf.cn/Article/details/gtkjdhonpd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gogol.net.cn/Article/details/gtdbqtdisf.html

[Q39] 自连接（查上下级）
来源：http://dali.cucudq.cn/Article/details/gtlahjnunc.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yj20258.top/Article/details/gtovuwniob.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthbsojkmo.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.fzhhl.top/Article/details/gteedwrlvf.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hammf.cn/Article/details/gtijsxigxu.html

[Q41] 多表连接
来源：http://dali.c1oappe.top/Article/details/gtpyownqhw.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jqgufenzy.top/Article/details/gtlvbsolsr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhoulong.xyz/Article/details/gtbhmmatbx.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.meibo888.top/Article/details/gtmkuwjpuv.html

[Q42] 连接条件附加过滤
来源：http://dali.tian-w.cn/Article/details/gtfmzflzpm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sufxvd.cn/Article/details/gtuluxyric.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.nanxinkj.top/Article/details/gtiavcddre.html

[Q43] 标量子查询
来源：http://dali.jiagoushi.top/Article/details/gtrolypqbn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ydzc1.top/Article/details/gtvqicifpm.html

[Q44] IN 子查询
来源：http://dali.9152youxi.cn/Article/details/gtsyshpzij.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yuanzhike.top/Article/details/gtaucgomki.html

[Q45] EXISTS 判断存在
来源：http://dali.cucudq.cn/Article/details/gtnfnscegf.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258.top/Article/details/gtipwdlsxk.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.shangyingyoupin.top/Article/details/gtqesysjyh.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cucudq.cn/Article/details/gtvdukmvix.html

[Q47] 与平均值比较
来源：http://dali.hammf.cn/Article/details/gtinpyvlqt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jqgufenzy.top/Article/details/gtpufrymyf.html

[Q48] CTE 公用表表达式
来源：http://dali.9152youxi.cn/Article/details/gtntwqjedz.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.meibo888.top/Article/details/gtusrntldp.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gzhubu.top/Article/details/gtogzvzrhr.html

[Q49] 更新单行
来源：http://dali.yanxiufei.cn/Article/details/gtkhgyrasa.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinqigufen.top/Article/details/gthwcktzet.html

[Q50] 批量更新
来源：http://dali.chenjidiqi.icu/Article/details/gtlyveqddg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinqigufen.top/Article/details/gtipugsvdy.html

[Q51] 用子查询更新
来源：http://dali.yueranfly.top/Article/details/gtdefzberz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jqgfzy.top/Article/details/gtjaiypdvi.html

[Q52] 删除指定行
来源：http://dali.feifeiyinyue.top/Article/details/gtorvbvgdy.html

DELETE FROM users WHERE id = 10;
来源：http://dali.tanke756.top/Article/details/gtqmabsuxd.html

[Q53] 按条件删除
来源：http://dali.kuanghao11.cn/Article/details/gtugjwahjc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.wangshuangyany.cn/Article/details/gtmrvmngyw.html

[Q54] 清空表
来源：http://dali.zhijiandao.cn/Article/details/gtkxbbhatc.html

TRUNCATE TABLE logs;
来源：http://dali.dianchejie.cn/Article/details/gtqdgjjpvt.html

[Q55] 排名（并列占位）
来源：http://dali.daria6918.cn/Article/details/gtgscusiqa.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.smart0.xyz/Article/details/gtiafakbeu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhongyouzk.top/Article/details/gtnpxxklfy.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jqgfzy.top/Article/details/gtsycmvqxy.html

[Q57] 行号
来源：http://dali.zhijiandao.cn/Article/details/gtpvxbpzwd.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtdfuchofj.html

[Q58] 累计求和
来源：http://dali.redwolf501.top/Article/details/gttuetxgkq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtunrblior.html

[Q59] 分组内累计
来源：http://dali.fzhhl.top/Article/details/gthgyttdlc.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.meibo888.top/Article/details/gthismvzyd.html

[Q60] 取上一行 / 下一行
来源：http://dali.guannengcc.top/Article/details/gtbfhkmbnn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.jinqigufen.top/Article/details/gtemrzjftb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.ydzc1.top/Article/details/gtzankggpk.html

[Q61] 移动平均
来源：http://dali.chenjidiqi.icu/Article/details/gtqjleeolr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.chenzaomai.com/Article/details/gtnkdvwyjb.html

[Q62] 分组占比
来源：http://dali.gaohongyu789.top/Article/details/gtlajpgagu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.havefunace.top/Article/details/gtirodivdv.html

[Q63] 开启事务
来源：http://dali.9152youxi.cn/Article/details/gtbqimarze.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.wangdashe.top/Article/details/gtajdltmxo.html

[Q64] 提交事务
来源：http://dali.ybcxt.top/Article/details/gtjkzqcqsk.html

COMMIT;
来源：http://dali.xziqi.cn/Article/details/gtptvwesca.html

[Q65] 回滚事务
来源：http://dali.nanxinkj.top/Article/details/gtdsbivtcf.html

ROLLBACK;
来源：http://dali.shzxlz.cn/Article/details/gtxtskyuff.html

[Q66] 行锁查询
来源：http://dali.cashguo.top/Article/details/gtigzggzlt.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.havefunace.top/Article/details/gtikoxcjzp.html

[Q67] 设置隔离级别
来源：http://dali.yueranfly.top/Article/details/gttalymgqj.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.daria6918.cn/Article/details/gtviortjug.html

[Q68] 保存点
来源：http://dali.hongshengwenyu.top/Article/details/gteuquslkc.html

SAVEPOINT sp1;
来源：http://dali.ehwqpu.com/Article/details/gtobfrzrdy.html

ROLLBACK TO sp1;
来源：http://dali.hnxiangtu.top/Article/details/gtuprsfkqm.html

[Q69] 查看执行计划
来源：http://dali.ivvv.top/Article/details/gtgylrefsr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.svipenyu.cn/Article/details/gtxrjzoqzz.html

[Q70] 更新统计信息
来源：http://dali.9152youxi.cn/Article/details/gtemrlgfgp.html

ANALYZE TABLE users;
来源：http://dali.smart0.xyz/Article/details/gtvujmyvli.html

[Q71] 查看建表语句
来源：http://dali.iojbl.cn/Article/details/gtesfcbzyp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.fzhhl.top/Article/details/gtfraxlvhk.html

[Q72] 查看索引
来源：http://dali.316326.xyz/Article/details/gtjwizifix.html

SHOW INDEX FROM users;
来源：http://dali.ydzc1.top/Article/details/gtbivejvre.html

[Q73] 查看表状态
来源：http://dali.yueranfly.top/Article/details/gtvubpmecx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ehwqpu.com/Article/details/gtpvkrrutb.html

[Q74] 强制使用索引
来源：http://dali.zhengqikj.top/Article/details/gtkuhnzuas.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jinqigufen.top/Article/details/gtlnjerxmu.html

[Q75] 日期格式化
来源：http://dali.guannengcc.top/Article/details/gtaglulzeq.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtiznquvnl.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shanyushiyangtech.top/Article/details/gtjkoakffj.html

[Q76] 按天统计
来源：http://dali.yongpay.top/Article/details/gtqmyfuqqg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.dashuyun.cn/Article/details/gttchdnckp.html

[Q77] 时间加减
来源：http://dali.nwbrower.top/Article/details/gthwwixnmo.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.smart0.xyz/Article/details/gtkrjkgccu.html

[Q78] 当前时间
来源：http://dali.jianghu66.top/Article/details/gtrxtdwcbu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yanxiufei.cn/Article/details/gtcjykvgpw.html

[Q79] 字符串拼接
来源：http://dali.chenjidiqi.icu/Article/details/gtraxdwttp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.andypj.xyz/Article/details/gtcxmbaqbe.html

[Q80] 字符串截取
来源：http://dali.zhixingplan.top/Article/details/gtaenhevbi.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.sweek.top/Article/details/gtunqsaaao.html

[Q81] 字符串替换
来源：http://dali.gogol.net.cn/Article/details/gttdxbdbaf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.pycfn.com/Article/details/gtylaemmym.html

[Q82] 字符长度与字节长度
来源：http://dali.nanxuanxn.top/Article/details/gtvwysfjul.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtbxulkmxu.html

[Q83] 大小写转换
来源：http://dali.jianghu66.top/Article/details/gtpyjffuyw.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtepjajqjk.html

[Q84] 去除首尾空格
来源：http://dali.cashguo.top/Article/details/gtczaftwnq.html

SELECT TRIM(name) FROM users;
来源：http://dali.yj20258888.top/Article/details/gtkmwbmlgn.html

[Q85] 数值取整
来源：http://dali.gzhubu.top/Article/details/gtwmocuobt.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.ppjwa.cn/Article/details/gtkiybzoik.html

[Q86] 读取 JSON 字段
来源：http://dali.zycfv.cn/Article/details/gtgppnfcua.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.fzhhl.top/Article/details/gtsuvaklbc.html

[Q87] JSON 字段做条件
来源：http://dali.iojbl.cn/Article/details/gthvjhhlax.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.daxiang520.top/Article/details/gtjdipjkel.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtykvjoyxg.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.fzhhl.top/Article/details/gttiwhslmi.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ehwqpu.com/Article/details/gthxnmovdi.html

[Q89] 判断表是否存在
来源：http://dali.jiagoushi.top/Article/details/gtylpnlmtj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.feifeiyinyue.top/Article/details/gtvbfjevff.html

[Q90] 生成序号列
来源：http://dali.yanxiufei.cn/Article/details/gttvshwrwm.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hywenlv.cn/Article/details/gtaletbzsh.html

================================================================================
来源：http://dali.pengpengdd.cyou/Article/details/gtqchvlqco.html

R. Bash 专题
来源：http://dali.vqdsnc.cn/Article/details/gthxmprhdt.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtfppznxzg.html

[R01] shebang 与严格模式
来源：http://dali.xinyue.icu/Article/details/gtvmevdyra.html

#!/usr/bin/env bash
来源：http://dali.jianghu66.top/Article/details/gtlrbrxczm.html

set -euo pipefail
来源：http://dali.daria6918.cn/Article/details/gtdgwpfbsn.html

[R02] 变量赋值与使用
来源：http://dali.jqgfzy.top/Article/details/gtsipspjgv.html

name="Tom"; echo "$name"
来源：http://dali.sxryk.cn/Article/details/gtwthlhjkz.html

[R03] 只读变量
来源：http://dali.shanyushiyangtech.top/Article/details/gttmojifwu.html

readonly PI=3.14
来源：http://dali.mhx1999.top/Article/details/gtqolpxlkv.html

[R04] 位置参数
来源：http://dali.yanxiufei.cn/Article/details/gtqqtrheiy.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.chenjidiqi.icu/Article/details/gtazauajiz.html

[R05] 参数默认值
来源：http://dali.wangshuangyany.cn/Article/details/gtrbceqrmk.html

name="${1:-default}"
来源：http://dali.gogol.net.cn/Article/details/gtsjbdvmcr.html

[R06] 判断命令是否存在
来源：http://dali.xinyue.icu/Article/details/gtbnkqimhi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hnxiangtu.top/Article/details/gtcgxghhhe.html

[R07] if 判断文件
来源：http://dali.guannengcc.top/Article/details/gtgkbkxnhk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xziqi.cn/Article/details/gtvukcqtfh.html

[R08] 数值比较
来源：http://dali.xuetiantiany.cn/Article/details/gtzzyoazoy.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yvedp.cn/Article/details/gtygxcdayd.html

[R09] 字符串比较
来源：http://dali.chenlongwang.top/Article/details/gtctsutovn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jiagoushi.top/Article/details/gtillwhxpb.html

[R10] 正则匹配
来源：http://dali.gzhubu.top/Article/details/gtsoxoqlvr.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.ivvv.top/Article/details/gtzqbptjto.html

[R11] case 多分支
来源：http://dali.zhijiandao.cn/Article/details/gtjdawwcfg.html

case "$1" in
来源：http://dali.pengpengdd.cyou/Article/details/gtlgqhnmak.html

start) echo "启动" ;;
来源：http://dali.chenlongwang.top/Article/details/gtkpgsjbyr.html

stop)  echo "停止" ;;
来源：http://dali.tian-w.cn/Article/details/gtnibukbxx.html

*)     echo "未知命令" ;;
来源：http://dali.chenzaomai.com/Article/details/gteiklkles.html

esac
来源：http://dali.nanxuanxn.top/Article/details/gtpyxvdhye.html

[R12] for 遍历文件
来源：http://dali.cdnleiting.top/Article/details/gttspvgziw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xuanzx.com/Article/details/gtxcmfxgbd.html

[R13] for 计数循环
来源：http://dali.ydzc1.top/Article/details/gtgktwssuh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjetothze.html

[R14] C 风格 for
来源：http://dali.ydzc1.top/Article/details/gtgnmstprd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtfvupaijp.html

[R15] while 逐行读文件
来源：http://dali.fzhhl.top/Article/details/gtijqfpnne.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.9152youxi.cn/Article/details/gtekcmqhwy.html

[R16] until 等待条件
来源：http://dali.yueranfly.top/Article/details/gtkytluonu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yvedp.cn/Article/details/gtqyniwxxw.html

[R17] 数组定义与取值
来源：http://dali.kuanghao11.cn/Article/details/gtmyprqkls.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xuanzx.com/Article/details/gtmiyshoea.html

[R18] 遍历数组
来源：http://dali.tianlin.xyz/Article/details/gtwfhuiuvh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shzxlz.cn/Article/details/gtfvdryimc.html

[R19] 数组长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtbyjzdbxr.html

echo "${#arr[@]}"
来源：http://dali.sysykeji.top/Article/details/gtzncexxqu.html

[R20] 关联数组（字典）
来源：http://dali.jlsjyb.cn/Article/details/gtrevtgtpj.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yuanzhike.top/Article/details/gttoszlgzv.html

[R21] 字符串长度
来源：http://dali.zhongyouzk.top/Article/details/gtgfzfjuxl.html

echo "${#s}"
来源：http://dali.aibaodan.cn/Article/details/gtyzqvraie.html

[R22] 截取子串
来源：http://dali.fengsongda.top/Article/details/gtqjeogwtq.html

echo "${s:0:5}"
来源：http://dali.jlsjyb.cn/Article/details/gtvsxyhbxt.html

[R23] 字符串替换
来源：http://dali.ydzc1.top/Article/details/gtqamqffkt.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.sysykeji.top/Article/details/gtiwknstoe.html

[R24] 大小写转换
来源：http://dali.yj202588.top/Article/details/gtkxzaxqfz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.meibo888.top/Article/details/gtblzhtemw.html

[R25] 去后缀 / 去前缀
来源：http://dali.guannengcc.top/Article/details/gtkhpxlcwo.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yuxming.cn/Article/details/gtcmvmyeep.html

[R26] 命令替换
来源：http://dali.zhijiandao.cn/Article/details/gtjrgkdssg.html

now=$(date +%F); echo "$now"
来源：http://dali.yongpay.top/Article/details/gtnvwwrnce.html

[R27] 算术展开
来源：http://dali.haohaochexian.top/Article/details/gtpnotvikj.html

echo $((1 + 2 * 3))
来源：http://dali.feifeiyinyue.top/Article/details/gtzyakpqbv.html

[R28] 浮点运算
来源：http://dali.shzxlz.cn/Article/details/gtoemaqxmk.html

echo "scale=2; 10/3" | bc
来源：http://dali.smart0.xyz/Article/details/gtoiwjwidd.html

[R29] 定义函数
来源：http://dali.gogol.net.cn/Article/details/gterwdqjgu.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yanxiufei.cn/Article/details/gtzukjifma.html

[R30] 函数返回状态码
来源：http://dali.jinyuanbaomall.cn/Article/details/gtcshvgwvz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cheryme.top/Article/details/gtdfigcpix.html

[R31] 局部变量
来源：http://dali.shangyingyoupin.top/Article/details/gtjlcbfxdx.html

f() { local x=1; echo "$x"; }
来源：http://dali.ivvv.top/Article/details/gtctvzqsvl.html

[R32] 参数个数校验
来源：http://dali.chenlongwang.top/Article/details/gtrfuauomb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.guannengcc.top/Article/details/gtvawssbsj.html

[R33] 捕获错误并提示行号
来源：http://dali.ydzc1.top/Article/details/gtgypwygud.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.andypj.xyz/Article/details/gtzqojpqip.html

[R34] 退出时清理
来源：http://dali.chenjidiqi.icu/Article/details/gtjckccaua.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenlongwang.top/Article/details/gtynmgvkcx.html

[R35] 后台执行并等待
来源：http://dali.gaohongyu789.top/Article/details/gtjashnhdp.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yongpay.top/Article/details/gtbucdjduf.html

[R36] 并发执行多个任务
来源：http://dali.pycfn.com/Article/details/gtggwvwvqq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.bjfxy.top/Article/details/gtvgoxtfth.html

[R37] 把输出赋给变量
来源：http://dali.chenlongwang.top/Article/details/gtjucelepx.html

files=$(ls -1)
来源：http://dali.wangshuangyany.cn/Article/details/gtarxmdzqc.html

[R38] 管道串联
来源：http://dali.yongpay.top/Article/details/gtmbvrpzso.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hammf.cn/Article/details/gtfmjbmjnh.html

[R39] 重定向标准输出与错误
来源：http://dali.hnxiangtu.top/Article/details/gtqfvimehv.html

cmd > out.log 2>&1
来源：http://dali.havefunace.top/Article/details/gtvitkkjdv.html

[R40] 追加写日志
来源：http://dali.316326.xyz/Article/details/gtqcdbdihg.html

echo "log" >> out.log
来源：http://dali.hysaishi.cn/Article/details/gtrtagtidj.html

[R41] 丢弃输出
来源：http://dali.ehwqpu.com/Article/details/gtlohbeqdq.html

cmd >/dev/null 2>&1
来源：http://dali.nanxinkj.top/Article/details/gtbntratpg.html

[R42] 输入重定向
来源：http://dali.chenjidiqi.icu/Article/details/gtzkgqhmyw.html

wc -l < a.txt
来源：http://dali.chenlongwang.top/Article/details/gthrrtykgr.html

[R43] 按名字查找文件
来源：http://dali.zhixingplan.top/Article/details/gtxuanelwe.html

find . -name "*.log" -type f
来源：http://dali.0kj1m.cn/Article/details/gtvcrjuchm.html

[R44] 按修改时间查找
来源：http://dali.hnxiangtu.top/Article/details/gtymzeaaun.html

find . -mtime -7 -type f
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjzyxgwvr.html

[R45] 批量删除
来源：http://dali.jinghuilouyu.cn/Article/details/gtsifcbtkb.html

find . -name "*.tmp" -delete
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvesuduax.html

[R46] 递归替换文件内容
来源：http://dali.pengpengdd.cyou/Article/details/gthwqxtpzl.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjiuljpai.html

[R47] sed 单行替换
来源：http://dali.hongshengwenyu.top/Article/details/gtokpzkfqq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yanxiufei.cn/Article/details/gtgkqltjeg.html

[R48] awk 取指定列
来源：http://dali.bjfxy.top/Article/details/gtrmqlcutf.html

awk '{print $1, $3}' a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtjqstuoej.html

[R49] awk 带条件
来源：http://dali.jlsjyb.cn/Article/details/gtlwtvhcuj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jianghu66.top/Article/details/gttztoszab.html

[R50] awk 求和
来源：http://dali.snrcjt.cn/Article/details/gturbwrcyk.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.aizwys.cn/Article/details/gtmvuhmevn.html

[R51] 排序去重取前几
来源：http://dali.tanke756.top/Article/details/gtcecdugoj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.mhx1999.top/Article/details/gtilbkaogz.html

[R52] 统计行数
来源：http://dali.shzxlz.cn/Article/details/gtxvqnygpx.html

wc -l a.txt
来源：http://dali.jqgufenzy.top/Article/details/gttdxukxob.html

[R53] 查看文件头与实时尾
来源：http://dali.hammf.cn/Article/details/gtvryenyvb.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yvedp.cn/Article/details/gtziroxcrm.html

[R54] 比较两个文件
来源：http://dali.zhoulong.xyz/Article/details/gtendcklaj.html

diff a.txt b.txt
来源：http://dali.yongpay.top/Article/details/gtelrognjp.html

[R55] 压缩与解压
来源：http://dali.yongpay.top/Article/details/gtltmitosw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.pengpengdd.cyou/Article/details/gtocnzwltg.html

[R56] 远程拷贝
来源：http://dali.svipenyu.cn/Article/details/gtpynfqctj.html

scp file user@host:/path/
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgepntmvj.html

[R57] 远程执行命令
来源：http://dali.hammf.cn/Article/details/gtlqrigvib.html

ssh user@host 'uptime'
来源：http://dali.quarkkingdee.top/Article/details/gtptabwwii.html

[R58] 下载文件
来源：http://dali.ybcxt.top/Article/details/gtedhllfyt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhongyouzk.top/Article/details/gtkbihjxue.html

[R59] 发 POST JSON
来源：http://dali.jqgfzy.top/Article/details/gtenhlpety.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlfjqfoqa.html

[R60] 只看 HTTP 状态码
来源：http://dali.cdnleiting.top/Article/details/gtnyszblrn.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.birdmap.top/Article/details/gtzlvwrhqf.html

[R61] 磁盘占用
来源：http://dali.ivvv.top/Article/details/gtujdrrael.html

df -h;  du -sh *
来源：http://dali.pengpengdd.cyou/Article/details/gtjriigixq.html

[R62] 找最占空间的文件
来源：http://dali.ydzc1.top/Article/details/gtyvuiaujq.html

du -ah . | sort -rh | head -10
来源：http://dali.hywenlv.cn/Article/details/gtqhprzeyo.html

[R63] 内存与进程
来源：http://dali.chenzaomai.com/Article/details/gtnruysblc.html

free -h;  ps aux | grep nginx
来源：http://dali.xinyue.icu/Article/details/gtdbxyrduo.html

[R64] 结束进程
来源：http://dali.yueranfly.top/Article/details/gtqnlaugwf.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkjusizew.html

[R65] 查看端口占用
来源：http://dali.dashuyun.cn/Article/details/gtcbtqdqts.html


<!-- 参考信息 -->