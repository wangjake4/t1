代发 wailian999

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.ybcxt.top/Article/details/gtqrukquhd.html

[Q28] 求和与平均
来源：http://dali.hnqzz.top/Article/details/gtedlbqkkp.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtwiurzktj.html

[Q29] 最大最小值
来源：http://dali.zhongyouzk.top/Article/details/gtlfiqzsil.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.snrcjt.cn/Article/details/gtquffyhnt.html

[Q30] 分组统计
来源：http://dali.hfpthk.cn/Article/details/gtujxljzca.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yj20258.top/Article/details/gtffoxlvvj.html

[Q31] 分组后过滤
来源：http://dali.shuidangran.top/Article/details/gtvjutaaqa.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.pycfn.com/Article/details/gtybybpjnb.html

[Q32] 分组拼接字符串
来源：http://dali.sysykeji.top/Article/details/gtlpecwhxp.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.daria6918.cn/Article/details/gteyxvwivs.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmepcmkfo.html

[Q33] 多列分组
来源：http://dali.feifeiyinyue.top/Article/details/gtevtmuhtg.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmopjlftq.html

[Q34] 每组取第一条
来源：http://dali.ehwqpu.com/Article/details/gtycfbmvsf.html

SELECT * FROM (
来源：http://dali.0kj1m.cn/Article/details/gtbuahwxuj.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.jlsjyb.cn/Article/details/gtyjuqchql.html

) t WHERE rn = 1;
来源：http://dali.nanxuanxn.top/Article/details/gtewyrqyro.html

[Q35] 内连接
来源：http://dali.feifeiyinyue.top/Article/details/gtfwrmlpzs.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenzaomai.com/Article/details/gtiivxrmax.html

[Q36] 左连接
来源：http://dali.quarkkingdee.top/Article/details/gtvvzlwnea.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.chenjidiqi.icu/Article/details/gtrjthinti.html

[Q37] 右连接
来源：http://dali.haohaochexian.top/Article/details/gtnitdbems.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.yj20258.top/Article/details/gthyymipet.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.fengsongda.top/Article/details/gtuwxsgylu.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yj202588.top/Article/details/gtissaptbh.html

[Q39] 自连接（查上下级）
来源：http://dali.bjfxy.top/Article/details/gtynqttwhw.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.kuanghao11.cn/Article/details/gttmypznls.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.aibaodan.cn/Article/details/gtxpsfeasp.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.gogol.net.cn/Article/details/gthhzxttwb.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.yj20258888.top/Article/details/gtphpimxqj.html

[Q41] 多表连接
来源：http://dali.nwbrower.top/Article/details/gtiwyhjhnt.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.zhiwuduotai.top/Article/details/gtdycywsbr.html

JOIN users u ON u.id = o.user_id
来源：http://dali.zhaomingkeji.xyz/Article/details/gtoxebtrzi.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.yueranfly.top/Article/details/gtmhpnmiyv.html

[Q42] 连接条件附加过滤
来源：http://dali.gzhubu.top/Article/details/gtikrzrzed.html

SELECT u.name, o.amount FROM users u
来源：http://dali.redwolf501.top/Article/details/gttjclioyx.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.yonumen.top/Article/details/gtqmpgleig.html

[Q43] 标量子查询
来源：http://dali.hywenlv.cn/Article/details/gtuqwvbseo.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.pengpengdd.cyou/Article/details/gtjtcuepmf.html

[Q44] IN 子查询
来源：http://dali.yongpay.top/Article/details/gtsybbzvwt.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.yuanzhike.top/Article/details/gtjpfzwpea.html

[Q45] EXISTS 判断存在
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmgqxifzy.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.chenzaomai.com/Article/details/gtcglcajkl.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtalrpbxlx.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.tian-w.cn/Article/details/gtjeyslakn.html

[Q47] 与平均值比较
来源：http://dali.gotoacloud.top/Article/details/gtzrdnghsa.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.0kj1m.cn/Article/details/gtzhwdejzt.html

