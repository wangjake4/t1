代发 wailian999

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.hfpthk.cn/Article/details/gtweverbnv.html

[Q32] 分组拼接字符串
来源：http://dali.yueranfly.top/Article/details/gtpnpxxnyn.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.smart0.xyz/Article/details/gtjavnncjp.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.pengpengdd.cyou/Article/details/gtmjhfktqd.html

[Q33] 多列分组
来源：http://dali.nanxuanxn.top/Article/details/gtxrkdstgc.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ppjwa.cn/Article/details/gtsvrlsobb.html

[Q34] 每组取第一条
来源：http://dali.zhaomingkeji.xyz/Article/details/gtgsnrnrnk.html

SELECT * FROM (
来源：http://dali.yueranfly.top/Article/details/gttygxqjvp.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.aibaodan.cn/Article/details/gttqepdyqx.html

) t WHERE rn = 1;
来源：http://dali.fengsongda.top/Article/details/gtcakepxuo.html

[Q35] 内连接
来源：http://dali.cdnleiting.top/Article/details/gtpkncfjbr.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.daria6918.cn/Article/details/gtkcnfkdqv.html

[Q36] 左连接
来源：http://dali.gaohongyu789.top/Article/details/gtnwljkkdk.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.c1oappe.top/Article/details/gtiwhpasqk.html

[Q37] 右连接
来源：http://dali.chenlongwang.top/Article/details/gtbkwdobkc.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.gaohongyu789.top/Article/details/gtgghxsops.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.svipenyu.cn/Article/details/gtnjgflwea.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.gogol.net.cn/Article/details/gthwexunix.html

[Q39] 自连接（查上下级）
来源：http://dali.sweek.top/Article/details/gtvbswfkzh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.xylfe.cn/Article/details/gtqwcqclnm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xinyue.icu/Article/details/gtgymtnenq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.guowangkeji.top/Article/details/gtqtinwqot.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.fzhhl.top/Article/details/gtkjmtjzct.html

[Q41] 多表连接
来源：http://dali.zhengqikj.top/Article/details/gtqtehuksv.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.pengpengdd.cyou/Article/details/gtddjpfney.html

JOIN users u ON u.id = o.user_id
来源：http://dali.vqdsnc.cn/Article/details/gtkrfopddq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzzunvvxg.html

[Q42] 连接条件附加过滤
来源：http://dali.chenjidiqi.icu/Article/details/gtytqtntmp.html

SELECT u.name, o.amount FROM users u
来源：http://dali.dianchejie.cn/Article/details/gtkhxuclps.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.tanke756.top/Article/details/gtlaxsjdoo.html

[Q43] 标量子查询
来源：http://dali.ivvv.top/Article/details/gtgngydlic.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtqwyhhwjm.html

[Q44] IN 子查询
来源：http://dali.hfpthk.cn/Article/details/gtkzsfhpfu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jqgufenzy.top/Article/details/gtbbdojofg.html

[Q45] EXISTS 判断存在
来源：http://dali.chenjidiqi.icu/Article/details/gtcuztyvsv.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tianlin.xyz/Article/details/gtdrpzaxvc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.gotoacloud.top/Article/details/gtmddqqqzc.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.c1oappe.top/Article/details/gtkcnrswxc.html

[Q47] 与平均值比较
来源：http://dali.zhiwuduotai.top/Article/details/gtpnknyscw.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.aibaodan.cn/Article/details/gtumadckxr.html

[Q48] CTE 公用表表达式
来源：http://dali.xinyue.icu/Article/details/gttdmhorra.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hongshengwenyu.top/Article/details/gtjdgfxndq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.svipenyu.cn/Article/details/gtyapzguqj.html

[Q49] 更新单行
来源：http://dali.xuetiantiany.cn/Article/details/gtjzcazfjd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.9152youxi.cn/Article/details/gtcpvljqgo.html

[Q50] 批量更新
来源：http://dali.sysykeji.top/Article/details/gtddpuvjln.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.jinyuanbaomall.cn/Article/details/gttlgdhfjf.html

