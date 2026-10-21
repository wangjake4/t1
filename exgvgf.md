代发 wailian999

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.zycfv.cn/Article/details/gtiulguyyc.html

[Q18] 模糊匹配
来源：http://dali.yj202588.top/Article/details/gtgrivkblc.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.yangfankeji.com/Article/details/gtzdhgiwsr.html

[Q19] 范围查询
来源：http://dali.316326.xyz/Article/details/gtiahmecku.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.tanke756.top/Article/details/gtxtuuznxm.html

[Q20] IN 列表
来源：http://dali.fzhhl.top/Article/details/gtdaibieaw.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.shanyushiyangtech.top/Article/details/gtrodhwakm.html

[Q21] 空值判断
来源：http://dali.hysaishi.cn/Article/details/gtnqiwhgco.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfnkmeeux.html

[Q22] 排序
来源：http://dali.gotoacloud.top/Article/details/gtoyhnmpws.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.meibo888.top/Article/details/gtfnzjzfat.html

[Q23] 分页
来源：http://dali.ppjwa.cn/Article/details/gtausmnvho.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jiagoushi.top/Article/details/gtqaopjice.html

[Q24] 去重
来源：http://dali.pengpengdd.cyou/Article/details/gtfaavevwi.html

SELECT DISTINCT city FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtzcbjjqit.html

[Q25] 只取前 N 条
来源：http://dali.bjfxy.top/Article/details/gtpxivasdv.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.dashuyun.cn/Article/details/gtqtstxglh.html

[Q26] 计数
来源：http://dali.jinqigfzy.top/Article/details/gtihdtzwco.html

SELECT COUNT(*) FROM users;
来源：http://dali.shuidangran.top/Article/details/gttijzhyxu.html

[Q27] 条件计数
来源：http://dali.jiagoushi.top/Article/details/gtivbgrzye.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yueranfly.top/Article/details/gtxjokinqz.html

[Q28] 求和与平均
来源：http://dali.zhoulong.xyz/Article/details/gtxxoqxkxj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.daria6918.cn/Article/details/gtqkwwzmmc.html

[Q29] 最大最小值
来源：http://dali.jinqigfzy.top/Article/details/gtczbcypej.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yuxming.cn/Article/details/gtvuqpswik.html

[Q30] 分组统计
来源：http://dali.andypj.xyz/Article/details/gtwgnfwluw.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jinqigufen.top/Article/details/gtzfysxqoa.html

[Q31] 分组后过滤
来源：http://dali.cucudq.cn/Article/details/gtgkebraej.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.wangdashe.top/Article/details/gtawfazdzm.html

[Q32] 分组拼接字符串
来源：http://dali.xuanzx.com/Article/details/gtcegbrtnt.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.dashuyun.cn/Article/details/gtveymgxbs.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.redwolf501.top/Article/details/gtdjaqwhxi.html

[Q33] 多列分组
来源：http://dali.shanyushiyangtech.top/Article/details/gtnalmxtfm.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.nwbrower.top/Article/details/gtqvdzqhfb.html

[Q34] 每组取第一条
来源：http://dali.hywenlv.cn/Article/details/gtepcifpsj.html

SELECT * FROM (
来源：http://dali.cucudq.cn/Article/details/gtrazremfh.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.guowangkeji.top/Article/details/gtzbebeakv.html

) t WHERE rn = 1;
来源：http://dali.zhixingplan.top/Article/details/gtpixbuxcv.html

[Q35] 内连接
来源：http://dali.gotoacloud.top/Article/details/gtsihaqbac.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.andypj.xyz/Article/details/gtfjazvguj.html

[Q36] 左连接
来源：http://dali.9152youxi.cn/Article/details/gtrvipdcrr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhixingplan.top/Article/details/gtpsvtajgf.html

