代发 wailian999

SELECT * FROM users WHERE email IS NULL;
来源：http://dali.nanxinkj.top/Article/details/gtdoqfucaa.html

[Q22] 排序
来源：http://dali.gogol.net.cn/Article/details/gtbyffrtqw.html

SELECT * FROM users ORDER BY age DESC, id ASC;
来源：http://dali.gogol.net.cn/Article/details/gtwyjgbreg.html

[Q23] 分页
来源：http://dali.yueranfly.top/Article/details/gtixcszowo.html

SELECT * FROM users ORDER BY id LIMIT 20 OFFSET 40;
来源：http://dali.ivvv.top/Article/details/gtxgkkvmvg.html

[Q24] 去重
来源：http://dali.yj20258.top/Article/details/gtlqhqtjyt.html

SELECT DISTINCT city FROM users;
来源：http://dali.bjfxy.top/Article/details/gtrrcsuxgp.html

[Q25] 只取前 N 条
来源：http://dali.havefunace.top/Article/details/gtabjgitix.html

SELECT * FROM users LIMIT 10;      -- SQL Server: SELECT TOP 10 *
来源：http://dali.ywan-chungtsiang.top/Article/details/gtyedytgze.html

[Q26] 计数
来源：http://dali.guowangkeji.top/Article/details/gtjryhwtrn.html

SELECT COUNT(*) FROM users;
来源：http://dali.yuxming.cn/Article/details/gtgpsyrpwv.html

[Q27] 条件计数
来源：http://dali.yj20258888.top/Article/details/gtecrmngyl.html

SELECT COUNT(CASE WHEN age > 18 THEN 1 END) AS adults FROM users;
来源：http://dali.zhijiandao.cn/Article/details/gtjyztaybx.html

[Q28] 求和与平均
来源：http://dali.jinghuilouyu.cn/Article/details/gtgywispxf.html

SELECT SUM(amount), AVG(amount) FROM orders;
来源：http://dali.daxiang520.top/Article/details/gtojioienu.html

[Q29] 最大最小值
来源：http://dali.daria6918.cn/Article/details/gtzexyeffb.html

SELECT MAX(age), MIN(age) FROM users;
来源：http://dali.redwolf501.top/Article/details/gtxjqywelj.html

[Q30] 分组统计
来源：http://dali.guannengcc.top/Article/details/gtolodqhwb.html

SELECT city, COUNT(*) FROM users GROUP BY city;
来源：http://dali.yangfankeji.com/Article/details/gtupjykkca.html

[Q31] 分组后过滤
来源：http://dali.tanke756.top/Article/details/gtbkuktldo.html

SELECT city, COUNT(*) AS c FROM users GROUP BY city HAVING c > 10;
来源：http://dali.guannengcc.top/Article/details/gtodcbrbkk.html

[Q32] 分组拼接字符串
来源：http://dali.hfpthk.cn/Article/details/gtzrlyzwlq.html

SELECT city, GROUP_CONCAT(name) FROM users GROUP BY city;
来源：http://dali.xuanzx.com/Article/details/gtfgpdqzwt.html

-- PostgreSQL: STRING_AGG(name, ',')
来源：http://dali.ywan-chungtsiang.top/Article/details/gtkaicwxww.html

[Q33] 多列分组
来源：http://dali.chenjidiqi.icu/Article/details/gtrisnsrsj.html

SELECT city, gender, COUNT(*) FROM users GROUP BY city, gender;
来源：http://dali.jyoumei.cn/Article/details/gtbneamsbn.html

[Q34] 每组取第一条
来源：http://dali.chenlongwang.top/Article/details/gtdpmzmvsh.html

SELECT * FROM (
来源：http://dali.jinqigufen.top/Article/details/gtwctxlwwc.html

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.sufxvd.cn/Article/details/gtdqufsrsw.html

) t WHERE rn = 1;
来源：http://dali.cdnleiting.top/Article/details/gtqekuztvy.html

[Q35] 内连接
来源：http://dali.tianlin.xyz/Article/details/gtdadtkizq.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.hywenlv.cn/Article/details/gthilvmslh.html

[Q36] 左连接
来源：http://dali.daria6918.cn/Article/details/gtuwtzcrru.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.ybcxt.top/Article/details/gtmfrtjfmd.html

