代发 wailian999

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.wangdashe.top/Article/details/gtkjushtxo.html

[Q32] 分组拼接字符串
来源：http://dali.nanxinkj.top/Article/details/gtrysateoq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.haohaochexian.top/Article/details/gttidvviyw.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yongpay.top/Article/details/gtwpkrhzki.html

[Q33] 多列分组
来源：http://dali.shanyushiyangtech.top/Article/details/gtgpbdhgrw.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.yanxiufei.cn/Article/details/gtpjvgakhn.html

[Q34] 每组取第一条
来源：http://dali.zhijiandao.cn/Article/details/gtdxpjabxo.html

SELECT * FROM (
来源：http://dali.hnqzz.top/Article/details/gtlyslkpxx.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtoxdmlrck.html

) t WHERE rn = 1;
来源：http://dali.yuxming.cn/Article/details/gtldguvuth.html

[Q35] 内连接
来源：http://dali.xuetiantiany.cn/Article/details/gtpnzqyplu.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.sweek.top/Article/details/gtquvsvmrr.html

[Q36] 左连接
来源：http://dali.shuidangran.top/Article/details/gtnawmtvci.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zycfv.cn/Article/details/gtwazeekne.html

[Q37] 右连接
来源：http://dali.zhixingplan.top/Article/details/gtjvcziuce.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.dianchejie.cn/Article/details/gtbepztbfm.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ybcxt.top/Article/details/gtewnrlqwd.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hnqzz.top/Article/details/gtcdvydyth.html

[Q39] 自连接（查上下级）
来源：http://dali.jlsjyb.cn/Article/details/gturteqjna.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.quarkkingdee.top/Article/details/gtkvufbrqu.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.wangdashe.top/Article/details/gtlznuqnjl.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.hysaishi.cn/Article/details/gtmxkkvkob.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.wangshuangyany.cn/Article/details/gtzzynsxeq.html

[Q41] 多表连接
来源：http://dali.zycfv.cn/Article/details/gtbhotobqh.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hysaishi.cn/Article/details/gtbjivcbho.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shangyingyoupin.top/Article/details/gtgknsnvzf.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.wangshuangyany.cn/Article/details/gtjlgmffmp.html

[Q42] 连接条件附加过滤
来源：http://dali.andypj.xyz/Article/details/gtmthiufsx.html

SELECT u.name, o.amount FROM users u
来源：http://dali.9152youxi.cn/Article/details/gtxhxflaqw.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.pengpengdd.cyou/Article/details/gtdybuwxoa.html

[Q43] 标量子查询
来源：http://dali.daxiang520.top/Article/details/gtkntqogtd.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.jianghu66.top/Article/details/gtsnracdyn.html

[Q44] IN 子查询
来源：http://dali.xuanzx.com/Article/details/gtnizxeqzu.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yuanzhike.top/Article/details/gtfvuybrtq.html

[Q45] EXISTS 判断存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gtpguqiugp.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.yj202588.top/Article/details/gtfwmgmaxn.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.feifeiyinyue.top/Article/details/gtlhzogbrz.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jianghu66.top/Article/details/gtlpkvzhtt.html

[Q47] 与平均值比较
来源：http://dali.jinqigfzy.top/Article/details/gtzplmtisy.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.zhixingplan.top/Article/details/gtoejjyktn.html

[Q48] CTE 公用表表达式
来源：http://dali.kuanghao11.cn/Article/details/gtmfbwmqcx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.aibaodan.cn/Article/details/gthgomzhly.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.jlsjyb.cn/Article/details/gtxlkcffew.html

[Q49] 更新单行
来源：http://dali.ppjwa.cn/Article/details/gtpxnxaibg.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.xziqi.cn/Article/details/gtxkdqvnyh.html

[Q50] 批量更新
来源：http://dali.yj20258.top/Article/details/gtwidroxkq.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.fzhhl.top/Article/details/gtcntejewi.html

[Q51] 用子查询更新
来源：http://dali.jinqigfzy.top/Article/details/gtszhzmmmz.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.xinyue.icu/Article/details/gtxclrpabu.html

