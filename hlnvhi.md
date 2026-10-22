代发 wailian999

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.tian-w.cn/Article/details/gtzfkkyuul.html

[Q24] 去重
来源：http://dali.yuxming.cn/Article/details/gtupbxnjpk.html

SELECT DISTINCT city FROM users;
来源：http://dali.iojbl.cn/Article/details/gtgvcwkpez.html

[Q25] 只取前 N 条
来源：http://dali.pycfn.com/Article/details/gtwsckzvys.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.vqdsnc.cn/Article/details/gtmmnvpngp.html

[Q26] 计数
来源：http://dali.xinyue.icu/Article/details/gteujjmhyy.html

SELECT COUNT(*) FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtdjpdwchp.html

[Q27] 条件计数
来源：http://dali.yonumen.top/Article/details/gtloaemzxu.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtafpzabop.html

[Q28] 求和与平均
来源：http://dali.xinyue.icu/Article/details/gtbshdjkye.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gtkpymkxla.html

[Q29] 最大最小值
来源：http://dali.nwbrower.top/Article/details/gtsnqfkkrn.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.kuanghao11.cn/Article/details/gtatyufeyq.html

[Q30] 分组统计
来源：http://dali.mhx1999.top/Article/details/gtvwxtqhrl.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.sxryk.cn/Article/details/gttuuzdppl.html

[Q31] 分组后过滤
来源：http://dali.hammf.cn/Article/details/gtcchyvptq.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.bjfxy.top/Article/details/gthuthtgaa.html

[Q32] 分组拼接字符串
来源：http://dali.sweek.top/Article/details/gtxlunlmhz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yangfankeji.com/Article/details/gtzrzufvns.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.gaohongyu789.top/Article/details/gtwqifsgtd.html

[Q33] 多列分组
来源：http://dali.havefunace.top/Article/details/gtxydcmxvk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.kuanghao11.cn/Article/details/gtcpuordop.html

[Q34] 每组取第一条
来源：http://dali.yvedp.cn/Article/details/gtuhnhmpbm.html

SELECT * FROM (
来源：http://dali.bjfxy.top/Article/details/gtpwuwkpsf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hysaishi.cn/Article/details/gtjzymmriu.html

) t WHERE rn = 1;
来源：http://dali.haohaochexian.top/Article/details/gtqgrrxbmz.html

[Q35] 内连接
来源：http://dali.nanxuanxn.top/Article/details/gtujabwhqo.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ydzc1.top/Article/details/gtxxdxozhi.html

[Q36] 左连接
来源：http://dali.ydzc1.top/Article/details/gtbbhcxouk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.hfpthk.cn/Article/details/gtyenwpwko.html

[Q37] 右连接
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvopfagpv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.daria6918.cn/Article/details/gtueendajd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.9152youxi.cn/Article/details/gtsjslxktv.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.kuanghao11.cn/Article/details/gtatrlsmru.html

[Q39] 自连接（查上下级）
来源：http://dali.sweek.top/Article/details/gttupmrzte.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.cashguo.top/Article/details/gtmarpxcwn.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.kuanghao11.cn/Article/details/gtgcouvrxz.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.feifeiyinyue.top/Article/details/gthsbxsicx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xylfe.cn/Article/details/gtqrxukult.html

[Q41] 多表连接
来源：http://dali.guannengcc.top/Article/details/gtlwgrmssi.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhengqikj.top/Article/details/gtafnxirig.html

JOIN users u ON u.id = o.user_id
来源：http://dali.feifeiyinyue.top/Article/details/gtgzachujf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cucudq.cn/Article/details/gtlykdqdld.html

[Q42] 连接条件附加过滤
来源：http://dali.shangyingyoupin.top/Article/details/gtucgnsrrs.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cheryme.top/Article/details/gtoxohitkb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.dashuyun.cn/Article/details/gtcylnemcx.html

[Q43] 标量子查询
来源：http://dali.nanxuanxn.top/Article/details/gtfycfeqie.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jinqigfzy.top/Article/details/gtsiqgolwt.html

