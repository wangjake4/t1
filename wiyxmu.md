代发 wailian999

[Q36] 左连接
来源：http://dali.pycfn.com/Article/details/gtswxxmmqg.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.dianchejie.cn/Article/details/gtonhmubuc.html

[Q37] 右连接
来源：http://dali.hywenlv.cn/Article/details/gtqtkoafkx.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhengqikj.top/Article/details/gtovmgilph.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.yuxming.cn/Article/details/gtqmpcfcjb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.tian-w.cn/Article/details/gtdpzgqdwf.html

[Q39] 自连接（查上下级）
来源：http://dali.daxiang520.top/Article/details/gtooxkeuly.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.hnqzz.top/Article/details/gtkhqvnwwm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.xuetiantiany.cn/Article/details/gthnubqhjs.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.daxiang520.top/Article/details/gtilguggvq.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.sxryk.cn/Article/details/gtjweokgog.html

[Q41] 多表连接
来源：http://dali.havefunace.top/Article/details/gtnhyrhlrx.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.birdmap.top/Article/details/gtatmlnlms.html

JOIN users u ON u.id = o.user_id
来源：http://dali.ybcxt.top/Article/details/gtqtkzvwuj.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.shuidangran.top/Article/details/gtkgzfvasx.html

[Q42] 连接条件附加过滤
来源：http://dali.daxiang520.top/Article/details/gttpucimjg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.xylfe.cn/Article/details/gtuiqvwtkt.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtlfdygzoy.html

[Q43] 标量子查询
来源：http://dali.yj202588.top/Article/details/gtxtmxxopw.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.nwbrower.top/Article/details/gtpspkewtq.html

[Q44] IN 子查询
来源：http://dali.jiagoushi.top/Article/details/gtmygofvzo.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jiagoushi.top/Article/details/gtnaxjchuz.html

[Q45] EXISTS 判断存在
来源：http://dali.jlsjyb.cn/Article/details/gtywdiiyza.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.jinqigufen.top/Article/details/gtetdhyegl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.0kj1m.cn/Article/details/gtetuozbjw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.nanxinkj.top/Article/details/gtcxvdyjlj.html

[Q47] 与平均值比较
来源：http://dali.zhixingplan.top/Article/details/gtuwarwzae.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.shangyingyoupin.top/Article/details/gtrsoapfah.html

[Q48] CTE 公用表表达式
来源：http://dali.hammf.cn/Article/details/gtwsavuuij.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.guowangkeji.top/Article/details/gtjyiicjvy.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.nanxinkj.top/Article/details/gtuflupung.html

[Q49] 更新单行
来源：http://dali.hfpthk.cn/Article/details/gtngcxlewz.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.zhijiandao.cn/Article/details/gtisqfkjwa.html

[Q50] 批量更新
来源：http://dali.pengpengdd.cyou/Article/details/gtlkcdqfht.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.zhongyouzk.top/Article/details/gtimpdtxax.html

[Q51] 用子查询更新
来源：http://dali.yongpay.top/Article/details/gtsujebchy.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.snrcjt.cn/Article/details/gtfakyrtrl.html

[Q52] 删除指定行
来源：http://dali.bjfxy.top/Article/details/gtiobemzzd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.gaohongyu789.top/Article/details/gtrnyuhlpr.html

[Q53] 按条件删除
来源：http://dali.snrcjt.cn/Article/details/gtkferrkgc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.wangdashe.top/Article/details/gtemzjzyzi.html

[Q54] 清空表
来源：http://dali.ybcxt.top/Article/details/gtddyzaypq.html

TRUNCATE TABLE logs;
来源：http://dali.hfpthk.cn/Article/details/gtukipofme.html

[Q55] 排名（并列占位）
来源：http://dali.andypj.xyz/Article/details/gtntweezjy.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jinqigfzy.top/Article/details/gtvfqldyol.html

[Q56] 密集排名（并列不占位）
来源：http://dali.ppjwa.cn/Article/details/gtqncrkfwn.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.sxryk.cn/Article/details/gtmnwiwxqb.html