[Q52] 删除指定行
来源：http://dali.9152youxi.cn/Article/details/gtygupaxwq.html

DELETE FROM users WHERE id = 10;
来源：http://dali.pengpengdd.cyou/Article/details/gtpjquepez.html

[Q53] 按条件删除
来源：http://dali.yj202588.top/Article/details/gtuwsatzlp.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.wangshuangyany.cn/Article/details/gtmsryolbr.html

[Q54] 清空表
来源：http://dali.cdnleiting.top/Article/details/gtdfmlamcg.html

TRUNCATE TABLE logs;
来源：http://dali.yj20258888.top/Article/details/gtacvzuvmr.html

[Q55] 排名（并列占位）
来源：http://dali.jinghuilouyu.cn/Article/details/gtvoqpbnnh.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.gaohongyu789.top/Article/details/gtfkarryrb.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yj20258.top/Article/details/gtiwwyvqce.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shuidangran.top/Article/details/gtoclechgs.html

[Q57] 行号
来源：http://dali.yongpay.top/Article/details/gtxuougcqe.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.jqgufenzy.top/Article/details/gtifcsdavm.html

[Q58] 累计求和
来源：http://dali.hnqzz.top/Article/details/gtlhhofrix.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.gaohongyu789.top/Article/details/gtqhhoesdf.html

[Q59] 分组内累计
来源：http://dali.pengpengdd.cyou/Article/details/gtxjfvsebn.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.fengsongda.top/Article/details/gtleupryqz.html

[Q60] 取上一行 / 下一行
来源：http://dali.0kj1m.cn/Article/details/gtqbkwcpna.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.fengsongda.top/Article/details/gttwjpfbri.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtcgshtfpm.html

[Q61] 移动平均
来源：http://dali.quarkkingdee.top/Article/details/gtqtnvglyj.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.ivvv.top/Article/details/gtvtgmvlee.html

[Q62] 分组占比
来源：http://dali.ivvv.top/Article/details/gtzxwnrswi.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.daxiang520.top/Article/details/gtunttdutj.html

[Q63] 开启事务
来源：http://dali.pengpengdd.cyou/Article/details/gtnlpaqxwt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.xinyue.icu/Article/details/gtwayboyua.html

[Q64] 提交事务
来源：http://dali.yuanzhike.top/Article/details/gtxlnklogj.html

COMMIT;
来源：http://dali.kuanghao11.cn/Article/details/gtijhcjtyl.html

[Q65] 回滚事务
来源：http://dali.shzxlz.cn/Article/details/gtdzrjboot.html

ROLLBACK;
来源：http://dali.tianlin.xyz/Article/details/gtqceiumjh.html

[Q66] 行锁查询
来源：http://dali.yuxming.cn/Article/details/gtdeyewnhi.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.nwbrower.top/Article/details/gtemqmzbwi.html

[Q67] 设置隔离级别
来源：http://dali.mhx1999.top/Article/details/gtfrqjujhf.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.xuetiantiany.cn/Article/details/gtucarxrai.html

[Q68] 保存点
来源：http://dali.dianchejie.cn/Article/details/gttsbfuakn.html

SAVEPOINT sp1;
来源：http://dali.hnqzz.top/Article/details/gttpyndepc.html

ROLLBACK TO sp1;
来源：http://dali.guowangkeji.top/Article/details/gtcanzqcjm.html

[Q69] 查看执行计划
来源：http://dali.zhengqikj.top/Article/details/gtzpyqurij.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.tianlin.xyz/Article/details/gtiiwxmoog.html

[Q70] 更新统计信息
来源：http://dali.jyoumei.cn/Article/details/gtdehkxnhw.html

ANALYZE TABLE users;
来源：http://dali.ybcxt.top/Article/details/gthnusakhd.html

[Q71] 查看建表语句
来源：http://dali.zhixingplan.top/Article/details/gthvkxdusf.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cucudq.cn/Article/details/gthvgvlfam.html

