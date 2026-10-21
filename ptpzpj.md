代发 wailian999

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.cheryme.top/Article/details/gtyasuuyta.html

[Q22] 排序
来源：http://dali.havefunace.top/Article/details/gtvuskledm.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.jinghuilouyu.cn/Article/details/gtulgarqih.html

[Q23] 分页
来源：http://dali.sysykeji.top/Article/details/gtkkpoblxn.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.cdnleiting.top/Article/details/gtfybadgai.html

[Q24] 去重
来源：http://dali.mhx1999.top/Article/details/gtjpipapgk.html

SELECT DISTINCT city FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtaecvxwoe.html

[Q25] 只取前 N 条
来源：http://dali.cheryme.top/Article/details/gtwvccpmze.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.wangshuangyany.cn/Article/details/gtmzccmaof.html

[Q26] 计数
来源：http://dali.gotoacloud.top/Article/details/gtvdxqebnp.html

SELECT COUNT(*) FROM users;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtseexapsb.html

[Q27] 条件计数
来源：http://dali.ybcxt.top/Article/details/gtfmkqqxfp.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.tanke756.top/Article/details/gtfsajbncy.html

[Q28] 求和与平均
来源：http://dali.zhongyouzk.top/Article/details/gtqdnqbnqd.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.pycfn.com/Article/details/gtfwavhvjh.html

[Q29] 最大最小值
来源：http://dali.cucudq.cn/Article/details/gtsfekswxz.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.chenlongwang.top/Article/details/gtwdlrzgoa.html

[Q30] 分组统计
来源：http://dali.tianlin.xyz/Article/details/gtfhrsjuxj.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yongpay.top/Article/details/gtlanspezo.html

[Q31] 分组后过滤
来源：http://dali.hfpthk.cn/Article/details/gthvkfgsmm.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.quarkkingdee.top/Article/details/gthpnbothu.html

[Q32] 分组拼接字符串
来源：http://dali.xinyue.icu/Article/details/gtzbzpamec.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.hysaishi.cn/Article/details/gtskykeary.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.iojbl.cn/Article/details/gtscebykgb.html

[Q33] 多列分组
来源：http://dali.sysykeji.top/Article/details/gtghiywfqj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.chenjidiqi.icu/Article/details/gtwbgqhtfg.html

[Q34] 每组取第一条
来源：http://dali.feifeiyinyue.top/Article/details/gtwqovvlei.html

SELECT * FROM (
来源：http://dali.xuanzx.com/Article/details/gtbeidssep.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.haohaochexian.top/Article/details/gtxkvlrrhp.html

) t WHERE rn = 1;
来源：http://dali.aibaodan.cn/Article/details/gtnzjzmjlx.html

[Q35] 内连接
来源：http://dali.bjfxy.top/Article/details/gtoyjsdipy.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.daxiang520.top/Article/details/gtvniqpccz.html

[Q36] 左连接
来源：http://dali.cqqwz.cn/Article/details/gtzprazdez.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.meibo888.top/Article/details/gtenrabfsq.html

[Q37] 右连接
来源：http://dali.nwbrower.top/Article/details/gtlpftloeu.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtqkjujpxx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.vqdsnc.cn/Article/details/gtclozstzh.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.yueranfly.top/Article/details/gtcorylqpm.html

[Q39] 自连接（查上下级）
来源：http://dali.xinyue.icu/Article/details/gtckodwamu.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.gotoacloud.top/Article/details/gtvprcqyvt.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtqtvkhxgl.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.jlsjyb.cn/Article/details/gthmuqeeyu.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.nanxuanxn.top/Article/details/gtquugitro.html

[Q41] 多表连接
来源：http://dali.meibo888.top/Article/details/gthkaywoxn.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.guowangkeji.top/Article/details/gtftprdbqd.html

JOIN users u ON u.id = o.user_id
来源：http://dali.nanxuanxn.top/Article/details/gtfvmwphuq.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.sufxvd.cn/Article/details/gtejfzqtqv.html

