代发 wailian999

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtxqnhtmih.html

[Q28] 求和与平均
来源：http://dali.gotoacloud.top/Article/details/gtcetdzyuf.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.fengsongda.top/Article/details/gtqjibxpba.html

[Q29] 最大最小值
来源：http://dali.zhiwuduotai.top/Article/details/gtmhntaxvp.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.smart0.xyz/Article/details/gtvhoqkwcd.html

[Q30] 分组统计
来源：http://dali.jinqigfzy.top/Article/details/gtufvajpls.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.shuidangran.top/Article/details/gthatwcdjf.html

[Q31] 分组后过滤
来源：http://dali.ppjwa.cn/Article/details/gtmqnoljxc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yj20258888.top/Article/details/gtxpcbwtnu.html

[Q32] 分组拼接字符串
来源：http://dali.yangfankeji.com/Article/details/gtnobemfik.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ppjwa.cn/Article/details/gtrqldqpqh.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.gaohongyu789.top/Article/details/gtymqgpqkb.html

[Q33] 多列分组
来源：http://dali.cdnleiting.top/Article/details/gthqecugbl.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.xziqi.cn/Article/details/gtawzclglr.html

[Q34] 每组取第一条
来源：http://dali.shangyingyoupin.top/Article/details/gtjsnujdli.html

SELECT * FROM (
来源：http://dali.c1oappe.top/Article/details/gtgtizsnkz.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yvedp.cn/Article/details/gtahbrlkok.html

) t WHERE rn = 1;
来源：http://dali.hammf.cn/Article/details/gtsoxnxxsk.html

[Q35] 内连接
来源：http://dali.dashuyun.cn/Article/details/gtohmvjmru.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.bjfxy.top/Article/details/gtxjekvqfs.html

[Q36] 左连接
来源：http://dali.haohaochexian.top/Article/details/gtlwjikvdb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.haohaochexian.top/Article/details/gtjhdehadw.html

[Q37] 右连接
来源：http://dali.zhixingplan.top/Article/details/gtlzittajb.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yvedp.cn/Article/details/gtjdbytgqj.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hnqzz.top/Article/details/gtezmvmwjc.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.snrcjt.cn/Article/details/gtbzspdebs.html

[Q39] 自连接（查上下级）
来源：http://dali.hysaishi.cn/Article/details/gttwjciqhp.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zycfv.cn/Article/details/gtajaqwcbq.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.316326.xyz/Article/details/gtnczvtyqi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.birdmap.top/Article/details/gtaftqweza.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.hammf.cn/Article/details/gtxalfqjeg.html

[Q41] 多表连接
来源：http://dali.nanxinkj.top/Article/details/gtmppxfpwo.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hywenlv.cn/Article/details/gtzagwzdwf.html

JOIN users u ON u.id = o.user_id
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtwqpfxedo.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zdqjudy.top/Article/details/gtbrhktiat.html

[Q42] 连接条件附加过滤
来源：http://dali.redwolf501.top/Article/details/gtjpebfquc.html

SELECT u.name, o.amount FROM users u
来源：http://dali.fzhhl.top/Article/details/gtvwpnumqo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.nwbrower.top/Article/details/gtoarugisd.html

[Q43] 标量子查询
来源：http://dali.zycfv.cn/Article/details/gtlvduxmca.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.zycfv.cn/Article/details/gtfpdjqbtm.html

[Q44] IN 子查询
来源：http://dali.sxryk.cn/Article/details/gtzhahfbwc.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hysaishi.cn/Article/details/gtmlmtmbgm.html

[Q45] EXISTS 判断存在
来源：http://dali.hammf.cn/Article/details/gtmaigdoyr.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aibaodan.cn/Article/details/gtxytkabae.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpkfzeart.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hongshengwenyu.top/Article/details/gtyflzukot.html

[Q47] 与平均值比较
来源：http://dali.guowangkeji.top/Article/details/gtsyohqlnn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwybenpog.html

