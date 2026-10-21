代发 wailian999

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtlntbcrys.html

[Q30] 分组统计
来源：http://dali.jlsjyb.cn/Article/details/gtwujykyww.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.jyoumei.cn/Article/details/gtlsyletxm.html

[Q31] 分组后过滤
来源：http://dali.chenlongwang.top/Article/details/gtdvpswsrx.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.shzxlz.cn/Article/details/gtuchjscbe.html

[Q32] 分组拼接字符串
来源：http://dali.hongshengwenyu.top/Article/details/gtcydjkcrh.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.cucudq.cn/Article/details/gtjloeubyk.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.yj20258.top/Article/details/gtqlbblmdq.html

[Q33] 多列分组
来源：http://dali.wangshuangyany.cn/Article/details/gtzquzebxy.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.cashguo.top/Article/details/gtotnsfmli.html

[Q34] 每组取第一条
来源：http://dali.mhx1999.top/Article/details/gtmhcwzcoc.html

SELECT * FROM (
来源：http://dali.hnxiangtu.top/Article/details/gtfezumbmw.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.tianlin.xyz/Article/details/gturipichl.html

) t WHERE rn = 1;
来源：http://dali.gzhubu.top/Article/details/gtwjwytfpm.html

[Q35] 内连接
来源：http://dali.jinqigufen.top/Article/details/gtiqbvfkvq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.wangshuangyany.cn/Article/details/gturiaumhm.html

[Q36] 左连接
来源：http://dali.cucudq.cn/Article/details/gtvbffbjsn.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcukxzmbx.html

[Q37] 右连接
来源：http://dali.meibo888.top/Article/details/gtoqtwlvhv.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.daria6918.cn/Article/details/gtbsjtbsqp.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.ehwqpu.com/Article/details/gtblhtljxf.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yonumen.top/Article/details/gtgaosewcl.html

[Q39] 自连接（查上下级）
来源：http://dali.cucudq.cn/Article/details/gtldnwzatb.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.shangyingyoupin.top/Article/details/gtzkengthm.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.dianchejie.cn/Article/details/gtosyexsfm.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.shanyushiyangkeji.top/Article/details/gtdjbpfwpx.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.xylfe.cn/Article/details/gtsfolquaz.html

[Q41] 多表连接
来源：http://dali.zycfv.cn/Article/details/gtsbjcpjgo.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.c1oappe.top/Article/details/gtpvocsjzw.html

JOIN users u ON u.id = o.user_id
来源：http://dali.yongpay.top/Article/details/gtrvobwtma.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.aibaodan.cn/Article/details/gtlrjcbatr.html

[Q42] 连接条件附加过滤
来源：http://dali.yonumen.top/Article/details/gtaarisedg.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yanxiufei.cn/Article/details/gtdpthmnly.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.haohaochexian.top/Article/details/gtlyexdlef.html

[Q43] 标量子查询
来源：http://dali.nwbrower.top/Article/details/gtjkuhouyt.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.dashuyun.cn/Article/details/gtppmrnovm.html

[Q44] IN 子查询
来源：http://dali.zdqjudy.top/Article/details/gtnjtdmquz.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.hysaishi.cn/Article/details/gtycymbjmy.html

[Q45] EXISTS 判断存在
来源：http://dali.yonumen.top/Article/details/gtwdikadmt.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.kuanghao11.cn/Article/details/gtyhiswgxb.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yongpay.top/Article/details/gthuwgwddq.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtuvccumzb.html

[Q47] 与平均值比较
来源：http://dali.ydzc1.top/Article/details/gtqwcxbweb.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.sweek.top/Article/details/gtgubhtvvc.html

[Q48] CTE 公用表表达式
来源：http://dali.yuxming.cn/Article/details/gtmjpgnvcu.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.zdqjudy.top/Article/details/gtshkzuauv.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.gaohongyu789.top/Article/details/gtsffvldkh.html

[Q49] 更新单行
来源：http://dali.zhengqikj.top/Article/details/gtfuosboib.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.cheryme.top/Article/details/gtbjldqsuj.html