[Q37] 右连接
来源：http://dali.aizwys.cn/Article/details/gtnimhuhcr.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.jqgfzy.top/Article/details/gtjppgspgu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.wangdashe.top/Article/details/gtjzdmbdwf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.fengsongda.top/Article/details/gtpnkpmhzk.html

[Q39] 自连接（查上下级）
来源：http://dali.aizwys.cn/Article/details/gtbcruxdfn.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhongyouzk.top/Article/details/gtsghyrwkv.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.vqdsnc.cn/Article/details/gtnoavfaai.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.pengpengdd.cyou/Article/details/gtdsfbimdw.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cucudq.cn/Article/details/gtfwwgffsa.html

[Q41] 多表连接
来源：http://dali.jqgufenzy.top/Article/details/gtsqzijwbd.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.sufxvd.cn/Article/details/gtxwakrots.html

JOIN users u ON u.id = o.user_id
来源：http://dali.nwbrower.top/Article/details/gtoeekbnfk.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.hnqzz.top/Article/details/gtqwhyqxpg.html

[Q42] 连接条件附加过滤
来源：http://dali.yuxming.cn/Article/details/gtdozuuwbg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.kuanghao11.cn/Article/details/gtuhajnjsx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.hfpthk.cn/Article/details/gtsceeyvpp.html

[Q43] 标量子查询
来源：http://dali.meibo888.top/Article/details/gtktkzhowf.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cucudq.cn/Article/details/gtngyysgbp.html

[Q44] IN 子查询
来源：http://dali.meibo888.top/Article/details/gtpjdanzfa.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sysykeji.top/Article/details/gtpqqfjyfa.html

[Q45] EXISTS 判断存在
来源：http://dali.feifeiyinyue.top/Article/details/gtmrhklfbm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.fzhhl.top/Article/details/gtyisvrzcb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.sufxvd.cn/Article/details/gtyqnjcebj.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aibaodan.cn/Article/details/gtmzoxclex.html

[Q47] 与平均值比较
来源：http://dali.daxiang520.top/Article/details/gtkakzqxqq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cqqwz.cn/Article/details/gtsrmbgnzg.html

[Q48] CTE 公用表表达式
来源：http://dali.jinqigufen.top/Article/details/gtyvxjqnwu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.aibaodan.cn/Article/details/gtjhocgwfd.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hfpthk.cn/Article/details/gtyaxoysfs.html

[Q49] 更新单行
来源：http://dali.gogol.net.cn/Article/details/gtpejahylv.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yangfankeji.com/Article/details/gtqszzgwgm.html

[Q50] 批量更新
来源：http://dali.hongshengwenyu.top/Article/details/gtjvehnopi.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zycfv.cn/Article/details/gtpwxyrzpt.html

[Q51] 用子查询更新
来源：http://dali.xuetiantiany.cn/Article/details/gteqmvyyti.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hysaishi.cn/Article/details/gtsukjafsv.html

[Q52] 删除指定行
来源：http://dali.316326.xyz/Article/details/gtaddlfgay.html

DELETE FROM users WHERE id = 10;
来源：http://dali.ppjwa.cn/Article/details/gtowlktdzp.html

[Q53] 按条件删除
来源：http://dali.sweek.top/Article/details/gtyxpdqhbw.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shanyushiyangtech.top/Article/details/gtgtemmrte.html

[Q54] 清空表
来源：http://dali.jqgfzy.top/Article/details/gtkeelwaiz.html

TRUNCATE TABLE logs;
来源：http://dali.xinyue.icu/Article/details/gtegwwkbtn.html

[Q55] 排名（并列占位）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbfrbdqqn.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jianghu66.top/Article/details/gtolfuewos.html

[Q56] 密集排名（并列不占位）
来源：http://dali.snrcjt.cn/Article/details/gtdcoridvq.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.guannengcc.top/Article/details/gtkevjiyvg.html

[Q57] 行号
来源：http://dali.ydzc1.top/Article/details/gtxiehjaxe.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ivvv.top/Article/details/gtuvptccci.html

