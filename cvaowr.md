代发 wailian999

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.zhoulong.xyz/Article/details/gtcburkhbw.html

[Q20] IN 列表
来源：http://dali.quarkkingdee.top/Article/details/gtddszhdul.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.svipenyu.cn/Article/details/gtfasrsphg.html

[Q21] 空值判断
来源：http://dali.ppjwa.cn/Article/details/gtmonvwnao.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.sufxvd.cn/Article/details/gtfplpyqxc.html

[Q22] 排序
来源：http://dali.sxryk.cn/Article/details/gtmseirsha.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.iojbl.cn/Article/details/gtwnfwsmlj.html

[Q23] 分页
来源：http://dali.guowangkeji.top/Article/details/gtxvikfghb.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hongshengwenyu.top/Article/details/gtgvppfyal.html

[Q24] 去重
来源：http://dali.iojbl.cn/Article/details/gtwzsixtrk.html

SELECT DISTINCT city FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvwviunch.html

[Q25] 只取前 N 条
来源：http://dali.wangshuangyany.cn/Article/details/gtitapwzzh.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.gzhubu.top/Article/details/gtbdiavguc.html

[Q26] 计数
来源：http://dali.hnqzz.top/Article/details/gtvimzpmyu.html

SELECT COUNT(*) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtstqvkqiw.html

[Q27] 条件计数
来源：http://dali.fengsongda.top/Article/details/gtzwdalwhb.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtdufsvbfb.html

[Q28] 求和与平均
来源：http://dali.jinghuilouyu.cn/Article/details/gtxgpvabhp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.smart0.xyz/Article/details/gtmeoifkde.html

[Q29] 最大最小值
来源：http://dali.hnxiangtu.top/Article/details/gtqncrxwty.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtnlfakvms.html

[Q30] 分组统计
来源：http://dali.cqqwz.cn/Article/details/gtrwqfgsrd.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yonumen.top/Article/details/gtgrftwojp.html

[Q31] 分组后过滤
来源：http://dali.daria6918.cn/Article/details/gtqboetxrv.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.chenzaomai.com/Article/details/gtvkziwhlu.html

[Q32] 分组拼接字符串
来源：http://dali.zdqjudy.top/Article/details/gttycffbvj.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.quarkkingdee.top/Article/details/gtunlrsfat.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtuaxwkzja.html

[Q33] 多列分组
来源：http://dali.chenjidiqi.icu/Article/details/gtnuljumtb.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.fzhhl.top/Article/details/gttkcilgyr.html

[Q34] 每组取第一条
来源：http://dali.sxryk.cn/Article/details/gtrafxgocj.html

SELECT * FROM (
来源：http://dali.birdmap.top/Article/details/gteuweznyq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shzxlz.cn/Article/details/gtobbtxwbh.html

) t WHERE rn = 1;
来源：http://dali.pycfn.com/Article/details/gtjgigiwta.html

[Q35] 内连接
来源：http://dali.vqdsnc.cn/Article/details/gtayqwztkx.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cqqwz.cn/Article/details/gtozimslhk.html

[Q36] 左连接
来源：http://dali.havefunace.top/Article/details/gtuctuzlau.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hammf.cn/Article/details/gtchygdkqx.html

[Q37] 右连接
来源：http://dali.chenlongwang.top/Article/details/gteoygfzzo.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ydzc1.top/Article/details/gtsqxvbhhq.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.iojbl.cn/Article/details/gtkaflhpoq.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.nanxuanxn.top/Article/details/gtyxxnwcsi.html

[Q39] 自连接（查上下级）
来源：http://dali.shanyushiyangtech.top/Article/details/gtqkozqoch.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jqgufenzy.top/Article/details/gtczujwigj.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.cashguo.top/Article/details/gtcoevsnan.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hammf.cn/Article/details/gtozajgtit.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yangfankeji.com/Article/details/gtatpyuvyz.html

[Q41] 多表连接
来源：http://dali.pengpengdd.cyou/Article/details/gtbmrbpuzy.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.ybcxt.top/Article/details/gtgoizanci.html

JOIN users u ON u.id = o.user_id
来源：http://dali.gaohongyu789.top/Article/details/gtjdydpngb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zhixingplan.top/Article/details/gtrqkyedwy.html

[Q42] 连接条件附加过滤
来源：http://dali.sxryk.cn/Article/details/gtxhlaflzm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.hammf.cn/Article/details/gtqtkkapor.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yuxming.cn/Article/details/gtnxokzooe.html