[Q57] 行号
来源：http://dali.gaohongyu789.top/Article/details/gttladjwgi.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.meibo888.top/Article/details/gthjqpzrhl.html

[Q58] 累计求和
来源：http://dali.nanxinkj.top/Article/details/gtpjqacnzz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.chenlongwang.top/Article/details/gtdwgtblkb.html

[Q59] 分组内累计
来源：http://dali.jiagoushi.top/Article/details/gtiaukjbta.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gtrjqldend.html

[Q60] 取上一行 / 下一行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyuitazjb.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.haohaochexian.top/Article/details/gtajswmkur.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hysaishi.cn/Article/details/gtvycyhoxq.html

[Q61] 移动平均
来源：http://dali.jiagoushi.top/Article/details/gtxrtxoevd.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.feifeiyinyue.top/Article/details/gtjkomzlpo.html

[Q62] 分组占比
来源：http://dali.cqqwz.cn/Article/details/gtbxbogmir.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.fzhhl.top/Article/details/gtepiwydqc.html

[Q63] 开启事务
来源：http://dali.iojbl.cn/Article/details/gtpcdiaqxz.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.yj202588.top/Article/details/gtsikubbnn.html

[Q64] 提交事务
来源：http://dali.316326.xyz/Article/details/gtgsvslcgi.html

COMMIT;
来源：http://dali.hfpthk.cn/Article/details/gtyqvwayps.html

[Q65] 回滚事务
来源：http://dali.haohaochexian.top/Article/details/gtlotwzzan.html

ROLLBACK;
来源：http://dali.yuanzhike.top/Article/details/gtdopigemh.html

[Q66] 行锁查询
来源：http://dali.jinghuilouyu.cn/Article/details/gtumafyrpn.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.cheryme.top/Article/details/gtmfxkkicq.html

[Q67] 设置隔离级别
来源：http://dali.birdmap.top/Article/details/gtjymihwsg.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.ivvv.top/Article/details/gtzbtnzdvy.html

[Q68] 保存点
来源：http://dali.jinyuanbaomall.cn/Article/details/gtxeqlhcfw.html

SAVEPOINT sp1;
来源：http://dali.hywenlv.cn/Article/details/gtgotmxcej.html

ROLLBACK TO sp1;
来源：http://dali.fengsongda.top/Article/details/gtergankuv.html

[Q69] 查看执行计划
来源：http://dali.316326.xyz/Article/details/gtjxccjhro.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.shanyushiyangkeji.top/Article/details/gteurolxqj.html

[Q70] 更新统计信息
来源：http://dali.meibo888.top/Article/details/gtuecmrtoy.html

ANALYZE TABLE users;
来源：http://dali.fengsongda.top/Article/details/gtfxzsqjoa.html

[Q71] 查看建表语句
来源：http://dali.ivvv.top/Article/details/gtwkevjxfq.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.gotoacloud.top/Article/details/gtthxzrcjo.html

[Q72] 查看索引
来源：http://dali.jianghu66.top/Article/details/gtntbmylru.html

SHOW INDEX FROM users;
来源：http://dali.guannengcc.top/Article/details/gtuodrhufz.html

[Q73] 查看表状态
来源：http://dali.jqgfzy.top/Article/details/gtuwdompim.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.gotoacloud.top/Article/details/gtaefyluwh.html

[Q74] 强制使用索引
来源：http://dali.tianlin.xyz/Article/details/gtmlxorfnl.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.jiagoushi.top/Article/details/gthcnrruci.html

[Q75] 日期格式化
来源：http://dali.fengsongda.top/Article/details/gtdahgsxwi.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.snrcjt.cn/Article/details/gtvehjvcfb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shanyushiyangkeji.top/Article/details/gtjargnwzh.html

[Q76] 按天统计
来源：http://dali.hysaishi.cn/Article/details/gtdtajcivt.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.birdmap.top/Article/details/gtplyldfea.html

[Q77] 时间加减
来源：http://dali.zycfv.cn/Article/details/gtsahlbgcp.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.daxiang520.top/Article/details/gtlzuceowm.html

