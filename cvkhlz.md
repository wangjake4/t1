代发 wailian999

SELECT * FROM users;
来源：http://dali.gzhubu.top/Article/details/gtlslvagtk.html

[Q16] 查询指定列
来源：http://dali.sysykeji.top/Article/details/gtwdplgzla.html

SELECT id, name FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtdbwvdkpb.html

[Q17] 条件查询
来源：http://dali.yj20258888.top/Article/details/gtrowboopx.html

SELECT * FROM users WHERE age > 18 AND status = 1;
来源：http://dali.gaohongyu789.top/Article/details/gthpqtwycc.html

[Q18] 模糊匹配
来源：http://dali.hysaishi.cn/Article/details/gtgjbonivs.html

SELECT * FROM users WHERE name LIKE '张%';
来源：http://dali.jiagoushi.top/Article/details/gttgavmqoj.html

[Q19] 范围查询
来源：http://dali.sxryk.cn/Article/details/gtbxocovfp.html

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.redwolf501.top/Article/details/gtzginxfhv.html

[Q20] IN 列表
来源：http://dali.haohaochexian.top/Article/details/gtftfkdroz.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.andypj.xyz/Article/details/gtcihbsjkx.html

[Q21] 空值判断
来源：http://dali.gaohongyu789.top/Article/details/gtosdugntf.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.yonumen.top/Article/details/gtoxfezpcl.html

[Q22] 排序
来源：http://dali.shanyushiyangtech.top/Article/details/gtwybrmski.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.kuanghao11.cn/Article/details/gtnbjhvkur.html

[Q23] 分页
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxuweszps.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.chenjidiqi.icu/Article/details/gtfudzrjjz.html

[Q24] 去重
来源：http://dali.fengsongda.top/Article/details/gtchthutrt.html

SELECT DISTINCT city FROM users;
来源：http://dali.sysykeji.top/Article/details/gtdcuaiuvy.html

[Q25] 只取前 N 条
来源：http://dali.jlsjyb.cn/Article/details/gtrtusukjp.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jinghuilouyu.cn/Article/details/gtuiynauii.html

[Q26] 计数
来源：http://dali.tanke756.top/Article/details/gtisbgtroy.html

SELECT COUNT(*) FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtcnrwjwos.html

[Q27] 条件计数
来源：http://dali.zhongyouzk.top/Article/details/gtwtdeepib.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfanxzsnw.html

[Q28] 求和与平均
来源：http://dali.daria6918.cn/Article/details/gtmonwexvw.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtxpuvwrbe.html

[Q29] 最大最小值
来源：http://dali.andypj.xyz/Article/details/gtrvdkgtxp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gturaqgkpe.html

[Q30] 分组统计
来源：http://dali.zhiwuduotai.top/Article/details/gtnxrmdgvd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jlsjyb.cn/Article/details/gtzauhetne.html

[Q31] 分组后过滤
来源：http://dali.jqgufenzy.top/Article/details/gthzptagpj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.gzhubu.top/Article/details/gtskmfoknt.html

[Q32] 分组拼接字符串
来源：http://dali.snrcjt.cn/Article/details/gtddecjebk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jiagoushi.top/Article/details/gttoxcvukf.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.shanyushiyangtech.top/Article/details/gtgubbecyz.html

[Q33] 多列分组
来源：http://dali.nanxuanxn.top/Article/details/gtenknufkq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yuanzhike.top/Article/details/gtaaqelnnu.html

[Q34] 每组取第一条
来源：http://dali.jqgfzy.top/Article/details/gtwgdltxeo.html

SELECT * FROM (
来源：http://dali.quarkkingdee.top/Article/details/gtkexdsfcp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.pycfn.com/Article/details/gtzkuysdve.html

) t WHERE rn = 1;
来源：http://dali.jiagoushi.top/Article/details/gtxxxhnvhn.html

