代发 wailian999

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.sysykeji.top/Article/details/gtybscocnn.html

[Q24] 去重
来源：http://dali.hywenlv.cn/Article/details/gtkyuntgzy.html

SELECT DISTINCT city FROM users;
来源：http://dali.nanxuanxn.top/Article/details/gtheztsjds.html

[Q25] 只取前 N 条
来源：http://dali.cheryme.top/Article/details/gtrpasvrdr.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.chenjidiqi.icu/Article/details/gtmaloeamj.html

[Q26] 计数
来源：http://dali.yj20258.top/Article/details/gtuwoxvxqb.html

SELECT COUNT(*) FROM users;
来源：http://dali.cdnleiting.top/Article/details/gthlouocpx.html

[Q27] 条件计数
来源：http://dali.jiagoushi.top/Article/details/gtiyoiyyaz.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtxxprttzp.html

[Q28] 求和与平均
来源：http://dali.xuetiantiany.cn/Article/details/gttorngdsr.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.mhx1999.top/Article/details/gtapntvxll.html

[Q29] 最大最小值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmfflcbsw.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.tanke756.top/Article/details/gtmtrbwvvz.html

[Q30] 分组统计
来源：http://dali.hysaishi.cn/Article/details/gtypiwddxk.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yj20258.top/Article/details/gtcolcdpun.html

[Q31] 分组后过滤
来源：http://dali.yanxiufei.cn/Article/details/gtsijpvbuc.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.c1oappe.top/Article/details/gtkrusumyc.html

[Q32] 分组拼接字符串
来源：http://dali.ydzc1.top/Article/details/gtvdaqdmsl.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.nwbrower.top/Article/details/gtzijzrvbj.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zdqjudy.top/Article/details/gtxeimfsvx.html

[Q33] 多列分组
来源：http://dali.yongpay.top/Article/details/gtjxtzptqk.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.zhoulong.xyz/Article/details/gtcvubvmaq.html

[Q34] 每组取第一条
来源：http://dali.cucudq.cn/Article/details/gtfplavrhx.html

SELECT * FROM (
来源：http://dali.xylfe.cn/Article/details/gtutaiqwgf.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.shanyushiyangkeji.top/Article/details/gtthnpanmw.html

) t WHERE rn = 1;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtgwolhjlo.html

[Q35] 内连接
来源：http://dali.aibaodan.cn/Article/details/gtieszghml.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.316326.xyz/Article/details/gtlanxdrsm.html

[Q36] 左连接
来源：http://dali.svipenyu.cn/Article/details/gtgmnoqshd.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhixingplan.top/Article/details/gtzfcslqlp.html

[Q37] 右连接
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtxpbryjgt.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.hnxiangtu.top/Article/details/gtkritorpc.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.quarkkingdee.top/Article/details/gtkvklymko.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.chenzaomai.com/Article/details/gtnvkrjvaf.html

[Q39] 自连接（查上下级）
来源：http://dali.xinyue.icu/Article/details/gtfswpzhaw.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jiagoushi.top/Article/details/gthzfvjmkk.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.guowangkeji.top/Article/details/gtaceyaidu.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.zhiwuduotai.top/Article/details/gtvqmkkunt.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.0kj1m.cn/Article/details/gtomjterse.html

[Q41] 多表连接
来源：http://dali.nwbrower.top/Article/details/gtoyxkkgku.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.jiagoushi.top/Article/details/gtzubatdto.html

JOIN users u ON u.id = o.user_id
来源：http://dali.vqdsnc.cn/Article/details/gtmvqjcdpt.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.chenlongwang.top/Article/details/gtofdphlge.html

[Q42] 连接条件附加过滤
来源：http://dali.kuanghao11.cn/Article/details/gtmqgpevmm.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xuanzx.com/Article/details/gtezwetxev.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.shzxlz.cn/Article/details/gtlrzovnin.html

[Q43] 标量子查询
来源：http://dali.ehwqpu.com/Article/details/gtgpaqenda.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cqqwz.cn/Article/details/gtmxgywugg.html