[Q51] 用子查询更新
来源：http://dali.meibo888.top/Article/details/gtctkqrwvl.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.cheryme.top/Article/details/gtdzvrqhvz.html

[Q52] 删除指定行
来源：http://dali.guannengcc.top/Article/details/gtrdbelgqj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.wangshuangyany.cn/Article/details/gtkwwhkpiw.html

[Q53] 按条件删除
来源：http://dali.c1oappe.top/Article/details/gtfxnfggnx.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.sufxvd.cn/Article/details/gtxvltcsgd.html

[Q54] 清空表
来源：http://dali.jinghuilouyu.cn/Article/details/gtvnzprenz.html

TRUNCATE TABLE logs;
来源：http://dali.tanke756.top/Article/details/gtscfcdaxi.html

[Q55] 排名（并列占位）
来源：http://dali.yonumen.top/Article/details/gtkakpnezw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.cashguo.top/Article/details/gtaypufrww.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yongpay.top/Article/details/gtmpdctmbu.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.chenzaomai.com/Article/details/gtqrynkwjs.html

[Q57] 行号
来源：http://dali.jyoumei.cn/Article/details/gtfwjoqhyp.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.nwbrower.top/Article/details/gtkjhdkyxa.html

[Q58] 累计求和
来源：http://dali.cheryme.top/Article/details/gtilurmnxb.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gtjtmjnzxr.html

[Q59] 分组内累计
来源：http://dali.quarkkingdee.top/Article/details/gtsnqnsolh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.haohaochexian.top/Article/details/gtxclrxupy.html

[Q60] 取上一行 / 下一行
来源：http://dali.xuanzx.com/Article/details/gtlfwmagay.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.ydzc1.top/Article/details/gtalapelru.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhongyouzk.top/Article/details/gtjjboevkl.html

[Q61] 移动平均
来源：http://dali.jinghuilouyu.cn/Article/details/gtdjtlialt.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.gogol.net.cn/Article/details/gtrbupxuaj.html

[Q62] 分组占比
来源：http://dali.xuanzx.com/Article/details/gtcyjuczop.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.pengpengdd.cyou/Article/details/gtaigxclio.html

[Q63] 开启事务
来源：http://dali.cdnleiting.top/Article/details/gtdspuwyuc.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yanxiufei.cn/Article/details/gtyilesgbx.html

[Q64] 提交事务
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkmpbchop.html

COMMIT;
来源：http://dali.zhengqikj.top/Article/details/gtzvnrkhny.html

[Q65] 回滚事务
来源：http://dali.tian-w.cn/Article/details/gtdkmpkylu.html

ROLLBACK;
来源：http://dali.yj202588.top/Article/details/gtuibyfkrt.html

[Q66] 行锁查询
来源：http://dali.smart0.xyz/Article/details/gtoazeinxg.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.nanxinkj.top/Article/details/gtgibwhvki.html

[Q67] 设置隔离级别
来源：http://dali.cashguo.top/Article/details/gtcyfxgsdd.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.shangyingyoupin.top/Article/details/gtduyshxvz.html

[Q68] 保存点
来源：http://dali.shanyushiyangkeji.top/Article/details/gttkqdqqmi.html

SAVEPOINT sp1;
来源：http://dali.zhoulong.xyz/Article/details/gtgyklyytl.html

ROLLBACK TO sp1;
来源：http://dali.316326.xyz/Article/details/gtadaalxtm.html

[Q69] 查看执行计划
来源：http://dali.guowangkeji.top/Article/details/gthqpufqrj.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.hnxiangtu.top/Article/details/gttldfjybh.html

[Q70] 更新统计信息
来源：http://dali.cqqwz.cn/Article/details/gtcvkftxct.html

ANALYZE TABLE users;
来源：http://dali.shuidangran.top/Article/details/gtytgwvxyh.html

[Q71] 查看建表语句
来源：http://dali.shuidangran.top/Article/details/gtpkyjsriy.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.yj20258888.top/Article/details/gtinibilau.html