[Q35] 内连接
来源：http://dali.xylfe.cn/Article/details/gtybnvqwua.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.nwbrower.top/Article/details/gtalfdgdxz.html

[Q36] 左连接
来源：http://dali.hnxiangtu.top/Article/details/gtsrelbavh.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xziqi.cn/Article/details/gtfefxsqgp.html

[Q37] 右连接
来源：http://dali.dianchejie.cn/Article/details/gtuxnrjczz.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xylfe.cn/Article/details/gtdcezgawe.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jinqigfzy.top/Article/details/gtyllqxfrx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xinyue.icu/Article/details/gthvbajirz.html

[Q39] 自连接（查上下级）
来源：http://dali.chenlongwang.top/Article/details/gtvphfgfzj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yj20258.top/Article/details/gtoywggkiw.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hnxiangtu.top/Article/details/gtuabcsvsc.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cqqwz.cn/Article/details/gtnolgogmd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.gogol.net.cn/Article/details/gttbuljoqq.html

[Q41] 多表连接
来源：http://dali.mhx1999.top/Article/details/gtewjsqkns.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xinyue.icu/Article/details/gtuuqagzbp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yuxming.cn/Article/details/gtvfomujes.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.dianchejie.cn/Article/details/gtejlpishm.html

[Q42] 连接条件附加过滤
来源：http://dali.wangdashe.top/Article/details/gtdelndjrd.html

SELECT u.name, o.amount FROM users u
来源：http://dali.vqdsnc.cn/Article/details/gtwhgawijh.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shangyingyoupin.top/Article/details/gthhfzgicu.html

[Q43] 标量子查询
来源：http://dali.gzhubu.top/Article/details/gtirlfzngs.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.havefunace.top/Article/details/gtvtdtohjx.html

[Q44] IN 子查询
来源：http://dali.nwbrower.top/Article/details/gtpraxines.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhongyouzk.top/Article/details/gtvbuknnhs.html

[Q45] EXISTS 判断存在
来源：http://dali.havefunace.top/Article/details/gtayurryey.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zdqjudy.top/Article/details/gtejozvbpp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.hysaishi.cn/Article/details/gtfmnvmvjg.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ydzc1.top/Article/details/gtvzvmfemq.html

[Q47] 与平均值比较
来源：http://dali.ehwqpu.com/Article/details/gtqzfzxxxy.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jlsjyb.cn/Article/details/gtoerhmyfn.html

[Q48] CTE 公用表表达式
来源：http://dali.jinghuilouyu.cn/Article/details/gtyakvxfsj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.gotoacloud.top/Article/details/gtwvphmocv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.shuidangran.top/Article/details/gtgmtfpgsa.html

[Q49] 更新单行
来源：http://dali.chenzaomai.com/Article/details/gtqvbzwaqd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtszhmiura.html

[Q50] 批量更新
来源：http://dali.haohaochexian.top/Article/details/gtqaxyouta.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zdqjudy.top/Article/details/gtfaehdffd.html

[Q51] 用子查询更新
来源：http://dali.hammf.cn/Article/details/gthwbuerbm.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhoulong.xyz/Article/details/gtuaruzzev.html

[Q52] 删除指定行
来源：http://dali.zhiwuduotai.top/Article/details/gteelqoroq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.shangyingyoupin.top/Article/details/gtaakevjxk.html

[Q53] 按条件删除
来源：http://dali.gogol.net.cn/Article/details/gtrcteofdf.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yueranfly.top/Article/details/gtqyhvmdng.html

[Q54] 清空表
来源：http://dali.xinyue.icu/Article/details/gtkxxqrwoz.html

TRUNCATE TABLE logs;
来源：http://dali.chenlongwang.top/Article/details/gtydddcmmj.html

[Q55] 排名（并列占位）
来源：http://dali.xziqi.cn/Article/details/gtbbmmeywa.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.wangdashe.top/Article/details/gtzjjlhram.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yanxiufei.cn/Article/details/gtxefvmzpz.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.sysykeji.top/Article/details/gtpwhsydvq.html

