代发 wailian999

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.yj20258888.top/Article/details/gtmxvovyto.html

[Q28] 求和与平均
来源：http://dali.xinyue.icu/Article/details/gthgiezcpj.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.guowangkeji.top/Article/details/gtglxksxjb.html

[Q29] 最大最小值
来源：http://dali.yonumen.top/Article/details/gtsrkedlvr.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtavqlyrgq.html

[Q30] 分组统计
来源：http://dali.aizwys.cn/Article/details/gtifzekjxv.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.andypj.xyz/Article/details/gtrzbeyrvo.html

[Q31] 分组后过滤
来源：http://dali.guannengcc.top/Article/details/gtgntgnnoj.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.jlsjyb.cn/Article/details/gtfjzyswmm.html

[Q32] 分组拼接字符串
来源：http://dali.snrcjt.cn/Article/details/gthfgqtbcb.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.yangfankeji.com/Article/details/gtzuhxmaoq.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.jqgfzy.top/Article/details/gtilguavgr.html

[Q33] 多列分组
来源：http://dali.shuidangran.top/Article/details/gtyjmwiroz.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.wangdashe.top/Article/details/gtrypislvo.html

[Q34] 每组取第一条
来源：http://dali.havefunace.top/Article/details/gtuclzjxzn.html

SELECT * FROM (
来源：http://dali.shuidangran.top/Article/details/gtaisounum.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.cdnleiting.top/Article/details/gtsucahipc.html

) t WHERE rn = 1;
来源：http://dali.dashuyun.cn/Article/details/gtiscqrovv.html

[Q35] 内连接
来源：http://dali.smart0.xyz/Article/details/gtqckztqpv.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hfpthk.cn/Article/details/gtlnsxixct.html

[Q36] 左连接
来源：http://dali.svipenyu.cn/Article/details/gtdaroonkb.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.cucudq.cn/Article/details/gtyqzatuyd.html

[Q37] 右连接
来源：http://dali.xylfe.cn/Article/details/gtevpwlexx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.guannengcc.top/Article/details/gtrxugspmt.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.jiagoushi.top/Article/details/gtutrklgti.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.xuanzx.com/Article/details/gtjgjnjvgk.html

[Q39] 自连接（查上下级）
来源：http://dali.jinqigufen.top/Article/details/gtvahswncg.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.daxiang520.top/Article/details/gtcuygfyvl.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.nanxuanxn.top/Article/details/gtyfxiojnq.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.daria6918.cn/Article/details/gtshftxudz.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.tanke756.top/Article/details/gtwaksajdp.html

[Q41] 多表连接
来源：http://dali.pycfn.com/Article/details/gthfnjoayj.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhoulong.xyz/Article/details/gtwwvkncux.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yj20258888.top/Article/details/gtnytsmuyw.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.daxiang520.top/Article/details/gtnizfcgoz.html

[Q42] 连接条件附加过滤
来源：http://dali.quarkkingdee.top/Article/details/gtjzayzksg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.nanxinkj.top/Article/details/gtrsrkmxvk.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zdqjudy.top/Article/details/gtghaiyqfv.html

[Q43] 标量子查询
来源：http://dali.yj20258.top/Article/details/gtufwzcnok.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.cqqwz.cn/Article/details/gtovorhkvg.html

[Q44] IN 子查询
来源：http://dali.shanyushiyangtech.top/Article/details/gtevqmblhk.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.nanxinkj.top/Article/details/gtyyphwuzy.html

[Q45] EXISTS 判断存在
来源：http://dali.meibo888.top/Article/details/gtbwnxunza.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gzhubu.top/Article/details/gttjridcrq.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.pycfn.com/Article/details/gtvflihkvr.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigfzy.top/Article/details/gtopcjaiej.html

[Q47] 与平均值比较
来源：http://dali.xuetiantiany.cn/Article/details/gtonrjfbku.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.yanxiufei.cn/Article/details/gtpokjvpfl.html