[Q48] CTE 公用表表达式
来源：http://dali.snrcjt.cn/Article/details/gtlcraubyr.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.hysaishi.cn/Article/details/gtxgbrslqe.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.chenzaomai.com/Article/details/gthjuhqibm.html

[Q49] 更新单行
来源：http://dali.vqdsnc.cn/Article/details/gtavnshamd.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.smart0.xyz/Article/details/gtfkuuiqvu.html

[Q50] 批量更新
来源：http://dali.xuanzx.com/Article/details/gtodvkwtmm.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.kuanghao11.cn/Article/details/gtgcqalsrz.html

[Q51] 用子查询更新
来源：http://dali.wangdashe.top/Article/details/gtymgfeeph.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.vqdsnc.cn/Article/details/gtwlkrpocd.html

[Q52] 删除指定行
来源：http://dali.daria6918.cn/Article/details/gtykxybnbd.html

DELETE FROM users WHERE id = 10;
来源：http://dali.meibo888.top/Article/details/gtnxikwomm.html

[Q53] 按条件删除
来源：http://dali.yangfankeji.com/Article/details/gthewovmlg.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.tianlin.xyz/Article/details/gtljocepjl.html

[Q54] 清空表
来源：http://dali.tian-w.cn/Article/details/gtkvgypvqm.html

TRUNCATE TABLE logs;
来源：http://dali.tanke756.top/Article/details/gttrfgytcy.html

[Q55] 排名（并列占位）
来源：http://dali.hywenlv.cn/Article/details/gtxdhjsiho.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.andypj.xyz/Article/details/gtairjyvtg.html

[Q56] 密集排名（并列不占位）
来源：http://dali.cashguo.top/Article/details/gtlaustkzd.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.shuidangran.top/Article/details/gtvfommizl.html

[Q57] 行号
来源：http://dali.jyoumei.cn/Article/details/gtoxhdcnqc.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.ybcxt.top/Article/details/gtbszqbbxf.html

[Q58] 累计求和
来源：http://dali.c1oappe.top/Article/details/gttnmvtryg.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.zhijiandao.cn/Article/details/gtwiwhgeja.html

[Q59] 分组内累计
来源：http://dali.jiagoushi.top/Article/details/gtaclznrxh.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.pengpengdd.cyou/Article/details/gtytjphgda.html

[Q60] 取上一行 / 下一行
来源：http://dali.gzhubu.top/Article/details/gtcehgqvys.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.fengsongda.top/Article/details/gtapvkzrfh.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.0kj1m.cn/Article/details/gtdciepgtq.html

[Q61] 移动平均
来源：http://dali.yuxming.cn/Article/details/gteydgacod.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.tianlin.xyz/Article/details/gtmnpnyeqk.html

[Q62] 分组占比
来源：http://dali.jianghu66.top/Article/details/gtfcbpckta.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.hysaishi.cn/Article/details/gtdgggfqtv.html

[Q63] 开启事务
来源：http://dali.xuanzx.com/Article/details/gtmjfokxex.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.nanxuanxn.top/Article/details/gtueqrbovs.html

[Q64] 提交事务
来源：http://dali.smart0.xyz/Article/details/gtzihkvrte.html

COMMIT;
来源：http://dali.xziqi.cn/Article/details/gttyilohug.html

[Q65] 回滚事务
来源：http://dali.yvedp.cn/Article/details/gtoijwkxql.html

ROLLBACK;
来源：http://dali.pycfn.com/Article/details/gtrzzqshsb.html

[Q66] 行锁查询
来源：http://dali.ivvv.top/Article/details/gtfahvaoiu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ppjwa.cn/Article/details/gttglldahi.html

[Q67] 设置隔离级别
来源：http://dali.sufxvd.cn/Article/details/gtmymvlykh.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.pengpengdd.cyou/Article/details/gtzsyrawiy.html

[Q68] 保存点
来源：http://dali.zhiwuduotai.top/Article/details/gtwopihebg.html

SAVEPOINT sp1;
来源：http://dali.yuxming.cn/Article/details/gtcltsjqmo.html

ROLLBACK TO sp1;
来源：http://dali.jinghuilouyu.cn/Article/details/gthvpmfbuc.html

