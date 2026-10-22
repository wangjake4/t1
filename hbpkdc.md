代发 wailian999

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.jinqigufen.top/Article/details/gtsivsmeow.html

[Q24] 去重
来源：http://dali.wangdashe.top/Article/details/gtnmudxezq.html

SELECT DISTINCT city FROM users;
来源：http://dali.vqdsnc.cn/Article/details/gtyslarbfs.html

[Q25] 只取前 N 条
来源：http://dali.fzhhl.top/Article/details/gtqiggcclz.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.daxiang520.top/Article/details/gtsdfwkxcj.html

[Q26] 计数
来源：http://dali.zdqjudy.top/Article/details/gtaomxhbau.html

SELECT COUNT(*) FROM users;
来源：http://dali.cheryme.top/Article/details/gtnkjqoqrb.html

[Q27] 条件计数
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfglcaekf.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtgtzaalgp.html

[Q28] 求和与平均
来源：http://dali.shzxlz.cn/Article/details/gtlwibtiqx.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.cashguo.top/Article/details/gtvidkukrp.html

[Q29] 最大最小值
来源：http://dali.sweek.top/Article/details/gttczcvczb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.yueranfly.top/Article/details/gtdhackrva.html

[Q30] 分组统计
来源：http://dali.yj202588.top/Article/details/gtpshmfqih.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sxryk.cn/Article/details/gtmyrykdru.html

[Q31] 分组后过滤
来源：http://dali.hnqzz.top/Article/details/gtsboiafli.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.vqdsnc.cn/Article/details/gtamkvnqds.html

[Q32] 分组拼接字符串
来源：http://dali.gzhubu.top/Article/details/gtfxwhxqlk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.jinqigufen.top/Article/details/gtgykgbzph.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.wangshuangyany.cn/Article/details/gtbsibatez.html

[Q33] 多列分组
来源：http://dali.chenjidiqi.icu/Article/details/gtmkmqcgzv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xuetiantiany.cn/Article/details/gtkmdrlcnj.html

[Q34] 每组取第一条
来源：http://dali.gzhubu.top/Article/details/gtsqtbloun.html

SELECT * FROM (
来源：http://dali.cdnleiting.top/Article/details/gthxgisqbw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cdnleiting.top/Article/details/gteaacqvjm.html

) t WHERE rn = 1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtxmsfqqqe.html

[Q35] 内连接
来源：http://dali.sufxvd.cn/Article/details/gtrptvmzmm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hammf.cn/Article/details/gtufuwkapk.html

[Q36] 左连接
来源：http://dali.svipenyu.cn/Article/details/gtokgnqpwm.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.tianlin.xyz/Article/details/gtskvtwbky.html

[Q37] 右连接
来源：http://dali.yangfankeji.com/Article/details/gtmwgwydme.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.nwbrower.top/Article/details/gtlrqcsgsy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.zhoulong.xyz/Article/details/gtuipvecsh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrlgskxvv.html

[Q39] 自连接（查上下级）
来源：http://dali.hongshengwenyu.top/Article/details/gtgjymhbix.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.yangfankeji.com/Article/details/gtumdyhhba.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.wangdashe.top/Article/details/gtcqkyxtlz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xziqi.cn/Article/details/gtyixvjskb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hywenlv.cn/Article/details/gtoishfoik.html

[Q41] 多表连接
来源：http://dali.ydzc1.top/Article/details/gtckqohonr.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yvedp.cn/Article/details/gttjopubft.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sweek.top/Article/details/gtkgjxccwb.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yj20258.top/Article/details/gteqcfvxbx.html

[Q42] 连接条件附加过滤
来源：http://dali.tianlin.xyz/Article/details/gtbfofnotx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yj20258.top/Article/details/gtmrpgnddr.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zdqjudy.top/Article/details/gtmxbaqsxp.html