[Q48] CTE 公用表表达式
来源：http://dali.ydzc1.top/Article/details/gttpjmifml.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.9152youxi.cn/Article/details/gtjnhdyfbh.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.cqqwz.cn/Article/details/gtzvufxgyb.html

[Q49] 更新单行
来源：http://dali.chenlongwang.top/Article/details/gtqfatsjcs.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.316326.xyz/Article/details/gtggmqlpqe.html

[Q50] 批量更新
来源：http://dali.sxryk.cn/Article/details/gtnwkamrdx.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhoulong.xyz/Article/details/gtrmdfvrhd.html

[Q51] 用子查询更新
来源：http://dali.dianchejie.cn/Article/details/gtwxvrxtqa.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.hongshengwenyu.top/Article/details/gtfvojucsf.html

[Q52] 删除指定行
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmajxbpip.html

DELETE FROM users WHERE id = 10;
来源：http://dali.sysykeji.top/Article/details/gtjpilieic.html

[Q53] 按条件删除
来源：http://dali.hfpthk.cn/Article/details/gtgxamhaxm.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.chenjidiqi.icu/Article/details/gtdqnguwuj.html

[Q54] 清空表
来源：http://dali.yj20258888.top/Article/details/gtuqppcdta.html

TRUNCATE TABLE logs;
来源：http://dali.hnxiangtu.top/Article/details/gtddlrwhfw.html

[Q55] 排名（并列占位）
来源：http://dali.shuidangran.top/Article/details/gtvmvnzvou.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.chenjidiqi.icu/Article/details/gtreataygh.html

[Q56] 密集排名（并列不占位）
来源：http://dali.haohaochexian.top/Article/details/gtjtbdhfki.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.gotoacloud.top/Article/details/gtxstgmoub.html

[Q57] 行号
来源：http://dali.yonumen.top/Article/details/gtojhivrcl.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.sxryk.cn/Article/details/gtsakkzmzo.html

[Q58] 累计求和
来源：http://dali.kuanghao11.cn/Article/details/gtrrbagikd.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.dashuyun.cn/Article/details/gtvxxfdrvz.html

[Q59] 分组内累计
来源：http://dali.tianlin.xyz/Article/details/gtcsllfhtj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.9152youxi.cn/Article/details/gtrnmehnrp.html

[Q60] 取上一行 / 下一行
来源：http://dali.yuanzhike.top/Article/details/gtpgrmovmg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.zhongyouzk.top/Article/details/gtlkkypebl.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.cucudq.cn/Article/details/gtvontxwae.html

[Q61] 移动平均
来源：http://dali.svipenyu.cn/Article/details/gtinissvup.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.tanke756.top/Article/details/gthfvgvlko.html

[Q62] 分组占比
来源：http://dali.zhixingplan.top/Article/details/gtyrbhnprx.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.kuanghao11.cn/Article/details/gtvxabhrbo.html

[Q63] 开启事务
来源：http://dali.tianlin.xyz/Article/details/gtzsojfbzh.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.nanxinkj.top/Article/details/gtvajljxap.html

[Q64] 提交事务
来源：http://dali.jianghu66.top/Article/details/gtcexbvojf.html

COMMIT;
来源：http://dali.guowangkeji.top/Article/details/gtsdleewgd.html

[Q65] 回滚事务
来源：http://dali.jlsjyb.cn/Article/details/gtxhkbuzkj.html

ROLLBACK;
来源：http://dali.yuxming.cn/Article/details/gtcbtdijpq.html

[Q66] 行锁查询
来源：http://dali.xuanzx.com/Article/details/gthhdbooac.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.jiagoushi.top/Article/details/gtlmhfkzlm.html

[Q67] 设置隔离级别
来源：http://dali.yj202588.top/Article/details/gtffheqeqm.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.fzhhl.top/Article/details/gtdqkufdda.html

[Q68] 保存点
来源：http://dali.chenjidiqi.icu/Article/details/gtzqsybtmo.html

SAVEPOINT sp1;
来源：http://dali.cucudq.cn/Article/details/gtdzmwpdxo.html

ROLLBACK TO sp1;
来源：http://dali.hfpthk.cn/Article/details/gtszwivuml.html