[Q72] 查看索引
来源：http://dali.aibaodan.cn/Article/details/gtwhocngea.html

SHOW INDEX FROM users;
来源：http://dali.tanke756.top/Article/details/gttjbuojsk.html

[Q73] 查看表状态
来源：http://dali.dashuyun.cn/Article/details/gtjxsdtucd.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.zhoulong.xyz/Article/details/gthnhlxpcj.html

[Q74] 强制使用索引
来源：http://dali.quarkkingdee.top/Article/details/gtitsshkyy.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtaaniuwoj.html

[Q75] 日期格式化
来源：http://dali.jyoumei.cn/Article/details/gtsqefxkpf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.guannengcc.top/Article/details/gtqebvicwc.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.9152youxi.cn/Article/details/gtywhjnwrf.html

[Q76] 按天统计
来源：http://dali.meibo888.top/Article/details/gtnuxapyqs.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.xuetiantiany.cn/Article/details/gtpwrrqfwz.html

[Q77] 时间加减
来源：http://dali.svipenyu.cn/Article/details/gtxydulnyz.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.cucudq.cn/Article/details/gtssrhxwxn.html

[Q78] 当前时间
来源：http://dali.andypj.xyz/Article/details/gtmqsrkxcq.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.yj20258.top/Article/details/gtjpsuboxb.html

[Q79] 字符串拼接
来源：http://dali.xuetiantiany.cn/Article/details/gtuauvmzae.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.smart0.xyz/Article/details/gtpeqkquxj.html

[Q80] 字符串截取
来源：http://dali.ybcxt.top/Article/details/gtfvfytufs.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtoafpezij.html

[Q81] 字符串替换
来源：http://dali.sweek.top/Article/details/gtwvdoxkor.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.gaohongyu789.top/Article/details/gtyjfxohfw.html

[Q82] 字符长度与字节长度
来源：http://dali.xziqi.cn/Article/details/gtmdozdfsv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtkistbohk.html

[Q83] 大小写转换
来源：http://dali.hysaishi.cn/Article/details/gtropxqlhf.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmuacncif.html

[Q84] 去除首尾空格
来源：http://dali.hysaishi.cn/Article/details/gtedtshodr.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtjmvlyoxf.html

[Q85] 数值取整
来源：http://dali.dashuyun.cn/Article/details/gtifqqksik.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.smart0.xyz/Article/details/gtnflxxkpx.html

[Q86] 读取 JSON 字段
来源：http://dali.ydzc1.top/Article/details/gtlpcaupmv.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.dianchejie.cn/Article/details/gtkcnysrym.html

[Q87] JSON 字段做条件
来源：http://dali.fzhhl.top/Article/details/gtmroxgeix.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.hywenlv.cn/Article/details/gtharbubwe.html

[Q88] 行转列（条件聚合）
来源：http://dali.yonumen.top/Article/details/gtmrvjwvji.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yueranfly.top/Article/details/gtypicvrme.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.feifeiyinyue.top/Article/details/gteqrxbobo.html

[Q89] 判断表是否存在
来源：http://dali.quarkkingdee.top/Article/details/gtlkfsolja.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.yongpay.top/Article/details/gtmzkiivtq.html

[Q90] 生成序号列
来源：http://dali.hnxiangtu.top/Article/details/gtnbvxfhld.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhijiandao.cn/Article/details/gttbirtxdn.html

================================================================================
来源：http://dali.yuxming.cn/Article/details/gtgtxrhety.html

R. Bash 专题
来源：http://dali.zhaomingkeji.xyz/Article/details/gtixymrdow.html

================================================================================
来源：http://dali.meibo888.top/Article/details/gtnkyrpfaf.html

[R01] shebang 与严格模式
来源：http://dali.kuanghao11.cn/Article/details/gtdrmnmceg.html

#!/usr/bin/env bash
来源：http://dali.yonumen.top/Article/details/gttxvelhcj.html

set -euo pipefail
来源：http://dali.tian-w.cn/Article/details/gtldnuospk.html

