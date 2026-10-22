代发 wailian999

[Q33] 多列分组
来源：http://dali.zhixingplan.top/Article/details/gtukfrehfw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.316326.xyz/Article/details/gtqznmqxcr.html

[Q34] 每组取第一条
来源：http://dali.chenzaomai.com/Article/details/gthyeetltc.html

SELECT * FROM (
来源：http://dali.316326.xyz/Article/details/gtapbqxrsg.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.fzhhl.top/Article/details/gtyzgpkseo.html

) t WHERE rn = 1;
来源：http://dali.sxryk.cn/Article/details/gtesdqrzdr.html

[Q35] 内连接
来源：http://dali.jianghu66.top/Article/details/gtafvtvgny.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.xuanzx.com/Article/details/gtlvfhaypv.html

[Q36] 左连接
来源：http://dali.zycfv.cn/Article/details/gtffchjfqr.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.xylfe.cn/Article/details/gtrsrqdyvo.html

[Q37] 右连接
来源：http://dali.zhengqikj.top/Article/details/gtzececffh.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.xuetiantiany.cn/Article/details/gtbmxwdomy.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.hammf.cn/Article/details/gtmwhdrvht.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.pycfn.com/Article/details/gtvrvwwpzl.html

[Q39] 自连接（查上下级）
来源：http://dali.yvedp.cn/Article/details/gtbqcdyxmh.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.snrcjt.cn/Article/details/gtmwkugpio.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.bjfxy.top/Article/details/gtiytzltxl.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.cashguo.top/Article/details/gtekldalgb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xuetiantiany.cn/Article/details/gtudtbnpfp.html

[Q41] 多表连接
来源：http://dali.birdmap.top/Article/details/gtwlssgoxq.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.dashuyun.cn/Article/details/gtnijkyxvp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yj20258888.top/Article/details/gtpnslmglp.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.chenzaomai.com/Article/details/gtwclktpzs.html

[Q42] 连接条件附加过滤
来源：http://dali.0kj1m.cn/Article/details/gtfccpqdvl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtvbufgigt.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.gaohongyu789.top/Article/details/gtoqihygqo.html

[Q43] 标量子查询
来源：http://dali.havefunace.top/Article/details/gttxiwtzyk.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.yvedp.cn/Article/details/gtlgpuyiee.html

[Q44] IN 子查询
来源：http://dali.shanyushiyangkeji.top/Article/details/gtctcpakur.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.guowangkeji.top/Article/details/gtgmcpvrnu.html

[Q45] EXISTS 判断存在
来源：http://dali.guowangkeji.top/Article/details/gtqbtrygrm.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.daria6918.cn/Article/details/gtghmccyhj.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.ydzc1.top/Article/details/gtlpwvgspa.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.aibaodan.cn/Article/details/gtrirezfeo.html

[Q47] 与平均值比较
来源：http://dali.yvedp.cn/Article/details/gtjflmvcso.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.havefunace.top/Article/details/gtemayeowf.html

[Q48] CTE 公用表表达式
来源：http://dali.jinqigufen.top/Article/details/gtckbbvfqg.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zhijiandao.cn/Article/details/gtzlkzupkt.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jiagoushi.top/Article/details/gtqeeisgdg.html

[Q49] 更新单行
来源：http://dali.snrcjt.cn/Article/details/gtxxttgmyt.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhengqikj.top/Article/details/gtgtzckgfn.html

[Q50] 批量更新
来源：http://dali.daria6918.cn/Article/details/gtwmnbkbna.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.xuetiantiany.cn/Article/details/gtokxilpsi.html

[Q51] 用子查询更新
来源：http://dali.jinghuilouyu.cn/Article/details/gtenymvbmi.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.jinghuilouyu.cn/Article/details/gtgwsgegnw.html

[Q52] 删除指定行
来源：http://dali.jiagoushi.top/Article/details/gtttxrrvib.html

DELETE FROM users WHERE id = 10;
来源：http://dali.aibaodan.cn/Article/details/gtfpwlnnwh.html

