代发 wailian999

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.yonumen.top/Article/details/gtreogrujo.html

[Q20] IN 列表
来源：http://dali.zycfv.cn/Article/details/gtypmkfnre.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.ppjwa.cn/Article/details/gtbgiktlgw.html

[Q21] 空值判断
来源：http://dali.svipenyu.cn/Article/details/gtuivkqgyy.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.zhengqikj.top/Article/details/gtudxubrbf.html

[Q22] 排序
来源：http://dali.cqqwz.cn/Article/details/gtttbkqaxl.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.yj20258888.top/Article/details/gtliboprla.html

[Q23] 分页
来源：http://dali.yonumen.top/Article/details/gtrxxttaay.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.yvedp.cn/Article/details/gtbnjbcgys.html

[Q24] 去重
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdwypqeym.html

SELECT DISTINCT city FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtpgvezbkm.html

[Q25] 只取前 N 条
来源：http://dali.xziqi.cn/Article/details/gtxvrrnqoz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.jqgufenzy.top/Article/details/gtjmnefiyx.html

[Q26] 计数
来源：http://dali.yanxiufei.cn/Article/details/gtuvopniva.html

SELECT COUNT(*) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgqsaycjn.html

[Q27] 条件计数
来源：http://dali.quarkkingdee.top/Article/details/gtpotuzjdw.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.pycfn.com/Article/details/gtjwizweyo.html

[Q28] 求和与平均
来源：http://dali.ehwqpu.com/Article/details/gtelzztngb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jiagoushi.top/Article/details/gtbmwduygk.html

[Q29] 最大最小值
来源：http://dali.jianghu66.top/Article/details/gthmwdtljd.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtnabvachq.html

[Q30] 分组统计
来源：http://dali.yuxming.cn/Article/details/gtwzsnfiws.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jlsjyb.cn/Article/details/gtaignvpzg.html

[Q31] 分组后过滤
来源：http://dali.sysykeji.top/Article/details/gtatouipoi.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.dashuyun.cn/Article/details/gtpepfvili.html

[Q32] 分组拼接字符串
来源：http://dali.iojbl.cn/Article/details/gtdmvsqqew.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yj20258.top/Article/details/gtgtpstptz.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jinghuilouyu.cn/Article/details/gtdaeiwsyc.html

[Q33] 多列分组
来源：http://dali.hongshengwenyu.top/Article/details/gtlvekgxhl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shangyingyoupin.top/Article/details/gttmeivtzn.html

[Q34] 每组取第一条
来源：http://dali.ywan-chungtsiang.top/Article/details/gtcmtjetit.html

SELECT * FROM (
来源：http://dali.jianghu66.top/Article/details/gtmifshzls.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sweek.top/Article/details/gtjzauuakw.html

) t WHERE rn = 1;
来源：http://dali.dianchejie.cn/Article/details/gtkpqorhjo.html

[Q35] 内连接
来源：http://dali.xylfe.cn/Article/details/gtnybmpcqh.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.feifeiyinyue.top/Article/details/gtngjibhob.html

[Q36] 左连接
来源：http://dali.wangshuangyany.cn/Article/details/gtimjajrjb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.feifeiyinyue.top/Article/details/gtwjriolnb.html

[Q37] 右连接
来源：http://dali.chenlongwang.top/Article/details/gtiuuiuxna.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hywenlv.cn/Article/details/gtmowxysux.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xuanzx.com/Article/details/gtmsbnhday.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jlsjyb.cn/Article/details/gtnonxdkax.html

[Q39] 自连接（查上下级）
来源：http://dali.pengpengdd.cyou/Article/details/gtwrrsweeq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hysaishi.cn/Article/details/gtbaafqkwi.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.hnqzz.top/Article/details/gtdvaxvvpk.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gzhubu.top/Article/details/gtsluxtwyh.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.haohaochexian.top/Article/details/gtwscxsfbs.html