[Q58] 累计求和
来源：http://dali.jlsjyb.cn/Article/details/gtlulbumic.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtxdrptbvt.html

[Q59] 分组内累计
来源：http://dali.mhx1999.top/Article/details/gtzdkkfiog.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zycfv.cn/Article/details/gtonchkjxg.html

[Q60] 取上一行 / 下一行
来源：http://dali.pycfn.com/Article/details/gtkqtgptfa.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yj20258.top/Article/details/gtiimexsnb.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtsrsmtktn.html

[Q61] 移动平均
来源：http://dali.316326.xyz/Article/details/gtoohtdsim.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtrpgyenbb.html

[Q62] 分组占比
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrlryjvvd.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hnxiangtu.top/Article/details/gtneootcma.html

[Q63] 开启事务
来源：http://dali.fengsongda.top/Article/details/gtegayewwh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.shuidangran.top/Article/details/gtlituewlo.html

[Q64] 提交事务
来源：http://dali.hammf.cn/Article/details/gtisrzqwhi.html

COMMIT;
来源：http://dali.iojbl.cn/Article/details/gtmdqqizwe.html

[Q65] 回滚事务
来源：http://dali.quarkkingdee.top/Article/details/gtjbxajfwe.html

ROLLBACK;
来源：http://dali.kuanghao11.cn/Article/details/gtzwykdwhw.html

[Q66] 行锁查询
来源：http://dali.tianlin.xyz/Article/details/gthzepxclt.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.chenzaomai.com/Article/details/gtavkytvzc.html

[Q67] 设置隔离级别
来源：http://dali.shuidangran.top/Article/details/gtsohwczef.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yj202588.top/Article/details/gtvvhwaull.html

[Q68] 保存点
来源：http://dali.jinghuilouyu.cn/Article/details/gtenfagibk.html

SAVEPOINT sp1;
来源：http://dali.cucudq.cn/Article/details/gtwljhfhgw.html

ROLLBACK TO sp1;
来源：http://dali.zhiwuduotai.top/Article/details/gtikjollfa.html

[Q69] 查看执行计划
来源：http://dali.shuidangran.top/Article/details/gtdyikxjvx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.dashuyun.cn/Article/details/gtwfvlijqz.html

[Q70] 更新统计信息
来源：http://dali.birdmap.top/Article/details/gtkkkeqkgu.html

ANALYZE TABLE users;
来源：http://dali.gogol.net.cn/Article/details/gtkvjktfdz.html

[Q71] 查看建表语句
来源：http://dali.gzhubu.top/Article/details/gtwdojhxsd.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.0kj1m.cn/Article/details/gttiwsczsq.html

[Q72] 查看索引
来源：http://dali.zhixingplan.top/Article/details/gteqaqahej.html

SHOW INDEX FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtychelhuz.html

[Q73] 查看表状态
来源：http://dali.jyoumei.cn/Article/details/gttwingvek.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hywenlv.cn/Article/details/gtieussrwv.html

[Q74] 强制使用索引
来源：http://dali.yvedp.cn/Article/details/gttetxqgba.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.fzhhl.top/Article/details/gthgyhlhyy.html

[Q75] 日期格式化
来源：http://dali.9152youxi.cn/Article/details/gtfnizrmoy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtjkgoduax.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.cheryme.top/Article/details/gtdtxdebwv.html

[Q76] 按天统计
来源：http://dali.0kj1m.cn/Article/details/gtksurkidn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.wangshuangyany.cn/Article/details/gtxljrffji.html

[Q77] 时间加减
来源：http://dali.ppjwa.cn/Article/details/gthbuhpufg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yuanzhike.top/Article/details/gtgdhqzdkh.html

[Q78] 当前时间
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuxycqquu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.pycfn.com/Article/details/gtwembpunu.html

