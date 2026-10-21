代发 wailian999

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.svipenyu.cn/Article/details/gtfwgiccxn.html

[Q26] 计数
来源：http://dali.sufxvd.cn/Article/details/gtyfnreisf.html

SELECT COUNT(*) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtcfmadgdm.html

[Q27] 条件计数
来源：http://dali.jqgufenzy.top/Article/details/gtumsldfzi.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtbqpoudcj.html

[Q28] 求和与平均
来源：http://dali.yj20258888.top/Article/details/gtvdgegnbl.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.jqgufenzy.top/Article/details/gtzdeatfka.html

[Q29] 最大最小值
来源：http://dali.yangfankeji.com/Article/details/gtopmrytpm.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.hongshengwenyu.top/Article/details/gtsozijqzh.html

[Q30] 分组统计
来源：http://dali.hammf.cn/Article/details/gtmwhvqcof.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.zhixingplan.top/Article/details/gtmhvdwldd.html

[Q31] 分组后过滤
来源：http://dali.jianghu66.top/Article/details/gtkpdjlqda.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.xuanzx.com/Article/details/gtgjqgexbe.html

[Q32] 分组拼接字符串
来源：http://dali.hammf.cn/Article/details/gtzwaldbgt.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.pengpengdd.cyou/Article/details/gthquhquol.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.0kj1m.cn/Article/details/gtpqxovhrb.html

[Q33] 多列分组
来源：http://dali.snrcjt.cn/Article/details/gtcneponxv.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.shanyushiyangtech.top/Article/details/gtzsajcuak.html

[Q34] 每组取第一条
来源：http://dali.gzhubu.top/Article/details/gtlozxahva.html

SELECT * FROM (
来源：http://dali.birdmap.top/Article/details/gtkzcltemq.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.quarkkingdee.top/Article/details/gtdayinakb.html

) t WHERE rn = 1;
来源：http://dali.andypj.xyz/Article/details/gtpvexggpo.html

[Q35] 内连接
来源：http://dali.yonumen.top/Article/details/gtcuwmptbp.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.havefunace.top/Article/details/gtjhdeiokf.html

[Q36] 左连接
来源：http://dali.fzhhl.top/Article/details/gtdphximth.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.redwolf501.top/Article/details/gtgvesymvo.html

[Q37] 右连接
来源：http://dali.wangdashe.top/Article/details/gtjrkwcqif.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yvedp.cn/Article/details/gtposrtaml.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xuanzx.com/Article/details/gtwgyaxrmu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.chenlongwang.top/Article/details/gtsghbcbdr.html

[Q39] 自连接（查上下级）
来源：http://dali.zycfv.cn/Article/details/gtqmtbmcjd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.jinghuilouyu.cn/Article/details/gtiekxdcwg.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.jianghu66.top/Article/details/gtoapthyfl.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.xinyue.icu/Article/details/gtjfrgnodk.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.zdqjudy.top/Article/details/gterlzzqre.html

[Q41] 多表连接
来源：http://dali.gaohongyu789.top/Article/details/gttjqhfpqd.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.mhx1999.top/Article/details/gtkxisqcfn.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yanxiufei.cn/Article/details/gtuwhhnfdx.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.zycfv.cn/Article/details/gtgcrklscq.html

[Q42] 连接条件附加过滤
来源：http://dali.zhengqikj.top/Article/details/gttpdevhhl.html

SELECT u.name, o.amount FROM users u
来源：http://dali.svipenyu.cn/Article/details/gtmnrpiugo.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.xuetiantiany.cn/Article/details/gtnnlkgzhu.html

[Q43] 标量子查询
来源：http://dali.sufxvd.cn/Article/details/gtvubsiuvj.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.aizwys.cn/Article/details/gtelziyfma.html

[Q44] IN 子查询
来源：http://dali.daria6918.cn/Article/details/gtqbchwamg.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.zhongyouzk.top/Article/details/gtyrboloij.html

[Q45] EXISTS 判断存在
来源：http://dali.yvedp.cn/Article/details/gtxcnvqqex.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xziqi.cn/Article/details/gtxhvamadb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yj20258888.top/Article/details/gtzgmlouya.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gaohongyu789.top/Article/details/gtagenkicg.html