[Q37] 右连接
来源：http://dali.yueranfly.top/Article/details/gtbxynhnoo.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.shzxlz.cn/Article/details/gtkycdvstx.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.xuanzx.com/Article/details/gtlzkvqyet.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.hnqzz.top/Article/details/gtggvcqitr.html

[Q39] 自连接（查上下级）
来源：http://dali.zdqjudy.top/Article/details/gtzcjxapav.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.ppjwa.cn/Article/details/gtyodvgsnb.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.pengpengdd.cyou/Article/details/gtebzhhygv.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.yangfankeji.com/Article/details/gtqwpzzgcg.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.haohaochexian.top/Article/details/gtcgkmryzp.html

[Q41] 多表连接
来源：http://dali.tian-w.cn/Article/details/gtsouypwrf.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.c1oappe.top/Article/details/gtoqeudibp.html

JOIN users u ON u.id = o.user_id
来源：http://dali.jyoumei.cn/Article/details/gtqtbfbnti.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.pengpengdd.cyou/Article/details/gtzcsweskz.html

[Q42] 连接条件附加过滤
来源：http://dali.cheryme.top/Article/details/gtgsurxpzq.html

SELECT u.name, o.amount FROM users u
来源：http://dali.nanxinkj.top/Article/details/gtowcnyrmp.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.aibaodan.cn/Article/details/gtiupjhxkd.html

[Q43] 标量子查询
来源：http://dali.c1oappe.top/Article/details/gtnctrvtfu.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.ybcxt.top/Article/details/gtvexjmvwy.html

[Q44] IN 子查询
来源：http://dali.shuidangran.top/Article/details/gttfysocvs.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.cashguo.top/Article/details/gtnqdrzoxi.html

[Q45] EXISTS 判断存在
来源：http://dali.tianlin.xyz/Article/details/gthbivfxau.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.gzhubu.top/Article/details/gteeoqbpvm.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.zhixingplan.top/Article/details/gtkvmslmgd.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.zhijiandao.cn/Article/details/gtppkmkhnf.html

[Q47] 与平均值比较
来源：http://dali.nwbrower.top/Article/details/gtttysibsc.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.fengsongda.top/Article/details/gtceugmibq.html

[Q48] CTE 公用表表达式
来源：http://dali.shangyingyoupin.top/Article/details/gtljxnzpdj.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cqqwz.cn/Article/details/gtyrkmcrtq.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.yueranfly.top/Article/details/gtomgivmnf.html

[Q49] 更新单行
来源：http://dali.haohaochexian.top/Article/details/gttzirycrp.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.vqdsnc.cn/Article/details/gtbkfppcbt.html

[Q50] 批量更新
来源：http://dali.chenjidiqi.icu/Article/details/gtcygxmiue.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.hammf.cn/Article/details/gtushokylj.html

[Q51] 用子查询更新
来源：http://dali.yongpay.top/Article/details/gthepcvbvp.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.ybcxt.top/Article/details/gtwmdiylwc.html

[Q52] 删除指定行
来源：http://dali.cucudq.cn/Article/details/gtgvljvtou.html

DELETE FROM users WHERE id = 10;
来源：http://dali.daria6918.cn/Article/details/gtrqrbtghs.html

[Q53] 按条件删除
来源：http://dali.yongpay.top/Article/details/gtziclkabm.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.ydzc1.top/Article/details/gtmbvtantl.html

[Q54] 清空表
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgdgpzqmk.html

TRUNCATE TABLE logs;
来源：http://dali.birdmap.top/Article/details/gtfwdyhice.html

[Q55] 排名（并列占位）
来源：http://dali.cheryme.top/Article/details/gtdrubettk.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.yonumen.top/Article/details/gtwsadpqbf.html

[Q56] 密集排名（并列不占位）
来源：http://dali.9152youxi.cn/Article/details/gtspreqcfw.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.tanke756.top/Article/details/gtybmgnwcf.html

[Q57] 行号
来源：http://dali.bjfxy.top/Article/details/gtsywvedhi.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.nwbrower.top/Article/details/gtncpbysex.html

[Q58] 累计求和
来源：http://dali.hnxiangtu.top/Article/details/gtpdzudxsy.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.jinqigfzy.top/Article/details/gtnivjoafa.html