[Q50] 批量更新
来源：http://dali.wangdashe.top/Article/details/gtalfvycqw.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.pengpengdd.cyou/Article/details/gtkqioftcu.html

[Q51] 用子查询更新
来源：http://dali.tanke756.top/Article/details/gtdwfkmtdg.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.andypj.xyz/Article/details/gtsgrrhwjv.html

[Q52] 删除指定行
来源：http://dali.ywan-chungtsiang.top/Article/details/gtclqvtvrb.html

DELETE FROM users WHERE id = 10;
来源：http://dali.yj20258.top/Article/details/gttxsozroo.html

[Q53] 按条件删除
来源：http://dali.havefunace.top/Article/details/gtroirhsjc.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.bjfxy.top/Article/details/gtmjhomahe.html

[Q54] 清空表
来源：http://dali.hfpthk.cn/Article/details/gtqehkqcnd.html

TRUNCATE TABLE logs;
来源：http://dali.xuetiantiany.cn/Article/details/gtltoyxlap.html

[Q55] 排名（并列占位）
来源：http://dali.fengsongda.top/Article/details/gtwplheqcl.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.daxiang520.top/Article/details/gthdbooosm.html

[Q56] 密集排名（并列不占位）
来源：http://dali.chenlongwang.top/Article/details/gtcrmogmho.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.jinghuilouyu.cn/Article/details/gtbgpwdezn.html

[Q57] 行号
来源：http://dali.hnqzz.top/Article/details/gtwykbweey.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.yj20258888.top/Article/details/gtedvtafxk.html

[Q58] 累计求和
来源：http://dali.hysaishi.cn/Article/details/gtxxmxkhdc.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtnzubpugk.html

[Q59] 分组内累计
来源：http://dali.nanxinkj.top/Article/details/gtjmazwyep.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.tian-w.cn/Article/details/gtyyghpilc.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhijiandao.cn/Article/details/gtvfxfgquk.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.gotoacloud.top/Article/details/gtopidaokm.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.shuidangran.top/Article/details/gthxtfcqvs.html

[Q61] 移动平均
来源：http://dali.havefunace.top/Article/details/gtoxvjdtxr.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.aizwys.cn/Article/details/gtharlbxxv.html

[Q62] 分组占比
来源：http://dali.shangyingyoupin.top/Article/details/gtgvttdtnq.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.zhaomingkeji.xyz/Article/details/gttgkfziek.html

[Q63] 开启事务
来源：http://dali.yongpay.top/Article/details/gtibrsigsm.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.cheryme.top/Article/details/gtzpcfssyp.html

[Q64] 提交事务
来源：http://dali.tian-w.cn/Article/details/gtyjgqaksn.html

COMMIT;
来源：http://dali.hammf.cn/Article/details/gtefcbsdgu.html

[Q65] 回滚事务
来源：http://dali.guowangkeji.top/Article/details/gtmitlgaoi.html

ROLLBACK;
来源：http://dali.quarkkingdee.top/Article/details/gtfvqavozu.html

[Q66] 行锁查询
来源：http://dali.cdnleiting.top/Article/details/gtxgrbvzhh.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.tian-w.cn/Article/details/gtbnsooqxv.html

[Q67] 设置隔离级别
来源：http://dali.bjfxy.top/Article/details/gtitnuuaky.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.fengsongda.top/Article/details/gtklpoenlw.html

[Q68] 保存点
来源：http://dali.ivvv.top/Article/details/gtuddvfgab.html

SAVEPOINT sp1;
来源：http://dali.pycfn.com/Article/details/gtgsmiynzc.html

ROLLBACK TO sp1;
来源：http://dali.zhiwuduotai.top/Article/details/gtoivfreev.html

[Q69] 查看执行计划
来源：http://dali.jqgfzy.top/Article/details/gtommcvazd.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.9152youxi.cn/Article/details/gtqltrcgnf.html

[Q70] 更新统计信息
来源：http://dali.dashuyun.cn/Article/details/gthjemnpnd.html