[Q48] CTE 公用表表达式
来源：http://dali.yongpay.top/Article/details/gtnaelcwqj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrtbpuqao.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yvedp.cn/Article/details/gtgvjrogfp.html

[Q49] 更新单行
来源：http://dali.sxryk.cn/Article/details/gtslttqcnc.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.svipenyu.cn/Article/details/gtlzuhrqbv.html

[Q50] 批量更新
来源：http://dali.tianlin.xyz/Article/details/gteobafhly.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.pycfn.com/Article/details/gtotaqvais.html

[Q51] 用子查询更新
来源：http://dali.ybcxt.top/Article/details/gtacvkrqhj.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.gaohongyu789.top/Article/details/gtorkdzbri.html

[Q52] 删除指定行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqkwhijth.html

DELETE FROM users WHERE id = 10;
来源：http://dali.xuetiantiany.cn/Article/details/gtztlplydr.html

[Q53] 按条件删除
来源：http://dali.zdqjudy.top/Article/details/gtjshbmynm.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.dianchejie.cn/Article/details/gtlaoskokb.html

[Q54] 清空表
来源：http://dali.jinqigfzy.top/Article/details/gtypdofene.html

TRUNCATE TABLE logs;
来源：http://dali.gzhubu.top/Article/details/gtanlipqhw.html

[Q55] 排名（并列占位）
来源：http://dali.feifeiyinyue.top/Article/details/gthljywiml.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.tianlin.xyz/Article/details/gtfyxanzym.html

[Q56] 密集排名（并列不占位）
来源：http://dali.quarkkingdee.top/Article/details/gtzzmlgadm.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.zhiwuduotai.top/Article/details/gtqdhxbhhm.html

[Q57] 行号
来源：http://dali.havefunace.top/Article/details/gthoabpzbf.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtzlcfmbaz.html

[Q58] 累计求和
来源：http://dali.kuanghao11.cn/Article/details/gtozfgavci.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.cheryme.top/Article/details/gtxezqbzap.html

[Q59] 分组内累计
来源：http://dali.feifeiyinyue.top/Article/details/gtcyswhmdi.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yvedp.cn/Article/details/gtbnpsfkga.html

[Q60] 取上一行 / 下一行
来源：http://dali.pengpengdd.cyou/Article/details/gtxpxxwifr.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhoulong.xyz/Article/details/gtzwpizwrd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtrxbjxptn.html

[Q61] 移动平均
来源：http://dali.c1oappe.top/Article/details/gtzfnebpyw.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtuypvbpfp.html

[Q62] 分组占比
来源：http://dali.pycfn.com/Article/details/gtlgrtmkzh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhoulong.xyz/Article/details/gtvgvyhmjn.html

[Q63] 开启事务
来源：http://dali.bjfxy.top/Article/details/gtqkhwowgc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.svipenyu.cn/Article/details/gtmxylmhbi.html

[Q64] 提交事务
来源：http://dali.yvedp.cn/Article/details/gtatpiylee.html

COMMIT;
来源：http://dali.quarkkingdee.top/Article/details/gtyzsdezea.html

[Q65] 回滚事务
来源：http://dali.yj20258888.top/Article/details/gtvexkzhoo.html

ROLLBACK;
来源：http://dali.dashuyun.cn/Article/details/gtfnpyzhjx.html

[Q66] 行锁查询
来源：http://dali.cucudq.cn/Article/details/gtsipbcyty.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.fzhhl.top/Article/details/gtnybcuviu.html

[Q67] 设置隔离级别
来源：http://dali.cheryme.top/Article/details/gtintwgrjb.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.haohaochexian.top/Article/details/gtkcudsyak.html

[Q68] 保存点
来源：http://dali.yj202588.top/Article/details/gtuvxtvzar.html

SAVEPOINT sp1;
来源：http://dali.tianlin.xyz/Article/details/gtbxowlmmo.html

ROLLBACK TO sp1;
来源：http://dali.316326.xyz/Article/details/gtfaqmbglr.html

