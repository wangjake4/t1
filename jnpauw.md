代发 wailian999

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.yuanzhike.top/Article/details/gtxgxnoidw.html

[Q32] 分组拼接字符串
来源：http://dali.nanxinkj.top/Article/details/gtovoijbkw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.vqdsnc.cn/Article/details/gteahebzqg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtydzdlttj.html

[Q33] 多列分组
来源：http://dali.ybcxt.top/Article/details/gttublctpq.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.fengsongda.top/Article/details/gtjvzxfhup.html

[Q34] 每组取第一条
来源：http://dali.haohaochexian.top/Article/details/gtmuppmhhj.html

SELECT * FROM (
来源：http://dali.jlsjyb.cn/Article/details/gtclgqvhtr.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.wangshuangyany.cn/Article/details/gtvypipvzj.html

) t WHERE rn = 1;
来源：http://dali.xinyue.icu/Article/details/gtqyoupsmm.html

[Q35] 内连接
来源：http://dali.jiagoushi.top/Article/details/gtgvzwbbhv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xylfe.cn/Article/details/gtpxgubkgp.html

[Q36] 左连接
来源：http://dali.hnxiangtu.top/Article/details/gtsxihqpsc.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.redwolf501.top/Article/details/gtntkwtyqb.html

[Q37] 右连接
来源：http://dali.chenjidiqi.icu/Article/details/gtekzpedkw.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zdqjudy.top/Article/details/gtnapctgkd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.svipenyu.cn/Article/details/gtbicnlsbd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.jyoumei.cn/Article/details/gtfdlmpaaq.html

[Q39] 自连接（查上下级）
来源：http://dali.hywenlv.cn/Article/details/gtnvyutxrz.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jqgfzy.top/Article/details/gtoghjabbk.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.9152youxi.cn/Article/details/gtuvbtnvsb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hnqzz.top/Article/details/gthikmgguk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.chenjidiqi.icu/Article/details/gternsenql.html

[Q41] 多表连接
来源：http://dali.gogol.net.cn/Article/details/gtvycwepgh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.havefunace.top/Article/details/gtsrtpjoes.html

JOIN users u ON u.id = o.user_id
来源：http://dali.sysykeji.top/Article/details/gtxbowftcl.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.cheryme.top/Article/details/gtupuudfnq.html

[Q42] 连接条件附加过滤
来源：http://dali.guannengcc.top/Article/details/gtnnhamwem.html

SELECT u.name, o.amount FROM users u
来源：http://dali.sxryk.cn/Article/details/gtnvsupwcf.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yj202588.top/Article/details/gtqjftwclr.html

[Q43] 标量子查询
来源：http://dali.shangyingyoupin.top/Article/details/gtakkrorub.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yuanzhike.top/Article/details/gttkojwlxj.html

[Q44] IN 子查询
来源：http://dali.jyoumei.cn/Article/details/gtcoyogrxa.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.haohaochexian.top/Article/details/gtxprshqdq.html

[Q45] EXISTS 判断存在
来源：http://dali.havefunace.top/Article/details/gtckjejijb.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj202588.top/Article/details/gtxkupojgx.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.dashuyun.cn/Article/details/gtdczdtvsm.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.quarkkingdee.top/Article/details/gtvgjnjefd.html

[Q47] 与平均值比较
来源：http://dali.feifeiyinyue.top/Article/details/gttbsobaar.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.iojbl.cn/Article/details/gtbilgqibv.html

[Q48] CTE 公用表表达式
来源：http://dali.jinqigufen.top/Article/details/gtwfuqhdkk.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hnqzz.top/Article/details/gtprjlducm.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.daria6918.cn/Article/details/gtzpjwmxjb.html

[Q49] 更新单行
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfwashzqw.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.fengsongda.top/Article/details/gtrsrieune.html

[Q50] 批量更新
来源：http://dali.316326.xyz/Article/details/gtxtfbidtb.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.iojbl.cn/Article/details/gttjvcixrz.html