[Q57] 行号
来源：http://dali.xziqi.cn/Article/details/gtwgsugvbj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gzhubu.top/Article/details/gtwuemzhkr.html

[Q58] 累计求和
来源：http://dali.zhoulong.xyz/Article/details/gtbrqqmnqq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yueranfly.top/Article/details/gtfeauhtul.html

[Q59] 分组内累计
来源：http://dali.aizwys.cn/Article/details/gtzswnnuof.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.316326.xyz/Article/details/gtwlhdqkbo.html

[Q60] 取上一行 / 下一行
来源：http://dali.hysaishi.cn/Article/details/gtqalrpxrx.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.wangdashe.top/Article/details/gtyeumqrro.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gtqugtyfnm.html

[Q61] 移动平均
来源：http://dali.jinghuilouyu.cn/Article/details/gtcwralvzm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jyoumei.cn/Article/details/gtxwgfbgtg.html

[Q62] 分组占比
来源：http://dali.ivvv.top/Article/details/gtxuevdyeu.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvfwfoqyn.html

[Q63] 开启事务
来源：http://dali.pengpengdd.cyou/Article/details/gtzhwctwor.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcufnabmy.html

[Q64] 提交事务
来源：http://dali.hnxiangtu.top/Article/details/gtfnoarhbq.html

COMMIT;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfvtzxtyv.html

[Q65] 回滚事务
来源：http://dali.haohaochexian.top/Article/details/gtsbvecfhh.html

ROLLBACK;
来源：http://dali.shangyingyoupin.top/Article/details/gtklvlvfww.html

[Q66] 行锁查询
来源：http://dali.zhengqikj.top/Article/details/gtauknvhcm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.bjfxy.top/Article/details/gtwdkqpyig.html

[Q67] 设置隔离级别
来源：http://dali.zhoulong.xyz/Article/details/gthveejffn.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gtdcbhkiwy.html

[Q68] 保存点
来源：http://dali.wangdashe.top/Article/details/gtjenyylbu.html

SAVEPOINT sp1;
来源：http://dali.chenlongwang.top/Article/details/gtaumyeuyn.html

ROLLBACK TO sp1;
来源：http://dali.cucudq.cn/Article/details/gtyyipubar.html

[Q69] 查看执行计划
来源：http://dali.nwbrower.top/Article/details/gtxiztbvos.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ehwqpu.com/Article/details/gtyqhshmgk.html

[Q70] 更新统计信息
来源：http://dali.chenjidiqi.icu/Article/details/gtoxdsaszb.html

ANALYZE TABLE users;
来源：http://dali.cashguo.top/Article/details/gtjyckjjju.html

[Q71] 查看建表语句
来源：http://dali.c1oappe.top/Article/details/gtcyexsxxz.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.xziqi.cn/Article/details/gtetvdthaz.html

[Q72] 查看索引
来源：http://dali.hnxiangtu.top/Article/details/gtcjretynf.html

SHOW INDEX FROM users;
来源：http://dali.316326.xyz/Article/details/gtiwdkhejr.html

[Q73] 查看表状态
来源：http://dali.yongpay.top/Article/details/gtsawszpzj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.ehwqpu.com/Article/details/gtjukfshop.html

[Q74] 强制使用索引
来源：http://dali.birdmap.top/Article/details/gtnrbrblyp.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.sufxvd.cn/Article/details/gtpeyavldb.html

[Q75] 日期格式化
来源：http://dali.yj202588.top/Article/details/gtasorlltg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtwxwnjumw.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gzhubu.top/Article/details/gtsprgvhuq.html

[Q76] 按天统计
来源：http://dali.aibaodan.cn/Article/details/gtqvkcnghn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hnxiangtu.top/Article/details/gtlqhpjcxd.html

[Q77] 时间加减
来源：http://dali.xziqi.cn/Article/details/gtsxnqitvc.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhiwuduotai.top/Article/details/gtqipnqrty.html

