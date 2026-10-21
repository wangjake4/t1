代发 wailian999

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.redwolf501.top/Article/details/gtmfzqvbxy.html

[Q32] 分组拼接字符串
来源：http://dali.nanxuanxn.top/Article/details/gtylnpxnbk.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yueranfly.top/Article/details/gtzsmljqzv.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yvedp.cn/Article/details/gtlihopyfa.html

[Q33] 多列分组
来源：http://dali.nanxuanxn.top/Article/details/gtiopcloew.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shuidangran.top/Article/details/gtsyadjrlg.html

[Q34] 每组取第一条
来源：http://dali.zhiwuduotai.top/Article/details/gtifcnnhht.html

SELECT * FROM (
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnpkfkwcl.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shanyushiyangkeji.top/Article/details/gtkpnqmbmf.html

) t WHERE rn = 1;
来源：http://dali.yuxming.cn/Article/details/gtpddxqimz.html

[Q35] 内连接
来源：http://dali.jlsjyb.cn/Article/details/gttvhshacg.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.shuidangran.top/Article/details/gtwakeevlp.html

[Q36] 左连接
来源：http://dali.jinyuanbaomall.cn/Article/details/gtucjxbpcf.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.quarkkingdee.top/Article/details/gtslbdffvo.html

[Q37] 右连接
来源：http://dali.sufxvd.cn/Article/details/gtufcvjbfy.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.sweek.top/Article/details/gtiffbtqwd.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ybcxt.top/Article/details/gtpbrqfyur.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.shanyushiyangtech.top/Article/details/gtezzozahi.html

[Q39] 自连接（查上下级）
来源：http://dali.chenlongwang.top/Article/details/gtulkiwmyg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ybcxt.top/Article/details/gtvutugbyf.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.guannengcc.top/Article/details/gtbniimkmi.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.sufxvd.cn/Article/details/gtoabbopwg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.cqqwz.cn/Article/details/gtfhivdjxn.html

[Q41] 多表连接
来源：http://dali.sysykeji.top/Article/details/gtkgljmfix.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zycfv.cn/Article/details/gtycuscher.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yangfankeji.com/Article/details/gtsfyvqxaw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.vqdsnc.cn/Article/details/gtpicgrmul.html

[Q42] 连接条件附加过滤
来源：http://dali.jqgufenzy.top/Article/details/gtrhyqbael.html

SELECT u.name, o.amount FROM users u
来源：http://dali.jinghuilouyu.cn/Article/details/gtqzwajjuk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yueranfly.top/Article/details/gtreozewwb.html

[Q43] 标量子查询
来源：http://dali.fzhhl.top/Article/details/gtvftqvchh.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.xylfe.cn/Article/details/gtosyailsh.html

[Q44] IN 子查询
来源：http://dali.ybcxt.top/Article/details/gtowrxhjjb.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cashguo.top/Article/details/gtpznjgszk.html

[Q45] EXISTS 判断存在
来源：http://dali.haohaochexian.top/Article/details/gtytqzcjtt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jqgfzy.top/Article/details/gtgrfitrlg.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.cashguo.top/Article/details/gtxigtilxu.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hongshengwenyu.top/Article/details/gtajxykbhx.html

[Q47] 与平均值比较
来源：http://dali.shangyingyoupin.top/Article/details/gtkjxejjph.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.dianchejie.cn/Article/details/gtqwisoxjx.html

[Q48] CTE 公用表表达式
来源：http://dali.jianghu66.top/Article/details/gtgjirxlac.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.xinyue.icu/Article/details/gtjnlnwdrs.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.pengpengdd.cyou/Article/details/gtnnxpdoft.html

[Q49] 更新单行
来源：http://dali.havefunace.top/Article/details/gtuayunldj.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.jinqigufen.top/Article/details/gtxijxjtel.html

[Q50] 批量更新
来源：http://dali.ivvv.top/Article/details/gtgncdwxkg.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinyuanbaomall.cn/Article/details/gtdszqcywe.html