[Q42] 连接条件附加过滤
来源：http://dali.mhx1999.top/Article/details/gtzkfdvosi.html

SELECT u.name, o.amount FROM users u
来源：http://dali.yuxming.cn/Article/details/gtcnhmmqyc.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjyzsvuag.html

[Q43] 标量子查询
来源：http://dali.aibaodan.cn/Article/details/gtaetrarir.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.birdmap.top/Article/details/gtlzatluzb.html

[Q44] IN 子查询
来源：http://dali.zdqjudy.top/Article/details/gtewqsqxzj.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.snrcjt.cn/Article/details/gtmwftbljb.html

[Q45] EXISTS 判断存在
来源：http://dali.316326.xyz/Article/details/gtiitateir.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.sweek.top/Article/details/gtgskkrkvt.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhoulong.xyz/Article/details/gtmcuayexw.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhiwuduotai.top/Article/details/gtykgmapaw.html

[Q47] 与平均值比较
来源：http://dali.birdmap.top/Article/details/gtqtrhgkjc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.guowangkeji.top/Article/details/gtnuqsejgr.html

[Q48] CTE 公用表表达式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtmddurpqb.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cheryme.top/Article/details/gtzkioaemo.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yongpay.top/Article/details/gttbxoeotc.html

[Q49] 更新单行
来源：http://dali.zhiwuduotai.top/Article/details/gtkhrfbgou.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.smart0.xyz/Article/details/gtoexcfjfv.html

[Q50] 批量更新
来源：http://dali.yangfankeji.com/Article/details/gtlzkvcixs.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.pengpengdd.cyou/Article/details/gtpjxsubgj.html

[Q51] 用子查询更新
来源：http://dali.zhongyouzk.top/Article/details/gtjwogzwar.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.sufxvd.cn/Article/details/gtvxcmdxea.html

[Q52] 删除指定行
来源：http://dali.jiagoushi.top/Article/details/gthuvxaidw.html

DELETE FROM users WHERE id = 10;
来源：http://dali.9152youxi.cn/Article/details/gtnaskdlmc.html

[Q53] 按条件删除
来源：http://dali.hysaishi.cn/Article/details/gtwlfqjwxt.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.zhongyouzk.top/Article/details/gtigmwmhva.html

[Q54] 清空表
来源：http://dali.0kj1m.cn/Article/details/gthuikrzaz.html

TRUNCATE TABLE logs;
来源：http://dali.svipenyu.cn/Article/details/gtunmwsedm.html

[Q55] 排名（并列占位）
来源：http://dali.shuidangran.top/Article/details/gtjrygarlw.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.ywan-chungtsiang.top/Article/details/gtwgitvpsp.html

[Q56] 密集排名（并列不占位）
来源：http://dali.dianchejie.cn/Article/details/gtvafmmbso.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.nanxinkj.top/Article/details/gtqcbuqjhs.html

[Q57] 行号
来源：http://dali.yj20258.top/Article/details/gtyxynpgww.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.zdqjudy.top/Article/details/gtzyngceie.html

[Q58] 累计求和
来源：http://dali.ybcxt.top/Article/details/gtmoefinlq.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.nanxuanxn.top/Article/details/gttbgmvdys.html

[Q59] 分组内累计
来源：http://dali.ivvv.top/Article/details/gtzdorcxfj.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.ydzc1.top/Article/details/gtbkmeplow.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhaomingkeji.xyz/Article/details/gtsowxllum.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.mhx1999.top/Article/details/gtspyfhzkq.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.hnqzz.top/Article/details/gtfolkdpiw.html

[Q61] 移动平均
来源：http://dali.xuanzx.com/Article/details/gtmtnbygsu.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.redwolf501.top/Article/details/gtkpxqdnyw.html

[Q62] 分组占比
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtdtmqsims.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.jqgufenzy.top/Article/details/gtrysahbmk.html

[Q63] 开启事务
来源：http://dali.gogol.net.cn/Article/details/gtjiszysfe.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.guowangkeji.top/Article/details/gtiimlxdqc.html