[Q69] 查看执行计划
来源：http://dali.tianlin.xyz/Article/details/gtdsuywwha.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.316326.xyz/Article/details/gtkxywvpgz.html

[Q70] 更新统计信息
来源：http://dali.gaohongyu789.top/Article/details/gtnzuqhzxg.html

ANALYZE TABLE users;
来源：http://dali.hongshengwenyu.top/Article/details/gtxzgeitbx.html

[Q71] 查看建表语句
来源：http://dali.dashuyun.cn/Article/details/gtqyesadai.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.ybcxt.top/Article/details/gtkxzcrldy.html

[Q72] 查看索引
来源：http://dali.shuidangran.top/Article/details/gtqbmnnvmk.html

SHOW INDEX FROM users;
来源：http://dali.guowangkeji.top/Article/details/gtfvmqpjmc.html

[Q73] 查看表状态
来源：http://dali.hnqzz.top/Article/details/gtjzfttukn.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.nwbrower.top/Article/details/gtllvzusrh.html

[Q74] 强制使用索引
来源：http://dali.yuanzhike.top/Article/details/gtpwlpdtoa.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.feifeiyinyue.top/Article/details/gtuqlrixht.html

[Q75] 日期格式化
来源：http://dali.yongpay.top/Article/details/gtfwpaijlv.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yuxming.cn/Article/details/gtszaxbxxq.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.pengpengdd.cyou/Article/details/gtluzvlvkc.html

[Q76] 按天统计
来源：http://dali.pengpengdd.cyou/Article/details/gtknufmqyg.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.c1oappe.top/Article/details/gtbtptpicl.html

[Q77] 时间加减
来源：http://dali.haohaochexian.top/Article/details/gtyybrcpbh.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shangyingyoupin.top/Article/details/gthenljexr.html

[Q78] 当前时间
来源：http://dali.tianlin.xyz/Article/details/gtgjjbtdwb.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.dashuyun.cn/Article/details/gtdwiacudk.html

[Q79] 字符串拼接
来源：http://dali.nanxuanxn.top/Article/details/gtvkvydzfu.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.iojbl.cn/Article/details/gtotgwjeby.html

[Q80] 字符串截取
来源：http://dali.gaohongyu789.top/Article/details/gtkyricbdx.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xziqi.cn/Article/details/gteairabmr.html

[Q81] 字符串替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtpinxsptj.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.hysaishi.cn/Article/details/gtzisdmewd.html

[Q82] 字符长度与字节长度
来源：http://dali.daxiang520.top/Article/details/gttyzeivnd.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.cucudq.cn/Article/details/gtledvnqua.html

[Q83] 大小写转换
来源：http://dali.jqgfzy.top/Article/details/gtowclhals.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtgpwvlxdw.html

[Q84] 去除首尾空格
来源：http://dali.meibo888.top/Article/details/gtmirdpqrx.html

SELECT TRIM(name) FROM users;
来源：http://dali.ivvv.top/Article/details/gtzekvyiwp.html

[Q85] 数值取整
来源：http://dali.svipenyu.cn/Article/details/gtrjcxdqax.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtqoamlsre.html

[Q86] 读取 JSON 字段
来源：http://dali.jlsjyb.cn/Article/details/gtwrjizobs.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.jianghu66.top/Article/details/gtpgvjwyrf.html

[Q87] JSON 字段做条件
来源：http://dali.jinqigufen.top/Article/details/gtceddqaar.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbmlepadw.html

[Q88] 行转列（条件聚合）
来源：http://dali.daxiang520.top/Article/details/gtoslmorkq.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.hongshengwenyu.top/Article/details/gtevmxubjx.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.ppjwa.cn/Article/details/gtrxltfhcy.html

[Q89] 判断表是否存在
来源：http://dali.gotoacloud.top/Article/details/gtxygyadrf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.sxryk.cn/Article/details/gtwlamaybp.html

[Q90] 生成序号列
来源：http://dali.zhijiandao.cn/Article/details/gtuylodleb.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.shuidangran.top/Article/details/gtgtfdsxsh.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtfynvjoqb.html