ANALYZE TABLE users;
来源：http://dali.xylfe.cn/Article/details/gtqsbjdvae.html

[Q71] 查看建表语句
来源：http://dali.zhiwuduotai.top/Article/details/gtgnefyyoh.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.sweek.top/Article/details/gtdtxihfrq.html

[Q72] 查看索引
来源：http://dali.yj20258.top/Article/details/gtyslyoulh.html

SHOW INDEX FROM users;
来源：http://dali.sweek.top/Article/details/gtjfjjrwiq.html

[Q73] 查看表状态
来源：http://dali.mhx1999.top/Article/details/gtognpyipu.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.tanke756.top/Article/details/gtcwyfkckl.html

[Q74] 强制使用索引
来源：http://dali.birdmap.top/Article/details/gthsbwdqkm.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yuanzhike.top/Article/details/gttbfnomqr.html

[Q75] 日期格式化
来源：http://dali.haohaochexian.top/Article/details/gtthkqytzs.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yangfankeji.com/Article/details/gtyspcbcdz.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.zhijiandao.cn/Article/details/gtktjrckrg.html

[Q76] 按天统计
来源：http://dali.vqdsnc.cn/Article/details/gtzbgicwtr.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.ppjwa.cn/Article/details/gtokntryed.html

[Q77] 时间加减
来源：http://dali.zdqjudy.top/Article/details/gtmwlqbwap.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.dashuyun.cn/Article/details/gteofthuoa.html

[Q78] 当前时间
来源：http://dali.nanxinkj.top/Article/details/gtxwzoxlhr.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.snrcjt.cn/Article/details/gtlkitckte.html

[Q79] 字符串拼接
来源：http://dali.zhongyouzk.top/Article/details/gtmtlhsgle.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.zhixingplan.top/Article/details/gtokvjroap.html

[Q80] 字符串截取
来源：http://dali.wangshuangyany.cn/Article/details/gtzszbsucp.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.chenzaomai.com/Article/details/gtpprpwkpf.html

[Q81] 字符串替换
来源：http://dali.ppjwa.cn/Article/details/gtxlnuzddx.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtkwygfpuz.html

[Q82] 字符长度与字节长度
来源：http://dali.9152youxi.cn/Article/details/gtwtwedfwu.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.aibaodan.cn/Article/details/gtkhcmtcbs.html

[Q83] 大小写转换
来源：http://dali.hongshengwenyu.top/Article/details/gtwfulhyzz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gtasucmgyd.html

[Q84] 去除首尾空格
来源：http://dali.shzxlz.cn/Article/details/gtgzkovhqz.html

SELECT TRIM(name) FROM users;
来源：http://dali.cheryme.top/Article/details/gtlefuafsp.html

[Q85] 数值取整
来源：http://dali.kuanghao11.cn/Article/details/gthbeyaeqh.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yuxming.cn/Article/details/gtsrsdjphu.html

[Q86] 读取 JSON 字段
来源：http://dali.fengsongda.top/Article/details/gtvoioipye.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.hongshengwenyu.top/Article/details/gtxsjmruqp.html

[Q87] JSON 字段做条件
来源：http://dali.hnxiangtu.top/Article/details/gtchntvrdr.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.tian-w.cn/Article/details/gtgllfyygl.html

[Q88] 行转列（条件聚合）
来源：http://dali.smart0.xyz/Article/details/gtnjutwdbz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhengqikj.top/Article/details/gtxrbvmhjg.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.yj202588.top/Article/details/gtgovokflm.html

[Q89] 判断表是否存在
来源：http://dali.jiagoushi.top/Article/details/gtayymmirq.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.nanxinkj.top/Article/details/gtgfroeqmh.html

[Q90] 生成序号列
来源：http://dali.jianghu66.top/Article/details/gtvhunxlrl.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.bjfxy.top/Article/details/gttogqaxol.html

================================================================================
来源：http://dali.fengsongda.top/Article/details/gtdnwktqht.html

R. Bash 专题
来源：http://dali.ydzc1.top/Article/details/gtbtthuezy.html