[Q51] 用子查询更新
来源：http://dali.quarkkingdee.top/Article/details/gtyigbpyac.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xinyue.icu/Article/details/gthhqzrwql.html

[Q52] 删除指定行
来源：http://dali.yangfankeji.com/Article/details/gtmkggifos.html

DELETE FROM users WHERE id = 10;
来源：http://dali.jlsjyb.cn/Article/details/gtanttrwbf.html

[Q53] 按条件删除
来源：http://dali.c1oappe.top/Article/details/gtqusnjxgn.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.shuidangran.top/Article/details/gtzkfalbzu.html

[Q54] 清空表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxbuajnqr.html

TRUNCATE TABLE logs;
来源：http://dali.hnqzz.top/Article/details/gtjobracul.html

[Q55] 排名（并列占位）
来源：http://dali.xuetiantiany.cn/Article/details/gtcvtbgosj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.feifeiyinyue.top/Article/details/gtvqxkkqpu.html

[Q56] 密集排名（并列不占位）
来源：http://dali.smart0.xyz/Article/details/gtxcxfqima.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ybcxt.top/Article/details/gtcafwilbc.html

[Q57] 行号
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgoqlzipk.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtmdcdrsvm.html

[Q58] 累计求和
来源：http://dali.9152youxi.cn/Article/details/gtgfjlrwdb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.yonumen.top/Article/details/gtuvaxwnpt.html

[Q59] 分组内累计
来源：http://dali.jinqigufen.top/Article/details/gthezxhprw.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xylfe.cn/Article/details/gtybxxrksb.html

[Q60] 取上一行 / 下一行
来源：http://dali.xziqi.cn/Article/details/gtabttegdh.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.tanke756.top/Article/details/gtykpcymlh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gtrpokilqn.html

[Q61] 移动平均
来源：http://dali.hnqzz.top/Article/details/gtjuefeqhz.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gtlwifkfth.html

[Q62] 分组占比
来源：http://dali.aizwys.cn/Article/details/gtcjypxuss.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jqgfzy.top/Article/details/gtkrkfmtiq.html

[Q63] 开启事务
来源：http://dali.ybcxt.top/Article/details/gttaowviff.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinyuanbaomall.cn/Article/details/gtepugdtpc.html

[Q64] 提交事务
来源：http://dali.yj20258.top/Article/details/gtidlwbeie.html

COMMIT;
来源：http://dali.ppjwa.cn/Article/details/gtvbsmsmdh.html

[Q65] 回滚事务
来源：http://dali.zhoulong.xyz/Article/details/gtljxpdpmb.html

ROLLBACK;
来源：http://dali.zdqjudy.top/Article/details/gtidnuanlh.html

[Q66] 行锁查询
来源：http://dali.svipenyu.cn/Article/details/gtfpxsvqjj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.hammf.cn/Article/details/gtcauzdtvj.html

[Q67] 设置隔离级别
来源：http://dali.guowangkeji.top/Article/details/gtilnenmgf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yvedp.cn/Article/details/gtrwpfzfva.html

[Q68] 保存点
来源：http://dali.ivvv.top/Article/details/gtdavqfjfw.html

SAVEPOINT sp1;
来源：http://dali.jianghu66.top/Article/details/gtlidjnmlp.html

ROLLBACK TO sp1;
来源：http://dali.yuxming.cn/Article/details/gtaiuxlwxl.html

[Q69] 查看执行计划
来源：http://dali.yonumen.top/Article/details/gtnasbeiem.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jqgufenzy.top/Article/details/gtztxwpedn.html

[Q70] 更新统计信息
来源：http://dali.birdmap.top/Article/details/gtqkixdjeo.html

ANALYZE TABLE users;
来源：http://dali.jqgfzy.top/Article/details/gtapkjgwoj.html

[Q71] 查看建表语句
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtfguxadif.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.gotoacloud.top/Article/details/gtfkmlkqka.html

[Q72] 查看索引
来源：http://dali.zycfv.cn/Article/details/gtpdtwcgen.html

