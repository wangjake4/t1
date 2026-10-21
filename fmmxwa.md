代发 wailian999

SELECT *, ROW_NUMBER() OVER (PARTITION BY city ORDER BY age DESC) AS rn FROM users
来源：http://dali.hysaishi.cn/Article/details/gtgopnxfqw.html

) t WHERE rn = 1;
来源：http://dali.aibaodan.cn/Article/details/gtedaisklt.html

[Q35] 内连接
来源：http://dali.zdqjudy.top/Article/details/gtyxurzhhm.html

SELECT u.name, o.amount FROM users u JOIN orders o ON o.user_id = u.id;
来源：http://dali.cdnleiting.top/Article/details/gtgqbetyqt.html

[Q36] 左连接
来源：http://dali.daria6918.cn/Article/details/gtsakqlpyq.html

SELECT u.name, o.amount FROM users u LEFT JOIN orders o ON o.user_id = u.id;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtguhasceb.html

[Q37] 右连接
来源：http://dali.iojbl.cn/Article/details/gtflmyhyur.html

SELECT * FROM orders o RIGHT JOIN users u ON u.id = o.user_id;
来源：http://dali.zhixingplan.top/Article/details/gtxmipofzu.html

[Q38] 全外连接（PostgreSQL）
来源：http://dali.nanxuanxn.top/Article/details/gtjmpjshqb.html

SELECT * FROM a FULL OUTER JOIN b ON a.id = b.a_id;
来源：http://dali.kuanghao11.cn/Article/details/gtxzbgycde.html

[Q39] 自连接（查上下级）
来源：http://dali.havefunace.top/Article/details/gtfmcbjzzd.html

SELECT e.name, m.name AS manager FROM employees e
来源：http://dali.mhx1999.top/Article/details/gtginkvixh.html

LEFT JOIN employees m ON e.manager_id = m.id;
来源：http://dali.havefunace.top/Article/details/gtjqrihqwb.html

[Q40] 交叉连接（笛卡尔积）
来源：http://dali.iojbl.cn/Article/details/gtiynlslqd.html

SELECT * FROM colors CROSS JOIN sizes;
来源：http://dali.9152youxi.cn/Article/details/gtyrdhwwln.html

[Q41] 多表连接
来源：http://dali.fengsongda.top/Article/details/gtbgzseqfe.html

SELECT o.id, u.name, p.title FROM orders o
来源：http://dali.hfpthk.cn/Article/details/gtmhuypvqa.html

JOIN users u ON u.id = o.user_id
来源：http://dali.shuidangran.top/Article/details/gthbjmajos.html

JOIN products p ON p.id = o.product_id;
来源：http://dali.jqgfzy.top/Article/details/gtcbwfwnjr.html

[Q42] 连接条件附加过滤
来源：http://dali.c1oappe.top/Article/details/gtfnlkazbr.html

SELECT u.name, o.amount FROM users u
来源：http://dali.zdqjudy.top/Article/details/gtdsfmnqdb.html

JOIN orders o ON o.user_id = u.id AND o.amount > 100;
来源：http://dali.ppjwa.cn/Article/details/gtlyqqhare.html

[Q43] 标量子查询
来源：http://dali.yueranfly.top/Article/details/gtmuimktqn.html

SELECT name, (SELECT COUNT(*) FROM orders o WHERE o.user_id = u.id) AS cnt FROM users u;
来源：http://dali.svipenyu.cn/Article/details/gtuqwnqdgd.html

[Q44] IN 子查询
来源：http://dali.jinghuilouyu.cn/Article/details/gtnuackwiq.html

SELECT * FROM users WHERE id IN (SELECT user_id FROM orders);
来源：http://dali.jlsjyb.cn/Article/details/gtzgxlwikw.html

[Q45] EXISTS 判断存在
来源：http://dali.ybcxt.top/Article/details/gtkeoklrbe.html

SELECT * FROM users u WHERE EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.ehwqpu.com/Article/details/gtzyikejzc.html

[Q46] NOT EXISTS 判断不存在
来源：http://dali.yanxiufei.cn/Article/details/gtahngwosk.html

SELECT * FROM users u WHERE NOT EXISTS (SELECT 1 FROM orders o WHERE o.user_id = u.id);
来源：http://dali.shzxlz.cn/Article/details/gtlmycjild.html

[Q47] 与平均值比较
来源：http://dali.yueranfly.top/Article/details/gtgjzajemz.html

SELECT * FROM users WHERE age > (SELECT AVG(age) FROM users);
来源：http://dali.aibaodan.cn/Article/details/gtwgpogmza.html

[Q48] CTE 公用表表达式
来源：http://dali.shanyushiyangtech.top/Article/details/gtktimebwx.html

WITH t AS (SELECT city, COUNT(*) AS c FROM users GROUP BY city)
来源：http://dali.cashguo.top/Article/details/gtdfmoinex.html