[Q59] 分组内累计
来源：http://dali.quarkkingdee.top/Article/details/gtxmeihnvi.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gtsgwuknrj.html

[Q60] 取上一行 / 下一行
来源：http://dali.zhongyouzk.top/Article/details/gtmjobrwsm.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.cqqwz.cn/Article/details/gtswmgwruy.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.jlsjyb.cn/Article/details/gtxtqiwzjx.html

[Q61] 移动平均
来源：http://dali.zhaomingkeji.xyz/Article/details/gtwkjlzwjv.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.hammf.cn/Article/details/gtaexqzukp.html

[Q62] 分组占比
来源：http://dali.xziqi.cn/Article/details/gtbrqrypmk.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.yueranfly.top/Article/details/gtvdfgcitc.html

[Q63] 开启事务
来源：http://dali.redwolf501.top/Article/details/gtrllzztyv.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.tian-w.cn/Article/details/gtpbiahjkr.html

[Q64] 提交事务
来源：http://dali.daria6918.cn/Article/details/gtumhsjbfi.html

COMMIT;
来源：http://dali.316326.xyz/Article/details/gtgpkojmmo.html

[Q65] 回滚事务
来源：http://dali.snrcjt.cn/Article/details/gtozuispae.html

ROLLBACK;
来源：http://dali.yueranfly.top/Article/details/gthobqhvig.html

[Q66] 行锁查询
来源：http://dali.birdmap.top/Article/details/gtzcezmbeq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.yueranfly.top/Article/details/gtpviyegvz.html

[Q67] 设置隔离级别
来源：http://dali.sxryk.cn/Article/details/gtlpdaewze.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.birdmap.top/Article/details/gteiwwwqnd.html

[Q68] 保存点
来源：http://dali.nanxuanxn.top/Article/details/gttkvfepfm.html

SAVEPOINT sp1;
来源：http://dali.0kj1m.cn/Article/details/gtdrrqaorw.html

ROLLBACK TO sp1;
来源：http://dali.shanyushiyangtech.top/Article/details/gtpixstltg.html

[Q69] 查看执行计划
来源：http://dali.yuanzhike.top/Article/details/gtahcovpti.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.yvedp.cn/Article/details/gtkyixvgtu.html

[Q70] 更新统计信息
来源：http://dali.hongshengwenyu.top/Article/details/gthupjjhdl.html

ANALYZE TABLE users;
来源：http://dali.ydzc1.top/Article/details/gtlxvvxqqj.html

[Q71] 查看建表语句
来源：http://dali.smart0.xyz/Article/details/gtaijtcvvm.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.nanxuanxn.top/Article/details/gtitzhmjgw.html

[Q72] 查看索引
来源：http://dali.kuanghao11.cn/Article/details/gtvcsmbvpt.html

SHOW INDEX FROM users;
来源：http://dali.meibo888.top/Article/details/gtukjehitr.html

[Q73] 查看表状态
来源：http://dali.hysaishi.cn/Article/details/gtzqghuumj.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.xziqi.cn/Article/details/gtbeblpjog.html

[Q74] 强制使用索引
来源：http://dali.yanxiufei.cn/Article/details/gtpipujatn.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.yanxiufei.cn/Article/details/gtcanxyjbm.html

[Q75] 日期格式化
来源：http://dali.chenzaomai.com/Article/details/gtvwlqusrf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.xinyue.icu/Article/details/gtajtqjzuu.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.c1oappe.top/Article/details/gtccmpinip.html

[Q76] 按天统计
来源：http://dali.yj20258888.top/Article/details/gtmlybznhf.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.chenzaomai.com/Article/details/gttxbhcjyh.html

[Q77] 时间加减
来源：http://dali.sysykeji.top/Article/details/gtodgpzumv.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.shanyushiyangtech.top/Article/details/gtmogevoxx.html

[Q78] 当前时间
来源：http://dali.redwolf501.top/Article/details/gtacueqjov.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.jinqigufen.top/Article/details/gtebwtorns.html

[Q79] 字符串拼接
来源：http://dali.ppjwa.cn/Article/details/gtklfgrjkt.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.birdmap.top/Article/details/gtzwgrtgus.html

