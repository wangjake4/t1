代发 wailian999

SELECT * FROM users WHERE age BETWEEN 18 AND 30;
来源：http://dali.aizwys.cn/Article/details/gtdxepcqdk.html

[Q20] IN 列表
来源：http://dali.jqgfzy.top/Article/details/gtdjeieufq.html

SELECT * FROM users WHERE id IN (1, 2, 3);
来源：http://dali.daria6918.cn/Article/details/gtynyqxyoe.html

[Q21] 空值判断
来源：http://dali.xinyue.icu/Article/details/gtnwymefiu.html

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.birdmap.top/Article/details/gtxnmdszob.html

[Q22] 排序
来源：http://dali.hnxiangtu.top/Article/details/gtqogvquli.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.nwbrower.top/Article/details/gtocrwgxgx.html

[Q23] 分页
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwwmjpbox.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxqcbalje.html

[Q24] 去重
来源：http://dali.havefunace.top/Article/details/gtnlcxsvbi.html

SELECT DISTINCT city FROM users;
来源：http://dali.gzhubu.top/Article/details/gtkhpwarwh.html

[Q25] 只取前 N 条
来源：http://dali.fengsongda.top/Article/details/gtblcinamu.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtmqzvusry.html

[Q26] 计数
来源：http://dali.316326.xyz/Article/details/gtabqxpxby.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhongyouzk.top/Article/details/gtbkbpfjlj.html

[Q27] 条件计数
来源：http://dali.chenjidiqi.icu/Article/details/gtyaxakxnv.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.cucudq.cn/Article/details/gtheowojox.html

[Q28] 求和与平均
来源：http://dali.birdmap.top/Article/details/gtswcalrel.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtxbrxyelb.html

[Q29] 最大最小值
来源：http://dali.mhx1999.top/Article/details/gtzudgjnrv.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.xuetiantiany.cn/Article/details/gtpmmeykww.html

[Q30] 分组统计
来源：http://dali.zdqjudy.top/Article/details/gtqjhibtmv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yj20258888.top/Article/details/gtibmfklzm.html

[Q31] 分组后过滤
来源：http://dali.zhongyouzk.top/Article/details/gtepzseqqb.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xuanzx.com/Article/details/gtnvnfxbgf.html

[Q32] 分组拼接字符串
来源：http://dali.yvedp.cn/Article/details/gtxutvljhw.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxampfvgg.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.cqqwz.cn/Article/details/gtdocxnvwu.html

[Q33] 多列分组
来源：http://dali.meibo888.top/Article/details/gtxfqwhhrt.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.svipenyu.cn/Article/details/gtgsbvmsno.html

[Q34] 每组取第一条
来源：http://dali.snrcjt.cn/Article/details/gtmfahztir.html

SELECT * FROM (
来源：http://dali.daxiang520.top/Article/details/gtomqynviw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.nwbrower.top/Article/details/gtrrmkybcq.html

) t WHERE rn = 1;
来源：http://dali.shzxlz.cn/Article/details/gtovfowhkk.html

[Q35] 内连接
来源：http://dali.gzhubu.top/Article/details/gtzurppnrz.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.ydzc1.top/Article/details/gtsencxofk.html

[Q36] 左连接
来源：http://dali.gzhubu.top/Article/details/gtdalmdrkj.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.yuxming.cn/Article/details/gtvucjyvwe.html

[Q37] 右连接
来源：http://dali.jinqigufen.top/Article/details/gtkaovuqsg.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhiwuduotai.top/Article/details/gtzssddike.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yj20258.top/Article/details/gtounavqhh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yj202588.top/Article/details/gtdudnpbos.html

[Q39] 自连接（查上下级）
来源：http://dali.mhx1999.top/Article/details/gtxqiksdbm.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.nanxinkj.top/Article/details/gtqvaqtgny.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhixingplan.top/Article/details/gtknxthcpy.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shuidangran.top/Article/details/gtgmsxslpn.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.tianlin.xyz/Article/details/gtacexkqed.html