[Q53] 按条件删除
来源：http://dali.fzhhl.top/Article/details/gttboxrnxt.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.hywenlv.cn/Article/details/gteciwrybf.html

[Q54] 清空表
来源：http://dali.wangdashe.top/Article/details/gtjogdjnym.html

TRUNCATE TABLE logs;
来源：http://dali.zdqjudy.top/Article/details/gtvmjjxszu.html

[Q55] 排名（并列占位）
来源：http://dali.cqqwz.cn/Article/details/gtgyzmkrpu.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.smart0.xyz/Article/details/gtijbkdopc.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ivvv.top/Article/details/gtqgsjtsbj.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.tanke756.top/Article/details/gtecolgljy.html

[Q57] 行号
来源：http://dali.hywenlv.cn/Article/details/gtnooqiwhs.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xuanzx.com/Article/details/gtfdbnwclh.html

[Q58] 累计求和
来源：http://dali.feifeiyinyue.top/Article/details/gtehishwvp.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.xuetiantiany.cn/Article/details/gtevcaegpk.html

[Q59] 分组内累计
来源：http://dali.daxiang520.top/Article/details/gtycgwgqqu.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtjllpdzjd.html

[Q60] 取上一行 / 下一行
来源：http://dali.wangdashe.top/Article/details/gtazhqfbtn.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.yongpay.top/Article/details/gtlmyksvvd.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jinghuilouyu.cn/Article/details/gtkoibhedc.html

[Q61] 移动平均
来源：http://dali.wangshuangyany.cn/Article/details/gtxubokqug.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.pycfn.com/Article/details/gtwjvavbhl.html

[Q62] 分组占比
来源：http://dali.xingfuxueyuan.xyz/Article/details/gthhxwgcvi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.birdmap.top/Article/details/gthvsyqpmq.html

[Q63] 开启事务
来源：http://dali.guannengcc.top/Article/details/gtwsivczhn.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.316326.xyz/Article/details/gthxnnbycb.html

[Q64] 提交事务
来源：http://dali.birdmap.top/Article/details/gthrsslvfh.html

COMMIT;
来源：http://dali.shanyushiyangtech.top/Article/details/gtjyoancrl.html

[Q65] 回滚事务
来源：http://dali.sxryk.cn/Article/details/gtiwqhmnup.html

ROLLBACK;
来源：http://dali.iojbl.cn/Article/details/gtkbzodltq.html

[Q66] 行锁查询
来源：http://dali.nwbrower.top/Article/details/gtmyoedkhq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.shangyingyoupin.top/Article/details/gtknpznyua.html

[Q67] 设置隔离级别
来源：http://dali.cheryme.top/Article/details/gthqwapmgo.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.jinqigfzy.top/Article/details/gthzqrunts.html

[Q68] 保存点
来源：http://dali.cashguo.top/Article/details/gturuhlivy.html

SAVEPOINT sp1;
来源：http://dali.feifeiyinyue.top/Article/details/gtdseymvwg.html

ROLLBACK TO sp1;
来源：http://dali.sxryk.cn/Article/details/gttzjaonad.html

[Q69] 查看执行计划
来源：http://dali.316326.xyz/Article/details/gtogpzlahh.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.nanxinkj.top/Article/details/gthtdorkvs.html

[Q70] 更新统计信息
来源：http://dali.cdnleiting.top/Article/details/gtfruivzjq.html

ANALYZE TABLE users;
来源：http://dali.kuanghao11.cn/Article/details/gtzsxrgywu.html

[Q71] 查看建表语句
来源：http://dali.nanxuanxn.top/Article/details/gtjfwzhrmn.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ehwqpu.com/Article/details/gtpkbysdvz.html

[Q72] 查看索引
来源：http://dali.jqgfzy.top/Article/details/gtmelukbwf.html

SHOW INDEX FROM users;
来源：http://dali.tanke756.top/Article/details/gttcjqwncv.html

[Q73] 查看表状态
来源：http://dali.mhx1999.top/Article/details/gtuqreyoan.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.smart0.xyz/Article/details/gtrqcaprgm.html