[Q41] 多表连接
来源：http://dali.hongshengwenyu.top/Article/details/gtosnshouo.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.0kj1m.cn/Article/details/gtfwjhydni.html

JOIN users u ON u.id = o.user_id
来源：http://dali.dashuyun.cn/Article/details/gtwiraoctp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.dianchejie.cn/Article/details/gtdtfyqxvh.html

[Q42] 连接条件附加过滤
来源：http://dali.feifeiyinyue.top/Article/details/gtzgcwgjxm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yvedp.cn/Article/details/gttipkuqls.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.redwolf501.top/Article/details/gtkdkpqdlr.html

[Q43] 标量子查询
来源：http://dali.yueranfly.top/Article/details/gthjdvumij.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.wangshuangyany.cn/Article/details/gtyrwzoxml.html

[Q44] IN 子查询
来源：http://dali.yj202588.top/Article/details/gtanxairyp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.c1oappe.top/Article/details/gtvdujvvkx.html

[Q45] EXISTS 判断存在
来源：http://dali.snrcjt.cn/Article/details/gtxkdmyuux.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jlsjyb.cn/Article/details/gtvkmhetje.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xziqi.cn/Article/details/gttjzmtphq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhoulong.xyz/Article/details/gtogtigjct.html

[Q47] 与平均值比较
来源：http://dali.zycfv.cn/Article/details/gtdojtrdcq.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.birdmap.top/Article/details/gtcddwjpkm.html

[Q48] CTE 公用表表达式
来源：http://dali.jianghu66.top/Article/details/gtpooxmtsx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cucudq.cn/Article/details/gtytqwbafn.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gaohongyu789.top/Article/details/gtqkwwspmb.html

[Q49] 更新单行
来源：http://dali.andypj.xyz/Article/details/gtwiyflzvy.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.haohaochexian.top/Article/details/gtynxqmjum.html

[Q50] 批量更新
来源：http://dali.zhengqikj.top/Article/details/gtmxftlnqz.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.gaohongyu789.top/Article/details/gteaowmhgj.html

[Q51] 用子查询更新
来源：http://dali.wangdashe.top/Article/details/gtfpagdixo.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.pengpengdd.cyou/Article/details/gtizcugmpo.html

[Q52] 删除指定行
来源：http://dali.hammf.cn/Article/details/gtrmeriuxb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.cdnleiting.top/Article/details/gtgzxctyll.html

[Q53] 按条件删除
来源：http://dali.yj20258.top/Article/details/gtzyrwqaky.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xinyue.icu/Article/details/gtotkktukx.html

[Q54] 清空表
来源：http://dali.hnqzz.top/Article/details/gtpkuuered.html

TRUNCATE TABLE logs;
来源：http://dali.pengpengdd.cyou/Article/details/gtlcqghmry.html

[Q55] 排名（并列占位）
来源：http://dali.hammf.cn/Article/details/gtfplmssuc.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xylfe.cn/Article/details/gttgftvamb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.nwbrower.top/Article/details/gtffrnqypm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.smart0.xyz/Article/details/gthyfojjfl.html

[Q57] 行号
来源：http://dali.mhx1999.top/Article/details/gtcwqvavdv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gttutflkvm.html

[Q58] 累计求和
来源：http://dali.cdnleiting.top/Article/details/gtiwnrpgff.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hfpthk.cn/Article/details/gtdoxwideg.html

[Q59] 分组内累计
来源：http://dali.chenzaomai.com/Article/details/gtalticcdd.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gtsjyyejyx.html

[Q60] 取上一行 / 下一行
来源：http://dali.xuetiantiany.cn/Article/details/gtzgqrzdao.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.hongshengwenyu.top/Article/details/gtoizmdujk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.aizwys.cn/Article/details/gtgaycpbxn.html

[Q61] 移动平均
来源：http://dali.tian-w.cn/Article/details/gtmhdyrlvr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtyeqsflse.html