[Q41] 多表连接
来源：http://dali.jianghu66.top/Article/details/gtclnpmevi.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.nanxinkj.top/Article/details/gtphqydjfy.html

JOIN users u ON u.id = o.user_id
来源：http://dali.316326.xyz/Article/details/gtrnsnauxh.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.fengsongda.top/Article/details/gtqhppuxms.html

[Q42] 连接条件附加过滤
来源：http://dali.kuanghao11.cn/Article/details/gtgmrhdhrj.html

SELECT u.name, o.amount FROM users u
来源：http://dali.0kj1m.cn/Article/details/gtndkvjhdo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhongyouzk.top/Article/details/gtxiaccaas.html

[Q43] 标量子查询
来源：http://dali.kuanghao11.cn/Article/details/gtqhzewjaj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmedwxrkr.html

[Q44] IN 子查询
来源：http://dali.guowangkeji.top/Article/details/gtlocqkxdq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yj20258888.top/Article/details/gtachmqqlp.html

[Q45] EXISTS 判断存在
来源：http://dali.zhoulong.xyz/Article/details/gttzrelrnk.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yanxiufei.cn/Article/details/gtbshjtwmw.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.guannengcc.top/Article/details/gtxlixmjrx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.mhx1999.top/Article/details/gtywqvorcr.html

[Q47] 与平均值比较
来源：http://dali.cucudq.cn/Article/details/gtbvafjljv.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.dashuyun.cn/Article/details/gtzjdmsjnt.html

[Q48] CTE 公用表表达式
来源：http://dali.xinyue.icu/Article/details/gtgqckeswd.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.chenzaomai.com/Article/details/gthsspbbjl.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.pengpengdd.cyou/Article/details/gtnympbcwk.html

[Q49] 更新单行
来源：http://dali.cqqwz.cn/Article/details/gtwyyvxmtr.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cashguo.top/Article/details/gtdixlmipm.html

[Q50] 批量更新
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtktjxmecn.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.pycfn.com/Article/details/gtokzxzwwk.html

[Q51] 用子查询更新
来源：http://dali.smart0.xyz/Article/details/gtdxyfglbe.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.nwbrower.top/Article/details/gtrwsyoaum.html

[Q52] 删除指定行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtrewmgypc.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yueranfly.top/Article/details/gtbxrqayls.html

[Q53] 按条件删除
来源：http://dali.nanxinkj.top/Article/details/gtdniqlkzh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.kuanghao11.cn/Article/details/gtawfmfins.html

[Q54] 清空表
来源：http://dali.hnqzz.top/Article/details/gtdhiqtila.html

TRUNCATE TABLE logs;
来源：http://dali.jqgufenzy.top/Article/details/gtkxsmgryp.html

[Q55] 排名（并列占位）
来源：http://dali.zycfv.cn/Article/details/gtxtpzucjo.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.xylfe.cn/Article/details/gtshqilsia.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yuanzhike.top/Article/details/gtgjkfibfk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shangyingyoupin.top/Article/details/gtexksnkaq.html

[Q57] 行号
来源：http://dali.sufxvd.cn/Article/details/gtrvbnpizw.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtceeydtmn.html

[Q58] 累计求和
来源：http://dali.sufxvd.cn/Article/details/gttisqhqqb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhoulong.xyz/Article/details/gtmaplskec.html

[Q59] 分组内累计
来源：http://dali.jqgfzy.top/Article/details/gtdnaxkpem.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yj202588.top/Article/details/gtqoxpicfr.html

[Q60] 取上一行 / 下一行
来源：http://dali.tian-w.cn/Article/details/gtxindfxax.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cucudq.cn/Article/details/gtndwkfdoa.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yj202588.top/Article/details/gtwhymbafz.html