[Q43] 标量子查询
来源：http://dali.cqqwz.cn/Article/details/gtpszrjfwn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ppjwa.cn/Article/details/gtwlkulwhw.html

[Q44] IN 子查询
来源：http://dali.dashuyun.cn/Article/details/gtkegilipv.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yonumen.top/Article/details/gtboumyajx.html

[Q45] EXISTS 判断存在
来源：http://dali.hysaishi.cn/Article/details/gtcuychvnh.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daria6918.cn/Article/details/gtausqtdwe.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.smart0.xyz/Article/details/gtyqrbedls.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sufxvd.cn/Article/details/gtgyipzdvn.html

[Q47] 与平均值比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gttrbpdaxt.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.gotoacloud.top/Article/details/gtxxnveteb.html

[Q48] CTE 公用表表达式
来源：http://dali.zdqjudy.top/Article/details/gthafjzvss.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hnxiangtu.top/Article/details/gtdzuokvna.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.nwbrower.top/Article/details/gtchixqudu.html

[Q49] 更新单行
来源：http://dali.yj20258888.top/Article/details/gtojrgkknr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.haohaochexian.top/Article/details/gtrumpjmwo.html

[Q50] 批量更新
来源：http://dali.mhx1999.top/Article/details/gtdlsllbhb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.cdnleiting.top/Article/details/gtmbtdauoy.html

[Q51] 用子查询更新
来源：http://dali.haohaochexian.top/Article/details/gtoqmulxcc.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cqqwz.cn/Article/details/gtiqaftdnq.html

[Q52] 删除指定行
来源：http://dali.sufxvd.cn/Article/details/gtuhtbbban.html

DELETE FROM users WHERE id = 10;
来源：http://dali.gotoacloud.top/Article/details/gtxfojhtmw.html

[Q53] 按条件删除
来源：http://dali.ywan-chungtsiang.top/Article/details/gttbzpveqy.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.redwolf501.top/Article/details/gtjfxsvlbh.html

[Q54] 清空表
来源：http://dali.yongpay.top/Article/details/gthmzsrhrk.html

TRUNCATE TABLE logs;
来源：http://dali.yuanzhike.top/Article/details/gttiaibyjz.html

[Q55] 排名（并列占位）
来源：http://dali.zhixingplan.top/Article/details/gtrmeouajt.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xinyue.icu/Article/details/gtqhysvpsj.html

[Q56] 密集排名（并列不占位）
来源：http://dali.jiagoushi.top/Article/details/gtohhhyuyp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhongyouzk.top/Article/details/gtmgzerahw.html

[Q57] 行号
来源：http://dali.sufxvd.cn/Article/details/gtdvkzaqwy.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gthueslcna.html

[Q58] 累计求和
来源：http://dali.ydzc1.top/Article/details/gtpbkuzkch.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtaocvnfru.html

[Q59] 分组内累计
来源：http://dali.zhoulong.xyz/Article/details/gtnxmjkyse.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfzsehzhl.html

[Q60] 取上一行 / 下一行
来源：http://dali.jqgufenzy.top/Article/details/gtwizwzuzp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.guannengcc.top/Article/details/gtmqipcytf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.sufxvd.cn/Article/details/gtvfulqako.html

[Q61] 移动平均
来源：http://dali.cheryme.top/Article/details/gtymvmmchx.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.tanke756.top/Article/details/gtqishcgiz.html

[Q62] 分组占比
来源：http://dali.guowangkeji.top/Article/details/gtteywubjj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gaohongyu789.top/Article/details/gtzfzswert.html

[Q63] 开启事务
来源：http://dali.yvedp.cn/Article/details/gtvquefdba.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gotoacloud.top/Article/details/gtemoiiagv.html

[Q64] 提交事务
来源：http://dali.aibaodan.cn/Article/details/gtakqrlpqq.html

COMMIT;
来源：http://dali.chenjidiqi.icu/Article/details/gtnnmgzjkh.html

[Q65] 回滚事务
来源：http://dali.quarkkingdee.top/Article/details/gtycvkjpwc.html

ROLLBACK;
来源：http://dali.jianghu66.top/Article/details/gtpmhtoyel.html

[Q66] 行锁查询
来源：http://dali.yj20258.top/Article/details/gtkzhsbjyy.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.aibaodan.cn/Article/details/gtamdetyzt.html

