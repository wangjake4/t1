代发 wailian999

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.hammf.cn/Article/details/gtdhjafmfe.html

[Q24] 去重
来源：http://dali.yongpay.top/Article/details/gtbmkmcepu.html

SELECT DISTINCT city FROM users;
来源：http://dali.jinqigufen.top/Article/details/gtveqxuxku.html

[Q25] 只取前 N 条
来源：http://dali.sweek.top/Article/details/gtazysjspa.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.guannengcc.top/Article/details/gtzpofbmhg.html

[Q26] 计数
来源：http://dali.shzxlz.cn/Article/details/gtkwjvdkih.html

SELECT COUNT(*) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtpvddtjuf.html

[Q27] 条件计数
来源：http://dali.jianghu66.top/Article/details/gtwmajcqnt.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.smart0.xyz/Article/details/gthbvlvxen.html

[Q28] 求和与平均
来源：http://dali.chenzaomai.com/Article/details/gttnvownlb.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gthazxxedv.html

[Q29] 最大最小值
来源：http://dali.haohaochexian.top/Article/details/gtytnomasr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.pycfn.com/Article/details/gtpobdcbxn.html

[Q30] 分组统计
来源：http://dali.havefunace.top/Article/details/gtcnrpheza.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jinqigfzy.top/Article/details/gtizmkxqrs.html

[Q31] 分组后过滤
来源：http://dali.chenzaomai.com/Article/details/gtyztkzqlz.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.feifeiyinyue.top/Article/details/gtzxsbilol.html

[Q32] 分组拼接字符串
来源：http://dali.chenlongwang.top/Article/details/gtdquxmxij.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hywenlv.cn/Article/details/gtxsmrbaby.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jlsjyb.cn/Article/details/gtbkblkaos.html

[Q33] 多列分组
来源：http://dali.birdmap.top/Article/details/gtbmefcznt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.redwolf501.top/Article/details/gtiztklgwa.html

[Q34] 每组取第一条
来源：http://dali.ybcxt.top/Article/details/gtujixlyig.html

SELECT * FROM (
来源：http://dali.hammf.cn/Article/details/gtxdwbngvf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hysaishi.cn/Article/details/gtnmpugsfq.html

) t WHERE rn = 1;
来源：http://dali.yueranfly.top/Article/details/gttmnhczga.html

[Q35] 内连接
来源：http://dali.jiagoushi.top/Article/details/gtulehjoki.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.tian-w.cn/Article/details/gttrgvdbbk.html

[Q36] 左连接
来源：http://dali.yangfankeji.com/Article/details/gtkwtzptyo.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.316326.xyz/Article/details/gtgyzzbjuc.html

[Q37] 右连接
来源：http://dali.0kj1m.cn/Article/details/gtjiijapof.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.aizwys.cn/Article/details/gtcndnflvd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ehwqpu.com/Article/details/gtsfdoelek.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.kuanghao11.cn/Article/details/gtxlkyuaad.html

[Q39] 自连接（查上下级）
来源：http://dali.havefunace.top/Article/details/gtmqtlejdq.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.gogol.net.cn/Article/details/gtnyezuyiz.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.fzhhl.top/Article/details/gtuilkrtud.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gaohongyu789.top/Article/details/gtuipepcco.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.gotoacloud.top/Article/details/gtbvojdnth.html

[Q41] 多表连接
来源：http://dali.jqgfzy.top/Article/details/gtcuokjvzb.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.gogol.net.cn/Article/details/gtkatgfrvu.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jqgufenzy.top/Article/details/gtqkyqljtx.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jqgfzy.top/Article/details/gtnxmkxkrn.html

[Q42] 连接条件附加过滤
来源：http://dali.yuxming.cn/Article/details/gtepdwcsyw.html

SELECT u.name, o.amount FROM users u
来源：http://dali.wangdashe.top/Article/details/gtgwmawsnd.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.sxryk.cn/Article/details/gtohpugmbl.html