SELECT * FROM t WHERE c > 5;
来源：http://dali.zycfv.cn/Article/details/gtpjkugxtu.html

[Q49] 更新单行
来源：http://dali.ppjwa.cn/Article/details/gtayymvall.html

UPDATE users SET status = 1 WHERE id = 10;
来源：http://dali.shzxlz.cn/Article/details/gtewqjiyvj.html

[Q50] 批量更新
来源：http://dali.gzhubu.top/Article/details/gtihxsimay.html

UPDATE users SET status = 2 WHERE created_at < '2024-01-01';
来源：http://dali.kuanghao11.cn/Article/details/gtmsnhhsby.html

[Q51] 用子查询更新
来源：http://dali.zhongyouzk.top/Article/details/gtetsfwwst.html

UPDATE users SET age = (SELECT MAX(age) FROM users) WHERE id = 1;
来源：http://dali.haohaochexian.top/Article/details/gtbnneityi.html

[Q52] 删除指定行
来源：http://dali.xuanzx.com/Article/details/gtaepegelm.html

DELETE FROM users WHERE id = 10;
来源：http://dali.fzhhl.top/Article/details/gticilibet.html

[Q53] 按条件删除
来源：http://dali.guowangkeji.top/Article/details/gthxyyjyhu.html

DELETE FROM orders WHERE created_at < '2020-01-01';
来源：http://dali.jiagoushi.top/Article/details/gtytbpxxxi.html

[Q54] 清空表
来源：http://dali.guannengcc.top/Article/details/gtocgbfcga.html

TRUNCATE TABLE logs;
来源：http://dali.aizwys.cn/Article/details/gtyyxywnik.html

[Q55] 排名（并列占位）
来源：http://dali.jinqigufen.top/Article/details/gtyvygfqtz.html

SELECT name, RANK() OVER (ORDER BY score DESC) AS rk FROM scores;
来源：http://dali.jinghuilouyu.cn/Article/details/gtnengyuby.html

[Q56] 密集排名（并列不占位）
来源：http://dali.nanxinkj.top/Article/details/gtdghygqtp.html

SELECT name, DENSE_RANK() OVER (ORDER BY score DESC) FROM scores;
来源：http://dali.tanke756.top/Article/details/gtqjrjubuk.html

[Q57] 行号
来源：http://dali.kuanghao11.cn/Article/details/gtinhjpqyu.html

SELECT ROW_NUMBER() OVER (ORDER BY id) AS seq FROM users;
来源：http://dali.fengsongda.top/Article/details/gtsmqatroq.html

[Q58] 累计求和
来源：http://dali.zhijiandao.cn/Article/details/gtinznqpiz.html

SELECT id, amount, SUM(amount) OVER (ORDER BY id) AS running FROM orders;
来源：http://dali.316326.xyz/Article/details/gtqjpjsrdn.html

[Q59] 分组内累计
来源：http://dali.redwolf501.top/Article/details/gtnrgohhyb.html

SELECT city, id, SUM(amount) OVER (PARTITION BY city ORDER BY id) FROM orders;
来源：http://dali.zhaomingkeji.xyz/Article/details/gtdeuxmnpz.html

[Q60] 取上一行 / 下一行
来源：http://dali.ppjwa.cn/Article/details/gtebtxhcdg.html

SELECT id, LAG(amount) OVER (ORDER BY id) AS prev,
来源：http://dali.haohaochexian.top/Article/details/gtqztzhxjf.html

LEAD(amount) OVER (ORDER BY id) AS next FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gtjnfdhany.html

[Q61] 移动平均
来源：http://dali.jinyuanbaomall.cn/Article/details/gtbipkform.html

SELECT id, AVG(amount) OVER (ORDER BY id ROWS BETWEEN 2 PRECEDING AND CURRENT ROW) FROM orders;
来源：http://dali.yanxiufei.cn/Article/details/gtrtxlddxh.html

[Q62] 分组占比
来源：http://dali.sysykeji.top/Article/details/gtgfjosynm.html

SELECT city, COUNT(*) * 100.0 / SUM(COUNT(*)) OVER () AS pct FROM users GROUP BY city;
来源：http://dali.ydzc1.top/Article/details/gtdavhnzfw.html

[Q63] 开启事务
来源：http://dali.ivvv.top/Article/details/gtctpbklkt.html

START TRANSACTION;                -- 或 BEGIN
来源：http://dali.snrcjt.cn/Article/details/gtoaagbyws.html

[Q64] 提交事务
来源：http://dali.feifeiyinyue.top/Article/details/gtlhhgovdg.html

COMMIT;
来源：http://dali.yueranfly.top/Article/details/gtetlrzpxj.html

[Q65] 回滚事务
来源：http://dali.guannengcc.top/Article/details/gtbbcaefbe.html

