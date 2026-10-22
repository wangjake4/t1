代发 wailian999

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yj20258888.top/Article/details/gtuljogaqw.html

[Q28] 求和与平均
来源：http://dali.yj202588.top/Article/details/gtdgbgsycc.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.meibo888.top/Article/details/gtufmucljf.html

[Q29] 最大最小值
来源：http://dali.vqdsnc.cn/Article/details/gtmotwvfwr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtkgrxgjhs.html

[Q30] 分组统计
来源：http://dali.jinqigufen.top/Article/details/gtjmhniyhu.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gtmprutfkc.html

[Q31] 分组后过滤
来源：http://dali.xylfe.cn/Article/details/gtcbvecvgx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.wangshuangyany.cn/Article/details/gtcyvimqxu.html

[Q32] 分组拼接字符串
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiinengqx.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.0kj1m.cn/Article/details/gtjtibgqxg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.haohaochexian.top/Article/details/gtwsqjxorr.html

[Q33] 多列分组
来源：http://dali.shzxlz.cn/Article/details/gtgndvitvg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shuidangran.top/Article/details/gtfvbhgqon.html

[Q34] 每组取第一条
来源：http://dali.sweek.top/Article/details/gtczhlmpvz.html

SELECT * FROM (
来源：http://dali.zhixingplan.top/Article/details/gtmgchhzjx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.yj20258888.top/Article/details/gtmdvssptj.html

) t WHERE rn = 1;
来源：http://dali.nanxinkj.top/Article/details/gtfyhrlfqm.html

[Q35] 内连接
来源：http://dali.quarkkingdee.top/Article/details/gtjsrvehmk.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.9152youxi.cn/Article/details/gtxdnawezn.html

[Q36] 左连接
来源：http://dali.cqqwz.cn/Article/details/gthmnoadjz.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yj202588.top/Article/details/gtqgcteagg.html

[Q37] 右连接
来源：http://dali.zhoulong.xyz/Article/details/gthawcysfe.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gogol.net.cn/Article/details/gtkijpefqf.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.redwolf501.top/Article/details/gtzeldxvpx.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gotoacloud.top/Article/details/gtqhffatxo.html

[Q39] 自连接（查上下级）
来源：http://dali.zdqjudy.top/Article/details/gtaanyqfra.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfpbdwuyi.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.sysykeji.top/Article/details/gtxasyavzy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.nwbrower.top/Article/details/gtmjfcynzo.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zdqjudy.top/Article/details/gtijdzrhox.html

[Q41] 多表连接
来源：http://dali.zhiwuduotai.top/Article/details/gtlkbkoesq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.xylfe.cn/Article/details/gtrtipawik.html

JOIN users u ON u.id = o.user_id
来源：http://dali.svipenyu.cn/Article/details/gtdjsqdrte.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.bjfxy.top/Article/details/gtffdjczmc.html

[Q42] 连接条件附加过滤
来源：http://dali.sxryk.cn/Article/details/gtpulpynhk.html

SELECT u.name, o.amount FROM users u
来源：http://dali.cucudq.cn/Article/details/gtmwvhznym.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhengqikj.top/Article/details/gtmdxcfcgo.html

[Q43] 标量子查询
来源：http://dali.gogol.net.cn/Article/details/gttrjvsjet.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jqgfzy.top/Article/details/gtuekucgaq.html

[Q44] IN 子查询
来源：http://dali.havefunace.top/Article/details/gtxsxbsoyo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.fzhhl.top/Article/details/gtwksegwgz.html

[Q45] EXISTS 判断存在
来源：http://dali.xuetiantiany.cn/Article/details/gttqurczjj.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yongpay.top/Article/details/gtekaidryp.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.jqgufenzy.top/Article/details/gtdrjotcxd.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.hnqzz.top/Article/details/gtoedzdxra.html

[Q47] 与平均值比较
来源：http://dali.sufxvd.cn/Article/details/gtjrbvvnuz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.jianghu66.top/Article/details/gthpomfwxr.html