[Q72] 查看索引
来源：http://dali.shanyushiyangkeji.top/Article/details/gtifhdrfot.html

SHOW INDEX FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtsbgwbsdg.html

[Q73] 查看表状态
来源：http://dali.zhixingplan.top/Article/details/gtusrqsjcr.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmbpwsvkq.html

[Q74] 强制使用索引
来源：http://dali.yvedp.cn/Article/details/gtsknbwhhf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.fzhhl.top/Article/details/gtvvurxysr.html

[Q75] 日期格式化
来源：http://dali.iojbl.cn/Article/details/gtaelhegbe.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.bjfxy.top/Article/details/gtdbgzzjmq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.yonumen.top/Article/details/gtkmdkbhzx.html

[Q76] 按天统计
来源：http://dali.svipenyu.cn/Article/details/gtuqnomfat.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.sweek.top/Article/details/gtkyqogkjt.html

[Q77] 时间加减
来源：http://dali.zhongyouzk.top/Article/details/gtojyecyxq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cheryme.top/Article/details/gtuyrdcgys.html

[Q78] 当前时间
来源：http://dali.yangfankeji.com/Article/details/gthhhcvbep.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xziqi.cn/Article/details/gtcolbrcso.html

[Q79] 字符串拼接
来源：http://dali.tian-w.cn/Article/details/gtguygtkbg.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.ybcxt.top/Article/details/gtbndcssgr.html

[Q80] 字符串截取
来源：http://dali.jqgufenzy.top/Article/details/gtpcebhdhf.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.guannengcc.top/Article/details/gtqzewpwmw.html

[Q81] 字符串替换
来源：http://dali.ehwqpu.com/Article/details/gtiyccylhr.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.jqgfzy.top/Article/details/gtjtkhmrpo.html

[Q82] 字符长度与字节长度
来源：http://dali.316326.xyz/Article/details/gtorxehxex.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shzxlz.cn/Article/details/gtmelxsuvw.html

[Q83] 大小写转换
来源：http://dali.jqgfzy.top/Article/details/gtnlihxgcz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtxjufcmpz.html

[Q84] 去除首尾空格
来源：http://dali.shangyingyoupin.top/Article/details/gtlkkbtort.html

SELECT TRIM(name) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtrbqkiusg.html

[Q85] 数值取整
来源：http://dali.chenjidiqi.icu/Article/details/gtysmkrjye.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.zhijiandao.cn/Article/details/gteerxtdey.html

[Q86] 读取 JSON 字段
来源：http://dali.yongpay.top/Article/details/gtfeivgqmj.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.zhiwuduotai.top/Article/details/gtdovbkmop.html

[Q87] JSON 字段做条件
来源：http://dali.snrcjt.cn/Article/details/gtndgbtkzw.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.kuanghao11.cn/Article/details/gtsrqdxlkb.html

[Q88] 行转列（条件聚合）
来源：http://dali.hfpthk.cn/Article/details/gtcinouyha.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.birdmap.top/Article/details/gtoonmhggj.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.andypj.xyz/Article/details/gtssiqklhr.html

[Q89] 判断表是否存在
来源：http://dali.nanxinkj.top/Article/details/gtefeyhsks.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyasjdoml.html

[Q90] 生成序号列
来源：http://dali.daxiang520.top/Article/details/gtyrqvwpfi.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.dianchejie.cn/Article/details/gtotegewns.html

================================================================================
来源：http://dali.daria6918.cn/Article/details/gtierasluu.html

R. Bash 专题
来源：http://dali.cqqwz.cn/Article/details/gthsnopins.html

================================================================================
来源：http://dali.0kj1m.cn/Article/details/gtungfshna.html

[R01] shebang 与严格模式
来源：http://dali.yj20258.top/Article/details/gtfdirtxhv.html

#!/usr/bin/env bash
来源：http://dali.yongpay.top/Article/details/gtmfefmtiu.html

set -euo pipefail
来源：http://dali.andypj.xyz/Article/details/gtcfhjnczi.html