[Q51] 用子查询更新
来源：http://dali.chenlongwang.top/Article/details/gtwiauvfau.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.tianlin.xyz/Article/details/gteeqjtjhh.html

[Q52] 删除指定行
来源：http://dali.xuanzx.com/Article/details/gtwzmkvvoe.html

DELETE FROM users WHERE id = 10;
来源：http://dali.nwbrower.top/Article/details/gtygpcfiuh.html

[Q53] 按条件删除
来源：http://dali.wangdashe.top/Article/details/gtfezkpjqb.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.daxiang520.top/Article/details/gtstarzmhu.html

[Q54] 清空表
来源：http://dali.kuanghao11.cn/Article/details/gtpryvqbma.html

TRUNCATE TABLE logs;
来源：http://dali.redwolf501.top/Article/details/gtzykftmws.html

[Q55] 排名（并列占位）
来源：http://dali.jqgfzy.top/Article/details/gtakxeygnu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.fengsongda.top/Article/details/gtddprzajn.html

[Q56] 密集排名（并列不占位）
来源：http://dali.sweek.top/Article/details/gtexmjojfl.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gogol.net.cn/Article/details/gtpjelihxp.html

[Q57] 行号
来源：http://dali.andypj.xyz/Article/details/gtfiiisfxq.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zycfv.cn/Article/details/gtoycazaas.html

[Q58] 累计求和
来源：http://dali.zhengqikj.top/Article/details/gtrtdhevrh.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhengqikj.top/Article/details/gttcjmmjfx.html

[Q59] 分组内累计
来源：http://dali.ybcxt.top/Article/details/gtuizwmark.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtcxtvjykc.html

[Q60] 取上一行 / 下一行
来源：http://dali.meibo888.top/Article/details/gtxvnbydeg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yj20258888.top/Article/details/gtxuxlhauu.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yueranfly.top/Article/details/gtceqiumpo.html

[Q61] 移动平均
来源：http://dali.ehwqpu.com/Article/details/gtikgtvkhf.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.nwbrower.top/Article/details/gtlkznhbsb.html

[Q62] 分组占比
来源：http://dali.jyoumei.cn/Article/details/gtltftwyej.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtfqkujwry.html

[Q63] 开启事务
来源：http://dali.daxiang520.top/Article/details/gtcqumwwka.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xuetiantiany.cn/Article/details/gttmudcqbi.html

[Q64] 提交事务
来源：http://dali.smart0.xyz/Article/details/gtuaajqzxd.html

COMMIT;
来源：http://dali.hnqzz.top/Article/details/gtoxntqfgu.html

[Q65] 回滚事务
来源：http://dali.xuetiantiany.cn/Article/details/gtsussuwdo.html

ROLLBACK;
来源：http://dali.iojbl.cn/Article/details/gtviknuhpv.html

[Q66] 行锁查询
来源：http://dali.cashguo.top/Article/details/gtgyjbaldl.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.mhx1999.top/Article/details/gthzvysqge.html

[Q67] 设置隔离级别
来源：http://dali.zhixingplan.top/Article/details/gtmiikjcnc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.fengsongda.top/Article/details/gthadxfsmt.html

[Q68] 保存点
来源：http://dali.vqdsnc.cn/Article/details/gtfxzrjsmu.html

SAVEPOINT sp1;
来源：http://dali.jinqigfzy.top/Article/details/gtrtqbajbb.html

ROLLBACK TO sp1;
来源：http://dali.yuxming.cn/Article/details/gtxddhcsyu.html

[Q69] 查看执行计划
来源：http://dali.jinqigfzy.top/Article/details/gthedgrzpr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yj20258.top/Article/details/gtxejfkabm.html

[Q70] 更新统计信息
来源：http://dali.snrcjt.cn/Article/details/gtsgxpobir.html

ANALYZE TABLE users;
来源：http://dali.hfpthk.cn/Article/details/gtsafwcjrp.html

