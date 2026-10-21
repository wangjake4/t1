代发 wailian999

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hywenlv.cn/Article/details/gtshwkhsts.html

[Q30] 分组统计
来源：http://dali.yangfankeji.com/Article/details/gtqyvruaur.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.kuanghao11.cn/Article/details/gtbztywmpo.html

[Q31] 分组后过滤
来源：http://dali.yj20258.top/Article/details/gtniuqwzwl.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xuetiantiany.cn/Article/details/gtmihmbnhk.html

[Q32] 分组拼接字符串
来源：http://dali.pycfn.com/Article/details/gtcujskozz.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.haohaochexian.top/Article/details/gtujxcysxp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.hywenlv.cn/Article/details/gtsohtjxcf.html

[Q33] 多列分组
来源：http://dali.nwbrower.top/Article/details/gtjcbgjwvi.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yj202588.top/Article/details/gtvztpkmct.html

[Q34] 每组取第一条
来源：http://dali.jinqigufen.top/Article/details/gteltdglyy.html

SELECT * FROM (
来源：http://dali.nwbrower.top/Article/details/gtqsxlrlmd.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cdnleiting.top/Article/details/gtplhxuybw.html

) t WHERE rn = 1;
来源：http://dali.xuetiantiany.cn/Article/details/gtqtmmbaaw.html

[Q35] 内连接
来源：http://dali.jinqigfzy.top/Article/details/gtwrtrgcmy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.gzhubu.top/Article/details/gttslaqxff.html

[Q36] 左连接
来源：http://dali.jyoumei.cn/Article/details/gtvfagmiaw.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.jyoumei.cn/Article/details/gtjkudccku.html

[Q37] 右连接
来源：http://dali.zhongyouzk.top/Article/details/gtwxjtcqwi.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yuxming.cn/Article/details/gtqsckqhdr.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.tian-w.cn/Article/details/gtizhppelt.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.c1oappe.top/Article/details/gtauqsaxmc.html

[Q39] 自连接（查上下级）
来源：http://dali.zhongyouzk.top/Article/details/gtpsssnbrj.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.vqdsnc.cn/Article/details/gtyiwdavus.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.bjfxy.top/Article/details/gtfvkqkhlb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xuanzx.com/Article/details/gtbxvucrvz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.dashuyun.cn/Article/details/gtyuntqyor.html

[Q41] 多表连接
来源：http://dali.cashguo.top/Article/details/gtvrmnkvny.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.yangfankeji.com/Article/details/gtvqcwukso.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ppjwa.cn/Article/details/gtzftifufp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.feifeiyinyue.top/Article/details/gtikltybdl.html

[Q42] 连接条件附加过滤
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrnafdqhb.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zhongyouzk.top/Article/details/gtrghihifb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.daria6918.cn/Article/details/gtugfbvadc.html

[Q43] 标量子查询
来源：http://dali.iojbl.cn/Article/details/gtsrshpqrw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.tianlin.xyz/Article/details/gtfkngbglr.html

[Q44] IN 子查询
来源：http://dali.jiagoushi.top/Article/details/gtemxqyzpt.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.sysykeji.top/Article/details/gttbgadfwt.html

[Q45] EXISTS 判断存在
来源：http://dali.xziqi.cn/Article/details/gtwmlzdhgz.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgnpeevhu.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.redwolf501.top/Article/details/gtbuyjksru.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yuxming.cn/Article/details/gtkqiywimt.html

[Q47] 与平均值比较
来源：http://dali.yvedp.cn/Article/details/gtxiasmxsn.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.cqqwz.cn/Article/details/gtanhfazll.html

[Q48] CTE 公用表表达式
来源：http://dali.haohaochexian.top/Article/details/gtmrdpwuvi.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.yuxming.cn/Article/details/gtioymolxh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.hywenlv.cn/Article/details/gtijcxrlnp.html

[Q49] 更新单行
来源：http://dali.haohaochexian.top/Article/details/gthiuoilju.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.aibaodan.cn/Article/details/gtcnmozjkp.html