[Q43] 标量子查询
来源：http://dali.cashguo.top/Article/details/gtporlrssy.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yonumen.top/Article/details/gtawrflbsv.html

[Q44] IN 子查询
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxnpicwvh.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.aizwys.cn/Article/details/gthrnemojg.html

[Q45] EXISTS 判断存在
来源：http://dali.shanyushiyangtech.top/Article/details/gtogejafdb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.cheryme.top/Article/details/gtjyjvlqhl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.gogol.net.cn/Article/details/gteabpjseb.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gogol.net.cn/Article/details/gtmwcwwiwy.html

[Q47] 与平均值比较
来源：http://dali.gzhubu.top/Article/details/gtpraqtqje.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.guannengcc.top/Article/details/gttskneaok.html

[Q48] CTE 公用表表达式
来源：http://dali.zycfv.cn/Article/details/gthhwdgztg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.chenzaomai.com/Article/details/gtpuwkbppf.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jqgfzy.top/Article/details/gtazkpfeev.html

[Q49] 更新单行
来源：http://dali.yangfankeji.com/Article/details/gtjlpxxyhz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cheryme.top/Article/details/gtkpjgnklo.html

[Q50] 批量更新
来源：http://dali.ybcxt.top/Article/details/gtaevedmmg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.guannengcc.top/Article/details/gtoojczdtu.html

[Q51] 用子查询更新
来源：http://dali.shuidangran.top/Article/details/gtuzlrkhjy.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sysykeji.top/Article/details/gteenbcgvp.html

[Q52] 删除指定行
来源：http://dali.bjfxy.top/Article/details/gtpffyfujn.html

DELETE FROM users WHERE id = 10;
来源：http://dali.aizwys.cn/Article/details/gtpqcruwwj.html

[Q53] 按条件删除
来源：http://dali.yongpay.top/Article/details/gtfthqnuay.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jqgufenzy.top/Article/details/gtyhboehaw.html

[Q54] 清空表
来源：http://dali.aizwys.cn/Article/details/gtbuewzfsp.html

TRUNCATE TABLE logs;
来源：http://dali.zhoulong.xyz/Article/details/gtxxscksnw.html

[Q55] 排名（并列占位）
来源：http://dali.jqgfzy.top/Article/details/gtctvgsbcj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.mhx1999.top/Article/details/gtqqeellbp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.xziqi.cn/Article/details/gtuwdolvko.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.hywenlv.cn/Article/details/gtylxmioxg.html

[Q57] 行号
来源：http://dali.zdqjudy.top/Article/details/gtuqwnxrjn.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.gzhubu.top/Article/details/gtzseuwcfs.html

[Q58] 累计求和
来源：http://dali.mhx1999.top/Article/details/gtludmpchf.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hongshengwenyu.top/Article/details/gtgpnpcncg.html

[Q59] 分组内累计
来源：http://dali.zhijiandao.cn/Article/details/gtklsgqrhm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuuxrkxjf.html

[Q60] 取上一行 / 下一行
来源：http://dali.gotoacloud.top/Article/details/gtiqofnwik.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.c1oappe.top/Article/details/gtkongpzmu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtjmshdfsg.html

[Q61] 移动平均
来源：http://dali.chenzaomai.com/Article/details/gtmbxabbse.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.havefunace.top/Article/details/gtwfmptpbd.html

[Q62] 分组占比
来源：http://dali.jinqigfzy.top/Article/details/gtrirmcfjh.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.birdmap.top/Article/details/gttjmzvgrw.html

[Q63] 开启事务
来源：http://dali.xylfe.cn/Article/details/gtumxcqohi.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cucudq.cn/Article/details/gtpssmrajf.html

[Q64] 提交事务
来源：http://dali.0kj1m.cn/Article/details/gtdothrsjo.html

COMMIT;
来源：http://dali.cucudq.cn/Article/details/gtgkhpgbtf.html

[Q65] 回滚事务
来源：http://dali.jlsjyb.cn/Article/details/gtcjbuyhcj.html