R. Bash 专题
来源：http://dali.ybcxt.top/Article/details/gtaeqsrcxr.html

================================================================================
来源：http://dali.wangdashe.top/Article/details/gtlpexlokn.html

[R01] shebang 与严格模式
来源：http://dali.gogol.net.cn/Article/details/gtxqdhzpgf.html

#!/usr/bin/env bash
来源：http://dali.yvedp.cn/Article/details/gtvdzjhczi.html

set -euo pipefail
来源：http://dali.redwolf501.top/Article/details/gtmqiqsyjh.html

[R02] 变量赋值与使用
来源：http://dali.iojbl.cn/Article/details/gtpufnttqr.html

name="Tom"; echo "$name"
来源：http://dali.9152youxi.cn/Article/details/gtzqggraop.html

[R03] 只读变量
来源：http://dali.hysaishi.cn/Article/details/gtkdvmaklp.html

readonly PI=3.14
来源：http://dali.vqdsnc.cn/Article/details/gttxoeohxe.html

[R04] 位置参数
来源：http://dali.jiagoushi.top/Article/details/gthmtatvnk.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.gotoacloud.top/Article/details/gttmqfrqgm.html

[R05] 参数默认值
来源：http://dali.ehwqpu.com/Article/details/gtsvnxpygo.html

name="${1:-default}"
来源：http://dali.hnqzz.top/Article/details/gtdproizwp.html

[R06] 判断命令是否存在
来源：http://dali.hammf.cn/Article/details/gtaqagrtuy.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.jinghuilouyu.cn/Article/details/gtlywxfkkv.html

[R07] if 判断文件
来源：http://dali.zycfv.cn/Article/details/gtijcfnhsq.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.hfpthk.cn/Article/details/gtvxjejcie.html

[R08] 数值比较
来源：http://dali.dianchejie.cn/Article/details/gtlxajfzat.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.sxryk.cn/Article/details/gtmacfanue.html

[R09] 字符串比较
来源：http://dali.birdmap.top/Article/details/gtmqldihfm.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.gotoacloud.top/Article/details/gtcfvwkqeh.html

[R10] 正则匹配
来源：http://dali.ehwqpu.com/Article/details/gtdoavwqfp.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.pycfn.com/Article/details/gtrjkaocsn.html

[R11] case 多分支
来源：http://dali.zycfv.cn/Article/details/gtknajhtgu.html

case "$1" in
来源：http://dali.cdnleiting.top/Article/details/gtgakoldjz.html

start) echo "启动" ;;
来源：http://dali.zdqjudy.top/Article/details/gtgofhztgc.html

stop)  echo "停止" ;;
来源：http://dali.nwbrower.top/Article/details/gtrnvjipre.html

*)     echo "未知命令" ;;
来源：http://dali.yueranfly.top/Article/details/gtzdnekntg.html

esac
来源：http://dali.gaohongyu789.top/Article/details/gtkwpsplxx.html

[R12] for 遍历文件
来源：http://dali.guannengcc.top/Article/details/gtatngttxa.html

for f in *.txt; do echo "$f"; done
来源：http://dali.daxiang520.top/Article/details/gtbwrfdlmd.html

[R13] for 计数循环
来源：http://dali.yangfankeji.com/Article/details/gtiosibjtd.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jianghu66.top/Article/details/gtlmllxoyp.html

[R14] C 风格 for
来源：http://dali.zhoulong.xyz/Article/details/gtopdgbcgu.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.c1oappe.top/Article/details/gttmozacyp.html

[R15] while 逐行读文件
来源：http://dali.iojbl.cn/Article/details/gtnpuhsfbb.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.xuetiantiany.cn/Article/details/gtohypenim.html

[R16] until 等待条件
来源：http://dali.yuxming.cn/Article/details/gtgfpzkjou.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.meibo888.top/Article/details/gtxhueqima.html

[R17] 数组定义与取值
来源：http://dali.wangshuangyany.cn/Article/details/gtjfiagotn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hammf.cn/Article/details/gttvukpinr.html