[Q78] 当前时间
来源：http://dali.cashguo.top/Article/details/gtdsgfgwgf.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.xuetiantiany.cn/Article/details/gtowcdmkwl.html

[Q79] 字符串拼接
来源：http://dali.tianlin.xyz/Article/details/gtimyfimmc.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.chenjidiqi.icu/Article/details/gtthuzcifj.html

[Q80] 字符串截取
来源：http://dali.tianlin.xyz/Article/details/gtvtmksnjg.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.gogol.net.cn/Article/details/gtiwijyhfo.html

[Q81] 字符串替换
来源：http://dali.feifeiyinyue.top/Article/details/gtvagpdorl.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.dianchejie.cn/Article/details/gtdllrkcfl.html

[Q82] 字符长度与字节长度
来源：http://dali.xziqi.cn/Article/details/gtxukzldba.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cqqwz.cn/Article/details/gtnvcbnmaz.html

[Q83] 大小写转换
来源：http://dali.havefunace.top/Article/details/gtvxqfigbx.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.meibo888.top/Article/details/gtgvlsaabo.html

[Q84] 去除首尾空格
来源：http://dali.ywan-chungtsiang.top/Article/details/gtdxkdagdf.html

SELECT TRIM(name) FROM users;
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlugqhxgz.html

[Q85] 数值取整
来源：http://dali.yj202588.top/Article/details/gtmiohyvmq.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yanxiufei.cn/Article/details/gtudmewalc.html

[Q86] 读取 JSON 字段
来源：http://dali.fengsongda.top/Article/details/gtgnpqxkkc.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.gogol.net.cn/Article/details/gtfmfcnkse.html

[Q87] JSON 字段做条件
来源：http://dali.snrcjt.cn/Article/details/gtcenmkdmu.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.wangshuangyany.cn/Article/details/gtmrmohhnt.html

[Q88] 行转列（条件聚合）
来源：http://dali.shuidangran.top/Article/details/gtbigznthn.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.c1oappe.top/Article/details/gtmirutwss.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ehwqpu.com/Article/details/gtltlrocfh.html

[Q89] 判断表是否存在
来源：http://dali.dianchejie.cn/Article/details/gtoshnnejl.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.hnqzz.top/Article/details/gttpnafprb.html

[Q90] 生成序号列
来源：http://dali.meibo888.top/Article/details/gtojicrxah.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhongyouzk.top/Article/details/gtkkkbgwxx.html

================================================================================
来源：http://dali.guowangkeji.top/Article/details/gtltarmcbp.html

R. Bash 专题
来源：http://dali.tian-w.cn/Article/details/gtvaydrwkj.html

================================================================================
来源：http://dali.jianghu66.top/Article/details/gtiewdshum.html

[R01] shebang 与严格模式
来源：http://dali.jinqigfzy.top/Article/details/gtbeypjaqk.html

#!/usr/bin/env bash
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqbaljtoe.html

set -euo pipefail
来源：http://dali.yonumen.top/Article/details/gthypivkee.html

[R02] 变量赋值与使用
来源：http://dali.jyoumei.cn/Article/details/gtexjfnwdx.html

name="Tom"; echo "$name"
来源：http://dali.yj20258888.top/Article/details/gthcurvybq.html

[R03] 只读变量
来源：http://dali.chenjidiqi.icu/Article/details/gthbwrqmhj.html

readonly PI=3.14
来源：http://dali.birdmap.top/Article/details/gtduuaolmd.html

[R04] 位置参数
来源：http://dali.jinghuilouyu.cn/Article/details/gtctrdcoci.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yonumen.top/Article/details/gttofgweji.html

[R05] 参数默认值
来源：http://dali.shanyushiyangtech.top/Article/details/gtfqcnfxpp.html

name="${1:-default}"
来源：http://dali.feifeiyinyue.top/Article/details/gtimnicywl.html

[R06] 判断命令是否存在
来源：http://dali.yongpay.top/Article/details/gtelhcgswz.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.havefunace.top/Article/details/gtrvnhesnt.html