[Q79] 字符串拼接
来源：http://dali.gaohongyu789.top/Article/details/gtredxchgp.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.havefunace.top/Article/details/gtgxtgkyui.html

[Q80] 字符串截取
来源：http://dali.tianlin.xyz/Article/details/gtsgtokapf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zhiwuduotai.top/Article/details/gtqqghhsck.html

[Q81] 字符串替换
来源：http://dali.cucudq.cn/Article/details/gtechpzvyp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.sweek.top/Article/details/gtqroqubcz.html

[Q82] 字符长度与字节长度
来源：http://dali.fzhhl.top/Article/details/gtbatmtsiy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtjdvgerjg.html

[Q83] 大小写转换
来源：http://dali.zhixingplan.top/Article/details/gtvniugccf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtufjxvrzz.html

[Q84] 去除首尾空格
来源：http://dali.ivvv.top/Article/details/gtxwfmidtj.html

SELECT TRIM(name) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtipzxotpa.html

[Q85] 数值取整
来源：http://dali.wangshuangyany.cn/Article/details/gtrupkgzel.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yanxiufei.cn/Article/details/gtqbjccask.html

[Q86] 读取 JSON 字段
来源：http://dali.yuanzhike.top/Article/details/gtbxqcgibd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jlsjyb.cn/Article/details/gtxekibyaq.html

[Q87] JSON 字段做条件
来源：http://dali.316326.xyz/Article/details/gtemdatnai.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hywenlv.cn/Article/details/gtypboyhsf.html

[Q88] 行转列（条件聚合）
来源：http://dali.bjfxy.top/Article/details/gtirkvbqqc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xuanzx.com/Article/details/gtusehjepo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtjuxxacuc.html

[Q89] 判断表是否存在
来源：http://dali.wangdashe.top/Article/details/gtwcwmcwdg.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinqigfzy.top/Article/details/gtvlqvkyqq.html

[Q90] 生成序号列
来源：http://dali.zhongyouzk.top/Article/details/gtvjflwfhf.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hywenlv.cn/Article/details/gtbkpiodon.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtgiovfjfm.html

R. Bash 专题
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfdqeonpz.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtocumwuln.html

[R01] shebang 与严格模式
来源：http://dali.yuxming.cn/Article/details/gtwhvnpule.html

#!/usr/bin/env bash
来源：http://dali.shanyushiyangtech.top/Article/details/gtkacjchft.html

set -euo pipefail
来源：http://dali.yj20258.top/Article/details/gteajzwxvd.html

[R02] 变量赋值与使用
来源：http://dali.ivvv.top/Article/details/gtrslvvqnp.html

name="Tom"; echo "$name"
来源：http://dali.gzhubu.top/Article/details/gtewlbahfp.html

[R03] 只读变量
来源：http://dali.sysykeji.top/Article/details/gtskaoqhuh.html

readonly PI=3.14
来源：http://dali.wangdashe.top/Article/details/gtgycetmyb.html

[R04] 位置参数
来源：http://dali.smart0.xyz/Article/details/gtmwyvwafs.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.andypj.xyz/Article/details/gtyfyuabht.html

[R05] 参数默认值
来源：http://dali.yangfankeji.com/Article/details/gtnivrrciq.html

name="${1:-default}"
来源：http://dali.hnqzz.top/Article/details/gtiusgxoge.html

[R06] 判断命令是否存在
来源：http://dali.sweek.top/Article/details/gtjszloepb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj20258888.top/Article/details/gtlkpwgfib.html

[R07] if 判断文件
来源：http://dali.yj202588.top/Article/details/gtsctfgflv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gtzbkztbha.html

[R08] 数值比较
来源：http://dali.yvedp.cn/Article/details/gtifpzkanz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hnqzz.top/Article/details/gtjdwdxmpo.html

[R09] 字符串比较
来源：http://dali.jinqigfzy.top/Article/details/gtgvhhdjsb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.smart0.xyz/Article/details/gtlomobzgl.html