[Q71] 查看建表语句
来源：http://dali.zhengqikj.top/Article/details/gtuqfrsqxn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.jqgufenzy.top/Article/details/gtcgzuotkc.html

[Q72] 查看索引
来源：http://dali.yangfankeji.com/Article/details/gtmizdmglf.html

SHOW INDEX FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtdcwxtlyl.html

[Q73] 查看表状态
来源：http://dali.hammf.cn/Article/details/gtaubmklyv.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.c1oappe.top/Article/details/gtswxmkusz.html

[Q74] 强制使用索引
来源：http://dali.gotoacloud.top/Article/details/gtgaqibeqz.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.tanke756.top/Article/details/gtazqgwdqw.html

[Q75] 日期格式化
来源：http://dali.jinqigfzy.top/Article/details/gtqvuwmdks.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtxlohvlzg.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.snrcjt.cn/Article/details/gttaxaxhwu.html

[Q76] 按天统计
来源：http://dali.sufxvd.cn/Article/details/gtsiedtzyn.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.hysaishi.cn/Article/details/gthuaezpls.html

[Q77] 时间加减
来源：http://dali.haohaochexian.top/Article/details/gtkgrcrqqm.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.dianchejie.cn/Article/details/gthpwxiwtw.html

[Q78] 当前时间
来源：http://dali.gotoacloud.top/Article/details/gtcfbasbdl.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hywenlv.cn/Article/details/gtaddsopst.html

[Q79] 字符串拼接
来源：http://dali.cdnleiting.top/Article/details/gtintnozfe.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ydzc1.top/Article/details/gtzgxzpcic.html

[Q80] 字符串截取
来源：http://dali.shuidangran.top/Article/details/gtfdgdvqwl.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xuanzx.com/Article/details/gtplvdehha.html

[Q81] 字符串替换
来源：http://dali.yangfankeji.com/Article/details/gtxhujyzbe.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtloxwmelv.html

[Q82] 字符长度与字节长度
来源：http://dali.dianchejie.cn/Article/details/gtbgyxtifp.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtcfcljayb.html

[Q83] 大小写转换
来源：http://dali.shzxlz.cn/Article/details/gtxoeawesp.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlrvlhtkl.html

[Q84] 去除首尾空格
来源：http://dali.yj20258.top/Article/details/gtnvbebksm.html

SELECT TRIM(name) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtiusccyla.html

[Q85] 数值取整
来源：http://dali.shuidangran.top/Article/details/gtrmbzfeef.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.jinqigfzy.top/Article/details/gtjrbjeeij.html

[Q86] 读取 JSON 字段
来源：http://dali.c1oappe.top/Article/details/gtwtlpeolt.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zdqjudy.top/Article/details/gthtvonwxh.html

[Q87] JSON 字段做条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtqprzjuzh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.chenzaomai.com/Article/details/gtcvoylvtk.html

[Q88] 行转列（条件聚合）
来源：http://dali.jianghu66.top/Article/details/gtzzuygrji.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.nanxuanxn.top/Article/details/gtmyfaobks.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtmxobmowe.html

[Q89] 判断表是否存在
来源：http://dali.sysykeji.top/Article/details/gtjmfnigge.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nanxuanxn.top/Article/details/gtroyemivo.html

[Q90] 生成序号列
来源：http://dali.nwbrower.top/Article/details/gtvuayynss.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.fzhhl.top/Article/details/gtgbpxlzea.html

================================================================================
来源：http://dali.birdmap.top/Article/details/gtyzppfshe.html

R. Bash 专题
来源：http://dali.yonumen.top/Article/details/gtfkktzifq.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gtqcrlpgom.html

[R01] shebang 与严格模式
来源：http://dali.sxryk.cn/Article/details/gtxlsnuxbx.html

#!/usr/bin/env bash
来源：http://dali.yongpay.top/Article/details/gtbhthvdmw.html

set -euo pipefail
来源：http://dali.tanke756.top/Article/details/gtyfffybbu.html