[Q64] 提交事务
来源：http://dali.yvedp.cn/Article/details/gtggupowuc.html

COMMIT;
来源：http://dali.gotoacloud.top/Article/details/gtfqslyslz.html

[Q65] 回滚事务
来源：http://dali.cashguo.top/Article/details/gtpektgxlt.html

ROLLBACK;
来源：http://dali.wangshuangyany.cn/Article/details/gtjcmvknio.html

[Q66] 行锁查询
来源：http://dali.chenjidiqi.icu/Article/details/gtkxgwnbiu.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.ybcxt.top/Article/details/gtpyphyaqm.html

[Q67] 设置隔离级别
来源：http://dali.gotoacloud.top/Article/details/gtvhygdkai.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.yj202588.top/Article/details/gtfbdaisfz.html

[Q68] 保存点
来源：http://dali.zhixingplan.top/Article/details/gtgjlmmdkm.html

SAVEPOINT sp1;
来源：http://dali.jqgfzy.top/Article/details/gtcwuqygon.html

ROLLBACK TO sp1;
来源：http://dali.jqgufenzy.top/Article/details/gtnoqbbixu.html

[Q69] 查看执行计划
来源：http://dali.jinqigfzy.top/Article/details/gtmofeeglr.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.gaohongyu789.top/Article/details/gttflycsaz.html

[Q70] 更新统计信息
来源：http://dali.cdnleiting.top/Article/details/gtlgjfkllm.html

ANALYZE TABLE users;
来源：http://dali.shanyushiyangtech.top/Article/details/gtuteqkcvz.html

[Q71] 查看建表语句
来源：http://dali.jianghu66.top/Article/details/gtuejicdyw.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.daxiang520.top/Article/details/gtrelawlcm.html

[Q72] 查看索引
来源：http://dali.zycfv.cn/Article/details/gtxrobcxtl.html

SHOW INDEX FROM users;
来源：http://dali.yongpay.top/Article/details/gtccbhdjkm.html

[Q73] 查看表状态
来源：http://dali.andypj.xyz/Article/details/gtutzcurfw.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.cqqwz.cn/Article/details/gtjkscbqdl.html

[Q74] 强制使用索引
来源：http://dali.yj20258.top/Article/details/gtityigddf.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.zhoulong.xyz/Article/details/gtaxjrpfka.html

[Q75] 日期格式化
来源：http://dali.cucudq.cn/Article/details/gtlslqekzh.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtxdzorguj.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.sweek.top/Article/details/gtbxmujlgr.html

[Q76] 按天统计
来源：http://dali.tianlin.xyz/Article/details/gtribgmxit.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.zhongyouzk.top/Article/details/gtvuzkqhja.html

[Q77] 时间加减
来源：http://dali.ivvv.top/Article/details/gtfihpocqq.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyncckumz.html

[Q78] 当前时间
来源：http://dali.xinyue.icu/Article/details/gtqncscoba.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.vqdsnc.cn/Article/details/gtbfyuunac.html

[Q79] 字符串拼接
来源：http://dali.xylfe.cn/Article/details/gtgqumcvms.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.fengsongda.top/Article/details/gtwlhmlhzh.html

[Q80] 字符串截取
来源：http://dali.xuanzx.com/Article/details/gtloiogaky.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.yangfankeji.com/Article/details/gtzxqjducu.html

[Q81] 字符串替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtlbyymizm.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.daxiang520.top/Article/details/gtjudmlqzj.html

[Q82] 字符长度与字节长度
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyqvepagk.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.jinqigufen.top/Article/details/gturwhtmpv.html

[Q83] 大小写转换
来源：http://dali.chenjidiqi.icu/Article/details/gtepbduqcz.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.jinghuilouyu.cn/Article/details/gtxyduflxw.html

[Q84] 去除首尾空格
来源：http://dali.quarkkingdee.top/Article/details/gtvvqyvcrg.html

SELECT TRIM(name) FROM users;
来源：http://dali.zhoulong.xyz/Article/details/gttdoprumg.html