ROLLBACK;
来源：http://dali.yj202588.top/Article/details/gtztxtervo.html

[Q66] 行锁查询
来源：http://dali.jianghu66.top/Article/details/gthtoxubte.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xinyue.icu/Article/details/gtwieryghn.html

[Q67] 设置隔离级别
来源：http://dali.cashguo.top/Article/details/gtumnoxusp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zhijiandao.cn/Article/details/gtzczcnhsa.html

[Q68] 保存点
来源：http://dali.cashguo.top/Article/details/gtaaowkixj.html

SAVEPOINT sp1;
来源：http://dali.hnqzz.top/Article/details/gtwbclxzbq.html

ROLLBACK TO sp1;
来源：http://dali.chenjidiqi.icu/Article/details/gtxnpdfgcx.html

[Q69] 查看执行计划
来源：http://dali.haohaochexian.top/Article/details/gtnqarxtgb.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.aibaodan.cn/Article/details/gtjlijgdjy.html

[Q70] 更新统计信息
来源：http://dali.hywenlv.cn/Article/details/gtiufyjnub.html

ANALYZE TABLE users;
来源：http://dali.haohaochexian.top/Article/details/gticogfylh.html

[Q71] 查看建表语句
来源：http://dali.xziqi.cn/Article/details/gtcvrzzicc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.c1oappe.top/Article/details/gtnstvduqo.html

[Q72] 查看索引
来源：http://dali.c1oappe.top/Article/details/gtuxzmafwb.html

SHOW INDEX FROM users;
来源：http://dali.9152youxi.cn/Article/details/gtnustedjy.html

[Q73] 查看表状态
来源：http://dali.yj20258.top/Article/details/gtezaqqyva.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.sxryk.cn/Article/details/gtaikhhjwa.html

[Q74] 强制使用索引
来源：http://dali.chenjidiqi.icu/Article/details/gtevqvgewo.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyuzgnsvq.html

[Q75] 日期格式化
来源：http://dali.andypj.xyz/Article/details/gtkazhowvt.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwvfxdvlb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.vqdsnc.cn/Article/details/gtpasqvcnf.html

[Q76] 按天统计
来源：http://dali.meibo888.top/Article/details/gtnaxyiyma.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yuxming.cn/Article/details/gtmgppjahl.html

[Q77] 时间加减
来源：http://dali.cqqwz.cn/Article/details/gtmqikyint.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhoulong.xyz/Article/details/gtaoucciyu.html

[Q78] 当前时间
来源：http://dali.dianchejie.cn/Article/details/gtgvxpdpwm.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xuetiantiany.cn/Article/details/gtavcogetl.html

[Q79] 字符串拼接
来源：http://dali.xuanzx.com/Article/details/gtrpksqbcm.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.c1oappe.top/Article/details/gtaorycldj.html

[Q80] 字符串截取
来源：http://dali.birdmap.top/Article/details/gtdcwkdabi.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.fzhhl.top/Article/details/gtknfxqwqc.html

[Q81] 字符串替换
来源：http://dali.zhiwuduotai.top/Article/details/gteeinjflz.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.nanxinkj.top/Article/details/gtzhjcicxy.html

[Q82] 字符长度与字节长度
来源：http://dali.daria6918.cn/Article/details/gttcvqukso.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtknqfigla.html

[Q83] 大小写转换
来源：http://dali.c1oappe.top/Article/details/gtsssygvzd.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.aizwys.cn/Article/details/gtvvcxarnj.html

[Q84] 去除首尾空格
来源：http://dali.xziqi.cn/Article/details/gteklwmkry.html

SELECT TRIM(name) FROM users;
来源：http://dali.tianlin.xyz/Article/details/gtiqcuaxkv.html

[Q85] 数值取整
来源：http://dali.svipenyu.cn/Article/details/gtbhqndauw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zycfv.cn/Article/details/gtfdjztwih.html