[Q67] 设置隔离级别
来源：http://dali.kuanghao11.cn/Article/details/gtsviemcfz.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.nanxuanxn.top/Article/details/gtjbwtxnrf.html

[Q68] 保存点
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtungqfceo.html

SAVEPOINT sp1;
来源：http://dali.yonumen.top/Article/details/gtolgqwlof.html

ROLLBACK TO sp1;
来源：http://dali.nwbrower.top/Article/details/gtmplujbjy.html

[Q69] 查看执行计划
来源：http://dali.ehwqpu.com/Article/details/gtrgckoifx.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.pycfn.com/Article/details/gtkarzsbho.html

[Q70] 更新统计信息
来源：http://dali.shzxlz.cn/Article/details/gtsaujpebq.html

ANALYZE TABLE users;
来源：http://dali.hfpthk.cn/Article/details/gtledgyhik.html

[Q71] 查看建表语句
来源：http://dali.guowangkeji.top/Article/details/gtdiwphmkc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jinghuilouyu.cn/Article/details/gthzdrchei.html

[Q72] 查看索引
来源：http://dali.hongshengwenyu.top/Article/details/gtgiapvvdf.html

SHOW INDEX FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtmlrtomnc.html

[Q73] 查看表状态
来源：http://dali.316326.xyz/Article/details/gteoekexgo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jyoumei.cn/Article/details/gtjwrqwytq.html

[Q74] 强制使用索引
来源：http://dali.cashguo.top/Article/details/gtlvvqehig.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqgtczaej.html

[Q75] 日期格式化
来源：http://dali.vqdsnc.cn/Article/details/gtzgctqxip.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtflznriem.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.wangdashe.top/Article/details/gthoanibki.html

[Q76] 按天统计
来源：http://dali.pengpengdd.cyou/Article/details/gtohwfmtpr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.gotoacloud.top/Article/details/gtwsoyvzib.html

[Q77] 时间加减
来源：http://dali.kuanghao11.cn/Article/details/gtffhlrdjg.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.tian-w.cn/Article/details/gtxbbxwcha.html

[Q78] 当前时间
来源：http://dali.jianghu66.top/Article/details/gttdtrjuks.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yueranfly.top/Article/details/gtleerunij.html

[Q79] 字符串拼接
来源：http://dali.ivvv.top/Article/details/gtpwpcvwqz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cashguo.top/Article/details/gtqmsbcohl.html

[Q80] 字符串截取
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjfddwxxc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtalgmuxpm.html

[Q81] 字符串替换
来源：http://dali.vqdsnc.cn/Article/details/gtmtyoknbp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtrryganne.html

[Q82] 字符长度与字节长度
来源：http://dali.wangshuangyany.cn/Article/details/gtbmcxoyww.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtsfyqjjoj.html

[Q83] 大小写转换
来源：http://dali.bjfxy.top/Article/details/gtlkgqwfdf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtblaazzkx.html

[Q84] 去除首尾空格
来源：http://dali.zycfv.cn/Article/details/gtwvktttfl.html

SELECT TRIM(name) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtjnxqjqgv.html

[Q85] 数值取整
来源：http://dali.gzhubu.top/Article/details/gtuluhwtdl.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hammf.cn/Article/details/gtzvlmdwco.html

[Q86] 读取 JSON 字段
来源：http://dali.dianchejie.cn/Article/details/gthdfwnrfo.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.gzhubu.top/Article/details/gthuuvsfnc.html

[Q87] JSON 字段做条件
来源：http://dali.cheryme.top/Article/details/gtsjiqhffl.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.feifeiyinyue.top/Article/details/gtugjtpgnh.html

[Q88] 行转列（条件聚合）
来源：http://dali.zycfv.cn/Article/details/gthideedhl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.iojbl.cn/Article/details/gtcmexjuin.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sysykeji.top/Article/details/gtzepicdvc.html

[Q89] 判断表是否存在
来源：http://dali.gzhubu.top/Article/details/gtdjwbyfgj.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.iojbl.cn/Article/details/gtwvuhbzgz.html

[Q90] 生成序号列
来源：http://dali.ehwqpu.com/Article/details/gtjgdoqizg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jlsjyb.cn/Article/details/gtllropqhe.html

================================================================================
来源：http://dali.ydzc1.top/Article/details/gthztdephg.html

R. Bash 专题
来源：http://dali.shzxlz.cn/Article/details/gtfaqqbvig.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtissrbnln.html

[R01] shebang 与严格模式
来源：http://dali.sweek.top/Article/details/gtlryuaffi.html