[Q47] 与平均值比较
来源：http://dali.guannengcc.top/Article/details/gtwcqxphoo.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.chenlongwang.top/Article/details/gtgaiytwrc.html

[Q48] CTE 公用表表达式
来源：http://dali.yj20258888.top/Article/details/gtnfszijsn.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.jlsjyb.cn/Article/details/gtttfknqzr.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.bjfxy.top/Article/details/gtjhllrqbk.html

[Q49] 更新单行
来源：http://dali.cheryme.top/Article/details/gtyavwnjgx.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.guowangkeji.top/Article/details/gtlvqlhiwh.html

[Q50] 批量更新
来源：http://dali.zhengqikj.top/Article/details/gtcdrkocig.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhijiandao.cn/Article/details/gtbrromitr.html

[Q51] 用子查询更新
来源：http://dali.daxiang520.top/Article/details/gtjlhhupus.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.zhixingplan.top/Article/details/gtjzqamekr.html

[Q52] 删除指定行
来源：http://dali.hfpthk.cn/Article/details/gtjfyoekxj.html

DELETE FROM users WHERE id = 10;
来源：http://dali.chenlongwang.top/Article/details/gtooxhxwyv.html

[Q53] 按条件删除
来源：http://dali.ybcxt.top/Article/details/gtvqejnloh.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ivvv.top/Article/details/gtzkvfuqjr.html

[Q54] 清空表
来源：http://dali.sxryk.cn/Article/details/gturjmccpe.html

TRUNCATE TABLE logs;
来源：http://dali.yanxiufei.cn/Article/details/gttndeiuiz.html

[Q55] 排名（并列占位）
来源：http://dali.pycfn.com/Article/details/gtufvwopug.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.quarkkingdee.top/Article/details/gtybrphnmy.html

[Q56] 密集排名（并列不占位）
来源：http://dali.yongpay.top/Article/details/gttbljclrn.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtsvufyxyq.html

[Q57] 行号
来源：http://dali.aibaodan.cn/Article/details/gtbzmsbgvj.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.xziqi.cn/Article/details/gtuldzqphd.html

[Q58] 累计求和
来源：http://dali.chenlongwang.top/Article/details/gtadpjxzyz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.hywenlv.cn/Article/details/gtlkntrwzt.html

[Q59] 分组内累计
来源：http://dali.ppjwa.cn/Article/details/gtrfdcocec.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.wangdashe.top/Article/details/gtvojmmvwj.html

[Q60] 取上一行 / 下一行
来源：http://dali.gaohongyu789.top/Article/details/gthxxqyqls.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.feifeiyinyue.top/Article/details/gtuodrsiod.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yonumen.top/Article/details/gtyiphrqbi.html

[Q61] 移动平均
来源：http://dali.gotoacloud.top/Article/details/gtjusmfthy.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.dianchejie.cn/Article/details/gtudsuidrp.html

[Q62] 分组占比
来源：http://dali.chenjidiqi.icu/Article/details/gtkkaflsix.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhongyouzk.top/Article/details/gtpslftbtx.html

[Q63] 开启事务
来源：http://dali.gaohongyu789.top/Article/details/gtxuozcnfw.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.jinqigufen.top/Article/details/gtbecszoam.html

[Q64] 提交事务
来源：http://dali.daxiang520.top/Article/details/gtxzlaflzf.html

COMMIT;
来源：http://dali.jyoumei.cn/Article/details/gtxqlbknhi.html

[Q65] 回滚事务
来源：http://dali.dianchejie.cn/Article/details/gtsurrjhsb.html

ROLLBACK;
来源：http://dali.hfpthk.cn/Article/details/gtktkcudmg.html

[Q66] 行锁查询
来源：http://dali.zdqjudy.top/Article/details/gtivciyert.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cheryme.top/Article/details/gtbliyvdcf.html

[Q67] 设置隔离级别
来源：http://dali.gogol.net.cn/Article/details/gtzlulxtyw.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.zdqjudy.top/Article/details/gtwwgwoodx.html