[Q69] 查看执行计划
来源：http://dali.316326.xyz/Article/details/gtpybbdnaf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jiagoushi.top/Article/details/gtslstwmsl.html

[Q70] 更新统计信息
来源：http://dali.aizwys.cn/Article/details/gtncnammfi.html

ANALYZE TABLE users;
来源：http://dali.snrcjt.cn/Article/details/gtpbvqgyuw.html

[Q71] 查看建表语句
来源：http://dali.cqqwz.cn/Article/details/gthefxuntx.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jlsjyb.cn/Article/details/gtpcuzzctc.html

[Q72] 查看索引
来源：http://dali.jqgfzy.top/Article/details/gtmnfyxqjx.html

SHOW INDEX FROM users;
来源：http://dali.chenlongwang.top/Article/details/gttvlhcppq.html

[Q73] 查看表状态
来源：http://dali.chenlongwang.top/Article/details/gtlzmrewbo.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.mhx1999.top/Article/details/gtljoszfph.html

[Q74] 强制使用索引
来源：http://dali.xziqi.cn/Article/details/gtgzbizxio.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.dashuyun.cn/Article/details/gtaoaoptnw.html

[Q75] 日期格式化
来源：http://dali.yanxiufei.cn/Article/details/gtdryzhjvy.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtyxnlmbiv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.chenzaomai.com/Article/details/gtagfnoguc.html

[Q76] 按天统计
来源：http://dali.hywenlv.cn/Article/details/gtcgqfmwcy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.kuanghao11.cn/Article/details/gtkevnpxxt.html

[Q77] 时间加减
来源：http://dali.zycfv.cn/Article/details/gtfvqcsxsn.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.wangdashe.top/Article/details/gtpegkyyax.html

[Q78] 当前时间
来源：http://dali.guowangkeji.top/Article/details/gtqemkkhsw.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhiwuduotai.top/Article/details/gtzysyzoxm.html

[Q79] 字符串拼接
来源：http://dali.yanxiufei.cn/Article/details/gtgirlqpta.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.kuanghao11.cn/Article/details/gtayyvaebf.html

[Q80] 字符串截取
来源：http://dali.fzhhl.top/Article/details/gticiaqbeb.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xinyue.icu/Article/details/gtgkejwryj.html

[Q81] 字符串替换
来源：http://dali.shangyingyoupin.top/Article/details/gttjofwwmn.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtbtpvrrkp.html

[Q82] 字符长度与字节长度
来源：http://dali.ppjwa.cn/Article/details/gthhrysmlu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtajbdenpi.html

[Q83] 大小写转换
来源：http://dali.zhengqikj.top/Article/details/gtnipbkspd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtrgeacbov.html

[Q84] 去除首尾空格
来源：http://dali.guowangkeji.top/Article/details/gtlbcxdsmb.html

SELECT TRIM(name) FROM users;
来源：http://dali.nwbrower.top/Article/details/gtgkpzfhxe.html

[Q85] 数值取整
来源：http://dali.ehwqpu.com/Article/details/gtzeqfjtyk.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yongpay.top/Article/details/gtgxiyaoav.html

[Q86] 读取 JSON 字段
来源：http://dali.yueranfly.top/Article/details/gtfntphxqi.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.9152youxi.cn/Article/details/gtcqrfjyik.html

[Q87] JSON 字段做条件
来源：http://dali.hywenlv.cn/Article/details/gtsdwxmmye.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.quarkkingdee.top/Article/details/gtiyrpizka.html

[Q88] 行转列（条件聚合）
来源：http://dali.9152youxi.cn/Article/details/gtirmqvskb.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.chenjidiqi.icu/Article/details/gtvxzmsmzc.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.pycfn.com/Article/details/gtzxtncgyq.html

[Q89] 判断表是否存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdvrxsqvt.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.fzhhl.top/Article/details/gtpgbywjil.html

[Q90] 生成序号列
来源：http://dali.ybcxt.top/Article/details/gtatmlabnn.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.gotoacloud.top/Article/details/gtqrckhuzk.html