[R02] 变量赋值与使用
来源：http://dali.zhengqikj.top/Article/details/gtxjypjsay.html

name="Tom"; echo "$name"
来源：http://dali.hywenlv.cn/Article/details/gtqrpkmvgh.html

[R03] 只读变量
来源：http://dali.yuanzhike.top/Article/details/gtfijnhgjq.html

readonly PI=3.14
来源：http://dali.andypj.xyz/Article/details/gtnjmpahhv.html

[R04] 位置参数
来源：http://dali.feifeiyinyue.top/Article/details/gtrjxxywss.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.jqgufenzy.top/Article/details/gtougpefax.html

[R05] 参数默认值
来源：http://dali.zdqjudy.top/Article/details/gtkcjiwtrp.html

name="${1:-default}"
来源：http://dali.yj202588.top/Article/details/gtkatadlau.html

[R06] 判断命令是否存在
来源：http://dali.iojbl.cn/Article/details/gtpxsqazlv.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.iojbl.cn/Article/details/gtlglkurmr.html

[R07] if 判断文件
来源：http://dali.meibo888.top/Article/details/gtigermlfx.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.redwolf501.top/Article/details/gtzllydfxl.html

[R08] 数值比较
来源：http://dali.snrcjt.cn/Article/details/gtutdiwowk.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhongyouzk.top/Article/details/gtanaiwkar.html

[R09] 字符串比较
来源：http://dali.yvedp.cn/Article/details/gttlpkmtze.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jqgufenzy.top/Article/details/gtytjkouwv.html

[R10] 正则匹配
来源：http://dali.jlsjyb.cn/Article/details/gtrfhivnsy.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.daxiang520.top/Article/details/gtdwljushh.html

[R11] case 多分支
来源：http://dali.jqgfzy.top/Article/details/gtksvhhozi.html

case "$1" in
来源：http://dali.ydzc1.top/Article/details/gtwchdfivb.html

start) echo "启动" ;;
来源：http://dali.kuanghao11.cn/Article/details/gtyysvyzjw.html

stop)  echo "停止" ;;
来源：http://dali.wangshuangyany.cn/Article/details/gtowbnarsn.html

*)     echo "未知命令" ;;
来源：http://dali.yuanzhike.top/Article/details/gtildqyaqj.html

esac
来源：http://dali.shuidangran.top/Article/details/gtzmruanrt.html

[R12] for 遍历文件
来源：http://dali.chenlongwang.top/Article/details/gtdlxjgaey.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jianghu66.top/Article/details/gtcrhkrlfy.html

[R13] for 计数循环
来源：http://dali.zhaomingkeji.xyz/Article/details/gtzfrnybwj.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.hywenlv.cn/Article/details/gtiyykjkss.html

[R14] C 风格 for
来源：http://dali.smart0.xyz/Article/details/gtseppsccl.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.ivvv.top/Article/details/gtkflyioso.html

[R15] while 逐行读文件
来源：http://dali.yueranfly.top/Article/details/gtkzlievxi.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.yj20258888.top/Article/details/gtkbftbpud.html

[R16] until 等待条件
来源：http://dali.shzxlz.cn/Article/details/gtfjnnzqef.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hammf.cn/Article/details/gtlpormoox.html

[R17] 数组定义与取值
来源：http://dali.jinyuanbaomall.cn/Article/details/gttcdrweyo.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.smart0.xyz/Article/details/gtuygxcrgg.html

[R18] 遍历数组
来源：http://dali.hfpthk.cn/Article/details/gtmxedqyzc.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.redwolf501.top/Article/details/gtglepqqqa.html

[R19] 数组长度
来源：http://dali.chenzaomai.com/Article/details/gteaosonnb.html

echo "${#arr[@]}"
来源：http://dali.hysaishi.cn/Article/details/gtlamdbgcc.html

[R20] 关联数组（字典）
来源：http://dali.havefunace.top/Article/details/gtlpkbqqmy.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yuxming.cn/Article/details/gtffasfgfz.html