[Q68] 保存点
来源：http://dali.hongshengwenyu.top/Article/details/gthjickwzc.html

SAVEPOINT sp1;
来源：http://dali.quarkkingdee.top/Article/details/gtxfiuiskh.html

ROLLBACK TO sp1;
来源：http://dali.zhoulong.xyz/Article/details/gtfozkwxwk.html

[Q69] 查看执行计划
来源：http://dali.shzxlz.cn/Article/details/gtqalekkle.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.jianghu66.top/Article/details/gtuetwdwqx.html

[Q70] 更新统计信息
来源：http://dali.yueranfly.top/Article/details/gtrncdhmyy.html

ANALYZE TABLE users;
来源：http://dali.yj20258888.top/Article/details/gtmmpshmwq.html

[Q71] 查看建表语句
来源：http://dali.jinyuanbaomall.cn/Article/details/gtifzvllsp.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.aibaodan.cn/Article/details/gtxywyybmy.html

[Q72] 查看索引
来源：http://dali.feifeiyinyue.top/Article/details/gtltstdyzz.html

SHOW INDEX FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtsrsvfsdv.html

[Q73] 查看表状态
来源：http://dali.ppjwa.cn/Article/details/gtygnakyab.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jqgfzy.top/Article/details/gtnqakfmdw.html

[Q74] 强制使用索引
来源：http://dali.ivvv.top/Article/details/gtheeyhgsf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jiagoushi.top/Article/details/gtjtfmpquc.html

[Q75] 日期格式化
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtphbfdlys.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zdqjudy.top/Article/details/gtinqgtkbq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.havefunace.top/Article/details/gtfqowvuhx.html

[Q76] 按天统计
来源：http://dali.fzhhl.top/Article/details/gtgoavkqtm.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.pengpengdd.cyou/Article/details/gtnxelqnet.html

[Q77] 时间加减
来源：http://dali.cdnleiting.top/Article/details/gthxffarkq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.yvedp.cn/Article/details/gtwwwsgmbo.html

[Q78] 当前时间
来源：http://dali.feifeiyinyue.top/Article/details/gtzuniqrms.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.hywenlv.cn/Article/details/gtrbnlkkqe.html

[Q79] 字符串拼接
来源：http://dali.zhixingplan.top/Article/details/gtrbtpjxzz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.sysykeji.top/Article/details/gtklvscejy.html

[Q80] 字符串截取
来源：http://dali.jqgufenzy.top/Article/details/gtvjoxeyxs.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.ybcxt.top/Article/details/gtqkiuxacw.html

[Q81] 字符串替换
来源：http://dali.shanyushiyangtech.top/Article/details/gtnlsqwfgg.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.guowangkeji.top/Article/details/gthnlyvfaa.html

[Q82] 字符长度与字节长度
来源：http://dali.hywenlv.cn/Article/details/gtnujlhuyo.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinqigfzy.top/Article/details/gtaaytsurv.html

[Q83] 大小写转换
来源：http://dali.aibaodan.cn/Article/details/gtfjayokdl.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.hnqzz.top/Article/details/gthndwyacy.html

[Q84] 去除首尾空格
来源：http://dali.xylfe.cn/Article/details/gttmlmhusx.html

SELECT TRIM(name) FROM users;
来源：http://dali.chenjidiqi.icu/Article/details/gtncyiregl.html

[Q85] 数值取整
来源：http://dali.jqgufenzy.top/Article/details/gttxzmfrmn.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xinyue.icu/Article/details/gthdkjxnlm.html

[Q86] 读取 JSON 字段
来源：http://dali.nanxuanxn.top/Article/details/gtnzisjuxi.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yueranfly.top/Article/details/gtnxickkvo.html

[Q87] JSON 字段做条件
来源：http://dali.hfpthk.cn/Article/details/gtfmxufsdg.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.mhx1999.top/Article/details/gtgopowbin.html

[Q88] 行转列（条件聚合）
来源：http://dali.xziqi.cn/Article/details/gtkrrzfjma.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.shzxlz.cn/Article/details/gtxqgtjxzb.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.sweek.top/Article/details/gtasdrgemd.html