[Q48] CTE 公用表表达式
来源：http://dali.nanxuanxn.top/Article/details/gtawaegetf.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.daria6918.cn/Article/details/gtvqmzmtqr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.aibaodan.cn/Article/details/gtvtvjzaec.html

[Q49] 更新单行
来源：http://dali.haohaochexian.top/Article/details/gtxjmvvlob.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shzxlz.cn/Article/details/gtycujlnxg.html

[Q50] 批量更新
来源：http://dali.yangfankeji.com/Article/details/gtyrpfpbvi.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ywan-chungtsiang.top/Article/details/gtalawbrmp.html

[Q51] 用子查询更新
来源：http://dali.dashuyun.cn/Article/details/gtmylqbvrk.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zdqjudy.top/Article/details/gtrznbhynh.html

[Q52] 删除指定行
来源：http://dali.cqqwz.cn/Article/details/gtbgbayauz.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yangfankeji.com/Article/details/gtnqtraezm.html

[Q53] 按条件删除
来源：http://dali.jyoumei.cn/Article/details/gtwglfcslz.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.tanke756.top/Article/details/gtyvoavaol.html

[Q54] 清空表
来源：http://dali.ywan-chungtsiang.top/Article/details/gtenjwextf.html

TRUNCATE TABLE logs;
来源：http://dali.zhongyouzk.top/Article/details/gtubosdatg.html

[Q55] 排名（并列占位）
来源：http://dali.jyoumei.cn/Article/details/gtmohjnbvj.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.guowangkeji.top/Article/details/gtsqsilucp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.zhaomingkeji.xyz/Article/details/gtffogaaii.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.yj20258.top/Article/details/gtnicwkewn.html

[Q57] 行号
来源：http://dali.jinyuanbaomall.cn/Article/details/gtvvqodgkm.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.mhx1999.top/Article/details/gttoypvqzp.html

[Q58] 累计求和
来源：http://dali.xinyue.icu/Article/details/gtfitkwfgs.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gthmbexzdw.html

[Q59] 分组内累计
来源：http://dali.mhx1999.top/Article/details/gtaaymsnrm.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtxgjmzuir.html

[Q60] 取上一行 / 下一行
来源：http://dali.9152youxi.cn/Article/details/gtgnscncia.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyfbxfcnp.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gtnbbrpyxh.html

[Q61] 移动平均
来源：http://dali.zhijiandao.cn/Article/details/gtwkkerhmc.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gtsqcksuyi.html

[Q62] 分组占比
来源：http://dali.nwbrower.top/Article/details/gtmdukrwpy.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.haohaochexian.top/Article/details/gtgxjuzvcb.html

[Q63] 开启事务
来源：http://dali.jinqigfzy.top/Article/details/gtleaxmaif.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinqigfzy.top/Article/details/gtihgfvffj.html

[Q64] 提交事务
来源：http://dali.mhx1999.top/Article/details/gtvannjswb.html

COMMIT;
来源：http://dali.sxryk.cn/Article/details/gttigjlhcp.html

[Q65] 回滚事务
来源：http://dali.feifeiyinyue.top/Article/details/gtropwdbmw.html

ROLLBACK;
来源：http://dali.0kj1m.cn/Article/details/gtxeyyqpfg.html

[Q66] 行锁查询
来源：http://dali.fengsongda.top/Article/details/gthksfzisr.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.316326.xyz/Article/details/gtdzweeyxg.html

[Q67] 设置隔离级别
来源：http://dali.c1oappe.top/Article/details/gtcxyqrolv.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.andypj.xyz/Article/details/gtuqypcnxs.html

[Q68] 保存点
来源：http://dali.shanyushiyangtech.top/Article/details/gtoobyeuhe.html

SAVEPOINT sp1;
来源：http://dali.hnxiangtu.top/Article/details/gtqganclii.html

ROLLBACK TO sp1;
来源：http://dali.tanke756.top/Article/details/gtmwtdlwhs.html