================================================================================
来源：http://dali.yj202588.top/Article/details/gtcwwrbndg.html

R. Bash 专题
来源：http://dali.daria6918.cn/Article/details/gttvbtkqvy.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gttozjtbwb.html

[R01] shebang 与严格模式
来源：http://dali.jinqigfzy.top/Article/details/gttkvpddfo.html

#!/usr/bin/env bash
来源：http://dali.zycfv.cn/Article/details/gtmifbunji.html

set -euo pipefail
来源：http://dali.jianghu66.top/Article/details/gteckoswwi.html

[R02] 变量赋值与使用
来源：http://dali.chenzaomai.com/Article/details/gtwhpulcnc.html

name="Tom"; echo "$name"
来源：http://dali.gaohongyu789.top/Article/details/gtfiblqwoq.html

[R03] 只读变量
来源：http://dali.chenzaomai.com/Article/details/gttegfborg.html

readonly PI=3.14
来源：http://dali.hongshengwenyu.top/Article/details/gtbvkwydcr.html

[R04] 位置参数
来源：http://dali.cqqwz.cn/Article/details/gtcuayjcsb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jqgufenzy.top/Article/details/gtutqobyab.html

[R05] 参数默认值
来源：http://dali.nwbrower.top/Article/details/gtmmimywll.html

name="${1:-default}"
来源：http://dali.andypj.xyz/Article/details/gtmwgfdsvb.html

[R06] 判断命令是否存在
来源：http://dali.zhijiandao.cn/Article/details/gtlqpqbdon.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.shanyushiyangtech.top/Article/details/gteiqaxdob.html

[R07] if 判断文件
来源：http://dali.0kj1m.cn/Article/details/gtvtqpjsgf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.sufxvd.cn/Article/details/gtownccedx.html

[R08] 数值比较
来源：http://dali.svipenyu.cn/Article/details/gtewouumos.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.smart0.xyz/Article/details/gtlrdbzzst.html

[R09] 字符串比较
来源：http://dali.tanke756.top/Article/details/gtgbcuwivn.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.daxiang520.top/Article/details/gtwfrzusau.html

[R10] 正则匹配
来源：http://dali.ivvv.top/Article/details/gtclrytzwh.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.0kj1m.cn/Article/details/gtogatmwtt.html

[R11] case 多分支
来源：http://dali.aibaodan.cn/Article/details/gttdeytywx.html

case "$1" in
来源：http://dali.yangfankeji.com/Article/details/gtlvccnhbu.html

start) echo "启动" ;;
来源：http://dali.chenzaomai.com/Article/details/gtijexueoe.html

stop)  echo "停止" ;;
来源：http://dali.yuxming.cn/Article/details/gtczeptvjm.html

*)     echo "未知命令" ;;
来源：http://dali.xuanzx.com/Article/details/gtmmthrydp.html

esac
来源：http://dali.yvedp.cn/Article/details/gtjycujmxe.html

[R12] for 遍历文件
来源：http://dali.hfpthk.cn/Article/details/gtodpsyyuh.html

for f in *.txt; do echo "$f"; done
来源：http://dali.hfpthk.cn/Article/details/gtzycunmqx.html

[R13] for 计数循环
来源：http://dali.smart0.xyz/Article/details/gtzaeqqvmf.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdjtgrffb.html

[R14] C 风格 for
来源：http://dali.shuidangran.top/Article/details/gtwqzcvapn.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.svipenyu.cn/Article/details/gtkhgjmsjg.html

[R15] while 逐行读文件
来源：http://dali.hammf.cn/Article/details/gtxgkwpuvt.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yangfankeji.com/Article/details/gttvguoesq.html

[R16] until 等待条件
来源：http://dali.hnqzz.top/Article/details/gtbpajbzms.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.zhixingplan.top/Article/details/gtuowkzxxm.html