[Q44] IN 子查询
来源：http://dali.jqgufenzy.top/Article/details/gtayaogdhb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhongyouzk.top/Article/details/gtgteepgrv.html

[Q45] EXISTS 判断存在
来源：http://dali.meibo888.top/Article/details/gtotqmdnzi.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.0kj1m.cn/Article/details/gtardnmzwy.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ydzc1.top/Article/details/gtweoekwul.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.0kj1m.cn/Article/details/gtzfmuhyfl.html

[Q47] 与平均值比较
来源：http://dali.havefunace.top/Article/details/gtbmahqbmn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.kuanghao11.cn/Article/details/gtkbqaomni.html

[Q48] CTE 公用表表达式
来源：http://dali.cucudq.cn/Article/details/gtlvqjzsdh.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.shzxlz.cn/Article/details/gtxftagtbq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.feifeiyinyue.top/Article/details/gtlcccmpdv.html

[Q49] 更新单行
来源：http://dali.daxiang520.top/Article/details/gtymnixzrg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cashguo.top/Article/details/gtakkyoehw.html

[Q50] 批量更新
来源：http://dali.yueranfly.top/Article/details/gtuyqacpml.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.daxiang520.top/Article/details/gtxpthaahj.html

[Q51] 用子查询更新
来源：http://dali.zhiwuduotai.top/Article/details/gtbfvjngys.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.chenzaomai.com/Article/details/gtwaklekdq.html

[Q52] 删除指定行
来源：http://dali.dashuyun.cn/Article/details/gtvuyglqfu.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinqigufen.top/Article/details/gtkhihkdry.html

[Q53] 按条件删除
来源：http://dali.gaohongyu789.top/Article/details/gtybboxvir.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.xuanzx.com/Article/details/gtfcoiavuz.html

[Q54] 清空表
来源：http://dali.9152youxi.cn/Article/details/gtrjxaxekx.html

TRUNCATE TABLE logs;
来源：http://dali.yj20258.top/Article/details/gtlcbsnmib.html

[Q55] 排名（并列占位）
来源：http://dali.jinyuanbaomall.cn/Article/details/gtruzvxzmh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.shanyushiyangkeji.top/Article/details/gthepqckyo.html

[Q56] 密集排名（并列不占位）
来源：http://dali.havefunace.top/Article/details/gthqtjielf.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nwbrower.top/Article/details/gtnglbdeam.html

[Q57] 行号
来源：http://dali.chenzaomai.com/Article/details/gtrtywurhk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.andypj.xyz/Article/details/gtwkxrpbgl.html

[Q58] 累计求和
来源：http://dali.yj20258888.top/Article/details/gtalpvjbrg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ehwqpu.com/Article/details/gtdlkrxyre.html

[Q59] 分组内累计
来源：http://dali.nanxuanxn.top/Article/details/gtxcqccpie.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtmjmgfyst.html

[Q60] 取上一行 / 下一行
来源：http://dali.hnxiangtu.top/Article/details/gtdrylzqfm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.tanke756.top/Article/details/gtshjeyjio.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.xuanzx.com/Article/details/gtpnqvlpjn.html

[Q61] 移动平均
来源：http://dali.aibaodan.cn/Article/details/gtxicsrxvu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.316326.xyz/Article/details/gtanuszrej.html

[Q62] 分组占比
来源：http://dali.guannengcc.top/Article/details/gtnmhzqieo.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.fzhhl.top/Article/details/gteddsiwgp.html

[Q63] 开启事务
来源：http://dali.yj202588.top/Article/details/gtkdmqbiij.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.316326.xyz/Article/details/gtshwgjjfm.html

[Q64] 提交事务
来源：http://dali.gaohongyu789.top/Article/details/gtercxgzrk.html

COMMIT;
来源：http://dali.gogol.net.cn/Article/details/gtyigwjnoj.html

[Q65] 回滚事务
来源：http://dali.nanxuanxn.top/Article/details/gtmuahmkom.html