[Q69] 查看执行计划
来源：http://dali.ehwqpu.com/Article/details/gtkrlhkiuz.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.tian-w.cn/Article/details/gtuwoihqcb.html

[Q70] 更新统计信息
来源：http://dali.nwbrower.top/Article/details/gthhtrsikv.html

ANALYZE TABLE users;
来源：http://dali.yuanzhike.top/Article/details/gtfhzsjwnn.html

[Q71] 查看建表语句
来源：http://dali.hnxiangtu.top/Article/details/gtiyrzkswu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.zhijiandao.cn/Article/details/gtjvvdewjt.html

[Q72] 查看索引
来源：http://dali.yj20258.top/Article/details/gtpivprrqz.html

SHOW INDEX FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtfrfdedul.html

[Q73] 查看表状态
来源：http://dali.shanyushiyangtech.top/Article/details/gtyacjfmkd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.tian-w.cn/Article/details/gtwhityqww.html

[Q74] 强制使用索引
来源：http://dali.cdnleiting.top/Article/details/gtczcfciwg.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.feifeiyinyue.top/Article/details/gtzeiewksl.html

[Q75] 日期格式化
来源：http://dali.feifeiyinyue.top/Article/details/gtyluwqrkd.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtglgnrtia.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.gaohongyu789.top/Article/details/gtuqikzjsj.html

[Q76] 按天统计
来源：http://dali.guannengcc.top/Article/details/gtzrsvyboy.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xuetiantiany.cn/Article/details/gtyyqkiksp.html

[Q77] 时间加减
来源：http://dali.iojbl.cn/Article/details/gtixngfvfx.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhoulong.xyz/Article/details/gtiwpyfxzs.html

[Q78] 当前时间
来源：http://dali.bjfxy.top/Article/details/gtbznsvwui.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yangfankeji.com/Article/details/gtdancikve.html

[Q79] 字符串拼接
来源：http://dali.zdqjudy.top/Article/details/gtuexvkpgr.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.shangyingyoupin.top/Article/details/gtqlynlznp.html

[Q80] 字符串截取
来源：http://dali.nanxinkj.top/Article/details/gtkajnbqcf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.c1oappe.top/Article/details/gtqfuvvqea.html

[Q81] 字符串替换
来源：http://dali.shangyingyoupin.top/Article/details/gtdfygjjqx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.quarkkingdee.top/Article/details/gtypydvyce.html

[Q82] 字符长度与字节长度
来源：http://dali.ehwqpu.com/Article/details/gthjvfvwfj.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.andypj.xyz/Article/details/gtywkurejo.html

[Q83] 大小写转换
来源：http://dali.xylfe.cn/Article/details/gtiuagiuaj.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtfjaipusl.html

[Q84] 去除首尾空格
来源：http://dali.xziqi.cn/Article/details/gtcgzkgslg.html

SELECT TRIM(name) FROM users;
来源：http://dali.yj20258.top/Article/details/gtjfzqnfxf.html

[Q85] 数值取整
来源：http://dali.jinyuanbaomall.cn/Article/details/gtynbecvjw.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hysaishi.cn/Article/details/gtbjwtdaet.html

[Q86] 读取 JSON 字段
来源：http://dali.sufxvd.cn/Article/details/gtyvsglfnh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.andypj.xyz/Article/details/gtqefrqzjh.html

[Q87] JSON 字段做条件
来源：http://dali.zhongyouzk.top/Article/details/gtcamnfidh.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.kuanghao11.cn/Article/details/gtuasjfqwh.html

[Q88] 行转列（条件聚合）
来源：http://dali.shuidangran.top/Article/details/gtmdmjgzzu.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.quarkkingdee.top/Article/details/gtnijtogck.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yonumen.top/Article/details/gtplgzvyot.html

[Q89] 判断表是否存在
来源：http://dali.yangfankeji.com/Article/details/gtznwzkrqc.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.jinqigufen.top/Article/details/gtnvvqkfej.html