[Q78] 当前时间
来源：http://dali.zhongyouzk.top/Article/details/gtkfttxaaa.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinqigfzy.top/Article/details/gtdbqpmxpm.html

[Q79] 字符串拼接
来源：http://dali.gotoacloud.top/Article/details/gtdgknauit.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.316326.xyz/Article/details/gtgkrczuhg.html

[Q80] 字符串截取
来源：http://dali.andypj.xyz/Article/details/gtbmecmlqs.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtimitlsre.html

[Q81] 字符串替换
来源：http://dali.hysaishi.cn/Article/details/gtaxqrtpoz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmgwaqfxh.html

[Q82] 字符长度与字节长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttmoiaewd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtudheycys.html

[Q83] 大小写转换
来源：http://dali.fzhhl.top/Article/details/gttzwimggy.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtezxppfif.html

[Q84] 去除首尾空格
来源：http://dali.pengpengdd.cyou/Article/details/gtxgvvujcr.html

SELECT TRIM(name) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtdalbucil.html

[Q85] 数值取整
来源：http://dali.cashguo.top/Article/details/gtdplxuhda.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.iojbl.cn/Article/details/gtzpbpvxhl.html

[Q86] 读取 JSON 字段
来源：http://dali.chenjidiqi.icu/Article/details/gtzojofkbk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xuetiantiany.cn/Article/details/gtzticvzfd.html

[Q87] JSON 字段做条件
来源：http://dali.xuetiantiany.cn/Article/details/gtqxdgkcop.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.nanxuanxn.top/Article/details/gtafhhmadi.html

[Q88] 行转列（条件聚合）
来源：http://dali.nanxinkj.top/Article/details/gtetriztmd.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.sufxvd.cn/Article/details/gtbzkqpfxx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqoeeatie.html

[Q89] 判断表是否存在
来源：http://dali.nwbrower.top/Article/details/gtyosomwrz.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cucudq.cn/Article/details/gtcrrygixs.html

[Q90] 生成序号列
来源：http://dali.redwolf501.top/Article/details/gtsbqkhqeb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gaohongyu789.top/Article/details/gtqzvcwyhd.html

================================================================================
来源：http://dali.ppjwa.cn/Article/details/gtkukpjzmh.html

R. Bash 专题
来源：http://dali.chenzaomai.com/Article/details/gtpmewntgv.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtdralatvj.html

[R01] shebang 与严格模式
来源：http://dali.haohaochexian.top/Article/details/gtvlplajbi.html

#!/usr/bin/env bash
来源：http://dali.ehwqpu.com/Article/details/gtdmmlchqd.html

set -euo pipefail
来源：http://dali.zhixingplan.top/Article/details/gtofajfqpx.html

[R02] 变量赋值与使用
来源：http://dali.shzxlz.cn/Article/details/gtbxgkxwoy.html

name="Tom"; echo "$name"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwfswefqz.html

[R03] 只读变量
来源：http://dali.havefunace.top/Article/details/gtonndpkjy.html

readonly PI=3.14
来源：http://dali.zhongyouzk.top/Article/details/gthzbfpade.html

[R04] 位置参数
来源：http://dali.chenlongwang.top/Article/details/gtpobgkiup.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gogol.net.cn/Article/details/gtoncifxmi.html

[R05] 参数默认值
来源：http://dali.zdqjudy.top/Article/details/gtuhjxnjwv.html

name="${1:-default}"
来源：http://dali.pengpengdd.cyou/Article/details/gtdrsmcogk.html

[R06] 判断命令是否存在
来源：http://dali.jlsjyb.cn/Article/details/gtvebpwany.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.xziqi.cn/Article/details/gtbgmkkcfy.html

[R07] if 判断文件
来源：http://dali.jinqigufen.top/Article/details/gtymbnvnna.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinqigfzy.top/Article/details/gttxnraolz.html