[R10] 正则匹配
来源：http://dali.sweek.top/Article/details/gtnywjturt.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hywenlv.cn/Article/details/gtpcoyktft.html

[R11] case 多分支
来源：http://dali.jqgfzy.top/Article/details/gtormbbiaj.html

case "$1" in
来源：http://dali.nanxinkj.top/Article/details/gtippgwyoz.html

start) echo "启动" ;;
来源：http://dali.jqgfzy.top/Article/details/gtjbdgpcat.html

stop)  echo "停止" ;;
来源：http://dali.hnxiangtu.top/Article/details/gtyljzywci.html

*)     echo "未知命令" ;;
来源：http://dali.feifeiyinyue.top/Article/details/gtlnbaldkx.html

esac
来源：http://dali.cdnleiting.top/Article/details/gtxxxuulvo.html

[R12] for 遍历文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtigaxfpka.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jyoumei.cn/Article/details/gttocswdcx.html

[R13] for 计数循环
来源：http://dali.chenlongwang.top/Article/details/gtxkhsfwao.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hammf.cn/Article/details/gtelpwbzeo.html

[R14] C 风格 for
来源：http://dali.yj20258.top/Article/details/gtbsegcbua.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.chenjidiqi.icu/Article/details/gtsvrnuink.html

[R15] while 逐行读文件
来源：http://dali.sysykeji.top/Article/details/gtjijajwci.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.nanxuanxn.top/Article/details/gtdtvijcvr.html

[R16] until 等待条件
来源：http://dali.zhongyouzk.top/Article/details/gtdjxmwpxu.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.316326.xyz/Article/details/gtxuxyvkin.html

[R17] 数组定义与取值
来源：http://dali.jianghu66.top/Article/details/gtgekvozzo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.fzhhl.top/Article/details/gtzpfjngsx.html

[R18] 遍历数组
来源：http://dali.daria6918.cn/Article/details/gtqhbdbcdl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jinqigfzy.top/Article/details/gttyxcqjka.html

[R19] 数组长度
来源：http://dali.jqgfzy.top/Article/details/gtzrlnwybl.html

echo "${#arr[@]}"
来源：http://dali.guannengcc.top/Article/details/gthwicszvo.html

[R20] 关联数组（字典）
来源：http://dali.havefunace.top/Article/details/gtsxnlfhnr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj202588.top/Article/details/gtzsczhmit.html

[R21] 字符串长度
来源：http://dali.cheryme.top/Article/details/gtmeonyuxe.html

echo "${#s}"
来源：http://dali.yuanzhike.top/Article/details/gtmzcwrhaq.html

[R22] 截取子串
来源：http://dali.redwolf501.top/Article/details/gtitocbphj.html

echo "${s:0:5}"
来源：http://dali.zhoulong.xyz/Article/details/gtxzfgnnha.html

[R23] 字符串替换
来源：http://dali.cucudq.cn/Article/details/gtzijhpguw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zycfv.cn/Article/details/gteuxlghdj.html

[R24] 大小写转换
来源：http://dali.shanyushiyangtech.top/Article/details/gttjfjnsrg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtpxjfqlmc.html

[R25] 去后缀 / 去前缀
来源：http://dali.tian-w.cn/Article/details/gtjuobexib.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.wangshuangyany.cn/Article/details/gtckfcjjci.html

[R26] 命令替换
来源：http://dali.gaohongyu789.top/Article/details/gtyoomiglu.html

now=$(date +%F); echo "$now"
来源：http://dali.feifeiyinyue.top/Article/details/gtsyunrjne.html

[R27] 算术展开
来源：http://dali.jyoumei.cn/Article/details/gtfxmfycha.html

echo $((1 + 2 * 3))
来源：http://dali.ydzc1.top/Article/details/gtftakbkvx.html

[R28] 浮点运算
来源：http://dali.shanyushiyangkeji.top/Article/details/gtitabtgnn.html