ROLLBACK;
来源：http://dali.yongpay.top/Article/details/gtlmcepoce.html

[Q66] 行锁查询
来源：http://dali.yueranfly.top/Article/details/gtqxhdurjq.html

SELECT * FROM users WHERE id = 1 FOR UPDATE;
来源：http://dali.havefunace.top/Article/details/gtbatuehmw.html

[Q67] 设置隔离级别
来源：http://dali.hongshengwenyu.top/Article/details/gtxqphpcio.html

SET TRANSACTION ISOLATION LEVEL READ COMMITTED;
来源：http://dali.nwbrower.top/Article/details/gtwdsrqfxw.html

[Q68] 保存点
来源：http://dali.quarkkingdee.top/Article/details/gtzvgejyru.html

SAVEPOINT sp1;
来源：http://dali.aizwys.cn/Article/details/gtbvirrsol.html

ROLLBACK TO sp1;
来源：http://dali.shzxlz.cn/Article/details/gtlxlfursr.html

[Q69] 查看执行计划
来源：http://dali.cashguo.top/Article/details/gtdasrodpu.html

EXPLAIN SELECT * FROM users WHERE email = 'a@a.com';
来源：http://dali.meibo888.top/Article/details/gtwxuqdyjm.html

[Q70] 更新统计信息
来源：http://dali.cdnleiting.top/Article/details/gtfzaennnb.html

ANALYZE TABLE users;
来源：http://dali.xylfe.cn/Article/details/gtvivqdyot.html

[Q71] 查看建表语句
来源：http://dali.cheryme.top/Article/details/gtwvozpsrc.html

SHOW CREATE TABLE users;          -- PostgreSQL: \d users
来源：http://dali.cqqwz.cn/Article/details/gtnizmwpuo.html

[Q72] 查看索引
来源：http://dali.316326.xyz/Article/details/gtcqrufanj.html

SHOW INDEX FROM users;
来源：http://dali.yuanzhike.top/Article/details/gtvbaglzdr.html

[Q73] 查看表状态
来源：http://dali.ywan-chungtsiang.top/Article/details/gtnsgzklbg.html

SHOW TABLE STATUS LIKE 'users';
来源：http://dali.jiagoushi.top/Article/details/gtozwcfgfc.html

[Q74] 强制使用索引
来源：http://dali.andypj.xyz/Article/details/gttaghmykv.html

SELECT * FROM users FORCE INDEX (idx_users_email) WHERE email = 'x';
来源：http://dali.tianlin.xyz/Article/details/gtuvagkixd.html

[Q75] 日期格式化
来源：http://dali.shangyingyoupin.top/Article/details/gtangdxezf.html

SELECT DATE_FORMAT(created_at, '%Y-%m') FROM orders;
来源：http://dali.yonumen.top/Article/details/gteiemewxb.html

-- PostgreSQL: to_char(created_at, 'YYYY-MM')
来源：http://dali.shuidangran.top/Article/details/gtndqxhtcu.html

[Q76] 按天统计
来源：http://dali.xuanzx.com/Article/details/gtubbwfeom.html

SELECT DATE(created_at) AS d, COUNT(*) FROM orders GROUP BY d;
来源：http://dali.guannengcc.top/Article/details/gtrmnajusr.html

[Q77] 时间加减
来源：http://dali.pycfn.com/Article/details/gtbhbltugd.html

SELECT DATE_ADD(NOW(), INTERVAL 7 DAY);   -- PostgreSQL: now() + interval '7 day'
来源：http://dali.snrcjt.cn/Article/details/gtbdldhrjv.html

[Q78] 当前时间
来源：http://dali.jinqigfzy.top/Article/details/gtfjsqvpuo.html

SELECT NOW(), CURDATE(), UNIX_TIMESTAMP();
来源：http://dali.zhixingplan.top/Article/details/gtqgsxjfdl.html

[Q79] 字符串拼接
来源：http://dali.cucudq.cn/Article/details/gtsdqmtqlz.html

SELECT CONCAT(first_name, ' ', last_name) FROM users;   -- PostgreSQL: ||
来源：http://dali.cheryme.top/Article/details/gtemchnaiv.html

[Q80] 字符串截取
来源：http://dali.gzhubu.top/Article/details/gtdvivptrc.html

SELECT SUBSTRING(name, 1, 3) FROM users;
来源：http://dali.xylfe.cn/Article/details/gtqulaprpo.html

[Q81] 字符串替换
来源：http://dali.feifeiyinyue.top/Article/details/gtnwrbdsth.html

SELECT REPLACE(name, 'a', 'b') FROM users;
来源：http://dali.yj20258888.top/Article/details/gtrrbkqnui.html

[Q82] 字符长度与字节长度
来源：http://dali.ehwqpu.com/Article/details/gtxmmtozlv.html