================================================================================
来源：http://dali.sysykeji.top/Article/details/gthktxfcla.html

[R01] shebang 与严格模式
来源：http://dali.nwbrower.top/Article/details/gtekgxjwha.html

#!/usr/bin/env bash
来源：http://dali.sysykeji.top/Article/details/gtiribkxta.html

set -euo pipefail
来源：http://dali.yuanzhike.top/Article/details/gtdxucuqvb.html

[R02] 变量赋值与使用
来源：http://dali.tianlin.xyz/Article/details/gtinzlsevg.html

name="Tom"; echo "$name"
来源：http://dali.chenlongwang.top/Article/details/gteafzmxjv.html

[R03] 只读变量
来源：http://dali.c1oappe.top/Article/details/gtpcfjssdf.html

readonly PI=3.14
来源：http://dali.jiagoushi.top/Article/details/gttbrmeeam.html

[R04] 位置参数
来源：http://dali.kuanghao11.cn/Article/details/gtatkqobrf.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.hammf.cn/Article/details/gtscjbjofh.html

[R05] 参数默认值
来源：http://dali.zhengqikj.top/Article/details/gtvahqstnm.html

name="${1:-default}"
来源：http://dali.vqdsnc.cn/Article/details/gtpecpawzu.html

[R06] 判断命令是否存在
来源：http://dali.feifeiyinyue.top/Article/details/gtogqplhdn.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.iojbl.cn/Article/details/gtsxhrhqxt.html

[R07] if 判断文件
来源：http://dali.zycfv.cn/Article/details/gtafsgolsv.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtnqiaqadb.html

[R08] 数值比较
来源：http://dali.andypj.xyz/Article/details/gtpfiwebgs.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.tian-w.cn/Article/details/gtjpibvklj.html

[R09] 字符串比较
来源：http://dali.dianchejie.cn/Article/details/gtllcwekzb.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.zhijiandao.cn/Article/details/gtejhfaxve.html

[R10] 正则匹配
来源：http://dali.cucudq.cn/Article/details/gtdlwisiii.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.haohaochexian.top/Article/details/gttpbhgopv.html

[R11] case 多分支
来源：http://dali.cheryme.top/Article/details/gtfvzpwxib.html

case "$1" in
来源：http://dali.shanyushiyangtech.top/Article/details/gthssiafpa.html

start) echo "启动" ;;
来源：http://dali.andypj.xyz/Article/details/gtfqhpyrnq.html

stop)  echo "停止" ;;
来源：http://dali.cdnleiting.top/Article/details/gtbcgiwmfl.html

*)     echo "未知命令" ;;
来源：http://dali.bjfxy.top/Article/details/gtporoaome.html

esac
来源：http://dali.tianlin.xyz/Article/details/gttdwqdxvd.html

[R12] for 遍历文件
来源：http://dali.zhongyouzk.top/Article/details/gtptqnfbnx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.xylfe.cn/Article/details/gtsmsanffr.html

[R13] for 计数循环
来源：http://dali.xuanzx.com/Article/details/gtualguizz.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.zhijiandao.cn/Article/details/gtgpytgijj.html

[R14] C 风格 for
来源：http://dali.sweek.top/Article/details/gtoiwlqroh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.sweek.top/Article/details/gtdabdynyu.html

[R15] while 逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gtbcomyevh.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.0kj1m.cn/Article/details/gtzgoyewdn.html

[R16] until 等待条件
来源：http://dali.tianlin.xyz/Article/details/gtomyrhfnl.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.hongshengwenyu.top/Article/details/gtfzchbflp.html

[R17] 数组定义与取值
来源：http://dali.aizwys.cn/Article/details/gtgdhaiaml.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.ybcxt.top/Article/details/gtbruyvyhm.html

[R18] 遍历数组
来源：http://dali.shuidangran.top/Article/details/gtdqqpzwxe.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.birdmap.top/Article/details/gtiomxtfnh.html

[R19] 数组长度
来源：http://dali.hnxiangtu.top/Article/details/gtfvcwcevu.html