[Q85] 数值取整
来源：http://dali.ppjwa.cn/Article/details/gtrqirlvug.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.yj202588.top/Article/details/gteeluaaqo.html

[Q86] 读取 JSON 字段
来源：http://dali.gotoacloud.top/Article/details/gtjwiympuh.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.xuanzx.com/Article/details/gtmxdgpocp.html

[Q87] JSON 字段做条件
来源：http://dali.tanke756.top/Article/details/gthgppgvhj.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.guannengcc.top/Article/details/gtzondvzyw.html

[Q88] 行转列（条件聚合）
来源：http://dali.bjfxy.top/Article/details/gtloalzaxp.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.yueranfly.top/Article/details/gtpymbdcmy.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.pycfn.com/Article/details/gtwkxcsebe.html

[Q89] 判断表是否存在
来源：http://dali.hongshengwenyu.top/Article/details/gtmwkqxudv.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.daria6918.cn/Article/details/gtdymfqugr.html

[Q90] 生成序号列
来源：http://dali.xinyue.icu/Article/details/gtznelxref.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtkhzbuhup.html

================================================================================
来源：http://dali.yueranfly.top/Article/details/gtldidfqka.html

R. Bash 专题
来源：http://dali.yangfankeji.com/Article/details/gtdtbxvsxe.html

================================================================================
来源：http://dali.havefunace.top/Article/details/gtnuemeeij.html

[R01] shebang 与严格模式
来源：http://dali.fzhhl.top/Article/details/gtkblpqyus.html

#!/usr/bin/env bash
来源：http://dali.ydzc1.top/Article/details/gtfgvooalh.html

set -euo pipefail
来源：http://dali.pengpengdd.cyou/Article/details/gtotryfxpy.html

[R02] 变量赋值与使用
来源：http://dali.ehwqpu.com/Article/details/gtgexaaylr.html

name="Tom"; echo "$name"
来源：http://dali.hfpthk.cn/Article/details/gthoaddejy.html

[R03] 只读变量
来源：http://dali.andypj.xyz/Article/details/gtduleyjpe.html

readonly PI=3.14
来源：http://dali.jinqigufen.top/Article/details/gttbbknzxa.html

[R04] 位置参数
来源：http://dali.zhengqikj.top/Article/details/gtartjkrhz.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.316326.xyz/Article/details/gtoaweniak.html

[R05] 参数默认值
来源：http://dali.snrcjt.cn/Article/details/gtsmfmozwq.html

name="${1:-default}"
来源：http://dali.hongshengwenyu.top/Article/details/gtfdhzeogp.html

[R06] 判断命令是否存在
来源：http://dali.yvedp.cn/Article/details/gtizhqpqwp.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.wangdashe.top/Article/details/gtauzudvng.html

[R07] if 判断文件
来源：http://dali.wangdashe.top/Article/details/gtmwyhfnfl.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.chenjidiqi.icu/Article/details/gtxbgewrmn.html

[R08] 数值比较
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtykmcbfic.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.xinyue.icu/Article/details/gteupcwhmj.html

[R09] 字符串比较
来源：http://dali.redwolf501.top/Article/details/gthrkaxalh.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.dashuyun.cn/Article/details/gtzahjwsag.html

[R10] 正则匹配
来源：http://dali.zhijiandao.cn/Article/details/gtfuvcqryu.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.yj202588.top/Article/details/gtkpudbfez.html

[R11] case 多分支
来源：http://dali.yuanzhike.top/Article/details/gtzukzpiey.html

case "$1" in
来源：http://dali.cucudq.cn/Article/details/gtfajfhvsc.html

start) echo "启动" ;;
来源：http://dali.xuetiantiany.cn/Article/details/gtitiuwlnu.html

stop)  echo "停止" ;;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtrazaguse.html

*)     echo "未知命令" ;;
来源：http://dali.jinyuanbaomall.cn/Article/details/gtjzgedxmt.html

esac
来源：http://dali.zhixingplan.top/Article/details/gtcdhqtmzw.html

[R12] for 遍历文件
来源：http://dali.yj20258888.top/Article/details/gtsvexztzs.html