[R18] 遍历数组
来源：http://dali.gotoacloud.top/Article/details/gtejuhxepl.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xuetiantiany.cn/Article/details/gttwghzvsn.html

[R19] 数组长度
来源：http://dali.hfpthk.cn/Article/details/gtbdefcetc.html

echo "${#arr[@]}"
来源：http://dali.yuanzhike.top/Article/details/gthzyzsiwb.html

[R20] 关联数组（字典）
来源：http://dali.wangdashe.top/Article/details/gtuguozbum.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.wangshuangyany.cn/Article/details/gtoykmhiou.html

[R21] 字符串长度
来源：http://dali.jqgfzy.top/Article/details/gtyhsgvdwh.html

echo "${#s}"
来源：http://dali.vqdsnc.cn/Article/details/gtlehcuhec.html

[R22] 截取子串
来源：http://dali.yonumen.top/Article/details/gtxlenwlns.html

echo "${s:0:5}"
来源：http://dali.jianghu66.top/Article/details/gtwuljsxsy.html

[R23] 字符串替换
来源：http://dali.zhoulong.xyz/Article/details/gtfrjvrmuy.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.zhijiandao.cn/Article/details/gtmqimlaar.html

[R24] 大小写转换
来源：http://dali.shuidangran.top/Article/details/gtdgwcgdqv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.bjfxy.top/Article/details/gtokfhwqun.html

[R25] 去后缀 / 去前缀
来源：http://dali.ivvv.top/Article/details/gtqcdjxdvq.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.0kj1m.cn/Article/details/gtzfbyftdu.html

[R26] 命令替换
来源：http://dali.zhoulong.xyz/Article/details/gtoiimmpqx.html

now=$(date +%F); echo "$now"
来源：http://dali.redwolf501.top/Article/details/gtdaksovkd.html

[R27] 算术展开
来源：http://dali.ydzc1.top/Article/details/gtyqshqqsm.html

echo $((1 + 2 * 3))
来源：http://dali.guowangkeji.top/Article/details/gtlgsaorvy.html

[R28] 浮点运算
来源：http://dali.yj20258888.top/Article/details/gtxwauiyeu.html

echo "scale=2; 10/3" | bc
来源：http://dali.tianlin.xyz/Article/details/gtamclqbum.html

[R29] 定义函数
来源：http://dali.yuanzhike.top/Article/details/gtcpyqulrk.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jqgfzy.top/Article/details/gtugasesvs.html

[R30] 函数返回状态码
来源：http://dali.fengsongda.top/Article/details/gtzkyxraxd.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.iojbl.cn/Article/details/gtbdzssvww.html

[R31] 局部变量
来源：http://dali.0kj1m.cn/Article/details/gtxjdyltiq.html

f() { local x=1; echo "$x"; }
来源：http://dali.shanyushiyangkeji.top/Article/details/gtevupexcx.html

[R32] 参数个数校验
来源：http://dali.ywan-chungtsiang.top/Article/details/gtvzivetks.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.nanxinkj.top/Article/details/gtbjbtqivq.html

[R33] 捕获错误并提示行号
来源：http://dali.feifeiyinyue.top/Article/details/gtnaxgvvfl.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.xziqi.cn/Article/details/gtjfplmfrf.html

[R34] 退出时清理
来源：http://dali.xylfe.cn/Article/details/gtiygpuvvh.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.jqgufenzy.top/Article/details/gtrnfjhepd.html

[R35] 后台执行并等待
来源：http://dali.zhijiandao.cn/Article/details/gtquiaergw.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.yj202588.top/Article/details/gtsdsgnhfi.html

[R36] 并发执行多个任务
来源：http://dali.jqgfzy.top/Article/details/gtzmedahcb.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.yj202588.top/Article/details/gtjboabetj.html

[R37] 把输出赋给变量
来源：http://dali.feifeiyinyue.top/Article/details/gtivqxwwst.html

files=$(ls -1)
来源：http://dali.hongshengwenyu.top/Article/details/gtyntwdfff.html

[R38] 管道串联
来源：http://dali.jqgfzy.top/Article/details/gtyueqfuli.html