[R08] 数值比较
来源：http://dali.tian-w.cn/Article/details/gtveqxtcmr.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cucudq.cn/Article/details/gtlijtirnw.html

[R09] 字符串比较
来源：http://dali.shzxlz.cn/Article/details/gtafuoxbgf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.fzhhl.top/Article/details/gtdpefrqnq.html

[R10] 正则匹配
来源：http://dali.shzxlz.cn/Article/details/gtpbgoqjwz.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hywenlv.cn/Article/details/gtjyphdojc.html

[R11] case 多分支
来源：http://dali.shzxlz.cn/Article/details/gtbwcmjjqv.html

case "$1" in
来源：http://dali.sxryk.cn/Article/details/gtgkciptfi.html

start) echo "启动" ;;
来源：http://dali.redwolf501.top/Article/details/gtsgorqzwb.html

stop)  echo "停止" ;;
来源：http://dali.hongshengwenyu.top/Article/details/gtegxlkqxe.html

*)     echo "未知命令" ;;
来源：http://dali.fengsongda.top/Article/details/gteheqzgtf.html

esac
来源：http://dali.tanke756.top/Article/details/gtuocndfzu.html

[R12] for 遍历文件
来源：http://dali.c1oappe.top/Article/details/gtgbjeqmly.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ppjwa.cn/Article/details/gtjkqwemtj.html

[R13] for 计数循环
来源：http://dali.nanxinkj.top/Article/details/gtkipyhfis.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jinghuilouyu.cn/Article/details/gtsjpgdwtl.html

[R14] C 风格 for
来源：http://dali.shuidangran.top/Article/details/gtppsonrod.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqdctlcud.html

[R15] while 逐行读文件
来源：http://dali.ydzc1.top/Article/details/gthwbdlxtq.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.andypj.xyz/Article/details/gtjftospqh.html

[R16] until 等待条件
来源：http://dali.fengsongda.top/Article/details/gtsnwsyqdm.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlvlgewqn.html

[R17] 数组定义与取值
来源：http://dali.chenjidiqi.icu/Article/details/gtrahxssqm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shangyingyoupin.top/Article/details/gtqptkayep.html

[R18] 遍历数组
来源：http://dali.pycfn.com/Article/details/gtdazigimq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shuidangran.top/Article/details/gtfbwmjdwl.html

[R19] 数组长度
来源：http://dali.ybcxt.top/Article/details/gtzbnbbydo.html

echo "${#arr[@]}"
来源：http://dali.pengpengdd.cyou/Article/details/gtkxryexcg.html

[R20] 关联数组（字典）
来源：http://dali.yj20258.top/Article/details/gtafanbskn.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.aizwys.cn/Article/details/gthcjfkaid.html

[R21] 字符串长度
来源：http://dali.daxiang520.top/Article/details/gtkwpzlbjr.html

echo "${#s}"
来源：http://dali.yangfankeji.com/Article/details/gtadcxphse.html

[R22] 截取子串
来源：http://dali.zhaomingkeji.xyz/Article/details/gteqajgxyq.html

echo "${s:0:5}"
来源：http://dali.sysykeji.top/Article/details/gtapijytgt.html

[R23] 字符串替换
来源：http://dali.yueranfly.top/Article/details/gtocztpipk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xinyue.icu/Article/details/gtasljaqdp.html

[R24] 大小写转换
来源：http://dali.dashuyun.cn/Article/details/gtmmoiqbvd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.tianlin.xyz/Article/details/gtzrjyziom.html

[R25] 去后缀 / 去前缀
来源：http://dali.yongpay.top/Article/details/gtepjzehzj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.kuanghao11.cn/Article/details/gtxkvbpcry.html

[R26] 命令替换
来源：http://dali.iojbl.cn/Article/details/gtessjtgxn.html

now=$(date +%F); echo "$now"
来源：http://dali.yuanzhike.top/Article/details/gtycfqhqnd.html