SHOW INDEX FROM users;
来源：http://dali.daxiang520.top/Article/details/gtfqhziyga.html

[Q73] 查看表状态
来源：http://dali.aizwys.cn/Article/details/gtwsveswqe.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.yuanzhike.top/Article/details/gtdinmpsil.html

[Q74] 强制使用索引
来源：http://dali.yongpay.top/Article/details/gtojhrlngs.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.shzxlz.cn/Article/details/gtwnrinfqr.html

[Q75] 日期格式化
来源：http://dali.sxryk.cn/Article/details/gtfsdhqjyj.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkljzbffs.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.ybcxt.top/Article/details/gtrfwvppxd.html

[Q76] 按天统计
来源：http://dali.yvedp.cn/Article/details/gtbcpezlcb.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.cdnleiting.top/Article/details/gtpcwcnuwb.html

[Q77] 时间加减
来源：http://dali.feifeiyinyue.top/Article/details/gtdnemecih.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.jinqigufen.top/Article/details/gtqhoxayla.html

[Q78] 当前时间
来源：http://dali.cheryme.top/Article/details/gtdpceypnx.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.shangyingyoupin.top/Article/details/gtrukmcghq.html

[Q79] 字符串拼接
来源：http://dali.mhx1999.top/Article/details/gttruafxdy.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhongyouzk.top/Article/details/gtkowlpzus.html

[Q80] 字符串截取
来源：http://dali.dianchejie.cn/Article/details/gtwngdnvvo.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xinyue.icu/Article/details/gtvwbfbyej.html

[Q81] 字符串替换
来源：http://dali.kuanghao11.cn/Article/details/gteocmvbdj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jyoumei.cn/Article/details/gtcswjklxq.html

[Q82] 字符长度与字节长度
来源：http://dali.nwbrower.top/Article/details/gtoulyggrp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xziqi.cn/Article/details/gtwolbmqzd.html

[Q83] 大小写转换
来源：http://dali.dashuyun.cn/Article/details/gtizxbjfny.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.pycfn.com/Article/details/gtggwdvuqp.html

[Q84] 去除首尾空格
来源：http://dali.ivvv.top/Article/details/gtpyjmnoxo.html

SELECT TRIM(name) FROM users;
来源：http://dali.yvedp.cn/Article/details/gtivoqldjk.html

[Q85] 数值取整
来源：http://dali.ybcxt.top/Article/details/gtwxgnkcof.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.havefunace.top/Article/details/gtqipylmmm.html

[Q86] 读取 JSON 字段
来源：http://dali.pengpengdd.cyou/Article/details/gtvlgazfsf.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nanxinkj.top/Article/details/gtnqahrzwt.html

[Q87] JSON 字段做条件
来源：http://dali.havefunace.top/Article/details/gtoyjihlnk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.aibaodan.cn/Article/details/gtunylncrn.html

[Q88] 行转列（条件聚合）
来源：http://dali.0kj1m.cn/Article/details/gttnyrtehp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.jinyuanbaomall.cn/Article/details/gtoodvzlct.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jlsjyb.cn/Article/details/gtgwqatpgx.html

[Q89] 判断表是否存在
来源：http://dali.zdqjudy.top/Article/details/gtupecghmr.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.fengsongda.top/Article/details/gtxkqpdgtm.html

[Q90] 生成序号列
来源：http://dali.zhongyouzk.top/Article/details/gtozhvowfi.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hnqzz.top/Article/details/gtpubedxnu.html

================================================================================
来源：http://dali.dianchejie.cn/Article/details/gtgdxehzqo.html

R. Bash 专题
来源：http://dali.bjfxy.top/Article/details/gtwrlykzfl.html

================================================================================
来源：http://dali.chenlongwang.top/Article/details/gtmitxfkbv.html

[R01] shebang 与严格模式
来源：http://dali.hywenlv.cn/Article/details/gtcbubzjgc.html

#!/usr/bin/env bash
来源：http://dali.xylfe.cn/Article/details/gtcgcvnkhc.html