[Q50] 批量更新
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwshntsnl.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.yj20258.top/Article/details/gtpvkddddg.html

[Q51] 用子查询更新
来源：http://dali.ybcxt.top/Article/details/gtgdkmzlsa.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.haohaochexian.top/Article/details/gtmibxyrex.html

[Q52] 删除指定行
来源：http://dali.zhongyouzk.top/Article/details/gtckicwngc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jinghuilouyu.cn/Article/details/gtmuwmowiw.html

[Q53] 按条件删除
来源：http://dali.shzxlz.cn/Article/details/gtsqcvyzqd.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jqgfzy.top/Article/details/gtfnhnuqbr.html

[Q54] 清空表
来源：http://dali.yangfankeji.com/Article/details/gttpwduonn.html

TRUNCATE TABLE logs;
来源：http://dali.birdmap.top/Article/details/gtlkrwewdl.html

[Q55] 排名（并列占位）
来源：http://dali.feifeiyinyue.top/Article/details/gtodpkergj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.hfpthk.cn/Article/details/gtlyznrwzd.html

[Q56] 密集排名（并列不占位）
来源：http://dali.nwbrower.top/Article/details/gtavupxged.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.guowangkeji.top/Article/details/gtyipqpdfi.html

[Q57] 行号
来源：http://dali.cucudq.cn/Article/details/gtvvwhzhxt.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtkztevagh.html

[Q58] 累计求和
来源：http://dali.jianghu66.top/Article/details/gtogoxinqw.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtfrsvwazt.html

[Q59] 分组内累计
来源：http://dali.mhx1999.top/Article/details/gtinwvnson.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.chenjidiqi.icu/Article/details/gtcsebnhdx.html

[Q60] 取上一行 / 下一行
来源：http://dali.fengsongda.top/Article/details/gtsjdjowiz.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.xinyue.icu/Article/details/gtvzlannvk.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yongpay.top/Article/details/gtzqyxeyav.html

[Q61] 移动平均
来源：http://dali.shanyushiyangtech.top/Article/details/gtfvkslpqm.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtnejtqqjt.html

[Q62] 分组占比
来源：http://dali.hongshengwenyu.top/Article/details/gtguwmuxpe.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.bjfxy.top/Article/details/gtlpwjhhyz.html

[Q63] 开启事务
来源：http://dali.yongpay.top/Article/details/gtfnrapxpn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cqqwz.cn/Article/details/gtbhtugobs.html

[Q64] 提交事务
来源：http://dali.zhixingplan.top/Article/details/gtavyilnot.html

COMMIT;
来源：http://dali.bjfxy.top/Article/details/gtlzpzrppw.html

[Q65] 回滚事务
来源：http://dali.sxryk.cn/Article/details/gtpethihhv.html

ROLLBACK;
来源：http://dali.iojbl.cn/Article/details/gtzuyauhsc.html

[Q66] 行锁查询
来源：http://dali.guannengcc.top/Article/details/gtmuloakcm.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shangyingyoupin.top/Article/details/gthvrdmgdp.html

[Q67] 设置隔离级别
来源：http://dali.shuidangran.top/Article/details/gtgkljoxmp.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jqgufenzy.top/Article/details/gtptgpoqkn.html

[Q68] 保存点
来源：http://dali.jqgfzy.top/Article/details/gtwxuuhojk.html

SAVEPOINT sp1;
来源：http://dali.shzxlz.cn/Article/details/gtwskmiwhq.html

ROLLBACK TO sp1;
来源：http://dali.cashguo.top/Article/details/gtkorcqjng.html

[Q69] 查看执行计划
来源：http://dali.andypj.xyz/Article/details/gtrcdfifra.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.dashuyun.cn/Article/details/gtrgiaheqf.html

[Q70] 更新统计信息
来源：http://dali.tian-w.cn/Article/details/gtxjztbskf.html

ANALYZE TABLE users;
来源：http://dali.tian-w.cn/Article/details/gtkkzozbbx.html