[Q90] 生成序号列
来源：http://dali.xinyue.icu/Article/details/gtozgomlxe.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.andypj.xyz/Article/details/gtjsenijlw.html

================================================================================
来源：http://dali.snrcjt.cn/Article/details/gtfuigmppo.html

R. Bash 专题
来源：http://dali.quarkkingdee.top/Article/details/gtvfuhxhom.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtsutrktdr.html

[R01] shebang 与严格模式
来源：http://dali.ppjwa.cn/Article/details/gtntzcduaz.html

#!/usr/bin/env bash
来源：http://dali.yueranfly.top/Article/details/gtitlxxxjf.html

set -euo pipefail
来源：http://dali.gogol.net.cn/Article/details/gtlfryqpbi.html

[R02] 变量赋值与使用
来源：http://dali.shzxlz.cn/Article/details/gtnurrnsxs.html

name="Tom"; echo "$name"
来源：http://dali.cqqwz.cn/Article/details/gtfnlwkoig.html

[R03] 只读变量
来源：http://dali.hfpthk.cn/Article/details/gtmvwqlcoa.html

readonly PI=3.14
来源：http://dali.ivvv.top/Article/details/gtxjybjduz.html

[R04] 位置参数
来源：http://dali.wangshuangyany.cn/Article/details/gtouszhanp.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.snrcjt.cn/Article/details/gtgwgduvce.html

[R05] 参数默认值
来源：http://dali.yuanzhike.top/Article/details/gtkxtaglkj.html

name="${1:-default}"
来源：http://dali.9152youxi.cn/Article/details/gtqwmluiye.html

[R06] 判断命令是否存在
来源：http://dali.chenjidiqi.icu/Article/details/gtegkmjrbh.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zdqjudy.top/Article/details/gtnaqhwnkf.html

[R07] if 判断文件
来源：http://dali.cashguo.top/Article/details/gtpfebiqxs.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.fengsongda.top/Article/details/gthnkdzclp.html

[R08] 数值比较
来源：http://dali.hysaishi.cn/Article/details/gtvfzmnsem.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tianlin.xyz/Article/details/gtadjtnprr.html

[R09] 字符串比较
来源：http://dali.yj202588.top/Article/details/gttudmjcot.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gtvmtldvjy.html

[R10] 正则匹配
来源：http://dali.gogol.net.cn/Article/details/gtpewzzuer.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.fengsongda.top/Article/details/gtiwlaivpy.html

[R11] case 多分支
来源：http://dali.iojbl.cn/Article/details/gtjuzqslgp.html

case "$1" in
来源：http://dali.smart0.xyz/Article/details/gtknisszbk.html

start) echo "启动" ;;
来源：http://dali.kuanghao11.cn/Article/details/gtojsehixm.html

stop)  echo "停止" ;;
来源：http://dali.jinqigufen.top/Article/details/gtyumvczzm.html

*)     echo "未知命令" ;;
来源：http://dali.cheryme.top/Article/details/gtaxbylsir.html

esac
来源：http://dali.c1oappe.top/Article/details/gtafkvwtnd.html

[R12] for 遍历文件
来源：http://dali.zhoulong.xyz/Article/details/gtayqtihoe.html

for f in *.txt; do echo "$f"; done
来源：http://dali.quarkkingdee.top/Article/details/gtnskdfikk.html

[R13] for 计数循环
来源：http://dali.nwbrower.top/Article/details/gtrpveobdy.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.gzhubu.top/Article/details/gtdqvqrfma.html

[R14] C 风格 for
来源：http://dali.shuidangran.top/Article/details/gtvqmtgqsx.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.gaohongyu789.top/Article/details/gtjosscqkg.html

[R15] while 逐行读文件
来源：http://dali.ydzc1.top/Article/details/gtzturtbpk.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.smart0.xyz/Article/details/gtyaxmmmii.html

[R16] until 等待条件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdekscddh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.c1oappe.top/Article/details/gtburzizfq.html