echo "scale=2; 10/3" | bc
来源：http://dali.yj202588.top/Article/details/gtfgqimtge.html

[R29] 定义函数
来源：http://dali.aibaodan.cn/Article/details/gtamexwbsb.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.redwolf501.top/Article/details/gtomywfpqa.html

[R30] 函数返回状态码
来源：http://dali.jinqigufen.top/Article/details/gtbfiqgufi.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sweek.top/Article/details/gtpxmetpis.html

[R31] 局部变量
来源：http://dali.cashguo.top/Article/details/gteupwtfze.html

f() { local x=1; echo "$x"; }
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqlhtazyn.html

[R32] 参数个数校验
来源：http://dali.zhongyouzk.top/Article/details/gtlhmkhcxi.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yuxming.cn/Article/details/gtwvqcecyy.html

[R33] 捕获错误并提示行号
来源：http://dali.daxiang520.top/Article/details/gtusrkrmfb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.daria6918.cn/Article/details/gtxgvxcotk.html

[R34] 退出时清理
来源：http://dali.tian-w.cn/Article/details/gtzbhjqncu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sysykeji.top/Article/details/gtfyfrcueb.html

[R35] 后台执行并等待
来源：http://dali.yongpay.top/Article/details/gtidrouxjx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.jqgfzy.top/Article/details/gtzbjozzck.html

[R36] 并发执行多个任务
来源：http://dali.xuanzx.com/Article/details/gtuloaduvh.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jinqigufen.top/Article/details/gtpxtlgpes.html

[R37] 把输出赋给变量
来源：http://dali.sysykeji.top/Article/details/gtsmeefsao.html

files=$(ls -1)
来源：http://dali.xziqi.cn/Article/details/gtnohziahy.html

[R38] 管道串联
来源：http://dali.cucudq.cn/Article/details/gtyxfdwpib.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xziqi.cn/Article/details/gtynvaqakk.html

[R39] 重定向标准输出与错误
来源：http://dali.shanyushiyangtech.top/Article/details/gtcgghkxny.html

cmd > out.log 2>&1
来源：http://dali.redwolf501.top/Article/details/gtjenlvuer.html

[R40] 追加写日志
来源：http://dali.nanxuanxn.top/Article/details/gthrlqyzwx.html

echo "log" >> out.log
来源：http://dali.hnqzz.top/Article/details/gtzxejdouo.html

[R41] 丢弃输出
来源：http://dali.yuxming.cn/Article/details/gtbpggmfqt.html

cmd >/dev/null 2>&1
来源：http://dali.jinqigfzy.top/Article/details/gtytqsagup.html

[R42] 输入重定向
来源：http://dali.gotoacloud.top/Article/details/gtqbbiqxdm.html

wc -l < a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtordtplqu.html

[R43] 按名字查找文件
来源：http://dali.jqgfzy.top/Article/details/gtbohoowuq.html

find . -name "*.log" -type f
来源：http://dali.hywenlv.cn/Article/details/gtpblmklcq.html

[R44] 按修改时间查找
来源：http://dali.dashuyun.cn/Article/details/gtwovewpib.html

find . -mtime -7 -type f
来源：http://dali.havefunace.top/Article/details/gtkqshuypy.html

[R45] 批量删除
来源：http://dali.ydzc1.top/Article/details/gtywrstjza.html

find . -name "*.tmp" -delete
来源：http://dali.hnqzz.top/Article/details/gtgolnmsfn.html

[R46] 递归替换文件内容
来源：http://dali.xuetiantiany.cn/Article/details/gtapmxqmgp.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinqigfzy.top/Article/details/gtkbnxcjkp.html

[R47] sed 单行替换
来源：http://dali.ivvv.top/Article/details/gtumavbdzx.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cdnleiting.top/Article/details/gtprvjhynh.html