[Q71] 查看建表语句
来源：http://dali.yj202588.top/Article/details/gtiwdrrvzo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.mhx1999.top/Article/details/gtlfxcthax.html

[Q72] 查看索引
来源：http://dali.cheryme.top/Article/details/gtgvhbujls.html

SHOW INDEX FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtghysudkv.html

[Q73] 查看表状态
来源：http://dali.daxiang520.top/Article/details/gtrfrzspek.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.daria6918.cn/Article/details/gtsppfcdjn.html

[Q74] 强制使用索引
来源：http://dali.jyoumei.cn/Article/details/gtfjdthabl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.hnxiangtu.top/Article/details/gtcapmocdf.html

[Q75] 日期格式化
来源：http://dali.jlsjyb.cn/Article/details/gtntoipkql.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.ppjwa.cn/Article/details/gtwzfhlyok.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gaohongyu789.top/Article/details/gtpvalpyqp.html

[Q76] 按天统计
来源：http://dali.mhx1999.top/Article/details/gtzkijnlyz.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.yuxming.cn/Article/details/gtsjwbpwhm.html

[Q77] 时间加减
来源：http://dali.jlsjyb.cn/Article/details/gtulttipax.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cqqwz.cn/Article/details/gtcvlkcnvu.html

[Q78] 当前时间
来源：http://dali.cheryme.top/Article/details/gtdoaiqass.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.bjfxy.top/Article/details/gtufunfloq.html

[Q79] 字符串拼接
来源：http://dali.andypj.xyz/Article/details/gtiivputoa.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.mhx1999.top/Article/details/gtaslygnmi.html

[Q80] 字符串截取
来源：http://dali.iojbl.cn/Article/details/gtwhifjpwe.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtcnllvjsn.html

[Q81] 字符串替换
来源：http://dali.xuanzx.com/Article/details/gttnixpnph.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdsxmybxo.html

[Q82] 字符长度与字节长度
来源：http://dali.yuxming.cn/Article/details/gtvsezhytt.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtrwpzuxea.html

[Q83] 大小写转换
来源：http://dali.nanxuanxn.top/Article/details/gtwhhugznf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.sxryk.cn/Article/details/gtdnhblrpf.html

[Q84] 去除首尾空格
来源：http://dali.xuanzx.com/Article/details/gtvjzdnibz.html

SELECT TRIM(name) FROM users;
来源：http://dali.cheryme.top/Article/details/gtattoqjcq.html

[Q85] 数值取整
来源：http://dali.jinghuilouyu.cn/Article/details/gtpecsfebm.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jlsjyb.cn/Article/details/gtnkpuhnao.html

[Q86] 读取 JSON 字段
来源：http://dali.pycfn.com/Article/details/gtkwcgjcpw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.pycfn.com/Article/details/gtjvylenyf.html

[Q87] JSON 字段做条件
来源：http://dali.ehwqpu.com/Article/details/gtilzchzto.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hysaishi.cn/Article/details/gtsasosgay.html

[Q88] 行转列（条件聚合）
来源：http://dali.ydzc1.top/Article/details/gtntqfqoei.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.ivvv.top/Article/details/gttkugbllh.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.xylfe.cn/Article/details/gtsyyqsunh.html

[Q89] 判断表是否存在
来源：http://dali.jinghuilouyu.cn/Article/details/gtbvjxkrvv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.c1oappe.top/Article/details/gtlidcupty.html

[Q90] 生成序号列
来源：http://dali.aibaodan.cn/Article/details/gtahizwjth.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.ppjwa.cn/Article/details/gtsikvqsgu.html

================================================================================
来源：http://dali.andypj.xyz/Article/details/gtwtlpwxoe.html

R. Bash 专题
来源：http://dali.sxryk.cn/Article/details/gtkcswvdzg.html

================================================================================
来源：http://dali.sweek.top/Article/details/gtcwhvxjig.html