[Q61] 移动平均
来源：http://dali.yvedp.cn/Article/details/gtpkuyzphd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gtzgyeiskp.html

[Q62] 分组占比
来源：http://dali.zycfv.cn/Article/details/gtqbhdefql.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yonumen.top/Article/details/gtcohkumnw.html

[Q63] 开启事务
来源：http://dali.tian-w.cn/Article/details/gtwjcnckvp.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.sysykeji.top/Article/details/gtmchspwgg.html

[Q64] 提交事务
来源：http://dali.jiagoushi.top/Article/details/gtmhgnavrj.html

COMMIT;
来源：http://dali.tanke756.top/Article/details/gtpazegdkx.html

[Q65] 回滚事务
来源：http://dali.ehwqpu.com/Article/details/gtxxehbqiq.html

ROLLBACK;
来源：http://dali.snrcjt.cn/Article/details/gtnkszzpjq.html

[Q66] 行锁查询
来源：http://dali.hongshengwenyu.top/Article/details/gtkdvlqkbj.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.xylfe.cn/Article/details/gteqxxpfvd.html

[Q67] 设置隔离级别
来源：http://dali.zhixingplan.top/Article/details/gtijiprxrt.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yj202588.top/Article/details/gtnmqlodch.html

[Q68] 保存点
来源：http://dali.smart0.xyz/Article/details/gtsayjaeak.html

SAVEPOINT sp1;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwikpjmax.html

ROLLBACK TO sp1;
来源：http://dali.zhoulong.xyz/Article/details/gtbfbvxbhd.html

[Q69] 查看执行计划
来源：http://dali.birdmap.top/Article/details/gthofdysdf.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yangfankeji.com/Article/details/gtdyhvmmvp.html

[Q70] 更新统计信息
来源：http://dali.zhengqikj.top/Article/details/gtkriexset.html

ANALYZE TABLE users;
来源：http://dali.dashuyun.cn/Article/details/gtrqltdrmh.html

[Q71] 查看建表语句
来源：http://dali.havefunace.top/Article/details/gtmwaqymcu.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.316326.xyz/Article/details/gtpinzbjad.html

[Q72] 查看索引
来源：http://dali.iojbl.cn/Article/details/gtilyfbtwq.html

SHOW INDEX FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtqqzcwdrg.html

[Q73] 查看表状态
来源：http://dali.wangshuangyany.cn/Article/details/gtqparucjc.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gaohongyu789.top/Article/details/gtpdoivhsb.html

[Q74] 强制使用索引
来源：http://dali.fengsongda.top/Article/details/gtfvmgevor.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.sweek.top/Article/details/gtkjmgwqsy.html

[Q75] 日期格式化
来源：http://dali.cashguo.top/Article/details/gtogtooawa.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtetcixwej.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.tian-w.cn/Article/details/gtxngensrq.html

[Q76] 按天统计
来源：http://dali.xziqi.cn/Article/details/gtiomzmuir.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.chenlongwang.top/Article/details/gtnkppzefx.html

[Q77] 时间加减
来源：http://dali.yvedp.cn/Article/details/gtqdkcnlrq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ivvv.top/Article/details/gtyodzuqma.html

[Q78] 当前时间
来源：http://dali.feifeiyinyue.top/Article/details/gtudurwybv.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xinyue.icu/Article/details/gtypdimrjy.html

[Q79] 字符串拼接
来源：http://dali.cashguo.top/Article/details/gtmmphzcty.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.daria6918.cn/Article/details/gtfiqfrykc.html

[Q80] 字符串截取
来源：http://dali.shzxlz.cn/Article/details/gtxeefmidf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtizjfkfzl.html

[Q81] 字符串替换
来源：http://dali.jianghu66.top/Article/details/gtaphwpxyw.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.pycfn.com/Article/details/gthurnghxi.html

[Q82] 字符长度与字节长度
来源：http://dali.svipenyu.cn/Article/details/gtbhisygrn.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtcnlrfkdy.html