[R07] if 判断文件
来源：http://dali.tian-w.cn/Article/details/gthsotupyp.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.mhx1999.top/Article/details/gtjskmoyiq.html

[R08] 数值比较
来源：http://dali.yueranfly.top/Article/details/gtayfnlfnd.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.c1oappe.top/Article/details/gthecshbkv.html

[R09] 字符串比较
来源：http://dali.fzhhl.top/Article/details/gtdrxhtzth.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.ybcxt.top/Article/details/gtipkyjhxd.html

[R10] 正则匹配
来源：http://dali.yongpay.top/Article/details/gtatickyra.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yuanzhike.top/Article/details/gtnnvheyhc.html

[R11] case 多分支
来源：http://dali.0kj1m.cn/Article/details/gtdogodjcm.html

case "$1" in
来源：http://dali.birdmap.top/Article/details/gturbyxqnn.html

start) echo "启动" ;;
来源：http://dali.ppjwa.cn/Article/details/gtuzftxlob.html

stop)  echo "停止" ;;
来源：http://dali.zhengqikj.top/Article/details/gtegafpbry.html

*)     echo "未知命令" ;;
来源：http://dali.jlsjyb.cn/Article/details/gtcghgszrx.html

esac
来源：http://dali.jinghuilouyu.cn/Article/details/gtfayjdcbm.html

[R12] for 遍历文件
来源：http://dali.smart0.xyz/Article/details/gtlhdlemvf.html

for f in *.txt; do echo "$f"; done
来源：http://dali.tianlin.xyz/Article/details/gtpmgmeuus.html

[R13] for 计数循环
来源：http://dali.svipenyu.cn/Article/details/gtihfhxnmq.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtamdykpdw.html

[R14] C 风格 for
来源：http://dali.ybcxt.top/Article/details/gtuaknuizu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.fengsongda.top/Article/details/gttcebpsiv.html

[R15] while 逐行读文件
来源：http://dali.andypj.xyz/Article/details/gtbpkmhjex.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.nanxinkj.top/Article/details/gtsgyckdem.html

[R16] until 等待条件
来源：http://dali.yj20258888.top/Article/details/gtdivdtbjd.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.ppjwa.cn/Article/details/gtgzkescof.html

[R17] 数组定义与取值
来源：http://dali.zhaomingkeji.xyz/Article/details/gtfdveznec.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.zhijiandao.cn/Article/details/gtinnzjjqt.html

[R18] 遍历数组
来源：http://dali.pengpengdd.cyou/Article/details/gtsuuzizjw.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.daria6918.cn/Article/details/gtuhwmdiox.html

[R19] 数组长度
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkvaiinak.html

echo "${#arr[@]}"
来源：http://dali.chenjidiqi.icu/Article/details/gtzjxkfnrt.html

[R20] 关联数组（字典）
来源：http://dali.daxiang520.top/Article/details/gtrcsfdmxg.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.pycfn.com/Article/details/gtynkldhla.html

[R21] 字符串长度
来源：http://dali.jinghuilouyu.cn/Article/details/gtehwzyect.html

echo "${#s}"
来源：http://dali.gogol.net.cn/Article/details/gttkeybjqo.html

[R22] 截取子串
来源：http://dali.nanxuanxn.top/Article/details/gtolnexnos.html

echo "${s:0:5}"
来源：http://dali.zhaomingkeji.xyz/Article/details/gthkycbsce.html

[R23] 字符串替换
来源：http://dali.yuxming.cn/Article/details/gtzanuftuj.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hammf.cn/Article/details/gtdrfegdsz.html

[R24] 大小写转换
来源：http://dali.wangdashe.top/Article/details/gtlllvshhr.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ppjwa.cn/Article/details/gtfdonyohq.html

[R25] 去后缀 / 去前缀
来源：http://dali.shuidangran.top/Article/details/gtgsmkcfwj.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.tian-w.cn/Article/details/gtsuacnvzj.html

[R26] 命令替换
来源：http://dali.zycfv.cn/Article/details/gttxrlyqps.html