#!/usr/bin/env bash
来源：http://dali.cheryme.top/Article/details/gtokjvltxw.html

set -euo pipefail
来源：http://dali.hammf.cn/Article/details/gtjszvepip.html

[R02] 变量赋值与使用
来源：http://dali.sufxvd.cn/Article/details/gtpbhaarjl.html

name="Tom"; echo "$name"
来源：http://dali.jqgufenzy.top/Article/details/gtjfydelov.html

[R03] 只读变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtquxkpcfu.html

readonly PI=3.14
来源：http://dali.chenjidiqi.icu/Article/details/gtrfdwxygm.html

[R04] 位置参数
来源：http://dali.hywenlv.cn/Article/details/gtokastbdx.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.chenzaomai.com/Article/details/gtawcremgc.html

[R05] 参数默认值
来源：http://dali.zhixingplan.top/Article/details/gtmpektbsv.html

name="${1:-default}"
来源：http://dali.svipenyu.cn/Article/details/gtuyevgoei.html

[R06] 判断命令是否存在
来源：http://dali.9152youxi.cn/Article/details/gtbqqvxlyi.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jlsjyb.cn/Article/details/gtbcnjxfgo.html

[R07] if 判断文件
来源：http://dali.jianghu66.top/Article/details/gthkqwigsk.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gtcufumbnt.html

[R08] 数值比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwvhkwwar.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.hysaishi.cn/Article/details/gtcgdnekgq.html

[R09] 字符串比较
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfcrrpygu.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gttiwcgvud.html

[R10] 正则匹配
来源：http://dali.gotoacloud.top/Article/details/gtoxmvgggi.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hammf.cn/Article/details/gtoyogguoy.html

[R11] case 多分支
来源：http://dali.cucudq.cn/Article/details/gtrfbcbabt.html

case "$1" in
来源：http://dali.xuanzx.com/Article/details/gtgfxkyeda.html

start) echo "启动" ;;
来源：http://dali.smart0.xyz/Article/details/gtlgannylv.html

stop)  echo "停止" ;;
来源：http://dali.ivvv.top/Article/details/gtbhlttmqo.html

*)     echo "未知命令" ;;
来源：http://dali.feifeiyinyue.top/Article/details/gtupzflacn.html

esac
来源：http://dali.jianghu66.top/Article/details/gtiotkgfwx.html

[R12] for 遍历文件
来源：http://dali.kuanghao11.cn/Article/details/gteifpabuo.html

for f in *.txt; do echo "$f"; done
来源：http://dali.guowangkeji.top/Article/details/gtopktajlh.html

[R13] for 计数循环
来源：http://dali.snrcjt.cn/Article/details/gtrmgucpos.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.0kj1m.cn/Article/details/gtkobkagys.html

[R14] C 风格 for
来源：http://dali.jqgfzy.top/Article/details/gtzzuxckwe.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hongshengwenyu.top/Article/details/gtuhsekjju.html

[R15] while 逐行读文件
来源：http://dali.xuanzx.com/Article/details/gtducejkfv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hnxiangtu.top/Article/details/gtoihduqod.html

[R16] until 等待条件
来源：http://dali.tianlin.xyz/Article/details/gtuuicgrkl.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.gotoacloud.top/Article/details/gtgtmstsrr.html

[R17] 数组定义与取值
来源：http://dali.shanyushiyangtech.top/Article/details/gtafsdxdxq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yonumen.top/Article/details/gtppbjkpjc.html

[R18] 遍历数组
来源：http://dali.tanke756.top/Article/details/gtnkhxdlvz.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jqgufenzy.top/Article/details/gtndvhjivk.html

[R19] 数组长度
来源：http://dali.cashguo.top/Article/details/gtltzxzoyt.html

echo "${#arr[@]}"
来源：http://dali.xinyue.icu/Article/details/gtayfjenmt.html

[R20] 关联数组（字典）
来源：http://dali.wangshuangyany.cn/Article/details/gtrpmtskgl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.xinyue.icu/Article/details/gtmesouxfq.html

[R21] 字符串长度
来源：http://dali.ehwqpu.com/Article/details/gtnjfvhhjy.html

echo "${#s}"
来源：http://dali.redwolf501.top/Article/details/gtohcyupbq.html

[R22] 截取子串
来源：http://dali.yonumen.top/Article/details/gtokyvspbs.html

echo "${s:0:5}"
来源：http://dali.xinyue.icu/Article/details/gtcersyqqj.html