[R02] 变量赋值与使用
来源：http://dali.birdmap.top/Article/details/gtmbplhziv.html

name="Tom"; echo "$name"
来源：http://dali.ivvv.top/Article/details/gtzgrkoagp.html

[R03] 只读变量
来源：http://dali.hongshengwenyu.top/Article/details/gtutwdsflv.html

readonly PI=3.14
来源：http://dali.yuanzhike.top/Article/details/gthdzpwmlh.html

[R04] 位置参数
来源：http://dali.aibaodan.cn/Article/details/gtbwynrmhr.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.sufxvd.cn/Article/details/gtttnidxzl.html

[R05] 参数默认值
来源：http://dali.guowangkeji.top/Article/details/gtvmhjzqov.html

name="${1:-default}"
来源：http://dali.dianchejie.cn/Article/details/gtewomslnw.html

[R06] 判断命令是否存在
来源：http://dali.fzhhl.top/Article/details/gtdyygyhbd.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.hammf.cn/Article/details/gtglfflgro.html

[R07] if 判断文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtewkxjquq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.smart0.xyz/Article/details/gtuogykuvn.html

[R08] 数值比较
来源：http://dali.xinyue.icu/Article/details/gtenzfcasd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cheryme.top/Article/details/gtcbuynwst.html

[R09] 字符串比较
来源：http://dali.chenzaomai.com/Article/details/gtpivnnzwv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.chenzaomai.com/Article/details/gtbccpqgnb.html

[R10] 正则匹配
来源：http://dali.fzhhl.top/Article/details/gtewuxrdok.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.nanxuanxn.top/Article/details/gtizmlvtxd.html

[R11] case 多分支
来源：http://dali.shanyushiyangtech.top/Article/details/gtlaeftcew.html

case "$1" in
来源：http://dali.jyoumei.cn/Article/details/gtmfnvtigb.html

start) echo "启动" ;;
来源：http://dali.jinqigufen.top/Article/details/gtxcgvaqbj.html

stop)  echo "停止" ;;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtagvhtbzo.html

*)     echo "未知命令" ;;
来源：http://dali.cucudq.cn/Article/details/gtvdmuavpf.html

esac
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkvpsmnnb.html

[R12] for 遍历文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkrgiwobk.html

for f in *.txt; do echo "$f"; done
来源：http://dali.cucudq.cn/Article/details/gtnzacjlzp.html

[R13] for 计数循环
来源：http://dali.cdnleiting.top/Article/details/gtaxljvxvw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ivvv.top/Article/details/gtqtcglhtl.html

[R14] C 风格 for
来源：http://dali.jianghu66.top/Article/details/gtvucnbnmp.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gtpxxniteu.html

[R15] while 逐行读文件
来源：http://dali.zhoulong.xyz/Article/details/gtacayikya.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.chenzaomai.com/Article/details/gtszxfhpqh.html

[R16] until 等待条件
来源：http://dali.chenzaomai.com/Article/details/gtrsdkopni.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.andypj.xyz/Article/details/gtjtvnzgxj.html

[R17] 数组定义与取值
来源：http://dali.sysykeji.top/Article/details/gtfluosybh.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.yj202588.top/Article/details/gtrahikkco.html

[R18] 遍历数组
来源：http://dali.xuetiantiany.cn/Article/details/gtzodzqadq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.aizwys.cn/Article/details/gtzkmdkwid.html

[R19] 数组长度
来源：http://dali.xylfe.cn/Article/details/gtuxhvlryi.html

echo "${#arr[@]}"
来源：http://dali.fengsongda.top/Article/details/gtezsktxjp.html

[R20] 关联数组（字典）
来源：http://dali.tanke756.top/Article/details/gtzrnkercf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.daria6918.cn/Article/details/gtkrdcpioi.html

[R21] 字符串长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtukidrlrh.html

echo "${#s}"
来源：http://dali.zdqjudy.top/Article/details/gtloiutnza.html