[R27] 算术展开
来源：http://dali.zhiwuduotai.top/Article/details/gtmktwfmse.html

echo $((1 + 2 * 3))
来源：http://dali.chenlongwang.top/Article/details/gtfjsncmor.html

[R28] 浮点运算
来源：http://dali.zhongyouzk.top/Article/details/gtnmrigdel.html

echo "scale=2; 10/3" | bc
来源：http://dali.jinghuilouyu.cn/Article/details/gtwrlywzpo.html

[R29] 定义函数
来源：http://dali.havefunace.top/Article/details/gtbbwuxxqv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.daria6918.cn/Article/details/gtgcrtpcxu.html

[R30] 函数返回状态码
来源：http://dali.yangfankeji.com/Article/details/gtafvffvac.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.aizwys.cn/Article/details/gtqnvhzpqf.html

[R31] 局部变量
来源：http://dali.ybcxt.top/Article/details/gtdophxtnq.html

f() { local x=1; echo "$x"; }
来源：http://dali.yvedp.cn/Article/details/gtnoeonfgz.html

[R32] 参数个数校验
来源：http://dali.dianchejie.cn/Article/details/gtzfzvzkvd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jlsjyb.cn/Article/details/gtvguheabt.html

[R33] 捕获错误并提示行号
来源：http://dali.316326.xyz/Article/details/gtkpfpxfdl.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.meibo888.top/Article/details/gteywfbpoz.html

[R34] 退出时清理
来源：http://dali.9152youxi.cn/Article/details/gtvgwmlczm.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj20258.top/Article/details/gtjscpsjzz.html

[R35] 后台执行并等待
来源：http://dali.tanke756.top/Article/details/gtbeuyrngb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.guowangkeji.top/Article/details/gtyazlivpi.html

[R36] 并发执行多个任务
来源：http://dali.yueranfly.top/Article/details/gtgomjkfrb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zhoulong.xyz/Article/details/gtlhhorbzd.html

[R37] 把输出赋给变量
来源：http://dali.feifeiyinyue.top/Article/details/gtppybrvkt.html

files=$(ls -1)
来源：http://dali.nanxuanxn.top/Article/details/gtuqmwidwr.html

[R38] 管道串联
来源：http://dali.zhengqikj.top/Article/details/gtiaioxrhm.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ppjwa.cn/Article/details/gtxopvnlpb.html

[R39] 重定向标准输出与错误
来源：http://dali.dianchejie.cn/Article/details/gtdgosrkpb.html

cmd > out.log 2>&1
来源：http://dali.shuidangran.top/Article/details/gtwihpvkwy.html

[R40] 追加写日志
来源：http://dali.wangdashe.top/Article/details/gtnwtcwcle.html

echo "log" >> out.log
来源：http://dali.9152youxi.cn/Article/details/gtugiiyuhf.html

[R41] 丢弃输出
来源：http://dali.daxiang520.top/Article/details/gtkoimfrcr.html

cmd >/dev/null 2>&1
来源：http://dali.aizwys.cn/Article/details/gtboksapds.html

[R42] 输入重定向
来源：http://dali.zycfv.cn/Article/details/gtkqnligif.html

wc -l < a.txt
来源：http://dali.svipenyu.cn/Article/details/gtibxvituy.html

[R43] 按名字查找文件
来源：http://dali.yuxming.cn/Article/details/gtfrwtnnnf.html

find . -name "*.log" -type f
来源：http://dali.yonumen.top/Article/details/gtcqmeukyp.html

[R44] 按修改时间查找
来源：http://dali.jinyuanbaomall.cn/Article/details/gttaacdyru.html

find . -mtime -7 -type f
来源：http://dali.vqdsnc.cn/Article/details/gtybbfgoht.html

[R45] 批量删除
来源：http://dali.vqdsnc.cn/Article/details/gtceuxkjai.html

find . -name "*.tmp" -delete
来源：http://dali.ehwqpu.com/Article/details/gtxmausegp.html