SELECT CHAR_LENGTH(name), LENGTH(name) FROM users;
来源：http://dali.shuidangran.top/Article/details/gtnxogncuc.html

[Q83] 大小写转换
来源：http://dali.yongpay.top/Article/details/gtyuhbqwjt.html

SELECT UPPER(name), LOWER(name) FROM users;
来源：http://dali.haohaochexian.top/Article/details/gtabtcwawn.html

[Q84] 去除首尾空格
来源：http://dali.daxiang520.top/Article/details/gtoaunwtzz.html

SELECT TRIM(name) FROM users;
来源：http://dali.fengsongda.top/Article/details/gtourtoniu.html

[Q85] 数值取整
来源：http://dali.wangshuangyany.cn/Article/details/gtulcywigr.html

SELECT ROUND(3.567, 2), CEIL(3.1), FLOOR(3.9);
来源：http://dali.guannengcc.top/Article/details/gtjxkundwb.html

[Q86] 读取 JSON 字段
来源：http://dali.aizwys.cn/Article/details/gtnebdnddz.html

SELECT data->>'$.name' FROM t;    -- PostgreSQL: data->>'name'
来源：http://dali.c1oappe.top/Article/details/gtihxqtrgv.html

[Q87] JSON 字段做条件
来源：http://dali.ivvv.top/Article/details/gtrwafdwuy.html

SELECT * FROM t WHERE JSON_EXTRACT(data, '$.age') > 18;
来源：http://dali.nanxinkj.top/Article/details/gtxpldlfom.html

[Q88] 行转列（条件聚合）
来源：http://dali.zhongyouzk.top/Article/details/gtxwbvgwsz.html

SELECT SUM(CASE WHEN status = 1 THEN 1 ELSE 0 END) AS s1,
来源：http://dali.guannengcc.top/Article/details/gtymshosms.html

SUM(CASE WHEN status = 2 THEN 1 ELSE 0 END) AS s2 FROM users;
来源：http://dali.pycfn.com/Article/details/gttzgfiucu.html

[Q89] 判断表是否存在
来源：http://dali.vqdsnc.cn/Article/details/gtuginlpof.html

SELECT COUNT(*) FROM information_schema.tables WHERE table_name = 'users';
来源：http://dali.cucudq.cn/Article/details/gtawjntmeu.html

[Q90] 生成序号列
来源：http://dali.9152youxi.cn/Article/details/gthdwmdzhu.html

SELECT @i := @i + 1 AS seq, name FROM users, (SELECT @i := 0) x;
来源：http://dali.hnxiangtu.top/Article/details/gthcdailnp.html

================================================================================
来源：http://dali.zhongyouzk.top/Article/details/gtddyzhrti.html

R. Bash 专题
来源：http://dali.quarkkingdee.top/Article/details/gtcctrkxri.html

================================================================================
来源：http://dali.shanyushiyangtech.top/Article/details/gtglvyostw.html

[R01] shebang 与严格模式
来源：http://dali.zhaomingkeji.xyz/Article/details/gtiyphfhgi.html

#!/usr/bin/env bash
来源：http://dali.yj20258.top/Article/details/gtyeixoglz.html

set -euo pipefail
来源：http://dali.yuanzhike.top/Article/details/gtxbdionmb.html

[R02] 变量赋值与使用
来源：http://dali.sysykeji.top/Article/details/gtvbfgwnjg.html

name="Tom"; echo "$name"
来源：http://dali.shanyushiyangtech.top/Article/details/gtsnjequci.html

[R03] 只读变量
来源：http://dali.jqgufenzy.top/Article/details/gtshndcbhg.html

readonly PI=3.14
来源：http://dali.svipenyu.cn/Article/details/gtpafubtlb.html

[R04] 位置参数
来源：http://dali.meibo888.top/Article/details/gttvxvknmq.html

echo "$0 $1 $2 | 全部: $@ | 个数: $#"
来源：http://dali.yuanzhike.top/Article/details/gtnfkwicms.html

[R05] 参数默认值
来源：http://dali.cheryme.top/Article/details/gtqntdybqv.html

name="${1:-default}"
来源：http://dali.gotoacloud.top/Article/details/gtmnjrmutj.html

[R06] 判断命令是否存在
来源：http://dali.ywan-chungtsiang.top/Article/details/gttncywmzl.html

command -v git >/dev/null || { echo "缺少 git"; exit 1; }
来源：http://dali.zdqjudy.top/Article/details/gtpltgfswt.html

[R07] if 判断文件
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtanzwnxur.html

if [[ -f "$f" ]]; then echo "是文件"; fi
来源：http://dali.yongpay.top/Article/details/gtytefqmdv.html

[R08] 数值比较
来源：http://dali.ydzc1.top/Article/details/gtspsakzej.html

if (( a > b )); then echo "a 更大"; fi
来源：http://dali.yonumen.top/Article/details/gthimphdxf.html