[Q69] 查看执行计划
来源：http://dali.aizwys.cn/Article/details/gtkzjmshzr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.ybcxt.top/Article/details/gtwbrjeqop.html

[Q70] 更新统计信息
来源：http://dali.ivvv.top/Article/details/gtdknqpbml.html

ANALYZE TABLE users;
来源：http://dali.meibo888.top/Article/details/gtnycolrps.html

[Q71] 查看建表语句
来源：http://dali.ehwqpu.com/Article/details/gtwrrzegax.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.hywenlv.cn/Article/details/gtlqwzeqaq.html

[Q72] 查看索引
来源：http://dali.jlsjyb.cn/Article/details/gtzdiioxmb.html

SHOW INDEX FROM users;
来源：http://dali.316326.xyz/Article/details/gtobxogoun.html

[Q73] 查看表状态
来源：http://dali.hnxiangtu.top/Article/details/gtkrewqmiy.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.redwolf501.top/Article/details/gtjstmyujp.html

[Q74] 强制使用索引
来源：http://dali.yongpay.top/Article/details/gttcnowqlw.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.ybcxt.top/Article/details/gtafwzseqr.html

[Q75] 日期格式化
来源：http://dali.tianlin.xyz/Article/details/gtadswackg.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.hnxiangtu.top/Article/details/gtlwxelhkv.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.bjfxy.top/Article/details/gtdycyehwh.html

[Q76] 按天统计
来源：http://dali.jlsjyb.cn/Article/details/gtplnwtsxi.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhongyouzk.top/Article/details/gtssdyomhu.html

[Q77] 时间加减
来源：http://dali.ppjwa.cn/Article/details/gtooewhhld.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.meibo888.top/Article/details/gtmrdwjooh.html

[Q78] 当前时间
来源：http://dali.shuidangran.top/Article/details/gtmmxdnosu.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.cashguo.top/Article/details/gtudrqdbqr.html

[Q79] 字符串拼接
来源：http://dali.fengsongda.top/Article/details/gtjqbbprlk.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jiagoushi.top/Article/details/gteleqkiqz.html

[Q80] 字符串截取
来源：http://dali.gogol.net.cn/Article/details/gteetakkkk.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.tian-w.cn/Article/details/gtmijrwbbc.html

[Q81] 字符串替换
来源：http://dali.hnqzz.top/Article/details/gtofjvdxom.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.cdnleiting.top/Article/details/gtwmasvcih.html

[Q82] 字符长度与字节长度
来源：http://dali.hammf.cn/Article/details/gthbbhlvzl.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.tanke756.top/Article/details/gtobsmibgd.html

[Q83] 大小写转换
来源：http://dali.gogol.net.cn/Article/details/gtcqruqdgl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cashguo.top/Article/details/gttepxhqxq.html

[Q84] 去除首尾空格
来源：http://dali.zdqjudy.top/Article/details/gtfsxwfsvj.html

SELECT TRIM(name) FROM users;
来源：http://dali.dashuyun.cn/Article/details/gtsppkeyya.html

[Q85] 数值取整
来源：http://dali.cdnleiting.top/Article/details/gtagfnjqrs.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.shanyushiyangtech.top/Article/details/gtlpgsbzxx.html

[Q86] 读取 JSON 字段
来源：http://dali.yj202588.top/Article/details/gteinuxqxk.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.feifeiyinyue.top/Article/details/gtgzisqvaj.html

[Q87] JSON 字段做条件
来源：http://dali.birdmap.top/Article/details/gtknzpwdaj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.chenzaomai.com/Article/details/gtjciqaftf.html

[Q88] 行转列（条件聚合）
来源：http://dali.daxiang520.top/Article/details/gtlynlqwdc.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzcpwpbof.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.jiagoushi.top/Article/details/gtatplovqx.html

[Q89] 判断表是否存在
来源：http://dali.meibo888.top/Article/details/gthmtaguhb.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.chenzaomai.com/Article/details/gtigxekhfp.html