[Q86] 读取 JSON 字段
来源：http://dali.zhiwuduotai.top/Article/details/gtvymgfiqd.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jianghu66.top/Article/details/gtibbbpvkn.html

[Q87] JSON 字段做条件
来源：http://dali.gaohongyu789.top/Article/details/gtgxrzquzm.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.aibaodan.cn/Article/details/gtvlvrcboi.html

[Q88] 行转列（条件聚合）
来源：http://dali.chenzaomai.com/Article/details/gtwwkfvkfx.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhengqikj.top/Article/details/gtuesyqwhn.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.shuidangran.top/Article/details/gtyhyhuzkd.html

[Q89] 判断表是否存在
来源：http://dali.pycfn.com/Article/details/gtromftvak.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.havefunace.top/Article/details/gtlytbtgbg.html

[Q90] 生成序号列
来源：http://dali.fengsongda.top/Article/details/gtsafsmexw.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ehwqpu.com/Article/details/gtdogyaxik.html

================================================================================
来源：http://dali.gaohongyu789.top/Article/details/gtixfnjxnz.html

R. Bash 专题
来源：http://dali.chenzaomai.com/Article/details/gtqmqpmelz.html

================================================================================
来源：http://dali.gogol.net.cn/Article/details/gtptdpmbky.html

[R01] shebang 与严格模式
来源：http://dali.aizwys.cn/Article/details/gtlkutdmqj.html

#!/usr/bin/env bash
来源：http://dali.sweek.top/Article/details/gtcqvgsgkb.html

set -euo pipefail
来源：http://dali.yuanzhike.top/Article/details/gtgtoedire.html

[R02] 变量赋值与使用
来源：http://dali.nwbrower.top/Article/details/gtueutdsyg.html

name="Tom"; echo "$name"
来源：http://dali.zhengqikj.top/Article/details/gtscmweeqk.html

[R03] 只读变量
来源：http://dali.jianghu66.top/Article/details/gtquyoctum.html

readonly PI=3.14
来源：http://dali.9152youxi.cn/Article/details/gtgueovmsk.html

[R04] 位置参数
来源：http://dali.tianlin.xyz/Article/details/gtqhgctrcj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hammf.cn/Article/details/gtdabfjvay.html

[R05] 参数默认值
来源：http://dali.gogol.net.cn/Article/details/gtkrivsdse.html

name="${1:-default}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdrkeascx.html

[R06] 判断命令是否存在
来源：http://dali.zhoulong.xyz/Article/details/gtlfihbisq.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.dianchejie.cn/Article/details/gtwgjrjmkw.html

[R07] if 判断文件
来源：http://dali.yonumen.top/Article/details/gtmoyeezjm.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlmfvdjhd.html

[R08] 数值比较
来源：http://dali.zhongyouzk.top/Article/details/gtkoafhwgu.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.daxiang520.top/Article/details/gtzrotuhbn.html

[R09] 字符串比较
来源：http://dali.jinqigufen.top/Article/details/gtzswtdbgx.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.nwbrower.top/Article/details/gtwvohbgke.html

[R10] 正则匹配
来源：http://dali.hysaishi.cn/Article/details/gtbrccvguj.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.xinyue.icu/Article/details/gtfqshwqyn.html

[R11] case 多分支
来源：http://dali.daria6918.cn/Article/details/gtcxuvryvg.html

case "$1" in
来源：http://dali.cdnleiting.top/Article/details/gtcnndeyni.html

start) echo "启动" ;;
来源：http://dali.shuidangran.top/Article/details/gtrdynaknv.html

stop)  echo "停止" ;;
来源：http://dali.jinqigfzy.top/Article/details/gtnlxdcbce.html

*)     echo "未知命令" ;;
来源：http://dali.sufxvd.cn/Article/details/gtavpvhwpr.html

esac
来源：http://dali.shzxlz.cn/Article/details/gtahzkbjzp.html

[R12] for 遍历文件
来源：http://dali.yonumen.top/Article/details/gtuotytakg.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj202588.top/Article/details/gtqgcspkjl.html