cat a.txt | grep -i error | wc -l
来源：http://dali.kuanghao11.cn/Article/details/gtxvolvpnc.html

[R39] 重定向标准输出与错误
来源：http://dali.tanke756.top/Article/details/gtmiplnyrg.html

cmd > out.log 2>&1
来源：http://dali.dianchejie.cn/Article/details/gtmbkagmar.html

[R40] 追加写日志
来源：http://dali.pengpengdd.cyou/Article/details/gtcazimtfo.html

echo "log" >> out.log
来源：http://dali.yonumen.top/Article/details/gtaqcjqoui.html

[R41] 丢弃输出
来源：http://dali.zhongyouzk.top/Article/details/gtejypujzd.html

cmd >/dev/null 2>&1
来源：http://dali.cdnleiting.top/Article/details/gtkybjgnuy.html

[R42] 输入重定向
来源：http://dali.0kj1m.cn/Article/details/gttbxqvdgq.html

wc -l < a.txt
来源：http://dali.tian-w.cn/Article/details/gteubemudb.html

[R43] 按名字查找文件
来源：http://dali.chenjidiqi.icu/Article/details/gtprzacoqv.html

find . -name "*.log" -type f
来源：http://dali.birdmap.top/Article/details/gtuydmpldk.html

[R44] 按修改时间查找
来源：http://dali.316326.xyz/Article/details/gtorzujhct.html

find . -mtime -7 -type f
来源：http://dali.jinyuanbaomall.cn/Article/details/gttzujqoyv.html

[R45] 批量删除
来源：http://dali.ehwqpu.com/Article/details/gtgnorowhb.html

find . -name "*.tmp" -delete
来源：http://dali.hammf.cn/Article/details/gtjdhvjzel.html

[R46] 递归替换文件内容
来源：http://dali.sxryk.cn/Article/details/gtqsrfgxmk.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.dianchejie.cn/Article/details/gtpmwlrmyy.html

[R47] sed 单行替换
来源：http://dali.gogol.net.cn/Article/details/gtjntfpgur.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.smart0.xyz/Article/details/gtahozjybc.html

[R48] awk 取指定列
来源：http://dali.meibo888.top/Article/details/gtpktfrkgj.html

awk '{print $1, $3}' a.txt
来源：http://dali.hfpthk.cn/Article/details/gtdurnuuad.html

[R49] awk 带条件
来源：http://dali.guannengcc.top/Article/details/gtstxiogqg.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.bjfxy.top/Article/details/gtecxfptkt.html

[R50] awk 求和
来源：http://dali.cqqwz.cn/Article/details/gteptostif.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.guowangkeji.top/Article/details/gtnrnefdpx.html

[R51] 排序去重取前几
来源：http://dali.feifeiyinyue.top/Article/details/gtlutfwobp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.svipenyu.cn/Article/details/gtmxtjjsei.html

[R52] 统计行数
来源：http://dali.zhijiandao.cn/Article/details/gtsycekxcd.html

wc -l a.txt
来源：http://dali.hysaishi.cn/Article/details/gtbkmzixny.html

[R53] 查看文件头与实时尾
来源：http://dali.cqqwz.cn/Article/details/gtkmkbeoxp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.pycfn.com/Article/details/gtexfjnfgj.html

[R54] 比较两个文件
来源：http://dali.tanke756.top/Article/details/gtlqtnxeqw.html

diff a.txt b.txt
来源：http://dali.zhijiandao.cn/Article/details/gterccccqy.html

[R55] 压缩与解压
来源：http://dali.chenzaomai.com/Article/details/gtcmbwykxv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.yj20258888.top/Article/details/gtxvumrcpc.html

[R56] 远程拷贝
来源：http://dali.shangyingyoupin.top/Article/details/gtpnmcvjmp.html

scp file user@host:/path/
来源：http://dali.haohaochexian.top/Article/details/gtiyxefkxw.html

[R57] 远程执行命令
来源：http://dali.wangshuangyany.cn/Article/details/gtnbmvrzsu.html