[Q90] 生成序号列
来源：http://dali.sufxvd.cn/Article/details/gtrivmrrnt.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.cqqwz.cn/Article/details/gtbihkzzvr.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtdejuykxp.html

R. Bash 专题
来源：http://dali.ybcxt.top/Article/details/gtvpfzcotq.html

================================================================================
来源：http://dali.hywenlv.cn/Article/details/gtcgbpfgby.html

[R01] shebang 与严格模式
来源：http://dali.ehwqpu.com/Article/details/gtfbqszufk.html

#!/usr/bin/env bash
来源：http://dali.gaohongyu789.top/Article/details/gtzlxaoytz.html

set -euo pipefail
来源：http://dali.ppjwa.cn/Article/details/gthufmufax.html

[R02] 变量赋值与使用
来源：http://dali.fengsongda.top/Article/details/gtcvzxoebe.html

name="Tom"; echo "$name"
来源：http://dali.fzhhl.top/Article/details/gtfzzfnkbs.html

[R03] 只读变量
来源：http://dali.hongshengwenyu.top/Article/details/gtgdwfdlro.html

readonly PI=3.14
来源：http://dali.cqqwz.cn/Article/details/gttmtgzolr.html

[R04] 位置参数
来源：http://dali.fengsongda.top/Article/details/gtqucpajsa.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhixingplan.top/Article/details/gtbhszcbxj.html

[R05] 参数默认值
来源：http://dali.xylfe.cn/Article/details/gtzolqnzwg.html

name="${1:-default}"
来源：http://dali.hysaishi.cn/Article/details/gtfwfnbciw.html

[R06] 判断命令是否存在
来源：http://dali.gogol.net.cn/Article/details/gtnjlimnra.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.tian-w.cn/Article/details/gtgzlznkry.html

[R07] if 判断文件
来源：http://dali.cheryme.top/Article/details/gtpwvyjlzf.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.aizwys.cn/Article/details/gththceocf.html

[R08] 数值比较
来源：http://dali.jqgfzy.top/Article/details/gtrosaxnry.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gtgiqxdyiv.html

[R09] 字符串比较
来源：http://dali.tianlin.xyz/Article/details/gtnhqwxfra.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zycfv.cn/Article/details/gtbbkqvjxw.html

[R10] 正则匹配
来源：http://dali.wangshuangyany.cn/Article/details/gtxdyvzdvq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gtghzfklaf.html

[R11] case 多分支
来源：http://dali.hammf.cn/Article/details/gtyvlovvso.html

case "$1" in
来源：http://dali.ehwqpu.com/Article/details/gtqjeuwomh.html

start) echo "启动" ;;
来源：http://dali.snrcjt.cn/Article/details/gttdbjgvvy.html

stop)  echo "停止" ;;
来源：http://dali.316326.xyz/Article/details/gtdotdprqq.html

*)     echo "未知命令" ;;
来源：http://dali.aizwys.cn/Article/details/gtfpebzmoy.html

esac
来源：http://dali.tanke756.top/Article/details/gtnxnmeqke.html

[R12] for 遍历文件
来源：http://dali.cdnleiting.top/Article/details/gtrexcbmod.html

for f in *.txt; do echo "$f"; done
来源：http://dali.shanyushiyangkeji.top/Article/details/gtlufxvshy.html

[R13] for 计数循环
来源：http://dali.hfpthk.cn/Article/details/gtrpvxvcvh.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.shangyingyoupin.top/Article/details/gtxlaijunm.html

[R14] C 风格 for
来源：http://dali.hysaishi.cn/Article/details/gtcutkleuh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.tanke756.top/Article/details/gtpvzaxhdv.html

[R15] while 逐行读文件
来源：http://dali.shzxlz.cn/Article/details/gtaagwhdej.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.meibo888.top/Article/details/gtrbpirvwu.html

[R16] until 等待条件
来源：http://dali.chenjidiqi.icu/Article/details/gtapdyegbq.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.chenlongwang.top/Article/details/gtyzbizais.html

[R17] 数组定义与取值
来源：http://dali.iojbl.cn/Article/details/gtvvjsagpx.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.snrcjt.cn/Article/details/gtsyxdcqqa.html