[Q43] 标量子查询
来源：http://dali.yongpay.top/Article/details/gtourgtxsg.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yj20258888.top/Article/details/gtnpurhavq.html

[Q44] IN 子查询
来源：http://dali.nanxinkj.top/Article/details/gtfsefvaro.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yonumen.top/Article/details/gtekhhtfcz.html

[Q45] EXISTS 判断存在
来源：http://dali.fengsongda.top/Article/details/gtruhrjtja.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj20258.top/Article/details/gtkqcnlksi.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ppjwa.cn/Article/details/gtwvuevabo.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hongshengwenyu.top/Article/details/gtibmzpkik.html

[Q47] 与平均值比较
来源：http://dali.zdqjudy.top/Article/details/gtsjcaxzeo.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.ybcxt.top/Article/details/gtewqecnay.html

[Q48] CTE 公用表表达式
来源：http://dali.jyoumei.cn/Article/details/gtalwikgrl.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.bjfxy.top/Article/details/gtinkrszdt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.guowangkeji.top/Article/details/gtvynlmmyd.html

[Q49] 更新单行
来源：http://dali.jinqigufen.top/Article/details/gtllbztopk.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xuanzx.com/Article/details/gtrntlfypr.html

[Q50] 批量更新
来源：http://dali.hnxiangtu.top/Article/details/gtxzrjnzfc.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ydzc1.top/Article/details/gtutulkgzx.html

[Q51] 用子查询更新
来源：http://dali.jyoumei.cn/Article/details/gtxiyaktzl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zdqjudy.top/Article/details/gtcdvsrdxc.html

[Q52] 删除指定行
来源：http://dali.zdqjudy.top/Article/details/gteuoqoyel.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yueranfly.top/Article/details/gtmdiuormy.html

[Q53] 按条件删除
来源：http://dali.snrcjt.cn/Article/details/gtvnjyebhh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.yueranfly.top/Article/details/gtokmjwhdf.html

[Q54] 清空表
来源：http://dali.dashuyun.cn/Article/details/gtwyrrbphj.html

TRUNCATE TABLE logs;
来源：http://dali.hywenlv.cn/Article/details/gtenofvwpk.html

[Q55] 排名（并列占位）
来源：http://dali.hnxiangtu.top/Article/details/gtcmonayqi.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.nwbrower.top/Article/details/gtmgynfqtd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xuetiantiany.cn/Article/details/gtkulbqneh.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yanxiufei.cn/Article/details/gtvryvfwvx.html

[Q57] 行号
来源：http://dali.vqdsnc.cn/Article/details/gtyryybuxv.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zhengqikj.top/Article/details/gtxgbqxtak.html

[Q58] 累计求和
来源：http://dali.guowangkeji.top/Article/details/gtanzhtlnl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtdrrxflwt.html

[Q59] 分组内累计
来源：http://dali.hammf.cn/Article/details/gtnbysqvbe.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.fengsongda.top/Article/details/gtmirrxjal.html

[Q60] 取上一行 / 下一行
来源：http://dali.nwbrower.top/Article/details/gtjdborcra.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.daxiang520.top/Article/details/gtgiftayxc.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shzxlz.cn/Article/details/gtxlcvsxuu.html

[Q61] 移动平均
来源：http://dali.gzhubu.top/Article/details/gtgvyuluok.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtxbjlpfau.html

[Q62] 分组占比
来源：http://dali.meibo888.top/Article/details/gtmaycdofn.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.cashguo.top/Article/details/gtqjvazcsi.html

[Q63] 开启事务
来源：http://dali.cashguo.top/Article/details/gtcufpmdrw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.gotoacloud.top/Article/details/gtfanltowc.html

[Q64] 提交事务
来源：http://dali.jinqigfzy.top/Article/details/gtuqlcbrtp.html

COMMIT;
来源：http://dali.yj202588.top/Article/details/gtmyisokvm.html

[Q65] 回滚事务
来源：http://dali.0kj1m.cn/Article/details/gtfccapvya.html