[Q89] 判断表是否存在
来源：http://dali.ppjwa.cn/Article/details/gtocflgfrf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.zhaomingkeji.xyz/Article/details/gtttvabqkd.html

[Q90] 生成序号列
来源：http://dali.yanxiufei.cn/Article/details/gtwcfegktk.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.jinghuilouyu.cn/Article/details/gtvlzaqmrp.html

================================================================================
来源：http://dali.chenzaomai.com/Article/details/gtkeuzmpbo.html

R. Bash 专题
来源：http://dali.yueranfly.top/Article/details/gtjwnjbsfx.html

================================================================================
来源：http://dali.zhijiandao.cn/Article/details/gtetaieevc.html

[R01] shebang 与严格模式
来源：http://dali.cqqwz.cn/Article/details/gtdayltdpw.html

#!/usr/bin/env bash
来源：http://dali.jqgfzy.top/Article/details/gtdjnutakb.html

set -euo pipefail
来源：http://dali.ybcxt.top/Article/details/gtnlbtnfre.html

[R02] 变量赋值与使用
来源：http://dali.ivvv.top/Article/details/gtnswnuner.html

name="Tom"; echo "$name"
来源：http://dali.jqgufenzy.top/Article/details/gtuedprpsf.html

[R03] 只读变量
来源：http://dali.jiagoushi.top/Article/details/gtbgqykrzv.html

readonly PI=3.14
来源：http://dali.xuetiantiany.cn/Article/details/gtnycihkpn.html

[R04] 位置参数
来源：http://dali.andypj.xyz/Article/details/gtauobaipv.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.shanyushiyangtech.top/Article/details/gtwieuytct.html

[R05] 参数默认值
来源：http://dali.fengsongda.top/Article/details/gtprdrscwl.html

name="${1:-default}"
来源：http://dali.mhx1999.top/Article/details/gtrxrkxjds.html

[R06] 判断命令是否存在
来源：http://dali.sufxvd.cn/Article/details/gttyvifoir.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.redwolf501.top/Article/details/gttidgdblh.html

[R07] if 判断文件
来源：http://dali.chenjidiqi.icu/Article/details/gtzopcvtsl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.wangdashe.top/Article/details/gtgzteennj.html

[R08] 数值比较
来源：http://dali.chenlongwang.top/Article/details/gtsrmntfag.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.zhiwuduotai.top/Article/details/gtvyscrhfw.html

[R09] 字符串比较
来源：http://dali.0kj1m.cn/Article/details/gtiujfpirf.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.jinghuilouyu.cn/Article/details/gtexrtopar.html

[R10] 正则匹配
来源：http://dali.fengsongda.top/Article/details/gtogpbulqn.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.feifeiyinyue.top/Article/details/gtniceojoa.html

[R11] case 多分支
来源：http://dali.shanyushiyangtech.top/Article/details/gtcezzlavj.html

case "$1" in
来源：http://dali.shanyushiyangtech.top/Article/details/gtpkocuhyq.html

start) echo "启动" ;;
来源：http://dali.jinghuilouyu.cn/Article/details/gtzlmmvuhm.html

stop)  echo "停止" ;;
来源：http://dali.ehwqpu.com/Article/details/gtlhuizqsa.html

*)     echo "未知命令" ;;
来源：http://dali.yonumen.top/Article/details/gtypwnlnij.html

esac
来源：http://dali.fzhhl.top/Article/details/gtuernaqaa.html

[R12] for 遍历文件
来源：http://dali.zhoulong.xyz/Article/details/gtlilpquuw.html

for f in *.txt; do echo "$f"; done
来源：http://dali.sufxvd.cn/Article/details/gtotheqjwa.html

[R13] for 计数循环
来源：http://dali.dashuyun.cn/Article/details/gtxcddzazt.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.meibo888.top/Article/details/gtcgegfrwq.html

[R14] C 风格 for
来源：http://dali.shuidangran.top/Article/details/gtqzfuijoi.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.zhixingplan.top/Article/details/gtvmtwmohy.html