now=$(date +%F); echo "$now"
来源：http://dali.smart0.xyz/Article/details/gtumefsrbz.html

[R27] 算术展开
来源：http://dali.c1oappe.top/Article/details/gtgtacgbir.html

echo $((1 + 2 * 3))
来源：http://dali.yanxiufei.cn/Article/details/gtrofuhody.html

[R28] 浮点运算
来源：http://dali.ehwqpu.com/Article/details/gtceqzzsyi.html

echo "scale=2; 10/3" | bc
来源：http://dali.jiagoushi.top/Article/details/gtrjrebhxn.html

[R29] 定义函数
来源：http://dali.hammf.cn/Article/details/gtwymtjzgl.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.yuxming.cn/Article/details/gteteprjks.html

[R30] 函数返回状态码
来源：http://dali.zhongyouzk.top/Article/details/gtuxxiwgtd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.haohaochexian.top/Article/details/gtpccxuyyz.html

[R31] 局部变量
来源：http://dali.bjfxy.top/Article/details/gtxrghjkuu.html

f() { local x=1; echo "$x"; }
来源：http://dali.ydzc1.top/Article/details/gtardpjjku.html

[R32] 参数个数校验
来源：http://dali.smart0.xyz/Article/details/gtsbitjocx.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.zhijiandao.cn/Article/details/gtfccrepbt.html

[R33] 捕获错误并提示行号
来源：http://dali.jqgfzy.top/Article/details/gtrqymumxe.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.jiagoushi.top/Article/details/gtpkafssob.html

[R34] 退出时清理
来源：http://dali.guannengcc.top/Article/details/gtzfbbynuu.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.yj202588.top/Article/details/gthpgkrlhb.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gtwgnwxpxh.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.guowangkeji.top/Article/details/gtpwsitnim.html

[R36] 并发执行多个任务
来源：http://dali.jqgfzy.top/Article/details/gtzinigyia.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.jqgufenzy.top/Article/details/gthueudwer.html

[R37] 把输出赋给变量
来源：http://dali.zhengqikj.top/Article/details/gtzthanfwh.html

files=$(ls -1)
来源：http://dali.xylfe.cn/Article/details/gtqucatdfh.html

[R38] 管道串联
来源：http://dali.pengpengdd.cyou/Article/details/gtmpydzgcd.html

cat a.txt | grep -i error | wc -l
来源：http://dali.xylfe.cn/Article/details/gtfpabklhs.html

[R39] 重定向标准输出与错误
来源：http://dali.chenlongwang.top/Article/details/gtkxzbatpw.html

cmd > out.log 2>&1
来源：http://dali.xziqi.cn/Article/details/gtrnoiiovn.html

[R40] 追加写日志
来源：http://dali.meibo888.top/Article/details/gtrrajkqsv.html

echo "log" >> out.log
来源：http://dali.snrcjt.cn/Article/details/gtjjguimvn.html

[R41] 丢弃输出
来源：http://dali.chenlongwang.top/Article/details/gtbvfmenkw.html

cmd >/dev/null 2>&1
来源：http://dali.xziqi.cn/Article/details/gtovefrqms.html

[R42] 输入重定向
来源：http://dali.ybcxt.top/Article/details/gtdhxehiby.html

wc -l < a.txt
来源：http://dali.nanxuanxn.top/Article/details/gtkzahzevm.html

[R43] 按名字查找文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtxbhcqeta.html

find . -name "*.log" -type f
来源：http://dali.yj202588.top/Article/details/gtkxlpegug.html

[R44] 按修改时间查找
来源：http://dali.nwbrower.top/Article/details/gtyramhscz.html

find . -mtime -7 -type f
来源：http://dali.jiagoushi.top/Article/details/gtnlnrotbr.html

[R45] 批量删除
来源：http://dali.ydzc1.top/Article/details/gtcxxvsvmn.html

find . -name "*.tmp" -delete
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnjdwmgav.html

[R46] 递归替换文件内容
来源：http://dali.dianchejie.cn/Article/details/gtejmkyxgf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.gzhubu.top/Article/details/gtmdjxfobx.html