echo "${#arr[@]}"
来源：http://dali.fzhhl.top/Article/details/gtefnsojre.html

[R20] 关联数组（字典）
来源：http://dali.ywan-chungtsiang.top/Article/details/gtlfwvdqvz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.tanke756.top/Article/details/gteepecqsg.html

[R21] 字符串长度
来源：http://dali.yj20258888.top/Article/details/gtyzmkzome.html

echo "${#s}"
来源：http://dali.jyoumei.cn/Article/details/gtwgoczbns.html

[R22] 截取子串
来源：http://dali.cashguo.top/Article/details/gtitpyicxe.html

echo "${s:0:5}"
来源：http://dali.yuanzhike.top/Article/details/gtbxxobjuw.html

[R23] 字符串替换
来源：http://dali.xziqi.cn/Article/details/gtbpuxsmbq.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jyoumei.cn/Article/details/gtenghrpgk.html

[R24] 大小写转换
来源：http://dali.cashguo.top/Article/details/gtgqflczjm.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.pycfn.com/Article/details/gtgjbsocln.html

[R25] 去后缀 / 去前缀
来源：http://dali.tanke756.top/Article/details/gtkjyrxabd.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.yongpay.top/Article/details/gtomktippl.html

[R26] 命令替换
来源：http://dali.haohaochexian.top/Article/details/gtambsctsv.html

now=$(date +%F); echo "$now"
来源：http://dali.guannengcc.top/Article/details/gtpvlaahlv.html

[R27] 算术展开
来源：http://dali.cucudq.cn/Article/details/gtitxvgnti.html

echo $((1 + 2 * 3))
来源：http://dali.yonumen.top/Article/details/gtyzjcvtzs.html

[R28] 浮点运算
来源：http://dali.yvedp.cn/Article/details/gtaizmktyn.html

echo "scale=2; 10/3" | bc
来源：http://dali.aibaodan.cn/Article/details/gtimssdpgu.html

[R29] 定义函数
来源：http://dali.birdmap.top/Article/details/gtalnprwnq.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jqgfzy.top/Article/details/gtsmxjmmej.html

[R30] 函数返回状态码
来源：http://dali.gzhubu.top/Article/details/gtfkovbncu.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sysykeji.top/Article/details/gteogrzuvi.html

[R31] 局部变量
来源：http://dali.jiagoushi.top/Article/details/gtepmkxhnj.html

f() { local x=1; echo "$x"; }
来源：http://dali.xuetiantiany.cn/Article/details/gtvpzcxefe.html

[R32] 参数个数校验
来源：http://dali.guowangkeji.top/Article/details/gtcdvdrggj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yj20258.top/Article/details/gtvtyevobj.html

[R33] 捕获错误并提示行号
来源：http://dali.havefunace.top/Article/details/gtypfrzohg.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.sufxvd.cn/Article/details/gtvajjjrvr.html

[R34] 退出时清理
来源：http://dali.yanxiufei.cn/Article/details/gtpczqfbjy.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.pycfn.com/Article/details/gtumcnjstu.html

[R35] 后台执行并等待
来源：http://dali.guannengcc.top/Article/details/gtvvqtuniq.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.dashuyun.cn/Article/details/gtxoxfkjsw.html

[R36] 并发执行多个任务
来源：http://dali.zhijiandao.cn/Article/details/gtgxpbdxta.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.ivvv.top/Article/details/gtnxtxxlju.html

[R37] 把输出赋给变量
来源：http://dali.smart0.xyz/Article/details/gtoohgxhjn.html

files=$(ls -1)
来源：http://dali.zhijiandao.cn/Article/details/gtymtinlle.html

[R38] 管道串联
来源：http://dali.cucudq.cn/Article/details/gtunaynnuy.html

cat a.txt | grep -i error | wc -l
来源：http://dali.ehwqpu.com/Article/details/gtxmtewcyd.html

[R39] 重定向标准输出与错误
来源：http://dali.ydzc1.top/Article/details/gtlfhljwvv.html