[R02] 变量赋值与使用
来源：http://dali.jqgfzy.top/Article/details/gtmponecac.html

name="Tom"; echo "$name"
来源：http://dali.xziqi.cn/Article/details/gtkffvkvjq.html

[R03] 只读变量
来源：http://dali.meibo888.top/Article/details/gtptxqtglm.html

readonly PI=3.14
来源：http://dali.vqdsnc.cn/Article/details/gtmcnfuudq.html

[R04] 位置参数
来源：http://dali.yuanzhike.top/Article/details/gtibbcfchh.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jlsjyb.cn/Article/details/gtmjbrvztl.html

[R05] 参数默认值
来源：http://dali.nanxinkj.top/Article/details/gthvvyaaim.html

name="${1:-default}"
来源：http://dali.yuanzhike.top/Article/details/gtthiqpmaz.html

[R06] 判断命令是否存在
来源：http://dali.dianchejie.cn/Article/details/gtttnrxsad.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.andypj.xyz/Article/details/gtsivmhgcx.html

[R07] if 判断文件
来源：http://dali.zhixingplan.top/Article/details/gtervvrkkr.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xinyue.icu/Article/details/gtwoklzepn.html

[R08] 数值比较
来源：http://dali.xuanzx.com/Article/details/gtrrlkjbuv.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.gotoacloud.top/Article/details/gtvqlwurms.html

[R09] 字符串比较
来源：http://dali.yonumen.top/Article/details/gtkoxuozvg.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jinqigufen.top/Article/details/gttxrmkjcm.html

[R10] 正则匹配
来源：http://dali.sufxvd.cn/Article/details/gtinsobjbc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shuidangran.top/Article/details/gtfdzqcwaq.html

[R11] case 多分支
来源：http://dali.chenlongwang.top/Article/details/gtkxjpqcew.html

case "$1" in
来源：http://dali.yj20258.top/Article/details/gtwnlewogc.html

start) echo "启动" ;;
来源：http://dali.jiagoushi.top/Article/details/gtgzxenhtm.html

stop)  echo "停止" ;;
来源：http://dali.meibo888.top/Article/details/gtkpxmhhvl.html

*)     echo "未知命令" ;;
来源：http://dali.cheryme.top/Article/details/gtaahohhac.html

esac
来源：http://dali.aibaodan.cn/Article/details/gtvoitejbm.html

[R12] for 遍历文件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtwdckrzcs.html

for f in *.txt; do echo "$f"; done
来源：http://dali.yj20258888.top/Article/details/gtgxmjhjyl.html

[R13] for 计数循环
来源：http://dali.smart0.xyz/Article/details/gtwsfovohg.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.fengsongda.top/Article/details/gtnphzhksw.html

[R14] C 风格 for
来源：http://dali.cashguo.top/Article/details/gtghutzewe.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.nanxuanxn.top/Article/details/gtpghdgswm.html

[R15] while 逐行读文件
来源：http://dali.yuxming.cn/Article/details/gtnzcljnef.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.meibo888.top/Article/details/gtunjeoppj.html

[R16] until 等待条件
来源：http://dali.jinghuilouyu.cn/Article/details/gtpnipkmoj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.guannengcc.top/Article/details/gtmbjixpbu.html

[R17] 数组定义与取值
来源：http://dali.nanxinkj.top/Article/details/gtzirjgvve.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.guannengcc.top/Article/details/gtpzfooaxg.html

[R18] 遍历数组
来源：http://dali.xinyue.icu/Article/details/gtfjtocdne.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.zdqjudy.top/Article/details/gthzkslwtu.html

[R19] 数组长度
来源：http://dali.nwbrower.top/Article/details/gthyjoxkek.html

echo "${#arr[@]}"
来源：http://dali.kuanghao11.cn/Article/details/gtpeeijods.html

[R20] 关联数组（字典）
来源：http://dali.hywenlv.cn/Article/details/gtiibtgfwf.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.smart0.xyz/Article/details/gtxztlvizc.html