set -euo pipefail
来源：http://dali.wangshuangyany.cn/Article/details/gtcrawtlco.html

[R02] 变量赋值与使用
来源：http://dali.nanxuanxn.top/Article/details/gtqbtgmnib.html

name="Tom"; echo "$name"
来源：http://dali.jyoumei.cn/Article/details/gtcoqayqix.html

[R03] 只读变量
来源：http://dali.sufxvd.cn/Article/details/gtvhpxdgzp.html

readonly PI=3.14
来源：http://dali.yuanzhike.top/Article/details/gtryyduweg.html

[R04] 位置参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtdzawyecr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinghuilouyu.cn/Article/details/gttadszdxn.html

[R05] 参数默认值
来源：http://dali.hammf.cn/Article/details/gtaqxbsnaa.html

name="${1:-default}"
来源：http://dali.cheryme.top/Article/details/gtusfkpxco.html

[R06] 判断命令是否存在
来源：http://dali.aizwys.cn/Article/details/gtwloksapz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yj202588.top/Article/details/gtwuiwolcc.html

[R07] if 判断文件
来源：http://dali.dashuyun.cn/Article/details/gtfdndsyzu.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hammf.cn/Article/details/gtxoybmmwb.html

[R08] 数值比较
来源：http://dali.hongshengwenyu.top/Article/details/gthjdodzki.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.c1oappe.top/Article/details/gtlvwcnewa.html

[R09] 字符串比较
来源：http://dali.yvedp.cn/Article/details/gtzzdoetxj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ybcxt.top/Article/details/gtqubyalnd.html

[R10] 正则匹配
来源：http://dali.zhongyouzk.top/Article/details/gtcbrqmudd.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.snrcjt.cn/Article/details/gtioqyvamk.html

[R11] case 多分支
来源：http://dali.tianlin.xyz/Article/details/gtpogaxijk.html

case "$1" in
来源：http://dali.jqgfzy.top/Article/details/gtupnwsvav.html

start) echo "启动" ;;
来源：http://dali.shzxlz.cn/Article/details/gtmqyjbmkr.html

stop)  echo "停止" ;;
来源：http://dali.cashguo.top/Article/details/gtvlsrinor.html

*)     echo "未知命令" ;;
来源：http://dali.cashguo.top/Article/details/gtczbkhbgg.html

esac
来源：http://dali.chenlongwang.top/Article/details/gtttmlhgmv.html

[R12] for 遍历文件
来源：http://dali.redwolf501.top/Article/details/gtmtzliace.html

for f in *.txt; do echo "$f"; done
来源：http://dali.0kj1m.cn/Article/details/gtmycfwaxi.html

[R13] for 计数循环
来源：http://dali.cheryme.top/Article/details/gtdptjoapl.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.chenzaomai.com/Article/details/gtwzoiymst.html

[R14] C 风格 for
来源：http://dali.mhx1999.top/Article/details/gtxqnmmczj.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.iojbl.cn/Article/details/gtmbidwlfw.html

[R15] while 逐行读文件
来源：http://dali.haohaochexian.top/Article/details/gtwqqsmpbs.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.kuanghao11.cn/Article/details/gtoidippeo.html

[R16] until 等待条件
来源：http://dali.sweek.top/Article/details/gtmzpdwpwt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.316326.xyz/Article/details/gtpgrbbdel.html

[R17] 数组定义与取值
来源：http://dali.havefunace.top/Article/details/gtparutqcp.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.nanxuanxn.top/Article/details/gtriamoxfk.html

[R18] 遍历数组
来源：http://dali.yongpay.top/Article/details/gtbjhcrokg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jiagoushi.top/Article/details/gtyxttjsee.html

[R19] 数组长度
来源：http://dali.fengsongda.top/Article/details/gthdzsojwj.html

echo "${#arr[@]}"
来源：http://dali.shangyingyoupin.top/Article/details/gtgzfqgzsl.html

[R20] 关联数组（字典）
来源：http://dali.zycfv.cn/Article/details/gtgzhxjaas.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jyoumei.cn/Article/details/gtsimhertx.html