[Q74] 强制使用索引
来源：http://dali.jqgfzy.top/Article/details/gtvaeyaexj.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jqgfzy.top/Article/details/gtcduqsdny.html

[Q75] 日期格式化
来源：http://dali.xuetiantiany.cn/Article/details/gtnugdfcoz.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.jqgfzy.top/Article/details/gtlcjbksll.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhaomingkeji.xyz/Article/details/gtciuzmqhs.html

[Q76] 按天统计
来源：http://dali.nanxuanxn.top/Article/details/gtxvmxrtka.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.tianlin.xyz/Article/details/gtyzgockqr.html

[Q77] 时间加减
来源：http://dali.zhaomingkeji.xyz/Article/details/gtixcbkbyq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.zhixingplan.top/Article/details/gtkmmsiruc.html

[Q78] 当前时间
来源：http://dali.xziqi.cn/Article/details/gtsyfrlstf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xuanzx.com/Article/details/gtsmnfwltt.html

[Q79] 字符串拼接
来源：http://dali.snrcjt.cn/Article/details/gtkzkfiptf.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.jianghu66.top/Article/details/gtgwdpbwil.html

[Q80] 字符串截取
来源：http://dali.zycfv.cn/Article/details/gtefvcapov.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtqgvbpfph.html

[Q81] 字符串替换
来源：http://dali.meibo888.top/Article/details/gtsfritkfp.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.c1oappe.top/Article/details/gtthnkuziv.html

[Q82] 字符长度与字节长度
来源：http://dali.cqqwz.cn/Article/details/gtashsqlfi.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtlhxmujnx.html

[Q83] 大小写转换
来源：http://dali.zdqjudy.top/Article/details/gtljykowht.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtkdnhbppb.html

[Q84] 去除首尾空格
来源：http://dali.tanke756.top/Article/details/gthjcsnatn.html

SELECT TRIM(name) FROM users;
来源：http://dali.zycfv.cn/Article/details/gtglaoxgzd.html

[Q85] 数值取整
来源：http://dali.zycfv.cn/Article/details/gttwrvhwpu.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.aizwys.cn/Article/details/gtwbpdwshp.html

[Q86] 读取 JSON 字段
来源：http://dali.yj202588.top/Article/details/gteixfbilg.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.gzhubu.top/Article/details/gtfjbkvhym.html

[Q87] JSON 字段做条件
来源：http://dali.xuanzx.com/Article/details/gtgfchhctk.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.c1oappe.top/Article/details/gtmsgohxkn.html

[Q88] 行转列（条件聚合）
来源：http://dali.pengpengdd.cyou/Article/details/gtvibahuym.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtrwqsvpmm.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.cashguo.top/Article/details/gthdhjxxof.html

[Q89] 判断表是否存在
来源：http://dali.gaohongyu789.top/Article/details/gtpjqmgmor.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.aizwys.cn/Article/details/gtnvloxcan.html

[Q90] 生成序号列
来源：http://dali.yanxiufei.cn/Article/details/gtvzmweqiy.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.svipenyu.cn/Article/details/gtitbaulfm.html

================================================================================
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtctqzclcl.html

R. Bash 专题
来源：http://dali.jiagoushi.top/Article/details/gtumnmmtci.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtyckfwgeg.html

[R01] shebang 与严格模式
来源：http://dali.tianlin.xyz/Article/details/gtezxbosql.html

#!/usr/bin/env bash
来源：http://dali.xuetiantiany.cn/Article/details/gtaxexzmcp.html

set -euo pipefail
来源：http://dali.guowangkeji.top/Article/details/gturoybegq.html

[R02] 变量赋值与使用
来源：http://dali.yanxiufei.cn/Article/details/gtndkxfttu.html

name="Tom"; echo "$name"
来源：http://dali.316326.xyz/Article/details/gtdiadplyj.html

[R03] 只读变量
来源：http://dali.snrcjt.cn/Article/details/gtdzmlymew.html

readonly PI=3.14
来源：http://dali.redwolf501.top/Article/details/gtpjatzwdf.html