ROLLBACK;
来源：http://dali.kuanghao11.cn/Article/details/gtfsxgczig.html

[Q66] 行锁查询
来源：http://dali.kuanghao11.cn/Article/details/gtjrsgxzpq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.smart0.xyz/Article/details/gtelfhyfxe.html

[Q67] 设置隔离级别
来源：http://dali.chenlongwang.top/Article/details/gtxhgjbqbh.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.fzhhl.top/Article/details/gtxlblisoc.html

[Q68] 保存点
来源：http://dali.jiagoushi.top/Article/details/gtidwmcgjf.html

SAVEPOINT sp1;
来源：http://dali.gogol.net.cn/Article/details/gtkwncwhad.html

ROLLBACK TO sp1;
来源：http://dali.chenlongwang.top/Article/details/gtlpksytzv.html

[Q69] 查看执行计划
来源：http://dali.xuanzx.com/Article/details/gtrqydxped.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlqncqhns.html

[Q70] 更新统计信息
来源：http://dali.yongpay.top/Article/details/gtkiikxvfp.html

ANALYZE TABLE users;
来源：http://dali.tanke756.top/Article/details/gtokbzyhpz.html

[Q71] 查看建表语句
来源：http://dali.hongshengwenyu.top/Article/details/gtcqyeoouh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.fengsongda.top/Article/details/gtwhjyujdn.html

[Q72] 查看索引
来源：http://dali.chenlongwang.top/Article/details/gtjwzdxrhf.html

SHOW INDEX FROM users;
来源：http://dali.jianghu66.top/Article/details/gthwawdqch.html

[Q73] 查看表状态
来源：http://dali.ydzc1.top/Article/details/gtxbpocfyy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hnxiangtu.top/Article/details/gtrjkhmkra.html

[Q74] 强制使用索引
来源：http://dali.zhoulong.xyz/Article/details/gtyezydwvv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jianghu66.top/Article/details/gtdlbdtdye.html

[Q75] 日期格式化
来源：http://dali.316326.xyz/Article/details/gtyiqpfgza.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.iojbl.cn/Article/details/gtlujberxx.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhoulong.xyz/Article/details/gtqjhzqraq.html

[Q76] 按天统计
来源：http://dali.smart0.xyz/Article/details/gtzjanimft.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hnqzz.top/Article/details/gtpjcrnqcv.html

[Q77] 时间加减
来源：http://dali.hongshengwenyu.top/Article/details/gtczwnifev.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jiagoushi.top/Article/details/gtfyhstarv.html

[Q78] 当前时间
来源：http://dali.zhoulong.xyz/Article/details/gtfijhhpwj.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yonumen.top/Article/details/gtfifxxbkn.html

[Q79] 字符串拼接
来源：http://dali.hammf.cn/Article/details/gtxxkquzzs.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jianghu66.top/Article/details/gtpnwdfsec.html

[Q80] 字符串截取
来源：http://dali.fzhhl.top/Article/details/gtbcejrzam.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtqfjxbqjy.html

[Q81] 字符串替换
来源：http://dali.chenjidiqi.icu/Article/details/gtsdfvtmnk.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gthapyjqql.html

[Q82] 字符长度与字节长度
来源：http://dali.0kj1m.cn/Article/details/gtuuenkmns.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gthamzimfy.html

[Q83] 大小写转换
来源：http://dali.aizwys.cn/Article/details/gtjnycvyac.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.0kj1m.cn/Article/details/gtjdojobwx.html

[Q84] 去除首尾空格
来源：http://dali.gogol.net.cn/Article/details/gttmcyjxuy.html

SELECT TRIM(name) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtevonbtno.html

[Q85] 数值取整
来源：http://dali.quarkkingdee.top/Article/details/gtfearrkae.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhengqikj.top/Article/details/gtajxsvlww.html