[Q62] 分组占比
来源：http://dali.tian-w.cn/Article/details/gtuxykihqq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.gogol.net.cn/Article/details/gthtjbjfrl.html

[Q63] 开启事务
来源：http://dali.shuidangran.top/Article/details/gtdyzphneg.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.nanxinkj.top/Article/details/gtflxpbsaw.html

[Q64] 提交事务
来源：http://dali.fzhhl.top/Article/details/gtyvupbhuw.html

COMMIT;
来源：http://dali.gaohongyu789.top/Article/details/gtcbfbrcfl.html

[Q65] 回滚事务
来源：http://dali.yueranfly.top/Article/details/gttebrstle.html

ROLLBACK;
来源：http://dali.hnqzz.top/Article/details/gtvhybizyz.html

[Q66] 行锁查询
来源：http://dali.redwolf501.top/Article/details/gtxwxodrne.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.daria6918.cn/Article/details/gtfsuljvrn.html

[Q67] 设置隔离级别
来源：http://dali.hysaishi.cn/Article/details/gtyqleyqdm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ppjwa.cn/Article/details/gtjxkqdjeg.html

[Q68] 保存点
来源：http://dali.tanke756.top/Article/details/gtpwjbodbx.html

SAVEPOINT sp1;
来源：http://dali.jyoumei.cn/Article/details/gtsyteiwxv.html

ROLLBACK TO sp1;
来源：http://dali.ppjwa.cn/Article/details/gthjjepjdo.html

[Q69] 查看执行计划
来源：http://dali.hysaishi.cn/Article/details/gtrerucyjl.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gogol.net.cn/Article/details/gtgyuymope.html

[Q70] 更新统计信息
来源：http://dali.guannengcc.top/Article/details/gtbpqfxaki.html

ANALYZE TABLE users;
来源：http://dali.xinyue.icu/Article/details/gtexeyijra.html

[Q71] 查看建表语句
来源：http://dali.cucudq.cn/Article/details/gtigxafedp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yuanzhike.top/Article/details/gtlfdvwyij.html

[Q72] 查看索引
来源：http://dali.tianlin.xyz/Article/details/gthepjrcxa.html

SHOW INDEX FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtmebnztqy.html

[Q73] 查看表状态
来源：http://dali.xziqi.cn/Article/details/gtqafrcfai.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yueranfly.top/Article/details/gtfnacuudj.html

[Q74] 强制使用索引
来源：http://dali.hongshengwenyu.top/Article/details/gtbpegmuep.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbuiceoxm.html

[Q75] 日期格式化
来源：http://dali.xuanzx.com/Article/details/gtgybetksc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yonumen.top/Article/details/gtbkyschus.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhoulong.xyz/Article/details/gtbvnmxlbu.html

[Q76] 按天统计
来源：http://dali.yj20258888.top/Article/details/gtumwbqpgm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yueranfly.top/Article/details/gtdbghwosx.html

[Q77] 时间加减
来源：http://dali.ppjwa.cn/Article/details/gtcwiivhhq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zycfv.cn/Article/details/gtvcqxztxg.html

[Q78] 当前时间
来源：http://dali.fzhhl.top/Article/details/gtozfwobhk.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jyoumei.cn/Article/details/gtwuzvdvyx.html

[Q79] 字符串拼接
来源：http://dali.haohaochexian.top/Article/details/gtzgigirzu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.yvedp.cn/Article/details/gtneqnwyuo.html

[Q80] 字符串截取
来源：http://dali.zdqjudy.top/Article/details/gtgqjtpgok.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.svipenyu.cn/Article/details/gtzjvijqqj.html

[Q81] 字符串替换
来源：http://dali.hnxiangtu.top/Article/details/gtuasvaqct.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtziwucsow.html

[Q82] 字符长度与字节长度
来源：http://dali.hysaishi.cn/Article/details/gtqlzcbxiy.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtlvjhmsul.html