[Q83] 大小写转换
来源：http://dali.dashuyun.cn/Article/details/gthzjyjxok.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtylwflnts.html

[Q84] 去除首尾空格
来源：http://dali.cashguo.top/Article/details/gtgampzosb.html

SELECT TRIM(name) FROM users;
来源：http://dali.yueranfly.top/Article/details/gtxzjieanx.html

[Q85] 数值取整
来源：http://dali.tanke756.top/Article/details/gtodzdfdnq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.gogol.net.cn/Article/details/gtkwzgpxkw.html

[Q86] 读取 JSON 字段
来源：http://dali.ybcxt.top/Article/details/gtdllkthcj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jinqigufen.top/Article/details/gtccwifght.html

[Q87] JSON 字段做条件
来源：http://dali.sysykeji.top/Article/details/gtpipwislj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.gaohongyu789.top/Article/details/gtbkxnvfcg.html

[Q88] 行转列（条件聚合）
来源：http://dali.pengpengdd.cyou/Article/details/gthecnshsp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hnxiangtu.top/Article/details/gtaifoowoy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtxoglceea.html

[Q89] 判断表是否存在
来源：http://dali.316326.xyz/Article/details/gtzohpdwbo.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cdnleiting.top/Article/details/gtuhsegunx.html

[Q90] 生成序号列
来源：http://dali.iojbl.cn/Article/details/gtxyqmlslg.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.meibo888.top/Article/details/gtfgkesrru.html

================================================================================
来源：http://dali.jinqigufen.top/Article/details/gtiuzkzwcl.html

R. Bash 专题
来源：http://dali.yj20258.top/Article/details/gtxzwjyzim.html

================================================================================
来源：http://dali.yvedp.cn/Article/details/gtvmrestnt.html

[R01] shebang 与严格模式
来源：http://dali.hywenlv.cn/Article/details/gtntenjwdd.html

#!/usr/bin/env bash
来源：http://dali.meibo888.top/Article/details/gttpljzxzs.html

set -euo pipefail
来源：http://dali.xinyue.icu/Article/details/gtruxtwqzw.html

[R02] 变量赋值与使用
来源：http://dali.nanxuanxn.top/Article/details/gtxzuoeewd.html

name="Tom"; echo "$name"
来源：http://dali.wangdashe.top/Article/details/gtwhhvjwgl.html

[R03] 只读变量
来源：http://dali.andypj.xyz/Article/details/gthhabgztj.html

readonly PI=3.14
来源：http://dali.nanxuanxn.top/Article/details/gtmtqswbif.html

[R04] 位置参数
来源：http://dali.nanxinkj.top/Article/details/gtangdyvvg.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtrkrjckxc.html

[R05] 参数默认值
来源：http://dali.wangshuangyany.cn/Article/details/gtjxtioocy.html

name="${1:-default}"
来源：http://dali.zhixingplan.top/Article/details/gtnemeemkq.html

[R06] 判断命令是否存在
来源：http://dali.haohaochexian.top/Article/details/gtjotdbety.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.daria6918.cn/Article/details/gtxethfeik.html

[R07] if 判断文件
来源：http://dali.gogol.net.cn/Article/details/gtgzjlaccf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.zdqjudy.top/Article/details/gtpncrvpua.html

[R08] 数值比较
来源：http://dali.yj20258.top/Article/details/gtiowmnnap.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.bjfxy.top/Article/details/gtxxottzae.html

[R09] 字符串比较
来源：http://dali.yvedp.cn/Article/details/gtnqoupjgf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.hongshengwenyu.top/Article/details/gtowfoodmv.html

[R10] 正则匹配
来源：http://dali.aizwys.cn/Article/details/gtgymjwflc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yuxming.cn/Article/details/gtkwnxkfvr.html

[R11] case 多分支
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxxqiiueu.html

case "$1" in
来源：http://dali.shzxlz.cn/Article/details/gtpmtfuymd.html