[R04] 位置参数
来源：http://dali.haohaochexian.top/Article/details/gtlsvaaknb.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.zhiwuduotai.top/Article/details/gtwunocyvx.html

[R05] 参数默认值
来源：http://dali.yj20258.top/Article/details/gtusqyqjvy.html

name="${1:-default}"
来源：http://dali.0kj1m.cn/Article/details/gtdvjohkuz.html

[R06] 判断命令是否存在
来源：http://dali.ybcxt.top/Article/details/gteteokgjg.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.wangdashe.top/Article/details/gttblqpjvm.html

[R07] if 判断文件
来源：http://dali.cqqwz.cn/Article/details/gtcmvcpgqp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.tanke756.top/Article/details/gtwifpcdrt.html

[R08] 数值比较
来源：http://dali.jinqigfzy.top/Article/details/gtokzwcsml.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.0kj1m.cn/Article/details/gtjfpuyddx.html

[R09] 字符串比较
来源：http://dali.cashguo.top/Article/details/gtiglfosbv.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.birdmap.top/Article/details/gtgxewunzz.html

[R10] 正则匹配
来源：http://dali.nanxuanxn.top/Article/details/gtfvnrplmc.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.hnxiangtu.top/Article/details/gtcssuovvd.html

[R11] case 多分支
来源：http://dali.sweek.top/Article/details/gtgngwfwkb.html

case "$1" in
来源：http://dali.nanxinkj.top/Article/details/gtquutdscs.html

start) echo "启动" ;;
来源：http://dali.gogol.net.cn/Article/details/gtzxgvcbew.html

stop)  echo "停止" ;;
来源：http://dali.ybcxt.top/Article/details/gtqxinorrw.html

*)     echo "未知命令" ;;
来源：http://dali.tianlin.xyz/Article/details/gtscixlhvi.html

esac
来源：http://dali.daria6918.cn/Article/details/gtzfaaqdky.html

[R12] for 遍历文件
来源：http://dali.cqqwz.cn/Article/details/gtkffixfqi.html

for f in *.txt; do echo "$f"; done
来源：http://dali.nanxinkj.top/Article/details/gtbmbhufdl.html

[R13] for 计数循环
来源：http://dali.xuetiantiany.cn/Article/details/gtlhdtjzcr.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.wangshuangyany.cn/Article/details/gtkexwcbgh.html

[R14] C 风格 for
来源：http://dali.nwbrower.top/Article/details/gtxrssokbd.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.yj20258.top/Article/details/gthovkfjsm.html

[R15] while 逐行读文件
来源：http://dali.yj20258888.top/Article/details/gtesjehinb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.tian-w.cn/Article/details/gthpsbavqx.html

[R16] until 等待条件
来源：http://dali.aizwys.cn/Article/details/gtdsmlvehh.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.quarkkingdee.top/Article/details/gtutmtavys.html

[R17] 数组定义与取值
来源：http://dali.ppjwa.cn/Article/details/gtjellwumu.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.jiagoushi.top/Article/details/gtskvbkmwv.html

[R18] 遍历数组
来源：http://dali.cqqwz.cn/Article/details/gtnzlygcaq.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.ivvv.top/Article/details/gtfpdovkrx.html

[R19] 数组长度
来源：http://dali.iojbl.cn/Article/details/gtwafrwczg.html

echo "${#arr[@]}"
来源：http://dali.yongpay.top/Article/details/gtvhewluve.html

[R20] 关联数组（字典）
来源：http://dali.sufxvd.cn/Article/details/gthhkraybb.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.shangyingyoupin.top/Article/details/gtmuarblxf.html

[R21] 字符串长度
来源：http://dali.cqqwz.cn/Article/details/gtlvwxqbzv.html

echo "${#s}"
来源：http://dali.yvedp.cn/Article/details/gtoagcqxrc.html

[R22] 截取子串
来源：http://dali.yonumen.top/Article/details/gtbcksqgwg.html

echo "${s:0:5}"
来源：http://dali.redwolf501.top/Article/details/gtbjlienoq.html