for f in *.txt; do echo "$f"; done
来源：http://dali.jinyuanbaomall.cn/Article/details/gtkxahogpa.html

[R13] for 计数循环
来源：http://dali.havefunace.top/Article/details/gtvlmjzyhw.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.nanxinkj.top/Article/details/gtmiixcfdd.html

[R14] C 风格 for
来源：http://dali.daxiang520.top/Article/details/gtqjqofogq.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cashguo.top/Article/details/gtesudjznp.html

[R15] while 逐行读文件
来源：http://dali.mhx1999.top/Article/details/gtkmxanxja.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.ybcxt.top/Article/details/gteyzymsud.html

[R16] until 等待条件
来源：http://dali.xuanzx.com/Article/details/gtqitgsxkt.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.jqgfzy.top/Article/details/gtdemfbzzo.html

[R17] 数组定义与取值
来源：http://dali.ywan-chungtsiang.top/Article/details/gtpqmmnkwr.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.fengsongda.top/Article/details/gtqadwixjp.html

[R18] 遍历数组
来源：http://dali.zhijiandao.cn/Article/details/gtyiqzfkyv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.xuetiantiany.cn/Article/details/gtynoxrfbm.html

[R19] 数组长度
来源：http://dali.yuanzhike.top/Article/details/gtqlejlvns.html

echo "${#arr[@]}"
来源：http://dali.smart0.xyz/Article/details/gtopuwdami.html

[R20] 关联数组（字典）
来源：http://dali.jlsjyb.cn/Article/details/gtiazfdfzh.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.yj20258.top/Article/details/gtilyssuvk.html

[R21] 字符串长度
来源：http://dali.hysaishi.cn/Article/details/gtybptjhhi.html

echo "${#s}"
来源：http://dali.tianlin.xyz/Article/details/gtmnjsfpjz.html

[R22] 截取子串
来源：http://dali.jianghu66.top/Article/details/gtkpylikvq.html

echo "${s:0:5}"
来源：http://dali.hnxiangtu.top/Article/details/gthytaeixr.html

[R23] 字符串替换
来源：http://dali.0kj1m.cn/Article/details/gtuqdzehje.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hysaishi.cn/Article/details/gtcdbftghy.html

[R24] 大小写转换
来源：http://dali.zhaomingkeji.xyz/Article/details/gtjqqcpzux.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.ehwqpu.com/Article/details/gtwtlzkjth.html

[R25] 去后缀 / 去前缀
来源：http://dali.guowangkeji.top/Article/details/gtczhnjnda.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.jinqigfzy.top/Article/details/gtjfpjohrf.html

[R26] 命令替换
来源：http://dali.hywenlv.cn/Article/details/gtgvpsqpvp.html

now=$(date +%F); echo "$now"
来源：http://dali.ybcxt.top/Article/details/gtbjyomtje.html

[R27] 算术展开
来源：http://dali.tanke756.top/Article/details/gtbpfslxzp.html

echo $((1 + 2 * 3))
来源：http://dali.feifeiyinyue.top/Article/details/gtotedqpax.html

[R28] 浮点运算
来源：http://dali.shanyushiyangkeji.top/Article/details/gtayuxbyvu.html

echo "scale=2; 10/3" | bc
来源：http://dali.daxiang520.top/Article/details/gtsknsvplm.html

[R29] 定义函数
来源：http://dali.fzhhl.top/Article/details/gtdpobyubw.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.hnqzz.top/Article/details/gtacdpzgpe.html

[R30] 函数返回状态码
来源：http://dali.yvedp.cn/Article/details/gtdivfpend.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.svipenyu.cn/Article/details/gtfyqqjjgc.html

[R31] 局部变量
来源：http://dali.zhiwuduotai.top/Article/details/gtsvjeuonb.html

f() { local x=1; echo "$x"; }
来源：http://dali.zhixingplan.top/Article/details/gthoxdugqo.html

[R32] 参数个数校验
来源：http://dali.meibo888.top/Article/details/gtmbdhnqlj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.yuanzhike.top/Article/details/gtocgvgypw.html