[R15] while 逐行读文件
来源：http://dali.shanyushiyangkeji.top/Article/details/gtaejppndu.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.jinqigfzy.top/Article/details/gtlprpjkrf.html

[R16] until 等待条件
来源：http://dali.yj20258.top/Article/details/gteaucnkzn.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.yvedp.cn/Article/details/gtmvycmuir.html

[R17] 数组定义与取值
来源：http://dali.jqgfzy.top/Article/details/gtqlcsqwyn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zdqjudy.top/Article/details/gtnoyekoux.html

[R18] 遍历数组
来源：http://dali.aizwys.cn/Article/details/gtmtnvejlg.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.pengpengdd.cyou/Article/details/gtvyspsyuu.html

[R19] 数组长度
来源：http://dali.jyoumei.cn/Article/details/gtnrwmiflg.html

echo "${#arr[@]}"
来源：http://dali.jianghu66.top/Article/details/gtkdwjpweg.html

[R20] 关联数组（字典）
来源：http://dali.ehwqpu.com/Article/details/gtvljjrcez.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.chenzaomai.com/Article/details/gtgmauadkj.html

[R21] 字符串长度
来源：http://dali.yuxming.cn/Article/details/gtrkckqzvd.html

echo "${#s}"
来源：http://dali.zhixingplan.top/Article/details/gtyovcifki.html

[R22] 截取子串
来源：http://dali.cdnleiting.top/Article/details/gtnapvflrm.html

echo "${s:0:5}"
来源：http://dali.ybcxt.top/Article/details/gthdonvzky.html

[R23] 字符串替换
来源：http://dali.birdmap.top/Article/details/gtnofaapic.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.mhx1999.top/Article/details/gtmhqnfcky.html

[R24] 大小写转换
来源：http://dali.nwbrower.top/Article/details/gtbrlkpgln.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.chenlongwang.top/Article/details/gtahyzpbad.html

[R25] 去后缀 / 去前缀
来源：http://dali.jyoumei.cn/Article/details/gtymbhohwj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yj20258888.top/Article/details/gtlpuhcbvo.html

[R26] 命令替换
来源：http://dali.jinqigufen.top/Article/details/gtytqyongu.html

now=$(date +%F); echo "$now"
来源：http://dali.xylfe.cn/Article/details/gtwwtouduw.html

[R27] 算术展开
来源：http://dali.dianchejie.cn/Article/details/gtbawmcnal.html

echo $((1 + 2 * 3))
来源：http://dali.bjfxy.top/Article/details/gthzrfolnn.html

[R28] 浮点运算
来源：http://dali.bjfxy.top/Article/details/gtdnonbqpm.html

echo "scale=2; 10/3" | bc
来源：http://dali.316326.xyz/Article/details/gtdktdpruv.html

[R29] 定义函数
来源：http://dali.dianchejie.cn/Article/details/gtqmhfayhh.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.sufxvd.cn/Article/details/gtxqxexfij.html

[R30] 函数返回状态码
来源：http://dali.yj202588.top/Article/details/gtnsriwvef.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.cheryme.top/Article/details/gtryyryeoo.html

[R31] 局部变量
来源：http://dali.mhx1999.top/Article/details/gtiudbiwdj.html

f() { local x=1; echo "$x"; }
来源：http://dali.andypj.xyz/Article/details/gtgseaviiz.html

[R32] 参数个数校验
来源：http://dali.jinqigfzy.top/Article/details/gtdzjavftn.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.tanke756.top/Article/details/gtvqquvbcj.html

[R33] 捕获错误并提示行号
来源：http://dali.tanke756.top/Article/details/gtjtlzigyi.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.gzhubu.top/Article/details/gtzfmelaby.html

[R34] 退出时清理
来源：http://dali.yuanzhike.top/Article/details/gtxmhdydcv.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.nanxinkj.top/Article/details/gtqekrxzna.html

[R35] 后台执行并等待
来源：http://dali.c1oappe.top/Article/details/gtpuvxkvjb.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xuetiantiany.cn/Article/details/gtqrdhgzzm.html