[R23] 字符串替换
来源：http://dali.jlsjyb.cn/Article/details/gtvxeztthw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhoulong.xyz/Article/details/gtbcqwoudz.html

[R24] 大小写转换
来源：http://dali.jyoumei.cn/Article/details/gtmkvllsth.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.redwolf501.top/Article/details/gtvghpouon.html

[R25] 去后缀 / 去前缀
来源：http://dali.jqgufenzy.top/Article/details/gttishsibw.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.birdmap.top/Article/details/gtbfdftefm.html

[R26] 命令替换
来源：http://dali.andypj.xyz/Article/details/gtgphqhyak.html

now=$(date +%F); echo "$now"
来源：http://dali.jinqigufen.top/Article/details/gtmwuicneh.html

[R27] 算术展开
来源：http://dali.aibaodan.cn/Article/details/gtivpqdeud.html

echo $((1 + 2 * 3))
来源：http://dali.nanxuanxn.top/Article/details/gtfzabxmbq.html

[R28] 浮点运算
来源：http://dali.yanxiufei.cn/Article/details/gtpgjairna.html

echo "scale=2; 10/3" | bc
来源：http://dali.xylfe.cn/Article/details/gtsvrpnbxt.html

[R29] 定义函数
来源：http://dali.sxryk.cn/Article/details/gtiedyutaa.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yj20258888.top/Article/details/gtqyyocwuu.html

[R30] 函数返回状态码
来源：http://dali.yangfankeji.com/Article/details/gtirgoeynl.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.nanxuanxn.top/Article/details/gtgzzwmdfc.html

[R31] 局部变量
来源：http://dali.birdmap.top/Article/details/gtctltictl.html

f() { local x=1; echo "$x"; }
来源：http://dali.jianghu66.top/Article/details/gtteetvqln.html

[R32] 参数个数校验
来源：http://dali.shuidangran.top/Article/details/gtevgcmqcg.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.jlsjyb.cn/Article/details/gthxqgpxgb.html

[R33] 捕获错误并提示行号
来源：http://dali.shzxlz.cn/Article/details/gtvlwkdaoz.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.daxiang520.top/Article/details/gtklhmbllw.html

[R34] 退出时清理
来源：http://dali.haohaochexian.top/Article/details/gtfrxpxtdx.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.pycfn.com/Article/details/gttvwdjyru.html

[R35] 后台执行并等待
来源：http://dali.guannengcc.top/Article/details/gtzospalsm.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.gotoacloud.top/Article/details/gtzdujyklc.html

[R36] 并发执行多个任务
来源：http://dali.jiagoushi.top/Article/details/gtkernfsjz.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.zycfv.cn/Article/details/gtuvohirvk.html

[R37] 把输出赋给变量
来源：http://dali.cucudq.cn/Article/details/gtyqkcukpj.html

files=$(ls -1)
来源：http://dali.sysykeji.top/Article/details/gtbvbtkfew.html

[R38] 管道串联
来源：http://dali.dashuyun.cn/Article/details/gtzflclcbv.html

cat a.txt | grep -i error | wc -l
来源：http://dali.shzxlz.cn/Article/details/gtommmhxvf.html

[R39] 重定向标准输出与错误
来源：http://dali.jinqigufen.top/Article/details/gtulcgqztz.html

cmd > out.log 2>&1
来源：http://dali.iojbl.cn/Article/details/gtaopvjans.html

[R40] 追加写日志
来源：http://dali.shuidangran.top/Article/details/gtypmlerux.html

echo "log" >> out.log
来源：http://dali.yongpay.top/Article/details/gtquddjrfq.html

[R41] 丢弃输出
来源：http://dali.xuetiantiany.cn/Article/details/gtsxylhekj.html

cmd >/dev/null 2>&1
来源：http://dali.chenjidiqi.icu/Article/details/gtsmubsheh.html

[R42] 输入重定向
来源：http://dali.yuanzhike.top/Article/details/gtbcovnwor.html

wc -l < a.txt
来源：http://dali.pengpengdd.cyou/Article/details/gtnwptnuxa.html