[Q86] 读取 JSON 字段
来源：http://dali.shanyushiyangtech.top/Article/details/gtajwdmfra.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xinyue.icu/Article/details/gtlvgvznin.html

[Q87] JSON 字段做条件
来源：http://dali.316326.xyz/Article/details/gttdkidtin.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpgvaxrky.html

[Q88] 行转列（条件聚合）
来源：http://dali.tanke756.top/Article/details/gtunpvscou.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.guowangkeji.top/Article/details/gtnyjjzbkl.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtrwjzepgp.html

[Q89] 判断表是否存在
来源：http://dali.jlsjyb.cn/Article/details/gtknyasplc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.0kj1m.cn/Article/details/gtmdbitpmj.html

[Q90] 生成序号列
来源：http://dali.yj202588.top/Article/details/gtpuercysb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.316326.xyz/Article/details/gtdtzkblmj.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtxjlxdolh.html

R. Bash 专题
来源：http://dali.wangdashe.top/Article/details/gtvzwnssab.html

================================================================================
来源：http://dali.xuetiantiany.cn/Article/details/gteebqiqut.html

[R01] shebang 与严格模式
来源：http://dali.havefunace.top/Article/details/gtrxijcqbx.html

#!/usr/bin/env bash
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwecnsgtd.html

set -euo pipefail
来源：http://dali.guowangkeji.top/Article/details/gtlnnnvvre.html

[R02] 变量赋值与使用
来源：http://dali.wangshuangyany.cn/Article/details/gtpwumcfmj.html

name="Tom"; echo "$name"
来源：http://dali.cucudq.cn/Article/details/gttxjkuroe.html

[R03] 只读变量
来源：http://dali.xuetiantiany.cn/Article/details/gthtfqsxba.html

readonly PI=3.14
来源：http://dali.wangshuangyany.cn/Article/details/gtgcqeqrzl.html

[R04] 位置参数
来源：http://dali.guowangkeji.top/Article/details/gtdoxueppf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jqgfzy.top/Article/details/gttjtvkcfg.html

[R05] 参数默认值
来源：http://dali.sweek.top/Article/details/gtbbsxapkg.html

name="${1:-default}"
来源：http://dali.haohaochexian.top/Article/details/gtkouuiqir.html

[R06] 判断命令是否存在
来源：http://dali.0kj1m.cn/Article/details/gtvuapakqj.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jqgfzy.top/Article/details/gtpumjghsf.html

[R07] if 判断文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgwjekmmf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.havefunace.top/Article/details/gtkcismpvz.html

[R08] 数值比较
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuuwkqibk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cucudq.cn/Article/details/gtldbvjuhi.html

[R09] 字符串比较
来源：http://dali.hysaishi.cn/Article/details/gtnzgoxoqd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.haohaochexian.top/Article/details/gtlybdooay.html

[R10] 正则匹配
来源：http://dali.shzxlz.cn/Article/details/gtmpjhimyd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.dianchejie.cn/Article/details/gtltxskcue.html

[R11] case 多分支
来源：http://dali.shuidangran.top/Article/details/gtjlkbjxyc.html

case "$1" in
来源：http://dali.jqgfzy.top/Article/details/gtqrmrmquq.html

start) echo "启动" ;;
来源：http://dali.jianghu66.top/Article/details/gttcuibxng.html

stop)  echo "停止" ;;
来源：http://dali.jinqigfzy.top/Article/details/gtkhgfybxz.html

*)     echo "未知命令" ;;
来源：http://dali.hnxiangtu.top/Article/details/gterguxvpc.html

esac
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjcsalred.html

[R12] for 遍历文件
来源：http://dali.aizwys.cn/Article/details/gtyesxpspj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gotoacloud.top/Article/details/gtajqttxyy.html

[R13] for 计数循环
来源：http://dali.aizwys.cn/Article/details/gtltlrpqdu.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.sxryk.cn/Article/details/gtxcfdrquy.html