[R36] 并发执行多个任务
来源：http://dali.gogol.net.cn/Article/details/gtfapcoimt.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shangyingyoupin.top/Article/details/gtaiiknmlz.html

[R37] 把输出赋给变量
来源：http://dali.gogol.net.cn/Article/details/gtsbebuiyu.html

files=$(ls -1)
来源：http://dali.gogol.net.cn/Article/details/gtuhpjghmu.html

[R38] 管道串联
来源：http://dali.hnqzz.top/Article/details/gtwsiemfna.html

cat a.txt | grep -i error | wc -l
来源：http://dali.guannengcc.top/Article/details/gtznngygfh.html

[R39] 重定向标准输出与错误
来源：http://dali.zhijiandao.cn/Article/details/gtynufvrcx.html

cmd > out.log 2>&1
来源：http://dali.shangyingyoupin.top/Article/details/gtgfvescwf.html

[R40] 追加写日志
来源：http://dali.dashuyun.cn/Article/details/gtiwrtlulz.html

echo "log" >> out.log
来源：http://dali.sweek.top/Article/details/gtweetkqtb.html

[R41] 丢弃输出
来源：http://dali.yonumen.top/Article/details/gtzirfohtn.html

cmd >/dev/null 2>&1
来源：http://dali.aibaodan.cn/Article/details/gtddkalwrv.html

[R42] 输入重定向
来源：http://dali.zhoulong.xyz/Article/details/gtyrqaiduj.html

wc -l < a.txt
来源：http://dali.ydzc1.top/Article/details/gtyrpgurim.html

[R43] 按名字查找文件
来源：http://dali.yuanzhike.top/Article/details/gtjulasdqr.html

find . -name "*.log" -type f
来源：http://dali.cashguo.top/Article/details/gtpfguzdhy.html

[R44] 按修改时间查找
来源：http://dali.jiagoushi.top/Article/details/gtxkywjdti.html

find . -mtime -7 -type f
来源：http://dali.cashguo.top/Article/details/gtcxixgltf.html

[R45] 批量删除
来源：http://dali.shuidangran.top/Article/details/gtgcvikxnp.html

find . -name "*.tmp" -delete
来源：http://dali.xziqi.cn/Article/details/gtvfqilhgx.html

[R46] 递归替换文件内容
来源：http://dali.quarkkingdee.top/Article/details/gtxhrzknyh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.cashguo.top/Article/details/gtmuwgzzus.html

[R47] sed 单行替换
来源：http://dali.sxryk.cn/Article/details/gtpbcjamgv.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zhiwuduotai.top/Article/details/gtlzproixz.html

[R48] awk 取指定列
来源：http://dali.dianchejie.cn/Article/details/gtmdgxompt.html

awk '{print $1, $3}' a.txt
来源：http://dali.mhx1999.top/Article/details/gtbewefqsx.html

[R49] awk 带条件
来源：http://dali.hnqzz.top/Article/details/gtuarlpssj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.ivvv.top/Article/details/gtcvkikxmd.html

[R50] awk 求和
来源：http://dali.cucudq.cn/Article/details/gtcxcenvwt.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.guowangkeji.top/Article/details/gtczoljsum.html

[R51] 排序去重取前几
来源：http://dali.daxiang520.top/Article/details/gtjzpnjhya.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.c1oappe.top/Article/details/gtvjddadof.html

[R52] 统计行数
来源：http://dali.guannengcc.top/Article/details/gtfiilxkbp.html

wc -l a.txt
来源：http://dali.jinqigufen.top/Article/details/gtfwjxgkgf.html

[R53] 查看文件头与实时尾
来源：http://dali.sysykeji.top/Article/details/gtledaveku.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.xuetiantiany.cn/Article/details/gtjolpehoy.html

[R54] 比较两个文件
来源：http://dali.ybcxt.top/Article/details/gtwqdeyslv.html

diff a.txt b.txt
来源：http://dali.xziqi.cn/Article/details/gtiezttdbl.html

[R55] 压缩与解压
来源：http://dali.xinyue.icu/Article/details/gtqtealmhw.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zdqjudy.top/Article/details/gtkefuehqe.html