[R01] shebang 与严格模式
来源：http://dali.zhijiandao.cn/Article/details/gtqzipjxwc.html

#!/usr/bin/env bash
来源：http://dali.cashguo.top/Article/details/gtvyblqxhf.html

set -euo pipefail
来源：http://dali.wangshuangyany.cn/Article/details/gtpojaptzu.html

[R02] 变量赋值与使用
来源：http://dali.tanke756.top/Article/details/gtuswqljgg.html

name="Tom"; echo "$name"
来源：http://dali.ehwqpu.com/Article/details/gtqxafkmww.html

[R03] 只读变量
来源：http://dali.feifeiyinyue.top/Article/details/gtmdyzkman.html

readonly PI=3.14
来源：http://dali.iojbl.cn/Article/details/gtmhaiqjbk.html

[R04] 位置参数
来源：http://dali.cucudq.cn/Article/details/gtztdizytj.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.vqdsnc.cn/Article/details/gtkfwzmfya.html

[R05] 参数默认值
来源：http://dali.xziqi.cn/Article/details/gtdkdwrout.html

name="${1:-default}"
来源：http://dali.redwolf501.top/Article/details/gtwqzzmcqq.html

[R06] 判断命令是否存在
来源：http://dali.feifeiyinyue.top/Article/details/gtujvfkhic.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yvedp.cn/Article/details/gtzxfuvjsd.html

[R07] if 判断文件
来源：http://dali.0kj1m.cn/Article/details/gtpvdsfxdx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.jinqigfzy.top/Article/details/gthptfaccs.html

[R08] 数值比较
来源：http://dali.xuanzx.com/Article/details/gtizzbbaof.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.haohaochexian.top/Article/details/gtgzaisvuy.html

[R09] 字符串比较
来源：http://dali.nanxinkj.top/Article/details/gtfgltpdue.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gtyjaverzn.html

[R10] 正则匹配
来源：http://dali.xuetiantiany.cn/Article/details/gtzwudflwo.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.redwolf501.top/Article/details/gtygbxyffm.html

[R11] case 多分支
来源：http://dali.shanyushiyangtech.top/Article/details/gtgfffwltt.html

case "$1" in
来源：http://dali.tian-w.cn/Article/details/gtjklexdff.html

start) echo "启动" ;;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtksbmuuxg.html

stop)  echo "停止" ;;
来源：http://dali.zhixingplan.top/Article/details/gtwbldkjvg.html

*)     echo "未知命令" ;;
来源：http://dali.jlsjyb.cn/Article/details/gtsybyibbp.html

esac
来源：http://dali.gotoacloud.top/Article/details/gtxftzbkzj.html

[R12] for 遍历文件
来源：http://dali.tian-w.cn/Article/details/gtwxvaadsa.html

for f in *.txt; do echo "$f"; done
来源：http://dali.mhx1999.top/Article/details/gtjioctkot.html

[R13] for 计数循环
来源：http://dali.cucudq.cn/Article/details/gtdshltxri.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhixingplan.top/Article/details/gtfrcskntr.html

[R14] C 风格 for
来源：http://dali.xuetiantiany.cn/Article/details/gtcyxotvrl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.hfpthk.cn/Article/details/gtqugzilos.html

[R15] while 逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrbumuwzh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.tian-w.cn/Article/details/gtblgtmhzk.html

[R16] until 等待条件
来源：http://dali.wangshuangyany.cn/Article/details/gtrfwbtoyk.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cdnleiting.top/Article/details/gtftqhblmq.html

[R17] 数组定义与取值
来源：http://dali.aibaodan.cn/Article/details/gtjoxljiof.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.9152youxi.cn/Article/details/gtmxdpshrs.html

[R18] 遍历数组
来源：http://dali.shanyushiyangtech.top/Article/details/gtssfbuiuu.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shzxlz.cn/Article/details/gturmyvtdx.html

[R19] 数组长度
来源：http://dali.ydzc1.top/Article/details/gtxxeqjaai.html