[R17] 数组定义与取值
来源：http://dali.wangdashe.top/Article/details/gtboacytsu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.xylfe.cn/Article/details/gtqnvrgesj.html

[R18] 遍历数组
来源：http://dali.tanke756.top/Article/details/gtqgdfhjgc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.shzxlz.cn/Article/details/gtphnkhkmy.html

[R19] 数组长度
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjixpwykh.html

echo "${#arr[@]}"
来源：http://dali.ywan-chungtsiang.top/Article/details/gthxvenbvl.html

[R20] 关联数组（字典）
来源：http://dali.yueranfly.top/Article/details/gtqxbngyey.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.cashguo.top/Article/details/gttqzdqvxf.html

[R21] 字符串长度
来源：http://dali.hfpthk.cn/Article/details/gtzggbjdra.html

echo "${#s}"
来源：http://dali.feifeiyinyue.top/Article/details/gtefkunjql.html

[R22] 截取子串
来源：http://dali.xuetiantiany.cn/Article/details/gtatrksxdw.html

echo "${s:0:5}"
来源：http://dali.cashguo.top/Article/details/gtrpyrpbxi.html

[R23] 字符串替换
来源：http://dali.xinyue.icu/Article/details/gtrgqzpgwa.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.gogol.net.cn/Article/details/gtonqmkmlh.html

[R24] 大小写转换
来源：http://dali.yuanzhike.top/Article/details/gtpdvigias.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sxryk.cn/Article/details/gtbyfjrklq.html

[R25] 去后缀 / 去前缀
来源：http://dali.hnqzz.top/Article/details/gtquykmlmz.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzbcieffk.html

[R26] 命令替换
来源：http://dali.0kj1m.cn/Article/details/gtkyuhbtlj.html

now=$(date +%F); echo "$now"
来源：http://dali.dashuyun.cn/Article/details/gtvbimqkif.html

[R27] 算术展开
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjzkenbbn.html

echo $((1 + 2 * 3))
来源：http://dali.ivvv.top/Article/details/gtnqvpftpm.html

[R28] 浮点运算
来源：http://dali.svipenyu.cn/Article/details/gtcgvsmujg.html

echo "scale=2; 10/3" | bc
来源：http://dali.zycfv.cn/Article/details/gtsufqwypx.html

[R29] 定义函数
来源：http://dali.hnqzz.top/Article/details/gtpaocgpty.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jianghu66.top/Article/details/gtwxavtlua.html

[R30] 函数返回状态码
来源：http://dali.yj20258888.top/Article/details/gtmzbgclcy.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.tianlin.xyz/Article/details/gtdiucaald.html

[R31] 局部变量
来源：http://dali.gaohongyu789.top/Article/details/gticxeqjrt.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhoulong.xyz/Article/details/gtrwspcjmm.html

[R32] 参数个数校验
来源：http://dali.chenzaomai.com/Article/details/gtfujyalac.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yongpay.top/Article/details/gtljugrtzc.html

[R33] 捕获错误并提示行号
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgatgxszz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.pengpengdd.cyou/Article/details/gtnklkoejr.html

[R34] 退出时清理
来源：http://dali.zhoulong.xyz/Article/details/gtibosxwmc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenjidiqi.icu/Article/details/gtvlfuiflw.html

[R35] 后台执行并等待
来源：http://dali.dashuyun.cn/Article/details/gttbhlnubt.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hnqzz.top/Article/details/gtmkmgcpze.html

[R36] 并发执行多个任务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpnasvqmy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gzhubu.top/Article/details/gtnumywijt.html

[R37] 把输出赋给变量
来源：http://dali.snrcjt.cn/Article/details/gttmcajzsg.html

files=$(ls -1)
来源：http://dali.0kj1m.cn/Article/details/gtcougthrd.html

[R38] 管道串联
来源：http://dali.bjfxy.top/Article/details/gtuveodebi.html

cat a.txt | grep -i error | wc -l
来源：http://dali.havefunace.top/Article/details/gtyrbzpbgt.html