[R21] 字符串长度
来源：http://dali.sweek.top/Article/details/gtjzzhvcgd.html

echo "${#s}"
来源：http://dali.tanke756.top/Article/details/gtwamcrhxc.html

[R22] 截取子串
来源：http://dali.xinyue.icu/Article/details/gtyssynkmp.html

echo "${s:0:5}"
来源：http://dali.0kj1m.cn/Article/details/gtxreetgka.html

[R23] 字符串替换
来源：http://dali.jlsjyb.cn/Article/details/gtmmgohmzm.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.shuidangran.top/Article/details/gtxtfbdlrw.html

[R24] 大小写转换
来源：http://dali.cdnleiting.top/Article/details/gtzrvyoswj.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.cheryme.top/Article/details/gtixbzykul.html

[R25] 去后缀 / 去前缀
来源：http://dali.zhiwuduotai.top/Article/details/gtafjpkyrm.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.xziqi.cn/Article/details/gtmeawmokp.html

[R26] 命令替换
来源：http://dali.pengpengdd.cyou/Article/details/gtvjufexea.html

now=$(date +%F); echo "$now"
来源：http://dali.andypj.xyz/Article/details/gtxkxdudvk.html

[R27] 算术展开
来源：http://dali.yongpay.top/Article/details/gtgikjqrgf.html

echo $((1 + 2 * 3))
来源：http://dali.yanxiufei.cn/Article/details/gtmqierckq.html

[R28] 浮点运算
来源：http://dali.zhijiandao.cn/Article/details/gtftsblssl.html

echo "scale=2; 10/3" | bc
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtbmwkivnq.html

[R29] 定义函数
来源：http://dali.shzxlz.cn/Article/details/gthhdnhigi.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cdnleiting.top/Article/details/gtnlwvpjas.html

[R30] 函数返回状态码
来源：http://dali.zhixingplan.top/Article/details/gtcvejktbz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.mhx1999.top/Article/details/gtsvwwczgv.html

[R31] 局部变量
来源：http://dali.tanke756.top/Article/details/gtwyticyjx.html

f() { local x=1; echo "$x"; }
来源：http://dali.pycfn.com/Article/details/gtcczorwjf.html

[R32] 参数个数校验
来源：http://dali.wangdashe.top/Article/details/gtxihoegpb.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ybcxt.top/Article/details/gtaxbbpqdi.html

[R33] 捕获错误并提示行号
来源：http://dali.birdmap.top/Article/details/gtocgnfgmf.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.wangdashe.top/Article/details/gtmktftude.html

[R34] 退出时清理
来源：http://dali.tanke756.top/Article/details/gtgyslfneg.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.daria6918.cn/Article/details/gtmceaeify.html

[R35] 后台执行并等待
来源：http://dali.yonumen.top/Article/details/gtwdannyky.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.iojbl.cn/Article/details/gtzcryxaor.html

[R36] 并发执行多个任务
来源：http://dali.wangshuangyany.cn/Article/details/gtodploaeo.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.aizwys.cn/Article/details/gtrcfyjppg.html

[R37] 把输出赋给变量
来源：http://dali.gogol.net.cn/Article/details/gtowwcyzdn.html

files=$(ls -1)
来源：http://dali.tanke756.top/Article/details/gtplekqsva.html

[R38] 管道串联
来源：http://dali.sweek.top/Article/details/gtxelqvlbv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.jianghu66.top/Article/details/gtlivgtpcn.html

[R39] 重定向标准输出与错误
来源：http://dali.bjfxy.top/Article/details/gtdresaczx.html

cmd > out.log 2>&1
来源：http://dali.smart0.xyz/Article/details/gtpzwrvmez.html

[R40] 追加写日志
来源：http://dali.haohaochexian.top/Article/details/gtkunnqzul.html

echo "log" >> out.log
来源：http://dali.yonumen.top/Article/details/gtvlyacyps.html

[R41] 丢弃输出
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdyaehpah.html

cmd >/dev/null 2>&1
来源：http://dali.nanxuanxn.top/Article/details/gtovyojbfx.html