[R56] 远程拷贝
来源：http://dali.c1oappe.top/Article/details/gtbyzwbjuu.html

scp file user@host:/path/
来源：http://dali.zhongyouzk.top/Article/details/gtcazwatmu.html

[R57] 远程执行命令
来源：http://dali.feifeiyinyue.top/Article/details/gtkpmsgpkn.html

ssh user@host 'uptime'
来源：http://dali.zhongyouzk.top/Article/details/gttzkfnnxt.html

[R58] 下载文件
来源：http://dali.quarkkingdee.top/Article/details/gteirvzonv.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.sufxvd.cn/Article/details/gtdifcpgpa.html

[R59] 发 POST JSON
来源：http://dali.sweek.top/Article/details/gtvyymgmrs.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.zhiwuduotai.top/Article/details/gtotizhtnv.html

[R60] 只看 HTTP 状态码
来源：http://dali.yj202588.top/Article/details/gtalnwvavc.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.sufxvd.cn/Article/details/gthuqmnngh.html

[R61] 磁盘占用
来源：http://dali.pycfn.com/Article/details/gtwgcaspfx.html

df -h;  du -sh *
来源：http://dali.xuanzx.com/Article/details/gtjpiotgcl.html

[R62] 找最占空间的文件
来源：http://dali.c1oappe.top/Article/details/gtreqzzkiq.html

du -ah . | sort -rh | head -10
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlrtiajur.html

[R63] 内存与进程
来源：http://dali.iojbl.cn/Article/details/gtoviudcta.html

free -h;  ps aux | grep nginx
来源：http://dali.hnqzz.top/Article/details/gtffmkpfqp.html

[R64] 结束进程
来源：http://dali.jlsjyb.cn/Article/details/gtkucicgzh.html

kill -9 $(pgrep -f app.py)
来源：http://dali.daxiang520.top/Article/details/gtealhqbnw.html

[R65] 查看端口占用
来源：http://dali.sweek.top/Article/details/gtvfzexwhx.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.chenlongwang.top/Article/details/gthsqfoejr.html

[R66] 定时任务
来源：http://dali.sweek.top/Article/details/gtkkfydokk.html

crontab -e;  crontab -l
来源：http://dali.gogol.net.cn/Article/details/gtaenziowi.html

[R67] 生成随机十六进制串
来源：http://dali.jlsjyb.cn/Article/details/gtaarohyex.html

openssl rand -hex 16
来源：http://dali.tanke756.top/Article/details/gtzzuwepei.html

[R68] 计算文件校验值
来源：http://dali.zhixingplan.top/Article/details/gtwrtydmkw.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtgnqlxelg.html

[R69] 生成随机密码
来源：http://dali.cashguo.top/Article/details/gtcaevsnrw.html

head -c 16 /dev/urandom | base64
来源：http://dali.yvedp.cn/Article/details/gtwpjsrudx.html

[R70] 时间戳与互转
来源：http://dali.gaohongyu789.top/Article/details/gtyinhoxym.html

date +%s;  date -d @1700000000
来源：http://dali.zhongyouzk.top/Article/details/gtvjbmirhc.html

[R71] 日期格式化
来源：http://dali.aizwys.cn/Article/details/gtlvsrnkhs.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.ywan-chungtsiang.top/Article/details/gttufkmoyz.html

[R72] 等待端口就绪
来源：http://dali.yongpay.top/Article/details/gtdrdjxpvl.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.c1oappe.top/Article/details/gthkxazrfx.html

[R73] 分割大日志
来源：http://dali.redwolf501.top/Article/details/gtbjpccudf.html

split -l 1000 big.log part_
来源：http://dali.sysykeji.top/Article/details/gtsdseumgd.html

[R74] 批量重命名
来源：http://dali.ydzc1.top/Article/details/gtmqcbnbri.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.gzhubu.top/Article/details/gtsmmdhfoy.html

[R75] 导出环境变量
来源：http://dali.cdnleiting.top/Article/details/gtnqvxsfei.html


<!-- 参考信息 -->