ssh user@host 'uptime'
来源：http://dali.sxryk.cn/Article/details/gtuswqovot.html

[R58] 下载文件
来源：http://dali.jinghuilouyu.cn/Article/details/gtyzvitnjf.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.tianlin.xyz/Article/details/gtfounqwcc.html

[R59] 发 POST JSON
来源：http://dali.hammf.cn/Article/details/gtqvlehmkc.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hnxiangtu.top/Article/details/gtknkyquku.html

[R60] 只看 HTTP 状态码
来源：http://dali.tanke756.top/Article/details/gtrveedlcj.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.birdmap.top/Article/details/gtkafezxfq.html

[R61] 磁盘占用
来源：http://dali.aibaodan.cn/Article/details/gtbfoydfve.html

df -h;  du -sh *
来源：http://dali.yonumen.top/Article/details/gtbirqbwwl.html

[R62] 找最占空间的文件
来源：http://dali.sysykeji.top/Article/details/gtwrlnqzwm.html

du -ah . | sort -rh | head -10
来源：http://dali.mhx1999.top/Article/details/gtpyoffuap.html

[R63] 内存与进程
来源：http://dali.sweek.top/Article/details/gtjuisljxh.html

free -h;  ps aux | grep nginx
来源：http://dali.cucudq.cn/Article/details/gtqlnguhop.html

[R64] 结束进程
来源：http://dali.havefunace.top/Article/details/gtmyftefhy.html

kill -9 $(pgrep -f app.py)
来源：http://dali.sufxvd.cn/Article/details/gtovgabveg.html

[R65] 查看端口占用
来源：http://dali.wangshuangyany.cn/Article/details/gtqsqrqrwh.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.yanxiufei.cn/Article/details/gttsjvwekh.html

[R66] 定时任务
来源：http://dali.daxiang520.top/Article/details/gtcemsbuay.html

crontab -e;  crontab -l
来源：http://dali.zhixingplan.top/Article/details/gtspqpotnw.html

[R67] 生成随机十六进制串
来源：http://dali.9152youxi.cn/Article/details/gtyvohrgov.html

openssl rand -hex 16
来源：http://dali.yuanzhike.top/Article/details/gttvbovkbx.html

[R68] 计算文件校验值
来源：http://dali.xuetiantiany.cn/Article/details/gtidaueqai.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jqgfzy.top/Article/details/gtihudeflj.html

[R69] 生成随机密码
来源：http://dali.yj20258888.top/Article/details/gtfppkoekv.html

head -c 16 /dev/urandom | base64
来源：http://dali.c1oappe.top/Article/details/gtfztvmcjw.html

[R70] 时间戳与互转
来源：http://dali.yj20258888.top/Article/details/gttnsgphkx.html

date +%s;  date -d @1700000000
来源：http://dali.zhixingplan.top/Article/details/gtgnquceje.html

[R71] 日期格式化
来源：http://dali.meibo888.top/Article/details/gtosdyvezy.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinyuanbaomall.cn/Article/details/gtshvvgmww.html

[R72] 等待端口就绪
来源：http://dali.mhx1999.top/Article/details/gtrngkhfna.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.nanxuanxn.top/Article/details/gtmcdvurex.html

[R73] 分割大日志
来源：http://dali.jiagoushi.top/Article/details/gtvauvywyb.html

split -l 1000 big.log part_
来源：http://dali.redwolf501.top/Article/details/gtgfqurlou.html

[R74] 批量重命名
来源：http://dali.xuanzx.com/Article/details/gtrqhcxyzv.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.aibaodan.cn/Article/details/gtjqnmcven.html

[R75] 导出环境变量
来源：http://dali.hammf.cn/Article/details/gtxyudqhdu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.xuetiantiany.cn/Article/details/gtwkwmhlqp.html

[R76] 使用临时文件
来源：http://dali.zhijiandao.cn/Article/details/gtvsqxwvsp.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.yangfankeji.com/Article/details/gtsjgvaihy.html

[R77] 读取用户输入
来源：http://dali.vqdsnc.cn/Article/details/gtadbauuct.html


<!-- 参考信息 -->