[R42] 输入重定向
来源：http://dali.zhixingplan.top/Article/details/gtimglgbno.html

wc -l < a.txt
来源：http://dali.hywenlv.cn/Article/details/gtfehdrvsb.html

[R43] 按名字查找文件
来源：http://dali.gaohongyu789.top/Article/details/gtzjogwwjz.html

find . -name "*.log" -type f
来源：http://dali.hfpthk.cn/Article/details/gtntbakkaa.html

[R44] 按修改时间查找
来源：http://dali.nanxuanxn.top/Article/details/gtvwaivpsf.html

find . -mtime -7 -type f
来源：http://dali.redwolf501.top/Article/details/gtevscxlrn.html

[R45] 批量删除
来源：http://dali.cheryme.top/Article/details/gtjkibwmrh.html

find . -name "*.tmp" -delete
来源：http://dali.zdqjudy.top/Article/details/gtwjwktwcd.html

[R46] 递归替换文件内容
来源：http://dali.gaohongyu789.top/Article/details/gtgbhyaeuc.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.wangshuangyany.cn/Article/details/gtoklrvbib.html

[R47] sed 单行替换
来源：http://dali.meibo888.top/Article/details/gtilgiwlcq.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.sysykeji.top/Article/details/gtdzypawhg.html

[R48] awk 取指定列
来源：http://dali.cqqwz.cn/Article/details/gtmpndiqyo.html

awk '{print $1, $3}' a.txt
来源：http://dali.xuanzx.com/Article/details/gtityobrpo.html

[R49] awk 带条件
来源：http://dali.guannengcc.top/Article/details/gtbfwyetir.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.andypj.xyz/Article/details/gtsenqnnkc.html

[R50] awk 求和
来源：http://dali.shanyushiyangkeji.top/Article/details/gtyerowsuu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yj20258.top/Article/details/gtxctxrman.html

[R51] 排序去重取前几
来源：http://dali.cdnleiting.top/Article/details/gtuvewvmex.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.chenlongwang.top/Article/details/gtpmdlexfz.html

[R52] 统计行数
来源：http://dali.jinqigfzy.top/Article/details/gtgvnlrdjy.html

wc -l a.txt
来源：http://dali.jiagoushi.top/Article/details/gtvszjubez.html

[R53] 查看文件头与实时尾
来源：http://dali.jinqigfzy.top/Article/details/gtcifenfde.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shuidangran.top/Article/details/gtxvylkujr.html

[R54] 比较两个文件
来源：http://dali.xylfe.cn/Article/details/gtxhcxjrmg.html

diff a.txt b.txt
来源：http://dali.9152youxi.cn/Article/details/gtsteyxyba.html

[R55] 压缩与解压
来源：http://dali.yj20258.top/Article/details/gtamkyiqxs.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.feifeiyinyue.top/Article/details/gtelnztlhl.html

[R56] 远程拷贝
来源：http://dali.jqgufenzy.top/Article/details/gtxnniquqf.html

scp file user@host:/path/
来源：http://dali.guowangkeji.top/Article/details/gthzaeqzkh.html

[R57] 远程执行命令
来源：http://dali.ehwqpu.com/Article/details/gttjuujfxt.html

ssh user@host 'uptime'
来源：http://dali.hammf.cn/Article/details/gttiwudoyg.html

[R58] 下载文件
来源：http://dali.zycfv.cn/Article/details/gtspebwffs.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.dashuyun.cn/Article/details/gtsvrrvfau.html

[R59] 发 POST JSON
来源：http://dali.zhijiandao.cn/Article/details/gtughygfkq.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.yanxiufei.cn/Article/details/gtovmstwpg.html

[R60] 只看 HTTP 状态码
来源：http://dali.zhengqikj.top/Article/details/gtlykoqcwd.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cdnleiting.top/Article/details/gtezfxebhr.html

[R61] 磁盘占用
来源：http://dali.ydzc1.top/Article/details/gtrahisgtw.html