[R39] 重定向标准输出与错误
来源：http://dali.ehwqpu.com/Article/details/gtqzhlzmpy.html

cmd > out.log 2>&1
来源：http://dali.yj20258.top/Article/details/gtrqwvtvcw.html

[R40] 追加写日志
来源：http://dali.shzxlz.cn/Article/details/gtzsrstaxo.html

echo "log" >> out.log
来源：http://dali.pengpengdd.cyou/Article/details/gtwxehrkom.html

[R41] 丢弃输出
来源：http://dali.zhijiandao.cn/Article/details/gtqxlpbnjd.html

cmd >/dev/null 2>&1
来源：http://dali.kuanghao11.cn/Article/details/gtlpvrrtyu.html

[R42] 输入重定向
来源：http://dali.yvedp.cn/Article/details/gtpxtxjzpc.html

wc -l < a.txt
来源：http://dali.hammf.cn/Article/details/gtxkyakgmh.html

[R43] 按名字查找文件
来源：http://dali.zhiwuduotai.top/Article/details/gtacrspwby.html

find . -name "*.log" -type f
来源：http://dali.quarkkingdee.top/Article/details/gtbsseeawb.html

[R44] 按修改时间查找
来源：http://dali.birdmap.top/Article/details/gtmmdvulwe.html

find . -mtime -7 -type f
来源：http://dali.vqdsnc.cn/Article/details/gtdpdiksip.html

[R45] 批量删除
来源：http://dali.cqqwz.cn/Article/details/gtrwazhwgh.html

find . -name "*.tmp" -delete
来源：http://dali.316326.xyz/Article/details/gtxcfaurwg.html

[R46] 递归替换文件内容
来源：http://dali.gaohongyu789.top/Article/details/gtjetrvetm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xuetiantiany.cn/Article/details/gtkuyegohw.html

[R47] sed 单行替换
来源：http://dali.jqgfzy.top/Article/details/gtfuskxywe.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.cdnleiting.top/Article/details/gtytllwqqz.html

[R48] awk 取指定列
来源：http://dali.aizwys.cn/Article/details/gtyrttxnjh.html

awk '{print $1, $3}' a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpyaccnqj.html

[R49] awk 带条件
来源：http://dali.xuanzx.com/Article/details/gtjaujgtuc.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yj202588.top/Article/details/gtjcrdovdd.html

[R50] awk 求和
来源：http://dali.jinqigfzy.top/Article/details/gtgghzqcxh.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.guowangkeji.top/Article/details/gtcnsjtjsx.html

[R51] 排序去重取前几
来源：http://dali.nwbrower.top/Article/details/gtoxmoydga.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shzxlz.cn/Article/details/gtglmhrwkv.html

[R52] 统计行数
来源：http://dali.wangdashe.top/Article/details/gtmyzppqey.html

wc -l a.txt
来源：http://dali.yvedp.cn/Article/details/gttptqcidg.html

[R53] 查看文件头与实时尾
来源：http://dali.shanyushiyangkeji.top/Article/details/gtimxsckls.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jianghu66.top/Article/details/gttqcovfdk.html

[R54] 比较两个文件
来源：http://dali.jqgfzy.top/Article/details/gtkwtehshd.html

diff a.txt b.txt
来源：http://dali.sweek.top/Article/details/gtqhedtbyv.html

[R55] 压缩与解压
来源：http://dali.dianchejie.cn/Article/details/gtxcuiyhgr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yuxming.cn/Article/details/gtabcwiday.html

[R56] 远程拷贝
来源：http://dali.xuanzx.com/Article/details/gtrqnlvosi.html

scp file user@host:/path/
来源：http://dali.cqqwz.cn/Article/details/gtdhuhffqc.html

[R57] 远程执行命令
来源：http://dali.nanxinkj.top/Article/details/gtehwmlstj.html

ssh user@host 'uptime'
来源：http://dali.gotoacloud.top/Article/details/gtaoabfzbt.html