[R09] 字符串比较
来源：http://dali.jqgfzy.top/Article/details/gtamkqxrfj.html

if [[ "$a" == "$b" ]]; then echo "相等"; fi
来源：http://dali.xuetiantiany.cn/Article/details/gtymaetmol.html

[R10] 正则匹配
来源：http://dali.gzhubu.top/Article/details/gtdpvduvzf.html

if [[ "$s" =~ ^[0-9]+$ ]]; then echo "纯数字"; fi
来源：http://dali.shanyushiyangkeji.top/Article/details/gtwwlstmvg.html

[R11] case 多分支
来源：http://dali.yuanzhike.top/Article/details/gtvpbsqaiw.html

case "$1" in
来源：http://dali.xuetiantiany.cn/Article/details/gtfoqcdoev.html

start) echo "启动" ;;
来源：http://dali.feifeiyinyue.top/Article/details/gtbeutudye.html

stop)  echo "停止" ;;
来源：http://dali.daxiang520.top/Article/details/gtbvudtrzn.html

*)     echo "未知命令" ;;
来源：http://dali.shanyushiyangkeji.top/Article/details/gtgvsrrada.html

esac
来源：http://dali.tianlin.xyz/Article/details/gtlhhogixy.html

[R12] for 遍历文件
来源：http://dali.yonumen.top/Article/details/gtfkuazqsd.html

for f in *.txt; do echo "$f"; done
来源：http://dali.fzhhl.top/Article/details/gtieyceitf.html

[R13] for 计数循环
来源：http://dali.meibo888.top/Article/details/gtjiysyurp.html

for i in {1..10}; do echo "$i"; done
来源：http://dali.jyoumei.cn/Article/details/gtbtflqbwf.html

[R14] C 风格 for
来源：http://dali.vqdsnc.cn/Article/details/gtrpfdicrg.html

for ((i = 0; i < 10; i++)); do echo "$i"; done
来源：http://dali.smart0.xyz/Article/details/gtgivzlxpu.html

[R15] while 逐行读文件
来源：http://dali.zhengqikj.top/Article/details/gtppqvsldi.html

while IFS= read -r line; do echo "$line"; done < file.txt
来源：http://dali.feifeiyinyue.top/Article/details/gtsholkmbq.html

[R16] until 等待条件
来源：http://dali.hysaishi.cn/Article/details/gtysqotfqj.html

until [[ -f done.flag ]]; do sleep 1; done
来源：http://dali.smart0.xyz/Article/details/gtphfvjnjv.html

[R17] 数组定义与取值
来源：http://dali.xinyue.icu/Article/details/gtspqcktdn.html

arr=(a b c); echo "${arr[0]}"
来源：http://dali.hywenlv.cn/Article/details/gtbgcyqsof.html

[R18] 遍历数组
来源：http://dali.nanxinkj.top/Article/details/gthojytilr.html

for x in "${arr[@]}"; do echo "$x"; done
来源：http://dali.gaohongyu789.top/Article/details/gtpyxudhie.html

[R19] 数组长度
来源：http://dali.zhongyouzk.top/Article/details/gtpsfworoq.html

echo "${#arr[@]}"
来源：http://dali.yj202588.top/Article/details/gtxefajhmb.html

[R20] 关联数组（字典）
来源：http://dali.tianlin.xyz/Article/details/gtkuydczfi.html

declare -A m; m[k]=v; echo "${m[k]}"
来源：http://dali.jqgfzy.top/Article/details/gtxfwfxfpx.html

[R21] 字符串长度
来源：http://dali.316326.xyz/Article/details/gttkhxsoix.html

echo "${#s}"
来源：http://dali.zhixingplan.top/Article/details/gtpfqskiya.html

[R22] 截取子串
来源：http://dali.316326.xyz/Article/details/gtzunxvwkp.html

echo "${s:0:5}"
来源：http://dali.jlsjyb.cn/Article/details/gtdrkygfbr.html

[R23] 字符串替换
来源：http://dali.ppjwa.cn/Article/details/gthdspqngw.html

echo "${s/old/new}"; echo "${s//old/new}"    # 后者全部替换
来源：http://dali.hongshengwenyu.top/Article/details/gtkoaapexn.html

[R24] 大小写转换
来源：http://dali.dianchejie.cn/Article/details/gtiaibxowk.html

echo "${s^^}"; echo "${s,,}"
来源：http://dali.shzxlz.cn/Article/details/gtekanzwlo.html

[R25] 去后缀 / 去前缀
来源：http://dali.wangdashe.top/Article/details/gtnjqizjea.html

echo "${f%.txt}"; echo "${f#./}"
来源：http://dali.hfpthk.cn/Article/details/gtydaatzdd.html

[R26] 命令替换
来源：http://dali.yuxming.cn/Article/details/gtkftajwun.html