[R13] for 计数循环
来源：http://dali.havefunace.top/Article/details/gtuwqafmfp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtlhjmxjoa.html

[R14] C 风格 for
来源：http://dali.jinyuanbaomall.cn/Article/details/gtolycorhw.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.iojbl.cn/Article/details/gtomlmzcjg.html

[R15] while 逐行读文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtodaeigcf.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cucudq.cn/Article/details/gtywlvjczf.html

[R16] until 等待条件
来源：http://dali.shanyushiyangtech.top/Article/details/gtvfnzflfp.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yangfankeji.com/Article/details/gtqdfomqfb.html

[R17] 数组定义与取值
来源：http://dali.hywenlv.cn/Article/details/gtvdnpnxwq.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.feifeiyinyue.top/Article/details/gtuboezosg.html

[R18] 遍历数组
来源：http://dali.yj20258.top/Article/details/gtbchhpvdm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.tanke756.top/Article/details/gtzfrourup.html

[R19] 数组长度
来源：http://dali.daria6918.cn/Article/details/gttidzsunz.html

echo "${#arr[@]}"
来源：http://dali.xinyue.icu/Article/details/gtimsqbrat.html

[R20] 关联数组（字典）
来源：http://dali.yanxiufei.cn/Article/details/gthuufumbw.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.tianlin.xyz/Article/details/gtrtgdfkto.html

[R21] 字符串长度
来源：http://dali.gzhubu.top/Article/details/gtveenndsn.html

echo "${#s}"
来源：http://dali.nanxinkj.top/Article/details/gtgrtwcuqi.html

[R22] 截取子串
来源：http://dali.chenlongwang.top/Article/details/gtjcyyyugh.html

echo "${s:0:5}"
来源：http://dali.iojbl.cn/Article/details/gttagqxkoj.html

[R23] 字符串替换
来源：http://dali.yj20258888.top/Article/details/gtrwkmwztk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.aizwys.cn/Article/details/gtwwxbwnbi.html

[R24] 大小写转换
来源：http://dali.jinqigufen.top/Article/details/gtqcezjpwp.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.yonumen.top/Article/details/gtmatkfqkr.html

[R25] 去后缀 / 去前缀
来源：http://dali.aibaodan.cn/Article/details/gtortuvebc.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtuxfheiov.html

[R26] 命令替换
来源：http://dali.jinqigfzy.top/Article/details/gtrtnajgqu.html

now=$(date +%F); echo "$now"
来源：http://dali.guannengcc.top/Article/details/gtwmtkiaxj.html

[R27] 算术展开
来源：http://dali.zhengqikj.top/Article/details/gtgwwhwaou.html

echo $((1 + 2 * 3))
来源：http://dali.daria6918.cn/Article/details/gtanyghrna.html

[R28] 浮点运算
来源：http://dali.zycfv.cn/Article/details/gttdmfqvio.html

echo "scale=2; 10/3" | bc
来源：http://dali.haohaochexian.top/Article/details/gtlzmwbcgl.html

[R29] 定义函数
来源：http://dali.jqgfzy.top/Article/details/gtqmhywmuf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.aibaodan.cn/Article/details/gthjspkfng.html

[R30] 函数返回状态码
来源：http://dali.tanke756.top/Article/details/gttbfdrrjy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.hongshengwenyu.top/Article/details/gtesuhzcwr.html

[R31] 局部变量
来源：http://dali.yuxming.cn/Article/details/gtzflawpxs.html

f() { local x=1; echo "$x"; }
来源：http://dali.yonumen.top/Article/details/gtatcjiifi.html

[R32] 参数个数校验
来源：http://dali.sweek.top/Article/details/gtxvkmqvso.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yuxming.cn/Article/details/gtavclrlkt.html

[R33] 捕获错误并提示行号
来源：http://dali.nwbrower.top/Article/details/gtvgodamqm.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xuanzx.com/Article/details/gtlzmdhyhx.html