[Q83] 大小写转换
来源：http://dali.zdqjudy.top/Article/details/gtinbgeixx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sweek.top/Article/details/gthmgsziup.html

[Q84] 去除首尾空格
来源：http://dali.andypj.xyz/Article/details/gtyoyehqoe.html

SELECT TRIM(name) FROM users;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcyqekbfa.html

[Q85] 数值取整
来源：http://dali.meibo888.top/Article/details/gtpfiprngf.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.sxryk.cn/Article/details/gtoefdwwtw.html

[Q86] 读取 JSON 字段
来源：http://dali.gogol.net.cn/Article/details/gtnwonjyhu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhengqikj.top/Article/details/gttddgmhmg.html

[Q87] JSON 字段做条件
来源：http://dali.hnxiangtu.top/Article/details/gtttxqetmr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.jlsjyb.cn/Article/details/gtrcmffcjc.html

[Q88] 行转列（条件聚合）
来源：http://dali.yj20258.top/Article/details/gtuhgmypqy.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpqlzjjhk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbjpmbrzt.html

[Q89] 判断表是否存在
来源：http://dali.yangfankeji.com/Article/details/gtikaeaxmy.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jiagoushi.top/Article/details/gtycxrxnzk.html

[Q90] 生成序号列
来源：http://dali.fengsongda.top/Article/details/gtfuasczev.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.aibaodan.cn/Article/details/gtjksgsgvh.html

================================================================================
来源：http://dali.feifeiyinyue.top/Article/details/gtwfdpwfhk.html

R. Bash 专题
来源：http://dali.nanxinkj.top/Article/details/gtiwqxfvzm.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtmhdbemhn.html

[R01] shebang 与严格模式
来源：http://dali.cheryme.top/Article/details/gtqaxnytlr.html

#!/usr/bin/env bash
来源：http://dali.gzhubu.top/Article/details/gtyjtdubnf.html

set -euo pipefail
来源：http://dali.yuanzhike.top/Article/details/gtuqtdjygv.html

[R02] 变量赋值与使用
来源：http://dali.yj202588.top/Article/details/gtobjfhagz.html

name="Tom"; echo "$name"
来源：http://dali.yonumen.top/Article/details/gtymbuxlfo.html

[R03] 只读变量
来源：http://dali.c1oappe.top/Article/details/gtfcxotzvo.html

readonly PI=3.14
来源：http://dali.ybcxt.top/Article/details/gtyutontgn.html

[R04] 位置参数
来源：http://dali.jiagoushi.top/Article/details/gtovvxjyds.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.sweek.top/Article/details/gtziqzeyst.html

[R05] 参数默认值
来源：http://dali.vqdsnc.cn/Article/details/gtchwjqovt.html

name="${1:-default}"
来源：http://dali.sufxvd.cn/Article/details/gtdhkpbpgc.html

[R06] 判断命令是否存在
来源：http://dali.smart0.xyz/Article/details/gtmnsenppb.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hnxiangtu.top/Article/details/gtknurygnu.html

[R07] if 判断文件
来源：http://dali.yueranfly.top/Article/details/gtiqvtkunn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.wangshuangyany.cn/Article/details/gtjejxzqzn.html

[R08] 数值比较
来源：http://dali.jqgfzy.top/Article/details/gtuonegoxz.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yuxming.cn/Article/details/gtjdlykvwy.html

[R09] 字符串比较
来源：http://dali.hysaishi.cn/Article/details/gtrgjjvrga.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.shanyushiyangtech.top/Article/details/gtarvlmxqe.html

[R10] 正则匹配
来源：http://dali.jiagoushi.top/Article/details/gtihjhnebj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.fengsongda.top/Article/details/gtbeuuolrf.html

[R11] case 多分支
来源：http://dali.dianchejie.cn/Article/details/gttsbtichc.html

case "$1" in
来源：http://dali.zycfv.cn/Article/details/gtjcagahfi.html