[R22] 截取子串
来源：http://dali.meibo888.top/Article/details/gtxykgmpki.html

echo "${s:0:5}"
来源：http://dali.316326.xyz/Article/details/gtzyikknxq.html

[R23] 字符串替换
来源：http://dali.shuidangran.top/Article/details/gtxmuiwbmv.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.guannengcc.top/Article/details/gtsdszpdew.html

[R24] 大小写转换
来源：http://dali.sufxvd.cn/Article/details/gtwcazrdyy.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cucudq.cn/Article/details/gttzxnhngr.html

[R25] 去后缀 / 去前缀
来源：http://dali.xziqi.cn/Article/details/gtepkpxfhm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.316326.xyz/Article/details/gttxpqcijw.html

[R26] 命令替换
来源：http://dali.tianlin.xyz/Article/details/gttfvgstly.html

now=$(date +%F); echo "$now"
来源：http://dali.ybcxt.top/Article/details/gtmeqlazsa.html

[R27] 算术展开
来源：http://dali.redwolf501.top/Article/details/gtnzvwrcna.html

echo $((1 + 2 * 3))
来源：http://dali.smart0.xyz/Article/details/gtghlltiie.html

[R28] 浮点运算
来源：http://dali.sufxvd.cn/Article/details/gtqupfeklg.html

echo "scale=2; 10/3" | bc
来源：http://dali.smart0.xyz/Article/details/gtqtdadxkw.html

[R29] 定义函数
来源：http://dali.yuanzhike.top/Article/details/gtdbdvbyeo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinghuilouyu.cn/Article/details/gtfzqusopp.html

[R30] 函数返回状态码
来源：http://dali.aibaodan.cn/Article/details/gtaaydktwm.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.pengpengdd.cyou/Article/details/gtypplhgjr.html

[R31] 局部变量
来源：http://dali.xuanzx.com/Article/details/gtttiwntud.html

f() { local x=1; echo "$x"; }
来源：http://dali.xylfe.cn/Article/details/gtjbpdcfli.html

[R32] 参数个数校验
来源：http://dali.andypj.xyz/Article/details/gtbxrrybdf.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.daxiang520.top/Article/details/gttcrctjaf.html

[R33] 捕获错误并提示行号
来源：http://dali.ppjwa.cn/Article/details/gtagvenjry.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.andypj.xyz/Article/details/gtgvgckbfs.html

[R34] 退出时清理
来源：http://dali.cheryme.top/Article/details/gtuophkhjq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.pycfn.com/Article/details/gtafdulsno.html

[R35] 后台执行并等待
来源：http://dali.pengpengdd.cyou/Article/details/gtfjvssnsh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.wangshuangyany.cn/Article/details/gtomgesjan.html

[R36] 并发执行多个任务
来源：http://dali.yuanzhike.top/Article/details/gtrcyqwsfb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.xinyue.icu/Article/details/gtgrekuapb.html

[R37] 把输出赋给变量
来源：http://dali.gzhubu.top/Article/details/gtcedhbzkc.html

files=$(ls -1)
来源：http://dali.jinqigufen.top/Article/details/gtteleakei.html

[R38] 管道串联
来源：http://dali.nanxuanxn.top/Article/details/gtpwwnyiyv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.yueranfly.top/Article/details/gtbucjohyy.html

[R39] 重定向标准输出与错误
来源：http://dali.shzxlz.cn/Article/details/gtexptevva.html

cmd > out.log 2>&1
来源：http://dali.cdnleiting.top/Article/details/gtujqezifv.html

[R40] 追加写日志
来源：http://dali.smart0.xyz/Article/details/gtambvkrct.html

echo "log" >> out.log
来源：http://dali.iojbl.cn/Article/details/gtwkkgymhz.html

[R41] 丢弃输出
来源：http://dali.sufxvd.cn/Article/details/gtwqwezwhv.html

cmd >/dev/null 2>&1
来源：http://dali.havefunace.top/Article/details/gttyszszza.html