echo "${#arr[@]}"
来源：http://dali.nwbrower.top/Article/details/gtixcokbtr.html

[R20] 关联数组（字典）
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxwtledom.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.sxryk.cn/Article/details/gtberxvxfl.html

[R21] 字符串长度
来源：http://dali.xziqi.cn/Article/details/gtacrgxinm.html

echo "${#s}"
来源：http://dali.nanxinkj.top/Article/details/gtmixzqbmg.html

[R22] 截取子串
来源：http://dali.jinqigufen.top/Article/details/gtrziqtgbt.html

echo "${s:0:5}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gteuxfevpd.html

[R23] 字符串替换
来源：http://dali.nwbrower.top/Article/details/gtdikgzfqe.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.aizwys.cn/Article/details/gticdfjkab.html

[R24] 大小写转换
来源：http://dali.jqgufenzy.top/Article/details/gturybdtae.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinqigufen.top/Article/details/gtrmfixnyd.html

[R25] 去后缀 / 去前缀
来源：http://dali.smart0.xyz/Article/details/gtaaeylkcw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jiagoushi.top/Article/details/gtkkwneucl.html

[R26] 命令替换
来源：http://dali.cqqwz.cn/Article/details/gtknswzrgk.html

now=$(date +%F); echo "$now"
来源：http://dali.ydzc1.top/Article/details/gtiwfylsxe.html

[R27] 算术展开
来源：http://dali.iojbl.cn/Article/details/gtdhqyhszn.html

echo $((1 + 2 * 3))
来源：http://dali.aizwys.cn/Article/details/gtbacpjrhl.html

[R28] 浮点运算
来源：http://dali.ydzc1.top/Article/details/gtmfklkctn.html

echo "scale=2; 10/3" | bc
来源：http://dali.zycfv.cn/Article/details/gtilcnsqzi.html

[R29] 定义函数
来源：http://dali.gzhubu.top/Article/details/gtgfymzhdi.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sxryk.cn/Article/details/gtrevijmvi.html

[R30] 函数返回状态码
来源：http://dali.jinghuilouyu.cn/Article/details/gtjdovftri.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.c1oappe.top/Article/details/gtsnszcstu.html

[R31] 局部变量
来源：http://dali.nanxuanxn.top/Article/details/gtmwovyfki.html

f() { local x=1; echo "$x"; }
来源：http://dali.meibo888.top/Article/details/gtcixifapg.html

[R32] 参数个数校验
来源：http://dali.fengsongda.top/Article/details/gtyelgfeol.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhaomingkeji.xyz/Article/details/gtuonlzlyx.html

[R33] 捕获错误并提示行号
来源：http://dali.fzhhl.top/Article/details/gtccbwqhqq.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.guowangkeji.top/Article/details/gtswmfnwyl.html

[R34] 退出时清理
来源：http://dali.hysaishi.cn/Article/details/gtkaogdugb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jinqigufen.top/Article/details/gtibiowsmo.html

[R35] 后台执行并等待
来源：http://dali.shuidangran.top/Article/details/gtduxtwuyj.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hfpthk.cn/Article/details/gtfuqjpqvx.html

[R36] 并发执行多个任务
来源：http://dali.zhoulong.xyz/Article/details/gtsxpjigpf.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.sweek.top/Article/details/gtvvmrooke.html

[R37] 把输出赋给变量
来源：http://dali.nwbrower.top/Article/details/gtlcfkubye.html

files=$(ls -1)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthgkgodxa.html

[R38] 管道串联
来源：http://dali.zhiwuduotai.top/Article/details/gtejvhncos.html

cat a.txt | grep -i error | wc -l
来源：http://dali.hnxiangtu.top/Article/details/gthizlrtpb.html

[R39] 重定向标准输出与错误
来源：http://dali.ehwqpu.com/Article/details/gtglsmyqtm.html

cmd > out.log 2>&1
来源：http://dali.jinqigufen.top/Article/details/gtyzkbubar.html