[Q44] IN 子查询
来源：http://dali.yuanzhike.top/Article/details/gtonzmmvmp.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.xuetiantiany.cn/Article/details/gtfnayzqrb.html

[Q45] EXISTS 判断存在
来源：http://dali.zhengqikj.top/Article/details/gtauiwdmwq.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.pycfn.com/Article/details/gtwejkrpxn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xylfe.cn/Article/details/gtluudmwqy.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.quarkkingdee.top/Article/details/gtavlbgtsn.html

[Q47] 与平均值比较
来源：http://dali.smart0.xyz/Article/details/gtpfwpqsnl.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shzxlz.cn/Article/details/gtpiwepnuq.html

[Q48] CTE 公用表表达式
来源：http://dali.ybcxt.top/Article/details/gtqqbjyood.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.sufxvd.cn/Article/details/gtpbkcphpr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpesjbviu.html

[Q49] 更新单行
来源：http://dali.wangdashe.top/Article/details/gtemxmpral.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.yj20258888.top/Article/details/gturifimay.html

[Q50] 批量更新
来源：http://dali.jianghu66.top/Article/details/gtbxbpjxnm.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.ehwqpu.com/Article/details/gtnolpmmhw.html

[Q51] 用子查询更新
来源：http://dali.vqdsnc.cn/Article/details/gtcesixety.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.chenzaomai.com/Article/details/gtgwexwqoo.html

[Q52] 删除指定行
来源：http://dali.yongpay.top/Article/details/gtbbmjqufg.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yuanzhike.top/Article/details/gtjwguospg.html

[Q53] 按条件删除
来源：http://dali.chenlongwang.top/Article/details/gtclypfqlq.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.gotoacloud.top/Article/details/gtkzrqrfof.html

[Q54] 清空表
来源：http://dali.jianghu66.top/Article/details/gtddbsgqig.html

TRUNCATE TABLE logs;
来源：http://dali.jyoumei.cn/Article/details/gtbosedoqp.html

[Q55] 排名（并列占位）
来源：http://dali.yanxiufei.cn/Article/details/gtbfjkeyon.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.9152youxi.cn/Article/details/gtjejzsolq.html

[Q56] 密集排名（并列不占位）
来源：http://dali.shzxlz.cn/Article/details/gtcuoblnnk.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtxhyeozmx.html

[Q57] 行号
来源：http://dali.hnxiangtu.top/Article/details/gtpvcbnsic.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yongpay.top/Article/details/gtoybntznz.html

[Q58] 累计求和
来源：http://dali.xuanzx.com/Article/details/gtznavophl.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gtzvgdlgnb.html

[Q59] 分组内累计
来源：http://dali.smart0.xyz/Article/details/gtragimkpy.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gtwxssuwmz.html

[Q60] 取上一行 / 下一行
来源：http://dali.daxiang520.top/Article/details/gtcwpehfbp.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.fengsongda.top/Article/details/gtjclyawoh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.meibo888.top/Article/details/gtswrmogbo.html

[Q61] 移动平均
来源：http://dali.ivvv.top/Article/details/gtkskvnmua.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.kuanghao11.cn/Article/details/gtyxhjtklg.html

[Q62] 分组占比
来源：http://dali.jinqigfzy.top/Article/details/gtpoaamqhj.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.snrcjt.cn/Article/details/gtaxjxrrvr.html

[Q63] 开启事务
来源：http://dali.hysaishi.cn/Article/details/gthzmbpvad.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jlsjyb.cn/Article/details/gtwmfnwcxg.html

[Q64] 提交事务
来源：http://dali.hfpthk.cn/Article/details/gtrvobrnkj.html

COMMIT;
来源：http://dali.xuanzx.com/Article/details/gtduvcprih.html

[Q65] 回滚事务
来源：http://dali.hammf.cn/Article/details/gtuqkrtglg.html

ROLLBACK;
来源：http://dali.bjfxy.top/Article/details/gtfqifnsar.html