[R42] 输入重定向
来源：http://dali.yueranfly.top/Article/details/gthhlblweo.html

wc -l < a.txt
来源：http://dali.jiagoushi.top/Article/details/gtcilznarz.html

[R43] 按名字查找文件
来源：http://dali.xuetiantiany.cn/Article/details/gtsyzzpemp.html

find . -name "*.log" -type f
来源：http://dali.hammf.cn/Article/details/gtnkuntzej.html

[R44] 按修改时间查找
来源：http://dali.jqgufenzy.top/Article/details/gtzkupvfkl.html

find . -mtime -7 -type f
来源：http://dali.nanxuanxn.top/Article/details/gtytpsbiyp.html

[R45] 批量删除
来源：http://dali.pycfn.com/Article/details/gtjsilkrku.html

find . -name "*.tmp" -delete
来源：http://dali.yonumen.top/Article/details/gtrxiiyjvn.html

[R46] 递归替换文件内容
来源：http://dali.yj202588.top/Article/details/gtqbzffjcw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.fzhhl.top/Article/details/gtkjyanlhv.html

[R47] sed 单行替换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtagbwkzwn.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.gogol.net.cn/Article/details/gtayvscget.html

[R48] awk 取指定列
来源：http://dali.9152youxi.cn/Article/details/gtwlfhytyr.html

awk '{print $1, $3}' a.txt
来源：http://dali.tanke756.top/Article/details/gtukhwpjyh.html

[R49] awk 带条件
来源：http://dali.hywenlv.cn/Article/details/gtsulojhqg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.sysykeji.top/Article/details/gtyitcoblw.html

[R50] awk 求和
来源：http://dali.zhijiandao.cn/Article/details/gtsvzspbiv.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.vqdsnc.cn/Article/details/gtaydzknzg.html

[R51] 排序去重取前几
来源：http://dali.xinyue.icu/Article/details/gtxorptbtr.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.gaohongyu789.top/Article/details/gtjkqbostw.html

[R52] 统计行数
来源：http://dali.tianlin.xyz/Article/details/gtzxhpjfgj.html

wc -l a.txt
来源：http://dali.sysykeji.top/Article/details/gtsdnzqnwu.html

[R53] 查看文件头与实时尾
来源：http://dali.sysykeji.top/Article/details/gthfrkjqel.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tanke756.top/Article/details/gtmcttnphh.html

[R54] 比较两个文件
来源：http://dali.xuetiantiany.cn/Article/details/gthgvzqosp.html

diff a.txt b.txt
来源：http://dali.zdqjudy.top/Article/details/gtqmrffply.html

[R55] 压缩与解压
来源：http://dali.haohaochexian.top/Article/details/gtqyylxaae.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.chenzaomai.com/Article/details/gtkhvyutsi.html

[R56] 远程拷贝
来源：http://dali.nanxuanxn.top/Article/details/gtxxyxjowz.html

scp file user@host:/path/
来源：http://dali.shzxlz.cn/Article/details/gtoxomkbmd.html

[R57] 远程执行命令
来源：http://dali.ppjwa.cn/Article/details/gtbnprxrcl.html

ssh user@host 'uptime'
来源：http://dali.shangyingyoupin.top/Article/details/gticpginvp.html

[R58] 下载文件
来源：http://dali.cashguo.top/Article/details/gtqwknpuwj.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.xziqi.cn/Article/details/gtxqmzmgep.html

[R59] 发 POST JSON
来源：http://dali.kuanghao11.cn/Article/details/gtyuytranq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xuanzx.com/Article/details/gtrqeajkzi.html

[R60] 只看 HTTP 状态码
来源：http://dali.yuxming.cn/Article/details/gttftzwxug.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yonumen.top/Article/details/gtalvotbqf.html

[R61] 磁盘占用
来源：http://dali.feifeiyinyue.top/Article/details/gttkiucxqf.html