start) echo "启动" ;;
来源：http://dali.jinghuilouyu.cn/Article/details/gtxqqqhqmz.html

stop)  echo "停止" ;;
来源：http://dali.mhx1999.top/Article/details/gtracvjkjf.html

*)     echo "未知命令" ;;
来源：http://dali.bjfxy.top/Article/details/gtwxmawtfe.html

esac
来源：http://dali.hnxiangtu.top/Article/details/gtjzkqjjzl.html

[R12] for 遍历文件
来源：http://dali.zhongyouzk.top/Article/details/gtxdbrlzzf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.ehwqpu.com/Article/details/gtonczthoq.html

[R13] for 计数循环
来源：http://dali.iojbl.cn/Article/details/gtcuedpeew.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.tian-w.cn/Article/details/gtaentjoju.html

[R14] C 风格 for
来源：http://dali.zhongyouzk.top/Article/details/gtcbxwkqor.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.jiagoushi.top/Article/details/gtdefnhspf.html

[R15] while 逐行读文件
来源：http://dali.jinqigufen.top/Article/details/gtrjtdarvc.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xylfe.cn/Article/details/gtjcmalbvr.html

[R16] until 等待条件
来源：http://dali.sufxvd.cn/Article/details/gtcxpzfxlc.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cashguo.top/Article/details/gtwxhyxorz.html

[R17] 数组定义与取值
来源：http://dali.zhijiandao.cn/Article/details/gtstfuiabb.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinghuilouyu.cn/Article/details/gthiarcpqs.html

[R18] 遍历数组
来源：http://dali.yj202588.top/Article/details/gttchgsyje.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gzhubu.top/Article/details/gtfauzmpsf.html

[R19] 数组长度
来源：http://dali.jyoumei.cn/Article/details/gtfajkammt.html

echo "${#arr[@]}"
来源：http://dali.yangfankeji.com/Article/details/gtixkgmxrb.html

[R20] 关联数组（字典）
来源：http://dali.hfpthk.cn/Article/details/gttbqrrlrl.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.gaohongyu789.top/Article/details/gtmdtmxwyk.html

[R21] 字符串长度
来源：http://dali.hongshengwenyu.top/Article/details/gtshzkvnmw.html

echo "${#s}"
来源：http://dali.zhengqikj.top/Article/details/gtzjhewqhl.html

[R22] 截取子串
来源：http://dali.yongpay.top/Article/details/gtkmsjihwe.html

echo "${s:0:5}"
来源：http://dali.zhiwuduotai.top/Article/details/gtwqkfoyvz.html

[R23] 字符串替换
来源：http://dali.yj20258.top/Article/details/gtwczvqmfk.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtvyzarnjr.html

[R24] 大小写转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzpeavnlx.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtjwzakkil.html

[R25] 去后缀 / 去前缀
来源：http://dali.yuanzhike.top/Article/details/gthtcqgsak.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.ydzc1.top/Article/details/gtfjhvkegq.html

[R26] 命令替换
来源：http://dali.daxiang520.top/Article/details/gtghfvvawd.html

now=$(date +%F); echo "$now"
来源：http://dali.xuanzx.com/Article/details/gtwkjtcfba.html

[R27] 算术展开
来源：http://dali.andypj.xyz/Article/details/gtoifgqxlu.html

echo $((1 + 2 * 3))
来源：http://dali.zhixingplan.top/Article/details/gtvstnawah.html

[R28] 浮点运算
来源：http://dali.sweek.top/Article/details/gtyjrouwyx.html

echo "scale=2; 10/3" | bc
来源：http://dali.aizwys.cn/Article/details/gtqjkibzjx.html

[R29] 定义函数
来源：http://dali.haohaochexian.top/Article/details/gtyysyrtmw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcnvedbnc.html

[R30] 函数返回状态码
来源：http://dali.wangdashe.top/Article/details/gtmqamkcof.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.gzhubu.top/Article/details/gtigmptmyo.html