[R17] 数组定义与取值
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtluyiepkm.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.tianlin.xyz/Article/details/gtadvowifc.html

[R18] 遍历数组
来源：http://dali.zhengqikj.top/Article/details/gtkyqopxjg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ydzc1.top/Article/details/gtayyrtdng.html

[R19] 数组长度
来源：http://dali.yj202588.top/Article/details/gtkhdwezzv.html

echo "${#arr[@]}"
来源：http://dali.aibaodan.cn/Article/details/gtqlxscsvy.html

[R20] 关联数组（字典）
来源：http://dali.shuidangran.top/Article/details/gtksxjhmaf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.pycfn.com/Article/details/gtigakkmvf.html

[R21] 字符串长度
来源：http://dali.wangdashe.top/Article/details/gtdhpxwkfj.html

echo "${#s}"
来源：http://dali.chenzaomai.com/Article/details/gtamypwgkp.html

[R22] 截取子串
来源：http://dali.gogol.net.cn/Article/details/gtvkslnzmt.html

echo "${s:0:5}"
来源：http://dali.jqgfzy.top/Article/details/gtuxfwznhq.html

[R23] 字符串替换
来源：http://dali.cucudq.cn/Article/details/gtanssgdmj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.havefunace.top/Article/details/gtcgtmnzzd.html

[R24] 大小写转换
来源：http://dali.zhiwuduotai.top/Article/details/gtcixgario.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zycfv.cn/Article/details/gtxcbiwbin.html

[R25] 去后缀 / 去前缀
来源：http://dali.daria6918.cn/Article/details/gtfbkngkfm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.daxiang520.top/Article/details/gtrmstofzn.html

[R26] 命令替换
来源：http://dali.hysaishi.cn/Article/details/gtnfxiilrm.html

now=$(date +%F); echo "$now"
来源：http://dali.jinqigufen.top/Article/details/gthxxfqyha.html

[R27] 算术展开
来源：http://dali.jyoumei.cn/Article/details/gtcewszsuo.html

echo $((1 + 2 * 3))
来源：http://dali.iojbl.cn/Article/details/gtoyjnozyl.html

[R28] 浮点运算
来源：http://dali.pengpengdd.cyou/Article/details/gtadxhuibm.html

echo "scale=2; 10/3" | bc
来源：http://dali.yanxiufei.cn/Article/details/gtfnwldjqb.html

[R29] 定义函数
来源：http://dali.cucudq.cn/Article/details/gtefmukwjf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.svipenyu.cn/Article/details/gtxwuetijg.html

[R30] 函数返回状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gtveftqdoq.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gaohongyu789.top/Article/details/gtymuczhko.html

[R31] 局部变量
来源：http://dali.jqgufenzy.top/Article/details/gtjspsrqdd.html

f() { local x=1; echo "$x"; }
来源：http://dali.havefunace.top/Article/details/gtsztholtw.html

[R32] 参数个数校验
来源：http://dali.havefunace.top/Article/details/gtuvywdpgd.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.mhx1999.top/Article/details/gtklptavxb.html

[R33] 捕获错误并提示行号
来源：http://dali.sxryk.cn/Article/details/gtvspsvqbv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.daria6918.cn/Article/details/gthtvbgvor.html

[R34] 退出时清理
来源：http://dali.ybcxt.top/Article/details/gtnwserwqh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgufenzy.top/Article/details/gtmguzzkfk.html

[R35] 后台执行并等待
来源：http://dali.jqgufenzy.top/Article/details/gtjhanhiei.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xuanzx.com/Article/details/gtqooiiclh.html

[R36] 并发执行多个任务
来源：http://dali.shzxlz.cn/Article/details/gtowradggf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ppjwa.cn/Article/details/gtqcgbfvmi.html

[R37] 把输出赋给变量
来源：http://dali.shanyushiyangtech.top/Article/details/gtbnpgwifc.html

files=$(ls -1)
来源：http://dali.ybcxt.top/Article/details/gtdjxzqqnm.html