[R46] 递归替换文件内容
来源：http://dali.cashguo.top/Article/details/gttbuwomwe.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cashguo.top/Article/details/gtzqgnbkkl.html

[R47] sed 单行替换
来源：http://dali.shzxlz.cn/Article/details/gtmhsfrvfe.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.dianchejie.cn/Article/details/gtksjpspjn.html

[R48] awk 取指定列
来源：http://dali.cucudq.cn/Article/details/gtzssahdxi.html

awk '{print $1, $3}' a.txt
来源：http://dali.hysaishi.cn/Article/details/gtdrwedqwv.html

[R49] awk 带条件
来源：http://dali.gaohongyu789.top/Article/details/gtqjxziygc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.wangshuangyany.cn/Article/details/gthrlendym.html

[R50] awk 求和
来源：http://dali.dashuyun.cn/Article/details/gtdsujtdza.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtnzxygtfr.html

[R51] 排序去重取前几
来源：http://dali.kuanghao11.cn/Article/details/gtfinutmqt.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.xuetiantiany.cn/Article/details/gtsnbnjlam.html

[R52] 统计行数
来源：http://dali.jinyuanbaomall.cn/Article/details/gtylpqlzoq.html

wc -l a.txt
来源：http://dali.xinyue.icu/Article/details/gtrcuozeft.html

[R53] 查看文件头与实时尾
来源：http://dali.gotoacloud.top/Article/details/gtgzazcnbd.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yuanzhike.top/Article/details/gtfdxpzbvt.html

[R54] 比较两个文件
来源：http://dali.guowangkeji.top/Article/details/gtqgudyjvd.html

diff a.txt b.txt
来源：http://dali.cdnleiting.top/Article/details/gtqrhmouqn.html

[R55] 压缩与解压
来源：http://dali.yj20258888.top/Article/details/gtuoxvnqcj.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.vqdsnc.cn/Article/details/gtapjtgjwy.html

[R56] 远程拷贝
来源：http://dali.sxryk.cn/Article/details/gtdddskdqh.html

scp file user@host:/path/
来源：http://dali.andypj.xyz/Article/details/gtuziefmyb.html

[R57] 远程执行命令
来源：http://dali.guowangkeji.top/Article/details/gtgdwotksf.html

ssh user@host 'uptime'
来源：http://dali.zhijiandao.cn/Article/details/gtvbnmdxoe.html

[R58] 下载文件
来源：http://dali.tian-w.cn/Article/details/gthllagwdn.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zycfv.cn/Article/details/gtjdsqbdbu.html

[R59] 发 POST JSON
来源：http://dali.cdnleiting.top/Article/details/gthczbvbbn.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinghuilouyu.cn/Article/details/gtgecsingm.html

[R60] 只看 HTTP 状态码
来源：http://dali.gaohongyu789.top/Article/details/gtppstjplc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jlsjyb.cn/Article/details/gtoknzpevt.html

[R61] 磁盘占用
来源：http://dali.gzhubu.top/Article/details/gtlnwftqpe.html

df -h;  du -sh *
来源：http://dali.hnqzz.top/Article/details/gtuzqkpoax.html

[R62] 找最占空间的文件
来源：http://dali.meibo888.top/Article/details/gtuvhnpdmv.html

du -ah . | sort -rh | head -10
来源：http://dali.jinqigufen.top/Article/details/gtwwuvvghy.html

[R63] 内存与进程
来源：http://dali.gaohongyu789.top/Article/details/gtlzswxkqm.html

free -h;  ps aux | grep nginx
来源：http://dali.yonumen.top/Article/details/gtwlubbzap.html

[R64] 结束进程
来源：http://dali.svipenyu.cn/Article/details/gtnnaqzjdw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.dianchejie.cn/Article/details/gtflgtfyxs.html

[R65] 查看端口占用
来源：http://dali.jiagoushi.top/Article/details/gtemtgaxpj.html


<!-- 参考信息 -->