[R18] 遍历数组
来源：http://dali.gotoacloud.top/Article/details/gtgrqrmwbh.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.yuxming.cn/Article/details/gtestyppzz.html

[R19] 数组长度
来源：http://dali.aizwys.cn/Article/details/gtmxcyacqc.html

echo "${#arr[@]}"
来源：http://dali.jqgufenzy.top/Article/details/gtmprtbwez.html

[R20] 关联数组（字典）
来源：http://dali.jlsjyb.cn/Article/details/gtwugnjdhr.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.tanke756.top/Article/details/gtqdxtzytn.html

[R21] 字符串长度
来源：http://dali.yuxming.cn/Article/details/gtlwkgamzs.html

echo "${#s}"
来源：http://dali.zdqjudy.top/Article/details/gtyrsosmtu.html

[R22] 截取子串
来源：http://dali.shanyushiyangkeji.top/Article/details/gthfvpplfw.html

echo "${s:0:5}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtvnqhinpl.html

[R23] 字符串替换
来源：http://dali.zhoulong.xyz/Article/details/gtuhdkcbom.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.birdmap.top/Article/details/gtkvwcoqew.html

[R24] 大小写转换
来源：http://dali.hnqzz.top/Article/details/gtegbdgaae.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.zhengqikj.top/Article/details/gtqfufzoqd.html

[R25] 去后缀 / 去前缀
来源：http://dali.chenlongwang.top/Article/details/gtbqiyfkfp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.c1oappe.top/Article/details/gtxkeitvuy.html

[R26] 命令替换
来源：http://dali.chenzaomai.com/Article/details/gtjonouqfl.html

now=$(date +%F); echo "$now"
来源：http://dali.jianghu66.top/Article/details/gtszohehka.html

[R27] 算术展开
来源：http://dali.cucudq.cn/Article/details/gtpuidftxq.html

echo $((1 + 2 * 3))
来源：http://dali.aizwys.cn/Article/details/gtjjxugusr.html

[R28] 浮点运算
来源：http://dali.shzxlz.cn/Article/details/gtwmnzauli.html

echo "scale=2; 10/3" | bc
来源：http://dali.aizwys.cn/Article/details/gtdrotbele.html

[R29] 定义函数
来源：http://dali.pengpengdd.cyou/Article/details/gtlznkywuv.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hywenlv.cn/Article/details/gtvnjzcfey.html

[R30] 函数返回状态码
来源：http://dali.pengpengdd.cyou/Article/details/gthquufvgt.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.ppjwa.cn/Article/details/gtektjriwl.html

[R31] 局部变量
来源：http://dali.vqdsnc.cn/Article/details/gtwxhvszvx.html

f() { local x=1; echo "$x"; }
来源：http://dali.dianchejie.cn/Article/details/gtpxtwnpza.html

[R32] 参数个数校验
来源：http://dali.yuxming.cn/Article/details/gtljqpcvyr.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.xinyue.icu/Article/details/gtrgnyhttg.html

[R33] 捕获错误并提示行号
来源：http://dali.tianlin.xyz/Article/details/gthfarbuxn.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hnxiangtu.top/Article/details/gtwgyejoxd.html

[R34] 退出时清理
来源：http://dali.yj20258.top/Article/details/gtjkqfvemz.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.vqdsnc.cn/Article/details/gtmokwlnaa.html

[R35] 后台执行并等待
来源：http://dali.xylfe.cn/Article/details/gtlvwhfnih.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.andypj.xyz/Article/details/gtxhsenweg.html

[R36] 并发执行多个任务
来源：http://dali.gogol.net.cn/Article/details/gtscycweys.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.gotoacloud.top/Article/details/gtmleuelnx.html

[R37] 把输出赋给变量
来源：http://dali.bjfxy.top/Article/details/gtpyizcxyl.html

files=$(ls -1)
来源：http://dali.pengpengdd.cyou/Article/details/gtnndwswla.html

[R38] 管道串联
来源：http://dali.hongshengwenyu.top/Article/details/gtpxsnctmr.html