[R48] awk 取指定列
来源：http://dali.andypj.xyz/Article/details/gthesvlnvt.html

awk '{print $1, $3}' a.txt
来源：http://dali.cucudq.cn/Article/details/gtcsiryqef.html

[R49] awk 带条件
来源：http://dali.sweek.top/Article/details/gtfreuojma.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.tian-w.cn/Article/details/gtolxgkdve.html

[R50] awk 求和
来源：http://dali.sweek.top/Article/details/gtntlarmbb.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ehwqpu.com/Article/details/gtlsgtdngc.html

[R51] 排序去重取前几
来源：http://dali.kuanghao11.cn/Article/details/gtgqddrbhy.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gaohongyu789.top/Article/details/gtwoymiojj.html

[R52] 统计行数
来源：http://dali.andypj.xyz/Article/details/gtfmsjxqsj.html

wc -l a.txt
来源：http://dali.jianghu66.top/Article/details/gttioaeilq.html

[R53] 查看文件头与实时尾
来源：http://dali.meibo888.top/Article/details/gtbcnegkwr.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.haohaochexian.top/Article/details/gtrkmrrxlj.html

[R54] 比较两个文件
来源：http://dali.andypj.xyz/Article/details/gtepwjjycu.html

diff a.txt b.txt
来源：http://dali.aizwys.cn/Article/details/gtwcapyhem.html

[R55] 压缩与解压
来源：http://dali.zhoulong.xyz/Article/details/gteugmareo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.hfpthk.cn/Article/details/gtxxmghzof.html

[R56] 远程拷贝
来源：http://dali.ehwqpu.com/Article/details/gtqlbzbjeb.html

scp file user@host:/path/
来源：http://dali.vqdsnc.cn/Article/details/gtyqvpblfr.html

[R57] 远程执行命令
来源：http://dali.redwolf501.top/Article/details/gtauzszwfj.html

ssh user@host 'uptime'
来源：http://dali.smart0.xyz/Article/details/gttozaqiuj.html

[R58] 下载文件
来源：http://dali.ydzc1.top/Article/details/gtqubysbfi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cdnleiting.top/Article/details/gtjffbdseu.html

[R59] 发 POST JSON
来源：http://dali.snrcjt.cn/Article/details/gtqtwpxnki.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xziqi.cn/Article/details/gtnzogekku.html

[R60] 只看 HTTP 状态码
来源：http://dali.cheryme.top/Article/details/gtikufsshe.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yonumen.top/Article/details/gtowteodec.html

[R61] 磁盘占用
来源：http://dali.yj202588.top/Article/details/gtwkikohfs.html

df -h;  du -sh *
来源：http://dali.fzhhl.top/Article/details/gtgkjpqira.html

[R62] 找最占空间的文件
来源：http://dali.guowangkeji.top/Article/details/gtupsrpmle.html

du -ah . | sort -rh | head -10
来源：http://dali.yvedp.cn/Article/details/gtclieiqnl.html

[R63] 内存与进程
来源：http://dali.tanke756.top/Article/details/gtdnsdyyaz.html

free -h;  ps aux | grep nginx
来源：http://dali.aibaodan.cn/Article/details/gtvrvgudww.html

[R64] 结束进程
来源：http://dali.cashguo.top/Article/details/gtejbhxjcz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xuanzx.com/Article/details/gttdlybtgp.html

[R65] 查看端口占用
来源：http://dali.yuanzhike.top/Article/details/gtgwxbeoag.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.wangshuangyany.cn/Article/details/gthcoldmxo.html

[R66] 定时任务
来源：http://dali.hnqzz.top/Article/details/gtrntemhpt.html

crontab -e;  crontab -l
来源：http://dali.gotoacloud.top/Article/details/gtirhbwrup.html

[R67] 生成随机十六进制串
来源：http://dali.zhengqikj.top/Article/details/gtiqftxflz.html


<!-- 参考信息 -->