now=$(date +%F); echo "$now"
来源：http://dali.yonumen.top/Article/details/gtugdvjtkl.html

[R27] 算术展开
来源：http://dali.haohaochexian.top/Article/details/gtpbvuocms.html

echo $((1 + 2 * 3))
来源：http://dali.daria6918.cn/Article/details/gtjckzxpdd.html

[R28] 浮点运算
来源：http://dali.jianghu66.top/Article/details/gtktxaxemf.html

echo "scale=2; 10/3" | bc
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtyxfcxkyt.html

[R29] 定义函数
来源：http://dali.guannengcc.top/Article/details/gtefkfvdyo.html

add() { echo $(($1 + $2)); }; add 1 2
来源：http://dali.cucudq.cn/Article/details/gtfuinyhbn.html

[R30] 函数返回状态码
来源：http://dali.hywenlv.cn/Article/details/gtfsbxksbz.html

f() { return 0; }; f || echo "失败了"
来源：http://dali.smart0.xyz/Article/details/gtocyyizmk.html

[R31] 局部变量
来源：http://dali.tanke756.top/Article/details/gtntutypef.html

f() { local x=1; echo "$x"; }
来源：http://dali.smart0.xyz/Article/details/gtptgkvsex.html

[R32] 参数个数校验
来源：http://dali.zhixingplan.top/Article/details/gtcddyfixj.html