df -h;  du -sh *
来源：http://dali.zhiwuduotai.top/Article/details/gtvzecnume.html

[R62] 找最占空间的文件
来源：http://dali.jqgufenzy.top/Article/details/gtbftqwrma.html

du -ah . | sort -rh | head -10
来源：http://dali.guannengcc.top/Article/details/gtorxqfsmz.html

[R63] 内存与进程
来源：http://dali.nanxuanxn.top/Article/details/gtosyrruyi.html

free -h;  ps aux | grep nginx
来源：http://dali.fengsongda.top/Article/details/gtvoirlkps.html

[R64] 结束进程
来源：http://dali.zycfv.cn/Article/details/gtjxovntbd.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinyuanbaomall.cn/Article/details/gtljcdutpc.html

[R65] 查看端口占用
来源：http://dali.zhiwuduotai.top/Article/details/gtnsoezeol.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hfpthk.cn/Article/details/gtstndmwfy.html

[R66] 定时任务
来源：http://dali.jqgufenzy.top/Article/details/gtffjkmgrr.html

crontab -e;  crontab -l
来源：http://dali.zhijiandao.cn/Article/details/gtzszayzvc.html

[R67] 生成随机十六进制串
来源：http://dali.shzxlz.cn/Article/details/gtsbhmcojg.html

openssl rand -hex 16
来源：http://dali.shanyushiyangtech.top/Article/details/gtogxvzdve.html

[R68] 计算文件校验值
来源：http://dali.jianghu66.top/Article/details/gtyydczpzm.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jyoumei.cn/Article/details/gtgfabqypx.html

[R69] 生成随机密码
来源：http://dali.jlsjyb.cn/Article/details/gtgwdgsjyl.html

head -c 16 /dev/urandom | base64
来源：http://dali.0kj1m.cn/Article/details/gtukshnkje.html

[R70] 时间戳与互转
来源：http://dali.chenlongwang.top/Article/details/gtvjwyqeip.html

date +%s;  date -d @1700000000
来源：http://dali.zhixingplan.top/Article/details/gtvpxvqadh.html

[R71] 日期格式化
来源：http://dali.zhaomingkeji.xyz/Article/details/gtboplegxy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yangfankeji.com/Article/details/gtilypikve.html

[R72] 等待端口就绪
来源：http://dali.nanxinkj.top/Article/details/gtujqpilix.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.fengsongda.top/Article/details/gtaxqjghti.html

[R73] 分割大日志
来源：http://dali.sxryk.cn/Article/details/gtmpnmewfd.html

split -l 1000 big.log part_
来源：http://dali.jianghu66.top/Article/details/gtbxrnvwca.html

[R74] 批量重命名
来源：http://dali.yvedp.cn/Article/details/gtnyqxuodn.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.0kj1m.cn/Article/details/gtpzwdgurg.html

[R75] 导出环境变量
来源：http://dali.jianghu66.top/Article/details/gtutsgktvj.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.chenzaomai.com/Article/details/gtxqaodwwk.html

[R76] 使用临时文件
来源：http://dali.yj20258888.top/Article/details/gtpaipjniw.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.xinyue.icu/Article/details/gtivnevftq.html

[R77] 读取用户输入
来源：http://dali.hysaishi.cn/Article/details/gthuoklycn.html

read -rp "请输入: " ans
来源：http://dali.yonumen.top/Article/details/gtnstijmuz.html

[R78] 交互式菜单
来源：http://dali.jlsjyb.cn/Article/details/gtycveihuc.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ydzc1.top/Article/details/gtlhfnyrsr.html

[R79] 解析命令行选项
来源：http://dali.smart0.xyz/Article/details/gtswrlnztd.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdhwkopbg.html

[R80] 查看脚本执行耗时
来源：http://dali.ehwqpu.com/Article/details/gtincghhxn.html

time ./run.sh
来源：http://dali.cqqwz.cn/Article/details/gtperfyzpd.html

================================================================================
来源：http://dali.gzhubu.top/Article/details/gtzwnymdms.html


<!-- 参考信息 -->