[Q66] 行锁查询
来源：http://dali.aibaodan.cn/Article/details/gtqyiwedvb.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.c1oappe.top/Article/details/gtavgibvbj.html

[Q67] 设置隔离级别
来源：http://dali.jyoumei.cn/Article/details/gtzmnotcyc.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.daria6918.cn/Article/details/gtweyywzce.html

[Q68] 保存点
来源：http://dali.jqgfzy.top/Article/details/gtuyhiusaz.html

SAVEPOINT sp1;
来源：http://dali.yj20258.top/Article/details/gtdupoecae.html

ROLLBACK TO sp1;
来源：http://dali.shuidangran.top/Article/details/gtsafltmlh.html

[Q69] 查看执行计划
来源：http://dali.yueranfly.top/Article/details/gtgewjnilp.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shangyingyoupin.top/Article/details/gtaqfkxykl.html

[Q70] 更新统计信息
来源：http://dali.pengpengdd.cyou/Article/details/gtnvsobjcz.html

ANALYZE TABLE users;
来源：http://dali.guannengcc.top/Article/details/gtncjvshde.html

[Q71] 查看建表语句
来源：http://dali.vqdsnc.cn/Article/details/gtpwjikouo.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cucudq.cn/Article/details/gtmqpcjzfp.html

[Q72] 查看索引
来源：http://dali.jinghuilouyu.cn/Article/details/gtiwvekkay.html

SHOW INDEX FROM users;
来源：http://dali.cashguo.top/Article/details/gtdednsnkq.html

[Q73] 查看表状态
来源：http://dali.havefunace.top/Article/details/gtybwabfxx.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.hammf.cn/Article/details/gtsclxqqfi.html

[Q74] 强制使用索引
来源：http://dali.yonumen.top/Article/details/gtlhxcgdcc.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ybcxt.top/Article/details/gtrwofustl.html

[Q75] 日期格式化
来源：http://dali.zhengqikj.top/Article/details/gtogrvoiux.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yj202588.top/Article/details/gtdipuarsi.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.havefunace.top/Article/details/gtekwmvouc.html

[Q76] 按天统计
来源：http://dali.yj20258888.top/Article/details/gtfllclpjw.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.jinqigfzy.top/Article/details/gttvfmaegs.html

[Q77] 时间加减
来源：http://dali.havefunace.top/Article/details/gtttueojrj.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtkldlxoby.html

[Q78] 当前时间
来源：http://dali.shuidangran.top/Article/details/gtwncuqaiq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.gogol.net.cn/Article/details/gtbgexwlpm.html

[Q79] 字符串拼接
来源：http://dali.hfpthk.cn/Article/details/gtxkdgvvpu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jqgfzy.top/Article/details/gtbwixbaxf.html

[Q80] 字符串截取
来源：http://dali.daxiang520.top/Article/details/gtxmcsbuso.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtilmajyie.html

[Q81] 字符串替换
来源：http://dali.xinyue.icu/Article/details/gtkqwnxyqb.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yanxiufei.cn/Article/details/gtpqqjyldc.html

[Q82] 字符长度与字节长度
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaqekgjoc.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.gotoacloud.top/Article/details/gtevltnifm.html

[Q83] 大小写转换
来源：http://dali.shuidangran.top/Article/details/gtnrjncczm.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.wangshuangyany.cn/Article/details/gtqomwjwij.html

[Q84] 去除首尾空格
来源：http://dali.yj20258.top/Article/details/gtlslzpyjd.html

SELECT TRIM(name) FROM users;
来源：http://dali.pycfn.com/Article/details/gtdnuaorxi.html

[Q85] 数值取整
来源：http://dali.sxryk.cn/Article/details/gtakgmefmr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.hongshengwenyu.top/Article/details/gtjvwmzlbj.html

[Q86] 读取 JSON 字段
来源：http://dali.jinqigufen.top/Article/details/gttmwpfwxw.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.nanxinkj.top/Article/details/gtbqqihktb.html