df -h;  du -sh *
来源：http://dali.svipenyu.cn/Article/details/gtvflrvffh.html

[R62] 找最占空间的文件
来源：http://dali.9152youxi.cn/Article/details/gtvirhoaaa.html

du -ah . | sort -rh | head -10
来源：http://dali.aizwys.cn/Article/details/gthfghklsk.html

[R63] 内存与进程
来源：http://dali.gogol.net.cn/Article/details/gtweufgbpx.html

free -h;  ps aux | grep nginx
来源：http://dali.gzhubu.top/Article/details/gtqztxfzmf.html

[R64] 结束进程
来源：http://dali.aizwys.cn/Article/details/gtfhqmzzhw.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hammf.cn/Article/details/gtzkubcbye.html

[R65] 查看端口占用
来源：http://dali.zhongyouzk.top/Article/details/gtifrfpezr.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.guowangkeji.top/Article/details/gtjmdxanbl.html

[R66] 定时任务
来源：http://dali.zhijiandao.cn/Article/details/gtmutrmokp.html

crontab -e;  crontab -l
来源：http://dali.kuanghao11.cn/Article/details/gtqizyqqbz.html

[R67] 生成随机十六进制串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlvyuipru.html

openssl rand -hex 16
来源：http://dali.zhixingplan.top/Article/details/gtfwdwgznr.html

[R68] 计算文件校验值
来源：http://dali.aibaodan.cn/Article/details/gtptvgjagu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.cqqwz.cn/Article/details/gtbwfaeigf.html

[R69] 生成随机密码
来源：http://dali.chenjidiqi.icu/Article/details/gtoxwvzqpj.html

head -c 16 /dev/urandom | base64
来源：http://dali.gzhubu.top/Article/details/gtfjzvgypk.html

[R70] 时间戳与互转
来源：http://dali.yj20258888.top/Article/details/gtydgucsrb.html

date +%s;  date -d @1700000000
来源：http://dali.nwbrower.top/Article/details/gtfjtsngbx.html

[R71] 日期格式化
来源：http://dali.hfpthk.cn/Article/details/gtblsdqbyo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hywenlv.cn/Article/details/gtzjrojqnm.html

[R72] 等待端口就绪
来源：http://dali.sysykeji.top/Article/details/gteyjxhacc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.aibaodan.cn/Article/details/gttvwywzjp.html

[R73] 分割大日志
来源：http://dali.jqgufenzy.top/Article/details/gtffgsxvvw.html

split -l 1000 big.log part_
来源：http://dali.sxryk.cn/Article/details/gtmtpuodpf.html

[R74] 批量重命名
来源：http://dali.yj20258888.top/Article/details/gtmwyxhnow.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.xinyue.icu/Article/details/gtqvlaafgm.html

[R75] 导出环境变量
来源：http://dali.316326.xyz/Article/details/gtbbuaohzm.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.redwolf501.top/Article/details/gtvqtzbvkw.html

[R76] 使用临时文件
来源：http://dali.kuanghao11.cn/Article/details/gtghanwlcg.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.gogol.net.cn/Article/details/gtevduquqb.html

[R77] 读取用户输入
来源：http://dali.jlsjyb.cn/Article/details/gtrkpttdau.html

read -rp "请输入: " ans
来源：http://dali.zhengqikj.top/Article/details/gtptgrywns.html

[R78] 交互式菜单
来源：http://dali.gogol.net.cn/Article/details/gtcmytgdrk.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.iojbl.cn/Article/details/gtafphgkhz.html

[R79] 解析命令行选项
来源：http://dali.jqgfzy.top/Article/details/gtgcxyamhm.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.haohaochexian.top/Article/details/gteiswavym.html

[R80] 查看脚本执行耗时
来源：http://dali.mhx1999.top/Article/details/gtzmncqhni.html

time ./run.sh
来源：http://dali.wangshuangyany.cn/Article/details/gtkvdvdvjo.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtfzpnjhti.html


<!-- 参考信息 -->