[R40] 追加写日志
来源：http://dali.cashguo.top/Article/details/gtnhdqvpxo.html

echo "log" >> out.log
来源：http://dali.chenjidiqi.icu/Article/details/gtfgcwsokd.html

[R41] 丢弃输出
来源：http://dali.iojbl.cn/Article/details/gtzkslrtqt.html

cmd >/dev/null 2>&1
来源：http://dali.jinghuilouyu.cn/Article/details/gtvsonsmig.html

[R42] 输入重定向
来源：http://dali.chenlongwang.top/Article/details/gtpyokykew.html

wc -l < a.txt
来源：http://dali.jqgufenzy.top/Article/details/gtnflqkmgv.html

[R43] 按名字查找文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtppywidct.html

find . -name "*.log" -type f
来源：http://dali.shuidangran.top/Article/details/gtpjsgnmff.html

[R44] 按修改时间查找
来源：http://dali.zhoulong.xyz/Article/details/gtqhfhxmjf.html

find . -mtime -7 -type f
来源：http://dali.shanyushiyangtech.top/Article/details/gtfzrhlmxh.html

[R45] 批量删除
来源：http://dali.dianchejie.cn/Article/details/gtwcrphcia.html

find . -name "*.tmp" -delete
来源：http://dali.ywan-chungtsiang.top/Article/details/gtovmqoeqt.html

[R46] 递归替换文件内容
来源：http://dali.shzxlz.cn/Article/details/gtelaqaybf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yj202588.top/Article/details/gtxfbolxda.html

[R47] sed 单行替换
来源：http://dali.jqgufenzy.top/Article/details/gtbyjfkplr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.guowangkeji.top/Article/details/gtlztbgyes.html

[R48] awk 取指定列
来源：http://dali.jianghu66.top/Article/details/gtijnbeplh.html

awk '{print $1, $3}' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtixsbmpqn.html

[R49] awk 带条件
来源：http://dali.jlsjyb.cn/Article/details/gtuujnuhor.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.redwolf501.top/Article/details/gtfnqdalki.html

[R50] awk 求和
来源：http://dali.wangdashe.top/Article/details/gtbxxqqhjl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.jqgfzy.top/Article/details/gtutuukjwx.html

[R51] 排序去重取前几
来源：http://dali.guowangkeji.top/Article/details/gtchkrhzuj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ppjwa.cn/Article/details/gtfptixolq.html

[R52] 统计行数
来源：http://dali.cucudq.cn/Article/details/gtfmqyrqfh.html

wc -l a.txt
来源：http://dali.dashuyun.cn/Article/details/gtwuuagntl.html

[R53] 查看文件头与实时尾
来源：http://dali.yonumen.top/Article/details/gtbwovrviy.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.hongshengwenyu.top/Article/details/gtesklxvhh.html

[R54] 比较两个文件
来源：http://dali.jyoumei.cn/Article/details/gtkolcbeqk.html

diff a.txt b.txt
来源：http://dali.dianchejie.cn/Article/details/gtofabqhlx.html

[R55] 压缩与解压
来源：http://dali.yuanzhike.top/Article/details/gtrfzcvyun.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.havefunace.top/Article/details/gtwxycvciv.html

[R56] 远程拷贝
来源：http://dali.gogol.net.cn/Article/details/gtenicriuo.html

scp file user@host:/path/
来源：http://dali.ydzc1.top/Article/details/gthdmfyfwd.html

[R57] 远程执行命令
来源：http://dali.smart0.xyz/Article/details/gtjudzddfh.html

ssh user@host 'uptime'
来源：http://dali.haohaochexian.top/Article/details/gtyfoknele.html

[R58] 下载文件
来源：http://dali.zhengqikj.top/Article/details/gtgvpzjrzv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.cheryme.top/Article/details/gtjtamltoz.html

[R59] 发 POST JSON
来源：http://dali.xziqi.cn/Article/details/gtpzqorjsm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shzxlz.cn/Article/details/gtwcmpefvq.html