ROLLBACK;
来源：http://dali.snrcjt.cn/Article/details/gtyhyinzvs.html

[Q66] 行锁查询
来源：http://dali.nanxuanxn.top/Article/details/gtnfynvrqo.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.pengpengdd.cyou/Article/details/gtyzeazlrp.html

[Q67] 设置隔离级别
来源：http://dali.shzxlz.cn/Article/details/gtkhfliius.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.0kj1m.cn/Article/details/gtnemqdwut.html

[Q68] 保存点
来源：http://dali.zhijiandao.cn/Article/details/gtbttfoeyf.html

SAVEPOINT sp1;
来源：http://dali.sxryk.cn/Article/details/gtjlvmaxxv.html

ROLLBACK TO sp1;
来源：http://dali.snrcjt.cn/Article/details/gtctdrbuij.html

[Q69] 查看执行计划
来源：http://dali.haohaochexian.top/Article/details/gtqcoiaawg.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.iojbl.cn/Article/details/gtxtzzkrrx.html

[Q70] 更新统计信息
来源：http://dali.cqqwz.cn/Article/details/gteidtmdrs.html

ANALYZE TABLE users;
来源：http://dali.chenzaomai.com/Article/details/gtupjsjmkq.html

[Q71] 查看建表语句
来源：http://dali.pycfn.com/Article/details/gtvjlngkgi.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.snrcjt.cn/Article/details/gtasinsfck.html

[Q72] 查看索引
来源：http://dali.shangyingyoupin.top/Article/details/gtxeenzbok.html

SHOW INDEX FROM users;
来源：http://dali.shuidangran.top/Article/details/gtzvvqwhth.html

[Q73] 查看表状态
来源：http://dali.iojbl.cn/Article/details/gtiykdsixf.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jinqigufen.top/Article/details/gtsxtkxfcl.html

[Q74] 强制使用索引
来源：http://dali.yonumen.top/Article/details/gtsjsstdzi.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhijiandao.cn/Article/details/gtcaayhgwe.html

[Q75] 日期格式化
来源：http://dali.cucudq.cn/Article/details/gtjjwppvqc.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yueranfly.top/Article/details/gtdepfyggb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yj20258888.top/Article/details/gtteumfbtu.html

[Q76] 按天统计
来源：http://dali.xuanzx.com/Article/details/gtchjojnwi.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jinqigufen.top/Article/details/gtspvvkqwi.html

[Q77] 时间加减
来源：http://dali.cucudq.cn/Article/details/gtxbptaapy.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.316326.xyz/Article/details/gtlzbbzjxa.html

[Q78] 当前时间
来源：http://dali.aibaodan.cn/Article/details/gtcwlcssuq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfekoczxu.html

[Q79] 字符串拼接
来源：http://dali.nanxinkj.top/Article/details/gtdaeucgou.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cashguo.top/Article/details/gtyapnnjlo.html

[Q80] 字符串截取
来源：http://dali.0kj1m.cn/Article/details/gtbtegnkqs.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.wangdashe.top/Article/details/gtzbrbrjrd.html

[Q81] 字符串替换
来源：http://dali.ydzc1.top/Article/details/gtyqbosyub.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.nwbrower.top/Article/details/gtbucckuiz.html

[Q82] 字符长度与字节长度
来源：http://dali.sxryk.cn/Article/details/gtamxrgtyi.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.fengsongda.top/Article/details/gtevgfrabu.html

[Q83] 大小写转换
来源：http://dali.vqdsnc.cn/Article/details/gtvglxmqvv.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hnxiangtu.top/Article/details/gtiabrswgn.html

[Q84] 去除首尾空格
来源：http://dali.zhaomingkeji.xyz/Article/details/gtllppjyeo.html