cmd > out.log 2>&1
来源：http://dali.c1oappe.top/Article/details/gtroqrofwo.html

[R40] 追加写日志
来源：http://dali.svipenyu.cn/Article/details/gthvxhmyhd.html

echo "log" >> out.log
来源：http://dali.hfpthk.cn/Article/details/gtvqxvqijx.html

[R41] 丢弃输出
来源：http://dali.wangdashe.top/Article/details/gtpengcemd.html

cmd >/dev/null 2>&1
来源：http://dali.chenlongwang.top/Article/details/gtnyhrzgjt.html

[R42] 输入重定向
来源：http://dali.pengpengdd.cyou/Article/details/gtxtxnoulb.html

wc -l < a.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtuahurois.html

[R43] 按名字查找文件
来源：http://dali.havefunace.top/Article/details/gtcjydhxho.html

find . -name "*.log" -type f
来源：http://dali.xziqi.cn/Article/details/gtjqrzfcwr.html

[R44] 按修改时间查找
来源：http://dali.yongpay.top/Article/details/gtecncgowq.html

find . -mtime -7 -type f
来源：http://dali.yangfankeji.com/Article/details/gtspgkqffz.html

[R45] 批量删除
来源：http://dali.cqqwz.cn/Article/details/gtwtapjrbd.html

find . -name "*.tmp" -delete
来源：http://dali.cashguo.top/Article/details/gtpqwqfggi.html

[R46] 递归替换文件内容
来源：http://dali.xziqi.cn/Article/details/gtojbuovkv.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.gogol.net.cn/Article/details/gtfvzuvpjt.html

[R47] sed 单行替换
来源：http://dali.hysaishi.cn/Article/details/gtsgsceudt.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.tanke756.top/Article/details/gtfdhpkpxm.html

[R48] awk 取指定列
来源：http://dali.ivvv.top/Article/details/gtpapcndcy.html

awk '{print $1, $3}' a.txt
来源：http://dali.birdmap.top/Article/details/gtwwgqnjoq.html

[R49] awk 带条件
来源：http://dali.zdqjudy.top/Article/details/gtmvwxudyj.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.daria6918.cn/Article/details/gtxzlwgmrt.html

[R50] awk 求和
来源：http://dali.hysaishi.cn/Article/details/gtjivbcmxl.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.sweek.top/Article/details/gtphckjrzx.html

[R51] 排序去重取前几
来源：http://dali.cheryme.top/Article/details/gtcknnucau.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.ywan-chungtsiang.top/Article/details/gtjqwvxprw.html

[R52] 统计行数
来源：http://dali.chenzaomai.com/Article/details/gtnhqpuokq.html

wc -l a.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtfudlipgb.html

[R53] 查看文件头与实时尾
来源：http://dali.yueranfly.top/Article/details/gtvpkooswp.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.shanyushiyangkeji.top/Article/details/gtrofvobek.html

[R54] 比较两个文件
来源：http://dali.sysykeji.top/Article/details/gtzoulifoi.html

diff a.txt b.txt
来源：http://dali.zycfv.cn/Article/details/gtcgzbuvag.html

[R55] 压缩与解压
来源：http://dali.sweek.top/Article/details/gtqybagoie.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.c1oappe.top/Article/details/gtumipdjei.html

[R56] 远程拷贝
来源：http://dali.chenlongwang.top/Article/details/gtzofhlvwy.html

scp file user@host:/path/
来源：http://dali.zhiwuduotai.top/Article/details/gtiklopjku.html

[R57] 远程执行命令
来源：http://dali.feifeiyinyue.top/Article/details/gtbrpqpblz.html

ssh user@host 'uptime'
来源：http://dali.haohaochexian.top/Article/details/gtjrqnfxor.html

[R58] 下载文件
来源：http://dali.hfpthk.cn/Article/details/gtpztcvmly.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yangfankeji.com/Article/details/gtjcvqfnmv.html

[R59] 发 POST JSON
来源：http://dali.cdnleiting.top/Article/details/gtllsyljrv.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.hnxiangtu.top/Article/details/gtaklknijf.html