[R60] 只看 HTTP 状态码
来源：http://dali.0kj1m.cn/Article/details/gtgvionrnd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.snrcjt.cn/Article/details/gtozjouvun.html

[R61] 磁盘占用
来源：http://dali.xuetiantiany.cn/Article/details/gtasndpbqr.html

df -h;  du -sh *
来源：http://dali.daxiang520.top/Article/details/gtfueoufgu.html

[R62] 找最占空间的文件
来源：http://dali.shzxlz.cn/Article/details/gtzmrbpdmy.html

du -ah . | sort -rh | head -10
来源：http://dali.pengpengdd.cyou/Article/details/gtldxruelf.html

[R63] 内存与进程
来源：http://dali.sxryk.cn/Article/details/gtdtlfhjmw.html

free -h;  ps aux | grep nginx
来源：http://dali.shangyingyoupin.top/Article/details/gturvxgvcy.html

[R64] 结束进程
来源：http://dali.meibo888.top/Article/details/gtjthfpeqv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ehwqpu.com/Article/details/gttrmeetkb.html

[R65] 查看端口占用
来源：http://dali.andypj.xyz/Article/details/gtbujrdzlz.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.xinyue.icu/Article/details/gtsdufahwu.html

[R66] 定时任务
来源：http://dali.chenlongwang.top/Article/details/gtqixwuseo.html

crontab -e;  crontab -l
来源：http://dali.pycfn.com/Article/details/gtknstnemr.html

[R67] 生成随机十六进制串
来源：http://dali.ywan-chungtsiang.top/Article/details/gttfcolaak.html

openssl rand -hex 16
来源：http://dali.chenzaomai.com/Article/details/gtpfgvostf.html

[R68] 计算文件校验值
来源：http://dali.tanke756.top/Article/details/gtbsuwkwup.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.quarkkingdee.top/Article/details/gtrheiwxlb.html

[R69] 生成随机密码
来源：http://dali.nanxinkj.top/Article/details/gtqupjjfne.html

head -c 16 /dev/urandom | base64
来源：http://dali.ehwqpu.com/Article/details/gtprwwcgfp.html

[R70] 时间戳与互转
来源：http://dali.shangyingyoupin.top/Article/details/gtzrkjqsub.html

date +%s;  date -d @1700000000
来源：http://dali.dianchejie.cn/Article/details/gtyneeuivp.html

[R71] 日期格式化
来源：http://dali.nwbrower.top/Article/details/gtdgakemnv.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yonumen.top/Article/details/gtpituqssb.html

[R72] 等待端口就绪
来源：http://dali.pengpengdd.cyou/Article/details/gtfceaixur.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.daxiang520.top/Article/details/gtnimcujjm.html

[R73] 分割大日志
来源：http://dali.316326.xyz/Article/details/gtdbfusuqd.html

split -l 1000 big.log part_
来源：http://dali.kuanghao11.cn/Article/details/gtyrxxnyzr.html

[R74] 批量重命名
来源：http://dali.jinqigfzy.top/Article/details/gtlxgysqrl.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.sufxvd.cn/Article/details/gtvjjtlmar.html

[R75] 导出环境变量
来源：http://dali.tianlin.xyz/Article/details/gtchbiegxe.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.nanxuanxn.top/Article/details/gtlfpibexc.html

[R76] 使用临时文件
来源：http://dali.meibo888.top/Article/details/gtzdmsrdix.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.316326.xyz/Article/details/gtvwkyehhy.html

[R77] 读取用户输入
来源：http://dali.dianchejie.cn/Article/details/gtiribqaxh.html

read -rp "请输入: " ans
来源：http://dali.hysaishi.cn/Article/details/gttrgqumon.html

[R78] 交互式菜单
来源：http://dali.nanxuanxn.top/Article/details/gtiafeacrz.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.zhixingplan.top/Article/details/gtzurywmao.html

[R79] 解析命令行选项
来源：http://dali.ppjwa.cn/Article/details/gtmutqqyva.html


<!-- 参考信息 -->