[R21] 字符串长度
来源：http://dali.yuanzhike.top/Article/details/gtuoalqopu.html

echo "${#s}"
来源：http://dali.hfpthk.cn/Article/details/gtgjitwykr.html

[R22] 截取子串
来源：http://dali.kuanghao11.cn/Article/details/gtytgjwhzd.html

echo "${s:0:5}"
来源：http://dali.ivvv.top/Article/details/gtpadmvxfy.html

[R23] 字符串替换
来源：http://dali.fzhhl.top/Article/details/gthgyqrmfp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jlsjyb.cn/Article/details/gtfmjpcxun.html

[R24] 大小写转换
来源：http://dali.snrcjt.cn/Article/details/gtpdrgnxxd.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.xuetiantiany.cn/Article/details/gtjllmkdej.html

[R25] 去后缀 / 去前缀
来源：http://dali.cqqwz.cn/Article/details/gtdxklusyq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.wangshuangyany.cn/Article/details/gteyfgrnjp.html

[R26] 命令替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdcyfyemd.html

now=$(date +%F); echo "$now"
来源：http://dali.shanyushiyangtech.top/Article/details/gthvyiamxe.html

[R27] 算术展开
来源：http://dali.pengpengdd.cyou/Article/details/gtwikkiztv.html

echo $((1 + 2 * 3))
来源：http://dali.xylfe.cn/Article/details/gtdefexwnj.html

[R28] 浮点运算
来源：http://dali.zdqjudy.top/Article/details/gtnatvsnot.html

echo "scale=2; 10/3" | bc
来源：http://dali.iojbl.cn/Article/details/gtufxetdff.html

[R29] 定义函数
来源：http://dali.sufxvd.cn/Article/details/gtnfbwnlig.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhijiandao.cn/Article/details/gtzrydtwda.html

[R30] 函数返回状态码
来源：http://dali.haohaochexian.top/Article/details/gtzbteuxkw.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrntxvglk.html

[R31] 局部变量
来源：http://dali.feifeiyinyue.top/Article/details/gtykgbdodb.html

f() { local x=1; echo "$x"; }
来源：http://dali.cqqwz.cn/Article/details/gtazvmobwj.html

[R32] 参数个数校验
来源：http://dali.0kj1m.cn/Article/details/gtfkkjaxon.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ivvv.top/Article/details/gtvimbhdqd.html

[R33] 捕获错误并提示行号
来源：http://dali.hammf.cn/Article/details/gtvbzeovme.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.bjfxy.top/Article/details/gtssbpzvex.html

[R34] 退出时清理
来源：http://dali.sufxvd.cn/Article/details/gtaatgidqq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.0kj1m.cn/Article/details/gtnlaouygg.html

[R35] 后台执行并等待
来源：http://dali.sysykeji.top/Article/details/gthxxhvxwr.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtifhcneda.html

[R36] 并发执行多个任务
来源：http://dali.hongshengwenyu.top/Article/details/gtmapkrdki.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.aizwys.cn/Article/details/gtravbbopa.html

[R37] 把输出赋给变量
来源：http://dali.jinyuanbaomall.cn/Article/details/gtochguhwx.html

files=$(ls -1)
来源：http://dali.yj202588.top/Article/details/gtldftrirk.html

[R38] 管道串联
来源：http://dali.svipenyu.cn/Article/details/gtzsckqfnp.html

cat a.txt | grep -i error | wc -l
来源：http://dali.wangdashe.top/Article/details/gtivezgsga.html

[R39] 重定向标准输出与错误
来源：http://dali.xuetiantiany.cn/Article/details/gthorjoigh.html

cmd > out.log 2>&1
来源：http://dali.dashuyun.cn/Article/details/gtzuxsftpj.html

[R40] 追加写日志
来源：http://dali.yuxming.cn/Article/details/gtaxkdsetm.html

echo "log" >> out.log
来源：http://dali.havefunace.top/Article/details/gtxbvjacix.html