[R58] 下载文件
来源：http://dali.gaohongyu789.top/Article/details/gtfdvixath.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.aibaodan.cn/Article/details/gttxpgbqru.html

[R59] 发 POST JSON
来源：http://dali.yuxming.cn/Article/details/gtyickfzmb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.andypj.xyz/Article/details/gtnimlpqfe.html

[R60] 只看 HTTP 状态码
来源：http://dali.andypj.xyz/Article/details/gtbljjmwmt.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yuxming.cn/Article/details/gtrcibgtyv.html

[R61] 磁盘占用
来源：http://dali.xuanzx.com/Article/details/gtnntnfifr.html

df -h;  du -sh *
来源：http://dali.gaohongyu789.top/Article/details/gttojqpghr.html

[R62] 找最占空间的文件
来源：http://dali.sweek.top/Article/details/gtvvhwdkjs.html

du -ah . | sort -rh | head -10
来源：http://dali.cucudq.cn/Article/details/gtuqpjhgol.html

[R63] 内存与进程
来源：http://dali.andypj.xyz/Article/details/gtuasclxxi.html

free -h;  ps aux | grep nginx
来源：http://dali.9152youxi.cn/Article/details/gtjqrdyowy.html

[R64] 结束进程
来源：http://dali.fengsongda.top/Article/details/gtoxrmamtp.html

kill -9 $(pgrep -f app.py)
来源：http://dali.meibo888.top/Article/details/gtsqlhwhrc.html

[R65] 查看端口占用
来源：http://dali.ybcxt.top/Article/details/gttkcmppwc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jianghu66.top/Article/details/gtxidvfdvo.html

[R66] 定时任务
来源：http://dali.iojbl.cn/Article/details/gtfmwoithm.html

crontab -e;  crontab -l
来源：http://dali.bjfxy.top/Article/details/gtdatzwsji.html

[R67] 生成随机十六进制串
来源：http://dali.dianchejie.cn/Article/details/gtlurjankv.html

openssl rand -hex 16
来源：http://dali.haohaochexian.top/Article/details/gtggvceuml.html

[R68] 计算文件校验值
来源：http://dali.hysaishi.cn/Article/details/gtsmmcxwda.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.yueranfly.top/Article/details/gtpldqwzpf.html

[R69] 生成随机密码
来源：http://dali.shuidangran.top/Article/details/gtreozcxva.html

head -c 16 /dev/urandom | base64
来源：http://dali.gaohongyu789.top/Article/details/gtxlzkhosz.html

[R70] 时间戳与互转
来源：http://dali.yueranfly.top/Article/details/gtygieuowd.html

date +%s;  date -d @1700000000
来源：http://dali.316326.xyz/Article/details/gtydycojny.html

[R71] 日期格式化
来源：http://dali.nwbrower.top/Article/details/gtkmmdnshx.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinghuilouyu.cn/Article/details/gtuarjjobn.html

[R72] 等待端口就绪
来源：http://dali.dianchejie.cn/Article/details/gtqrikiudq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zhongyouzk.top/Article/details/gtjglghlvv.html

[R73] 分割大日志
来源：http://dali.jinqigfzy.top/Article/details/gtezljgylf.html

split -l 1000 big.log part_
来源：http://dali.ydzc1.top/Article/details/gthsmotyte.html

[R74] 批量重命名
来源：http://dali.chenzaomai.com/Article/details/gttqrtsawu.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.dianchejie.cn/Article/details/gteqfjmqcl.html

[R75] 导出环境变量
来源：http://dali.hysaishi.cn/Article/details/gtwugvybwk.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.pengpengdd.cyou/Article/details/gtzwutggqt.html

[R76] 使用临时文件
来源：http://dali.iojbl.cn/Article/details/gtmmemugkr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.dianchejie.cn/Article/details/gtpfqvvgrq.html

[R77] 读取用户输入
来源：http://dali.jianghu66.top/Article/details/gtsircxfie.html


<!-- 参考信息 -->