[Q87] JSON 字段做条件
来源：http://dali.tanke756.top/Article/details/gtqygcqyld.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtetvtmlof.html

[Q88] 行转列（条件聚合）
来源：http://dali.xuanzx.com/Article/details/gtlrqotacl.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.9152youxi.cn/Article/details/gtowgyjklb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtdxttyjsv.html

[Q89] 判断表是否存在
来源：http://dali.xuanzx.com/Article/details/gtnpxzgeza.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sufxvd.cn/Article/details/gtfgebdfwn.html

[Q90] 生成序号列
来源：http://dali.aibaodan.cn/Article/details/gtznfbywny.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.nwbrower.top/Article/details/gtnckorirv.html

================================================================================
来源：http://dali.xuanzx.com/Article/details/gtiwesfjic.html

R. Bash 专题
来源：http://dali.yj20258.top/Article/details/gtsnctsqim.html

================================================================================
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvxdccdco.html

[R01] shebang 与严格模式
来源：http://dali.yueranfly.top/Article/details/gtezyjafaj.html

#!/usr/bin/env bash
来源：http://dali.xuetiantiany.cn/Article/details/gtrzrnmhvl.html

set -euo pipefail
来源：http://dali.hnqzz.top/Article/details/gthyodlunt.html

[R02] 变量赋值与使用
来源：http://dali.shzxlz.cn/Article/details/gtcfuqwbdz.html

name="Tom"; echo "$name"
来源：http://dali.shzxlz.cn/Article/details/gtvcfhkpfn.html

[R03] 只读变量
来源：http://dali.svipenyu.cn/Article/details/gtkgweuqjw.html

readonly PI=3.14
来源：http://dali.gaohongyu789.top/Article/details/gtxvkafjfy.html

[R04] 位置参数
来源：http://dali.xinyue.icu/Article/details/gtffpufgxf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hnxiangtu.top/Article/details/gtkftipfnh.html

[R05] 参数默认值
来源：http://dali.yanxiufei.cn/Article/details/gthlxlqvwu.html

name="${1:-default}"
来源：http://dali.jinqigufen.top/Article/details/gtezcvnlsx.html

[R06] 判断命令是否存在
来源：http://dali.sufxvd.cn/Article/details/gtwsnhdtld.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zdqjudy.top/Article/details/gtvqkyowdu.html

[R07] if 判断文件
来源：http://dali.sysykeji.top/Article/details/gtdcqhvptl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yuxming.cn/Article/details/gtkqvjffrt.html

[R08] 数值比较
来源：http://dali.redwolf501.top/Article/details/gtcwpwnhuc.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.jianghu66.top/Article/details/gtreygoprk.html

[R09] 字符串比较
来源：http://dali.kuanghao11.cn/Article/details/gtnkqfjbug.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.smart0.xyz/Article/details/gtclmrqdnr.html

[R10] 正则匹配
来源：http://dali.sufxvd.cn/Article/details/gtgjonaxex.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.sufxvd.cn/Article/details/gtmeqrqqba.html

[R11] case 多分支
来源：http://dali.yuanzhike.top/Article/details/gtgcwcmgkp.html

case "$1" in
来源：http://dali.zhengqikj.top/Article/details/gtsxsoqkvv.html

start) echo "启动" ;;
来源：http://dali.vqdsnc.cn/Article/details/gtyqksaurd.html

stop)  echo "停止" ;;
来源：http://dali.tanke756.top/Article/details/gtwceyjkwr.html

*)     echo "未知命令" ;;
来源：http://dali.nwbrower.top/Article/details/gtdmzzefwi.html

esac
来源：http://dali.aibaodan.cn/Article/details/gtkdsuhofm.html

[R12] for 遍历文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkrluvbkp.html

for f in *.txt; do echo "$f"; done
来源：http://dali.gogol.net.cn/Article/details/gtdqruqkgh.html