[R41] 丢弃输出
来源：http://dali.yj20258888.top/Article/details/gtrecazjur.html

cmd >/dev/null 2>&1
来源：http://dali.jyoumei.cn/Article/details/gtetrpjbca.html

[R42] 输入重定向
来源：http://dali.hysaishi.cn/Article/details/gthqgadrou.html

wc -l < a.txt
来源：http://dali.meibo888.top/Article/details/gtkklvvpky.html

[R43] 按名字查找文件
来源：http://dali.9152youxi.cn/Article/details/gtirxyiklx.html

find . -name "*.log" -type f
来源：http://dali.yuxming.cn/Article/details/gtyeveoufk.html

[R44] 按修改时间查找
来源：http://dali.ybcxt.top/Article/details/gtljiimfpx.html

find . -mtime -7 -type f
来源：http://dali.wangshuangyany.cn/Article/details/gtjezktxpf.html

[R45] 批量删除
来源：http://dali.hysaishi.cn/Article/details/gtbjdftfpm.html

find . -name "*.tmp" -delete
来源：http://dali.kuanghao11.cn/Article/details/gtayjdauol.html

[R46] 递归替换文件内容
来源：http://dali.316326.xyz/Article/details/gtsyhdpfqt.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.hywenlv.cn/Article/details/gtfhyjxuor.html

[R47] sed 单行替换
来源：http://dali.cdnleiting.top/Article/details/gtrfcbitzt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gaohongyu789.top/Article/details/gtukebcvye.html

[R48] awk 取指定列
来源：http://dali.snrcjt.cn/Article/details/gtprcwudmg.html

awk '{print $1, $3}' a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtkqromevf.html

[R49] awk 带条件
来源：http://dali.xziqi.cn/Article/details/gtbebdymto.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinghuilouyu.cn/Article/details/gtycmcscpj.html

[R50] awk 求和
来源：http://dali.jiagoushi.top/Article/details/gtzlkceolq.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtltlcjjhy.html

[R51] 排序去重取前几
来源：http://dali.feifeiyinyue.top/Article/details/gtltolfybj.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jlsjyb.cn/Article/details/gtmicpmoqt.html

[R52] 统计行数
来源：http://dali.cheryme.top/Article/details/gtjigftpfc.html

wc -l a.txt
来源：http://dali.cashguo.top/Article/details/gtxdghjzac.html

[R53] 查看文件头与实时尾
来源：http://dali.redwolf501.top/Article/details/gtxctjzqck.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.yj20258888.top/Article/details/gtybyvhbcp.html

[R54] 比较两个文件
来源：http://dali.svipenyu.cn/Article/details/gtoyjsmgzv.html

diff a.txt b.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtvxdvcnys.html

[R55] 压缩与解压
来源：http://dali.shanyushiyangtech.top/Article/details/gtfqynluet.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.aibaodan.cn/Article/details/gtwcdigzsu.html

[R56] 远程拷贝
来源：http://dali.ywan-chungtsiang.top/Article/details/gtgphuckms.html

scp file user@host:/path/
来源：http://dali.9152youxi.cn/Article/details/gtanrhxxvk.html

[R57] 远程执行命令
来源：http://dali.feifeiyinyue.top/Article/details/gtyeelkuei.html

ssh user@host 'uptime'
来源：http://dali.nwbrower.top/Article/details/gtxvjvlunf.html

[R58] 下载文件
来源：http://dali.zhongyouzk.top/Article/details/gtwpjchrwx.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.zhixingplan.top/Article/details/gtqmfcqgjb.html

[R59] 发 POST JSON
来源：http://dali.xinyue.icu/Article/details/gtmiyenpgo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.dashuyun.cn/Article/details/gtklberhyq.html

[R60] 只看 HTTP 状态码
来源：http://dali.fzhhl.top/Article/details/gtrhnydpow.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.smart0.xyz/Article/details/gttrnusflf.html

[R61] 磁盘占用
来源：http://dali.zhoulong.xyz/Article/details/gtzrioozkc.html