[R43] 按名字查找文件
来源：http://dali.zhixingplan.top/Article/details/gtpofrbuzu.html

find . -name "*.log" -type f
来源：http://dali.shangyingyoupin.top/Article/details/gtglfrmkeb.html

[R44] 按修改时间查找
来源：http://dali.nwbrower.top/Article/details/gtvackzvjg.html

find . -mtime -7 -type f
来源：http://dali.hongshengwenyu.top/Article/details/gtwjpoxudm.html

[R45] 批量删除
来源：http://dali.gotoacloud.top/Article/details/gtssdhvayf.html

find . -name "*.tmp" -delete
来源：http://dali.gaohongyu789.top/Article/details/gtctddzkkh.html

[R46] 递归替换文件内容
来源：http://dali.xziqi.cn/Article/details/gtrnhvonab.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.tian-w.cn/Article/details/gtgkxvahuy.html

[R47] sed 单行替换
来源：http://dali.wangdashe.top/Article/details/gtlzhxknih.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.aizwys.cn/Article/details/gtheytfmwc.html

[R48] awk 取指定列
来源：http://dali.zhengqikj.top/Article/details/gtmsopcxtn.html

awk '{print $1, $3}' a.txt
来源：http://dali.yvedp.cn/Article/details/gtacwydrsv.html

[R49] awk 带条件
来源：http://dali.0kj1m.cn/Article/details/gterkdmmdb.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.cheryme.top/Article/details/gtgoolujft.html

[R50] awk 求和
来源：http://dali.chenjidiqi.icu/Article/details/gtlzuseqiu.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.fzhhl.top/Article/details/gtcbwzbhhu.html

[R51] 排序去重取前几
来源：http://dali.jyoumei.cn/Article/details/gtfcosxwss.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.zhixingplan.top/Article/details/gtfrvgfonp.html

[R52] 统计行数
来源：http://dali.mhx1999.top/Article/details/gtshxiiexk.html

wc -l a.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtnwapdcln.html

[R53] 查看文件头与实时尾
来源：http://dali.guowangkeji.top/Article/details/gtvcaxeydu.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.birdmap.top/Article/details/gtgnysqrnp.html

[R54] 比较两个文件
来源：http://dali.xziqi.cn/Article/details/gtypjluhzg.html

diff a.txt b.txt
来源：http://dali.zycfv.cn/Article/details/gtuscepnmt.html

[R55] 压缩与解压
来源：http://dali.zycfv.cn/Article/details/gtxqunuqls.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.nanxinkj.top/Article/details/gtbgowtrcv.html

[R56] 远程拷贝
来源：http://dali.cheryme.top/Article/details/gteijhmhyb.html

scp file user@host:/path/
来源：http://dali.zhiwuduotai.top/Article/details/gtozhbkuzj.html

[R57] 远程执行命令
来源：http://dali.hammf.cn/Article/details/gtoazeitqb.html

ssh user@host 'uptime'
来源：http://dali.jinqigfzy.top/Article/details/gtollxirtx.html

[R58] 下载文件
来源：http://dali.ydzc1.top/Article/details/gtehqqufdd.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.haohaochexian.top/Article/details/gtoutprsyj.html

[R59] 发 POST JSON
来源：http://dali.pycfn.com/Article/details/gteaidizkf.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhijiandao.cn/Article/details/gtdysojflq.html

[R60] 只看 HTTP 状态码
来源：http://dali.cashguo.top/Article/details/gtbtypdqts.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.zhengqikj.top/Article/details/gtuzxyjbpq.html

[R61] 磁盘占用
来源：http://dali.vqdsnc.cn/Article/details/gtdkcdvklc.html

df -h;  du -sh *
来源：http://dali.yongpay.top/Article/details/gtyzlbkcip.html

[R62] 找最占空间的文件
来源：http://dali.bjfxy.top/Article/details/gtyplxpapv.html

du -ah . | sort -rh | head -10
来源：http://dali.svipenyu.cn/Article/details/gtzsctmbmv.html

[R63] 内存与进程
来源：http://dali.hywenlv.cn/Article/details/gtiryiieev.html