[R34] 退出时清理
来源：http://dali.xuetiantiany.cn/Article/details/gtwtwlsbhu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.sxryk.cn/Article/details/gtceshgolg.html

[R35] 后台执行并等待
来源：http://dali.snrcjt.cn/Article/details/gtwsrjudaz.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.shzxlz.cn/Article/details/gtuoroleae.html

[R36] 并发执行多个任务
来源：http://dali.mhx1999.top/Article/details/gtrjhoqmyj.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.guowangkeji.top/Article/details/gtoyzgddrr.html

[R37] 把输出赋给变量
来源：http://dali.fengsongda.top/Article/details/gtrqpbuaig.html

files=$(ls -1)
来源：http://dali.zhixingplan.top/Article/details/gtwbdzvnui.html

[R38] 管道串联
来源：http://dali.andypj.xyz/Article/details/gtpehavtvl.html

cat a.txt | grep -i error | wc -l
来源：http://dali.c1oappe.top/Article/details/gtlzkghnjc.html

[R39] 重定向标准输出与错误
来源：http://dali.0kj1m.cn/Article/details/gttjxptxsc.html

cmd > out.log 2>&1
来源：http://dali.xuanzx.com/Article/details/gtysbqdybv.html

[R40] 追加写日志
来源：http://dali.daria6918.cn/Article/details/gtjiymhqxf.html

echo "log" >> out.log
来源：http://dali.316326.xyz/Article/details/gthdzkzbzy.html

[R41] 丢弃输出
来源：http://dali.pycfn.com/Article/details/gttpzoeraz.html

cmd >/dev/null 2>&1
来源：http://dali.tianlin.xyz/Article/details/gtrtywshbr.html

[R42] 输入重定向
来源：http://dali.shanyushiyangtech.top/Article/details/gtkvylwvbb.html

wc -l < a.txt
来源：http://dali.snrcjt.cn/Article/details/gtqsemevcr.html

[R43] 按名字查找文件
来源：http://dali.zhongyouzk.top/Article/details/gtavbzsped.html

find . -name "*.log" -type f
来源：http://dali.cdnleiting.top/Article/details/gtyuzdldob.html

[R44] 按修改时间查找
来源：http://dali.xuetiantiany.cn/Article/details/gtmccvjjsl.html

find . -mtime -7 -type f
来源：http://dali.zhengqikj.top/Article/details/gtignqubde.html

[R45] 批量删除
来源：http://dali.meibo888.top/Article/details/gtmtjjmkdf.html

find . -name "*.tmp" -delete
来源：http://dali.jinqigufen.top/Article/details/gtlrwynmei.html

[R46] 递归替换文件内容
来源：http://dali.haohaochexian.top/Article/details/gtpwheckkw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hammf.cn/Article/details/gtqjjrxugn.html

[R47] sed 单行替换
来源：http://dali.kuanghao11.cn/Article/details/gtkpgnnsqp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhongyouzk.top/Article/details/gtpdasumta.html

[R48] awk 取指定列
来源：http://dali.kuanghao11.cn/Article/details/gtotoavioe.html

awk '{print $1, $3}' a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtfmkywfnj.html

[R49] awk 带条件
来源：http://dali.zhongyouzk.top/Article/details/gtugvpnkae.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.guowangkeji.top/Article/details/gtcipjzdbg.html

[R50] awk 求和
来源：http://dali.316326.xyz/Article/details/gtzcrnqpfg.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.9152youxi.cn/Article/details/gtknfudidc.html

[R51] 排序去重取前几
来源：http://dali.zhengqikj.top/Article/details/gtazlzwwlu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jinyuanbaomall.cn/Article/details/gtzrvptexr.html

[R52] 统计行数
来源：http://dali.pycfn.com/Article/details/gtyitelnge.html

wc -l a.txt
来源：http://dali.sysykeji.top/Article/details/gtqwqmvrng.html

[R53] 查看文件头与实时尾
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbpfmrcot.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.snrcjt.cn/Article/details/gtwewwwihf.html