[R47] sed 单行替换
来源：http://dali.chenlongwang.top/Article/details/gtkoulkywi.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yj20258.top/Article/details/gtgufmvbrp.html

[R48] awk 取指定列
来源：http://dali.aizwys.cn/Article/details/gtfqejvsqs.html

awk '{print $1, $3}' a.txt
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcnhlqssv.html

[R49] awk 带条件
来源：http://dali.jinyuanbaomall.cn/Article/details/gtybonrrtu.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.hongshengwenyu.top/Article/details/gtfgvsjbkp.html

[R50] awk 求和
来源：http://dali.chenjidiqi.icu/Article/details/gteghzrnia.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.316326.xyz/Article/details/gtazoprosd.html

[R51] 排序去重取前几
来源：http://dali.wangshuangyany.cn/Article/details/gtvopdbcje.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.cdnleiting.top/Article/details/gthrsdvlng.html

[R52] 统计行数
来源：http://dali.chenjidiqi.icu/Article/details/gtydmsqcgu.html

wc -l a.txt
来源：http://dali.hfpthk.cn/Article/details/gtdhdszfqy.html

[R53] 查看文件头与实时尾
来源：http://dali.haohaochexian.top/Article/details/gtfxyqiygi.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.chenjidiqi.icu/Article/details/gtryulqwul.html

[R54] 比较两个文件
来源：http://dali.gotoacloud.top/Article/details/gtfzaamanz.html

diff a.txt b.txt
来源：http://dali.ydzc1.top/Article/details/gtiicymhtt.html

[R55] 压缩与解压
来源：http://dali.jqgfzy.top/Article/details/gtkrcgaciq.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yanxiufei.cn/Article/details/gtrmqmohaf.html

[R56] 远程拷贝
来源：http://dali.cqqwz.cn/Article/details/gtgiutqygr.html

scp file user@host:/path/
来源：http://dali.ydzc1.top/Article/details/gtcwhegvmq.html

[R57] 远程执行命令
来源：http://dali.ehwqpu.com/Article/details/gteuakoeel.html

ssh user@host 'uptime'
来源：http://dali.cqqwz.cn/Article/details/gtxodhvoup.html

[R58] 下载文件
来源：http://dali.xylfe.cn/Article/details/gteeavgkva.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.bjfxy.top/Article/details/gtmacavbei.html

[R59] 发 POST JSON
来源：http://dali.zhiwuduotai.top/Article/details/gtcfswhuno.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.snrcjt.cn/Article/details/gtdsaiqjzj.html

[R60] 只看 HTTP 状态码
来源：http://dali.birdmap.top/Article/details/gttliqnbhe.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.hnqzz.top/Article/details/gtmrdsaira.html

[R61] 磁盘占用
来源：http://dali.shanyushiyangtech.top/Article/details/gtwtduwqov.html

df -h;  du -sh *
来源：http://dali.nwbrower.top/Article/details/gtfdxkysqf.html

[R62] 找最占空间的文件
来源：http://dali.zhaomingkeji.xyz/Article/details/gtljriwljz.html

du -ah . | sort -rh | head -10
来源：http://dali.gogol.net.cn/Article/details/gtwxwsajxq.html

[R63] 内存与进程
来源：http://dali.gogol.net.cn/Article/details/gtzydsanfz.html

free -h;  ps aux | grep nginx
来源：http://dali.yangfankeji.com/Article/details/gtsghexxqo.html

[R64] 结束进程
来源：http://dali.feifeiyinyue.top/Article/details/gtnqdfnmfv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.xingfuxueyuan.xyz/Article/details/gttbtpbedv.html

[R65] 查看端口占用
来源：http://dali.hnqzz.top/Article/details/gtqtuwprya.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.hfpthk.cn/Article/details/gttsmlfheh.html

[R66] 定时任务
来源：http://dali.cashguo.top/Article/details/gtxxwvcsri.html

crontab -e;  crontab -l
来源：http://dali.haohaochexian.top/Article/details/gttbiukymm.html

[R67] 生成随机十六进制串
来源：http://dali.hnxiangtu.top/Article/details/gtosmpssaw.html