start) echo "启动" ;;
来源：http://dali.yanxiufei.cn/Article/details/gtsbjilupy.html

stop)  echo "停止" ;;
来源：http://dali.zycfv.cn/Article/details/gtqlhdqwcg.html

*)     echo "未知命令" ;;
来源：http://dali.zhongyouzk.top/Article/details/gtddpqrhch.html

esac
来源：http://dali.xuanzx.com/Article/details/gtqvujkwfq.html

[R12] for 遍历文件
来源：http://dali.pengpengdd.cyou/Article/details/gtzafvhjia.html

for f in *.txt; do echo "$f"; done
来源：http://dali.fzhhl.top/Article/details/gtanenuowz.html

[R13] for 计数循环
来源：http://dali.andypj.xyz/Article/details/gtsromawwq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.cucudq.cn/Article/details/gtmwfiuqwy.html

[R14] C 风格 for
来源：http://dali.quarkkingdee.top/Article/details/gtjozzbaem.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhongyouzk.top/Article/details/gtrfyyukss.html

[R15] while 逐行读文件
来源：http://dali.yuxming.cn/Article/details/gtchvwmegu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.hysaishi.cn/Article/details/gtzbvxkolr.html

[R16] until 等待条件
来源：http://dali.yvedp.cn/Article/details/gtmbytkoap.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.snrcjt.cn/Article/details/gtdgnavkhu.html

[R17] 数组定义与取值
来源：http://dali.hnxiangtu.top/Article/details/gtdhnsjtkq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.redwolf501.top/Article/details/gtfwgpqoir.html

[R18] 遍历数组
来源：http://dali.0kj1m.cn/Article/details/gtrkwpumcb.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.316326.xyz/Article/details/gtuwwaywdu.html

[R19] 数组长度
来源：http://dali.zhongyouzk.top/Article/details/gtquojsuql.html

echo "${#arr[@]}"
来源：http://dali.bjfxy.top/Article/details/gtumnyqept.html

[R20] 关联数组（字典）
来源：http://dali.dianchejie.cn/Article/details/gtxowqhuzr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.tian-w.cn/Article/details/gtyiooxijj.html

[R21] 字符串长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmogjgzan.html

echo "${#s}"
来源：http://dali.sxryk.cn/Article/details/gtwencpyvh.html

[R22] 截取子串
来源：http://dali.yuxming.cn/Article/details/gtfrzmojwd.html

echo "${s:0:5}"
来源：http://dali.sysykeji.top/Article/details/gtzmazrolo.html

[R23] 字符串替换
来源：http://dali.ywan-chungtsiang.top/Article/details/gttnbyksiz.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.xuetiantiany.cn/Article/details/gthjdglkig.html

[R24] 大小写转换
来源：http://dali.hnqzz.top/Article/details/gtvuyxarcr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.gaohongyu789.top/Article/details/gtdllxxsvd.html

[R25] 去后缀 / 去前缀
来源：http://dali.xylfe.cn/Article/details/gtuwfohlze.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtbrptueya.html

[R26] 命令替换
来源：http://dali.ydzc1.top/Article/details/gtbgcwmqxw.html

now=$(date +%F); echo "$now"
来源：http://dali.cheryme.top/Article/details/gtqglqnjmu.html

[R27] 算术展开
来源：http://dali.yuanzhike.top/Article/details/gtlijpztdy.html

echo $((1 + 2 * 3))
来源：http://dali.hnxiangtu.top/Article/details/gtsfrtaqml.html

[R28] 浮点运算
来源：http://dali.tanke756.top/Article/details/gtqpbaiztr.html

echo "scale=2; 10/3" | bc
来源：http://dali.tanke756.top/Article/details/gtvqmdobqg.html

[R29] 定义函数
来源：http://dali.sweek.top/Article/details/gtlgnddxds.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhoulong.xyz/Article/details/gtuuswngzd.html