[R38] 管道串联
来源：http://dali.xuanzx.com/Article/details/gtehyipglx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.chenzaomai.com/Article/details/gtqoqjzvmy.html

[R39] 重定向标准输出与错误
来源：http://dali.sxryk.cn/Article/details/gtwzduhyjo.html

cmd > out.log 2>&1
来源：http://dali.zhoulong.xyz/Article/details/gtrwvvcowl.html

[R40] 追加写日志
来源：http://dali.chenjidiqi.icu/Article/details/gtghiyjejo.html

echo "log" >> out.log
来源：http://dali.daxiang520.top/Article/details/gtaamorufe.html

[R41] 丢弃输出
来源：http://dali.smart0.xyz/Article/details/gthnsbfdoe.html

cmd >/dev/null 2>&1
来源：http://dali.zhaomingkeji.xyz/Article/details/gthlrdhquq.html

[R42] 输入重定向
来源：http://dali.quarkkingdee.top/Article/details/gtrfbbxxfp.html

wc -l < a.txt
来源：http://dali.yvedp.cn/Article/details/gtqqyhgrvt.html

[R43] 按名字查找文件
来源：http://dali.gotoacloud.top/Article/details/gtjtheqavh.html

find . -name "*.log" -type f
来源：http://dali.9152youxi.cn/Article/details/gtvcqmnokb.html

[R44] 按修改时间查找
来源：http://dali.jinghuilouyu.cn/Article/details/gtezahelnv.html

find . -mtime -7 -type f
来源：http://dali.shanyushiyangtech.top/Article/details/gtdyabmrtc.html

[R45] 批量删除
来源：http://dali.redwolf501.top/Article/details/gtufkoiaen.html

find . -name "*.tmp" -delete
来源：http://dali.dianchejie.cn/Article/details/gtcbtrsscr.html

[R46] 递归替换文件内容
来源：http://dali.gzhubu.top/Article/details/gtlmgmarrc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jyoumei.cn/Article/details/gtlnvlwxev.html

[R47] sed 单行替换
来源：http://dali.jinqigfzy.top/Article/details/gtebvbblnr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cheryme.top/Article/details/gtrvcopywf.html

[R48] awk 取指定列
来源：http://dali.yj202588.top/Article/details/gtaelmrfxg.html

awk '{print $1, $3}' a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtgyisfhhs.html

[R49] awk 带条件
来源：http://dali.gogol.net.cn/Article/details/gtfipxilew.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hnxiangtu.top/Article/details/gttmjwcnvr.html

[R50] awk 求和
来源：http://dali.yangfankeji.com/Article/details/gtvsrilvwf.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.c1oappe.top/Article/details/gtbmkzvbty.html

[R51] 排序去重取前几
来源：http://dali.daria6918.cn/Article/details/gtaobdshho.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.sufxvd.cn/Article/details/gtnjqlcvpg.html

[R52] 统计行数
来源：http://dali.nwbrower.top/Article/details/gtrckcuddy.html

wc -l a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtdxvmevyu.html

[R53] 查看文件头与实时尾
来源：http://dali.yueranfly.top/Article/details/gterwemnys.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.zdqjudy.top/Article/details/gthnoyiyzs.html

[R54] 比较两个文件
来源：http://dali.gzhubu.top/Article/details/gtsgdihqog.html

diff a.txt b.txt
来源：http://dali.jlsjyb.cn/Article/details/gthonwelip.html

[R55] 压缩与解压
来源：http://dali.yonumen.top/Article/details/gtghftkhhr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.jqgfzy.top/Article/details/gtxaydiqsx.html

[R56] 远程拷贝
来源：http://dali.hnxiangtu.top/Article/details/gttefnwpga.html

scp file user@host:/path/
来源：http://dali.jinqigufen.top/Article/details/gtpxwsomsj.html

[R57] 远程执行命令
来源：http://dali.kuanghao11.cn/Article/details/gtqooiones.html