[R14] C 风格 for
来源：http://dali.jiagoushi.top/Article/details/gtzlqtihyj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gogol.net.cn/Article/details/gtlbycmqzk.html

[R15] while 逐行读文件
来源：http://dali.zhixingplan.top/Article/details/gtzfjvmllv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.iojbl.cn/Article/details/gtqlilhwqz.html

[R16] until 等待条件
来源：http://dali.havefunace.top/Article/details/gtayuwgpso.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.xuanzx.com/Article/details/gtzadfpxgb.html

[R17] 数组定义与取值
来源：http://dali.fzhhl.top/Article/details/gtpjrrrhxy.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.snrcjt.cn/Article/details/gtethwxyck.html

[R18] 遍历数组
来源：http://dali.cashguo.top/Article/details/gtrhnfawha.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ppjwa.cn/Article/details/gttcpcjiee.html

[R19] 数组长度
来源：http://dali.yj20258888.top/Article/details/gtsplborjs.html

echo "${#arr[@]}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtskkzhzaf.html

[R20] 关联数组（字典）
来源：http://dali.316326.xyz/Article/details/gtmyboonrw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cqqwz.cn/Article/details/gtrlwjpgbq.html

[R21] 字符串长度
来源：http://dali.guowangkeji.top/Article/details/gtxkpizrix.html

echo "${#s}"
来源：http://dali.shzxlz.cn/Article/details/gtsiishwqp.html

[R22] 截取子串
来源：http://dali.yj20258888.top/Article/details/gtsdvxtwqo.html

echo "${s:0:5}"
来源：http://dali.hnxiangtu.top/Article/details/gtwhmyyudg.html

[R23] 字符串替换
来源：http://dali.jqgufenzy.top/Article/details/gtxihbwsdo.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gaohongyu789.top/Article/details/gtiscvgooh.html

[R24] 大小写转换
来源：http://dali.birdmap.top/Article/details/gtqmhjthnz.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.pycfn.com/Article/details/gtndfypops.html

[R25] 去后缀 / 去前缀
来源：http://dali.sysykeji.top/Article/details/gtvdbstner.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ppjwa.cn/Article/details/gtkzjjdkga.html

[R26] 命令替换
来源：http://dali.smart0.xyz/Article/details/gtyuuomkbt.html

now=$(date +%F); echo "$now"
来源：http://dali.yonumen.top/Article/details/gtpmgsofhl.html

[R27] 算术展开
来源：http://dali.zhixingplan.top/Article/details/gtrlxfytlc.html

echo $((1 + 2 * 3))
来源：http://dali.meibo888.top/Article/details/gtsgsvkcej.html

[R28] 浮点运算
来源：http://dali.andypj.xyz/Article/details/gtpzqvtlve.html

echo "scale=2; 10/3" | bc
来源：http://dali.snrcjt.cn/Article/details/gtpllarpsv.html

[R29] 定义函数
来源：http://dali.andypj.xyz/Article/details/gttbrflcrq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.havefunace.top/Article/details/gtkqnzfxwx.html

[R30] 函数返回状态码
来源：http://dali.yj20258.top/Article/details/gtqggcqptc.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.dashuyun.cn/Article/details/gthemuhlyy.html

[R31] 局部变量
来源：http://dali.yongpay.top/Article/details/gtjhocvgtj.html

f() { local x=1; echo "$x"; }
来源：http://dali.cucudq.cn/Article/details/gtvcacphmw.html

[R32] 参数个数校验
来源：http://dali.zhongyouzk.top/Article/details/gtofubwtmg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.kuanghao11.cn/Article/details/gthngitlbx.html

[R33] 捕获错误并提示行号
来源：http://dali.guannengcc.top/Article/details/gtijkesysj.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.nwbrower.top/Article/details/gtxitxefkx.html

[R34] 退出时清理
来源：http://dali.nanxuanxn.top/Article/details/gtsedfpsbc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.wangdashe.top/Article/details/gtsugrhuzo.html