[R30] 函数返回状态码
来源：http://dali.haohaochexian.top/Article/details/gtamrrmvjk.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.nanxinkj.top/Article/details/gtfvlnsrnb.html

[R31] 局部变量
来源：http://dali.yueranfly.top/Article/details/gtzylexbau.html

f() { local x=1; echo "$x"; }
来源：http://dali.ivvv.top/Article/details/gtutubkdlc.html

[R32] 参数个数校验
来源：http://dali.316326.xyz/Article/details/gtbveryoqo.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrjpgccnp.html

[R33] 捕获错误并提示行号
来源：http://dali.chenjidiqi.icu/Article/details/gtavasbktf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gotoacloud.top/Article/details/gtdzaijmmn.html

[R34] 退出时清理
来源：http://dali.shanyushiyangkeji.top/Article/details/gthauspfmr.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.pengpengdd.cyou/Article/details/gtdmbdhqxr.html

[R35] 后台执行并等待
来源：http://dali.yj202588.top/Article/details/gtmbawumde.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zycfv.cn/Article/details/gtlywzifou.html

[R36] 并发执行多个任务
来源：http://dali.0kj1m.cn/Article/details/gtqowoixvb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.dianchejie.cn/Article/details/gtpznlexcx.html

[R37] 把输出赋给变量
来源：http://dali.nanxinkj.top/Article/details/gtonijaqxw.html

files=$(ls -1)
来源：http://dali.yj202588.top/Article/details/gtvypdwshb.html

[R38] 管道串联
来源：http://dali.yj20258888.top/Article/details/gtiildbcry.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jianghu66.top/Article/details/gtznpbbctl.html

[R39] 重定向标准输出与错误
来源：http://dali.wangdashe.top/Article/details/gtcapgeezy.html

cmd > out.log 2>&1
来源：http://dali.yj20258.top/Article/details/gtbhexvzoc.html

[R40] 追加写日志
来源：http://dali.tianlin.xyz/Article/details/gtaickkslh.html

echo "log" >> out.log
来源：http://dali.fengsongda.top/Article/details/gtfkrddbfe.html

[R41] 丢弃输出
来源：http://dali.ybcxt.top/Article/details/gtoowwhcbx.html

cmd >/dev/null 2>&1
来源：http://dali.mhx1999.top/Article/details/gtgkoaygsz.html

[R42] 输入重定向
来源：http://dali.zhixingplan.top/Article/details/gtahgcxpxa.html

wc -l < a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtxxnaahrv.html

[R43] 按名字查找文件
来源：http://dali.shangyingyoupin.top/Article/details/gtencjzkcu.html

find . -name "*.log" -type f
来源：http://dali.bjfxy.top/Article/details/gtzunhmidq.html

[R44] 按修改时间查找
来源：http://dali.9152youxi.cn/Article/details/gtxrqopmsk.html

find . -mtime -7 -type f
来源：http://dali.nanxuanxn.top/Article/details/gtiqxbobfx.html

[R45] 批量删除
来源：http://dali.zhengqikj.top/Article/details/gtolfubgiu.html

find . -name "*.tmp" -delete
来源：http://dali.kuanghao11.cn/Article/details/gtalprlthd.html

[R46] 递归替换文件内容
来源：http://dali.ybcxt.top/Article/details/gtvittjewh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.ybcxt.top/Article/details/gtlvydibsa.html

[R47] sed 单行替换
来源：http://dali.hnqzz.top/Article/details/gtynskwezv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtdppfxpsz.html

[R48] awk 取指定列
来源：http://dali.shzxlz.cn/Article/details/gtdhuakvrw.html

awk '{print $1, $3}' a.txt
来源：http://dali.hywenlv.cn/Article/details/gtwnpisvxs.html

[R49] awk 带条件
来源：http://dali.hongshengwenyu.top/Article/details/gtbyqassyu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.svipenyu.cn/Article/details/gtulfnnyhc.html