[R60] 只看 HTTP 状态码
来源：http://dali.shuidangran.top/Article/details/gtpkbojqcs.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.wangdashe.top/Article/details/gtmffpdmln.html

[R61] 磁盘占用
来源：http://dali.svipenyu.cn/Article/details/gtkegzprdj.html

df -h;  du -sh *
来源：http://dali.vqdsnc.cn/Article/details/gtynqigwlx.html

[R62] 找最占空间的文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyzobdmfh.html

du -ah . | sort -rh | head -10
来源：http://dali.xziqi.cn/Article/details/gtfxmcgdmk.html

[R63] 内存与进程
来源：http://dali.shanyushiyangkeji.top/Article/details/gtpsmfmhki.html

free -h;  ps aux | grep nginx
来源：http://dali.birdmap.top/Article/details/gtabrvwgah.html

[R64] 结束进程
来源：http://dali.xinyue.icu/Article/details/gtuwctywiv.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jinqigfzy.top/Article/details/gtnnrrmtve.html

[R65] 查看端口占用
来源：http://dali.birdmap.top/Article/details/gtqzhhhxhl.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.zdqjudy.top/Article/details/gtnzymvtmi.html

[R66] 定时任务
来源：http://dali.smart0.xyz/Article/details/gtieknvrgo.html

crontab -e;  crontab -l
来源：http://dali.hammf.cn/Article/details/gtlyxhobpl.html

[R67] 生成随机十六进制串
来源：http://dali.zhengqikj.top/Article/details/gtzygoxsbn.html

openssl rand -hex 16
来源：http://dali.hongshengwenyu.top/Article/details/gtehmntutv.html

[R68] 计算文件校验值
来源：http://dali.c1oappe.top/Article/details/gtwazebove.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.chenjidiqi.icu/Article/details/gthraqaaqw.html

[R69] 生成随机密码
来源：http://dali.daxiang520.top/Article/details/gtzkjlquql.html

head -c 16 /dev/urandom | base64
来源：http://dali.xziqi.cn/Article/details/gtrdhrjerw.html

[R70] 时间戳与互转
来源：http://dali.shanyushiyangtech.top/Article/details/gteytqypua.html

date +%s;  date -d @1700000000
来源：http://dali.shanyushiyangtech.top/Article/details/gtodxkpfyq.html

[R71] 日期格式化
来源：http://dali.xuanzx.com/Article/details/gtocmlakvs.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.yongpay.top/Article/details/gtozdftxxh.html

[R72] 等待端口就绪
来源：http://dali.ivvv.top/Article/details/gtxzxkesyb.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.shangyingyoupin.top/Article/details/gtlcpaclqt.html

[R73] 分割大日志
来源：http://dali.cdnleiting.top/Article/details/gtcftbtteq.html

split -l 1000 big.log part_
来源：http://dali.pengpengdd.cyou/Article/details/gtshbwpkho.html

[R74] 批量重命名
来源：http://dali.daxiang520.top/Article/details/gtspotyhmh.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.ybcxt.top/Article/details/gtkcquhqez.html

[R75] 导出环境变量
来源：http://dali.chenzaomai.com/Article/details/gtwffevqeu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.hysaishi.cn/Article/details/gtcdszsuux.html

[R76] 使用临时文件
来源：http://dali.andypj.xyz/Article/details/gtuupofhyq.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.smart0.xyz/Article/details/gthlxvwjjh.html

[R77] 读取用户输入
来源：http://dali.ydzc1.top/Article/details/gtketxmlim.html

read -rp "请输入: " ans
来源：http://dali.xinyue.icu/Article/details/gtxercgbcr.html

[R78] 交互式菜单
来源：http://dali.c1oappe.top/Article/details/gtyemhfayp.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.fzhhl.top/Article/details/gtifbuaooc.html

[R79] 解析命令行选项
来源：http://dali.zhijiandao.cn/Article/details/gtnjgiugzk.html


<!-- 参考信息 -->