[R21] 字符串长度
来源：http://dali.ybcxt.top/Article/details/gtxdazgkdn.html

echo "${#s}"
来源：http://dali.nwbrower.top/Article/details/gtlyrrfncg.html

[R22] 截取子串
来源：http://dali.jqgufenzy.top/Article/details/gtnthlcwqa.html

echo "${s:0:5}"
来源：http://dali.ybcxt.top/Article/details/gtixpuyiek.html

[R23] 字符串替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtozsrhlne.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jlsjyb.cn/Article/details/gtyaaorrtt.html

[R24] 大小写转换
来源：http://dali.zdqjudy.top/Article/details/gtfdaclgde.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.sxryk.cn/Article/details/gtxuniqgqy.html

[R25] 去后缀 / 去前缀
来源：http://dali.shuidangran.top/Article/details/gtqdplunvb.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.nanxinkj.top/Article/details/gtebrfsjyy.html

[R26] 命令替换
来源：http://dali.zycfv.cn/Article/details/gtnaazzaub.html

now=$(date +%F); echo "$now"
来源：http://dali.0kj1m.cn/Article/details/gtbzxhsmki.html

[R27] 算术展开
来源：http://dali.havefunace.top/Article/details/gttzpitfti.html

echo $((1 + 2 * 3))
来源：http://dali.svipenyu.cn/Article/details/gtfedxtbmu.html

[R28] 浮点运算
来源：http://dali.snrcjt.cn/Article/details/gthihavyrj.html

echo "scale=2; 10/3" | bc
来源：http://dali.guannengcc.top/Article/details/gteipcyfve.html

[R29] 定义函数
来源：http://dali.havefunace.top/Article/details/gtfoxqgeam.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.gogol.net.cn/Article/details/gtliwpoqlw.html

[R30] 函数返回状态码
来源：http://dali.tian-w.cn/Article/details/gtjoziyklp.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cashguo.top/Article/details/gtyklbcqqe.html

[R31] 局部变量
来源：http://dali.cheryme.top/Article/details/gtsmtbxdan.html

f() { local x=1; echo "$x"; }
来源：http://dali.chenjidiqi.icu/Article/details/gtmfedqchb.html

[R32] 参数个数校验
来源：http://dali.daria6918.cn/Article/details/gtirzhbabj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.ppjwa.cn/Article/details/gtqlojgfke.html

[R33] 捕获错误并提示行号
来源：http://dali.pengpengdd.cyou/Article/details/gtzdrcprcb.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.chenzaomai.com/Article/details/gtyoxmsalv.html

[R34] 退出时清理
来源：http://dali.wangdashe.top/Article/details/gtfipbyrnc.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.hywenlv.cn/Article/details/gtikhqnhxr.html

[R35] 后台执行并等待
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttqifyjef.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.mhx1999.top/Article/details/gtkfwfwxpg.html

[R36] 并发执行多个任务
来源：http://dali.wangshuangyany.cn/Article/details/gtveeaggjm.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jyoumei.cn/Article/details/gtexzsxell.html

[R37] 把输出赋给变量
来源：http://dali.hywenlv.cn/Article/details/gtiwuunlrs.html

files=$(ls -1)
来源：http://dali.yueranfly.top/Article/details/gteqesgaqr.html

[R38] 管道串联
来源：http://dali.zhiwuduotai.top/Article/details/gthhriwmee.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xylfe.cn/Article/details/gtmrlfhdol.html

[R39] 重定向标准输出与错误
来源：http://dali.c1oappe.top/Article/details/gtlfckqhiq.html

cmd > out.log 2>&1
来源：http://dali.snrcjt.cn/Article/details/gtiihuncgu.html

[R40] 追加写日志
来源：http://dali.yongpay.top/Article/details/gtpefppelh.html

echo "log" >> out.log
来源：http://dali.jinyuanbaomall.cn/Article/details/gttajjwxkp.html

[R41] 丢弃输出
来源：http://dali.wangshuangyany.cn/Article/details/gtbcoblqys.html