[R33] 捕获错误并提示行号
来源：http://dali.jinqigfzy.top/Article/details/gtukdhzlqv.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.fengsongda.top/Article/details/gttytsekjk.html

[R34] 退出时清理
来源：http://dali.tanke756.top/Article/details/gtodwlxeup.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.9152youxi.cn/Article/details/gtaounkghn.html

[R35] 后台执行并等待
来源：http://dali.chenjidiqi.icu/Article/details/gtcpzashns.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.hnqzz.top/Article/details/gtawxdgrzl.html

[R36] 并发执行多个任务
来源：http://dali.smart0.xyz/Article/details/gtfzffbbqq.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nwbrower.top/Article/details/gtoqgzhhbc.html

[R37] 把输出赋给变量
来源：http://dali.sxryk.cn/Article/details/gtlhihlcah.html

files=$(ls -1)
来源：http://dali.snrcjt.cn/Article/details/gtiswgyipm.html

[R38] 管道串联
来源：http://dali.yueranfly.top/Article/details/gtbhmxawds.html

cat a.txt | grep -i error | wc -l
来源：http://dali.nwbrower.top/Article/details/gtvsxubqzt.html

[R39] 重定向标准输出与错误
来源：http://dali.tianlin.xyz/Article/details/gtvvbzkqkv.html

cmd > out.log 2>&1
来源：http://dali.gzhubu.top/Article/details/gtalqhifsf.html

[R40] 追加写日志
来源：http://dali.smart0.xyz/Article/details/gtfcgpngoi.html

echo "log" >> out.log
来源：http://dali.fengsongda.top/Article/details/gtvpyidfel.html

[R41] 丢弃输出
来源：http://dali.redwolf501.top/Article/details/gtmeizojqd.html

cmd >/dev/null 2>&1
来源：http://dali.zdqjudy.top/Article/details/gtrkzmqjnv.html

[R42] 输入重定向
来源：http://dali.yongpay.top/Article/details/gtizgwuqmx.html

wc -l < a.txt
来源：http://dali.quarkkingdee.top/Article/details/gthyrfpwzi.html

[R43] 按名字查找文件
来源：http://dali.mhx1999.top/Article/details/gtgbrctcrh.html

find . -name "*.log" -type f
来源：http://dali.shuidangran.top/Article/details/gtrdmzfnrp.html

[R44] 按修改时间查找
来源：http://dali.chenlongwang.top/Article/details/gtzftdszii.html

find . -mtime -7 -type f
来源：http://dali.meibo888.top/Article/details/gtjbbgtitp.html

[R45] 批量删除
来源：http://dali.xziqi.cn/Article/details/gtqrmdrbdt.html

find . -name "*.tmp" -delete
来源：http://dali.zhoulong.xyz/Article/details/gtcamhyjft.html

[R46] 递归替换文件内容
来源：http://dali.hywenlv.cn/Article/details/gtdvocefkh.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.tianlin.xyz/Article/details/gtefkiwyre.html

[R47] sed 单行替换
来源：http://dali.tanke756.top/Article/details/gtjihgnnrr.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.zycfv.cn/Article/details/gtazqyujwr.html

[R48] awk 取指定列
来源：http://dali.snrcjt.cn/Article/details/gtqaqicwce.html

awk '{print $1, $3}' a.txt
来源：http://dali.kuanghao11.cn/Article/details/gtjslnvhle.html

[R49] awk 带条件
来源：http://dali.ywan-chungtsiang.top/Article/details/gtmrimlhrv.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.jinqigfzy.top/Article/details/gtycuegset.html

[R50] awk 求和
来源：http://dali.sufxvd.cn/Article/details/gtbedgggmm.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.smart0.xyz/Article/details/gttdzktrag.html

[R51] 排序去重取前几
来源：http://dali.fzhhl.top/Article/details/gtilsjkdrk.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.jyoumei.cn/Article/details/gtkhwgapvg.html

[R52] 统计行数
来源：http://dali.ybcxt.top/Article/details/gtlcfzswot.html