[R31] 局部变量
来源：http://dali.xylfe.cn/Article/details/gtaruitsuq.html

f() { local x=1; echo "$x"; }
来源：http://dali.shangyingyoupin.top/Article/details/gtcdkuqyhv.html

[R32] 参数个数校验
来源：http://dali.jqgufenzy.top/Article/details/gtiqfwfnzh.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.gzhubu.top/Article/details/gtsjesyofp.html

[R33] 捕获错误并提示行号
来源：http://dali.yj20258.top/Article/details/gtnwfuxaya.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jlsjyb.cn/Article/details/gtudbgueez.html

[R34] 退出时清理
来源：http://dali.sweek.top/Article/details/gtwdohjprf.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.fzhhl.top/Article/details/gtcllnrsym.html

[R35] 后台执行并等待
来源：http://dali.tian-w.cn/Article/details/gttzsofxqy.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.wangdashe.top/Article/details/gttvxywgkh.html

[R36] 并发执行多个任务
来源：http://dali.zdqjudy.top/Article/details/gtieuiqwwx.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yuxming.cn/Article/details/gtzxzruhrv.html

[R37] 把输出赋给变量
来源：http://dali.hysaishi.cn/Article/details/gtgdtnzipk.html

files=$(ls -1)
来源：http://dali.dianchejie.cn/Article/details/gtxrbztbjk.html

[R38] 管道串联
来源：http://dali.ywan-chungtsiang.top/Article/details/gttszmsylx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.0kj1m.cn/Article/details/gtczbxeweb.html

[R39] 重定向标准输出与错误
来源：http://dali.0kj1m.cn/Article/details/gtpbaolhnp.html

cmd > out.log 2>&1
来源：http://dali.yvedp.cn/Article/details/gtupqpcbst.html

[R40] 追加写日志
来源：http://dali.bjfxy.top/Article/details/gtsaafnrgo.html

echo "log" >> out.log
来源：http://dali.daria6918.cn/Article/details/gtectuaabp.html

[R41] 丢弃输出
来源：http://dali.yvedp.cn/Article/details/gtuiknypvx.html

cmd >/dev/null 2>&1
来源：http://dali.gotoacloud.top/Article/details/gtgymxdcso.html

[R42] 输入重定向
来源：http://dali.xziqi.cn/Article/details/gttodargti.html

wc -l < a.txt
来源：http://dali.dashuyun.cn/Article/details/gtvgownjfc.html

[R43] 按名字查找文件
来源：http://dali.0kj1m.cn/Article/details/gtbtklmbwx.html

find . -name "*.log" -type f
来源：http://dali.aizwys.cn/Article/details/gtxtqcvleq.html

[R44] 按修改时间查找
来源：http://dali.shzxlz.cn/Article/details/gtxhtqffhn.html

find . -mtime -7 -type f
来源：http://dali.snrcjt.cn/Article/details/gtqvxjeyki.html

[R45] 批量删除
来源：http://dali.zhongyouzk.top/Article/details/gttwocbeqp.html

find . -name "*.tmp" -delete
来源：http://dali.jiagoushi.top/Article/details/gtochhknrw.html

[R46] 递归替换文件内容
来源：http://dali.gotoacloud.top/Article/details/gtfopsfctn.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.jinqigufen.top/Article/details/gtjijalmjr.html

[R47] sed 单行替换
来源：http://dali.ivvv.top/Article/details/gtfoikygvi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.fengsongda.top/Article/details/gtfsylqvzo.html

[R48] awk 取指定列
来源：http://dali.kuanghao11.cn/Article/details/gtxnosyhll.html

awk '{print $1, $3}' a.txt
来源：http://dali.ybcxt.top/Article/details/gtybpwvbot.html

[R49] awk 带条件
来源：http://dali.zycfv.cn/Article/details/gtwrdeiwqv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.smart0.xyz/Article/details/gtwiytvarh.html