[Q80] 字符串截取
来源：http://dali.hongshengwenyu.top/Article/details/gtupkfanwc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.mhx1999.top/Article/details/gtthpgsdxa.html

[Q81] 字符串替换
来源：http://dali.jinyuanbaomall.cn/Article/details/gtirmuuwzf.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.fzhhl.top/Article/details/gtemkjczyu.html

[Q82] 字符长度与字节长度
来源：http://dali.mhx1999.top/Article/details/gteplklskg.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.yueranfly.top/Article/details/gtmyzngpdh.html

[Q83] 大小写转换
来源：http://dali.shangyingyoupin.top/Article/details/gtkkuftfuc.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.zhixingplan.top/Article/details/gtnhiwttfm.html

[Q84] 去除首尾空格
来源：http://dali.dashuyun.cn/Article/details/gtolvfbogi.html

SELECT TRIM(name) FROM users;
来源：http://dali.hnqzz.top/Article/details/gtienutqab.html

[Q85] 数值取整
来源：http://dali.vqdsnc.cn/Article/details/gtrfuqvmho.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.chenlongwang.top/Article/details/gtkgwpmvdb.html

[Q86] 读取 JSON 字段
来源：http://dali.yj20258888.top/Article/details/gttexpwwfu.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.yuxming.cn/Article/details/gtvhuvjbkw.html

[Q87] JSON 字段做条件
来源：http://dali.guowangkeji.top/Article/details/gtsofulooz.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.cashguo.top/Article/details/gtwvduxtdt.html

[Q88] 行转列（条件聚合）
来源：http://dali.yuanzhike.top/Article/details/gtmzfbbwug.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.zhiwuduotai.top/Article/details/gtiupilonk.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.guannengcc.top/Article/details/gtgqcztstn.html

[Q89] 判断表是否存在
来源：http://dali.tian-w.cn/Article/details/gtoyjkhagf.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.gotoacloud.top/Article/details/gtlpqqfsgs.html

[Q90] 生成序号列
来源：http://dali.xuetiantiany.cn/Article/details/gtqgotxzhu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.zhiwuduotai.top/Article/details/gtwfgiwuea.html

================================================================================
来源：http://dali.xziqi.cn/Article/details/gtflkoiohd.html

R. Bash 专题
来源：http://dali.jinghuilouyu.cn/Article/details/gtkpsgivfp.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtbangwffo.html

[R01] shebang 与严格模式
来源：http://dali.birdmap.top/Article/details/gtbpvntcdr.html

#!/usr/bin/env bash
来源：http://dali.guannengcc.top/Article/details/gtyghexgad.html

set -euo pipefail
来源：http://dali.havefunace.top/Article/details/gtuyoyeczy.html

[R02] 变量赋值与使用
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtzyhiofmw.html

name="Tom"; echo "$name"
来源：http://dali.yj20258888.top/Article/details/gtjxuogalm.html

[R03] 只读变量
来源：http://dali.nanxuanxn.top/Article/details/gtkpthchno.html

readonly PI=3.14
来源：http://dali.fzhhl.top/Article/details/gtvlsjmbal.html

[R04] 位置参数
来源：http://dali.redwolf501.top/Article/details/gtovimrpql.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.birdmap.top/Article/details/gtqwgaimkh.html

[R05] 参数默认值
来源：http://dali.sysykeji.top/Article/details/gtwbyghimk.html

name="${1:-default}"
来源：http://dali.meibo888.top/Article/details/gtmqhwrait.html

[R06] 判断命令是否存在
来源：http://dali.yj202588.top/Article/details/gtkpndtqds.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.yvedp.cn/Article/details/gtsshtctac.html

[R07] if 判断文件
来源：http://dali.sysykeji.top/Article/details/gtvtrqpmyw.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.cucudq.cn/Article/details/gtksrtvzdt.html

[R08] 数值比较
来源：http://dali.shzxlz.cn/Article/details/gthawlerop.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.cheryme.top/Article/details/gtvfbiursr.html

[R09] 字符串比较
来源：http://dali.hysaishi.cn/Article/details/gtxxenaupd.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.chenlongwang.top/Article/details/gtchivmaib.html

[R10] 正则匹配
来源：http://dali.redwolf501.top/Article/details/gtpudhvcgq.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.zycfv.cn/Article/details/gtgqdioosd.html