[R13] for 计数循环
来源：http://dali.c1oappe.top/Article/details/gtrxtgdrun.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.yj202588.top/Article/details/gtzalsbnfk.html

[R14] C 风格 for
来源：http://dali.yuanzhike.top/Article/details/gttqribjio.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sxryk.cn/Article/details/gtgqpupbbp.html

[R15] while 逐行读文件
来源：http://dali.yuxming.cn/Article/details/gtoqdumukg.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.cashguo.top/Article/details/gteegpdreq.html

[R16] until 等待条件
来源：http://dali.cheryme.top/Article/details/gtjexsoujr.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.cashguo.top/Article/details/gtkfxygsqi.html

[R17] 数组定义与取值
来源：http://dali.cashguo.top/Article/details/gtlzestppx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jinghuilouyu.cn/Article/details/gtsvqzrqdb.html

[R18] 遍历数组
来源：http://dali.jiagoushi.top/Article/details/gtozgmpjhm.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.jianghu66.top/Article/details/gtyctlecze.html

[R19] 数组长度
来源：http://dali.birdmap.top/Article/details/gtcafiniro.html

echo "${#arr[@]}"
来源：http://dali.yuxming.cn/Article/details/gtfncpovnr.html

[R20] 关联数组（字典）
来源：http://dali.jqgfzy.top/Article/details/gtpnvztcey.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhongyouzk.top/Article/details/gtkaeoehia.html

[R21] 字符串长度
来源：http://dali.tianlin.xyz/Article/details/gtolykhdls.html

echo "${#s}"
来源：http://dali.hywenlv.cn/Article/details/gtqqqwdeqp.html

[R22] 截取子串
来源：http://dali.guannengcc.top/Article/details/gtpklgzcbj.html

echo "${s:0:5}"
来源：http://dali.yvedp.cn/Article/details/gttrajzbre.html

[R23] 字符串替换
来源：http://dali.nanxuanxn.top/Article/details/gtctxdwnzp.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.guannengcc.top/Article/details/gtepbjsrmx.html

[R24] 大小写转换
来源：http://dali.cdnleiting.top/Article/details/gtmmndxjbu.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.fzhhl.top/Article/details/gtxqegfqld.html

[R25] 去后缀 / 去前缀
来源：http://dali.gotoacloud.top/Article/details/gtuvrrskew.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.nwbrower.top/Article/details/gtausgwued.html

[R26] 命令替换
来源：http://dali.sweek.top/Article/details/gtjemnukqa.html

now=$(date +%F); echo "$now"
来源：http://dali.wangdashe.top/Article/details/gtuagxizub.html

[R27] 算术展开
来源：http://dali.yueranfly.top/Article/details/gtsesizlsa.html

echo $((1 + 2 * 3))
来源：http://dali.yangfankeji.com/Article/details/gttmjpzald.html

[R28] 浮点运算
来源：http://dali.aizwys.cn/Article/details/gtdjryyaco.html

echo "scale=2; 10/3" | bc
来源：http://dali.hnxiangtu.top/Article/details/gtiltysnon.html

[R29] 定义函数
来源：http://dali.zhoulong.xyz/Article/details/gtmfcedvfw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.kuanghao11.cn/Article/details/gtsimwvecc.html

[R30] 函数返回状态码
来源：http://dali.hfpthk.cn/Article/details/gtldfewnww.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.zhoulong.xyz/Article/details/gtmszhskbd.html

[R31] 局部变量
来源：http://dali.xinyue.icu/Article/details/gtmxzpfbyc.html

f() { local x=1; echo "$x"; }
来源：http://dali.birdmap.top/Article/details/gtwxukauim.html

[R32] 参数个数校验
来源：http://dali.pengpengdd.cyou/Article/details/gtkzwnisnm.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.redwolf501.top/Article/details/gtwzccvmtp.html

[R33] 捕获错误并提示行号
来源：http://dali.smart0.xyz/Article/details/gtsezleczn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yj20258.top/Article/details/gtazdthgzu.html