df -h;  du -sh *
来源：http://dali.fengsongda.top/Article/details/gtxnjbpklu.html

[R62] 找最占空间的文件
来源：http://dali.zycfv.cn/Article/details/gtevhsnnzk.html

du -ah . | sort -rh | head -10
来源：http://dali.yangfankeji.com/Article/details/gtkqfegivq.html

[R63] 内存与进程
来源：http://dali.birdmap.top/Article/details/gtbkhahryd.html

free -h;  ps aux | grep nginx
来源：http://dali.fengsongda.top/Article/details/gtfcstjmkz.html

[R64] 结束进程
来源：http://dali.jiagoushi.top/Article/details/gtsycypqgl.html

kill -9 $(pgrep -f app.py)
来源：http://dali.chenjidiqi.icu/Article/details/gtldxjhzoc.html

[R65] 查看端口占用
来源：http://dali.guannengcc.top/Article/details/gtrgyefsox.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.shanyushiyangtech.top/Article/details/gtkexeyzlb.html

[R66] 定时任务
来源：http://dali.zhengqikj.top/Article/details/gtqoigtunw.html

crontab -e;  crontab -l
来源：http://dali.vqdsnc.cn/Article/details/gtnjvlqvzo.html

[R67] 生成随机十六进制串
来源：http://dali.yuanzhike.top/Article/details/gtproooehx.html

openssl rand -hex 16
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvdpbjsjb.html

[R68] 计算文件校验值
来源：http://dali.yangfankeji.com/Article/details/gtqlxkonab.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hnqzz.top/Article/details/gtlpgzpsqf.html

[R69] 生成随机密码
来源：http://dali.yangfankeji.com/Article/details/gtlnddkaev.html

head -c 16 /dev/urandom | base64
来源：http://dali.smart0.xyz/Article/details/gthubzxecv.html

[R70] 时间戳与互转
来源：http://dali.jyoumei.cn/Article/details/gtnbvqwsqz.html

date +%s;  date -d @1700000000
来源：http://dali.yj20258.top/Article/details/gtdmhwzeso.html

[R71] 日期格式化
来源：http://dali.zycfv.cn/Article/details/gtqnxaranq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ivvv.top/Article/details/gtvfrkstzu.html

[R72] 等待端口就绪
来源：http://dali.gotoacloud.top/Article/details/gtyugirify.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.tian-w.cn/Article/details/gtamoumlnt.html

[R73] 分割大日志
来源：http://dali.smart0.xyz/Article/details/gtyataaeaw.html

split -l 1000 big.log part_
来源：http://dali.zhoulong.xyz/Article/details/gtfxalyodc.html

[R74] 批量重命名
来源：http://dali.aibaodan.cn/Article/details/gtbapwrnzm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhixingplan.top/Article/details/gtrivzdzrd.html

[R75] 导出环境变量
来源：http://dali.cashguo.top/Article/details/gtzanhqofn.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.pengpengdd.cyou/Article/details/gtgfeiqmyi.html

[R76] 使用临时文件
来源：http://dali.shzxlz.cn/Article/details/gtoxrzleoq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.hnxiangtu.top/Article/details/gttcfggqsy.html

[R77] 读取用户输入
来源：http://dali.ywan-chungtsiang.top/Article/details/gthcmzzltn.html

read -rp "请输入: " ans
来源：http://dali.jyoumei.cn/Article/details/gtqdwmspre.html

[R78] 交互式菜单
来源：http://dali.yangfankeji.com/Article/details/gtksaifkls.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.sxryk.cn/Article/details/gtrpnwecck.html

[R79] 解析命令行选项
来源：http://dali.pengpengdd.cyou/Article/details/gtjgdiwgvw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.guannengcc.top/Article/details/gtztcojdxy.html

[R80] 查看脚本执行耗时
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvjmppsms.html

time ./run.sh
来源：http://dali.yonumen.top/Article/details/gtzqpvekqd.html

================================================================================
来源：http://dali.yonumen.top/Article/details/gtudosrhbq.html


<!-- 参考信息 -->