wc -l a.txt
来源：http://dali.sysykeji.top/Article/details/gtfljbzmsc.html

[R53] 查看文件头与实时尾
来源：http://dali.smart0.xyz/Article/details/gtfveauomk.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.gaohongyu789.top/Article/details/gtsrzhstng.html

[R54] 比较两个文件
来源：http://dali.hfpthk.cn/Article/details/gtbvqozcoy.html

diff a.txt b.txt
来源：http://dali.jiagoushi.top/Article/details/gtpnbnsqfi.html

[R55] 压缩与解压
来源：http://dali.zhaomingkeji.xyz/Article/details/gthheqrxrv.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.cqqwz.cn/Article/details/gtpisajaoh.html

[R56] 远程拷贝
来源：http://dali.jqgfzy.top/Article/details/gtmprndxqy.html

scp file user@host:/path/
来源：http://dali.pengpengdd.cyou/Article/details/gtlznaulvf.html

[R57] 远程执行命令
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtenfflswv.html

ssh user@host 'uptime'
来源：http://dali.aibaodan.cn/Article/details/gtnrihiqjw.html

[R58] 下载文件
来源：http://dali.jinqigufen.top/Article/details/gtwykjfafs.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yongpay.top/Article/details/gtpubarlhv.html

[R59] 发 POST JSON
来源：http://dali.yj20258.top/Article/details/gtgbpxqbfm.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.guannengcc.top/Article/details/gtgvonzvsa.html

[R60] 只看 HTTP 状态码
来源：http://dali.gaohongyu789.top/Article/details/gtvnmtdbzv.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.cdnleiting.top/Article/details/gtbazunivt.html

[R61] 磁盘占用
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnfnzvxxa.html

df -h;  du -sh *
来源：http://dali.ybcxt.top/Article/details/gtbbpqfmoc.html

[R62] 找最占空间的文件
来源：http://dali.yvedp.cn/Article/details/gtdwmglvqq.html

du -ah . | sort -rh | head -10
来源：http://dali.0kj1m.cn/Article/details/gtyjkdcdqn.html

[R63] 内存与进程
来源：http://dali.fzhhl.top/Article/details/gtzgtndnsz.html

free -h;  ps aux | grep nginx
来源：http://dali.shanyushiyangtech.top/Article/details/gtucmazkom.html

[R64] 结束进程
来源：http://dali.jianghu66.top/Article/details/gtmtigvfkj.html

kill -9 $(pgrep -f app.py)
来源：http://dali.ppjwa.cn/Article/details/gtchkkxryk.html

[R65] 查看端口占用
来源：http://dali.pengpengdd.cyou/Article/details/gtpevcbnhc.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.jiagoushi.top/Article/details/gtrknnaubx.html

[R66] 定时任务
来源：http://dali.zhengqikj.top/Article/details/gthyfbusdt.html

crontab -e;  crontab -l
来源：http://dali.kuanghao11.cn/Article/details/gtmalvqyuj.html

[R67] 生成随机十六进制串
来源：http://dali.shanyushiyangkeji.top/Article/details/gtbauaurct.html

openssl rand -hex 16
来源：http://dali.shanyushiyangtech.top/Article/details/gttktygynh.html

[R68] 计算文件校验值
来源：http://dali.aizwys.cn/Article/details/gtlsxnnmsr.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jinqigfzy.top/Article/details/gtilzfakrq.html

[R69] 生成随机密码
来源：http://dali.yvedp.cn/Article/details/gtepviphmo.html

head -c 16 /dev/urandom | base64
来源：http://dali.yangfankeji.com/Article/details/gtbqddzprv.html

[R70] 时间戳与互转
来源：http://dali.gzhubu.top/Article/details/gtobgcqywf.html

date +%s;  date -d @1700000000
来源：http://dali.yueranfly.top/Article/details/gtrkmelnvy.html

[R71] 日期格式化
来源：http://dali.iojbl.cn/Article/details/gtrvaqnykq.html


<!-- 参考信息 -->