cmd >/dev/null 2>&1
来源：http://dali.cdnleiting.top/Article/details/gtkhyfcilk.html

[R42] 输入重定向
来源：http://dali.0kj1m.cn/Article/details/gtjayelplz.html

wc -l < a.txt
来源：http://dali.cheryme.top/Article/details/gtbvddqlxd.html

[R43] 按名字查找文件
来源：http://dali.yuanzhike.top/Article/details/gttmtnszom.html

find . -name "*.log" -type f
来源：http://dali.c1oappe.top/Article/details/gtdnpxuond.html

[R44] 按修改时间查找
来源：http://dali.fzhhl.top/Article/details/gtxfvdzzab.html

find . -mtime -7 -type f
来源：http://dali.9152youxi.cn/Article/details/gtihmqkftd.html

[R45] 批量删除
来源：http://dali.yj20258.top/Article/details/gtrnozakxp.html

find . -name "*.tmp" -delete
来源：http://dali.haohaochexian.top/Article/details/gtzhglyyxv.html

[R46] 递归替换文件内容
来源：http://dali.jlsjyb.cn/Article/details/gtanezfnjf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.daxiang520.top/Article/details/gtcrcvxnsx.html

[R47] sed 单行替换
来源：http://dali.jqgufenzy.top/Article/details/gtyngjwmnu.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.dianchejie.cn/Article/details/gtznduvdoh.html

[R48] awk 取指定列
来源：http://dali.nwbrower.top/Article/details/gtucpvthht.html

awk '{print $1, $3}' a.txt
来源：http://dali.xuanzx.com/Article/details/gtopxpxlvd.html

[R49] awk 带条件
来源：http://dali.shanyushiyangtech.top/Article/details/gtfdrzxndz.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.yuanzhike.top/Article/details/gtgiggjqmv.html

[R50] awk 求和
来源：http://dali.yangfankeji.com/Article/details/gtkxxwpfwx.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yonumen.top/Article/details/gtuivxdrud.html

[R51] 排序去重取前几
来源：http://dali.xylfe.cn/Article/details/gtcuchuqtz.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.shanyushiyangtech.top/Article/details/gtyaxlftle.html

[R52] 统计行数
来源：http://dali.guowangkeji.top/Article/details/gthsywfaov.html

wc -l a.txt
来源：http://dali.9152youxi.cn/Article/details/gtvnlsbmrd.html

[R53] 查看文件头与实时尾
来源：http://dali.zhijiandao.cn/Article/details/gtsfqnkcda.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jiagoushi.top/Article/details/gtyvmidtfj.html

[R54] 比较两个文件
来源：http://dali.0kj1m.cn/Article/details/gtivzqpdna.html

diff a.txt b.txt
来源：http://dali.jinghuilouyu.cn/Article/details/gtxybwyzgx.html

[R55] 压缩与解压
来源：http://dali.haohaochexian.top/Article/details/gtekfbjwbm.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsfjulxkw.html

[R56] 远程拷贝
来源：http://dali.shzxlz.cn/Article/details/gtydpogvrb.html

scp file user@host:/path/
来源：http://dali.hfpthk.cn/Article/details/gtnwxlooau.html

[R57] 远程执行命令
来源：http://dali.fzhhl.top/Article/details/gtqtalfolp.html

ssh user@host 'uptime'
来源：http://dali.sufxvd.cn/Article/details/gtxuoheuts.html

[R58] 下载文件
来源：http://dali.c1oappe.top/Article/details/gtezbymbcw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.dashuyun.cn/Article/details/gtvjxdsdpl.html

[R59] 发 POST JSON
来源：http://dali.jqgfzy.top/Article/details/gtfvkyrmlo.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.gogol.net.cn/Article/details/gtjbiyzaol.html

[R60] 只看 HTTP 状态码
来源：http://dali.chenzaomai.com/Article/details/gtevjksvme.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtltmldgsf.html

[R61] 磁盘占用
来源：http://dali.316326.xyz/Article/details/gtxuahkgdl.html