[R35] 后台执行并等待
来源：http://dali.iojbl.cn/Article/details/gtpeenoquu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.svipenyu.cn/Article/details/gtrecnzijg.html

[R36] 并发执行多个任务
来源：http://dali.jinqigfzy.top/Article/details/gtwsolqxau.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.pycfn.com/Article/details/gtystmbuhf.html

[R37] 把输出赋给变量
来源：http://dali.fengsongda.top/Article/details/gtltukraqb.html

files=$(ls -1)
来源：http://dali.ybcxt.top/Article/details/gtdbasbyzl.html

[R38] 管道串联
来源：http://dali.zhoulong.xyz/Article/details/gtziippnnb.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jiagoushi.top/Article/details/gtphfinwtb.html

[R39] 重定向标准输出与错误
来源：http://dali.zhiwuduotai.top/Article/details/gtsxjuawdy.html

cmd > out.log 2>&1
来源：http://dali.cucudq.cn/Article/details/gtgohmyepj.html

[R40] 追加写日志
来源：http://dali.hongshengwenyu.top/Article/details/gthyhvorto.html

echo "log" >> out.log
来源：http://dali.hongshengwenyu.top/Article/details/gtwqjqisjj.html

[R41] 丢弃输出
来源：http://dali.yuanzhike.top/Article/details/gtdqwqjvuu.html

cmd >/dev/null 2>&1
来源：http://dali.zycfv.cn/Article/details/gtgkpsfjru.html

[R42] 输入重定向
来源：http://dali.hnqzz.top/Article/details/gtgjvbdnno.html

wc -l < a.txt
来源：http://dali.hammf.cn/Article/details/gtxvdynqit.html

[R43] 按名字查找文件
来源：http://dali.jlsjyb.cn/Article/details/gtfesfqumy.html

find . -name "*.log" -type f
来源：http://dali.jlsjyb.cn/Article/details/gtmcdfyhiu.html

[R44] 按修改时间查找
来源：http://dali.yj20258888.top/Article/details/gtjbkxjcbs.html

find . -mtime -7 -type f
来源：http://dali.birdmap.top/Article/details/gtmzippobb.html

[R45] 批量删除
来源：http://dali.fzhhl.top/Article/details/gtppalgysk.html

find . -name "*.tmp" -delete
来源：http://dali.sufxvd.cn/Article/details/gtcumdefvh.html

[R46] 递归替换文件内容
来源：http://dali.guowangkeji.top/Article/details/gterzrkien.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zycfv.cn/Article/details/gtxaiyetcm.html

[R47] sed 单行替换
来源：http://dali.hfpthk.cn/Article/details/gtomvqibpr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.nanxinkj.top/Article/details/gtuueuqdvs.html

[R48] awk 取指定列
来源：http://dali.sxryk.cn/Article/details/gtzbwzjjrm.html

awk '{print $1, $3}' a.txt
来源：http://dali.chenzaomai.com/Article/details/gtbatawipl.html

[R49] awk 带条件
来源：http://dali.ydzc1.top/Article/details/gtpljgpfze.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlzcwspwd.html

[R50] awk 求和
来源：http://dali.shangyingyoupin.top/Article/details/gtnskejpxw.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ehwqpu.com/Article/details/gtlahlksuj.html

[R51] 排序去重取前几
来源：http://dali.kuanghao11.cn/Article/details/gtpgkwvaea.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ivvv.top/Article/details/gtxdogxahk.html

[R52] 统计行数
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtonqqhbvf.html

wc -l a.txt
来源：http://dali.ivvv.top/Article/details/gtubablbrk.html

[R53] 查看文件头与实时尾
来源：http://dali.zdqjudy.top/Article/details/gtmzyfgbdi.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.aizwys.cn/Article/details/gttkhrbyub.html

[R54] 比较两个文件
来源：http://dali.kuanghao11.cn/Article/details/gtislxpbcp.html