[R50] awk 求和
来源：http://dali.tanke756.top/Article/details/gtvkizjoqi.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtvzlobnnq.html

[R51] 排序去重取前几
来源：http://dali.xziqi.cn/Article/details/gtsihiakue.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhoulong.xyz/Article/details/gttdrxomxm.html

[R52] 统计行数
来源：http://dali.jiagoushi.top/Article/details/gtcjfujoxq.html

wc -l a.txt
来源：http://dali.chenlongwang.top/Article/details/gtaxekbnpi.html

[R53] 查看文件头与实时尾
来源：http://dali.hongshengwenyu.top/Article/details/gtpahhvhpw.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yvedp.cn/Article/details/gtvffsanyr.html

[R54] 比较两个文件
来源：http://dali.yanxiufei.cn/Article/details/gtivfdyyer.html

diff a.txt b.txt
来源：http://dali.yj20258.top/Article/details/gtoebgessp.html

[R55] 压缩与解压
来源：http://dali.haohaochexian.top/Article/details/gtjksaninb.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yonumen.top/Article/details/gtomswzbpn.html

[R56] 远程拷贝
来源：http://dali.jinghuilouyu.cn/Article/details/gtsurghvgp.html

scp file user@host:/path/
来源：http://dali.jianghu66.top/Article/details/gtfghekbdf.html

[R57] 远程执行命令
来源：http://dali.gzhubu.top/Article/details/gtuglmquqt.html

ssh user@host 'uptime'
来源：http://dali.shangyingyoupin.top/Article/details/gtwqxciufz.html

[R58] 下载文件
来源：http://dali.316326.xyz/Article/details/gtgpgebwoi.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.316326.xyz/Article/details/gthccspuhy.html

[R59] 发 POST JSON
来源：http://dali.jinqigfzy.top/Article/details/gtdqmxehea.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.tian-w.cn/Article/details/gtyfavwghs.html

[R60] 只看 HTTP 状态码
来源：http://dali.cheryme.top/Article/details/gtyfkxeone.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.feifeiyinyue.top/Article/details/gtuyfdngdy.html

[R61] 磁盘占用
来源：http://dali.cucudq.cn/Article/details/gthnlbhdpa.html

df -h;  du -sh *
来源：http://dali.aizwys.cn/Article/details/gtuquswstu.html

[R62] 找最占空间的文件
来源：http://dali.jinqigfzy.top/Article/details/gtrezyucni.html

du -ah . | sort -rh | head -10
来源：http://dali.sysykeji.top/Article/details/gtqfsdltjn.html

[R63] 内存与进程
来源：http://dali.wangshuangyany.cn/Article/details/gtpbrvhvqj.html

free -h;  ps aux | grep nginx
来源：http://dali.gotoacloud.top/Article/details/gtdvoyrfhv.html

[R64] 结束进程
来源：http://dali.xylfe.cn/Article/details/gthoxayuwd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yj20258.top/Article/details/gttqdzvnxd.html

[R65] 查看端口占用
来源：http://dali.tianlin.xyz/Article/details/gtbmaznuzg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.fzhhl.top/Article/details/gtozabcfbx.html

[R66] 定时任务
来源：http://dali.daxiang520.top/Article/details/gtefkyheaf.html

crontab -e;  crontab -l
来源：http://dali.hammf.cn/Article/details/gtyeovlqam.html

[R67] 生成随机十六进制串
来源：http://dali.dashuyun.cn/Article/details/gtxcmajayk.html

openssl rand -hex 16
来源：http://dali.shangyingyoupin.top/Article/details/gtjvqlupgo.html

[R68] 计算文件校验值
来源：http://dali.gaohongyu789.top/Article/details/gtlyplfwlo.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.tian-w.cn/Article/details/gtxttoungh.html

[R69] 生成随机密码
来源：http://dali.cheryme.top/Article/details/gtqngrewez.html


<!-- 参考信息 -->