[R11] case 多分支
来源：http://dali.guannengcc.top/Article/details/gtikziaexv.html

case "$1" in
来源：http://dali.yanxiufei.cn/Article/details/gtufpkexsl.html

start) echo "启动" ;;
来源：http://dali.nanxinkj.top/Article/details/gtzjwwlvlz.html

stop)  echo "停止" ;;
来源：http://dali.hammf.cn/Article/details/gtdrdnkskl.html

*)     echo "未知命令" ;;
来源：http://dali.9152youxi.cn/Article/details/gteyplfqvf.html

esac
来源：http://dali.yonumen.top/Article/details/gtjmmelmgl.html

[R12] for 遍历文件
来源：http://dali.yj202588.top/Article/details/gtgypxrdvx.html

for f in *.txt; do echo "$f"; done
来源：http://dali.fzhhl.top/Article/details/gtifztqmdr.html

[R13] for 计数循环
来源：http://dali.shanyushiyangkeji.top/Article/details/gtzzeazexb.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.ehwqpu.com/Article/details/gtczteasyl.html

[R14] C 风格 for
来源：http://dali.cucudq.cn/Article/details/gtrxfaxkqh.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.cdnleiting.top/Article/details/gtsbkeubol.html

[R15] while 逐行读文件
来源：http://dali.yonumen.top/Article/details/gtnnncxkez.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtclxallog.html

[R16] until 等待条件
来源：http://dali.jqgfzy.top/Article/details/gtkfwvxfoy.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.daxiang520.top/Article/details/gtzxesfahe.html

[R17] 数组定义与取值
来源：http://dali.vqdsnc.cn/Article/details/gtihcdfvzs.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.nanxuanxn.top/Article/details/gtaafauqiy.html

[R18] 遍历数组
来源：http://dali.cashguo.top/Article/details/gteyevkwsv.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.daxiang520.top/Article/details/gtsmshlmej.html

[R19] 数组长度
来源：http://dali.hywenlv.cn/Article/details/gteyfvbiee.html

echo "${#arr[@]}"
来源：http://dali.zhengqikj.top/Article/details/gtworizmrd.html

[R20] 关联数组（字典）
来源：http://dali.hammf.cn/Article/details/gtzrydcktz.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.zhixingplan.top/Article/details/gtrpcoajjt.html

[R21] 字符串长度
来源：http://dali.iojbl.cn/Article/details/gtoeztvzpr.html

echo "${#s}"
来源：http://dali.hnqzz.top/Article/details/gtciwgsoia.html

[R22] 截取子串
来源：http://dali.ybcxt.top/Article/details/gtrhjdiqtc.html

echo "${s:0:5}"
来源：http://dali.yongpay.top/Article/details/gtuywtvthr.html

[R23] 字符串替换
来源：http://dali.guannengcc.top/Article/details/gticqoxepb.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.jyoumei.cn/Article/details/gtanzukboo.html

[R24] 大小写转换
来源：http://dali.dashuyun.cn/Article/details/gtzjvvdkjv.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.hfpthk.cn/Article/details/gtvarcdeku.html

[R25] 去后缀 / 去前缀
来源：http://dali.hammf.cn/Article/details/gthwjstipp.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.gotoacloud.top/Article/details/gtlumdtoak.html

[R26] 命令替换
来源：http://dali.fzhhl.top/Article/details/gtvhsztlru.html

now=$(date +%F); echo "$now"
来源：http://dali.xuetiantiany.cn/Article/details/gtbbmwarkx.html

[R27] 算术展开
来源：http://dali.dianchejie.cn/Article/details/gttgjlzwgz.html

echo $((1 + 2 * 3))
来源：http://dali.yueranfly.top/Article/details/gtmvxitdcd.html

[R28] 浮点运算
来源：http://dali.shanyushiyangtech.top/Article/details/gtfgayuiid.html

echo "scale=2; 10/3" | bc
来源：http://dali.kuanghao11.cn/Article/details/gttetlakqo.html

[R29] 定义函数
来源：http://dali.feifeiyinyue.top/Article/details/gtkqhypfkf.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.jinyuanbaomall.cn/Article/details/gtgotruvkt.html

[R30] 函数返回状态码
来源：http://dali.meibo888.top/Article/details/gtsuaiagjj.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.sxryk.cn/Article/details/gtwfnalbqa.html