[R54] 比较两个文件
来源：http://dali.zhiwuduotai.top/Article/details/gttcexowsl.html

diff a.txt b.txt
来源：http://dali.shzxlz.cn/Article/details/gthlazkdcx.html

[R55] 压缩与解压
来源：http://dali.ywan-chungtsiang.top/Article/details/gttqvhwcoz.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.shuidangran.top/Article/details/gtuxuejpge.html

[R56] 远程拷贝
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtujcsrgbw.html

scp file user@host:/path/
来源：http://dali.yj20258888.top/Article/details/gtiwsnhxhi.html

[R57] 远程执行命令
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdwtfxngp.html

ssh user@host 'uptime'
来源：http://dali.nwbrower.top/Article/details/gtrkhaswzj.html

[R58] 下载文件
来源：http://dali.gaohongyu789.top/Article/details/gtndfyrevm.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.svipenyu.cn/Article/details/gtarkgyjpv.html

[R59] 发 POST JSON
来源：http://dali.gaohongyu789.top/Article/details/gtyrycjuqe.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.daria6918.cn/Article/details/gtpndrccgd.html

[R60] 只看 HTTP 状态码
来源：http://dali.mhx1999.top/Article/details/gtnzeobsrc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.daxiang520.top/Article/details/gtcpzzwwis.html

[R61] 磁盘占用
来源：http://dali.fengsongda.top/Article/details/gtpjqypsyf.html

df -h;  du -sh *
来源：http://dali.chenlongwang.top/Article/details/gtuhpsflve.html

[R62] 找最占空间的文件
来源：http://dali.pengpengdd.cyou/Article/details/gtniwobsre.html

du -ah . | sort -rh | head -10
来源：http://dali.jinqigfzy.top/Article/details/gtzknwwgtv.html

[R63] 内存与进程
来源：http://dali.shuidangran.top/Article/details/gtxabtnyar.html

free -h;  ps aux | grep nginx
来源：http://dali.jianghu66.top/Article/details/gtpnqyxmyd.html

[R64] 结束进程
来源：http://dali.fzhhl.top/Article/details/gtabxpcvmh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gotoacloud.top/Article/details/gtaouvwezi.html

[R65] 查看端口占用
来源：http://dali.0kj1m.cn/Article/details/gtkhczxcwo.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zdqjudy.top/Article/details/gtvofuhkcy.html

[R66] 定时任务
来源：http://dali.yuanzhike.top/Article/details/gtykkmnwsu.html

crontab -e;  crontab -l
来源：http://dali.shzxlz.cn/Article/details/gtyobxhnme.html

[R67] 生成随机十六进制串
来源：http://dali.yvedp.cn/Article/details/gtzekwroya.html

openssl rand -hex 16
来源：http://dali.xziqi.cn/Article/details/gttttqdopz.html

[R68] 计算文件校验值
来源：http://dali.ehwqpu.com/Article/details/gtvtxefubh.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.sweek.top/Article/details/gtygqnvxfi.html

[R69] 生成随机密码
来源：http://dali.ppjwa.cn/Article/details/gtwbchssvk.html

head -c 16 /dev/urandom | base64
来源：http://dali.gogol.net.cn/Article/details/gtkqkajwnj.html

[R70] 时间戳与互转
来源：http://dali.daria6918.cn/Article/details/gtktgxbpoo.html

date +%s;  date -d @1700000000
来源：http://dali.dashuyun.cn/Article/details/gtnubwflrd.html

[R71] 日期格式化
来源：http://dali.yangfankeji.com/Article/details/gtsotvnkox.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.redwolf501.top/Article/details/gttlsrvllm.html

[R72] 等待端口就绪
来源：http://dali.zhaomingkeji.xyz/Article/details/gtybrvwmhn.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.0kj1m.cn/Article/details/gtzzessfkb.html

[R73] 分割大日志
来源：http://dali.yvedp.cn/Article/details/gtryegslnq.html


<!-- 参考信息 -->