free -h;  ps aux | grep nginx
来源：http://dali.gogol.net.cn/Article/details/gtdtfumivw.html

[R64] 结束进程
来源：http://dali.yj20258.top/Article/details/gtijhyvhiy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.hysaishi.cn/Article/details/gtnwuilxkx.html

[R65] 查看端口占用
来源：http://dali.svipenyu.cn/Article/details/gtdkiymdls.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yueranfly.top/Article/details/gtudzcdofb.html

[R66] 定时任务
来源：http://dali.zhengqikj.top/Article/details/gtjyowvbuw.html

crontab -e;  crontab -l
来源：http://dali.gaohongyu789.top/Article/details/gtsevurjic.html

[R67] 生成随机十六进制串
来源：http://dali.yj20258.top/Article/details/gtzvexgrrm.html

openssl rand -hex 16
来源：http://dali.xylfe.cn/Article/details/gtqxngdruz.html

[R68] 计算文件校验值
来源：http://dali.yj20258.top/Article/details/gtikprligt.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.snrcjt.cn/Article/details/gtkuttrmyr.html

[R69] 生成随机密码
来源：http://dali.gotoacloud.top/Article/details/gtmtsztzwm.html

head -c 16 /dev/urandom | base64
来源：http://dali.aizwys.cn/Article/details/gtwqxckhgi.html

[R70] 时间戳与互转
来源：http://dali.hongshengwenyu.top/Article/details/gtopqqkaiv.html

date +%s;  date -d @1700000000
来源：http://dali.ivvv.top/Article/details/gtmhcffkzf.html

[R71] 日期格式化
来源：http://dali.cdnleiting.top/Article/details/gtxrazhlki.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.xylfe.cn/Article/details/gtoxyuyhsb.html

[R72] 等待端口就绪
来源：http://dali.zhaomingkeji.xyz/Article/details/gtssabhjhu.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.iojbl.cn/Article/details/gtutldktyb.html

[R73] 分割大日志
来源：http://dali.mhx1999.top/Article/details/gtquhwwumz.html

split -l 1000 big.log part_
来源：http://dali.feifeiyinyue.top/Article/details/gtwhslbkzd.html

[R74] 批量重命名
来源：http://dali.jyoumei.cn/Article/details/gtmxlhrnfo.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.snrcjt.cn/Article/details/gtonikkwqn.html

[R75] 导出环境变量
来源：http://dali.jiagoushi.top/Article/details/gtlcdrxkji.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xylfe.cn/Article/details/gtjbnfghkp.html

[R76] 使用临时文件
来源：http://dali.guannengcc.top/Article/details/gtajzdeveh.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yuxming.cn/Article/details/gtmqwnxefl.html

[R77] 读取用户输入
来源：http://dali.hysaishi.cn/Article/details/gtcbnomhyp.html

read -rp "请输入: " ans
来源：http://dali.ybcxt.top/Article/details/gtkszumuvw.html

[R78] 交互式菜单
来源：http://dali.kuanghao11.cn/Article/details/gtfajaemfb.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.daria6918.cn/Article/details/gtrpqrkmtv.html

[R79] 解析命令行选项
来源：http://dali.yuxming.cn/Article/details/gtlghpgoyc.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.wangshuangyany.cn/Article/details/gtkwuiflci.html

[R80] 查看脚本执行耗时
来源：http://dali.shanyushiyangtech.top/Article/details/gtfdjvefvb.html

time ./run.sh
来源：http://dali.yueranfly.top/Article/details/gtfhxngdxi.html

================================================================================
来源：http://dali.fzhhl.top/Article/details/gtyvqpbjrv.html

S. C / C++ 专题
来源：http://dali.havefunace.top/Article/details/gtlhvmbxrr.html

================================================================================
来源：http://dali.xylfe.cn/Article/details/gtaysroaob.html

[S01] C：Hello World
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwdjbaptd.html

#include <stdio.h>
来源：http://dali.jinqigfzy.top/Article/details/gtkxdhajno.html


<!-- 参考信息 -->