SELECT TRIM(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtcdxinich.html

[Q85] 数值取整
来源：http://dali.jiagoushi.top/Article/details/gthajmpshm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.cashguo.top/Article/details/gtcvzvekqj.html

[Q86] 读取 JSON 字段
来源：http://dali.c1oappe.top/Article/details/gtzsbgzgaw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.haohaochexian.top/Article/details/gtcykybyvb.html

[Q87] JSON 字段做条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgzadnzkd.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.dashuyun.cn/Article/details/gthbomjjaf.html

[Q88] 行转列（条件聚合）
来源：http://dali.cdnleiting.top/Article/details/gtbbshliht.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.vqdsnc.cn/Article/details/gtaijtiblo.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtwuiiymac.html

[Q89] 判断表是否存在
来源：http://dali.mhx1999.top/Article/details/gtzxvbmquh.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhengqikj.top/Article/details/gtkxecccss.html

[Q90] 生成序号列
来源：http://dali.yueranfly.top/Article/details/gtpbvsnjam.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hysaishi.cn/Article/details/gtybtzwbrh.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtqzlgqjvw.html

R. Bash 专题
来源：http://dali.kuanghao11.cn/Article/details/gtzxgltewv.html

================================================================================
来源：http://dali.tian-w.cn/Article/details/gtzrmgjiyv.html

[R01] shebang 与严格模式
来源：http://dali.0kj1m.cn/Article/details/gtctxchlcu.html

#!/usr/bin/env bash
来源：http://dali.zhiwuduotai.top/Article/details/gtgyxnvefv.html

set -euo pipefail
来源：http://dali.ybcxt.top/Article/details/gtxojfadnu.html

[R02] 变量赋值与使用
来源：http://dali.hnqzz.top/Article/details/gtwcgmbwod.html

name="Tom"; echo "$name"
来源：http://dali.jinqigfzy.top/Article/details/gtppffjgyb.html

[R03] 只读变量
来源：http://dali.yuanzhike.top/Article/details/gtxzmdxmgq.html

readonly PI=3.14
来源：http://dali.quarkkingdee.top/Article/details/gtfjxvhggz.html

[R04] 位置参数
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkodacxut.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hammf.cn/Article/details/gtzoswrjhk.html

[R05] 参数默认值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpuywvvzl.html

name="${1:-default}"
来源：http://dali.jyoumei.cn/Article/details/gtvchtegvw.html

[R06] 判断命令是否存在
来源：http://dali.yueranfly.top/Article/details/gtfwqnomuq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zhixingplan.top/Article/details/gtooafftms.html

[R07] if 判断文件
来源：http://dali.nanxuanxn.top/Article/details/gtwvspdodn.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cheryme.top/Article/details/gtzwfezhup.html

[R08] 数值比较
来源：http://dali.feifeiyinyue.top/Article/details/gtzuqdbcpt.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jqgfzy.top/Article/details/gtuytvecbn.html

[R09] 字符串比较
来源：http://dali.chenjidiqi.icu/Article/details/gtqublbkjw.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.guannengcc.top/Article/details/gtdryxqzqw.html

[R10] 正则匹配
来源：http://dali.sxryk.cn/Article/details/gtfvcfimyp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.mhx1999.top/Article/details/gtobdlchae.html

[R11] case 多分支
来源：http://dali.xylfe.cn/Article/details/gtvaczdklm.html

case "$1" in
来源：http://dali.jqgufenzy.top/Article/details/gtsghczhmb.html

start) echo "启动" ;;
来源：http://dali.andypj.xyz/Article/details/gtohzydfmw.html

stop)  echo "停止" ;;
来源：http://dali.zhijiandao.cn/Article/details/gtbydflpgp.html

*)     echo "未知命令" ;;
来源：http://dali.jlsjyb.cn/Article/details/gtqohxcbcd.html

esac
来源：http://dali.chenjidiqi.icu/Article/details/gtevhcmrss.html

[R12] for 遍历文件
来源：http://dali.haohaochexian.top/Article/details/gtlezfbrqj.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ydzc1.top/Article/details/gtwxtpanmg.html

[R13] for 计数循环
来源：http://dali.xziqi.cn/Article/details/gtvlxwmukq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtvvrtamyh.html