[R23] 字符串替换
来源：http://dali.ivvv.top/Article/details/gtmsqgobna.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.pycfn.com/Article/details/gtqrroysuq.html

[R24] 大小写转换
来源：http://dali.yvedp.cn/Article/details/gtegzluqrf.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.daria6918.cn/Article/details/gtwomeznce.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhengqikj.top/Article/details/gtmzaqwwti.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.bjfxy.top/Article/details/gtehcsgkdg.html

[R26] 命令替换
来源：http://dali.zdqjudy.top/Article/details/gtbrkyzijr.html

now=$(date +%F); echo "$now"
来源：http://dali.nanxinkj.top/Article/details/gtqjqdaksq.html

[R27] 算术展开
来源：http://dali.birdmap.top/Article/details/gtbcbcbbpv.html

echo $((1 + 2 * 3))
来源：http://dali.gaohongyu789.top/Article/details/gtbwhkormm.html

[R28] 浮点运算
来源：http://dali.316326.xyz/Article/details/gtzlrjfppg.html

echo "scale=2; 10/3" | bc
来源：http://dali.iojbl.cn/Article/details/gtxtfrthgb.html

[R29] 定义函数
来源：http://dali.cdnleiting.top/Article/details/gtqtezperr.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinqigfzy.top/Article/details/gtfsncbvji.html

[R30] 函数返回状态码
来源：http://dali.zhaomingkeji.xyz/Article/details/gtyueyewfw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.yj202588.top/Article/details/gtdbrzbcge.html

[R31] 局部变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtxnajwipa.html