[R50] awk 求和
来源：http://dali.cashguo.top/Article/details/gtmktdakuj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yuxming.cn/Article/details/gtbptigkiy.html

[R51] 排序去重取前几
来源：http://dali.iojbl.cn/Article/details/gtafhbksig.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.fengsongda.top/Article/details/gtanvbevhr.html

[R52] 统计行数
来源：http://dali.nwbrower.top/Article/details/gteifadjiw.html

wc -l a.txt
来源：http://dali.shanyushiyangtech.top/Article/details/gtykckswgf.html

[R53] 查看文件头与实时尾
来源：http://dali.hnqzz.top/Article/details/gtjdbbzkbo.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tanke756.top/Article/details/gtrxvbxscf.html

[R54] 比较两个文件
来源：http://dali.meibo888.top/Article/details/gtzqeheape.html

diff a.txt b.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmswkcsyc.html

[R55] 压缩与解压
来源：http://dali.hysaishi.cn/Article/details/gtapgaemae.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ppjwa.cn/Article/details/gttoqwnpxb.html

[R56] 远程拷贝
来源：http://dali.jqgfzy.top/Article/details/gtstyelefy.html

scp file user@host:/path/
来源：http://dali.jianghu66.top/Article/details/gtyfjchnow.html

[R57] 远程执行命令
来源：http://dali.nanxinkj.top/Article/details/gtlixoduyy.html

ssh user@host 'uptime'
来源：http://dali.daxiang520.top/Article/details/gtabwjqpqo.html

[R58] 下载文件
来源：http://dali.cdnleiting.top/Article/details/gtrwuzdtwk.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.svipenyu.cn/Article/details/gtlcgmdlft.html

[R59] 发 POST JSON
来源：http://dali.gotoacloud.top/Article/details/gtgbzbdkmd.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.shzxlz.cn/Article/details/gtgsbqveha.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhiwuduotai.top/Article/details/gtioyuwojp.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ppjwa.cn/Article/details/gtnxxiwhrs.html

[R61] 磁盘占用
来源：http://dali.jyoumei.cn/Article/details/gtwzfvwopn.html

df -h;  du -sh *
来源：http://dali.guowangkeji.top/Article/details/gtofxguyjk.html

[R62] 找最占空间的文件
来源：http://dali.ppjwa.cn/Article/details/gtmqlrawgm.html

du -ah . | sort -rh | head -10
来源：http://dali.hysaishi.cn/Article/details/gtlommdnug.html

[R63] 内存与进程
来源：http://dali.jiagoushi.top/Article/details/gtgezitoeu.html

free -h;  ps aux | grep nginx
来源：http://dali.gzhubu.top/Article/details/gtvrscgcxo.html

[R64] 结束进程
来源：http://dali.jyoumei.cn/Article/details/gtwpoaqwrj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.zhaomingkeji.xyz/Article/details/gtihjkbeqm.html

[R65] 查看端口占用
来源：http://dali.yvedp.cn/Article/details/gtgoflvglb.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.ivvv.top/Article/details/gtfygfbdak.html

[R66] 定时任务
来源：http://dali.aizwys.cn/Article/details/gtnyzcnxlw.html

crontab -e;  crontab -l
来源：http://dali.feifeiyinyue.top/Article/details/gtvermpoja.html

[R67] 生成随机十六进制串
来源：http://dali.cheryme.top/Article/details/gtfrfvryee.html

openssl rand -hex 16
来源：http://dali.yj20258888.top/Article/details/gtyvtavttj.html

[R68] 计算文件校验值
来源：http://dali.gogol.net.cn/Article/details/gttfyunlli.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.ydzc1.top/Article/details/gtmgghrpxs.html

[R69] 生成随机密码
来源：http://dali.yvedp.cn/Article/details/gtzuaujdho.html


<!-- 参考信息 -->