cat a.txt | grep -i error | wc -l
来源：http://dali.bjfxy.top/Article/details/gtirxmhbgm.html

[R39] 重定向标准输出与错误
来源：http://dali.shuidangran.top/Article/details/gtoqkpzcum.html

cmd > out.log 2>&1
来源：http://dali.cheryme.top/Article/details/gttilfoblw.html

[R40] 追加写日志
来源：http://dali.quarkkingdee.top/Article/details/gtwsbruofh.html

echo "log" >> out.log
来源：http://dali.wangdashe.top/Article/details/gtmmoeazkp.html

[R41] 丢弃输出
来源：http://dali.haohaochexian.top/Article/details/gtwuffswww.html

cmd >/dev/null 2>&1
来源：http://dali.yongpay.top/Article/details/gtkjukkpxm.html

[R42] 输入重定向
来源：http://dali.shanyushiyangkeji.top/Article/details/gtutjhwijw.html

wc -l < a.txt
来源：http://dali.birdmap.top/Article/details/gtzvzepukj.html

[R43] 按名字查找文件
来源：http://dali.0kj1m.cn/Article/details/gtwcqeqnpt.html

find . -name "*.log" -type f
来源：http://dali.aizwys.cn/Article/details/gtzaohzbsy.html

[R44] 按修改时间查找
来源：http://dali.yj20258.top/Article/details/gtslgmfdqm.html

find . -mtime -7 -type f
来源：http://dali.xylfe.cn/Article/details/gtwtxxbqvo.html

[R45] 批量删除
来源：http://dali.hnxiangtu.top/Article/details/gtmwxugfrr.html

find . -name "*.tmp" -delete
来源：http://dali.nwbrower.top/Article/details/gtmkuiuhiw.html

[R46] 递归替换文件内容
来源：http://dali.zhiwuduotai.top/Article/details/gtxivfjgrw.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yuxming.cn/Article/details/gtfdywqzgs.html

[R47] sed 单行替换
来源：http://dali.haohaochexian.top/Article/details/gtaglvkwcp.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhoulong.xyz/Article/details/gtlgzszkwn.html

[R48] awk 取指定列
来源：http://dali.haohaochexian.top/Article/details/gttfwqwsfo.html

awk '{print $1, $3}' a.txt
来源：http://dali.meibo888.top/Article/details/gtnoiqciqx.html

[R49] awk 带条件
来源：http://dali.316326.xyz/Article/details/gtuvqabeyq.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.quarkkingdee.top/Article/details/gtiwvclfqp.html

[R50] awk 求和
来源：http://dali.yueranfly.top/Article/details/gtzsjafzzx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.gogol.net.cn/Article/details/gtketembio.html

[R51] 排序去重取前几
来源：http://dali.jqgfzy.top/Article/details/gtwglqrhnu.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.chenzaomai.com/Article/details/gtyqsqwnka.html

[R52] 统计行数
来源：http://dali.gogol.net.cn/Article/details/gtbraobnjf.html

wc -l a.txt
来源：http://dali.316326.xyz/Article/details/gtiriinrcp.html

[R53] 查看文件头与实时尾
来源：http://dali.fengsongda.top/Article/details/gtljfwgvfs.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.ybcxt.top/Article/details/gttosbksvb.html

[R54] 比较两个文件
来源：http://dali.jqgfzy.top/Article/details/gtozvljfwd.html

diff a.txt b.txt
来源：http://dali.yuxming.cn/Article/details/gtctxdklkd.html

[R55] 压缩与解压
来源：http://dali.pycfn.com/Article/details/gtilcrmeoy.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.gotoacloud.top/Article/details/gtejaeqlul.html

[R56] 远程拷贝
来源：http://dali.zhengqikj.top/Article/details/gtztsoevlk.html

scp file user@host:/path/
来源：http://dali.yj202588.top/Article/details/gthszacorf.html

[R57] 远程执行命令
来源：http://dali.meibo888.top/Article/details/gtysycjmyx.html