[R14] C 风格 for
来源：http://dali.yuanzhike.top/Article/details/gtzezdbhif.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.vqdsnc.cn/Article/details/gtyqitjizk.html

[R15] while 逐行读文件
来源：http://dali.ybcxt.top/Article/details/gtnlwdetzv.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yangfankeji.com/Article/details/gttmzkrjks.html

[R16] until 等待条件
来源：http://dali.gogol.net.cn/Article/details/gtrhubzorn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hammf.cn/Article/details/gtnoulsgww.html

[R17] 数组定义与取值
来源：http://dali.gotoacloud.top/Article/details/gtshvsjyli.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtlvskktpv.html

[R18] 遍历数组
来源：http://dali.fzhhl.top/Article/details/gtbfuxvmfl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.sweek.top/Article/details/gtahvdrdsz.html

[R19] 数组长度
来源：http://dali.shangyingyoupin.top/Article/details/gtwpndmowc.html

echo "${#arr[@]}"
来源：http://dali.hnxiangtu.top/Article/details/gtswkbfyzt.html

[R20] 关联数组（字典）
来源：http://dali.bjfxy.top/Article/details/gtwrqxkmwa.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shanyushiyangtech.top/Article/details/gtjzedfhyd.html

[R21] 字符串长度
来源：http://dali.haohaochexian.top/Article/details/gturschchm.html

echo "${#s}"
来源：http://dali.hnxiangtu.top/Article/details/gttvtxxihv.html

[R22] 截取子串
来源：http://dali.nwbrower.top/Article/details/gtidibwzto.html

echo "${s:0:5}"
来源：http://dali.jianghu66.top/Article/details/gtwogydwvb.html

[R23] 字符串替换
来源：http://dali.yanxiufei.cn/Article/details/gtsefioibx.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.meibo888.top/Article/details/gtdgnhtazu.html

[R24] 大小写转换
来源：http://dali.hnqzz.top/Article/details/gtrilbnabg.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.aibaodan.cn/Article/details/gtpnnemkwk.html

[R25] 去后缀 / 去前缀
来源：http://dali.zdqjudy.top/Article/details/gtpolfwixs.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yongpay.top/Article/details/gtybafomgp.html

[R26] 命令替换
来源：http://dali.dashuyun.cn/Article/details/gticyqicgm.html

now=$(date +%F); echo "$now"
来源：http://dali.yvedp.cn/Article/details/gthofbqqry.html

[R27] 算术展开
来源：http://dali.jqgfzy.top/Article/details/gtoijkmnvy.html

echo $((1 + 2 * 3))
来源：http://dali.ybcxt.top/Article/details/gtzrjrhqxh.html

[R28] 浮点运算
来源：http://dali.cashguo.top/Article/details/gtfrsliifn.html

echo "scale=2; 10/3" | bc
来源：http://dali.chenlongwang.top/Article/details/gtymvifvvs.html

[R29] 定义函数
来源：http://dali.cucudq.cn/Article/details/gtdhhviebn.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cucudq.cn/Article/details/gtwxkeqkos.html

[R30] 函数返回状态码
来源：http://dali.guowangkeji.top/Article/details/gtjysdjvch.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ivvv.top/Article/details/gtxkqxxqqd.html

[R31] 局部变量
来源：http://dali.cashguo.top/Article/details/gtzlbwdsqm.html

f() { local x=1; echo "$x"; }
来源：http://dali.chenlongwang.top/Article/details/gtpzskhrdq.html

[R32] 参数个数校验
来源：http://dali.hfpthk.cn/Article/details/gtebafdduh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gotoacloud.top/Article/details/gtwaiytgha.html

[R33] 捕获错误并提示行号
来源：http://dali.zycfv.cn/Article/details/gtjaxwtwje.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.zhiwuduotai.top/Article/details/gtmsfwkplr.html

[R34] 退出时清理
来源：http://dali.gogol.net.cn/Article/details/gtsonxmthd.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jiagoushi.top/Article/details/gtdujzibbb.html