[R31] 局部变量
来源：http://dali.zhiwuduotai.top/Article/details/gtzlwtooid.html

f() { local x=1; echo "$x"; }
来源：http://dali.sweek.top/Article/details/gtctngtgan.html

[R32] 参数个数校验
来源：http://dali.gogol.net.cn/Article/details/gtlfvzdcuc.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.wangshuangyany.cn/Article/details/gtrmpqfztu.html

[R33] 捕获错误并提示行号
来源：http://dali.bjfxy.top/Article/details/gtbripejfd.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.hammf.cn/Article/details/gtjxvlfnnl.html

[R34] 退出时清理
来源：http://dali.meibo888.top/Article/details/gtjwfchaaq.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.svipenyu.cn/Article/details/gtusxrnddm.html

[R35] 后台执行并等待
来源：http://dali.ybcxt.top/Article/details/gtolpjesud.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.xylfe.cn/Article/details/gtqnmcybva.html

[R36] 并发执行多个任务
来源：http://dali.kuanghao11.cn/Article/details/gtofnfkcsy.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.nanxinkj.top/Article/details/gtodbxjksl.html

[R37] 把输出赋给变量
来源：http://dali.316326.xyz/Article/details/gtrgqwtfip.html

files=$(ls -1)
来源：http://dali.jianghu66.top/Article/details/gthplbmrjg.html

[R38] 管道串联
来源：http://dali.yangfankeji.com/Article/details/gteognzndx.html

cat a.txt | grep -i error | wc -l
来源：http://dali.c1oappe.top/Article/details/gtvxwyhldb.html

[R39] 重定向标准输出与错误
来源：http://dali.sufxvd.cn/Article/details/gttnlpavta.html

cmd > out.log 2>&1
来源：http://dali.svipenyu.cn/Article/details/gtvavwzyid.html

[R40] 追加写日志
来源：http://dali.guannengcc.top/Article/details/gtjbuysejt.html

echo "log" >> out.log
来源：http://dali.shuidangran.top/Article/details/gtirussqwv.html

[R41] 丢弃输出
来源：http://dali.aibaodan.cn/Article/details/gtzlgqjnvt.html

cmd >/dev/null 2>&1
来源：http://dali.hfpthk.cn/Article/details/gtyvzirdkc.html

[R42] 输入重定向
来源：http://dali.jyoumei.cn/Article/details/gtatksqtsn.html

wc -l < a.txt
来源：http://dali.ywan-chungtsiang.top/Article/details/gtzyfvakhc.html

[R43] 按名字查找文件
来源：http://dali.316326.xyz/Article/details/gttflutvyo.html

find . -name "*.log" -type f
来源：http://dali.fengsongda.top/Article/details/gtkedvpzbb.html

[R44] 按修改时间查找
来源：http://dali.redwolf501.top/Article/details/gtqmcwecyt.html

find . -mtime -7 -type f
来源：http://dali.jqgfzy.top/Article/details/gtzuyjwrmp.html

[R45] 批量删除
来源：http://dali.guannengcc.top/Article/details/gtmbrflqgj.html

find . -name "*.tmp" -delete
来源：http://dali.sysykeji.top/Article/details/gtdgflauwk.html

[R46] 递归替换文件内容
来源：http://dali.yonumen.top/Article/details/gtaluetuxf.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.yuxming.cn/Article/details/gtouilnppb.html

[R47] sed 单行替换
来源：http://dali.shuidangran.top/Article/details/gtnnwimsdf.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.yangfankeji.com/Article/details/gtyaeduflr.html

[R48] awk 取指定列
来源：http://dali.gaohongyu789.top/Article/details/gtoczxvmwd.html

awk '{print $1, $3}' a.txt
来源：http://dali.xinyue.icu/Article/details/gtswcermpu.html

[R49] awk 带条件
来源：http://dali.jiagoushi.top/Article/details/gtjkojbhis.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.shanyushiyangkeji.top/Article/details/gtmkiqqpqs.html

[R50] awk 求和
来源：http://dali.jlsjyb.cn/Article/details/gttqbbozoj.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gttzesvgll.html

[R51] 排序去重取前几
来源：http://dali.jiagoushi.top/Article/details/gtmgmbrsjx.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.andypj.xyz/Article/details/gtjouycrum.html