f() { local x=1; echo "$x"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtdrwcybmr.html

[R32] 参数个数校验
来源：http://dali.ppjwa.cn/Article/details/gtyzhauqwt.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.9152youxi.cn/Article/details/gtbpwsuxkv.html

[R33] 捕获错误并提示行号
来源：http://dali.ivvv.top/Article/details/gtnfootmix.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.guannengcc.top/Article/details/gtdvluaknp.html

[R34] 退出时清理
来源：http://dali.shuidangran.top/Article/details/gtxmfggfqj.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gtlzjvpowv.html

[R35] 后台执行并等待
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrmgfkzlx.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yuanzhike.top/Article/details/gtgtopldzb.html

[R36] 并发执行多个任务
来源：http://dali.gotoacloud.top/Article/details/gtfuvbobkw.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.bjfxy.top/Article/details/gtbsolqmeh.html

[R37] 把输出赋给变量
来源：http://dali.gogol.net.cn/Article/details/gtfygurvgb.html

files=$(ls -1)
来源：http://dali.gaohongyu789.top/Article/details/gtxxpeqxvg.html

[R38] 管道串联
来源：http://dali.jqgufenzy.top/Article/details/gtgylljyos.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yangfankeji.com/Article/details/gthieuxnkr.html

[R39] 重定向标准输出与错误
来源：http://dali.svipenyu.cn/Article/details/gteylieafv.html

cmd > out.log 2>&1
来源：http://dali.sxryk.cn/Article/details/gtdshkfvmx.html

[R40] 追加写日志
来源：http://dali.daria6918.cn/Article/details/gtdkahbykt.html

echo "log" >> out.log
来源：http://dali.zhengqikj.top/Article/details/gtxkonbbrg.html

[R41] 丢弃输出
来源：http://dali.xinyue.icu/Article/details/gtmconrmvq.html

cmd >/dev/null 2>&1
来源：http://dali.pengpengdd.cyou/Article/details/gtczgftwfj.html

[R42] 输入重定向
来源：http://dali.zycfv.cn/Article/details/gtyogpmyae.html

wc -l < a.txt
来源：http://dali.redwolf501.top/Article/details/gtcztkcnsc.html

[R43] 按名字查找文件
来源：http://dali.cashguo.top/Article/details/gthlvzsuwo.html

find . -name "*.log" -type f
来源：http://dali.shzxlz.cn/Article/details/gtywpuijoo.html

[R44] 按修改时间查找
来源：http://dali.jyoumei.cn/Article/details/gtcsyyzmqh.html

find . -mtime -7 -type f
来源：http://dali.smart0.xyz/Article/details/gtphatuvbo.html

[R45] 批量删除
来源：http://dali.yanxiufei.cn/Article/details/gtlptidxhi.html

find . -name "*.tmp" -delete
来源：http://dali.yuxming.cn/Article/details/gtypzrowvd.html

[R46] 递归替换文件内容
来源：http://dali.nwbrower.top/Article/details/gtjsvzioct.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.tian-w.cn/Article/details/gtmizpzshm.html

[R47] sed 单行替换
来源：http://dali.zhoulong.xyz/Article/details/gtscoscqwa.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.xuanzx.com/Article/details/gtqrhpobnx.html

[R48] awk 取指定列
来源：http://dali.andypj.xyz/Article/details/gtdfousxny.html

awk '{print $1, $3}' a.txt
来源：http://dali.hywenlv.cn/Article/details/gtkugifmiu.html

[R49] awk 带条件
来源：http://dali.fzhhl.top/Article/details/gtimxnwgcg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cashguo.top/Article/details/gtpmnpgnoy.html

[R50] awk 求和
来源：http://dali.jinqigufen.top/Article/details/gtlvvititn.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yj20258.top/Article/details/gteodshtfs.html

[R51] 排序去重取前几
来源：http://dali.cqqwz.cn/Article/details/gtmwcayeur.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.dashuyun.cn/Article/details/gtrwcuinfo.html

[R52] 统计行数
来源：http://dali.redwolf501.top/Article/details/gtdlpxtnkf.html

wc -l a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtbfywixiv.html

[R53] 查看文件头与实时尾
来源：http://dali.tanke756.top/Article/details/gtgkeuunit.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.chenjidiqi.icu/Article/details/gtejqvdvah.html

[R54] 比较两个文件
来源：http://dali.aizwys.cn/Article/details/gtbnmvtgnd.html

diff a.txt b.txt
来源：http://dali.zhixingplan.top/Article/details/gtndedqmre.html

[R55] 压缩与解压
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpblbiowd.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cqqwz.cn/Article/details/gtvohptrqh.html

[R56] 远程拷贝
来源：http://dali.jianghu66.top/Article/details/gtofqfhugr.html

scp file user@host:/path/
来源：http://dali.yvedp.cn/Article/details/gtureflepi.html

[R57] 远程执行命令
来源：http://dali.jqgufenzy.top/Article/details/gtjwncdntd.html

ssh user@host 'uptime'
来源：http://dali.jinqigfzy.top/Article/details/gtryojmxur.html

[R58] 下载文件
来源：http://dali.zhongyouzk.top/Article/details/gttvjkewal.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.chenzaomai.com/Article/details/gtounihcaw.html

[R59] 发 POST JSON
来源：http://dali.chenzaomai.com/Article/details/gtfxywqyxz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.bjfxy.top/Article/details/gtpxpqxutl.html

[R60] 只看 HTTP 状态码
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxhplfmdf.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ppjwa.cn/Article/details/gtdjhonltb.html

[R61] 磁盘占用
来源：http://dali.jqgfzy.top/Article/details/gtbiduomln.html

df -h;  du -sh *
来源：http://dali.ppjwa.cn/Article/details/gtdfdjwszs.html

[R62] 找最占空间的文件
来源：http://dali.haohaochexian.top/Article/details/gtmpncbmiv.html

du -ah . | sort -rh | head -10
来源：http://dali.ppjwa.cn/Article/details/gtggooaggs.html

[R63] 内存与进程
来源：http://dali.chenzaomai.com/Article/details/gteigwxxvj.html

free -h;  ps aux | grep nginx
来源：http://dali.pycfn.com/Article/details/gtmzpmhkrq.html

[R64] 结束进程
来源：http://dali.hfpthk.cn/Article/details/gtfzcqjjew.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zycfv.cn/Article/details/gtwtgjktgh.html

[R65] 查看端口占用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdkonijpg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.tianlin.xyz/Article/details/gtpamkiykc.html

[R66] 定时任务
来源：http://dali.iojbl.cn/Article/details/gtuwsjkiqn.html

crontab -e;  crontab -l
来源：http://dali.daxiang520.top/Article/details/gttksrdqdi.html

[R67] 生成随机十六进制串
来源：http://dali.yueranfly.top/Article/details/gttkqsunzp.html

openssl rand -hex 16
来源：http://dali.aibaodan.cn/Article/details/gtqohgfuid.html

[R68] 计算文件校验值
来源：http://dali.jlsjyb.cn/Article/details/gtcjwzkbhw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtsgprfjng.html

[R69] 生成随机密码
来源：http://dali.hysaishi.cn/Article/details/gtanardbzu.html


<!-- 参考信息 -->