openssl rand -hex 16
来源：http://dali.dashuyun.cn/Article/details/gtxhbarsws.html

[R68] 计算文件校验值
来源：http://dali.jlsjyb.cn/Article/details/gtphfplyep.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.xinyue.icu/Article/details/gtglsqvara.html

[R69] 生成随机密码
来源：http://dali.zdqjudy.top/Article/details/gtxbwmrigr.html

head -c 16 /dev/urandom | base64
来源：http://dali.kuanghao11.cn/Article/details/gtofkfybqs.html

[R70] 时间戳与互转
来源：http://dali.birdmap.top/Article/details/gtatbxtfox.html

date +%s;  date -d @1700000000
来源：http://dali.jiagoushi.top/Article/details/gtejfvrjwa.html

[R71] 日期格式化
来源：http://dali.wangshuangyany.cn/Article/details/gtjzkjiwqo.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.iojbl.cn/Article/details/gtrowurbqn.html

[R72] 等待端口就绪
来源：http://dali.andypj.xyz/Article/details/gtrojxvruc.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.zycfv.cn/Article/details/gtxmnlwuhj.html

[R73] 分割大日志
来源：http://dali.birdmap.top/Article/details/gtbukjblvj.html

split -l 1000 big.log part_
来源：http://dali.bjfxy.top/Article/details/gtuvlwjzrk.html

[R74] 批量重命名
来源：http://dali.chenjidiqi.icu/Article/details/gtfcqlbxlh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.shanyushiyangtech.top/Article/details/gtxtsmdwjt.html

[R75] 导出环境变量
来源：http://dali.yanxiufei.cn/Article/details/gtwurgxjdt.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxbklseza.html

[R76] 使用临时文件
来源：http://dali.bjfxy.top/Article/details/gtvqszmzda.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.zhijiandao.cn/Article/details/gtxpcvnhvv.html

[R77] 读取用户输入
来源：http://dali.c1oappe.top/Article/details/gtqxlkjcgg.html

read -rp "请输入: " ans
来源：http://dali.smart0.xyz/Article/details/gtpjsromll.html

[R78] 交互式菜单
来源：http://dali.316326.xyz/Article/details/gtyhvhjfio.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.shzxlz.cn/Article/details/gtnvxpicvm.html

[R79] 解析命令行选项
来源：http://dali.ybcxt.top/Article/details/gtsawoozyw.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.jqgfzy.top/Article/details/gtqyvqfnnp.html

[R80] 查看脚本执行耗时
来源：http://dali.wangshuangyany.cn/Article/details/gtcormplvm.html

time ./run.sh
来源：http://dali.jiagoushi.top/Article/details/gtrrczpwku.html

================================================================================
来源：http://dali.nwbrower.top/Article/details/gtenpcfjtt.html

S. C / C++ 专题
来源：http://dali.smart0.xyz/Article/details/gtqnlqkwjy.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtrsazuksf.html

[S01] C：Hello World
来源：http://dali.jinyuanbaomall.cn/Article/details/gtmldhajpr.html

#include <stdio.h>
来源：http://dali.hongshengwenyu.top/Article/details/gthqqvhnfk.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkhlhszox.html

[S02] C：变量与格式化输出
来源：http://dali.guowangkeji.top/Article/details/gtonzsmrws.html

int a = 10; printf("%d\n", a);
来源：http://dali.jqgufenzy.top/Article/details/gtrhjspgas.html

[S03] C：读入整数
来源：http://dali.kuanghao11.cn/Article/details/gtksggznkc.html

int x; scanf("%d", &x);
来源：http://dali.birdmap.top/Article/details/gtnkczmual.html

[S04] C：字符串复制
来源：http://dali.haohaochexian.top/Article/details/gtvehjwack.html

char dst[32]; strcpy(dst, "hi");
来源：http://dali.yj202588.top/Article/details/gtpwkkevmr.html

[S05] C：字符串长度
来源：http://dali.wangdashe.top/Article/details/gtoxajgbms.html


<!-- 参考信息 -->