[[ $# -lt 2 ]] && { echo "用法: $0 a b"; exit 1; }
来源：http://dali.shzxlz.cn/Article/details/gtzudbdxbh.html

[R33] 捕获错误并提示行号
来源：http://dali.havefunace.top/Article/details/gtxpvjzvot.html

trap 'echo "出错于第 $LINENO 行"' ERR
来源：http://dali.yvedp.cn/Article/details/gtfpkcfgpy.html

[R34] 退出时清理
来源：http://dali.jianghu66.top/Article/details/gtnjqwgacb.html

trap 'rm -f "$tmp"' EXIT
来源：http://dali.meibo888.top/Article/details/gtkzfuysoj.html

[R35] 后台执行并等待
来源：http://dali.feifeiyinyue.top/Article/details/gtrmqgsxfg.html

sleep 5 & pid=$!; wait "$pid"
来源：http://dali.316326.xyz/Article/details/gtwmypdpit.html

[R36] 并发执行多个任务
来源：http://dali.ehwqpu.com/Article/details/gtprroioph.html

for i in 1 2 3; do (sleep 1; echo "$i") & done; wait
来源：http://dali.shzxlz.cn/Article/details/gtkvaesazd.html

[R37] 把输出赋给变量
来源：http://dali.ehwqpu.com/Article/details/gtnrqztmag.html

files=$(ls -1)
来源：http://dali.xinyue.icu/Article/details/gtwuyopehx.html

[R38] 管道串联
来源：http://dali.kuanghao11.cn/Article/details/gtkalafphs.html

cat a.txt | grep -i error | wc -l
来源：http://dali.quarkkingdee.top/Article/details/gtlvzovxqv.html

[R39] 重定向标准输出与错误
来源：http://dali.cucudq.cn/Article/details/gtljebwotw.html

cmd > out.log 2>&1
来源：http://dali.sxryk.cn/Article/details/gtdoouemhi.html

[R40] 追加写日志
来源：http://dali.wangdashe.top/Article/details/gtaigstgdd.html

echo "log" >> out.log
来源：http://dali.hnxiangtu.top/Article/details/gthqicwegb.html

[R41] 丢弃输出
来源：http://dali.fzhhl.top/Article/details/gtdcndnqvh.html

cmd >/dev/null 2>&1
来源：http://dali.hnqzz.top/Article/details/gtwoeohsve.html

[R42] 输入重定向
来源：http://dali.zhiwuduotai.top/Article/details/gtkxuekktl.html

wc -l < a.txt
来源：http://dali.zhaomingkeji.xyz/Article/details/gtggvfneof.html

[R43] 按名字查找文件
来源：http://dali.tianlin.xyz/Article/details/gtxcmjontp.html

find . -name "*.log" -type f
来源：http://dali.ppjwa.cn/Article/details/gtdjghcdon.html

[R44] 按修改时间查找
来源：http://dali.quarkkingdee.top/Article/details/gtklvfroel.html

find . -mtime -7 -type f
来源：http://dali.yanxiufei.cn/Article/details/gtljnpezqd.html

[R45] 批量删除
来源：http://dali.vqdsnc.cn/Article/details/gtpapflnrb.html

find . -name "*.tmp" -delete
来源：http://dali.shzxlz.cn/Article/details/gtpxhgekou.html

[R46] 递归替换文件内容
来源：http://dali.feifeiyinyue.top/Article/details/gtzdhlaszm.html

grep -rl 'old' . | xargs sed -i 's/old/new/g'
来源：http://dali.zhijiandao.cn/Article/details/gtlqhdqrtq.html

[R47] sed 单行替换
来源：http://dali.xingfuxueyuan.xyz/Article/details/gtygfidrxe.html

sed -i 's/foo/bar/g' a.txt
来源：http://dali.havefunace.top/Article/details/gtbtrqeexv.html

[R48] awk 取指定列
来源：http://dali.jianghu66.top/Article/details/gtkqahuvan.html

awk '{print $1, $3}' a.txt
来源：http://dali.havefunace.top/Article/details/gtlcnjcgbg.html

[R49] awk 带条件
来源：http://dali.chenlongwang.top/Article/details/gttqxnggys.html

awk -F, '$3 > 100 {print $1}' a.csv
来源：http://dali.meibo888.top/Article/details/gtbuujzzmy.html

[R50] awk 求和
来源：http://dali.9152youxi.cn/Article/details/gtakfwatka.html

awk '{s += $2} END {print s}' a.txt
来源：http://dali.yuanzhike.top/Article/details/gticwvuwhr.html

[R51] 排序去重取前几
来源：http://dali.hnxiangtu.top/Article/details/gtqelsdmgp.html

sort a.txt | uniq -c | sort -rn | head
来源：http://dali.yanxiufei.cn/Article/details/gtttleebvt.html

[R52] 统计行数
来源：http://dali.yvedp.cn/Article/details/gtvswqccto.html

wc -l a.txt
来源：http://dali.svipenyu.cn/Article/details/gtoqfvfdua.html

[R53] 查看文件头与实时尾
来源：http://dali.yangfankeji.com/Article/details/gtuzqsowfg.html

head -n 20 a.txt;  tail -f -n 100 app.log
来源：http://dali.havefunace.top/Article/details/gtsupishfz.html

[R54] 比较两个文件
来源：http://dali.shzxlz.cn/Article/details/gttfgxcdzc.html

diff a.txt b.txt
来源：http://dali.jlsjyb.cn/Article/details/gtaukbxqvs.html

[R55] 压缩与解压
来源：http://dali.mhx1999.top/Article/details/gtvalquugr.html

tar -czf x.tar.gz dir/;  tar -xzf x.tar.gz
来源：http://dali.zhongyouzk.top/Article/details/gtytywmktj.html

[R56] 远程拷贝
来源：http://dali.fzhhl.top/Article/details/gthypgxpoq.html

scp file user@host:/path/
来源：http://dali.tian-w.cn/Article/details/gtcemybbvu.html

[R57] 远程执行命令
来源：http://dali.0kj1m.cn/Article/details/gtftgepery.html

ssh user@host 'uptime'
来源：http://dali.zhaomingkeji.xyz/Article/details/gtnrvjxnkh.html

[R58] 下载文件
来源：http://dali.zdqjudy.top/Article/details/gtcgnmscrw.html

curl -LO https://a.com/file.zip;  wget https://a.com/file.zip
来源：http://dali.yongpay.top/Article/details/gtebakjzrx.html

[R59] 发 POST JSON
来源：http://dali.hfpthk.cn/Article/details/gtrjltgpea.html

curl -X POST -H 'Content-Type: application/json' -d '{"a":1}' https://api.example.com
来源：http://dali.xinyue.icu/Article/details/gtlgigjxxv.html

[R60] 只看 HTTP 状态码
来源：http://dali.nanxuanxn.top/Article/details/gtwcgewpsq.html

curl -s -o /dev/null -w "%{http_code}\n" https://a.com
来源：http://dali.pengpengdd.cyou/Article/details/gthrooeyjc.html

[R61] 磁盘占用
来源：http://dali.ehwqpu.com/Article/details/gtmchvrufe.html

df -h;  du -sh *
来源：http://dali.sxryk.cn/Article/details/gtgbyfmreu.html

[R62] 找最占空间的文件
来源：http://dali.shanyushiyangtech.top/Article/details/gtwzdkppzz.html

du -ah . | sort -rh | head -10
来源：http://dali.jinghuilouyu.cn/Article/details/gtxmqnybfa.html

[R63] 内存与进程
来源：http://dali.shzxlz.cn/Article/details/gtsixxbgpj.html

free -h;  ps aux | grep nginx
来源：http://dali.cqqwz.cn/Article/details/gtgoiapecg.html

[R64] 结束进程
来源：http://dali.smart0.xyz/Article/details/gtrqurgtnk.html

kill -9 $(pgrep -f app.py)
来源：http://dali.gaohongyu789.top/Article/details/gtmkfitzsj.html

[R65] 查看端口占用
来源：http://dali.jqgufenzy.top/Article/details/gtmkmbzced.html

ss -tlnp | grep 8080;  lsof -i:8080
来源：http://dali.guannengcc.top/Article/details/gtwrwbdfoy.html

[R66] 定时任务
来源：http://dali.jqgfzy.top/Article/details/gtnbunopcq.html

crontab -e;  crontab -l
来源：http://dali.xziqi.cn/Article/details/gtylofbbyr.html

[R67] 生成随机十六进制串
来源：http://dali.guannengcc.top/Article/details/gtoipjwope.html

openssl rand -hex 16
来源：http://dali.jiagoushi.top/Article/details/gtsnvyawus.html

[R68] 计算文件校验值
来源：http://dali.aibaodan.cn/Article/details/gtzoutczqu.html

sha256sum a.txt;  md5sum a.txt
来源：http://dali.bjfxy.top/Article/details/gtblqshfar.html

[R69] 生成随机密码
来源：http://dali.yvedp.cn/Article/details/gtoivfalxw.html

head -c 16 /dev/urandom | base64
来源：http://dali.yonumen.top/Article/details/gtpwwrqeuc.html

[R70] 时间戳与互转
来源：http://dali.nanxinkj.top/Article/details/gtsrkuifzw.html

date +%s;  date -d @1700000000
来源：http://dali.aibaodan.cn/Article/details/gtsegucezl.html

[R71] 日期格式化
来源：http://dali.0kj1m.cn/Article/details/gtvcgpwsno.html

date +"%Y-%m-%d %H:%M:%S"
来源：http://dali.jinqigufen.top/Article/details/gtmzmaeosg.html

[R72] 等待端口就绪
来源：http://dali.zhoulong.xyz/Article/details/gtvydwaexg.html

until nc -z localhost 3306; do sleep 1; done
来源：http://dali.nwbrower.top/Article/details/gttwuhbzhd.html

[R73] 分割大日志
来源：http://dali.zhijiandao.cn/Article/details/gtzihzrptt.html

split -l 1000 big.log part_
来源：http://dali.zhoulong.xyz/Article/details/gtkewowwqx.html

[R74] 批量重命名
来源：http://dali.zhoulong.xyz/Article/details/gtmtzfxvgc.html

for f in *.jpeg; do mv "$f" "${f%.jpeg}.jpg"; done
来源：http://dali.hammf.cn/Article/details/gtfjrpgeny.html

[R75] 导出环境变量
来源：http://dali.jiagoushi.top/Article/details/gtbcskuihu.html

export PATH="$HOME/bin:$PATH"
来源：http://dali.fzhhl.top/Article/details/gtaingwfdd.html

[R76] 使用临时文件
来源：http://dali.chenlongwang.top/Article/details/gtnpbfuslx.html

tmp=$(mktemp); trap 'rm -f "$tmp"' EXIT
来源：http://dali.cqqwz.cn/Article/details/gteaeuxalq.html

[R77] 读取用户输入
来源：http://dali.dashuyun.cn/Article/details/gtadmpdpme.html

read -rp "请输入: " ans
来源：http://dali.pycfn.com/Article/details/gtdzwqypyg.html

[R78] 交互式菜单
来源：http://dali.nanxinkj.top/Article/details/gtzxmcxxeh.html

select opt in a b c; do echo "$opt"; break; done
来源：http://dali.jianghu66.top/Article/details/gtkfqifetz.html

[R79] 解析命令行选项
来源：http://dali.haohaochexian.top/Article/details/gtaltxzroa.html

while getopts "v:f:" o; do case $o in v) V=$OPTARG ;; f) F=$OPTARG ;; esac; done
来源：http://dali.cqqwz.cn/Article/details/gtgxnamyek.html