diff a.txt b.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfegaikzx.html

[R55] 压缩与解压
来源：http://dali.xuanzx.com/Article/details/gtivdsyhpo.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.andypj.xyz/Article/details/gtjzydzswn.html

[R56] 远程拷贝
来源：http://dali.ppjwa.cn/Article/details/gtfqbfkhis.html

scp file user@host:/path/
来源：http://dali.pycfn.com/Article/details/gtbtzgwfkm.html

[R57] 远程执行命令
来源：http://dali.aibaodan.cn/Article/details/gtbhpziugi.html

ssh user@host 'uptime'
来源：http://dali.hnxiangtu.top/Article/details/gtjfvuppnm.html

[R58] 下载文件
来源：http://dali.yanxiufei.cn/Article/details/gteasiptvd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.nanxuanxn.top/Article/details/gtkbnbvqzj.html

[R59] 发 POST JSON
来源：http://dali.dianchejie.cn/Article/details/gtoryegydv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.vqdsnc.cn/Article/details/gtgubmzhng.html

[R60] 只看 HTTP 状态码
来源：http://dali.pycfn.com/Article/details/gtdpixhcis.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.kuanghao11.cn/Article/details/gtjrcvpepl.html

[R61] 磁盘占用
来源：http://dali.cucudq.cn/Article/details/gtdxlbhaio.html

df -h;  du -sh *
来源：http://dali.yueranfly.top/Article/details/gtdtkyeisy.html

[R62] 找最占空间的文件
来源：http://dali.hnqzz.top/Article/details/gtmhtcvcmq.html

du -ah . | sort -rh | head -10
来源：http://dali.zycfv.cn/Article/details/gtsdhededv.html

[R63] 内存与进程
来源：http://dali.daxiang520.top/Article/details/gtseslvfgs.html

free -h;  ps aux | grep nginx
来源：http://dali.sweek.top/Article/details/gtflzwxihf.html

[R64] 结束进程
来源：http://dali.yanxiufei.cn/Article/details/gtsgakmrlo.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hfpthk.cn/Article/details/gtvtdckjae.html

[R65] 查看端口占用
来源：http://dali.sxryk.cn/Article/details/gtmzzdsnhe.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hongshengwenyu.top/Article/details/gtshanmcyc.html

[R66] 定时任务
来源：http://dali.c1oappe.top/Article/details/gtvwraimwp.html

crontab -e;  crontab -l
来源：http://dali.yuanzhike.top/Article/details/gthnhjqeqg.html

[R67] 生成随机十六进制串
来源：http://dali.tianlin.xyz/Article/details/gtylznytse.html

openssl rand -hex 16
来源：http://dali.chenlongwang.top/Article/details/gtalkedmtb.html

[R68] 计算文件校验值
来源：http://dali.tianlin.xyz/Article/details/gtywkjzedr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yongpay.top/Article/details/gtjhleawzs.html

[R69] 生成随机密码
来源：http://dali.yvedp.cn/Article/details/gtsldbbout.html

head -c 16 /dev/urandom | base64
来源：http://dali.nwbrower.top/Article/details/gtbvjyibns.html

[R70] 时间戳与互转
来源：http://dali.xinyue.icu/Article/details/gtcbbptomb.html

date +%s;  date -d @1700000000
来源：http://dali.ehwqpu.com/Article/details/gthzmlqvpw.html

[R71] 日期格式化
来源：http://dali.fzhhl.top/Article/details/gtqcgbhgpo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xuanzx.com/Article/details/gtelysjfze.html

[R72] 等待端口就绪
来源：http://dali.yj20258.top/Article/details/gtzawivlrw.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sufxvd.cn/Article/details/gtrllvtbmi.html

[R73] 分割大日志
来源：http://dali.pengpengdd.cyou/Article/details/gtadsjjpsq.html


<!-- 参考信息 -->