[R35] 后台执行并等待
来源：http://dali.shangyingyoupin.top/Article/details/gtzxsezmtu.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.daria6918.cn/Article/details/gthagnpqxc.html

[R36] 并发执行多个任务
来源：http://dali.zhongyouzk.top/Article/details/gtunnghfgg.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gzhubu.top/Article/details/gtgycztvmg.html

[R37] 把输出赋给变量
来源：http://dali.tianlin.xyz/Article/details/gtsyopkhvf.html

files=$(ls -1)
来源：http://dali.zdqjudy.top/Article/details/gtgujsspnt.html

[R38] 管道串联
来源：http://dali.chenlongwang.top/Article/details/gtxvxcunqn.html

cat a.txt | grep -i error | wc -l
来源：http://dali.snrcjt.cn/Article/details/gtnzfhibbe.html

[R39] 重定向标准输出与错误
来源：http://dali.yj20258.top/Article/details/gtcxopjoai.html

cmd > out.log 2>&1
来源：http://dali.xuanzx.com/Article/details/gtthcprtpn.html

[R40] 追加写日志
来源：http://dali.ivvv.top/Article/details/gtrbnsfppu.html

echo "log" >> out.log
来源：http://dali.andypj.xyz/Article/details/gtzuvkzwng.html

[R41] 丢弃输出
来源：http://dali.smart0.xyz/Article/details/gtvyiolrrs.html

cmd >/dev/null 2>&1
来源：http://dali.haohaochexian.top/Article/details/gtyaawcxjj.html

[R42] 输入重定向
来源：http://dali.hnqzz.top/Article/details/gtaddobkfe.html

wc -l < a.txt
来源：http://dali.wangdashe.top/Article/details/gtflcxzlth.html

[R43] 按名字查找文件
来源：http://dali.shanyushiyangtech.top/Article/details/gthiluyvot.html

find . -name "*.log" -type f
来源：http://dali.hnqzz.top/Article/details/gtipxzdvod.html

[R44] 按修改时间查找
来源：http://dali.pengpengdd.cyou/Article/details/gtledcdjev.html

find . -mtime -7 -type f
来源：http://dali.shuidangran.top/Article/details/gtmxiriunp.html

[R45] 批量删除
来源：http://dali.jinqigufen.top/Article/details/gtggqwjpgy.html

find . -name "*.tmp" -delete
来源：http://dali.hnxiangtu.top/Article/details/gtadebrdgr.html

[R46] 递归替换文件内容
来源：http://dali.hfpthk.cn/Article/details/gteapqchvk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jyoumei.cn/Article/details/gtrkbztovz.html

[R47] sed 单行替换
来源：http://dali.cqqwz.cn/Article/details/gtnyfcprgq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.0kj1m.cn/Article/details/gtfxnccivo.html

[R48] awk 取指定列
来源：http://dali.bjfxy.top/Article/details/gtyaqnsgjt.html

awk '{print $1, $3}' a.txt
来源：http://dali.yj20258888.top/Article/details/gthhoappmo.html

[R49] awk 带条件
来源：http://dali.ehwqpu.com/Article/details/gtcidssfey.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.dashuyun.cn/Article/details/gtsjhvmqlj.html

[R50] awk 求和
来源：http://dali.tian-w.cn/Article/details/gtdyyglqgo.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yvedp.cn/Article/details/gtsereiwwc.html

[R51] 排序去重取前几
来源：http://dali.gzhubu.top/Article/details/gtpurocgrj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yonumen.top/Article/details/gtqsptfkzz.html

[R52] 统计行数
来源：http://dali.ppjwa.cn/Article/details/gtdqetoxeu.html

wc -l a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtgftivswt.html

[R53] 查看文件头与实时尾
来源：http://dali.yj20258888.top/Article/details/gtcjcinnba.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yvedp.cn/Article/details/gtewtligyr.html

[R54] 比较两个文件
来源：http://dali.cqqwz.cn/Article/details/gthyzdxupg.html