ssh user@host 'uptime'
来源：http://dali.shangyingyoupin.top/Article/details/gtgfzopmol.html

[R58] 下载文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtsqqgrqst.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.smart0.xyz/Article/details/gtmvvwiekv.html

[R59] 发 POST JSON
来源：http://dali.jinqigfzy.top/Article/details/gtztvxfnfi.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.jinghuilouyu.cn/Article/details/gteuncolup.html

[R60] 只看 HTTP 状态码
来源：http://dali.shanyushiyangtech.top/Article/details/gtsezhlmqc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.yangfankeji.com/Article/details/gtiwagrgqm.html

[R61] 磁盘占用
来源：http://dali.zhoulong.xyz/Article/details/gtdobxvbyv.html

df -h;  du -sh *
来源：http://dali.yj20258.top/Article/details/gtfxjozslr.html

[R62] 找最占空间的文件
来源：http://dali.chenlongwang.top/Article/details/gtsqpztaoe.html

du -ah . | sort -rh | head -10
来源：http://dali.nanxinkj.top/Article/details/gtenyyzzjx.html

[R63] 内存与进程
来源：http://dali.dashuyun.cn/Article/details/gtlldmhnrd.html

free -h;  ps aux | grep nginx
来源：http://dali.shangyingyoupin.top/Article/details/gtmhduvzoo.html

[R64] 结束进程
来源：http://dali.daxiang520.top/Article/details/gtltwqzsuc.html

kill -9 $(pgrep -f app.py)
来源：http://dali.shuidangran.top/Article/details/gtavcyfsnj.html

[R65] 查看端口占用
来源：http://dali.yonumen.top/Article/details/gtxwkrpiws.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.svipenyu.cn/Article/details/gtptuxpuzd.html

[R66] 定时任务
来源：http://dali.guowangkeji.top/Article/details/gteletenfq.html

crontab -e;  crontab -l
来源：http://dali.wangdashe.top/Article/details/gtwmtlrjig.html

[R67] 生成随机十六进制串
来源：http://dali.jinqigfzy.top/Article/details/gtxmzfalxl.html

openssl rand -hex 16
来源：http://dali.jinqigfzy.top/Article/details/gtdcussuiz.html

[R68] 计算文件校验值
来源：http://dali.kuanghao11.cn/Article/details/gtyjhajtti.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenzaomai.com/Article/details/gtidinrkue.html

[R69] 生成随机密码
来源：http://dali.yj20258.top/Article/details/gtpbevcvnb.html

head -c 16 /dev/urandom | base64
来源：http://dali.meibo888.top/Article/details/gtmxuaqeqr.html

[R70] 时间戳与互转
来源：http://dali.zycfv.cn/Article/details/gtezbolall.html

date +%s;  date -d @1700000000
来源：http://dali.cucudq.cn/Article/details/gtqrwnecww.html

[R71] 日期格式化
来源：http://dali.vqdsnc.cn/Article/details/gtjnrjdvxn.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hysaishi.cn/Article/details/gtnozuxyxw.html

[R72] 等待端口就绪
来源：http://dali.kuanghao11.cn/Article/details/gtocjsbkyq.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.pycfn.com/Article/details/gtxylfyspn.html

[R73] 分割大日志
来源：http://dali.sxryk.cn/Article/details/gtxcsgfdts.html

split -l 1000 big.log part_
来源：http://dali.jlsjyb.cn/Article/details/gtrncabsnj.html

[R74] 批量重命名
来源：http://dali.jinghuilouyu.cn/Article/details/gtygdblyxr.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.zhoulong.xyz/Article/details/gtksoypdgb.html

[R75] 导出环境变量
来源：http://dali.chenjidiqi.icu/Article/details/gtutqtgbky.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.shuidangran.top/Article/details/gteayhroiq.html

[R76] 使用临时文件
来源：http://dali.wangdashe.top/Article/details/gtyerukujr.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.guannengcc.top/Article/details/gtjxzflkeb.html

[R77] 读取用户输入
来源：http://dali.ehwqpu.com/Article/details/gttxikzuru.html


<!-- 参考信息 -->