ssh user@host 'uptime'
来源：http://dali.jlsjyb.cn/Article/details/gtmazfybxl.html

[R58] 下载文件
来源：http://dali.sysykeji.top/Article/details/gtbmkkdcub.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.tianlin.xyz/Article/details/gtbukgnkae.html

[R59] 发 POST JSON
来源：http://dali.nanxinkj.top/Article/details/gtqvnekrfz.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.nanxuanxn.top/Article/details/gthqyeiobk.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhiwuduotai.top/Article/details/gtuiweeykw.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.jinqigufen.top/Article/details/gtarhfqvbj.html

[R61] 磁盘占用
来源：http://dali.fengsongda.top/Article/details/gtgokzccyl.html

df -h;  du -sh *
来源：http://dali.birdmap.top/Article/details/gtkzfjbuak.html

[R62] 找最占空间的文件
来源：http://dali.c1oappe.top/Article/details/gtglytpxuk.html

du -ah . | sort -rh | head -10
来源：http://dali.yonumen.top/Article/details/gteuzqnzjw.html

[R63] 内存与进程
来源：http://dali.cashguo.top/Article/details/gtukuoouce.html

free -h;  ps aux | grep nginx
来源：http://dali.9152youxi.cn/Article/details/gtjmctqwqg.html

[R64] 结束进程
来源：http://dali.cucudq.cn/Article/details/gtcgjpukiu.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jqgufenzy.top/Article/details/gtfujmxxaz.html

[R65] 查看端口占用
来源：http://dali.jinqigfzy.top/Article/details/gtixeedxfg.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.aizwys.cn/Article/details/gtnrxflsoy.html

[R66] 定时任务
来源：http://dali.jinqigufen.top/Article/details/gtvkjvczes.html

crontab -e;  crontab -l
来源：http://dali.cheryme.top/Article/details/gttaewarrp.html

[R67] 生成随机十六进制串
来源：http://dali.bjfxy.top/Article/details/gtjhojzjwm.html

openssl rand -hex 16
来源：http://dali.hysaishi.cn/Article/details/gtdaehxqbt.html

[R68] 计算文件校验值
来源：http://dali.nanxinkj.top/Article/details/gtwvmuytex.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.0kj1m.cn/Article/details/gtytvayoda.html

[R69] 生成随机密码
来源：http://dali.nanxinkj.top/Article/details/gtqdujfydy.html

head -c 16 /dev/urandom | base64
来源：http://dali.ybcxt.top/Article/details/gtpppbgsbs.html

[R70] 时间戳与互转
来源：http://dali.hongshengwenyu.top/Article/details/gtaogyyiuo.html

date +%s;  date -d @1700000000
来源：http://dali.hnxiangtu.top/Article/details/gterpklqdq.html

[R71] 日期格式化
来源：http://dali.zhixingplan.top/Article/details/gtczhsefuk.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jyoumei.cn/Article/details/gtijhvbbgw.html

[R72] 等待端口就绪
来源：http://dali.xuetiantiany.cn/Article/details/gtqvmpqbed.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.wangshuangyany.cn/Article/details/gtpjtdsbpj.html

[R73] 分割大日志
来源：http://dali.meibo888.top/Article/details/gtvocxvbmq.html

split -l 1000 big.log part_
来源：http://dali.ybcxt.top/Article/details/gthmekenpa.html

[R74] 批量重命名
来源：http://dali.birdmap.top/Article/details/gtksfyzniw.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zycfv.cn/Article/details/gtywowkvzt.html

[R75] 导出环境变量
来源：http://dali.snrcjt.cn/Article/details/gtvkytxkqz.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.jinghuilouyu.cn/Article/details/gtecugpnlf.html

[R76] 使用临时文件
来源：http://dali.jqgfzy.top/Article/details/gtgwbdasoj.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.shangyingyoupin.top/Article/details/gtajnoiztl.html

[R77] 读取用户输入
来源：http://dali.svipenyu.cn/Article/details/gtwfrtczof.html


<!-- 参考信息 -->