[R34] 退出时清理
来源：http://dali.cucudq.cn/Article/details/gttmipnbjp.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.chenlongwang.top/Article/details/gtwnkemrtq.html

[R35] 后台执行并等待
来源：http://dali.316326.xyz/Article/details/gtqwkbogwf.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.zhengqikj.top/Article/details/gtdrbcejbp.html

[R36] 并发执行多个任务
来源：http://dali.hysaishi.cn/Article/details/gtejkatsfs.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shzxlz.cn/Article/details/gtvskgyzle.html

[R37] 把输出赋给变量
来源：http://dali.guannengcc.top/Article/details/gtzoezzqyi.html

files=$(ls -1)
来源：http://dali.yj20258.top/Article/details/gtxybmqjnv.html

[R38] 管道串联
来源：http://dali.smart0.xyz/Article/details/gtvvumueae.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jqgfzy.top/Article/details/gtgfmsjvcw.html

[R39] 重定向标准输出与错误
来源：http://dali.gotoacloud.top/Article/details/gtguffvajf.html

cmd > out.log 2>&1
来源：http://dali.yj20258.top/Article/details/gttacczxwc.html

[R40] 追加写日志
来源：http://dali.shangyingyoupin.top/Article/details/gtwvccwpln.html

echo "log" >> out.log
来源：http://dali.sweek.top/Article/details/gtuunoazhp.html

[R41] 丢弃输出
来源：http://dali.mhx1999.top/Article/details/gtopfnvyxg.html

cmd >/dev/null 2>&1
来源：http://dali.hongshengwenyu.top/Article/details/gthtdqdpty.html

[R42] 输入重定向
来源：http://dali.iojbl.cn/Article/details/gtkiripauy.html

wc -l < a.txt
来源：http://dali.shzxlz.cn/Article/details/gtiamzkdps.html

[R43] 按名字查找文件
来源：http://dali.tanke756.top/Article/details/gtacclynev.html

find . -name "*.log" -type f
来源：http://dali.jyoumei.cn/Article/details/gtlsfbmpop.html

[R44] 按修改时间查找
来源：http://dali.yongpay.top/Article/details/gttwecewep.html

find . -mtime -7 -type f
来源：http://dali.tian-w.cn/Article/details/gtdtqgcwxh.html

[R45] 批量删除
来源：http://dali.hysaishi.cn/Article/details/gtmeripnjf.html

find . -name "*.tmp" -delete
来源：http://dali.shangyingyoupin.top/Article/details/gtwejtdxcn.html

[R46] 递归替换文件内容
来源：http://dali.sufxvd.cn/Article/details/gtzunoqjyi.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.xylfe.cn/Article/details/gtgnbbplhr.html

[R47] sed 单行替换
来源：http://dali.ppjwa.cn/Article/details/gttyvldiei.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhixingplan.top/Article/details/gtwlfqjuqu.html

[R48] awk 取指定列
来源：http://dali.cucudq.cn/Article/details/gtelljxsjt.html

awk '{print $1, $3}' a.txt
来源：http://dali.zhixingplan.top/Article/details/gtvzuvmfas.html

[R49] awk 带条件
来源：http://dali.xylfe.cn/Article/details/gtmphlhksa.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.aizwys.cn/Article/details/gtobiodcxx.html

[R50] awk 求和
来源：http://dali.hfpthk.cn/Article/details/gtxdvjcopr.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.ehwqpu.com/Article/details/gtvzaymzmk.html

[R51] 排序去重取前几
来源：http://dali.jlsjyb.cn/Article/details/gtwjuehdag.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jqgfzy.top/Article/details/gtkhzjywny.html

[R52] 统计行数
来源：http://dali.xinyue.icu/Article/details/gtburubxmi.html

wc -l a.txt
来源：http://dali.smart0.xyz/Article/details/gtwsjwxjzy.html

[R53] 查看文件头与实时尾
来源：http://dali.nanxuanxn.top/Article/details/gtqgfolthj.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.tian-w.cn/Article/details/gtaviidhwi.html