[R80] 查看脚本执行耗时
来源：http://dali.guowangkeji.top/Article/details/gtzsaixqzi.html

time ./run.sh
来源：http://dali.ppjwa.cn/Article/details/gtykuazbat.html

================================================================================
来源：http://dali.jqgufenzy.top/Article/details/gtzlvolpap.html

S. C / C++ 专题
来源：http://dali.shanyushiyangkeji.top/Article/details/gtcbzqbgqj.html

================================================================================
来源：http://dali.cheryme.top/Article/details/gttgxqovtr.html

[S01] C：Hello World
来源：http://dali.fzhhl.top/Article/details/gtvnoapuhb.html

#include <stdio.h>
来源：http://dali.xuetiantiany.cn/Article/details/gtqzwjgtzi.html

int main(void) { printf("Hello\n"); return 0; }
来源：http://dali.yueranfly.top/Article/details/gtkpdfunax.html

[S02] C：变量与格式化输出
来源：http://dali.feifeiyinyue.top/Article/details/gttnjzprge.html

int a = 10; printf("%d\n", a);
来源：http://dali.feifeiyinyue.top/Article/details/gthsvnzlvd.html

[S03] C：读入整数
来源：http://dali.yuxming.cn/Article/details/gtghroyxco.html


<!-- 参考信息 -->