diff a.txt b.txt
来源：http://dali.ehwqpu.com/Article/details/gtpqemrlpr.html

[R55] 压缩与解压
来源：http://dali.jqgfzy.top/Article/details/gtbjzpgkru.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yanxiufei.cn/Article/details/gtqvcahnwl.html

[R56] 远程拷贝
来源：http://dali.jlsjyb.cn/Article/details/gtdhexhcne.html

scp file user@host:/path/
来源：http://dali.xuanzx.com/Article/details/gtlligxupg.html

[R57] 远程执行命令
来源：http://dali.guannengcc.top/Article/details/gtunnfmnmt.html

ssh user@host 'uptime'
来源：http://dali.shzxlz.cn/Article/details/gtlgwlampw.html

[R58] 下载文件
来源：http://dali.chenjidiqi.icu/Article/details/gtsnpfufqt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.hywenlv.cn/Article/details/gtrwibmkve.html

[R59] 发 POST JSON
来源：http://dali.svipenyu.cn/Article/details/gtiwkanuoj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.fengsongda.top/Article/details/gtjeceprft.html

[R60] 只看 HTTP 状态码
来源：http://dali.redwolf501.top/Article/details/gtuzmoryni.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.quarkkingdee.top/Article/details/gtdybxtqnl.html

[R61] 磁盘占用
来源：http://dali.fengsongda.top/Article/details/gteqyverhv.html

df -h;  du -sh *
来源：http://dali.birdmap.top/Article/details/gtospaedzm.html

[R62] 找最占空间的文件
来源：http://dali.nanxinkj.top/Article/details/gtxhqrynqg.html

du -ah . | sort -rh | head -10
来源：http://dali.0kj1m.cn/Article/details/gttotuzdly.html

[R63] 内存与进程
来源：http://dali.yanxiufei.cn/Article/details/gtpezrmobg.html

free -h;  ps aux | grep nginx
来源：http://dali.iojbl.cn/Article/details/gteyvjpzhk.html

[R64] 结束进程
来源：http://dali.yangfankeji.com/Article/details/gtynpiqkmz.html

kill -9 $(pgrep -f app.py)
来源：http://dali.aibaodan.cn/Article/details/gtinmpiuin.html

[R65] 查看端口占用
来源：http://dali.nanxuanxn.top/Article/details/gtszweowgc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yvedp.cn/Article/details/gtaohfwcvp.html

[R66] 定时任务
来源：http://dali.haohaochexian.top/Article/details/gtilivdwbk.html

crontab -e;  crontab -l
来源：http://dali.zhongyouzk.top/Article/details/gtkccrnuqk.html

[R67] 生成随机十六进制串
来源：http://dali.tianlin.xyz/Article/details/gtpthneihd.html

openssl rand -hex 16
来源：http://dali.aibaodan.cn/Article/details/gtlxehmyyt.html

[R68] 计算文件校验值
来源：http://dali.jinyuanbaomall.cn/Article/details/gtnskkbwvi.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtemwjoxuc.html

[R69] 生成随机密码
来源：http://dali.snrcjt.cn/Article/details/gtarnyqhhf.html

head -c 16 /dev/urandom | base64
来源：http://dali.hywenlv.cn/Article/details/gtfhvoaehv.html

[R70] 时间戳与互转
来源：http://dali.zhengqikj.top/Article/details/gtpfbxozzw.html

date +%s;  date -d @1700000000
来源：http://dali.sysykeji.top/Article/details/gtcpunviue.html

[R71] 日期格式化
来源：http://dali.hongshengwenyu.top/Article/details/gtxxqjzicp.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yj20258.top/Article/details/gtsrfocxov.html

[R72] 等待端口就绪
来源：http://dali.nwbrower.top/Article/details/gtmfjtkuwp.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.sxryk.cn/Article/details/gtzezpnqyi.html

[R73] 分割大日志
来源：http://dali.bjfxy.top/Article/details/gtdicjjjtg.html


<!-- 参考信息 -->