[R52] 统计行数
来源：http://dali.yanxiufei.cn/Article/details/gtbzehmwse.html

wc -l a.txt
来源：http://dali.birdmap.top/Article/details/gtmsupyqyv.html

[R53] 查看文件头与实时尾
来源：http://dali.hnqzz.top/Article/details/gtscbinpry.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.jianghu66.top/Article/details/gtcljhlndp.html

[R54] 比较两个文件
来源：http://dali.daxiang520.top/Article/details/gthnalayxd.html

diff a.txt b.txt
来源：http://dali.jinyuanbaomall.cn/Article/details/gtprdiyhgu.html

[R55] 压缩与解压
来源：http://dali.xuanzx.com/Article/details/gtlporsyin.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.snrcjt.cn/Article/details/gtlavydovy.html

[R56] 远程拷贝
来源：http://dali.kuanghao11.cn/Article/details/gtgmfvjnlj.html

scp file user@host:/path/
来源：http://dali.sxryk.cn/Article/details/gtfnckdxjz.html

[R57] 远程执行命令
来源：http://dali.c1oappe.top/Article/details/gtqizolacq.html

ssh user@host 'uptime'
来源：http://dali.chenlongwang.top/Article/details/gtrtyusfaz.html

[R58] 下载文件
来源：http://dali.zhoulong.xyz/Article/details/gtphtazzwt.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.kuanghao11.cn/Article/details/gtvdzngdds.html

[R59] 发 POST JSON
来源：http://dali.yanxiufei.cn/Article/details/gtkvlkkhqj.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.sysykeji.top/Article/details/gtyrfxyqxs.html

[R60] 只看 HTTP 状态码
来源：http://dali.svipenyu.cn/Article/details/gtoygetkej.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.shanyushiyangtech.top/Article/details/gtzwuurwbn.html

[R61] 磁盘占用
来源：http://dali.shuidangran.top/Article/details/gtrzdcpidc.html

df -h;  du -sh *
来源：http://dali.aibaodan.cn/Article/details/gtvwnkexfj.html

[R62] 找最占空间的文件
来源：http://dali.zhengqikj.top/Article/details/gtdxabtkcb.html

du -ah . | sort -rh | head -10
来源：http://dali.smart0.xyz/Article/details/gtfrysccrt.html

[R63] 内存与进程
来源：http://dali.dianchejie.cn/Article/details/gtkscelevd.html

free -h;  ps aux | grep nginx
来源：http://dali.havefunace.top/Article/details/gtollrnbuj.html

[R64] 结束进程
来源：http://dali.mhx1999.top/Article/details/gtcumuscps.html

kill -9 $(pgrep -f app.py)
来源：http://dali.jqgufenzy.top/Article/details/gtmngiukyd.html

[R65] 查看端口占用
来源：http://dali.shanyushiyangtech.top/Article/details/gtxtfgmgdt.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.dianchejie.cn/Article/details/gtqiruhgkm.html

[R66] 定时任务
来源：http://dali.jyoumei.cn/Article/details/gthjisknqh.html

crontab -e;  crontab -l
来源：http://dali.yueranfly.top/Article/details/gtapbkysht.html

[R67] 生成随机十六进制串
来源：http://dali.smart0.xyz/Article/details/gtwwxchxie.html

openssl rand -hex 16
来源：http://dali.ppjwa.cn/Article/details/gttvheurst.html

[R68] 计算文件校验值
来源：http://dali.cqqwz.cn/Article/details/gtdfteoxwl.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.jlsjyb.cn/Article/details/gtkdnvmwpn.html

[R69] 生成随机密码
来源：http://dali.yj20258888.top/Article/details/gtmziapfby.html

head -c 16 /dev/urandom | base64
来源：http://dali.bjfxy.top/Article/details/gtyakdypzv.html

[R70] 时间戳与互转
来源：http://dali.guannengcc.top/Article/details/gtuhqyswyj.html

date +%s;  date -d @1700000000
来源：http://dali.zhijiandao.cn/Article/details/gtzvsugztp.html

[R71] 日期格式化
来源：http://dali.xuanzx.com/Article/details/gtxvvxglhw.html


<!-- 参考信息 -->