df -h;  du -sh *
来源：http://dali.chenjidiqi.icu/Article/details/gtovjwjmti.html

[R62] 找最占空间的文件
来源：http://dali.nwbrower.top/Article/details/gtybutxgzp.html

du -ah . | sort -rh | head -10
来源：http://dali.ehwqpu.com/Article/details/gtfcmagdun.html

[R63] 内存与进程
来源：http://dali.feifeiyinyue.top/Article/details/gtyemtuhkx.html

free -h;  ps aux | grep nginx
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzbxggugq.html

[R64] 结束进程
来源：http://dali.yvedp.cn/Article/details/gtpxpinvav.html

kill -9 $(pgrep -f app.py)
来源：http://dali.yj20258888.top/Article/details/gtickmxgxy.html

[R65] 查看端口占用
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpnusctze.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.gotoacloud.top/Article/details/gtfthudvmb.html

[R66] 定时任务
来源：http://dali.kuanghao11.cn/Article/details/gtiriufkjg.html

crontab -e;  crontab -l
来源：http://dali.hfpthk.cn/Article/details/gtdcqpvhzq.html

[R67] 生成随机十六进制串
来源：http://dali.nanxuanxn.top/Article/details/gtbbtnghpo.html

openssl rand -hex 16
来源：http://dali.bjfxy.top/Article/details/gtdfxabjxw.html

[R68] 计算文件校验值
来源：http://dali.yonumen.top/Article/details/gtdoussmea.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.hnxiangtu.top/Article/details/gtogooizkk.html

[R69] 生成随机密码
来源：http://dali.fzhhl.top/Article/details/gtvgtwlvbz.html

head -c 16 /dev/urandom | base64
来源：http://dali.meibo888.top/Article/details/gtxnhkeomv.html

[R70] 时间戳与互转
来源：http://dali.shangyingyoupin.top/Article/details/gtemidpqwz.html

date +%s;  date -d @1700000000
来源：http://dali.wangdashe.top/Article/details/gtoxvmcpdr.html

[R71] 日期格式化
来源：http://dali.meibo888.top/Article/details/gtqvyfaksr.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.hnxiangtu.top/Article/details/gtapfetzkx.html

[R72] 等待端口就绪
来源：http://dali.jqgfzy.top/Article/details/gtangaowhb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.316326.xyz/Article/details/gthpiyrtvy.html

[R73] 分割大日志
来源：http://dali.shzxlz.cn/Article/details/gthobnqndn.html

split -l 1000 big.log part_
来源：http://dali.jinghuilouyu.cn/Article/details/gtayzvgnip.html

[R74] 批量重命名
来源：http://dali.shanyushiyangtech.top/Article/details/gtxjcpnnjm.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gzhubu.top/Article/details/gtxalsojdq.html

[R75] 导出环境变量
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtiakxhwhg.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.ywan-chungtsiang.top/Article/details/gtxuhqyspa.html

[R76] 使用临时文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtfjtmxqcz.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.daxiang520.top/Article/details/gtovqvgaov.html

[R77] 读取用户输入
来源：http://dali.gaohongyu789.top/Article/details/gtbugwanxc.html

read -rp "请输入: " ans
来源：http://dali.jiagoushi.top/Article/details/gtdalecurh.html

[R78] 交互式菜单
来源：http://dali.jlsjyb.cn/Article/details/gtvpvnpskg.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.ybcxt.top/Article/details/gtpzgctpxh.html

[R79] 解析命令行选项
来源：http://dali.hongshengwenyu.top/Article/details/gttilhwlag.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.ydzc1.top/Article/details/gtfacpsbsk.html

[R80] 查看脚本执行耗时
来源：http://dali.zdqjudy.top/Article/details/gtvexqpjfw.html

time ./run.sh
来源：http://dali.xinyue.icu/Article/details/gtqorgedjb.html

================================================================================
来源：http://dali.svipenyu.cn/Article/details/gtxvjjfzhp.html


<!-- 参考信息 -->