[R54] 比较两个文件
来源：http://dali.bjfxy.top/Article/details/gtkhjhppbh.html

diff a.txt b.txt
来源：http://dali.gzhubu.top/Article/details/gthxktpmru.html

[R55] 压缩与解压
来源：http://dali.wangshuangyany.cn/Article/details/gtvcivmkjg.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtjqikkgus.html

[R56] 远程拷贝
来源：http://dali.cucudq.cn/Article/details/gtjqnnuqgk.html

scp file user@host:/path/
来源：http://dali.yvedp.cn/Article/details/gtrmdwydta.html

[R57] 远程执行命令
来源：http://dali.jqgfzy.top/Article/details/gtlffemeza.html

ssh user@host 'uptime'
来源：http://dali.yvedp.cn/Article/details/gtqoclzebx.html

[R58] 下载文件
来源：http://dali.bjfxy.top/Article/details/gtfoavncwd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.gaohongyu789.top/Article/details/gttdkwliua.html

[R59] 发 POST JSON
来源：http://dali.chenzaomai.com/Article/details/gtofgwisnb.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sxryk.cn/Article/details/gtanjgbmkf.html

[R60] 只看 HTTP 状态码
来源：http://dali.redwolf501.top/Article/details/gtnvvdxels.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.ivvv.top/Article/details/gtyabdvper.html

[R61] 磁盘占用
来源：http://dali.hnqzz.top/Article/details/gtmtqhlegz.html

df -h;  du -sh *
来源：http://dali.tian-w.cn/Article/details/gtqxqybwaj.html

[R62] 找最占空间的文件
来源：http://dali.yj202588.top/Article/details/gtfhfymwxr.html

du -ah . | sort -rh | head -10
来源：http://dali.hfpthk.cn/Article/details/gtepbratpq.html

[R63] 内存与进程
来源：http://dali.zhoulong.xyz/Article/details/gtewpjndqz.html

free -h;  ps aux | grep nginx
来源：http://dali.redwolf501.top/Article/details/gtcwkanxcw.html

[R64] 结束进程
来源：http://dali.jqgufenzy.top/Article/details/gtqsrygozc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.dianchejie.cn/Article/details/gtngsvjqjk.html

[R65] 查看端口占用
来源：http://dali.jqgfzy.top/Article/details/gtcskvrval.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.c1oappe.top/Article/details/gtyayzpxsj.html

[R66] 定时任务
来源：http://dali.pengpengdd.cyou/Article/details/gtpngmekqn.html

crontab -e;  crontab -l
来源：http://dali.shanyushiyangtech.top/Article/details/gtpsagotwk.html

[R67] 生成随机十六进制串
来源：http://dali.jlsjyb.cn/Article/details/gtpqbsvwrx.html

openssl rand -hex 16
来源：http://dali.yonumen.top/Article/details/gtmieehytr.html

[R68] 计算文件校验值
来源：http://dali.feifeiyinyue.top/Article/details/gtdcgfojyg.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.wangshuangyany.cn/Article/details/gtotsuxzfo.html

[R69] 生成随机密码
来源：http://dali.wangshuangyany.cn/Article/details/gtxfrgjihf.html

head -c 16 /dev/urandom | base64
来源：http://dali.mhx1999.top/Article/details/gtvbtbghqx.html

[R70] 时间戳与互转
来源：http://dali.shanyushiyangtech.top/Article/details/gtkprapbyr.html

date +%s;  date -d @1700000000
来源：http://dali.chenlongwang.top/Article/details/gtvstnfgec.html

[R71] 日期格式化
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkdpptwdq.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jlsjyb.cn/Article/details/gtvjjznjug.html

[R72] 等待端口就绪
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjtqvohkq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.yj20258.top/Article/details/gtvpmvtajz.html

[R73] 分割大日志
来源：http://dali.gaohongyu789.top/Article/details/gtzvkpwzbb.html


<!-- 参考信息 -->